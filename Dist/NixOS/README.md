NixOS - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for NixOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/NixOS/Desktop/README.md) and [notebooks](/Dist/NixOS/Notebook/README.md).

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

Total: 303

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E6540              | Notebook    | [8fdc000f7e](https://linux-hardware.org/?probe=8fdc000f7e) | Oct 01, 2023 |
| Dell          | Latitude E6540              | Notebook    | [a5de8b78e7](https://linux-hardware.org/?probe=a5de8b78e7) | Oct 01, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [1135ddac8e](https://linux-hardware.org/?probe=1135ddac8e) | Sep 30, 2023 |
| MSI           | Z68A-GD65                   | Desktop     | [c0f968740b](https://linux-hardware.org/?probe=c0f968740b) | Sep 29, 2023 |
| Dell          | Latitude 5430               | Notebook    | [583aa8cf02](https://linux-hardware.org/?probe=583aa8cf02) | Sep 29, 2023 |
| Intel         | SharkBay Platform           | Notebook    | [2406bf1c0d](https://linux-hardware.org/?probe=2406bf1c0d) | Sep 29, 2023 |
| Dell          | Latitude E6540              | Notebook    | [1478e1265d](https://linux-hardware.org/?probe=1478e1265d) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [0177e96165](https://linux-hardware.org/?probe=0177e96165) | Sep 28, 2023 |
| HP            | 3397                        | Desktop     | [5c1b3bed0b](https://linux-hardware.org/?probe=5c1b3bed0b) | Sep 28, 2023 |
| ASUSTek       | P8H77-V                     | Desktop     | [24ff983f95](https://linux-hardware.org/?probe=24ff983f95) | Sep 28, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [009a6a1a98](https://linux-hardware.org/?probe=009a6a1a98) | Sep 27, 2023 |
| Dell          | Latitude E6540              | Notebook    | [7d9885cd7c](https://linux-hardware.org/?probe=7d9885cd7c) | Sep 27, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [78d31814cf](https://linux-hardware.org/?probe=78d31814cf) | Sep 26, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [0d7d5f0613](https://linux-hardware.org/?probe=0d7d5f0613) | Sep 26, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [086b0dc21a](https://linux-hardware.org/?probe=086b0dc21a) | Sep 23, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [220a0f8733](https://linux-hardware.org/?probe=220a0f8733) | Sep 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [bf71bcd90e](https://linux-hardware.org/?probe=bf71bcd90e) | Sep 22, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | Notebook    | [ad989ac089](https://linux-hardware.org/?probe=ad989ac089) | Sep 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4d2c8f9f07](https://linux-hardware.org/?probe=4d2c8f9f07) | Sep 20, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [5e50efa2c4](https://linux-hardware.org/?probe=5e50efa2c4) | Sep 19, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | Notebook    | [aebeeb7401](https://linux-hardware.org/?probe=aebeeb7401) | Sep 17, 2023 |
| HP            | 1998                        | Desktop     | [4af6b915c2](https://linux-hardware.org/?probe=4af6b915c2) | Sep 17, 2023 |
| Dell          | Latitude E6540              | Notebook    | [ff29b23e60](https://linux-hardware.org/?probe=ff29b23e60) | Sep 13, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [ff31b68cf3](https://linux-hardware.org/?probe=ff31b68cf3) | Sep 12, 2023 |
| Lenovo        | ThinkPad T480 20L6S4RV00    | Notebook    | [8ae7288bf3](https://linux-hardware.org/?probe=8ae7288bf3) | Sep 11, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD00B... | Notebook    | [5778731f85](https://linux-hardware.org/?probe=5778731f85) | Sep 10, 2023 |
| HP            | 8767 A                      | Desktop     | [ce91ccf3a9](https://linux-hardware.org/?probe=ce91ccf3a9) | Sep 09, 2023 |
| Dell          | Precision 5680              | Notebook    | [fdcb7ce5d4](https://linux-hardware.org/?probe=fdcb7ce5d4) | Sep 05, 2023 |
| Lenovo        | ThinkPad T470 20HES2RC00    | Notebook    | [390104a086](https://linux-hardware.org/?probe=390104a086) | Aug 28, 2023 |
| Dell          | Wyse 5470                   | Notebook    | [6d45205020](https://linux-hardware.org/?probe=6d45205020) | Aug 27, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [ac09f27b9d](https://linux-hardware.org/?probe=ac09f27b9d) | Aug 22, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | Desktop     | [a9a56ae120](https://linux-hardware.org/?probe=a9a56ae120) | Aug 22, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [aed7eacff0](https://linux-hardware.org/?probe=aed7eacff0) | Aug 20, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [9e03b48bf3](https://linux-hardware.org/?probe=9e03b48bf3) | Aug 15, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [320138e7f5](https://linux-hardware.org/?probe=320138e7f5) | Aug 11, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [72bb72d2aa](https://linux-hardware.org/?probe=72bb72d2aa) | Aug 08, 2023 |
| AZW           | EQ                          | Desktop     | [4a9aad33f3](https://linux-hardware.org/?probe=4a9aad33f3) | Aug 06, 2023 |
| ASUSTek       | ProArt StudioBook W730G5... | Notebook    | [c384115725](https://linux-hardware.org/?probe=c384115725) | Aug 05, 2023 |
| ASUSTek       | Zenbook UN5401RA UN5401R... | Convertible | [13c8b276bb](https://linux-hardware.org/?probe=13c8b276bb) | Aug 04, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1abcf2ad6f](https://linux-hardware.org/?probe=1abcf2ad6f) | Aug 04, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [39fbf6393c](https://linux-hardware.org/?probe=39fbf6393c) | Aug 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [a6c2e042e4](https://linux-hardware.org/?probe=a6c2e042e4) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [f75ea8cfef](https://linux-hardware.org/?probe=f75ea8cfef) | Aug 02, 2023 |
| Teclast       | F5                          | Convertible | [76fcc31a43](https://linux-hardware.org/?probe=76fcc31a43) | Aug 01, 2023 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [e452f85fb8](https://linux-hardware.org/?probe=e452f85fb8) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [19b6ecf591](https://linux-hardware.org/?probe=19b6ecf591) | Jul 29, 2023 |
| System76      | Pangolin                    | Notebook    | [3b37a9bedb](https://linux-hardware.org/?probe=3b37a9bedb) | Jul 29, 2023 |
| Alienware     | 17                          | Notebook    | [25f67e59b8](https://linux-hardware.org/?probe=25f67e59b8) | Jul 26, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [959f3b36df](https://linux-hardware.org/?probe=959f3b36df) | Jul 26, 2023 |
| HP            | 1998                        | Desktop     | [ef5201611b](https://linux-hardware.org/?probe=ef5201611b) | Jul 24, 2023 |
| HP            | 1998                        | Desktop     | [5a95ac128d](https://linux-hardware.org/?probe=5a95ac128d) | Jul 24, 2023 |
| AZW           | EQ                          | Desktop     | [e065c16f2c](https://linux-hardware.org/?probe=e065c16f2c) | Jul 23, 2023 |
| AZW           | EQ                          | Desktop     | [46a76eeb81](https://linux-hardware.org/?probe=46a76eeb81) | Jul 23, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [8d48a50003](https://linux-hardware.org/?probe=8d48a50003) | Jul 22, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [c29abaca55](https://linux-hardware.org/?probe=c29abaca55) | Jul 22, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [568ab8dd45](https://linux-hardware.org/?probe=568ab8dd45) | Jul 21, 2023 |
| ASUSTek       | 1005HA                      | Notebook    | [59a0d6a7bb](https://linux-hardware.org/?probe=59a0d6a7bb) | Jul 19, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [1e8eeb8513](https://linux-hardware.org/?probe=1e8eeb8513) | Jul 16, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [8efa3cf99d](https://linux-hardware.org/?probe=8efa3cf99d) | Jul 16, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [9bb1b8fbca](https://linux-hardware.org/?probe=9bb1b8fbca) | Jul 12, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [62fac1de1c](https://linux-hardware.org/?probe=62fac1de1c) | Jul 08, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d7afc91d12](https://linux-hardware.org/?probe=d7afc91d12) | Jul 07, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [a2dc9efa21](https://linux-hardware.org/?probe=a2dc9efa21) | Jul 06, 2023 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [f1c343e2c2](https://linux-hardware.org/?probe=f1c343e2c2) | Jul 02, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | Notebook    | [95c540792e](https://linux-hardware.org/?probe=95c540792e) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [f15cf1d31b](https://linux-hardware.org/?probe=f15cf1d31b) | Jul 02, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [4d377fc8b8](https://linux-hardware.org/?probe=4d377fc8b8) | Jul 01, 2023 |
| Dell          | Latitude E5470              | Notebook    | [fd56f44c38](https://linux-hardware.org/?probe=fd56f44c38) | Jun 29, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [4c4d870bdb](https://linux-hardware.org/?probe=4c4d870bdb) | Jun 29, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [de699b13ba](https://linux-hardware.org/?probe=de699b13ba) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [699aa2d6e1](https://linux-hardware.org/?probe=699aa2d6e1) | Jun 26, 2023 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [cf6a7757d5](https://linux-hardware.org/?probe=cf6a7757d5) | Jun 26, 2023 |
| Microtech     | CoreBook Lite               | Notebook    | [1840bef280](https://linux-hardware.org/?probe=1840bef280) | Jun 24, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [2812cf43d0](https://linux-hardware.org/?probe=2812cf43d0) | Jun 23, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [925e5f0915](https://linux-hardware.org/?probe=925e5f0915) | Jun 22, 2023 |
| MECHREVO      | WUJIE 14                    | Notebook    | [a55e31b287](https://linux-hardware.org/?probe=a55e31b287) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [9726121d1b](https://linux-hardware.org/?probe=9726121d1b) | Jun 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [c5c0838f41](https://linux-hardware.org/?probe=c5c0838f41) | Jun 18, 2023 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [46ffcb9672](https://linux-hardware.org/?probe=46ffcb9672) | Jun 18, 2023 |
| Lenovo        | Yoga 14sARE 2020 82A8       | Notebook    | [fa79d9b26d](https://linux-hardware.org/?probe=fa79d9b26d) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [85902981fd](https://linux-hardware.org/?probe=85902981fd) | Jun 11, 2023 |
| MACHENIKE     | F117-7P                     | Notebook    | [78ad896b83](https://linux-hardware.org/?probe=78ad896b83) | Jun 10, 2023 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [754d228b9b](https://linux-hardware.org/?probe=754d228b9b) | Jun 09, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [309d09ae8c](https://linux-hardware.org/?probe=309d09ae8c) | Jun 03, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [0d31f94244](https://linux-hardware.org/?probe=0d31f94244) | May 30, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c9c4e5ddb5](https://linux-hardware.org/?probe=c9c4e5ddb5) | May 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [cc8e36e75a](https://linux-hardware.org/?probe=cc8e36e75a) | May 26, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [6607361205](https://linux-hardware.org/?probe=6607361205) | May 25, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [19dc1505b5](https://linux-hardware.org/?probe=19dc1505b5) | May 24, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [4396db2f33](https://linux-hardware.org/?probe=4396db2f33) | May 22, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [b309bee7e9](https://linux-hardware.org/?probe=b309bee7e9) | May 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [e0cbba6897](https://linux-hardware.org/?probe=e0cbba6897) | May 16, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [acd8d0441a](https://linux-hardware.org/?probe=acd8d0441a) | May 15, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [aefc60eaea](https://linux-hardware.org/?probe=aefc60eaea) | May 11, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [c40c2cb964](https://linux-hardware.org/?probe=c40c2cb964) | May 10, 2023 |
| Acer          | Spin SP514-51N              | Convertible | [6b23655b4b](https://linux-hardware.org/?probe=6b23655b4b) | May 10, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [4d84deed6b](https://linux-hardware.org/?probe=4d84deed6b) | May 09, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [21ecf73d3a](https://linux-hardware.org/?probe=21ecf73d3a) | May 09, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [29b2378b4b](https://linux-hardware.org/?probe=29b2378b4b) | May 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [62b28b69dc](https://linux-hardware.org/?probe=62b28b69dc) | May 08, 2023 |
| UNOWHY        | Y13G011S4EI                 | Notebook    | [581cd68800](https://linux-hardware.org/?probe=581cd68800) | May 02, 2023 |
| Gigabyte      | B760 GAMING X DDR4          | Desktop     | [6ee65c19d2](https://linux-hardware.org/?probe=6ee65c19d2) | May 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [493bc0b894](https://linux-hardware.org/?probe=493bc0b894) | Apr 29, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [5792e8cfa2](https://linux-hardware.org/?probe=5792e8cfa2) | Apr 29, 2023 |
| Dell          | 0KFKMF A00                  | All in one  | [cbae954ecc](https://linux-hardware.org/?probe=cbae954ecc) | Apr 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | Notebook    | [2063d4a9fc](https://linux-hardware.org/?probe=2063d4a9fc) | Apr 27, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [b8b51b29ef](https://linux-hardware.org/?probe=b8b51b29ef) | Apr 25, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [7fd17e2245](https://linux-hardware.org/?probe=7fd17e2245) | Apr 22, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [bbbc9206b4](https://linux-hardware.org/?probe=bbbc9206b4) | Apr 17, 2023 |
| Avell High... | A70 MOB                     | Notebook    | [869b1ae79b](https://linux-hardware.org/?probe=869b1ae79b) | Apr 17, 2023 |
| Lenovo        | ThinkPad P50 20EN0005GE     | Notebook    | [85a4de4e58](https://linux-hardware.org/?probe=85a4de4e58) | Apr 12, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [63035ef97f](https://linux-hardware.org/?probe=63035ef97f) | Apr 12, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [6ce8b7fb26](https://linux-hardware.org/?probe=6ce8b7fb26) | Apr 11, 2023 |
| Dell          | XPS 9320                    | Notebook    | [c78c87474d](https://linux-hardware.org/?probe=c78c87474d) | Apr 05, 2023 |
| GPD           | G1621-02                    | Notebook    | [2ed8b6c147](https://linux-hardware.org/?probe=2ed8b6c147) | Mar 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [10ec4f48dd](https://linux-hardware.org/?probe=10ec4f48dd) | Mar 16, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [f53ad14ea5](https://linux-hardware.org/?probe=f53ad14ea5) | Mar 13, 2023 |
| ASUSTek       | 1005HA                      | Notebook    | [3326423f04](https://linux-hardware.org/?probe=3326423f04) | Mar 06, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [8bf9dd7b83](https://linux-hardware.org/?probe=8bf9dd7b83) | Mar 05, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4fc82abdeb](https://linux-hardware.org/?probe=4fc82abdeb) | Mar 04, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [c4f08a9fc3](https://linux-hardware.org/?probe=c4f08a9fc3) | Mar 04, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c4d51ca1b8](https://linux-hardware.org/?probe=c4d51ca1b8) | Mar 04, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [8abe852ff0](https://linux-hardware.org/?probe=8abe852ff0) | Mar 03, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4c25c88937](https://linux-hardware.org/?probe=4c25c88937) | Mar 03, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [4f3c01941d](https://linux-hardware.org/?probe=4f3c01941d) | Feb 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [9b044bd920](https://linux-hardware.org/?probe=9b044bd920) | Feb 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [c8c79f26d8](https://linux-hardware.org/?probe=c8c79f26d8) | Feb 26, 2023 |
| Lenovo        | 13w Yoga 82S1               | Convertible | [616e689b13](https://linux-hardware.org/?probe=616e689b13) | Feb 19, 2023 |
| Lenovo        | 13w Yoga 82S1               | Convertible | [5f59be48e1](https://linux-hardware.org/?probe=5f59be48e1) | Feb 16, 2023 |
| Lenovo        | 13w Yoga 82S1               | Convertible | [68effccd60](https://linux-hardware.org/?probe=68effccd60) | Feb 16, 2023 |
| Teclast       | F5                          | Convertible | [e62bdaaa3b](https://linux-hardware.org/?probe=e62bdaaa3b) | Feb 13, 2023 |
| Teclast       | F5                          | Convertible | [30e30a5c3e](https://linux-hardware.org/?probe=30e30a5c3e) | Feb 13, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [8ac9c4b4ef](https://linux-hardware.org/?probe=8ac9c4b4ef) | Feb 09, 2023 |
| Acer          | Switch SW713-51GNP          | Tablet      | [46ecb88f1d](https://linux-hardware.org/?probe=46ecb88f1d) | Feb 08, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [eb768bf205](https://linux-hardware.org/?probe=eb768bf205) | Feb 03, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [75a3416ebc](https://linux-hardware.org/?probe=75a3416ebc) | Jan 31, 2023 |
| Lenovo        | ThinkPad X230 2333AZ2       | Notebook    | [d9d0138294](https://linux-hardware.org/?probe=d9d0138294) | Jan 19, 2023 |
| Blackview     | AceBook 1                   | Notebook    | [ea4db42aa8](https://linux-hardware.org/?probe=ea4db42aa8) | Jan 19, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [b795f7c940](https://linux-hardware.org/?probe=b795f7c940) | Jan 19, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [0e4ba05b0f](https://linux-hardware.org/?probe=0e4ba05b0f) | Jan 15, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [226b8e5ff8](https://linux-hardware.org/?probe=226b8e5ff8) | Jan 15, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [b99e4815bc](https://linux-hardware.org/?probe=b99e4815bc) | Jan 10, 2023 |
| Dell          | Latitude 7420               | Notebook    | [e770b3e784](https://linux-hardware.org/?probe=e770b3e784) | Jan 04, 2023 |
| Dell          | Latitude 7420               | Notebook    | [bab9b86606](https://linux-hardware.org/?probe=bab9b86606) | Jan 04, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [b721a47fa4](https://linux-hardware.org/?probe=b721a47fa4) | Jan 03, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [d5df950832](https://linux-hardware.org/?probe=d5df950832) | Jan 03, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [6a53c626dd](https://linux-hardware.org/?probe=6a53c626dd) | Jan 02, 2023 |
| Dell          | Precision M4800             | Notebook    | [505f1b47dc](https://linux-hardware.org/?probe=505f1b47dc) | Dec 30, 2022 |
| ASUSTek       | Z87-C                       | Desktop     | [4929f6a6c9](https://linux-hardware.org/?probe=4929f6a6c9) | Dec 28, 2022 |
| Dell          | Inspiron 7586               | Convertible | [d670af270f](https://linux-hardware.org/?probe=d670af270f) | Dec 28, 2022 |
| GPD           | WIN2                        | Notebook    | [d7d31b67d0](https://linux-hardware.org/?probe=d7d31b67d0) | Dec 28, 2022 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [84c6275c04](https://linux-hardware.org/?probe=84c6275c04) | Dec 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cf62b1c520](https://linux-hardware.org/?probe=cf62b1c520) | Dec 20, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [db7b91ac2f](https://linux-hardware.org/?probe=db7b91ac2f) | Dec 17, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [e070540587](https://linux-hardware.org/?probe=e070540587) | Dec 16, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [e4ba0262b4](https://linux-hardware.org/?probe=e4ba0262b4) | Dec 16, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [1a9c49eb4f](https://linux-hardware.org/?probe=1a9c49eb4f) | Dec 16, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [893190593e](https://linux-hardware.org/?probe=893190593e) | Dec 12, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ee5f96d645](https://linux-hardware.org/?probe=ee5f96d645) | Dec 09, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [3c18fca709](https://linux-hardware.org/?probe=3c18fca709) | Dec 09, 2022 |
| Dell          | 0F0XJ6 A11                  | Server      | [3dfa1ba4b1](https://linux-hardware.org/?probe=3dfa1ba4b1) | Dec 09, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [110e3eab7f](https://linux-hardware.org/?probe=110e3eab7f) | Dec 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [d512bff9cc](https://linux-hardware.org/?probe=d512bff9cc) | Dec 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [fef748b3f4](https://linux-hardware.org/?probe=fef748b3f4) | Dec 04, 2022 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [f698b715e4](https://linux-hardware.org/?probe=f698b715e4) | Nov 30, 2022 |
| Dell          | Inspiron 7586               | Convertible | [91dcb3265a](https://linux-hardware.org/?probe=91dcb3265a) | Nov 24, 2022 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [b79f103dd5](https://linux-hardware.org/?probe=b79f103dd5) | Nov 24, 2022 |
| Acer          | Aspire A315-54K             | Notebook    | [12f19e4fbe](https://linux-hardware.org/?probe=12f19e4fbe) | Nov 23, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [44a3785f1f](https://linux-hardware.org/?probe=44a3785f1f) | Nov 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [0c889920b5](https://linux-hardware.org/?probe=0c889920b5) | Nov 12, 2022 |
| Dell          | Latitude E5540              | Notebook    | [f2420e40cd](https://linux-hardware.org/?probe=f2420e40cd) | Nov 06, 2022 |
| Dell          | Latitude E5540              | Notebook    | [2456786404](https://linux-hardware.org/?probe=2456786404) | Nov 06, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [b60f8a187c](https://linux-hardware.org/?probe=b60f8a187c) | Nov 04, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [33d3e9ce22](https://linux-hardware.org/?probe=33d3e9ce22) | Nov 03, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [c242c45dbe](https://linux-hardware.org/?probe=c242c45dbe) | Nov 01, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [fce691523b](https://linux-hardware.org/?probe=fce691523b) | Oct 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [d58a7c30a9](https://linux-hardware.org/?probe=d58a7c30a9) | Oct 26, 2022 |
| Lenovo        | ThinkPad E470 20H1006JIX    | Notebook    | [8bc8778497](https://linux-hardware.org/?probe=8bc8778497) | Oct 26, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [6ffc032b64](https://linux-hardware.org/?probe=6ffc032b64) | Oct 25, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [d79322ca4a](https://linux-hardware.org/?probe=d79322ca4a) | Oct 19, 2022 |
| Dell          | Precision 5760              | Notebook    | [4255007db8](https://linux-hardware.org/?probe=4255007db8) | Oct 18, 2022 |
| HP            | ZBook Studio G5             | Notebook    | [0a9b0167c7](https://linux-hardware.org/?probe=0a9b0167c7) | Oct 17, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [aa5ea0c17c](https://linux-hardware.org/?probe=aa5ea0c17c) | Oct 14, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [ae775f1f89](https://linux-hardware.org/?probe=ae775f1f89) | Oct 13, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [99232ffba3](https://linux-hardware.org/?probe=99232ffba3) | Oct 13, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [c203d7c388](https://linux-hardware.org/?probe=c203d7c388) | Oct 07, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3a409e83a0](https://linux-hardware.org/?probe=3a409e83a0) | Oct 07, 2022 |
| Dell          | 0F0XJ6 A11                  | Server      | [5eb1758869](https://linux-hardware.org/?probe=5eb1758869) | Oct 07, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [8e301a5e4e](https://linux-hardware.org/?probe=8e301a5e4e) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [263276babe](https://linux-hardware.org/?probe=263276babe) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [86e1da35ba](https://linux-hardware.org/?probe=86e1da35ba) | Sep 30, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [564eb3b439](https://linux-hardware.org/?probe=564eb3b439) | Sep 28, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [085bd81d5b](https://linux-hardware.org/?probe=085bd81d5b) | Sep 28, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [b21f5fee1a](https://linux-hardware.org/?probe=b21f5fee1a) | Sep 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [7fc4cdb860](https://linux-hardware.org/?probe=7fc4cdb860) | Sep 22, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3f823868fd](https://linux-hardware.org/?probe=3f823868fd) | Sep 15, 2022 |
| Dell          | Precision M4800             | Notebook    | [fae4dbff63](https://linux-hardware.org/?probe=fae4dbff63) | Sep 13, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [ad69daf392](https://linux-hardware.org/?probe=ad69daf392) | Sep 11, 2022 |
| Dell          | 0F0XJ6 A11                  | Server      | [a02c8258ba](https://linux-hardware.org/?probe=a02c8258ba) | Sep 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7986ddc1d9](https://linux-hardware.org/?probe=7986ddc1d9) | Sep 11, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [98fd9b974e](https://linux-hardware.org/?probe=98fd9b974e) | Sep 09, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [305905e674](https://linux-hardware.org/?probe=305905e674) | Sep 07, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [ce872c873e](https://linux-hardware.org/?probe=ce872c873e) | Aug 24, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [19d3fab687](https://linux-hardware.org/?probe=19d3fab687) | Aug 21, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [898a635cdd](https://linux-hardware.org/?probe=898a635cdd) | Aug 20, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [28e67ea5a7](https://linux-hardware.org/?probe=28e67ea5a7) | Aug 20, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [9351f31042](https://linux-hardware.org/?probe=9351f31042) | Aug 13, 2022 |
| Dell          | Latitude 7420               | Notebook    | [219cf18b1e](https://linux-hardware.org/?probe=219cf18b1e) | Jul 06, 2022 |
| ASUSTek       | H97I-PLUS                   | Desktop     | [982df0dba9](https://linux-hardware.org/?probe=982df0dba9) | Jun 22, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B+     | Soc         | [2911b2782c](https://linux-hardware.org/?probe=2911b2782c) | Jun 21, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [6d5fdb800a](https://linux-hardware.org/?probe=6d5fdb800a) | Jun 20, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [a4621aa4ec](https://linux-hardware.org/?probe=a4621aa4ec) | Jun 19, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [380770f287](https://linux-hardware.org/?probe=380770f287) | Jun 15, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [248f252b2a](https://linux-hardware.org/?probe=248f252b2a) | Jun 13, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [d26f08ea88](https://linux-hardware.org/?probe=d26f08ea88) | Jun 12, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [0123caa2f3](https://linux-hardware.org/?probe=0123caa2f3) | Jun 11, 2022 |
| Lenovo        | ThinkPad X230 23243E9       | Notebook    | [85ffd2561e](https://linux-hardware.org/?probe=85ffd2561e) | Jun 08, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [affa614c99](https://linux-hardware.org/?probe=affa614c99) | Jun 07, 2022 |
| Dell          | Latitude 7420               | Notebook    | [5be44c8aae](https://linux-hardware.org/?probe=5be44c8aae) | Jun 01, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [ab13de0478](https://linux-hardware.org/?probe=ab13de0478) | May 27, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [96b24b0640](https://linux-hardware.org/?probe=96b24b0640) | May 20, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [5cd59453b1](https://linux-hardware.org/?probe=5cd59453b1) | Apr 15, 2022 |
| Framework     | Laptop                      | Notebook    | [4997cab79b](https://linux-hardware.org/?probe=4997cab79b) | Apr 14, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [2cb837e17f](https://linux-hardware.org/?probe=2cb837e17f) | Apr 14, 2022 |
| Lenovo        | ThinkPad T490 20N2000LUK    | Notebook    | [a394ce9693](https://linux-hardware.org/?probe=a394ce9693) | Apr 13, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [50d2e86de8](https://linux-hardware.org/?probe=50d2e86de8) | Apr 13, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [fb5bcd7c77](https://linux-hardware.org/?probe=fb5bcd7c77) | Apr 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [502a8c9d32](https://linux-hardware.org/?probe=502a8c9d32) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | Notebook    | [729b19eda3](https://linux-hardware.org/?probe=729b19eda3) | Apr 13, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [46b46c842f](https://linux-hardware.org/?probe=46b46c842f) | Apr 13, 2022 |
| Supermicro    | X8DT6                       | Server      | [0fd3b261c7](https://linux-hardware.org/?probe=0fd3b261c7) | Apr 03, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4c96d9df2f](https://linux-hardware.org/?probe=4c96d9df2f) | Apr 02, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [5570a879d3](https://linux-hardware.org/?probe=5570a879d3) | Mar 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [d6cae900dc](https://linux-hardware.org/?probe=d6cae900dc) | Mar 13, 2022 |
| ASUSTek       | P8Q77-M                     | Desktop     | [6cd75b6762](https://linux-hardware.org/?probe=6cd75b6762) | Mar 11, 2022 |
| GPD           | MicroPC                     | Notebook    | [a572eb2b39](https://linux-hardware.org/?probe=a572eb2b39) | Mar 11, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [815cb9ab49](https://linux-hardware.org/?probe=815cb9ab49) | Mar 11, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [f031fb1a5a](https://linux-hardware.org/?probe=f031fb1a5a) | Mar 11, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [1d6563ada3](https://linux-hardware.org/?probe=1d6563ada3) | Mar 11, 2022 |
| Lenovo        | ThinkPad T540p 20BE005YM... | Notebook    | [6d0cd0f4b9](https://linux-hardware.org/?probe=6d0cd0f4b9) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S6MF02    | Notebook    | [5e026c07c0](https://linux-hardware.org/?probe=5e026c07c0) | Mar 10, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [5c984c6d9a](https://linux-hardware.org/?probe=5c984c6d9a) | Mar 09, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [40d2eced72](https://linux-hardware.org/?probe=40d2eced72) | Mar 09, 2022 |
| EVGA          | X299 FTW K                  | Desktop     | [6f9489b2e6](https://linux-hardware.org/?probe=6f9489b2e6) | Mar 09, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [524b675e7e](https://linux-hardware.org/?probe=524b675e7e) | Mar 09, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [f38279e396](https://linux-hardware.org/?probe=f38279e396) | Mar 09, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [273737b3d7](https://linux-hardware.org/?probe=273737b3d7) | Feb 25, 2022 |
| OBSIDIAN-P... | N13_N140ZU                  | Notebook    | [9f2fdbfce5](https://linux-hardware.org/?probe=9f2fdbfce5) | Feb 25, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [a1d172dbc0](https://linux-hardware.org/?probe=a1d172dbc0) | Feb 16, 2022 |
| Dell          | Latitude 7420               | Notebook    | [64178dcbb7](https://linux-hardware.org/?probe=64178dcbb7) | Feb 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | Notebook    | [cf3fa03922](https://linux-hardware.org/?probe=cf3fa03922) | Jan 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | Notebook    | [d62840031f](https://linux-hardware.org/?probe=d62840031f) | Jan 08, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [c84b603f92](https://linux-hardware.org/?probe=c84b603f92) | Jan 04, 2022 |
| Lenovo        | Legion 5 17ARH05H 82GN      | Notebook    | [9e022a2288](https://linux-hardware.org/?probe=9e022a2288) | Dec 26, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | Notebook    | [8ff8fb5efd](https://linux-hardware.org/?probe=8ff8fb5efd) | Dec 26, 2021 |
| ASUSTek       | Z170-P                      | Desktop     | [d4bac456d1](https://linux-hardware.org/?probe=d4bac456d1) | Dec 16, 2021 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [e5dc04e6a5](https://linux-hardware.org/?probe=e5dc04e6a5) | Dec 16, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [eb5d5f4361](https://linux-hardware.org/?probe=eb5d5f4361) | Dec 12, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [5fb4f1b6a6](https://linux-hardware.org/?probe=5fb4f1b6a6) | Nov 29, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [af887c3f7b](https://linux-hardware.org/?probe=af887c3f7b) | Nov 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [dbe8d36249](https://linux-hardware.org/?probe=dbe8d36249) | Nov 04, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [349fbeb586](https://linux-hardware.org/?probe=349fbeb586) | Oct 23, 2021 |
| Teclast       | F5                          | Convertible | [0854310843](https://linux-hardware.org/?probe=0854310843) | Oct 08, 2021 |
| Lenovo        | ThinkPad X250 20CLS18S0T    | Notebook    | [0151eadf78](https://linux-hardware.org/?probe=0151eadf78) | Oct 06, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [66d71367c1](https://linux-hardware.org/?probe=66d71367c1) | Aug 24, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [bd919b4bd6](https://linux-hardware.org/?probe=bd919b4bd6) | Aug 22, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [36c94af49d](https://linux-hardware.org/?probe=36c94af49d) | Aug 09, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [87a418ce6c](https://linux-hardware.org/?probe=87a418ce6c) | Aug 09, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [3df83086ef](https://linux-hardware.org/?probe=3df83086ef) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [052ccd7a40](https://linux-hardware.org/?probe=052ccd7a40) | Aug 07, 2021 |
| MSI           | X399 SLI PLUS               | Desktop     | [128ae965a7](https://linux-hardware.org/?probe=128ae965a7) | Aug 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [48fd4d3b89](https://linux-hardware.org/?probe=48fd4d3b89) | Aug 06, 2021 |
| Dell          | Inspiron 7391 2n1           | Convertible | [f632a64d73](https://linux-hardware.org/?probe=f632a64d73) | Jul 22, 2021 |
| Dell          | Latitude 7420               | Notebook    | [0624aeffd1](https://linux-hardware.org/?probe=0624aeffd1) | Jul 19, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [d93a80d973](https://linux-hardware.org/?probe=d93a80d973) | Jul 14, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [59a699d357](https://linux-hardware.org/?probe=59a699d357) | Jul 14, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | Notebook    | [d14e0ef395](https://linux-hardware.org/?probe=d14e0ef395) | Jun 18, 2021 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [60eed45305](https://linux-hardware.org/?probe=60eed45305) | Jun 18, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [0619809b36](https://linux-hardware.org/?probe=0619809b36) | Jun 01, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [6056eac50c](https://linux-hardware.org/?probe=6056eac50c) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [bd9fb4818b](https://linux-hardware.org/?probe=bd9fb4818b) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [12fa3ffea5](https://linux-hardware.org/?probe=12fa3ffea5) | May 31, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [fc12f446bb](https://linux-hardware.org/?probe=fc12f446bb) | May 23, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [f03b19461f](https://linux-hardware.org/?probe=f03b19461f) | May 16, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [529e915984](https://linux-hardware.org/?probe=529e915984) | May 16, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [d323a9cfbf](https://linux-hardware.org/?probe=d323a9cfbf) | Apr 23, 2021 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | Notebook    | [38ab65a49b](https://linux-hardware.org/?probe=38ab65a49b) | Mar 18, 2021 |
| ASUSTek       | Pro WS W480-ACE             | Desktop     | [3825190816](https://linux-hardware.org/?probe=3825190816) | Mar 11, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d55d51a3e2](https://linux-hardware.org/?probe=d55d51a3e2) | Feb 08, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [188755ebc7](https://linux-hardware.org/?probe=188755ebc7) | Oct 25, 2020 |
| Hardkernel    | ODROID-H2                   | Desktop     | [a5d75a24e5](https://linux-hardware.org/?probe=a5d75a24e5) | Oct 13, 2020 |
| Lenovo        | ThinkPad T580 20L90024PB    | Notebook    | [8dc60fafaa](https://linux-hardware.org/?probe=8dc60fafaa) | Oct 13, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b85fb81c59](https://linux-hardware.org/?probe=b85fb81c59) | Sep 28, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [5656cda6a4](https://linux-hardware.org/?probe=5656cda6a4) | Sep 01, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [550264c421](https://linux-hardware.org/?probe=550264c421) | Aug 22, 2020 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [5f7f2db973](https://linux-hardware.org/?probe=5f7f2db973) | Aug 21, 2020 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [cc8de41afd](https://linux-hardware.org/?probe=cc8de41afd) | Aug 21, 2020 |
| HP            | 8055                        | Desktop     | [1165b457fa](https://linux-hardware.org/?probe=1165b457fa) | Jul 08, 2020 |
| HP            | 8055                        | Desktop     | [a5c65e8d4a](https://linux-hardware.org/?probe=a5c65e8d4a) | Jul 08, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | Notebook    | [71029187b1](https://linux-hardware.org/?probe=71029187b1) | Jul 03, 2020 |
| ASRock        | TRX40 Creator               | Desktop     | [2cefd65bfb](https://linux-hardware.org/?probe=2cefd65bfb) | Jun 29, 2020 |
| Acer          | Aspire E5-576G              | Notebook    | [c126c8b2fd](https://linux-hardware.org/?probe=c126c8b2fd) | Apr 15, 2020 |
| Gigabyte      | Sabre 15                    | Notebook    | [4f92cff461](https://linux-hardware.org/?probe=4f92cff461) | Jul 14, 2019 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| NixOS 23.05                      | 65        | 28.02%  |
| NixOS 22.11                      | 53        | 22.84%  |
| NixOS 22.05                      | 37        | 15.95%  |
| NixOS 23.11                      | 24        | 10.34%  |
| NixOS 21.11                      | 18        | 7.76%   |
| NixOS                            | 5         | 2.16%   |
| NixOS 21.05pre-git               | 2         | 0.86%   |
| NixOS 20.09pre-git               | 2         | 0.86%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 0.43%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 0.43%   |
| NixOS 21.11.20210528.540dccb     | 1         | 0.43%   |
| NixOS 21.05.git.62d4591722f      | 1         | 0.43%   |
| NixOS 21.05.git.2e369bb2f4e      | 1         | 0.43%   |
| NixOS 21.05.993.93963c27b93      | 1         | 0.43%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 0.43%   |
| NixOS 21.05.3509.7daf35532d2     | 1         | 0.43%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 0.43%   |
| NixOS 21.05.2132.733682c3292     | 1         | 0.43%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1         | 0.43%   |
| NixOS 21.05.20210929.ee90403     | 1         | 0.43%   |
| NixOS 21.05.20210430.c8dff32     | 1         | 0.43%   |
| NixOS 21.05.20210423.c21475e     | 1         | 0.43%   |
| NixOS 21.05.20210224.f6b5bfd     | 1         | 0.43%   |
| NixOS 21.05.1471.a7512bb64b1     | 1         | 0.43%   |
| NixOS 21.03pre246062.420f89ceb26 | 1         | 0.43%   |
| NixOS 21.03.git.b4349c13a6d      | 1         | 0.43%   |
| NixOS 21.03.20201007.420f89c     | 1         | 0.43%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 0.43%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1         | 0.43%   |
| NixOS 20.09.git.4a361b06a93      | 1         | 0.43%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 0.43%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 0.43%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 0.43%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 0.43%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| NixOS | 207       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version     | Computers | Percent |
|-------------|-----------|---------|
| 6.1.51      | 5         | 2%      |
| 5.15.74     | 5         | 2%      |
| 6.4.0       | 4         | 1.6%    |
| 6.3.8       | 4         | 1.6%    |
| 6.3.3       | 4         | 1.6%    |
| 6.1.38      | 4         | 1.6%    |
| 5.15.86     | 4         | 1.6%    |
| 5.15.43     | 4         | 1.6%    |
| 6.3.1       | 3         | 1.2%    |
| 6.2.0-rc6   | 3         | 1.2%    |
| 6.1.55      | 3         | 1.2%    |
| 6.1.53      | 3         | 1.2%    |
| 6.1.42      | 3         | 1.2%    |
| 6.1.35      | 3         | 1.2%    |
| 6.1.31      | 3         | 1.2%    |
| 6.1.0       | 3         | 1.2%    |
| 6.0.11      | 3         | 1.2%    |
| 6.0.10      | 3         | 1.2%    |
| 5.15.82     | 3         | 1.2%    |
| 5.15.72     | 3         | 1.2%    |
| 5.15.68     | 3         | 1.2%    |
| 5.15.47     | 3         | 1.2%    |
| 5.15.26     | 3         | 1.2%    |
| 6.5.2       | 2         | 0.8%    |
| 6.4.7       | 2         | 0.8%    |
| 6.4.6       | 2         | 0.8%    |
| 6.1.47      | 2         | 0.8%    |
| 6.1.45      | 2         | 0.8%    |
| 6.1.41      | 2         | 0.8%    |
| 6.1.39      | 2         | 0.8%    |
| 6.1.37      | 2         | 0.8%    |
| 6.1.34      | 2         | 0.8%    |
| 6.1.27      | 2         | 0.8%    |
| 6.1.24      | 2         | 0.8%    |
| 6.1.1       | 2         | 0.8%    |
| 5.8.1-zen1  | 2         | 0.8%    |
| 5.19.14     | 2         | 0.8%    |
| 5.18.19     | 2         | 0.8%    |
| 5.17.1      | 2         | 0.8%    |
| 5.16.8-zen1 | 2         | 0.8%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.4.0   | 5         | 2%      |
| 6.1.51  | 5         | 2%      |
| 5.15.74 | 5         | 2%      |
| 6.3.8   | 4         | 1.6%    |
| 6.3.3   | 4         | 1.6%    |
| 6.2.0   | 4         | 1.6%    |
| 6.1.38  | 4         | 1.6%    |
| 6.1.31  | 4         | 1.6%    |
| 6.1.0   | 4         | 1.6%    |
| 6.0.10  | 4         | 1.6%    |
| 5.15.86 | 4         | 1.6%    |
| 5.15.43 | 4         | 1.6%    |
| 6.3.1   | 3         | 1.2%    |
| 6.1.55  | 3         | 1.2%    |
| 6.1.53  | 3         | 1.2%    |
| 6.1.42  | 3         | 1.2%    |
| 6.1.35  | 3         | 1.2%    |
| 6.0.11  | 3         | 1.2%    |
| 5.15.82 | 3         | 1.2%    |
| 5.15.72 | 3         | 1.2%    |
| 5.15.68 | 3         | 1.2%    |
| 5.15.47 | 3         | 1.2%    |
| 5.15.26 | 3         | 1.2%    |
| 6.5.2   | 2         | 0.8%    |
| 6.4.7   | 2         | 0.8%    |
| 6.4.6   | 2         | 0.8%    |
| 6.4.4   | 2         | 0.8%    |
| 6.2.9   | 2         | 0.8%    |
| 6.2.11  | 2         | 0.8%    |
| 6.1.47  | 2         | 0.8%    |
| 6.1.45  | 2         | 0.8%    |
| 6.1.41  | 2         | 0.8%    |
| 6.1.39  | 2         | 0.8%    |
| 6.1.37  | 2         | 0.8%    |
| 6.1.34  | 2         | 0.8%    |
| 6.1.27  | 2         | 0.8%    |
| 6.1.24  | 2         | 0.8%    |
| 6.1.1   | 2         | 0.8%    |
| 6.0.2   | 2         | 0.8%    |
| 5.8.1   | 2         | 0.8%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 61        | 25.74%  |
| 6.1     | 54        | 22.78%  |
| 5.10    | 14        | 5.91%   |
| 6.4     | 13        | 5.49%   |
| 6.3     | 13        | 5.49%   |
| 6.2     | 13        | 5.49%   |
| 6.0     | 13        | 5.49%   |
| 5.16    | 8         | 3.38%   |
| 5.4     | 7         | 2.95%   |
| 5.19    | 7         | 2.95%   |
| 5.8     | 6         | 2.53%   |
| 5.18    | 5         | 2.11%   |
| 5.13    | 4         | 1.69%   |
| 6.5     | 3         | 1.27%   |
| 5.7     | 3         | 1.27%   |
| 5.17    | 3         | 1.27%   |
| 5.12    | 3         | 1.27%   |
| 5.14    | 2         | 0.84%   |
| 5.11    | 2         | 0.84%   |
| 4.19    | 2         | 0.84%   |
| Unknown | 1         | 0.42%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 201       | 97.1%   |
| aarch64 | 5         | 2.42%   |
| i686    | 1         | 0.48%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 97        | 44.7%   |
| GNOME        | 29        | 13.36%  |
| sway         | 23        | 10.6%   |
| KDE5         | 21        | 9.68%   |
| Hyprland     | 10        | 4.61%   |
| KDE          | 9         | 4.15%   |
| XFCE         | 8         | 3.69%   |
| none+i3      | 7         | 3.23%   |
| none+awesome | 3         | 1.38%   |
| X-Generic    | 2         | 0.92%   |
| none+xmonad  | 2         | 0.92%   |
| xsession     | 1         | 0.46%   |
| X-Cinnamon   | 1         | 0.46%   |
| Pantheon     | 1         | 0.46%   |
| none+bspwm   | 1         | 0.46%   |
| MATE         | 1         | 0.46%   |
| Budgie       | 1         | 0.46%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 97        | 44.29%  |
| Wayland | 60        | 27.4%   |
| X11     | 45        | 20.55%  |
| Tty     | 17        | 7.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 116       | 55.24%  |
| GDM     | 33        | 15.71%  |
| SDDM    | 32        | 15.24%  |
| LightDM | 29        | 13.81%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 105       | 50.24%  |
| Unknown    | 60        | 28.71%  |
| en_GB      | 11        | 5.26%   |
| en_AU      | 5         | 2.39%   |
| en_DK      | 4         | 1.91%   |
| de_DE      | 4         | 1.91%   |
| ru_RU      | 3         | 1.44%   |
| fr_FR      | 3         | 1.44%   |
| pt_BR      | 2         | 0.96%   |
| it_IT      | 2         | 0.96%   |
| en_CA      | 2         | 0.96%   |
| de_CH      | 2         | 0.96%   |
| ro_RO      | 1         | 0.48%   |
| lv_LV      | 1         | 0.48%   |
| es_MX      | 1         | 0.48%   |
| en_NZ      | 1         | 0.48%   |
| en_IN      | 1         | 0.48%   |
| en_IE.UTF8 | 1         | 0.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 184       | 88.04%  |
| BIOS | 25        | 11.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 111       | 52.61%  |
| Btrfs   | 34        | 16.11%  |
| Tmpfs   | 22        | 10.43%  |
| Zfs     | 20        | 9.48%   |
| Xfs     | 17        | 8.06%   |
| Unknown | 6         | 2.84%   |
| Ext2    | 1         | 0.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 195       | 92.86%  |
| Unknown | 8         | 3.81%   |
| MBR     | 7         | 3.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 161       | 75.94%  |
| Yes       | 51        | 24.06%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 148       | 71.15%  |
| Yes       | 60        | 28.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 47        | 22.71%  |
| ASUSTek Computer                     | 41        | 19.81%  |
| Dell                                 | 26        | 12.56%  |
| Hewlett-Packard                      | 15        | 7.25%   |
| MSI                                  | 14        | 6.76%   |
| Gigabyte Technology                  | 12        | 5.8%    |
| Acer                                 | 8         | 3.86%   |
| Apple                                | 7         | 3.38%   |
| ASRock                               | 6         | 2.9%    |
| Pine Microsystems                    | 3         | 1.45%   |
| Intel                                | 3         | 1.45%   |
| GPD                                  | 3         | 1.45%   |
| Supermicro                           | 2         | 0.97%   |
| Raspberry Pi Foundation              | 2         | 0.97%   |
| MECHREVO                             | 2         | 0.97%   |
| Framework                            | 2         | 0.97%   |
| Toshiba                              | 1         | 0.48%   |
| Teclast                              | 1         | 0.48%   |
| System76                             | 1         | 0.48%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.48%   |
| OBSIDIAN-PC                          | 1         | 0.48%   |
| Microtech                            | 1         | 0.48%   |
| MACHENIKE                            | 1         | 0.48%   |
| HUAWEI                               | 1         | 0.48%   |
| Hardkernel                           | 1         | 0.48%   |
| EVGA                                 | 1         | 0.48%   |
| Blackview                            | 1         | 0.48%   |
| AZW                                  | 1         | 0.48%   |
| Avell High Performance               | 1         | 0.48%   |
| Alienware                            | 1         | 0.48%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Pine Microsystems Pine64 PinePhone (1.2)   | 3         | 1.45%   |
| Lenovo 13w Yoga 82S1                       | 3         | 1.45%   |
| ASUS All Series                            | 3         | 1.45%   |
| MSI MS-7C56                                | 2         | 0.97%   |
| MSI MS-7C37                                | 2         | 0.97%   |
| HP EliteBook 8470p                         | 2         | 0.97%   |
| Gigabyte B550I AORUS PRO AX                | 2         | 0.97%   |
| Gigabyte B450M DS3H                        | 2         | 0.97%   |
| Dell Latitude 7420                         | 2         | 0.97%   |
| ASUS Zenbook UX3402ZA_UX3402ZA             | 2         | 0.97%   |
| ASUS ROG STRIX B550-F GAMING               | 2         | 0.97%   |
| Apple MacBookPro11,5                       | 2         | 0.97%   |
| Apple MacBookPro11,3                       | 2         | 0.97%   |
| Apple iMac17,1                             | 2         | 0.97%   |
| Toshiba Satellite L50-B                    | 1         | 0.48%   |
| Teclast F5                                 | 1         | 0.48%   |
| System76 Pangolin                          | 1         | 0.48%   |
| Supermicro X8DT6                           | 1         | 0.48%   |
| Supermicro X10SLL-F                        | 1         | 0.48%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1         | 0.48%   |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 1         | 0.48%   |
| RPi Raspberry Pi 3 Model B+                | 1         | 0.48%   |
| OBSIDIAN-PC N13_N140ZU                     | 1         | 0.48%   |
| MSI MS-7C95                                | 1         | 0.48%   |
| MSI MS-7C91                                | 1         | 0.48%   |
| MSI MS-7C84                                | 1         | 0.48%   |
| MSI MS-7C35                                | 1         | 0.48%   |
| MSI MS-7B89                                | 1         | 0.48%   |
| MSI MS-7B09                                | 1         | 0.48%   |
| MSI MS-7758                                | 1         | 0.48%   |
| MSI MS-7681                                | 1         | 0.48%   |
| MSI Bravo 15 B5DD                          | 1         | 0.48%   |
| MSI Alpha 15 B5EEK                         | 1         | 0.48%   |
| Microtech CoreBook Lite                    | 1         | 0.48%   |
| MECHREVO WUJIE 14                          | 1         | 0.48%   |
| MECHREVO Code01 Ver2.0                     | 1         | 0.48%   |
| MACHENIKE F117-7P                          | 1         | 0.48%   |
| Lenovo Yoga Slim 7 13ACN5 82CY             | 1         | 0.48%   |
| Lenovo Yoga 520-14IKB 81C8                 | 1         | 0.48%   |
| Lenovo Yoga 14sARE 2020 82A8               | 1         | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 28        | 13.53%  |
| ASUS ROG                                   | 11        | 5.31%   |
| ASUS PRIME                                 | 8         | 3.86%   |
| Dell XPS                                   | 7         | 3.38%   |
| Dell Latitude                              | 7         | 3.38%   |
| Dell Inspiron                              | 6         | 2.9%    |
| ASUS Zenbook                               | 6         | 2.9%    |
| Lenovo Legion                              | 5         | 2.42%   |
| HP EliteBook                               | 5         | 2.42%   |
| Acer Aspire                                | 5         | 2.42%   |
| Lenovo IdeaPad                             | 4         | 1.93%   |
| Dell Precision                             | 4         | 1.93%   |
| Apple MacBookPro11                         | 4         | 1.93%   |
| Pine Microsystems Pine64                   | 3         | 1.45%   |
| Lenovo Yoga                                | 3         | 1.45%   |
| Lenovo 13w                                 | 3         | 1.45%   |
| Gigabyte B450M                             | 3         | 1.45%   |
| ASUS All                                   | 3         | 1.45%   |
| RPi Raspberry                              | 2         | 0.97%   |
| MSI MS-7C56                                | 2         | 0.97%   |
| MSI MS-7C37                                | 2         | 0.97%   |
| Lenovo IdeaPadFlex                         | 2         | 0.97%   |
| HP Spectre                                 | 2         | 0.97%   |
| HP ProBook                                 | 2         | 0.97%   |
| HP EliteDesk                               | 2         | 0.97%   |
| Gigabyte X570                              | 2         | 0.97%   |
| Gigabyte B550I                             | 2         | 0.97%   |
| Framework Laptop                           | 2         | 0.97%   |
| ASUS TUF                                   | 2         | 0.97%   |
| Apple iMac17                               | 2         | 0.97%   |
| Toshiba Satellite                          | 1         | 0.48%   |
| Teclast F5                                 | 1         | 0.48%   |
| System76 Pangolin                          | 1         | 0.48%   |
| Supermicro X8DT6                           | 1         | 0.48%   |
| Supermicro X10SLL-F                        | 1         | 0.48%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1         | 0.48%   |
| OBSIDIAN-PC N13                            | 1         | 0.48%   |
| MSI MS-7C95                                | 1         | 0.48%   |
| MSI MS-7C91                                | 1         | 0.48%   |
| MSI MS-7C84                                | 1         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 35        | 16.91%  |
| 2022    | 26        | 12.56%  |
| 2019    | 24        | 11.59%  |
| 2021    | 21        | 10.14%  |
| 2018    | 20        | 9.66%   |
| 2016    | 14        | 6.76%   |
| 2017    | 12        | 5.8%    |
| 2013    | 10        | 4.83%   |
| 2012    | 10        | 4.83%   |
| 2015    | 9         | 4.35%   |
| 2014    | 8         | 3.86%   |
| 2023    | 6         | 2.9%    |
| Unknown | 5         | 2.42%   |
| 2011    | 4         | 1.93%   |
| 2010    | 1         | 0.48%   |
| 2009    | 1         | 0.48%   |
| 2008    | 1         | 0.48%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 108       | 52.17%  |
| Desktop        | 68        | 32.85%  |
| Convertible    | 17        | 8.21%   |
| Phone          | 3         | 1.45%   |
| All in one     | 3         | 1.45%   |
| Server         | 3         | 1.45%   |
| System on chip | 2         | 0.97%   |
| Mini pc        | 2         | 0.97%   |
| Tablet         | 1         | 0.48%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 205       | 98.09%  |
| Enabled  | 4         | 1.91%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 206       | 99.52%  |
| Yes  | 1         | 0.48%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 52        | 24.76%  |
| 32.01-64.0      | 49        | 23.33%  |
| 8.01-16.0       | 33        | 15.71%  |
| 4.01-8.0        | 26        | 12.38%  |
| 64.01-256.0     | 26        | 12.38%  |
| 24.01-32.0      | 11        | 5.24%   |
| 3.01-4.0        | 9         | 4.29%   |
| 0.51-1.0        | 2         | 0.95%   |
| More than 256.0 | 1         | 0.48%   |
| 1.01-2.0        | 1         | 0.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 61        | 26.52%  |
| 8.01-16.0   | 39        | 16.96%  |
| 3.01-4.0    | 35        | 15.22%  |
| 2.01-3.0    | 30        | 13.04%  |
| 1.01-2.0    | 27        | 11.74%  |
| 0.51-1.0    | 10        | 4.35%   |
| 16.01-24.0  | 9         | 3.91%   |
| 32.01-64.0  | 8         | 3.48%   |
| 24.01-32.0  | 7         | 3.04%   |
| 0.01-0.5    | 3         | 1.3%    |
| 64.01-256.0 | 1         | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 122       | 56.74%  |
| 2      | 57        | 26.51%  |
| 3      | 16        | 7.44%   |
| 5      | 5         | 2.33%   |
| 6      | 4         | 1.86%   |
| 4      | 4         | 1.86%   |
| 7      | 2         | 0.93%   |
| 23     | 1         | 0.47%   |
| 17     | 1         | 0.47%   |
| 11     | 1         | 0.47%   |
| 8      | 1         | 0.47%   |
| 0      | 1         | 0.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 183       | 87.98%  |
| Yes       | 25        | 12.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 156       | 74.29%  |
| No        | 54        | 25.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 163       | 77.99%  |
| No        | 46        | 22.01%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 155       | 73.81%  |
| No        | 55        | 26.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 42        | 20.29%  |
| Germany      | 23        | 11.11%  |
| UK           | 16        | 7.73%   |
| France       | 12        | 5.8%    |
| Russia       | 11        | 5.31%   |
| Italy        | 11        | 5.31%   |
| Poland       | 8         | 3.86%   |
| Ukraine      | 7         | 3.38%   |
| Canada       | 7         | 3.38%   |
| Austria      | 5         | 2.42%   |
| Australia    | 5         | 2.42%   |
| Switzerland  | 4         | 1.93%   |
| Norway       | 4         | 1.93%   |
| Netherlands  | 4         | 1.93%   |
| Czechia      | 4         | 1.93%   |
| Brazil       | 4         | 1.93%   |
| India        | 3         | 1.45%   |
| Denmark      | 3         | 1.45%   |
| Belgium      | 3         | 1.45%   |
| Sweden       | 2         | 0.97%   |
| Slovenia     | 2         | 0.97%   |
| Serbia       | 2         | 0.97%   |
| New Zealand  | 2         | 0.97%   |
| Japan        | 2         | 0.97%   |
| Iraq         | 2         | 0.97%   |
| Hungary      | 2         | 0.97%   |
| Uruguay      | 1         | 0.48%   |
| Taiwan       | 1         | 0.48%   |
| Spain        | 1         | 0.48%   |
| South Africa | 1         | 0.48%   |
| Singapore    | 1         | 0.48%   |
| Romania      | 1         | 0.48%   |
| Portugal     | 1         | 0.48%   |
| Peru         | 1         | 0.48%   |
| Mexico       | 1         | 0.48%   |
| Latvia       | 1         | 0.48%   |
| Kyrgyzstan   | 1         | 0.48%   |
| Kuwait       | 1         | 0.48%   |
| Ireland      | 1         | 0.48%   |
| Iran         | 1         | 0.48%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Kharkiv           | 5         | 2.26%   |
| Vienna            | 4         | 1.81%   |
| Milwaukee         | 4         | 1.81%   |
| Marki             | 4         | 1.81%   |
| Frankfurt am Main | 4         | 1.81%   |
| Plymouth          | 3         | 1.36%   |
| Perth             | 3         | 1.36%   |
| Oslo              | 3         | 1.36%   |
| Lyon              | 3         | 1.36%   |
| London            | 3         | 1.36%   |
| Cerami            | 3         | 1.36%   |
| Southampton       | 2         | 0.9%    |
| South Deerfield   | 2         | 0.9%    |
| Schaafheim        | 2         | 0.9%    |
| Rochester         | 2         | 0.9%    |
| Richardson        | 2         | 0.9%    |
| Prague            | 2         | 0.9%    |
| Phoenix           | 2         | 0.9%    |
| Ottawa            | 2         | 0.9%    |
| Melbourne         | 2         | 0.9%    |
| Los Angeles       | 2         | 0.9%    |
| Krasnodar         | 2         | 0.9%    |
| Hamburg           | 2         | 0.9%    |
| Halifax           | 2         | 0.9%    |
| Gdansk            | 2         | 0.9%    |
| Darmstadt         | 2         | 0.9%    |
| Craigsville       | 2         | 0.9%    |
| Chelyabinsk       | 2         | 0.9%    |
| Catania           | 2         | 0.9%    |
| Cambridge         | 2         | 0.9%    |
| Berlin            | 2         | 0.9%    |
| Belgrade          | 2         | 0.9%    |
| Baghdad           | 2         | 0.9%    |
| Austin            | 2         | 0.9%    |
| Amsterdam         | 2         | 0.9%    |
| Zurich            | 1         | 0.45%   |
| Yangzhou          | 1         | 0.45%   |
| Woodford          | 1         | 0.45%   |
| Woldegk           | 1         | 0.45%   |
| Wellington        | 1         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 82        | 149    | 26.62%  |
| SanDisk                        | 26        | 32     | 8.44%   |
| WDC                            | 25        | 47     | 8.12%   |
| Seagate                        | 19        | 52     | 6.17%   |
| Toshiba                        | 18        | 34     | 5.84%   |
| Crucial                        | 14        | 21     | 4.55%   |
| Kingston                       | 13        | 14     | 4.22%   |
| Intel                          | 13        | 20     | 4.22%   |
| Micron Technology              | 12        | 13     | 3.9%    |
| Unknown                        | 10        | 14     | 3.25%   |
| SK hynix                       | 8         | 11     | 2.6%    |
| Apple                          | 7         | 11     | 2.27%   |
| HGST                           | 5         | 15     | 1.62%   |
| Yangtze Memory Technologies    | 3         | 4      | 0.97%   |
| Phison Electronics             | 3         | 6      | 0.97%   |
| KIOXIA                         | 3         | 5      | 0.97%   |
| Kingston Technology Company    | 3         | 3      | 0.97%   |
| Hitachi                        | 3         | 6      | 0.97%   |
| Corsair                        | 3         | 3      | 0.97%   |
| Transcend                      | 2         | 2      | 0.65%   |
| SPCC                           | 2         | 2      | 0.65%   |
| Realtek Semiconductor          | 2         | 5      | 0.65%   |
| Plextor                        | 2         | 2      | 0.65%   |
| OCZ                            | 2         | 2      | 0.65%   |
| Micron/Crucial Technology      | 2         | 2      | 0.65%   |
| MAXIO Technology (Hangzhou)    | 2         | 3      | 0.65%   |
| China                          | 2         | 2      | 0.65%   |
| ADATA Technology               | 2         | 4      | 0.65%   |
| A-DATA Technology              | 2         | 2      | 0.65%   |
| ZHITAI                         | 1         | 1      | 0.32%   |
| Teclast                        | 1         | 3      | 0.32%   |
| Solid State Storage Technology | 1         | 1      | 0.32%   |
| Silicon Motion                 | 1         | 1      | 0.32%   |
| S3+                            | 1         | 1      | 0.32%   |
| PNY                            | 1         | 2      | 0.32%   |
| Phison                         | 1         | 1      | 0.32%   |
| MBED                           | 1         | 1      | 0.32%   |
| LITEONIT                       | 1         | 1      | 0.32%   |
| LITEON                         | 1         | 1      | 0.32%   |
| Lexar                          | 1         | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 12        | 3.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 10        | 2.77%   |
| Samsung SSD 860 EVO 500GB                           | 5         | 1.39%   |
| Samsung SSD 860 EVO 1TB                             | 5         | 1.39%   |
| Unknown MMC Card  32GB                              | 4         | 1.11%   |
| SanDisk SSD PLUS 240GB                              | 4         | 1.11%   |
| Samsung SSD 860 QVO 1TB                             | 4         | 1.11%   |
| Seagate ST3000DM001-1ER166 3TB                      | 3         | 0.83%   |
| Samsung SSD 970 EVO Plus 2TB                        | 3         | 0.83%   |
| Samsung SSD 970 EVO Plus 1TB                        | 3         | 0.83%   |
| Samsung SSD 970 EVO 500GB                           | 3         | 0.83%   |
| Samsung SSD 870 EVO 500GB                           | 3         | 0.83%   |
| Micron MTFDKCD512TFK 512GB                          | 3         | 0.83%   |
| Intel SSDPEKNU010TZ 1024GB                          | 3         | 0.83%   |
| Crucial CT1000MX500SSD1 1TB                         | 3         | 0.83%   |
| Unknown MMC Card  16GB                              | 2         | 0.55%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                | 2         | 0.55%   |
| SK hynix PC801 NVMe 512GB                           | 2         | 0.55%   |
| Seagate ST4000DM004-2CV104 4TB                      | 2         | 0.55%   |
| Seagate ST3000DM001-1CH166 3TB                      | 2         | 0.55%   |
| Sandisk WD Black SN850 1TB                          | 2         | 0.55%   |
| SanDisk Ultra II 240GB SSD                          | 2         | 0.55%   |
| SanDisk NVMe SSD Drive 1TB                          | 2         | 0.55%   |
| Samsung SSD 980 PRO 1TB                             | 2         | 0.55%   |
| Samsung SSD 980 1TB                                 | 2         | 0.55%   |
| Samsung SSD 970 EVO 1TB                             | 2         | 0.55%   |
| Samsung SSD 870 EVO 1TB                             | 2         | 0.55%   |
| Samsung SSD 860 EVO 2TB                             | 2         | 0.55%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 0.55%   |
| Samsung SSD 850 EVO 500GB                           | 2         | 0.55%   |
| Samsung SSD 840 EVO 250GB                           | 2         | 0.55%   |
| Samsung PM9A1 NVMe 1024GB                           | 2         | 0.55%   |
| Samsung NVMe SSD Drive 1TB                          | 2         | 0.55%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB | 2         | 0.55%   |
| Kingston SA400S37960G 960GB SSD                     | 2         | 0.55%   |
| Kingston OM8PCP3512F-AI1 512GB                      | 2         | 0.55%   |
| HGST HTS721010A9E630 1TB                            | 2         | 0.55%   |
| Crucial CT250MX500SSD1 250GB                        | 2         | 0.55%   |
| Apple SSD SM0512G 500GB                             | 2         | 0.55%   |
| Apple SSD SM0128G 121GB                             | 2         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 52     | 30.65%  |
| WDC                 | 18        | 38     | 29.03%  |
| Toshiba             | 12        | 25     | 19.35%  |
| HGST                | 5         | 15     | 8.06%   |
| Hitachi             | 3         | 6      | 4.84%   |
| Apple               | 3         | 3      | 4.84%   |
| Samsung Electronics | 2         | 2      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 34        | 71     | 31.19%  |
| Crucial             | 13        | 20     | 11.93%  |
| SanDisk             | 12        | 17     | 11.01%  |
| Kingston            | 9         | 9      | 8.26%   |
| Apple               | 6         | 8      | 5.5%    |
| Intel               | 5         | 7      | 4.59%   |
| WDC                 | 3         | 4      | 2.75%   |
| Corsair             | 3         | 3      | 2.75%   |
| Transcend           | 2         | 2      | 1.83%   |
| SPCC                | 2         | 2      | 1.83%   |
| OCZ                 | 2         | 2      | 1.83%   |
| Micron Technology   | 2         | 2      | 1.83%   |
| China               | 2         | 2      | 1.83%   |
| ZHITAI              | 1         | 1      | 0.92%   |
| Toshiba             | 1         | 1      | 0.92%   |
| Teclast             | 1         | 3      | 0.92%   |
| SK hynix            | 1         | 1      | 0.92%   |
| S3+                 | 1         | 1      | 0.92%   |
| PNY                 | 1         | 2      | 0.92%   |
| Plextor             | 1         | 1      | 0.92%   |
| LITEONIT            | 1         | 1      | 0.92%   |
| LITEON              | 1         | 1      | 0.92%   |
| INNOVATION IT       | 1         | 1      | 0.92%   |
| Dogfish             | 1         | 1      | 0.92%   |
| BIWIN               | 1         | 1      | 0.92%   |
| ASMT                | 1         | 1      | 0.92%   |
| ASMedia             | 1         | 1      | 0.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 129       | 184    | 46.24%  |
| SSD     | 94        | 166    | 33.69%  |
| HDD     | 45        | 141    | 16.13%  |
| MMC     | 10        | 15     | 3.58%   |
| Unknown | 1         | 1      | 0.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 129       | 184    | 51.19%  |
| SATA | 106       | 298    | 42.06%  |
| MMC  | 10        | 15     | 3.97%   |
| SAS  | 7         | 10     | 2.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 75        | 129    | 48.7%   |
| 0.51-1.0   | 45        | 72     | 29.22%  |
| 1.01-2.0   | 13        | 18     | 8.44%   |
| 4.01-10.0  | 10        | 54     | 6.49%   |
| 2.01-3.0   | 7         | 13     | 4.55%   |
| 3.01-4.0   | 3         | 15     | 1.95%   |
| 10.01-20.0 | 1         | 6      | 0.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 66        | 30.99%  |
| 1-20           | 50        | 23.47%  |
| 251-500        | 21        | 9.86%   |
| 101-250        | 21        | 9.86%   |
| 501-1000       | 19        | 8.92%   |
| 1001-2000      | 13        | 6.1%    |
| More than 3000 | 12        | 5.63%   |
| 2001-3000      | 9         | 4.23%   |
| 21-50          | 2         | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 66        | 30.14%  |
| 1-20           | 65        | 29.68%  |
| 101-250        | 21        | 9.59%   |
| 21-50          | 16        | 7.31%   |
| 51-100         | 16        | 7.31%   |
| 501-1000       | 14        | 6.39%   |
| 251-500        | 8         | 3.65%   |
| 1001-2000      | 6         | 2.74%   |
| More than 3000 | 5         | 2.28%   |
| 2001-3000      | 2         | 0.91%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                          | Computers | Drives | Percent |
|----------------------------------------------------------------|-----------|--------|---------|
| SanDisk SSD PLUS 240GB                                         | 2         | 4      | 8.33%   |
| WDC WD30EZRX-00SPEB0 3TB                                       | 1         | 1      | 4.17%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                       | 1         | 1      | 4.17%   |
| WDC WD20EARX-008FB0 2TB                                        | 1         | 1      | 4.17%   |
| WDC WD10EZEX-60ZF5A0 1TB                                       | 1         | 1      | 4.17%   |
| WDC WD10 JPLX-00MBPT0 1TB                                      | 1         | 1      | 4.17%   |
| Toshiba MQ01ABD100 1TB                                         | 1         | 1      | 4.17%   |
| Toshiba MK2565GSXV 250GB                                       | 1         | 1      | 4.17%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                           | 1         | 1      | 4.17%   |
| Seagate ST8000VN004-2M2101 8TB                                 | 1         | 3      | 4.17%   |
| Seagate ST8000VN0022-2EL112 8TB                                | 1         | 1      | 4.17%   |
| Seagate ST3500418AS 500GB                                      | 1         | 1      | 4.17%   |
| Samsung Electronics SSD 970 EVO 1TB                            | 1         | 1      | 4.17%   |
| Samsung Electronics SSD 870 EVO 1TB                            | 1         | 1      | 4.17%   |
| Samsung Electronics NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 1         | 1      | 4.17%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD                 | 1         | 1      | 4.17%   |
| Intel SSDSC2BW240A4 240GB                                      | 1         | 1      | 4.17%   |
| Hitachi HDS722020ALA330 2TB                                    | 1         | 1      | 4.17%   |
| HGST HTS545050A7E680 500GB                                     | 1         | 1      | 4.17%   |
| Crucial CT240M500SSD1 240GB                                    | 1         | 1      | 4.17%   |
| Corsair Neutron XT SSD 240GB                                   | 1         | 1      | 4.17%   |
| Corsair Force GS 240GB SSD                                     | 1         | 1      | 4.17%   |
| ASMT 2115 250GB                                                | 1         | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 20.83%  |
| Seagate             | 3         | 5      | 12.5%   |
| Samsung Electronics | 3         | 3      | 12.5%   |
| Toshiba             | 2         | 2      | 8.33%   |
| SanDisk             | 2         | 4      | 8.33%   |
| Corsair             | 2         | 2      | 8.33%   |
| SK hynix            | 1         | 1      | 4.17%   |
| Micron Technology   | 1         | 1      | 4.17%   |
| Intel               | 1         | 1      | 4.17%   |
| Hitachi             | 1         | 1      | 4.17%   |
| HGST                | 1         | 1      | 4.17%   |
| Crucial             | 1         | 1      | 4.17%   |
| ASMT                | 1         | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 41.67%  |
| Seagate | 3         | 5      | 25%     |
| Toshiba | 2         | 2      | 16.67%  |
| Hitachi | 1         | 1      | 8.33%   |
| HGST    | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 14     | 47.83%  |
| SSD  | 9         | 11     | 39.13%  |
| NVMe | 3         | 3      | 13.04%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MG03ACA300 3TB                           | 1         | 1      | 33.33%  |
| Toshiba HDWG180 8TB                              | 1         | 4      | 33.33%  |
| Samsung Electronics MZNLN256HCHP-000L7 256GB SSD | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 5      | 66.67%  |
| Samsung Electronics | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 195       | 431    | 81.25%  |
| Detected | 24        | 42     | 10%     |
| Malfunc  | 18        | 28     | 7.5%    |
| Failed   | 3         | 6      | 1.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 105       | 35.23%  |
| Samsung Electronics            | 60        | 20.13%  |
| AMD                            | 43        | 14.43%  |
| SanDisk                        | 19        | 6.38%   |
| Micron Technology              | 10        | 3.36%   |
| SK hynix                       | 7         | 2.35%   |
| Kingston Technology Company    | 7         | 2.35%   |
| ASMedia Technology             | 7         | 2.35%   |
| Toshiba America Info Systems   | 6         | 2.01%   |
| Phison Electronics             | 4         | 1.34%   |
| ADATA Technology               | 4         | 1.34%   |
| Yangtze Memory Technologies    | 3         | 1.01%   |
| Micron/Crucial Technology      | 3         | 1.01%   |
| LSI Logic / Symbios Logic      | 3         | 1.01%   |
| KIOXIA                         | 3         | 1.01%   |
| Broadcom / LSI                 | 3         | 1.01%   |
| Realtek Semiconductor          | 2         | 0.67%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.67%   |
| Marvell Technology Group       | 2         | 0.67%   |
| Solid State Storage Technology | 1         | 0.34%   |
| Silicon Motion                 | 1         | 0.34%   |
| Shenzhen Longsys Electronics   | 1         | 0.34%   |
| Lite-On Technology             | 1         | 0.34%   |
| Biwin Storage Technology       | 1         | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 29        | 9.03%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 28        | 8.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 17        | 5.3%    |
| AMD 500 Series Chipset SATA Controller                                         | 12        | 3.74%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 11        | 3.43%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 3.12%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 7         | 2.18%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 7         | 2.18%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 6         | 1.87%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 1.87%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 1.87%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 1.87%   |
| AMD 400 Series Chipset SATA Controller                                         | 6         | 1.87%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 1.56%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 1.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 1.56%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 4         | 1.25%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 4         | 1.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 1.25%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 4         | 1.25%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 1.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 1.25%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 0.93%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 0.93%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.93%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.93%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 3         | 0.93%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 0.93%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 0.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 0.93%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 0.93%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 0.93%   |
| Yangtze Memory ZHITAI TiPlus7100                                               | 2         | 0.62%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 2         | 0.62%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.62%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 0.62%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 2         | 0.62%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 2         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 129       | 45.1%   |
| SATA | 126       | 44.06%  |
| RAID | 20        | 6.99%   |
| SAS  | 6         | 2.1%    |
| IDE  | 5         | 1.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 133       | 64.25%  |
| AMD    | 69        | 33.33%  |
| ARM    | 5         | 2.42%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz          | 5         | 2.42%   |
| ARM Processor                              | 5         | 2.42%   |
| AMD Ryzen 5 3600 6-Core Processor          | 5         | 2.42%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 4         | 1.93%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 4         | 1.93%   |
| Intel 12th Gen Core i7-1260P               | 4         | 1.93%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 4         | 1.93%   |
| AMD Ryzen 9 5950X 16-Core Processor        | 4         | 1.93%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 4         | 1.93%   |
| AMD Ryzen 5 5625U with Radeon Graphics     | 4         | 1.93%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 3         | 1.45%   |
| Intel Celeron N4100 CPU @ 1.10GHz          | 3         | 1.45%   |
| Intel 12th Gen Core i5-1240P               | 3         | 1.45%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 3         | 1.45%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz    | 3         | 1.45%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 3         | 1.45%   |
| AMD Ryzen 7 3800X 8-Core Processor         | 3         | 1.45%   |
| AMD Ryzen 5 5600G with Radeon Graphics     | 3         | 1.45%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 0.97%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 2         | 0.97%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 2         | 0.97%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 0.97%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 2         | 0.97%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 2         | 0.97%   |
| Intel Core i7-5500U CPU @ 2.40GHz          | 2         | 0.97%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz         | 2         | 0.97%   |
| Intel Core i7-4770 CPU @ 3.40GHz           | 2         | 0.97%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz         | 2         | 0.97%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 2         | 0.97%   |
| Intel Core i5-8350U CPU @ 1.70GHz          | 2         | 0.97%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 2         | 0.97%   |
| Intel Core i5-3470 CPU @ 3.20GHz           | 2         | 0.97%   |
| Intel 12th Gen Core i7-1255U               | 2         | 0.97%   |
| AMD Ryzen 9 5900X 12-Core Processor        | 2         | 0.97%   |
| AMD Ryzen 9 5900HX with Radeon Graphics    | 2         | 0.97%   |
| AMD Ryzen 7 6800H with Radeon Graphics     | 2         | 0.97%   |
| AMD Ryzen 5 5600X 6-Core Processor         | 2         | 0.97%   |
| AMD Ryzen 5 3600X 6-Core Processor         | 2         | 0.97%   |
| AMD Ryzen 5 1600 Six-Core Processor        | 2         | 0.97%   |
| Intel Xeon W-1290P CPU @ 3.70GHz           | 1         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 51        | 24.64%  |
| Other                  | 34        | 16.43%  |
| Intel Core i5          | 30        | 14.49%  |
| AMD Ryzen 7            | 24        | 11.59%  |
| AMD Ryzen 5            | 22        | 10.63%  |
| AMD Ryzen 9            | 14        | 6.76%   |
| Intel Xeon             | 7         | 3.38%   |
| Intel Celeron          | 6         | 2.9%    |
| Intel Core i3          | 5         | 2.42%   |
| AMD Ryzen 7 PRO        | 5         | 2.42%   |
| AMD Ryzen Threadripper | 3         | 1.45%   |
| Intel Core i9          | 2         | 0.97%   |
| Intel Pentium Gold     | 1         | 0.48%   |
| Intel Core m3          | 1         | 0.48%   |
| Intel Atom             | 1         | 0.48%   |
| AMD FX                 | 1         | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 65        | 31.4%   |
| 8       | 40        | 19.32%  |
| 2       | 33        | 15.94%  |
| 6       | 32        | 15.46%  |
| 12      | 13        | 6.28%   |
| 16      | 7         | 3.38%   |
| Unknown | 5         | 2.42%   |
| 24      | 4         | 1.93%   |
| 10      | 4         | 1.93%   |
| 14      | 2         | 0.97%   |
| 32      | 1         | 0.48%   |
| 1       | 1         | 0.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 200       | 96.62%  |
| Unknown | 5         | 2.42%   |
| 2       | 2         | 0.97%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 183       | 88.41%  |
| 1       | 19        | 9.18%   |
| Unknown | 5         | 2.42%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 206       | 99.04%  |
| 32-bit         | 1         | 0.48%   |
| Unknown        | 1         | 0.48%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 51        | 23.61%  |
| 0x0a50000c | 12        | 5.56%   |
| 0x306c3    | 11        | 5.09%   |
| 0x306a9    | 9         | 4.17%   |
| 0x806ea    | 8         | 3.7%    |
| 0x806c1    | 8         | 3.7%    |
| 0x0a50000d | 7         | 3.24%   |
| 0x08701021 | 7         | 3.24%   |
| 0x906ea    | 6         | 2.78%   |
| 0x506e3    | 5         | 2.31%   |
| 0x0a404102 | 5         | 2.31%   |
| 0x08600106 | 5         | 2.31%   |
| 0x806ec    | 4         | 1.85%   |
| 0x806eb    | 4         | 1.85%   |
| 0x806e9    | 4         | 1.85%   |
| 0x406e3    | 4         | 1.85%   |
| 0x306d4    | 4         | 1.85%   |
| 0x08701013 | 4         | 1.85%   |
| 0x906e9    | 3         | 1.39%   |
| 0x906a3    | 3         | 1.39%   |
| 0x706a1    | 3         | 1.39%   |
| 0x40661    | 3         | 1.39%   |
| 0x40651    | 3         | 1.39%   |
| 0xa0653    | 2         | 0.93%   |
| 0x906ed    | 2         | 0.93%   |
| 0x906a4    | 2         | 0.93%   |
| 0x706a8    | 2         | 0.93%   |
| 0x0a601203 | 2         | 0.93%   |
| 0x0a201204 | 2         | 0.93%   |
| 0x0a201025 | 2         | 0.93%   |
| 0x0a201016 | 2         | 0.93%   |
| 0x0a201009 | 2         | 0.93%   |
| 0x08600104 | 2         | 0.93%   |
| 0x08108109 | 2         | 0.93%   |
| 0x08001138 | 2         | 0.93%   |
| 0xa0652    | 1         | 0.46%   |
| 0x90672    | 1         | 0.46%   |
| 0x806d1    | 1         | 0.46%   |
| 0x406f1    | 1         | 0.46%   |
| 0x306f2    | 1         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 37        | 17.87%  |
| Zen 3            | 29        | 14.01%  |
| Zen 2            | 21        | 10.14%  |
| Haswell          | 19        | 9.18%   |
| Unknown          | 19        | 9.18%   |
| Skylake          | 15        | 7.25%   |
| Alderlake Hybrid | 14        | 6.76%   |
| IvyBridge        | 12        | 5.8%    |
| TigerLake        | 10        | 4.83%   |
| Goldmont plus    | 6         | 2.9%    |
| Broadwell        | 5         | 2.42%   |
| Zen+             | 4         | 1.93%   |
| Zen              | 4         | 1.93%   |
| CometLake        | 4         | 1.93%   |
| Westmere         | 2         | 0.97%   |
| Icelake          | 2         | 0.97%   |
| SandyBridge      | 1         | 0.48%   |
| Piledriver       | 1         | 0.48%   |
| Gracemont        | 1         | 0.48%   |
| Bonnell          | 1         | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 107       | 42.46%  |
| Nvidia                     | 74        | 29.37%  |
| AMD                        | 68        | 26.98%  |
| Matrox Electronics Systems | 2         | 0.79%   |
| ASPEED Technology          | 1         | 0.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 14        | 5.45%   |
| Intel UHD Graphics 620                                                                | 9         | 3.5%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 8         | 3.11%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 8         | 3.11%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 8         | 3.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 7         | 2.72%   |
| AMD Renoir                                                                            | 7         | 2.72%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 6         | 2.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 6         | 2.33%   |
| AMD Rembrandt [Radeon 680M]                                                           | 6         | 2.33%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                               | 6         | 2.33%   |
| Intel HD Graphics 620                                                                 | 5         | 1.95%   |
| Intel HD Graphics 530                                                                 | 5         | 1.95%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 5         | 1.95%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 5         | 1.95%   |
| AMD Barcelo                                                                           | 5         | 1.95%   |
| Nvidia GP108M [GeForce MX150]                                                         | 4         | 1.56%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 4         | 1.56%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 1.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 4         | 1.56%   |
| Nvidia TU106 [GeForce RTX 2070]                                                       | 3         | 1.17%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 1.17%   |
| Nvidia GK104 [GeForce GTX 760]                                                        | 3         | 1.17%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 1.17%   |
| Intel HD Graphics 630                                                                 | 3         | 1.17%   |
| Intel HD Graphics 5500                                                                | 3         | 1.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 3         | 1.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 3         | 1.17%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 1.17%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                         | 3         | 1.17%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 2         | 0.78%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                 | 2         | 0.78%   |
| Nvidia GP108 [GeForce GT 1030]                                                        | 2         | 0.78%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 2         | 0.78%   |
| Nvidia GP104 [GeForce GTX 1070]                                                       | 2         | 0.78%   |
| Nvidia GM204 [GeForce GTX 970]                                                        | 2         | 0.78%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 0.78%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                           | 2         | 0.78%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                         | 2         | 0.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 2         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 68        | 32.69%  |
| 1 x AMD        | 46        | 22.12%  |
| Intel + Nvidia | 32        | 15.38%  |
| 1 x Nvidia     | 30        | 14.42%  |
| AMD + Nvidia   | 12        | 5.77%   |
| Other          | 6         | 2.88%   |
| Intel + AMD    | 5         | 2.4%    |
| 2 x AMD        | 4         | 1.92%   |
| 1 x Matrox     | 2         | 0.96%   |
| 2 x Intel      | 1         | 0.48%   |
| 1 x ASPEED     | 1         | 0.48%   |
| AMD + ASPEED   | 1         | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 149       | 71.63%  |
| Proprietary | 49        | 23.56%  |
| Unknown     | 10        | 4.81%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 135       | 63.68%  |
| 0.01-0.5   | 23        | 10.85%  |
| 7.01-8.0   | 16        | 7.55%   |
| 1.01-2.0   | 16        | 7.55%   |
| 3.01-4.0   | 12        | 5.66%   |
| 8.01-16.0  | 5         | 2.36%   |
| 0.51-1.0   | 4         | 1.89%   |
| 16.01-24.0 | 1         | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Dell                 | 27        | 12%     |
| AU Optronics         | 27        | 12%     |
| Samsung Electronics  | 23        | 10.22%  |
| BOE                  | 22        | 9.78%   |
| LG Display           | 15        | 6.67%   |
| Goldstar             | 14        | 6.22%   |
| Chimei Innolux       | 14        | 6.22%   |
| Acer                 | 9         | 4%      |
| Sharp                | 7         | 3.11%   |
| Apple                | 7         | 3.11%   |
| PANDA                | 6         | 2.67%   |
| Hewlett-Packard      | 5         | 2.22%   |
| CSO                  | 5         | 2.22%   |
| Ancor Communications | 5         | 2.22%   |
| Philips              | 4         | 1.78%   |
| Iiyama               | 4         | 1.78%   |
| AOC                  | 4         | 1.78%   |
| ViewSonic            | 2         | 0.89%   |
| Panasonic            | 2         | 0.89%   |
| Lenovo               | 2         | 0.89%   |
| InfoVision           | 2         | 0.89%   |
| HannStar             | 2         | 0.89%   |
| Eizo                 | 2         | 0.89%   |
| BenQ                 | 2         | 0.89%   |
| WST                  | 1         | 0.44%   |
| Vizio                | 1         | 0.44%   |
| Unknown (AAA)        | 1         | 0.44%   |
| Toshiba              | 1         | 0.44%   |
| TMX                  | 1         | 0.44%   |
| RTK                  | 1         | 0.44%   |
| NEC Computers        | 1         | 0.44%   |
| MSI                  | 1         | 0.44%   |
| MPI                  | 1         | 0.44%   |
| JDI                  | 1         | 0.44%   |
| HVR                  | 1         | 0.44%   |
| Gigabyte Technology  | 1         | 0.44%   |
| ASUSTek Computer     | 1         | 0.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 4         | 1.74%   |
| AU Optronics LCD Monitor AUO019C 1920x1200 286x178mm 13.3-inch        | 3         | 1.3%    |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 2         | 0.87%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.87%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 2         | 0.87%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2         | 0.87%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                     | 2         | 0.87%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 2         | 0.87%   |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                     | 2         | 0.87%   |
| Dell S3220DGF DELD0F4 2560x1440 697x392mm 31.5-inch                   | 2         | 0.87%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                     | 2         | 0.87%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch        | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO103D 1920x1080 310x170mm 13.9-inch        | 2         | 0.87%   |
| Apple iMac APPAE05 3840x2160 597x336mm 27.0-inch                      | 2         | 0.87%   |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                  | 2         | 0.87%   |
| WST KL.1350W.005 WST2C34 2256x1504 285x190mm 13.5-inch                | 1         | 0.43%   |
| Vizio E500i-A1 VIZ1004 1920x1080 1095x616mm 49.5-inch                 | 1         | 0.43%   |
| ViewSonic VX2758-SERIES VSCA738 2560x1440 598x336mm 27.0-inch         | 1         | 0.43%   |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch         | 1         | 0.43%   |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch           | 1         | 0.43%   |
| Toshiba no-audio-HD TSB8888 1080x1920 1080x1920mm 86.7-inch           | 1         | 0.43%   |
| TMX TL140ADXP24-0 TMX2004 2880x1800 300x190mm 14.0-inch               | 1         | 0.43%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 1         | 0.43%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.43%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.43%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.43%   |
| Sharp LCD Monitor SHP1479 1920x1280 259x173mm 12.3-inch               | 1         | 0.43%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.43%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch               | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 1         | 0.43%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1         | 0.43%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 1         | 0.43%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SDC4160 3000x2000 285x190mm 13.5-inch | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SDC4152 2880x1800 302x189mm 14.0-inch | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 85        | 39.72%  |
| 3840x2160 (4K)     | 32        | 14.95%  |
| 2560x1440 (QHD)    | 21        | 9.81%   |
| 1366x768 (WXGA)    | 13        | 6.07%   |
| 2880x1800          | 12        | 5.61%   |
| 1920x1200 (WUXGA)  | 10        | 4.67%   |
| 2560x1600          | 8         | 3.74%   |
| 1280x1024 (SXGA)   | 7         | 3.27%   |
| 3440x1440          | 4         | 1.87%   |
| 2560x1080          | 4         | 1.87%   |
| 1600x900 (HD+)     | 4         | 1.87%   |
| 2256x1504          | 3         | 1.4%    |
| 1680x1050 (WSXGA+) | 2         | 0.93%   |
| 3840x2400          | 1         | 0.47%   |
| 3840x1200          | 1         | 0.47%   |
| 3000x2000          | 1         | 0.47%   |
| 2160x1200          | 1         | 0.47%   |
| 1920x1280          | 1         | 0.47%   |
| 1440x900 (WXGA+)   | 1         | 0.47%   |
| 1280x800 (WXGA)    | 1         | 0.47%   |
| 1280x720 (HD)      | 1         | 0.47%   |
| 1024x600           | 1         | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 38        | 17.27%  |
| 14      | 35        | 15.91%  |
| 13      | 27        | 12.27%  |
| 27      | 25        | 11.36%  |
| 24      | 19        | 8.64%   |
| 23      | 14        | 6.36%   |
| 17      | 10        | 4.55%   |
| 34      | 8         | 3.64%   |
| 12      | 8         | 3.64%   |
| 31      | 6         | 2.73%   |
| 16      | 6         | 2.73%   |
| 21      | 4         | 1.82%   |
| 19      | 3         | 1.36%   |
| 25      | 2         | 0.91%   |
| 22      | 2         | 0.91%   |
| 86      | 1         | 0.45%   |
| 84      | 1         | 0.45%   |
| 49      | 1         | 0.45%   |
| 46      | 1         | 0.45%   |
| 43      | 1         | 0.45%   |
| 39      | 1         | 0.45%   |
| 38      | 1         | 0.45%   |
| 28      | 1         | 0.45%   |
| 26      | 1         | 0.45%   |
| 20      | 1         | 0.45%   |
| 11      | 1         | 0.45%   |
| 10      | 1         | 0.45%   |
| Unknown | 1         | 0.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 88        | 40.93%  |
| 501-600     | 56        | 26.05%  |
| 201-300     | 30        | 13.95%  |
| 351-400     | 10        | 4.65%   |
| 701-800     | 8         | 3.72%   |
| 601-700     | 8         | 3.72%   |
| 401-500     | 7         | 3.26%   |
| 1001-1500   | 4         | 1.86%   |
| 801-900     | 2         | 0.93%   |
| 1501-2000   | 1         | 0.47%   |
| Unknown     | 1         | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 137       | 69.19%  |
| 16/10 | 38        | 19.19%  |
| 21/9  | 8         | 4.04%   |
| 5/4   | 7         | 3.54%   |
| 3/2   | 5         | 2.53%   |
| 3.20  | 1         | 0.51%   |
| 1.00  | 1         | 0.51%   |
| 0.56  | 1         | 0.51%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 48        | 21.82%  |
| 101-110        | 39        | 17.73%  |
| 201-250        | 30        | 13.64%  |
| 301-350        | 26        | 11.82%  |
| 351-500        | 15        | 6.82%   |
| 71-80          | 13        | 5.91%   |
| 251-300        | 9         | 4.09%   |
| 61-70          | 8         | 3.64%   |
| 151-200        | 6         | 2.73%   |
| 121-130        | 6         | 2.73%   |
| 111-120        | 5         | 2.27%   |
| 141-150        | 4         | 1.82%   |
| 501-1000       | 4         | 1.82%   |
| More than 1000 | 3         | 1.36%   |
| 51-60          | 1         | 0.45%   |
| 41-50          | 1         | 0.45%   |
| 131-140        | 1         | 0.45%   |
| Unknown        | 1         | 0.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 55        | 26.32%  |
| 51-100        | 53        | 25.36%  |
| 161-240       | 46        | 22.01%  |
| 101-120       | 32        | 15.31%  |
| More than 240 | 19        | 9.09%   |
| 1-50          | 3         | 1.44%   |
| Unknown       | 1         | 0.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 144       | 67.61%  |
| 2     | 39        | 18.31%  |
| 0     | 23        | 10.8%   |
| 3     | 7         | 3.29%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 135       | 45.61%  |
| Realtek Semiconductor             | 94        | 31.76%  |
| Qualcomm Atheros                  | 14        | 4.73%   |
| MediaTek                          | 12        | 4.05%   |
| Broadcom                          | 10        | 3.38%   |
| Aquantia                          | 5         | 1.69%   |
| TP-Link                           | 3         | 1.01%   |
| Ralink Technology                 | 2         | 0.68%   |
| Qualcomm                          | 2         | 0.68%   |
| Microsoft                         | 2         | 0.68%   |
| Lenovo                            | 2         | 0.68%   |
| Xiaomi                            | 1         | 0.34%   |
| Texas Instruments                 | 1         | 0.34%   |
| STMicroelectronics                | 1         | 0.34%   |
| Standard Microsystems             | 1         | 0.34%   |
| Ralink                            | 1         | 0.34%   |
| QinHeng Electronics               | 1         | 0.34%   |
| Pulse-Eight                       | 1         | 0.34%   |
| Oculus VR                         | 1         | 0.34%   |
| ICS Advent                        | 1         | 0.34%   |
| Google                            | 1         | 0.34%   |
| Fibocom                           | 1         | 0.34%   |
| Ericsson Business Mobile Networks | 1         | 0.34%   |
| Edimax Technology                 | 1         | 0.34%   |
| D-Link System                     | 1         | 0.34%   |
| D-Link                            | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 61        | 17.28%  |
| Intel Wi-Fi 6 AX200                                               | 23        | 6.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19        | 5.38%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 3.12%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 10        | 2.83%   |
| Intel Ethernet Controller I225-V                                  | 9         | 2.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 8         | 2.27%   |
| Intel I211 Gigabit Network Connection                             | 8         | 2.27%   |
| Intel Wireless 8265 / 8275                                        | 7         | 1.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 1.98%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 6         | 1.7%    |
| Intel Wireless 8260                                               | 6         | 1.7%    |
| Intel Wireless 7265                                               | 6         | 1.7%    |
| Intel Wi-Fi 6 AX201                                               | 6         | 1.7%    |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.42%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.42%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 1.42%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 4         | 1.13%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 4         | 1.13%   |
| Intel Wireless-AC 9260                                            | 4         | 1.13%   |
| Intel Wireless 7260                                               | 4         | 1.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 1.13%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.13%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 4         | 1.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.85%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.85%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 0.57%   |
| Microsoft Xbox 360 Wireless Adapter                               | 2         | 0.57%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.57%   |
| Intel Wireless 3165                                               | 2         | 0.57%   |
| Intel Wireless 3160                                               | 2         | 0.57%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 111       | 66.87%  |
| MediaTek              | 12        | 7.23%   |
| Qualcomm Atheros      | 11        | 6.63%   |
| Realtek Semiconductor | 10        | 6.02%   |
| Broadcom              | 8         | 4.82%   |
| TP-Link               | 3         | 1.81%   |
| Ralink Technology     | 2         | 1.2%    |
| Qualcomm              | 2         | 1.2%    |
| Microsoft             | 2         | 1.2%    |
| Ralink                | 1         | 0.6%    |
| Fibocom               | 1         | 0.6%    |
| Edimax Technology     | 1         | 0.6%    |
| D-Link System         | 1         | 0.6%    |
| D-Link                | 1         | 0.6%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 23        | 13.86%  |
| Intel Alder Lake-P PCH CNVi WiFi                              | 10        | 6.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 8         | 4.82%   |
| Intel Wireless 8265 / 8275                                    | 7         | 4.22%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 6         | 3.61%   |
| Intel Wireless 8260                                           | 6         | 3.61%   |
| Intel Wireless 7265                                           | 6         | 3.61%   |
| Intel Wi-Fi 6 AX201                                           | 6         | 3.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 5         | 3.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 5         | 3.01%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 4         | 2.41%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 4         | 2.41%   |
| Intel Wireless-AC 9260                                        | 4         | 2.41%   |
| Intel Wireless 7260                                           | 4         | 2.41%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 4         | 2.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 4         | 2.41%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 4         | 2.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 3         | 1.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 3         | 1.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 3         | 1.81%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 3         | 1.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 1.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 2         | 1.2%    |
| Microsoft Xbox 360 Wireless Adapter                           | 2         | 1.2%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 1.2%    |
| Intel Wireless 3165                                           | 2         | 1.2%    |
| Intel Wireless 3160                                           | 2         | 1.2%    |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 1.2%    |
| Intel Alder Lake-S PCH CNVi WiFi                              | 2         | 1.2%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 2         | 1.2%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1         | 0.6%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 1         | 0.6%    |
| TP-Link 802.11ac NIC                                          | 1         | 0.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 0.6%    |
| Realtek 802.11ac NIC                                          | 1         | 0.6%    |
| Ralink RT5572 Wireless Adapter                                | 1         | 0.6%    |
| Ralink RT5370 Wireless Adapter                                | 1         | 0.6%    |
| Ralink RT2800 802.11n PCI                                     | 1         | 0.6%    |
| Qualcomm QCNFA765 Wireless Network Adapter                    | 1         | 0.6%    |
| Qualcomm QCA6390 Wireless Network Adapter                     | 1         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 87        | 50.29%  |
| Intel                 | 65        | 37.57%  |
| Broadcom              | 6         | 3.47%   |
| Aquantia              | 5         | 2.89%   |
| Qualcomm Atheros      | 4         | 2.31%   |
| Lenovo                | 2         | 1.16%   |
| Xiaomi                | 1         | 0.58%   |
| Standard Microsystems | 1         | 0.58%   |
| ICS Advent            | 1         | 0.58%   |
| Google                | 1         | 0.58%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 61        | 33.7%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19        | 10.5%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 6.08%   |
| Intel Ethernet Controller I225-V                                  | 9         | 4.97%   |
| Intel I211 Gigabit Network Connection                             | 8         | 4.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 3.87%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 3.31%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 2.76%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 2.21%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.66%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.1%    |
| Intel I210 Gigabit Network Connection                             | 2         | 1.1%    |
| Intel Ethernet Connection I217-V                                  | 2         | 1.1%    |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.1%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.1%    |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.1%    |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.1%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 1.1%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 1.1%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.55%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.55%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.55%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.55%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.55%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 0.55%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.55%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.55%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.55%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.55%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.55%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 0.55%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.55%   |
| ICS Advent 10/100M LAN                                            | 1         | 0.55%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 160       | 49.54%  |
| Ethernet | 157       | 48.61%  |
| Modem    | 6         | 1.86%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 136       | 63.26%  |
| Ethernet | 79        | 36.74%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 99        | 47.37%  |
| 1     | 96        | 45.93%  |
| 3     | 7         | 3.35%   |
| 0     | 6         | 2.87%   |
| 4     | 1         | 0.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 156       | 73.58%  |
| Yes  | 56        | 26.42%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 97        | 61.78%  |
| Realtek Semiconductor           | 11        | 7.01%   |
| Apple                           | 7         | 4.46%   |
| MediaTek                        | 6         | 3.82%   |
| Cambridge Silicon Radio         | 6         | 3.82%   |
| Broadcom                        | 6         | 3.82%   |
| Qualcomm Atheros Communications | 5         | 3.18%   |
| ASUSTek Computer                | 5         | 3.18%   |
| IMC Networks                    | 4         | 2.55%   |
| Foxconn / Hon Hai               | 4         | 2.55%   |
| Lite-On Technology              | 2         | 1.27%   |
| USI                             | 1         | 0.64%   |
| Realtek                         | 1         | 0.64%   |
| Integrated System Solution      | 1         | 0.64%   |
| HTC (High Tech Computer)        | 1         | 0.64%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 23        | 14.65%  |
| Intel AX200 Bluetooth                                                | 21        | 13.38%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 14        | 8.92%   |
| Intel AX201 Bluetooth                                                | 14        | 8.92%   |
| Intel Bluetooth Device                                               | 11        | 7.01%   |
| Realtek Bluetooth Radio                                              | 10        | 6.37%   |
| Intel AX210 Bluetooth                                                | 7         | 4.46%   |
| MediaTek Wireless_Device                                             | 6         | 3.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 6         | 3.82%   |
| Apple Bluetooth Host Controller                                      | 4         | 2.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 3         | 1.91%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 3         | 1.91%   |
| Foxconn / Hon Hai Wireless_Device                                    | 3         | 1.91%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 3         | 1.91%   |
| Apple Bluetooth USB Host Controller                                  | 3         | 1.91%   |
| Qualcomm Atheros  Bluetooth Device                                   | 2         | 1.27%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 2         | 1.27%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 2         | 1.27%   |
| IMC Networks Wireless_Device                                         | 2         | 1.27%   |
| Broadcom HP Portable SoftSailing                                     | 2         | 1.27%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2         | 1.27%   |
| USI Bluetooth Device                                                 | 1         | 0.64%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1         | 0.64%   |
| Realtek Bluetooth Radio                                              | 1         | 0.64%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 1         | 0.64%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1         | 0.64%   |
| Integrated System Solution Bluetooth Device                          | 1         | 0.64%   |
| IMC Networks Bluetooth Device                                        | 1         | 0.64%   |
| IMC Networks BCM20702A0                                              | 1         | 0.64%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 0.64%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                         | 1         | 0.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 1         | 0.64%   |
| ASUS Broadcom Bluetooth 2.1                                          | 1         | 0.64%   |
| ASUS Bluetooth Device                                                | 1         | 0.64%   |
| ASUS ASUS USB-BT500                                                  | 1         | 0.64%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 131       | 39.82%  |
| AMD                                  | 79        | 24.01%  |
| Nvidia                               | 55        | 16.72%  |
| C-Media Electronics                  | 8         | 2.43%   |
| Lenovo                               | 4         | 1.22%   |
| Creative Technology                  | 4         | 1.22%   |
| Texas Instruments                    | 3         | 0.91%   |
| Sennheiser Communications            | 3         | 0.91%   |
| Realtek Semiconductor                | 3         | 0.91%   |
| Razer USA                            | 3         | 0.91%   |
| Kingston Technology                  | 3         | 0.91%   |
| Focusrite-Novation                   | 3         | 0.91%   |
| ASUSTek Computer                     | 3         | 0.91%   |
| Synaptics                            | 2         | 0.61%   |
| Trust                                | 1         | 0.3%    |
| Thomann                              | 1         | 0.3%    |
| Thesycon Systemsoftware & Consulting | 1         | 0.3%    |
| Sony                                 | 1         | 0.3%    |
| Shure                                | 1         | 0.3%    |
| Schiit Audio                         | 1         | 0.3%    |
| Satechi                              | 1         | 0.3%    |
| RODE Microphones                     | 1         | 0.3%    |
| PreSonus Audio Electronics           | 1         | 0.3%    |
| Logitech                             | 1         | 0.3%    |
| JMTek                                | 1         | 0.3%    |
| Huawei Technologies                  | 1         | 0.3%    |
| Hewlett-Packard                      | 1         | 0.3%    |
| GYROCOM C&C                          | 1         | 0.3%    |
| Giga-Byte Technology                 | 1         | 0.3%    |
| Edifier Technology                   | 1         | 0.3%    |
| Dell                                 | 1         | 0.3%    |
| Creative Labs                        | 1         | 0.3%    |
| Corsair                              | 1         | 0.3%    |
| Conexant Systems                     | 1         | 0.3%    |
| Blue Microphones                     | 1         | 0.3%    |
| ASRock                               | 1         | 0.3%    |
| Apogee Electronics                   | 1         | 0.3%    |
| Antlion Audio                        | 1         | 0.3%    |
| (LCS) USB Audio Device               | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 36        | 9.11%   |
| AMD Renoir Radeon High Definition Audio Controller                      | 25        | 6.33%   |
| Intel Sunrise Point-LP HD Audio                                         | 22        | 5.57%   |
| AMD Starship/Matisse HD Audio Controller                                | 22        | 5.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 12        | 3.04%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                 | 11        | 2.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 11        | 2.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 10        | 2.53%   |
| Intel Cannon Lake PCH cAVS                                              | 9         | 2.28%   |
| AMD Rembrandt Radeon High Definition Audio Controller                   | 8         | 2.03%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]              | 8         | 2.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 7         | 1.77%   |
| AMD Navi 10 HDMI Audio                                                  | 7         | 1.77%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio            | 6         | 1.52%   |
| Intel Cannon Point-LP High Definition Audio Controller                  | 6         | 1.52%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                 | 6         | 1.52%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 6         | 1.52%   |
| Nvidia TU106 High Definition Audio Controller                           | 5         | 1.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 5         | 1.27%   |
| Nvidia TU116 High Definition Audio Controller                           | 4         | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                         | 4         | 1.01%   |
| Nvidia GK104 HDMI Audio Controller                                      | 4         | 1.01%   |
| Nvidia GA106 High Definition Audio Controller                           | 4         | 1.01%   |
| Nvidia GA104 High Definition Audio Controller                           | 4         | 1.01%   |
| Nvidia Audio device                                                     | 4         | 1.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 4         | 1.01%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 4         | 1.01%   |
| Intel Comet Lake PCH cAVS                                               | 4         | 1.01%   |
| Intel Broadwell-U Audio Controller                                      | 4         | 1.01%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 4         | 1.01%   |
| Realtek Semiconductor USB Audio                                         | 3         | 0.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 3         | 0.76%   |
| Nvidia GP106 High Definition Audio Controller                           | 3         | 0.76%   |
| Nvidia GP104 High Definition Audio Controller                           | 3         | 0.76%   |
| Nvidia GK107 HDMI Audio Controller                                      | 3         | 0.76%   |
| Intel Haswell-ULT HD Audio Controller                                   | 3         | 0.76%   |
| Intel Comet Lake PCH-LP cAVS                                            | 3         | 0.76%   |
| Intel 8 Series HD Audio Controller                                      | 3         | 0.76%   |
| Intel 200 Series PCH HD Audio                                           | 3         | 0.76%   |
| Creative Technology SoundBlaster Live! 24-bit External SB0490           | 3         | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 49        | 20.85%  |
| SK hynix                     | 33        | 14.04%  |
| Kingston                     | 30        | 12.77%  |
| Micron Technology            | 29        | 12.34%  |
| Corsair                      | 24        | 10.21%  |
| Crucial                      | 17        | 7.23%   |
| G.Skill                      | 15        | 6.38%   |
| Unknown                      | 6         | 2.55%   |
| Team                         | 6         | 2.55%   |
| Unknown (ABCD)               | 5         | 2.13%   |
| A-DATA Technology            | 4         | 1.7%    |
| Ramaxel Technology           | 3         | 1.28%   |
| GOODRAM                      | 2         | 0.85%   |
| AMD                          | 2         | 0.85%   |
| Unknown                      | 2         | 0.85%   |
| Unknown (0x59B)              | 1         | 0.43%   |
| Strontium                    | 1         | 0.43%   |
| Smart Brazil                 | 1         | 0.43%   |
| Patriot Memory (PDP Systems) | 1         | 0.43%   |
| Patriot                      | 1         | 0.43%   |
| GLOWAY                       | 1         | 0.43%   |
| Avant                        | 1         | 0.43%   |
| Apacer                       | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 4         | 1.59%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.59%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 3         | 1.2%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 3         | 1.2%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 1.2%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.2%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 3         | 1.2%    |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s           | 3         | 1.2%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.8%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 0.8%    |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 0.8%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.8%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.8%    |
| Micron RAM MT62F1G32D4DR-031 8GB Row Of Chips LPDDR5 6400MT/s    | 2         | 0.8%    |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s          | 2         | 0.8%    |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 0.8%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.8%    |
| Micron RAM 16KTF2G64HZ-1G6A1 16GB SODIMM DDR3 1600MT/s           | 2         | 0.8%    |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 2         | 0.8%    |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 2         | 0.8%    |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s              | 2         | 0.8%    |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s           | 2         | 0.8%    |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s           | 2         | 0.8%    |
| Unknown                                                          | 2         | 0.8%    |
| Unknown RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 0.4%    |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 0.4%    |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.4%    |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.4%    |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.4%    |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s                    | 1         | 0.4%    |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s   | 1         | 0.4%    |
| Unknown (0x59B) RAM Module 8GB SODIMM DDR3 1600MT/s              | 1         | 0.4%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s               | 1         | 0.4%    |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s               | 1         | 0.4%    |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2933MT/s               | 1         | 0.4%    |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s             | 1         | 0.4%    |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s               | 1         | 0.4%    |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 1         | 0.4%    |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.4%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1867MT/s                     | 1         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 116       | 58.29%  |
| DDR3   | 40        | 20.1%   |
| LPDDR4 | 16        | 8.04%   |
| LPDDR5 | 13        | 6.53%   |
| DDR5   | 7         | 3.52%   |
| LPDDR3 | 6         | 3.02%   |
| SDRAM  | 1         | 0.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 102       | 50.25%  |
| DIMM         | 66        | 32.51%  |
| Row Of Chips | 30        | 14.78%  |
| Chip         | 3         | 1.48%   |
| RIMM         | 1         | 0.49%   |
| Unknown      | 1         | 0.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 95        | 42.79%  |
| 16384 | 60        | 27.03%  |
| 4096  | 36        | 16.22%  |
| 32768 | 26        | 11.71%  |
| 2048  | 3         | 1.35%   |
| 1024  | 2         | 0.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 52        | 23.85%  |
| 1600    | 30        | 13.76%  |
| 2667    | 25        | 11.47%  |
| 2400    | 19        | 8.72%   |
| 2133    | 16        | 7.34%   |
| 6400    | 13        | 5.96%   |
| 3600    | 9         | 4.13%   |
| 4267    | 8         | 3.67%   |
| 1867    | 5         | 2.29%   |
| 3733    | 4         | 1.83%   |
| 3000    | 4         | 1.83%   |
| 1333    | 4         | 1.83%   |
| 4800    | 3         | 1.38%   |
| 4266    | 3         | 1.38%   |
| 3266    | 3         | 1.38%   |
| 5600    | 2         | 0.92%   |
| 3400    | 2         | 0.92%   |
| 3334    | 2         | 0.92%   |
| 2933    | 2         | 0.92%   |
| 6000    | 1         | 0.46%   |
| 5200    | 1         | 0.46%   |
| 4000    | 1         | 0.46%   |
| 3866    | 1         | 0.46%   |
| 3666    | 1         | 0.46%   |
| 3534    | 1         | 0.46%   |
| 2800    | 1         | 0.46%   |
| 2134    | 1         | 0.46%   |
| 2132    | 1         | 0.46%   |
| 1866    | 1         | 0.46%   |
| 1066    | 1         | 0.46%   |
| Unknown | 1         | 0.46%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Xerox  | 1         | 50%     |
| Canon  | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model               | Computers | Percent |
|---------------------|-----------|---------|
| Xerox Phaser 6125N  | 1         | 50%     |
| Canon TR8500 series | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 23        | 17.04%  |
| IMC Networks                           | 18        | 13.33%  |
| Logitech                               | 17        | 12.59%  |
| Microdia                               | 15        | 11.11%  |
| Realtek Semiconductor                  | 12        | 8.89%   |
| Bison Electronics                      | 11        | 8.15%   |
| Sunplus Innovation Technology          | 7         | 5.19%   |
| Apple                                  | 4         | 2.96%   |
| Acer                                   | 4         | 2.96%   |
| Syntek                                 | 3         | 2.22%   |
| Quanta                                 | 3         | 2.22%   |
| MacroSilicon                           | 3         | 2.22%   |
| Lite-On Technology                     | 3         | 2.22%   |
| Primax Electronics                     | 2         | 1.48%   |
| Alcor Micro                            | 2         | 1.48%   |
| webcamvendor                           | 1         | 0.74%   |
| SunplusIT                              | 1         | 0.74%   |
| Sonix Technology                       | 1         | 0.74%   |
| Samsung Electronics                    | 1         | 0.74%   |
| OPPO Electronics                       | 1         | 0.74%   |
| Microsoft                              | 1         | 0.74%   |
| Luxvisions Innotech Limited            | 1         | 0.74%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 0.74%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 15        | 10.95%  |
| IMC Networks USB2.0 HD UVC WebCam       | 9         | 6.57%   |
| Microdia Integrated_Webcam_HD           | 7         | 5.11%   |
| Bison Integrated Camera                 | 7         | 5.11%   |
| IMC Networks Integrated Camera          | 6         | 4.38%   |
| Realtek Integrated_Webcam_HD            | 5         | 3.65%   |
| Logitech HD Pro Webcam C920             | 4         | 2.92%   |
| Chicony HP HD Camera                    | 4         | 2.92%   |
| Syntek Integrated Camera                | 3         | 2.19%   |
| Sunplus Integrated_Webcam_FHD           | 3         | 2.19%   |
| MacroSilicon USB3. 0 capture            | 3         | 2.19%   |
| Logitech StreamCam                      | 3         | 2.19%   |
| Sunplus Integrated_Webcam_HD            | 2         | 1.46%   |
| Realtek Laptop Camera                   | 2         | 1.46%   |
| Primax HP HD Webcam [Fixed]             | 2         | 1.46%   |
| Microdia Webcam Vitade AF               | 2         | 1.46%   |
| Microdia Integrated Webcam              | 2         | 1.46%   |
| Logitech Webcam C270                    | 2         | 1.46%   |
| Lite-On Integrated Camera               | 2         | 1.46%   |
| Bison HD Webcam                         | 2         | 1.46%   |
| Apple FaceTime HD Camera (Built-in)     | 2         | 1.46%   |
| webcamvendor webcamproduct              | 1         | 0.73%   |
| SunplusIT MTD camera                    | 1         | 0.73%   |
| Sunplus Laptop Integrated Webcam FHD    | 1         | 0.73%   |
| Sunplus HD WebCam                       | 1         | 0.73%   |
| Sonix USB2.0 FHD UVC WebCam             | 1         | 0.73%   |
| Samsung Galaxy series, misc. (MTP mode) | 1         | 0.73%   |
| Realtek USB Camera                      | 1         | 0.73%   |
| Realtek TV Camera                       | 1         | 0.73%   |
| Realtek Lenovo EasyCamera               | 1         | 0.73%   |
| Realtek Integrated Webcam               | 1         | 0.73%   |
| Realtek HD WebCam                       | 1         | 0.73%   |
| Realtek EasyCamera                      | 1         | 0.73%   |
| Quanta VGA WebCam                       | 1         | 0.73%   |
| Quanta HP True Vision HD Camera         | 1         | 0.73%   |
| Quanta HD WebCam                        | 1         | 0.73%   |
| OPPO Oppo N1                            | 1         | 0.73%   |
| Microsoft LifeCam HD-3000               | 1         | 0.73%   |
| Microdia USB 2.0 Camera                 | 1         | 0.73%   |
| Microdia Laptop_Integrated_Webcam_HD    | 1         | 0.73%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 13        | 38.24%  |
| Validity Sensors           | 12        | 35.29%  |
| Shenzhen Goodix Technology | 7         | 20.59%  |
| Gingytech                  | 1         | 2.94%   |
| Focal-systems.Corp         | 1         | 2.94%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 5         | 14.71%  |
| Shenzhen Goodix Fingerprint Reader                       | 5         | 14.71%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 3         | 8.82%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 3         | 8.82%   |
| Validity Sensors VFS491                                  | 2         | 5.88%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 5.88%   |
| Validity Sensors Synaptics WBDI                          | 2         | 5.88%   |
| Synaptics UWP WBDI Device                                | 2         | 5.88%   |
| Synaptics UWP WBDI                                       | 2         | 5.88%   |
| Shenzhen Goodix  Fingerprint Device                      | 2         | 5.88%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor        | 1         | 2.94%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 2.94%   |
| Validity Sensors VFS495 Fingerprint Reader               | 1         | 2.94%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 2.94%   |
| Gingytech Fingerprint sensor                             | 1         | 2.94%   |
| Focal-systems.Corp FT9201Fingerprint.                    | 1         | 2.94%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 12        | 54.55%  |
| Broadcom    | 5         | 22.73%  |
| Yubico.com  | 3         | 13.64%  |
| Upek        | 1         | 4.55%   |
| OmniKey     | 1         | 4.55%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 12        | 54.55%  |
| Yubico.com Yubikey 4/5 U2F+CCID                            | 2         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 9.09%   |
| Broadcom 5880                                              | 2         | 9.09%   |
| Yubico.com Yubikey NEO(-N) U2F+CCID                        | 1         | 4.55%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 4.55%   |
| OmniKey CardMan Smart@Link                                 | 1         | 4.55%   |
| Broadcom 58200                                             | 1         | 4.55%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 124       | 57.41%  |
| 1     | 58        | 26.85%  |
| 2     | 31        | 14.35%  |
| 4     | 2         | 0.93%   |
| 3     | 1         | 0.46%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 32        | 25.6%   |
| Multimedia controller    | 24        | 19.2%   |
| Graphics card            | 21        | 16.8%   |
| Chipcard                 | 17        | 13.6%   |
| Net/wireless             | 8         | 6.4%    |
| Camera                   | 6         | 4.8%    |
| Bluetooth                | 5         | 4%      |
| Unassigned class         | 3         | 2.4%    |
| Modem                    | 2         | 1.6%    |
| Card reader              | 2         | 1.6%    |
| Storage/ata              | 1         | 0.8%    |
| Network                  | 1         | 0.8%    |
| Firewire controller      | 1         | 0.8%    |
| Dvb card                 | 1         | 0.8%    |
| Communication controller | 1         | 0.8%    |

