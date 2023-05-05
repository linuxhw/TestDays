Xubuntu 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Xubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Xubuntu_22.04/Notebook/README.md).

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

Total: 545

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | X58A-UD3R                   | Desktop     | [36f4134c6b](https://linux-hardware.org/?probe=36f4134c6b) | May 01, 2023 |
| Toshiba       | EQUIUM P200                 | Notebook    | [812a164a8a](https://linux-hardware.org/?probe=812a164a8a) | Apr 30, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [95d59e1bc3](https://linux-hardware.org/?probe=95d59e1bc3) | Apr 28, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [b2c012c1e2](https://linux-hardware.org/?probe=b2c012c1e2) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [dfd3d8a5c5](https://linux-hardware.org/?probe=dfd3d8a5c5) | Apr 27, 2023 |
| MSI           | GP65 Leopard 10SDK          | Notebook    | [fc66ccccde](https://linux-hardware.org/?probe=fc66ccccde) | Apr 27, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [09f98983fd](https://linux-hardware.org/?probe=09f98983fd) | Apr 27, 2023 |
| SGIN          | M15                         | Notebook    | [ac5d947f22](https://linux-hardware.org/?probe=ac5d947f22) | Apr 27, 2023 |
| Radxa         | ROCK Pi 4B                  | Soc         | [4382f0cce7](https://linux-hardware.org/?probe=4382f0cce7) | Apr 27, 2023 |
| HP            | 1632                        | Desktop     | [b818834691](https://linux-hardware.org/?probe=b818834691) | Apr 26, 2023 |
| HP            | 1632                        | Desktop     | [caae9b5992](https://linux-hardware.org/?probe=caae9b5992) | Apr 26, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [ef4bb434d9](https://linux-hardware.org/?probe=ef4bb434d9) | Apr 26, 2023 |
| HP            | 470 17 inch G9 Notebook ... | Notebook    | [6b73c4cb65](https://linux-hardware.org/?probe=6b73c4cb65) | Apr 24, 2023 |
| Lenovo        | ThinkPad T420 4236PA8       | Notebook    | [f45e2448aa](https://linux-hardware.org/?probe=f45e2448aa) | Apr 24, 2023 |
| HP            | ProBook 11 G2               | Notebook    | [43f6a6180a](https://linux-hardware.org/?probe=43f6a6180a) | Apr 24, 2023 |
| Dell          | XPS 13 9333                 | Notebook    | [0fedfa2911](https://linux-hardware.org/?probe=0fedfa2911) | Apr 22, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [4611a1d998](https://linux-hardware.org/?probe=4611a1d998) | Apr 22, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C50... | Notebook    | [77cfc9d5b2](https://linux-hardware.org/?probe=77cfc9d5b2) | Apr 22, 2023 |
| HP            | 0AECh D                     | Desktop     | [827246f901](https://linux-hardware.org/?probe=827246f901) | Apr 22, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [3e1880b375](https://linux-hardware.org/?probe=3e1880b375) | Apr 20, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [194535b314](https://linux-hardware.org/?probe=194535b314) | Apr 19, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [9f2a1a2c93](https://linux-hardware.org/?probe=9f2a1a2c93) | Apr 19, 2023 |
| HP            | ProBook 11 G2               | Notebook    | [222f45e8c6](https://linux-hardware.org/?probe=222f45e8c6) | Apr 18, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4c6934e946](https://linux-hardware.org/?probe=4c6934e946) | Apr 17, 2023 |
| HP            | Pavilion g6                 | Notebook    | [5fc4a56d59](https://linux-hardware.org/?probe=5fc4a56d59) | Apr 17, 2023 |
| ASRock        | N3700-ITX                   | Desktop     | [849679b442](https://linux-hardware.org/?probe=849679b442) | Apr 17, 2023 |
| ASRock        | X370 Killer SLI             | Desktop     | [912a7f830b](https://linux-hardware.org/?probe=912a7f830b) | Apr 16, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [7b5363bc3e](https://linux-hardware.org/?probe=7b5363bc3e) | Apr 16, 2023 |
| HP            | Laptop 17-cp2xxx            | Notebook    | [b901ff7e98](https://linux-hardware.org/?probe=b901ff7e98) | Apr 14, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [7f4ed3cfde](https://linux-hardware.org/?probe=7f4ed3cfde) | Apr 13, 2023 |
| Lenovo        | ThinkPad X200s 74664SJ      | Notebook    | [54088fa2e9](https://linux-hardware.org/?probe=54088fa2e9) | Apr 13, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [93fae77e6c](https://linux-hardware.org/?probe=93fae77e6c) | Apr 13, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [fcbc0b286f](https://linux-hardware.org/?probe=fcbc0b286f) | Apr 12, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [f44505b54b](https://linux-hardware.org/?probe=f44505b54b) | Apr 12, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [48b143cc2f](https://linux-hardware.org/?probe=48b143cc2f) | Apr 12, 2023 |
| Medion        | MS-7848                     | Desktop     | [40e46961a4](https://linux-hardware.org/?probe=40e46961a4) | Apr 08, 2023 |
| Dell          | 060J9C A00                  | Mini pc     | [71ee0575d4](https://linux-hardware.org/?probe=71ee0575d4) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | Notebook    | [d510eabb78](https://linux-hardware.org/?probe=d510eabb78) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | Notebook    | [3c8c0e7455](https://linux-hardware.org/?probe=3c8c0e7455) | Apr 08, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [c7444ac7f0](https://linux-hardware.org/?probe=c7444ac7f0) | Apr 07, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [fc1b119dca](https://linux-hardware.org/?probe=fc1b119dca) | Apr 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [93cb5f66a1](https://linux-hardware.org/?probe=93cb5f66a1) | Apr 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [2ac5f02bb5](https://linux-hardware.org/?probe=2ac5f02bb5) | Apr 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c80b7018f6](https://linux-hardware.org/?probe=c80b7018f6) | Apr 05, 2023 |
| Dell          | Latitude E6400              | Notebook    | [5aa68e620c](https://linux-hardware.org/?probe=5aa68e620c) | Apr 04, 2023 |
| Acer          | NU-SF314-42-R3S0            | Notebook    | [6f56806ef1](https://linux-hardware.org/?probe=6f56806ef1) | Apr 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [3a225208fd](https://linux-hardware.org/?probe=3a225208fd) | Apr 02, 2023 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [f7cdc4223d](https://linux-hardware.org/?probe=f7cdc4223d) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [8bc61e0fcd](https://linux-hardware.org/?probe=8bc61e0fcd) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [0f26b74917](https://linux-hardware.org/?probe=0f26b74917) | Mar 30, 2023 |
| Medion        | S321X                       | Notebook    | [4c02136dda](https://linux-hardware.org/?probe=4c02136dda) | Mar 30, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [a46eb24b2a](https://linux-hardware.org/?probe=a46eb24b2a) | Mar 29, 2023 |
| MSI           | MS-AA8B 100                 | All in one  | [8f698075ee](https://linux-hardware.org/?probe=8f698075ee) | Mar 27, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [426c7d7939](https://linux-hardware.org/?probe=426c7d7939) | Mar 25, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [da0d90d69f](https://linux-hardware.org/?probe=da0d90d69f) | Mar 25, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [a822425dcf](https://linux-hardware.org/?probe=a822425dcf) | Mar 25, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [3d8b7a6d89](https://linux-hardware.org/?probe=3d8b7a6d89) | Mar 25, 2023 |
| MSI           | H81M-E33                    | Desktop     | [47f031e68c](https://linux-hardware.org/?probe=47f031e68c) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [34d3fc12b2](https://linux-hardware.org/?probe=34d3fc12b2) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [f7aaf1dcd0](https://linux-hardware.org/?probe=f7aaf1dcd0) | Mar 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [fb97269a4d](https://linux-hardware.org/?probe=fb97269a4d) | Mar 24, 2023 |
| Gigabyte      | AERO 15WV8                  | Notebook    | [379c88860a](https://linux-hardware.org/?probe=379c88860a) | Mar 23, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [204b7c3324](https://linux-hardware.org/?probe=204b7c3324) | Mar 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [bbd16627c2](https://linux-hardware.org/?probe=bbd16627c2) | Mar 22, 2023 |
| ASRock        | H270 Pro4                   | Desktop     | [01eb4c8ba5](https://linux-hardware.org/?probe=01eb4c8ba5) | Mar 22, 2023 |
| Gateway       | EC14 Series                 | Notebook    | [fdeb2e4e3b](https://linux-hardware.org/?probe=fdeb2e4e3b) | Mar 22, 2023 |
| Getac         | F110G3                      | Notebook    | [792ac98040](https://linux-hardware.org/?probe=792ac98040) | Mar 22, 2023 |
| HP            | EliteBook 725 G2            | Notebook    | [5112f86dde](https://linux-hardware.org/?probe=5112f86dde) | Mar 21, 2023 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [5c07e530e9](https://linux-hardware.org/?probe=5c07e530e9) | Mar 21, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [00b550c606](https://linux-hardware.org/?probe=00b550c606) | Mar 18, 2023 |
| Gateway       | EC14 Series                 | Notebook    | [c6ea9d7f10](https://linux-hardware.org/?probe=c6ea9d7f10) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [182bd8cca1](https://linux-hardware.org/?probe=182bd8cca1) | Mar 16, 2023 |
| MSI           | H81M-E34                    | Desktop     | [4cad3cfe12](https://linux-hardware.org/?probe=4cad3cfe12) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 20RES05U00     | Notebook    | [7047c529ef](https://linux-hardware.org/?probe=7047c529ef) | Mar 13, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [a6af61dfb4](https://linux-hardware.org/?probe=a6af61dfb4) | Mar 13, 2023 |
| Google        | Kefka                       | Notebook    | [58abcf00e9](https://linux-hardware.org/?probe=58abcf00e9) | Mar 12, 2023 |
| HP            | 0A64h                       | Desktop     | [d5b197e7f2](https://linux-hardware.org/?probe=d5b197e7f2) | Mar 12, 2023 |
| HP            | 0A64h                       | Desktop     | [14de22ae05](https://linux-hardware.org/?probe=14de22ae05) | Mar 11, 2023 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [728697bff3](https://linux-hardware.org/?probe=728697bff3) | Mar 11, 2023 |
| Xunlong       | Orange Pi PC Plus           | Soc         | [ac565d5d7d](https://linux-hardware.org/?probe=ac565d5d7d) | Mar 11, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [e2b7d998d8](https://linux-hardware.org/?probe=e2b7d998d8) | Mar 11, 2023 |
| Lenovo        | ThinkPad T510 4384VJZ       | Notebook    | [d9c87b4795](https://linux-hardware.org/?probe=d9c87b4795) | Mar 11, 2023 |
| Foxconn       | ETON                        | Desktop     | [3a087bc020](https://linux-hardware.org/?probe=3a087bc020) | Mar 10, 2023 |
| Xunlong       | Orange Pi PC Plus           | Soc         | [ad41e0e370](https://linux-hardware.org/?probe=ad41e0e370) | Mar 09, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [6f915814dd](https://linux-hardware.org/?probe=6f915814dd) | Mar 08, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [5fdd1701df](https://linux-hardware.org/?probe=5fdd1701df) | Mar 08, 2023 |
| Foxconn       | ETON                        | Desktop     | [2afed9b076](https://linux-hardware.org/?probe=2afed9b076) | Mar 08, 2023 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | Desktop     | [44509323b0](https://linux-hardware.org/?probe=44509323b0) | Mar 08, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [2d093cc3ef](https://linux-hardware.org/?probe=2d093cc3ef) | Mar 08, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [57d690358f](https://linux-hardware.org/?probe=57d690358f) | Mar 08, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [32dedf99a8](https://linux-hardware.org/?probe=32dedf99a8) | Mar 07, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [5bd9a1c0d2](https://linux-hardware.org/?probe=5bd9a1c0d2) | Mar 07, 2023 |
| Toshiba       | Satellite C55D-B            | Notebook    | [963b41587c](https://linux-hardware.org/?probe=963b41587c) | Mar 07, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [a3dbc9b45e](https://linux-hardware.org/?probe=a3dbc9b45e) | Mar 07, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [ade979391f](https://linux-hardware.org/?probe=ade979391f) | Mar 07, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [9404cddcdf](https://linux-hardware.org/?probe=9404cddcdf) | Mar 07, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [439ec46914](https://linux-hardware.org/?probe=439ec46914) | Mar 05, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [ec9c2f21a5](https://linux-hardware.org/?probe=ec9c2f21a5) | Mar 05, 2023 |
| Radxa         | ROCK Pi 4C+                 | Soc         | [e513434675](https://linux-hardware.org/?probe=e513434675) | Mar 04, 2023 |
| Radxa         | ROCK Pi 4C+                 | Soc         | [5c3d9047bd](https://linux-hardware.org/?probe=5c3d9047bd) | Mar 04, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [c9efc71e60](https://linux-hardware.org/?probe=c9efc71e60) | Mar 04, 2023 |
| OEM           | Unknown                     | Desktop     | [d0f1ae246c](https://linux-hardware.org/?probe=d0f1ae246c) | Mar 03, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [e367c45f3b](https://linux-hardware.org/?probe=e367c45f3b) | Mar 03, 2023 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | Desktop     | [c803be2765](https://linux-hardware.org/?probe=c803be2765) | Mar 02, 2023 |
| Google        | Nautilus                    | Convertible | [5aff7271ac](https://linux-hardware.org/?probe=5aff7271ac) | Mar 02, 2023 |
| AZW           | GTR V01                     | Mini pc     | [09e66839c3](https://linux-hardware.org/?probe=09e66839c3) | Mar 01, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [45f781ee3a](https://linux-hardware.org/?probe=45f781ee3a) | Feb 28, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [de0d12baa4](https://linux-hardware.org/?probe=de0d12baa4) | Feb 27, 2023 |
| HP            | 655                         | Notebook    | [e6b694526e](https://linux-hardware.org/?probe=e6b694526e) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [3f35f45bf0](https://linux-hardware.org/?probe=3f35f45bf0) | Feb 26, 2023 |
| Gigabyte      | MZBSWBP-00                  | Desktop     | [525ac20362](https://linux-hardware.org/?probe=525ac20362) | Feb 26, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [75a0fcca48](https://linux-hardware.org/?probe=75a0fcca48) | Feb 25, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [634b80ac90](https://linux-hardware.org/?probe=634b80ac90) | Feb 24, 2023 |
| Dell          | Latitude E5470              | Notebook    | [d7c8a049c4](https://linux-hardware.org/?probe=d7c8a049c4) | Feb 24, 2023 |
| MSI           | C847MS-E33                  | Desktop     | [698d950f05](https://linux-hardware.org/?probe=698d950f05) | Feb 24, 2023 |
| Dell          | 0YC03K A03                  | Desktop     | [0101ef8ce7](https://linux-hardware.org/?probe=0101ef8ce7) | Feb 23, 2023 |
| Dell          | Studio 1450                 | Notebook    | [c26228f66f](https://linux-hardware.org/?probe=c26228f66f) | Feb 22, 2023 |
| HP            | Pavilion 15                 | Notebook    | [c33178dcdc](https://linux-hardware.org/?probe=c33178dcdc) | Feb 21, 2023 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [c9adb74693](https://linux-hardware.org/?probe=c9adb74693) | Feb 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [7ac4bb7d51](https://linux-hardware.org/?probe=7ac4bb7d51) | Feb 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [19e03ac7b2](https://linux-hardware.org/?probe=19e03ac7b2) | Feb 20, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [51cf60bd9b](https://linux-hardware.org/?probe=51cf60bd9b) | Feb 18, 2023 |
| Sony          | VPCEA3S1E                   | Notebook    | [45d0b9a823](https://linux-hardware.org/?probe=45d0b9a823) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [28c9b2590c](https://linux-hardware.org/?probe=28c9b2590c) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [89c51847f9](https://linux-hardware.org/?probe=89c51847f9) | Feb 18, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [8338ee5a0d](https://linux-hardware.org/?probe=8338ee5a0d) | Feb 17, 2023 |
| Gigabyte      | H410M S2 V3                 | Desktop     | [0dbeeea38c](https://linux-hardware.org/?probe=0dbeeea38c) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [e1bbf14222](https://linux-hardware.org/?probe=e1bbf14222) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [ba96494c0f](https://linux-hardware.org/?probe=ba96494c0f) | Feb 16, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [40c415883e](https://linux-hardware.org/?probe=40c415883e) | Feb 16, 2023 |
| HP            | Pavilion g6                 | Notebook    | [8a53743bd0](https://linux-hardware.org/?probe=8a53743bd0) | Feb 15, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | Notebook    | [d576d16c25](https://linux-hardware.org/?probe=d576d16c25) | Feb 14, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [21ad600245](https://linux-hardware.org/?probe=21ad600245) | Feb 14, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [25dbf25c62](https://linux-hardware.org/?probe=25dbf25c62) | Feb 14, 2023 |
| ASRock        | AOD790GX/128M               | Desktop     | [693f4f40f8](https://linux-hardware.org/?probe=693f4f40f8) | Feb 13, 2023 |
| HP            | Compaq nc6400 (RM741PA#A... | Notebook    | [d556bf453d](https://linux-hardware.org/?probe=d556bf453d) | Feb 13, 2023 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [0634db3367](https://linux-hardware.org/?probe=0634db3367) | Feb 13, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [f840248d22](https://linux-hardware.org/?probe=f840248d22) | Feb 13, 2023 |
| Dell          | Latitude E5450              | Notebook    | [693f8c9c36](https://linux-hardware.org/?probe=693f8c9c36) | Feb 11, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [59a015c31d](https://linux-hardware.org/?probe=59a015c31d) | Feb 11, 2023 |
| Gigabyte      | GA-A75-UD4H                 | Desktop     | [eb4302c6dd](https://linux-hardware.org/?probe=eb4302c6dd) | Feb 10, 2023 |
| Acer          | Extensa 5635ZG              | Notebook    | [dd22b216a9](https://linux-hardware.org/?probe=dd22b216a9) | Feb 08, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [d5bb6335d4](https://linux-hardware.org/?probe=d5bb6335d4) | Feb 08, 2023 |
| Acer          | Aspire E5-572G              | Notebook    | [f44e9ce856](https://linux-hardware.org/?probe=f44e9ce856) | Feb 08, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | Notebook    | [262dfe3aa9](https://linux-hardware.org/?probe=262dfe3aa9) | Feb 05, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9c9aa5e0e0](https://linux-hardware.org/?probe=9c9aa5e0e0) | Feb 03, 2023 |
| HP            | 240 G3                      | Notebook    | [43e56d3ae5](https://linux-hardware.org/?probe=43e56d3ae5) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ccf7f4d126](https://linux-hardware.org/?probe=ccf7f4d126) | Feb 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [c6d48c9847](https://linux-hardware.org/?probe=c6d48c9847) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [fafb999b1a](https://linux-hardware.org/?probe=fafb999b1a) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [50076364b8](https://linux-hardware.org/?probe=50076364b8) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [0211cbb448](https://linux-hardware.org/?probe=0211cbb448) | Feb 03, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [17b77b89e5](https://linux-hardware.org/?probe=17b77b89e5) | Feb 03, 2023 |
| ECS           | SF20PA2                     | Notebook    | [30df19ca2e](https://linux-hardware.org/?probe=30df19ca2e) | Feb 02, 2023 |
| Dell          | 0HFG24 A02                  | Server      | [a05562bc52](https://linux-hardware.org/?probe=a05562bc52) | Feb 02, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [894f632950](https://linux-hardware.org/?probe=894f632950) | Feb 01, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3fac03d01d](https://linux-hardware.org/?probe=3fac03d01d) | Jan 30, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [0f2037dcd8](https://linux-hardware.org/?probe=0f2037dcd8) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [0e28b954b4](https://linux-hardware.org/?probe=0e28b954b4) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [10421fe598](https://linux-hardware.org/?probe=10421fe598) | Jan 30, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6444a93633](https://linux-hardware.org/?probe=6444a93633) | Jan 29, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [64810b20c3](https://linux-hardware.org/?probe=64810b20c3) | Jan 26, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [6de2ea7d90](https://linux-hardware.org/?probe=6de2ea7d90) | Jan 26, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [058de08b2b](https://linux-hardware.org/?probe=058de08b2b) | Jan 24, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Notebook      | W65_67SZ                    | Notebook    | [74d788dccb](https://linux-hardware.org/?probe=74d788dccb) | Jan 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [7e91e49912](https://linux-hardware.org/?probe=7e91e49912) | Jan 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3324fafe5a](https://linux-hardware.org/?probe=3324fafe5a) | Jan 23, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [b5e6a74fcb](https://linux-hardware.org/?probe=b5e6a74fcb) | Jan 22, 2023 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | Notebook    | [68ff3c02cb](https://linux-hardware.org/?probe=68ff3c02cb) | Jan 22, 2023 |
| Gigabyte      | 8I945GMF                    | Desktop     | [2971006e43](https://linux-hardware.org/?probe=2971006e43) | Jan 21, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [82c74e5cca](https://linux-hardware.org/?probe=82c74e5cca) | Jan 21, 2023 |
| Dell          | Venue 11 Pro 7139           | Notebook    | [6c3528d4c0](https://linux-hardware.org/?probe=6c3528d4c0) | Jan 20, 2023 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [6c83597890](https://linux-hardware.org/?probe=6c83597890) | Jan 19, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [fd8b8416ea](https://linux-hardware.org/?probe=fd8b8416ea) | Jan 19, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [80712a04ec](https://linux-hardware.org/?probe=80712a04ec) | Jan 18, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [d5ad4c9486](https://linux-hardware.org/?probe=d5ad4c9486) | Jan 17, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [a49a3ddeaa](https://linux-hardware.org/?probe=a49a3ddeaa) | Jan 17, 2023 |
| ASUSTek       | UX305CA                     | Notebook    | [b831308d6c](https://linux-hardware.org/?probe=b831308d6c) | Jan 16, 2023 |
| Dell          | Latitude E6420              | Notebook    | [3594f88292](https://linux-hardware.org/?probe=3594f88292) | Jan 15, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d667bf6bb2](https://linux-hardware.org/?probe=d667bf6bb2) | Jan 15, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [0277ea7e50](https://linux-hardware.org/?probe=0277ea7e50) | Jan 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [251a926c19](https://linux-hardware.org/?probe=251a926c19) | Jan 14, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b3711a9adc](https://linux-hardware.org/?probe=b3711a9adc) | Jan 13, 2023 |
| HP            | 873A A01                    | Mini pc     | [5c3be4e9aa](https://linux-hardware.org/?probe=5c3be4e9aa) | Jan 13, 2023 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [07a6ffe405](https://linux-hardware.org/?probe=07a6ffe405) | Jan 11, 2023 |
| ASUSTek       | X555YI                      | Notebook    | [4968e51e0b](https://linux-hardware.org/?probe=4968e51e0b) | Jan 10, 2023 |
| Acer          | Veriton N2620G              | Desktop     | [6345424cff](https://linux-hardware.org/?probe=6345424cff) | Jan 07, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [daca90b2bb](https://linux-hardware.org/?probe=daca90b2bb) | Jan 05, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [74bacb92f5](https://linux-hardware.org/?probe=74bacb92f5) | Jan 05, 2023 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [ef5e737fd6](https://linux-hardware.org/?probe=ef5e737fd6) | Jan 04, 2023 |
| MiPi PC       | Mini PC                     | Mini pc     | [776c827bdb](https://linux-hardware.org/?probe=776c827bdb) | Jan 03, 2023 |
| Gigabyte      | J1800N-D2H                  | Desktop     | [f809473b20](https://linux-hardware.org/?probe=f809473b20) | Jan 03, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [da1db1e278](https://linux-hardware.org/?probe=da1db1e278) | Jan 02, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [f1494f113b](https://linux-hardware.org/?probe=f1494f113b) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [79d4fe0592](https://linux-hardware.org/?probe=79d4fe0592) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [aeb6ecee74](https://linux-hardware.org/?probe=aeb6ecee74) | Jan 01, 2023 |
| Unknown       | Intel X79                   | Desktop     | [f26c05e261](https://linux-hardware.org/?probe=f26c05e261) | Dec 31, 2022 |
| Dell          | Latitude E5440              | Notebook    | [9578ad1ea3](https://linux-hardware.org/?probe=9578ad1ea3) | Dec 31, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [cc1d0776d5](https://linux-hardware.org/?probe=cc1d0776d5) | Dec 30, 2022 |
| Lenovo        | ChiefRiver                  | Desktop     | [847a9e86cd](https://linux-hardware.org/?probe=847a9e86cd) | Dec 30, 2022 |
| HP            | 1998                        | Desktop     | [c3404205e3](https://linux-hardware.org/?probe=c3404205e3) | Dec 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [4a8c3f4014](https://linux-hardware.org/?probe=4a8c3f4014) | Dec 29, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [79f628b951](https://linux-hardware.org/?probe=79f628b951) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [15ec0001c5](https://linux-hardware.org/?probe=15ec0001c5) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [e84551a6eb](https://linux-hardware.org/?probe=e84551a6eb) | Dec 29, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [20a055c383](https://linux-hardware.org/?probe=20a055c383) | Dec 29, 2022 |
| Lenovo        | ThinkPad X230 23252S4       | Notebook    | [667dcc287e](https://linux-hardware.org/?probe=667dcc287e) | Dec 28, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [a4d55d44ed](https://linux-hardware.org/?probe=a4d55d44ed) | Dec 28, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [3548fd618d](https://linux-hardware.org/?probe=3548fd618d) | Dec 28, 2022 |
| HIGRADED      | W651UI                      | Notebook    | [66d9d484cd](https://linux-hardware.org/?probe=66d9d484cd) | Dec 27, 2022 |
| Acer          | Veriton NBU                 | Desktop     | [cca454d1bd](https://linux-hardware.org/?probe=cca454d1bd) | Dec 26, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [9bfeb5727a](https://linux-hardware.org/?probe=9bfeb5727a) | Dec 26, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [89b85889f9](https://linux-hardware.org/?probe=89b85889f9) | Dec 25, 2022 |
| ASRock        | N3700-ITX                   | Desktop     | [dc3f0d5062](https://linux-hardware.org/?probe=dc3f0d5062) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [3bf8001e85](https://linux-hardware.org/?probe=3bf8001e85) | Dec 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [8a5bfa5e66](https://linux-hardware.org/?probe=8a5bfa5e66) | Dec 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| ASUSTek       | G60JX                       | Notebook    | [5e9b0bb890](https://linux-hardware.org/?probe=5e9b0bb890) | Dec 23, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [41ec48c0e5](https://linux-hardware.org/?probe=41ec48c0e5) | Dec 23, 2022 |
| ASUSTek       | X555LF                      | Notebook    | [bed000b293](https://linux-hardware.org/?probe=bed000b293) | Dec 22, 2022 |
| HP            | 81C9                        | Desktop     | [cb40ddba01](https://linux-hardware.org/?probe=cb40ddba01) | Dec 22, 2022 |
| Acer          | Aspire A114-31              | Notebook    | [850c0c4a65](https://linux-hardware.org/?probe=850c0c4a65) | Dec 22, 2022 |
| Dell          | Latitude E5450              | Notebook    | [652099945b](https://linux-hardware.org/?probe=652099945b) | Dec 21, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [827696b95a](https://linux-hardware.org/?probe=827696b95a) | Dec 21, 2022 |
| HP            | 8594                        | Desktop     | [de0b36257e](https://linux-hardware.org/?probe=de0b36257e) | Dec 21, 2022 |
| Acer          | Aspire 7730ZG               | Notebook    | [bf9325456e](https://linux-hardware.org/?probe=bf9325456e) | Dec 20, 2022 |
| PCWare        | IPMH81G1                    | Desktop     | [3dc25592eb](https://linux-hardware.org/?probe=3dc25592eb) | Dec 20, 2022 |
| Lenovo        | ThinkPad Edge E545 20B20... | Notebook    | [0293f9b7c3](https://linux-hardware.org/?probe=0293f9b7c3) | Dec 20, 2022 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [52b5b53173](https://linux-hardware.org/?probe=52b5b53173) | Dec 19, 2022 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [64972eb902](https://linux-hardware.org/?probe=64972eb902) | Dec 19, 2022 |
| Sony          | VPCS12V9E                   | Notebook    | [a353c5ef57](https://linux-hardware.org/?probe=a353c5ef57) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [224bdb435d](https://linux-hardware.org/?probe=224bdb435d) | Dec 19, 2022 |
| ASUSTek       | K75VJ                       | Notebook    | [a1b40660b5](https://linux-hardware.org/?probe=a1b40660b5) | Dec 18, 2022 |
| Lenovo        | FLEX-14IWL Laptop 81SQ      | Convertible | [f64e5ab064](https://linux-hardware.org/?probe=f64e5ab064) | Dec 18, 2022 |
| Acer          | Aspire A317-51K             | Notebook    | [b02c6dccc2](https://linux-hardware.org/?probe=b02c6dccc2) | Dec 17, 2022 |
| Packard Be... | PT890-8237A                 | Desktop     | [bb9e8d2cd7](https://linux-hardware.org/?probe=bb9e8d2cd7) | Dec 17, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [fdb9e278dd](https://linux-hardware.org/?probe=fdb9e278dd) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [5c6f8cd52d](https://linux-hardware.org/?probe=5c6f8cd52d) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [87603a034e](https://linux-hardware.org/?probe=87603a034e) | Dec 15, 2022 |
| ECS           | CMPC                        | Notebook    | [53d853228f](https://linux-hardware.org/?probe=53d853228f) | Dec 14, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [282ef194e5](https://linux-hardware.org/?probe=282ef194e5) | Dec 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [c62c8e69b0](https://linux-hardware.org/?probe=c62c8e69b0) | Dec 12, 2022 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [0cc39aa03c](https://linux-hardware.org/?probe=0cc39aa03c) | Dec 12, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [d65a8640af](https://linux-hardware.org/?probe=d65a8640af) | Dec 11, 2022 |
| HP            | 1497                        | Desktop     | [475049bb79](https://linux-hardware.org/?probe=475049bb79) | Dec 10, 2022 |
| Fusion5       | Lapbook T90B                | Notebook    | [73a67d82fd](https://linux-hardware.org/?probe=73a67d82fd) | Dec 10, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [ef403a3962](https://linux-hardware.org/?probe=ef403a3962) | Dec 10, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [aca71547f1](https://linux-hardware.org/?probe=aca71547f1) | Dec 08, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ce802653d4](https://linux-hardware.org/?probe=ce802653d4) | Dec 07, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e2e47d2d43](https://linux-hardware.org/?probe=e2e47d2d43) | Dec 06, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | Notebook    | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [87d3950072](https://linux-hardware.org/?probe=87d3950072) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [89e340c4ec](https://linux-hardware.org/?probe=89e340c4ec) | Nov 30, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [bd30397e24](https://linux-hardware.org/?probe=bd30397e24) | Nov 29, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [3b4f834c63](https://linux-hardware.org/?probe=3b4f834c63) | Nov 29, 2022 |
| ASRock        | H270M-ITX/ac                | Desktop     | [dfc381d411](https://linux-hardware.org/?probe=dfc381d411) | Nov 29, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [472530d650](https://linux-hardware.org/?probe=472530d650) | Nov 29, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [1387bf11ea](https://linux-hardware.org/?probe=1387bf11ea) | Nov 28, 2022 |
| Google        | Akemi                       | Notebook    | [89c466ffd4](https://linux-hardware.org/?probe=89c466ffd4) | Nov 28, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [97cf5008bb](https://linux-hardware.org/?probe=97cf5008bb) | Nov 27, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [7d6eeaf95c](https://linux-hardware.org/?probe=7d6eeaf95c) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [bc3563401b](https://linux-hardware.org/?probe=bc3563401b) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | Notebook    | [46ec8527f5](https://linux-hardware.org/?probe=46ec8527f5) | Nov 25, 2022 |
| sunxi         | LeMaker Banana Pi           | Soc         | [56f65f30b3](https://linux-hardware.org/?probe=56f65f30b3) | Nov 24, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [199ed733ad](https://linux-hardware.org/?probe=199ed733ad) | Nov 24, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [8eb4e40bf5](https://linux-hardware.org/?probe=8eb4e40bf5) | Nov 22, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [b1e3f41ed1](https://linux-hardware.org/?probe=b1e3f41ed1) | Nov 22, 2022 |
| Intel         | AB2L .A004                  | Mini pc     | [6124722e1f](https://linux-hardware.org/?probe=6124722e1f) | Nov 22, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [452417fa68](https://linux-hardware.org/?probe=452417fa68) | Nov 21, 2022 |
| Sony          | VPCEH25EN                   | Notebook    | [d9136e5b75](https://linux-hardware.org/?probe=d9136e5b75) | Nov 20, 2022 |
| HP            | 245 G8 Notebook PC          | Notebook    | [4d4f9a0e10](https://linux-hardware.org/?probe=4d4f9a0e10) | Nov 17, 2022 |
| ASUSTek       | M4A88TD-M/USB3              | Desktop     | [8ff2384625](https://linux-hardware.org/?probe=8ff2384625) | Nov 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [c9a4863d1f](https://linux-hardware.org/?probe=c9a4863d1f) | Nov 15, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [5ffe9844bd](https://linux-hardware.org/?probe=5ffe9844bd) | Nov 15, 2022 |
| HP            | 1495                        | Desktop     | [e29c423a17](https://linux-hardware.org/?probe=e29c423a17) | Nov 15, 2022 |
| HP            | ProBook 6450b               | Notebook    | [ee3a2a2ef8](https://linux-hardware.org/?probe=ee3a2a2ef8) | Nov 14, 2022 |
| HP            | Pavilion g6                 | Notebook    | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [161b81845e](https://linux-hardware.org/?probe=161b81845e) | Nov 11, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [b042e75495](https://linux-hardware.org/?probe=b042e75495) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [38f39ebccd](https://linux-hardware.org/?probe=38f39ebccd) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [d3bbc5ba4f](https://linux-hardware.org/?probe=d3bbc5ba4f) | Nov 11, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [ac93b84c08](https://linux-hardware.org/?probe=ac93b84c08) | Nov 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| Dell          | 06FW8M A03                  | Server      | [2d4eead63b](https://linux-hardware.org/?probe=2d4eead63b) | Nov 08, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [70ba1bf558](https://linux-hardware.org/?probe=70ba1bf558) | Nov 08, 2022 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [0a1efcf166](https://linux-hardware.org/?probe=0a1efcf166) | Nov 08, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [377df38ed7](https://linux-hardware.org/?probe=377df38ed7) | Nov 08, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [2796faab6c](https://linux-hardware.org/?probe=2796faab6c) | Nov 08, 2022 |
| Lenovo        | ThinkPad T440p 20AN0033R... | Notebook    | [7ca892ad44](https://linux-hardware.org/?probe=7ca892ad44) | Nov 06, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d37fe5f0b4](https://linux-hardware.org/?probe=d37fe5f0b4) | Nov 06, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [e97900160b](https://linux-hardware.org/?probe=e97900160b) | Nov 05, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [2bf5248261](https://linux-hardware.org/?probe=2bf5248261) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [f1117abc19](https://linux-hardware.org/?probe=f1117abc19) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | Desktop     | [f60040c1b7](https://linux-hardware.org/?probe=f60040c1b7) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | Desktop     | [cd87b011a0](https://linux-hardware.org/?probe=cd87b011a0) | Nov 05, 2022 |
| Lenovo        | ThinkPad P51 20HH0014IX     | Notebook    | [e519495581](https://linux-hardware.org/?probe=e519495581) | Nov 04, 2022 |
| HP            | 8054                        | Desktop     | [0f1371d133](https://linux-hardware.org/?probe=0f1371d133) | Nov 03, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [423d3158cd](https://linux-hardware.org/?probe=423d3158cd) | Nov 03, 2022 |
| Dell          | Precision M6400             | Notebook    | [b98b318067](https://linux-hardware.org/?probe=b98b318067) | Nov 02, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [65231808f8](https://linux-hardware.org/?probe=65231808f8) | Nov 02, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [37f3d75177](https://linux-hardware.org/?probe=37f3d75177) | Oct 31, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [bbea359211](https://linux-hardware.org/?probe=bbea359211) | Oct 28, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [6ebaad0374](https://linux-hardware.org/?probe=6ebaad0374) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3c65639aad](https://linux-hardware.org/?probe=3c65639aad) | Oct 25, 2022 |
| ASUSTek       | X555YI                      | Notebook    | [5d6562117a](https://linux-hardware.org/?probe=5d6562117a) | Oct 25, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [7027921568](https://linux-hardware.org/?probe=7027921568) | Oct 25, 2022 |
| Intel         | DH61AG AAG23736-507         | Desktop     | [7fa3b3bc6a](https://linux-hardware.org/?probe=7fa3b3bc6a) | Oct 25, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [d10106fb33](https://linux-hardware.org/?probe=d10106fb33) | Oct 24, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [6398e45c99](https://linux-hardware.org/?probe=6398e45c99) | Oct 24, 2022 |
| HP            | 15                          | Notebook    | [2831771472](https://linux-hardware.org/?probe=2831771472) | Oct 22, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [5f1aeaf170](https://linux-hardware.org/?probe=5f1aeaf170) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [66418dda52](https://linux-hardware.org/?probe=66418dda52) | Oct 22, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [f5b8282e1f](https://linux-hardware.org/?probe=f5b8282e1f) | Oct 21, 2022 |
| ASUSTek       | N551ZU                      | Notebook    | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | Notebook    | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| Acer          | Aspire ES1-331              | Notebook    | [f5ace96d5d](https://linux-hardware.org/?probe=f5ace96d5d) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| Itautec       | ST 4273 ST-4273 Padrao 0... | Desktop     | [8c4af1707c](https://linux-hardware.org/?probe=8c4af1707c) | Oct 17, 2022 |
| MSI           | MS-7309                     | Desktop     | [9d4f0daf60](https://linux-hardware.org/?probe=9d4f0daf60) | Oct 16, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [4f03e84827](https://linux-hardware.org/?probe=4f03e84827) | Oct 16, 2022 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [ed6ebf5f98](https://linux-hardware.org/?probe=ed6ebf5f98) | Oct 16, 2022 |
| HP            | 198E                        | Desktop     | [47439edd0e](https://linux-hardware.org/?probe=47439edd0e) | Oct 15, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [a14ced18eb](https://linux-hardware.org/?probe=a14ced18eb) | Oct 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [a098b893f4](https://linux-hardware.org/?probe=a098b893f4) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [c3513de476](https://linux-hardware.org/?probe=c3513de476) | Oct 11, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [3598f82c1e](https://linux-hardware.org/?probe=3598f82c1e) | Oct 10, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | Notebook    | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [6580d55237](https://linux-hardware.org/?probe=6580d55237) | Oct 09, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [caf9a63020](https://linux-hardware.org/?probe=caf9a63020) | Oct 08, 2022 |
| HP            | 1589                        | Desktop     | [d50afd3db1](https://linux-hardware.org/?probe=d50afd3db1) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537AF8       | Notebook    | [06dd00b171](https://linux-hardware.org/?probe=06dd00b171) | Oct 08, 2022 |
| Dell          | Latitude 5411               | Notebook    | [4bb05d639f](https://linux-hardware.org/?probe=4bb05d639f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30L0... | Notebook    | [ea6a5c970c](https://linux-hardware.org/?probe=ea6a5c970c) | Oct 07, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [b67d9b67e4](https://linux-hardware.org/?probe=b67d9b67e4) | Oct 06, 2022 |
| ASUSTek       | ET1612I                     | Desktop     | [91fea00cbf](https://linux-hardware.org/?probe=91fea00cbf) | Oct 06, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [b838d87a4b](https://linux-hardware.org/?probe=b838d87a4b) | Oct 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [0e52b51f87](https://linux-hardware.org/?probe=0e52b51f87) | Oct 05, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [dd6693ffa9](https://linux-hardware.org/?probe=dd6693ffa9) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [986b3c962e](https://linux-hardware.org/?probe=986b3c962e) | Oct 04, 2022 |
| Dell          | Precision 7560              | Notebook    | [877583cc90](https://linux-hardware.org/?probe=877583cc90) | Oct 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [10e3123558](https://linux-hardware.org/?probe=10e3123558) | Oct 03, 2022 |
| Lenovo        | B70-80 80MR                 | Notebook    | [69aec9e100](https://linux-hardware.org/?probe=69aec9e100) | Oct 01, 2022 |
| HP            | Notebook                    | Notebook    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [ddf1904011](https://linux-hardware.org/?probe=ddf1904011) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Sony          | SVE1512C6EB                 | Notebook    | [c47a3a5bd7](https://linux-hardware.org/?probe=c47a3a5bd7) | Sep 30, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | Notebook    | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| Dell          | Latitude 5420               | Notebook    | [36ddd1d6d7](https://linux-hardware.org/?probe=36ddd1d6d7) | Sep 30, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [dcdafbbd9b](https://linux-hardware.org/?probe=dcdafbbd9b) | Sep 28, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5479c35130](https://linux-hardware.org/?probe=5479c35130) | Sep 28, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [834ef0ec59](https://linux-hardware.org/?probe=834ef0ec59) | Sep 27, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [564d385b61](https://linux-hardware.org/?probe=564d385b61) | Sep 27, 2022 |
| Dell          | CS24-TY                     | Server      | [029e2bdb60](https://linux-hardware.org/?probe=029e2bdb60) | Sep 27, 2022 |
| MSI           | H170M PRO-VDH               | Desktop     | [f7254adff2](https://linux-hardware.org/?probe=f7254adff2) | Sep 25, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [c7920c2e68](https://linux-hardware.org/?probe=c7920c2e68) | Sep 24, 2022 |
| Packard Be... | EasyNote MH45               | Notebook    | [c312580997](https://linux-hardware.org/?probe=c312580997) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5588f73920](https://linux-hardware.org/?probe=5588f73920) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a83e57d8c1](https://linux-hardware.org/?probe=a83e57d8c1) | Sep 23, 2022 |
| Tactus        | GeoBook 140                 | Notebook    | [7d8700d0e1](https://linux-hardware.org/?probe=7d8700d0e1) | Sep 23, 2022 |
| Dell          | Latitude 5411               | Notebook    | [018a9c569a](https://linux-hardware.org/?probe=018a9c569a) | Sep 23, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [c3a88ed62d](https://linux-hardware.org/?probe=c3a88ed62d) | Sep 22, 2022 |
| Lenovo        | ThinkPad T61 7659AB7        | Notebook    | [aa07f9c271](https://linux-hardware.org/?probe=aa07f9c271) | Sep 20, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [966ae734c2](https://linux-hardware.org/?probe=966ae734c2) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61p 6457A24       | Notebook    | [d98e9a64bd](https://linux-hardware.org/?probe=d98e9a64bd) | Sep 20, 2022 |
| Lenovo        | ThinkPad X220 42918F6       | Notebook    | [69dda668fc](https://linux-hardware.org/?probe=69dda668fc) | Sep 18, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e2b4056812](https://linux-hardware.org/?probe=e2b4056812) | Sep 18, 2022 |
| ASRock        | 960GC-GS FX                 | Desktop     | [3e40742ff0](https://linux-hardware.org/?probe=3e40742ff0) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| ASUSTek       | ET1612I                     | Desktop     | [0ddd9554cc](https://linux-hardware.org/?probe=0ddd9554cc) | Sep 16, 2022 |
| Pine Micro... | Pine64 Rock64               | Soc         | [dbd6ac01d6](https://linux-hardware.org/?probe=dbd6ac01d6) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [588c189149](https://linux-hardware.org/?probe=588c189149) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [4b94d21772](https://linux-hardware.org/?probe=4b94d21772) | Sep 16, 2022 |
| Dell          | Latitude 7490               | Notebook    | [ce54bcd741](https://linux-hardware.org/?probe=ce54bcd741) | Sep 15, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [6d40add21a](https://linux-hardware.org/?probe=6d40add21a) | Sep 15, 2022 |
| Dell          | Latitude 7420               | Convertible | [5d119f6255](https://linux-hardware.org/?probe=5d119f6255) | Sep 14, 2022 |
| Dell          | 0DR845                      | Desktop     | [158b3832bc](https://linux-hardware.org/?probe=158b3832bc) | Sep 13, 2022 |
| Dell          | Precision 5540              | Notebook    | [229337f709](https://linux-hardware.org/?probe=229337f709) | Sep 13, 2022 |
| ASUSTek       | K30BD                       | Desktop     | [d6daf0e1f8](https://linux-hardware.org/?probe=d6daf0e1f8) | Sep 13, 2022 |
| ASUSTek       | H61M-C                      | Desktop     | [bb07dfab63](https://linux-hardware.org/?probe=bb07dfab63) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [e59aa2e1d5](https://linux-hardware.org/?probe=e59aa2e1d5) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [930da2e105](https://linux-hardware.org/?probe=930da2e105) | Sep 13, 2022 |
| Dell          | 0DR845                      | Desktop     | [f65bf44380](https://linux-hardware.org/?probe=f65bf44380) | Sep 13, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3f56f510f8](https://linux-hardware.org/?probe=3f56f510f8) | Sep 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [940507a1ec](https://linux-hardware.org/?probe=940507a1ec) | Sep 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7b7a1cfeb9](https://linux-hardware.org/?probe=7b7a1cfeb9) | Sep 11, 2022 |
| Dell          | 03NVJ6 A01                  | Desktop     | [3f51b6da48](https://linux-hardware.org/?probe=3f51b6da48) | Sep 10, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [bf1aba4ebe](https://linux-hardware.org/?probe=bf1aba4ebe) | Sep 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [31a50780b4](https://linux-hardware.org/?probe=31a50780b4) | Sep 08, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [b0412cee20](https://linux-hardware.org/?probe=b0412cee20) | Sep 07, 2022 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [7649a53341](https://linux-hardware.org/?probe=7649a53341) | Sep 06, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [989e0d5d57](https://linux-hardware.org/?probe=989e0d5d57) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [f51b1f139e](https://linux-hardware.org/?probe=f51b1f139e) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | Notebook    | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [dd775ffe8f](https://linux-hardware.org/?probe=dd775ffe8f) | Sep 05, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [668995f3ff](https://linux-hardware.org/?probe=668995f3ff) | Sep 04, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [1bd6f2ba6f](https://linux-hardware.org/?probe=1bd6f2ba6f) | Sep 04, 2022 |
| Google        | Kip                         | Notebook    | [e92d971d5e](https://linux-hardware.org/?probe=e92d971d5e) | Sep 04, 2022 |
| ASUSTek       | K30BD                       | Desktop     | [6042bda5d7](https://linux-hardware.org/?probe=6042bda5d7) | Sep 03, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Google        | Reks                        | Notebook    | [d88eecb32d](https://linux-hardware.org/?probe=d88eecb32d) | Sep 03, 2022 |
| Clientron     | C800                        | Mini pc     | [18fcb4170b](https://linux-hardware.org/?probe=18fcb4170b) | Sep 03, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [506f9da93b](https://linux-hardware.org/?probe=506f9da93b) | Sep 03, 2022 |
| HP            | 8433 11                     | Desktop     | [00868f25c6](https://linux-hardware.org/?probe=00868f25c6) | Aug 31, 2022 |
| sunxi         | Allwinner sun7i (A20) Fa... | Soc         | [632a8a0ad8](https://linux-hardware.org/?probe=632a8a0ad8) | Aug 30, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [9bdae9239f](https://linux-hardware.org/?probe=9bdae9239f) | Aug 29, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [e692fe97cb](https://linux-hardware.org/?probe=e692fe97cb) | Aug 28, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [b9953ab67e](https://linux-hardware.org/?probe=b9953ab67e) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [f725a87544](https://linux-hardware.org/?probe=f725a87544) | Aug 27, 2022 |
| Lenovo        | 14w 81MQ000JUS              | Notebook    | [d71f12bede](https://linux-hardware.org/?probe=d71f12bede) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [8a689fc0fd](https://linux-hardware.org/?probe=8a689fc0fd) | Aug 27, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [7bf3626764](https://linux-hardware.org/?probe=7bf3626764) | Aug 25, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [5bb7561235](https://linux-hardware.org/?probe=5bb7561235) | Aug 25, 2022 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | Notebook    | [d269aaa456](https://linux-hardware.org/?probe=d269aaa456) | Aug 25, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [c37bc2a345](https://linux-hardware.org/?probe=c37bc2a345) | Aug 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [92be7f3368](https://linux-hardware.org/?probe=92be7f3368) | Aug 24, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [5652f2c73d](https://linux-hardware.org/?probe=5652f2c73d) | Aug 24, 2022 |
| Lenovo        | 14w 81MQ000JUS              | Notebook    | [1ff769c6ef](https://linux-hardware.org/?probe=1ff769c6ef) | Aug 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5dabf74b7f](https://linux-hardware.org/?probe=5dabf74b7f) | Aug 21, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [ed1f055157](https://linux-hardware.org/?probe=ed1f055157) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [764eaea2ba](https://linux-hardware.org/?probe=764eaea2ba) | Aug 19, 2022 |
| eMachines     | ET1350                      | Desktop     | [96e9f7aba7](https://linux-hardware.org/?probe=96e9f7aba7) | Aug 18, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [015ccc4b06](https://linux-hardware.org/?probe=015ccc4b06) | Aug 18, 2022 |
| HP            | 8591                        | Desktop     | [4235eb97c1](https://linux-hardware.org/?probe=4235eb97c1) | Aug 18, 2022 |
| Dell          | 0YXT71 A00                  | Desktop     | [def7e10c65](https://linux-hardware.org/?probe=def7e10c65) | Aug 17, 2022 |
| ASUSTek       | K53TA                       | Notebook    | [db6525efb3](https://linux-hardware.org/?probe=db6525efb3) | Aug 15, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [b98fcab3a6](https://linux-hardware.org/?probe=b98fcab3a6) | Aug 15, 2022 |
| Lenovo        | ThinkPad T460s 20FAS0Q90... | Notebook    | [644c7518e9](https://linux-hardware.org/?probe=644c7518e9) | Aug 14, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [fd06db829d](https://linux-hardware.org/?probe=fd06db829d) | Aug 14, 2022 |
| Toshiba       | PT10F                       | Notebook    | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [5bb07e1a28](https://linux-hardware.org/?probe=5bb07e1a28) | Aug 11, 2022 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [0fadd2421f](https://linux-hardware.org/?probe=0fadd2421f) | Aug 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6JY0... | Notebook    | [7d85d4f00b](https://linux-hardware.org/?probe=7d85d4f00b) | Aug 06, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [8b0237ee5e](https://linux-hardware.org/?probe=8b0237ee5e) | Aug 03, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | Notebook    | [fdd30ffa23](https://linux-hardware.org/?probe=fdd30ffa23) | Aug 03, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [4b8ed45c90](https://linux-hardware.org/?probe=4b8ed45c90) | Aug 03, 2022 |
| GMKtec        | NucBox5                     | Notebook    | [5023bc1773](https://linux-hardware.org/?probe=5023bc1773) | Aug 02, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [745f6815cb](https://linux-hardware.org/?probe=745f6815cb) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [01bcafef3c](https://linux-hardware.org/?probe=01bcafef3c) | Jul 30, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9a97caa028](https://linux-hardware.org/?probe=9a97caa028) | Jul 28, 2022 |
| Schenker      | WORK (Early 2021)           | Notebook    | [8666cc396a](https://linux-hardware.org/?probe=8666cc396a) | Jul 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d00325cd68](https://linux-hardware.org/?probe=d00325cd68) | Jul 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [da54317b9a](https://linux-hardware.org/?probe=da54317b9a) | Jul 27, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c380d02bbf](https://linux-hardware.org/?probe=c380d02bbf) | Jul 25, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [a27a0707b8](https://linux-hardware.org/?probe=a27a0707b8) | Jul 25, 2022 |
| PCWare        | IPX1800E2                   | Desktop     | [4426727633](https://linux-hardware.org/?probe=4426727633) | Jul 24, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [ba0058e96e](https://linux-hardware.org/?probe=ba0058e96e) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [75b4088788](https://linux-hardware.org/?probe=75b4088788) | Jul 20, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [5889a04334](https://linux-hardware.org/?probe=5889a04334) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [3c2afd2b5e](https://linux-hardware.org/?probe=3c2afd2b5e) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| Dell          | 0PM2CW A04                  | Server      | [8162a1a915](https://linux-hardware.org/?probe=8162a1a915) | Jul 17, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d5a64d7baa](https://linux-hardware.org/?probe=d5a64d7baa) | Jul 16, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [13d38a6632](https://linux-hardware.org/?probe=13d38a6632) | Jul 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [a6ae556389](https://linux-hardware.org/?probe=a6ae556389) | Jul 16, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [da05c4539d](https://linux-hardware.org/?probe=da05c4539d) | Jul 11, 2022 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [f2f3db370a](https://linux-hardware.org/?probe=f2f3db370a) | Jul 10, 2022 |
| MSI           | A320M PRO-E                 | Desktop     | [d16a812a12](https://linux-hardware.org/?probe=d16a812a12) | Jul 10, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [7becd2f2df](https://linux-hardware.org/?probe=7becd2f2df) | Jul 10, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [51b138f349](https://linux-hardware.org/?probe=51b138f349) | Jul 04, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [2f915d68e5](https://linux-hardware.org/?probe=2f915d68e5) | Jul 04, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [7b470f27d3](https://linux-hardware.org/?probe=7b470f27d3) | Jul 03, 2022 |
| Samsung       | 370E4K                      | Notebook    | [a6512c1606](https://linux-hardware.org/?probe=a6512c1606) | Jul 03, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [d48eb55102](https://linux-hardware.org/?probe=d48eb55102) | Jul 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [9ce5b9c45c](https://linux-hardware.org/?probe=9ce5b9c45c) | Jun 30, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [f532d90f38](https://linux-hardware.org/?probe=f532d90f38) | Jun 29, 2022 |
| Standard      | Unknown                     | Notebook    | [1a94acbc05](https://linux-hardware.org/?probe=1a94acbc05) | Jun 29, 2022 |
| Supermicro    | X10SRA                      | Server      | [4646cb2fae](https://linux-hardware.org/?probe=4646cb2fae) | Jun 27, 2022 |
| Standard      | Unknown                     | Notebook    | [93ac825a25](https://linux-hardware.org/?probe=93ac825a25) | Jun 27, 2022 |
| HP            | Pavilion dv5                | Notebook    | [4009a4fd8c](https://linux-hardware.org/?probe=4009a4fd8c) | Jun 24, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [db4763808b](https://linux-hardware.org/?probe=db4763808b) | Jun 22, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [ded5eaba87](https://linux-hardware.org/?probe=ded5eaba87) | Jun 19, 2022 |
| Google        | Kindred                     | Notebook    | [c12b15c596](https://linux-hardware.org/?probe=c12b15c596) | Jun 17, 2022 |
| Medion        | E2221T MD60684              | Convertible | [559733f94d](https://linux-hardware.org/?probe=559733f94d) | Jun 16, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [f41d413820](https://linux-hardware.org/?probe=f41d413820) | Jun 13, 2022 |
| GPU Compan... | GWTN141-4                   | Notebook    | [ba579cb383](https://linux-hardware.org/?probe=ba579cb383) | Jun 11, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [824dc8a1c9](https://linux-hardware.org/?probe=824dc8a1c9) | Jun 11, 2022 |
| Dell          | Latitude 7280               | Notebook    | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [77a5e1c6f9](https://linux-hardware.org/?probe=77a5e1c6f9) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [33dbe3e5db](https://linux-hardware.org/?probe=33dbe3e5db) | Jun 08, 2022 |
| AMI           | Intel                       | Notebook    | [79b1f29bc4](https://linux-hardware.org/?probe=79b1f29bc4) | Jun 07, 2022 |
| AMI           | Intel                       | Notebook    | [d7746ec6d5](https://linux-hardware.org/?probe=d7746ec6d5) | Jun 07, 2022 |
| Digma         | EVE 15 C413 ES5059EW        | Notebook    | [26eb7d39e1](https://linux-hardware.org/?probe=26eb7d39e1) | Jun 06, 2022 |
| HP            | Pavilion g7                 | Notebook    | [b31de17368](https://linux-hardware.org/?probe=b31de17368) | Jun 06, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| Dell          | Latitude D820               | Notebook    | [8c2336469f](https://linux-hardware.org/?probe=8c2336469f) | Jun 01, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [db6d025d69](https://linux-hardware.org/?probe=db6d025d69) | Jun 01, 2022 |
| LG Electro... | 22V280 FAB1                 | All in one  | [d61829e715](https://linux-hardware.org/?probe=d61829e715) | May 26, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [496399846f](https://linux-hardware.org/?probe=496399846f) | May 26, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [2c541b20f6](https://linux-hardware.org/?probe=2c541b20f6) | May 26, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [aa8d9cb3b9](https://linux-hardware.org/?probe=aa8d9cb3b9) | May 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [a22a5ebbff](https://linux-hardware.org/?probe=a22a5ebbff) | May 25, 2022 |
| HP            | Mini 5103                   | Notebook    | [aa7f4e957e](https://linux-hardware.org/?probe=aa7f4e957e) | May 23, 2022 |
| ASUSTek       | X99-A II                    | Desktop     | [288a6b3b20](https://linux-hardware.org/?probe=288a6b3b20) | May 23, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [3e34ce179d](https://linux-hardware.org/?probe=3e34ce179d) | May 22, 2022 |
| Google        | Snappy                      | Notebook    | [c88d27b24a](https://linux-hardware.org/?probe=c88d27b24a) | May 20, 2022 |
| Google        | Snappy                      | Notebook    | [9fc85cd49a](https://linux-hardware.org/?probe=9fc85cd49a) | May 20, 2022 |
| Google        | Snappy                      | Notebook    | [cb9e7730ad](https://linux-hardware.org/?probe=cb9e7730ad) | May 20, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [ee3726a591](https://linux-hardware.org/?probe=ee3726a591) | May 19, 2022 |
| Lenovo        | ThinkPad E580 20KS001JGE    | Notebook    | [724c06c08c](https://linux-hardware.org/?probe=724c06c08c) | May 19, 2022 |
| ASUSTek       | UL30A                       | Notebook    | [c121dd37ba](https://linux-hardware.org/?probe=c121dd37ba) | May 16, 2022 |
| Google        | Droid                       | Notebook    | [e938864c93](https://linux-hardware.org/?probe=e938864c93) | May 15, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [6f58937bed](https://linux-hardware.org/?probe=6f58937bed) | May 13, 2022 |
| Unknown       | Unknown                     | Notebook    | [f802e84b8e](https://linux-hardware.org/?probe=f802e84b8e) | May 08, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [bd94a8145a](https://linux-hardware.org/?probe=bd94a8145a) | May 08, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [a8a1e1e3a2](https://linux-hardware.org/?probe=a8a1e1e3a2) | May 07, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [e7ad5ed098](https://linux-hardware.org/?probe=e7ad5ed098) | May 06, 2022 |
| Dell          | Latitude 7420               | Notebook    | [384325350c](https://linux-hardware.org/?probe=384325350c) | May 05, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [795d9af5a7](https://linux-hardware.org/?probe=795d9af5a7) | May 05, 2022 |
| Acer          | Veriton M490G               | Desktop     | [f55983d536](https://linux-hardware.org/?probe=f55983d536) | May 04, 2022 |
| Dell          | XPS M1530                   | Notebook    | [760cae00c1](https://linux-hardware.org/?probe=760cae00c1) | May 03, 2022 |
| ASRock        | P55 Pro                     | Desktop     | [e626676348](https://linux-hardware.org/?probe=e626676348) | May 02, 2022 |
| Dell          | XPS M1530                   | Notebook    | [757d1b099e](https://linux-hardware.org/?probe=757d1b099e) | Apr 30, 2022 |
| ASUSTek       | T100HAN                     | Notebook    | [5ee200cfbe](https://linux-hardware.org/?probe=5ee200cfbe) | Apr 30, 2022 |
| HP            | 09F8h                       | Desktop     | [8605181df9](https://linux-hardware.org/?probe=8605181df9) | Apr 26, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [f0ed67e309](https://linux-hardware.org/?probe=f0ed67e309) | Apr 26, 2022 |
| Supermicro    | X11SPL-F                    | Server      | [34f6e28125](https://linux-hardware.org/?probe=34f6e28125) | Apr 26, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [bd286b124a](https://linux-hardware.org/?probe=bd286b124a) | Apr 25, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c16cb4e0d6](https://linux-hardware.org/?probe=c16cb4e0d6) | Apr 24, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | Notebook    | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [d88db86125](https://linux-hardware.org/?probe=d88db86125) | Apr 20, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [b073554afc](https://linux-hardware.org/?probe=b073554afc) | Apr 08, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [c3dcb61dd5](https://linux-hardware.org/?probe=c3dcb61dd5) | Apr 02, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [6098716d3e](https://linux-hardware.org/?probe=6098716d3e) | Mar 30, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Xubuntu_22.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.15.0-56-generic    | 44        | 9.65%   |
| 5.15.0-52-generic    | 35        | 7.68%   |
| 5.15.0-47-generic    | 31        | 6.8%    |
| 5.15.0-58-generic    | 27        | 5.92%   |
| 5.15.0-48-generic    | 25        | 5.48%   |
| 5.15.0-60-generic    | 22        | 4.82%   |
| 5.15.0-67-generic    | 20        | 4.39%   |
| 5.15.0-25-generic    | 20        | 4.39%   |
| 5.15.0-46-generic    | 17        | 3.73%   |
| 5.15.0-53-generic    | 14        | 3.07%   |
| 5.15.0-27-generic    | 14        | 3.07%   |
| 5.19.0-35-generic    | 13        | 2.85%   |
| 5.19.0-38-generic    | 10        | 2.19%   |
| 5.15.0-69-generic    | 10        | 2.19%   |
| 5.15.0-57-generic    | 10        | 2.19%   |
| 5.15.0-50-generic    | 9         | 1.97%   |
| 5.15.0-43-generic    | 9         | 1.97%   |
| 5.15.0-41-generic    | 9         | 1.97%   |
| 5.15.0-40-generic    | 9         | 1.97%   |
| 5.15.0-70-generic    | 7         | 1.54%   |
| 5.19.0-32-generic    | 6         | 1.32%   |
| 5.15.0-39-generic    | 6         | 1.32%   |
| 5.15.0-37-generic    | 5         | 1.1%    |
| 5.15.0-35-generic    | 5         | 1.1%    |
| 5.15.0-33-generic    | 4         | 0.88%   |
| 5.15.0-30-generic    | 4         | 0.88%   |
| 5.19.0-41-generic    | 3         | 0.66%   |
| 5.17.0-1020-oem      | 3         | 0.66%   |
| 6.1.0-1006-oem       | 2         | 0.44%   |
| 5.17.0-1013-oem      | 2         | 0.44%   |
| 5.15.0-60-lowlatency | 2         | 0.44%   |
| 5.15.0-54-generic    | 2         | 0.44%   |
| 5.15.0-50-lowlatency | 2         | 0.44%   |
| 5.15.0-48-lowlatency | 2         | 0.44%   |
| 5.15.0-46-lowlatency | 2         | 0.44%   |
| 6.2.9-060209-generic | 1         | 0.22%   |
| 6.2.7-060207-generic | 1         | 0.22%   |
| 6.2.2-060202-generic | 1         | 0.22%   |
| 6.1.6-060106-generic | 1         | 0.22%   |
| 6.1.10.mmn           | 1         | 0.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.0   | 352       | 81.11%  |
| 5.19.0   | 37        | 8.53%   |
| 5.17.0   | 11        | 2.53%   |
| 6.1.0    | 4         | 0.92%   |
| 6.0.0    | 2         | 0.46%   |
| 5.4.0    | 2         | 0.46%   |
| 5.18.0   | 2         | 0.46%   |
| 5.15.93  | 2         | 0.46%   |
| 6.2.9    | 1         | 0.23%   |
| 6.2.7    | 1         | 0.23%   |
| 6.2.2    | 1         | 0.23%   |
| 6.1.6    | 1         | 0.23%   |
| 6.1.10   | 1         | 0.23%   |
| 6.0.9    | 1         | 0.23%   |
| 6.0.7    | 1         | 0.23%   |
| 5.19.5   | 1         | 0.23%   |
| 5.19.13  | 1         | 0.23%   |
| 5.19.1   | 1         | 0.23%   |
| 5.18.12  | 1         | 0.23%   |
| 5.17.3   | 1         | 0.23%   |
| 5.16.9   | 1         | 0.23%   |
| 5.15.89  | 1         | 0.23%   |
| 5.15.74  | 1         | 0.23%   |
| 5.15.68  | 1         | 0.23%   |
| 5.15.61  | 1         | 0.23%   |
| 5.15.59  | 1         | 0.23%   |
| 5.15.48  | 1         | 0.23%   |
| 5.15.23  | 1         | 0.23%   |
| 5.10.110 | 1         | 0.23%   |
| 4.19.241 | 1         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 361       | 83.18%  |
| 5.19    | 40        | 9.22%   |
| 5.17    | 12        | 2.76%   |
| 6.1     | 6         | 1.38%   |
| 6.0     | 4         | 0.92%   |
| 6.2     | 3         | 0.69%   |
| 5.18    | 3         | 0.69%   |
| 5.4     | 2         | 0.46%   |
| 5.16    | 1         | 0.23%   |
| 5.10    | 1         | 0.23%   |
| 4.19    | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 421       | 97.68%  |
| aarch64 | 7         | 1.62%   |
| armv7l  | 3         | 0.7%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 417       | 96.75%  |
| GNOME           | 11        | 2.55%   |
| KDE5            | 1         | 0.23%   |
| i3              | 1         | 0.23%   |
| GNOME Flashback | 1         | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 416       | 96.07%  |
| Tty     | 10        | 2.31%   |
| Wayland | 7         | 1.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 376       | 87.24%  |
| Unknown | 25        | 5.8%    |
| GDM3    | 23        | 5.34%   |
| SDDM    | 4         | 0.93%   |
| SLiM    | 2         | 0.46%   |
| GDM     | 1         | 0.23%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 173       | 40.14%  |
| de_DE | 58        | 13.46%  |
| fr_FR | 47        | 10.9%   |
| it_IT | 26        | 6.03%   |
| en_GB | 16        | 3.71%   |
| pt_BR | 15        | 3.48%   |
| ru_RU | 13        | 3.02%   |
| en_CA | 11        | 2.55%   |
| es_ES | 7         | 1.62%   |
| cs_CZ | 6         | 1.39%   |
| nl_NL | 5         | 1.16%   |
| en_AU | 5         | 1.16%   |
| en_IN | 4         | 0.93%   |
| C     | 4         | 0.93%   |
| tr_TR | 3         | 0.7%    |
| ja_JP | 3         | 0.7%    |
| hu_HU | 3         | 0.7%    |
| ru_UA | 2         | 0.46%   |
| pl_PL | 2         | 0.46%   |
| fr_BE | 2         | 0.46%   |
| es_VE | 2         | 0.46%   |
| es_MX | 2         | 0.46%   |
| es_CO | 2         | 0.46%   |
| es_AR | 2         | 0.46%   |
| de_CH | 2         | 0.46%   |
| zh_CN | 1         | 0.23%   |
| sv_SE | 1         | 0.23%   |
| ro_RO | 1         | 0.23%   |
| pt_PT | 1         | 0.23%   |
| nl_BE | 1         | 0.23%   |
| ko_KR | 1         | 0.23%   |
| fr_CH | 1         | 0.23%   |
| fr_CA | 1         | 0.23%   |
| fi_FI | 1         | 0.23%   |
| es_CL | 1         | 0.23%   |
| en_ZA | 1         | 0.23%   |
| en_IL | 1         | 0.23%   |
| en_IE | 1         | 0.23%   |
| el_GR | 1         | 0.23%   |
| bg_BG | 1         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 223       | 51.38%  |
| BIOS | 211       | 48.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 387       | 89.58%  |
| Overlay | 16        | 3.7%    |
| Btrfs   | 12        | 2.78%   |
| Zfs     | 11        | 2.55%   |
| Tmpfs   | 5         | 1.16%   |
| Ext3    | 1         | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 297       | 67.35%  |
| MBR     | 72        | 16.33%  |
| Unknown | 72        | 16.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 374       | 85.98%  |
| Yes       | 61        | 14.02%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 301       | 69.52%  |
| Yes       | 132       | 30.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 67        | 15.55%  |
| Hewlett-Packard         | 65        | 15.08%  |
| ASUSTek Computer        | 62        | 14.39%  |
| Dell                    | 45        | 10.44%  |
| MSI                     | 27        | 6.26%   |
| Acer                    | 27        | 6.26%   |
| Gigabyte Technology     | 25        | 5.8%    |
| ASRock                  | 12        | 2.78%   |
| Google                  | 8         | 1.86%   |
| Apple                   | 8         | 1.86%   |
| Toshiba                 | 7         | 1.62%   |
| Intel                   | 5         | 1.16%   |
| Supermicro              | 4         | 0.93%   |
| Sony                    | 4         | 0.93%   |
| GPU Company             | 4         | 0.93%   |
| Unknown                 | 4         | 0.93%   |
| Rockchip                | 3         | 0.7%    |
| Medion                  | 3         | 0.7%    |
| HUAWEI                  | 3         | 0.7%    |
| sunxi                   | 2         | 0.46%   |
| Samsung Electronics     | 2         | 0.46%   |
| Radxa                   | 2         | 0.46%   |
| PCWare                  | 2         | 0.46%   |
| Packard Bell            | 2         | 0.46%   |
| Notebook                | 2         | 0.46%   |
| HONOR                   | 2         | 0.46%   |
| Fujitsu                 | 2         | 0.46%   |
| Foxconn                 | 2         | 0.46%   |
| Xunlong                 | 1         | 0.23%   |
| VIT                     | 1         | 0.23%   |
| Tactus                  | 1         | 0.23%   |
| Standard                | 1         | 0.23%   |
| SGIN                    | 1         | 0.23%   |
| Schenker                | 1         | 0.23%   |
| Raspberry Pi Foundation | 1         | 0.23%   |
| Pine Microsystems       | 1         | 0.23%   |
| Panasonic               | 1         | 0.23%   |
| OEM                     | 1         | 0.23%   |
| Nuvision                | 1         | 0.23%   |
| MiPi PC                 | 1         | 0.23%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 6         | 1.39%   |
| HP EliteBook 840 G3                      | 4         | 0.93%   |
| ASUS All Series                          | 4         | 0.93%   |
| MSI MS-7D43                              | 3         | 0.7%    |
| Dell OptiPlex 7010                       | 3         | 0.7%    |
| Rockchip RK3318 BOX                      | 2         | 0.46%   |
| MSI MS-7D46                              | 2         | 0.46%   |
| MSI MS-7D25                              | 2         | 0.46%   |
| MSI MS-7C52                              | 2         | 0.46%   |
| MSI MS-7817                              | 2         | 0.46%   |
| HP Pavilion Notebook                     | 2         | 0.46%   |
| HP Pavilion g6                           | 2         | 0.46%   |
| HP Pavilion 15                           | 2         | 0.46%   |
| HP Laptop 15s-fq2xxx                     | 2         | 0.46%   |
| HP 255 G8 Notebook PC                    | 2         | 0.46%   |
| GPU Company GWTN116-3                    | 2         | 0.46%   |
| Dell Latitude E5450                      | 2         | 0.46%   |
| Dell Latitude 7420                       | 2         | 0.46%   |
| ASUS K30AD_M31AD_M51AD                   | 2         | 0.46%   |
| ASUS ASUS TUF Gaming A15 FA507RE_FA507RE | 2         | 0.46%   |
| Apple MacBookPro8,1                      | 2         | 0.46%   |
| Acer Switch SW312-31                     | 2         | 0.46%   |
| Xunlong Orange Pi PC Plus                | 1         | 0.23%   |
| VIT Aptio CRB                            | 1         | 0.23%   |
| Toshiba Satellite Pro R50-C              | 1         | 0.23%   |
| Toshiba Satellite Pro R50-B              | 1         | 0.23%   |
| Toshiba Satellite L750D                  | 1         | 0.23%   |
| Toshiba Satellite C650                   | 1         | 0.23%   |
| Toshiba Satellite C55D-B                 | 1         | 0.23%   |
| Toshiba PT10F                            | 1         | 0.23%   |
| Toshiba EQUIUM P200                      | 1         | 0.23%   |
| Tactus GeoBook 140                       | 1         | 0.23%   |
| Supermicro X10SRA                        | 1         | 0.23%   |
| Supermicro Super Server                  | 1         | 0.23%   |
| Supermicro M12SWA-TF                     | 1         | 0.23%   |
| Supermicro AS -5014A-TT                  | 1         | 0.23%   |
| sunxi LeMaker Banana Pi                  | 1         | 0.23%   |
| sunxi Allwinner sun7i (A20) Family       | 1         | 0.23%   |
| Sony VPCS12V9E                           | 1         | 0.23%   |
| Sony VPCEH25EN                           | 1         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 36        | 8.35%   |
| Acer Aspire           | 17        | 3.94%   |
| HP Pavilion           | 15        | 3.48%   |
| Dell Latitude         | 13        | 3.02%   |
| HP EliteBook          | 10        | 2.32%   |
| Dell OptiPlex         | 9         | 2.09%   |
| ASUS PRIME            | 9         | 2.09%   |
| Lenovo IdeaPad        | 8         | 1.86%   |
| HP Compaq             | 7         | 1.62%   |
| Dell Inspiron         | 7         | 1.62%   |
| Lenovo ThinkCentre    | 6         | 1.39%   |
| HP Laptop             | 6         | 1.39%   |
| Unknown               | 6         | 1.39%   |
| Toshiba Satellite     | 5         | 1.16%   |
| Dell XPS              | 5         | 1.16%   |
| ASUS VivoBook         | 5         | 1.16%   |
| ASUS ROG              | 4         | 0.93%   |
| ASUS All              | 4         | 0.93%   |
| MSI MS-7D43           | 3         | 0.7%    |
| HP ProBook            | 3         | 0.7%    |
| HP EliteDesk          | 3         | 0.7%    |
| HP 255                | 3         | 0.7%    |
| Dell Precision        | 3         | 0.7%    |
| Dell PowerEdge        | 3         | 0.7%    |
| ASUS TUF              | 3         | 0.7%    |
| ASUS ASUS             | 3         | 0.7%    |
| Acer Veriton          | 3         | 0.7%    |
| Rockchip RK3318       | 2         | 0.46%   |
| Radxa ROCK            | 2         | 0.46%   |
| MSI MS-7D46           | 2         | 0.46%   |
| MSI MS-7D25           | 2         | 0.46%   |
| MSI MS-7C52           | 2         | 0.46%   |
| MSI MS-7817           | 2         | 0.46%   |
| Lenovo Yoga           | 2         | 0.46%   |
| Lenovo ThinkBook      | 2         | 0.46%   |
| HP Stream             | 2         | 0.46%   |
| HP 250                | 2         | 0.46%   |
| GPU Company GWTN116-3 | 2         | 0.46%   |
| Gigabyte B550         | 2         | 0.46%   |
| ASUS ZenBook          | 2         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 40        | 9.28%   |
| 2020    | 37        | 8.58%   |
| 2014    | 34        | 7.89%   |
| 2018    | 31        | 7.19%   |
| 2017    | 30        | 6.96%   |
| 2016    | 28        | 6.5%    |
| 2022    | 27        | 6.26%   |
| 2013    | 27        | 6.26%   |
| 2012    | 26        | 6.03%   |
| 2011    | 26        | 6.03%   |
| 2015    | 23        | 5.34%   |
| 2019    | 22        | 5.1%    |
| 2010    | 22        | 5.1%    |
| 2009    | 17        | 3.94%   |
| 2007    | 14        | 3.25%   |
| 2008    | 10        | 2.32%   |
| Unknown | 10        | 2.32%   |
| 2006    | 3         | 0.7%    |
| 2023    | 2         | 0.46%   |
| 2005    | 2         | 0.46%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 238       | 55.22%  |
| Desktop        | 148       | 34.34%  |
| System on chip | 10        | 2.32%   |
| Mini pc        | 8         | 1.86%   |
| All in one     | 8         | 1.86%   |
| Server         | 8         | 1.86%   |
| Convertible    | 7         | 1.62%   |
| Tablet         | 4         | 0.93%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 397       | 92.11%  |
| Enabled  | 34        | 7.89%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 423       | 98.14%  |
| Yes  | 8         | 1.86%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 111       | 25.69%  |
| 4.01-8.0        | 106       | 24.54%  |
| 16.01-24.0      | 73        | 16.9%   |
| 8.01-16.0       | 55        | 12.73%  |
| 32.01-64.0      | 35        | 8.1%    |
| 1.01-2.0        | 20        | 4.63%   |
| 64.01-256.0     | 11        | 2.55%   |
| 24.01-32.0      | 9         | 2.08%   |
| 2.01-3.0        | 7         | 1.62%   |
| 0.51-1.0        | 4         | 0.93%   |
| More than 256.0 | 1         | 0.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 188       | 41.96%  |
| 2.01-3.0   | 114       | 25.45%  |
| 3.01-4.0   | 47        | 10.49%  |
| 4.01-8.0   | 43        | 9.6%    |
| 0.51-1.0   | 33        | 7.37%   |
| 8.01-16.0  | 18        | 4.02%   |
| 0.01-0.5   | 3         | 0.67%   |
| 24.01-32.0 | 1         | 0.22%   |
| 16.01-24.0 | 1         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 265       | 60.92%  |
| 2      | 106       | 24.37%  |
| 3      | 31        | 7.13%   |
| 4      | 17        | 3.91%   |
| 5      | 6         | 1.38%   |
| 6      | 4         | 0.92%   |
| 7      | 2         | 0.46%   |
| 0      | 2         | 0.46%   |
| 10     | 1         | 0.23%   |
| 9      | 1         | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 258       | 59.72%  |
| Yes       | 174       | 40.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 358       | 83.06%  |
| No        | 73        | 16.94%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 320       | 74.07%  |
| No        | 112       | 25.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 251       | 58.24%  |
| No        | 180       | 41.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 72        | 16.63%  |
| Germany     | 70        | 16.17%  |
| France      | 52        | 12.01%  |
| Italy       | 30        | 6.93%   |
| Brazil      | 17        | 3.93%   |
| Russia      | 16        | 3.7%    |
| UK          | 14        | 3.23%   |
| Netherlands | 12        | 2.77%   |
| Canada      | 12        | 2.77%   |
| Poland      | 9         | 2.08%   |
| Sweden      | 8         | 1.85%   |
| Czechia     | 8         | 1.85%   |
| Spain       | 7         | 1.62%   |
| Mexico      | 7         | 1.62%   |
| India       | 7         | 1.62%   |
| Belgium     | 6         | 1.39%   |
| Switzerland | 5         | 1.15%   |
| Australia   | 5         | 1.15%   |
| Argentina   | 5         | 1.15%   |
| Turkey      | 4         | 0.92%   |
| Iran        | 4         | 0.92%   |
| Colombia    | 4         | 0.92%   |
| Belarus     | 4         | 0.92%   |
| Venezuela   | 3         | 0.69%   |
| Portugal    | 3         | 0.69%   |
| Malaysia    | 3         | 0.69%   |
| Japan       | 3         | 0.69%   |
| Indonesia   | 3         | 0.69%   |
| Hungary     | 3         | 0.69%   |
| Greece      | 3         | 0.69%   |
| Austria     | 3         | 0.69%   |
| Taiwan      | 2         | 0.46%   |
| Slovenia    | 2         | 0.46%   |
| Romania     | 2         | 0.46%   |
| Norway      | 2         | 0.46%   |
| Israel      | 2         | 0.46%   |
| Finland     | 2         | 0.46%   |
| China       | 2         | 0.46%   |
| Bulgaria    | 2         | 0.46%   |
| Vietnam     | 1         | 0.23%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Paris            | 9         | 2.02%   |
| Munich           | 7         | 1.57%   |
| Berlin           | 6         | 1.35%   |
| Stuttgart        | 5         | 1.12%   |
| Milan            | 5         | 1.12%   |
| Melbourne        | 5         | 1.12%   |
| Hamburg          | 4         | 0.9%    |
| Warsaw           | 3         | 0.67%   |
| Uppsala          | 3         | 0.67%   |
| North Hills      | 3         | 0.67%   |
| Moscow           | 3         | 0.67%   |
| Kuala Lumpur     | 3         | 0.67%   |
| Hanover          | 3         | 0.67%   |
| Biella           | 3         | 0.67%   |
| Ankara           | 3         | 0.67%   |
| Witten           | 2         | 0.45%   |
| Washington       | 2         | 0.45%   |
| Västerås       | 2         | 0.45%   |
| Toronto          | 2         | 0.45%   |
| Tehran           | 2         | 0.45%   |
| St Petersburg    | 2         | 0.45%   |
| Springfield      | 2         | 0.45%   |
| Santiago de Cali | 2         | 0.45%   |
| Rochester        | 2         | 0.45%   |
| Rio de Janeiro   | 2         | 0.45%   |
| Puebla City      | 2         | 0.45%   |
| Pilsen           | 2         | 0.45%   |
| Olathe           | 2         | 0.45%   |
| Oklahoma City    | 2         | 0.45%   |
| Oberhausen       | 2         | 0.45%   |
| Mumbai           | 2         | 0.45%   |
| Minsk            | 2         | 0.45%   |
| Mexico City      | 2         | 0.45%   |
| Lincoln          | 2         | 0.45%   |
| Liège           | 2         | 0.45%   |
| Leipzig          | 2         | 0.45%   |
| Lavras           | 2         | 0.45%   |
| Kazan’         | 2         | 0.45%   |
| Jakarta          | 2         | 0.45%   |
| Indianapolis     | 2         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 95        | 115    | 15.27%  |
| WDC                         | 87        | 120    | 13.99%  |
| Seagate                     | 71        | 91     | 11.41%  |
| Unknown                     | 46        | 53     | 7.4%    |
| SanDisk                     | 33        | 38     | 5.31%   |
| Toshiba                     | 31        | 33     | 4.98%   |
| Kingston                    | 31        | 38     | 4.98%   |
| Hitachi                     | 24        | 33     | 3.86%   |
| Crucial                     | 23        | 28     | 3.7%    |
| SK hynix                    | 18        | 20     | 2.89%   |
| Intel                       | 16        | 16     | 2.57%   |
| HGST                        | 13        | 18     | 2.09%   |
| PNY                         | 10        | 10     | 1.61%   |
| China                       | 10        | 11     | 1.61%   |
| A-DATA Technology           | 10        | 13     | 1.61%   |
| Micron Technology           | 7         | 7      | 1.13%   |
| Unknown                     | 6         | 6      | 0.96%   |
| Phison                      | 5         | 12     | 0.8%    |
| Transcend                   | 4         | 5      | 0.64%   |
| SPCC                        | 4         | 4      | 0.64%   |
| Patriot                     | 4         | 4      | 0.64%   |
| Silicon Motion              | 3         | 3      | 0.48%   |
| Kingston Technology Company | 3         | 5      | 0.48%   |
| Intenso                     | 3         | 3      | 0.48%   |
| Fujitsu                     | 3         | 3      | 0.48%   |
| ASMT                        | 3         | 7      | 0.48%   |
| USB3.0                      | 2         | 4      | 0.32%   |
| TO Exter                    | 2         | 2      | 0.32%   |
| TEXTORM                     | 2         | 2      | 0.32%   |
| Realtek Semiconductor       | 2         | 2      | 0.32%   |
| OCZ                         | 2         | 2      | 0.32%   |
| Maxtor                      | 2         | 2      | 0.32%   |
| LITEON                      | 2         | 2      | 0.32%   |
| KIOXIA                      | 2         | 2      | 0.32%   |
| Hewlett-Packard             | 2         | 4      | 0.32%   |
| Gigabyte Technology         | 2         | 2      | 0.32%   |
| FORESEE                     | 2         | 3      | 0.32%   |
| Corsair                     | 2         | 2      | 0.32%   |
| Apple                       | 2         | 3      | 0.32%   |
| Apacer                      | 2         | 2      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB            | 9         | 1.32%   |
| Kingston SA400S37240G 240GB SSD      | 7         | 1.02%   |
| Crucial CT480BX500SSD1 480GB         | 7         | 1.02%   |
| Samsung SSD 850 EVO 500GB            | 6         | 0.88%   |
| Kingston SA400S37480G 480GB SSD      | 6         | 0.88%   |
| Unknown                              | 6         | 0.88%   |
| Unknown MMC Card  32GB               | 4         | 0.58%   |
| Toshiba DT01ACA200 2TB               | 4         | 0.58%   |
| Seagate ST500DM002-1BD142 500GB      | 4         | 0.58%   |
| SanDisk DF4064  64GB                 | 4         | 0.58%   |
| Crucial CT500MX500SSD1 500GB         | 4         | 0.58%   |
| Unknown SD/MMC/MS PRO 249GB          | 3         | 0.44%   |
| Unknown MMC Card  128GB              | 3         | 0.44%   |
| Toshiba MQ04ABF100 1TB               | 3         | 0.44%   |
| Toshiba MQ01ABF050 500GB             | 3         | 0.44%   |
| Toshiba HDWD110 1TB                  | 3         | 0.44%   |
| Toshiba DT01ACA100 1TB               | 3         | 0.44%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 0.44%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 0.44%   |
| Seagate ST500LM000-1EJ162 500GB      | 3         | 0.44%   |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 0.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 0.44%   |
| Seagate ST1000DM003-1SB102 1TB       | 3         | 0.44%   |
| SanDisk SDSSDA240G 240GB             | 3         | 0.44%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 0.44%   |
| Samsung SSD 850 EVO 250GB            | 3         | 0.44%   |
| Samsung SSD 840 Series 120GB         | 3         | 0.44%   |
| Samsung NVMe SSD Drive 256GB         | 3         | 0.44%   |
| PNY CS900 120GB SSD                  | 3         | 0.44%   |
| Hitachi HDS721050CLA362 500GB        | 3         | 0.44%   |
| HGST HTS541010A9E680 1TB             | 3         | 0.44%   |
| China SATA SSD 120GB                 | 3         | 0.44%   |
| WDC WD20EARS-00MVWB0 2TB             | 2         | 0.29%   |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 0.29%   |
| WDC WD10JPCX-24UE4T0 1TB             | 2         | 0.29%   |
| WDC WD10EZRZ-00HTKB0 1TB             | 2         | 0.29%   |
| WDC WD10EZEX-00BBHA0 1TB             | 2         | 0.29%   |
| WDC PC SN530 SDBPNPZ-512G-1036 512GB | 2         | 0.29%   |
| Unknown SA08G  8GB                   | 2         | 0.29%   |
| Unknown NCard  32GB                  | 2         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 71        | 89     | 30.74%  |
| WDC                 | 70        | 100    | 30.3%   |
| Toshiba             | 27        | 29     | 11.69%  |
| Hitachi             | 24        | 33     | 10.39%  |
| HGST                | 13        | 18     | 5.63%   |
| Samsung Electronics | 10        | 14     | 4.33%   |
| Unknown             | 3         | 4      | 1.3%    |
| Fujitsu             | 3         | 3      | 1.3%    |
| USB3.0              | 2         | 4      | 0.87%   |
| ASMT                | 2         | 5      | 0.87%   |
| PHD 3.0             | 1         | 1      | 0.43%   |
| Maxtor              | 1         | 1      | 0.43%   |
| LaCie               | 1         | 1      | 0.43%   |
| JMicron Technology  | 1         | 1      | 0.43%   |
| Hewlett-Packard     | 1         | 1      | 0.43%   |
| ASMedia             | 1         | 1      | 0.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 48        | 58     | 22.86%  |
| Kingston            | 26        | 30     | 12.38%  |
| Crucial             | 22        | 27     | 10.48%  |
| SanDisk             | 17        | 20     | 8.1%    |
| China               | 10        | 11     | 4.76%   |
| A-DATA Technology   | 10        | 13     | 4.76%   |
| WDC                 | 9         | 10     | 4.29%   |
| PNY                 | 9         | 9      | 4.29%   |
| Intel               | 6         | 6      | 2.86%   |
| Transcend           | 4         | 4      | 1.9%    |
| SPCC                | 4         | 4      | 1.9%    |
| Patriot             | 4         | 4      | 1.9%    |
| Micron Technology   | 4         | 4      | 1.9%    |
| Toshiba             | 3         | 3      | 1.43%   |
| Intenso             | 3         | 3      | 1.43%   |
| TO Exter            | 2         | 2      | 0.95%   |
| TEXTORM             | 2         | 2      | 0.95%   |
| SK hynix            | 2         | 2      | 0.95%   |
| OCZ                 | 2         | 2      | 0.95%   |
| LITEON              | 2         | 2      | 0.95%   |
| FORESEE             | 2         | 3      | 0.95%   |
| Apacer              | 2         | 2      | 0.95%   |
| Veno                | 1         | 1      | 0.48%   |
| Vaseky              | 1         | 1      | 0.48%   |
| Team                | 1         | 2      | 0.48%   |
| SSSTC               | 1         | 1      | 0.48%   |
| Netac               | 1         | 1      | 0.48%   |
| Maxtor              | 1         | 1      | 0.48%   |
| LITEONIT            | 1         | 1      | 0.48%   |
| Linux               | 1         | 1      | 0.48%   |
| KingFast            | 1         | 1      | 0.48%   |
| KingDian            | 1         | 1      | 0.48%   |
| Kimtigo             | 1         | 1      | 0.48%   |
| INNOVATION IT       | 1         | 1      | 0.48%   |
| EVM                 | 1         | 1      | 0.48%   |
| Corsair             | 1         | 1      | 0.48%   |
| ASMT                | 1         | 2      | 0.48%   |
| addlink             | 1         | 1      | 0.48%   |
| Unknown             | 1         | 1      | 0.48%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 191       | 305    | 34.29%  |
| SSD     | 185       | 240    | 33.21%  |
| NVMe    | 120       | 148    | 21.54%  |
| MMC     | 52        | 60     | 9.34%   |
| Unknown | 9         | 10     | 1.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 310       | 513    | 60.78%  |
| NVMe | 120       | 148    | 23.53%  |
| MMC  | 52        | 60     | 10.2%   |
| SAS  | 28        | 42     | 5.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 239       | 337    | 59.16%  |
| 0.51-1.0   | 98        | 117    | 24.26%  |
| 1.01-2.0   | 37        | 48     | 9.16%   |
| 3.01-4.0   | 18        | 27     | 4.46%   |
| 2.01-3.0   | 5         | 6      | 1.24%   |
| 4.01-10.0  | 5         | 7      | 1.24%   |
| 10.01-20.0 | 2         | 3      | 0.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 118       | 27.06%  |
| 251-500        | 103       | 23.62%  |
| 501-1000       | 57        | 13.07%  |
| 1001-2000      | 40        | 9.17%   |
| 51-100         | 32        | 7.34%   |
| 1-20           | 31        | 7.11%   |
| More than 3000 | 21        | 4.82%   |
| 21-50          | 21        | 4.82%   |
| 2001-3000      | 12        | 2.75%   |
| Unknown        | 1         | 0.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 160       | 36.28%  |
| 21-50          | 80        | 18.14%  |
| 101-250        | 63        | 14.29%  |
| 51-100         | 48        | 10.88%  |
| 251-500        | 41        | 9.3%    |
| 501-1000       | 20        | 4.54%   |
| 1001-2000      | 13        | 2.95%   |
| 2001-3000      | 8         | 1.81%   |
| More than 3000 | 7         | 1.59%   |
| Unknown        | 1         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba DT01ACA100 1TB                           | 2         | 2      | 3.03%   |
| Seagate ST500LT012-9WS142 500GB                  | 2         | 2      | 3.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 2         | 2      | 3.03%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                 | 1         | 1      | 1.52%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                 | 1         | 1      | 1.52%   |
| WDC WD5000AAKX-00ERMA0 500GB                     | 1         | 1      | 1.52%   |
| WDC WD3200AAKS-00L9A0 320GB                      | 1         | 1      | 1.52%   |
| WDC WD2500AAKS-00VSA0 250GB                      | 1         | 1      | 1.52%   |
| WDC WD20EFRX-68AX9N0 2TB                         | 1         | 1      | 1.52%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1         | 1      | 1.52%   |
| WDC WD2002FYPS-02W3B0 2TB                        | 1         | 1      | 1.52%   |
| WDC WD1200BEVS-60UST0 120GB                      | 1         | 1      | 1.52%   |
| WDC WD10EZEX-60ZF5A0 1TB                         | 1         | 1      | 1.52%   |
| WDC WD10EAVS-00D7B1 1TB                          | 1         | 1      | 1.52%   |
| WDC WD10EARS-00Y5B1 1TB                          | 1         | 1      | 1.52%   |
| WDC WD1003FBYX-01Y7B1 1TB                        | 1         | 1      | 1.52%   |
| WDC WD1001FALS-40Y6A0 1TB                        | 1         | 2      | 1.52%   |
| Toshiba MK1246GSX 120GB                          | 1         | 1      | 1.52%   |
| SSSTC CVB-8D128-HP 128GB                         | 1         | 1      | 1.52%   |
| Seagate ST9500325ASG 500GB                       | 1         | 1      | 1.52%   |
| Seagate ST9500325AS 500GB                        | 1         | 1      | 1.52%   |
| Seagate ST9250410AS 250GB                        | 1         | 1      | 1.52%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 1.52%   |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 1.52%   |
| Seagate ST3750840AS 752GB                        | 1         | 1      | 1.52%   |
| Seagate ST3250318AS 250GB                        | 1         | 2      | 1.52%   |
| Seagate ST320LT007-9ZV142 320GB                  | 1         | 1      | 1.52%   |
| Seagate ST2000DM001-1CH164 2TB                   | 1         | 1      | 1.52%   |
| Seagate ST1000LM 035-1RK172 1TB                  | 1         | 1      | 1.52%   |
| Seagate ST1000DM003-1ER162 1TB                   | 1         | 1      | 1.52%   |
| SanDisk SSD PLUS 240GB                           | 1         | 1      | 1.52%   |
| Samsung Electronics SP2514N 250GB                | 1         | 1      | 1.52%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 1.52%   |
| Samsung Electronics HM321HI 320GB                | 1         | 2      | 1.52%   |
| Samsung Electronics HD753LJ 752GB                | 1         | 1      | 1.52%   |
| Samsung Electronics HD250HJ 250GB                | 1         | 1      | 1.52%   |
| Samsung Electronics HD103SJ 1TB                  | 1         | 1      | 1.52%   |
| PNY 69D03094-T 40GB SSD                          | 1         | 1      | 1.52%   |
| Maxtor STM3160215AS 160GB                        | 1         | 1      | 1.52%   |
| LITEON LCH-512V2S 512GB SSD                      | 1         | 1      | 1.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 16     | 23.44%  |
| WDC                 | 13        | 15     | 20.31%  |
| Hitachi             | 8         | 9      | 12.5%   |
| Samsung Electronics | 5         | 7      | 7.81%   |
| Toshiba             | 3         | 3      | 4.69%   |
| Intel               | 3         | 3      | 4.69%   |
| HGST                | 3         | 5      | 4.69%   |
| Fujitsu             | 3         | 3      | 4.69%   |
| SSSTC               | 1         | 1      | 1.56%   |
| SanDisk             | 1         | 1      | 1.56%   |
| PNY                 | 1         | 1      | 1.56%   |
| Maxtor              | 1         | 1      | 1.56%   |
| LITEON              | 1         | 1      | 1.56%   |
| Kingston            | 1         | 2      | 1.56%   |
| JMicron Technology  | 1         | 1      | 1.56%   |
| Hewlett-Packard     | 1         | 1      | 1.56%   |
| Crucial             | 1         | 1      | 1.56%   |
| ASMT                | 1         | 4      | 1.56%   |
| Unknown             | 1         | 1      | 1.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 16     | 29.41%  |
| WDC                 | 11        | 13     | 21.57%  |
| Hitachi             | 8         | 9      | 15.69%  |
| Samsung Electronics | 4         | 6      | 7.84%   |
| Toshiba             | 3         | 3      | 5.88%   |
| HGST                | 3         | 5      | 5.88%   |
| Fujitsu             | 3         | 3      | 5.88%   |
| Maxtor              | 1         | 1      | 1.96%   |
| JMicron Technology  | 1         | 1      | 1.96%   |
| Hewlett-Packard     | 1         | 1      | 1.96%   |
| ASMT                | 1         | 4      | 1.96%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 47        | 62     | 79.66%  |
| SSD  | 12        | 14     | 20.34%  |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 233       | 358    | 48.64%  |
| Detected | 188       | 329    | 39.25%  |
| Malfunc  | 58        | 76     | 12.11%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 282       | 55.62%  |
| AMD                          | 83        | 16.37%  |
| Samsung Electronics          | 42        | 8.28%   |
| SanDisk                      | 18        | 3.55%   |
| SK hynix                     | 16        | 3.16%   |
| Kingston Technology Company  | 10        | 1.97%   |
| Phison Electronics           | 8         | 1.58%   |
| Silicon Motion               | 6         | 1.18%   |
| JMicron Technology           | 6         | 1.18%   |
| ASMedia Technology           | 6         | 1.18%   |
| Nvidia                       | 4         | 0.79%   |
| VIA Technologies             | 3         | 0.59%   |
| Realtek Semiconductor        | 3         | 0.59%   |
| Silicon Image                | 2         | 0.39%   |
| Micron/Crucial Technology    | 2         | 0.39%   |
| Micron Technology            | 2         | 0.39%   |
| Marvell Technology Group     | 2         | 0.39%   |
| KIOXIA                       | 2         | 0.39%   |
| Union Memory (Shenzhen)      | 1         | 0.2%    |
| Toshiba America Info Systems | 1         | 0.2%    |
| Shenzhen Longsys Electronics | 1         | 0.2%    |
| LSI Logic / Symbios Logic    | 1         | 0.2%    |
| Lenovo                       | 1         | 0.2%    |
| INNOGRIT                     | 1         | 0.2%    |
| Broadcom / LSI               | 1         | 0.2%    |
| Biwin Storage Technology     | 1         | 0.2%    |
| Apple                        | 1         | 0.2%    |
| Adaptec                      | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 62        | 10.53%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 20        | 3.4%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 19        | 3.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 17        | 2.89%   |
| Samsung NVMe SSD Controller 980                                                  | 16        | 2.72%   |
| Intel Volume Management Device NVMe RAID Controller                              | 12        | 2.04%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 11        | 1.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 11        | 1.87%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 11        | 1.87%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 11        | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 11        | 1.87%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 10        | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 10        | 1.7%    |
| AMD 400 Series Chipset SATA Controller                                           | 10        | 1.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 9         | 1.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 8         | 1.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 8         | 1.36%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 8         | 1.36%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 7         | 1.19%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 7         | 1.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 1.19%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 7         | 1.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 1.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 1.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 7         | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 7         | 1.19%   |
| AMD 500 Series Chipset SATA Controller                                           | 7         | 1.19%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 1.02%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 6         | 1.02%   |
| Intel SATA Controller [RAID mode]                                                | 6         | 1.02%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 6         | 1.02%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 6         | 1.02%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 1.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 1.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 6         | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 1.02%   |
| AMD FCH SATA Controller D                                                        | 6         | 1.02%   |
| Kingston Company A2000 NVMe SSD                                                  | 5         | 0.85%   |
| JMicron JMB363 SATA/IDE Controller                                               | 5         | 0.85%   |
| Intel Tiger Lake-LP SATA Controller                                              | 5         | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 314       | 60.38%  |
| NVMe | 120       | 23.08%  |
| IDE  | 53        | 10.19%  |
| RAID | 31        | 5.96%   |
| SAS  | 1         | 0.19%   |
| SCSI | 1         | 0.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 319       | 74.01%  |
| AMD    | 102       | 23.67%  |
| ARM    | 10        | 2.32%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 7         | 1.62%   |
| ARM Processor                               | 7         | 1.62%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 6         | 1.39%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 6         | 1.39%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 5         | 1.16%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 5         | 1.16%   |
| AMD Ryzen 5 3600 6-Core Processor           | 5         | 1.16%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 4         | 0.93%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 4         | 0.93%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 4         | 0.93%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 4         | 0.93%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 4         | 0.93%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 4         | 0.93%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 4         | 0.93%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 4         | 0.93%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 3         | 0.69%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3         | 0.69%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 0.69%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 3         | 0.69%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 3         | 0.69%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3         | 0.69%   |
| Intel 12th Gen Core i7-1260P                | 3         | 0.69%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz     | 3         | 0.69%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 3         | 0.69%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 3         | 0.69%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics  | 3         | 0.69%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3         | 0.69%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics | 3         | 0.69%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 2         | 0.46%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2         | 0.46%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 0.46%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 0.46%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 0.46%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 0.46%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 2         | 0.46%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 0.46%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 0.46%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2         | 0.46%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 0.46%   |
| Intel Core i5-7360U CPU @ 2.30GHz           | 2         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 86        | 19.91%  |
| Intel Celeron           | 52        | 12.04%  |
| Other                   | 44        | 10.19%  |
| Intel Core i7           | 44        | 10.19%  |
| Intel Core i3           | 32        | 7.41%   |
| AMD Ryzen 5             | 29        | 6.71%   |
| Intel Core 2 Duo        | 17        | 3.94%   |
| AMD Ryzen 7             | 14        | 3.24%   |
| Intel Xeon              | 11        | 2.55%   |
| Intel Pentium           | 9         | 2.08%   |
| Intel Atom              | 9         | 2.08%   |
| AMD A8                  | 7         | 1.62%   |
| AMD Ryzen 9             | 5         | 1.16%   |
| AMD A6                  | 5         | 1.16%   |
| Intel Pentium Dual-Core | 4         | 0.93%   |
| Intel Core 2            | 4         | 0.93%   |
| AMD Ryzen 3             | 4         | 0.93%   |
| AMD FX                  | 4         | 0.93%   |
| Intel Pentium Dual      | 3         | 0.69%   |
| Intel Genuine           | 3         | 0.69%   |
| Intel Core 2 Quad       | 3         | 0.69%   |
| ARM Allwinner           | 3         | 0.69%   |
| AMD Ryzen 7 PRO         | 3         | 0.69%   |
| AMD Ryzen 5 PRO         | 3         | 0.69%   |
| AMD Phenom II X4        | 3         | 0.69%   |
| AMD E1                  | 3         | 0.69%   |
| AMD Athlon II X2        | 3         | 0.69%   |
| AMD A10                 | 3         | 0.69%   |
| Intel Pentium 4         | 2         | 0.46%   |
| AMD Ryzen Threadripper  | 2         | 0.46%   |
| AMD E2                  | 2         | 0.46%   |
| AMD Athlon 64 X2        | 2         | 0.46%   |
| AMD Athlon              | 2         | 0.46%   |
| AMD A4                  | 2         | 0.46%   |
| Intel Xeon Gold         | 1         | 0.23%   |
| Intel Pentium Silver    | 1         | 0.23%   |
| Intel Core m3           | 1         | 0.23%   |
| Intel Core 2 Extreme    | 1         | 0.23%   |
| AMD Turion II Neo       | 1         | 0.23%   |
| AMD Sempron             | 1         | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 192       | 44.34%  |
| 4       | 145       | 33.49%  |
| 6       | 40        | 9.24%   |
| 8       | 25        | 5.77%   |
| 12      | 9         | 2.08%   |
| 1       | 6         | 1.39%   |
| 10      | 4         | 0.92%   |
| 16      | 3         | 0.69%   |
| Unknown | 3         | 0.69%   |
| 64      | 2         | 0.46%   |
| 14      | 2         | 0.46%   |
| 3       | 2         | 0.46%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 425       | 98.61%  |
| 2       | 3         | 0.7%    |
| Unknown | 3         | 0.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 252       | 58.47%  |
| 1       | 176       | 40.84%  |
| Unknown | 3         | 0.7%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 426       | 98.84%  |
| Unknown        | 4         | 0.93%   |
| 64-bit         | 1         | 0.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 151       | 34.79%  |
| 0x806c1    | 16        | 3.69%   |
| 0x306c3    | 14        | 3.23%   |
| 0x306a9    | 14        | 3.23%   |
| 0x406e3    | 11        | 2.53%   |
| 0x206a7    | 11        | 2.53%   |
| 0x406c4    | 8         | 1.84%   |
| 0x506c9    | 7         | 1.61%   |
| 0x306d4    | 7         | 1.61%   |
| 0x1067a    | 7         | 1.61%   |
| 0x08608103 | 7         | 1.61%   |
| 0x906ea    | 6         | 1.38%   |
| 0x806ec    | 6         | 1.38%   |
| 0x506e3    | 6         | 1.38%   |
| 0x406c3    | 6         | 1.38%   |
| 0x106e5    | 6         | 1.38%   |
| 0x806e9    | 5         | 1.15%   |
| 0x706a8    | 5         | 1.15%   |
| 0x30678    | 5         | 1.15%   |
| 0x0800820d | 5         | 1.15%   |
| 0xa0652    | 4         | 0.92%   |
| 0x706a1    | 4         | 0.92%   |
| 0x6fd      | 4         | 0.92%   |
| 0x6fb      | 4         | 0.92%   |
| 0x40651    | 4         | 0.92%   |
| 0x20655    | 4         | 0.92%   |
| 0x10676    | 4         | 0.92%   |
| 0x08701021 | 4         | 0.92%   |
| 0x08108109 | 4         | 0.92%   |
| 0x07030105 | 4         | 0.92%   |
| 0x010000c8 | 4         | 0.92%   |
| 0x906e9    | 3         | 0.69%   |
| 0x906a3    | 3         | 0.69%   |
| 0x90672    | 3         | 0.69%   |
| 0x806ea    | 3         | 0.69%   |
| 0x6f6      | 3         | 0.69%   |
| 0x20652    | 3         | 0.69%   |
| 0x0a50000c | 3         | 0.69%   |
| 0x05000119 | 3         | 0.69%   |
| 0xb0671    | 2         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 41        | 9.49%   |
| Haswell          | 32        | 7.41%   |
| Unknown          | 32        | 7.41%   |
| SandyBridge      | 30        | 6.94%   |
| Skylake          | 27        | 6.25%   |
| Silvermont       | 27        | 6.25%   |
| IvyBridge        | 25        | 5.79%   |
| Penryn           | 21        | 4.86%   |
| TigerLake        | 20        | 4.63%   |
| Zen 2            | 18        | 4.17%   |
| Core             | 15        | 3.47%   |
| Zen+             | 13        | 3.01%   |
| Zen 3            | 12        | 2.78%   |
| Westmere         | 11        | 2.55%   |
| Goldmont plus    | 11        | 2.55%   |
| Goldmont         | 10        | 2.31%   |
| Broadwell        | 10        | 2.31%   |
| K10              | 9         | 2.08%   |
| Nehalem          | 8         | 1.85%   |
| Puma             | 7         | 1.62%   |
| CometLake        | 7         | 1.62%   |
| Alderlake Hybrid | 7         | 1.62%   |
| Piledriver       | 6         | 1.39%   |
| Excavator        | 6         | 1.39%   |
| Zen              | 5         | 1.16%   |
| Icelake          | 4         | 0.93%   |
| Bobcat           | 4         | 0.93%   |
| K10 Llano        | 3         | 0.69%   |
| Bonnell          | 3         | 0.69%   |
| Steamroller      | 2         | 0.46%   |
| NetBurst         | 2         | 0.46%   |
| K8 Hammer        | 2         | 0.46%   |
| Tremont          | 1         | 0.23%   |
| Jaguar           | 1         | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 258       | 53.97%  |
| AMD                        | 107       | 22.38%  |
| Nvidia                     | 106       | 22.18%  |
| ASPEED Technology          | 4         | 0.84%   |
| Matrox Electronics Systems | 3         | 0.63%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 25        | 5.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 19        | 3.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 17        | 3.46%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 3.05%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 2.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 2.03%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 10        | 2.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 1.83%   |
| AMD Lucienne                                                                             | 9         | 1.83%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 8         | 1.63%   |
| Intel HD Graphics 530                                                                    | 8         | 1.63%   |
| Intel HD Graphics 500                                                                    | 8         | 1.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 1.63%   |
| Intel HD Graphics 620                                                                    | 7         | 1.42%   |
| Intel HD Graphics 5500                                                                   | 7         | 1.42%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 1.22%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 1.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 1.22%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 1.22%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 1.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.02%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 1.02%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 1.02%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 5         | 1.02%   |
| AMD Renoir                                                                               | 5         | 1.02%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 5         | 1.02%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 0.81%   |
| Nvidia GM108M [GeForce 840M]                                                             | 4         | 0.81%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4         | 0.81%   |
| Intel UHD Graphics 620                                                                   | 4         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 0.81%   |
| Intel HD Graphics 630                                                                    | 4         | 0.81%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 0.81%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 4         | 0.81%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 0.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.61%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 3         | 0.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 0.61%   |
| Intel AlderLake-S GT1                                                                    | 3         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 211       | 48.96%  |
| 1 x AMD         | 85        | 19.72%  |
| 1 x Nvidia      | 64        | 14.85%  |
| Intel + Nvidia  | 32        | 7.42%   |
| Other           | 11        | 2.55%   |
| 2 x AMD         | 7         | 1.62%   |
| Intel + AMD     | 7         | 1.62%   |
| AMD + Nvidia    | 7         | 1.62%   |
| Nvidia + ASPEED | 3         | 0.7%    |
| 1 x Matrox      | 2         | 0.46%   |
| 1 x ASPEED      | 1         | 0.23%   |
| AMD + Matrox    | 1         | 0.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 350       | 81.21%  |
| Proprietary | 61        | 14.15%  |
| Unknown     | 20        | 4.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 298       | 68.66%  |
| 0.01-0.5   | 46        | 10.6%   |
| 0.51-1.0   | 29        | 6.68%   |
| 1.01-2.0   | 28        | 6.45%   |
| 3.01-4.0   | 15        | 3.46%   |
| 7.01-8.0   | 7         | 1.61%   |
| 8.01-16.0  | 5         | 1.15%   |
| 5.01-6.0   | 3         | 0.69%   |
| 2.01-3.0   | 2         | 0.46%   |
| 32.01-64.0 | 1         | 0.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 61        | 13.62%  |
| Samsung Electronics     | 46        | 10.27%  |
| BOE                     | 42        | 9.38%   |
| LG Display              | 40        | 8.93%   |
| Dell                    | 35        | 7.81%   |
| Chimei Innolux          | 34        | 7.59%   |
| Hewlett-Packard         | 17        | 3.79%   |
| Goldstar                | 16        | 3.57%   |
| AOC                     | 12        | 2.68%   |
| Acer                    | 12        | 2.68%   |
| Lenovo                  | 10        | 2.23%   |
| ViewSonic               | 8         | 1.79%   |
| Iiyama                  | 8         | 1.79%   |
| Chi Mei Optoelectronics | 8         | 1.79%   |
| Apple                   | 8         | 1.79%   |
| Philips                 | 7         | 1.56%   |
| BenQ                    | 7         | 1.56%   |
| Ancor Communications    | 6         | 1.34%   |
| PANDA                   | 5         | 1.12%   |
| InfoVision              | 5         | 1.12%   |
| RTK                     | 4         | 0.89%   |
| LG Philips              | 4         | 0.89%   |
| Sony                    | 3         | 0.67%   |
| Sharp                   | 3         | 0.67%   |
| KDC                     | 3         | 0.67%   |
| Fujitsu Siemens         | 3         | 0.67%   |
| Vizio                   | 2         | 0.45%   |
| Unknown                 | 2         | 0.45%   |
| Toshiba                 | 2         | 0.45%   |
| Envision Peripherals    | 2         | 0.45%   |
| Eizo                    | 2         | 0.45%   |
| Unknown                 | 2         | 0.45%   |
| ___                     | 1         | 0.22%   |
| Vita                    | 1         | 0.22%   |
| Vestel Elektronik       | 1         | 0.22%   |
| TEO                     | 1         | 0.22%   |
| Tech Concepts           | 1         | 0.22%   |
| TCL                     | 1         | 0.22%   |
| SNC                     | 1         | 0.22%   |
| Sceptre Tech            | 1         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.66%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 3         | 0.66%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                   | 2         | 0.44%   |
| Sony NvidiaDefault SNY05FA 1366x768 290x170mm 13.2-inch                  | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 2         | 0.44%   |
| RTK AIO PC RTK2136 1600x900 432x239mm 19.4-inch                          | 2         | 0.44%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                       | 2         | 0.44%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.44%   |
| LG Display LCD Monitor LGD071D 1920x1080 344x194mm 15.5-inch             | 2         | 0.44%   |
| LG Display LCD Monitor LGD0514 1920x1080 309x174mm 14.0-inch             | 2         | 0.44%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 2         | 0.44%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch              | 2         | 0.44%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.44%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 2         | 0.44%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 2         | 0.44%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                      | 2         | 0.44%   |
| Hewlett-Packard 2309 HWP2821 1920x1080 510x287mm 23.0-inch               | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN153C 1920x1080 344x193mm 15.5-inch         | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1139 1366x768 256x144mm 11.6-inch          | 2         | 0.44%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 2         | 0.44%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 2         | 0.44%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch            | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 2         | 0.44%   |
| AOC U34G2G4R3 AOC3402 3440x1440 797x334mm 34.0-inch                      | 2         | 0.44%   |
| AOC 1970W-1 AOC1970 1366x768 410x230mm 18.5-inch                         | 2         | 0.44%   |
| Unknown                                                                  | 2         | 0.44%   |
| ___ LCD Monitor ___1BBC 1920x540 140x90mm 6.6-inch                       | 1         | 0.22%   |
| Vizio E320VT VIZ0067 1920x1080 698x392mm 31.5-inch                       | 1         | 0.22%   |
| Vizio E221VA VIZ0070 1920x1080 476x268mm 21.5-inch                       | 1         | 0.22%   |
| Vita V195EW-W VIT1950 1600x900 432x240mm 19.5-inch                       | 1         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 189       | 43.75%  |
| 1366x768 (WXGA)    | 86        | 19.91%  |
| 1600x900 (HD+)     | 28        | 6.48%   |
| 1920x1200 (WUXGA)  | 15        | 3.47%   |
| 1280x1024 (SXGA)   | 15        | 3.47%   |
| 3840x2160 (4K)     | 14        | 3.24%   |
| 2560x1440 (QHD)    | 14        | 3.24%   |
| 1440x900 (WXGA+)   | 13        | 3.01%   |
| 1280x800 (WXGA)    | 13        | 3.01%   |
| 1680x1050 (WSXGA+) | 8         | 1.85%   |
| 1024x768 (XGA)     | 5         | 1.16%   |
| 1360x768           | 4         | 0.93%   |
| 3840x1080          | 3         | 0.69%   |
| 3440x1440          | 3         | 0.69%   |
| 2560x1600          | 3         | 0.69%   |
| 1600x1200          | 3         | 0.69%   |
| 3840x1600          | 2         | 0.46%   |
| 2160x1440          | 2         | 0.46%   |
| 1024x600           | 2         | 0.46%   |
| Unknown            | 2         | 0.46%   |
| 2880x1800          | 1         | 0.23%   |
| 2560x1080          | 1         | 0.23%   |
| 2288x1287          | 1         | 0.23%   |
| 2048x1152          | 1         | 0.23%   |
| 1920x540           | 1         | 0.23%   |
| 1920x515           | 1         | 0.23%   |
| 1366x912           | 1         | 0.23%   |
| 1280x720 (HD)      | 1         | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 109       | 24.17%  |
| 14      | 44        | 9.76%   |
| 13      | 40        | 8.87%   |
| 23      | 32        | 7.1%    |
| 24      | 30        | 6.65%   |
| 17      | 29        | 6.43%   |
| 27      | 27        | 5.99%   |
| 21      | 20        | 4.43%   |
| Unknown | 17        | 3.77%   |
| 19      | 14        | 3.1%    |
| 18      | 12        | 2.66%   |
| 20      | 11        | 2.44%   |
| 12      | 10        | 2.22%   |
| 11      | 10        | 2.22%   |
| 31      | 6         | 1.33%   |
| 26      | 5         | 1.11%   |
| 16      | 5         | 1.11%   |
| 22      | 4         | 0.89%   |
| 34      | 3         | 0.67%   |
| 25      | 3         | 0.67%   |
| 84      | 2         | 0.44%   |
| 72      | 2         | 0.44%   |
| 54      | 2         | 0.44%   |
| 40      | 2         | 0.44%   |
| 37      | 2         | 0.44%   |
| 32      | 2         | 0.44%   |
| 10      | 2         | 0.44%   |
| 142     | 1         | 0.22%   |
| 49      | 1         | 0.22%   |
| 42      | 1         | 0.22%   |
| 30      | 1         | 0.22%   |
| 29      | 1         | 0.22%   |
| 6       | 1         | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 188       | 42.44%  |
| 501-600        | 88        | 19.86%  |
| 401-500        | 56        | 12.64%  |
| 201-300        | 38        | 8.58%   |
| 351-400        | 26        | 5.87%   |
| Unknown        | 17        | 3.84%   |
| 601-700        | 11        | 2.48%   |
| 701-800        | 5         | 1.13%   |
| 801-900        | 4         | 0.9%    |
| 1501-2000      | 4         | 0.9%    |
| 1001-1500      | 3         | 0.68%   |
| More than 2000 | 1         | 0.23%   |
| 101-200        | 1         | 0.23%   |
| 901-1000       | 1         | 0.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 315       | 75.9%   |
| 16/10   | 56        | 13.49%  |
| 5/4     | 12        | 2.89%   |
| Unknown | 11        | 2.65%   |
| 4/3     | 9         | 2.17%   |
| 21/9    | 5         | 1.2%    |
| 3/2     | 3         | 0.72%   |
| 6/5     | 1         | 0.24%   |
| 32/9    | 1         | 0.24%   |
| 3.73    | 1         | 0.24%   |
| 1.00    | 1         | 0.24%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 108       | 24.22%  |
| 81-90          | 71        | 15.92%  |
| 201-250        | 68        | 15.25%  |
| 151-200        | 35        | 7.85%   |
| 301-350        | 30        | 6.73%   |
| 141-150        | 18        | 4.04%   |
| Unknown        | 17        | 3.81%   |
| 121-130        | 15        | 3.36%   |
| 71-80          | 13        | 2.91%   |
| 351-500        | 13        | 2.91%   |
| 251-300        | 12        | 2.69%   |
| 51-60          | 10        | 2.24%   |
| 61-70          | 9         | 2.02%   |
| More than 1000 | 7         | 1.57%   |
| 131-140        | 7         | 1.57%   |
| 501-1000       | 5         | 1.12%   |
| 111-120        | 3         | 0.67%   |
| 41-50          | 2         | 0.45%   |
| 91-100         | 2         | 0.45%   |
| 1-40           | 1         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 150       | 34.48%  |
| 121-160       | 129       | 29.66%  |
| 101-120       | 115       | 26.44%  |
| Unknown       | 17        | 3.91%   |
| 161-240       | 14        | 3.22%   |
| 1-50          | 6         | 1.38%   |
| More than 240 | 4         | 0.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 360       | 83.53%  |
| 2     | 49        | 11.37%  |
| 0     | 15        | 3.48%   |
| 3     | 7         | 1.62%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 232       | 37%     |
| Intel                             | 205       | 32.7%   |
| Qualcomm Atheros                  | 62        | 9.89%   |
| Broadcom                          | 34        | 5.42%   |
| MediaTek                          | 9         | 1.44%   |
| Ralink Technology                 | 7         | 1.12%   |
| Marvell Technology Group          | 7         | 1.12%   |
| Broadcom Limited                  | 6         | 0.96%   |
| TP-Link                           | 5         | 0.8%    |
| Dell                              | 5         | 0.8%    |
| Sierra Wireless                   | 4         | 0.64%   |
| Qualcomm                          | 4         | 0.64%   |
| Nvidia                            | 4         | 0.64%   |
| Ralink                            | 3         | 0.48%   |
| Huawei Technologies               | 3         | 0.48%   |
| ASIX Electronics                  | 3         | 0.48%   |
| Aquantia                          | 3         | 0.48%   |
| Xiaomi                            | 2         | 0.32%   |
| Samsung Electronics               | 2         | 0.32%   |
| Qualcomm Atheros Communications   | 2         | 0.32%   |
| OPPO Electronics                  | 2         | 0.32%   |
| Microchip Technology              | 2         | 0.32%   |
| Insyde Software                   | 2         | 0.32%   |
| Hewlett-Packard                   | 2         | 0.32%   |
| D-Link System                     | 2         | 0.32%   |
| ZyDAS                             | 1         | 0.16%   |
| TRENDnet                          | 1         | 0.16%   |
| NetGear                           | 1         | 0.16%   |
| Microsoft                         | 1         | 0.16%   |
| Mellanox Technologies             | 1         | 0.16%   |
| LG Electronics                    | 1         | 0.16%   |
| Fibocom                           | 1         | 0.16%   |
| Ericsson Business Mobile Networks | 1         | 0.16%   |
| D-Link                            | 1         | 0.16%   |
| BUFFALO                           | 1         | 0.16%   |
| Belkin Components                 | 1         | 0.16%   |
| Attansic Technology               | 1         | 0.16%   |
| ASUSTek Computer                  | 1         | 0.16%   |
| Arduino SA                        | 1         | 0.16%   |
| Apple                             | 1         | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 157       | 21.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 3.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 2.15%   |
| Intel Wi-Fi 6 AX200                                               | 15        | 2.02%   |
| Intel Wireless 8260                                               | 14        | 1.88%   |
| Intel Wi-Fi 6 AX201                                               | 14        | 1.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 13        | 1.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 1.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 1.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 10        | 1.34%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 1.34%   |
| Intel Wireless 7265                                               | 10        | 1.34%   |
| Intel Wireless 3165                                               | 9         | 1.21%   |
| Intel I211 Gigabit Network Connection                             | 9         | 1.21%   |
| Intel Wireless 7260                                               | 8         | 1.08%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 1.08%   |
| Intel Ethernet Connection (2) I219-V                              | 8         | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 8         | 1.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 0.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 0.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7         | 0.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 0.81%   |
| Realtek 802.11ac NIC                                              | 6         | 0.81%   |
| Intel Wireless 3160                                               | 6         | 0.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 0.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 0.81%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 0.81%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 5         | 0.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 0.67%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 5         | 0.67%   |
| Intel Wireless 8265 / 8275                                        | 5         | 0.67%   |
| Intel Ethernet Controller I225-V                                  | 5         | 0.67%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.67%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 0.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 0.54%   |
| Realtek 802.11n WLAN Adapter                                      | 4         | 0.54%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 0.54%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 4         | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 152       | 44.31%  |
| Realtek Semiconductor           | 67        | 19.53%  |
| Qualcomm Atheros                | 57        | 16.62%  |
| Broadcom                        | 18        | 5.25%   |
| MediaTek                        | 9         | 2.62%   |
| Ralink Technology               | 7         | 2.04%   |
| TP-Link                         | 4         | 1.17%   |
| Sierra Wireless                 | 4         | 1.17%   |
| Qualcomm                        | 4         | 1.17%   |
| Ralink                          | 3         | 0.87%   |
| Dell                            | 3         | 0.87%   |
| Qualcomm Atheros Communications | 2         | 0.58%   |
| Broadcom Limited                | 2         | 0.58%   |
| ZyDAS                           | 1         | 0.29%   |
| TRENDnet                        | 1         | 0.29%   |
| NetGear                         | 1         | 0.29%   |
| Microsoft                       | 1         | 0.29%   |
| Marvell Technology Group        | 1         | 0.29%   |
| Fibocom                         | 1         | 0.29%   |
| D-Link System                   | 1         | 0.29%   |
| D-Link                          | 1         | 0.29%   |
| BUFFALO                         | 1         | 0.29%   |
| Belkin Components               | 1         | 0.29%   |
| ASUSTek Computer                | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 15        | 4.31%   |
| Intel Wireless 8260                                                     | 14        | 4.02%   |
| Intel Wi-Fi 6 AX201                                                     | 14        | 4.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 13        | 3.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 3.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 2.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 2.87%   |
| Intel Wireless 7265                                                     | 10        | 2.87%   |
| Intel Wireless 3165                                                     | 9         | 2.59%   |
| Intel Wireless 7260                                                     | 8         | 2.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 8         | 2.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 2.01%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 7         | 2.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 1.72%   |
| Realtek 802.11ac NIC                                                    | 6         | 1.72%   |
| Intel Wireless 3160                                                     | 6         | 1.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 1.72%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 5         | 1.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 1.44%   |
| Intel Wireless 8265 / 8275                                              | 5         | 1.44%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 1.44%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 1.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 1.15%   |
| Realtek 802.11n WLAN Adapter                                            | 4         | 1.15%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 1.15%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 4         | 1.15%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 1.15%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 1.15%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.15%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.15%   |
| Sierra Wireless EM7455                                                  | 3         | 0.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 0.86%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 3         | 0.86%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.86%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 202       | 53.02%  |
| Intel                    | 110       | 28.87%  |
| Broadcom                 | 19        | 4.99%   |
| Qualcomm Atheros         | 12        | 3.15%   |
| Marvell Technology Group | 6         | 1.57%   |
| Nvidia                   | 4         | 1.05%   |
| Broadcom Limited         | 4         | 1.05%   |
| Huawei Technologies      | 3         | 0.79%   |
| ASIX Electronics         | 3         | 0.79%   |
| Aquantia                 | 3         | 0.79%   |
| Xiaomi                   | 2         | 0.52%   |
| OPPO Electronics         | 2         | 0.52%   |
| Insyde Software          | 2         | 0.52%   |
| Hewlett-Packard          | 2         | 0.52%   |
| TP-Link                  | 1         | 0.26%   |
| Samsung Electronics      | 1         | 0.26%   |
| Microchip Technology     | 1         | 0.26%   |
| LG Electronics           | 1         | 0.26%   |
| D-Link System            | 1         | 0.26%   |
| Attansic Technology      | 1         | 0.26%   |
| Apple                    | 1         | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 157       | 40.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 27        | 6.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16        | 4.11%   |
| Realtek RTL8125 2.5GbE Controller                                              | 11        | 2.83%   |
| Intel I211 Gigabit Network Connection                                          | 9         | 2.31%   |
| Intel Ethernet Connection I219-LM                                              | 8         | 2.06%   |
| Intel Ethernet Connection (2) I219-V                                           | 8         | 2.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7         | 1.8%    |
| Intel Ethernet Controller I225-V                                               | 5         | 1.29%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.29%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 4         | 1.03%   |
| Nvidia MCP61 Ethernet                                                          | 4         | 1.03%   |
| Intel I210 Gigabit Network Connection                                          | 4         | 1.03%   |
| Intel Ethernet Connection I217-V                                               | 4         | 1.03%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 4         | 1.03%   |
| Intel Ethernet Connection I219-V                                               | 3         | 0.77%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 0.77%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 0.77%   |
| Intel Ethernet Connection (13) I219-V                                          | 3         | 0.77%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 0.77%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 0.77%   |
| Huawei ATU-L21                                                                 | 3         | 0.77%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 0.77%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 0.51%   |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                                           | 2         | 0.51%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.51%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 2         | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 0.51%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 0.51%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.51%   |
| Intel Ethernet Connection (17) I219-V                                          | 2         | 0.51%   |
| Intel Ethernet Connection (16) I219-V                                          | 2         | 0.51%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 0.51%   |
| Intel 82578DM Gigabit Network Connection                                       | 2         | 0.51%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2         | 0.51%   |
| Intel 82566MM Gigabit Network Connection                                       | 2         | 0.51%   |
| Insyde Software RNDIS/Ethernet Gadget                                          | 2         | 0.51%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 2         | 0.51%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 357       | 52.27%  |
| WiFi     | 319       | 46.71%  |
| Modem    | 6         | 0.88%   |
| Unknown  | 1         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 257       | 58.28%  |
| Ethernet | 184       | 41.72%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 232       | 53.7%   |
| 1     | 171       | 39.58%  |
| 0     | 19        | 4.4%    |
| 3     | 7         | 1.62%   |
| 4     | 3         | 0.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 287       | 65.98%  |
| Yes  | 148       | 34.02%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 117       | 46.06%  |
| Realtek Semiconductor           | 29        | 11.42%  |
| Broadcom                        | 19        | 7.48%   |
| Cambridge Silicon Radio         | 17        | 6.69%   |
| Qualcomm Atheros Communications | 12        | 4.72%   |
| IMC Networks                    | 11        | 4.33%   |
| Foxconn / Hon Hai               | 11        | 4.33%   |
| Lite-On Technology              | 10        | 3.94%   |
| Apple                           | 7         | 2.76%   |
| Hewlett-Packard                 | 4         | 1.57%   |
| Realtek                         | 3         | 1.18%   |
| MediaTek                        | 2         | 0.79%   |
| Dell                            | 2         | 0.79%   |
| ASUSTek Computer                | 2         | 0.79%   |
| USI                             | 1         | 0.39%   |
| Toshiba                         | 1         | 0.39%   |
| Ralink                          | 1         | 0.39%   |
| Marvell Semiconductor           | 1         | 0.39%   |
| Fujitsu                         | 1         | 0.39%   |
| Foxconn International           | 1         | 0.39%   |
| Chicony Electronics             | 1         | 0.39%   |
| Alps Electric                   | 1         | 0.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 51        | 20.08%  |
| Intel AX201 Bluetooth                                                               | 22        | 8.66%   |
| Realtek Bluetooth Radio                                                             | 21        | 8.27%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 17        | 6.69%   |
| Intel AX200 Bluetooth                                                               | 15        | 5.91%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 8         | 3.15%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 2.36%   |
| Intel Bluetooth Device                                                              | 6         | 2.36%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 2.36%   |
| Intel AX210 Bluetooth                                                               | 6         | 2.36%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 2.36%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 1.97%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 1.57%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 1.57%   |
| Realtek 802.11ac WLAN Adapter                                                       | 3         | 1.18%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.18%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.18%   |
| IMC Networks Wireless_Device                                                        | 3         | 1.18%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 1.18%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 3         | 1.18%   |
| MediaTek Wireless_Device                                                            | 2         | 0.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 0.79%   |
| Lite-On Bluetooth Device                                                            | 2         | 0.79%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.79%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 0.79%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.79%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.79%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.79%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 0.79%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 0.79%   |
| Broadcom BCM2045 Bluetooth                                                          | 2         | 0.79%   |
| Apple Bluetooth Host Controller                                                     | 2         | 0.79%   |
| USI Bluetooth Device                                                                | 1         | 0.39%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.39%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.39%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 0.39%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.39%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.39%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.39%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 308       | 57.46%  |
| AMD                         | 112       | 20.9%   |
| Nvidia                      | 75        | 13.99%  |
| C-Media Electronics         | 5         | 0.93%   |
| Texas Instruments           | 4         | 0.75%   |
| Generalplus Technology      | 3         | 0.56%   |
| ASUSTek Computer            | 3         | 0.56%   |
| SAVITECH                    | 2         | 0.37%   |
| JMTek                       | 2         | 0.37%   |
| GN Netcom                   | 2         | 0.37%   |
| Creative Technology         | 2         | 0.37%   |
| Creative Labs               | 2         | 0.37%   |
| VIA Technologies            | 1         | 0.19%   |
| Trust International         | 1         | 0.19%   |
| Tenx Technology             | 1         | 0.19%   |
| STMicroelectronics          | 1         | 0.19%   |
| Samson Technologies         | 1         | 0.19%   |
| Plantronics                 | 1         | 0.19%   |
| Micro Star International    | 1         | 0.19%   |
| Medeli Electronics          | 1         | 0.19%   |
| MAG Technology              | 1         | 0.19%   |
| Logitech                    | 1         | 0.19%   |
| Lenovo                      | 1         | 0.19%   |
| Kingston Technology         | 1         | 0.19%   |
| Hewlett-Packard             | 1         | 0.19%   |
| FiiO Electronics Technology | 1         | 0.19%   |
| Corsair                     | 1         | 0.19%   |
| Conexant Systems            | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 32        | 5.02%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 30        | 4.71%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 26        | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 26        | 4.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 22        | 3.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 20        | 3.14%   |
| AMD FCH Azalia Controller                                                                         | 20        | 3.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 19        | 2.98%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 17        | 2.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 16        | 2.51%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 15        | 2.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 14        | 2.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 14        | 2.2%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 13        | 2.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 1.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 11        | 1.73%   |
| AMD Kabini HDMI/DP Audio                                                                          | 11        | 1.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 10        | 1.57%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 1.57%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 1.41%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 1.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 1.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 1.41%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 1.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 1.26%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 8         | 1.26%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 1.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 1.1%    |
| Intel Alder Lake-S HD Audio Controller                                                            | 7         | 1.1%    |
| Intel 8 Series HD Audio Controller                                                                | 7         | 1.1%    |
| Intel 200 Series PCH HD Audio                                                                     | 7         | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 0.94%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 0.94%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 6         | 0.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 0.94%   |
| Nvidia Audio device                                                                               | 5         | 0.78%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 0.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 0.78%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 5         | 0.78%   |
| Nvidia MCP61 High Definition Audio                                                                | 4         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 88        | 24.44%  |
| Unknown                    | 53        | 14.72%  |
| SK hynix                   | 49        | 13.61%  |
| Kingston                   | 42        | 11.67%  |
| Micron Technology          | 29        | 8.06%   |
| Crucial                    | 26        | 7.22%   |
| Ramaxel Technology         | 12        | 3.33%   |
| G.Skill                    | 12        | 3.33%   |
| Unknown (ABCD)             | 10        | 2.78%   |
| Corsair                    | 8         | 2.22%   |
| Nanya Technology           | 5         | 1.39%   |
| Elpida                     | 5         | 1.39%   |
| Transcend                  | 3         | 0.83%   |
| Smart                      | 2         | 0.56%   |
| A-DATA Technology          | 2         | 0.56%   |
| Unknown                    | 2         | 0.56%   |
| V-Color                    | 1         | 0.28%   |
| Unknown (7F7F7F7F7F7F6B00) | 1         | 0.28%   |
| Timetec                    | 1         | 0.28%   |
| Qumo                       | 1         | 0.28%   |
| Qimonda                    | 1         | 0.28%   |
| GLOWAY                     | 1         | 0.28%   |
| Foxline                    | 1         | 0.28%   |
| fef5                       | 1         | 0.28%   |
| Essencore                  | 1         | 0.28%   |
| Daten Tecnologia           | 1         | 0.28%   |
| Avant                      | 1         | 0.28%   |
| ASint Technology           | 1         | 0.28%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 7         | 1.87%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 1.07%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 1.07%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 1.07%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 1.07%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 3         | 0.8%    |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                        | 3         | 0.8%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 3         | 0.8%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 3         | 0.8%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.8%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.8%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.8%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.53%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 2         | 0.53%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 0.53%   |
| Unknown RAM Module 1GB SODIMM LPDDR3 1600MT/s                    | 2         | 0.53%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 2         | 0.53%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.53%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 0.53%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 2         | 0.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.53%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.53%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.53%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.53%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.53%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.53%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 2         | 0.53%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.53%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 0.53%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 0.53%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.53%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.53%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.53%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.53%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                  | 2         | 0.53%   |
| Samsung RAM K3LKCKC0BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s     | 2         | 0.53%   |
| Ramaxel RAM RMUA5120ME86H9F-2666 4GB DIMM DDR4 2667MT/s          | 2         | 0.53%   |
| Micron RAM Module 2GB SODIMM DDR3 1333MT/s                       | 2         | 0.53%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 125       | 40.45%  |
| DDR3    | 109       | 35.28%  |
| LPDDR4  | 23        | 7.44%   |
| DDR2    | 17        | 5.5%    |
| Unknown | 9         | 2.91%   |
| SDRAM   | 8         | 2.59%   |
| LPDDR3  | 8         | 2.59%   |
| LPDDR5  | 4         | 1.29%   |
| DDR5    | 4         | 1.29%   |
| DRAM    | 1         | 0.32%   |
| DDR     | 1         | 0.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 170       | 55.02%  |
| DIMM         | 109       | 35.28%  |
| Row Of Chips | 22        | 7.12%   |
| Unknown      | 5         | 1.62%   |
| Chip         | 3         | 0.97%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 104       | 31.52%  |
| 8192  | 103       | 31.21%  |
| 2048  | 56        | 16.97%  |
| 16384 | 45        | 13.64%  |
| 1024  | 13        | 3.94%   |
| 32768 | 6         | 1.82%   |
| 65536 | 1         | 0.3%    |
| 1536  | 1         | 0.3%    |
| 512   | 1         | 0.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 74        | 22.77%  |
| 3200    | 51        | 15.69%  |
| 2667    | 33        | 10.15%  |
| 2400    | 28        | 8.62%   |
| 1333    | 24        | 7.38%   |
| 2133    | 16        | 4.92%   |
| 667     | 11        | 3.38%   |
| 1334    | 8         | 2.46%   |
| 4267    | 6         | 1.85%   |
| 3600    | 6         | 1.85%   |
| 1867    | 5         | 1.54%   |
| 1067    | 5         | 1.54%   |
| 1066    | 5         | 1.54%   |
| Unknown | 5         | 1.54%   |
| 3000    | 4         | 1.23%   |
| 6400    | 3         | 0.92%   |
| 4800    | 3         | 0.92%   |
| 3466    | 3         | 0.92%   |
| 3266    | 3         | 0.92%   |
| 2666    | 3         | 0.92%   |
| 4266    | 2         | 0.62%   |
| 4199    | 2         | 0.62%   |
| 2048    | 2         | 0.62%   |
| 1866    | 2         | 0.62%   |
| 975     | 2         | 0.62%   |
| 800     | 2         | 0.62%   |
| 533     | 2         | 0.62%   |
| 6000    | 1         | 0.31%   |
| 5500    | 1         | 0.31%   |
| 5354    | 1         | 0.31%   |
| 4000    | 1         | 0.31%   |
| 3866    | 1         | 0.31%   |
| 3733    | 1         | 0.31%   |
| 3400    | 1         | 0.31%   |
| 3020    | 1         | 0.31%   |
| 2800    | 1         | 0.31%   |
| 2134    | 1         | 0.31%   |
| 2000    | 1         | 0.31%   |
| 1800    | 1         | 0.31%   |
| 1776    | 1         | 0.31%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 44.44%  |
| Brother Industries  | 2         | 22.22%  |
| Samsung Electronics | 1         | 11.11%  |
| Minolta             | 1         | 11.11%  |
| Canon               | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung SF-760 Series         | 1         | 11.11%  |
| Minolta PagePro 1300W         | 1         | 11.11%  |
| HP ENVY Pro 6400 series       | 1         | 11.11%  |
| HP DeskJet D1360              | 1         | 11.11%  |
| HP DeskJet 840c               | 1         | 11.11%  |
| HP Deskjet 3070 B611 series   | 1         | 11.11%  |
| Canon TS3500 series           | 1         | 11.11%  |
| Brother HL-2030 Laser Printer | 1         | 11.11%  |
| Brother DCP-7040              | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 4         | 66.67%  |
| Seiko Epson     | 1         | 16.67%  |
| Hewlett-Packard | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Canon CanoScan LiDE 100                | 3         | 50%     |
| Seiko Epson GT-9800F [Perfection 3200] | 1         | 16.67%  |
| HP ScanJet 7400c                       | 1         | 16.67%  |
| Canon CanoScan LiDE 110                | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 66        | 24.63%  |
| Realtek Semiconductor                  | 21        | 7.84%   |
| Quanta                                 | 18        | 6.72%   |
| Microdia                               | 18        | 6.72%   |
| IMC Networks                           | 17        | 6.34%   |
| Cheng Uei Precision Industry (Foxlink) | 16        | 5.97%   |
| Sunplus Innovation Technology          | 15        | 5.6%    |
| Suyin                                  | 14        | 5.22%   |
| Logitech                               | 11        | 4.1%    |
| Apple                                  | 6         | 2.24%   |
| Acer                                   | 6         | 2.24%   |
| Luxvisions Innotech Limited            | 5         | 1.87%   |
| Bison Electronics                      | 5         | 1.87%   |
| Z-Star Microelectronics                | 4         | 1.49%   |
| Syntek                                 | 4         | 1.49%   |
| Alcor Micro                            | 4         | 1.49%   |
| Silicon Motion                         | 3         | 1.12%   |
| Microsoft                              | 3         | 1.12%   |
| Lite-On Technology                     | 3         | 1.12%   |
| USB Camera CS                          | 2         | 0.75%   |
| Sonix Technology                       | 2         | 0.75%   |
| Ricoh                                  | 2         | 0.75%   |
| Lenovo                                 | 2         | 0.75%   |
| KYE Systems (Mouse Systems)            | 2         | 0.75%   |
| icSpring                               | 2         | 0.75%   |
| Xiongmai                               | 1         | 0.37%   |
| Xiaomi                                 | 1         | 0.37%   |
| ValueHD                                | 1         | 0.37%   |
| SunplusIT                              | 1         | 0.37%   |
| Sunplus Technology                     | 1         | 0.37%   |
| Samsung Electronics                    | 1         | 0.37%   |
| Primax Electronics                     | 1         | 0.37%   |
| OYT Tech                               | 1         | 0.37%   |
| OmniVision Technologies                | 1         | 0.37%   |
| MacroSilicon                           | 1         | 0.37%   |
| Importek                               | 1         | 0.37%   |
| Guillemot                              | 1         | 0.37%   |
| Generalplus Technology                 | 1         | 0.37%   |
| Creative Technology                    | 1         | 0.37%   |
| ARC International                      | 1         | 0.37%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 23        | 8.52%   |
| Chicony HD Webcam                                   | 6         | 2.22%   |
| Sunplus Integrated_Webcam_HD                        | 5         | 1.85%   |
| Quanta HD User Facing                               | 5         | 1.85%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 5         | 1.85%   |
| Realtek Integrated_Webcam_HD                        | 4         | 1.48%   |
| Microdia Integrated_Webcam_HD                       | 4         | 1.48%   |
| Logitech C922 Pro Stream Webcam                     | 4         | 1.48%   |
| IMC Networks Integrated Camera                      | 4         | 1.48%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 4         | 1.48%   |
| Suyin HP TrueVision HD Integrated Webcam            | 3         | 1.11%   |
| Sunplus Integrated_Webcam_FHD                       | 3         | 1.11%   |
| Realtek Acer 640 x 480 laptop camera                | 3         | 1.11%   |
| Quanta HP TrueVision HD Camera                      | 3         | 1.11%   |
| Microdia Sonix USB 2.0 Camera                       | 3         | 1.11%   |
| Chicony TOSHIBA Web Camera - HD                     | 3         | 1.11%   |
| Chicony EasyCamera                                  | 3         | 1.11%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 3         | 1.11%   |
| Alcor Micro SHUNCCM2MP                              | 3         | 1.11%   |
| USB Camera CS USB Camera CS                         | 2         | 0.74%   |
| Syntek Integrated Camera                            | 2         | 0.74%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 2         | 0.74%   |
| Sunplus HD WebCam                                   | 2         | 0.74%   |
| Silicon Motion 300k Pixel Camera                    | 2         | 0.74%   |
| Realtek USB Camera                                  | 2         | 0.74%   |
| Realtek Lenovo EasyCamera                           | 2         | 0.74%   |
| Realtek HP Truevision HD                            | 2         | 0.74%   |
| Quanta USB2.0 HD UVC WebCam                         | 2         | 0.74%   |
| Quanta HP Webcam                                    | 2         | 0.74%   |
| Quanta HP HD Camera                                 | 2         | 0.74%   |
| Microdia Webcam Vitade AF                           | 2         | 0.74%   |
| Microdia USB 2.0 Camera                             | 2         | 0.74%   |
| Microdia Lenovo EasyCamera                          | 2         | 0.74%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 0.74%   |
| Logitech HD Pro Webcam C920                         | 2         | 0.74%   |
| Logitech BRIO Ultra HD Webcam                       | 2         | 0.74%   |
| Lenovo Integrated Webcam [R5U877]                   | 2         | 0.74%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 0.74%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 2         | 0.74%   |
| IMC Networks ov9734_azurewave_camera                | 2         | 0.74%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 13        | 29.55%  |
| Shenzhen Goodix Technology | 10        | 22.73%  |
| Upek                       | 6         | 13.64%  |
| Synaptics                  | 6         | 13.64%  |
| STMicroelectronics         | 2         | 4.55%   |
| Elan Microelectronics      | 2         | 4.55%   |
| AuthenTec                  | 2         | 4.55%   |
| LighTuning Technology      | 1         | 2.27%   |
| Gingytech                  | 1         | 2.27%   |
| Focal-systems.Corp         | 1         | 2.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                    | 7         | 15.91%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 5         | 11.36%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 5         | 11.36%  |
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 6.82%   |
| Validity Sensors Synaptics WBDI                        | 3         | 6.82%   |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 6.82%   |
| Validity Sensors VFS451 Fingerprint Reader             | 2         | 4.55%   |
| Synaptics UWP WBDI Device                              | 2         | 4.55%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 4.55%   |
| STMicroelectronics Fingerprint Reader                  | 2         | 4.55%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 2.27%   |
| Synaptics  WBDI                                        | 1         | 2.27%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 2.27%   |
| LighTuning Fingerprint Sensor                          | 1         | 2.27%   |
| Gingytech Fingerprint sensor                           | 1         | 2.27%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 2.27%   |
| Elan ELAN:Fingerprint                                  | 1         | 2.27%   |
| Elan ELAN:ARM-M4                                       | 1         | 2.27%   |
| AuthenTec AES2810                                      | 1         | 2.27%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 2.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 10        | 38.46%  |
| Alcor Micro              | 9         | 34.62%  |
| Lenovo                   | 3         | 11.54%  |
| O2 Micro                 | 2         | 7.69%   |
| Reiner SCT Kartensysteme | 1         | 3.85%   |
| In Focus Systems         | 1         | 3.85%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 34.62%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 11.54%  |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 11.54%  |
| Broadcom 5880                                                                | 3         | 11.54%  |
| Broadcom 58200                                                               | 3         | 11.54%  |
| Reiner SCT Kartensysteme cyberJack one                                       | 1         | 3.85%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 3.85%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 3.85%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 3.85%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.85%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 311       | 71.66%  |
| 1     | 96        | 22.12%  |
| 2     | 21        | 4.84%   |
| 3     | 5         | 1.15%   |
| 5     | 1         | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 42        | 28%     |
| Graphics card            | 26        | 17.33%  |
| Chipcard                 | 25        | 16.67%  |
| Camera                   | 14        | 9.33%   |
| Net/wireless             | 10        | 6.67%   |
| Multimedia controller    | 7         | 4.67%   |
| Bluetooth                | 5         | 3.33%   |
| Unassigned class         | 4         | 2.67%   |
| Communication controller | 4         | 2.67%   |
| Card reader              | 4         | 2.67%   |
| Network                  | 3         | 2%      |
| Storage                  | 2         | 1.33%   |
| Net/ethernet             | 2         | 1.33%   |
| Sound                    | 1         | 0.67%   |
| Dvb card                 | 1         | 0.67%   |

