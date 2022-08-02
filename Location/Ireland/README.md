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

Total: 633

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [dfe7ba57b8](https://linux-hardware.org/?probe=dfe7ba57b8) | Jul 31, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [d83f785b08](https://linux-hardware.org/?probe=d83f785b08) | Jul 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| MSI           | AMETHYST-M                  | Desktop     | [d5fb610246](https://linux-hardware.org/?probe=d5fb610246) | Jul 26, 2022 |
| Samsung       | 935XDB                      | Notebook    | [d6149a337b](https://linux-hardware.org/?probe=d6149a337b) | Jul 26, 2022 |
| Dell          | 0V8WGR A01                  | Desktop     | [76ddff41fc](https://linux-hardware.org/?probe=76ddff41fc) | Jul 25, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [f70ea66873](https://linux-hardware.org/?probe=f70ea66873) | Jul 21, 2022 |
| Samsung       | 935XDB                      | Notebook    | [e01b518899](https://linux-hardware.org/?probe=e01b518899) | Jul 21, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [033c284273](https://linux-hardware.org/?probe=033c284273) | Jul 19, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [8d0399bc8d](https://linux-hardware.org/?probe=8d0399bc8d) | Jul 17, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ef61582503](https://linux-hardware.org/?probe=ef61582503) | Jul 16, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [e9be99b44d](https://linux-hardware.org/?probe=e9be99b44d) | Jul 14, 2022 |
| Jumper        | EZbook                      | Notebook    | [5e7336ee93](https://linux-hardware.org/?probe=5e7336ee93) | Jul 02, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [ca7efa311a](https://linux-hardware.org/?probe=ca7efa311a) | Jul 01, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [282d2ad16b](https://linux-hardware.org/?probe=282d2ad16b) | Jun 29, 2022 |
| ASUSTek       | X411UN                      | Notebook    | [d4543f64dc](https://linux-hardware.org/?probe=d4543f64dc) | Jun 24, 2022 |
| ASUSTek       | X411UN                      | Notebook    | [57e0198d3a](https://linux-hardware.org/?probe=57e0198d3a) | Jun 23, 2022 |
| Samsung       | 935XDB                      | Notebook    | [7089a0f6bc](https://linux-hardware.org/?probe=7089a0f6bc) | Jun 20, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [5caa4002f1](https://linux-hardware.org/?probe=5caa4002f1) | Jun 17, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [028b64776a](https://linux-hardware.org/?probe=028b64776a) | Jun 15, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [eef8a87283](https://linux-hardware.org/?probe=eef8a87283) | Jun 15, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [674cb88747](https://linux-hardware.org/?probe=674cb88747) | Jun 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c1bde29740](https://linux-hardware.org/?probe=c1bde29740) | Jun 11, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [d9ac2ec5c8](https://linux-hardware.org/?probe=d9ac2ec5c8) | Jun 08, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [a38fb61dfb](https://linux-hardware.org/?probe=a38fb61dfb) | Jun 08, 2022 |
| Samsung       | 935XDB                      | Notebook    | [497a2424e0](https://linux-hardware.org/?probe=497a2424e0) | Jun 07, 2022 |
| Samsung       | 935XDB                      | Notebook    | [3cde44fcf1](https://linux-hardware.org/?probe=3cde44fcf1) | Jun 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [3bd843466c](https://linux-hardware.org/?probe=3bd843466c) | Jun 04, 2022 |
| Dell          | Latitude 9420               | Notebook    | [28ba6de10d](https://linux-hardware.org/?probe=28ba6de10d) | Jun 01, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [0a87c33624](https://linux-hardware.org/?probe=0a87c33624) | Jun 01, 2022 |
| ASUSTek       | Maximus VII IMPACT          | Desktop     | [8b0844f325](https://linux-hardware.org/?probe=8b0844f325) | Jun 01, 2022 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 79        | 17.06%  |
| Ubuntu 18.04                 | 47        | 10.15%  |
| Debian 11                    | 13        | 2.81%   |
| OpenMandriva 4.2             | 12        | 2.59%   |
| Arch                         | 11        | 2.38%   |
| Debian 10                    | 10        | 2.16%   |
| Ubuntu 19.04                 | 9         | 1.94%   |
| Pop!_OS 21.10                | 9         | 1.94%   |
| Manjaro                      | 9         | 1.94%   |
| Linux Mint 20.2              | 9         | 1.94%   |
| Linux Mint 20                | 9         | 1.94%   |
| ArcoLinux Rolling            | 9         | 1.94%   |
| Pop!_OS 20.10                | 8         | 1.73%   |
| Pop!_OS 20.04                | 7         | 1.51%   |
| KDE neon 20.04               | 7         | 1.51%   |
| BlackPanther 18.1            | 7         | 1.51%   |
| Ubuntu 19.10                 | 6         | 1.3%    |
| Ubuntu 21.10                 | 5         | 1.08%   |
| ROSA R11                     | 5         | 1.08%   |
| ROSA R10                     | 5         | 1.08%   |
| Pop!_OS 22.04                | 5         | 1.08%   |
| Linux Mint 20.1              | 5         | 1.08%   |
| Linux Mint 19.3              | 5         | 1.08%   |
| Fedora 35                    | 5         | 1.08%   |
| Fedora 33                    | 5         | 1.08%   |
| Fedora 32                    | 5         | 1.08%   |
| Arch Rolling                 | 5         | 1.08%   |
| Zorin 16                     | 4         | 0.86%   |
| Zorin 15                     | 4         | 0.86%   |
| Ubuntu 22.04                 | 4         | 0.86%   |
| Ubuntu 20.10                 | 4         | 0.86%   |
| Ubuntu 16.04                 | 4         | 0.86%   |
| OpenMandriva 4.3             | 4         | 0.86%   |
| Lubuntu 20.04                | 4         | 0.86%   |
| Fedora 36                    | 4         | 0.86%   |
| Fedora 34                    | 4         | 0.86%   |
| Debian Unstable              | 4         | 0.86%   |
| Pop!_OS 21.04                | 3         | 0.65%   |
| OpenMandriva 4.50            | 3         | 0.65%   |
| Linux Mint 20.3              | 3         | 0.65%   |
| Linux Mint 19.2              | 3         | 0.65%   |
| Linux Mint 19.1              | 3         | 0.65%   |
| Linux Mint 19                | 3         | 0.65%   |
| Linux Mint 18.3              | 3         | 0.65%   |
| Kubuntu 20.04                | 3         | 0.65%   |
| Endless 3.7.8                | 3         | 0.65%   |
| Xubuntu 20.04                | 2         | 0.43%   |
| Ubuntu MATE 20.04            | 2         | 0.43%   |
| ROSA R9                      | 2         | 0.43%   |
| ROSA R11.1                   | 2         | 0.43%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.43%   |
| Manjaro 21.0.7               | 2         | 0.43%   |
| Manjaro 21.0.5               | 2         | 0.43%   |
| Manjaro 20.2                 | 2         | 0.43%   |
| Kubuntu 21.10                | 2         | 0.43%   |
| Kubuntu 21.04                | 2         | 0.43%   |
| Kubuntu 20.10                | 2         | 0.43%   |
| KDE neon 18.04               | 2         | 0.43%   |
| Gentoo 2.7                   | 2         | 0.43%   |
| Elementary 5.1.7             | 2         | 0.43%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 159       | 35.97%  |
| Linux Mint    | 38        | 8.6%    |
| Pop!_OS       | 30        | 6.79%   |
| Debian        | 30        | 6.79%   |
| Manjaro       | 22        | 4.98%   |
| Fedora        | 22        | 4.98%   |
| OpenMandriva  | 19        | 4.3%    |
| Arch          | 16        | 3.62%   |
| ROSA          | 12        | 2.71%   |
| Kubuntu       | 11        | 2.49%   |
| ArcoLinux     | 9         | 2.04%   |
| Zorin         | 8         | 1.81%   |
| KDE neon      | 8         | 1.81%   |
| BlackPanther  | 7         | 1.58%   |
| Lubuntu       | 6         | 1.36%   |
| Elementary    | 6         | 1.36%   |
| Endless       | 5         | 1.13%   |
| openSUSE      | 4         | 0.9%    |
| Xubuntu       | 3         | 0.68%   |
| Ubuntu Budgie | 3         | 0.68%   |
| Gentoo        | 3         | 0.68%   |
| Clear Linux   | 3         | 0.68%   |
| Ubuntu MATE   | 2         | 0.45%   |
| Peppermint    | 2         | 0.45%   |
| LMDE          | 2         | 0.45%   |
| Kali          | 2         | 0.45%   |
| CentOS        | 2         | 0.45%   |
| Trisquel      | 1         | 0.23%   |
| SteamOS       | 1         | 0.23%   |
| Solus         | 1         | 0.23%   |
| RHEL          | 1         | 0.23%   |
| MX            | 1         | 0.23%   |
| Linux Lite    | 1         | 0.23%   |
| Feren OS      | 1         | 0.23%   |
| Chrome OS     | 1         | 0.23%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.4.0-42-generic                | 15        | 2.96%   |
| 5.10.14-desktop-1omv4002        | 12        | 2.37%   |
| 5.3.0-46-generic                | 10        | 1.98%   |
| 5.4.0-52-generic                | 6         | 1.19%   |
| 4.18.16-desktop-1bP             | 6         | 1.19%   |
| 5.4.0-91-generic                | 5         | 0.99%   |
| 5.4.0-48-generic                | 5         | 0.99%   |
| 5.11.0-27-generic               | 5         | 0.99%   |
| 5.8.0-7630-generic              | 4         | 0.79%   |
| 5.8.0-43-generic                | 4         | 0.79%   |
| 5.4.0-72-generic                | 4         | 0.79%   |
| 5.4.0-47-generic                | 4         | 0.79%   |
| 5.4.0-31-generic                | 4         | 0.79%   |
| 5.4.0-29-generic                | 4         | 0.79%   |
| 5.4.0-26-generic                | 4         | 0.79%   |
| 5.3.0-28-generic                | 4         | 0.79%   |
| 5.16.7-desktop-1omv4003         | 4         | 0.79%   |
| 4.18.0-15-generic               | 4         | 0.79%   |
| 5.8.0-53-generic                | 3         | 0.59%   |
| 5.8.0-41-generic                | 3         | 0.59%   |
| 5.4.0-77-generic                | 3         | 0.59%   |
| 5.4.0-7634-generic              | 3         | 0.59%   |
| 5.4.0-58-generic                | 3         | 0.59%   |
| 5.4.0-54-generic                | 3         | 0.59%   |
| 5.4.0-40-generic                | 3         | 0.59%   |
| 5.4.0-39-generic                | 3         | 0.59%   |
| 5.4.0-37-generic                | 3         | 0.59%   |
| 5.3.0-45-generic                | 3         | 0.59%   |
| 5.3.0-40-generic                | 3         | 0.59%   |
| 5.17.5-arch1-1                  | 3         | 0.59%   |
| 5.17.5-76051705-generic         | 3         | 0.59%   |
| 5.16.15-76051615-generic        | 3         | 0.59%   |
| 5.15.11-76051511-generic        | 3         | 0.59%   |
| 5.15.0-40-generic               | 3         | 0.59%   |
| 5.12.4-desktop-1omv4050         | 3         | 0.59%   |
| 5.11.0-38-generic               | 3         | 0.59%   |
| 5.10.0-8-amd64                  | 3         | 0.59%   |
| 5.10.0-14-amd64                 | 3         | 0.59%   |
| 5.0.0-25-generic                | 3         | 0.59%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 3         | 0.59%   |
| 4.9.60-nrj-desktop-1rosa-i586   | 3         | 0.59%   |
| 4.19.0-9-amd64                  | 3         | 0.59%   |
| 4.15.0-50-generic               | 3         | 0.59%   |
| 4.10.0-38-generic               | 3         | 0.59%   |
| 5.8.14-arch1-1                  | 2         | 0.4%    |
| 5.8.0-7625-generic              | 2         | 0.4%    |
| 5.8.0-33-generic                | 2         | 0.4%    |
| 5.8.0-26-generic                | 2         | 0.4%    |
| 5.7.12-arch1-1                  | 2         | 0.4%    |
| 5.4.0-88-generic                | 2         | 0.4%    |
| 5.4.0-80-generic                | 2         | 0.4%    |
| 5.4.0-7625-generic              | 2         | 0.4%    |
| 5.4.0-73-generic                | 2         | 0.4%    |
| 5.4.0-70-generic                | 2         | 0.4%    |
| 5.4.0-65-generic                | 2         | 0.4%    |
| 5.4.0-62-generic                | 2         | 0.4%    |
| 5.4.0-56-generic                | 2         | 0.4%    |
| 5.4.0-53-generic                | 2         | 0.4%    |
| 5.4.0-51-generic                | 2         | 0.4%    |
| 5.4.0-13-generic                | 2         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 107       | 22.57%  |
| 4.15.0  | 36        | 7.59%   |
| 5.8.0   | 28        | 5.91%   |
| 5.3.0   | 26        | 5.49%   |
| 5.11.0  | 25        | 5.27%   |
| 5.13.0  | 15        | 3.16%   |
| 5.10.0  | 15        | 3.16%   |
| 5.0.0   | 15        | 3.16%   |
| 5.10.14 | 12        | 2.53%   |
| 4.19.0  | 11        | 2.32%   |
| 4.18.0  | 11        | 2.32%   |
| 5.17.5  | 8         | 1.69%   |
| 5.15.0  | 8         | 1.69%   |
| 4.18.16 | 6         | 1.27%   |
| 5.16.7  | 4         | 0.84%   |
| 5.16.11 | 4         | 0.84%   |
| 4.9.60  | 4         | 0.84%   |
| 5.8.14  | 3         | 0.63%   |
| 5.6.0   | 3         | 0.63%   |
| 5.16.15 | 3         | 0.63%   |
| 5.15.12 | 3         | 0.63%   |
| 5.15.11 | 3         | 0.63%   |
| 5.12.4  | 3         | 0.63%   |
| 4.9.155 | 3         | 0.63%   |
| 4.10.0  | 3         | 0.63%   |
| 5.7.9   | 2         | 0.42%   |
| 5.7.12  | 2         | 0.42%   |
| 5.6.7   | 2         | 0.42%   |
| 5.6.15  | 2         | 0.42%   |
| 5.18.10 | 2         | 0.42%   |
| 5.18.0  | 2         | 0.42%   |
| 5.15.7  | 2         | 0.42%   |
| 5.15.6  | 2         | 0.42%   |
| 5.15.5  | 2         | 0.42%   |
| 5.13.19 | 2         | 0.42%   |
| 5.13.13 | 2         | 0.42%   |
| 5.12.8  | 2         | 0.42%   |
| 5.12.2  | 2         | 0.42%   |
| 5.11.11 | 2         | 0.42%   |
| 5.11.10 | 2         | 0.42%   |
| 5.10.42 | 2         | 0.42%   |
| 5.10.2  | 2         | 0.42%   |
| 4.9.41  | 2         | 0.42%   |
| 4.13.0  | 2         | 0.42%   |
| 4.12.14 | 2         | 0.42%   |
| 3.10.0  | 2         | 0.42%   |
| 5.9.3   | 1         | 0.21%   |
| 5.9.16  | 1         | 0.21%   |
| 5.9.11  | 1         | 0.21%   |
| 5.9.1   | 1         | 0.21%   |
| 5.9.0   | 1         | 0.21%   |
| 5.9     | 1         | 0.21%   |
| 5.8.7   | 1         | 0.21%   |
| 5.8.18  | 1         | 0.21%   |
| 5.8.11  | 1         | 0.21%   |
| 5.8.10  | 1         | 0.21%   |
| 5.7.8   | 1         | 0.21%   |
| 5.7.7   | 1         | 0.21%   |
| 5.7.11  | 1         | 0.21%   |
| 5.6.3   | 1         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 112       | 24.14%  |
| 5.10    | 40        | 8.62%   |
| 4.15    | 36        | 7.76%   |
| 5.8     | 35        | 7.54%   |
| 5.11    | 31        | 6.68%   |
| 5.3     | 27        | 5.82%   |
| 5.15    | 22        | 4.74%   |
| 5.13    | 21        | 4.53%   |
| 4.18    | 17        | 3.66%   |
| 5.0     | 15        | 3.23%   |
| 5.17    | 14        | 3.02%   |
| 5.16    | 13        | 2.8%    |
| 4.19    | 12        | 2.59%   |
| 4.9     | 11        | 2.37%   |
| 5.6     | 10        | 2.16%   |
| 5.12    | 9         | 1.94%   |
| 5.7     | 7         | 1.51%   |
| 5.18    | 6         | 1.29%   |
| 5.9     | 5         | 1.08%   |
| 5.14    | 5         | 1.08%   |
| 4.10    | 3         | 0.65%   |
| 4.4     | 2         | 0.43%   |
| 4.13    | 2         | 0.43%   |
| 4.12    | 2         | 0.43%   |
| 3.10    | 2         | 0.43%   |
| 5.5     | 1         | 0.22%   |
| 5.2     | 1         | 0.22%   |
| 5       | 1         | 0.22%   |
| 4.14    | 1         | 0.22%   |
| 4.1     | 1         | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 405       | 94.85%  |
| i686    | 15        | 3.51%   |
| aarch64 | 7         | 1.64%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 193       | 42.89%  |
| KDE5            | 67        | 14.89%  |
| Unknown         | 66        | 14.67%  |
| XFCE            | 29        | 6.44%   |
| X-Cinnamon      | 23        | 5.11%   |
| KDE             | 18        | 4%      |
| MATE            | 9         | 2%      |
| Cinnamon        | 8         | 1.78%   |
| LXQt            | 7         | 1.56%   |
| KDE4            | 6         | 1.33%   |
| Unity           | 5         | 1.11%   |
| Pantheon        | 5         | 1.11%   |
| i3              | 4         | 0.89%   |
| Budgie          | 3         | 0.67%   |
| GNOME Flashback | 2         | 0.44%   |
| GNOME Classic   | 2         | 0.44%   |
| LXDE            | 1         | 0.22%   |
| LeftWM          | 1         | 0.22%   |
| Enlightenment   | 1         | 0.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 354       | 81.94%  |
| Unknown | 39        | 9.03%   |
| Wayland | 32        | 7.41%   |
| Tty     | 7         | 1.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 247       | 56.39%  |
| SDDM    | 67        | 15.3%   |
| GDM     | 57        | 13.01%  |
| LightDM | 27        | 6.16%   |
| TDM     | 19        | 4.34%   |
| GDM3    | 13        | 2.97%   |
| KDM     | 6         | 1.37%   |
| LXDM    | 2         | 0.46%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_IE   | 210       | 47.51%  |
| en_US   | 72        | 16.29%  |
| en_GB   | 66        | 14.93%  |
| Unknown | 66        | 14.93%  |
| pl_PL   | 10        | 2.26%   |
| es_ES   | 3         | 0.68%   |
| C       | 3         | 0.68%   |
| en_CA   | 2         | 0.45%   |
| bg_BG   | 2         | 0.45%   |
| ru_RU   | 1         | 0.23%   |
| pt_PT   | 1         | 0.23%   |
| it_IT   | 1         | 0.23%   |
| ga_IE   | 1         | 0.23%   |
| fr_FR   | 1         | 0.23%   |
| fr_BE   | 1         | 0.23%   |
| en_IN   | 1         | 0.23%   |
| en_DE   | 1         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 230       | 53.24%  |
| EFI  | 202       | 46.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Ext4                | 340       | 79.25%  |
| Overlay             | 31        | 7.23%   |
| Btrfs               | 24        | 5.59%   |
| Unknown             | 23        | 5.36%   |
| Xfs                 | 5         | 1.17%   |
| Zfs                 | 4         | 0.93%   |
| Fuse.fuse-overlayfs | 1         | 0.23%   |
| F2fs                | 1         | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 253       | 58.43%  |
| GPT     | 134       | 30.95%  |
| MBR     | 46        | 10.62%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 368       | 85.38%  |
| Yes       | 63        | 14.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 315       | 72.75%  |
| Yes       | 118       | 27.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 82        | 19.29%  |
| Lenovo                  | 75        | 17.65%  |
| ASUSTek Computer        | 55        | 12.94%  |
| Hewlett-Packard         | 48        | 11.29%  |
| Gigabyte Technology     | 22        | 5.18%   |
| Acer                    | 19        | 4.47%   |
| MSI                     | 16        | 3.76%   |
| Apple                   | 15        | 3.53%   |
| ASRock                  | 12        | 2.82%   |
| Toshiba                 | 10        | 2.35%   |
| Samsung Electronics     | 6         | 1.41%   |
| Intel                   | 6         | 1.41%   |
| TUXEDO                  | 4         | 0.94%   |
| PC Specialist           | 4         | 0.94%   |
| Medion                  | 4         | 0.94%   |
| Notebook                | 3         | 0.71%   |
| Foxconn                 | 3         | 0.71%   |
| Timi                    | 2         | 0.47%   |
| System76                | 2         | 0.47%   |
| Shuttle                 | 2         | 0.47%   |
| Seco                    | 2         | 0.47%   |
| Raspberry Pi Foundation | 2         | 0.47%   |
| Packard Bell            | 2         | 0.47%   |
| Nvidia                  | 2         | 0.47%   |
| HUAWEI                  | 2         | 0.47%   |
| Entroware               | 2         | 0.47%   |
| eMachines               | 2         | 0.47%   |
| Chuwi                   | 2         | 0.47%   |
| Sony UK                 | 1         | 0.24%   |
| Sony                    | 1         | 0.24%   |
| SLIMBOOK                | 1         | 0.24%   |
| Schenker                | 1         | 0.24%   |
| Rockchip                | 1         | 0.24%   |
| Pine Microsystems       | 1         | 0.24%   |
| Pegatron                | 1         | 0.24%   |
| MiTAC                   | 1         | 0.24%   |
| Microtech               | 1         | 0.24%   |
| Jumper                  | 1         | 0.24%   |
| IP3 Tech                | 1         | 0.24%   |
| Fujitsu Siemens         | 1         | 0.24%   |
| DFI                     | 1         | 0.24%   |
| AVITA                   | 1         | 0.24%   |
| AMI                     | 1         | 0.24%   |
| Alienware               | 1         | 0.24%   |
| Advent                  | 1         | 0.24%   |
| ABIT                    | 1         | 0.24%   |
| Unknown                 | 1         | 0.24%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| ASUS All Series                     | 6         | 1.41%   |
| Gigabyte B450M DS3H                 | 4         | 0.94%   |
| Dell OptiPlex 7010                  | 4         | 0.94%   |
| Lenovo V145-15AST 81MT              | 3         | 0.71%   |
| HP Compaq 8200 Elite SFF PC         | 3         | 0.71%   |
| Dell OptiPlex 790                   | 3         | 0.71%   |
| ASUS ROG STRIX B450-F GAMING        | 3         | 0.71%   |
| TUXEDO Pulse 15 Gen1                | 2         | 0.47%   |
| Seco C40                            | 2         | 0.47%   |
| RPi Raspberry Pi                    | 2         | 0.47%   |
| Nvidia Tegra                        | 2         | 0.47%   |
| MSI MS-7B79                         | 2         | 0.47%   |
| Lenovo ThinkStation D20 415892G     | 2         | 0.47%   |
| Lenovo ThinkPad X1 Carbon 3443CTO   | 2         | 0.47%   |
| Lenovo IdeaPad 510-15ISK 80SR       | 2         | 0.47%   |
| HP Notebook                         | 2         | 0.47%   |
| HP EliteDesk 800 G1 SFF             | 2         | 0.47%   |
| Gigabyte X570 AORUS ULTRA           | 2         | 0.47%   |
| Dell XPS 13 9310                    | 2         | 0.47%   |
| Dell XPS 13 9300                    | 2         | 0.47%   |
| Dell XPS 13 7390                    | 2         | 0.47%   |
| Dell Precision 5550                 | 2         | 0.47%   |
| Dell OptiPlex 780                   | 2         | 0.47%   |
| Dell OptiPlex 7020                  | 2         | 0.47%   |
| Dell Latitude E6230                 | 2         | 0.47%   |
| Dell Inspiron 13-5378               | 2         | 0.47%   |
| ASUS TUF Gaming X570-PLUS           | 2         | 0.47%   |
| ASUS P8P67 PRO                      | 2         | 0.47%   |
| ASUS M5A78L/USB3                    | 2         | 0.47%   |
| Apple MacBook6,1                    | 2         | 0.47%   |
| Acer Aspire E5-575G                 | 2         | 0.47%   |
| Unknown                             | 2         | 0.47%   |
| TUXEDO InfinityBook Pro 15 v5       | 1         | 0.24%   |
| TUXEDO InfinityBook Pro 14 Gen6     | 1         | 0.24%   |
| Toshiba TECRA R850                  | 1         | 0.24%   |
| Toshiba TECRA M4                    | 1         | 0.24%   |
| Toshiba Satellite Pro R50-B         | 1         | 0.24%   |
| Toshiba Satellite Pro C660          | 1         | 0.24%   |
| Toshiba Satellite L500              | 1         | 0.24%   |
| Toshiba Satellite L50-C             | 1         | 0.24%   |
| Toshiba Satellite L50-B             | 1         | 0.24%   |
| Toshiba Satellite C50-B             | 1         | 0.24%   |
| Toshiba Satellite A300              | 1         | 0.24%   |
| Toshiba PORTEGE R830                | 1         | 0.24%   |
| Timi TM1703                         | 1         | 0.24%   |
| Timi TM1607                         | 1         | 0.24%   |
| System76 Galago Pro                 | 1         | 0.24%   |
| System76 Bonobo Extreme             | 1         | 0.24%   |
| Sony VPCCB35FG                      | 1         | 0.24%   |
| Sony UK Raspberry Pi 3 Model B      | 1         | 0.24%   |
| SLIMBOOK PROX15                     | 1         | 0.24%   |
| Shuttle XS35V4                      | 1         | 0.24%   |
| Shuttle XS35V3                      | 1         | 0.24%   |
| Schenker XMG NEO (TGL/M21)          | 1         | 0.24%   |
| Samsung RC420/RC520/RC720           | 1         | 0.24%   |
| Samsung N150/N210/N220              | 1         | 0.24%   |
| Samsung Galaxy TabPro S             | 1         | 0.24%   |
| Samsung 935XDB                      | 1         | 0.24%   |
| Samsung 550P5C/550P7C               | 1         | 0.24%   |
| Samsung 350V5C/351V5C/3540VC/3440VC | 1         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 34        | 8%      |
| Dell Latitude       | 23        | 5.41%   |
| Dell OptiPlex       | 16        | 3.76%   |
| Dell Inspiron       | 14        | 3.29%   |
| Acer Aspire         | 14        | 3.29%   |
| Lenovo IdeaPad      | 13        | 3.06%   |
| Dell XPS            | 11        | 2.59%   |
| HP Pavilion         | 9         | 2.12%   |
| HP EliteBook        | 9         | 2.12%   |
| Dell Precision      | 9         | 2.12%   |
| Toshiba Satellite   | 7         | 1.65%   |
| Lenovo ThinkCentre  | 7         | 1.65%   |
| HP Compaq           | 7         | 1.65%   |
| ASUS TUF            | 6         | 1.41%   |
| ASUS PRIME          | 6         | 1.41%   |
| ASUS All            | 6         | 1.41%   |
| ASUS ROG            | 5         | 1.18%   |
| Gigabyte B450M      | 4         | 0.94%   |
| Dell Vostro         | 4         | 0.94%   |
| Lenovo Yoga         | 3         | 0.71%   |
| Lenovo V145-15AST   | 3         | 0.71%   |
| HP Presario         | 3         | 0.71%   |
| HP Laptop           | 3         | 0.71%   |
| HP EliteDesk        | 3         | 0.71%   |
| Apple MacBookPro5   | 3         | 0.71%   |
| TUXEDO Pulse        | 2         | 0.47%   |
| TUXEDO InfinityBook | 2         | 0.47%   |
| Toshiba TECRA       | 2         | 0.47%   |
| Seco C40            | 2         | 0.47%   |
| RPi Raspberry       | 2         | 0.47%   |
| Nvidia Tegra        | 2         | 0.47%   |
| MSI MS-7B79         | 2         | 0.47%   |
| Lenovo ThinkStation | 2         | 0.47%   |
| HP Notebook         | 2         | 0.47%   |
| Gigabyte X570       | 2         | 0.47%   |
| Gigabyte B450       | 2         | 0.47%   |
| Foxconn Pro         | 2         | 0.47%   |
| Dell Studio         | 2         | 0.47%   |
| ASUS ZenBook        | 2         | 0.47%   |
| ASUS P8P67          | 2         | 0.47%   |
| ASUS Maximus        | 2         | 0.47%   |
| ASUS M5A78L         | 2         | 0.47%   |
| ASUS CROSSHAIR      | 2         | 0.47%   |
| ASRock Z77          | 2         | 0.47%   |
| Apple MacBook6      | 2         | 0.47%   |
| Unknown             | 2         | 0.47%   |
| Toshiba PORTEGE     | 1         | 0.24%   |
| Timi TM1703         | 1         | 0.24%   |
| Timi TM1607         | 1         | 0.24%   |
| System76 Galago     | 1         | 0.24%   |
| System76 Bonobo     | 1         | 0.24%   |
| Sony VPCCB35FG      | 1         | 0.24%   |
| Sony UK Raspberry   | 1         | 0.24%   |
| SLIMBOOK PROX15     | 1         | 0.24%   |
| Shuttle XS35V4      | 1         | 0.24%   |
| Shuttle XS35V3      | 1         | 0.24%   |
| Schenker XMG        | 1         | 0.24%   |
| Samsung RC420       | 1         | 0.24%   |
| Samsung N150        | 1         | 0.24%   |
| Samsung Galaxy      | 1         | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 44        | 10.35%  |
| 2018    | 43        | 10.12%  |
| 2013    | 39        | 9.18%   |
| 2012    | 36        | 8.47%   |
| 2011    | 35        | 8.24%   |
| 2020    | 34        | 8%      |
| 2017    | 31        | 7.29%   |
| 2010    | 25        | 5.88%   |
| 2008    | 23        | 5.41%   |
| 2015    | 21        | 4.94%   |
| 2021    | 18        | 4.24%   |
| 2016    | 18        | 4.24%   |
| 2009    | 17        | 4%      |
| 2014    | 15        | 3.53%   |
| 2007    | 9         | 2.12%   |
| 2006    | 7         | 1.65%   |
| Unknown | 6         | 1.41%   |
| 2005    | 2         | 0.47%   |
| 2022    | 1         | 0.24%   |
| 2003    | 1         | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 247       | 58.12%  |
| Desktop        | 148       | 34.82%  |
| Convertible    | 7         | 1.65%   |
| Mini pc        | 7         | 1.65%   |
| System on chip | 6         | 1.41%   |
| All in one     | 6         | 1.41%   |
| Tablet         | 3         | 0.71%   |
| Phone          | 1         | 0.24%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 389       | 90.89%  |
| Enabled  | 39        | 9.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 425       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 100       | 23.04%  |
| 16.01-24.0  | 89        | 20.51%  |
| 3.01-4.0    | 86        | 19.82%  |
| 8.01-16.0   | 76        | 17.51%  |
| 32.01-64.0  | 41        | 9.45%   |
| 1.01-2.0    | 16        | 3.69%   |
| 64.01-256.0 | 11        | 2.53%   |
| 24.01-32.0  | 6         | 1.38%   |
| 2.01-3.0    | 5         | 1.15%   |
| 0.51-1.0    | 3         | 0.69%   |
| 0.01-0.5    | 1         | 0.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 169       | 36.11%  |
| 2.01-3.0   | 113       | 24.15%  |
| 3.01-4.0   | 68        | 14.53%  |
| 4.01-8.0   | 55        | 11.75%  |
| 0.51-1.0   | 37        | 7.91%   |
| 8.01-16.0  | 17        | 3.63%   |
| 0.01-0.5   | 5         | 1.07%   |
| 16.01-24.0 | 3         | 0.64%   |
| 32.01-64.0 | 1         | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 262       | 58.48%  |
| 2      | 106       | 23.66%  |
| 3      | 34        | 7.59%   |
| 4      | 19        | 4.24%   |
| 5      | 11        | 2.46%   |
| 7      | 5         | 1.12%   |
| 6      | 4         | 0.89%   |
| 0      | 4         | 0.89%   |
| 10     | 2         | 0.45%   |
| 9      | 1         | 0.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 250       | 57.87%  |
| Yes       | 182       | 42.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 369       | 86.62%  |
| No        | 57        | 13.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 353       | 82.48%  |
| No        | 75        | 17.52%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 268       | 62.04%  |
| No        | 164       | 37.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Ireland | 425       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Dublin              | 251       | 57.05%  |
| Cork                | 24        | 5.45%   |
| Limerick            | 15        | 3.41%   |
| Naas                | 12        | 2.73%   |
| Galway              | 11        | 2.5%    |
| Ennis               | 6         | 1.36%   |
| Drogheda            | 6         | 1.36%   |
| Portlaoise          | 5         | 1.14%   |
| Navan               | 5         | 1.14%   |
| Sligo               | 4         | 0.91%   |
| Nenagh              | 4         | 0.91%   |
| Kilkenny            | 4         | 0.91%   |
| Kenmare             | 4         | 0.91%   |
| Gorey               | 4         | 0.91%   |
| Athlone             | 4         | 0.91%   |
| Tuam                | 3         | 0.68%   |
| Enniscorthy         | 3         | 0.68%   |
| Dún Laoghaire      | 3         | 0.68%   |
| Wexford             | 2         | 0.45%   |
| Westport            | 2         | 0.45%   |
| Waterford           | 2         | 0.45%   |
| Oranmore            | 2         | 0.45%   |
| Maynooth            | 2         | 0.45%   |
| Mallow              | 2         | 0.45%   |
| Loughrea            | 2         | 0.45%   |
| Letterkenny         | 2         | 0.45%   |
| Cobh                | 2         | 0.45%   |
| Clonakilty          | 2         | 0.45%   |
| Cavan               | 2         | 0.45%   |
| Bray                | 2         | 0.45%   |
| Ballina             | 2         | 0.45%   |
| Balbriggan          | 2         | 0.45%   |
| Youghal             | 1         | 0.23%   |
| Wicklow             | 1         | 0.23%   |
| Tullamore           | 1         | 0.23%   |
| Tobercurry          | 1         | 0.23%   |
| Tipperary           | 1         | 0.23%   |
| Swords              | 1         | 0.23%   |
| Summerhill          | 1         | 0.23%   |
| Slane               | 1         | 0.23%   |
| Shanagolden         | 1         | 0.23%   |
| Scarriff            | 1         | 0.23%   |
| Santry              | 1         | 0.23%   |
| Newmarket on Fergus | 1         | 0.23%   |
| New Ross            | 1         | 0.23%   |
| Moyne               | 1         | 0.23%   |
| Midleton            | 1         | 0.23%   |
| Lucan               | 1         | 0.23%   |
| Listowel            | 1         | 0.23%   |
| Leixlip             | 1         | 0.23%   |
| Kilrush             | 1         | 0.23%   |
| Killorglin          | 1         | 0.23%   |
| Kildare             | 1         | 0.23%   |
| Kilcoole            | 1         | 0.23%   |
| Greystones          | 1         | 0.23%   |
| Enfield             | 1         | 0.23%   |
| Edenderry           | 1         | 0.23%   |
| Dunshaughlin        | 1         | 0.23%   |
| Dungarvan           | 1         | 0.23%   |
| Drumcondra          | 1         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 116       | 195    | 18.21%  |
| Samsung Electronics       | 111       | 158    | 17.43%  |
| Seagate                   | 81        | 136    | 12.72%  |
| Toshiba                   | 41        | 51     | 6.44%   |
| Crucial                   | 35        | 45     | 5.49%   |
| Unknown                   | 33        | 42     | 5.18%   |
| SanDisk                   | 33        | 41     | 5.18%   |
| Hitachi                   | 31        | 43     | 4.87%   |
| Kingston                  | 19        | 25     | 2.98%   |
| Intel                     | 13        | 16     | 2.04%   |
| HGST                      | 10        | 10     | 1.57%   |
| Micron Technology         | 9         | 10     | 1.41%   |
| A-DATA Technology         | 9         | 14     | 1.41%   |
| Fujitsu                   | 7         | 8      | 1.1%    |
| SK hynix                  | 6         | 6      | 0.94%   |
| Phison                    | 5         | 10     | 0.78%   |
| Verbatim                  | 4         | 4      | 0.63%   |
| PNY                       | 4         | 4      | 0.63%   |
| LITEON                    | 4         | 4      | 0.63%   |
| China                     | 4         | 7      | 0.63%   |
| Apple                     | 4         | 5      | 0.63%   |
| Silicon Motion            | 3         | 5      | 0.47%   |
| OCZ                       | 3         | 3      | 0.47%   |
| Micron/Crucial Technology | 3         | 4      | 0.47%   |
| KIOXIA                    | 3         | 4      | 0.47%   |
| KingSpec                  | 3         | 3      | 0.47%   |
| ASMT                      | 3         | 5      | 0.47%   |
| Transcend                 | 2         | 2      | 0.31%   |
| Team                      | 2         | 2      | 0.31%   |
| Netac                     | 2         | 2      | 0.31%   |
| Maxtor                    | 2         | 2      | 0.31%   |
| LITEONIT                  | 2         | 2      | 0.31%   |
| KingDian                  | 2         | 6      | 0.31%   |
| Integral                  | 2         | 2      | 0.31%   |
| Zheino                    | 1         | 1      | 0.16%   |
| WDS100T1                  | 1         | 1      | 0.16%   |
| W800S                     | 1         | 2      | 0.16%   |
| USB3.0                    | 1         | 1      | 0.16%   |
| Union Memory (Shenzhen)   | 1         | 1      | 0.16%   |
| Union Memory              | 1         | 1      | 0.16%   |
| TCSUNBOW                  | 1         | 1      | 0.16%   |
| SABRENT                   | 1         | 2      | 0.16%   |
| QNAP                      | 1         | 1      | 0.16%   |
| Plextor                   | 1         | 1      | 0.16%   |
| Palit                     | 1         | 1      | 0.16%   |
| MaxDigital                | 1         | 1      | 0.16%   |
| LaCie                     | 1         | 1      | 0.16%   |
| KESU                      | 1         | 1      | 0.16%   |
| JMicron Technology        | 1         | 1      | 0.16%   |
| Hikvision                 | 1         | 1      | 0.16%   |
| Hewlett-Packard           | 1         | 2      | 0.16%   |
| FORESEE                   | 1         | 1      | 0.16%   |
| faspeed                   | 1         | 1      | 0.16%   |
| ExcelStor                 | 1         | 2      | 0.16%   |
| EMTEC                     | 1         | 2      | 0.16%   |
| DRVEO                     | 1         | 1      | 0.16%   |
| Dogfish                   | 1         | 1      | 0.16%   |
| Corsair                   | 1         | 2      | 0.16%   |
| AMD                       | 1         | 1      | 0.16%   |
| ADplus                    | 1         | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  64GB             | 6         | 0.84%   |
| Toshiba MQ01ABD100 1TB             | 6         | 0.84%   |
| Seagate ST1000LM035-1RK172 1TB     | 6         | 0.84%   |
| Seagate ST1000DM010-2EP102 1TB     | 6         | 0.84%   |
| Samsung SSD 860 EVO 500GB          | 6         | 0.84%   |
| Samsung SSD 850 EVO 250GB          | 6         | 0.84%   |
| Samsung SSD 840 EVO 250GB          | 6         | 0.84%   |
| Samsung NVMe SSD Drive 500GB       | 6         | 0.84%   |
| Samsung NVMe SSD Drive 256GB       | 6         | 0.84%   |
| Crucial CT1000MX500SSD1 1TB        | 6         | 0.84%   |
| Unknown MMC Card  32GB             | 5         | 0.7%    |
| Seagate ST8000DM004-2CX188 8TB     | 5         | 0.7%    |
| Samsung SSD 970 EVO Plus 500GB     | 5         | 0.7%    |
| WDC WDS500G2B0B-00YS70 500GB SSD   | 4         | 0.56%   |
| WDC WD10EURX-83UY4Y0 1TB           | 4         | 0.56%   |
| Verbatim Vi550 S3 SSD 128GB        | 4         | 0.56%   |
| Seagate ST500DM002-1BD142 500GB    | 4         | 0.56%   |
| Seagate ST2000DL003-9VT166 2TB     | 4         | 0.56%   |
| Seagate Expansion Desk 4TB         | 4         | 0.56%   |
| SanDisk NVMe SSD Drive 512GB       | 4         | 0.56%   |
| Kingston SV300S37A120G 120GB SSD   | 4         | 0.56%   |
| Kingston SA400S37480G 480GB SSD    | 4         | 0.56%   |
| Crucial CT500MX500SSD1 500GB       | 4         | 0.56%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 3         | 0.42%   |
| WDC WD3200AAJS-60Z0A0 320GB        | 3         | 0.42%   |
| WDC WD20EZRX-00D8PB0 2TB           | 3         | 0.42%   |
| WDC WD10EZEX-08WN4A0 1TB           | 3         | 0.42%   |
| WDC WD10EALX-009BA0 1TB            | 3         | 0.42%   |
| Toshiba DT01ACA100 1TB             | 3         | 0.42%   |
| Seagate ST3500418AS 500GB          | 3         | 0.42%   |
| Seagate ST3500312CS 500GB          | 3         | 0.42%   |
| Seagate ST31000528AS 1TB           | 3         | 0.42%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 0.42%   |
| SanDisk NVMe SSD Drive 500GB       | 3         | 0.42%   |
| Samsung SSD 970 EVO 500GB          | 3         | 0.42%   |
| Samsung SSD 860 QVO 1TB            | 3         | 0.42%   |
| Samsung SSD 850 EVO 500GB          | 3         | 0.42%   |
| Samsung NVMe SSD Drive 512GB       | 3         | 0.42%   |
| PNY CS900 120GB SSD                | 3         | 0.42%   |
| Micron 2300 NVMe 512GB             | 3         | 0.42%   |
| Kingston SA400S37240G 240GB SSD    | 3         | 0.42%   |
| Hitachi HTS723232A7A364 320GB      | 3         | 0.42%   |
| Hitachi HDS721032CLA362 320GB      | 3         | 0.42%   |
| HGST HTS721010A9E630 1TB           | 3         | 0.42%   |
| HGST HTS545050A7E680 500GB         | 3         | 0.42%   |
| Crucial M4-CT128M4SSD2 128GB       | 3         | 0.42%   |
| Crucial CT480BX500SSD1 480GB       | 3         | 0.42%   |
| A-DATA SU650 240GB SSD             | 3         | 0.42%   |
| WDC WDS250G2B0C-00PXH0 250GB       | 2         | 0.28%   |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 2         | 0.28%   |
| WDC WDS100T1B0A-00H9H0 1TB SSD     | 2         | 0.28%   |
| WDC WD5000BPKT-60PK4T0 500GB       | 2         | 0.28%   |
| WDC WD5000AAKX-22ERMA0 500GB       | 2         | 0.28%   |
| WDC WD40EZRZ-19GXCB0 4TB           | 2         | 0.28%   |
| WDC WD2500AAKX-753CA1 250GB        | 2         | 0.28%   |
| WDC WD20EARX-00PASB0 2TB           | 2         | 0.28%   |
| WDC WD20EARS-00MVWB0 2TB           | 2         | 0.28%   |
| WDC WD10JPVX-22JC3T0 1TB           | 2         | 0.28%   |
| WDC WD10JPVX-00JC3T0 1TB           | 2         | 0.28%   |
| WDC WD10JPCX-24UE4T0 1TB           | 2         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 91        | 161    | 33.46%  |
| Seagate             | 80        | 135    | 29.41%  |
| Hitachi             | 31        | 43     | 11.4%   |
| Toshiba             | 30        | 37     | 11.03%  |
| Samsung Electronics | 10        | 12     | 3.68%   |
| HGST                | 10        | 10     | 3.68%   |
| Fujitsu             | 7         | 8      | 2.57%   |
| ASMT                | 3         | 5      | 1.1%    |
| Maxtor              | 2         | 2      | 0.74%   |
| Apple               | 2         | 2      | 0.74%   |
| Unknown             | 1         | 1      | 0.37%   |
| SABRENT             | 1         | 2      | 0.37%   |
| QNAP                | 1         | 1      | 0.37%   |
| LaCie               | 1         | 1      | 0.37%   |
| KESU                | 1         | 1      | 0.37%   |
| ExcelStor           | 1         | 2      | 0.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 61        | 79     | 28.64%  |
| Crucial             | 32        | 42     | 15.02%  |
| SanDisk             | 21        | 24     | 9.86%   |
| Kingston            | 18        | 23     | 8.45%   |
| WDC                 | 11        | 17     | 5.16%   |
| A-DATA Technology   | 7         | 11     | 3.29%   |
| Intel               | 5         | 5      | 2.35%   |
| Verbatim            | 4         | 4      | 1.88%   |
| PNY                 | 4         | 4      | 1.88%   |
| LITEON              | 4         | 4      | 1.88%   |
| China               | 4         | 7      | 1.88%   |
| Toshiba             | 3         | 4      | 1.41%   |
| OCZ                 | 3         | 3      | 1.41%   |
| Micron Technology   | 3         | 3      | 1.41%   |
| KingSpec            | 3         | 3      | 1.41%   |
| Apple               | 3         | 3      | 1.41%   |
| Transcend           | 2         | 2      | 0.94%   |
| Team                | 2         | 2      | 0.94%   |
| Netac               | 2         | 2      | 0.94%   |
| LITEONIT            | 2         | 2      | 0.94%   |
| KingDian            | 2         | 6      | 0.94%   |
| Integral            | 2         | 2      | 0.94%   |
| Zheino              | 1         | 1      | 0.47%   |
| W800S               | 1         | 2      | 0.47%   |
| USB3.0              | 1         | 1      | 0.47%   |
| TCSUNBOW            | 1         | 1      | 0.47%   |
| SK hynix            | 1         | 1      | 0.47%   |
| Plextor             | 1         | 1      | 0.47%   |
| Palit               | 1         | 1      | 0.47%   |
| Hikvision           | 1         | 1      | 0.47%   |
| Hewlett-Packard     | 1         | 2      | 0.47%   |
| FORESEE             | 1         | 1      | 0.47%   |
| faspeed             | 1         | 1      | 0.47%   |
| EMTEC               | 1         | 2      | 0.47%   |
| DRVEO               | 1         | 1      | 0.47%   |
| Dogfish             | 1         | 1      | 0.47%   |
| Corsair             | 1         | 2      | 0.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 218       | 423    | 39.28%  |
| SSD     | 186       | 271    | 33.51%  |
| NVMe    | 113       | 164    | 20.36%  |
| MMC     | 31        | 43     | 5.59%   |
| Unknown | 7         | 7      | 1.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 331       | 672    | 66.73%  |
| NVMe | 113       | 164    | 22.78%  |
| MMC  | 31        | 43     | 6.25%   |
| SAS  | 21        | 29     | 4.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 247       | 394    | 56.65%  |
| 0.51-1.0   | 131       | 195    | 30.05%  |
| 1.01-2.0   | 25        | 38     | 5.73%   |
| 3.01-4.0   | 17        | 34     | 3.9%    |
| 2.01-3.0   | 8         | 11     | 1.83%   |
| 4.01-10.0  | 8         | 22     | 1.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 110       | 24.55%  |
| 251-500        | 103       | 22.99%  |
| 501-1000       | 60        | 13.39%  |
| 51-100         | 42        | 9.38%   |
| 1-20           | 36        | 8.04%   |
| 1001-2000      | 29        | 6.47%   |
| More than 3000 | 25        | 5.58%   |
| Unknown        | 17        | 3.79%   |
| 21-50          | 14        | 3.13%   |
| 2001-3000      | 12        | 2.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 178       | 38.2%   |
| 101-250        | 67        | 14.38%  |
| 21-50          | 61        | 13.09%  |
| 51-100         | 53        | 11.37%  |
| 251-500        | 32        | 6.87%   |
| 501-1000       | 30        | 6.44%   |
| Unknown        | 17        | 3.65%   |
| More than 3000 | 12        | 2.58%   |
| 1001-2000      | 9         | 1.93%   |
| 2001-3000      | 7         | 1.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD10EALX-009BA0 1TB                        | 3         | 8      | 5.45%   |
| Seagate ST2000DL003-9VT166 2TB                 | 3         | 5      | 5.45%   |
| WDC WD2500AAKX-753CA1 250GB                    | 2         | 3      | 3.64%   |
| Hitachi HTS723232A7A364 320GB                  | 2         | 2      | 3.64%   |
| WDC WD7500BPKX-00HPJT0 752GB                   | 1         | 1      | 1.82%   |
| WDC WD5000BEVT-35A0RT0 500GB                   | 1         | 1      | 1.82%   |
| WDC WD5000AAKX-001CA0 500GB                    | 1         | 1      | 1.82%   |
| WDC WD400JB-00FMA0 40GB                        | 1         | 2      | 1.82%   |
| WDC WD3200AVJS-63B6A0 320GB                    | 1         | 1      | 1.82%   |
| WDC WD2500BEVT-22A23T0 250GB                   | 1         | 1      | 1.82%   |
| WDC WD2500BEKT-75A25T0 250GB                   | 1         | 1      | 1.82%   |
| WDC WD2500AAKX-603CA0 250GB                    | 1         | 1      | 1.82%   |
| WDC WD20EZRZ-00Z5HB0 2TB                       | 1         | 1      | 1.82%   |
| WDC WD10EZEX-00BN5A0 1TB                       | 1         | 1      | 1.82%   |
| WDC WD1001FALS-00E8B0 1TB                      | 1         | 2      | 1.82%   |
| Toshiba MQ01ABF050H 500GB                      | 1         | 1      | 1.82%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 1.82%   |
| Toshiba MK1652GSX 160GB                        | 1         | 1      | 1.82%   |
| Toshiba MK1059GSM 1TB                          | 1         | 1      | 1.82%   |
| Toshiba DT01ACA050 500GB                       | 1         | 1      | 1.82%   |
| Seagate ST910021AS 100GB                       | 1         | 1      | 1.82%   |
| Seagate ST4000DX001-1CE168 4TB                 | 1         | 1      | 1.82%   |
| Seagate ST3500418AS 500GB                      | 1         | 2      | 1.82%   |
| Seagate ST31500541AS 1TB                       | 1         | 1      | 1.82%   |
| Seagate ST3120026A 120GB                       | 1         | 1      | 1.82%   |
| Seagate ST31000333AS 1TB                       | 1         | 2      | 1.82%   |
| Seagate ST3000DM001-1ER166 3TB                 | 1         | 1      | 1.82%   |
| SanDisk SSD PLUS 240GB                         | 1         | 1      | 1.82%   |
| Samsung Electronics SSD 970 EVO Plus 2TB       | 1         | 1      | 1.82%   |
| Samsung Electronics HM120JC 120GB              | 1         | 1      | 1.82%   |
| Samsung Electronics HD103SI 1TB                | 1         | 1      | 1.82%   |
| Netac SSD 128GB                                | 1         | 1      | 1.82%   |
| Micron Technology 2300 NVMe 512GB              | 1         | 1      | 1.82%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 1.82%   |
| Maxtor STM3250310AS 250GB                      | 1         | 1      | 1.82%   |
| Intel SSDSA2M080G2GC 80GB                      | 1         | 1      | 1.82%   |
| Hitachi HUS724030ALA640 3TB                    | 1         | 2      | 1.82%   |
| Hitachi HTS545050B9A300 500GB                  | 1         | 1      | 1.82%   |
| Hitachi HTS545025B9SA02 250GB                  | 1         | 1      | 1.82%   |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 1.82%   |
| Hitachi HDT721016SLA380 160GB                  | 1         | 2      | 1.82%   |
| Hitachi HDS721010CLA332 1TB                    | 1         | 1      | 1.82%   |
| Hitachi DK23CA-30 32GB                         | 1         | 1      | 1.82%   |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 1.82%   |
| HGST HTS541010A7E630 1TB                       | 1         | 1      | 1.82%   |
| Fujitsu MHJ2181AT 18GB                         | 1         | 1      | 1.82%   |
| DRVEO X1 SSD 480GB                             | 1         | 1      | 1.82%   |
| China T480 480GB SSD                           | 1         | 1      | 1.82%   |
| A-DATA Technology SU800 128GB SSD              | 1         | 1      | 1.82%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 24     | 25%     |
| Seagate             | 10        | 14     | 19.23%  |
| Hitachi             | 9         | 11     | 17.31%  |
| Toshiba             | 5         | 5      | 9.62%   |
| Samsung Electronics | 3         | 3      | 5.77%   |
| Micron Technology   | 2         | 2      | 3.85%   |
| HGST                | 2         | 2      | 3.85%   |
| SanDisk             | 1         | 1      | 1.92%   |
| Netac               | 1         | 1      | 1.92%   |
| Maxtor              | 1         | 1      | 1.92%   |
| Intel               | 1         | 1      | 1.92%   |
| Fujitsu             | 1         | 1      | 1.92%   |
| DRVEO               | 1         | 1      | 1.92%   |
| China               | 1         | 1      | 1.92%   |
| A-DATA Technology   | 1         | 1      | 1.92%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 24     | 30.23%  |
| Seagate             | 10        | 14     | 23.26%  |
| Hitachi             | 9         | 11     | 20.93%  |
| Toshiba             | 5         | 5      | 11.63%  |
| Samsung Electronics | 2         | 2      | 4.65%   |
| HGST                | 2         | 2      | 4.65%   |
| Maxtor              | 1         | 1      | 2.33%   |
| Fujitsu             | 1         | 1      | 2.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 60     | 79.07%  |
| SSD  | 7         | 7      | 16.28%  |
| NVMe | 2         | 2      | 4.65%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                   | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| KingDian S400 120GB SSD | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| KingDian | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 265       | 535    | 56.5%   |
| Works    | 161       | 303    | 34.33%  |
| Malfunc  | 42        | 69     | 8.96%   |
| Failed   | 1         | 1      | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 280       | 54.05%  |
| AMD                          | 79        | 15.25%  |
| Samsung Electronics          | 49        | 9.46%   |
| SanDisk                      | 25        | 4.83%   |
| Nvidia                       | 12        | 2.32%   |
| Toshiba America Info Systems | 9         | 1.74%   |
| Marvell Technology Group     | 9         | 1.74%   |
| ASMedia Technology           | 8         | 1.54%   |
| Micron/Crucial Technology    | 6         | 1.16%   |
| Micron Technology            | 6         | 1.16%   |
| SK hynix                     | 5         | 0.97%   |
| Phison Electronics           | 5         | 0.97%   |
| JMicron Technology           | 5         | 0.97%   |
| Union Memory (Shenzhen)      | 3         | 0.58%   |
| Silicon Motion               | 3         | 0.58%   |
| LSI Logic / Symbios Logic    | 3         | 0.58%   |
| KIOXIA                       | 3         | 0.58%   |
| ULi Electronics              | 1         | 0.19%   |
| Silicon Image                | 1         | 0.19%   |
| Seagate Technology           | 1         | 0.19%   |
| Realtek Semiconductor        | 1         | 0.19%   |
| Kingston Technology Company  | 1         | 0.19%   |
| Broadcom / LSI               | 1         | 0.19%   |
| ADATA Technology             | 1         | 0.19%   |
| Adaptec                      | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 59        | 9.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 30        | 4.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 29        | 4.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 19        | 3.13%   |
| AMD 400 Series Chipset SATA Controller                                                  | 17        | 2.8%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 15        | 2.47%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15        | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 15        | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 13        | 2.14%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 11        | 1.81%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 11        | 1.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11        | 1.81%   |
| Samsung NVMe SSD Controller 980                                                         | 10        | 1.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 10        | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10        | 1.64%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 9         | 1.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 1.48%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8         | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8         | 1.32%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 8         | 1.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7         | 1.15%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 7         | 1.15%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 7         | 1.15%   |
| Micron Non-Volatile memory controller                                                   | 6         | 0.99%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 0.99%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 6         | 0.99%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 6         | 0.99%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 6         | 0.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 6         | 0.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 0.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6         | 0.99%   |
| Nvidia MCP79 AHCI Controller                                                            | 5         | 0.82%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 0.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5         | 0.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5         | 0.82%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5         | 0.82%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 4         | 0.66%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 4         | 0.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4         | 0.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4         | 0.66%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4         | 0.66%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 0.66%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 4         | 0.66%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 4         | 0.66%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4         | 0.66%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 3         | 0.49%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 3         | 0.49%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3         | 0.49%   |
| SanDisk PC SN520 NVMe SSD                                                               | 3         | 0.49%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 3         | 0.49%   |
| Intel SSD 660P Series                                                                   | 3         | 0.49%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 0.49%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 0.49%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 0.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 0.49%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3         | 0.49%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3         | 0.49%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3         | 0.49%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.49%   |
| AMD FCH SATA Controller D                                                               | 3         | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 311       | 59.69%  |
| NVMe | 114       | 21.88%  |
| IDE  | 65        | 12.48%  |
| RAID | 28        | 5.37%   |
| SCSI | 3         | 0.58%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 322       | 75.76%  |
| AMD    | 96        | 22.59%  |
| ARM    | 7         | 1.65%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 1.64%   |
| ARM Processor                                 | 7         | 1.64%   |
| AMD Ryzen 5 3600 6-Core Processor             | 7         | 1.64%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 1.4%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 1.4%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.17%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.17%   |
| Intel Core i7-2600K CPU @ 3.40GHz             | 5         | 1.17%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 1.17%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 1.17%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 5         | 1.17%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 4         | 0.93%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 0.93%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 0.93%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 0.93%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 4         | 0.93%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 0.93%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 4         | 0.93%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3         | 0.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 0.7%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 0.7%    |
| Intel Core i5-3340M CPU @ 2.70GHz             | 3         | 0.7%    |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 0.7%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 0.7%    |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.7%    |
| Intel Core i3-2120 CPU @ 3.30GHz              | 3         | 0.7%    |
| Intel Core i3-2100 CPU @ 3.10GHz              | 3         | 0.7%    |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz          | 3         | 0.7%    |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 3         | 0.7%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 0.7%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 3         | 0.7%    |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 0.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.7%    |
| AMD Athlon II X4 620 Processor                | 3         | 0.7%    |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 3         | 0.7%    |
| Intel Xeon CPU X5690 @ 3.47GHz                | 2         | 0.47%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 2         | 0.47%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.47%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.47%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.47%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.47%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 2         | 0.47%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 0.47%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.47%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 2         | 0.47%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.47%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.47%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.47%   |
| Intel Core i5-4690K CPU @ 3.50GHz             | 2         | 0.47%   |
| Intel Core i5-4670K CPU @ 3.40GHz             | 2         | 0.47%   |
| Intel Core i5-3570 CPU @ 3.40GHz              | 2         | 0.47%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.47%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.47%   |
| Intel Core i5-2500 CPU @ 3.30GHz              | 2         | 0.47%   |
| Intel Core i5-10500 CPU @ 3.10GHz             | 2         | 0.47%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.47%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 2         | 0.47%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.47%   |
| Intel Core i3-4150 CPU @ 3.50GHz              | 2         | 0.47%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 2         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 92        | 21.5%   |
| Intel Core i7           | 89        | 20.79%  |
| Intel Core i3           | 32        | 7.48%   |
| Other                   | 28        | 6.54%   |
| AMD Ryzen 5             | 27        | 6.31%   |
| Intel Core 2 Duo        | 22        | 5.14%   |
| Intel Celeron           | 20        | 4.67%   |
| Intel Atom              | 10        | 2.34%   |
| AMD Ryzen 7             | 9         | 2.1%    |
| Intel Pentium           | 7         | 1.64%   |
| Intel Core 2 Quad       | 7         | 1.64%   |
| AMD Ryzen 9             | 7         | 1.64%   |
| Intel Xeon              | 6         | 1.4%    |
| AMD FX                  | 6         | 1.4%    |
| AMD Athlon 64 X2        | 6         | 1.4%    |
| Intel Pentium Dual-Core | 4         | 0.93%   |
| AMD Ryzen 3             | 4         | 0.93%   |
| AMD A8                  | 4         | 0.93%   |
| Intel Core 2            | 3         | 0.7%    |
| AMD Athlon II X4        | 3         | 0.7%    |
| AMD A6                  | 3         | 0.7%    |
| Intel Pentium 4         | 2         | 0.47%   |
| Intel Core m3           | 2         | 0.47%   |
| Intel Core i9           | 2         | 0.47%   |
| Intel Celeron Dual-Core | 2         | 0.47%   |
| AMD Ryzen Threadripper  | 2         | 0.47%   |
| AMD Ryzen Embedded      | 2         | 0.47%   |
| AMD Phenom II X6        | 2         | 0.47%   |
| AMD A4                  | 2         | 0.47%   |
| Intel Pentium Silver    | 1         | 0.23%   |
| Intel Pentium M         | 1         | 0.23%   |
| Intel Pentium III       | 1         | 0.23%   |
| Intel Pentium D         | 1         | 0.23%   |
| Intel Genuine           | 1         | 0.23%   |
| Intel Core m7           | 1         | 0.23%   |
| Intel Core m5           | 1         | 0.23%   |
| Intel Core 2 Extreme    | 1         | 0.23%   |
| Intel Celeron M         | 1         | 0.23%   |
| AMD Turion 64 X2 Mobile | 1         | 0.23%   |
| AMD Sempron             | 1         | 0.23%   |
| AMD Ryzen 7 PRO         | 1         | 0.23%   |
| AMD Ryzen 5 PRO         | 1         | 0.23%   |
| AMD PRO A10             | 1         | 0.23%   |
| AMD Phenom II X4        | 1         | 0.23%   |
| AMD Phenom II           | 1         | 0.23%   |
| AMD E2                  | 1         | 0.23%   |
| AMD E1                  | 1         | 0.23%   |
| AMD E                   | 1         | 0.23%   |
| AMD Athlon II X2        | 1         | 0.23%   |
| AMD Athlon Dual Core    | 1         | 0.23%   |
| AMD Athlon              | 1         | 0.23%   |
| AMD A10                 | 1         | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 172       | 40.38%  |
| 2       | 171       | 40.14%  |
| 6       | 35        | 8.22%   |
| 8       | 17        | 3.99%   |
| 1       | 15        | 3.52%   |
| 12      | 9         | 2.11%   |
| 3       | 3         | 0.7%    |
| 14      | 2         | 0.47%   |
| 32      | 1         | 0.23%   |
| Unknown | 1         | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 422       | 99.29%  |
| 2      | 3         | 0.71%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 272       | 63.55%  |
| 1       | 155       | 36.21%  |
| Unknown | 1         | 0.23%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 407       | 95.32%  |
| Unknown        | 17        | 3.98%   |
| 32-bit         | 3         | 0.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 102       | 23.39%  |
| 0x306a9    | 30        | 6.88%   |
| 0x206a7    | 24        | 5.5%    |
| 0x1067a    | 20        | 4.59%   |
| 0x306c3    | 19        | 4.36%   |
| 0x806e9    | 15        | 3.44%   |
| 0x806ec    | 14        | 3.21%   |
| 0x806c1    | 10        | 2.29%   |
| 0x806ea    | 9         | 2.06%   |
| 0x406e3    | 9         | 2.06%   |
| 0x40651    | 9         | 2.06%   |
| 0x906ea    | 7         | 1.61%   |
| 0x10676    | 7         | 1.61%   |
| 0xa0652    | 6         | 1.38%   |
| 0x906e9    | 6         | 1.38%   |
| 0x406c4    | 6         | 1.38%   |
| 0x306d4    | 6         | 1.38%   |
| 0x30678    | 6         | 1.38%   |
| 0x08701021 | 6         | 1.38%   |
| 0x08108109 | 6         | 1.38%   |
| 0x20655    | 5         | 1.15%   |
| 0x0810100b | 5         | 1.15%   |
| 0x06006705 | 5         | 1.15%   |
| 0x6fd      | 4         | 0.92%   |
| 0x08108102 | 4         | 0.92%   |
| 0x0800820d | 4         | 0.92%   |
| 0xa0653    | 3         | 0.69%   |
| 0x706e5    | 3         | 0.69%   |
| 0x6fb      | 3         | 0.69%   |
| 0x506e3    | 3         | 0.69%   |
| 0x206c2    | 3         | 0.69%   |
| 0x106ca    | 3         | 0.69%   |
| 0x08701013 | 3         | 0.69%   |
| 0x06001119 | 3         | 0.69%   |
| 0x06000852 | 3         | 0.69%   |
| 0x010000c8 | 3         | 0.69%   |
| 0x906ed    | 2         | 0.46%   |
| 0x906a3    | 2         | 0.46%   |
| 0x806d1    | 2         | 0.46%   |
| 0x706a8    | 2         | 0.46%   |
| 0x706a1    | 2         | 0.46%   |
| 0x6f6      | 2         | 0.46%   |
| 0x6d8      | 2         | 0.46%   |
| 0x30661    | 2         | 0.46%   |
| 0x20652    | 2         | 0.46%   |
| 0x106e5    | 2         | 0.46%   |
| 0x106a5    | 2         | 0.46%   |
| 0x0a50000c | 2         | 0.46%   |
| 0x08600103 | 2         | 0.46%   |
| 0x07030106 | 2         | 0.46%   |
| 0x0600611a | 2         | 0.46%   |
| 0x010000db | 2         | 0.46%   |
| 0xf47      | 1         | 0.23%   |
| 0xf43      | 1         | 0.23%   |
| 0xf41      | 1         | 0.23%   |
| 0x906eb    | 1         | 0.23%   |
| 0x6f7      | 1         | 0.23%   |
| 0x6f2      | 1         | 0.23%   |
| 0x6ec      | 1         | 0.23%   |
| 0x6b1      | 1         | 0.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 62        | 14.55%  |
| IvyBridge        | 40        | 9.39%   |
| SandyBridge      | 35        | 8.22%   |
| Haswell          | 33        | 7.75%   |
| Penryn           | 28        | 6.57%   |
| Zen+             | 20        | 4.69%   |
| Zen 2            | 19        | 4.46%   |
| Skylake          | 19        | 4.46%   |
| Silvermont       | 17        | 3.99%   |
| Westmere         | 14        | 3.29%   |
| TigerLake        | 12        | 2.82%   |
| Core             | 12        | 2.82%   |
| CometLake        | 10        | 2.35%   |
| K8 Hammer        | 9         | 2.11%   |
| K10              | 9         | 2.11%   |
| Excavator        | 9         | 2.11%   |
| Zen              | 8         | 1.88%   |
| Piledriver       | 8         | 1.88%   |
| Unknown          | 8         | 1.88%   |
| Broadwell        | 7         | 1.64%   |
| Nehalem          | 6         | 1.41%   |
| Icelake          | 6         | 1.41%   |
| Goldmont plus    | 6         | 1.41%   |
| Zen 3            | 5         | 1.17%   |
| Bonnell          | 5         | 1.17%   |
| P6               | 4         | 0.94%   |
| Puma             | 3         | 0.7%    |
| NetBurst         | 3         | 0.7%    |
| Goldmont         | 2         | 0.47%   |
| Bobcat           | 2         | 0.47%   |
| Alderlake Hybrid | 2         | 0.47%   |
| Steamroller      | 1         | 0.23%   |
| Jaguar           | 1         | 0.23%   |
| Bulldozer        | 1         | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 242       | 49.29%  |
| Nvidia | 136       | 27.7%   |
| AMD    | 113       | 23.01%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 22        | 4.31%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 21        | 4.12%   |
| Intel HD Graphics 620                                                                    | 15        | 2.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 14        | 2.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 1.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 1.96%   |
| Intel UHD Graphics 620                                                                   | 9         | 1.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 1.76%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 1.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 1.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 1.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 1.57%   |
| Intel HD Graphics 630                                                                    | 8         | 1.57%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 1.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 1.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 1.57%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 7         | 1.37%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.18%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 1.18%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 1.18%   |
| AMD Renoir                                                                               | 6         | 1.18%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 1.18%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 0.98%   |
| Nvidia C79 [GeForce 9400M]                                                               | 5         | 0.98%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 0.98%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 0.98%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 0.98%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5         | 0.98%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 0.98%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.78%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 4         | 0.78%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 4         | 0.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 0.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 0.78%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 0.78%   |
| AMD Caicos PRO [Radeon HD 7450]                                                          | 4         | 0.78%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.59%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 3         | 0.59%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.59%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.59%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.59%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 3         | 0.59%   |
| Nvidia GM204 [GeForce GTX 980]                                                           | 3         | 0.59%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 0.59%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.59%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.59%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3         | 0.59%   |
| Intel HD Graphics 515                                                                    | 3         | 0.59%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 0.59%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 0.59%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 3         | 0.59%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 3         | 0.59%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.59%   |
| AMD Cezanne                                                                              | 3         | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.39%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2         | 0.39%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 2         | 0.39%   |
| Nvidia GM204M [GeForce GTX 970M]                                                         | 2         | 0.39%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 181       | 42.09%  |
| 1 x AMD        | 92        | 21.4%   |
| 1 x Nvidia     | 79        | 18.37%  |
| Intel + Nvidia | 49        | 11.4%   |
| 2 x AMD        | 11        | 2.56%   |
| Other          | 7         | 1.63%   |
| AMD + Nvidia   | 7         | 1.63%   |
| Intel + AMD    | 3         | 0.7%    |
| 2 x Nvidia     | 1         | 0.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 340       | 78.7%   |
| Proprietary | 69        | 15.97%  |
| Unknown     | 23        | 5.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 231       | 52.14%  |
| 0.01-0.5   | 53        | 11.96%  |
| 1.01-2.0   | 45        | 10.16%  |
| 3.01-4.0   | 38        | 8.58%   |
| 0.51-1.0   | 38        | 8.58%   |
| 7.01-8.0   | 19        | 4.29%   |
| 5.01-6.0   | 12        | 2.71%   |
| 2.01-3.0   | 4         | 0.9%    |
| 8.01-16.0  | 2         | 0.45%   |
| 16.01-24.0 | 1         | 0.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 51        | 11.28%  |
| Dell                    | 50        | 11.06%  |
| LG Display              | 49        | 10.84%  |
| Samsung Electronics     | 45        | 9.96%   |
| BOE                     | 33        | 7.3%    |
| Chimei Innolux          | 30        | 6.64%   |
| Acer                    | 19        | 4.2%    |
| Sharp                   | 17        | 3.76%   |
| Hewlett-Packard         | 15        | 3.32%   |
| BenQ                    | 14        | 3.1%    |
| Apple                   | 14        | 3.1%    |
| Philips                 | 13        | 2.88%   |
| Goldstar                | 12        | 2.65%   |
| Iiyama                  | 10        | 2.21%   |
| AOC                     | 8         | 1.77%   |
| Lenovo                  | 7         | 1.55%   |
| Chi Mei Optoelectronics | 7         | 1.55%   |
| PANDA                   | 5         | 1.11%   |
| Ancor Communications    | 4         | 0.88%   |
| ___                     | 3         | 0.66%   |
| ViewSonic               | 3         | 0.66%   |
| Vestel Elektronik       | 3         | 0.66%   |
| Unknown                 | 3         | 0.66%   |
| InfoVision              | 3         | 0.66%   |
| HannStar                | 3         | 0.66%   |
| Toshiba                 | 2         | 0.44%   |
| Sony                    | 2         | 0.44%   |
| MiTAC                   | 2         | 0.44%   |
| LG Philips              | 2         | 0.44%   |
| CPT                     | 2         | 0.44%   |
| BOE Technology Group    | 2         | 0.44%   |
| Unknown                 | 2         | 0.44%   |
| Targa Visionary         | 1         | 0.22%   |
| Targa                   | 1         | 0.22%   |
| RTK                     | 1         | 0.22%   |
| Quanta Display          | 1         | 0.22%   |
| Panasonic               | 1         | 0.22%   |
| OEM                     | 1         | 0.22%   |
| NEC Computers           | 1         | 0.22%   |
| MSI                     | 1         | 0.22%   |
| Medion                  | 1         | 0.22%   |
| LGD                     | 1         | 0.22%   |
| Lenovo Group Limited    | 1         | 0.22%   |
| HYO                     | 1         | 0.22%   |
| HUAWEI                  | 1         | 0.22%   |
| HKC                     | 1         | 0.22%   |
| CSO                     | 1         | 0.22%   |
| CHR                     | 1         | 0.22%   |
| ASUSTek Computer        | 1         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Iiyama PLT2336 IVM5628 1920x1080 509x286mm 23.0-inch                  | 5         | 1.05%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch  | 4         | 0.84%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.84%   |
| ___ LCD TV ___9000 1360x768                                           | 3         | 0.63%   |
| Vestel Elektronik 39FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 3         | 0.63%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 3         | 0.63%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 3         | 0.63%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 3         | 0.63%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch           | 3         | 0.63%   |
| Dell P2014H DEL4097 1600x900 434x236mm 19.4-inch                      | 3         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch      | 3         | 0.63%   |
| BenQ BenQG2222HDL BNQ7859 1920x1080 478x269mm 21.6-inch               | 3         | 0.63%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 3         | 0.63%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 2         | 0.42%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 2         | 0.42%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch               | 2         | 0.42%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch               | 2         | 0.42%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 2         | 0.42%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch   | 2         | 0.42%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 2         | 0.42%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 2         | 0.42%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 2         | 0.42%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 2         | 0.42%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.42%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch         | 2         | 0.42%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 2         | 0.42%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 2         | 0.42%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 0.42%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 2         | 0.42%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.42%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch               | 2         | 0.42%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 2         | 0.42%   |
| Hewlett-Packard Z34c HWP3201 3440x1440 797x333mm 34.0-inch            | 2         | 0.42%   |
| Dell U2715H DELD069 2560x1440 597x336mm 27.0-inch                     | 2         | 0.42%   |
| Dell U2518D DEL413C 2560x1440 553x311mm 25.0-inch                     | 2         | 0.42%   |
| Dell U2518D DEL413A 2560x1440 550x310mm 24.9-inch                     | 2         | 0.42%   |
| Dell P2417H DELA0DB 1920x1080 530x300mm 24.0-inch                     | 2         | 0.42%   |
| Dell P2317H DEL40F3 1920x1080 509x286mm 23.0-inch                     | 2         | 0.42%   |
| Dell E171FP DEL300F 1280x1024 340x270mm 17.1-inch                     | 2         | 0.42%   |
| Dell 2007FP DELA020 1600x1200 367x275mm 18.1-inch                     | 2         | 0.42%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                     | 2         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 2         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 2         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 2         | 0.42%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch      | 2         | 0.42%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch      | 2         | 0.42%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 0.42%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 2         | 0.42%   |
| BenQ ZOWIE XL LCD BNQ7F33 1920x1080 531x298mm 24.0-inch               | 2         | 0.42%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 2         | 0.42%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 0.42%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch         | 2         | 0.42%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 2         | 0.42%   |
| Apple LED Cinema APP9236 1920x1200 518x324mm 24.1-inch                | 2         | 0.42%   |
| Acer KA270H ACR0522 1920x1080 598x336mm 27.0-inch                     | 2         | 0.42%   |
| Acer K222HQL ACR040D 1920x1080 477x268mm 21.5-inch                    | 2         | 0.42%   |
| Unknown                                                               | 2         | 0.42%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch             | 1         | 0.21%   |
| ViewSonic VX2776-4K-mhd VSC7137 3840x2160 608x355mm 27.7-inch         | 1         | 0.21%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 1         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 192       | 43.74%  |
| 1366x768 (WXGA)    | 82        | 18.68%  |
| 3840x2160 (4K)     | 25        | 5.69%   |
| 2560x1440 (QHD)    | 19        | 4.33%   |
| 1600x900 (HD+)     | 18        | 4.1%    |
| 1440x900 (WXGA+)   | 14        | 3.19%   |
| 1920x1200 (WUXGA)  | 13        | 2.96%   |
| 1280x800 (WXGA)    | 12        | 2.73%   |
| 1280x1024 (SXGA)   | 11        | 2.51%   |
| 3440x1440          | 7         | 1.59%   |
| 1360x768           | 7         | 1.59%   |
| Unknown            | 7         | 1.59%   |
| 1680x1050 (WSXGA+) | 6         | 1.37%   |
| 3840x2400          | 3         | 0.68%   |
| 3840x1080          | 3         | 0.68%   |
| 1600x1200          | 3         | 0.68%   |
| 1024x600           | 3         | 0.68%   |
| 3200x1800 (QHD+)   | 2         | 0.46%   |
| 2560x1600          | 2         | 0.46%   |
| 1024x768 (XGA)     | 2         | 0.46%   |
| 6400x2160          | 1         | 0.23%   |
| 5280x2560          | 1         | 0.23%   |
| 4480x1440          | 1         | 0.23%   |
| 3600x1080          | 1         | 0.23%   |
| 3456x2160          | 1         | 0.23%   |
| 2560x1080          | 1         | 0.23%   |
| 2160x1440          | 1         | 0.23%   |
| 1920x540           | 1         | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 120       | 26.49%  |
| 14      | 45        | 9.93%   |
| 27      | 43        | 9.49%   |
| 13      | 36        | 7.95%   |
| 24      | 31        | 6.84%   |
| 23      | 27        | 5.96%   |
| 21      | 24        | 5.3%    |
| Unknown | 24        | 5.3%    |
| 17      | 20        | 4.42%   |
| 12      | 12        | 2.65%   |
| 19      | 11        | 2.43%   |
| 31      | 9         | 1.99%   |
| 18      | 8         | 1.77%   |
| 34      | 7         | 1.55%   |
| 20      | 5         | 1.1%    |
| 84      | 4         | 0.88%   |
| 72      | 4         | 0.88%   |
| 32      | 4         | 0.88%   |
| 11      | 4         | 0.88%   |
| 25      | 3         | 0.66%   |
| 22      | 3         | 0.66%   |
| 10      | 3         | 0.66%   |
| 40      | 2         | 0.44%   |
| 49      | 1         | 0.22%   |
| 46      | 1         | 0.22%   |
| 35      | 1         | 0.22%   |
| 29      | 1         | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 177       | 39.78%  |
| 501-600     | 91        | 20.45%  |
| 401-500     | 47        | 10.56%  |
| 201-300     | 43        | 9.66%   |
| Unknown     | 24        | 5.39%   |
| 351-400     | 23        | 5.17%   |
| 601-700     | 16        | 3.6%    |
| 701-800     | 11        | 2.47%   |
| 1501-2000   | 8         | 1.8%    |
| 801-900     | 3         | 0.67%   |
| 1001-1500   | 2         | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 310       | 76.73%  |
| 16/10   | 47        | 11.63%  |
| Unknown | 19        | 4.7%    |
| 5/4     | 11        | 2.72%   |
| 21/9    | 8         | 1.98%   |
| 4/3     | 5         | 1.24%   |
| 3/2     | 3         | 0.74%   |
| 32/9    | 1         | 0.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 119       | 26.15%  |
| 201-250        | 67        | 14.73%  |
| 81-90          | 60        | 13.19%  |
| 301-350        | 43        | 9.45%   |
| 151-200        | 24        | 5.27%   |
| Unknown        | 24        | 5.27%   |
| 71-80          | 22        | 4.84%   |
| 351-500        | 22        | 4.84%   |
| 251-300        | 16        | 3.52%   |
| 141-150        | 13        | 2.86%   |
| 61-70          | 11        | 2.42%   |
| 121-130        | 11        | 2.42%   |
| More than 1000 | 8         | 1.76%   |
| 51-60          | 4         | 0.88%   |
| 501-1000       | 4         | 0.88%   |
| 41-50          | 3         | 0.66%   |
| 131-140        | 3         | 0.66%   |
| 111-120        | 1         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 130       | 29.55%  |
| 121-160       | 120       | 27.27%  |
| 101-120       | 117       | 26.59%  |
| 161-240       | 27        | 6.14%   |
| Unknown       | 24        | 5.45%   |
| More than 240 | 11        | 2.5%    |
| 1-50          | 11        | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 338       | 77.35%  |
| 2     | 71        | 16.25%  |
| 0     | 20        | 4.58%   |
| 3     | 7         | 1.6%    |
| 4     | 1         | 0.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 229       | 34.7%   |
| Realtek Semiconductor             | 200       | 30.3%   |
| Qualcomm Atheros                  | 65        | 9.85%   |
| Broadcom                          | 49        | 7.42%   |
| Ralink Technology                 | 13        | 1.97%   |
| Broadcom Limited                  | 12        | 1.82%   |
| Nvidia                            | 11        | 1.67%   |
| Ralink                            | 10        | 1.52%   |
| Marvell Technology Group          | 9         | 1.36%   |
| TP-Link                           | 8         | 1.21%   |
| Microsoft                         | 5         | 0.76%   |
| Ericsson Business Mobile Networks | 5         | 0.76%   |
| Samsung Electronics               | 4         | 0.61%   |
| Lenovo                            | 4         | 0.61%   |
| MediaTek                          | 3         | 0.45%   |
| NetGear                           | 2         | 0.3%    |
| ICS Advent                        | 2         | 0.3%    |
| DisplayLink                       | 2         | 0.3%    |
| Belkin Components                 | 2         | 0.3%    |
| Xilinx                            | 1         | 0.15%   |
| Xiaomi                            | 1         | 0.15%   |
| Van Ooijen Technische Informatica | 1         | 0.15%   |
| ULi Electronics                   | 1         | 0.15%   |
| Toshiba                           | 1         | 0.15%   |
| T & A Mobile Phones               | 1         | 0.15%   |
| Qualcomm Atheros Communications   | 1         | 0.15%   |
| Qualcomm                          | 1         | 0.15%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.15%   |
| NetXen Incorporated               | 1         | 0.15%   |
| Microchip Technology              | 1         | 0.15%   |
| LSI                               | 1         | 0.15%   |
| LG Electronics                    | 1         | 0.15%   |
| JMicron Technology                | 1         | 0.15%   |
| IMC Networks                      | 1         | 0.15%   |
| Huawei Technologies               | 1         | 0.15%   |
| HMD Global                        | 1         | 0.15%   |
| Hewlett-Packard                   | 1         | 0.15%   |
| Dell                              | 1         | 0.15%   |
| Bose                              | 1         | 0.15%   |
| ASUSTek Computer                  | 1         | 0.15%   |
| ASIX Electronics                  | 1         | 0.15%   |
| Apple                             | 1         | 0.15%   |
| ADMtek                            | 1         | 0.15%   |
| 3Com                              | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 134       | 17.01%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 34        | 4.31%   |
| Intel Wi-Fi 6 AX200                                               | 28        | 3.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 3.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 15        | 1.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 1.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13        | 1.65%   |
| Intel Wireless 8265 / 8275                                        | 13        | 1.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 1.4%    |
| Intel Wireless 7260                                               | 11        | 1.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 1.27%   |
| Realtek 802.11ac NIC                                              | 10        | 1.27%   |
| Intel I211 Gigabit Network Connection                             | 10        | 1.27%   |
| Intel Wireless-AC 9260                                            | 9         | 1.14%   |
| Intel Wireless 7265                                               | 9         | 1.14%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 9         | 1.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 1.02%   |
| Intel Wireless 8260                                               | 8         | 1.02%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 1.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 0.89%   |
| Ralink MT7601U Wireless Adapter                                   | 6         | 0.76%   |
| Nvidia MCP79 Ethernet                                             | 6         | 0.76%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 0.76%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 0.76%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 0.63%   |
| Microsoft Xbox 360 Wireless Adapter                               | 5         | 0.63%   |
| Intel Wireless 3165                                               | 5         | 0.63%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 0.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 0.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 0.63%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 5         | 0.63%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 5         | 0.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.51%   |
| Ralink RT5370 Wireless Adapter                                    | 4         | 0.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 0.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 0.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 0.51%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 0.51%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.51%   |
| TP-Link 802.11ac WLAN Adapter                                     | 3         | 0.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.38%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.38%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 3         | 0.38%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 3         | 0.38%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 3         | 0.38%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.38%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 3         | 0.38%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 0.38%   |
| Intel Wireless 3160                                               | 3         | 0.38%   |
| Intel WiFi Link 5100                                              | 3         | 0.38%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.38%   |
| Intel Ethernet Controller I225-V                                  | 3         | 0.38%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.38%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.38%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.38%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 174       | 46.65%  |
| Qualcomm Atheros                | 57        | 15.28%  |
| Realtek Semiconductor           | 53        | 14.21%  |
| Broadcom                        | 35        | 9.38%   |
| Ralink Technology               | 13        | 3.49%   |
| Ralink                          | 10        | 2.68%   |
| TP-Link                         | 8         | 2.14%   |
| Microsoft                       | 5         | 1.34%   |
| Broadcom Limited                | 4         | 1.07%   |
| MediaTek                        | 3         | 0.8%    |
| NetGear                         | 2         | 0.54%   |
| Belkin Components               | 2         | 0.54%   |
| Qualcomm Atheros Communications | 1         | 0.27%   |
| Qualcomm                        | 1         | 0.27%   |
| LG Electronics                  | 1         | 0.27%   |
| IMC Networks                    | 1         | 0.27%   |
| Dell                            | 1         | 0.27%   |
| ASUSTek Computer                | 1         | 0.27%   |
| Apple                           | 1         | 0.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 28        | 7.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 3.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 3.71%   |
| Intel Wireless 8265 / 8275                                              | 13        | 3.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 2.92%   |
| Intel Wireless 7260                                                     | 11        | 2.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 2.65%   |
| Realtek 802.11ac NIC                                                    | 10        | 2.65%   |
| Intel Wireless-AC 9260                                                  | 9         | 2.39%   |
| Intel Wireless 7265                                                     | 9         | 2.39%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 2.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 2.12%   |
| Intel Wireless 8260                                                     | 8         | 2.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 1.86%   |
| Ralink MT7601U Wireless Adapter                                         | 6         | 1.59%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 1.59%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 1.59%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 1.33%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 5         | 1.33%   |
| Intel Wireless 3165                                                     | 5         | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.33%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 5         | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.06%   |
| Ralink RT5370 Wireless Adapter                                          | 4         | 1.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 1.06%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.06%   |
| Intel Centrino Ultimate-N 6300                                          | 4         | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.06%   |
| TP-Link 802.11ac WLAN Adapter                                           | 3         | 0.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.8%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.8%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 3         | 0.8%    |
| Ralink RT2561/RT61 802.11g PCI                                          | 3         | 0.8%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 3         | 0.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.8%    |
| Intel Wireless 3160                                                     | 3         | 0.8%    |
| Intel WiFi Link 5100                                                    | 3         | 0.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.8%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 3         | 0.8%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 0.8%    |
| Broadcom BCM4311 802.11b/g WLAN                                         | 3         | 0.8%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 0.53%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 0.53%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 2         | 0.53%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 2         | 0.53%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.53%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.53%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.53%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.53%   |
| NetGear A6210                                                           | 2         | 0.53%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.53%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.53%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.53%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.53%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 2         | 0.53%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.53%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 177       | 45.27%  |
| Intel                         | 125       | 31.97%  |
| Broadcom                      | 20        | 5.12%   |
| Qualcomm Atheros              | 15        | 3.84%   |
| Nvidia                        | 11        | 2.81%   |
| Marvell Technology Group      | 9         | 2.3%    |
| Broadcom Limited              | 9         | 2.3%    |
| Samsung Electronics           | 4         | 1.02%   |
| Lenovo                        | 4         | 1.02%   |
| ICS Advent                    | 2         | 0.51%   |
| DisplayLink                   | 2         | 0.51%   |
| Xilinx                        | 1         | 0.26%   |
| Xiaomi                        | 1         | 0.26%   |
| ULi Electronics               | 1         | 0.26%   |
| T & A Mobile Phones           | 1         | 0.26%   |
| OnePlus Technology (Shenzhen) | 1         | 0.26%   |
| NetXen Incorporated           | 1         | 0.26%   |
| Microchip Technology          | 1         | 0.26%   |
| JMicron Technology            | 1         | 0.26%   |
| Huawei Technologies           | 1         | 0.26%   |
| HMD Global                    | 1         | 0.26%   |
| ASIX Electronics              | 1         | 0.26%   |
| ADMtek                        | 1         | 0.26%   |
| 3Com                          | 1         | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 134       | 33.58%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 34        | 8.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 6.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13        | 3.26%   |
| Intel I211 Gigabit Network Connection                             | 10        | 2.51%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 2.01%   |
| Nvidia MCP79 Ethernet                                             | 6         | 1.5%    |
| Intel Ethernet Connection I218-LM                                 | 6         | 1.5%    |
| Intel Ethernet Connection (4) I219-V                              | 5         | 1.25%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 5         | 1.25%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 1%      |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 3         | 0.75%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 0.75%   |
| Intel Ethernet Controller I225-V                                  | 3         | 0.75%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.75%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.75%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.75%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.75%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.75%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 0.75%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.5%    |
| Nvidia MCP51 Ethernet Controller                                  | 2         | 0.5%    |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 2         | 0.5%    |
| Intel I210 Gigabit Network Connection                             | 2         | 0.5%    |
| Intel Ethernet Connection I219-V                                  | 2         | 0.5%    |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.5%    |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.5%    |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.5%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.5%    |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.5%    |
| Intel Ethernet Connection (13) I219-LM                            | 2         | 0.5%    |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.5%    |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.5%    |
| Intel 82583V Gigabit Network Connection                           | 2         | 0.5%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.5%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2         | 0.5%    |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 2         | 0.5%    |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.5%    |
| Xilinx Ethernet controller                                        | 1         | 0.25%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.25%   |
| ULi ULi 1689,1573 integrated ethernet.                            | 1         | 0.25%   |
| T & A Mobile Phones QM215-QRD _SN:6B7D8716                        | 1         | 0.25%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.25%   |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1         | 0.25%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.25%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.25%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.25%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.25%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 369       | 50.48%  |
| WiFi     | 350       | 47.88%  |
| Modem    | 12        | 1.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 259       | 58.33%  |
| Ethernet | 185       | 41.67%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 248       | 57.94%  |
| 1     | 159       | 37.15%  |
| 3     | 10        | 2.34%   |
| 0     | 9         | 2.1%    |
| 6     | 1         | 0.23%   |
| 4     | 1         | 0.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 392       | 91.38%  |
| Yes  | 37        | 8.62%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 133       | 48.9%   |
| Broadcom                        | 22        | 8.09%   |
| Realtek Semiconductor           | 20        | 7.35%   |
| Cambridge Silicon Radio         | 20        | 7.35%   |
| Qualcomm Atheros Communications | 14        | 5.15%   |
| IMC Networks                    | 14        | 5.15%   |
| Apple                           | 13        | 4.78%   |
| Lite-On Technology              | 10        | 3.68%   |
| Dell                            | 7         | 2.57%   |
| Hewlett-Packard                 | 5         | 1.84%   |
| ASUSTek Computer                | 4         | 1.47%   |
| Toshiba                         | 2         | 0.74%   |
| Realtek                         | 2         | 0.74%   |
| Ralink                          | 1         | 0.37%   |
| Foxconn International           | 1         | 0.37%   |
| Foxconn / Hon Hai               | 1         | 0.37%   |
| Edimax Technology               | 1         | 0.37%   |
| Conwise Technology              | 1         | 0.37%   |
| Belkin Components               | 1         | 0.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 55        | 20.15%  |
| Intel AX200 Bluetooth                                       | 27        | 9.89%   |
| Intel AX201 Bluetooth                                       | 21        | 7.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 20        | 7.33%   |
| Realtek Bluetooth Radio                                     | 12        | 4.4%    |
| Intel Bluetooth Device                                      | 11        | 4.03%   |
| Qualcomm Atheros  Bluetooth Device                          | 10        | 3.66%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 10        | 3.66%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 6         | 2.2%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 6         | 2.2%    |
| Realtek  Bluetooth 4.2 Adapter                              | 5         | 1.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 5         | 1.83%   |
| IMC Networks Bluetooth Radio                                | 5         | 1.83%   |
| IMC Networks Bluetooth Device                               | 5         | 1.83%   |
| Apple Bluetooth Host Controller                             | 5         | 1.83%   |
| Intel Wireless-AC 3168 Bluetooth                            | 4         | 1.47%   |
| Intel AX210 Bluetooth                                       | 4         | 1.47%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 4         | 1.47%   |
| Apple Bluetooth USB Host Controller                         | 4         | 1.47%   |
| Realtek RTL8821A Bluetooth                                  | 3         | 1.1%    |
| HP Broadcom 2070 Bluetooth Combo                            | 3         | 1.1%    |
| Apple Bluetooth HCI                                         | 3         | 1.1%    |
| Realtek Bluetooth Radio                                     | 2         | 0.73%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 0.73%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 0.73%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 0.73%   |
| IMC Networks Wireless_Device                                | 2         | 0.73%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 0.73%   |
| Dell Wireless 355 Bluetooth                                 | 2         | 0.73%   |
| Dell DW375 Bluetooth Module                                 | 2         | 0.73%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 2         | 0.73%   |
| Toshiba Bluetooth Device                                    | 1         | 0.37%   |
| Toshiba BCM43142A0                                          | 1         | 0.37%   |
| Ralink RT3290 Bluetooth                                     | 1         | 0.37%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 0.37%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 0.37%   |
| Lite-On Wireless_Device                                     | 1         | 0.37%   |
| Lite-On BCM43142A0                                          | 1         | 0.37%   |
| Lite-On Atheros Bluetooth                                   | 1         | 0.37%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.37%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.37%   |
| Foxconn International BCM43142A0 Bluetooth module           | 1         | 0.37%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth               | 1         | 0.37%   |
| Edimax Wi-Fi N150 Bluetooth4.0 USB Adapter                  | 1         | 0.37%   |
| Dell Wireless 365 Bluetooth                                 | 1         | 0.37%   |
| Dell Wireless 350 Bluetooth                                 | 1         | 0.37%   |
| Dell BT Mini-Receiver                                       | 1         | 0.37%   |
| Conwise CW6622                                              | 1         | 0.37%   |
| Broadcom Bluetooth Device                                   | 1         | 0.37%   |
| Broadcom BCM92045B3 ROM                                     | 1         | 0.37%   |
| Broadcom BCM43142A0 Bluetooth Device                        | 1         | 0.37%   |
| Broadcom BCM2070 Bluetooth Device                           | 1         | 0.37%   |
| Belkin Components F8T012 Bluetooth Adapter                  | 1         | 0.37%   |
| ASUS Qualcomm Bluetooth 4.1                                 | 1         | 0.37%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1         | 0.37%   |
| ASUS Bluetooth Device                                       | 1         | 0.37%   |
| ASUS BCM20702A0                                             | 1         | 0.37%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 306       | 51.52%  |
| AMD                                             | 125       | 21.04%  |
| Nvidia                                          | 105       | 17.68%  |
| C-Media Electronics                             | 6         | 1.01%   |
| Creative Technology                             | 5         | 0.84%   |
| Creative Labs                                   | 4         | 0.67%   |
| Plantronics                                     | 3         | 0.51%   |
| Logitech                                        | 3         | 0.51%   |
| Lenovo                                          | 3         | 0.51%   |
| GN Netcom                                       | 3         | 0.51%   |
| Texas Instruments                               | 2         | 0.34%   |
| Realtek Semiconductor                           | 2         | 0.34%   |
| JMTek                                           | 2         | 0.34%   |
| Ensoniq                                         | 2         | 0.34%   |
| VIA Technologies                                | 1         | 0.17%   |
| ULi Electronics                                 | 1         | 0.17%   |
| Turtle Beach                                    | 1         | 0.17%   |
| Thesycon Systemsoftware & Consulting            | 1         | 0.17%   |
| Sony                                            | 1         | 0.17%   |
| SAVITECH                                        | 1         | 0.17%   |
| RODE Microphones                                | 1         | 0.17%   |
| Razer USA                                       | 1         | 0.17%   |
| Native Instruments                              | 1         | 0.17%   |
| Micronas                                        | 1         | 0.17%   |
| M-Audio                                         | 1         | 0.17%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.17%   |
| Kingston Technology                             | 1         | 0.17%   |
| Giga-Byte Technology                            | 1         | 0.17%   |
| Focusrite-Novation                              | 1         | 0.17%   |
| FiiO Electronics Technology                     | 1         | 0.17%   |
| ESS Technology                                  | 1         | 0.17%   |
| Corsair                                         | 1         | 0.17%   |
| Blue Microphones                                | 1         | 0.17%   |
| AudioQuest                                      | 1         | 0.17%   |
| AUDIOLAB                                        | 1         | 0.17%   |
| Audio-Technica                                  | 1         | 0.17%   |
| Audient                                         | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 39        | 5.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 37        | 5.32%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 36        | 5.17%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 28        | 4.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 19        | 2.73%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 17        | 2.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15        | 2.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 2.16%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 15        | 2.16%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 14        | 2.01%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 14        | 2.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 1.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 1.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 12        | 1.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 1.58%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 11        | 1.58%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 1.44%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 1.44%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 1.44%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 1.44%   |
| AMD FCH Azalia Controller                                                                         | 10        | 1.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 10        | 1.44%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 9         | 1.29%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 9         | 1.29%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 8         | 1.15%   |
| Intel Comet Lake PCH cAVS                                                                         | 8         | 1.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 1.15%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 1.15%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 1.15%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 8         | 1.15%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 7         | 1.01%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 7         | 1.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 1.01%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 1.01%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 7         | 1.01%   |
| Nvidia MCP79 High Definition Audio                                                                | 6         | 0.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6         | 0.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 0.86%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 0.86%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 0.86%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 0.72%   |
| Intel CM238 HD Audio Controller                                                                   | 5         | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 0.72%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 5         | 0.72%   |
| AMD High Definition Audio Controller                                                              | 5         | 0.72%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 4         | 0.57%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 0.57%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.57%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 4         | 0.57%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.43%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.43%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 0.43%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 0.43%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 3         | 0.43%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.43%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 0.43%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.43%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 3         | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 51        | 20.08%  |
| SK hynix            | 38        | 14.96%  |
| Unknown             | 29        | 11.42%  |
| Crucial             | 27        | 10.63%  |
| Corsair             | 25        | 9.84%   |
| Micron Technology   | 24        | 9.45%   |
| Kingston            | 19        | 7.48%   |
| Ramaxel Technology  | 7         | 2.76%   |
| G.Skill             | 7         | 2.76%   |
| Elpida              | 5         | 1.97%   |
| Unknown (ABCD)      | 3         | 1.18%   |
| Team                | 3         | 1.18%   |
| Patriot             | 3         | 1.18%   |
| Nanya Technology    | 3         | 1.18%   |
| Apacer              | 2         | 0.79%   |
| Transcend           | 1         | 0.39%   |
| Toshiba             | 1         | 0.39%   |
| SHARETRONIC         | 1         | 0.39%   |
| OSV                 | 1         | 0.39%   |
| Infineon            | 1         | 0.39%   |
| CSX                 | 1         | 0.39%   |
| A-DATA Technology   | 1         | 0.39%   |
| A Force             | 1         | 0.39%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 5         | 1.83%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 5         | 1.83%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 1.47%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 1.1%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.1%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.1%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 3         | 1.1%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s            | 3         | 1.1%    |
| Corsair RAM CM4X16GE2666C18S4 16384MB SODIMM DDR4 2667MT/s       | 3         | 1.1%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 0.73%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 2         | 0.73%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 2         | 0.73%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 2         | 0.73%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 2         | 0.73%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                       | 2         | 0.73%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 2         | 0.73%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.73%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s          | 2         | 0.73%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.73%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.73%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.73%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.73%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.73%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 2         | 0.73%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 0.73%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 2         | 0.73%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.73%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.73%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 0.73%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s             | 2         | 0.73%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 0.73%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 2         | 0.73%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s             | 2         | 0.73%   |
| Elpida RAM EBJ41UF8BDU0-DJ-F 2048MB Chip DDR3 1333MT/s           | 2         | 0.73%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s            | 2         | 0.73%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s       | 2         | 0.73%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s            | 2         | 0.73%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.37%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.37%   |
| Unknown RAM Module 8192MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.37%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                     | 1         | 0.37%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                          | 1         | 0.37%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1867MT/s                    | 1         | 0.37%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                      | 1         | 0.37%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                             | 1         | 0.37%   |
| Unknown RAM Module 4096MB SODIMM 800MT/s                         | 1         | 0.37%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.37%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s                     | 1         | 0.37%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 0.37%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 1         | 0.37%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 0.37%   |
| Unknown RAM Module 256MB SODIMM DRAM                             | 1         | 0.37%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                    | 1         | 0.37%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.37%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 0.37%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                     | 1         | 0.37%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                           | 1         | 0.37%   |
| Unknown RAM Module 2048MB DIMM                                   | 1         | 0.37%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.37%   |
| Unknown RAM Module 1GB DIMM 667MT/s                              | 1         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 96        | 42.29%  |
| DDR3    | 73        | 32.16%  |
| Unknown | 13        | 5.73%   |
| DDR2    | 12        | 5.29%   |
| LPDDR4  | 11        | 4.85%   |
| SDRAM   | 10        | 4.41%   |
| LPDDR3  | 7         | 3.08%   |
| DDR     | 3         | 1.32%   |
| DRAM    | 2         | 0.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 124       | 55.11%  |
| DIMM         | 78        | 34.67%  |
| Row Of Chips | 17        | 7.56%   |
| Chip         | 4         | 1.78%   |
| Unknown      | 2         | 0.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 83        | 34.3%   |
| 4096  | 70        | 28.93%  |
| 2048  | 35        | 14.46%  |
| 16384 | 33        | 13.64%  |
| 1024  | 10        | 4.13%   |
| 32768 | 7         | 2.89%   |
| 128   | 2         | 0.83%   |
| 512   | 1         | 0.41%   |
| 256   | 1         | 0.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 48        | 19.43%  |
| 2667    | 33        | 13.36%  |
| 3200    | 22        | 8.91%   |
| 2400    | 19        | 7.69%   |
| 2133    | 17        | 6.88%   |
| 1333    | 13        | 5.26%   |
| 800     | 12        | 4.86%   |
| 667     | 9         | 3.64%   |
| 1334    | 8         | 3.24%   |
| 4267    | 7         | 2.83%   |
| 3600    | 7         | 2.83%   |
| 3266    | 6         | 2.43%   |
| 1867    | 6         | 2.43%   |
| Unknown | 5         | 2.02%   |
| 1067    | 4         | 1.62%   |
| 3466    | 3         | 1.21%   |
| 1800    | 3         | 1.21%   |
| 8400    | 2         | 0.81%   |
| 4800    | 2         | 0.81%   |
| 4199    | 2         | 0.81%   |
| 3400    | 2         | 0.81%   |
| 1866    | 2         | 0.81%   |
| 1066    | 2         | 0.81%   |
| 975     | 2         | 0.81%   |
| 533     | 2         | 0.81%   |
| 3800    | 1         | 0.4%    |
| 3733    | 1         | 0.4%    |
| 3000    | 1         | 0.4%    |
| 2933    | 1         | 0.4%    |
| 2733    | 1         | 0.4%    |
| 2666    | 1         | 0.4%    |
| 2267    | 1         | 0.4%    |
| 2048    | 1         | 0.4%    |
| 400     | 1         | 0.4%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 2         | 40%     |
| STMicroelectronics  | 1         | 20%     |
| Samsung Electronics | 1         | 20%     |
| Canon               | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 62        | 23.85%  |
| Realtek Semiconductor                  | 32        | 12.31%  |
| Acer                                   | 23        | 8.85%   |
| IMC Networks                           | 22        | 8.46%   |
| Microdia                               | 21        | 8.08%   |
| Logitech                               | 16        | 6.15%   |
| Apple                                  | 11        | 4.23%   |
| Quanta                                 | 9         | 3.46%   |
| Sunplus Innovation Technology          | 8         | 3.08%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 2.69%   |
| Suyin                                  | 6         | 2.31%   |
| Samsung Electronics                    | 5         | 1.92%   |
| ALi                                    | 5         | 1.92%   |
| Syntek                                 | 4         | 1.54%   |
| Microsoft                              | 4         | 1.54%   |
| Silicon Motion                         | 3         | 1.15%   |
| Ricoh                                  | 3         | 1.15%   |
| Lite-On Technology                     | 2         | 0.77%   |
| Generalplus Technology                 | 2         | 0.77%   |
| Creative Technology                    | 2         | 0.77%   |
| Z-Star Microelectronics                | 1         | 0.38%   |
| Y Media                                | 1         | 0.38%   |
| USB3.0 HD Audio Capture                | 1         | 0.38%   |
| Unknown                                | 1         | 0.38%   |
| Trust                                  | 1         | 0.38%   |
| SunplusIT                              | 1         | 0.38%   |
| Razer USA                              | 1         | 0.38%   |
| Nikon                                  | 1         | 0.38%   |
| Lenovo                                 | 1         | 0.38%   |
| GenesysLogic Technology                | 1         | 0.38%   |
| GEMBIRD                                | 1         | 0.38%   |
| DigiTech                               | 1         | 0.38%   |
| Alcor Micro                            | 1         | 0.38%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                     | 13        | 4.94%   |
| Microdia Integrated_Webcam_HD                    | 10        | 3.8%    |
| Chicony Integrated Camera                        | 10        | 3.8%    |
| Apple Built-in iSight                            | 8         | 3.04%   |
| IMC Networks Integrated Camera                   | 7         | 2.66%   |
| Chicony USB2.0 Camera                            | 7         | 2.66%   |
| Chicony HD Webcam                                | 7         | 2.66%   |
| Acer Integrated Camera                           | 7         | 2.66%   |
| Samsung Galaxy A5 (MTP)                          | 5         | 1.9%    |
| Logitech HD Pro Webcam C920                      | 5         | 1.9%    |
| Microdia Integrated Webcam                       | 4         | 1.52%   |
| IMC Networks USB2.0 HD UVC WebCam                | 4         | 1.52%   |
| Acer EasyCamera                                  | 4         | 1.52%   |
| Realtek Integrated Webcam HD                     | 3         | 1.14%   |
| Microsoft LifeCam HD-3000                        | 3         | 1.14%   |
| Logitech Webcam C270                             | 3         | 1.14%   |
| Chicony USB2.0 HD UVC WebCam                     | 3         | 1.14%   |
| Chicony Lenovo EasyCamera                        | 3         | 1.14%   |
| Chicony EasyCamera                               | 3         | 1.14%   |
| ALi WebCam                                       | 3         | 1.14%   |
| Acer BisonCam, NB Pro                            | 3         | 1.14%   |
| Syntek Integrated Camera                         | 2         | 0.76%   |
| Syntek EasyCamera                                | 2         | 0.76%   |
| Suyin HP Truevision HD                           | 2         | 0.76%   |
| Sunplus Integrated_Webcam_HD                     | 2         | 0.76%   |
| Realtek USB2.0 HD UVC WebCam                     | 2         | 0.76%   |
| Realtek HP Truevision HD integrated webcam       | 2         | 0.76%   |
| Realtek HD WebCam                                | 2         | 0.76%   |
| Realtek EasyCamera                               | 2         | 0.76%   |
| Quanta HP Wide Vision HD Camera                  | 2         | 0.76%   |
| Quanta HP Webcam                                 | 2         | 0.76%   |
| Logitech C922 Pro Stream Webcam                  | 2         | 0.76%   |
| Logitech B525 HD Webcam                          | 2         | 0.76%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 2         | 0.76%   |
| IMC Networks TOSHIBA Web Camera - HD             | 2         | 0.76%   |
| IMC Networks EasyCamera                          | 2         | 0.76%   |
| Creative Live! Cam Sync HD [VF0770]              | 2         | 0.76%   |
| Chicony thinkpad t430s camera                    | 2         | 0.76%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 2         | 0.76%   |
| Chicony Integrated Camera (1280x720@30)          | 2         | 0.76%   |
| Chicony HP Wide Vision HD Camera                 | 2         | 0.76%   |
| Chicony HP TrueVision HD Camera                  | 2         | 0.76%   |
| Chicony HP Truevision HD                         | 2         | 0.76%   |
| Chicony CNF9055 Toshiba Webcam                   | 2         | 0.76%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 0.76%   |
| Apple iPhone 5/5C/5S/6/SE                        | 2         | 0.76%   |
| ALi Gateway Webcam                               | 2         | 0.76%   |
| Acer Lenovo EasyCamera                           | 2         | 0.76%   |
| Acer BisonCam,NB Pro                             | 2         | 0.76%   |
| Z-Star Webcam                                    | 1         | 0.38%   |
| Y Media USB Camera                               | 1         | 0.38%   |
| USB3.0 HD Audio Capture USB3.0 HD Video Capture  | 1         | 0.38%   |
| Unknown 720p HD Camera                           | 1         | 0.38%   |
| Trust USB Camera                                 | 1         | 0.38%   |
| Suyin VGA Webcam                                 | 1         | 0.38%   |
| Suyin HD Video WebCam                            | 1         | 0.38%   |
| Suyin Acer CrystalEye Webcam                     | 1         | 0.38%   |
| Suyin 1.3M HD WebCam                             | 1         | 0.38%   |
| SunplusIT MTD camera                             | 1         | 0.38%   |
| Sunplus Laptop_Integrated_Webcam_FHD             | 1         | 0.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 19        | 31.67%  |
| Validity Sensors           | 18        | 30%     |
| Shenzhen Goodix Technology | 11        | 18.33%  |
| Upek                       | 4         | 6.67%   |
| LighTuning Technology      | 2         | 3.33%   |
| Elan Microelectronics      | 2         | 3.33%   |
| AuthenTec                  | 2         | 3.33%   |
| STMicroelectronics         | 1         | 1.67%   |
| Focal-systems.Corp         | 1         | 1.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown                                                    | 9         | 15%     |
| Shenzhen Goodix FingerPrint                                | 6         | 10%     |
| Validity Sensors VFS495 Fingerprint Reader                 | 4         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 6.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 5%      |
| Shenzhen Goodix  FingerPrint Device                        | 3         | 5%      |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 3.33%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 2         | 3.33%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 2         | 3.33%   |
| Validity Sensors Synaptics WBDI                            | 2         | 3.33%   |
| Synaptics  WBDI                                            | 2         | 3.33%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 2         | 3.33%   |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 3.33%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 2         | 3.33%   |
| Elan ELAN:Fingerprint                                      | 2         | 3.33%   |
| AuthenTec Fingerprint Sensor                               | 2         | 3.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 1.67%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 1.67%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 1.67%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 1.67%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 1.67%   |
| Validity Sensors Fingerprint scanner                       | 1         | 1.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 1.67%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 1.67%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 1.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 16        | 48.48%  |
| Alcor Micro | 7         | 21.21%  |
| Upek        | 5         | 15.15%  |
| O2 Micro    | 4         | 12.12%  |
| Lenovo      | 1         | 3.03%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 21.21%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 15.15%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 15.15%  |
| Broadcom 58200                                                               | 5         | 15.15%  |
| Broadcom 5880                                                                | 4         | 12.12%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 6.06%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 3.03%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 3.03%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 282       | 64.68%  |
| 1     | 125       | 28.67%  |
| 2     | 23        | 5.28%   |
| 3     | 6         | 1.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 59        | 33.15%  |
| Net/wireless             | 34        | 19.1%   |
| Graphics card            | 29        | 16.29%  |
| Chipcard                 | 28        | 15.73%  |
| Multimedia controller    | 9         | 5.06%   |
| Communication controller | 5         | 2.81%   |
| Storage                  | 4         | 2.25%   |
| Card reader              | 3         | 1.69%   |
| Camera                   | 3         | 1.69%   |
| Bluetooth                | 2         | 1.12%   |
| Net/ethernet             | 1         | 0.56%   |
| Modem                    | 1         | 0.56%   |

