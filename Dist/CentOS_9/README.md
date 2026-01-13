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

Total: 140

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B760-PLUS             | Desktop     | [d05a07fcbc](https://linux-hardware.org/?probe=d05a07fcbc) | Nov 18, 2025 |
| HPE           | ProLiant DL325 Gen10 Plu... | Server      | [6cb419d8cd](https://linux-hardware.org/?probe=6cb419d8cd) | Oct 06, 2025 |
| Supermicro    | X13SEW-F                    | Desktop     | [e11e0a3c3a](https://linux-hardware.org/?probe=e11e0a3c3a) | Jul 18, 2025 |
| Dell          | 02C2CP A00                  | Server      | [4d2b90a7c3](https://linux-hardware.org/?probe=4d2b90a7c3) | Jul 04, 2025 |
| Dell          | 07NDJ2 A01                  | Server      | [e3a944751f](https://linux-hardware.org/?probe=e3a944751f) | Jun 23, 2025 |
| ASUSTek       | PRIME H510M-R               | Desktop     | [7430eb8b5f](https://linux-hardware.org/?probe=7430eb8b5f) | Jun 16, 2025 |
| Lenovo        | ThinkPad T450s 20BWS0FU0... | Notebook    | [e9d9c9770c](https://linux-hardware.org/?probe=e9d9c9770c) | Jun 10, 2025 |
| Dell          | 0CN7X8 A01                  | Server      | [1caf581c69](https://linux-hardware.org/?probe=1caf581c69) | Jun 06, 2025 |
| Dell          | 086D43 A08                  | Server      | [97f1a09e50](https://linux-hardware.org/?probe=97f1a09e50) | May 08, 2025 |
| Intel         | DZ77GA-70K AAG39009-402     | Desktop     | [9fb57777ae](https://linux-hardware.org/?probe=9fb57777ae) | Apr 11, 2025 |
| Intel         | DZ77GA-70K AAG39009-402     | Desktop     | [7820b990f9](https://linux-hardware.org/?probe=7820b990f9) | Apr 11, 2025 |
| Supermicro    | X11DPH-T                    | Server      | [a57898de54](https://linux-hardware.org/?probe=a57898de54) | Mar 07, 2025 |
| Supermicro    | X11DPH-T                    | Server      | [796d568cce](https://linux-hardware.org/?probe=796d568cce) | Mar 06, 2025 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [d8d86946e7](https://linux-hardware.org/?probe=d8d86946e7) | Mar 05, 2025 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [26747b091b](https://linux-hardware.org/?probe=26747b091b) | Feb 21, 2025 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [c1d0483654](https://linux-hardware.org/?probe=c1d0483654) | Feb 11, 2025 |
| Dell          | 0GXJYG A06                  | Server      | [1c5bddfc83](https://linux-hardware.org/?probe=1c5bddfc83) | Feb 11, 2025 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [ce67196c06](https://linux-hardware.org/?probe=ce67196c06) | Jan 26, 2025 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [c48fe7366b](https://linux-hardware.org/?probe=c48fe7366b) | Jan 12, 2025 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [16efaa656c](https://linux-hardware.org/?probe=16efaa656c) | Jan 10, 2025 |
| HP            | 8906 SMVB                   | Desktop     | [1a1d29f62e](https://linux-hardware.org/?probe=1a1d29f62e) | Jan 10, 2025 |
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

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.14.0-511.el9.x86_64       | 4         | 3.48%   |
| 5.14.0-362.el9.x86_64       | 4         | 3.48%   |
| 5.14.0-86.el9.x86_64        | 3         | 2.61%   |
| 5.14.0-522.el9.x86_64       | 3         | 2.61%   |
| 5.14.0-480.el9.x86_64       | 3         | 2.61%   |
| 5.14.0-432.el9.x86_64       | 3         | 2.61%   |
| 5.14.0-391.el9.x86_64       | 3         | 2.61%   |
| 5.14.0-202.el9.x86_64       | 3         | 2.61%   |
| 5.14.0-134.el9.x86_64       | 3         | 2.61%   |
| 5.14.0-590.el9.x86_64       | 2         | 1.74%   |
| 5.14.0-587.el9.x86_64       | 2         | 1.74%   |
| 5.14.0-565.el9.x86_64       | 2         | 1.74%   |
| 5.14.0-542.el9.x86_64       | 2         | 1.74%   |
| 5.14.0-496.el9.x86_64       | 2         | 1.74%   |
| 5.14.0-479.el9.x86_64       | 2         | 1.74%   |
| 5.14.0-427.el9.x86_64       | 2         | 1.74%   |
| 5.14.0-407.el9.x86_64       | 2         | 1.74%   |
| 5.14.0-333.el9.x86_64       | 2         | 1.74%   |
| 5.14.0-325.el9.x86_64       | 2         | 1.74%   |
| 5.14.0-319.el9.x86_64       | 2         | 1.74%   |
| 5.14.0-214.el9.x86_64       | 2         | 1.74%   |
| 5.14.0-183.el9.x86_64       | 2         | 1.74%   |
| 5.14.0-171.el9.x86_64       | 2         | 1.74%   |
| 5.14.0-148.el9.x86_64       | 2         | 1.74%   |
| 6.12.8-1.el9.elrepo.x86_64  | 1         | 0.87%   |
| 6.10.6-1.el9.elrepo.x86_64  | 1         | 0.87%   |
| 6.1.8-1.el9.elrepo.x86_64   | 1         | 0.87%   |
| 6.1.102-1.el9.elrepo.x86_64 | 1         | 0.87%   |
| 6.1.1                       | 1         | 0.87%   |
| 5.17.2-lqx3.0.el9.x86_64    | 1         | 0.87%   |
| 5.14.0-78.el9.x86_64        | 1         | 0.87%   |
| 5.14.0-71.el9.x86_64        | 1         | 0.87%   |
| 5.14.0-66.el9.x86_64        | 1         | 0.87%   |
| 5.14.0-639.el9.x86_64       | 1         | 0.87%   |
| 5.14.0-620.el9.x86_64       | 1         | 0.87%   |
| 5.14.0-596.el9.x86_64       | 1         | 0.87%   |
| 5.14.0-592.el9.x86_64       | 1         | 0.87%   |
| 5.14.0-582.el9.x86_64       | 1         | 0.87%   |
| 5.14.0-570.el9.x86_64       | 1         | 0.87%   |
| 5.14.0-559.el9.x86_64       | 1         | 0.87%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 94        | 93.07%  |
| 6.12.8  | 1         | 0.99%   |
| 6.10.6  | 1         | 0.99%   |
| 6.1.8   | 1         | 0.99%   |
| 6.1.102 | 1         | 0.99%   |
| 6.1.1   | 1         | 0.99%   |
| 5.17.2  | 1         | 0.99%   |
| 4.18.0  | 1         | 0.99%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 94        | 93.07%  |
| 6.1     | 3         | 2.97%   |
| 6.12    | 1         | 0.99%   |
| 6.10    | 1         | 0.99%   |
| 5.17    | 1         | 0.99%   |
| 4.18    | 1         | 0.99%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 99        | 99%     |
| aarch64 | 1         | 1%      |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 80        | 80%     |
| Unknown       | 9         | 9%      |
| KDE5          | 7         | 7%      |
| GNOME Classic | 3         | 3%      |
| MATE          | 1         | 1%      |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 59        | 57.84%  |
| X11     | 28        | 27.45%  |
| Tty     | 10        | 9.8%    |
| Unknown | 3         | 2.94%   |
| Web     | 2         | 1.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 51        | 50%     |
| GDM     | 45        | 44.12%  |
| SDDM    | 4         | 3.92%   |
| LightDM | 2         | 1.96%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 63        | 63%     |
| de_DE   | 6         | 6%      |
| ru_RU   | 5         | 5%      |
| pt_BR   | 5         | 5%      |
| en_IE   | 3         | 3%      |
| zh_CN   | 2         | 2%      |
| ja_JP   | 2         | 2%      |
| it_IT   | 2         | 2%      |
| en_GB   | 2         | 2%      |
| en_AU   | 2         | 2%      |
| sv_SE   | 1         | 1%      |
| ru_UA   | 1         | 1%      |
| ro_RO   | 1         | 1%      |
| fr_FR   | 1         | 1%      |
| fr_CA   | 1         | 1%      |
| en_IN   | 1         | 1%      |
| C       | 1         | 1%      |
| Unknown | 1         | 1%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 77        | 76.24%  |
| BIOS | 24        | 23.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Xfs   | 87        | 87%     |
| Ext4  | 11        | 11%     |
| Tmpfs | 2         | 2%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 51        | 49.51%  |
| Unknown | 40        | 38.83%  |
| MBR     | 12        | 11.65%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 86        | 85.15%  |
| Yes       | 15        | 14.85%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 78        | 75.73%  |
| Yes       | 25        | 24.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Lenovo                           | 18        | 18%     |
| Dell                             | 17        | 17%     |
| ASUSTek Computer                 | 16        | 16%     |
| Hewlett-Packard                  | 8         | 8%      |
| Intel                            | 5         | 5%      |
| Supermicro                       | 4         | 4%      |
| MSI                              | 4         | 4%      |
| Gigabyte Technology              | 4         | 4%      |
| Acer                             | 4         | 4%      |
| Timi                             | 2         | 2%      |
| Seeed Studio                     | 2         | 2%      |
| Samsung Electronics              | 2         | 2%      |
| AZW                              | 2         | 2%      |
| Zvezda                           | 1         | 1%      |
| SHANGZHAOYUAN                    | 1         | 1%      |
| Razer                            | 1         | 1%      |
| Positivo Bahia - VAIO            | 1         | 1%      |
| Notebook                         | 1         | 1%      |
| Micro Computer (HK) Tech Limited | 1         | 1%      |
| IP3 Tech                         | 1         | 1%      |
| IBM                              | 1         | 1%      |
| HUAWEI                           | 1         | 1%      |
| HPE                              | 1         | 1%      |
| Gateway                          | 1         | 1%      |
| Colorful Technology              | 1         | 1%      |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Dell PowerEdge R630                         | 3         | 3%      |
| Supermicro Super Server                     | 2         | 2%      |
| Seeed Studio ODYSSEY-X86J4105               | 2         | 2%      |
| ASUS PRIME H670-PLUS D4                     | 2         | 2%      |
| Zvezda Altair Z                             | 1         | 1%      |
| Timi RedmiBook 16                           | 1         | 1%      |
| Timi Mi NoteBook Horizon Edition 14         | 1         | 1%      |
| Supermicro X10DRi                           | 1         | 1%      |
| Supermicro SYS-511E-WR                      | 1         | 1%      |
| SHANGZHAOYUAN B85M-PRO V1.1                 | 1         | 1%      |
| Samsung 530U3C/530U4C/532U3C                | 1         | 1%      |
| Samsung 355V4C/356V4C/3445VC/3545VC         | 1         | 1%      |
| Razer Blade 15 (2022) - RZ09-0421           | 1         | 1%      |
| Positivo Bahia - VAIO VJFE41F11X-XXXXXX     | 1         | 1%      |
| Notebook P377SM-A                           | 1         | 1%      |
| MSI MS-7E01                                 | 1         | 1%      |
| MSI MS-7D86                                 | 1         | 1%      |
| MSI MS-7B79                                 | 1         | 1%      |
| MSI Katana GF76 12UE                        | 1         | 1%      |
| Micro (HK) Tech Limited Venus series        | 1         | 1%      |
| Lenovo Yoga S740-14IIL 81RS                 | 1         | 1%      |
| Lenovo V15 G2 ITL 82KB                      | 1         | 1%      |
| Lenovo ThinkPad X390 20Q00039CD             | 1         | 1%      |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBCTO1WW | 1         | 1%      |
| Lenovo ThinkPad W510 431967G                | 1         | 1%      |
| Lenovo ThinkPad T470p 20J7002GPH            | 1         | 1%      |
| Lenovo ThinkPad T460s 20FAS5WX00            | 1         | 1%      |
| Lenovo ThinkPad T450s 20BWS0FU02            | 1         | 1%      |
| Lenovo ThinkPad T430 2349DG5                | 1         | 1%      |
| Lenovo ThinkPad T430 2347DE9                | 1         | 1%      |
| Lenovo ThinkPad T15 Gen 1 20S7S43600        | 1         | 1%      |
| Lenovo ThinkPad L14 Gen 1 20U5S0NT00        | 1         | 1%      |
| Lenovo ThinkCentre M900 10FGS0301H          | 1         | 1%      |
| Lenovo Legion 5P 15IMH05H 82AW              | 1         | 1%      |
| Lenovo IdeaPad S145-15IWL 81S9              | 1         | 1%      |
| Lenovo IdeaPad 5 14ITL05 82FE               | 1         | 1%      |
| Lenovo G580 20150                           | 1         | 1%      |
| Lenovo G410 20237                           | 1         | 1%      |
| IP3 Tech HeroBox                            | 1         | 1%      |
| Intel NUC7i3BNK                             | 1         | 1%      |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo ThinkPad                         | 10        | 10%     |
| Dell PowerEdge                          | 10        | 10%     |
| ASUS PRIME                              | 5         | 5%      |
| HP EliteBook                            | 3         | 3%      |
| ASUS ROG                                | 3         | 3%      |
| Supermicro Super                        | 2         | 2%      |
| Seeed Studio ODYSSEY-X86J4105           | 2         | 2%      |
| Lenovo IdeaPad                          | 2         | 2%      |
| HP Pavilion                             | 2         | 2%      |
| Dell Precision                          | 2         | 2%      |
| Acer Aspire                             | 2         | 2%      |
| Zvezda Altair                           | 1         | 1%      |
| Timi RedmiBook                          | 1         | 1%      |
| Timi Mi                                 | 1         | 1%      |
| Supermicro X10DRi                       | 1         | 1%      |
| Supermicro SYS-511E-WR                  | 1         | 1%      |
| SHANGZHAOYUAN B85M-PRO                  | 1         | 1%      |
| Samsung 530U3C                          | 1         | 1%      |
| Samsung 355V4C                          | 1         | 1%      |
| Razer Blade                             | 1         | 1%      |
| Positivo Bahia - VAIO VJFE41F11X-XXXXXX | 1         | 1%      |
| Notebook P377SM-A                       | 1         | 1%      |
| MSI MS-7E01                             | 1         | 1%      |
| MSI MS-7D86                             | 1         | 1%      |
| MSI MS-7B79                             | 1         | 1%      |
| MSI Katana                              | 1         | 1%      |
| Micro (HK) Tech Limited Venus           | 1         | 1%      |
| Lenovo Yoga                             | 1         | 1%      |
| Lenovo V15                              | 1         | 1%      |
| Lenovo ThinkCentre                      | 1         | 1%      |
| Lenovo Legion                           | 1         | 1%      |
| Lenovo G580                             | 1         | 1%      |
| Lenovo G410                             | 1         | 1%      |
| IP3 Tech HeroBox                        | 1         | 1%      |
| Intel NUC7i3BNK                         | 1         | 1%      |
| Intel NUC12WSHi7                        | 1         | 1%      |
| Intel NUC12WSHi5                        | 1         | 1%      |
| Intel DZ77GA-70K                        | 1         | 1%      |
| Intel D34010WYK                         | 1         | 1%      |
| IBM System                              | 1         | 1%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 17        | 17%     |
| 2013 | 13        | 13%     |
| 2021 | 12        | 12%     |
| 2022 | 11        | 11%     |
| 2019 | 8         | 8%      |
| 2023 | 6         | 6%      |
| 2018 | 6         | 6%      |
| 2017 | 5         | 5%      |
| 2014 | 5         | 5%      |
| 2012 | 5         | 5%      |
| 2011 | 3         | 3%      |
| 2016 | 2         | 2%      |
| 2015 | 2         | 2%      |
| 2010 | 2         | 2%      |
| 2025 | 1         | 1%      |
| 2024 | 1         | 1%      |
| 2009 | 1         | 1%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 42        | 42%     |
| Desktop     | 34        | 34%     |
| Server      | 17        | 17%     |
| Mini pc     | 5         | 5%      |
| Convertible | 2         | 2%      |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 94        | 94%     |
| Enabled  | 6         | 6%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 100       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 32        | 32%     |
| 64.01-256.0     | 20        | 20%     |
| 8.01-16.0       | 20        | 20%     |
| 32.01-64.0      | 13        | 13%     |
| More than 256.0 | 6         | 6%      |
| 3.01-4.0        | 3         | 3%      |
| 24.01-32.0      | 3         | 3%      |
| 16.01-24.0      | 3         | 3%      |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 35        | 33.02%  |
| 4.01-8.0   | 27        | 25.47%  |
| 3.01-4.0   | 22        | 20.75%  |
| 8.01-16.0  | 7         | 6.6%    |
| 1.01-2.0   | 6         | 5.66%   |
| 16.01-24.0 | 4         | 3.77%   |
| 32.01-64.0 | 2         | 1.89%   |
| 0.51-1.0   | 2         | 1.89%   |
| 24.01-32.0 | 1         | 0.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 44        | 44%     |
| 2      | 21        | 21%     |
| 3      | 14        | 14%     |
| 4      | 8         | 8%      |
| 5      | 5         | 5%      |
| 10     | 2         | 2%      |
| 6      | 2         | 2%      |
| 26     | 1         | 1%      |
| 25     | 1         | 1%      |
| 20     | 1         | 1%      |
| 9      | 1         | 1%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 79        | 79%     |
| Yes       | 21        | 21%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 89%     |
| No        | 11        | 11%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 64%     |
| No        | 36        | 36%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 61%     |
| No        | 39        | 39%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 22        | 22%     |
| Germany      | 10        | 10%     |
| Brazil       | 10        | 10%     |
| Russia       | 8         | 8%      |
| China        | 5         | 5%      |
| Australia    | 4         | 4%      |
| Italy        | 3         | 3%      |
| Ireland      | 3         | 3%      |
| Canada       | 3         | 3%      |
| Bulgaria     | 3         | 3%      |
| Ukraine      | 2         | 2%      |
| Poland       | 2         | 2%      |
| Japan        | 2         | 2%      |
| Finland      | 2         | 2%      |
| Vietnam      | 1         | 1%      |
| Uzbekistan   | 1         | 1%      |
| Switzerland  | 1         | 1%      |
| Sweden       | 1         | 1%      |
| South Africa | 1         | 1%      |
| Romania      | 1         | 1%      |
| Puerto Rico  | 1         | 1%      |
| Philippines  | 1         | 1%      |
| Norway       | 1         | 1%      |
| Netherlands  | 1         | 1%      |
| Myanmar      | 1         | 1%      |
| Kenya        | 1         | 1%      |
| Kazakhstan   | 1         | 1%      |
| India        | 1         | 1%      |
| Greece       | 1         | 1%      |
| France       | 1         | 1%      |
| Croatia      | 1         | 1%      |
| Colombia     | 1         | 1%      |
| Chile        | 1         | 1%      |
| Belarus      | 1         | 1%      |
| Argentina    | 1         | 1%      |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Moscow               | 4         | 3.88%   |
| Dublin               | 3         | 2.91%   |
| Beijing              | 3         | 2.91%   |
| Sofia                | 2         | 1.94%   |
| Rio de Janeiro       | 2         | 1.94%   |
| Itaperuna            | 2         | 1.94%   |
| Canberra             | 2         | 1.94%   |
| Brooklyn             | 2         | 1.94%   |
| Bristow              | 2         | 1.94%   |
| Zagreb               | 1         | 0.97%   |
| Yangpu               | 1         | 0.97%   |
| Yangon               | 1         | 0.97%   |
| Yakima               | 1         | 0.97%   |
| Wuhan                | 1         | 0.97%   |
| Vitebsk              | 1         | 0.97%   |
| Vicenza              | 1         | 0.97%   |
| Tyumen               | 1         | 0.97%   |
| Tromsø              | 1         | 0.97%   |
| Tomah                | 1         | 0.97%   |
| Tashkent             | 1         | 0.97%   |
| Sykesville           | 1         | 0.97%   |
| Stromberg            | 1         | 0.97%   |
| Stockholm            | 1         | 0.97%   |
| Soest                | 1         | 0.97%   |
| Schemmerhofen        | 1         | 0.97%   |
| Sao Paulo            | 1         | 0.97%   |
| Sao José dos Campos | 1         | 0.97%   |
| Sanford              | 1         | 0.97%   |
| San Juan             | 1         | 0.97%   |
| Ruda Śląska        | 1         | 0.97%   |
| Rostov-on-Don        | 1         | 0.97%   |
| Rome                 | 1         | 0.97%   |
| Ribeirao Preto       | 1         | 0.97%   |
| Redmond              | 1         | 0.97%   |
| Ramstein-Miesenbach  | 1         | 0.97%   |
| Ramenskoye           | 1         | 0.97%   |
| Quitman              | 1         | 0.97%   |
| Québec              | 1         | 0.97%   |
| Puente Alto          | 1         | 0.97%   |
| Porto Alegre         | 1         | 0.97%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 24        | 39     | 15.38%  |
| Seagate                     | 20        | 84     | 12.82%  |
| WDC                         | 15        | 24     | 9.62%   |
| Kingston                    | 12        | 22     | 7.69%   |
| Toshiba                     | 10        | 19     | 6.41%   |
| Sandisk                     | 9         | 31     | 5.77%   |
| Intel                       | 6         | 9      | 3.85%   |
| SK hynix                    | 5         | 5      | 3.21%   |
| Micron Technology           | 5         | 5      | 3.21%   |
| HGST                        | 4         | 15     | 2.56%   |
| Unknown                     | 3         | 5      | 1.92%   |
| Phison Electronics          | 3         | 3      | 1.92%   |
| Hitachi                     | 3         | 4      | 1.92%   |
| DELLBOSS                    | 3         | 3      | 1.92%   |
| Crucial                     | 3         | 21     | 1.92%   |
| Netac                       | 2         | 3      | 1.28%   |
| Micron/Crucial Technology   | 2         | 2      | 1.28%   |
| LITEON                      | 2         | 2      | 1.28%   |
| Hewlett-Packard             | 2         | 3      | 1.28%   |
| ASMT                        | 2         | 2      | 1.28%   |
| WD MediaMax                 | 1         | 1      | 0.64%   |
| VICKTER                     | 1         | 1      | 0.64%   |
| Vi550                       | 1         | 1      | 0.64%   |
| Union Memory                | 1         | 1      | 0.64%   |
| Team                        | 1         | 2      | 0.64%   |
| SPCC                        | 1         | 1      | 0.64%   |
| Plextor                     | 1         | 1      | 0.64%   |
| Phison                      | 1         | 1      | 0.64%   |
| OCZ                         | 1         | 1      | 0.64%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.64%   |
| KIOXIA                      | 1         | 1      | 0.64%   |
| Intenso                     | 1         | 1      | 0.64%   |
| HS-SSD-E100                 | 1         | 1      | 0.64%   |
| HPE                         | 1         | 6      | 0.64%   |
| Hjwdz                       | 1         | 1      | 0.64%   |
| Gigabyte Technology         | 1         | 2      | 0.64%   |
| ETOPSO                      | 1         | 1      | 0.64%   |
| China                       | 1         | 1      | 0.64%   |
| Biwin Storage Technology    | 1         | 1      | 0.64%   |
| ADATA Technology            | 1         | 1      | 0.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 4         | 2.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 3         | 1.7%    |
| DELLBOSS VD 240GB                                  | 3         | 1.7%    |
| Unknown MMC Card  64GB                             | 2         | 1.14%   |
| SK hynix BC511 512GB                               | 2         | 1.14%   |
| Seagate ST1000DM010-2EP102 1TB                     | 2         | 1.14%   |
| Sandisk WD_BLACK SN770 1TB                         | 2         | 1.14%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB              | 2         | 1.14%   |
| SanDisk SDSSDH3 1T00 1TB                           | 2         | 1.14%   |
| Samsung MZNLH512HALU-00000 512GB SSD               | 2         | 1.14%   |
| Netac SSD 256GB                                    | 2         | 1.14%   |
| Micron 2450_MTFDKBA512TFK 512GB                    | 2         | 1.14%   |
| Crucial CT525MX300SSD1 528GB                       | 2         | 1.14%   |
| ASMT 2115 240GB                                    | 2         | 1.14%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                   | 1         | 0.57%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                   | 1         | 0.57%   |
| WDC WD6400BEVT-22A0RT0 640GB                       | 1         | 0.57%   |
| WDC WD60EFRX-68L0BN1 6TB                           | 1         | 0.57%   |
| WDC WD6003FZBX-00K5WB0 6TB                         | 1         | 0.57%   |
| WDC WD5000LPLX-60ZNTT1 500GB                       | 1         | 0.57%   |
| WDC WD5000BEVT-55A0RT0 500GB                       | 1         | 0.57%   |
| WDC WD5000AAKX-083CA1 500GB                        | 1         | 0.57%   |
| WDC WD3200AAKX-753CA1 320GB                        | 1         | 0.57%   |
| WDC WD2500BEVT-00ZCT0 250GB                        | 1         | 0.57%   |
| WDC WD2500AAJS-60M0A0 250GB                        | 1         | 0.57%   |
| WDC WD22EJRX-89BEMY0 2TB                           | 1         | 0.57%   |
| WDC WD20EZAZ-00GGJB0 2TB                           | 1         | 0.57%   |
| WDC WD2003FZEX-00Z4SA0 2TB                         | 1         | 0.57%   |
| WDC WD10EZEX-60M2NA0 1TB                           | 1         | 0.57%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 1         | 0.57%   |
| WDC WD10EZEX-00BN5A0 1TB                           | 1         | 0.57%   |
| WDC WD Blue SA510 2.5 500GB                        | 1         | 0.57%   |
| WD MediaMax WL750GSA6472 752GB                     | 1         | 0.57%   |
| VICKTER SSD 128GB                                  | 1         | 0.57%   |
| Vi550 S3 SSD 2TB                                   | 1         | 0.57%   |
| Unknown MMC Card  7GB                              | 1         | 0.57%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB            | 1         | 0.57%   |
| Toshiba MQ04ABF100 1TB                             | 1         | 0.57%   |
| Toshiba MQ01ABD100 1TB                             | 1         | 0.57%   |
| Toshiba MK2561GSYN 250GB                           | 1         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| Seagate         | 19        | 82     | 35.85%  |
| WDC             | 13        | 21     | 24.53%  |
| Toshiba         | 9         | 17     | 16.98%  |
| HGST            | 4         | 15     | 7.55%   |
| Hitachi         | 3         | 4      | 5.66%   |
| DELLBOSS        | 3         | 3      | 5.66%   |
| WD MediaMax     | 1         | 1      | 1.89%   |
| Hewlett-Packard | 1         | 2      | 1.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 22     | 22.41%  |
| Kingston            | 9         | 19     | 15.52%  |
| SanDisk             | 5         | 14     | 8.62%   |
| WDC                 | 3         | 3      | 5.17%   |
| Intel               | 3         | 5      | 5.17%   |
| Crucial             | 3         | 21     | 5.17%   |
| Netac               | 2         | 3      | 3.45%   |
| Micron Technology   | 2         | 2      | 3.45%   |
| LITEON              | 2         | 2      | 3.45%   |
| ASMT                | 2         | 2      | 3.45%   |
| VICKTER             | 1         | 1      | 1.72%   |
| Vi550               | 1         | 1      | 1.72%   |
| Team                | 1         | 2      | 1.72%   |
| SPCC                | 1         | 1      | 1.72%   |
| Plextor             | 1         | 1      | 1.72%   |
| OCZ                 | 1         | 1      | 1.72%   |
| Intenso             | 1         | 1      | 1.72%   |
| HS-SSD-E100         | 1         | 1      | 1.72%   |
| HPE                 | 1         | 6      | 1.72%   |
| Hewlett-Packard     | 1         | 1      | 1.72%   |
| Gigabyte Technology | 1         | 2      | 1.72%   |
| ETOPSO              | 1         | 1      | 1.72%   |
| China               | 1         | 1      | 1.72%   |
| A-DATA Technology   | 1         | 1      | 1.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 50        | 114    | 36.5%   |
| NVMe    | 43        | 63     | 31.39%  |
| HDD     | 39        | 145    | 28.47%  |
| MMC     | 3         | 5      | 2.19%   |
| Unknown | 2         | 2      | 1.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 70        | 251    | 56.91%  |
| NVMe | 42        | 61     | 34.15%  |
| SAS  | 8         | 12     | 6.5%    |
| MMC  | 3         | 5      | 2.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 47        | 76     | 48.45%  |
| 0.51-1.0   | 29        | 71     | 29.9%   |
| 1.01-2.0   | 13        | 34     | 13.4%   |
| 4.01-10.0  | 4         | 44     | 4.12%   |
| 10.01-20.0 | 3         | 33     | 3.09%   |
| 2.01-3.0   | 1         | 1      | 1.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 26        | 25.24%  |
| 251-500        | 17        | 16.5%   |
| 1001-2000      | 16        | 15.53%  |
| 501-1000       | 14        | 13.59%  |
| More than 3000 | 13        | 12.62%  |
| 51-100         | 7         | 6.8%    |
| 2001-3000      | 6         | 5.83%   |
| Unknown        | 2         | 1.94%   |
| 21-50          | 1         | 0.97%   |
| 1-20           | 1         | 0.97%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 37        | 35.92%  |
| 21-50          | 14        | 13.59%  |
| 101-250        | 12        | 11.65%  |
| 51-100         | 12        | 11.65%  |
| 501-1000       | 8         | 7.77%   |
| 251-500        | 7         | 6.8%    |
| More than 3000 | 6         | 5.83%   |
| 1001-2000      | 4         | 3.88%   |
| Unknown        | 2         | 1.94%   |
| 2001-3000      | 1         | 0.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000LPLX-60ZNTT1 500GB      | 1         | 1      | 9.09%   |
| WDC WD5000AAKX-083CA1 500GB       | 1         | 1      | 9.09%   |
| WDC WD10EZEX-60M2NA0 1TB          | 1         | 1      | 9.09%   |
| Toshiba MQ01ABD100 1TB            | 1         | 1      | 9.09%   |
| Toshiba MK2561GSYN 250GB          | 1         | 1      | 9.09%   |
| Toshiba MK1234GSX 120GB           | 1         | 1      | 9.09%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 9.09%   |
| Seagate ST3250820AS 250GB         | 1         | 1      | 9.09%   |
| Seagate ST32000644NS 2TB          | 1         | 1      | 9.09%   |
| Samsung Electronics SSD 840 250GB | 1         | 1      | 9.09%   |
| Hitachi HTS545050A7E380 500GB     | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 27.27%  |
| Toshiba             | 3         | 3      | 27.27%  |
| Seagate             | 3         | 3      | 27.27%  |
| Samsung Electronics | 1         | 1      | 9.09%   |
| Hitachi             | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 30%     |
| Toshiba | 3         | 3      | 30%     |
| Seagate | 3         | 3      | 30%     |
| Hitachi | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 10     | 90%     |
| SSD  | 1         | 1      | 10%     |

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
| Works    | 57        | 185    | 47.9%   |
| Detected | 52        | 133    | 43.7%   |
| Malfunc  | 10        | 11     | 8.4%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 74        | 48.68%  |
| AMD                          | 12        | 7.89%   |
| Samsung Electronics          | 11        | 7.24%   |
| LSI Logic / Symbios Logic    | 10        | 6.58%   |
| SanDisk                      | 6         | 3.95%   |
| SK hynix                     | 5         | 3.29%   |
| Phison Electronics           | 4         | 2.63%   |
| Marvell Technology Group     | 4         | 2.63%   |
| Micron Technology            | 3         | 1.97%   |
| Kingston Technology Company  | 3         | 1.97%   |
| Broadcom / LSI               | 3         | 1.97%   |
| Micron/Crucial Technology    | 2         | 1.32%   |
| JMicron Technology           | 2         | 1.32%   |
| Adaptec                      | 2         | 1.32%   |
| Union Memory (Shenzhen)      | 1         | 0.66%   |
| Toshiba America Info Systems | 1         | 0.66%   |
| Silicon Image                | 1         | 0.66%   |
| Seagate Technology           | 1         | 0.66%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.66%   |
| KIOXIA                       | 1         | 0.66%   |
| Huawei Technologies          | 1         | 0.66%   |
| Hewlett-Packard              | 1         | 0.66%   |
| Biwin Storage Technology     | 1         | 0.66%   |
| ASMedia Technology           | 1         | 0.66%   |
| ADATA Technology             | 1         | 0.66%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 5.14%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                        | 6         | 3.43%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 6         | 3.43%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 6         | 3.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 3.43%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 2.86%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 5         | 2.86%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 2.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 2.29%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 4         | 2.29%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 4         | 2.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 2.29%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 1.71%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller          | 3         | 1.71%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.71%   |
| Intel SATA Controller [RAID Mode]                                              | 3         | 1.71%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 3         | 1.71%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.71%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 3         | 1.71%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 1.71%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 1.71%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                   | 3         | 1.71%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 1.14%   |
| SK hynix BC511 NVMe SSD                                                        | 2         | 1.14%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 2         | 1.14%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 2         | 1.14%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 1.14%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                           | 2         | 1.14%   |
| Intel SSD 660P Series                                                          | 2         | 1.14%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.14%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.14%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2         | 1.14%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2         | 1.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 1.14%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2         | 1.14%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2         | 1.14%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 1.14%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 1.14%   |
| Adaptec Smart Storage PQI SAS                                                  | 2         | 1.14%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 1         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 79        | 53.38%  |
| NVMe | 42        | 28.38%  |
| RAID | 22        | 14.86%  |
| SAS  | 2         | 1.35%   |
| IDE  | 2         | 1.35%   |
| SCSI | 1         | 0.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| Intel     | 82        | 82%     |
| AMD       | 17        | 17%     |
| HiSilicon | 1         | 1%      |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz     | 2         | 2%      |
| Intel Core i5-8250U CPU @ 1.60GHz       | 2         | 2%      |
| Intel Core i3-3217U CPU @ 1.80GHz       | 2         | 2%      |
| Intel Celeron J4105 CPU @ 1.50GHz       | 2         | 2%      |
| Intel 12th Gen Core i7-1260P            | 2         | 2%      |
| Intel 12th Gen Core i5-12600K           | 2         | 2%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 2%      |
| Intel Xeon Silver 4314 CPU @ 2.40GHz    | 1         | 1%      |
| Intel Xeon Silver 4215R CPU @ 3.20GHz   | 1         | 1%      |
| Intel Xeon Silver 4214 CPU @ 2.20GHz    | 1         | 1%      |
| Intel Xeon Silver 4210 CPU @ 2.20GHz    | 1         | 1%      |
| Intel XEON GOLD 6544Y                   | 1         | 1%      |
| Intel Xeon Gold 6326 CPU @ 2.90GHz      | 1         | 1%      |
| Intel Xeon Gold 6132 CPU @ 2.60GHz      | 1         | 1%      |
| Intel Xeon CPU X3440 @ 2.53GHz          | 1         | 1%      |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz      | 1         | 1%      |
| Intel Xeon CPU E5-2687W v4 @ 3.00GHz    | 1         | 1%      |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz      | 1         | 1%      |
| Intel Xeon CPU E5-2667 v4 @ 3.20GHz     | 1         | 1%      |
| Intel Xeon CPU E5-2650 v4 @ 2.20GHz     | 1         | 1%      |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz     | 1         | 1%      |
| Intel N100                              | 1         | 1%      |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 1%      |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1%      |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1%      |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 1         | 1%      |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1%      |
| Intel Core i7-5930K CPU @ 3.50GHz       | 1         | 1%      |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1%      |
| Intel Core i7-4910MQ CPU @ 2.90GHz      | 1         | 1%      |
| Intel Core i7-4770K CPU @ 3.50GHz       | 1         | 1%      |
| Intel Core i7-4770 CPU @ 3.40GHz        | 1         | 1%      |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 1         | 1%      |
| Intel Core i7-4500U CPU @ 1.80GHz       | 1         | 1%      |
| Intel Core i7-3770K CPU @ 3.50GHz       | 1         | 1%      |
| Intel Core i7-2600K CPU @ 3.40GHz       | 1         | 1%      |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1%      |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 1         | 1%      |
| Intel Core i7 CPU Q 820 @ 1.73GHz       | 1         | 1%      |
| Intel Core i5-8265U CPU @ 1.60GHz       | 1         | 1%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Other                  | 20        | 20%     |
| Intel Core i5          | 19        | 19%     |
| Intel Core i7          | 17        | 17%     |
| Intel Xeon             | 9         | 9%      |
| Intel Core i3          | 7         | 7%      |
| AMD Ryzen 5            | 5         | 5%      |
| Intel Xeon Silver      | 4         | 4%      |
| Intel Celeron          | 4         | 4%      |
| AMD Ryzen 7            | 4         | 4%      |
| AMD Ryzen 9            | 3         | 3%      |
| Intel Xeon Gold        | 2         | 2%      |
| Intel Atom             | 1         | 1%      |
| AMD Ryzen Threadripper | 1         | 1%      |
| AMD Ryzen 3 PRO        | 1         | 1%      |
| AMD FX                 | 1         | 1%      |
| AMD EPYC               | 1         | 1%      |
| AMD A10                | 1         | 1%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 36        | 36%     |
| 2      | 17        | 17%     |
| 6      | 10        | 10%     |
| 16     | 9         | 9%      |
| 12     | 7         | 7%      |
| 8      | 6         | 6%      |
| 24     | 5         | 5%      |
| 32     | 3         | 3%      |
| 10     | 3         | 3%      |
| 14     | 2         | 2%      |
| 28     | 1         | 1%      |
| 1      | 1         | 1%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 90        | 90%     |
| 2      | 10        | 10%     |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 80        | 80%     |
| 1      | 20        | 20%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 99        | 99%     |
| 64-bit         | 1         | 1%      |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 60%     |
| 0x906a3    | 5         | 5%      |
| 0x306c3    | 4         | 4%      |
| 0x306a9    | 4         | 4%      |
| 0x40651    | 3         | 3%      |
| 0x08600106 | 3         | 3%      |
| 0x806ec    | 2         | 2%      |
| 0x406e3    | 2         | 2%      |
| 0xa0671    | 1         | 1%      |
| 0xa0653    | 1         | 1%      |
| 0xa0652    | 1         | 1%      |
| 0x90672    | 1         | 1%      |
| 0x806ea    | 1         | 1%      |
| 0x706e5    | 1         | 1%      |
| 0x706a8    | 1         | 1%      |
| 0x606a6    | 1         | 1%      |
| 0x306f2    | 1         | 1%      |
| 0x206a7    | 1         | 1%      |
| 0x20652    | 1         | 1%      |
| 0x0a50000c | 1         | 1%      |
| 0x0a201016 | 1         | 1%      |
| 0x08701021 | 1         | 1%      |
| 0x08701013 | 1         | 1%      |
| 0x06001119 | 1         | 1%      |
| 0x0600063d | 1         | 1%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 13        | 12.87%  |
| KabyLake         | 12        | 11.88%  |
| Alderlake Hybrid | 11        | 10.89%  |
| Zen 2            | 8         | 7.92%   |
| Skylake          | 7         | 6.93%   |
| IvyBridge        | 7         | 6.93%   |
| SandyBridge      | 5         | 4.95%   |
| Icelake          | 5         | 4.95%   |
| Broadwell        | 5         | 4.95%   |
| Zen 3            | 4         | 3.96%   |
| TigerLake        | 4         | 3.96%   |
| Unknown          | 4         | 3.96%   |
| Goldmont plus    | 3         | 2.97%   |
| CometLake        | 3         | 2.97%   |
| Nehalem          | 2         | 1.98%   |
| Zen+             | 1         | 0.99%   |
| Westmere         | 1         | 0.99%   |
| Tremont          | 1         | 0.99%   |
| Sapphire Rapids  | 1         | 0.99%   |
| Piledriver       | 1         | 0.99%   |
| Gracemont        | 1         | 0.99%   |
| Bulldozer        | 1         | 0.99%   |
| Bonnell          | 1         | 0.99%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 52        | 42.28%  |
| Nvidia                     | 35        | 28.46%  |
| AMD                        | 18        | 14.63%  |
| Matrox Electronics Systems | 12        | 9.76%   |
| ASPEED Technology          | 5         | 4.07%   |
| Huawei Technologies        | 1         | 0.81%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Matrox Electronics Systems G200eR2                                          | 6         | 4.72%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 5         | 3.94%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 3.94%   |
| ASPEED Technology ASPEED Graphics Family                                    | 5         | 3.94%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller    | 4         | 3.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 3.15%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 4         | 3.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 3         | 2.36%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                    | 3         | 2.36%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3         | 2.36%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3         | 2.36%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2         | 1.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.57%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                       | 2         | 1.57%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 2         | 1.57%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                     | 2         | 1.57%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 1.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 1.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2         | 1.57%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2         | 1.57%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.79%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 0.79%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1         | 0.79%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 0.79%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1         | 0.79%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1         | 0.79%   |
| Nvidia GT216GLM [Quadro FX 880M]                                            | 1         | 0.79%   |
| Nvidia GP108M [GeForce MX330]                                               | 1         | 0.79%   |
| Nvidia GP108M [GeForce MX250]                                               | 1         | 0.79%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 0.79%   |
| Nvidia GP107M [GeForce MX350]                                               | 1         | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.79%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                     | 1         | 0.79%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1         | 0.79%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1         | 0.79%   |
| Nvidia GM108M [GeForce MX110]                                               | 1         | 0.79%   |
| Nvidia GM108M [GeForce 940MX]                                               | 1         | 0.79%   |
| Nvidia GM107M [GeForce GTX 850M]                                            | 1         | 0.79%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                       | 1         | 0.79%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1         | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 33        | 33%     |
| 1 x Nvidia              | 17        | 17%     |
| Intel + Nvidia          | 15        | 15%     |
| 1 x AMD                 | 11        | 11%     |
| 1 x Matrox              | 10        | 10%     |
| 1 x ASPEED              | 4         | 4%      |
| 2 x AMD                 | 3         | 3%      |
| Nvidia + Matrox         | 2         | 2%      |
| Intel + AMD             | 2         | 2%      |
| 1 x Huawei Technologies | 1         | 1%      |
| AMD + Nvidia            | 1         | 1%      |
| AMD + ASPEED            | 1         | 1%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 85        | 84.16%  |
| Proprietary | 10        | 9.9%    |
| Unknown     | 6         | 5.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 59        | 56.73%  |
| 1.01-2.0   | 12        | 11.54%  |
| 3.01-4.0   | 10        | 9.62%   |
| 0.51-1.0   | 6         | 5.77%   |
| 0.01-0.5   | 6         | 5.77%   |
| 5.01-6.0   | 5         | 4.81%   |
| 8.01-16.0  | 5         | 4.81%   |
| 7.01-8.0   | 1         | 0.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 12        | 12.5%   |
| Samsung Electronics     | 9         | 9.38%   |
| LG Display              | 9         | 9.38%   |
| Dell                    | 9         | 9.38%   |
| Chimei Innolux          | 6         | 6.25%   |
| Goldstar                | 5         | 5.21%   |
| BOE                     | 4         | 4.17%   |
| ViewSonic               | 3         | 3.13%   |
| Iiyama                  | 3         | 3.13%   |
| BenQ                    | 3         | 3.13%   |
| Acer                    | 3         | 3.13%   |
| Unknown (XXX)           | 2         | 2.08%   |
| Hewlett-Packard         | 2         | 2.08%   |
| AOC                     | 2         | 2.08%   |
| TMX                     | 1         | 1.04%   |
| SKY                     | 1         | 1.04%   |
| Sharp                   | 1         | 1.04%   |
| Philips                 | 1         | 1.04%   |
| PANDA                   | 1         | 1.04%   |
| NXG                     | 1         | 1.04%   |
| NEC Computers           | 1         | 1.04%   |
| MStar                   | 1         | 1.04%   |
| MSI                     | 1         | 1.04%   |
| LG Electronics          | 1         | 1.04%   |
| Lenovo                  | 1         | 1.04%   |
| KVM                     | 1         | 1.04%   |
| InfoVision              | 1         | 1.04%   |
| HKC                     | 1         | 1.04%   |
| HannStar                | 1         | 1.04%   |
| GVV                     | 1         | 1.04%   |
| Gigabyte Technology     | 1         | 1.04%   |
| Eizo                    | 1         | 1.04%   |
| Denver                  | 1         | 1.04%   |
| CSO                     | 1         | 1.04%   |
| Chi Mei Optoelectronics | 1         | 1.04%   |
| CHD                     | 1         | 1.04%   |
| ASUSTek Computer        | 1         | 1.04%   |
| Unknown                 | 1         | 1.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Iiyama PL2888H IVM7106 1920x1080 621x341mm 27.9-inch                    | 2         | 1.96%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                   | 2         | 1.96%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch           | 1         | 0.98%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch           | 1         | 0.98%   |
| ViewSonic PJ402D-2 HCD7B1D 1280x1024                                    | 1         | 0.98%   |
| Unknown (XXX) FURRION TV XXX3553 1920x1080 520x290mm 23.4-inch          | 1         | 0.98%   |
| Unknown (XXX) Beyond TV XXX9221 1920x1080 1209x680mm 54.6-inch          | 1         | 0.98%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch                 | 1         | 0.98%   |
| SKY 22X1-M225F SKY2150 1920x1080 476x268mm 21.5-inch                    | 1         | 0.98%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                 | 1         | 0.98%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch       | 1         | 0.98%   |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch    | 1         | 0.98%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch    | 1         | 0.98%   |
| Samsung Electronics SMT22A350 SAM07A7 1920x1080 477x268mm 21.5-inch     | 1         | 0.98%   |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 477x268mm 21.5-inch      | 1         | 0.98%   |
| Samsung Electronics S27C450 SAM09D9 1920x1080 598x336mm 27.0-inch       | 1         | 0.98%   |
| Samsung Electronics S22E310 SAM0C2C 1920x1080 477x268mm 21.5-inch       | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch   | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SAM7048 1366x768 522x293mm 23.6-inch    | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1         | 0.98%   |
| Philips LCD Monitor 215Vw 1920x1080                                     | 1         | 0.98%   |
| PANDA LCD Monitor NCP0052 1920x1080 309x174mm 14.0-inch                 | 1         | 0.98%   |
| NXG MIRAI DML-517 NXG138B 1280x1024 338x270mm 17.0-inch                 | 1         | 0.98%   |
| NEC Computers EA232WMi NEC6816 1920x1080 510x287mm 23.0-inch            | 1         | 0.98%   |
| NEC Computers EA232WMi NEC6814 1920x1080 510x287mm 23.0-inch            | 1         | 0.98%   |
| MStar LCD Monitor Demo 1920x1080                                        | 1         | 0.98%   |
| MSI MAG342CQRV MSI3DB6 3440x1440 797x333mm 34.0-inch                    | 1         | 0.98%   |
| LG Electronics LCD Monitor LG FULL HD                                   | 1         | 0.98%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch            | 1         | 0.98%   |
| LG Display LCD Monitor LGD068A 1920x1080 309x174mm 14.0-inch            | 1         | 0.98%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch            | 1         | 0.98%   |
| LG Display LCD Monitor LGD05E4 1920x1080 344x194mm 15.5-inch            | 1         | 0.98%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch            | 1         | 0.98%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch            | 1         | 0.98%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch             | 1         | 0.98%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch             | 1         | 0.98%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch             | 1         | 0.98%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                | 1         | 0.98%   |
| KVM LCD Monitor1919 KVM4308 1280x1024 376x301mm 19.0-inch               | 1         | 0.98%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch            | 1         | 0.98%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 51        | 55.43%  |
| 1366x768 (WXGA)    | 9         | 9.78%   |
| 3840x2160 (4K)     | 7         | 7.61%   |
| 2560x1440 (QHD)    | 5         | 5.43%   |
| 1920x1200 (WUXGA)  | 4         | 4.35%   |
| 3440x1440          | 3         | 3.26%   |
| 1600x900 (HD+)     | 3         | 3.26%   |
| 1280x1024 (SXGA)   | 2         | 2.17%   |
| Unknown            | 2         | 2.17%   |
| 5760x1080          | 1         | 1.09%   |
| 3840x1080          | 1         | 1.09%   |
| 3200x2000          | 1         | 1.09%   |
| 1680x1050 (WSXGA+) | 1         | 1.09%   |
| 1440x900 (WXGA+)   | 1         | 1.09%   |
| 1280x960           | 1         | 1.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 14      | 17        | 17.35%  |
| 15      | 16        | 16.33%  |
| 27      | 11        | 11.22%  |
| 21      | 11        | 11.22%  |
| 23      | 9         | 9.18%   |
| 24      | 8         | 8.16%   |
| Unknown | 5         | 5.1%    |
| 17      | 3         | 3.06%   |
| 13      | 3         | 3.06%   |
| 34      | 2         | 2.04%   |
| 32      | 2         | 2.04%   |
| 19      | 2         | 2.04%   |
| 84      | 1         | 1.02%   |
| 54      | 1         | 1.02%   |
| 38      | 1         | 1.02%   |
| 35      | 1         | 1.02%   |
| 31      | 1         | 1.02%   |
| 25      | 1         | 1.02%   |
| 22      | 1         | 1.02%   |
| 18      | 1         | 1.02%   |
| 16      | 1         | 1.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 36        | 37.89%  |
| 501-600     | 22        | 23.16%  |
| 401-500     | 14        | 14.74%  |
| 601-700     | 5         | 5.26%   |
| Unknown     | 5         | 5.26%   |
| 701-800     | 4         | 4.21%   |
| 351-400     | 4         | 4.21%   |
| 801-900     | 2         | 2.11%   |
| 201-300     | 1         | 1.05%   |
| 1501-2000   | 1         | 1.05%   |
| 1001-1500   | 1         | 1.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 67        | 79.76%  |
| 16/10   | 7         | 8.33%   |
| Unknown | 4         | 4.76%   |
| 21/9    | 3         | 3.57%   |
| 5/4     | 2         | 2.38%   |
| 4/3     | 1         | 1.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 23        | 23.96%  |
| 81-90          | 19        | 19.79%  |
| 101-110        | 15        | 15.63%  |
| 301-350        | 11        | 11.46%  |
| 351-500        | 6         | 6.25%   |
| Unknown        | 5         | 5.21%   |
| 251-300        | 4         | 4.17%   |
| 151-200        | 3         | 3.13%   |
| More than 1000 | 2         | 2.08%   |
| 141-150        | 2         | 2.08%   |
| 121-130        | 2         | 2.08%   |
| 111-120        | 2         | 2.08%   |
| 71-80          | 1         | 1.04%   |
| 501-1000       | 1         | 1.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 29        | 30.85%  |
| 51-100        | 28        | 29.79%  |
| 101-120       | 24        | 25.53%  |
| 161-240       | 5         | 5.32%   |
| Unknown       | 5         | 5.32%   |
| More than 240 | 2         | 2.13%   |
| 1-50          | 1         | 1.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 66        | 64.71%  |
| 2     | 17        | 16.67%  |
| 0     | 17        | 16.67%  |
| 4     | 1         | 0.98%   |
| 3     | 1         | 0.98%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 62        | 39.49%  |
| Realtek Semiconductor             | 41        | 26.11%  |
| Qualcomm Atheros                  | 13        | 8.28%   |
| Broadcom                          | 11        | 7.01%   |
| Ralink Technology                 | 4         | 2.55%   |
| Mellanox Technologies             | 4         | 2.55%   |
| TP-Link                           | 2         | 1.27%   |
| Dell                              | 2         | 1.27%   |
| ASUSTek Computer                  | 2         | 1.27%   |
| ASIX Electronics                  | 2         | 1.27%   |
| Aquantia                          | 2         | 1.27%   |
| Xiaomi                            | 1         | 0.64%   |
| U-Blox                            | 1         | 0.64%   |
| Solarflare Communications         | 1         | 0.64%   |
| Seeed Technology                  | 1         | 0.64%   |
| MediaTek                          | 1         | 0.64%   |
| Insyde Software                   | 1         | 0.64%   |
| IBM                               | 1         | 0.64%   |
| Huawei Technologies               | 1         | 0.64%   |
| Ericsson Business Mobile Networks | 1         | 0.64%   |
| DisplayLink                       | 1         | 0.64%   |
| Ceton Technologies                | 1         | 0.64%   |
| Broadcom Limited                  | 1         | 0.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 29        | 14.95%  |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 3.09%   |
| Intel Ethernet Controller I225-V                                       | 6         | 3.09%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 6         | 3.09%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 6         | 3.09%   |
| Intel Wireless 7260                                                    | 4         | 2.06%   |
| Intel Wi-Fi 6 AX200                                                    | 4         | 2.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 1.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 3         | 1.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 1.55%   |
| Intel Wireless 8265 / 8275                                             | 3         | 1.55%   |
| Intel Wireless 7265                                                    | 3         | 1.55%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 1.55%   |
| Intel I350 Gigabit Network Connection                                  | 3         | 1.55%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 1.55%   |
| Intel I210 Gigabit Network Connection                                  | 3         | 1.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 1.55%   |
| Intel 82574L Gigabit Network Connection                                | 3         | 1.55%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller  | 3         | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 2         | 1.03%   |
| Ralink RT5370 Wireless Adapter                                         | 2         | 1.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2         | 1.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2         | 1.03%   |
| Intel Wireless 8260                                                    | 2         | 1.03%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                          | 2         | 1.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 1.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 2         | 1.03%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 1.03%   |
| Intel 700 Series Chipset CNVi WiFi                                     | 2         | 1.03%   |
| Dell iDRAC Virtual NIC                                                 | 2         | 1.03%   |
| ASUS 802.11ac NIC                                                      | 2         | 1.03%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 1.03%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.52%   |
| U-Blox [u-blox 8]                                                      | 1         | 0.52%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 1         | 0.52%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1         | 0.52%   |
| Solarflare SFC9120 10G Ethernet Controller                             | 1         | 0.52%   |
| Seeed Seeeduino_Cortex_M0+                                             | 1         | 0.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 40        | 57.97%  |
| Qualcomm Atheros      | 12        | 17.39%  |
| Realtek Semiconductor | 7         | 10.14%  |
| Ralink Technology     | 4         | 5.8%    |
| TP-Link               | 2         | 2.9%    |
| ASUSTek Computer      | 2         | 2.9%    |
| MediaTek              | 1         | 1.45%   |
| Broadcom              | 1         | 1.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 4         | 5.8%    |
| Intel Wi-Fi 6 AX200                                            | 4         | 5.8%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 4         | 5.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 4.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 4.35%   |
| Intel Wireless 8265 / 8275                                     | 3         | 4.35%   |
| Intel Wireless 7265                                            | 3         | 4.35%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 4.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 2.9%    |
| Ralink RT5370 Wireless Adapter                                 | 2         | 2.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 2.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 2.9%    |
| Intel Wireless 8260                                            | 2         | 2.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 2.9%    |
| Intel 700 Series Chipset CNVi WiFi                             | 2         | 2.9%    |
| ASUS 802.11ac NIC                                              | 2         | 2.9%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1         | 1.45%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 1.45%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 1.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.45%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 1         | 1.45%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 1.45%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.45%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 1.45%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 1         | 1.45%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.45%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 1.45%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 1.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.45%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.45%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.45%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 1.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 40        | 36.7%   |
| Realtek Semiconductor     | 39        | 35.78%  |
| Broadcom                  | 10        | 9.17%   |
| Mellanox Technologies     | 4         | 3.67%   |
| Qualcomm Atheros          | 2         | 1.83%   |
| Dell                      | 2         | 1.83%   |
| ASIX Electronics          | 2         | 1.83%   |
| Aquantia                  | 2         | 1.83%   |
| Xiaomi                    | 1         | 0.92%   |
| Solarflare Communications | 1         | 0.92%   |
| Insyde Software           | 1         | 0.92%   |
| IBM                       | 1         | 0.92%   |
| Huawei Technologies       | 1         | 0.92%   |
| DisplayLink               | 1         | 0.92%   |
| Ceton Technologies        | 1         | 0.92%   |
| Broadcom Limited          | 1         | 0.92%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 29        | 23.77%  |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 4.92%   |
| Intel Ethernet Controller I225-V                                       | 6         | 4.92%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 6         | 4.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 2.46%   |
| Intel I350 Gigabit Network Connection                                  | 3         | 2.46%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 2.46%   |
| Intel I210 Gigabit Network Connection                                  | 3         | 2.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 2.46%   |
| Intel 82574L Gigabit Network Connection                                | 3         | 2.46%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller  | 3         | 2.46%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                          | 2         | 1.64%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 1.64%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 1.64%   |
| Dell iDRAC Virtual NIC                                                 | 2         | 1.64%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 1.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.82%   |
| Solarflare SFC9120 10G Ethernet Controller                             | 1         | 0.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 0.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.82%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.82%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.82%   |
| Mellanox MT2892 Family [ConnectX-6 Dx]                                 | 1         | 0.82%   |
| Mellanox MT27800 Family [ConnectX-5]                                   | 1         | 0.82%   |
| Mellanox MT27700 Family [ConnectX-4]                                   | 1         | 0.82%   |
| Mellanox MT27500 Family [ConnectX-3]                                   | 1         | 0.82%   |
| Intel Ethernet Controller XL710 for 40GbE QSFP+                        | 1         | 0.82%   |
| Intel Ethernet Controller X710/X557-AT 10GBASE-T                       | 1         | 0.82%   |
| Intel Ethernet Controller X710 for 10GBASE-T                           | 1         | 0.82%   |
| Intel Ethernet Controller X550                                         | 1         | 0.82%   |
| Intel Ethernet Controller I226-V                                       | 1         | 0.82%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.82%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.82%   |
| Intel Ethernet Connection I218-V                                       | 1         | 0.82%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.82%   |
| Intel Ethernet Connection I217-V                                       | 1         | 0.82%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 0.82%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 0.82%   |
| Intel Ethernet Connection (5) I219-V                                   | 1         | 0.82%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 89        | 57.05%  |
| WiFi     | 64        | 41.03%  |
| Modem    | 3         | 1.92%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 55        | 59.14%  |
| WiFi     | 38        | 40.86%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 51        | 51%     |
| 1     | 29        | 29%     |
| 4     | 6         | 6%      |
| 3     | 5         | 5%      |
| 6     | 4         | 4%      |
| 8     | 2         | 2%      |
| 10    | 1         | 1%      |
| 7     | 1         | 1%      |
| 0     | 1         | 1%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 76        | 76%     |
| Yes  | 24        | 24%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 38        | 61.29%  |
| Qualcomm Atheros Communications | 6         | 9.68%   |
| Realtek Semiconductor           | 5         | 8.06%   |
| Lite-On Technology              | 3         | 4.84%   |
| Broadcom                        | 3         | 4.84%   |
| IMC Networks                    | 2         | 3.23%   |
| MediaTek                        | 1         | 1.61%   |
| Integrated System Solution      | 1         | 1.61%   |
| Foxconn / Hon Hai               | 1         | 1.61%   |
| Cambridge Silicon Radio         | 1         | 1.61%   |
| ASUSTek Computer                | 1         | 1.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 13        | 20.97%  |
| Intel Bluetooth Device                              | 7         | 11.29%  |
| Intel AX201 Bluetooth                               | 6         | 9.68%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 8.06%   |
| Realtek Bluetooth Radio                             | 4         | 6.45%   |
| Intel AX200 Bluetooth                               | 4         | 6.45%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 4.84%   |
| Lite-On Bluetooth Device                            | 2         | 3.23%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 3.23%   |
| Realtek Bluetooth 5.4 Radio                         | 1         | 1.61%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.61%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.61%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.61%   |
| MediaTek Wireless_Device                            | 1         | 1.61%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.61%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.61%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.61%   |
| Integrated System Solution Bluetooth Device         | 1         | 1.61%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.61%   |
| IMC Networks Bluetooth Device                       | 1         | 1.61%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.61%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.61%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.61%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 64        | 53.33%  |
| Nvidia                   | 24        | 20%     |
| AMD                      | 22        | 18.33%  |
| SteelSeries ApS          | 3         | 2.5%    |
| Walmart                  | 1         | 0.83%   |
| Micro Star International | 1         | 0.83%   |
| KTMicro                  | 1         | 0.83%   |
| JBL                      | 1         | 0.83%   |
| Giga-Byte Technology     | 1         | 0.83%   |
| Generalplus Technology   | 1         | 0.83%   |
| DSEA A/S                 | 1         | 0.83%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 8         | 5.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 5%      |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 7         | 5%      |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 4.29%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 4.29%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 3.57%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 3.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 2.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 2.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.14%   |
| Intel Raptor Lake High Definition Audio Controller                         | 3         | 2.14%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 2.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 2.14%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 2.14%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.43%   |
| Nvidia TU102 High Definition Audio Controller                              | 2         | 1.43%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 1.43%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 1.43%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.43%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 2         | 1.43%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.43%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.43%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.43%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 1.43%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.43%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 1.43%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 1.43%   |
| Walmart AB13X Headset Adapter                                              | 1         | 0.71%   |
| SteelSeries ApS SteelSeries Siberia 800                                    | 1         | 0.71%   |
| SteelSeries ApS SteelSeries GameDAC                                        | 1         | 0.71%   |
| SteelSeries ApS Arctis Nova Pro Wireless                                   | 1         | 0.71%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.71%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.71%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.71%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.71%   |
| Nvidia GM200 High Definition Audio                                         | 1         | 0.71%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.71%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.71%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 22        | 32.84%  |
| SK hynix            | 13        | 19.4%   |
| Crucial             | 6         | 8.96%   |
| Kingston            | 4         | 5.97%   |
| Corsair             | 4         | 5.97%   |
| Unknown (ABCD)      | 3         | 4.48%   |
| Micron Technology   | 3         | 4.48%   |
| G.Skill             | 3         | 4.48%   |
| Unknown             | 2         | 2.99%   |
| Team                | 1         | 1.49%   |
| Smart Brazil        | 1         | 1.49%   |
| SHARETRONIC         | 1         | 1.49%   |
| Ramaxel Technology  | 1         | 1.49%   |
| Elpida              | 1         | 1.49%   |
| A-DATA Technology   | 1         | 1.49%   |
| 019400B300CE        | 1         | 1.49%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s | 3         | 4.23%   |
| SK hynix RAM HMA84GR7DJR4N-XN 32GB DIMM DDR4 3200MT/s          | 2         | 2.82%   |
| SK hynix RAM HMA84GR7AFR4N-UH 32GB DIMM DDR4 2400MT/s          | 2         | 2.82%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 2.82%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 2         | 2.82%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                     | 1         | 1.41%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s           | 1         | 1.41%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1866MT/s             | 1         | 1.41%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s   | 1         | 1.41%   |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s                     | 1         | 1.41%   |
| SK hynix RAM Module 2GB Row Of Chips LPDDR4 4267MT/s           | 1         | 1.41%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM 1334MT/s              | 1         | 1.41%   |
| SK hynix RAM HMT31GR7BFR4A-H9 8GB DIMM DDR3 1333MT/s           | 1         | 1.41%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s         | 1         | 1.41%   |
| SK hynix RAM HMAA8GR7AJR4N-XN 64GB DIMM DDR4 3200MT/s          | 1         | 1.41%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s        | 1         | 1.41%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s        | 1         | 1.41%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s        | 1         | 1.41%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 1.41%   |
| SHARETRONIC RAM Module 4GB SODIMM DDR3 800MT/s                 | 1         | 1.41%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 1.41%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR5 4000MT/s            | 1         | 1.41%   |
| Samsung RAM M474A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s         | 1         | 1.41%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s          | 1         | 1.41%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s          | 1         | 1.41%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 1         | 1.41%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 1.41%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s          | 1         | 1.41%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s          | 1         | 1.41%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s          | 1         | 1.41%   |
| Samsung RAM M393B1K70DH0-YH9 8GB DIMM DDR3 1333MT/s            | 1         | 1.41%   |
| Samsung RAM M393A4K40EB3-CWE 32GB DIMM DDR4 3200MT/s           | 1         | 1.41%   |
| Samsung RAM M393A4K40CB2-CTD 32GB DIMM DDR4 2667MT/s           | 1         | 1.41%   |
| Samsung RAM M393A4K40BB2-CTD 32GB DIMM DDR4 2667MT/s           | 1         | 1.41%   |
| Samsung RAM M393A2K43BB1-CRC 16GB DIMM DDR4 2400MT/s           | 1         | 1.41%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s           | 1         | 1.41%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s            | 1         | 1.41%   |
| Samsung RAM M321R8GA0PB0-CWMCJ 64GB DIMM DDR5 5600MT/s         | 1         | 1.41%   |
| Samsung RAM K4UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.41%   |
| Samsung RAM K3LKBKB0BM-MGCP 2GB Row Of Chips LPDDR5 6400MT/s   | 1         | 1.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 33        | 54.1%   |
| DDR3   | 16        | 26.23%  |
| LPDDR4 | 5         | 8.2%    |
| DDR5   | 3         | 4.92%   |
| LPDDR5 | 2         | 3.28%   |
| DRAM   | 2         | 3.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 31        | 51.67%  |
| SODIMM       | 23        | 38.33%  |
| Row Of Chips | 6         | 10%     |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 25        | 37.88%  |
| 32768 | 13        | 19.7%   |
| 16384 | 13        | 19.7%   |
| 4096  | 9         | 13.64%  |
| 2048  | 4         | 6.06%   |
| 65536 | 2         | 3.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 12        | 19.05%  |
| 2400  | 12        | 19.05%  |
| 2667  | 8         | 12.7%   |
| 1600  | 8         | 12.7%   |
| 2133  | 3         | 4.76%   |
| 5600  | 2         | 3.17%   |
| 4267  | 2         | 3.17%   |
| 4000  | 2         | 3.17%   |
| 1866  | 2         | 3.17%   |
| 800   | 2         | 3.17%   |
| 6400  | 1         | 1.59%   |
| 4800  | 1         | 1.59%   |
| 3600  | 1         | 1.59%   |
| 3466  | 1         | 1.59%   |
| 2933  | 1         | 1.59%   |
| 2666  | 1         | 1.59%   |
| 1800  | 1         | 1.59%   |
| 1334  | 1         | 1.59%   |
| 1333  | 1         | 1.59%   |
| 1067  | 1         | 1.59%   |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 9         | 19.15%  |
| IMC Networks                           | 5         | 10.64%  |
| Bison Electronics                      | 5         | 10.64%  |
| Realtek Semiconductor                  | 4         | 8.51%   |
| Logitech                               | 4         | 8.51%   |
| Syntek                                 | 3         | 6.38%   |
| Sunplus Innovation Technology          | 3         | 6.38%   |
| Microdia                               | 3         | 6.38%   |
| Silicon Motion                         | 2         | 4.26%   |
| Luxvisions Innotech Limited            | 2         | 4.26%   |
| Lite-On Technology                     | 2         | 4.26%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.26%   |
| Lenovo                                 | 1         | 2.13%   |
| KYE Systems                            | 1         | 2.13%   |
| Apple                                  | 1         | 2.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                            | 3         | 6.25%   |
| Chicony Integrated Camera                           | 3         | 6.25%   |
| Bison Integrated Camera                             | 3         | 6.25%   |
| Sunplus Full HD webcam                              | 2         | 4.17%   |
| Realtek Integrated_Webcam_HD                        | 2         | 4.17%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 4.17%   |
| Logitech Webcam C270                                | 2         | 4.17%   |
| Logitech C922 Pro Stream Webcam                     | 2         | 4.17%   |
| IMC Networks Integrated Camera                      | 2         | 4.17%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 2.08%   |
| Silicon Motion WebCam SC-13HDL12131N                | 1         | 2.08%   |
| Silicon Motion WebCam SC-13HDL11939N                | 1         | 2.08%   |
| Realtek Lenovo EasyCamera                           | 1         | 2.08%   |
| Realtek Integrated Webcam                           | 1         | 2.08%   |
| Microdia USB Live camera                            | 1         | 2.08%   |
| Microdia USB 2.0 Camera                             | 1         | 2.08%   |
| Microdia Integrated_Webcam_HD                       | 1         | 2.08%   |
| Lite-On Integrated Camera                           | 1         | 2.08%   |
| Lite-On HP Wide Vision FHD Camera                   | 1         | 2.08%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 2.08%   |
| KYE Systems FaceCam 1320                            | 1         | 2.08%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 2.08%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 2.08%   |
| IMC Networks Integrated RGB Camera                  | 1         | 2.08%   |
| Chicony USB2.0 2M WebCam                            | 1         | 2.08%   |
| Chicony USB 5M WebCam                               | 1         | 2.08%   |
| Chicony Thinkpad T430 camera                        | 1         | 2.08%   |
| Chicony HP HD Camera                                | 1         | 2.08%   |
| Chicony HD WebCam (Asus N-series)                   | 1         | 2.08%   |
| Chicony HD WebCam                                   | 1         | 2.08%   |
| Chicony Acer CrystalEye Webcam                      | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 2.08%   |
| Bison Lenovo Integrated Webcam                      | 1         | 2.08%   |
| Bison HD Webcam                                     | 1         | 2.08%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 1         | 2.08%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 3         | 37.5%   |
| Synaptics             | 3         | 37.5%   |
| Upek                  | 1         | 12.5%   |
| LighTuning Technology | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Upek   | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 58        | 56.31%  |
| 1     | 24        | 23.3%   |
| 2     | 11        | 10.68%  |
| 3     | 7         | 6.8%    |
| 5     | 2         | 1.94%   |
| 4     | 1         | 0.97%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 16        | 23.53%  |
| Unassigned class         | 13        | 19.12%  |
| Graphics card            | 10        | 14.71%  |
| Fingerprint reader       | 8         | 11.76%  |
| Net/wireless             | 7         | 10.29%  |
| Multimedia controller    | 3         | 4.41%   |
| Storage                  | 2         | 2.94%   |
| Firewire controller      | 2         | 2.94%   |
| Bluetooth                | 2         | 2.94%   |
| Storage/ata              | 1         | 1.47%   |
| Sound                    | 1         | 1.47%   |
| Net/ethernet             | 1         | 1.47%   |
| Dvb card                 | 1         | 1.47%   |
| Chipcard                 | 1         | 1.47%   |

