CentOS 9 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for CentOS 9.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/CentOS_9/Desktop/README.md) and [notebooks](/Dist/CentOS_9/Notebook/README.md).

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

Total: 119

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 18E7                        | Desktop     | [4ed0c6182c](https://linux-hardware.org/?probe=4ed0c6182c) | Dec 21, 2024 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [6d27d6c54c](https://linux-hardware.org/?probe=6d27d6c54c) | Nov 22, 2024 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [90ebd3b804](https://linux-hardware.org/?probe=90ebd3b804) | Nov 22, 2024 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [645136fe14](https://linux-hardware.org/?probe=645136fe14) | Nov 22, 2024 |
| Positivo B... | VJFE41F11X-XXXXXX           | Notebook    | [0efd10fc40](https://linux-hardware.org/?probe=0efd10fc40) | Nov 21, 2024 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [fbfd923c5c](https://linux-hardware.org/?probe=fbfd923c5c) | Nov 11, 2024 |
| ASUSTek       | PRIME X570-P                | Desktop     | [c747936704](https://linux-hardware.org/?probe=c747936704) | Oct 20, 2024 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [313e850ec5](https://linux-hardware.org/?probe=313e850ec5) | Oct 14, 2024 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | Notebook    | [e6d4792686](https://linux-hardware.org/?probe=e6d4792686) | Oct 09, 2024 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [9abaa26cf8](https://linux-hardware.org/?probe=9abaa26cf8) | Sep 29, 2024 |
| Dell          | Latitude 3490               | Notebook    | [e0b48e8d4f](https://linux-hardware.org/?probe=e0b48e8d4f) | Sep 07, 2024 |
| AZW           | MINI S                      | Desktop     | [f9c5011b08](https://linux-hardware.org/?probe=f9c5011b08) | Sep 03, 2024 |
| AZW           | MINI S                      | Desktop     | [7a6ffcc519](https://linux-hardware.org/?probe=7a6ffcc519) | Sep 03, 2024 |
| Lenovo        | ThinkPad T470p 20J7002GP... | Notebook    | [4f6dfce3d8](https://linux-hardware.org/?probe=4f6dfce3d8) | Aug 23, 2024 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [84cb8afc07](https://linux-hardware.org/?probe=84cb8afc07) | Aug 18, 2024 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [a83776fa56](https://linux-hardware.org/?probe=a83776fa56) | Aug 15, 2024 |
| Lenovo        | ThinkPad W510 431967G       | Notebook    | [58cb012163](https://linux-hardware.org/?probe=58cb012163) | Aug 06, 2024 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [6cabf822ae](https://linux-hardware.org/?probe=6cabf822ae) | Aug 03, 2024 |
| Dell          | Inspiron 3576               | Notebook    | [f14330846e](https://linux-hardware.org/?probe=f14330846e) | Aug 02, 2024 |
| Gigabyte      | TRX50 AERO D                | Desktop     | [8a253c988f](https://linux-hardware.org/?probe=8a253c988f) | Jul 20, 2024 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [03405c1729](https://linux-hardware.org/?probe=03405c1729) | Jul 17, 2024 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [786c05a4a8](https://linux-hardware.org/?probe=786c05a4a8) | Jul 15, 2024 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [2431de91a7](https://linux-hardware.org/?probe=2431de91a7) | Jul 15, 2024 |
| Google        | Lick                        | Notebook    | [f8ad9ee153](https://linux-hardware.org/?probe=f8ad9ee153) | Jul 12, 2024 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [e7c9470e44](https://linux-hardware.org/?probe=e7c9470e44) | Jun 23, 2024 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [3b70ac5b2a](https://linux-hardware.org/?probe=3b70ac5b2a) | Jun 23, 2024 |
| Supermicro    | X10DRI-TB                   | Server      | [6dc8dfa9e3](https://linux-hardware.org/?probe=6dc8dfa9e3) | Jun 18, 2024 |
| Dell          | 0D4JCX A04                  | Server      | [e87c223500](https://linux-hardware.org/?probe=e87c223500) | Jun 11, 2024 |
| Supermicro    | X10DRI-TB                   | Server      | [a42aac47d4](https://linux-hardware.org/?probe=a42aac47d4) | Jun 11, 2024 |
| Dell          | 0D4JCX A04                  | Server      | [de94679aac](https://linux-hardware.org/?probe=de94679aac) | Jun 11, 2024 |
| Dell          | 0TKD84 A02                  | Server      | [9b82766db5](https://linux-hardware.org/?probe=9b82766db5) | Jun 08, 2024 |
| Supermicro    | X10DRL-i                    | Server      | [aec8be386b](https://linux-hardware.org/?probe=aec8be386b) | Jun 07, 2024 |
| HUAWEI        | IT21EKMA V200R002C00        | Server      | [5bdd494f43](https://linux-hardware.org/?probe=5bdd494f43) | May 24, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [994aae0769](https://linux-hardware.org/?probe=994aae0769) | Apr 21, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [e26cecc411](https://linux-hardware.org/?probe=e26cecc411) | Apr 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [05372f86e5](https://linux-hardware.org/?probe=05372f86e5) | Apr 10, 2024 |
| Lenovo        | ThinkPad X390 20Q00039CD    | Notebook    | [9e8475784d](https://linux-hardware.org/?probe=9e8475784d) | Apr 05, 2024 |
| Micro Comp... | Venus series                | Notebook    | [ec0a83d39a](https://linux-hardware.org/?probe=ec0a83d39a) | Mar 27, 2024 |
| Dell          | 02C2CP A04                  | Server      | [2eb0ecb18c](https://linux-hardware.org/?probe=2eb0ecb18c) | Mar 15, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [0bea57057c](https://linux-hardware.org/?probe=0bea57057c) | Mar 13, 2024 |
| Notebook      | P377SM-A                    | Notebook    | [c073b6897b](https://linux-hardware.org/?probe=c073b6897b) | Mar 05, 2024 |
| Dell          | Precision 5560              | Notebook    | [e500714178](https://linux-hardware.org/?probe=e500714178) | Feb 22, 2024 |
| Dell          | Precision 5520              | Notebook    | [47f7336949](https://linux-hardware.org/?probe=47f7336949) | Jan 30, 2024 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [5a711c0ff0](https://linux-hardware.org/?probe=5a711c0ff0) | Jan 20, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [6c329db1cf](https://linux-hardware.org/?probe=6c329db1cf) | Jan 18, 2024 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [7adc9b4d41](https://linux-hardware.org/?probe=7adc9b4d41) | Jan 06, 2024 |
| Dell          | G5 5505                     | Notebook    | [fd284cda8a](https://linux-hardware.org/?probe=fd284cda8a) | Jan 04, 2024 |
| MSI           | MAG B760M MORTAR WIFI       | Desktop     | [342164a6a4](https://linux-hardware.org/?probe=342164a6a4) | Dec 29, 2023 |
| SHANGZHAOY... | B85M-PRO V1.1               | Desktop     | [bd7c6e2693](https://linux-hardware.org/?probe=bd7c6e2693) | Dec 22, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [e8965075d3](https://linux-hardware.org/?probe=e8965075d3) | Dec 14, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [e9e5956d89](https://linux-hardware.org/?probe=e9e5956d89) | Dec 10, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [ecc33f393d](https://linux-hardware.org/?probe=ecc33f393d) | Nov 22, 2023 |
| MSI           | MEG Z790 ACE                | Desktop     | [41d0e4fddd](https://linux-hardware.org/?probe=41d0e4fddd) | Oct 24, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [f23d8804a7](https://linux-hardware.org/?probe=f23d8804a7) | Oct 11, 2023 |
| Dell          | 0HJK12 A03                  | Server      | [b4ec3650ef](https://linux-hardware.org/?probe=b4ec3650ef) | Sep 11, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [ecf1a70c5d](https://linux-hardware.org/?probe=ecf1a70c5d) | Sep 08, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [149cb27e46](https://linux-hardware.org/?probe=149cb27e46) | Aug 18, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [dfcebaef82](https://linux-hardware.org/?probe=dfcebaef82) | Aug 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [888c56f232](https://linux-hardware.org/?probe=888c56f232) | Aug 01, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [993a10a30b](https://linux-hardware.org/?probe=993a10a30b) | Aug 01, 2023 |
| Dell          | 07978V A05                  | Server      | [8e1deb831f](https://linux-hardware.org/?probe=8e1deb831f) | Jul 26, 2023 |
| Intel         | NUC7i3BNB J22859-315        | Mini pc     | [8b2dd0b294](https://linux-hardware.org/?probe=8b2dd0b294) | Jul 07, 2023 |
| IBM           | 69Y1006 SIT                 | Server      | [b34e147b1c](https://linux-hardware.org/?probe=b34e147b1c) | Jun 25, 2023 |
| Gateway       | H61H2-AD V1.0               | Desktop     | [9a34a9295c](https://linux-hardware.org/?probe=9a34a9295c) | Jun 15, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [d93dbf6db3](https://linux-hardware.org/?probe=d93dbf6db3) | Jun 01, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [16c7ca187a](https://linux-hardware.org/?probe=16c7ca187a) | Jun 01, 2023 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [a69366e2b7](https://linux-hardware.org/?probe=a69366e2b7) | May 29, 2023 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [07202660b9](https://linux-hardware.org/?probe=07202660b9) | May 26, 2023 |
| Acer          | Predator G3-605             | Desktop     | [6f91022c83](https://linux-hardware.org/?probe=6f91022c83) | May 04, 2023 |
| Colorful T... | CVN Z590 GAMING PRO V20     | Desktop     | [209ec5e477](https://linux-hardware.org/?probe=209ec5e477) | Apr 28, 2023 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | Notebook    | [61408603be](https://linux-hardware.org/?probe=61408603be) | Apr 21, 2023 |
| Intel         | NUC12WSBi5 M63398-302       | Mini pc     | [785a41f4e9](https://linux-hardware.org/?probe=785a41f4e9) | Apr 02, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [d148f91b52](https://linux-hardware.org/?probe=d148f91b52) | Mar 15, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [eecf7c5d8b](https://linux-hardware.org/?probe=eecf7c5d8b) | Mar 13, 2023 |
| ASUSTek       | Q550LF                      | Notebook    | [793bf0d1d8](https://linux-hardware.org/?probe=793bf0d1d8) | Mar 06, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [a7270cf962](https://linux-hardware.org/?probe=a7270cf962) | Feb 19, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [a67a4d078f](https://linux-hardware.org/?probe=a67a4d078f) | Jan 21, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [259556fd6f](https://linux-hardware.org/?probe=259556fd6f) | Jan 11, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [b9522e3683](https://linux-hardware.org/?probe=b9522e3683) | Jan 02, 2023 |
| Lenovo        | ThinkPad T430 2347DE9       | Notebook    | [7b4305ce5a](https://linux-hardware.org/?probe=7b4305ce5a) | Dec 27, 2022 |
| Lenovo        | ThinkPad T430 2347DE9       | Notebook    | [afc91c5da0](https://linux-hardware.org/?probe=afc91c5da0) | Dec 24, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [117f4c04d6](https://linux-hardware.org/?probe=117f4c04d6) | Dec 21, 2022 |
| Dell          | 0NKW6Y A02                  | Desktop     | [f20d5b9289](https://linux-hardware.org/?probe=f20d5b9289) | Dec 07, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [b2aac5194c](https://linux-hardware.org/?probe=b2aac5194c) | Dec 06, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [6ca3196f35](https://linux-hardware.org/?probe=6ca3196f35) | Dec 05, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [558174d9f4](https://linux-hardware.org/?probe=558174d9f4) | Nov 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e840ded8c0](https://linux-hardware.org/?probe=e840ded8c0) | Nov 09, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [b981adc21a](https://linux-hardware.org/?probe=b981adc21a) | Nov 07, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [8ee7171b61](https://linux-hardware.org/?probe=8ee7171b61) | Nov 03, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [9598c40129](https://linux-hardware.org/?probe=9598c40129) | Oct 27, 2022 |
| Zvezda        | Arctur test_serv            | Server      | [0ace3642f0](https://linux-hardware.org/?probe=0ace3642f0) | Oct 21, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [8bd50f112b](https://linux-hardware.org/?probe=8bd50f112b) | Oct 15, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [88497baf29](https://linux-hardware.org/?probe=88497baf29) | Oct 15, 2022 |
| Intel         | D34010WYK H14771-303        | Desktop     | [e58d9849a5](https://linux-hardware.org/?probe=e58d9849a5) | Oct 06, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [2293724ae2](https://linux-hardware.org/?probe=2293724ae2) | Sep 19, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [09db514840](https://linux-hardware.org/?probe=09db514840) | Sep 19, 2022 |
| Lenovo        | ThinkPad T430 2349DG5       | Notebook    | [740898521d](https://linux-hardware.org/?probe=740898521d) | Aug 27, 2022 |
| AZW           | SER V01                     | Mini pc     | [873aac6635](https://linux-hardware.org/?probe=873aac6635) | Aug 11, 2022 |
| Timi          | Mi NoteBook Horizon Edit... | Notebook    | [52a0cb298b](https://linux-hardware.org/?probe=52a0cb298b) | Aug 09, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [e115d77240](https://linux-hardware.org/?probe=e115d77240) | Aug 07, 2022 |
| Lenovo        | G410 20237                  | Notebook    | [daea3239f0](https://linux-hardware.org/?probe=daea3239f0) | Aug 05, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [46201e4773](https://linux-hardware.org/?probe=46201e4773) | Jul 27, 2022 |
| Dell          | CS24-TY                     | Server      | [230ad2532f](https://linux-hardware.org/?probe=230ad2532f) | Jul 24, 2022 |
| NCR           | Pocono BIOS.6.0             | Desktop     | [ae030a0cda](https://linux-hardware.org/?probe=ae030a0cda) | Jul 15, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [c45dba9246](https://linux-hardware.org/?probe=c45dba9246) | Jun 26, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [3d36beed4b](https://linux-hardware.org/?probe=3d36beed4b) | Jun 25, 2022 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [88a7cd954c](https://linux-hardware.org/?probe=88a7cd954c) | Jun 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [29f2cd44d5](https://linux-hardware.org/?probe=29f2cd44d5) | Jun 11, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [9a331b90a5](https://linux-hardware.org/?probe=9a331b90a5) | May 19, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [4c3a3b2de2](https://linux-hardware.org/?probe=4c3a3b2de2) | May 17, 2022 |
| MSI           | Katana GF76 12UE            | Notebook    | [460e78b93a](https://linux-hardware.org/?probe=460e78b93a) | May 15, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [a7fb96d9aa](https://linux-hardware.org/?probe=a7fb96d9aa) | May 13, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | Notebook    | [228ec1a5f7](https://linux-hardware.org/?probe=228ec1a5f7) | Apr 24, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [db53151112](https://linux-hardware.org/?probe=db53151112) | Apr 19, 2022 |
| Timi          | RedmiBook 16                | Notebook    | [bef46c5065](https://linux-hardware.org/?probe=bef46c5065) | Mar 20, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [1f84b1e42d](https://linux-hardware.org/?probe=1f84b1e42d) | Mar 11, 2022 |
| Lenovo        | ThinkPad T460s 20FAS5WX0... | Notebook    | [6fa180d5fa](https://linux-hardware.org/?probe=6fa180d5fa) | Feb 06, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [cf90d5430c](https://linux-hardware.org/?probe=cf90d5430c) | Feb 04, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [0c661cb2d6](https://linux-hardware.org/?probe=0c661cb2d6) | Nov 12, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.14.0-362.el9.x86_64       | 4         | 4.12%   |
| 5.14.0-86.el9.x86_64        | 3         | 3.09%   |
| 5.14.0-511.el9.x86_64       | 3         | 3.09%   |
| 5.14.0-480.el9.x86_64       | 3         | 3.09%   |
| 5.14.0-432.el9.x86_64       | 3         | 3.09%   |
| 5.14.0-391.el9.x86_64       | 3         | 3.09%   |
| 5.14.0-202.el9.x86_64       | 3         | 3.09%   |
| 5.14.0-134.el9.x86_64       | 3         | 3.09%   |
| 5.14.0-496.el9.x86_64       | 2         | 2.06%   |
| 5.14.0-479.el9.x86_64       | 2         | 2.06%   |
| 5.14.0-427.el9.x86_64       | 2         | 2.06%   |
| 5.14.0-407.el9.x86_64       | 2         | 2.06%   |
| 5.14.0-333.el9.x86_64       | 2         | 2.06%   |
| 5.14.0-325.el9.x86_64       | 2         | 2.06%   |
| 5.14.0-319.el9.x86_64       | 2         | 2.06%   |
| 5.14.0-214.el9.x86_64       | 2         | 2.06%   |
| 5.14.0-183.el9.x86_64       | 2         | 2.06%   |
| 5.14.0-171.el9.x86_64       | 2         | 2.06%   |
| 5.14.0-148.el9.x86_64       | 2         | 2.06%   |
| 6.10.6-1.el9.elrepo.x86_64  | 1         | 1.03%   |
| 6.1.8-1.el9.elrepo.x86_64   | 1         | 1.03%   |
| 6.1.102-1.el9.elrepo.x86_64 | 1         | 1.03%   |
| 6.1.1                       | 1         | 1.03%   |
| 5.17.2-lqx3.0.el9.x86_64    | 1         | 1.03%   |
| 5.14.0-78.el9.x86_64        | 1         | 1.03%   |
| 5.14.0-71.el9.x86_64        | 1         | 1.03%   |
| 5.14.0-66.el9.x86_64        | 1         | 1.03%   |
| 5.14.0-542.el9.x86_64       | 1         | 1.03%   |
| 5.14.0-529.el9.x86_64       | 1         | 1.03%   |
| 5.14.0-522.el9.x86_64       | 1         | 1.03%   |
| 5.14.0-52.el9.x86_64        | 1         | 1.03%   |
| 5.14.0-516.el9.x86_64       | 1         | 1.03%   |
| 5.14.0-514.el9.x86_64       | 1         | 1.03%   |
| 5.14.0-474.el9.x86_64       | 1         | 1.03%   |
| 5.14.0-460.el9.x86_64       | 1         | 1.03%   |
| 5.14.0-447.el9.aarch64      | 1         | 1.03%   |
| 5.14.0-44.el9.x86_64        | 1         | 1.03%   |
| 5.14.0-437.el9.x86_64       | 1         | 1.03%   |
| 5.14.0-435.el9.x86_64       | 1         | 1.03%   |
| 5.14.0-425.el9.x86_64       | 1         | 1.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 79        | 92.94%  |
| 6.10.6  | 1         | 1.18%   |
| 6.1.8   | 1         | 1.18%   |
| 6.1.102 | 1         | 1.18%   |
| 6.1.1   | 1         | 1.18%   |
| 5.17.2  | 1         | 1.18%   |
| 4.18.0  | 1         | 1.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 79        | 92.94%  |
| 6.1     | 3         | 3.53%   |
| 6.10    | 1         | 1.18%   |
| 5.17    | 1         | 1.18%   |
| 4.18    | 1         | 1.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 83        | 98.81%  |
| aarch64 | 1         | 1.19%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 68        | 80.95%  |
| KDE5          | 7         | 8.33%   |
| Unknown       | 5         | 5.95%   |
| GNOME Classic | 3         | 3.57%   |
| MATE          | 1         | 1.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 53        | 62.35%  |
| X11     | 26        | 30.59%  |
| Tty     | 3         | 3.53%   |
| Web     | 2         | 2.35%   |
| Unknown | 1         | 1.18%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 42        | 48.84%  |
| GDM     | 38        | 44.19%  |
| SDDM    | 4         | 4.65%   |
| LightDM | 2         | 2.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 53        | 63.1%   |
| de_DE   | 5         | 5.95%   |
| ru_RU   | 4         | 4.76%   |
| pt_BR   | 4         | 4.76%   |
| zh_CN   | 2         | 2.38%   |
| ja_JP   | 2         | 2.38%   |
| it_IT   | 2         | 2.38%   |
| en_GB   | 2         | 2.38%   |
| en_AU   | 2         | 2.38%   |
| sv_SE   | 1         | 1.19%   |
| ru_UA   | 1         | 1.19%   |
| ro_RO   | 1         | 1.19%   |
| fr_FR   | 1         | 1.19%   |
| fr_CA   | 1         | 1.19%   |
| en_IN   | 1         | 1.19%   |
| C       | 1         | 1.19%   |
| Unknown | 1         | 1.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 64        | 75.29%  |
| BIOS | 21        | 24.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Xfs   | 76        | 90.48%  |
| Ext4  | 7         | 8.33%   |
| Tmpfs | 1         | 1.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 40        | 45.98%  |
| Unknown | 36        | 41.38%  |
| MBR     | 11        | 12.64%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 85.88%  |
| Yes       | 12        | 14.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 65        | 74.71%  |
| Yes       | 22        | 25.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Lenovo                           | 17        | 20.24%  |
| ASUSTek Computer                 | 14        | 16.67%  |
| Dell                             | 12        | 14.29%  |
| Hewlett-Packard                  | 7         | 8.33%   |
| MSI                              | 4         | 4.76%   |
| Intel                            | 4         | 4.76%   |
| Gigabyte Technology              | 4         | 4.76%   |
| Acer                             | 4         | 4.76%   |
| Timi                             | 2         | 2.38%   |
| Supermicro                       | 2         | 2.38%   |
| AZW                              | 2         | 2.38%   |
| Zvezda                           | 1         | 1.19%   |
| SHANGZHAOYUAN                    | 1         | 1.19%   |
| Samsung Electronics              | 1         | 1.19%   |
| Razer                            | 1         | 1.19%   |
| Positivo Bahia - VAIO            | 1         | 1.19%   |
| Notebook                         | 1         | 1.19%   |
| Micro Computer (HK) Tech Limited | 1         | 1.19%   |
| IP3 Tech                         | 1         | 1.19%   |
| IBM                              | 1         | 1.19%   |
| HUAWEI                           | 1         | 1.19%   |
| Gateway                          | 1         | 1.19%   |
| Colorful Technology              | 1         | 1.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| ASUS PRIME H670-PLUS D4                     | 2         | 2.38%   |
| Zvezda Altair Z                             | 1         | 1.19%   |
| Timi RedmiBook 16                           | 1         | 1.19%   |
| Timi Mi NoteBook Horizon Edition 14         | 1         | 1.19%   |
| Supermicro X10DRi                           | 1         | 1.19%   |
| Supermicro Super Server                     | 1         | 1.19%   |
| SHANGZHAOYUAN B85M-PRO V1.1                 | 1         | 1.19%   |
| Samsung 355V4C/356V4C/3445VC/3545VC         | 1         | 1.19%   |
| Razer Blade 15 (2022) - RZ09-0421           | 1         | 1.19%   |
| Positivo Bahia - VAIO VJFE41F11X-XXXXXX     | 1         | 1.19%   |
| Notebook P377SM-A                           | 1         | 1.19%   |
| MSI MS-7E01                                 | 1         | 1.19%   |
| MSI MS-7D86                                 | 1         | 1.19%   |
| MSI MS-7B79                                 | 1         | 1.19%   |
| MSI Katana GF76 12UE                        | 1         | 1.19%   |
| Micro (HK) Tech Limited Venus series        | 1         | 1.19%   |
| Lenovo Yoga S740-14IIL 81RS                 | 1         | 1.19%   |
| Lenovo V15 G2 ITL 82KB                      | 1         | 1.19%   |
| Lenovo ThinkPad X390 20Q00039CD             | 1         | 1.19%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBCTO1WW | 1         | 1.19%   |
| Lenovo ThinkPad W510 431967G                | 1         | 1.19%   |
| Lenovo ThinkPad T470p 20J7002GPH            | 1         | 1.19%   |
| Lenovo ThinkPad T460s 20FAS5WX00            | 1         | 1.19%   |
| Lenovo ThinkPad T430 2349DG5                | 1         | 1.19%   |
| Lenovo ThinkPad T430 2347DE9                | 1         | 1.19%   |
| Lenovo ThinkPad T15 Gen 1 20S7S43600        | 1         | 1.19%   |
| Lenovo ThinkPad L14 Gen 1 20U5S0NT00        | 1         | 1.19%   |
| Lenovo ThinkCentre M900 10FGS0301H          | 1         | 1.19%   |
| Lenovo Legion 5P 15IMH05H 82AW              | 1         | 1.19%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 1         | 1.19%   |
| Lenovo IdeaPad 5 14ITL05 82FE               | 1         | 1.19%   |
| Lenovo G580 20150                           | 1         | 1.19%   |
| Lenovo G410 20237                           | 1         | 1.19%   |
| IP3 Tech HeroBox                            | 1         | 1.19%   |
| Intel NUC7i3BNK                             | 1         | 1.19%   |
| Intel NUC12WSHi7                            | 1         | 1.19%   |
| Intel NUC12WSHi5                            | 1         | 1.19%   |
| Intel D34010WYK H14771-303                  | 1         | 1.19%   |
| IBM System x3250 M3 -[425242G]              | 1         | 1.19%   |
| HUAWEI Atlas 500 Pro (Model 3000)           | 1         | 1.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo ThinkPad                         | 9         | 10.71%  |
| Dell PowerEdge                          | 5         | 5.95%   |
| HP EliteBook                            | 3         | 3.57%   |
| ASUS ROG                                | 3         | 3.57%   |
| ASUS PRIME                              | 3         | 3.57%   |
| Lenovo IdeaPad                          | 2         | 2.38%   |
| Dell Precision                          | 2         | 2.38%   |
| Acer Aspire                             | 2         | 2.38%   |
| Zvezda Altair                           | 1         | 1.19%   |
| Timi RedmiBook                          | 1         | 1.19%   |
| Timi Mi                                 | 1         | 1.19%   |
| Supermicro X10DRi                       | 1         | 1.19%   |
| Supermicro Super                        | 1         | 1.19%   |
| SHANGZHAOYUAN B85M-PRO                  | 1         | 1.19%   |
| Samsung 355V4C                          | 1         | 1.19%   |
| Razer Blade                             | 1         | 1.19%   |
| Positivo Bahia - VAIO VJFE41F11X-XXXXXX | 1         | 1.19%   |
| Notebook P377SM-A                       | 1         | 1.19%   |
| MSI MS-7E01                             | 1         | 1.19%   |
| MSI MS-7D86                             | 1         | 1.19%   |
| MSI MS-7B79                             | 1         | 1.19%   |
| MSI Katana                              | 1         | 1.19%   |
| Micro (HK) Tech Limited Venus           | 1         | 1.19%   |
| Lenovo Yoga                             | 1         | 1.19%   |
| Lenovo V15                              | 1         | 1.19%   |
| Lenovo ThinkCentre                      | 1         | 1.19%   |
| Lenovo Legion                           | 1         | 1.19%   |
| Lenovo G580                             | 1         | 1.19%   |
| Lenovo G410                             | 1         | 1.19%   |
| IP3 Tech HeroBox                        | 1         | 1.19%   |
| Intel NUC7i3BNK                         | 1         | 1.19%   |
| Intel NUC12WSHi7                        | 1         | 1.19%   |
| Intel NUC12WSHi5                        | 1         | 1.19%   |
| Intel D34010WYK                         | 1         | 1.19%   |
| IBM System                              | 1         | 1.19%   |
| HUAWEI Atlas                            | 1         | 1.19%   |
| HP Spectre                              | 1         | 1.19%   |
| HP ProDesk                              | 1         | 1.19%   |
| HP Pavilion                             | 1         | 1.19%   |
| HP Laptop                               | 1         | 1.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 14        | 16.67%  |
| 2013 | 12        | 14.29%  |
| 2022 | 11        | 13.1%   |
| 2021 | 10        | 11.9%   |
| 2019 | 8         | 9.52%   |
| 2023 | 4         | 4.76%   |
| 2018 | 4         | 4.76%   |
| 2017 | 4         | 4.76%   |
| 2012 | 4         | 4.76%   |
| 2014 | 3         | 3.57%   |
| 2011 | 3         | 3.57%   |
| 2016 | 2         | 2.38%   |
| 2015 | 2         | 2.38%   |
| 2010 | 2         | 2.38%   |
| 2009 | 1         | 1.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 40        | 47.62%  |
| Desktop     | 27        | 32.14%  |
| Server      | 10        | 11.9%   |
| Mini pc     | 5         | 5.95%   |
| Convertible | 2         | 2.38%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 79        | 94.05%  |
| Enabled  | 5         | 5.95%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 84        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 27        | 32.14%  |
| 8.01-16.0       | 20        | 23.81%  |
| 64.01-256.0     | 15        | 17.86%  |
| 32.01-64.0      | 12        | 14.29%  |
| More than 256.0 | 3         | 3.57%   |
| 3.01-4.0        | 3         | 3.57%   |
| 24.01-32.0      | 2         | 2.38%   |
| 16.01-24.0      | 2         | 2.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 32        | 35.96%  |
| 3.01-4.0   | 20        | 22.47%  |
| 4.01-8.0   | 19        | 21.35%  |
| 1.01-2.0   | 6         | 6.74%   |
| 8.01-16.0  | 6         | 6.74%   |
| 16.01-24.0 | 3         | 3.37%   |
| 0.51-1.0   | 2         | 2.25%   |
| 32.01-64.0 | 1         | 1.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 42        | 50%     |
| 2      | 17        | 20.24%  |
| 3      | 10        | 11.9%   |
| 4      | 7         | 8.33%   |
| 5      | 3         | 3.57%   |
| 10     | 2         | 2.38%   |
| 26     | 1         | 1.19%   |
| 25     | 1         | 1.19%   |
| 20     | 1         | 1.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 66        | 78.57%  |
| Yes       | 18        | 21.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 86.9%   |
| No        | 11        | 13.1%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 72.62%  |
| No        | 23        | 27.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 66.67%  |
| No        | 28        | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 16        | 19.05%  |
| Brazil       | 9         | 10.71%  |
| Germany      | 8         | 9.52%   |
| Russia       | 5         | 5.95%   |
| China        | 5         | 5.95%   |
| Australia    | 4         | 4.76%   |
| Italy        | 3         | 3.57%   |
| Canada       | 3         | 3.57%   |
| Bulgaria     | 3         | 3.57%   |
| Ukraine      | 2         | 2.38%   |
| Poland       | 2         | 2.38%   |
| Japan        | 2         | 2.38%   |
| Finland      | 2         | 2.38%   |
| Vietnam      | 1         | 1.19%   |
| Uzbekistan   | 1         | 1.19%   |
| Switzerland  | 1         | 1.19%   |
| Sweden       | 1         | 1.19%   |
| South Africa | 1         | 1.19%   |
| Romania      | 1         | 1.19%   |
| Puerto Rico  | 1         | 1.19%   |
| Philippines  | 1         | 1.19%   |
| Norway       | 1         | 1.19%   |
| Netherlands  | 1         | 1.19%   |
| Myanmar      | 1         | 1.19%   |
| Kenya        | 1         | 1.19%   |
| Kazakhstan   | 1         | 1.19%   |
| India        | 1         | 1.19%   |
| Greece       | 1         | 1.19%   |
| France       | 1         | 1.19%   |
| Colombia     | 1         | 1.19%   |
| Chile        | 1         | 1.19%   |
| Belarus      | 1         | 1.19%   |
| Argentina    | 1         | 1.19%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Moscow               | 3         | 3.45%   |
| Beijing              | 3         | 3.45%   |
| Sofia                | 2         | 2.3%    |
| Rio de Janeiro       | 2         | 2.3%    |
| Itaperuna            | 2         | 2.3%    |
| Canberra             | 2         | 2.3%    |
| Bristow              | 2         | 2.3%    |
| Yangpu               | 1         | 1.15%   |
| Yangon               | 1         | 1.15%   |
| Yakima               | 1         | 1.15%   |
| Wuhan                | 1         | 1.15%   |
| Vitebsk              | 1         | 1.15%   |
| Vicenza              | 1         | 1.15%   |
| Tyumen               | 1         | 1.15%   |
| Tromsø              | 1         | 1.15%   |
| Tomah                | 1         | 1.15%   |
| Tashkent             | 1         | 1.15%   |
| Sykesville           | 1         | 1.15%   |
| Stromberg            | 1         | 1.15%   |
| Stockholm            | 1         | 1.15%   |
| Soest                | 1         | 1.15%   |
| Schemmerhofen        | 1         | 1.15%   |
| Sao Paulo            | 1         | 1.15%   |
| Sao José dos Campos | 1         | 1.15%   |
| Sanford              | 1         | 1.15%   |
| San Juan             | 1         | 1.15%   |
| Ruda Śląska        | 1         | 1.15%   |
| Rome                 | 1         | 1.15%   |
| Ribeirao Preto       | 1         | 1.15%   |
| Quitman              | 1         | 1.15%   |
| Québec              | 1         | 1.15%   |
| Puente Alto          | 1         | 1.15%   |
| Porto Alegre         | 1         | 1.15%   |
| Portland             | 1         | 1.15%   |
| Plano                | 1         | 1.15%   |
| Perth                | 1         | 1.15%   |
| Persan               | 1         | 1.15%   |
| Ozarow Mazowiecki    | 1         | 1.15%   |
| Okazaki              | 1         | 1.15%   |
| Offenbach            | 1         | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 23        | 35     | 17.42%  |
| Seagate                   | 17        | 72     | 12.88%  |
| WDC                       | 14        | 22     | 10.61%  |
| Kingston                  | 11        | 16     | 8.33%   |
| Toshiba                   | 10        | 19     | 7.58%   |
| SK hynix                  | 5         | 5      | 3.79%   |
| SanDisk                   | 5         | 22     | 3.79%   |
| Micron Technology         | 5         | 5      | 3.79%   |
| Intel                     | 4         | 4      | 3.03%   |
| HGST                      | 4         | 15     | 3.03%   |
| Crucial                   | 3         | 19     | 2.27%   |
| Phison Electronics        | 2         | 2      | 1.52%   |
| LITEON                    | 2         | 2      | 1.52%   |
| DELLBOSS                  | 2         | 2      | 1.52%   |
| ASMT                      | 2         | 2      | 1.52%   |
| WD MediaMax               | 1         | 1      | 0.76%   |
| VICKTER                   | 1         | 1      | 0.76%   |
| Unknown                   | 1         | 1      | 0.76%   |
| Union Memory              | 1         | 1      | 0.76%   |
| Team                      | 1         | 2      | 0.76%   |
| SPCC                      | 1         | 1      | 0.76%   |
| Plextor                   | 1         | 1      | 0.76%   |
| Phison                    | 1         | 1      | 0.76%   |
| OCZ                       | 1         | 1      | 0.76%   |
| Netac                     | 1         | 2      | 0.76%   |
| Micron/Crucial Technology | 1         | 1      | 0.76%   |
| KIOXIA                    | 1         | 1      | 0.76%   |
| Intenso                   | 1         | 1      | 0.76%   |
| HS-SSD-E100               | 1         | 1      | 0.76%   |
| Hjwdz                     | 1         | 1      | 0.76%   |
| Hitachi                   | 1         | 1      | 0.76%   |
| Hewlett-Packard           | 1         | 1      | 0.76%   |
| Gigabyte Technology       | 1         | 2      | 0.76%   |
| ETOPSO                    | 1         | 1      | 0.76%   |
| China                     | 1         | 1      | 0.76%   |
| Biwin Storage Technology  | 1         | 1      | 0.76%   |
| ADATA Technology          | 1         | 1      | 0.76%   |
| A-DATA Technology         | 1         | 1      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 4         | 2.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 3         | 2.04%   |
| SK hynix BC511 512GB                                 | 2         | 1.36%   |
| Seagate ST1000DM010-2EP102 1TB                       | 2         | 1.36%   |
| Sandisk WD_BLACK SN770 1TB                           | 2         | 1.36%   |
| SanDisk SDSSDH3 1T00 1TB                             | 2         | 1.36%   |
| Samsung MZNLH512HALU-00000 512GB SSD                 | 2         | 1.36%   |
| Micron 2450_MTFDKBA512TFK 512GB                      | 2         | 1.36%   |
| DELLBOSS VD 480GB                                    | 2         | 1.36%   |
| Crucial CT525MX300SSD1 528GB                         | 2         | 1.36%   |
| ASMT 2115 320GB                                      | 2         | 1.36%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                     | 1         | 0.68%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                     | 1         | 0.68%   |
| WDC WD6400BEVT-22A0RT0 640GB                         | 1         | 0.68%   |
| WDC WD60EFRX-68L0BN1 6TB                             | 1         | 0.68%   |
| WDC WD6003FZBX-00K5WB0 6TB                           | 1         | 0.68%   |
| WDC WD5000LPLX-60ZNTT1 500GB                         | 1         | 0.68%   |
| WDC WD5000BEVT-55A0RT0 500GB                         | 1         | 0.68%   |
| WDC WD3200AAKX-753CA1 320GB                          | 1         | 0.68%   |
| WDC WD2500AAJS-60M0A0 250GB                          | 1         | 0.68%   |
| WDC WD22EJRX-89BEMY0 2TB                             | 1         | 0.68%   |
| WDC WD20EZAZ-00GGJB0 2TB                             | 1         | 0.68%   |
| WDC WD2003FZEX-00Z4SA0 2TB                           | 1         | 0.68%   |
| WDC WD10EZEX-60M2NA0 1TB                             | 1         | 0.68%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 1         | 0.68%   |
| WDC WD10EZEX-00BN5A0 1TB                             | 1         | 0.68%   |
| WDC WD Blue SA510 2.5 500GB                          | 1         | 0.68%   |
| WD MediaMax WL750GSA6472 752GB                       | 1         | 0.68%   |
| VICKTER SSD 128GB                                    | 1         | 0.68%   |
| Unknown MMC Card  7GB                                | 1         | 0.68%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB              | 1         | 0.68%   |
| Toshiba MQ04ABF100 1TB                               | 1         | 0.68%   |
| Toshiba MQ01ABD100 1TB                               | 1         | 0.68%   |
| Toshiba MK2561GSYN 250GB                             | 1         | 0.68%   |
| Toshiba MK1234GSX 120GB                              | 1         | 0.68%   |
| Toshiba MG07ACA14TEY 14TB                            | 1         | 0.68%   |
| Toshiba KXG50ZNV512G 512GB                           | 1         | 0.68%   |
| Toshiba HDWR160 6TB                                  | 1         | 0.68%   |
| Toshiba DT01ACA200 2TB                               | 1         | 0.68%   |
| Toshiba DT01ACA100 1TB                               | 1         | 0.68%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 16        | 70     | 34.04%  |
| WDC         | 12        | 19     | 25.53%  |
| Toshiba     | 9         | 17     | 19.15%  |
| HGST        | 4         | 15     | 8.51%   |
| DELLBOSS    | 2         | 2      | 4.26%   |
| ASMT        | 2         | 2      | 4.26%   |
| WD MediaMax | 1         | 1      | 2.13%   |
| Hitachi     | 1         | 1      | 2.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 24     | 28%     |
| Kingston            | 8         | 13     | 16%     |
| SanDisk             | 4         | 12     | 8%      |
| WDC                 | 3         | 3      | 6%      |
| Crucial             | 3         | 19     | 6%      |
| Micron Technology   | 2         | 2      | 4%      |
| LITEON              | 2         | 2      | 4%      |
| VICKTER             | 1         | 1      | 2%      |
| Team                | 1         | 2      | 2%      |
| SPCC                | 1         | 1      | 2%      |
| Plextor             | 1         | 1      | 2%      |
| OCZ                 | 1         | 1      | 2%      |
| Netac               | 1         | 2      | 2%      |
| Intenso             | 1         | 1      | 2%      |
| Intel               | 1         | 1      | 2%      |
| HS-SSD-E100         | 1         | 1      | 2%      |
| Hewlett-Packard     | 1         | 1      | 2%      |
| Gigabyte Technology | 1         | 2      | 2%      |
| ETOPSO              | 1         | 1      | 2%      |
| China               | 1         | 1      | 2%      |
| A-DATA Technology   | 1         | 1      | 2%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 43        | 92     | 37.39%  |
| NVMe    | 36        | 46     | 31.3%   |
| HDD     | 33        | 127    | 28.7%   |
| Unknown | 2         | 2      | 1.74%   |
| MMC     | 1         | 1      | 0.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 57        | 211    | 56.44%  |
| NVMe | 36        | 46     | 35.64%  |
| SAS  | 7         | 10     | 6.93%   |
| MMC  | 1         | 1      | 0.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 40        | 58     | 47.62%  |
| 0.51-1.0   | 27        | 65     | 32.14%  |
| 1.01-2.0   | 10        | 19     | 11.9%   |
| 4.01-10.0  | 3         | 43     | 3.57%   |
| 10.01-20.0 | 2         | 32     | 2.38%   |
| 3.01-4.0   | 1         | 1      | 1.19%   |
| 2.01-3.0   | 1         | 1      | 1.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 23        | 26.44%  |
| 251-500        | 15        | 17.24%  |
| 1001-2000      | 14        | 16.09%  |
| 501-1000       | 13        | 14.94%  |
| More than 3000 | 9         | 10.34%  |
| 2001-3000      | 6         | 6.9%    |
| 51-100         | 4         | 4.6%    |
| 21-50          | 1         | 1.15%   |
| 1-20           | 1         | 1.15%   |
| Unknown        | 1         | 1.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 34        | 39.08%  |
| 21-50          | 10        | 11.49%  |
| 101-250        | 10        | 11.49%  |
| 501-1000       | 8         | 9.2%    |
| 51-100         | 8         | 9.2%    |
| 251-500        | 7         | 8.05%   |
| More than 3000 | 5         | 5.75%   |
| 1001-2000      | 3         | 3.45%   |
| 2001-3000      | 1         | 1.15%   |
| Unknown        | 1         | 1.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000LPLX-60ZNTT1 500GB      | 1         | 1      | 11.11%  |
| WDC WD10EZEX-60M2NA0 1TB          | 1         | 1      | 11.11%  |
| Toshiba MQ01ABD100 1TB            | 1         | 1      | 11.11%  |
| Toshiba MK2561GSYN 250GB          | 1         | 1      | 11.11%  |
| Toshiba MK1234GSX 120GB           | 1         | 1      | 11.11%  |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 11.11%  |
| Seagate ST3250820AS 250GB         | 1         | 1      | 11.11%  |
| Seagate ST32000644NS 2TB          | 1         | 1      | 11.11%  |
| Samsung Electronics SSD 840 250GB | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 3         | 3      | 33.33%  |
| Seagate             | 3         | 3      | 33.33%  |
| WDC                 | 2         | 2      | 22.22%  |
| Samsung Electronics | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 37.5%   |
| Seagate | 3         | 3      | 37.5%   |
| WDC     | 2         | 2      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 8      | 87.5%   |
| SSD  | 1         | 1      | 12.5%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 46        | 150    | 46.46%  |
| Detected | 45        | 109    | 45.45%  |
| Malfunc  | 8         | 9      | 8.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 60        | 49.59%  |
| AMD                          | 11        | 9.09%   |
| Samsung Electronics          | 10        | 8.26%   |
| LSI Logic / Symbios Logic    | 7         | 5.79%   |
| SK hynix                     | 5         | 4.13%   |
| SanDisk                      | 3         | 2.48%   |
| Phison Electronics           | 3         | 2.48%   |
| Micron Technology            | 3         | 2.48%   |
| Kingston Technology Company  | 3         | 2.48%   |
| Marvell Technology Group     | 2         | 1.65%   |
| Broadcom / LSI               | 2         | 1.65%   |
| Union Memory (Shenzhen)      | 1         | 0.83%   |
| Toshiba America Info Systems | 1         | 0.83%   |
| Silicon Image                | 1         | 0.83%   |
| Seagate Technology           | 1         | 0.83%   |
| Micron/Crucial Technology    | 1         | 0.83%   |
| KIOXIA                       | 1         | 0.83%   |
| JMicron Technology           | 1         | 0.83%   |
| Huawei Technologies          | 1         | 0.83%   |
| Biwin Storage Technology     | 1         | 0.83%   |
| ASMedia Technology           | 1         | 0.83%   |
| ADATA Technology             | 1         | 0.83%   |
| Adaptec                      | 1         | 0.83%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 5.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 4.41%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 3.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 2.94%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 4         | 2.94%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                        | 4         | 2.94%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 2.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 2.21%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 2.21%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 3         | 2.21%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 3         | 2.21%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 3         | 2.21%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 3         | 2.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 2.21%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 1.47%   |
| SK hynix BC511 NVMe SSD                                                        | 2         | 1.47%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 2         | 1.47%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 1.47%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller          | 2         | 1.47%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                           | 2         | 1.47%   |
| Intel SSD 660P Series                                                          | 2         | 1.47%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 2         | 1.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.47%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.47%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 2         | 1.47%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2         | 1.47%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 1.47%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 1.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2         | 1.47%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2         | 1.47%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                   | 2         | 1.47%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 1.47%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 1         | 0.74%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.74%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.74%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 0.74%   |
| Seagate FireCuda 520/IronWolf 525 SSD                                          | 1         | 0.74%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 1         | 0.74%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 64        | 53.78%  |
| NVMe | 36        | 30.25%  |
| RAID | 15        | 12.61%  |
| IDE  | 2         | 1.68%   |
| SAS  | 1         | 0.84%   |
| SCSI | 1         | 0.84%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| Intel     | 68        | 80.95%  |
| AMD       | 15        | 17.86%  |
| HiSilicon | 1         | 1.19%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 2         | 2.38%   |
| Intel 12th Gen Core i7-1260P            | 2         | 2.38%   |
| Intel 12th Gen Core i5-12600K           | 2         | 2.38%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 2.38%   |
| Intel Xeon Silver 4215R CPU @ 3.20GHz   | 1         | 1.19%   |
| Intel Xeon Silver 4214 CPU @ 2.20GHz    | 1         | 1.19%   |
| Intel Xeon Silver 4210 CPU @ 2.20GHz    | 1         | 1.19%   |
| Intel Xeon Gold 6326 CPU @ 2.90GHz      | 1         | 1.19%   |
| Intel Xeon CPU X3440 @ 2.53GHz          | 1         | 1.19%   |
| Intel Xeon CPU E5-2687W v4 @ 3.00GHz    | 1         | 1.19%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz      | 1         | 1.19%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz     | 1         | 1.19%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz     | 1         | 1.19%   |
| Intel N100                              | 1         | 1.19%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 1.19%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.19%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.19%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 1         | 1.19%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.19%   |
| Intel Core i7-5930K CPU @ 3.50GHz       | 1         | 1.19%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz      | 1         | 1.19%   |
| Intel Core i7-4770K CPU @ 3.50GHz       | 1         | 1.19%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 1         | 1.19%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 1         | 1.19%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 1         | 1.19%   |
| Intel Core i7-2600K CPU @ 3.40GHz       | 1         | 1.19%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.19%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 1         | 1.19%   |
| Intel Core i7 CPU Q 820 @ 1.73GHz       | 1         | 1.19%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 1         | 1.19%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 1         | 1.19%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 1.19%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 1         | 1.19%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 1         | 1.19%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 1         | 1.19%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 1         | 1.19%   |
| Intel Core i5-4200M CPU @ 2.50GHz       | 1         | 1.19%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 1         | 1.19%   |
| Intel Core i5-3380M CPU @ 2.90GHz       | 1         | 1.19%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.19%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 19        | 22.62%  |
| Other                  | 18        | 21.43%  |
| Intel Core i7          | 15        | 17.86%  |
| Intel Xeon             | 5         | 5.95%   |
| Intel Core i3          | 5         | 5.95%   |
| AMD Ryzen 7            | 4         | 4.76%   |
| AMD Ryzen 5            | 4         | 4.76%   |
| Intel Xeon Silver      | 3         | 3.57%   |
| AMD Ryzen 9            | 3         | 3.57%   |
| Intel Celeron          | 2         | 2.38%   |
| Intel Xeon Gold        | 1         | 1.19%   |
| Intel Atom             | 1         | 1.19%   |
| AMD Ryzen Threadripper | 1         | 1.19%   |
| AMD Ryzen 3 PRO        | 1         | 1.19%   |
| AMD FX                 | 1         | 1.19%   |
| AMD A10                | 1         | 1.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 32        | 38.1%   |
| 2      | 15        | 17.86%  |
| 6      | 9         | 10.71%  |
| 12     | 6         | 7.14%   |
| 8      | 6         | 7.14%   |
| 16     | 5         | 5.95%   |
| 24     | 4         | 4.76%   |
| 10     | 3         | 3.57%   |
| 14     | 2         | 2.38%   |
| 32     | 1         | 1.19%   |
| 1      | 1         | 1.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 80        | 95.24%  |
| 2      | 4         | 4.76%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 68        | 80.95%  |
| 1      | 16        | 19.05%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 83        | 98.81%  |
| 64-bit         | 1         | 1.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 52.38%  |
| 0x906a3    | 5         | 5.95%   |
| 0x306c3    | 4         | 4.76%   |
| 0x306a9    | 4         | 4.76%   |
| 0x40651    | 3         | 3.57%   |
| 0x08600106 | 3         | 3.57%   |
| 0x806ec    | 2         | 2.38%   |
| 0x406e3    | 2         | 2.38%   |
| 0xa0671    | 1         | 1.19%   |
| 0xa0653    | 1         | 1.19%   |
| 0xa0652    | 1         | 1.19%   |
| 0x90672    | 1         | 1.19%   |
| 0x806ea    | 1         | 1.19%   |
| 0x706e5    | 1         | 1.19%   |
| 0x706a8    | 1         | 1.19%   |
| 0x606a6    | 1         | 1.19%   |
| 0x306f2    | 1         | 1.19%   |
| 0x206a7    | 1         | 1.19%   |
| 0x20652    | 1         | 1.19%   |
| 0x0a50000c | 1         | 1.19%   |
| 0x0a201016 | 1         | 1.19%   |
| 0x08701021 | 1         | 1.19%   |
| 0x08701013 | 1         | 1.19%   |
| 0x06001119 | 1         | 1.19%   |
| 0x0600063d | 1         | 1.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 12        | 14.12%  |
| Haswell          | 12        | 14.12%  |
| Alderlake Hybrid | 10        | 11.76%  |
| Zen 2            | 7         | 8.24%   |
| Skylake          | 6         | 7.06%   |
| IvyBridge        | 5         | 5.88%   |
| TigerLake        | 4         | 4.71%   |
| SandyBridge      | 4         | 4.71%   |
| Icelake          | 4         | 4.71%   |
| Unknown          | 4         | 4.71%   |
| Zen 3            | 3         | 3.53%   |
| Nehalem          | 2         | 2.35%   |
| CometLake        | 2         | 2.35%   |
| Broadwell        | 2         | 2.35%   |
| Zen+             | 1         | 1.18%   |
| Westmere         | 1         | 1.18%   |
| Tremont          | 1         | 1.18%   |
| Piledriver       | 1         | 1.18%   |
| Gracemont        | 1         | 1.18%   |
| Goldmont plus    | 1         | 1.18%   |
| Bulldozer        | 1         | 1.18%   |
| Bonnell          | 1         | 1.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 47        | 45.19%  |
| Nvidia                     | 31        | 29.81%  |
| AMD                        | 16        | 15.38%  |
| Matrox Electronics Systems | 6         | 5.77%   |
| ASPEED Technology          | 3         | 2.88%   |
| Huawei Technologies        | 1         | 0.96%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 5         | 4.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 3.74%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 4         | 3.74%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 4         | 3.74%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller    | 3         | 2.8%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 3         | 2.8%    |
| Intel UHD Graphics 620                                                      | 3         | 2.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3         | 2.8%    |
| ASPEED Technology ASPEED Graphics Family                                    | 3         | 2.8%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2         | 1.87%   |
| Matrox Electronics Systems G200eR2                                          | 2         | 1.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 1.87%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 2         | 1.87%   |
| Intel HD Graphics 630                                                       | 2         | 1.87%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 1.87%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 1.87%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2         | 1.87%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.93%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 0.93%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1         | 0.93%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 0.93%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1         | 0.93%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1         | 0.93%   |
| Nvidia GT216GLM [Quadro FX 880M]                                            | 1         | 0.93%   |
| Nvidia GP108M [GeForce MX330]                                               | 1         | 0.93%   |
| Nvidia GP108M [GeForce MX250]                                               | 1         | 0.93%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 0.93%   |
| Nvidia GP107M [GeForce MX350]                                               | 1         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.93%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                     | 1         | 0.93%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1         | 0.93%   |
| Nvidia GM108M [GeForce MX110]                                               | 1         | 0.93%   |
| Nvidia GM108M [GeForce 940MX]                                               | 1         | 0.93%   |
| Nvidia GM107M [GeForce GTX 850M]                                            | 1         | 0.93%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                       | 1         | 0.93%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1         | 0.93%   |
| Nvidia GK208M [GeForce GT 740M]                                             | 1         | 0.93%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1         | 0.93%   |
| Nvidia GK208 [GeForce GT 720]                                               | 1         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 29        | 34.52%  |
| 1 x Nvidia              | 15        | 17.86%  |
| Intel + Nvidia          | 14        | 16.67%  |
| 1 x AMD                 | 11        | 13.1%   |
| 1 x Matrox              | 5         | 5.95%   |
| 1 x ASPEED              | 3         | 3.57%   |
| 2 x AMD                 | 2         | 2.38%   |
| Intel + AMD             | 2         | 2.38%   |
| Nvidia + Matrox         | 1         | 1.19%   |
| 1 x Huawei Technologies | 1         | 1.19%   |
| AMD + Nvidia            | 1         | 1.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 69        | 81.18%  |
| Proprietary | 12        | 14.12%  |
| Unknown     | 4         | 4.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 52.27%  |
| 1.01-2.0   | 11        | 12.5%   |
| 3.01-4.0   | 8         | 9.09%   |
| 0.51-1.0   | 6         | 6.82%   |
| 0.01-0.5   | 6         | 6.82%   |
| 5.01-6.0   | 5         | 5.68%   |
| 8.01-16.0  | 5         | 5.68%   |
| 7.01-8.0   | 1         | 1.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 12        | 13.95%  |
| Samsung Electronics     | 9         | 10.47%  |
| LG Display              | 9         | 10.47%  |
| Dell                    | 8         | 9.3%    |
| Goldstar                | 5         | 5.81%   |
| Chimei Innolux          | 5         | 5.81%   |
| BOE                     | 4         | 4.65%   |
| ViewSonic               | 3         | 3.49%   |
| Unknown (XXX)           | 2         | 2.33%   |
| Iiyama                  | 2         | 2.33%   |
| Hewlett-Packard         | 2         | 2.33%   |
| BenQ                    | 2         | 2.33%   |
| AOC                     | 2         | 2.33%   |
| Acer                    | 2         | 2.33%   |
| TMX                     | 1         | 1.16%   |
| SKY                     | 1         | 1.16%   |
| Sharp                   | 1         | 1.16%   |
| PANDA                   | 1         | 1.16%   |
| NXG                     | 1         | 1.16%   |
| MStar                   | 1         | 1.16%   |
| LG Electronics          | 1         | 1.16%   |
| Lenovo                  | 1         | 1.16%   |
| KVM                     | 1         | 1.16%   |
| InfoVision              | 1         | 1.16%   |
| HKC                     | 1         | 1.16%   |
| Gigabyte Technology     | 1         | 1.16%   |
| Eizo                    | 1         | 1.16%   |
| Denver                  | 1         | 1.16%   |
| CSO                     | 1         | 1.16%   |
| Chi Mei Optoelectronics | 1         | 1.16%   |
| CHD                     | 1         | 1.16%   |
| ASUSTek Computer        | 1         | 1.16%   |
| Unknown                 | 1         | 1.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Iiyama PL2888H IVM7106 1920x1080 621x341mm 27.9-inch                    | 2         | 2.2%    |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                   | 2         | 2.2%    |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch           | 1         | 1.1%    |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch           | 1         | 1.1%    |
| ViewSonic PJ402D-2 HCD7B1D 1280x960                                     | 1         | 1.1%    |
| Unknown (XXX) FURRION TV XXX3553 1920x1080 520x290mm 23.4-inch          | 1         | 1.1%    |
| Unknown (XXX) Beyond TV XXX9221 1920x1080 1209x680mm 54.6-inch          | 1         | 1.1%    |
| TMX TL156VDXP01 TMX1560 1920x1080 344x194mm 15.5-inch                   | 1         | 1.1%    |
| SKY 22X1-M225F SKY2150 1920x1080 476x268mm 21.5-inch                    | 1         | 1.1%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                 | 1         | 1.1%    |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch       | 1         | 1.1%    |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch    | 1         | 1.1%    |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch    | 1         | 1.1%    |
| Samsung Electronics SMT23A350 SAM07A7 1920x1080 510x287mm 23.0-inch     | 1         | 1.1%    |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 477x268mm 21.5-inch      | 1         | 1.1%    |
| Samsung Electronics S27C450 SAM09D9 1920x1080 598x336mm 27.0-inch       | 1         | 1.1%    |
| Samsung Electronics S22E310 SAM0C2C 1920x1080 480x270mm 21.7-inch       | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch   | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SAM7048 1366x768 522x293mm 23.6-inch    | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1         | 1.1%    |
| PANDA LCD Monitor NCP0052 1920x1080 309x174mm 14.0-inch                 | 1         | 1.1%    |
| NXG MIRAI DML-517 NXG138B 1280x1024 338x270mm 17.0-inch                 | 1         | 1.1%    |
| MStar LCD Monitor Demo 1920x1080                                        | 1         | 1.1%    |
| LG Electronics LCD Monitor LG FULL HD                                   | 1         | 1.1%    |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch            | 1         | 1.1%    |
| LG Display LCD Monitor LGD068A 1920x1080 309x174mm 14.0-inch            | 1         | 1.1%    |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch            | 1         | 1.1%    |
| LG Display LCD Monitor LGD05E4 1920x1080 344x194mm 15.5-inch            | 1         | 1.1%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch            | 1         | 1.1%    |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch            | 1         | 1.1%    |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch             | 1         | 1.1%    |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch             | 1         | 1.1%    |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch             | 1         | 1.1%    |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                | 1         | 1.1%    |
| KVM LCD Monitor1717 KVM4308 1280x1024 338x270mm 17.0-inch               | 1         | 1.1%    |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch            | 1         | 1.1%    |
| HKC 24N1A HKC2413 1920x1080 527x296mm 23.8-inch                         | 1         | 1.1%    |
| Hewlett-Packard L185x HWP298C 1366x768 410x230mm 18.5-inch              | 1         | 1.1%    |
| Hewlett-Packard 2159 HWP282C 1920x1080 479x269mm 21.6-inch              | 1         | 1.1%    |
| Goldstar ULTRAGEAR GSM5B70 1920x1080 531x298mm 24.0-inch                | 1         | 1.1%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 45        | 54.88%  |
| 1366x768 (WXGA)    | 9         | 10.98%  |
| 3840x2160 (4K)     | 7         | 8.54%   |
| 2560x1440 (QHD)    | 4         | 4.88%   |
| 1920x1200 (WUXGA)  | 4         | 4.88%   |
| 3440x1440          | 2         | 2.44%   |
| 1600x900 (HD+)     | 2         | 2.44%   |
| 1280x1024 (SXGA)   | 2         | 2.44%   |
| Unknown            | 2         | 2.44%   |
| 5760x1080          | 1         | 1.22%   |
| 3840x1080          | 1         | 1.22%   |
| 3200x2000          | 1         | 1.22%   |
| 1680x1050 (WSXGA+) | 1         | 1.22%   |
| 1280x960           | 1         | 1.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 16        | 18.18%  |
| 14      | 16        | 18.18%  |
| 27      | 10        | 11.36%  |
| 21      | 10        | 11.36%  |
| 23      | 8         | 9.09%   |
| 24      | 5         | 5.68%   |
| Unknown | 4         | 4.55%   |
| 17      | 3         | 3.41%   |
| 13      | 3         | 3.41%   |
| 32      | 2         | 2.27%   |
| 84      | 1         | 1.14%   |
| 54      | 1         | 1.14%   |
| 38      | 1         | 1.14%   |
| 35      | 1         | 1.14%   |
| 34      | 1         | 1.14%   |
| 31      | 1         | 1.14%   |
| 25      | 1         | 1.14%   |
| 22      | 1         | 1.14%   |
| 19      | 1         | 1.14%   |
| 18      | 1         | 1.14%   |
| 16      | 1         | 1.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 35        | 41.18%  |
| 501-600     | 17        | 20%     |
| 401-500     | 12        | 14.12%  |
| 601-700     | 5         | 5.88%   |
| 351-400     | 4         | 4.71%   |
| Unknown     | 4         | 4.71%   |
| 701-800     | 3         | 3.53%   |
| 801-900     | 2         | 2.35%   |
| 201-300     | 1         | 1.18%   |
| 1501-2000   | 1         | 1.18%   |
| 1001-1500   | 1         | 1.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 61        | 82.43%  |
| 16/10   | 5         | 6.76%   |
| Unknown | 3         | 4.05%   |
| 5/4     | 2         | 2.7%    |
| 21/9    | 2         | 2.7%    |
| 4/3     | 1         | 1.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 19        | 22.09%  |
| 81-90          | 18        | 20.93%  |
| 101-110        | 16        | 18.6%   |
| 301-350        | 10        | 11.63%  |
| 351-500        | 5         | 5.81%   |
| Unknown        | 4         | 4.65%   |
| 251-300        | 3         | 3.49%   |
| More than 1000 | 2         | 2.33%   |
| 151-200        | 2         | 2.33%   |
| 141-150        | 2         | 2.33%   |
| 121-130        | 2         | 2.33%   |
| 71-80          | 1         | 1.16%   |
| 111-120        | 1         | 1.16%   |
| 501-1000       | 1         | 1.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 28        | 32.94%  |
| 51-100        | 24        | 28.24%  |
| 101-120       | 21        | 24.71%  |
| 161-240       | 5         | 5.88%   |
| Unknown       | 4         | 4.71%   |
| More than 240 | 2         | 2.35%   |
| 1-50          | 1         | 1.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 59        | 68.6%   |
| 2     | 15        | 17.44%  |
| 0     | 10        | 11.63%  |
| 4     | 1         | 1.16%   |
| 3     | 1         | 1.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 54        | 40.6%   |
| Realtek Semiconductor             | 37        | 27.82%  |
| Qualcomm Atheros                  | 13        | 9.77%   |
| Broadcom                          | 7         | 5.26%   |
| Ralink Technology                 | 3         | 2.26%   |
| TP-Link                           | 2         | 1.5%    |
| Dell                              | 2         | 1.5%    |
| ASUSTek Computer                  | 2         | 1.5%    |
| ASIX Electronics                  | 2         | 1.5%    |
| Aquantia                          | 2         | 1.5%    |
| Xiaomi                            | 1         | 0.75%   |
| U-Blox                            | 1         | 0.75%   |
| Mellanox Technologies             | 1         | 0.75%   |
| MediaTek                          | 1         | 0.75%   |
| IBM                               | 1         | 0.75%   |
| Huawei Technologies               | 1         | 0.75%   |
| Ericsson Business Mobile Networks | 1         | 0.75%   |
| DisplayLink                       | 1         | 0.75%   |
| Ceton Technologies                | 1         | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 26        | 15.95%  |
| Intel Ethernet Controller I225-V                                       | 6         | 3.68%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 6         | 3.68%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5         | 3.07%   |
| Intel Wireless 7260                                                    | 4         | 2.45%   |
| Intel Wi-Fi 6 AX200                                                    | 4         | 2.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 1.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 3         | 1.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 1.84%   |
| Intel Wireless 8265 / 8275                                             | 3         | 1.84%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 1.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 1.84%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 3         | 1.84%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller  | 3         | 1.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 2         | 1.23%   |
| Ralink RT5370 Wireless Adapter                                         | 2         | 1.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2         | 1.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2         | 1.23%   |
| Intel Wireless 8260                                                    | 2         | 1.23%   |
| Intel Wireless 7265                                                    | 2         | 1.23%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 2         | 1.23%   |
| Intel I210 Gigabit Network Connection                                  | 2         | 1.23%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                          | 2         | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 1.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 2         | 1.23%   |
| Intel 82574L Gigabit Network Connection                                | 2         | 1.23%   |
| Dell iDRAC Virtual NIC                                                 | 2         | 1.23%   |
| ASUS 802.11ac NIC                                                      | 2         | 1.23%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 1.23%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.61%   |
| U-Blox [u-blox 8]                                                      | 1         | 0.61%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 1         | 0.61%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1         | 0.61%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1         | 0.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1         | 0.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.61%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.61%   |
| Ralink RT2501/RT2573 Wireless Adapter                                  | 1         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 39        | 59.09%  |
| Qualcomm Atheros      | 12        | 18.18%  |
| Realtek Semiconductor | 6         | 9.09%   |
| Ralink Technology     | 3         | 4.55%   |
| TP-Link               | 2         | 3.03%   |
| ASUSTek Computer      | 2         | 3.03%   |
| MediaTek              | 1         | 1.52%   |
| Broadcom              | 1         | 1.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                               | 6         | 9.09%   |
| Intel Wireless 7260                                            | 4         | 6.06%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 6.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 4.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 4.55%   |
| Intel Wireless 8265 / 8275                                     | 3         | 4.55%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 4.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 3.03%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 3.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 3.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 3.03%   |
| Intel Wireless 8260                                            | 2         | 3.03%   |
| Intel Wireless 7265                                            | 2         | 3.03%   |
| Intel Raptor Lake-S PCH CNVi WiFi                              | 2         | 3.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 3.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 3.03%   |
| ASUS 802.11ac NIC                                              | 2         | 3.03%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1         | 1.52%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 1.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.52%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 1         | 1.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.52%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 1.52%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 1         | 1.52%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.52%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 1.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.52%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.52%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 1.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 35        | 40.7%   |
| Intel                 | 31        | 36.05%  |
| Broadcom              | 6         | 6.98%   |
| Qualcomm Atheros      | 2         | 2.33%   |
| Dell                  | 2         | 2.33%   |
| ASIX Electronics      | 2         | 2.33%   |
| Aquantia              | 2         | 2.33%   |
| Xiaomi                | 1         | 1.16%   |
| Mellanox Technologies | 1         | 1.16%   |
| IBM                   | 1         | 1.16%   |
| Huawei Technologies   | 1         | 1.16%   |
| DisplayLink           | 1         | 1.16%   |
| Ceton Technologies    | 1         | 1.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 26        | 27.37%  |
| Intel Ethernet Controller I225-V                                       | 6         | 6.32%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5         | 5.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 3.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 3.16%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 3         | 3.16%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller  | 3         | 3.16%   |
| Intel I210 Gigabit Network Connection                                  | 2         | 2.11%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                          | 2         | 2.11%   |
| Intel 82574L Gigabit Network Connection                                | 2         | 2.11%   |
| Dell iDRAC Virtual NIC                                                 | 2         | 2.11%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 2.11%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 1.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 1.05%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 1.05%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.05%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 1.05%   |
| Mellanox MT27800 Family [ConnectX-5]                                   | 1         | 1.05%   |
| Intel I350 Gigabit Network Connection                                  | 1         | 1.05%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.05%   |
| Intel Ethernet Controller XL710 for 40GbE QSFP+                        | 1         | 1.05%   |
| Intel Ethernet Controller X710 for 10GBASE-T                           | 1         | 1.05%   |
| Intel Ethernet Controller X550                                         | 1         | 1.05%   |
| Intel Ethernet Controller I226-V                                       | 1         | 1.05%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.05%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.05%   |
| Intel Ethernet Connection I218-V                                       | 1         | 1.05%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.05%   |
| Intel Ethernet Connection I217-V                                       | 1         | 1.05%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 1.05%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 1.05%   |
| Intel Ethernet Connection (5) I219-V                                   | 1         | 1.05%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.05%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.05%   |
| Intel Ethernet Connection (2) I218-V                                   | 1         | 1.05%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 1.05%   |
| Intel 82599 10 Gigabit TN Network Connection                           | 1         | 1.05%   |
| Intel 82579V Gigabit Network Connection                                | 1         | 1.05%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.05%   |
| IBM RNDIS/CDC ETHER                                                    | 1         | 1.05%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 73        | 53.68%  |
| WiFi     | 61        | 44.85%  |
| Modem    | 2         | 1.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 43        | 53.09%  |
| WiFi     | 38        | 46.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 47        | 55.95%  |
| 1     | 26        | 30.95%  |
| 4     | 4         | 4.76%   |
| 3     | 4         | 4.76%   |
| 6     | 2         | 2.38%   |
| 7     | 1         | 1.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 62        | 73.81%  |
| Yes  | 22        | 26.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 61.4%   |
| Qualcomm Atheros Communications | 6         | 10.53%  |
| Realtek Semiconductor           | 3         | 5.26%   |
| Lite-On Technology              | 3         | 5.26%   |
| Broadcom                        | 3         | 5.26%   |
| IMC Networks                    | 2         | 3.51%   |
| MediaTek                        | 1         | 1.75%   |
| Integrated System Solution      | 1         | 1.75%   |
| Foxconn / Hon Hai               | 1         | 1.75%   |
| Cambridge Silicon Radio         | 1         | 1.75%   |
| ASUSTek Computer                | 1         | 1.75%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 12        | 21.05%  |
| Intel AX211 Bluetooth                               | 7         | 12.28%  |
| Intel AX201 Bluetooth                               | 6         | 10.53%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 7.02%   |
| Intel AX200 Bluetooth                               | 4         | 7.02%   |
| Realtek Bluetooth Radio                             | 3         | 5.26%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 5.26%   |
| Lite-On Bluetooth Device                            | 2         | 3.51%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 3.51%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.75%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.75%   |
| MediaTek Wireless_Device                            | 1         | 1.75%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.75%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.75%   |
| Integrated System Solution Bluetooth Device         | 1         | 1.75%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.75%   |
| IMC Networks Bluetooth Device                       | 1         | 1.75%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.75%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.75%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.75%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 58        | 53.21%  |
| Nvidia                   | 21        | 19.27%  |
| AMD                      | 20        | 18.35%  |
| SteelSeries ApS          | 3         | 2.75%   |
| Walmart                  | 1         | 0.92%   |
| Micro Star International | 1         | 0.92%   |
| KTMicro                  | 1         | 0.92%   |
| JBL                      | 1         | 0.92%   |
| Giga-Byte Technology     | 1         | 0.92%   |
| Generalplus Technology   | 1         | 0.92%   |
| DSEA A/S                 | 1         | 0.92%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 5.56%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 7         | 5.56%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 4.76%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 4.76%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 3.97%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 3.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 3.17%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 3.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 3.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 3.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.38%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 2.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 2.38%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 2.38%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.59%   |
| Nvidia TU102 High Definition Audio Controller                              | 2         | 1.59%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.59%   |
| Intel Raptor Lake High Definition Audio Controller                         | 2         | 1.59%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.59%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.59%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 1.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.59%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 1.59%   |
| Walmart AB13X Headset Adapter                                              | 1         | 0.79%   |
| SteelSeries ApS SteelSeries Siberia 800                                    | 1         | 0.79%   |
| SteelSeries ApS SteelSeries GameDAC                                        | 1         | 0.79%   |
| SteelSeries ApS Arctis Nova Pro Wireless                                   | 1         | 0.79%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.79%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.79%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.79%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.79%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.79%   |
| Nvidia GM200 High Definition Audio                                         | 1         | 0.79%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.79%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.79%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.79%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.79%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.79%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.79%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 35.71%  |
| SK hynix            | 12        | 21.43%  |
| Kingston            | 4         | 7.14%   |
| Crucial             | 4         | 7.14%   |
| Corsair             | 4         | 7.14%   |
| G.Skill             | 3         | 5.36%   |
| Unknown             | 2         | 3.57%   |
| Unknown (ABCD)      | 1         | 1.79%   |
| Team                | 1         | 1.79%   |
| Smart Brazil        | 1         | 1.79%   |
| SHARETRONIC         | 1         | 1.79%   |
| Ramaxel Technology  | 1         | 1.79%   |
| A-DATA Technology   | 1         | 1.79%   |
| 019400B300CE        | 1         | 1.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA84GR7AFR4N-UH 32GB DIMM DDR4 2400MT/s        | 2         | 3.45%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 3.45%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 2         | 3.45%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                   | 1         | 1.72%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s         | 1         | 1.72%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM DDR3 2400MT/s | 1         | 1.72%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s           | 1         | 1.72%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s | 1         | 1.72%   |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s                   | 1         | 1.72%   |
| SK hynix RAM Module 2GB Row Of Chips LPDDR4 4267MT/s         | 1         | 1.72%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 1         | 1.72%   |
| SK hynix RAM HMT31GR7BFR4A-H9 8192MB DIMM DDR3 1333MT/s      | 1         | 1.72%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s       | 1         | 1.72%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s      | 1         | 1.72%   |
| SK hynix RAM HMA84GR7DJR4N-XN 32GB DIMM DDR4 3200MT/s        | 1         | 1.72%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 1.72%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 1         | 1.72%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 1         | 1.72%   |
| SHARETRONIC RAM Module 4GB SODIMM DDR3 800MT/s               | 1         | 1.72%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 1.72%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR5 4000MT/s          | 1         | 1.72%   |
| Samsung RAM M474A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s       | 1         | 1.72%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s        | 1         | 1.72%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.72%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.72%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.72%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s        | 1         | 1.72%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 1         | 1.72%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.72%   |
| Samsung RAM M393B1K70DH0-YH9 8GB DIMM DDR3 1333MT/s          | 1         | 1.72%   |
| Samsung RAM M393A4K40EB3-CWE 32GB DIMM DDR4 3200MT/s         | 1         | 1.72%   |
| Samsung RAM M393A4K40CB2-CTD 32GB DIMM DDR4 2667MT/s         | 1         | 1.72%   |
| Samsung RAM M393A4K40BB2-CTD 32GB DIMM DDR4 2667MT/s         | 1         | 1.72%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s         | 1         | 1.72%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s          | 1         | 1.72%   |
| Samsung RAM K4UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s | 1         | 1.72%   |
| Samsung RAM K3LKBKB0BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 1.72%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8GB DIMM DDR4 2400MT/s       | 1         | 1.72%   |
| Kingston RAM KF556R36-32 32GB DIMM DDR5 4800MT/s             | 1         | 1.72%   |
| Kingston RAM 99U5700-027.A00G 8GB SODIMM DDR4 2667MT/s       | 1         | 1.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 28        | 56%     |
| DDR3   | 14        | 28%     |
| LPDDR4 | 3         | 6%      |
| LPDDR5 | 2         | 4%      |
| DDR5   | 2         | 4%      |
| DRAM   | 1         | 2%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 22        | 44.9%   |
| DIMM         | 21        | 42.86%  |
| Row Of Chips | 6         | 12.24%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 22        | 41.51%  |
| 32768 | 12        | 22.64%  |
| 16384 | 8         | 15.09%  |
| 4096  | 7         | 13.21%  |
| 2048  | 4         | 7.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 9         | 16.98%  |
| 2667  | 8         | 15.09%  |
| 2400  | 8         | 15.09%  |
| 1600  | 7         | 13.21%  |
| 2133  | 3         | 5.66%   |
| 4267  | 2         | 3.77%   |
| 4000  | 2         | 3.77%   |
| 1800  | 2         | 3.77%   |
| 1334  | 2         | 3.77%   |
| 800   | 2         | 3.77%   |
| 6400  | 1         | 1.89%   |
| 5600  | 1         | 1.89%   |
| 4800  | 1         | 1.89%   |
| 3600  | 1         | 1.89%   |
| 2933  | 1         | 1.89%   |
| 2666  | 1         | 1.89%   |
| 1333  | 1         | 1.89%   |
| 1067  | 1         | 1.89%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 8         | 18.18%  |
| IMC Networks                           | 5         | 11.36%  |
| Realtek Semiconductor                  | 4         | 9.09%   |
| Syntek                                 | 3         | 6.82%   |
| Sunplus Innovation Technology          | 3         | 6.82%   |
| Microdia                               | 3         | 6.82%   |
| Logitech                               | 3         | 6.82%   |
| Bison Electronics                      | 3         | 6.82%   |
| Luxvisions Innotech Limited            | 2         | 4.55%   |
| Lite-On Technology                     | 2         | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.55%   |
| Acer                                   | 2         | 4.55%   |
| Silicon Motion                         | 1         | 2.27%   |
| Lenovo                                 | 1         | 2.27%   |
| KYE Systems                            | 1         | 2.27%   |
| Apple                                  | 1         | 2.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                            | 3         | 6.67%   |
| Sunplus Full HD webcam                              | 2         | 4.44%   |
| Realtek Integrated_Webcam_HD                        | 2         | 4.44%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 4.44%   |
| Logitech C922 Pro Stream Webcam                     | 2         | 4.44%   |
| IMC Networks Integrated Camera                      | 2         | 4.44%   |
| Chicony Integrated Camera                           | 2         | 4.44%   |
| Acer Integrated Camera                              | 2         | 4.44%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 2.22%   |
| Silicon Motion WebCam SC-13HDL11939N                | 1         | 2.22%   |
| Realtek Lenovo EasyCamera                           | 1         | 2.22%   |
| Realtek Integrated Webcam                           | 1         | 2.22%   |
| Microdia USB Live camera                            | 1         | 2.22%   |
| Microdia USB 2.0 Camera                             | 1         | 2.22%   |
| Microdia Integrated_Webcam_HD                       | 1         | 2.22%   |
| Logitech Webcam C270                                | 1         | 2.22%   |
| Lite-On Integrated Camera                           | 1         | 2.22%   |
| Lite-On HP Wide Vision FHD Camera                   | 1         | 2.22%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 2.22%   |
| KYE Systems FaceCam 1320                            | 1         | 2.22%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 2.22%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 2.22%   |
| IMC Networks Integrated RGB Camera                  | 1         | 2.22%   |
| Chicony USB2.0 2M WebCam                            | 1         | 2.22%   |
| Chicony USB 5M WebCam                               | 1         | 2.22%   |
| Chicony Thinkpad T430 camera                        | 1         | 2.22%   |
| Chicony HP HD Camera                                | 1         | 2.22%   |
| Chicony HD WebCam (Asus N-series)                   | 1         | 2.22%   |
| Chicony HD WebCam                                   | 1         | 2.22%   |
| Chicony Acer CrystalEye Webcam                      | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 2.22%   |
| Bison Lenovo Integrated Webcam                      | 1         | 2.22%   |
| Bison Integrated Camera                             | 1         | 2.22%   |
| Bison HD Webcam                                     | 1         | 2.22%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 1         | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 3         | 37.5%   |
| Synaptics             | 3         | 37.5%   |
| Upek                  | 1         | 12.5%   |
| LighTuning Technology | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 1         | 12.5%   |
| Validity Sensors VFS495 Fingerprint Reader                | 1         | 12.5%   |
| Validity Sensors Synaptics WBDI                           | 1         | 12.5%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 1         | 12.5%   |
| Synaptics WBDI Fingerprint Reader USB 102                 | 1         | 12.5%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 12.5%   |
| Synaptics Prometheus Fingerprint Reader                   | 1         | 12.5%   |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Upek   | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 53        | 60.92%  |
| 1     | 20        | 22.99%  |
| 2     | 8         | 9.2%    |
| 3     | 4         | 4.6%    |
| 5     | 1         | 1.15%   |
| 4     | 1         | 1.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 9         | 18.37%  |
| Unassigned class         | 8         | 16.33%  |
| Fingerprint reader       | 8         | 16.33%  |
| Net/wireless             | 7         | 14.29%  |
| Graphics card            | 6         | 12.24%  |
| Multimedia controller    | 3         | 6.12%   |
| Bluetooth                | 2         | 4.08%   |
| Storage/ata              | 1         | 2.04%   |
| Storage                  | 1         | 2.04%   |
| Sound                    | 1         | 2.04%   |
| Firewire controller      | 1         | 2.04%   |
| Dvb card                 | 1         | 2.04%   |
| Chipcard                 | 1         | 2.04%   |

