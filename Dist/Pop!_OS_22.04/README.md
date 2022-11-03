Pop!_OS 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pop!_OS_22.04/Desktop/README.md) and [notebooks](/Dist/Pop!_OS_22.04/Notebook/README.md).

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

Total: 1838

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [77f847ca29](https://linux-hardware.org/?probe=77f847ca29) | Nov 02, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [d9de10d93e](https://linux-hardware.org/?probe=d9de10d93e) | Nov 02, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [4191ce8788](https://linux-hardware.org/?probe=4191ce8788) | Nov 02, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [036ff9e51f](https://linux-hardware.org/?probe=036ff9e51f) | Nov 02, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [d5d1583252](https://linux-hardware.org/?probe=d5d1583252) | Nov 02, 2022 |
| Microsoft     | Surface Book                | Tablet      | [e4a7690a77](https://linux-hardware.org/?probe=e4a7690a77) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4e97493141](https://linux-hardware.org/?probe=4e97493141) | Nov 02, 2022 |
| HP            | 212A                        | Desktop     | [80abe48959](https://linux-hardware.org/?probe=80abe48959) | Nov 02, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [0f40b36846](https://linux-hardware.org/?probe=0f40b36846) | Nov 02, 2022 |
| PC Special... | Elimina Iv 15               | Notebook    | [f462ba9c43](https://linux-hardware.org/?probe=f462ba9c43) | Nov 02, 2022 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [d4af3b0745](https://linux-hardware.org/?probe=d4af3b0745) | Nov 01, 2022 |
| Intel Clie... | CMCN1CC                     | Notebook    | [719731b244](https://linux-hardware.org/?probe=719731b244) | Nov 01, 2022 |
| Dell          | Latitude E7240              | Notebook    | [effafc033d](https://linux-hardware.org/?probe=effafc033d) | Nov 01, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [e08326bc94](https://linux-hardware.org/?probe=e08326bc94) | Nov 01, 2022 |
| Dell          | G5 5587                     | Notebook    | [a4e32e9eb8](https://linux-hardware.org/?probe=a4e32e9eb8) | Nov 01, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81JM     | Notebook    | [da8fec7ac4](https://linux-hardware.org/?probe=da8fec7ac4) | Nov 01, 2022 |
| ASUSTek       | H110M-D                     | Desktop     | [248b9533a3](https://linux-hardware.org/?probe=248b9533a3) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [6db184e152](https://linux-hardware.org/?probe=6db184e152) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [60cfb7dcc6](https://linux-hardware.org/?probe=60cfb7dcc6) | Nov 01, 2022 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [0f62f6f3b1](https://linux-hardware.org/?probe=0f62f6f3b1) | Nov 01, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [11de150949](https://linux-hardware.org/?probe=11de150949) | Nov 01, 2022 |
| Dell          | Latitude E7240              | Notebook    | [d8ae1a7195](https://linux-hardware.org/?probe=d8ae1a7195) | Nov 01, 2022 |
| ASUSTek       | H97-PRO                     | Desktop     | [bae404d45c](https://linux-hardware.org/?probe=bae404d45c) | Oct 31, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [d284b1709a](https://linux-hardware.org/?probe=d284b1709a) | Oct 31, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [87187c0e23](https://linux-hardware.org/?probe=87187c0e23) | Oct 31, 2022 |
| Sony          | VAIO                        | All in one  | [cefad415d0](https://linux-hardware.org/?probe=cefad415d0) | Oct 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4c3ae53c16](https://linux-hardware.org/?probe=4c3ae53c16) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [325516bbce](https://linux-hardware.org/?probe=325516bbce) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [740d19ba42](https://linux-hardware.org/?probe=740d19ba42) | Oct 31, 2022 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | Notebook    | [c6a13e1ab3](https://linux-hardware.org/?probe=c6a13e1ab3) | Oct 31, 2022 |
| Dell          | 02P9X9 A00                  | Server      | [4fa081a282](https://linux-hardware.org/?probe=4fa081a282) | Oct 31, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [43a99f49f8](https://linux-hardware.org/?probe=43a99f49f8) | Oct 31, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [b4fedd7c20](https://linux-hardware.org/?probe=b4fedd7c20) | Oct 31, 2022 |
| Dell          | Precision M6700             | Notebook    | [e5952f6f57](https://linux-hardware.org/?probe=e5952f6f57) | Oct 31, 2022 |
| HP            | ENVY NOTEBOOK PC            | Notebook    | [f2893aaedf](https://linux-hardware.org/?probe=f2893aaedf) | Oct 31, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [56ee27b737](https://linux-hardware.org/?probe=56ee27b737) | Oct 31, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [64d1c159aa](https://linux-hardware.org/?probe=64d1c159aa) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | Notebook    | [4591ea2ad6](https://linux-hardware.org/?probe=4591ea2ad6) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | Notebook    | [5dd8b365d6](https://linux-hardware.org/?probe=5dd8b365d6) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [424aaaf5bd](https://linux-hardware.org/?probe=424aaaf5bd) | Oct 30, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e638ed7bd3](https://linux-hardware.org/?probe=e638ed7bd3) | Oct 30, 2022 |
| Toshiba       | Satellite C855-1T5          | Notebook    | [c07f6a167a](https://linux-hardware.org/?probe=c07f6a167a) | Oct 30, 2022 |
| HP            | 3048h                       | Desktop     | [6ce1d2bf43](https://linux-hardware.org/?probe=6ce1d2bf43) | Oct 30, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [189fca8ab3](https://linux-hardware.org/?probe=189fca8ab3) | Oct 30, 2022 |
| Tactus        | GeoBook 140                 | Notebook    | [71f32a229a](https://linux-hardware.org/?probe=71f32a229a) | Oct 30, 2022 |
| HP            | Pavilion dv7                | Notebook    | [6ff9a469f7](https://linux-hardware.org/?probe=6ff9a469f7) | Oct 30, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4bc0220a01](https://linux-hardware.org/?probe=4bc0220a01) | Oct 30, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bd18c2b33d](https://linux-hardware.org/?probe=bd18c2b33d) | Oct 29, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [ab324c3cdd](https://linux-hardware.org/?probe=ab324c3cdd) | Oct 29, 2022 |
| Apple         | MacBookPro3,1               | Notebook    | [27a5553057](https://linux-hardware.org/?probe=27a5553057) | Oct 29, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [0616272661](https://linux-hardware.org/?probe=0616272661) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [8f48ae7586](https://linux-hardware.org/?probe=8f48ae7586) | Oct 29, 2022 |
| MSI           | GE60 0NC\0ND                | Notebook    | [79bd38da8f](https://linux-hardware.org/?probe=79bd38da8f) | Oct 29, 2022 |
| Samsung       | 800G5M/800G5W               | Notebook    | [d688233d28](https://linux-hardware.org/?probe=d688233d28) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [8f1f41f3b0](https://linux-hardware.org/?probe=8f1f41f3b0) | Oct 29, 2022 |
| ASUSTek       | ZenBook Q406DA              | Convertible | [f8bae249b9](https://linux-hardware.org/?probe=f8bae249b9) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [1c5d979ba1](https://linux-hardware.org/?probe=1c5d979ba1) | Oct 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [77ef1a661c](https://linux-hardware.org/?probe=77ef1a661c) | Oct 29, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [cc0f34a2fa](https://linux-hardware.org/?probe=cc0f34a2fa) | Oct 29, 2022 |
| Intel         | B75                         | Desktop     | [59cc97d6c7](https://linux-hardware.org/?probe=59cc97d6c7) | Oct 28, 2022 |
| MSI           | Prestige 15 A12UC           | Notebook    | [3d4c4364f1](https://linux-hardware.org/?probe=3d4c4364f1) | Oct 28, 2022 |
| Notebook      | NV4xPZ                      | Notebook    | [86e7370778](https://linux-hardware.org/?probe=86e7370778) | Oct 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [9dcb685f5e](https://linux-hardware.org/?probe=9dcb685f5e) | Oct 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [df9ef8c115](https://linux-hardware.org/?probe=df9ef8c115) | Oct 28, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [c9cd061f05](https://linux-hardware.org/?probe=c9cd061f05) | Oct 28, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [4fa08c7d6f](https://linux-hardware.org/?probe=4fa08c7d6f) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3e6896ee0a](https://linux-hardware.org/?probe=3e6896ee0a) | Oct 28, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [2fdc53f0f3](https://linux-hardware.org/?probe=2fdc53f0f3) | Oct 28, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [04d54cb9c8](https://linux-hardware.org/?probe=04d54cb9c8) | Oct 28, 2022 |
| Dell          | Precision 5530              | Notebook    | [bb4d35f452](https://linux-hardware.org/?probe=bb4d35f452) | Oct 28, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [d04e962e56](https://linux-hardware.org/?probe=d04e962e56) | Oct 28, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [0957761dea](https://linux-hardware.org/?probe=0957761dea) | Oct 28, 2022 |
| Lenovo        | Legion Y540-15IRH 81RJ      | Notebook    | [a90eba59e8](https://linux-hardware.org/?probe=a90eba59e8) | Oct 28, 2022 |
| Pegatron      | TRUCKEE                     | Desktop     | [2a6fe2bcd1](https://linux-hardware.org/?probe=2a6fe2bcd1) | Oct 28, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [b82aebb005](https://linux-hardware.org/?probe=b82aebb005) | Oct 28, 2022 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [9031f7b82b](https://linux-hardware.org/?probe=9031f7b82b) | Oct 27, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [f27c4e1041](https://linux-hardware.org/?probe=f27c4e1041) | Oct 27, 2022 |
| System76      | Oryx Pro                    | Notebook    | [ff42b6e74a](https://linux-hardware.org/?probe=ff42b6e74a) | Oct 27, 2022 |
| Novatech      | NLx0MU                      | Notebook    | [41c5d984a0](https://linux-hardware.org/?probe=41c5d984a0) | Oct 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [e7db99be75](https://linux-hardware.org/?probe=e7db99be75) | Oct 27, 2022 |
| MSI           | B85-G43                     | Desktop     | [48ac016cd9](https://linux-hardware.org/?probe=48ac016cd9) | Oct 27, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [cca0d420fe](https://linux-hardware.org/?probe=cca0d420fe) | Oct 27, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [304a013939](https://linux-hardware.org/?probe=304a013939) | Oct 27, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [9f7121381b](https://linux-hardware.org/?probe=9f7121381b) | Oct 27, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9e7c028b0b](https://linux-hardware.org/?probe=9e7c028b0b) | Oct 27, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [ada4cec1b7](https://linux-hardware.org/?probe=ada4cec1b7) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [022cfe6707](https://linux-hardware.org/?probe=022cfe6707) | Oct 26, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [97d2bacb5d](https://linux-hardware.org/?probe=97d2bacb5d) | Oct 26, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [cb657f604d](https://linux-hardware.org/?probe=cb657f604d) | Oct 26, 2022 |
| Acer          | Aspire A515-52              | Notebook    | [81371581d1](https://linux-hardware.org/?probe=81371581d1) | Oct 26, 2022 |
| Gigabyte      | AERO 15 Classic-SA          | Notebook    | [7977a48aca](https://linux-hardware.org/?probe=7977a48aca) | Oct 26, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [daf7975ca0](https://linux-hardware.org/?probe=daf7975ca0) | Oct 26, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [1ede815931](https://linux-hardware.org/?probe=1ede815931) | Oct 26, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [9deeea3723](https://linux-hardware.org/?probe=9deeea3723) | Oct 26, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [58af9b9a77](https://linux-hardware.org/?probe=58af9b9a77) | Oct 26, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [2b6b8d3854](https://linux-hardware.org/?probe=2b6b8d3854) | Oct 26, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [892c5e2cda](https://linux-hardware.org/?probe=892c5e2cda) | Oct 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [b98bd6b361](https://linux-hardware.org/?probe=b98bd6b361) | Oct 26, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [1603f6064b](https://linux-hardware.org/?probe=1603f6064b) | Oct 26, 2022 |
| Lenovo        | ThinkPad X260 20F600A4MD    | Notebook    | [50cce404c7](https://linux-hardware.org/?probe=50cce404c7) | Oct 25, 2022 |
| Avell High... | A62 LIV                     | Notebook    | [673f411692](https://linux-hardware.org/?probe=673f411692) | Oct 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [3375318388](https://linux-hardware.org/?probe=3375318388) | Oct 25, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [7f9028d036](https://linux-hardware.org/?probe=7f9028d036) | Oct 25, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [a26efdcfb5](https://linux-hardware.org/?probe=a26efdcfb5) | Oct 25, 2022 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [c838769296](https://linux-hardware.org/?probe=c838769296) | Oct 25, 2022 |
| HP            | ZBook 15                    | Notebook    | [b2d2352668](https://linux-hardware.org/?probe=b2d2352668) | Oct 25, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [b31fec75e1](https://linux-hardware.org/?probe=b31fec75e1) | Oct 25, 2022 |
| Dell          | G15 5511                    | Notebook    | [0f47c64bab](https://linux-hardware.org/?probe=0f47c64bab) | Oct 25, 2022 |
| MSI           | H61M-P31/W8                 | Desktop     | [7ba2ecf5f0](https://linux-hardware.org/?probe=7ba2ecf5f0) | Oct 25, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [3cd266dbbb](https://linux-hardware.org/?probe=3cd266dbbb) | Oct 25, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [c77d3dfeba](https://linux-hardware.org/?probe=c77d3dfeba) | Oct 25, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [d03f6896eb](https://linux-hardware.org/?probe=d03f6896eb) | Oct 25, 2022 |
| Dell          | Latitude E7240              | Notebook    | [6966cfc71f](https://linux-hardware.org/?probe=6966cfc71f) | Oct 25, 2022 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [7c4edd1a6d](https://linux-hardware.org/?probe=7c4edd1a6d) | Oct 24, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [d76c41ef1b](https://linux-hardware.org/?probe=d76c41ef1b) | Oct 24, 2022 |
| Dell          | Inspiron 16 7610            | Notebook    | [47a3e2b5f6](https://linux-hardware.org/?probe=47a3e2b5f6) | Oct 24, 2022 |
| Lenovo        | ThinkPad L380 Yoga 20M7C... | Convertible | [c9577d0d5a](https://linux-hardware.org/?probe=c9577d0d5a) | Oct 24, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [df05c11ff4](https://linux-hardware.org/?probe=df05c11ff4) | Oct 24, 2022 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [2510215a0b](https://linux-hardware.org/?probe=2510215a0b) | Oct 24, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [0a2cbff604](https://linux-hardware.org/?probe=0a2cbff604) | Oct 24, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [3a8627fb53](https://linux-hardware.org/?probe=3a8627fb53) | Oct 24, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [c271de3628](https://linux-hardware.org/?probe=c271de3628) | Oct 24, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [3749438ef1](https://linux-hardware.org/?probe=3749438ef1) | Oct 24, 2022 |
| MSI           | 970A-G46                    | Desktop     | [38541ac772](https://linux-hardware.org/?probe=38541ac772) | Oct 24, 2022 |
| System76      | Gazelle                     | Notebook    | [77686d0854](https://linux-hardware.org/?probe=77686d0854) | Oct 24, 2022 |
| HP            | Laptop 15s-gy0xxx           | Notebook    | [d1219c1387](https://linux-hardware.org/?probe=d1219c1387) | Oct 23, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [c70d6b90b6](https://linux-hardware.org/?probe=c70d6b90b6) | Oct 23, 2022 |
| ASUSTek       | A88X-PLUS                   | Desktop     | [7435d326b7](https://linux-hardware.org/?probe=7435d326b7) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [bd25fa1073](https://linux-hardware.org/?probe=bd25fa1073) | Oct 23, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [edd13bcc76](https://linux-hardware.org/?probe=edd13bcc76) | Oct 23, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [04ea0c7dd2](https://linux-hardware.org/?probe=04ea0c7dd2) | Oct 23, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [153aaa07cd](https://linux-hardware.org/?probe=153aaa07cd) | Oct 23, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [9380dfc8b7](https://linux-hardware.org/?probe=9380dfc8b7) | Oct 23, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [cfb362baf3](https://linux-hardware.org/?probe=cfb362baf3) | Oct 23, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [5d14f79724](https://linux-hardware.org/?probe=5d14f79724) | Oct 23, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [4884be1a24](https://linux-hardware.org/?probe=4884be1a24) | Oct 22, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [426ddc8fdb](https://linux-hardware.org/?probe=426ddc8fdb) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [e14654d246](https://linux-hardware.org/?probe=e14654d246) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c0867dfce4](https://linux-hardware.org/?probe=c0867dfce4) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6199e2daaa](https://linux-hardware.org/?probe=6199e2daaa) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [dc48a995c4](https://linux-hardware.org/?probe=dc48a995c4) | Oct 22, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [32a9b1de4f](https://linux-hardware.org/?probe=32a9b1de4f) | Oct 22, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [079a05485d](https://linux-hardware.org/?probe=079a05485d) | Oct 22, 2022 |
| System76      | Oryx Pro                    | Notebook    | [7de5d55c99](https://linux-hardware.org/?probe=7de5d55c99) | Oct 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | Desktop     | [32cd9cd246](https://linux-hardware.org/?probe=32cd9cd246) | Oct 22, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [b2cc208474](https://linux-hardware.org/?probe=b2cc208474) | Oct 22, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [1056e456bc](https://linux-hardware.org/?probe=1056e456bc) | Oct 22, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [d8f21a8ec6](https://linux-hardware.org/?probe=d8f21a8ec6) | Oct 22, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [9f293160d5](https://linux-hardware.org/?probe=9f293160d5) | Oct 22, 2022 |
| Intel         | Montevina CRB               | Notebook    | [11cb344c52](https://linux-hardware.org/?probe=11cb344c52) | Oct 22, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | Desktop     | [624b9f3b57](https://linux-hardware.org/?probe=624b9f3b57) | Oct 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [1227d6561e](https://linux-hardware.org/?probe=1227d6561e) | Oct 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [15c764f6fa](https://linux-hardware.org/?probe=15c764f6fa) | Oct 21, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [2a9b4f61c6](https://linux-hardware.org/?probe=2a9b4f61c6) | Oct 21, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [fb86c213ca](https://linux-hardware.org/?probe=fb86c213ca) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [ed692d6080](https://linux-hardware.org/?probe=ed692d6080) | Oct 21, 2022 |
| Razer x La... | TensorBook (late 2021)      | Notebook    | [27cae45787](https://linux-hardware.org/?probe=27cae45787) | Oct 20, 2022 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [504036a2f6](https://linux-hardware.org/?probe=504036a2f6) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [02b0d2ded2](https://linux-hardware.org/?probe=02b0d2ded2) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [ddee1b5408](https://linux-hardware.org/?probe=ddee1b5408) | Oct 20, 2022 |
| System76      | Lemur Pro                   | Notebook    | [df61411c9d](https://linux-hardware.org/?probe=df61411c9d) | Oct 20, 2022 |
| Dell          | 0HY175 A03                  | Desktop     | [86950688ac](https://linux-hardware.org/?probe=86950688ac) | Oct 20, 2022 |
| Dell          | 0HY175 A03                  | Desktop     | [ede27fb1d0](https://linux-hardware.org/?probe=ede27fb1d0) | Oct 19, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [8a872b5819](https://linux-hardware.org/?probe=8a872b5819) | Oct 19, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [b4afec070e](https://linux-hardware.org/?probe=b4afec070e) | Oct 19, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [d565cdf4a5](https://linux-hardware.org/?probe=d565cdf4a5) | Oct 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [c14937070e](https://linux-hardware.org/?probe=c14937070e) | Oct 19, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [a8170f7786](https://linux-hardware.org/?probe=a8170f7786) | Oct 19, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [ca39605260](https://linux-hardware.org/?probe=ca39605260) | Oct 18, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [08327d561d](https://linux-hardware.org/?probe=08327d561d) | Oct 18, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [2a51555c53](https://linux-hardware.org/?probe=2a51555c53) | Oct 18, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [c6e10b3bcb](https://linux-hardware.org/?probe=c6e10b3bcb) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [c84509fb21](https://linux-hardware.org/?probe=c84509fb21) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [e3ce426450](https://linux-hardware.org/?probe=e3ce426450) | Oct 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [ed64a103f1](https://linux-hardware.org/?probe=ed64a103f1) | Oct 18, 2022 |
| HP            | Laptop 15-dy0xxx            | Notebook    | [2d1482e433](https://linux-hardware.org/?probe=2d1482e433) | Oct 18, 2022 |
| HP            | 339A                        | Desktop     | [e168e3b75b](https://linux-hardware.org/?probe=e168e3b75b) | Oct 18, 2022 |
| System76      | Lemur Pro                   | Notebook    | [53226822f5](https://linux-hardware.org/?probe=53226822f5) | Oct 18, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [d522208941](https://linux-hardware.org/?probe=d522208941) | Oct 17, 2022 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [40771441a2](https://linux-hardware.org/?probe=40771441a2) | Oct 17, 2022 |
| Lenovo        | Legion Y740-17IRH 81UG      | Notebook    | [67aec6ad33](https://linux-hardware.org/?probe=67aec6ad33) | Oct 17, 2022 |
| MSI           | GP72VR 7RF                  | Notebook    | [86a4902866](https://linux-hardware.org/?probe=86a4902866) | Oct 17, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [e8e5ae4784](https://linux-hardware.org/?probe=e8e5ae4784) | Oct 17, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [40c27af11f](https://linux-hardware.org/?probe=40c27af11f) | Oct 17, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [25fdbfba33](https://linux-hardware.org/?probe=25fdbfba33) | Oct 17, 2022 |
| Dell          | Latitude E6430s             | Notebook    | [ca202dddd6](https://linux-hardware.org/?probe=ca202dddd6) | Oct 17, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [bab2e8dad2](https://linux-hardware.org/?probe=bab2e8dad2) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [0a30a79788](https://linux-hardware.org/?probe=0a30a79788) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [a4f5a5b0be](https://linux-hardware.org/?probe=a4f5a5b0be) | Oct 17, 2022 |
| HP            | G62                         | Notebook    | [839b09744e](https://linux-hardware.org/?probe=839b09744e) | Oct 17, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [dfdde1675c](https://linux-hardware.org/?probe=dfdde1675c) | Oct 17, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [b7ea5640c2](https://linux-hardware.org/?probe=b7ea5640c2) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [e2991c4619](https://linux-hardware.org/?probe=e2991c4619) | Oct 17, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [0ec570b33c](https://linux-hardware.org/?probe=0ec570b33c) | Oct 16, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [def577cdb8](https://linux-hardware.org/?probe=def577cdb8) | Oct 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [bf7cebc10e](https://linux-hardware.org/?probe=bf7cebc10e) | Oct 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0e0a3b9cf0](https://linux-hardware.org/?probe=0e0a3b9cf0) | Oct 16, 2022 |
| HP            | ENVY 17                     | Notebook    | [ab25d54223](https://linux-hardware.org/?probe=ab25d54223) | Oct 16, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [502f19e8b3](https://linux-hardware.org/?probe=502f19e8b3) | Oct 16, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [3c2eef945d](https://linux-hardware.org/?probe=3c2eef945d) | Oct 16, 2022 |
| ASRock        | X570 Phantom Gaming 4 Wi... | Desktop     | [d91f9fb542](https://linux-hardware.org/?probe=d91f9fb542) | Oct 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [daaa9d8dcc](https://linux-hardware.org/?probe=daaa9d8dcc) | Oct 16, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [b7ebef4e11](https://linux-hardware.org/?probe=b7ebef4e11) | Oct 15, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [beb41f73d2](https://linux-hardware.org/?probe=beb41f73d2) | Oct 15, 2022 |
| Lenovo        | ThinkCentre M90 5536A76     | Desktop     | [d6f13cdb14](https://linux-hardware.org/?probe=d6f13cdb14) | Oct 15, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [b1de0617da](https://linux-hardware.org/?probe=b1de0617da) | Oct 15, 2022 |
| HP            | Pavilion g6                 | Notebook    | [2729d4b101](https://linux-hardware.org/?probe=2729d4b101) | Oct 14, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [2e1434c4ff](https://linux-hardware.org/?probe=2e1434c4ff) | Oct 14, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [2ba7e8c424](https://linux-hardware.org/?probe=2ba7e8c424) | Oct 14, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [6b78ca11b4](https://linux-hardware.org/?probe=6b78ca11b4) | Oct 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [128cccafa6](https://linux-hardware.org/?probe=128cccafa6) | Oct 14, 2022 |
| HP            | Pavilion g6                 | Notebook    | [4fbce46637](https://linux-hardware.org/?probe=4fbce46637) | Oct 14, 2022 |
| System76      | Galago Pro                  | Notebook    | [ec92c5a918](https://linux-hardware.org/?probe=ec92c5a918) | Oct 14, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [a14b57c22c](https://linux-hardware.org/?probe=a14b57c22c) | Oct 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [e2db064195](https://linux-hardware.org/?probe=e2db064195) | Oct 13, 2022 |
| Google        | Kefka                       | Notebook    | [4775b995dd](https://linux-hardware.org/?probe=4775b995dd) | Oct 13, 2022 |
| System76      | Lemur Pro                   | Notebook    | [ec569ddc8f](https://linux-hardware.org/?probe=ec569ddc8f) | Oct 13, 2022 |
| Dell          | Latitude 7420               | Convertible | [dade6a2b21](https://linux-hardware.org/?probe=dade6a2b21) | Oct 13, 2022 |
| MSI           | Katana GF76 11UD            | Notebook    | [3c11d61a58](https://linux-hardware.org/?probe=3c11d61a58) | Oct 13, 2022 |
| MSI           | Katana GF76 11UD            | Notebook    | [236e24530f](https://linux-hardware.org/?probe=236e24530f) | Oct 12, 2022 |
| Dell          | Precision M6700             | Notebook    | [4c867e9075](https://linux-hardware.org/?probe=4c867e9075) | Oct 12, 2022 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [86c8fabb2d](https://linux-hardware.org/?probe=86c8fabb2d) | Oct 12, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [273721cef2](https://linux-hardware.org/?probe=273721cef2) | Oct 12, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [512238de46](https://linux-hardware.org/?probe=512238de46) | Oct 12, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [c82722f056](https://linux-hardware.org/?probe=c82722f056) | Oct 12, 2022 |
| Razer         | Blade                       | Notebook    | [c7386df23f](https://linux-hardware.org/?probe=c7386df23f) | Oct 12, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [2d102e0f1e](https://linux-hardware.org/?probe=2d102e0f1e) | Oct 12, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [4b0116a8c6](https://linux-hardware.org/?probe=4b0116a8c6) | Oct 12, 2022 |
| HP            | Pavilion 15                 | Notebook    | [8b93ec27f4](https://linux-hardware.org/?probe=8b93ec27f4) | Oct 12, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [1feb5d7501](https://linux-hardware.org/?probe=1feb5d7501) | Oct 12, 2022 |
| Alienware     | 15 R3                       | Notebook    | [bfdbf12cbb](https://linux-hardware.org/?probe=bfdbf12cbb) | Oct 11, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [93ca81946a](https://linux-hardware.org/?probe=93ca81946a) | Oct 11, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [921c4a26d1](https://linux-hardware.org/?probe=921c4a26d1) | Oct 11, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [477851891a](https://linux-hardware.org/?probe=477851891a) | Oct 11, 2022 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [1b31cf42bb](https://linux-hardware.org/?probe=1b31cf42bb) | Oct 11, 2022 |
| MSI           | MS-7A34                     | Notebook    | [9850074c97](https://linux-hardware.org/?probe=9850074c97) | Oct 10, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [f4a46537c2](https://linux-hardware.org/?probe=f4a46537c2) | Oct 10, 2022 |
| Gigabyte      | P34V7                       | Notebook    | [c1423fce9e](https://linux-hardware.org/?probe=c1423fce9e) | Oct 10, 2022 |
| System76      | Galago Pro                  | Notebook    | [28e36afa26](https://linux-hardware.org/?probe=28e36afa26) | Oct 10, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [a6eb228e33](https://linux-hardware.org/?probe=a6eb228e33) | Oct 10, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [3462676a1d](https://linux-hardware.org/?probe=3462676a1d) | Oct 10, 2022 |
| Dell          | 0GM819                      | Desktop     | [e0266a8468](https://linux-hardware.org/?probe=e0266a8468) | Oct 09, 2022 |
| Dell          | Latitude 5501               | Notebook    | [9051fd0e00](https://linux-hardware.org/?probe=9051fd0e00) | Oct 09, 2022 |
| Dell          | Latitude 5501               | Notebook    | [3396ccdbab](https://linux-hardware.org/?probe=3396ccdbab) | Oct 09, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [7231761ea1](https://linux-hardware.org/?probe=7231761ea1) | Oct 09, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [e26fca4929](https://linux-hardware.org/?probe=e26fca4929) | Oct 09, 2022 |
| MSI           | GV62 8RD                    | Notebook    | [8902a355f4](https://linux-hardware.org/?probe=8902a355f4) | Oct 09, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [1f013f181d](https://linux-hardware.org/?probe=1f013f181d) | Oct 09, 2022 |
| Dell          | Inspiron 14 7425 2-in-1     | Convertible | [4f74ee653c](https://linux-hardware.org/?probe=4f74ee653c) | Oct 09, 2022 |
| Dell          | 0J3C2F A01                  | Desktop     | [d1001275c6](https://linux-hardware.org/?probe=d1001275c6) | Oct 09, 2022 |
| Sony          | VPCEB46FG                   | Notebook    | [71e2273974](https://linux-hardware.org/?probe=71e2273974) | Oct 08, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK 1       | Desktop     | [324f177fa7](https://linux-hardware.org/?probe=324f177fa7) | Oct 08, 2022 |
| HP            | ProBook 640 G3              | Notebook    | [03112f2830](https://linux-hardware.org/?probe=03112f2830) | Oct 08, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [d6742b3ec0](https://linux-hardware.org/?probe=d6742b3ec0) | Oct 08, 2022 |
| ASUSTek       | G752VS                      | Notebook    | [df98c91ed6](https://linux-hardware.org/?probe=df98c91ed6) | Oct 08, 2022 |
| Lenovo        | V155-15API 81V5             | Notebook    | [c08e4bed15](https://linux-hardware.org/?probe=c08e4bed15) | Oct 07, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [53ca822dcd](https://linux-hardware.org/?probe=53ca822dcd) | Oct 07, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [8ad48ccaec](https://linux-hardware.org/?probe=8ad48ccaec) | Oct 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [9525ea0de3](https://linux-hardware.org/?probe=9525ea0de3) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [ff847da23a](https://linux-hardware.org/?probe=ff847da23a) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [fceffec337](https://linux-hardware.org/?probe=fceffec337) | Oct 07, 2022 |
| Sony          | VPCEH3LFX                   | Notebook    | [fbb59e09fc](https://linux-hardware.org/?probe=fbb59e09fc) | Oct 07, 2022 |
| Alienware     | 17 R4                       | Notebook    | [cac06d6050](https://linux-hardware.org/?probe=cac06d6050) | Oct 07, 2022 |
| Positivo      | Mobile                      | Notebook    | [f26e597436](https://linux-hardware.org/?probe=f26e597436) | Oct 06, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [83a49e76b9](https://linux-hardware.org/?probe=83a49e76b9) | Oct 06, 2022 |
| MSI           | GP66 Leopard 10UG           | Notebook    | [c2082a042d](https://linux-hardware.org/?probe=c2082a042d) | Oct 06, 2022 |
| ASRock        | B450M/ac                    | Desktop     | [af66fef71a](https://linux-hardware.org/?probe=af66fef71a) | Oct 06, 2022 |
| HP            | 3398                        | Desktop     | [c70e10b68b](https://linux-hardware.org/?probe=c70e10b68b) | Oct 06, 2022 |
| Acer          | Aspire 5520                 | Notebook    | [05e6a5cb26](https://linux-hardware.org/?probe=05e6a5cb26) | Oct 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [512c095e83](https://linux-hardware.org/?probe=512c095e83) | Oct 06, 2022 |
| Lenovo        | IdeaPad Y560                | Notebook    | [15e2c8994f](https://linux-hardware.org/?probe=15e2c8994f) | Oct 06, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [d4a282a4b8](https://linux-hardware.org/?probe=d4a282a4b8) | Oct 06, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [9232451f1a](https://linux-hardware.org/?probe=9232451f1a) | Oct 06, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [5f5a6947ab](https://linux-hardware.org/?probe=5f5a6947ab) | Oct 06, 2022 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | Notebook    | [fa7e7d106e](https://linux-hardware.org/?probe=fa7e7d106e) | Oct 06, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [ed969ece24](https://linux-hardware.org/?probe=ed969ece24) | Oct 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [72163c289e](https://linux-hardware.org/?probe=72163c289e) | Oct 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [2fda8270f0](https://linux-hardware.org/?probe=2fda8270f0) | Oct 05, 2022 |
| HP            | 3398                        | Desktop     | [7dd62dded1](https://linux-hardware.org/?probe=7dd62dded1) | Oct 05, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [c0f42e7ac4](https://linux-hardware.org/?probe=c0f42e7ac4) | Oct 05, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [8e7d366723](https://linux-hardware.org/?probe=8e7d366723) | Oct 05, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [48901aff3f](https://linux-hardware.org/?probe=48901aff3f) | Oct 04, 2022 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [736ded7422](https://linux-hardware.org/?probe=736ded7422) | Oct 04, 2022 |
| Intel         | DQ35JO AAD82085-801         | Desktop     | [4056c37c50](https://linux-hardware.org/?probe=4056c37c50) | Oct 04, 2022 |
| Dell          | Latitude E7240              | Notebook    | [0a41ea4b4c](https://linux-hardware.org/?probe=0a41ea4b4c) | Oct 04, 2022 |
| HP            | EliteBook 1040 G4           | Notebook    | [8a19b834c8](https://linux-hardware.org/?probe=8a19b834c8) | Oct 04, 2022 |
| Microsoft     | Surface Book                | Tablet      | [85c4f341f3](https://linux-hardware.org/?probe=85c4f341f3) | Oct 04, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [b8237b1bd7](https://linux-hardware.org/?probe=b8237b1bd7) | Oct 04, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [eb1ee8ad1f](https://linux-hardware.org/?probe=eb1ee8ad1f) | Oct 04, 2022 |
| System76      | Lemur Pro                   | Notebook    | [8842585a92](https://linux-hardware.org/?probe=8842585a92) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | Notebook    | [50d641ecf9](https://linux-hardware.org/?probe=50d641ecf9) | Oct 03, 2022 |
| Dell          | Latitude E6420              | Notebook    | [652b18aabe](https://linux-hardware.org/?probe=652b18aabe) | Oct 03, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [1e0190a274](https://linux-hardware.org/?probe=1e0190a274) | Oct 03, 2022 |
| Google        | Banon                       | Notebook    | [269a819905](https://linux-hardware.org/?probe=269a819905) | Oct 03, 2022 |
| Fujitsu       | LIFEBOOK T5010              | Notebook    | [2637a452d0](https://linux-hardware.org/?probe=2637a452d0) | Oct 03, 2022 |
| Samsung       | 550XDA                      | Notebook    | [418d32112e](https://linux-hardware.org/?probe=418d32112e) | Oct 03, 2022 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [b3a9474c83](https://linux-hardware.org/?probe=b3a9474c83) | Oct 03, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [7fbccd3f20](https://linux-hardware.org/?probe=7fbccd3f20) | Oct 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0382d1ec36](https://linux-hardware.org/?probe=0382d1ec36) | Oct 02, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | Notebook    | [8d405f5135](https://linux-hardware.org/?probe=8d405f5135) | Oct 02, 2022 |
| Dell          | XPS L421X                   | Notebook    | [aedcc42b0a](https://linux-hardware.org/?probe=aedcc42b0a) | Oct 02, 2022 |
| Apple         | MacBookPro5,2               | Notebook    | [b0a6dc4162](https://linux-hardware.org/?probe=b0a6dc4162) | Oct 02, 2022 |
| Acer          | Aspire ES1-522              | Notebook    | [b5c516677a](https://linux-hardware.org/?probe=b5c516677a) | Oct 02, 2022 |
| Acer          | Aspire ES1-522              | Notebook    | [86e57e249a](https://linux-hardware.org/?probe=86e57e249a) | Oct 02, 2022 |
| Alienware     | 15 R3                       | Notebook    | [28e4e84fb1](https://linux-hardware.org/?probe=28e4e84fb1) | Oct 02, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [54c3aa5cc5](https://linux-hardware.org/?probe=54c3aa5cc5) | Oct 02, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | Notebook    | [8731307ce6](https://linux-hardware.org/?probe=8731307ce6) | Oct 02, 2022 |
| ASUSTek       | GL502VM                     | Notebook    | [1d1616405d](https://linux-hardware.org/?probe=1d1616405d) | Oct 02, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [ae706e478d](https://linux-hardware.org/?probe=ae706e478d) | Oct 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [32dba0444e](https://linux-hardware.org/?probe=32dba0444e) | Oct 02, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [49595ef8f4](https://linux-hardware.org/?probe=49595ef8f4) | Oct 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [46d6046fce](https://linux-hardware.org/?probe=46d6046fce) | Oct 02, 2022 |
| Micro Elec... | Element                     | Notebook    | [9cee0f76c1](https://linux-hardware.org/?probe=9cee0f76c1) | Oct 02, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [42113dd7e3](https://linux-hardware.org/?probe=42113dd7e3) | Oct 01, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FE00... | Convertible | [4eaeb1d5ad](https://linux-hardware.org/?probe=4eaeb1d5ad) | Oct 01, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [4168f641b5](https://linux-hardware.org/?probe=4168f641b5) | Oct 01, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [a4252ba03a](https://linux-hardware.org/?probe=a4252ba03a) | Oct 01, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [b2d146f923](https://linux-hardware.org/?probe=b2d146f923) | Oct 01, 2022 |
| HP            | Pavilion                    | Notebook    | [124e8b760a](https://linux-hardware.org/?probe=124e8b760a) | Oct 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3595e90895](https://linux-hardware.org/?probe=3595e90895) | Oct 01, 2022 |
| System76      | Darter Pro                  | Notebook    | [2829e72506](https://linux-hardware.org/?probe=2829e72506) | Oct 01, 2022 |
| System76      | Darter Pro                  | Notebook    | [c142cf370a](https://linux-hardware.org/?probe=c142cf370a) | Oct 01, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [692b59019a](https://linux-hardware.org/?probe=692b59019a) | Oct 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [29648b493a](https://linux-hardware.org/?probe=29648b493a) | Oct 01, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [6f6704ea90](https://linux-hardware.org/?probe=6f6704ea90) | Oct 01, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [5e9a9b60e6](https://linux-hardware.org/?probe=5e9a9b60e6) | Oct 01, 2022 |
| Lenovo        | ThinkPad P1 Gen 5 21DCCT... | Notebook    | [bde2b36c88](https://linux-hardware.org/?probe=bde2b36c88) | Oct 01, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [2e9261e2a7](https://linux-hardware.org/?probe=2e9261e2a7) | Sep 30, 2022 |
| Lenovo        | ThinkPad T480 20L5001FUS    | Notebook    | [a7e0da7aa4](https://linux-hardware.org/?probe=a7e0da7aa4) | Sep 30, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [8856e3bf98](https://linux-hardware.org/?probe=8856e3bf98) | Sep 30, 2022 |
| Dell          | Latitude 5400               | Notebook    | [66a5bc26f0](https://linux-hardware.org/?probe=66a5bc26f0) | Sep 30, 2022 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [3f01bbaa12](https://linux-hardware.org/?probe=3f01bbaa12) | Sep 30, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [3ccd7ea5d6](https://linux-hardware.org/?probe=3ccd7ea5d6) | Sep 30, 2022 |
| Fujitsu       | LIFEBOOK A6210              | Notebook    | [81653ba834](https://linux-hardware.org/?probe=81653ba834) | Sep 30, 2022 |
| HUAWEI        | VLT-WX0                     | Notebook    | [1669dae0a6](https://linux-hardware.org/?probe=1669dae0a6) | Sep 30, 2022 |
| Fujitsu       | LIFEBOOK A6210              | Notebook    | [d31b97630d](https://linux-hardware.org/?probe=d31b97630d) | Sep 29, 2022 |
| Dell          | Latitude 5400               | Notebook    | [4536a4b473](https://linux-hardware.org/?probe=4536a4b473) | Sep 29, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [7a2f334861](https://linux-hardware.org/?probe=7a2f334861) | Sep 29, 2022 |
| Dell          | Latitude 5400               | Notebook    | [972e4ab3fa](https://linux-hardware.org/?probe=972e4ab3fa) | Sep 29, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [d06b40ddf1](https://linux-hardware.org/?probe=d06b40ddf1) | Sep 29, 2022 |
| Dell          | Inspiron 7405 2n1           | Convertible | [8196b8f736](https://linux-hardware.org/?probe=8196b8f736) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | Notebook    | [f758c22d98](https://linux-hardware.org/?probe=f758c22d98) | Sep 28, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [d23d86be40](https://linux-hardware.org/?probe=d23d86be40) | Sep 28, 2022 |
| Lenovo        | ThinkPad X220 4286PJ2       | Notebook    | [2d0c850c3a](https://linux-hardware.org/?probe=2d0c850c3a) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | Notebook    | [b08fc47990](https://linux-hardware.org/?probe=b08fc47990) | Sep 28, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [46cba6613f](https://linux-hardware.org/?probe=46cba6613f) | Sep 28, 2022 |
| Dell          | 0NDYHG A01                  | Desktop     | [7a5df20f28](https://linux-hardware.org/?probe=7a5df20f28) | Sep 28, 2022 |
| Dell          | Latitude E7450              | Notebook    | [daeb4afb69](https://linux-hardware.org/?probe=daeb4afb69) | Sep 28, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [5ce350f38b](https://linux-hardware.org/?probe=5ce350f38b) | Sep 28, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [f129c4da4a](https://linux-hardware.org/?probe=f129c4da4a) | Sep 28, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [a3c4032d28](https://linux-hardware.org/?probe=a3c4032d28) | Sep 27, 2022 |
| HP            | 83E9                        | Desktop     | [c24faa3c5b](https://linux-hardware.org/?probe=c24faa3c5b) | Sep 27, 2022 |
| Gigabyte      | P34V7                       | Notebook    | [27b9651432](https://linux-hardware.org/?probe=27b9651432) | Sep 27, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [99b6a53bd2](https://linux-hardware.org/?probe=99b6a53bd2) | Sep 27, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2c52de3e56](https://linux-hardware.org/?probe=2c52de3e56) | Sep 27, 2022 |
| ASUSTek       | GL702VSK                    | Notebook    | [3b69ddb263](https://linux-hardware.org/?probe=3b69ddb263) | Sep 27, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [8579eba471](https://linux-hardware.org/?probe=8579eba471) | Sep 26, 2022 |
| Gigabyte      | Z170MX-Gaming 5             | Desktop     | [fbc760a09c](https://linux-hardware.org/?probe=fbc760a09c) | Sep 26, 2022 |
| ASUSTek       | GL702VSK                    | Notebook    | [e91056ceab](https://linux-hardware.org/?probe=e91056ceab) | Sep 26, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [eff6424aa4](https://linux-hardware.org/?probe=eff6424aa4) | Sep 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9fff405744](https://linux-hardware.org/?probe=9fff405744) | Sep 26, 2022 |
| System76      | Galago Pro                  | Notebook    | [6b2de473b7](https://linux-hardware.org/?probe=6b2de473b7) | Sep 26, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [1b4db0c30c](https://linux-hardware.org/?probe=1b4db0c30c) | Sep 26, 2022 |
| ASUSTek       | K52N                        | Notebook    | [8d7b00011f](https://linux-hardware.org/?probe=8d7b00011f) | Sep 26, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [34035b63b6](https://linux-hardware.org/?probe=34035b63b6) | Sep 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [acbd9cc9af](https://linux-hardware.org/?probe=acbd9cc9af) | Sep 25, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [50792d0ac6](https://linux-hardware.org/?probe=50792d0ac6) | Sep 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [27d8d35004](https://linux-hardware.org/?probe=27d8d35004) | Sep 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [e9de38d8eb](https://linux-hardware.org/?probe=e9de38d8eb) | Sep 25, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [05dc7a54c7](https://linux-hardware.org/?probe=05dc7a54c7) | Sep 25, 2022 |
| ASRock        | H97M Anniversary            | Desktop     | [289532b8bb](https://linux-hardware.org/?probe=289532b8bb) | Sep 24, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [5c39bdf4ab](https://linux-hardware.org/?probe=5c39bdf4ab) | Sep 24, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [029c059963](https://linux-hardware.org/?probe=029c059963) | Sep 24, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d2327ba5d4](https://linux-hardware.org/?probe=d2327ba5d4) | Sep 24, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [b3f2c4694c](https://linux-hardware.org/?probe=b3f2c4694c) | Sep 24, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [61dd74082f](https://linux-hardware.org/?probe=61dd74082f) | Sep 24, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d07b0cb7a0](https://linux-hardware.org/?probe=d07b0cb7a0) | Sep 24, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [2bc6e102ef](https://linux-hardware.org/?probe=2bc6e102ef) | Sep 24, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [fac56b0962](https://linux-hardware.org/?probe=fac56b0962) | Sep 24, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [214a55ad3e](https://linux-hardware.org/?probe=214a55ad3e) | Sep 24, 2022 |
| MSI           | Z97-G55 SLI                 | Desktop     | [dc60d66502](https://linux-hardware.org/?probe=dc60d66502) | Sep 24, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [86b6d46191](https://linux-hardware.org/?probe=86b6d46191) | Sep 24, 2022 |
| System76      | Thelio Mira                 | Desktop     | [2e9601d2a2](https://linux-hardware.org/?probe=2e9601d2a2) | Sep 24, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [9e8207dfb7](https://linux-hardware.org/?probe=9e8207dfb7) | Sep 23, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [59c4a7e761](https://linux-hardware.org/?probe=59c4a7e761) | Sep 23, 2022 |
| MSI           | Z97-G55 SLI                 | Desktop     | [27b47d5592](https://linux-hardware.org/?probe=27b47d5592) | Sep 23, 2022 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [609225524a](https://linux-hardware.org/?probe=609225524a) | Sep 23, 2022 |
| Dell          | 0HHV7N A00                  | Desktop     | [cda6d76f04](https://linux-hardware.org/?probe=cda6d76f04) | Sep 22, 2022 |
| Dell          | Latitude 7275               | Tablet      | [3ce0ab7672](https://linux-hardware.org/?probe=3ce0ab7672) | Sep 22, 2022 |
| System76      | Darter Pro                  | Notebook    | [012968a4a3](https://linux-hardware.org/?probe=012968a4a3) | Sep 22, 2022 |
| ASRock        | 4X4-V1000                   | Desktop     | [e73062fe01](https://linux-hardware.org/?probe=e73062fe01) | Sep 22, 2022 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [074a9f8433](https://linux-hardware.org/?probe=074a9f8433) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [7910fab01e](https://linux-hardware.org/?probe=7910fab01e) | Sep 22, 2022 |
| System76      | Darter Pro                  | Notebook    | [8d3bdb7585](https://linux-hardware.org/?probe=8d3bdb7585) | Sep 22, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [032bbec1e3](https://linux-hardware.org/?probe=032bbec1e3) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [3c93753c6c](https://linux-hardware.org/?probe=3c93753c6c) | Sep 22, 2022 |
| Dell          | Latitude 3490               | Notebook    | [de749eeeb8](https://linux-hardware.org/?probe=de749eeeb8) | Sep 21, 2022 |
| Dell          | Precision 3561              | Notebook    | [b924a86b79](https://linux-hardware.org/?probe=b924a86b79) | Sep 21, 2022 |
| Acer          | Nitro AN715-51              | Notebook    | [36fb85e6cb](https://linux-hardware.org/?probe=36fb85e6cb) | Sep 21, 2022 |
| HP            | 829A                        | Mini pc     | [9fbbfa249d](https://linux-hardware.org/?probe=9fbbfa249d) | Sep 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [dc49b2baf4](https://linux-hardware.org/?probe=dc49b2baf4) | Sep 21, 2022 |
| Dell          | Latitude 7490               | Notebook    | [b8c3a5519a](https://linux-hardware.org/?probe=b8c3a5519a) | Sep 21, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [facc4c1755](https://linux-hardware.org/?probe=facc4c1755) | Sep 21, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [07dd388834](https://linux-hardware.org/?probe=07dd388834) | Sep 21, 2022 |
| Acer          | Aspire A515-54              | Notebook    | [8116705a81](https://linux-hardware.org/?probe=8116705a81) | Sep 21, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [7fa417e9a6](https://linux-hardware.org/?probe=7fa417e9a6) | Sep 21, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [7fc6799a48](https://linux-hardware.org/?probe=7fc6799a48) | Sep 21, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [2c7466119d](https://linux-hardware.org/?probe=2c7466119d) | Sep 21, 2022 |
| Dell          | Inspiron 5577               | Notebook    | [c6f4124e49](https://linux-hardware.org/?probe=c6f4124e49) | Sep 21, 2022 |
| HP            | 1589                        | Desktop     | [da376a40a1](https://linux-hardware.org/?probe=da376a40a1) | Sep 20, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [8e78f3c776](https://linux-hardware.org/?probe=8e78f3c776) | Sep 20, 2022 |
| Gigabyte      | EX58-UD4P                   | Desktop     | [394aad4be9](https://linux-hardware.org/?probe=394aad4be9) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [1e7ca74f13](https://linux-hardware.org/?probe=1e7ca74f13) | Sep 20, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [b1df3aa03f](https://linux-hardware.org/?probe=b1df3aa03f) | Sep 20, 2022 |
| Itronix       | GD8200                      | Notebook    | [d9f515b935](https://linux-hardware.org/?probe=d9f515b935) | Sep 20, 2022 |
| Lenovo        | Legion 5-15ACH6H 82JU       | Notebook    | [1f48647e32](https://linux-hardware.org/?probe=1f48647e32) | Sep 20, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [61a4ab7c20](https://linux-hardware.org/?probe=61a4ab7c20) | Sep 20, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [6d43012457](https://linux-hardware.org/?probe=6d43012457) | Sep 20, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [df0348739e](https://linux-hardware.org/?probe=df0348739e) | Sep 20, 2022 |
| HONOR         | NMH-WCX9                    | Notebook    | [dd2687098a](https://linux-hardware.org/?probe=dd2687098a) | Sep 19, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [a0d6f208fb](https://linux-hardware.org/?probe=a0d6f208fb) | Sep 19, 2022 |
| ASUSTek       | GL502VSK                    | Notebook    | [a6dc9b627f](https://linux-hardware.org/?probe=a6dc9b627f) | Sep 19, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [136eca7e32](https://linux-hardware.org/?probe=136eca7e32) | Sep 19, 2022 |
| Sony          | VAIO                        | All in one  | [0e3271f88f](https://linux-hardware.org/?probe=0e3271f88f) | Sep 19, 2022 |
| HONOR         | NMH-WCX9                    | Notebook    | [060f3bd895](https://linux-hardware.org/?probe=060f3bd895) | Sep 19, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [ecc3b7e71d](https://linux-hardware.org/?probe=ecc3b7e71d) | Sep 19, 2022 |
| Dell          | Latitude 9420               | Convertible | [1c6c42624d](https://linux-hardware.org/?probe=1c6c42624d) | Sep 19, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [4fcfd69ec1](https://linux-hardware.org/?probe=4fcfd69ec1) | Sep 19, 2022 |
| HP            | OMEN by Laptop 15z-en100    | Notebook    | [47b0aed151](https://linux-hardware.org/?probe=47b0aed151) | Sep 19, 2022 |
| Framework     | Laptop                      | Notebook    | [8dbbe54af9](https://linux-hardware.org/?probe=8dbbe54af9) | Sep 18, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [83b0a59729](https://linux-hardware.org/?probe=83b0a59729) | Sep 18, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [37b4da9922](https://linux-hardware.org/?probe=37b4da9922) | Sep 18, 2022 |
| Dell          | Inspiron 7791 2n1           | Convertible | [31e3939680](https://linux-hardware.org/?probe=31e3939680) | Sep 18, 2022 |
| Dell          | Inspiron 7791 2n1           | Convertible | [f207769c14](https://linux-hardware.org/?probe=f207769c14) | Sep 18, 2022 |
| Gateway       | NV55C                       | Notebook    | [e00587af22](https://linux-hardware.org/?probe=e00587af22) | Sep 18, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [fa4082533e](https://linux-hardware.org/?probe=fa4082533e) | Sep 18, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [a418c3e997](https://linux-hardware.org/?probe=a418c3e997) | Sep 18, 2022 |
| Dell          | Latitude E7470              | Notebook    | [ceed7544ab](https://linux-hardware.org/?probe=ceed7544ab) | Sep 18, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [f40cc0db8a](https://linux-hardware.org/?probe=f40cc0db8a) | Sep 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1ad10d3c4b](https://linux-hardware.org/?probe=1ad10d3c4b) | Sep 18, 2022 |
| Dell          | Precision 5530              | Notebook    | [8fc00af945](https://linux-hardware.org/?probe=8fc00af945) | Sep 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [50da0a8acf](https://linux-hardware.org/?probe=50da0a8acf) | Sep 18, 2022 |
| MSI           | Sword 15 A11UD              | Notebook    | [e749154c3d](https://linux-hardware.org/?probe=e749154c3d) | Sep 18, 2022 |
| Dell          | Latitude E6330              | Notebook    | [5a1085f939](https://linux-hardware.org/?probe=5a1085f939) | Sep 18, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [bd7ddbf9f7](https://linux-hardware.org/?probe=bd7ddbf9f7) | Sep 18, 2022 |
| Alienware     | 0CPDXD A00                  | Desktop     | [f65bdb053d](https://linux-hardware.org/?probe=f65bdb053d) | Sep 18, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [a403b2a79d](https://linux-hardware.org/?probe=a403b2a79d) | Sep 17, 2022 |
| MSI           | Prestige 15 A12UC           | Notebook    | [48437ccf94](https://linux-hardware.org/?probe=48437ccf94) | Sep 17, 2022 |
| OriginPC      | NT17-PRO                    | Notebook    | [962138caa9](https://linux-hardware.org/?probe=962138caa9) | Sep 17, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [4c919169ea](https://linux-hardware.org/?probe=4c919169ea) | Sep 17, 2022 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [0bec316a0b](https://linux-hardware.org/?probe=0bec316a0b) | Sep 17, 2022 |
| System76      | Darter Pro                  | Notebook    | [5d1e0ddc1a](https://linux-hardware.org/?probe=5d1e0ddc1a) | Sep 16, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [7099830d0a](https://linux-hardware.org/?probe=7099830d0a) | Sep 16, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [d66cbae64b](https://linux-hardware.org/?probe=d66cbae64b) | Sep 16, 2022 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [545552c43e](https://linux-hardware.org/?probe=545552c43e) | Sep 16, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [4dd83a1b80](https://linux-hardware.org/?probe=4dd83a1b80) | Sep 16, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [b0e6601fbf](https://linux-hardware.org/?probe=b0e6601fbf) | Sep 16, 2022 |
| ASUSTek       | N550LF                      | Notebook    | [73f2edfe65](https://linux-hardware.org/?probe=73f2edfe65) | Sep 16, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [9cc24963d4](https://linux-hardware.org/?probe=9cc24963d4) | Sep 16, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [6d28bb81ce](https://linux-hardware.org/?probe=6d28bb81ce) | Sep 16, 2022 |
| Toshiba       | Satellite C55t-C            | Notebook    | [9c45d5a042](https://linux-hardware.org/?probe=9c45d5a042) | Sep 16, 2022 |
| NZXT          | N7 B550                     | Desktop     | [7deb3849db](https://linux-hardware.org/?probe=7deb3849db) | Sep 16, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [2c90f58ae4](https://linux-hardware.org/?probe=2c90f58ae4) | Sep 16, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [6d94f648e4](https://linux-hardware.org/?probe=6d94f648e4) | Sep 16, 2022 |
| GPD           | MicroPC                     | Notebook    | [dadac68a23](https://linux-hardware.org/?probe=dadac68a23) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [3196144640](https://linux-hardware.org/?probe=3196144640) | Sep 15, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [d39fd89ab8](https://linux-hardware.org/?probe=d39fd89ab8) | Sep 15, 2022 |
| MACHINIST     | X99-RS9 V3.0                | Desktop     | [3f9fc3fc62](https://linux-hardware.org/?probe=3f9fc3fc62) | Sep 15, 2022 |
| Dell          | Precision 3561              | Notebook    | [b61765a085](https://linux-hardware.org/?probe=b61765a085) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6de8f25119](https://linux-hardware.org/?probe=6de8f25119) | Sep 15, 2022 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [2d33f80fbd](https://linux-hardware.org/?probe=2d33f80fbd) | Sep 15, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5c00a1875c](https://linux-hardware.org/?probe=5c00a1875c) | Sep 14, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [9c97b9e2c1](https://linux-hardware.org/?probe=9c97b9e2c1) | Sep 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ed284e43fb](https://linux-hardware.org/?probe=ed284e43fb) | Sep 14, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [750bf03293](https://linux-hardware.org/?probe=750bf03293) | Sep 14, 2022 |
| MSI           | Katana GF66 12UE            | Notebook    | [955b9787eb](https://linux-hardware.org/?probe=955b9787eb) | Sep 14, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [64b85307ec](https://linux-hardware.org/?probe=64b85307ec) | Sep 14, 2022 |
| ASUSTek       | X405UA                      | Notebook    | [3b098addea](https://linux-hardware.org/?probe=3b098addea) | Sep 14, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [aa0553a310](https://linux-hardware.org/?probe=aa0553a310) | Sep 13, 2022 |
| Lenovo        | ThinkBook 13x ITG 20WJ      | Notebook    | [2e6e759434](https://linux-hardware.org/?probe=2e6e759434) | Sep 13, 2022 |
| MACHINIST     | X99-RS9 V3.0                | Desktop     | [64795f6f69](https://linux-hardware.org/?probe=64795f6f69) | Sep 13, 2022 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [a27c60fbde](https://linux-hardware.org/?probe=a27c60fbde) | Sep 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [81b9b18da4](https://linux-hardware.org/?probe=81b9b18da4) | Sep 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [cacc85ca2e](https://linux-hardware.org/?probe=cacc85ca2e) | Sep 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0c6d5b57dd](https://linux-hardware.org/?probe=0c6d5b57dd) | Sep 13, 2022 |
| ASRock        | H97M Anniversary            | Desktop     | [1b5e2c2e0a](https://linux-hardware.org/?probe=1b5e2c2e0a) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [b502b7938d](https://linux-hardware.org/?probe=b502b7938d) | Sep 13, 2022 |
| ASRock        | H97M Anniversary            | Desktop     | [649c5fb453](https://linux-hardware.org/?probe=649c5fb453) | Sep 13, 2022 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [89fb49d843](https://linux-hardware.org/?probe=89fb49d843) | Sep 13, 2022 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [a385e1220b](https://linux-hardware.org/?probe=a385e1220b) | Sep 13, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [2548dada71](https://linux-hardware.org/?probe=2548dada71) | Sep 13, 2022 |
| Dell          | Studio 1555                 | Notebook    | [0d0f3de3b4](https://linux-hardware.org/?probe=0d0f3de3b4) | Sep 12, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [8bdaf4361b](https://linux-hardware.org/?probe=8bdaf4361b) | Sep 12, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [0c3d0800eb](https://linux-hardware.org/?probe=0c3d0800eb) | Sep 12, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [4fbc7a765f](https://linux-hardware.org/?probe=4fbc7a765f) | Sep 12, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [e1d128b56a](https://linux-hardware.org/?probe=e1d128b56a) | Sep 12, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Notebook    | [1889334e1f](https://linux-hardware.org/?probe=1889334e1f) | Sep 12, 2022 |
| ECS           | Nettle3                     | Desktop     | [23f7f8708c](https://linux-hardware.org/?probe=23f7f8708c) | Sep 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [f9add8f93d](https://linux-hardware.org/?probe=f9add8f93d) | Sep 11, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [931f4d2ca7](https://linux-hardware.org/?probe=931f4d2ca7) | Sep 11, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [2f6745bad5](https://linux-hardware.org/?probe=2f6745bad5) | Sep 11, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [34964d8e2d](https://linux-hardware.org/?probe=34964d8e2d) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ce4fc6576c](https://linux-hardware.org/?probe=ce4fc6576c) | Sep 11, 2022 |
| Lenovo        | ThinkPad T430 2350A26       | Notebook    | [7374ee44fa](https://linux-hardware.org/?probe=7374ee44fa) | Sep 10, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [4f1849370d](https://linux-hardware.org/?probe=4f1849370d) | Sep 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f19e04efc1](https://linux-hardware.org/?probe=f19e04efc1) | Sep 10, 2022 |
| System76      | Oryx Pro                    | Notebook    | [d84de42ab6](https://linux-hardware.org/?probe=d84de42ab6) | Sep 10, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [c0adc468b3](https://linux-hardware.org/?probe=c0adc468b3) | Sep 10, 2022 |
| Dell          | Inspiron 16 5625            | Notebook    | [5ae1f0d923](https://linux-hardware.org/?probe=5ae1f0d923) | Sep 10, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [6c1c4c8712](https://linux-hardware.org/?probe=6c1c4c8712) | Sep 10, 2022 |
| Dell          | 0P4T42 A01                  | All in one  | [21db941a5b](https://linux-hardware.org/?probe=21db941a5b) | Sep 10, 2022 |
| HP            | Dev One Notebook PC         | Notebook    | [bb72f0c2f4](https://linux-hardware.org/?probe=bb72f0c2f4) | Sep 10, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [2e9e331465](https://linux-hardware.org/?probe=2e9e331465) | Sep 10, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [29da7835e4](https://linux-hardware.org/?probe=29da7835e4) | Sep 10, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [5811e17863](https://linux-hardware.org/?probe=5811e17863) | Sep 09, 2022 |
| ASUSTek       | M4N72-E                     | Desktop     | [83be030771](https://linux-hardware.org/?probe=83be030771) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [4d3543d03f](https://linux-hardware.org/?probe=4d3543d03f) | Sep 09, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [b3aa7bd9ca](https://linux-hardware.org/?probe=b3aa7bd9ca) | Sep 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [87f754ac29](https://linux-hardware.org/?probe=87f754ac29) | Sep 09, 2022 |
| System76      | Galago Pro                  | Notebook    | [8d52d900f2](https://linux-hardware.org/?probe=8d52d900f2) | Sep 09, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [1be1b9b040](https://linux-hardware.org/?probe=1be1b9b040) | Sep 09, 2022 |
| HP            | ZBook Studio x360 G5        | Convertible | [5fe757d559](https://linux-hardware.org/?probe=5fe757d559) | Sep 09, 2022 |
| Intel         | X99                         | Desktop     | [9ebaa38244](https://linux-hardware.org/?probe=9ebaa38244) | Sep 08, 2022 |
| LattePanda    | 3 Delta CDJQ-BS-7-S70JR1... | Desktop     | [dbfdcae895](https://linux-hardware.org/?probe=dbfdcae895) | Sep 08, 2022 |
| LattePanda    | 3 Delta CDJQ-BS-7-S70JR1... | Desktop     | [4167167e38](https://linux-hardware.org/?probe=4167167e38) | Sep 08, 2022 |
| Dell          | 0TTDMJ A00                  | Desktop     | [66aa958693](https://linux-hardware.org/?probe=66aa958693) | Sep 08, 2022 |
| Dell          | Inspiron 5457               | Notebook    | [e44e9d3a85](https://linux-hardware.org/?probe=e44e9d3a85) | Sep 08, 2022 |
| AZW           | SEi                         | Notebook    | [d3531738fa](https://linux-hardware.org/?probe=d3531738fa) | Sep 08, 2022 |
| Lenovo        | ThinkPad T460 20FN003LGE    | Notebook    | [6108c677a2](https://linux-hardware.org/?probe=6108c677a2) | Sep 08, 2022 |
| Lenovo        | ThinkPad T460 20FN003LGE    | Notebook    | [0f8da1f0c8](https://linux-hardware.org/?probe=0f8da1f0c8) | Sep 08, 2022 |
| Dell          | Latitude 5420               | Notebook    | [511ef8a105](https://linux-hardware.org/?probe=511ef8a105) | Sep 08, 2022 |
| Dell          | Latitude 5420               | Notebook    | [48db2c3954](https://linux-hardware.org/?probe=48db2c3954) | Sep 08, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [bb2d82813c](https://linux-hardware.org/?probe=bb2d82813c) | Sep 08, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [e757b79169](https://linux-hardware.org/?probe=e757b79169) | Sep 08, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [09e8283762](https://linux-hardware.org/?probe=09e8283762) | Sep 08, 2022 |
| HP            | 245 G6                      | Notebook    | [054d226709](https://linux-hardware.org/?probe=054d226709) | Sep 07, 2022 |
| ASRock        | B450M/ac                    | Desktop     | [efb78c5d25](https://linux-hardware.org/?probe=efb78c5d25) | Sep 07, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [e73c83b5c7](https://linux-hardware.org/?probe=e73c83b5c7) | Sep 07, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [132a8e025a](https://linux-hardware.org/?probe=132a8e025a) | Sep 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [af2641c077](https://linux-hardware.org/?probe=af2641c077) | Sep 07, 2022 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [483a414289](https://linux-hardware.org/?probe=483a414289) | Sep 07, 2022 |
| Acer          | Aspire S3                   | Notebook    | [cb62300974](https://linux-hardware.org/?probe=cb62300974) | Sep 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0efcfb2037](https://linux-hardware.org/?probe=0efcfb2037) | Sep 07, 2022 |
| Lenovo        | ThinkPad T470s 20HGA039U... | Notebook    | [43c002ad40](https://linux-hardware.org/?probe=43c002ad40) | Sep 07, 2022 |
| Acer          | 1.0                         | Desktop     | [b81c44ff15](https://linux-hardware.org/?probe=b81c44ff15) | Sep 06, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [47d065ed5c](https://linux-hardware.org/?probe=47d065ed5c) | Sep 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [11b9de78b5](https://linux-hardware.org/?probe=11b9de78b5) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480s 20L8SC160... | Notebook    | [b860019cf4](https://linux-hardware.org/?probe=b860019cf4) | Sep 06, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [40d6a47565](https://linux-hardware.org/?probe=40d6a47565) | Sep 05, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [c17c4d475f](https://linux-hardware.org/?probe=c17c4d475f) | Sep 05, 2022 |
| Clevo         | P65_P67SE                   | Notebook    | [9a38027b73](https://linux-hardware.org/?probe=9a38027b73) | Sep 05, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [cb787086fa](https://linux-hardware.org/?probe=cb787086fa) | Sep 05, 2022 |
| HP            | EliteBook x360 1030 G3      | Convertible | [f6e3690dd8](https://linux-hardware.org/?probe=f6e3690dd8) | Sep 04, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [61e1164988](https://linux-hardware.org/?probe=61e1164988) | Sep 04, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [ea5f9662d7](https://linux-hardware.org/?probe=ea5f9662d7) | Sep 04, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [8f5998a9e4](https://linux-hardware.org/?probe=8f5998a9e4) | Sep 04, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [8b964572d7](https://linux-hardware.org/?probe=8b964572d7) | Sep 04, 2022 |
| Alienware     | 0NWN7M A00                  | Desktop     | [e254b049c3](https://linux-hardware.org/?probe=e254b049c3) | Sep 04, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [c40b757ca3](https://linux-hardware.org/?probe=c40b757ca3) | Sep 04, 2022 |
| MSI           | GP72 7RDX                   | Notebook    | [5d4efc6589](https://linux-hardware.org/?probe=5d4efc6589) | Sep 04, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [70de682c06](https://linux-hardware.org/?probe=70de682c06) | Sep 03, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30D0... | Notebook    | [b75636bf8b](https://linux-hardware.org/?probe=b75636bf8b) | Sep 03, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [bd0c518002](https://linux-hardware.org/?probe=bd0c518002) | Sep 03, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [81eb6e9f4e](https://linux-hardware.org/?probe=81eb6e9f4e) | Sep 03, 2022 |
| Dell          | Inspiron 13-7378            | Notebook    | [0ab8b4e169](https://linux-hardware.org/?probe=0ab8b4e169) | Sep 03, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [39e1d43301](https://linux-hardware.org/?probe=39e1d43301) | Sep 03, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [db5a53a31c](https://linux-hardware.org/?probe=db5a53a31c) | Sep 03, 2022 |
| ASUSTek       | M5A97                       | Desktop     | [de7dc826b0](https://linux-hardware.org/?probe=de7dc826b0) | Sep 03, 2022 |
| Intel         | DX58SO AAE29331-702         | Desktop     | [24c48ddc3e](https://linux-hardware.org/?probe=24c48ddc3e) | Sep 03, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [cfb4e75518](https://linux-hardware.org/?probe=cfb4e75518) | Sep 03, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [7b914b0347](https://linux-hardware.org/?probe=7b914b0347) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [5472c45d04](https://linux-hardware.org/?probe=5472c45d04) | Sep 03, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [6e45ea1408](https://linux-hardware.org/?probe=6e45ea1408) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6d1fcccbb8](https://linux-hardware.org/?probe=6d1fcccbb8) | Sep 03, 2022 |
| Lenovo        | IdeaPad Flex-15IWL 81SR     | Convertible | [6723781de1](https://linux-hardware.org/?probe=6723781de1) | Sep 03, 2022 |
| Dell          | 0FGCC7 A01                  | Server      | [4689cac5c7](https://linux-hardware.org/?probe=4689cac5c7) | Sep 03, 2022 |
| HP            | 1497                        | Desktop     | [a8566c45a9](https://linux-hardware.org/?probe=a8566c45a9) | Sep 03, 2022 |
| MSI           | MEG Z390 ACE                | Desktop     | [1f702cfc06](https://linux-hardware.org/?probe=1f702cfc06) | Sep 03, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [39cb364d6f](https://linux-hardware.org/?probe=39cb364d6f) | Sep 03, 2022 |
| Dell          | Latitude E5570              | Notebook    | [20350411cf](https://linux-hardware.org/?probe=20350411cf) | Sep 03, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [2e3f16bc80](https://linux-hardware.org/?probe=2e3f16bc80) | Sep 02, 2022 |
| MSI           | B450 GAMING PLUS            | Desktop     | [3561723d92](https://linux-hardware.org/?probe=3561723d92) | Sep 02, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [b54a09966b](https://linux-hardware.org/?probe=b54a09966b) | Sep 02, 2022 |
| Lenovo        | ThinkPad T480 20L6S80G00    | Notebook    | [bd599c876c](https://linux-hardware.org/?probe=bd599c876c) | Sep 02, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [d664029076](https://linux-hardware.org/?probe=d664029076) | Sep 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [d8505e212b](https://linux-hardware.org/?probe=d8505e212b) | Sep 02, 2022 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [9b42566191](https://linux-hardware.org/?probe=9b42566191) | Sep 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [8e366d7e21](https://linux-hardware.org/?probe=8e366d7e21) | Sep 02, 2022 |
| HP            | 87D6 SMVB                   | Desktop     | [8efd1ba4e0](https://linux-hardware.org/?probe=8efd1ba4e0) | Sep 02, 2022 |
| Dell          | Precision 5530              | Notebook    | [0151d15e28](https://linux-hardware.org/?probe=0151d15e28) | Sep 02, 2022 |
| Gigabyte      | B85M-HD3                    | Desktop     | [4f4717cb85](https://linux-hardware.org/?probe=4f4717cb85) | Sep 02, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [b6e6d0a261](https://linux-hardware.org/?probe=b6e6d0a261) | Sep 02, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [7ef3570396](https://linux-hardware.org/?probe=7ef3570396) | Sep 02, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [1746053c5b](https://linux-hardware.org/?probe=1746053c5b) | Sep 01, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [fb12fe29dd](https://linux-hardware.org/?probe=fb12fe29dd) | Sep 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [46e67b2b16](https://linux-hardware.org/?probe=46e67b2b16) | Sep 01, 2022 |
| Dell          | G3 3590                     | Notebook    | [cbe6c26276](https://linux-hardware.org/?probe=cbe6c26276) | Sep 01, 2022 |
| ASUSTek       | N552VW                      | Notebook    | [99d4a9be86](https://linux-hardware.org/?probe=99d4a9be86) | Sep 01, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | Notebook    | [55073b08dc](https://linux-hardware.org/?probe=55073b08dc) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [e311938d4a](https://linux-hardware.org/?probe=e311938d4a) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [8ac8531142](https://linux-hardware.org/?probe=8ac8531142) | Sep 01, 2022 |
| Toshiba       | Satellite C850              | Notebook    | [6cf6d8fca8](https://linux-hardware.org/?probe=6cf6d8fca8) | Sep 01, 2022 |
| Apple         | MacBookAir9,1               | Notebook    | [51c4002c97](https://linux-hardware.org/?probe=51c4002c97) | Sep 01, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [d96b24b7f3](https://linux-hardware.org/?probe=d96b24b7f3) | Sep 01, 2022 |
| ASRock        | B450M/ac                    | Desktop     | [393a08345e](https://linux-hardware.org/?probe=393a08345e) | Sep 01, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [838e09c9cf](https://linux-hardware.org/?probe=838e09c9cf) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [6e245e4c63](https://linux-hardware.org/?probe=6e245e4c63) | Sep 01, 2022 |
| Acer          | Aspire X3400                | Desktop     | [705a3242ae](https://linux-hardware.org/?probe=705a3242ae) | Sep 01, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | Notebook    | [d6e9455a63](https://linux-hardware.org/?probe=d6e9455a63) | Aug 31, 2022 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [1dd7a06125](https://linux-hardware.org/?probe=1dd7a06125) | Aug 31, 2022 |
| Dell          | Latitude 7275               | Tablet      | [fce77a6b4b](https://linux-hardware.org/?probe=fce77a6b4b) | Aug 31, 2022 |
| Dell          | Latitude 7275               | Tablet      | [896ceefe29](https://linux-hardware.org/?probe=896ceefe29) | Aug 31, 2022 |
| Acer          | Aspire X3400                | Desktop     | [cb5288e92d](https://linux-hardware.org/?probe=cb5288e92d) | Aug 31, 2022 |
| Acer          | Aspire X3400                | Desktop     | [5e9e5dd1ce](https://linux-hardware.org/?probe=5e9e5dd1ce) | Aug 31, 2022 |
| Dell          | Inspiron 13-7378            | Notebook    | [42666a5460](https://linux-hardware.org/?probe=42666a5460) | Aug 31, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [6eeadaf886](https://linux-hardware.org/?probe=6eeadaf886) | Aug 31, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [56e8f54a3e](https://linux-hardware.org/?probe=56e8f54a3e) | Aug 31, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [4db54180a8](https://linux-hardware.org/?probe=4db54180a8) | Aug 31, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [6d04d534fa](https://linux-hardware.org/?probe=6d04d534fa) | Aug 31, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [988032b933](https://linux-hardware.org/?probe=988032b933) | Aug 31, 2022 |
| Toshiba       | Satellite C850              | Notebook    | [5d7cb36794](https://linux-hardware.org/?probe=5d7cb36794) | Aug 31, 2022 |
| Dell          | Inspiron 3493               | Notebook    | [dc23941a16](https://linux-hardware.org/?probe=dc23941a16) | Aug 31, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [e249508d61](https://linux-hardware.org/?probe=e249508d61) | Aug 30, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [53af4f5de7](https://linux-hardware.org/?probe=53af4f5de7) | Aug 30, 2022 |
| Lenovo        | V330 81AX                   | Notebook    | [1457fc2903](https://linux-hardware.org/?probe=1457fc2903) | Aug 30, 2022 |
| Dell          | XPS 9320                    | Notebook    | [7fe70d3907](https://linux-hardware.org/?probe=7fe70d3907) | Aug 30, 2022 |
| Lenovo        | V330 81AX                   | Notebook    | [0699372547](https://linux-hardware.org/?probe=0699372547) | Aug 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [e5545fc36a](https://linux-hardware.org/?probe=e5545fc36a) | Aug 30, 2022 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [d0ca11a18a](https://linux-hardware.org/?probe=d0ca11a18a) | Aug 29, 2022 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [fb155ef3bd](https://linux-hardware.org/?probe=fb155ef3bd) | Aug 29, 2022 |
| Toshiba       | Satellite C845              | Notebook    | [58d3152512](https://linux-hardware.org/?probe=58d3152512) | Aug 29, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [b91ce43523](https://linux-hardware.org/?probe=b91ce43523) | Aug 29, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [289c5dc0b6](https://linux-hardware.org/?probe=289c5dc0b6) | Aug 29, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [059ab7e21e](https://linux-hardware.org/?probe=059ab7e21e) | Aug 29, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [907d5f36e6](https://linux-hardware.org/?probe=907d5f36e6) | Aug 29, 2022 |
| HP            | 1497                        | Desktop     | [625185d1db](https://linux-hardware.org/?probe=625185d1db) | Aug 29, 2022 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [aa5f4a0207](https://linux-hardware.org/?probe=aa5f4a0207) | Aug 29, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [281360b58a](https://linux-hardware.org/?probe=281360b58a) | Aug 29, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [065da8ca1e](https://linux-hardware.org/?probe=065da8ca1e) | Aug 29, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [13fdf5ef5e](https://linux-hardware.org/?probe=13fdf5ef5e) | Aug 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [780e5cbb44](https://linux-hardware.org/?probe=780e5cbb44) | Aug 28, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [2d89536f80](https://linux-hardware.org/?probe=2d89536f80) | Aug 28, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [d8bd3d6fc6](https://linux-hardware.org/?probe=d8bd3d6fc6) | Aug 28, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [a328df0016](https://linux-hardware.org/?probe=a328df0016) | Aug 28, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [3a448c33f9](https://linux-hardware.org/?probe=3a448c33f9) | Aug 28, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4210c6a219](https://linux-hardware.org/?probe=4210c6a219) | Aug 28, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [f07bd2b99b](https://linux-hardware.org/?probe=f07bd2b99b) | Aug 28, 2022 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [d0c37f7188](https://linux-hardware.org/?probe=d0c37f7188) | Aug 28, 2022 |
| Lenovo        | ThinkPad W520 4270CTO       | Notebook    | [c4be3fe1b6](https://linux-hardware.org/?probe=c4be3fe1b6) | Aug 28, 2022 |
| Lenovo        | ThinkPad W520 4270CTO       | Notebook    | [568802fb43](https://linux-hardware.org/?probe=568802fb43) | Aug 28, 2022 |
| HP            | ENVY dv7                    | Notebook    | [cbd3824347](https://linux-hardware.org/?probe=cbd3824347) | Aug 28, 2022 |
| Gigabyte      | H67A-USB3-B3                | Desktop     | [b04fc1333e](https://linux-hardware.org/?probe=b04fc1333e) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [a90735a9e9](https://linux-hardware.org/?probe=a90735a9e9) | Aug 27, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [2e085a419b](https://linux-hardware.org/?probe=2e085a419b) | Aug 27, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [c47cd7c7ed](https://linux-hardware.org/?probe=c47cd7c7ed) | Aug 27, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [262ff7d08a](https://linux-hardware.org/?probe=262ff7d08a) | Aug 27, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [e3c7cd81e8](https://linux-hardware.org/?probe=e3c7cd81e8) | Aug 27, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [1746f3874c](https://linux-hardware.org/?probe=1746f3874c) | Aug 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1c75cbf917](https://linux-hardware.org/?probe=1c75cbf917) | Aug 27, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [7f2e793766](https://linux-hardware.org/?probe=7f2e793766) | Aug 27, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [8aeb1b057b](https://linux-hardware.org/?probe=8aeb1b057b) | Aug 27, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [704ce84e6a](https://linux-hardware.org/?probe=704ce84e6a) | Aug 27, 2022 |
| Lenovo        | ThinkPad 20M8S1K100         | Convertible | [4e77e4b1a0](https://linux-hardware.org/?probe=4e77e4b1a0) | Aug 27, 2022 |
| Dell          | XPS 9315                    | Notebook    | [6ab1d7417d](https://linux-hardware.org/?probe=6ab1d7417d) | Aug 27, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [fdb7c715b3](https://linux-hardware.org/?probe=fdb7c715b3) | Aug 26, 2022 |
| Panasonic     | FZ55-1                      | Notebook    | [a45848f10f](https://linux-hardware.org/?probe=a45848f10f) | Aug 26, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [88467a99ae](https://linux-hardware.org/?probe=88467a99ae) | Aug 26, 2022 |
| ASRock        | B560 Steel Legend           | Desktop     | [55ebdff357](https://linux-hardware.org/?probe=55ebdff357) | Aug 26, 2022 |
| Dell          | Precision M4600             | Notebook    | [de9a03d9be](https://linux-hardware.org/?probe=de9a03d9be) | Aug 26, 2022 |
| HP            | 1850                        | Desktop     | [85b5eedc40](https://linux-hardware.org/?probe=85b5eedc40) | Aug 26, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [51e23209a4](https://linux-hardware.org/?probe=51e23209a4) | Aug 26, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [8aa6fdef16](https://linux-hardware.org/?probe=8aa6fdef16) | Aug 26, 2022 |
| ASRock        | X570 Creator                | Desktop     | [612ada6405](https://linux-hardware.org/?probe=612ada6405) | Aug 26, 2022 |
| Panasonic     | FZ55-1                      | Notebook    | [0ec106ca31](https://linux-hardware.org/?probe=0ec106ca31) | Aug 26, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [d988a14a82](https://linux-hardware.org/?probe=d988a14a82) | Aug 26, 2022 |
| Dell          | Precision M4600             | Notebook    | [83c727c6db](https://linux-hardware.org/?probe=83c727c6db) | Aug 26, 2022 |
| Acer          | Aspire X3400                | Desktop     | [81acff75f6](https://linux-hardware.org/?probe=81acff75f6) | Aug 25, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [edac754e93](https://linux-hardware.org/?probe=edac754e93) | Aug 25, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [8d1cad5e52](https://linux-hardware.org/?probe=8d1cad5e52) | Aug 25, 2022 |
| Dell          | Latitude 7275               | Tablet      | [41f2262c86](https://linux-hardware.org/?probe=41f2262c86) | Aug 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [945109f9f8](https://linux-hardware.org/?probe=945109f9f8) | Aug 25, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 Ub 82KU    | Notebook    | [5237518074](https://linux-hardware.org/?probe=5237518074) | Aug 25, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [7e2c842043](https://linux-hardware.org/?probe=7e2c842043) | Aug 25, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [b502ab922f](https://linux-hardware.org/?probe=b502ab922f) | Aug 25, 2022 |
| Dell          | Latitude 7275               | Tablet      | [43d764b91f](https://linux-hardware.org/?probe=43d764b91f) | Aug 24, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [b008775e13](https://linux-hardware.org/?probe=b008775e13) | Aug 24, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [5e20db2905](https://linux-hardware.org/?probe=5e20db2905) | Aug 24, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [f0c2f3a689](https://linux-hardware.org/?probe=f0c2f3a689) | Aug 24, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [967ff51388](https://linux-hardware.org/?probe=967ff51388) | Aug 24, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [18102e8a9a](https://linux-hardware.org/?probe=18102e8a9a) | Aug 24, 2022 |
| HP            | Dev One Notebook PC         | Notebook    | [4263165650](https://linux-hardware.org/?probe=4263165650) | Aug 24, 2022 |
| ASRock        | B660-ITX                    | Desktop     | [316ae22af8](https://linux-hardware.org/?probe=316ae22af8) | Aug 24, 2022 |
| HP            | 3647h                       | Desktop     | [dc17a52501](https://linux-hardware.org/?probe=dc17a52501) | Aug 23, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [35ffc8d54b](https://linux-hardware.org/?probe=35ffc8d54b) | Aug 23, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [6cb194ca87](https://linux-hardware.org/?probe=6cb194ca87) | Aug 23, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [8118d6f78c](https://linux-hardware.org/?probe=8118d6f78c) | Aug 23, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [beb3c92510](https://linux-hardware.org/?probe=beb3c92510) | Aug 23, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [92b070c9be](https://linux-hardware.org/?probe=92b070c9be) | Aug 23, 2022 |
| Positivo      | W942SV_SV1                  | Notebook    | [24ad2b387d](https://linux-hardware.org/?probe=24ad2b387d) | Aug 23, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [62dbb0625f](https://linux-hardware.org/?probe=62dbb0625f) | Aug 23, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [e5442dd2d4](https://linux-hardware.org/?probe=e5442dd2d4) | Aug 23, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [8e57e188c9](https://linux-hardware.org/?probe=8e57e188c9) | Aug 23, 2022 |
| ASUSTek       | P9X79 LE                    | Desktop     | [1fbde15177](https://linux-hardware.org/?probe=1fbde15177) | Aug 22, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [33a1092c01](https://linux-hardware.org/?probe=33a1092c01) | Aug 22, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [33ff4e4962](https://linux-hardware.org/?probe=33ff4e4962) | Aug 22, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [b41e95cd1b](https://linux-hardware.org/?probe=b41e95cd1b) | Aug 22, 2022 |
| Dell          | 02P9X9 A00                  | Server      | [b7d9a0c4a2](https://linux-hardware.org/?probe=b7d9a0c4a2) | Aug 22, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [8f7d642c46](https://linux-hardware.org/?probe=8f7d642c46) | Aug 22, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [6b5ced2971](https://linux-hardware.org/?probe=6b5ced2971) | Aug 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e8bee7737a](https://linux-hardware.org/?probe=e8bee7737a) | Aug 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b182084c88](https://linux-hardware.org/?probe=b182084c88) | Aug 22, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [959dda5404](https://linux-hardware.org/?probe=959dda5404) | Aug 22, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [52a1f16ef3](https://linux-hardware.org/?probe=52a1f16ef3) | Aug 22, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [ae19610f33](https://linux-hardware.org/?probe=ae19610f33) | Aug 21, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [3de1fd7f2c](https://linux-hardware.org/?probe=3de1fd7f2c) | Aug 21, 2022 |
| System76      | Oryx Pro                    | Notebook    | [7c763e43c6](https://linux-hardware.org/?probe=7c763e43c6) | Aug 21, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [f67221bd42](https://linux-hardware.org/?probe=f67221bd42) | Aug 21, 2022 |
| MSI           | FM2-A55M-E33                | Desktop     | [fac0116bf7](https://linux-hardware.org/?probe=fac0116bf7) | Aug 21, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [19158f2e35](https://linux-hardware.org/?probe=19158f2e35) | Aug 21, 2022 |
| HP            | ENVY TS m6 Sleekbook        | Notebook    | [314250b1d7](https://linux-hardware.org/?probe=314250b1d7) | Aug 21, 2022 |
| MSI           | Katana GF76 11UD            | Notebook    | [256a057752](https://linux-hardware.org/?probe=256a057752) | Aug 21, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [23c07b5d2b](https://linux-hardware.org/?probe=23c07b5d2b) | Aug 21, 2022 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [c717f7c6d5](https://linux-hardware.org/?probe=c717f7c6d5) | Aug 21, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [9c31fff4b2](https://linux-hardware.org/?probe=9c31fff4b2) | Aug 20, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [3f12b83029](https://linux-hardware.org/?probe=3f12b83029) | Aug 20, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [8df71394cd](https://linux-hardware.org/?probe=8df71394cd) | Aug 20, 2022 |
| Intel         | NUC11TNBi5 M11904-404       | Mini pc     | [d7d2cfb261](https://linux-hardware.org/?probe=d7d2cfb261) | Aug 20, 2022 |
| Intel         | NUC11TNBi5 M11904-404       | Mini pc     | [d9b92f7c2c](https://linux-hardware.org/?probe=d9b92f7c2c) | Aug 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [0cef35b44a](https://linux-hardware.org/?probe=0cef35b44a) | Aug 20, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [b6df5aec25](https://linux-hardware.org/?probe=b6df5aec25) | Aug 20, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [774796ffbd](https://linux-hardware.org/?probe=774796ffbd) | Aug 20, 2022 |
| MSI           | GF63 Thin 10UC              | Notebook    | [b04f79d93a](https://linux-hardware.org/?probe=b04f79d93a) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [3a7a62f6f8](https://linux-hardware.org/?probe=3a7a62f6f8) | Aug 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [93c5d7b0f9](https://linux-hardware.org/?probe=93c5d7b0f9) | Aug 19, 2022 |
| ASUSTek       | GL703VD                     | Notebook    | [54f9d46a7d](https://linux-hardware.org/?probe=54f9d46a7d) | Aug 19, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [7af77fd850](https://linux-hardware.org/?probe=7af77fd850) | Aug 18, 2022 |
| Gigabyte      | X299 AORUS MASTER           | Desktop     | [8d76a030ca](https://linux-hardware.org/?probe=8d76a030ca) | Aug 18, 2022 |
| Gateway       | NV55C                       | Notebook    | [377412b832](https://linux-hardware.org/?probe=377412b832) | Aug 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8a1a495053](https://linux-hardware.org/?probe=8a1a495053) | Aug 18, 2022 |
| ASUSTek       | B150M-C/BR                  | Desktop     | [b15c721e4c](https://linux-hardware.org/?probe=b15c721e4c) | Aug 18, 2022 |
| Acer          | Predator PO5-600s V:1.0     | Desktop     | [6e8b922033](https://linux-hardware.org/?probe=6e8b922033) | Aug 18, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [9a1a049600](https://linux-hardware.org/?probe=9a1a049600) | Aug 18, 2022 |
| System76      | Oryx Pro                    | Notebook    | [1583fbab76](https://linux-hardware.org/?probe=1583fbab76) | Aug 18, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [0887012e66](https://linux-hardware.org/?probe=0887012e66) | Aug 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [169469e8b6](https://linux-hardware.org/?probe=169469e8b6) | Aug 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d98e5c8b5e](https://linux-hardware.org/?probe=d98e5c8b5e) | Aug 17, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [1e4e125d11](https://linux-hardware.org/?probe=1e4e125d11) | Aug 17, 2022 |
| HP            | 2215                        | Desktop     | [71a33dc713](https://linux-hardware.org/?probe=71a33dc713) | Aug 17, 2022 |
| HP            | 2215                        | Desktop     | [aa386126ad](https://linux-hardware.org/?probe=aa386126ad) | Aug 17, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [e6e4efd93a](https://linux-hardware.org/?probe=e6e4efd93a) | Aug 17, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [45681a9dcc](https://linux-hardware.org/?probe=45681a9dcc) | Aug 17, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [8441adcca9](https://linux-hardware.org/?probe=8441adcca9) | Aug 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [5967f639c3](https://linux-hardware.org/?probe=5967f639c3) | Aug 16, 2022 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [9ac20fda5a](https://linux-hardware.org/?probe=9ac20fda5a) | Aug 16, 2022 |
| Dell          | Inspiron 5491 2n1           | Convertible | [6c0375d442](https://linux-hardware.org/?probe=6c0375d442) | Aug 16, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [5c2c3d81ef](https://linux-hardware.org/?probe=5c2c3d81ef) | Aug 16, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [0a5775d3a8](https://linux-hardware.org/?probe=0a5775d3a8) | Aug 16, 2022 |
| Acer          | Aspire A515-43              | Notebook    | [bec0e1fbd6](https://linux-hardware.org/?probe=bec0e1fbd6) | Aug 16, 2022 |
| Apple         | MacBookPro13,3              | Notebook    | [6cf76ee482](https://linux-hardware.org/?probe=6cf76ee482) | Aug 15, 2022 |
| GEO           | GeoFlex 340                 | Convertible | [d844757fcc](https://linux-hardware.org/?probe=d844757fcc) | Aug 15, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [cb59c4a321](https://linux-hardware.org/?probe=cb59c4a321) | Aug 15, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [496f0834ae](https://linux-hardware.org/?probe=496f0834ae) | Aug 15, 2022 |
| ASUSTek       | UX310UQ                     | Notebook    | [f058aa0bf2](https://linux-hardware.org/?probe=f058aa0bf2) | Aug 15, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e75de6c205](https://linux-hardware.org/?probe=e75de6c205) | Aug 15, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [332459de48](https://linux-hardware.org/?probe=332459de48) | Aug 15, 2022 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [5262ee60e8](https://linux-hardware.org/?probe=5262ee60e8) | Aug 14, 2022 |
| System76      | Oryx Pro                    | Notebook    | [b2c1b403b8](https://linux-hardware.org/?probe=b2c1b403b8) | Aug 14, 2022 |
| Acer          | Aspire 4752                 | Notebook    | [9854c38629](https://linux-hardware.org/?probe=9854c38629) | Aug 14, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [82bfe63c71](https://linux-hardware.org/?probe=82bfe63c71) | Aug 14, 2022 |
| HP            | 8054                        | Desktop     | [75e3136f50](https://linux-hardware.org/?probe=75e3136f50) | Aug 14, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [58d3be66c0](https://linux-hardware.org/?probe=58d3be66c0) | Aug 14, 2022 |
| Dell          | Latitude E7470              | Notebook    | [1c49732e63](https://linux-hardware.org/?probe=1c49732e63) | Aug 14, 2022 |
| Apple         | MacBookAir3,2               | Notebook    | [0756ed833b](https://linux-hardware.org/?probe=0756ed833b) | Aug 14, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [2c210a5825](https://linux-hardware.org/?probe=2c210a5825) | Aug 14, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [5a5538ce52](https://linux-hardware.org/?probe=5a5538ce52) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [5ef85261aa](https://linux-hardware.org/?probe=5ef85261aa) | Aug 13, 2022 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [966a3e1593](https://linux-hardware.org/?probe=966a3e1593) | Aug 13, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [ebf974be3e](https://linux-hardware.org/?probe=ebf974be3e) | Aug 13, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [81a59240ea](https://linux-hardware.org/?probe=81a59240ea) | Aug 13, 2022 |
| Gigabyte      | GA-A55M-DS2                 | Desktop     | [29e8c10282](https://linux-hardware.org/?probe=29e8c10282) | Aug 13, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [309312e25d](https://linux-hardware.org/?probe=309312e25d) | Aug 13, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [6dd71dbcf3](https://linux-hardware.org/?probe=6dd71dbcf3) | Aug 12, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [fa9cdcd977](https://linux-hardware.org/?probe=fa9cdcd977) | Aug 12, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [da7cc3fcb6](https://linux-hardware.org/?probe=da7cc3fcb6) | Aug 12, 2022 |
| Apple         | Mac-A369DDC4E67F1C45 iMa... | All in one  | [6440e9a054](https://linux-hardware.org/?probe=6440e9a054) | Aug 12, 2022 |
| Apple         | Mac-A369DDC4E67F1C45 iMa... | All in one  | [063c2efc80](https://linux-hardware.org/?probe=063c2efc80) | Aug 12, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [d7735b3387](https://linux-hardware.org/?probe=d7735b3387) | Aug 12, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [74624820da](https://linux-hardware.org/?probe=74624820da) | Aug 12, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [5e0a6f08b1](https://linux-hardware.org/?probe=5e0a6f08b1) | Aug 12, 2022 |
| MSI           | Z87-G45 GAMING              | Desktop     | [2f541727e1](https://linux-hardware.org/?probe=2f541727e1) | Aug 12, 2022 |
| Dell          | Inspiron 13-7378            | Notebook    | [097cd944e0](https://linux-hardware.org/?probe=097cd944e0) | Aug 12, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [0644c9f46c](https://linux-hardware.org/?probe=0644c9f46c) | Aug 12, 2022 |
| ASRock        | A320M                       | Desktop     | [1e0a574078](https://linux-hardware.org/?probe=1e0a574078) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [688ae71abc](https://linux-hardware.org/?probe=688ae71abc) | Aug 12, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [31a967ba05](https://linux-hardware.org/?probe=31a967ba05) | Aug 12, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [4ca1b1050d](https://linux-hardware.org/?probe=4ca1b1050d) | Aug 12, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [230d7247c0](https://linux-hardware.org/?probe=230d7247c0) | Aug 11, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [ff6370169f](https://linux-hardware.org/?probe=ff6370169f) | Aug 11, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [fe91d8cdd3](https://linux-hardware.org/?probe=fe91d8cdd3) | Aug 11, 2022 |
| Dell          | XPS 9320                    | Notebook    | [bdb29b0481](https://linux-hardware.org/?probe=bdb29b0481) | Aug 11, 2022 |
| ASUSTek       | X455LJ                      | Notebook    | [f90572b8e2](https://linux-hardware.org/?probe=f90572b8e2) | Aug 11, 2022 |
| Lenovo        | ThinkPad T450s 20BWS1RT0... | Notebook    | [b2f479d0b0](https://linux-hardware.org/?probe=b2f479d0b0) | Aug 11, 2022 |
| HP            | ENVY TS m6 Sleekbook        | Notebook    | [1f0a966a58](https://linux-hardware.org/?probe=1f0a966a58) | Aug 11, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [aebe04abda](https://linux-hardware.org/?probe=aebe04abda) | Aug 11, 2022 |
| Dell          | XPS 9320                    | Notebook    | [1d0ef5711d](https://linux-hardware.org/?probe=1d0ef5711d) | Aug 11, 2022 |
| Acer          | Aspire 4736Z                | Notebook    | [16cf1afc2a](https://linux-hardware.org/?probe=16cf1afc2a) | Aug 11, 2022 |
| Dell          | Inspiron 13-7378            | Notebook    | [637b0f0905](https://linux-hardware.org/?probe=637b0f0905) | Aug 11, 2022 |
| System76      | Galago UltraPro             | Notebook    | [8c38c1dac4](https://linux-hardware.org/?probe=8c38c1dac4) | Aug 11, 2022 |
| Dell          | Latitude 3330               | Notebook    | [e1f58ad934](https://linux-hardware.org/?probe=e1f58ad934) | Aug 10, 2022 |
| Dell          | Latitude 3330               | Notebook    | [24c9c3fe68](https://linux-hardware.org/?probe=24c9c3fe68) | Aug 10, 2022 |
| Dell          | Inspiron 13-7378            | Notebook    | [4093a81a8d](https://linux-hardware.org/?probe=4093a81a8d) | Aug 10, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [84453db535](https://linux-hardware.org/?probe=84453db535) | Aug 10, 2022 |
| ASUSTek       | K55A                        | Notebook    | [fb75627e6c](https://linux-hardware.org/?probe=fb75627e6c) | Aug 10, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [87e84c988f](https://linux-hardware.org/?probe=87e84c988f) | Aug 10, 2022 |
| Fujitsu       | LIFEBOOK UH552              | Notebook    | [cbcfa4fc6e](https://linux-hardware.org/?probe=cbcfa4fc6e) | Aug 10, 2022 |
| Apple         | MacBookPro15,4              | Notebook    | [494f3495c8](https://linux-hardware.org/?probe=494f3495c8) | Aug 10, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [c0813b6c4e](https://linux-hardware.org/?probe=c0813b6c4e) | Aug 10, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [d93b98ed98](https://linux-hardware.org/?probe=d93b98ed98) | Aug 10, 2022 |
| HP            | 3397                        | Desktop     | [9beccd0ca8](https://linux-hardware.org/?probe=9beccd0ca8) | Aug 10, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [fa15ec0e79](https://linux-hardware.org/?probe=fa15ec0e79) | Aug 09, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | Notebook    | [6ca46e8126](https://linux-hardware.org/?probe=6ca46e8126) | Aug 09, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | Notebook    | [ad3cfbb4c9](https://linux-hardware.org/?probe=ad3cfbb4c9) | Aug 09, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [6f0c6f7474](https://linux-hardware.org/?probe=6f0c6f7474) | Aug 09, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [d0b0186eb9](https://linux-hardware.org/?probe=d0b0186eb9) | Aug 09, 2022 |
| Intel         | NUC5i7RYB H73774-101        | Mini pc     | [1d9686de85](https://linux-hardware.org/?probe=1d9686de85) | Aug 09, 2022 |
| System76      | Gazelle                     | Notebook    | [a251ef0ac1](https://linux-hardware.org/?probe=a251ef0ac1) | Aug 08, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [10d18cd30b](https://linux-hardware.org/?probe=10d18cd30b) | Aug 08, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [49ab4e0197](https://linux-hardware.org/?probe=49ab4e0197) | Aug 08, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [15c1c667af](https://linux-hardware.org/?probe=15c1c667af) | Aug 08, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [9e849a1708](https://linux-hardware.org/?probe=9e849a1708) | Aug 07, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [67e1664484](https://linux-hardware.org/?probe=67e1664484) | Aug 07, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [6a73917b78](https://linux-hardware.org/?probe=6a73917b78) | Aug 07, 2022 |
| Avell High... | B.ON                        | Notebook    | [d16f62f2b9](https://linux-hardware.org/?probe=d16f62f2b9) | Aug 07, 2022 |
| HP            | Pavilion g7                 | Notebook    | [ecd57742f3](https://linux-hardware.org/?probe=ecd57742f3) | Aug 07, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [221e16bfb1](https://linux-hardware.org/?probe=221e16bfb1) | Aug 07, 2022 |
| AZW           | GTR V01                     | Mini pc     | [504142e8e0](https://linux-hardware.org/?probe=504142e8e0) | Aug 07, 2022 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [80bb75a792](https://linux-hardware.org/?probe=80bb75a792) | Aug 07, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [7e5a0c0004](https://linux-hardware.org/?probe=7e5a0c0004) | Aug 06, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [80794c55e8](https://linux-hardware.org/?probe=80794c55e8) | Aug 06, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [d1954b42ae](https://linux-hardware.org/?probe=d1954b42ae) | Aug 06, 2022 |
| HP            | 1998                        | Desktop     | [5164a156e2](https://linux-hardware.org/?probe=5164a156e2) | Aug 05, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [a711d41e0d](https://linux-hardware.org/?probe=a711d41e0d) | Aug 05, 2022 |
| Intel         | NUC6CAYB J23203-410         | Mini pc     | [ca6ec44ac0](https://linux-hardware.org/?probe=ca6ec44ac0) | Aug 05, 2022 |
| Dell          | Inspiron 3480               | Notebook    | [637d2f9f41](https://linux-hardware.org/?probe=637d2f9f41) | Aug 05, 2022 |
| Intel         | NUC6CAYB J23203-410         | Mini pc     | [6ac26cb256](https://linux-hardware.org/?probe=6ac26cb256) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | Notebook    | [abaec227ae](https://linux-hardware.org/?probe=abaec227ae) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | Notebook    | [a1effa04c3](https://linux-hardware.org/?probe=a1effa04c3) | Aug 05, 2022 |
| Intel         | D955XBK AAC96732-501        | Desktop     | [d6463d7629](https://linux-hardware.org/?probe=d6463d7629) | Aug 05, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | Notebook    | [e4d16e5adf](https://linux-hardware.org/?probe=e4d16e5adf) | Aug 05, 2022 |
| MSI           | 970A-G43                    | Desktop     | [a77e1878ae](https://linux-hardware.org/?probe=a77e1878ae) | Aug 05, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [508f6ab592](https://linux-hardware.org/?probe=508f6ab592) | Aug 04, 2022 |
| ASUSTek       | ROG Strix G713RS_G713RS     | Notebook    | [707ab083b3](https://linux-hardware.org/?probe=707ab083b3) | Aug 04, 2022 |
| HP            | ProBook 645 G1              | Notebook    | [0183d60d2c](https://linux-hardware.org/?probe=0183d60d2c) | Aug 04, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [56b0b42020](https://linux-hardware.org/?probe=56b0b42020) | Aug 04, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [cc2c2e7ceb](https://linux-hardware.org/?probe=cc2c2e7ceb) | Aug 04, 2022 |
| Lenovo        | ThinkPad E470c 20H3A000C... | Notebook    | [047888752c](https://linux-hardware.org/?probe=047888752c) | Aug 04, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [e0153e91b7](https://linux-hardware.org/?probe=e0153e91b7) | Aug 04, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [585bf3495e](https://linux-hardware.org/?probe=585bf3495e) | Aug 04, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [2d017b110e](https://linux-hardware.org/?probe=2d017b110e) | Aug 04, 2022 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [14447cf212](https://linux-hardware.org/?probe=14447cf212) | Aug 04, 2022 |
| Lenovo        | IdeaPad U410                | Notebook    | [048c78d129](https://linux-hardware.org/?probe=048c78d129) | Aug 04, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [e73f25c149](https://linux-hardware.org/?probe=e73f25c149) | Aug 03, 2022 |
| Lenovo        | ThinkPad L590 20Q7001HGE    | Notebook    | [3549ef85b6](https://linux-hardware.org/?probe=3549ef85b6) | Aug 03, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [385e290982](https://linux-hardware.org/?probe=385e290982) | Aug 03, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [c7789bc8ca](https://linux-hardware.org/?probe=c7789bc8ca) | Aug 03, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [9878a3365c](https://linux-hardware.org/?probe=9878a3365c) | Aug 03, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [85f64b5fa5](https://linux-hardware.org/?probe=85f64b5fa5) | Aug 03, 2022 |
| Intel         | D955XBK AAC96732-501        | Desktop     | [ed4b3ec577](https://linux-hardware.org/?probe=ed4b3ec577) | Aug 03, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [06da05d12b](https://linux-hardware.org/?probe=06da05d12b) | Aug 03, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [83123dba6b](https://linux-hardware.org/?probe=83123dba6b) | Aug 03, 2022 |
| Dell          | Inspiron N5040              | Notebook    | [2da4d2a843](https://linux-hardware.org/?probe=2da4d2a843) | Aug 03, 2022 |
| Intel         | DP55WB AAE64798-208         | Desktop     | [0c66cac06d](https://linux-hardware.org/?probe=0c66cac06d) | Aug 03, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [3f1ccf427a](https://linux-hardware.org/?probe=3f1ccf427a) | Aug 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [73b2c51a7e](https://linux-hardware.org/?probe=73b2c51a7e) | Aug 02, 2022 |
| Acer          | Aspire A115-32              | Notebook    | [d7eb24100d](https://linux-hardware.org/?probe=d7eb24100d) | Aug 02, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [77990d76cc](https://linux-hardware.org/?probe=77990d76cc) | Aug 02, 2022 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [6127d6e7a3](https://linux-hardware.org/?probe=6127d6e7a3) | Aug 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [ed743724e7](https://linux-hardware.org/?probe=ed743724e7) | Aug 02, 2022 |
| Lenovo        | Legion 5 15ITH6H 82JH       | Notebook    | [0b8452087a](https://linux-hardware.org/?probe=0b8452087a) | Aug 02, 2022 |
| Dell          | Latitude 5520               | Notebook    | [0406990128](https://linux-hardware.org/?probe=0406990128) | Aug 01, 2022 |
| HP            | Spectre                     | Convertible | [4d0f459190](https://linux-hardware.org/?probe=4d0f459190) | Aug 01, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [7b369e1cdf](https://linux-hardware.org/?probe=7b369e1cdf) | Aug 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [4e2361dd88](https://linux-hardware.org/?probe=4e2361dd88) | Aug 01, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [d73365fe3e](https://linux-hardware.org/?probe=d73365fe3e) | Jul 31, 2022 |
| Gigabyte      | A520I AC                    | Desktop     | [0bf3f1a8a2](https://linux-hardware.org/?probe=0bf3f1a8a2) | Jul 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [98e8e717df](https://linux-hardware.org/?probe=98e8e717df) | Jul 31, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | Notebook    | [bdc243bf9f](https://linux-hardware.org/?probe=bdc243bf9f) | Jul 31, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | Notebook    | [41a0eba80f](https://linux-hardware.org/?probe=41a0eba80f) | Jul 31, 2022 |
| HP            | Pavilion 17                 | Notebook    | [b2c0846cf5](https://linux-hardware.org/?probe=b2c0846cf5) | Jul 31, 2022 |
| Acer          | Swift SF314-51              | Notebook    | [f9a61fd8ad](https://linux-hardware.org/?probe=f9a61fd8ad) | Jul 31, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [36659d2410](https://linux-hardware.org/?probe=36659d2410) | Jul 30, 2022 |
| Toshiba       | Satellite C75D-C            | Notebook    | [f4a9c3bc7f](https://linux-hardware.org/?probe=f4a9c3bc7f) | Jul 30, 2022 |
| Toshiba       | Satellite C75D-C            | Notebook    | [f017593574](https://linux-hardware.org/?probe=f017593574) | Jul 30, 2022 |
| EVGA          | 134-KS-E377                 | Desktop     | [2624cfe274](https://linux-hardware.org/?probe=2624cfe274) | Jul 30, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [cc3deb0a17](https://linux-hardware.org/?probe=cc3deb0a17) | Jul 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ea83758651](https://linux-hardware.org/?probe=ea83758651) | Jul 30, 2022 |
| MSI           | MEG Z690 UNIFY              | Desktop     | [571f500e5e](https://linux-hardware.org/?probe=571f500e5e) | Jul 30, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [74b9e88d97](https://linux-hardware.org/?probe=74b9e88d97) | Jul 30, 2022 |
| Dell          | 0TP412                      | Desktop     | [c6138574f4](https://linux-hardware.org/?probe=c6138574f4) | Jul 30, 2022 |
| Gigabyte      | A520I AC                    | Desktop     | [f0d27ae2f0](https://linux-hardware.org/?probe=f0d27ae2f0) | Jul 30, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [0783ac445f](https://linux-hardware.org/?probe=0783ac445f) | Jul 30, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [1316e90024](https://linux-hardware.org/?probe=1316e90024) | Jul 30, 2022 |
| Intel         | NUC5i7RYB H73774-104        | Mini pc     | [773e4afb47](https://linux-hardware.org/?probe=773e4afb47) | Jul 30, 2022 |
| Lenovo        | ThinkPad P53 20QN003TUS     | Notebook    | [bf8e504209](https://linux-hardware.org/?probe=bf8e504209) | Jul 30, 2022 |
| HP            | 2215                        | Desktop     | [6e351e6da3](https://linux-hardware.org/?probe=6e351e6da3) | Jul 30, 2022 |
| PC Special... | NS50MU                      | Notebook    | [b5dd220296](https://linux-hardware.org/?probe=b5dd220296) | Jul 29, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [a6c7b90642](https://linux-hardware.org/?probe=a6c7b90642) | Jul 29, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [31b2d82a52](https://linux-hardware.org/?probe=31b2d82a52) | Jul 29, 2022 |
| Positivo      | C4128E-S                    | Notebook    | [a06c799159](https://linux-hardware.org/?probe=a06c799159) | Jul 29, 2022 |
| Lenovo        | ThinkPad P53 20QN003TUS     | Notebook    | [cf54e60bf1](https://linux-hardware.org/?probe=cf54e60bf1) | Jul 29, 2022 |
| Alienware     | 02XRCM A00                  | Desktop     | [622aa6421e](https://linux-hardware.org/?probe=622aa6421e) | Jul 29, 2022 |
| Alienware     | 02XRCM A00                  | Desktop     | [d8c0404bad](https://linux-hardware.org/?probe=d8c0404bad) | Jul 29, 2022 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [29694e2098](https://linux-hardware.org/?probe=29694e2098) | Jul 29, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [e392f0348d](https://linux-hardware.org/?probe=e392f0348d) | Jul 29, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [dea75365be](https://linux-hardware.org/?probe=dea75365be) | Jul 29, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [a5220ea2c0](https://linux-hardware.org/?probe=a5220ea2c0) | Jul 28, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [d0ff2340b1](https://linux-hardware.org/?probe=d0ff2340b1) | Jul 28, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [830913d1ab](https://linux-hardware.org/?probe=830913d1ab) | Jul 28, 2022 |
| Sony          | VPCEG27FM                   | Notebook    | [b8c840d19a](https://linux-hardware.org/?probe=b8c840d19a) | Jul 28, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [c6643cb779](https://linux-hardware.org/?probe=c6643cb779) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [be9941b639](https://linux-hardware.org/?probe=be9941b639) | Jul 28, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [c884d7548c](https://linux-hardware.org/?probe=c884d7548c) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [56faf89859](https://linux-hardware.org/?probe=56faf89859) | Jul 28, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [0fe8633425](https://linux-hardware.org/?probe=0fe8633425) | Jul 27, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [36001f3112](https://linux-hardware.org/?probe=36001f3112) | Jul 27, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [b25ca31168](https://linux-hardware.org/?probe=b25ca31168) | Jul 27, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [82192dcb1d](https://linux-hardware.org/?probe=82192dcb1d) | Jul 27, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a33f728c24](https://linux-hardware.org/?probe=a33f728c24) | Jul 27, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [2d81f40aad](https://linux-hardware.org/?probe=2d81f40aad) | Jul 27, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [8e76bb6095](https://linux-hardware.org/?probe=8e76bb6095) | Jul 27, 2022 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [8d563bf194](https://linux-hardware.org/?probe=8d563bf194) | Jul 27, 2022 |
| Dell          | 0F896N A02                  | Desktop     | [ede9425ed8](https://linux-hardware.org/?probe=ede9425ed8) | Jul 27, 2022 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [a3c2fdccfc](https://linux-hardware.org/?probe=a3c2fdccfc) | Jul 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [577c3ce56c](https://linux-hardware.org/?probe=577c3ce56c) | Jul 27, 2022 |
| Sony          | VPCF11M1E                   | Notebook    | [97a18303ee](https://linux-hardware.org/?probe=97a18303ee) | Jul 26, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [ce18b4e9ab](https://linux-hardware.org/?probe=ce18b4e9ab) | Jul 26, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [cfb18dd008](https://linux-hardware.org/?probe=cfb18dd008) | Jul 26, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [04ae47501b](https://linux-hardware.org/?probe=04ae47501b) | Jul 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [7005989783](https://linux-hardware.org/?probe=7005989783) | Jul 26, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4812de622f](https://linux-hardware.org/?probe=4812de622f) | Jul 26, 2022 |
| Acer          | Ferrari One 200             | Notebook    | [023ff9a691](https://linux-hardware.org/?probe=023ff9a691) | Jul 25, 2022 |
| Acer          | Ferrari One 200             | Notebook    | [447f8a06ea](https://linux-hardware.org/?probe=447f8a06ea) | Jul 25, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [1361193180](https://linux-hardware.org/?probe=1361193180) | Jul 25, 2022 |
| System76      | Lemur Pro                   | Notebook    | [c6269208fe](https://linux-hardware.org/?probe=c6269208fe) | Jul 25, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [b8e8d2b6c4](https://linux-hardware.org/?probe=b8e8d2b6c4) | Jul 25, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [8c5e11fe0e](https://linux-hardware.org/?probe=8c5e11fe0e) | Jul 25, 2022 |
| Dynabook      | Satellite Pro C50D-B        | Notebook    | [bd7ef0af73](https://linux-hardware.org/?probe=bd7ef0af73) | Jul 25, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [ac0f2b51c0](https://linux-hardware.org/?probe=ac0f2b51c0) | Jul 25, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [567addf380](https://linux-hardware.org/?probe=567addf380) | Jul 24, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [221bb14fbd](https://linux-hardware.org/?probe=221bb14fbd) | Jul 24, 2022 |
| Lenovo        | E41-25 81FS                 | Notebook    | [51b984566a](https://linux-hardware.org/?probe=51b984566a) | Jul 24, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [970f226406](https://linux-hardware.org/?probe=970f226406) | Jul 24, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [c1515e724a](https://linux-hardware.org/?probe=c1515e724a) | Jul 24, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [147556bf0a](https://linux-hardware.org/?probe=147556bf0a) | Jul 23, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [f13fde648e](https://linux-hardware.org/?probe=f13fde648e) | Jul 23, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [752155f862](https://linux-hardware.org/?probe=752155f862) | Jul 23, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [e31685e3ae](https://linux-hardware.org/?probe=e31685e3ae) | Jul 23, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a86b33bdc2](https://linux-hardware.org/?probe=a86b33bdc2) | Jul 22, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [f9e9de55c0](https://linux-hardware.org/?probe=f9e9de55c0) | Jul 22, 2022 |
| ASUSTek       | K52Dr                       | Notebook    | [efd71c663d](https://linux-hardware.org/?probe=efd71c663d) | Jul 22, 2022 |
| ASUSTek       | K93SM                       | Notebook    | [add292129b](https://linux-hardware.org/?probe=add292129b) | Jul 22, 2022 |
| Samsung       | 760XDA                      | Notebook    | [c3e04193b8](https://linux-hardware.org/?probe=c3e04193b8) | Jul 22, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [4763ba77ba](https://linux-hardware.org/?probe=4763ba77ba) | Jul 22, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8f131b55b9](https://linux-hardware.org/?probe=8f131b55b9) | Jul 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [da25f9d9b4](https://linux-hardware.org/?probe=da25f9d9b4) | Jul 22, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [1fef57c873](https://linux-hardware.org/?probe=1fef57c873) | Jul 22, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [c35f07bb03](https://linux-hardware.org/?probe=c35f07bb03) | Jul 21, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [f70ea66873](https://linux-hardware.org/?probe=f70ea66873) | Jul 21, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [a1cab26fa9](https://linux-hardware.org/?probe=a1cab26fa9) | Jul 21, 2022 |
| Lenovo        | ThinkPad P52 20MAS1R100     | Notebook    | [7a01b8819c](https://linux-hardware.org/?probe=7a01b8819c) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [9689ac8020](https://linux-hardware.org/?probe=9689ac8020) | Jul 21, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [f965008c98](https://linux-hardware.org/?probe=f965008c98) | Jul 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [5a52692425](https://linux-hardware.org/?probe=5a52692425) | Jul 21, 2022 |
| Toshiba       | BLB                         | Notebook    | [997a7c93d7](https://linux-hardware.org/?probe=997a7c93d7) | Jul 21, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [e73fa302e0](https://linux-hardware.org/?probe=e73fa302e0) | Jul 21, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [ed3f7b7f50](https://linux-hardware.org/?probe=ed3f7b7f50) | Jul 21, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [c6dcb4ffa6](https://linux-hardware.org/?probe=c6dcb4ffa6) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f524dac3fa](https://linux-hardware.org/?probe=f524dac3fa) | Jul 20, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [add1e46d7e](https://linux-hardware.org/?probe=add1e46d7e) | Jul 20, 2022 |
| Lenovo        | 3136 SDK0K17763 WIN 1801... | Mini pc     | [fd1c3f77f0](https://linux-hardware.org/?probe=fd1c3f77f0) | Jul 20, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [f5675c45dc](https://linux-hardware.org/?probe=f5675c45dc) | Jul 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YES... | Notebook    | [48e2fa9544](https://linux-hardware.org/?probe=48e2fa9544) | Jul 19, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [9500cfd7e1](https://linux-hardware.org/?probe=9500cfd7e1) | Jul 19, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [94b2dc99fa](https://linux-hardware.org/?probe=94b2dc99fa) | Jul 19, 2022 |
| ASUSTek       | K52Dr                       | Notebook    | [31471e3583](https://linux-hardware.org/?probe=31471e3583) | Jul 19, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [0cee82005e](https://linux-hardware.org/?probe=0cee82005e) | Jul 19, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [8a81341ecd](https://linux-hardware.org/?probe=8a81341ecd) | Jul 18, 2022 |
| Dell          | Latitude D430               | Notebook    | [22c020a070](https://linux-hardware.org/?probe=22c020a070) | Jul 18, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [c1c146a0f9](https://linux-hardware.org/?probe=c1c146a0f9) | Jul 18, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [df814add04](https://linux-hardware.org/?probe=df814add04) | Jul 18, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [2baa51bbc9](https://linux-hardware.org/?probe=2baa51bbc9) | Jul 18, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [b903541b55](https://linux-hardware.org/?probe=b903541b55) | Jul 18, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [219d908f50](https://linux-hardware.org/?probe=219d908f50) | Jul 17, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [e423ccf90d](https://linux-hardware.org/?probe=e423ccf90d) | Jul 17, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [8ae373a79c](https://linux-hardware.org/?probe=8ae373a79c) | Jul 17, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e02de9c624](https://linux-hardware.org/?probe=e02de9c624) | Jul 17, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [1c0d0a79d1](https://linux-hardware.org/?probe=1c0d0a79d1) | Jul 17, 2022 |
| Acer          | Aspire 5520                 | Notebook    | [a471c15853](https://linux-hardware.org/?probe=a471c15853) | Jul 17, 2022 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | Desktop     | [3c55557131](https://linux-hardware.org/?probe=3c55557131) | Jul 17, 2022 |
| ASUSTek       | K53SJ                       | Notebook    | [515f269efc](https://linux-hardware.org/?probe=515f269efc) | Jul 17, 2022 |
| Gigabyte      | H97M-Gaming 3               | Desktop     | [a72ad8ba14](https://linux-hardware.org/?probe=a72ad8ba14) | Jul 16, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS_22.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                              | Computers | Percent |
|--------------------------------------|-----------|---------|
| 5.19.0-76051900-generic              | 426       | 28.92%  |
| 5.17.5-76051705-generic              | 407       | 27.63%  |
| 5.18.10-76051810-generic             | 197       | 13.37%  |
| 5.17.15-76051715-generic             | 182       | 12.36%  |
| 5.16.19-76051619-generic             | 119       | 8.08%   |
| 6.0.2-76060002-generic               | 61        | 4.14%   |
| 5.19.16-76051916-generic             | 40        | 2.72%   |
| 6.0.3-76060003-generic               | 3         | 0.2%    |
| 5.16.15-76051615-generic             | 3         | 0.2%    |
| 6.0.2-x64v1-xanmod1                  | 2         | 0.14%   |
| 5.19.12-xanmod1                      | 2         | 0.14%   |
| 5.17.7-051707-generic                | 2         | 0.14%   |
| 5.17.5-051705-generic                | 2         | 0.14%   |
| 6.0.2-x64v2-xanmod1                  | 1         | 0.07%   |
| 6.0.0-060000rc1daily20220820-generic | 1         | 0.07%   |
| 6.0.0-060000-generic                 | 1         | 0.07%   |
| 5.4.210-whitehax0r                   | 1         | 0.07%   |
| 5.19.6-xanmod1-x64v2                 | 1         | 0.07%   |
| 5.19.3-051903-generic                | 1         | 0.07%   |
| 5.19.14-xanmod1                      | 1         | 0.07%   |
| 5.19.0-xanmod1-x64v2                 | 1         | 0.07%   |
| 5.19.0-rc1+                          | 1         | 0.07%   |
| 5.19.0-051900-generic                | 1         | 0.07%   |
| 5.18.6-xanmod1                       | 1         | 0.07%   |
| 5.18.4-xanmod1                       | 1         | 0.07%   |
| 5.18.16-xanmod1                      | 1         | 0.07%   |
| 5.18.11-051811-generic               | 1         | 0.07%   |
| 5.18.0-9.1-liquorix-amd64            | 1         | 0.07%   |
| 5.18.0-051800rc1-generic             | 1         | 0.07%   |
| 5.17.9-051709-generic                | 1         | 0.07%   |
| 5.17.6-051706-generic                | 1         | 0.07%   |
| 5.17.5-tkg-bmq                       | 1         | 0.07%   |
| 5.17.4-051704-generic                | 1         | 0.07%   |
| 5.17.2-xanmod1                       | 1         | 0.07%   |
| 5.17.14-xanmod1                      | 1         | 0.07%   |
| 5.17.0-051700-generic                | 1         | 0.07%   |
| 5.16.11-76051611-generic             | 1         | 0.07%   |
| 5.15.15-76051515-generic             | 1         | 0.07%   |
| 5.15.0-46-generic                    | 1         | 0.07%   |
| 5.15.0-1017-raspi                    | 1         | 0.07%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19.0  | 429       | 29.12%  |
| 5.17.5  | 410       | 27.83%  |
| 5.18.10 | 197       | 13.37%  |
| 5.17.15 | 182       | 12.36%  |
| 5.16.19 | 119       | 8.08%   |
| 6.0.2   | 64        | 4.34%   |
| 5.19.16 | 40        | 2.72%   |
| 6.0.3   | 3         | 0.2%    |
| 5.16.15 | 3         | 0.2%    |
| 6.0.0   | 2         | 0.14%   |
| 5.19.12 | 2         | 0.14%   |
| 5.18.0  | 2         | 0.14%   |
| 5.17.7  | 2         | 0.14%   |
| 5.15.0  | 2         | 0.14%   |
| 5.4.210 | 1         | 0.07%   |
| 5.19.6  | 1         | 0.07%   |
| 5.19.3  | 1         | 0.07%   |
| 5.19.14 | 1         | 0.07%   |
| 5.18.6  | 1         | 0.07%   |
| 5.18.4  | 1         | 0.07%   |
| 5.18.16 | 1         | 0.07%   |
| 5.18.11 | 1         | 0.07%   |
| 5.17.9  | 1         | 0.07%   |
| 5.17.6  | 1         | 0.07%   |
| 5.17.4  | 1         | 0.07%   |
| 5.17.2  | 1         | 0.07%   |
| 5.17.14 | 1         | 0.07%   |
| 5.17.0  | 1         | 0.07%   |
| 5.16.11 | 1         | 0.07%   |
| 5.15.15 | 1         | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17    | 587       | 40.32%  |
| 5.19    | 470       | 32.28%  |
| 5.18    | 203       | 13.94%  |
| 5.16    | 123       | 8.45%   |
| 6.0     | 69        | 4.74%   |
| 5.15    | 3         | 0.21%   |
| 5.4     | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1389      | 99.93%  |
| aarch64 | 1         | 0.07%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1348      | 96.77%  |
| KDE5            | 21        | 1.51%   |
| Unknown         | 10        | 0.72%   |
| X-Cinnamon      | 5         | 0.36%   |
| GNOME Flashback | 3         | 0.22%   |
| LXQt            | 2         | 0.14%   |
| Cinnamon        | 2         | 0.14%   |
| XFCE            | 1         | 0.07%   |
| Unity           | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1331      | 95.28%  |
| Wayland | 56        | 4.01%   |
| Unknown | 7         | 0.5%    |
| Tty     | 3         | 0.21%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1067      | 76.38%  |
| GDM3    | 322       | 23.05%  |
| SDDM    | 4         | 0.29%   |
| GDM     | 4         | 0.29%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 829       | 59.38%  |
| en_GB   | 92        | 6.59%   |
| pt_BR   | 82        | 5.87%   |
| de_DE   | 55        | 3.94%   |
| en_AU   | 40        | 2.87%   |
| C       | 38        | 2.72%   |
| it_IT   | 33        | 2.36%   |
| en_CA   | 29        | 2.08%   |
| fr_FR   | 27        | 1.93%   |
| es_ES   | 17        | 1.22%   |
| pl_PL   | 14        | 1%      |
| ru_RU   | 11        | 0.79%   |
| sv_SE   | 10        | 0.72%   |
| Unknown | 9         | 0.64%   |
| nb_NO   | 8         | 0.57%   |
| fi_FI   | 8         | 0.57%   |
| nl_NL   | 7         | 0.5%    |
| en_IN   | 6         | 0.43%   |
| en_IE   | 6         | 0.43%   |
| pt_PT   | 5         | 0.36%   |
| es_CL   | 5         | 0.36%   |
| es_AR   | 5         | 0.36%   |
| ja_JP   | 4         | 0.29%   |
| fr_CA   | 4         | 0.29%   |
| es_MX   | 4         | 0.29%   |
| en_DK   | 4         | 0.29%   |
| de_CH   | 4         | 0.29%   |
| de_AT   | 4         | 0.29%   |
| es_CO   | 3         | 0.21%   |
| en_NZ   | 3         | 0.21%   |
| da_DK   | 3         | 0.21%   |
| zh_TW   | 2         | 0.14%   |
| ro_RO   | 2         | 0.14%   |
| fr_CH   | 2         | 0.14%   |
| fr_BE   | 2         | 0.14%   |
| es_UY   | 2         | 0.14%   |
| en_ZA   | 2         | 0.14%   |
| cs_CZ   | 2         | 0.14%   |
| tr_TR   | 1         | 0.07%   |
| sr_RS   | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1086      | 77.79%  |
| EFI  | 310       | 22.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1322      | 94.9%   |
| Btrfs   | 43        | 3.09%   |
| Overlay | 24        | 1.72%   |
| Xfs     | 4         | 0.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1058      | 75.73%  |
| GPT     | 320       | 22.91%  |
| MBR     | 19        | 1.36%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1345      | 96.62%  |
| Yes       | 47        | 3.38%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1256      | 90.17%  |
| Yes       | 137       | 9.83%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| ASUSTek Computer     | 259       | 18.63%  |
| Lenovo               | 188       | 13.53%  |
| Dell                 | 184       | 13.24%  |
| Hewlett-Packard      | 144       | 10.36%  |
| MSI                  | 106       | 7.63%   |
| Gigabyte Technology  | 94        | 6.76%   |
| Apple                | 72        | 5.18%   |
| Acer                 | 65        | 4.68%   |
| ASRock               | 41        | 2.95%   |
| System76             | 34        | 2.45%   |
| Intel                | 21        | 1.51%   |
| Toshiba              | 18        | 1.29%   |
| Samsung Electronics  | 16        | 1.15%   |
| HUAWEI               | 12        | 0.86%   |
| Alienware            | 10        | 0.72%   |
| Microsoft            | 9         | 0.65%   |
| Fujitsu              | 9         | 0.65%   |
| Sony                 | 6         | 0.43%   |
| GPU Company          | 6         | 0.43%   |
| Google               | 6         | 0.43%   |
| Notebook             | 5         | 0.36%   |
| Unknown              | 5         | 0.36%   |
| Razer                | 4         | 0.29%   |
| Framework            | 4         | 0.29%   |
| Positivo             | 3         | 0.22%   |
| Pegatron             | 3         | 0.22%   |
| PC Specialist        | 3         | 0.22%   |
| Medion               | 3         | 0.22%   |
| MACHINIST            | 3         | 0.22%   |
| AZW                  | 3         | 0.22%   |
| TUXEDO               | 2         | 0.14%   |
| Timi                 | 2         | 0.14%   |
| Panasonic            | 2         | 0.14%   |
| NZXT                 | 2         | 0.14%   |
| IP3 Tech             | 2         | 0.14%   |
| Intel Client Systems | 2         | 0.14%   |
| HONOR                | 2         | 0.14%   |
| Foxconn              | 2         | 0.14%   |
| EVGA                 | 2         | 0.14%   |
| ECS                  | 2         | 0.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| System76 Oryx Pro                    | 11        | 0.79%   |
| ASUS All Series                      | 11        | 0.79%   |
| Unknown                              | 8         | 0.58%   |
| System76 Lemur Pro                   | 7         | 0.5%    |
| Gigabyte B450 AORUS M                | 6         | 0.43%   |
| Dell XPS 15 9520                     | 6         | 0.43%   |
| ASUS TUF Gaming B550-PLUS            | 6         | 0.43%   |
| Apple MacBookAir7,2                  | 6         | 0.43%   |
| Apple MacBookAir6,2                  | 6         | 0.43%   |
| Gigabyte X570 AORUS ELITE            | 5         | 0.36%   |
| ASUS ROG STRIX B550-I GAMING         | 5         | 0.36%   |
| ASUS ROG STRIX B550-F GAMING         | 5         | 0.36%   |
| ASUS ROG STRIX B450-F GAMING         | 5         | 0.36%   |
| Apple MacBookPro9,2                  | 5         | 0.36%   |
| MSI MS-7B86                          | 4         | 0.29%   |
| Lenovo IdeaPad S145-15API 81V7       | 4         | 0.29%   |
| Gigabyte B450M DS3H                  | 4         | 0.29%   |
| ASUS ROG CROSSHAIR VIII DARK HERO    | 4         | 0.29%   |
| ASUS PRIME B450M-A                   | 4         | 0.29%   |
| System76 Thelio                      | 3         | 0.22%   |
| System76 Galago Pro                  | 3         | 0.22%   |
| System76 Darter Pro                  | 3         | 0.22%   |
| MSI Prestige 15 A10SC                | 3         | 0.22%   |
| MSI MS-7D54                          | 3         | 0.22%   |
| MSI MS-7D25                          | 3         | 0.22%   |
| MSI MS-7C37                          | 3         | 0.22%   |
| MSI MS-7C35                          | 3         | 0.22%   |
| MSI MS-7C02                          | 3         | 0.22%   |
| MSI MS-7693                          | 3         | 0.22%   |
| Lenovo Legion Y530-15ICH 81FV        | 3         | 0.22%   |
| HP Pavilion Notebook                 | 3         | 0.22%   |
| HP Pavilion 15                       | 3         | 0.22%   |
| HP OMEN Laptop 15-en0xxx             | 3         | 0.22%   |
| HP ENVY x360 2-in-1 Laptop 15-ey0xxx | 3         | 0.22%   |
| HP Dev One Notebook PC               | 3         | 0.22%   |
| HP Compaq Elite 8300 USDT            | 3         | 0.22%   |
| GPU Company GWTN141-10               | 3         | 0.22%   |
| GPU Company GWTC116-2                | 3         | 0.22%   |
| Gigabyte X570 AORUS MASTER           | 3         | 0.22%   |
| Gigabyte B550 AORUS ELITE V2         | 3         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ASUS ROG           | 74        | 5.32%   |
| Lenovo ThinkPad    | 70        | 5.04%   |
| Dell Inspiron      | 50        | 3.6%    |
| Acer Aspire        | 45        | 3.24%   |
| Lenovo IdeaPad     | 40        | 2.88%   |
| Dell Latitude      | 38        | 2.73%   |
| Dell XPS           | 36        | 2.59%   |
| ASUS TUF           | 27        | 1.94%   |
| ASUS PRIME         | 25        | 1.8%    |
| HP Pavilion        | 23        | 1.65%   |
| Dell Precision     | 22        | 1.58%   |
| Lenovo Legion      | 21        | 1.51%   |
| HP Laptop          | 20        | 1.44%   |
| HP EliteBook       | 19        | 1.37%   |
| HP ENVY            | 16        | 1.15%   |
| Toshiba Satellite  | 15        | 1.08%   |
| HP ProBook         | 13        | 0.94%   |
| Dell Vostro        | 13        | 0.94%   |
| Lenovo ThinkCentre | 12        | 0.86%   |
| Gigabyte X570      | 12        | 0.86%   |
| Dell OptiPlex      | 12        | 0.86%   |
| ASUS Zenbook       | 12        | 0.86%   |
| ASUS VivoBook      | 12        | 0.86%   |
| System76 Oryx      | 11        | 0.79%   |
| ASUS All           | 11        | 0.79%   |
| Lenovo Yoga        | 10        | 0.72%   |
| HP Compaq          | 10        | 0.72%   |
| Microsoft Surface  | 9         | 0.65%   |
| Gigabyte B450      | 9         | 0.65%   |
| HP OMEN            | 8         | 0.58%   |
| ASUS ASUS          | 8         | 0.58%   |
| Acer Nitro         | 8         | 0.58%   |
| Unknown            | 8         | 0.58%   |
| System76 Lemur     | 7         | 0.5%    |
| HP EliteDesk       | 7         | 0.5%    |
| Apple MacBookPro11 | 7         | 0.5%    |
| MSI Prestige       | 6         | 0.43%   |
| Lenovo ThinkBook   | 6         | 0.43%   |
| HP ZBook           | 6         | 0.43%   |
| Gigabyte B550      | 6         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 208       | 14.96%  |
| 2020    | 184       | 13.24%  |
| 2019    | 147       | 10.58%  |
| 2018    | 145       | 10.43%  |
| 2022    | 96        | 6.91%   |
| 2016    | 80        | 5.76%   |
| 2017    | 79        | 5.68%   |
| 2013    | 78        | 5.61%   |
| 2012    | 74        | 5.32%   |
| 2014    | 73        | 5.25%   |
| 2015    | 63        | 4.53%   |
| 2011    | 58        | 4.17%   |
| 2010    | 43        | 3.09%   |
| 2009    | 41        | 2.95%   |
| 2008    | 11        | 0.79%   |
| 2007    | 8         | 0.58%   |
| 2006    | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 811       | 58.35%  |
| Desktop        | 474       | 34.1%   |
| Convertible    | 51        | 3.67%   |
| Mini pc        | 21        | 1.51%   |
| All in one     | 15        | 1.08%   |
| Tablet         | 14        | 1.01%   |
| Server         | 3         | 0.22%   |
| System on chip | 1         | 0.07%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1389      | 99.93%  |
| Enabled  | 1         | 0.07%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1363      | 98.06%  |
| Yes  | 27        | 1.94%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 393       | 28.07%  |
| 4.01-8.0        | 303       | 21.64%  |
| 8.01-16.0       | 250       | 17.86%  |
| 32.01-64.0      | 233       | 16.64%  |
| 3.01-4.0        | 129       | 9.21%   |
| 64.01-256.0     | 65        | 4.64%   |
| 24.01-32.0      | 19        | 1.36%   |
| 1.01-2.0        | 4         | 0.29%   |
| More than 256.0 | 2         | 0.14%   |
| 2.01-3.0        | 2         | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 486       | 32.97%  |
| 4.01-8.0    | 363       | 24.63%  |
| 3.01-4.0    | 332       | 22.52%  |
| 1.01-2.0    | 181       | 12.28%  |
| 8.01-16.0   | 90        | 6.11%   |
| 16.01-24.0  | 16        | 1.09%   |
| 32.01-64.0  | 4         | 0.27%   |
| 24.01-32.0  | 1         | 0.07%   |
| 64.01-256.0 | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 799       | 57.15%  |
| 2      | 369       | 26.39%  |
| 3      | 130       | 9.3%    |
| 4      | 46        | 3.29%   |
| 5      | 23        | 1.65%   |
| 6      | 15        | 1.07%   |
| 7      | 7         | 0.5%    |
| 9      | 3         | 0.21%   |
| 10     | 2         | 0.14%   |
| 0      | 2         | 0.14%   |
| 19     | 1         | 0.07%   |
| 11     | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1062      | 76.35%  |
| Yes       | 329       | 23.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1143      | 81.94%  |
| No        | 252       | 18.06%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1173      | 84.33%  |
| No        | 218       | 15.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1012      | 72.49%  |
| No        | 384       | 27.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 437       | 31.26%  |
| Brazil       | 111       | 7.94%   |
| Germany      | 82        | 5.87%   |
| UK           | 62        | 4.43%   |
| Italy        | 62        | 4.43%   |
| Canada       | 60        | 4.29%   |
| Australia    | 48        | 3.43%   |
| India        | 39        | 2.79%   |
| France       | 38        | 2.72%   |
| Netherlands  | 27        | 1.93%   |
| Norway       | 24        | 1.72%   |
| Russia       | 22        | 1.57%   |
| Poland       | 20        | 1.43%   |
| Sweden       | 19        | 1.36%   |
| Spain        | 19        | 1.36%   |
| Mexico       | 17        | 1.22%   |
| Switzerland  | 16        | 1.14%   |
| Finland      | 15        | 1.07%   |
| Portugal     | 13        | 0.93%   |
| Austria      | 13        | 0.93%   |
| Argentina    | 13        | 0.93%   |
| Greece       | 12        | 0.86%   |
| Romania      | 10        | 0.72%   |
| Japan        | 10        | 0.72%   |
| Belgium      | 10        | 0.72%   |
| Turkey       | 9         | 0.64%   |
| Philippines  | 9         | 0.64%   |
| New Zealand  | 9         | 0.64%   |
| Ireland      | 9         | 0.64%   |
| Denmark      | 9         | 0.64%   |
| Chile        | 9         | 0.64%   |
| Thailand     | 8         | 0.57%   |
| Indonesia    | 7         | 0.5%    |
| Hungary      | 7         | 0.5%    |
| Colombia     | 7         | 0.5%    |
| Serbia       | 6         | 0.43%   |
| Hong Kong    | 6         | 0.43%   |
| Egypt        | 6         | 0.43%   |
| Czechia      | 6         | 0.43%   |
| South Africa | 5         | 0.36%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Milan          | 15        | 1.06%   |
| Melbourne      | 12        | 0.85%   |
| Brisbane       | 12        | 0.85%   |
| Berlin         | 11        | 0.78%   |
| Rio de Janeiro | 10        | 0.71%   |
| Seattle        | 9         | 0.64%   |
| Oslo           | 9         | 0.64%   |
| Zurich         | 8         | 0.56%   |
| Vienna         | 8         | 0.56%   |
| Sydney         | 8         | 0.56%   |
| Sao Paulo      | 8         | 0.56%   |
| Rome           | 8         | 0.56%   |
| Helsinki       | 8         | 0.56%   |
| Paris          | 7         | 0.49%   |
| Istanbul       | 7         | 0.49%   |
| Dallas         | 7         | 0.49%   |
| San Francisco  | 6         | 0.42%   |
| Moscow         | 6         | 0.42%   |
| Madrid         | 6         | 0.42%   |
| London         | 6         | 0.42%   |
| Edmonton       | 6         | 0.42%   |
| Bengaluru      | 6         | 0.42%   |
| Toronto        | 5         | 0.35%   |
| Stockholm      | 5         | 0.35%   |
| St Petersburg  | 5         | 0.35%   |
| Munich         | 5         | 0.35%   |
| Mumbai         | 5         | 0.35%   |
| Mannheim       | 5         | 0.35%   |
| Lisbon         | 5         | 0.35%   |
| Hamburg        | 5         | 0.35%   |
| Chicago        | 5         | 0.35%   |
| Tucson         | 4         | 0.28%   |
| Singapore      | 4         | 0.28%   |
| San Jose       | 4         | 0.28%   |
| San Antonio    | 4         | 0.28%   |
| Montreal       | 4         | 0.28%   |
| Miami          | 4         | 0.28%   |
| Manaus         | 4         | 0.28%   |
| Dublin         | 4         | 0.28%   |
| Denver         | 4         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 406       | 541    | 19.04%  |
| Seagate                        | 244       | 328    | 11.44%  |
| WDC                            | 242       | 320    | 11.35%  |
| SanDisk                        | 154       | 188    | 7.22%   |
| Toshiba                        | 117       | 133    | 5.49%   |
| Kingston                       | 111       | 131    | 5.21%   |
| Crucial                        | 101       | 134    | 4.74%   |
| SK hynix                       | 77        | 85     | 3.61%   |
| Intel                          | 53        | 59     | 2.49%   |
| Unknown                        | 49        | 64     | 2.3%    |
| Micron Technology              | 49        | 55     | 2.3%    |
| Apple                          | 41        | 46     | 1.92%   |
| Phison                         | 39        | 50     | 1.83%   |
| HGST                           | 36        | 38     | 1.69%   |
| Hitachi                        | 35        | 47     | 1.64%   |
| A-DATA Technology              | 31        | 33     | 1.45%   |
| Silicon Motion                 | 21        | 27     | 0.98%   |
| Micron/Crucial Technology      | 21        | 25     | 0.98%   |
| PNY                            | 20        | 26     | 0.94%   |
| China                          | 19        | 22     | 0.89%   |
| KIOXIA                         | 16        | 17     | 0.75%   |
| SPCC                           | 12        | 15     | 0.56%   |
| Phison Electronics             | 12        | 18     | 0.56%   |
| Netac                          | 11        | 11     | 0.52%   |
| LITEON                         | 9         | 10     | 0.42%   |
| Intenso                        | 9         | 9      | 0.42%   |
| Unknown                        | 9         | 10     | 0.42%   |
| Team                           | 8         | 10     | 0.38%   |
| ADATA Technology               | 7         | 7      | 0.33%   |
| Patriot                        | 6         | 7      | 0.28%   |
| LITEONIT                       | 6         | 8      | 0.28%   |
| KingSpec                       | 6         | 7      | 0.28%   |
| XPG                            | 5         | 5      | 0.23%   |
| Union Memory (Shenzhen)        | 5         | 7      | 0.23%   |
| Solid State Storage Technology | 5         | 5      | 0.23%   |
| OCZ                            | 5         | 7      | 0.23%   |
| Lexar                          | 5         | 5      | 0.23%   |
| JMicron Technology             | 5         | 14     | 0.23%   |
| Hewlett-Packard                | 5         | 5      | 0.23%   |
| Fujitsu                        | 5         | 6      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 1TB                           | 36        | 1.52%   |
| Samsung NVMe SSD Drive 500GB                         | 29        | 1.22%   |
| SanDisk NVMe SSD Drive 1TB                           | 28        | 1.18%   |
| Kingston SA400S37240G 240GB SSD                      | 28        | 1.18%   |
| Samsung NVMe SSD Drive 512GB                         | 22        | 0.93%   |
| Seagate ST2000DM008-2FR102 2TB                       | 21        | 0.88%   |
| Samsung NVMe SSD Drive 2TB                           | 20        | 0.84%   |
| Samsung SSD 850 EVO 500GB                            | 19        | 0.8%    |
| Seagate ST1000LM035-1RK172 1TB                       | 17        | 0.72%   |
| Crucial CT1000MX500SSD1 1TB                          | 17        | 0.72%   |
| Samsung SSD 860 EVO 1TB                              | 16        | 0.67%   |
| SK hynix NVMe SSD Drive 512GB                        | 15        | 0.63%   |
| SanDisk NVMe SSD Drive 512GB                         | 15        | 0.63%   |
| Samsung SSD 850 EVO 250GB                            | 15        | 0.63%   |
| Kingston SA400S37120G 120GB SSD                      | 14        | 0.59%   |
| Seagate ST1000DM010-2EP102 1TB                       | 13        | 0.55%   |
| Samsung SSD 860 EVO 500GB                            | 13        | 0.55%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB               | 13        | 0.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB  | 13        | 0.55%   |
| HGST HTS721010A9E630 1TB                             | 13        | 0.55%   |
| Crucial CT240BX500SSD1 240GB                         | 13        | 0.55%   |
| SanDisk NVMe SSD Drive 500GB                         | 12        | 0.51%   |
| Kingston SA400S37480G 480GB SSD                      | 12        | 0.51%   |
| Toshiba MQ01ABD100 1TB                               | 11        | 0.46%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 11        | 0.46%   |
| Seagate ST1000DM003-1ER162 1TB                       | 11        | 0.46%   |
| Samsung SSD 970 EVO Plus 1TB                         | 11        | 0.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 250GB | 11        | 0.46%   |
| Crucial CT500MX500SSD1 500GB                         | 11        | 0.46%   |
| SanDisk NVMe SSD Drive 256GB                         | 10        | 0.42%   |
| Samsung NVMe SSD Drive 250GB                         | 10        | 0.42%   |
| Samsung NVMe SSD Drive 1024GB                        | 10        | 0.42%   |
| Kingston NVMe SSD Drive 512GB                        | 10        | 0.42%   |
| Crucial CT1000BX500SSD1 1TB                          | 10        | 0.42%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 9         | 0.38%   |
| SK hynix NVMe SSD Drive 1024GB                       | 9         | 0.38%   |
| Seagate ST500DM002-1BD142 500GB                      | 9         | 0.38%   |
| Seagate ST1000DM003-1CH162 1TB                       | 9         | 0.38%   |
| Seagate Expansion 2TB                                | 9         | 0.38%   |
| Samsung SSD 980 PRO 1TB                              | 9         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 234       | 312    | 38.36%  |
| WDC                 | 175       | 231    | 28.69%  |
| Toshiba             | 79        | 90     | 12.95%  |
| HGST                | 36        | 38     | 5.9%    |
| Hitachi             | 35        | 47     | 5.74%   |
| Samsung Electronics | 18        | 22     | 2.95%   |
| Apple               | 12        | 12     | 1.97%   |
| Unknown             | 5         | 9      | 0.82%   |
| Fujitsu             | 4         | 5      | 0.66%   |
| SABRENT             | 2         | 3      | 0.33%   |
| Maxtor              | 2         | 2      | 0.33%   |
| JMicron Technology  | 2         | 7      | 0.33%   |
| USB3.0              | 1         | 1      | 0.16%   |
| SATAFIRM            | 1         | 1      | 0.16%   |
| Intenso             | 1         | 1      | 0.16%   |
| HGST HDN            | 1         | 1      | 0.16%   |
| ASMT                | 1         | 1      | 0.16%   |
| Asm                 | 1         | 1      | 0.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 168       | 213    | 23.63%  |
| Crucial             | 91        | 120    | 12.8%   |
| Kingston            | 85        | 95     | 11.95%  |
| SanDisk             | 61        | 71     | 8.58%   |
| WDC                 | 45        | 53     | 6.33%   |
| Apple               | 25        | 27     | 3.52%   |
| A-DATA Technology   | 22        | 24     | 3.09%   |
| PNY                 | 20        | 26     | 2.81%   |
| China               | 18        | 21     | 2.53%   |
| Intel               | 15        | 15     | 2.11%   |
| Toshiba             | 12        | 12     | 1.69%   |
| SK hynix            | 11        | 13     | 1.55%   |
| Netac               | 10        | 10     | 1.41%   |
| SPCC                | 9         | 10     | 1.27%   |
| Micron Technology   | 9         | 9      | 1.27%   |
| LITEON              | 8         | 9      | 1.13%   |
| Patriot             | 6         | 7      | 0.84%   |
| LITEONIT            | 6         | 8      | 0.84%   |
| KingSpec            | 6         | 7      | 0.84%   |
| OCZ                 | 5         | 7      | 0.7%    |
| Intenso             | 5         | 5      | 0.7%    |
| Team                | 4         | 6      | 0.56%   |
| Lexar               | 4         | 4      | 0.56%   |
| MyDigitalSSD        | 3         | 3      | 0.42%   |
| KingDian            | 3         | 3      | 0.42%   |
| Hewlett-Packard     | 3         | 3      | 0.42%   |
| Apacer              | 3         | 5      | 0.42%   |
| Transcend           | 2         | 3      | 0.28%   |
| Seagate             | 2         | 2      | 0.28%   |
| PNY USB             | 2         | 2      | 0.28%   |
| Mushkin             | 2         | 3      | 0.28%   |
| GOODRAM             | 2         | 2      | 0.28%   |
| FORESEE             | 2         | 3      | 0.28%   |
| AFOX                | 2         | 2      | 0.28%   |
| Unknown             | 2         | 2      | 0.28%   |
| Yeyian              | 1         | 1      | 0.14%   |
| W800S               | 1         | 1      | 0.14%   |
| TwinMOS             | 1         | 1      | 0.14%   |
| TrekStor            | 1         | 1      | 0.14%   |
| TO Exter            | 1         | 1      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 685       | 929    | 35.81%  |
| SSD     | 628       | 845    | 32.83%  |
| HDD     | 514       | 784    | 26.87%  |
| MMC     | 43        | 49     | 2.25%   |
| Unknown | 43        | 62     | 2.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 915       | 1571   | 53.07%  |
| NVMe | 684       | 924    | 39.68%  |
| SAS  | 82        | 125    | 4.76%   |
| MMC  | 43        | 49     | 2.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 622       | 842    | 51.24%  |
| 0.51-1.0   | 378       | 487    | 31.14%  |
| 1.01-2.0   | 131       | 169    | 10.79%  |
| 3.01-4.0   | 35        | 48     | 2.88%   |
| 4.01-10.0  | 24        | 42     | 1.98%   |
| 2.01-3.0   | 21        | 30     | 1.73%   |
| 10.01-20.0 | 3         | 11     | 0.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 397       | 28.08%  |
| 251-500        | 361       | 25.53%  |
| 501-1000       | 298       | 21.07%  |
| 1001-2000      | 139       | 9.83%   |
| More than 3000 | 71        | 5.02%   |
| 2001-3000      | 49        | 3.47%   |
| 51-100         | 33        | 2.33%   |
| 1-20           | 30        | 2.12%   |
| 21-50          | 26        | 1.84%   |
| Unknown        | 10        | 0.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 439       | 30.21%  |
| 21-50          | 314       | 21.61%  |
| 101-250        | 215       | 14.8%   |
| 51-100         | 191       | 13.15%  |
| 251-500        | 126       | 8.67%   |
| 501-1000       | 74        | 5.09%   |
| 1001-2000      | 45        | 3.1%    |
| More than 3000 | 27        | 1.86%   |
| 2001-3000      | 12        | 0.83%   |
| Unknown        | 10        | 0.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB                          | 3         | 4      | 7.14%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 1      | 2.38%   |
| WDC WD60EFRX-68L0BN1 6TB                            | 1         | 1      | 2.38%   |
| WDC WD5001AALS-00J7B1 500GB                         | 1         | 1      | 2.38%   |
| WDC WD5000AADS-00S9B0 500GB                         | 1         | 1      | 2.38%   |
| WDC WD20EFRX-68AX9N0 2TB                            | 1         | 2      | 2.38%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 1      | 2.38%   |
| WDC WD10EZEX-60WN4A0 1TB                            | 1         | 1      | 2.38%   |
| WDC WD1001FALS-00E8B0 1TB                           | 1         | 1      | 2.38%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD            | 1         | 1      | 2.38%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 2.38%   |
| Team TM8FP4004T 4TB                                 | 1         | 1      | 2.38%   |
| SK hynix PC711 HFS001TDE9X073N 1024GB               | 1         | 1      | 2.38%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 2.38%   |
| Seagate ST500LM030-2E717D 500GB                     | 1         | 1      | 2.38%   |
| Seagate ST5000LM000-2AN170 5TB                      | 1         | 1      | 2.38%   |
| Seagate ST320LM001 HN-M320MBB 320GB                 | 1         | 1      | 2.38%   |
| Seagate ST2000DM008-2FR102 2TB                      | 1         | 1      | 2.38%   |
| Seagate ST2000DM006-2DM164 2TB                      | 1         | 1      | 2.38%   |
| Seagate ST1000LX015-1U7172 1TB                      | 1         | 1      | 2.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 2.38%   |
| Seagate Expansion Desk 8TB                          | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 850 PRO 256GB               | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 850 EVO 500GB               | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 850 EVO 250GB               | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 840 PRO Series 512GB        | 1         | 1      | 2.38%   |
| Samsung Electronics HD103SI 1TB                     | 1         | 1      | 2.38%   |
| SABRENT Disk 500GB                                  | 1         | 1      | 2.38%   |
| Plextor PX-128M6M 128GB SSD                         | 1         | 1      | 2.38%   |
| Micron Technology MTFDDAK256MAY-1AH1ZABHA 256GB SSD | 1         | 1      | 2.38%   |
| Lexar 1TB SSD                                       | 1         | 1      | 2.38%   |
| Leven JAJS600M256C 256GB                            | 1         | 1      | 2.38%   |
| Kingston SV300S37A240G 240GB SSD                    | 1         | 1      | 2.38%   |
| Intel SSDPEKNW010T8 1TB                             | 1         | 1      | 2.38%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 3      | 2.38%   |
| Hitachi HDP725050GLA360 500GB                       | 1         | 1      | 2.38%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 2.38%   |
| Crucial CT525MX300SSD1 528GB                        | 1         | 1      | 2.38%   |
| BAITITON BT58SSD08M 128GB                           | 1         | 1      | 2.38%   |
| A-DATA Technology SU800 512GB SSD                   | 1         | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 9      | 19.51%  |
| Seagate             | 8         | 9      | 19.51%  |
| Samsung Electronics | 5         | 5      | 12.2%   |
| HGST                | 4         | 5      | 9.76%   |
| Toshiba             | 2         | 2      | 4.88%   |
| Hitachi             | 2         | 4      | 4.88%   |
| Team                | 1         | 1      | 2.44%   |
| SK hynix            | 1         | 1      | 2.44%   |
| SABRENT             | 1         | 1      | 2.44%   |
| Plextor             | 1         | 1      | 2.44%   |
| Micron Technology   | 1         | 1      | 2.44%   |
| Lexar               | 1         | 1      | 2.44%   |
| Leven               | 1         | 1      | 2.44%   |
| Kingston            | 1         | 1      | 2.44%   |
| Intel               | 1         | 1      | 2.44%   |
| Crucial             | 1         | 1      | 2.44%   |
| BAITITON            | 1         | 1      | 2.44%   |
| A-DATA Technology   | 1         | 1      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 9      | 33.33%  |
| WDC                 | 7         | 8      | 29.17%  |
| HGST                | 4         | 5      | 16.67%  |
| Hitachi             | 2         | 4      | 8.33%   |
| Toshiba             | 1         | 1      | 4.17%   |
| Samsung Electronics | 1         | 1      | 4.17%   |
| SABRENT             | 1         | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 29     | 57.5%   |
| SSD  | 13        | 13     | 32.5%   |
| NVMe | 4         | 4      | 10%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1090      | 2092   | 73.9%   |
| Works    | 346       | 530    | 23.46%  |
| Malfunc  | 38        | 46     | 2.58%   |
| Failed   | 1         | 1      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 796       | 40.12%  |
| AMD                            | 350       | 17.64%  |
| Samsung Electronics            | 274       | 13.81%  |
| SanDisk                        | 122       | 6.15%   |
| SK hynix                       | 66        | 3.33%   |
| Phison Electronics             | 56        | 2.82%   |
| Micron Technology              | 39        | 1.97%   |
| Micron/Crucial Technology      | 31        | 1.56%   |
| Toshiba America Info Systems   | 28        | 1.41%   |
| Kingston Technology Company    | 28        | 1.41%   |
| Nvidia                         | 27        | 1.36%   |
| ASMedia Technology             | 26        | 1.31%   |
| Silicon Motion                 | 25        | 1.26%   |
| ADATA Technology               | 18        | 0.91%   |
| Marvell Technology Group       | 17        | 0.86%   |
| KIOXIA                         | 17        | 0.86%   |
| Solid State Storage Technology | 8         | 0.4%    |
| Realtek Semiconductor          | 8         | 0.4%    |
| Seagate Technology             | 7         | 0.35%   |
| Union Memory (Shenzhen)        | 6         | 0.3%    |
| JMicron Technology             | 6         | 0.3%    |
| Apple                          | 5         | 0.25%   |
| Shenzhen Longsys Electronics   | 4         | 0.2%    |
| LSI Logic / Symbios Logic      | 4         | 0.2%    |
| Unknown                        | 3         | 0.15%   |
| Broadcom / LSI                 | 3         | 0.15%   |
| Silicon Image                  | 2         | 0.1%    |
| MAXIO Technology (Hangzhou)    | 2         | 0.1%    |
| Lite-On Technology             | 2         | 0.1%    |
| Yangtze Memory Technologies    | 1         | 0.05%   |
| VIA Technologies               | 1         | 0.05%   |
| O2 Micro                       | 1         | 0.05%   |
| Hewlett-Packard                | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 262       | 11.97%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 125       | 5.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 64        | 2.92%   |
| AMD 400 Series Chipset SATA Controller                                         | 63        | 2.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 61        | 2.79%   |
| Samsung NVMe SSD Controller 980                                                | 52        | 2.38%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 51        | 2.33%   |
| AMD 500 Series Chipset SATA Controller                                         | 49        | 2.24%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 48        | 2.19%   |
| Intel Volume Management Device NVMe RAID Controller                            | 46        | 2.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 45        | 2.06%   |
| Micron Non-Volatile memory controller                                          | 39        | 1.78%   |
| SK hynix Gold P31 SSD                                                          | 38        | 1.74%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 37        | 1.69%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 35        | 1.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 32        | 1.46%   |
| Phison E12 NVMe Controller                                                     | 30        | 1.37%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 30        | 1.37%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 29        | 1.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 28        | 1.28%   |
| SanDisk Non-Volatile memory controller                                         | 24        | 1.1%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 24        | 1.1%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 23        | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 23        | 1.05%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 22        | 1.01%   |
| Intel SSD 660P Series                                                          | 22        | 1.01%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 22        | 1.01%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 21        | 0.96%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 20        | 0.91%   |
| Intel Comet Lake SATA AHCI Controller                                          | 19        | 0.87%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 18        | 0.82%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 17        | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 17        | 0.78%   |
| Intel SATA Controller [RAID mode]                                              | 16        | 0.73%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 16        | 0.73%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 16        | 0.73%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 15        | 0.69%   |
| Kingston Company Company Non-Volatile memory controller                        | 15        | 0.69%   |
| Intel Tiger Lake-LP SATA Controller                                            | 15        | 0.69%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 15        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1016      | 52.94%  |
| NVMe | 683       | 35.59%  |
| RAID | 123       | 6.41%   |
| IDE  | 90        | 4.69%   |
| SAS  | 7         | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 946       | 68.06%  |
| AMD    | 443       | 31.87%  |
| ARM    | 1         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 24        | 1.72%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 23        | 1.65%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 23        | 1.65%   |
| AMD Ryzen 5 3600 6-Core Processor             | 22        | 1.58%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 19        | 1.36%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 17        | 1.22%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 15        | 1.08%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 15        | 1.08%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 15        | 1.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 14        | 1.01%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 14        | 1.01%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 14        | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 0.93%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 0.86%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 12        | 0.86%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 12        | 0.86%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 11        | 0.79%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 11        | 0.79%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 0.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 10        | 0.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 10        | 0.72%   |
| Intel 12th Gen Core i7-12700H                 | 10        | 0.72%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 10        | 0.72%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 10        | 0.72%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 10        | 0.72%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 8         | 0.57%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 8         | 0.57%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 0.57%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 8         | 0.57%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 8         | 0.57%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 8         | 0.57%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 8         | 0.57%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 8         | 0.57%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 7         | 0.5%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 7         | 0.5%    |
| Intel Core i7-3770 CPU @ 3.40GHz              | 7         | 0.5%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 0.5%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.5%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 7         | 0.5%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 7         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 311       | 22.36%  |
| Intel Core i5           | 271       | 19.48%  |
| Other                   | 153       | 11%     |
| AMD Ryzen 5             | 141       | 10.14%  |
| AMD Ryzen 7             | 128       | 9.2%    |
| Intel Core i3           | 67        | 4.82%   |
| AMD Ryzen 9             | 55        | 3.95%   |
| Intel Core 2 Duo        | 34        | 2.44%   |
| Intel Celeron           | 32        | 2.3%    |
| Intel Xeon              | 24        | 1.73%   |
| AMD Ryzen 3             | 19        | 1.37%   |
| Intel Core i9           | 15        | 1.08%   |
| Intel Pentium           | 14        | 1.01%   |
| AMD FX                  | 14        | 1.01%   |
| AMD A8                  | 11        | 0.79%   |
| AMD A10                 | 10        | 0.72%   |
| AMD A6                  | 9         | 0.65%   |
| AMD Ryzen 7 PRO         | 8         | 0.58%   |
| Intel Pentium Gold      | 6         | 0.43%   |
| Intel Core 2 Quad       | 6         | 0.43%   |
| Intel Pentium Dual-Core | 5         | 0.36%   |
| AMD Ryzen Threadripper  | 5         | 0.36%   |
| AMD Ryzen 5 PRO         | 5         | 0.36%   |
| AMD A4                  | 5         | 0.36%   |
| AMD Athlon              | 4         | 0.29%   |
| Intel Atom              | 3         | 0.22%   |
| AMD Phenom              | 3         | 0.22%   |
| Intel Pentium Silver    | 2         | 0.14%   |
| Intel Pentium Dual      | 2         | 0.14%   |
| Intel Pentium D         | 2         | 0.14%   |
| Intel Core m5           | 2         | 0.14%   |
| Intel Core 2            | 2         | 0.14%   |
| AMD Phenom II X6        | 2         | 0.14%   |
| AMD Phenom II X4        | 2         | 0.14%   |
| AMD Athlon II X4        | 2         | 0.14%   |
| AMD Athlon II X2        | 2         | 0.14%   |
| Intel Genuine           | 1         | 0.07%   |
| Intel Core m3           | 1         | 0.07%   |
| AMD Turion II           | 1         | 0.07%   |
| AMD Turion 64 X2 Mobile | 1         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 477       | 34.29%  |
| 2       | 389       | 27.97%  |
| 8       | 210       | 15.1%   |
| 6       | 204       | 14.67%  |
| 12      | 36        | 2.59%   |
| 16      | 24        | 1.73%   |
| 14      | 20        | 1.44%   |
| 10      | 10        | 0.72%   |
| 3       | 7         | 0.5%    |
| 1       | 7         | 0.5%    |
| 24      | 3         | 0.22%   |
| 32      | 2         | 0.14%   |
| 18      | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1385      | 99.64%  |
| 2       | 4         | 0.29%   |
| Unknown | 1         | 0.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1142      | 82.16%  |
| 1       | 247       | 17.77%  |
| Unknown | 1         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1389      | 99.93%  |
| 64-bit         | 1         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1042      | 74.22%  |
| 0x806c1    | 29        | 2.07%   |
| 0x806ec    | 19        | 1.35%   |
| 0x0a50000c | 19        | 1.35%   |
| 0x806d1    | 18        | 1.28%   |
| 0x906a3    | 15        | 1.07%   |
| 0x306a9    | 15        | 1.07%   |
| 0x806ea    | 13        | 0.93%   |
| 0x906ea    | 12        | 0.85%   |
| 0x08701021 | 12        | 0.85%   |
| 0xa0652    | 11        | 0.78%   |
| 0x906e9    | 10        | 0.71%   |
| 0x206a7    | 9         | 0.64%   |
| 0x506e3    | 8         | 0.57%   |
| 0x406e3    | 8         | 0.57%   |
| 0x40651    | 8         | 0.57%   |
| 0x0a404101 | 8         | 0.57%   |
| 0x08608103 | 8         | 0.57%   |
| 0x08600106 | 8         | 0.57%   |
| 0x08108109 | 8         | 0.57%   |
| 0x806e9    | 7         | 0.5%    |
| 0x706e5    | 7         | 0.5%    |
| 0x306c3    | 7         | 0.5%    |
| 0x0a201016 | 7         | 0.5%    |
| 0x0800820d | 7         | 0.5%    |
| 0x08600104 | 6         | 0.43%   |
| 0x906ec    | 5         | 0.36%   |
| 0x706a8    | 5         | 0.36%   |
| 0x306d4    | 5         | 0.36%   |
| 0x806eb    | 4         | 0.28%   |
| 0x08701013 | 4         | 0.28%   |
| 0x906ed    | 3         | 0.21%   |
| 0x90672    | 3         | 0.21%   |
| 0x1067a    | 3         | 0.21%   |
| 0x08600103 | 3         | 0.21%   |
| 0x0810100b | 3         | 0.21%   |
| 0x08001138 | 3         | 0.21%   |
| 0x06003106 | 3         | 0.21%   |
| 0xa0671    | 2         | 0.14%   |
| 0xa0660    | 2         | 0.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 225       | 16.16%  |
| Zen 3            | 131       | 9.41%   |
| Haswell          | 123       | 8.84%   |
| Unknown          | 103       | 7.4%    |
| Zen 2            | 97        | 6.97%   |
| IvyBridge        | 84        | 6.03%   |
| Skylake          | 73        | 5.24%   |
| Zen+             | 66        | 4.74%   |
| SandyBridge      | 65        | 4.67%   |
| TigerLake        | 63        | 4.53%   |
| CometLake        | 45        | 3.23%   |
| Penryn           | 43        | 3.09%   |
| Broadwell        | 39        | 2.8%    |
| IceLake          | 36        | 2.59%   |
| Zen              | 26        | 1.87%   |
| Westmere         | 24        | 1.72%   |
| Piledriver       | 23        | 1.65%   |
| Alderlake Hybrid | 18        | 1.29%   |
| Silvermont       | 16        | 1.15%   |
| Nehalem          | 14        | 1.01%   |
| K10              | 14        | 1.01%   |
| Excavator        | 14        | 1.01%   |
| Goldmont plus    | 12        | 0.86%   |
| Puma             | 8         | 0.57%   |
| Steamroller      | 7         | 0.5%    |
| Core             | 7         | 0.5%    |
| K10 Llano        | 5         | 0.36%   |
| K8 Hammer        | 3         | 0.22%   |
| Goldmont         | 3         | 0.22%   |
| NetBurst         | 2         | 0.14%   |
| Tremont          | 1         | 0.07%   |
| Jaguar           | 1         | 0.07%   |
| Bobcat           | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 714       | 42.05%  |
| Nvidia                     | 558       | 32.86%  |
| AMD                        | 423       | 24.91%  |
| Matrox Electronics Systems | 3         | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 58        | 3.34%   |
| AMD Cezanne                                                                 | 50        | 2.88%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 49        | 2.83%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 47        | 2.71%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 45        | 2.6%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 42        | 2.42%   |
| Intel UHD Graphics 620                                                      | 34        | 1.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 34        | 1.96%   |
| AMD Renoir                                                                  | 34        | 1.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 29        | 1.67%   |
| Intel HD Graphics 620                                                       | 29        | 1.67%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 28        | 1.61%   |
| AMD Lucienne                                                                | 28        | 1.61%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 27        | 1.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 26        | 1.5%    |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 26        | 1.5%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 23        | 1.33%   |
| Intel HD Graphics 5500                                                      | 23        | 1.33%   |
| Intel HD Graphics 630                                                       | 22        | 1.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 22        | 1.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 22        | 1.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 22        | 1.27%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 21        | 1.21%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 17        | 0.98%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 16        | 0.92%   |
| Intel HD Graphics 530                                                       | 16        | 0.92%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 16        | 0.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 15        | 0.87%   |
| AMD Rembrandt [Radeon 680M]                                                 | 15        | 0.87%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 15        | 0.87%   |
| Intel Core Processor Integrated Graphics Controller                         | 14        | 0.81%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 14        | 0.81%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 13        | 0.75%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 12        | 0.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 12        | 0.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 12        | 0.69%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 12        | 0.69%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 11        | 0.63%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 11        | 0.63%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 10        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 470       | 33.55%  |
| 1 x AMD              | 318       | 22.7%   |
| 1 x Nvidia           | 289       | 20.63%  |
| Intel + Nvidia       | 204       | 14.56%  |
| AMD + Nvidia         | 56        | 4%      |
| Intel + AMD          | 25        | 1.78%   |
| 2 x AMD              | 24        | 1.71%   |
| 2 x Nvidia           | 8         | 0.57%   |
| 1 x Matrox           | 3         | 0.21%   |
| Other                | 2         | 0.14%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.07%   |
| AMD + 2 x Nvidia     | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 905       | 64.6%   |
| Proprietary | 462       | 32.98%  |
| Unknown     | 34        | 2.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1091      | 77.65%  |
| 7.01-8.0   | 70        | 4.98%   |
| 1.01-2.0   | 56        | 3.99%   |
| 3.01-4.0   | 51        | 3.63%   |
| 5.01-6.0   | 44        | 3.13%   |
| 0.01-0.5   | 37        | 2.63%   |
| 8.01-16.0  | 33        | 2.35%   |
| 2.01-3.0   | 10        | 0.71%   |
| 0.51-1.0   | 10        | 0.71%   |
| 16.01-24.0 | 2         | 0.14%   |
| 32.01-64.0 | 1         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 206       | 12.79%  |
| Samsung Electronics     | 180       | 11.17%  |
| BOE                     | 150       | 9.31%   |
| LG Display              | 143       | 8.88%   |
| Chimei Innolux          | 142       | 8.81%   |
| Goldstar                | 107       | 6.64%   |
| Dell                    | 103       | 6.39%   |
| Apple                   | 56        | 3.48%   |
| Hewlett-Packard         | 49        | 3.04%   |
| Acer                    | 44        | 2.73%   |
| AOC                     | 40        | 2.48%   |
| Sharp                   | 37        | 2.3%    |
| Ancor Communications    | 35        | 2.17%   |
| ASUSTek Computer        | 34        | 2.11%   |
| BenQ                    | 28        | 1.74%   |
| Lenovo                  | 26        | 1.61%   |
| PANDA                   | 25        | 1.55%   |
| Philips                 | 14        | 0.87%   |
| MSI                     | 12        | 0.74%   |
| InfoVision              | 11        | 0.68%   |
| Iiyama                  | 10        | 0.62%   |
| CSO                     | 10        | 0.62%   |
| ViewSonic               | 9         | 0.56%   |
| Sony                    | 7         | 0.43%   |
| Sceptre Tech            | 7         | 0.43%   |
| Chi Mei Optoelectronics | 7         | 0.43%   |
| NEC Computers           | 6         | 0.37%   |
| Gigabyte Technology     | 6         | 0.37%   |
| Vizio                   | 5         | 0.31%   |
| Unknown                 | 5         | 0.31%   |
| TMX                     | 5         | 0.31%   |
| Panasonic               | 5         | 0.31%   |
| Vestel Elektronik       | 4         | 0.25%   |
| Viotek                  | 3         | 0.19%   |
| Toshiba                 | 3         | 0.19%   |
| LG Electronics          | 3         | 0.19%   |
| Eizo                    | 3         | 0.19%   |
| Valve                   | 2         | 0.12%   |
| TCL                     | 2         | 0.12%   |
| ONN                     | 2         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch       | 10        | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 9         | 0.54%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 9         | 0.54%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch          | 9         | 0.54%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 8         | 0.48%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 7         | 0.42%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 7         | 0.42%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch           | 7         | 0.42%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                   | 7         | 0.42%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch               | 6         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 6         | 0.36%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch         | 6         | 0.36%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 5         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 5         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch        | 5         | 0.3%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch       | 5         | 0.3%    |
| BOE LCD Monitor BOE08DF 1920x1080 344x194mm 15.5-inch                  | 5         | 0.3%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                  | 5         | 0.3%    |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch          | 5         | 0.3%    |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch         | 5         | 0.3%    |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch       | 5         | 0.3%    |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 4         | 0.24%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 344x194mm 15.5-inch   | 4         | 0.24%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch  | 4         | 0.24%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch    | 4         | 0.24%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                | 4         | 0.24%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch           | 4         | 0.24%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch            | 4         | 0.24%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 4         | 0.24%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 4         | 0.24%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 4         | 0.24%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 4         | 0.24%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                 | 4         | 0.24%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 4         | 0.24%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                      | 4         | 0.24%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                      | 4         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch       | 4         | 0.24%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch        | 4         | 0.24%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch        | 4         | 0.24%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch       | 4         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 743       | 48.95%  |
| 1366x768 (WXGA)    | 218       | 14.36%  |
| 3840x2160 (4K)     | 122       | 8.04%   |
| 2560x1440 (QHD)    | 92        | 6.06%   |
| 1920x1200 (WUXGA)  | 46        | 3.03%   |
| 1600x900 (HD+)     | 46        | 3.03%   |
| 3440x1440          | 36        | 2.37%   |
| 2560x1080          | 28        | 1.84%   |
| 2560x1600          | 25        | 1.65%   |
| 1440x900 (WXGA+)   | 23        | 1.52%   |
| 1280x1024 (SXGA)   | 19        | 1.25%   |
| 1680x1050 (WSXGA+) | 18        | 1.19%   |
| 1280x800 (WXGA)    | 15        | 0.99%   |
| 2880x1800          | 14        | 0.92%   |
| 3840x1080          | 8         | 0.53%   |
| 1920x540           | 7         | 0.46%   |
| 1360x768           | 6         | 0.4%    |
| 2256x1504          | 5         | 0.33%   |
| 2160x1440          | 5         | 0.33%   |
| 3840x2400          | 4         | 0.26%   |
| 3456x2160          | 4         | 0.26%   |
| 3000x2000          | 4         | 0.26%   |
| Unknown            | 4         | 0.26%   |
| 3840x1600          | 3         | 0.2%    |
| 1024x768 (XGA)     | 3         | 0.2%    |
| 3840x1100          | 2         | 0.13%   |
| 3200x2000          | 2         | 0.13%   |
| 2736x1824          | 2         | 0.13%   |
| 1920x1280          | 2         | 0.13%   |
| 1280x720 (HD)      | 2         | 0.13%   |
| 800x1280           | 1         | 0.07%   |
| 3840x1200          | 1         | 0.07%   |
| 3280x1080          | 1         | 0.07%   |
| 3200x1800 (QHD+)   | 1         | 0.07%   |
| 3072x1920          | 1         | 0.07%   |
| 3040x900           | 1         | 0.07%   |
| 2880x1600          | 1         | 0.07%   |
| 1920x515           | 1         | 0.07%   |
| 1600x1200          | 1         | 0.07%   |
| 1280x1080          | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 417       | 26.01%  |
| 13      | 190       | 11.85%  |
| 27      | 127       | 7.92%   |
| 24      | 127       | 7.92%   |
| 14      | 117       | 7.3%    |
| 23      | 95        | 5.93%   |
| 17      | 81        | 5.05%   |
| 21      | 69        | 4.3%    |
| 31      | 63        | 3.93%   |
| 34      | 57        | 3.56%   |
| Unknown | 27        | 1.68%   |
| 12      | 26        | 1.62%   |
| 32      | 20        | 1.25%   |
| 16      | 19        | 1.19%   |
| 19      | 18        | 1.12%   |
| 18      | 18        | 1.12%   |
| 22      | 16        | 1%      |
| 84      | 12        | 0.75%   |
| 72      | 11        | 0.69%   |
| 20      | 10        | 0.62%   |
| 11      | 10        | 0.62%   |
| 48      | 9         | 0.56%   |
| 28      | 7         | 0.44%   |
| 25      | 7         | 0.44%   |
| 54      | 6         | 0.37%   |
| 37      | 5         | 0.31%   |
| 35      | 5         | 0.31%   |
| 26      | 5         | 0.31%   |
| 49      | 3         | 0.19%   |
| 47      | 3         | 0.19%   |
| 46      | 3         | 0.19%   |
| 65      | 2         | 0.12%   |
| 52      | 2         | 0.12%   |
| 44      | 2         | 0.12%   |
| 40      | 2         | 0.12%   |
| 29      | 2         | 0.12%   |
| 89      | 1         | 0.06%   |
| 80      | 1         | 0.06%   |
| 69      | 1         | 0.06%   |
| 61      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 648       | 41.17%  |
| 501-600     | 319       | 20.27%  |
| 201-300     | 132       | 8.39%   |
| 401-500     | 119       | 7.56%   |
| 601-700     | 92        | 5.84%   |
| 351-400     | 87        | 5.53%   |
| 701-800     | 77        | 4.89%   |
| 1001-1500   | 31        | 1.97%   |
| Unknown     | 27        | 1.72%   |
| 1501-2000   | 25        | 1.59%   |
| 801-900     | 14        | 0.89%   |
| 901-1000    | 3         | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1130      | 78.97%  |
| 16/10   | 161       | 11.25%  |
| 21/9    | 69        | 4.82%   |
| 5/4     | 19        | 1.33%   |
| 3/2     | 17        | 1.19%   |
| Unknown | 14        | 0.98%   |
| 32/9    | 10        | 0.7%    |
| 4/3     | 5         | 0.35%   |
| 3.40    | 2         | 0.14%   |
| 6/5     | 1         | 0.07%   |
| 3.73    | 1         | 0.07%   |
| 3.20    | 1         | 0.07%   |
| 0.62    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 416       | 26.33%  |
| 81-90          | 239       | 15.13%  |
| 201-250        | 237       | 15%     |
| 351-500        | 148       | 9.37%   |
| 301-350        | 132       | 8.35%   |
| 71-80          | 68        | 4.3%    |
| 121-130        | 68        | 4.3%    |
| 251-300        | 48        | 3.04%   |
| 151-200        | 47        | 2.97%   |
| More than 1000 | 40        | 2.53%   |
| 141-150        | 27        | 1.71%   |
| Unknown        | 27        | 1.71%   |
| 501-1000       | 26        | 1.65%   |
| 61-70          | 23        | 1.46%   |
| 111-120        | 17        | 1.08%   |
| 51-60          | 12        | 0.76%   |
| 91-100         | 3         | 0.19%   |
| 131-140        | 2         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 506       | 33.07%  |
| 51-100        | 440       | 28.76%  |
| 101-120       | 357       | 23.33%  |
| 161-240       | 118       | 7.71%   |
| More than 240 | 47        | 3.07%   |
| 1-50          | 35        | 2.29%   |
| Unknown       | 27        | 1.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1063      | 75.55%  |
| 2     | 258       | 18.34%  |
| 0     | 45        | 3.2%    |
| 3     | 37        | 2.63%   |
| 4     | 3         | 0.21%   |
| 6     | 1         | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 750       | 34.93%  |
| Intel                             | 739       | 34.42%  |
| Qualcomm Atheros                  | 221       | 10.29%  |
| Broadcom                          | 114       | 5.31%   |
| MediaTek                          | 56        | 2.61%   |
| Broadcom Limited                  | 38        | 1.77%   |
| TP-Link                           | 22        | 1.02%   |
| Nvidia                            | 20        | 0.93%   |
| Marvell Technology Group          | 17        | 0.79%   |
| Samsung Electronics               | 14        | 0.65%   |
| Ralink Technology                 | 12        | 0.56%   |
| DisplayLink                       | 12        | 0.56%   |
| Ralink                            | 10        | 0.47%   |
| NetGear                           | 10        | 0.47%   |
| ASIX Electronics                  | 10        | 0.47%   |
| Aquantia                          | 8         | 0.37%   |
| Xiaomi                            | 7         | 0.33%   |
| Dell                              | 7         | 0.33%   |
| Microsoft                         | 6         | 0.28%   |
| InterBiometrics                   | 5         | 0.23%   |
| ASUSTek Computer                  | 5         | 0.23%   |
| Sierra Wireless                   | 4         | 0.19%   |
| Qualcomm Atheros Communications   | 4         | 0.19%   |
| Qualcomm                          | 4         | 0.19%   |
| Lenovo                            | 4         | 0.19%   |
| Huawei Technologies               | 4         | 0.19%   |
| D-Link                            | 4         | 0.19%   |
| OPPO Electronics                  | 3         | 0.14%   |
| JMicron Technology                | 3         | 0.14%   |
| Hewlett-Packard                   | 3         | 0.14%   |
| Google                            | 3         | 0.14%   |
| OnePlus                           | 2         | 0.09%   |
| Mellanox Technologies             | 2         | 0.09%   |
| Ericsson Business Mobile Networks | 2         | 0.09%   |
| D-Link System                     | 2         | 0.09%   |
| Apple                             | 2         | 0.09%   |
| U-Blox                            | 1         | 0.05%   |
| STMicroelectronics                | 1         | 0.05%   |
| Sitecom Europe                    | 1         | 0.05%   |
| SIEMENS                           | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 488       | 19.4%   |
| Intel Wi-Fi 6 AX200                                               | 119       | 4.73%   |
| Realtek RTL8125 2.5GbE Controller                                 | 69        | 2.74%   |
| Intel I211 Gigabit Network Connection                             | 67        | 2.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 57        | 2.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 52        | 2.07%   |
| Intel Wireless 8265 / 8275                                        | 45        | 1.79%   |
| Intel Wi-Fi 6 AX201                                               | 45        | 1.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 43        | 1.71%   |
| Intel Ethernet Controller I225-V                                  | 41        | 1.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 36        | 1.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 34        | 1.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 33        | 1.31%   |
| Intel Wireless 7265                                               | 31        | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 31        | 1.23%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 30        | 1.19%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 29        | 1.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 28        | 1.11%   |
| Intel Wireless 7260                                               | 27        | 1.07%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 27        | 1.07%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 27        | 1.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 26        | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 26        | 1.03%   |
| Intel Wireless 8260                                               | 24        | 0.95%   |
| Intel Ethernet Connection I217-LM                                 | 23        | 0.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 23        | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 22        | 0.87%   |
| Intel Wireless-AC 9260                                            | 22        | 0.87%   |
| Intel Ethernet Connection (2) I219-V                              | 20        | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 20        | 0.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 20        | 0.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 18        | 0.72%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 18        | 0.72%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 16        | 0.64%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 15        | 0.6%    |
| Broadcom BCM43142 802.11b/g/n                                     | 15        | 0.6%    |
| Realtek 802.11ac NIC                                              | 14        | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 14        | 0.56%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 14        | 0.56%   |
| Nvidia MCP79 Ethernet                                             | 12        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 605       | 48.87%  |
| Realtek Semiconductor                 | 182       | 14.7%   |
| Qualcomm Atheros                      | 174       | 14.05%  |
| Broadcom                              | 88        | 7.11%   |
| MediaTek                              | 55        | 4.44%   |
| Broadcom Limited                      | 33        | 2.67%   |
| TP-Link                               | 19        | 1.53%   |
| Ralink Technology                     | 12        | 0.97%   |
| Ralink                                | 10        | 0.81%   |
| NetGear                               | 10        | 0.81%   |
| Dell                                  | 7         | 0.57%   |
| Microsoft                             | 6         | 0.48%   |
| Marvell Technology Group              | 6         | 0.48%   |
| Sierra Wireless                       | 4         | 0.32%   |
| Qualcomm Atheros Communications       | 4         | 0.32%   |
| ASUSTek Computer                      | 4         | 0.32%   |
| Qualcomm                              | 3         | 0.24%   |
| D-Link                                | 3         | 0.24%   |
| D-Link System                         | 2         | 0.16%   |
| Sitecom Europe                        | 1         | 0.08%   |
| Micro Star International              | 1         | 0.08%   |
| IMC Networks                          | 1         | 0.08%   |
| Hewlett-Packard                       | 1         | 0.08%   |
| Gemtek                                | 1         | 0.08%   |
| FIBOCOM                               | 1         | 0.08%   |
| Belkin Components                     | 1         | 0.08%   |
| AVM                                   | 1         | 0.08%   |
| Arduino SA                            | 1         | 0.08%   |
| Accton Technology                     | 1         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 119       | 9.54%   |
| Intel Wireless 8265 / 8275                                     | 45        | 3.61%   |
| Intel Wi-Fi 6 AX201                                            | 45        | 3.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 36        | 2.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 34        | 2.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 33        | 2.65%   |
| Intel Wireless 7265                                            | 31        | 2.49%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 31        | 2.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 30        | 2.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 29        | 2.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 28        | 2.25%   |
| Intel Wireless 7260                                            | 27        | 2.17%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 27        | 2.17%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 27        | 2.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 26        | 2.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 26        | 2.09%   |
| Intel Wireless 8260                                            | 24        | 1.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 23        | 1.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 22        | 1.76%   |
| Intel Wireless-AC 9260                                         | 22        | 1.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 20        | 1.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 20        | 1.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 18        | 1.44%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 18        | 1.44%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 16        | 1.28%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 15        | 1.2%    |
| Broadcom BCM43142 802.11b/g/n                                  | 15        | 1.2%    |
| Realtek 802.11ac NIC                                           | 14        | 1.12%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 14        | 1.12%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 11        | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 11        | 0.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 11        | 0.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 11        | 0.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10        | 0.8%    |
| MediaTek WLAN controller                                       | 10        | 0.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 10        | 0.8%    |
| Intel Centrino Advanced-N 6235                                 | 10        | 0.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 10        | 0.8%    |
| Intel Alder Lake-S PCH CNVi WiFi                               | 9         | 0.72%   |
| Realtek Realtek Network controller                             | 8         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 663       | 54.03%  |
| Intel                    | 336       | 27.38%  |
| Qualcomm Atheros         | 63        | 5.13%   |
| Broadcom                 | 48        | 3.91%   |
| Nvidia                   | 20        | 1.63%   |
| Samsung Electronics      | 14        | 1.14%   |
| DisplayLink              | 12        | 0.98%   |
| Marvell Technology Group | 11        | 0.9%    |
| ASIX Electronics         | 10        | 0.81%   |
| Aquantia                 | 8         | 0.65%   |
| Xiaomi                   | 7         | 0.57%   |
| Broadcom Limited         | 5         | 0.41%   |
| Lenovo                   | 4         | 0.33%   |
| TP-Link                  | 3         | 0.24%   |
| OPPO Electronics         | 3         | 0.24%   |
| JMicron Technology       | 3         | 0.24%   |
| Huawei Technologies      | 3         | 0.24%   |
| Google                   | 3         | 0.24%   |
| OnePlus                  | 2         | 0.16%   |
| Mellanox Technologies    | 2         | 0.16%   |
| Apple                    | 2         | 0.16%   |
| Qualcomm                 | 1         | 0.08%   |
| Motorola PCS             | 1         | 0.08%   |
| Hewlett-Packard          | 1         | 0.08%   |
| D-Link                   | 1         | 0.08%   |
| ASUSTek Computer         | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 488       | 39.04%  |
| Realtek RTL8125 2.5GbE Controller                                 | 69        | 5.52%   |
| Intel I211 Gigabit Network Connection                             | 67        | 5.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 57        | 4.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 52        | 4.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 43        | 3.44%   |
| Intel Ethernet Controller I225-V                                  | 41        | 3.28%   |
| Intel Ethernet Connection I217-LM                                 | 23        | 1.84%   |
| Intel Ethernet Connection (2) I219-V                              | 20        | 1.6%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 14        | 1.12%   |
| Nvidia MCP79 Ethernet                                             | 12        | 0.96%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 10        | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 10        | 0.8%    |
| Intel Ethernet Connection (7) I219-V                              | 10        | 0.8%    |
| Intel Ethernet Connection I219-LM                                 | 9         | 0.72%   |
| Intel Ethernet Connection (4) I219-LM                             | 9         | 0.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 9         | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 8         | 0.64%   |
| Intel Ethernet Connection (2) I218-V                              | 8         | 0.64%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 8         | 0.64%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 0.64%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 7         | 0.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.56%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 7         | 0.56%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 7         | 0.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 6         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.48%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5         | 0.4%    |
| Intel Ethernet Connection (6) I219-V                              | 5         | 0.4%    |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.4%    |
| Intel Ethernet Connection (13) I219-V                             | 5         | 0.4%    |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.4%    |
| DisplayLink Dell Universal Dock D6000                             | 5         | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 0.32%   |
| Nvidia MCP61 Ethernet                                             | 4         | 0.32%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 4         | 0.32%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1175      | 50.34%  |
| Ethernet | 1140      | 48.84%  |
| Modem    | 14        | 0.6%    |
| Unknown  | 5         | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 893       | 61.29%  |
| Ethernet | 564       | 38.71%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 778       | 55.93%  |
| 1     | 551       | 39.61%  |
| 3     | 43        | 3.09%   |
| 0     | 16        | 1.15%   |
| 4     | 3         | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 985       | 70.41%  |
| Yes  | 414       | 29.59%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 547       | 53.57%  |
| Realtek Semiconductor           | 76        | 7.44%   |
| Qualcomm Atheros Communications | 74        | 7.25%   |
| Apple                           | 68        | 6.66%   |
| IMC Networks                    | 52        | 5.09%   |
| Cambridge Silicon Radio         | 48        | 4.7%    |
| Lite-On Technology              | 31        | 3.04%   |
| Foxconn / Hon Hai               | 31        | 3.04%   |
| Broadcom                        | 30        | 2.94%   |
| ASUSTek Computer                | 14        | 1.37%   |
| Dell                            | 7         | 0.69%   |
| Marvell Semiconductor           | 6         | 0.59%   |
| Toshiba                         | 5         | 0.49%   |
| Realtek                         | 5         | 0.49%   |
| MediaTek                        | 5         | 0.49%   |
| TP-Link                         | 3         | 0.29%   |
| Hewlett-Packard                 | 3         | 0.29%   |
| Taiyo Yuden                     | 2         | 0.2%    |
| Ralink                          | 2         | 0.2%    |
| Opticis                         | 2         | 0.2%    |
| Foxconn International           | 2         | 0.2%    |
| USI                             | 1         | 0.1%    |
| Ralink Technology               | 1         | 0.1%    |
| Micro Star International        | 1         | 0.1%    |
| HTC (High Tech Computer)        | 1         | 0.1%    |
| Fujitsu                         | 1         | 0.1%    |
| Edimax Technology               | 1         | 0.1%    |
| Dynex                           | 1         | 0.1%    |
| Belkin Components               | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 137       | 13.42%  |
| Intel AX201 Bluetooth                               | 117       | 11.46%  |
| Intel AX200 Bluetooth                               | 112       | 10.97%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 73        | 7.15%   |
| Realtek Bluetooth Radio                             | 54        | 5.29%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 48        | 4.7%    |
| Qualcomm Atheros  Bluetooth Device                  | 39        | 3.82%   |
| Apple Bluetooth USB Host Controller                 | 32        | 3.13%   |
| Intel AX210 Bluetooth                               | 26        | 2.55%   |
| Apple Bluetooth Host Controller                     | 26        | 2.55%   |
| Intel Bluetooth Device                              | 24        | 2.35%   |
| IMC Networks Wireless_Device                        | 24        | 2.35%   |
| Intel Wireless-AC 3168 Bluetooth                    | 22        | 2.15%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 20        | 1.96%   |
| Realtek  Bluetooth 4.2 Adapter                      | 17        | 1.67%   |
| Foxconn / Hon Hai Wireless_Device                   | 14        | 1.37%   |
| IMC Networks Bluetooth Device                       | 13        | 1.27%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 12        | 1.18%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 12        | 1.18%   |
| Foxconn / Hon Hai Bluetooth Device                  | 11        | 1.08%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 8         | 0.78%   |
| IMC Networks Bluetooth Radio                        | 7         | 0.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 0.59%   |
| Lite-On Wireless_Device                             | 6         | 0.59%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.59%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 6         | 0.59%   |
| Realtek Bluetooth Radio                             | 5         | 0.49%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 0.49%   |
| MediaTek Wireless_Device                            | 5         | 0.49%   |
| Marvell Bluetooth and Wireless LAN Composite        | 5         | 0.49%   |
| Lite-On Bluetooth Device                            | 5         | 0.49%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 0.49%   |
| ASUS ASUS USB-BT500                                 | 5         | 0.49%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 5         | 0.49%   |
| Apple Bluetooth HCI                                 | 5         | 0.49%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 0.39%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 0.39%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 0.39%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 4         | 0.39%   |
| ASUS Bluetooth Radio                                | 4         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 912       | 42.52%  |
| AMD                                  | 502       | 23.4%   |
| Nvidia                               | 440       | 20.51%  |
| C-Media Electronics                  | 34        | 1.59%   |
| Logitech                             | 25        | 1.17%   |
| Kingston Technology                  | 17        | 0.79%   |
| JMTek                                | 13        | 0.61%   |
| Razer USA                            | 12        | 0.56%   |
| GN Netcom                            | 11        | 0.51%   |
| Focusrite-Novation                   | 11        | 0.51%   |
| Creative Labs                        | 10        | 0.47%   |
| Texas Instruments                    | 9         | 0.42%   |
| ASUSTek Computer                     | 8         | 0.37%   |
| SteelSeries ApS                      | 7         | 0.33%   |
| Lenovo                               | 7         | 0.33%   |
| Generalplus Technology               | 7         | 0.33%   |
| Corsair                              | 6         | 0.28%   |
| Blue Microphones                     | 6         | 0.28%   |
| Sony                                 | 5         | 0.23%   |
| Micro Star International             | 5         | 0.23%   |
| Creative Technology                  | 5         | 0.23%   |
| Realtek Semiconductor                | 4         | 0.19%   |
| Hewlett-Packard                      | 4         | 0.19%   |
| Apple                                | 4         | 0.19%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.14%   |
| Sennheiser Communications            | 3         | 0.14%   |
| Plantronics                          | 3         | 0.14%   |
| Astro Gaming                         | 3         | 0.14%   |
| Antlion Audio                        | 3         | 0.14%   |
| Valve Software                       | 2         | 0.09%   |
| Turtle Beach                         | 2         | 0.09%   |
| Trust                                | 2         | 0.09%   |
| Tenx Technology                      | 2         | 0.09%   |
| Samsung Electronics                  | 2         | 0.09%   |
| Samson Technologies                  | 2         | 0.09%   |
| Mackie Designs                       | 2         | 0.09%   |
| M-Audio                              | 2         | 0.09%   |
| Jieli Technology                     | 2         | 0.09%   |
| BEHRINGER International              | 2         | 0.09%   |
| Yamaha                               | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 201       | 7.77%   |
| AMD Starship/Matisse HD Audio Controller                                   | 121       | 4.68%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 110       | 4.25%   |
| Intel Sunrise Point-LP HD Audio                                            | 97        | 3.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 83        | 3.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 63        | 2.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 60        | 2.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 59        | 2.28%   |
| Intel Cannon Lake PCH cAVS                                                 | 58        | 2.24%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 55        | 2.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 50        | 1.93%   |
| Intel Haswell-ULT HD Audio Controller                                      | 45        | 1.74%   |
| Intel 8 Series HD Audio Controller                                         | 44        | 1.7%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 41        | 1.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 40        | 1.55%   |
| Nvidia GA106 High Definition Audio Controller                              | 37        | 1.43%   |
| Nvidia GA104 High Definition Audio Controller                              | 37        | 1.43%   |
| Nvidia GP107GL High Definition Audio Controller                            | 36        | 1.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 36        | 1.39%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 36        | 1.39%   |
| Intel Comet Lake PCH cAVS                                                  | 35        | 1.35%   |
| Intel Broadwell-U Audio Controller                                         | 35        | 1.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 34        | 1.31%   |
| Nvidia TU116 High Definition Audio Controller                              | 32        | 1.24%   |
| Nvidia TU106 High Definition Audio Controller                              | 32        | 1.24%   |
| Nvidia GP106 High Definition Audio Controller                              | 32        | 1.24%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 32        | 1.24%   |
| AMD FCH Azalia Controller                                                  | 31        | 1.2%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 29        | 1.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 27        | 1.04%   |
| Nvidia GP104 High Definition Audio Controller                              | 27        | 1.04%   |
| Nvidia TU104 HD Audio Controller                                           | 26        | 1%      |
| Intel Comet Lake PCH-LP cAVS                                               | 26        | 1%      |
| Intel CM238 HD Audio Controller                                            | 26        | 1%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 26        | 1%      |
| Intel 200 Series PCH HD Audio                                              | 24        | 0.93%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 22        | 0.85%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 21        | 0.81%   |
| Nvidia GA102 High Definition Audio Controller                              | 17        | 0.66%   |
| Nvidia GK107 HDMI Audio Controller                                         | 16        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 116       | 26.67%  |
| SK hynix            | 77        | 17.7%   |
| Micron Technology   | 55        | 12.64%  |
| Corsair             | 36        | 8.28%   |
| Kingston            | 33        | 7.59%   |
| Crucial             | 24        | 5.52%   |
| G.Skill             | 17        | 3.91%   |
| Unknown             | 12        | 2.76%   |
| Team                | 11        | 2.53%   |
| Unknown             | 8         | 1.84%   |
| A-DATA Technology   | 7         | 1.61%   |
| Smart               | 6         | 1.38%   |
| Neo Forza           | 4         | 0.92%   |
| Ramaxel Technology  | 3         | 0.69%   |
| Goldkey             | 3         | 0.69%   |
| Elpida              | 3         | 0.69%   |
| Avant               | 3         | 0.69%   |
| Unknown (ABCD)      | 2         | 0.46%   |
| Teikon              | 2         | 0.46%   |
| PNY                 | 2         | 0.46%   |
| Nanya Technology    | 2         | 0.46%   |
| GSkill              | 2         | 0.46%   |
| Gold Key            | 2         | 0.46%   |
| Unknown (8A02)      | 1         | 0.23%   |
| Timetec             | 1         | 0.23%   |
| Smart Brazil        | 1         | 0.23%   |
| Patriot Memory      | 1         | 0.23%   |
| Apacer              | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 1.74%   |
| Unknown                                                          | 8         | 1.74%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 1.53%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 7         | 1.53%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 1.31%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 1.31%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.09%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 1.09%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 5         | 1.09%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 1.09%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 5         | 1.09%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 5         | 1.09%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 4         | 0.87%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 4         | 0.87%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.87%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s        | 4         | 0.87%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.87%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.87%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.87%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 4         | 0.87%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.87%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 4         | 0.87%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.65%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 0.65%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.65%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 3         | 0.65%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.65%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 3         | 0.65%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 3         | 0.65%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.65%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 3         | 0.65%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 3         | 0.65%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 2         | 0.44%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 2         | 0.44%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.44%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.44%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 2         | 0.44%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.44%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.44%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s | 2         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 258       | 68.8%   |
| DDR3    | 52        | 13.87%  |
| LPDDR4  | 24        | 6.4%    |
| LPDDR3  | 11        | 2.93%   |
| DDR5    | 10        | 2.67%   |
| LPDDR5  | 8         | 2.13%   |
| Unknown | 6         | 1.6%    |
| SDRAM   | 3         | 0.8%    |
| DDR2    | 3         | 0.8%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 237       | 61.88%  |
| DIMM         | 83        | 21.67%  |
| Row Of Chips | 61        | 15.93%  |
| Chip         | 2         | 0.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 185       | 45.91%  |
| 4096  | 91        | 22.58%  |
| 16384 | 78        | 19.35%  |
| 32768 | 29        | 7.2%    |
| 2048  | 20        | 4.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 118       | 29.28%  |
| 2667  | 72        | 17.87%  |
| 1600  | 40        | 9.93%   |
| 2400  | 27        | 6.7%    |
| 3600  | 23        | 5.71%   |
| 2133  | 18        | 4.47%   |
| 4267  | 15        | 3.72%   |
| 4800  | 12        | 2.98%   |
| 6400  | 10        | 2.48%   |
| 1333  | 10        | 2.48%   |
| 3266  | 6         | 1.49%   |
| 8400  | 5         | 1.24%   |
| 3800  | 5         | 1.24%   |
| 3466  | 4         | 0.99%   |
| 3000  | 4         | 0.99%   |
| 3733  | 3         | 0.74%   |
| 2933  | 3         | 0.74%   |
| 1867  | 3         | 0.74%   |
| 1334  | 3         | 0.74%   |
| 800   | 3         | 0.74%   |
| 4266  | 2         | 0.5%    |
| 2666  | 2         | 0.5%    |
| 2048  | 2         | 0.5%    |
| 1067  | 2         | 0.5%    |
| 4199  | 1         | 0.25%   |
| 4000  | 1         | 0.25%   |
| 3866  | 1         | 0.25%   |
| 3666  | 1         | 0.25%   |
| 3400  | 1         | 0.25%   |
| 3100  | 1         | 0.25%   |
| 3067  | 1         | 0.25%   |
| 2800  | 1         | 0.25%   |
| 2733  | 1         | 0.25%   |
| 1866  | 1         | 0.25%   |
| 1200  | 1         | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 6         | 25%     |
| Hewlett-Packard     | 5         | 20.83%  |
| Canon               | 4         | 16.67%  |
| Samsung Electronics | 3         | 12.5%   |
| Seiko Epson         | 2         | 8.33%   |
| QinHeng Electronics | 1         | 4.17%   |
| Prolific Technology | 1         | 4.17%   |
| ICS Advent          | 1         | 4.17%   |
| Dymo-CoStar         | 1         | 4.17%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Brother HL-2130 series                 | 2         | 8%      |
| Seiko Epson WF-4830 Series             | 1         | 4%      |
| Seiko Epson ET-2800 Series             | 1         | 4%      |
| Samsung SCX-3400 Series                | 1         | 4%      |
| Samsung ML-191x/ML-252x Laser Printer  | 1         | 4%      |
| Samsung M2070 Series                   | 1         | 4%      |
| QinHeng CH340S                         | 1         | 4%      |
| Prolific PL2305 Parallel Port          | 1         | 4%      |
| ICS Advent Parallel Adapter            | 1         | 4%      |
| HP PSC-1315/PSC-1317                   | 1         | 4%      |
| HP LaserJet P2035                      | 1         | 4%      |
| HP LaserJet 1010                       | 1         | 4%      |
| HP Ink Tank Wireless 410 series        | 1         | 4%      |
| HP ENVY Pro 6400 series                | 1         | 4%      |
| Dymo-CoStar DYMO LabelWriter 4XL       | 1         | 4%      |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1         | 4%      |
| Canon TR8500 series                    | 1         | 4%      |
| Canon Pro9000II series                 | 1         | 4%      |
| Canon PIXMA MP240                      | 1         | 4%      |
| Canon E400 series                      | 1         | 4%      |
| Brother MFC-L2700DW                    | 1         | 4%      |
| Brother MFC-5440CN                     | 1         | 4%      |
| Brother HL-3140CW series               | 1         | 4%      |
| Brother HL-2270DW Laser Printer        | 1         | 4%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 3         | 75%     |
| Mustek Systems | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 UB | 1         | 25%     |
| Canon CanoScan N650U/N656U         | 1         | 25%     |
| Canon CanoScan LiDE 60             | 1         | 25%     |
| Canon CanoScan LiDE 200            | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 179       | 19.29%  |
| Microdia                               | 91        | 9.81%   |
| Acer                                   | 90        | 9.7%    |
| IMC Networks                           | 85        | 9.16%   |
| Realtek Semiconductor                  | 66        | 7.11%   |
| Logitech                               | 59        | 6.36%   |
| Apple                                  | 50        | 5.39%   |
| Quanta                                 | 49        | 5.28%   |
| Sunplus Innovation Technology          | 48        | 5.17%   |
| Syntek                                 | 22        | 2.37%   |
| Cheng Uei Precision Industry (Foxlink) | 22        | 2.37%   |
| Suyin                                  | 18        | 1.94%   |
| Luxvisions Innotech Limited            | 15        | 1.62%   |
| Lite-On Technology                     | 15        | 1.62%   |
| Microsoft                              | 14        | 1.51%   |
| Samsung Electronics                    | 11        | 1.19%   |
| SunplusIT                              | 8         | 0.86%   |
| Silicon Motion                         | 8         | 0.86%   |
| Razer USA                              | 6         | 0.65%   |
| Z-Star Microelectronics                | 5         | 0.54%   |
| Sonix Technology                       | 5         | 0.54%   |
| MacroSilicon                           | 4         | 0.43%   |
| Jieli Technology                       | 4         | 0.43%   |
| Generalplus Technology                 | 4         | 0.43%   |
| AVerMedia Technologies                 | 3         | 0.32%   |
| ARC International                      | 3         | 0.32%   |
| Alcor Micro                            | 3         | 0.32%   |
| Valve Software                         | 2         | 0.22%   |
| Unknown                                | 2         | 0.22%   |
| Sunplus IT                             | 2         | 0.22%   |
| Ricoh                                  | 2         | 0.22%   |
| Primax Electronics                     | 2         | 0.22%   |
| LG Electronics                         | 2         | 0.22%   |
| KYE Systems (Mouse Systems)            | 2         | 0.22%   |
| Cubeternet                             | 2         | 0.22%   |
| Creative Technology                    | 2         | 0.22%   |
| YGTek                                  | 1         | 0.11%   |
| XHT-210518                             | 1         | 0.11%   |
| WaveRider Communications               | 1         | 0.11%   |
| Trust                                  | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD           | 41        | 4.37%   |
| Chicony Integrated Camera               | 36        | 3.83%   |
| IMC Networks USB2.0 HD UVC WebCam       | 34        | 3.62%   |
| Realtek Integrated_Webcam_HD            | 26        | 2.77%   |
| Syntek Integrated Camera                | 20        | 2.13%   |
| IMC Networks Integrated Camera          | 19        | 2.02%   |
| Chicony HD WebCam                       | 19        | 2.02%   |
| Acer Integrated Camera                  | 18        | 1.92%   |
| Apple Built-in iSight                   | 16        | 1.7%    |
| Logitech Webcam C270                    | 15        | 1.6%    |
| Acer HD Webcam                          | 15        | 1.6%    |
| Acer BisonCam,NB Pro                    | 15        | 1.6%    |
| Chicony USB2.0 Camera                   | 14        | 1.49%   |
| Apple iPhone 5/5C/5S/6/SE               | 13        | 1.38%   |
| Sunplus Integrated_Webcam_HD            | 11        | 1.17%   |
| Samsung Galaxy series, misc. (MTP mode) | 11        | 1.17%   |
| Quanta HP HD Camera                     | 11        | 1.17%   |
| Apple FaceTime HD Camera (Built-in)     | 11        | 1.17%   |
| Quanta HD User Facing                   | 10        | 1.06%   |
| Logitech HD Pro Webcam C920             | 10        | 1.06%   |
| Chicony USB2.0 VGA UVC WebCam           | 9         | 0.96%   |
| Apple FaceTime HD Camera                | 9         | 0.96%   |
| Microdia Integrated Webcam              | 8         | 0.85%   |
| Chicony Integrated Camera (1280x720@30) | 8         | 0.85%   |
| Logitech C922 Pro Stream Webcam         | 7         | 0.75%   |
| Lite-On Integrated Camera               | 7         | 0.75%   |
| Chicony USB 2.0 Camera                  | 7         | 0.75%   |
| Chicony TOSHIBA Web Camera - HD         | 7         | 0.75%   |
| Acer SunplusIT Integrated Camera        | 7         | 0.75%   |
| Quanta HP Wide Vision HD Camera         | 6         | 0.64%   |
| Microdia USB Live camera                | 6         | 0.64%   |
| Microdia USB 2.0 Camera                 | 6         | 0.64%   |
| Chicony HP HD Camera                    | 6         | 0.64%   |
| Chicony HD User Facing                  | 6         | 0.64%   |
| Suyin 1.3M HD WebCam                    | 5         | 0.53%   |
| Sonix USB2.0 HD UVC WebCam              | 5         | 0.53%   |
| Realtek USB2.0 HD UVC WebCam            | 5         | 0.53%   |
| Razer USA Gaming Webcam [Kiyo]          | 5         | 0.53%   |
| Quanta HP TrueVision HD Camera          | 5         | 0.53%   |
| Microdia Integrated_Webcam_FHD          | 5         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 59        | 39.6%   |
| Validity Sensors           | 34        | 22.82%  |
| Shenzhen Goodix Technology | 30        | 20.13%  |
| LighTuning Technology      | 9         | 6.04%   |
| Elan Microelectronics      | 5         | 3.36%   |
| AuthenTec                  | 4         | 2.68%   |
| Upek                       | 3         | 2.01%   |
| HOLTEK                     | 2         | 1.34%   |
| Samsung Electronics        | 1         | 0.67%   |
| Focal-systems.Corp         | 1         | 0.67%   |
| DigitalPersona             | 1         | 0.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 22        | 14.77%  |
| Shenzhen Goodix  FingerPrint Device                                        | 15        | 10.07%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 13        | 8.72%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 6.04%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 4.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 4.7%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 4.03%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 4.03%   |
| LighTuning EgisTec_ES603                                                   | 6         | 4.03%   |
| Synaptics WBDI Device                                                      | 5         | 3.36%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 3.36%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 2.68%   |
| Elan ELAN:ARM-M4                                                           | 4         | 2.68%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.01%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 2.01%   |
| Synaptics  WBDI                                                            | 3         | 2.01%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 2.01%   |
| Validity Sensors VFS491                                                    | 2         | 1.34%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.34%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 1.34%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.34%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.34%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.34%   |
| HOLTEK FocalTech Fingerprint Device                                        | 2         | 1.34%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 1.34%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.67%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.67%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.67%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.67%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.67%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.67%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.67%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.67%   |
| Elan ELAN:Fingerprint                                                      | 1         | 0.67%   |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.67%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.67%   |
| AuthenTec AES2810                                                          | 1         | 0.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 27        | 49.09%  |
| Alcor Micro           | 16        | 29.09%  |
| O2 Micro              | 4         | 7.27%   |
| Upek                  | 2         | 3.64%   |
| Lenovo                | 2         | 3.64%   |
| SCM Microsystems      | 1         | 1.82%   |
| OmniKey               | 1         | 1.82%   |
| Clay Logic            | 1         | 1.82%   |
| Advanced Card Systems | 1         | 1.82%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 16        | 29.09%  |
| Broadcom BCM5880 Secure Applications Processor                               | 8         | 14.55%  |
| Broadcom 5880                                                                | 8         | 14.55%  |
| Broadcom 58200                                                               | 7         | 12.73%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 7.27%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 5.45%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.64%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 3.64%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 1.82%   |
| OmniKey CardMan 4321                                                         | 1         | 1.82%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.82%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.82%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 1.82%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 956       | 68.29%  |
| 1     | 357       | 25.5%   |
| 2     | 72        | 5.14%   |
| 3     | 14        | 1%      |
| 4     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 142       | 26.89%  |
| Net/wireless             | 81        | 15.34%  |
| Multimedia controller    | 81        | 15.34%  |
| Graphics card            | 65        | 12.31%  |
| Chipcard                 | 51        | 9.66%   |
| Bluetooth                | 37        | 7.01%   |
| Camera                   | 15        | 2.84%   |
| Sound                    | 12        | 2.27%   |
| Net/ethernet             | 9         | 1.7%    |
| Unassigned class         | 7         | 1.33%   |
| Communication controller | 7         | 1.33%   |
| Storage                  | 6         | 1.14%   |
| Network                  | 6         | 1.14%   |
| Storage/ide              | 3         | 0.57%   |
| Modem                    | 3         | 0.57%   |
| Card reader              | 2         | 0.38%   |
| Wireless                 | 1         | 0.19%   |

