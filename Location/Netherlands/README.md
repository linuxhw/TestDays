Linux in Netherlands - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in Netherlands.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Netherlands/Desktop/README.md) and [notebooks](/Location/Netherlands/Notebook/README.md).

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

Total: 5841

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | FRS780M                     | Desktop     | [3066c1772f](https://linux-hardware.org/?probe=3066c1772f) | Jul 01, 2023 |
| Acer          | FRS780M                     | Desktop     | [4f8ad26557](https://linux-hardware.org/?probe=4f8ad26557) | Jul 01, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [7b546735a4](https://linux-hardware.org/?probe=7b546735a4) | Jun 30, 2023 |
| Lenovo        | ThinkPad L512 44444NG       | Notebook    | [300a79aa88](https://linux-hardware.org/?probe=300a79aa88) | Jun 30, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [70ce1e280f](https://linux-hardware.org/?probe=70ce1e280f) | Jun 30, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [b5e0044759](https://linux-hardware.org/?probe=b5e0044759) | Jun 30, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [64e81a22a5](https://linux-hardware.org/?probe=64e81a22a5) | Jun 29, 2023 |
| ASUSTek       | X751MA                      | Notebook    | [b36ca5687c](https://linux-hardware.org/?probe=b36ca5687c) | Jun 29, 2023 |
| Acer          | Aspire 5745G                | Notebook    | [c3394b9eb0](https://linux-hardware.org/?probe=c3394b9eb0) | Jun 28, 2023 |
| Dell          | Latitude 7370               | Notebook    | [cb11921012](https://linux-hardware.org/?probe=cb11921012) | Jun 28, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [3ef19cf418](https://linux-hardware.org/?probe=3ef19cf418) | Jun 28, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [1ef1762ac3](https://linux-hardware.org/?probe=1ef1762ac3) | Jun 28, 2023 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [e39c7f5f6f](https://linux-hardware.org/?probe=e39c7f5f6f) | Jun 28, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [771e2e233a](https://linux-hardware.org/?probe=771e2e233a) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [3ea9e41d03](https://linux-hardware.org/?probe=3ea9e41d03) | Jun 28, 2023 |
| Lenovo        | ThinkPad X280 20KF001RUK    | Notebook    | [a1da72b9a5](https://linux-hardware.org/?probe=a1da72b9a5) | Jun 27, 2023 |
| Intel Clie... | LAPRC710                    | Notebook    | [5aabe7850a](https://linux-hardware.org/?probe=5aabe7850a) | Jun 27, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [e1b714fdf1](https://linux-hardware.org/?probe=e1b714fdf1) | Jun 27, 2023 |
| Gigabyte      | AB350M-D3H-CF               | Desktop     | [c73458700f](https://linux-hardware.org/?probe=c73458700f) | Jun 27, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [e16689358e](https://linux-hardware.org/?probe=e16689358e) | Jun 26, 2023 |
| HP            | 8599                        | Desktop     | [d72522f488](https://linux-hardware.org/?probe=d72522f488) | Jun 26, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [da86501858](https://linux-hardware.org/?probe=da86501858) | Jun 26, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [f5e04da161](https://linux-hardware.org/?probe=f5e04da161) | Jun 26, 2023 |
| MSI           | GF75 Thin 9SC               | Notebook    | [554a954c22](https://linux-hardware.org/?probe=554a954c22) | Jun 26, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [9c925666a5](https://linux-hardware.org/?probe=9c925666a5) | Jun 26, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [ea814b3f7b](https://linux-hardware.org/?probe=ea814b3f7b) | Jun 26, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [9888e54285](https://linux-hardware.org/?probe=9888e54285) | Jun 25, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [2d7e4f3505](https://linux-hardware.org/?probe=2d7e4f3505) | Jun 24, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [23c2fe2245](https://linux-hardware.org/?probe=23c2fe2245) | Jun 24, 2023 |
| ASUSTek       | P5B                         | Desktop     | [a62968d622](https://linux-hardware.org/?probe=a62968d622) | Jun 24, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [abbe9c9751](https://linux-hardware.org/?probe=abbe9c9751) | Jun 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [d7e8503e88](https://linux-hardware.org/?probe=d7e8503e88) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [4ab121533a](https://linux-hardware.org/?probe=4ab121533a) | Jun 23, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [0ee3f7532c](https://linux-hardware.org/?probe=0ee3f7532c) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [c7be73b6ca](https://linux-hardware.org/?probe=c7be73b6ca) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [346bbb0b47](https://linux-hardware.org/?probe=346bbb0b47) | Jun 23, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [b33e52fa0a](https://linux-hardware.org/?probe=b33e52fa0a) | Jun 22, 2023 |
| ASUSTek       | PN64                        | Mini pc     | [c63cf5f434](https://linux-hardware.org/?probe=c63cf5f434) | Jun 22, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [7782ddf809](https://linux-hardware.org/?probe=7782ddf809) | Jun 22, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [e4407d328d](https://linux-hardware.org/?probe=e4407d328d) | Jun 22, 2023 |
| HP            | 0B40h                       | Desktop     | [ac50670d44](https://linux-hardware.org/?probe=ac50670d44) | Jun 21, 2023 |
| Dell          | Latitude E6410              | Notebook    | [b34442d8c3](https://linux-hardware.org/?probe=b34442d8c3) | Jun 20, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [b154e92f35](https://linux-hardware.org/?probe=b154e92f35) | Jun 20, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [ee8a4e18c4](https://linux-hardware.org/?probe=ee8a4e18c4) | Jun 20, 2023 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [f9bf8920f7](https://linux-hardware.org/?probe=f9bf8920f7) | Jun 20, 2023 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [c436287876](https://linux-hardware.org/?probe=c436287876) | Jun 20, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | Notebook    | [9e06717237](https://linux-hardware.org/?probe=9e06717237) | Jun 19, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [b6b7fa0f5d](https://linux-hardware.org/?probe=b6b7fa0f5d) | Jun 19, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [bcd39f0607](https://linux-hardware.org/?probe=bcd39f0607) | Jun 19, 2023 |
| HP            | HDX18                       | Notebook    | [dec8492b2f](https://linux-hardware.org/?probe=dec8492b2f) | Jun 19, 2023 |
| ASUSTek       | X541NA                      | Notebook    | [2fa7c42c59](https://linux-hardware.org/?probe=2fa7c42c59) | Jun 18, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [b7a4e69498](https://linux-hardware.org/?probe=b7a4e69498) | Jun 18, 2023 |
| Dell          | Latitude 5430               | Notebook    | [cb097e3c83](https://linux-hardware.org/?probe=cb097e3c83) | Jun 18, 2023 |
| Dell          | Precision 7540              | Notebook    | [8b9ddcc1d8](https://linux-hardware.org/?probe=8b9ddcc1d8) | Jun 18, 2023 |
| Acer          | Aspire Z24-890              | All in one  | [8f7aac560c](https://linux-hardware.org/?probe=8f7aac560c) | Jun 18, 2023 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [3f18a24757](https://linux-hardware.org/?probe=3f18a24757) | Jun 18, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [8f32e75d6e](https://linux-hardware.org/?probe=8f32e75d6e) | Jun 18, 2023 |
| Dell          | Latitude 3189               | Notebook    | [c7f2d1b100](https://linux-hardware.org/?probe=c7f2d1b100) | Jun 17, 2023 |
| HP            | 3397                        | Desktop     | [b9fa9f9e43](https://linux-hardware.org/?probe=b9fa9f9e43) | Jun 17, 2023 |
| Dell          | 0PU052                      | Desktop     | [93bd9e7b0b](https://linux-hardware.org/?probe=93bd9e7b0b) | Jun 17, 2023 |
| Dell          | 0PU052                      | Desktop     | [36b0b1204f](https://linux-hardware.org/?probe=36b0b1204f) | Jun 17, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [a62dc4b2ed](https://linux-hardware.org/?probe=a62dc4b2ed) | Jun 17, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [6e0568f0df](https://linux-hardware.org/?probe=6e0568f0df) | Jun 17, 2023 |
| Dell          | 0PU052                      | Desktop     | [d5d7c6ec90](https://linux-hardware.org/?probe=d5d7c6ec90) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [c338e10965](https://linux-hardware.org/?probe=c338e10965) | Jun 16, 2023 |
| Acer          | Aspire V5-571P              | Notebook    | [2adeb26f8a](https://linux-hardware.org/?probe=2adeb26f8a) | Jun 15, 2023 |
| HP            | HDX18                       | Notebook    | [9a49d14af9](https://linux-hardware.org/?probe=9a49d14af9) | Jun 15, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [175aa8aae4](https://linux-hardware.org/?probe=175aa8aae4) | Jun 15, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [6b73cb1d75](https://linux-hardware.org/?probe=6b73cb1d75) | Jun 15, 2023 |
| Razer         | Blade 16 - RZ09-0483        | Notebook    | [a8cc966bac](https://linux-hardware.org/?probe=a8cc966bac) | Jun 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [bc3ba9b05e](https://linux-hardware.org/?probe=bc3ba9b05e) | Jun 15, 2023 |
| Dell          | Latitude 3310               | Notebook    | [40aa328d98](https://linux-hardware.org/?probe=40aa328d98) | Jun 15, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [cc3d8c4659](https://linux-hardware.org/?probe=cc3d8c4659) | Jun 15, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [1f5318c2b4](https://linux-hardware.org/?probe=1f5318c2b4) | Jun 14, 2023 |
| Dell          | Latitude E5270              | Notebook    | [49f184b9e9](https://linux-hardware.org/?probe=49f184b9e9) | Jun 13, 2023 |
| Samsung       | 750XED                      | Notebook    | [8997330d6a](https://linux-hardware.org/?probe=8997330d6a) | Jun 13, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [39d97bb85b](https://linux-hardware.org/?probe=39d97bb85b) | Jun 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [aca09b2a54](https://linux-hardware.org/?probe=aca09b2a54) | Jun 12, 2023 |
| ASUSTek       | P5B                         | Desktop     | [6308a1c633](https://linux-hardware.org/?probe=6308a1c633) | Jun 12, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [b815ac19d4](https://linux-hardware.org/?probe=b815ac19d4) | Jun 12, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [b9c83e1b8a](https://linux-hardware.org/?probe=b9c83e1b8a) | Jun 12, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [d2cb2b5360](https://linux-hardware.org/?probe=d2cb2b5360) | Jun 11, 2023 |
| Google        | Snappy                      | Notebook    | [737988d62e](https://linux-hardware.org/?probe=737988d62e) | Jun 11, 2023 |
| Google        | Snappy                      | Notebook    | [f228dabe46](https://linux-hardware.org/?probe=f228dabe46) | Jun 11, 2023 |
| ASUSTek       | P5B                         | Desktop     | [794635cbea](https://linux-hardware.org/?probe=794635cbea) | Jun 10, 2023 |
| Dell          | Latitude 9420               | Convertible | [354adf0653](https://linux-hardware.org/?probe=354adf0653) | Jun 10, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [977d645961](https://linux-hardware.org/?probe=977d645961) | Jun 10, 2023 |
| MP            | MS-7848                     | Desktop     | [cd63c98850](https://linux-hardware.org/?probe=cd63c98850) | Jun 10, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f502f89e9d](https://linux-hardware.org/?probe=f502f89e9d) | Jun 10, 2023 |
| Dell          | 0PU052                      | Desktop     | [84db4b658c](https://linux-hardware.org/?probe=84db4b658c) | Jun 09, 2023 |
| Dell          | 0PU052                      | Desktop     | [145d296b59](https://linux-hardware.org/?probe=145d296b59) | Jun 09, 2023 |
| Dell          | Latitude 9420               | Convertible | [593403cb67](https://linux-hardware.org/?probe=593403cb67) | Jun 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [7a36bdb92a](https://linux-hardware.org/?probe=7a36bdb92a) | Jun 09, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [6f26f51ef6](https://linux-hardware.org/?probe=6f26f51ef6) | Jun 09, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [ab95a219f5](https://linux-hardware.org/?probe=ab95a219f5) | Jun 09, 2023 |
| Dell          | Precision 7540              | Notebook    | [41fe2f93ff](https://linux-hardware.org/?probe=41fe2f93ff) | Jun 09, 2023 |
| ASUSTek       | P5B                         | Desktop     | [32baec6c0f](https://linux-hardware.org/?probe=32baec6c0f) | Jun 08, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [610c9c318f](https://linux-hardware.org/?probe=610c9c318f) | Jun 08, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [aab84214f1](https://linux-hardware.org/?probe=aab84214f1) | Jun 06, 2023 |
| Lenovo        | ThinkPad T590 20N5000AMH    | Notebook    | [91c0d99427](https://linux-hardware.org/?probe=91c0d99427) | Jun 06, 2023 |
| Dell          | Latitude 7480               | Notebook    | [61c800a3b4](https://linux-hardware.org/?probe=61c800a3b4) | Jun 06, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [0d326774c9](https://linux-hardware.org/?probe=0d326774c9) | Jun 06, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [4895fe7746](https://linux-hardware.org/?probe=4895fe7746) | Jun 05, 2023 |
| Dell          | Precision 7540              | Notebook    | [a10ecca056](https://linux-hardware.org/?probe=a10ecca056) | Jun 04, 2023 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [d4bc6d6c8c](https://linux-hardware.org/?probe=d4bc6d6c8c) | Jun 04, 2023 |
| ASRock        | J5040-ITX                   | Desktop     | [5e1bb16065](https://linux-hardware.org/?probe=5e1bb16065) | Jun 04, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [253c561829](https://linux-hardware.org/?probe=253c561829) | Jun 04, 2023 |
| AMI           | Intel                       | Notebook    | [cd2beb79d2](https://linux-hardware.org/?probe=cd2beb79d2) | Jun 04, 2023 |
| ASUSTek       | H170-PRO                    | Desktop     | [b9fd75507c](https://linux-hardware.org/?probe=b9fd75507c) | Jun 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | Notebook    | [6d8d7f6384](https://linux-hardware.org/?probe=6d8d7f6384) | Jun 04, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [309d09ae8c](https://linux-hardware.org/?probe=309d09ae8c) | Jun 03, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [d07b3215b1](https://linux-hardware.org/?probe=d07b3215b1) | Jun 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [4d1ad8d52a](https://linux-hardware.org/?probe=4d1ad8d52a) | Jun 03, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [3e7ad22b6b](https://linux-hardware.org/?probe=3e7ad22b6b) | Jun 03, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [e459d2654f](https://linux-hardware.org/?probe=e459d2654f) | Jun 03, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [71c4a65aae](https://linux-hardware.org/?probe=71c4a65aae) | Jun 03, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [20a14caf03](https://linux-hardware.org/?probe=20a14caf03) | Jun 03, 2023 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [d50ca19dc3](https://linux-hardware.org/?probe=d50ca19dc3) | Jun 02, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [31400c0b8a](https://linux-hardware.org/?probe=31400c0b8a) | Jun 02, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [c87d784c98](https://linux-hardware.org/?probe=c87d784c98) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [6b1168349b](https://linux-hardware.org/?probe=6b1168349b) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [3da98cc9bb](https://linux-hardware.org/?probe=3da98cc9bb) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [98b0b355db](https://linux-hardware.org/?probe=98b0b355db) | Jun 01, 2023 |
| HP            | 1906                        | Desktop     | [ac98480bd2](https://linux-hardware.org/?probe=ac98480bd2) | Jun 01, 2023 |
| Dell          | Precision 7540              | Notebook    | [de2fc5bc92](https://linux-hardware.org/?probe=de2fc5bc92) | Jun 01, 2023 |
| Supermicro    | X11SCD-F                    | Desktop     | [80072f2519](https://linux-hardware.org/?probe=80072f2519) | Jun 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [06000e9b0e](https://linux-hardware.org/?probe=06000e9b0e) | Jun 01, 2023 |
| ASUSTek       | X200LA                      | Notebook    | [ae3925153d](https://linux-hardware.org/?probe=ae3925153d) | May 31, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [743741a477](https://linux-hardware.org/?probe=743741a477) | May 31, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [4c7348e8b3](https://linux-hardware.org/?probe=4c7348e8b3) | May 31, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [10f4ef3e86](https://linux-hardware.org/?probe=10f4ef3e86) | May 31, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [87d9c3f3a1](https://linux-hardware.org/?probe=87d9c3f3a1) | May 31, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [7210e5c07e](https://linux-hardware.org/?probe=7210e5c07e) | May 31, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [ad79be40f5](https://linux-hardware.org/?probe=ad79be40f5) | May 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [6d6d7c65a8](https://linux-hardware.org/?probe=6d6d7c65a8) | May 31, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [a3e4ffb4fd](https://linux-hardware.org/?probe=a3e4ffb4fd) | May 30, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [fa8eeaabff](https://linux-hardware.org/?probe=fa8eeaabff) | May 30, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [541e16d421](https://linux-hardware.org/?probe=541e16d421) | May 29, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [bf0674c0f0](https://linux-hardware.org/?probe=bf0674c0f0) | May 28, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [9178413d40](https://linux-hardware.org/?probe=9178413d40) | May 28, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [cc9d03264f](https://linux-hardware.org/?probe=cc9d03264f) | May 27, 2023 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [3058a75499](https://linux-hardware.org/?probe=3058a75499) | May 26, 2023 |
| MSI           | CX700                       | Notebook    | [ecb1aaf9c1](https://linux-hardware.org/?probe=ecb1aaf9c1) | May 26, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [689eec8b51](https://linux-hardware.org/?probe=689eec8b51) | May 26, 2023 |
| Dell          | Latitude 5290               | Notebook    | [fb6cbb6a2f](https://linux-hardware.org/?probe=fb6cbb6a2f) | May 26, 2023 |
| AAEON         | UP-CHCR1 V0.4               | Desktop     | [b77201e825](https://linux-hardware.org/?probe=b77201e825) | May 26, 2023 |
| Dell          | Precision 7540              | Notebook    | [99c7b41c6b](https://linux-hardware.org/?probe=99c7b41c6b) | May 25, 2023 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [1987af2458](https://linux-hardware.org/?probe=1987af2458) | May 25, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [cbcfc55949](https://linux-hardware.org/?probe=cbcfc55949) | May 25, 2023 |
| Acer          | Aspire M3920                | Desktop     | [5e61c22a26](https://linux-hardware.org/?probe=5e61c22a26) | May 24, 2023 |
| ASUSTek       | Z87-DELUXE/DUAL             | Desktop     | [0f0c4f64ce](https://linux-hardware.org/?probe=0f0c4f64ce) | May 23, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [52b95d45ca](https://linux-hardware.org/?probe=52b95d45ca) | May 23, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [b880d4f8c1](https://linux-hardware.org/?probe=b880d4f8c1) | May 23, 2023 |
| Acidanther... | Mac-77EB7D7DAF985301 iMa... | All in one  | [b021476220](https://linux-hardware.org/?probe=b021476220) | May 23, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [69f5bff4c0](https://linux-hardware.org/?probe=69f5bff4c0) | May 23, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [c77cb59a5c](https://linux-hardware.org/?probe=c77cb59a5c) | May 23, 2023 |
| Dell          | Precision 7540              | Notebook    | [95bbab11f1](https://linux-hardware.org/?probe=95bbab11f1) | May 23, 2023 |
| Packard Be... | EasyNote MH35               | Notebook    | [ea7710b373](https://linux-hardware.org/?probe=ea7710b373) | May 22, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [7a302f637c](https://linux-hardware.org/?probe=7a302f637c) | May 22, 2023 |
| ASRock        | A520M Phantom Gaming 4      | Desktop     | [50b46e4d8c](https://linux-hardware.org/?probe=50b46e4d8c) | May 22, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [d0466f101a](https://linux-hardware.org/?probe=d0466f101a) | May 22, 2023 |
| AMI           | Intel                       | Desktop     | [9ddb291be3](https://linux-hardware.org/?probe=9ddb291be3) | May 22, 2023 |
| Dell          | XPS 9315                    | Notebook    | [6c3fdbf590](https://linux-hardware.org/?probe=6c3fdbf590) | May 22, 2023 |
| HP            | ZBook 14u G5                | Notebook    | [a655c52b88](https://linux-hardware.org/?probe=a655c52b88) | May 22, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [536b91dce1](https://linux-hardware.org/?probe=536b91dce1) | May 21, 2023 |
| Fujitsu Si... | D2831-S1 S26361-D2831-S1    | Desktop     | [0d2426a070](https://linux-hardware.org/?probe=0d2426a070) | May 21, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [ca280c2e18](https://linux-hardware.org/?probe=ca280c2e18) | May 21, 2023 |
| Lenovo        | ThinkPad T410 2537V32       | Notebook    | [cece14e931](https://linux-hardware.org/?probe=cece14e931) | May 21, 2023 |
| HP            | 0A08h                       | Desktop     | [9d159d2637](https://linux-hardware.org/?probe=9d159d2637) | May 21, 2023 |
| AMI           | Intel                       | Desktop     | [13f87e64f1](https://linux-hardware.org/?probe=13f87e64f1) | May 21, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b344b7ea03](https://linux-hardware.org/?probe=b344b7ea03) | May 21, 2023 |
| Toshiba       | Satellite C870-1FZ          | Notebook    | [1f2563578e](https://linux-hardware.org/?probe=1f2563578e) | May 20, 2023 |
| Dell          | Latitude 3120               | Convertible | [ac4bbe967d](https://linux-hardware.org/?probe=ac4bbe967d) | May 19, 2023 |
| Intel         | NUC5i5RYB H40999-503        | Mini pc     | [41342ea0f6](https://linux-hardware.org/?probe=41342ea0f6) | May 19, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [ce80a21736](https://linux-hardware.org/?probe=ce80a21736) | May 19, 2023 |
| Sony          | SVF1521A6EW                 | Notebook    | [49a9f77ea9](https://linux-hardware.org/?probe=49a9f77ea9) | May 18, 2023 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [97149ea35b](https://linux-hardware.org/?probe=97149ea35b) | May 18, 2023 |
| Dell          | Latitude 5500               | Notebook    | [f03dddbf42](https://linux-hardware.org/?probe=f03dddbf42) | May 18, 2023 |
| Acer          | Aspire A114-32              | Notebook    | [d17a909427](https://linux-hardware.org/?probe=d17a909427) | May 18, 2023 |
| Acer          | Aspire 7535                 | Notebook    | [32b02980a7](https://linux-hardware.org/?probe=32b02980a7) | May 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [6c83146909](https://linux-hardware.org/?probe=6c83146909) | May 18, 2023 |
| Gigabyte      | GB-BRR7H-4700               | Desktop     | [215d88c8b6](https://linux-hardware.org/?probe=215d88c8b6) | May 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [1ed7f81c69](https://linux-hardware.org/?probe=1ed7f81c69) | May 18, 2023 |
| Gigabyte      | GB-BRR7H-4700               | Desktop     | [d452669f4a](https://linux-hardware.org/?probe=d452669f4a) | May 18, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [beacb75b2c](https://linux-hardware.org/?probe=beacb75b2c) | May 18, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [004f548439](https://linux-hardware.org/?probe=004f548439) | May 17, 2023 |
| Dell          | Latitude E5510              | Notebook    | [74ecc09f16](https://linux-hardware.org/?probe=74ecc09f16) | May 17, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [228fa2798d](https://linux-hardware.org/?probe=228fa2798d) | May 16, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [32d4567b37](https://linux-hardware.org/?probe=32d4567b37) | May 16, 2023 |
| Framework     | Laptop                      | Notebook    | [b8739c141d](https://linux-hardware.org/?probe=b8739c141d) | May 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e31c83db5e](https://linux-hardware.org/?probe=e31c83db5e) | May 16, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [de2456eae8](https://linux-hardware.org/?probe=de2456eae8) | May 16, 2023 |
| Dell          | Latitude 5320               | Notebook    | [c33be8e25c](https://linux-hardware.org/?probe=c33be8e25c) | May 16, 2023 |
| Dell          | Latitude 5320               | Notebook    | [5e8463c682](https://linux-hardware.org/?probe=5e8463c682) | May 16, 2023 |
| Dell          | Latitude 5320               | Notebook    | [093e6a63c8](https://linux-hardware.org/?probe=093e6a63c8) | May 16, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [3ca79ab5f8](https://linux-hardware.org/?probe=3ca79ab5f8) | May 15, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [3f18889439](https://linux-hardware.org/?probe=3f18889439) | May 15, 2023 |
| HP            | 3398                        | Desktop     | [858590e655](https://linux-hardware.org/?probe=858590e655) | May 15, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | Desktop     | [7332acbb0e](https://linux-hardware.org/?probe=7332acbb0e) | May 15, 2023 |
| Medion        | B360H4-EM V1.0              | Desktop     | [1efefa9214](https://linux-hardware.org/?probe=1efefa9214) | May 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7978974828](https://linux-hardware.org/?probe=7978974828) | May 14, 2023 |
| HP            | ZBook 15u G5                | Notebook    | [4f1f52ce64](https://linux-hardware.org/?probe=4f1f52ce64) | May 14, 2023 |
| HP            | 829D                        | Desktop     | [a9358c228a](https://linux-hardware.org/?probe=a9358c228a) | May 14, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [acc449dad2](https://linux-hardware.org/?probe=acc449dad2) | May 14, 2023 |
| SKIKK         | Niflheim 17 II              | Notebook    | [ce9c27f16f](https://linux-hardware.org/?probe=ce9c27f16f) | May 14, 2023 |
| Xiaomi        | Mipad2                      | Tablet      | [c3c41b0bae](https://linux-hardware.org/?probe=c3c41b0bae) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [58557ae6a2](https://linux-hardware.org/?probe=58557ae6a2) | May 12, 2023 |
| MSI           | Stealth GS77 12UH           | Notebook    | [08fdf9cb20](https://linux-hardware.org/?probe=08fdf9cb20) | May 12, 2023 |
| HP            | EliteBook 720 G2            | Notebook    | [d6a156003b](https://linux-hardware.org/?probe=d6a156003b) | May 12, 2023 |
| Dell          | Latitude E7450              | Notebook    | [9dbbae1356](https://linux-hardware.org/?probe=9dbbae1356) | May 12, 2023 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [4318c51164](https://linux-hardware.org/?probe=4318c51164) | May 12, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [341a5673f2](https://linux-hardware.org/?probe=341a5673f2) | May 12, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [34bd8e2402](https://linux-hardware.org/?probe=34bd8e2402) | May 12, 2023 |
| HP            | 829A                        | Mini pc     | [e51b2da826](https://linux-hardware.org/?probe=e51b2da826) | May 12, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [e855bafa57](https://linux-hardware.org/?probe=e855bafa57) | May 11, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [eefa55009a](https://linux-hardware.org/?probe=eefa55009a) | May 11, 2023 |
| Dell          | 0X8DXD A00                  | Desktop     | [1e8359a02c](https://linux-hardware.org/?probe=1e8359a02c) | May 11, 2023 |
| Notebook      | N14xWU                      | Notebook    | [0e4f386b46](https://linux-hardware.org/?probe=0e4f386b46) | May 11, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [a7327f2e2e](https://linux-hardware.org/?probe=a7327f2e2e) | May 11, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [63e082c879](https://linux-hardware.org/?probe=63e082c879) | May 10, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [c85cc0e79c](https://linux-hardware.org/?probe=c85cc0e79c) | May 10, 2023 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [99af0c1e17](https://linux-hardware.org/?probe=99af0c1e17) | May 10, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [e4b3bba2b5](https://linux-hardware.org/?probe=e4b3bba2b5) | May 10, 2023 |
| Acer          | TravelMate P653-M           | Notebook    | [a0f805c8ca](https://linux-hardware.org/?probe=a0f805c8ca) | May 10, 2023 |
| Dell          | XPS 9315                    | Notebook    | [291a190f04](https://linux-hardware.org/?probe=291a190f04) | May 10, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [86136dd98f](https://linux-hardware.org/?probe=86136dd98f) | May 09, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [ba32d27df1](https://linux-hardware.org/?probe=ba32d27df1) | May 08, 2023 |
| HP            | 0AA8h                       | Desktop     | [05689fe634](https://linux-hardware.org/?probe=05689fe634) | May 08, 2023 |
| Acer          | Aspire M1930                | Desktop     | [712a246ce4](https://linux-hardware.org/?probe=712a246ce4) | May 08, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [8e4cbc4837](https://linux-hardware.org/?probe=8e4cbc4837) | May 08, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [ec45ea6206](https://linux-hardware.org/?probe=ec45ea6206) | May 08, 2023 |
| Acer          | Aspire M3920                | Desktop     | [aed14c1e20](https://linux-hardware.org/?probe=aed14c1e20) | May 07, 2023 |
| PC Special... | NP5x_NP6x_NP7xPNP           | Notebook    | [72d9dac16b](https://linux-hardware.org/?probe=72d9dac16b) | May 07, 2023 |
| Lenovo        | ThinkPad T420 4236WR1       | Notebook    | [148433c97e](https://linux-hardware.org/?probe=148433c97e) | May 07, 2023 |
| Timi          | TM1701                      | Notebook    | [c41d566374](https://linux-hardware.org/?probe=c41d566374) | May 07, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [dce7e41a72](https://linux-hardware.org/?probe=dce7e41a72) | May 07, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [64db3d70f1](https://linux-hardware.org/?probe=64db3d70f1) | May 07, 2023 |
| Lenovo        | ThinkPad T420 4236WR1       | Notebook    | [0d6a9b046a](https://linux-hardware.org/?probe=0d6a9b046a) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | Notebook    | [0304fddec7](https://linux-hardware.org/?probe=0304fddec7) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | Notebook    | [2a30823af1](https://linux-hardware.org/?probe=2a30823af1) | May 07, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [bdafbe06aa](https://linux-hardware.org/?probe=bdafbe06aa) | May 07, 2023 |
| HP            | 829A                        | Mini pc     | [eba2b6ce4e](https://linux-hardware.org/?probe=eba2b6ce4e) | May 06, 2023 |
| ASUSTek       | Zenbook UP5401EA_UP5401E... | Convertible | [01e1d2ef02](https://linux-hardware.org/?probe=01e1d2ef02) | May 05, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [3bea2bcd99](https://linux-hardware.org/?probe=3bea2bcd99) | May 05, 2023 |
| Unknown       | Cherry Trail CR             | Notebook    | [9569a530e8](https://linux-hardware.org/?probe=9569a530e8) | May 05, 2023 |
| Dell          | Precision 7720              | Notebook    | [b6c3392263](https://linux-hardware.org/?probe=b6c3392263) | May 05, 2023 |
| Intel         | JSL MRD                     | Desktop     | [76ff5c3bd7](https://linux-hardware.org/?probe=76ff5c3bd7) | May 05, 2023 |
| Acer          | TravelMate P214-53          | Notebook    | [8e78c8d139](https://linux-hardware.org/?probe=8e78c8d139) | May 05, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [f839b22217](https://linux-hardware.org/?probe=f839b22217) | May 05, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [9684be9c3a](https://linux-hardware.org/?probe=9684be9c3a) | May 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [4aec6123b0](https://linux-hardware.org/?probe=4aec6123b0) | May 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [0a6a9a6675](https://linux-hardware.org/?probe=0a6a9a6675) | May 03, 2023 |
| Dell          | Latitude 7420               | Notebook    | [7986f6779d](https://linux-hardware.org/?probe=7986f6779d) | May 03, 2023 |
| HP            | EliteBook Folio G1          | Notebook    | [a31ef5e00e](https://linux-hardware.org/?probe=a31ef5e00e) | May 02, 2023 |
| Toshiba       | Satellite C870-1FZ          | Notebook    | [dfbf38e06f](https://linux-hardware.org/?probe=dfbf38e06f) | May 01, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [f3b0efc277](https://linux-hardware.org/?probe=f3b0efc277) | May 01, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [07324ae678](https://linux-hardware.org/?probe=07324ae678) | May 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [24363c23cf](https://linux-hardware.org/?probe=24363c23cf) | May 01, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [6c1969f77e](https://linux-hardware.org/?probe=6c1969f77e) | May 01, 2023 |
| Intel         | CHERRYVIEW D1 PLATFORM      | Notebook    | [6c58138c35](https://linux-hardware.org/?probe=6c58138c35) | May 01, 2023 |
| VIOS          | LTH17                       | Notebook    | [4d1a86ee61](https://linux-hardware.org/?probe=4d1a86ee61) | Apr 30, 2023 |
| HP            | Compaq Mini CQ10-500        | Notebook    | [9a1134210f](https://linux-hardware.org/?probe=9a1134210f) | Apr 30, 2023 |
| Lenovo        | YB1-X91F                    | Tablet      | [3316360d7a](https://linux-hardware.org/?probe=3316360d7a) | Apr 29, 2023 |
| Intel         | CHERRYVIEW D1 PLATFORM      | Notebook    | [edf1d60e46](https://linux-hardware.org/?probe=edf1d60e46) | Apr 29, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [ef3f4d1ac1](https://linux-hardware.org/?probe=ef3f4d1ac1) | Apr 29, 2023 |
| Insyde        | M890BAP                     | Notebook    | [151efb0278](https://linux-hardware.org/?probe=151efb0278) | Apr 29, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [a9f658c8af](https://linux-hardware.org/?probe=a9f658c8af) | Apr 29, 2023 |
| Lenovo        | ThinkPad P50 20EQS5C701     | Notebook    | [e84690f2d5](https://linux-hardware.org/?probe=e84690f2d5) | Apr 29, 2023 |
| Dell          | Latitude 3301               | Notebook    | [3a0aad0e75](https://linux-hardware.org/?probe=3a0aad0e75) | Apr 29, 2023 |
| HP            | Pavilion dv7                | Notebook    | [e3f05fe37f](https://linux-hardware.org/?probe=e3f05fe37f) | Apr 28, 2023 |
| Dell          | 0773VG A02                  | Desktop     | [bd3dba564e](https://linux-hardware.org/?probe=bd3dba564e) | Apr 28, 2023 |
| HP            | Pavilion dv7                | Notebook    | [da542ba626](https://linux-hardware.org/?probe=da542ba626) | Apr 28, 2023 |
| Dell          | 0773VG A02                  | Desktop     | [cab1aa59e0](https://linux-hardware.org/?probe=cab1aa59e0) | Apr 28, 2023 |
| ASRock        | Z790 Steel Legend WiFi      | Desktop     | [36175223a5](https://linux-hardware.org/?probe=36175223a5) | Apr 28, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [fa82c3b6ba](https://linux-hardware.org/?probe=fa82c3b6ba) | Apr 28, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | Desktop     | [c416a3f44a](https://linux-hardware.org/?probe=c416a3f44a) | Apr 28, 2023 |
| Medion        | MS-7708                     | Desktop     | [af2020cd9c](https://linux-hardware.org/?probe=af2020cd9c) | Apr 28, 2023 |
| Medion        | MS-7708                     | Desktop     | [424c4ca2db](https://linux-hardware.org/?probe=424c4ca2db) | Apr 28, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [b5a953a984](https://linux-hardware.org/?probe=b5a953a984) | Apr 28, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [589810ee4b](https://linux-hardware.org/?probe=589810ee4b) | Apr 28, 2023 |
| Dell          | Latitude 3301               | Notebook    | [855564b077](https://linux-hardware.org/?probe=855564b077) | Apr 28, 2023 |
| BESSTAR Te... | HM80                        | Desktop     | [476c573547](https://linux-hardware.org/?probe=476c573547) | Apr 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [858404838d](https://linux-hardware.org/?probe=858404838d) | Apr 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [0bf066e179](https://linux-hardware.org/?probe=0bf066e179) | Apr 27, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [6b17eb81f8](https://linux-hardware.org/?probe=6b17eb81f8) | Apr 26, 2023 |
| Medion        | E2215T MD60198              | Notebook    | [390ccbba6f](https://linux-hardware.org/?probe=390ccbba6f) | Apr 26, 2023 |
| AZW           | SER                         | Mini pc     | [74f148fb60](https://linux-hardware.org/?probe=74f148fb60) | Apr 26, 2023 |
| Acer          | Aspire X3995                | Desktop     | [877c9deb7a](https://linux-hardware.org/?probe=877c9deb7a) | Apr 25, 2023 |
| Acer          | Predator G3-605             | Desktop     | [37cd92a7f0](https://linux-hardware.org/?probe=37cd92a7f0) | Apr 25, 2023 |
| Acer          | Predator G3-605             | Desktop     | [0b966e7b88](https://linux-hardware.org/?probe=0b966e7b88) | Apr 25, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [693f0cea98](https://linux-hardware.org/?probe=693f0cea98) | Apr 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [5236dde38f](https://linux-hardware.org/?probe=5236dde38f) | Apr 25, 2023 |
| Gigabyte      | Z270X-UD3-CF                | Desktop     | [06fbe4d0b6](https://linux-hardware.org/?probe=06fbe4d0b6) | Apr 25, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [40df32580a](https://linux-hardware.org/?probe=40df32580a) | Apr 25, 2023 |
| Notebook      | P95_96_97Ex,Rx              | Notebook    | [297da8c979](https://linux-hardware.org/?probe=297da8c979) | Apr 24, 2023 |
| ASRock        | H97M Anniversary            | Desktop     | [fdcfb2bde7](https://linux-hardware.org/?probe=fdcfb2bde7) | Apr 24, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [2337ae230f](https://linux-hardware.org/?probe=2337ae230f) | Apr 24, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [09eb88ba6c](https://linux-hardware.org/?probe=09eb88ba6c) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [6cacf7a9f9](https://linux-hardware.org/?probe=6cacf7a9f9) | Apr 24, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [90db0063b0](https://linux-hardware.org/?probe=90db0063b0) | Apr 24, 2023 |
| BTO           | 17X1183                     | Notebook    | [134a6ead50](https://linux-hardware.org/?probe=134a6ead50) | Apr 23, 2023 |
| BTO           | 17X1183                     | Notebook    | [181163b5e8](https://linux-hardware.org/?probe=181163b5e8) | Apr 23, 2023 |
| Dell          | Latitude 9520               | Notebook    | [0ab9a83db6](https://linux-hardware.org/?probe=0ab9a83db6) | Apr 23, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b906572f4b](https://linux-hardware.org/?probe=b906572f4b) | Apr 23, 2023 |
| Notebook      | NLxxPUx                     | Notebook    | [3648be5b0f](https://linux-hardware.org/?probe=3648be5b0f) | Apr 23, 2023 |
| Notebook      | W54_55_94_95_97AU,AUQ       | Notebook    | [f4e4c58948](https://linux-hardware.org/?probe=f4e4c58948) | Apr 23, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [65ba6571a2](https://linux-hardware.org/?probe=65ba6571a2) | Apr 23, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [72088721ec](https://linux-hardware.org/?probe=72088721ec) | Apr 22, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [112a18b586](https://linux-hardware.org/?probe=112a18b586) | Apr 22, 2023 |
| Dell          | Latitude E4300              | Notebook    | [f58f44d242](https://linux-hardware.org/?probe=f58f44d242) | Apr 22, 2023 |
| Medion        | E4251                       | Notebook    | [76820d982c](https://linux-hardware.org/?probe=76820d982c) | Apr 22, 2023 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [2e828158e5](https://linux-hardware.org/?probe=2e828158e5) | Apr 22, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [a26039eb50](https://linux-hardware.org/?probe=a26039eb50) | Apr 22, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [7e7a982c3c](https://linux-hardware.org/?probe=7e7a982c3c) | Apr 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [1c76d0f5a4](https://linux-hardware.org/?probe=1c76d0f5a4) | Apr 22, 2023 |
| Acer          | TP-SW3-013-181M             | Notebook    | [d231dc8846](https://linux-hardware.org/?probe=d231dc8846) | Apr 22, 2023 |
| Notebook      | N13_N140ZU                  | Notebook    | [51ee77485d](https://linux-hardware.org/?probe=51ee77485d) | Apr 21, 2023 |
| ASUSTek       | ZenBook UX333FN_RX333FN     | Notebook    | [8027ff2b04](https://linux-hardware.org/?probe=8027ff2b04) | Apr 21, 2023 |
| EVERCOM NE... | Unknown                     | Desktop     | [d36803f05d](https://linux-hardware.org/?probe=d36803f05d) | Apr 21, 2023 |
| HP            | 1494                        | Desktop     | [625373a1de](https://linux-hardware.org/?probe=625373a1de) | Apr 21, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [8c9f6ec7ef](https://linux-hardware.org/?probe=8c9f6ec7ef) | Apr 20, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [e8332849a1](https://linux-hardware.org/?probe=e8332849a1) | Apr 20, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [bca816c594](https://linux-hardware.org/?probe=bca816c594) | Apr 20, 2023 |
| Dell          | Latitude 5400               | Notebook    | [f0e05c9726](https://linux-hardware.org/?probe=f0e05c9726) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [4e45f9c51f](https://linux-hardware.org/?probe=4e45f9c51f) | Apr 20, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [9093d27c30](https://linux-hardware.org/?probe=9093d27c30) | Apr 19, 2023 |
| ASUSTek       | K501LX                      | Notebook    | [00676747c4](https://linux-hardware.org/?probe=00676747c4) | Apr 19, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [6a0eced5fc](https://linux-hardware.org/?probe=6a0eced5fc) | Apr 19, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [f691871296](https://linux-hardware.org/?probe=f691871296) | Apr 19, 2023 |
| Acer          | Swift SF314-57              | Notebook    | [5fc25cc033](https://linux-hardware.org/?probe=5fc25cc033) | Apr 19, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [abcb6ed7e8](https://linux-hardware.org/?probe=abcb6ed7e8) | Apr 19, 2023 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [213cd129cd](https://linux-hardware.org/?probe=213cd129cd) | Apr 18, 2023 |
| Lenovo        | 3714 SDK0J40709 WIN 3259... | Desktop     | [ae7ea68877](https://linux-hardware.org/?probe=ae7ea68877) | Apr 18, 2023 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | Notebook    | [17b3242021](https://linux-hardware.org/?probe=17b3242021) | Apr 18, 2023 |
| Acer          | Iconia                      | Notebook    | [1ebc88d3ab](https://linux-hardware.org/?probe=1ebc88d3ab) | Apr 18, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [f045e3f800](https://linux-hardware.org/?probe=f045e3f800) | Apr 18, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a99920ebba](https://linux-hardware.org/?probe=a99920ebba) | Apr 17, 2023 |
| ASRock        | Z790 Taichi                 | Desktop     | [0d25cf28bc](https://linux-hardware.org/?probe=0d25cf28bc) | Apr 17, 2023 |
| Lenovo        | 3714 SDK0J40709 WIN 3259... | Desktop     | [6c08e40387](https://linux-hardware.org/?probe=6c08e40387) | Apr 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [9f2a7943c7](https://linux-hardware.org/?probe=9f2a7943c7) | Apr 17, 2023 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [c370821f44](https://linux-hardware.org/?probe=c370821f44) | Apr 17, 2023 |
| Dell          | Latitude 5500               | Notebook    | [f4ac637463](https://linux-hardware.org/?probe=f4ac637463) | Apr 16, 2023 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [6c62f23970](https://linux-hardware.org/?probe=6c62f23970) | Apr 16, 2023 |
| HP            | 18E7                        | Desktop     | [6c2c248eec](https://linux-hardware.org/?probe=6c2c248eec) | Apr 16, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [5994a04ee0](https://linux-hardware.org/?probe=5994a04ee0) | Apr 16, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [ca89b451bd](https://linux-hardware.org/?probe=ca89b451bd) | Apr 15, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [df2e4c0c56](https://linux-hardware.org/?probe=df2e4c0c56) | Apr 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [2c7e1238eb](https://linux-hardware.org/?probe=2c7e1238eb) | Apr 15, 2023 |
| HP            | ZBook 14u G5                | Notebook    | [fcf729207a](https://linux-hardware.org/?probe=fcf729207a) | Apr 15, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [c30c14f9b0](https://linux-hardware.org/?probe=c30c14f9b0) | Apr 14, 2023 |
| Foxconn       | G31MVP FAB:1.0              | Desktop     | [41eac5ca2f](https://linux-hardware.org/?probe=41eac5ca2f) | Apr 14, 2023 |
| Medion        | MS-7857                     | Desktop     | [5d04997966](https://linux-hardware.org/?probe=5d04997966) | Apr 14, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [7f4d0d2d91](https://linux-hardware.org/?probe=7f4d0d2d91) | Apr 14, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [f3114cd0d7](https://linux-hardware.org/?probe=f3114cd0d7) | Apr 14, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [75ce029800](https://linux-hardware.org/?probe=75ce029800) | Apr 13, 2023 |
| ASUSTek       | GL502VM                     | Notebook    | [4d31e0eb90](https://linux-hardware.org/?probe=4d31e0eb90) | Apr 13, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [6b481f17c2](https://linux-hardware.org/?probe=6b481f17c2) | Apr 13, 2023 |
| Wortmann      | TERRA_MOBILE_1160           | Notebook    | [d40eed27fd](https://linux-hardware.org/?probe=d40eed27fd) | Apr 13, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [0519471935](https://linux-hardware.org/?probe=0519471935) | Apr 13, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [0a09da06be](https://linux-hardware.org/?probe=0a09da06be) | Apr 13, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [5411d789c3](https://linux-hardware.org/?probe=5411d789c3) | Apr 12, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [dc40d51336](https://linux-hardware.org/?probe=dc40d51336) | Apr 12, 2023 |
| Dell          | 03V7GF A01                  | Desktop     | [c309233437](https://linux-hardware.org/?probe=c309233437) | Apr 12, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [d2fbfe344c](https://linux-hardware.org/?probe=d2fbfe344c) | Apr 12, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [e8645a51dc](https://linux-hardware.org/?probe=e8645a51dc) | Apr 11, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [3d0ccace69](https://linux-hardware.org/?probe=3d0ccace69) | Apr 11, 2023 |
| Notebook      | NH55RGQ                     | Notebook    | [7fc1310fc2](https://linux-hardware.org/?probe=7fc1310fc2) | Apr 11, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a2aa745e5c](https://linux-hardware.org/?probe=a2aa745e5c) | Apr 10, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [94efe20a0f](https://linux-hardware.org/?probe=94efe20a0f) | Apr 10, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [5a903505c7](https://linux-hardware.org/?probe=5a903505c7) | Apr 10, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [854ec28c71](https://linux-hardware.org/?probe=854ec28c71) | Apr 09, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | Notebook    | [02bbb66fe9](https://linux-hardware.org/?probe=02bbb66fe9) | Apr 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [ea22560713](https://linux-hardware.org/?probe=ea22560713) | Apr 09, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [3fe1220d26](https://linux-hardware.org/?probe=3fe1220d26) | Apr 08, 2023 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e0913458ee](https://linux-hardware.org/?probe=e0913458ee) | Apr 07, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [76af734c86](https://linux-hardware.org/?probe=76af734c86) | Apr 07, 2023 |
| Notebook      | N141CU                      | Notebook    | [8648ddb323](https://linux-hardware.org/?probe=8648ddb323) | Apr 07, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [8d68ef79c3](https://linux-hardware.org/?probe=8d68ef79c3) | Apr 06, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [c2195f003d](https://linux-hardware.org/?probe=c2195f003d) | Apr 06, 2023 |
| Acer          | Aspire M1930                | Desktop     | [2bc158bf57](https://linux-hardware.org/?probe=2bc158bf57) | Apr 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [7aec6da94d](https://linux-hardware.org/?probe=7aec6da94d) | Apr 05, 2023 |
| Acer          | Spin SP314-51               | Convertible | [4b3e9e100d](https://linux-hardware.org/?probe=4b3e9e100d) | Apr 05, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [405f73f1fd](https://linux-hardware.org/?probe=405f73f1fd) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [0af2f7cc7f](https://linux-hardware.org/?probe=0af2f7cc7f) | Apr 05, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [10213d8aa1](https://linux-hardware.org/?probe=10213d8aa1) | Apr 05, 2023 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [b34f7e7ea6](https://linux-hardware.org/?probe=b34f7e7ea6) | Apr 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [e8a69f8de9](https://linux-hardware.org/?probe=e8a69f8de9) | Apr 05, 2023 |
| Dell          | XPS 9320                    | Notebook    | [c78c87474d](https://linux-hardware.org/?probe=c78c87474d) | Apr 05, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [519d2a4d5a](https://linux-hardware.org/?probe=519d2a4d5a) | Apr 04, 2023 |
| HP            | Pro x360 435 13.3 inch G... | Convertible | [f211babaa5](https://linux-hardware.org/?probe=f211babaa5) | Apr 04, 2023 |
| HP            | ProBook 6570b               | Notebook    | [d42564b34f](https://linux-hardware.org/?probe=d42564b34f) | Apr 04, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [ec3a161d36](https://linux-hardware.org/?probe=ec3a161d36) | Apr 04, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [316e31eae5](https://linux-hardware.org/?probe=316e31eae5) | Apr 04, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [088a09317e](https://linux-hardware.org/?probe=088a09317e) | Apr 04, 2023 |
| HP            | 3032h                       | Desktop     | [75792234b4](https://linux-hardware.org/?probe=75792234b4) | Apr 03, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [1af731cc92](https://linux-hardware.org/?probe=1af731cc92) | Apr 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [3125aa5d21](https://linux-hardware.org/?probe=3125aa5d21) | Apr 03, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [2296872799](https://linux-hardware.org/?probe=2296872799) | Apr 03, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [2e820040bc](https://linux-hardware.org/?probe=2e820040bc) | Apr 02, 2023 |
| Toxic         | GM5MPHY                     | Notebook    | [9ce64fb49a](https://linux-hardware.org/?probe=9ce64fb49a) | Apr 02, 2023 |
| ilife         | S806                        | Notebook    | [d089301e66](https://linux-hardware.org/?probe=d089301e66) | Apr 02, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [f78d5a9d04](https://linux-hardware.org/?probe=f78d5a9d04) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [ac5393930b](https://linux-hardware.org/?probe=ac5393930b) | Apr 02, 2023 |
| ilife         | S806                        | Notebook    | [3a3ccd7c55](https://linux-hardware.org/?probe=3a3ccd7c55) | Apr 02, 2023 |
| Intel         | VALLEYVIEW C0 PLATFORM      | Tablet      | [3dcf212c95](https://linux-hardware.org/?probe=3dcf212c95) | Apr 01, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [644ab9aa21](https://linux-hardware.org/?probe=644ab9aa21) | Apr 01, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [3494157f4b](https://linux-hardware.org/?probe=3494157f4b) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [1fb4c6ac6a](https://linux-hardware.org/?probe=1fb4c6ac6a) | Apr 01, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [5ef1391fb2](https://linux-hardware.org/?probe=5ef1391fb2) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [80bb5bbf28](https://linux-hardware.org/?probe=80bb5bbf28) | Apr 01, 2023 |
| ASRock        | B450 Pro4 R2.0              | Desktop     | [046d59655e](https://linux-hardware.org/?probe=046d59655e) | Apr 01, 2023 |
| ASRock        | H470M-STX                   | Desktop     | [c1f349f579](https://linux-hardware.org/?probe=c1f349f579) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [2e79b95cb4](https://linux-hardware.org/?probe=2e79b95cb4) | Apr 01, 2023 |
| Dell          | Latitude E7450              | Notebook    | [8bf693a890](https://linux-hardware.org/?probe=8bf693a890) | Apr 01, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [ca8ae50d80](https://linux-hardware.org/?probe=ca8ae50d80) | Mar 31, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [e18d9530c1](https://linux-hardware.org/?probe=e18d9530c1) | Mar 31, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [c3065ba2b6](https://linux-hardware.org/?probe=c3065ba2b6) | Mar 31, 2023 |
| Medion        | Iron238G                    | All in one  | [55cab5c7fa](https://linux-hardware.org/?probe=55cab5c7fa) | Mar 31, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [96107a824d](https://linux-hardware.org/?probe=96107a824d) | Mar 31, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [34bd6f42b1](https://linux-hardware.org/?probe=34bd6f42b1) | Mar 30, 2023 |
| HP            | 843F                        | Desktop     | [862f573134](https://linux-hardware.org/?probe=862f573134) | Mar 30, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [7edc7c9f47](https://linux-hardware.org/?probe=7edc7c9f47) | Mar 30, 2023 |
| Foxconn       | ETON                        | Desktop     | [52e92b5803](https://linux-hardware.org/?probe=52e92b5803) | Mar 30, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [6ade0ea04f](https://linux-hardware.org/?probe=6ade0ea04f) | Mar 30, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [0028f21c3e](https://linux-hardware.org/?probe=0028f21c3e) | Mar 30, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [de3828d539](https://linux-hardware.org/?probe=de3828d539) | Mar 29, 2023 |
| Acer          | FIH57                       | All in one  | [7a6b0e67f0](https://linux-hardware.org/?probe=7a6b0e67f0) | Mar 29, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [059358e49b](https://linux-hardware.org/?probe=059358e49b) | Mar 29, 2023 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [61ede0b764](https://linux-hardware.org/?probe=61ede0b764) | Mar 29, 2023 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [39d6f86500](https://linux-hardware.org/?probe=39d6f86500) | Mar 29, 2023 |
| Acer          | Aspire E5-773G              | Notebook    | [3cb72ca21c](https://linux-hardware.org/?probe=3cb72ca21c) | Mar 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [5b1e547f92](https://linux-hardware.org/?probe=5b1e547f92) | Mar 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [ce74564fd9](https://linux-hardware.org/?probe=ce74564fd9) | Mar 28, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [422e4056ea](https://linux-hardware.org/?probe=422e4056ea) | Mar 28, 2023 |
| ASRock        | J5040-ITX                   | Desktop     | [799a14a5d5](https://linux-hardware.org/?probe=799a14a5d5) | Mar 28, 2023 |
| MSI           | H87-G41 PC Mate             | Desktop     | [0d1345af82](https://linux-hardware.org/?probe=0d1345af82) | Mar 28, 2023 |
| ZOTAC         | AMD M1                      | Desktop     | [2b2c8fd4fa](https://linux-hardware.org/?probe=2b2c8fd4fa) | Mar 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [68175ccbea](https://linux-hardware.org/?probe=68175ccbea) | Mar 27, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [af90cee242](https://linux-hardware.org/?probe=af90cee242) | Mar 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [1988691e71](https://linux-hardware.org/?probe=1988691e71) | Mar 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [dd081eb573](https://linux-hardware.org/?probe=dd081eb573) | Mar 27, 2023 |
| ASUSTek       | N76VM                       | Notebook    | [0a05b4b5ce](https://linux-hardware.org/?probe=0a05b4b5ce) | Mar 26, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [b6a0d45508](https://linux-hardware.org/?probe=b6a0d45508) | Mar 26, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [05ecadea38](https://linux-hardware.org/?probe=05ecadea38) | Mar 26, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [5fff36a878](https://linux-hardware.org/?probe=5fff36a878) | Mar 25, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [79c876bced](https://linux-hardware.org/?probe=79c876bced) | Mar 25, 2023 |
| MSI           | 2AE0                        | Desktop     | [43a4a75176](https://linux-hardware.org/?probe=43a4a75176) | Mar 25, 2023 |
| Haier         | S15                         | Notebook    | [497105206c](https://linux-hardware.org/?probe=497105206c) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [c37a546614](https://linux-hardware.org/?probe=c37a546614) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [444375922e](https://linux-hardware.org/?probe=444375922e) | Mar 25, 2023 |
| MSI           | Summit E16FlipEvo A11MT     | Notebook    | [62839dd4ac](https://linux-hardware.org/?probe=62839dd4ac) | Mar 24, 2023 |
| Acer          | Aspire 5733Z                | Notebook    | [8a7f87172d](https://linux-hardware.org/?probe=8a7f87172d) | Mar 24, 2023 |
| Framework     | Laptop                      | Notebook    | [4e1bd28ce3](https://linux-hardware.org/?probe=4e1bd28ce3) | Mar 24, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [55f0bb1013](https://linux-hardware.org/?probe=55f0bb1013) | Mar 24, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [1ee3769d23](https://linux-hardware.org/?probe=1ee3769d23) | Mar 24, 2023 |
| Acer          | FIH57                       | All in one  | [1f63978352](https://linux-hardware.org/?probe=1f63978352) | Mar 23, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [06d6af1db0](https://linux-hardware.org/?probe=06d6af1db0) | Mar 23, 2023 |
| Acer          | Aspire M1930                | Desktop     | [228747d646](https://linux-hardware.org/?probe=228747d646) | Mar 22, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [386f37d114](https://linux-hardware.org/?probe=386f37d114) | Mar 22, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [825332bfce](https://linux-hardware.org/?probe=825332bfce) | Mar 21, 2023 |
| HP            | EliteBook 725 G2            | Notebook    | [5112f86dde](https://linux-hardware.org/?probe=5112f86dde) | Mar 21, 2023 |
| HP            | 1494                        | Desktop     | [e682c9975e](https://linux-hardware.org/?probe=e682c9975e) | Mar 21, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [83ddb49a8a](https://linux-hardware.org/?probe=83ddb49a8a) | Mar 21, 2023 |
| Hampoo        | Cherry Trail CR Hampoo_r... | Notebook    | [e7eb855568](https://linux-hardware.org/?probe=e7eb855568) | Mar 20, 2023 |
| Dell          | Latitude E6520              | Notebook    | [82f97b14f4](https://linux-hardware.org/?probe=82f97b14f4) | Mar 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [b73f7b46c4](https://linux-hardware.org/?probe=b73f7b46c4) | Mar 20, 2023 |
| Dell          | Latitude E6520              | Notebook    | [7f92514d4e](https://linux-hardware.org/?probe=7f92514d4e) | Mar 20, 2023 |
| Dell          | XPS 9315                    | Notebook    | [3a6814a18f](https://linux-hardware.org/?probe=3a6814a18f) | Mar 20, 2023 |
| Medion        | MS-7797                     | Desktop     | [180b0242e8](https://linux-hardware.org/?probe=180b0242e8) | Mar 20, 2023 |
| Dell          | XPS 9315                    | Notebook    | [a6054e6f0e](https://linux-hardware.org/?probe=a6054e6f0e) | Mar 20, 2023 |
| Lenovo        | [3633AC1] STC               | Server      | [aef7266e33](https://linux-hardware.org/?probe=aef7266e33) | Mar 20, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [53a3d14aa0](https://linux-hardware.org/?probe=53a3d14aa0) | Mar 20, 2023 |
| Gigabyte      | GB-BRR7H-4700               | Desktop     | [9d7f6de46c](https://linux-hardware.org/?probe=9d7f6de46c) | Mar 19, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [149e050820](https://linux-hardware.org/?probe=149e050820) | Mar 19, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [92ae74e13d](https://linux-hardware.org/?probe=92ae74e13d) | Mar 19, 2023 |
| HP            | 8056                        | Desktop     | [fa7f589aea](https://linux-hardware.org/?probe=fa7f589aea) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [add9634ad5](https://linux-hardware.org/?probe=add9634ad5) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [e2cfab15ef](https://linux-hardware.org/?probe=e2cfab15ef) | Mar 19, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [75dd9244fb](https://linux-hardware.org/?probe=75dd9244fb) | Mar 18, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [e90a87f6f2](https://linux-hardware.org/?probe=e90a87f6f2) | Mar 18, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [5356d2a0ef](https://linux-hardware.org/?probe=5356d2a0ef) | Mar 18, 2023 |
| HP            | 198E                        | Desktop     | [23e214216d](https://linux-hardware.org/?probe=23e214216d) | Mar 17, 2023 |
| HP            | 198E                        | Desktop     | [d5d5af66a8](https://linux-hardware.org/?probe=d5d5af66a8) | Mar 17, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [ba56245418](https://linux-hardware.org/?probe=ba56245418) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [c6ef926aa6](https://linux-hardware.org/?probe=c6ef926aa6) | Mar 17, 2023 |
| Dell          | Latitude E7240              | Notebook    | [cbcae7df75](https://linux-hardware.org/?probe=cbcae7df75) | Mar 17, 2023 |
| HP            | Compaq 6730s                | Notebook    | [7e2310fcf0](https://linux-hardware.org/?probe=7e2310fcf0) | Mar 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e0fa4709db](https://linux-hardware.org/?probe=e0fa4709db) | Mar 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3e5167941c](https://linux-hardware.org/?probe=3e5167941c) | Mar 17, 2023 |
| Dell          | Latitude E7440              | Notebook    | [edf7e8521c](https://linux-hardware.org/?probe=edf7e8521c) | Mar 17, 2023 |
| Dell          | 072T6D A01                  | Server      | [ba5febe33b](https://linux-hardware.org/?probe=ba5febe33b) | Mar 16, 2023 |
| ASUSTek       | M4A88T-M                    | Desktop     | [372deb4bed](https://linux-hardware.org/?probe=372deb4bed) | Mar 16, 2023 |
| ASUSTek       | M4A88T-M                    | Desktop     | [d8e1601e65](https://linux-hardware.org/?probe=d8e1601e65) | Mar 16, 2023 |
| Acer          | Predator PO3-630            | Desktop     | [07ac5c2647](https://linux-hardware.org/?probe=07ac5c2647) | Mar 16, 2023 |
| Acer          | Aspire M3920                | Desktop     | [bb2e9ec8a1](https://linux-hardware.org/?probe=bb2e9ec8a1) | Mar 16, 2023 |
| HP            | 3397                        | Desktop     | [5f261fa554](https://linux-hardware.org/?probe=5f261fa554) | Mar 15, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d73bb5ec34](https://linux-hardware.org/?probe=d73bb5ec34) | Mar 15, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [a78f938382](https://linux-hardware.org/?probe=a78f938382) | Mar 15, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [1c6475f7da](https://linux-hardware.org/?probe=1c6475f7da) | Mar 15, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [fcb50f0e4f](https://linux-hardware.org/?probe=fcb50f0e4f) | Mar 14, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [fc7320db54](https://linux-hardware.org/?probe=fc7320db54) | Mar 14, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [b3e091147a](https://linux-hardware.org/?probe=b3e091147a) | Mar 14, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | Notebook    | [e6d2f2a3b4](https://linux-hardware.org/?probe=e6d2f2a3b4) | Mar 14, 2023 |
| Samsung       | 930QED                      | Convertible | [a3182e0455](https://linux-hardware.org/?probe=a3182e0455) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [57000f8a86](https://linux-hardware.org/?probe=57000f8a86) | Mar 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [a826b1cd32](https://linux-hardware.org/?probe=a826b1cd32) | Mar 13, 2023 |
| Dell          | 09N44V A05                  | Server      | [d1a141052c](https://linux-hardware.org/?probe=d1a141052c) | Mar 13, 2023 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [659e2861d9](https://linux-hardware.org/?probe=659e2861d9) | Mar 13, 2023 |
| HP            | ProLiant DL380 G7           | Server      | [9911027e53](https://linux-hardware.org/?probe=9911027e53) | Mar 12, 2023 |
| HP            | Pavilion dv7                | Notebook    | [66f70aa8f4](https://linux-hardware.org/?probe=66f70aa8f4) | Mar 12, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | Notebook    | [2b864d8f97](https://linux-hardware.org/?probe=2b864d8f97) | Mar 12, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | Notebook    | [eb987f6db2](https://linux-hardware.org/?probe=eb987f6db2) | Mar 12, 2023 |
| Medion        | E4251                       | Notebook    | [8b057f3a15](https://linux-hardware.org/?probe=8b057f3a15) | Mar 12, 2023 |
| Acer          | Aspire 8930                 | Notebook    | [7434247d21](https://linux-hardware.org/?probe=7434247d21) | Mar 12, 2023 |
| ASUSTek       | V-P7H55E                    | Desktop     | [53357f1807](https://linux-hardware.org/?probe=53357f1807) | Mar 11, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [66094e937a](https://linux-hardware.org/?probe=66094e937a) | Mar 11, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | Notebook    | [c8d3cf3a4b](https://linux-hardware.org/?probe=c8d3cf3a4b) | Mar 11, 2023 |
| Lenovo        | ThinkPad T510 4384VJZ       | Notebook    | [d9c87b4795](https://linux-hardware.org/?probe=d9c87b4795) | Mar 11, 2023 |
| ASUSTek       | T100TAM                     | Notebook    | [1d647e564b](https://linux-hardware.org/?probe=1d647e564b) | Mar 10, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [3283454c2d](https://linux-hardware.org/?probe=3283454c2d) | Mar 10, 2023 |
| Intel         | NUC11TNBi3 M11908-404       | Mini pc     | [14bbc3a006](https://linux-hardware.org/?probe=14bbc3a006) | Mar 10, 2023 |
| HP            | ProBook 430 G2              | Notebook    | [21595cd5ed](https://linux-hardware.org/?probe=21595cd5ed) | Mar 09, 2023 |
| ASRock        | H87M Pro4                   | Desktop     | [49a012cecd](https://linux-hardware.org/?probe=49a012cecd) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [276ce8bd7c](https://linux-hardware.org/?probe=276ce8bd7c) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3daf833362](https://linux-hardware.org/?probe=3daf833362) | Mar 09, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [e8e1e04dbd](https://linux-hardware.org/?probe=e8e1e04dbd) | Mar 08, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [2dd91e2cd2](https://linux-hardware.org/?probe=2dd91e2cd2) | Mar 08, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [f4dd257e1d](https://linux-hardware.org/?probe=f4dd257e1d) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [8a6c736217](https://linux-hardware.org/?probe=8a6c736217) | Mar 07, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [c6119be13a](https://linux-hardware.org/?probe=c6119be13a) | Mar 07, 2023 |
| HP            | 3398                        | Desktop     | [024ce6b407](https://linux-hardware.org/?probe=024ce6b407) | Mar 06, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [b00f87c99b](https://linux-hardware.org/?probe=b00f87c99b) | Mar 06, 2023 |
| Fujitsu       | LIFEBOOK U9312              | Notebook    | [19a72f502b](https://linux-hardware.org/?probe=19a72f502b) | Mar 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [98a2c9f264](https://linux-hardware.org/?probe=98a2c9f264) | Mar 06, 2023 |
| Google        | Rammus                      | Notebook    | [0d905c6981](https://linux-hardware.org/?probe=0d905c6981) | Mar 05, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [439ec46914](https://linux-hardware.org/?probe=439ec46914) | Mar 05, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [53b112adac](https://linux-hardware.org/?probe=53b112adac) | Mar 05, 2023 |
| ASUSTek       | T200TA                      | Notebook    | [4d2a27cffa](https://linux-hardware.org/?probe=4d2a27cffa) | Mar 05, 2023 |
| MSI           | X58 Pro-E                   | Desktop     | [52169be881](https://linux-hardware.org/?probe=52169be881) | Mar 05, 2023 |
| MSI           | X58 Pro-E                   | Desktop     | [d841b24c32](https://linux-hardware.org/?probe=d841b24c32) | Mar 05, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [76243066c7](https://linux-hardware.org/?probe=76243066c7) | Mar 05, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [9667db85fc](https://linux-hardware.org/?probe=9667db85fc) | Mar 05, 2023 |
| HP            | 89B5 A                      | Desktop     | [b1f4e34d2d](https://linux-hardware.org/?probe=b1f4e34d2d) | Mar 04, 2023 |
| ASUSTek       | P5B-MX                      | Desktop     | [823575b2b0](https://linux-hardware.org/?probe=823575b2b0) | Mar 04, 2023 |
| Dell          | Studio XPS 1647             | Notebook    | [484c629656](https://linux-hardware.org/?probe=484c629656) | Mar 04, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [b5b5f89ca1](https://linux-hardware.org/?probe=b5b5f89ca1) | Mar 04, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [4a80c78c43](https://linux-hardware.org/?probe=4a80c78c43) | Mar 03, 2023 |
| HP            | 212B                        | Desktop     | [45dec8a39c](https://linux-hardware.org/?probe=45dec8a39c) | Mar 03, 2023 |
| Alienware     | m15                         | Notebook    | [180a0251f5](https://linux-hardware.org/?probe=180a0251f5) | Mar 02, 2023 |
| HP            | 3398                        | Desktop     | [6479dbaa0e](https://linux-hardware.org/?probe=6479dbaa0e) | Mar 02, 2023 |
| HP            | Notebook                    | Notebook    | [453811c44a](https://linux-hardware.org/?probe=453811c44a) | Mar 02, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [6b7925d129](https://linux-hardware.org/?probe=6b7925d129) | Mar 02, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [bbdc843fb2](https://linux-hardware.org/?probe=bbdc843fb2) | Mar 02, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [5cb58db69b](https://linux-hardware.org/?probe=5cb58db69b) | Mar 02, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [f6b780ae7e](https://linux-hardware.org/?probe=f6b780ae7e) | Mar 01, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [80dca547fc](https://linux-hardware.org/?probe=80dca547fc) | Mar 01, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [25112e4f96](https://linux-hardware.org/?probe=25112e4f96) | Mar 01, 2023 |
| Intel         | D34010WYK H14771-303        | Desktop     | [5bc379ea65](https://linux-hardware.org/?probe=5bc379ea65) | Mar 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [89fb184b09](https://linux-hardware.org/?probe=89fb184b09) | Mar 01, 2023 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [71b8cbeda5](https://linux-hardware.org/?probe=71b8cbeda5) | Feb 28, 2023 |
| ASUSTek       | N76VB                       | Notebook    | [0043164762](https://linux-hardware.org/?probe=0043164762) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [3b70c27ca4](https://linux-hardware.org/?probe=3b70c27ca4) | Feb 28, 2023 |
| HP            | ProBook 6570b               | Notebook    | [3692011e3f](https://linux-hardware.org/?probe=3692011e3f) | Feb 28, 2023 |
| Sony          | VGN-FW11M                   | Notebook    | [06b355e1de](https://linux-hardware.org/?probe=06b355e1de) | Feb 28, 2023 |
| ASUSTek       | PRIME X370-A                | Desktop     | [6bf890e60c](https://linux-hardware.org/?probe=6bf890e60c) | Feb 27, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [979b4559fe](https://linux-hardware.org/?probe=979b4559fe) | Feb 27, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [323a03f1c6](https://linux-hardware.org/?probe=323a03f1c6) | Feb 27, 2023 |
| Dell          | 0J584C A00                  | Desktop     | [c16b58c7ce](https://linux-hardware.org/?probe=c16b58c7ce) | Feb 26, 2023 |
| Dell          | 0J584C A00                  | Desktop     | [9d8016f80e](https://linux-hardware.org/?probe=9d8016f80e) | Feb 26, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [8184285a7d](https://linux-hardware.org/?probe=8184285a7d) | Feb 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [1dfaaf5a59](https://linux-hardware.org/?probe=1dfaaf5a59) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3aae5788cf](https://linux-hardware.org/?probe=3aae5788cf) | Feb 25, 2023 |
| HP            | Pavilion g7                 | Notebook    | [8f46d24897](https://linux-hardware.org/?probe=8f46d24897) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b5f840e593](https://linux-hardware.org/?probe=b5f840e593) | Feb 25, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [2978ec71b8](https://linux-hardware.org/?probe=2978ec71b8) | Feb 25, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [ca2ef50547](https://linux-hardware.org/?probe=ca2ef50547) | Feb 25, 2023 |
| Lenovo        | 851F 60072                  | Tablet      | [8466ce344b](https://linux-hardware.org/?probe=8466ce344b) | Feb 24, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [3899b2f13e](https://linux-hardware.org/?probe=3899b2f13e) | Feb 24, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [926fcff980](https://linux-hardware.org/?probe=926fcff980) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2bbce041f5](https://linux-hardware.org/?probe=2bbce041f5) | Feb 24, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [f91140d700](https://linux-hardware.org/?probe=f91140d700) | Feb 24, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [66b104fc61](https://linux-hardware.org/?probe=66b104fc61) | Feb 24, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [7233b168b4](https://linux-hardware.org/?probe=7233b168b4) | Feb 24, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [9398719812](https://linux-hardware.org/?probe=9398719812) | Feb 24, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [2cb9f58eae](https://linux-hardware.org/?probe=2cb9f58eae) | Feb 24, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [fa08c93ecd](https://linux-hardware.org/?probe=fa08c93ecd) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [a0bf98bcab](https://linux-hardware.org/?probe=a0bf98bcab) | Feb 23, 2023 |
| Intel         | SKYBAY                      | Desktop     | [a3d9851893](https://linux-hardware.org/?probe=a3d9851893) | Feb 23, 2023 |
| HUAWEI        | DRC-WXX                     | Tablet      | [f348e93361](https://linux-hardware.org/?probe=f348e93361) | Feb 23, 2023 |
| Dell          | 0YC03K A03                  | Desktop     | [0101ef8ce7](https://linux-hardware.org/?probe=0101ef8ce7) | Feb 23, 2023 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [1cca7fe830](https://linux-hardware.org/?probe=1cca7fe830) | Feb 22, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [de79cbb975](https://linux-hardware.org/?probe=de79cbb975) | Feb 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [5e92cdeee7](https://linux-hardware.org/?probe=5e92cdeee7) | Feb 22, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [cd66af8994](https://linux-hardware.org/?probe=cd66af8994) | Feb 21, 2023 |
| HP            | Pavilion dv7                | Notebook    | [1ecf49cbaf](https://linux-hardware.org/?probe=1ecf49cbaf) | Feb 21, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e1c694b371](https://linux-hardware.org/?probe=e1c694b371) | Feb 20, 2023 |
| Dell          | Latitude 7300               | Notebook    | [65690f7efc](https://linux-hardware.org/?probe=65690f7efc) | Feb 20, 2023 |
| Dell          | Latitude E6320              | Notebook    | [0b5bcfefc5](https://linux-hardware.org/?probe=0b5bcfefc5) | Feb 20, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [8ca2b786db](https://linux-hardware.org/?probe=8ca2b786db) | Feb 19, 2023 |
| ASRock        | H87 Performance             | Desktop     | [a28df01cad](https://linux-hardware.org/?probe=a28df01cad) | Feb 19, 2023 |
| Acer          | Aspire XC-780               | Desktop     | [db95126414](https://linux-hardware.org/?probe=db95126414) | Feb 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [f73ae7038f](https://linux-hardware.org/?probe=f73ae7038f) | Feb 19, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [c2e0245ec5](https://linux-hardware.org/?probe=c2e0245ec5) | Feb 19, 2023 |
| Dell          | Latitude E6320              | Notebook    | [8110ff7717](https://linux-hardware.org/?probe=8110ff7717) | Feb 19, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [0a015cdb94](https://linux-hardware.org/?probe=0a015cdb94) | Feb 18, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | Notebook    | [2daf635e15](https://linux-hardware.org/?probe=2daf635e15) | Feb 18, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [b2a9f21210](https://linux-hardware.org/?probe=b2a9f21210) | Feb 18, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [5857177f10](https://linux-hardware.org/?probe=5857177f10) | Feb 18, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [c4a1fe4a4f](https://linux-hardware.org/?probe=c4a1fe4a4f) | Feb 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [3886d9287f](https://linux-hardware.org/?probe=3886d9287f) | Feb 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [1b401aa3cf](https://linux-hardware.org/?probe=1b401aa3cf) | Feb 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [c59694e05c](https://linux-hardware.org/?probe=c59694e05c) | Feb 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [c614caec4a](https://linux-hardware.org/?probe=c614caec4a) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [7e8c7de460](https://linux-hardware.org/?probe=7e8c7de460) | Feb 17, 2023 |
| Alienware     | 15 R3                       | Notebook    | [c273319d9d](https://linux-hardware.org/?probe=c273319d9d) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [e01cd81ae1](https://linux-hardware.org/?probe=e01cd81ae1) | Feb 16, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [4fe16ec4fe](https://linux-hardware.org/?probe=4fe16ec4fe) | Feb 16, 2023 |
| HP            | Notebook                    | Notebook    | [3de841fd56](https://linux-hardware.org/?probe=3de841fd56) | Feb 16, 2023 |
| HP            | Pavilion dv7                | Notebook    | [130fe12846](https://linux-hardware.org/?probe=130fe12846) | Feb 16, 2023 |
| HP            | Pavilion dv7                | Notebook    | [7ca9bf386b](https://linux-hardware.org/?probe=7ca9bf386b) | Feb 16, 2023 |
| Google        | Helios                      | Notebook    | [4505c27d12](https://linux-hardware.org/?probe=4505c27d12) | Feb 16, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [ddc2c7ec7a](https://linux-hardware.org/?probe=ddc2c7ec7a) | Feb 16, 2023 |
| HP            | 3031h                       | Desktop     | [2b0cc2bd6e](https://linux-hardware.org/?probe=2b0cc2bd6e) | Feb 16, 2023 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [940563622b](https://linux-hardware.org/?probe=940563622b) | Feb 16, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [38c3a4311b](https://linux-hardware.org/?probe=38c3a4311b) | Feb 16, 2023 |
| HP            | 870C                        | Desktop     | [76ae5c62cf](https://linux-hardware.org/?probe=76ae5c62cf) | Feb 15, 2023 |
| Medion        | MS-7616                     | Desktop     | [0655a4e58c](https://linux-hardware.org/?probe=0655a4e58c) | Feb 15, 2023 |
| Dell          | Latitude 3320               | Notebook    | [fecee449d4](https://linux-hardware.org/?probe=fecee449d4) | Feb 15, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [3039ccd4b0](https://linux-hardware.org/?probe=3039ccd4b0) | Feb 14, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [d2754bf08f](https://linux-hardware.org/?probe=d2754bf08f) | Feb 14, 2023 |
| HP            | 3648h                       | Desktop     | [18eb122bc9](https://linux-hardware.org/?probe=18eb122bc9) | Feb 14, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [0d16c9013f](https://linux-hardware.org/?probe=0d16c9013f) | Feb 14, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [dcfa5b1fc5](https://linux-hardware.org/?probe=dcfa5b1fc5) | Feb 13, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [3a4a4dedc3](https://linux-hardware.org/?probe=3a4a4dedc3) | Feb 13, 2023 |
| Dell          | Latitude E5570              | Notebook    | [16e090c63c](https://linux-hardware.org/?probe=16e090c63c) | Feb 13, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [7c1423b767](https://linux-hardware.org/?probe=7c1423b767) | Feb 13, 2023 |
| Acer          | Aspire M1930                | Desktop     | [3b78f6fb4e](https://linux-hardware.org/?probe=3b78f6fb4e) | Feb 13, 2023 |
| MSI           | X99A SLI PLUS               | Desktop     | [98447ce3dd](https://linux-hardware.org/?probe=98447ce3dd) | Feb 13, 2023 |
| Dell          | Precision 3571              | Notebook    | [8f7f52dcaa](https://linux-hardware.org/?probe=8f7f52dcaa) | Feb 13, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [ea169af948](https://linux-hardware.org/?probe=ea169af948) | Feb 13, 2023 |
| HP            | 843F                        | Desktop     | [3047a0ff5b](https://linux-hardware.org/?probe=3047a0ff5b) | Feb 13, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [672b71db3e](https://linux-hardware.org/?probe=672b71db3e) | Feb 12, 2023 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [86026e4f54](https://linux-hardware.org/?probe=86026e4f54) | Feb 12, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [480da10129](https://linux-hardware.org/?probe=480da10129) | Feb 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [5629f3ed8c](https://linux-hardware.org/?probe=5629f3ed8c) | Feb 12, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [4829b991be](https://linux-hardware.org/?probe=4829b991be) | Feb 12, 2023 |
| HP            | Compaq 6820s                | Notebook    | [6c67866714](https://linux-hardware.org/?probe=6c67866714) | Feb 12, 2023 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [e1dc99210d](https://linux-hardware.org/?probe=e1dc99210d) | Feb 11, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [95875d4afc](https://linux-hardware.org/?probe=95875d4afc) | Feb 11, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [f5a8290d38](https://linux-hardware.org/?probe=f5a8290d38) | Feb 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e4340c10db](https://linux-hardware.org/?probe=e4340c10db) | Feb 10, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [845d2e4d52](https://linux-hardware.org/?probe=845d2e4d52) | Feb 10, 2023 |
| Dell          | Latitude 3120               | Convertible | [3bf2bfe867](https://linux-hardware.org/?probe=3bf2bfe867) | Feb 10, 2023 |
| ASUSTek       | N751JX                      | Notebook    | [fd591a3e67](https://linux-hardware.org/?probe=fd591a3e67) | Feb 10, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [7ac6f508b2](https://linux-hardware.org/?probe=7ac6f508b2) | Feb 10, 2023 |
| Dell          | Precision 3571              | Notebook    | [85985612ac](https://linux-hardware.org/?probe=85985612ac) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [353bd3a5b2](https://linux-hardware.org/?probe=353bd3a5b2) | Feb 09, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [f3eb8a2592](https://linux-hardware.org/?probe=f3eb8a2592) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [eeafe897ae](https://linux-hardware.org/?probe=eeafe897ae) | Feb 09, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [0779ef912a](https://linux-hardware.org/?probe=0779ef912a) | Feb 08, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [7091e6ba95](https://linux-hardware.org/?probe=7091e6ba95) | Feb 08, 2023 |
| Dell          | Latitude E7450              | Notebook    | [2513ec83c8](https://linux-hardware.org/?probe=2513ec83c8) | Feb 08, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [bb851866ac](https://linux-hardware.org/?probe=bb851866ac) | Feb 08, 2023 |
| Gigabyte      | B550 GAMING X               | Desktop     | [e92a6b0131](https://linux-hardware.org/?probe=e92a6b0131) | Feb 08, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [20d7058e4f](https://linux-hardware.org/?probe=20d7058e4f) | Feb 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [b376c55e80](https://linux-hardware.org/?probe=b376c55e80) | Feb 07, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [1e6a345b00](https://linux-hardware.org/?probe=1e6a345b00) | Feb 07, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [cdc1678cae](https://linux-hardware.org/?probe=cdc1678cae) | Feb 07, 2023 |
| Dell          | Latitude E6320              | Notebook    | [6d1fe4f041](https://linux-hardware.org/?probe=6d1fe4f041) | Feb 06, 2023 |
| Lenovo        | ThinkPad T510 4349AF5       | Notebook    | [5d737e59ae](https://linux-hardware.org/?probe=5d737e59ae) | Feb 06, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [ffc97bf3de](https://linux-hardware.org/?probe=ffc97bf3de) | Feb 06, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [2e581dc622](https://linux-hardware.org/?probe=2e581dc622) | Feb 06, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [3b4320a91a](https://linux-hardware.org/?probe=3b4320a91a) | Feb 06, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [33639358ab](https://linux-hardware.org/?probe=33639358ab) | Feb 06, 2023 |
| Standard      | Unknown                     | Notebook    | [c983c471de](https://linux-hardware.org/?probe=c983c471de) | Feb 05, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [b6333de3ab](https://linux-hardware.org/?probe=b6333de3ab) | Feb 05, 2023 |
| MSI           | MS-7376                     | Desktop     | [5f62748624](https://linux-hardware.org/?probe=5f62748624) | Feb 04, 2023 |
| MSI           | MS-7376                     | Desktop     | [33fa767f72](https://linux-hardware.org/?probe=33fa767f72) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [9f5df7e4e0](https://linux-hardware.org/?probe=9f5df7e4e0) | Feb 04, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [04c5cc4aec](https://linux-hardware.org/?probe=04c5cc4aec) | Feb 04, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [82a573d8cd](https://linux-hardware.org/?probe=82a573d8cd) | Feb 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [8dee1d9415](https://linux-hardware.org/?probe=8dee1d9415) | Feb 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [c6d48c9847](https://linux-hardware.org/?probe=c6d48c9847) | Feb 03, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [1e38d08821](https://linux-hardware.org/?probe=1e38d08821) | Feb 03, 2023 |
| Gigabyte      | EP45-DS3                    | Desktop     | [b9e4e36496](https://linux-hardware.org/?probe=b9e4e36496) | Feb 03, 2023 |
| Gigabyte      | EP45-DS3                    | Desktop     | [ac1f8787af](https://linux-hardware.org/?probe=ac1f8787af) | Feb 03, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [a899b18189](https://linux-hardware.org/?probe=a899b18189) | Feb 02, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [2a25e1c4d6](https://linux-hardware.org/?probe=2a25e1c4d6) | Feb 02, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [ecf260f299](https://linux-hardware.org/?probe=ecf260f299) | Feb 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [b829e9afbd](https://linux-hardware.org/?probe=b829e9afbd) | Feb 01, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [f05a20fe00](https://linux-hardware.org/?probe=f05a20fe00) | Feb 01, 2023 |
| Huanan        | X99-F8D PLUS V1.1           | Desktop     | [e68a009e8f](https://linux-hardware.org/?probe=e68a009e8f) | Feb 01, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [8a53501060](https://linux-hardware.org/?probe=8a53501060) | Jan 31, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [db8bdbd72b](https://linux-hardware.org/?probe=db8bdbd72b) | Jan 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [66b96d9a0f](https://linux-hardware.org/?probe=66b96d9a0f) | Jan 31, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [798466ab86](https://linux-hardware.org/?probe=798466ab86) | Jan 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [4dbe55873b](https://linux-hardware.org/?probe=4dbe55873b) | Jan 31, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [30a093116e](https://linux-hardware.org/?probe=30a093116e) | Jan 30, 2023 |
| MSI           | PRO Z690-P DDR4             | Desktop     | [a434328de5](https://linux-hardware.org/?probe=a434328de5) | Jan 30, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [67262a8155](https://linux-hardware.org/?probe=67262a8155) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [070a09add8](https://linux-hardware.org/?probe=070a09add8) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [8cca3cb036](https://linux-hardware.org/?probe=8cca3cb036) | Jan 30, 2023 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | Notebook    | [2469884587](https://linux-hardware.org/?probe=2469884587) | Jan 30, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [bdb3c91476](https://linux-hardware.org/?probe=bdb3c91476) | Jan 29, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [debdb8208f](https://linux-hardware.org/?probe=debdb8208f) | Jan 29, 2023 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [d17dc00a8a](https://linux-hardware.org/?probe=d17dc00a8a) | Jan 29, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [8bee986aca](https://linux-hardware.org/?probe=8bee986aca) | Jan 28, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [fb0dcf8d7e](https://linux-hardware.org/?probe=fb0dcf8d7e) | Jan 28, 2023 |
| HP            | 17E2                        | Mini pc     | [41fdb27963](https://linux-hardware.org/?probe=41fdb27963) | Jan 28, 2023 |
| HP            | 0A08h                       | Desktop     | [f9b0168de1](https://linux-hardware.org/?probe=f9b0168de1) | Jan 28, 2023 |
| Dell          | 0599V5 A12                  | Server      | [14f503ae4a](https://linux-hardware.org/?probe=14f503ae4a) | Jan 28, 2023 |
| HP            | Compaq nc6320 (RH569ET#A... | Notebook    | [bf4432a140](https://linux-hardware.org/?probe=bf4432a140) | Jan 28, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [a50b0e3645](https://linux-hardware.org/?probe=a50b0e3645) | Jan 28, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [97d1ab1b7d](https://linux-hardware.org/?probe=97d1ab1b7d) | Jan 28, 2023 |
| Acer          | Aspire E5-774               | Notebook    | [86e3285b31](https://linux-hardware.org/?probe=86e3285b31) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | Notebook    | [d3adeb692c](https://linux-hardware.org/?probe=d3adeb692c) | Jan 27, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [b9793eca79](https://linux-hardware.org/?probe=b9793eca79) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | Notebook    | [46b1227255](https://linux-hardware.org/?probe=46b1227255) | Jan 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [ee769c62bf](https://linux-hardware.org/?probe=ee769c62bf) | Jan 27, 2023 |
| HP            | 8055                        | Desktop     | [81fa44d8fa](https://linux-hardware.org/?probe=81fa44d8fa) | Jan 27, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1b1079b0bf](https://linux-hardware.org/?probe=1b1079b0bf) | Jan 27, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [c0468fe8fd](https://linux-hardware.org/?probe=c0468fe8fd) | Jan 27, 2023 |
| HP            | 3397                        | Desktop     | [ab38ecfb97](https://linux-hardware.org/?probe=ab38ecfb97) | Jan 26, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0P    | Notebook    | [1a36af70e8](https://linux-hardware.org/?probe=1a36af70e8) | Jan 26, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [c1427c9b7b](https://linux-hardware.org/?probe=c1427c9b7b) | Jan 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [cb8c4c9711](https://linux-hardware.org/?probe=cb8c4c9711) | Jan 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [076783b777](https://linux-hardware.org/?probe=076783b777) | Jan 26, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [b5cb34ea4d](https://linux-hardware.org/?probe=b5cb34ea4d) | Jan 26, 2023 |
| Toshiba       | Satellite C870-12F          | Notebook    | [fc9a6d3a7e](https://linux-hardware.org/?probe=fc9a6d3a7e) | Jan 25, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [4efa4db490](https://linux-hardware.org/?probe=4efa4db490) | Jan 25, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [70019cbdbf](https://linux-hardware.org/?probe=70019cbdbf) | Jan 25, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [dd2f21ab84](https://linux-hardware.org/?probe=dd2f21ab84) | Jan 25, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [9b7c80b059](https://linux-hardware.org/?probe=9b7c80b059) | Jan 25, 2023 |
| MSI           | CX700ND/CX70 0NF/CX70 0N... | Notebook    | [dad68fd07f](https://linux-hardware.org/?probe=dad68fd07f) | Jan 24, 2023 |
| MSI           | CX700ND/CX70 0NF/CX70 0N... | Notebook    | [b61b0f981e](https://linux-hardware.org/?probe=b61b0f981e) | Jan 24, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [0bde1ca99a](https://linux-hardware.org/?probe=0bde1ca99a) | Jan 24, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [8ac6e901d5](https://linux-hardware.org/?probe=8ac6e901d5) | Jan 24, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [47ff2a2e42](https://linux-hardware.org/?probe=47ff2a2e42) | Jan 24, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [a3672f1d47](https://linux-hardware.org/?probe=a3672f1d47) | Jan 24, 2023 |
| MSI           | GE70 2QD                    | Notebook    | [3194fb8316](https://linux-hardware.org/?probe=3194fb8316) | Jan 24, 2023 |
| MSI           | GE70 2QD                    | Notebook    | [8e124bc501](https://linux-hardware.org/?probe=8e124bc501) | Jan 24, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [75362fb07d](https://linux-hardware.org/?probe=75362fb07d) | Jan 24, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [7630683952](https://linux-hardware.org/?probe=7630683952) | Jan 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [8c427938e2](https://linux-hardware.org/?probe=8c427938e2) | Jan 24, 2023 |
| HP            | EliteBook 735 G6            | Notebook    | [bb321263f8](https://linux-hardware.org/?probe=bb321263f8) | Jan 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [5ca72b0d88](https://linux-hardware.org/?probe=5ca72b0d88) | Jan 24, 2023 |
| Acer          | Aspire SW5-012              | Notebook    | [247455614c](https://linux-hardware.org/?probe=247455614c) | Jan 23, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [5e4253b22d](https://linux-hardware.org/?probe=5e4253b22d) | Jan 23, 2023 |
| realme        | CloudProXXXX                | Notebook    | [8ba70a4617](https://linux-hardware.org/?probe=8ba70a4617) | Jan 23, 2023 |
| Acer          | Aspire 5680                 | Notebook    | [b4b7ebe3f9](https://linux-hardware.org/?probe=b4b7ebe3f9) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | Notebook    | [6e7a21c6d5](https://linux-hardware.org/?probe=6e7a21c6d5) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | Notebook    | [7d6077c27c](https://linux-hardware.org/?probe=7d6077c27c) | Jan 23, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [54313c1c76](https://linux-hardware.org/?probe=54313c1c76) | Jan 23, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [459ab8ae3d](https://linux-hardware.org/?probe=459ab8ae3d) | Jan 23, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [aa16eaced0](https://linux-hardware.org/?probe=aa16eaced0) | Jan 23, 2023 |
| Medion        | E4251                       | Notebook    | [7c90da8c5f](https://linux-hardware.org/?probe=7c90da8c5f) | Jan 23, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [0a3f1269f7](https://linux-hardware.org/?probe=0a3f1269f7) | Jan 23, 2023 |
| Acer          | Aspire 5680                 | Notebook    | [b2792832c2](https://linux-hardware.org/?probe=b2792832c2) | Jan 22, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [9beaa4240c](https://linux-hardware.org/?probe=9beaa4240c) | Jan 22, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [ffc0fa7fb5](https://linux-hardware.org/?probe=ffc0fa7fb5) | Jan 22, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [7933a58a32](https://linux-hardware.org/?probe=7933a58a32) | Jan 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [733770beaf](https://linux-hardware.org/?probe=733770beaf) | Jan 22, 2023 |
| Dell          | Latitude 5520               | Notebook    | [a3541758f7](https://linux-hardware.org/?probe=a3541758f7) | Jan 22, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [40cc1bf7d9](https://linux-hardware.org/?probe=40cc1bf7d9) | Jan 21, 2023 |
| MSI           | Z97 GAMING 3                | Desktop     | [325f9e8310](https://linux-hardware.org/?probe=325f9e8310) | Jan 21, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [eeea0542b8](https://linux-hardware.org/?probe=eeea0542b8) | Jan 21, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [5d606f2c60](https://linux-hardware.org/?probe=5d606f2c60) | Jan 21, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [acf0fd5893](https://linux-hardware.org/?probe=acf0fd5893) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [2b7ce5b726](https://linux-hardware.org/?probe=2b7ce5b726) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490 20N3S0E000    | Notebook    | [d324a863a5](https://linux-hardware.org/?probe=d324a863a5) | Jan 20, 2023 |
| BESSTAR Te... | UM350                       | Desktop     | [4a2292e809](https://linux-hardware.org/?probe=4a2292e809) | Jan 19, 2023 |
| Acer          | Predator G3-710             | Desktop     | [c7f97640a5](https://linux-hardware.org/?probe=c7f97640a5) | Jan 19, 2023 |
| ASUSTek       | P6T                         | Desktop     | [ac42d5a147](https://linux-hardware.org/?probe=ac42d5a147) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [9620f447dd](https://linux-hardware.org/?probe=9620f447dd) | Jan 19, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [1a61029965](https://linux-hardware.org/?probe=1a61029965) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [2135c30983](https://linux-hardware.org/?probe=2135c30983) | Jan 19, 2023 |
| HP            | Notebook                    | Notebook    | [63f0c0b90c](https://linux-hardware.org/?probe=63f0c0b90c) | Jan 19, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [da0d1f442a](https://linux-hardware.org/?probe=da0d1f442a) | Jan 19, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [3591fb1d6c](https://linux-hardware.org/?probe=3591fb1d6c) | Jan 19, 2023 |
| Pegatron      | EVANS                       | Desktop     | [798a545fa8](https://linux-hardware.org/?probe=798a545fa8) | Jan 19, 2023 |
| Pegatron      | EVANS                       | Desktop     | [411db3ea66](https://linux-hardware.org/?probe=411db3ea66) | Jan 19, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [68d2fcbdcf](https://linux-hardware.org/?probe=68d2fcbdcf) | Jan 18, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [f0ce1e8b3f](https://linux-hardware.org/?probe=f0ce1e8b3f) | Jan 18, 2023 |
| Dell          | Latitude E6540              | Notebook    | [440b0eec1c](https://linux-hardware.org/?probe=440b0eec1c) | Jan 18, 2023 |
| Dell          | Precision M6800             | Notebook    | [62d01a5b26](https://linux-hardware.org/?probe=62d01a5b26) | Jan 18, 2023 |
| Dell          | Precision M6800             | Notebook    | [09e31ee1c8](https://linux-hardware.org/?probe=09e31ee1c8) | Jan 18, 2023 |
| ASRock        | B550 Extreme4               | Desktop     | [e5599ac616](https://linux-hardware.org/?probe=e5599ac616) | Jan 18, 2023 |
| Lenovo        | 374F SDK0R32862 WIN 3258... | Desktop     | [d50f9357b4](https://linux-hardware.org/?probe=d50f9357b4) | Jan 18, 2023 |
| Dell          | Latitude 5530               | Notebook    | [f9325236bb](https://linux-hardware.org/?probe=f9325236bb) | Jan 17, 2023 |
| Dell          | Latitude 5530               | Notebook    | [fafa35ef88](https://linux-hardware.org/?probe=fafa35ef88) | Jan 17, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [2cc8923eb1](https://linux-hardware.org/?probe=2cc8923eb1) | Jan 17, 2023 |
| HP            | ProBook 4540s               | Notebook    | [3f9e3a1cbb](https://linux-hardware.org/?probe=3f9e3a1cbb) | Jan 17, 2023 |
| ASRock        | H87 Performance             | Desktop     | [a71c911bcf](https://linux-hardware.org/?probe=a71c911bcf) | Jan 17, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [856324369f](https://linux-hardware.org/?probe=856324369f) | Jan 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d6b6c22af1](https://linux-hardware.org/?probe=d6b6c22af1) | Jan 17, 2023 |
| ASRock        | H87 Performance             | Desktop     | [9e2cd66ef5](https://linux-hardware.org/?probe=9e2cd66ef5) | Jan 16, 2023 |
| HP            | ProBook 4540s               | Notebook    | [7b9cd1b51c](https://linux-hardware.org/?probe=7b9cd1b51c) | Jan 16, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [4da81f73f5](https://linux-hardware.org/?probe=4da81f73f5) | Jan 16, 2023 |
| Google        | Banon                       | Notebook    | [6bb3ed04f9](https://linux-hardware.org/?probe=6bb3ed04f9) | Jan 16, 2023 |
| Lenovo        | ThinkPad T490s 20NX0076M... | Notebook    | [4c896e2c0e](https://linux-hardware.org/?probe=4c896e2c0e) | Jan 16, 2023 |
| Acer          | Aspire 5680                 | Notebook    | [dc5f6d7ac6](https://linux-hardware.org/?probe=dc5f6d7ac6) | Jan 16, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [976f23d99e](https://linux-hardware.org/?probe=976f23d99e) | Jan 16, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [01c0e96288](https://linux-hardware.org/?probe=01c0e96288) | Jan 16, 2023 |
| HP            | Pavilion 17                 | Notebook    | [895f75daf7](https://linux-hardware.org/?probe=895f75daf7) | Jan 16, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [57cd4eaca3](https://linux-hardware.org/?probe=57cd4eaca3) | Jan 15, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [bdfc087b4d](https://linux-hardware.org/?probe=bdfc087b4d) | Jan 15, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [4621c0d31b](https://linux-hardware.org/?probe=4621c0d31b) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [86039b3063](https://linux-hardware.org/?probe=86039b3063) | Jan 15, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [0277ea7e50](https://linux-hardware.org/?probe=0277ea7e50) | Jan 15, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [2f2fec82c8](https://linux-hardware.org/?probe=2f2fec82c8) | Jan 15, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [dd0a234ebb](https://linux-hardware.org/?probe=dd0a234ebb) | Jan 14, 2023 |
| Dell          | Latitude E5410              | Notebook    | [909ca0fd93](https://linux-hardware.org/?probe=909ca0fd93) | Jan 14, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [116b26047d](https://linux-hardware.org/?probe=116b26047d) | Jan 14, 2023 |
| Supermicro    | A1SA2-2750F                 | Server      | [e134d7a317](https://linux-hardware.org/?probe=e134d7a317) | Jan 14, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [c4cfa1aa47](https://linux-hardware.org/?probe=c4cfa1aa47) | Jan 13, 2023 |
| HP            | ZBook Studio G4             | Notebook    | [67168cc8a9](https://linux-hardware.org/?probe=67168cc8a9) | Jan 13, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [85d6a0b721](https://linux-hardware.org/?probe=85d6a0b721) | Jan 13, 2023 |
| Lenovo        | ThinkPad X270 20K5S1A524    | Notebook    | [e4eaef80f8](https://linux-hardware.org/?probe=e4eaef80f8) | Jan 13, 2023 |
| realme        | CloudProXXXX                | Notebook    | [25d1a9b890](https://linux-hardware.org/?probe=25d1a9b890) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [178c6f90fa](https://linux-hardware.org/?probe=178c6f90fa) | Jan 13, 2023 |
| Dell          | Latitude 3350               | Notebook    | [065c4a4a95](https://linux-hardware.org/?probe=065c4a4a95) | Jan 12, 2023 |
| Lenovo        | G770 1037                   | Notebook    | [da21020be1](https://linux-hardware.org/?probe=da21020be1) | Jan 12, 2023 |
| HP            | 8648                        | Desktop     | [df76c90c20](https://linux-hardware.org/?probe=df76c90c20) | Jan 12, 2023 |
| Notebook      | NS50MU                      | Notebook    | [7d94a36b67](https://linux-hardware.org/?probe=7d94a36b67) | Jan 12, 2023 |
| Standard      | Unknown                     | Notebook    | [b6f4b12847](https://linux-hardware.org/?probe=b6f4b12847) | Jan 12, 2023 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [77c659307a](https://linux-hardware.org/?probe=77c659307a) | Jan 11, 2023 |
| HP            | Pavilion dv9500             | Notebook    | [0f8c99e8d7](https://linux-hardware.org/?probe=0f8c99e8d7) | Jan 11, 2023 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [07a6ffe405](https://linux-hardware.org/?probe=07a6ffe405) | Jan 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [3696db52a7](https://linux-hardware.org/?probe=3696db52a7) | Jan 11, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [379a5aa220](https://linux-hardware.org/?probe=379a5aa220) | Jan 11, 2023 |
| Sony          | VPCEB3L9E                   | Notebook    | [5a7ea474fd](https://linux-hardware.org/?probe=5a7ea474fd) | Jan 11, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [7588fecfe8](https://linux-hardware.org/?probe=7588fecfe8) | Jan 10, 2023 |
| HP            | 843B                        | Desktop     | [ac14cee88f](https://linux-hardware.org/?probe=ac14cee88f) | Jan 10, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [69b3403f94](https://linux-hardware.org/?probe=69b3403f94) | Jan 10, 2023 |
| Acer          | Aspire 5735                 | Notebook    | [27b63fd8b1](https://linux-hardware.org/?probe=27b63fd8b1) | Jan 10, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [16a4dc82f5](https://linux-hardware.org/?probe=16a4dc82f5) | Jan 10, 2023 |
| HP            | 843B                        | Desktop     | [e45a20a47f](https://linux-hardware.org/?probe=e45a20a47f) | Jan 10, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [be24cf68d4](https://linux-hardware.org/?probe=be24cf68d4) | Jan 10, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [1375baed6d](https://linux-hardware.org/?probe=1375baed6d) | Jan 09, 2023 |
| MSI           | FM2-A75MA-E35               | Desktop     | [4bbe8325bd](https://linux-hardware.org/?probe=4bbe8325bd) | Jan 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [5663965a51](https://linux-hardware.org/?probe=5663965a51) | Jan 09, 2023 |
| Gigabyte      | J1900N-D2H                  | Desktop     | [62be43a4a3](https://linux-hardware.org/?probe=62be43a4a3) | Jan 09, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [774902b83f](https://linux-hardware.org/?probe=774902b83f) | Jan 09, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [6fd945d3cd](https://linux-hardware.org/?probe=6fd945d3cd) | Jan 09, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [1f97553f11](https://linux-hardware.org/?probe=1f97553f11) | Jan 08, 2023 |
| Dell          | 0WG855                      | Desktop     | [0a2e7733bf](https://linux-hardware.org/?probe=0a2e7733bf) | Jan 08, 2023 |
| Acer          | Aspire One 721              | Notebook    | [4b9311cfed](https://linux-hardware.org/?probe=4b9311cfed) | Jan 08, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [648dcae4c6](https://linux-hardware.org/?probe=648dcae4c6) | Jan 08, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [b39a58c2e6](https://linux-hardware.org/?probe=b39a58c2e6) | Jan 08, 2023 |
| Acer          | TravelMate P614-51-G2       | Notebook    | [0d0c035342](https://linux-hardware.org/?probe=0d0c035342) | Jan 08, 2023 |
| Lenovo        | ThinkPad Edge E145 20BC0... | Notebook    | [8ca4d7b38b](https://linux-hardware.org/?probe=8ca4d7b38b) | Jan 08, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [ebf4546adf](https://linux-hardware.org/?probe=ebf4546adf) | Jan 08, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [a4e777ea7d](https://linux-hardware.org/?probe=a4e777ea7d) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [782467ee8c](https://linux-hardware.org/?probe=782467ee8c) | Jan 07, 2023 |
| Standard      | X50-V2                      | Desktop     | [69b7593670](https://linux-hardware.org/?probe=69b7593670) | Jan 07, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [67b5b9902a](https://linux-hardware.org/?probe=67b5b9902a) | Jan 06, 2023 |
| ASRock        | H77M-ITX                    | Desktop     | [fb6cbfce9a](https://linux-hardware.org/?probe=fb6cbfce9a) | Jan 06, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [1ff445305d](https://linux-hardware.org/?probe=1ff445305d) | Jan 06, 2023 |
| Unknown       | HX90                        | Desktop     | [af144f98b6](https://linux-hardware.org/?probe=af144f98b6) | Jan 05, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [e3c76a5b82](https://linux-hardware.org/?probe=e3c76a5b82) | Jan 05, 2023 |
| HP            | 8648                        | Desktop     | [2345926399](https://linux-hardware.org/?probe=2345926399) | Jan 05, 2023 |
| Medion        | E4251 MD61435               | Notebook    | [7f3f24b812](https://linux-hardware.org/?probe=7f3f24b812) | Jan 05, 2023 |
| HP            | Pavilion 17                 | Notebook    | [fe325358d6](https://linux-hardware.org/?probe=fe325358d6) | Jan 04, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [4335d83dfc](https://linux-hardware.org/?probe=4335d83dfc) | Jan 04, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [8027cc9eeb](https://linux-hardware.org/?probe=8027cc9eeb) | Jan 04, 2023 |
| Dell          | Latitude E6330              | Notebook    | [0341a89f2f](https://linux-hardware.org/?probe=0341a89f2f) | Jan 04, 2023 |
| Sony          | VPCEB3L1E                   | Notebook    | [e8ac8a5d95](https://linux-hardware.org/?probe=e8ac8a5d95) | Jan 04, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [2f148d690a](https://linux-hardware.org/?probe=2f148d690a) | Jan 03, 2023 |
| ASUSTek       | F1A55-V                     | Desktop     | [fec2a24044](https://linux-hardware.org/?probe=fec2a24044) | Jan 03, 2023 |
| Acer          | Aspire E5-774               | Notebook    | [96c68886cf](https://linux-hardware.org/?probe=96c68886cf) | Jan 03, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [a316608c78](https://linux-hardware.org/?probe=a316608c78) | Jan 03, 2023 |
| Acer          | Aspire V3-574G              | Notebook    | [a889bba557](https://linux-hardware.org/?probe=a889bba557) | Jan 02, 2023 |
| Lenovo        | 31A7 SDK0J40697 WIN 3305... | Mini pc     | [efa2748c95](https://linux-hardware.org/?probe=efa2748c95) | Jan 02, 2023 |
| HP            | 3048h                       | Desktop     | [dabc36c98f](https://linux-hardware.org/?probe=dabc36c98f) | Jan 02, 2023 |
| Intel         | NUC5PPYB H76558-108         | Mini pc     | [e93bf27a59](https://linux-hardware.org/?probe=e93bf27a59) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [08fb8de608](https://linux-hardware.org/?probe=08fb8de608) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [bca75efbe5](https://linux-hardware.org/?probe=bca75efbe5) | Jan 02, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [f31ae01428](https://linux-hardware.org/?probe=f31ae01428) | Jan 02, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [0229b8166f](https://linux-hardware.org/?probe=0229b8166f) | Jan 02, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [6def847114](https://linux-hardware.org/?probe=6def847114) | Jan 01, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1E70... | Notebook    | [e8b6dd6f1f](https://linux-hardware.org/?probe=e8b6dd6f1f) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | Desktop     | [12c1c0d9a0](https://linux-hardware.org/?probe=12c1c0d9a0) | Jan 01, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [500ce7ae28](https://linux-hardware.org/?probe=500ce7ae28) | Dec 31, 2022 |
| Notebook      | PB50_70RF,RD,RC             | Notebook    | [d1f655b9b1](https://linux-hardware.org/?probe=d1f655b9b1) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP14... | Convertible | [195eb3e6eb](https://linux-hardware.org/?probe=195eb3e6eb) | Dec 31, 2022 |
| HP            | Pavilion 17                 | Notebook    | [c87d61d0cd](https://linux-hardware.org/?probe=c87d61d0cd) | Dec 31, 2022 |
| HP            | Pavilion 17                 | Notebook    | [bbf52af119](https://linux-hardware.org/?probe=bbf52af119) | Dec 31, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [fc108fb0d8](https://linux-hardware.org/?probe=fc108fb0d8) | Dec 31, 2022 |
| HP            | EliteBook 820 G4            | Notebook    | [9e794046d8](https://linux-hardware.org/?probe=9e794046d8) | Dec 30, 2022 |
| Acer          | Aspire 5680                 | Notebook    | [c14cfe5386](https://linux-hardware.org/?probe=c14cfe5386) | Dec 29, 2022 |
| Acer          | Aspire V3-772               | Notebook    | [9f431b484a](https://linux-hardware.org/?probe=9f431b484a) | Dec 29, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [b8cb61c70a](https://linux-hardware.org/?probe=b8cb61c70a) | Dec 29, 2022 |
| ASRock        | Z790 PG Riptide             | Desktop     | [19c8814aba](https://linux-hardware.org/?probe=19c8814aba) | Dec 29, 2022 |
| Alienware     | x17 R2                      | Notebook    | [5a7ea2683a](https://linux-hardware.org/?probe=5a7ea2683a) | Dec 28, 2022 |
| Gigabyte      | GB-BRR3H-4300               | Desktop     | [241d631981](https://linux-hardware.org/?probe=241d631981) | Dec 28, 2022 |
| Dell          | Latitude 2120               | Notebook    | [b52922b482](https://linux-hardware.org/?probe=b52922b482) | Dec 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [488d26f3e8](https://linux-hardware.org/?probe=488d26f3e8) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0763603d12](https://linux-hardware.org/?probe=0763603d12) | Dec 27, 2022 |
| LG Electro... | 17Z90Q-G.AA79G              | Notebook    | [59d7266746](https://linux-hardware.org/?probe=59d7266746) | Dec 26, 2022 |
| Gigabyte      | GB-BRR7H-4700               | Desktop     | [43c2d92e5f](https://linux-hardware.org/?probe=43c2d92e5f) | Dec 26, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [3d8320e362](https://linux-hardware.org/?probe=3d8320e362) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [5d95c28ac6](https://linux-hardware.org/?probe=5d95c28ac6) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [a98ca87f6a](https://linux-hardware.org/?probe=a98ca87f6a) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [00af244895](https://linux-hardware.org/?probe=00af244895) | Dec 25, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [5047d29893](https://linux-hardware.org/?probe=5047d29893) | Dec 24, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [ce9fc7a224](https://linux-hardware.org/?probe=ce9fc7a224) | Dec 24, 2022 |
| Medion        | E4251 MD61435               | Notebook    | [0ef8f76193](https://linux-hardware.org/?probe=0ef8f76193) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [0c1d9b9b28](https://linux-hardware.org/?probe=0c1d9b9b28) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [000660b461](https://linux-hardware.org/?probe=000660b461) | Dec 23, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [82cc0b362d](https://linux-hardware.org/?probe=82cc0b362d) | Dec 23, 2022 |
| Intel         | X99                         | Desktop     | [191fefa053](https://linux-hardware.org/?probe=191fefa053) | Dec 23, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [313bf04928](https://linux-hardware.org/?probe=313bf04928) | Dec 22, 2022 |
| Lenovo        | IdeaPad 3 14IAU7 82RJ       | Notebook    | [b5c5aba33a](https://linux-hardware.org/?probe=b5c5aba33a) | Dec 22, 2022 |
| Lenovo        | ThinkPad T470s 20HF003QU... | Notebook    | [5145350f9a](https://linux-hardware.org/?probe=5145350f9a) | Dec 21, 2022 |
| Acer          | Aspire 5680                 | Notebook    | [9b188c358e](https://linux-hardware.org/?probe=9b188c358e) | Dec 21, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [6a6ba7eba1](https://linux-hardware.org/?probe=6a6ba7eba1) | Dec 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [90331ea7da](https://linux-hardware.org/?probe=90331ea7da) | Dec 21, 2022 |
| Dell          | Latitude 5521               | Notebook    | [6fcbfd9271](https://linux-hardware.org/?probe=6fcbfd9271) | Dec 21, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [638667a90f](https://linux-hardware.org/?probe=638667a90f) | Dec 20, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [82687103ac](https://linux-hardware.org/?probe=82687103ac) | Dec 20, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [7f18d05353](https://linux-hardware.org/?probe=7f18d05353) | Dec 20, 2022 |
| HP            | 3048h                       | Desktop     | [4535cf0f5a](https://linux-hardware.org/?probe=4535cf0f5a) | Dec 20, 2022 |
| HP            | 3048h                       | Desktop     | [1d795fdd33](https://linux-hardware.org/?probe=1d795fdd33) | Dec 19, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [2aeb8fd0cd](https://linux-hardware.org/?probe=2aeb8fd0cd) | Dec 19, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [2fa8510855](https://linux-hardware.org/?probe=2fa8510855) | Dec 19, 2022 |
| ASUSTek       | N750JK                      | Notebook    | [8d876c21b0](https://linux-hardware.org/?probe=8d876c21b0) | Dec 18, 2022 |
| ASUSTek       | N750JK                      | Notebook    | [71575f3d8c](https://linux-hardware.org/?probe=71575f3d8c) | Dec 18, 2022 |
| HP            | ProLiant ML350 G6           | Desktop     | [3b242628e4](https://linux-hardware.org/?probe=3b242628e4) | Dec 18, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [06f90011b2](https://linux-hardware.org/?probe=06f90011b2) | Dec 18, 2022 |
| Acer          | Aspire 5680                 | Notebook    | [64f5eb2f4b](https://linux-hardware.org/?probe=64f5eb2f4b) | Dec 17, 2022 |
| ASUSTek       | K50IE                       | Notebook    | [5681babfa5](https://linux-hardware.org/?probe=5681babfa5) | Dec 17, 2022 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [db147cf534](https://linux-hardware.org/?probe=db147cf534) | Dec 17, 2022 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [fa2cc2d975](https://linux-hardware.org/?probe=fa2cc2d975) | Dec 17, 2022 |
| Acer          | Aspire XC-1660 V:1.1        | Desktop     | [88aa1f841a](https://linux-hardware.org/?probe=88aa1f841a) | Dec 17, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [30f6db8749](https://linux-hardware.org/?probe=30f6db8749) | Dec 17, 2022 |
| Acer          | Aspire E5-575               | Notebook    | [3fd939cef5](https://linux-hardware.org/?probe=3fd939cef5) | Dec 17, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [182e467ce6](https://linux-hardware.org/?probe=182e467ce6) | Dec 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [4d39c63e0a](https://linux-hardware.org/?probe=4d39c63e0a) | Dec 17, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [e070540587](https://linux-hardware.org/?probe=e070540587) | Dec 16, 2022 |
| ASUSTek       | X99-WS/IPMI                 | Desktop     | [41f02987e9](https://linux-hardware.org/?probe=41f02987e9) | Dec 16, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [7b3f9b5af0](https://linux-hardware.org/?probe=7b3f9b5af0) | Dec 16, 2022 |
| Dell          | Latitude 3120               | Notebook    | [e886df2722](https://linux-hardware.org/?probe=e886df2722) | Dec 16, 2022 |
| Acer          | Nitro AN517-54              | Notebook    | [cb963df304](https://linux-hardware.org/?probe=cb963df304) | Dec 16, 2022 |
| MSI           | GP75 Leopard 10SEK          | Notebook    | [9eda9896f3](https://linux-hardware.org/?probe=9eda9896f3) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [eeb913fa7c](https://linux-hardware.org/?probe=eeb913fa7c) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [7a72cfa484](https://linux-hardware.org/?probe=7a72cfa484) | Dec 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [bc8782be9a](https://linux-hardware.org/?probe=bc8782be9a) | Dec 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d320b71c77](https://linux-hardware.org/?probe=d320b71c77) | Dec 15, 2022 |
| HP            | 3048h                       | Desktop     | [63f57e3458](https://linux-hardware.org/?probe=63f57e3458) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [72175490ae](https://linux-hardware.org/?probe=72175490ae) | Dec 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [35ef32b165](https://linux-hardware.org/?probe=35ef32b165) | Dec 14, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [b90d5cfed0](https://linux-hardware.org/?probe=b90d5cfed0) | Dec 14, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [de26ffa293](https://linux-hardware.org/?probe=de26ffa293) | Dec 14, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [dd65da9c9b](https://linux-hardware.org/?probe=dd65da9c9b) | Dec 14, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [e94792b948](https://linux-hardware.org/?probe=e94792b948) | Dec 13, 2022 |
| Gigabyte      | P35-DS4                     | Desktop     | [3f787740f8](https://linux-hardware.org/?probe=3f787740f8) | Dec 12, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [ee22896cd2](https://linux-hardware.org/?probe=ee22896cd2) | Dec 12, 2022 |
| Intel         | NUC6CAYB J23203-410         | Mini pc     | [e9c5ef16cd](https://linux-hardware.org/?probe=e9c5ef16cd) | Dec 12, 2022 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [1db3976bb5](https://linux-hardware.org/?probe=1db3976bb5) | Dec 12, 2022 |
| HP            | 339A                        | Desktop     | [63c184fafd](https://linux-hardware.org/?probe=63c184fafd) | Dec 12, 2022 |
| Dell          | Inspiron 7306 2n1           | Convertible | [f1aa6058e3](https://linux-hardware.org/?probe=f1aa6058e3) | Dec 12, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [56adac1fcb](https://linux-hardware.org/?probe=56adac1fcb) | Dec 12, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [2c52e941ea](https://linux-hardware.org/?probe=2c52e941ea) | Dec 11, 2022 |
| Medion        | E4251                       | Notebook    | [f7303bf4c9](https://linux-hardware.org/?probe=f7303bf4c9) | Dec 11, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | Notebook    | [cd7399049b](https://linux-hardware.org/?probe=cd7399049b) | Dec 11, 2022 |
| Supermicro    | C7SIM-Q                     | Desktop     | [76cf2b62db](https://linux-hardware.org/?probe=76cf2b62db) | Dec 11, 2022 |
| Medion        | E4251                       | Notebook    | [a16b01515b](https://linux-hardware.org/?probe=a16b01515b) | Dec 10, 2022 |
| HP            | 3048h                       | Desktop     | [c2fd939c1f](https://linux-hardware.org/?probe=c2fd939c1f) | Dec 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [173f4b722f](https://linux-hardware.org/?probe=173f4b722f) | Dec 10, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [25d5b5623b](https://linux-hardware.org/?probe=25d5b5623b) | Dec 10, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [869e2a9671](https://linux-hardware.org/?probe=869e2a9671) | Dec 09, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [503b61f120](https://linux-hardware.org/?probe=503b61f120) | Dec 09, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [95d47d14cb](https://linux-hardware.org/?probe=95d47d14cb) | Dec 09, 2022 |
| MSI           | Modern 15 A11MU             | Notebook    | [e5ba0c8749](https://linux-hardware.org/?probe=e5ba0c8749) | Dec 09, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [1a4bdc4874](https://linux-hardware.org/?probe=1a4bdc4874) | Dec 07, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [61a9d5f84c](https://linux-hardware.org/?probe=61a9d5f84c) | Dec 07, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [611fd80398](https://linux-hardware.org/?probe=611fd80398) | Dec 07, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [27dc9420ed](https://linux-hardware.org/?probe=27dc9420ed) | Dec 07, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [9b7c1953a6](https://linux-hardware.org/?probe=9b7c1953a6) | Dec 07, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ce802653d4](https://linux-hardware.org/?probe=ce802653d4) | Dec 07, 2022 |
| Lenovo        | ThinkPad T510 4349AF5       | Notebook    | [a7d8d66fb7](https://linux-hardware.org/?probe=a7d8d66fb7) | Dec 07, 2022 |
| Dell          | XPS 9320                    | Notebook    | [34c3b0b6a0](https://linux-hardware.org/?probe=34c3b0b6a0) | Dec 06, 2022 |
| Medion        | E4251                       | Notebook    | [a515c5c071](https://linux-hardware.org/?probe=a515c5c071) | Dec 05, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [da82fb083d](https://linux-hardware.org/?probe=da82fb083d) | Dec 05, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [1798adf382](https://linux-hardware.org/?probe=1798adf382) | Dec 05, 2022 |
| ASUSTek       | X756UQK                     | Notebook    | [b473216b84](https://linux-hardware.org/?probe=b473216b84) | Dec 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [05f6a48b4a](https://linux-hardware.org/?probe=05f6a48b4a) | Dec 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c22a748043](https://linux-hardware.org/?probe=c22a748043) | Dec 05, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [86e9e1e21e](https://linux-hardware.org/?probe=86e9e1e21e) | Dec 05, 2022 |
| Acer          | Aspire V3-772               | Notebook    | [942312fe9e](https://linux-hardware.org/?probe=942312fe9e) | Dec 05, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [344b0c3082](https://linux-hardware.org/?probe=344b0c3082) | Dec 05, 2022 |
| Medion        | E4251 MD61435               | Notebook    | [481a9c958a](https://linux-hardware.org/?probe=481a9c958a) | Dec 04, 2022 |
| ASRock        | X300-ITX                    | Desktop     | [77d8c41481](https://linux-hardware.org/?probe=77d8c41481) | Dec 04, 2022 |
| Intel         | Unknown                     | Desktop     | [d00187a52a](https://linux-hardware.org/?probe=d00187a52a) | Dec 04, 2022 |
| Acer          | Aspire ES1-732              | Notebook    | [7000f5ee26](https://linux-hardware.org/?probe=7000f5ee26) | Dec 04, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [101ea9ca8e](https://linux-hardware.org/?probe=101ea9ca8e) | Dec 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [d8890572a5](https://linux-hardware.org/?probe=d8890572a5) | Dec 03, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [2cf560b162](https://linux-hardware.org/?probe=2cf560b162) | Dec 03, 2022 |
| Medion        | E4251 MD61435               | Notebook    | [c3f4fd226e](https://linux-hardware.org/?probe=c3f4fd226e) | Dec 03, 2022 |
| Medion        | E4251                       | Notebook    | [3167cbece1](https://linux-hardware.org/?probe=3167cbece1) | Dec 03, 2022 |
| ASRock        | Z87 Extreme4                | Desktop     | [422dde5ae5](https://linux-hardware.org/?probe=422dde5ae5) | Dec 03, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Netherlands/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 580       | 13.82%  |
| Ubuntu 18.04                 | 305       | 7.27%   |
| Ubuntu 22.04                 | 227       | 5.41%   |
| OpenMandriva 4.3             | 196       | 4.67%   |
| Debian 11                    | 102       | 2.43%   |
| Zorin 16                     | 91        | 2.17%   |
| Linux Mint 20.3              | 77        | 1.83%   |
| Ubuntu 20.10                 | 66        | 1.57%   |
| Arch                         | 66        | 1.57%   |
| Arch Rolling                 | 59        | 1.41%   |
| Manjaro                      | 57        | 1.36%   |
| Xubuntu 20.04                | 56        | 1.33%   |
| Linux Mint 21.1              | 56        | 1.33%   |
| OpenMandriva 4.2             | 55        | 1.31%   |
| KDE neon 20.04               | 54        | 1.29%   |
| Pop!_OS 22.04                | 53        | 1.26%   |
| Fedora 36                    | 53        | 1.26%   |
| Fedora 34                    | 53        | 1.26%   |
| openSUSE Tumbleweed-XXXXXXXX | 52        | 1.24%   |
| Linux Mint 20.2              | 52        | 1.24%   |
| Ubuntu 21.10                 | 51        | 1.22%   |
| Fedora 37                    | 49        | 1.17%   |
| Ubuntu 21.04                 | 46        | 1.1%    |
| Linux Mint 20.1              | 46        | 1.1%    |
| Linux Mint 19.3              | 46        | 1.1%    |
| Fedora 35                    | 44        | 1.05%   |
| Ubuntu 19.10                 | 43        | 1.02%   |
| Pop!_OS 20.10                | 41        | 0.98%   |
| Fedora 33                    | 41        | 0.98%   |
| Pop!_OS 21.04                | 39        | 0.93%   |
| Pop!_OS 20.04                | 39        | 0.93%   |
| ArcoLinux Rolling            | 39        | 0.93%   |
| Zorin 15                     | 38        | 0.91%   |
| Linux Mint 20                | 38        | 0.91%   |
| Kubuntu 20.04                | 38        | 0.91%   |
| Fedora 31                    | 38        | 0.91%   |
| Ubuntu 22.10                 | 35        | 0.83%   |
| Ubuntu 19.04                 | 35        | 0.83%   |
| Pop!_OS 21.10                | 35        | 0.83%   |
| OpenMandriva 23.01           | 33        | 0.79%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1372      | 34.44%  |
| Linux Mint    | 359       | 9.01%   |
| OpenMandriva  | 321       | 8.06%   |
| Fedora        | 311       | 7.81%   |
| Pop!_OS       | 199       | 4.99%   |
| Debian        | 164       | 4.12%   |
| Manjaro       | 154       | 3.87%   |
| Zorin         | 138       | 3.46%   |
| Arch          | 126       | 3.16%   |
| Xubuntu       | 98        | 2.46%   |
| Kubuntu       | 89        | 2.23%   |
| KDE neon      | 74        | 1.86%   |
| openSUSE      | 68        | 1.71%   |
| ArcoLinux     | 42        | 1.05%   |
| Kali          | 30        | 0.75%   |
| Gentoo        | 30        | 0.75%   |
| EndeavourOS   | 30        | 0.75%   |
| Elementary    | 27        | 0.68%   |
| ROSA          | 26        | 0.65%   |
| Lubuntu       | 26        | 0.65%   |
| Ubuntu Unity  | 23        | 0.58%   |
| Ubuntu MATE   | 21        | 0.53%   |
| SteamOS       | 21        | 0.53%   |
| Clear Linux   | 20        | 0.5%    |
| Endless       | 16        | 0.4%    |
| Parrot        | 15        | 0.38%   |
| Ubuntu Budgie | 14        | 0.35%   |
| LMDE          | 13        | 0.33%   |
| MX            | 12        | 0.3%    |
| Peppermint    | 10        | 0.25%   |
| Garuda Linux  | 10        | 0.25%   |
| CentOS        | 10        | 0.25%   |
| Solus         | 9         | 0.23%   |
| Raspbian      | 9         | 0.23%   |
| Nobara        | 8         | 0.2%    |
| BlackPanther  | 6         | 0.15%   |
| RHEL          | 5         | 0.13%   |
| Reborn OS     | 5         | 0.13%   |
| NixOS         | 4         | 0.1%    |
| LinuxFX       | 4         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 195       | 4.18%   |
| 5.4.0-42-generic         | 69        | 1.48%   |
| 5.10.14-desktop-1omv4002 | 54        | 1.16%   |
| 5.4.0-58-generic         | 43        | 0.92%   |
| 5.8.0-50-generic         | 42        | 0.9%    |
| 5.15.0-56-generic        | 39        | 0.84%   |
| 5.15.0-58-generic        | 37        | 0.79%   |
| 5.4.0-52-generic         | 36        | 0.77%   |
| 5.4.0-48-generic         | 35        | 0.75%   |
| 5.11.0-38-generic        | 33        | 0.71%   |
| 5.15.0-46-generic        | 30        | 0.64%   |
| 6.1.1-desktop-1omv2290   | 27        | 0.58%   |
| 5.8.0-43-generic         | 26        | 0.56%   |
| 5.4.0-26-generic         | 26        | 0.56%   |
| 5.13.0-28-generic        | 26        | 0.56%   |
| 5.11.0-27-generic        | 26        | 0.56%   |
| 6.2.6-desktop-1omv2390   | 25        | 0.54%   |
| 5.4.0-77-generic         | 25        | 0.54%   |
| 5.15.0-52-generic        | 25        | 0.54%   |
| 5.4.0-40-generic         | 24        | 0.51%   |
| 5.15.0-43-generic        | 24        | 0.51%   |
| 5.19.0-35-generic        | 23        | 0.49%   |
| 5.4.0-37-generic         | 22        | 0.47%   |
| 5.15.0-48-generic        | 22        | 0.47%   |
| 5.8.0-53-generic         | 21        | 0.45%   |
| 5.4.0-65-generic         | 21        | 0.45%   |
| 5.15.0-67-generic        | 21        | 0.45%   |
| 5.15.0-60-generic        | 21        | 0.45%   |
| 5.13.0-39-generic        | 21        | 0.45%   |
| 5.11.0-7620-generic      | 21        | 0.45%   |
| 5.8.0-7630-generic       | 20        | 0.43%   |
| 5.4.0-56-generic         | 20        | 0.43%   |
| 5.4.0-33-generic         | 20        | 0.43%   |
| 5.4.0-29-generic         | 20        | 0.43%   |
| 5.3.0-46-generic         | 19        | 0.41%   |
| 5.8.0-48-generic         | 18        | 0.39%   |
| 5.4.0-54-generic         | 18        | 0.39%   |
| 5.4.0-47-generic         | 18        | 0.39%   |
| 5.11.0-43-generic        | 18        | 0.39%   |
| 4.15.0-29-generic        | 18        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 721       | 16.5%   |
| 5.15.0  | 383       | 8.76%   |
| 5.8.0   | 285       | 6.52%   |
| 4.15.0  | 240       | 5.49%   |
| 5.11.0  | 235       | 5.38%   |
| 5.13.0  | 202       | 4.62%   |
| 5.16.7  | 198       | 4.53%   |
| 5.3.0   | 141       | 3.23%   |
| 5.19.0  | 129       | 2.95%   |
| 5.10.0  | 119       | 2.72%   |
| 5.0.0   | 106       | 2.43%   |
| 4.18.0  | 72        | 1.65%   |
| 5.10.14 | 57        | 1.3%    |
| 4.19.0  | 37        | 0.85%   |
| 6.2.6   | 36        | 0.82%   |
| 6.1.1   | 31        | 0.71%   |
| 5.14.0  | 23        | 0.53%   |
| 6.2.0   | 20        | 0.46%   |
| 6.1.0   | 20        | 0.46%   |
| 4.4.0   | 18        | 0.41%   |
| 5.6.0   | 16        | 0.37%   |
| 5.16.11 | 16        | 0.37%   |
| 5.17.5  | 15        | 0.34%   |
| 6.0.6   | 14        | 0.32%   |
| 5.9.16  | 14        | 0.32%   |
| 6.3.0   | 13        | 0.3%    |
| 6.0.0   | 12        | 0.27%   |
| 5.3.18  | 11        | 0.25%   |
| 5.18.0  | 11        | 0.25%   |
| 5.17.1  | 11        | 0.25%   |
| 6.0.12  | 10        | 0.23%   |
| 5.17.0  | 10        | 0.23%   |
| 5.16.0  | 10        | 0.23%   |
| 6.2.9   | 9         | 0.21%   |
| 6.2.8   | 9         | 0.21%   |
| 5.9.8   | 9         | 0.21%   |
| 5.9.0   | 9         | 0.21%   |
| 5.8.16  | 9         | 0.21%   |
| 5.16.19 | 9         | 0.21%   |
| 5.15.5  | 9         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 785       | 18.18%  |
| 5.15    | 496       | 11.48%  |
| 5.8     | 336       | 7.78%   |
| 5.11    | 281       | 6.51%   |
| 5.16    | 265       | 6.14%   |
| 5.13    | 244       | 5.65%   |
| 5.10    | 242       | 5.6%    |
| 4.15    | 241       | 5.58%   |
| 5.3     | 173       | 4.01%   |
| 5.19    | 167       | 3.87%   |
| 6.1     | 117       | 2.71%   |
| 5.0     | 110       | 2.55%   |
| 6.2     | 108       | 2.5%    |
| 4.18    | 86        | 1.99%   |
| 6.0     | 84        | 1.94%   |
| 5.17    | 69        | 1.6%    |
| 5.14    | 62        | 1.44%   |
| 5.18    | 61        | 1.41%   |
| 5.9     | 56        | 1.3%    |
| 5.6     | 51        | 1.18%   |
| 4.19    | 50        | 1.16%   |
| 6.3     | 49        | 1.13%   |
| 5.12    | 36        | 0.83%   |
| 5.7     | 32        | 0.74%   |
| 5.5     | 28        | 0.65%   |
| 4.9     | 26        | 0.6%    |
| 4.4     | 20        | 0.46%   |
| 5.2     | 9         | 0.21%   |
| 4.16    | 5         | 0.12%   |
| 4.10    | 5         | 0.12%   |
| 4.20    | 4         | 0.09%   |
| 4.14    | 4         | 0.09%   |
| 4.12    | 4         | 0.09%   |
| 3.10    | 3         | 0.07%   |
| 4.1     | 2         | 0.05%   |
| 3.16    | 2         | 0.05%   |
| 6.4     | 1         | 0.02%   |
| 5.17.1  | 1         | 0.02%   |
| 5.1     | 1         | 0.02%   |
| 4.7     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3716      | 96.07%  |
| i686    | 102       | 2.64%   |
| aarch64 | 41        | 1.06%   |
| armv7l  | 7         | 0.18%   |
| armv8l  | 1         | 0.03%   |
| armv6l  | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 1784      | 44.37%  |
| KDE5             | 703       | 17.48%  |
| Unknown          | 533       | 13.26%  |
| XFCE             | 285       | 7.09%   |
| X-Cinnamon       | 272       | 6.76%   |
| KDE              | 93        | 2.31%   |
| MATE             | 89        | 2.21%   |
| Cinnamon         | 36        | 0.9%    |
| LXQt             | 28        | 0.7%    |
| Pantheon         | 27        | 0.67%   |
| LXDE             | 24        | 0.6%    |
| Budgie           | 24        | 0.6%    |
| Unity            | 23        | 0.57%   |
| i3               | 22        | 0.55%   |
| KDE4             | 15        | 0.37%   |
| GNOME Flashback  | 12        | 0.3%    |
| Openbox          | 7         | 0.17%   |
| Deepin           | 6         | 0.15%   |
| sway             | 5         | 0.12%   |
| ICEWM            | 5         | 0.12%   |
| Enlightenment    | 5         | 0.12%   |
| qtile            | 4         | 0.1%    |
| awesome          | 4         | 0.1%    |
| trinity          | 2         | 0.05%   |
| lightdm-xsession | 2         | 0.05%   |
| GNOME Classic    | 2         | 0.05%   |
| xmonad           | 1         | 0.02%   |
| LeftWM           | 1         | 0.02%   |
| jwm              | 1         | 0.02%   |
| herbstluftwm     | 1         | 0.02%   |
| fluxbox          | 1         | 0.02%   |
| DWM              | 1         | 0.02%   |
| dusk             | 1         | 0.02%   |
| Core             | 1         | 0.02%   |
| bspwm            | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2979      | 75.21%  |
| Wayland | 637       | 16.08%  |
| Unknown | 260       | 6.56%   |
| Tty     | 84        | 2.12%   |
| Web     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2025      | 50.6%   |
| SDDM    | 592       | 14.79%  |
| GDM     | 469       | 11.72%  |
| GDM3    | 435       | 10.87%  |
| LightDM | 351       | 8.77%   |
| TDM     | 94        | 2.35%   |
| KDM     | 14        | 0.35%   |
| XDM     | 8         | 0.2%    |
| Ly      | 4         | 0.1%    |
| SLiM    | 3         | 0.07%   |
| GREETD  | 3         | 0.07%   |
| LXDM    | 2         | 0.05%   |
| NODM    | 1         | 0.02%   |
| MDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 1900      | 47.96%  |
| nl_NL       | 1136      | 28.67%  |
| Unknown     | 431       | 10.88%  |
| en_GB       | 163       | 4.11%   |
| C           | 64        | 1.62%   |
| de_DE       | 40        | 1.01%   |
| pl_PL       | 33        | 0.83%   |
| ru_RU       | 26        | 0.66%   |
| en_IE       | 14        | 0.35%   |
| POSIX       | 13        | 0.33%   |
| fr_FR       | 12        | 0.3%    |
| en_NL       | 12        | 0.3%    |
| it_IT       | 8         | 0.2%    |
| en_IN       | 7         | 0.18%   |
| en_CA       | 7         | 0.18%   |
| es_ES       | 6         | 0.15%   |
| fr_BE       | 5         | 0.13%   |
| en_DK       | 5         | 0.13%   |
| en_AG       | 5         | 0.13%   |
| C.UTF8      | 5         | 0.13%   |
| sv_SE       | 4         | 0.1%    |
| ru_UA       | 4         | 0.1%    |
| pt_PT       | 4         | 0.1%    |
| nl_BE       | 4         | 0.1%    |
| es_MX       | 4         | 0.1%    |
| de_AT       | 4         | 0.1%    |
| sk_SK       | 3         | 0.08%   |
| nb_NO       | 3         | 0.08%   |
| hu_HU       | 3         | 0.08%   |
| en_US.utf-8 | 3         | 0.08%   |
| en_AU       | 3         | 0.08%   |
| cs_CZ       | 3         | 0.08%   |
| zh_CN       | 2         | 0.05%   |
| uk_UA       | 2         | 0.05%   |
| pt_BR       | 2         | 0.05%   |
| nl_AW       | 2         | 0.05%   |
| en_ZA       | 2         | 0.05%   |
| en_SG       | 2         | 0.05%   |
| ar_KW       | 2         | 0.05%   |
| tr_TR       | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2040      | 51.76%  |
| BIOS | 1901      | 48.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2959      | 74.89%  |
| Overlay | 361       | 9.14%   |
| Btrfs   | 349       | 8.83%   |
| Unknown | 125       | 3.16%   |
| Xfs     | 51        | 1.29%   |
| Zfs     | 41        | 1.04%   |
| Tmpfs   | 37        | 0.94%   |
| Ext2    | 10        | 0.25%   |
| F2fs    | 9         | 0.23%   |
| Ext3    | 5         | 0.13%   |
| Aufs    | 3         | 0.08%   |
| Jfs     | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2154      | 54.63%  |
| GPT     | 1449      | 36.75%  |
| MBR     | 340       | 8.62%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3357      | 85.35%  |
| Yes       | 576       | 14.65%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2757      | 70.39%  |
| Yes       | 1160      | 29.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 626       | 16.21%  |
| Hewlett-Packard         | 609       | 15.77%  |
| ASUSTek Computer        | 540       | 13.99%  |
| Lenovo                  | 435       | 11.27%  |
| Acer                    | 239       | 6.19%   |
| Gigabyte Technology     | 217       | 5.62%   |
| MSI                     | 212       | 5.49%   |
| ASRock                  | 154       | 3.99%   |
| Apple                   | 120       | 3.11%   |
| Intel                   | 84        | 2.18%   |
| Medion                  | 61        | 1.58%   |
| Toshiba                 | 56        | 1.45%   |
| Notebook                | 52        | 1.35%   |
| Raspberry Pi Foundation | 43        | 1.11%   |
| Unknown                 | 28        | 0.73%   |
| Packard Bell            | 27        | 0.7%    |
| Samsung Electronics     | 26        | 0.67%   |
| Fujitsu                 | 22        | 0.57%   |
| Google                  | 19        | 0.49%   |
| Valve                   | 18        | 0.47%   |
| Sony                    | 16        | 0.41%   |
| Microsoft               | 16        | 0.41%   |
| HUAWEI                  | 14        | 0.36%   |
| Fujitsu Siemens         | 13        | 0.34%   |
| Foxconn                 | 12        | 0.31%   |
| Alienware               | 10        | 0.26%   |
| Supermicro              | 9         | 0.23%   |
| Pegatron                | 8         | 0.21%   |
| Biostar                 | 7         | 0.18%   |
| AMI                     | 7         | 0.18%   |
| TUXEDO                  | 6         | 0.16%   |
| Timi                    | 6         | 0.16%   |
| Shuttle                 | 6         | 0.16%   |
| Insyde                  | 6         | 0.16%   |
| BESSTAR Tech            | 6         | 0.16%   |
| ZOTAC                   | 5         | 0.13%   |
| PC Specialist           | 5         | 0.13%   |
| Chuwi                   | 5         | 0.13%   |
| System76                | 4         | 0.1%    |
| SLIMBOOK                | 4         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Dell Latitude 3120                  | 56        | 1.45%   |
| Dell Latitude 3190 2-in-1           | 41        | 1.06%   |
| Unknown                             | 40        | 1.04%   |
| Dell Latitude 3310                  | 32        | 0.83%   |
| ASUS All Series                     | 29        | 0.75%   |
| Valve Jupiter                       | 18        | 0.47%   |
| RPi Raspberry Pi                    | 17        | 0.44%   |
| Dell XPS 15 7590                    | 12        | 0.31%   |
| Dell OptiPlex 7010                  | 11        | 0.28%   |
| RPi Raspberry Pi 4 Model B Rev 1.4  | 10        | 0.26%   |
| MSI MS-7C02                         | 10        | 0.26%   |
| HP Notebook                         | 10        | 0.26%   |
| HP Pavilion dv7                     | 9         | 0.23%   |
| Dell XPS 15 9560                    | 9         | 0.23%   |
| Apple MacBookPro9,2                 | 9         | 0.23%   |
| MSI MS-7C37                         | 8         | 0.21%   |
| HP ZBook Studio G5                  | 8         | 0.21%   |
| HP Pavilion g7                      | 8         | 0.21%   |
| Dell OptiPlex 3020                  | 8         | 0.21%   |
| Dell Latitude E6410                 | 8         | 0.21%   |
| Dell Latitude 3300                  | 8         | 0.21%   |
| ASRock B450M Pro4                   | 8         | 0.21%   |
| MSI MS-7B86                         | 7         | 0.18%   |
| MSI MS-7817                         | 7         | 0.18%   |
| HP Pavilion Laptop 15-cw1xxx        | 7         | 0.18%   |
| HP Pavilion Gaming Laptop 15-cx0xxx | 7         | 0.18%   |
| HP Pavilion g6                      | 7         | 0.18%   |
| Dell XPS 13 9310                    | 7         | 0.18%   |
| Dell Latitude 3189                  | 7         | 0.18%   |
| MSI MS-7721                         | 6         | 0.16%   |
| Intel NUC8i3BEH                     | 6         | 0.16%   |
| HP ProBook 6570b                    | 6         | 0.16%   |
| HP Pavilion dv6                     | 6         | 0.16%   |
| HP EliteBook 8570w                  | 6         | 0.16%   |
| HP EliteBook 8460p                  | 6         | 0.16%   |
| HP Compaq Elite 8300 SFF            | 6         | 0.16%   |
| HP Compaq dc7900 Small Form Factor  | 6         | 0.16%   |
| Gigabyte X570 AORUS PRO             | 6         | 0.16%   |
| Gigabyte B450M DS3H                 | 6         | 0.16%   |
| Dell XPS 15 9570                    | 6         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 319       | 8.26%   |
| Lenovo ThinkPad       | 219       | 5.67%   |
| Acer Aspire           | 163       | 4.22%   |
| HP Compaq             | 104       | 2.69%   |
| HP EliteBook          | 103       | 2.67%   |
| HP Pavilion           | 102       | 2.64%   |
| Dell XPS              | 102       | 2.64%   |
| Lenovo IdeaPad        | 71        | 1.84%   |
| HP ProBook            | 68        | 1.76%   |
| Dell OptiPlex         | 65        | 1.68%   |
| ASUS PRIME            | 59        | 1.53%   |
| Toshiba Satellite     | 51        | 1.32%   |
| ASUS ROG              | 51        | 1.32%   |
| Dell Inspiron         | 49        | 1.27%   |
| RPi Raspberry         | 43        | 1.11%   |
| Unknown               | 40        | 1.04%   |
| Dell Precision        | 36        | 0.93%   |
| HP ZBook              | 35        | 0.91%   |
| Lenovo Yoga           | 32        | 0.83%   |
| HP ENVY               | 29        | 0.75%   |
| ASUS All              | 29        | 0.75%   |
| Lenovo Legion         | 27        | 0.7%    |
| ASUS VivoBook         | 23        | 0.6%    |
| HP Laptop             | 21        | 0.54%   |
| Packard Bell EasyNote | 20        | 0.52%   |
| Gigabyte X570         | 20        | 0.52%   |
| ASUS TUF              | 20        | 0.52%   |
| Valve Jupiter         | 18        | 0.47%   |
| Microsoft Surface     | 16        | 0.41%   |
| Lenovo ThinkCentre    | 16        | 0.41%   |
| Lenovo ThinkBook      | 16        | 0.41%   |
| HP ProDesk            | 15        | 0.39%   |
| ASUS ZenBook          | 14        | 0.36%   |
| Acer TravelMate       | 14        | 0.36%   |
| Acer Swift            | 14        | 0.36%   |
| Fujitsu LIFEBOOK      | 13        | 0.34%   |
| HP Spectre            | 12        | 0.31%   |
| HP EliteDesk          | 11        | 0.28%   |
| Dell Studio           | 11        | 0.28%   |
| ASRock B450M          | 11        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 450       | 11.66%  |
| 2018    | 338       | 8.75%   |
| 2020    | 303       | 7.85%   |
| 2012    | 291       | 7.54%   |
| 2021    | 290       | 7.51%   |
| 2011    | 255       | 6.6%    |
| 2013    | 243       | 6.29%   |
| 2017    | 233       | 6.03%   |
| 2014    | 209       | 5.41%   |
| 2010    | 197       | 5.1%    |
| 2016    | 193       | 5%      |
| 2015    | 190       | 4.92%   |
| 2008    | 153       | 3.96%   |
| 2009    | 152       | 3.94%   |
| 2022    | 123       | 3.19%   |
| 2007    | 113       | 2.93%   |
| 2006    | 50        | 1.3%    |
| Unknown | 45        | 1.17%   |
| 2005    | 12        | 0.31%   |
| 2023    | 11        | 0.28%   |
| 2004    | 6         | 0.16%   |
| 2003    | 3         | 0.08%   |
| 2002    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2062      | 53.41%  |
| Desktop        | 1343      | 34.78%  |
| Convertible    | 199       | 5.15%   |
| Mini pc        | 91        | 2.36%   |
| All in one     | 50        | 1.3%    |
| System on chip | 47        | 1.22%   |
| Tablet         | 41        | 1.06%   |
| Server         | 26        | 0.67%   |
| Phone          | 2         | 0.05%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3568      | 91.75%  |
| Enabled  | 321       | 8.25%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3836      | 99.35%  |
| Yes  | 25        | 0.65%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 905       | 23.06%  |
| 16.01-24.0      | 814       | 20.74%  |
| 3.01-4.0        | 714       | 18.19%  |
| 8.01-16.0       | 661       | 16.84%  |
| 32.01-64.0      | 404       | 10.29%  |
| 1.01-2.0        | 148       | 3.77%   |
| 64.01-256.0     | 100       | 2.55%   |
| 24.01-32.0      | 72        | 1.83%   |
| 2.01-3.0        | 69        | 1.76%   |
| 0.51-1.0        | 36        | 0.92%   |
| More than 256.0 | 1         | 0.03%   |
| 0.01-0.5        | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1561      | 36.7%   |
| 2.01-3.0    | 991       | 23.3%   |
| 4.01-8.0    | 586       | 13.78%  |
| 3.01-4.0    | 543       | 12.77%  |
| 0.51-1.0    | 273       | 6.42%   |
| 8.01-16.0   | 207       | 4.87%   |
| 0.01-0.5    | 40        | 0.94%   |
| 16.01-24.0  | 36        | 0.85%   |
| 32.01-64.0  | 12        | 0.28%   |
| 24.01-32.0  | 3         | 0.07%   |
| 64.01-256.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2336      | 59.03%  |
| 2       | 972       | 24.56%  |
| 3       | 302       | 7.63%   |
| 4       | 150       | 3.79%   |
| 5       | 76        | 1.92%   |
| 0       | 52        | 1.31%   |
| 6       | 31        | 0.78%   |
| 7       | 21        | 0.53%   |
| 8       | 6         | 0.15%   |
| 9       | 4         | 0.1%    |
| Unknown | 4         | 0.1%    |
| 28      | 1         | 0.03%   |
| 27      | 1         | 0.03%   |
| 10      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2459      | 63.13%  |
| Yes       | 1436      | 36.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3223      | 83.2%   |
| No        | 651       | 16.8%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2866      | 73.89%  |
| No        | 1013      | 26.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2344      | 59.73%  |
| No        | 1580      | 40.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Netherlands | 3861      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Amsterdam              | 730       | 17.73%  |
| The Hague              | 200       | 4.86%   |
| Schagen                | 142       | 3.45%   |
| Rotterdam              | 139       | 3.38%   |
| Utrecht                | 99        | 2.4%    |
| Delft                  | 91        | 2.21%   |
| Haarlem                | 80        | 1.94%   |
| Groningen              | 69        | 1.68%   |
| Almere Stad            | 63        | 1.53%   |
| Eindhoven              | 58        | 1.41%   |
| Naaldwijk              | 51        | 1.24%   |
| Tilburg                | 47        | 1.14%   |
| Amersfoort             | 46        | 1.12%   |
| Enschede               | 43        | 1.04%   |
| Leiden                 | 40        | 0.97%   |
| Zoetermeer             | 35        | 0.85%   |
| Arnhem                 | 34        | 0.83%   |
| Nijmegen               | 33        | 0.8%    |
| Apeldoorn              | 31        | 0.75%   |
| Breda                  | 30        | 0.73%   |
| Almelo                 | 29        | 0.7%    |
| Zwolle                 | 25        | 0.61%   |
| Zeist                  | 24        | 0.58%   |
| Hilversum              | 24        | 0.58%   |
| Capelle aan den IJssel | 23        | 0.56%   |
| Maastricht             | 22        | 0.53%   |
| Lelystad               | 22        | 0.53%   |
| Heerlen                | 22        | 0.53%   |
| Dordrecht              | 22        | 0.53%   |
| Assen                  | 22        | 0.53%   |
| Amstelveen             | 22        | 0.53%   |
| Roosendaal             | 20        | 0.49%   |
| Alkmaar                | 20        | 0.49%   |
| 's-Hertogenbosch       | 20        | 0.49%   |
| Schiedam               | 18        | 0.44%   |
| Purmerend              | 18        | 0.44%   |
| Leeuwarden             | 18        | 0.44%   |
| Gouda                  | 18        | 0.44%   |
| Hoofddorp              | 17        | 0.41%   |
| Meppel                 | 16        | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1273      | 2066   | 22.99%  |
| WDC                         | 728       | 1118   | 13.15%  |
| Seagate                     | 672       | 1058   | 12.13%  |
| Kingston                    | 335       | 443    | 6.05%   |
| Toshiba                     | 305       | 416    | 5.51%   |
| SanDisk                     | 249       | 333    | 4.5%    |
| Crucial                     | 241       | 313    | 4.35%   |
| Unknown                     | 237       | 296    | 4.28%   |
| SK hynix                    | 196       | 229    | 3.54%   |
| Intel                       | 166       | 222    | 3%      |
| Hitachi                     | 165       | 213    | 2.98%   |
| HGST                        | 95        | 118    | 1.72%   |
| Micron Technology           | 68        | 82     | 1.23%   |
| A-DATA Technology           | 62        | 68     | 1.12%   |
| KIOXIA                      | 53        | 67     | 0.96%   |
| Apple                       | 53        | 74     | 0.96%   |
| LITEON                      | 42        | 53     | 0.76%   |
| OCZ                         | 31        | 39     | 0.56%   |
| Maxtor                      | 31        | 43     | 0.56%   |
| China                       | 29        | 40     | 0.52%   |
| Phison                      | 27        | 40     | 0.49%   |
| Corsair                     | 27        | 36     | 0.49%   |
| Transcend                   | 23        | 28     | 0.42%   |
| LITEONIT                    | 23        | 26     | 0.42%   |
| PNY                         | 22        | 27     | 0.4%    |
| Fujitsu                     | 21        | 23     | 0.38%   |
| SSSTC                       | 20        | 21     | 0.36%   |
| Kingston Technology Company | 19        | 22     | 0.34%   |
| Gigabyte Technology         | 16        | 21     | 0.29%   |
| ASMT                        | 16        | 18     | 0.29%   |
| Micron/Crucial Technology   | 15        | 19     | 0.27%   |
| Intenso                     | 14        | 14     | 0.25%   |
| Unknown                     | 14        | 17     | 0.25%   |
| SPCC                        | 13        | 14     | 0.23%   |
| Patriot                     | 13        | 16     | 0.23%   |
| KingFast                    | 13        | 17     | 0.23%   |
| GOODRAM                     | 13        | 14     | 0.23%   |
| JMicron Technology          | 12        | 19     | 0.22%   |
| Phison Electronics          | 11        | 15     | 0.2%    |
| Silicon Motion              | 9         | 10     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                           | 95        | 1.52%   |
| Samsung SSD 860 EVO 500GB                           | 67        | 1.08%   |
| Samsung SSD 850 EVO 500GB                           | 62        | 0.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 55        | 0.88%   |
| Samsung NVMe SSD Drive 500GB                        | 47        | 0.75%   |
| Samsung NVMe SSD Drive 1TB                          | 46        | 0.74%   |
| Kingston SA400S37240G 240GB SSD                     | 46        | 0.74%   |
| Unknown MMC Card  32GB                              | 44        | 0.71%   |
| Samsung SSD 840 EVO 250GB                           | 41        | 0.66%   |
| Kingston SA400S37120G 120GB SSD                     | 40        | 0.64%   |
| Crucial CT500MX500SSD1 500GB                        | 35        | 0.56%   |
| Seagate Expansion 1TB                               | 33        | 0.53%   |
| Samsung SSD 860 EVO 1TB                             | 33        | 0.53%   |
| Samsung SSD 840 EVO 120GB                           | 33        | 0.53%   |
| Kingston SV300S37A120G 120GB SSD                    | 31        | 0.5%    |
| Unknown MMC Card  64GB                              | 30        | 0.48%   |
| Seagate ST500DM002-1BD142 500GB                     | 30        | 0.48%   |
| Samsung SSD 980 1TB                                 | 30        | 0.48%   |
| Samsung SSD 970 EVO 1TB                             | 30        | 0.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 30        | 0.48%   |
| Seagate ST2000DM008-2FR102 2TB                      | 29        | 0.47%   |
| Samsung NVMe SSD Drive 256GB                        | 28        | 0.45%   |
| Seagate ST1000LM035-1RK172 1TB                      | 27        | 0.43%   |
| HGST HTS721010A9E630 1TB                            | 26        | 0.42%   |
| Samsung NVMe SSD Drive 512GB                        | 25        | 0.4%    |
| Crucial CT1000MX500SSD1 1TB                         | 25        | 0.4%    |
| Toshiba DT01ACA100 1TB                              | 24        | 0.39%   |
| Toshiba MQ01ABF050 500GB                            | 22        | 0.35%   |
| SK hynix BC711 NVMe 128GB                           | 22        | 0.35%   |
| Seagate ST9500325AS 500GB                           | 22        | 0.35%   |
| Samsung SSD 860 QVO 1TB                             | 22        | 0.35%   |
| Samsung NVMe SSD Drive 1024GB                       | 22        | 0.35%   |
| Crucial CT240BX500SSD1 240GB                        | 22        | 0.35%   |
| Samsung SSD 870 QVO 1TB                             | 21        | 0.34%   |
| Seagate ST1000DM010-2EP102 1TB                      | 20        | 0.32%   |
| SanDisk NVMe SSD Drive 512GB                        | 20        | 0.32%   |
| Samsung SSD 970 EVO Plus 1TB                        | 20        | 0.32%   |
| Toshiba MQ01ABD100 1TB                              | 19        | 0.3%    |
| Samsung SSD 860 EVO 250GB                           | 19        | 0.3%    |
| Samsung SSD 870 EVO 500GB                           | 17        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 662       | 1040   | 33.88%  |
| WDC                 | 586       | 912    | 29.99%  |
| Toshiba             | 207       | 292    | 10.59%  |
| Hitachi             | 165       | 213    | 8.44%   |
| Samsung Electronics | 136       | 217    | 6.96%   |
| HGST                | 95        | 118    | 4.86%   |
| Maxtor              | 31        | 43     | 1.59%   |
| Fujitsu             | 21        | 23     | 1.07%   |
| Apple               | 12        | 16     | 0.61%   |
| Unknown             | 8         | 15     | 0.41%   |
| JMicron Technology  | 3         | 6      | 0.15%   |
| Intenso             | 3         | 3      | 0.15%   |
| HGST HTS            | 3         | 4      | 0.15%   |
| ASMT                | 3         | 5      | 0.15%   |
| SAGE                | 2         | 2      | 0.1%    |
| IBM/Hitachi         | 2         | 2      | 0.1%    |
| ExcelStor           | 2         | 2      | 0.1%    |
| ASMedia             | 2         | 4      | 0.1%    |
| Synology            | 1         | 1      | 0.05%   |
| SSK                 | 1         | 1      | 0.05%   |
| QNAP                | 1         | 1      | 0.05%   |
| NAS                 | 1         | 10     | 0.05%   |
| Maxtor 6            | 1         | 2      | 0.05%   |
| Magnetic Data       | 1         | 1      | 0.05%   |
| LIO-ORG             | 1         | 4      | 0.05%   |
| LaCie               | 1         | 1      | 0.05%   |
| KESU                | 1         | 1      | 0.05%   |
| Inateck             | 1         | 1      | 0.05%   |
| Hewlett-Packard     | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 674       | 1007   | 34.14%  |
| Kingston            | 248       | 318    | 12.56%  |
| Crucial             | 230       | 302    | 11.65%  |
| SanDisk             | 159       | 197    | 8.05%   |
| WDC                 | 78        | 108    | 3.95%   |
| Intel               | 68        | 85     | 3.44%   |
| A-DATA Technology   | 51        | 57     | 2.58%   |
| SK hynix            | 46        | 57     | 2.33%   |
| LITEON              | 34        | 45     | 1.72%   |
| Micron Technology   | 32        | 43     | 1.62%   |
| OCZ                 | 31        | 39     | 1.57%   |
| China               | 29        | 40     | 1.47%   |
| Apple               | 29        | 36     | 1.47%   |
| Toshiba             | 27        | 33     | 1.37%   |
| LITEONIT            | 23        | 26     | 1.17%   |
| PNY                 | 22        | 27     | 1.11%   |
| Corsair             | 20        | 28     | 1.01%   |
| Transcend           | 19        | 24     | 0.96%   |
| SPCC                | 13        | 14     | 0.66%   |
| Patriot             | 13        | 16     | 0.66%   |
| GOODRAM             | 13        | 14     | 0.66%   |
| ASMT                | 12        | 12     | 0.61%   |
| Intenso             | 9         | 9      | 0.46%   |
| Gigabyte Technology | 6         | 10     | 0.3%    |
| Mushkin             | 5         | 7      | 0.25%   |
| KingSpec            | 5         | 6      | 0.25%   |
| KingFast            | 5         | 6      | 0.25%   |
| Netac               | 4         | 4      | 0.2%    |
| Apacer              | 4         | 4      | 0.2%    |
| ACASIS              | 4         | 4      | 0.2%    |
| Unknown             | 4         | 7      | 0.2%    |
| Unknown             | 3         | 3      | 0.15%   |
| Team                | 3         | 5      | 0.15%   |
| SSSTC               | 3         | 3      | 0.15%   |
| Plextor             | 3         | 4      | 0.15%   |
| Leven               | 3         | 3      | 0.15%   |
| Vaseky              | 2         | 2      | 0.1%    |
| Seagate             | 2         | 2      | 0.1%    |
| Phison              | 2         | 5      | 0.1%    |
| KingDian            | 2         | 3      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1736      | 2657   | 34.6%   |
| HDD     | 1612      | 2941   | 32.12%  |
| NVMe    | 1379      | 1961   | 27.48%  |
| MMC     | 235       | 283    | 4.68%   |
| Unknown | 56        | 70     | 1.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2677      | 5328   | 59.4%   |
| NVMe | 1373      | 1950   | 30.46%  |
| MMC  | 235       | 283    | 5.21%   |
| SAS  | 222       | 351    | 4.93%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2176      | 3423   | 61.85%  |
| 0.51-1.0   | 865       | 1306   | 24.59%  |
| 1.01-2.0   | 268       | 445    | 7.62%   |
| 3.01-4.0   | 78        | 163    | 2.22%   |
| 4.01-10.0  | 68        | 162    | 1.93%   |
| 2.01-3.0   | 60        | 84     | 1.71%   |
| 10.01-20.0 | 2         | 14     | 0.06%   |
| 20.01-50.0 | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1071      | 26.19%  |
| 251-500        | 795       | 19.44%  |
| 501-1000       | 535       | 13.08%  |
| 1-20           | 427       | 10.44%  |
| 1001-2000      | 346       | 8.46%   |
| 51-100         | 270       | 6.6%    |
| More than 3000 | 234       | 5.72%   |
| 21-50          | 180       | 4.4%    |
| 2001-3000      | 123       | 3.01%   |
| Unknown        | 109       | 2.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1696      | 40.21%  |
| 21-50          | 625       | 14.82%  |
| 101-250        | 483       | 11.45%  |
| 51-100         | 450       | 10.67%  |
| 251-500        | 310       | 7.35%   |
| 501-1000       | 262       | 6.21%   |
| 1001-2000      | 131       | 3.11%   |
| Unknown        | 109       | 2.58%   |
| More than 3000 | 98        | 2.32%   |
| 2001-3000      | 52        | 1.23%   |
| 0              | 2         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 4         | 4      | 1.65%   |
| SanDisk SD6SF1M128G1022I 128GB SSD    | 4         | 4      | 1.65%   |
| Kingston SV300S37A120G 120GB SSD      | 4         | 5      | 1.65%   |
| WDC WD10EADS-22M2B0 1TB               | 3         | 3      | 1.23%   |
| Toshiba MQ01ABF050 500GB              | 3         | 3      | 1.23%   |
| Seagate ST9250410AS 250GB             | 3         | 3      | 1.23%   |
| Intel SSDSC2BW120A4 120GB             | 3         | 4      | 1.23%   |
| HGST HTS725050A7E630 500GB            | 3         | 3      | 1.23%   |
| HGST HTS721010A9E630 1TB              | 3         | 4      | 1.23%   |
| Crucial CT128MX100SSD1 128GB          | 3         | 3      | 1.23%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 2         | 2      | 0.82%   |
| WDC WD60EFRX-68MYMN1 6TB              | 2         | 2      | 0.82%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 2         | 2      | 0.82%   |
| WDC WD1002FAEX-00Y9A0 1TB             | 2         | 2      | 0.82%   |
| Toshiba MQ01ABD050 500GB              | 2         | 3      | 0.82%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 2      | 0.82%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 0.82%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 0.82%   |
| Seagate ST380011A 80GB                | 2         | 2      | 0.82%   |
| Seagate ST3500418AS 500GB             | 2         | 2      | 0.82%   |
| Seagate ST31000524AS 1TB              | 2         | 2      | 0.82%   |
| Seagate ST2000DM001-1CH164 2TB        | 2         | 2      | 0.82%   |
| Samsung Electronics SSD 870 EVO 500GB | 2         | 2      | 0.82%   |
| Samsung Electronics HM500JI 500GB     | 2         | 2      | 0.82%   |
| Samsung Electronics HD753LJ 752GB     | 2         | 2      | 0.82%   |
| Samsung Electronics HD103UJ 1TB       | 2         | 2      | 0.82%   |
| Kingston SUV400S37240G 240GB SSD      | 2         | 2      | 0.82%   |
| Kingston SA400S37120G 120GB SSD       | 2         | 3      | 0.82%   |
| Intel SSDSC2CW120A3 120GB             | 2         | 2      | 0.82%   |
| Intel SSDSA2M080G2GC 80GB             | 2         | 3      | 0.82%   |
| Hitachi HTS725050A7E630 500GB         | 2         | 2      | 0.82%   |
| Hitachi HTS545050A7E380 500GB         | 2         | 3      | 0.82%   |
| Fujitsu MHZ2320BH G2 320GB            | 2         | 2      | 0.82%   |
| Crucial CT525MX300SSD1 528GB          | 2         | 2      | 0.82%   |
| WDC WD800JD-00HKA0 80GB               | 1         | 1      | 0.41%   |
| WDC WD7500BPVT-08HXZT3 752GB          | 1         | 1      | 0.41%   |
| WDC WD6400AACS-00G8B1 640GB           | 1         | 1      | 0.41%   |
| WDC WD60EFRX-68L0BN1 6TB              | 1         | 1      | 0.41%   |
| WDC WD600UE-22HCT0 64GB               | 1         | 1      | 0.41%   |
| WDC WD5000HHTZ-04N21V0 500GB          | 1         | 1      | 0.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 58        | 70     | 24.27%  |
| Seagate                     | 44        | 59     | 18.41%  |
| Samsung Electronics         | 17        | 21     | 7.11%   |
| Kingston                    | 15        | 17     | 6.28%   |
| Hitachi                     | 15        | 16     | 6.28%   |
| Intel                       | 14        | 19     | 5.86%   |
| Toshiba                     | 12        | 13     | 5.02%   |
| Crucial                     | 12        | 20     | 5.02%   |
| HGST                        | 10        | 12     | 4.18%   |
| SanDisk                     | 8         | 8      | 3.35%   |
| SK hynix                    | 6         | 6      | 2.51%   |
| Fujitsu                     | 4         | 4      | 1.67%   |
| Micron Technology           | 3         | 3      | 1.26%   |
| Maxtor                      | 3         | 5      | 1.26%   |
| LITEON                      | 3         | 6      | 1.26%   |
| OCZ                         | 2         | 2      | 0.84%   |
| Corsair                     | 2         | 4      | 0.84%   |
| A-DATA Technology           | 2         | 2      | 0.84%   |
| Realtek                     | 1         | 1      | 0.42%   |
| Patriot                     | 1         | 1      | 0.42%   |
| LITEONIT                    | 1         | 1      | 0.42%   |
| Kingston Technology Company | 1         | 1      | 0.42%   |
| Intenso                     | 1         | 1      | 0.42%   |
| GOODRAM                     | 1         | 1      | 0.42%   |
| C-Series                    | 1         | 1      | 0.42%   |
| Apple                       | 1         | 1      | 0.42%   |
| Anobit                      | 1         | 1      | 0.42%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 56        | 68     | 36.84%  |
| Seagate             | 44        | 59     | 28.95%  |
| Hitachi             | 15        | 16     | 9.87%   |
| Toshiba             | 11        | 12     | 7.24%   |
| HGST                | 10        | 12     | 6.58%   |
| Samsung Electronics | 8         | 8      | 5.26%   |
| Fujitsu             | 4         | 4      | 2.63%   |
| Maxtor              | 3         | 5      | 1.97%   |
| Apple               | 1         | 1      | 0.66%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 142       | 185    | 62.01%  |
| SSD  | 77        | 95     | 33.62%  |
| NVMe | 10        | 16     | 4.37%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-22ZCT0 250GB       | 1         | 1      | 12.5%   |
| Toshiba MK5065GSXN 500GB          | 1         | 1      | 12.5%   |
| Toshiba HDWG180 8TB               | 1         | 4      | 12.5%   |
| Seagate ST2000DL001-9VT156 2TB    | 1         | 1      | 12.5%   |
| Samsung Electronics HD502HJ 500GB | 1         | 1      | 12.5%   |
| Samsung Electronics HD161HJ 160GB | 1         | 1      | 12.5%   |
| Crucial M4-CT256M4SSD3 256GB      | 1         | 1      | 12.5%   |
| Apple HDD HTS541010A9E662 1TB     | 1         | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 5      | 25%     |
| Samsung Electronics | 2         | 2      | 25%     |
| WDC                 | 1         | 1      | 12.5%   |
| Seagate             | 1         | 1      | 12.5%   |
| Crucial             | 1         | 1      | 12.5%   |
| Apple               | 1         | 1      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2464      | 5171   | 59.95%  |
| Works    | 1418      | 2434   | 34.5%   |
| Malfunc  | 220       | 296    | 5.35%   |
| Failed   | 8         | 11     | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2520      | 52.18%  |
| Samsung Electronics              | 612       | 12.67%  |
| AMD                              | 600       | 12.42%  |
| SanDisk                          | 162       | 3.35%   |
| SK hynix                         | 148       | 3.06%   |
| Kingston Technology Company      | 105       | 2.17%   |
| Toshiba America Info Systems     | 84        | 1.74%   |
| ASMedia Technology               | 76        | 1.57%   |
| JMicron Technology               | 60        | 1.24%   |
| Nvidia                           | 57        | 1.18%   |
| Phison Electronics               | 53        | 1.1%    |
| Marvell Technology Group         | 53        | 1.1%    |
| KIOXIA                           | 52        | 1.08%   |
| Micron Technology                | 37        | 0.77%   |
| Micron/Crucial Technology        | 24        | 0.5%    |
| Solid State Storage Technology   | 19        | 0.39%   |
| VIA Technologies                 | 15        | 0.31%   |
| Silicon Motion                   | 15        | 0.31%   |
| Silicon Integrated Systems [SiS] | 15        | 0.31%   |
| ADATA Technology                 | 15        | 0.31%   |
| Apple                            | 13        | 0.27%   |
| Lite-On Technology               | 11        | 0.23%   |
| Broadcom / LSI                   | 11        | 0.23%   |
| Seagate Technology               | 9         | 0.19%   |
| Silicon Image                    | 8         | 0.17%   |
| Realtek Semiconductor            | 8         | 0.17%   |
| LSI Logic / Symbios Logic        | 8         | 0.17%   |
| Union Memory (Shenzhen)          | 7         | 0.14%   |
| O2 Micro                         | 6         | 0.12%   |
| Hewlett-Packard                  | 5         | 0.1%    |
| MAXIO Technology (Hangzhou)      | 3         | 0.06%   |
| Integrated Technology Express    | 3         | 0.06%   |
| Adaptec                          | 3         | 0.06%   |
| ULi Electronics                  | 2         | 0.04%   |
| Transcend                        | 2         | 0.04%   |
| Promise Technology               | 2         | 0.04%   |
| Shenzhen Longsys Electronics     | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| Lenovo                           | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 387       | 6.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 308       | 5.53%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 176       | 3.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 174       | 3.12%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 167       | 3%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 154       | 2.76%   |
| Samsung NVMe SSD Controller 980                                                | 136       | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 109       | 1.96%   |
| AMD 400 Series Chipset SATA Controller                                         | 97        | 1.74%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 89        | 1.6%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 88        | 1.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 74        | 1.33%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 74        | 1.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 73        | 1.31%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 72        | 1.29%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 71        | 1.27%   |
| Intel Volume Management Device NVMe RAID Controller                            | 69        | 1.24%   |
| Intel SATA Controller [RAID mode]                                              | 69        | 1.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 69        | 1.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 67        | 1.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 66        | 1.18%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 64        | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 63        | 1.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 60        | 1.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 58        | 1.04%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 57        | 1.02%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 57        | 1.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 57        | 1.02%   |
| AMD 500 Series Chipset SATA Controller                                         | 56        | 1.01%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 55        | 0.99%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 53        | 0.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 52        | 0.93%   |
| Kingston Company A2000 NVMe SSD                                                | 50        | 0.9%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 50        | 0.9%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 47        | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 47        | 0.84%   |
| Intel SSD 660P Series                                                          | 44        | 0.79%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 44        | 0.79%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 43        | 0.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 43        | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2585      | 52.86%  |
| NVMe | 1385      | 28.32%  |
| IDE  | 559       | 11.43%  |
| RAID | 346       | 7.08%   |
| SAS  | 8         | 0.16%   |
| SCSI | 7         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3033      | 78.55%  |
| AMD          | 776       | 20.1%   |
| ARM          | 49        | 1.27%   |
| CentaurHauls | 2         | 0.05%   |
| QUALCOMM     | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium Silver N6000 @ 1.10GHz          | 58        | 1.5%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 47        | 1.22%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 45        | 1.16%   |
| ARM Processor                                 | 39        | 1.01%   |
| AMD Ryzen 5 3600 6-Core Processor             | 39        | 1.01%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 38        | 0.98%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 36        | 0.93%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 34        | 0.88%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 33        | 0.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 32        | 0.83%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 30        | 0.78%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 29        | 0.75%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 28        | 0.72%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 28        | 0.72%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 27        | 0.7%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 27        | 0.7%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 27        | 0.7%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 24        | 0.62%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 23        | 0.59%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 23        | 0.59%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 23        | 0.59%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 22        | 0.57%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 21        | 0.54%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 21        | 0.54%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 20        | 0.52%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 20        | 0.52%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 20        | 0.52%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 19        | 0.49%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 19        | 0.49%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 19        | 0.49%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 19        | 0.49%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 19        | 0.49%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 18        | 0.47%   |
| AMD Custom APU 0405                           | 18        | 0.47%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 17        | 0.44%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 17        | 0.44%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 17        | 0.44%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 16        | 0.41%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 16        | 0.41%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 16        | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 840       | 21.73%  |
| Intel Core i7           | 774       | 20.02%  |
| Intel Core i3           | 291       | 7.53%   |
| Other                   | 268       | 6.93%   |
| AMD Ryzen 5             | 187       | 4.84%   |
| AMD Ryzen 7             | 180       | 4.66%   |
| Intel Core 2 Duo        | 168       | 4.35%   |
| Intel Celeron           | 133       | 3.44%   |
| Intel Pentium Silver    | 106       | 2.74%   |
| Intel Atom              | 92        | 2.38%   |
| Intel Pentium           | 87        | 2.25%   |
| Intel Xeon              | 80        | 2.07%   |
| Intel Pentium Dual-Core | 54        | 1.4%    |
| AMD Ryzen 9             | 53        | 1.37%   |
| Intel Core 2 Quad       | 45        | 1.16%   |
| AMD FX                  | 35        | 0.91%   |
| Intel Core i9           | 32        | 0.83%   |
| Intel Core 2            | 29        | 0.75%   |
| Intel Pentium Dual      | 26        | 0.67%   |
| AMD A6                  | 26        | 0.67%   |
| AMD Ryzen 7 PRO         | 24        | 0.62%   |
| Intel Genuine           | 22        | 0.57%   |
| AMD A8                  | 22        | 0.57%   |
| AMD Ryzen 5 PRO         | 19        | 0.49%   |
| AMD Athlon 64 X2        | 19        | 0.49%   |
| AMD Ryzen 3             | 18        | 0.47%   |
| AMD Phenom II X4        | 17        | 0.44%   |
| AMD A4                  | 16        | 0.41%   |
| AMD A10                 | 15        | 0.39%   |
| Intel Pentium 4         | 14        | 0.36%   |
| Intel Pentium D         | 13        | 0.34%   |
| AMD E                   | 13        | 0.34%   |
| AMD Athlon II X2        | 13        | 0.34%   |
| AMD E1                  | 10        | 0.26%   |
| ARM BCM                 | 9         | 0.23%   |
| AMD Athlon II X4        | 8         | 0.21%   |
| AMD Athlon              | 8         | 0.21%   |
| AMD Ryzen Threadripper  | 7         | 0.18%   |
| Intel Core m3           | 6         | 0.16%   |
| AMD E2                  | 6         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1533      | 39.63%  |
| 2       | 1426      | 36.87%  |
| 6       | 376       | 9.72%   |
| 8       | 278       | 7.19%   |
| 1       | 90        | 2.33%   |
| 12      | 62        | 1.6%    |
| 10      | 34        | 0.88%   |
| 16      | 22        | 0.57%   |
| 14      | 18        | 0.47%   |
| 3       | 10        | 0.26%   |
| 24      | 8         | 0.21%   |
| Unknown | 7         | 0.18%   |
| 64      | 1         | 0.03%   |
| 48      | 1         | 0.03%   |
| 32      | 1         | 0.03%   |
| 5       | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3826      | 99.09%  |
| 2       | 28        | 0.73%   |
| Unknown | 5         | 0.13%   |
| 4       | 1         | 0.03%   |
| 3       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2487      | 64.35%  |
| 1       | 1368      | 35.39%  |
| Unknown | 7         | 0.18%   |
| 16      | 1         | 0.03%   |
| 8       | 1         | 0.03%   |
| 4       | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3747      | 96.8%   |
| Unknown        | 91        | 2.35%   |
| 32-bit         | 30        | 0.77%   |
| 64-bit         | 3         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1016      | 25.4%   |
| 0x306a9    | 209       | 5.23%   |
| 0x206a7    | 197       | 4.93%   |
| 0x306c3    | 165       | 4.13%   |
| 0x1067a    | 140       | 3.5%    |
| 0x806ec    | 124       | 3.1%    |
| 0x906ea    | 111       | 2.78%   |
| 0x806c1    | 78        | 1.95%   |
| 0x806ea    | 76        | 1.9%    |
| 0x406e3    | 76        | 1.9%    |
| 0x506e3    | 73        | 1.83%   |
| 0x40651    | 71        | 1.78%   |
| 0x20655    | 67        | 1.68%   |
| 0x806e9    | 66        | 1.65%   |
| 0x906e9    | 61        | 1.53%   |
| 0x906c0    | 59        | 1.48%   |
| 0x6fd      | 59        | 1.48%   |
| 0x08701021 | 54        | 1.35%   |
| 0x306d4    | 47        | 1.18%   |
| 0x08600106 | 42        | 1.05%   |
| 0x30678    | 41        | 1.03%   |
| 0x706a8    | 40        | 1%      |
| 0x0a50000c | 40        | 1%      |
| 0x6fb      | 35        | 0.88%   |
| 0x08701013 | 33        | 0.83%   |
| 0x010000c8 | 33        | 0.83%   |
| 0x806eb    | 31        | 0.78%   |
| 0xa0652    | 28        | 0.7%    |
| 0x10676    | 28        | 0.7%    |
| 0x906ed    | 26        | 0.65%   |
| 0x706e5    | 26        | 0.65%   |
| 0x20652    | 26        | 0.65%   |
| 0x0800820d | 26        | 0.65%   |
| 0x406c4    | 25        | 0.63%   |
| 0x706a1    | 24        | 0.6%    |
| 0x106e5    | 24        | 0.6%    |
| 0x08108109 | 24        | 0.6%    |
| 0x08108102 | 23        | 0.58%   |
| 0x06001119 | 23        | 0.58%   |
| 0x506c9    | 22        | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 674       | 17.43%  |
| Haswell          | 333       | 8.61%   |
| IvyBridge        | 274       | 7.09%   |
| SandyBridge      | 258       | 6.67%   |
| Skylake          | 209       | 5.4%    |
| Penryn           | 206       | 5.33%   |
| Zen 2            | 189       | 4.89%   |
| Unknown          | 153       | 3.96%   |
| Core             | 152       | 3.93%   |
| Westmere         | 133       | 3.44%   |
| Silvermont       | 129       | 3.34%   |
| Zen 3            | 115       | 2.97%   |
| TigerLake        | 104       | 2.69%   |
| Zen+             | 98        | 2.53%   |
| Broadwell        | 78        | 2.02%   |
| Goldmont plus    | 68        | 1.76%   |
| CometLake        | 68        | 1.76%   |
| Piledriver       | 57        | 1.47%   |
| K10              | 57        | 1.47%   |
| Nehalem          | 56        | 1.45%   |
| Zen              | 53        | 1.37%   |
| Tremont          | 52        | 1.34%   |
| Alderlake Hybrid | 52        | 1.34%   |
| IceLake          | 48        | 1.24%   |
| K8 Hammer        | 35        | 0.91%   |
| Goldmont         | 32        | 0.83%   |
| NetBurst         | 31        | 0.8%    |
| Excavator        | 23        | 0.59%   |
| Bonnell          | 21        | 0.54%   |
| Bobcat           | 21        | 0.54%   |
| K10 Llano        | 17        | 0.44%   |
| P6               | 16        | 0.41%   |
| Jaguar           | 16        | 0.41%   |
| Steamroller      | 12        | 0.31%   |
| Puma             | 10        | 0.26%   |
| K8 & K10 hybrid  | 9         | 0.23%   |
| Bulldozer        | 7         | 0.18%   |
| CannonLake       | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2285      | 50.89%  |
| Nvidia                           | 1243      | 27.68%  |
| AMD                              | 921       | 20.51%  |
| Matrox Electronics Systems       | 15        | 0.33%   |
| ASPEED Technology                | 10        | 0.22%   |
| Silicon Integrated Systems [SiS] | 8         | 0.18%   |
| VIA Technologies                 | 7         | 0.16%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 189       | 4.1%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 161       | 3.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 121       | 2.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 112       | 2.43%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 96        | 2.08%   |
| Intel UHD Graphics 620                                                                   | 87        | 1.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 80        | 1.74%   |
| AMD Renoir                                                                               | 78        | 1.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 76        | 1.65%   |
| Intel HD Graphics 620                                                                    | 73        | 1.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 71        | 1.54%   |
| Intel Core Processor Integrated Graphics Controller                                      | 71        | 1.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 66        | 1.43%   |
| Intel JasperLake [UHD Graphics]                                                          | 63        | 1.37%   |
| Intel HD Graphics 630                                                                    | 63        | 1.37%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 63        | 1.37%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 62        | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 61        | 1.32%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 61        | 1.32%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 59        | 1.28%   |
| Intel HD Graphics 530                                                                    | 58        | 1.26%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 55        | 1.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 51        | 1.11%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 48        | 1.04%   |
| Intel HD Graphics 5500                                                                   | 45        | 0.98%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 44        | 0.96%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 41        | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 35        | 0.76%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 35        | 0.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 34        | 0.74%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 32        | 0.69%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 31        | 0.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 30        | 0.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 30        | 0.65%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 30        | 0.65%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 30        | 0.65%   |
| Nvidia GT218 [GeForce 210]                                                               | 29        | 0.63%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 25        | 0.54%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 23        | 0.5%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 22        | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1675      | 43.05%  |
| 1 x AMD                  | 755       | 19.4%   |
| 1 x Nvidia               | 700       | 17.99%  |
| Intel + Nvidia           | 482       | 12.39%  |
| Intel + AMD              | 73        | 1.88%   |
| Other                    | 56        | 1.44%   |
| AMD + Nvidia             | 47        | 1.21%   |
| 2 x AMD                  | 44        | 1.13%   |
| 1 x Matrox               | 12        | 0.31%   |
| 2 x Nvidia               | 10        | 0.26%   |
| 1 x SiS                  | 8         | 0.21%   |
| 2 x Intel                | 7         | 0.18%   |
| 1 x VIA                  | 7         | 0.18%   |
| 1 x ASPEED               | 5         | 0.13%   |
| Nvidia + ASPEED          | 4         | 0.1%    |
| Nvidia + Matrox          | 2         | 0.05%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.05%   |
| AMD + Matrox             | 1         | 0.03%   |
| AMD + ASPEED             | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3083      | 78.49%  |
| Proprietary | 662       | 16.85%  |
| Unknown     | 183       | 4.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2323      | 58.47%  |
| 1.01-2.0   | 419       | 10.55%  |
| 0.01-0.5   | 386       | 9.72%   |
| 0.51-1.0   | 284       | 7.15%   |
| 3.01-4.0   | 254       | 6.39%   |
| 7.01-8.0   | 165       | 4.15%   |
| 5.01-6.0   | 81        | 2.04%   |
| 8.01-16.0  | 34        | 0.86%   |
| 2.01-3.0   | 25        | 0.63%   |
| 16.01-24.0 | 2         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 555       | 13.1%   |
| Samsung Electronics     | 529       | 12.49%  |
| LG Display              | 353       | 8.33%   |
| BOE                     | 332       | 7.84%   |
| Chimei Innolux          | 280       | 6.61%   |
| Dell                    | 237       | 5.59%   |
| Philips                 | 187       | 4.41%   |
| Iiyama                  | 186       | 4.39%   |
| Goldstar                | 182       | 4.3%    |
| Hewlett-Packard         | 144       | 3.4%    |
| Acer                    | 132       | 3.12%   |
| Apple                   | 107       | 2.53%   |
| Sharp                   | 97        | 2.29%   |
| AOC                     | 91        | 2.15%   |
| BenQ                    | 82        | 1.94%   |
| Chi Mei Optoelectronics | 60        | 1.42%   |
| Ancor Communications    | 54        | 1.27%   |
| Lenovo                  | 51        | 1.2%    |
| LG Philips              | 34        | 0.8%    |
| Sony                    | 33        | 0.78%   |
| Medion                  | 31        | 0.73%   |
| Idek Iiyama             | 29        | 0.68%   |
| InfoVision              | 26        | 0.61%   |
| LG Electronics          | 22        | 0.52%   |
| Eizo                    | 19        | 0.45%   |
| CSO                     | 19        | 0.45%   |
| MSI                     | 18        | 0.42%   |
| ASUSTek Computer        | 18        | 0.42%   |
| PANDA                   | 17        | 0.4%    |
| Unknown                 | 15        | 0.35%   |
| Valve                   | 14        | 0.33%   |
| Panasonic               | 14        | 0.33%   |
| ViewSonic               | 12        | 0.28%   |
| Fujitsu Siemens         | 12        | 0.28%   |
| Packard Bell            | 11        | 0.26%   |
| NEC Computers           | 11        | 0.26%   |
| Gigabyte Technology     | 11        | 0.26%   |
| Vestel Elektronik       | 10        | 0.24%   |
| HannStar                | 10        | 0.24%   |
| Toshiba                 | 9         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE093D 1366x768 256x144mm 11.6-inch                      | 33        | 0.75%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 26        | 0.59%   |
| AU Optronics LCD Monitor AUO202D 1920x1080 293x165mm 13.2-inch            | 23        | 0.52%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch      | 18        | 0.41%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch             | 18        | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 17        | 0.39%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 16        | 0.36%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 16        | 0.36%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch       | 15        | 0.34%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 14        | 0.32%   |
| BOE LCD Monitor BOE0744 1366x768 256x144mm 11.6-inch                      | 13        | 0.3%    |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 13        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 12        | 0.27%   |
| AU Optronics LCD Monitor AUO7E91 1366x768 256x144mm 11.6-inch             | 12        | 0.27%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 11        | 0.25%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch              | 11        | 0.25%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 11        | 0.25%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch      | 10        | 0.23%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch      | 10        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 10        | 0.23%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 9         | 0.2%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 9         | 0.2%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 9         | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 9         | 0.2%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 9         | 0.2%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                   | 8         | 0.18%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                   | 8         | 0.18%   |
| LGD LCD Monitor 1920x1080                                                 | 8         | 0.18%   |
| Iiyama PL2492H IVM612F 1920x1080 530x300mm 24.0-inch                      | 8         | 0.18%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                   | 8         | 0.18%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 8         | 0.18%   |
| BOE LCD Monitor BOE097B 1366x768 256x144mm 11.6-inch                      | 8         | 0.18%   |
| BOE LCD Monitor BOE07B9 1920x1080 293x165mm 13.2-inch                     | 8         | 0.18%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 7         | 0.16%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch                   | 7         | 0.16%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch               | 7         | 0.16%   |
| Iiyama PLT1931 IVM483F 1280x1024 376x301mm 19.0-inch                      | 7         | 0.16%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 7         | 0.16%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                   | 7         | 0.16%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch          | 7         | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1713      | 41.88%  |
| 1366x768 (WXGA)    | 572       | 13.99%  |
| 3840x2160 (4K)     | 266       | 6.5%    |
| 2560x1440 (QHD)    | 245       | 5.99%   |
| 1600x900 (HD+)     | 176       | 4.3%    |
| 1280x1024 (SXGA)   | 146       | 3.57%   |
| 1680x1050 (WSXGA+) | 144       | 3.52%   |
| 1280x800 (WXGA)    | 113       | 2.76%   |
| 1920x1200 (WUXGA)  | 111       | 2.71%   |
| 1440x900 (WXGA+)   | 100       | 2.44%   |
| 3440x1440          | 66        | 1.61%   |
| Unknown            | 56        | 1.37%   |
| 2560x1600          | 43        | 1.05%   |
| 2560x1080          | 43        | 1.05%   |
| 3840x2400          | 30        | 0.73%   |
| 1360x768           | 30        | 0.73%   |
| 2880x1800          | 29        | 0.71%   |
| 3840x1080          | 19        | 0.46%   |
| 1024x768 (XGA)     | 18        | 0.44%   |
| 800x1280           | 14        | 0.34%   |
| 1920x540           | 13        | 0.32%   |
| 2736x1824          | 9         | 0.22%   |
| 1280x720 (HD)      | 9         | 0.22%   |
| 1600x1200          | 8         | 0.2%    |
| 2160x1440          | 7         | 0.17%   |
| 3840x1600          | 6         | 0.15%   |
| 3456x2160          | 6         | 0.15%   |
| 3200x1800 (QHD+)   | 6         | 0.15%   |
| 3840x1200          | 5         | 0.12%   |
| 3600x1080          | 5         | 0.12%   |
| 3000x2000          | 5         | 0.12%   |
| 2048x1152          | 5         | 0.12%   |
| 1400x1050          | 5         | 0.12%   |
| 1024x600           | 5         | 0.12%   |
| 7680x2160          | 4         | 0.1%    |
| 5760x1080          | 4         | 0.1%    |
| 2256x1504          | 4         | 0.1%    |
| 1280x960           | 4         | 0.1%    |
| 3072x1920          | 3         | 0.07%   |
| 1680x945           | 3         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 930       | 21.95%  |
| 13      | 367       | 8.66%   |
| 17      | 338       | 7.98%   |
| 24      | 309       | 7.29%   |
| 27      | 298       | 7.03%   |
| 23      | 259       | 6.11%   |
| 14      | 256       | 6.04%   |
| Unknown | 240       | 5.66%   |
| 21      | 199       | 4.7%    |
| 11      | 147       | 3.47%   |
| 19      | 110       | 2.6%    |
| 12      | 94        | 2.22%   |
| 22      | 92        | 2.17%   |
| 34      | 86        | 2.03%   |
| 31      | 73        | 1.72%   |
| 20      | 55        | 1.3%    |
| 18      | 44        | 1.04%   |
| 84      | 33        | 0.78%   |
| 25      | 33        | 0.78%   |
| 16      | 33        | 0.78%   |
| 72      | 26        | 0.61%   |
| 40      | 24        | 0.57%   |
| 10      | 16        | 0.38%   |
| 65      | 15        | 0.35%   |
| 54      | 15        | 0.35%   |
| 28      | 11        | 0.26%   |
| 26      | 11        | 0.26%   |
| 7       | 11        | 0.26%   |
| 33      | 10        | 0.24%   |
| 32      | 10        | 0.24%   |
| 29      | 9         | 0.21%   |
| 37      | 8         | 0.19%   |
| 35      | 7         | 0.17%   |
| 46      | 6         | 0.14%   |
| 36      | 6         | 0.14%   |
| 58      | 5         | 0.12%   |
| 52      | 5         | 0.12%   |
| 42      | 5         | 0.12%   |
| 57      | 4         | 0.09%   |
| 47      | 4         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1375      | 33.04%  |
| 501-600        | 826       | 19.85%  |
| 201-300        | 500       | 12.02%  |
| 401-500        | 415       | 9.97%   |
| 351-400        | 377       | 9.06%   |
| Unknown        | 240       | 5.77%   |
| 601-700        | 120       | 2.88%   |
| 701-800        | 108       | 2.6%    |
| 1001-1500      | 64        | 1.54%   |
| 1501-2000      | 61        | 1.47%   |
| 801-900        | 46        | 1.11%   |
| 1-100          | 14        | 0.34%   |
| 901-1000       | 12        | 0.29%   |
| 101-200        | 2         | 0.05%   |
| More than 2000 | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2708      | 70.45%  |
| 16/10   | 572       | 14.88%  |
| Unknown | 199       | 5.18%   |
| 5/4     | 138       | 3.59%   |
| 21/9    | 107       | 2.78%   |
| 3/2     | 44        | 1.14%   |
| 4/3     | 41        | 1.07%   |
| 6/5     | 11        | 0.29%   |
| 0.67    | 11        | 0.29%   |
| 32/9    | 6         | 0.16%   |
| 3.40    | 1         | 0.03%   |
| 3.33    | 1         | 0.03%   |
| 1.00    | 1         | 0.03%   |
| 0.80    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |
| 0.45    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 916       | 21.79%  |
| 201-250        | 673       | 16.01%  |
| 81-90          | 424       | 10.09%  |
| 301-350        | 308       | 7.33%   |
| Unknown        | 240       | 5.71%   |
| 151-200        | 232       | 5.52%   |
| 121-130        | 219       | 5.21%   |
| 71-80          | 207       | 4.92%   |
| 351-500        | 206       | 4.9%    |
| 51-60          | 149       | 3.54%   |
| 251-300        | 143       | 3.4%    |
| More than 1000 | 113       | 2.69%   |
| 141-150        | 100       | 2.38%   |
| 61-70          | 81        | 1.93%   |
| 501-1000       | 65        | 1.55%   |
| 131-140        | 48        | 1.14%   |
| 111-120        | 43        | 1.02%   |
| 1-40           | 16        | 0.38%   |
| 41-50          | 15        | 0.36%   |
| 91-100         | 6         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1291      | 31.49%  |
| 121-160       | 1153      | 28.12%  |
| 101-120       | 886       | 21.61%  |
| 161-240       | 278       | 6.78%   |
| Unknown       | 240       | 5.85%   |
| More than 240 | 154       | 3.76%   |
| 1-50          | 98        | 2.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3051      | 77.08%  |
| 2     | 642       | 16.22%  |
| 0     | 191       | 4.83%   |
| 3     | 68        | 1.72%   |
| 4     | 5         | 0.13%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2053      | 36.22%  |
| Realtek Semiconductor                 | 1855      | 32.73%  |
| Qualcomm Atheros                      | 540       | 9.53%   |
| Broadcom                              | 355       | 6.26%   |
| Broadcom Limited                      | 84        | 1.48%   |
| Marvell Technology Group              | 74        | 1.31%   |
| TP-Link                               | 73        | 1.29%   |
| Ralink Technology                     | 68        | 1.2%    |
| Ralink                                | 58        | 1.02%   |
| MediaTek                              | 54        | 0.95%   |
| Nvidia                                | 45        | 0.79%   |
| ASIX Electronics                      | 36        | 0.64%   |
| DisplayLink                           | 30        | 0.53%   |
| Dell                                  | 30        | 0.53%   |
| Hewlett-Packard                       | 24        | 0.42%   |
| Microsoft                             | 16        | 0.28%   |
| Sitecom Europe                        | 15        | 0.26%   |
| Huawei Technologies                   | 13        | 0.23%   |
| Silicon Integrated Systems [SiS]      | 12        | 0.21%   |
| Samsung Electronics                   | 12        | 0.21%   |
| NetGear                               | 12        | 0.21%   |
| JMicron Technology                    | 12        | 0.21%   |
| Ericsson Business Mobile Networks     | 12        | 0.21%   |
| Sierra Wireless                       | 11        | 0.19%   |
| IMC Networks                          | 11        | 0.19%   |
| ASUSTek Computer                      | 11        | 0.19%   |
| Lenovo                                | 10        | 0.18%   |
| Qualcomm                              | 9         | 0.16%   |
| Aquantia                              | 8         | 0.14%   |
| VIA Technologies                      | 6         | 0.11%   |
| Gemtek                                | 6         | 0.11%   |
| D-Link                                | 6         | 0.11%   |
| Xiaomi                                | 5         | 0.09%   |
| Mellanox Technologies                 | 5         | 0.09%   |
| Edimax Technology                     | 5         | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 5         | 0.09%   |
| U-Blox                                | 4         | 0.07%   |
| Microchip Technology                  | 4         | 0.07%   |
| Linksys                               | 4         | 0.07%   |
| Fibocom                               | 4         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1329      | 20.04%  |
| Intel Wi-Fi 6 AX200                                               | 203       | 3.06%   |
| Intel Wireless 8265 / 8275                                        | 161       | 2.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 157       | 2.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 156       | 2.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 140       | 2.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 117       | 1.76%   |
| Intel Wireless 7265                                               | 95        | 1.43%   |
| Intel I211 Gigabit Network Connection                             | 92        | 1.39%   |
| Intel Wi-Fi 6 AX201                                               | 81        | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 75        | 1.13%   |
| Intel Wireless 7260                                               | 71        | 1.07%   |
| Realtek RTL8125 2.5GbE Controller                                 | 70        | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 64        | 0.97%   |
| Intel Ethernet Connection (2) I219-V                              | 63        | 0.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 61        | 0.92%   |
| Intel Wireless 8260                                               | 61        | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 59        | 0.89%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 59        | 0.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 56        | 0.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 54        | 0.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 49        | 0.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 46        | 0.69%   |
| Intel Wireless 3165                                               | 46        | 0.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 46        | 0.69%   |
| Intel Wireless-AC 9260                                            | 45        | 0.68%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 45        | 0.68%   |
| Intel 82579V Gigabit Network Connection                           | 44        | 0.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 43        | 0.65%   |
| Intel Ethernet Connection I217-LM                                 | 43        | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 42        | 0.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 38        | 0.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 37        | 0.56%   |
| Intel Ethernet Connection (6) I219-V                              | 36        | 0.54%   |
| Intel Centrino Ultimate-N 6300                                    | 36        | 0.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 35        | 0.53%   |
| Intel 82577LM Gigabit Network Connection                          | 34        | 0.51%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 33        | 0.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 33        | 0.5%    |
| Intel Wireless 3160                                               | 32        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1577      | 52.18%  |
| Qualcomm Atheros                      | 427       | 14.13%  |
| Realtek Semiconductor                 | 353       | 11.68%  |
| Broadcom                              | 222       | 7.35%   |
| Ralink Technology                     | 68        | 2.25%   |
| TP-Link                               | 64        | 2.12%   |
| Ralink                                | 58        | 1.92%   |
| MediaTek                              | 52        | 1.72%   |
| Broadcom Limited                      | 43        | 1.42%   |
| Sitecom Europe                        | 15        | 0.5%    |
| Microsoft                             | 14        | 0.46%   |
| Marvell Technology Group              | 13        | 0.43%   |
| NetGear                               | 12        | 0.4%    |
| Dell                                  | 12        | 0.4%    |
| Sierra Wireless                       | 11        | 0.36%   |
| IMC Networks                          | 11        | 0.36%   |
| ASUSTek Computer                      | 11        | 0.36%   |
| Qualcomm                              | 6         | 0.2%    |
| Gemtek                                | 6         | 0.2%    |
| D-Link                                | 6         | 0.2%    |
| Edimax Technology                     | 5         | 0.17%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 5         | 0.17%   |
| Linksys                               | 4         | 0.13%   |
| Hewlett-Packard                       | 4         | 0.13%   |
| Fibocom                               | 4         | 0.13%   |
| Belkin Components                     | 4         | 0.13%   |
| Qualcomm Atheros Communications       | 3         | 0.1%    |
| Senao                                 | 2         | 0.07%   |
| Sagem                                 | 2         | 0.07%   |
| CyberTAN Technology                   | 2         | 0.07%   |
| Wilocity                              | 1         | 0.03%   |
| Silicon Integrated Systems [SiS]      | 1         | 0.03%   |
| Samsung Electronics                   | 1         | 0.03%   |
| Realtek                               | 1         | 0.03%   |
| Cinterion                             | 1         | 0.03%   |
| BUFFALO                               | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 203       | 6.69%   |
| Intel Wireless 8265 / 8275                                              | 161       | 5.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 117       | 3.86%   |
| Intel Wireless 7265                                                     | 95        | 3.13%   |
| Intel Wi-Fi 6 AX201                                                     | 81        | 2.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 75        | 2.47%   |
| Intel Wireless 7260                                                     | 71        | 2.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 64        | 2.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 61        | 2.01%   |
| Intel Wireless 8260                                                     | 61        | 2.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 59        | 1.94%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 59        | 1.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 56        | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 54        | 1.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 49        | 1.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 46        | 1.52%   |
| Intel Wireless 3165                                                     | 46        | 1.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 46        | 1.52%   |
| Intel Wireless-AC 9260                                                  | 45        | 1.48%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 45        | 1.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 43        | 1.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 42        | 1.38%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 38        | 1.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 37        | 1.22%   |
| Intel Centrino Ultimate-N 6300                                          | 36        | 1.19%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 35        | 1.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 33        | 1.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 33        | 1.09%   |
| Intel Wireless 3160                                                     | 32        | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 32        | 1.05%   |
| Intel Centrino Advanced-N 6200                                          | 31        | 1.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 29        | 0.96%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 29        | 0.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 25        | 0.82%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 24        | 0.79%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 23        | 0.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 22        | 0.72%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 22        | 0.72%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 21        | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                           | 21        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1711      | 50.09%  |
| Intel                                  | 1002      | 29.33%  |
| Broadcom                               | 189       | 5.53%   |
| Qualcomm Atheros                       | 176       | 5.15%   |
| Marvell Technology Group               | 61        | 1.79%   |
| Nvidia                                 | 44        | 1.29%   |
| Broadcom Limited                       | 41        | 1.2%    |
| ASIX Electronics                       | 36        | 1.05%   |
| DisplayLink                            | 30        | 0.88%   |
| JMicron Technology                     | 12        | 0.35%   |
| Silicon Integrated Systems [SiS]       | 11        | 0.32%   |
| Lenovo                                 | 10        | 0.29%   |
| TP-Link                                | 9         | 0.26%   |
| Huawei Technologies                    | 9         | 0.26%   |
| Samsung Electronics                    | 8         | 0.23%   |
| Aquantia                               | 8         | 0.23%   |
| VIA Technologies                       | 6         | 0.18%   |
| Hewlett-Packard                        | 6         | 0.18%   |
| Xiaomi                                 | 5         | 0.15%   |
| Mellanox Technologies                  | 4         | 0.12%   |
| Standard Microsystems                  | 3         | 0.09%   |
| Qualcomm                               | 3         | 0.09%   |
| 3Com                                   | 3         | 0.09%   |
| ULi Electronics                        | 2         | 0.06%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.06%   |
| Motorola PCS                           | 2         | 0.06%   |
| MosChip Semiconductor                  | 2         | 0.06%   |
| Microsoft                              | 2         | 0.06%   |
| Microchip Technology                   | 2         | 0.06%   |
| ICS Advent                             | 2         | 0.06%   |
| Apple                                  | 2         | 0.06%   |
| Accton Technology                      | 2         | 0.06%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.03%   |
| Spreadtrum Communications              | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| QLogic                                 | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.03%   |
| MediaTek                               | 1         | 0.03%   |
| Jolla Oy                               | 1         | 0.03%   |
| Google                                 | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1329      | 37.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 157       | 4.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 156       | 4.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 140       | 3.99%   |
| Intel I211 Gigabit Network Connection                             | 92        | 2.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 70        | 1.99%   |
| Intel Ethernet Connection (2) I219-V                              | 63        | 1.8%    |
| Intel 82579V Gigabit Network Connection                           | 44        | 1.25%   |
| Intel Ethernet Connection I217-LM                                 | 43        | 1.23%   |
| Intel Ethernet Connection (6) I219-V                              | 36        | 1.03%   |
| Intel 82577LM Gigabit Network Connection                          | 34        | 0.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 31        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 31        | 0.88%   |
| Intel Ethernet Controller I225-V                                  | 31        | 0.88%   |
| Intel Ethernet Connection I219-LM                                 | 31        | 0.88%   |
| Intel Ethernet Connection I217-V                                  | 31        | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                     | 31        | 0.88%   |
| Intel Ethernet Connection (4) I219-LM                             | 29        | 0.83%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 28        | 0.8%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 27        | 0.77%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 26        | 0.74%   |
| Intel Ethernet Connection I218-LM                                 | 25        | 0.71%   |
| Intel Ethernet Connection (7) I219-V                              | 24        | 0.68%   |
| Intel Ethernet Connection (4) I219-V                              | 24        | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 23        | 0.66%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 23        | 0.66%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 20        | 0.57%   |
| Nvidia MCP79 Ethernet                                             | 18        | 0.51%   |
| Intel Ethernet Connection (3) I218-LM                             | 18        | 0.51%   |
| Intel I210 Gigabit Network Connection                             | 17        | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                             | 17        | 0.48%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 16        | 0.46%   |
| Intel Ethernet Connection (6) I219-LM                             | 16        | 0.46%   |
| Intel 82574L Gigabit Network Connection                           | 16        | 0.46%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 15        | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 15        | 0.43%   |
| Intel Ethernet Connection (2) I218-V                              | 15        | 0.43%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 14        | 0.4%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 14        | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 13        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3222      | 52.21%  |
| WiFi     | 2864      | 46.41%  |
| Modem    | 76        | 1.23%   |
| Unknown  | 9         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2182      | 53.94%  |
| Ethernet | 1862      | 46.03%  |
| Unknown  | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2006      | 51.79%  |
| 1     | 1659      | 42.84%  |
| 0     | 105       | 2.71%   |
| 3     | 74        | 1.91%   |
| 4     | 18        | 0.46%   |
| 5     | 4         | 0.1%    |
| 7     | 3         | 0.08%   |
| 6     | 3         | 0.08%   |
| 8     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3129      | 79.14%  |
| Yes  | 825       | 20.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1263      | 53.36%  |
| Cambridge Silicon Radio         | 189       | 7.98%   |
| Realtek Semiconductor           | 158       | 6.68%   |
| Qualcomm Atheros Communications | 124       | 5.24%   |
| Apple                           | 107       | 4.52%   |
| Broadcom                        | 102       | 4.31%   |
| IMC Networks                    | 83        | 3.51%   |
| Lite-On Technology              | 65        | 2.75%   |
| Foxconn / Hon Hai               | 64        | 2.7%    |
| Hewlett-Packard                 | 43        | 1.82%   |
| ASUSTek Computer                | 43        | 1.82%   |
| Dell                            | 37        | 1.56%   |
| Toshiba                         | 19        | 0.8%    |
| MediaTek                        | 13        | 0.55%   |
| Marvell Semiconductor           | 13        | 0.55%   |
| Ralink                          | 10        | 0.42%   |
| TP-Link                         | 6         | 0.25%   |
| Realtek                         | 5         | 0.21%   |
| Alps Electric                   | 4         | 0.17%   |
| Ralink Technology               | 3         | 0.13%   |
| Integrated System Solution      | 3         | 0.13%   |
| USI                             | 2         | 0.08%   |
| Sitecom Europe                  | 2         | 0.08%   |
| Micro Star International        | 2         | 0.08%   |
| Foxconn International           | 2         | 0.08%   |
| Roper                           | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| Actions                         | 1         | 0.04%   |
| Unknown                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 443       | 18.7%   |
| Intel AX201 Bluetooth                               | 233       | 9.84%   |
| Intel AX200 Bluetooth                               | 195       | 8.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 189       | 7.98%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 188       | 7.94%   |
| Realtek Bluetooth Radio                             | 96        | 4.05%   |
| Intel Bluetooth Device                              | 45        | 1.9%    |
| Realtek  Bluetooth 4.2 Adapter                      | 44        | 1.86%   |
| Qualcomm Atheros  Bluetooth Device                  | 43        | 1.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 43        | 1.82%   |
| Apple Bluetooth Host Controller                     | 43        | 1.82%   |
| Intel Wireless-AC 3168 Bluetooth                    | 42        | 1.77%   |
| IMC Networks Bluetooth Radio                        | 34        | 1.44%   |
| Apple Bluetooth USB Host Controller                 | 32        | 1.35%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 31        | 1.31%   |
| Intel AX210 Bluetooth                               | 30        | 1.27%   |
| Lite-On Bluetooth Device                            | 29        | 1.22%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 27        | 1.14%   |
| Foxconn / Hon Hai Bluetooth Device                  | 25        | 1.06%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 23        | 0.97%   |
| HP Broadcom 2070 Bluetooth Combo                    | 22        | 0.93%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 21        | 0.89%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 21        | 0.89%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 20        | 0.84%   |
| Dell DW375 Bluetooth Module                         | 19        | 0.8%    |
| IMC Networks Bluetooth Device                       | 18        | 0.76%   |
| Broadcom BCM2045B (BDC-2.1)                         | 17        | 0.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 16        | 0.68%   |
| Broadcom HP Portable SoftSailing                    | 16        | 0.68%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 15        | 0.63%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 15        | 0.63%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 14        | 0.59%   |
| IMC Networks Wireless_Device                        | 14        | 0.59%   |
| Broadcom BCM2045 Bluetooth                          | 13        | 0.55%   |
| MediaTek Wireless_Device                            | 12        | 0.51%   |
| Dell BCM20702A0 Bluetooth Module                    | 12        | 0.51%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 12        | 0.51%   |
| Marvell Bluetooth and Wireless LAN Composite        | 11        | 0.46%   |
| Apple Bluetooth HCI                                 | 11        | 0.46%   |
| Ralink RT3290 Bluetooth                             | 10        | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2840      | 53.51%  |
| AMD                              | 989       | 18.64%  |
| Nvidia                           | 887       | 16.71%  |
| C-Media Electronics              | 79        | 1.49%   |
| Logitech                         | 44        | 0.83%   |
| Realtek Semiconductor            | 39        | 0.73%   |
| Creative Labs                    | 32        | 0.6%    |
| GN Netcom                        | 31        | 0.58%   |
| Texas Instruments                | 25        | 0.47%   |
| Focusrite-Novation               | 17        | 0.32%   |
| Creative Technology              | 15        | 0.28%   |
| Silicon Integrated Systems [SiS] | 14        | 0.26%   |
| Hewlett-Packard                  | 14        | 0.26%   |
| Plantronics                      | 12        | 0.23%   |
| Kingston Technology              | 12        | 0.23%   |
| BEHRINGER International          | 12        | 0.23%   |
| VIA Technologies                 | 11        | 0.21%   |
| SteelSeries ApS                  | 11        | 0.21%   |
| JMTek                            | 11        | 0.21%   |
| Corsair                          | 10        | 0.19%   |
| Apple                            | 9         | 0.17%   |
| Generalplus Technology           | 8         | 0.15%   |
| ASUSTek Computer                 | 8         | 0.15%   |
| Sony                             | 7         | 0.13%   |
| Sennheiser Communications        | 7         | 0.13%   |
| GYROCOM C&C                      | 7         | 0.13%   |
| RODE Microphones                 | 6         | 0.11%   |
| Razer USA                        | 6         | 0.11%   |
| Lenovo                           | 6         | 0.11%   |
| Yamaha                           | 5         | 0.09%   |
| Cambridge Silicon Radio          | 5         | 0.09%   |
| XMOS                             | 4         | 0.08%   |
| SAVITECH                         | 4         | 0.08%   |
| Samson Technologies              | 4         | 0.08%   |
| Native Instruments               | 4         | 0.08%   |
| Micro Star International         | 4         | 0.08%   |
| AKAI Professional M.I.           | 4         | 0.08%   |
| Valve Software                   | 3         | 0.06%   |
| Tenx Technology                  | 3         | 0.06%   |
| Schiit Audio                     | 3         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 276       | 4.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 274       | 4.44%   |
| AMD Family 17h/19h HD Audio Controller                                     | 264       | 4.28%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 230       | 3.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 194       | 3.14%   |
| Intel Cannon Lake PCH cAVS                                                 | 165       | 2.67%   |
| AMD Starship/Matisse HD Audio Controller                                   | 151       | 2.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 148       | 2.4%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 145       | 2.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 140       | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 134       | 2.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 123       | 1.99%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 114       | 1.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 104       | 1.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 104       | 1.68%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 97        | 1.57%   |
| AMD FCH Azalia Controller                                                  | 88        | 1.43%   |
| Nvidia GP107GL High Definition Audio Controller                            | 83        | 1.34%   |
| Intel Haswell-ULT HD Audio Controller                                      | 82        | 1.33%   |
| Intel 8 Series HD Audio Controller                                         | 82        | 1.33%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 74        | 1.2%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 73        | 1.18%   |
| Intel Broadwell-U Audio Controller                                         | 71        | 1.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 70        | 1.13%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 69        | 1.12%   |
| Nvidia High Definition Audio Controller                                    | 68        | 1.1%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 68        | 1.1%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 66        | 1.07%   |
| Intel Comet Lake PCH-LP cAVS                                               | 65        | 1.05%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 64        | 1.04%   |
| Intel Jasper Lake HD Audio                                                 | 63        | 1.02%   |
| Intel 200 Series PCH HD Audio                                              | 63        | 1.02%   |
| Nvidia TU106 High Definition Audio Controller                              | 55        | 0.89%   |
| Intel CM238 HD Audio Controller                                            | 53        | 0.86%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 53        | 0.86%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 52        | 0.84%   |
| Intel Comet Lake PCH cAVS                                                  | 51        | 0.83%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 48        | 0.78%   |
| Nvidia GF108 High Definition Audio Controller                              | 47        | 0.76%   |
| Nvidia GP106 High Definition Audio Controller                              | 46        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 484       | 22.05%  |
| Samsung Electronics | 434       | 19.77%  |
| Kingston            | 243       | 11.07%  |
| Micron Technology   | 227       | 10.34%  |
| Corsair             | 182       | 8.29%   |
| Unknown             | 166       | 7.56%   |
| Crucial             | 148       | 6.74%   |
| G.Skill             | 69        | 3.14%   |
| Nanya Technology    | 32        | 1.46%   |
| A-DATA Technology   | 32        | 1.46%   |
| Ramaxel Technology  | 31        | 1.41%   |
| Elpida              | 22        | 1%      |
| Unknown             | 14        | 0.64%   |
| Transcend           | 12        | 0.55%   |
| Unknown (ABCD)      | 9         | 0.41%   |
| Team                | 8         | 0.36%   |
| GOODRAM             | 8         | 0.36%   |
| Qimonda             | 7         | 0.32%   |
| ASint Technology    | 5         | 0.23%   |
| Patriot             | 4         | 0.18%   |
| 48spaces            | 4         | 0.18%   |
| Wilk                | 3         | 0.14%   |
| GeIL                | 3         | 0.14%   |
| Axiom               | 3         | 0.14%   |
| Toshiba             | 2         | 0.09%   |
| TakeMS              | 2         | 0.09%   |
| Lexar               | 2         | 0.09%   |
| Goldkey             | 2         | 0.09%   |
| Atermiter           | 2         | 0.09%   |
| AMD                 | 2         | 0.09%   |
| A-DA                | 2         | 0.09%   |
| A Force             | 2         | 0.09%   |
| ZIFEI               | 1         | 0.05%   |
| zApacer             | 1         | 0.05%   |
| Unknown (AD8A)      | 1         | 0.05%   |
| Unknown (768A)      | 1         | 0.05%   |
| Unknown (0x873E)    | 1         | 0.05%   |
| Unknown (08C8)      | 1         | 0.05%   |
| Timetec             | 1         | 0.05%   |
| tigo                | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s | 43        | 1.84%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 30        | 1.28%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s       | 25        | 1.07%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 19        | 0.81%   |
| Micron RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s           | 19        | 0.81%   |
| SK hynix RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s         | 17        | 0.73%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 16        | 0.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 14        | 0.6%    |
| Unknown                                                        | 14        | 0.6%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 13        | 0.56%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 13        | 0.56%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 13        | 0.56%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s           | 13        | 0.56%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 12        | 0.51%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s      | 12        | 0.51%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 12        | 0.51%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 12        | 0.51%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s         | 12        | 0.51%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 12        | 0.51%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 11        | 0.47%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 11        | 0.47%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 10        | 0.43%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 9         | 0.38%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 9         | 0.38%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 9         | 0.38%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                   | 8         | 0.34%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 8         | 0.34%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 8         | 0.34%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 8         | 0.34%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s       | 8         | 0.34%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 8         | 0.34%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s          | 8         | 0.34%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s           | 8         | 0.34%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 8         | 0.34%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 8         | 0.34%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 8         | 0.34%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s            | 7         | 0.3%    |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                    | 7         | 0.3%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 7         | 0.3%    |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s         | 7         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 929       | 48.04%  |
| DDR3    | 592       | 30.61%  |
| LPDDR4  | 123       | 6.36%   |
| DDR2    | 79        | 4.08%   |
| LPDDR3  | 64        | 3.31%   |
| SDRAM   | 56        | 2.9%    |
| DDR5    | 30        | 1.55%   |
| Unknown | 28        | 1.45%   |
| LPDDR5  | 17        | 0.88%   |
| DDR     | 12        | 0.62%   |
| DRAM    | 3         | 0.16%   |
| EEPROM  | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1114      | 57.66%  |
| DIMM         | 587       | 30.38%  |
| Row Of Chips | 209       | 10.82%  |
| Chip         | 9         | 0.47%   |
| Unknown      | 9         | 0.47%   |
| FB-DIMM      | 2         | 0.1%    |
| RIMM         | 1         | 0.05%   |
| DIP          | 1         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 815       | 39.01%  |
| 4096  | 532       | 25.47%  |
| 16384 | 328       | 15.7%   |
| 2048  | 266       | 12.73%  |
| 1024  | 77        | 3.69%   |
| 32768 | 58        | 2.78%   |
| 512   | 10        | 0.48%   |
| 256   | 1         | 0.05%   |
| 64    | 1         | 0.05%   |
| 1     | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 358       | 17.36%  |
| 2667    | 306       | 14.84%  |
| 3200    | 302       | 14.65%  |
| 2400    | 160       | 7.76%   |
| 1333    | 132       | 6.4%    |
| 2133    | 108       | 5.24%   |
| 4267    | 91        | 4.41%   |
| 1334    | 61        | 2.96%   |
| 3600    | 59        | 2.86%   |
| 1867    | 51        | 2.47%   |
| 800     | 47        | 2.28%   |
| 667     | 44        | 2.13%   |
| Unknown | 32        | 1.55%   |
| 4800    | 21        | 1.02%   |
| 1066    | 21        | 1.02%   |
| 6400    | 18        | 0.87%   |
| 3400    | 15        | 0.73%   |
| 1067    | 15        | 0.73%   |
| 2933    | 14        | 0.68%   |
| 3266    | 13        | 0.63%   |
| 1866    | 13        | 0.63%   |
| 8400    | 12        | 0.58%   |
| 3000    | 11        | 0.53%   |
| 3533    | 10        | 0.48%   |
| 2048    | 10        | 0.48%   |
| 1800    | 10        | 0.48%   |
| 4199    | 9         | 0.44%   |
| 3866    | 9         | 0.44%   |
| 3800    | 8         | 0.39%   |
| 400     | 8         | 0.39%   |
| 4266    | 7         | 0.34%   |
| 3733    | 7         | 0.34%   |
| 1639    | 7         | 0.34%   |
| 3466    | 6         | 0.29%   |
| 2666    | 6         | 0.29%   |
| 533     | 6         | 0.29%   |
| 6000    | 5         | 0.24%   |
| 2800    | 5         | 0.24%   |
| 49926   | 3         | 0.15%   |
| 3666    | 3         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 27        | 29.35%  |
| Brother Industries  | 18        | 19.57%  |
| Canon               | 16        | 17.39%  |
| Samsung Electronics | 9         | 9.78%   |
| Seiko Epson         | 7         | 7.61%   |
| Dymo-CoStar         | 7         | 7.61%   |
| Citizen             | 4         | 4.35%   |
| Zebra               | 1         | 1.09%   |
| STMicroelectronics  | 1         | 1.09%   |
| Ricoh               | 1         | 1.09%   |
| Prolific Technology | 1         | 1.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2620 All-in-One Printer                        | 4         | 4.35%   |
| Dymo-CoStar LabelWriter 450                               | 4         | 4.35%   |
| Citizen Thermal Receipt Printer [CT-E351]                 | 4         | 4.35%   |
| HP ENVY 5000 series                                       | 3         | 3.26%   |
| HP Deskjet 2540 series                                    | 3         | 3.26%   |
| Seiko Epson ET-2820 Series                                | 2         | 2.17%   |
| Samsung SCX-4600 Series                                   | 2         | 2.17%   |
| Samsung ML-1640 Series Laser Printer                      | 2         | 2.17%   |
| Canon TS3100 series                                       | 2         | 2.17%   |
| Canon PIXMA MX920 Series                                  | 2         | 2.17%   |
| Canon PIXMA MG2500 Series                                 | 2         | 2.17%   |
| Canon MG5600 series                                       | 2         | 2.17%   |
| Brother Printer                                           | 2         | 2.17%   |
| Brother HL-2030 Laser Printer                             | 2         | 2.17%   |
| Zebra Printer                                             | 1         | 1.09%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.09%   |
| Seiko Epson XP-4200 Series                                | 1         | 1.09%   |
| Seiko Epson XP-200 Series                                 | 1         | 1.09%   |
| Seiko Epson Thermal Receipt Printer [TM-T20]              | 1         | 1.09%   |
| Seiko Epson Printer                                       | 1         | 1.09%   |
| Seiko Epson ET-2720 Series                                | 1         | 1.09%   |
| Samsung SCX-4300 Series                                   | 1         | 1.09%   |
| Samsung ML-2240 Series                                    | 1         | 1.09%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 1.09%   |
| Samsung C48x Series                                       | 1         | 1.09%   |
| Samsung C43x Series                                       | 1         | 1.09%   |
| Ricoh Aficio SP 3510DN                                    | 1         | 1.09%   |
| Prolific PL2305 Parallel Port                             | 1         | 1.09%   |
| HP Printing Support                                       | 1         | 1.09%   |
| HP OfficeJet Pro 8020 series                              | 1         | 1.09%   |
| HP OfficeJet 8010 series                                  | 1         | 1.09%   |
| HP OfficeJet 6950                                         | 1         | 1.09%   |
| HP OfficeJet 3830 series                                  | 1         | 1.09%   |
| HP LaserJet Professional P1102w                           | 1         | 1.09%   |
| HP LaserJet P1005                                         | 1         | 1.09%   |
| HP LaserJet 1320                                          | 1         | 1.09%   |
| HP Laser 107a                                             | 1         | 1.09%   |
| HP DeskJet F2100 Printer series                           | 1         | 1.09%   |
| HP Deskjet D1500 series                                   | 1         | 1.09%   |
| HP DeskJet 916C                                           | 1         | 1.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 23        | 62.16%  |
| Seiko Epson     | 7         | 18.92%  |
| Mustek Systems  | 4         | 10.81%  |
| Hewlett-Packard | 2         | 5.41%   |
| Plustek         | 1         | 2.7%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                       | 4         | 10.53%  |
| Canon CanoScan LiDE 210                       | 4         | 10.53%  |
| Mustek Systems ScanExpress 1200 UB            | 3         | 7.89%   |
| Seiko Epson Scanner                           | 2         | 5.26%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]   | 2         | 5.26%   |
| Seiko Epson GT-X770 [Perfection V500]         | 2         | 5.26%   |
| Canon CanoScan N670U/N676U/LiDE 20            | 2         | 5.26%   |
| Canon CanoScan N650U/N656U                    | 2         | 5.26%   |
| Canon CanoScan LiDE 200                       | 2         | 5.26%   |
| Canon CanoScan LiDE 120                       | 2         | 5.26%   |
| Canon CanoScan LiDE 110                       | 2         | 5.26%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 2.63%   |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 2.63%   |
| Plustek 600dpi USB Scanner                    | 1         | 2.63%   |
| Mustek Systems BearPaw 2400 CU Plus           | 1         | 2.63%   |
| HP ScanJet 5590                               | 1         | 2.63%   |
| HP ScanJet 3300c                              | 1         | 2.63%   |
| Canon CanoScan N1240U/LiDE 30                 | 1         | 2.63%   |
| Canon CanoScan LiDE 60                        | 1         | 2.63%   |
| Canon CanoScan FB630U                         | 1         | 2.63%   |
| Canon CanoScan 9000F Mark II                  | 1         | 2.63%   |
| Canon CanoScan 5600F                          | 1         | 2.63%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 496       | 21.01%  |
| Microdia                               | 272       | 11.52%  |
| Realtek Semiconductor                  | 228       | 9.66%   |
| IMC Networks                           | 188       | 7.96%   |
| Sunplus Innovation Technology          | 163       | 6.9%    |
| Logitech                               | 152       | 6.44%   |
| Cheng Uei Precision Industry (Foxlink) | 101       | 4.28%   |
| Apple                                  | 94        | 3.98%   |
| Bison Electronics                      | 92        | 3.9%    |
| Quanta                                 | 79        | 3.35%   |
| Suyin                                  | 72        | 3.05%   |
| Acer                                   | 65        | 2.75%   |
| Lite-On Technology                     | 46        | 1.95%   |
| Syntek                                 | 30        | 1.27%   |
| Luxvisions Innotech Limited            | 26        | 1.1%    |
| Samsung Electronics                    | 23        | 0.97%   |
| Silicon Motion                         | 21        | 0.89%   |
| Ricoh                                  | 18        | 0.76%   |
| Microsoft                              | 17        | 0.72%   |
| Lenovo                                 | 16        | 0.68%   |
| Alcor Micro                            | 16        | 0.68%   |
| Primax Electronics                     | 13        | 0.55%   |
| Trust                                  | 10        | 0.42%   |
| Importek                               | 8         | 0.34%   |
| Sonix Technology                       | 7         | 0.3%    |
| Jieli Technology                       | 7         | 0.3%    |
| MacroSilicon                           | 6         | 0.25%   |
| Generalplus Technology                 | 6         | 0.25%   |
| ALi                                    | 5         | 0.21%   |
| Z-Star Microelectronics                | 4         | 0.17%   |
| Sweex                                  | 4         | 0.17%   |
| SunplusIT                              | 4         | 0.17%   |
| Creative Technology                    | 4         | 0.17%   |
| ARC International                      | 4         | 0.17%   |
| Y Media                                | 3         | 0.13%   |
| Valve Software                         | 3         | 0.13%   |
| Ruision                                | 3         | 0.13%   |
| LG Electronics                         | 3         | 0.13%   |
| Genesys Logic                          | 3         | 0.13%   |
| Alpha Imaging Technology               | 3         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 167       | 6.93%   |
| Realtek Integrated_Webcam_HD                                               | 87        | 3.61%   |
| Chicony Integrated Camera                                                  | 80        | 3.32%   |
| Sunplus Integrated_Webcam_HD                                               | 70        | 2.9%    |
| Realtek Integrated_Webcam_5M                                               | 68        | 2.82%   |
| IMC Networks Integrated Camera                                             | 68        | 2.82%   |
| Chicony HD WebCam                                                          | 62        | 2.57%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 40        | 1.66%   |
| Chicony HP HD Camera                                                       | 35        | 1.45%   |
| Logitech Webcam C270                                                       | 30        | 1.24%   |
| Apple Built-in iSight                                                      | 28        | 1.16%   |
| Chicony USB2.0 Camera                                                      | 26        | 1.08%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 25        | 1.04%   |
| Acer Integrated Camera                                                     | 25        | 1.04%   |
| Samsung Galaxy A5 (MTP)                                                    | 23        | 0.95%   |
| Logitech HD Pro Webcam C920                                                | 22        | 0.91%   |
| Chicony HP Wide Vision HD Camera                                           | 22        | 0.91%   |
| Bison Integrated Camera                                                    | 21        | 0.87%   |
| Microdia Integrated_Webcam_5M                                              | 20        | 0.83%   |
| Chicony USB 2.0 Camera                                                     | 19        | 0.79%   |
| Apple FaceTime HD Camera (Built-in)                                        | 19        | 0.79%   |
| Apple FaceTime HD Camera                                                   | 19        | 0.79%   |
| Syntek Integrated Camera                                                   | 18        | 0.75%   |
| Bison BisonCam,NB Pro                                                      | 18        | 0.75%   |
| Chicony TOSHIBA Web Camera - HD                                            | 17        | 0.71%   |
| Sunplus HD WebCam                                                          | 16        | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 16        | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 16        | 0.66%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 15        | 0.62%   |
| Logitech Webcam C310                                                       | 15        | 0.62%   |
| Realtek USB Camera                                                         | 13        | 0.54%   |
| Quanta HD User Facing                                                      | 13        | 0.54%   |
| Microdia Integrated Webcam                                                 | 13        | 0.54%   |
| Lite-On HP HD Camera                                                       | 13        | 0.54%   |
| Quanta HP Wide Vision HD Camera                                            | 12        | 0.5%    |
| Quanta HP HD Camera                                                        | 12        | 0.5%    |
| Logitech C922 Pro Stream Webcam                                            | 12        | 0.5%    |
| Lite-On Integrated Camera                                                  | 12        | 0.5%    |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 12        | 0.5%    |
| IMC Networks Integrated Webcam                                             | 12        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 154       | 32.98%  |
| Synaptics                          | 150       | 32.12%  |
| Shenzhen Goodix Technology         | 59        | 12.63%  |
| AuthenTec                          | 32        | 6.85%   |
| Elan Microelectronics              | 25        | 5.35%   |
| LighTuning Technology              | 22        | 4.71%   |
| Upek                               | 20        | 4.28%   |
| STMicroelectronics                 | 3         | 0.64%   |
| Samsung Electronics                | 1         | 0.21%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.21%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 52        | 11.13%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 40        | 8.57%   |
| Shenzhen Goodix  FingerPrint Device                                        | 25        | 5.35%   |
| Synaptics UWP WBDI                                                         | 20        | 4.28%   |
| Validity Sensors VFS491                                                    | 19        | 4.07%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 19        | 4.07%   |
| Shenzhen Goodix FingerPrint                                                | 19        | 4.07%   |
| Shenzhen Goodix Fingerprint Reader                                         | 15        | 3.21%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 14        | 3%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 14        | 3%      |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 3%      |
| Validity Sensors VFS451 Fingerprint Reader                                 | 13        | 2.78%   |
| Elan ELAN:ARM-M4                                                           | 13        | 2.78%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 12        | 2.57%   |
| Synaptics  WBDI                                                            | 12        | 2.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 12        | 2.57%   |
| Elan ELAN:Fingerprint                                                      | 12        | 2.57%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 12        | 2.57%   |
| Synaptics WBDI                                                             | 11        | 2.36%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 11        | 2.36%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 2.14%   |
| AuthenTec AES2810                                                          | 9         | 1.93%   |
| Unknown                                                                    | 7         | 1.5%    |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.28%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.28%   |
| AuthenTec AES1600                                                          | 6         | 1.28%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.07%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.07%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 1.07%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 5         | 1.07%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 1.07%   |
| Synaptics WBDI Device                                                      | 4         | 0.86%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 4         | 0.86%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.64%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.64%   |
| Synaptics UWP WBDI Device                                                  | 3         | 0.64%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.64%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 0.64%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.64%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 114       | 53.02%  |
| Alcor Micro                       | 55        | 25.58%  |
| O2 Micro                          | 23        | 10.7%   |
| Upek                              | 7         | 3.26%   |
| Lenovo                            | 6         | 2.79%   |
| Gemalto (was Gemplus)             | 2         | 0.93%   |
| Yubico.com                        | 1         | 0.47%   |
| VASCO Data Security International | 1         | 0.47%   |
| SCM Microsystems                  | 1         | 0.47%   |
| OmniKey                           | 1         | 0.47%   |
| Fujitsu Siemens Computers         | 1         | 0.47%   |
| Clay Logic                        | 1         | 0.47%   |
| Chicony Electronics               | 1         | 0.47%   |
| Advanced Card Systems             | 1         | 0.47%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 55        | 25.58%  |
| Broadcom BCM5880 Secure Applications Processor                               | 36        | 16.74%  |
| Broadcom 58200                                                               | 33        | 15.35%  |
| Broadcom 5880                                                                | 24        | 11.16%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 9.77%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 21        | 9.77%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 3.26%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 2.79%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 0.93%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.47%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.47%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.47%   |
| OmniKey 5422 Smartcard Reader                                                | 1         | 0.47%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.47%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.47%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.47%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 0.47%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.47%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.47%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2691      | 67.9%   |
| 1     | 997       | 25.16%  |
| 2     | 221       | 5.58%   |
| 3     | 36        | 0.91%   |
| 4     | 9         | 0.23%   |
| 5     | 5         | 0.13%   |
| 6     | 3         | 0.08%   |
| 8     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 462       | 29.65%  |
| Graphics card            | 314       | 20.15%  |
| Chipcard                 | 189       | 12.13%  |
| Net/wireless             | 154       | 9.88%   |
| Multimedia controller    | 154       | 9.88%   |
| Communication controller | 60        | 3.85%   |
| Camera                   | 50        | 3.21%   |
| Bluetooth                | 29        | 1.86%   |
| Unassigned class         | 28        | 1.8%    |
| Sound                    | 24        | 1.54%   |
| Storage                  | 20        | 1.28%   |
| Network                  | 16        | 1.03%   |
| Card reader              | 16        | 1.03%   |
| Net/ethernet             | 13        | 0.83%   |
| Flash memory             | 8         | 0.51%   |
| Storage/ide              | 5         | 0.32%   |
| Storage/ata              | 5         | 0.32%   |
| Modem                    | 3         | 0.19%   |
| Tv card                  | 2         | 0.13%   |
| Storage/raid             | 2         | 0.13%   |
| Storage/nvme             | 2         | 0.13%   |
| Firewire controller      | 1         | 0.06%   |
| Dvb card                 | 1         | 0.06%   |

