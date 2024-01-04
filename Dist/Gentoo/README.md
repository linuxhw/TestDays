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

Total: 3161

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [8250c46efe](https://linux-hardware.org/?probe=8250c46efe) | Jan 02, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [57cd074cfd](https://linux-hardware.org/?probe=57cd074cfd) | Jan 02, 2024 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [ee3998d501](https://linux-hardware.org/?probe=ee3998d501) | Jan 02, 2024 |
| Acer          | Aspire A517-52G             | Notebook    | [fb86c6f71c](https://linux-hardware.org/?probe=fb86c6f71c) | Jan 01, 2024 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [6826d7c88d](https://linux-hardware.org/?probe=6826d7c88d) | Jan 01, 2024 |
| Dell          | Latitude D630               | Notebook    | [bbae93d767](https://linux-hardware.org/?probe=bbae93d767) | Dec 31, 2023 |
| MSI           | Stealth 16Studio A13VF      | Notebook    | [04acb5230d](https://linux-hardware.org/?probe=04acb5230d) | Dec 30, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [0e7bbb6dea](https://linux-hardware.org/?probe=0e7bbb6dea) | Dec 30, 2023 |
| MSI           | Stealth 16Studio A13VF      | Notebook    | [1fd1d2e727](https://linux-hardware.org/?probe=1fd1d2e727) | Dec 30, 2023 |
| Dell          | Precision 5560              | Notebook    | [3555a4c2fa](https://linux-hardware.org/?probe=3555a4c2fa) | Dec 29, 2023 |
| Gigabyte      | X79-UP4                     | Desktop     | [618dfee965](https://linux-hardware.org/?probe=618dfee965) | Dec 29, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [2b867b6af5](https://linux-hardware.org/?probe=2b867b6af5) | Dec 28, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [619ddf5210](https://linux-hardware.org/?probe=619ddf5210) | Dec 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [983d2046a3](https://linux-hardware.org/?probe=983d2046a3) | Dec 27, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [3d96eb6f36](https://linux-hardware.org/?probe=3d96eb6f36) | Dec 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [d1cd9acaf0](https://linux-hardware.org/?probe=d1cd9acaf0) | Dec 26, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [af7c011930](https://linux-hardware.org/?probe=af7c011930) | Dec 25, 2023 |
| ASUSTek       | D500MD                      | Desktop     | [21870febdd](https://linux-hardware.org/?probe=21870febdd) | Dec 25, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [47255f4ba3](https://linux-hardware.org/?probe=47255f4ba3) | Dec 25, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [2394204218](https://linux-hardware.org/?probe=2394204218) | Dec 24, 2023 |
| TULPAR        | A5 V20.3                    | Notebook    | [c1abfa26d5](https://linux-hardware.org/?probe=c1abfa26d5) | Dec 24, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [646b9af5a9](https://linux-hardware.org/?probe=646b9af5a9) | Dec 24, 2023 |
| MSI           | MPG B650 EDGE WIFI          | Desktop     | [8503d79f6c](https://linux-hardware.org/?probe=8503d79f6c) | Dec 24, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [6b0368fd61](https://linux-hardware.org/?probe=6b0368fd61) | Dec 23, 2023 |
| TULPAR        | A5 V20.3                    | Notebook    | [83c6679958](https://linux-hardware.org/?probe=83c6679958) | Dec 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [391ef34135](https://linux-hardware.org/?probe=391ef34135) | Dec 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [87b9f04878](https://linux-hardware.org/?probe=87b9f04878) | Dec 23, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [c6caf2cc7a](https://linux-hardware.org/?probe=c6caf2cc7a) | Dec 22, 2023 |
| Dell          | Precision 5480              | Notebook    | [7cc190b5c0](https://linux-hardware.org/?probe=7cc190b5c0) | Dec 22, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [f65d61f128](https://linux-hardware.org/?probe=f65d61f128) | Dec 20, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b14bdf4602](https://linux-hardware.org/?probe=b14bdf4602) | Dec 20, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [37ee5a4acd](https://linux-hardware.org/?probe=37ee5a4acd) | Dec 19, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [89fd7ee431](https://linux-hardware.org/?probe=89fd7ee431) | Dec 18, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [3504b628f1](https://linux-hardware.org/?probe=3504b628f1) | Dec 18, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [877c79184e](https://linux-hardware.org/?probe=877c79184e) | Dec 18, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [e0b7c61c9f](https://linux-hardware.org/?probe=e0b7c61c9f) | Dec 18, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [25525c17e0](https://linux-hardware.org/?probe=25525c17e0) | Dec 17, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [c01e13535f](https://linux-hardware.org/?probe=c01e13535f) | Dec 17, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [402a34ec30](https://linux-hardware.org/?probe=402a34ec30) | Dec 17, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [776cc9f3bb](https://linux-hardware.org/?probe=776cc9f3bb) | Dec 17, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [f02dc20ac0](https://linux-hardware.org/?probe=f02dc20ac0) | Dec 16, 2023 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | Notebook    | [8e419e7090](https://linux-hardware.org/?probe=8e419e7090) | Dec 16, 2023 |
| HP            | 8592                        | Desktop     | [511feb6066](https://linux-hardware.org/?probe=511feb6066) | Dec 15, 2023 |
| HP            | 8592                        | Desktop     | [c5817452fd](https://linux-hardware.org/?probe=c5817452fd) | Dec 15, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [ba4e95a15e](https://linux-hardware.org/?probe=ba4e95a15e) | Dec 13, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [5eaaa9dcdc](https://linux-hardware.org/?probe=5eaaa9dcdc) | Dec 13, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [8524c9dcd5](https://linux-hardware.org/?probe=8524c9dcd5) | Dec 13, 2023 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | Notebook    | [042bbde845](https://linux-hardware.org/?probe=042bbde845) | Dec 13, 2023 |
| Dell          | 02C2CP A03                  | Server      | [3a651d8f80](https://linux-hardware.org/?probe=3a651d8f80) | Dec 13, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [9b92833e92](https://linux-hardware.org/?probe=9b92833e92) | Dec 12, 2023 |
| Foxconn       | TPS01                       | Desktop     | [a417ff19ae](https://linux-hardware.org/?probe=a417ff19ae) | Dec 12, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [e07d68d658](https://linux-hardware.org/?probe=e07d68d658) | Dec 11, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [8bf4107eed](https://linux-hardware.org/?probe=8bf4107eed) | Dec 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [4c6cd4453d](https://linux-hardware.org/?probe=4c6cd4453d) | Dec 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b87d7c1c10](https://linux-hardware.org/?probe=b87d7c1c10) | Dec 10, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [ba355033b7](https://linux-hardware.org/?probe=ba355033b7) | Dec 08, 2023 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [7e738d8259](https://linux-hardware.org/?probe=7e738d8259) | Dec 08, 2023 |
| Dell          | XPS 9320                    | Notebook    | [60c734eb9c](https://linux-hardware.org/?probe=60c734eb9c) | Dec 08, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [d57960be0a](https://linux-hardware.org/?probe=d57960be0a) | Dec 05, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [1fe1dc7462](https://linux-hardware.org/?probe=1fe1dc7462) | Dec 04, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [675f997c0b](https://linux-hardware.org/?probe=675f997c0b) | Dec 03, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [358a92be0d](https://linux-hardware.org/?probe=358a92be0d) | Dec 03, 2023 |
| BANGHO        | MAX L4                      | Notebook    | [d1306fe54f](https://linux-hardware.org/?probe=d1306fe54f) | Dec 03, 2023 |
| BANGHO        | MAX L4                      | Notebook    | [a0f107fc92](https://linux-hardware.org/?probe=a0f107fc92) | Dec 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [426263e458](https://linux-hardware.org/?probe=426263e458) | Dec 03, 2023 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [3f49a16307](https://linux-hardware.org/?probe=3f49a16307) | Dec 02, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [7f49fad2c7](https://linux-hardware.org/?probe=7f49fad2c7) | Dec 02, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [fc87fb1112](https://linux-hardware.org/?probe=fc87fb1112) | Dec 01, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [d95358436c](https://linux-hardware.org/?probe=d95358436c) | Nov 30, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [f9175866ae](https://linux-hardware.org/?probe=f9175866ae) | Nov 30, 2023 |
| Unknown       | Unknown                     | Soc         | [ab9297851b](https://linux-hardware.org/?probe=ab9297851b) | Nov 30, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FBA... | Convertible | [720eead0a5](https://linux-hardware.org/?probe=720eead0a5) | Nov 29, 2023 |
| Unknown       | Unknown                     | Soc         | [7acffa679c](https://linux-hardware.org/?probe=7acffa679c) | Nov 29, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | Desktop     | [f16bc78368](https://linux-hardware.org/?probe=f16bc78368) | Nov 29, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [d4c90a615f](https://linux-hardware.org/?probe=d4c90a615f) | Nov 29, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | Desktop     | [879c59cf41](https://linux-hardware.org/?probe=879c59cf41) | Nov 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [b6ebeab524](https://linux-hardware.org/?probe=b6ebeab524) | Nov 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [2b2bb98701](https://linux-hardware.org/?probe=2b2bb98701) | Nov 29, 2023 |
| Dell          | Latitude E6540              | Notebook    | [ae3c1282c2](https://linux-hardware.org/?probe=ae3c1282c2) | Nov 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [d7d0f11ab2](https://linux-hardware.org/?probe=d7d0f11ab2) | Nov 28, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [f5949df300](https://linux-hardware.org/?probe=f5949df300) | Nov 28, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [1d71979dbb](https://linux-hardware.org/?probe=1d71979dbb) | Nov 27, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [ee929504ae](https://linux-hardware.org/?probe=ee929504ae) | Nov 27, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [68644f2689](https://linux-hardware.org/?probe=68644f2689) | Nov 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [9d3e14a9ba](https://linux-hardware.org/?probe=9d3e14a9ba) | Nov 27, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [83d5ded7d9](https://linux-hardware.org/?probe=83d5ded7d9) | Nov 27, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [8ef4fb91ac](https://linux-hardware.org/?probe=8ef4fb91ac) | Nov 27, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [6fcbd9b64c](https://linux-hardware.org/?probe=6fcbd9b64c) | Nov 27, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [2a04ec7adc](https://linux-hardware.org/?probe=2a04ec7adc) | Nov 27, 2023 |
| Supermicro    | X8DT3                       | Server      | [93de2051e2](https://linux-hardware.org/?probe=93de2051e2) | Nov 27, 2023 |
| Dell          | Latitude D630               | Notebook    | [51af6a8f00](https://linux-hardware.org/?probe=51af6a8f00) | Nov 26, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [26b99168f7](https://linux-hardware.org/?probe=26b99168f7) | Nov 26, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [320763e400](https://linux-hardware.org/?probe=320763e400) | Nov 25, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [9e8f9907bb](https://linux-hardware.org/?probe=9e8f9907bb) | Nov 24, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [fde8cf07ef](https://linux-hardware.org/?probe=fde8cf07ef) | Nov 24, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [c397c51bfb](https://linux-hardware.org/?probe=c397c51bfb) | Nov 24, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [b305b3da28](https://linux-hardware.org/?probe=b305b3da28) | Nov 22, 2023 |
| Acer          | Aspire A315-34              | Notebook    | [336fe65e03](https://linux-hardware.org/?probe=336fe65e03) | Nov 22, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4eae08c59f](https://linux-hardware.org/?probe=4eae08c59f) | Nov 22, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [2305a057a8](https://linux-hardware.org/?probe=2305a057a8) | Nov 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [360ad65af8](https://linux-hardware.org/?probe=360ad65af8) | Nov 21, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [8d33a8020d](https://linux-hardware.org/?probe=8d33a8020d) | Nov 20, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [ac6d14ae8d](https://linux-hardware.org/?probe=ac6d14ae8d) | Nov 20, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [3a8da808e0](https://linux-hardware.org/?probe=3a8da808e0) | Nov 20, 2023 |
| HP            | ProLiant DL380e Gen8        | Server      | [221dcda3ae](https://linux-hardware.org/?probe=221dcda3ae) | Nov 19, 2023 |
| UMAX          | VisionBook 9Wi Pro          | Tablet      | [816a26352f](https://linux-hardware.org/?probe=816a26352f) | Nov 19, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [fc7f2d74b8](https://linux-hardware.org/?probe=fc7f2d74b8) | Nov 19, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [d46bf1bcb4](https://linux-hardware.org/?probe=d46bf1bcb4) | Nov 18, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CMC... | Notebook    | [e25caef1f8](https://linux-hardware.org/?probe=e25caef1f8) | Nov 18, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [85f5d912da](https://linux-hardware.org/?probe=85f5d912da) | Nov 18, 2023 |
| Dell          | Latitude D630               | Notebook    | [54e404f085](https://linux-hardware.org/?probe=54e404f085) | Nov 18, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [a868498279](https://linux-hardware.org/?probe=a868498279) | Nov 18, 2023 |
| Dell          | Precision 5480              | Notebook    | [ee10103325](https://linux-hardware.org/?probe=ee10103325) | Nov 18, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [477c710fe1](https://linux-hardware.org/?probe=477c710fe1) | Nov 15, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [c26f7106c6](https://linux-hardware.org/?probe=c26f7106c6) | Nov 15, 2023 |
| Gigabyte      | Z590 UD                     | Desktop     | [76092ba872](https://linux-hardware.org/?probe=76092ba872) | Nov 15, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [6a5b4cf051](https://linux-hardware.org/?probe=6a5b4cf051) | Nov 15, 2023 |
| ASUSTek       | P10S-I Series               | Desktop     | [f27cfbe5ca](https://linux-hardware.org/?probe=f27cfbe5ca) | Nov 15, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [1105d135a2](https://linux-hardware.org/?probe=1105d135a2) | Nov 14, 2023 |
| Acer          | Aspire A315-34              | Notebook    | [8179414a49](https://linux-hardware.org/?probe=8179414a49) | Nov 14, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [8080101e6f](https://linux-hardware.org/?probe=8080101e6f) | Nov 13, 2023 |
| Dell          | G5 5505                     | Notebook    | [be553804bd](https://linux-hardware.org/?probe=be553804bd) | Nov 13, 2023 |
| ASUSTek       | ROG G703GI_G7BI             | Notebook    | [f1e3e6eb2c](https://linux-hardware.org/?probe=f1e3e6eb2c) | Nov 13, 2023 |
| Dell          | G5 5505                     | Notebook    | [574ccd4e6f](https://linux-hardware.org/?probe=574ccd4e6f) | Nov 13, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [de369665dc](https://linux-hardware.org/?probe=de369665dc) | Nov 13, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [9d2aeb3f90](https://linux-hardware.org/?probe=9d2aeb3f90) | Nov 13, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [ab65845e2f](https://linux-hardware.org/?probe=ab65845e2f) | Nov 12, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [51cd292a70](https://linux-hardware.org/?probe=51cd292a70) | Nov 12, 2023 |
| Medion        | B360H4-EM V1.0              | Desktop     | [3efb188b16](https://linux-hardware.org/?probe=3efb188b16) | Nov 12, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [8415697290](https://linux-hardware.org/?probe=8415697290) | Nov 12, 2023 |
| Lenovo        | ThinkPad T420 4236QE0       | Notebook    | [16d356b88c](https://linux-hardware.org/?probe=16d356b88c) | Nov 12, 2023 |
| Lenovo        | ThinkPad T420 4236QE0       | Notebook    | [bce581924a](https://linux-hardware.org/?probe=bce581924a) | Nov 12, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [6996973cde](https://linux-hardware.org/?probe=6996973cde) | Nov 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [4aae90aee9](https://linux-hardware.org/?probe=4aae90aee9) | Nov 11, 2023 |
| Dell          | Latitude D630               | Notebook    | [8af88f25f0](https://linux-hardware.org/?probe=8af88f25f0) | Nov 10, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [4b53c4e9da](https://linux-hardware.org/?probe=4b53c4e9da) | Nov 10, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [aa17167e95](https://linux-hardware.org/?probe=aa17167e95) | Nov 09, 2023 |
| Gigabyte      | Z590 UD                     | Desktop     | [4c763ba78a](https://linux-hardware.org/?probe=4c763ba78a) | Nov 09, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [379584ba47](https://linux-hardware.org/?probe=379584ba47) | Nov 08, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [1de1299edf](https://linux-hardware.org/?probe=1de1299edf) | Nov 08, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [7ecc25dda7](https://linux-hardware.org/?probe=7ecc25dda7) | Nov 08, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [715aee0ee7](https://linux-hardware.org/?probe=715aee0ee7) | Nov 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [c0f28da2b7](https://linux-hardware.org/?probe=c0f28da2b7) | Nov 07, 2023 |
| ASUSTek       | Z10PA-D8 Series             | Desktop     | [b865e2f52d](https://linux-hardware.org/?probe=b865e2f52d) | Nov 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [24cd0b58d3](https://linux-hardware.org/?probe=24cd0b58d3) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [503b6e943c](https://linux-hardware.org/?probe=503b6e943c) | Nov 06, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [d0570de821](https://linux-hardware.org/?probe=d0570de821) | Nov 06, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [29f3c0c25f](https://linux-hardware.org/?probe=29f3c0c25f) | Nov 06, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [4d3a7373ae](https://linux-hardware.org/?probe=4d3a7373ae) | Nov 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [ff44a3299b](https://linux-hardware.org/?probe=ff44a3299b) | Nov 06, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [cff5d02cde](https://linux-hardware.org/?probe=cff5d02cde) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [8e8cfaa103](https://linux-hardware.org/?probe=8e8cfaa103) | Nov 05, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [63e30986f6](https://linux-hardware.org/?probe=63e30986f6) | Nov 05, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [0ce0a4d87a](https://linux-hardware.org/?probe=0ce0a4d87a) | Nov 04, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0e493c7b85](https://linux-hardware.org/?probe=0e493c7b85) | Nov 03, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fc6336fedd](https://linux-hardware.org/?probe=fc6336fedd) | Nov 02, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [40deedc435](https://linux-hardware.org/?probe=40deedc435) | Oct 31, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [57d643d36b](https://linux-hardware.org/?probe=57d643d36b) | Oct 31, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [148857cc51](https://linux-hardware.org/?probe=148857cc51) | Oct 31, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [7b6fe38982](https://linux-hardware.org/?probe=7b6fe38982) | Oct 31, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [b553bb2a36](https://linux-hardware.org/?probe=b553bb2a36) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [0a990e1165](https://linux-hardware.org/?probe=0a990e1165) | Oct 31, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f6e8c279ef](https://linux-hardware.org/?probe=f6e8c279ef) | Oct 31, 2023 |
| Dell          | Latitude 7320               | Notebook    | [efc40122bf](https://linux-hardware.org/?probe=efc40122bf) | Oct 30, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [de3f77c938](https://linux-hardware.org/?probe=de3f77c938) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [af050c4fa2](https://linux-hardware.org/?probe=af050c4fa2) | Oct 29, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [b113709ec2](https://linux-hardware.org/?probe=b113709ec2) | Oct 29, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [bee59e348e](https://linux-hardware.org/?probe=bee59e348e) | Oct 28, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d0cea8f6bb](https://linux-hardware.org/?probe=d0cea8f6bb) | Oct 28, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [63b5c65c01](https://linux-hardware.org/?probe=63b5c65c01) | Oct 28, 2023 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | Notebook    | [5c169fe4ed](https://linux-hardware.org/?probe=5c169fe4ed) | Oct 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [54aa16ef1e](https://linux-hardware.org/?probe=54aa16ef1e) | Oct 27, 2023 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | Notebook    | [1c1d7bd2b1](https://linux-hardware.org/?probe=1c1d7bd2b1) | Oct 27, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [50b77f9f9e](https://linux-hardware.org/?probe=50b77f9f9e) | Oct 26, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [47e99a1356](https://linux-hardware.org/?probe=47e99a1356) | Oct 26, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [78bdbc6419](https://linux-hardware.org/?probe=78bdbc6419) | Oct 25, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [ba2a49fbef](https://linux-hardware.org/?probe=ba2a49fbef) | Oct 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [f4a0aca53d](https://linux-hardware.org/?probe=f4a0aca53d) | Oct 24, 2023 |
| HP            | 3397                        | Desktop     | [1344d9d38b](https://linux-hardware.org/?probe=1344d9d38b) | Oct 23, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [9a65857d3c](https://linux-hardware.org/?probe=9a65857d3c) | Oct 23, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [001c668695](https://linux-hardware.org/?probe=001c668695) | Oct 23, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [def0406ec0](https://linux-hardware.org/?probe=def0406ec0) | Oct 23, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [f2b15bc2f1](https://linux-hardware.org/?probe=f2b15bc2f1) | Oct 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [95d6dab241](https://linux-hardware.org/?probe=95d6dab241) | Oct 23, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [6ef12aa776](https://linux-hardware.org/?probe=6ef12aa776) | Oct 23, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [2a00efe761](https://linux-hardware.org/?probe=2a00efe761) | Oct 22, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [4b93c11bcb](https://linux-hardware.org/?probe=4b93c11bcb) | Oct 21, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [62ae73f967](https://linux-hardware.org/?probe=62ae73f967) | Oct 21, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e8d5f9186c](https://linux-hardware.org/?probe=e8d5f9186c) | Oct 20, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [b677f99638](https://linux-hardware.org/?probe=b677f99638) | Oct 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [3368da4a2b](https://linux-hardware.org/?probe=3368da4a2b) | Oct 19, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [911d7f21e7](https://linux-hardware.org/?probe=911d7f21e7) | Oct 18, 2023 |
| ASRock        | H170 Pro4S                  | Desktop     | [e3960f114d](https://linux-hardware.org/?probe=e3960f114d) | Oct 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [e794aa4113](https://linux-hardware.org/?probe=e794aa4113) | Oct 18, 2023 |
| Dell          | 0MNPJ9 A03                  | Desktop     | [36e7a1e261](https://linux-hardware.org/?probe=36e7a1e261) | Oct 18, 2023 |
| Gigabyte      | Z590 UD                     | Desktop     | [1e2597a152](https://linux-hardware.org/?probe=1e2597a152) | Oct 17, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [acd4052588](https://linux-hardware.org/?probe=acd4052588) | Oct 16, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [cc5a77d2c3](https://linux-hardware.org/?probe=cc5a77d2c3) | Oct 16, 2023 |
| Gigabyte      | Z590 UD                     | Desktop     | [65277f3f01](https://linux-hardware.org/?probe=65277f3f01) | Oct 16, 2023 |
| MSI           | MEG X570S ACE MAX           | Desktop     | [d3cf683bad](https://linux-hardware.org/?probe=d3cf683bad) | Oct 15, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [8be373f42f](https://linux-hardware.org/?probe=8be373f42f) | Oct 14, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [98ebe6766d](https://linux-hardware.org/?probe=98ebe6766d) | Oct 14, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [4f5f1c9eea](https://linux-hardware.org/?probe=4f5f1c9eea) | Oct 11, 2023 |
| PINE64        | Pinebook Pro                | Soc         | [e62b12571a](https://linux-hardware.org/?probe=e62b12571a) | Oct 09, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [f0f128becf](https://linux-hardware.org/?probe=f0f128becf) | Oct 09, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [212f394b32](https://linux-hardware.org/?probe=212f394b32) | Oct 09, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [078d4619a6](https://linux-hardware.org/?probe=078d4619a6) | Oct 09, 2023 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [af06968ae1](https://linux-hardware.org/?probe=af06968ae1) | Oct 08, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [586d5eef76](https://linux-hardware.org/?probe=586d5eef76) | Oct 08, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [6f6e394cdf](https://linux-hardware.org/?probe=6f6e394cdf) | Oct 05, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [c5d7f755ac](https://linux-hardware.org/?probe=c5d7f755ac) | Oct 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [da869ee2ba](https://linux-hardware.org/?probe=da869ee2ba) | Oct 04, 2023 |
| HP            | 1589                        | Desktop     | [75f8ba109d](https://linux-hardware.org/?probe=75f8ba109d) | Oct 04, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [27d781a357](https://linux-hardware.org/?probe=27d781a357) | Oct 04, 2023 |
| Dell          | 0NGT4D A01                  | Mini pc     | [457dfea13d](https://linux-hardware.org/?probe=457dfea13d) | Oct 03, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [e684c274a6](https://linux-hardware.org/?probe=e684c274a6) | Oct 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e705d58ab0](https://linux-hardware.org/?probe=e705d58ab0) | Oct 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [d5de51003e](https://linux-hardware.org/?probe=d5de51003e) | Oct 03, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [8fd9631bea](https://linux-hardware.org/?probe=8fd9631bea) | Oct 03, 2023 |
| Supermicro    | X10SL7-F                    | Server      | [5e6d01b044](https://linux-hardware.org/?probe=5e6d01b044) | Oct 03, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [ea10bf8eab](https://linux-hardware.org/?probe=ea10bf8eab) | Oct 02, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | Notebook    | [40f87e9874](https://linux-hardware.org/?probe=40f87e9874) | Oct 02, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [cbd8df2f8a](https://linux-hardware.org/?probe=cbd8df2f8a) | Oct 02, 2023 |
| Supermicro    | H12SSL-NT                   | Server      | [5018997f48](https://linux-hardware.org/?probe=5018997f48) | Oct 01, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [6fb4d2a754](https://linux-hardware.org/?probe=6fb4d2a754) | Oct 01, 2023 |
| ASUSTek       | PRIME X670-P                | Desktop     | [25c3794b84](https://linux-hardware.org/?probe=25c3794b84) | Oct 01, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [ff0e651b1b](https://linux-hardware.org/?probe=ff0e651b1b) | Oct 01, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [154150aa88](https://linux-hardware.org/?probe=154150aa88) | Sep 30, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [2a507c567b](https://linux-hardware.org/?probe=2a507c567b) | Sep 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [b6acaf4c61](https://linux-hardware.org/?probe=b6acaf4c61) | Sep 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4ef9eaaaba](https://linux-hardware.org/?probe=4ef9eaaaba) | Sep 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [f1623258a8](https://linux-hardware.org/?probe=f1623258a8) | Sep 27, 2023 |
| HP            | 1589                        | Desktop     | [1063a6e665](https://linux-hardware.org/?probe=1063a6e665) | Sep 27, 2023 |
| Supermicro    | X10SDE-DF                   | Desktop     | [c2ba80af3b](https://linux-hardware.org/?probe=c2ba80af3b) | Sep 26, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [a85d516a80](https://linux-hardware.org/?probe=a85d516a80) | Sep 25, 2023 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [6dca52cc54](https://linux-hardware.org/?probe=6dca52cc54) | Sep 25, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [32a39c6a01](https://linux-hardware.org/?probe=32a39c6a01) | Sep 25, 2023 |
| Supermicro    | X10SDE-DF                   | Desktop     | [fb93d199f3](https://linux-hardware.org/?probe=fb93d199f3) | Sep 25, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [4c68092d28](https://linux-hardware.org/?probe=4c68092d28) | Sep 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [7d4c2dc8f6](https://linux-hardware.org/?probe=7d4c2dc8f6) | Sep 25, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [8a581a8a85](https://linux-hardware.org/?probe=8a581a8a85) | Sep 24, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [d17427680f](https://linux-hardware.org/?probe=d17427680f) | Sep 24, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [1c0c7815dd](https://linux-hardware.org/?probe=1c0c7815dd) | Sep 24, 2023 |
| Supermicro    | X10SDE-DF                   | Desktop     | [b0297cff82](https://linux-hardware.org/?probe=b0297cff82) | Sep 24, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [7732f1eb9b](https://linux-hardware.org/?probe=7732f1eb9b) | Sep 22, 2023 |
| Dell          | 0RY206                      | Desktop     | [11a31518a3](https://linux-hardware.org/?probe=11a31518a3) | Sep 20, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0748266b0a](https://linux-hardware.org/?probe=0748266b0a) | Sep 19, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [e1b56bb588](https://linux-hardware.org/?probe=e1b56bb588) | Sep 19, 2023 |
| ASRock        | B85M                        | Desktop     | [8a3dc73931](https://linux-hardware.org/?probe=8a3dc73931) | Sep 18, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [8dcd49002d](https://linux-hardware.org/?probe=8dcd49002d) | Sep 18, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [5680b32e39](https://linux-hardware.org/?probe=5680b32e39) | Sep 18, 2023 |
| Lenovo        | ThinkPad P43s 20RHCTO1WW    | Notebook    | [4b1c4ae225](https://linux-hardware.org/?probe=4b1c4ae225) | Sep 18, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [524eb9d966](https://linux-hardware.org/?probe=524eb9d966) | Sep 17, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [2f86649b91](https://linux-hardware.org/?probe=2f86649b91) | Sep 17, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [3306655fb2](https://linux-hardware.org/?probe=3306655fb2) | Sep 17, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [75a8af42cd](https://linux-hardware.org/?probe=75a8af42cd) | Sep 17, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [cd5cabf48f](https://linux-hardware.org/?probe=cd5cabf48f) | Sep 16, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [7cd5acacf7](https://linux-hardware.org/?probe=7cd5acacf7) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [d23a7d46f3](https://linux-hardware.org/?probe=d23a7d46f3) | Sep 15, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [ec5b4aeb84](https://linux-hardware.org/?probe=ec5b4aeb84) | Sep 15, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [077f5b81b8](https://linux-hardware.org/?probe=077f5b81b8) | Sep 14, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [e38a2e668b](https://linux-hardware.org/?probe=e38a2e668b) | Sep 12, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [de7acf45a6](https://linux-hardware.org/?probe=de7acf45a6) | Sep 12, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [12f4431262](https://linux-hardware.org/?probe=12f4431262) | Sep 12, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | Desktop     | [0dabf67d5f](https://linux-hardware.org/?probe=0dabf67d5f) | Sep 11, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [f24f476710](https://linux-hardware.org/?probe=f24f476710) | Sep 11, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [77105eb7da](https://linux-hardware.org/?probe=77105eb7da) | Sep 11, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [5ac44fe5ec](https://linux-hardware.org/?probe=5ac44fe5ec) | Sep 11, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [a25f4b1c5c](https://linux-hardware.org/?probe=a25f4b1c5c) | Sep 11, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [830ca674bb](https://linux-hardware.org/?probe=830ca674bb) | Sep 10, 2023 |
| ASUSTek       | PRIME N100I-D D4            | Desktop     | [ce24c28731](https://linux-hardware.org/?probe=ce24c28731) | Sep 10, 2023 |
| Dell          | Precision M4800             | Notebook    | [ea570fedac](https://linux-hardware.org/?probe=ea570fedac) | Sep 09, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | Desktop     | [87971ac772](https://linux-hardware.org/?probe=87971ac772) | Sep 09, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [dffd28975a](https://linux-hardware.org/?probe=dffd28975a) | Sep 09, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [8f6631088b](https://linux-hardware.org/?probe=8f6631088b) | Sep 08, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [a6bbf0ac50](https://linux-hardware.org/?probe=a6bbf0ac50) | Sep 08, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [7be90edf82](https://linux-hardware.org/?probe=7be90edf82) | Sep 08, 2023 |
| HP            | 1589                        | Desktop     | [550b95765c](https://linux-hardware.org/?probe=550b95765c) | Sep 06, 2023 |
| System76      | Pangolin                    | Notebook    | [43dbf49440](https://linux-hardware.org/?probe=43dbf49440) | Sep 06, 2023 |
| System76      | Pangolin                    | Notebook    | [461b8d48ba](https://linux-hardware.org/?probe=461b8d48ba) | Sep 05, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | Desktop     | [48e1f16931](https://linux-hardware.org/?probe=48e1f16931) | Sep 05, 2023 |
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
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | Desktop     | [a99a5ccc55](https://linux-hardware.org/?probe=a99a5ccc55) | Aug 30, 2023 |
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
| Gentoo 2.7     | 556       | 28.91%  |
| Gentoo 2.6     | 413       | 21.48%  |
| Gentoo 2.8     | 306       | 15.91%  |
| Gentoo 2.13    | 240       | 12.48%  |
| Gentoo 2.14    | 193       | 10.04%  |
| Gentoo 2.9     | 160       | 8.32%   |
| Gentoo 2.4.1   | 14        | 0.73%   |
| Gentoo         | 11        | 0.57%   |
| Gentoo 2.3     | 9         | 0.47%   |
| Gentoo 2.2     | 7         | 0.36%   |
| Gentoo 23      | 3         | 0.16%   |
| Gentoo 1       | 3         | 0.16%   |
| Gentoo 22.0.1  | 2         | 0.1%    |
| Gentoo Pelikan | 1         | 0.05%   |
| Gentoo 22      | 1         | 0.05%   |
| Gentoo 2022    | 1         | 0.05%   |
| Gentoo 20.04   | 1         | 0.05%   |
| Gentoo 2.1     | 1         | 0.05%   |
| Gentoo 13.0    | 1         | 0.05%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Gentoo | 1653      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.38-gentoo            | 26        | 1.16%   |
| 5.10.27-gentoo           | 25        | 1.11%   |
| 5.10.61-gentoo           | 23        | 1.02%   |
| 5.15.32-gentoo-r1        | 18        | 0.8%    |
| 6.1.57-gentoo            | 16        | 0.71%   |
| 6.1.12-gentoo            | 16        | 0.71%   |
| 5.15.80-gentoo-x86_64    | 16        | 0.71%   |
| 5.15.80-gentoo           | 16        | 0.71%   |
| 6.1.19-gentoo-x86_64     | 15        | 0.67%   |
| 5.4.80-gentoo-r1         | 15        | 0.67%   |
| 5.4.48-gentoo            | 15        | 0.67%   |
| 6.1.19-gentoo            | 14        | 0.62%   |
| 5.4.97-gentoo            | 14        | 0.62%   |
| 5.4.28-gentoo            | 14        | 0.62%   |
| 5.10.76-gentoo-r1        | 14        | 0.62%   |
| 6.1.57-gentoo-x86_64     | 13        | 0.58%   |
| 5.15.75-gentoo-x86_64    | 13        | 0.58%   |
| 5.10.61-gentoo-x86_64    | 13        | 0.58%   |
| 5.10.27-gentoo-x86_64    | 13        | 0.58%   |
| 5.15.59-gentoo-x86_64    | 12        | 0.53%   |
| 5.15.32-gentoo-r1-x86_64 | 12        | 0.53%   |
| 5.10.52-gentoo           | 12        | 0.53%   |
| 5.7.0-gentoo             | 11        | 0.49%   |
| 5.4.60-gentoo            | 11        | 0.49%   |
| 5.15.88-gentoo           | 11        | 0.49%   |
| 6.1.53-gentoo-r1         | 10        | 0.44%   |
| 5.4.38-gentoo-x86_64     | 10        | 0.44%   |
| 6.1.41-gentoo-dist       | 9         | 0.4%    |
| 6.1.31-gentoo-dist       | 9         | 0.4%    |
| 6.1.12-gentoo-x86_64     | 9         | 0.4%    |
| 5.15.75-gentoo           | 9         | 0.4%    |
| 5.15.59-gentoo           | 9         | 0.4%    |
| 5.15.52-gentoo-x86_64    | 9         | 0.4%    |
| 5.15.52-gentoo           | 9         | 0.4%    |
| 5.15.41-gentoo-x86_64    | 9         | 0.4%    |
| 5.10.76-gentoo-r1-x86_64 | 9         | 0.4%    |
| 6.1.46-gentoo            | 8         | 0.36%   |
| 6.1.41-gentoo            | 8         | 0.36%   |
| 5.6.15-gentoo            | 8         | 0.36%   |
| 5.4.66-gentoo            | 8         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.27 | 46        | 2.05%   |
| 5.4.38  | 45        | 2%      |
| 5.15.32 | 41        | 1.83%   |
| 6.1.57  | 39        | 1.74%   |
| 5.10.61 | 39        | 1.74%   |
| 6.1.19  | 37        | 1.65%   |
| 6.1.12  | 35        | 1.56%   |
| 5.15.80 | 34        | 1.51%   |
| 5.4.48  | 33        | 1.47%   |
| 5.10.76 | 32        | 1.43%   |
| 5.15.75 | 30        | 1.34%   |
| 5.15.59 | 26        | 1.16%   |
| 6.1.31  | 25        | 1.11%   |
| 5.4.97  | 25        | 1.11%   |
| 5.4.28  | 25        | 1.11%   |
| 5.15.52 | 24        | 1.07%   |
| 5.10.52 | 24        | 1.07%   |
| 5.15.41 | 23        | 1.02%   |
| 6.1.41  | 22        | 0.98%   |
| 5.4.80  | 22        | 0.98%   |
| 5.15.11 | 19        | 0.85%   |
| 6.1.53  | 18        | 0.8%    |
| 6.1.46  | 18        | 0.8%    |
| 5.4.66  | 17        | 0.76%   |
| 5.15.88 | 17        | 0.76%   |
| 5.6.15  | 16        | 0.71%   |
| 5.4.60  | 16        | 0.71%   |
| 5.17.1  | 16        | 0.71%   |
| 5.15.72 | 16        | 0.71%   |
| 5.15.69 | 16        | 0.71%   |
| 6.1.38  | 15        | 0.67%   |
| 5.7.0   | 15        | 0.67%   |
| 5.15.23 | 15        | 0.67%   |
| 5.4.72  | 13        | 0.58%   |
| 4.19.97 | 13        | 0.58%   |
| 6.2.11  | 12        | 0.53%   |
| 6.0.0   | 12        | 0.53%   |
| 5.9.11  | 12        | 0.53%   |
| 5.19.0  | 12        | 0.53%   |
| 5.15.74 | 12        | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 335       | 16.36%  |
| 6.1     | 257       | 12.55%  |
| 5.4     | 230       | 11.23%  |
| 5.10    | 226       | 11.04%  |
| 4.19    | 66        | 3.22%   |
| 5.6     | 64        | 3.13%   |
| 5.9     | 58        | 2.83%   |
| 6.2     | 54        | 2.64%   |
| 5.8     | 54        | 2.64%   |
| 5.16    | 50        | 2.44%   |
| 5.14    | 50        | 2.44%   |
| 5.7     | 49        | 2.39%   |
| 5.17    | 49        | 2.39%   |
| 6.0     | 45        | 2.2%    |
| 6.4     | 42        | 2.05%   |
| 6.5     | 41        | 2%      |
| 6.3     | 41        | 2%      |
| 5.18    | 41        | 2%      |
| 5.11    | 41        | 2%      |
| 6.6     | 37        | 1.81%   |
| 5.19    | 37        | 1.81%   |
| 5.13    | 36        | 1.76%   |
| 5.12    | 30        | 1.46%   |
| 5.5     | 17        | 0.83%   |
| 4.14    | 17        | 0.83%   |
| 5.2     | 12        | 0.59%   |
| 5.1     | 10        | 0.49%   |
| 5.3     | 9         | 0.44%   |
| 5.0     | 9         | 0.44%   |
| 4.9     | 8         | 0.39%   |
| 4.4     | 8         | 0.39%   |
| 4.18    | 7         | 0.34%   |
| 6.7     | 3         | 0.15%   |
| 4.6     | 3         | 0.15%   |
| 4.12    | 3         | 0.15%   |
| 4.20    | 2         | 0.1%    |
| 4.10    | 2         | 0.1%    |
| 4.5     | 1         | 0.05%   |
| 4.16    | 1         | 0.05%   |
| 4.13    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| x86_64      | 1586      | 95.95%  |
| i686        | 31        | 1.88%   |
| aarch64     | 16        | 0.97%   |
| ppc         | 7         | 0.42%   |
| armv7l      | 3         | 0.18%   |
| armv6l      | 3         | 0.18%   |
| loongarch64 | 2         | 0.12%   |
| armv5tel    | 2         | 0.12%   |
| riscv64     | 1         | 0.06%   |
| ppc64le     | 1         | 0.06%   |
| ppc64       | 1         | 0.06%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 731       | 41.02%  |
| KDE5           | 398       | 22.33%  |
| GNOME          | 221       | 12.4%   |
| XFCE           | 160       | 8.98%   |
| KDE            | 60        | 3.37%   |
| MATE           | 48        | 2.69%   |
| DWM            | 30        | 1.68%   |
| LXQt           | 19        | 1.07%   |
| i3             | 15        | 0.84%   |
| Sway           | 14        | 0.79%   |
| Hyprland       | 14        | 0.79%   |
| X-Cinnamon     | 12        | 0.67%   |
| LXDE           | 8         | 0.45%   |
| Enlightenment  | 8         | 0.45%   |
| awesome        | 7         | 0.39%   |
| Xsession       | 6         | 0.34%   |
| Cinnamon       | 6         | 0.34%   |
| openbox        | 4         | 0.22%   |
| bspwm          | 4         | 0.22%   |
| Trinity        | 3         | 0.17%   |
| Unity          | 2         | 0.11%   |
| GNOME Classic  | 2         | 0.11%   |
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
| X11     | 929       | 51.96%  |
| Unknown | 337       | 18.85%  |
| Tty     | 276       | 15.44%  |
| Wayland | 246       | 13.76%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 819       | 47.01%  |
| SDDM    | 466       | 26.75%  |
| LightDM | 201       | 11.54%  |
| GDM     | 155       | 8.9%    |
| SLiM    | 32        | 1.84%   |
| XDM     | 27        | 1.55%   |
| LXDM    | 21        | 1.21%   |
| GREETD  | 11        | 0.63%   |
| TDM     | 7         | 0.4%    |
| Ly      | 1         | 0.06%   |
| KDM     | 1         | 0.06%   |
| GDM3    | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 638       | 36.67%  |
| Unknown    | 254       | 14.6%   |
| C.UTF8     | 162       | 9.31%   |
| en_GB      | 109       | 6.26%   |
| de_DE      | 108       | 6.21%   |
| ru_RU      | 71        | 4.08%   |
| C          | 46        | 2.64%   |
| fr_FR      | 37        | 2.13%   |
| es_ES      | 25        | 1.44%   |
| it_IT      | 23        | 1.32%   |
| en_CA      | 22        | 1.26%   |
| cs_CZ      | 22        | 1.26%   |
| pl_PL      | 18        | 1.03%   |
| en_AU      | 18        | 1.03%   |
| pt_BR      | 13        | 0.75%   |
| zh_CN      | 12        | 0.69%   |
| en_IE      | 11        | 0.63%   |
| sv_SE      | 7         | 0.4%    |
| ru_RU.UTF8 | 7         | 0.4%    |
| POSIX      | 7         | 0.4%    |
| nl_NL      | 7         | 0.4%    |
| fi_FI      | 6         | 0.34%   |
| es_AR      | 6         | 0.34%   |
| en_US.UTF8 | 6         | 0.34%   |
| el_GR      | 6         | 0.34%   |
| de_CH      | 6         | 0.34%   |
| uk_UA      | 5         | 0.29%   |
| nl_BE      | 5         | 0.29%   |
| ja_JP      | 5         | 0.29%   |
| fr_CA      | 5         | 0.29%   |
| ca_ES      | 5         | 0.29%   |
| zh_TW      | 4         | 0.23%   |
| es_MX      | 4         | 0.23%   |
| ro_RO      | 3         | 0.17%   |
| es_CL      | 3         | 0.17%   |
| en_ZA      | 3         | 0.17%   |
| ru_UA      | 2         | 0.11%   |
| pt_PT      | 2         | 0.11%   |
| mi_NZ      | 2         | 0.11%   |
| lt_LT      | 2         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1230      | 72.91%  |
| BIOS | 457       | 27.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 989       | 58.49%  |
| Btrfs    | 397       | 23.48%  |
| Xfs      | 80        | 4.73%   |
| F2fs     | 64        | 3.78%   |
| Zfs      | 60        | 3.55%   |
| Unknown  | 46        | 2.72%   |
| XXXXXXX  | 23        | 1.36%   |
| Reiserfs | 17        | 1.01%   |
| Overlay  | 3         | 0.18%   |
| Jfs      | 3         | 0.18%   |
| Ext3     | 3         | 0.18%   |
| XXX      | 2         | 0.12%   |
| Bcachefs | 2         | 0.12%   |
| Xtrfs    | 1         | 0.06%   |
| Ext2     | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1402      | 83.6%   |
| MBR     | 182       | 10.85%  |
| Unknown | 93        | 5.55%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1188      | 68.39%  |
| Yes       | 549       | 31.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1143      | 67.24%  |
| Yes       | 557       | 32.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 375       | 22.69%  |
| Lenovo                  | 242       | 14.64%  |
| Dell                    | 160       | 9.68%   |
| Hewlett-Packard         | 149       | 9.01%   |
| MSI                     | 142       | 8.59%   |
| Gigabyte Technology     | 113       | 6.84%   |
| ASRock                  | 97        | 5.87%   |
| Acer                    | 51        | 3.09%   |
| Unknown                 | 32        | 1.94%   |
| Intel                   | 30        | 1.81%   |
| Apple                   | 29        | 1.75%   |
| Supermicro              | 24        | 1.45%   |
| Raspberry Pi Foundation | 14        | 0.85%   |
| Fujitsu                 | 13        | 0.79%   |
| Timi                    | 12        | 0.73%   |
| HUAWEI                  | 12        | 0.73%   |
| Samsung Electronics     | 11        | 0.67%   |
| Toshiba                 | 9         | 0.54%   |
| TUXEDO                  | 7         | 0.42%   |
| Framework               | 7         | 0.42%   |
| Razer                   | 5         | 0.3%    |
| IBM                     | 5         | 0.3%    |
| Google                  | 5         | 0.3%    |
| ASRockRack              | 5         | 0.3%    |
| TYAN Computer           | 4         | 0.24%   |
| System76                | 4         | 0.24%   |
| Notebook                | 4         | 0.24%   |
| Alienware               | 4         | 0.24%   |
| Tekram Technology       | 3         | 0.18%   |
| Sony                    | 3         | 0.18%   |
| Pegatron                | 3         | 0.18%   |
| Medion                  | 3         | 0.18%   |
| Foxconn                 | 3         | 0.18%   |
| BESSTAR Tech            | 3         | 0.18%   |
| ZOTAC                   | 2         | 0.12%   |
| win element             | 2         | 0.12%   |
| Valve                   | 2         | 0.12%   |
| Star Labs               | 2         | 0.12%   |
| Schenker                | 2         | 0.12%   |
| Purism                  | 2         | 0.12%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 39        | 2.36%   |
| ASUS All Series                        | 21        | 1.27%   |
| ASUS TUF Gaming X570-PLUS              | 12        | 0.73%   |
| Supermicro Super Server                | 9         | 0.54%   |
| MSI MS-7C02                            | 9         | 0.54%   |
| ASUS ROG STRIX X570-E GAMING           | 8         | 0.48%   |
| ASUS PRIME X570-PRO                    | 8         | 0.48%   |
| ASUS PRIME X470-PRO                    | 7         | 0.42%   |
| MSI MS-7A38                            | 6         | 0.36%   |
| Dell XPS 15 9570                       | 6         | 0.36%   |
| ASUS TUF Gaming B550-PLUS              | 6         | 0.36%   |
| ASUS ROG Strix G513QY_G513QY           | 6         | 0.36%   |
| ASUS PRIME X370-PRO                    | 6         | 0.36%   |
| MSI MS-7C91                            | 5         | 0.3%    |
| MSI MS-7C37                            | 5         | 0.3%    |
| MSI MS-7C35                            | 5         | 0.3%    |
| HP Pavilion Notebook                   | 5         | 0.3%    |
| HP OMEN by Laptop                      | 5         | 0.3%    |
| ASUS ROG STRIX B450-F GAMING           | 5         | 0.3%    |
| ASUS ROG CROSSHAIR VIII HERO           | 5         | 0.3%    |
| ASUS PRIME X570-P                      | 5         | 0.3%    |
| ASRock B450 Pro4                       | 5         | 0.3%    |
| MSI MS-7B89                            | 4         | 0.24%   |
| MSI MS-7B86                            | 4         | 0.24%   |
| MSI MS-7B79                            | 4         | 0.24%   |
| HP Pavilion Gaming Laptop 15-ec1xxx    | 4         | 0.24%   |
| HP Laptop 14-dk1xxx                    | 4         | 0.24%   |
| Gigabyte X570 AORUS ELITE              | 4         | 0.24%   |
| Gigabyte B450M DS3H                    | 4         | 0.24%   |
| Framework Laptop (13th Gen Intel Core) | 4         | 0.24%   |
| Dell XPS 17 9710                       | 4         | 0.24%   |
| Dell XPS 15 7590                       | 4         | 0.24%   |
| Dell XPS 13 9310                       | 4         | 0.24%   |
| ASUS Z170 PRO GAMING                   | 4         | 0.24%   |
| ASUS ROG Zephyrus G14 GA401II_GA401II  | 4         | 0.24%   |
| ASUS ROG STRIX B550-F GAMING           | 4         | 0.24%   |
| ASUS ROG CROSSHAIR VIII DARK HERO      | 4         | 0.24%   |
| ASUS ROG CROSSHAIR VII HERO            | 4         | 0.24%   |
| ASUS PRIME B450M-A                     | 4         | 0.24%   |
| ASUS M4A89GTD-PRO/USB3                 | 4         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 137       | 8.29%   |
| ASUS ROG          | 97        | 5.87%   |
| ASUS PRIME        | 67        | 4.05%   |
| Dell Latitude     | 46        | 2.78%   |
| ASUS TUF          | 45        | 2.72%   |
| Dell XPS          | 43        | 2.6%    |
| Unknown           | 39        | 2.36%   |
| Acer Aspire       | 30        | 1.81%   |
| Lenovo IdeaPad    | 27        | 1.63%   |
| HP EliteBook      | 27        | 1.63%   |
| Lenovo Legion     | 26        | 1.57%   |
| HP Pavilion       | 26        | 1.57%   |
| Dell Precision    | 22        | 1.33%   |
| ASUS All          | 21        | 1.27%   |
| Dell Inspiron     | 20        | 1.21%   |
| Lenovo Yoga       | 18        | 1.09%   |
| HP Laptop         | 17        | 1.03%   |
| ASUS VivoBook     | 16        | 0.97%   |
| RPi Raspberry     | 14        | 0.85%   |
| HP OMEN           | 13        | 0.79%   |
| ASRock X570       | 13        | 0.79%   |
| Gigabyte X570     | 12        | 0.73%   |
| HP ProBook        | 11        | 0.67%   |
| Dell OptiPlex     | 11        | 0.67%   |
| ASUS ZenBook      | 10        | 0.6%    |
| Supermicro Super  | 9         | 0.54%   |
| MSI MS-7C02       | 9         | 0.54%   |
| Gigabyte B450M    | 9         | 0.54%   |
| Acer Swift        | 9         | 0.54%   |
| HP ProLiant       | 8         | 0.48%   |
| Gigabyte B450     | 8         | 0.48%   |
| ASUS ASUS         | 8         | 0.48%   |
| ASRock X370       | 8         | 0.48%   |
| Toshiba Satellite | 7         | 0.42%   |
| Timi RedmiBook    | 7         | 0.42%   |
| HP ZBook          | 7         | 0.42%   |
| HP Compaq         | 7         | 0.42%   |
| Framework Laptop  | 7         | 0.42%   |
| Acer Nitro        | 7         | 0.42%   |
| MSI MS-7A38       | 6         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 247       | 14.94%  |
| 2020    | 218       | 13.19%  |
| 2018    | 202       | 12.22%  |
| 2021    | 180       | 10.89%  |
| 2022    | 100       | 6.05%   |
| 2017    | 98        | 5.93%   |
| 2012    | 79        | 4.78%   |
| 2015    | 73        | 4.42%   |
| 2014    | 67        | 4.05%   |
| 2013    | 65        | 3.93%   |
| 2016    | 62        | 3.75%   |
| 2011    | 51        | 3.09%   |
| 2010    | 45        | 2.72%   |
| Unknown | 34        | 2.06%   |
| 2023    | 33        | 2%      |
| 2008    | 32        | 1.94%   |
| 2009    | 30        | 1.81%   |
| 2007    | 12        | 0.73%   |
| 2006    | 7         | 0.42%   |
| 2005    | 5         | 0.3%    |
| 2004    | 5         | 0.3%    |
| 2003    | 4         | 0.24%   |
| 2000    | 3         | 0.18%   |
| 2002    | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 774       | 46.82%  |
| Desktop        | 747       | 45.19%  |
| Server         | 43        | 2.6%    |
| Convertible    | 38        | 2.3%    |
| System on chip | 20        | 1.21%   |
| Mini pc        | 17        | 1.03%   |
| All in one     | 7         | 0.42%   |
| Tablet         | 5         | 0.3%    |
| Phone          | 1         | 0.06%   |
| Stick pc       | 1         | 0.06%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1629      | 98.13%  |
| Enabled  | 31        | 1.87%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1641      | 99.27%  |
| Yes  | 12        | 0.73%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 423       | 24.88%  |
| 16.01-24.0      | 392       | 23.06%  |
| 8.01-16.0       | 260       | 15.29%  |
| 4.01-8.0        | 201       | 11.82%  |
| 64.01-256.0     | 186       | 10.94%  |
| 3.01-4.0        | 90        | 5.29%   |
| 24.01-32.0      | 68        | 4%      |
| 1.01-2.0        | 30        | 1.76%   |
| 0.51-1.0        | 20        | 1.18%   |
| 2.01-3.0        | 19        | 1.12%   |
| 0.01-0.5        | 8         | 0.47%   |
| More than 256.0 | 3         | 0.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 405       | 20.29%  |
| 4.01-8.0    | 374       | 18.74%  |
| 2.01-3.0    | 336       | 16.83%  |
| 3.01-4.0    | 228       | 11.42%  |
| 8.01-16.0   | 202       | 10.12%  |
| 0.01-0.5    | 185       | 9.27%   |
| 0.51-1.0    | 173       | 8.67%   |
| 16.01-24.0  | 55        | 2.76%   |
| 32.01-64.0  | 18        | 0.9%    |
| 24.01-32.0  | 13        | 0.65%   |
| 64.01-256.0 | 4         | 0.2%    |
| 0           | 3         | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 766       | 43.87%  |
| 2       | 454       | 26%     |
| 3       | 203       | 11.63%  |
| 4       | 117       | 6.7%    |
| 5       | 79        | 4.52%   |
| 6       | 43        | 2.46%   |
| 7       | 32        | 1.83%   |
| 8       | 16        | 0.92%   |
| 0       | 11        | 0.63%   |
| 9       | 6         | 0.34%   |
| 13      | 4         | 0.23%   |
| 10      | 4         | 0.23%   |
| 12      | 3         | 0.17%   |
| 21      | 2         | 0.11%   |
| 31      | 1         | 0.06%   |
| 26      | 1         | 0.06%   |
| 18      | 1         | 0.06%   |
| 17      | 1         | 0.06%   |
| 11      | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1325      | 78.82%  |
| Yes       | 356       | 21.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1428      | 85.71%  |
| No        | 238       | 14.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1145      | 68.85%  |
| No        | 518       | 31.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1060      | 63.17%  |
| No        | 618       | 36.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 353       | 21.06%  |
| Germany      | 233       | 13.9%   |
| Russia       | 147       | 8.77%   |
| UK           | 85        | 5.07%   |
| France       | 77        | 4.59%   |
| Canada       | 65        | 3.88%   |
| Spain        | 56        | 3.34%   |
| Poland       | 52        | 3.1%    |
| China        | 50        | 2.98%   |
| Czechia      | 42        | 2.51%   |
| Italy        | 39        | 2.33%   |
| Sweden       | 35        | 2.09%   |
| Australia    | 34        | 2.03%   |
| Netherlands  | 33        | 1.97%   |
| Finland      | 30        | 1.79%   |
| Ukraine      | 24        | 1.43%   |
| Brazil       | 22        | 1.31%   |
| Switzerland  | 21        | 1.25%   |
| Greece       | 18        | 1.07%   |
| Belgium      | 17        | 1.01%   |
| Austria      | 15        | 0.89%   |
| Mexico       | 14        | 0.84%   |
| Japan        | 13        | 0.78%   |
| Turkey       | 11        | 0.66%   |
| Romania      | 11        | 0.66%   |
| Norway       | 11        | 0.66%   |
| Belarus      | 11        | 0.66%   |
| Hungary      | 10        | 0.6%    |
| Slovakia     | 9         | 0.54%   |
| India        | 9         | 0.54%   |
| Hong Kong    | 9         | 0.54%   |
| Taiwan       | 8         | 0.48%   |
| Argentina    | 8         | 0.48%   |
| Ireland      | 7         | 0.42%   |
| Portugal     | 6         | 0.36%   |
| Indonesia    | 6         | 0.36%   |
| Vietnam      | 5         | 0.3%    |
| South Africa | 5         | 0.3%    |
| Slovenia     | 5         | 0.3%    |
| New Zealand  | 5         | 0.3%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 56        | 3.03%   |
| Moscow            | 49        | 2.65%   |
| St Petersburg     | 22        | 1.19%   |
| Athens            | 18        | 0.97%   |
| Sydney            | 17        | 0.92%   |
| Warsaw            | 16        | 0.87%   |
| Munich            | 15        | 0.81%   |
| Paris             | 14        | 0.76%   |
| Los Angeles       | 13        | 0.7%    |
| Helsinki          | 13        | 0.7%    |
| Frankfurt am Main | 13        | 0.7%    |
| Amsterdam         | 13        | 0.7%    |
| Vancouver         | 12        | 0.65%   |
| Cieszyn           | 12        | 0.65%   |
| Prague            | 11        | 0.59%   |
| Milan             | 11        | 0.59%   |
| Kyiv              | 11        | 0.59%   |
| Vladivostok       | 10        | 0.54%   |
| Beijing           | 10        | 0.54%   |
| New York          | 9         | 0.49%   |
| Guangzhou         | 9         | 0.49%   |
| Wuelfrath         | 8         | 0.43%   |
| Vienna            | 8         | 0.43%   |
| Stockholm         | 8         | 0.43%   |
| Seattle           | 8         | 0.43%   |
| Minsk             | 8         | 0.43%   |
| Melbourne         | 8         | 0.43%   |
| Barcelona         | 8         | 0.43%   |
| Sao Paulo         | 7         | 0.38%   |
| Oulu              | 7         | 0.38%   |
| Ottawa            | 7         | 0.38%   |
| Madrid            | 7         | 0.38%   |
| London            | 7         | 0.38%   |
| Hamburg           | 7         | 0.38%   |
| Dublin            | 7         | 0.38%   |
| Bothell           | 7         | 0.38%   |
| Zurich            | 6         | 0.32%   |
| Woolwich          | 6         | 0.32%   |
| Weatherford       | 6         | 0.32%   |
| Sterling          | 6         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 618       | 1290   | 21.59%  |
| WDC                         | 446       | 1014   | 15.58%  |
| Seagate                     | 341       | 742    | 11.91%  |
| Sandisk                     | 158       | 229    | 5.52%   |
| Kingston                    | 138       | 198    | 4.82%   |
| Toshiba                     | 131       | 237    | 4.58%   |
| Intel                       | 126       | 209    | 4.4%    |
| Crucial                     | 87        | 159    | 3.04%   |
| SK hynix                    | 80        | 102    | 2.8%    |
| Unknown                     | 74        | 109    | 2.59%   |
| Hitachi                     | 64        | 182    | 2.24%   |
| HGST                        | 61        | 103    | 2.13%   |
| Micron Technology           | 47        | 63     | 1.64%   |
| Phison Electronics          | 42        | 56     | 1.47%   |
| A-DATA Technology           | 41        | 58     | 1.43%   |
| KIOXIA                      | 27        | 36     | 0.94%   |
| Phison                      | 22        | 34     | 0.77%   |
| Micron/Crucial Technology   | 19        | 25     | 0.66%   |
| Kingston Technology Company | 19        | 21     | 0.66%   |
| Corsair                     | 19        | 34     | 0.66%   |
| OCZ                         | 17        | 25     | 0.59%   |
| China                       | 17        | 43     | 0.59%   |
| Silicon Motion              | 12        | 19     | 0.42%   |
| Apple                       | 12        | 14     | 0.42%   |
| GOODRAM                     | 11        | 64     | 0.38%   |
| Transcend                   | 10        | 15     | 0.35%   |
| Realtek Semiconductor       | 8         | 16     | 0.28%   |
| PNY                         | 8         | 13     | 0.28%   |
| Patriot                     | 8         | 12     | 0.28%   |
| Fujitsu                     | 8         | 11     | 0.28%   |
| ADATA Technology            | 8         | 12     | 0.28%   |
| XPG                         | 7         | 14     | 0.24%   |
| SPCC                        | 7         | 9      | 0.24%   |
| Plextor                     | 7         | 8      | 0.24%   |
| LITEONIT                    | 7         | 9      | 0.24%   |
| Team                        | 6         | 13     | 0.21%   |
| Mushkin                     | 6         | 6      | 0.21%   |
| MAXIO Technology (Hangzhou) | 6         | 7      | 0.21%   |
| Yangtze Memory Technologies | 5         | 7      | 0.17%   |
| LITEON                      | 5         | 9      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 77        | 2.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 55        | 1.6%    |
| Samsung SSD 860 EVO 1TB                             | 32        | 0.93%   |
| Samsung SSD 850 EVO 250GB                           | 31        | 0.9%    |
| Samsung SSD 860 EVO 500GB                           | 26        | 0.76%   |
| HGST HTS721010A9E630 1TB                            | 26        | 0.76%   |
| Samsung SSD 850 EVO 500GB                           | 25        | 0.73%   |
| Samsung SSD 980 1TB                                 | 24        | 0.7%    |
| WDC WD30EFRX-68EUZN0 3TB                            | 23        | 0.67%   |
| Kingston SA400S37240G 240GB SSD                     | 22        | 0.64%   |
| Samsung SSD 860 EVO 250GB                           | 21        | 0.61%   |
| Samsung SSD 970 EVO Plus 500GB                      | 19        | 0.55%   |
| Seagate ST1000DM010-2EP102 1TB                      | 18        | 0.52%   |
| Kingston SA400S37480G 480GB SSD                     | 16        | 0.46%   |
| Seagate ST4000DM004-2CV104 4TB                      | 15        | 0.44%   |
| Seagate ST2000DM008-2FR102 2TB                      | 15        | 0.44%   |
| Samsung SSD 970 EVO Plus 1TB                        | 15        | 0.44%   |
| Samsung SSD 970 EVO 500GB                           | 15        | 0.44%   |
| Crucial CT1000MX500SSD1 1TB                         | 15        | 0.44%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 14        | 0.41%   |
| Unknown MMC Card  32GB                              | 14        | 0.41%   |
| Seagate ST500DM002-1BD142 500GB                     | 14        | 0.41%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 14        | 0.41%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 2TB      | 14        | 0.41%   |
| Intel SSD 660P Series 1TB                           | 14        | 0.41%   |
| Seagate ST2000DM001-1ER164 2TB                      | 13        | 0.38%   |
| Samsung SSD 970 EVO 250GB                           | 13        | 0.38%   |
| Samsung SSD 970 EVO 1TB                             | 13        | 0.38%   |
| Phison E12 NVMe Controller 1TB                      | 13        | 0.38%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 12        | 0.35%   |
| Unknown MMC Card  128GB                             | 12        | 0.35%   |
| Seagate ST2000DM006-2DM164 2TB                      | 12        | 0.35%   |
| Samsung SSD 980 PRO 1TB                             | 12        | 0.35%   |
| Samsung SSD 870 EVO 1TB                             | 12        | 0.35%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                 | 12        | 0.35%   |
| Kingston SA400S37120G 120GB SSD                     | 12        | 0.35%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 11        | 0.32%   |
| WDC WD20EFRX-68EUZN0 2TB                            | 11        | 0.32%   |
| Toshiba DT01ACA100 1TB                              | 11        | 0.32%   |
| Samsung SSD 970 PRO 512GB                           | 11        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 338       | 819    | 35.32%  |
| Seagate             | 332       | 726    | 34.69%  |
| Toshiba             | 89        | 183    | 9.3%    |
| Hitachi             | 64        | 182    | 6.69%   |
| HGST                | 61        | 103    | 6.37%   |
| Samsung Electronics | 30        | 45     | 3.13%   |
| Fujitsu             | 8         | 11     | 0.84%   |
| IBM                 | 5         | 6      | 0.52%   |
| Unknown             | 4         | 5      | 0.42%   |
| SABRENT             | 3         | 3      | 0.31%   |
| IBM/Hitachi         | 3         | 4      | 0.31%   |
| TO Exter            | 2         | 2      | 0.21%   |
| MDT                 | 2         | 2      | 0.21%   |
| Maxtor              | 2         | 2      | 0.21%   |
| LaCie               | 2         | 12     | 0.21%   |
| Apple               | 2         | 2      | 0.21%   |
| Teleplan            | 1         | 4      | 0.1%    |
| StoreJet            | 1         | 1      | 0.1%    |
| HGST HTS            | 1         | 1      | 0.1%    |
| Hewlett-Packard     | 1         | 2      | 0.1%    |
| FNK TECH            | 1         | 1      | 0.1%    |
| Dyconn H            | 1         | 1      | 0.1%    |
| ASMT                | 1         | 2      | 0.1%    |
| ASMedia             | 1         | 1      | 0.1%    |
| AFAYA               | 1         | 1      | 0.1%    |
| Unknown             | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 297       | 540    | 32.42%  |
| Kingston            | 101       | 142    | 11.03%  |
| SanDisk             | 81        | 124    | 8.84%   |
| Crucial             | 79        | 144    | 8.62%   |
| WDC                 | 57        | 80     | 6.22%   |
| Intel               | 41        | 54     | 4.48%   |
| A-DATA Technology   | 27        | 38     | 2.95%   |
| China               | 17        | 43     | 1.86%   |
| OCZ                 | 16        | 24     | 1.75%   |
| Micron Technology   | 16        | 26     | 1.75%   |
| Toshiba             | 13        | 15     | 1.42%   |
| SK hynix            | 13        | 14     | 1.42%   |
| Corsair             | 12        | 19     | 1.31%   |
| GOODRAM             | 11        | 64     | 1.2%    |
| Transcend           | 8         | 13     | 0.87%   |
| Apple               | 8         | 9      | 0.87%   |
| PNY                 | 7         | 12     | 0.76%   |
| LITEONIT            | 7         | 9      | 0.76%   |
| SPCC                | 6         | 8      | 0.66%   |
| Plextor             | 6         | 6      | 0.66%   |
| Patriot             | 6         | 10     | 0.66%   |
| Team                | 5         | 7      | 0.55%   |
| Mushkin             | 5         | 5      | 0.55%   |
| Verbatim            | 4         | 4      | 0.44%   |
| Intenso             | 4         | 5      | 0.44%   |
| Unknown             | 4         | 5      | 0.44%   |
| T-FORCE             | 3         | 8      | 0.33%   |
| Seagate             | 3         | 6      | 0.33%   |
| Netac               | 3         | 3      | 0.33%   |
| KingSpec            | 3         | 4      | 0.33%   |
| Dogfish             | 3         | 3      | 0.33%   |
| Apacer              | 3         | 5      | 0.33%   |
| Smartbuy            | 2         | 2      | 0.22%   |
| MyDigitalSSD        | 2         | 2      | 0.22%   |
| LITEON              | 2         | 4      | 0.22%   |
| Linux               | 2         | 2      | 0.22%   |
| Lexar               | 2         | 2      | 0.22%   |
| Lenovo              | 2         | 3      | 0.22%   |
| KingDian            | 2         | 2      | 0.22%   |
| Kingchuxing         | 2         | 5      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 921       | 1667   | 37.15%  |
| SSD     | 745       | 1509   | 30.05%  |
| HDD     | 739       | 2122   | 29.81%  |
| MMC     | 64        | 94     | 2.58%   |
| Unknown | 10        | 20     | 0.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1090      | 3544   | 51.03%  |
| NVMe | 920       | 1666   | 43.07%  |
| MMC  | 64        | 94     | 3%      |
| SAS  | 62        | 108    | 2.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 727       | 1417   | 42.92%  |
| 0.51-1.0   | 486       | 871    | 28.69%  |
| 1.01-2.0   | 220       | 524    | 12.99%  |
| 3.01-4.0   | 113       | 266    | 6.67%   |
| 4.01-10.0  | 67        | 277    | 3.96%   |
| 2.01-3.0   | 61        | 213    | 3.6%    |
| 10.01-20.0 | 19        | 62     | 1.12%   |
| 20.01-50.0 | 1         | 1      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 345       | 19.19%  |
| 101-250        | 311       | 17.3%   |
| 501-1000       | 308       | 17.13%  |
| 1001-2000      | 213       | 11.85%  |
| More than 3000 | 209       | 11.62%  |
| Unknown        | 103       | 5.73%   |
| 2001-3000      | 91        | 5.06%   |
| 51-100         | 89        | 4.95%   |
| 1-20           | 88        | 4.89%   |
| 21-50          | 41        | 2.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 392       | 20.71%  |
| 101-250        | 269       | 14.21%  |
| 21-50          | 265       | 14%     |
| 251-500        | 234       | 12.36%  |
| 51-100         | 182       | 9.61%   |
| 501-1000       | 177       | 9.35%   |
| 1001-2000      | 127       | 6.71%   |
| Unknown        | 103       | 5.44%   |
| More than 3000 | 96        | 5.07%   |
| 2001-3000      | 48        | 2.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                     | 8         | 9      | 2.58%   |
| Seagate ST3500418AS 500GB                    | 6         | 7      | 1.94%   |
| Seagate ST500DM002-1BC142 500GB              | 5         | 5      | 1.61%   |
| WDC WD40EFRX-68WT0N0 4TB                     | 4         | 14     | 1.29%   |
| Seagate ST500DM002-1BD142 500GB              | 4         | 4      | 1.29%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 4         | 9      | 1.29%   |
| Samsung Electronics SSD 980 1TB              | 4         | 4      | 1.29%   |
| WDC WD5000BEVT-22ZAT0 500GB                  | 3         | 3      | 0.97%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 3         | 6      | 0.97%   |
| WDC WD30EFRX-68AX9N0 3TB                     | 3         | 7      | 0.97%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 3         | 6      | 0.97%   |
| WDC WD2002FAEX-007BA0 2TB                    | 3         | 3      | 0.97%   |
| Seagate ST8000AS0002-1NA17Z 8TB              | 3         | 15     | 0.97%   |
| Samsung Electronics SSD 850 EVO 1TB          | 3         | 3      | 0.97%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD      | 3         | 3      | 0.97%   |
| IBM DJSA-220 12GB                            | 3         | 3      | 0.97%   |
| Hitachi HDS722020ALA330 2TB                  | 3         | 17     | 0.97%   |
| WDC WD60EFRX-68MYMN1 6TB                     | 2         | 5      | 0.65%   |
| WDC WD40EFRX-68N32N0 4TB                     | 2         | 2      | 0.65%   |
| WDC WD20EZRX-00D8PB0 2TB                     | 2         | 3      | 0.65%   |
| WDC WD20EARS-00MVWB0 2TB                     | 2         | 2      | 0.65%   |
| WDC WD1600AAJS-75B4A0 160GB                  | 2         | 2      | 0.65%   |
| WDC WD15EARS-00Z5B1 1TB                      | 2         | 2      | 0.65%   |
| WDC WD10JPVX-75JC3T0 1TB                     | 2         | 2      | 0.65%   |
| Toshiba DT01ACA200 2TB                       | 2         | 2      | 0.65%   |
| SK hynix HFS256G39TND-N210A 256GB SSD        | 2         | 2      | 0.65%   |
| Seagate ST4000DM000-1F2168 4TB               | 2         | 2      | 0.65%   |
| Seagate ST31000340NS 1TB                     | 2         | 3      | 0.65%   |
| Seagate ST3000DM001-9YN166 3TB               | 2         | 3      | 0.65%   |
| Seagate ST2000LX001-1RG174 2TB               | 2         | 2      | 0.65%   |
| Seagate ST2000DX002-2DV164 2TB               | 2         | 2      | 0.65%   |
| Seagate ST2000DL003-9VT166 2TB               | 2         | 3      | 0.65%   |
| Seagate ST1000NM0011 1TB                     | 2         | 6      | 0.65%   |
| SanDisk SSD PLUS 480GB                       | 2         | 2      | 0.65%   |
| SanDisk SSD PLUS 1000GB                      | 2         | 2      | 0.65%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD          | 2         | 2      | 0.65%   |
| Samsung Electronics SSD 870 EVO 500GB        | 2         | 3      | 0.65%   |
| Samsung Electronics SSD 870 EVO 1TB          | 2         | 9      | 0.65%   |
| Samsung Electronics SSD 840 PRO Series 512GB | 2         | 4      | 0.65%   |
| Samsung Electronics SP2504C 250GB            | 2         | 2      | 0.65%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 69        | 108    | 23.39%  |
| WDC                         | 65        | 122    | 22.03%  |
| Samsung Electronics         | 34        | 54     | 11.53%  |
| Hitachi                     | 18        | 34     | 6.1%    |
| Toshiba                     | 17        | 19     | 5.76%   |
| HGST                        | 15        | 21     | 5.08%   |
| SanDisk                     | 9         | 11     | 3.05%   |
| Intel                       | 9         | 11     | 3.05%   |
| Crucial                     | 7         | 7      | 2.37%   |
| SK hynix                    | 6         | 9      | 2.03%   |
| Kingston                    | 6         | 6      | 2.03%   |
| IBM                         | 4         | 4      | 1.36%   |
| Fujitsu                     | 4         | 4      | 1.36%   |
| Realtek Semiconductor       | 3         | 9      | 1.02%   |
| OCZ                         | 3         | 3      | 1.02%   |
| A-DATA Technology           | 3         | 3      | 1.02%   |
| PNY                         | 2         | 3      | 0.68%   |
| Plextor                     | 2         | 2      | 0.68%   |
| MDT                         | 2         | 2      | 0.68%   |
| IBM/Hitachi                 | 2         | 2      | 0.68%   |
| Corsair                     | 2         | 5      | 0.68%   |
| China                       | 2         | 3      | 0.68%   |
| Transcend                   | 1         | 1      | 0.34%   |
| SPCC                        | 1         | 1      | 0.34%   |
| Mushkin                     | 1         | 1      | 0.34%   |
| Maxtor                      | 1         | 1      | 0.34%   |
| LITEON                      | 1         | 3      | 0.34%   |
| Kingston Technology Company | 1         | 1      | 0.34%   |
| HGST HTS                    | 1         | 1      | 0.34%   |
| Emtec                       | 1         | 2      | 0.34%   |
| Apple                       | 1         | 1      | 0.34%   |
| 2.5"                        | 1         | 1      | 0.34%   |
| Unknown                     | 1         | 1      | 0.34%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 69        | 108    | 33.99%  |
| WDC                 | 63        | 120    | 31.03%  |
| Hitachi             | 18        | 34     | 8.87%   |
| Toshiba             | 16        | 18     | 7.88%   |
| HGST                | 15        | 21     | 7.39%   |
| Samsung Electronics | 6         | 7      | 2.96%   |
| IBM                 | 4         | 4      | 1.97%   |
| Fujitsu             | 4         | 4      | 1.97%   |
| MDT                 | 2         | 2      | 0.99%   |
| IBM/Hitachi         | 2         | 2      | 0.99%   |
| Maxtor              | 1         | 1      | 0.49%   |
| HGST HTS            | 1         | 1      | 0.49%   |
| Apple               | 1         | 1      | 0.49%   |
| Unknown             | 1         | 1      | 0.49%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 192       | 324    | 67.61%  |
| SSD  | 68        | 94     | 23.94%  |
| NVMe | 24        | 38     | 8.45%   |

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
| Works    | 1447      | 4453   | 73.79%  |
| Malfunc  | 270       | 456    | 13.77%  |
| Detected | 235       | 491    | 11.98%  |
| Failed   | 9         | 12     | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 852       | 34.08%  |
| AMD                              | 479       | 19.16%  |
| Samsung Electronics              | 398       | 15.92%  |
| SanDisk                          | 150       | 6%      |
| ASMedia Technology               | 80        | 3.2%    |
| Phison Electronics               | 73        | 2.92%   |
| SK hynix                         | 67        | 2.68%   |
| Kingston Technology Company      | 57        | 2.28%   |
| Toshiba America Info Systems     | 34        | 1.36%   |
| Micron Technology                | 32        | 1.28%   |
| Marvell Technology Group         | 32        | 1.28%   |
| KIOXIA                           | 29        | 1.16%   |
| Micron/Crucial Technology        | 26        | 1.04%   |
| ADATA Technology                 | 25        | 1%      |
| Nvidia                           | 24        | 0.96%   |
| JMicron Technology               | 20        | 0.8%    |
| Broadcom / LSI                   | 18        | 0.72%   |
| Silicon Motion                   | 17        | 0.68%   |
| LSI Logic / Symbios Logic        | 13        | 0.52%   |
| Realtek Semiconductor            | 11        | 0.44%   |
| Seagate Technology               | 6         | 0.24%   |
| MAXIO Technology (Hangzhou)      | 6         | 0.24%   |
| Adaptec                          | 6         | 0.24%   |
| Yangtze Memory Technologies      | 5         | 0.2%    |
| Solid State Storage Technology   | 5         | 0.2%    |
| Silicon Image                    | 5         | 0.2%    |
| INNOGRIT                         | 4         | 0.16%   |
| Silicon Integrated Systems [SiS] | 3         | 0.12%   |
| Lite-On Technology               | 3         | 0.12%   |
| VIA Technologies                 | 2         | 0.08%   |
| Union Memory (Shenzhen)          | 2         | 0.08%   |
| Loongson Technology              | 2         | 0.08%   |
| Lenovo                           | 2         | 0.08%   |
| Hewlett-Packard                  | 2         | 0.08%   |
| Apple                            | 2         | 0.08%   |
| 3ware                            | 2         | 0.08%   |
| Transcend                        | 1         | 0.04%   |
| Solidigm                         | 1         | 0.04%   |
| OCZ Technology Group             | 1         | 0.04%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 363       | 12.76%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 231       | 8.12%   |
| AMD 400 Series Chipset SATA Controller                                         | 100       | 3.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 85        | 2.99%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 69        | 2.43%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 58        | 2.04%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 55        | 1.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 55        | 1.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 54        | 1.9%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 48        | 1.69%   |
| AMD 500 Series Chipset SATA Controller                                         | 48        | 1.69%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 43        | 1.51%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 42        | 1.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 42        | 1.48%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 40        | 1.41%   |
| Intel Volume Management Device NVMe RAID Controller                            | 38        | 1.34%   |
| Intel SSD 660P Series                                                          | 37        | 1.3%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 34        | 1.2%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 30        | 1.05%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 30        | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 29        | 1.02%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 29        | 1.02%   |
| Intel Comet Lake SATA AHCI Controller                                          | 27        | 0.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 26        | 0.91%   |
| Phison E12 NVMe Controller                                                     | 25        | 0.88%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 25        | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 24        | 0.84%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 23        | 0.81%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 21        | 0.74%   |
| AMD X370 Series Chipset SATA Controller                                        | 21        | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 20        | 0.7%    |
| Phison E16 PCIe4 NVMe Controller                                               | 19        | 0.67%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 19        | 0.67%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 18        | 0.63%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 18        | 0.63%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 16        | 0.56%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 16        | 0.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 16        | 0.56%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 15        | 0.53%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 15        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1173      | 49.04%  |
| NVMe | 928       | 38.8%   |
| IDE  | 128       | 5.35%   |
| RAID | 126       | 5.27%   |
| SAS  | 29        | 1.21%   |
| SCSI | 8         | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 1010      | 61.1%   |
| AMD                      | 607       | 36.72%  |
| ARM                      | 21        | 1.27%   |
| Marvell Semiconductor    | 3         | 0.18%   |
| Loongson                 | 2         | 0.12%   |
| thead,c906               | 1         | 0.06%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.06%   |
| PowerMac8,1              | 1         | 0.06%   |
| PowerMac3,6              | 1         | 0.06%   |
| PowerMac10,2             | 1         | 0.06%   |
| PowerBook6,7             | 1         | 0.06%   |
| PowerBook5,6             | 1         | 0.06%   |
| PowerBook5,5             | 1         | 0.06%   |
| PowerBook5,4             | 1         | 0.06%   |
| PowerBook3,4             | 1         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor            | 29        | 1.74%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 24        | 1.44%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 22        | 1.32%   |
| AMD Ryzen 5 3600 6-Core Processor             | 22        | 1.32%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 21        | 1.26%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 20        | 1.2%    |
| AMD Ryzen 5 5600X 6-Core Processor            | 20        | 1.2%    |
| AMD Ryzen 9 3900X 12-Core Processor           | 19        | 1.14%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 18        | 1.08%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 18        | 1.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 1.02%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 16        | 0.96%   |
| ARM Processor                                 | 16        | 0.96%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 15        | 0.9%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 15        | 0.9%    |
| AMD Ryzen 9 3950X 16-Core Processor           | 15        | 0.9%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 15        | 0.9%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 14        | 0.84%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 13        | 0.78%   |
| Intel 12th Gen Core i7-12700H                 | 13        | 0.78%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 13        | 0.78%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 13        | 0.78%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 13        | 0.78%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 13        | 0.78%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 12        | 0.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 0.72%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 12        | 0.72%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 12        | 0.72%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 12        | 0.72%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 11        | 0.66%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 10        | 0.6%    |
| Intel Core i7-6700K CPU @ 4.00GHz             | 10        | 0.6%    |
| AMD Ryzen 9 7950X 16-Core Processor           | 10        | 0.6%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 10        | 0.6%    |
| Intel Core i9-9900K CPU @ 3.60GHz             | 9         | 0.54%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.54%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 0.54%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 9         | 0.54%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 9         | 0.54%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 9         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 359       | 21.61%  |
| Intel Core i5          | 227       | 13.67%  |
| AMD Ryzen 7            | 200       | 12.04%  |
| Other                  | 184       | 11.08%  |
| AMD Ryzen 5            | 141       | 8.49%   |
| AMD Ryzen 9            | 111       | 6.68%   |
| Intel Xeon             | 80        | 4.82%   |
| AMD Ryzen 7 PRO        | 30        | 1.81%   |
| Intel Atom             | 27        | 1.63%   |
| Intel Core i3          | 26        | 1.57%   |
| Intel Celeron          | 26        | 1.57%   |
| Intel Core i9          | 25        | 1.51%   |
| AMD FX                 | 24        | 1.44%   |
| Intel Core 2 Duo       | 22        | 1.32%   |
| Intel Pentium          | 20        | 1.2%    |
| AMD Ryzen 3            | 17        | 1.02%   |
| AMD Ryzen Threadripper | 11        | 0.66%   |
| AMD Phenom II X4       | 11        | 0.66%   |
| Intel Core 2 Quad      | 10        | 0.6%    |
| Intel Pentium M        | 9         | 0.54%   |
| AMD Ryzen 5 PRO        | 9         | 0.54%   |
| Intel Pentium 4        | 8         | 0.48%   |
| AMD A6                 | 7         | 0.42%   |
| AMD Phenom II X6       | 6         | 0.36%   |
| Intel Pentium Silver   | 5         | 0.3%    |
| AMD A10                | 5         | 0.3%    |
| Intel Pentium III      | 4         | 0.24%   |
| ARM BCM                | 4         | 0.24%   |
| AMD Sempron            | 4         | 0.24%   |
| AMD EPYC               | 4         | 0.24%   |
| AMD Athlon 64 X2       | 4         | 0.24%   |
| AMD Athlon             | 4         | 0.24%   |
| Intel Core m3          | 3         | 0.18%   |
| Intel Core 2           | 3         | 0.18%   |
| AMD E                  | 3         | 0.18%   |
| AMD Athlon II X3       | 3         | 0.18%   |
| AMD A8                 | 3         | 0.18%   |
| Intel Genuine          | 2         | 0.12%   |
| Intel Core Duo         | 2         | 0.12%   |
| AMD E1                 | 2         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 542       | 32.59%  |
| 8       | 316       | 19%     |
| 6       | 274       | 16.48%  |
| 2       | 258       | 15.51%  |
| 12      | 86        | 5.17%   |
| 16      | 63        | 3.79%   |
| 1       | 48        | 2.89%   |
| 14      | 28        | 1.68%   |
| Unknown | 13        | 0.78%   |
| 10      | 11        | 0.66%   |
| 3       | 7         | 0.42%   |
| 32      | 5         | 0.3%    |
| 24      | 4         | 0.24%   |
| 28      | 2         | 0.12%   |
| 20      | 2         | 0.12%   |
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
| 1       | 1610      | 97.28%  |
| 2       | 33        | 1.99%   |
| Unknown | 12        | 0.73%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1322      | 79.45%  |
| 1       | 327       | 19.65%  |
| Unknown | 13        | 0.78%   |
| 4       | 2         | 0.12%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1603      | 96.98%  |
| 32-bit         | 35        | 2.12%   |
| Unknown        | 15        | 0.91%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 322       | 18.44%  |
| 0x906ea    | 74        | 4.24%   |
| 0x08701021 | 67        | 3.84%   |
| 0x506e3    | 55        | 3.15%   |
| 0x306a9    | 50        | 2.86%   |
| 0x306c3    | 49        | 2.81%   |
| 0x806ec    | 47        | 2.69%   |
| 0x0a50000c | 47        | 2.69%   |
| 0x806c1    | 41        | 2.35%   |
| 0x0800820d | 41        | 2.35%   |
| 0x906e9    | 40        | 2.29%   |
| 0x806ea    | 36        | 2.06%   |
| 0x206a7    | 35        | 2%      |
| 0x08701013 | 35        | 2%      |
| 0x08600106 | 34        | 1.95%   |
| 0x0a201016 | 29        | 1.66%   |
| 0x806e9    | 28        | 1.6%    |
| 0x906ed    | 26        | 1.49%   |
| 0x0a601203 | 24        | 1.37%   |
| 0x08108109 | 21        | 1.2%    |
| 0x08001138 | 21        | 1.2%    |
| 0xa0652    | 20        | 1.15%   |
| 0x0a201009 | 20        | 1.15%   |
| 0x806d1    | 19        | 1.09%   |
| 0x40651    | 19        | 1.09%   |
| 0x0a20120a | 19        | 1.09%   |
| 0x906a3    | 18        | 1.03%   |
| 0x406e3    | 17        | 0.97%   |
| 0x1067a    | 17        | 0.97%   |
| 0x306d4    | 14        | 0.8%    |
| 0x08600103 | 14        | 0.8%    |
| 0x90672    | 13        | 0.74%   |
| 0x306f2    | 13        | 0.74%   |
| 0x206c2    | 13        | 0.74%   |
| 0x0a50000d | 13        | 0.74%   |
| 0x08608103 | 13        | 0.74%   |
| 0xa0671    | 12        | 0.69%   |
| 0x306e4    | 12        | 0.69%   |
| 0x0a404102 | 12        | 0.69%   |
| 0x08108102 | 12        | 0.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 305       | 18.3%   |
| Zen 2            | 188       | 11.28%  |
| Zen 3            | 144       | 8.64%   |
| Unknown          | 123       | 7.38%   |
| Haswell          | 99        | 5.94%   |
| Zen+             | 87        | 5.22%   |
| Skylake          | 83        | 4.98%   |
| IvyBridge        | 70        | 4.2%    |
| Alderlake Hybrid | 63        | 3.78%   |
| SandyBridge      | 54        | 3.24%   |
| TigerLake        | 47        | 2.82%   |
| Icelake          | 45        | 2.7%    |
| CometLake        | 44        | 2.64%   |
| Zen              | 43        | 2.58%   |
| Broadwell        | 32        | 1.92%   |
| Westmere         | 27        | 1.62%   |
| Silvermont       | 24        | 1.44%   |
| Penryn           | 24        | 1.44%   |
| K10              | 23        | 1.38%   |
| Piledriver       | 22        | 1.32%   |
| P6               | 18        | 1.08%   |
| Bonnell          | 17        | 1.02%   |
| Core             | 15        | 0.9%    |
| Goldmont plus    | 10        | 0.6%    |
| Nehalem          | 9         | 0.54%   |
| K8 Hammer        | 9         | 0.54%   |
| NetBurst         | 8         | 0.48%   |
| Steamroller      | 5         | 0.3%    |
| Bulldozer        | 5         | 0.3%    |
| Bobcat           | 5         | 0.3%    |
| Jaguar           | 4         | 0.24%   |
| Goldmont         | 4         | 0.24%   |
| Excavator        | 4         | 0.24%   |
| Tremont          | 2         | 0.12%   |
| Puma             | 2         | 0.12%   |
| K10 Llano        | 2         | 0.12%   |
| Gracemont        | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 688       | 34.98%  |
| Nvidia                           | 638       | 32.44%  |
| AMD                              | 588       | 29.89%  |
| ASPEED Technology                | 31        | 1.58%   |
| Matrox Electronics Systems       | 19        | 0.97%   |
| Loongson Technology              | 2         | 0.1%    |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 94        | 4.57%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 65        | 3.16%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 61        | 2.97%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 48        | 2.33%   |
| Intel UHD Graphics 620                                                      | 46        | 2.24%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 44        | 2.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 41        | 1.99%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 38        | 1.85%   |
| Intel HD Graphics 530                                                       | 34        | 1.65%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 33        | 1.6%    |
| ASPEED Technology ASPEED Graphics Family                                    | 31        | 1.51%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 30        | 1.46%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 29        | 1.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 28        | 1.36%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 27        | 1.31%   |
| AMD Raphael                                                                 | 25        | 1.22%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 24        | 1.17%   |
| Intel HD Graphics 620                                                       | 23        | 1.12%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 23        | 1.12%   |
| Intel HD Graphics 630                                                       | 21        | 1.02%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 20        | 0.97%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 20        | 0.97%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 20        | 0.97%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 18        | 0.88%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 17        | 0.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 17        | 0.83%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 17        | 0.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 16        | 0.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 16        | 0.78%   |
| AMD Rembrandt [Radeon 680M]                                                 | 16        | 0.78%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 16        | 0.78%   |
| AMD Lucienne                                                                | 16        | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 15        | 0.73%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 15        | 0.73%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 14        | 0.68%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 13        | 0.63%   |
| Intel HD Graphics 5500                                                      | 13        | 0.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 13        | 0.63%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 13        | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 12        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| 1 x AMD                   | 470       | 27.84%  |
| 1 x Intel                 | 411       | 24.35%  |
| 1 x Nvidia                | 355       | 21.03%  |
| Intel + Nvidia            | 228       | 13.51%  |
| AMD + Nvidia              | 51        | 3.02%   |
| 2 x AMD                   | 42        | 2.49%   |
| Other                     | 29        | 1.72%   |
| 1 x ASPEED                | 27        | 1.6%    |
| Intel + AMD               | 26        | 1.54%   |
| 1 x Matrox                | 16        | 0.95%   |
| 2 x Intel                 | 13        | 0.77%   |
| 2 x Nvidia                | 8         | 0.47%   |
| Nvidia + ASPEED           | 2         | 0.12%   |
| AMD + Matrox              | 2         | 0.12%   |
| AMD + Loongson Technology | 2         | 0.12%   |
| AMD + ASPEED              | 2         | 0.12%   |
| 1 x SiS                   | 1         | 0.06%   |
| Nvidia + Matrox           | 1         | 0.06%   |
| Intel + 2 x Nvidia        | 1         | 0.06%   |
| Intel + AMD + 1 x Nvidia  | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1170      | 68.62%  |
| Proprietary | 398       | 23.34%  |
| Unknown     | 137       | 8.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 804       | 46.29%  |
| 7.01-8.0   | 198       | 11.4%   |
| 0.01-0.5   | 177       | 10.19%  |
| 1.01-2.0   | 159       | 9.15%   |
| 3.01-4.0   | 139       | 8%      |
| 8.01-16.0  | 85        | 4.89%   |
| 0.51-1.0   | 82        | 4.72%   |
| 5.01-6.0   | 63        | 3.63%   |
| 2.01-3.0   | 16        | 0.92%   |
| 16.01-24.0 | 12        | 0.69%   |
| 4.01-5.0   | 2         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 201       | 10.58%  |
| AU Optronics            | 173       | 9.11%   |
| Dell                    | 160       | 8.42%   |
| BOE                     | 145       | 7.63%   |
| LG Display              | 121       | 6.37%   |
| Chimei Innolux          | 118       | 6.21%   |
| Goldstar                | 102       | 5.37%   |
| AOC                     | 63        | 3.32%   |
| BenQ                    | 61        | 3.21%   |
| Sharp                   | 60        | 3.16%   |
| Ancor Communications    | 59        | 3.11%   |
| Hewlett-Packard         | 58        | 3.05%   |
| Acer                    | 56        | 2.95%   |
| ASUSTek Computer        | 45        | 2.37%   |
| Lenovo                  | 40        | 2.11%   |
| Iiyama                  | 40        | 2.11%   |
| Philips                 | 38        | 2%      |
| ViewSonic               | 35        | 1.84%   |
| Apple                   | 33        | 1.74%   |
| Eizo                    | 19        | 1%      |
| Chi Mei Optoelectronics | 18        | 0.95%   |
| PANDA                   | 14        | 0.74%   |
| Gigabyte Technology     | 14        | 0.74%   |
| Unknown                 | 13        | 0.68%   |
| CSO                     | 13        | 0.68%   |
| LG Electronics          | 12        | 0.63%   |
| MSI                     | 10        | 0.53%   |
| Fujitsu Siemens         | 10        | 0.53%   |
| Unknown                 | 8         | 0.42%   |
| NEC Computers           | 7         | 0.37%   |
| Sony                    | 6         | 0.32%   |
| Mi                      | 6         | 0.32%   |
| InfoVision              | 6         | 0.32%   |
| Idek Iiyama             | 6         | 0.32%   |
| HannStar                | 6         | 0.32%   |
| Toshiba                 | 5         | 0.26%   |
| TMX                     | 5         | 0.26%   |
| Sceptre Tech            | 5         | 0.26%   |
| RTK                     | 4         | 0.21%   |
| Panasonic               | 4         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 10        | 0.5%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 9         | 0.45%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 9         | 0.45%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 8         | 0.4%    |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                 | 8         | 0.4%    |
| Unknown                                                               | 8         | 0.4%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 7         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch      | 7         | 0.35%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 7         | 0.35%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.35%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 6         | 0.3%    |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                 | 6         | 0.3%    |
| Fujitsu Siemens P24W-6 IPS FUS07EA 1920x1200 518x324mm 24.1-inch      | 6         | 0.3%    |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 6         | 0.3%    |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 6         | 0.3%    |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 5         | 0.25%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 5         | 0.25%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch            | 5         | 0.25%   |
| Dell U2715H DELD066 2560x1440 600x340mm 27.2-inch                     | 5         | 0.25%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                     | 5         | 0.25%   |
| BOE LCD Monitor BOE0BCA 2256x1504 285x190mm 13.5-inch                 | 5         | 0.25%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                    | 5         | 0.25%   |
| ASUSTek Computer VG27A AUS2722 2560x1440 597x336mm 27.0-inch          | 5         | 0.25%   |
| TMX LCD Monitor TMX1560 1920x1080 344x194mm 15.5-inch                 | 4         | 0.2%    |
| Sceptre Tech C305W-2560UN SPT0C0D 2560x1080 690x291mm 29.5-inch       | 4         | 0.2%    |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 4         | 0.2%    |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 4         | 0.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4         | 0.2%    |
| MSI G273Q MSI3CA8 3840x2160 596x335mm 26.9-inch                       | 4         | 0.2%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 4         | 0.2%    |
| HVR HTC-VIVE HVRAA01 2160x1200                                        | 4         | 0.2%    |
| Hewlett-Packard 22es HWP331B 1920x1080 476x268mm 21.5-inch            | 4         | 0.2%    |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 4         | 0.2%    |
| Envision Peripherals LCD2361 ENV2361 1920x1080 521x293mm 23.5-inch    | 4         | 0.2%    |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                     | 4         | 0.2%    |
| Dell P2418D DELD0C2 2560x1440 526x296mm 23.8-inch                     | 4         | 0.2%    |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                 | 4         | 0.2%    |
| BenQ PD2700U BNQ802E 3840x2160 597x336mm 27.0-inch                    | 4         | 0.2%    |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 4         | 0.2%    |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 4         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 824       | 45.91%  |
| 3840x2160 (4K)     | 182       | 10.14%  |
| 2560x1440 (QHD)    | 165       | 9.19%   |
| 1366x768 (WXGA)    | 97        | 5.4%    |
| 1920x1200 (WUXGA)  | 65        | 3.62%   |
| 1280x1024 (SXGA)   | 48        | 2.67%   |
| 3440x1440          | 42        | 2.34%   |
| 1680x1050 (WSXGA+) | 41        | 2.28%   |
| 1600x900 (HD+)     | 35        | 1.95%   |
| Unknown            | 33        | 1.84%   |
| 2560x1600          | 28        | 1.56%   |
| 2560x1080          | 26        | 1.45%   |
| 1440x900 (WXGA+)   | 25        | 1.39%   |
| 3840x2400          | 20        | 1.11%   |
| 3840x1080          | 18        | 1%      |
| 1280x800 (WXGA)    | 14        | 0.78%   |
| 2880x1800          | 9         | 0.5%    |
| 2256x1504          | 8         | 0.45%   |
| 1600x1200          | 8         | 0.45%   |
| 1024x600           | 8         | 0.45%   |
| 2288x1287          | 6         | 0.33%   |
| 3840x1200          | 5         | 0.28%   |
| 3200x2000          | 5         | 0.28%   |
| 2160x1440          | 5         | 0.28%   |
| 2048x1152          | 5         | 0.28%   |
| 3200x1800 (QHD+)   | 4         | 0.22%   |
| 2160x1200          | 4         | 0.22%   |
| 1920x540           | 4         | 0.22%   |
| 1360x768           | 4         | 0.22%   |
| 1024x768 (XGA)     | 4         | 0.22%   |
| 7680x2160          | 3         | 0.17%   |
| 3456x2160          | 3         | 0.17%   |
| 1400x1050          | 3         | 0.17%   |
| 1280x960           | 3         | 0.17%   |
| 1280x854           | 3         | 0.17%   |
| 800x1280           | 2         | 0.11%   |
| 5760x2160          | 2         | 0.11%   |
| 3072x1920          | 2         | 0.11%   |
| 2240x1400          | 2         | 0.11%   |
| 1920x1280          | 2         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 338       | 17.95%  |
| 27      | 246       | 13.06%  |
| 24      | 176       | 9.35%   |
| 23      | 149       | 7.91%   |
| 13      | 149       | 7.91%   |
| 14      | 127       | 6.74%   |
| Unknown | 102       | 5.42%   |
| 21      | 100       | 5.31%   |
| 17      | 98        | 5.2%    |
| 34      | 58        | 3.08%   |
| 19      | 42        | 2.23%   |
| 31      | 37        | 1.96%   |
| 16      | 32        | 1.7%    |
| 12      | 31        | 1.65%   |
| 22      | 28        | 1.49%   |
| 25      | 17        | 0.9%    |
| 20      | 14        | 0.74%   |
| 18      | 13        | 0.69%   |
| 11      | 13        | 0.69%   |
| 84      | 12        | 0.64%   |
| 32      | 12        | 0.64%   |
| 40      | 9         | 0.48%   |
| 54      | 7         | 0.37%   |
| 48      | 7         | 0.37%   |
| 26      | 7         | 0.37%   |
| 10      | 7         | 0.37%   |
| 142     | 6         | 0.32%   |
| 72      | 6         | 0.32%   |
| 49      | 5         | 0.27%   |
| 29      | 5         | 0.27%   |
| 28      | 4         | 0.21%   |
| 42      | 3         | 0.16%   |
| 8       | 3         | 0.16%   |
| 58      | 2         | 0.11%   |
| 7       | 2         | 0.11%   |
| 75      | 1         | 0.05%   |
| 74      | 1         | 0.05%   |
| 65      | 1         | 0.05%   |
| 60      | 1         | 0.05%   |
| 52      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 567       | 31.21%  |
| 501-600        | 497       | 27.35%  |
| 401-500        | 173       | 9.52%   |
| 201-300        | 143       | 7.87%   |
| 351-400        | 108       | 5.94%   |
| Unknown        | 102       | 5.61%   |
| 601-700        | 81        | 4.46%   |
| 701-800        | 72        | 3.96%   |
| 1001-1500      | 26        | 1.43%   |
| 1501-2000      | 20        | 1.1%    |
| 801-900        | 12        | 0.66%   |
| More than 2000 | 6         | 0.33%   |
| 101-200        | 4         | 0.22%   |
| 901-1000       | 4         | 0.22%   |
| 1-100          | 2         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1149      | 70.06%  |
| 16/10   | 228       | 13.9%   |
| Unknown | 85        | 5.18%   |
| 21/9    | 62        | 3.78%   |
| 5/4     | 45        | 2.74%   |
| 3/2     | 26        | 1.59%   |
| 4/3     | 16        | 0.98%   |
| 32/9    | 13        | 0.79%   |
| 1.00    | 7         | 0.43%   |
| 6/5     | 3         | 0.18%   |
| 3.40    | 1         | 0.06%   |
| 3.20    | 1         | 0.06%   |
| 0.89    | 1         | 0.06%   |
| 0.67    | 1         | 0.06%   |
| 0.62    | 1         | 0.06%   |
| 0.31    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 336       | 18.12%  |
| 201-250        | 334       | 18.02%  |
| 301-350        | 252       | 13.59%  |
| 81-90          | 201       | 10.84%  |
| 351-500        | 110       | 5.93%   |
| Unknown        | 102       | 5.5%    |
| 251-300        | 88        | 4.75%   |
| 151-200        | 83        | 4.48%   |
| 71-80          | 74        | 3.99%   |
| 121-130        | 66        | 3.56%   |
| More than 1000 | 41        | 2.21%   |
| 141-150        | 35        | 1.89%   |
| 111-120        | 33        | 1.78%   |
| 61-70          | 28        | 1.51%   |
| 501-1000       | 28        | 1.51%   |
| 51-60          | 15        | 0.81%   |
| 131-140        | 9         | 0.49%   |
| 41-50          | 7         | 0.38%   |
| 1-40           | 6         | 0.32%   |
| 91-100         | 6         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 550       | 31.02%  |
| 121-160       | 514       | 28.99%  |
| 101-120       | 327       | 18.44%  |
| 161-240       | 170       | 9.59%   |
| Unknown       | 102       | 5.75%   |
| More than 240 | 78        | 4.4%    |
| 1-50          | 32        | 1.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1175      | 67.61%  |
| 2     | 322       | 18.53%  |
| 0     | 162       | 9.32%   |
| 3     | 65        | 3.74%   |
| 4     | 14        | 0.81%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1029      | 42.5%   |
| Realtek Semiconductor             | 786       | 32.47%  |
| Qualcomm Atheros                  | 148       | 6.11%   |
| Broadcom                          | 98        | 4.05%   |
| MediaTek                          | 62        | 2.56%   |
| ASIX Electronics                  | 25        | 1.03%   |
| Aquantia                          | 21        | 0.87%   |
| Nvidia                            | 20        | 0.83%   |
| Marvell Technology Group          | 17        | 0.7%    |
| Lenovo                            | 14        | 0.58%   |
| Qualcomm                          | 12        | 0.5%    |
| TP-Link                           | 11        | 0.45%   |
| Broadcom Limited                  | 11        | 0.45%   |
| Apple                             | 10        | 0.41%   |
| Sierra Wireless                   | 9         | 0.37%   |
| Qualcomm Atheros Communications   | 9         | 0.37%   |
| Dell                              | 9         | 0.37%   |
| Xiaomi                            | 8         | 0.33%   |
| Microsoft                         | 8         | 0.33%   |
| Ralink Technology                 | 7         | 0.29%   |
| Samsung Electronics               | 6         | 0.25%   |
| Ralink                            | 6         | 0.25%   |
| Fibocom                           | 5         | 0.21%   |
| Ericsson Business Mobile Networks | 5         | 0.21%   |
| NetGear                           | 4         | 0.17%   |
| Huawei Technologies               | 4         | 0.17%   |
| D-Link System                     | 4         | 0.17%   |
| Standard Microsystems             | 3         | 0.12%   |
| Microchip Technology              | 3         | 0.12%   |
| ICS Advent                        | 3         | 0.12%   |
| D-Link                            | 3         | 0.12%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.08%   |
| U-Blox                            | 2         | 0.08%   |
| Texas Instruments                 | 2         | 0.08%   |
| STMicroelectronics                | 2         | 0.08%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.08%   |
| Sigma Designs                     | 2         | 0.08%   |
| QLogic                            | 2         | 0.08%   |
| Prusa                             | 2         | 0.08%   |
| OpenMoko                          | 2         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 554       | 19%     |
| Intel Wi-Fi 6 AX200                                               | 167       | 5.73%   |
| Intel I211 Gigabit Network Connection                             | 124       | 4.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 89        | 3.05%   |
| Intel Wireless 8265 / 8275                                        | 65        | 2.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 61        | 2.09%   |
| Intel Ethernet Controller I225-V                                  | 47        | 1.61%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 46        | 1.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 46        | 1.58%   |
| Intel I210 Gigabit Network Connection                             | 39        | 1.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 37        | 1.27%   |
| Intel Wi-Fi 6 AX201                                               | 35        | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 33        | 1.13%   |
| Intel Ethernet Connection (2) I219-V                              | 33        | 1.13%   |
| Intel Wireless-AC 9260                                            | 29        | 0.99%   |
| Intel Wireless 8260                                               | 29        | 0.99%   |
| Intel Wireless 7265                                               | 29        | 0.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 0.96%   |
| Intel Ethernet Connection (7) I219-V                              | 28        | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 28        | 0.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 27        | 0.93%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 25        | 0.86%   |
| Intel 82574L Gigabit Network Connection                           | 25        | 0.86%   |
| Intel Wireless 7260                                               | 24        | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 24        | 0.82%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 24        | 0.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 23        | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 23        | 0.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 23        | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                             | 21        | 0.72%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 20        | 0.69%   |
| Intel Wireless 3165                                               | 19        | 0.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 19        | 0.65%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 18        | 0.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 18        | 0.62%   |
| Intel I350 Gigabit Network Connection                             | 17        | 0.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 16        | 0.55%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 14        | 0.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 13        | 0.45%   |
| Intel Ethernet Connection I217-LM                                 | 13        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 733       | 60.63%  |
| Realtek Semiconductor                 | 138       | 11.41%  |
| Qualcomm Atheros                      | 113       | 9.35%   |
| Broadcom                              | 64        | 5.29%   |
| MediaTek                              | 60        | 4.96%   |
| Qualcomm                              | 12        | 0.99%   |
| TP-Link                               | 9         | 0.74%   |
| Sierra Wireless                       | 9         | 0.74%   |
| Qualcomm Atheros Communications       | 9         | 0.74%   |
| Microsoft                             | 8         | 0.66%   |
| Broadcom Limited                      | 8         | 0.66%   |
| Ralink Technology                     | 7         | 0.58%   |
| Dell                                  | 7         | 0.58%   |
| Ralink                                | 6         | 0.5%    |
| Fibocom                               | 5         | 0.41%   |
| NetGear                               | 4         | 0.33%   |
| D-Link System                         | 3         | 0.25%   |
| D-Link                                | 3         | 0.25%   |
| Ericsson Business Mobile Networks     | 2         | 0.17%   |
| Wilocity                              | 1         | 0.08%   |
| Texas Instruments                     | 1         | 0.08%   |
| Senao                                 | 1         | 0.08%   |
| Quectel Wireless Solutions            | 1         | 0.08%   |
| Edimax Technology                     | 1         | 0.08%   |
| Cisco Aironet Wireless Communications | 1         | 0.08%   |
| BUFFALO                               | 1         | 0.08%   |
| AVM                                   | 1         | 0.08%   |
| ASUSTek Computer                      | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 167       | 13.76%  |
| Intel Wireless 8265 / 8275                                              | 65        | 5.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 46        | 3.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 46        | 3.79%   |
| Intel Wi-Fi 6 AX201                                                     | 35        | 2.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 33        | 2.72%   |
| Intel Wireless-AC 9260                                                  | 29        | 2.39%   |
| Intel Wireless 8260                                                     | 29        | 2.39%   |
| Intel Wireless 7265                                                     | 29        | 2.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 28        | 2.31%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 27        | 2.22%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 25        | 2.06%   |
| Intel Wireless 7260                                                     | 24        | 1.98%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 24        | 1.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 23        | 1.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 23        | 1.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 23        | 1.89%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 20        | 1.65%   |
| Intel Wireless 3165                                                     | 19        | 1.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 19        | 1.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 18        | 1.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 18        | 1.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 16        | 1.32%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 14        | 1.15%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 1.07%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 12        | 0.99%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter            | 12        | 0.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 0.91%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 11        | 0.91%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 11        | 0.91%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 10        | 0.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 9         | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 9         | 0.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 0.74%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 8         | 0.66%   |
| Qualcomm Atheros AR9271 802.11n                                         | 8         | 0.66%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 8         | 0.66%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 8         | 0.66%   |
| Intel Centrino Advanced-N 6235                                          | 8         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 740       | 47.07%  |
| Intel                            | 580       | 36.9%   |
| Qualcomm Atheros                 | 48        | 3.05%   |
| Broadcom                         | 44        | 2.8%    |
| ASIX Electronics                 | 25        | 1.59%   |
| Aquantia                         | 21        | 1.34%   |
| Nvidia                           | 20        | 1.27%   |
| Marvell Technology Group         | 17        | 1.08%   |
| Lenovo                           | 14        | 0.89%   |
| Apple                            | 10        | 0.64%   |
| Xiaomi                           | 8         | 0.51%   |
| Samsung Electronics              | 4         | 0.25%   |
| Standard Microsystems            | 3         | 0.19%   |
| Microchip Technology             | 3         | 0.19%   |
| ICS Advent                       | 3         | 0.19%   |
| Broadcom Limited                 | 3         | 0.19%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.13%   |
| TP-Link                          | 2         | 0.13%   |
| Silicon Integrated Systems [SiS] | 2         | 0.13%   |
| QLogic                           | 2         | 0.13%   |
| Loongson Technology              | 2         | 0.13%   |
| Huawei Technologies              | 2         | 0.13%   |
| Google                           | 2         | 0.13%   |
| DisplayLink                      | 2         | 0.13%   |
| 3Com                             | 2         | 0.13%   |
| NetXen Incorporated              | 1         | 0.06%   |
| Mellanox Technologies            | 1         | 0.06%   |
| MediaTek                         | 1         | 0.06%   |
| JMicron Technology               | 1         | 0.06%   |
| Insyde Software                  | 1         | 0.06%   |
| HMD Global                       | 1         | 0.06%   |
| Hewlett-Packard                  | 1         | 0.06%   |
| Gemtek                           | 1         | 0.06%   |
| Davicom Semiconductor            | 1         | 0.06%   |
| D-Link System                    | 1         | 0.06%   |
| American Megatrends              | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 554       | 33.54%  |
| Intel I211 Gigabit Network Connection                                         | 124       | 7.51%   |
| Realtek RTL8125 2.5GbE Controller                                             | 89        | 5.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 61        | 3.69%   |
| Intel Ethernet Controller I225-V                                              | 47        | 2.85%   |
| Intel I210 Gigabit Network Connection                                         | 39        | 2.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 37        | 2.24%   |
| Intel Ethernet Connection (2) I219-V                                          | 33        | 2%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 28        | 1.69%   |
| Intel Ethernet Connection (7) I219-V                                          | 28        | 1.69%   |
| Intel 82574L Gigabit Network Connection                                       | 25        | 1.51%   |
| Intel Ethernet Connection (2) I219-LM                                         | 24        | 1.45%   |
| Intel Ethernet Connection (4) I219-LM                                         | 21        | 1.27%   |
| Intel I350 Gigabit Network Connection                                         | 17        | 1.03%   |
| Intel Ethernet Connection I217-LM                                             | 13        | 0.79%   |
| Intel Ethernet Connection (2) I218-V                                          | 13        | 0.79%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 12        | 0.73%   |
| Intel Ethernet Connection (4) I219-V                                          | 12        | 0.73%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 12        | 0.73%   |
| Intel Ethernet Connection (7) I219-LM                                         | 11        | 0.67%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 11        | 0.67%   |
| Intel 82579V Gigabit Network Connection                                       | 11        | 0.67%   |
| Intel Ethernet Connection (6) I219-V                                          | 10        | 0.61%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 9         | 0.54%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 9         | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 8         | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 7         | 0.42%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 7         | 0.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 7         | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 7         | 0.42%   |
| Nvidia MCP77 Ethernet                                                         | 7         | 0.42%   |
| Intel Ethernet Connection I218-LM                                             | 7         | 0.42%   |
| Intel Ethernet Connection (5) I219-LM                                         | 7         | 0.42%   |
| Intel 82577LM Gigabit Network Connection                                      | 7         | 0.42%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 7         | 0.42%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 7         | 0.42%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 6         | 0.36%   |
| Lenovo USB-C Dock Ethernet                                                    | 6         | 0.36%   |
| Intel Ethernet Connection I219-LM                                             | 6         | 0.36%   |
| Intel Ethernet Connection I217-V                                              | 6         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1428      | 54.55%  |
| WiFi     | 1142      | 43.62%  |
| Modem    | 46        | 1.76%   |
| Unknown  | 2         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 937       | 54.19%  |
| WiFi     | 792       | 45.81%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 838       | 50.09%  |
| 1     | 659       | 39.39%  |
| 3     | 93        | 5.56%   |
| 0     | 34        | 2.03%   |
| 4     | 27        | 1.61%   |
| 5     | 9         | 0.54%   |
| 6     | 7         | 0.42%   |
| 8     | 2         | 0.12%   |
| 7     | 2         | 0.12%   |
| 12    | 1         | 0.06%   |
| 9     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1384      | 80.94%  |
| Yes  | 326       | 19.06%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 656       | 60.52%  |
| Realtek Semiconductor           | 86        | 7.93%   |
| Cambridge Silicon Radio         | 61        | 5.63%   |
| IMC Networks                    | 38        | 3.51%   |
| Apple                           | 37        | 3.41%   |
| Foxconn / Hon Hai               | 32        | 2.95%   |
| Broadcom                        | 32        | 2.95%   |
| Qualcomm Atheros Communications | 26        | 2.4%    |
| Lite-On Technology              | 24        | 2.21%   |
| MediaTek                        | 20        | 1.85%   |
| ASUSTek Computer                | 20        | 1.85%   |
| Dell                            | 9         | 0.83%   |
| Realtek                         | 8         | 0.74%   |
| USI                             | 6         | 0.55%   |
| Toshiba                         | 5         | 0.46%   |
| HTC (High Tech Computer)        | 4         | 0.37%   |
| Hewlett-Packard                 | 4         | 0.37%   |
| Foxconn International           | 3         | 0.28%   |
| Belkin Components               | 3         | 0.28%   |
| Edimax Technology               | 2         | 0.18%   |
| Ralink Technology               | 1         | 0.09%   |
| Opticis                         | 1         | 0.09%   |
| Dynex                           | 1         | 0.09%   |
| Chicony Electronics             | 1         | 0.09%   |
| Askey Computer                  | 1         | 0.09%   |
| Alps Electric                   | 1         | 0.09%   |
| Actiontec Electronics           | 1         | 0.09%   |
| Actions                         | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                | 167       | 15.39%  |
| Intel Bluetooth wireless interface                                   | 166       | 15.3%   |
| Intel Bluetooth Device                                               | 138       | 12.72%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 86        | 7.93%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 61        | 5.62%   |
| Realtek Bluetooth Radio                                              | 58        | 5.35%   |
| Intel AX210 Bluetooth                                                | 43        | 3.96%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 30        | 2.76%   |
| MediaTek Wireless_Device                                             | 20        | 1.84%   |
| IMC Networks Wireless_Device                                         | 17        | 1.57%   |
| Apple Bluetooth Host Controller                                      | 17        | 1.57%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 16        | 1.47%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 16        | 1.47%   |
| IMC Networks Bluetooth Radio                                         | 12        | 1.11%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 10        | 0.92%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                         | 9         | 0.83%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 9         | 0.83%   |
| Realtek Bluetooth Radio                                              | 8         | 0.74%   |
| Foxconn / Hon Hai Wireless_Device                                    | 8         | 0.74%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 8         | 0.74%   |
| Apple Bluetooth USB Host Controller                                  | 8         | 0.74%   |
| Qualcomm Atheros  Bluetooth Device                                   | 7         | 0.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 7         | 0.65%   |
| Lite-On Bluetooth Device                                             | 7         | 0.65%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 7         | 0.65%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 7         | 0.65%   |
| USI Bluetooth Device                                                 | 6         | 0.55%   |
| Realtek RTL8723B Bluetooth                                           | 6         | 0.55%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 6         | 0.55%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                              | 5         | 0.46%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 5         | 0.46%   |
| IMC Networks Bluetooth Device                                        | 5         | 0.46%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 4         | 0.37%   |
| Lite-On Wireless_Device                                              | 4         | 0.37%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 4         | 0.37%   |
| Dell DW375 Bluetooth Module                                          | 4         | 0.37%   |
| Broadcom HP Portable SoftSailing                                     | 4         | 0.37%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 4         | 0.37%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 4         | 0.37%   |
| Apple Bluetooth HCI                                                  | 4         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 907       | 35.24%  |
| AMD                                  | 675       | 26.22%  |
| Nvidia                               | 503       | 19.54%  |
| C-Media Electronics                  | 67        | 2.6%    |
| Logitech                             | 35        | 1.36%   |
| ASUSTek Computer                     | 24        | 0.93%   |
| Creative Labs                        | 23        | 0.89%   |
| SteelSeries ApS                      | 21        | 0.82%   |
| Creative Technology                  | 17        | 0.66%   |
| Realtek Semiconductor                | 16        | 0.62%   |
| Lenovo                               | 16        | 0.62%   |
| Texas Instruments                    | 15        | 0.58%   |
| Kingston Technology                  | 14        | 0.54%   |
| Razer USA                            | 13        | 0.51%   |
| JMTek                                | 11        | 0.43%   |
| Plantronics                          | 10        | 0.39%   |
| Focusrite-Novation                   | 10        | 0.39%   |
| Thesycon Systemsoftware & Consulting | 8         | 0.31%   |
| Micro Star International             | 8         | 0.31%   |
| GYROCOM C&C                          | 8         | 0.31%   |
| GN Netcom                            | 8         | 0.31%   |
| Blue Microphones                     | 8         | 0.31%   |
| Generalplus Technology               | 7         | 0.27%   |
| AudioQuest                           | 7         | 0.27%   |
| DSEA A/S                             | 6         | 0.23%   |
| Corsair                              | 6         | 0.23%   |
| BEHRINGER International              | 6         | 0.23%   |
| Samson Technologies                  | 5         | 0.19%   |
| RODE Microphones                     | 5         | 0.19%   |
| Dell                                 | 5         | 0.19%   |
| Sony                                 | 4         | 0.16%   |
| Solid State Logic                    | 4         | 0.16%   |
| SAVITECH                             | 4         | 0.16%   |
| No brand                             | 4         | 0.16%   |
| Hewlett-Packard                      | 4         | 0.16%   |
| Yamaha                               | 3         | 0.12%   |
| Trust                                | 3         | 0.12%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.12%   |
| Microsoft                            | 3         | 0.12%   |
| FiiO Electronics Technology          | 3         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 228       | 7.29%   |
| AMD Starship/Matisse HD Audio Controller                                   | 180       | 5.75%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 130       | 4.15%   |
| Intel Cannon Lake PCH cAVS                                                 | 102       | 3.26%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 98        | 3.13%   |
| Intel Sunrise Point-LP HD Audio                                            | 96        | 3.07%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 77        | 2.46%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 65        | 2.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 59        | 1.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 54        | 1.73%   |
| AMD Navi 10 HDMI Audio                                                     | 51        | 1.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 47        | 1.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 47        | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 45        | 1.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 44        | 1.41%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 43        | 1.37%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 38        | 1.21%   |
| Nvidia GA104 High Definition Audio Controller                              | 37        | 1.18%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 35        | 1.12%   |
| Nvidia TU106 High Definition Audio Controller                              | 35        | 1.12%   |
| Nvidia GP107GL High Definition Audio Controller                            | 35        | 1.12%   |
| Nvidia GP106 High Definition Audio Controller                              | 34        | 1.09%   |
| Nvidia GP104 High Definition Audio Controller                              | 33        | 1.05%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 33        | 1.05%   |
| Intel Comet Lake PCH cAVS                                                  | 31        | 0.99%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 31        | 0.99%   |
| Nvidia GA106 High Definition Audio Controller                              | 30        | 0.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 30        | 0.96%   |
| Intel Comet Lake PCH-LP cAVS                                               | 30        | 0.96%   |
| Nvidia TU104 HD Audio Controller                                           | 29        | 0.93%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 28        | 0.89%   |
| Nvidia TU116 High Definition Audio Controller                              | 27        | 0.86%   |
| Intel 200 Series PCH HD Audio                                              | 26        | 0.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 24        | 0.77%   |
| Intel CM238 HD Audio Controller                                            | 24        | 0.77%   |
| Nvidia GA102 High Definition Audio Controller                              | 22        | 0.7%    |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 22        | 0.7%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 21        | 0.67%   |
| Nvidia GM206 High Definition Audio Controller                              | 20        | 0.64%   |
| Intel Haswell-ULT HD Audio Controller                                      | 20        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 352       | 20.07%  |
| Kingston                     | 239       | 13.63%  |
| SK hynix                     | 233       | 13.28%  |
| Micron Technology            | 168       | 9.58%   |
| Corsair                      | 163       | 9.29%   |
| G.Skill                      | 144       | 8.21%   |
| Crucial                      | 139       | 7.92%   |
| Unknown                      | 131       | 7.47%   |
| A-DATA Technology            | 21        | 1.2%    |
| Ramaxel Technology           | 20        | 1.14%   |
| Team                         | 17        | 0.97%   |
| Patriot                      | 15        | 0.86%   |
| Elpida                       | 15        | 0.86%   |
| Unknown                      | 15        | 0.86%   |
| Transcend                    | 11        | 0.63%   |
| Nanya Technology             | 10        | 0.57%   |
| GOODRAM                      | 8         | 0.46%   |
| Unknown (ABCD)               | 4         | 0.23%   |
| AMD                          | 4         | 0.23%   |
| Timetec                      | 3         | 0.17%   |
| Apacer                       | 3         | 0.17%   |
| Toshiba                      | 2         | 0.11%   |
| KLEVV                        | 2         | 0.11%   |
| Chun Well                    | 2         | 0.11%   |
| Avant                        | 2         | 0.11%   |
| Unknown (0x5D00000000000000) | 1         | 0.06%   |
| Unknown (0x0B92)             | 1         | 0.06%   |
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

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown                                                     | 15        | 0.8%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 14        | 0.75%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 14        | 0.75%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s       | 14        | 0.75%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s      | 13        | 0.7%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 12        | 0.64%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 12        | 0.64%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 12        | 0.64%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 12        | 0.64%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s        | 12        | 0.64%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 11        | 0.59%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 10        | 0.54%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 9         | 0.48%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 9         | 0.48%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s      | 9         | 0.48%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s    | 9         | 0.48%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 9         | 0.48%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s      | 9         | 0.48%   |
| Unknown RAM Module 1GB SODIMM DDR                           | 8         | 0.43%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s      | 8         | 0.43%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 8         | 0.43%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s      | 8         | 0.43%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s      | 8         | 0.43%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 8         | 0.43%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 8         | 0.43%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s           | 8         | 0.43%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s         | 8         | 0.43%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s         | 8         | 0.43%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s       | 8         | 0.43%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s     | 7         | 0.38%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s       | 7         | 0.38%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s      | 7         | 0.38%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 6         | 0.32%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 6         | 0.32%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 6         | 0.32%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s       | 6         | 0.32%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 6         | 0.32%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s       | 6         | 0.32%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM 6400MT/s             | 6         | 0.32%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s      | 6         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 956       | 61.4%   |
| DDR3    | 326       | 20.94%  |
| DDR5    | 58        | 3.73%   |
| DDR2    | 51        | 3.28%   |
| LPDDR4  | 46        | 2.95%   |
| Unknown | 32        | 2.06%   |
| LPDDR3  | 27        | 1.73%   |
| LPDDR5  | 23        | 1.48%   |
| SDRAM   | 19        | 1.22%   |
| DDR     | 16        | 1.03%   |
| DRAM    | 3         | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 728       | 46.73%  |
| SODIMM       | 724       | 46.47%  |
| Row Of Chips | 97        | 6.23%   |
| Chip         | 6         | 0.39%   |
| Unknown      | 2         | 0.13%   |
| RIMM         | 1         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 681       | 40.54%  |
| 16384 | 436       | 25.95%  |
| 4096  | 266       | 15.83%  |
| 32768 | 142       | 8.45%   |
| 2048  | 103       | 6.13%   |
| 1024  | 39        | 2.32%   |
| 512   | 8         | 0.48%   |
| 256   | 5         | 0.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 332       | 19.71%  |
| 2667    | 235       | 13.95%  |
| 1600    | 200       | 11.88%  |
| 2400    | 105       | 6.24%   |
| 3600    | 94        | 5.58%   |
| 2133    | 84        | 4.99%   |
| 1333    | 73        | 4.33%   |
| 667     | 34        | 2.02%   |
| 4800    | 32        | 1.9%    |
| 3733    | 32        | 1.9%    |
| 800     | 32        | 1.9%    |
| 6400    | 31        | 1.84%   |
| 3000    | 29        | 1.72%   |
| Unknown | 28        | 1.66%   |
| 4267    | 27        | 1.6%    |
| 3400    | 26        | 1.54%   |
| 2933    | 23        | 1.37%   |
| 1867    | 22        | 1.31%   |
| 2666    | 18        | 1.07%   |
| 1334    | 18        | 1.07%   |
| 3800    | 16        | 0.95%   |
| 1866    | 14        | 0.83%   |
| 3466    | 12        | 0.71%   |
| 3266    | 12        | 0.71%   |
| 3866    | 11        | 0.65%   |
| 8400    | 10        | 0.59%   |
| 5600    | 10        | 0.59%   |
| 1067    | 9         | 0.53%   |
| 1066    | 9         | 0.53%   |
| 4000    | 8         | 0.48%   |
| 3533    | 8         | 0.48%   |
| 3666    | 7         | 0.42%   |
| 3534    | 7         | 0.42%   |
| 6000    | 6         | 0.36%   |
| 2800    | 6         | 0.36%   |
| 400     | 6         | 0.36%   |
| 4266    | 5         | 0.3%    |
| 5200    | 4         | 0.24%   |
| 3933    | 4         | 0.24%   |
| 3333    | 4         | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 13        | 40.63%  |
| Seiko Epson           | 4         | 12.5%   |
| Samsung Electronics   | 4         | 12.5%   |
| Canon                 | 4         | 12.5%   |
| Brother Industries    | 4         | 12.5%   |
| Xiaomi                | 1         | 3.13%   |
| Lexmark International | 1         | 3.13%   |
| Konica Minolta        | 1         | 3.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| HP LaserJet M14-M17                   | 2         | 6.25%   |
| Canon LiDE 400                        | 2         | 6.25%   |
| Xiaomi MiMouse 2                      | 1         | 3.13%   |
| Seiko Epson XP-4200 Series            | 1         | 3.13%   |
| Seiko Epson WF-3520 Series            | 1         | 3.13%   |
| Seiko Epson WF-2510 Series            | 1         | 3.13%   |
| Seiko Epson AL-M310DN                 | 1         | 3.13%   |
| Samsung ML-191x/ML-252x Laser Printer | 1         | 3.13%   |
| Samsung ML-1630 Series                | 1         | 3.13%   |
| Samsung CLP-325 Color Laser Printer   | 1         | 3.13%   |
| Samsung C460 Series                   | 1         | 3.13%   |
| Lexmark International Lexmark E352dn  | 1         | 3.13%   |
| Konica Minolta magicolor 1680MF scan  | 1         | 3.13%   |
| HP PhotoSmart 130                     | 1         | 3.13%   |
| HP LaserJet P2055 series              | 1         | 3.13%   |
| HP LaserJet 3200                      | 1         | 3.13%   |
| HP LaserJet 1020                      | 1         | 3.13%   |
| HP LaserJet 1018                      | 1         | 3.13%   |
| HP LaserJet 1010                      | 1         | 3.13%   |
| HP Deskjet D1500 series               | 1         | 3.13%   |
| HP Deskjet 9800                       | 1         | 3.13%   |
| HP DeskJet 5440                       | 1         | 3.13%   |
| HP DeskJet 3630 series                | 1         | 3.13%   |
| HP Deskjet 2050 J510                  | 1         | 3.13%   |
| Canon PIXMA MG2900 Series             | 1         | 3.13%   |
| Canon CanoScan LiDE 300               | 1         | 3.13%   |
| Brother QL-500 label printer          | 1         | 3.13%   |
| Brother MFC-L2700DW                   | 1         | 3.13%   |
| Brother MFC-9340CDW                   | 1         | 3.13%   |
| Brother MFC-9130CW                    | 1         | 3.13%   |

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
| Chicony Electronics                    | 183       | 20.13%  |
| Logitech                               | 117       | 12.87%  |
| IMC Networks                           | 98        | 10.78%  |
| Microdia                               | 79        | 8.69%   |
| Realtek Semiconductor                  | 60        | 6.6%    |
| Bison Electronics                      | 52        | 5.72%   |
| Sunplus Innovation Technology          | 46        | 5.06%   |
| Quanta                                 | 41        | 4.51%   |
| Lite-On Technology                     | 26        | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) | 25        | 2.75%   |
| Luxvisions Innotech Limited            | 20        | 2.2%    |
| Apple                                  | 20        | 2.2%    |
| Syntek                                 | 19        | 2.09%   |
| Samsung Electronics                    | 13        | 1.43%   |
| Z-Star Microelectronics                | 8         | 0.88%   |
| Acer                                   | 8         | 0.88%   |
| Microsoft                              | 7         | 0.77%   |
| Sonix Technology                       | 6         | 0.66%   |
| Suyin                                  | 4         | 0.44%   |
| MacroSilicon                           | 4         | 0.44%   |
| Generalplus Technology                 | 4         | 0.44%   |
| DigiTech                               | 4         | 0.44%   |
| Creative Technology                    | 4         | 0.44%   |
| ARC International                      | 4         | 0.44%   |
| Silicon Motion                         | 3         | 0.33%   |
| AVerMedia Technologies                 | 3         | 0.33%   |
| SunplusIT                              | 2         | 0.22%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.22%   |
| Ricoh                                  | 2         | 0.22%   |
| Razer USA                              | 2         | 0.22%   |
| LG Electronics                         | 2         | 0.22%   |
| Lenovo                                 | 2         | 0.22%   |
| KYE Systems (Mouse Systems)            | 2         | 0.22%   |
| kingcome                               | 2         | 0.22%   |
| Genesys Logic                          | 2         | 0.22%   |
| Elgato Systems                         | 2         | 0.22%   |
| Cubeternet                             | 2         | 0.22%   |
| Alcor Micro                            | 2         | 0.22%   |
| A4Tech                                 | 2         | 0.22%   |
| 8SSC21D67422V1SR28902JL                | 2         | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 63        | 6.83%   |
| Microdia Integrated_Webcam_HD                        | 40        | 4.33%   |
| IMC Networks Integrated Camera                       | 39        | 4.23%   |
| Logitech HD Pro Webcam C920                          | 29        | 3.14%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 28        | 3.03%   |
| Bison Integrated Camera                              | 25        | 2.71%   |
| Realtek Integrated_Webcam_HD                         | 22        | 2.38%   |
| Logitech Webcam C270                                 | 22        | 2.38%   |
| Chicony HD WebCam                                    | 16        | 1.73%   |
| Syntek Integrated Camera                             | 14        | 1.52%   |
| Sunplus Integrated_Webcam_HD                         | 14        | 1.52%   |
| Samsung Galaxy series, misc. (MTP mode)              | 13        | 1.41%   |
| Chicony HP HD Camera                                 | 12        | 1.3%    |
| Logitech C922 Pro Stream Webcam                      | 11        | 1.19%   |
| Lite-On Integrated Camera                            | 10        | 1.08%   |
| Quanta HD User Facing                                | 9         | 0.98%   |
| Microdia USB Camera                                  | 8         | 0.87%   |
| Logitech Webcam C310                                 | 8         | 0.87%   |
| Logitech BRIO Ultra HD Webcam                        | 8         | 0.87%   |
| Chicony USB2.0 Camera                                | 8         | 0.87%   |
| Lite-On HP HD Camera                                 | 7         | 0.76%   |
| Sunplus HD WebCam                                    | 6         | 0.65%   |
| Realtek Integrated Webcam HD                         | 6         | 0.65%   |
| Quanta HP Wide Vision HD Camera                      | 6         | 0.65%   |
| Chicony Lenovo EasyCamera                            | 6         | 0.65%   |
| Chicony HD User Facing                               | 6         | 0.65%   |
| Bison SunplusIT Integrated Camera                    | 6         | 0.65%   |
| Apple FaceTime HD Camera                             | 6         | 0.65%   |
| Realtek Laptop Camera                                | 5         | 0.54%   |
| Quanta HP TrueVision HD Camera                       | 5         | 0.54%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 5         | 0.54%   |
| Luxvisions Innotech Limited Integrated Camera        | 5         | 0.54%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 5         | 0.54%   |
| Luxvisions Innotech Limited HP HD Camera             | 5         | 0.54%   |
| Chicony ThinkPad T490 Webcam                         | 5         | 0.54%   |
| Chicony Integrated IR Camera                         | 5         | 0.54%   |
| Chicony Integrated Camera (1280x720@30)              | 5         | 0.54%   |
| Bison HD Webcam                                      | 5         | 0.54%   |
| Apple iPhone 5/5C/5S/6/SE                            | 5         | 0.54%   |
| Z-Star Venus USB2.0 Camera                           | 4         | 0.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 76        | 44.71%  |
| Validity Sensors           | 40        | 23.53%  |
| Shenzhen Goodix Technology | 28        | 16.47%  |
| Elan Microelectronics      | 9         | 5.29%   |
| STMicroelectronics         | 4         | 2.35%   |
| LighTuning Technology      | 4         | 2.35%   |
| AuthenTec                  | 4         | 2.35%   |
| DigitalPersona             | 3         | 1.76%   |
| Upek                       | 1         | 0.59%   |
| Samsung Electronics        | 1         | 0.59%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 29        | 17.06%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 15        | 8.82%   |
| Shenzhen Goodix  Fingerprint Device                                        | 12        | 7.06%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 5.88%   |
| Shenzhen Goodix Fingerprint Reader                                         | 10        | 5.88%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 9         | 5.29%   |
| Synaptics WBDI                                                             | 8         | 4.71%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 4.12%   |
| Elan ELAN:Fingerprint                                                      | 7         | 4.12%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 3.53%   |
| Synaptics UWP WBDI Device                                                  | 5         | 2.94%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 2.94%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 2.35%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 4         | 2.35%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 2.35%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 2.35%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.76%   |
| DigitalPersona Fingerprint Reader                                          | 3         | 1.76%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 1.18%   |
| Validity Sensors VFS491                                                    | 2         | 1.18%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.18%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.18%   |
| Unknown                                                                    | 2         | 1.18%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.59%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.59%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.59%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 0.59%   |
| Synaptics WBDI Device                                                      | 1         | 0.59%   |
| Synaptics TouchPad                                                         | 1         | 0.59%   |
| Synaptics  WBDI                                                            | 1         | 0.59%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.59%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.59%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.59%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.59%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.59%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 42        | 34.15%  |
| Alcor Micro                       | 42        | 34.15%  |
| Upek                              | 5         | 4.07%   |
| O2 Micro                          | 5         | 4.07%   |
| Clay Logic                        | 5         | 4.07%   |
| Yubico.com                        | 4         | 3.25%   |
| SCM Microsystems                  | 4         | 3.25%   |
| Hewlett-Packard                   | 2         | 1.63%   |
| Gemalto (was Gemplus)             | 2         | 1.63%   |
| Advanced Card Systems             | 2         | 1.63%   |
| VASCO Data Security International | 1         | 0.81%   |
| Purism, SPC                       | 1         | 0.81%   |
| OmniKey                           | 1         | 0.81%   |
| Microchip Technology              | 1         | 0.81%   |
| Lenovo                            | 1         | 0.81%   |
| Free Software Initiative of Japan | 1         | 0.81%   |
| Feitian Technologies              | 1         | 0.81%   |
| Bit4id                            | 1         | 0.81%   |
| Aladdin Knowledge Systems         | 1         | 0.81%   |
| Aktiv                             | 1         | 0.81%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 42        | 34.15%  |
| Broadcom 58200                                                               | 16        | 13.01%  |
| Broadcom 5880                                                                | 12        | 9.76%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 5.69%   |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 4.88%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 4.07%   |
| Clay Logic Nitrokey Pro                                                      | 5         | 4.07%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 4         | 3.25%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 3.25%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.63%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 2         | 1.63%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 2         | 1.63%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.63%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.81%   |
| Purism, SPC Librem Key                                                       | 1         | 0.81%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.81%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.81%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.81%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 0.81%   |
| Free Software Initiative of Japan Gnuk Token                                 | 1         | 0.81%   |
| Feitian Technologies FIDO CCID KB                                            | 1         | 0.81%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.81%   |
| Bit4id miniLector-s                                                          | 1         | 0.81%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.81%   |
| Aktiv Rutoken lite                                                           | 1         | 0.81%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.81%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.81%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 802       | 43.35%  |
| 1     | 510       | 27.57%  |
| 2     | 252       | 13.62%  |
| 3     | 137       | 7.41%   |
| 4     | 80        | 4.32%   |
| 5     | 41        | 2.22%   |
| 6     | 22        | 1.19%   |
| 7     | 5         | 0.27%   |
| 8     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 332       | 17.6%   |
| Graphics card            | 260       | 13.79%  |
| Bluetooth                | 234       | 12.41%  |
| Camera                   | 192       | 10.18%  |
| Fingerprint reader       | 168       | 8.91%   |
| Net/wireless             | 142       | 7.53%   |
| Chipcard                 | 96        | 5.09%   |
| Multimedia controller    | 87        | 4.61%   |
| Sound                    | 85        | 4.51%   |
| Card reader              | 77        | 4.08%   |
| Network                  | 36        | 1.91%   |
| Net/ethernet             | 31        | 1.64%   |
| Firewire controller      | 31        | 1.64%   |
| Unassigned class         | 25        | 1.33%   |
| Modem                    | 21        | 1.11%   |
| Storage/ide              | 20        | 1.06%   |
| Storage/ata              | 16        | 0.85%   |
| Storage/raid             | 9         | 0.48%   |
| Tv card                  | 7         | 0.37%   |
| Storage                  | 6         | 0.32%   |
| Storage/nvme             | 5         | 0.27%   |
| Dvb card                 | 4         | 0.21%   |
| Wireless                 | 1         | 0.05%   |
| Unclassified device      | 1         | 0.05%   |

