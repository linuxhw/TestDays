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

Total: 2884

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 1589                        | Desktop     | [550b95765c](https://linux-hardware.org/?probe=550b95765c) | Sep 06, 2023 |
| System76      | Pangolin                    | Notebook    | [43dbf49440](https://linux-hardware.org/?probe=43dbf49440) | Sep 06, 2023 |
| System76      | Pangolin                    | Notebook    | [461b8d48ba](https://linux-hardware.org/?probe=461b8d48ba) | Sep 05, 2023 |
| Loongson      | LS3A6000-7A2000-1w-EVB-V... | Desktop     | [48e1f16931](https://linux-hardware.org/?probe=48e1f16931) | Sep 05, 2023 |
| Gigabyte      | AORUS 17 XE4                | Notebook    | [7987abcc44](https://linux-hardware.org/?probe=7987abcc44) | Sep 04, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [f3cbaf1a86](https://linux-hardware.org/?probe=f3cbaf1a86) | Sep 04, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [b0e01251ca](https://linux-hardware.org/?probe=b0e01251ca) | Sep 04, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f51b98f4cd](https://linux-hardware.org/?probe=f51b98f4cd) | Sep 04, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [ba5eecca4c](https://linux-hardware.org/?probe=ba5eecca4c) | Sep 03, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [6f9a36245f](https://linux-hardware.org/?probe=6f9a36245f) | Sep 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [efd96ce796](https://linux-hardware.org/?probe=efd96ce796) | Sep 03, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [e6df46a4a8](https://linux-hardware.org/?probe=e6df46a4a8) | Sep 03, 2023 |
| HP            | ProBook 430 G5              | Notebook    | [1785af95b8](https://linux-hardware.org/?probe=1785af95b8) | Sep 02, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [32a90ea48e](https://linux-hardware.org/?probe=32a90ea48e) | Sep 02, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [5032531f3e](https://linux-hardware.org/?probe=5032531f3e) | Sep 02, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [9f3df2894e](https://linux-hardware.org/?probe=9f3df2894e) | Sep 02, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [678bbd1366](https://linux-hardware.org/?probe=678bbd1366) | Sep 01, 2023 |
| HP            | 1589                        | Desktop     | [447cae1b4c](https://linux-hardware.org/?probe=447cae1b4c) | Sep 01, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [cb84df3a99](https://linux-hardware.org/?probe=cb84df3a99) | Aug 31, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [96d825f112](https://linux-hardware.org/?probe=96d825f112) | Aug 31, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [f0e20e0089](https://linux-hardware.org/?probe=f0e20e0089) | Aug 31, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [b4eb252e8f](https://linux-hardware.org/?probe=b4eb252e8f) | Aug 31, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [d53deba94a](https://linux-hardware.org/?probe=d53deba94a) | Aug 31, 2023 |
| Loongson      | LS3A6000-7A2000-1w-EVB-V... | Desktop     | [a99a5ccc55](https://linux-hardware.org/?probe=a99a5ccc55) | Aug 30, 2023 |
| Dell          | Latitude E6510              | Notebook    | [ccc08ed4ed](https://linux-hardware.org/?probe=ccc08ed4ed) | Aug 30, 2023 |
| Dell          | Latitude E6510              | Notebook    | [dcf1be6cbe](https://linux-hardware.org/?probe=dcf1be6cbe) | Aug 30, 2023 |
| Loongson      | LS3A6000-7A2000-1w-EVB-V... | Desktop     | [ad154077da](https://linux-hardware.org/?probe=ad154077da) | Aug 28, 2023 |
| Dell          | G5 5505                     | Notebook    | [a96b02c261](https://linux-hardware.org/?probe=a96b02c261) | Aug 28, 2023 |
| Dell          | G5 5505                     | Notebook    | [01201d16aa](https://linux-hardware.org/?probe=01201d16aa) | Aug 28, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [e3ca221ba9](https://linux-hardware.org/?probe=e3ca221ba9) | Aug 28, 2023 |
| Dell          | 0RY206                      | Desktop     | [fff4c01588](https://linux-hardware.org/?probe=fff4c01588) | Aug 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e6e9efdb61](https://linux-hardware.org/?probe=e6e9efdb61) | Aug 26, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1f69210d69](https://linux-hardware.org/?probe=1f69210d69) | Aug 25, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [19433fe76f](https://linux-hardware.org/?probe=19433fe76f) | Aug 24, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [475563b8b4](https://linux-hardware.org/?probe=475563b8b4) | Aug 24, 2023 |
| HP            | ProBook 430 G7              | Notebook    | [b8a468626b](https://linux-hardware.org/?probe=b8a468626b) | Aug 24, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [c61948c95e](https://linux-hardware.org/?probe=c61948c95e) | Aug 23, 2023 |
| MSI           | Modern 14 C12M              | Notebook    | [86efcd3eb7](https://linux-hardware.org/?probe=86efcd3eb7) | Aug 21, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [6f1a280aa5](https://linux-hardware.org/?probe=6f1a280aa5) | Aug 21, 2023 |
| ASUSTek       | PRIME N100I-D D4            | Desktop     | [34ef0ea7ff](https://linux-hardware.org/?probe=34ef0ea7ff) | Aug 20, 2023 |
| ASUSTek       | PRIME N100I-D D4            | Desktop     | [101202101b](https://linux-hardware.org/?probe=101202101b) | Aug 19, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d1af143bed](https://linux-hardware.org/?probe=d1af143bed) | Aug 19, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [3223b9a4bb](https://linux-hardware.org/?probe=3223b9a4bb) | Aug 19, 2023 |
| Huanan        | X99-F8D V2.4                | Desktop     | [8af741a2c4](https://linux-hardware.org/?probe=8af741a2c4) | Aug 19, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [a4747bf8ea](https://linux-hardware.org/?probe=a4747bf8ea) | Aug 18, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [2173b6b2b0](https://linux-hardware.org/?probe=2173b6b2b0) | Aug 18, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [63a0a35452](https://linux-hardware.org/?probe=63a0a35452) | Aug 18, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [6b5f510903](https://linux-hardware.org/?probe=6b5f510903) | Aug 18, 2023 |
| HP            | Laptop 14-df0xxx            | Notebook    | [7d3c3dc329](https://linux-hardware.org/?probe=7d3c3dc329) | Aug 17, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [a6ad62b671](https://linux-hardware.org/?probe=a6ad62b671) | Aug 15, 2023 |
| Dell          | 0RY206                      | Desktop     | [f060a8a559](https://linux-hardware.org/?probe=f060a8a559) | Aug 14, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [c24cfbc475](https://linux-hardware.org/?probe=c24cfbc475) | Aug 14, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [6077ff7606](https://linux-hardware.org/?probe=6077ff7606) | Aug 14, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [25f4c96f7b](https://linux-hardware.org/?probe=25f4c96f7b) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [dfae10b78d](https://linux-hardware.org/?probe=dfae10b78d) | Aug 14, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [7ff2052c0f](https://linux-hardware.org/?probe=7ff2052c0f) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [23d9892448](https://linux-hardware.org/?probe=23d9892448) | Aug 13, 2023 |
| Dell          | Latitude E7450              | Notebook    | [057d88b470](https://linux-hardware.org/?probe=057d88b470) | Aug 13, 2023 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [aa4c1f2237](https://linux-hardware.org/?probe=aa4c1f2237) | Aug 13, 2023 |
| Foxconn       | TPS01                       | Desktop     | [8e5b20544d](https://linux-hardware.org/?probe=8e5b20544d) | Aug 13, 2023 |
| AMD           | A690G M2+                   | Desktop     | [4179510c0b](https://linux-hardware.org/?probe=4179510c0b) | Aug 13, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [231f8f9b37](https://linux-hardware.org/?probe=231f8f9b37) | Aug 13, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [13aee7ad4d](https://linux-hardware.org/?probe=13aee7ad4d) | Aug 13, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [6f3ec125fd](https://linux-hardware.org/?probe=6f3ec125fd) | Aug 13, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [ae8c13e17e](https://linux-hardware.org/?probe=ae8c13e17e) | Aug 12, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [3048a8eb60](https://linux-hardware.org/?probe=3048a8eb60) | Aug 12, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [e280c00c8b](https://linux-hardware.org/?probe=e280c00c8b) | Aug 12, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4fe5238f21](https://linux-hardware.org/?probe=4fe5238f21) | Aug 12, 2023 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [73f0314b31](https://linux-hardware.org/?probe=73f0314b31) | Aug 12, 2023 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [d1a19f992d](https://linux-hardware.org/?probe=d1a19f992d) | Aug 12, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [5712d7b72d](https://linux-hardware.org/?probe=5712d7b72d) | Aug 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [46ae462027](https://linux-hardware.org/?probe=46ae462027) | Aug 11, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [2df5a4bd58](https://linux-hardware.org/?probe=2df5a4bd58) | Aug 11, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [1bf7b69b0f](https://linux-hardware.org/?probe=1bf7b69b0f) | Aug 11, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [5cbfb27db2](https://linux-hardware.org/?probe=5cbfb27db2) | Aug 11, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [72b375ad38](https://linux-hardware.org/?probe=72b375ad38) | Aug 11, 2023 |
| NEC Comput... | 312C                        | Desktop     | [770ffcfcf5](https://linux-hardware.org/?probe=770ffcfcf5) | Aug 10, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a5e0e043cb](https://linux-hardware.org/?probe=a5e0e043cb) | Aug 09, 2023 |
| MSI           | 970A-G43 PLUS               | Desktop     | [133d4b58c9](https://linux-hardware.org/?probe=133d4b58c9) | Aug 08, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [ed5ccc8efb](https://linux-hardware.org/?probe=ed5ccc8efb) | Aug 08, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [93e4fee7df](https://linux-hardware.org/?probe=93e4fee7df) | Aug 08, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [ed97e2ea3e](https://linux-hardware.org/?probe=ed97e2ea3e) | Aug 08, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [fb8e926bd4](https://linux-hardware.org/?probe=fb8e926bd4) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [1d6bf926f6](https://linux-hardware.org/?probe=1d6bf926f6) | Aug 05, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [584974f252](https://linux-hardware.org/?probe=584974f252) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | Notebook    | [41b594c2c7](https://linux-hardware.org/?probe=41b594c2c7) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | Notebook    | [ae42e537d2](https://linux-hardware.org/?probe=ae42e537d2) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | Notebook    | [51f2c38666](https://linux-hardware.org/?probe=51f2c38666) | Aug 05, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [570728a351](https://linux-hardware.org/?probe=570728a351) | Aug 05, 2023 |
| Medion        | B360H4-EM V1.0              | Desktop     | [18146f8bc9](https://linux-hardware.org/?probe=18146f8bc9) | Aug 04, 2023 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [767b492aa4](https://linux-hardware.org/?probe=767b492aa4) | Aug 03, 2023 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [47ca08e0d1](https://linux-hardware.org/?probe=47ca08e0d1) | Aug 03, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [9be3b9bb83](https://linux-hardware.org/?probe=9be3b9bb83) | Aug 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [839698eb4c](https://linux-hardware.org/?probe=839698eb4c) | Aug 01, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [5d63b469f8](https://linux-hardware.org/?probe=5d63b469f8) | Aug 01, 2023 |
| HP            | 2B47                        | Desktop     | [06373794be](https://linux-hardware.org/?probe=06373794be) | Aug 01, 2023 |
| Alienware     | x17 R1                      | Notebook    | [bcdf52a63e](https://linux-hardware.org/?probe=bcdf52a63e) | Aug 01, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [51541062dc](https://linux-hardware.org/?probe=51541062dc) | Jul 31, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [4e2e9f1f7f](https://linux-hardware.org/?probe=4e2e9f1f7f) | Jul 31, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [23c9c57a00](https://linux-hardware.org/?probe=23c9c57a00) | Jul 30, 2023 |
| Pine Micro... | Pine64 RockPro64 v2.1       | Soc         | [f9b68dbdc9](https://linux-hardware.org/?probe=f9b68dbdc9) | Jul 30, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [436e1e4e01](https://linux-hardware.org/?probe=436e1e4e01) | Jul 29, 2023 |
| Lenovo        | 1036 SDK0Q40112 WIN 3305... | Desktop     | [731b8aed1b](https://linux-hardware.org/?probe=731b8aed1b) | Jul 29, 2023 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [451cbfaee5](https://linux-hardware.org/?probe=451cbfaee5) | Jul 29, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [24b2f4274d](https://linux-hardware.org/?probe=24b2f4274d) | Jul 29, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [bc3cb3cbfd](https://linux-hardware.org/?probe=bc3cb3cbfd) | Jul 28, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [7e6ad75fc4](https://linux-hardware.org/?probe=7e6ad75fc4) | Jul 28, 2023 |
| ASRock        | X570 PG Velocita            | Desktop     | [ba2f93d0af](https://linux-hardware.org/?probe=ba2f93d0af) | Jul 28, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [27da4128a7](https://linux-hardware.org/?probe=27da4128a7) | Jul 28, 2023 |
| MSI           | TRX40 PRO 10G               | Desktop     | [6391114079](https://linux-hardware.org/?probe=6391114079) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [60d9839bbe](https://linux-hardware.org/?probe=60d9839bbe) | Jul 27, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [4895ec9de1](https://linux-hardware.org/?probe=4895ec9de1) | Jul 27, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [96a30f2f21](https://linux-hardware.org/?probe=96a30f2f21) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [45149f899d](https://linux-hardware.org/?probe=45149f899d) | Jul 26, 2023 |
| Lenovo        | Yoga 14sACH 2021 82MS       | Notebook    | [3cb74490f6](https://linux-hardware.org/?probe=3cb74490f6) | Jul 25, 2023 |
| Gateway       | MS-7399                     | Desktop     | [904775a387](https://linux-hardware.org/?probe=904775a387) | Jul 25, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [c73107bcac](https://linux-hardware.org/?probe=c73107bcac) | Jul 25, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [1aeabb238f](https://linux-hardware.org/?probe=1aeabb238f) | Jul 25, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [290a0dd297](https://linux-hardware.org/?probe=290a0dd297) | Jul 25, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [54377b2911](https://linux-hardware.org/?probe=54377b2911) | Jul 25, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a2fcdf6c36](https://linux-hardware.org/?probe=a2fcdf6c36) | Jul 24, 2023 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [21edb88f94](https://linux-hardware.org/?probe=21edb88f94) | Jul 23, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [5c5147b82d](https://linux-hardware.org/?probe=5c5147b82d) | Jul 23, 2023 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [9c64742080](https://linux-hardware.org/?probe=9c64742080) | Jul 23, 2023 |
| Foxconn       | TPS01                       | Desktop     | [d8e4cab1b8](https://linux-hardware.org/?probe=d8e4cab1b8) | Jul 21, 2023 |
| Gigabyte      | Z590 UD                     | Desktop     | [8504edcacf](https://linux-hardware.org/?probe=8504edcacf) | Jul 21, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [4884c4b183](https://linux-hardware.org/?probe=4884c4b183) | Jul 18, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [3dfd41fda9](https://linux-hardware.org/?probe=3dfd41fda9) | Jul 17, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [c5bee4d8fe](https://linux-hardware.org/?probe=c5bee4d8fe) | Jul 17, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [aac317ef80](https://linux-hardware.org/?probe=aac317ef80) | Jul 17, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [48cf81576d](https://linux-hardware.org/?probe=48cf81576d) | Jul 17, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [cda9e7abe9](https://linux-hardware.org/?probe=cda9e7abe9) | Jul 17, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f4936b2064](https://linux-hardware.org/?probe=f4936b2064) | Jul 17, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [8d8d1d6cbf](https://linux-hardware.org/?probe=8d8d1d6cbf) | Jul 17, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [b86a3c24df](https://linux-hardware.org/?probe=b86a3c24df) | Jul 16, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [1f1b7763a5](https://linux-hardware.org/?probe=1f1b7763a5) | Jul 14, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [c8179fd349](https://linux-hardware.org/?probe=c8179fd349) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP34... | Convertible | [be7dcafaba](https://linux-hardware.org/?probe=be7dcafaba) | Jul 14, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [a5cdc8bb58](https://linux-hardware.org/?probe=a5cdc8bb58) | Jul 13, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [26c6ceb0a6](https://linux-hardware.org/?probe=26c6ceb0a6) | Jul 13, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | Notebook    | [0d54b47098](https://linux-hardware.org/?probe=0d54b47098) | Jul 12, 2023 |
| Fujitsu       | LIFEBOOK T939               | Convertible | [4d1ecd77ad](https://linux-hardware.org/?probe=4d1ecd77ad) | Jul 11, 2023 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [2a37881afa](https://linux-hardware.org/?probe=2a37881afa) | Jul 11, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [7256e6a7b2](https://linux-hardware.org/?probe=7256e6a7b2) | Jul 11, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [ab32a0e447](https://linux-hardware.org/?probe=ab32a0e447) | Jul 11, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [38420a6afe](https://linux-hardware.org/?probe=38420a6afe) | Jul 10, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [14c6f3f286](https://linux-hardware.org/?probe=14c6f3f286) | Jul 10, 2023 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [89dc06fa6d](https://linux-hardware.org/?probe=89dc06fa6d) | Jul 09, 2023 |
| ASRock        | Z390 Extreme4               | Desktop     | [cf9ad63ff9](https://linux-hardware.org/?probe=cf9ad63ff9) | Jul 09, 2023 |
| ASRock        | Z390 Extreme4               | Desktop     | [306eaba8f1](https://linux-hardware.org/?probe=306eaba8f1) | Jul 09, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [0b6dcc1ea9](https://linux-hardware.org/?probe=0b6dcc1ea9) | Jul 09, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [ca41a9886a](https://linux-hardware.org/?probe=ca41a9886a) | Jul 09, 2023 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [4b611c264e](https://linux-hardware.org/?probe=4b611c264e) | Jul 08, 2023 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [8cccaeb0ed](https://linux-hardware.org/?probe=8cccaeb0ed) | Jul 08, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [a760e46715](https://linux-hardware.org/?probe=a760e46715) | Jul 08, 2023 |
| Fujitsu       | LIFEBOOK U758               | Notebook    | [eaa8bbf9da](https://linux-hardware.org/?probe=eaa8bbf9da) | Jul 07, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [1a53ce97b8](https://linux-hardware.org/?probe=1a53ce97b8) | Jul 07, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [9a6e78196d](https://linux-hardware.org/?probe=9a6e78196d) | Jul 06, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [b4b26d2f53](https://linux-hardware.org/?probe=b4b26d2f53) | Jul 06, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | Notebook    | [84b5d3ce3c](https://linux-hardware.org/?probe=84b5d3ce3c) | Jul 06, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [348b9a4a73](https://linux-hardware.org/?probe=348b9a4a73) | Jul 05, 2023 |
| Aierben       | NA17                        | Desktop     | [462b502bab](https://linux-hardware.org/?probe=462b502bab) | Jul 05, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [f4fdc8a532](https://linux-hardware.org/?probe=f4fdc8a532) | Jul 05, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [49bcd116ba](https://linux-hardware.org/?probe=49bcd116ba) | Jul 04, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [67281face4](https://linux-hardware.org/?probe=67281face4) | Jul 03, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f928781025](https://linux-hardware.org/?probe=f928781025) | Jul 03, 2023 |
| Jumper        | EZbook                      | Notebook    | [735e20e770](https://linux-hardware.org/?probe=735e20e770) | Jul 02, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [68daff498d](https://linux-hardware.org/?probe=68daff498d) | Jul 02, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [f587b9a46c](https://linux-hardware.org/?probe=f587b9a46c) | Jul 02, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [465b44efff](https://linux-hardware.org/?probe=465b44efff) | Jul 01, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [826e649d7a](https://linux-hardware.org/?probe=826e649d7a) | Jul 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a0ac212cac](https://linux-hardware.org/?probe=a0ac212cac) | Jul 01, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [0f0e96b03c](https://linux-hardware.org/?probe=0f0e96b03c) | Jul 01, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [a0fdd16a9e](https://linux-hardware.org/?probe=a0fdd16a9e) | Jul 01, 2023 |
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
| Lenovo        | Yoga 2 13 20344             | Notebook    | [eab5787d6a](https://linux-hardware.org/?probe=eab5787d6a) | Jun 11, 2023 |
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

...

See full list of test cases in the file [Test_Cases.md](</Dist/Gentoo/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Gentoo 2.7     | 556       | 31.41%  |
| Gentoo 2.6     | 413       | 23.33%  |
| Gentoo 2.8     | 306       | 17.29%  |
| Gentoo 2.13    | 239       | 13.5%   |
| Gentoo 2.9     | 159       | 8.98%   |
| Gentoo 2.14    | 44        | 2.49%   |
| Gentoo 2.4.1   | 14        | 0.79%   |
| Gentoo         | 11        | 0.62%   |
| Gentoo 2.3     | 9         | 0.51%   |
| Gentoo 2.2     | 7         | 0.4%    |
| Gentoo 1       | 3         | 0.17%   |
| Gentoo 23      | 2         | 0.11%   |
| Gentoo 22.0.1  | 2         | 0.11%   |
| Gentoo Pelikan | 1         | 0.06%   |
| Gentoo 22      | 1         | 0.06%   |
| Gentoo 2022    | 1         | 0.06%   |
| Gentoo 2.1     | 1         | 0.06%   |
| Gentoo 13.0    | 1         | 0.06%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Gentoo | 1537      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.38-gentoo            | 26        | 1.25%   |
| 5.10.27-gentoo           | 25        | 1.21%   |
| 5.10.61-gentoo           | 23        | 1.11%   |
| 5.15.32-gentoo-r1        | 18        | 0.87%   |
| 6.1.12-gentoo            | 16        | 0.77%   |
| 5.15.80-gentoo-x86_64    | 16        | 0.77%   |
| 5.15.80-gentoo           | 16        | 0.77%   |
| 6.1.19-gentoo-x86_64     | 15        | 0.72%   |
| 5.4.80-gentoo-r1         | 15        | 0.72%   |
| 5.4.48-gentoo            | 15        | 0.72%   |
| 5.4.97-gentoo            | 14        | 0.68%   |
| 5.4.28-gentoo            | 14        | 0.68%   |
| 5.10.76-gentoo-r1        | 14        | 0.68%   |
| 6.1.19-gentoo            | 13        | 0.63%   |
| 5.15.75-gentoo-x86_64    | 13        | 0.63%   |
| 5.10.61-gentoo-x86_64    | 13        | 0.63%   |
| 5.10.27-gentoo-x86_64    | 13        | 0.63%   |
| 5.15.59-gentoo-x86_64    | 12        | 0.58%   |
| 5.15.32-gentoo-r1-x86_64 | 12        | 0.58%   |
| 5.10.52-gentoo           | 12        | 0.58%   |
| 5.7.0-gentoo             | 11        | 0.53%   |
| 5.4.60-gentoo            | 11        | 0.53%   |
| 5.15.88-gentoo           | 11        | 0.53%   |
| 5.4.38-gentoo-x86_64     | 10        | 0.48%   |
| 6.1.31-gentoo-dist       | 9         | 0.43%   |
| 6.1.12-gentoo-x86_64     | 9         | 0.43%   |
| 5.15.75-gentoo           | 9         | 0.43%   |
| 5.15.59-gentoo           | 9         | 0.43%   |
| 5.15.52-gentoo-x86_64    | 9         | 0.43%   |
| 5.15.52-gentoo           | 9         | 0.43%   |
| 5.15.41-gentoo-x86_64    | 9         | 0.43%   |
| 5.10.76-gentoo-r1-x86_64 | 9         | 0.43%   |
| 6.1.41-gentoo-dist       | 8         | 0.39%   |
| 6.1.41-gentoo            | 8         | 0.39%   |
| 5.6.15-gentoo            | 8         | 0.39%   |
| 5.4.66-gentoo            | 8         | 0.39%   |
| 5.4.48-gentoo-x86_64     | 8         | 0.39%   |
| 5.15.69-gentoo           | 8         | 0.39%   |
| 5.15.41-gentoo           | 8         | 0.39%   |
| 4.19.86-gentoo           | 8         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.27 | 46        | 2.22%   |
| 5.4.38  | 45        | 2.17%   |
| 5.15.32 | 41        | 1.98%   |
| 5.10.61 | 39        | 1.88%   |
| 6.1.19  | 36        | 1.74%   |
| 6.1.12  | 35        | 1.69%   |
| 5.15.80 | 34        | 1.64%   |
| 5.4.48  | 33        | 1.59%   |
| 5.10.76 | 32        | 1.55%   |
| 5.15.75 | 30        | 1.45%   |
| 5.15.59 | 26        | 1.26%   |
| 6.1.31  | 25        | 1.21%   |
| 5.4.97  | 25        | 1.21%   |
| 5.4.28  | 25        | 1.21%   |
| 5.15.52 | 24        | 1.16%   |
| 5.10.52 | 24        | 1.16%   |
| 5.15.41 | 23        | 1.11%   |
| 5.4.80  | 22        | 1.06%   |
| 6.1.41  | 19        | 0.92%   |
| 5.15.11 | 19        | 0.92%   |
| 5.4.66  | 17        | 0.82%   |
| 5.15.88 | 17        | 0.82%   |
| 5.6.15  | 16        | 0.77%   |
| 5.4.60  | 16        | 0.77%   |
| 5.17.1  | 16        | 0.77%   |
| 5.15.72 | 16        | 0.77%   |
| 5.15.69 | 16        | 0.77%   |
| 6.1.38  | 15        | 0.72%   |
| 5.7.0   | 15        | 0.72%   |
| 5.15.23 | 15        | 0.72%   |
| 5.4.72  | 13        | 0.63%   |
| 4.19.97 | 13        | 0.63%   |
| 6.2.11  | 12        | 0.58%   |
| 6.0.0   | 12        | 0.58%   |
| 5.9.11  | 12        | 0.58%   |
| 5.19.0  | 12        | 0.58%   |
| 5.15.74 | 12        | 0.58%   |
| 5.15.26 | 12        | 0.58%   |
| 5.15.10 | 12        | 0.58%   |
| 6.3.1   | 10        | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 334       | 17.59%  |
| 5.4     | 230       | 12.11%  |
| 5.10    | 226       | 11.9%   |
| 6.1     | 190       | 10.01%  |
| 4.19    | 66        | 3.48%   |
| 5.6     | 64        | 3.37%   |
| 5.9     | 58        | 3.05%   |
| 6.2     | 54        | 2.84%   |
| 5.8     | 54        | 2.84%   |
| 5.14    | 50        | 2.63%   |
| 5.7     | 49        | 2.58%   |
| 5.17    | 49        | 2.58%   |
| 5.16    | 49        | 2.58%   |
| 6.0     | 45        | 2.37%   |
| 6.3     | 41        | 2.16%   |
| 5.18    | 41        | 2.16%   |
| 5.11    | 41        | 2.16%   |
| 6.4     | 37        | 1.95%   |
| 5.19    | 36        | 1.9%    |
| 5.13    | 36        | 1.9%    |
| 5.12    | 30        | 1.58%   |
| 5.5     | 17        | 0.9%    |
| 4.14    | 17        | 0.9%    |
| 5.2     | 12        | 0.63%   |
| 5.1     | 10        | 0.53%   |
| 5.3     | 9         | 0.47%   |
| 5.0     | 9         | 0.47%   |
| 4.9     | 8         | 0.42%   |
| 4.4     | 8         | 0.42%   |
| 6.5     | 7         | 0.37%   |
| 4.18    | 7         | 0.37%   |
| 4.6     | 3         | 0.16%   |
| 4.12    | 3         | 0.16%   |
| 4.20    | 2         | 0.11%   |
| 4.10    | 2         | 0.11%   |
| 4.5     | 1         | 0.05%   |
| 4.16    | 1         | 0.05%   |
| 4.13    | 1         | 0.05%   |
| 4.1     | 1         | 0.05%   |
| 3.18    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| x86_64      | 1472      | 95.77%  |
| i686        | 31        | 2.02%   |
| aarch64     | 14        | 0.91%   |
| ppc         | 7         | 0.46%   |
| armv7l      | 3         | 0.2%    |
| armv6l      | 3         | 0.2%    |
| loongarch64 | 2         | 0.13%   |
| armv5tel    | 2         | 0.13%   |
| riscv64     | 1         | 0.07%   |
| ppc64le     | 1         | 0.07%   |
| ppc64       | 1         | 0.07%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 693       | 41.9%   |
| KDE5           | 356       | 21.52%  |
| GNOME          | 205       | 12.39%  |
| XFCE           | 149       | 9.01%   |
| KDE            | 60        | 3.63%   |
| MATE           | 43        | 2.6%    |
| DWM            | 27        | 1.63%   |
| LXQt           | 17        | 1.03%   |
| sway           | 14        | 0.85%   |
| i3             | 12        | 0.73%   |
| X-Cinnamon     | 10        | 0.6%    |
| Hyprland       | 9         | 0.54%   |
| Enlightenment  | 8         | 0.48%   |
| LXDE           | 7         | 0.42%   |
| awesome        | 7         | 0.42%   |
| Xsession       | 6         | 0.36%   |
| Cinnamon       | 6         | 0.36%   |
| openbox        | 4         | 0.24%   |
| bspwm          | 4         | 0.24%   |
| Trinity        | 3         | 0.18%   |
| Unity          | 2         | 0.12%   |
| GNOME Classic  | 2         | 0.12%   |
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

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 881       | 53.01%  |
| Unknown | 315       | 18.95%  |
| Tty     | 259       | 15.58%  |
| Wayland | 207       | 12.45%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 769       | 47.68%  |
| SDDM    | 421       | 26.1%   |
| LightDM | 182       | 11.28%  |
| GDM     | 147       | 9.11%   |
| SLiM    | 28        | 1.74%   |
| XDM     | 27        | 1.67%   |
| LXDM    | 19        | 1.18%   |
| GREETD  | 11        | 0.68%   |
| TDM     | 7         | 0.43%   |
| KDM     | 1         | 0.06%   |
| GDM3    | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 598       | 36.94%  |
| Unknown    | 239       | 14.76%  |
| C.UTF8     | 149       | 9.2%    |
| en_GB      | 102       | 6.3%    |
| de_DE      | 100       | 6.18%   |
| ru_RU      | 68        | 4.2%    |
| C          | 43        | 2.66%   |
| fr_FR      | 31        | 1.91%   |
| es_ES      | 23        | 1.42%   |
| it_IT      | 22        | 1.36%   |
| en_CA      | 22        | 1.36%   |
| cs_CZ      | 21        | 1.3%    |
| en_AU      | 18        | 1.11%   |
| pl_PL      | 17        | 1.05%   |
| pt_BR      | 12        | 0.74%   |
| zh_CN      | 10        | 0.62%   |
| en_IE      | 10        | 0.62%   |
| sv_SE      | 7         | 0.43%   |
| nl_NL      | 7         | 0.43%   |
| ru_RU.UTF8 | 6         | 0.37%   |
| POSIX      | 6         | 0.37%   |
| en_US.UTF8 | 6         | 0.37%   |
| el_GR      | 6         | 0.37%   |
| nl_BE      | 5         | 0.31%   |
| ja_JP      | 5         | 0.31%   |
| fi_FI      | 5         | 0.31%   |
| ca_ES      | 5         | 0.31%   |
| uk_UA      | 4         | 0.25%   |
| fr_CA      | 4         | 0.25%   |
| es_AR      | 4         | 0.25%   |
| de_CH      | 4         | 0.25%   |
| zh_TW      | 3         | 0.19%   |
| ro_RO      | 3         | 0.19%   |
| es_MX      | 3         | 0.19%   |
| es_CL      | 3         | 0.19%   |
| en_ZA      | 3         | 0.19%   |
| ru_UA      | 2         | 0.12%   |
| pt_PT      | 2         | 0.12%   |
| mi_NZ      | 2         | 0.12%   |
| ko_KR      | 2         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1126      | 71.77%  |
| BIOS | 443       | 28.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 934       | 59.41%  |
| Btrfs    | 366       | 23.28%  |
| Xfs      | 62        | 3.94%   |
| F2fs     | 57        | 3.63%   |
| Zfs      | 55        | 3.5%    |
| Unknown  | 46        | 2.93%   |
| XXXXXXX  | 21        | 1.34%   |
| Reiserfs | 17        | 1.08%   |
| Overlay  | 3         | 0.19%   |
| Jfs      | 3         | 0.19%   |
| Ext3     | 3         | 0.19%   |
| XXX      | 2         | 0.13%   |
| Xtrfs    | 1         | 0.06%   |
| Ext2     | 1         | 0.06%   |
| Bcachefs | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1297      | 83.14%  |
| MBR     | 178       | 11.41%  |
| Unknown | 85        | 5.45%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1094      | 67.87%  |
| Yes       | 518       | 32.13%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1056      | 66.88%  |
| Yes       | 523       | 33.12%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 345       | 22.45%  |
| Lenovo                  | 225       | 14.64%  |
| Dell                    | 148       | 9.63%   |
| Hewlett-Packard         | 138       | 8.98%   |
| MSI                     | 131       | 8.52%   |
| Gigabyte Technology     | 105       | 6.83%   |
| ASRock                  | 91        | 5.92%   |
| Acer                    | 48        | 3.12%   |
| Intel                   | 29        | 1.89%   |
| Unknown                 | 29        | 1.89%   |
| Apple                   | 28        | 1.82%   |
| Supermicro              | 21        | 1.37%   |
| Raspberry Pi Foundation | 14        | 0.91%   |
| Fujitsu                 | 13        | 0.85%   |
| Timi                    | 12        | 0.78%   |
| HUAWEI                  | 12        | 0.78%   |
| Samsung Electronics     | 11        | 0.72%   |
| Toshiba                 | 9         | 0.59%   |
| TUXEDO                  | 7         | 0.46%   |
| Razer                   | 5         | 0.33%   |
| IBM                     | 5         | 0.33%   |
| Google                  | 5         | 0.33%   |
| ASRockRack              | 5         | 0.33%   |
| TYAN Computer           | 4         | 0.26%   |
| System76                | 4         | 0.26%   |
| Notebook                | 4         | 0.26%   |
| Alienware               | 4         | 0.26%   |
| Tekram Technology       | 3         | 0.2%    |
| Sony                    | 3         | 0.2%    |
| Pegatron                | 3         | 0.2%    |
| Medion                  | 3         | 0.2%    |
| Framework               | 3         | 0.2%    |
| Foxconn                 | 3         | 0.2%    |
| ZOTAC                   | 2         | 0.13%   |
| win element             | 2         | 0.13%   |
| Valve                   | 2         | 0.13%   |
| Star Labs               | 2         | 0.13%   |
| Schenker                | 2         | 0.13%   |
| Purism                  | 2         | 0.13%   |
| Positivo                | 2         | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 36        | 2.34%   |
| ASUS All Series                       | 21        | 1.37%   |
| ASUS TUF Gaming X570-PLUS             | 12        | 0.78%   |
| Supermicro Super Server               | 9         | 0.59%   |
| ASUS PRIME X570-PRO                   | 8         | 0.52%   |
| MSI MS-7C02                           | 7         | 0.46%   |
| ASUS ROG STRIX X570-E GAMING          | 7         | 0.46%   |
| ASUS PRIME X470-PRO                   | 7         | 0.46%   |
| MSI MS-7A38                           | 6         | 0.39%   |
| Dell XPS 15 9570                      | 6         | 0.39%   |
| ASUS ROG Strix G513QY_G513QY          | 6         | 0.39%   |
| ASUS PRIME X370-PRO                   | 6         | 0.39%   |
| MSI MS-7C37                           | 5         | 0.33%   |
| MSI MS-7C35                           | 5         | 0.33%   |
| HP Pavilion Notebook                  | 5         | 0.33%   |
| HP OMEN by Laptop                     | 5         | 0.33%   |
| ASUS TUF GAMING B550-PLUS             | 5         | 0.33%   |
| ASUS ROG STRIX B450-F GAMING          | 5         | 0.33%   |
| ASUS ROG CROSSHAIR VIII HERO          | 5         | 0.33%   |
| ASUS PRIME X570-P                     | 5         | 0.33%   |
| ASRock B450 Pro4                      | 5         | 0.33%   |
| MSI MS-7C91                           | 4         | 0.26%   |
| MSI MS-7B89                           | 4         | 0.26%   |
| MSI MS-7B86                           | 4         | 0.26%   |
| MSI MS-7B79                           | 4         | 0.26%   |
| HP Pavilion Gaming Laptop 15-ec1xxx   | 4         | 0.26%   |
| HP Laptop 14-dk1xxx                   | 4         | 0.26%   |
| Dell XPS 17 9710                      | 4         | 0.26%   |
| Dell XPS 15 7590                      | 4         | 0.26%   |
| Dell XPS 13 9310                      | 4         | 0.26%   |
| ASUS Z170 PRO GAMING                  | 4         | 0.26%   |
| ASUS ROG Zephyrus G14 GA401II_GA401II | 4         | 0.26%   |
| ASUS ROG STRIX B550-F GAMING          | 4         | 0.26%   |
| ASUS ROG CROSSHAIR VIII DARK HERO     | 4         | 0.26%   |
| ASUS ROG CROSSHAIR VII HERO           | 4         | 0.26%   |
| ASUS PRIME B450M-A                    | 4         | 0.26%   |
| ASUS M4A89GTD-PRO/USB3                | 4         | 0.26%   |
| ASRock X570 Taichi                    | 4         | 0.26%   |
| ASRock B550M Steel Legend             | 4         | 0.26%   |
| TYAN S7025                            | 3         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 126       | 8.2%    |
| ASUS ROG          | 90        | 5.86%   |
| ASUS PRIME        | 59        | 3.84%   |
| Dell Latitude     | 43        | 2.8%    |
| ASUS TUF          | 42        | 2.73%   |
| Dell XPS          | 41        | 2.67%   |
| Unknown           | 36        | 2.34%   |
| Acer Aspire       | 28        | 1.82%   |
| Lenovo IdeaPad    | 27        | 1.76%   |
| HP Pavilion       | 26        | 1.69%   |
| Lenovo Legion     | 25        | 1.63%   |
| HP EliteBook      | 22        | 1.43%   |
| ASUS All          | 21        | 1.37%   |
| Dell Inspiron     | 20        | 1.3%    |
| Lenovo Yoga       | 18        | 1.17%   |
| Dell Precision    | 17        | 1.11%   |
| HP Laptop         | 16        | 1.04%   |
| RPi Raspberry     | 14        | 0.91%   |
| ASRock X570       | 13        | 0.85%   |
| HP OMEN           | 12        | 0.78%   |
| HP ProBook        | 11        | 0.72%   |
| Gigabyte X570     | 11        | 0.72%   |
| Dell OptiPlex     | 10        | 0.65%   |
| ASUS VivoBook     | 10        | 0.65%   |
| Supermicro Super  | 9         | 0.59%   |
| Gigabyte B450M    | 8         | 0.52%   |
| Gigabyte B450     | 8         | 0.52%   |
| ASUS ZenBook      | 8         | 0.52%   |
| ASRock X370       | 8         | 0.52%   |
| Acer Swift        | 8         | 0.52%   |
| Toshiba Satellite | 7         | 0.46%   |
| Timi RedmiBook    | 7         | 0.46%   |
| MSI MS-7C02       | 7         | 0.46%   |
| HP ZBook          | 7         | 0.46%   |
| HP ProLiant       | 7         | 0.46%   |
| Acer Nitro        | 7         | 0.46%   |
| MSI MS-7A38       | 6         | 0.39%   |
| HP ENVY           | 6         | 0.39%   |
| HP Compaq         | 6         | 0.39%   |
| ASUS ASUS         | 6         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 241       | 15.68%  |
| 2020    | 206       | 13.4%   |
| 2018    | 192       | 12.49%  |
| 2021    | 162       | 10.54%  |
| 2017    | 95        | 6.18%   |
| 2022    | 81        | 5.27%   |
| 2012    | 74        | 4.81%   |
| 2015    | 72        | 4.68%   |
| 2014    | 60        | 3.9%    |
| 2016    | 59        | 3.84%   |
| 2013    | 58        | 3.77%   |
| 2011    | 50        | 3.25%   |
| 2010    | 44        | 2.86%   |
| 2008    | 32        | 2.08%   |
| Unknown | 32        | 2.08%   |
| 2009    | 29        | 1.89%   |
| 2023    | 14        | 0.91%   |
| 2007    | 11        | 0.72%   |
| 2006    | 7         | 0.46%   |
| 2005    | 5         | 0.33%   |
| 2004    | 5         | 0.33%   |
| 2003    | 4         | 0.26%   |
| 2000    | 3         | 0.2%    |
| 2002    | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 719       | 46.78%  |
| Desktop        | 695       | 45.22%  |
| Server         | 39        | 2.54%   |
| Convertible    | 38        | 2.47%   |
| System on chip | 18        | 1.17%   |
| Mini pc        | 16        | 1.04%   |
| All in one     | 7         | 0.46%   |
| Tablet         | 3         | 0.2%    |
| Phone          | 1         | 0.07%   |
| Stick pc       | 1         | 0.07%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1513      | 98.12%  |
| Enabled  | 29        | 1.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1525      | 99.22%  |
| Yes  | 12        | 0.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 378       | 23.91%  |
| 16.01-24.0      | 373       | 23.59%  |
| 8.01-16.0       | 244       | 15.43%  |
| 4.01-8.0        | 190       | 12.02%  |
| 64.01-256.0     | 168       | 10.63%  |
| 3.01-4.0        | 86        | 5.44%   |
| 24.01-32.0      | 63        | 3.98%   |
| 1.01-2.0        | 29        | 1.83%   |
| 0.51-1.0        | 20        | 1.27%   |
| 2.01-3.0        | 19        | 1.2%    |
| 0.01-0.5        | 8         | 0.51%   |
| More than 256.0 | 3         | 0.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 373       | 20.17%  |
| 4.01-8.0    | 349       | 18.88%  |
| 2.01-3.0    | 315       | 17.04%  |
| 3.01-4.0    | 206       | 11.14%  |
| 8.01-16.0   | 189       | 10.22%  |
| 0.01-0.5    | 178       | 9.63%   |
| 0.51-1.0    | 158       | 8.55%   |
| 16.01-24.0  | 46        | 2.49%   |
| 32.01-64.0  | 15        | 0.81%   |
| 24.01-32.0  | 13        | 0.7%    |
| 64.01-256.0 | 4         | 0.22%   |
| 0           | 3         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 713       | 44.04%  |
| 2      | 422       | 26.07%  |
| 3      | 186       | 11.49%  |
| 4      | 108       | 6.67%   |
| 5      | 78        | 4.82%   |
| 6      | 36        | 2.22%   |
| 7      | 29        | 1.79%   |
| 8      | 13        | 0.8%    |
| 0      | 12        | 0.74%   |
| 9      | 5         | 0.31%   |
| 13     | 4         | 0.25%   |
| 10     | 4         | 0.25%   |
| 12     | 3         | 0.19%   |
| 21     | 2         | 0.12%   |
| 26     | 1         | 0.06%   |
| 18     | 1         | 0.06%   |
| 17     | 1         | 0.06%   |
| 11     | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1227      | 78.5%   |
| Yes       | 336       | 21.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1336      | 86.25%  |
| No        | 213       | 13.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1060      | 68.56%  |
| No        | 486       | 31.44%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 980       | 62.82%  |
| No        | 580       | 37.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 328       | 21.05%  |
| Germany      | 221       | 14.18%  |
| Russia       | 136       | 8.73%   |
| UK           | 80        | 5.13%   |
| France       | 68        | 4.36%   |
| Canada       | 61        | 3.92%   |
| Spain        | 51        | 3.27%   |
| Poland       | 49        | 3.15%   |
| China        | 47        | 3.02%   |
| Czechia      | 37        | 2.37%   |
| Australia    | 34        | 2.18%   |
| Sweden       | 33        | 2.12%   |
| Italy        | 33        | 2.12%   |
| Netherlands  | 32        | 2.05%   |
| Finland      | 29        | 1.86%   |
| Ukraine      | 22        | 1.41%   |
| Brazil       | 21        | 1.35%   |
| Switzerland  | 18        | 1.16%   |
| Greece       | 16        | 1.03%   |
| Belgium      | 16        | 1.03%   |
| Mexico       | 13        | 0.83%   |
| Japan        | 13        | 0.83%   |
| Austria      | 12        | 0.77%   |
| Turkey       | 11        | 0.71%   |
| Romania      | 11        | 0.71%   |
| Norway       | 11        | 0.71%   |
| Belarus      | 10        | 0.64%   |
| India        | 9         | 0.58%   |
| Hungary      | 9         | 0.58%   |
| Hong Kong    | 9         | 0.58%   |
| Slovakia     | 8         | 0.51%   |
| Taiwan       | 7         | 0.45%   |
| Argentina    | 7         | 0.45%   |
| Portugal     | 6         | 0.39%   |
| Vietnam      | 5         | 0.32%   |
| South Africa | 5         | 0.32%   |
| Slovenia     | 5         | 0.32%   |
| New Zealand  | 5         | 0.32%   |
| Denmark      | 5         | 0.32%   |
| Lithuania    | 4         | 0.26%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 55        | 3.21%   |
| Moscow            | 46        | 2.68%   |
| St Petersburg     | 21        | 1.22%   |
| Sydney            | 17        | 0.99%   |
| Warsaw            | 16        | 0.93%   |
| Athens            | 16        | 0.93%   |
| Munich            | 14        | 0.82%   |
| Paris             | 13        | 0.76%   |
| Helsinki          | 13        | 0.76%   |
| Vancouver         | 12        | 0.7%    |
| Los Angeles       | 12        | 0.7%    |
| Frankfurt am Main | 12        | 0.7%    |
| Amsterdam         | 12        | 0.7%    |
| Milan             | 10        | 0.58%   |
| Kyiv              | 10        | 0.58%   |
| Cieszyn           | 10        | 0.58%   |
| Vladivostok       | 9         | 0.52%   |
| Prague            | 9         | 0.52%   |
| Guangzhou         | 9         | 0.52%   |
| Beijing           | 9         | 0.52%   |
| Wuelfrath         | 8         | 0.47%   |
| Seattle           | 8         | 0.47%   |
| Melbourne         | 8         | 0.47%   |
| Sao Paulo         | 7         | 0.41%   |
| Oulu              | 7         | 0.41%   |
| Ottawa            | 7         | 0.41%   |
| Minsk             | 7         | 0.41%   |
| Bothell           | 7         | 0.41%   |
| Barcelona         | 7         | 0.41%   |
| Zurich            | 6         | 0.35%   |
| Woolwich          | 6         | 0.35%   |
| Weatherford       | 6         | 0.35%   |
| Vienna            | 6         | 0.35%   |
| Stockholm         | 6         | 0.35%   |
| Sterling          | 6         | 0.35%   |
| Perth             | 6         | 0.35%   |
| New York          | 6         | 0.35%   |
| Manitowoc         | 6         | 0.35%   |
| London            | 6         | 0.35%   |
| Hamburg           | 6         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 578       | 1186   | 21.88%  |
| WDC                         | 428       | 961    | 16.2%   |
| Seagate                     | 319       | 693    | 12.07%  |
| SanDisk                     | 136       | 197    | 5.15%   |
| Kingston                    | 127       | 179    | 4.81%   |
| Toshiba                     | 125       | 212    | 4.73%   |
| Intel                       | 117       | 192    | 4.43%   |
| Crucial                     | 81        | 147    | 3.07%   |
| SK hynix                    | 72        | 88     | 2.73%   |
| Unknown                     | 67        | 95     | 2.54%   |
| Hitachi                     | 62        | 169    | 2.35%   |
| HGST                        | 58        | 99     | 2.2%    |
| Micron Technology           | 42        | 56     | 1.59%   |
| A-DATA Technology           | 39        | 56     | 1.48%   |
| Phison Electronics          | 28        | 39     | 1.06%   |
| KIOXIA                      | 22        | 29     | 0.83%   |
| Phison                      | 21        | 32     | 0.79%   |
| Corsair                     | 19        | 34     | 0.72%   |
| OCZ                         | 17        | 25     | 0.64%   |
| Kingston Technology Company | 15        | 16     | 0.57%   |
| China                       | 14        | 38     | 0.53%   |
| Micron/Crucial Technology   | 13        | 17     | 0.49%   |
| Apple                       | 12        | 14     | 0.45%   |
| GOODRAM                     | 11        | 54     | 0.42%   |
| Silicon Motion              | 10        | 17     | 0.38%   |
| Transcend                   | 8         | 13     | 0.3%    |
| PNY                         | 8         | 12     | 0.3%    |
| Fujitsu                     | 8         | 11     | 0.3%    |
| XPG                         | 7         | 14     | 0.26%   |
| SPCC                        | 7         | 8      | 0.26%   |
| Realtek Semiconductor       | 7         | 15     | 0.26%   |
| Plextor                     | 7         | 8      | 0.26%   |
| Patriot                     | 7         | 11     | 0.26%   |
| ADATA Technology            | 7         | 9      | 0.26%   |
| Mushkin                     | 6         | 6      | 0.23%   |
| LITEONIT                    | 6         | 8      | 0.23%   |
| Team                        | 5         | 12     | 0.19%   |
| LITEON                      | 5         | 9      | 0.19%   |
| IBM                         | 5         | 6      | 0.19%   |
| Apacer                      | 5         | 7      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 65        | 2.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 45        | 1.41%   |
| Samsung SSD 860 EVO 1TB                               | 30        | 0.94%   |
| Samsung SSD 850 EVO 250GB                             | 29        | 0.91%   |
| HGST HTS721010A9E630 1TB                              | 25        | 0.79%   |
| Samsung SSD 860 EVO 500GB                             | 24        | 0.75%   |
| WDC WD30EFRX-68EUZN0 3TB                              | 22        | 0.69%   |
| Samsung SSD 850 EVO 500GB                             | 22        | 0.69%   |
| Kingston SA400S37240G 240GB SSD                       | 22        | 0.69%   |
| Samsung SSD 980 1TB                                   | 20        | 0.63%   |
| Samsung SSD 970 EVO Plus 500GB                        | 19        | 0.6%    |
| Samsung SSD 860 EVO 250GB                             | 19        | 0.6%    |
| Seagate ST1000DM010-2EP102 1TB                        | 18        | 0.57%   |
| Seagate ST4000DM004-2CV104 4TB                        | 15        | 0.47%   |
| Samsung SSD 970 EVO Plus 1TB                          | 15        | 0.47%   |
| Samsung SSD 970 EVO 500GB                             | 15        | 0.47%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 13        | 0.41%   |
| Unknown MMC Card  32GB                                | 13        | 0.41%   |
| Seagate ST2000DM008-2FR102 2TB                        | 13        | 0.41%   |
| Seagate ST2000DM001-1ER164 2TB                        | 13        | 0.41%   |
| Samsung SSD 970 EVO 250GB                             | 13        | 0.41%   |
| Samsung SSD 970 EVO 1TB                               | 13        | 0.41%   |
| Kingston SA400S37480G 480GB SSD                       | 13        | 0.41%   |
| Crucial CT1000MX500SSD1 1TB                           | 13        | 0.41%   |
| Seagate ST500DM002-1BD142 500GB                       | 12        | 0.38%   |
| Seagate ST2000DM006-2DM164 2TB                        | 12        | 0.38%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                  | 12        | 0.38%   |
| Samsung SSD 980 PRO 1TB                               | 12        | 0.38%   |
| Samsung SSD 870 EVO 1TB                               | 12        | 0.38%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 11        | 0.35%   |
| WDC WD40EZRZ-00GXCB0 4TB                              | 11        | 0.35%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 11        | 0.35%   |
| Samsung SSD 970 PRO 512GB                             | 11        | 0.35%   |
| Samsung SSD 840 EVO 250GB                             | 11        | 0.35%   |
| Samsung SSD 840 EVO 120GB                             | 11        | 0.35%   |
| Kingston SA400S37120G 120GB SSD                       | 11        | 0.35%   |
| Intel SSDPEKNW010T8 1TB                               | 11        | 0.35%   |
| Intel SSD 660P Series 512GB                           | 11        | 0.35%   |
| WDC WD20EFRX-68EUZN0 2TB                              | 10        | 0.31%   |
| Unknown MMC Card  128GB                               | 10        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 322       | 772    | 35.7%   |
| Seagate             | 310       | 677    | 34.37%  |
| Toshiba             | 85        | 160    | 9.42%   |
| Hitachi             | 62        | 169    | 6.87%   |
| HGST                | 58        | 99     | 6.43%   |
| Samsung Electronics | 28        | 42     | 3.1%    |
| Fujitsu             | 8         | 11     | 0.89%   |
| IBM                 | 5         | 6      | 0.55%   |
| Unknown             | 4         | 5      | 0.44%   |
| IBM/Hitachi         | 3         | 4      | 0.33%   |
| MDT                 | 2         | 2      | 0.22%   |
| Maxtor              | 2         | 2      | 0.22%   |
| LaCie               | 2         | 12     | 0.22%   |
| Apple               | 2         | 2      | 0.22%   |
| Teleplan            | 1         | 3      | 0.11%   |
| SABRENT             | 1         | 1      | 0.11%   |
| HGST HTS            | 1         | 1      | 0.11%   |
| Hewlett-Packard     | 1         | 2      | 0.11%   |
| FNK TECH            | 1         | 1      | 0.11%   |
| Dyconn H            | 1         | 1      | 0.11%   |
| ASMT                | 1         | 2      | 0.11%   |
| ASMedia             | 1         | 1      | 0.11%   |
| AFAYA               | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 280       | 506    | 32.63%  |
| Kingston            | 94        | 133    | 10.96%  |
| SanDisk             | 77        | 120    | 8.97%   |
| Crucial             | 73        | 132    | 8.51%   |
| WDC                 | 53        | 74     | 6.18%   |
| Intel               | 39        | 51     | 4.55%   |
| A-DATA Technology   | 25        | 36     | 2.91%   |
| OCZ                 | 16        | 24     | 1.86%   |
| Micron Technology   | 16        | 26     | 1.86%   |
| China               | 14        | 38     | 1.63%   |
| SK hynix            | 13        | 14     | 1.52%   |
| Corsair             | 12        | 19     | 1.4%    |
| Toshiba             | 11        | 13     | 1.28%   |
| GOODRAM             | 11        | 54     | 1.28%   |
| Apple               | 8         | 9      | 0.93%   |
| Transcend           | 7         | 12     | 0.82%   |
| PNY                 | 7         | 11     | 0.82%   |
| SPCC                | 6         | 7      | 0.7%    |
| Plextor             | 6         | 6      | 0.7%    |
| LITEONIT            | 6         | 8      | 0.7%    |
| Patriot             | 5         | 9      | 0.58%   |
| Mushkin             | 5         | 5      | 0.58%   |
| Team                | 4         | 6      | 0.47%   |
| Intenso             | 4         | 5      | 0.47%   |
| T-FORCE             | 3         | 8      | 0.35%   |
| Seagate             | 3         | 6      | 0.35%   |
| Netac               | 3         | 3      | 0.35%   |
| Dogfish             | 3         | 3      | 0.35%   |
| Apacer              | 3         | 5      | 0.35%   |
| Verbatim            | 2         | 2      | 0.23%   |
| TO Exter            | 2         | 2      | 0.23%   |
| Smartbuy            | 2         | 2      | 0.23%   |
| MyDigitalSSD        | 2         | 2      | 0.23%   |
| LITEON              | 2         | 4      | 0.23%   |
| Linux               | 2         | 2      | 0.23%   |
| KingSpec            | 2         | 3      | 0.23%   |
| KingDian            | 2         | 2      | 0.23%   |
| Kingchuxing         | 2         | 3      | 0.23%   |
| ADROITLARK          | 2         | 3      | 0.23%   |
| Unknown             | 2         | 3      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 834       | 1474   | 36.28%  |
| HDD     | 700       | 1976   | 30.45%  |
| SSD     | 698       | 1407   | 30.36%  |
| MMC     | 59        | 84     | 2.57%   |
| Unknown | 8         | 11     | 0.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1031      | 3304   | 52.18%  |
| NVMe | 833       | 1473   | 42.16%  |
| MMC  | 59        | 84     | 2.99%   |
| SAS  | 53        | 91     | 2.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 695       | 1345   | 43.6%   |
| 0.51-1.0   | 454       | 808    | 28.48%  |
| 1.01-2.0   | 204       | 481    | 12.8%   |
| 3.01-4.0   | 104       | 236    | 6.52%   |
| 4.01-10.0  | 62        | 263    | 3.89%   |
| 2.01-3.0   | 56        | 197    | 3.51%   |
| 10.01-20.0 | 18        | 52     | 1.13%   |
| 20.01-50.0 | 1         | 1      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 321       | 19.23%  |
| 101-250        | 294       | 17.62%  |
| 501-1000       | 286       | 17.14%  |
| 1001-2000      | 198       | 11.86%  |
| More than 3000 | 189       | 11.32%  |
| Unknown        | 93        | 5.57%   |
| 2001-3000      | 87        | 5.21%   |
| 51-100         | 85        | 5.09%   |
| 1-20           | 78        | 4.67%   |
| 21-50          | 38        | 2.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 361       | 20.59%  |
| 21-50          | 247       | 14.09%  |
| 101-250        | 247       | 14.09%  |
| 251-500        | 219       | 12.49%  |
| 51-100         | 169       | 9.64%   |
| 501-1000       | 165       | 9.41%   |
| 1001-2000      | 117       | 6.67%   |
| Unknown        | 93        | 5.31%   |
| More than 3000 | 91        | 5.19%   |
| 2001-3000      | 44        | 2.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                     | 7         | 8      | 2.39%   |
| Seagate ST3500418AS 500GB                    | 6         | 7      | 2.05%   |
| WDC WD40EFRX-68WT0N0 4TB                     | 4         | 14     | 1.37%   |
| Seagate ST500DM002-1BD142 500GB              | 4         | 4      | 1.37%   |
| Seagate ST500DM002-1BC142 500GB              | 4         | 4      | 1.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 4         | 8      | 1.37%   |
| Samsung Electronics SSD 980 1TB              | 4         | 4      | 1.37%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 3         | 6      | 1.02%   |
| WDC WD30EFRX-68AX9N0 3TB                     | 3         | 7      | 1.02%   |
| WDC WD2002FAEX-007BA0 2TB                    | 3         | 3      | 1.02%   |
| Seagate ST8000AS0002-1NA17Z 8TB              | 3         | 15     | 1.02%   |
| Samsung Electronics SSD 850 EVO 1TB          | 3         | 3      | 1.02%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD      | 3         | 3      | 1.02%   |
| IBM DJSA-220 12GB                            | 3         | 3      | 1.02%   |
| WDC WD60EFRX-68MYMN1 6TB                     | 2         | 5      | 0.68%   |
| WDC WD5000BEVT-22ZAT0 500GB                  | 2         | 2      | 0.68%   |
| WDC WD40EFRX-68N32N0 4TB                     | 2         | 2      | 0.68%   |
| WDC WD20EZRX-00D8PB0 2TB                     | 2         | 3      | 0.68%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 2         | 5      | 0.68%   |
| WDC WD20EARS-00MVWB0 2TB                     | 2         | 2      | 0.68%   |
| WDC WD1600AAJS-75B4A0 160GB                  | 2         | 2      | 0.68%   |
| WDC WD15EARS-00Z5B1 1TB                      | 2         | 2      | 0.68%   |
| WDC WD10JPVX-75JC3T0 1TB                     | 2         | 2      | 0.68%   |
| Toshiba DT01ACA200 2TB                       | 2         | 2      | 0.68%   |
| SK hynix HFS256G39TND-N210A 256GB SSD        | 2         | 2      | 0.68%   |
| Seagate ST4000DM000-1F2168 4TB               | 2         | 2      | 0.68%   |
| Seagate ST31000340NS 1TB                     | 2         | 3      | 0.68%   |
| Seagate ST3000DM001-9YN166 3TB               | 2         | 3      | 0.68%   |
| Seagate ST2000LX001-1RG174 2TB               | 2         | 2      | 0.68%   |
| Seagate ST2000DX002-2DV164 2TB               | 2         | 2      | 0.68%   |
| Seagate ST2000DL003-9VT166 2TB               | 2         | 3      | 0.68%   |
| Seagate ST1000NM0011 1TB                     | 2         | 6      | 0.68%   |
| SanDisk SSD PLUS 480GB                       | 2         | 2      | 0.68%   |
| SanDisk SSD PLUS 1000GB                      | 2         | 2      | 0.68%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD          | 2         | 2      | 0.68%   |
| Samsung Electronics SSD 870 EVO 500GB        | 2         | 3      | 0.68%   |
| Samsung Electronics SSD 870 EVO 1TB          | 2         | 9      | 0.68%   |
| Samsung Electronics SSD 840 PRO Series 512GB | 2         | 4      | 0.68%   |
| Samsung Electronics SP2504C 250GB            | 2         | 2      | 0.68%   |
| Samsung Electronics HD103UJ 1TB              | 2         | 2      | 0.68%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 64        | 100    | 22.94%  |
| WDC                         | 62        | 117    | 22.22%  |
| Samsung Electronics         | 33        | 53     | 11.83%  |
| Toshiba                     | 16        | 18     | 5.73%   |
| Hitachi                     | 16        | 32     | 5.73%   |
| HGST                        | 14        | 19     | 5.02%   |
| SanDisk                     | 9         | 11     | 3.23%   |
| Intel                       | 8         | 9      | 2.87%   |
| Crucial                     | 7         | 7      | 2.51%   |
| SK hynix                    | 6         | 8      | 2.15%   |
| Kingston                    | 6         | 6      | 2.15%   |
| IBM                         | 4         | 4      | 1.43%   |
| Fujitsu                     | 4         | 4      | 1.43%   |
| Realtek Semiconductor       | 3         | 9      | 1.08%   |
| OCZ                         | 3         | 3      | 1.08%   |
| PNY                         | 2         | 2      | 0.72%   |
| Plextor                     | 2         | 2      | 0.72%   |
| MDT                         | 2         | 2      | 0.72%   |
| IBM/Hitachi                 | 2         | 2      | 0.72%   |
| Corsair                     | 2         | 5      | 0.72%   |
| China                       | 2         | 3      | 0.72%   |
| A-DATA Technology           | 2         | 2      | 0.72%   |
| Transcend                   | 1         | 1      | 0.36%   |
| SPCC                        | 1         | 1      | 0.36%   |
| Mushkin                     | 1         | 1      | 0.36%   |
| Maxtor                      | 1         | 1      | 0.36%   |
| LITEON                      | 1         | 3      | 0.36%   |
| Kingston Technology Company | 1         | 1      | 0.36%   |
| HGST HTS                    | 1         | 1      | 0.36%   |
| Emtec                       | 1         | 2      | 0.36%   |
| Apple                       | 1         | 1      | 0.36%   |
| 2.5"                        | 1         | 1      | 0.36%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 64        | 100    | 33.51%  |
| WDC                 | 61        | 116    | 31.94%  |
| Hitachi             | 16        | 32     | 8.38%   |
| Toshiba             | 15        | 17     | 7.85%   |
| HGST                | 14        | 19     | 7.33%   |
| Samsung Electronics | 6         | 7      | 3.14%   |
| IBM                 | 4         | 4      | 2.09%   |
| Fujitsu             | 4         | 4      | 2.09%   |
| MDT                 | 2         | 2      | 1.05%   |
| IBM/Hitachi         | 2         | 2      | 1.05%   |
| Maxtor              | 1         | 1      | 0.52%   |
| HGST HTS            | 1         | 1      | 0.52%   |
| Apple               | 1         | 1      | 0.52%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 180       | 306    | 67.16%  |
| SSD  | 65        | 89     | 24.25%  |
| NVMe | 23        | 36     | 8.58%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


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

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1339      | 4074   | 73.53%  |
| Malfunc  | 256       | 431    | 14.06%  |
| Detected | 217       | 435    | 11.92%  |
| Failed   | 9         | 12     | 0.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 796       | 34.55%  |
| AMD                              | 451       | 19.57%  |
| Samsung Electronics              | 373       | 16.19%  |
| SanDisk                          | 132       | 5.73%   |
| ASMedia Technology               | 75        | 3.26%   |
| SK hynix                         | 59        | 2.56%   |
| Phison Electronics               | 58        | 2.52%   |
| Kingston Technology Company      | 49        | 2.13%   |
| Toshiba America Info Systems     | 34        | 1.48%   |
| Marvell Technology Group         | 31        | 1.35%   |
| Micron Technology                | 27        | 1.17%   |
| Nvidia                           | 24        | 1.04%   |
| KIOXIA                           | 24        | 1.04%   |
| ADATA Technology                 | 24        | 1.04%   |
| Micron/Crucial Technology        | 20        | 0.87%   |
| JMicron Technology               | 18        | 0.78%   |
| Silicon Motion                   | 15        | 0.65%   |
| Broadcom / LSI                   | 15        | 0.65%   |
| LSI Logic / Symbios Logic        | 12        | 0.52%   |
| Realtek Semiconductor            | 10        | 0.43%   |
| Seagate Technology               | 6         | 0.26%   |
| Adaptec                          | 6         | 0.26%   |
| Solid State Storage Technology   | 5         | 0.22%   |
| Silicon Image                    | 5         | 0.22%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.17%   |
| INNOGRIT                         | 4         | 0.17%   |
| Yangtze Memory Technologies      | 3         | 0.13%   |
| Silicon Integrated Systems [SiS] | 3         | 0.13%   |
| Lite-On Technology               | 3         | 0.13%   |
| VIA Technologies                 | 2         | 0.09%   |
| Union Memory (Shenzhen)          | 2         | 0.09%   |
| Loongson Technology              | 2         | 0.09%   |
| Lenovo                           | 2         | 0.09%   |
| Hewlett-Packard                  | 2         | 0.09%   |
| Apple                            | 2         | 0.09%   |
| 3ware                            | 2         | 0.09%   |
| OCZ Technology Group             | 1         | 0.04%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.04%   |
| Integrated Technology Express    | 1         | 0.04%   |
| Broadcom                         | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 343       | 13.1%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 222       | 8.48%   |
| AMD 400 Series Chipset SATA Controller                                         | 97        | 3.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 75        | 2.86%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 66        | 2.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 56        | 2.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 51        | 1.95%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 47        | 1.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 46        | 1.76%   |
| Samsung NVMe SSD Controller 980                                                | 46        | 1.76%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 42        | 1.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 42        | 1.6%    |
| AMD 500 Series Chipset SATA Controller                                         | 42        | 1.6%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 40        | 1.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 38        | 1.45%   |
| Intel SSD 660P Series                                                          | 35        | 1.34%   |
| Intel Volume Management Device NVMe RAID Controller                            | 34        | 1.3%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 31        | 1.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 29        | 1.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 29        | 1.11%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 28        | 1.07%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 27        | 1.03%   |
| Intel Comet Lake SATA AHCI Controller                                          | 26        | 0.99%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 23        | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 23        | 0.88%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 23        | 0.88%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 22        | 0.84%   |
| Phison E12 NVMe Controller                                                     | 20        | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 20        | 0.76%   |
| AMD X370 Series Chipset SATA Controller                                        | 20        | 0.76%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 19        | 0.73%   |
| Phison E16 PCIe4 NVMe Controller                                               | 18        | 0.69%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 18        | 0.69%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 18        | 0.69%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 16        | 0.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 16        | 0.61%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 15        | 0.57%   |
| Kingston Company A2000 NVMe SSD                                                | 15        | 0.57%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 15        | 0.57%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 14        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1102      | 49.86%  |
| NVMe | 840       | 38.01%  |
| IDE  | 124       | 5.61%   |
| RAID | 112       | 5.07%   |
| SAS  | 25        | 1.13%   |
| SCSI | 7         | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 940       | 61.16%  |
| AMD                      | 563       | 36.63%  |
| ARM                      | 19        | 1.24%   |
| Marvell Semiconductor    | 3         | 0.2%    |
| Loongson                 | 2         | 0.13%   |
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

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor            | 29        | 1.87%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 24        | 1.55%   |
| AMD Ryzen 5 3600 6-Core Processor             | 22        | 1.42%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 20        | 1.29%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 19        | 1.23%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 19        | 1.23%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 18        | 1.16%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 1.1%    |
| AMD Ryzen 9 5950X 16-Core Processor           | 17        | 1.1%    |
| AMD Ryzen 9 5900X 12-Core Processor           | 17        | 1.1%    |
| AMD Ryzen 9 3900X 12-Core Processor           | 17        | 1.1%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 16        | 1.03%   |
| AMD Ryzen 9 3950X 16-Core Processor           | 15        | 0.97%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 15        | 0.97%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 14        | 0.9%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 14        | 0.9%    |
| ARM Processor                                 | 14        | 0.9%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 13        | 0.84%   |
| Intel 12th Gen Core i7-12700H                 | 13        | 0.84%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 0.84%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 13        | 0.84%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 13        | 0.84%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 12        | 0.77%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 0.77%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 12        | 0.77%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 12        | 0.77%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 11        | 0.71%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 11        | 0.71%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 11        | 0.71%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 10        | 0.65%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 10        | 0.65%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 10        | 0.65%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 10        | 0.65%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 9         | 0.58%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.58%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 0.58%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 9         | 0.58%   |
| AMD FX-8350 Eight-Core Processor              | 9         | 0.58%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 8         | 0.52%   |
| AMD Ryzen 9 7900X 12-Core Processor           | 8         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 344       | 22.27%  |
| Intel Core i5          | 216       | 13.98%  |
| AMD Ryzen 7            | 185       | 11.97%  |
| Other                  | 154       | 9.97%   |
| AMD Ryzen 5            | 129       | 8.35%   |
| AMD Ryzen 9            | 100       | 6.47%   |
| Intel Xeon             | 71        | 4.6%    |
| AMD Ryzen 7 PRO        | 28        | 1.81%   |
| Intel Atom             | 26        | 1.68%   |
| Intel Core i9          | 25        | 1.62%   |
| Intel Celeron          | 25        | 1.62%   |
| Intel Core i3          | 24        | 1.55%   |
| AMD FX                 | 24        | 1.55%   |
| Intel Core 2 Duo       | 21        | 1.36%   |
| Intel Pentium          | 18        | 1.17%   |
| AMD Ryzen 3            | 16        | 1.04%   |
| AMD Phenom II X4       | 11        | 0.71%   |
| Intel Core 2 Quad      | 10        | 0.65%   |
| AMD Ryzen Threadripper | 10        | 0.65%   |
| Intel Pentium M        | 9         | 0.58%   |
| Intel Pentium 4        | 8         | 0.52%   |
| AMD Ryzen 5 PRO        | 8         | 0.52%   |
| AMD A6                 | 7         | 0.45%   |
| AMD Phenom II X6       | 6         | 0.39%   |
| AMD A10                | 5         | 0.32%   |
| Intel Pentium Silver   | 4         | 0.26%   |
| Intel Pentium III      | 4         | 0.26%   |
| ARM BCM                | 4         | 0.26%   |
| AMD Sempron            | 4         | 0.26%   |
| AMD EPYC               | 4         | 0.26%   |
| AMD Athlon 64 X2       | 4         | 0.26%   |
| AMD Athlon             | 4         | 0.26%   |
| Intel Core m3          | 3         | 0.19%   |
| Intel Core 2           | 3         | 0.19%   |
| AMD E                  | 3         | 0.19%   |
| AMD Athlon II X3       | 3         | 0.19%   |
| AMD A8                 | 3         | 0.19%   |
| Intel Genuine          | 2         | 0.13%   |
| Intel Core Duo         | 2         | 0.13%   |
| AMD E1                 | 2         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 511       | 33.05%  |
| 8       | 293       | 18.95%  |
| 6       | 252       | 16.3%   |
| 2       | 250       | 16.17%  |
| 12      | 75        | 4.85%   |
| 16      | 54        | 3.49%   |
| 1       | 47        | 3.04%   |
| 14      | 20        | 1.29%   |
| Unknown | 12        | 0.78%   |
| 10      | 9         | 0.58%   |
| 3       | 7         | 0.45%   |
| 32      | 5         | 0.32%   |
| 24      | 3         | 0.19%   |
| 28      | 2         | 0.13%   |
| 20      | 2         | 0.13%   |
| 64      | 1         | 0.06%   |
| 44      | 1         | 0.06%   |
| 22      | 1         | 0.06%   |
| 18      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1499      | 97.4%   |
| 2       | 29        | 1.88%   |
| Unknown | 11        | 0.71%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1220      | 78.86%  |
| 1       | 314       | 20.3%   |
| Unknown | 12        | 0.78%   |
| 4       | 1         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1487      | 96.75%  |
| 32-bit         | 35        | 2.28%   |
| Unknown        | 15        | 0.98%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 277       | 17.15%  |
| 0x906ea    | 72        | 4.46%   |
| 0x08701021 | 66        | 4.09%   |
| 0x506e3    | 55        | 3.41%   |
| 0x306a9    | 49        | 3.03%   |
| 0x306c3    | 46        | 2.85%   |
| 0x806ec    | 44        | 2.72%   |
| 0x0a50000c | 43        | 2.66%   |
| 0x0800820d | 40        | 2.48%   |
| 0x906e9    | 39        | 2.41%   |
| 0x806c1    | 38        | 2.35%   |
| 0x806ea    | 36        | 2.23%   |
| 0x08701013 | 35        | 2.17%   |
| 0x206a7    | 34        | 2.11%   |
| 0x08600106 | 32        | 1.98%   |
| 0x806e9    | 28        | 1.73%   |
| 0x0a201016 | 28        | 1.73%   |
| 0x906ed    | 25        | 1.55%   |
| 0x0a601203 | 20        | 1.24%   |
| 0x0a201009 | 20        | 1.24%   |
| 0x08108109 | 20        | 1.24%   |
| 0x08001138 | 20        | 1.24%   |
| 0xa0652    | 19        | 1.18%   |
| 0x806d1    | 19        | 1.18%   |
| 0x40651    | 19        | 1.18%   |
| 0x906a3    | 17        | 1.05%   |
| 0x1067a    | 17        | 1.05%   |
| 0x406e3    | 16        | 0.99%   |
| 0x306d4    | 14        | 0.87%   |
| 0x08600103 | 14        | 0.87%   |
| 0x206c2    | 13        | 0.8%    |
| 0x0a20120a | 13        | 0.8%    |
| 0x306f2    | 12        | 0.74%   |
| 0xa0671    | 11        | 0.68%   |
| 0xa0655    | 11        | 0.68%   |
| 0x90672    | 11        | 0.68%   |
| 0x08608103 | 11        | 0.68%   |
| 0x08108102 | 11        | 0.68%   |
| 0x306e4    | 10        | 0.62%   |
| 0x0a404102 | 10        | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 291       | 18.79%  |
| Zen 2            | 183       | 11.81%  |
| Zen 3            | 127       | 8.2%    |
| Unknown          | 104       | 6.71%   |
| Haswell          | 91        | 5.87%   |
| Zen+             | 83        | 5.36%   |
| Skylake          | 82        | 5.29%   |
| IvyBridge        | 66        | 4.26%   |
| SandyBridge      | 50        | 3.23%   |
| Alderlake Hybrid | 44        | 2.84%   |
| TigerLake        | 43        | 2.78%   |
| CometLake        | 42        | 2.71%   |
| Zen              | 41        | 2.65%   |
| Icelake          | 40        | 2.58%   |
| Broadwell        | 29        | 1.87%   |
| Westmere         | 25        | 1.61%   |
| Penryn           | 24        | 1.55%   |
| K10              | 23        | 1.48%   |
| Silvermont       | 22        | 1.42%   |
| Piledriver       | 22        | 1.42%   |
| P6               | 18        | 1.16%   |
| Bonnell          | 17        | 1.1%    |
| Core             | 14        | 0.9%    |
| Nehalem          | 9         | 0.58%   |
| K8 Hammer        | 9         | 0.58%   |
| Goldmont plus    | 9         | 0.58%   |
| NetBurst         | 8         | 0.52%   |
| Steamroller      | 5         | 0.32%   |
| Bulldozer        | 5         | 0.32%   |
| Bobcat           | 5         | 0.32%   |
| Jaguar           | 4         | 0.26%   |
| Goldmont         | 4         | 0.26%   |
| Excavator        | 4         | 0.26%   |
| Puma             | 2         | 0.13%   |
| K10 Llano        | 2         | 0.13%   |
| Tremont          | 1         | 0.06%   |
| Gracemont        | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 643       | 35.18%  |
| Nvidia                           | 599       | 32.77%  |
| AMD                              | 539       | 29.49%  |
| ASPEED Technology                | 28        | 1.53%   |
| Matrox Electronics Systems       | 16        | 0.88%   |
| Loongson Technology              | 2         | 0.11%   |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 87        | 4.56%   |
| AMD Renoir                                                                  | 62        | 3.25%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 60        | 3.14%   |
| Intel UHD Graphics 620                                                      | 44        | 2.31%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 42        | 2.2%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 40        | 2.1%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 40        | 2.1%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 35        | 1.83%   |
| Intel HD Graphics 530                                                       | 34        | 1.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 31        | 1.62%   |
| ASPEED Technology ASPEED Graphics Family                                    | 28        | 1.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 27        | 1.42%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 27        | 1.42%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 26        | 1.36%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 25        | 1.31%   |
| Intel HD Graphics 620                                                       | 23        | 1.21%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 23        | 1.21%   |
| Intel HD Graphics 630                                                       | 20        | 1.05%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 20        | 1.05%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 20        | 1.05%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 19        | 1%      |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 18        | 0.94%   |
| AMD Raphael                                                                 | 18        | 0.94%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 17        | 0.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 16        | 0.84%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 16        | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 15        | 0.79%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 15        | 0.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 15        | 0.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 15        | 0.79%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 15        | 0.79%   |
| AMD Rembrandt [Radeon 680M]                                                 | 14        | 0.73%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 13        | 0.68%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 13        | 0.68%   |
| Intel HD Graphics 5500                                                      | 13        | 0.68%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 13        | 0.68%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 13        | 0.68%   |
| AMD Lucienne                                                                | 13        | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 12        | 0.63%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 12        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| 1 x AMD                   | 433       | 27.65%  |
| 1 x Intel                 | 383       | 24.46%  |
| 1 x Nvidia                | 336       | 21.46%  |
| Intel + Nvidia            | 213       | 13.6%   |
| AMD + Nvidia              | 46        | 2.94%   |
| 2 x AMD                   | 36        | 2.3%    |
| Other                     | 27        | 1.72%   |
| 1 x ASPEED                | 25        | 1.6%    |
| Intel + AMD               | 24        | 1.53%   |
| 1 x Matrox                | 14        | 0.89%   |
| 2 x Intel                 | 12        | 0.77%   |
| 2 x Nvidia                | 7         | 0.45%   |
| AMD + Loongson Technology | 2         | 0.13%   |
| AMD + ASPEED              | 2         | 0.13%   |
| 1 x SiS                   | 1         | 0.06%   |
| Nvidia + Matrox           | 1         | 0.06%   |
| Nvidia + ASPEED           | 1         | 0.06%   |
| Intel + 2 x Nvidia        | 1         | 0.06%   |
| Intel + AMD + 1 x Nvidia  | 1         | 0.06%   |
| AMD + Matrox              | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1089      | 68.79%  |
| Proprietary | 371       | 23.44%  |
| Unknown     | 123       | 7.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 738       | 45.9%   |
| 7.01-8.0   | 184       | 11.44%  |
| 0.01-0.5   | 162       | 10.07%  |
| 1.01-2.0   | 148       | 9.2%    |
| 3.01-4.0   | 133       | 8.27%   |
| 0.51-1.0   | 78        | 4.85%   |
| 8.01-16.0  | 76        | 4.73%   |
| 5.01-6.0   | 60        | 3.73%   |
| 2.01-3.0   | 16        | 1%      |
| 16.01-24.0 | 11        | 0.68%   |
| 4.01-5.0   | 2         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 190       | 10.81%  |
| AU Optronics            | 158       | 8.99%   |
| Dell                    | 150       | 8.53%   |
| BOE                     | 136       | 7.74%   |
| LG Display              | 115       | 6.54%   |
| Chimei Innolux          | 109       | 6.2%    |
| Goldstar                | 86        | 4.89%   |
| AOC                     | 59        | 3.36%   |
| Ancor Communications    | 59        | 3.36%   |
| Sharp                   | 56        | 3.19%   |
| Hewlett-Packard         | 56        | 3.19%   |
| BenQ                    | 55        | 3.13%   |
| Acer                    | 53        | 3.01%   |
| ASUSTek Computer        | 40        | 2.28%   |
| Lenovo                  | 37        | 2.1%    |
| Iiyama                  | 36        | 2.05%   |
| ViewSonic               | 34        | 1.93%   |
| Philips                 | 33        | 1.88%   |
| Apple                   | 32        | 1.82%   |
| Eizo                    | 18        | 1.02%   |
| Chi Mei Optoelectronics | 17        | 0.97%   |
| PANDA                   | 12        | 0.68%   |
| LG Electronics          | 12        | 0.68%   |
| Gigabyte Technology     | 12        | 0.68%   |
| CSO                     | 12        | 0.68%   |
| Unknown                 | 11        | 0.63%   |
| MSI                     | 9         | 0.51%   |
| Fujitsu Siemens         | 9         | 0.51%   |
| Unknown                 | 7         | 0.4%    |
| Sony                    | 6         | 0.34%   |
| NEC Computers           | 6         | 0.34%   |
| InfoVision              | 6         | 0.34%   |
| Idek Iiyama             | 6         | 0.34%   |
| HannStar                | 6         | 0.34%   |
| Sceptre Tech            | 5         | 0.28%   |
| TMX                     | 4         | 0.23%   |
| Panasonic               | 4         | 0.23%   |
| Mi                      | 4         | 0.23%   |
| Envision Peripherals    | 4         | 0.23%   |
| Toshiba                 | 3         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch    | 9         | 0.48%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch      | 9         | 0.48%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch        | 8         | 0.43%   |
| Iiyama PL2473HD IVM6107 1920x1080 520x290mm 23.4-inch               | 8         | 0.43%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch            | 8         | 0.43%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch    | 7         | 0.38%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch      | 7         | 0.38%   |
| Unknown                                                             | 7         | 0.38%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch   | 6         | 0.32%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch               | 6         | 0.32%   |
| Fujitsu Siemens P24W-6 IPS FUS07EA 1920x1200 518x324mm 24.1-inch    | 6         | 0.32%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch      | 6         | 0.32%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch      | 6         | 0.32%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                  | 6         | 0.32%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch             | 5         | 0.27%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch        | 5         | 0.27%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 5         | 0.27%   |
| Dell U2715H DELD066 2560x1440 597x336mm 27.0-inch                   | 5         | 0.27%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                   | 5         | 0.27%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                  | 5         | 0.27%   |
| ASUSTek Computer VG27A AUS2722 2560x1440 600x340mm 27.2-inch        | 5         | 0.27%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch           | 4         | 0.21%   |
| TMX TL156MDMP01-1 TMX1560 3200x2000 336x210mm 15.6-inch             | 4         | 0.21%   |
| Sceptre Tech C305W-2560UN SPT0C0D 2560x1080 690x291mm 29.5-inch     | 4         | 0.21%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch | 4         | 0.21%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch   | 4         | 0.21%   |
| MSI MAG274QRF-QD MSI3CA8 2560x1440 597x336mm 27.0-inch              | 4         | 0.21%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch        | 4         | 0.21%   |
| Hewlett-Packard 22es HWP331B 1920x1080 476x268mm 21.5-inch          | 4         | 0.21%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch           | 4         | 0.21%   |
| Envision Peripherals LCD2361 ENV2361 1920x1080 521x293mm 23.5-inch  | 4         | 0.21%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                   | 4         | 0.21%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch               | 4         | 0.21%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch      | 4         | 0.21%   |
| AOC 2460X AOC2460 1920x1200 518x324mm 24.1-inch                     | 4         | 0.21%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch    | 4         | 0.21%   |
| Acer T232HL ACR041F 1920x1080 509x286mm 23.0-inch                   | 4         | 0.21%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch       | 3         | 0.16%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch             | 3         | 0.16%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch             | 3         | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 771       | 46.11%  |
| 2560x1440 (QHD)    | 163       | 9.75%   |
| 3840x2160 (4K)     | 162       | 9.69%   |
| 1366x768 (WXGA)    | 92        | 5.5%    |
| 1920x1200 (WUXGA)  | 56        | 3.35%   |
| 1280x1024 (SXGA)   | 42        | 2.51%   |
| 1680x1050 (WSXGA+) | 41        | 2.45%   |
| 3440x1440          | 40        | 2.39%   |
| 1600x900 (HD+)     | 35        | 2.09%   |
| Unknown            | 33        | 1.97%   |
| 2560x1600          | 26        | 1.56%   |
| 1440x900 (WXGA+)   | 24        | 1.44%   |
| 2560x1080          | 21        | 1.26%   |
| 3840x2400          | 19        | 1.14%   |
| 3840x1080          | 17        | 1.02%   |
| 1280x800 (WXGA)    | 13        | 0.78%   |
| 2880x1800          | 8         | 0.48%   |
| 1024x600           | 8         | 0.48%   |
| 1600x1200          | 7         | 0.42%   |
| 3840x1200          | 5         | 0.3%    |
| 2160x1440          | 5         | 0.3%    |
| 3200x2000          | 4         | 0.24%   |
| 3200x1800 (QHD+)   | 4         | 0.24%   |
| 2288x1287          | 4         | 0.24%   |
| 2256x1504          | 4         | 0.24%   |
| 2048x1152          | 4         | 0.24%   |
| 1360x768           | 4         | 0.24%   |
| 1024x768 (XGA)     | 4         | 0.24%   |
| 7680x2160          | 3         | 0.18%   |
| 3456x2160          | 3         | 0.18%   |
| 2160x1200          | 3         | 0.18%   |
| 1920x540           | 3         | 0.18%   |
| 1280x960           | 3         | 0.18%   |
| 1280x854           | 3         | 0.18%   |
| 800x1280           | 2         | 0.12%   |
| 5760x2160          | 2         | 0.12%   |
| 3072x1920          | 2         | 0.12%   |
| 2240x1400          | 2         | 0.12%   |
| 1920x1280          | 2         | 0.12%   |
| 1400x1050          | 2         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 318       | 18.24%  |
| 27      | 230       | 13.2%   |
| 24      | 162       | 9.29%   |
| 23      | 138       | 7.92%   |
| 13      | 138       | 7.92%   |
| 14      | 112       | 6.43%   |
| Unknown | 100       | 5.74%   |
| 17      | 94        | 5.39%   |
| 21      | 91        | 5.22%   |
| 34      | 51        | 2.93%   |
| 19      | 39        | 2.24%   |
| 31      | 33        | 1.89%   |
| 12      | 31        | 1.78%   |
| 22      | 27        | 1.55%   |
| 16      | 25        | 1.43%   |
| 25      | 16        | 0.92%   |
| 20      | 14        | 0.8%    |
| 11      | 13        | 0.75%   |
| 84      | 12        | 0.69%   |
| 32      | 12        | 0.69%   |
| 18      | 12        | 0.69%   |
| 54      | 7         | 0.4%    |
| 10      | 7         | 0.4%    |
| 48      | 6         | 0.34%   |
| 40      | 6         | 0.34%   |
| 26      | 6         | 0.34%   |
| 72      | 5         | 0.29%   |
| 29      | 5         | 0.29%   |
| 142     | 4         | 0.23%   |
| 49      | 4         | 0.23%   |
| 28      | 3         | 0.17%   |
| 8       | 3         | 0.17%   |
| 58      | 2         | 0.11%   |
| 43      | 2         | 0.11%   |
| 42      | 2         | 0.11%   |
| 75      | 1         | 0.06%   |
| 65      | 1         | 0.06%   |
| 52      | 1         | 0.06%   |
| 50      | 1         | 0.06%   |
| 41      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 520       | 30.95%  |
| 501-600        | 461       | 27.44%  |
| 401-500        | 161       | 9.58%   |
| 201-300        | 135       | 8.04%   |
| 351-400        | 103       | 6.13%   |
| Unknown        | 100       | 5.95%   |
| 601-700        | 73        | 4.35%   |
| 701-800        | 64        | 3.81%   |
| 1001-1500      | 23        | 1.37%   |
| 1501-2000      | 18        | 1.07%   |
| 801-900        | 9         | 0.54%   |
| More than 2000 | 4         | 0.24%   |
| 901-1000       | 4         | 0.24%   |
| 101-200        | 3         | 0.18%   |
| 1-100          | 2         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1076      | 70.6%   |
| 16/10   | 208       | 13.65%  |
| Unknown | 84        | 5.51%   |
| 21/9    | 56        | 3.67%   |
| 5/4     | 39        | 2.56%   |
| 3/2     | 22        | 1.44%   |
| 4/3     | 15        | 0.98%   |
| 32/9    | 11        | 0.72%   |
| 1.00    | 5         | 0.33%   |
| 6/5     | 3         | 0.2%    |
| 3.40    | 1         | 0.07%   |
| 3.20    | 1         | 0.07%   |
| 0.67    | 1         | 0.07%   |
| 0.62    | 1         | 0.07%   |
| 0.31    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 317       | 18.45%  |
| 201-250        | 311       | 18.1%   |
| 301-350        | 234       | 13.62%  |
| 81-90          | 179       | 10.42%  |
| 351-500        | 100       | 5.82%   |
| Unknown        | 100       | 5.82%   |
| 251-300        | 82        | 4.77%   |
| 151-200        | 77        | 4.48%   |
| 71-80          | 70        | 4.07%   |
| 121-130        | 64        | 3.73%   |
| More than 1000 | 36        | 2.1%    |
| 141-150        | 31        | 1.8%    |
| 61-70          | 28        | 1.63%   |
| 111-120        | 26        | 1.51%   |
| 501-1000       | 21        | 1.22%   |
| 51-60          | 15        | 0.87%   |
| 131-140        | 9         | 0.52%   |
| 41-50          | 7         | 0.41%   |
| 91-100         | 6         | 0.35%   |
| 1-40           | 5         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 511       | 31.03%  |
| 121-160       | 475       | 28.84%  |
| 101-120       | 309       | 18.76%  |
| 161-240       | 151       | 9.17%   |
| Unknown       | 100       | 6.07%   |
| More than 240 | 75        | 4.55%   |
| 1-50          | 26        | 1.58%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1099      | 68.22%  |
| 2     | 298       | 18.5%   |
| 0     | 144       | 8.94%   |
| 3     | 59        | 3.66%   |
| 4     | 11        | 0.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 958       | 42.58%  |
| Realtek Semiconductor             | 727       | 32.31%  |
| Qualcomm Atheros                  | 143       | 6.36%   |
| Broadcom                          | 93        | 4.13%   |
| MediaTek                          | 46        | 2.04%   |
| ASIX Electronics                  | 21        | 0.93%   |
| Aquantia                          | 21        | 0.93%   |
| Nvidia                            | 20        | 0.89%   |
| Marvell Technology Group          | 17        | 0.76%   |
| Lenovo                            | 13        | 0.58%   |
| TP-Link                           | 11        | 0.49%   |
| Qualcomm                          | 11        | 0.49%   |
| Broadcom Limited                  | 11        | 0.49%   |
| Apple                             | 10        | 0.44%   |
| Sierra Wireless                   | 9         | 0.4%    |
| Dell                              | 9         | 0.4%    |
| Qualcomm Atheros Communications   | 8         | 0.36%   |
| Microsoft                         | 8         | 0.36%   |
| Xiaomi                            | 6         | 0.27%   |
| Ralink                            | 6         | 0.27%   |
| Samsung Electronics               | 5         | 0.22%   |
| Ralink Technology                 | 5         | 0.22%   |
| Fibocom                           | 5         | 0.22%   |
| Ericsson Business Mobile Networks | 5         | 0.22%   |
| D-Link System                     | 4         | 0.18%   |
| Standard Microsystems             | 3         | 0.13%   |
| NetGear                           | 3         | 0.13%   |
| Microchip Technology              | 3         | 0.13%   |
| ICS Advent                        | 3         | 0.13%   |
| Huawei Technologies               | 3         | 0.13%   |
| D-Link                            | 3         | 0.13%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.09%   |
| U-Blox                            | 2         | 0.09%   |
| STMicroelectronics                | 2         | 0.09%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.09%   |
| Sigma Designs                     | 2         | 0.09%   |
| QLogic                            | 2         | 0.09%   |
| Prusa                             | 2         | 0.09%   |
| OpenMoko                          | 2         | 0.09%   |
| Netchip Technology                | 2         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 521       | 19.19%  |
| Intel Wi-Fi 6 AX200                                               | 161       | 5.93%   |
| Intel I211 Gigabit Network Connection                             | 120       | 4.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 73        | 2.69%   |
| Intel Wireless 8265 / 8275                                        | 62        | 2.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 59        | 2.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 46        | 1.69%   |
| Intel Ethernet Controller I225-V                                  | 44        | 1.62%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 38        | 1.4%    |
| Intel I210 Gigabit Network Connection                             | 36        | 1.33%   |
| Intel Wi-Fi 6 AX201                                               | 33        | 1.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 32        | 1.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 32        | 1.18%   |
| Intel Ethernet Connection (2) I219-V                              | 31        | 1.14%   |
| Intel Wireless-AC 9260                                            | 29        | 1.07%   |
| Intel Wireless 8260                                               | 28        | 1.03%   |
| Intel Wireless 7265                                               | 28        | 1.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 0.99%   |
| Intel Ethernet Connection (7) I219-V                              | 27        | 0.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 27        | 0.99%   |
| Intel 82574L Gigabit Network Connection                           | 25        | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                             | 24        | 0.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 24        | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 23        | 0.85%   |
| Intel Wireless 7260                                               | 23        | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 22        | 0.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 21        | 0.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 21        | 0.77%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 20        | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 20        | 0.74%   |
| Intel Wireless 3165                                               | 19        | 0.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 18        | 0.66%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 16        | 0.59%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 16        | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 16        | 0.59%   |
| Intel I350 Gigabit Network Connection                             | 15        | 0.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 0.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 13        | 0.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 13        | 0.48%   |
| Intel Ethernet Connection (2) I218-V                              | 13        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 684       | 61.13%  |
| Realtek Semiconductor                 | 125       | 11.17%  |
| Qualcomm Atheros                      | 109       | 9.74%   |
| Broadcom                              | 61        | 5.45%   |
| MediaTek                              | 44        | 3.93%   |
| Qualcomm                              | 11        | 0.98%   |
| TP-Link                               | 9         | 0.8%    |
| Sierra Wireless                       | 9         | 0.8%    |
| Qualcomm Atheros Communications       | 8         | 0.71%   |
| Microsoft                             | 8         | 0.71%   |
| Broadcom Limited                      | 8         | 0.71%   |
| Dell                                  | 7         | 0.63%   |
| Ralink                                | 6         | 0.54%   |
| Ralink Technology                     | 5         | 0.45%   |
| Fibocom                               | 5         | 0.45%   |
| NetGear                               | 3         | 0.27%   |
| D-Link System                         | 3         | 0.27%   |
| D-Link                                | 3         | 0.27%   |
| Ericsson Business Mobile Networks     | 2         | 0.18%   |
| Wilocity                              | 1         | 0.09%   |
| Texas Instruments                     | 1         | 0.09%   |
| Senao                                 | 1         | 0.09%   |
| Quectel Wireless Solutions            | 1         | 0.09%   |
| Edimax Technology                     | 1         | 0.09%   |
| Cisco Aironet Wireless Communications | 1         | 0.09%   |
| BUFFALO                               | 1         | 0.09%   |
| AVM                                   | 1         | 0.09%   |
| ASUSTek Computer                      | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 161       | 14.32%  |
| Intel Wireless 8265 / 8275                                              | 62        | 5.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 46        | 4.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 38        | 3.38%   |
| Intel Wi-Fi 6 AX201                                                     | 33        | 2.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 32        | 2.85%   |
| Intel Wireless-AC 9260                                                  | 29        | 2.58%   |
| Intel Wireless 8260                                                     | 28        | 2.49%   |
| Intel Wireless 7265                                                     | 28        | 2.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 27        | 2.4%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 24        | 2.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 23        | 2.05%   |
| Intel Wireless 7260                                                     | 23        | 2.05%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 22        | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 21        | 1.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 21        | 1.87%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 20        | 1.78%   |
| Intel Wireless 3165                                                     | 19        | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 18        | 1.6%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 16        | 1.42%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 16        | 1.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 16        | 1.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 1.25%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 13        | 1.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 0.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 0.98%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 11        | 0.98%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 10        | 0.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 0.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 9         | 0.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 9         | 0.8%    |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 9         | 0.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 0.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 8         | 0.71%   |
| Intel Centrino Advanced-N 6235                                          | 8         | 0.71%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 7         | 0.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 0.62%   |
| Qualcomm Atheros AR9271 802.11n                                         | 7         | 0.62%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 7         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 684       | 46.66%  |
| Intel                            | 541       | 36.9%   |
| Qualcomm Atheros                 | 47        | 3.21%   |
| Broadcom                         | 42        | 2.86%   |
| ASIX Electronics                 | 21        | 1.43%   |
| Aquantia                         | 21        | 1.43%   |
| Nvidia                           | 20        | 1.36%   |
| Marvell Technology Group         | 17        | 1.16%   |
| Lenovo                           | 13        | 0.89%   |
| Apple                            | 10        | 0.68%   |
| Xiaomi                           | 6         | 0.41%   |
| Samsung Electronics              | 4         | 0.27%   |
| Standard Microsystems            | 3         | 0.2%    |
| Microchip Technology             | 3         | 0.2%    |
| ICS Advent                       | 3         | 0.2%    |
| Broadcom Limited                 | 3         | 0.2%    |
| ZTE WCDMA Technologies MSM       | 2         | 0.14%   |
| TP-Link                          | 2         | 0.14%   |
| Silicon Integrated Systems [SiS] | 2         | 0.14%   |
| QLogic                           | 2         | 0.14%   |
| Loongson Technology              | 2         | 0.14%   |
| Google                           | 2         | 0.14%   |
| DisplayLink                      | 2         | 0.14%   |
| 3Com                             | 2         | 0.14%   |
| NetXen Incorporated              | 1         | 0.07%   |
| Mellanox Technologies            | 1         | 0.07%   |
| MediaTek                         | 1         | 0.07%   |
| JMicron Technology               | 1         | 0.07%   |
| Insyde Software                  | 1         | 0.07%   |
| Huawei Technologies              | 1         | 0.07%   |
| HMD Global                       | 1         | 0.07%   |
| Hewlett-Packard                  | 1         | 0.07%   |
| Gemtek                           | 1         | 0.07%   |
| Davicom Semiconductor            | 1         | 0.07%   |
| D-Link System                    | 1         | 0.07%   |
| American Megatrends              | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 521       | 33.77%  |
| Intel I211 Gigabit Network Connection                                         | 120       | 7.78%   |
| Realtek RTL8125 2.5GbE Controller                                             | 73        | 4.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 59        | 3.82%   |
| Intel Ethernet Controller I225-V                                              | 44        | 2.85%   |
| Intel I210 Gigabit Network Connection                                         | 36        | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 32        | 2.07%   |
| Intel Ethernet Connection (2) I219-V                                          | 31        | 2.01%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 27        | 1.75%   |
| Intel Ethernet Connection (7) I219-V                                          | 27        | 1.75%   |
| Intel 82574L Gigabit Network Connection                                       | 25        | 1.62%   |
| Intel Ethernet Connection (2) I219-LM                                         | 24        | 1.56%   |
| Intel Ethernet Connection (4) I219-LM                                         | 20        | 1.3%    |
| Intel I350 Gigabit Network Connection                                         | 15        | 0.97%   |
| Intel Ethernet Connection (2) I218-V                                          | 13        | 0.84%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 12        | 0.78%   |
| Intel Ethernet Connection (4) I219-V                                          | 12        | 0.78%   |
| Intel Ethernet Connection I217-LM                                             | 11        | 0.71%   |
| Intel Ethernet Connection (7) I219-LM                                         | 10        | 0.65%   |
| Intel Ethernet Connection (6) I219-V                                          | 10        | 0.65%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 10        | 0.65%   |
| Intel 82579V Gigabit Network Connection                                       | 10        | 0.65%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 9         | 0.58%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 8         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 8         | 0.52%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 8         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 7         | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 7         | 0.45%   |
| Nvidia MCP77 Ethernet                                                         | 7         | 0.45%   |
| Intel Ethernet Connection I218-LM                                             | 7         | 0.45%   |
| Intel Ethernet Connection (5) I219-LM                                         | 7         | 0.45%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 7         | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 6         | 0.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 6         | 0.39%   |
| Intel Ethernet Connection I219-LM                                             | 6         | 0.39%   |
| Intel Ethernet Connection (3) I218-LM                                         | 6         | 0.39%   |
| Intel Ethernet Connection (10) I219-V                                         | 6         | 0.39%   |
| Intel 82577LM Gigabit Network Connection                                      | 6         | 0.39%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6         | 0.39%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                               | 6         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1336      | 54.78%  |
| WiFi     | 1057      | 43.34%  |
| Modem    | 44        | 1.8%    |
| Unknown  | 2         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 880       | 54.69%  |
| WiFi     | 729       | 45.31%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 780       | 50.13%  |
| 1     | 615       | 39.52%  |
| 3     | 89        | 5.72%   |
| 0     | 29        | 1.86%   |
| 4     | 23        | 1.48%   |
| 6     | 7         | 0.45%   |
| 5     | 7         | 0.45%   |
| 8     | 2         | 0.13%   |
| 7     | 2         | 0.13%   |
| 12    | 1         | 0.06%   |
| 9     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1302      | 82.04%  |
| Yes  | 285       | 17.96%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 613       | 61.12%  |
| Realtek Semiconductor           | 82        | 8.18%   |
| Cambridge Silicon Radio         | 57        | 5.68%   |
| Apple                           | 36        | 3.59%   |
| IMC Networks                    | 30        | 2.99%   |
| Foxconn / Hon Hai               | 28        | 2.79%   |
| Broadcom                        | 27        | 2.69%   |
| Qualcomm Atheros Communications | 26        | 2.59%   |
| Lite-On Technology              | 22        | 2.19%   |
| ASUSTek Computer                | 22        | 2.19%   |
| MediaTek                        | 13        | 1.3%    |
| Dell                            | 9         | 0.9%    |
| Realtek                         | 8         | 0.8%    |
| USI                             | 5         | 0.5%    |
| Toshiba                         | 5         | 0.5%    |
| Hewlett-Packard                 | 4         | 0.4%    |
| HTC (High Tech Computer)        | 3         | 0.3%    |
| Belkin Components               | 3         | 0.3%    |
| Foxconn International           | 2         | 0.2%    |
| Ralink Technology               | 1         | 0.1%    |
| Opticis                         | 1         | 0.1%    |
| Edimax Technology               | 1         | 0.1%    |
| Dynex                           | 1         | 0.1%    |
| Chicony Electronics             | 1         | 0.1%    |
| Askey Computer                  | 1         | 0.1%    |
| Alps Electric                   | 1         | 0.1%    |
| Actiontec Electronics           | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 161       | 16.04%  |
| Intel AX200 Bluetooth                                                | 161       | 16.04%  |
| Intel AX201 Bluetooth                                                | 96        | 9.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 80        | 7.97%   |
| Realtek Bluetooth Radio                                              | 61        | 6.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 57        | 5.68%   |
| Intel Bluetooth Device                                               | 40        | 3.98%   |
| Intel AX210 Bluetooth                                                | 35        | 3.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 30        | 2.99%   |
| Apple Bluetooth Host Controller                                      | 20        | 1.99%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 16        | 1.59%   |
| IMC Networks Wireless_Device                                         | 15        | 1.49%   |
| MediaTek Wireless_Device                                             | 13        | 1.29%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 10        | 1%      |
| IMC Networks Bluetooth Radio                                         | 10        | 1%      |
| Foxconn / Hon Hai Wireless_Device                                    | 9         | 0.9%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 9         | 0.9%    |
| Realtek 802.11ac WLAN Adapter                                        | 8         | 0.8%    |
| Foxconn / Hon Hai Bluetooth Device                                   | 8         | 0.8%    |
| Qualcomm Atheros  Bluetooth Device                                   | 7         | 0.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 7         | 0.7%    |
| Lite-On Bluetooth Device                                             | 7         | 0.7%    |
| Lite-On Atheros AR3012 Bluetooth                                     | 7         | 0.7%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                         | 6         | 0.6%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 6         | 0.6%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 6         | 0.6%    |
| USI Bluetooth Device                                                 | 5         | 0.5%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                              | 5         | 0.5%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 5         | 0.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 4         | 0.4%    |
| IMC Networks Bluetooth Device                                        | 4         | 0.4%    |
| Dell DW375 Bluetooth Module                                          | 4         | 0.4%    |
| Broadcom HP Portable SoftSailing                                     | 4         | 0.4%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 4         | 0.4%    |
| Apple Bluetooth USB Host Controller                                  | 4         | 0.4%    |
| Apple Bluetooth HCI                                                  | 4         | 0.4%    |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 3         | 0.3%    |
| Qualcomm Atheros AR3011 Bluetooth                                    | 3         | 0.3%    |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 3         | 0.3%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                        | 3         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 845       | 35.39%  |
| AMD                                  | 622       | 26.05%  |
| Nvidia                               | 471       | 19.72%  |
| C-Media Electronics                  | 60        | 2.51%   |
| Logitech                             | 33        | 1.38%   |
| Creative Labs                        | 23        | 0.96%   |
| ASUSTek Computer                     | 22        | 0.92%   |
| SteelSeries ApS                      | 18        | 0.75%   |
| Realtek Semiconductor                | 15        | 0.63%   |
| Lenovo                               | 15        | 0.63%   |
| Creative Technology                  | 15        | 0.63%   |
| Texas Instruments                    | 14        | 0.59%   |
| Razer USA                            | 12        | 0.5%    |
| JMTek                                | 11        | 0.46%   |
| Kingston Technology                  | 10        | 0.42%   |
| Focusrite-Novation                   | 10        | 0.42%   |
| Plantronics                          | 9         | 0.38%   |
| Thesycon Systemsoftware & Consulting | 8         | 0.34%   |
| GYROCOM C&C                          | 8         | 0.34%   |
| Blue Microphones                     | 8         | 0.34%   |
| AudioQuest                           | 7         | 0.29%   |
| GN Netcom                            | 6         | 0.25%   |
| Generalplus Technology               | 6         | 0.25%   |
| Corsair                              | 6         | 0.25%   |
| BEHRINGER International              | 6         | 0.25%   |
| Samson Technologies                  | 5         | 0.21%   |
| RODE Microphones                     | 5         | 0.21%   |
| Dell                                 | 5         | 0.21%   |
| Sony                                 | 4         | 0.17%   |
| Solid State Logic                    | 4         | 0.17%   |
| Sennheiser Communications            | 4         | 0.17%   |
| SAVITECH                             | 4         | 0.17%   |
| Micro Star International             | 4         | 0.17%   |
| DSEA A/S                             | 4         | 0.17%   |
| Yamaha                               | 3         | 0.13%   |
| Trust                                | 3         | 0.13%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.13%   |
| No brand                             | 3         | 0.13%   |
| Microsoft                            | 3         | 0.13%   |
| Hewlett-Packard                      | 3         | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 200       | 6.91%   |
| AMD Starship/Matisse HD Audio Controller                                   | 170       | 5.87%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 115       | 3.97%   |
| Intel Cannon Lake PCH cAVS                                                 | 99        | 3.42%   |
| Intel Sunrise Point-LP HD Audio                                            | 93        | 3.21%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 90        | 3.11%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 74        | 2.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 57        | 1.97%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 55        | 1.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 51        | 1.76%   |
| AMD Navi 10 HDMI Audio                                                     | 48        | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 44        | 1.52%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 43        | 1.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 41        | 1.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 40        | 1.38%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 38        | 1.31%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 34        | 1.17%   |
| Nvidia GP106 High Definition Audio Controller                              | 34        | 1.17%   |
| Nvidia TU106 High Definition Audio Controller                              | 33        | 1.14%   |
| Nvidia GP104 High Definition Audio Controller                              | 33        | 1.14%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 32        | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                            | 31        | 1.07%   |
| Nvidia TU104 HD Audio Controller                                           | 29        | 1%      |
| Nvidia GA104 High Definition Audio Controller                              | 29        | 1%      |
| Intel Tiger Lake-H HD Audio Controller                                     | 29        | 1%      |
| Intel Comet Lake PCH-LP cAVS                                               | 29        | 1%      |
| Intel Comet Lake PCH cAVS                                                  | 29        | 1%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 28        | 0.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 28        | 0.97%   |
| Nvidia TU116 High Definition Audio Controller                              | 27        | 0.93%   |
| Nvidia GA106 High Definition Audio Controller                              | 27        | 0.93%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 27        | 0.93%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 24        | 0.83%   |
| Intel CM238 HD Audio Controller                                            | 24        | 0.83%   |
| Intel 200 Series PCH HD Audio                                              | 23        | 0.79%   |
| Nvidia GA102 High Definition Audio Controller                              | 21        | 0.73%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 21        | 0.73%   |
| Intel Haswell-ULT HD Audio Controller                                      | 20        | 0.69%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 20        | 0.69%   |
| Intel 8 Series HD Audio Controller                                         | 20        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 327       | 20.11%  |
| Kingston                     | 223       | 13.71%  |
| SK hynix                     | 219       | 13.47%  |
| Micron Technology            | 152       | 9.35%   |
| Corsair                      | 152       | 9.35%   |
| G.Skill                      | 132       | 8.12%   |
| Unknown                      | 128       | 7.87%   |
| Crucial                      | 125       | 7.69%   |
| Ramaxel Technology           | 19        | 1.17%   |
| A-DATA Technology            | 19        | 1.17%   |
| Team                         | 16        | 0.98%   |
| Patriot                      | 14        | 0.86%   |
| Elpida                       | 12        | 0.74%   |
| Transcend                    | 10        | 0.62%   |
| Nanya Technology             | 10        | 0.62%   |
| Unknown                      | 9         | 0.55%   |
| GOODRAM                      | 8         | 0.49%   |
| Unknown (ABCD)               | 4         | 0.25%   |
| AMD                          | 4         | 0.25%   |
| Timetec                      | 3         | 0.18%   |
| Apacer                       | 3         | 0.18%   |
| Toshiba                      | 2         | 0.12%   |
| KLEVV                        | 2         | 0.12%   |
| Chun Well                    | 2         | 0.12%   |
| Avant                        | 2         | 0.12%   |
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
| Mushkin                      | 1         | 0.06%   |
| Magnum Tech                  | 1         | 0.06%   |
| Kllisre                      | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 14        | 0.81%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 14        | 0.81%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s      | 13        | 0.75%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s       | 13        | 0.75%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 12        | 0.69%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 12        | 0.69%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 11        | 0.64%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s     | 11        | 0.64%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 10        | 0.58%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 10        | 0.58%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 10        | 0.58%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 9         | 0.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 9         | 0.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 9         | 0.52%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s      | 9         | 0.52%   |
| Unknown                                                     | 9         | 0.52%   |
| Unknown RAM Module 1GB SODIMM DDR                           | 8         | 0.46%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s      | 8         | 0.46%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 8         | 0.46%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s      | 8         | 0.46%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s      | 8         | 0.46%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s      | 8         | 0.46%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 8         | 0.46%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 8         | 0.46%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 8         | 0.46%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s         | 8         | 0.46%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s       | 8         | 0.46%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s     | 7         | 0.41%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s       | 7         | 0.41%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s           | 7         | 0.41%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s      | 7         | 0.41%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 6         | 0.35%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 6         | 0.35%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s       | 6         | 0.35%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s       | 6         | 0.35%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s        | 6         | 0.35%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s      | 6         | 0.35%   |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3866MT/s      | 6         | 0.35%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s          | 6         | 0.35%   |
| Unknown RAM Module 1024MB DIMM SDRAM                        | 5         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 890       | 61.42%  |
| DDR3    | 310       | 21.39%  |
| DDR2    | 50        | 3.45%   |
| DDR5    | 43        | 2.97%   |
| LPDDR4  | 42        | 2.9%    |
| Unknown | 32        | 2.21%   |
| LPDDR3  | 27        | 1.86%   |
| SDRAM   | 19        | 1.31%   |
| LPDDR5  | 17        | 1.17%   |
| DDR     | 16        | 1.1%    |
| DRAM    | 3         | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 678       | 46.76%  |
| SODIMM       | 674       | 46.48%  |
| Row Of Chips | 89        | 6.14%   |
| Chip         | 6         | 0.41%   |
| Unknown      | 2         | 0.14%   |
| RIMM         | 1         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 640       | 41.03%  |
| 16384 | 398       | 25.51%  |
| 4096  | 250       | 16.03%  |
| 32768 | 122       | 7.82%   |
| 2048  | 98        | 6.28%   |
| 1024  | 39        | 2.5%    |
| 512   | 8         | 0.51%   |
| 256   | 5         | 0.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 296       | 18.9%   |
| 2667    | 224       | 14.3%   |
| 1600    | 189       | 12.07%  |
| 2400    | 99        | 6.32%   |
| 3600    | 90        | 5.75%   |
| 2133    | 84        | 5.36%   |
| 1333    | 72        | 4.6%    |
| 667     | 33        | 2.11%   |
| 800     | 32        | 2.04%   |
| 3000    | 31        | 1.98%   |
| Unknown | 28        | 1.79%   |
| 4800    | 27        | 1.72%   |
| 3733    | 26        | 1.66%   |
| 6400    | 25        | 1.6%    |
| 4267    | 25        | 1.6%    |
| 3400    | 22        | 1.4%    |
| 2933    | 21        | 1.34%   |
| 1867    | 21        | 1.34%   |
| 1334    | 17        | 1.09%   |
| 2666    | 15        | 0.96%   |
| 3800    | 14        | 0.89%   |
| 1866    | 13        | 0.83%   |
| 3266    | 12        | 0.77%   |
| 3466    | 11        | 0.7%    |
| 8400    | 10        | 0.64%   |
| 3866    | 9         | 0.57%   |
| 1067    | 9         | 0.57%   |
| 1066    | 9         | 0.57%   |
| 4000    | 8         | 0.51%   |
| 3533    | 8         | 0.51%   |
| 3666    | 7         | 0.45%   |
| 3534    | 6         | 0.38%   |
| 2800    | 6         | 0.38%   |
| 400     | 6         | 0.38%   |
| 6000    | 5         | 0.32%   |
| 3333    | 5         | 0.32%   |
| 3933    | 4         | 0.26%   |
| 2048    | 4         | 0.26%   |
| 533     | 4         | 0.26%   |
| 5200    | 3         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 13        | 41.94%  |
| Seiko Epson           | 4         | 12.9%   |
| Samsung Electronics   | 4         | 12.9%   |
| Brother Industries    | 4         | 12.9%   |
| Canon                 | 3         | 9.68%   |
| Xiaomi                | 1         | 3.23%   |
| Lexmark International | 1         | 3.23%   |
| Konica Minolta        | 1         | 3.23%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| HP LaserJet M14-M17                   | 2         | 6.45%   |
| Canon LiDE 400                        | 2         | 6.45%   |
| Xiaomi MiMouse 2                      | 1         | 3.23%   |
| Seiko Epson XP-4200 Series            | 1         | 3.23%   |
| Seiko Epson WF-3520 Series            | 1         | 3.23%   |
| Seiko Epson WF-2510 Series            | 1         | 3.23%   |
| Seiko Epson AL-M310DN                 | 1         | 3.23%   |
| Samsung ML-191x/ML-252x Laser Printer | 1         | 3.23%   |
| Samsung ML-1630 Series                | 1         | 3.23%   |
| Samsung CLP-325 Color Laser Printer   | 1         | 3.23%   |
| Samsung C460 Series                   | 1         | 3.23%   |
| Lexmark International Lexmark E352dn  | 1         | 3.23%   |
| Konica Minolta magicolor 1680MF scan  | 1         | 3.23%   |
| HP PhotoSmart 130                     | 1         | 3.23%   |
| HP LaserJet P2055 series              | 1         | 3.23%   |
| HP LaserJet 3200                      | 1         | 3.23%   |
| HP LaserJet 1020                      | 1         | 3.23%   |
| HP LaserJet 1018                      | 1         | 3.23%   |
| HP LaserJet 1010                      | 1         | 3.23%   |
| HP Deskjet D1500 series               | 1         | 3.23%   |
| HP Deskjet 9800                       | 1         | 3.23%   |
| HP DeskJet 5440                       | 1         | 3.23%   |
| HP DeskJet 3630 series                | 1         | 3.23%   |
| HP Deskjet 2050 J510                  | 1         | 3.23%   |
| Canon CanoScan LiDE 300               | 1         | 3.23%   |
| Brother QL-500 label printer          | 1         | 3.23%   |
| Brother MFC-L2700DW                   | 1         | 3.23%   |
| Brother MFC-9340CDW                   | 1         | 3.23%   |
| Brother MFC-9130CW                    | 1         | 3.23%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 71.43%  |
| Mustek Systems  | 1         | 14.29%  |
| AGFA-Gevaert NV | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30      | 2         | 28.57%  |
| Mustek Systems BearPaw 2448 TA Pro | 1         | 14.29%  |
| Canon CanoScan LiDE 600F           | 1         | 14.29%  |
| Canon CanoScan LiDE 220            | 1         | 14.29%  |
| Canon CanoScan LiDE 110            | 1         | 14.29%  |
| AGFA-Gevaert NV SnapScan e20       | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 169       | 19.93%  |
| Logitech                               | 112       | 13.21%  |
| IMC Networks                           | 91        | 10.73%  |
| Microdia                               | 76        | 8.96%   |
| Realtek Semiconductor                  | 55        | 6.49%   |
| Bison Electronics                      | 46        | 5.42%   |
| Sunplus Innovation Technology          | 45        | 5.31%   |
| Quanta                                 | 37        | 4.36%   |
| Lite-On Technology                     | 23        | 2.71%   |
| Cheng Uei Precision Industry (Foxlink) | 23        | 2.71%   |
| Luxvisions Innotech Limited            | 20        | 2.36%   |
| Apple                                  | 20        | 2.36%   |
| Syntek                                 | 17        | 2%      |
| Samsung Electronics                    | 13        | 1.53%   |
| Acer                                   | 10        | 1.18%   |
| Z-Star Microelectronics                | 8         | 0.94%   |
| Microsoft                              | 7         | 0.83%   |
| Suyin                                  | 4         | 0.47%   |
| Sonix Technology                       | 4         | 0.47%   |
| MacroSilicon                           | 4         | 0.47%   |
| DigiTech                               | 4         | 0.47%   |
| Creative Technology                    | 4         | 0.47%   |
| Silicon Motion                         | 3         | 0.35%   |
| Generalplus Technology                 | 3         | 0.35%   |
| AVerMedia Technologies                 | 3         | 0.35%   |
| ARC International                      | 3         | 0.35%   |
| SunplusIT                              | 2         | 0.24%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.24%   |
| Ricoh                                  | 2         | 0.24%   |
| Razer USA                              | 2         | 0.24%   |
| LG Electronics                         | 2         | 0.24%   |
| KYE Systems (Mouse Systems)            | 2         | 0.24%   |
| Genesys Logic                          | 2         | 0.24%   |
| Elgato Systems                         | 2         | 0.24%   |
| Cubeternet                             | 2         | 0.24%   |
| Alcor Micro                            | 2         | 0.24%   |
| Xiaomi                                 | 1         | 0.12%   |
| WaveRider Communications               | 1         | 0.12%   |
| Valve Software                         | 1         | 0.12%   |
| USB3.0 HD Audio Capture                | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 54        | 6.26%   |
| Microdia Integrated_Webcam_HD                 | 39        | 4.52%   |
| IMC Networks Integrated Camera                | 38        | 4.41%   |
| Logitech HD Pro Webcam C920                   | 33        | 3.83%   |
| IMC Networks USB2.0 HD UVC WebCam             | 25        | 2.9%    |
| Realtek Integrated_Webcam_HD                  | 22        | 2.55%   |
| Bison Integrated Camera                       | 21        | 2.44%   |
| Logitech Webcam C270                          | 19        | 2.2%    |
| Chicony HD WebCam                             | 15        | 1.74%   |
| Samsung Galaxy series, misc. (MTP mode)       | 13        | 1.51%   |
| Syntek Integrated Camera                      | 12        | 1.39%   |
| Sunplus Integrated_Webcam_HD                  | 12        | 1.39%   |
| Chicony HP HD Camera                          | 12        | 1.39%   |
| Logitech C922 Pro Stream Webcam               | 10        | 1.16%   |
| Lite-On Integrated Camera                     | 10        | 1.16%   |
| Chicony USB2.0 Camera                         | 9         | 1.04%   |
| Microdia GC02M2                               | 8         | 0.93%   |
| Logitech Webcam C310                          | 8         | 0.93%   |
| Quanta HD User Facing                         | 7         | 0.81%   |
| Logitech BRIO Ultra HD Webcam                 | 7         | 0.81%   |
| Sunplus HD WebCam                             | 6         | 0.7%    |
| Realtek Integrated Webcam HD                  | 6         | 0.7%    |
| Quanta HP Wide Vision HD Camera               | 6         | 0.7%    |
| Chicony Lenovo EasyCamera                     | 6         | 0.7%    |
| Bison SunplusIT Integrated Camera             | 6         | 0.7%    |
| Apple FaceTime HD Camera                      | 6         | 0.7%    |
| Luxvisions Innotech Limited Integrated Camera | 5         | 0.58%   |
| Chicony Integrated IR Camera                  | 5         | 0.58%   |
| Chicony Integrated Camera (1280x720@30)       | 5         | 0.58%   |
| Chicony HD User Facing                        | 5         | 0.58%   |
| Bison HD Webcam                               | 5         | 0.58%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X               | 5         | 0.58%   |
| Acer Integrated Camera                        | 5         | 0.58%   |
| Z-Star Venus USB2.0 Camera                    | 4         | 0.46%   |
| Sunplus HP Wide Vision HD                     | 4         | 0.46%   |
| Quanta RGB-IR Camera                          | 4         | 0.46%   |
| Quanta HP TrueVision HD Camera                | 4         | 0.46%   |
| Quanta HD Webcam                              | 4         | 0.46%   |
| Microdia Laptop_Integrated_Webcam_HD          | 4         | 0.46%   |
| Microdia Integrated_Webcam_FHD                | 4         | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 70        | 43.21%  |
| Validity Sensors           | 39        | 24.07%  |
| Shenzhen Goodix Technology | 28        | 17.28%  |
| Elan Microelectronics      | 8         | 4.94%   |
| STMicroelectronics         | 4         | 2.47%   |
| LighTuning Technology      | 4         | 2.47%   |
| AuthenTec                  | 4         | 2.47%   |
| DigitalPersona             | 3         | 1.85%   |
| Upek                       | 1         | 0.62%   |
| Samsung Electronics        | 1         | 0.62%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 26        | 16.05%  |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 15        | 9.26%   |
| Shenzhen Goodix  FingerPrint Device                       | 12        | 7.41%   |
| Validity Sensors Synaptics WBDI                           | 10        | 6.17%   |
| Shenzhen Goodix Fingerprint Reader                        | 10        | 6.17%   |
| Validity Sensors VFS495 Fingerprint Reader                | 9         | 5.56%   |
| Synaptics WBDI                                            | 8         | 4.94%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 7         | 4.32%   |
| Shenzhen Goodix FingerPrint                               | 6         | 3.7%    |
| Elan ELAN:Fingerprint                                     | 6         | 3.7%    |
| Synaptics UWP WBDI Device                                 | 5         | 3.09%   |
| Validity Sensors Fingerprint scanner                      | 4         | 2.47%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 4         | 2.47%   |
| STMicroelectronics Fingerprint Reader                     | 4         | 2.47%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 3         | 1.85%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint  | 3         | 1.85%   |
| Synaptics Fingerprint reader [HP G6]                      | 3         | 1.85%   |
| LighTuning EgisTec Touch Fingerprint Sensor               | 3         | 1.85%   |
| DigitalPersona Fingerprint Reader                         | 3         | 1.85%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor         | 2         | 1.23%   |
| Validity Sensors VFS491                                   | 2         | 1.23%   |
| Elan ELAN:ARM-M4                                          | 2         | 1.23%   |
| AuthenTec AES2501 Fingerprint Sensor                      | 2         | 1.23%   |
| Unknown                                                   | 2         | 1.23%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 1         | 0.62%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 0.62%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 1         | 0.62%   |
| Synaptics WBDI Device                                     | 1         | 0.62%   |
| Synaptics UWP WBDI                                        | 1         | 0.62%   |
| Synaptics  WBDI                                           | 1         | 0.62%   |
| Synaptics Metallica MOH Touch Fingerprint Reader          | 1         | 0.62%   |
| Samsung Fingerprint Sensor Device - 730B                  | 1         | 0.62%   |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 1         | 0.62%   |
| AuthenTec Fingerprint Sensor                              | 1         | 0.62%   |
| AuthenTec AES2550 Fingerprint Sensor                      | 1         | 0.62%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 40        | 34.48%  |
| Broadcom                          | 39        | 33.62%  |
| Upek                              | 5         | 4.31%   |
| Clay Logic                        | 5         | 4.31%   |
| Yubico.com                        | 4         | 3.45%   |
| SCM Microsystems                  | 4         | 3.45%   |
| O2 Micro                          | 4         | 3.45%   |
| Hewlett-Packard                   | 2         | 1.72%   |
| Gemalto (was Gemplus)             | 2         | 1.72%   |
| Advanced Card Systems             | 2         | 1.72%   |
| VASCO Data Security International | 1         | 0.86%   |
| Purism, SPC                       | 1         | 0.86%   |
| OmniKey                           | 1         | 0.86%   |
| Microchip Technology              | 1         | 0.86%   |
| Free Software Initiative of Japan | 1         | 0.86%   |
| Feitian Technologies              | 1         | 0.86%   |
| Bit4id                            | 1         | 0.86%   |
| Aladdin Knowledge Systems         | 1         | 0.86%   |
| Aktiv                             | 1         | 0.86%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 40        | 34.48%  |
| Broadcom 58200                                                               | 14        | 12.07%  |
| Broadcom 5880                                                                | 12        | 10.34%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 6.03%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 4.31%   |
| Clay Logic Nitrokey Pro                                                      | 5         | 4.31%   |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 4.31%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 4         | 3.45%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 2.59%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.72%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 2         | 1.72%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 2         | 1.72%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.72%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.86%   |
| Purism, SPC Librem Key                                                       | 1         | 0.86%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.86%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.86%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.86%   |
| Free Software Initiative of Japan Gnuk Token                                 | 1         | 0.86%   |
| Feitian Technologies U2F CCID KB                                             | 1         | 0.86%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.86%   |
| Bit4id miniLector-s                                                          | 1         | 0.86%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.86%   |
| Aktiv Rutoken lite                                                           | 1         | 0.86%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.86%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.86%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 746       | 43.3%   |
| 1     | 476       | 27.63%  |
| 2     | 239       | 13.87%  |
| 3     | 125       | 7.25%   |
| 4     | 75        | 4.35%   |
| 5     | 36        | 2.09%   |
| 6     | 20        | 1.16%   |
| 7     | 5         | 0.29%   |
| 8     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 309       | 17.56%  |
| Graphics card            | 235       | 13.35%  |
| Bluetooth                | 217       | 12.33%  |
| Camera                   | 184       | 10.45%  |
| Fingerprint reader       | 160       | 9.09%   |
| Net/wireless             | 131       | 7.44%   |
| Chipcard                 | 89        | 5.06%   |
| Sound                    | 82        | 4.66%   |
| Multimedia controller    | 78        | 4.43%   |
| Card reader              | 75        | 4.26%   |
| Network                  | 33        | 1.88%   |
| Net/ethernet             | 29        | 1.65%   |
| Firewire controller      | 29        | 1.65%   |
| Unassigned class         | 23        | 1.31%   |
| Modem                    | 21        | 1.19%   |
| Storage/ide              | 19        | 1.08%   |
| Storage/ata              | 15        | 0.85%   |
| Storage/raid             | 8         | 0.45%   |
| Tv card                  | 7         | 0.4%    |
| Storage                  | 6         | 0.34%   |
| Storage/nvme             | 4         | 0.23%   |
| Dvb card                 | 4         | 0.23%   |
| Wireless                 | 1         | 0.06%   |
| Unclassified device      | 1         | 0.06%   |

