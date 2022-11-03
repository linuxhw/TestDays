Pop!_OS - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pop!_OS/Desktop/README.md) and [notebooks](/Dist/Pop!_OS/Notebook/README.md).

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

Total: 11233

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
| Acer          | Predator PH317-52           | Notebook    | [379aad9180](https://linux-hardware.org/?probe=379aad9180) | Oct 10, 2022 |
| Gigabyte      | P34V7                       | Notebook    | [c1423fce9e](https://linux-hardware.org/?probe=c1423fce9e) | Oct 10, 2022 |
| System76      | Galago Pro                  | Notebook    | [28e36afa26](https://linux-hardware.org/?probe=28e36afa26) | Oct 10, 2022 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [84fa1dd520](https://linux-hardware.org/?probe=84fa1dd520) | Oct 10, 2022 |
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
| Dell          | G7 7500                     | Notebook    | [e50429ccfa](https://linux-hardware.org/?probe=e50429ccfa) | Oct 08, 2022 |
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
| Dell          | Precision M4800             | Notebook    | [d4142adadc](https://linux-hardware.org/?probe=d4142adadc) | Sep 29, 2022 |
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
| MSI           | GS73 Stealth 8RF            | Notebook    | [37d9172163](https://linux-hardware.org/?probe=37d9172163) | Sep 26, 2022 |
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
| System76      | Oryx Pro                    | Notebook    | [3cf39a6993](https://linux-hardware.org/?probe=3cf39a6993) | Sep 24, 2022 |
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
| ASUSTek       | E402NA                      | Notebook    | [9d97fe89bb](https://linux-hardware.org/?probe=9d97fe89bb) | Sep 16, 2022 |
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
| HP            | Laptop 15s-fq1xxx           | Notebook    | [dc870b4e8a](https://linux-hardware.org/?probe=dc870b4e8a) | Sep 15, 2022 |
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
| Dell          | Precision 3551              | Notebook    | [78f7c77b35](https://linux-hardware.org/?probe=78f7c77b35) | Sep 09, 2022 |
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
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [a2962588fa](https://linux-hardware.org/?probe=a2962588fa) | Sep 04, 2022 |
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
| Dell          | Latitude E6400              | Notebook    | [714643ef93](https://linux-hardware.org/?probe=714643ef93) | Aug 25, 2022 |
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
| System76      | Thelio thelio-r2            | Desktop     | [6eb968883d](https://linux-hardware.org/?probe=6eb968883d) | Aug 22, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [33ff4e4962](https://linux-hardware.org/?probe=33ff4e4962) | Aug 22, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [b41e95cd1b](https://linux-hardware.org/?probe=b41e95cd1b) | Aug 22, 2022 |
| Dell          | 02P9X9 A00                  | Server      | [b7d9a0c4a2](https://linux-hardware.org/?probe=b7d9a0c4a2) | Aug 22, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [8f7d642c46](https://linux-hardware.org/?probe=8f7d642c46) | Aug 22, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [6b5ced2971](https://linux-hardware.org/?probe=6b5ced2971) | Aug 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e8bee7737a](https://linux-hardware.org/?probe=e8bee7737a) | Aug 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b182084c88](https://linux-hardware.org/?probe=b182084c88) | Aug 22, 2022 |
| Unknown       | GSUO H61V10C                | Desktop     | [1e7ccd0999](https://linux-hardware.org/?probe=1e7ccd0999) | Aug 22, 2022 |
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
| MSI           | B360-A PRO                  | Desktop     | [a5505919b5](https://linux-hardware.org/?probe=a5505919b5) | Aug 14, 2022 |
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
| Dell          | G7 7500                     | Notebook    | [981382d336](https://linux-hardware.org/?probe=981382d336) | Aug 03, 2022 |
| Intel         | D955XBK AAC96732-501        | Desktop     | [ed4b3ec577](https://linux-hardware.org/?probe=ed4b3ec577) | Aug 03, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [06da05d12b](https://linux-hardware.org/?probe=06da05d12b) | Aug 03, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [83123dba6b](https://linux-hardware.org/?probe=83123dba6b) | Aug 03, 2022 |
| Dell          | Inspiron N5040              | Notebook    | [2da4d2a843](https://linux-hardware.org/?probe=2da4d2a843) | Aug 03, 2022 |
| Intel         | DP55WB AAE64798-208         | Desktop     | [0c66cac06d](https://linux-hardware.org/?probe=0c66cac06d) | Aug 03, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [3f1ccf427a](https://linux-hardware.org/?probe=3f1ccf427a) | Aug 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [73b2c51a7e](https://linux-hardware.org/?probe=73b2c51a7e) | Aug 02, 2022 |
| Alienware     | x17 R2                      | Notebook    | [48772fabd8](https://linux-hardware.org/?probe=48772fabd8) | Aug 02, 2022 |
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
| Dell          | Precision M6800             | Notebook    | [3584b1693d](https://linux-hardware.org/?probe=3584b1693d) | Jul 31, 2022 |
| Acer          | Swift SF314-51              | Notebook    | [f9a61fd8ad](https://linux-hardware.org/?probe=f9a61fd8ad) | Jul 31, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [36659d2410](https://linux-hardware.org/?probe=36659d2410) | Jul 30, 2022 |
| Toshiba       | Satellite C75D-C            | Notebook    | [f4a9c3bc7f](https://linux-hardware.org/?probe=f4a9c3bc7f) | Jul 30, 2022 |
| Toshiba       | Satellite C75D-C            | Notebook    | [f017593574](https://linux-hardware.org/?probe=f017593574) | Jul 30, 2022 |
| EVGA          | 134-KS-E377                 | Desktop     | [2624cfe274](https://linux-hardware.org/?probe=2624cfe274) | Jul 30, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [cc3deb0a17](https://linux-hardware.org/?probe=cc3deb0a17) | Jul 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ea83758651](https://linux-hardware.org/?probe=ea83758651) | Jul 30, 2022 |
| MSI           | MEG Z690 UNIFY              | Desktop     | [571f500e5e](https://linux-hardware.org/?probe=571f500e5e) | Jul 30, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [74b9e88d97](https://linux-hardware.org/?probe=74b9e88d97) | Jul 30, 2022 |
| Lenovo        | ThinkPad X270 20HMS12K00    | Notebook    | [b3d3ab37ef](https://linux-hardware.org/?probe=b3d3ab37ef) | Jul 30, 2022 |
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
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [adb71c8acc](https://linux-hardware.org/?probe=adb71c8acc) | Jul 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e3dc0a4c49](https://linux-hardware.org/?probe=e3dc0a4c49) | Jul 28, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [d0ff2340b1](https://linux-hardware.org/?probe=d0ff2340b1) | Jul 28, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [830913d1ab](https://linux-hardware.org/?probe=830913d1ab) | Jul 28, 2022 |
| Sony          | VPCEG27FM                   | Notebook    | [b8c840d19a](https://linux-hardware.org/?probe=b8c840d19a) | Jul 28, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [c6643cb779](https://linux-hardware.org/?probe=c6643cb779) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [be9941b639](https://linux-hardware.org/?probe=be9941b639) | Jul 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [36e0686495](https://linux-hardware.org/?probe=36e0686495) | Jul 28, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [c884d7548c](https://linux-hardware.org/?probe=c884d7548c) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [56faf89859](https://linux-hardware.org/?probe=56faf89859) | Jul 28, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [0fe8633425](https://linux-hardware.org/?probe=0fe8633425) | Jul 27, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [36001f3112](https://linux-hardware.org/?probe=36001f3112) | Jul 27, 2022 |
| MSI           | X370 GAMING PLUS            | Desktop     | [a39ccd24ff](https://linux-hardware.org/?probe=a39ccd24ff) | Jul 27, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [b25ca31168](https://linux-hardware.org/?probe=b25ca31168) | Jul 27, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [82192dcb1d](https://linux-hardware.org/?probe=82192dcb1d) | Jul 27, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a33f728c24](https://linux-hardware.org/?probe=a33f728c24) | Jul 27, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [2d81f40aad](https://linux-hardware.org/?probe=2d81f40aad) | Jul 27, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [8e76bb6095](https://linux-hardware.org/?probe=8e76bb6095) | Jul 27, 2022 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [71f25aa9f5](https://linux-hardware.org/?probe=71f25aa9f5) | Jul 27, 2022 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [8d563bf194](https://linux-hardware.org/?probe=8d563bf194) | Jul 27, 2022 |
| Dell          | 0F896N A02                  | Desktop     | [ede9425ed8](https://linux-hardware.org/?probe=ede9425ed8) | Jul 27, 2022 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [a3c2fdccfc](https://linux-hardware.org/?probe=a3c2fdccfc) | Jul 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [577c3ce56c](https://linux-hardware.org/?probe=577c3ce56c) | Jul 27, 2022 |
| Sony          | VPCF11M1E                   | Notebook    | [97a18303ee](https://linux-hardware.org/?probe=97a18303ee) | Jul 26, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [ce18b4e9ab](https://linux-hardware.org/?probe=ce18b4e9ab) | Jul 26, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [cfb18dd008](https://linux-hardware.org/?probe=cfb18dd008) | Jul 26, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [fe48f1e5cd](https://linux-hardware.org/?probe=fe48f1e5cd) | Jul 26, 2022 |
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
| Intel Clie... | LAPKC71F                    | Notebook    | [baf09f6525](https://linux-hardware.org/?probe=baf09f6525) | Jul 24, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [c1515e724a](https://linux-hardware.org/?probe=c1515e724a) | Jul 24, 2022 |
| HP            | 8433 11                     | Desktop     | [a66fb85e77](https://linux-hardware.org/?probe=a66fb85e77) | Jul 23, 2022 |
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

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Pop!_OS 20.04 | 2114      | 25.99%  |
| Pop!_OS 21.04 | 1798      | 22.1%   |
| Pop!_OS 20.10 | 1649      | 20.27%  |
| Pop!_OS 22.04 | 1390      | 17.09%  |
| Pop!_OS 21.10 | 1108      | 13.62%  |
| Pop!_OS 19.10 | 47        | 0.58%   |
| Pop!_OS 19.04 | 12        | 0.15%   |
| Pop!_OS 18.04 | 11        | 0.14%   |
| Pop!_OS 18.10 | 5         | 0.06%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Pop!_OS | 7674      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.11.0-7620-generic      | 837       | 9.68%   |
| 5.8.0-7630-generic       | 741       | 8.57%   |
| 5.4.0-7634-generic       | 666       | 7.7%    |
| 5.13.0-7614-generic      | 496       | 5.74%   |
| 5.8.0-7642-generic       | 481       | 5.56%   |
| 5.4.0-7642-generic       | 465       | 5.38%   |
| 5.17.5-76051705-generic  | 443       | 5.12%   |
| 5.11.0-7614-generic      | 437       | 5.05%   |
| 5.19.0-76051900-generic  | 426       | 4.93%   |
| 5.13.0-7620-generic      | 412       | 4.77%   |
| 5.15.15-76051515-generic | 280       | 3.24%   |
| 5.16.11-76051611-generic | 262       | 3.03%   |
| 5.15.5-76051505-generic  | 235       | 2.72%   |
| 5.11.0-7612-generic      | 226       | 2.61%   |
| 5.18.10-76051810-generic | 200       | 2.31%   |
| 5.8.0-7625-generic       | 195       | 2.26%   |
| 5.17.15-76051715-generic | 186       | 2.15%   |
| 5.11.0-7633-generic      | 180       | 2.08%   |
| 5.16.19-76051619-generic | 177       | 2.05%   |
| 5.15.8-76051508-generic  | 171       | 1.98%   |
| 5.16.15-76051615-generic | 150       | 1.73%   |
| 5.4.0-7626-generic       | 144       | 1.67%   |
| 5.15.11-76051511-generic | 112       | 1.3%    |
| 5.15.23-76051523-generic | 91        | 1.05%   |
| 5.4.0-7625-generic       | 74        | 0.86%   |
| 5.4.0-7629-generic       | 62        | 0.72%   |
| 6.0.2-76060002-generic   | 61        | 0.71%   |
| 5.19.16-76051916-generic | 40        | 0.46%   |
| 5.3.0-7625-generic       | 16        | 0.19%   |
| 5.3.0-7629-generic       | 10        | 0.12%   |
| 5.3.0-7648-generic       | 9         | 0.1%    |
| 5.11.0-051100-generic    | 9         | 0.1%    |
| 5.4.0-7624-generic       | 6         | 0.07%   |
| 5.13.0-1011-raspi        | 6         | 0.07%   |
| 5.3.0-22-generic         | 5         | 0.06%   |
| 5.15.0-76051500-generic  | 5         | 0.06%   |
| 5.8.5-xanmod1            | 4         | 0.05%   |
| 5.8.5-050805-generic     | 4         | 0.05%   |
| 5.8.12-xanmod1           | 4         | 0.05%   |
| 5.7.8-050708-generic     | 4         | 0.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 1624      | 19.24%  |
| 5.4.0   | 1370      | 16.23%  |
| 5.8.0   | 1357      | 16.08%  |
| 5.13.0  | 910       | 10.78%  |
| 5.17.5  | 446       | 5.28%   |
| 5.19.0  | 429       | 5.08%   |
| 5.15.15 | 281       | 3.33%   |
| 5.16.11 | 262       | 3.1%    |
| 5.15.5  | 235       | 2.78%   |
| 5.18.10 | 200       | 2.37%   |
| 5.17.15 | 186       | 2.2%    |
| 5.16.19 | 177       | 2.1%    |
| 5.15.8  | 171       | 2.03%   |
| 5.16.15 | 150       | 1.78%   |
| 5.15.11 | 112       | 1.33%   |
| 5.15.23 | 91        | 1.08%   |
| 6.0.2   | 64        | 0.76%   |
| 5.3.0   | 51        | 0.6%    |
| 5.19.16 | 40        | 0.47%   |
| 5.0.0   | 12        | 0.14%   |
| 5.8.5   | 8         | 0.09%   |
| 5.7.0   | 8         | 0.09%   |
| 5.15.0  | 8         | 0.09%   |
| 5.8.12  | 7         | 0.08%   |
| 4.18.0  | 7         | 0.08%   |
| 5.13.12 | 6         | 0.07%   |
| 5.10.0  | 6         | 0.07%   |
| 5.8.6   | 5         | 0.06%   |
| 5.6.16  | 5         | 0.06%   |
| 5.7.8   | 4         | 0.05%   |
| 5.7.1   | 4         | 0.05%   |
| 5.14.0  | 4         | 0.05%   |
| 5.12.14 | 4         | 0.05%   |
| 6.0.3   | 3         | 0.04%   |
| 5.9.1   | 3         | 0.04%   |
| 5.8.9   | 3         | 0.04%   |
| 5.8.11  | 3         | 0.04%   |
| 5.7.15  | 3         | 0.04%   |
| 5.7.12  | 3         | 0.04%   |
| 5.15.7  | 3         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 1633      | 19.5%   |
| 5.8     | 1394      | 16.65%  |
| 5.4     | 1374      | 16.41%  |
| 5.13    | 929       | 11.1%   |
| 5.15    | 893       | 10.67%  |
| 5.17    | 631       | 7.54%   |
| 5.16    | 578       | 6.9%    |
| 5.19    | 470       | 5.61%   |
| 5.18    | 207       | 2.47%   |
| 6.0     | 69        | 0.82%   |
| 5.3     | 51        | 0.61%   |
| 5.10    | 28        | 0.33%   |
| 5.7     | 27        | 0.32%   |
| 5.12    | 18        | 0.21%   |
| 5.14    | 16        | 0.19%   |
| 5.9     | 15        | 0.18%   |
| 5.6     | 15        | 0.18%   |
| 5.0     | 12        | 0.14%   |
| 4.18    | 8         | 0.1%    |
| 4.15    | 3         | 0.04%   |
| 5.1     | 1         | 0.01%   |
| 4.9     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 7658      | 99.79%  |
| aarch64 | 16        | 0.21%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 7421      | 96.11%  |
| KDE5            | 63        | 0.82%   |
| KDE             | 59        | 0.76%   |
| Unknown         | 54        | 0.7%    |
| X-Cinnamon      | 33        | 0.43%   |
| MATE            | 19        | 0.25%   |
| XFCE            | 16        | 0.21%   |
| GNOME Flashback | 15        | 0.19%   |
| Cinnamon        | 13        | 0.17%   |
| LXQt            | 10        | 0.13%   |
| Budgie          | 6         | 0.08%   |
| Unity           | 5         | 0.06%   |
| i3              | 3         | 0.04%   |
| pop             | 1         | 0.01%   |
| Pantheon        | 1         | 0.01%   |
| Deepin          | 1         | 0.01%   |
| awesome         | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 7479      | 97%     |
| Wayland | 196       | 2.54%   |
| Unknown | 22        | 0.29%   |
| Tty     | 13        | 0.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 6192      | 79.96%  |
| GDM     | 1195      | 15.43%  |
| GDM3    | 334       | 4.31%   |
| SDDM    | 13        | 0.17%   |
| TDM     | 8         | 0.1%    |
| LightDM | 2         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 4373      | 56.62%  |
| en_GB   | 582       | 7.53%   |
| pt_BR   | 568       | 7.35%   |
| de_DE   | 364       | 4.71%   |
| C       | 233       | 3.02%   |
| en_AU   | 204       | 2.64%   |
| en_CA   | 176       | 2.28%   |
| fr_FR   | 157       | 2.03%   |
| it_IT   | 134       | 1.73%   |
| es_ES   | 129       | 1.67%   |
| ru_RU   | 101       | 1.31%   |
| Unknown | 70        | 0.91%   |
| pl_PL   | 68        | 0.88%   |
| sv_SE   | 53        | 0.69%   |
| pt_PT   | 51        | 0.66%   |
| nl_NL   | 49        | 0.63%   |
| en_IN   | 31        | 0.4%    |
| fi_FI   | 27        | 0.35%   |
| en_ZA   | 21        | 0.27%   |
| nb_NO   | 20        | 0.26%   |
| es_MX   | 20        | 0.26%   |
| es_AR   | 19        | 0.25%   |
| fr_CA   | 18        | 0.23%   |
| en_DK   | 16        | 0.21%   |
| tr_TR   | 15        | 0.19%   |
| en_NZ   | 15        | 0.19%   |
| hr_HR   | 12        | 0.16%   |
| da_DK   | 12        | 0.16%   |
| sk_SK   | 11        | 0.14%   |
| nl_BE   | 11        | 0.14%   |
| hu_HU   | 11        | 0.14%   |
| es_CL   | 11        | 0.14%   |
| cs_CZ   | 11        | 0.14%   |
| zh_TW   | 10        | 0.13%   |
| ja_JP   | 9         | 0.12%   |
| ro_RO   | 8         | 0.1%    |
| en_IE   | 8         | 0.1%    |
| de_AT   | 8         | 0.1%    |
| zh_CN   | 7         | 0.09%   |
| de_CH   | 7         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 5712      | 73.39%  |
| EFI  | 2071      | 26.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 7371      | 95.76%  |
| Btrfs   | 163       | 2.12%   |
| Overlay | 122       | 1.59%   |
| Xfs     | 24        | 0.31%   |
| Unknown | 12        | 0.16%   |
| Zfs     | 4         | 0.05%   |
| Ext2    | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 6151      | 79.54%  |
| GPT     | 1413      | 18.27%  |
| MBR     | 169       | 2.19%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 7487      | 97.25%  |
| Yes       | 212       | 2.75%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 7029      | 91.13%  |
| Yes       | 684       | 8.87%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1339      | 17.45%  |
| Dell                    | 1033      | 13.46%  |
| Lenovo                  | 992       | 12.93%  |
| Hewlett-Packard         | 804       | 10.48%  |
| Gigabyte Technology     | 606       | 7.9%    |
| MSI                     | 586       | 7.64%   |
| Acer                    | 369       | 4.81%   |
| Apple                   | 316       | 4.12%   |
| ASRock                  | 303       | 3.95%   |
| System76                | 186       | 2.42%   |
| Intel                   | 109       | 1.42%   |
| Toshiba                 | 88        | 1.15%   |
| Samsung Electronics     | 81        | 1.06%   |
| HUAWEI                  | 50        | 0.65%   |
| Alienware               | 48        | 0.63%   |
| Sony                    | 46        | 0.6%    |
| Notebook                | 41        | 0.53%   |
| Microsoft               | 40        | 0.52%   |
| Fujitsu                 | 38        | 0.5%    |
| Positivo                | 34        | 0.44%   |
| Google                  | 33        | 0.43%   |
| Unknown                 | 28        | 0.36%   |
| Pegatron                | 26        | 0.34%   |
| Medion                  | 21        | 0.27%   |
| Razer                   | 20        | 0.26%   |
| Raspberry Pi Foundation | 16        | 0.21%   |
| PC Specialist           | 16        | 0.21%   |
| Biostar                 | 16        | 0.21%   |
| Foxconn                 | 15        | 0.2%    |
| ECS                     | 15        | 0.2%    |
| Supermicro              | 14        | 0.18%   |
| Timi                    | 13        | 0.17%   |
| LG Electronics          | 13        | 0.17%   |
| Gateway                 | 12        | 0.16%   |
| TUXEDO                  | 11        | 0.14%   |
| Packard Bell            | 11        | 0.14%   |
| Framework               | 10        | 0.13%   |
| Huanan                  | 9         | 0.12%   |
| GPU Company             | 9         | 0.12%   |
| PCWare                  | 8         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| ASUS All Series                | 79        | 1.03%   |
| System76 Oryx Pro              | 40        | 0.52%   |
| Unknown                        | 40        | 0.52%   |
| ASUS TUF Gaming X570-PLUS      | 35        | 0.46%   |
| System76 Lemur Pro             | 33        | 0.43%   |
| Gigabyte B450M DS3H            | 33        | 0.43%   |
| MSI MS-7C02                    | 29        | 0.38%   |
| Dell XPS 15 7590               | 28        | 0.36%   |
| MSI MS-7C37                    | 26        | 0.34%   |
| MSI MS-7B86                    | 25        | 0.33%   |
| ASUS ROG STRIX B450-F GAMING   | 25        | 0.33%   |
| Apple MacBookPro9,2            | 22        | 0.29%   |
| ASUS PRIME B450M-A             | 21        | 0.27%   |
| Dell OptiPlex 9020             | 20        | 0.26%   |
| System76 Galago Pro            | 19        | 0.25%   |
| HP Pavilion Notebook           | 19        | 0.25%   |
| Dell XPS 15 9500               | 19        | 0.25%   |
| ASUS ROG STRIX B550-F GAMING   | 19        | 0.25%   |
| System76 Thelio                | 18        | 0.23%   |
| System76 Gazelle               | 18        | 0.23%   |
| Gigabyte X570 AORUS ELITE      | 18        | 0.23%   |
| System76 Darter Pro            | 16        | 0.21%   |
| ASRock B450M Pro4              | 16        | 0.21%   |
| Apple MacBookPro8,1            | 16        | 0.21%   |
| HP Pavilion 15                 | 15        | 0.2%    |
| Dell OptiPlex 7010             | 15        | 0.2%    |
| ASRock B450M Steel Legend      | 15        | 0.2%    |
| HP Notebook                    | 14        | 0.18%   |
| Dell XPS 15 9560               | 14        | 0.18%   |
| Apple MacBookPro12,1           | 14        | 0.18%   |
| HP Pavilion dv6                | 13        | 0.17%   |
| Gigabyte B450 I AORUS PRO WIFI | 13        | 0.17%   |
| Dell Latitude E6420            | 13        | 0.17%   |
| Apple MacBookAir7,2            | 13        | 0.17%   |
| Apple MacBookAir6,2            | 13        | 0.17%   |
| RPi Raspberry Pi               | 12        | 0.16%   |
| MSI MS-7C91                    | 12        | 0.16%   |
| Gigabyte X570 AORUS MASTER     | 12        | 0.16%   |
| Gigabyte B450 AORUS M          | 12        | 0.16%   |
| Gigabyte A320M-S2H             | 12        | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 419       | 5.46%   |
| Dell Inspiron      | 297       | 3.87%   |
| Acer Aspire        | 256       | 3.34%   |
| ASUS ROG           | 253       | 3.3%    |
| Lenovo IdeaPad     | 229       | 2.98%   |
| Dell Latitude      | 190       | 2.48%   |
| Dell XPS           | 189       | 2.46%   |
| ASUS PRIME         | 159       | 2.07%   |
| HP Pavilion        | 157       | 2.05%   |
| ASUS TUF           | 134       | 1.75%   |
| Dell OptiPlex      | 131       | 1.71%   |
| HP EliteBook       | 92        | 1.2%    |
| Dell Precision     | 87        | 1.13%   |
| HP Laptop          | 83        | 1.08%   |
| ASUS All           | 79        | 1.03%   |
| Toshiba Satellite  | 76        | 0.99%   |
| HP ProBook         | 66        | 0.86%   |
| HP ENVY            | 66        | 0.86%   |
| HP Compaq          | 66        | 0.86%   |
| Gigabyte X570      | 66        | 0.86%   |
| ASUS VivoBook      | 66        | 0.86%   |
| Lenovo Legion      | 62        | 0.81%   |
| Dell Vostro        | 55        | 0.72%   |
| Lenovo Yoga        | 52        | 0.68%   |
| Lenovo ThinkCentre | 47        | 0.61%   |
| Gigabyte B450      | 46        | 0.6%    |
| Gigabyte B450M     | 45        | 0.59%   |
| Acer Nitro         | 43        | 0.56%   |
| System76 Oryx      | 40        | 0.52%   |
| Microsoft Surface  | 40        | 0.52%   |
| Unknown            | 40        | 0.52%   |
| ASRock B450M       | 37        | 0.48%   |
| System76 Lemur     | 36        | 0.47%   |
| HP OMEN            | 32        | 0.42%   |
| ASUS ZenBook       | 32        | 0.42%   |
| ASUS ASUS          | 32        | 0.42%   |
| ASRock X570        | 30        | 0.39%   |
| MSI MS-7C02        | 29        | 0.38%   |
| Apple MacBookPro9  | 29        | 0.38%   |
| System76 Thelio    | 28        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 1029      | 13.41%  |
| 2018    | 956       | 12.46%  |
| 2020    | 915       | 11.92%  |
| 2012    | 572       | 7.45%   |
| 2021    | 560       | 7.3%    |
| 2017    | 553       | 7.21%   |
| 2013    | 479       | 6.24%   |
| 2011    | 461       | 6.01%   |
| 2015    | 414       | 5.39%   |
| 2014    | 412       | 5.37%   |
| 2016    | 398       | 5.19%   |
| 2010    | 301       | 3.92%   |
| 2009    | 225       | 2.93%   |
| 2008    | 167       | 2.18%   |
| 2022    | 104       | 1.36%   |
| 2007    | 89        | 1.16%   |
| 2006    | 21        | 0.27%   |
| Unknown | 16        | 0.21%   |
| 2005    | 1         | 0.01%   |
| 2004    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 4187      | 54.56%  |
| Desktop        | 2968      | 38.68%  |
| Convertible    | 202       | 2.63%   |
| Tablet         | 94        | 1.22%   |
| All in one     | 93        | 1.21%   |
| Mini pc        | 91        | 1.19%   |
| Server         | 22        | 0.29%   |
| System on chip | 16        | 0.21%   |
| Stick pc       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 7669      | 99.93%  |
| Enabled  | 5         | 0.07%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 7546      | 98.33%  |
| Yes  | 128       | 1.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 2044      | 26.3%   |
| 4.01-8.0        | 1673      | 21.52%  |
| 8.01-16.0       | 1446      | 18.6%   |
| 32.01-64.0      | 1033      | 13.29%  |
| 3.01-4.0        | 996       | 12.81%  |
| 64.01-256.0     | 275       | 3.54%   |
| 24.01-32.0      | 143       | 1.84%   |
| 1.01-2.0        | 111       | 1.43%   |
| 2.01-3.0        | 42        | 0.54%   |
| More than 256.0 | 9         | 0.12%   |
| 0.51-1.0        | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 2615      | 31.25%  |
| 1.01-2.0    | 2296      | 27.44%  |
| 4.01-8.0    | 1522      | 18.19%  |
| 3.01-4.0    | 1488      | 17.78%  |
| 8.01-16.0   | 347       | 4.15%   |
| 16.01-24.0  | 49        | 0.59%   |
| 0.51-1.0    | 18        | 0.22%   |
| 24.01-32.0  | 16        | 0.19%   |
| 32.01-64.0  | 12        | 0.14%   |
| 64.01-256.0 | 3         | 0.04%   |
| 0.01-0.5    | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 4331      | 55.19%  |
| 2      | 2141      | 27.28%  |
| 3      | 713       | 9.09%   |
| 4      | 353       | 4.5%    |
| 5      | 145       | 1.85%   |
| 6      | 64        | 0.82%   |
| 0      | 42        | 0.54%   |
| 7      | 25        | 0.32%   |
| 8      | 9         | 0.11%   |
| 11     | 8         | 0.1%    |
| 9      | 7         | 0.09%   |
| 10     | 3         | 0.04%   |
| 23     | 1         | 0.01%   |
| 20     | 1         | 0.01%   |
| 19     | 1         | 0.01%   |
| 14     | 1         | 0.01%   |
| 13     | 1         | 0.01%   |
| 12     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 5404      | 70.05%  |
| Yes       | 2311      | 29.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6577      | 85.38%  |
| No        | 1126      | 14.62%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6176      | 80.1%   |
| No        | 1534      | 19.9%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5133      | 66.23%  |
| No        | 2617      | 33.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 2326      | 30.16%  |
| Brazil       | 760       | 9.86%   |
| Germany      | 503       | 6.52%   |
| UK           | 388       | 5.03%   |
| Canada       | 331       | 4.29%   |
| Australia    | 227       | 2.94%   |
| India        | 222       | 2.88%   |
| Italy        | 213       | 2.76%   |
| France       | 198       | 2.57%   |
| Netherlands  | 174       | 2.26%   |
| Sweden       | 134       | 1.74%   |
| Russia       | 126       | 1.63%   |
| Poland       | 116       | 1.5%    |
| Spain        | 104       | 1.35%   |
| Mexico       | 88        | 1.14%   |
| Portugal     | 86        | 1.12%   |
| Switzerland  | 79        | 1.02%   |
| South Africa | 79        | 1.02%   |
| Romania      | 77        | 1%      |
| Norway       | 69        | 0.89%   |
| Finland      | 67        | 0.87%   |
| Austria      | 58        | 0.75%   |
| Argentina    | 56        | 0.73%   |
| Belgium      | 55        | 0.71%   |
| Philippines  | 54        | 0.7%    |
| New Zealand  | 53        | 0.69%   |
| Greece       | 52        | 0.67%   |
| Denmark      | 50        | 0.65%   |
| Turkey       | 45        | 0.58%   |
| Indonesia    | 40        | 0.52%   |
| Chile        | 37        | 0.48%   |
| Japan        | 35        | 0.45%   |
| Czechia      | 35        | 0.45%   |
| Ireland      | 34        | 0.44%   |
| Croatia      | 32        | 0.41%   |
| Bulgaria     | 31        | 0.4%    |
| Ukraine      | 30        | 0.39%   |
| Hungary      | 30        | 0.39%   |
| Malaysia     | 29        | 0.38%   |
| Serbia       | 25        | 0.32%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 89        | 1.11%   |
| Sydney         | 61        | 0.76%   |
| Melbourne      | 46        | 0.57%   |
| Rio de Janeiro | 45        | 0.56%   |
| Brisbane       | 43        | 0.54%   |
| Berlin         | 43        | 0.54%   |
| Milan          | 42        | 0.52%   |
| Vienna         | 37        | 0.46%   |
| Dallas         | 36        | 0.45%   |
| London         | 34        | 0.42%   |
| Moscow         | 33        | 0.41%   |
| Warsaw         | 32        | 0.4%    |
| Helsinki       | 32        | 0.4%    |
| Paris          | 31        | 0.39%   |
| Bengaluru      | 30        | 0.37%   |
| New York       | 29        | 0.36%   |
| Amsterdam      | 29        | 0.36%   |
| Bucharest      | 28        | 0.35%   |
| Athens         | 28        | 0.35%   |
| Toronto        | 27        | 0.34%   |
| Rome           | 27        | 0.34%   |
| Miami          | 27        | 0.34%   |
| Chicago        | 27        | 0.34%   |
| Zurich         | 26        | 0.32%   |
| Auckland       | 26        | 0.32%   |
| Montreal       | 25        | 0.31%   |
| Denver         | 25        | 0.31%   |
| Madrid         | 24        | 0.3%    |
| Los Angeles    | 23        | 0.29%   |
| Johannesburg   | 23        | 0.29%   |
| Edmonton       | 23        | 0.29%   |
| Zagreb         | 22        | 0.27%   |
| Sofia          | 22        | 0.27%   |
| Seattle        | 22        | 0.27%   |
| Calgary        | 22        | 0.27%   |
| Brasília      | 22        | 0.27%   |
| Stockholm      | 21        | 0.26%   |
| Lisbon         | 21        | 0.26%   |
| Istanbul       | 21        | 0.26%   |
| Atlanta        | 21        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 2111      | 3179   | 17.82%  |
| Seagate                   | 1644      | 2342   | 13.88%  |
| WDC                       | 1624      | 2246   | 13.71%  |
| SanDisk                   | 769       | 1009   | 6.49%   |
| Kingston                  | 677       | 850    | 5.72%   |
| Toshiba                   | 650       | 794    | 5.49%   |
| Crucial                   | 468       | 610    | 3.95%   |
| Unknown                   | 388       | 492    | 3.28%   |
| Intel                     | 329       | 432    | 2.78%   |
| SK hynix                  | 322       | 411    | 2.72%   |
| Hitachi                   | 250       | 311    | 2.11%   |
| Phison                    | 223       | 314    | 1.88%   |
| HGST                      | 212       | 252    | 1.79%   |
| A-DATA Technology         | 180       | 226    | 1.52%   |
| Micron Technology         | 171       | 201    | 1.44%   |
| Apple                     | 145       | 168    | 1.22%   |
| PNY                       | 111       | 138    | 0.94%   |
| Silicon Motion            | 106       | 144    | 0.89%   |
| China                     | 106       | 141    | 0.89%   |
| Micron/Crucial Technology | 94        | 124    | 0.79%   |
| LITEON                    | 54        | 63     | 0.46%   |
| OCZ                       | 51        | 66     | 0.43%   |
| SPCC                      | 48        | 62     | 0.41%   |
| KIOXIA                    | 48        | 57     | 0.41%   |
| XPG                       | 44        | 57     | 0.37%   |
| Transcend                 | 41        | 47     | 0.35%   |
| Corsair                   | 41        | 52     | 0.35%   |
| Team                      | 40        | 48     | 0.34%   |
| Patriot                   | 38        | 50     | 0.32%   |
| Realtek Semiconductor     | 35        | 39     | 0.3%    |
| Maxtor                    | 34        | 35     | 0.29%   |
| LITEONIT                  | 33        | 41     | 0.28%   |
| JMicron Technology        | 29        | 45     | 0.24%   |
| KingSpec                  | 25        | 29     | 0.21%   |
| Hewlett-Packard           | 25        | 32     | 0.21%   |
| ADATA Technology          | 25        | 34     | 0.21%   |
| Fujitsu                   | 24        | 26     | 0.2%    |
| Intenso                   | 23        | 25     | 0.19%   |
| Lexar                     | 22        | 23     | 0.19%   |
| Netac                     | 19        | 19     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 1TB             | 197       | 1.5%    |
| Samsung NVMe SSD Drive 500GB           | 178       | 1.36%   |
| Kingston SA400S37240G 240GB SSD        | 178       | 1.36%   |
| Samsung NVMe SSD Drive 512GB           | 118       | 0.9%    |
| Seagate ST1000LM035-1RK172 1TB         | 113       | 0.86%   |
| Samsung SSD 850 EVO 250GB              | 110       | 0.84%   |
| SanDisk NVMe SSD Drive 1TB             | 104       | 0.79%   |
| Samsung SSD 860 EVO 500GB              | 100       | 0.76%   |
| Unknown MMC Card  64GB                 | 97        | 0.74%   |
| Samsung SSD 850 EVO 500GB              | 96        | 0.73%   |
| SanDisk NVMe SSD Drive 500GB           | 94        | 0.72%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 91        | 0.69%   |
| Seagate ST2000DM008-2FR102 2TB         | 90        | 0.69%   |
| Samsung SSD 860 EVO 1TB                | 89        | 0.68%   |
| Seagate ST1000DM010-2EP102 1TB         | 86        | 0.66%   |
| Kingston SA400S37120G 120GB SSD        | 84        | 0.64%   |
| HGST HTS721010A9E630 1TB               | 79        | 0.6%    |
| Seagate ST500DM002-1BD142 500GB        | 74        | 0.56%   |
| Samsung NVMe SSD Drive 250GB           | 74        | 0.56%   |
| Kingston SA400S37480G 480GB SSD        | 73        | 0.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 72        | 0.55%   |
| Toshiba MQ01ABD100 1TB                 | 70        | 0.53%   |
| SanDisk NVMe SSD Drive 512GB           | 69        | 0.53%   |
| Intel NVMe SSD Drive 512GB             | 69        | 0.53%   |
| Crucial CT1000MX500SSD1 1TB            | 67        | 0.51%   |
| Unknown MMC Card  32GB                 | 64        | 0.49%   |
| Crucial CT500MX500SSD1 500GB           | 64        | 0.49%   |
| WDC WD10EZEX-08WN4A0 1TB               | 63        | 0.48%   |
| SK hynix NVMe SSD Drive 512GB          | 61        | 0.47%   |
| Samsung NVMe SSD Drive 2TB             | 59        | 0.45%   |
| Samsung NVMe SSD Drive 1024GB          | 58        | 0.44%   |
| Crucial CT240BX500SSD1 240GB           | 54        | 0.41%   |
| Intel NVMe SSD Drive 1024GB            | 52        | 0.4%    |
| Samsung SSD 970 EVO Plus 1TB           | 50        | 0.38%   |
| Samsung SSD 860 EVO 250GB              | 49        | 0.37%   |
| Phison NVMe SSD Drive 1TB              | 49        | 0.37%   |
| Micron/Crucial NVMe SSD Drive 1TB      | 49        | 0.37%   |
| Kingston SV300S37A120G 120GB SSD       | 49        | 0.37%   |
| Unknown MMC Card  128GB                | 48        | 0.37%   |
| Seagate Expansion 2TB                  | 46        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1589      | 2221   | 38.79%  |
| WDC                 | 1258      | 1723   | 30.71%  |
| Toshiba             | 461       | 553    | 11.25%  |
| Hitachi             | 250       | 311    | 6.1%    |
| HGST                | 212       | 252    | 5.18%   |
| Samsung Electronics | 130       | 151    | 3.17%   |
| Unknown             | 46        | 57     | 1.12%   |
| Apple               | 43        | 51     | 1.05%   |
| Maxtor              | 26        | 27     | 0.63%   |
| Fujitsu             | 23        | 25     | 0.56%   |
| SABRENT             | 16        | 18     | 0.39%   |
| ASMT                | 6         | 7      | 0.15%   |
| JMicron Technology  | 5         | 13     | 0.12%   |
| USB                 | 3         | 4      | 0.07%   |
| SATAFIRM            | 3         | 3      | 0.07%   |
| Hewlett-Packard     | 3         | 5      | 0.07%   |
| ExcelStor           | 3         | 3      | 0.07%   |
| Magnetic Data       | 2         | 2      | 0.05%   |
| Intenso             | 2         | 2      | 0.05%   |
| USB3.0              | 1         | 1      | 0.02%   |
| RSH-339             | 1         | 1      | 0.02%   |
| Quantum             | 1         | 1      | 0.02%   |
| PHD 3.0             | 1         | 1      | 0.02%   |
| OEM                 | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 2      | 0.02%   |
| LaCie               | 1         | 1      | 0.02%   |
| Inateck             | 1         | 1      | 0.02%   |
| HGST HTS            | 1         | 1      | 0.02%   |
| HGST HDN            | 1         | 1      | 0.02%   |
| H/W                 | 1         | 1      | 0.02%   |
| Glyph               | 1         | 2      | 0.02%   |
| DAS                 | 1         | 4      | 0.02%   |
| ASMT109x            | 1         | 1      | 0.02%   |
| Asm                 | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1030      | 1484   | 24.66%  |
| Kingston            | 552       | 676    | 13.22%  |
| Crucial             | 436       | 570    | 10.44%  |
| SanDisk             | 394       | 499    | 9.43%   |
| WDC                 | 282       | 353    | 6.75%   |
| A-DATA Technology   | 144       | 182    | 3.45%   |
| PNY                 | 109       | 136    | 2.61%   |
| China               | 104       | 139    | 2.49%   |
| Intel               | 98        | 115    | 2.35%   |
| Apple               | 86        | 92     | 2.06%   |
| SK hynix            | 79        | 99     | 1.89%   |
| Micron Technology   | 68        | 75     | 1.63%   |
| Toshiba             | 66        | 77     | 1.58%   |
| OCZ                 | 50        | 62     | 1.2%    |
| LITEON              | 50        | 59     | 1.2%    |
| SPCC                | 44        | 55     | 1.05%   |
| Transcend           | 40        | 46     | 0.96%   |
| Patriot             | 38        | 50     | 0.91%   |
| Team                | 33        | 41     | 0.79%   |
| LITEONIT            | 33        | 41     | 0.79%   |
| Seagate             | 31        | 45     | 0.74%   |
| Corsair             | 31        | 38     | 0.74%   |
| KingSpec            | 24        | 28     | 0.57%   |
| Lexar               | 21        | 22     | 0.5%    |
| Hewlett-Packard     | 18        | 23     | 0.43%   |
| Netac               | 17        | 17     | 0.41%   |
| Apacer              | 15        | 20     | 0.36%   |
| Intenso             | 14        | 16     | 0.34%   |
| KingDian            | 13        | 15     | 0.31%   |
| GOODRAM             | 13        | 14     | 0.31%   |
| Plextor             | 12        | 16     | 0.29%   |
| Gigabyte Technology | 12        | 14     | 0.29%   |
| TO Exter            | 11        | 14     | 0.26%   |
| Mushkin             | 10        | 12     | 0.24%   |
| Dogfish             | 9         | 11     | 0.22%   |
| ASMT                | 9         | 14     | 0.22%   |
| Maxtor              | 8         | 8      | 0.19%   |
| OWC                 | 7         | 16     | 0.17%   |
| PNY USB             | 6         | 13     | 0.14%   |
| FORESEE             | 6         | 8      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 3632      | 5383   | 34.15%  |
| HDD     | 3493      | 5448   | 32.84%  |
| NVMe    | 3019      | 4459   | 28.39%  |
| MMC     | 297       | 369    | 2.79%   |
| Unknown | 194       | 267    | 1.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5640      | 10463  | 60.07%  |
| NVMe | 3008      | 4428   | 32.04%  |
| SAS  | 444       | 666    | 4.73%   |
| MMC  | 297       | 369    | 3.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4102      | 6069   | 55.05%  |
| 0.51-1.0   | 2251      | 3091   | 30.21%  |
| 1.01-2.0   | 652       | 923    | 8.75%   |
| 3.01-4.0   | 188       | 302    | 2.52%   |
| 2.01-3.0   | 134       | 197    | 1.8%    |
| 4.01-10.0  | 108       | 205    | 1.45%   |
| 10.01-20.0 | 17        | 44     | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2392      | 30.03%  |
| 251-500        | 1983      | 24.89%  |
| 501-1000       | 1451      | 18.21%  |
| 1001-2000      | 739       | 9.28%   |
| 51-100         | 372       | 4.67%   |
| More than 3000 | 367       | 4.61%   |
| 2001-3000      | 239       | 3%      |
| 21-50          | 186       | 2.33%   |
| 1-20           | 184       | 2.31%   |
| Unknown        | 53        | 0.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3179      | 38.23%  |
| 21-50          | 1641      | 19.73%  |
| 101-250        | 1007      | 12.11%  |
| 51-100         | 985       | 11.84%  |
| 251-500        | 595       | 7.15%   |
| 501-1000       | 402       | 4.83%   |
| 1001-2000      | 243       | 2.92%   |
| More than 3000 | 135       | 1.62%   |
| 2001-3000      | 76        | 0.91%   |
| Unknown        | 53        | 0.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB    | 6         | 6      | 2.53%   |
| HGST HTS725050A7E630 500GB            | 6         | 9      | 2.53%   |
| HGST HTS721010A9E630 1TB              | 5         | 5      | 2.11%   |
| Seagate ST1000LM035-1RK172 1TB        | 4         | 4      | 1.69%   |
| HGST HTS541010A9E680 1TB              | 4         | 4      | 1.69%   |
| WDC WD10JPCX-24UE4T0 1TB              | 3         | 3      | 1.27%   |
| Seagate ST500LT012-9WS142 500GB       | 3         | 4      | 1.27%   |
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 1.27%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 3         | 3      | 1.27%   |
| Seagate ST500DM002-1BD142 500GB       | 3         | 3      | 1.27%   |
| Seagate ST1500DL003-9VT16L 1TB        | 3         | 3      | 1.27%   |
| Seagate ST1000LX015-1U7172 1TB        | 3         | 3      | 1.27%   |
| Seagate ST1000DM003-9YN162 1TB        | 3         | 3      | 1.27%   |
| Samsung Electronics HD502HI 500GB     | 3         | 3      | 1.27%   |
| Kingston SV300S37A120G 120GB SSD      | 3         | 5      | 1.27%   |
| Hitachi HTS545050A7E380 500GB         | 3         | 5      | 1.27%   |
| Crucial CT525MX300SSD1 528GB          | 3         | 3      | 1.27%   |
| Crucial CT1000P1SSD8 1TB              | 3         | 3      | 1.27%   |
| WDC WD3200AAKS-75B3A0 320GB           | 2         | 2      | 0.84%   |
| WDC WD10EZEX-60WN4A0 1TB              | 2         | 2      | 0.84%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 0.84%   |
| Toshiba HDWD110 1TB                   | 2         | 2      | 0.84%   |
| Seagate ST9750420AS 752GB             | 2         | 2      | 0.84%   |
| Seagate ST9500325AS 500GB             | 2         | 3      | 0.84%   |
| Seagate ST9320325AS 320GB             | 2         | 2      | 0.84%   |
| Seagate ST2000DM008-2FR102 2TB        | 2         | 2      | 0.84%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD   | 2         | 2      | 0.84%   |
| Samsung Electronics SSD 850 EVO 500GB | 2         | 2      | 0.84%   |
| Samsung Electronics HD103SJ 1TB       | 2         | 2      | 0.84%   |
| Kingston SUV400S37120G 120GB SSD      | 2         | 2      | 0.84%   |
| Kingston SA400S37120G 120GB SSD       | 2         | 3      | 0.84%   |
| Hitachi HDP725050GLA360 500GB         | 2         | 2      | 0.84%   |
| A-DATA Technology SU800 512GB SSD     | 2         | 2      | 0.84%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.42%   |
| WDC WD7500BPVT-60HXZT1 752GB          | 1         | 1      | 0.42%   |
| WDC WD7500BPKT-75PK4T0 752GB          | 1         | 1      | 0.42%   |
| WDC WD6400AAKS-22A7B2 640GB           | 1         | 1      | 0.42%   |
| WDC WD60EFRX-68L0BN1 6TB              | 1         | 1      | 0.42%   |
| WDC WD5001AALS-00J7B1 500GB           | 1         | 1      | 0.42%   |
| WDC WD5000LPLX-00ZNTT0 500GB          | 1         | 2      | 0.42%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 61        | 68     | 26.18%  |
| WDC                 | 47        | 53     | 20.17%  |
| Samsung Electronics | 23        | 27     | 9.87%   |
| HGST                | 17        | 20     | 7.3%    |
| Toshiba             | 15        | 16     | 6.44%   |
| Kingston            | 11        | 14     | 4.72%   |
| Hitachi             | 11        | 14     | 4.72%   |
| Crucial             | 8         | 8      | 3.43%   |
| SK hynix            | 6         | 7      | 2.58%   |
| Intel               | 6         | 6      | 2.58%   |
| Micron Technology   | 5         | 5      | 2.15%   |
| A-DATA Technology   | 5         | 5      | 2.15%   |
| SanDisk             | 3         | 3      | 1.29%   |
| China               | 2         | 2      | 0.86%   |
| Team                | 1         | 1      | 0.43%   |
| SPCC                | 1         | 1      | 0.43%   |
| SABRENT             | 1         | 1      | 0.43%   |
| S3+                 | 1         | 1      | 0.43%   |
| Plextor             | 1         | 1      | 0.43%   |
| Maxtor              | 1         | 1      | 0.43%   |
| LITEON              | 1         | 1      | 0.43%   |
| Lexar               | 1         | 1      | 0.43%   |
| Leven               | 1         | 1      | 0.43%   |
| Intenso             | 1         | 1      | 0.43%   |
| BAITITON            | 1         | 1      | 0.43%   |
| ASMT                | 1         | 1      | 0.43%   |
| Apple               | 1         | 1      | 0.43%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 61        | 68     | 37.89%  |
| WDC                 | 46        | 52     | 28.57%  |
| HGST                | 17        | 20     | 10.56%  |
| Toshiba             | 13        | 13     | 8.07%   |
| Hitachi             | 11        | 14     | 6.83%   |
| Samsung Electronics | 10        | 10     | 6.21%   |
| SABRENT             | 1         | 1      | 0.62%   |
| Maxtor              | 1         | 1      | 0.62%   |
| Apple               | 1         | 1      | 0.62%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 149       | 180    | 67.42%  |
| SSD  | 57        | 66     | 25.79%  |
| NVMe | 15        | 15     | 6.79%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST3500418ASQ 500GB        | 1         | 1      | 33.33%  |
| Samsung Electronics HM321HI 320GB | 1         | 1      | 33.33%  |
| Patriot Pyro SSD 120GB            | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| Patriot             | 1         | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 6239      | 13060  | 77.66%  |
| Works    | 1577      | 2600   | 19.63%  |
| Malfunc  | 214       | 261    | 2.66%   |
| Failed   | 3         | 4      | 0.04%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4789      | 45.97%  |
| AMD                              | 1891      | 18.15%  |
| Samsung Electronics              | 1208      | 11.6%   |
| SanDisk                          | 496       | 4.76%   |
| Phison Electronics               | 253       | 2.43%   |
| SK hynix                         | 242       | 2.32%   |
| ASMedia Technology               | 178       | 1.71%   |
| Nvidia                           | 144       | 1.38%   |
| Toshiba America Info Systems     | 138       | 1.32%   |
| Kingston Technology Company      | 131       | 1.26%   |
| Micron/Crucial Technology        | 121       | 1.16%   |
| Silicon Motion                   | 119       | 1.14%   |
| Micron Technology                | 105       | 1.01%   |
| Marvell Technology Group         | 95        | 0.91%   |
| ADATA Technology                 | 95        | 0.91%   |
| JMicron Technology               | 79        | 0.76%   |
| KIOXIA                           | 52        | 0.5%    |
| Realtek Semiconductor            | 48        | 0.46%   |
| Union Memory (Shenzhen)          | 30        | 0.29%   |
| Solid State Storage Technology   | 29        | 0.28%   |
| Seagate Technology               | 24        | 0.23%   |
| Broadcom / LSI                   | 23        | 0.22%   |
| LSI Logic / Symbios Logic        | 18        | 0.17%   |
| Apple                            | 18        | 0.17%   |
| Lite-On Technology               | 15        | 0.14%   |
| Shenzhen Longsys Electronics     | 11        | 0.11%   |
| VIA Technologies                 | 10        | 0.1%    |
| Silicon Integrated Systems [SiS] | 10        | 0.1%    |
| Silicon Image                    | 7         | 0.07%   |
| Lenovo                           | 7         | 0.07%   |
| Unknown                          | 5         | 0.05%   |
| Hewlett-Packard                  | 5         | 0.05%   |
| Adaptec                          | 5         | 0.05%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.04%   |
| HighPoint Technologies           | 3         | 0.03%   |
| OCZ Technology Group             | 2         | 0.02%   |
| Yangtze Memory Technologies      | 1         | 0.01%   |
| Transcend                        | 1         | 0.01%   |
| O2 Micro                         | 1         | 0.01%   |
| Integrated Technology Express    | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1433      | 12.15%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 714       | 6.05%   |
| AMD 400 Series Chipset SATA Controller                                         | 411       | 3.49%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 387       | 3.28%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 324       | 2.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 310       | 2.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 295       | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 244       | 2.07%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 222       | 1.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 206       | 1.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 173       | 1.47%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 170       | 1.44%   |
| AMD 500 Series Chipset SATA Controller                                         | 164       | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 154       | 1.31%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 149       | 1.26%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 147       | 1.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 147       | 1.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 146       | 1.24%   |
| Samsung NVMe SSD Controller 980                                                | 145       | 1.23%   |
| Intel SATA Controller [RAID mode]                                              | 145       | 1.23%   |
| Phison E12 NVMe Controller                                                     | 136       | 1.15%   |
| Intel SSD 660P Series                                                          | 128       | 1.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 127       | 1.08%   |
| Intel Volume Management Device NVMe RAID Controller                            | 125       | 1.06%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 124       | 1.05%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 121       | 1.03%   |
| Intel Comet Lake SATA AHCI Controller                                          | 116       | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 115       | 0.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 113       | 0.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 105       | 0.89%   |
| Micron Non-Volatile memory controller                                          | 104       | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 104       | 0.88%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 94        | 0.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 93        | 0.79%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 92        | 0.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 89        | 0.75%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 87        | 0.74%   |
| SK hynix Gold P31 SSD                                                          | 83        | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 75        | 0.64%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 73        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 5837      | 57.08%  |
| NVMe | 3010      | 29.43%  |
| IDE  | 677       | 6.62%   |
| RAID | 653       | 6.39%   |
| SAS  | 35        | 0.34%   |
| SCSI | 14        | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 5461      | 71.16%  |
| AMD    | 2197      | 28.63%  |
| ARM    | 16        | 0.21%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 137       | 1.78%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 110       | 1.43%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 107       | 1.39%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 93        | 1.21%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 89        | 1.16%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 85        | 1.1%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 85        | 1.1%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 73        | 0.95%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 69        | 0.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 68        | 0.88%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 66        | 0.86%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 66        | 0.86%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 65        | 0.84%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 65        | 0.84%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 62        | 0.81%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 60        | 0.78%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 58        | 0.75%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 55        | 0.71%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 50        | 0.65%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 50        | 0.65%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 50        | 0.65%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 47        | 0.61%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 47        | 0.61%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 45        | 0.58%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 45        | 0.58%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 45        | 0.58%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 45        | 0.58%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 43        | 0.56%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 43        | 0.56%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 40        | 0.52%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 40        | 0.52%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 39        | 0.51%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 38        | 0.49%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 38        | 0.49%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 38        | 0.49%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 38        | 0.49%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 38        | 0.49%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 37        | 0.48%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 36        | 0.47%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 35        | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1874      | 24.38%  |
| Intel Core i5           | 1718      | 22.35%  |
| AMD Ryzen 5             | 710       | 9.24%   |
| AMD Ryzen 7             | 526       | 6.84%   |
| Intel Core i3           | 443       | 5.76%   |
| Other                   | 388       | 5.05%   |
| Intel Core 2 Duo        | 227       | 2.95%   |
| AMD Ryzen 9             | 204       | 2.65%   |
| Intel Celeron           | 196       | 2.55%   |
| Intel Xeon              | 165       | 2.15%   |
| AMD Ryzen 3             | 116       | 1.51%   |
| AMD FX                  | 112       | 1.46%   |
| Intel Core i9           | 102       | 1.33%   |
| Intel Pentium           | 100       | 1.3%    |
| AMD A6                  | 62        | 0.81%   |
| Intel Atom              | 60        | 0.78%   |
| Intel Pentium Dual-Core | 59        | 0.77%   |
| AMD A8                  | 55        | 0.72%   |
| AMD A10                 | 52        | 0.68%   |
| Intel Core 2 Quad       | 46        | 0.6%    |
| AMD Ryzen Threadripper  | 43        | 0.56%   |
| AMD A4                  | 36        | 0.47%   |
| Intel Core 2            | 31        | 0.4%    |
| AMD Phenom II X4        | 31        | 0.4%    |
| AMD Ryzen 7 PRO         | 26        | 0.34%   |
| AMD Athlon              | 26        | 0.34%   |
| Intel Pentium Dual      | 21        | 0.27%   |
| AMD Athlon II X2        | 19        | 0.25%   |
| Intel Core m3           | 16        | 0.21%   |
| AMD Ryzen 5 PRO         | 16        | 0.21%   |
| Intel Genuine           | 15        | 0.2%    |
| AMD Phenom II X6        | 12        | 0.16%   |
| AMD Athlon II X4        | 12        | 0.16%   |
| AMD Athlon 64 X2        | 12        | 0.16%   |
| AMD E1                  | 11        | 0.14%   |
| AMD E                   | 11        | 0.14%   |
| Intel Pentium Gold      | 9         | 0.12%   |
| AMD Phenom              | 9         | 0.12%   |
| AMD E2                  | 9         | 0.12%   |
| Intel Pentium Silver    | 8         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 2875      | 37.41%  |
| 2       | 2482      | 32.29%  |
| 6       | 1088      | 14.16%  |
| 8       | 814       | 10.59%  |
| 12      | 152       | 1.98%   |
| 16      | 69        | 0.9%    |
| 1       | 53        | 0.69%   |
| 3       | 46        | 0.6%    |
| 10      | 36        | 0.47%   |
| 14      | 26        | 0.34%   |
| 24      | 17        | 0.22%   |
| 32      | 16        | 0.21%   |
| Unknown | 4         | 0.05%   |
| 64      | 3         | 0.04%   |
| 28      | 1         | 0.01%   |
| 20      | 1         | 0.01%   |
| 18      | 1         | 0.01%   |
| 7       | 1         | 0.01%   |
| 5       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 7628      | 99.4%   |
| 2       | 42        | 0.55%   |
| Unknown | 4         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5830      | 75.88%  |
| 1       | 1849      | 24.07%  |
| Unknown | 4         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7650      | 99.69%  |
| 64-bit         | 13        | 0.17%   |
| Unknown        | 11        | 0.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5092      | 64.75%  |
| 0x906ea    | 184       | 2.34%   |
| 0x306a9    | 160       | 2.03%   |
| 0x206a7    | 142       | 1.81%   |
| 0x306c3    | 128       | 1.63%   |
| 0x806ec    | 116       | 1.48%   |
| 0x806ea    | 115       | 1.46%   |
| 0x806c1    | 96        | 1.22%   |
| 0x08701021 | 95        | 1.21%   |
| 0x406e3    | 89        | 1.13%   |
| 0x906e9    | 87        | 1.11%   |
| 0x40651    | 82        | 1.04%   |
| 0x806e9    | 75        | 0.95%   |
| 0x08701013 | 75        | 0.95%   |
| 0x506e3    | 73        | 0.93%   |
| 0x0800820d | 70        | 0.89%   |
| 0xa0652    | 66        | 0.84%   |
| 0x1067a    | 58        | 0.74%   |
| 0x08108109 | 48        | 0.61%   |
| 0x08108102 | 46        | 0.58%   |
| 0x906ed    | 43        | 0.55%   |
| 0x0a50000c | 41        | 0.52%   |
| 0x306d4    | 40        | 0.51%   |
| 0x806eb    | 36        | 0.46%   |
| 0x08600106 | 35        | 0.45%   |
| 0x806d1    | 32        | 0.41%   |
| 0x20655    | 29        | 0.37%   |
| 0x08001138 | 27        | 0.34%   |
| 0x706e5    | 26        | 0.33%   |
| 0x406c4    | 26        | 0.33%   |
| 0x0810100b | 25        | 0.32%   |
| 0x08600104 | 23        | 0.29%   |
| 0x06000852 | 23        | 0.29%   |
| 0x0a201016 | 19        | 0.24%   |
| 0x06006705 | 19        | 0.24%   |
| 0x06001119 | 19        | 0.24%   |
| 0x706a1    | 18        | 0.23%   |
| 0x08608103 | 18        | 0.23%   |
| 0x906a3    | 17        | 0.22%   |
| 0x08600103 | 17        | 0.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1444      | 18.79%  |
| Haswell          | 726       | 9.45%   |
| Zen 2            | 638       | 8.3%    |
| IvyBridge        | 549       | 7.14%   |
| SandyBridge      | 527       | 6.86%   |
| Skylake          | 437       | 5.69%   |
| Zen+             | 425       | 5.53%   |
| Zen 3            | 311       | 4.05%   |
| Penryn           | 292       | 3.8%    |
| CometLake        | 257       | 3.34%   |
| Zen              | 207       | 2.69%   |
| TigerLake        | 206       | 2.68%   |
| Unknown          | 205       | 2.67%   |
| Westmere         | 188       | 2.45%   |
| Broadwell        | 163       | 2.12%   |
| Piledriver       | 160       | 2.08%   |
| Silvermont       | 134       | 1.74%   |
| Core             | 129       | 1.68%   |
| K10              | 104       | 1.35%   |
| IceLake          | 100       | 1.3%    |
| Nehalem          | 85        | 1.11%   |
| Excavator        | 81        | 1.05%   |
| Goldmont plus    | 60        | 0.78%   |
| Puma             | 39        | 0.51%   |
| Steamroller      | 35        | 0.46%   |
| Goldmont         | 30        | 0.39%   |
| K8 Hammer        | 29        | 0.38%   |
| Bobcat           | 26        | 0.34%   |
| K10 Llano        | 25        | 0.33%   |
| Alderlake Hybrid | 21        | 0.27%   |
| Jaguar           | 18        | 0.23%   |
| Bulldozer        | 13        | 0.17%   |
| NetBurst         | 8         | 0.1%    |
| K8 & K10 hybrid  | 7         | 0.09%   |
| Bonnell          | 6         | 0.08%   |
| Tremont          | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4022      | 43.04%  |
| Nvidia                           | 3141      | 33.61%  |
| AMD                              | 2157      | 23.08%  |
| Matrox Electronics Systems       | 13        | 0.14%   |
| Silicon Integrated Systems [SiS] | 8         | 0.09%   |
| ASPEED Technology                | 3         | 0.03%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 369       | 3.85%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 299       | 3.12%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 296       | 3.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 240       | 2.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 238       | 2.48%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 232       | 2.42%   |
| Intel UHD Graphics 620                                                                   | 206       | 2.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 194       | 2.02%   |
| AMD Renoir                                                                               | 184       | 1.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 168       | 1.75%   |
| Intel HD Graphics 620                                                                    | 151       | 1.58%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 148       | 1.54%   |
| Intel HD Graphics 630                                                                    | 140       | 1.46%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 140       | 1.46%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 136       | 1.42%   |
| AMD Cezanne                                                                              | 123       | 1.28%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 122       | 1.27%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 114       | 1.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 110       | 1.15%   |
| Intel HD Graphics 5500                                                                   | 108       | 1.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 108       | 1.13%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 104       | 1.09%   |
| Intel HD Graphics 530                                                                    | 103       | 1.07%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 100       | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 89        | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 83        | 0.87%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 80        | 0.83%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 79        | 0.82%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 72        | 0.75%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 70        | 0.73%   |
| AMD Lucienne                                                                             | 66        | 0.69%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 62        | 0.65%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 61        | 0.64%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 61        | 0.64%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 61        | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 59        | 0.62%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 56        | 0.58%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 54        | 0.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 53        | 0.55%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 52        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 2621      | 33.81%  |
| 1 x Nvidia              | 1756      | 22.66%  |
| 1 x AMD                 | 1650      | 21.29%  |
| Intel + Nvidia          | 1125      | 14.51%  |
| AMD + Nvidia            | 197       | 2.54%   |
| Intel + AMD             | 189       | 2.44%   |
| 2 x AMD                 | 124       | 1.6%    |
| 2 x Nvidia              | 41        | 0.53%   |
| Other                   | 17        | 0.22%   |
| 1 x SiS                 | 8         | 0.1%    |
| 1 x Matrox              | 7         | 0.09%   |
| Nvidia + Matrox         | 3         | 0.04%   |
| Nvidia + ASPEED         | 3         | 0.04%   |
| AMD + Matrox            | 2         | 0.03%   |
| 5 x Nvidia              | 1         | 0.01%   |
| 4 x Nvidia              | 1         | 0.01%   |
| 3 x Nvidia              | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia    | 1         | 0.01%   |
| 1 x S3 Graphics         | 1         | 0.01%   |
| Intel + 2 x Nvidia      | 1         | 0.01%   |
| AMD + 2 x Nvidia        | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4895      | 63.09%  |
| Proprietary | 2525      | 32.54%  |
| Unknown     | 339       | 4.37%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5062      | 64.71%  |
| 1.01-2.0   | 613       | 7.84%   |
| 3.01-4.0   | 579       | 7.4%    |
| 7.01-8.0   | 529       | 6.76%   |
| 5.01-6.0   | 402       | 5.14%   |
| 0.01-0.5   | 229       | 2.93%   |
| 0.51-1.0   | 174       | 2.22%   |
| 8.01-16.0  | 132       | 1.69%   |
| 2.01-3.0   | 80        | 1.02%   |
| 16.01-24.0 | 17        | 0.22%   |
| 4.01-5.0   | 3         | 0.04%   |
| 32.01-64.0 | 1         | 0.01%   |
| 24.01-32.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1062      | 12.21%  |
| AU Optronics            | 946       | 10.87%  |
| LG Display              | 750       | 8.62%   |
| Chimei Innolux          | 743       | 8.54%   |
| BOE                     | 649       | 7.46%   |
| Goldstar                | 574       | 6.6%    |
| Dell                    | 543       | 6.24%   |
| Acer                    | 356       | 4.09%   |
| Hewlett-Packard         | 270       | 3.1%    |
| AOC                     | 250       | 2.87%   |
| Apple                   | 247       | 2.84%   |
| Ancor Communications    | 207       | 2.38%   |
| Sharp                   | 203       | 2.33%   |
| BenQ                    | 198       | 2.28%   |
| Philips                 | 138       | 1.59%   |
| ASUSTek Computer        | 131       | 1.51%   |
| Lenovo                  | 126       | 1.45%   |
| PANDA                   | 121       | 1.39%   |
| ViewSonic               | 81        | 0.93%   |
| Chi Mei Optoelectronics | 78        | 0.9%    |
| Sony                    | 62        | 0.71%   |
| Iiyama                  | 61        | 0.7%    |
| InfoVision              | 48        | 0.55%   |
| MSI                     | 47        | 0.54%   |
| Sceptre Tech            | 44        | 0.51%   |
| Vizio                   | 40        | 0.46%   |
| Panasonic               | 37        | 0.43%   |
| Toshiba                 | 30        | 0.34%   |
| CSO                     | 23        | 0.26%   |
| Unknown                 | 22        | 0.25%   |
| Gigabyte Technology     | 22        | 0.25%   |
| Eizo                    | 18        | 0.21%   |
| Insignia                | 17        | 0.2%    |
| LG Electronics          | 16        | 0.18%   |
| Fujitsu Siemens         | 16        | 0.18%   |
| Vestel Elektronik       | 15        | 0.17%   |
| NEC Computers           | 15        | 0.17%   |
| MStar                   | 15        | 0.17%   |
| Hitachi                 | 15        | 0.17%   |
| LG Philips              | 13        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch               | 64        | 0.71%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 54        | 0.6%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 54        | 0.6%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 41        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 39        | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch       | 38        | 0.42%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 37        | 0.41%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch          | 34        | 0.38%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 33        | 0.37%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 32        | 0.36%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 27        | 0.3%    |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch  | 26        | 0.29%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch           | 25        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch        | 24        | 0.27%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                 | 23        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 23        | 0.26%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch         | 23        | 0.26%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 22        | 0.25%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 22        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 22        | 0.25%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch       | 22        | 0.25%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 21        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 21        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch        | 20        | 0.22%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch        | 20        | 0.22%   |
| AOC 24V2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 20        | 0.22%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 19        | 0.21%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch          | 19        | 0.21%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 19        | 0.21%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch           | 18        | 0.2%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 18        | 0.2%    |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                      | 18        | 0.2%    |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch       | 18        | 0.2%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                  | 17        | 0.19%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch               | 16        | 0.18%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch          | 16        | 0.18%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 15        | 0.17%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                | 15        | 0.17%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                | 15        | 0.17%   |
| MSI G241VC MSI1462 1920x1080 521x294mm 23.6-inch                       | 15        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3875      | 47.28%  |
| 1366x768 (WXGA)    | 1321      | 16.12%  |
| 3840x2160 (4K)     | 695       | 8.48%   |
| 2560x1440 (QHD)    | 481       | 5.87%   |
| 1600x900 (HD+)     | 272       | 3.32%   |
| 1920x1200 (WUXGA)  | 173       | 2.11%   |
| 1680x1050 (WSXGA+) | 165       | 2.01%   |
| 1440x900 (WXGA+)   | 159       | 1.94%   |
| 2560x1080          | 154       | 1.88%   |
| 3440x1440          | 146       | 1.78%   |
| 1280x1024 (SXGA)   | 141       | 1.72%   |
| 1280x800 (WXGA)    | 113       | 1.38%   |
| 2560x1600          | 64        | 0.78%   |
| 1360x768           | 55        | 0.67%   |
| 2880x1800          | 44        | 0.54%   |
| 1920x540           | 40        | 0.49%   |
| 3840x1080          | 36        | 0.44%   |
| Unknown            | 30        | 0.37%   |
| 3840x2400          | 27        | 0.33%   |
| 2160x1440          | 27        | 0.33%   |
| 3200x1800 (QHD+)   | 15        | 0.18%   |
| 2736x1824          | 15        | 0.18%   |
| 3000x2000          | 14        | 0.17%   |
| 2256x1504          | 13        | 0.16%   |
| 1024x768 (XGA)     | 13        | 0.16%   |
| 3840x1600          | 12        | 0.15%   |
| 1280x720 (HD)      | 11        | 0.13%   |
| 1600x1200          | 10        | 0.12%   |
| 3456x2160          | 6         | 0.07%   |
| 2048x1152          | 5         | 0.06%   |
| 3840x1200          | 4         | 0.05%   |
| 3200x2000          | 4         | 0.05%   |
| 1920x1280          | 4         | 0.05%   |
| 3840x1100          | 3         | 0.04%   |
| 3072x1920          | 3         | 0.04%   |
| 2288x1287          | 3         | 0.04%   |
| 7680x2160          | 2         | 0.02%   |
| 5120x1440          | 2         | 0.02%   |
| 4480x1440          | 2         | 0.02%   |
| 3280x1080          | 2         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2205      | 25.42%  |
| 13      | 832       | 9.59%   |
| 27      | 793       | 9.14%   |
| 24      | 681       | 7.85%   |
| 14      | 589       | 6.79%   |
| 23      | 550       | 6.34%   |
| 21      | 455       | 5.25%   |
| 17      | 445       | 5.13%   |
| 31      | 279       | 3.22%   |
| 34      | 252       | 2.91%   |
| 19      | 163       | 1.88%   |
| Unknown | 153       | 1.76%   |
| 18      | 144       | 1.66%   |
| 12      | 129       | 1.49%   |
| 22      | 113       | 1.3%    |
| 20      | 102       | 1.18%   |
| 84      | 85        | 0.98%   |
| 32      | 77        | 0.89%   |
| 11      | 72        | 0.83%   |
| 72      | 65        | 0.75%   |
| 16      | 52        | 0.6%    |
| 54      | 41        | 0.47%   |
| 26      | 37        | 0.43%   |
| 25      | 34        | 0.39%   |
| 48      | 30        | 0.35%   |
| 40      | 30        | 0.35%   |
| 49      | 23        | 0.27%   |
| 35      | 23        | 0.27%   |
| 52      | 22        | 0.25%   |
| 28      | 21        | 0.24%   |
| 65      | 20        | 0.23%   |
| 46      | 19        | 0.22%   |
| 37      | 14        | 0.16%   |
| 29      | 14        | 0.16%   |
| 47      | 11        | 0.13%   |
| 33      | 11        | 0.13%   |
| 43      | 9         | 0.1%    |
| 42      | 8         | 0.09%   |
| 10      | 8         | 0.09%   |
| 39      | 7         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 3239      | 38.16%  |
| 501-600        | 1825      | 21.5%   |
| 401-500        | 882       | 10.39%  |
| 201-300        | 627       | 7.39%   |
| 351-400        | 545       | 6.42%   |
| 601-700        | 424       | 4.99%   |
| 701-800        | 339       | 3.99%   |
| 1001-1500      | 188       | 2.21%   |
| 1501-2000      | 161       | 1.9%    |
| Unknown        | 153       | 1.8%    |
| 801-900        | 80        | 0.94%   |
| 901-1000       | 23        | 0.27%   |
| More than 2000 | 2         | 0.02%   |
| 101-200        | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 6094      | 80.04%  |
| 16/10   | 804       | 10.56%  |
| 21/9    | 303       | 3.98%   |
| 5/4     | 137       | 1.8%    |
| Unknown | 92        | 1.21%   |
| 3/2     | 82        | 1.08%   |
| 32/9    | 39        | 0.51%   |
| 4/3     | 38        | 0.5%    |
| 6/5     | 9         | 0.12%   |
| 1.96    | 5         | 0.07%   |
| 3.40    | 3         | 0.04%   |
| 3.20    | 3         | 0.04%   |
| 3.73    | 2         | 0.03%   |
| 0.62    | 2         | 0.03%   |
| 1.00    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2206      | 25.74%  |
| 201-250        | 1419      | 16.56%  |
| 81-90          | 1120      | 13.07%  |
| 301-350        | 815       | 9.51%   |
| 351-500        | 643       | 7.5%    |
| 151-200        | 405       | 4.73%   |
| 121-130        | 360       | 4.2%    |
| 71-80          | 310       | 3.62%   |
| More than 1000 | 281       | 3.28%   |
| 251-300        | 255       | 2.98%   |
| 141-150        | 179       | 2.09%   |
| Unknown        | 153       | 1.79%   |
| 501-1000       | 152       | 1.77%   |
| 61-70          | 112       | 1.31%   |
| 51-60          | 75        | 0.88%   |
| 111-120        | 39        | 0.46%   |
| 131-140        | 25        | 0.29%   |
| 91-100         | 12        | 0.14%   |
| 41-50          | 8         | 0.09%   |
| 1-40           | 1         | 0.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2626      | 31.82%  |
| 121-160       | 2394      | 29.01%  |
| 101-120       | 2100      | 25.45%  |
| 161-240       | 487       | 5.9%    |
| More than 240 | 252       | 3.05%   |
| 1-50          | 240       | 2.91%   |
| Unknown       | 153       | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 5850      | 74.5%   |
| 2     | 1429      | 18.2%   |
| 0     | 394       | 5.02%   |
| 3     | 163       | 2.08%   |
| 4     | 14        | 0.18%   |
| 6     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4185      | 35.27%  |
| Intel                             | 3944      | 33.24%  |
| Qualcomm Atheros                  | 1290      | 10.87%  |
| Broadcom                          | 702       | 5.92%   |
| Broadcom Limited                  | 156       | 1.31%   |
| TP-Link                           | 134       | 1.13%   |
| Ralink Technology                 | 131       | 1.1%    |
| Marvell Technology Group          | 119       | 1%      |
| MediaTek                          | 116       | 0.98%   |
| Nvidia                            | 111       | 0.94%   |
| Ralink                            | 92        | 0.78%   |
| Samsung Electronics               | 72        | 0.61%   |
| Microsoft                         | 69        | 0.58%   |
| ASIX Electronics                  | 50        | 0.42%   |
| NetGear                           | 43        | 0.36%   |
| Qualcomm Atheros Communications   | 37        | 0.31%   |
| Xiaomi                            | 36        | 0.3%    |
| DisplayLink                       | 34        | 0.29%   |
| Google                            | 32        | 0.27%   |
| Aquantia                          | 32        | 0.27%   |
| InterBiometrics                   | 30        | 0.25%   |
| Huawei Technologies               | 27        | 0.23%   |
| ASUSTek Computer                  | 27        | 0.23%   |
| Dell                              | 26        | 0.22%   |
| D-Link                            | 25        | 0.21%   |
| Lenovo                            | 24        | 0.2%    |
| Sierra Wireless                   | 21        | 0.18%   |
| Ericsson Business Mobile Networks | 20        | 0.17%   |
| Linksys                           | 19        | 0.16%   |
| Qualcomm                          | 18        | 0.15%   |
| JMicron Technology                | 16        | 0.13%   |
| Motorola PCS                      | 14        | 0.12%   |
| Edimax Technology                 | 14        | 0.12%   |
| OnePlus                           | 13        | 0.11%   |
| Hewlett-Packard                   | 12        | 0.1%    |
| OPPO Electronics                  | 11        | 0.09%   |
| D-Link System                     | 10        | 0.08%   |
| Silicon Integrated Systems [SiS]  | 9         | 0.08%   |
| Belkin Components                 | 9         | 0.08%   |
| Apple                             | 8         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2927      | 21.07%  |
| Intel Wi-Fi 6 AX200                                               | 596       | 4.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 428       | 3.08%   |
| Intel I211 Gigabit Network Connection                             | 362       | 2.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 278       | 2%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 244       | 1.76%   |
| Intel Wireless 8265 / 8275                                        | 234       | 1.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 226       | 1.63%   |
| Realtek RTL8125 2.5GbE Controller                                 | 201       | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 194       | 1.4%    |
| Intel Wireless 7265                                               | 175       | 1.26%   |
| Intel Wireless 7260                                               | 169       | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 162       | 1.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 160       | 1.15%   |
| Intel Wi-Fi 6 AX201                                               | 157       | 1.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 154       | 1.11%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 146       | 1.05%   |
| Intel Wireless-AC 9260                                            | 143       | 1.03%   |
| Intel Wireless 8260                                               | 141       | 1.01%   |
| Intel Ethernet Connection (2) I219-V                              | 141       | 1.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 128       | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 128       | 0.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 120       | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 120       | 0.86%   |
| Intel Ethernet Connection I217-LM                                 | 108       | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 102       | 0.73%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 101       | 0.73%   |
| Intel Ethernet Controller I225-V                                  | 100       | 0.72%   |
| Intel Ethernet Connection (7) I219-V                              | 100       | 0.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 96        | 0.69%   |
| Intel Wireless 3165                                               | 93        | 0.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 77        | 0.55%   |
| Broadcom BCM43142 802.11b/g/n                                     | 77        | 0.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 72        | 0.52%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 70        | 0.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 69        | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 67        | 0.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 66        | 0.48%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 66        | 0.48%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 65        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 3091      | 47.15%  |
| Qualcomm Atheros                      | 997       | 15.21%  |
| Realtek Semiconductor                 | 979       | 14.94%  |
| Broadcom                              | 534       | 8.15%   |
| Ralink Technology                     | 131       | 2%      |
| TP-Link                               | 124       | 1.89%   |
| Broadcom Limited                      | 120       | 1.83%   |
| MediaTek                              | 107       | 1.63%   |
| Ralink                                | 92        | 1.4%    |
| Microsoft                             | 64        | 0.98%   |
| NetGear                               | 41        | 0.63%   |
| Qualcomm Atheros Communications       | 37        | 0.56%   |
| Marvell Technology Group              | 32        | 0.49%   |
| ASUSTek Computer                      | 25        | 0.38%   |
| D-Link                                | 24        | 0.37%   |
| Dell                                  | 23        | 0.35%   |
| Sierra Wireless                       | 21        | 0.32%   |
| Linksys                               | 15        | 0.23%   |
| Edimax Technology                     | 14        | 0.21%   |
| Qualcomm                              | 12        | 0.18%   |
| Belkin Components                     | 9         | 0.14%   |
| AVM                                   | 7         | 0.11%   |
| Sitecom Europe                        | 6         | 0.09%   |
| Fibocom                               | 6         | 0.09%   |
| D-Link System                         | 6         | 0.09%   |
| Gemtek                                | 5         | 0.08%   |
| Mercucys                              | 4         | 0.06%   |
| Hewlett-Packard                       | 4         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4         | 0.06%   |
| IMC Networks                          | 3         | 0.05%   |
| Wilocity                              | 2         | 0.03%   |
| Samsung Electronics                   | 2         | 0.03%   |
| Ovislink                              | 2         | 0.03%   |
| Micro Star International              | 2         | 0.03%   |
| Accton Technology                     | 2         | 0.03%   |
| ZyDAS                                 | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| TRENDnet                              | 1         | 0.02%   |
| Texas Instruments                     | 1         | 0.02%   |
| Philips (or NXP)                      | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 596       | 9.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 244       | 3.69%   |
| Intel Wireless 8265 / 8275                                     | 234       | 3.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 194       | 2.94%   |
| Intel Wireless 7265                                            | 175       | 2.65%   |
| Intel Wireless 7260                                            | 169       | 2.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 162       | 2.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 160       | 2.42%   |
| Intel Wi-Fi 6 AX201                                            | 157       | 2.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 154       | 2.33%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 146       | 2.21%   |
| Intel Wireless-AC 9260                                         | 143       | 2.17%   |
| Intel Wireless 8260                                            | 141       | 2.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 128       | 1.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 128       | 1.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 120       | 1.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 120       | 1.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 102       | 1.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 101       | 1.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 96        | 1.45%   |
| Intel Wireless 3165                                            | 93        | 1.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 77        | 1.17%   |
| Broadcom BCM43142 802.11b/g/n                                  | 77        | 1.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 72        | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 70        | 1.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 69        | 1.04%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 66        | 1%      |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 65        | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 64        | 0.97%   |
| Realtek 802.11ac NIC                                           | 59        | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 59        | 0.89%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 58        | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 58        | 0.88%   |
| Intel Wireless 3160                                            | 55        | 0.83%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 54        | 0.82%   |
| Ralink MT7601U Wireless Adapter                                | 48        | 0.73%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 46        | 0.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 45        | 0.68%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 45        | 0.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 44        | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 3799      | 53.94%  |
| Intel                            | 1868      | 26.52%  |
| Qualcomm Atheros                 | 398       | 5.65%   |
| Broadcom                         | 291       | 4.13%   |
| Nvidia                           | 111       | 1.58%   |
| Marvell Technology Group         | 87        | 1.24%   |
| Samsung Electronics              | 70        | 0.99%   |
| ASIX Electronics                 | 50        | 0.71%   |
| Broadcom Limited                 | 40        | 0.57%   |
| Xiaomi                           | 36        | 0.51%   |
| DisplayLink                      | 34        | 0.48%   |
| Google                           | 32        | 0.45%   |
| Aquantia                         | 32        | 0.45%   |
| Huawei Technologies              | 24        | 0.34%   |
| Lenovo                           | 23        | 0.33%   |
| JMicron Technology               | 16        | 0.23%   |
| OnePlus                          | 13        | 0.18%   |
| OPPO Electronics                 | 11        | 0.16%   |
| TP-Link                          | 10        | 0.14%   |
| Motorola PCS                     | 10        | 0.14%   |
| Silicon Integrated Systems [SiS] | 9         | 0.13%   |
| MediaTek                         | 8         | 0.11%   |
| Qualcomm                         | 6         | 0.09%   |
| Apple                            | 6         | 0.09%   |
| Microsoft                        | 5         | 0.07%   |
| ICS Advent                       | 5         | 0.07%   |
| VIA Technologies                 | 4         | 0.06%   |
| Linksys                          | 4         | 0.06%   |
| D-Link System                    | 4         | 0.06%   |
| Mellanox Technologies            | 3         | 0.04%   |
| LG Electronics                   | 3         | 0.04%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.03%   |
| T & A Mobile Phones              | 2         | 0.03%   |
| NetGear                          | 2         | 0.03%   |
| LSI                              | 2         | 0.03%   |
| Hewlett-Packard                  | 2         | 0.03%   |
| ASUSTek Computer                 | 2         | 0.03%   |
| 3Com                             | 2         | 0.03%   |
| Unknown                          | 1         | 0.01%   |
| Tehuti Networks                  | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2927      | 40.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 428       | 5.97%   |
| Intel I211 Gigabit Network Connection                             | 362       | 5.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 278       | 3.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 226       | 3.15%   |
| Realtek RTL8125 2.5GbE Controller                                 | 201       | 2.8%    |
| Intel Ethernet Connection (2) I219-V                              | 141       | 1.97%   |
| Intel Ethernet Connection I217-LM                                 | 108       | 1.51%   |
| Intel Ethernet Controller I225-V                                  | 100       | 1.39%   |
| Intel Ethernet Connection (7) I219-V                              | 100       | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 67        | 0.93%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 66        | 0.92%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 63        | 0.88%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 54        | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 53        | 0.74%   |
| Intel 82579V Gigabit Network Connection                           | 53        | 0.74%   |
| Nvidia MCP79 Ethernet                                             | 51        | 0.71%   |
| Intel Ethernet Connection I218-LM                                 | 50        | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 49        | 0.68%   |
| Intel Ethernet Connection I219-LM                                 | 48        | 0.67%   |
| Intel Ethernet Connection I217-V                                  | 44        | 0.61%   |
| Intel Ethernet Connection (2) I218-V                              | 42        | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 41        | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                             | 41        | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 40        | 0.56%   |
| ASIX AX88179 Gigabit Ethernet                                     | 37        | 0.52%   |
| Nvidia MCP61 Ethernet                                             | 35        | 0.49%   |
| Intel Ethernet Connection (4) I219-V                              | 34        | 0.47%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 34        | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 33        | 0.46%   |
| Intel Ethernet Connection (3) I218-LM                             | 32        | 0.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 32        | 0.45%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 30        | 0.42%   |
| Intel Ethernet Connection (6) I219-V                              | 29        | 0.4%    |
| Intel 82577LM Gigabit Network Connection                          | 29        | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                             | 28        | 0.39%   |
| Intel I210 Gigabit Network Connection                             | 27        | 0.38%   |
| Google Nexus/Pixel Device (tether)                                | 26        | 0.36%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 26        | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 25        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 6568      | 51.06%  |
| WiFi     | 6183      | 48.06%  |
| Modem    | 88        | 0.68%   |
| Unknown  | 25        | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4777      | 58.8%   |
| Ethernet | 3343      | 41.15%  |
| Unknown  | 4         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 4295      | 55.8%   |
| 1     | 3083      | 40.05%  |
| 3     | 182       | 2.36%   |
| 0     | 100       | 1.3%    |
| 4     | 28        | 0.36%   |
| 5     | 5         | 0.06%   |
| 10    | 2         | 0.03%   |
| 6     | 2         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6243      | 80.23%  |
| Yes  | 1538      | 19.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2675      | 51.56%  |
| Qualcomm Atheros Communications | 414       | 7.98%   |
| Realtek Semiconductor           | 394       | 7.59%   |
| Apple                           | 300       | 5.78%   |
| Cambridge Silicon Radio         | 298       | 5.74%   |
| Broadcom                        | 240       | 4.63%   |
| IMC Networks                    | 204       | 3.93%   |
| Lite-On Technology              | 180       | 3.47%   |
| Foxconn / Hon Hai               | 109       | 2.1%    |
| ASUSTek Computer                | 93        | 1.79%   |
| Dell                            | 61        | 1.18%   |
| Marvell Semiconductor           | 34        | 0.66%   |
| Ralink                          | 30        | 0.58%   |
| Realtek                         | 27        | 0.52%   |
| Toshiba                         | 26        | 0.5%    |
| Hewlett-Packard                 | 26        | 0.5%    |
| Foxconn International           | 10        | 0.19%   |
| Ralink Technology               | 7         | 0.13%   |
| Alps Electric                   | 7         | 0.13%   |
| TP-Link                         | 6         | 0.12%   |
| MediaTek                        | 6         | 0.12%   |
| HTC (High Tech Computer)        | 4         | 0.08%   |
| Dynex                           | 4         | 0.08%   |
| Askey Computer                  | 4         | 0.08%   |
| USI                             | 3         | 0.06%   |
| Taiyo Yuden                     | 3         | 0.06%   |
| Qcom                            | 3         | 0.06%   |
| Creative Technology             | 3         | 0.06%   |
| Unknown                         | 2         | 0.04%   |
| SINO WEALTH                     | 2         | 0.04%   |
| Opticis                         | 2         | 0.04%   |
| Integrated System Solution      | 2         | 0.04%   |
| Conwise Technology              | 2         | 0.04%   |
| Belkin Components               | 2         | 0.04%   |
| Primax Electronics              | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Logitech                        | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| Edimax Technology               | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 843       | 16.24%  |
| Intel AX200 Bluetooth                               | 571       | 11%     |
| Intel AX201 Bluetooth                               | 430       | 8.28%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 389       | 7.49%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 298       | 5.74%   |
| Realtek Bluetooth Radio                             | 236       | 4.55%   |
| Qualcomm Atheros  Bluetooth Device                  | 225       | 4.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 133       | 2.56%   |
| Apple Bluetooth Host Controller                     | 127       | 2.45%   |
| Intel Wireless-AC 3168 Bluetooth                    | 119       | 2.29%   |
| Apple Bluetooth USB Host Controller                 | 109       | 2.1%    |
| Realtek  Bluetooth 4.2 Adapter                      | 108       | 2.08%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 70        | 1.35%   |
| Intel AX210 Bluetooth                               | 69        | 1.33%   |
| IMC Networks Bluetooth Radio                        | 65        | 1.25%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 62        | 1.19%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 53        | 1.02%   |
| IMC Networks Wireless_Device                        | 50        | 0.96%   |
| Foxconn / Hon Hai Bluetooth Device                  | 50        | 0.96%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 50        | 0.96%   |
| IMC Networks Bluetooth Device                       | 47        | 0.91%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 43        | 0.83%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 42        | 0.81%   |
| Lite-On Bluetooth Device                            | 41        | 0.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 35        | 0.67%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 35        | 0.67%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 34        | 0.65%   |
| Ralink RT3290 Bluetooth                             | 30        | 0.58%   |
| Intel Bluetooth Device                              | 29        | 0.56%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 29        | 0.56%   |
| Apple Bluetooth HCI                                 | 29        | 0.56%   |
| Broadcom BCM2045B (BDC-2.1)                         | 28        | 0.54%   |
| Realtek Bluetooth Radio                             | 27        | 0.52%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 24        | 0.46%   |
| Marvell Bluetooth and Wireless LAN Composite        | 22        | 0.42%   |
| Dell DW375 Bluetooth Module                         | 22        | 0.42%   |
| Lite-On Atheros AR3012 Bluetooth                    | 21        | 0.4%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 20        | 0.39%   |
| Foxconn / Hon Hai Wireless_Device                   | 20        | 0.39%   |
| ASUS Bluetooth Radio                                | 20        | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 5228      | 44.72%  |
| AMD                                             | 2567      | 21.96%  |
| Nvidia                                          | 2488      | 21.28%  |
| C-Media Electronics                             | 209       | 1.79%   |
| Logitech                                        | 117       | 1%      |
| JMTek                                           | 64        | 0.55%   |
| Creative Labs                                   | 60        | 0.51%   |
| Kingston Technology                             | 56        | 0.48%   |
| Corsair                                         | 54        | 0.46%   |
| Texas Instruments                               | 52        | 0.44%   |
| Razer USA                                       | 51        | 0.44%   |
| Realtek Semiconductor                           | 45        | 0.38%   |
| SteelSeries ApS                                 | 41        | 0.35%   |
| Focusrite-Novation                              | 35        | 0.3%    |
| GN Netcom                                       | 32        | 0.27%   |
| Creative Technology                             | 29        | 0.25%   |
| Blue Microphones                                | 27        | 0.23%   |
| ASUSTek Computer                                | 27        | 0.23%   |
| Generalplus Technology                          | 25        | 0.21%   |
| Lenovo                                          | 23        | 0.2%    |
| Sony                                            | 20        | 0.17%   |
| Plantronics                                     | 18        | 0.15%   |
| Astro Gaming                                    | 16        | 0.14%   |
| Apple                                           | 16        | 0.14%   |
| Sennheiser Communications                       | 15        | 0.13%   |
| Samson Technologies                             | 14        | 0.12%   |
| Giga-Byte Technology                            | 14        | 0.12%   |
| Turtle Beach                                    | 12        | 0.1%    |
| Tenx Technology                                 | 12        | 0.1%    |
| Yamaha                                          | 11        | 0.09%   |
| Thesycon Systemsoftware & Consulting            | 10        | 0.09%   |
| Silicon Integrated Systems [SiS]                | 10        | 0.09%   |
| SAVITECH                                        | 10        | 0.09%   |
| M-Audio                                         | 10        | 0.09%   |
| Hewlett-Packard                                 | 10        | 0.09%   |
| Valve Software                                  | 9         | 0.08%   |
| FiiO Electronics Technology                     | 9         | 0.08%   |
| Micro Star International                        | 8         | 0.07%   |
| Licensed by Sony Computer Entertainment America | 8         | 0.07%   |
| Audio-Technica                                  | 8         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 757       | 5.46%   |
| AMD Starship/Matisse HD Audio Controller                                   | 598       | 4.31%   |
| Intel Sunrise Point-LP HD Audio                                            | 583       | 4.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 521       | 3.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 489       | 3.53%   |
| Intel Cannon Lake PCH cAVS                                                 | 442       | 3.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 374       | 2.7%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 323       | 2.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 294       | 2.12%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 273       | 1.97%   |
| Intel 8 Series HD Audio Controller                                         | 242       | 1.75%   |
| Intel Haswell-ULT HD Audio Controller                                      | 238       | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 236       | 1.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 234       | 1.69%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 232       | 1.67%   |
| Nvidia GP107GL High Definition Audio Controller                            | 219       | 1.58%   |
| Nvidia TU106 High Definition Audio Controller                              | 214       | 1.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 206       | 1.49%   |
| AMD FCH Azalia Controller                                                  | 195       | 1.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 193       | 1.39%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 192       | 1.39%   |
| Intel Comet Lake PCH cAVS                                                  | 188       | 1.36%   |
| Nvidia GP104 High Definition Audio Controller                              | 184       | 1.33%   |
| Nvidia GP106 High Definition Audio Controller                              | 174       | 1.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 169       | 1.22%   |
| Nvidia TU116 High Definition Audio Controller                              | 163       | 1.18%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 163       | 1.18%   |
| Intel 200 Series PCH HD Audio                                              | 163       | 1.18%   |
| Intel Comet Lake PCH-LP cAVS                                               | 159       | 1.15%   |
| Intel Broadwell-U Audio Controller                                         | 157       | 1.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 148       | 1.07%   |
| AMD Navi 10 HDMI Audio                                                     | 142       | 1.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 138       | 1%      |
| Intel CM238 HD Audio Controller                                            | 129       | 0.93%   |
| Nvidia TU104 HD Audio Controller                                           | 124       | 0.89%   |
| Nvidia GA104 High Definition Audio Controller                              | 113       | 0.82%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 108       | 0.78%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 105       | 0.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 93        | 0.67%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 89        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 466       | 22.9%   |
| SK hynix            | 356       | 17.49%  |
| Kingston            | 223       | 10.96%  |
| Micron Technology   | 214       | 10.52%  |
| Corsair             | 150       | 7.37%   |
| Crucial             | 141       | 6.93%   |
| Unknown             | 103       | 5.06%   |
| G.Skill             | 94        | 4.62%   |
| A-DATA Technology   | 48        | 2.36%   |
| Smart               | 29        | 1.43%   |
| Ramaxel Technology  | 27        | 1.33%   |
| Team                | 25        | 1.23%   |
| Elpida              | 20        | 0.98%   |
| Goldkey             | 17        | 0.84%   |
| Neo Forza           | 16        | 0.79%   |
| Unknown (ABCD)      | 11        | 0.54%   |
| Patriot             | 10        | 0.49%   |
| Smart Brazil        | 9         | 0.44%   |
| Unknown             | 9         | 0.44%   |
| Teikon              | 7         | 0.34%   |
| Nanya Technology    | 6         | 0.29%   |
| Apacer              | 6         | 0.29%   |
| Avant               | 5         | 0.25%   |
| Silicon Power       | 3         | 0.15%   |
| High Bridge         | 3         | 0.15%   |
| GOODRAM             | 3         | 0.15%   |
| Transcend           | 2         | 0.1%    |
| Timetec             | 2         | 0.1%    |
| PNY                 | 2         | 0.1%    |
| Patriot Memory      | 2         | 0.1%    |
| OLOY                | 2         | 0.1%    |
| GSkill              | 2         | 0.1%    |
| Gold Key            | 2         | 0.1%    |
| CSX                 | 2         | 0.1%    |
| AMD                 | 2         | 0.1%    |
| Unknown (8A02)      | 1         | 0.05%   |
| Unknown (898F)      | 1         | 0.05%   |
| Unifosa             | 1         | 0.05%   |
| Toshiba             | 1         | 0.05%   |
| RZX                 | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 35        | 1.63%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 29        | 1.35%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 27        | 1.26%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 22        | 1.03%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 19        | 0.89%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 18        | 0.84%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 18        | 0.84%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 17        | 0.79%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 17        | 0.79%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 15        | 0.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 15        | 0.7%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.65%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 12        | 0.56%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.56%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.56%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 12        | 0.56%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 11        | 0.51%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.51%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 11        | 0.51%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.47%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 10        | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 9         | 0.42%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 0.42%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s        | 9         | 0.42%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 9         | 0.42%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.42%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 9         | 0.42%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 9         | 0.42%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 9         | 0.42%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 9         | 0.42%   |
| Unknown                                                          | 9         | 0.42%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 0.37%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.37%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.37%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 8         | 0.37%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 8         | 0.37%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 8         | 0.37%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 8         | 0.37%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1186      | 67.85%  |
| DDR3    | 353       | 20.19%  |
| LPDDR4  | 69        | 3.95%   |
| LPDDR3  | 63        | 3.6%    |
| Unknown | 23        | 1.32%   |
| DDR2    | 21        | 1.2%    |
| DDR5    | 12        | 0.69%   |
| SDRAM   | 11        | 0.63%   |
| LPDDR5  | 8         | 0.46%   |
| DDR     | 2         | 0.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1079      | 61.13%  |
| DIMM         | 495       | 28.05%  |
| Row Of Chips | 178       | 10.08%  |
| Chip         | 11        | 0.62%   |
| RIMM         | 1         | 0.06%   |
| Unknown      | 1         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 859       | 45.31%  |
| 4096  | 450       | 23.73%  |
| 16384 | 374       | 19.73%  |
| 2048  | 101       | 5.33%   |
| 32768 | 94        | 4.96%   |
| 1024  | 16        | 0.84%   |
| 512   | 2         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 424       | 22.34%  |
| 3200    | 367       | 19.34%  |
| 1600    | 252       | 13.28%  |
| 2400    | 177       | 9.33%   |
| 2133    | 107       | 5.64%   |
| 3600    | 99        | 5.22%   |
| 1333    | 70        | 3.69%   |
| 4267    | 35        | 1.84%   |
| 1867    | 35        | 1.84%   |
| 3266    | 29        | 1.53%   |
| 3000    | 26        | 1.37%   |
| 1334    | 25        | 1.32%   |
| 8400    | 18        | 0.95%   |
| 3400    | 18        | 0.95%   |
| 800     | 17        | 0.9%    |
| 4800    | 14        | 0.74%   |
| 3866    | 14        | 0.74%   |
| 3466    | 14        | 0.74%   |
| 3733    | 12        | 0.63%   |
| 3800    | 11        | 0.58%   |
| 2933    | 11        | 0.58%   |
| 1866    | 11        | 0.58%   |
| 667     | 11        | 0.58%   |
| 6400    | 10        | 0.53%   |
| 4266    | 10        | 0.53%   |
| 2666    | 9         | 0.47%   |
| 1067    | 8         | 0.42%   |
| Unknown | 8         | 0.42%   |
| 2800    | 7         | 0.37%   |
| 1800    | 4         | 0.21%   |
| 4400    | 3         | 0.16%   |
| 4000    | 3         | 0.16%   |
| 3666    | 3         | 0.16%   |
| 3333    | 3         | 0.16%   |
| 1066    | 3         | 0.16%   |
| 4199    | 2         | 0.11%   |
| 3533    | 2         | 0.11%   |
| 3334    | 2         | 0.11%   |
| 3151    | 2         | 0.11%   |
| 3100    | 2         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 47        | 30.32%  |
| Brother Industries    | 31        | 20%     |
| Canon                 | 23        | 14.84%  |
| Seiko Epson           | 18        | 11.61%  |
| Samsung Electronics   | 18        | 11.61%  |
| Dymo-CoStar           | 4         | 2.58%   |
| Fuji Xerox            | 3         | 1.94%   |
| QinHeng Electronics   | 2         | 1.29%   |
| Xerox                 | 1         | 0.65%   |
| STMicroelectronics    | 1         | 0.65%   |
| Prolific Technology   | 1         | 0.65%   |
| Oki Data              | 1         | 0.65%   |
| MIIIW                 | 1         | 0.65%   |
| Lexmark International | 1         | 0.65%   |
| Kyocera               | 1         | 0.65%   |
| ICS Advent            | 1         | 0.65%   |
| Apple                 | 1         | 0.65%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| HP Deskjet 3050 J610 series                                | 5         | 3.21%   |
| Seiko Epson L4150 Series                                   | 3         | 1.92%   |
| Samsung SCX-3400 Series                                    | 3         | 1.92%   |
| Samsung ML-1640 Series Laser Printer                       | 3         | 1.92%   |
| Samsung M2020 Series                                       | 3         | 1.92%   |
| Brother Printer                                            | 3         | 1.92%   |
| Brother HL-2270DW Laser Printer                            | 3         | 1.92%   |
| Seiko Epson WF-3520 Series                                 | 2         | 1.28%   |
| Seiko Epson L395 Series                                    | 2         | 1.28%   |
| Seiko Epson L355 Series                                    | 2         | 1.28%   |
| Seiko Epson L3110 Series                                   | 2         | 1.28%   |
| Samsung M2070 Series                                       | 2         | 1.28%   |
| QinHeng CH340S                                             | 2         | 1.28%   |
| HP LaserJet Professional P 1102w                           | 2         | 1.28%   |
| HP ENVY Photo 6200 series                                  | 2         | 1.28%   |
| HP ENVY 4520 series                                        | 2         | 1.28%   |
| HP ENVY 4500 series                                        | 2         | 1.28%   |
| HP DeskJet F4100 Printer series                            | 2         | 1.28%   |
| HP Deskjet 2540 series                                     | 2         | 1.28%   |
| HP Deskjet 1000 J110 series                                | 2         | 1.28%   |
| Fuji Xerox DocuPrint CM315/318 z                           | 2         | 1.28%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                     | 2         | 1.28%   |
| Canon PIXMA MX920 Series                                   | 2         | 1.28%   |
| Brother HL-L3230CDW series                                 | 2         | 1.28%   |
| Brother HL-2130 series                                     | 2         | 1.28%   |
| Brother HL-1110 series                                     | 2         | 1.28%   |
| Xerox Phaser 6000B                                         | 1         | 0.64%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44  | 1         | 0.64%   |
| Seiko Epson WF-4830 Series                                 | 1         | 0.64%   |
| Seiko Epson L365 Series                                    | 1         | 0.64%   |
| Seiko Epson L132 Series                                    | 1         | 0.64%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1         | 0.64%   |
| Seiko Epson ET-3760 Series                                 | 1         | 0.64%   |
| Seiko Epson ET-3750 Series                                 | 1         | 0.64%   |
| Seiko Epson ET-2800 Series                                 | 1         | 0.64%   |
| Samsung SCX-4200 series                                    | 1         | 0.64%   |
| Samsung ML-2540 Series Laser Printer                       | 1         | 0.64%   |
| Samsung ML-191x/ML-252x Laser Printer                      | 1         | 0.64%   |
| Samsung ML-1670 Series                                     | 1         | 0.64%   |
| Samsung ML-1660 Series                                     | 1         | 0.64%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 10        | 62.5%   |
| Seiko Epson     | 3         | 18.75%  |
| Hewlett-Packard | 2         | 12.5%   |
| Mustek Systems  | 1         | 6.25%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seiko Epson Scanner                    | 2         | 12.5%   |
| Canon CanoScan N1240U/LiDE 30          | 2         | 12.5%   |
| Canon CanoScan LiDE 210                | 2         | 12.5%   |
| Seiko Epson GT-X700 [Perfection 4870]  | 1         | 6.25%   |
| Mustek Systems ScanExpress 1200 UB     | 1         | 6.25%   |
| HP Scanjet 300                         | 1         | 6.25%   |
| HP ScanJet 2400c                       | 1         | 6.25%   |
| Canon CanoScan N650U/N656U             | 1         | 6.25%   |
| Canon CanoScan LiDE 60                 | 1         | 6.25%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40 | 1         | 6.25%   |
| Canon CanoScan LiDE 220                | 1         | 6.25%   |
| Canon CanoScan LiDE 200                | 1         | 6.25%   |
| Canon CanoScan LiDE 110                | 1         | 6.25%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 970       | 21.08%  |
| Microdia                               | 434       | 9.43%   |
| IMC Networks                           | 431       | 9.37%   |
| Acer                                   | 405       | 8.8%    |
| Realtek Semiconductor                  | 344       | 7.48%   |
| Logitech                               | 313       | 6.8%    |
| Sunplus Innovation Technology          | 242       | 5.26%   |
| Apple                                  | 233       | 5.06%   |
| Quanta                                 | 196       | 4.26%   |
| Cheng Uei Precision Industry (Foxlink) | 144       | 3.13%   |
| Suyin                                  | 121       | 2.63%   |
| Syntek                                 | 107       | 2.33%   |
| Lite-On Technology                     | 86        | 1.87%   |
| Silicon Motion                         | 57        | 1.24%   |
| Microsoft                              | 57        | 1.24%   |
| Luxvisions Innotech Limited            | 46        | 1%      |
| Samsung Electronics                    | 36        | 0.78%   |
| Ricoh                                  | 36        | 0.78%   |
| Alcor Micro                            | 30        | 0.65%   |
| Generalplus Technology                 | 21        | 0.46%   |
| Z-Star Microelectronics                | 17        | 0.37%   |
| MacroSilicon                           | 13        | 0.28%   |
| ARC International                      | 13        | 0.28%   |
| Razer USA                              | 12        | 0.26%   |
| ALi                                    | 11        | 0.24%   |
| Unknown                                | 10        | 0.22%   |
| SunplusIT                              | 10        | 0.22%   |
| KYE Systems (Mouse Systems)            | 10        | 0.22%   |
| DigiTech                               | 10        | 0.22%   |
| Valve Software                         | 9         | 0.2%    |
| Sonix Technology                       | 9         | 0.2%    |
| Primax Electronics                     | 9         | 0.2%    |
| Jieli Technology                       | 9         | 0.2%    |
| Intel                                  | 9         | 0.2%    |
| Importek                               | 9         | 0.2%    |
| Lenovo                                 | 8         | 0.17%   |
| AVerMedia Technologies                 | 8         | 0.17%   |
| OmniVision Technologies                | 6         | 0.13%   |
| Creative Technology                    | 6         | 0.13%   |
| LG Electronics                         | 5         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD           | 209       | 4.5%    |
| Chicony Integrated Camera               | 178       | 3.83%   |
| IMC Networks USB2.0 HD UVC WebCam       | 136       | 2.93%   |
| Realtek Integrated_Webcam_HD            | 130       | 2.8%    |
| Chicony HD WebCam                       | 130       | 2.8%    |
| IMC Networks Integrated Camera          | 127       | 2.73%   |
| Chicony USB2.0 Camera                   | 88        | 1.89%   |
| Acer Integrated Camera                  | 86        | 1.85%   |
| Acer BisonCam,NB Pro                    | 83        | 1.79%   |
| Apple Built-in iSight                   | 77        | 1.66%   |
| Logitech HD Pro Webcam C920             | 69        | 1.49%   |
| Syntek Integrated Camera                | 68        | 1.46%   |
| Sunplus Integrated_Webcam_HD            | 66        | 1.42%   |
| Logitech Webcam C270                    | 59        | 1.27%   |
| Apple FaceTime HD Camera                | 53        | 1.14%   |
| Apple iPhone 5/5C/5S/6/SE               | 51        | 1.1%    |
| Acer HD Webcam                          | 48        | 1.03%   |
| Quanta HD User Facing                   | 44        | 0.95%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 43        | 0.93%   |
| Apple FaceTime HD Camera (Built-in)     | 41        | 0.88%   |
| Chicony USB 2.0 Camera                  | 39        | 0.84%   |
| Acer BisonCam, NB Pro                   | 39        | 0.84%   |
| Samsung Galaxy series, misc. (MTP mode) | 33        | 0.71%   |
| Lite-On Integrated Camera               | 33        | 0.71%   |
| Quanta HD Webcam                        | 31        | 0.67%   |
| Microdia Laptop_Integrated_Webcam_HD    | 31        | 0.67%   |
| Chicony TOSHIBA Web Camera - HD         | 31        | 0.67%   |
| Chicony Integrated Camera (1280x720@30) | 30        | 0.65%   |
| Sunplus HD WebCam                       | 29        | 0.62%   |
| Microdia Integrated Webcam              | 29        | 0.62%   |
| Logitech C922 Pro Stream Webcam         | 29        | 0.62%   |
| Chicony USB2.0 HD UVC WebCam            | 28        | 0.6%    |
| Chicony HP Wide Vision HD Camera        | 28        | 0.6%    |
| Sunplus ASUS Webcam                     | 27        | 0.58%   |
| Microdia Webcam Vitade AF               | 27        | 0.58%   |
| Acer SunplusIT Integrated Camera        | 26        | 0.56%   |
| Acer EasyCamera                         | 25        | 0.54%   |
| Chicony USB2.0 VGA UVC WebCam           | 24        | 0.52%   |
| Chicony HP HD Camera                    | 24        | 0.52%   |
| Chicony HD User Facing                  | 24        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 272       | 33.21%  |
| Validity Sensors           | 233       | 28.45%  |
| Shenzhen Goodix Technology | 156       | 19.05%  |
| Elan Microelectronics      | 42        | 5.13%   |
| Upek                       | 41        | 5.01%   |
| LighTuning Technology      | 35        | 4.27%   |
| AuthenTec                  | 26        | 3.17%   |
| STMicroelectronics         | 7         | 0.85%   |
| Samsung Electronics        | 2         | 0.24%   |
| HOLTEK                     | 2         | 0.24%   |
| DigitalPersona             | 2         | 0.24%   |
| Focal-systems.Corp         | 1         | 0.12%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 100       | 12.21%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 66        | 8.06%   |
| Shenzhen Goodix  FingerPrint Device                                        | 61        | 7.45%   |
| Shenzhen Goodix Fingerprint Reader                                         | 53        | 6.47%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 50        | 6.11%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 42        | 5.13%   |
| Shenzhen Goodix FingerPrint                                                | 42        | 5.13%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 38        | 4.64%   |
| Elan ELAN:Fingerprint                                                      | 33        | 4.03%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 30        | 3.66%   |
| Synaptics  WBDI                                                            | 22        | 2.69%   |
| Validity Sensors Synaptics WBDI                                            | 20        | 2.44%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 2.32%   |
| Validity Sensors VFS491                                                    | 18        | 2.2%    |
| Synaptics WBDI Device                                                      | 18        | 2.2%    |
| LighTuning EgisTec_ES603                                                   | 18        | 2.2%    |
| Validity Sensors Fingerprint scanner                                       | 16        | 1.95%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 1.83%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 1.71%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 13        | 1.59%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 12        | 1.47%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 12        | 1.47%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 1.1%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 8         | 0.98%   |
| Elan ELAN:ARM-M4                                                           | 8         | 0.98%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 7         | 0.85%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 0.85%   |
| AuthenTec AES2810                                                          | 7         | 0.85%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 0.73%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 0.73%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 0.73%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 0.73%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 0.61%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 0.37%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.37%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.37%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.37%   |
| AuthenTec AES1600                                                          | 3         | 0.37%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.24%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 0.24%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 132       | 43.85%  |
| Alcor Micro               | 80        | 26.58%  |
| Upek                      | 28        | 9.3%    |
| O2 Micro                  | 22        | 7.31%   |
| Lenovo                    | 18        | 5.98%   |
| SCM Microsystems          | 7         | 2.33%   |
| OmniKey                   | 4         | 1.33%   |
| Realtek Semiconductor     | 2         | 0.66%   |
| Aladdin Knowledge Systems | 2         | 0.66%   |
| Advanced Card Systems     | 2         | 0.66%   |
| Giesecke & Devrient       | 1         | 0.33%   |
| Gemalto (was Gemplus)     | 1         | 0.33%   |
| Clay Logic                | 1         | 0.33%   |
| Chicony Electronics       | 1         | 0.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 79        | 26.25%  |
| Broadcom BCM5880 Secure Applications Processor                               | 42        | 13.95%  |
| Broadcom 5880                                                                | 37        | 12.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 35        | 11.63%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 28        | 9.3%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 5.98%   |
| Lenovo Integrated Smart Card Reader                                          | 18        | 5.98%   |
| Broadcom 58200                                                               | 16        | 5.32%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 5         | 1.66%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.33%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.66%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.66%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.66%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.66%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.33%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.33%   |
| OmniKey CardMan 4321                                                         | 1         | 0.33%   |
| OmniKey CardMan 1021                                                         | 1         | 0.33%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.33%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.33%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.33%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.33%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.33%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.33%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5432      | 69.53%  |
| 1     | 1945      | 24.89%  |
| 2     | 374       | 4.79%   |
| 3     | 52        | 0.67%   |
| 4     | 7         | 0.09%   |
| 5     | 2         | 0.03%   |
| 7     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 802       | 28.76%  |
| Net/wireless             | 504       | 18.07%  |
| Graphics card            | 463       | 16.6%   |
| Multimedia controller    | 317       | 11.37%  |
| Chipcard                 | 290       | 10.4%   |
| Bluetooth                | 80        | 2.87%   |
| Communication controller | 52        | 1.86%   |
| Sound                    | 44        | 1.58%   |
| Unassigned class         | 42        | 1.51%   |
| Camera                   | 41        | 1.47%   |
| Net/ethernet             | 38        | 1.36%   |
| Storage                  | 37        | 1.33%   |
| Network                  | 19        | 0.68%   |
| Card reader              | 18        | 0.65%   |
| Storage/raid             | 11        | 0.39%   |
| Storage/ide              | 10        | 0.36%   |
| Modem                    | 8         | 0.29%   |
| Firewire controller      | 4         | 0.14%   |
| Storage/nvme             | 3         | 0.11%   |
| Flash memory             | 2         | 0.07%   |
| Dvb card                 | 2         | 0.07%   |
| Wireless                 | 1         | 0.04%   |
| Unclassified device      | 1         | 0.04%   |

