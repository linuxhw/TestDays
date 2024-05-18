Mageia - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Mageia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Mageia/Desktop/README.md) and [notebooks](/Dist/Mageia/Notebook/README.md).

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

Total: 220

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell      | 03W3VW A02                  | Desktop     | [ee02b7cd0b](https://linux-hardware.org/?probe=ee02b7cd0b) | May 05, 2024 |
| MSI       | MAG B460M MORTAR            | Desktop     | [175185cdad](https://linux-hardware.org/?probe=175185cdad) | Apr 12, 2024 |
| Acer      | Aspire 5742Z                | Notebook    | [f9ceb71c71](https://linux-hardware.org/?probe=f9ceb71c71) | Apr 11, 2024 |
| Acer      | Aspire SW5-011              | Notebook    | [4e8ad9d65f](https://linux-hardware.org/?probe=4e8ad9d65f) | Apr 10, 2024 |
| Acer      | Aspire SW5-011              | Notebook    | [6f6cb62f08](https://linux-hardware.org/?probe=6f6cb62f08) | Apr 02, 2024 |
| Acer      | Aspire SW5-011              | Notebook    | [6fbb2e2797](https://linux-hardware.org/?probe=6fbb2e2797) | Apr 01, 2024 |
| HP        | ProBook 650 G1              | Notebook    | [f097372357](https://linux-hardware.org/?probe=f097372357) | Mar 31, 2024 |
| ASRock    | 970 Pro3 R2.0               | Desktop     | [a06f99839a](https://linux-hardware.org/?probe=a06f99839a) | Mar 30, 2024 |
| ASUSTek   | VivoBook_ASUSLaptop X712... | Notebook    | [d6f2169d3f](https://linux-hardware.org/?probe=d6f2169d3f) | Mar 26, 2024 |
| Insyde    | BayTrail                    | Notebook    | [2566898a32](https://linux-hardware.org/?probe=2566898a32) | Mar 23, 2024 |
| Gigabyte  | F2A68HM-H                   | Desktop     | [2ae64472ff](https://linux-hardware.org/?probe=2ae64472ff) | Mar 20, 2024 |
| Gigabyte  | P67A-UD3-B3                 | Desktop     | [5089ab522a](https://linux-hardware.org/?probe=5089ab522a) | Mar 20, 2024 |
| Dell      | 0HN7XN A01                  | Desktop     | [987e3ca0a5](https://linux-hardware.org/?probe=987e3ca0a5) | Mar 20, 2024 |
| MSI       | A520M-A PRO                 | Desktop     | [8ff1245537](https://linux-hardware.org/?probe=8ff1245537) | Mar 19, 2024 |
| Lenovo    | SHARKBAY 0B98401 PRO        | Desktop     | [392bd2c7d3](https://linux-hardware.org/?probe=392bd2c7d3) | Mar 10, 2024 |
| MSI       | A520M-A PRO                 | Desktop     | [4958d63fb4](https://linux-hardware.org/?probe=4958d63fb4) | Feb 20, 2024 |
| Unknown   | Unknown                     | Desktop     | [3e1781cc8c](https://linux-hardware.org/?probe=3e1781cc8c) | Feb 16, 2024 |
| Unknown   | Unknown                     | Desktop     | [daefcf1b9f](https://linux-hardware.org/?probe=daefcf1b9f) | Feb 16, 2024 |
| Lenovo    | G50-30 80G0                 | Notebook    | [e1e268d222](https://linux-hardware.org/?probe=e1e268d222) | Jan 18, 2024 |
| Gigabyte  | B550 AORUS ELITE V2         | Desktop     | [0c54141bbd](https://linux-hardware.org/?probe=0c54141bbd) | Jan 11, 2024 |
| Gigabyte  | B550 AORUS ELITE V2         | Desktop     | [3117cde827](https://linux-hardware.org/?probe=3117cde827) | Jan 11, 2024 |
| HP        | ProBook 450 G1              | Notebook    | [028d205023](https://linux-hardware.org/?probe=028d205023) | Jan 09, 2024 |
| HP        | Compaq 6710b (GB887ET#AB... | Notebook    | [2aaeccac56](https://linux-hardware.org/?probe=2aaeccac56) | Jan 08, 2024 |
| Gigabyte  | H110M-S2-CF                 | Desktop     | [8ea8935806](https://linux-hardware.org/?probe=8ea8935806) | Jan 04, 2024 |
| ASUSTek   | PRIME B450-PLUS             | Desktop     | [863f0b5c06](https://linux-hardware.org/?probe=863f0b5c06) | Dec 29, 2023 |
| Lenovo    | 317C SDK0J40700 WIN 3258... | Desktop     | [f24d5f341c](https://linux-hardware.org/?probe=f24d5f341c) | Dec 28, 2023 |
| Gigabyte  | H81M-S2H                    | Desktop     | [8dd5a975f9](https://linux-hardware.org/?probe=8dd5a975f9) | Dec 02, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop K660... | Notebook    | [9315424410](https://linux-hardware.org/?probe=9315424410) | Nov 21, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop K660... | Notebook    | [5e92402cde](https://linux-hardware.org/?probe=5e92402cde) | Nov 21, 2023 |
| HP        | 255 15.6 inch G9 Noteboo... | Notebook    | [b1394cc278](https://linux-hardware.org/?probe=b1394cc278) | Oct 30, 2023 |
| Gigabyte  | B450M DS3H-CF               | Desktop     | [e18680d1f4](https://linux-hardware.org/?probe=e18680d1f4) | Oct 29, 2023 |
| Dell      | 0GK35Y A00                  | Desktop     | [99aded4434](https://linux-hardware.org/?probe=99aded4434) | Oct 17, 2023 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [ff0a453a0e](https://linux-hardware.org/?probe=ff0a453a0e) | Oct 13, 2023 |
| Lenovo    | IdeaPad Slim 3 15AMN8 82... | Notebook    | [02c2fabd1e](https://linux-hardware.org/?probe=02c2fabd1e) | Oct 11, 2023 |
| Lenovo    | IdeaPad Slim 3 15AMN8 82... | Notebook    | [02a4135aff](https://linux-hardware.org/?probe=02a4135aff) | Oct 09, 2023 |
| Dell      | 0GK35Y A00                  | Desktop     | [47987fd9dd](https://linux-hardware.org/?probe=47987fd9dd) | Oct 07, 2023 |
| Dell      | 0GK35Y A00                  | Desktop     | [d785138af0](https://linux-hardware.org/?probe=d785138af0) | Sep 03, 2023 |
| Fujitsu   | S6420                       | Notebook    | [044d4185b7](https://linux-hardware.org/?probe=044d4185b7) | Aug 22, 2023 |
| HP        | Pavilion Notebook           | Notebook    | [7fd3205fde](https://linux-hardware.org/?probe=7fd3205fde) | Aug 11, 2023 |
| Lenovo    | Yoga 720-15IKB 80X7         | Convertible | [b691f28c43](https://linux-hardware.org/?probe=b691f28c43) | Aug 10, 2023 |
| Dell      | Latitude E5470              | Notebook    | [f64529e38b](https://linux-hardware.org/?probe=f64529e38b) | Aug 08, 2023 |
| ASUSTek   | Q551LN                      | Notebook    | [ad2abcddcf](https://linux-hardware.org/?probe=ad2abcddcf) | Jul 27, 2023 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [6f489ed497](https://linux-hardware.org/?probe=6f489ed497) | Jul 20, 2023 |
| HP        | Laptop 14-cm0xxx            | Notebook    | [a0fd2eeb7b](https://linux-hardware.org/?probe=a0fd2eeb7b) | Jul 11, 2023 |
| Compaq    | 420                         | Notebook    | [6f4350d53e](https://linux-hardware.org/?probe=6f4350d53e) | Jul 10, 2023 |
| ASUSTek   | K73SD                       | Notebook    | [063e42ac60](https://linux-hardware.org/?probe=063e42ac60) | May 22, 2023 |
| ASUSTek   | TUF Gaming B550M-PLUS       | Desktop     | [a2b832afa2](https://linux-hardware.org/?probe=a2b832afa2) | Apr 30, 2023 |
| Gigabyte  | Z97-D3H-CF                  | Desktop     | [a62e386eae](https://linux-hardware.org/?probe=a62e386eae) | Apr 24, 2023 |
| Gigabyte  | Z97-D3H-CF                  | Desktop     | [bd9d832f72](https://linux-hardware.org/?probe=bd9d832f72) | Apr 23, 2023 |
| Dell      | Latitude 7370               | Notebook    | [a254d0d7f1](https://linux-hardware.org/?probe=a254d0d7f1) | Apr 02, 2023 |
| ASUSTek   | TUF Gaming B550M-PLUS       | Desktop     | [e45ad193f8](https://linux-hardware.org/?probe=e45ad193f8) | Apr 01, 2023 |
| Dell      | Latitude 7370               | Notebook    | [b8a0b25983](https://linux-hardware.org/?probe=b8a0b25983) | Mar 30, 2023 |
| MSI       | Z590-A PRO                  | Desktop     | [ad6a144db9](https://linux-hardware.org/?probe=ad6a144db9) | Mar 23, 2023 |
| ASUSTek   | M3A78-EMH HDMI              | Desktop     | [0aa8c2bf55](https://linux-hardware.org/?probe=0aa8c2bf55) | Mar 20, 2023 |
| ASUSTek   | P8H61-M LE                  | Desktop     | [bb43961724](https://linux-hardware.org/?probe=bb43961724) | Mar 17, 2023 |
| HP        | ProBook 5330m               | Notebook    | [2ec50367d4](https://linux-hardware.org/?probe=2ec50367d4) | Mar 11, 2023 |
| Lenovo    | MAHOBAY                     | Desktop     | [d0541545c8](https://linux-hardware.org/?probe=d0541545c8) | Mar 11, 2023 |
| ASUSTek   | P8H61-M LE                  | Desktop     | [69713a19ea](https://linux-hardware.org/?probe=69713a19ea) | Feb 28, 2023 |
| HP        | Unknown                     | Notebook    | [702ed67add](https://linux-hardware.org/?probe=702ed67add) | Dec 17, 2022 |
| HP        | Unknown                     | Notebook    | [d952fd785e](https://linux-hardware.org/?probe=d952fd785e) | Dec 17, 2022 |
| Fujitsu   | CELSIUS H720                | Notebook    | [a7eacb37c5](https://linux-hardware.org/?probe=a7eacb37c5) | Dec 03, 2022 |
| Lenovo    | ThinkCentre A57 970274G     | Desktop     | [809e137f17](https://linux-hardware.org/?probe=809e137f17) | Nov 02, 2022 |
| MSI       | B360I GMAING PRO AC         | Desktop     | [2584a31610](https://linux-hardware.org/?probe=2584a31610) | Oct 12, 2022 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [8d0d1ba821](https://linux-hardware.org/?probe=8d0d1ba821) | Oct 12, 2022 |
| MSI       | B360I GMAING PRO AC         | Desktop     | [bbdf7b4f77](https://linux-hardware.org/?probe=bbdf7b4f77) | Oct 01, 2022 |
| Irbis     | NB264                       | Notebook    | [103ca2d20b](https://linux-hardware.org/?probe=103ca2d20b) | Sep 16, 2022 |
| ASRock    | B550M-HDV                   | Desktop     | [c786c365d5](https://linux-hardware.org/?probe=c786c365d5) | Sep 06, 2022 |
| ASUSTek   | X751LN                      | Notebook    | [68cd0152fb](https://linux-hardware.org/?probe=68cd0152fb) | Aug 22, 2022 |
| ASUSTek   | M5A99FX PRO R2.0            | Desktop     | [d14ad254ca](https://linux-hardware.org/?probe=d14ad254ca) | Jul 05, 2022 |
| Schenker  | VIA_14_SVI14E20             | Notebook    | [3adb69bbf5](https://linux-hardware.org/?probe=3adb69bbf5) | Jun 03, 2022 |
| Notebook  | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [e30e3da709](https://linux-hardware.org/?probe=e30e3da709) | May 18, 2022 |
| Dell      | Latitude E5570              | Notebook    | [ec640c6644](https://linux-hardware.org/?probe=ec640c6644) | May 12, 2022 |
| Gigabyte  | H170-D3H-CF                 | Desktop     | [9f255eb7d5](https://linux-hardware.org/?probe=9f255eb7d5) | May 06, 2022 |
| ASUSTek   | F1A75-M LE                  | Desktop     | [93232d0716](https://linux-hardware.org/?probe=93232d0716) | May 01, 2022 |
| Microsoft | Surface Pro 4               | Tablet      | [4e74006288](https://linux-hardware.org/?probe=4e74006288) | Apr 21, 2022 |
| Lenovo    | ThinkPad X1 Carbon 5th 2... | Notebook    | [086a94d83c](https://linux-hardware.org/?probe=086a94d83c) | Apr 15, 2022 |
| Megaware  | MW-G31T-M7                  | Desktop     | [3ac4860cb3](https://linux-hardware.org/?probe=3ac4860cb3) | Apr 13, 2022 |
| Megaware  | MW-G31T-M7                  | Desktop     | [ce643cbdcd](https://linux-hardware.org/?probe=ce643cbdcd) | Apr 13, 2022 |
| Gigabyte  | H81M-S2H                    | Desktop     | [ac5d29c839](https://linux-hardware.org/?probe=ac5d29c839) | Apr 05, 2022 |
| MSI       | Z590-A PRO                  | Desktop     | [229ed42b3d](https://linux-hardware.org/?probe=229ed42b3d) | Apr 03, 2022 |
| Toshiba   | dynabook R73/A              | Notebook    | [42b60c90c7](https://linux-hardware.org/?probe=42b60c90c7) | Apr 01, 2022 |
| Gigabyte  | GA-78LMT-USB3 SEx           | Desktop     | [2955e87822](https://linux-hardware.org/?probe=2955e87822) | Mar 29, 2022 |
| Gigabyte  | G31M-S2C                    | Desktop     | [a56fb721dd](https://linux-hardware.org/?probe=a56fb721dd) | Mar 17, 2022 |
| Gigabyte  | X570 AORUS ELITE WIFI       | Desktop     | [8d52e31d86](https://linux-hardware.org/?probe=8d52e31d86) | Mar 09, 2022 |
| MSI       | Z590-A PRO                  | Desktop     | [5f37c84d61](https://linux-hardware.org/?probe=5f37c84d61) | Mar 06, 2022 |
| Gigabyte  | G31M-S2C                    | Desktop     | [d419223147](https://linux-hardware.org/?probe=d419223147) | Mar 06, 2022 |
| Gigabyte  | X570 AORUS ELITE WIFI       | Desktop     | [c11d937631](https://linux-hardware.org/?probe=c11d937631) | Feb 23, 2022 |
| ASRock    | M3A UCC                     | Desktop     | [eaa75fb3f4](https://linux-hardware.org/?probe=eaa75fb3f4) | Feb 20, 2022 |
| ASRock    | M3A UCC                     | Desktop     | [ce306a4c86](https://linux-hardware.org/?probe=ce306a4c86) | Feb 20, 2022 |
| MSI       | B250M BAZOOKA               | Desktop     | [4a8f0501a2](https://linux-hardware.org/?probe=4a8f0501a2) | Feb 11, 2022 |
| ASRock    | G41M-VS3                    | Desktop     | [825356bf6c](https://linux-hardware.org/?probe=825356bf6c) | Feb 02, 2022 |
| HP        | 1589                        | Desktop     | [41dbcb78cb](https://linux-hardware.org/?probe=41dbcb78cb) | Jan 30, 2022 |
| Gigabyte  | H81M-DS2                    | Desktop     | [c0328d5402](https://linux-hardware.org/?probe=c0328d5402) | Jan 27, 2022 |
| Lenovo    | ThinkCentre M58e 7491B1G    | Desktop     | [568741947f](https://linux-hardware.org/?probe=568741947f) | Jan 12, 2022 |
| Gigabyte  | B450 AORUS M                | Desktop     | [d9856d52b0](https://linux-hardware.org/?probe=d9856d52b0) | Jan 11, 2022 |
| Gigabyte  | B450 AORUS M                | Desktop     | [8b8a13f3b4](https://linux-hardware.org/?probe=8b8a13f3b4) | Jan 11, 2022 |
| Gigabyte  | B450 AORUS M                | Desktop     | [0fa4a81a77](https://linux-hardware.org/?probe=0fa4a81a77) | Jan 09, 2022 |
| Lenovo    | ThinkCentre M58e 7491B1G    | Desktop     | [a77218c72c](https://linux-hardware.org/?probe=a77218c72c) | Jan 09, 2022 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [a1a7854f7a](https://linux-hardware.org/?probe=a1a7854f7a) | Jan 04, 2022 |
| MSI       | MPG X570 GAMING EDGE WIF... | Desktop     | [c1d67915d0](https://linux-hardware.org/?probe=c1d67915d0) | Dec 26, 2021 |
| ASUSTek   | ROG ZENITH EXTREME          | Desktop     | [e3d82aebbe](https://linux-hardware.org/?probe=e3d82aebbe) | Dec 20, 2021 |
| MSI       | MPG X570 GAMING EDGE WIF... | Desktop     | [fdc65fea9d](https://linux-hardware.org/?probe=fdc65fea9d) | Dec 08, 2021 |
| Dell      | Latitude E5570              | Notebook    | [38032eae74](https://linux-hardware.org/?probe=38032eae74) | Dec 06, 2021 |
| Dell      | Latitude E5570              | Notebook    | [9314738bbb](https://linux-hardware.org/?probe=9314738bbb) | Dec 06, 2021 |
| Dell      | Precision 5530              | Notebook    | [f98313a80c](https://linux-hardware.org/?probe=f98313a80c) | Nov 29, 2021 |
| Dell      | 0TP412                      | Desktop     | [f759f2084b](https://linux-hardware.org/?probe=f759f2084b) | Nov 22, 2021 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [3e92c96ac0](https://linux-hardware.org/?probe=3e92c96ac0) | Nov 17, 2021 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [6e13fb31c9](https://linux-hardware.org/?probe=6e13fb31c9) | Oct 17, 2021 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [45d12f532c](https://linux-hardware.org/?probe=45d12f532c) | Oct 01, 2021 |
| Lenovo    | IdeaPad 3 15ADA05 81W1      | Notebook    | [3f4fe97a8a](https://linux-hardware.org/?probe=3f4fe97a8a) | Sep 30, 2021 |
| Gigabyte  | H170-D3H-CF                 | Desktop     | [42784959b9](https://linux-hardware.org/?probe=42784959b9) | Sep 28, 2021 |
| Apple     | Mac-F42386C8 PVT            | All in one  | [3235b7d95a](https://linux-hardware.org/?probe=3235b7d95a) | Sep 24, 2021 |
| Dell      | 0TP412                      | Desktop     | [25b9af915a](https://linux-hardware.org/?probe=25b9af915a) | Sep 09, 2021 |
| MSI       | MAG B460M MORTAR            | Desktop     | [6fa1f56407](https://linux-hardware.org/?probe=6fa1f56407) | Aug 30, 2021 |
| Gigabyte  | H81M-S2H                    | Desktop     | [894c915ecc](https://linux-hardware.org/?probe=894c915ecc) | Aug 17, 2021 |
| Lenovo    | IdeaPad Slim 1-14AST-05 ... | Notebook    | [46250d420a](https://linux-hardware.org/?probe=46250d420a) | Aug 14, 2021 |
| Gigabyte  | B450 AORUS PRO WIFI-CF      | Desktop     | [4c28c43c28](https://linux-hardware.org/?probe=4c28c43c28) | Aug 10, 2021 |
| Lenovo    | ThinkPad T61 6468AE2        | Notebook    | [216fbf401b](https://linux-hardware.org/?probe=216fbf401b) | Aug 05, 2021 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [88ddc09b9e](https://linux-hardware.org/?probe=88ddc09b9e) | Jul 28, 2021 |
| Gigabyte  | H81M-S2H                    | Desktop     | [f52713e401](https://linux-hardware.org/?probe=f52713e401) | Jul 28, 2021 |
| Dell      | 0TP412                      | Desktop     | [8788d078a0](https://linux-hardware.org/?probe=8788d078a0) | Jul 19, 2021 |
| ASUSTek   | PRIME X399-A                | Desktop     | [a2b6af1a6a](https://linux-hardware.org/?probe=a2b6af1a6a) | Jul 14, 2021 |
| ASUSTek   | X751LN                      | Notebook    | [8c0efa94e8](https://linux-hardware.org/?probe=8c0efa94e8) | Jul 08, 2021 |
| Gigabyte  | Z68XP-UD3P                  | Desktop     | [259e2a4ac0](https://linux-hardware.org/?probe=259e2a4ac0) | Jun 24, 2021 |
| Notebook  | NL40_50GU                   | Notebook    | [baa8447288](https://linux-hardware.org/?probe=baa8447288) | May 08, 2021 |
| Medion    | DEFENDER P10                | Notebook    | [cb752c0a4a](https://linux-hardware.org/?probe=cb752c0a4a) | May 01, 2021 |
| Medion    | DEFENDER P10                | Notebook    | [f42aa05a37](https://linux-hardware.org/?probe=f42aa05a37) | May 01, 2021 |
| Gigabyte  | B450M DS3H-CF               | Desktop     | [1be802a26e](https://linux-hardware.org/?probe=1be802a26e) | Apr 18, 2021 |
| ECS       | IC780M-A2                   | Desktop     | [e3cbd0879b](https://linux-hardware.org/?probe=e3cbd0879b) | Apr 17, 2021 |
| ASUSTek   | Z170-P                      | Desktop     | [1ebcf0ea2c](https://linux-hardware.org/?probe=1ebcf0ea2c) | Apr 16, 2021 |
| ASUSTek   | Z170-P                      | Desktop     | [a95896e05e](https://linux-hardware.org/?probe=a95896e05e) | Apr 16, 2021 |
| Medion    | Z370H4-EM                   | Desktop     | [57435ad8fb](https://linux-hardware.org/?probe=57435ad8fb) | Apr 16, 2021 |
| ASUSTek   | SABERTOOTH P67              | Desktop     | [6d81c9d615](https://linux-hardware.org/?probe=6d81c9d615) | Apr 16, 2021 |
| Fujitsu   | LIFEBOOK E752               | Notebook    | [8ec052ba75](https://linux-hardware.org/?probe=8ec052ba75) | Apr 15, 2021 |
| Gigabyte  | H61M-S2PV                   | Desktop     | [dce1091d81](https://linux-hardware.org/?probe=dce1091d81) | Apr 15, 2021 |
| Medion    | Z370H4-EM                   | Desktop     | [b88834e15d](https://linux-hardware.org/?probe=b88834e15d) | Apr 15, 2021 |
| Lenovo    | ThinkPad T430 2342A19       | Notebook    | [9a5ad3016a](https://linux-hardware.org/?probe=9a5ad3016a) | Apr 15, 2021 |
| HP        | 212B                        | Desktop     | [697e2f24f0](https://linux-hardware.org/?probe=697e2f24f0) | Apr 03, 2021 |
| ASUSTek   | X751LN                      | Notebook    | [09afc59907](https://linux-hardware.org/?probe=09afc59907) | Apr 02, 2021 |
| Intel     | STL2-bd A28808-302          | Desktop     | [d6b5151873](https://linux-hardware.org/?probe=d6b5151873) | Apr 01, 2021 |
| Gigabyte  | B450M DS3H-CF               | Desktop     | [dbb3c1865f](https://linux-hardware.org/?probe=dbb3c1865f) | Mar 29, 2021 |
| HP        | 212B                        | Desktop     | [69f528da9b](https://linux-hardware.org/?probe=69f528da9b) | Mar 28, 2021 |
| ASUSTek   | PRIME A320M-K               | Desktop     | [2b381b3421](https://linux-hardware.org/?probe=2b381b3421) | Mar 24, 2021 |
| ASUSTek   | X556URK                     | Notebook    | [4904d2c78e](https://linux-hardware.org/?probe=4904d2c78e) | Mar 18, 2021 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [d4570ea6b2](https://linux-hardware.org/?probe=d4570ea6b2) | Mar 12, 2021 |
| ASUSTek   | X751LN                      | Notebook    | [0bb2c11bdc](https://linux-hardware.org/?probe=0bb2c11bdc) | Feb 24, 2021 |
| ASRock    | M3A UCC                     | Desktop     | [714da9501f](https://linux-hardware.org/?probe=714da9501f) | Feb 19, 2021 |
| HP        | 339A                        | Desktop     | [43e759b593](https://linux-hardware.org/?probe=43e759b593) | Feb 14, 2021 |
| Dell      | Latitude E6530              | Notebook    | [035378659f](https://linux-hardware.org/?probe=035378659f) | Feb 12, 2021 |
| Gigabyte  | H81M-S2H                    | Desktop     | [f9e5b1d3c6](https://linux-hardware.org/?probe=f9e5b1d3c6) | Feb 08, 2021 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [aea262050c](https://linux-hardware.org/?probe=aea262050c) | Feb 04, 2021 |
| Dell      | Inspiron 5480               | Notebook    | [2ae12f394c](https://linux-hardware.org/?probe=2ae12f394c) | Jan 27, 2021 |
| Gigabyte  | B450M DS3H-CF               | Desktop     | [a399a43535](https://linux-hardware.org/?probe=a399a43535) | Jan 16, 2021 |
| Kiano     | SlimNote 15.6               | Notebook    | [55179f361c](https://linux-hardware.org/?probe=55179f361c) | Jan 08, 2021 |
| Kiano     | SlimNote 15.6               | Notebook    | [5379fd7478](https://linux-hardware.org/?probe=5379fd7478) | Jan 08, 2021 |
| ASUSTek   | VivoBook 15_ASUS Laptop ... | Notebook    | [01aa1a7b95](https://linux-hardware.org/?probe=01aa1a7b95) | Dec 30, 2020 |
| ASUSTek   | Z87-DELUXE                  | Desktop     | [e160eea25a](https://linux-hardware.org/?probe=e160eea25a) | Dec 28, 2020 |
| ASUSTek   | X751LN                      | Notebook    | [f7f3533d54](https://linux-hardware.org/?probe=f7f3533d54) | Dec 27, 2020 |
| HP        | 339A                        | Desktop     | [ea7792c224](https://linux-hardware.org/?probe=ea7792c224) | Dec 26, 2020 |
| ASUSTek   | ROG ZENITH EXTREME          | Desktop     | [5fd86e8c94](https://linux-hardware.org/?probe=5fd86e8c94) | Dec 22, 2020 |
| Dell      | Inspiron 5480               | Notebook    | [1261d0c9d3](https://linux-hardware.org/?probe=1261d0c9d3) | Dec 21, 2020 |
| Lenovo    | ThinkServer TS140           | Desktop     | [ec475a7f9a](https://linux-hardware.org/?probe=ec475a7f9a) | Dec 09, 2020 |
| ASRock    | H87M Pro4                   | Desktop     | [12185c0c75](https://linux-hardware.org/?probe=12185c0c75) | Dec 07, 2020 |
| ASRock    | H87M Pro4                   | Desktop     | [747bc56208](https://linux-hardware.org/?probe=747bc56208) | Dec 07, 2020 |
| Gigabyte  | F2A88XM-DS2                 | Desktop     | [1b5123770e](https://linux-hardware.org/?probe=1b5123770e) | Dec 06, 2020 |
| HP        | Spectre 13 Ultrabook        | Notebook    | [9b88fe4fa5](https://linux-hardware.org/?probe=9b88fe4fa5) | Nov 30, 2020 |
| Gigabyte  | H81M-S2H                    | Desktop     | [009e2519cb](https://linux-hardware.org/?probe=009e2519cb) | Nov 22, 2020 |
| HP        | EliteBook 840 G3            | Notebook    | [4dd618cb59](https://linux-hardware.org/?probe=4dd618cb59) | Nov 21, 2020 |
| HP        | EliteBook 840 G3            | Notebook    | [2543664b54](https://linux-hardware.org/?probe=2543664b54) | Nov 21, 2020 |
| Gigabyte  | GA-78LMT-USB3 R2            | Desktop     | [1aec57de3b](https://linux-hardware.org/?probe=1aec57de3b) | Nov 20, 2020 |
| ASUSTek   | PRIME B360-PLUS             | Desktop     | [dadbc2f1d7](https://linux-hardware.org/?probe=dadbc2f1d7) | Nov 15, 2020 |
| Lenovo    | IdeaPad 3 15ADA05 81W1      | Notebook    | [889cb35866](https://linux-hardware.org/?probe=889cb35866) | Nov 13, 2020 |
| HP        | ProBook 445 G7              | Notebook    | [2e97281aa0](https://linux-hardware.org/?probe=2e97281aa0) | Nov 05, 2020 |
| MSI       | MPG X570 GAMING EDGE WIF... | Desktop     | [fb717dc126](https://linux-hardware.org/?probe=fb717dc126) | Nov 05, 2020 |
| Gigabyte  | H170-D3H-CF                 | Desktop     | [8220a96972](https://linux-hardware.org/?probe=8220a96972) | Nov 02, 2020 |
| Acer      | Aspire V3-772               | Notebook    | [413786151e](https://linux-hardware.org/?probe=413786151e) | Oct 31, 2020 |
| Dell      | Inspiron 5480               | Notebook    | [62bb8575f1](https://linux-hardware.org/?probe=62bb8575f1) | Oct 22, 2020 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [e50d2bd553](https://linux-hardware.org/?probe=e50d2bd553) | Oct 18, 2020 |
| ZOTAC     | Unknown                     | Desktop     | [624888f3ab](https://linux-hardware.org/?probe=624888f3ab) | Oct 14, 2020 |
| Gigabyte  | H170-D3H-CF                 | Desktop     | [c73f4878af](https://linux-hardware.org/?probe=c73f4878af) | Oct 04, 2020 |
| Lenovo    | ThinkServer TS140           | Desktop     | [87f4eac666](https://linux-hardware.org/?probe=87f4eac666) | Sep 27, 2020 |
| HP        | Unknown                     | Notebook    | [b12d1589a1](https://linux-hardware.org/?probe=b12d1589a1) | Sep 08, 2020 |
| Acer      | Aspire 7741                 | Notebook    | [e5914ee358](https://linux-hardware.org/?probe=e5914ee358) | Sep 05, 2020 |
| HP        | Pavilion dv6                | Notebook    | [021a94f63e](https://linux-hardware.org/?probe=021a94f63e) | Sep 03, 2020 |
| ASRock    | M3A UCC                     | Desktop     | [43182d8754](https://linux-hardware.org/?probe=43182d8754) | Sep 01, 2020 |
| ASRock    | M3A UCC                     | Desktop     | [50908c43f9](https://linux-hardware.org/?probe=50908c43f9) | Sep 01, 2020 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [cbab4d3ea3](https://linux-hardware.org/?probe=cbab4d3ea3) | Aug 31, 2020 |
| Lenovo    | G480 20149                  | Notebook    | [5598a535c7](https://linux-hardware.org/?probe=5598a535c7) | Jul 24, 2020 |
| ASUSTek   | P8H61-M LE                  | Desktop     | [2ca048a380](https://linux-hardware.org/?probe=2ca048a380) | Jun 29, 2020 |
| ASRock    | H81M-VG4 R2.0               | Desktop     | [ed7fe704dd](https://linux-hardware.org/?probe=ed7fe704dd) | May 25, 2020 |
| HP        | 339A                        | Desktop     | [bbd2341205](https://linux-hardware.org/?probe=bbd2341205) | May 09, 2020 |
| HP        | 339A                        | Desktop     | [1334fcea56](https://linux-hardware.org/?probe=1334fcea56) | May 09, 2020 |
| ASUSTek   | VivoBook 15_ASUS Laptop ... | Notebook    | [8e31f45bf5](https://linux-hardware.org/?probe=8e31f45bf5) | May 07, 2020 |
| ASUSTek   | VivoBook 15_ASUS Laptop ... | Notebook    | [4b71b90312](https://linux-hardware.org/?probe=4b71b90312) | May 04, 2020 |
| MSI       | B360M MORTAR                | Desktop     | [d2215c28af](https://linux-hardware.org/?probe=d2215c28af) | Apr 26, 2020 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [f6e5343aa5](https://linux-hardware.org/?probe=f6e5343aa5) | Mar 31, 2020 |
| ASUSTek   | H170M-PLUS                  | Desktop     | [6dd350fc4a](https://linux-hardware.org/?probe=6dd350fc4a) | Mar 31, 2020 |
| ASUSTek   | PRIME A320M-K               | Desktop     | [cabb3f4266](https://linux-hardware.org/?probe=cabb3f4266) | Mar 29, 2020 |
| Vorke     | V1 Plus                     | Desktop     | [c49c2bb635](https://linux-hardware.org/?probe=c49c2bb635) | Mar 29, 2020 |
| ASRock    | X470 Taichi                 | Desktop     | [5125778e67](https://linux-hardware.org/?probe=5125778e67) | Mar 02, 2020 |
| Gigabyte  | B85M-D3H                    | Desktop     | [00442cfd17](https://linux-hardware.org/?probe=00442cfd17) | Feb 25, 2020 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [71a967abf8](https://linux-hardware.org/?probe=71a967abf8) | Feb 22, 2020 |
| Gigabyte  | H81M-S2H                    | Desktop     | [52c3f45c8f](https://linux-hardware.org/?probe=52c3f45c8f) | Feb 22, 2020 |
| ASUSTek   | H170M-PLUS                  | Desktop     | [0ae790ac85](https://linux-hardware.org/?probe=0ae790ac85) | Feb 01, 2020 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [506294e8e9](https://linux-hardware.org/?probe=506294e8e9) | Jan 13, 2020 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [16e8d236b4](https://linux-hardware.org/?probe=16e8d236b4) | Jan 12, 2020 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [7df7d9c296](https://linux-hardware.org/?probe=7df7d9c296) | Dec 20, 2019 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [0c42dfc62c](https://linux-hardware.org/?probe=0c42dfc62c) | Dec 08, 2019 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [2ef79b672c](https://linux-hardware.org/?probe=2ef79b672c) | Nov 15, 2019 |
| ASUSTek   | A55BM-K                     | Desktop     | [d58dbcdd06](https://linux-hardware.org/?probe=d58dbcdd06) | Nov 08, 2019 |
| MSI       | Z97-G43                     | Desktop     | [87e4cd50ce](https://linux-hardware.org/?probe=87e4cd50ce) | Apr 26, 2019 |
| ASRock    | X470 Taichi                 | Desktop     | [14a8808d2b](https://linux-hardware.org/?probe=14a8808d2b) | Apr 26, 2019 |
| Gigabyte  | Z68X-UD3H-B3                | Desktop     | [28ea4213cb](https://linux-hardware.org/?probe=28ea4213cb) | Feb 25, 2019 |
| Gigabyte  | Z68X-UD3H-B3                | Desktop     | [b9c55f2790](https://linux-hardware.org/?probe=b9c55f2790) | Feb 25, 2019 |
| ASRock    | X470 Taichi                 | Desktop     | [7b6ec43d58](https://linux-hardware.org/?probe=7b6ec43d58) | Jan 08, 2019 |
| ASRock    | X470 Taichi                 | Desktop     | [117cb09799](https://linux-hardware.org/?probe=117cb09799) | Dec 31, 2018 |
| Gigabyte  | Z68X-UD3H-B3                | Desktop     | [0a61436f40](https://linux-hardware.org/?probe=0a61436f40) | Feb 15, 2018 |
| ASUSTek   | M5A97 R2.0                  | Desktop     | [304aa59840](https://linux-hardware.org/?probe=304aa59840) | Dec 14, 2017 |
| ASUSTek   | M4A78 PLUS                  | Desktop     | [ed9d8a148d](https://linux-hardware.org/?probe=ed9d8a148d) | Mar 06, 2016 |
| Lenovo    | G570 20079                  | Notebook    | [fc57cb086b](https://linux-hardware.org/?probe=fc57cb086b) | Nov 26, 2015 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Mageia 8  | 62        | 43.66%  |
| Mageia 9  | 41        | 28.87%  |
| Mageia 7  | 33        | 23.24%  |
| Mageia 6  | 4         | 2.82%   |
| Mageia 5  | 1         | 0.7%    |
| Mageia 10 | 1         | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Mageia | 128       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.7.19-desktop-3.mga7    | 13        | 7.47%   |
| 5.10.27-desktop-1.mga8   | 8         | 4.6%    |
| 5.7.19-desktop-1.mga7    | 7         | 4.02%   |
| 6.6.18-desktop-1.mga9    | 5         | 2.87%   |
| 5.15.32-desktop-1.mga8   | 5         | 2.87%   |
| 6.5.13-desktop-6.mga9    | 4         | 2.3%    |
| 6.4.9-desktop-4.mga9     | 4         | 2.3%    |
| 6.4.16-desktop-3.mga9    | 4         | 2.3%    |
| 5.6.14-desktop-2.mga7    | 4         | 2.3%    |
| 5.5.4-desktop-1.mga7     | 4         | 2.3%    |
| 5.15.23-desktop-1.mga8   | 4         | 2.3%    |
| 5.10.25-desktop-1.mga8   | 4         | 2.3%    |
| 5.5.9-desktop-1.mga7     | 3         | 1.72%   |
| 5.10.12-desktop-1.mga7   | 3         | 1.72%   |
| 6.6.22-desktop-1.mga9    | 2         | 1.15%   |
| 6.6.14-desktop586-2.mga9 | 2         | 1.15%   |
| 6.6.14-desktop-2.mga9    | 2         | 1.15%   |
| 6.4.8-desktop-6.mga9     | 2         | 1.15%   |
| 5.6.6-desktop-1.mga7     | 2         | 1.15%   |
| 5.3.7-desktop-4.mga7     | 2         | 1.15%   |
| 5.17.4-desktop-2.mga8    | 2         | 1.15%   |
| 5.16.10-desktop-2.mga8   | 2         | 1.15%   |
| 5.15.98-desktop-1.mga8   | 2         | 1.15%   |
| 5.15.4-desktop-1.mga8    | 2         | 1.15%   |
| 5.15.35-desktop-2.mga8   | 2         | 1.15%   |
| 5.15.16-desktop-1.mga8   | 2         | 1.15%   |
| 5.15.11-desktop-3.mga8   | 2         | 1.15%   |
| 5.10.60-desktop-2.mga8   | 2         | 1.15%   |
| 5.10.52-desktop-1.mga8   | 2         | 1.15%   |
| 5.10.20-desktop-2.mga7   | 2         | 1.15%   |
| 5.10.14-desktop-1.mga7   | 2         | 1.15%   |
| 6.6.28-desktop-1.mga9    | 1         | 0.57%   |
| 6.6.22-desktop-1.mga10   | 1         | 0.57%   |
| 6.6.17-desktop-1.mga9    | 1         | 0.57%   |
| 6.5.13-server-6.mga9     | 1         | 0.57%   |
| 6.5.11-desktop-5.mga9    | 1         | 0.57%   |
| 6.4.6-desktop-2.mga9     | 1         | 0.57%   |
| 6.4.3-desktop-1.mga9     | 1         | 0.57%   |
| 6.2.6-desktop-1.mga9     | 1         | 0.57%   |
| 6.2.2-desktop-2.mga9     | 1         | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.7.19  | 18        | 10.47%  |
| 5.10.27 | 8         | 4.65%   |
| 6.6.18  | 5         | 2.91%   |
| 6.5.13  | 5         | 2.91%   |
| 5.15.32 | 5         | 2.91%   |
| 6.6.14  | 4         | 2.33%   |
| 6.4.9   | 4         | 2.33%   |
| 6.4.16  | 4         | 2.33%   |
| 5.6.14  | 4         | 2.33%   |
| 5.5.4   | 4         | 2.33%   |
| 5.15.23 | 4         | 2.33%   |
| 5.10.25 | 4         | 2.33%   |
| 5.10.12 | 4         | 2.33%   |
| 6.6.22  | 3         | 1.74%   |
| 5.5.9   | 3         | 1.74%   |
| 6.4.8   | 2         | 1.16%   |
| 5.6.6   | 2         | 1.16%   |
| 5.3.7   | 2         | 1.16%   |
| 5.17.4  | 2         | 1.16%   |
| 5.16.18 | 2         | 1.16%   |
| 5.16.10 | 2         | 1.16%   |
| 5.15.98 | 2         | 1.16%   |
| 5.15.4  | 2         | 1.16%   |
| 5.15.35 | 2         | 1.16%   |
| 5.15.16 | 2         | 1.16%   |
| 5.15.11 | 2         | 1.16%   |
| 5.10.60 | 2         | 1.16%   |
| 5.10.52 | 2         | 1.16%   |
| 5.10.20 | 2         | 1.16%   |
| 5.10.16 | 2         | 1.16%   |
| 5.10.14 | 2         | 1.16%   |
| 6.6.28  | 1         | 0.58%   |
| 6.6.17  | 1         | 0.58%   |
| 6.5.11  | 1         | 0.58%   |
| 6.4.6   | 1         | 0.58%   |
| 6.4.3   | 1         | 0.58%   |
| 6.2.6   | 1         | 0.58%   |
| 6.2.2   | 1         | 0.58%   |
| 6.1.6   | 1         | 0.58%   |
| 6.1.45  | 1         | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 29        | 18.13%  |
| 5.10    | 27        | 16.88%  |
| 5.7     | 19        | 11.88%  |
| 6.6     | 13        | 8.13%   |
| 6.4     | 12        | 7.5%    |
| 5.5     | 8         | 5%      |
| 5.6     | 7         | 4.38%   |
| 6.5     | 6         | 3.75%   |
| 6.1     | 5         | 3.13%   |
| 5.9     | 5         | 3.13%   |
| 5.16    | 4         | 2.5%    |
| 4.14    | 3         | 1.88%   |
| 6.2     | 2         | 1.25%   |
| 5.8     | 2         | 1.25%   |
| 5.4     | 2         | 1.25%   |
| 5.3     | 2         | 1.25%   |
| 5.19    | 2         | 1.25%   |
| 5.17    | 2         | 1.25%   |
| 5.14    | 2         | 1.25%   |
| 6.0     | 1         | 0.63%   |
| 5.18    | 1         | 0.63%   |
| 5.13    | 1         | 0.63%   |
| 5.12    | 1         | 0.63%   |
| 5.1     | 1         | 0.63%   |
| 4.9     | 1         | 0.63%   |
| 4.19    | 1         | 0.63%   |
| 4.1     | 1         | 0.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 124       | 96.88%  |
| i686   | 3         | 2.34%   |
| i586   | 1         | 0.78%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 56        | 40.29%  |
| KDE           | 24        | 17.27%  |
| GNOME         | 19        | 13.67%  |
| Unknown       | 9         | 6.47%   |
| XFCE          | 7         | 5.04%   |
| MATE          | 6         | 4.32%   |
| LXDE          | 6         | 4.32%   |
| Cinnamon      | 5         | 3.6%    |
| X-Cinnamon    | 2         | 1.44%   |
| LXQt          | 2         | 1.44%   |
| GNOME Classic | 2         | 1.44%   |
| KDE4          | 1         | 0.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 113       | 87.6%   |
| Wayland | 12        | 9.3%    |
| Tty     | 4         | 3.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 55        | 42.64%  |
| SDDM    | 47        | 36.43%  |
| LightDM | 13        | 10.08%  |
| GDM     | 7         | 5.43%   |
| TDM     | 3         | 2.33%   |
| LXDM    | 3         | 2.33%   |
| XDM     | 1         | 0.78%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| fr_FR   | 28        | 21.54%  |
| en_US   | 26        | 20%     |
| de_DE   | 11        | 8.46%   |
| ru_RU   | 10        | 7.69%   |
| en_GB   | 10        | 7.69%   |
| Unknown | 8         | 6.15%   |
| pt_BR   | 5         | 3.85%   |
| it_IT   | 4         | 3.08%   |
| pl_PL   | 3         | 2.31%   |
| en_CA   | 3         | 2.31%   |
| sv_SE   | 2         | 1.54%   |
| hu_HU   | 2         | 1.54%   |
| es_MX   | 2         | 1.54%   |
| es_GT   | 2         | 1.54%   |
| bg_BG   | 2         | 1.54%   |
| zh_TW   | 1         | 0.77%   |
| sl_SI   | 1         | 0.77%   |
| sk_SK   | 1         | 0.77%   |
| ro_RO   | 1         | 0.77%   |
| fur_IT  | 1         | 0.77%   |
| fr_BE   | 1         | 0.77%   |
| es_ES   | 1         | 0.77%   |
| es_CR   | 1         | 0.77%   |
| es_CO   | 1         | 0.77%   |
| es_CL   | 1         | 0.77%   |
| es_AR   | 1         | 0.77%   |
| cs_CZ   | 1         | 0.77%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 76        | 56.72%  |
| EFI  | 58        | 43.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 107       | 82.31%  |
| Xfs      | 8         | 6.15%   |
| Unknown  | 6         | 4.62%   |
| Btrfs    | 5         | 3.85%   |
| Reiserfs | 2         | 1.54%   |
| Overlay  | 1         | 0.77%   |
| Ext3     | 1         | 0.77%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 56        | 42.11%  |
| Unknown | 46        | 34.59%  |
| MBR     | 31        | 23.31%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 111       | 86.05%  |
| Yes       | 18        | 13.95%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 98        | 74.81%  |
| Yes       | 33        | 25.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 26        | 20.31%  |
| Gigabyte Technology | 23        | 17.97%  |
| Hewlett-Packard     | 16        | 12.5%   |
| Lenovo              | 13        | 10.16%  |
| Dell                | 11        | 8.59%   |
| MSI                 | 8         | 6.25%   |
| ASRock              | 7         | 5.47%   |
| Acer                | 4         | 3.13%   |
| Fujitsu             | 3         | 2.34%   |
| Notebook            | 2         | 1.56%   |
| Medion              | 2         | 1.56%   |
| Unknown             | 2         | 1.56%   |
| ZOTAC               | 1         | 0.78%   |
| Vorke               | 1         | 0.78%   |
| Toshiba             | 1         | 0.78%   |
| Schenker            | 1         | 0.78%   |
| Microsoft           | 1         | 0.78%   |
| Megaware            | 1         | 0.78%   |
| Kiano               | 1         | 0.78%   |
| Intel               | 1         | 0.78%   |
| Insyde              | 1         | 0.78%   |
| ECS                 | 1         | 0.78%   |
| Apple               | 1         | 0.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 5         | 3.91%   |
| Gigabyte Z68X-UD3H-B3                    | 2         | 1.56%   |
| Gigabyte H81M-S2H                        | 2         | 1.56%   |
| Gigabyte B450M DS3H                      | 2         | 1.56%   |
| Dell Precision WorkStation T3400         | 2         | 1.56%   |
| ASUS SABERTOOTH 990FX R2.0               | 2         | 1.56%   |
| Vorke V1 Plus                            | 1         | 0.78%   |
| Toshiba dynabook R73/A                   | 1         | 0.78%   |
| Schenker VIA_14_SVI14E20                 | 1         | 0.78%   |
| Notebook NL40_50GU                       | 1         | 0.78%   |
| Notebook NH5x_NH7x_HHx_HJx_HKx           | 1         | 0.78%   |
| MSI MS-7D09                              | 1         | 0.78%   |
| MSI MS-7C96                              | 1         | 0.78%   |
| MSI MS-7C82                              | 1         | 0.78%   |
| MSI MS-7C37                              | 1         | 0.78%   |
| MSI MS-7B31                              | 1         | 0.78%   |
| MSI MS-7B23                              | 1         | 0.78%   |
| MSI MS-7A70                              | 1         | 0.78%   |
| MSI MS-7816                              | 1         | 0.78%   |
| Microsoft Surface Pro 4                  | 1         | 0.78%   |
| Megaware MW-G31T-M7                      | 1         | 0.78%   |
| Medion MD34161/C708                      | 1         | 0.78%   |
| Medion DEFENDER P10                      | 1         | 0.78%   |
| Lenovo Yoga 720-15IKB 80X7               | 1         | 0.78%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1741F | 1         | 0.78%   |
| Lenovo ThinkPad T430 2342A19             | 1         | 0.78%   |
| Lenovo ThinkCentre M93p 10A90011UK       | 1         | 0.78%   |
| Lenovo ThinkCentre M92p 2992A7U          | 1         | 0.78%   |
| Lenovo ThinkCentre M58e 7491B1G          | 1         | 0.78%   |
| Lenovo ThinkCentre A57 970274G           | 1         | 0.78%   |
| Lenovo IdeaPad Slim 3 15AMN8 82XQ        | 1         | 0.78%   |
| Lenovo IdeaPad 3 15ADA05 81W1            | 1         | 0.78%   |
| Lenovo IdeaCentre 5 14IMB05 90NA0000US   | 1         | 0.78%   |
| Lenovo G50-30 80G0                       | 1         | 0.78%   |
| Lenovo G480 20149                        | 1         | 0.78%   |
| Lenovo 70A4000HUX ThinkServer TS140      | 1         | 0.78%   |
| Kiano SlimNote 15.6                      | 1         | 0.78%   |
| Intel STL2                               | 1         | 0.78%   |
| Insyde BayTrail                          | 1         | 0.78%   |
| HP Z440 Workstation                      | 1         | 0.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Unknown                | 5         | 3.91%   |
| Lenovo ThinkCentre     | 4         | 3.13%   |
| HP ProBook             | 4         | 3.13%   |
| Dell Precision         | 4         | 3.13%   |
| Dell Latitude          | 4         | 3.13%   |
| ASUS PRIME             | 4         | 3.13%   |
| Acer Aspire            | 4         | 3.13%   |
| ASUS VivoBook          | 3         | 2.34%   |
| ASUS SABERTOOTH        | 3         | 2.34%   |
| Lenovo ThinkPad        | 2         | 1.56%   |
| Lenovo IdeaPad         | 2         | 1.56%   |
| HP Pavilion            | 2         | 1.56%   |
| HP Compaq              | 2         | 1.56%   |
| Gigabyte Z68X-UD3H-B3  | 2         | 1.56%   |
| Gigabyte H81M-S2H      | 2         | 1.56%   |
| Gigabyte GA-78LMT-USB3 | 2         | 1.56%   |
| Gigabyte B450M         | 2         | 1.56%   |
| Dell OptiPlex          | 2         | 1.56%   |
| Vorke V1               | 1         | 0.78%   |
| Toshiba dynabook       | 1         | 0.78%   |
| Schenker VIA           | 1         | 0.78%   |
| Notebook NL40          | 1         | 0.78%   |
| Notebook NH5x          | 1         | 0.78%   |
| MSI MS-7D09            | 1         | 0.78%   |
| MSI MS-7C96            | 1         | 0.78%   |
| MSI MS-7C82            | 1         | 0.78%   |
| MSI MS-7C37            | 1         | 0.78%   |
| MSI MS-7B31            | 1         | 0.78%   |
| MSI MS-7B23            | 1         | 0.78%   |
| MSI MS-7A70            | 1         | 0.78%   |
| MSI MS-7816            | 1         | 0.78%   |
| Microsoft Surface      | 1         | 0.78%   |
| Megaware MW-G31T-M7    | 1         | 0.78%   |
| Medion MD34161         | 1         | 0.78%   |
| Medion DEFENDER        | 1         | 0.78%   |
| Lenovo Yoga            | 1         | 0.78%   |
| Lenovo IdeaCentre      | 1         | 0.78%   |
| Lenovo G50-30          | 1         | 0.78%   |
| Lenovo G480            | 1         | 0.78%   |
| Lenovo 70A4000HUX      | 1         | 0.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 14        | 10.94%  |
| 2013    | 14        | 10.94%  |
| 2012    | 14        | 10.94%  |
| 2014    | 12        | 9.38%   |
| 2017    | 9         | 7.03%   |
| 2020    | 8         | 6.25%   |
| 2016    | 8         | 6.25%   |
| 2011    | 7         | 5.47%   |
| 2008    | 7         | 5.47%   |
| 2019    | 6         | 4.69%   |
| 2010    | 6         | 4.69%   |
| 2021    | 5         | 3.91%   |
| 2009    | 5         | 3.91%   |
| 2015    | 4         | 3.13%   |
| 2007    | 3         | 2.34%   |
| 2023    | 2         | 1.56%   |
| 2022    | 2         | 1.56%   |
| 2002    | 1         | 0.78%   |
| Unknown | 1         | 0.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 79        | 61.72%  |
| Notebook    | 46        | 35.94%  |
| Tablet      | 1         | 0.78%   |
| Convertible | 1         | 0.78%   |
| All in one  | 1         | 0.78%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 128       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 128       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 30        | 22.56%  |
| 16.01-24.0  | 30        | 22.56%  |
| 8.01-16.0   | 23        | 17.29%  |
| 3.01-4.0    | 18        | 13.53%  |
| 32.01-64.0  | 17        | 12.78%  |
| 64.01-256.0 | 5         | 3.76%   |
| 24.01-32.0  | 3         | 2.26%   |
| 2.01-3.0    | 3         | 2.26%   |
| 1.01-2.0    | 2         | 1.5%    |
| 0.51-1.0    | 1         | 0.75%   |
| 0.01-0.5    | 1         | 0.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 45        | 29.8%   |
| 1.01-2.0   | 36        | 23.84%  |
| 4.01-8.0   | 32        | 21.19%  |
| 3.01-4.0   | 18        | 11.92%  |
| 8.01-16.0  | 9         | 5.96%   |
| 0.51-1.0   | 8         | 5.3%    |
| 16.01-24.0 | 2         | 1.32%   |
| 0.01-0.5   | 1         | 0.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 57        | 42.54%  |
| 2      | 33        | 24.63%  |
| 3      | 26        | 19.4%   |
| 5      | 7         | 5.22%   |
| 4      | 5         | 3.73%   |
| 7      | 2         | 1.49%   |
| 6      | 2         | 1.49%   |
| 8      | 1         | 0.75%   |
| 0      | 1         | 0.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 66        | 51.56%  |
| Yes       | 62        | 48.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 88.28%  |
| No        | 15        | 11.72%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 56.59%  |
| No        | 56        | 43.41%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 51.56%  |
| No        | 62        | 48.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Computers | Percent |
|-----------------|-----------|---------|
| France          | 29        | 22.66%  |
| USA             | 18        | 14.06%  |
| Germany         | 11        | 8.59%   |
| UK              | 9         | 7.03%   |
| Russia          | 7         | 5.47%   |
| Brazil          | 5         | 3.91%   |
| Italy           | 4         | 3.13%   |
| Canada          | 4         | 3.13%   |
| Ukraine         | 3         | 2.34%   |
| Poland          | 3         | 2.34%   |
| Netherlands     | 3         | 2.34%   |
| Mexico          | 3         | 2.34%   |
| Sweden          | 2         | 1.56%   |
| Romania         | 2         | 1.56%   |
| Guatemala       | 2         | 1.56%   |
| Greece          | 2         | 1.56%   |
| Colombia        | 2         | 1.56%   |
| Bulgaria        | 2         | 1.56%   |
| The Netherlands | 1         | 0.78%   |
| Taiwan          | 1         | 0.78%   |
| Spain           | 1         | 0.78%   |
| Slovenia        | 1         | 0.78%   |
| Slovakia        | 1         | 0.78%   |
| Malaysia        | 1         | 0.78%   |
| Luxembourg      | 1         | 0.78%   |
| Kenya           | 1         | 0.78%   |
| Indonesia       | 1         | 0.78%   |
| Hungary         | 1         | 0.78%   |
| Czechia         | 1         | 0.78%   |
| Costa Rica      | 1         | 0.78%   |
| Chile           | 1         | 0.78%   |
| Belgium         | 1         | 0.78%   |
| Belarus         | 1         | 0.78%   |
| Australia       | 1         | 0.78%   |
| Argentina       | 1         | 0.78%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Paris                 | 4         | 2.65%   |
| Virginia Beach        | 3         | 1.99%   |
| Rommerskirchen        | 3         | 1.99%   |
| Mala Danylivka        | 3         | 1.99%   |
| Kharkiv               | 3         | 1.99%   |
| Woking                | 2         | 1.32%   |
| Woincourt             | 2         | 1.32%   |
| Waterloo              | 2         | 1.32%   |
| Versailles            | 2         | 1.32%   |
| Upper Norwood         | 2         | 1.32%   |
| Strasbourg            | 2         | 1.32%   |
| Sao Paulo             | 2         | 1.32%   |
| Oakland               | 2         | 1.32%   |
| Londrina              | 2         | 1.32%   |
| Kirishi               | 2         | 1.32%   |
| Guatemala City        | 2         | 1.32%   |
| Grants Pass           | 2         | 1.32%   |
| Delft                 | 2         | 1.32%   |
| Bogotá               | 2         | 1.32%   |
| Yakutsk               | 1         | 0.66%   |
| Wroclaw               | 1         | 0.66%   |
| Wiwersheim            | 1         | 0.66%   |
| Voronezh              | 1         | 0.66%   |
| Vanves                | 1         | 0.66%   |
| Uzhhorod              | 1         | 0.66%   |
| Tver                  | 1         | 0.66%   |
| Turin                 | 1         | 0.66%   |
| Tours                 | 1         | 0.66%   |
| Toulouse              | 1         | 0.66%   |
| Tijuana               | 1         | 0.66%   |
| Thiais                | 1         | 0.66%   |
| The Hague             | 1         | 0.66%   |
| Surabaya              | 1         | 0.66%   |
| Sternberk             | 1         | 0.66%   |
| Sofia                 | 1         | 0.66%   |
| Sartrouville          | 1         | 0.66%   |
| Santiago              | 1         | 0.66%   |
| Sant'Angelo Lodigiano | 1         | 0.66%   |
| San Isidro            | 1         | 0.66%   |
| San Antonio           | 1         | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| WDC                     | 52        | 143    | 21.4%   |
| Seagate                 | 34        | 58     | 13.99%  |
| Samsung Electronics     | 34        | 44     | 13.99%  |
| Kingston                | 15        | 24     | 6.17%   |
| Toshiba                 | 14        | 22     | 5.76%   |
| Hitachi                 | 11        | 11     | 4.53%   |
| SanDisk                 | 9         | 15     | 3.7%    |
| Crucial                 | 9         | 15     | 3.7%    |
| Unknown                 | 8         | 10     | 3.29%   |
| PNY                     | 5         | 8      | 2.06%   |
| HGST                    | 5         | 9      | 2.06%   |
| Intel                   | 4         | 4      | 1.65%   |
| A-DATA Technology       | 4         | 9      | 1.65%   |
| SK hynix                | 3         | 4      | 1.23%   |
| Verbatim                | 2         | 3      | 0.82%   |
| TO Exter                | 2         | 2      | 0.82%   |
| Phison Electronics      | 2         | 3      | 0.82%   |
| Phison                  | 2         | 3      | 0.82%   |
| OCZ-VERTEX              | 2         | 2      | 0.82%   |
| OCZ                     | 2         | 2      | 0.82%   |
| JMicron Technology      | 2         | 2      | 0.82%   |
| GOODRAM                 | 2         | 3      | 0.82%   |
| XPG                     | 1         | 4      | 0.41%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.41%   |
| Transcend               | 1         | 1      | 0.41%   |
| Team                    | 1         | 1      | 0.41%   |
| SPCC                    | 1         | 1      | 0.41%   |
| PNY CS90                | 1         | 1      | 0.41%   |
| MSP                     | 1         | 1      | 0.41%   |
| LITEON                  | 1         | 1      | 0.41%   |
| LDLC                    | 1         | 1      | 0.41%   |
| KingFast                | 1         | 2      | 0.41%   |
| HUAWEI                  | 1         | 1      | 0.41%   |
| Hewlett-Packard         | 1         | 1      | 0.41%   |
| Gigabyte Technology     | 1         | 1      | 0.41%   |
| Fujitsu                 | 1         | 1      | 0.41%   |
| FORESEE                 | 1         | 1      | 0.41%   |
| Emtec                   | 1         | 1      | 0.41%   |
| Corsair                 | 1         | 1      | 0.41%   |
| China                   | 1         | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| WDC WD2500BEVT-22ZCT0 250GB      | 4         | 1.47%   |
| WDC WD10EZEX-08WN4A0 1TB         | 4         | 1.47%   |
| Samsung SSD 860 EVO 500GB        | 4         | 1.47%   |
| WDC WD20EFRX-68EUZN0 2TB         | 3         | 1.1%    |
| Unknown MMC Card  32GB           | 3         | 1.1%    |
| Toshiba HDWD110 1TB              | 3         | 1.1%    |
| Seagate ST3500418AS 500GB        | 3         | 1.1%    |
| Seagate ST32000644NS 2TB         | 3         | 1.1%    |
| Samsung SSD 860 EVO 250GB        | 3         | 1.1%    |
| Samsung SSD 850 EVO 500GB        | 3         | 1.1%    |
| WDC WDS500G2B0A-00SM50 500GB SSD | 2         | 0.73%   |
| WDC WDS250G2B0A-00SM50 250GB SSD | 2         | 0.73%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 2         | 0.73%   |
| WDC WDS100T2B0A 1TB SSD          | 2         | 0.73%   |
| WDC WD30EZRZ-00Z5HB0 3TB         | 2         | 0.73%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 2         | 0.73%   |
| WDC WD10EZRZ-00HTKB0 1TB         | 2         | 0.73%   |
| WDC WD10EFRX-68PJCN0 1TB         | 2         | 0.73%   |
| Unknown MMC Card  16GB           | 2         | 0.73%   |
| Toshiba MQ01ABF050 500GB         | 2         | 0.73%   |
| Toshiba HDWD120 2TB              | 2         | 0.73%   |
| TO Exter nal USB 3.0 500GB       | 2         | 0.73%   |
| Seagate ST2000DM008-2FR102 2TB   | 2         | 0.73%   |
| Seagate ST1000DM003-1CH162 1TB   | 2         | 0.73%   |
| SanDisk SDSSDA120G 120GB         | 2         | 0.73%   |
| SanDisk Extreme SSD 1TB          | 2         | 0.73%   |
| Samsung SSD 870 EVO 500GB        | 2         | 0.73%   |
| Samsung SSD 870 EVO 1TB          | 2         | 0.73%   |
| Samsung NVMe SSD Drive 500GB     | 2         | 0.73%   |
| PNY CS900 120GB SSD              | 2         | 0.73%   |
| OCZ-VERTEX PLUS R2 128GB SSD     | 2         | 0.73%   |
| Kingston SV300S37A240G 240GB SSD | 2         | 0.73%   |
| Kingston SH103S3120G 120GB SSD   | 2         | 0.73%   |
| Kingston SA400S37240G 240GB SSD  | 2         | 0.73%   |
| Kingston SA400S37120G 120GB SSD  | 2         | 0.73%   |
| Intel SSDSC2CW120A3 120GB        | 2         | 0.73%   |
| Hitachi HDS722020ALA330 2TB      | 2         | 0.73%   |
| HGST HUS726040ALE611 4TB         | 2         | 0.73%   |
| Crucial CT500MX500SSD1 500GB     | 2         | 0.73%   |
| Crucial CT120BX500SSD1 120GB     | 2         | 0.73%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 43        | 123    | 36.13%  |
| Seagate             | 33        | 52     | 27.73%  |
| Toshiba             | 13        | 21     | 10.92%  |
| Hitachi             | 11        | 11     | 9.24%   |
| Samsung Electronics | 7         | 11     | 5.88%   |
| HGST                | 5         | 9      | 4.2%    |
| Unknown             | 2         | 2      | 1.68%   |
| TO Exter            | 2         | 2      | 1.68%   |
| JMicron Technology  | 1         | 1      | 0.84%   |
| Hewlett-Packard     | 1         | 1      | 0.84%   |
| Fujitsu             | 1         | 1      | 0.84%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 22     | 21.59%  |
| Kingston            | 11        | 17     | 12.5%   |
| Crucial             | 9         | 15     | 10.23%  |
| WDC                 | 8         | 18     | 9.09%   |
| SanDisk             | 7         | 9      | 7.95%   |
| PNY                 | 5         | 8      | 5.68%   |
| A-DATA Technology   | 4         | 9      | 4.55%   |
| Intel               | 3         | 3      | 3.41%   |
| Verbatim            | 2         | 3      | 2.27%   |
| OCZ-VERTEX          | 2         | 2      | 2.27%   |
| OCZ                 | 2         | 2      | 2.27%   |
| GOODRAM             | 2         | 3      | 2.27%   |
| Transcend           | 1         | 1      | 1.14%   |
| Team                | 1         | 1      | 1.14%   |
| SPCC                | 1         | 1      | 1.14%   |
| SK hynix            | 1         | 1      | 1.14%   |
| PNY CS90            | 1         | 1      | 1.14%   |
| LITEON              | 1         | 1      | 1.14%   |
| LDLC                | 1         | 1      | 1.14%   |
| KingFast            | 1         | 2      | 1.14%   |
| FORESEE             | 1         | 1      | 1.14%   |
| Emtec               | 1         | 1      | 1.14%   |
| Corsair             | 1         | 1      | 1.14%   |
| China               | 1         | 1      | 1.14%   |
| ASMedia             | 1         | 1      | 1.14%   |
| Apacer              | 1         | 1      | 1.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 86        | 234    | 45.26%  |
| SSD     | 67        | 126    | 35.26%  |
| NVMe    | 28        | 44     | 14.74%  |
| MMC     | 6         | 8      | 3.16%   |
| Unknown | 3         | 8      | 1.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 112       | 340    | 69.57%  |
| NVMe | 27        | 43     | 16.77%  |
| SAS  | 16        | 29     | 9.94%   |
| MMC  | 6         | 8      | 3.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 88        | 157    | 49.44%  |
| 0.51-1.0   | 47        | 108    | 26.4%   |
| 1.01-2.0   | 23        | 43     | 12.92%  |
| 3.01-4.0   | 7         | 9      | 3.93%   |
| 2.01-3.0   | 7         | 31     | 3.93%   |
| 4.01-10.0  | 4         | 10     | 2.25%   |
| 10.01-20.0 | 2         | 2      | 1.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 31        | 22.63%  |
| 501-1000       | 29        | 21.17%  |
| 101-250        | 23        | 16.79%  |
| More than 3000 | 22        | 16.06%  |
| 2001-3000      | 12        | 8.76%   |
| 1001-2000      | 12        | 8.76%   |
| 51-100         | 4         | 2.92%   |
| 21-50          | 2         | 1.46%   |
| Unknown        | 2         | 1.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 24        | 16.33%  |
| 51-100         | 24        | 16.33%  |
| 101-250        | 23        | 15.65%  |
| 251-500        | 16        | 10.88%  |
| 501-1000       | 16        | 10.88%  |
| 21-50          | 14        | 9.52%   |
| 1001-2000      | 13        | 8.84%   |
| More than 3000 | 11        | 7.48%   |
| 2001-3000      | 4         | 2.72%   |
| Unknown        | 2         | 1.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Intel SSDSC2CW120A3 120GB             | 2         | 2      | 7.69%   |
| WDC WD20PURZ-85GU6Y0 2TB              | 1         | 1      | 3.85%   |
| WDC WD20PURZ-85AKKY0 2TB              | 1         | 1      | 3.85%   |
| WDC WD15EARS-00MVWB0 1TB              | 1         | 1      | 3.85%   |
| WDC WD10EARS-00MVWB0 1TB              | 1         | 1      | 3.85%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 1         | 1      | 3.85%   |
| WDC WD1001FAES-75W7A0 1TB             | 1         | 1      | 3.85%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 3.85%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 1      | 3.85%   |
| Seagate ST9250315AS 250GB             | 1         | 1      | 3.85%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 3.85%   |
| Seagate ST3320820AS 320GB             | 1         | 1      | 3.85%   |
| Seagate ST3250410AS 250GB             | 1         | 3      | 3.85%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 3.85%   |
| Seagate ST2000VN004-2E4164 2TB        | 1         | 1      | 3.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 3.85%   |
| Seagate ST1000DM003-1CH162 1TB        | 1         | 1      | 3.85%   |
| Samsung Electronics HD400LD 400GB     | 1         | 1      | 3.85%   |
| OCZ VERTEX3 120GB SSD                 | 1         | 1      | 3.85%   |
| LITEON IT SCS-256L9S 256GB SSD        | 1         | 1      | 3.85%   |
| Hitachi HTS725050A9A364 500GB         | 1         | 1      | 3.85%   |
| Hitachi HTS542525K9A300 250GB         | 1         | 1      | 3.85%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 3.85%   |
| Fujitsu MHZ2160BH G2 160GB            | 1         | 1      | 3.85%   |
| A-DATA Technology SU630 240GB SSD     | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 10     | 33.33%  |
| WDC                 | 4         | 6      | 16.67%  |
| Intel               | 2         | 2      | 8.33%   |
| Hitachi             | 2         | 2      | 8.33%   |
| Toshiba             | 1         | 1      | 4.17%   |
| SK hynix            | 1         | 1      | 4.17%   |
| Samsung Electronics | 1         | 1      | 4.17%   |
| OCZ                 | 1         | 1      | 4.17%   |
| LITEON              | 1         | 1      | 4.17%   |
| HGST                | 1         | 1      | 4.17%   |
| Fujitsu             | 1         | 1      | 4.17%   |
| A-DATA Technology   | 1         | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 10     | 44.44%  |
| WDC                 | 4         | 6      | 22.22%  |
| Hitachi             | 2         | 2      | 11.11%  |
| Toshiba             | 1         | 1      | 5.56%   |
| Samsung Electronics | 1         | 1      | 5.56%   |
| HGST                | 1         | 1      | 5.56%   |
| Fujitsu             | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 22     | 73.91%  |
| SSD  | 6         | 6      | 26.09%  |

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
| Works    | 71        | 208    | 46.71%  |
| Detected | 59        | 184    | 38.82%  |
| Malfunc  | 22        | 28     | 14.47%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 82        | 51.57%  |
| AMD                          | 34        | 21.38%  |
| Samsung Electronics          | 9         | 5.66%   |
| Marvell Technology Group     | 7         | 4.4%    |
| ASMedia Technology           | 7         | 4.4%    |
| Phison Electronics           | 5         | 3.14%   |
| SanDisk                      | 4         | 2.52%   |
| Kingston Technology Company  | 4         | 2.52%   |
| SK hynix                     | 2         | 1.26%   |
| Toshiba America Info Systems | 1         | 0.63%   |
| Nvidia                       | 1         | 0.63%   |
| JMicron Technology           | 1         | 0.63%   |
| Broadcom                     | 1         | 0.63%   |
| ADATA Technology             | 1         | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14        | 7.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12        | 6.06%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 7         | 3.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7         | 3.54%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7         | 3.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6         | 3.03%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6         | 3.03%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 3.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 2.53%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 2.53%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 4         | 2.02%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 4         | 2.02%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 2.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 2.02%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4         | 2.02%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 3         | 1.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 1.52%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 3         | 1.52%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 1.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 1.52%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 1.52%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 3         | 1.52%   |
| AMD SB600 IDE                                                                           | 3         | 1.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 1.01%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2         | 1.01%   |
| Phison E12 NVMe Controller                                                              | 2         | 1.01%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 2         | 1.01%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 1.01%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2         | 1.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 1.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 1.01%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 1.01%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 1.01%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 1.01%   |
| AMD X399 Series Chipset SATA Controller                                                 | 2         | 1.01%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 98        | 60.12%  |
| IDE  | 30        | 18.4%   |
| NVMe | 26        | 15.95%  |
| RAID | 8         | 4.91%   |
| SAS  | 1         | 0.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 90        | 70.31%  |
| AMD          | 37        | 28.91%  |
| Vortex86 SoC | 1         | 0.78%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 3.1%    |
| AMD FX-8350 Eight-Core Processor            | 4         | 3.1%    |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 2         | 1.55%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2         | 1.55%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 2         | 1.55%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2         | 1.55%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 2         | 1.55%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2         | 1.55%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 2         | 1.55%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 1.55%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2         | 1.55%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1.55%   |
| AMD Turion 64 X2 Mobile Technology TL-60    | 2         | 1.55%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2         | 1.55%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2         | 1.55%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2         | 1.55%   |
| Vortex86 SoC Vortex86DX                     | 1         | 0.78%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz          | 1         | 0.78%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 1         | 0.78%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.78%   |
| Intel Pentium III (Coppermine)              | 1         | 0.78%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz      | 1         | 0.78%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.78%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.78%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 0.78%   |
| Intel Pentium CPU G3450 @ 3.40GHz           | 1         | 0.78%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1         | 0.78%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz            | 1         | 0.78%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 0.78%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.78%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.78%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 0.78%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.78%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.78%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.78%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 0.78%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 0.78%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 1         | 0.78%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 25        | 19.53%  |
| Intel Core i7           | 24        | 18.75%  |
| Intel Core i3           | 8         | 6.25%   |
| AMD FX                  | 7         | 5.47%   |
| Other                   | 6         | 4.69%   |
| Intel Core 2 Duo        | 6         | 4.69%   |
| AMD Ryzen 5             | 6         | 4.69%   |
| AMD Ryzen 7             | 5         | 3.91%   |
| Intel Pentium           | 4         | 3.13%   |
| Intel Atom              | 4         | 3.13%   |
| AMD Ryzen 3             | 4         | 3.13%   |
| Intel Pentium Dual-Core | 3         | 2.34%   |
| Intel Celeron           | 3         | 2.34%   |
| Intel Xeon              | 2         | 1.56%   |
| AMD Turion 64 X2 Mobile | 2         | 1.56%   |
| AMD Ryzen Threadripper  | 2         | 1.56%   |
| AMD A8                  | 2         | 1.56%   |
| AMD A10                 | 2         | 1.56%   |
| Intel Pentium Silver    | 1         | 0.78%   |
| Intel Pentium III       | 1         | 0.78%   |
| Intel Pentium Gold      | 1         | 0.78%   |
| Intel Core m5           | 1         | 0.78%   |
| Intel Core 2 Quad       | 1         | 0.78%   |
| Intel Core 2            | 1         | 0.78%   |
| AMD Ryzen 9             | 1         | 0.78%   |
| AMD Phenom II X6        | 1         | 0.78%   |
| AMD Phenom II X4        | 1         | 0.78%   |
| AMD Athlon X2           | 1         | 0.78%   |
| AMD Athlon II X3        | 1         | 0.78%   |
| AMD Athlon 64 X2        | 1         | 0.78%   |
| AMD A6                  | 1         | 0.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 52        | 40.31%  |
| 2      | 49        | 37.98%  |
| 6      | 11        | 8.53%   |
| 8      | 8         | 6.2%    |
| 1      | 3         | 2.33%   |
| 12     | 2         | 1.55%   |
| 3      | 2         | 1.55%   |
| 32     | 1         | 0.78%   |
| 16     | 1         | 0.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 127       | 99.22%  |
| 2      | 1         | 0.78%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 81        | 63.28%  |
| 1      | 47        | 36.72%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 125       | 96.15%  |
| Unknown        | 3         | 2.31%   |
| 32-bit         | 2         | 1.54%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 50        | 36.23%  |
| 0x306c3    | 10        | 7.25%   |
| 0x206a7    | 7         | 5.07%   |
| 0x306a9    | 6         | 4.35%   |
| 0x406e3    | 4         | 2.9%    |
| 0x1067a    | 4         | 2.9%    |
| 0x06000852 | 4         | 2.9%    |
| 0x806e9    | 3         | 2.17%   |
| 0x08701021 | 3         | 2.17%   |
| 0x906ea    | 2         | 1.45%   |
| 0x906e9    | 2         | 1.45%   |
| 0x40651    | 2         | 1.45%   |
| 0x0a50000d | 2         | 1.45%   |
| 0x08701030 | 2         | 1.45%   |
| 0x08108109 | 2         | 1.45%   |
| 0x0800820d | 2         | 1.45%   |
| 0x06001119 | 2         | 1.45%   |
| 0x010000c8 | 2         | 1.45%   |
| 0xa0671    | 1         | 0.72%   |
| 0xa0653    | 1         | 0.72%   |
| 0xa0652    | 1         | 0.72%   |
| 0x906eb    | 1         | 0.72%   |
| 0x806ec    | 1         | 0.72%   |
| 0x806eb    | 1         | 0.72%   |
| 0x706a1    | 1         | 0.72%   |
| 0x6fb      | 1         | 0.72%   |
| 0x6f6      | 1         | 0.72%   |
| 0x686      | 1         | 0.72%   |
| 0x506e3    | 1         | 0.72%   |
| 0x506c9    | 1         | 0.72%   |
| 0x406c4    | 1         | 0.72%   |
| 0x306f2    | 1         | 0.72%   |
| 0x206d7    | 1         | 0.72%   |
| 0x20655    | 1         | 0.72%   |
| 0x10676    | 1         | 0.72%   |
| 0x08a00008 | 1         | 0.72%   |
| 0x08701013 | 1         | 0.72%   |
| 0x08600106 | 1         | 0.72%   |
| 0x08108102 | 1         | 0.72%   |
| 0x08101016 | 1         | 0.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 19        | 14.73%  |
| KabyLake         | 14        | 10.85%  |
| Skylake          | 9         | 6.98%   |
| SandyBridge      | 9         | 6.98%   |
| IvyBridge        | 9         | 6.98%   |
| Zen 2            | 8         | 6.2%    |
| Piledriver       | 8         | 6.2%    |
| Penryn           | 7         | 5.43%   |
| Zen+             | 5         | 3.88%   |
| Silvermont       | 4         | 3.1%    |
| Core             | 4         | 3.1%    |
| Zen              | 3         | 2.33%   |
| K8 Hammer        | 3         | 2.33%   |
| K10              | 3         | 2.33%   |
| Icelake          | 3         | 2.33%   |
| CometLake        | 3         | 2.33%   |
| Unknown          | 3         | 2.33%   |
| Zen 3            | 2         | 1.55%   |
| Westmere         | 2         | 1.55%   |
| Excavator        | 2         | 1.55%   |
| Alderlake Hybrid | 2         | 1.55%   |
| Steamroller      | 1         | 0.78%   |
| P6               | 1         | 0.78%   |
| K10 Llano        | 1         | 0.78%   |
| Goldmont plus    | 1         | 0.78%   |
| Goldmont         | 1         | 0.78%   |
| Bulldozer        | 1         | 0.78%   |
| Bonnell          | 1         | 0.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 65        | 42.48%  |
| Nvidia                                       | 56        | 36.6%   |
| AMD                                          | 31        | 20.26%  |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.65%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 3.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5         | 3.23%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 3.23%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4         | 2.58%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4         | 2.58%   |
| Nvidia GF108 [GeForce GT 430]                                               | 4         | 2.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 2.58%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.94%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3         | 1.94%   |
| Intel HD Graphics 620                                                       | 3         | 1.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3         | 1.94%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 1.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 1.94%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3         | 1.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 3         | 1.94%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 3         | 1.94%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2         | 1.29%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2         | 1.29%   |
| Nvidia GM108M [GeForce 840M]                                                | 2         | 1.29%   |
| Nvidia GK107 [GeForce GT 640]                                               | 2         | 1.29%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2         | 1.29%   |
| Intel HD Graphics 630                                                       | 2         | 1.29%   |
| Intel HD Graphics 530                                                       | 2         | 1.29%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.29%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2         | 1.29%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                           | 2         | 1.29%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                   | 2         | 1.29%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2         | 1.29%   |
| XGI Technology (eXtreme Graphics Innovation) Z7/Z9 (XG20 core)              | 1         | 0.65%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1         | 0.65%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 0.65%   |
| Nvidia NV11 [GeForce2 MX/MX 400]                                            | 1         | 0.65%   |
| Nvidia GT218 [GeForce G210]                                                 | 1         | 0.65%   |
| Nvidia GP108M [GeForce MX150]                                               | 1         | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 1         | 0.65%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                       | 1         | 0.65%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 0.65%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 0.65%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1         | 0.65%   |
| Nvidia GM108M [GeForce 930MX]                                               | 1         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 40        | 31.01%  |
| 1 x Nvidia     | 38        | 29.46%  |
| 1 x AMD        | 25        | 19.38%  |
| Intel + Nvidia | 17        | 13.18%  |
| Intel + AMD    | 4         | 3.1%    |
| 2 x Intel      | 2         | 1.55%   |
| 2 x AMD        | 1         | 0.78%   |
| 1 x XGI        | 1         | 0.78%   |
| AMD + Nvidia   | 1         | 0.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 99        | 73.88%  |
| Unknown     | 20        | 14.93%  |
| Proprietary | 15        | 11.19%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 55        | 41.35%  |
| 1.01-2.0   | 27        | 20.3%   |
| 0.51-1.0   | 20        | 15.04%  |
| 0.01-0.5   | 12        | 9.02%   |
| 3.01-4.0   | 6         | 4.51%   |
| 5.01-6.0   | 5         | 3.76%   |
| 7.01-8.0   | 4         | 3.01%   |
| 2.01-3.0   | 3         | 2.26%   |
| 8.01-16.0  | 1         | 0.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 17        | 11.72%  |
| AU Optronics            | 10        | 6.9%    |
| LG Display              | 9         | 6.21%   |
| BOE                     | 9         | 6.21%   |
| Dell                    | 8         | 5.52%   |
| Chimei Innolux          | 8         | 5.52%   |
| AOC                     | 8         | 5.52%   |
| Ancor Communications    | 8         | 5.52%   |
| Hewlett-Packard         | 7         | 4.83%   |
| Acer                    | 7         | 4.83%   |
| Goldstar                | 6         | 4.14%   |
| BenQ                    | 5         | 3.45%   |
| SNC                     | 4         | 2.76%   |
| ViewSonic               | 3         | 2.07%   |
| Sony                    | 3         | 2.07%   |
| Philips                 | 3         | 2.07%   |
| LG Electronics          | 3         | 2.07%   |
| Iiyama                  | 3         | 2.07%   |
| Sharp                   | 2         | 1.38%   |
| NEC Computers           | 2         | 1.38%   |
| Eizo                    | 2         | 1.38%   |
| Chi Mei Optoelectronics | 2         | 1.38%   |
| ASUSTek Computer        | 2         | 1.38%   |
| Unknown                 | 1         | 0.69%   |
| SANSUI                  | 1         | 0.69%   |
| RTK                     | 1         | 0.69%   |
| QBell                   | 1         | 0.69%   |
| PKB                     | 1         | 0.69%   |
| Onkyo                   | 1         | 0.69%   |
| Medion                  | 1         | 0.69%   |
| Lenovo                  | 1         | 0.69%   |
| Insignia                | 1         | 0.69%   |
| Idek Iiyama             | 1         | 0.69%   |
| HannStar                | 1         | 0.69%   |
| Compal                  | 1         | 0.69%   |
| Apple                   | 1         | 0.69%   |
| AGS                     | 1         | 0.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                   | 4         | 2.53%   |
| Hewlett-Packard L2206tm HWP3014 1920x1080 477x268mm 21.5-inch         | 3         | 1.9%    |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 890x500mm 40.2-inch | 2         | 1.27%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 1.27%   |
| Goldstar 27EA33 GSM59BC 1920x1080 598x337mm 27.0-inch                 | 2         | 1.27%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch         | 2         | 1.27%   |
| AOC CT500G AOCE556 1024x768 280x210mm 13.8-inch                       | 2         | 1.27%   |
| Ancor Communications PA248 ACI24B1 1920x1200 550x350mm 25.7-inch      | 2         | 1.27%   |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch | 2         | 1.27%   |
| ViewSonic VX2409 SERIES VSC6C2E 1920x1080 521x293mm 23.5-inch         | 1         | 0.63%   |
| ViewSonic VA903-3Series VSC701E 1280x1024 376x301mm 19.0-inch         | 1         | 0.63%   |
| ViewSonic LCD Monitor VP2468 Series 3520x1080                         | 1         | 0.63%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1         | 0.63%   |
| Sony TV SNYF301 1920x1080                                             | 1         | 0.63%   |
| Sony TV SNYDC02 1920x1080 708x398mm 32.0-inch                         | 1         | 0.63%   |
| Sony SDM-X72 SNY1E70 1280x1024 338x270mm 17.0-inch                    | 1         | 0.63%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.63%   |
| Sharp LCD Monitor SHP1461 3200x1800 294x165mm 13.3-inch               | 1         | 0.63%   |
| SANSUI ES-22F1 XEC3150 1920x1080 476x268mm 21.5-inch                  | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM0612 1920x1080 600x340mm 27.2-inch  | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM0471 1360x768 340x190mm 15.3-inch   | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM0194 1280x1024 380x300mm 19.1-inch  | 1         | 0.63%   |
| Samsung Electronics SMB2240W SAM0699 1680x1050 459x296mm 21.5-inch    | 1         | 0.63%   |
| Samsung Electronics SMB2240W SAM0698 1680x1050 474x296mm 22.0-inch    | 1         | 0.63%   |
| Samsung Electronics SM2333TN SAM06FC 1920x1080 477x268mm 21.5-inch    | 1         | 0.63%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.63%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1         | 0.63%   |
| Samsung Electronics LS27A80 SAM7184 3840x2160 597x336mm 27.0-inch     | 1         | 0.63%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3155 1920x1200 367x230mm 17.1-inch | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch | 1         | 0.63%   |
| Samsung Electronics LCD Monitor S24D330 3840x1080                     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor S24D330                               | 1         | 0.63%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.63%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 1         | 0.63%   |
| QBell QB.19F-4WLHGB QBL3EC6 1440x900 410x257mm 19.1-inch              | 1         | 0.63%   |
| PKB LCD Monitor Viseo223DX 1920x1080                                  | 1         | 0.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 66        | 45.83%  |
| 1366x768 (WXGA)    | 16        | 11.11%  |
| 3840x2160 (4K)     | 9         | 6.25%   |
| Unknown            | 8         | 5.56%   |
| 1920x1200 (WUXGA)  | 7         | 4.86%   |
| 1280x1024 (SXGA)   | 7         | 4.86%   |
| 1600x900 (HD+)     | 6         | 4.17%   |
| 1680x1050 (WSXGA+) | 4         | 2.78%   |
| 1280x800 (WXGA)    | 3         | 2.08%   |
| 3840x1080          | 2         | 1.39%   |
| 2560x1080          | 2         | 1.39%   |
| 1440x900 (WXGA+)   | 2         | 1.39%   |
| 1024x768 (XGA)     | 2         | 1.39%   |
| 5760x2160          | 1         | 0.69%   |
| 4480x1440          | 1         | 0.69%   |
| 3520x1080          | 1         | 0.69%   |
| 3200x900           | 1         | 0.69%   |
| 3200x1800 (QHD+)   | 1         | 0.69%   |
| 2736x1824          | 1         | 0.69%   |
| 2560x1440 (QHD)    | 1         | 0.69%   |
| 2560x1024          | 1         | 0.69%   |
| 1920x540           | 1         | 0.69%   |
| 1360x768           | 1         | 0.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 24        | 17.02%  |
| Unknown | 15        | 10.64%  |
| 24      | 13        | 9.22%   |
| 21      | 13        | 9.22%   |
| 27      | 11        | 7.8%    |
| 13      | 10        | 7.09%   |
| 17      | 9         | 6.38%   |
| 23      | 8         | 5.67%   |
| 19      | 8         | 5.67%   |
| 22      | 5         | 3.55%   |
| 18      | 4         | 2.84%   |
| 14      | 4         | 2.84%   |
| 54      | 2         | 1.42%   |
| 46      | 2         | 1.42%   |
| 32      | 2         | 1.42%   |
| 29      | 2         | 1.42%   |
| 25      | 2         | 1.42%   |
| 72      | 1         | 0.71%   |
| 48      | 1         | 0.71%   |
| 42      | 1         | 0.71%   |
| 20      | 1         | 0.71%   |
| 16      | 1         | 0.71%   |
| 12      | 1         | 0.71%   |
| 10      | 1         | 0.71%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 35        | 25.18%  |
| 501-600     | 32        | 23.02%  |
| 401-500     | 23        | 16.55%  |
| Unknown     | 15        | 10.79%  |
| 351-400     | 14        | 10.07%  |
| 201-300     | 7         | 5.04%   |
| 1001-1500   | 5         | 3.6%    |
| 601-700     | 4         | 2.88%   |
| 701-800     | 2         | 1.44%   |
| 1501-2000   | 1         | 0.72%   |
| 901-1000    | 1         | 0.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 89        | 66.42%  |
| 16/10   | 17        | 12.69%  |
| Unknown | 15        | 11.19%  |
| 5/4     | 7         | 5.22%   |
| 4/3     | 2         | 1.49%   |
| 21/9    | 2         | 1.49%   |
| 3/2     | 1         | 0.75%   |
| 1.96    | 1         | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 30        | 21.74%  |
| 101-110        | 24        | 17.39%  |
| Unknown        | 15        | 10.87%  |
| 301-350        | 13        | 9.42%   |
| 151-200        | 11        | 7.97%   |
| 81-90          | 9         | 6.52%   |
| 121-130        | 7         | 5.07%   |
| 251-300        | 6         | 4.35%   |
| 141-150        | 5         | 3.62%   |
| 501-1000       | 4         | 2.9%    |
| More than 1000 | 3         | 2.17%   |
| 71-80          | 3         | 2.17%   |
| 351-500        | 2         | 1.45%   |
| 91-100         | 2         | 1.45%   |
| 61-70          | 1         | 0.72%   |
| 41-50          | 1         | 0.72%   |
| 131-140        | 1         | 0.72%   |
| 111-120        | 1         | 0.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 54        | 40%     |
| 101-120       | 29        | 21.48%  |
| 121-160       | 25        | 18.52%  |
| Unknown       | 15        | 11.11%  |
| 1-50          | 6         | 4.44%   |
| More than 240 | 3         | 2.22%   |
| 161-240       | 3         | 2.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 105       | 80.77%  |
| 2     | 23        | 17.69%  |
| 3     | 2         | 1.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 67        | 37.85%  |
| Intel                    | 59        | 33.33%  |
| Qualcomm Atheros         | 14        | 7.91%   |
| Broadcom                 | 12        | 6.78%   |
| Marvell Technology Group | 5         | 2.82%   |
| MediaTek                 | 3         | 1.69%   |
| Broadcom Limited         | 3         | 1.69%   |
| TP-Link                  | 2         | 1.13%   |
| Sierra Wireless          | 2         | 1.13%   |
| Wilocity                 | 1         | 0.56%   |
| Ultimarc                 | 1         | 0.56%   |
| RDC Semiconductor        | 1         | 0.56%   |
| Ralink Technology        | 1         | 0.56%   |
| Nvidia                   | 1         | 0.56%   |
| Huawei Technologies      | 1         | 0.56%   |
| Dell                     | 1         | 0.56%   |
| D-Link System            | 1         | 0.56%   |
| ASIX Electronics         | 1         | 0.56%   |
| Aquantia                 | 1         | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 52        | 24.76%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 3.33%   |
| Intel Wireless 8260                                                    | 5         | 2.38%   |
| Intel I211 Gigabit Network Connection                                  | 5         | 2.38%   |
| Intel Ethernet Connection I217-V                                       | 5         | 2.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 4         | 1.9%    |
| Realtek RTL8125 2.5GbE Controller                                      | 4         | 1.9%    |
| Intel Wireless 3165                                                    | 4         | 1.9%    |
| Intel Wi-Fi 6 AX200                                                    | 4         | 1.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 4         | 1.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 1.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3         | 1.43%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 1.43%   |
| Sierra Wireless MC8305 Modem                                           | 2         | 0.95%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 2         | 0.95%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 2         | 0.95%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                        | 2         | 0.95%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 2         | 0.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2         | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.95%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter             | 2         | 0.95%   |
| Intel Wireless 8265 / 8275                                             | 2         | 0.95%   |
| Intel Wireless 7265                                                    | 2         | 0.95%   |
| Intel Wireless 7260                                                    | 2         | 0.95%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 0.95%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.95%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.95%   |
| Intel Ethernet Connection (2) I219-V                                   | 2         | 0.95%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 0.95%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                   | 2         | 0.95%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 2         | 0.95%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express         | 2         | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 0.95%   |
| Broadcom BCM4311 802.11a/b/g                                           | 2         | 0.95%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                     | 1         | 0.48%   |
| Ultimarc A-PAC Arcade Control Interface                                | 1         | 0.48%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 1         | 0.48%   |
| TP-Link 802.11ac NIC                                                   | 1         | 0.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 37        | 45.12%  |
| Realtek Semiconductor    | 15        | 18.29%  |
| Qualcomm Atheros         | 11        | 13.41%  |
| Broadcom                 | 8         | 9.76%   |
| MediaTek                 | 3         | 3.66%   |
| TP-Link                  | 2         | 2.44%   |
| Sierra Wireless          | 2         | 2.44%   |
| Wilocity                 | 1         | 1.22%   |
| Ralink Technology        | 1         | 1.22%   |
| Marvell Technology Group | 1         | 1.22%   |
| Dell                     | 1         | 1.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 5         | 5.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 4.65%   |
| Intel Wireless 3165                                            | 4         | 4.65%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 4.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 4.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 4.65%   |
| Sierra Wireless MC8305 Modem                                   | 2         | 2.33%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 2         | 2.33%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 2         | 2.33%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 2         | 2.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 2.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 2.33%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 2         | 2.33%   |
| Intel Wireless 8265 / 8275                                     | 2         | 2.33%   |
| Intel Wireless 7265                                            | 2         | 2.33%   |
| Intel Wireless 7260                                            | 2         | 2.33%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 2         | 2.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2.33%   |
| Broadcom BCM4311 802.11a/b/g                                   | 2         | 2.33%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter             | 1         | 1.16%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1         | 1.16%   |
| TP-Link 802.11ac NIC                                           | 1         | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.16%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 1.16%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 1.16%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 1.16%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 1.16%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.16%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 1.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.16%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.16%   |
| MediaTek WiFi                                                  | 1         | 1.16%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.16%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter            | 1         | 1.16%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 1         | 1.16%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 61        | 51.26%  |
| Intel                    | 36        | 30.25%  |
| Qualcomm Atheros         | 5         | 4.2%    |
| Broadcom                 | 5         | 4.2%    |
| Marvell Technology Group | 4         | 3.36%   |
| Broadcom Limited         | 3         | 2.52%   |
| RDC Semiconductor        | 1         | 0.84%   |
| Nvidia                   | 1         | 0.84%   |
| D-Link System            | 1         | 0.84%   |
| ASIX Electronics         | 1         | 0.84%   |
| Aquantia                 | 1         | 0.84%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 52        | 42.62%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7         | 5.74%   |
| Intel I211 Gigabit Network Connection                                         | 5         | 4.1%    |
| Intel Ethernet Connection I217-V                                              | 5         | 4.1%    |
| Realtek RTL8125 2.5GbE Controller                                             | 4         | 3.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 2.46%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 3         | 2.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2         | 1.64%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 1.64%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 1.64%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 1.64%   |
| Intel 82579V Gigabit Network Connection                                       | 2         | 1.64%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 2         | 1.64%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 2         | 1.64%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                | 2         | 1.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.82%   |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 1         | 0.82%   |
| RDC R6040 MAC Controller                                                      | 1         | 0.82%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1         | 0.82%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                         | 1         | 0.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.82%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.82%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 0.82%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                       | 1         | 0.82%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 0.82%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                       | 1         | 0.82%   |
| Intel I210 Gigabit Network Connection                                         | 1         | 0.82%   |
| Intel Ethernet Controller I225-V                                              | 1         | 0.82%   |
| Intel Ethernet Connection I219-V                                              | 1         | 0.82%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 0.82%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1         | 0.82%   |
| Intel Ethernet Connection (17) I219-LM                                        | 1         | 0.82%   |
| Intel Ethernet Connection (14) I219-LM                                        | 1         | 0.82%   |
| Intel 82574L Gigabit Network Connection                                       | 1         | 0.82%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.82%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1         | 0.82%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 1         | 0.82%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                       | 1         | 0.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 113       | 59.79%  |
| WiFi     | 74        | 39.15%  |
| Modem    | 1         | 0.53%   |
| Unknown  | 1         | 0.53%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 75        | 57.25%  |
| WiFi     | 56        | 42.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 66        | 50%     |
| 2     | 56        | 42.42%  |
| 3     | 5         | 3.79%   |
| 0     | 4         | 3.03%   |
| 4     | 1         | 0.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 99        | 75.57%  |
| Yes  | 32        | 24.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 28        | 40%     |
| Cambridge Silicon Radio | 9         | 12.86%  |
| Realtek Semiconductor   | 7         | 10%     |
| IMC Networks            | 5         | 7.14%   |
| Hewlett-Packard         | 3         | 4.29%   |
| Broadcom                | 3         | 4.29%   |
| ASUSTek Computer        | 3         | 4.29%   |
| Lite-On Technology      | 2         | 2.86%   |
| Foxconn / Hon Hai       | 2         | 2.86%   |
| Belkin Components       | 2         | 2.86%   |
| TP-Link                 | 1         | 1.43%   |
| Taiyo Yuden             | 1         | 1.43%   |
| MediaTek                | 1         | 1.43%   |
| Marvell Semiconductor   | 1         | 1.43%   |
| Dell                    | 1         | 1.43%   |
| Apple                   | 1         | 1.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9         | 12.86%  |
| Intel Bluetooth wireless interface                  | 8         | 11.43%  |
| Realtek Bluetooth Radio                             | 4         | 5.71%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 5.71%   |
| Intel Bluetooth Device                              | 4         | 5.71%   |
| Intel AX200 Bluetooth                               | 4         | 5.71%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 4.29%   |
| Lite-On Bluetooth Device                            | 2         | 2.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 2.86%   |
| IMC Networks Bluetooth Device                       | 2         | 2.86%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 2.86%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 2.86%   |
| TP-Link UB500 Adapter                               | 1         | 1.43%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 1         | 1.43%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.43%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.43%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 1.43%   |
| MediaTek MT7630e Bluetooth Adapter                  | 1         | 1.43%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 1.43%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.43%   |
| Intel AX211 Bluetooth                               | 1         | 1.43%   |
| Intel AX201 Bluetooth                               | 1         | 1.43%   |
| IMC Networks Wireless_Device                        | 1         | 1.43%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.43%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.43%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.43%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.43%   |
| Broadcom Bluetooth dongle                           | 1         | 1.43%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.43%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.43%   |
| Belkin Components F8T013 Bluetooth Adapter          | 1         | 1.43%   |
| Belkin Components Bluetooth Mini Dongle             | 1         | 1.43%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.43%   |
| ASUS Bluetooth Device                               | 1         | 1.43%   |
| ASUS BCM20702A0                                     | 1         | 1.43%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 1.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 86        | 45.74%  |
| Nvidia                     | 44        | 23.4%   |
| AMD                        | 41        | 21.81%  |
| C-Media Electronics        | 9         | 4.79%   |
| Samsung Electronics        | 1         | 0.53%   |
| Mackie Designs             | 1         | 0.53%   |
| Logitech                   | 1         | 0.53%   |
| iCreate Technologies       | 1         | 0.53%   |
| Corsair                    | 1         | 0.53%   |
| BEHRINGER International    | 1         | 0.53%   |
| ASUSTek Computer           | 1         | 0.53%   |
| Altec Lansing Technologies | 1         | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 5.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10        | 4.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 4.61%   |
| Intel Sunrise Point-LP HD Audio                                            | 9         | 4.15%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 9         | 4.15%   |
| AMD Family 17h/19h HD Audio Controller                                     | 8         | 3.69%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7         | 3.23%   |
| Nvidia GF108 High Definition Audio Controller                              | 7         | 3.23%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 3.23%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7         | 3.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6         | 2.76%   |
| Nvidia GP106 High Definition Audio Controller                              | 5         | 2.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2.3%    |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 1.84%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 1.84%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 4         | 1.84%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.84%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.38%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 1.38%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.38%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 3         | 1.38%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 3         | 1.38%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 1.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.38%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.38%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 0.92%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.92%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 0.92%   |
| Nvidia Audio device                                                        | 2         | 0.92%   |
| Intel Comet Lake PCH-V cAVS                                                | 2         | 0.92%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2         | 0.92%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.92%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 0.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 0.92%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 0.92%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 2         | 0.92%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 0.92%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 0.92%   |
| Samsung Electronics Samsung USB C Earphones                                | 1         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 23        | 22.77%  |
| Samsung Electronics | 22        | 21.78%  |
| Unknown             | 16        | 15.84%  |
| SK hynix            | 9         | 8.91%   |
| G.Skill             | 6         | 5.94%   |
| Micron Technology   | 5         | 4.95%   |
| Corsair             | 5         | 4.95%   |
| Unknown (ABCD)      | 2         | 1.98%   |
| Team                | 2         | 1.98%   |
| Crucial             | 2         | 1.98%   |
| Smart               | 1         | 0.99%   |
| Silicon Power       | 1         | 0.99%   |
| Ramaxel Technology  | 1         | 0.99%   |
| Nanya Technology    | 1         | 0.99%   |
| Lexar               | 1         | 0.99%   |
| GOODRAM             | 1         | 0.99%   |
| CSX                 | 1         | 0.99%   |
| A-DATA Technology   | 1         | 0.99%   |
| Unknown             | 1         | 0.99%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 2.78%   |
| Kingston RAM KHX2400C15/16G 16384MB DIMM DDR4 3334MT/s           | 3         | 2.78%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 2         | 1.85%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.85%   |
| Samsung RAM M4 70T5663QZ3-CE6 2GB SODIMM DDR2 667MT/s            | 2         | 1.85%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 1.85%   |
| G.Skill RAM F3-12800CL9-4GBXM 4096MB DIMM DDR3 1600MT/s          | 2         | 1.85%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.93%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                    | 1         | 0.93%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 0.93%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.93%   |
| Unknown RAM Module 4GB DIMM 667MT/s                              | 1         | 0.93%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 1         | 0.93%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                           | 1         | 0.93%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.93%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.93%   |
| Unknown RAM Module 2GB SODIMM 533MT/s                            | 1         | 0.93%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.93%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 0.93%   |
| Unknown RAM Module 2048MB SODIMM DDR2 975MT/s                    | 1         | 0.93%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 0.93%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.93%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                           | 1         | 0.93%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                      | 1         | 0.93%   |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                      | 1         | 0.93%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 1         | 0.93%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.93%   |
| Team RAM Elite-16 8GB DIMM DDR3 1600MT/s                         | 1         | 0.93%   |
| Team RAM Elite-1333 2GB DIMM DDR3 1333MT/s                       | 1         | 0.93%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.93%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.93%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                     | 1         | 0.93%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 1639MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.93%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.93%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 0.93%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 0.93%   |
| Silicon Power RAM D8LR2GNC88S 2GB DIMM SDRAM 2048MT/s            | 1         | 0.93%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 38        | 42.7%   |
| DDR4    | 30        | 33.71%  |
| SDRAM   | 6         | 6.74%   |
| DDR2    | 5         | 5.62%   |
| Unknown | 5         | 5.62%   |
| LPDDR4  | 2         | 2.25%   |
| LPDDR3  | 2         | 2.25%   |
| LPDDR5  | 1         | 1.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 45        | 53.57%  |
| SODIMM       | 37        | 44.05%  |
| Row Of Chips | 2         | 2.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 35        | 36.84%  |
| 4096  | 31        | 32.63%  |
| 2048  | 14        | 14.74%  |
| 16384 | 11        | 11.58%  |
| 1024  | 4         | 4.21%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 28        | 29.47%  |
| 1333  | 9         | 9.47%   |
| 3200  | 8         | 8.42%   |
| 2400  | 8         | 8.42%   |
| 2133  | 5         | 5.26%   |
| 2667  | 4         | 4.21%   |
| 800   | 4         | 4.21%   |
| 3334  | 3         | 3.16%   |
| 667   | 3         | 3.16%   |
| 4199  | 2         | 2.11%   |
| 3733  | 2         | 2.11%   |
| 3600  | 2         | 2.11%   |
| 1867  | 2         | 2.11%   |
| 1334  | 2         | 2.11%   |
| 1066  | 2         | 2.11%   |
| 6400  | 1         | 1.05%   |
| 3500  | 1         | 1.05%   |
| 3466  | 1         | 1.05%   |
| 3400  | 1         | 1.05%   |
| 3266  | 1         | 1.05%   |
| 3000  | 1         | 1.05%   |
| 2048  | 1         | 1.05%   |
| 1866  | 1         | 1.05%   |
| 1639  | 1         | 1.05%   |
| 975   | 1         | 1.05%   |
| 533   | 1         | 1.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 33.33%  |
| Brother Industries  | 2         | 22.22%  |
| Xerox               | 1         | 11.11%  |
| Seiko Epson         | 1         | 11.11%  |
| Samsung Electronics | 1         | 11.11%  |
| Canon               | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Xerox Phaser 3140 and 3155    | 1         | 11.11%  |
| Seiko Epson WF-2530 Series    | 1         | 11.11%  |
| Samsung CLP-300 Series        | 1         | 11.11%  |
| HP OfficeJet Pro 6970         | 1         | 11.11%  |
| HP OfficeJet 6950             | 1         | 11.11%  |
| HP DeskJet 840c               | 1         | 11.11%  |
| Canon PIXMA MG3600 Series     | 1         | 11.11%  |
| Brother QL-570 Label Printer  | 1         | 11.11%  |
| Brother HL-2030 Laser Printer | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 4         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Seiko Epson Scanner                     | 1         | 25%     |
| Seiko Epson GT-X770 [Perfection V500]   | 1         | 25%     |
| Seiko Epson GT-9800F [Perfection 3200]  | 1         | 25%     |
| Seiko Epson GT-7700U [Perfection 1240U] | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 13        | 20.97%  |
| Logitech                               | 8         | 12.9%   |
| Microdia                               | 5         | 8.06%   |
| Realtek Semiconductor                  | 4         | 6.45%   |
| IMC Networks                           | 4         | 6.45%   |
| Lite-On Technology                     | 3         | 4.84%   |
| Bison Electronics                      | 3         | 4.84%   |
| Apple                                  | 3         | 4.84%   |
| Suyin                                  | 2         | 3.23%   |
| Sunplus Innovation Technology          | 2         | 3.23%   |
| Microsoft                              | 2         | 3.23%   |
| Luxvisions Innotech Limited            | 2         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.23%   |
| Alcor Micro                            | 2         | 3.23%   |
| Xiongmai                               | 1         | 1.61%   |
| WaveRider Communications               | 1         | 1.61%   |
| Sunplus IT                             | 1         | 1.61%   |
| Sonix Technology                       | 1         | 1.61%   |
| Primax Electronics                     | 1         | 1.61%   |
| Leap Motion                            | 1         | 1.61%   |
| Huawei Technologies                    | 1         | 1.61%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                | 3         | 4.76%   |
| Chicony USB2.0 Camera                                       | 3         | 4.76%   |
| Chicony Integrated Camera                                   | 3         | 4.76%   |
| Microdia Camera                                             | 2         | 3.17%   |
| Lite-On HP HD Webcam                                        | 2         | 3.17%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 3.17%   |
| Chicony FJ Camera                                           | 2         | 3.17%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                             | 2         | 3.17%   |
| Xiongmai web camera                                         | 1         | 1.59%   |
| WaveRider USB 2.0 Camera                                    | 1         | 1.59%   |
| Suyin HP TrueVision HD Integrated Webcam                    | 1         | 1.59%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 1.59%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                          | 1         | 1.59%   |
| Sunplus Full HD webcam                                      | 1         | 1.59%   |
| Sunplus Dell E5570 integrated webcam                        | 1         | 1.59%   |
| Sonix USB2.0 FHD UVC WebCam                                 | 1         | 1.59%   |
| Realtek USB Camera                                          | 1         | 1.59%   |
| Primax HP Truevision FHD                                    | 1         | 1.59%   |
| Microsoft LifeCam VX-800                                    | 1         | 1.59%   |
| Microsoft LifeCam HD-3000                                   | 1         | 1.59%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 1.59%   |
| Microdia Integrated_Webcam_HD                               | 1         | 1.59%   |
| Microdia Integrated Webcam                                  | 1         | 1.59%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 1.59%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 1         | 1.59%   |
| Logitech Webcam C270                                        | 1         | 1.59%   |
| Logitech Webcam C210                                        | 1         | 1.59%   |
| Logitech Webcam C200                                        | 1         | 1.59%   |
| Logitech Webcam C110                                        | 1         | 1.59%   |
| Logitech QuickCam Pro 9000                                  | 1         | 1.59%   |
| Logitech QuickCam Communicate Deluxe                        | 1         | 1.59%   |
| Logitech HD Pro Webcam C920                                 | 1         | 1.59%   |
| Logitech Fujitsu Webcam                                     | 1         | 1.59%   |
| Lite-On HP Webcam                                           | 1         | 1.59%   |
| Leap Motion Controller                                      | 1         | 1.59%   |
| IMC Networks USB2.0 UVC HD Webcam                           | 1         | 1.59%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 1.59%   |
| Huawei HiCamera                                             | 1         | 1.59%   |
| Chicony TOSHIBA Web Camera - FHD                            | 1         | 1.59%   |
| Chicony Lenovo EasyCamera                                   | 1         | 1.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 4         | 33.33%  |
| AuthenTec                          | 4         | 33.33%  |
| Shenzhen Goodix Technology         | 2         | 16.67%  |
| Synaptics                          | 1         | 8.33%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor                            | 3         | 25%     |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 8.33%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 8.33%   |
| Validity Sensors Synaptics WBDI                                 | 1         | 8.33%   |
| Validity Sensors Fingerprint scanner                            | 1         | 8.33%   |
| Synaptics  WBDI                                                 | 1         | 8.33%   |
| Shenzhen Goodix  FingerPrint Device                             | 1         | 8.33%   |
| Shenzhen Goodix Fingerprint Reader                              | 1         | 8.33%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 8.33%   |
| AuthenTec Fingerprint Sensor                                    | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 42.86%  |
| O2 Micro | 2         | 28.57%  |
| Bit4id   | 1         | 14.29%  |
| Avtor    | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 28.57%  |
| Broadcom 5880                                                                | 2         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 14.29%  |
| Bit4id miniLector EVO                                                        | 1         | 14.29%  |
| Avtor SecureToken                                                            | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 92        | 69.7%   |
| 1     | 29        | 21.97%  |
| 2     | 8         | 6.06%   |
| 3     | 3         | 2.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 16        | 32.65%  |
| Fingerprint reader       | 12        | 24.49%  |
| Chipcard                 | 7         | 14.29%  |
| Net/wireless             | 4         | 8.16%   |
| Multimedia controller    | 3         | 6.12%   |
| Sound                    | 2         | 4.08%   |
| Unassigned class         | 1         | 2.04%   |
| Storage                  | 1         | 2.04%   |
| Communication controller | 1         | 2.04%   |
| Camera                   | 1         | 2.04%   |
| Bluetooth                | 1         | 2.04%   |

