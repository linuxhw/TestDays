Linux in Slovenia - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Slovenia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Slovenia/Desktop/README.md) and [notebooks](/Location/Slovenia/Notebook/README.md).

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

Total: 401

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [f4c9e8f3f2](https://linux-hardware.org/?probe=f4c9e8f3f2) | May 30, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [14ebca03fe](https://linux-hardware.org/?probe=14ebca03fe) | May 30, 2022 |
| Toshiba       | Satellite Pro U400          | Notebook    | [4aeeca648d](https://linux-hardware.org/?probe=4aeeca648d) | May 24, 2022 |
| Intel         | CM-iAM/SBC-FITPC2i          | Desktop     | [cbfe433386](https://linux-hardware.org/?probe=cbfe433386) | May 20, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [ecfb1c48d9](https://linux-hardware.org/?probe=ecfb1c48d9) | May 17, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [ddadf86375](https://linux-hardware.org/?probe=ddadf86375) | May 15, 2022 |
| ASUSTek       | N71Vg                       | Notebook    | [33a6047c0b](https://linux-hardware.org/?probe=33a6047c0b) | May 14, 2022 |
| ASUSTek       | N71Vg                       | Notebook    | [86d9e911f1](https://linux-hardware.org/?probe=86d9e911f1) | May 13, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [86d60d0227](https://linux-hardware.org/?probe=86d60d0227) | May 12, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [b420f9214c](https://linux-hardware.org/?probe=b420f9214c) | May 06, 2022 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [934d403a31](https://linux-hardware.org/?probe=934d403a31) | May 04, 2022 |
| HP            | Laptop 17-ca3xxx            | Notebook    | [373f22a70f](https://linux-hardware.org/?probe=373f22a70f) | May 03, 2022 |
| HP            | Laptop 17-ca3xxx            | Notebook    | [91a367d874](https://linux-hardware.org/?probe=91a367d874) | May 03, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [ce528c379a](https://linux-hardware.org/?probe=ce528c379a) | May 01, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [95ec2ff7d2](https://linux-hardware.org/?probe=95ec2ff7d2) | Apr 30, 2022 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [5d0f1a15e1](https://linux-hardware.org/?probe=5d0f1a15e1) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [965985d6f4](https://linux-hardware.org/?probe=965985d6f4) | Apr 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [57271a5f8b](https://linux-hardware.org/?probe=57271a5f8b) | Apr 28, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [81409450dc](https://linux-hardware.org/?probe=81409450dc) | Apr 28, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [f727388ac8](https://linux-hardware.org/?probe=f727388ac8) | Apr 17, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [c1102c77ec](https://linux-hardware.org/?probe=c1102c77ec) | Apr 17, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [d7b7a81cbb](https://linux-hardware.org/?probe=d7b7a81cbb) | Apr 16, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [7e7136d915](https://linux-hardware.org/?probe=7e7136d915) | Apr 16, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | Desktop     | [76a5225b83](https://linux-hardware.org/?probe=76a5225b83) | Apr 16, 2022 |
| ASRock        | H170M Pro4                  | Desktop     | [0dd1b326c0](https://linux-hardware.org/?probe=0dd1b326c0) | Apr 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [8570b5ab84](https://linux-hardware.org/?probe=8570b5ab84) | Apr 12, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [222189213d](https://linux-hardware.org/?probe=222189213d) | Apr 11, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
| Lenovo        | ThinkPad R61 8933W4F        | Notebook    | [4864fcdfa0](https://linux-hardware.org/?probe=4864fcdfa0) | Apr 07, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [0813d4bc9e](https://linux-hardware.org/?probe=0813d4bc9e) | Mar 31, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [defac75126](https://linux-hardware.org/?probe=defac75126) | Mar 31, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [d13496f68a](https://linux-hardware.org/?probe=d13496f68a) | Mar 31, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [da62c7238d](https://linux-hardware.org/?probe=da62c7238d) | Mar 28, 2022 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [1260b540e7](https://linux-hardware.org/?probe=1260b540e7) | Mar 27, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1eebe899b0](https://linux-hardware.org/?probe=1eebe899b0) | Mar 27, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [f0efa22aa2](https://linux-hardware.org/?probe=f0efa22aa2) | Mar 27, 2022 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [0bf3028253](https://linux-hardware.org/?probe=0bf3028253) | Mar 27, 2022 |
| Dell          | Precision 5540              | Notebook    | [38d9bed727](https://linux-hardware.org/?probe=38d9bed727) | Mar 21, 2022 |
| Fujitsu       | LIFEBOOK S792               | Notebook    | [55da3ab4e0](https://linux-hardware.org/?probe=55da3ab4e0) | Mar 09, 2022 |
| Supermicro    | X11SCAA                     | Server      | [b850cd60f6](https://linux-hardware.org/?probe=b850cd60f6) | Mar 08, 2022 |
| HP            | Compaq nw8440 (RH415EA#A... | Notebook    | [55a6d982b3](https://linux-hardware.org/?probe=55a6d982b3) | Mar 07, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [d9773ef48d](https://linux-hardware.org/?probe=d9773ef48d) | Mar 06, 2022 |
| HP            | kip                         | Notebook    | [4d6e1264c7](https://linux-hardware.org/?probe=4d6e1264c7) | Mar 02, 2022 |
| HP            | kip                         | Notebook    | [a6ab5d4d8a](https://linux-hardware.org/?probe=a6ab5d4d8a) | Mar 01, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [d5c0be1b13](https://linux-hardware.org/?probe=d5c0be1b13) | Feb 27, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9d5d5c0ffb](https://linux-hardware.org/?probe=9d5d5c0ffb) | Feb 26, 2022 |
| HP            | Pavilion dv7                | Notebook    | [46280b758c](https://linux-hardware.org/?probe=46280b758c) | Feb 25, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [1c8a37fb2f](https://linux-hardware.org/?probe=1c8a37fb2f) | Feb 24, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [ec93ded12b](https://linux-hardware.org/?probe=ec93ded12b) | Feb 23, 2022 |
| Dell          | 09M8Y8 A02                  | Desktop     | [202fc1f0b9](https://linux-hardware.org/?probe=202fc1f0b9) | Feb 22, 2022 |
| HP            | Pavilion dv7                | Notebook    | [fd1bbe1769](https://linux-hardware.org/?probe=fd1bbe1769) | Feb 21, 2022 |
| HP            | Pavilion dv7                | Notebook    | [da9449422c](https://linux-hardware.org/?probe=da9449422c) | Feb 21, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [0ee9dcd568](https://linux-hardware.org/?probe=0ee9dcd568) | Feb 20, 2022 |
| HP            | ProBook 4730s               | Notebook    | [5ffa4bce13](https://linux-hardware.org/?probe=5ffa4bce13) | Feb 19, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [5ee5668ab1](https://linux-hardware.org/?probe=5ee5668ab1) | Feb 19, 2022 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [5323885713](https://linux-hardware.org/?probe=5323885713) | Feb 17, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [cad9a70c49](https://linux-hardware.org/?probe=cad9a70c49) | Feb 16, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [676d121bda](https://linux-hardware.org/?probe=676d121bda) | Feb 13, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [df5a829402](https://linux-hardware.org/?probe=df5a829402) | Feb 09, 2022 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [239eb94a17](https://linux-hardware.org/?probe=239eb94a17) | Feb 07, 2022 |
| Acer          | Predator PH317-52           | Notebook    | [ec43c5baa2](https://linux-hardware.org/?probe=ec43c5baa2) | Feb 07, 2022 |
| ASUSTek       | X750LN                      | Notebook    | [94a70cdd5d](https://linux-hardware.org/?probe=94a70cdd5d) | Feb 02, 2022 |
| Dell          | Inspiron 5748               | Notebook    | [07c8076d3e](https://linux-hardware.org/?probe=07c8076d3e) | Feb 01, 2022 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [901d568e70](https://linux-hardware.org/?probe=901d568e70) | Jan 31, 2022 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [621d099786](https://linux-hardware.org/?probe=621d099786) | Jan 31, 2022 |
| HP            | 1589                        | Desktop     | [41dbcb78cb](https://linux-hardware.org/?probe=41dbcb78cb) | Jan 30, 2022 |
| Pegatron      | EVE                         | Desktop     | [06d22ac6e2](https://linux-hardware.org/?probe=06d22ac6e2) | Jan 21, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [81e03a6b48](https://linux-hardware.org/?probe=81e03a6b48) | Jan 21, 2022 |
| Pegatron      | EVE                         | Desktop     | [5640f6122a](https://linux-hardware.org/?probe=5640f6122a) | Jan 21, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [faba7de732](https://linux-hardware.org/?probe=faba7de732) | Jan 17, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [f2bae7651d](https://linux-hardware.org/?probe=f2bae7651d) | Jan 16, 2022 |
| ASRock        | B85M-HDS                    | Desktop     | [77cb3218a8](https://linux-hardware.org/?probe=77cb3218a8) | Jan 12, 2022 |
| Dell          | Inspiron 7706 2n1           | Convertible | [b9b69a73a3](https://linux-hardware.org/?probe=b9b69a73a3) | Jan 09, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [22e51b8b41](https://linux-hardware.org/?probe=22e51b8b41) | Jan 06, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [52db8d0bbf](https://linux-hardware.org/?probe=52db8d0bbf) | Jan 06, 2022 |
| Lenovo        | ThinkPad T590 20N5S0MR00    | Notebook    | [29040ecce5](https://linux-hardware.org/?probe=29040ecce5) | Jan 01, 2022 |
| MSI           | U210                        | Notebook    | [24eb05a4d9](https://linux-hardware.org/?probe=24eb05a4d9) | Dec 29, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [be79b3cd82](https://linux-hardware.org/?probe=be79b3cd82) | Dec 26, 2021 |
| Lenovo        | ThinkCentre M57e 9439WHV    | Desktop     | [a9b2163945](https://linux-hardware.org/?probe=a9b2163945) | Dec 25, 2021 |
| Intel         | NUC5i7RYB H73774-101        | Mini pc     | [97ec4e3d99](https://linux-hardware.org/?probe=97ec4e3d99) | Dec 25, 2021 |
| Gigabyte      | H57M-USB3                   | Desktop     | [ee70d6b4b4](https://linux-hardware.org/?probe=ee70d6b4b4) | Dec 24, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [8887022aa7](https://linux-hardware.org/?probe=8887022aa7) | Dec 23, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6b40a0f2c5](https://linux-hardware.org/?probe=6b40a0f2c5) | Dec 21, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [31c2b40e84](https://linux-hardware.org/?probe=31c2b40e84) | Dec 21, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [6238c622ad](https://linux-hardware.org/?probe=6238c622ad) | Dec 18, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [6aee0ff442](https://linux-hardware.org/?probe=6aee0ff442) | Dec 15, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [45ac665485](https://linux-hardware.org/?probe=45ac665485) | Dec 10, 2021 |
| Dell          | Inspiron 5748               | Notebook    | [77f278682e](https://linux-hardware.org/?probe=77f278682e) | Dec 06, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [6649bea1f8](https://linux-hardware.org/?probe=6649bea1f8) | Dec 04, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [723e2a158a](https://linux-hardware.org/?probe=723e2a158a) | Dec 03, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [6d9c31a411](https://linux-hardware.org/?probe=6d9c31a411) | Nov 28, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [e005ddb405](https://linux-hardware.org/?probe=e005ddb405) | Nov 28, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [0a4f8ff5f1](https://linux-hardware.org/?probe=0a4f8ff5f1) | Nov 28, 2021 |
| HP            | EliteBook 8760w             | Notebook    | [febc9d2faa](https://linux-hardware.org/?probe=febc9d2faa) | Nov 28, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [df3010e1b8](https://linux-hardware.org/?probe=df3010e1b8) | Nov 27, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [6016236fad](https://linux-hardware.org/?probe=6016236fad) | Nov 24, 2021 |
| Gigabyte      | H57M-USB3                   | Desktop     | [97409a8d1c](https://linux-hardware.org/?probe=97409a8d1c) | Nov 22, 2021 |
| Gigabyte      | H57M-USB3                   | Desktop     | [e0e4ee802a](https://linux-hardware.org/?probe=e0e4ee802a) | Nov 22, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [e898d8c017](https://linux-hardware.org/?probe=e898d8c017) | Nov 20, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [e37febb0b3](https://linux-hardware.org/?probe=e37febb0b3) | Nov 18, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [163092e4b9](https://linux-hardware.org/?probe=163092e4b9) | Nov 18, 2021 |
| HP            | 250 G3                      | Notebook    | [8d370cbb27](https://linux-hardware.org/?probe=8d370cbb27) | Nov 16, 2021 |
| HP            | 250 G3                      | Notebook    | [fb9fe2f3fb](https://linux-hardware.org/?probe=fb9fe2f3fb) | Nov 16, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [c4e6de1315](https://linux-hardware.org/?probe=c4e6de1315) | Nov 15, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [0f6c2b21cf](https://linux-hardware.org/?probe=0f6c2b21cf) | Nov 14, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [01c20231f2](https://linux-hardware.org/?probe=01c20231f2) | Nov 13, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [dfe40a023a](https://linux-hardware.org/?probe=dfe40a023a) | Nov 12, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [1336c9e31c](https://linux-hardware.org/?probe=1336c9e31c) | Nov 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [5a2fa34576](https://linux-hardware.org/?probe=5a2fa34576) | Nov 10, 2021 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | Desktop     | [ab14080e40](https://linux-hardware.org/?probe=ab14080e40) | Nov 09, 2021 |
| HP            | Pavilion dv7                | Notebook    | [3c3e5bc872](https://linux-hardware.org/?probe=3c3e5bc872) | Nov 08, 2021 |
| HP            | EliteBook 8760w             | Notebook    | [99fb47dc2b](https://linux-hardware.org/?probe=99fb47dc2b) | Oct 28, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [4e5da9e4d3](https://linux-hardware.org/?probe=4e5da9e4d3) | Oct 24, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [f66ba65dc8](https://linux-hardware.org/?probe=f66ba65dc8) | Oct 22, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [1d50915627](https://linux-hardware.org/?probe=1d50915627) | Oct 21, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [a11d4b7c50](https://linux-hardware.org/?probe=a11d4b7c50) | Oct 20, 2021 |
| Lenovo        | ThinkPad 10 20C10025SC      | Tablet      | [7d6ab19f8d](https://linux-hardware.org/?probe=7d6ab19f8d) | Oct 20, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [f18e793687](https://linux-hardware.org/?probe=f18e793687) | Oct 17, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [065ee91163](https://linux-hardware.org/?probe=065ee91163) | Oct 17, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [2cbf85194c](https://linux-hardware.org/?probe=2cbf85194c) | Oct 14, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [cd738f5036](https://linux-hardware.org/?probe=cd738f5036) | Oct 11, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [bc1fd03a63](https://linux-hardware.org/?probe=bc1fd03a63) | Oct 10, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [6ec6ce5c81](https://linux-hardware.org/?probe=6ec6ce5c81) | Oct 10, 2021 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [f424437bd1](https://linux-hardware.org/?probe=f424437bd1) | Oct 01, 2021 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [c85622ebee](https://linux-hardware.org/?probe=c85622ebee) | Sep 29, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [9813ead17b](https://linux-hardware.org/?probe=9813ead17b) | Sep 23, 2021 |
| Medion        | Akoya E7226                 | Desktop     | [9367472acb](https://linux-hardware.org/?probe=9367472acb) | Sep 18, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [284c0763b3](https://linux-hardware.org/?probe=284c0763b3) | Sep 09, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [934d0576e0](https://linux-hardware.org/?probe=934d0576e0) | Aug 27, 2021 |
| Lenovo        | ThinkPad T460s 20FAS7XT0... | Notebook    | [b2de2ea1ab](https://linux-hardware.org/?probe=b2de2ea1ab) | Aug 22, 2021 |
| Lenovo        | ThinkPad T460s 20FAS7XT0... | Notebook    | [9da6a33d24](https://linux-hardware.org/?probe=9da6a33d24) | Aug 22, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | Notebook    | [8c7e729202](https://linux-hardware.org/?probe=8c7e729202) | Aug 19, 2021 |
| ASRock        | H310CM-HDV                  | Desktop     | [0fccd48745](https://linux-hardware.org/?probe=0fccd48745) | Aug 13, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [8cc7d05010](https://linux-hardware.org/?probe=8cc7d05010) | Aug 12, 2021 |
| HP            | 2000                        | Notebook    | [2909375db3](https://linux-hardware.org/?probe=2909375db3) | Aug 06, 2021 |
| HP            | 2000                        | Notebook    | [df5d5e05c6](https://linux-hardware.org/?probe=df5d5e05c6) | Aug 06, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [5b89a99ad8](https://linux-hardware.org/?probe=5b89a99ad8) | Jul 31, 2021 |
| HP            | 2000                        | Notebook    | [9fbfcf95d2](https://linux-hardware.org/?probe=9fbfcf95d2) | Jul 29, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [53d3003d94](https://linux-hardware.org/?probe=53d3003d94) | Jul 25, 2021 |
| HP            | 2000                        | Notebook    | [13aaafccdb](https://linux-hardware.org/?probe=13aaafccdb) | Jul 22, 2021 |
| HP            | 2000                        | Notebook    | [f3c7f85988](https://linux-hardware.org/?probe=f3c7f85988) | Jul 21, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e6e223209a](https://linux-hardware.org/?probe=e6e223209a) | Jul 20, 2021 |
| MSI           | H61M-P31                    | Desktop     | [ccd9d80d59](https://linux-hardware.org/?probe=ccd9d80d59) | Jul 18, 2021 |
| Pegatron      | 2A73                        | Desktop     | [2bff425af7](https://linux-hardware.org/?probe=2bff425af7) | Jul 14, 2021 |
| Pegatron      | 2A73                        | Desktop     | [44ea7169ef](https://linux-hardware.org/?probe=44ea7169ef) | Jul 14, 2021 |
| HP            | 2000                        | Notebook    | [e6019f1bd3](https://linux-hardware.org/?probe=e6019f1bd3) | Jul 12, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [bc18a23953](https://linux-hardware.org/?probe=bc18a23953) | Jun 28, 2021 |
| HP            | 2000                        | Notebook    | [6a169f2d87](https://linux-hardware.org/?probe=6a169f2d87) | Jun 22, 2021 |
| HP            | 2000                        | Notebook    | [b2e5075aaf](https://linux-hardware.org/?probe=b2e5075aaf) | Jun 17, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [330d2214c6](https://linux-hardware.org/?probe=330d2214c6) | Jun 10, 2021 |
| HP            | 2000                        | Notebook    | [6a1c91ae8d](https://linux-hardware.org/?probe=6a1c91ae8d) | Jun 07, 2021 |
| Acer          | Nitro AN517-52              | Notebook    | [c79b400454](https://linux-hardware.org/?probe=c79b400454) | Jun 06, 2021 |
| Lenovo        | ThinkPad T61 8897CTO        | Notebook    | [6cfc0271ba](https://linux-hardware.org/?probe=6cfc0271ba) | Jun 03, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [181bd83bdd](https://linux-hardware.org/?probe=181bd83bdd) | Jun 02, 2021 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [02bf919368](https://linux-hardware.org/?probe=02bf919368) | Jun 02, 2021 |
| Acer          | Aspire Z5610                | All in one  | [b24fdb7446](https://linux-hardware.org/?probe=b24fdb7446) | May 28, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [92d97521bc](https://linux-hardware.org/?probe=92d97521bc) | May 21, 2021 |
| HP            | ProLiant DL380p Gen8        | Server      | [32951a000f](https://linux-hardware.org/?probe=32951a000f) | May 21, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [76598a468f](https://linux-hardware.org/?probe=76598a468f) | May 20, 2021 |
| HP            | 2000                        | Notebook    | [1469c94a5f](https://linux-hardware.org/?probe=1469c94a5f) | May 17, 2021 |
| HP            | ProLiant DL380p Gen8        | Server      | [a4b9bc232a](https://linux-hardware.org/?probe=a4b9bc232a) | May 15, 2021 |
| HP            | EliteBook 830 G6            | Notebook    | [8fcf99f057](https://linux-hardware.org/?probe=8fcf99f057) | May 12, 2021 |
| Lenovo        | ThinkStation S20 4157ZSK    | Desktop     | [3e6d98fe9c](https://linux-hardware.org/?probe=3e6d98fe9c) | Apr 27, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | Notebook    | [f67c550f8e](https://linux-hardware.org/?probe=f67c550f8e) | Apr 27, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | Notebook    | [0876a200b7](https://linux-hardware.org/?probe=0876a200b7) | Apr 27, 2021 |
| ASRock        | B560 Pro4                   | Desktop     | [ddd384c6cb](https://linux-hardware.org/?probe=ddd384c6cb) | Apr 26, 2021 |
| Lenovo        | ThinkCentre M55e 9389WEG    | Desktop     | [66c2003859](https://linux-hardware.org/?probe=66c2003859) | Apr 20, 2021 |
| HP            | 1905                        | Desktop     | [e0fc243f47](https://linux-hardware.org/?probe=e0fc243f47) | Apr 19, 2021 |
| Panasonic     | CF-53SWWZ5MG                | Notebook    | [c59fd76192](https://linux-hardware.org/?probe=c59fd76192) | Apr 14, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [d0a4124a2a](https://linux-hardware.org/?probe=d0a4124a2a) | Apr 10, 2021 |
| HP            | ProBook 4515s (VC377ES#A... | Notebook    | [2c84f60b0d](https://linux-hardware.org/?probe=2c84f60b0d) | Apr 09, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [132c1a0515](https://linux-hardware.org/?probe=132c1a0515) | Apr 08, 2021 |
| HP            | ProBook 4740s               | Notebook    | [cf941af09e](https://linux-hardware.org/?probe=cf941af09e) | Apr 08, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [10132d3ee3](https://linux-hardware.org/?probe=10132d3ee3) | Apr 05, 2021 |
| ASUSTek       | P5Q SE                      | Desktop     | [325f4ca461](https://linux-hardware.org/?probe=325f4ca461) | Apr 05, 2021 |
| ASUSTek       | P5Q SE                      | Desktop     | [1c3958d998](https://linux-hardware.org/?probe=1c3958d998) | Apr 05, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [62f6aa5c03](https://linux-hardware.org/?probe=62f6aa5c03) | Mar 27, 2021 |
| Lenovo        | ThinkStation S20 4157ZSK    | Desktop     | [1038d58fea](https://linux-hardware.org/?probe=1038d58fea) | Mar 25, 2021 |
| Dell          | Latitude 5501               | Notebook    | [474510883b](https://linux-hardware.org/?probe=474510883b) | Mar 22, 2021 |
| Lenovo        | ThinkStation S20 4157ZSK    | Desktop     | [8b28b318fd](https://linux-hardware.org/?probe=8b28b318fd) | Mar 19, 2021 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [453120855b](https://linux-hardware.org/?probe=453120855b) | Mar 18, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [49b951896d](https://linux-hardware.org/?probe=49b951896d) | Mar 17, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [2d9ae8527d](https://linux-hardware.org/?probe=2d9ae8527d) | Mar 11, 2021 |
| ASUSTek       | K52JT                       | Notebook    | [e434a21940](https://linux-hardware.org/?probe=e434a21940) | Mar 04, 2021 |
| Panasonic     | CF-53SWWZ5MG                | Notebook    | [6fdf12c20c](https://linux-hardware.org/?probe=6fdf12c20c) | Feb 28, 2021 |
| Apple         | Mac-F4208DA9 PVT            | Desktop     | [4ab255096c](https://linux-hardware.org/?probe=4ab255096c) | Feb 28, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [9dc547fceb](https://linux-hardware.org/?probe=9dc547fceb) | Feb 26, 2021 |
| Dell          | 0C27VV A02                  | Desktop     | [49cd056ca4](https://linux-hardware.org/?probe=49cd056ca4) | Feb 24, 2021 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [8e84f252bc](https://linux-hardware.org/?probe=8e84f252bc) | Feb 20, 2021 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [bd76fdbde8](https://linux-hardware.org/?probe=bd76fdbde8) | Feb 20, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [153bb12a6a](https://linux-hardware.org/?probe=153bb12a6a) | Feb 19, 2021 |
| MSI           | H61M-P31                    | Desktop     | [a0192f9d6e](https://linux-hardware.org/?probe=a0192f9d6e) | Feb 17, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [106c66da60](https://linux-hardware.org/?probe=106c66da60) | Feb 14, 2021 |
| Lenovo        | ThinkCentre M90p 5498PK8    | Desktop     | [df39a8847b](https://linux-hardware.org/?probe=df39a8847b) | Feb 14, 2021 |
| Lenovo        | ThinkPad L520 785958G       | Notebook    | [45025e2399](https://linux-hardware.org/?probe=45025e2399) | Feb 13, 2021 |
| Lenovo        | ThinkPad L520 785958G       | Notebook    | [be03f382e6](https://linux-hardware.org/?probe=be03f382e6) | Feb 09, 2021 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [e40fe3768d](https://linux-hardware.org/?probe=e40fe3768d) | Feb 09, 2021 |
| Panasonic     | CF-53SWWZ5MG                | Notebook    | [d1ade3e39d](https://linux-hardware.org/?probe=d1ade3e39d) | Feb 08, 2021 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [a31754db23](https://linux-hardware.org/?probe=a31754db23) | Feb 08, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [95958aa225](https://linux-hardware.org/?probe=95958aa225) | Feb 08, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [0e552a01e6](https://linux-hardware.org/?probe=0e552a01e6) | Feb 03, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [1f3dc6c825](https://linux-hardware.org/?probe=1f3dc6c825) | Feb 03, 2021 |
| ASUSTek       | X551CA                      | Notebook    | [1857586e3a](https://linux-hardware.org/?probe=1857586e3a) | Feb 03, 2021 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [7e828e295f](https://linux-hardware.org/?probe=7e828e295f) | Jan 20, 2021 |
| Pegatron      | 2A73                        | Desktop     | [4c2042c088](https://linux-hardware.org/?probe=4c2042c088) | Jan 18, 2021 |
| Pegatron      | 2A73                        | Desktop     | [c6cf8a7efe](https://linux-hardware.org/?probe=c6cf8a7efe) | Jan 18, 2021 |
| HP            | ZBook 15u G3                | Notebook    | [812e100310](https://linux-hardware.org/?probe=812e100310) | Jan 12, 2021 |
| HP            | ZBook 15u G3                | Notebook    | [30332e1d71](https://linux-hardware.org/?probe=30332e1d71) | Jan 12, 2021 |
| MSI           | H55M-P31                    | Desktop     | [3313a8aba5](https://linux-hardware.org/?probe=3313a8aba5) | Jan 12, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [0265add193](https://linux-hardware.org/?probe=0265add193) | Jan 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8b0a9a71b3](https://linux-hardware.org/?probe=8b0a9a71b3) | Jan 10, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [497bf4005e](https://linux-hardware.org/?probe=497bf4005e) | Jan 10, 2021 |
| HP            | Laptop 15-ra0xx             | Notebook    | [8227f44e5c](https://linux-hardware.org/?probe=8227f44e5c) | Jan 10, 2021 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [60d8b9344b](https://linux-hardware.org/?probe=60d8b9344b) | Jan 09, 2021 |
| HP            | ProBook 4730s               | Notebook    | [e7ab1bcd89](https://linux-hardware.org/?probe=e7ab1bcd89) | Jan 06, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [58204a920b](https://linux-hardware.org/?probe=58204a920b) | Jan 05, 2021 |
| HP            | EliteBook 6930p             | Notebook    | [e9c1683321](https://linux-hardware.org/?probe=e9c1683321) | Jan 04, 2021 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [b6c93666ee](https://linux-hardware.org/?probe=b6c93666ee) | Dec 29, 2020 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [7905034ba5](https://linux-hardware.org/?probe=7905034ba5) | Dec 29, 2020 |
| ASUSTek       | UX31E                       | Notebook    | [912f3fe702](https://linux-hardware.org/?probe=912f3fe702) | Dec 25, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [d759211bb6](https://linux-hardware.org/?probe=d759211bb6) | Dec 24, 2020 |
| Lenovo        | ThinkPad T420 4236A78       | Notebook    | [f98c371e7f](https://linux-hardware.org/?probe=f98c371e7f) | Dec 24, 2020 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [71370e1dd8](https://linux-hardware.org/?probe=71370e1dd8) | Dec 19, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [6c3965a41f](https://linux-hardware.org/?probe=6c3965a41f) | Dec 18, 2020 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [87bd14894c](https://linux-hardware.org/?probe=87bd14894c) | Dec 18, 2020 |
| ASUSTek       | G771JW                      | Notebook    | [b103133d69](https://linux-hardware.org/?probe=b103133d69) | Dec 16, 2020 |
| Gigabyte      | B450M GAMING                | Desktop     | [def1b6fff4](https://linux-hardware.org/?probe=def1b6fff4) | Dec 13, 2020 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [edd5100ec5](https://linux-hardware.org/?probe=edd5100ec5) | Dec 13, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [4260174285](https://linux-hardware.org/?probe=4260174285) | Dec 11, 2020 |
| Lenovo        | ThinkPad T500 2055WYX       | Notebook    | [6f04a45e2e](https://linux-hardware.org/?probe=6f04a45e2e) | Dec 11, 2020 |
| Lenovo        | 3135                        | Mini pc     | [b16b2d9bd5](https://linux-hardware.org/?probe=b16b2d9bd5) | Dec 11, 2020 |
| Lenovo        | ThinkPad T410 2522A92       | Notebook    | [dd93682c3c](https://linux-hardware.org/?probe=dd93682c3c) | Dec 09, 2020 |
| Dell          | Latitude D630               | Notebook    | [92ccc6100c](https://linux-hardware.org/?probe=92ccc6100c) | Dec 05, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | Notebook    | [e2ffbd65b4](https://linux-hardware.org/?probe=e2ffbd65b4) | Dec 04, 2020 |
| Pegatron      | EVE                         | Desktop     | [08ced52205](https://linux-hardware.org/?probe=08ced52205) | Nov 29, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [44642a5ed8](https://linux-hardware.org/?probe=44642a5ed8) | Nov 27, 2020 |
| Apple         | Mac-F2218EA9                | All in one  | [201739da91](https://linux-hardware.org/?probe=201739da91) | Nov 25, 2020 |
| Apple         | Mac-F2218EA9                | All in one  | [abd1a36454](https://linux-hardware.org/?probe=abd1a36454) | Nov 23, 2020 |
| Acer          | Aspire A315-42              | Notebook    | [1b5583ba18](https://linux-hardware.org/?probe=1b5583ba18) | Nov 23, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1bc0a5a430](https://linux-hardware.org/?probe=1bc0a5a430) | Nov 23, 2020 |
| HP            | 250 G7 Notebook PC          | Notebook    | [bc3c7d8910](https://linux-hardware.org/?probe=bc3c7d8910) | Nov 22, 2020 |
| HP            | 250 G7 Notebook PC          | Notebook    | [db1f0e1247](https://linux-hardware.org/?probe=db1f0e1247) | Nov 22, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | Notebook    | [5978ba6a13](https://linux-hardware.org/?probe=5978ba6a13) | Nov 22, 2020 |
| Intel         | NUC8BEB J72692-304          | Mini pc     | [505fb108f7](https://linux-hardware.org/?probe=505fb108f7) | Nov 21, 2020 |
| HP            | 470 G7 Notebook PC          | Notebook    | [f0d3574818](https://linux-hardware.org/?probe=f0d3574818) | Nov 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8783481f8a](https://linux-hardware.org/?probe=8783481f8a) | Nov 15, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | Notebook    | [1298138505](https://linux-hardware.org/?probe=1298138505) | Nov 13, 2020 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [c3df499de1](https://linux-hardware.org/?probe=c3df499de1) | Nov 12, 2020 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [e05c144d2f](https://linux-hardware.org/?probe=e05c144d2f) | Nov 12, 2020 |
| HP            | ProBook 4720s               | Notebook    | [e58dca9ad5](https://linux-hardware.org/?probe=e58dca9ad5) | Nov 11, 2020 |
| Lenovo        | ThinkCentre M55e 9389WEG    | Desktop     | [2462c80a14](https://linux-hardware.org/?probe=2462c80a14) | Nov 10, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [e8f7b6ef7e](https://linux-hardware.org/?probe=e8f7b6ef7e) | Nov 07, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [7e9d52855a](https://linux-hardware.org/?probe=7e9d52855a) | Nov 07, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3ecd75648c](https://linux-hardware.org/?probe=3ecd75648c) | Nov 06, 2020 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [b9007f3b4f](https://linux-hardware.org/?probe=b9007f3b4f) | Nov 05, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [1e6ba50614](https://linux-hardware.org/?probe=1e6ba50614) | Nov 04, 2020 |
| Intel         | DH87RL AAG74240-403         | Desktop     | [caa0e9c93b](https://linux-hardware.org/?probe=caa0e9c93b) | Nov 02, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [0b3fe9a6f2](https://linux-hardware.org/?probe=0b3fe9a6f2) | Nov 01, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [49bc5032be](https://linux-hardware.org/?probe=49bc5032be) | Nov 01, 2020 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [fa6d538a50](https://linux-hardware.org/?probe=fa6d538a50) | Oct 31, 2020 |
| Microsoft     | Surface Pro 4               | Tablet      | [9c9e8ac41c](https://linux-hardware.org/?probe=9c9e8ac41c) | Oct 24, 2020 |
| MSI           | B360M PRO-VDH               | Desktop     | [d336eeaa8d](https://linux-hardware.org/?probe=d336eeaa8d) | Oct 21, 2020 |
| Lenovo        | 3098 NOK                    | Desktop     | [2c592ebb94](https://linux-hardware.org/?probe=2c592ebb94) | Oct 19, 2020 |
| Lenovo        | 3098 NOK                    | Desktop     | [92a22bd753](https://linux-hardware.org/?probe=92a22bd753) | Oct 19, 2020 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [2e8b092dbc](https://linux-hardware.org/?probe=2e8b092dbc) | Oct 12, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [3ad72de5c7](https://linux-hardware.org/?probe=3ad72de5c7) | Oct 09, 2020 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [da4740881e](https://linux-hardware.org/?probe=da4740881e) | Oct 04, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [2c625d510e](https://linux-hardware.org/?probe=2c625d510e) | Oct 03, 2020 |
| Pegatron      | 2A94h                       | Desktop     | [3a1ede6188](https://linux-hardware.org/?probe=3a1ede6188) | Oct 03, 2020 |
| Unknown       | Unknown                     | Phone       | [f4bd5779b6](https://linux-hardware.org/?probe=f4bd5779b6) | Oct 02, 2020 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [1d3401ff46](https://linux-hardware.org/?probe=1d3401ff46) | Oct 02, 2020 |
| Intel         | NUC7i3BNB J22859-302        | Mini pc     | [afa81d3409](https://linux-hardware.org/?probe=afa81d3409) | Oct 01, 2020 |
| Lenovo        | ThinkPad P53 20QN000DGE     | Notebook    | [3a0bc546cc](https://linux-hardware.org/?probe=3a0bc546cc) | Sep 28, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [f12775338c](https://linux-hardware.org/?probe=f12775338c) | Sep 27, 2020 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | Notebook    | [1a20b51c58](https://linux-hardware.org/?probe=1a20b51c58) | Sep 24, 2020 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | Notebook    | [ca8c660b91](https://linux-hardware.org/?probe=ca8c660b91) | Sep 24, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [8bba4f976e](https://linux-hardware.org/?probe=8bba4f976e) | Sep 20, 2020 |
| Intel         | DQ35JO AAD82085-801         | Desktop     | [51c42a0f25](https://linux-hardware.org/?probe=51c42a0f25) | Sep 17, 2020 |
| Dell          | Vostro 3550                 | Notebook    | [ef71fe525d](https://linux-hardware.org/?probe=ef71fe525d) | Sep 17, 2020 |
| Unknown       | Unknown                     | Phone       | [e49d4429f4](https://linux-hardware.org/?probe=e49d4429f4) | Sep 15, 2020 |
| Unknown       | Unknown                     | Phone       | [6354f593f4](https://linux-hardware.org/?probe=6354f593f4) | Sep 15, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [41b9e8cb16](https://linux-hardware.org/?probe=41b9e8cb16) | Sep 15, 2020 |
| ASUSTek       | VivoBook S14 X430UA         | Notebook    | [85ab9de98f](https://linux-hardware.org/?probe=85ab9de98f) | Sep 03, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [94e860aade](https://linux-hardware.org/?probe=94e860aade) | Sep 03, 2020 |
| PC Special... | Fusion IV                   | Notebook    | [55da1618ab](https://linux-hardware.org/?probe=55da1618ab) | Aug 30, 2020 |
| Lenovo        | IdeaPad 320-17ISK 80XJ      | Notebook    | [a87567fe16](https://linux-hardware.org/?probe=a87567fe16) | Aug 27, 2020 |
| HP            | ProBook 4540s               | Notebook    | [32346e7861](https://linux-hardware.org/?probe=32346e7861) | Aug 26, 2020 |
| Pegatron      | 2A73                        | Desktop     | [a4607af679](https://linux-hardware.org/?probe=a4607af679) | Aug 25, 2020 |
| Pegatron      | 2A73                        | Desktop     | [f2c225880d](https://linux-hardware.org/?probe=f2c225880d) | Aug 25, 2020 |
| HP            | 3048h                       | Desktop     | [0bc2b9bafc](https://linux-hardware.org/?probe=0bc2b9bafc) | Aug 17, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | Notebook    | [438b0df832](https://linux-hardware.org/?probe=438b0df832) | Jul 21, 2020 |
| HP            | 2000                        | Notebook    | [1facf761c9](https://linux-hardware.org/?probe=1facf761c9) | Jul 19, 2020 |
| Lenovo        | ThinkPad T420 423662G       | Notebook    | [f0e52bdb36](https://linux-hardware.org/?probe=f0e52bdb36) | Jul 10, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | Notebook    | [b78049616e](https://linux-hardware.org/?probe=b78049616e) | Jul 09, 2020 |
| Lenovo        | ThinkPad T480 20L6S01W00    | Notebook    | [758a8710d7](https://linux-hardware.org/?probe=758a8710d7) | Jun 29, 2020 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [c323481902](https://linux-hardware.org/?probe=c323481902) | Jun 14, 2020 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [6889f53e3b](https://linux-hardware.org/?probe=6889f53e3b) | Jun 13, 2020 |
| HP            | ProBook 4540s               | Notebook    | [98a9e4902b](https://linux-hardware.org/?probe=98a9e4902b) | Jun 08, 2020 |
| ASRock        | X570 Extreme4               | Desktop     | [add6daf97a](https://linux-hardware.org/?probe=add6daf97a) | Jun 07, 2020 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [d7dee77bfc](https://linux-hardware.org/?probe=d7dee77bfc) | Jun 04, 2020 |
| HP            | ProBook 4540s               | Notebook    | [2b515ca642](https://linux-hardware.org/?probe=2b515ca642) | May 31, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [a8e5567ca8](https://linux-hardware.org/?probe=a8e5567ca8) | May 30, 2020 |
| Gigabyte      | B85M-HD3                    | Desktop     | [03b36ff9c1](https://linux-hardware.org/?probe=03b36ff9c1) | May 28, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [bea6687b8b](https://linux-hardware.org/?probe=bea6687b8b) | May 27, 2020 |
| ASRock        | Z390 Pro4                   | Desktop     | [e1c0c74ca6](https://linux-hardware.org/?probe=e1c0c74ca6) | May 25, 2020 |
| Acer          | Aspire V3-771               | Notebook    | [910279b054](https://linux-hardware.org/?probe=910279b054) | May 25, 2020 |
| Lenovo        | ThinkPad X250 20CM004ESC    | Notebook    | [793c164825](https://linux-hardware.org/?probe=793c164825) | May 25, 2020 |
| MSI           | H61M-P31                    | Desktop     | [870b2534d7](https://linux-hardware.org/?probe=870b2534d7) | May 22, 2020 |
| HP            | ProBook 470 G2              | Notebook    | [d39ca7c5fa](https://linux-hardware.org/?probe=d39ca7c5fa) | May 15, 2020 |
| MSI           | H110M ECO                   | Desktop     | [fe6009a465](https://linux-hardware.org/?probe=fe6009a465) | May 15, 2020 |
| HP            | 15                          | Notebook    | [fa65501be6](https://linux-hardware.org/?probe=fa65501be6) | May 10, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [91d3944426](https://linux-hardware.org/?probe=91d3944426) | May 10, 2020 |
| HP            | 250 G6 Notebook PC          | Notebook    | [ee92e64256](https://linux-hardware.org/?probe=ee92e64256) | May 07, 2020 |
| HP            | ProBook 4515s (VC377ES#A... | Notebook    | [3ec25a2e7a](https://linux-hardware.org/?probe=3ec25a2e7a) | May 01, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [a1de2f2fe9](https://linux-hardware.org/?probe=a1de2f2fe9) | Apr 18, 2020 |
| Lenovo        | ThinkCentre M55e 9389W11    | Desktop     | [f148017266](https://linux-hardware.org/?probe=f148017266) | Apr 12, 2020 |
| Lenovo        | ThinkPad T590 20N5S0YN00    | Notebook    | [0efab1d69f](https://linux-hardware.org/?probe=0efab1d69f) | Apr 08, 2020 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [f9c3afb706](https://linux-hardware.org/?probe=f9c3afb706) | Apr 08, 2020 |
| Gigabyte      | B360M DS3H                  | Desktop     | [17dd7e6ddb](https://linux-hardware.org/?probe=17dd7e6ddb) | Apr 05, 2020 |
| Lenovo        | ThinkCentre M57e 9356W2K    | Desktop     | [663d112138](https://linux-hardware.org/?probe=663d112138) | Apr 02, 2020 |
| ASUSTek       | X750LB                      | Notebook    | [a7c5fb20f8](https://linux-hardware.org/?probe=a7c5fb20f8) | Mar 28, 2020 |
| Lenovo        | G510 20238                  | Notebook    | [9130b68bf4](https://linux-hardware.org/?probe=9130b68bf4) | Mar 22, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | Notebook    | [ff84ae40b8](https://linux-hardware.org/?probe=ff84ae40b8) | Mar 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | Notebook    | [0877aa97e7](https://linux-hardware.org/?probe=0877aa97e7) | Mar 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | Notebook    | [677f41b346](https://linux-hardware.org/?probe=677f41b346) | Mar 21, 2020 |
| HP            | 0A58h                       | Desktop     | [0734e4224d](https://linux-hardware.org/?probe=0734e4224d) | Mar 16, 2020 |
| Lenovo        | ThinkPad P52 20MAS5XN00     | Notebook    | [48cd703e5b](https://linux-hardware.org/?probe=48cd703e5b) | Mar 05, 2020 |
| Lenovo        | ThinkPad P52 20MAS5XN00     | Notebook    | [e6a4ad2c61](https://linux-hardware.org/?probe=e6a4ad2c61) | Mar 04, 2020 |
| HP            | EliteBook 8760w             | Notebook    | [624fd6f7fa](https://linux-hardware.org/?probe=624fd6f7fa) | Mar 01, 2020 |
| ASUSTek       | H110M-A                     | Desktop     | [9a43e8f82a](https://linux-hardware.org/?probe=9a43e8f82a) | Feb 26, 2020 |
| ASUSTek       | H110M-A                     | Desktop     | [0722f7ccf8](https://linux-hardware.org/?probe=0722f7ccf8) | Feb 22, 2020 |
| Lenovo        | ThinkPad E595 20NF0000GE    | Notebook    | [608fef5510](https://linux-hardware.org/?probe=608fef5510) | Feb 03, 2020 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [44e0ce8fc8](https://linux-hardware.org/?probe=44e0ce8fc8) | Jan 24, 2020 |
| Medion        | MS-7707                     | Desktop     | [3feacd8f08](https://linux-hardware.org/?probe=3feacd8f08) | Jan 19, 2020 |
| Medion        | MS-7707                     | Desktop     | [5d5096c9a8](https://linux-hardware.org/?probe=5d5096c9a8) | Jan 18, 2020 |
| Biostar       | TH55B HD                    | Desktop     | [3f28da0706](https://linux-hardware.org/?probe=3f28da0706) | Jan 17, 2020 |
| HP            | 829B                        | All in one  | [d626be0762](https://linux-hardware.org/?probe=d626be0762) | Jan 09, 2020 |
| Lenovo        | ThinkPad E590 20NB002BSC    | Notebook    | [b20e37d478](https://linux-hardware.org/?probe=b20e37d478) | Jan 06, 2020 |
| Dell          | Latitude 5500               | Notebook    | [84e2b9bc59](https://linux-hardware.org/?probe=84e2b9bc59) | Jan 03, 2020 |
| HP            | EliteBook 850 G6            | Notebook    | [0d7f336b82](https://linux-hardware.org/?probe=0d7f336b82) | Jan 03, 2020 |
| Dell          | Latitude 5500               | Notebook    | [0d946e75f9](https://linux-hardware.org/?probe=0d946e75f9) | Jan 03, 2020 |
| Dell          | Latitude 5500               | Notebook    | [be70af9da7](https://linux-hardware.org/?probe=be70af9da7) | Jan 03, 2020 |
| Biostar       | TH55B HD                    | Desktop     | [980b5da590](https://linux-hardware.org/?probe=980b5da590) | Jan 02, 2020 |
| Biostar       | TH55B HD                    | Desktop     | [e13730f188](https://linux-hardware.org/?probe=e13730f188) | Dec 25, 2019 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [d853ff31e4](https://linux-hardware.org/?probe=d853ff31e4) | Dec 08, 2019 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [25e0799d44](https://linux-hardware.org/?probe=25e0799d44) | Dec 08, 2019 |
| HP            | 1495                        | Desktop     | [d56240bfb5](https://linux-hardware.org/?probe=d56240bfb5) | Dec 07, 2019 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [de68096cdc](https://linux-hardware.org/?probe=de68096cdc) | Nov 27, 2019 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [7ad66ff018](https://linux-hardware.org/?probe=7ad66ff018) | Nov 23, 2019 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [837d7c2621](https://linux-hardware.org/?probe=837d7c2621) | Nov 23, 2019 |
| HP            | 1495                        | Desktop     | [7517e7c74d](https://linux-hardware.org/?probe=7517e7c74d) | Nov 20, 2019 |
| HP            | 1495                        | Desktop     | [b4598c0e73](https://linux-hardware.org/?probe=b4598c0e73) | Nov 19, 2019 |
| HP            | 1495                        | Desktop     | [ab3f7ddb42](https://linux-hardware.org/?probe=ab3f7ddb42) | Nov 05, 2019 |
| MSI           | GP60 2OD                    | Notebook    | [f450b0d5d4](https://linux-hardware.org/?probe=f450b0d5d4) | Oct 20, 2019 |
| HP            | 1495                        | Desktop     | [75e4e80f87](https://linux-hardware.org/?probe=75e4e80f87) | Oct 04, 2019 |
| HP            | EliteBook 6930p             | Notebook    | [b11cbf51cb](https://linux-hardware.org/?probe=b11cbf51cb) | Sep 28, 2019 |
| HP            | 1495                        | Desktop     | [470c7daaaa](https://linux-hardware.org/?probe=470c7daaaa) | Sep 20, 2019 |
| HP            | 1495                        | Desktop     | [4f34ee60db](https://linux-hardware.org/?probe=4f34ee60db) | Sep 17, 2019 |
| Lenovo        | G585 20137                  | Notebook    | [084d318c5c](https://linux-hardware.org/?probe=084d318c5c) | Sep 16, 2019 |
| Acer          | Aspire E5-573G              | Notebook    | [d2242a3cd4](https://linux-hardware.org/?probe=d2242a3cd4) | Sep 02, 2019 |
| eMachines     | G730                        | Notebook    | [af8b954f82](https://linux-hardware.org/?probe=af8b954f82) | Aug 29, 2019 |
| ASUSTek       | G751JT                      | Notebook    | [a5f96019bd](https://linux-hardware.org/?probe=a5f96019bd) | Aug 04, 2019 |
| Medion        | MS-7707                     | Desktop     | [9b50675efd](https://linux-hardware.org/?probe=9b50675efd) | Aug 03, 2019 |
| eMachines     | G730                        | Notebook    | [5073ea0163](https://linux-hardware.org/?probe=5073ea0163) | Aug 02, 2019 |
| eMachines     | G730                        | Notebook    | [4f0fa60c8d](https://linux-hardware.org/?probe=4f0fa60c8d) | Jul 31, 2019 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [4a2455eae6](https://linux-hardware.org/?probe=4a2455eae6) | Jul 28, 2019 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [8d117b8f35](https://linux-hardware.org/?probe=8d117b8f35) | Jul 28, 2019 |
| HP            | Pavilion 15                 | Notebook    | [edf229fa5e](https://linux-hardware.org/?probe=edf229fa5e) | Jul 22, 2019 |
| Toshiba       | QOSMIO X500                 | Notebook    | [34905cb301](https://linux-hardware.org/?probe=34905cb301) | Jul 15, 2019 |
| ASUSTek       | G751JT                      | Notebook    | [3a17d38bdd](https://linux-hardware.org/?probe=3a17d38bdd) | Jul 09, 2019 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [ab7980dba3](https://linux-hardware.org/?probe=ab7980dba3) | Jul 01, 2019 |
| Lenovo        | ThinkPad T410 2522A92       | Notebook    | [68640c00d9](https://linux-hardware.org/?probe=68640c00d9) | Jun 09, 2019 |
| Medion        | MS-7707                     | Desktop     | [b843e52e30](https://linux-hardware.org/?probe=b843e52e30) | Jun 03, 2019 |
| HP            | Compaq 325                  | Notebook    | [4161a93030](https://linux-hardware.org/?probe=4161a93030) | May 16, 2019 |
| HP            | ProBook 4710s               | Notebook    | [54ed79f58d](https://linux-hardware.org/?probe=54ed79f58d) | May 15, 2019 |
| HP            | Compaq 325                  | Notebook    | [b9dadeece3](https://linux-hardware.org/?probe=b9dadeece3) | May 12, 2019 |
| HP            | Compaq 6720s                | Notebook    | [0e2550055b](https://linux-hardware.org/?probe=0e2550055b) | May 07, 2019 |
| Gigabyte      | P65                         | Notebook    | [6dfb59f508](https://linux-hardware.org/?probe=6dfb59f508) | May 07, 2019 |
| Lenovo        | ThinkCentre M57 6072VAM     | Desktop     | [c399cbb5f3](https://linux-hardware.org/?probe=c399cbb5f3) | May 04, 2019 |
| HP            | ZBook 14 G2                 | Notebook    | [e1463c9ca8](https://linux-hardware.org/?probe=e1463c9ca8) | Apr 23, 2019 |
| Lenovo        | ThinkPad W530 24479K4       | Notebook    | [7d56ca80ca](https://linux-hardware.org/?probe=7d56ca80ca) | Apr 22, 2019 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [8ad90844e8](https://linux-hardware.org/?probe=8ad90844e8) | Apr 16, 2019 |
| Medion        | MS-7707                     | Desktop     | [71684dcee4](https://linux-hardware.org/?probe=71684dcee4) | Apr 12, 2019 |
| ASUSTek       | X751NV                      | Notebook    | [a189d47b9a](https://linux-hardware.org/?probe=a189d47b9a) | Apr 09, 2019 |
| HP            | 82C0                        | Mini pc     | [1ecda8c9db](https://linux-hardware.org/?probe=1ecda8c9db) | Apr 06, 2019 |
| HP            | 82C0                        | Mini pc     | [134dd6a268](https://linux-hardware.org/?probe=134dd6a268) | Apr 06, 2019 |
| HP            | 0A68h                       | Desktop     | [fa9c3d044f](https://linux-hardware.org/?probe=fa9c3d044f) | Mar 13, 2019 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [d304d79466](https://linux-hardware.org/?probe=d304d79466) | Mar 10, 2019 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [8348d3c21e](https://linux-hardware.org/?probe=8348d3c21e) | Feb 23, 2019 |
| Dell          | Latitude E6500              | Notebook    | [abdbb02998](https://linux-hardware.org/?probe=abdbb02998) | Feb 23, 2019 |
| HP            | 82A2                        | Desktop     | [0f9aa13b55](https://linux-hardware.org/?probe=0f9aa13b55) | Feb 21, 2019 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [0407ee67e9](https://linux-hardware.org/?probe=0407ee67e9) | Feb 11, 2019 |
| Medion        | E7218                       | Notebook    | [5d97b97758](https://linux-hardware.org/?probe=5d97b97758) | Dec 16, 2018 |
| HP            | 0A68h                       | Desktop     | [7b0d921779](https://linux-hardware.org/?probe=7b0d921779) | Dec 15, 2018 |
| HP            | 0A68h                       | Desktop     | [b773c3a27d](https://linux-hardware.org/?probe=b773c3a27d) | Dec 15, 2018 |
| HP            | 0A68h                       | Desktop     | [11bcd6f218](https://linux-hardware.org/?probe=11bcd6f218) | Dec 15, 2018 |
| HP            | Unknown                     | Notebook    | [696e11ac42](https://linux-hardware.org/?probe=696e11ac42) | Nov 29, 2018 |
| HP            | Unknown                     | Notebook    | [121bf767df](https://linux-hardware.org/?probe=121bf767df) | Nov 29, 2018 |
| Lenovo        | ThinkPad Edge 326054G       | Notebook    | [6754682a3b](https://linux-hardware.org/?probe=6754682a3b) | Sep 16, 2017 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [d48dca3ee3](https://linux-hardware.org/?probe=d48dca3ee3) | Feb 18, 2017 |
| Lenovo        | ThinkPad Edge 326054G       | Notebook    | [c208f4b144](https://linux-hardware.org/?probe=c208f4b144) | Nov 24, 2016 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 54        | 19.85%  |
| Ubuntu 18.04                 | 25        | 9.19%   |
| Zorin 16                     | 8         | 2.94%   |
| Ubuntu 20.10                 | 8         | 2.94%   |
| Debian 11                    | 8         | 2.94%   |
| Xubuntu 20.04                | 7         | 2.57%   |
| KDE neon 20.04               | 7         | 2.57%   |
| Ubuntu 19.10                 | 6         | 2.21%   |
| Fedora 34                    | 5         | 1.84%   |
| ArcoLinux Rolling            | 5         | 1.84%   |
| Zorin 15                     | 4         | 1.47%   |
| Pop!_OS 20.04                | 4         | 1.47%   |
| OpenMandriva 4.3             | 4         | 1.47%   |
| Linux Mint 19.3              | 4         | 1.47%   |
| Linux Mint 19.1              | 4         | 1.47%   |
| Fedora 33                    | 4         | 1.47%   |
| Arch                         | 4         | 1.47%   |
| Ubuntu 21.10                 | 3         | 1.1%    |
| Pop!_OS 21.10                | 3         | 1.1%    |
| OpenMandriva 4.2             | 3         | 1.1%    |
| Manjaro                      | 3         | 1.1%    |
| Kubuntu 21.10                | 3         | 1.1%    |
| Kubuntu 20.04                | 3         | 1.1%    |
| Gentoo 2.6                   | 3         | 1.1%    |
| Fedora 35                    | 3         | 1.1%    |
| Debian Testing               | 3         | 1.1%    |
| Ubuntu 22.04                 | 2         | 0.74%   |
| Ubuntu 21.04                 | 2         | 0.74%   |
| Ubuntu 18.10                 | 2         | 0.74%   |
| Ubuntu 16.04                 | 2         | 0.74%   |
| ROSA R8                      | 2         | 0.74%   |
| Pop!_OS 21.04                | 2         | 0.74%   |
| Pop!_OS 20.10                | 2         | 0.74%   |
| OpenMandriva 4.50            | 2         | 0.74%   |
| Manjaro 20.2                 | 2         | 0.74%   |
| Lubuntu 20.04                | 2         | 0.74%   |
| Linux Mint 20.2              | 2         | 0.74%   |
| Linux Mint 20                | 2         | 0.74%   |
| Kubuntu 19.10                | 2         | 0.74%   |
| Kubuntu 18.04                | 2         | 0.74%   |
| Endless 3.7.4                | 2         | 0.74%   |
| Endless 3.6.3                | 2         | 0.74%   |
| Endless 3.5.8                | 2         | 0.74%   |
| EndeavourOS                  | 2         | 0.74%   |
| BlackPanther 18.1            | 2         | 0.74%   |
| Android                      | 2         | 0.74%   |
| Xubuntu 21.10                | 1         | 0.37%   |
| Xubuntu 18.04                | 1         | 0.37%   |
| Ubuntu MATE 18.04            | 1         | 0.37%   |
| Ubuntu Kylin 20.04           | 1         | 0.37%   |
| Ubuntu Budgie 20.04          | 1         | 0.37%   |
| Ubuntu 19.04                 | 1         | 0.37%   |
| ROSA R9                      | 1         | 0.37%   |
| Q4OS 4                       | 1         | 0.37%   |
| Pop!_OS 22.04                | 1         | 0.37%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.37%   |
| Manjaro 21.2.3               | 1         | 0.37%   |
| Manjaro 21.2.0               | 1         | 0.37%   |
| Manjaro 21.0.4               | 1         | 0.37%   |
| Manjaro 21.0.2               | 1         | 0.37%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 101       | 39.3%   |
| Linux Mint    | 14        | 5.45%   |
| Fedora        | 13        | 5.06%   |
| Pop!_OS       | 12        | 4.67%   |
| Debian        | 12        | 4.67%   |
| Zorin         | 11        | 4.28%   |
| Manjaro       | 11        | 4.28%   |
| Kubuntu       | 11        | 4.28%   |
| Xubuntu       | 9         | 3.5%    |
| Endless       | 9         | 3.5%    |
| OpenMandriva  | 8         | 3.11%   |
| KDE neon      | 8         | 3.11%   |
| Gentoo        | 5         | 1.95%   |
| ArcoLinux     | 5         | 1.95%   |
| Arch          | 4         | 1.56%   |
| Lubuntu       | 3         | 1.17%   |
| EndeavourOS   | 3         | 1.17%   |
| ROSA          | 2         | 0.78%   |
| BlackPanther  | 2         | 0.78%   |
| Android       | 2         | 0.78%   |
| Ubuntu MATE   | 1         | 0.39%   |
| Ubuntu Kylin  | 1         | 0.39%   |
| Ubuntu Budgie | 1         | 0.39%   |
| Q4OS          | 1         | 0.39%   |
| openSUSE      | 1         | 0.39%   |
| Mageia        | 1         | 0.39%   |
| Garuda Linux  | 1         | 0.39%   |
| Elementary    | 1         | 0.39%   |
| Clear Linux   | 1         | 0.39%   |
| Chrome OS     | 1         | 0.39%   |
| CentOS        | 1         | 0.39%   |
| Artix         | 1         | 0.39%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-48-generic         | 7         | 2.35%   |
| 4.18.0-15-generic        | 6         | 2.01%   |
| 5.4.0-42-generic         | 5         | 1.68%   |
| 5.3.0-40-generic         | 5         | 1.68%   |
| 5.13.0-30-generic        | 5         | 1.68%   |
| 5.8.0-41-generic         | 4         | 1.34%   |
| 5.16.7-desktop-1omv4003  | 4         | 1.34%   |
| 5.13.0-41-generic        | 4         | 1.34%   |
| 5.13.0-28-generic        | 4         | 1.34%   |
| 5.11.0-40-generic        | 4         | 1.34%   |
| 5.8.0-43-generic         | 3         | 1.01%   |
| 5.8.0-36-generic         | 3         | 1.01%   |
| 5.8.0-14-generic         | 3         | 1.01%   |
| 5.4.0-70-generic         | 3         | 1.01%   |
| 5.4.0-60-generic         | 3         | 1.01%   |
| 5.4.0-54-generic         | 3         | 1.01%   |
| 5.4.0-52-generic         | 3         | 1.01%   |
| 5.4.0-31-generic         | 3         | 1.01%   |
| 5.4.0-29-generic         | 3         | 1.01%   |
| 5.4.0-26-generic         | 3         | 1.01%   |
| 5.3.0-26-generic         | 3         | 1.01%   |
| 5.13.0-21-generic        | 3         | 1.01%   |
| 5.11.0-43-generic        | 3         | 1.01%   |
| 5.10.14-desktop-1omv4002 | 3         | 1.01%   |
| 4.18.0-17-generic        | 3         | 1.01%   |
| 5.9.2-arch1-1            | 2         | 0.67%   |
| 5.8.0-7630-generic       | 2         | 0.67%   |
| 5.8.0-53-generic         | 2         | 0.67%   |
| 5.8.0-44-generic         | 2         | 0.67%   |
| 5.6.14-desktop-2bP       | 2         | 0.67%   |
| 5.6.0-1-amd64            | 2         | 0.67%   |
| 5.4.0-90-generic         | 2         | 0.67%   |
| 5.4.0-89-generic         | 2         | 0.67%   |
| 5.4.0-7642-generic       | 2         | 0.67%   |
| 5.4.0-66-generic         | 2         | 0.67%   |
| 5.4.0-58-generic         | 2         | 0.67%   |
| 5.4.0-56-generic         | 2         | 0.67%   |
| 5.4.0-40-generic         | 2         | 0.67%   |
| 5.4.0-33-generic         | 2         | 0.67%   |
| 5.4.0-28-generic         | 2         | 0.67%   |
| 5.3.0-23-generic         | 2         | 0.67%   |
| 5.3.0-19-generic         | 2         | 0.67%   |
| 5.16.15-76051615-generic | 2         | 0.67%   |
| 5.13.19-2-MANJARO        | 2         | 0.67%   |
| 5.13.0-7614-generic      | 2         | 0.67%   |
| 5.13.0-27-generic        | 2         | 0.67%   |
| 5.13.0-22-generic        | 2         | 0.67%   |
| 5.12.4-desktop-1omv4050  | 2         | 0.67%   |
| 5.11.0-38-generic        | 2         | 0.67%   |
| 5.10.0-8-amd64           | 2         | 0.67%   |
| 5.10.0-10-amd64          | 2         | 0.67%   |
| 5.0.0-25-generic         | 2         | 0.67%   |
| 5.0.0-23-generic         | 2         | 0.67%   |
| 4.18.16-desktop-1bP      | 2         | 0.67%   |
| 4.15.0-46-generic        | 2         | 0.67%   |
| 4.15.0-45-generic        | 2         | 0.67%   |
| 4.15.0-42-generic        | 2         | 0.67%   |
| 4.15.0-20-generic        | 2         | 0.67%   |
| 4.15.0-128-generic       | 2         | 0.67%   |
| 5.9.8-2-MANJARO          | 1         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 64        | 22.7%   |
| 5.8.0   | 28        | 9.93%   |
| 5.13.0  | 24        | 8.51%   |
| 5.11.0  | 18        | 6.38%   |
| 5.3.0   | 16        | 5.67%   |
| 4.15.0  | 16        | 5.67%   |
| 4.18.0  | 15        | 5.32%   |
| 5.10.0  | 7         | 2.48%   |
| 5.0.0   | 6         | 2.13%   |
| 5.16.7  | 5         | 1.77%   |
| 5.10.14 | 5         | 1.77%   |
| 5.6.0   | 4         | 1.42%   |
| 5.9.2   | 2         | 0.71%   |
| 5.9.15  | 2         | 0.71%   |
| 5.6.14  | 2         | 0.71%   |
| 5.16.15 | 2         | 0.71%   |
| 5.15.2  | 2         | 0.71%   |
| 5.15.0  | 2         | 0.71%   |
| 5.14.16 | 2         | 0.71%   |
| 5.13.19 | 2         | 0.71%   |
| 5.12.8  | 2         | 0.71%   |
| 5.12.4  | 2         | 0.71%   |
| 5.10.30 | 2         | 0.71%   |
| 4.18.16 | 2         | 0.71%   |
| 5.9.8   | 1         | 0.35%   |
| 5.9.14  | 1         | 0.35%   |
| 5.8.8   | 1         | 0.35%   |
| 5.8.6   | 1         | 0.35%   |
| 5.8.5   | 1         | 0.35%   |
| 5.8.18  | 1         | 0.35%   |
| 5.8.10  | 1         | 0.35%   |
| 5.7.13  | 1         | 0.35%   |
| 5.7.0   | 1         | 0.35%   |
| 5.5.15  | 1         | 0.35%   |
| 5.5.0   | 1         | 0.35%   |
| 5.4.80  | 1         | 0.35%   |
| 5.4.53  | 1         | 0.35%   |
| 5.4.27  | 1         | 0.35%   |
| 5.4.14  | 1         | 0.35%   |
| 5.3.6   | 1         | 0.35%   |
| 5.17.5  | 1         | 0.35%   |
| 5.17.4  | 1         | 0.35%   |
| 5.17.1  | 1         | 0.35%   |
| 5.16.4  | 1         | 0.35%   |
| 5.16.19 | 1         | 0.35%   |
| 5.16.18 | 1         | 0.35%   |
| 5.16.16 | 1         | 0.35%   |
| 5.16.0  | 1         | 0.35%   |
| 5.15.6  | 1         | 0.35%   |
| 5.15.5  | 1         | 0.35%   |
| 5.15.16 | 1         | 0.35%   |
| 5.15.10 | 1         | 0.35%   |
| 5.14.11 | 1         | 0.35%   |
| 5.14.10 | 1         | 0.35%   |
| 5.14.0  | 1         | 0.35%   |
| 5.13.9  | 1         | 0.35%   |
| 5.13.8  | 1         | 0.35%   |
| 5.13.16 | 1         | 0.35%   |
| 5.12.9  | 1         | 0.35%   |
| 5.12.2  | 1         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 67        | 24.1%   |
| 5.8     | 33        | 11.87%  |
| 5.13    | 28        | 10.07%  |
| 5.11    | 21        | 7.55%   |
| 5.3     | 17        | 6.12%   |
| 4.18    | 17        | 6.12%   |
| 4.15    | 16        | 5.76%   |
| 5.10    | 15        | 5.4%    |
| 5.16    | 12        | 4.32%   |
| 5.15    | 7         | 2.52%   |
| 5.12    | 7         | 2.52%   |
| 5.6     | 6         | 2.16%   |
| 5.0     | 6         | 2.16%   |
| 5.9     | 5         | 1.8%    |
| 5.14    | 5         | 1.8%    |
| 5.17    | 3         | 1.08%   |
| 5.7     | 2         | 0.72%   |
| 5.5     | 2         | 0.72%   |
| 4.19    | 2         | 0.72%   |
| 4.1     | 2         | 0.72%   |
| 3.18    | 2         | 0.72%   |
| 4.9     | 1         | 0.36%   |
| 4.20    | 1         | 0.36%   |
| 4.14    | 1         | 0.36%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 237       | 95.18%  |
| i686    | 5         | 2.01%   |
| aarch64 | 5         | 2.01%   |
| armv8l  | 2         | 0.8%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 114       | 43.51%  |
| Unknown         | 44        | 16.79%  |
| KDE5            | 34        | 12.98%  |
| XFCE            | 25        | 9.54%   |
| X-Cinnamon      | 10        | 3.82%   |
| KDE             | 9         | 3.44%   |
| Cinnamon        | 6         | 2.29%   |
| LXQt            | 4         | 1.53%   |
| Unity           | 3         | 1.15%   |
| MATE            | 2         | 0.76%   |
| dwm             | 2         | 0.76%   |
| UKUI            | 1         | 0.38%   |
| Trinity         | 1         | 0.38%   |
| Pantheon        | 1         | 0.38%   |
| Openbox         | 1         | 0.38%   |
| NsCDE           | 1         | 0.38%   |
| KDE4            | 1         | 0.38%   |
| i3              | 1         | 0.38%   |
| GNOME Flashback | 1         | 0.38%   |
| Budgie          | 1         | 0.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 199       | 76.83%  |
| Unknown | 30        | 11.58%  |
| Wayland | 25        | 9.65%   |
| Tty     | 5         | 1.93%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 143       | 54.58%  |
| SDDM    | 37        | 14.12%  |
| GDM     | 33        | 12.6%   |
| LightDM | 21        | 8.02%   |
| TDM     | 14        | 5.34%   |
| GDM3    | 12        | 4.58%   |
| XDM     | 1         | 0.38%   |
| KDM     | 1         | 0.38%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 116       | 45.85%  |
| sl_SI   | 70        | 27.67%  |
| Unknown | 44        | 17.39%  |
| en_GB   | 12        | 4.74%   |
| C       | 5         | 1.98%   |
| en_SI   | 3         | 1.19%   |
| it_IT   | 1         | 0.4%    |
| hr_HR   | 1         | 0.4%    |
| de_DE   | 1         | 0.4%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 128       | 50.2%   |
| EFI  | 127       | 49.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 201       | 78.82%  |
| Overlay | 18        | 7.06%   |
| Unknown | 16        | 6.27%   |
| Btrfs   | 13        | 5.1%    |
| Zfs     | 4         | 1.57%   |
| Xfs     | 2         | 0.78%   |
| Ext2    | 1         | 0.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 152       | 59.38%  |
| GPT     | 74        | 28.91%  |
| MBR     | 30        | 11.72%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 222       | 87.06%  |
| Yes       | 33        | 12.94%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 180       | 70.87%  |
| Yes       | 74        | 29.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 57        | 22.89%  |
| Lenovo                  | 48        | 19.28%  |
| ASUSTek Computer        | 45        | 18.07%  |
| Gigabyte Technology     | 18        | 7.23%   |
| Dell                    | 16        | 6.43%   |
| MSI                     | 10        | 4.02%   |
| ASRock                  | 9         | 3.61%   |
| Intel                   | 7         | 2.81%   |
| Acer                    | 6         | 2.41%   |
| Raspberry Pi Foundation | 5         | 2.01%   |
| Toshiba                 | 4         | 1.61%   |
| Pegatron                | 4         | 1.61%   |
| Apple                   | 4         | 1.61%   |
| Medion                  | 3         | 1.2%    |
| Fujitsu                 | 2         | 0.8%    |
| Unknown                 | 2         | 0.8%    |
| Supermicro              | 1         | 0.4%    |
| Razer                   | 1         | 0.4%    |
| PC Specialist           | 1         | 0.4%    |
| Panasonic               | 1         | 0.4%    |
| Microsoft               | 1         | 0.4%    |
| Fujitsu Siemens         | 1         | 0.4%    |
| eMachines               | 1         | 0.4%    |
| Biostar                 | 1         | 0.4%    |
| Acidanthera             | 1         | 0.4%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| HP 255 G7 Notebook PC                      | 3         | 1.2%    |
| Unknown                                    | 3         | 1.2%    |
| Toshiba Satellite L750                     | 2         | 0.8%    |
| RPi Raspberry Pi 400 Rev 1.0               | 2         | 0.8%    |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 2         | 0.8%    |
| Pegatron FL308AA-ABD IQ512de               | 2         | 0.8%    |
| MSI MS-7C02                                | 2         | 0.8%    |
| MSI MS-7788                                | 2         | 0.8%    |
| Lenovo ThinkPad T410 2522A92               | 2         | 0.8%    |
| HP Spectre x360 Convertible 13-ae0xx       | 2         | 0.8%    |
| HP EliteBook 8760w                         | 2         | 0.8%    |
| Gigabyte F2A88XM-D3HP                      | 2         | 0.8%    |
| Dell Inspiron 5570                         | 2         | 0.8%    |
| ASUS ROG STRIX Z370-F GAMING               | 2         | 0.8%    |
| ASUS ROG STRIX X570-E GAMING               | 2         | 0.8%    |
| ASUS PRIME B350-PLUS                       | 2         | 0.8%    |
| ASUS PRIME A320M-K                         | 2         | 0.8%    |
| ASUS P7H55-M SI                            | 2         | 0.8%    |
| Toshiba Satellite Pro U400                 | 1         | 0.4%    |
| Toshiba QOSMIO X500                        | 1         | 0.4%    |
| Supermicro PCplus T600-C246                | 1         | 0.4%    |
| Razer Blade 14 - RZ09-0370                 | 1         | 0.4%    |
| RPi Raspberry Pi 4 Model B Rev 1.1 (DT)    | 1         | 0.4%    |
| Pegatron Pro 3010 Microtower PC            | 1         | 0.4%    |
| Pegatron 2A73                              | 1         | 0.4%    |
| PC Specialist Fusion IV                    | 1         | 0.4%    |
| Panasonic CF-53SWWZ5MG                     | 1         | 0.4%    |
| MSI U210                                   | 1         | 0.4%    |
| MSI MS-7C37                                | 1         | 0.4%    |
| MSI MS-7B24                                | 1         | 0.4%    |
| MSI MS-7994                                | 1         | 0.4%    |
| MSI MS-7636                                | 1         | 0.4%    |
| MSI GP60 2OD                               | 1         | 0.4%    |
| Microsoft Surface Pro 4                    | 1         | 0.4%    |
| Medion MS-7707                             | 1         | 0.4%    |
| Medion E7218                               | 1         | 0.4%    |
| Medion Akoya E7226                         | 1         | 0.4%    |
| Lenovo Yoga S740-14IIL 81RS                | 1         | 0.4%    |
| Lenovo Yoga 2 13 20344                     | 1         | 0.4%    |
| Lenovo ThinkStation S20 4157ZSK            | 1         | 0.4%    |
| Lenovo ThinkStation P330 Tiny 30CF000XMH   | 1         | 0.4%    |
| Lenovo ThinkPad X250 20CM004ESC            | 1         | 0.4%    |
| Lenovo ThinkPad X230 23202DG               | 1         | 0.4%    |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW      | 1         | 0.4%    |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 1         | 0.4%    |
| Lenovo ThinkPad W530 24479K4               | 1         | 0.4%    |
| Lenovo ThinkPad T61 8897CTO                | 1         | 0.4%    |
| Lenovo ThinkPad T590 20N5S0YN00            | 1         | 0.4%    |
| Lenovo ThinkPad T590 20N5S0MR00            | 1         | 0.4%    |
| Lenovo ThinkPad T500 2055WYX               | 1         | 0.4%    |
| Lenovo ThinkPad T480 20L6S01W00            | 1         | 0.4%    |
| Lenovo ThinkPad T460s 20FAS7XT01           | 1         | 0.4%    |
| Lenovo ThinkPad T420 4236A78               | 1         | 0.4%    |
| Lenovo ThinkPad T420 423662G               | 1         | 0.4%    |
| Lenovo ThinkPad T15 Gen 1 20S6000NSC       | 1         | 0.4%    |
| Lenovo ThinkPad S3 Yoga 14 20DM008FSC      | 1         | 0.4%    |
| Lenovo ThinkPad R61 8933W4F                | 1         | 0.4%    |
| Lenovo ThinkPad P53 20QN000DGE             | 1         | 0.4%    |
| Lenovo ThinkPad P52 20MAS5XN00             | 1         | 0.4%    |
| Lenovo ThinkPad L520 785958G               | 1         | 0.4%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 29        | 11.65%  |
| HP EliteBook           | 10        | 4.02%   |
| ASUS PRIME             | 10        | 4.02%   |
| HP ProBook             | 9         | 3.61%   |
| Lenovo ThinkCentre     | 7         | 2.81%   |
| HP Compaq              | 6         | 2.41%   |
| Dell Inspiron          | 6         | 2.41%   |
| ASUS ROG               | 6         | 2.41%   |
| RPi Raspberry          | 5         | 2.01%   |
| Lenovo IdeaPad         | 5         | 2.01%   |
| HP ZBook               | 4         | 1.61%   |
| HP 250                 | 4         | 1.61%   |
| Dell Latitude          | 4         | 1.61%   |
| ASUS TUF               | 4         | 1.61%   |
| Acer Aspire            | 4         | 1.61%   |
| Toshiba Satellite      | 3         | 1.2%    |
| HP Pavilion            | 3         | 1.2%    |
| HP 255                 | 3         | 1.2%    |
| ASUS VivoBook          | 3         | 1.2%    |
| Unknown                | 3         | 1.2%    |
| Pegatron FL308AA-ABD   | 2         | 0.8%    |
| MSI MS-7C02            | 2         | 0.8%    |
| MSI MS-7788            | 2         | 0.8%    |
| Lenovo Yoga            | 2         | 0.8%    |
| Lenovo ThinkStation    | 2         | 0.8%    |
| HP Spectre             | 2         | 0.8%    |
| HP Laptop              | 2         | 0.8%    |
| Gigabyte F2A88XM-D3HP  | 2         | 0.8%    |
| Gigabyte B450M         | 2         | 0.8%    |
| Dell XPS               | 2         | 0.8%    |
| Dell Precision         | 2         | 0.8%    |
| ASUS P7H55-M           | 2         | 0.8%    |
| Toshiba QOSMIO         | 1         | 0.4%    |
| Supermicro PCplus      | 1         | 0.4%    |
| Razer Blade            | 1         | 0.4%    |
| Pegatron Pro           | 1         | 0.4%    |
| Pegatron 2A73          | 1         | 0.4%    |
| PC Specialist Fusion   | 1         | 0.4%    |
| Panasonic CF-53SWWZ5MG | 1         | 0.4%    |
| MSI U210               | 1         | 0.4%    |
| MSI MS-7C37            | 1         | 0.4%    |
| MSI MS-7B24            | 1         | 0.4%    |
| MSI MS-7994            | 1         | 0.4%    |
| MSI MS-7636            | 1         | 0.4%    |
| MSI GP60               | 1         | 0.4%    |
| Microsoft Surface      | 1         | 0.4%    |
| Medion MS-7707         | 1         | 0.4%    |
| Medion E7218           | 1         | 0.4%    |
| Medion Akoya           | 1         | 0.4%    |
| Lenovo Legion          | 1         | 0.4%    |
| Lenovo G585            | 1         | 0.4%    |
| Lenovo G510            | 1         | 0.4%    |
| Intel NUC8i5BEK        | 1         | 0.4%    |
| Intel NUC7i3BNB        | 1         | 0.4%    |
| Intel NUC5i7RYB        | 1         | 0.4%    |
| Intel DQ67SW           | 1         | 0.4%    |
| Intel DQ35JO           | 1         | 0.4%    |
| Intel DH87RL           | 1         | 0.4%    |
| Intel CM-iAM           | 1         | 0.4%    |
| HP Z420                | 1         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 26        | 10.44%  |
| 2017    | 25        | 10.04%  |
| 2018    | 23        | 9.24%   |
| 2020    | 20        | 8.03%   |
| 2011    | 20        | 8.03%   |
| 2009    | 20        | 8.03%   |
| 2013    | 16        | 6.43%   |
| 2015    | 14        | 5.62%   |
| 2010    | 14        | 5.62%   |
| 2014    | 13        | 5.22%   |
| 2012    | 12        | 4.82%   |
| 2008    | 10        | 4.02%   |
| 2021    | 8         | 3.21%   |
| 2016    | 8         | 3.21%   |
| 2007    | 8         | 3.21%   |
| Unknown | 7         | 2.81%   |
| 2006    | 5         | 2.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 131       | 52.61%  |
| Desktop        | 93        | 37.35%  |
| All in one     | 6         | 2.41%   |
| System on chip | 5         | 2.01%   |
| Mini pc        | 5         | 2.01%   |
| Convertible    | 3         | 1.2%    |
| Phone          | 2         | 0.8%    |
| Tablet         | 2         | 0.8%    |
| Server         | 2         | 0.8%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 234       | 93.23%  |
| Enabled  | 17        | 6.77%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 248       | 99.6%   |
| Yes  | 1         | 0.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 59        | 23.51%  |
| 16.01-24.0      | 54        | 21.51%  |
| 8.01-16.0       | 54        | 21.51%  |
| 4.01-8.0        | 42        | 16.73%  |
| 32.01-64.0      | 20        | 7.97%   |
| 2.01-3.0        | 7         | 2.79%   |
| 1.01-2.0        | 5         | 1.99%   |
| 24.01-32.0      | 4         | 1.59%   |
| 64.01-256.0     | 4         | 1.59%   |
| More than 256.0 | 1         | 0.4%    |
| 0.51-1.0        | 1         | 0.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 98        | 35.13%  |
| 2.01-3.0   | 67        | 24.01%  |
| 4.01-8.0   | 38        | 13.62%  |
| 3.01-4.0   | 33        | 11.83%  |
| 0.51-1.0   | 19        | 6.81%   |
| 8.01-16.0  | 15        | 5.38%   |
| 0.01-0.5   | 5         | 1.79%   |
| 16.01-24.0 | 3         | 1.08%   |
| 24.01-32.0 | 1         | 0.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 151       | 59.22%  |
| 2      | 65        | 25.49%  |
| 3      | 18        | 7.06%   |
| 4      | 6         | 2.35%   |
| 0      | 5         | 1.96%   |
| 6      | 3         | 1.18%   |
| 5      | 3         | 1.18%   |
| 8      | 2         | 0.78%   |
| 7      | 2         | 0.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 138       | 55.2%   |
| Yes       | 112       | 44.8%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 223       | 89.56%  |
| No        | 26        | 10.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 174       | 69.32%  |
| No        | 77        | 30.68%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 139       | 55.38%  |
| No        | 112       | 44.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Slovenia | 249       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Ljubljana               | 92        | 33.95%  |
| Celje                   | 8         | 2.95%   |
| Maribor                 | 7         | 2.58%   |
| Kranj                   | 7         | 2.58%   |
| Koper                   | 7         | 2.58%   |
| Vrhnika                 | 5         | 1.85%   |
| Novo Mesto              | 5         | 1.85%   |
| Trzin                   | 4         | 1.48%   |
| Rence                   | 4         | 1.48%   |
| Portorož               | 4         | 1.48%   |
| Grosuplje               | 4         | 1.48%   |
| Žalec                  | 3         | 1.11%   |
| Slovenske Konjice       | 3         | 1.11%   |
| Radovljica              | 3         | 1.11%   |
| Ptuj                    | 3         | 1.11%   |
| Pragersko               | 3         | 1.11%   |
| Petrovce                | 3         | 1.11%   |
| Logatec                 | 3         | 1.11%   |
| Kamnik                  | 3         | 1.11%   |
| Ziri                    | 2         | 0.74%   |
| Zgornja Besnica         | 2         | 0.74%   |
| Velike Lašče          | 2         | 0.74%   |
| Velenje                 | 2         | 0.74%   |
| Slovenj Gradec          | 2         | 0.74%   |
| Šentjur pri Celju      | 2         | 0.74%   |
| Puconci                 | 2         | 0.74%   |
| Poljane nad Skofjo Loko | 2         | 0.74%   |
| Oplotnica               | 2         | 0.74%   |
| Nova Gorica             | 2         | 0.74%   |
| Muta                    | 2         | 0.74%   |
| Murska Sobota           | 2         | 0.74%   |
| Cerknica                | 2         | 0.74%   |
| Ajdovščina            | 2         | 0.74%   |
| Žužemberk             | 1         | 0.37%   |
| Zirovnica               | 1         | 0.37%   |
| Zgornji Leskovec        | 1         | 0.37%   |
| Zgornja Kungota         | 1         | 0.37%   |
| Zagorje ob Savi         | 1         | 0.37%   |
| Vuzenica                | 1         | 0.37%   |
| Volcja Draga            | 1         | 0.37%   |
| Visoko                  | 1         | 0.37%   |
| Trzic                   | 1         | 0.37%   |
| Trbovlje                | 1         | 0.37%   |
| Tabor                   | 1         | 0.37%   |
| Štore                  | 1         | 0.37%   |
| Stari Trg pri Lozu      | 1         | 0.37%   |
| Solkan                  | 1         | 0.37%   |
| Smartno ob Paki         | 1         | 0.37%   |
| Smarje pri Jelsah       | 1         | 0.37%   |
| Slovenska Bistrica      | 1         | 0.37%   |
| Škofja Loka            | 1         | 0.37%   |
| Skocjan                 | 1         | 0.37%   |
| Sežana                 | 1         | 0.37%   |
| Šentjernej             | 1         | 0.37%   |
| Sempeter pri Gorici     | 1         | 0.37%   |
| Selnica ob Dravi        | 1         | 0.37%   |
| Ruše                   | 1         | 0.37%   |
| Rogasovci               | 1         | 0.37%   |
| Rogaška Slatina        | 1         | 0.37%   |
| Preserje pri Komnu      | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| WDC                     | 65        | 113    | 18.57%  |
| Samsung Electronics     | 46        | 75     | 13.14%  |
| Seagate                 | 36        | 58     | 10.29%  |
| Toshiba                 | 31        | 44     | 8.86%   |
| Kingston                | 24        | 33     | 6.86%   |
| Crucial                 | 24        | 35     | 6.86%   |
| SanDisk                 | 16        | 20     | 4.57%   |
| Unknown                 | 15        | 18     | 4.29%   |
| Hitachi                 | 12        | 15     | 3.43%   |
| HGST                    | 11        | 12     | 3.14%   |
| SK Hynix                | 10        | 13     | 2.86%   |
| Intel                   | 7         | 7      | 2%      |
| Intenso                 | 5         | 7      | 1.43%   |
| Corsair                 | 4         | 5      | 1.14%   |
| Transcend               | 3         | 4      | 0.86%   |
| Patriot                 | 3         | 5      | 0.86%   |
| OCZ                     | 3         | 6      | 0.86%   |
| Apacer                  | 3         | 3      | 0.86%   |
| Silicon Motion          | 2         | 2      | 0.57%   |
| Micron Technology       | 2         | 2      | 0.57%   |
| LITEONIT                | 2         | 2      | 0.57%   |
| LITEON                  | 2         | 2      | 0.57%   |
| Hewlett-Packard         | 2         | 2      | 0.57%   |
| Gigabyte Technology     | 2         | 4      | 0.57%   |
| Fujitsu                 | 2         | 3      | 0.57%   |
| Apple                   | 2         | 2      | 0.57%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.29%   |
| TS512GMT                | 1         | 3      | 0.29%   |
| Team                    | 1         | 1      | 0.29%   |
| SABRENT                 | 1         | 1      | 0.29%   |
| Realtek                 | 1         | 1      | 0.29%   |
| Phison                  | 1         | 1      | 0.29%   |
| MAXTOR                  | 1         | 1      | 0.29%   |
| Leven                   | 1         | 1      | 0.29%   |
| Lenovo                  | 1         | 1      | 0.29%   |
| KIOXIA                  | 1         | 1      | 0.29%   |
| KingDian                | 1         | 1      | 0.29%   |
| JMicron                 | 1         | 1      | 0.29%   |
| HGST HTS                | 1         | 1      | 0.29%   |
| GOODRAM                 | 1         | 1      | 0.29%   |
| China                   | 1         | 1      | 0.29%   |
| A-DATA Technology       | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 7         | 1.76%   |
| Crucial CT240BX500SSD1 240GB        | 7         | 1.76%   |
| Toshiba DT01ACA100 1TB              | 5         | 1.26%   |
| Samsung NVMe SSD Drive 256GB        | 5         | 1.26%   |
| HGST HTS721010A9E630 1TB            | 5         | 1.26%   |
| Unknown MMC Card  16GB              | 4         | 1.01%   |
| Samsung SSD 850 EVO 250GB           | 4         | 1.01%   |
| Samsung NVMe SSD Drive 512GB        | 4         | 1.01%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 3         | 0.76%   |
| WDC WD10EARS-00Y5B1 1TB             | 3         | 0.76%   |
| Unknown MMC Card  32GB              | 3         | 0.76%   |
| Toshiba DT01ACA200 2TB              | 3         | 0.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 0.76%   |
| Sandisk NVMe SSD Drive 500GB        | 3         | 0.76%   |
| Samsung SSD 860 EVO 1TB             | 3         | 0.76%   |
| Kingston SUV400S37240G 240GB SSD    | 3         | 0.76%   |
| Kingston SA400S37120G 120GB SSD     | 3         | 0.76%   |
| Hitachi HTS547575A9E384 752GB       | 3         | 0.76%   |
| HGST HTS545050A7E680 500GB          | 3         | 0.76%   |
| Crucial CT1000MX500SSD1 1TB         | 3         | 0.76%   |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 2         | 0.5%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 2         | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2         | 0.5%    |
| WDC WD5000AADS-00S9B0 500GB         | 2         | 0.5%    |
| WDC WD5000AACS-00G8B1 500GB         | 2         | 0.5%    |
| WDC WD10EZEX-08M2NA0 1TB            | 2         | 0.5%    |
| WDC WD1002FAEX-00Y9A0 1TB           | 2         | 0.5%    |
| Unknown MMC Card                    | 2         | 0.5%    |
| Toshiba MQ04ABF100 1TB              | 2         | 0.5%    |
| Toshiba MQ01ABF050 500GB            | 2         | 0.5%    |
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 2         | 0.5%    |
| Toshiba HDWD120 2TB                 | 2         | 0.5%    |
| SK Hynix SC311 SATA 256GB SSD       | 2         | 0.5%    |
| Seagate ST9750420AS 752GB           | 2         | 0.5%    |
| Seagate ST9500325AS 500GB           | 2         | 0.5%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 0.5%    |
| Seagate ST1000DM003-1CH162 1TB      | 2         | 0.5%    |
| Seagate Portable 1TB                | 2         | 0.5%    |
| SanDisk SSD PLUS 1000GB             | 2         | 0.5%    |
| Sandisk NVMe SSD Drive 512GB        | 2         | 0.5%    |
| Samsung SSD 970 EVO Plus 500GB      | 2         | 0.5%    |
| Samsung SSD 970 EVO Plus 1TB        | 2         | 0.5%    |
| Samsung SSD 970 EVO 500GB           | 2         | 0.5%    |
| Samsung SSD 860 QVO 1TB             | 2         | 0.5%    |
| Samsung SSD 860 EVO 500GB           | 2         | 0.5%    |
| Samsung SSD 850 EVO 120GB           | 2         | 0.5%    |
| Samsung SSD 840 EVO 250GB           | 2         | 0.5%    |
| Samsung NVMe SSD Drive 500GB        | 2         | 0.5%    |
| Samsung NVMe SSD Drive 1024GB       | 2         | 0.5%    |
| Kingston SV300S37A120G 120GB SSD    | 2         | 0.5%    |
| Intenso 128GB                       | 2         | 0.5%    |
| Hitachi HTS725032A9A364 320GB       | 2         | 0.5%    |
| HP SSD EX900 500GB                  | 2         | 0.5%    |
| Crucial CT500MX500SSD1 500GB        | 2         | 0.5%    |
| Crucial CT2000MX500SSD1 2TB         | 2         | 0.5%    |
| WDC WUS721010ALE6L4 10TB            | 1         | 0.25%   |
| WDC WDS500G3X0C-00SJG0 500GB        | 1         | 0.25%   |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 1         | 0.25%   |
| WDC WDS500G2B0A 500GB SSD           | 1         | 0.25%   |
| WDC WDS256G1X0C-00ENX0 256GB        | 1         | 0.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 50        | 91     | 35.97%  |
| Seagate             | 35        | 56     | 25.18%  |
| Toshiba             | 22        | 32     | 15.83%  |
| Hitachi             | 12        | 15     | 8.63%   |
| HGST                | 11        | 12     | 7.91%   |
| Samsung Electronics | 2         | 2      | 1.44%   |
| Fujitsu             | 2         | 3      | 1.44%   |
| Unknown             | 1         | 1      | 0.72%   |
| SABRENT             | 1         | 1      | 0.72%   |
| MAXTOR              | 1         | 1      | 0.72%   |
| HGST HTS            | 1         | 1      | 0.72%   |
| Apple               | 1         | 1      | 0.72%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 31     | 17.6%   |
| Kingston            | 22        | 28     | 17.6%   |
| Crucial             | 22        | 33     | 17.6%   |
| WDC                 | 14        | 16     | 11.2%   |
| SanDisk             | 9         | 12     | 7.2%    |
| Intel               | 4         | 4      | 3.2%    |
| Transcend           | 3         | 4      | 2.4%    |
| SK Hynix            | 3         | 3      | 2.4%    |
| Patriot             | 3         | 5      | 2.4%    |
| OCZ                 | 3         | 6      | 2.4%    |
| Intenso             | 3         | 3      | 2.4%    |
| Toshiba             | 2         | 2      | 1.6%    |
| LITEONIT            | 2         | 2      | 1.6%    |
| LITEON              | 2         | 2      | 1.6%    |
| Corsair             | 2         | 3      | 1.6%    |
| Apacer              | 2         | 2      | 1.6%    |
| Micron Technology   | 1         | 1      | 0.8%    |
| Leven               | 1         | 1      | 0.8%    |
| KingDian            | 1         | 1      | 0.8%    |
| GOODRAM             | 1         | 1      | 0.8%    |
| Gigabyte Technology | 1         | 2      | 0.8%    |
| China               | 1         | 1      | 0.8%    |
| A-DATA Technology   | 1         | 1      | 0.8%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 121       | 216    | 37.46%  |
| SSD     | 110       | 164    | 34.06%  |
| NVMe    | 73        | 104    | 22.6%   |
| MMC     | 12        | 15     | 3.72%   |
| Unknown | 7         | 11     | 2.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 188       | 373    | 65.73%  |
| NVMe | 73        | 103    | 25.52%  |
| SAS  | 13        | 19     | 4.55%   |
| MMC  | 12        | 15     | 4.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 137       | 216    | 56.85%  |
| 0.51-1.0   | 75        | 121    | 31.12%  |
| 1.01-2.0   | 17        | 24     | 7.05%   |
| 3.01-4.0   | 6         | 11     | 2.49%   |
| 2.01-3.0   | 2         | 3      | 0.83%   |
| 10.01-20.0 | 2         | 2      | 0.83%   |
| 4.01-10.0  | 2         | 3      | 0.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 64        | 24.15%  |
| 251-500        | 63        | 23.77%  |
| 501-1000       | 38        | 14.34%  |
| 1001-2000      | 27        | 10.19%  |
| 1-20           | 17        | 6.42%   |
| 51-100         | 14        | 5.28%   |
| 2001-3000      | 13        | 4.91%   |
| 21-50          | 12        | 4.53%   |
| Unknown        | 10        | 3.77%   |
| More than 3000 | 7         | 2.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 107       | 39.93%  |
| 21-50     | 36        | 13.43%  |
| 101-250   | 33        | 12.31%  |
| 51-100    | 33        | 12.31%  |
| 251-500   | 21        | 7.84%   |
| 1001-2000 | 11        | 4.1%    |
| 501-1000  | 11        | 4.1%    |
| Unknown   | 10        | 3.73%   |
| 2001-3000 | 6         | 2.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB         | 2         | 2      | 6.67%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 1      | 3.33%   |
| WDC WD5000AADS-00S9B0 500GB        | 1         | 1      | 3.33%   |
| WDC WD40EFRX-68N32N0 4TB           | 1         | 1      | 3.33%   |
| WDC WD3200AAKS-22B3A0 320GB        | 1         | 1      | 3.33%   |
| WDC WD20EFRX-68EUZN0 2TB           | 1         | 1      | 3.33%   |
| Toshiba Q300. 240GB SSD            | 1         | 1      | 3.33%   |
| Toshiba MQ01ABF050 500GB           | 1         | 5      | 3.33%   |
| Toshiba DT01ACA300 3TB             | 1         | 1      | 3.33%   |
| Seagate ST9750420AS 752GB          | 1         | 1      | 3.33%   |
| Seagate ST9500423AS 500GB          | 1         | 1      | 3.33%   |
| Seagate ST9500325AS 500GB          | 1         | 2      | 3.33%   |
| Seagate ST3500514NS 500GB          | 1         | 1      | 3.33%   |
| Seagate ST3500320NS 500GB          | 1         | 1      | 3.33%   |
| Seagate ST3320620AS 320GB          | 1         | 1      | 3.33%   |
| Seagate ST3200822AS 200GB          | 1         | 1      | 3.33%   |
| Seagate ST2000DM001-1CH164 2TB     | 1         | 1      | 3.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 3.33%   |
| Seagate ST1000DM003-1CH162 1TB     | 1         | 1      | 3.33%   |
| SanDisk SD7SB2Q512G1001 512GB SSD  | 1         | 1      | 3.33%   |
| OCZ VERTEX3 120GB SSD              | 1         | 1      | 3.33%   |
| Kingston SV300S37A120G 120GB SSD   | 1         | 1      | 3.33%   |
| Kingston SA400S37240G 240GB SSD    | 1         | 1      | 3.33%   |
| Intel SSDSA2M160G2GC 160GB         | 1         | 1      | 3.33%   |
| Hitachi HTS727550A9E364 500GB      | 1         | 1      | 3.33%   |
| HGST HTS721010A9E630 1TB           | 1         | 1      | 3.33%   |
| Hewlett-Packard SSD EX900 500GB    | 1         | 1      | 3.33%   |
| Crucial M4-CT128M4SSD2 128GB       | 1         | 1      | 3.33%   |
| Crucial CT120M500SSD1 120GB        | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| Seagate         | 8         | 11     | 29.63%  |
| WDC             | 4         | 5      | 14.81%  |
| Toshiba         | 3         | 7      | 11.11%  |
| HGST            | 3         | 3      | 11.11%  |
| Kingston        | 2         | 2      | 7.41%   |
| Crucial         | 2         | 2      | 7.41%   |
| SanDisk         | 1         | 1      | 3.7%    |
| OCZ             | 1         | 1      | 3.7%    |
| Intel           | 1         | 1      | 3.7%    |
| Hitachi         | 1         | 1      | 3.7%    |
| Hewlett-Packard | 1         | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 11     | 47.06%  |
| WDC     | 3         | 4      | 17.65%  |
| HGST    | 3         | 3      | 17.65%  |
| Toshiba | 2         | 6      | 11.76%  |
| Hitachi | 1         | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 25     | 62.5%   |
| SSD  | 8         | 9      | 33.33%  |
| NVMe | 1         | 1      | 4.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                   | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba MK6465GSX 640GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 158       | 289    | 58.96%  |
| Works    | 85        | 184    | 31.72%  |
| Malfunc  | 24        | 35     | 8.96%   |
| Failed   | 1         | 2      | 0.37%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 178       | 57.05%  |
| AMD                              | 38        | 12.18%  |
| Samsung Electronics              | 33        | 10.58%  |
| Sandisk                          | 13        | 4.17%   |
| Toshiba America Info Systems     | 8         | 2.56%   |
| SK Hynix                         | 7         | 2.24%   |
| JMicron Technology               | 5         | 1.6%    |
| Silicon Motion                   | 4         | 1.28%   |
| Phison Electronics               | 4         | 1.28%   |
| Marvell Technology Group         | 4         | 1.28%   |
| Kingston Technology Company      | 3         | 0.96%   |
| Micron/Crucial Technology        | 2         | 0.64%   |
| ASMedia Technology               | 2         | 0.64%   |
| Union Memory (Shenzhen)          | 1         | 0.32%   |
| Silicon Integrated Systems [SiS] | 1         | 0.32%   |
| Silicon Image                    | 1         | 0.32%   |
| Shenzhen Longsys Electronics     | 1         | 0.32%   |
| OCZ Technology Group             | 1         | 0.32%   |
| Nvidia                           | 1         | 0.32%   |
| Micron Technology                | 1         | 0.32%   |
| Lenovo                           | 1         | 0.32%   |
| KIOXIA                           | 1         | 0.32%   |
| Hewlett-Packard                  | 1         | 0.32%   |
| Broadcom / LSI                   | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 29        | 7.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 20        | 5.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12        | 3.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 11        | 3.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 10        | 2.75%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10        | 2.75%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 8         | 2.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7         | 1.93%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 7         | 1.93%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7         | 1.93%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 6         | 1.65%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6         | 1.65%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6         | 1.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 6         | 1.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 6         | 1.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6         | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6         | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5         | 1.38%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4         | 1.1%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4         | 1.1%    |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 4         | 1.1%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 1.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 4         | 1.1%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 4         | 1.1%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 1.1%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4         | 1.1%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 1.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4         | 1.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 4         | 1.1%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4         | 1.1%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 3         | 0.83%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 3         | 0.83%   |
| SK Hynix Gold P31 SSD                                                                   | 3         | 0.83%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 3         | 0.83%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3         | 0.83%   |
| Samsung NVMe SSD Controller 980                                                         | 3         | 0.83%   |
| JMicron JMB368 IDE controller                                                           | 3         | 0.83%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 0.83%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 0.83%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 3         | 0.83%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3         | 0.83%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3         | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3         | 0.83%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 0.55%   |
| SK Hynix BC511                                                                          | 2         | 0.55%   |
| Sandisk PC SN520 NVMe SSD                                                               | 2         | 0.55%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2         | 0.55%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 2         | 0.55%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2         | 0.55%   |
| Intel SSD 660P Series                                                                   | 2         | 0.55%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2         | 0.55%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 0.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2         | 0.55%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 0.55%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2         | 0.55%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2         | 0.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 2         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 172       | 54.95%  |
| NVMe | 78        | 24.92%  |
| IDE  | 44        | 14.06%  |
| RAID | 16        | 5.11%   |
| SAS  | 2         | 0.64%   |
| SCSI | 1         | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 198       | 79.52%  |
| AMD    | 44        | 17.67%  |
| ARM    | 7         | 2.81%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 2.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.01%   |
| ARM Processor                                 | 5         | 2.01%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 1.61%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.2%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.2%    |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 1.2%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3         | 1.2%    |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 3         | 1.2%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 1.2%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.2%    |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2         | 0.8%    |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.8%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.8%    |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 0.8%    |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 0.8%    |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 0.8%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.8%    |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 2         | 0.8%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.8%    |
| Intel Core i5-7400 CPU @ 3.00GHz              | 2         | 0.8%    |
| Intel Core i5-6400 CPU @ 2.70GHz              | 2         | 0.8%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.8%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.8%    |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2         | 0.8%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.8%    |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.8%    |
| Intel Core i5-3550 CPU @ 3.30GHz              | 2         | 0.8%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.8%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 0.8%    |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2         | 0.8%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 0.8%    |
| Intel Core i5 CPU 750 @ 2.67GHz               | 2         | 0.8%    |
| Intel Core i5 CPU 650 @ 3.20GHz               | 2         | 0.8%    |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.8%    |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 0.8%    |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 2         | 0.8%    |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz          | 2         | 0.8%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 0.8%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 0.8%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.8%    |
| AMD Ryzen 9 5900X 12-Core Processor           | 2         | 0.8%    |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 0.8%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 0.8%    |
| AMD Ryzen 5 5600X 6-Core Processor            | 2         | 0.8%    |
| AMD Ryzen 5 1600X Six-Core Processor          | 2         | 0.8%    |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 2         | 0.8%    |
| Intel Xeon CPU X5365 @ 3.00GHz                | 1         | 0.4%    |
| Intel Xeon CPU W3565 @ 3.20GHz                | 1         | 0.4%    |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz            | 1         | 0.4%    |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz           | 1         | 0.4%    |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz            | 1         | 0.4%    |
| Intel Xeon CPU E3-1245 v6 @ 3.70GHz           | 1         | 0.4%    |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz           | 1         | 0.4%    |
| Intel Xeon CPU E3-1225 v6 @ 3.30GHz           | 1         | 0.4%    |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz           | 1         | 0.4%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.4%    |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 1         | 0.4%    |
| Intel Pentium D CPU 2.80GHz                   | 1         | 0.4%    |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 63        | 25.3%   |
| Intel Core i7           | 54        | 21.69%  |
| Intel Core 2 Duo        | 22        | 8.84%   |
| Intel Core i3           | 17        | 6.83%   |
| AMD Ryzen 5             | 13        | 5.22%   |
| Other                   | 12        | 4.82%   |
| Intel Xeon              | 9         | 3.61%   |
| Intel Celeron           | 8         | 3.21%   |
| AMD Ryzen 7             | 8         | 3.21%   |
| Intel Pentium           | 7         | 2.81%   |
| AMD Ryzen 3             | 6         | 2.41%   |
| AMD Ryzen 9             | 5         | 2.01%   |
| Intel Core 2            | 4         | 1.61%   |
| Intel Core 2 Quad       | 3         | 1.2%    |
| Intel Atom              | 2         | 0.8%    |
| Intel Pentium Silver    | 1         | 0.4%    |
| Intel Pentium Dual      | 1         | 0.4%    |
| Intel Pentium D         | 1         | 0.4%    |
| ARM AArch64             | 1         | 0.4%    |
| AMD Turion II Dual-Core | 1         | 0.4%    |
| AMD Turion II           | 1         | 0.4%    |
| AMD Phenom II X6        | 1         | 0.4%    |
| AMD Phenom II X4        | 1         | 0.4%    |
| AMD FX                  | 1         | 0.4%    |
| AMD E1                  | 1         | 0.4%    |
| AMD E                   | 1         | 0.4%    |
| AMD Athlon X4           | 1         | 0.4%    |
| AMD Athlon Neo          | 1         | 0.4%    |
| AMD Athlon II X2        | 1         | 0.4%    |
| AMD A8                  | 1         | 0.4%    |
| AMD A10                 | 1         | 0.4%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 102       | 40.96%  |
| 2      | 99        | 39.76%  |
| 6      | 28        | 11.24%  |
| 8      | 14        | 5.62%   |
| 12     | 4         | 1.61%   |
| 1      | 2         | 0.8%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 245       | 98.39%  |
| 2      | 4         | 1.61%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 153       | 61.45%  |
| 1      | 96        | 38.55%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 236       | 94.02%  |
| Unknown        | 14        | 5.58%   |
| 32-bit         | 1         | 0.4%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 18.22%  |
| 0x206a7    | 16        | 6.2%    |
| 0x306a9    | 14        | 5.43%   |
| 0x306c3    | 12        | 4.65%   |
| 0x906ea    | 11        | 4.26%   |
| 0x906e9    | 11        | 4.26%   |
| 0x806ec    | 9         | 3.49%   |
| 0x1067a    | 8         | 3.1%    |
| 0x806ea    | 7         | 2.71%   |
| 0x40651    | 7         | 2.71%   |
| 0x20655    | 7         | 2.71%   |
| 0x10676    | 7         | 2.71%   |
| 0x106e5    | 6         | 2.33%   |
| 0x6fd      | 5         | 1.94%   |
| 0x506e3    | 5         | 1.94%   |
| 0x30678    | 5         | 1.94%   |
| 0x08108102 | 5         | 1.94%   |
| 0x906ed    | 4         | 1.55%   |
| 0x806c1    | 4         | 1.55%   |
| 0x6fb      | 4         | 1.55%   |
| 0x306d4    | 4         | 1.55%   |
| 0x406e3    | 3         | 1.16%   |
| 0x20652    | 3         | 1.16%   |
| 0x0a201016 | 3         | 1.16%   |
| 0x0810100b | 3         | 1.16%   |
| 0x08001138 | 3         | 1.16%   |
| 0xa0671    | 2         | 0.78%   |
| 0x706e5    | 2         | 0.78%   |
| 0x506c9    | 2         | 0.78%   |
| 0x206d7    | 2         | 0.78%   |
| 0x0a201009 | 2         | 0.78%   |
| 0x08600106 | 2         | 0.78%   |
| 0x08108109 | 2         | 0.78%   |
| 0x0800820d | 2         | 0.78%   |
| 0x08001137 | 2         | 0.78%   |
| 0x010000dc | 2         | 0.78%   |
| 0xf47      | 1         | 0.39%   |
| 0xa0660    | 1         | 0.39%   |
| 0xa0655    | 1         | 0.39%   |
| 0xa0652    | 1         | 0.39%   |
| 0x906eb    | 1         | 0.39%   |
| 0x806eb    | 1         | 0.39%   |
| 0x706a1    | 1         | 0.39%   |
| 0x6f7      | 1         | 0.39%   |
| 0x6f6      | 1         | 0.39%   |
| 0x6f2      | 1         | 0.39%   |
| 0x406c4    | 1         | 0.39%   |
| 0x306e4    | 1         | 0.39%   |
| 0x106c2    | 1         | 0.39%   |
| 0x106a5    | 1         | 0.39%   |
| 0x0a50000c | 1         | 0.39%   |
| 0x08701013 | 1         | 0.39%   |
| 0x08608103 | 1         | 0.39%   |
| 0x08608102 | 1         | 0.39%   |
| 0x0700010f | 1         | 0.39%   |
| 0x06006113 | 1         | 0.39%   |
| 0x06003106 | 1         | 0.39%   |
| 0x06001119 | 1         | 0.39%   |
| 0x05000119 | 1         | 0.39%   |
| 0x010000c8 | 1         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 51        | 20.48%  |
| Haswell       | 22        | 8.84%   |
| SandyBridge   | 19        | 7.63%   |
| Penryn        | 17        | 6.83%   |
| IvyBridge     | 16        | 6.43%   |
| Core          | 15        | 6.02%   |
| Unknown       | 11        | 4.42%   |
| Westmere      | 10        | 4.02%   |
| Skylake       | 10        | 4.02%   |
| Zen+          | 9         | 3.61%   |
| Zen           | 9         | 3.61%   |
| Zen 3         | 7         | 2.81%   |
| Nehalem       | 7         | 2.81%   |
| Broadwell     | 7         | 2.81%   |
| Silvermont    | 6         | 2.41%   |
| K10           | 5         | 2.01%   |
| Zen 2         | 4         | 1.61%   |
| TigerLake     | 4         | 1.61%   |
| Icelake       | 4         | 1.61%   |
| CometLake     | 3         | 1.2%    |
| Piledriver    | 2         | 0.8%    |
| Goldmont plus | 2         | 0.8%    |
| Goldmont      | 2         | 0.8%    |
| Steamroller   | 1         | 0.4%    |
| NetBurst      | 1         | 0.4%    |
| K8 Hammer     | 1         | 0.4%    |
| Jaguar        | 1         | 0.4%    |
| Excavator     | 1         | 0.4%    |
| Bonnell       | 1         | 0.4%    |
| Bobcat        | 1         | 0.4%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 134       | 45.58%  |
| Nvidia                           | 83        | 28.23%  |
| AMD                              | 75        | 25.51%  |
| Silicon Integrated Systems [SiS] | 1         | 0.34%   |
| Matrox Electronics Systems       | 1         | 0.34%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 12        | 4%      |
| Intel 3rd Gen Core processor Graphics Controller                                      | 9         | 3%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 8         | 2.67%   |
| Intel UHD Graphics 620                                                                | 7         | 2.33%   |
| Intel HD Graphics 630                                                                 | 7         | 2.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 7         | 2.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 7         | 2.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 7         | 2.33%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 6         | 2%      |
| Intel HD Graphics 5500                                                                | 5         | 1.67%   |
| Intel Core Processor Integrated Graphics Controller                                   | 5         | 1.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 5         | 1.67%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 5         | 1.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 5         | 1.67%   |
| Nvidia GP108M [GeForce MX250]                                                         | 4         | 1.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 4         | 1.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 4         | 1.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 4         | 1.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 4         | 1.33%   |
| Nvidia GP104 [GeForce GTX 1070]                                                       | 3         | 1%      |
| Nvidia GM206 [GeForce GTX 960]                                                        | 3         | 1%      |
| Nvidia GK208M [GeForce GT 740M]                                                       | 3         | 1%      |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 3         | 1%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 3         | 1%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 3         | 1%      |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 1%      |
| AMD Renoir                                                                            | 3         | 1%      |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 3         | 1%      |
| AMD Lucienne                                                                          | 3         | 1%      |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                    | 3         | 1%      |
| Nvidia GP108 [GeForce GT 1030]                                                        | 2         | 0.67%   |
| Nvidia GP107M [GeForce MX350]                                                         | 2         | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 2         | 0.67%   |
| Nvidia GP107 [GeForce GTX 1050]                                                       | 2         | 0.67%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 2         | 0.67%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                    | 2         | 0.67%   |
| Nvidia GM108M [GeForce 940M]                                                          | 2         | 0.67%   |
| Nvidia G98M [GeForce 9300M GS]                                                        | 2         | 0.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 2         | 0.67%   |
| Intel Iris Plus Graphics G7                                                           | 2         | 0.67%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                | 2         | 0.67%   |
| Intel 82946GZ/GL Integrated Graphics Controller                                       | 2         | 0.67%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                 | 2         | 0.67%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                    | 2         | 0.67%   |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                                     | 2         | 0.67%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                          | 2         | 0.67%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                               | 2         | 0.67%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                        | 2         | 0.67%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                  | 2         | 0.67%   |
| AMD Juniper XT [Radeon HD 5770]                                                       | 2         | 0.67%   |
| AMD Cezanne                                                                           | 2         | 0.67%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                      | 2         | 0.67%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                   | 2         | 0.67%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                     | 1         | 0.33%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 0.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 0.33%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                  | 1         | 0.33%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                         | 1         | 0.33%   |
| Nvidia TU117 [GeForce GTX 1650]                                                       | 1         | 0.33%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                    | 1         | 0.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 89        | 35.46%  |
| 1 x AMD        | 54        | 21.51%  |
| 1 x Nvidia     | 50        | 19.92%  |
| Intel + Nvidia | 28        | 11.16%  |
| Intel + AMD    | 14        | 5.58%   |
| Other          | 7         | 2.79%   |
| AMD + Nvidia   | 5         | 1.99%   |
| 2 x AMD        | 2         | 0.8%    |
| 1 x SiS        | 1         | 0.4%    |
| 1 x Matrox     | 1         | 0.4%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 192       | 76.19%  |
| Proprietary | 43        | 17.06%  |
| Unknown     | 17        | 6.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 133       | 51.35%  |
| 1.01-2.0   | 46        | 17.76%  |
| 0.51-1.0   | 22        | 8.49%   |
| 0.01-0.5   | 22        | 8.49%   |
| 3.01-4.0   | 15        | 5.79%   |
| 7.01-8.0   | 9         | 3.47%   |
| 5.01-6.0   | 7         | 2.7%    |
| 2.01-3.0   | 3         | 1.16%   |
| 8.01-16.0  | 2         | 0.77%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 40        | 14.39%  |
| Samsung Electronics     | 38        | 13.67%  |
| Dell                    | 30        | 10.79%  |
| LG Display              | 19        | 6.83%   |
| AOC                     | 19        | 6.83%   |
| Chimei Innolux          | 17        | 6.12%   |
| BOE                     | 15        | 5.4%    |
| Goldstar                | 14        | 5.04%   |
| Philips                 | 12        | 4.32%   |
| Lenovo                  | 12        | 4.32%   |
| Hewlett-Packard         | 8         | 2.88%   |
| Chi Mei Optoelectronics | 6         | 2.16%   |
| Ancor Communications    | 4         | 1.44%   |
| Acer                    | 4         | 1.44%   |
| Unknown                 | 3         | 1.08%   |
| Sony                    | 3         | 1.08%   |
| Sharp                   | 3         | 1.08%   |
| Apple                   | 3         | 1.08%   |
| ViewSonic               | 2         | 0.72%   |
| LG Philips              | 2         | 0.72%   |
| Iiyama                  | 2         | 0.72%   |
| CSO                     | 2         | 0.72%   |
| BenQ                    | 2         | 0.72%   |
| Vestel Elektronik       | 1         | 0.36%   |
| Unknown (XXX)           | 1         | 0.36%   |
| TMX                     | 1         | 0.36%   |
| RS                      | 1         | 0.36%   |
| PANDA                   | 1         | 0.36%   |
| NEC Computers           | 1         | 0.36%   |
| LGD                     | 1         | 0.36%   |
| InfoVision              | 1         | 0.36%   |
| IBM                     | 1         | 0.36%   |
| HannStar                | 1         | 0.36%   |
| Gericom                 | 1         | 0.36%   |
| FUN                     | 1         | 0.36%   |
| Eizo                    | 1         | 0.36%   |
| DIF                     | 1         | 0.36%   |
| DENON                   | 1         | 0.36%   |
| CPT                     | 1         | 0.36%   |
| ASUSTek Computer        | 1         | 0.36%   |
| Arnos Instruments       | 1         | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 7         | 2.42%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 4         | 1.38%   |
| Philips LCD Monitor FTV 1920x1080                                         | 3         | 1.04%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 3         | 1.04%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 3         | 1.04%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch             | 3         | 1.04%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 2         | 0.69%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch      | 2         | 0.69%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 2         | 0.69%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                       | 2         | 0.69%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch              | 2         | 0.69%   |
| Lenovo LEN P27h-10 LEN61AF 2560x1440 600x340mm 27.2-inch                  | 2         | 0.69%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                   | 2         | 0.69%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                   | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN1376 1920x1080 293x165mm 13.2-inch          | 2         | 0.69%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.69%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                     | 2         | 0.69%   |
| BOE LCD Monitor BOE0869 1920x1080 344x194mm 15.5-inch                     | 2         | 0.69%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch            | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO129E 1600x900 382x214mm 17.2-inch             | 2         | 0.69%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                       | 2         | 0.69%   |
| AOC LCD Monitor AG251FWG2 1920x1080                                       | 2         | 0.69%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch                 | 1         | 0.35%   |
| ViewSonic VG2448 VSC3B35 1920x1080 530x300mm 24.0-inch                    | 1         | 0.35%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                             | 1         | 0.35%   |
| Unknown LCD Monitor SAMSUNG                                               | 1         | 0.35%   |
| Unknown (XXX) M22EI4 XXX076E 1680x1050 474x296mm 22.0-inch                | 1         | 0.35%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                   | 1         | 0.35%   |
| Sony TV SNYAB03 1920x1080                                                 | 1         | 0.35%   |
| Sony TV SNYAA01 1360x768                                                  | 1         | 0.35%   |
| Sony SDM-S93 SNY1390 1280x1024 359x287mm 18.1-inch                        | 1         | 0.35%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 1         | 0.35%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                   | 1         | 0.35%   |
| Sharp LCD Monitor SHP1450 3840x2160 350x190mm 15.7-inch                   | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM05EC 1920x1080 597x336mm 27.0-inch      | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM0526 1920x1080 510x287mm 23.0-inch      | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM04DE 1920x1080 477x268mm 21.5-inch      | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch      | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch      | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM041F 2048x1152 510x287mm 23.0-inch      | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch      | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 459x296mm 21.5-inch      | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM0303 1680x1050 494x320mm 23.2-inch      | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM02B5 1920x1200 518x324mm 24.1-inch      | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM0288 1680x1050 474x296mm 22.0-inch      | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM026F 1280x1024 376x301mm 19.0-inch      | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM0214 1680x1050 408x306mm 20.1-inch      | 1         | 0.35%   |
| Samsung Electronics SMS24A450/460 SAM0838 1920x1080 531x299mm 24.0-inch   | 1         | 0.35%   |
| Samsung Electronics S27D390 SAM0B66 1920x1080 598x336mm 27.0-inch         | 1         | 0.35%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 1         | 0.35%   |
| Samsung Electronics S24E450 SAM0C82 1920x1080 531x299mm 24.0-inch         | 1         | 0.35%   |
| Samsung Electronics S24D330 SAM0D93 1920x1080 531x299mm 24.0-inch         | 1         | 0.35%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch         | 1         | 0.35%   |
| Samsung Electronics S24B300 SAM08B4 1920x1080 521x293mm 23.5-inch         | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SyncMaster 2560x1024                      | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 353x198mm 15.9-inch     | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch      | 1         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 113       | 43.46%  |
| 1366x768 (WXGA)    | 29        | 11.15%  |
| 1600x900 (HD+)     | 19        | 7.31%   |
| 3840x2160 (4K)     | 17        | 6.54%   |
| 2560x1440 (QHD)    | 14        | 5.38%   |
| 1920x1200 (WUXGA)  | 13        | 5%      |
| 1680x1050 (WSXGA+) | 13        | 5%      |
| 1280x1024 (SXGA)   | 10        | 3.85%   |
| 3440x1440          | 6         | 2.31%   |
| 1440x900 (WXGA+)   | 5         | 1.92%   |
| 2560x1080          | 4         | 1.54%   |
| 2560x1600          | 3         | 1.15%   |
| 2288x1287          | 2         | 0.77%   |
| 1280x800 (WXGA)    | 2         | 0.77%   |
| Unknown            | 2         | 0.77%   |
| 3840x1200          | 1         | 0.38%   |
| 3840x1080          | 1         | 0.38%   |
| 2736x1824          | 1         | 0.38%   |
| 2560x1024          | 1         | 0.38%   |
| 2048x1152          | 1         | 0.38%   |
| 1400x1050          | 1         | 0.38%   |
| 1280x720 (HD)      | 1         | 0.38%   |
| 1024x768 (XGA)     | 1         | 0.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 68        | 24.55%  |
| 24      | 28        | 10.11%  |
| 17      | 26        | 9.39%   |
| 23      | 20        | 7.22%   |
| 21      | 18        | 6.5%    |
| 27      | 15        | 5.42%   |
| 14      | 14        | 5.05%   |
| Unknown | 14        | 5.05%   |
| 13      | 13        | 4.69%   |
| 34      | 10        | 3.61%   |
| 31      | 6         | 2.17%   |
| 22      | 6         | 2.17%   |
| 20      | 6         | 2.17%   |
| 19      | 5         | 1.81%   |
| 18      | 5         | 1.81%   |
| 12      | 4         | 1.44%   |
| 142     | 2         | 0.72%   |
| 84      | 2         | 0.72%   |
| 72      | 2         | 0.72%   |
| 65      | 2         | 0.72%   |
| 54      | 2         | 0.72%   |
| 33      | 2         | 0.72%   |
| 49      | 1         | 0.36%   |
| 39      | 1         | 0.36%   |
| 32      | 1         | 0.36%   |
| 29      | 1         | 0.36%   |
| 25      | 1         | 0.36%   |
| 16      | 1         | 0.36%   |
| 10      | 1         | 0.36%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 88        | 32.35%  |
| 501-600        | 58        | 21.32%  |
| 401-500        | 33        | 12.13%  |
| 351-400        | 32        | 11.76%  |
| 201-300        | 14        | 5.15%   |
| Unknown        | 14        | 5.15%   |
| 701-800        | 13        | 4.78%   |
| 601-700        | 8         | 2.94%   |
| 1001-1500      | 5         | 1.84%   |
| 1501-2000      | 4         | 1.47%   |
| More than 2000 | 2         | 0.74%   |
| 801-900        | 1         | 0.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 179       | 71.31%  |
| 16/10   | 32        | 12.75%  |
| Unknown | 12        | 4.78%   |
| 5/4     | 10        | 3.98%   |
| 21/9    | 10        | 3.98%   |
| 4/3     | 3         | 1.2%    |
| 3/2     | 2         | 0.8%    |
| 1.00    | 2         | 0.8%    |
| 32/9    | 1         | 0.4%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 67        | 24.28%  |
| 201-250        | 54        | 19.57%  |
| 121-130        | 22        | 7.97%   |
| 351-500        | 20        | 7.25%   |
| 81-90          | 18        | 6.52%   |
| 151-200        | 18        | 6.52%   |
| 301-350        | 15        | 5.43%   |
| Unknown        | 14        | 5.07%   |
| 251-300        | 13        | 4.71%   |
| More than 1000 | 10        | 3.62%   |
| 71-80          | 9         | 3.26%   |
| 141-150        | 5         | 1.81%   |
| 61-70          | 4         | 1.45%   |
| 131-140        | 2         | 0.72%   |
| 501-1000       | 2         | 0.72%   |
| 41-50          | 1         | 0.36%   |
| 111-120        | 1         | 0.36%   |
| 91-100         | 1         | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 89        | 33.33%  |
| 121-160       | 69        | 25.84%  |
| 101-120       | 65        | 24.34%  |
| 161-240       | 15        | 5.62%   |
| Unknown       | 14        | 5.24%   |
| 1-50          | 10        | 3.75%   |
| More than 240 | 5         | 1.87%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 200       | 77.82%  |
| 2     | 46        | 17.9%   |
| 0     | 8         | 3.11%   |
| 3     | 3         | 1.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 121       | 34.28%  |
| Intel                             | 121       | 34.28%  |
| Qualcomm Atheros                  | 37        | 10.48%  |
| Broadcom                          | 22        | 6.23%   |
| Ralink                            | 7         | 1.98%   |
| Ralink Technology                 | 5         | 1.42%   |
| Marvell Technology Group          | 5         | 1.42%   |
| ASUSTek Computer                  | 4         | 1.13%   |
| Huawei Technologies               | 3         | 0.85%   |
| Sierra Wireless                   | 2         | 0.57%   |
| Samsung Electronics               | 2         | 0.57%   |
| Linksys                           | 2         | 0.57%   |
| Hewlett-Packard                   | 2         | 0.57%   |
| Ericsson Business Mobile Networks | 2         | 0.57%   |
| Broadcom Limited                  | 2         | 0.57%   |
| ZyDAS Technology                  | 1         | 0.28%   |
| VIA Technologies                  | 1         | 0.28%   |
| TP-Link                           | 1         | 0.28%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.28%   |
| Qualcomm Atheros Communications   | 1         | 0.28%   |
| Nvidia                            | 1         | 0.28%   |
| Microsoft                         | 1         | 0.28%   |
| MEDIATEK                          | 1         | 0.28%   |
| Lenovo                            | 1         | 0.28%   |
| JMicron Technology                | 1         | 0.28%   |
| IMC Networks                      | 1         | 0.28%   |
| D-Link System                     | 1         | 0.28%   |
| D-Link                            | 1         | 0.28%   |
| Compal Electronics                | 1         | 0.28%   |
| Belkin Components                 | 1         | 0.28%   |
| ASIX Electronics                  | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 91        | 21.41%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 14        | 3.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 13        | 3.06%   |
| Intel Wi-Fi 6 AX200                                                     | 11        | 2.59%   |
| Intel Ethernet Connection (2) I219-V                                    | 10        | 2.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 1.88%   |
| Intel Wireless 8265 / 8275                                              | 7         | 1.65%   |
| Intel Wireless 7260                                                     | 7         | 1.65%   |
| Intel I211 Gigabit Network Connection                                   | 7         | 1.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 1.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.41%   |
| Intel Ethernet Connection (6) I219-V                                    | 6         | 1.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 1.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.18%   |
| Intel Wireless 7265                                                     | 5         | 1.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 1.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 0.94%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.94%   |
| Intel Ethernet Connection (7) I219-V                                    | 4         | 0.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 0.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 0.94%   |
| Intel 82577LM Gigabit Network Connection                                | 4         | 0.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.71%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3         | 0.71%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 0.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 0.71%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 3         | 0.71%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.71%   |
| Intel Ethernet Connection (7) I219-LM                                   | 3         | 0.71%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 0.71%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.71%   |
| Intel 82574L Gigabit Network Connection                                 | 3         | 0.71%   |
| Intel 82567LM Gigabit Network Connection                                | 3         | 0.71%   |
| Huawei MAR-LX1A                                                         | 3         | 0.71%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 0.71%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 2         | 0.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.47%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 2         | 0.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 0.47%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.47%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 2         | 0.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 2         | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 0.47%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.47%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                 | 2         | 0.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                 | 2         | 0.47%   |
| Intel Wireless 8260                                                     | 2         | 0.47%   |
| Intel Wireless 3165                                                     | 2         | 0.47%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.47%   |
| Intel Ethernet Connection I217-LM                                       | 2         | 0.47%   |
| Intel Ethernet Connection (4) I219-V                                    | 2         | 0.47%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 0.47%   |
| Intel Ethernet Connection (2) I219-LM                                   | 2         | 0.47%   |
| Intel Ethernet Connection (10) I219-V                                   | 2         | 0.47%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 80        | 44.2%   |
| Qualcomm Atheros                | 30        | 16.57%  |
| Realtek Semiconductor           | 26        | 14.36%  |
| Broadcom                        | 14        | 7.73%   |
| Ralink                          | 7         | 3.87%   |
| Ralink Technology               | 5         | 2.76%   |
| ASUSTek Computer                | 4         | 2.21%   |
| Sierra Wireless                 | 2         | 1.1%    |
| Broadcom Limited                | 2         | 1.1%    |
| ZyDAS Technology                | 1         | 0.55%   |
| TP-Link                         | 1         | 0.55%   |
| Qualcomm Atheros Communications | 1         | 0.55%   |
| MEDIATEK                        | 1         | 0.55%   |
| Marvell Technology Group        | 1         | 0.55%   |
| Linksys                         | 1         | 0.55%   |
| IMC Networks                    | 1         | 0.55%   |
| Hewlett-Packard                 | 1         | 0.55%   |
| D-Link System                   | 1         | 0.55%   |
| D-Link                          | 1         | 0.55%   |
| Belkin Components               | 1         | 0.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                   | 11        | 6.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 8         | 4.4%    |
| Intel Wireless 8265 / 8275                                                            | 7         | 3.85%   |
| Intel Wireless 7260                                                                   | 7         | 3.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 7         | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 6         | 3.3%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 5         | 2.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 5         | 2.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 5         | 2.75%   |
| Intel Wireless 7265                                                                   | 5         | 2.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 5         | 2.75%   |
| Intel Wi-Fi 6 AX201                                                                   | 4         | 2.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 4         | 2.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 4         | 2.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 3         | 1.65%   |
| Ralink MT7601U Wireless Adapter                                                       | 3         | 1.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 3         | 1.65%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 3         | 1.65%   |
| Intel Centrino Ultimate-N 6300                                                        | 3         | 1.65%   |
| Intel Centrino Advanced-N 6200                                                        | 3         | 1.65%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 3         | 1.65%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.1%    |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 2         | 1.1%    |
| Ralink RT2870/RT3070 Wireless Adapter                                                 | 2         | 1.1%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 2         | 1.1%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 2         | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 2         | 1.1%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 2         | 1.1%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 2         | 1.1%    |
| Intel Wireless 8260                                                                   | 2         | 1.1%    |
| Intel Wireless 3165                                                                   | 2         | 1.1%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                               | 2         | 1.1%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 2         | 1.1%    |
| Intel Centrino Advanced-N 6235                                                        | 2         | 1.1%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 2         | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 1.1%    |
| ZyDAS ZD1212B Wireless Adapter                                                        | 1         | 0.55%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                   | 1         | 0.55%   |
| Sierra Wireless MC8305 Modem                                                          | 1         | 0.55%   |
| Sierra Wireless EM7345 4G LTE                                                         | 1         | 0.55%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 1         | 0.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.55%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 0.55%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.55%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                            | 1         | 0.55%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 0.55%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1         | 0.55%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 0.55%   |
| Realtek RTL8187 Wireless Adapter                                                      | 1         | 0.55%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.55%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                  | 1         | 0.55%   |
| Ralink RT2561/RT61 802.11g PCI                                                        | 1         | 0.55%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 0.55%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 0.55%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.55%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]                | 1         | 0.55%   |
| MEDIATEK MT7630e 802.11bgn Wireless Network Adapter                                   | 1         | 0.55%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                                     | 1         | 0.55%   |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235]                         | 1         | 0.55%   |
| Intel Wireless-AC 9260                                                                | 1         | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 112       | 47.26%  |
| Intel                            | 84        | 35.44%  |
| Qualcomm Atheros                 | 12        | 5.06%   |
| Broadcom                         | 11        | 4.64%   |
| Marvell Technology Group         | 4         | 1.69%   |
| Huawei Technologies              | 3         | 1.27%   |
| Samsung Electronics              | 2         | 0.84%   |
| VIA Technologies                 | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] | 1         | 0.42%   |
| Nvidia                           | 1         | 0.42%   |
| Microsoft                        | 1         | 0.42%   |
| Linksys                          | 1         | 0.42%   |
| Lenovo                           | 1         | 0.42%   |
| JMicron Technology               | 1         | 0.42%   |
| Compal Electronics               | 1         | 0.42%   |
| ASIX Electronics                 | 1         | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 91        | 37.92%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 14        | 5.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 13        | 5.42%   |
| Intel Ethernet Connection (2) I219-V                                          | 10        | 4.17%   |
| Intel I211 Gigabit Network Connection                                         | 7         | 2.92%   |
| Intel Ethernet Connection (6) I219-V                                          | 6         | 2.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 4         | 1.67%   |
| Intel Ethernet Connection (7) I219-V                                          | 4         | 1.67%   |
| Intel 82577LM Gigabit Network Connection                                      | 4         | 1.67%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 1.25%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 3         | 1.25%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3         | 1.25%   |
| Intel 82574L Gigabit Network Connection                                       | 3         | 1.25%   |
| Intel 82567LM Gigabit Network Connection                                      | 3         | 1.25%   |
| Huawei MAR-LX1A                                                               | 3         | 1.25%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 2         | 0.83%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 2         | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2         | 0.83%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 0.83%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                       | 2         | 0.83%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 2         | 0.83%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 0.83%   |
| Intel Ethernet Connection (4) I219-V                                          | 2         | 0.83%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2         | 0.83%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 0.83%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2         | 0.83%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2         | 0.83%   |
| Intel 82562GT 10/100 Network Connection                                       | 2         | 0.83%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 2         | 0.83%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 2         | 0.83%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                         | 2         | 0.83%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 1         | 0.42%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1         | 0.42%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1         | 0.42%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.42%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                             | 1         | 0.42%   |
| Linksys Gigabit Network Adapter                                               | 1         | 0.42%   |
| Lenovo ThinkPad TBT3 LAN                                                      | 1         | 0.42%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 1         | 0.42%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 0.42%   |
| Intel I210 Gigabit Network Connection                                         | 1         | 0.42%   |
| Intel Ethernet Connection I219-V                                              | 1         | 0.42%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.42%   |
| Intel Ethernet Connection I217-V                                              | 1         | 0.42%   |
| Intel Ethernet Connection (6) I219-LM                                         | 1         | 0.42%   |
| Intel Ethernet Connection (5) I219-LM                                         | 1         | 0.42%   |
| Intel Ethernet Connection (3) I218-V                                          | 1         | 0.42%   |
| Intel Ethernet Connection (14) I219-V                                         | 1         | 0.42%   |
| Intel Ethernet Connection (13) I219-V                                         | 1         | 0.42%   |
| Intel 82579V Gigabit Network Connection                                       | 1         | 0.42%   |
| Intel 82578DM Gigabit Network Connection                                      | 1         | 0.42%   |
| Intel 82576 Gigabit Network Connection                                        | 1         | 0.42%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.42%   |
| Intel 82566MM Gigabit Network Connection                                      | 1         | 0.42%   |
| Intel 82566DM Gigabit Network Connection                                      | 1         | 0.42%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                        | 1         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 223       | 55.75%  |
| WiFi     | 174       | 43.5%   |
| Modem    | 3         | 0.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 128       | 51.2%   |
| Ethernet | 122       | 48.8%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 140       | 55.78%  |
| 1     | 96        | 38.25%  |
| 0     | 10        | 3.98%   |
| 3     | 3         | 1.2%    |
| 5     | 1         | 0.4%    |
| 4     | 1         | 0.4%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 242       | 94.9%   |
| Yes  | 13        | 5.1%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 58        | 41.43%  |
| Realtek Semiconductor           | 12        | 8.57%   |
| Broadcom                        | 12        | 8.57%   |
| Qualcomm Atheros Communications | 11        | 7.86%   |
| IMC Networks                    | 11        | 7.86%   |
| Hewlett-Packard                 | 7         | 5%      |
| Cambridge Silicon Radio         | 7         | 5%      |
| ASUSTek Computer                | 6         | 4.29%   |
| Lite-On Technology              | 4         | 2.86%   |
| Apple                           | 3         | 2.14%   |
| Ralink                          | 2         | 1.43%   |
| Ralink Technology               | 1         | 0.71%   |
| Qcom                            | 1         | 0.71%   |
| Marvell Semiconductor           | 1         | 0.71%   |
| Integrated System Solution      | 1         | 0.71%   |
| Foxconn / Hon Hai               | 1         | 0.71%   |
| Edimax Technology               | 1         | 0.71%   |
| Chicony Electronics             | 1         | 0.71%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 21        | 15%     |
| Intel AX201 Bluetooth                               | 13        | 9.29%   |
| Intel AX200 Bluetooth                               | 11        | 7.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 5.71%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 5%      |
| Realtek Bluetooth Radio                             | 5         | 3.57%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 3.57%   |
| IMC Networks Bluetooth Radio                        | 5         | 3.57%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 2.86%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 2.86%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 4         | 2.86%   |
| IMC Networks Bluetooth Device                       | 3         | 2.14%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 2.14%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 1.43%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.43%   |
| Lite-On Bluetooth Device                            | 2         | 1.43%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.43%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 1.43%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.43%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 1.43%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.43%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 1.43%   |
| ASUS BT-270 Bluetooth Adapter                       | 2         | 1.43%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 1.43%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.71%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.71%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.71%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.71%   |
| Qcom Broadcom Bluetooth USB                         | 1         | 0.71%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 0.71%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.71%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.71%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.71%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.71%   |
| Intel AX210 Bluetooth                               | 1         | 0.71%   |
| Integrated System Solution Bluetooth Device         | 1         | 0.71%   |
| IMC Networks Bluetooth                              | 1         | 0.71%   |
| Foxconn / Hon Hai BT                                | 1         | 0.71%   |
| Edimax Bluetooth Device                             | 1         | 0.71%   |
| Chicony Bluetooth Radio                             | 1         | 0.71%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.71%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.71%   |
| Broadcom BCM20702A0                                 | 1         | 0.71%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 0.71%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1         | 0.71%   |
| ASUS Bluetooth Radio                                | 1         | 0.71%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.71%   |
| Apple Bluetooth USB Host Controller                 | 1         | 0.71%   |
| Apple Bluetooth HCI                                 | 1         | 0.71%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 191       | 56.01%  |
| AMD                              | 65        | 19.06%  |
| Nvidia                           | 58        | 17.01%  |
| Logitech                         | 4         | 1.17%   |
| JMTek                            | 3         | 0.88%   |
| C-Media Electronics              | 3         | 0.88%   |
| Texas Instruments                | 2         | 0.59%   |
| ASUSTek Computer                 | 2         | 0.59%   |
| Yamaha                           | 1         | 0.29%   |
| Textech International            | 1         | 0.29%   |
| Syntek                           | 1         | 0.29%   |
| Silicon Integrated Systems [SiS] | 1         | 0.29%   |
| Sennheiser Communications        | 1         | 0.29%   |
| Nam Tai E&E Products             | 1         | 0.29%   |
| Lenovo                           | 1         | 0.29%   |
| Kingston Technology              | 1         | 0.29%   |
| iCreate Technologies             | 1         | 0.29%   |
| Hewlett-Packard                  | 1         | 0.29%   |
| FiiO Electronics Technology      | 1         | 0.29%   |
| Creative Labs                    | 1         | 0.29%   |
| BEHRINGER International          | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 20        | 5.05%   |
| AMD Family 17h/19h HD Audio Controller                                            | 18        | 4.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 16        | 4.04%   |
| Intel Cannon Lake PCH cAVS                                                        | 13        | 3.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 13        | 3.28%   |
| Intel Sunrise Point-LP HD Audio                                                   | 12        | 3.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 11        | 2.78%   |
| Intel 200 Series PCH HD Audio                                                     | 11        | 2.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 10        | 2.53%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 9         | 2.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 9         | 2.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 9         | 2.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 8         | 2.02%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 7         | 1.77%   |
| Intel Haswell-ULT HD Audio Controller                                             | 7         | 1.77%   |
| Intel Broadwell-U Audio Controller                                                | 7         | 1.77%   |
| Intel 8 Series HD Audio Controller                                                | 7         | 1.77%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 7         | 1.77%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 7         | 1.77%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 6         | 1.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 6         | 1.52%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 6         | 1.52%   |
| AMD Starship/Matisse HD Audio Controller                                          | 6         | 1.52%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 6         | 1.52%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 6         | 1.52%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 6         | 1.52%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 6         | 1.52%   |
| Nvidia GP106 High Definition Audio Controller                                     | 5         | 1.26%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 5         | 1.26%   |
| AMD FCH Azalia Controller                                                         | 5         | 1.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 4         | 1.01%   |
| Nvidia GP104 High Definition Audio Controller                                     | 4         | 1.01%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 4         | 1.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 4         | 1.01%   |
| Nvidia GM206 High Definition Audio Controller                                     | 3         | 0.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3         | 0.76%   |
| Nvidia GK107 HDMI Audio Controller                                                | 3         | 0.76%   |
| Nvidia GF106 High Definition Audio Controller                                     | 3         | 0.76%   |
| Nvidia GA104 High Definition Audio Controller                                     | 3         | 0.76%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 3         | 0.76%   |
| Intel CM238 HD Audio Controller                                                   | 3         | 0.76%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 3         | 0.76%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 3         | 0.76%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3         | 0.76%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 3         | 0.76%   |
| Texas Instruments PCM2902 Audio Codec                                             | 2         | 0.51%   |
| Nvidia GP108 High Definition Audio Controller                                     | 2         | 0.51%   |
| Nvidia GP102 HDMI Audio Controller                                                | 2         | 0.51%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2         | 0.51%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2         | 0.51%   |
| Nvidia GK106 HDMI Audio Controller                                                | 2         | 0.51%   |
| Nvidia GK104 HDMI Audio Controller                                                | 2         | 0.51%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2         | 0.51%   |
| Logitech G430 Surround Sound Gaming Headset                                       | 2         | 0.51%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2         | 0.51%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 2         | 0.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 2         | 0.51%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2         | 0.51%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 2         | 0.51%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 33        | 21.02%  |
| Samsung Electronics | 29        | 18.47%  |
| Kingston            | 17        | 10.83%  |
| Micron Technology   | 16        | 10.19%  |
| Crucial             | 16        | 10.19%  |
| Unknown             | 11        | 7.01%   |
| G.Skill             | 8         | 5.1%    |
| Elpida              | 5         | 3.18%   |
| Nanya Technology    | 4         | 2.55%   |
| Corsair             | 4         | 2.55%   |
| Ramaxel Technology  | 3         | 1.91%   |
| A-DATA Technology   | 3         | 1.91%   |
| Team                | 2         | 1.27%   |
| TakeMS              | 2         | 1.27%   |
| Patriot             | 2         | 1.27%   |
| Transcend           | 1         | 0.64%   |
| Qimonda             | 1         | 0.64%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.78%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.78%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 1.18%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                  | 2         | 1.18%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.18%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 1.18%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 1.18%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.18%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 1.18%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.18%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 1.18%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s           | 2         | 1.18%   |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s             | 2         | 1.18%   |
| Crucial RAM CT16G4SFD8266.M16FJ 16GB SODIMM DDR4 2667MT/s        | 2         | 1.18%   |
| Unknown RAM Module 8GB Chip DDR4 2133MT/s                        | 1         | 0.59%   |
| Unknown RAM Module 4096MB DIMM DDR 1600MT/s                      | 1         | 0.59%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.59%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 1         | 0.59%   |
| Unknown RAM Module 2048MB SODIMM DRAM                            | 1         | 0.59%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.59%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                      | 1         | 0.59%   |
| Unknown RAM Module 2048MB Chip DDR3 1066MT/s                     | 1         | 0.59%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s            | 1         | 0.59%   |
| Transcend RAM JM800QLU-2G 2048MB DIMM DDR2 2048MT/s              | 1         | 0.59%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s               | 1         | 0.59%   |
| Team RAM TEAMGROUP-UD4-2666 8192MB DIMM DDR4 2667MT/s            | 1         | 0.59%   |
| TakeMS RAM TMS4GB364F081139EM 4096MB DIMM DDR3 1333MT/s          | 1         | 0.59%   |
| TakeMS RAM TMS4GB364E081139PP 4GB DIMM DDR3 1333MT/s             | 1         | 0.59%   |
| TakeMS RAM TMS2GB264D081805EV 2048MB DIMM DDR2 800MT/s           | 1         | 0.59%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 0.59%   |
| SK Hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 0.59%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.59%   |
| SK Hynix RAM Module 4096MB FB-DIMM DDR2 667MT/s                  | 1         | 0.59%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 1         | 0.59%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 1         | 0.59%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 0.59%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                 | 1         | 0.59%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2400MT/s                 | 1         | 0.59%   |
| SK Hynix RAM HYMP512S64CP8-Y5 1024MB SODIMM DDR 667MT/s          | 1         | 0.59%   |
| SK Hynix RAM HYMP325S64AMP8-Y5 2048MB SODIMM DDR 667MT/s         | 1         | 0.59%   |
| SK Hynix RAM HYMP112S64CP6-Y5 1024MB SODIMM DDR 667MT/s          | 1         | 0.59%   |
| SK Hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.59%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.59%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 0.59%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.59%   |
| SK Hynix RAM HMT125U6BFR8C-H9 2GB DIMM 1333MT/s                  | 1         | 0.59%   |
| SK Hynix RAM HMT112S6BFR6C-H9 1GB SODIMM DDR3 1333MT/s           | 1         | 0.59%   |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 1         | 0.59%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.59%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s       | 1         | 0.59%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.59%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.59%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.59%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.59%   |
| SK Hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 0.59%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 0.59%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2400MT/s                   | 1         | 0.59%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.59%   |
| Samsung RAM Module 4096MB DIMM DDR4 2400MT/s                     | 1         | 0.59%   |
| Samsung RAM Module 16GB SODIMM DDR4 2133MT/s                     | 1         | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 66        | 48.53%  |
| DDR3    | 43        | 31.62%  |
| DDR2    | 12        | 8.82%   |
| SDRAM   | 6         | 4.41%   |
| LPDDR3  | 4         | 2.94%   |
| LPDDR4  | 2         | 1.47%   |
| DRAM    | 1         | 0.74%   |
| DDR     | 1         | 0.74%   |
| Unknown | 1         | 0.74%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 77        | 57.04%  |
| DIMM         | 48        | 35.56%  |
| Row Of Chips | 7         | 5.19%   |
| Chip         | 2         | 1.48%   |
| FB-DIMM      | 1         | 0.74%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 48        | 34.53%  |
| 4096  | 37        | 26.62%  |
| 16384 | 26        | 18.71%  |
| 2048  | 19        | 13.67%  |
| 1024  | 6         | 4.32%   |
| 32768 | 3         | 2.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 27        | 18.49%  |
| 2667    | 26        | 17.81%  |
| 3200    | 13        | 8.9%    |
| 2400    | 13        | 8.9%    |
| 2133    | 9         | 6.16%   |
| 1333    | 8         | 5.48%   |
| 1334    | 7         | 4.79%   |
| 667     | 7         | 4.79%   |
| 3600    | 4         | 2.74%   |
| 800     | 4         | 2.74%   |
| 1867    | 3         | 2.05%   |
| Unknown | 3         | 2.05%   |
| 4267    | 2         | 1.37%   |
| 4199    | 2         | 1.37%   |
| 3800    | 2         | 1.37%   |
| 3466    | 2         | 1.37%   |
| 3000    | 2         | 1.37%   |
| 2048    | 2         | 1.37%   |
| 1067    | 2         | 1.37%   |
| 49926   | 1         | 0.68%   |
| 3733    | 1         | 0.68%   |
| 3266    | 1         | 0.68%   |
| 2866    | 1         | 0.68%   |
| 1800    | 1         | 0.68%   |
| 1639    | 1         | 0.68%   |
| 1066    | 1         | 0.68%   |
| 975     | 1         | 0.68%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 42.86%  |
| Xerox               | 2         | 28.57%  |
| Samsung Electronics | 1         | 14.29%  |
| Canon               | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Xerox Phaser 3140 and 3155         | 1         | 14.29%  |
| Xerox Phaser 3010                  | 1         | 14.29%  |
| Samsung M2070 Series               | 1         | 14.29%  |
| HP DeskJet F4200 series            | 1         | 14.29%  |
| HP DeskJet 2620 All-in-One Printer | 1         | 14.29%  |
| HP Color LaserJet 2605dn           | 1         | 14.29%  |
| Canon PIXMA MP250                  | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 33.33%  |
| Canon CanoScan LiDE 700F           | 1         | 33.33%  |
| Canon CanoScan LiDE 220            | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 43        | 31.85%  |
| IMC Networks                           | 13        | 9.63%   |
| Quanta                                 | 9         | 6.67%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 6.67%   |
| Realtek Semiconductor                  | 8         | 5.93%   |
| Logitech                               | 8         | 5.93%   |
| Sunplus Innovation Technology          | 7         | 5.19%   |
| Microdia                               | 7         | 5.19%   |
| Acer                                   | 6         | 4.44%   |
| Lite-On Technology                     | 5         | 3.7%    |
| Apple                                  | 4         | 2.96%   |
| Lenovo                                 | 3         | 2.22%   |
| Suyin                                  | 2         | 1.48%   |
| Samsung Electronics                    | 2         | 1.48%   |
| Primax Electronics                     | 2         | 1.48%   |
| Generalplus Technology                 | 2         | 1.48%   |
| Z-Star Microelectronics                | 1         | 0.74%   |
| Syntek                                 | 1         | 0.74%   |
| Ricoh                                  | 1         | 0.74%   |
| Pixart Imaging                         | 1         | 0.74%   |
| Cubeternet                             | 1         | 0.74%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                        | 9         | 6.57%   |
| Microdia Integrated_Webcam_HD                                    | 7         | 5.11%   |
| IMC Networks Integrated Camera                                   | 5         | 3.65%   |
| Acer Integrated Camera                                           | 4         | 2.92%   |
| Lite-On HP HD Camera                                             | 3         | 2.19%   |
| IMC Networks USB2.0 HD UVC WebCam                                | 3         | 2.19%   |
| Chicony USB2.0 HD UVC WebCam                                     | 3         | 2.19%   |
| Chicony HP HD Webcam                                             | 3         | 2.19%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                 | 3         | 2.19%   |
| Sunplus HP HD Webcam [Fixed]                                     | 2         | 1.46%   |
| Sunplus HD WebCam                                                | 2         | 1.46%   |
| Samsung Galaxy A5 (MTP)                                          | 2         | 1.46%   |
| Realtek Integrated_Webcam_HD                                     | 2         | 1.46%   |
| Realtek Asus laptop camera                                       | 2         | 1.46%   |
| Quanta HP Webcam                                                 | 2         | 1.46%   |
| Quanta HP TrueVision HD Camera                                   | 2         | 1.46%   |
| Quanta HP HD Camera                                              | 2         | 1.46%   |
| Primax HP HD Webcam [Fixed]                                      | 2         | 1.46%   |
| Logitech Webcam C310                                             | 2         | 1.46%   |
| Lenovo Integrated Webcam [R5U877]                                | 2         | 1.46%   |
| IMC Networks Integrated Webcam                                   | 2         | 1.46%   |
| Generalplus CAMERA - UVC                                         | 2         | 1.46%   |
| Chicony USB2.0 VGA UVC WebCam                                    | 2         | 1.46%   |
| Chicony Lenovo EasyCamera                                        | 2         | 1.46%   |
| Chicony Integrated Camera [ThinkPad]                             | 2         | 1.46%   |
| Chicony Integrated Camera (1280x720@30)                          | 2         | 1.46%   |
| Chicony HP Wide Vision HD Camera                                 | 2         | 1.46%   |
| Chicony HP Webcam                                                | 2         | 1.46%   |
| Chicony CNF7042                                                  | 2         | 1.46%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision FHD Camera | 2         | 1.46%   |
| Apple FaceTime HD Camera (Built-in)                              | 2         | 1.46%   |
| Z-Star Venus USB2.0 Camera                                       | 1         | 0.73%   |
| Syntek Lenovo EasyCamera                                         | 1         | 0.73%   |
| Suyin HP Truevision HD                                           | 1         | 0.73%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)      | 1         | 0.73%   |
| Sunplus Integrated Camera                                        | 1         | 0.73%   |
| Sunplus HP Universal Camera                                      | 1         | 0.73%   |
| Sunplus HP 2.0MP High Definition Webcam                          | 1         | 0.73%   |
| Ricoh Integrated Webcam                                          | 1         | 0.73%   |
| Realtek USB2.0-Camera                                            | 1         | 0.73%   |
| Realtek USB Camera                                               | 1         | 0.73%   |
| Realtek Integrated Webcam                                        | 1         | 0.73%   |
| Realtek Integrated Camera                                        | 1         | 0.73%   |
| Quanta VGA WebCam                                                | 1         | 0.73%   |
| Quanta HP TrueVision HD Webcam                                   | 1         | 0.73%   |
| Quanta HD Webcam                                                 | 1         | 0.73%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                             | 1         | 0.73%   |
| Logitech Webcam C210                                             | 1         | 0.73%   |
| Logitech Webcam C170                                             | 1         | 0.73%   |
| Logitech HD Webcam C910                                          | 1         | 0.73%   |
| Logitech HD Pro Webcam C920                                      | 1         | 0.73%   |
| Logitech BRIO Ultra HD Webcam                                    | 1         | 0.73%   |
| Logitech BRIO 4K Stream Edition                                  | 1         | 0.73%   |
| Lite-On Integrated Camera                                        | 1         | 0.73%   |
| Lite-On HP HD Webcam                                             | 1         | 0.73%   |
| Lenovo UVC Camera                                                | 1         | 0.73%   |
| IMC Networks USB2.0 VGA Webcam                                   | 1         | 0.73%   |
| IMC Networks USB2.0 VGA UVC WebCam                               | 1         | 0.73%   |
| IMC Networks EasyCamera                                          | 1         | 0.73%   |
| Cubeternet GL-UPC822 UVC WebCam                                  | 1         | 0.73%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 14        | 35.9%   |
| Validity Sensors           | 13        | 33.33%  |
| AuthenTec                  | 4         | 10.26%  |
| Upek                       | 3         | 7.69%   |
| Shenzhen Goodix Technology | 3         | 7.69%   |
| STMicroelectronics         | 1         | 2.56%   |
| Elan Microelectronics      | 1         | 2.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 6         | 15.38%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 5         | 12.82%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 3         | 7.69%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 7.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 7.69%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 5.13%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 2         | 5.13%   |
| Shenzhen Goodix  FingerPrint Device                        | 2         | 5.13%   |
| AuthenTec AES2810                                          | 2         | 5.13%   |
| Unknown                                                    | 2         | 5.13%   |
| Validity Sensors VFS491                                    | 1         | 2.56%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.56%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 2.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 2.56%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 2.56%   |
| Shenzhen Goodix FingerPrint                                | 1         | 2.56%   |
| Elan ELAN:ARM-M4                                           | 1         | 2.56%   |
| AuthenTec AES2550 Fingerprint Sensor                       | 1         | 2.56%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 2.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Alcor Micro      | 7         | 53.85%  |
| Broadcom         | 3         | 23.08%  |
| Upek             | 1         | 7.69%   |
| SCM Microsystems | 1         | 7.69%   |
| O2 Micro         | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 7         | 53.85%  |
| Broadcom 58200                                             | 2         | 15.38%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 7.69%   |
| SCM Microsystems uTrust 3512 SAM slot Token                | 1         | 7.69%   |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 171       | 68.13%  |
| 1     | 60        | 23.9%   |
| 2     | 19        | 7.57%   |
| 3     | 1         | 0.4%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 39        | 39.39%  |
| Graphics card            | 19        | 19.19%  |
| Chipcard                 | 13        | 13.13%  |
| Multimedia controller    | 8         | 8.08%   |
| Net/wireless             | 7         | 7.07%   |
| Communication controller | 4         | 4.04%   |
| Bluetooth                | 3         | 3.03%   |
| Storage                  | 2         | 2.02%   |
| Net/ethernet             | 1         | 1.01%   |
| Dvb card                 | 1         | 1.01%   |
| Card reader              | 1         | 1.01%   |
| Camera                   | 1         | 1.01%   |

