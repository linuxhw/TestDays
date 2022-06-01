Linux in Ireland - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Ireland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Ireland/Desktop/README.md) and [notebooks](/Location/Ireland/Notebook/README.md).

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

Total: 602

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | B365M Pro4-F                | Desktop     | [afc161c6fb](https://linux-hardware.org/?probe=afc161c6fb) | May 30, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [522da9476b](https://linux-hardware.org/?probe=522da9476b) | May 29, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [07b116767e](https://linux-hardware.org/?probe=07b116767e) | May 27, 2022 |
| Dell          | Latitude D520               | Notebook    | [55364bfdc0](https://linux-hardware.org/?probe=55364bfdc0) | May 24, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [39f9e9e717](https://linux-hardware.org/?probe=39f9e9e717) | May 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [342929d56c](https://linux-hardware.org/?probe=342929d56c) | May 19, 2022 |
| ASUSTek       | UX330UAK                    | Notebook    | [7b50efe523](https://linux-hardware.org/?probe=7b50efe523) | May 19, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [8471800bb3](https://linux-hardware.org/?probe=8471800bb3) | May 16, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [0d7682cb61](https://linux-hardware.org/?probe=0d7682cb61) | May 14, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [f71977d1fa](https://linux-hardware.org/?probe=f71977d1fa) | May 11, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [6cacb1c49c](https://linux-hardware.org/?probe=6cacb1c49c) | May 11, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [373e009d3b](https://linux-hardware.org/?probe=373e009d3b) | May 09, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [cd1aff125e](https://linux-hardware.org/?probe=cd1aff125e) | May 09, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [6836f79bdf](https://linux-hardware.org/?probe=6836f79bdf) | May 08, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [41cc4d30d4](https://linux-hardware.org/?probe=41cc4d30d4) | May 08, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [01369642f4](https://linux-hardware.org/?probe=01369642f4) | May 03, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| MSI           | H55M-E23                    | Desktop     | [4ab5f58470](https://linux-hardware.org/?probe=4ab5f58470) | Apr 28, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [bf36d72c14](https://linux-hardware.org/?probe=bf36d72c14) | Apr 26, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [273526bab2](https://linux-hardware.org/?probe=273526bab2) | Apr 26, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [5e1b40c8b5](https://linux-hardware.org/?probe=5e1b40c8b5) | Apr 25, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [ea4f513eb9](https://linux-hardware.org/?probe=ea4f513eb9) | Apr 22, 2022 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [02dd52b3b5](https://linux-hardware.org/?probe=02dd52b3b5) | Apr 21, 2022 |
| Dell          | Latitude E6230              | Notebook    | [617c507040](https://linux-hardware.org/?probe=617c507040) | Apr 19, 2022 |
| Dell          | Latitude E6230              | Notebook    | [98f4014ead](https://linux-hardware.org/?probe=98f4014ead) | Apr 19, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [c20035dfb3](https://linux-hardware.org/?probe=c20035dfb3) | Apr 16, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [346c9b6c59](https://linux-hardware.org/?probe=346c9b6c59) | Apr 14, 2022 |
| Dell          | Latitude E6520              | Notebook    | [b10c0f8457](https://linux-hardware.org/?probe=b10c0f8457) | Apr 14, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [92e810b1dd](https://linux-hardware.org/?probe=92e810b1dd) | Apr 13, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [c0eb727f3c](https://linux-hardware.org/?probe=c0eb727f3c) | Apr 12, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [13d6da4ad9](https://linux-hardware.org/?probe=13d6da4ad9) | Apr 12, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [714baddf6f](https://linux-hardware.org/?probe=714baddf6f) | Apr 06, 2022 |
| Lenovo        | 312A SDK0J40700 WIN 3258... | Desktop     | [a645768047](https://linux-hardware.org/?probe=a645768047) | Apr 05, 2022 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [9ecbc31fc2](https://linux-hardware.org/?probe=9ecbc31fc2) | Apr 04, 2022 |
| Notebook      | P65_P67RGRERA               | Notebook    | [654f1700c4](https://linux-hardware.org/?probe=654f1700c4) | Apr 04, 2022 |
| Dell          | Latitude 5420               | Notebook    | [75963e8b7d](https://linux-hardware.org/?probe=75963e8b7d) | Apr 01, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [3e5267891f](https://linux-hardware.org/?probe=3e5267891f) | Apr 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0f98a36a43](https://linux-hardware.org/?probe=0f98a36a43) | Mar 30, 2022 |
| Dell          | Latitude E5440              | Notebook    | [82d2c39d98](https://linux-hardware.org/?probe=82d2c39d98) | Mar 30, 2022 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [949d5ffcf5](https://linux-hardware.org/?probe=949d5ffcf5) | Mar 26, 2022 |
| Intel         | DG45ID AAE46743-302         | Desktop     | [c185ef78b1](https://linux-hardware.org/?probe=c185ef78b1) | Mar 22, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [45c6461d6c](https://linux-hardware.org/?probe=45c6461d6c) | Mar 22, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [e117237c38](https://linux-hardware.org/?probe=e117237c38) | Mar 21, 2022 |
| Rockchip      | Unknown                     | Soc         | [fcef507e8e](https://linux-hardware.org/?probe=fcef507e8e) | Mar 18, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f5723ec8b7](https://linux-hardware.org/?probe=f5723ec8b7) | Mar 15, 2022 |
| Dell          | Latitude E6430              | Notebook    | [bc21cb0e8b](https://linux-hardware.org/?probe=bc21cb0e8b) | Mar 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [27548876c6](https://linux-hardware.org/?probe=27548876c6) | Mar 11, 2022 |
| PC Special... | NH5xAx                      | Notebook    | [ebf60d959f](https://linux-hardware.org/?probe=ebf60d959f) | Mar 11, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [e7c5306c00](https://linux-hardware.org/?probe=e7c5306c00) | Mar 10, 2022 |
| ASRock        | Z68 Pro3                    | Desktop     | [4c4afb883e](https://linux-hardware.org/?probe=4c4afb883e) | Mar 09, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0eaf02ff7d](https://linux-hardware.org/?probe=0eaf02ff7d) | Mar 07, 2022 |
| Dell          | Latitude 9420               | Notebook    | [355f64f6a7](https://linux-hardware.org/?probe=355f64f6a7) | Mar 03, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [44656b1bd4](https://linux-hardware.org/?probe=44656b1bd4) | Mar 03, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [34b97f062b](https://linux-hardware.org/?probe=34b97f062b) | Mar 01, 2022 |
| HP            | 21D0                        | Desktop     | [448912eeb9](https://linux-hardware.org/?probe=448912eeb9) | Feb 24, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [6dd3795cad](https://linux-hardware.org/?probe=6dd3795cad) | Feb 24, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Dell          | Precision M4600             | Notebook    | [9f1f4fcf9c](https://linux-hardware.org/?probe=9f1f4fcf9c) | Feb 18, 2022 |
| Acer          | Predator PH317-54           | Notebook    | [8fb9ac25be](https://linux-hardware.org/?probe=8fb9ac25be) | Feb 11, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ace22bd471](https://linux-hardware.org/?probe=ace22bd471) | Feb 11, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [bb5bd32928](https://linux-hardware.org/?probe=bb5bd32928) | Feb 10, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [2c93e69093](https://linux-hardware.org/?probe=2c93e69093) | Feb 07, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [7f24cf6cc9](https://linux-hardware.org/?probe=7f24cf6cc9) | Feb 07, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [45922e4586](https://linux-hardware.org/?probe=45922e4586) | Feb 04, 2022 |
| Dell          | 0X4H68 A00                  | Desktop     | [3ecad8d7e4](https://linux-hardware.org/?probe=3ecad8d7e4) | Feb 02, 2022 |
| Lenovo        | ThinkPad T480s 20L7S0VJ0... | Notebook    | [7535369bb0](https://linux-hardware.org/?probe=7535369bb0) | Jan 31, 2022 |
| Dell          | 0X4H68 A00                  | Desktop     | [0e6a0c4725](https://linux-hardware.org/?probe=0e6a0c4725) | Jan 29, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [311e85f0cb](https://linux-hardware.org/?probe=311e85f0cb) | Jan 27, 2022 |
| ASRock        | Z68 Pro3                    | Desktop     | [4cdd6daf44](https://linux-hardware.org/?probe=4cdd6daf44) | Jan 19, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [c8932dbfd0](https://linux-hardware.org/?probe=c8932dbfd0) | Jan 15, 2022 |
| Intel         | DG45ID AAE46743-302         | Desktop     | [ab40e8dd7d](https://linux-hardware.org/?probe=ab40e8dd7d) | Jan 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8c319cd6fc](https://linux-hardware.org/?probe=8c319cd6fc) | Jan 11, 2022 |
| Notebook      | P15SM                       | Notebook    | [3b7c794008](https://linux-hardware.org/?probe=3b7c794008) | Jan 08, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4fad903d2a](https://linux-hardware.org/?probe=4fad903d2a) | Jan 06, 2022 |
| Toshiba       | PORTEGE R830                | Notebook    | [097edea6f9](https://linux-hardware.org/?probe=097edea6f9) | Jan 06, 2022 |
| Toshiba       | PORTEGE R830                | Notebook    | [41ed435a4f](https://linux-hardware.org/?probe=41ed435a4f) | Jan 04, 2022 |
| Dell          | Latitude 5411               | Notebook    | [2064d78411](https://linux-hardware.org/?probe=2064d78411) | Jan 03, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [4894e2c956](https://linux-hardware.org/?probe=4894e2c956) | Jan 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [aea80bda1f](https://linux-hardware.org/?probe=aea80bda1f) | Jan 01, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [4161b37157](https://linux-hardware.org/?probe=4161b37157) | Dec 30, 2021 |
| Lenovo        | ThinkPad X220 4291W99       | Notebook    | [ead56def80](https://linux-hardware.org/?probe=ead56def80) | Dec 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [296af779e4](https://linux-hardware.org/?probe=296af779e4) | Dec 20, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | Notebook    | [609264397b](https://linux-hardware.org/?probe=609264397b) | Dec 19, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7230ad27b7](https://linux-hardware.org/?probe=7230ad27b7) | Dec 19, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7b6327d329](https://linux-hardware.org/?probe=7b6327d329) | Dec 19, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [342ba009be](https://linux-hardware.org/?probe=342ba009be) | Dec 19, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | Notebook    | [eefaa1b951](https://linux-hardware.org/?probe=eefaa1b951) | Dec 18, 2021 |
| AVITA         | NS14A8                      | Notebook    | [0ae2523309](https://linux-hardware.org/?probe=0ae2523309) | Dec 18, 2021 |
| Nvidia        | Tegra                       | Soc         | [30c09e0585](https://linux-hardware.org/?probe=30c09e0585) | Dec 17, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [ece425bcfc](https://linux-hardware.org/?probe=ece425bcfc) | Dec 12, 2021 |
| HP            | 1495                        | Desktop     | [489e740957](https://linux-hardware.org/?probe=489e740957) | Dec 12, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [da1818e0c5](https://linux-hardware.org/?probe=da1818e0c5) | Dec 12, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| MSI           | B450 GAMING PLUS            | Desktop     | [69b4695e8d](https://linux-hardware.org/?probe=69b4695e8d) | Dec 04, 2021 |
| Dell          | 0J3C2F A00                  | Desktop     | [bfead2c865](https://linux-hardware.org/?probe=bfead2c865) | Dec 04, 2021 |
| Acer          | AOD255                      | Notebook    | [eae98753db](https://linux-hardware.org/?probe=eae98753db) | Dec 03, 2021 |
| Acer          | AOD255                      | Notebook    | [d2e31c1441](https://linux-hardware.org/?probe=d2e31c1441) | Dec 02, 2021 |
| Acer          | Aspire A315-51              | Notebook    | [397f62191b](https://linux-hardware.org/?probe=397f62191b) | Nov 28, 2021 |
| Sony          | VPCCB35FG                   | Notebook    | [6e46b79e09](https://linux-hardware.org/?probe=6e46b79e09) | Nov 27, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [6c08986736](https://linux-hardware.org/?probe=6c08986736) | Nov 24, 2021 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [291a2a17e2](https://linux-hardware.org/?probe=291a2a17e2) | Nov 21, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [bb51358294](https://linux-hardware.org/?probe=bb51358294) | Nov 18, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [0424bd331e](https://linux-hardware.org/?probe=0424bd331e) | Nov 10, 2021 |
| HP            | Notebook                    | Notebook    | [65c122fe69](https://linux-hardware.org/?probe=65c122fe69) | Oct 31, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [00ac329183](https://linux-hardware.org/?probe=00ac329183) | Oct 30, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [22bc284f45](https://linux-hardware.org/?probe=22bc284f45) | Oct 27, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [3e574fa012](https://linux-hardware.org/?probe=3e574fa012) | Oct 25, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [7105829e72](https://linux-hardware.org/?probe=7105829e72) | Oct 25, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [8f25043c64](https://linux-hardware.org/?probe=8f25043c64) | Oct 24, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [b9412e1ab2](https://linux-hardware.org/?probe=b9412e1ab2) | Oct 23, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [a0ff38d606](https://linux-hardware.org/?probe=a0ff38d606) | Oct 22, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [4add26ac8c](https://linux-hardware.org/?probe=4add26ac8c) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [cbff9b4baf](https://linux-hardware.org/?probe=cbff9b4baf) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [1e6b01d3bd](https://linux-hardware.org/?probe=1e6b01d3bd) | Oct 21, 2021 |
| HP            | 21D0                        | Desktop     | [1dbb2b4a2d](https://linux-hardware.org/?probe=1dbb2b4a2d) | Oct 20, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [c11c89f0d4](https://linux-hardware.org/?probe=c11c89f0d4) | Oct 19, 2021 |
| ASUSTek       | X501A1                      | Notebook    | [0494cb6f11](https://linux-hardware.org/?probe=0494cb6f11) | Oct 13, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [b22927e36e](https://linux-hardware.org/?probe=b22927e36e) | Oct 12, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [74cbbcac9f](https://linux-hardware.org/?probe=74cbbcac9f) | Oct 07, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [f564d05797](https://linux-hardware.org/?probe=f564d05797) | Oct 05, 2021 |
| MSI           | MS-7270                     | Desktop     | [4281e009bb](https://linux-hardware.org/?probe=4281e009bb) | Oct 05, 2021 |
| HP            | 1998                        | Desktop     | [74a28b051a](https://linux-hardware.org/?probe=74a28b051a) | Oct 03, 2021 |
| Apple         | MacBookPro5,3               | Notebook    | [b0ea83da4d](https://linux-hardware.org/?probe=b0ea83da4d) | Oct 02, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [ddcd85bbe5](https://linux-hardware.org/?probe=ddcd85bbe5) | Oct 02, 2021 |
| Timi          | TM1607                      | Notebook    | [aa8b5d346a](https://linux-hardware.org/?probe=aa8b5d346a) | Sep 26, 2021 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [5acbf68626](https://linux-hardware.org/?probe=5acbf68626) | Sep 25, 2021 |
| Apple         | MacBook6,1                  | Notebook    | [4fbbe3d05b](https://linux-hardware.org/?probe=4fbbe3d05b) | Sep 19, 2021 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [9710e6ad6f](https://linux-hardware.org/?probe=9710e6ad6f) | Sep 19, 2021 |
| HP            | Notebook                    | Notebook    | [9c7d616423](https://linux-hardware.org/?probe=9c7d616423) | Sep 12, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [7500e17316](https://linux-hardware.org/?probe=7500e17316) | Sep 11, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [64a2841581](https://linux-hardware.org/?probe=64a2841581) | Sep 11, 2021 |
| Schenker      | XMG NEO (TGL/M21)           | Notebook    | [de8f619f3c](https://linux-hardware.org/?probe=de8f619f3c) | Sep 10, 2021 |
| Dell          | Inspiron 3585               | Notebook    | [3a55618aee](https://linux-hardware.org/?probe=3a55618aee) | Sep 10, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [feec038877](https://linux-hardware.org/?probe=feec038877) | Sep 06, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [c5fbf3298a](https://linux-hardware.org/?probe=c5fbf3298a) | Sep 06, 2021 |
| Lenovo        | ThinkPad E15 20RD0015FR     | Notebook    | [8a229968ef](https://linux-hardware.org/?probe=8a229968ef) | Sep 06, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [c483c45fc4](https://linux-hardware.org/?probe=c483c45fc4) | Sep 03, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f1b601400c](https://linux-hardware.org/?probe=f1b601400c) | Sep 01, 2021 |
| TUXEDO        | InfinityBook Pro 15 v5      | Notebook    | [e0a78bb2e5](https://linux-hardware.org/?probe=e0a78bb2e5) | Aug 30, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [88012fdf33](https://linux-hardware.org/?probe=88012fdf33) | Aug 30, 2021 |
| Toshiba       | Satellite A300              | Notebook    | [c5391fae24](https://linux-hardware.org/?probe=c5391fae24) | Aug 27, 2021 |
| Dell          | Precision 5550              | Notebook    | [705dbe4068](https://linux-hardware.org/?probe=705dbe4068) | Aug 21, 2021 |
| Medion        | Akoya E6239                 | Notebook    | [e22d5c4b21](https://linux-hardware.org/?probe=e22d5c4b21) | Aug 20, 2021 |
| MSI           | B450 GAMING PLUS            | Desktop     | [f5d2b51d19](https://linux-hardware.org/?probe=f5d2b51d19) | Aug 16, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Dell          | 0X9M3X A01                  | Desktop     | [b5b9c80c53](https://linux-hardware.org/?probe=b5b9c80c53) | Aug 14, 2021 |
| Sony          | VPCCB35FG                   | Notebook    | [6550f39d03](https://linux-hardware.org/?probe=6550f39d03) | Aug 10, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1ea279df08](https://linux-hardware.org/?probe=1ea279df08) | Aug 08, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [5ba990c425](https://linux-hardware.org/?probe=5ba990c425) | Aug 04, 2021 |
| Acer          | Swift SF313-53              | Notebook    | [f16feed16c](https://linux-hardware.org/?probe=f16feed16c) | Aug 03, 2021 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [32e0ae8af0](https://linux-hardware.org/?probe=32e0ae8af0) | Aug 03, 2021 |
| Dell          | 0KRC95 A00                  | Desktop     | [f8c48b22e6](https://linux-hardware.org/?probe=f8c48b22e6) | Aug 02, 2021 |
| Lenovo        | ThinkPad P50 20EN0007MS     | Notebook    | [73902de0d8](https://linux-hardware.org/?probe=73902de0d8) | Jul 31, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [69869dec40](https://linux-hardware.org/?probe=69869dec40) | Jul 27, 2021 |
| Dell          | Studio XPS 1640             | Notebook    | [00d5936a25](https://linux-hardware.org/?probe=00d5936a25) | Jul 22, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [1046a771fd](https://linux-hardware.org/?probe=1046a771fd) | Jul 19, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [77ab0c578d](https://linux-hardware.org/?probe=77ab0c578d) | Jul 17, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [06ba47ee9a](https://linux-hardware.org/?probe=06ba47ee9a) | Jul 17, 2021 |
| ASRock        | J4105M                      | Desktop     | [b732da09a3](https://linux-hardware.org/?probe=b732da09a3) | Jul 04, 2021 |
| ASRock        | J4105M                      | Desktop     | [a2d5afa1d6](https://linux-hardware.org/?probe=a2d5afa1d6) | Jul 04, 2021 |
| Dell          | Latitude 7370               | Notebook    | [4fc6100966](https://linux-hardware.org/?probe=4fc6100966) | Jul 03, 2021 |
| Dell          | Latitude 7370               | Notebook    | [2acd089f78](https://linux-hardware.org/?probe=2acd089f78) | Jul 03, 2021 |
| ASRock        | Z77 Extreme3                | Desktop     | [ecd7ec8f36](https://linux-hardware.org/?probe=ecd7ec8f36) | Jul 02, 2021 |
| Entroware     | Apollo                      | Notebook    | [3cbf412b11](https://linux-hardware.org/?probe=3cbf412b11) | Jul 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fff9c1a758](https://linux-hardware.org/?probe=fff9c1a758) | Jun 22, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [3980434b64](https://linux-hardware.org/?probe=3980434b64) | Jun 19, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [27fea5c8cb](https://linux-hardware.org/?probe=27fea5c8cb) | Jun 12, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [511a525213](https://linux-hardware.org/?probe=511a525213) | Jun 11, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [1ccc05a479](https://linux-hardware.org/?probe=1ccc05a479) | Jun 09, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f8241fa3ce](https://linux-hardware.org/?probe=f8241fa3ce) | Jun 08, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [63f094943a](https://linux-hardware.org/?probe=63f094943a) | Jun 07, 2021 |
| Dell          | Latitude C810               | Notebook    | [f379321c88](https://linux-hardware.org/?probe=f379321c88) | Jun 05, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [62b30f282d](https://linux-hardware.org/?probe=62b30f282d) | Jun 04, 2021 |
| Dell          | Latitude C810               | Notebook    | [23e6f5572a](https://linux-hardware.org/?probe=23e6f5572a) | Jun 04, 2021 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [6c770833c9](https://linux-hardware.org/?probe=6c770833c9) | Jun 04, 2021 |
| Toshiba       | TECRA M4                    | Notebook    | [3ac511cc5f](https://linux-hardware.org/?probe=3ac511cc5f) | Jun 03, 2021 |
| Lenovo        | B50-30 80ES                 | Notebook    | [6fff0f3407](https://linux-hardware.org/?probe=6fff0f3407) | Jun 03, 2021 |
| Lenovo        | B50-30 80ES                 | Notebook    | [cfa1b1a4fd](https://linux-hardware.org/?probe=cfa1b1a4fd) | Jun 03, 2021 |
| Dell          | 07F37C A01                  | Desktop     | [baba8a29ac](https://linux-hardware.org/?probe=baba8a29ac) | Jun 02, 2021 |
| Dell          | Inspiron 1764               | Notebook    | [a41c941365](https://linux-hardware.org/?probe=a41c941365) | Jun 02, 2021 |
| Entroware     | Proteus                     | Notebook    | [0ecc547a14](https://linux-hardware.org/?probe=0ecc547a14) | May 31, 2021 |
| MSI           | MS-7270                     | Desktop     | [7cc66e3a90](https://linux-hardware.org/?probe=7cc66e3a90) | May 29, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3c83289b45](https://linux-hardware.org/?probe=3c83289b45) | May 28, 2021 |
| HP            | Pavilion 15                 | Notebook    | [14128860c2](https://linux-hardware.org/?probe=14128860c2) | May 27, 2021 |
| HP            | ProBook 6550b               | Notebook    | [523c397ab6](https://linux-hardware.org/?probe=523c397ab6) | May 27, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [e7292a5491](https://linux-hardware.org/?probe=e7292a5491) | May 26, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [bb6ab823e7](https://linux-hardware.org/?probe=bb6ab823e7) | May 23, 2021 |
| HP            | 3397                        | Desktop     | [ae9a8581c5](https://linux-hardware.org/?probe=ae9a8581c5) | May 23, 2021 |
| MSI           | X470 GAMING PRO             | Desktop     | [f7c5833c2a](https://linux-hardware.org/?probe=f7c5833c2a) | May 23, 2021 |
| HP            | 15                          | Notebook    | [ab211b6ad8](https://linux-hardware.org/?probe=ab211b6ad8) | May 21, 2021 |
| HP            | 15                          | Notebook    | [d285154a2b](https://linux-hardware.org/?probe=d285154a2b) | May 21, 2021 |
| Shuttle       | FS35V4                      | Desktop     | [6f9a85a086](https://linux-hardware.org/?probe=6f9a85a086) | May 21, 2021 |
| Shuttle       | FS35V4                      | Desktop     | [acd3144c20](https://linux-hardware.org/?probe=acd3144c20) | May 21, 2021 |
| HP            | 18E5                        | Desktop     | [6cbae0f799](https://linux-hardware.org/?probe=6cbae0f799) | May 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ea97f7d05d](https://linux-hardware.org/?probe=ea97f7d05d) | May 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [824ec14630](https://linux-hardware.org/?probe=824ec14630) | May 20, 2021 |
| Entroware     | Proteus                     | Notebook    | [98be1903c4](https://linux-hardware.org/?probe=98be1903c4) | May 17, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [80f0e0228b](https://linux-hardware.org/?probe=80f0e0228b) | May 16, 2021 |
| Dell          | Latitude 5520               | Notebook    | [34c3dc01e9](https://linux-hardware.org/?probe=34c3dc01e9) | May 07, 2021 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | Desktop     | [452f706571](https://linux-hardware.org/?probe=452f706571) | May 07, 2021 |
| HP            | HDX 18                      | Notebook    | [dead2b5b56](https://linux-hardware.org/?probe=dead2b5b56) | May 07, 2021 |
| ASRock        | Z490M Pro4                  | Desktop     | [d1d4f84e0a](https://linux-hardware.org/?probe=d1d4f84e0a) | May 03, 2021 |
| HP            | EliteBook Folio G1          | Notebook    | [f3bdc3e991](https://linux-hardware.org/?probe=f3bdc3e991) | Apr 24, 2021 |
| Acer          | Aspire 5333                 | Notebook    | [c6227d5004](https://linux-hardware.org/?probe=c6227d5004) | Apr 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [fe576d54b4](https://linux-hardware.org/?probe=fe576d54b4) | Apr 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [e651f5da2c](https://linux-hardware.org/?probe=e651f5da2c) | Apr 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [be651d63a0](https://linux-hardware.org/?probe=be651d63a0) | Apr 19, 2021 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [9c0bbd0e0c](https://linux-hardware.org/?probe=9c0bbd0e0c) | Apr 18, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [0ceacbca21](https://linux-hardware.org/?probe=0ceacbca21) | Apr 17, 2021 |
| Acer          | Aspire 5333                 | Notebook    | [2171d74173](https://linux-hardware.org/?probe=2171d74173) | Apr 15, 2021 |
| Acer          | Aspire 5333                 | Notebook    | [dd4fee2ece](https://linux-hardware.org/?probe=dd4fee2ece) | Apr 15, 2021 |
| Dell          | 0NNNCT A01                  | Desktop     | [8253ac8502](https://linux-hardware.org/?probe=8253ac8502) | Apr 10, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [2e946e600e](https://linux-hardware.org/?probe=2e946e600e) | Apr 08, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [51b67b480d](https://linux-hardware.org/?probe=51b67b480d) | Apr 05, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [93033ed87e](https://linux-hardware.org/?probe=93033ed87e) | Apr 04, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [6b926d1195](https://linux-hardware.org/?probe=6b926d1195) | Apr 04, 2021 |
| HP            | Pavilion g6                 | Notebook    | [726040b78b](https://linux-hardware.org/?probe=726040b78b) | Apr 03, 2021 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [6917221b5b](https://linux-hardware.org/?probe=6917221b5b) | Apr 02, 2021 |
| ASUSTek       | P8Z77-V                     | Desktop     | [9e21f67ab7](https://linux-hardware.org/?probe=9e21f67ab7) | Mar 28, 2021 |
| Acer          | Aspire 5920G                | Notebook    | [9976792f0f](https://linux-hardware.org/?probe=9976792f0f) | Mar 26, 2021 |
| Lenovo        | ThinkPad W530 24491D1       | Notebook    | [31a4336d63](https://linux-hardware.org/?probe=31a4336d63) | Mar 25, 2021 |
| Microtech     | e-book Lite                 | Notebook    | [85b6d19466](https://linux-hardware.org/?probe=85b6d19466) | Mar 23, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [488904f6d8](https://linux-hardware.org/?probe=488904f6d8) | Mar 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [7fbf31af63](https://linux-hardware.org/?probe=7fbf31af63) | Mar 18, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [1b571fd1c4](https://linux-hardware.org/?probe=1b571fd1c4) | Mar 18, 2021 |
| Dell          | 0NNNCT A01                  | Desktop     | [e5a6c9dcb9](https://linux-hardware.org/?probe=e5a6c9dcb9) | Mar 17, 2021 |
| ASUSTek       | X540LA                      | Notebook    | [8b0145ff0c](https://linux-hardware.org/?probe=8b0145ff0c) | Mar 13, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [d2ff3aaec4](https://linux-hardware.org/?probe=d2ff3aaec4) | Mar 12, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [f2f15e9ef1](https://linux-hardware.org/?probe=f2f15e9ef1) | Mar 10, 2021 |
| Pegatron      | 2A94h                       | Desktop     | [b035a149a3](https://linux-hardware.org/?probe=b035a149a3) | Mar 02, 2021 |
| Medion        | MS-7646                     | Desktop     | [5ca2e128b6](https://linux-hardware.org/?probe=5ca2e128b6) | Feb 24, 2021 |
| HP            | Pavilion m6                 | Notebook    | [578aad5ad5](https://linux-hardware.org/?probe=578aad5ad5) | Feb 24, 2021 |
| HP            | Notebook                    | Notebook    | [21ead6ec52](https://linux-hardware.org/?probe=21ead6ec52) | Feb 22, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [7dbba6ee59](https://linux-hardware.org/?probe=7dbba6ee59) | Feb 21, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [8f2450a3b0](https://linux-hardware.org/?probe=8f2450a3b0) | Feb 20, 2021 |
| HP            | Compaq 6530b (GW688AV)      | Notebook    | [2812d098fd](https://linux-hardware.org/?probe=2812d098fd) | Feb 20, 2021 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [ce0aecd52b](https://linux-hardware.org/?probe=ce0aecd52b) | Feb 20, 2021 |
| Dell          | 0WR7PY A03                  | Desktop     | [878e82f1a3](https://linux-hardware.org/?probe=878e82f1a3) | Feb 19, 2021 |
| HP            | EliteBook 745 G6            | Notebook    | [3bf39bac3e](https://linux-hardware.org/?probe=3bf39bac3e) | Feb 19, 2021 |
| Apple         | MacBookPro2,2               | Notebook    | [52f24b3228](https://linux-hardware.org/?probe=52f24b3228) | Feb 19, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [6fad2f0ade](https://linux-hardware.org/?probe=6fad2f0ade) | Feb 14, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [46556ad380](https://linux-hardware.org/?probe=46556ad380) | Feb 14, 2021 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [78c7860103](https://linux-hardware.org/?probe=78c7860103) | Feb 10, 2021 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [8647ccdbef](https://linux-hardware.org/?probe=8647ccdbef) | Feb 10, 2021 |
| MSI           | 2AE0                        | Desktop     | [374ff27ab8](https://linux-hardware.org/?probe=374ff27ab8) | Feb 09, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [6ef4606f95](https://linux-hardware.org/?probe=6ef4606f95) | Feb 09, 2021 |
| HP            | 1495                        | Desktop     | [d8d36f4b2b](https://linux-hardware.org/?probe=d8d36f4b2b) | Feb 08, 2021 |
| Dell          | 0HY9JP A02                  | Desktop     | [51ede3687a](https://linux-hardware.org/?probe=51ede3687a) | Feb 05, 2021 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [ec083139fc](https://linux-hardware.org/?probe=ec083139fc) | Feb 05, 2021 |
| Samsung       | Galaxy TabPro S             | Tablet      | [4e4ef907a0](https://linux-hardware.org/?probe=4e4ef907a0) | Feb 05, 2021 |
| Dell          | 0HY9JP A02                  | Desktop     | [6c4261b08f](https://linux-hardware.org/?probe=6c4261b08f) | Feb 05, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b1ed72b941](https://linux-hardware.org/?probe=b1ed72b941) | Feb 04, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d4502d7365](https://linux-hardware.org/?probe=d4502d7365) | Jan 28, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [0a2ca85ddc](https://linux-hardware.org/?probe=0a2ca85ddc) | Jan 22, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2c59be484e](https://linux-hardware.org/?probe=2c59be484e) | Jan 22, 2021 |
| Dell          | 0P4T42 A00                  | All in one  | [1dbf9cced7](https://linux-hardware.org/?probe=1dbf9cced7) | Jan 22, 2021 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [9f3cf476f3](https://linux-hardware.org/?probe=9f3cf476f3) | Jan 19, 2021 |
| ASUSTek       | Maximus IV Extreme          | Desktop     | [9ce5eab595](https://linux-hardware.org/?probe=9ce5eab595) | Jan 16, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [192f01dd70](https://linux-hardware.org/?probe=192f01dd70) | Jan 16, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [e8cd5368b0](https://linux-hardware.org/?probe=e8cd5368b0) | Jan 14, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| Dell          | System XPS L502X            | Notebook    | [8b67c2132b](https://linux-hardware.org/?probe=8b67c2132b) | Jan 13, 2021 |
| Dell          | Precision 5550              | Notebook    | [ba201aad9e](https://linux-hardware.org/?probe=ba201aad9e) | Jan 11, 2021 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [54b2f4c522](https://linux-hardware.org/?probe=54b2f4c522) | Jan 11, 2021 |
| MSI           | X470 GAMING PRO             | Desktop     | [d7528e4806](https://linux-hardware.org/?probe=d7528e4806) | Jan 09, 2021 |
| HUAWEI        | BOHL-WXX9                   | Notebook    | [5845d9565c](https://linux-hardware.org/?probe=5845d9565c) | Jan 05, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [40ae1409a4](https://linux-hardware.org/?probe=40ae1409a4) | Jan 05, 2021 |
| Entroware     | Proteus                     | Notebook    | [7d71ef8a53](https://linux-hardware.org/?probe=7d71ef8a53) | Jan 05, 2021 |
| Samsung       | N150/N210/N220              | Notebook    | [e556ab958b](https://linux-hardware.org/?probe=e556ab958b) | Jan 02, 2021 |
| Intel         | NUC10i3FNB K61362-302       | Mini pc     | [59440917d2](https://linux-hardware.org/?probe=59440917d2) | Jan 01, 2021 |
| Samsung       | N150/N210/N220              | Notebook    | [adc4530996](https://linux-hardware.org/?probe=adc4530996) | Jan 01, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [b34a40d6b3](https://linux-hardware.org/?probe=b34a40d6b3) | Dec 31, 2020 |
| Lenovo        | ThinkPad E560 20EV000UUK    | Notebook    | [c38d67b61b](https://linux-hardware.org/?probe=c38d67b61b) | Dec 30, 2020 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8740e02802](https://linux-hardware.org/?probe=8740e02802) | Dec 29, 2020 |
| ASUSTek       | F2A55-M LK2                 | Desktop     | [b6ffae8f7a](https://linux-hardware.org/?probe=b6ffae8f7a) | Dec 27, 2020 |
| HP            | 3032h                       | Desktop     | [c71be55264](https://linux-hardware.org/?probe=c71be55264) | Dec 24, 2020 |
| Dell          | System XPS L502X            | Notebook    | [dda884ab5b](https://linux-hardware.org/?probe=dda884ab5b) | Dec 20, 2020 |
| MSI           | MEG X399 CREATION           | Desktop     | [d1e772d769](https://linux-hardware.org/?probe=d1e772d769) | Dec 11, 2020 |
| Acer          | Aspire 5551                 | Notebook    | [cb35dac70b](https://linux-hardware.org/?probe=cb35dac70b) | Dec 09, 2020 |
| HP            | Notebook                    | Notebook    | [2564f14d0b](https://linux-hardware.org/?probe=2564f14d0b) | Dec 06, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [325dd21da3](https://linux-hardware.org/?probe=325dd21da3) | Nov 27, 2020 |
| MSI           | MS-7270                     | Desktop     | [b4e45eae99](https://linux-hardware.org/?probe=b4e45eae99) | Nov 26, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [703167df7b](https://linux-hardware.org/?probe=703167df7b) | Nov 24, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [04e06f0e3b](https://linux-hardware.org/?probe=04e06f0e3b) | Nov 23, 2020 |
| HP            | Presario V6500              | Notebook    | [6950f2532b](https://linux-hardware.org/?probe=6950f2532b) | Nov 23, 2020 |
| HP            | Presario V6500              | Notebook    | [f4f30c83df](https://linux-hardware.org/?probe=f4f30c83df) | Nov 23, 2020 |
| HP            | EliteBook 8740w             | Notebook    | [f30611840c](https://linux-hardware.org/?probe=f30611840c) | Nov 23, 2020 |
| PC Special... | PCX0DX                      | Notebook    | [b4498047ef](https://linux-hardware.org/?probe=b4498047ef) | Nov 22, 2020 |
| Apple         | MacBookPro5,4               | Notebook    | [a7492067f0](https://linux-hardware.org/?probe=a7492067f0) | Nov 21, 2020 |
| HP            | EliteBook 820 G1            | Notebook    | [4db5c39f50](https://linux-hardware.org/?probe=4db5c39f50) | Nov 21, 2020 |
| Lenovo        | ThinkPad T400 64754G7       | Notebook    | [770660037c](https://linux-hardware.org/?probe=770660037c) | Nov 21, 2020 |
| HP            | EliteBook 8740w             | Notebook    | [072b557a79](https://linux-hardware.org/?probe=072b557a79) | Nov 20, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [58fc01c757](https://linux-hardware.org/?probe=58fc01c757) | Nov 19, 2020 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [d8379e8abb](https://linux-hardware.org/?probe=d8379e8abb) | Nov 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [578d1badca](https://linux-hardware.org/?probe=578d1badca) | Nov 18, 2020 |
| Alienware     | 17 R4                       | Notebook    | [8b7402a4e7](https://linux-hardware.org/?probe=8b7402a4e7) | Nov 16, 2020 |
| Alienware     | 17 R4                       | Notebook    | [62e5ac4fd3](https://linux-hardware.org/?probe=62e5ac4fd3) | Nov 16, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [7132bcc66d](https://linux-hardware.org/?probe=7132bcc66d) | Nov 15, 2020 |
| MSI           | MS-7270                     | Desktop     | [c70e52b025](https://linux-hardware.org/?probe=c70e52b025) | Nov 13, 2020 |
| Dell          | Latitude E6420              | Notebook    | [f542aafd19](https://linux-hardware.org/?probe=f542aafd19) | Nov 13, 2020 |
| HP            | 1495                        | Desktop     | [a250ea93d5](https://linux-hardware.org/?probe=a250ea93d5) | Nov 10, 2020 |
| Notebook      | NL40_50CU                   | Notebook    | [893477956d](https://linux-hardware.org/?probe=893477956d) | Nov 10, 2020 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [418e9ce805](https://linux-hardware.org/?probe=418e9ce805) | Nov 06, 2020 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [7780f8f320](https://linux-hardware.org/?probe=7780f8f320) | Nov 06, 2020 |
| MSI           | MS-7270                     | Desktop     | [97556dedc3](https://linux-hardware.org/?probe=97556dedc3) | Nov 05, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [eac2b32ee0](https://linux-hardware.org/?probe=eac2b32ee0) | Nov 04, 2020 |
| System76      | Galago Pro                  | Notebook    | [79822a5348](https://linux-hardware.org/?probe=79822a5348) | Nov 04, 2020 |
| Dell          | XPS M1530                   | Notebook    | [bc52d9b9a4](https://linux-hardware.org/?probe=bc52d9b9a4) | Nov 03, 2020 |
| Dell          | Dimension 5100              | Desktop     | [f18393d9aa](https://linux-hardware.org/?probe=f18393d9aa) | Nov 03, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [3be1cd15b1](https://linux-hardware.org/?probe=3be1cd15b1) | Oct 30, 2020 |
| Medion        | E6239 MD99452               | Notebook    | [2496b738ac](https://linux-hardware.org/?probe=2496b738ac) | Oct 29, 2020 |
| Medion        | E6239 MD99452               | Notebook    | [f875a122f9](https://linux-hardware.org/?probe=f875a122f9) | Oct 29, 2020 |
| PC Special... | TF                          | Notebook    | [e651ccb88e](https://linux-hardware.org/?probe=e651ccb88e) | Oct 29, 2020 |
| HP            | ZBook 15 G2                 | Notebook    | [0b113f8315](https://linux-hardware.org/?probe=0b113f8315) | Oct 29, 2020 |
| PC Special... | TF                          | Notebook    | [ba278ca133](https://linux-hardware.org/?probe=ba278ca133) | Oct 29, 2020 |
| Apple         | Mac-F2238AC8                | All in one  | [e9e4822309](https://linux-hardware.org/?probe=e9e4822309) | Oct 28, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [0e16f54971](https://linux-hardware.org/?probe=0e16f54971) | Oct 28, 2020 |
| Toshiba       | Satellite C50-B             | Notebook    | [0edec7c57f](https://linux-hardware.org/?probe=0edec7c57f) | Oct 27, 2020 |
| Toshiba       | Satellite C50-B             | Notebook    | [21e26c80bc](https://linux-hardware.org/?probe=21e26c80bc) | Oct 27, 2020 |
| Dell          | Vostro 3700                 | Notebook    | [5493bcf45a](https://linux-hardware.org/?probe=5493bcf45a) | Oct 26, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [2db5bc3b28](https://linux-hardware.org/?probe=2db5bc3b28) | Oct 23, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [acc7a651ac](https://linux-hardware.org/?probe=acc7a651ac) | Oct 23, 2020 |
| TUXEDO        | InfinityBook Pro 15 v5      | Notebook    | [6aea9a482c](https://linux-hardware.org/?probe=6aea9a482c) | Oct 20, 2020 |
| HP            | 1497                        | Desktop     | [dea5079fad](https://linux-hardware.org/?probe=dea5079fad) | Oct 19, 2020 |
| Dell          | 0RY206                      | Desktop     | [4e0283b4c8](https://linux-hardware.org/?probe=4e0283b4c8) | Oct 18, 2020 |
| Dell          | 0RY206                      | Desktop     | [5d45dd253e](https://linux-hardware.org/?probe=5d45dd253e) | Oct 18, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [96ff229c4c](https://linux-hardware.org/?probe=96ff229c4c) | Oct 17, 2020 |
| HP            | 1497                        | Desktop     | [8dd5fc52bd](https://linux-hardware.org/?probe=8dd5fc52bd) | Oct 15, 2020 |
| Nvidia        | Tegra                       | Soc         | [9b157b83a5](https://linux-hardware.org/?probe=9b157b83a5) | Oct 15, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [bd7a8f0f96](https://linux-hardware.org/?probe=bd7a8f0f96) | Oct 15, 2020 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [a0292a1315](https://linux-hardware.org/?probe=a0292a1315) | Oct 15, 2020 |
| Dell          | Dimension 5100              | Desktop     | [5b80714363](https://linux-hardware.org/?probe=5b80714363) | Oct 14, 2020 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ab8c149b9f](https://linux-hardware.org/?probe=ab8c149b9f) | Oct 14, 2020 |
| Lenovo        | ThinkStation D20 415892G    | Desktop     | [08619ece44](https://linux-hardware.org/?probe=08619ece44) | Oct 14, 2020 |
| Apple         | MacBook5,1                  | Notebook    | [598a9af3a1](https://linux-hardware.org/?probe=598a9af3a1) | Oct 12, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [d245d1c5a5](https://linux-hardware.org/?probe=d245d1c5a5) | Oct 06, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [1554f3d77d](https://linux-hardware.org/?probe=1554f3d77d) | Oct 05, 2020 |
| HP            | 1495                        | Desktop     | [d1cf757d40](https://linux-hardware.org/?probe=d1cf757d40) | Oct 05, 2020 |
| HP            | 1495                        | Desktop     | [2389a49dc0](https://linux-hardware.org/?probe=2389a49dc0) | Oct 05, 2020 |
| Lenovo        | ThinkStation D20 415892G    | Desktop     | [1e8497692d](https://linux-hardware.org/?probe=1e8497692d) | Oct 02, 2020 |
| ASRock        | H97M Pro4                   | Desktop     | [c2148ec054](https://linux-hardware.org/?probe=c2148ec054) | Oct 01, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [c22330bac3](https://linux-hardware.org/?probe=c22330bac3) | Sep 26, 2020 |
| Toshiba       | Satellite L50-B             | Notebook    | [58ce88778b](https://linux-hardware.org/?probe=58ce88778b) | Sep 23, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [a2c5c1ea67](https://linux-hardware.org/?probe=a2c5c1ea67) | Sep 18, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [3eba500997](https://linux-hardware.org/?probe=3eba500997) | Sep 15, 2020 |
| HP            | G70                         | Notebook    | [198fd94bda](https://linux-hardware.org/?probe=198fd94bda) | Sep 13, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [20c0d6785b](https://linux-hardware.org/?probe=20c0d6785b) | Sep 11, 2020 |
| Dell          | 0Y958C A00                  | Desktop     | [253e97e06c](https://linux-hardware.org/?probe=253e97e06c) | Sep 10, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [daceea1b39](https://linux-hardware.org/?probe=daceea1b39) | Sep 08, 2020 |
| HP            | 255 G2                      | Notebook    | [5d06b6eeff](https://linux-hardware.org/?probe=5d06b6eeff) | Sep 04, 2020 |
| Lenovo        | U410                        | Notebook    | [ad05692bf0](https://linux-hardware.org/?probe=ad05692bf0) | Sep 02, 2020 |
| Unknown       | RS780-SB700 Unknox          | Desktop     | [a084e40027](https://linux-hardware.org/?probe=a084e40027) | Aug 30, 2020 |
| Gigabyte      | GA-MA790X-UD3P              | Desktop     | [f5a642ebbb](https://linux-hardware.org/?probe=f5a642ebbb) | Aug 28, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [f710d270fe](https://linux-hardware.org/?probe=f710d270fe) | Aug 19, 2020 |
| Gigabyte      | G1.Sniper                   | Desktop     | [f25aa5934e](https://linux-hardware.org/?probe=f25aa5934e) | Aug 19, 2020 |
| Gigabyte      | G1.Sniper                   | Desktop     | [ebb3d9d7aa](https://linux-hardware.org/?probe=ebb3d9d7aa) | Aug 15, 2020 |
| Gigabyte      | G1.Sniper                   | Desktop     | [8d1bc7ce18](https://linux-hardware.org/?probe=8d1bc7ce18) | Aug 15, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [e1529e585d](https://linux-hardware.org/?probe=e1529e585d) | Aug 14, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [a20482ea67](https://linux-hardware.org/?probe=a20482ea67) | Aug 12, 2020 |
| ASUSTek       | ZN241IC                     | All in one  | [46c001d058](https://linux-hardware.org/?probe=46c001d058) | Aug 10, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [92a135b7d2](https://linux-hardware.org/?probe=92a135b7d2) | Aug 09, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [0eaa4ae12f](https://linux-hardware.org/?probe=0eaa4ae12f) | Aug 09, 2020 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [c3fbdc22c8](https://linux-hardware.org/?probe=c3fbdc22c8) | Aug 09, 2020 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [4a551e8c6b](https://linux-hardware.org/?probe=4a551e8c6b) | Aug 09, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [0c80b9688e](https://linux-hardware.org/?probe=0c80b9688e) | Aug 08, 2020 |
| Lenovo        | ThinkPad T430 2349G4G       | Notebook    | [db1ba375f2](https://linux-hardware.org/?probe=db1ba375f2) | Aug 08, 2020 |
| Dell          | 0T568R A00                  | Desktop     | [fb620a31fc](https://linux-hardware.org/?probe=fb620a31fc) | Aug 07, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [5101109869](https://linux-hardware.org/?probe=5101109869) | Aug 07, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [cb782efc58](https://linux-hardware.org/?probe=cb782efc58) | Aug 07, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [28a4ff7761](https://linux-hardware.org/?probe=28a4ff7761) | Aug 07, 2020 |
| Acer          | Aspire 5349                 | Notebook    | [fdae61b8d4](https://linux-hardware.org/?probe=fdae61b8d4) | Aug 07, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [d702543fbb](https://linux-hardware.org/?probe=d702543fbb) | Aug 06, 2020 |
| HP            | 8648                        | Desktop     | [e034f483fc](https://linux-hardware.org/?probe=e034f483fc) | Aug 06, 2020 |
| Dell          | 0P4T42 A00                  | All in one  | [4924eefd27](https://linux-hardware.org/?probe=4924eefd27) | Aug 03, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [b5911c66d7](https://linux-hardware.org/?probe=b5911c66d7) | Aug 02, 2020 |
| Dell          | Latitude E7450              | Notebook    | [e0eee5c0fc](https://linux-hardware.org/?probe=e0eee5c0fc) | Aug 01, 2020 |
| Dell          | Latitude E7450              | Notebook    | [a8695dbee5](https://linux-hardware.org/?probe=a8695dbee5) | Aug 01, 2020 |
| PC Special... | N150CU                      | Notebook    | [6d19fc4569](https://linux-hardware.org/?probe=6d19fc4569) | Aug 01, 2020 |
| Lenovo        | ThinkPad T430 2349KB4       | Notebook    | [291151dae1](https://linux-hardware.org/?probe=291151dae1) | Jul 31, 2020 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [0e300aa2a8](https://linux-hardware.org/?probe=0e300aa2a8) | Jul 30, 2020 |
| MSI           | WS65 9TK                    | Notebook    | [e9feed814f](https://linux-hardware.org/?probe=e9feed814f) | Jul 29, 2020 |
| MSI           | WS65 9TK                    | Notebook    | [b296acb26a](https://linux-hardware.org/?probe=b296acb26a) | Jul 29, 2020 |
| HP            | Pavilion dm1                | Notebook    | [cc8ed632dc](https://linux-hardware.org/?probe=cc8ed632dc) | Jul 25, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [9b5d494924](https://linux-hardware.org/?probe=9b5d494924) | Jul 25, 2020 |
| Dell          | Latitude 5480               | Notebook    | [e06096d959](https://linux-hardware.org/?probe=e06096d959) | Jul 24, 2020 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [4615574555](https://linux-hardware.org/?probe=4615574555) | Jul 24, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [a8709e5362](https://linux-hardware.org/?probe=a8709e5362) | Jul 23, 2020 |
| Lenovo        | IdeaPad Y500 9541           | Notebook    | [bdf2ff973b](https://linux-hardware.org/?probe=bdf2ff973b) | Jul 20, 2020 |
| Dell          | Latitude 5400               | Notebook    | [11473792e0](https://linux-hardware.org/?probe=11473792e0) | Jul 19, 2020 |
| HP            | 8425                        | Desktop     | [25fd18c4f7](https://linux-hardware.org/?probe=25fd18c4f7) | Jul 19, 2020 |
| HP            | 255 G2                      | Notebook    | [6801725bae](https://linux-hardware.org/?probe=6801725bae) | Jul 17, 2020 |
| HP            | 255 G2                      | Notebook    | [7319f8f1b3](https://linux-hardware.org/?probe=7319f8f1b3) | Jul 17, 2020 |
| HP            | 255 G2                      | Notebook    | [d1dea15553](https://linux-hardware.org/?probe=d1dea15553) | Jul 16, 2020 |
| Lenovo        | G500 VIWGP                  | Notebook    | [37286d3145](https://linux-hardware.org/?probe=37286d3145) | Jul 08, 2020 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [f504426c40](https://linux-hardware.org/?probe=f504426c40) | Jul 04, 2020 |
| Lenovo        | ThinkCentre M91p 7052A9G    | Desktop     | [332ba4769f](https://linux-hardware.org/?probe=332ba4769f) | Jul 01, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [561adcd20d](https://linux-hardware.org/?probe=561adcd20d) | Jun 30, 2020 |
| Apple         | MacBookPro8,3               | Notebook    | [2a16561ffa](https://linux-hardware.org/?probe=2a16561ffa) | Jun 28, 2020 |
| Apple         | MacBookPro8,3               | Notebook    | [8ba0fcfe7c](https://linux-hardware.org/?probe=8ba0fcfe7c) | Jun 28, 2020 |
| Lenovo        | ThinkCentre M91p 7052A9G    | Desktop     | [0c0f90ba39](https://linux-hardware.org/?probe=0c0f90ba39) | Jun 27, 2020 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [124cdbcc52](https://linux-hardware.org/?probe=124cdbcc52) | Jun 27, 2020 |
| Lenovo        | ThinkCentre M91p 7052A9G    | Desktop     | [92adc3c517](https://linux-hardware.org/?probe=92adc3c517) | Jun 25, 2020 |
| MSI           | X570-A PRO                  | Desktop     | [60c99711b8](https://linux-hardware.org/?probe=60c99711b8) | Jun 23, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [a36f83366b](https://linux-hardware.org/?probe=a36f83366b) | Jun 21, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d79300ba76](https://linux-hardware.org/?probe=d79300ba76) | Jun 18, 2020 |
| Dell          | Inspiron 15-3552            | Notebook    | [168dcc66c7](https://linux-hardware.org/?probe=168dcc66c7) | Jun 17, 2020 |
| Timi          | TM1703                      | Notebook    | [d3d89dc21d](https://linux-hardware.org/?probe=d3d89dc21d) | Jun 16, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [1cfb078c4e](https://linux-hardware.org/?probe=1cfb078c4e) | Jun 13, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [18230e354a](https://linux-hardware.org/?probe=18230e354a) | Jun 13, 2020 |
| MSI           | MEG X399 CREATION           | Desktop     | [89214de087](https://linux-hardware.org/?probe=89214de087) | Jun 12, 2020 |
| SLIMBOOK      | PROX15                      | Notebook    | [a4e6b0723d](https://linux-hardware.org/?probe=a4e6b0723d) | Jun 12, 2020 |
| ASUSTek       | G750JW                      | Notebook    | [cc02e1e15c](https://linux-hardware.org/?probe=cc02e1e15c) | Jun 10, 2020 |
| Lenovo        | ThinkCentre M58 7373BVU     | Desktop     | [5c40e26f41](https://linux-hardware.org/?probe=5c40e26f41) | Jun 09, 2020 |
| Dell          | Latitude E5420              | Notebook    | [eb3a4e918a](https://linux-hardware.org/?probe=eb3a4e918a) | Jun 08, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [a1615f709d](https://linux-hardware.org/?probe=a1615f709d) | Jun 07, 2020 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [7b570e8172](https://linux-hardware.org/?probe=7b570e8172) | Jun 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 34431... | Notebook    | [c5d45645b7](https://linux-hardware.org/?probe=c5d45645b7) | Jun 01, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [fbef0c90d4](https://linux-hardware.org/?probe=fbef0c90d4) | May 28, 2020 |
| Lenovo        | ThinkPad T410s 2904HDU      | Notebook    | [b1eb7716ed](https://linux-hardware.org/?probe=b1eb7716ed) | May 26, 2020 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [1538853c0c](https://linux-hardware.org/?probe=1538853c0c) | May 26, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [4a1413e289](https://linux-hardware.org/?probe=4a1413e289) | May 26, 2020 |
| HP            | Presario CQ61               | Notebook    | [28b3078708](https://linux-hardware.org/?probe=28b3078708) | May 25, 2020 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [4547e0d6fe](https://linux-hardware.org/?probe=4547e0d6fe) | May 25, 2020 |
| Chuwi         | LapBook SE                  | Notebook    | [c144d3a1bc](https://linux-hardware.org/?probe=c144d3a1bc) | May 24, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [206613fa48](https://linux-hardware.org/?probe=206613fa48) | May 22, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [6570cd4d9d](https://linux-hardware.org/?probe=6570cd4d9d) | May 22, 2020 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [cdcb59b3fb](https://linux-hardware.org/?probe=cdcb59b3fb) | May 22, 2020 |
| Packard Be... | P5N-E SLI                   | Desktop     | [495a29d64c](https://linux-hardware.org/?probe=495a29d64c) | May 22, 2020 |
| Packard Be... | P5N-E SLI                   | Desktop     | [1c2ca9c7de](https://linux-hardware.org/?probe=1c2ca9c7de) | May 22, 2020 |
| Dell          | Vostro 5490                 | Notebook    | [9000fa541e](https://linux-hardware.org/?probe=9000fa541e) | May 18, 2020 |
| Dell          | Latitude E5420              | Notebook    | [5519dbffbc](https://linux-hardware.org/?probe=5519dbffbc) | May 18, 2020 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [932b22c52a](https://linux-hardware.org/?probe=932b22c52a) | May 16, 2020 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [02b85cc578](https://linux-hardware.org/?probe=02b85cc578) | May 16, 2020 |
| Lenovo        | ThinkPad T520 424329U       | Notebook    | [bf1c52908b](https://linux-hardware.org/?probe=bf1c52908b) | May 16, 2020 |
| System76      | Galago Pro                  | Notebook    | [3ae6d02922](https://linux-hardware.org/?probe=3ae6d02922) | May 14, 2020 |
| ASRock        | H97M Pro4                   | Desktop     | [deca13654e](https://linux-hardware.org/?probe=deca13654e) | May 13, 2020 |
| Intel         | DQ57TM AAE92694-401         | Desktop     | [c2abb26814](https://linux-hardware.org/?probe=c2abb26814) | May 11, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [f05f9404d0](https://linux-hardware.org/?probe=f05f9404d0) | May 11, 2020 |
| Gigabyte      | P15FV7                      | Notebook    | [a7031c2684](https://linux-hardware.org/?probe=a7031c2684) | May 09, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | Notebook    | [702d00f33c](https://linux-hardware.org/?probe=702d00f33c) | May 07, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [db25140369](https://linux-hardware.org/?probe=db25140369) | May 06, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [6f82171699](https://linux-hardware.org/?probe=6f82171699) | May 06, 2020 |
| Sony UK       | Raspberry Pi 3 Model B      | Soc         | [52f0b7d3fa](https://linux-hardware.org/?probe=52f0b7d3fa) | May 06, 2020 |
| Dell          | Latitude E7240              | Notebook    | [6f9d4efc51](https://linux-hardware.org/?probe=6f9d4efc51) | May 06, 2020 |
| Dell          | Latitude E7240              | Notebook    | [9e5819a0bc](https://linux-hardware.org/?probe=9e5819a0bc) | May 06, 2020 |
| Acer          | Okinawa                     | Notebook    | [9e22849a3a](https://linux-hardware.org/?probe=9e22849a3a) | May 03, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [e356fece67](https://linux-hardware.org/?probe=e356fece67) | May 01, 2020 |
| Dell          | 0FH884                      | Desktop     | [1f7976ed89](https://linux-hardware.org/?probe=1f7976ed89) | Apr 30, 2020 |
| Dell          | 0200DY A03                  | Desktop     | [473467f488](https://linux-hardware.org/?probe=473467f488) | Apr 29, 2020 |
| Dell          | XPS M1530                   | Notebook    | [ef2ddf50e9](https://linux-hardware.org/?probe=ef2ddf50e9) | Apr 28, 2020 |
| Dell          | XPS M1530                   | Notebook    | [9d8053a9f5](https://linux-hardware.org/?probe=9d8053a9f5) | Apr 28, 2020 |
| Lenovo        | ThinkPad X260 20F5S13K00    | Notebook    | [e6010acabe](https://linux-hardware.org/?probe=e6010acabe) | Apr 28, 2020 |
| Dell          | Precision 7510              | Notebook    | [40e5c33fd8](https://linux-hardware.org/?probe=40e5c33fd8) | Apr 27, 2020 |
| Dell          | Latitude E5570              | Notebook    | [4c46b3c18d](https://linux-hardware.org/?probe=4c46b3c18d) | Apr 27, 2020 |
| Dell          | 0FH884                      | Desktop     | [306c5d73fb](https://linux-hardware.org/?probe=306c5d73fb) | Apr 27, 2020 |
| Dell          | 0FH884                      | Desktop     | [9fd393aab9](https://linux-hardware.org/?probe=9fd393aab9) | Apr 27, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [9b6c98e396](https://linux-hardware.org/?probe=9b6c98e396) | Apr 26, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [0d9716a2e8](https://linux-hardware.org/?probe=0d9716a2e8) | Apr 26, 2020 |
| ABIT          | KN9                         | Desktop     | [6254e80aba](https://linux-hardware.org/?probe=6254e80aba) | Apr 26, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [951197ee19](https://linux-hardware.org/?probe=951197ee19) | Apr 25, 2020 |
| Dell          | Inspiron 15-3552            | Notebook    | [64015bca38](https://linux-hardware.org/?probe=64015bca38) | Apr 24, 2020 |
| Acer          | Aspire 7741                 | Notebook    | [85a10d5a0c](https://linux-hardware.org/?probe=85a10d5a0c) | Apr 24, 2020 |
| Dell          | XPS M1530                   | Notebook    | [0d21d60816](https://linux-hardware.org/?probe=0d21d60816) | Apr 22, 2020 |
| HP            | Presario F500 (GH835EA#A... | Notebook    | [9e0244765a](https://linux-hardware.org/?probe=9e0244765a) | Apr 21, 2020 |
| Medion        | Erazer X7843 MD99945        | Notebook    | [f63ebecfac](https://linux-hardware.org/?probe=f63ebecfac) | Apr 20, 2020 |
| Medion        | Erazer X7843 MD99945        | Notebook    | [caa46f1899](https://linux-hardware.org/?probe=caa46f1899) | Apr 20, 2020 |
| ABIT          | KN9                         | Desktop     | [be7c3f4dc9](https://linux-hardware.org/?probe=be7c3f4dc9) | Apr 14, 2020 |
| Dell          | Latitude E5450              | Notebook    | [a0de4692f3](https://linux-hardware.org/?probe=a0de4692f3) | Apr 12, 2020 |
| Dell          | Latitude E5450              | Notebook    | [b934bac9f3](https://linux-hardware.org/?probe=b934bac9f3) | Apr 12, 2020 |
| Apple         | MacBook6,1                  | Notebook    | [7eae555356](https://linux-hardware.org/?probe=7eae555356) | Apr 11, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d882ce78cd](https://linux-hardware.org/?probe=d882ce78cd) | Apr 09, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [75cee4eeef](https://linux-hardware.org/?probe=75cee4eeef) | Apr 08, 2020 |
| eMachines     | E627                        | Notebook    | [395c0dace2](https://linux-hardware.org/?probe=395c0dace2) | Apr 07, 2020 |
| Dell          | XPS M1530                   | Notebook    | [daf947b1f0](https://linux-hardware.org/?probe=daf947b1f0) | Apr 07, 2020 |
| Lenovo        | ThinkStation D20 415892G    | Desktop     | [79ceb06042](https://linux-hardware.org/?probe=79ceb06042) | Apr 05, 2020 |
| HP            | Pavilion dv6                | Notebook    | [5ae586911d](https://linux-hardware.org/?probe=5ae586911d) | Apr 05, 2020 |
| ASUSTek       | Z87-K                       | Desktop     | [2ccf545fb8](https://linux-hardware.org/?probe=2ccf545fb8) | Apr 03, 2020 |
| Dell          | 0P301D A00                  | Desktop     | [5996aa0d7b](https://linux-hardware.org/?probe=5996aa0d7b) | Apr 02, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4151ed01a0](https://linux-hardware.org/?probe=4151ed01a0) | Apr 01, 2020 |
| HP            | EliteBook 2560p             | Notebook    | [1b7dfeda09](https://linux-hardware.org/?probe=1b7dfeda09) | Mar 30, 2020 |
| HP            | EliteBook 2560p             | Notebook    | [c32ad7e810](https://linux-hardware.org/?probe=c32ad7e810) | Mar 30, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [9d50122997](https://linux-hardware.org/?probe=9d50122997) | Mar 30, 2020 |
| Lenovo        | ThinkPad X260 20F5S13K00    | Notebook    | [b2b7dfbc87](https://linux-hardware.org/?probe=b2b7dfbc87) | Mar 29, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [ec4f08053a](https://linux-hardware.org/?probe=ec4f08053a) | Mar 23, 2020 |
| ASUSTek       | Z87-PRO                     | Desktop     | [cf7a7cb442](https://linux-hardware.org/?probe=cf7a7cb442) | Mar 21, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [087223b15f](https://linux-hardware.org/?probe=087223b15f) | Mar 20, 2020 |
| Lenovo        | ThinkCentre A70 7844Q2G     | Desktop     | [7a3df56f82](https://linux-hardware.org/?probe=7a3df56f82) | Mar 20, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [9225b58c75](https://linux-hardware.org/?probe=9225b58c75) | Mar 18, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [1287493f4e](https://linux-hardware.org/?probe=1287493f4e) | Mar 18, 2020 |
| Gigabyte      | F2A58M-DS2                  | Desktop     | [b5c9d31ae9](https://linux-hardware.org/?probe=b5c9d31ae9) | Mar 18, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [989982faa3](https://linux-hardware.org/?probe=989982faa3) | Mar 18, 2020 |
| Dell          | 0J3C2F A00                  | Desktop     | [3a37c7a548](https://linux-hardware.org/?probe=3a37c7a548) | Mar 11, 2020 |
| Lenovo        | ThinkStation D20 415892G    | Desktop     | [6672072cc5](https://linux-hardware.org/?probe=6672072cc5) | Mar 03, 2020 |
| ABIT          | KN9                         | Desktop     | [dafc30ae16](https://linux-hardware.org/?probe=dafc30ae16) | Mar 02, 2020 |
| ABIT          | KN9                         | Desktop     | [e26e7f08ca](https://linux-hardware.org/?probe=e26e7f08ca) | Feb 23, 2020 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [11d467ac47](https://linux-hardware.org/?probe=11d467ac47) | Feb 22, 2020 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | Desktop     | [e53a35010c](https://linux-hardware.org/?probe=e53a35010c) | Feb 22, 2020 |
| Dell          | Precision M6300             | Notebook    | [6e9681a74e](https://linux-hardware.org/?probe=6e9681a74e) | Feb 18, 2020 |
| Dell          | Precision M6300             | Notebook    | [e45c0c7fc9](https://linux-hardware.org/?probe=e45c0c7fc9) | Feb 18, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [46dd15e54f](https://linux-hardware.org/?probe=46dd15e54f) | Feb 18, 2020 |
| Lenovo        | ThinkPad X250 20CLS3ST01    | Notebook    | [b7a710c050](https://linux-hardware.org/?probe=b7a710c050) | Feb 10, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [e5b58a2f40](https://linux-hardware.org/?probe=e5b58a2f40) | Feb 08, 2020 |
| ASUSTek       | E402BA                      | Notebook    | [ef0178479b](https://linux-hardware.org/?probe=ef0178479b) | Feb 08, 2020 |
| Lenovo        | ThinkPad X250 20CLS3ST01    | Notebook    | [51d20a3d12](https://linux-hardware.org/?probe=51d20a3d12) | Feb 06, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [917f6c18a4](https://linux-hardware.org/?probe=917f6c18a4) | Feb 05, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ec722fbbfe](https://linux-hardware.org/?probe=ec722fbbfe) | Feb 01, 2020 |
| HP            | 1998                        | Desktop     | [edb9bba986](https://linux-hardware.org/?probe=edb9bba986) | Jan 19, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [8143d2c859](https://linux-hardware.org/?probe=8143d2c859) | Dec 23, 2019 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [efc1ac12c7](https://linux-hardware.org/?probe=efc1ac12c7) | Dec 21, 2019 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [0f6f830f1b](https://linux-hardware.org/?probe=0f6f830f1b) | Dec 21, 2019 |
| Acer          | Aspire 8930                 | Notebook    | [3bd04b5cd7](https://linux-hardware.org/?probe=3bd04b5cd7) | Dec 09, 2019 |
| Lenovo        | ThinkPad T410 2539W4Y       | Notebook    | [009c5c142e](https://linux-hardware.org/?probe=009c5c142e) | Dec 06, 2019 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [0c3d1fcefe](https://linux-hardware.org/?probe=0c3d1fcefe) | Dec 05, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [706aee4776](https://linux-hardware.org/?probe=706aee4776) | Dec 04, 2019 |
| Apple         | MacBookPro5,2               | Notebook    | [3b3fd20d67](https://linux-hardware.org/?probe=3b3fd20d67) | Dec 01, 2019 |
| Apple         | MacBookPro5,2               | Notebook    | [4918587a5c](https://linux-hardware.org/?probe=4918587a5c) | Dec 01, 2019 |
| Apple         | MacBookPro5,2               | Notebook    | [0ef52aaec2](https://linux-hardware.org/?probe=0ef52aaec2) | Dec 01, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [187a7265f0](https://linux-hardware.org/?probe=187a7265f0) | Dec 01, 2019 |
| MSI           | Z77 MPower                  | Desktop     | [ab7afebfb6](https://linux-hardware.org/?probe=ab7afebfb6) | Nov 26, 2019 |
| MSI           | Z77 MPower                  | Desktop     | [77c87b6b71](https://linux-hardware.org/?probe=77c87b6b71) | Nov 26, 2019 |
| System76      | Galago Pro                  | Notebook    | [15393d43e8](https://linux-hardware.org/?probe=15393d43e8) | Nov 25, 2019 |
| Dell          | Latitude 7490               | Notebook    | [4c5f40f7f3](https://linux-hardware.org/?probe=4c5f40f7f3) | Oct 18, 2019 |
| System76      | Galago Pro                  | Notebook    | [463dd28c7d](https://linux-hardware.org/?probe=463dd28c7d) | Oct 17, 2019 |
| Acer          | Aspire 5736Z                | Notebook    | [5ba5b7d13a](https://linux-hardware.org/?probe=5ba5b7d13a) | Oct 17, 2019 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | Notebook    | [a2da44ce3d](https://linux-hardware.org/?probe=a2da44ce3d) | Oct 15, 2019 |
| Alienware     | 17 R4                       | Notebook    | [fa39f4bdb4](https://linux-hardware.org/?probe=fa39f4bdb4) | Oct 04, 2019 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | Notebook    | [b17cca251b](https://linux-hardware.org/?probe=b17cca251b) | Sep 30, 2019 |
| System76      | Galago Pro                  | Notebook    | [8122dc5996](https://linux-hardware.org/?probe=8122dc5996) | Sep 25, 2019 |
| Seco          | C40 C                       | Desktop     | [a3f6f85e6a](https://linux-hardware.org/?probe=a3f6f85e6a) | Sep 15, 2019 |
| Alienware     | 17 R4                       | Notebook    | [5287c00902](https://linux-hardware.org/?probe=5287c00902) | Sep 15, 2019 |
| System76      | Galago Pro                  | Notebook    | [7c1dbad22c](https://linux-hardware.org/?probe=7c1dbad22c) | Sep 11, 2019 |
| Acer          | Aspire ES1-512              | Notebook    | [6b82a86df6](https://linux-hardware.org/?probe=6b82a86df6) | Sep 08, 2019 |
| Seco          | C40 C                       | Desktop     | [16208d3700](https://linux-hardware.org/?probe=16208d3700) | Sep 04, 2019 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [e5fc9849a0](https://linux-hardware.org/?probe=e5fc9849a0) | Aug 30, 2019 |
| Seco          | C40 C                       | Desktop     | [3a7afd413f](https://linux-hardware.org/?probe=3a7afd413f) | Aug 28, 2019 |
| Acer          | Aspire ES1-512              | Notebook    | [11727f9491](https://linux-hardware.org/?probe=11727f9491) | Aug 19, 2019 |
| Acer          | Aspire ES1-512              | Notebook    | [6a08c4afd1](https://linux-hardware.org/?probe=6a08c4afd1) | Aug 17, 2019 |
| Toshiba       | Satellite L500              | Notebook    | [5819f81be3](https://linux-hardware.org/?probe=5819f81be3) | Aug 16, 2019 |
| ASUSTek       | K5130                       | Desktop     | [72b7a5b445](https://linux-hardware.org/?probe=72b7a5b445) | Aug 08, 2019 |
| Acer          | Aspire E1-572               | Notebook    | [96bf232f30](https://linux-hardware.org/?probe=96bf232f30) | Aug 03, 2019 |
| DFI           | INF P35                     | Desktop     | [7987560cdc](https://linux-hardware.org/?probe=7987560cdc) | Aug 02, 2019 |
| DFI           | INF P35                     | Desktop     | [0379ced795](https://linux-hardware.org/?probe=0379ced795) | Aug 02, 2019 |
| MiTAC         | PD14TI AAPD14TI-101         | Desktop     | [b7db1f6d08](https://linux-hardware.org/?probe=b7db1f6d08) | Jul 27, 2019 |
| MiTAC         | PD14TI AAPD14TI-101         | Desktop     | [bf4c96625e](https://linux-hardware.org/?probe=bf4c96625e) | Jul 27, 2019 |
| Advent        | Roma                        | Notebook    | [a7ec10f5ee](https://linux-hardware.org/?probe=a7ec10f5ee) | Jul 21, 2019 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [649ff143ad](https://linux-hardware.org/?probe=649ff143ad) | Jul 08, 2019 |
| System76      | Bonobo Extreme              | Notebook    | [aa49d07bb2](https://linux-hardware.org/?probe=aa49d07bb2) | Jul 05, 2019 |
| System76      | Bonobo Extreme              | Notebook    | [f867ec3a39](https://linux-hardware.org/?probe=f867ec3a39) | Jul 05, 2019 |
| Toshiba       | TECRA R850                  | Notebook    | [4398e73607](https://linux-hardware.org/?probe=4398e73607) | Jul 04, 2019 |
| ASUSTek       | F2A55-M LK2                 | Desktop     | [93d8ad05a1](https://linux-hardware.org/?probe=93d8ad05a1) | Jun 30, 2019 |
| AMI           | Aptio CRB                   | Mini pc     | [8f87769d12](https://linux-hardware.org/?probe=8f87769d12) | Jun 19, 2019 |
| HP            | Pavilion dv6                | Notebook    | [6cfff2060e](https://linux-hardware.org/?probe=6cfff2060e) | Jun 16, 2019 |
| HP            | Pavilion dv6                | Notebook    | [90df3b230e](https://linux-hardware.org/?probe=90df3b230e) | Jun 16, 2019 |
| HP            | Pavilion dv6                | Notebook    | [694239801c](https://linux-hardware.org/?probe=694239801c) | Jun 16, 2019 |
| Shuttle       | XS35V3                      | Desktop     | [de0cc0ab6f](https://linux-hardware.org/?probe=de0cc0ab6f) | Jun 16, 2019 |
| Toshiba       | Satellite L500              | Notebook    | [7fcd49c923](https://linux-hardware.org/?probe=7fcd49c923) | Jun 08, 2019 |
| Dell          | 0FJ030                      | Desktop     | [c3dfb2bea5](https://linux-hardware.org/?probe=c3dfb2bea5) | Jun 05, 2019 |
| Lenovo        | MAHOBAY                     | Desktop     | [71dd964fb5](https://linux-hardware.org/?probe=71dd964fb5) | Jun 04, 2019 |
| ASUSTek       | S550CA                      | Notebook    | [469e04e0d5](https://linux-hardware.org/?probe=469e04e0d5) | May 26, 2019 |
| ASRock        | G31M-S                      | Desktop     | [213f2f20b6](https://linux-hardware.org/?probe=213f2f20b6) | May 24, 2019 |
| Dell          | 0Y2MRG A00                  | Desktop     | [f32755062c](https://linux-hardware.org/?probe=f32755062c) | May 23, 2019 |
| Lenovo        | ThinkPad T420 4236RN1       | Notebook    | [a151a65fee](https://linux-hardware.org/?probe=a151a65fee) | May 21, 2019 |
| Lenovo        | ThinkPad T420 4236RN1       | Notebook    | [ba564750a2](https://linux-hardware.org/?probe=ba564750a2) | May 21, 2019 |
| ASUSTek       | K53U                        | Notebook    | [24a0045ecc](https://linux-hardware.org/?probe=24a0045ecc) | May 18, 2019 |
| ASUSTek       | K53U                        | Notebook    | [0f7bf61a9d](https://linux-hardware.org/?probe=0f7bf61a9d) | May 17, 2019 |
| Dell          | 03NVJ6 A02                  | Desktop     | [915e0bab53](https://linux-hardware.org/?probe=915e0bab53) | May 12, 2019 |
| ASUSTek       | S550CA                      | Notebook    | [afe6d9bfe2](https://linux-hardware.org/?probe=afe6d9bfe2) | Apr 28, 2019 |
| ASUSTek       | T100TA                      | Notebook    | [5025b4af94](https://linux-hardware.org/?probe=5025b4af94) | Apr 26, 2019 |
| Lenovo        | ThinkPad T440 20B7S1G40L    | Notebook    | [47b05c165f](https://linux-hardware.org/?probe=47b05c165f) | Apr 24, 2019 |
| Toshiba       | Satellite L50-C             | Notebook    | [ffca1399e5](https://linux-hardware.org/?probe=ffca1399e5) | Apr 17, 2019 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [b0dcc92563](https://linux-hardware.org/?probe=b0dcc92563) | Apr 03, 2019 |
| Dell          | Inspiron ME051              | Notebook    | [6d096d9aa6](https://linux-hardware.org/?probe=6d096d9aa6) | Mar 30, 2019 |
| Dell          | Inspiron ME051              | Notebook    | [a41940bc7f](https://linux-hardware.org/?probe=a41940bc7f) | Mar 30, 2019 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [6bae84797a](https://linux-hardware.org/?probe=6bae84797a) | Mar 22, 2019 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [9e86bfbcc2](https://linux-hardware.org/?probe=9e86bfbcc2) | Mar 22, 2019 |
| Shuttle       | FS35V4                      | Desktop     | [03af7dbe17](https://linux-hardware.org/?probe=03af7dbe17) | Mar 20, 2019 |
| Dell          | 0P7V82 A00                  | All in one  | [2bf103dd36](https://linux-hardware.org/?probe=2bf103dd36) | Feb 23, 2019 |
| Dell          | 0P7V82 A00                  | All in one  | [2907768caa](https://linux-hardware.org/?probe=2907768caa) | Feb 23, 2019 |
| Dell          | 0CRH6C A00                  | Desktop     | [300a99b1d0](https://linux-hardware.org/?probe=300a99b1d0) | Feb 10, 2019 |
| eMachines     | eM350                       | Notebook    | [e42feb9612](https://linux-hardware.org/?probe=e42feb9612) | Feb 06, 2019 |
| eMachines     | eM350                       | Notebook    | [f19d2e4452](https://linux-hardware.org/?probe=f19d2e4452) | Feb 06, 2019 |
| Dell          | Latitude E6400              | Notebook    | [75df21c3fd](https://linux-hardware.org/?probe=75df21c3fd) | Jan 25, 2019 |
| Shuttle       | XS35V3                      | Desktop     | [ae76390fb4](https://linux-hardware.org/?probe=ae76390fb4) | Jan 18, 2019 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [1cfe678b48](https://linux-hardware.org/?probe=1cfe678b48) | Jan 16, 2019 |
| Toshiba       | Satellite Pro C660          | Notebook    | [9b641633c5](https://linux-hardware.org/?probe=9b641633c5) | Nov 17, 2018 |
| Acer          | Swift SF114-31              | Notebook    | [96142e3044](https://linux-hardware.org/?probe=96142e3044) | Nov 01, 2018 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [2311962133](https://linux-hardware.org/?probe=2311962133) | Sep 30, 2018 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [6a91010c14](https://linux-hardware.org/?probe=6a91010c14) | Jul 07, 2018 |
| ASUSTek       | T102HA                      | Tablet      | [7c47ab2fd4](https://linux-hardware.org/?probe=7c47ab2fd4) | Jun 14, 2018 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [e5e3ed1c7c](https://linux-hardware.org/?probe=e5e3ed1c7c) | Jun 01, 2018 |
| Dell          | Latitude E6230              | Notebook    | [889c4720de](https://linux-hardware.org/?probe=889c4720de) | Mar 31, 2018 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [1d52b52b65](https://linux-hardware.org/?probe=1d52b52b65) | Feb 28, 2018 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [1b14483855](https://linux-hardware.org/?probe=1b14483855) | Feb 23, 2018 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [bbe4f7f994](https://linux-hardware.org/?probe=bbe4f7f994) | Feb 11, 2018 |
| Acer          | Aspire E5-575G              | Notebook    | [5d4b293327](https://linux-hardware.org/?probe=5d4b293327) | Feb 07, 2018 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [b32d7f9bc2](https://linux-hardware.org/?probe=b32d7f9bc2) | Jan 12, 2018 |
| Dell          | Latitude E6230              | Notebook    | [70a07251da](https://linux-hardware.org/?probe=70a07251da) | Oct 21, 2017 |
| Dell          | Latitude D620               | Notebook    | [6652d3973b](https://linux-hardware.org/?probe=6652d3973b) | Sep 28, 2017 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [7cf734ce05](https://linux-hardware.org/?probe=7cf734ce05) | Nov 04, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 78        | 17.69%  |
| Ubuntu 18.04                 | 47        | 10.66%  |
| OpenMandriva 4.2             | 12        | 2.72%   |
| Debian 10                    | 10        | 2.27%   |
| Ubuntu 19.04                 | 9         | 2.04%   |
| Pop!_OS 21.10                | 9         | 2.04%   |
| Manjaro                      | 9         | 2.04%   |
| Linux Mint 20.2              | 9         | 2.04%   |
| Linux Mint 20                | 9         | 2.04%   |
| ArcoLinux Rolling            | 9         | 2.04%   |
| Arch                         | 9         | 2.04%   |
| Pop!_OS 20.10                | 8         | 1.81%   |
| Debian 11                    | 8         | 1.81%   |
| Pop!_OS 20.04                | 7         | 1.59%   |
| KDE neon 20.04               | 7         | 1.59%   |
| BlackPanther 18.1            | 7         | 1.59%   |
| Ubuntu 19.10                 | 6         | 1.36%   |
| Ubuntu 21.10                 | 5         | 1.13%   |
| ROSA R11                     | 5         | 1.13%   |
| ROSA R10                     | 5         | 1.13%   |
| Linux Mint 20.1              | 5         | 1.13%   |
| Linux Mint 19.3              | 5         | 1.13%   |
| Fedora 35                    | 5         | 1.13%   |
| Fedora 33                    | 5         | 1.13%   |
| Fedora 32                    | 5         | 1.13%   |
| Arch Rolling                 | 5         | 1.13%   |
| Zorin 16                     | 4         | 0.91%   |
| Zorin 15                     | 4         | 0.91%   |
| Ubuntu 20.10                 | 4         | 0.91%   |
| Ubuntu 16.04                 | 4         | 0.91%   |
| Fedora 34                    | 4         | 0.91%   |
| Debian Unstable              | 4         | 0.91%   |
| Pop!_OS 22.04                | 3         | 0.68%   |
| Pop!_OS 21.04                | 3         | 0.68%   |
| OpenMandriva 4.50            | 3         | 0.68%   |
| OpenMandriva 4.3             | 3         | 0.68%   |
| Lubuntu 20.04                | 3         | 0.68%   |
| Linux Mint 19.2              | 3         | 0.68%   |
| Linux Mint 19.1              | 3         | 0.68%   |
| Linux Mint 19                | 3         | 0.68%   |
| Linux Mint 18.3              | 3         | 0.68%   |
| Kubuntu 20.04                | 3         | 0.68%   |
| Endless 3.7.8                | 3         | 0.68%   |
| Xubuntu 20.04                | 2         | 0.45%   |
| Ubuntu MATE 20.04            | 2         | 0.45%   |
| ROSA R9                      | 2         | 0.45%   |
| ROSA R11.1                   | 2         | 0.45%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.45%   |
| Manjaro 21.0.7               | 2         | 0.45%   |
| Manjaro 21.0.5               | 2         | 0.45%   |
| Manjaro 20.2                 | 2         | 0.45%   |
| Kubuntu 21.10                | 2         | 0.45%   |
| Kubuntu 21.04                | 2         | 0.45%   |
| Kubuntu 20.10                | 2         | 0.45%   |
| KDE neon 18.04               | 2         | 0.45%   |
| Gentoo 2.7                   | 2         | 0.45%   |
| Fedora 36                    | 2         | 0.45%   |
| Elementary 5.1.7             | 2         | 0.45%   |
| Debian 9                     | 2         | 0.45%   |
| Xubuntu 20.10                | 1         | 0.23%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 155       | 36.82%  |
| Linux Mint    | 36        | 8.55%   |
| Pop!_OS       | 28        | 6.65%   |
| Debian        | 25        | 5.94%   |
| Manjaro       | 21        | 4.99%   |
| Fedora        | 21        | 4.99%   |
| OpenMandriva  | 18        | 4.28%   |
| Arch          | 14        | 3.33%   |
| ROSA          | 12        | 2.85%   |
| Kubuntu       | 10        | 2.38%   |
| ArcoLinux     | 9         | 2.14%   |
| Zorin         | 8         | 1.9%    |
| KDE neon      | 8         | 1.9%    |
| BlackPanther  | 7         | 1.66%   |
| Elementary    | 6         | 1.43%   |
| Lubuntu       | 5         | 1.19%   |
| Endless       | 5         | 1.19%   |
| openSUSE      | 4         | 0.95%   |
| Xubuntu       | 3         | 0.71%   |
| Ubuntu Budgie | 3         | 0.71%   |
| Gentoo        | 3         | 0.71%   |
| Clear Linux   | 3         | 0.71%   |
| Ubuntu MATE   | 2         | 0.48%   |
| Peppermint    | 2         | 0.48%   |
| Kali          | 2         | 0.48%   |
| CentOS        | 2         | 0.48%   |
| Trisquel      | 1         | 0.24%   |
| SteamOS       | 1         | 0.24%   |
| Solus         | 1         | 0.24%   |
| RHEL          | 1         | 0.24%   |
| MX            | 1         | 0.24%   |
| LMDE          | 1         | 0.24%   |
| Linux Lite    | 1         | 0.24%   |
| Feren OS      | 1         | 0.24%   |
| Chrome OS     | 1         | 0.24%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.4.0-42-generic                | 15        | 3.11%   |
| 5.10.14-desktop-1omv4002        | 12        | 2.48%   |
| 5.3.0-46-generic                | 10        | 2.07%   |
| 5.4.0-52-generic                | 6         | 1.24%   |
| 4.18.16-desktop-1bP             | 6         | 1.24%   |
| 5.4.0-91-generic                | 5         | 1.04%   |
| 5.4.0-48-generic                | 5         | 1.04%   |
| 5.11.0-27-generic               | 5         | 1.04%   |
| 5.8.0-7630-generic              | 4         | 0.83%   |
| 5.8.0-43-generic                | 4         | 0.83%   |
| 5.4.0-72-generic                | 4         | 0.83%   |
| 5.4.0-47-generic                | 4         | 0.83%   |
| 5.4.0-31-generic                | 4         | 0.83%   |
| 5.4.0-29-generic                | 4         | 0.83%   |
| 5.4.0-26-generic                | 4         | 0.83%   |
| 5.3.0-28-generic                | 4         | 0.83%   |
| 4.18.0-15-generic               | 4         | 0.83%   |
| 5.8.0-53-generic                | 3         | 0.62%   |
| 5.8.0-41-generic                | 3         | 0.62%   |
| 5.4.0-77-generic                | 3         | 0.62%   |
| 5.4.0-7634-generic              | 3         | 0.62%   |
| 5.4.0-58-generic                | 3         | 0.62%   |
| 5.4.0-54-generic                | 3         | 0.62%   |
| 5.4.0-40-generic                | 3         | 0.62%   |
| 5.4.0-39-generic                | 3         | 0.62%   |
| 5.4.0-37-generic                | 3         | 0.62%   |
| 5.3.0-45-generic                | 3         | 0.62%   |
| 5.3.0-40-generic                | 3         | 0.62%   |
| 5.17.5-arch1-1                  | 3         | 0.62%   |
| 5.16.7-desktop-1omv4003         | 3         | 0.62%   |
| 5.16.15-76051615-generic        | 3         | 0.62%   |
| 5.15.11-76051511-generic        | 3         | 0.62%   |
| 5.12.4-desktop-1omv4050         | 3         | 0.62%   |
| 5.11.0-38-generic               | 3         | 0.62%   |
| 5.10.0-8-amd64                  | 3         | 0.62%   |
| 5.0.0-25-generic                | 3         | 0.62%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 3         | 0.62%   |
| 4.9.60-nrj-desktop-1rosa-i586   | 3         | 0.62%   |
| 4.19.0-9-amd64                  | 3         | 0.62%   |
| 4.15.0-50-generic               | 3         | 0.62%   |
| 4.10.0-38-generic               | 3         | 0.62%   |
| 5.8.14-arch1-1                  | 2         | 0.41%   |
| 5.8.0-7625-generic              | 2         | 0.41%   |
| 5.8.0-33-generic                | 2         | 0.41%   |
| 5.8.0-26-generic                | 2         | 0.41%   |
| 5.7.12-arch1-1                  | 2         | 0.41%   |
| 5.4.0-88-generic                | 2         | 0.41%   |
| 5.4.0-80-generic                | 2         | 0.41%   |
| 5.4.0-7625-generic              | 2         | 0.41%   |
| 5.4.0-73-generic                | 2         | 0.41%   |
| 5.4.0-70-generic                | 2         | 0.41%   |
| 5.4.0-65-generic                | 2         | 0.41%   |
| 5.4.0-62-generic                | 2         | 0.41%   |
| 5.4.0-56-generic                | 2         | 0.41%   |
| 5.4.0-53-generic                | 2         | 0.41%   |
| 5.4.0-51-generic                | 2         | 0.41%   |
| 5.4.0-13-generic                | 2         | 0.41%   |
| 5.3.0-53-generic                | 2         | 0.41%   |
| 5.3.0-18-generic                | 2         | 0.41%   |
| 5.17.5-76051705-generic         | 2         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 105       | 23.28%  |
| 4.15.0  | 36        | 7.98%   |
| 5.8.0   | 28        | 6.21%   |
| 5.3.0   | 26        | 5.76%   |
| 5.11.0  | 25        | 5.54%   |
| 5.13.0  | 15        | 3.33%   |
| 5.0.0   | 15        | 3.33%   |
| 5.10.14 | 12        | 2.66%   |
| 4.19.0  | 11        | 2.44%   |
| 4.18.0  | 11        | 2.44%   |
| 5.10.0  | 10        | 2.22%   |
| 5.17.5  | 7         | 1.55%   |
| 4.18.16 | 6         | 1.33%   |
| 5.16.11 | 4         | 0.89%   |
| 4.9.60  | 4         | 0.89%   |
| 5.8.14  | 3         | 0.67%   |
| 5.6.0   | 3         | 0.67%   |
| 5.16.7  | 3         | 0.67%   |
| 5.16.15 | 3         | 0.67%   |
| 5.15.12 | 3         | 0.67%   |
| 5.15.11 | 3         | 0.67%   |
| 5.12.4  | 3         | 0.67%   |
| 4.9.155 | 3         | 0.67%   |
| 4.10.0  | 3         | 0.67%   |
| 5.7.9   | 2         | 0.44%   |
| 5.7.12  | 2         | 0.44%   |
| 5.6.7   | 2         | 0.44%   |
| 5.6.15  | 2         | 0.44%   |
| 5.15.7  | 2         | 0.44%   |
| 5.15.6  | 2         | 0.44%   |
| 5.15.5  | 2         | 0.44%   |
| 5.15.0  | 2         | 0.44%   |
| 5.13.19 | 2         | 0.44%   |
| 5.13.13 | 2         | 0.44%   |
| 5.12.8  | 2         | 0.44%   |
| 5.12.2  | 2         | 0.44%   |
| 5.11.11 | 2         | 0.44%   |
| 5.11.10 | 2         | 0.44%   |
| 5.10.42 | 2         | 0.44%   |
| 5.10.2  | 2         | 0.44%   |
| 4.9.41  | 2         | 0.44%   |
| 4.13.0  | 2         | 0.44%   |
| 4.12.14 | 2         | 0.44%   |
| 3.10.0  | 2         | 0.44%   |
| 5.9.3   | 1         | 0.22%   |
| 5.9.16  | 1         | 0.22%   |
| 5.9.11  | 1         | 0.22%   |
| 5.9.1   | 1         | 0.22%   |
| 5.9.0   | 1         | 0.22%   |
| 5.9     | 1         | 0.22%   |
| 5.8.7   | 1         | 0.22%   |
| 5.8.18  | 1         | 0.22%   |
| 5.8.11  | 1         | 0.22%   |
| 5.8.10  | 1         | 0.22%   |
| 5.7.8   | 1         | 0.22%   |
| 5.7.7   | 1         | 0.22%   |
| 5.7.11  | 1         | 0.22%   |
| 5.6.3   | 1         | 0.22%   |
| 5.6.14  | 1         | 0.22%   |
| 5.6.10  | 1         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 110       | 24.89%  |
| 4.15    | 36        | 8.14%   |
| 5.8     | 35        | 7.92%   |
| 5.10    | 35        | 7.92%   |
| 5.11    | 31        | 7.01%   |
| 5.3     | 27        | 6.11%   |
| 5.13    | 21        | 4.75%   |
| 4.18    | 17        | 3.85%   |
| 5.15    | 16        | 3.62%   |
| 5.0     | 15        | 3.39%   |
| 5.17    | 12        | 2.71%   |
| 5.16    | 12        | 2.71%   |
| 4.19    | 12        | 2.71%   |
| 4.9     | 11        | 2.49%   |
| 5.6     | 10        | 2.26%   |
| 5.12    | 9         | 2.04%   |
| 5.7     | 7         | 1.58%   |
| 5.9     | 5         | 1.13%   |
| 5.14    | 5         | 1.13%   |
| 4.10    | 3         | 0.68%   |
| 4.4     | 2         | 0.45%   |
| 4.13    | 2         | 0.45%   |
| 4.12    | 2         | 0.45%   |
| 3.10    | 2         | 0.45%   |
| 5.5     | 1         | 0.23%   |
| 5.2     | 1         | 0.23%   |
| 5       | 1         | 0.23%   |
| 4.14    | 1         | 0.23%   |
| 4.1     | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 387       | 94.62%  |
| i686    | 15        | 3.67%   |
| aarch64 | 7         | 1.71%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 184       | 42.69%  |
| Unknown         | 66        | 15.31%  |
| KDE5            | 63        | 14.62%  |
| XFCE            | 28        | 6.5%    |
| X-Cinnamon      | 21        | 4.87%   |
| KDE             | 18        | 4.18%   |
| MATE            | 8         | 1.86%   |
| Cinnamon        | 7         | 1.62%   |
| LXQt            | 6         | 1.39%   |
| KDE4            | 6         | 1.39%   |
| Unity           | 5         | 1.16%   |
| Pantheon        | 5         | 1.16%   |
| i3              | 4         | 0.93%   |
| Budgie          | 3         | 0.7%    |
| GNOME Flashback | 2         | 0.46%   |
| GNOME Classic   | 2         | 0.46%   |
| LXDE            | 1         | 0.23%   |
| LeftWM          | 1         | 0.23%   |
| Enlightenment   | 1         | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 340       | 82.52%  |
| Unknown | 38        | 9.22%   |
| Wayland | 27        | 6.55%   |
| Tty     | 7         | 1.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 242       | 57.89%  |
| SDDM    | 62        | 14.83%  |
| GDM     | 52        | 12.44%  |
| LightDM | 26        | 6.22%   |
| TDM     | 19        | 4.55%   |
| GDM3    | 10        | 2.39%   |
| KDM     | 6         | 1.44%   |
| LXDM    | 1         | 0.24%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_IE   | 202       | 47.87%  |
| en_US   | 66        | 15.64%  |
| Unknown | 66        | 15.64%  |
| en_GB   | 64        | 15.17%  |
| pl_PL   | 10        | 2.37%   |
| es_ES   | 2         | 0.47%   |
| en_CA   | 2         | 0.47%   |
| C       | 2         | 0.47%   |
| bg_BG   | 2         | 0.47%   |
| ru_RU   | 1         | 0.24%   |
| pt_PT   | 1         | 0.24%   |
| it_IT   | 1         | 0.24%   |
| ga_IE   | 1         | 0.24%   |
| fr_FR   | 1         | 0.24%   |
| fr_BE   | 1         | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 221       | 53.64%  |
| EFI  | 191       | 46.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Ext4                | 325       | 79.08%  |
| Overlay             | 30        | 7.3%    |
| Unknown             | 23        | 5.6%    |
| Btrfs               | 22        | 5.35%   |
| Xfs                 | 5         | 1.22%   |
| Zfs                 | 4         | 0.97%   |
| Fuse.fuse-overlayfs | 1         | 0.24%   |
| F2fs                | 1         | 0.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 245       | 59.32%  |
| GPT     | 125       | 30.27%  |
| MBR     | 43        | 10.41%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 351       | 85.19%  |
| Yes       | 61        | 14.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 300       | 72.46%  |
| Yes       | 114       | 27.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 79        | 19.41%  |
| Lenovo                  | 70        | 17.2%   |
| ASUSTek Computer        | 52        | 12.78%  |
| Hewlett-Packard         | 48        | 11.79%  |
| Gigabyte Technology     | 20        | 4.91%   |
| Acer                    | 19        | 4.67%   |
| MSI                     | 15        | 3.69%   |
| Apple                   | 14        | 3.44%   |
| ASRock                  | 12        | 2.95%   |
| Toshiba                 | 10        | 2.46%   |
| Intel                   | 6         | 1.47%   |
| TUXEDO                  | 4         | 0.98%   |
| Samsung Electronics     | 4         | 0.98%   |
| PC Specialist           | 4         | 0.98%   |
| Medion                  | 4         | 0.98%   |
| Notebook                | 3         | 0.74%   |
| Foxconn                 | 3         | 0.74%   |
| Timi                    | 2         | 0.49%   |
| System76                | 2         | 0.49%   |
| Shuttle                 | 2         | 0.49%   |
| Seco                    | 2         | 0.49%   |
| Raspberry Pi Foundation | 2         | 0.49%   |
| Packard Bell            | 2         | 0.49%   |
| Nvidia                  | 2         | 0.49%   |
| HUAWEI                  | 2         | 0.49%   |
| Entroware               | 2         | 0.49%   |
| eMachines               | 2         | 0.49%   |
| Chuwi                   | 2         | 0.49%   |
| Sony UK                 | 1         | 0.25%   |
| Sony                    | 1         | 0.25%   |
| SLIMBOOK                | 1         | 0.25%   |
| Schenker                | 1         | 0.25%   |
| Rockchip                | 1         | 0.25%   |
| Pine Microsystems       | 1         | 0.25%   |
| Pegatron                | 1         | 0.25%   |
| MiTAC                   | 1         | 0.25%   |
| Microtech               | 1         | 0.25%   |
| IP3 Tech                | 1         | 0.25%   |
| Fujitsu Siemens         | 1         | 0.25%   |
| DFI                     | 1         | 0.25%   |
| AVITA                   | 1         | 0.25%   |
| AMI                     | 1         | 0.25%   |
| Alienware               | 1         | 0.25%   |
| Advent                  | 1         | 0.25%   |
| ABIT                    | 1         | 0.25%   |
| Unknown                 | 1         | 0.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 5         | 1.23%   |
| Gigabyte B450M DS3H                      | 4         | 0.98%   |
| Lenovo V145-15AST 81MT                   | 3         | 0.74%   |
| HP Compaq 8200 Elite SFF PC              | 3         | 0.74%   |
| Dell OptiPlex 790                        | 3         | 0.74%   |
| Dell OptiPlex 7010                       | 3         | 0.74%   |
| ASUS ROG STRIX B450-F GAMING             | 3         | 0.74%   |
| TUXEDO Pulse 15 Gen1                     | 2         | 0.49%   |
| Seco C40                                 | 2         | 0.49%   |
| RPi Raspberry Pi                         | 2         | 0.49%   |
| Nvidia Tegra                             | 2         | 0.49%   |
| MSI MS-7B79                              | 2         | 0.49%   |
| Lenovo ThinkStation D20 415892G          | 2         | 0.49%   |
| Lenovo ThinkPad X1 Carbon 3443CTO        | 2         | 0.49%   |
| Lenovo IdeaPad 510-15ISK 80SR            | 2         | 0.49%   |
| HP Notebook                              | 2         | 0.49%   |
| HP EliteDesk 800 G1 SFF                  | 2         | 0.49%   |
| Gigabyte X570 AORUS ULTRA                | 2         | 0.49%   |
| Dell XPS 13 9310                         | 2         | 0.49%   |
| Dell XPS 13 9300                         | 2         | 0.49%   |
| Dell XPS 13 7390                         | 2         | 0.49%   |
| Dell Precision 5550                      | 2         | 0.49%   |
| Dell OptiPlex 780                        | 2         | 0.49%   |
| Dell OptiPlex 7020                       | 2         | 0.49%   |
| Dell Latitude E6230                      | 2         | 0.49%   |
| Dell Inspiron 13-5378                    | 2         | 0.49%   |
| ASUS TUF Gaming X570-PLUS                | 2         | 0.49%   |
| ASUS P8P67 PRO                           | 2         | 0.49%   |
| ASUS M5A78L/USB3                         | 2         | 0.49%   |
| Apple MacBook6,1                         | 2         | 0.49%   |
| Acer Aspire E5-575G                      | 2         | 0.49%   |
| Unknown                                  | 2         | 0.49%   |
| TUXEDO InfinityBook Pro 15 v5            | 1         | 0.25%   |
| TUXEDO InfinityBook Pro 14 Gen6          | 1         | 0.25%   |
| Toshiba TECRA R850                       | 1         | 0.25%   |
| Toshiba TECRA M4                         | 1         | 0.25%   |
| Toshiba Satellite Pro R50-B              | 1         | 0.25%   |
| Toshiba Satellite Pro C660               | 1         | 0.25%   |
| Toshiba Satellite L500                   | 1         | 0.25%   |
| Toshiba Satellite L50-C                  | 1         | 0.25%   |
| Toshiba Satellite L50-B                  | 1         | 0.25%   |
| Toshiba Satellite C50-B                  | 1         | 0.25%   |
| Toshiba Satellite A300                   | 1         | 0.25%   |
| Toshiba PORTEGE R830                     | 1         | 0.25%   |
| Timi TM1703                              | 1         | 0.25%   |
| Timi TM1607                              | 1         | 0.25%   |
| System76 Galago Pro                      | 1         | 0.25%   |
| System76 Bonobo Extreme                  | 1         | 0.25%   |
| Sony VPCCB35FG                           | 1         | 0.25%   |
| Sony UK Raspberry Pi 3 Model B           | 1         | 0.25%   |
| SLIMBOOK PROX15                          | 1         | 0.25%   |
| Shuttle XS35V4                           | 1         | 0.25%   |
| Shuttle XS35V3                           | 1         | 0.25%   |
| Schenker XMG NEO (TGL/M21)               | 1         | 0.25%   |
| Samsung N150/N210/N220                   | 1         | 0.25%   |
| Samsung Galaxy TabPro S                  | 1         | 0.25%   |
| Samsung 550P5C/550P7C                    | 1         | 0.25%   |
| Samsung 350V5C/351V5C/3540VC/3440VC      | 1         | 0.25%   |
| Pine Microsystems Pine64 PinePhone (1.2) | 1         | 0.25%   |
| Pegatron Pro 3010 Microtower PC          | 1         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 31        | 7.62%   |
| Dell Latitude       | 23        | 5.65%   |
| Dell OptiPlex       | 15        | 3.69%   |
| Dell Inspiron       | 14        | 3.44%   |
| Acer Aspire         | 14        | 3.44%   |
| Lenovo IdeaPad      | 12        | 2.95%   |
| Dell XPS            | 10        | 2.46%   |
| HP Pavilion         | 9         | 2.21%   |
| HP EliteBook        | 9         | 2.21%   |
| Dell Precision      | 8         | 1.97%   |
| Toshiba Satellite   | 7         | 1.72%   |
| Lenovo ThinkCentre  | 7         | 1.72%   |
| HP Compaq           | 7         | 1.72%   |
| ASUS TUF            | 6         | 1.47%   |
| ASUS PRIME          | 6         | 1.47%   |
| ASUS ROG            | 5         | 1.23%   |
| ASUS All            | 5         | 1.23%   |
| Gigabyte B450M      | 4         | 0.98%   |
| Dell Vostro         | 4         | 0.98%   |
| Lenovo Yoga         | 3         | 0.74%   |
| Lenovo V145-15AST   | 3         | 0.74%   |
| HP Presario         | 3         | 0.74%   |
| HP Laptop           | 3         | 0.74%   |
| HP EliteDesk        | 3         | 0.74%   |
| Apple MacBookPro5   | 3         | 0.74%   |
| TUXEDO Pulse        | 2         | 0.49%   |
| TUXEDO InfinityBook | 2         | 0.49%   |
| Toshiba TECRA       | 2         | 0.49%   |
| Seco C40            | 2         | 0.49%   |
| RPi Raspberry       | 2         | 0.49%   |
| Nvidia Tegra        | 2         | 0.49%   |
| MSI MS-7B79         | 2         | 0.49%   |
| Lenovo ThinkStation | 2         | 0.49%   |
| HP Notebook         | 2         | 0.49%   |
| Gigabyte X570       | 2         | 0.49%   |
| Gigabyte B450       | 2         | 0.49%   |
| Foxconn Pro         | 2         | 0.49%   |
| Dell Studio         | 2         | 0.49%   |
| ASUS ZenBook        | 2         | 0.49%   |
| ASUS P8P67          | 2         | 0.49%   |
| ASUS Maximus        | 2         | 0.49%   |
| ASUS M5A78L         | 2         | 0.49%   |
| ASUS CROSSHAIR      | 2         | 0.49%   |
| ASRock Z77          | 2         | 0.49%   |
| Apple MacBook6      | 2         | 0.49%   |
| Unknown             | 2         | 0.49%   |
| Toshiba PORTEGE     | 1         | 0.25%   |
| Timi TM1703         | 1         | 0.25%   |
| Timi TM1607         | 1         | 0.25%   |
| System76 Galago     | 1         | 0.25%   |
| System76 Bonobo     | 1         | 0.25%   |
| Sony VPCCB35FG      | 1         | 0.25%   |
| Sony UK Raspberry   | 1         | 0.25%   |
| SLIMBOOK PROX15     | 1         | 0.25%   |
| Shuttle XS35V4      | 1         | 0.25%   |
| Shuttle XS35V3      | 1         | 0.25%   |
| Schenker XMG        | 1         | 0.25%   |
| Samsung N150        | 1         | 0.25%   |
| Samsung Galaxy      | 1         | 0.25%   |
| Samsung 550P5C      | 1         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 44        | 10.81%  |
| 2018    | 42        | 10.32%  |
| 2013    | 36        | 8.85%   |
| 2012    | 35        | 8.6%    |
| 2011    | 34        | 8.35%   |
| 2020    | 31        | 7.62%   |
| 2017    | 29        | 7.13%   |
| 2010    | 25        | 6.14%   |
| 2008    | 23        | 5.65%   |
| 2015    | 19        | 4.67%   |
| 2016    | 18        | 4.42%   |
| 2009    | 17        | 4.18%   |
| 2021    | 15        | 3.69%   |
| 2014    | 15        | 3.69%   |
| 2007    | 9         | 2.21%   |
| 2006    | 6         | 1.47%   |
| Unknown | 6         | 1.47%   |
| 2005    | 2         | 0.49%   |
| 2003    | 1         | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 236       | 57.99%  |
| Desktop        | 142       | 34.89%  |
| Convertible    | 7         | 1.72%   |
| System on chip | 6         | 1.47%   |
| Mini pc        | 6         | 1.47%   |
| All in one     | 6         | 1.47%   |
| Tablet         | 3         | 0.74%   |
| Phone          | 1         | 0.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 372       | 90.73%  |
| Enabled  | 38        | 9.27%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 407       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 95        | 22.84%  |
| 3.01-4.0    | 83        | 19.95%  |
| 16.01-24.0  | 83        | 19.95%  |
| 8.01-16.0   | 73        | 17.55%  |
| 32.01-64.0  | 41        | 9.86%   |
| 1.01-2.0    | 16        | 3.85%   |
| 64.01-256.0 | 10        | 2.4%    |
| 24.01-32.0  | 6         | 1.44%   |
| 2.01-3.0    | 5         | 1.2%    |
| 0.51-1.0    | 3         | 0.72%   |
| 0.01-0.5    | 1         | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 165       | 36.91%  |
| 2.01-3.0   | 109       | 24.38%  |
| 3.01-4.0   | 62        | 13.87%  |
| 4.01-8.0   | 51        | 11.41%  |
| 0.51-1.0   | 37        | 8.28%   |
| 8.01-16.0  | 14        | 3.13%   |
| 0.01-0.5   | 5         | 1.12%   |
| 16.01-24.0 | 3         | 0.67%   |
| 32.01-64.0 | 1         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 250       | 58.28%  |
| 2      | 99        | 23.08%  |
| 3      | 34        | 7.93%   |
| 4      | 19        | 4.43%   |
| 5      | 11        | 2.56%   |
| 7      | 5         | 1.17%   |
| 6      | 4         | 0.93%   |
| 0      | 4         | 0.93%   |
| 10     | 2         | 0.47%   |
| 9      | 1         | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 237       | 57.25%  |
| Yes       | 177       | 42.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 354       | 86.98%  |
| No        | 53        | 13.02%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 337       | 82.4%   |
| No        | 72        | 17.6%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 255       | 61.59%  |
| No        | 159       | 38.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Ireland | 407       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Dublin              | 239       | 56.9%   |
| Cork                | 22        | 5.24%   |
| Limerick            | 14        | 3.33%   |
| Naas                | 11        | 2.62%   |
| Galway              | 10        | 2.38%   |
| Ennis               | 6         | 1.43%   |
| Drogheda            | 6         | 1.43%   |
| Portlaoise          | 5         | 1.19%   |
| Navan               | 5         | 1.19%   |
| Sligo               | 4         | 0.95%   |
| Kenmare             | 4         | 0.95%   |
| Gorey               | 4         | 0.95%   |
| Athlone             | 4         | 0.95%   |
| Tuam                | 3         | 0.71%   |
| Nenagh              | 3         | 0.71%   |
| Kilkenny            | 3         | 0.71%   |
| Enniscorthy         | 3         | 0.71%   |
| Dún Laoghaire      | 3         | 0.71%   |
| Wexford             | 2         | 0.48%   |
| Westport            | 2         | 0.48%   |
| Waterford           | 2         | 0.48%   |
| Oranmore            | 2         | 0.48%   |
| Maynooth            | 2         | 0.48%   |
| Mallow              | 2         | 0.48%   |
| Loughrea            | 2         | 0.48%   |
| Letterkenny         | 2         | 0.48%   |
| Cobh                | 2         | 0.48%   |
| Clonakilty          | 2         | 0.48%   |
| Cavan               | 2         | 0.48%   |
| Bray                | 2         | 0.48%   |
| Ballina             | 2         | 0.48%   |
| Balbriggan          | 2         | 0.48%   |
| Youghal             | 1         | 0.24%   |
| Wicklow             | 1         | 0.24%   |
| Tullamore           | 1         | 0.24%   |
| Tobercurry          | 1         | 0.24%   |
| Tipperary           | 1         | 0.24%   |
| Swords              | 1         | 0.24%   |
| Summerhill          | 1         | 0.24%   |
| Slane               | 1         | 0.24%   |
| Shanagolden         | 1         | 0.24%   |
| Scarriff            | 1         | 0.24%   |
| Santry              | 1         | 0.24%   |
| Newmarket on Fergus | 1         | 0.24%   |
| New Ross            | 1         | 0.24%   |
| Moyne               | 1         | 0.24%   |
| Midleton            | 1         | 0.24%   |
| Lucan               | 1         | 0.24%   |
| Leixlip             | 1         | 0.24%   |
| Kilrush             | 1         | 0.24%   |
| Killorglin          | 1         | 0.24%   |
| Kildare             | 1         | 0.24%   |
| Kilcoole            | 1         | 0.24%   |
| Greystones          | 1         | 0.24%   |
| Enfield             | 1         | 0.24%   |
| Edenderry           | 1         | 0.24%   |
| Dunshaughlin        | 1         | 0.24%   |
| Dungarvan           | 1         | 0.24%   |
| Drumcondra          | 1         | 0.24%   |
| Droichead Nua       | 1         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 114       | 191    | 18.57%  |
| Samsung Electronics       | 104       | 149    | 16.94%  |
| Seagate                   | 80        | 135    | 13.03%  |
| Toshiba                   | 41        | 51     | 6.68%   |
| Crucial                   | 32        | 41     | 5.21%   |
| Unknown                   | 31        | 39     | 5.05%   |
| SanDisk                   | 31        | 39     | 5.05%   |
| Hitachi                   | 30        | 42     | 4.89%   |
| Kingston                  | 19        | 25     | 3.09%   |
| Intel                     | 12        | 15     | 1.95%   |
| HGST                      | 10        | 10     | 1.63%   |
| Micron Technology         | 9         | 10     | 1.47%   |
| A-DATA Technology         | 9         | 14     | 1.47%   |
| Fujitsu                   | 7         | 8      | 1.14%   |
| SK Hynix                  | 6         | 6      | 0.98%   |
| Phison                    | 5         | 10     | 0.81%   |
| Verbatim                  | 4         | 4      | 0.65%   |
| PNY                       | 4         | 4      | 0.65%   |
| LITEON                    | 4         | 4      | 0.65%   |
| China                     | 4         | 7      | 0.65%   |
| Apple                     | 4         | 5      | 0.65%   |
| Silicon Motion            | 3         | 5      | 0.49%   |
| OCZ                       | 3         | 3      | 0.49%   |
| Micron/Crucial Technology | 3         | 4      | 0.49%   |
| KingSpec                  | 3         | 3      | 0.49%   |
| ASMT                      | 3         | 5      | 0.49%   |
| Transcend                 | 2         | 2      | 0.33%   |
| Team                      | 2         | 2      | 0.33%   |
| Netac                     | 2         | 2      | 0.33%   |
| MAXTOR                    | 2         | 2      | 0.33%   |
| KIOXIA                    | 2         | 3      | 0.33%   |
| KingDian                  | 2         | 5      | 0.33%   |
| Integral                  | 2         | 2      | 0.33%   |
| Zheino                    | 1         | 1      | 0.16%   |
| WDS100T1                  | 1         | 1      | 0.16%   |
| W800S                     | 1         | 2      | 0.16%   |
| USB3.0                    | 1         | 1      | 0.16%   |
| Union Memory (Shenzhen)   | 1         | 1      | 0.16%   |
| Union Memory              | 1         | 1      | 0.16%   |
| TCSUNBOW                  | 1         | 1      | 0.16%   |
| Sabrent                   | 1         | 2      | 0.16%   |
| QNAP                      | 1         | 1      | 0.16%   |
| PLEXTOR                   | 1         | 1      | 0.16%   |
| PALIT                     | 1         | 1      | 0.16%   |
| MaxDigital                | 1         | 1      | 0.16%   |
| LITEONIT                  | 1         | 1      | 0.16%   |
| LaCie                     | 1         | 1      | 0.16%   |
| KESU                      | 1         | 1      | 0.16%   |
| JMicron                   | 1         | 1      | 0.16%   |
| Hikvision                 | 1         | 1      | 0.16%   |
| FORESEE                   | 1         | 1      | 0.16%   |
| ExcelStor                 | 1         | 2      | 0.16%   |
| Emtec                     | 1         | 2      | 0.16%   |
| DRVEO                     | 1         | 1      | 0.16%   |
| DOGFISH                   | 1         | 1      | 0.16%   |
| Corsair                   | 1         | 2      | 0.16%   |
| AMD                       | 1         | 1      | 0.16%   |
| ADplus                    | 1         | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  64GB             | 6         | 0.87%   |
| Toshiba MQ01ABD100 1TB             | 6         | 0.87%   |
| Seagate ST1000LM035-1RK172 1TB     | 6         | 0.87%   |
| Samsung SSD 840 EVO 250GB          | 6         | 0.87%   |
| Samsung NVMe SSD Drive 500GB       | 6         | 0.87%   |
| Unknown MMC Card  32GB             | 5         | 0.73%   |
| Seagate ST8000DM004-2CX188 8TB     | 5         | 0.73%   |
| Seagate ST1000DM010-2EP102 1TB     | 5         | 0.73%   |
| Samsung SSD 970 EVO Plus 500GB     | 5         | 0.73%   |
| Samsung SSD 850 EVO 250GB          | 5         | 0.73%   |
| Crucial CT1000MX500SSD1 1TB        | 5         | 0.73%   |
| WDC WDS500G2B0B-00YS70 500GB SSD   | 4         | 0.58%   |
| WDC WD10EURX-83UY4Y0 1TB           | 4         | 0.58%   |
| Verbatim Vi550 S3 SSD 256GB        | 4         | 0.58%   |
| Seagate ST500DM002-1BD142 500GB    | 4         | 0.58%   |
| Seagate ST2000DL003-9VT166 2TB     | 4         | 0.58%   |
| Seagate Expansion Desk 10TB        | 4         | 0.58%   |
| Sandisk NVMe SSD Drive 512GB       | 4         | 0.58%   |
| Samsung SSD 860 EVO 500GB          | 4         | 0.58%   |
| Samsung NVMe SSD Drive 256GB       | 4         | 0.58%   |
| Kingston SV300S37A120G 120GB SSD   | 4         | 0.58%   |
| Kingston SA400S37480G 480GB SSD    | 4         | 0.58%   |
| Crucial CT500MX500SSD1 500GB       | 4         | 0.58%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 3         | 0.44%   |
| WDC WD3200AAJS-60Z0A0 320GB        | 3         | 0.44%   |
| WDC WD20EZRX-00D8PB0 2TB           | 3         | 0.44%   |
| WDC WD10EZEX-08WN4A0 1TB           | 3         | 0.44%   |
| WDC WD10EALX-009BA0 1TB            | 3         | 0.44%   |
| Toshiba DT01ACA100 1TB             | 3         | 0.44%   |
| Seagate ST3500418AS 500GB          | 3         | 0.44%   |
| Seagate ST3500312CS 500GB          | 3         | 0.44%   |
| Seagate ST31000528AS 1TB           | 3         | 0.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 0.44%   |
| Sandisk NVMe SSD Drive 500GB       | 3         | 0.44%   |
| Samsung SSD 970 EVO 500GB          | 3         | 0.44%   |
| Samsung SSD 860 QVO 1TB            | 3         | 0.44%   |
| Samsung SSD 850 EVO 500GB          | 3         | 0.44%   |
| Samsung NVMe SSD Drive 512GB       | 3         | 0.44%   |
| PNY CS900 120GB SSD                | 3         | 0.44%   |
| Micron 2300 NVMe 512GB             | 3         | 0.44%   |
| Kingston SA400S37240G 240GB SSD    | 3         | 0.44%   |
| Hitachi HTS723232A7A364 320GB      | 3         | 0.44%   |
| Hitachi HDS721032CLA362 320GB      | 3         | 0.44%   |
| HGST HTS721010A9E630 1TB           | 3         | 0.44%   |
| HGST HTS545050A7E680 500GB         | 3         | 0.44%   |
| Crucial M4-CT128M4SSD2 128GB       | 3         | 0.44%   |
| Crucial CT480BX500SSD1 480GB       | 3         | 0.44%   |
| A-DATA SU650 240GB SSD             | 3         | 0.44%   |
| WDC WDS250G2B0C-00PXH0 250GB       | 2         | 0.29%   |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 2         | 0.29%   |
| WDC WDS100T1B0A-00H9H0 1TB SSD     | 2         | 0.29%   |
| WDC WD5000BPKT-60PK4T0 500GB       | 2         | 0.29%   |
| WDC WD5000AAKX-22ERMA0 500GB       | 2         | 0.29%   |
| WDC WD40EZRZ-19GXCB0 4TB           | 2         | 0.29%   |
| WDC WD2500AAKX-753CA1 250GB        | 2         | 0.29%   |
| WDC WD20EARX-00PASB0 2TB           | 2         | 0.29%   |
| WDC WD20EARS-00MVWB0 2TB           | 2         | 0.29%   |
| WDC WD10JPVX-22JC3T0 1TB           | 2         | 0.29%   |
| WDC WD10JPVX-00JC3T0 1TB           | 2         | 0.29%   |
| WDC WD10JPCX-24UE4T0 1TB           | 2         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 89        | 158    | 33.21%  |
| Seagate             | 79        | 134    | 29.48%  |
| Toshiba             | 30        | 37     | 11.19%  |
| Hitachi             | 30        | 42     | 11.19%  |
| Samsung Electronics | 10        | 12     | 3.73%   |
| HGST                | 10        | 10     | 3.73%   |
| Fujitsu             | 7         | 8      | 2.61%   |
| ASMT                | 3         | 5      | 1.12%   |
| MAXTOR              | 2         | 2      | 0.75%   |
| Apple               | 2         | 2      | 0.75%   |
| Unknown             | 1         | 1      | 0.37%   |
| Sabrent             | 1         | 2      | 0.37%   |
| QNAP                | 1         | 1      | 0.37%   |
| LaCie               | 1         | 1      | 0.37%   |
| KESU                | 1         | 1      | 0.37%   |
| ExcelStor           | 1         | 2      | 0.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 58        | 75     | 28.57%  |
| Crucial             | 29        | 38     | 14.29%  |
| SanDisk             | 20        | 23     | 9.85%   |
| Kingston            | 18        | 23     | 8.87%   |
| WDC                 | 11        | 17     | 5.42%   |
| A-DATA Technology   | 7         | 11     | 3.45%   |
| Intel               | 5         | 5      | 2.46%   |
| Verbatim            | 4         | 4      | 1.97%   |
| PNY                 | 4         | 4      | 1.97%   |
| LITEON              | 4         | 4      | 1.97%   |
| China               | 4         | 7      | 1.97%   |
| Toshiba             | 3         | 4      | 1.48%   |
| OCZ                 | 3         | 3      | 1.48%   |
| Micron Technology   | 3         | 3      | 1.48%   |
| KingSpec            | 3         | 3      | 1.48%   |
| Apple               | 3         | 3      | 1.48%   |
| Transcend           | 2         | 2      | 0.99%   |
| Team                | 2         | 2      | 0.99%   |
| Netac               | 2         | 2      | 0.99%   |
| KingDian            | 2         | 5      | 0.99%   |
| Integral            | 2         | 2      | 0.99%   |
| Zheino              | 1         | 1      | 0.49%   |
| W800S               | 1         | 2      | 0.49%   |
| USB3.0              | 1         | 1      | 0.49%   |
| TCSUNBOW            | 1         | 1      | 0.49%   |
| SK Hynix            | 1         | 1      | 0.49%   |
| PLEXTOR             | 1         | 1      | 0.49%   |
| PALIT               | 1         | 1      | 0.49%   |
| LITEONIT            | 1         | 1      | 0.49%   |
| Hikvision           | 1         | 1      | 0.49%   |
| FORESEE             | 1         | 1      | 0.49%   |
| Emtec               | 1         | 2      | 0.49%   |
| DRVEO               | 1         | 1      | 0.49%   |
| DOGFISH             | 1         | 1      | 0.49%   |
| Corsair             | 1         | 2      | 0.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 214       | 418    | 40.15%  |
| SSD     | 177       | 257    | 33.21%  |
| NVMe    | 106       | 155    | 19.89%  |
| MMC     | 29        | 40     | 5.44%   |
| Unknown | 7         | 7      | 1.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 320       | 653    | 67.23%  |
| NVMe | 106       | 155    | 22.27%  |
| MMC  | 29        | 40     | 6.09%   |
| SAS  | 21        | 29     | 4.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 241       | 383    | 56.57%  |
| 0.51-1.0   | 125       | 182    | 29.34%  |
| 1.01-2.0   | 26        | 40     | 6.1%    |
| 3.01-4.0   | 14        | 28     | 3.29%   |
| 4.01-10.0  | 12        | 31     | 2.82%   |
| 2.01-3.0   | 8         | 11     | 1.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 103       | 24.01%  |
| 251-500        | 100       | 23.31%  |
| 501-1000       | 56        | 13.05%  |
| 51-100         | 41        | 9.56%   |
| 1-20           | 36        | 8.39%   |
| 1001-2000      | 27        | 6.29%   |
| More than 3000 | 25        | 5.83%   |
| Unknown        | 17        | 3.96%   |
| 21-50          | 14        | 3.26%   |
| 2001-3000      | 10        | 2.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 173       | 38.7%   |
| 101-250        | 66        | 14.77%  |
| 21-50          | 59        | 13.2%   |
| 51-100         | 49        | 10.96%  |
| 251-500        | 29        | 6.49%   |
| 501-1000       | 27        | 6.04%   |
| Unknown        | 17        | 3.8%    |
| More than 3000 | 12        | 2.68%   |
| 1001-2000      | 8         | 1.79%   |
| 2001-3000      | 7         | 1.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD10EALX-009BA0 1TB                        | 3         | 8      | 5.56%   |
| Seagate ST2000DL003-9VT166 2TB                 | 3         | 5      | 5.56%   |
| WDC WD2500AAKX-753CA1 250GB                    | 2         | 2      | 3.7%    |
| Hitachi HTS723232A7A364 320GB                  | 2         | 2      | 3.7%    |
| WDC WD7500BPKX-00HPJT0 752GB                   | 1         | 1      | 1.85%   |
| WDC WD5000BEVT-35A0RT0 500GB                   | 1         | 1      | 1.85%   |
| WDC WD5000AAKX-001CA0 500GB                    | 1         | 1      | 1.85%   |
| WDC WD40EFRX-68WT0N0 4TB                       | 1         | 1      | 1.85%   |
| WDC WD400JB-00FMA0 40GB                        | 1         | 2      | 1.85%   |
| WDC WD3200AVJS-63B6A0 320GB                    | 1         | 1      | 1.85%   |
| WDC WD2500BEVT-22A23T0 250GB                   | 1         | 1      | 1.85%   |
| WDC WD2500AAKX-603CA0 250GB                    | 1         | 1      | 1.85%   |
| WDC WD20EZRZ-00Z5HB0 2TB                       | 1         | 1      | 1.85%   |
| WDC WD10EZEX-00BN5A0 1TB                       | 1         | 1      | 1.85%   |
| WDC WD1001FALS-00E8B0 1TB                      | 1         | 2      | 1.85%   |
| Toshiba MQ01ABF050H 500GB                      | 1         | 1      | 1.85%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 1.85%   |
| Toshiba MK1652GSX 160GB                        | 1         | 1      | 1.85%   |
| Toshiba MK1059GSM 1TB                          | 1         | 1      | 1.85%   |
| Toshiba DT01ACA050 500GB                       | 1         | 1      | 1.85%   |
| Seagate ST910021AS 100GB                       | 1         | 1      | 1.85%   |
| Seagate ST4000DX001-1CE168 4TB                 | 1         | 1      | 1.85%   |
| Seagate ST3500418AS 500GB                      | 1         | 2      | 1.85%   |
| Seagate ST31500541AS 1TB                       | 1         | 1      | 1.85%   |
| Seagate ST3120026A 120GB                       | 1         | 1      | 1.85%   |
| Seagate ST31000333AS 1TB                       | 1         | 2      | 1.85%   |
| Seagate ST3000DM001-1ER166 3TB                 | 1         | 1      | 1.85%   |
| SanDisk SSD PLUS 240GB                         | 1         | 1      | 1.85%   |
| Samsung Electronics SSD 970 EVO Plus 2TB       | 1         | 1      | 1.85%   |
| Samsung Electronics HM120JC 120GB              | 1         | 1      | 1.85%   |
| Samsung Electronics HD103SI 1TB                | 1         | 1      | 1.85%   |
| Netac SSD 128GB                                | 1         | 1      | 1.85%   |
| Micron Technology 2300 NVMe 512GB              | 1         | 1      | 1.85%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 1.85%   |
| MAXTOR STM3250310AS 250GB                      | 1         | 1      | 1.85%   |
| Intel SSDSA2M080G2GC 80GB                      | 1         | 1      | 1.85%   |
| Hitachi HUS724030ALA640 3TB                    | 1         | 2      | 1.85%   |
| Hitachi HTS545050B9A300 500GB                  | 1         | 1      | 1.85%   |
| Hitachi HTS545025B9SA02 250GB                  | 1         | 1      | 1.85%   |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 1.85%   |
| Hitachi HDT721016SLA380 160GB                  | 1         | 2      | 1.85%   |
| Hitachi DK23CA-30 32GB                         | 1         | 1      | 1.85%   |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 1.85%   |
| HGST HTS541010A7E630 1TB                       | 1         | 1      | 1.85%   |
| Fujitsu MHJ2181AT 18GB                         | 1         | 1      | 1.85%   |
| DRVEO X1 SSD 480GB                             | 1         | 1      | 1.85%   |
| China T480 480GB SSD                           | 1         | 1      | 1.85%   |
| A-DATA Technology SU800 128GB SSD              | 1         | 1      | 1.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 23     | 25.49%  |
| Seagate             | 10        | 14     | 19.61%  |
| Hitachi             | 8         | 10     | 15.69%  |
| Toshiba             | 5         | 5      | 9.8%    |
| Samsung Electronics | 3         | 3      | 5.88%   |
| Micron Technology   | 2         | 2      | 3.92%   |
| HGST                | 2         | 2      | 3.92%   |
| SanDisk             | 1         | 1      | 1.96%   |
| Netac               | 1         | 1      | 1.96%   |
| MAXTOR              | 1         | 1      | 1.96%   |
| Intel               | 1         | 1      | 1.96%   |
| Fujitsu             | 1         | 1      | 1.96%   |
| DRVEO               | 1         | 1      | 1.96%   |
| China               | 1         | 1      | 1.96%   |
| A-DATA Technology   | 1         | 1      | 1.96%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 23     | 30.95%  |
| Seagate             | 10        | 14     | 23.81%  |
| Hitachi             | 8         | 10     | 19.05%  |
| Toshiba             | 5         | 5      | 11.9%   |
| Samsung Electronics | 2         | 2      | 4.76%   |
| HGST                | 2         | 2      | 4.76%   |
| MAXTOR              | 1         | 1      | 2.38%   |
| Fujitsu             | 1         | 1      | 2.38%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 33        | 58     | 78.57%  |
| SSD  | 7         | 7      | 16.67%  |
| NVMe | 2         | 2      | 4.76%   |

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
| Detected | 256       | 521    | 57.14%  |
| Works    | 151       | 289    | 33.71%  |
| Malfunc  | 41        | 67     | 9.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 268       | 53.92%  |
| AMD                          | 77        | 15.49%  |
| Samsung Electronics          | 45        | 9.05%   |
| Sandisk                      | 24        | 4.83%   |
| Nvidia                       | 12        | 2.41%   |
| Toshiba America Info Systems | 9         | 1.81%   |
| Marvell Technology Group     | 8         | 1.61%   |
| ASMedia Technology           | 8         | 1.61%   |
| Micron/Crucial Technology    | 6         | 1.21%   |
| Micron Technology            | 6         | 1.21%   |
| SK Hynix                     | 5         | 1.01%   |
| Phison Electronics           | 5         | 1.01%   |
| JMicron Technology           | 5         | 1.01%   |
| Union Memory (Shenzhen)      | 3         | 0.6%    |
| Silicon Motion               | 3         | 0.6%    |
| LSI Logic / Symbios Logic    | 3         | 0.6%    |
| KIOXIA                       | 2         | 0.4%    |
| ULi Electronics              | 1         | 0.2%    |
| Silicon Image                | 1         | 0.2%    |
| Seagate Technology           | 1         | 0.2%    |
| Realtek Semiconductor        | 1         | 0.2%    |
| Kingston Technology Company  | 1         | 0.2%    |
| Broadcom / LSI               | 1         | 0.2%    |
| ADATA Technology             | 1         | 0.2%    |
| Adaptec                      | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 58        | 9.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 29        | 4.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 28        | 4.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 18        | 3.08%   |
| AMD 400 Series Chipset SATA Controller                                                  | 17        | 2.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 15        | 2.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 14        | 2.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 14        | 2.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 13        | 2.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11        | 1.88%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 10        | 1.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 10        | 1.71%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10        | 1.71%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10        | 1.71%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 9         | 1.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8         | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8         | 1.37%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 8         | 1.37%   |
| Samsung NVMe SSD Controller 980                                                         | 7         | 1.2%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 7         | 1.2%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 7         | 1.2%    |
| Micron Non-Volatile memory controller                                                   | 6         | 1.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6         | 1.03%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 6         | 1.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 6         | 1.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 6         | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 6         | 1.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6         | 1.03%   |
| Nvidia MCP79 AHCI Controller                                                            | 5         | 0.86%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 0.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5         | 0.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5         | 0.86%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5         | 0.86%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 4         | 0.68%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 4         | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4         | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4         | 0.68%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4         | 0.68%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 0.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 4         | 0.68%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 4         | 0.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4         | 0.68%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 3         | 0.51%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 3         | 0.51%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3         | 0.51%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 3         | 0.51%   |
| Intel SSD 660P Series                                                                   | 3         | 0.51%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 0.51%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 0.51%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 0.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 0.51%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3         | 0.51%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3         | 0.51%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.51%   |
| AMD FCH SATA Controller D                                                               | 3         | 0.51%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 2         | 0.34%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 2         | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 302       | 60.28%  |
| NVMe | 107       | 21.36%  |
| IDE  | 62        | 12.38%  |
| RAID | 27        | 5.39%   |
| SCSI | 3         | 0.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 307       | 75.43%  |
| AMD    | 93        | 22.85%  |
| ARM    | 7         | 1.72%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 1.71%   |
| ARM Processor                                 | 7         | 1.71%   |
| AMD Ryzen 5 3600 6-Core Processor             | 7         | 1.71%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 1.46%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.22%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 5         | 1.22%   |
| Intel Core i7-2600K CPU @ 3.40GHz             | 5         | 1.22%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 1.22%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 1.22%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 5         | 1.22%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 0.98%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 4         | 0.98%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 0.98%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 0.98%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 4         | 0.98%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 0.98%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 4         | 0.98%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3         | 0.73%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 0.73%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 0.73%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 3         | 0.73%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 0.73%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 0.73%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.73%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 3         | 0.73%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 3         | 0.73%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz          | 3         | 0.73%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 3         | 0.73%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 0.73%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 3         | 0.73%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 0.73%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 0.73%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.73%   |
| AMD Athlon II X4 620 Processor                | 3         | 0.73%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 3         | 0.73%   |
| Intel Xeon CPU X5690 @ 3.47GHz                | 2         | 0.49%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 2         | 0.49%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.49%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.49%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.49%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.49%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 0.49%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.49%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 2         | 0.49%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.49%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.49%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.49%   |
| Intel Core i5-4670K CPU @ 3.40GHz             | 2         | 0.49%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.49%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.49%   |
| Intel Core i5-2500 CPU @ 3.30GHz              | 2         | 0.49%   |
| Intel Core i5-10500 CPU @ 3.10GHz             | 2         | 0.49%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.49%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 2         | 0.49%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.49%   |
| Intel Core i3-4150 CPU @ 3.50GHz              | 2         | 0.49%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 2         | 0.49%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.49%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz         | 2         | 0.49%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 2         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 88        | 21.46%  |
| Intel Core i7           | 84        | 20.49%  |
| Intel Core i3           | 31        | 7.56%   |
| AMD Ryzen 5             | 26        | 6.34%   |
| Other                   | 25        | 6.1%    |
| Intel Core 2 Duo        | 22        | 5.37%   |
| Intel Celeron           | 19        | 4.63%   |
| Intel Atom              | 10        | 2.44%   |
| AMD Ryzen 7             | 9         | 2.2%    |
| Intel Core 2 Quad       | 7         | 1.71%   |
| AMD Ryzen 9             | 7         | 1.71%   |
| Intel Xeon              | 6         | 1.46%   |
| Intel Pentium           | 6         | 1.46%   |
| AMD FX                  | 6         | 1.46%   |
| AMD Athlon 64 X2        | 5         | 1.22%   |
| Intel Pentium Dual-Core | 4         | 0.98%   |
| AMD Ryzen 3             | 4         | 0.98%   |
| AMD A8                  | 4         | 0.98%   |
| Intel Core 2            | 3         | 0.73%   |
| AMD Athlon II X4        | 3         | 0.73%   |
| AMD A6                  | 3         | 0.73%   |
| Intel Pentium 4         | 2         | 0.49%   |
| Intel Core m3           | 2         | 0.49%   |
| Intel Core i9           | 2         | 0.49%   |
| Intel Celeron Dual-Core | 2         | 0.49%   |
| AMD Ryzen Threadripper  | 2         | 0.49%   |
| AMD Ryzen Embedded      | 2         | 0.49%   |
| AMD Phenom II X6        | 2         | 0.49%   |
| AMD A4                  | 2         | 0.49%   |
| Intel Pentium Silver    | 1         | 0.24%   |
| Intel Pentium M         | 1         | 0.24%   |
| Intel Pentium III       | 1         | 0.24%   |
| Intel Pentium D         | 1         | 0.24%   |
| Intel Genuine           | 1         | 0.24%   |
| Intel Core m7           | 1         | 0.24%   |
| Intel Core m5           | 1         | 0.24%   |
| Intel Core 2 Extreme    | 1         | 0.24%   |
| Intel Celeron M         | 1         | 0.24%   |
| AMD Turion 64 X2 Mobile | 1         | 0.24%   |
| AMD Sempron             | 1         | 0.24%   |
| AMD Ryzen 5 PRO         | 1         | 0.24%   |
| AMD PRO A10             | 1         | 0.24%   |
| AMD Phenom II X4        | 1         | 0.24%   |
| AMD Phenom II           | 1         | 0.24%   |
| AMD E2                  | 1         | 0.24%   |
| AMD E1                  | 1         | 0.24%   |
| AMD E                   | 1         | 0.24%   |
| AMD Athlon II X2        | 1         | 0.24%   |
| AMD Athlon Dual Core    | 1         | 0.24%   |
| AMD Athlon              | 1         | 0.24%   |
| AMD A10                 | 1         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 166       | 40.69%  |
| 4       | 162       | 39.71%  |
| 6       | 34        | 8.33%   |
| 8       | 16        | 3.92%   |
| 1       | 15        | 3.68%   |
| 12      | 9         | 2.21%   |
| 3       | 3         | 0.74%   |
| 32      | 1         | 0.25%   |
| 14      | 1         | 0.25%   |
| Unknown | 1         | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 404       | 99.26%  |
| 2      | 3         | 0.74%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 259       | 63.17%  |
| 1       | 150       | 36.59%  |
| Unknown | 1         | 0.24%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 389       | 95.11%  |
| Unknown        | 17        | 4.16%   |
| 32-bit         | 3         | 0.73%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 94        | 22.54%  |
| 0x306a9    | 27        | 6.47%   |
| 0x206a7    | 24        | 5.76%   |
| 0x1067a    | 20        | 4.8%    |
| 0x306c3    | 17        | 4.08%   |
| 0x806e9    | 14        | 3.36%   |
| 0x806ec    | 13        | 3.12%   |
| 0x806ea    | 9         | 2.16%   |
| 0x806c1    | 9         | 2.16%   |
| 0x406e3    | 9         | 2.16%   |
| 0x40651    | 9         | 2.16%   |
| 0x906ea    | 7         | 1.68%   |
| 0x10676    | 7         | 1.68%   |
| 0xa0652    | 6         | 1.44%   |
| 0x906e9    | 6         | 1.44%   |
| 0x406c4    | 6         | 1.44%   |
| 0x306d4    | 6         | 1.44%   |
| 0x30678    | 6         | 1.44%   |
| 0x08701021 | 6         | 1.44%   |
| 0x08108109 | 6         | 1.44%   |
| 0x20655    | 5         | 1.2%    |
| 0x0810100b | 5         | 1.2%    |
| 0x06006705 | 5         | 1.2%    |
| 0x6fd      | 4         | 0.96%   |
| 0x08108102 | 4         | 0.96%   |
| 0x0800820d | 4         | 0.96%   |
| 0xa0653    | 3         | 0.72%   |
| 0x706e5    | 3         | 0.72%   |
| 0x6fb      | 3         | 0.72%   |
| 0x506e3    | 3         | 0.72%   |
| 0x206c2    | 3         | 0.72%   |
| 0x106ca    | 3         | 0.72%   |
| 0x08701013 | 3         | 0.72%   |
| 0x06001119 | 3         | 0.72%   |
| 0x06000852 | 3         | 0.72%   |
| 0x010000c8 | 3         | 0.72%   |
| 0x906ed    | 2         | 0.48%   |
| 0x806d1    | 2         | 0.48%   |
| 0x706a8    | 2         | 0.48%   |
| 0x706a1    | 2         | 0.48%   |
| 0x6f6      | 2         | 0.48%   |
| 0x6d8      | 2         | 0.48%   |
| 0x30661    | 2         | 0.48%   |
| 0x20652    | 2         | 0.48%   |
| 0x106e5    | 2         | 0.48%   |
| 0x106a5    | 2         | 0.48%   |
| 0x0a50000c | 2         | 0.48%   |
| 0x08600103 | 2         | 0.48%   |
| 0x07030106 | 2         | 0.48%   |
| 0x0600611a | 2         | 0.48%   |
| 0x010000db | 2         | 0.48%   |
| 0xf47      | 1         | 0.24%   |
| 0xf43      | 1         | 0.24%   |
| 0xf41      | 1         | 0.24%   |
| 0x906eb    | 1         | 0.24%   |
| 0x906a3    | 1         | 0.24%   |
| 0x6f7      | 1         | 0.24%   |
| 0x6f2      | 1         | 0.24%   |
| 0x6ec      | 1         | 0.24%   |
| 0x6b1      | 1         | 0.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 59        | 14.46%  |
| IvyBridge        | 37        | 9.07%   |
| SandyBridge      | 34        | 8.33%   |
| Haswell          | 30        | 7.35%   |
| Penryn           | 28        | 6.86%   |
| Zen+             | 20        | 4.9%    |
| Zen 2            | 18        | 4.41%   |
| Skylake          | 18        | 4.41%   |
| Silvermont       | 17        | 4.17%   |
| Westmere         | 14        | 3.43%   |
| Core             | 12        | 2.94%   |
| TigerLake        | 10        | 2.45%   |
| CometLake        | 10        | 2.45%   |
| K10              | 9         | 2.21%   |
| Excavator        | 9         | 2.21%   |
| Zen              | 8         | 1.96%   |
| Piledriver       | 8         | 1.96%   |
| K8 Hammer        | 8         | 1.96%   |
| Broadwell        | 7         | 1.72%   |
| Unknown          | 7         | 1.72%   |
| Nehalem          | 6         | 1.47%   |
| IceLake          | 6         | 1.47%   |
| Goldmont plus    | 6         | 1.47%   |
| Zen 3            | 5         | 1.23%   |
| Bonnell          | 5         | 1.23%   |
| P6               | 4         | 0.98%   |
| Puma             | 3         | 0.74%   |
| NetBurst         | 3         | 0.74%   |
| Bobcat           | 2         | 0.49%   |
| Steamroller      | 1         | 0.25%   |
| Jaguar           | 1         | 0.25%   |
| Goldmont         | 1         | 0.25%   |
| Bulldozer        | 1         | 0.25%   |
| Alderlake Hybrid | 1         | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 230       | 49.04%  |
| Nvidia | 131       | 27.93%  |
| AMD    | 108       | 23.03%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 4.3%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 20        | 4.1%    |
| Intel HD Graphics 620                                                                    | 14        | 2.87%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 13        | 2.66%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 2.05%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 1.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 1.84%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 1.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 1.84%   |
| Intel UHD Graphics 620                                                                   | 8         | 1.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 1.64%   |
| Intel HD Graphics 630                                                                    | 8         | 1.64%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 1.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 1.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 1.43%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 7         | 1.43%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.23%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 1.23%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 1.23%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 1.23%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 1.02%   |
| Nvidia C79 [GeForce 9400M]                                                               | 5         | 1.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.02%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.02%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 1.02%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5         | 1.02%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.02%   |
| AMD Renoir                                                                               | 5         | 1.02%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.82%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 4         | 0.82%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 4         | 0.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 0.82%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 0.82%   |
| AMD Caicos PRO [Radeon HD 7450]                                                          | 4         | 0.82%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.61%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 3         | 0.61%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.61%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.61%   |
| Nvidia GM204 [GeForce GTX 980]                                                           | 3         | 0.61%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.61%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 0.61%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.61%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.61%   |
| Intel HD Graphics 515                                                                    | 3         | 0.61%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 0.61%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 0.61%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 0.61%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 3         | 0.61%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 3         | 0.61%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.61%   |
| AMD Cezanne                                                                              | 3         | 0.61%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.41%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.41%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2         | 0.41%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 2         | 0.41%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2         | 0.41%   |
| Nvidia GM204M [GeForce GTX 970M]                                                         | 2         | 0.41%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.41%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 0.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 173       | 41.99%  |
| 1 x AMD        | 87        | 21.12%  |
| 1 x Nvidia     | 78        | 18.93%  |
| Intel + Nvidia | 45        | 10.92%  |
| 2 x AMD        | 11        | 2.67%   |
| Other          | 7         | 1.7%    |
| AMD + Nvidia   | 7         | 1.7%    |
| Intel + AMD    | 3         | 0.73%   |
| 2 x Nvidia     | 1         | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 325       | 78.5%   |
| Proprietary | 66        | 15.94%  |
| Unknown     | 23        | 5.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 218       | 51.29%  |
| 0.01-0.5   | 52        | 12.24%  |
| 1.01-2.0   | 42        | 9.88%   |
| 0.51-1.0   | 38        | 8.94%   |
| 3.01-4.0   | 37        | 8.71%   |
| 7.01-8.0   | 19        | 4.47%   |
| 5.01-6.0   | 12        | 2.82%   |
| 2.01-3.0   | 4         | 0.94%   |
| 8.01-16.0  | 2         | 0.47%   |
| 16.01-24.0 | 1         | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 48        | 11.14%  |
| Dell                    | 48        | 11.14%  |
| AU Optronics            | 48        | 11.14%  |
| Samsung Electronics     | 42        | 9.74%   |
| Chimei Innolux          | 30        | 6.96%   |
| BOE                     | 29        | 6.73%   |
| Acer                    | 19        | 4.41%   |
| Sharp                   | 17        | 3.94%   |
| Hewlett-Packard         | 15        | 3.48%   |
| Apple                   | 14        | 3.25%   |
| BenQ                    | 13        | 3.02%   |
| Philips                 | 11        | 2.55%   |
| Goldstar                | 10        | 2.32%   |
| Iiyama                  | 9         | 2.09%   |
| AOC                     | 8         | 1.86%   |
| Lenovo                  | 7         | 1.62%   |
| Chi Mei Optoelectronics | 7         | 1.62%   |
| PANDA                   | 5         | 1.16%   |
| Ancor Communications    | 4         | 0.93%   |
| ___                     | 3         | 0.7%    |
| Vestel Elektronik       | 3         | 0.7%    |
| Unknown                 | 3         | 0.7%    |
| InfoVision              | 3         | 0.7%    |
| HannStar                | 3         | 0.7%    |
| ViewSonic               | 2         | 0.46%   |
| Toshiba                 | 2         | 0.46%   |
| Sony                    | 2         | 0.46%   |
| MiTAC                   | 2         | 0.46%   |
| LG Philips              | 2         | 0.46%   |
| CPT                     | 2         | 0.46%   |
| BOE Technology Group    | 2         | 0.46%   |
| Unknown                 | 2         | 0.46%   |
| Targa Visionary         | 1         | 0.23%   |
| Targa                   | 1         | 0.23%   |
| RTK                     | 1         | 0.23%   |
| Quanta Display          | 1         | 0.23%   |
| Panasonic               | 1         | 0.23%   |
| OEM                     | 1         | 0.23%   |
| NEC Computers           | 1         | 0.23%   |
| MSI                     | 1         | 0.23%   |
| Medion                  | 1         | 0.23%   |
| LGD                     | 1         | 0.23%   |
| Lenovo Group Limited    | 1         | 0.23%   |
| HYO                     | 1         | 0.23%   |
| HKC                     | 1         | 0.23%   |
| CSO                     | 1         | 0.23%   |
| CHR                     | 1         | 0.23%   |
| ASUSTek Computer        | 1         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Iiyama PLT2336 IVM5628 1920x1080 509x286mm 23.0-inch                 | 5         | 1.09%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch | 4         | 0.88%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 4         | 0.88%   |
| ___ LCDTV16 ___9000 1360x768                                         | 3         | 0.66%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                        | 3         | 0.66%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                   | 3         | 0.66%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 3         | 0.66%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch          | 3         | 0.66%   |
| Dell P2014H DEL4097 1600x900 434x236mm 19.4-inch                     | 3         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch     | 3         | 0.66%   |
| BenQ BenQG2222HDL BNQ7859 1920x1080 478x269mm 21.6-inch              | 3         | 0.66%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 2         | 0.44%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch              | 2         | 0.44%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch              | 2         | 0.44%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch              | 2         | 0.44%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch    | 2         | 0.44%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch  | 2         | 0.44%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch | 2         | 0.44%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 2         | 0.44%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 2         | 0.44%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 2         | 0.44%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 2         | 0.44%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch         | 2         | 0.44%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 2         | 0.44%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 2         | 0.44%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.44%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch              | 2         | 0.44%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 2         | 0.44%   |
| Hewlett-Packard Z34c HWP3201 3440x1440 797x333mm 34.0-inch           | 2         | 0.44%   |
| Dell U2715H DELD069 2560x1440 597x336mm 27.0-inch                    | 2         | 0.44%   |
| Dell U2518D DEL413C 2560x1440 553x311mm 25.0-inch                    | 2         | 0.44%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                    | 2         | 0.44%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                    | 2         | 0.44%   |
| Dell P2317H DEL40F3 1920x1080 509x286mm 23.0-inch                    | 2         | 0.44%   |
| Dell E171FP DEL300F 1280x1024 340x270mm 17.1-inch                    | 2         | 0.44%   |
| Dell 2007FP DELA020 1600x1200 367x275mm 18.1-inch                    | 2         | 0.44%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                    | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch      | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch     | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch     | 2         | 0.44%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 2         | 0.44%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                | 2         | 0.44%   |
| BenQ ZOWIE XL LCD BNQ7F33 1920x1080 531x298mm 24.0-inch              | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch       | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch        | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 2         | 0.44%   |
| Apple LED Cinema APP9236 1920x1200 518x324mm 24.1-inch               | 2         | 0.44%   |
| Acer KA270H ACR0522 1920x1080 598x336mm 27.0-inch                    | 2         | 0.44%   |
| Acer K222HQL ACR040D 1920x1080 477x268mm 21.5-inch                   | 2         | 0.44%   |
| Unknown                                                              | 2         | 0.44%   |
| ViewSonic VX2776-4K-mhd VSC7137 3840x2160 608x355mm 27.7-inch        | 1         | 0.22%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch        | 1         | 0.22%   |
| Toshiba TV TSB1206 1360x768                                          | 1         | 0.22%   |
| Toshiba Internal LCD TOS5091 1366x768 309x174mm 14.0-inch            | 1         | 0.22%   |
| Targa Visionary LCD22-1 Wide TARA229 1680x1050 474x297mm 22.0-inch   | 1         | 0.22%   |
| Targa LCD Monitor LCDTV16 1360x768                                   | 1         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 179       | 42.62%  |
| 1366x768 (WXGA)    | 81        | 19.29%  |
| 3840x2160 (4K)     | 24        | 5.71%   |
| 1600x900 (HD+)     | 18        | 4.29%   |
| 2560x1440 (QHD)    | 17        | 4.05%   |
| 1440x900 (WXGA+)   | 14        | 3.33%   |
| 1920x1200 (WUXGA)  | 13        | 3.1%    |
| 1280x800 (WXGA)    | 12        | 2.86%   |
| 1280x1024 (SXGA)   | 10        | 2.38%   |
| 3440x1440          | 7         | 1.67%   |
| 1360x768           | 7         | 1.67%   |
| Unknown            | 7         | 1.67%   |
| 1680x1050 (WSXGA+) | 6         | 1.43%   |
| 3840x2400          | 3         | 0.71%   |
| 3840x1080          | 3         | 0.71%   |
| 1600x1200          | 3         | 0.71%   |
| 1024x600           | 3         | 0.71%   |
| 3200x1800 (QHD+)   | 2         | 0.48%   |
| 2560x1600          | 2         | 0.48%   |
| 1024x768 (XGA)     | 2         | 0.48%   |
| 6400x2160          | 1         | 0.24%   |
| 5280x2560          | 1         | 0.24%   |
| 4480x1440          | 1         | 0.24%   |
| 3600x1080          | 1         | 0.24%   |
| 2560x1080          | 1         | 0.24%   |
| 2160x1440          | 1         | 0.24%   |
| 1920x540           | 1         | 0.24%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 116       | 26.79%  |
| 27      | 41        | 9.47%   |
| 14      | 40        | 9.24%   |
| 13      | 34        | 7.85%   |
| 24      | 30        | 6.93%   |
| 23      | 26        | 6%      |
| Unknown | 24        | 5.54%   |
| 21      | 23        | 5.31%   |
| 17      | 20        | 4.62%   |
| 12      | 12        | 2.77%   |
| 19      | 10        | 2.31%   |
| 18      | 8         | 1.85%   |
| 34      | 7         | 1.62%   |
| 31      | 7         | 1.62%   |
| 20      | 5         | 1.15%   |
| 84      | 4         | 0.92%   |
| 72      | 4         | 0.92%   |
| 32      | 4         | 0.92%   |
| 11      | 4         | 0.92%   |
| 25      | 3         | 0.69%   |
| 10      | 3         | 0.69%   |
| 40      | 2         | 0.46%   |
| 22      | 2         | 0.46%   |
| 49      | 1         | 0.23%   |
| 46      | 1         | 0.23%   |
| 35      | 1         | 0.23%   |
| 29      | 1         | 0.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 169       | 39.76%  |
| 501-600     | 87        | 20.47%  |
| 401-500     | 45        | 10.59%  |
| 201-300     | 41        | 9.65%   |
| Unknown     | 24        | 5.65%   |
| 351-400     | 21        | 4.94%   |
| 601-700     | 14        | 3.29%   |
| 701-800     | 11        | 2.59%   |
| 1501-2000   | 8         | 1.88%   |
| 801-900     | 3         | 0.71%   |
| 1001-1500   | 2         | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 293       | 76.1%   |
| 16/10   | 46        | 11.95%  |
| Unknown | 19        | 4.94%   |
| 5/4     | 10        | 2.6%    |
| 21/9    | 8         | 2.08%   |
| 4/3     | 5         | 1.3%    |
| 3/2     | 3         | 0.78%   |
| 32/9    | 1         | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 115       | 26.44%  |
| 201-250        | 63        | 14.48%  |
| 81-90          | 55        | 12.64%  |
| 301-350        | 41        | 9.43%   |
| Unknown        | 24        | 5.52%   |
| 151-200        | 23        | 5.29%   |
| 71-80          | 20        | 4.6%    |
| 351-500        | 20        | 4.6%    |
| 251-300        | 16        | 3.68%   |
| 141-150        | 13        | 2.99%   |
| 61-70          | 11        | 2.53%   |
| 121-130        | 11        | 2.53%   |
| More than 1000 | 8         | 1.84%   |
| 51-60          | 4         | 0.92%   |
| 501-1000       | 4         | 0.92%   |
| 41-50          | 3         | 0.69%   |
| 131-140        | 3         | 0.69%   |
| 111-120        | 1         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 123       | 29.29%  |
| 101-120       | 115       | 27.38%  |
| 121-160       | 112       | 26.67%  |
| 161-240       | 25        | 5.95%   |
| Unknown       | 24        | 5.71%   |
| 1-50          | 11        | 2.62%   |
| More than 240 | 10        | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 321       | 76.79%  |
| 2     | 70        | 16.75%  |
| 0     | 20        | 4.78%   |
| 3     | 6         | 1.44%   |
| 4     | 1         | 0.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 219       | 34.6%   |
| Realtek Semiconductor             | 190       | 30.02%  |
| Qualcomm Atheros                  | 65        | 10.27%  |
| Broadcom                          | 47        | 7.42%   |
| Ralink Technology                 | 12        | 1.9%    |
| Broadcom Limited                  | 12        | 1.9%    |
| Nvidia                            | 11        | 1.74%   |
| Ralink                            | 9         | 1.42%   |
| Marvell Technology Group          | 9         | 1.42%   |
| TP-Link                           | 8         | 1.26%   |
| Microsoft                         | 5         | 0.79%   |
| Ericsson Business Mobile Networks | 5         | 0.79%   |
| Samsung Electronics               | 4         | 0.63%   |
| MEDIATEK                          | 3         | 0.47%   |
| Lenovo                            | 3         | 0.47%   |
| NetGear                           | 2         | 0.32%   |
| ICS Advent                        | 2         | 0.32%   |
| DisplayLink                       | 2         | 0.32%   |
| Belkin Components                 | 2         | 0.32%   |
| Xilinx                            | 1         | 0.16%   |
| Xiaomi                            | 1         | 0.16%   |
| Van Ooijen Technische Informatica | 1         | 0.16%   |
| ULi Electronics                   | 1         | 0.16%   |
| Toshiba                           | 1         | 0.16%   |
| T & A Mobile Phones               | 1         | 0.16%   |
| Qualcomm Atheros Communications   | 1         | 0.16%   |
| Qualcomm                          | 1         | 0.16%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.16%   |
| NetXen Incorporated               | 1         | 0.16%   |
| Microchip Technology              | 1         | 0.16%   |
| LSI                               | 1         | 0.16%   |
| LG Electronics                    | 1         | 0.16%   |
| JMicron Technology                | 1         | 0.16%   |
| IMC Networks                      | 1         | 0.16%   |
| HMD Global                        | 1         | 0.16%   |
| Hewlett-Packard                   | 1         | 0.16%   |
| Dell                              | 1         | 0.16%   |
| Bose                              | 1         | 0.16%   |
| ASUSTek Computer                  | 1         | 0.16%   |
| ASIX Electronics                  | 1         | 0.16%   |
| Apple                             | 1         | 0.16%   |
| 3Com                              | 1         | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 127       | 16.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 33        | 4.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 3.59%   |
| Intel Wi-Fi 6 AX200                                               | 26        | 3.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 15        | 1.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 1.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 1.59%   |
| Intel Wireless 8265 / 8275                                        | 12        | 1.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 1.46%   |
| Intel Wireless 7260                                               | 10        | 1.33%   |
| Intel I211 Gigabit Network Connection                             | 10        | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.2%    |
| Realtek 802.11ac NIC                                              | 9         | 1.2%    |
| Intel Wireless-AC 9260                                            | 9         | 1.2%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 9         | 1.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 1.06%   |
| Intel Wireless 8260                                               | 8         | 1.06%   |
| Intel Wireless 7265                                               | 8         | 1.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 0.93%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 0.93%   |
| Ralink MT7601U Wireless Adapter                                   | 6         | 0.8%    |
| Nvidia MCP79 Ethernet                                             | 6         | 0.8%    |
| Intel Ethernet Connection I218-LM                                 | 6         | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 0.8%    |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 0.66%   |
| Microsoft Xbox 360 Wireless Adapter                               | 5         | 0.66%   |
| Intel Wireless 3165                                               | 5         | 0.66%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 0.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 0.66%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 5         | 0.66%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 5         | 0.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 0.53%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 0.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 0.53%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 0.53%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.53%   |
| TP-Link 802.11ac WLAN Adapter                                     | 3         | 0.4%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.4%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 3         | 0.4%    |
| Ralink RT5370 Wireless Adapter                                    | 3         | 0.4%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 3         | 0.4%    |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.4%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 3         | 0.4%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 0.4%    |
| Intel Wireless 3160                                               | 3         | 0.4%    |
| Intel WiFi Link 5100                                              | 3         | 0.4%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.4%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.4%    |
| Intel Ethernet Controller I225-V                                  | 3         | 0.4%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.4%    |
| Intel Ethernet Connection I217-V                                  | 3         | 0.4%    |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.4%    |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.4%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.4%    |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 165       | 46.35%  |
| Qualcomm Atheros                | 57        | 16.01%  |
| Realtek Semiconductor           | 49        | 13.76%  |
| Broadcom                        | 33        | 9.27%   |
| Ralink Technology               | 12        | 3.37%   |
| Ralink                          | 9         | 2.53%   |
| TP-Link                         | 8         | 2.25%   |
| Microsoft                       | 5         | 1.4%    |
| Broadcom Limited                | 4         | 1.12%   |
| MEDIATEK                        | 3         | 0.84%   |
| NetGear                         | 2         | 0.56%   |
| Belkin Components               | 2         | 0.56%   |
| Qualcomm Atheros Communications | 1         | 0.28%   |
| Qualcomm                        | 1         | 0.28%   |
| LG Electronics                  | 1         | 0.28%   |
| IMC Networks                    | 1         | 0.28%   |
| Dell                            | 1         | 0.28%   |
| ASUSTek Computer                | 1         | 0.28%   |
| Apple                           | 1         | 0.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 26        | 7.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 4.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 3.89%   |
| Intel Wireless 8265 / 8275                                              | 12        | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 3.06%   |
| Intel Wireless 7260                                                     | 10        | 2.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 2.5%    |
| Realtek 802.11ac NIC                                                    | 9         | 2.5%    |
| Intel Wireless-AC 9260                                                  | 9         | 2.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 2.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 2.22%   |
| Intel Wireless 8260                                                     | 8         | 2.22%   |
| Intel Wireless 7265                                                     | 8         | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 1.94%   |
| Ralink MT7601U Wireless Adapter                                         | 6         | 1.67%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 1.67%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 1.39%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 5         | 1.39%   |
| Intel Wireless 3165                                                     | 5         | 1.39%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 1.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.39%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 5         | 1.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.11%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.11%   |
| Intel Centrino Ultimate-N 6300                                          | 4         | 1.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.11%   |
| TP-Link 802.11ac WLAN Adapter                                           | 3         | 0.83%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.83%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 3         | 0.83%   |
| Ralink RT5370 Wireless Adapter                                          | 3         | 0.83%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 3         | 0.83%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.83%   |
| Intel Wireless 3160                                                     | 3         | 0.83%   |
| Intel WiFi Link 5100                                                    | 3         | 0.83%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 0.83%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.83%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 3         | 0.83%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 0.83%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 3         | 0.83%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 0.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.56%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 2         | 0.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.56%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 2         | 0.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.56%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.56%   |
| NetGear A6210                                                           | 2         | 0.56%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.56%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.56%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.56%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 2         | 0.56%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.56%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 168       | 44.92%  |
| Intel                         | 121       | 32.35%  |
| Broadcom                      | 19        | 5.08%   |
| Qualcomm Atheros              | 15        | 4.01%   |
| Nvidia                        | 11        | 2.94%   |
| Marvell Technology Group      | 9         | 2.41%   |
| Broadcom Limited              | 9         | 2.41%   |
| Samsung Electronics           | 4         | 1.07%   |
| Lenovo                        | 3         | 0.8%    |
| ICS Advent                    | 2         | 0.53%   |
| DisplayLink                   | 2         | 0.53%   |
| Xilinx                        | 1         | 0.27%   |
| Xiaomi                        | 1         | 0.27%   |
| ULi Electronics               | 1         | 0.27%   |
| T & A Mobile Phones           | 1         | 0.27%   |
| OnePlus Technology (Shenzhen) | 1         | 0.27%   |
| NetXen Incorporated           | 1         | 0.27%   |
| Microchip Technology          | 1         | 0.27%   |
| JMicron Technology            | 1         | 0.27%   |
| HMD Global                    | 1         | 0.27%   |
| ASIX Electronics              | 1         | 0.27%   |
| 3Com                          | 1         | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 127       | 33.25%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 33        | 8.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 7.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 3.14%   |
| Intel I211 Gigabit Network Connection                             | 10        | 2.62%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 1.83%   |
| Nvidia MCP79 Ethernet                                             | 6         | 1.57%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 1.57%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 5         | 1.31%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.05%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.05%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 3         | 0.79%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 0.79%   |
| Intel Ethernet Controller I225-V                                  | 3         | 0.79%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.79%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.79%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.79%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.79%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.79%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 0.79%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.52%   |
| Nvidia MCP51 Ethernet Controller                                  | 2         | 0.52%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 2         | 0.52%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.52%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.52%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.52%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.52%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.52%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.52%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.52%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.52%   |
| Intel Ethernet Connection (13) I219-LM                            | 2         | 0.52%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.52%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.52%   |
| Intel 82583V Gigabit Network Connection                           | 2         | 0.52%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2         | 0.52%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 2         | 0.52%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.52%   |
| Xilinx Ethernet controller                                        | 1         | 0.26%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.26%   |
| ULi ULi 1689,1573 integrated ethernet.                            | 1         | 0.26%   |
| T & A Mobile Phones QM215-QRD _SN:6B7D8716                        | 1         | 0.26%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.26%   |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1         | 0.26%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.26%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.26%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.26%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.26%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.26%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.26%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 354       | 50.64%  |
| WiFi     | 334       | 47.78%  |
| Modem    | 11        | 1.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 248       | 58.35%  |
| Ethernet | 177       | 41.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 240       | 58.68%  |
| 1     | 149       | 36.43%  |
| 3     | 9         | 2.2%    |
| 0     | 9         | 2.2%    |
| 6     | 1         | 0.24%   |
| 4     | 1         | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 379       | 92.21%  |
| Yes  | 32        | 7.79%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 124       | 48.06%  |
| Broadcom                        | 21        | 8.14%   |
| Cambridge Silicon Radio         | 20        | 7.75%   |
| Realtek Semiconductor           | 19        | 7.36%   |
| Qualcomm Atheros Communications | 14        | 5.43%   |
| IMC Networks                    | 13        | 5.04%   |
| Apple                           | 12        | 4.65%   |
| Lite-On Technology              | 10        | 3.88%   |
| Dell                            | 7         | 2.71%   |
| Hewlett-Packard                 | 5         | 1.94%   |
| ASUSTek Computer                | 3         | 1.16%   |
| Toshiba                         | 2         | 0.78%   |
| Realtek                         | 2         | 0.78%   |
| Ralink                          | 1         | 0.39%   |
| Foxconn International           | 1         | 0.39%   |
| Foxconn / Hon Hai               | 1         | 0.39%   |
| Edimax Technology               | 1         | 0.39%   |
| Conwise Technology              | 1         | 0.39%   |
| Belkin Components               | 1         | 0.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 52        | 20.08%  |
| Intel AX200 Bluetooth                                       | 25        | 9.65%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 20        | 7.72%   |
| Intel AX201 Bluetooth                                       | 19        | 7.34%   |
| Realtek Bluetooth Radio                                     | 14        | 5.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 10        | 3.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 8         | 3.09%   |
| Qualcomm Atheros  Bluetooth Device                          | 7         | 2.7%    |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 6         | 2.32%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 6         | 2.32%   |
| Realtek  Bluetooth 4.2 Adapter                              | 5         | 1.93%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 5         | 1.93%   |
| IMC Networks Bluetooth Device                               | 5         | 1.93%   |
| Apple Bluetooth Host Controller                             | 5         | 1.93%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 4         | 1.54%   |
| Intel Wireless-AC 3168 Bluetooth                            | 4         | 1.54%   |
| IMC Networks Bluetooth Radio                                | 4         | 1.54%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 4         | 1.54%   |
| Intel AX210 Bluetooth                                       | 3         | 1.16%   |
| HP Broadcom 2070 Bluetooth Combo                            | 3         | 1.16%   |
| Apple Bluetooth USB Host Controller                         | 3         | 1.16%   |
| Apple Bluetooth HCI                                         | 3         | 1.16%   |
| Realtek Bluetooth Radio                                     | 2         | 0.77%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 0.77%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 0.77%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 0.77%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 0.77%   |
| IMC Networks Wireless_Device                                | 2         | 0.77%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 0.77%   |
| Dell Wireless 355 Bluetooth                                 | 2         | 0.77%   |
| Dell DW375 Bluetooth Module                                 | 2         | 0.77%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 2         | 0.77%   |
| Toshiba Bluetooth Device                                    | 1         | 0.39%   |
| Toshiba BCM43142A0                                          | 1         | 0.39%   |
| Ralink RT3290 Bluetooth                                     | 1         | 0.39%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 0.39%   |
| Lite-On Wireless_Device                                     | 1         | 0.39%   |
| Lite-On BCM43142A0                                          | 1         | 0.39%   |
| Lite-On Atheros Bluetooth                                   | 1         | 0.39%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.39%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.39%   |
| Foxconn International BCM43142A0 Bluetooth module           | 1         | 0.39%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth               | 1         | 0.39%   |
| Edimax Wi-Fi N150 Bluetooth4.0 USB Adapter                  | 1         | 0.39%   |
| Dell Wireless 365 Bluetooth                                 | 1         | 0.39%   |
| Dell Wireless 350 Bluetooth                                 | 1         | 0.39%   |
| Dell BT Mini-Receiver                                       | 1         | 0.39%   |
| Conwise CW6622                                              | 1         | 0.39%   |
| Broadcom Bluetooth Device                                   | 1         | 0.39%   |
| Broadcom BCM92045B3 ROM                                     | 1         | 0.39%   |
| Broadcom BCM43142A0 Bluetooth Device                        | 1         | 0.39%   |
| Belkin Components F8T012 Bluetooth Adapter                  | 1         | 0.39%   |
| ASUS Qualcomm Bluetooth 4.1                                 | 1         | 0.39%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1         | 0.39%   |
| ASUS Bluetooth Device                                       | 1         | 0.39%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 291       | 51.23%  |
| AMD                                             | 120       | 21.13%  |
| Nvidia                                          | 103       | 18.13%  |
| C-Media Electronics                             | 6         | 1.06%   |
| Creative Technology                             | 4         | 0.7%    |
| Creative Labs                                   | 4         | 0.7%    |
| Plantronics                                     | 3         | 0.53%   |
| GN Netcom                                       | 3         | 0.53%   |
| Texas Instruments                               | 2         | 0.35%   |
| Realtek Semiconductor                           | 2         | 0.35%   |
| Logitech                                        | 2         | 0.35%   |
| Lenovo                                          | 2         | 0.35%   |
| JMTek                                           | 2         | 0.35%   |
| Ensoniq                                         | 2         | 0.35%   |
| VIA Technologies                                | 1         | 0.18%   |
| ULi Electronics                                 | 1         | 0.18%   |
| Turtle Beach                                    | 1         | 0.18%   |
| Thesycon Systemsoftware & Consulting            | 1         | 0.18%   |
| Sony                                            | 1         | 0.18%   |
| SAVITECH                                        | 1         | 0.18%   |
| RODE Microphones                                | 1         | 0.18%   |
| Razer USA                                       | 1         | 0.18%   |
| Micronas                                        | 1         | 0.18%   |
| M-Audio                                         | 1         | 0.18%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.18%   |
| Kingston Technology                             | 1         | 0.18%   |
| Giga-Byte Technology                            | 1         | 0.18%   |
| Focusrite-Novation                              | 1         | 0.18%   |
| FiiO Electronics Technology                     | 1         | 0.18%   |
| ESS Technology                                  | 1         | 0.18%   |
| Corsair                                         | 1         | 0.18%   |
| Blue Microphones                                | 1         | 0.18%   |
| AudioQuest                                      | 1         | 0.18%   |
| AUDIOLAB                                        | 1         | 0.18%   |
| Audio-Technica                                  | 1         | 0.18%   |
| Audient                                         | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 37        | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 36        | 5.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 33        | 4.95%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 26        | 3.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 17        | 2.55%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 17        | 2.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 2.25%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 15        | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 1.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 1.95%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 13        | 1.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 13        | 1.95%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 1.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 12        | 1.8%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 1.5%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 1.5%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 10        | 1.5%    |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 1.5%    |
| Intel 8 Series HD Audio Controller                                                                | 10        | 1.5%    |
| AMD FCH Azalia Controller                                                                         | 10        | 1.5%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 10        | 1.5%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 9         | 1.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 1.35%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 9         | 1.35%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 8         | 1.2%    |
| Intel Comet Lake PCH cAVS                                                                         | 8         | 1.2%    |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 1.2%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 8         | 1.2%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 7         | 1.05%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 7         | 1.05%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 1.05%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 1.05%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 7         | 1.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 1.05%   |
| Nvidia MCP79 High Definition Audio                                                                | 6         | 0.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6         | 0.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 0.9%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 0.9%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 0.9%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 0.9%    |
| Nvidia High Definition Audio Controller                                                           | 5         | 0.75%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 0.75%   |
| Intel CM238 HD Audio Controller                                                                   | 5         | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 0.75%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 5         | 0.75%   |
| AMD High Definition Audio Controller                                                              | 5         | 0.75%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 0.6%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.6%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.45%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 0.45%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 0.45%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.45%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.45%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 0.45%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 0.45%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.45%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 3         | 0.45%   |
| AMD Navi 10 HDMI Audio                                                                            | 3         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 47        | 19.5%   |
| SK Hynix            | 37        | 15.35%  |
| Unknown             | 29        | 12.03%  |
| Crucial             | 24        | 9.96%   |
| Corsair             | 24        | 9.96%   |
| Micron Technology   | 22        | 9.13%   |
| Kingston            | 19        | 7.88%   |
| Ramaxel Technology  | 7         | 2.9%    |
| G.Skill             | 6         | 2.49%   |
| Elpida              | 5         | 2.07%   |
| Team                | 3         | 1.24%   |
| Patriot             | 3         | 1.24%   |
| Nanya Technology    | 3         | 1.24%   |
| Unknown (ABCD)      | 2         | 0.83%   |
| Apacer              | 2         | 0.83%   |
| Transcend           | 1         | 0.41%   |
| Toshiba             | 1         | 0.41%   |
| SHARETRONIC         | 1         | 0.41%   |
| OSV                 | 1         | 0.41%   |
| Infineon            | 1         | 0.41%   |
| CSX                 | 1         | 0.41%   |
| A-DATA Technology   | 1         | 0.41%   |
| A Force             | 1         | 0.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 5         | 1.93%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 5         | 1.93%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 3         | 1.16%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 3         | 1.16%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s       | 3         | 1.16%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s         | 3         | 1.16%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s       | 3         | 1.16%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s          | 3         | 1.16%   |
| Corsair RAM CM4X16GE2666C18S4 16384MB SODIMM DDR4 2667MT/s     | 3         | 1.16%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                 | 2         | 0.77%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                        | 2         | 0.77%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                 | 2         | 0.77%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                         | 2         | 0.77%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                     | 2         | 0.77%   |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 2         | 0.77%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.77%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s        | 2         | 0.77%   |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s     | 2         | 0.77%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s   | 2         | 0.77%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.77%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s       | 2         | 0.77%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s          | 2         | 0.77%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s         | 2         | 0.77%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 0.77%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s          | 2         | 0.77%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s   | 2         | 0.77%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8192MB SODIMM DDR4 2400MT/s        | 2         | 0.77%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s          | 2         | 0.77%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s           | 2         | 0.77%   |
| Elpida RAM EBJ41UF8BDU0-DJ-F 2048MB Chip DDR3 1333MT/s         | 2         | 0.77%   |
| Crucial RAM CT51264BD160B.C16F 4096MB DIMM DDR3 1600MT/s       | 2         | 0.77%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s     | 2         | 0.77%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s          | 2         | 0.77%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s            | 1         | 0.39%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 1         | 0.39%   |
| Unknown RAM Module 8192MB Row Of Chips LPDDR4 4267MT/s         | 1         | 0.39%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                   | 1         | 0.39%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                        | 1         | 0.39%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1867MT/s                  | 1         | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                    | 1         | 0.39%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                           | 1         | 0.39%   |
| Unknown RAM Module 4096MB SODIMM 800MT/s                       | 1         | 0.39%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s         | 1         | 0.39%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s                   | 1         | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                    | 1         | 0.39%   |
| Unknown RAM Module 2GB DIMM 667MT/s                            | 1         | 0.39%   |
| Unknown RAM Module 256MB SODIMM DRAM                           | 1         | 0.39%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                  | 1         | 0.39%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 0.39%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                       | 1         | 0.39%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                   | 1         | 0.39%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                         | 1         | 0.39%   |
| Unknown RAM Module 2048MB DIMM                                 | 1         | 0.39%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s            | 1         | 0.39%   |
| Unknown RAM Module 1GB DIMM 667MT/s                            | 1         | 0.39%   |
| Unknown RAM Module 128MB SODIMM DRAM                           | 1         | 0.39%   |
| Unknown RAM Module 128MB DIMM SDRAM                            | 1         | 0.39%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 0.39%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s | 1         | 0.39%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 93        | 43.06%  |
| DDR3    | 69        | 31.94%  |
| DDR2    | 12        | 5.56%   |
| Unknown | 12        | 5.56%   |
| SDRAM   | 9         | 4.17%   |
| LPDDR4  | 9         | 4.17%   |
| LPDDR3  | 7         | 3.24%   |
| DDR     | 3         | 1.39%   |
| DRAM    | 2         | 0.93%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 117       | 54.67%  |
| DIMM         | 75        | 35.05%  |
| Row Of Chips | 16        | 7.48%   |
| Chip         | 4         | 1.87%   |
| Unknown      | 2         | 0.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 79        | 34.2%   |
| 4096  | 66        | 28.57%  |
| 2048  | 35        | 15.15%  |
| 16384 | 32        | 13.85%  |
| 1024  | 9         | 3.9%    |
| 32768 | 6         | 2.6%    |
| 128   | 2         | 0.87%   |
| 512   | 1         | 0.43%   |
| 256   | 1         | 0.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 46        | 19.57%  |
| 2667    | 34        | 14.47%  |
| 3200    | 20        | 8.51%   |
| 2400    | 18        | 7.66%   |
| 2133    | 16        | 6.81%   |
| 1333    | 13        | 5.53%   |
| 800     | 12        | 5.11%   |
| 667     | 9         | 3.83%   |
| 3600    | 7         | 2.98%   |
| 1334    | 7         | 2.98%   |
| 4267    | 6         | 2.55%   |
| 3266    | 6         | 2.55%   |
| 1867    | 5         | 2.13%   |
| Unknown | 5         | 2.13%   |
| 1067    | 4         | 1.7%    |
| 3466    | 3         | 1.28%   |
| 1800    | 3         | 1.28%   |
| 4199    | 2         | 0.85%   |
| 3400    | 2         | 0.85%   |
| 1866    | 2         | 0.85%   |
| 1066    | 2         | 0.85%   |
| 975     | 2         | 0.85%   |
| 533     | 2         | 0.85%   |
| 4800    | 1         | 0.43%   |
| 3800    | 1         | 0.43%   |
| 3733    | 1         | 0.43%   |
| 3000    | 1         | 0.43%   |
| 2933    | 1         | 0.43%   |
| 2733    | 1         | 0.43%   |
| 2666    | 1         | 0.43%   |
| 2048    | 1         | 0.43%   |
| 400     | 1         | 0.43%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 2         | 40%     |
| STMicroelectronics  | 1         | 20%     |
| Samsung Electronics | 1         | 20%     |
| Canon               | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 20%     |
| Samsung M2070 Series                                      | 1         | 20%     |
| Canon PIXMA MG2500 Series                                 | 1         | 20%     |
| Brother MFC-L2700DW                                       | 1         | 20%     |
| Brother HL-L2340D series                                  | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 61        | 24.5%   |
| Realtek Semiconductor                  | 30        | 12.05%  |
| Acer                                   | 21        | 8.43%   |
| Microdia                               | 20        | 8.03%   |
| IMC Networks                           | 20        | 8.03%   |
| Logitech                               | 16        | 6.43%   |
| Apple                                  | 11        | 4.42%   |
| Quanta                                 | 9         | 3.61%   |
| Sunplus Innovation Technology          | 8         | 3.21%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 2.81%   |
| Suyin                                  | 6         | 2.41%   |
| Samsung Electronics                    | 5         | 2.01%   |
| ALi                                    | 5         | 2.01%   |
| Microsoft                              | 4         | 1.61%   |
| Syntek                                 | 3         | 1.2%    |
| Silicon Motion                         | 3         | 1.2%    |
| Ricoh                                  | 3         | 1.2%    |
| Lite-On Technology                     | 2         | 0.8%    |
| Generalplus Technology                 | 2         | 0.8%    |
| Creative Technology                    | 2         | 0.8%    |
| Z-Star Microelectronics                | 1         | 0.4%    |
| Y Media                                | 1         | 0.4%    |
| USB3.0 HD Audio Capture                | 1         | 0.4%    |
| Trust                                  | 1         | 0.4%    |
| SunplusIT                              | 1         | 0.4%    |
| Razer USA                              | 1         | 0.4%    |
| Nikon                                  | 1         | 0.4%    |
| Lenovo                                 | 1         | 0.4%    |
| GenesysLogic Technology                | 1         | 0.4%    |
| GEMBIRD                                | 1         | 0.4%    |
| Alcor Micro                            | 1         | 0.4%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                     | 13        | 5.16%   |
| Microdia Integrated_Webcam_HD                    | 10        | 3.97%   |
| Chicony Integrated Camera                        | 9         | 3.57%   |
| Apple Built-in iSight                            | 8         | 3.17%   |
| Chicony USB2.0 Camera                            | 7         | 2.78%   |
| Chicony HD Webcam                                | 7         | 2.78%   |
| IMC Networks Integrated Camera                   | 6         | 2.38%   |
| Samsung Galaxy A5 (MTP)                          | 5         | 1.98%   |
| Logitech HD Pro Webcam C920                      | 5         | 1.98%   |
| Acer Integrated Camera                           | 5         | 1.98%   |
| Microdia Integrated Webcam                       | 4         | 1.59%   |
| IMC Networks USB2.0 HD UVC WebCam                | 4         | 1.59%   |
| Acer EasyCamera                                  | 4         | 1.59%   |
| Realtek Integrated Webcam HD                     | 3         | 1.19%   |
| Microsoft LifeCam HD-3000                        | 3         | 1.19%   |
| Logitech Webcam C270                             | 3         | 1.19%   |
| Chicony USB2.0 HD UVC WebCam                     | 3         | 1.19%   |
| Chicony Lenovo EasyCamera                        | 3         | 1.19%   |
| Chicony EasyCamera                               | 3         | 1.19%   |
| ALi WebCam                                       | 3         | 1.19%   |
| Acer BisonCam, NB Pro                            | 3         | 1.19%   |
| Syntek EasyCamera                                | 2         | 0.79%   |
| Suyin HP Truevision HD                           | 2         | 0.79%   |
| Sunplus Integrated_Webcam_HD                     | 2         | 0.79%   |
| Realtek USB2.0 HD UVC WebCam                     | 2         | 0.79%   |
| Realtek HP Truevision HD integrated webcam       | 2         | 0.79%   |
| Realtek HD WebCam                                | 2         | 0.79%   |
| Realtek EasyCamera                               | 2         | 0.79%   |
| Quanta HP Wide Vision HD Camera                  | 2         | 0.79%   |
| Quanta HP Webcam                                 | 2         | 0.79%   |
| Logitech C922 Pro Stream Webcam                  | 2         | 0.79%   |
| Logitech B525 HD Webcam                          | 2         | 0.79%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 2         | 0.79%   |
| IMC Networks TOSHIBA Web Camera - HD             | 2         | 0.79%   |
| IMC Networks EasyCamera                          | 2         | 0.79%   |
| Creative Live! Cam Sync HD [VF0770]              | 2         | 0.79%   |
| Chicony thinkpad t430s camera                    | 2         | 0.79%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 2         | 0.79%   |
| Chicony Integrated Camera (1280x720@30)          | 2         | 0.79%   |
| Chicony HP Wide Vision HD Camera                 | 2         | 0.79%   |
| Chicony HP TrueVision HD Camera                  | 2         | 0.79%   |
| Chicony HP Truevision HD                         | 2         | 0.79%   |
| Chicony CNF9055 Toshiba Webcam                   | 2         | 0.79%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 0.79%   |
| Apple iPhone 5/5C/5S/6/SE                        | 2         | 0.79%   |
| ALi Gateway Webcam                               | 2         | 0.79%   |
| Acer Lenovo EasyCamera                           | 2         | 0.79%   |
| Acer BisonCam,NB Pro                             | 2         | 0.79%   |
| Z-Star Webcam                                    | 1         | 0.4%    |
| Y Media USB Camera                               | 1         | 0.4%    |
| USB3.0 HD Audio Capture USB3.0 HD Video Capture  | 1         | 0.4%    |
| Trust USB Camera                                 | 1         | 0.4%    |
| Syntek Integrated Camera                         | 1         | 0.4%    |
| Suyin VGA Webcam                                 | 1         | 0.4%    |
| Suyin HD Video WebCam                            | 1         | 0.4%    |
| Suyin Acer CrystalEye Webcam                     | 1         | 0.4%    |
| Suyin 1.3M HD WebCam                             | 1         | 0.4%    |
| SunplusIT USB Camera                             | 1         | 0.4%    |
| Sunplus Laptop_Integrated_Webcam_FHD             | 1         | 0.4%    |
| Sunplus HP HD Webcam [Fixed]                     | 1         | 0.4%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 19        | 33.33%  |
| Validity Sensors           | 17        | 29.82%  |
| Shenzhen Goodix Technology | 9         | 15.79%  |
| Upek                       | 4         | 7.02%   |
| LighTuning Technology      | 2         | 3.51%   |
| Elan Microelectronics      | 2         | 3.51%   |
| AuthenTec                  | 2         | 3.51%   |
| STMicroelectronics         | 1         | 1.75%   |
| Focal-systems.Corp         | 1         | 1.75%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown                                                    | 9         | 15.79%  |
| Shenzhen Goodix FingerPrint                                | 6         | 10.53%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 4         | 7.02%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 7.02%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 5.26%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 3.51%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 2         | 3.51%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 2         | 3.51%   |
| Synaptics  WBDI                                            | 2         | 3.51%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.51%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 2         | 3.51%   |
| Shenzhen Goodix  Fingerprint Device                        | 2         | 3.51%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 2         | 3.51%   |
| Elan ELAN:Fingerprint                                      | 2         | 3.51%   |
| AuthenTec Fingerprint Sensor                               | 2         | 3.51%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 1.75%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 1.75%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 1.75%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 1.75%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 1.75%   |
| Validity Sensors Synaptics WBDI                            | 1         | 1.75%   |
| Validity Sensors Fingerprint scanner                       | 1         | 1.75%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 1.75%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 1.75%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 1.75%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 1.75%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 15        | 50%     |
| Upek        | 5         | 16.67%  |
| Alcor Micro | 5         | 16.67%  |
| O2 Micro    | 4         | 13.33%  |
| Lenovo      | 1         | 3.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 16.67%  |
| Broadcom 58200                                                               | 5         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 13.33%  |
| Broadcom 5880                                                                | 4         | 13.33%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 6.67%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 3.33%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 3.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 275       | 66.11%  |
| 1     | 114       | 27.4%   |
| 2     | 22        | 5.29%   |
| 3     | 5         | 1.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 56        | 34.36%  |
| Net/wireless             | 30        | 18.4%   |
| Chipcard                 | 27        | 16.56%  |
| Graphics card            | 24        | 14.72%  |
| Multimedia controller    | 9         | 5.52%   |
| Communication controller | 5         | 3.07%   |
| Storage                  | 4         | 2.45%   |
| Camera                   | 3         | 1.84%   |
| Bluetooth                | 2         | 1.23%   |
| Net/ethernet             | 1         | 0.61%   |
| Modem                    | 1         | 0.61%   |
| Card reader              | 1         | 0.61%   |

