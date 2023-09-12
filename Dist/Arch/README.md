Arch - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Arch.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Arch/Desktop/README.md) and [notebooks](/Dist/Arch/Notebook/README.md).

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

Total: 9741

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Pavilion 15                 | Notebook    | [c251475f43](https://linux-hardware.org/?probe=c251475f43) | Sep 07, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [32c21f0b73](https://linux-hardware.org/?probe=32c21f0b73) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [f33c62ab06](https://linux-hardware.org/?probe=f33c62ab06) | Sep 07, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [d9509a0fa0](https://linux-hardware.org/?probe=d9509a0fa0) | Sep 07, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [373ba724e4](https://linux-hardware.org/?probe=373ba724e4) | Sep 06, 2023 |
| HP            | Pavilion dv6                | Notebook    | [08d38c1680](https://linux-hardware.org/?probe=08d38c1680) | Sep 06, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [a4fb146fe8](https://linux-hardware.org/?probe=a4fb146fe8) | Sep 06, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [5d22a61587](https://linux-hardware.org/?probe=5d22a61587) | Sep 06, 2023 |
| Lenovo        | Yoga Slim 7 14APU8 83AA     | Notebook    | [b884752710](https://linux-hardware.org/?probe=b884752710) | Sep 06, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [c22fad9c67](https://linux-hardware.org/?probe=c22fad9c67) | Sep 06, 2023 |
| ASUSTek       | PRIME B650M-A II            | Desktop     | [307ca05754](https://linux-hardware.org/?probe=307ca05754) | Sep 06, 2023 |
| ASUSTek       | X555QG                      | Notebook    | [8cf63afc0f](https://linux-hardware.org/?probe=8cf63afc0f) | Sep 06, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [57764e02db](https://linux-hardware.org/?probe=57764e02db) | Sep 06, 2023 |
| Lenovo        | ThinkPad X390 20Q0002UUS    | Notebook    | [aab185ac48](https://linux-hardware.org/?probe=aab185ac48) | Sep 06, 2023 |
| Microsoft     | Surface Book 2              | Tablet      | [de36160f60](https://linux-hardware.org/?probe=de36160f60) | Sep 06, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [8e0ee8ad83](https://linux-hardware.org/?probe=8e0ee8ad83) | Sep 06, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [ee70bf217a](https://linux-hardware.org/?probe=ee70bf217a) | Sep 06, 2023 |
| Pegatron      | 2AD3                        | Desktop     | [07cfb5b967](https://linux-hardware.org/?probe=07cfb5b967) | Sep 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d3e36fc6ea](https://linux-hardware.org/?probe=d3e36fc6ea) | Sep 05, 2023 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [9c7d201848](https://linux-hardware.org/?probe=9c7d201848) | Sep 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [a64157168e](https://linux-hardware.org/?probe=a64157168e) | Sep 05, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [bbbba2bc47](https://linux-hardware.org/?probe=bbbba2bc47) | Sep 05, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [cd4ccc8478](https://linux-hardware.org/?probe=cd4ccc8478) | Sep 05, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [51b40f3137](https://linux-hardware.org/?probe=51b40f3137) | Sep 05, 2023 |
| Samsung       | 750XDA                      | Notebook    | [efe919fb13](https://linux-hardware.org/?probe=efe919fb13) | Sep 05, 2023 |
| Intel         | DH55TC AAE70932-206         | Desktop     | [0576ca20ab](https://linux-hardware.org/?probe=0576ca20ab) | Sep 05, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [1fce93cab3](https://linux-hardware.org/?probe=1fce93cab3) | Sep 05, 2023 |
| Acer          | Veriton M480                | Desktop     | [0c97015cce](https://linux-hardware.org/?probe=0c97015cce) | Sep 05, 2023 |
| Intel         | DH55TC AAE70932-206         | Desktop     | [710c22af52](https://linux-hardware.org/?probe=710c22af52) | Sep 05, 2023 |
| HP            | ProBook 6570b               | Notebook    | [f66ec50e55](https://linux-hardware.org/?probe=f66ec50e55) | Sep 05, 2023 |
| HP            | ProBook 6570b               | Notebook    | [9a31047350](https://linux-hardware.org/?probe=9a31047350) | Sep 05, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [5e7621ae15](https://linux-hardware.org/?probe=5e7621ae15) | Sep 04, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [3747ee0c29](https://linux-hardware.org/?probe=3747ee0c29) | Sep 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [ceade9f24f](https://linux-hardware.org/?probe=ceade9f24f) | Sep 04, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [522dd175b1](https://linux-hardware.org/?probe=522dd175b1) | Sep 04, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [4a93cea12b](https://linux-hardware.org/?probe=4a93cea12b) | Sep 04, 2023 |
| Lenovo        | ThinkPad X250 20CLS2TQ0E    | Notebook    | [c5cdf73aa5](https://linux-hardware.org/?probe=c5cdf73aa5) | Sep 04, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [81f816e956](https://linux-hardware.org/?probe=81f816e956) | Sep 03, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [e30eaf0d9a](https://linux-hardware.org/?probe=e30eaf0d9a) | Sep 03, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [d208a16a1b](https://linux-hardware.org/?probe=d208a16a1b) | Sep 03, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [0fe16a99d6](https://linux-hardware.org/?probe=0fe16a99d6) | Sep 03, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [2eed39fb24](https://linux-hardware.org/?probe=2eed39fb24) | Sep 03, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [d6be71642e](https://linux-hardware.org/?probe=d6be71642e) | Sep 03, 2023 |
| ASUSTek       | A88X-PRO                    | Desktop     | [79ca2081a1](https://linux-hardware.org/?probe=79ca2081a1) | Sep 03, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [b8aba55b59](https://linux-hardware.org/?probe=b8aba55b59) | Sep 03, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [99b1fcf2e9](https://linux-hardware.org/?probe=99b1fcf2e9) | Sep 03, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [56520c8e8d](https://linux-hardware.org/?probe=56520c8e8d) | Sep 03, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [ebfb4ddd3e](https://linux-hardware.org/?probe=ebfb4ddd3e) | Sep 03, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [5dac4ae656](https://linux-hardware.org/?probe=5dac4ae656) | Sep 03, 2023 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [ad65335e8d](https://linux-hardware.org/?probe=ad65335e8d) | Sep 02, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [9ab3e57ab7](https://linux-hardware.org/?probe=9ab3e57ab7) | Sep 02, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [239c2bbc02](https://linux-hardware.org/?probe=239c2bbc02) | Sep 02, 2023 |
| Dell          | Latitude 3410               | Notebook    | [695e65a1f0](https://linux-hardware.org/?probe=695e65a1f0) | Sep 02, 2023 |
| Dell          | 030VXY A02                  | Desktop     | [ff787e57bc](https://linux-hardware.org/?probe=ff787e57bc) | Sep 01, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [f39e23df01](https://linux-hardware.org/?probe=f39e23df01) | Sep 01, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [6736962dbe](https://linux-hardware.org/?probe=6736962dbe) | Sep 01, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [e0c18cf228](https://linux-hardware.org/?probe=e0c18cf228) | Aug 31, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [e7d07d7c88](https://linux-hardware.org/?probe=e7d07d7c88) | Aug 31, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [3c434cdeda](https://linux-hardware.org/?probe=3c434cdeda) | Aug 31, 2023 |
| GEO           | GeoFlex 340                 | Convertible | [32d9616a38](https://linux-hardware.org/?probe=32d9616a38) | Aug 31, 2023 |
| GEO           | GeoFlex 340                 | Convertible | [2a0a234dbf](https://linux-hardware.org/?probe=2a0a234dbf) | Aug 31, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [aad9baafe2](https://linux-hardware.org/?probe=aad9baafe2) | Aug 31, 2023 |
| MSI           | MS-7E06                     | Notebook    | [afd9e6ccb2](https://linux-hardware.org/?probe=afd9e6ccb2) | Aug 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [86b1c6ecfa](https://linux-hardware.org/?probe=86b1c6ecfa) | Aug 30, 2023 |
| Intel Clie... | LAPAC71H                    | Notebook    | [67d6ffca34](https://linux-hardware.org/?probe=67d6ffca34) | Aug 30, 2023 |
| Intel Clie... | LAPAC71H                    | Notebook    | [e5a008be38](https://linux-hardware.org/?probe=e5a008be38) | Aug 30, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [6d0b6e95ba](https://linux-hardware.org/?probe=6d0b6e95ba) | Aug 30, 2023 |
| ASUSTek       | A88X-PRO                    | Desktop     | [9327ae4f97](https://linux-hardware.org/?probe=9327ae4f97) | Aug 30, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [ce793ccb8d](https://linux-hardware.org/?probe=ce793ccb8d) | Aug 30, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [6dd95e8115](https://linux-hardware.org/?probe=6dd95e8115) | Aug 30, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 8 2... | Convertible | [f253067fa5](https://linux-hardware.org/?probe=f253067fa5) | Aug 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [aa23e296ad](https://linux-hardware.org/?probe=aa23e296ad) | Aug 30, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [7075df2d62](https://linux-hardware.org/?probe=7075df2d62) | Aug 30, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [7d74c2bc61](https://linux-hardware.org/?probe=7d74c2bc61) | Aug 29, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [0b44043b10](https://linux-hardware.org/?probe=0b44043b10) | Aug 29, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [dcceb74a56](https://linux-hardware.org/?probe=dcceb74a56) | Aug 29, 2023 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [c5fb822b1c](https://linux-hardware.org/?probe=c5fb822b1c) | Aug 29, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 8 2... | Convertible | [baf0966633](https://linux-hardware.org/?probe=baf0966633) | Aug 29, 2023 |
| Acer          | One Z1402                   | Notebook    | [2e917719ec](https://linux-hardware.org/?probe=2e917719ec) | Aug 29, 2023 |
| Dell          | Inspiron 7791 2n1           | Convertible | [f209f11620](https://linux-hardware.org/?probe=f209f11620) | Aug 29, 2023 |
| Huanan        | H610M-PLUS V1.2             | Desktop     | [083aaaf1eb](https://linux-hardware.org/?probe=083aaaf1eb) | Aug 29, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [caaf599d6a](https://linux-hardware.org/?probe=caaf599d6a) | Aug 29, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [f91274084a](https://linux-hardware.org/?probe=f91274084a) | Aug 29, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [0817c6178e](https://linux-hardware.org/?probe=0817c6178e) | Aug 29, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [0a2adee694](https://linux-hardware.org/?probe=0a2adee694) | Aug 29, 2023 |
| HP            | Laptop 14s-dy2xxx           | Notebook    | [598458b278](https://linux-hardware.org/?probe=598458b278) | Aug 28, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [56692679f3](https://linux-hardware.org/?probe=56692679f3) | Aug 28, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [15b81ebfc0](https://linux-hardware.org/?probe=15b81ebfc0) | Aug 28, 2023 |
| Dell          | Precision 3520              | Notebook    | [a87048ecac](https://linux-hardware.org/?probe=a87048ecac) | Aug 28, 2023 |
| Dell          | Precision 3520              | Notebook    | [6afb6bacac](https://linux-hardware.org/?probe=6afb6bacac) | Aug 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [c2c0708639](https://linux-hardware.org/?probe=c2c0708639) | Aug 28, 2023 |
| ECS           | G31T-M7                     | Desktop     | [f095887170](https://linux-hardware.org/?probe=f095887170) | Aug 28, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [4bff36d914](https://linux-hardware.org/?probe=4bff36d914) | Aug 28, 2023 |
| Gigabyte      | 970A-D3P                    | Desktop     | [e178a50d54](https://linux-hardware.org/?probe=e178a50d54) | Aug 27, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [3c68838457](https://linux-hardware.org/?probe=3c68838457) | Aug 27, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [4e7e2a9946](https://linux-hardware.org/?probe=4e7e2a9946) | Aug 27, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [b7020427e0](https://linux-hardware.org/?probe=b7020427e0) | Aug 27, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [2a25ad0be2](https://linux-hardware.org/?probe=2a25ad0be2) | Aug 27, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [9b94ab3887](https://linux-hardware.org/?probe=9b94ab3887) | Aug 27, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [72e8fd41af](https://linux-hardware.org/?probe=72e8fd41af) | Aug 26, 2023 |
| Dell          | Latitude 5580               | Notebook    | [e16786f57e](https://linux-hardware.org/?probe=e16786f57e) | Aug 26, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [fc59d4358f](https://linux-hardware.org/?probe=fc59d4358f) | Aug 26, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [7425d71f52](https://linux-hardware.org/?probe=7425d71f52) | Aug 26, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [caf8dd1fc3](https://linux-hardware.org/?probe=caf8dd1fc3) | Aug 26, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [fc86b0463f](https://linux-hardware.org/?probe=fc86b0463f) | Aug 26, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [3cce8305bb](https://linux-hardware.org/?probe=3cce8305bb) | Aug 26, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [83695164cc](https://linux-hardware.org/?probe=83695164cc) | Aug 26, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [ee4e04964c](https://linux-hardware.org/?probe=ee4e04964c) | Aug 26, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [3ee57cbdbe](https://linux-hardware.org/?probe=3ee57cbdbe) | Aug 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [f30251883f](https://linux-hardware.org/?probe=f30251883f) | Aug 25, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [e3c32f6873](https://linux-hardware.org/?probe=e3c32f6873) | Aug 25, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [555c7d17f0](https://linux-hardware.org/?probe=555c7d17f0) | Aug 25, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [2668db7570](https://linux-hardware.org/?probe=2668db7570) | Aug 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3a86d43941](https://linux-hardware.org/?probe=3a86d43941) | Aug 25, 2023 |
| HP            | 1497                        | Desktop     | [32a8075d02](https://linux-hardware.org/?probe=32a8075d02) | Aug 25, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2707044ee5](https://linux-hardware.org/?probe=2707044ee5) | Aug 25, 2023 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [f5f6d366a1](https://linux-hardware.org/?probe=f5f6d366a1) | Aug 24, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [9d09e14624](https://linux-hardware.org/?probe=9d09e14624) | Aug 24, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | Notebook    | [9938e1fbcc](https://linux-hardware.org/?probe=9938e1fbcc) | Aug 24, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [d44597af00](https://linux-hardware.org/?probe=d44597af00) | Aug 23, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [7486221845](https://linux-hardware.org/?probe=7486221845) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [60588f77af](https://linux-hardware.org/?probe=60588f77af) | Aug 23, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [368f9f947b](https://linux-hardware.org/?probe=368f9f947b) | Aug 23, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [90faf14c05](https://linux-hardware.org/?probe=90faf14c05) | Aug 23, 2023 |
| Dell          | 07978V A10                  | Server      | [dcd73b2802](https://linux-hardware.org/?probe=dcd73b2802) | Aug 23, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [95b9733408](https://linux-hardware.org/?probe=95b9733408) | Aug 23, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [34532a7998](https://linux-hardware.org/?probe=34532a7998) | Aug 23, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [74ff13d301](https://linux-hardware.org/?probe=74ff13d301) | Aug 23, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [6c9f647d44](https://linux-hardware.org/?probe=6c9f647d44) | Aug 23, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [6e915a1913](https://linux-hardware.org/?probe=6e915a1913) | Aug 22, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [3a3b362bd0](https://linux-hardware.org/?probe=3a3b362bd0) | Aug 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [e0a5f63a8b](https://linux-hardware.org/?probe=e0a5f63a8b) | Aug 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [8e478e15da](https://linux-hardware.org/?probe=8e478e15da) | Aug 22, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [cdb0c49b6a](https://linux-hardware.org/?probe=cdb0c49b6a) | Aug 22, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [9762e16c0e](https://linux-hardware.org/?probe=9762e16c0e) | Aug 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [8fd1db4fee](https://linux-hardware.org/?probe=8fd1db4fee) | Aug 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [2cbbb89cd4](https://linux-hardware.org/?probe=2cbbb89cd4) | Aug 21, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [4bc2673b83](https://linux-hardware.org/?probe=4bc2673b83) | Aug 21, 2023 |
| Dell          | 0D883F A04                  | Desktop     | [f76b91821d](https://linux-hardware.org/?probe=f76b91821d) | Aug 21, 2023 |
| HONOR         | NMH-WDX9                    | Notebook    | [edc1d99b63](https://linux-hardware.org/?probe=edc1d99b63) | Aug 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2e4f8c0f7c](https://linux-hardware.org/?probe=2e4f8c0f7c) | Aug 21, 2023 |
| Lenovo        | ThinkPad P51 20HJS5WH0D     | Notebook    | [ae8a51b2f5](https://linux-hardware.org/?probe=ae8a51b2f5) | Aug 21, 2023 |
| Gigabyte      | M68M-S2P                    | Desktop     | [41ba06b203](https://linux-hardware.org/?probe=41ba06b203) | Aug 21, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [005b310c55](https://linux-hardware.org/?probe=005b310c55) | Aug 20, 2023 |
| AZW           | GTR V11                     | Desktop     | [9aefbc3e69](https://linux-hardware.org/?probe=9aefbc3e69) | Aug 20, 2023 |
| Intel         | X99                         | Desktop     | [c1ad35e185](https://linux-hardware.org/?probe=c1ad35e185) | Aug 20, 2023 |
| HP            | 2B29                        | Desktop     | [62f37a51ca](https://linux-hardware.org/?probe=62f37a51ca) | Aug 20, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [28a27adc22](https://linux-hardware.org/?probe=28a27adc22) | Aug 20, 2023 |
| Gigabyte      | AX370-Gaming 3-CF           | Desktop     | [13bcbc11d7](https://linux-hardware.org/?probe=13bcbc11d7) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XY... | Notebook    | [19675df004](https://linux-hardware.org/?probe=19675df004) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603VV... | Notebook    | [b156da40ac](https://linux-hardware.org/?probe=b156da40ac) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603VV... | Notebook    | [8b4709e684](https://linux-hardware.org/?probe=8b4709e684) | Aug 20, 2023 |
| MSI           | GF75 Thin 10SC              | Notebook    | [f50df27008](https://linux-hardware.org/?probe=f50df27008) | Aug 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [778ea97c77](https://linux-hardware.org/?probe=778ea97c77) | Aug 20, 2023 |
| TYAN Compu... | S8010                       | Desktop     | [a381c313e3](https://linux-hardware.org/?probe=a381c313e3) | Aug 20, 2023 |
| Alienware     | m15 R4                      | Notebook    | [46f36f26ff](https://linux-hardware.org/?probe=46f36f26ff) | Aug 20, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [e33524b456](https://linux-hardware.org/?probe=e33524b456) | Aug 20, 2023 |
| Dell          | 0VNP2H A01                  | Desktop     | [5724c221b8](https://linux-hardware.org/?probe=5724c221b8) | Aug 19, 2023 |
| Alienware     | m15 R4                      | Notebook    | [cf9a9e0729](https://linux-hardware.org/?probe=cf9a9e0729) | Aug 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [0585143fdc](https://linux-hardware.org/?probe=0585143fdc) | Aug 19, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [006d138f62](https://linux-hardware.org/?probe=006d138f62) | Aug 19, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [c95ab5ea6e](https://linux-hardware.org/?probe=c95ab5ea6e) | Aug 18, 2023 |
| ASUSTek       | P8H61-MX                    | Desktop     | [767b42eeca](https://linux-hardware.org/?probe=767b42eeca) | Aug 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3c0bf7ce7b](https://linux-hardware.org/?probe=3c0bf7ce7b) | Aug 18, 2023 |
| Gigabyte      | B560M D3H                   | Desktop     | [7a9ae970e6](https://linux-hardware.org/?probe=7a9ae970e6) | Aug 18, 2023 |
| Dell          | Inspiron 7591               | Notebook    | [2e09db6501](https://linux-hardware.org/?probe=2e09db6501) | Aug 18, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [1289521063](https://linux-hardware.org/?probe=1289521063) | Aug 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [84cbd742a1](https://linux-hardware.org/?probe=84cbd742a1) | Aug 17, 2023 |
| ASUSTek       | GL552VX                     | Notebook    | [fbe195ec09](https://linux-hardware.org/?probe=fbe195ec09) | Aug 17, 2023 |
| ASUSTek       | GL552VX                     | Notebook    | [37a66a073b](https://linux-hardware.org/?probe=37a66a073b) | Aug 17, 2023 |
| ASUSTek       | PRIME H610M-R D4            | Desktop     | [caae17275e](https://linux-hardware.org/?probe=caae17275e) | Aug 17, 2023 |
| Notebook      | NS50MU                      | Notebook    | [37abf5de2d](https://linux-hardware.org/?probe=37abf5de2d) | Aug 17, 2023 |
| QIYIDA        | X79 (INTEL Xeon E5/Corei... | Desktop     | [1aeba3a6ec](https://linux-hardware.org/?probe=1aeba3a6ec) | Aug 17, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [3a7f4ca491](https://linux-hardware.org/?probe=3a7f4ca491) | Aug 17, 2023 |
| QIYIDA        | X79 (INTEL Xeon E5/Corei... | Desktop     | [b44417fa3d](https://linux-hardware.org/?probe=b44417fa3d) | Aug 17, 2023 |
| Shenzhen M... | F7BSC                       | Desktop     | [94b9b057b4](https://linux-hardware.org/?probe=94b9b057b4) | Aug 17, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [eb44f4dfc1](https://linux-hardware.org/?probe=eb44f4dfc1) | Aug 17, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [14ea4148dc](https://linux-hardware.org/?probe=14ea4148dc) | Aug 17, 2023 |
| MSI           | GF75 Thin 9SCSR             | Notebook    | [365fe49e34](https://linux-hardware.org/?probe=365fe49e34) | Aug 17, 2023 |
| CWWK          | N3050 P1                    | Desktop     | [dd3dfb0c02](https://linux-hardware.org/?probe=dd3dfb0c02) | Aug 17, 2023 |
| Shenzhen M... | F7BSC                       | Desktop     | [bfe3223b92](https://linux-hardware.org/?probe=bfe3223b92) | Aug 17, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [576626db19](https://linux-hardware.org/?probe=576626db19) | Aug 17, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [1b29161809](https://linux-hardware.org/?probe=1b29161809) | Aug 16, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [fd91c311ff](https://linux-hardware.org/?probe=fd91c311ff) | Aug 16, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [73640f7f83](https://linux-hardware.org/?probe=73640f7f83) | Aug 16, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [1d389611a3](https://linux-hardware.org/?probe=1d389611a3) | Aug 16, 2023 |
| Dell          | Inspiron 7791 2n1           | Convertible | [b9ce6dd48c](https://linux-hardware.org/?probe=b9ce6dd48c) | Aug 16, 2023 |
| HUAWEI        | WRT-WX9                     | Notebook    | [39a98650a3](https://linux-hardware.org/?probe=39a98650a3) | Aug 16, 2023 |
| Timi          | A35S                        | Notebook    | [7f78fd50bd](https://linux-hardware.org/?probe=7f78fd50bd) | Aug 16, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [c8ed9b0cb2](https://linux-hardware.org/?probe=c8ed9b0cb2) | Aug 16, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | Notebook    | [2a3b142ddd](https://linux-hardware.org/?probe=2a3b142ddd) | Aug 16, 2023 |
| Dell          | Latitude 5300               | Notebook    | [506c05d30c](https://linux-hardware.org/?probe=506c05d30c) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [24a5a21c43](https://linux-hardware.org/?probe=24a5a21c43) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [accdc886c7](https://linux-hardware.org/?probe=accdc886c7) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [96d94e5f6c](https://linux-hardware.org/?probe=96d94e5f6c) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [5652688ceb](https://linux-hardware.org/?probe=5652688ceb) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [7463d795e8](https://linux-hardware.org/?probe=7463d795e8) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [38e95ded09](https://linux-hardware.org/?probe=38e95ded09) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [651eae5b59](https://linux-hardware.org/?probe=651eae5b59) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [d32a9fb8a4](https://linux-hardware.org/?probe=d32a9fb8a4) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [5929bf1039](https://linux-hardware.org/?probe=5929bf1039) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [ac0320b2ee](https://linux-hardware.org/?probe=ac0320b2ee) | Aug 15, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [78e30cb8ef](https://linux-hardware.org/?probe=78e30cb8ef) | Aug 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [67a1535765](https://linux-hardware.org/?probe=67a1535765) | Aug 15, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [e2a4a35103](https://linux-hardware.org/?probe=e2a4a35103) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [5d52bf85ca](https://linux-hardware.org/?probe=5d52bf85ca) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [f972a8359d](https://linux-hardware.org/?probe=f972a8359d) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [ab0235d27c](https://linux-hardware.org/?probe=ab0235d27c) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [3446b719ab](https://linux-hardware.org/?probe=3446b719ab) | Aug 15, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | Notebook    | [3750dc2cb1](https://linux-hardware.org/?probe=3750dc2cb1) | Aug 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [e53e56fcbc](https://linux-hardware.org/?probe=e53e56fcbc) | Aug 15, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [b78f4bf01d](https://linux-hardware.org/?probe=b78f4bf01d) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [c27b841a97](https://linux-hardware.org/?probe=c27b841a97) | Aug 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [d6925a9c7a](https://linux-hardware.org/?probe=d6925a9c7a) | Aug 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [acf70a31a9](https://linux-hardware.org/?probe=acf70a31a9) | Aug 14, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [b223cba859](https://linux-hardware.org/?probe=b223cba859) | Aug 14, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [bbe00bbe48](https://linux-hardware.org/?probe=bbe00bbe48) | Aug 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [10f2a6448d](https://linux-hardware.org/?probe=10f2a6448d) | Aug 14, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [17d837907e](https://linux-hardware.org/?probe=17d837907e) | Aug 14, 2023 |
| ECS           | G31T-M7                     | Desktop     | [2d35b5e140](https://linux-hardware.org/?probe=2d35b5e140) | Aug 14, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [857539aaba](https://linux-hardware.org/?probe=857539aaba) | Aug 14, 2023 |
| Intel         | X79M-S                      | Desktop     | [043e072c46](https://linux-hardware.org/?probe=043e072c46) | Aug 14, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [e6fe434dfa](https://linux-hardware.org/?probe=e6fe434dfa) | Aug 13, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [c822a4c96f](https://linux-hardware.org/?probe=c822a4c96f) | Aug 13, 2023 |
| NZXT          | N7 B550                     | Desktop     | [6cf14ccbe3](https://linux-hardware.org/?probe=6cf14ccbe3) | Aug 13, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [74a73b0208](https://linux-hardware.org/?probe=74a73b0208) | Aug 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [d344d7ada0](https://linux-hardware.org/?probe=d344d7ada0) | Aug 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [5286543cae](https://linux-hardware.org/?probe=5286543cae) | Aug 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [464dc037bd](https://linux-hardware.org/?probe=464dc037bd) | Aug 13, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [a6212b25ea](https://linux-hardware.org/?probe=a6212b25ea) | Aug 13, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [494c725472](https://linux-hardware.org/?probe=494c725472) | Aug 13, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [e03e2f8abc](https://linux-hardware.org/?probe=e03e2f8abc) | Aug 13, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [11a7488d83](https://linux-hardware.org/?probe=11a7488d83) | Aug 12, 2023 |
| Gigabyte      | 970A-D3P                    | Desktop     | [8ef51956a9](https://linux-hardware.org/?probe=8ef51956a9) | Aug 12, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [f7ab4aa00a](https://linux-hardware.org/?probe=f7ab4aa00a) | Aug 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e0e0c962d5](https://linux-hardware.org/?probe=e0e0c962d5) | Aug 12, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [504746e40c](https://linux-hardware.org/?probe=504746e40c) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [49662a8ac9](https://linux-hardware.org/?probe=49662a8ac9) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [c946b79f5a](https://linux-hardware.org/?probe=c946b79f5a) | Aug 12, 2023 |
| Alienware     | 15                          | Notebook    | [d6c9c4f931](https://linux-hardware.org/?probe=d6c9c4f931) | Aug 12, 2023 |
| Acer          | Aspire E1-571G              | Notebook    | [ca51aaad9f](https://linux-hardware.org/?probe=ca51aaad9f) | Aug 12, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [20559d710a](https://linux-hardware.org/?probe=20559d710a) | Aug 12, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [3181a592ac](https://linux-hardware.org/?probe=3181a592ac) | Aug 12, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [95d93fda2c](https://linux-hardware.org/?probe=95d93fda2c) | Aug 11, 2023 |
| Intel         | NUC7i5BNB J31144-303        | Mini pc     | [144f77980e](https://linux-hardware.org/?probe=144f77980e) | Aug 11, 2023 |
| Gigabyte      | B365 HD3                    | Desktop     | [e2ebf1941c](https://linux-hardware.org/?probe=e2ebf1941c) | Aug 11, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [79889c3f89](https://linux-hardware.org/?probe=79889c3f89) | Aug 11, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [7fe6adce5e](https://linux-hardware.org/?probe=7fe6adce5e) | Aug 10, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [3771669b84](https://linux-hardware.org/?probe=3771669b84) | Aug 10, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [773b111412](https://linux-hardware.org/?probe=773b111412) | Aug 10, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [70c4f2863b](https://linux-hardware.org/?probe=70c4f2863b) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d38ef662d4](https://linux-hardware.org/?probe=d38ef662d4) | Aug 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [89cb081c1f](https://linux-hardware.org/?probe=89cb081c1f) | Aug 10, 2023 |
| Lenovo        | ThinkPad T420 4236W1W       | Notebook    | [0b8fc947af](https://linux-hardware.org/?probe=0b8fc947af) | Aug 10, 2023 |
| Lenovo        | ThinkPad P51 20HH0015IX     | Notebook    | [77c11473b2](https://linux-hardware.org/?probe=77c11473b2) | Aug 10, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [6e7a8f72dd](https://linux-hardware.org/?probe=6e7a8f72dd) | Aug 10, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [fdfeffb5f3](https://linux-hardware.org/?probe=fdfeffb5f3) | Aug 10, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [71424c4380](https://linux-hardware.org/?probe=71424c4380) | Aug 10, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [84d6b99d2c](https://linux-hardware.org/?probe=84d6b99d2c) | Aug 10, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [45da50b5c8](https://linux-hardware.org/?probe=45da50b5c8) | Aug 10, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [03cb2690f7](https://linux-hardware.org/?probe=03cb2690f7) | Aug 10, 2023 |
| Acer          | Aspire A514-53              | Notebook    | [26e60daa62](https://linux-hardware.org/?probe=26e60daa62) | Aug 10, 2023 |
| HP            | Pavilion 17                 | Notebook    | [65733120b0](https://linux-hardware.org/?probe=65733120b0) | Aug 09, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [51fa860c87](https://linux-hardware.org/?probe=51fa860c87) | Aug 09, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [939205ed85](https://linux-hardware.org/?probe=939205ed85) | Aug 09, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [afef0bb361](https://linux-hardware.org/?probe=afef0bb361) | Aug 09, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [3ecd6d3f74](https://linux-hardware.org/?probe=3ecd6d3f74) | Aug 09, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [3474fa639e](https://linux-hardware.org/?probe=3474fa639e) | Aug 08, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [3cd08fb125](https://linux-hardware.org/?probe=3cd08fb125) | Aug 08, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [ffd0be48c6](https://linux-hardware.org/?probe=ffd0be48c6) | Aug 08, 2023 |
| Dell          | Inspiron 13-7353            | Notebook    | [0b797c9368](https://linux-hardware.org/?probe=0b797c9368) | Aug 08, 2023 |
| Dell          | Inspiron 13-7353            | Notebook    | [90fbc716ed](https://linux-hardware.org/?probe=90fbc716ed) | Aug 07, 2023 |
| Lenovo        | Legion S7 15ARH5 82HM       | Notebook    | [044df6f82e](https://linux-hardware.org/?probe=044df6f82e) | Aug 07, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [608c3967b2](https://linux-hardware.org/?probe=608c3967b2) | Aug 07, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [e6955ee04c](https://linux-hardware.org/?probe=e6955ee04c) | Aug 07, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f772c670ff](https://linux-hardware.org/?probe=f772c670ff) | Aug 07, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [fc8b72dd99](https://linux-hardware.org/?probe=fc8b72dd99) | Aug 07, 2023 |
| MSI           | H370M BAZOOKA               | Desktop     | [760051e27b](https://linux-hardware.org/?probe=760051e27b) | Aug 07, 2023 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | Notebook    | [5510e9c316](https://linux-hardware.org/?probe=5510e9c316) | Aug 06, 2023 |
| MSI           | Z270 TOMAHAWK OPT BOOST     | Desktop     | [6baabbdd21](https://linux-hardware.org/?probe=6baabbdd21) | Aug 06, 2023 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [01b9adfb02](https://linux-hardware.org/?probe=01b9adfb02) | Aug 05, 2023 |
| ASUSTek       | K73SV                       | Notebook    | [c908f2bfdd](https://linux-hardware.org/?probe=c908f2bfdd) | Aug 05, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [0219350ae0](https://linux-hardware.org/?probe=0219350ae0) | Aug 05, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [350a405f33](https://linux-hardware.org/?probe=350a405f33) | Aug 05, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [21eaf09dc9](https://linux-hardware.org/?probe=21eaf09dc9) | Aug 05, 2023 |
| Dell          | Latitude E5440              | Notebook    | [f6981c56b7](https://linux-hardware.org/?probe=f6981c56b7) | Aug 05, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [9365c3de56](https://linux-hardware.org/?probe=9365c3de56) | Aug 05, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [78566a197e](https://linux-hardware.org/?probe=78566a197e) | Aug 05, 2023 |
| Lenovo        | IdeaPadFlex 5 15ALC05 82... | Convertible | [2f2d909df8](https://linux-hardware.org/?probe=2f2d909df8) | Aug 05, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [c4d1667ffe](https://linux-hardware.org/?probe=c4d1667ffe) | Aug 05, 2023 |
| ASRock        | P67 Pro3                    | Desktop     | [da235e8c08](https://linux-hardware.org/?probe=da235e8c08) | Aug 05, 2023 |
| Dell          | Inspiron 14-3462            | Notebook    | [9300232981](https://linux-hardware.org/?probe=9300232981) | Aug 05, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [64810e5a10](https://linux-hardware.org/?probe=64810e5a10) | Aug 05, 2023 |
| ASRock        | B550 PG Velocita            | Desktop     | [71ca443602](https://linux-hardware.org/?probe=71ca443602) | Aug 05, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [f1e284ec93](https://linux-hardware.org/?probe=f1e284ec93) | Aug 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [5799f1a89c](https://linux-hardware.org/?probe=5799f1a89c) | Aug 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [058011da0f](https://linux-hardware.org/?probe=058011da0f) | Aug 04, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [87ecdcb4bd](https://linux-hardware.org/?probe=87ecdcb4bd) | Aug 04, 2023 |
| HP            | 83E8                        | Desktop     | [0d285189b9](https://linux-hardware.org/?probe=0d285189b9) | Aug 04, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [59dda0e2b7](https://linux-hardware.org/?probe=59dda0e2b7) | Aug 04, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [bd2d5f588f](https://linux-hardware.org/?probe=bd2d5f588f) | Aug 04, 2023 |
| HP            | Notebook                    | Notebook    | [9b9a2bd44a](https://linux-hardware.org/?probe=9b9a2bd44a) | Aug 04, 2023 |
| PC Special... | Lafite Pro III 17           | Notebook    | [702cdf4138](https://linux-hardware.org/?probe=702cdf4138) | Aug 03, 2023 |
| Gigabyte      | Z490M GAMING X              | Desktop     | [ad51d2548b](https://linux-hardware.org/?probe=ad51d2548b) | Aug 03, 2023 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | Notebook    | [a251ad988c](https://linux-hardware.org/?probe=a251ad988c) | Aug 03, 2023 |
| Acer          | Predator PHN16-71           | Notebook    | [1d1937f1d6](https://linux-hardware.org/?probe=1d1937f1d6) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [986cf08dc9](https://linux-hardware.org/?probe=986cf08dc9) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [da8d764a97](https://linux-hardware.org/?probe=da8d764a97) | Aug 03, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [c96666b80d](https://linux-hardware.org/?probe=c96666b80d) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [67d851300e](https://linux-hardware.org/?probe=67d851300e) | Aug 03, 2023 |
| Timi          | A7S                         | Notebook    | [7de693ff63](https://linux-hardware.org/?probe=7de693ff63) | Aug 03, 2023 |
| LG Electro... | 16Z90R-K.ADB9U1             | Notebook    | [d3a9e05559](https://linux-hardware.org/?probe=d3a9e05559) | Aug 02, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [5c8ad99a3c](https://linux-hardware.org/?probe=5c8ad99a3c) | Aug 02, 2023 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [2703b03104](https://linux-hardware.org/?probe=2703b03104) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [32d205bbdf](https://linux-hardware.org/?probe=32d205bbdf) | Aug 02, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [bdccf9a3db](https://linux-hardware.org/?probe=bdccf9a3db) | Aug 01, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | Notebook    | [6cfc0b2281](https://linux-hardware.org/?probe=6cfc0b2281) | Aug 01, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | Desktop     | [28f1074e0a](https://linux-hardware.org/?probe=28f1074e0a) | Aug 01, 2023 |
| Packard Be... | EasyNote TJ65               | Notebook    | [e5193cc5d3](https://linux-hardware.org/?probe=e5193cc5d3) | Aug 01, 2023 |
| HUAWEI        | KPR-WX9                     | Notebook    | [8918c544fe](https://linux-hardware.org/?probe=8918c544fe) | Aug 01, 2023 |
| Dell          | Latitude 5590               | Notebook    | [466fdce7aa](https://linux-hardware.org/?probe=466fdce7aa) | Aug 01, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [cb322d77a4](https://linux-hardware.org/?probe=cb322d77a4) | Aug 01, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [35f27e05c6](https://linux-hardware.org/?probe=35f27e05c6) | Jul 31, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [af6a2cb993](https://linux-hardware.org/?probe=af6a2cb993) | Jul 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [f7be9307b1](https://linux-hardware.org/?probe=f7be9307b1) | Jul 31, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [91887235b2](https://linux-hardware.org/?probe=91887235b2) | Jul 31, 2023 |
| Dell          | G15 5511                    | Notebook    | [278d65cdc0](https://linux-hardware.org/?probe=278d65cdc0) | Jul 31, 2023 |
| Dell          | G15 5511                    | Notebook    | [e4570caa8f](https://linux-hardware.org/?probe=e4570caa8f) | Jul 31, 2023 |
| Dell          | Latitude E6400              | Notebook    | [5863677081](https://linux-hardware.org/?probe=5863677081) | Jul 31, 2023 |
| Lenovo        | ThinkPad P50s 20FLCTO1WW    | Notebook    | [1594795f9e](https://linux-hardware.org/?probe=1594795f9e) | Jul 31, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [264f400d7e](https://linux-hardware.org/?probe=264f400d7e) | Jul 30, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [e16ea772e1](https://linux-hardware.org/?probe=e16ea772e1) | Jul 30, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [28ff56233b](https://linux-hardware.org/?probe=28ff56233b) | Jul 30, 2023 |
| Dell          | Latitude 5421               | Notebook    | [3872b1f799](https://linux-hardware.org/?probe=3872b1f799) | Jul 30, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3JE0... | Notebook    | [5e1021c76b](https://linux-hardware.org/?probe=5e1021c76b) | Jul 30, 2023 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [3bbfa332c0](https://linux-hardware.org/?probe=3bbfa332c0) | Jul 30, 2023 |
| HP            | 843B                        | Desktop     | [c570a7c5f2](https://linux-hardware.org/?probe=c570a7c5f2) | Jul 29, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [e43da17360](https://linux-hardware.org/?probe=e43da17360) | Jul 29, 2023 |
| Razer         | Blade                       | Notebook    | [6c3ef3aa59](https://linux-hardware.org/?probe=6c3ef3aa59) | Jul 29, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [e4efeb0276](https://linux-hardware.org/?probe=e4efeb0276) | Jul 29, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [30e5e63466](https://linux-hardware.org/?probe=30e5e63466) | Jul 29, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3JE0... | Notebook    | [6426edf740](https://linux-hardware.org/?probe=6426edf740) | Jul 29, 2023 |
| HP            | ProBook 455R G6             | Notebook    | [3731e7465c](https://linux-hardware.org/?probe=3731e7465c) | Jul 29, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [8d3733b439](https://linux-hardware.org/?probe=8d3733b439) | Jul 29, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [28bd5d7d66](https://linux-hardware.org/?probe=28bd5d7d66) | Jul 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [a8e51655da](https://linux-hardware.org/?probe=a8e51655da) | Jul 28, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [d94c3cc0e8](https://linux-hardware.org/?probe=d94c3cc0e8) | Jul 28, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [aaa06048d5](https://linux-hardware.org/?probe=aaa06048d5) | Jul 28, 2023 |
| Acer          | Aspire A517-53              | Notebook    | [41c9602cac](https://linux-hardware.org/?probe=41c9602cac) | Jul 28, 2023 |
| Acer          | Aspire 5350                 | Notebook    | [698672b19c](https://linux-hardware.org/?probe=698672b19c) | Jul 28, 2023 |
| MSI           | Raider GE78HX 13VI          | Notebook    | [0b179ca997](https://linux-hardware.org/?probe=0b179ca997) | Jul 28, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [ea402f269e](https://linux-hardware.org/?probe=ea402f269e) | Jul 28, 2023 |
| Google        | Atlas                       | Notebook    | [c3f0326575](https://linux-hardware.org/?probe=c3f0326575) | Jul 28, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | Notebook    | [407859fa58](https://linux-hardware.org/?probe=407859fa58) | Jul 27, 2023 |
| HP            | ProBook 4530s               | Notebook    | [46852380f2](https://linux-hardware.org/?probe=46852380f2) | Jul 27, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [bf3f7b4c2d](https://linux-hardware.org/?probe=bf3f7b4c2d) | Jul 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [6546d49225](https://linux-hardware.org/?probe=6546d49225) | Jul 27, 2023 |
| HUAWEI        | KPR-WX9                     | Notebook    | [2231e66b3d](https://linux-hardware.org/?probe=2231e66b3d) | Jul 26, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [1bac11c715](https://linux-hardware.org/?probe=1bac11c715) | Jul 26, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [1409af2a38](https://linux-hardware.org/?probe=1409af2a38) | Jul 26, 2023 |
| Lenovo        | 13w Yoga 82S1               | Convertible | [3516b91dc0](https://linux-hardware.org/?probe=3516b91dc0) | Jul 26, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e79fd50f34](https://linux-hardware.org/?probe=e79fd50f34) | Jul 26, 2023 |
| MECHREVO      | F7BFD V1.0                  | Desktop     | [f9be0fc5a7](https://linux-hardware.org/?probe=f9be0fc5a7) | Jul 26, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [8c8e7f5edd](https://linux-hardware.org/?probe=8c8e7f5edd) | Jul 26, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [6c978ec74d](https://linux-hardware.org/?probe=6c978ec74d) | Jul 26, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [864fcc639d](https://linux-hardware.org/?probe=864fcc639d) | Jul 25, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [787270abee](https://linux-hardware.org/?probe=787270abee) | Jul 25, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [7910b0c067](https://linux-hardware.org/?probe=7910b0c067) | Jul 25, 2023 |
| ASUSTek       | ROG Flow X13 GV302XI_GV3... | Convertible | [a326770d26](https://linux-hardware.org/?probe=a326770d26) | Jul 25, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [5399a2e19e](https://linux-hardware.org/?probe=5399a2e19e) | Jul 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [412bc51f72](https://linux-hardware.org/?probe=412bc51f72) | Jul 24, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [e1fea727ff](https://linux-hardware.org/?probe=e1fea727ff) | Jul 24, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [6dbfb1d71e](https://linux-hardware.org/?probe=6dbfb1d71e) | Jul 24, 2023 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [b571da19fb](https://linux-hardware.org/?probe=b571da19fb) | Jul 24, 2023 |
| Gigabyte      | G5 KE                       | Notebook    | [4837040c2a](https://linux-hardware.org/?probe=4837040c2a) | Jul 24, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [cb7e913e03](https://linux-hardware.org/?probe=cb7e913e03) | Jul 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2ff464874e](https://linux-hardware.org/?probe=2ff464874e) | Jul 24, 2023 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [2a23928116](https://linux-hardware.org/?probe=2a23928116) | Jul 24, 2023 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [247870abec](https://linux-hardware.org/?probe=247870abec) | Jul 24, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [a2d73523d4](https://linux-hardware.org/?probe=a2d73523d4) | Jul 24, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [313f3aa210](https://linux-hardware.org/?probe=313f3aa210) | Jul 23, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [f1db825d10](https://linux-hardware.org/?probe=f1db825d10) | Jul 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [3bd5c9d59c](https://linux-hardware.org/?probe=3bd5c9d59c) | Jul 23, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [44958ef86b](https://linux-hardware.org/?probe=44958ef86b) | Jul 23, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [0e123e6d85](https://linux-hardware.org/?probe=0e123e6d85) | Jul 23, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [3dac76b45f](https://linux-hardware.org/?probe=3dac76b45f) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [4222b801a9](https://linux-hardware.org/?probe=4222b801a9) | Jul 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [ddb8dbe4e4](https://linux-hardware.org/?probe=ddb8dbe4e4) | Jul 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [82242fa0a6](https://linux-hardware.org/?probe=82242fa0a6) | Jul 23, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [a6e2f105ed](https://linux-hardware.org/?probe=a6e2f105ed) | Jul 23, 2023 |
| ECS           | A780LM-M2                   | Desktop     | [b8b1304632](https://linux-hardware.org/?probe=b8b1304632) | Jul 22, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [2b3d4271bf](https://linux-hardware.org/?probe=2b3d4271bf) | Jul 22, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [2f8efec736](https://linux-hardware.org/?probe=2f8efec736) | Jul 22, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [fdbe29a1db](https://linux-hardware.org/?probe=fdbe29a1db) | Jul 22, 2023 |
| Biostar       | A320MH                      | Desktop     | [b4ad5e7452](https://linux-hardware.org/?probe=b4ad5e7452) | Jul 22, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [45065697ac](https://linux-hardware.org/?probe=45065697ac) | Jul 22, 2023 |
| ASUSTek       | ROG STRIX Z790-I GAMING ... | Desktop     | [625e829a7e](https://linux-hardware.org/?probe=625e829a7e) | Jul 22, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [a96fbb9461](https://linux-hardware.org/?probe=a96fbb9461) | Jul 22, 2023 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [fd2bcebb1d](https://linux-hardware.org/?probe=fd2bcebb1d) | Jul 22, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [d47c43e734](https://linux-hardware.org/?probe=d47c43e734) | Jul 22, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [a55a67fa01](https://linux-hardware.org/?probe=a55a67fa01) | Jul 22, 2023 |
| Acer          | Aspire V5-551               | Notebook    | [8a13138f82](https://linux-hardware.org/?probe=8a13138f82) | Jul 21, 2023 |
| Lenovo        | ThinkPad X390 20SDA018CD    | Notebook    | [b2f5443fc2](https://linux-hardware.org/?probe=b2f5443fc2) | Jul 21, 2023 |
| Lenovo        | ThinkPad X390 20SDA018CD    | Notebook    | [3161baf648](https://linux-hardware.org/?probe=3161baf648) | Jul 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [55639a6416](https://linux-hardware.org/?probe=55639a6416) | Jul 21, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [478fb56a7d](https://linux-hardware.org/?probe=478fb56a7d) | Jul 21, 2023 |
| HP            | ProBook 4530s               | Notebook    | [450e93a8de](https://linux-hardware.org/?probe=450e93a8de) | Jul 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [8b2077101c](https://linux-hardware.org/?probe=8b2077101c) | Jul 21, 2023 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [daff830182](https://linux-hardware.org/?probe=daff830182) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [cc9f1fdcd8](https://linux-hardware.org/?probe=cc9f1fdcd8) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [fc0fcad674](https://linux-hardware.org/?probe=fc0fcad674) | Jul 21, 2023 |
| Dell          | Latitude 5580               | Notebook    | [f115a04168](https://linux-hardware.org/?probe=f115a04168) | Jul 20, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [cb2cdb1a94](https://linux-hardware.org/?probe=cb2cdb1a94) | Jul 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [9a2d353d76](https://linux-hardware.org/?probe=9a2d353d76) | Jul 20, 2023 |
| Panasonic     | CFSZ5-3                     | Notebook    | [9eb560d292](https://linux-hardware.org/?probe=9eb560d292) | Jul 20, 2023 |
| ASUSTek       | VC66                        | Desktop     | [369cd2ba96](https://linux-hardware.org/?probe=369cd2ba96) | Jul 20, 2023 |
| ASUSTek       | N501VW                      | Notebook    | [08cd5a81b2](https://linux-hardware.org/?probe=08cd5a81b2) | Jul 19, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [9b44d7bd03](https://linux-hardware.org/?probe=9b44d7bd03) | Jul 19, 2023 |
| MSI           | A88XM-E35 V2                | Desktop     | [7ab6252e08](https://linux-hardware.org/?probe=7ab6252e08) | Jul 19, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [db2a22c2eb](https://linux-hardware.org/?probe=db2a22c2eb) | Jul 19, 2023 |
| ASUSTek       | ZenBook UX562IA_UM562IA     | Convertible | [08b6a97698](https://linux-hardware.org/?probe=08b6a97698) | Jul 19, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [b12aa2eb63](https://linux-hardware.org/?probe=b12aa2eb63) | Jul 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [6623b71de2](https://linux-hardware.org/?probe=6623b71de2) | Jul 19, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [ab65cec6fe](https://linux-hardware.org/?probe=ab65cec6fe) | Jul 19, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [8a9fabbdc0](https://linux-hardware.org/?probe=8a9fabbdc0) | Jul 19, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [f145687601](https://linux-hardware.org/?probe=f145687601) | Jul 19, 2023 |
| AZW           | U59                         | Desktop     | [1c919967a8](https://linux-hardware.org/?probe=1c919967a8) | Jul 19, 2023 |
| Avell High... | B.ON                        | Notebook    | [bf1f683383](https://linux-hardware.org/?probe=bf1f683383) | Jul 18, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [3121fc5450](https://linux-hardware.org/?probe=3121fc5450) | Jul 18, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c5475d0982](https://linux-hardware.org/?probe=c5475d0982) | Jul 18, 2023 |
| ONDA          | A320SD4-ITX Ver:2.00        | Desktop     | [ffe435deca](https://linux-hardware.org/?probe=ffe435deca) | Jul 18, 2023 |
| ASRock        | X470 Gaming K4              | Desktop     | [7217058966](https://linux-hardware.org/?probe=7217058966) | Jul 18, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [e68c02f317](https://linux-hardware.org/?probe=e68c02f317) | Jul 18, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [02f8df2129](https://linux-hardware.org/?probe=02f8df2129) | Jul 18, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [e7e056881b](https://linux-hardware.org/?probe=e7e056881b) | Jul 18, 2023 |
| Lenovo        | B50-45 20388                | Notebook    | [54b4137669](https://linux-hardware.org/?probe=54b4137669) | Jul 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [50e78d6df5](https://linux-hardware.org/?probe=50e78d6df5) | Jul 18, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | Notebook    | [53c97d91d4](https://linux-hardware.org/?probe=53c97d91d4) | Jul 18, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [42eb1edbb6](https://linux-hardware.org/?probe=42eb1edbb6) | Jul 17, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [6bebb2e751](https://linux-hardware.org/?probe=6bebb2e751) | Jul 17, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [4e4d74fab5](https://linux-hardware.org/?probe=4e4d74fab5) | Jul 17, 2023 |
| Dell          | 0TY565                      | Desktop     | [1d6edab344](https://linux-hardware.org/?probe=1d6edab344) | Jul 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [13ba381894](https://linux-hardware.org/?probe=13ba381894) | Jul 17, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [b53aa427b9](https://linux-hardware.org/?probe=b53aa427b9) | Jul 17, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [5be1306636](https://linux-hardware.org/?probe=5be1306636) | Jul 17, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [2b81f8a707](https://linux-hardware.org/?probe=2b81f8a707) | Jul 17, 2023 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [98acac35e7](https://linux-hardware.org/?probe=98acac35e7) | Jul 17, 2023 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [de9a7deb3b](https://linux-hardware.org/?probe=de9a7deb3b) | Jul 17, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [c659d8d6b5](https://linux-hardware.org/?probe=c659d8d6b5) | Jul 17, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [8464b9ef50](https://linux-hardware.org/?probe=8464b9ef50) | Jul 17, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [15d7862757](https://linux-hardware.org/?probe=15d7862757) | Jul 16, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [5202874aa5](https://linux-hardware.org/?probe=5202874aa5) | Jul 16, 2023 |
| HP            | Pavilion 17                 | Notebook    | [7c39d851fd](https://linux-hardware.org/?probe=7c39d851fd) | Jul 16, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [3f15239dd2](https://linux-hardware.org/?probe=3f15239dd2) | Jul 16, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [cbab6d2236](https://linux-hardware.org/?probe=cbab6d2236) | Jul 16, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [01ed316904](https://linux-hardware.org/?probe=01ed316904) | Jul 16, 2023 |
| Lenovo        | M490s 20215                 | Notebook    | [d029f6cf0b](https://linux-hardware.org/?probe=d029f6cf0b) | Jul 16, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [a4bd524029](https://linux-hardware.org/?probe=a4bd524029) | Jul 15, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2f2887fc32](https://linux-hardware.org/?probe=2f2887fc32) | Jul 15, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [c36495481b](https://linux-hardware.org/?probe=c36495481b) | Jul 15, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [97e2731292](https://linux-hardware.org/?probe=97e2731292) | Jul 15, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [08dede9db3](https://linux-hardware.org/?probe=08dede9db3) | Jul 15, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [e204dc6cf1](https://linux-hardware.org/?probe=e204dc6cf1) | Jul 15, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [4dc6731c7a](https://linux-hardware.org/?probe=4dc6731c7a) | Jul 14, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [e32b594990](https://linux-hardware.org/?probe=e32b594990) | Jul 14, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [9868eab45f](https://linux-hardware.org/?probe=9868eab45f) | Jul 14, 2023 |
| Acer          | Swift SF313-52              | Notebook    | [3b393fc916](https://linux-hardware.org/?probe=3b393fc916) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [e042e7c94e](https://linux-hardware.org/?probe=e042e7c94e) | Jul 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [28b21d099f](https://linux-hardware.org/?probe=28b21d099f) | Jul 14, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [1f05cae239](https://linux-hardware.org/?probe=1f05cae239) | Jul 14, 2023 |
| Lenovo        | ThinkPad X260 20F5S4NR00    | Notebook    | [281c5a429c](https://linux-hardware.org/?probe=281c5a429c) | Jul 13, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [793289bc48](https://linux-hardware.org/?probe=793289bc48) | Jul 13, 2023 |
| ASUSTek       | STRIX Z270G GAMING          | Desktop     | [1857fae531](https://linux-hardware.org/?probe=1857fae531) | Jul 13, 2023 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [8a2aeb02b0](https://linux-hardware.org/?probe=8a2aeb02b0) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [934947072a](https://linux-hardware.org/?probe=934947072a) | Jul 13, 2023 |
| Acer          | TravelMate P246-MG          | Notebook    | [62348fa6ed](https://linux-hardware.org/?probe=62348fa6ed) | Jul 13, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [adab548264](https://linux-hardware.org/?probe=adab548264) | Jul 13, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [ce2deb4b1d](https://linux-hardware.org/?probe=ce2deb4b1d) | Jul 13, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [a9b5963254](https://linux-hardware.org/?probe=a9b5963254) | Jul 13, 2023 |
| Dell          | Latitude 7480               | Notebook    | [a375f7685c](https://linux-hardware.org/?probe=a375f7685c) | Jul 13, 2023 |
| Lenovo        | ThinkPad T550 20CJS0P300    | Notebook    | [2c96c19647](https://linux-hardware.org/?probe=2c96c19647) | Jul 13, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [23e018569e](https://linux-hardware.org/?probe=23e018569e) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [392b02a797](https://linux-hardware.org/?probe=392b02a797) | Jul 13, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [30403bcd32](https://linux-hardware.org/?probe=30403bcd32) | Jul 12, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [222924f1c2](https://linux-hardware.org/?probe=222924f1c2) | Jul 12, 2023 |
| Dell          | 051FJ8 A02                  | Desktop     | [d8310de68b](https://linux-hardware.org/?probe=d8310de68b) | Jul 12, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [7573efcc6c](https://linux-hardware.org/?probe=7573efcc6c) | Jul 12, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e2792f841d](https://linux-hardware.org/?probe=e2792f841d) | Jul 12, 2023 |
| ASUSTek       | Maximus VI EXTREME          | Desktop     | [ea9603099a](https://linux-hardware.org/?probe=ea9603099a) | Jul 12, 2023 |
| Lenovo        | ThinkPad A285 20MXS0JR14    | Notebook    | [08bbd89b8c](https://linux-hardware.org/?probe=08bbd89b8c) | Jul 11, 2023 |
| Lenovo        | ThinkPad A285 20MXS0JR14    | Notebook    | [23b123605f](https://linux-hardware.org/?probe=23b123605f) | Jul 11, 2023 |
| MSI           | Z170A PC MATE               | Desktop     | [39b5c3bb23](https://linux-hardware.org/?probe=39b5c3bb23) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [38f91b870c](https://linux-hardware.org/?probe=38f91b870c) | Jul 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b89cab90c0](https://linux-hardware.org/?probe=b89cab90c0) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [e0c7ec0cbc](https://linux-hardware.org/?probe=e0c7ec0cbc) | Jul 11, 2023 |
| Dell          | Precision M4700             | Notebook    | [69a672ec44](https://linux-hardware.org/?probe=69a672ec44) | Jul 11, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [477ec4d403](https://linux-hardware.org/?probe=477ec4d403) | Jul 11, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [380c2c8a9e](https://linux-hardware.org/?probe=380c2c8a9e) | Jul 11, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [eb024b5188](https://linux-hardware.org/?probe=eb024b5188) | Jul 10, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [54b445c5c1](https://linux-hardware.org/?probe=54b445c5c1) | Jul 10, 2023 |
| Acer          | SF714-52T                   | Notebook    | [97b079be51](https://linux-hardware.org/?probe=97b079be51) | Jul 10, 2023 |
| ASRock        | A75 Extreme6                | Desktop     | [1c0eb1b3ea](https://linux-hardware.org/?probe=1c0eb1b3ea) | Jul 10, 2023 |
| HP            | 1998                        | Desktop     | [03da98871c](https://linux-hardware.org/?probe=03da98871c) | Jul 10, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [de7dbebf49](https://linux-hardware.org/?probe=de7dbebf49) | Jul 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [42aaaa0acb](https://linux-hardware.org/?probe=42aaaa0acb) | Jul 09, 2023 |
| AYANEO        | AIR Pro                     | Tablet      | [90413e073a](https://linux-hardware.org/?probe=90413e073a) | Jul 09, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [ee5ef8132f](https://linux-hardware.org/?probe=ee5ef8132f) | Jul 09, 2023 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | Notebook    | [866af72fb6](https://linux-hardware.org/?probe=866af72fb6) | Jul 09, 2023 |
| ASRock        | B650 PG Lightning           | Desktop     | [86c4d26a95](https://linux-hardware.org/?probe=86c4d26a95) | Jul 09, 2023 |
| Lenovo        | Legion R9000X ARHA7 82UG    | Notebook    | [5da53d3f61](https://linux-hardware.org/?probe=5da53d3f61) | Jul 09, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [c01a765f59](https://linux-hardware.org/?probe=c01a765f59) | Jul 09, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [aa2805e577](https://linux-hardware.org/?probe=aa2805e577) | Jul 09, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [214dd1ad57](https://linux-hardware.org/?probe=214dd1ad57) | Jul 09, 2023 |
| ASUSTek       | ROG STRIX Z790-I GAMING ... | Desktop     | [a1b896bd04](https://linux-hardware.org/?probe=a1b896bd04) | Jul 09, 2023 |
| HP            | ProBook 6460b               | Notebook    | [af3006237f](https://linux-hardware.org/?probe=af3006237f) | Jul 09, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [3540170054](https://linux-hardware.org/?probe=3540170054) | Jul 08, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [6b4669ec61](https://linux-hardware.org/?probe=6b4669ec61) | Jul 08, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [87a1bbb5cc](https://linux-hardware.org/?probe=87a1bbb5cc) | Jul 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [72af2d01c0](https://linux-hardware.org/?probe=72af2d01c0) | Jul 08, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [3a64eabd9b](https://linux-hardware.org/?probe=3a64eabd9b) | Jul 08, 2023 |
| Positivo      | POS-PIG43BC SIM             | Desktop     | [42727a7888](https://linux-hardware.org/?probe=42727a7888) | Jul 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [dd8bd37036](https://linux-hardware.org/?probe=dd8bd37036) | Jul 08, 2023 |
| ASUSTek       | ZenBook UX564EH_Q528EH      | Convertible | [cbea798725](https://linux-hardware.org/?probe=cbea798725) | Jul 08, 2023 |
| ASUSTek       | ZenBook UX564EH_Q528EH      | Convertible | [af380bf3d8](https://linux-hardware.org/?probe=af380bf3d8) | Jul 07, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [6f3284cac3](https://linux-hardware.org/?probe=6f3284cac3) | Jul 07, 2023 |
| ASRockRack    | E3C236D4U                   | Desktop     | [83ed95f0d3](https://linux-hardware.org/?probe=83ed95f0d3) | Jul 07, 2023 |
| Purism        | Librem 14                   | Notebook    | [18db47d3f6](https://linux-hardware.org/?probe=18db47d3f6) | Jul 07, 2023 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [8f01854bc7](https://linux-hardware.org/?probe=8f01854bc7) | Jul 07, 2023 |
| Medion        | Erazer P7643 MD60299        | Notebook    | [2c74ffe58f](https://linux-hardware.org/?probe=2c74ffe58f) | Jul 07, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [8a0a97b362](https://linux-hardware.org/?probe=8a0a97b362) | Jul 07, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [2fd3eada0f](https://linux-hardware.org/?probe=2fd3eada0f) | Jul 07, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c199c7040b](https://linux-hardware.org/?probe=c199c7040b) | Jul 07, 2023 |
| Lenovo        | Legion R9000P2021 82JS      | Notebook    | [0376dd3cbd](https://linux-hardware.org/?probe=0376dd3cbd) | Jul 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [49c59b6c86](https://linux-hardware.org/?probe=49c59b6c86) | Jul 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [df2a737853](https://linux-hardware.org/?probe=df2a737853) | Jul 07, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [d908a5a02e](https://linux-hardware.org/?probe=d908a5a02e) | Jul 07, 2023 |
| HP            | ENVY 15                     | Notebook    | [d519c2699c](https://linux-hardware.org/?probe=d519c2699c) | Jul 06, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [cf134cbdd9](https://linux-hardware.org/?probe=cf134cbdd9) | Jul 06, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [40d2eef376](https://linux-hardware.org/?probe=40d2eef376) | Jul 06, 2023 |
| Dell          | G3 3590                     | Notebook    | [e3cfb2968a](https://linux-hardware.org/?probe=e3cfb2968a) | Jul 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [0fc498ccfb](https://linux-hardware.org/?probe=0fc498ccfb) | Jul 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [25ea01643a](https://linux-hardware.org/?probe=25ea01643a) | Jul 06, 2023 |
| ASUSTek       | G750JZA                     | Notebook    | [fb2477dd61](https://linux-hardware.org/?probe=fb2477dd61) | Jul 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [e5539c7298](https://linux-hardware.org/?probe=e5539c7298) | Jul 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [e17ab8bbe7](https://linux-hardware.org/?probe=e17ab8bbe7) | Jul 06, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [79bd04036c](https://linux-hardware.org/?probe=79bd04036c) | Jul 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [e555b073b5](https://linux-hardware.org/?probe=e555b073b5) | Jul 05, 2023 |
| Acer          | TravelMate P246-MG          | Notebook    | [e1e4548a49](https://linux-hardware.org/?probe=e1e4548a49) | Jul 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [b11fe33b8c](https://linux-hardware.org/?probe=b11fe33b8c) | Jul 05, 2023 |
| Dell          | G3 3590                     | Notebook    | [35906fded9](https://linux-hardware.org/?probe=35906fded9) | Jul 05, 2023 |
| Dell          | Latitude 7350               | Notebook    | [bc00420bfc](https://linux-hardware.org/?probe=bc00420bfc) | Jul 05, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a4b93f17c2](https://linux-hardware.org/?probe=a4b93f17c2) | Jul 05, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [3cf621f13b](https://linux-hardware.org/?probe=3cf621f13b) | Jul 05, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [eb325b1c2a](https://linux-hardware.org/?probe=eb325b1c2a) | Jul 04, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [c387c4fbf1](https://linux-hardware.org/?probe=c387c4fbf1) | Jul 04, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [5699e37170](https://linux-hardware.org/?probe=5699e37170) | Jul 04, 2023 |
| Dell          | Latitude 7350               | Notebook    | [14d41ff667](https://linux-hardware.org/?probe=14d41ff667) | Jul 04, 2023 |
| ASUSTek       | G750JZA                     | Notebook    | [72fc73822c](https://linux-hardware.org/?probe=72fc73822c) | Jul 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [4b2cf13c22](https://linux-hardware.org/?probe=4b2cf13c22) | Jul 03, 2023 |
| HP            | 3047h                       | Desktop     | [7dfd0078f7](https://linux-hardware.org/?probe=7dfd0078f7) | Jul 03, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [7ee43d9cad](https://linux-hardware.org/?probe=7ee43d9cad) | Jul 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [90b6b19a97](https://linux-hardware.org/?probe=90b6b19a97) | Jul 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [25d3329df1](https://linux-hardware.org/?probe=25d3329df1) | Jul 03, 2023 |
| ASUSTek       | 1015BX                      | Notebook    | [c4bc43a932](https://linux-hardware.org/?probe=c4bc43a932) | Jul 03, 2023 |
| Huanan        | H610M-PLUS V1.2             | Desktop     | [0bc6a5e828](https://linux-hardware.org/?probe=0bc6a5e828) | Jul 03, 2023 |
| HP            | Elite x2 G4                 | Tablet      | [ae4fa28fb5](https://linux-hardware.org/?probe=ae4fa28fb5) | Jul 03, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [5af51ee197](https://linux-hardware.org/?probe=5af51ee197) | Jul 03, 2023 |
| MSI           | Z590 PRO WIFI               | Desktop     | [4fb1a41361](https://linux-hardware.org/?probe=4fb1a41361) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [364082f281](https://linux-hardware.org/?probe=364082f281) | Jul 03, 2023 |
| Pegatron      | 2AD3                        | Desktop     | [fd445e9894](https://linux-hardware.org/?probe=fd445e9894) | Jul 02, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [da24c07da6](https://linux-hardware.org/?probe=da24c07da6) | Jul 02, 2023 |
| ASRock        | B550M PG Riptide            | Desktop     | [e578144ebb](https://linux-hardware.org/?probe=e578144ebb) | Jul 02, 2023 |
| Lenovo        | ThinkPad T520 4243B65       | Notebook    | [07584ce70c](https://linux-hardware.org/?probe=07584ce70c) | Jul 02, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [47654b63c6](https://linux-hardware.org/?probe=47654b63c6) | Jul 02, 2023 |
| ASRock        | B550M PG Riptide            | Desktop     | [83fd2dc626](https://linux-hardware.org/?probe=83fd2dc626) | Jul 02, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [5c3eb7ce7c](https://linux-hardware.org/?probe=5c3eb7ce7c) | Jul 02, 2023 |
| Lenovo        | ThinkPad T410 2537PW4       | Notebook    | [10079a3e26](https://linux-hardware.org/?probe=10079a3e26) | Jul 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [556867d0f2](https://linux-hardware.org/?probe=556867d0f2) | Jul 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [b36612c9e4](https://linux-hardware.org/?probe=b36612c9e4) | Jul 02, 2023 |
| Lenovo        | ThinkPad T530 2429AA9       | Notebook    | [708fe309bc](https://linux-hardware.org/?probe=708fe309bc) | Jul 02, 2023 |
| Lex BayTra... | 2I380D                      | Notebook    | [d69c578d83](https://linux-hardware.org/?probe=d69c578d83) | Jul 02, 2023 |
| Lex BayTra... | 2I380D                      | Notebook    | [2e20df184f](https://linux-hardware.org/?probe=2e20df184f) | Jul 02, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [b4e7dadba8](https://linux-hardware.org/?probe=b4e7dadba8) | Jul 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [9e65cd9bd1](https://linux-hardware.org/?probe=9e65cd9bd1) | Jul 02, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [07f04b7377](https://linux-hardware.org/?probe=07f04b7377) | Jul 01, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [65c2a81637](https://linux-hardware.org/?probe=65c2a81637) | Jul 01, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [a57586f69b](https://linux-hardware.org/?probe=a57586f69b) | Jul 01, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [998267633e](https://linux-hardware.org/?probe=998267633e) | Jul 01, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [b49269ab3c](https://linux-hardware.org/?probe=b49269ab3c) | Jul 01, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [2ba1cce30e](https://linux-hardware.org/?probe=2ba1cce30e) | Jul 01, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | Desktop     | [f50a86955f](https://linux-hardware.org/?probe=f50a86955f) | Jul 01, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [9f1aec7e08](https://linux-hardware.org/?probe=9f1aec7e08) | Jul 01, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [36fed79d81](https://linux-hardware.org/?probe=36fed79d81) | Jul 01, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [ceb2b4c1c5](https://linux-hardware.org/?probe=ceb2b4c1c5) | Jun 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ef49f25cf8](https://linux-hardware.org/?probe=ef49f25cf8) | Jun 30, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [a3c2f0155c](https://linux-hardware.org/?probe=a3c2f0155c) | Jun 30, 2023 |
| Lenovo        | ThinkPad E490 20N80017RT    | Notebook    | [a2a1011725](https://linux-hardware.org/?probe=a2a1011725) | Jun 30, 2023 |
| Chuwi         | CoreBook XPro               | Notebook    | [501d899938](https://linux-hardware.org/?probe=501d899938) | Jun 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [31db4fffd0](https://linux-hardware.org/?probe=31db4fffd0) | Jun 30, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [6c6741deb9](https://linux-hardware.org/?probe=6c6741deb9) | Jun 30, 2023 |
| Dell          | Latitude E5440              | Notebook    | [1fd8c9652a](https://linux-hardware.org/?probe=1fd8c9652a) | Jun 30, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [45d5903c62](https://linux-hardware.org/?probe=45d5903c62) | Jun 30, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [5a88d6945d](https://linux-hardware.org/?probe=5a88d6945d) | Jun 29, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [a33602b335](https://linux-hardware.org/?probe=a33602b335) | Jun 29, 2023 |
| Lenovo        | 3000 G530 4151/200          | Notebook    | [f3482421c4](https://linux-hardware.org/?probe=f3482421c4) | Jun 29, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [06212dc183](https://linux-hardware.org/?probe=06212dc183) | Jun 29, 2023 |
| Acer          | Aspire XC-830               | Desktop     | [eccf186dfd](https://linux-hardware.org/?probe=eccf186dfd) | Jun 29, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [56e2b61337](https://linux-hardware.org/?probe=56e2b61337) | Jun 29, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [86866241cd](https://linux-hardware.org/?probe=86866241cd) | Jun 29, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [722b0302f4](https://linux-hardware.org/?probe=722b0302f4) | Jun 29, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | Notebook    | [9814b54843](https://linux-hardware.org/?probe=9814b54843) | Jun 29, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | Notebook    | [5b82e1dd39](https://linux-hardware.org/?probe=5b82e1dd39) | Jun 29, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [363067c171](https://linux-hardware.org/?probe=363067c171) | Jun 29, 2023 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | Notebook    | [b62328e801](https://linux-hardware.org/?probe=b62328e801) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TN34... | Convertible | [c6402add6a](https://linux-hardware.org/?probe=c6402add6a) | Jun 28, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 3 ... | Convertible | [d6d67cffd3](https://linux-hardware.org/?probe=d6d67cffd3) | Jun 28, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [971852cb38](https://linux-hardware.org/?probe=971852cb38) | Jun 28, 2023 |
| TUXEDO        | Polaris AMD Gen2 (REN)      | Notebook    | [18847b167a](https://linux-hardware.org/?probe=18847b167a) | Jun 28, 2023 |
| Dell          | 0PC5F7 A01                  | Desktop     | [133ed5cc64](https://linux-hardware.org/?probe=133ed5cc64) | Jun 28, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [238e77122e](https://linux-hardware.org/?probe=238e77122e) | Jun 28, 2023 |
| COLORFUL      | X16 Pro 23                  | Notebook    | [656cf52198](https://linux-hardware.org/?probe=656cf52198) | Jun 28, 2023 |
| Acer          | Veriton M490G               | Desktop     | [1f3da6e87f](https://linux-hardware.org/?probe=1f3da6e87f) | Jun 28, 2023 |
| MSI           | S3361                       | Server      | [81c0a2f5b6](https://linux-hardware.org/?probe=81c0a2f5b6) | Jun 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [cd0c241308](https://linux-hardware.org/?probe=cd0c241308) | Jun 28, 2023 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [6615a04065](https://linux-hardware.org/?probe=6615a04065) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c9cbb8f947](https://linux-hardware.org/?probe=c9cbb8f947) | Jun 27, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [48b0ff43fa](https://linux-hardware.org/?probe=48b0ff43fa) | Jun 27, 2023 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [c0af461776](https://linux-hardware.org/?probe=c0af461776) | Jun 27, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [47451d9f30](https://linux-hardware.org/?probe=47451d9f30) | Jun 27, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | Notebook    | [70cbf738e8](https://linux-hardware.org/?probe=70cbf738e8) | Jun 27, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [474833dcec](https://linux-hardware.org/?probe=474833dcec) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [85c3968edc](https://linux-hardware.org/?probe=85c3968edc) | Jun 26, 2023 |
| HP            | 18E7                        | Desktop     | [1ae4c92b7f](https://linux-hardware.org/?probe=1ae4c92b7f) | Jun 26, 2023 |
| Gigabyte      | AERO 15 KD                  | Notebook    | [1a17b8ee06](https://linux-hardware.org/?probe=1a17b8ee06) | Jun 26, 2023 |
| Gigabyte      | AERO 15 KD                  | Notebook    | [2fd779cefc](https://linux-hardware.org/?probe=2fd779cefc) | Jun 26, 2023 |
| Dell          | Precision 5570              | Notebook    | [dbf68aa669](https://linux-hardware.org/?probe=dbf68aa669) | Jun 26, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [ef2e8da48a](https://linux-hardware.org/?probe=ef2e8da48a) | Jun 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [00cf0b0faa](https://linux-hardware.org/?probe=00cf0b0faa) | Jun 26, 2023 |
| Dell          | XPS 9315                    | Notebook    | [41bb8bd332](https://linux-hardware.org/?probe=41bb8bd332) | Jun 25, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [94fe70521f](https://linux-hardware.org/?probe=94fe70521f) | Jun 25, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | Notebook    | [ba30e1369c](https://linux-hardware.org/?probe=ba30e1369c) | Jun 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8b0180f4d4](https://linux-hardware.org/?probe=8b0180f4d4) | Jun 25, 2023 |
| ASUSTek       | N501VW                      | Notebook    | [7513f535f9](https://linux-hardware.org/?probe=7513f535f9) | Jun 25, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [aa75d0dace](https://linux-hardware.org/?probe=aa75d0dace) | Jun 25, 2023 |
| Notebook      | PCX0DX                      | Notebook    | [d02e6a9fa6](https://linux-hardware.org/?probe=d02e6a9fa6) | Jun 25, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [2b4069db98](https://linux-hardware.org/?probe=2b4069db98) | Jun 25, 2023 |
| MSI           | GS63 7RD                    | Notebook    | [310191e110](https://linux-hardware.org/?probe=310191e110) | Jun 24, 2023 |
| HONOR         | GLO-GXXX                    | Notebook    | [0e22fb1d65](https://linux-hardware.org/?probe=0e22fb1d65) | Jun 24, 2023 |
| ASRock        | H55M                        | Desktop     | [cb9e89e20e](https://linux-hardware.org/?probe=cb9e89e20e) | Jun 24, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [dcfef21d2b](https://linux-hardware.org/?probe=dcfef21d2b) | Jun 24, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [62d08bd4ca](https://linux-hardware.org/?probe=62d08bd4ca) | Jun 24, 2023 |
| Dell          | Precision 3581              | Notebook    | [2e960d89db](https://linux-hardware.org/?probe=2e960d89db) | Jun 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2faa400326](https://linux-hardware.org/?probe=2faa400326) | Jun 23, 2023 |
| Gigabyte      | G1.Sniper Z87               | Desktop     | [8df9a683cb](https://linux-hardware.org/?probe=8df9a683cb) | Jun 23, 2023 |
| Gigabyte      | G1.Sniper Z87               | Desktop     | [4d419c5b63](https://linux-hardware.org/?probe=4d419c5b63) | Jun 23, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [56208916c9](https://linux-hardware.org/?probe=56208916c9) | Jun 23, 2023 |
| Dell          | Inspiron 5406 2n1           | Convertible | [4430ccf679](https://linux-hardware.org/?probe=4430ccf679) | Jun 23, 2023 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | Desktop     | [4cfd97f850](https://linux-hardware.org/?probe=4cfd97f850) | Jun 23, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | Notebook    | [856acf81ed](https://linux-hardware.org/?probe=856acf81ed) | Jun 22, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [83d89a8751](https://linux-hardware.org/?probe=83d89a8751) | Jun 22, 2023 |
| Lenovo        | 3717 SDK0R32862 WIN 3258... | Desktop     | [7bf78e33d4](https://linux-hardware.org/?probe=7bf78e33d4) | Jun 22, 2023 |
| IP3 Techno... | ACB19                       | Mini pc     | [db5c45e4f7](https://linux-hardware.org/?probe=db5c45e4f7) | Jun 22, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [e8391a9f3d](https://linux-hardware.org/?probe=e8391a9f3d) | Jun 22, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | Notebook    | [928f167dee](https://linux-hardware.org/?probe=928f167dee) | Jun 22, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [cbf5b19c76](https://linux-hardware.org/?probe=cbf5b19c76) | Jun 21, 2023 |
| Casper        | EXCALIBUR G770              | Notebook    | [9fef8732b6](https://linux-hardware.org/?probe=9fef8732b6) | Jun 21, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [baab7764b1](https://linux-hardware.org/?probe=baab7764b1) | Jun 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [26a3b9b3e9](https://linux-hardware.org/?probe=26a3b9b3e9) | Jun 21, 2023 |
| HP            | 21EF                        | Desktop     | [6022eb31ff](https://linux-hardware.org/?probe=6022eb31ff) | Jun 21, 2023 |
| Dell          | Inspiron 5737               | Notebook    | [a7e4d1a6bd](https://linux-hardware.org/?probe=a7e4d1a6bd) | Jun 21, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [e67932c5a0](https://linux-hardware.org/?probe=e67932c5a0) | Jun 21, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [ae2beb307a](https://linux-hardware.org/?probe=ae2beb307a) | Jun 20, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [c2c2365360](https://linux-hardware.org/?probe=c2c2365360) | Jun 20, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [092370b958](https://linux-hardware.org/?probe=092370b958) | Jun 20, 2023 |
| Acer          | Nitro AN517-51              | Notebook    | [b4423e6ac2](https://linux-hardware.org/?probe=b4423e6ac2) | Jun 20, 2023 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | Notebook    | [dd152b03bc](https://linux-hardware.org/?probe=dd152b03bc) | Jun 20, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [3375eaaeb3](https://linux-hardware.org/?probe=3375eaaeb3) | Jun 20, 2023 |
| Lenovo        | ThinkPad T590 20N5S14V00    | Notebook    | [6f81cc6d57](https://linux-hardware.org/?probe=6f81cc6d57) | Jun 19, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [9e30c629f3](https://linux-hardware.org/?probe=9e30c629f3) | Jun 19, 2023 |
| HASEE Comp... | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [2c0be5d314](https://linux-hardware.org/?probe=2c0be5d314) | Jun 19, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [5bd2521f5c](https://linux-hardware.org/?probe=5bd2521f5c) | Jun 19, 2023 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [0f15219a46](https://linux-hardware.org/?probe=0f15219a46) | Jun 19, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | Notebook    | [6a63f44627](https://linux-hardware.org/?probe=6a63f44627) | Jun 19, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [e9865c622f](https://linux-hardware.org/?probe=e9865c622f) | Jun 19, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [dcd3e79cb1](https://linux-hardware.org/?probe=dcd3e79cb1) | Jun 18, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [c1472b1c25](https://linux-hardware.org/?probe=c1472b1c25) | Jun 18, 2023 |
| Intel         | NUC5PPYB H76558-108         | Mini pc     | [1d1386c5e2](https://linux-hardware.org/?probe=1d1386c5e2) | Jun 18, 2023 |
| MSI           | Z97-G45 GAMING              | Desktop     | [cb20c2c912](https://linux-hardware.org/?probe=cb20c2c912) | Jun 18, 2023 |
| Acer          | Veriton M490G               | Desktop     | [f9405b8bd2](https://linux-hardware.org/?probe=f9405b8bd2) | Jun 18, 2023 |
| Lenovo        | ThinkPad X230 2324CD1       | Notebook    | [9ee6ed4144](https://linux-hardware.org/?probe=9ee6ed4144) | Jun 18, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [26e276dc29](https://linux-hardware.org/?probe=26e276dc29) | Jun 18, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [978e506718](https://linux-hardware.org/?probe=978e506718) | Jun 18, 2023 |
| Dell          | Latitude E7440              | Notebook    | [60d14fe6ab](https://linux-hardware.org/?probe=60d14fe6ab) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [94999d2965](https://linux-hardware.org/?probe=94999d2965) | Jun 18, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [676efbb266](https://linux-hardware.org/?probe=676efbb266) | Jun 18, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [9b5c44b13a](https://linux-hardware.org/?probe=9b5c44b13a) | Jun 17, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [d5ba369651](https://linux-hardware.org/?probe=d5ba369651) | Jun 17, 2023 |
| HP            | Pavilion dv7                | Notebook    | [f010c487a1](https://linux-hardware.org/?probe=f010c487a1) | Jun 17, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [6294c25695](https://linux-hardware.org/?probe=6294c25695) | Jun 17, 2023 |
| Acer          | Nitro AN517-51              | Notebook    | [d2f2f70083](https://linux-hardware.org/?probe=d2f2f70083) | Jun 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0d47dc3760](https://linux-hardware.org/?probe=0d47dc3760) | Jun 16, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | Notebook    | [bfa70344e3](https://linux-hardware.org/?probe=bfa70344e3) | Jun 16, 2023 |
| Samsung       | 750XDA                      | Notebook    | [e04dd13d49](https://linux-hardware.org/?probe=e04dd13d49) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [c338e10965](https://linux-hardware.org/?probe=c338e10965) | Jun 16, 2023 |
| Samsung       | 930QCG                      | Convertible | [339858c7c7](https://linux-hardware.org/?probe=339858c7c7) | Jun 16, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [176973d157](https://linux-hardware.org/?probe=176973d157) | Jun 16, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [1150629ceb](https://linux-hardware.org/?probe=1150629ceb) | Jun 16, 2023 |
| Lenovo        | ThinkPad E480 20KNA047CD    | Notebook    | [918de7de03](https://linux-hardware.org/?probe=918de7de03) | Jun 16, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [ae9d05ff3a](https://linux-hardware.org/?probe=ae9d05ff3a) | Jun 15, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [67b278ea0e](https://linux-hardware.org/?probe=67b278ea0e) | Jun 15, 2023 |
| Acer          | Aspire XC-830               | Desktop     | [ca0cba861a](https://linux-hardware.org/?probe=ca0cba861a) | Jun 15, 2023 |
| Lenovo        | ThinkPad T495 20NKS0TG00    | Notebook    | [628c8fb554](https://linux-hardware.org/?probe=628c8fb554) | Jun 15, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [a6f63a08e2](https://linux-hardware.org/?probe=a6f63a08e2) | Jun 15, 2023 |
| Microsoft     | Surface Laptop              | Tablet      | [2111a059f3](https://linux-hardware.org/?probe=2111a059f3) | Jun 15, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [66cc56555d](https://linux-hardware.org/?probe=66cc56555d) | Jun 15, 2023 |
| Lenovo        | ThinkPad L420 78545EG       | Notebook    | [bb42ee1009](https://linux-hardware.org/?probe=bb42ee1009) | Jun 14, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [535950bae5](https://linux-hardware.org/?probe=535950bae5) | Jun 14, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [c05a02e77b](https://linux-hardware.org/?probe=c05a02e77b) | Jun 14, 2023 |
| ASUSTek       | P553UA                      | Notebook    | [2543eb4ce8](https://linux-hardware.org/?probe=2543eb4ce8) | Jun 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b548786e27](https://linux-hardware.org/?probe=b548786e27) | Jun 13, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [928063a305](https://linux-hardware.org/?probe=928063a305) | Jun 13, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | Desktop     | [f0f0a1b2ac](https://linux-hardware.org/?probe=f0f0a1b2ac) | Jun 13, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [20c6793733](https://linux-hardware.org/?probe=20c6793733) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [d2e4302f28](https://linux-hardware.org/?probe=d2e4302f28) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [e858489484](https://linux-hardware.org/?probe=e858489484) | Jun 13, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [74b5d0e60a](https://linux-hardware.org/?probe=74b5d0e60a) | Jun 13, 2023 |
| Dell          | Inspiron 7786               | Convertible | [d6fa177357](https://linux-hardware.org/?probe=d6fa177357) | Jun 12, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [0fe4687002](https://linux-hardware.org/?probe=0fe4687002) | Jun 12, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [bac6eb2f16](https://linux-hardware.org/?probe=bac6eb2f16) | Jun 12, 2023 |
| Dell          | Inspiron 7786               | Convertible | [afd9c5a18f](https://linux-hardware.org/?probe=afd9c5a18f) | Jun 12, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [6fcdcaa48c](https://linux-hardware.org/?probe=6fcdcaa48c) | Jun 12, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [7082d05ede](https://linux-hardware.org/?probe=7082d05ede) | Jun 12, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [5678f7fb1f](https://linux-hardware.org/?probe=5678f7fb1f) | Jun 12, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [41526d21bc](https://linux-hardware.org/?probe=41526d21bc) | Jun 12, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [6154060edd](https://linux-hardware.org/?probe=6154060edd) | Jun 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [2aaa4324d0](https://linux-hardware.org/?probe=2aaa4324d0) | Jun 12, 2023 |
| Acer          | Veriton M490G               | Desktop     | [78ff85b0a4](https://linux-hardware.org/?probe=78ff85b0a4) | Jun 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [b88dfc7e5c](https://linux-hardware.org/?probe=b88dfc7e5c) | Jun 11, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [8bc28cc12c](https://linux-hardware.org/?probe=8bc28cc12c) | Jun 11, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | Notebook    | [ba129cd52d](https://linux-hardware.org/?probe=ba129cd52d) | Jun 11, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [67867c022f](https://linux-hardware.org/?probe=67867c022f) | Jun 11, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [e7d498373d](https://linux-hardware.org/?probe=e7d498373d) | Jun 11, 2023 |
| Medion        | E2291                       | Convertible | [4e834d645d](https://linux-hardware.org/?probe=4e834d645d) | Jun 11, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [7a081b66af](https://linux-hardware.org/?probe=7a081b66af) | Jun 11, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [4ecff82426](https://linux-hardware.org/?probe=4ecff82426) | Jun 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [0d80451f80](https://linux-hardware.org/?probe=0d80451f80) | Jun 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [b25c3a4ecb](https://linux-hardware.org/?probe=b25c3a4ecb) | Jun 11, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [823925da4a](https://linux-hardware.org/?probe=823925da4a) | Jun 11, 2023 |
| NEC Comput... | PC-LM550LS6R                | Notebook    | [695f9825a6](https://linux-hardware.org/?probe=695f9825a6) | Jun 11, 2023 |
| Dell          | Latitude E5470              | Notebook    | [cc81f6c74c](https://linux-hardware.org/?probe=cc81f6c74c) | Jun 11, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [80bc2607fb](https://linux-hardware.org/?probe=80bc2607fb) | Jun 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [57f37d5836](https://linux-hardware.org/?probe=57f37d5836) | Jun 10, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [0b0c11a052](https://linux-hardware.org/?probe=0b0c11a052) | Jun 09, 2023 |
| Gigabyte      | B460M DS3H                  | Desktop     | [63c9d6c822](https://linux-hardware.org/?probe=63c9d6c822) | Jun 09, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | Notebook    | [a165849009](https://linux-hardware.org/?probe=a165849009) | Jun 09, 2023 |
| Dell          | Latitude E5470              | Notebook    | [c9b909273b](https://linux-hardware.org/?probe=c9b909273b) | Jun 09, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | Notebook    | [05c07442a3](https://linux-hardware.org/?probe=05c07442a3) | Jun 09, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [61a0a2ea5f](https://linux-hardware.org/?probe=61a0a2ea5f) | Jun 09, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [8b8c6949b6](https://linux-hardware.org/?probe=8b8c6949b6) | Jun 09, 2023 |
| HP            | 14                          | Notebook    | [1540a787fb](https://linux-hardware.org/?probe=1540a787fb) | Jun 09, 2023 |
| HP            | 14                          | Notebook    | [1404218cab](https://linux-hardware.org/?probe=1404218cab) | Jun 09, 2023 |
| Dell          | XPS 17 9730                 | Notebook    | [bb7335618d](https://linux-hardware.org/?probe=bb7335618d) | Jun 08, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [fc60082dfe](https://linux-hardware.org/?probe=fc60082dfe) | Jun 08, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [5861bc7cef](https://linux-hardware.org/?probe=5861bc7cef) | Jun 08, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [97d002b53a](https://linux-hardware.org/?probe=97d002b53a) | Jun 08, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [ba4bfc1fe1](https://linux-hardware.org/?probe=ba4bfc1fe1) | Jun 08, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [5533070ec1](https://linux-hardware.org/?probe=5533070ec1) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [19c6b51f80](https://linux-hardware.org/?probe=19c6b51f80) | Jun 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [3cfa2bccb7](https://linux-hardware.org/?probe=3cfa2bccb7) | Jun 08, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [ac292cca00](https://linux-hardware.org/?probe=ac292cca00) | Jun 08, 2023 |
| ASRock        | H81M-VG4                    | Desktop     | [04d84e44a5](https://linux-hardware.org/?probe=04d84e44a5) | Jun 08, 2023 |
| Fujitsu       | FMVNA4NE-                   | Notebook    | [59c8fdd841](https://linux-hardware.org/?probe=59c8fdd841) | Jun 08, 2023 |
| Dell          | G15 5520                    | Notebook    | [2410d016d6](https://linux-hardware.org/?probe=2410d016d6) | Jun 08, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Convertible | [41dea00814](https://linux-hardware.org/?probe=41dea00814) | Jun 08, 2023 |
| Google        | Edgar                       | Notebook    | [bec197cb98](https://linux-hardware.org/?probe=bec197cb98) | Jun 07, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [e7cdd7e89b](https://linux-hardware.org/?probe=e7cdd7e89b) | Jun 07, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [45cc99775f](https://linux-hardware.org/?probe=45cc99775f) | Jun 07, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [9529a983b8](https://linux-hardware.org/?probe=9529a983b8) | Jun 07, 2023 |
| HP            | 3396                        | Desktop     | [ca540b449f](https://linux-hardware.org/?probe=ca540b449f) | Jun 07, 2023 |
| Lenovo        | Yoga 500-14ISK 80R5         | Notebook    | [2b1a1d3e39](https://linux-hardware.org/?probe=2b1a1d3e39) | Jun 07, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [05d49007a4](https://linux-hardware.org/?probe=05d49007a4) | Jun 07, 2023 |
| Lenovo        | Yoga 500-14ISK 80R5         | Notebook    | [3308d91565](https://linux-hardware.org/?probe=3308d91565) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [1f4ef72dbd](https://linux-hardware.org/?probe=1f4ef72dbd) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [78f12c4671](https://linux-hardware.org/?probe=78f12c4671) | Jun 07, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [db7f17cbe1](https://linux-hardware.org/?probe=db7f17cbe1) | Jun 07, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [9636ea4dc5](https://linux-hardware.org/?probe=9636ea4dc5) | Jun 07, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [aab84214f1](https://linux-hardware.org/?probe=aab84214f1) | Jun 06, 2023 |
| Dell          | Latitude 5480               | Notebook    | [dd2fef35ee](https://linux-hardware.org/?probe=dd2fef35ee) | Jun 06, 2023 |
| Dell          | Latitude 5480               | Notebook    | [7917512387](https://linux-hardware.org/?probe=7917512387) | Jun 06, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [662e292b55](https://linux-hardware.org/?probe=662e292b55) | Jun 06, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [024a1f80a1](https://linux-hardware.org/?probe=024a1f80a1) | Jun 06, 2023 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [6cd3cfcacf](https://linux-hardware.org/?probe=6cd3cfcacf) | Jun 06, 2023 |
| Lenovo        | ThinkPad 21CKCT01WW         | Notebook    | [92c9ec75c4](https://linux-hardware.org/?probe=92c9ec75c4) | Jun 05, 2023 |
| MSI           | Crosshair 15 C12VF          | Notebook    | [6cd11169d0](https://linux-hardware.org/?probe=6cd11169d0) | Jun 05, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [e92db65759](https://linux-hardware.org/?probe=e92db65759) | Jun 05, 2023 |
| HUAWEI        | KPR-WX9                     | Notebook    | [3eb711e453](https://linux-hardware.org/?probe=3eb711e453) | Jun 05, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [a3089228b1](https://linux-hardware.org/?probe=a3089228b1) | Jun 05, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [6d2c05fd11](https://linux-hardware.org/?probe=6d2c05fd11) | Jun 05, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [f8f07099c7](https://linux-hardware.org/?probe=f8f07099c7) | Jun 05, 2023 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [f4e7c7034f](https://linux-hardware.org/?probe=f4e7c7034f) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [54e2e07ac6](https://linux-hardware.org/?probe=54e2e07ac6) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [292e41c0e9](https://linux-hardware.org/?probe=292e41c0e9) | Jun 05, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [bfce53d6f5](https://linux-hardware.org/?probe=bfce53d6f5) | Jun 05, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [eb67866c74](https://linux-hardware.org/?probe=eb67866c74) | Jun 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [8c6a275a93](https://linux-hardware.org/?probe=8c6a275a93) | Jun 05, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [8cbfe4cdf0](https://linux-hardware.org/?probe=8cbfe4cdf0) | Jun 05, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [ecad21f91c](https://linux-hardware.org/?probe=ecad21f91c) | Jun 04, 2023 |
| MSI           | Katana GF66 11UG            | Notebook    | [d50f02e996](https://linux-hardware.org/?probe=d50f02e996) | Jun 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3d29012888](https://linux-hardware.org/?probe=3d29012888) | Jun 04, 2023 |
| ASUSTek       | X505BP                      | Notebook    | [f92e294ba0](https://linux-hardware.org/?probe=f92e294ba0) | Jun 04, 2023 |
| ASRock        | QC5000M-ITX/PH              | Desktop     | [bdf4ee4d4f](https://linux-hardware.org/?probe=bdf4ee4d4f) | Jun 04, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [72ccbe10aa](https://linux-hardware.org/?probe=72ccbe10aa) | Jun 04, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [2eeb67613f](https://linux-hardware.org/?probe=2eeb67613f) | Jun 04, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [7179829c20](https://linux-hardware.org/?probe=7179829c20) | Jun 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [038871f5be](https://linux-hardware.org/?probe=038871f5be) | Jun 04, 2023 |
| Unknown       | Intel X79                   | Desktop     | [0e2e65a79e](https://linux-hardware.org/?probe=0e2e65a79e) | Jun 04, 2023 |
| Cube          | i16-L                       | Notebook    | [5e0bd26a26](https://linux-hardware.org/?probe=5e0bd26a26) | Jun 04, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [fb0c1a4922](https://linux-hardware.org/?probe=fb0c1a4922) | Jun 04, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [d45c069b9f](https://linux-hardware.org/?probe=d45c069b9f) | Jun 04, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [a90856c944](https://linux-hardware.org/?probe=a90856c944) | Jun 04, 2023 |
| ASUSTek       | Zenbook UM5401RA_RM5401R... | Notebook    | [763a52f3e8](https://linux-hardware.org/?probe=763a52f3e8) | Jun 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [0523005c68](https://linux-hardware.org/?probe=0523005c68) | Jun 03, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [6754a25d1d](https://linux-hardware.org/?probe=6754a25d1d) | Jun 03, 2023 |
| Gigabyte      | H67MA-USB3-B3               | Desktop     | [1908e7e6f5](https://linux-hardware.org/?probe=1908e7e6f5) | Jun 03, 2023 |
| ASUSTek       | ROG Strix G814JV_G814JV     | Notebook    | [e0f06316db](https://linux-hardware.org/?probe=e0f06316db) | Jun 03, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [95ec288436](https://linux-hardware.org/?probe=95ec288436) | Jun 03, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [7720a9f71c](https://linux-hardware.org/?probe=7720a9f71c) | Jun 03, 2023 |
| Gigabyte      | AERO 15WV8                  | Notebook    | [a8700141be](https://linux-hardware.org/?probe=a8700141be) | Jun 03, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [4f512af4c2](https://linux-hardware.org/?probe=4f512af4c2) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [d2189d4a5f](https://linux-hardware.org/?probe=d2189d4a5f) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [49ca1fd34f](https://linux-hardware.org/?probe=49ca1fd34f) | Jun 02, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [d75ea1f93f](https://linux-hardware.org/?probe=d75ea1f93f) | Jun 02, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [947c70d6b6](https://linux-hardware.org/?probe=947c70d6b6) | Jun 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c9e1edde25](https://linux-hardware.org/?probe=c9e1edde25) | Jun 02, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [d61bd0903e](https://linux-hardware.org/?probe=d61bd0903e) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [1f18cef2df](https://linux-hardware.org/?probe=1f18cef2df) | Jun 01, 2023 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [38a0e17081](https://linux-hardware.org/?probe=38a0e17081) | Jun 01, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [7ae3edd73e](https://linux-hardware.org/?probe=7ae3edd73e) | Jun 01, 2023 |
| Dell          | Vostro 7590                 | Notebook    | [d9bfa42b63](https://linux-hardware.org/?probe=d9bfa42b63) | Jun 01, 2023 |
| ASRock        | X370 Pro4                   | Desktop     | [aaeac4c226](https://linux-hardware.org/?probe=aaeac4c226) | Jun 01, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [b3eed1356b](https://linux-hardware.org/?probe=b3eed1356b) | Jun 01, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [f383c5193d](https://linux-hardware.org/?probe=f383c5193d) | Jun 01, 2023 |
| ASUSTek       | ROG Flow X16 GV601VI_GV6... | Convertible | [76ec545734](https://linux-hardware.org/?probe=76ec545734) | Jun 01, 2023 |
| Dell          | Latitude E6400              | Notebook    | [efe855c429](https://linux-hardware.org/?probe=efe855c429) | May 31, 2023 |
| Dell          | Latitude E6400              | Notebook    | [c56e8318db](https://linux-hardware.org/?probe=c56e8318db) | May 31, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [2c4acbbad3](https://linux-hardware.org/?probe=2c4acbbad3) | May 31, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [ceaf9120eb](https://linux-hardware.org/?probe=ceaf9120eb) | May 31, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [ac6f421fef](https://linux-hardware.org/?probe=ac6f421fef) | May 31, 2023 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [8389c76bd3](https://linux-hardware.org/?probe=8389c76bd3) | May 31, 2023 |
| Dell          | Latitude E6420              | Notebook    | [102e4634b1](https://linux-hardware.org/?probe=102e4634b1) | May 31, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [4a3e8c4d6f](https://linux-hardware.org/?probe=4a3e8c4d6f) | May 31, 2023 |
| Lenovo        | 3730 SDK0T76463 WIN 3422... | Desktop     | [4dfacbbeb1](https://linux-hardware.org/?probe=4dfacbbeb1) | May 31, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [8a6ceb7d8b](https://linux-hardware.org/?probe=8a6ceb7d8b) | May 30, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [ab97cb7f09](https://linux-hardware.org/?probe=ab97cb7f09) | May 30, 2023 |
| Intel         | NUC11TNBi5 M11904-404       | Mini pc     | [b706fad8dc](https://linux-hardware.org/?probe=b706fad8dc) | May 30, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [b00cd1c84e](https://linux-hardware.org/?probe=b00cd1c84e) | May 30, 2023 |
| Cincoze       | 1.0.01.001                  | Desktop     | [1552e93368](https://linux-hardware.org/?probe=1552e93368) | May 30, 2023 |
| Dell          | 02N3WF A01                  | Desktop     | [c02695ea7d](https://linux-hardware.org/?probe=c02695ea7d) | May 30, 2023 |
| ASUSTek       | N61Jv                       | Notebook    | [7184d6add6](https://linux-hardware.org/?probe=7184d6add6) | May 30, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [55b500a1a9](https://linux-hardware.org/?probe=55b500a1a9) | May 30, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [4fbe93ecc5](https://linux-hardware.org/?probe=4fbe93ecc5) | May 30, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [c98400b6eb](https://linux-hardware.org/?probe=c98400b6eb) | May 30, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d4cc055d3a](https://linux-hardware.org/?probe=d4cc055d3a) | May 30, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [29d2e377ad](https://linux-hardware.org/?probe=29d2e377ad) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [b8e68f9227](https://linux-hardware.org/?probe=b8e68f9227) | May 29, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [10e4fd14b5](https://linux-hardware.org/?probe=10e4fd14b5) | May 29, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [541e16d421](https://linux-hardware.org/?probe=541e16d421) | May 29, 2023 |
| HP            | 14                          | Notebook    | [977d26c9b5](https://linux-hardware.org/?probe=977d26c9b5) | May 29, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [7adfc9796d](https://linux-hardware.org/?probe=7adfc9796d) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | Notebook    | [84781c068a](https://linux-hardware.org/?probe=84781c068a) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | Notebook    | [97f0880258](https://linux-hardware.org/?probe=97f0880258) | May 29, 2023 |
| Acer          | Aspire A515-41G             | Notebook    | [644a5d7a16](https://linux-hardware.org/?probe=644a5d7a16) | May 29, 2023 |
| Dell          | Inspiron 5447               | Notebook    | [270e3cd993](https://linux-hardware.org/?probe=270e3cd993) | May 29, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [12838b3e3b](https://linux-hardware.org/?probe=12838b3e3b) | May 28, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [99540846c4](https://linux-hardware.org/?probe=99540846c4) | May 28, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [99c9a792f5](https://linux-hardware.org/?probe=99c9a792f5) | May 28, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [47ac3b9c43](https://linux-hardware.org/?probe=47ac3b9c43) | May 28, 2023 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [f7d00f30cb](https://linux-hardware.org/?probe=f7d00f30cb) | May 28, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [b5e36f87e6](https://linux-hardware.org/?probe=b5e36f87e6) | May 28, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [4a54b4e82c](https://linux-hardware.org/?probe=4a54b4e82c) | May 28, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [c4ee84b38e](https://linux-hardware.org/?probe=c4ee84b38e) | May 28, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [462ae1c4f5](https://linux-hardware.org/?probe=462ae1c4f5) | May 28, 2023 |
| Gigabyte      | B660 DS3H DDR4              | Desktop     | [807dd44df4](https://linux-hardware.org/?probe=807dd44df4) | May 28, 2023 |
| Unknown       | Unknown                     | Soc         | [cb86a495e2](https://linux-hardware.org/?probe=cb86a495e2) | May 27, 2023 |
| HP            | 2AF7                        | Desktop     | [b459ce46cb](https://linux-hardware.org/?probe=b459ce46cb) | May 27, 2023 |
| Unknown       | Unknown                     | Soc         | [0ddad101d8](https://linux-hardware.org/?probe=0ddad101d8) | May 27, 2023 |
| Lenovo        | ThinkPad T560 20FJS0CX00    | Notebook    | [cf7d5b7149](https://linux-hardware.org/?probe=cf7d5b7149) | May 27, 2023 |
| Dell          | Latitude E6440              | Notebook    | [821e3e3246](https://linux-hardware.org/?probe=821e3e3246) | May 27, 2023 |
| Acer          | Swift SF514-54GT            | Notebook    | [dd79b67b18](https://linux-hardware.org/?probe=dd79b67b18) | May 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [737d3fe7fb](https://linux-hardware.org/?probe=737d3fe7fb) | May 27, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [cbcea9cc58](https://linux-hardware.org/?probe=cbcea9cc58) | May 27, 2023 |
| ASRock        | H81M-VG4                    | Desktop     | [4e7b273239](https://linux-hardware.org/?probe=4e7b273239) | May 27, 2023 |
| Dell          | Precision 3581              | Notebook    | [9fb00fd492](https://linux-hardware.org/?probe=9fb00fd492) | May 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [16ee98f9cc](https://linux-hardware.org/?probe=16ee98f9cc) | May 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [39cf075935](https://linux-hardware.org/?probe=39cf075935) | May 26, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [8b93a6ab33](https://linux-hardware.org/?probe=8b93a6ab33) | May 26, 2023 |
| Dell          | Latitude 5430               | Notebook    | [e8b9199229](https://linux-hardware.org/?probe=e8b9199229) | May 26, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [acee298918](https://linux-hardware.org/?probe=acee298918) | May 26, 2023 |
| Acer          | WG43M                       | Desktop     | [9afcfc4a44](https://linux-hardware.org/?probe=9afcfc4a44) | May 26, 2023 |
| Lenovo        | Yoga Slim 7 proX 14ARH7 ... | Notebook    | [684751d3db](https://linux-hardware.org/?probe=684751d3db) | May 26, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [a9e0505d3f](https://linux-hardware.org/?probe=a9e0505d3f) | May 26, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [db7d7cf31d](https://linux-hardware.org/?probe=db7d7cf31d) | May 26, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [f757bc2c6e](https://linux-hardware.org/?probe=f757bc2c6e) | May 25, 2023 |
| Lenovo        | IdeaPad Z580                | Notebook    | [8d9c3b024d](https://linux-hardware.org/?probe=8d9c3b024d) | May 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [f876b5169a](https://linux-hardware.org/?probe=f876b5169a) | May 25, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [961a04643c](https://linux-hardware.org/?probe=961a04643c) | May 25, 2023 |
| ASUSTek       | S551LB                      | Notebook    | [86f50d3933](https://linux-hardware.org/?probe=86f50d3933) | May 25, 2023 |
| MSI           | X99A GAMING PRO CARBON      | Desktop     | [4c9595e6ea](https://linux-hardware.org/?probe=4c9595e6ea) | May 24, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [fb5edbbd6b](https://linux-hardware.org/?probe=fb5edbbd6b) | May 24, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [00979b3baa](https://linux-hardware.org/?probe=00979b3baa) | May 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d92b2ec905](https://linux-hardware.org/?probe=d92b2ec905) | May 24, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [84d9f5a2cc](https://linux-hardware.org/?probe=84d9f5a2cc) | May 24, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [e6c958dd68](https://linux-hardware.org/?probe=e6c958dd68) | May 24, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [82183f4762](https://linux-hardware.org/?probe=82183f4762) | May 24, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [43069955ee](https://linux-hardware.org/?probe=43069955ee) | May 23, 2023 |
| Toshiba       | Satellite C645D             | Notebook    | [97abd98fdd](https://linux-hardware.org/?probe=97abd98fdd) | May 23, 2023 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [e752398b87](https://linux-hardware.org/?probe=e752398b87) | May 23, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [e4c9c425f8](https://linux-hardware.org/?probe=e4c9c425f8) | May 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [01c17ab9dc](https://linux-hardware.org/?probe=01c17ab9dc) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [6e1c91c725](https://linux-hardware.org/?probe=6e1c91c725) | May 23, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [a5a990a94c](https://linux-hardware.org/?probe=a5a990a94c) | May 23, 2023 |
| HP            | Pavilion 17                 | Notebook    | [eb6c222cf7](https://linux-hardware.org/?probe=eb6c222cf7) | May 23, 2023 |
| MSI           | X99A GAMING PRO CARBON      | Desktop     | [d0312b1a56](https://linux-hardware.org/?probe=d0312b1a56) | May 23, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [aa33ddd283](https://linux-hardware.org/?probe=aa33ddd283) | May 23, 2023 |
| MSI           | B550-A PRO[CEC]             | Desktop     | [66b4de8c55](https://linux-hardware.org/?probe=66b4de8c55) | May 22, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [324a8d5c88](https://linux-hardware.org/?probe=324a8d5c88) | May 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [97687a73c3](https://linux-hardware.org/?probe=97687a73c3) | May 22, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [5300f7df17](https://linux-hardware.org/?probe=5300f7df17) | May 22, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [179e48239b](https://linux-hardware.org/?probe=179e48239b) | May 22, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [a8e6f277e2](https://linux-hardware.org/?probe=a8e6f277e2) | May 22, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [c2d03bd839](https://linux-hardware.org/?probe=c2d03bd839) | May 22, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [88830e9fe8](https://linux-hardware.org/?probe=88830e9fe8) | May 22, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [cccb529fd3](https://linux-hardware.org/?probe=cccb529fd3) | May 21, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [ca280c2e18](https://linux-hardware.org/?probe=ca280c2e18) | May 21, 2023 |
| MSI           | MPG Z790 EDGE WIFI          | Desktop     | [30e9eb3dd1](https://linux-hardware.org/?probe=30e9eb3dd1) | May 21, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [1e231f6e75](https://linux-hardware.org/?probe=1e231f6e75) | May 21, 2023 |
| HP            | 339A                        | Desktop     | [d4a8f3dbb1](https://linux-hardware.org/?probe=d4a8f3dbb1) | May 21, 2023 |
| Dell          | G3 3500                     | Notebook    | [490bdc1f92](https://linux-hardware.org/?probe=490bdc1f92) | May 21, 2023 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [2229714a14](https://linux-hardware.org/?probe=2229714a14) | May 21, 2023 |
| HP            | Laptop 15-dy4xxx            | Notebook    | [d739b1ab41](https://linux-hardware.org/?probe=d739b1ab41) | May 21, 2023 |
| HASEE Comp... | V1x0PNPx                    | Notebook    | [ce5f16dcfe](https://linux-hardware.org/?probe=ce5f16dcfe) | May 20, 2023 |
| ASRock        | 970A-G                      | Desktop     | [fd39b2185b](https://linux-hardware.org/?probe=fd39b2185b) | May 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6bcf177a20](https://linux-hardware.org/?probe=6bcf177a20) | May 20, 2023 |
| HP            | 8437                        | Desktop     | [d41a0c8439](https://linux-hardware.org/?probe=d41a0c8439) | May 20, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [d82bf9332f](https://linux-hardware.org/?probe=d82bf9332f) | May 20, 2023 |
| ASRock        | 970A-G                      | Desktop     | [fac3e3c961](https://linux-hardware.org/?probe=fac3e3c961) | May 20, 2023 |
| Dell          | Latitude D630               | Notebook    | [d5d56f7183](https://linux-hardware.org/?probe=d5d56f7183) | May 20, 2023 |
| Dell          | Latitude D630               | Notebook    | [af41a1c303](https://linux-hardware.org/?probe=af41a1c303) | May 20, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [d52cf51575](https://linux-hardware.org/?probe=d52cf51575) | May 19, 2023 |
| Lenovo        | ThinkPad X240 20AMA21D00    | Notebook    | [a692a56bc0](https://linux-hardware.org/?probe=a692a56bc0) | May 19, 2023 |
| HP            | 8437                        | Desktop     | [ceacc79bf6](https://linux-hardware.org/?probe=ceacc79bf6) | May 19, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [515e752ecb](https://linux-hardware.org/?probe=515e752ecb) | May 19, 2023 |
| HP            | Unknown                     | Notebook    | [8ae91264ca](https://linux-hardware.org/?probe=8ae91264ca) | May 19, 2023 |
| ASUSTek       | X555LPB                     | Notebook    | [c1082eef21](https://linux-hardware.org/?probe=c1082eef21) | May 18, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING S     | Desktop     | [693c7b6d9b](https://linux-hardware.org/?probe=693c7b6d9b) | May 18, 2023 |
| Lenovo        | ThinkPad X61 7673V4Q        | Notebook    | [7df5747f30](https://linux-hardware.org/?probe=7df5747f30) | May 18, 2023 |
| Dell          | Latitude 5500               | Notebook    | [f03dddbf42](https://linux-hardware.org/?probe=f03dddbf42) | May 18, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [25e9a17dd0](https://linux-hardware.org/?probe=25e9a17dd0) | May 18, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | Notebook    | [fdb0fb3d9c](https://linux-hardware.org/?probe=fdb0fb3d9c) | May 18, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [cb6f71a6c4](https://linux-hardware.org/?probe=cb6f71a6c4) | May 18, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [d58889925f](https://linux-hardware.org/?probe=d58889925f) | May 18, 2023 |
| ASUSTek       | F1A75-M PRO/CSM             | Desktop     | [e0ebac1371](https://linux-hardware.org/?probe=e0ebac1371) | May 18, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [b07c7291d1](https://linux-hardware.org/?probe=b07c7291d1) | May 18, 2023 |
| Dell          | Latitude 5420               | Notebook    | [bd0c08b7b8](https://linux-hardware.org/?probe=bd0c08b7b8) | May 18, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [220fb1cfbc](https://linux-hardware.org/?probe=220fb1cfbc) | May 18, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [aa625a94a0](https://linux-hardware.org/?probe=aa625a94a0) | May 18, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [d23967583a](https://linux-hardware.org/?probe=d23967583a) | May 18, 2023 |
| Acer          | Swift SF315-51G             | Notebook    | [4361a75669](https://linux-hardware.org/?probe=4361a75669) | May 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [42f598550a](https://linux-hardware.org/?probe=42f598550a) | May 17, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [1a12100c5f](https://linux-hardware.org/?probe=1a12100c5f) | May 17, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [09e723be6f](https://linux-hardware.org/?probe=09e723be6f) | May 17, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | Notebook    | [2df1a28c50](https://linux-hardware.org/?probe=2df1a28c50) | May 17, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8ffa28e78e](https://linux-hardware.org/?probe=8ffa28e78e) | May 17, 2023 |
| Emdoor        | AG958                       | Notebook    | [7ff5858830](https://linux-hardware.org/?probe=7ff5858830) | May 17, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [4d1cd4ec12](https://linux-hardware.org/?probe=4d1cd4ec12) | May 17, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [de0485927b](https://linux-hardware.org/?probe=de0485927b) | May 17, 2023 |
| Google        | Cyan                        | Notebook    | [41811cace9](https://linux-hardware.org/?probe=41811cace9) | May 17, 2023 |
| ASUSTek       | P7H55D-M PRO                | Desktop     | [dc1bf86813](https://linux-hardware.org/?probe=dc1bf86813) | May 17, 2023 |
| Dell          | Latitude 5330               | Notebook    | [3cc5328fee](https://linux-hardware.org/?probe=3cc5328fee) | May 16, 2023 |
| GPD           | MicroPC                     | Notebook    | [0da3fc7738](https://linux-hardware.org/?probe=0da3fc7738) | May 16, 2023 |
| Google        | Cyan                        | Notebook    | [65c63caab7](https://linux-hardware.org/?probe=65c63caab7) | May 16, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [377fe6aa67](https://linux-hardware.org/?probe=377fe6aa67) | May 16, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B5402CBA... | Notebook    | [170341ae00](https://linux-hardware.org/?probe=170341ae00) | May 15, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [16308738b3](https://linux-hardware.org/?probe=16308738b3) | May 15, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [b788039ba1](https://linux-hardware.org/?probe=b788039ba1) | May 15, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [dc5dd8c32a](https://linux-hardware.org/?probe=dc5dd8c32a) | May 15, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [5dadcb24d0](https://linux-hardware.org/?probe=5dadcb24d0) | May 15, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [55eb2f47b9](https://linux-hardware.org/?probe=55eb2f47b9) | May 15, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [b938ce8d64](https://linux-hardware.org/?probe=b938ce8d64) | May 15, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [2750a05721](https://linux-hardware.org/?probe=2750a05721) | May 15, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [85c2869727](https://linux-hardware.org/?probe=85c2869727) | May 15, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [66f97c57e2](https://linux-hardware.org/?probe=66f97c57e2) | May 14, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [360db31139](https://linux-hardware.org/?probe=360db31139) | May 14, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [c3bbc544d3](https://linux-hardware.org/?probe=c3bbc544d3) | May 14, 2023 |
| Lenovo        | ThinkPad T570 20H90002GE    | Notebook    | [e6ff63678e](https://linux-hardware.org/?probe=e6ff63678e) | May 14, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [0f70383aab](https://linux-hardware.org/?probe=0f70383aab) | May 14, 2023 |
| Gigabyte      | Z170X-UD5 TH-CF             | Desktop     | [6a84af6428](https://linux-hardware.org/?probe=6a84af6428) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [ba47df6545](https://linux-hardware.org/?probe=ba47df6545) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [0b6c34eefa](https://linux-hardware.org/?probe=0b6c34eefa) | May 14, 2023 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [fe36fee27a](https://linux-hardware.org/?probe=fe36fee27a) | May 14, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [b9f9ed1b25](https://linux-hardware.org/?probe=b9f9ed1b25) | May 14, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Arch/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Arch Rolling     | 3946      | 56.74%  |
| Arch             | 2982      | 42.88%  |
| Arch V20.4.11    | 3         | 0.04%   |
| Arch V19.11.3    | 3         | 0.04%   |
| Arch V20.5.7     | 2         | 0.03%   |
| Arch V20.3.4     | 2         | 0.03%   |
| Arch V19.04.4    | 2         | 0.03%   |
| Arch Workstation | 1         | 0.01%   |
| Arch V6.9.2      | 1         | 0.01%   |
| Arch V19.09.1    | 1         | 0.01%   |
| Arch V19.07.9    | 1         | 0.01%   |
| Arch V19.07.11   | 1         | 0.01%   |
| Arch V19.06.1    | 1         | 0.01%   |
| Arch V19.05.2    | 1         | 0.01%   |
| Arch V19.01.4    | 1         | 0.01%   |
| Arch Breaking    | 1         | 0.01%   |
| Arch 23.0.0      | 1         | 0.01%   |
| Arch 22.10       | 1         | 0.01%   |
| Arch 2020.09.05  | 1         | 0.01%   |
| Arch 20.08.3     | 1         | 0.01%   |
| Arch 2.7         | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Arch | 6768      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version         | Computers | Percent |
|-----------------|-----------|---------|
| 5.17.1-arch1-1  | 85        | 1.06%   |
| 6.0.2-arch1-1   | 71        | 0.88%   |
| 5.8.5-arch1-1   | 70        | 0.87%   |
| 5.9.14-arch1-1  | 61        | 0.76%   |
| 5.9.1-arch1-1   | 60        | 0.75%   |
| 6.4.12-arch1-1  | 54        | 0.67%   |
| 5.17.5-arch1-1  | 53        | 0.66%   |
| 5.17.9-arch1-1  | 51        | 0.64%   |
| 5.8.12-arch1-1  | 48        | 0.6%    |
| 5.8.10-arch1-1  | 48        | 0.6%    |
| 5.8.14-arch1-1  | 47        | 0.59%   |
| 6.3.9-arch1-1   | 46        | 0.57%   |
| 6.1.1-arch1-1   | 46        | 0.57%   |
| 5.7.12-arch1-1  | 46        | 0.57%   |
| 6.2.8-arch1-1   | 45        | 0.56%   |
| 5.13.13-arch1-1 | 45        | 0.56%   |
| 6.0.12-arch1-1  | 43        | 0.54%   |
| 5.8.1-arch1-1   | 43        | 0.54%   |
| 6.0.9-arch1-1   | 42        | 0.52%   |
| 5.11.16-arch1-1 | 42        | 0.52%   |
| 6.3.2-arch1-1   | 38        | 0.47%   |
| 6.2.10-arch1-1  | 37        | 0.46%   |
| 6.1.12-arch1-1  | 37        | 0.46%   |
| 5.6.15-arch1-1  | 37        | 0.46%   |
| 6.1.8-arch1-1   | 35        | 0.44%   |
| 5.18.16-arch1-1 | 34        | 0.42%   |
| 5.11.6-arch1-1  | 34        | 0.42%   |
| 5.11.11-arch1-1 | 34        | 0.42%   |
| 6.4.10-arch1-1  | 33        | 0.41%   |
| 6.3.5-arch1-1   | 33        | 0.41%   |
| 6.3.1-arch1-1   | 33        | 0.41%   |
| 5.12.15-arch1-1 | 33        | 0.41%   |
| 5.10.16-arch1-1 | 33        | 0.41%   |
| 6.2.12-arch1-1  | 32        | 0.4%    |
| 6.0.10-arch2-1  | 32        | 0.4%    |
| 5.19.13-arch1-1 | 32        | 0.4%    |
| 5.18.1-arch1-1  | 32        | 0.4%    |
| 6.2.2-arch1-1   | 31        | 0.39%   |
| 6.0.7-arch1-1   | 31        | 0.39%   |
| 5.8.3-arch1-1   | 31        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.1  | 105       | 1.31%   |
| 5.8.5   | 92        | 1.15%   |
| 6.0.2   | 90        | 1.12%   |
| 5.9.1   | 77        | 0.96%   |
| 5.8.12  | 73        | 0.91%   |
| 5.9.14  | 72        | 0.9%    |
| 5.17.5  | 70        | 0.87%   |
| 6.3.1   | 65        | 0.81%   |
| 5.8.14  | 63        | 0.79%   |
| 5.8.10  | 62        | 0.77%   |
| 6.4.12  | 61        | 0.76%   |
| 5.17.9  | 61        | 0.76%   |
| 6.3.9   | 59        | 0.74%   |
| 6.1.1   | 57        | 0.71%   |
| 5.13.13 | 56        | 0.7%    |
| 6.2.2   | 54        | 0.67%   |
| 6.1.12  | 54        | 0.67%   |
| 6.4.3   | 53        | 0.66%   |
| 6.2.8   | 53        | 0.66%   |
| 5.8.1   | 53        | 0.66%   |
| 5.7.12  | 53        | 0.66%   |
| 6.0.9   | 52        | 0.65%   |
| 6.0.12  | 52        | 0.65%   |
| 5.11.6  | 52        | 0.65%   |
| 6.3.2   | 51        | 0.64%   |
| 6.1.9   | 51        | 0.64%   |
| 5.11.16 | 51        | 0.64%   |
| 6.2.10  | 49        | 0.61%   |
| 6.3.5   | 48        | 0.6%    |
| 6.4.10  | 44        | 0.55%   |
| 6.1.8   | 44        | 0.55%   |
| 5.11.2  | 43        | 0.54%   |
| 6.0.8   | 42        | 0.52%   |
| 5.12.15 | 42        | 0.52%   |
| 5.10.16 | 42        | 0.52%   |
| 6.0.11  | 41        | 0.51%   |
| 5.19.7  | 41        | 0.51%   |
| 5.18.16 | 41        | 0.51%   |
| 5.11.11 | 41        | 0.51%   |
| 6.0.10  | 40        | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.8     | 522       | 6.76%   |
| 5.15    | 479       | 6.2%    |
| 6.1     | 475       | 6.15%   |
| 6.0     | 413       | 5.35%   |
| 6.4     | 391       | 5.06%   |
| 6.2     | 385       | 4.98%   |
| 5.9     | 384       | 4.97%   |
| 5.18    | 367       | 4.75%   |
| 6.3     | 366       | 4.74%   |
| 5.10    | 355       | 4.59%   |
| 5.4     | 353       | 4.57%   |
| 5.11    | 350       | 4.53%   |
| 5.19    | 343       | 4.44%   |
| 5.17    | 342       | 4.43%   |
| 5.12    | 310       | 4.01%   |
| 5.16    | 305       | 3.95%   |
| 5.6     | 263       | 3.4%    |
| 5.7     | 260       | 3.37%   |
| 5.14    | 237       | 3.07%   |
| 5.13    | 234       | 3.03%   |
| 5.5     | 148       | 1.92%   |
| 5.3     | 114       | 1.48%   |
| 4.19    | 56        | 0.72%   |
| 5.2     | 54        | 0.7%    |
| 5.0     | 41        | 0.53%   |
| 4.18    | 37        | 0.48%   |
| 5.1     | 32        | 0.41%   |
| 4.20    | 22        | 0.28%   |
| 4.17    | 19        | 0.25%   |
| 4.15    | 14        | 0.18%   |
| 4.14    | 10        | 0.13%   |
| 4.16    | 9         | 0.12%   |
| 6.5     | 5         | 0.06%   |
| 4.9     | 5         | 0.06%   |
| 4.7     | 4         | 0.05%   |
| 4.6     | 4         | 0.05%   |
| 4.11    | 4         | 0.05%   |
| 4.8     | 3         | 0.04%   |
| 4.4     | 3         | 0.04%   |
| 4.13    | 3         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 6762      | 99.91%  |
| i686    | 5         | 0.07%   |
| riscv64 | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 2237      | 31.71%  |
| KDE5                     | 1874      | 26.57%  |
| Unknown                  | 854       | 12.11%  |
| XFCE                     | 544       | 7.71%   |
| i3                       | 350       | 4.96%   |
| KDE                      | 297       | 4.21%   |
| X-Cinnamon               | 97        | 1.38%   |
| sway                     | 93        | 1.32%   |
| MATE                     | 86        | 1.22%   |
| Budgie                   | 83        | 1.18%   |
| Cinnamon                 | 81        | 1.15%   |
| Deepin                   | 69        | 0.98%   |
| Hyprland                 | 65        | 0.92%   |
| LXQT                     | 55        | 0.78%   |
| LXDE                     | 40        | 0.57%   |
| bspwm                    | 40        | 0.57%   |
| awesome                  | 35        | 0.5%    |
| openbox                  | 21        | 0.3%    |
| qtile                    | 19        | 0.27%   |
| DWM                      | 16        | 0.23%   |
| GNOME Flashback          | 15        | 0.21%   |
| xmonad                   | 14        | 0.2%    |
| Unity                    | 12        | 0.17%   |
| GNOME Classic            | 9         | 0.13%   |
| LeftWM                   | 6         | 0.09%   |
| i3-with-shmlog           | 6         | 0.09%   |
| Enlightenment            | 5         | 0.07%   |
| chadwm                   | 4         | 0.06%   |
| Wayfire                  | 2         | 0.03%   |
| river                    | 2         | 0.03%   |
| jwm                      | 2         | 0.03%   |
| ICEWM                    | 2         | 0.03%   |
| GNUstep                  | 2         | 0.03%   |
| GNOME-Classic            | 2         | 0.03%   |
| dusk                     | 2         | 0.03%   |
| default                  | 2         | 0.03%   |
| /usr/bin/openbox-session | 2         | 0.03%   |
| Yaru:ubuntu:GNOME        | 1         | 0.01%   |
| xinitrc                  | 1         | 0.01%   |
| X-Generic                | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4121      | 58.74%  |
| Wayland | 1755      | 25.01%  |
| Tty     | 644       | 9.18%   |
| Unknown | 495       | 7.06%   |
| Web     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2902      | 41.55%  |
| SDDM    | 1671      | 23.93%  |
| GDM     | 988       | 14.15%  |
| LightDM | 771       | 11.04%  |
| TDM     | 398       | 5.7%    |
| Ly      | 76        | 1.09%   |
| XDM     | 56        | 0.8%    |
| LXDM    | 53        | 0.76%   |
| SLiM    | 28        | 0.4%    |
| GREETD  | 20        | 0.29%   |
| LY-DM   | 7         | 0.1%    |
| EMPTTY  | 6         | 0.09%   |
| NODM    | 5         | 0.07%   |
| XINIT   | 1         | 0.01%   |
| MDM     | 1         | 0.01%   |
| KDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 3376      | 48.78%  |
| Unknown    | 644       | 9.31%   |
| en_GB      | 405       | 5.85%   |
| C          | 367       | 5.3%    |
| de_DE      | 279       | 4.03%   |
| ru_RU      | 221       | 3.19%   |
| it_IT      | 210       | 3.03%   |
| pt_BR      | 191       | 2.76%   |
| fr_FR      | 160       | 2.31%   |
| pl_PL      | 87        | 1.26%   |
| zh_CN      | 82        | 1.18%   |
| en_CA      | 77        | 1.11%   |
| es_ES      | 76        | 1.1%    |
| en_IN      | 69        | 1%      |
| en_AU      | 68        | 0.98%   |
| en_IE      | 36        | 0.52%   |
| en_DK      | 30        | 0.43%   |
| es_MX      | 28        | 0.4%    |
| de_AT      | 22        | 0.32%   |
| hu_HU      | 21        | 0.3%    |
| pt_PT      | 20        | 0.29%   |
| es_AR      | 19        | 0.27%   |
| tr_TR      | 18        | 0.26%   |
| ja_JP      | 17        | 0.25%   |
| en_NZ      | 17        | 0.25%   |
| nl_NL      | 16        | 0.23%   |
| cs_CZ      | 16        | 0.23%   |
| es_CL      | 15        | 0.22%   |
| es_CO      | 14        | 0.2%    |
| en_DE      | 14        | 0.2%    |
| ru_UA      | 13        | 0.19%   |
| sv_SE      | 11        | 0.16%   |
| en_SG      | 11        | 0.16%   |
| en_ZA      | 10        | 0.14%   |
| en_US.UTF8 | 10        | 0.14%   |
| lv_LV      | 9         | 0.13%   |
| fi_FI      | 9         | 0.13%   |
| de_CH      | 9         | 0.13%   |
| zh_TW      | 8         | 0.12%   |
| en_AG      | 8         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 4274      | 61.87%  |
| BIOS | 2634      | 38.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 4841      | 70.53%  |
| Btrfs    | 1478      | 21.53%  |
| Unknown  | 182       | 2.65%   |
| Xfs      | 160       | 2.33%   |
| F2fs     | 91        | 1.33%   |
| Overlay  | 46        | 0.67%   |
| Zfs      | 40        | 0.58%   |
| Ext2     | 8         | 0.12%   |
| Tmpfs    | 7         | 0.1%    |
| XXXXX    | 4         | 0.06%   |
| Jfs      | 2         | 0.03%   |
| Ext3     | 2         | 0.03%   |
| XXX4     | 1         | 0.01%   |
| Reiserfs | 1         | 0.01%   |
| Aufs     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 4357      | 63.43%  |
| Unknown | 1953      | 28.43%  |
| MBR     | 559       | 8.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5909      | 86.11%  |
| Yes       | 953       | 13.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4780      | 69.45%  |
| Yes       | 2103      | 30.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUSTek Computer       | 1320      | 19.5%   |
| Lenovo                 | 1224      | 18.09%  |
| Dell                   | 713       | 10.53%  |
| Hewlett-Packard        | 710       | 10.49%  |
| MSI                    | 558       | 8.24%   |
| Gigabyte Technology    | 548       | 8.1%    |
| ASRock                 | 337       | 4.98%   |
| Acer                   | 331       | 4.89%   |
| Apple                  | 106       | 1.57%   |
| Intel                  | 84        | 1.24%   |
| HUAWEI                 | 71        | 1.05%   |
| Samsung Electronics    | 62        | 0.92%   |
| Toshiba                | 47        | 0.69%   |
| Microsoft              | 38        | 0.56%   |
| Notebook               | 34        | 0.5%    |
| Unknown                | 34        | 0.5%    |
| Timi                   | 31        | 0.46%   |
| Google                 | 28        | 0.41%   |
| Sony                   | 24        | 0.35%   |
| Fujitsu                | 23        | 0.34%   |
| TUXEDO                 | 22        | 0.33%   |
| Framework              | 20        | 0.3%    |
| Alienware              | 20        | 0.3%    |
| Biostar                | 16        | 0.24%   |
| Razer                  | 15        | 0.22%   |
| Medion                 | 13        | 0.19%   |
| LG Electronics         | 12        | 0.18%   |
| ECS                    | 12        | 0.18%   |
| Pegatron               | 11        | 0.16%   |
| Avell High Performance | 11        | 0.16%   |
| System76               | 10        | 0.15%   |
| Schenker               | 10        | 0.15%   |
| Positivo               | 9         | 0.13%   |
| Packard Bell           | 9         | 0.13%   |
| MECHREVO               | 9         | 0.13%   |
| Chuwi                  | 9         | 0.13%   |
| Supermicro             | 8         | 0.12%   |
| Huanan                 | 8         | 0.12%   |
| HONOR                  | 6         | 0.09%   |
| GPD                    | 6         | 0.09%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| ASUS All Series                  | 65        | 0.96%   |
| Unknown                          | 58        | 0.86%   |
| MSI MS-7C37                      | 31        | 0.46%   |
| MSI MS-7C02                      | 31        | 0.46%   |
| ASUS TUF Gaming X570-PLUS        | 31        | 0.46%   |
| MSI MS-7B86                      | 23        | 0.34%   |
| Gigabyte B450M DS3H              | 22        | 0.33%   |
| ASUS ROG STRIX B550-F GAMING     | 19        | 0.28%   |
| Dell XPS 15 9570                 | 18        | 0.27%   |
| Dell XPS 15 9500                 | 18        | 0.27%   |
| ASUS PRIME X470-PRO              | 18        | 0.27%   |
| MSI MS-7B89                      | 17        | 0.25%   |
| MSI MS-7A34                      | 17        | 0.25%   |
| Gigabyte X570 AORUS ELITE        | 17        | 0.25%   |
| ASUS ROG STRIX B450-F GAMING     | 17        | 0.25%   |
| MSI MS-7C91                      | 16        | 0.24%   |
| MSI MS-7B79                      | 16        | 0.24%   |
| HP Notebook                      | 16        | 0.24%   |
| Framework Laptop                 | 16        | 0.24%   |
| ASUS PRIME X370-PRO              | 16        | 0.24%   |
| ASUS PRIME B450M-A               | 16        | 0.24%   |
| MSI MS-7A38                      | 15        | 0.22%   |
| MSI MS-7C56                      | 14        | 0.21%   |
| Gigabyte X470 AORUS ULTRA GAMING | 14        | 0.21%   |
| Dell XPS 13 9360                 | 13        | 0.19%   |
| ASUS TUF Gaming B550-PLUS        | 13        | 0.19%   |
| ASUS ROG STRIX X570-E GAMING     | 13        | 0.19%   |
| ASRock X570 Taichi               | 12        | 0.18%   |
| ASRock B450M Pro4                | 12        | 0.18%   |
| Gigabyte B450 AORUS ELITE        | 11        | 0.16%   |
| Gigabyte 970A-DS3P               | 11        | 0.16%   |
| Dell XPS 13 9380                 | 11        | 0.16%   |
| ASUS ROG STRIX X470-F GAMING     | 11        | 0.16%   |
| ASUS PRIME A320M-K               | 11        | 0.16%   |
| MSI MS-7B98                      | 10        | 0.15%   |
| HUAWEI NBLK-WAX9X                | 10        | 0.15%   |
| Gigabyte X570 I AORUS PRO WIFI   | 10        | 0.15%   |
| Dell XPS 15 7590                 | 10        | 0.15%   |
| Dell XPS 13 9310                 | 10        | 0.15%   |
| Dell Latitude E6430              | 10        | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 662       | 9.78%   |
| ASUS ROG           | 261       | 3.86%   |
| ASUS PRIME         | 218       | 3.22%   |
| Lenovo IdeaPad     | 212       | 3.13%   |
| Acer Aspire        | 188       | 2.78%   |
| Dell Inspiron      | 178       | 2.63%   |
| Dell XPS           | 166       | 2.45%   |
| Dell Latitude      | 162       | 2.39%   |
| ASUS TUF           | 153       | 2.26%   |
| HP Pavilion        | 132       | 1.95%   |
| HP EliteBook       | 114       | 1.68%   |
| Lenovo Legion      | 76        | 1.12%   |
| HP Laptop          | 76        | 1.12%   |
| ASUS VivoBook      | 75        | 1.11%   |
| HP ENVY            | 69        | 1.02%   |
| ASUS All           | 65        | 0.96%   |
| Lenovo Yoga        | 63        | 0.93%   |
| HP ProBook         | 62        | 0.92%   |
| Gigabyte X570      | 60        | 0.89%   |
| Dell Precision     | 60        | 0.89%   |
| Dell OptiPlex      | 59        | 0.87%   |
| Unknown            | 58        | 0.86%   |
| Acer Nitro         | 49        | 0.72%   |
| ASUS ZenBook       | 42        | 0.62%   |
| ASUS ASUS          | 42        | 0.62%   |
| Acer Swift         | 40        | 0.59%   |
| Toshiba Satellite  | 38        | 0.56%   |
| Microsoft Surface  | 38        | 0.56%   |
| Gigabyte B450M     | 37        | 0.55%   |
| Lenovo ThinkBook   | 34        | 0.5%    |
| MSI MS-7C37        | 31        | 0.46%   |
| MSI MS-7C02        | 31        | 0.46%   |
| HP OMEN            | 31        | 0.46%   |
| Dell Vostro        | 31        | 0.46%   |
| ASRock X570        | 31        | 0.46%   |
| HP Spectre         | 30        | 0.44%   |
| Gigabyte B450      | 30        | 0.44%   |
| Lenovo ThinkCentre | 27        | 0.4%    |
| HP Compaq          | 26        | 0.38%   |
| MSI MS-7B86        | 23        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 971       | 14.35%  |
| 2019    | 943       | 13.93%  |
| 2020    | 874       | 12.91%  |
| 2021    | 620       | 9.16%   |
| 2017    | 558       | 8.24%   |
| 2016    | 384       | 5.67%   |
| 2012    | 364       | 5.38%   |
| 2015    | 334       | 4.93%   |
| 2014    | 331       | 4.89%   |
| 2013    | 330       | 4.88%   |
| 2022    | 325       | 4.8%    |
| 2011    | 278       | 4.11%   |
| 2010    | 162       | 2.39%   |
| 2008    | 96        | 1.42%   |
| 2009    | 89        | 1.32%   |
| 2023    | 57        | 0.84%   |
| 2007    | 33        | 0.49%   |
| 2006    | 11        | 0.16%   |
| Unknown | 4         | 0.06%   |
| 2005    | 3         | 0.04%   |
| 2002    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3695      | 54.6%   |
| Desktop        | 2616      | 38.65%  |
| Convertible    | 251       | 3.71%   |
| Tablet         | 75        | 1.11%   |
| Mini pc        | 58        | 0.86%   |
| All in one     | 43        | 0.64%   |
| Server         | 28        | 0.41%   |
| Stick pc       | 1         | 0.01%   |
| System on chip | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 6695      | 98.69%  |
| Enabled  | 89        | 1.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6716      | 99.23%  |
| Yes  | 52        | 0.77%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1966      | 28.63%  |
| 8.01-16.0       | 1334      | 19.43%  |
| 4.01-8.0        | 1289      | 18.77%  |
| 32.01-64.0      | 1115      | 16.24%  |
| 3.01-4.0        | 550       | 8.01%   |
| 64.01-256.0     | 283       | 4.12%   |
| 24.01-32.0      | 188       | 2.74%   |
| 1.01-2.0        | 79        | 1.15%   |
| 2.01-3.0        | 38        | 0.55%   |
| 0.51-1.0        | 13        | 0.19%   |
| More than 256.0 | 9         | 0.13%   |
| Unknown         | 2         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1814      | 24.25%  |
| 2.01-3.0    | 1752      | 23.42%  |
| 1.01-2.0    | 1546      | 20.67%  |
| 3.01-4.0    | 1228      | 16.42%  |
| 8.01-16.0   | 646       | 8.64%   |
| 0.51-1.0    | 259       | 3.46%   |
| 16.01-24.0  | 101       | 1.35%   |
| 0.01-0.5    | 69        | 0.92%   |
| 24.01-32.0  | 39        | 0.52%   |
| 32.01-64.0  | 22        | 0.29%   |
| 64.01-256.0 | 2         | 0.03%   |
| Unknown     | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3489      | 50.06%  |
| 2      | 1901      | 27.28%  |
| 3      | 773       | 11.09%  |
| 4      | 369       | 5.29%   |
| 5      | 209       | 3%      |
| 6      | 94        | 1.35%   |
| 7      | 53        | 0.76%   |
| 0      | 22        | 0.32%   |
| 8      | 20        | 0.29%   |
| 9      | 17        | 0.24%   |
| 11     | 5         | 0.07%   |
| 12     | 4         | 0.06%   |
| 10     | 4         | 0.06%   |
| 13     | 3         | 0.04%   |
| 14     | 2         | 0.03%   |
| 22     | 1         | 0.01%   |
| 19     | 1         | 0.01%   |
| 17     | 1         | 0.01%   |
| 15     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 5401      | 79.31%  |
| Yes       | 1409      | 20.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5634      | 82.94%  |
| No        | 1159      | 17.06%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5302      | 77.87%  |
| No        | 1507      | 22.13%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4798      | 70.07%  |
| No        | 2049      | 29.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 1280      | 18.78%  |
| Germany     | 660       | 9.69%   |
| Russia      | 454       | 6.66%   |
| Brazil      | 360       | 5.28%   |
| Italy       | 353       | 5.18%   |
| France      | 299       | 4.39%   |
| UK          | 260       | 3.82%   |
| India       | 203       | 2.98%   |
| Poland      | 198       | 2.91%   |
| Canada      | 185       | 2.71%   |
| Spain       | 152       | 2.23%   |
| Netherlands | 133       | 1.95%   |
| China       | 119       | 1.75%   |
| Australia   | 116       | 1.7%    |
| Sweden      | 101       | 1.48%   |
| Austria     | 98        | 1.44%   |
| Ukraine     | 91        | 1.34%   |
| Turkey      | 84        | 1.23%   |
| Finland     | 74        | 1.09%   |
| Switzerland | 62        | 0.91%   |
| Czechia     | 60        | 0.88%   |
| Hungary     | 57        | 0.84%   |
| Mexico      | 56        | 0.82%   |
| Romania     | 54        | 0.79%   |
| Indonesia   | 53        | 0.78%   |
| Argentina   | 51        | 0.75%   |
| Portugal    | 48        | 0.7%    |
| Denmark     | 48        | 0.7%    |
| Belgium     | 48        | 0.7%    |
| Japan       | 46        | 0.68%   |
| Norway      | 44        | 0.65%   |
| Greece      | 44        | 0.65%   |
| Chile       | 41        | 0.6%    |
| Vietnam     | 38        | 0.56%   |
| New Zealand | 36        | 0.53%   |
| Iran        | 35        | 0.51%   |
| Hong Kong   | 35        | 0.51%   |
| Colombia    | 34        | 0.5%    |
| Bulgaria    | 28        | 0.41%   |
| Taiwan      | 27        | 0.4%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 130       | 1.8%    |
| Paris             | 74        | 1.02%   |
| Berlin            | 69        | 0.95%   |
| St Petersburg     | 66        | 0.91%   |
| Sao Paulo         | 55        | 0.76%   |
| Warsaw            | 54        | 0.75%   |
| Vienna            | 54        | 0.75%   |
| Milan             | 53        | 0.73%   |
| Melbourne         | 46        | 0.64%   |
| Munich            | 43        | 0.59%   |
| Helsinki          | 40        | 0.55%   |
| Frankfurt am Main | 36        | 0.5%    |
| Los Angeles       | 35        | 0.48%   |
| Amsterdam         | 35        | 0.48%   |
| Sydney            | 32        | 0.44%   |
| Istanbul          | 30        | 0.41%   |
| New York          | 29        | 0.4%    |
| Hamburg           | 29        | 0.4%    |
| Valencia          | 28        | 0.39%   |
| Prague            | 28        | 0.39%   |
| Rome              | 26        | 0.36%   |
| London            | 26        | 0.36%   |
| Montreal          | 25        | 0.35%   |
| Kyiv              | 25        | 0.35%   |
| Budapest          | 25        | 0.35%   |
| Madrid            | 24        | 0.33%   |
| Athens            | 24        | 0.33%   |
| Singapore         | 23        | 0.32%   |
| Seattle           | 23        | 0.32%   |
| Bengaluru         | 23        | 0.32%   |
| Central           | 21        | 0.29%   |
| Krakow            | 20        | 0.28%   |
| Dallas            | 20        | 0.28%   |
| Cologne           | 20        | 0.28%   |
| Beijing           | 20        | 0.28%   |
| Phoenix           | 19        | 0.26%   |
| Mexico City       | 19        | 0.26%   |
| Barcelona         | 19        | 0.26%   |
| Auckland          | 19        | 0.26%   |
| Zurich            | 18        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 2265      | 3573   | 20.21%  |
| WDC                         | 1538      | 2384   | 13.72%  |
| Seagate                     | 1324      | 1991   | 11.81%  |
| SanDisk                     | 790       | 1044   | 7.05%   |
| Toshiba                     | 687       | 920    | 6.13%   |
| Kingston                    | 588       | 781    | 5.25%   |
| Crucial                     | 476       | 680    | 4.25%   |
| SK hynix                    | 353       | 431    | 3.15%   |
| Intel                       | 321       | 427    | 2.86%   |
| Unknown                     | 279       | 336    | 2.49%   |
| Micron Technology           | 210       | 254    | 1.87%   |
| HGST                        | 186       | 237    | 1.66%   |
| Hitachi                     | 172       | 215    | 1.53%   |
| A-DATA Technology           | 166       | 229    | 1.48%   |
| Phison                      | 117       | 151    | 1.04%   |
| Micron/Crucial Technology   | 93        | 108    | 0.83%   |
| Phison Electronics          | 89        | 107    | 0.79%   |
| Silicon Motion              | 80        | 94     | 0.71%   |
| China                       | 80        | 102    | 0.71%   |
| KIOXIA                      | 75        | 91     | 0.67%   |
| Apple                       | 73        | 90     | 0.65%   |
| SPCC                        | 54        | 59     | 0.48%   |
| OCZ                         | 54        | 72     | 0.48%   |
| Kingston Technology Company | 51        | 55     | 0.45%   |
| Corsair                     | 50        | 64     | 0.45%   |
| PNY                         | 49        | 60     | 0.44%   |
| Transcend                   | 47        | 62     | 0.42%   |
| ADATA Technology            | 44        | 54     | 0.39%   |
| LITEON                      | 43        | 46     | 0.38%   |
| Patriot                     | 41        | 52     | 0.37%   |
| GOODRAM                     | 31        | 39     | 0.28%   |
| Realtek Semiconductor       | 30        | 37     | 0.27%   |
| XPG                         | 27        | 39     | 0.24%   |
| JMicron Technology          | 27        | 36     | 0.24%   |
| Plextor                     | 23        | 32     | 0.21%   |
| Hewlett-Packard             | 23        | 25     | 0.21%   |
| Team                        | 22        | 31     | 0.2%    |
| Intenso                     | 22        | 24     | 0.2%    |
| Lenovo                      | 20        | 25     | 0.18%   |
| Lexar                       | 19        | 27     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 252       | 1.98%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 128       | 1.01%   |
| Samsung SSD 860 EVO 500GB                             | 120       | 0.94%   |
| Samsung SSD 850 EVO 500GB                             | 119       | 0.94%   |
| Kingston SA400S37240G 240GB SSD                       | 114       | 0.9%    |
| Seagate ST1000LM035-1RK172 1TB                        | 101       | 0.79%   |
| Samsung SSD 860 EVO 1TB                               | 89        | 0.7%    |
| Samsung SSD 850 EVO 250GB                             | 89        | 0.7%    |
| Seagate ST2000DM008-2FR102 2TB                        | 83        | 0.65%   |
| Samsung NVMe SSD Drive 512GB                          | 82        | 0.64%   |
| Samsung SSD 970 EVO Plus 1TB                          | 77        | 0.61%   |
| Crucial CT1000MX500SSD1 1TB                           | 77        | 0.61%   |
| Crucial CT500MX500SSD1 500GB                          | 76        | 0.6%    |
| Samsung NVMe SSD Drive 1TB                            | 67        | 0.53%   |
| Seagate ST1000DM010-2EP102 1TB                        | 66        | 0.52%   |
| Samsung SSD 970 EVO Plus 500GB                        | 65        | 0.51%   |
| Samsung NVMe SSD Drive 500GB                          | 64        | 0.5%    |
| Kingston SA400S37120G 120GB SSD                       | 64        | 0.5%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 59        | 0.46%   |
| Kingston SA400S37480G 480GB SSD                       | 59        | 0.46%   |
| HGST HTS721010A9E630 1TB                              | 59        | 0.46%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 58        | 0.46%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 57        | 0.45%   |
| Toshiba MQ01ABD100 1TB                                | 57        | 0.45%   |
| Samsung SSD 860 EVO 250GB                             | 55        | 0.43%   |
| Toshiba DT01ACA100 1TB                                | 52        | 0.41%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                  | 50        | 0.39%   |
| SanDisk NVMe SSD Drive 512GB                          | 50        | 0.39%   |
| SanDisk NVMe SSD Drive 1TB                            | 50        | 0.39%   |
| Seagate ST500DM002-1BD142 500GB                       | 49        | 0.39%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB                | 48        | 0.38%   |
| Seagate ST4000DM004-2CV104 4TB                        | 47        | 0.37%   |
| Unknown MMC Card  64GB                                | 45        | 0.35%   |
| Unknown MMC Card  32GB                                | 45        | 0.35%   |
| Toshiba MQ04ABF100 1TB                                | 45        | 0.35%   |
| Seagate ST2000DM006-2DM164 2TB                        | 44        | 0.35%   |
| Samsung SSD 860 QVO 1TB                               | 44        | 0.35%   |
| SK hynix NVMe SSD Drive 512GB                         | 43        | 0.34%   |
| Samsung SSD 840 EVO 250GB                             | 43        | 0.34%   |
| Samsung SSD 980 1TB                                   | 42        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1294      | 1943   | 36.04%  |
| WDC                 | 1193      | 1825   | 33.23%  |
| Toshiba             | 479       | 633    | 13.34%  |
| HGST                | 184       | 235    | 5.13%   |
| Hitachi             | 172       | 215    | 4.79%   |
| Samsung Electronics | 118       | 157    | 3.29%   |
| Unknown             | 28        | 36     | 0.78%   |
| Apple               | 26        | 26     | 0.72%   |
| SABRENT             | 16        | 17     | 0.45%   |
| Fujitsu             | 11        | 11     | 0.31%   |
| Maxtor              | 9         | 9      | 0.25%   |
| External            | 6         | 8      | 0.17%   |
| ASMT                | 6         | 7      | 0.17%   |
| USB3.0              | 4         | 5      | 0.11%   |
| HGST HTS            | 4         | 4      | 0.11%   |
| SSK                 | 3         | 3      | 0.08%   |
| LaCie               | 3         | 3      | 0.08%   |
| Generic-            | 3         | 4      | 0.08%   |
| SAGE                | 2         | 3      | 0.06%   |
| KESU                | 2         | 2      | 0.06%   |
| Hewlett-Packard     | 2         | 2      | 0.06%   |
| ASUSTOR             | 2         | 2      | 0.06%   |
| ASMedia             | 2         | 2      | 0.06%   |
| ACASIS              | 2         | 2      | 0.06%   |
| USB                 | 1         | 1      | 0.03%   |
| Synology            | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| RSH-319             | 1         | 1      | 0.03%   |
| QNAP                | 1         | 11     | 0.03%   |
| Pioneer             | 1         | 1      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| NeoTech             | 1         | 1      | 0.03%   |
| Maxone              | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 1      | 0.03%   |
| MARVELL             | 1         | 1      | 0.03%   |
| LIO-ORG             | 1         | 2      | 0.03%   |
| JMicron Technology  | 1         | 8      | 0.03%   |
| Intenso             | 1         | 1      | 0.03%   |
| Inateck             | 1         | 1      | 0.03%   |
| H/W                 | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1016      | 1455   | 27.56%  |
| Kingston            | 455       | 590    | 12.34%  |
| Crucial             | 435       | 621    | 11.8%   |
| SanDisk             | 359       | 490    | 9.74%   |
| WDC                 | 244       | 318    | 6.62%   |
| A-DATA Technology   | 110       | 155    | 2.98%   |
| Intel               | 87        | 103    | 2.36%   |
| China               | 80        | 102    | 2.17%   |
| Toshiba             | 55        | 94     | 1.49%   |
| OCZ                 | 54        | 72     | 1.47%   |
| SK hynix            | 51        | 60     | 1.38%   |
| Micron Technology   | 49        | 59     | 1.33%   |
| SPCC                | 45        | 48     | 1.22%   |
| Transcend           | 44        | 59     | 1.19%   |
| PNY                 | 44        | 55     | 1.19%   |
| Patriot             | 41        | 52     | 1.11%   |
| LITEON              | 38        | 40     | 1.03%   |
| Apple               | 33        | 34     | 0.9%    |
| GOODRAM             | 29        | 37     | 0.79%   |
| Corsair             | 23        | 28     | 0.62%   |
| Intenso             | 21        | 23     | 0.57%   |
| Plextor             | 20        | 21     | 0.54%   |
| JMicron Technology  | 18        | 21     | 0.49%   |
| LITEONIT            | 17        | 17     | 0.46%   |
| Lexar               | 17        | 24     | 0.46%   |
| Team                | 16        | 18     | 0.43%   |
| KingSpec            | 15        | 16     | 0.41%   |
| Hewlett-Packard     | 12        | 13     | 0.33%   |
| TO Exter            | 10        | 16     | 0.27%   |
| Mushkin             | 10        | 15     | 0.27%   |
| Gigabyte Technology | 10        | 11     | 0.27%   |
| Netac               | 9         | 9      | 0.24%   |
| ASMT                | 9         | 10     | 0.24%   |
| Unknown             | 9         | 10     | 0.24%   |
| Seagate             | 7         | 7      | 0.19%   |
| FORESEE             | 6         | 9      | 0.16%   |
| XrayDisk            | 5         | 6      | 0.14%   |
| Phison              | 5         | 5      | 0.14%   |
| KingDian            | 5         | 6      | 0.14%   |
| AMD                 | 5         | 6      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 3520      | 5220   | 35.6%   |
| SSD     | 3077      | 4945   | 31.12%  |
| HDD     | 2946      | 5191   | 29.79%  |
| MMC     | 237       | 282    | 2.4%    |
| Unknown | 109       | 131    | 1.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4431      | 9784   | 51.82%  |
| NVMe | 3518      | 5208   | 41.14%  |
| SAS  | 365       | 495    | 4.27%   |
| MMC  | 237       | 282    | 2.77%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3146      | 5049   | 48.59%  |
| 0.51-1.0   | 2054      | 3001   | 31.72%  |
| 1.01-2.0   | 704       | 1081   | 10.87%  |
| 3.01-4.0   | 230       | 398    | 3.55%   |
| 4.01-10.0  | 166       | 314    | 2.56%   |
| 2.01-3.0   | 145       | 225    | 2.24%   |
| 10.01-20.0 | 29        | 67     | 0.45%   |
| 20.01-50.0 | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 1525      | 21.56%  |
| 101-250        | 1472      | 20.81%  |
| 501-1000       | 1301      | 18.4%   |
| 1001-2000      | 968       | 13.69%  |
| More than 3000 | 749       | 10.59%  |
| 2001-3000      | 408       | 5.77%   |
| 51-100         | 260       | 3.68%   |
| Unknown        | 182       | 2.57%   |
| 21-50          | 108       | 1.53%   |
| 1-20           | 99        | 1.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1380      | 18.72%  |
| 101-250        | 1279      | 17.35%  |
| 21-50          | 1033      | 14.01%  |
| 251-500        | 921       | 12.49%  |
| 51-100         | 888       | 12.05%  |
| 501-1000       | 757       | 10.27%  |
| 1001-2000      | 474       | 6.43%   |
| More than 3000 | 277       | 3.76%   |
| Unknown        | 182       | 2.47%   |
| 2001-3000      | 179       | 2.43%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                                 | 15        | 17     | 1.88%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 15        | 15     | 1.88%   |
| HGST HTS721010A9E630 1TB                                        | 11        | 11     | 1.38%   |
| HGST HTS541010A9E680 1TB                                        | 8         | 8      | 1%      |
| Seagate ST9500325AS 500GB                                       | 7         | 7      | 0.88%   |
| Seagate ST500LT012-1DG142 500GB                                 | 7         | 8      | 0.88%   |
| Seagate ST500LM021-1KJ152 500GB                                 | 7         | 10     | 0.88%   |
| Seagate ST2000DM008-2FR102 2TB                                  | 7         | 10     | 0.88%   |
| Kingston SV300S37A120G 120GB SSD                                | 7         | 7      | 0.88%   |
| WDC WD5000AAKX-001CA0 500GB                                     | 6         | 7      | 0.75%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                        | 6         | 6      | 0.75%   |
| WDC WD20EARS-00MVWB0 2TB                                        | 6         | 8      | 0.75%   |
| Toshiba MQ01ABD100 1TB                                          | 6         | 9      | 0.75%   |
| Seagate ST2000DM006-2DM164 2TB                                  | 6         | 7      | 0.75%   |
| Seagate ST1000LX015-1U7172 1TB                                  | 6         | 8      | 0.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 6         | 10     | 0.75%   |
| Seagate ST1000DM010-2EP102 1TB                                  | 6         | 7      | 0.75%   |
| OCZ VERTEX4 256GB SSD                                           | 6         | 9      | 0.75%   |
| WDC WD10EZEX-08WN4A0 1TB                                        | 5         | 5      | 0.63%   |
| Seagate ST31000528AS 1TB                                        | 5         | 5      | 0.63%   |
| Seagate ST1000LM014-SSHD-8GB                                    | 5         | 5      | 0.63%   |
| Seagate ST1000DM003-9YN162 1TB                                  | 5         | 5      | 0.63%   |
| Samsung Electronics SSD 960 EVO 250GB                           | 5         | 11     | 0.63%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 500GB | 5         | 6      | 0.63%   |
| HGST HTS725050A7E630 500GB                                      | 5         | 5      | 0.63%   |
| HGST HTS545050A7E680 500GB                                      | 5         | 6      | 0.63%   |
| Crucial CT525MX300SSD1 528GB                                    | 5         | 7      | 0.63%   |
| WDC WD20EARX-00PASB0 2TB                                        | 4         | 4      | 0.5%    |
| WDC WD10EZEX-08M2NA0 1TB                                        | 4         | 4      | 0.5%    |
| WDC WD10EZEX-00WN4A0 1TB                                        | 4         | 4      | 0.5%    |
| WDC WD10EARS-00Y5B1 1TB                                         | 4         | 6      | 0.5%    |
| WDC WD1002FAEX-00Z3A0 1TB                                       | 4         | 5      | 0.5%    |
| Toshiba DT01ACA100 1TB                                          | 4         | 4      | 0.5%    |
| SK hynix HFS128G39TND-N210A 128GB SSD                           | 4         | 4      | 0.5%    |
| Seagate ST9250315AS 250GB                                       | 4         | 4      | 0.5%    |
| Seagate ST3500418AS 500GB                                       | 4         | 5      | 0.5%    |
| Seagate ST3320620AS 320GB                                       | 4         | 4      | 0.5%    |
| Seagate ST31000524AS 1TB                                        | 4         | 4      | 0.5%    |
| Seagate ST2000LM007-1R8174 2TB                                  | 4         | 4      | 0.5%    |
| Seagate ST2000DM001-1ER164 2TB                                  | 4         | 4      | 0.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 212       | 260    | 27.82%  |
| WDC                   | 173       | 234    | 22.7%   |
| Samsung Electronics   | 67        | 90     | 8.79%   |
| Toshiba               | 54        | 66     | 7.09%   |
| Hitachi               | 43        | 46     | 5.64%   |
| HGST                  | 37        | 38     | 4.86%   |
| Kingston              | 23        | 29     | 3.02%   |
| SanDisk               | 20        | 22     | 2.62%   |
| Intel                 | 20        | 23     | 2.62%   |
| Crucial               | 20        | 24     | 2.62%   |
| SK hynix              | 13        | 14     | 1.71%   |
| OCZ                   | 11        | 18     | 1.44%   |
| A-DATA Technology     | 10        | 11     | 1.31%   |
| Micron Technology     | 5         | 6      | 0.66%   |
| LITEON                | 5         | 5      | 0.66%   |
| Corsair               | 4         | 4      | 0.52%   |
| Transcend             | 3         | 10     | 0.39%   |
| Realtek Semiconductor | 3         | 4      | 0.39%   |
| Hewlett-Packard       | 3         | 3      | 0.39%   |
| Drevo                 | 3         | 4      | 0.39%   |
| ASMT                  | 3         | 3      | 0.39%   |
| Apple                 | 3         | 3      | 0.39%   |
| XrayDisk              | 2         | 3      | 0.26%   |
| SSSTC                 | 2         | 2      | 0.26%   |
| SPCC                  | 2         | 3      | 0.26%   |
| PNY                   | 2         | 3      | 0.26%   |
| Plextor               | 2         | 9      | 0.26%   |
| Patriot               | 2         | 2      | 0.26%   |
| Maxtor                | 2         | 2      | 0.26%   |
| China                 | 2         | 2      | 0.26%   |
| VNYEZ                 | 1         | 1      | 0.13%   |
| TO Exter              | 1         | 1      | 0.13%   |
| Silicon Motion        | 1         | 1      | 0.13%   |
| KingSpec              | 1         | 1      | 0.13%   |
| Kingrich              | 1         | 1      | 0.13%   |
| JMicron Technology    | 1         | 1      | 0.13%   |
| INNOVATION IT         | 1         | 1      | 0.13%   |
| GLOWAY                | 1         | 1      | 0.13%   |
| Gigabyte Technology   | 1         | 1      | 0.13%   |
| Fujitsu               | 1         | 1      | 0.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 212       | 260    | 39.41%  |
| WDC                 | 166       | 225    | 30.86%  |
| Toshiba             | 48        | 60     | 8.92%   |
| Hitachi             | 43        | 46     | 7.99%   |
| HGST                | 37        | 38     | 6.88%   |
| Samsung Electronics | 23        | 28     | 4.28%   |
| Apple               | 3         | 3      | 0.56%   |
| Maxtor              | 2         | 2      | 0.37%   |
| ASMT                | 2         | 2      | 0.37%   |
| Hewlett-Packard     | 1         | 1      | 0.19%   |
| Fujitsu             | 1         | 1      | 0.19%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 496       | 666    | 69.47%  |
| SSD  | 173       | 221    | 24.23%  |
| NVMe | 45        | 70     | 6.3%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Kingston SV300S37A120G 120GB SSD                 | 2         | 2      | 14.29%  |
| WDC WD4000FYYZ-01UL1B2 4TB                       | 1         | 1      | 7.14%   |
| WDC WD3200BEKT-60V5T1 320GB                      | 1         | 1      | 7.14%   |
| WDC WD2500BEVT-22ZCT0 250GB                      | 1         | 1      | 7.14%   |
| Union Memory (Shenzhen) RPFTJ128PDD2EWX 128GB    | 1         | 1      | 7.14%   |
| Transcend TS128GMTE850 128GB                     | 1         | 1      | 7.14%   |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 7.14%   |
| Seagate ST32000644NS 2TB                         | 1         | 1      | 7.14%   |
| Samsung Electronics MZVLW128HEGR-000L2 128GB     | 1         | 2      | 7.14%   |
| Samsung Electronics MZNLN128HAHQ-000H1 128GB SSD | 1         | 1      | 7.14%   |
| Samsung Electronics MZ7PC128HAFU-000H1 128GB SSD | 1         | 1      | 7.14%   |
| Samsung Electronics HM251JI 250GB                | 1         | 1      | 7.14%   |
| Phison ESO128GTLC9-E8C-2 128GB                   | 1         | 1      | 7.14%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 4         | 5      | 28.57%  |
| WDC                     | 3         | 3      | 21.43%  |
| Seagate                 | 2         | 2      | 14.29%  |
| Kingston                | 2         | 2      | 14.29%  |
| Union Memory (Shenzhen) | 1         | 1      | 7.14%   |
| Transcend               | 1         | 1      | 7.14%   |
| Phison                  | 1         | 1      | 7.14%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3633      | 7960   | 47.31%  |
| Detected | 3349      | 6836   | 43.61%  |
| Malfunc  | 682       | 957    | 8.88%   |
| Failed   | 14        | 15     | 0.18%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3715      | 38.57%  |
| AMD                              | 1825      | 18.95%  |
| Samsung Electronics              | 1413      | 14.67%  |
| SanDisk                          | 588       | 6.1%    |
| SK hynix                         | 299       | 3.1%    |
| Phison Electronics               | 250       | 2.6%    |
| ASMedia Technology               | 191       | 1.98%   |
| Kingston Technology Company      | 190       | 1.97%   |
| Micron Technology                | 167       | 1.73%   |
| Toshiba America Info Systems     | 153       | 1.59%   |
| Micron/Crucial Technology        | 130       | 1.35%   |
| ADATA Technology                 | 109       | 1.13%   |
| Silicon Motion                   | 100       | 1.04%   |
| KIOXIA                           | 78        | 0.81%   |
| Marvell Technology Group         | 74        | 0.77%   |
| Realtek Semiconductor            | 41        | 0.43%   |
| JMicron Technology               | 41        | 0.43%   |
| Union Memory (Shenzhen)          | 25        | 0.26%   |
| Lite-On Technology               | 21        | 0.22%   |
| Broadcom / LSI                   | 21        | 0.22%   |
| Solid State Storage Technology   | 20        | 0.21%   |
| Yangtze Memory Technologies      | 19        | 0.2%    |
| Nvidia                           | 19        | 0.2%    |
| Lenovo                           | 18        | 0.19%   |
| Apple                            | 18        | 0.19%   |
| MAXIO Technology (Hangzhou)      | 17        | 0.18%   |
| Seagate Technology               | 16        | 0.17%   |
| LSI Logic / Symbios Logic        | 11        | 0.11%   |
| Adaptec                          | 10        | 0.1%    |
| Shenzhen Longsys Electronics     | 9         | 0.09%   |
| VIA Technologies                 | 7         | 0.07%   |
| Silicon Image                    | 7         | 0.07%   |
| Hewlett-Packard                  | 6         | 0.06%   |
| Silicon Integrated Systems [SiS] | 4         | 0.04%   |
| OCZ Technology Group             | 4         | 0.04%   |
| Netac Technology                 | 4         | 0.04%   |
| INNOGRIT                         | 3         | 0.03%   |
| Biwin Storage Technology         | 3         | 0.03%   |
| Integrated Technology Express    | 2         | 0.02%   |
| Transcend                        | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1381      | 12.83%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 808       | 7.51%   |
| AMD 400 Series Chipset SATA Controller                                         | 417       | 3.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 348       | 3.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 236       | 2.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 223       | 2.07%   |
| Samsung NVMe SSD Controller 980                                                | 221       | 2.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 214       | 1.99%   |
| AMD 500 Series Chipset SATA Controller                                         | 197       | 1.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 194       | 1.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 192       | 1.78%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 182       | 1.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 175       | 1.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 172       | 1.6%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 164       | 1.52%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 155       | 1.44%   |
| Intel Volume Management Device NVMe RAID Controller                            | 152       | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 133       | 1.24%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 131       | 1.22%   |
| Phison E12 NVMe Controller                                                     | 125       | 1.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 123       | 1.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 120       | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 117       | 1.09%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 114       | 1.06%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 113       | 1.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 111       | 1.03%   |
| Intel SSD 660P Series                                                          | 108       | 1%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 84        | 0.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 83        | 0.77%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 82        | 0.76%   |
| Intel SATA Controller [RAID mode]                                              | 78        | 0.72%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 75        | 0.7%    |
| AMD 300 Series Chipset SATA Controller                                         | 75        | 0.7%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 69        | 0.64%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 69        | 0.64%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 69        | 0.64%   |
| Intel Comet Lake SATA AHCI Controller                                          | 67        | 0.62%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 65        | 0.6%    |
| AMD X370 Series Chipset SATA Controller                                        | 64        | 0.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 61        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 4875      | 52.48%  |
| NVMe | 3533      | 38.03%  |
| RAID | 517       | 5.57%   |
| IDE  | 332       | 3.57%   |
| SAS  | 24        | 0.26%   |
| SCSI | 8         | 0.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor     | Computers | Percent |
|------------|-----------|---------|
| Intel      | 4473      | 66.09%  |
| AMD        | 2294      | 33.89%  |
| thead,c906 | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 118       | 1.74%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 110       | 1.62%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 102       | 1.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 88        | 1.3%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 84        | 1.24%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 83        | 1.22%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 83        | 1.22%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 79        | 1.16%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 79        | 1.16%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 77        | 1.13%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 77        | 1.13%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 68        | 1%      |
| AMD Ryzen 7 2700X Eight-Core Processor        | 65        | 0.96%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 56        | 0.82%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 55        | 0.81%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 55        | 0.81%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 54        | 0.8%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 53        | 0.78%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 53        | 0.78%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 52        | 0.77%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 52        | 0.77%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 52        | 0.77%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 50        | 0.74%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 49        | 0.72%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 49        | 0.72%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 48        | 0.71%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 47        | 0.69%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 45        | 0.66%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 43        | 0.63%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 43        | 0.63%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 41        | 0.6%    |
| AMD Ryzen 5 1600 Six-Core Processor           | 39        | 0.57%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 38        | 0.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 38        | 0.56%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 38        | 0.56%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 38        | 0.56%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 38        | 0.56%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 37        | 0.54%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 37        | 0.54%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 35        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1519      | 22.41%  |
| Intel Core i5           | 1411      | 20.82%  |
| AMD Ryzen 5             | 746       | 11.01%  |
| AMD Ryzen 7             | 695       | 10.25%  |
| Other                   | 515       | 7.6%    |
| Intel Core i3           | 307       | 4.53%   |
| AMD Ryzen 9             | 269       | 3.97%   |
| Intel Celeron           | 167       | 2.46%   |
| Intel Xeon              | 128       | 1.89%   |
| Intel Core 2 Duo        | 107       | 1.58%   |
| AMD Ryzen 3             | 99        | 1.46%   |
| Intel Pentium           | 91        | 1.34%   |
| AMD FX                  | 89        | 1.31%   |
| AMD Ryzen 7 PRO         | 74        | 1.09%   |
| Intel Core i9           | 72        | 1.06%   |
| Intel Atom              | 56        | 0.83%   |
| AMD A8                  | 36        | 0.53%   |
| AMD Ryzen Threadripper  | 33        | 0.49%   |
| AMD Ryzen 5 PRO         | 33        | 0.49%   |
| Intel Core 2 Quad       | 28        | 0.41%   |
| AMD A10                 | 28        | 0.41%   |
| AMD A6                  | 27        | 0.4%    |
| Intel Pentium Dual-Core | 21        | 0.31%   |
| AMD Athlon              | 20        | 0.3%    |
| AMD A4                  | 19        | 0.28%   |
| Intel Pentium Silver    | 18        | 0.27%   |
| AMD Phenom II X4        | 14        | 0.21%   |
| Intel Genuine           | 10        | 0.15%   |
| Intel Core m3           | 10        | 0.15%   |
| AMD E2                  | 10        | 0.15%   |
| AMD Athlon II X4        | 9         | 0.13%   |
| AMD Athlon II X2        | 9         | 0.13%   |
| AMD E                   | 8         | 0.12%   |
| Intel Core 2            | 7         | 0.1%    |
| AMD Phenom II X6        | 7         | 0.1%    |
| Intel Pentium Dual      | 6         | 0.09%   |
| AMD E1                  | 6         | 0.09%   |
| AMD Athlon 64 X2        | 6         | 0.09%   |
| Intel Core m5           | 5         | 0.07%   |
| AMD Athlon X4           | 4         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 2502      | 36.89%  |
| 2       | 1695      | 24.99%  |
| 6       | 1084      | 15.98%  |
| 8       | 993       | 14.64%  |
| 12      | 200       | 2.95%   |
| 16      | 117       | 1.73%   |
| 10      | 45        | 0.66%   |
| 14      | 44        | 0.65%   |
| 1       | 36        | 0.53%   |
| 3       | 29        | 0.43%   |
| 24      | 15        | 0.22%   |
| 32      | 7         | 0.1%    |
| 64      | 4         | 0.06%   |
| Unknown | 3         | 0.04%   |
| 28      | 2         | 0.03%   |
| 18      | 2         | 0.03%   |
| 40      | 1         | 0.01%   |
| 22      | 1         | 0.01%   |
| 20      | 1         | 0.01%   |
| 5       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 6729      | 99.42%  |
| 2       | 38        | 0.56%   |
| Unknown | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5427      | 80.09%  |
| 1       | 1346      | 19.86%  |
| Unknown | 3         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6659      | 98.24%  |
| Unknown        | 115       | 1.7%    |
| 32-bit         | 4         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2521      | 35.73%  |
| 0x08701021 | 211       | 2.99%   |
| 0x306a9    | 208       | 2.95%   |
| 0x906ea    | 202       | 2.86%   |
| 0x306c3    | 200       | 2.83%   |
| 0x206a7    | 180       | 2.55%   |
| 0x906e9    | 172       | 2.44%   |
| 0x806ea    | 169       | 2.4%    |
| 0x0800820d | 150       | 2.13%   |
| 0x806ec    | 138       | 1.96%   |
| 0x806c1    | 136       | 1.93%   |
| 0x506e3    | 123       | 1.74%   |
| 0x0a50000c | 120       | 1.7%    |
| 0x406e3    | 110       | 1.56%   |
| 0x806e9    | 104       | 1.47%   |
| 0x08701013 | 99        | 1.4%    |
| 0x306d4    | 91        | 1.29%   |
| 0x08108102 | 90        | 1.28%   |
| 0x40651    | 87        | 1.23%   |
| 0x08600106 | 87        | 1.23%   |
| 0x08108109 | 82        | 1.16%   |
| 0x1067a    | 68        | 0.96%   |
| 0x08001138 | 64        | 0.91%   |
| 0xa0652    | 62        | 0.88%   |
| 0x0a201016 | 57        | 0.81%   |
| 0x08600104 | 53        | 0.75%   |
| 0x08608103 | 51        | 0.72%   |
| 0x20655    | 50        | 0.71%   |
| 0x0a201009 | 50        | 0.71%   |
| 0x806eb    | 46        | 0.65%   |
| 0x08600103 | 44        | 0.62%   |
| 0x0a50000d | 39        | 0.55%   |
| 0x706e5    | 38        | 0.54%   |
| 0x0a601203 | 38        | 0.54%   |
| 0x906ed    | 36        | 0.51%   |
| 0x0a404102 | 36        | 0.51%   |
| 0x0810100b | 36        | 0.51%   |
| 0x08001137 | 29        | 0.41%   |
| 0x06000852 | 29        | 0.41%   |
| 0x906a3    | 28        | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1458      | 21.48%  |
| Zen 2            | 655       | 9.65%   |
| Haswell          | 496       | 7.31%   |
| Zen 3            | 437       | 6.44%   |
| Zen+             | 429       | 6.32%   |
| Skylake          | 397       | 5.85%   |
| Unknown          | 338       | 4.98%   |
| IvyBridge        | 334       | 4.92%   |
| SandyBridge      | 298       | 4.39%   |
| TigerLake        | 250       | 3.68%   |
| Zen              | 228       | 3.36%   |
| CometLake        | 192       | 2.83%   |
| Broadwell        | 159       | 2.34%   |
| Penryn           | 146       | 2.15%   |
| Icelake          | 114       | 1.68%   |
| Piledriver       | 109       | 1.61%   |
| Silvermont       | 108       | 1.59%   |
| Alderlake Hybrid | 108       | 1.59%   |
| Westmere         | 106       | 1.56%   |
| Goldmont plus    | 57        | 0.84%   |
| K10              | 53        | 0.78%   |
| Excavator        | 48        | 0.71%   |
| Core             | 44        | 0.65%   |
| Nehalem          | 42        | 0.62%   |
| Goldmont         | 33        | 0.49%   |
| Bobcat           | 21        | 0.31%   |
| K10 Llano        | 20        | 0.29%   |
| Steamroller      | 19        | 0.28%   |
| Bonnell          | 19        | 0.28%   |
| Puma             | 18        | 0.27%   |
| Jaguar           | 13        | 0.19%   |
| Tremont          | 11        | 0.16%   |
| K8 Hammer        | 10        | 0.15%   |
| NetBurst         | 7         | 0.1%    |
| Bulldozer        | 7         | 0.1%    |
| P6               | 2         | 0.03%   |
| K8 & K10 hybrid  | 2         | 0.03%   |
| Gracemont        | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3471      | 41.4%   |
| Nvidia                           | 2629      | 31.36%  |
| AMD                              | 2247      | 26.8%   |
| Matrox Electronics Systems       | 18        | 0.21%   |
| ASPEED Technology                | 11        | 0.13%   |
| Silicon Integrated Systems [SiS] | 4         | 0.05%   |
| ATI Technologies                 | 3         | 0.04%   |
| VIA Technologies                 | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 299       | 3.48%   |
| Intel UHD Graphics 620                                                                   | 252       | 2.93%   |
| AMD Renoir                                                                               | 233       | 2.71%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 227       | 2.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 223       | 2.6%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 213       | 2.48%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 198       | 2.3%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 197       | 2.29%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 177       | 2.06%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 176       | 2.05%   |
| Intel HD Graphics 630                                                                    | 159       | 1.85%   |
| Intel HD Graphics 620                                                                    | 158       | 1.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 151       | 1.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 139       | 1.62%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 136       | 1.58%   |
| Intel HD Graphics 5500                                                                   | 121       | 1.41%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 112       | 1.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 110       | 1.28%   |
| AMD Lucienne                                                                             | 104       | 1.21%   |
| Intel HD Graphics 530                                                                    | 100       | 1.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 97        | 1.13%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 96        | 1.12%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 87        | 1.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 87        | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 81        | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 81        | 0.94%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 77        | 0.9%    |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 74        | 0.86%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 73        | 0.85%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 69        | 0.8%    |
| AMD Rembrandt [Radeon 680M]                                                              | 65        | 0.76%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 63        | 0.73%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 61        | 0.71%   |
| Intel Core Processor Integrated Graphics Controller                                      | 60        | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 60        | 0.7%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 57        | 0.66%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 56        | 0.65%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 55        | 0.64%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 54        | 0.63%   |
| Nvidia GP108M [GeForce MX150]                                                            | 53        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 2134      | 31.25%  |
| 1 x AMD                  | 1712      | 25.07%  |
| 1 x Nvidia               | 1263      | 18.49%  |
| Intel + Nvidia           | 1085      | 15.89%  |
| AMD + Nvidia             | 245       | 3.59%   |
| Intel + AMD              | 171       | 2.5%    |
| 2 x AMD                  | 122       | 1.79%   |
| 2 x Nvidia               | 34        | 0.5%    |
| 2 x Intel                | 14        | 0.21%   |
| 1 x Matrox               | 13        | 0.19%   |
| Other                    | 8         | 0.12%   |
| 1 x ASPEED               | 6         | 0.09%   |
| 1 x SiS                  | 4         | 0.06%   |
| AMD + ASPEED             | 4         | 0.06%   |
| Nvidia + Matrox          | 3         | 0.04%   |
| 2 x AMD + 1 x Nvidia     | 2         | 0.03%   |
| Intel + 2 x Nvidia       | 2         | 0.03%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.03%   |
| AMD + Matrox             | 2         | 0.03%   |
| 3 x Nvidia               | 1         | 0.01%   |
| 1 x VIA                  | 1         | 0.01%   |
| Nvidia + ASPEED          | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4909      | 71.75%  |
| Proprietary | 1861      | 27.2%   |
| Unknown     | 72        | 1.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3790      | 54.27%  |
| 7.01-8.0   | 673       | 9.64%   |
| 1.01-2.0   | 620       | 8.88%   |
| 0.01-0.5   | 533       | 7.63%   |
| 3.01-4.0   | 532       | 7.62%   |
| 0.51-1.0   | 280       | 4.01%   |
| 5.01-6.0   | 265       | 3.79%   |
| 8.01-16.0  | 212       | 3.04%   |
| 2.01-3.0   | 56        | 0.8%    |
| 16.01-24.0 | 18        | 0.26%   |
| 4.01-5.0   | 3         | 0.04%   |
| 32.01-64.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 900       | 10.94%  |
| Samsung Electronics     | 896       | 10.89%  |
| BOE                     | 749       | 9.11%   |
| Chimei Innolux          | 651       | 7.91%   |
| LG Display              | 626       | 7.61%   |
| Dell                    | 568       | 6.9%    |
| Goldstar                | 492       | 5.98%   |
| Acer                    | 320       | 3.89%   |
| AOC                     | 271       | 3.29%   |
| BenQ                    | 250       | 3.04%   |
| Hewlett-Packard         | 236       | 2.87%   |
| Sharp                   | 219       | 2.66%   |
| Ancor Communications    | 207       | 2.52%   |
| Philips                 | 155       | 1.88%   |
| Lenovo                  | 139       | 1.69%   |
| PANDA                   | 118       | 1.43%   |
| ViewSonic               | 105       | 1.28%   |
| Apple                   | 97        | 1.18%   |
| ASUSTek Computer        | 96        | 1.17%   |
| Iiyama                  | 90        | 1.09%   |
| InfoVision              | 60        | 0.73%   |
| LG Electronics          | 58        | 0.71%   |
| MSI                     | 47        | 0.57%   |
| CSO                     | 46        | 0.56%   |
| Sony                    | 45        | 0.55%   |
| Unknown                 | 41        | 0.5%    |
| Gigabyte Technology     | 37        | 0.45%   |
| NEC Computers           | 36        | 0.44%   |
| Eizo                    | 33        | 0.4%    |
| Chi Mei Optoelectronics | 33        | 0.4%    |
| Panasonic               | 23        | 0.28%   |
| Fujitsu Siemens         | 22        | 0.27%   |
| TMX                     | 21        | 0.26%   |
| Sceptre Tech            | 20        | 0.24%   |
| Unknown                 | 20        | 0.24%   |
| Toshiba                 | 16        | 0.19%   |
| HannStar                | 16        | 0.19%   |
| Vizio                   | 15        | 0.18%   |
| Valve                   | 14        | 0.17%   |
| Pixio                   | 14        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 50        | 0.58%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 42        | 0.49%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 38        | 0.44%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 37        | 0.43%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 32        | 0.37%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 31        | 0.36%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 29        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 29        | 0.34%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 28        | 0.33%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 26        | 0.3%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 25        | 0.29%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                   | 24        | 0.28%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 22        | 0.26%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 22        | 0.26%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 21        | 0.24%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 21        | 0.24%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 21        | 0.24%   |
| Unknown                                                              | 20        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 19        | 0.22%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 19        | 0.22%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 18        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 18        | 0.21%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch     | 18        | 0.21%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 16        | 0.19%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                | 16        | 0.19%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 16        | 0.19%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                     | 16        | 0.19%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 15        | 0.17%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 15        | 0.17%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 15        | 0.17%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 15        | 0.17%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 15        | 0.17%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 14        | 0.16%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 14        | 0.16%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch             | 14        | 0.16%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 14        | 0.16%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 14        | 0.16%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 14        | 0.16%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 14        | 0.16%   |
| AOC 27G2WG3 AOC2702 1920x1080 598x336mm 27.0-inch                    | 14        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3730      | 48.18%  |
| 1366x768 (WXGA)    | 885       | 11.43%  |
| 3840x2160 (4K)     | 617       | 7.97%   |
| 2560x1440 (QHD)    | 602       | 7.78%   |
| 1920x1200 (WUXGA)  | 226       | 2.92%   |
| 1600x900 (HD+)     | 202       | 2.61%   |
| 1680x1050 (WSXGA+) | 150       | 1.94%   |
| 3440x1440          | 141       | 1.82%   |
| 1280x1024 (SXGA)   | 129       | 1.67%   |
| Unknown            | 129       | 1.67%   |
| 1440x900 (WXGA+)   | 107       | 1.38%   |
| 2560x1600          | 93        | 1.2%    |
| 2560x1080          | 90        | 1.16%   |
| 1280x800 (WXGA)    | 59        | 0.76%   |
| 3840x1080          | 58        | 0.75%   |
| 2880x1800          | 56        | 0.72%   |
| 1360x768           | 49        | 0.63%   |
| 3840x2400          | 43        | 0.56%   |
| 2160x1440          | 26        | 0.34%   |
| 2256x1504          | 24        | 0.31%   |
| 3840x1600          | 22        | 0.28%   |
| 3200x1800 (QHD+)   | 21        | 0.27%   |
| 1920x540           | 20        | 0.26%   |
| 2736x1824          | 18        | 0.23%   |
| 3000x2000          | 13        | 0.17%   |
| 1600x1200          | 11        | 0.14%   |
| 7680x2160          | 10        | 0.13%   |
| 3200x2000          | 10        | 0.13%   |
| 3072x1920          | 10        | 0.13%   |
| 1920x1280          | 10        | 0.13%   |
| 5760x1080          | 9         | 0.12%   |
| 4480x1440          | 9         | 0.12%   |
| 2240x1400          | 9         | 0.12%   |
| 5120x1440          | 8         | 0.1%    |
| 1024x600           | 8         | 0.1%    |
| 1280x720 (HD)      | 7         | 0.09%   |
| 1024x768 (XGA)     | 7         | 0.09%   |
| 800x1280           | 5         | 0.06%   |
| 6400x2160          | 5         | 0.06%   |
| 3840x1200          | 5         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1828      | 22.34%  |
| 13      | 815       | 9.96%   |
| 27      | 804       | 9.83%   |
| 24      | 772       | 9.44%   |
| 14      | 703       | 8.59%   |
| 23      | 533       | 6.51%   |
| 21      | 460       | 5.62%   |
| Unknown | 406       | 4.96%   |
| 17      | 286       | 3.5%    |
| 34      | 192       | 2.35%   |
| 31      | 178       | 2.18%   |
| 19      | 156       | 1.91%   |
| 12      | 139       | 1.7%    |
| 18      | 112       | 1.37%   |
| 22      | 109       | 1.33%   |
| 16      | 89        | 1.09%   |
| 20      | 76        | 0.93%   |
| 11      | 60        | 0.73%   |
| 84      | 42        | 0.51%   |
| 72      | 41        | 0.5%    |
| 25      | 41        | 0.5%    |
| 54      | 28        | 0.34%   |
| 40      | 28        | 0.34%   |
| 48      | 26        | 0.32%   |
| 32      | 26        | 0.32%   |
| 26      | 25        | 0.31%   |
| 28      | 23        | 0.28%   |
| 10      | 21        | 0.26%   |
| 37      | 19        | 0.23%   |
| 29      | 19        | 0.23%   |
| 46      | 12        | 0.15%   |
| 35      | 11        | 0.13%   |
| 65      | 10        | 0.12%   |
| 33      | 10        | 0.12%   |
| 49      | 7         | 0.09%   |
| 43      | 7         | 0.09%   |
| 42      | 7         | 0.09%   |
| 39      | 7         | 0.09%   |
| 74      | 5         | 0.06%   |
| 57      | 5         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2969      | 37.51%  |
| 501-600        | 1884      | 23.8%   |
| 401-500        | 807       | 10.19%  |
| 201-300        | 668       | 8.44%   |
| Unknown        | 406       | 5.13%   |
| 351-400        | 362       | 4.57%   |
| 601-700        | 298       | 3.76%   |
| 701-800        | 231       | 2.92%   |
| 1001-1500      | 105       | 1.33%   |
| 1501-2000      | 89        | 1.12%   |
| 801-900        | 70        | 0.88%   |
| 901-1000       | 15        | 0.19%   |
| More than 2000 | 5         | 0.06%   |
| 1-100          | 4         | 0.05%   |
| 101-200        | 3         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 5374      | 75.37%  |
| 16/10   | 826       | 11.58%  |
| Unknown | 346       | 4.85%   |
| 21/9    | 237       | 3.32%   |
| 5/4     | 129       | 1.81%   |
| 3/2     | 122       | 1.71%   |
| 4/3     | 35        | 0.49%   |
| 32/9    | 34        | 0.48%   |
| 2.65    | 4         | 0.06%   |
| 1.00    | 4         | 0.06%   |
| 6/5     | 3         | 0.04%   |
| 3.40    | 3         | 0.04%   |
| 2.00    | 3         | 0.04%   |
| 1.96    | 2         | 0.03%   |
| 0.67    | 2         | 0.03%   |
| 3.20    | 1         | 0.01%   |
| 1.03    | 1         | 0.01%   |
| 0.89    | 1         | 0.01%   |
| 0.62    | 1         | 0.01%   |
| 0.58    | 1         | 0.01%   |
| 0.57    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1814      | 22.51%  |
| 201-250        | 1467      | 18.2%   |
| 81-90          | 1149      | 14.26%  |
| 301-350        | 826       | 10.25%  |
| 351-500        | 438       | 5.43%   |
| Unknown        | 406       | 5.04%   |
| 71-80          | 367       | 4.55%   |
| 151-200        | 330       | 4.09%   |
| 251-300        | 282       | 3.5%    |
| 121-130        | 201       | 2.49%   |
| More than 1000 | 156       | 1.94%   |
| 141-150        | 146       | 1.81%   |
| 61-70          | 124       | 1.54%   |
| 501-1000       | 117       | 1.45%   |
| 111-120        | 87        | 1.08%   |
| 51-60          | 65        | 0.81%   |
| 131-140        | 31        | 0.38%   |
| 91-100         | 29        | 0.36%   |
| 41-50          | 19        | 0.24%   |
| 1-40           | 6         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 2350      | 30.26%  |
| 51-100        | 2261      | 29.11%  |
| 101-120       | 1651      | 21.26%  |
| 161-240       | 681       | 8.77%   |
| Unknown       | 406       | 5.23%   |
| More than 240 | 291       | 3.75%   |
| 1-50          | 127       | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 5021      | 72.43%  |
| 2     | 1496      | 21.58%  |
| 3     | 254       | 3.66%   |
| 0     | 137       | 1.98%   |
| 4     | 21        | 0.3%    |
| 5     | 2         | 0.03%   |
| 6     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 3828      | 37.95%  |
| Realtek Semiconductor             | 3635      | 36.04%  |
| Qualcomm Atheros                  | 910       | 9.02%   |
| Broadcom                          | 360       | 3.57%   |
| MediaTek                          | 222       | 2.2%    |
| TP-Link                           | 104       | 1.03%   |
| Ralink Technology                 | 83        | 0.82%   |
| Microsoft                         | 69        | 0.68%   |
| Broadcom Limited                  | 65        | 0.64%   |
| Marvell Technology Group          | 62        | 0.61%   |
| ASIX Electronics                  | 56        | 0.56%   |
| Ralink                            | 50        | 0.5%    |
| Lenovo                            | 49        | 0.49%   |
| Qualcomm                          | 40        | 0.4%    |
| Sierra Wireless                   | 35        | 0.35%   |
| Samsung Electronics               | 35        | 0.35%   |
| Xiaomi                            | 30        | 0.3%    |
| DisplayLink                       | 29        | 0.29%   |
| Aquantia                          | 28        | 0.28%   |
| Ericsson Business Mobile Networks | 27        | 0.27%   |
| D-Link                            | 23        | 0.23%   |
| NetGear                           | 21        | 0.21%   |
| Dell                              | 19        | 0.19%   |
| Qualcomm Atheros Communications   | 18        | 0.18%   |
| Google                            | 18        | 0.18%   |
| Apple                             | 16        | 0.16%   |
| Nvidia                            | 15        | 0.15%   |
| Hewlett-Packard                   | 15        | 0.15%   |
| Mellanox Technologies             | 14        | 0.14%   |
| Huawei Technologies               | 14        | 0.14%   |
| Microchip Technology              | 11        | 0.11%   |
| ASUSTek Computer                  | 11        | 0.11%   |
| OPPO Electronics                  | 9         | 0.09%   |
| Linksys                           | 8         | 0.08%   |
| D-Link System                     | 8         | 0.08%   |
| Cypress Semiconductor             | 8         | 0.08%   |
| Oculus VR                         | 7         | 0.07%   |
| Motorola PCS                      | 7         | 0.07%   |
| Fibocom                           | 7         | 0.07%   |
| JMicron Technology                | 6         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2554      | 21.47%  |
| Intel Wi-Fi 6 AX200                                               | 580       | 4.88%   |
| Intel I211 Gigabit Network Connection                             | 398       | 3.35%   |
| Intel Wireless 8265 / 8275                                        | 288       | 2.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 261       | 2.19%   |
| Realtek RTL8125 2.5GbE Controller                                 | 243       | 2.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 226       | 1.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 188       | 1.58%   |
| Intel Wi-Fi 6 AX201                                               | 187       | 1.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 173       | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 170       | 1.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 169       | 1.42%   |
| Intel Ethernet Connection (2) I219-V                              | 163       | 1.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 159       | 1.34%   |
| Intel Wireless 8260                                               | 150       | 1.26%   |
| Intel Wireless 7265                                               | 150       | 1.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 132       | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 130       | 1.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 123       | 1.03%   |
| Intel Wireless-AC 9260                                            | 111       | 0.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 110       | 0.92%   |
| Intel Wireless 7260                                               | 110       | 0.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 104       | 0.87%   |
| Intel Ethernet Controller I225-V                                  | 101       | 0.85%   |
| Intel Wireless 3165                                               | 99        | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 96        | 0.81%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 96        | 0.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 95        | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 94        | 0.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 93        | 0.78%   |
| Intel Ethernet Connection (7) I219-V                              | 92        | 0.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 89        | 0.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 88        | 0.74%   |
| Intel Ethernet Connection I217-LM                                 | 79        | 0.66%   |
| Intel Ethernet Connection (4) I219-LM                             | 73        | 0.61%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 68        | 0.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 67        | 0.56%   |
| Intel Ethernet Connection (4) I219-V                              | 60        | 0.5%    |
| Intel Wireless 3160                                               | 52        | 0.44%   |
| Intel Ethernet Connection (2) I218-V                              | 52        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 3004      | 53.97%  |
| Realtek Semiconductor                 | 785       | 14.1%   |
| Qualcomm Atheros                      | 713       | 12.81%  |
| Broadcom                              | 271       | 4.87%   |
| MediaTek                              | 218       | 3.92%   |
| TP-Link                               | 90        | 1.62%   |
| Ralink Technology                     | 83        | 1.49%   |
| Microsoft                             | 61        | 1.1%    |
| Ralink                                | 50        | 0.9%    |
| Broadcom Limited                      | 50        | 0.9%    |
| Sierra Wireless                       | 35        | 0.63%   |
| Qualcomm                              | 34        | 0.61%   |
| Marvell Technology Group              | 22        | 0.4%    |
| D-Link                                | 20        | 0.36%   |
| NetGear                               | 19        | 0.34%   |
| Qualcomm Atheros Communications       | 18        | 0.32%   |
| Dell                                  | 12        | 0.22%   |
| Ericsson Business Mobile Networks     | 11        | 0.2%    |
| ASUSTek Computer                      | 11        | 0.2%    |
| Linksys                               | 8         | 0.14%   |
| Fibocom                               | 7         | 0.13%   |
| Hewlett-Packard                       | 6         | 0.11%   |
| Edimax Technology                     | 6         | 0.11%   |
| D-Link System                         | 4         | 0.07%   |
| AVM                                   | 4         | 0.07%   |
| Wilocity                              | 3         | 0.05%   |
| Mercucys                              | 3         | 0.05%   |
| Belkin Components                     | 3         | 0.05%   |
| Xiaomi                                | 2         | 0.04%   |
| Tenda                                 | 2         | 0.04%   |
| Micro Star International              | 2         | 0.04%   |
| IMC Networks                          | 2         | 0.04%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| Yoctopuce Sarl                        | 1         | 0.02%   |
| Sagem                                 | 1         | 0.02%   |
| Quectel Wireless Solutions            | 1         | 0.02%   |
| BUFFALO                               | 1         | 0.02%   |
| AboCom Systems                        | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 580       | 10.38%  |
| Intel Wireless 8265 / 8275                                     | 288       | 5.15%   |
| Intel Wi-Fi 6 AX201                                            | 187       | 3.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 173       | 3.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 170       | 3.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 169       | 3.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 159       | 2.84%   |
| Intel Wireless 8260                                            | 150       | 2.68%   |
| Intel Wireless 7265                                            | 150       | 2.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 132       | 2.36%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 130       | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 123       | 2.2%    |
| Intel Wireless-AC 9260                                         | 111       | 1.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 110       | 1.97%   |
| Intel Wireless 7260                                            | 110       | 1.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 104       | 1.86%   |
| Intel Wireless 3165                                            | 99        | 1.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 96        | 1.72%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 96        | 1.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 95        | 1.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 94        | 1.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 93        | 1.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 89        | 1.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 88        | 1.57%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 68        | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 67        | 1.2%    |
| Intel Wireless 3160                                            | 52        | 0.93%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 49        | 0.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 48        | 0.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 47        | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 43        | 0.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 41        | 0.73%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 41        | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 36        | 0.64%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 36        | 0.64%   |
| Broadcom BCM43142 802.11b/g/n                                  | 34        | 0.61%   |
| Realtek 802.11ac NIC                                           | 33        | 0.59%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 33        | 0.59%   |
| Microsoft Xbox 360 Wireless Adapter                            | 32        | 0.57%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 31        | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3302      | 54.66%  |
| Intel                                  | 1888      | 31.25%  |
| Qualcomm Atheros                       | 261       | 4.32%   |
| Broadcom                               | 137       | 2.27%   |
| ASIX Electronics                       | 56        | 0.93%   |
| Lenovo                                 | 45        | 0.74%   |
| Marvell Technology Group               | 40        | 0.66%   |
| Samsung Electronics                    | 35        | 0.58%   |
| DisplayLink                            | 29        | 0.48%   |
| Xiaomi                                 | 28        | 0.46%   |
| Aquantia                               | 28        | 0.46%   |
| Google                                 | 16        | 0.26%   |
| Apple                                  | 16        | 0.26%   |
| Nvidia                                 | 15        | 0.25%   |
| Broadcom Limited                       | 15        | 0.25%   |
| TP-Link                                | 14        | 0.23%   |
| Mellanox Technologies                  | 12        | 0.2%    |
| OPPO Electronics                       | 9         | 0.15%   |
| Cypress Semiconductor                  | 8         | 0.13%   |
| Microsoft                              | 7         | 0.12%   |
| Huawei Technologies                    | 7         | 0.12%   |
| Qualcomm                               | 6         | 0.1%    |
| JMicron Technology                     | 6         | 0.1%    |
| Motorola PCS                           | 5         | 0.08%   |
| ZTE WCDMA Technologies MSM             | 4         | 0.07%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.07%   |
| MediaTek                               | 4         | 0.07%   |
| ICS Advent                             | 4         | 0.07%   |
| D-Link System                          | 4         | 0.07%   |
| QLogic                                 | 3         | 0.05%   |
| Hewlett-Packard                        | 3         | 0.05%   |
| D-Link                                 | 3         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.03%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.03%   |
| NetGear                                | 2         | 0.03%   |
| IBM                                    | 2         | 0.03%   |
| HMD Global                             | 2         | 0.03%   |
| American Megatrends                    | 2         | 0.03%   |
| Xilinx                                 | 1         | 0.02%   |
| VIA Technologies                       | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2554      | 41.24%  |
| Intel I211 Gigabit Network Connection                             | 398       | 6.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 261       | 4.21%   |
| Realtek RTL8125 2.5GbE Controller                                 | 243       | 3.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 226       | 3.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 188       | 3.04%   |
| Intel Ethernet Connection (2) I219-V                              | 163       | 2.63%   |
| Intel Ethernet Controller I225-V                                  | 101       | 1.63%   |
| Intel Ethernet Connection (7) I219-V                              | 92        | 1.49%   |
| Intel Ethernet Connection I217-LM                                 | 79        | 1.28%   |
| Intel Ethernet Connection (4) I219-LM                             | 73        | 1.18%   |
| Intel Ethernet Connection (4) I219-V                              | 60        | 0.97%   |
| Intel Ethernet Connection (2) I218-V                              | 52        | 0.84%   |
| Intel Ethernet Connection (6) I219-V                              | 48        | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                     | 47        | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 46        | 0.74%   |
| Intel Ethernet Connection I219-LM                                 | 45        | 0.73%   |
| Intel Ethernet Connection (3) I218-LM                             | 45        | 0.73%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 43        | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 42        | 0.68%   |
| Intel 82579V Gigabit Network Connection                           | 42        | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 39        | 0.63%   |
| Intel Ethernet Connection I218-LM                                 | 38        | 0.61%   |
| Intel Ethernet Connection (7) I219-LM                             | 37        | 0.6%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 34        | 0.55%   |
| Intel 82577LM Gigabit Network Connection                          | 32        | 0.52%   |
| Intel I210 Gigabit Network Connection                             | 31        | 0.5%    |
| Intel Ethernet Connection I217-V                                  | 28        | 0.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 27        | 0.44%   |
| Intel Ethernet Connection (6) I219-LM                             | 27        | 0.44%   |
| Intel 82567LM Gigabit Network Connection                          | 25        | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 24        | 0.39%   |
| Intel 82574L Gigabit Network Connection                           | 24        | 0.39%   |
| Intel Ethernet Connection (10) I219-V                             | 23        | 0.37%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 23        | 0.37%   |
| Intel Ethernet Connection I219-V                                  | 22        | 0.36%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 19        | 0.31%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 18        | 0.29%   |
| Intel Ethernet Connection (5) I219-LM                             | 18        | 0.29%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 17        | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 5622      | 50.99%  |
| WiFi     | 5296      | 48.03%  |
| Modem    | 91        | 0.83%   |
| Unknown  | 17        | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4054      | 56.79%  |
| Ethernet | 3082      | 43.18%  |
| Modem    | 2         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3577      | 52.6%   |
| 1     | 2926      | 43.03%  |
| 3     | 201       | 2.96%   |
| 0     | 58        | 0.85%   |
| 4     | 23        | 0.34%   |
| 5     | 7         | 0.1%    |
| 6     | 5         | 0.07%   |
| 10    | 1         | 0.01%   |
| 9     | 1         | 0.01%   |
| 8     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5647      | 82.09%  |
| Yes  | 1232      | 17.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2650      | 54.39%  |
| Realtek Semiconductor           | 434       | 8.91%   |
| Cambridge Silicon Radio         | 323       | 6.63%   |
| Qualcomm Atheros Communications | 281       | 5.77%   |
| IMC Networks                    | 186       | 3.82%   |
| Broadcom                        | 177       | 3.63%   |
| Foxconn / Hon Hai               | 155       | 3.18%   |
| Lite-On Technology              | 149       | 3.06%   |
| ASUSTek Computer                | 111       | 2.28%   |
| Apple                           | 98        | 2.01%   |
| MediaTek                        | 51        | 1.05%   |
| Realtek                         | 49        | 1.01%   |
| Dell                            | 34        | 0.7%    |
| TP-Link                         | 22        | 0.45%   |
| Marvell Semiconductor           | 20        | 0.41%   |
| Hewlett-Packard                 | 20        | 0.41%   |
| HTC (High Tech Computer)        | 14        | 0.29%   |
| USI                             | 13        | 0.27%   |
| Toshiba                         | 13        | 0.27%   |
| Ralink                          | 12        | 0.25%   |
| Foxconn International           | 8         | 0.16%   |
| Edimax Technology               | 8         | 0.16%   |
| Dynex                           | 6         | 0.12%   |
| Opticis                         | 4         | 0.08%   |
| Integrated System Solution      | 4         | 0.08%   |
| Smart Modular Technologies      | 3         | 0.06%   |
| Micro Star International        | 3         | 0.06%   |
| Chicony Electronics             | 3         | 0.06%   |
| Askey Computer                  | 3         | 0.06%   |
| SINO WEALTH                     | 2         | 0.04%   |
| Ralink Technology               | 2         | 0.04%   |
| ISSC                            | 2         | 0.04%   |
| Belkin Components               | 2         | 0.04%   |
| Alps Electric                   | 2         | 0.04%   |
| Actions                         | 2         | 0.04%   |
| Syntek                          | 1         | 0.02%   |
| Roper                           | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| Cypress Semiconductor           | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 818       | 16.76%  |
| Intel AX200 Bluetooth                                                | 557       | 11.41%  |
| Intel AX201 Bluetooth                                                | 422       | 8.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 348       | 7.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 323       | 6.62%   |
| Realtek Bluetooth Radio                                              | 292       | 5.98%   |
| Intel Bluetooth Device                                               | 220       | 4.51%   |
| Qualcomm Atheros  Bluetooth Device                                   | 149       | 3.05%   |
| Intel AX210 Bluetooth                                                | 131       | 2.68%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 103       | 2.11%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 96        | 1.97%   |
| IMC Networks Wireless_Device                                         | 67        | 1.37%   |
| IMC Networks Bluetooth Radio                                         | 63        | 1.29%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 61        | 1.25%   |
| Apple Bluetooth Host Controller                                      | 53        | 1.09%   |
| MediaTek Wireless_Device                                             | 50        | 1.02%   |
| Lite-On Bluetooth Device                                             | 50        | 1.02%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 49        | 1%      |
| Intel Centrino Bluetooth Wireless Transceiver                        | 48        | 0.98%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 48        | 0.98%   |
| Foxconn / Hon Hai Wireless_Device                                    | 42        | 0.86%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 42        | 0.86%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 38        | 0.78%   |
| Realtek 802.11ac WLAN Adapter                                        | 37        | 0.76%   |
| IMC Networks Bluetooth Device                                        | 37        | 0.76%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 37        | 0.76%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                         | 31        | 0.64%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 30        | 0.61%   |
| Apple Bluetooth USB Host Controller                                  | 27        | 0.55%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 26        | 0.53%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                              | 24        | 0.49%   |
| Lite-On Wireless_Device                                              | 23        | 0.47%   |
| TP-Link UB5A Adapter                                                 | 22        | 0.45%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 21        | 0.43%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 18        | 0.37%   |
| Realtek RTL8821A Bluetooth                                           | 16        | 0.33%   |
| Marvell Bluetooth and Wireless LAN Composite                         | 16        | 0.33%   |
| ASUS Bluetooth Radio                                                 | 15        | 0.31%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 14        | 0.29%   |
| USI Bluetooth Device                                                 | 13        | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 4337      | 40.48%  |
| AMD                         | 2615      | 24.41%  |
| Nvidia                      | 1983      | 18.51%  |
| C-Media Electronics         | 246       | 2.3%    |
| Logitech                    | 122       | 1.14%   |
| Kingston Technology         | 91        | 0.85%   |
| Focusrite-Novation          | 74        | 0.69%   |
| Texas Instruments           | 73        | 0.68%   |
| JMTek                       | 66        | 0.62%   |
| SteelSeries ApS             | 61        | 0.57%   |
| Razer USA                   | 61        | 0.57%   |
| Realtek Semiconductor       | 58        | 0.54%   |
| Lenovo                      | 48        | 0.45%   |
| Creative Labs               | 45        | 0.42%   |
| Creative Technology         | 44        | 0.41%   |
| Corsair                     | 42        | 0.39%   |
| Blue Microphones            | 38        | 0.35%   |
| ASUSTek Computer            | 34        | 0.32%   |
| GN Netcom                   | 31        | 0.29%   |
| Samson Technologies         | 27        | 0.25%   |
| Generalplus Technology      | 23        | 0.21%   |
| Yamaha                      | 22        | 0.21%   |
| Valve Software              | 22        | 0.21%   |
| Apple                       | 21        | 0.2%    |
| GYROCOM C&C                 | 20        | 0.19%   |
| BEHRINGER International     | 20        | 0.19%   |
| Sony                        | 19        | 0.18%   |
| Plantronics                 | 16        | 0.15%   |
| RODE Microphones            | 15        | 0.14%   |
| FiiO Electronics Technology | 15        | 0.14%   |
| Audio-Technica              | 15        | 0.14%   |
| XMOS                        | 14        | 0.13%   |
| SAVITECH                    | 14        | 0.13%   |
| Micro Star International    | 14        | 0.13%   |
| M-Audio                     | 13        | 0.12%   |
| Hewlett-Packard             | 11        | 0.1%    |
| DSEA A/S                    | 11        | 0.1%    |
| Cambridge Silicon Radio     | 11        | 0.1%    |
| Microsoft                   | 10        | 0.09%   |
| Dell                        | 10        | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 971       | 7.51%   |
| Intel Sunrise Point-LP HD Audio                                            | 619       | 4.79%   |
| AMD Starship/Matisse HD Audio Controller                                   | 591       | 4.57%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 484       | 3.75%   |
| Intel Cannon Lake PCH cAVS                                                 | 362       | 2.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 330       | 2.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 328       | 2.54%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 300       | 2.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 271       | 2.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 259       | 2%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 253       | 1.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 250       | 1.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 234       | 1.81%   |
| Nvidia GP107GL High Definition Audio Controller                            | 213       | 1.65%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 193       | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 186       | 1.44%   |
| Intel 200 Series PCH HD Audio                                              | 181       | 1.4%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 180       | 1.39%   |
| Nvidia GP104 High Definition Audio Controller                              | 179       | 1.39%   |
| AMD Navi 10 HDMI Audio                                                     | 173       | 1.34%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 147       | 1.14%   |
| Nvidia TU106 High Definition Audio Controller                              | 145       | 1.12%   |
| Nvidia GP106 High Definition Audio Controller                              | 144       | 1.11%   |
| Intel Comet Lake PCH cAVS                                                  | 142       | 1.1%    |
| Intel Broadwell-U Audio Controller                                         | 142       | 1.1%    |
| Intel Haswell-ULT HD Audio Controller                                      | 140       | 1.08%   |
| Intel 8 Series HD Audio Controller                                         | 140       | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 139       | 1.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 137       | 1.06%   |
| Intel CM238 HD Audio Controller                                            | 126       | 0.98%   |
| Nvidia TU116 High Definition Audio Controller                              | 125       | 0.97%   |
| Nvidia GA104 High Definition Audio Controller                              | 119       | 0.92%   |
| Intel Comet Lake PCH-LP cAVS                                               | 119       | 0.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 110       | 0.85%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 109       | 0.84%   |
| Nvidia TU104 HD Audio Controller                                           | 101       | 0.78%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 101       | 0.78%   |
| AMD FCH Azalia Controller                                                  | 100       | 0.77%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 96        | 0.74%   |
| Nvidia GA106 High Definition Audio Controller                              | 87        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 1205      | 20.96%  |
| SK hynix                     | 906       | 15.76%  |
| Kingston                     | 710       | 12.35%  |
| Micron Technology            | 564       | 9.81%   |
| Corsair                      | 553       | 9.62%   |
| Crucial                      | 460       | 8%      |
| G.Skill                      | 359       | 6.25%   |
| Unknown                      | 298       | 5.18%   |
| A-DATA Technology            | 113       | 1.97%   |
| Ramaxel Technology           | 87        | 1.51%   |
| Elpida                       | 53        | 0.92%   |
| Team                         | 52        | 0.9%    |
| Patriot                      | 48        | 0.84%   |
| GOODRAM                      | 35        | 0.61%   |
| Nanya Technology             | 28        | 0.49%   |
| Unknown                      | 28        | 0.49%   |
| Unknown (ABCD)               | 22        | 0.38%   |
| Smart                        | 19        | 0.33%   |
| Transcend                    | 18        | 0.31%   |
| AMD                          | 16        | 0.28%   |
| PNY                          | 15        | 0.26%   |
| Goldkey                      | 9         | 0.16%   |
| Apacer                       | 9         | 0.16%   |
| Smart Brazil                 | 7         | 0.12%   |
| Teikon                       | 6         | 0.1%    |
| Golden Empire                | 6         | 0.1%    |
| Silicon Power                | 5         | 0.09%   |
| Kingmax                      | 5         | 0.09%   |
| GeIL                         | 5         | 0.09%   |
| Avant                        | 5         | 0.09%   |
| Wilk Elektronik              | 4         | 0.07%   |
| Neo Forza                    | 4         | 0.07%   |
| V-GeN                        | 3         | 0.05%   |
| V-Color                      | 3         | 0.05%   |
| Patriot Memory (PDP Systems) | 3         | 0.05%   |
| KLEVV                        | 3         | 0.05%   |
| GSkill                       | 3         | 0.05%   |
| ASint Technology             | 3         | 0.05%   |
| A Force                      | 3         | 0.05%   |
| 48spaces                     | 3         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 70        | 1.14%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 65        | 1.06%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 65        | 1.06%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s       | 60        | 0.98%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s       | 54        | 0.88%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 45        | 0.73%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 40        | 0.65%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 37        | 0.6%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 37        | 0.6%    |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s     | 32        | 0.52%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 31        | 0.51%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 30        | 0.49%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 30        | 0.49%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 30        | 0.49%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 28        | 0.46%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 28        | 0.46%   |
| Unknown                                                     | 28        | 0.46%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 26        | 0.42%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 26        | 0.42%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 26        | 0.42%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 25        | 0.41%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 25        | 0.41%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 25        | 0.41%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s      | 25        | 0.41%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 24        | 0.39%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 24        | 0.39%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s     | 24        | 0.39%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 23        | 0.38%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s      | 23        | 0.38%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s       | 21        | 0.34%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 20        | 0.33%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 20        | 0.33%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 20        | 0.33%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s           | 20        | 0.33%   |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3866MT/s      | 20        | 0.33%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 19        | 0.31%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 19        | 0.31%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 19        | 0.31%   |
| Kingston RAM KHX1600C10D3/8G 4GB DIMM DDR3 1600MT/s         | 19        | 0.31%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s   | 18        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 3047      | 61.61%  |
| DDR3    | 1160      | 23.45%  |
| LPDDR4  | 195       | 3.94%   |
| LPDDR3  | 150       | 3.03%   |
| DDR5    | 113       | 2.28%   |
| LPDDR5  | 71        | 1.44%   |
| Unknown | 68        | 1.37%   |
| SDRAM   | 64        | 1.29%   |
| DDR2    | 60        | 1.21%   |
| DDR     | 15        | 0.3%    |
| DRAM    | 3         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2589      | 52.35%  |
| DIMM         | 1875      | 37.91%  |
| Row Of Chips | 427       | 8.63%   |
| Chip         | 37        | 0.75%   |
| Unknown      | 15        | 0.3%    |
| RIMM         | 2         | 0.04%   |
| FB-DIMM      | 1         | 0.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 2484      | 46.33%  |
| 4096  | 1164      | 21.71%  |
| 16384 | 1029      | 19.19%  |
| 2048  | 351       | 6.55%   |
| 32768 | 268       | 5%      |
| 1024  | 58        | 1.08%   |
| 512   | 6         | 0.11%   |
| 65536 | 2         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 966       | 17.83%  |
| 2667    | 863       | 15.93%  |
| 1600    | 755       | 13.94%  |
| 2400    | 446       | 8.23%   |
| 3600    | 288       | 5.32%   |
| 2133    | 276       | 5.1%    |
| 1333    | 213       | 3.93%   |
| 1867    | 131       | 2.42%   |
| 1334    | 102       | 1.88%   |
| 4267    | 101       | 1.86%   |
| 3266    | 86        | 1.59%   |
| 4800    | 81        | 1.5%    |
| 6400    | 79        | 1.46%   |
| 3400    | 75        | 1.38%   |
| 3733    | 63        | 1.16%   |
| 3000    | 61        | 1.13%   |
| 3533    | 57        | 1.05%   |
| 2933    | 54        | 1%      |
| 3800    | 51        | 0.94%   |
| 667     | 49        | 0.9%    |
| 1866    | 41        | 0.76%   |
| 1067    | 38        | 0.7%    |
| Unknown | 35        | 0.65%   |
| 2800    | 32        | 0.59%   |
| 2666    | 32        | 0.59%   |
| 4266    | 31        | 0.57%   |
| 3866    | 31        | 0.57%   |
| 1066    | 31        | 0.57%   |
| 3666    | 29        | 0.54%   |
| 800     | 28        | 0.52%   |
| 3466    | 27        | 0.5%    |
| 1800    | 25        | 0.46%   |
| 4199    | 19        | 0.35%   |
| 8400    | 18        | 0.33%   |
| 3333    | 16        | 0.3%    |
| 400     | 12        | 0.22%   |
| 4000    | 11        | 0.2%    |
| 2048    | 10        | 0.18%   |
| 6000    | 9         | 0.17%   |
| 3066    | 9         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 37        | 37.37%  |
| Brother Industries       | 17        | 17.17%  |
| Samsung Electronics      | 13        | 13.13%  |
| Canon                    | 13        | 13.13%  |
| Seiko Epson              | 4         | 4.04%   |
| Prolific Technology      | 4         | 4.04%   |
| Dymo-CoStar              | 3         | 3.03%   |
| Zebra                    | 1         | 1.01%   |
| STMicroelectronics       | 1         | 1.01%   |
| Ricoh                    | 1         | 1.01%   |
| QinHeng Electronics      | 1         | 1.01%   |
| Philips (or NXP)         | 1         | 1.01%   |
| Magic Control Technology | 1         | 1.01%   |
| Fuji Xerox               | 1         | 1.01%   |
| Dell                     | 1         | 1.01%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                             | 4         | 4.04%   |
| Samsung M2070 Series                                      | 3         | 3.03%   |
| HP DeskJet 2130 series                                    | 3         | 3.03%   |
| Samsung SCX-4100 Scanner                                  | 2         | 2.02%   |
| HP Officejet Pro 8100                                     | 2         | 2.02%   |
| HP LaserJet P2015 series                                  | 2         | 2.02%   |
| HP LaserJet 1022                                          | 2         | 2.02%   |
| HP LaserJet 1018                                          | 2         | 2.02%   |
| HP LaserJet 1012                                          | 2         | 2.02%   |
| HP DeskJet F4200 series                                   | 2         | 2.02%   |
| HP DeskJet 840c                                           | 2         | 2.02%   |
| HP Deskjet 3050 J610 series                               | 2         | 2.02%   |
| HP DeskJet 2600 series                                    | 2         | 2.02%   |
| Dymo-CoStar LabelWriter 450                               | 2         | 2.02%   |
| Brother Printer                                           | 2         | 2.02%   |
| Brother HL-L2320D series                                  | 2         | 2.02%   |
| Brother HL-5370DW series                                  | 2         | 2.02%   |
| Brother DCP-1510                                          | 2         | 2.02%   |
| Zebra LP2844 Printer                                      | 1         | 1.01%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.01%   |
| Seiko Epson XP-7100 Series                                | 1         | 1.01%   |
| Seiko Epson WF-2530 Series                                | 1         | 1.01%   |
| Seiko Epson Printer                                       | 1         | 1.01%   |
| Seiko Epson L3110 Series                                  | 1         | 1.01%   |
| Samsung SCX-4200 series                                   | 1         | 1.01%   |
| Samsung SCX-3200 Series                                   | 1         | 1.01%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 1.01%   |
| Samsung ML-1610 Mono Laser Printer                        | 1         | 1.01%   |
| Samsung M267x 287x Series                                 | 1         | 1.01%   |
| Samsung M2020 Series                                      | 1         | 1.01%   |
| Samsung CLP-325 Color Laser Printer                       | 1         | 1.01%   |
| Samsung C1860 Series                                      | 1         | 1.01%   |
| Ricoh SP 150SU                                            | 1         | 1.01%   |
| QinHeng CH340S                                            | 1         | 1.01%   |
| Philips (or NXP) USB Printer                              | 1         | 1.01%   |
| Magic Control BAY-3U1S1P Parallel Port                    | 1         | 1.01%   |
| HP PSC-1315/PSC-1317                                      | 1         | 1.01%   |
| HP OfficeJet 5600 (USBHUB)                                | 1         | 1.01%   |
| HP Officejet 4500 G510g-m                                 | 1         | 1.01%   |
| HP LaserJet P1102                                         | 1         | 1.01%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 10        | 55.56%  |
| Seiko Epson    | 6         | 33.33%  |
| Mustek Systems | 2         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]                 | 2         | 11.11%  |
| Canon CanoScan N650U/N656U                                  | 2         | 11.11%  |
| Canon CanoScan LiDE 200                                     | 2         | 11.11%  |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]            | 1         | 5.56%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]     | 1         | 5.56%   |
| Seiko Epson GT-F700 [Perfection V350]                       | 1         | 5.56%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1         | 5.56%   |
| Mustek Systems ScanExpress 1200 UB                          | 1         | 5.56%   |
| Mustek Systems BearPaw 1200 CU Plus                         | 1         | 5.56%   |
| Canon CanoScan LiDE 60                                      | 1         | 5.56%   |
| Canon CanoScan LIDE 25                                      | 1         | 5.56%   |
| Canon CanoScan LiDE 220                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 210                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 120                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 110                                     | 1         | 5.56%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 864       | 19.83%  |
| IMC Networks                           | 477       | 10.95%  |
| Logitech                               | 385       | 8.84%   |
| Microdia                               | 364       | 8.35%   |
| Bison Electronics                      | 321       | 7.37%   |
| Realtek Semiconductor                  | 282       | 6.47%   |
| Quanta                                 | 235       | 5.39%   |
| Sunplus Innovation Technology          | 190       | 4.36%   |
| Cheng Uei Precision Industry (Foxlink) | 138       | 3.17%   |
| Syntek                                 | 115       | 2.64%   |
| Lite-On Technology                     | 105       | 2.41%   |
| Apple                                  | 89        | 2.04%   |
| Luxvisions Innotech Limited            | 78        | 1.79%   |
| Acer                                   | 66        | 1.51%   |
| Suyin                                  | 64        | 1.47%   |
| Microsoft                              | 59        | 1.35%   |
| Samsung Electronics                    | 46        | 1.06%   |
| Alcor Micro                            | 43        | 0.99%   |
| Silicon Motion                         | 42        | 0.96%   |
| Sonix Technology                       | 31        | 0.71%   |
| Lenovo                                 | 30        | 0.69%   |
| Z-Star Microelectronics                | 23        | 0.53%   |
| SunplusIT                              | 19        | 0.44%   |
| MacroSilicon                           | 19        | 0.44%   |
| Valve Software                         | 18        | 0.41%   |
| ARC International                      | 15        | 0.34%   |
| Razer USA                              | 13        | 0.3%    |
| Importek                               | 13        | 0.3%    |
| Ricoh                                  | 11        | 0.25%   |
| KYE Systems (Mouse Systems)            | 11        | 0.25%   |
| ALi                                    | 11        | 0.25%   |
| Primax Electronics                     | 10        | 0.23%   |
| Creative Technology                    | 10        | 0.23%   |
| Shenzhen Kingcome Optoelectronic       | 9         | 0.21%   |
| Generalplus Technology                 | 9         | 0.21%   |
| LG Electronics                         | 8         | 0.18%   |
| Jieli Technology                       | 8         | 0.18%   |
| Google                                 | 6         | 0.14%   |
| Unknown                                | 5         | 0.11%   |
| Trust                                  | 5         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 247       | 5.61%   |
| Microdia Integrated_Webcam_HD                                              | 181       | 4.11%   |
| IMC Networks Integrated Camera                                             | 160       | 3.63%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 144       | 3.27%   |
| Bison Integrated Camera                                                    | 115       | 2.61%   |
| Realtek Integrated_Webcam_HD                                               | 108       | 2.45%   |
| Logitech HD Pro Webcam C920                                                | 97        | 2.2%    |
| Chicony HD WebCam                                                          | 82        | 1.86%   |
| Syntek Integrated Camera                                                   | 78        | 1.77%   |
| Sunplus Integrated_Webcam_HD                                               | 74        | 1.68%   |
| Logitech Webcam C270                                                       | 60        | 1.36%   |
| Quanta HD User Facing                                                      | 52        | 1.18%   |
| Lite-On Integrated Camera                                                  | 51        | 1.16%   |
| Bison HD Webcam                                                            | 49        | 1.11%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 46        | 1.04%   |
| Bison SunplusIT Integrated Camera                                          | 46        | 1.04%   |
| Chicony USB2.0 Camera                                                      | 37        | 0.84%   |
| Chicony Integrated Camera (1280x720@30)                                    | 36        | 0.82%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 35        | 0.79%   |
| Chicony HP HD Camera                                                       | 35        | 0.79%   |
| Chicony HD User Facing                                                     | 35        | 0.79%   |
| Apple FaceTime HD Camera (Built-in)                                        | 35        | 0.79%   |
| Chicony HP Wide Vision HD Camera                                           | 34        | 0.77%   |
| Logitech C922 Pro Stream Webcam                                            | 32        | 0.73%   |
| Microdia Integrated Webcam                                                 | 31        | 0.7%    |
| Quanta HP Wide Vision HD Camera                                            | 28        | 0.64%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 28        | 0.64%   |
| Sunplus HD WebCam                                                          | 26        | 0.59%   |
| Realtek USB Camera                                                         | 26        | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 26        | 0.59%   |
| IMC Networks HD Camera                                                     | 25        | 0.57%   |
| Microdia Webcam Vitade AF                                                  | 24        | 0.54%   |
| Chicony Integrated IR Camera                                               | 24        | 0.54%   |
| Chicony HP Truevision HD                                                   | 24        | 0.54%   |
| Realtek Integrated Webcam                                                  | 23        | 0.52%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 23        | 0.52%   |
| Logitech BRIO Ultra HD Webcam                                              | 23        | 0.52%   |
| Chicony USB2.0 HD UVC WebCam                                               | 23        | 0.52%   |
| Chicony EasyCamera                                                         | 23        | 0.52%   |
| Quanta VGA WebCam                                                          | 22        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 355       | 37.85%  |
| Validity Sensors                   | 238       | 25.37%  |
| Shenzhen Goodix Technology         | 176       | 18.76%  |
| Elan Microelectronics              | 58        | 6.18%   |
| LighTuning Technology              | 32        | 3.41%   |
| Upek                               | 29        | 3.09%   |
| AuthenTec                          | 21        | 2.24%   |
| STMicroelectronics                 | 10        | 1.07%   |
| Samsung Electronics                | 6         | 0.64%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 0.43%   |
| Microsoft                          | 4         | 0.43%   |
| HOLTEK                             | 3         | 0.32%   |
| Focal-systems.Corp                 | 1         | 0.11%   |
| DigitalPersona                     | 1         | 0.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 125       | 13.33%  |
| Shenzhen Goodix  Fingerprint Device                                        | 92        | 9.81%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 55        | 5.86%   |
| Shenzhen Goodix Fingerprint Reader                                         | 49        | 5.22%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 43        | 4.58%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 37        | 3.94%   |
| Shenzhen Goodix FingerPrint                                                | 35        | 3.73%   |
| Validity Sensors Synaptics WBDI                                            | 33        | 3.52%   |
| Synaptics UWP WBDI                                                         | 32        | 3.41%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 27        | 2.88%   |
| Elan ELAN:Fingerprint                                                      | 27        | 2.88%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 24        | 2.56%   |
| Synaptics  WBDI                                                            | 22        | 2.35%   |
| Elan ELAN:ARM-M4                                                           | 22        | 2.35%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 20        | 2.13%   |
| Synaptics WBDI                                                             | 20        | 2.13%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 20        | 2.13%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 18        | 1.92%   |
| Synaptics Fingerprint reader [HP G6]                                       | 18        | 1.92%   |
| Synaptics UWP WBDI Device                                                  | 15        | 1.6%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 15        | 1.6%    |
| Validity Sensors VFS491                                                    | 13        | 1.39%   |
| Validity Sensors Fingerprint scanner                                       | 13        | 1.39%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 13        | 1.39%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 12        | 1.28%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 12        | 1.28%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 11        | 1.17%   |
| AuthenTec AES2810                                                          | 11        | 1.17%   |
| STMicroelectronics Fingerprint Reader                                      | 10        | 1.07%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 9         | 0.96%   |
| Elan WBF Fingerprint Sensor                                                | 7         | 0.75%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 0.64%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 0.64%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 5         | 0.53%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.43%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.43%   |
| Synaptics WBDI Device                                                      | 4         | 0.43%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 0.43%   |
| Microsoft Fingerprint Reader                                               | 4         | 0.43%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 141       | 39.83%  |
| Broadcom                          | 117       | 33.05%  |
| Upek                              | 24        | 6.78%   |
| Lenovo                            | 13        | 3.67%   |
| O2 Micro                          | 9         | 2.54%   |
| Clay Logic                        | 8         | 2.26%   |
| Gemalto (was Gemplus)             | 7         | 1.98%   |
| Yubico.com                        | 6         | 1.69%   |
| Advanced Card Systems             | 6         | 1.69%   |
| SCM Microsystems                  | 5         | 1.41%   |
| Reiner SCT Kartensysteme          | 4         | 1.13%   |
| Aladdin Knowledge Systems         | 3         | 0.85%   |
| OmniKey                           | 2         | 0.56%   |
| Aktiv                             | 2         | 0.56%   |
| VASCO Data Security International | 1         | 0.28%   |
| Realtek Semiconductor             | 1         | 0.28%   |
| Hewlett-Packard                   | 1         | 0.28%   |
| Fujitsu Siemens Computers         | 1         | 0.28%   |
| Chicony Electronics               | 1         | 0.28%   |
| C3PO                              | 1         | 0.28%   |
| Aladdin R.D.                      | 1         | 0.28%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 139       | 39.27%  |
| Broadcom 5880                                                                | 33        | 9.32%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 30        | 8.47%   |
| Broadcom BCM5880 Secure Applications Processor                               | 26        | 7.34%   |
| Broadcom 58200                                                               | 26        | 7.34%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 24        | 6.78%   |
| Lenovo Integrated Smart Card Reader                                          | 13        | 3.67%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 2.26%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 6         | 1.69%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 3         | 0.85%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 0.85%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.85%   |
| Clay Logic Nitrokey Pro                                                      | 3         | 0.85%   |
| Aladdin Knowledge Systems Token JC                                           | 3         | 0.85%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 3         | 0.85%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 2         | 0.56%   |
| Clay Logic Nitrokey Start                                                    | 2         | 0.56%   |
| Clay Logic CanoKey Pigeon                                                    | 2         | 0.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.56%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.56%   |
| Aktiv Rutoken lite                                                           | 2         | 0.56%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.28%   |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 0.28%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.28%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.28%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.28%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.28%   |
| OmniKey Smart Card Reader USB                                                | 1         | 0.28%   |
| OmniKey 5022 Smart Card Reader                                               | 1         | 0.28%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.28%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.28%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.28%   |
| Fujitsu Siemens Computers Keyboard KB100 SCR eSIG                            | 1         | 0.28%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 0.28%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.28%   |
| C3PO LTC31v2                                                                 | 1         | 0.28%   |
| Aladdin R.D. JaCarta                                                         | 1         | 0.28%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.28%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.28%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.28%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4813      | 69.58%  |
| 1     | 1685      | 24.36%  |
| 2     | 334       | 4.83%   |
| 3     | 70        | 1.01%   |
| 4     | 11        | 0.16%   |
| 6     | 2         | 0.03%   |
| 7     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 914       | 36.16%  |
| Graphics card            | 474       | 18.75%  |
| Chipcard                 | 299       | 11.83%  |
| Net/wireless             | 217       | 8.58%   |
| Multimedia controller    | 183       | 7.24%   |
| Camera                   | 132       | 5.22%   |
| Unassigned class         | 58        | 2.29%   |
| Bluetooth                | 51        | 2.02%   |
| Communication controller | 49        | 1.94%   |
| Sound                    | 38        | 1.5%    |
| Net/ethernet             | 26        | 1.03%   |
| Network                  | 24        | 0.95%   |
| Storage                  | 18        | 0.71%   |
| Card reader              | 14        | 0.55%   |
| Modem                    | 11        | 0.44%   |
| Dvb card                 | 8         | 0.32%   |
| Wireless                 | 2         | 0.08%   |
| Storage/raid             | 2         | 0.08%   |
| Storage/nvme             | 2         | 0.08%   |
| Storage/ide              | 2         | 0.08%   |
| Tv card                  | 1         | 0.04%   |
| Storage/ata              | 1         | 0.04%   |
| Flash memory             | 1         | 0.04%   |
| Firewire controller      | 1         | 0.04%   |

