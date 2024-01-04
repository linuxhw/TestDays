Ubuntu - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Ubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu/Desktop/README.md) and [notebooks](/Dist/Ubuntu/Notebook/README.md).

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

Total: 99962

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | J5005-ITX                   | Desktop     | [5373e7f16c](https://linux-hardware.org/?probe=5373e7f16c) | Jan 02, 2024 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [3a67df5dcf](https://linux-hardware.org/?probe=3a67df5dcf) | Jan 02, 2024 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [b163926938](https://linux-hardware.org/?probe=b163926938) | Jan 02, 2024 |
| ASUSTek       | H81M-C                      | Desktop     | [221ebe85fb](https://linux-hardware.org/?probe=221ebe85fb) | Jan 02, 2024 |
| Notebook      | N13xWU                      | Notebook    | [b88a27e565](https://linux-hardware.org/?probe=b88a27e565) | Jan 02, 2024 |
| Azulle        | Byte 3                      | Desktop     | [28f6b7cbad](https://linux-hardware.org/?probe=28f6b7cbad) | Jan 02, 2024 |
| Lenovo        | ThinkPad L380 Yoga 20M7C... | Convertible | [fa3f52294e](https://linux-hardware.org/?probe=fa3f52294e) | Jan 02, 2024 |
| Google        | Caroline                    | Notebook    | [8b3ec77c48](https://linux-hardware.org/?probe=8b3ec77c48) | Jan 02, 2024 |
| System76      | Serval                      | Notebook    | [a0597a9161](https://linux-hardware.org/?probe=a0597a9161) | Jan 02, 2024 |
| System76      | Serval                      | Notebook    | [c4a91b64e5](https://linux-hardware.org/?probe=c4a91b64e5) | Jan 02, 2024 |
| Gigabyte      | Z490 UD                     | Desktop     | [939fe5ab0c](https://linux-hardware.org/?probe=939fe5ab0c) | Jan 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [a9ddfb0974](https://linux-hardware.org/?probe=a9ddfb0974) | Jan 02, 2024 |
| Dell          | 0XJ8C4 A00                  | Desktop     | [e902f5396d](https://linux-hardware.org/?probe=e902f5396d) | Jan 02, 2024 |
| HP            | ProBook 430 G2              | Notebook    | [c56ad1ad48](https://linux-hardware.org/?probe=c56ad1ad48) | Jan 02, 2024 |
| MSI           | Z77A-G43                    | Desktop     | [b33c14ee42](https://linux-hardware.org/?probe=b33c14ee42) | Jan 02, 2024 |
| Dell          | G3 3590                     | Notebook    | [ae7267dd5f](https://linux-hardware.org/?probe=ae7267dd5f) | Jan 02, 2024 |
| Dell          | 07KY25 A01                  | Desktop     | [7936cb8967](https://linux-hardware.org/?probe=7936cb8967) | Jan 02, 2024 |
| ASUSTek       | M3702WFA                    | All in one  | [878dc1f9b0](https://linux-hardware.org/?probe=878dc1f9b0) | Jan 02, 2024 |
| HP            | Notebook                    | Notebook    | [f6e5af2da0](https://linux-hardware.org/?probe=f6e5af2da0) | Jan 02, 2024 |
| HP            | Pavilion dv3                | Notebook    | [351a45926e](https://linux-hardware.org/?probe=351a45926e) | Jan 02, 2024 |
| Azulle        | Byte 3                      | Desktop     | [273bcd474a](https://linux-hardware.org/?probe=273bcd474a) | Jan 02, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [b822b77797](https://linux-hardware.org/?probe=b822b77797) | Jan 02, 2024 |
| Sony          | VGN-AR51SU                  | Notebook    | [ad09db7b69](https://linux-hardware.org/?probe=ad09db7b69) | Jan 01, 2024 |
| Sony          | VGN-AR51SU                  | Notebook    | [01e1a67d40](https://linux-hardware.org/?probe=01e1a67d40) | Jan 01, 2024 |
| Gigabyte      | Z790 AERO G                 | Desktop     | [121de16d3b](https://linux-hardware.org/?probe=121de16d3b) | Jan 01, 2024 |
| Gigabyte      | Z790 AERO G                 | Desktop     | [2ad2af0de5](https://linux-hardware.org/?probe=2ad2af0de5) | Jan 01, 2024 |
| ASUSTek       | P8H77-M                     | Desktop     | [7ae937132b](https://linux-hardware.org/?probe=7ae937132b) | Jan 01, 2024 |
| MSI           | X79A-GD65                   | Desktop     | [ecb9a57738](https://linux-hardware.org/?probe=ecb9a57738) | Jan 01, 2024 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [4389374c55](https://linux-hardware.org/?probe=4389374c55) | Jan 01, 2024 |
| ASRock        | B450M Gaming                | Desktop     | [81242d3eca](https://linux-hardware.org/?probe=81242d3eca) | Jan 01, 2024 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [a679e6f722](https://linux-hardware.org/?probe=a679e6f722) | Jan 01, 2024 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [c3356daec6](https://linux-hardware.org/?probe=c3356daec6) | Jan 01, 2024 |
| Dell          | Inspiron 5537               | Notebook    | [d19fc7dff7](https://linux-hardware.org/?probe=d19fc7dff7) | Jan 01, 2024 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [82877fbf5e](https://linux-hardware.org/?probe=82877fbf5e) | Jan 01, 2024 |
| HP            | 82A2                        | Desktop     | [7cc3d17916](https://linux-hardware.org/?probe=7cc3d17916) | Jan 01, 2024 |
| ASUSTek       | V241IC-R                    | All in one  | [555f0208db](https://linux-hardware.org/?probe=555f0208db) | Jan 01, 2024 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [d47bc3897f](https://linux-hardware.org/?probe=d47bc3897f) | Jan 01, 2024 |
| Medion        | H110H4-EM                   | Desktop     | [da3367c80e](https://linux-hardware.org/?probe=da3367c80e) | Jan 01, 2024 |
| Acer          | Aspire ES1-523              | Notebook    | [65fb7df562](https://linux-hardware.org/?probe=65fb7df562) | Jan 01, 2024 |
| HP            | EliteBook 850 G4            | Notebook    | [bd25e4866f](https://linux-hardware.org/?probe=bd25e4866f) | Jan 01, 2024 |
| Dell          | 0D24M8 A01                  | Desktop     | [f363c3e115](https://linux-hardware.org/?probe=f363c3e115) | Jan 01, 2024 |
| Acer          | Spin SP314-21N              | Convertible | [a58ed9a59b](https://linux-hardware.org/?probe=a58ed9a59b) | Jan 01, 2024 |
| Google        | Caroline                    | Notebook    | [95fb0e423e](https://linux-hardware.org/?probe=95fb0e423e) | Jan 01, 2024 |
| Lenovo        | SHARKBAY SDK0E50519 WIN     | Desktop     | [fc9ced99d5](https://linux-hardware.org/?probe=fc9ced99d5) | Jan 01, 2024 |
| Lenovo        | Legion Y7000P2020H 82AX     | Notebook    | [59d5eb147b](https://linux-hardware.org/?probe=59d5eb147b) | Jan 01, 2024 |
| Dell          | 09KPNV A01                  | Desktop     | [d6c27424e2](https://linux-hardware.org/?probe=d6c27424e2) | Jan 01, 2024 |
| Packard Be... | EasyNote LJ65               | Notebook    | [52bbda495f](https://linux-hardware.org/?probe=52bbda495f) | Jan 01, 2024 |
| Notebook      | N13xWU                      | Notebook    | [d877ecb7be](https://linux-hardware.org/?probe=d877ecb7be) | Jan 01, 2024 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [a70caacf5a](https://linux-hardware.org/?probe=a70caacf5a) | Jan 01, 2024 |
| Lenovo        | ThinkPad L380 Yoga 20M7C... | Convertible | [7e61024957](https://linux-hardware.org/?probe=7e61024957) | Jan 01, 2024 |
| Centerm       | C92                         | Desktop     | [5ede09f987](https://linux-hardware.org/?probe=5ede09f987) | Jan 01, 2024 |
| Centerm       | C92                         | Desktop     | [0201370bf4](https://linux-hardware.org/?probe=0201370bf4) | Jan 01, 2024 |
| Toshiba       | Satellite A660              | Notebook    | [34dd6e3ec3](https://linux-hardware.org/?probe=34dd6e3ec3) | Jan 01, 2024 |
| Toshiba       | Satellite A660              | Notebook    | [4b00ffd071](https://linux-hardware.org/?probe=4b00ffd071) | Jan 01, 2024 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [cd5e5dff22](https://linux-hardware.org/?probe=cd5e5dff22) | Jan 01, 2024 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [6dbc709464](https://linux-hardware.org/?probe=6dbc709464) | Jan 01, 2024 |
| Dell          | Inspiron 3593               | Notebook    | [a2424d3523](https://linux-hardware.org/?probe=a2424d3523) | Jan 01, 2024 |
| Dell          | Inspiron 7786               | Convertible | [b495c4c522](https://linux-hardware.org/?probe=b495c4c522) | Jan 01, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [1e67ed5915](https://linux-hardware.org/?probe=1e67ed5915) | Jan 01, 2024 |
| Acer          | Aspire ES1-523              | Notebook    | [e270ce7266](https://linux-hardware.org/?probe=e270ce7266) | Jan 01, 2024 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [553c16eb6c](https://linux-hardware.org/?probe=553c16eb6c) | Jan 01, 2024 |
| HP            | ProBook 640 G1              | Notebook    | [a6ba47a6e6](https://linux-hardware.org/?probe=a6ba47a6e6) | Jan 01, 2024 |
| ASRock        | X399 Professional Gaming    | Desktop     | [2d812c76d3](https://linux-hardware.org/?probe=2d812c76d3) | Jan 01, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [126f6b0c9c](https://linux-hardware.org/?probe=126f6b0c9c) | Dec 31, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [8625e5d1fa](https://linux-hardware.org/?probe=8625e5d1fa) | Dec 31, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [3b6183bbb5](https://linux-hardware.org/?probe=3b6183bbb5) | Dec 31, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [ae6e6ab09f](https://linux-hardware.org/?probe=ae6e6ab09f) | Dec 31, 2023 |
| Supermicro    | H13DSH                      | Desktop     | [4110ba22a1](https://linux-hardware.org/?probe=4110ba22a1) | Dec 31, 2023 |
| Dell          | 0HX555                      | Desktop     | [72e32eaf42](https://linux-hardware.org/?probe=72e32eaf42) | Dec 31, 2023 |
| ASUSTek       | UX550VE                     | Notebook    | [90014cac84](https://linux-hardware.org/?probe=90014cac84) | Dec 31, 2023 |
| Dell          | 0HX555                      | Desktop     | [535a5964b8](https://linux-hardware.org/?probe=535a5964b8) | Dec 31, 2023 |
| Gigabyte      | B660 DS3H DDR4              | Desktop     | [3cb3c98a92](https://linux-hardware.org/?probe=3cb3c98a92) | Dec 31, 2023 |
| Supermicro    | X10SL7-F                    | Server      | [5aef85f1c3](https://linux-hardware.org/?probe=5aef85f1c3) | Dec 31, 2023 |
| Google        | Caroline                    | Notebook    | [94a1dd78ec](https://linux-hardware.org/?probe=94a1dd78ec) | Dec 31, 2023 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [b569c39f5a](https://linux-hardware.org/?probe=b569c39f5a) | Dec 31, 2023 |
| Google        | Caroline                    | Notebook    | [0d1ce09fbd](https://linux-hardware.org/?probe=0d1ce09fbd) | Dec 31, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [5dde4deb12](https://linux-hardware.org/?probe=5dde4deb12) | Dec 31, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Notebook    | [ec8f742a7f](https://linux-hardware.org/?probe=ec8f742a7f) | Dec 31, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [bc788ac36f](https://linux-hardware.org/?probe=bc788ac36f) | Dec 31, 2023 |
| Microsoft     | Surface Pro 7+              | Tablet      | [b4c9aa37e6](https://linux-hardware.org/?probe=b4c9aa37e6) | Dec 31, 2023 |
| ASUSTek       | VivoBook E14 E402YA_R417... | Notebook    | [47112e4c46](https://linux-hardware.org/?probe=47112e4c46) | Dec 31, 2023 |
| HP            | Pavilion 17                 | Notebook    | [77a7431f73](https://linux-hardware.org/?probe=77a7431f73) | Dec 31, 2023 |
| Google        | Peppy                       | Notebook    | [9b8131eea3](https://linux-hardware.org/?probe=9b8131eea3) | Dec 31, 2023 |
| Unknown       | Unknown                     | Notebook    | [764c59c56e](https://linux-hardware.org/?probe=764c59c56e) | Dec 31, 2023 |
| ASUSTek       | X450CC                      | Notebook    | [0d985ff465](https://linux-hardware.org/?probe=0d985ff465) | Dec 31, 2023 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [d60c82646d](https://linux-hardware.org/?probe=d60c82646d) | Dec 31, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [9f9b454f97](https://linux-hardware.org/?probe=9f9b454f97) | Dec 31, 2023 |
| HP            | 18E9                        | Desktop     | [298cd92eb1](https://linux-hardware.org/?probe=298cd92eb1) | Dec 31, 2023 |
| Intel         | NUC7JYB M37329-600          | Mini pc     | [7237a0a423](https://linux-hardware.org/?probe=7237a0a423) | Dec 31, 2023 |
| Gigabyte      | GA-MA790GPT-UD3H            | Desktop     | [0ff4f2cb79](https://linux-hardware.org/?probe=0ff4f2cb79) | Dec 31, 2023 |
| ASUSTek       | K53U                        | Notebook    | [84ba38c3c5](https://linux-hardware.org/?probe=84ba38c3c5) | Dec 31, 2023 |
| ZOTAC         | NM10                        | Desktop     | [c0f4135bd0](https://linux-hardware.org/?probe=c0f4135bd0) | Dec 31, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [0c20bdae04](https://linux-hardware.org/?probe=0c20bdae04) | Dec 31, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [a7a54aba38](https://linux-hardware.org/?probe=a7a54aba38) | Dec 31, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [d6622a2c0a](https://linux-hardware.org/?probe=d6622a2c0a) | Dec 31, 2023 |
| AZW           | U57                         | Mini pc     | [857aa7dbae](https://linux-hardware.org/?probe=857aa7dbae) | Dec 31, 2023 |
| MACHINIST     | X99-D8-MAX V1.0             | Desktop     | [ef584ae5a8](https://linux-hardware.org/?probe=ef584ae5a8) | Dec 31, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [53913ce746](https://linux-hardware.org/?probe=53913ce746) | Dec 31, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [fda4d32a86](https://linux-hardware.org/?probe=fda4d32a86) | Dec 31, 2023 |
| Lenovo        | ThinkPad T61 7662CTO        | Notebook    | [d38807fbbe](https://linux-hardware.org/?probe=d38807fbbe) | Dec 31, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [d694f21feb](https://linux-hardware.org/?probe=d694f21feb) | Dec 31, 2023 |
| Dell          | 03X6X0 A06                  | Server      | [37cb3cf7de](https://linux-hardware.org/?probe=37cb3cf7de) | Dec 31, 2023 |
| Lenovo        | ThinkPad P43s 20RHCTO1WW    | Notebook    | [7b1fe348e4](https://linux-hardware.org/?probe=7b1fe348e4) | Dec 31, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [dd7c0e5406](https://linux-hardware.org/?probe=dd7c0e5406) | Dec 31, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [7f113211a4](https://linux-hardware.org/?probe=7f113211a4) | Dec 31, 2023 |
| HP            | 82B4                        | Desktop     | [02bcf6a9d1](https://linux-hardware.org/?probe=02bcf6a9d1) | Dec 31, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [2a12979b75](https://linux-hardware.org/?probe=2a12979b75) | Dec 31, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [23b04c5445](https://linux-hardware.org/?probe=23b04c5445) | Dec 31, 2023 |
| NEC Comput... | PC-VK19SGZDF                | Notebook    | [aa9f420488](https://linux-hardware.org/?probe=aa9f420488) | Dec 31, 2023 |
| HC Technol... | HCAR5000-MI2                | Desktop     | [907ca49963](https://linux-hardware.org/?probe=907ca49963) | Dec 31, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [70057bbd62](https://linux-hardware.org/?probe=70057bbd62) | Dec 31, 2023 |
| Dell          | 0C2XKD A01                  | Desktop     | [5e36d4fb43](https://linux-hardware.org/?probe=5e36d4fb43) | Dec 31, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [275f675ca4](https://linux-hardware.org/?probe=275f675ca4) | Dec 31, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [934f756965](https://linux-hardware.org/?probe=934f756965) | Dec 31, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [59909058f1](https://linux-hardware.org/?probe=59909058f1) | Dec 31, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [76869cc8d4](https://linux-hardware.org/?probe=76869cc8d4) | Dec 31, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [63d62dd94e](https://linux-hardware.org/?probe=63d62dd94e) | Dec 31, 2023 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [0181b68b4a](https://linux-hardware.org/?probe=0181b68b4a) | Dec 31, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [eb25c26beb](https://linux-hardware.org/?probe=eb25c26beb) | Dec 30, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [6a45d6cf9e](https://linux-hardware.org/?probe=6a45d6cf9e) | Dec 30, 2023 |
| Gigabyte      | A620I AX                    | Desktop     | [7f73790fbf](https://linux-hardware.org/?probe=7f73790fbf) | Dec 30, 2023 |
| HP            | Laptop 14s-ef1xxx           | Notebook    | [961d2db618](https://linux-hardware.org/?probe=961d2db618) | Dec 30, 2023 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [af479728a3](https://linux-hardware.org/?probe=af479728a3) | Dec 30, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [1a5d669774](https://linux-hardware.org/?probe=1a5d669774) | Dec 30, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [495efd257e](https://linux-hardware.org/?probe=495efd257e) | Dec 30, 2023 |
| Pine Micro... | Pine64 RockPro64 v2.1       | Soc         | [38ff4c1e6c](https://linux-hardware.org/?probe=38ff4c1e6c) | Dec 30, 2023 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [3607077350](https://linux-hardware.org/?probe=3607077350) | Dec 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [e6e8bd6545](https://linux-hardware.org/?probe=e6e8bd6545) | Dec 30, 2023 |
| Dell          | Precision 3551              | Notebook    | [38a733d0c4](https://linux-hardware.org/?probe=38a733d0c4) | Dec 30, 2023 |
| MSI           | B350 KRAIT GAMING           | Desktop     | [a4582db0da](https://linux-hardware.org/?probe=a4582db0da) | Dec 30, 2023 |
| DFI           | LP DK 790FXB-M2RS           | Desktop     | [8d0c82bedc](https://linux-hardware.org/?probe=8d0c82bedc) | Dec 30, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [4987fb1cb9](https://linux-hardware.org/?probe=4987fb1cb9) | Dec 30, 2023 |
| HP            | ProBook 440 G6              | Notebook    | [14623af544](https://linux-hardware.org/?probe=14623af544) | Dec 30, 2023 |
| Chuwi         | GemiBook                    | Notebook    | [3e5282eb93](https://linux-hardware.org/?probe=3e5282eb93) | Dec 30, 2023 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [4cb0683071](https://linux-hardware.org/?probe=4cb0683071) | Dec 30, 2023 |
| Infinix       | INBOOK X1 NEO               | Notebook    | [71e74b3e03](https://linux-hardware.org/?probe=71e74b3e03) | Dec 30, 2023 |
| Medion        | DEFENDER E10                | Notebook    | [811e5b34cd](https://linux-hardware.org/?probe=811e5b34cd) | Dec 30, 2023 |
| HP            | 8053                        | Desktop     | [26cb660757](https://linux-hardware.org/?probe=26cb660757) | Dec 30, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [3185001cb4](https://linux-hardware.org/?probe=3185001cb4) | Dec 30, 2023 |
| Dell          | Latitude E5420              | Notebook    | [0bc1fb2eaf](https://linux-hardware.org/?probe=0bc1fb2eaf) | Dec 30, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [5ded7ca887](https://linux-hardware.org/?probe=5ded7ca887) | Dec 30, 2023 |
| HP            | ProBook 6450b               | Notebook    | [ce6d3d0e7f](https://linux-hardware.org/?probe=ce6d3d0e7f) | Dec 30, 2023 |
| HP            | ProBook 6450b               | Notebook    | [f2128c8e8a](https://linux-hardware.org/?probe=f2128c8e8a) | Dec 30, 2023 |
| Lenovo        | 30BD NOK                    | Desktop     | [033b3c8abd](https://linux-hardware.org/?probe=033b3c8abd) | Dec 30, 2023 |
| Lenovo        | ThinkPad E15 20RD002RUS     | Notebook    | [221c773946](https://linux-hardware.org/?probe=221c773946) | Dec 30, 2023 |
| Medion        | DEFENDER E10                | Notebook    | [2e99d46be8](https://linux-hardware.org/?probe=2e99d46be8) | Dec 30, 2023 |
| Acer          | Spin SP314-21N              | Convertible | [4605e31e7d](https://linux-hardware.org/?probe=4605e31e7d) | Dec 30, 2023 |
| Acer          | Spin SP314-21N              | Convertible | [4f7ad65c82](https://linux-hardware.org/?probe=4f7ad65c82) | Dec 30, 2023 |
| Alurin        | ALU-BAR-I511-000-140        | Notebook    | [04ce6d9f2e](https://linux-hardware.org/?probe=04ce6d9f2e) | Dec 30, 2023 |
| Dell          | 0C522T A03                  | Desktop     | [67a47d8d83](https://linux-hardware.org/?probe=67a47d8d83) | Dec 30, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JNC... | Notebook    | [6410cef098](https://linux-hardware.org/?probe=6410cef098) | Dec 30, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [e14a6e4044](https://linux-hardware.org/?probe=e14a6e4044) | Dec 30, 2023 |
| HP            | 212B                        | Desktop     | [0ca173f4a7](https://linux-hardware.org/?probe=0ca173f4a7) | Dec 30, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [4744ad0a98](https://linux-hardware.org/?probe=4744ad0a98) | Dec 30, 2023 |
| Lenovo        | SDK0K11822 WIN              | Desktop     | [075f05f3df](https://linux-hardware.org/?probe=075f05f3df) | Dec 30, 2023 |
| Lenovo        | Yoga Slim 7 14APU8 83AA     | Notebook    | [8fe9261232](https://linux-hardware.org/?probe=8fe9261232) | Dec 30, 2023 |
| Dell          | 0V8WGR A00                  | Desktop     | [88a9972a33](https://linux-hardware.org/?probe=88a9972a33) | Dec 30, 2023 |
| Dell          | 0V8WGR A00                  | Desktop     | [91be04698f](https://linux-hardware.org/?probe=91be04698f) | Dec 30, 2023 |
| Lenovo        | ThinkPad T61 7662CTO        | Notebook    | [9e025b8cde](https://linux-hardware.org/?probe=9e025b8cde) | Dec 30, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [101c85733f](https://linux-hardware.org/?probe=101c85733f) | Dec 29, 2023 |
| Pegatron      | 2ACD                        | Desktop     | [44b4857097](https://linux-hardware.org/?probe=44b4857097) | Dec 29, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [01c6121d4c](https://linux-hardware.org/?probe=01c6121d4c) | Dec 29, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [64dddef2fa](https://linux-hardware.org/?probe=64dddef2fa) | Dec 29, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [115ec4e7a9](https://linux-hardware.org/?probe=115ec4e7a9) | Dec 29, 2023 |
| HP            | 304Ah                       | Desktop     | [0a84d8bd4a](https://linux-hardware.org/?probe=0a84d8bd4a) | Dec 29, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [dc67ac3e38](https://linux-hardware.org/?probe=dc67ac3e38) | Dec 29, 2023 |
| HP            | Laptop 17t-cn200            | Notebook    | [4c241f7e1d](https://linux-hardware.org/?probe=4c241f7e1d) | Dec 29, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [aabd2af674](https://linux-hardware.org/?probe=aabd2af674) | Dec 29, 2023 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [f42a6325e3](https://linux-hardware.org/?probe=f42a6325e3) | Dec 29, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [83399f5e60](https://linux-hardware.org/?probe=83399f5e60) | Dec 29, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [9104adc237](https://linux-hardware.org/?probe=9104adc237) | Dec 29, 2023 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [9883edd543](https://linux-hardware.org/?probe=9883edd543) | Dec 29, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [1229449c91](https://linux-hardware.org/?probe=1229449c91) | Dec 29, 2023 |
| Toshiba       | Satellite P70-B             | Notebook    | [2a5acedd16](https://linux-hardware.org/?probe=2a5acedd16) | Dec 29, 2023 |
| Supermicro    | X10DDW-i                    | Desktop     | [36b4cb3de7](https://linux-hardware.org/?probe=36b4cb3de7) | Dec 29, 2023 |
| Supermicro    | X10DDW-i                    | Desktop     | [7accaaedbb](https://linux-hardware.org/?probe=7accaaedbb) | Dec 29, 2023 |
| Supermicro    | X10DDW-i                    | Desktop     | [5d7ab2ff4b](https://linux-hardware.org/?probe=5d7ab2ff4b) | Dec 29, 2023 |
| Supermicro    | X10DDW-i                    | Desktop     | [be9b9577fd](https://linux-hardware.org/?probe=be9b9577fd) | Dec 29, 2023 |
| Supermicro    | X10DDW-i                    | Desktop     | [4f7ea59b94](https://linux-hardware.org/?probe=4f7ea59b94) | Dec 29, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [74b6d51ade](https://linux-hardware.org/?probe=74b6d51ade) | Dec 29, 2023 |
| Supermicro    | X8DTU                       | Server      | [f1f8eb7460](https://linux-hardware.org/?probe=f1f8eb7460) | Dec 29, 2023 |
| Supermicro    | X8DTU                       | Server      | [85a63e7856](https://linux-hardware.org/?probe=85a63e7856) | Dec 29, 2023 |
| Supermicro    | X8DTU                       | Server      | [17a55bc4e2](https://linux-hardware.org/?probe=17a55bc4e2) | Dec 29, 2023 |
| Supermicro    | X8DTT                       | Server      | [88a46dccc4](https://linux-hardware.org/?probe=88a46dccc4) | Dec 29, 2023 |
| Supermicro    | X8DTL                       | Server      | [bcd6e1b410](https://linux-hardware.org/?probe=bcd6e1b410) | Dec 29, 2023 |
| Supermicro    | X8DTT                       | Server      | [bbb803049b](https://linux-hardware.org/?probe=bbb803049b) | Dec 29, 2023 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [2433b4bc75](https://linux-hardware.org/?probe=2433b4bc75) | Dec 29, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [c7e2a4aa7c](https://linux-hardware.org/?probe=c7e2a4aa7c) | Dec 29, 2023 |
| Acer          | Aspire A715-76G             | Notebook    | [e25984fb5e](https://linux-hardware.org/?probe=e25984fb5e) | Dec 29, 2023 |
| Alienware     | x17 R2                      | Notebook    | [b439c4c2a9](https://linux-hardware.org/?probe=b439c4c2a9) | Dec 29, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [1148fbe6b6](https://linux-hardware.org/?probe=1148fbe6b6) | Dec 29, 2023 |
| HP            | ProLiant DL360p Gen8        | Server      | [01d5a057b5](https://linux-hardware.org/?probe=01d5a057b5) | Dec 29, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | Notebook    | [f3af16ad5d](https://linux-hardware.org/?probe=f3af16ad5d) | Dec 29, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [4ba914628d](https://linux-hardware.org/?probe=4ba914628d) | Dec 29, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [0032f131d1](https://linux-hardware.org/?probe=0032f131d1) | Dec 29, 2023 |
| Gigabyte      | Z490 UD                     | Desktop     | [e0aa5cc2d1](https://linux-hardware.org/?probe=e0aa5cc2d1) | Dec 29, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [318343d58b](https://linux-hardware.org/?probe=318343d58b) | Dec 29, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [3133f699e1](https://linux-hardware.org/?probe=3133f699e1) | Dec 29, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [915a028a6a](https://linux-hardware.org/?probe=915a028a6a) | Dec 29, 2023 |
| Unknown       | M17                         | Notebook    | [3d6789f805](https://linux-hardware.org/?probe=3d6789f805) | Dec 29, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [a353b43ac0](https://linux-hardware.org/?probe=a353b43ac0) | Dec 29, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [51ab2c0529](https://linux-hardware.org/?probe=51ab2c0529) | Dec 29, 2023 |
| Inventec      | VXC Class A02               | Desktop     | [0575404de8](https://linux-hardware.org/?probe=0575404de8) | Dec 29, 2023 |
| Timi          | A34R                        | Notebook    | [d72018ec19](https://linux-hardware.org/?probe=d72018ec19) | Dec 29, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [78e92a08a9](https://linux-hardware.org/?probe=78e92a08a9) | Dec 29, 2023 |
| Dell          | Latitude 5424 Rugged        | Notebook    | [1339f0b553](https://linux-hardware.org/?probe=1339f0b553) | Dec 29, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [2109440c5e](https://linux-hardware.org/?probe=2109440c5e) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [6a99e4eda2](https://linux-hardware.org/?probe=6a99e4eda2) | Dec 29, 2023 |
| Positivo      | P5GC-MX/CKD/POST/SI         | Desktop     | [1503c2f4b8](https://linux-hardware.org/?probe=1503c2f4b8) | Dec 29, 2023 |
| MSI           | MS-168B                     | Notebook    | [cd9dc4eadd](https://linux-hardware.org/?probe=cd9dc4eadd) | Dec 29, 2023 |
| Positivo      | P5GC-MX/CKD/POST/SI         | Desktop     | [08dadf5cbb](https://linux-hardware.org/?probe=08dadf5cbb) | Dec 29, 2023 |
| Dell          | Latitude 7300               | Notebook    | [926a273123](https://linux-hardware.org/?probe=926a273123) | Dec 29, 2023 |
| Acer          | Aspire 4736Z                | Notebook    | [ea8dffb40f](https://linux-hardware.org/?probe=ea8dffb40f) | Dec 29, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [69ed200761](https://linux-hardware.org/?probe=69ed200761) | Dec 29, 2023 |
| Dell          | Latitude 7300               | Notebook    | [ac9c0099fd](https://linux-hardware.org/?probe=ac9c0099fd) | Dec 29, 2023 |
| FriendlyEl... | NanoPi R6S                  | Soc         | [9a762ca6b1](https://linux-hardware.org/?probe=9a762ca6b1) | Dec 29, 2023 |
| Dell          | 0V8WGR A00                  | Desktop     | [e6479e42e3](https://linux-hardware.org/?probe=e6479e42e3) | Dec 29, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [1c6ef1eeb0](https://linux-hardware.org/?probe=1c6ef1eeb0) | Dec 29, 2023 |
| HP            | ZBook 14 G2                 | Notebook    | [0d092c7ece](https://linux-hardware.org/?probe=0d092c7ece) | Dec 29, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [13ba865757](https://linux-hardware.org/?probe=13ba865757) | Dec 29, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [f2d5cce82a](https://linux-hardware.org/?probe=f2d5cce82a) | Dec 29, 2023 |
| Lenovo        | Unknown                     | Notebook    | [71b939033d](https://linux-hardware.org/?probe=71b939033d) | Dec 28, 2023 |
| Lenovo        | ThinkPad E15 20RD002RUS     | Notebook    | [be86cafd2e](https://linux-hardware.org/?probe=be86cafd2e) | Dec 28, 2023 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [c2d6079fe7](https://linux-hardware.org/?probe=c2d6079fe7) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | Desktop     | [4f4c0766c2](https://linux-hardware.org/?probe=4f4c0766c2) | Dec 28, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [c6c27e51ca](https://linux-hardware.org/?probe=c6c27e51ca) | Dec 28, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | Notebook    | [e456132635](https://linux-hardware.org/?probe=e456132635) | Dec 28, 2023 |
| HUAWEI        | CREFG-XX                    | Notebook    | [91cc2daf14](https://linux-hardware.org/?probe=91cc2daf14) | Dec 28, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [4e1a45dee6](https://linux-hardware.org/?probe=4e1a45dee6) | Dec 28, 2023 |
| Dell          | Latitude E7450              | Notebook    | [50b3989c19](https://linux-hardware.org/?probe=50b3989c19) | Dec 28, 2023 |
| Foxconn       | H67MP-S/-V/H67MP            | Desktop     | [17473d28e3](https://linux-hardware.org/?probe=17473d28e3) | Dec 28, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [62aa46f354](https://linux-hardware.org/?probe=62aa46f354) | Dec 28, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [412a23e374](https://linux-hardware.org/?probe=412a23e374) | Dec 28, 2023 |
| Lenovo        | ThinkPad T420 4180ED3       | Notebook    | [0c9cecfac4](https://linux-hardware.org/?probe=0c9cecfac4) | Dec 28, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [2d53ff60cb](https://linux-hardware.org/?probe=2d53ff60cb) | Dec 28, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [ba96083a55](https://linux-hardware.org/?probe=ba96083a55) | Dec 28, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [6f277a8c3f](https://linux-hardware.org/?probe=6f277a8c3f) | Dec 28, 2023 |
| HP            | 830C                        | Desktop     | [2f602f34b2](https://linux-hardware.org/?probe=2f602f34b2) | Dec 28, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX         | Desktop     | [0d4c53d42f](https://linux-hardware.org/?probe=0d4c53d42f) | Dec 28, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [e65000c3c2](https://linux-hardware.org/?probe=e65000c3c2) | Dec 28, 2023 |
| HP            | 2000                        | Notebook    | [eac2251c15](https://linux-hardware.org/?probe=eac2251c15) | Dec 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [d6477c7999](https://linux-hardware.org/?probe=d6477c7999) | Dec 28, 2023 |
| HP            | 830C                        | Desktop     | [2256355ca5](https://linux-hardware.org/?probe=2256355ca5) | Dec 28, 2023 |
| Samsung       | 900X3C/900X3D/900X4C/900... | Notebook    | [e0bfd9face](https://linux-hardware.org/?probe=e0bfd9face) | Dec 28, 2023 |
| Chuwi         | GemiBook                    | Notebook    | [15199d7550](https://linux-hardware.org/?probe=15199d7550) | Dec 28, 2023 |
| ASRock        | AMCP7A-ION                  | Desktop     | [8358bb2fb8](https://linux-hardware.org/?probe=8358bb2fb8) | Dec 28, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [a21fc70e01](https://linux-hardware.org/?probe=a21fc70e01) | Dec 28, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e260b20e5d](https://linux-hardware.org/?probe=e260b20e5d) | Dec 28, 2023 |
| Intel         | NUC6CAYB J23203-407         | Mini pc     | [11883e6f6c](https://linux-hardware.org/?probe=11883e6f6c) | Dec 28, 2023 |
| Lenovo        | ThinkPad 20FRS22T00         | Convertible | [cc869f9f92](https://linux-hardware.org/?probe=cc869f9f92) | Dec 28, 2023 |
| Lenovo        | SDK0K11822 WIN              | Desktop     | [449d548765](https://linux-hardware.org/?probe=449d548765) | Dec 28, 2023 |
| HP            | ZBook 15                    | Notebook    | [92d7e45b22](https://linux-hardware.org/?probe=92d7e45b22) | Dec 28, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [ce26af0483](https://linux-hardware.org/?probe=ce26af0483) | Dec 28, 2023 |
| Dell          | 0YXT71 A03                  | Desktop     | [7a857447b4](https://linux-hardware.org/?probe=7a857447b4) | Dec 28, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [6abb72e809](https://linux-hardware.org/?probe=6abb72e809) | Dec 28, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [8250429628](https://linux-hardware.org/?probe=8250429628) | Dec 28, 2023 |
| JHZD          | BQM6                        | Desktop     | [fa041569a6](https://linux-hardware.org/?probe=fa041569a6) | Dec 28, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [27f6eb03d0](https://linux-hardware.org/?probe=27f6eb03d0) | Dec 28, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [1676225992](https://linux-hardware.org/?probe=1676225992) | Dec 28, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [6e74e1b943](https://linux-hardware.org/?probe=6e74e1b943) | Dec 28, 2023 |
| MACHINIST     | E5-D8-MAX V1.1              | Desktop     | [1cdeeaefff](https://linux-hardware.org/?probe=1cdeeaefff) | Dec 28, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [8df141917e](https://linux-hardware.org/?probe=8df141917e) | Dec 28, 2023 |
| HP            | ProBook 455 G1              | Notebook    | [d132700b11](https://linux-hardware.org/?probe=d132700b11) | Dec 28, 2023 |
| Acer          | H410H6-M17 P21-A1           | Desktop     | [6c4e2313d7](https://linux-hardware.org/?probe=6c4e2313d7) | Dec 28, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [020ea108b0](https://linux-hardware.org/?probe=020ea108b0) | Dec 28, 2023 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [7b388d0a8f](https://linux-hardware.org/?probe=7b388d0a8f) | Dec 28, 2023 |
| win elemen... | MoreFine S500+              | Notebook    | [6880205d9e](https://linux-hardware.org/?probe=6880205d9e) | Dec 28, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [f61d16f126](https://linux-hardware.org/?probe=f61d16f126) | Dec 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [a5b16ddafb](https://linux-hardware.org/?probe=a5b16ddafb) | Dec 28, 2023 |
| Valve         | Galileo                     | Notebook    | [ae65838bd7](https://linux-hardware.org/?probe=ae65838bd7) | Dec 28, 2023 |
| HP            | Spectre x360 Convertible    | Convertible | [8cd96ef9b2](https://linux-hardware.org/?probe=8cd96ef9b2) | Dec 28, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [52a99e896e](https://linux-hardware.org/?probe=52a99e896e) | Dec 28, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [323f661113](https://linux-hardware.org/?probe=323f661113) | Dec 27, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [06147cc721](https://linux-hardware.org/?probe=06147cc721) | Dec 27, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [6be155ee0d](https://linux-hardware.org/?probe=6be155ee0d) | Dec 27, 2023 |
| Dell          | 0F642F A00                  | Desktop     | [6adfd04a7e](https://linux-hardware.org/?probe=6adfd04a7e) | Dec 27, 2023 |
| MSI           | Pulse GL66 12UEK            | Notebook    | [4600a758fa](https://linux-hardware.org/?probe=4600a758fa) | Dec 27, 2023 |
| Gigabyte      | B660 DS3H DDR4              | Desktop     | [3b68c7809f](https://linux-hardware.org/?probe=3b68c7809f) | Dec 27, 2023 |
| HP            | 1589                        | Desktop     | [c52940817e](https://linux-hardware.org/?probe=c52940817e) | Dec 27, 2023 |
| Dell          | G3 3500                     | Notebook    | [87c0216250](https://linux-hardware.org/?probe=87c0216250) | Dec 27, 2023 |
| ASUSTek       | ROG Strix G614JZ_G614JZ     | Notebook    | [eb40e7ad5c](https://linux-hardware.org/?probe=eb40e7ad5c) | Dec 27, 2023 |
| AZW           | EQ                          | Desktop     | [1300ad3a67](https://linux-hardware.org/?probe=1300ad3a67) | Dec 27, 2023 |
| ASRock        | B660M Pro RS                | Desktop     | [0ddd3db13a](https://linux-hardware.org/?probe=0ddd3db13a) | Dec 27, 2023 |
| HP            | 3048h                       | Desktop     | [94e268312a](https://linux-hardware.org/?probe=94e268312a) | Dec 27, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [90e55e787b](https://linux-hardware.org/?probe=90e55e787b) | Dec 27, 2023 |
| Lenovo        | IdeaPad Slim 3 15IRU8 82... | Notebook    | [c16f162169](https://linux-hardware.org/?probe=c16f162169) | Dec 27, 2023 |
| ASUSTek       | UN42                        | Desktop     | [1b146f734f](https://linux-hardware.org/?probe=1b146f734f) | Dec 27, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [e0b1c57cc6](https://linux-hardware.org/?probe=e0b1c57cc6) | Dec 27, 2023 |
| Dell          | Latitude 3520               | Notebook    | [b5802159c7](https://linux-hardware.org/?probe=b5802159c7) | Dec 27, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [84242f4904](https://linux-hardware.org/?probe=84242f4904) | Dec 27, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [ab7e890030](https://linux-hardware.org/?probe=ab7e890030) | Dec 27, 2023 |
| MSI           | X79A-GD65                   | Desktop     | [298e0aeef7](https://linux-hardware.org/?probe=298e0aeef7) | Dec 27, 2023 |
| ASUSTek       | ROG STRIX B360-G GAMING     | Desktop     | [136b8b5f83](https://linux-hardware.org/?probe=136b8b5f83) | Dec 27, 2023 |
| MSI           | X79A-GD65                   | Desktop     | [0272fb469a](https://linux-hardware.org/?probe=0272fb469a) | Dec 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [0f40cd177e](https://linux-hardware.org/?probe=0f40cd177e) | Dec 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [5965d25e5a](https://linux-hardware.org/?probe=5965d25e5a) | Dec 27, 2023 |
| Dell          | 02VCFF A00                  | Desktop     | [902c7a4466](https://linux-hardware.org/?probe=902c7a4466) | Dec 27, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [bfa7e572a4](https://linux-hardware.org/?probe=bfa7e572a4) | Dec 27, 2023 |
| HP            | Pavilion dv7                | Notebook    | [c84d0249b0](https://linux-hardware.org/?probe=c84d0249b0) | Dec 27, 2023 |
| HP            | Pavilion dv7                | Notebook    | [a5fde2f725](https://linux-hardware.org/?probe=a5fde2f725) | Dec 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [d23b5553ca](https://linux-hardware.org/?probe=d23b5553ca) | Dec 27, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [82dda49ee8](https://linux-hardware.org/?probe=82dda49ee8) | Dec 27, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [f9484ac33e](https://linux-hardware.org/?probe=f9484ac33e) | Dec 27, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [9a27ea61df](https://linux-hardware.org/?probe=9a27ea61df) | Dec 27, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [555b9489dd](https://linux-hardware.org/?probe=555b9489dd) | Dec 27, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [de1dd08f64](https://linux-hardware.org/?probe=de1dd08f64) | Dec 27, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [16e3fbc6bb](https://linux-hardware.org/?probe=16e3fbc6bb) | Dec 27, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [27856e6bb2](https://linux-hardware.org/?probe=27856e6bb2) | Dec 27, 2023 |
| Supermicro    | X11DAi-N                    | Server      | [6e0a7e9f92](https://linux-hardware.org/?probe=6e0a7e9f92) | Dec 27, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [9440079733](https://linux-hardware.org/?probe=9440079733) | Dec 27, 2023 |
| HP            | 86E9 A                      | Desktop     | [e373d2be5d](https://linux-hardware.org/?probe=e373d2be5d) | Dec 27, 2023 |
| Supermicro    | X11DAi-N                    | Server      | [9a681db276](https://linux-hardware.org/?probe=9a681db276) | Dec 27, 2023 |
| Dell          | Latitude 5420               | Notebook    | [07b64f5dfe](https://linux-hardware.org/?probe=07b64f5dfe) | Dec 27, 2023 |
| MSI           | B150M MORTAR                | Desktop     | [c179cdb6dc](https://linux-hardware.org/?probe=c179cdb6dc) | Dec 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [04601b4053](https://linux-hardware.org/?probe=04601b4053) | Dec 27, 2023 |
| Zinox Tech... | x64-Based PC                | Tablet      | [6512568b77](https://linux-hardware.org/?probe=6512568b77) | Dec 27, 2023 |
| HP            | 81BB                        | Desktop     | [354921dd8b](https://linux-hardware.org/?probe=354921dd8b) | Dec 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [8af95757fe](https://linux-hardware.org/?probe=8af95757fe) | Dec 27, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [b1e081701a](https://linux-hardware.org/?probe=b1e081701a) | Dec 27, 2023 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [81ec2dbefe](https://linux-hardware.org/?probe=81ec2dbefe) | Dec 27, 2023 |
| Lenovo        | ThinkPad E480 20KN0065MX    | Notebook    | [14018f1aec](https://linux-hardware.org/?probe=14018f1aec) | Dec 27, 2023 |
| Acer          | H410H6-M17 P21-A1           | Desktop     | [106af034ae](https://linux-hardware.org/?probe=106af034ae) | Dec 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S24N3J    | Notebook    | [b6b0c2c889](https://linux-hardware.org/?probe=b6b0c2c889) | Dec 27, 2023 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [3c0ecabaa3](https://linux-hardware.org/?probe=3c0ecabaa3) | Dec 27, 2023 |
| HUAWEI        | NbDE-WXX9                   | Notebook    | [5f124e4838](https://linux-hardware.org/?probe=5f124e4838) | Dec 27, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [a8871fb21b](https://linux-hardware.org/?probe=a8871fb21b) | Dec 27, 2023 |
| Dell          | Precision M4800             | Notebook    | [47508330f1](https://linux-hardware.org/?probe=47508330f1) | Dec 26, 2023 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [412f9dbf1e](https://linux-hardware.org/?probe=412f9dbf1e) | Dec 26, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [a14ae548b1](https://linux-hardware.org/?probe=a14ae548b1) | Dec 26, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [51f2048be8](https://linux-hardware.org/?probe=51f2048be8) | Dec 26, 2023 |
| GITSTAR       | GDC-1461                    | Notebook    | [398e4f42e4](https://linux-hardware.org/?probe=398e4f42e4) | Dec 26, 2023 |
| MSI           | GS40 6QE Phantom            | Notebook    | [2946f9add8](https://linux-hardware.org/?probe=2946f9add8) | Dec 26, 2023 |
| Medion        | P6613                       | Notebook    | [1f30069d6d](https://linux-hardware.org/?probe=1f30069d6d) | Dec 26, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [fae868ef79](https://linux-hardware.org/?probe=fae868ef79) | Dec 26, 2023 |
| TUXEDO        | N24_25JU                    | Notebook    | [3c7a5feb48](https://linux-hardware.org/?probe=3c7a5feb48) | Dec 26, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [4e5179b4d1](https://linux-hardware.org/?probe=4e5179b4d1) | Dec 26, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [67979f3133](https://linux-hardware.org/?probe=67979f3133) | Dec 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4a481ca830](https://linux-hardware.org/?probe=4a481ca830) | Dec 26, 2023 |
| Lenovo        | IdeaPad Slim 5 14IAH8 83... | Notebook    | [e514863c67](https://linux-hardware.org/?probe=e514863c67) | Dec 26, 2023 |
| MACHINIST     | X99-K9 V2.0                 | Desktop     | [53f503a6e5](https://linux-hardware.org/?probe=53f503a6e5) | Dec 26, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [d5e9630425](https://linux-hardware.org/?probe=d5e9630425) | Dec 26, 2023 |
| MACHINIST     | X99-K9 V2.0                 | Desktop     | [4736deb84b](https://linux-hardware.org/?probe=4736deb84b) | Dec 26, 2023 |
| Supermicro    | X8SIL                       | Desktop     | [16a2d27e0a](https://linux-hardware.org/?probe=16a2d27e0a) | Dec 26, 2023 |
| Chuwi         | MiniBook X                  | Notebook    | [f55a24b036](https://linux-hardware.org/?probe=f55a24b036) | Dec 26, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [17304074a6](https://linux-hardware.org/?probe=17304074a6) | Dec 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3db4d71445](https://linux-hardware.org/?probe=3db4d71445) | Dec 26, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [bb819f78ef](https://linux-hardware.org/?probe=bb819f78ef) | Dec 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8fae3225fd](https://linux-hardware.org/?probe=8fae3225fd) | Dec 26, 2023 |
| MSI           | MAG B560M BAZOOKA           | Desktop     | [64d1814f82](https://linux-hardware.org/?probe=64d1814f82) | Dec 26, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [3015754a4f](https://linux-hardware.org/?probe=3015754a4f) | Dec 26, 2023 |
| HP            | 2000                        | Notebook    | [057698e1aa](https://linux-hardware.org/?probe=057698e1aa) | Dec 26, 2023 |
| Lenovo        | ThinkPad 20FRS22T00         | Convertible | [97644755b2](https://linux-hardware.org/?probe=97644755b2) | Dec 26, 2023 |
| Dell          | Latitude 5440               | Notebook    | [44e45480d1](https://linux-hardware.org/?probe=44e45480d1) | Dec 26, 2023 |
| MSI           | B150M MORTAR                | Desktop     | [23577ab5f1](https://linux-hardware.org/?probe=23577ab5f1) | Dec 26, 2023 |
| Dell          | 042P49 A02                  | Desktop     | [67c9288ec5](https://linux-hardware.org/?probe=67c9288ec5) | Dec 26, 2023 |
| ASUSTek       | X550DP                      | Notebook    | [c7758c21ce](https://linux-hardware.org/?probe=c7758c21ce) | Dec 26, 2023 |
| ASUSTek       | X550DP                      | Notebook    | [a456e712b7](https://linux-hardware.org/?probe=a456e712b7) | Dec 26, 2023 |
| HP            | 86E9 A                      | Desktop     | [c13adc0c5e](https://linux-hardware.org/?probe=c13adc0c5e) | Dec 26, 2023 |
| Gigabyte      | Z490 UD                     | Desktop     | [09813a10ac](https://linux-hardware.org/?probe=09813a10ac) | Dec 26, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [aee55a670d](https://linux-hardware.org/?probe=aee55a670d) | Dec 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [83eea945be](https://linux-hardware.org/?probe=83eea945be) | Dec 26, 2023 |
| Medion        | E6228                       | Notebook    | [827fcc5d4b](https://linux-hardware.org/?probe=827fcc5d4b) | Dec 26, 2023 |
| Dell          | 0D6H9T A00                  | Desktop     | [280147184f](https://linux-hardware.org/?probe=280147184f) | Dec 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [d382bd5980](https://linux-hardware.org/?probe=d382bd5980) | Dec 26, 2023 |
| NCR           | Monaco BIOS.9.1             | Desktop     | [afa7781093](https://linux-hardware.org/?probe=afa7781093) | Dec 26, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [67492721ec](https://linux-hardware.org/?probe=67492721ec) | Dec 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [c701a5ce22](https://linux-hardware.org/?probe=c701a5ce22) | Dec 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [ef974b90c4](https://linux-hardware.org/?probe=ef974b90c4) | Dec 25, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [148b2b7232](https://linux-hardware.org/?probe=148b2b7232) | Dec 25, 2023 |
| HP            | 81C5 MVB                    | Desktop     | [15a3980b4a](https://linux-hardware.org/?probe=15a3980b4a) | Dec 25, 2023 |
| MSI           | B85-G43                     | Desktop     | [fd632d7a1f](https://linux-hardware.org/?probe=fd632d7a1f) | Dec 25, 2023 |
| Dell          | Latitude 7490               | Notebook    | [3c17f0bdce](https://linux-hardware.org/?probe=3c17f0bdce) | Dec 25, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [59e540836e](https://linux-hardware.org/?probe=59e540836e) | Dec 25, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [475a32b16d](https://linux-hardware.org/?probe=475a32b16d) | Dec 25, 2023 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [f6df6fc800](https://linux-hardware.org/?probe=f6df6fc800) | Dec 25, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [39eb82bb24](https://linux-hardware.org/?probe=39eb82bb24) | Dec 25, 2023 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [2f1d5396df](https://linux-hardware.org/?probe=2f1d5396df) | Dec 25, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | Notebook    | [fb78f052e1](https://linux-hardware.org/?probe=fb78f052e1) | Dec 25, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [771d35e2bc](https://linux-hardware.org/?probe=771d35e2bc) | Dec 25, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [022fc838b1](https://linux-hardware.org/?probe=022fc838b1) | Dec 25, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [4997b8894d](https://linux-hardware.org/?probe=4997b8894d) | Dec 25, 2023 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [7522238d8b](https://linux-hardware.org/?probe=7522238d8b) | Dec 25, 2023 |
| Microsoft     | Surface Pro 8               | Tablet      | [751e8a9cc9](https://linux-hardware.org/?probe=751e8a9cc9) | Dec 25, 2023 |
| Dell          | Latitude E6520              | Notebook    | [fa25376a64](https://linux-hardware.org/?probe=fa25376a64) | Dec 25, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [e7901d2ec9](https://linux-hardware.org/?probe=e7901d2ec9) | Dec 25, 2023 |
| MSI           | A68HM-P33 V2                | Desktop     | [4f11205fd5](https://linux-hardware.org/?probe=4f11205fd5) | Dec 25, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [494c6b1fe3](https://linux-hardware.org/?probe=494c6b1fe3) | Dec 25, 2023 |
| Google        | Aleena                      | Notebook    | [a5a888a877](https://linux-hardware.org/?probe=a5a888a877) | Dec 25, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [a82bef9300](https://linux-hardware.org/?probe=a82bef9300) | Dec 25, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [57131068a4](https://linux-hardware.org/?probe=57131068a4) | Dec 25, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [df812b1171](https://linux-hardware.org/?probe=df812b1171) | Dec 25, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [884a852341](https://linux-hardware.org/?probe=884a852341) | Dec 25, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [0972c678d9](https://linux-hardware.org/?probe=0972c678d9) | Dec 25, 2023 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [9007132e3a](https://linux-hardware.org/?probe=9007132e3a) | Dec 25, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [61d0f60cae](https://linux-hardware.org/?probe=61d0f60cae) | Dec 25, 2023 |
| MSI           | PS63 Modern 8M              | Notebook    | [3097ac02eb](https://linux-hardware.org/?probe=3097ac02eb) | Dec 25, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [7f06a26b50](https://linux-hardware.org/?probe=7f06a26b50) | Dec 25, 2023 |
| Lenovo        | ThinkPad X270 20HN005NMX    | Notebook    | [aeb2dccb91](https://linux-hardware.org/?probe=aeb2dccb91) | Dec 25, 2023 |
| ASUSTek       | ET2010AG                    | All in one  | [34f80ef918](https://linux-hardware.org/?probe=34f80ef918) | Dec 25, 2023 |
| HP            | Laptop 17-bs1xx             | Notebook    | [736cd905c8](https://linux-hardware.org/?probe=736cd905c8) | Dec 25, 2023 |
| ASUSTek       | ET2010AG                    | All in one  | [bf542378eb](https://linux-hardware.org/?probe=bf542378eb) | Dec 25, 2023 |
| TUXEDO        | N24_25JU                    | Notebook    | [26beeaeefa](https://linux-hardware.org/?probe=26beeaeefa) | Dec 25, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [814681e28a](https://linux-hardware.org/?probe=814681e28a) | Dec 25, 2023 |
| AMI           | Cherry Trail CR             | Mini pc     | [dd463a721a](https://linux-hardware.org/?probe=dd463a721a) | Dec 25, 2023 |
| AMI           | Cherry Trail CR             | Mini pc     | [aaaee08085](https://linux-hardware.org/?probe=aaaee08085) | Dec 25, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [a8acfd11f6](https://linux-hardware.org/?probe=a8acfd11f6) | Dec 25, 2023 |
| MSI           | EX610                       | Notebook    | [95fe9d0294](https://linux-hardware.org/?probe=95fe9d0294) | Dec 25, 2023 |
| ASRock        | B760M Pro RS/D4 WiFi        | Desktop     | [c75f8f9d6f](https://linux-hardware.org/?probe=c75f8f9d6f) | Dec 25, 2023 |
| HP            | Pavilion dv7                | Notebook    | [72ee76c262](https://linux-hardware.org/?probe=72ee76c262) | Dec 25, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [e1f5de21d1](https://linux-hardware.org/?probe=e1f5de21d1) | Dec 25, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [9eccf6133e](https://linux-hardware.org/?probe=9eccf6133e) | Dec 25, 2023 |
| HP            | 829A                        | Mini pc     | [07d865f884](https://linux-hardware.org/?probe=07d865f884) | Dec 24, 2023 |
| HP            | 829A                        | Mini pc     | [949e9e9250](https://linux-hardware.org/?probe=949e9e9250) | Dec 24, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [1ef527f93a](https://linux-hardware.org/?probe=1ef527f93a) | Dec 24, 2023 |
| HP            | 625                         | Notebook    | [c826402085](https://linux-hardware.org/?probe=c826402085) | Dec 24, 2023 |
| HP            | 625                         | Notebook    | [3d8a288af1](https://linux-hardware.org/?probe=3d8a288af1) | Dec 24, 2023 |
| Acer          | Aspire 5749                 | Notebook    | [e70e0eae25](https://linux-hardware.org/?probe=e70e0eae25) | Dec 24, 2023 |
| ASRock        | H61DEL                      | Desktop     | [932b2c50eb](https://linux-hardware.org/?probe=932b2c50eb) | Dec 24, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [e6d150acea](https://linux-hardware.org/?probe=e6d150acea) | Dec 24, 2023 |
| Lenovo        | ThinkPad W530 2436CT0       | Notebook    | [7f8be52856](https://linux-hardware.org/?probe=7f8be52856) | Dec 24, 2023 |
| Dell          | Latitude 3520               | Notebook    | [2bac03be10](https://linux-hardware.org/?probe=2bac03be10) | Dec 24, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [679c502604](https://linux-hardware.org/?probe=679c502604) | Dec 24, 2023 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [915a47dab1](https://linux-hardware.org/?probe=915a47dab1) | Dec 24, 2023 |
| Lenovo        | ThinkPad X280 20KES4TD0T    | Notebook    | [978819464c](https://linux-hardware.org/?probe=978819464c) | Dec 24, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [a3c4869087](https://linux-hardware.org/?probe=a3c4869087) | Dec 24, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [d330d1d9f9](https://linux-hardware.org/?probe=d330d1d9f9) | Dec 24, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [d8ae24af2b](https://linux-hardware.org/?probe=d8ae24af2b) | Dec 24, 2023 |
| eMachines     | E725                        | Notebook    | [830cb3faa4](https://linux-hardware.org/?probe=830cb3faa4) | Dec 24, 2023 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | Desktop     | [b29541d467](https://linux-hardware.org/?probe=b29541d467) | Dec 24, 2023 |
| Panasonic     | FZG1-4                      | Notebook    | [f6c98a5b67](https://linux-hardware.org/?probe=f6c98a5b67) | Dec 24, 2023 |
| Dell          | 03X6X0 A06                  | Server      | [ca9bb6b7ff](https://linux-hardware.org/?probe=ca9bb6b7ff) | Dec 24, 2023 |
| Dell          | Inspiron 1564               | Notebook    | [a1945990cc](https://linux-hardware.org/?probe=a1945990cc) | Dec 24, 2023 |
| Dell          | Inspiron 1564               | Notebook    | [e02428db4a](https://linux-hardware.org/?probe=e02428db4a) | Dec 24, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [f666ec3927](https://linux-hardware.org/?probe=f666ec3927) | Dec 24, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [bcb6745ac2](https://linux-hardware.org/?probe=bcb6745ac2) | Dec 24, 2023 |
| HP            | 8918                        | Desktop     | [4b922c3362](https://linux-hardware.org/?probe=4b922c3362) | Dec 24, 2023 |
| Dell          | Inspiron 5485 2n1           | Convertible | [334b43f409](https://linux-hardware.org/?probe=334b43f409) | Dec 24, 2023 |
| Intel         | B85                         | Desktop     | [5b462c9ed1](https://linux-hardware.org/?probe=5b462c9ed1) | Dec 24, 2023 |
| Dell          | Latitude 7490               | Notebook    | [69205c648f](https://linux-hardware.org/?probe=69205c648f) | Dec 24, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [cc87c11e7b](https://linux-hardware.org/?probe=cc87c11e7b) | Dec 24, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [1cb09f63f9](https://linux-hardware.org/?probe=1cb09f63f9) | Dec 24, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [f8abeb2607](https://linux-hardware.org/?probe=f8abeb2607) | Dec 24, 2023 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [ef61ad2663](https://linux-hardware.org/?probe=ef61ad2663) | Dec 24, 2023 |
| Dell          | 0P658H A05                  | Server      | [14a0701959](https://linux-hardware.org/?probe=14a0701959) | Dec 24, 2023 |
| Google        | Magolor                     | Notebook    | [f5d079bc79](https://linux-hardware.org/?probe=f5d079bc79) | Dec 24, 2023 |
| Dell          | Latitude 12 Rugged Table... | Notebook    | [7690d56522](https://linux-hardware.org/?probe=7690d56522) | Dec 24, 2023 |
| Dell          | Precision 3560              | Notebook    | [b945ab8339](https://linux-hardware.org/?probe=b945ab8339) | Dec 24, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0600... | Notebook    | [07efd36bbe](https://linux-hardware.org/?probe=07efd36bbe) | Dec 24, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [a3af8ee68a](https://linux-hardware.org/?probe=a3af8ee68a) | Dec 24, 2023 |
| Lenovo        | 3181 NO DPK                 | Mini pc     | [441eb7b439](https://linux-hardware.org/?probe=441eb7b439) | Dec 24, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [3ac6a566ab](https://linux-hardware.org/?probe=3ac6a566ab) | Dec 24, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [dc269fb33a](https://linux-hardware.org/?probe=dc269fb33a) | Dec 24, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [a70e7da743](https://linux-hardware.org/?probe=a70e7da743) | Dec 23, 2023 |
| Gateway       | NV59C                       | Notebook    | [1537866140](https://linux-hardware.org/?probe=1537866140) | Dec 23, 2023 |
| AZW           | EQ                          | Desktop     | [a04c9735a7](https://linux-hardware.org/?probe=a04c9735a7) | Dec 23, 2023 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [a57f2ee15f](https://linux-hardware.org/?probe=a57f2ee15f) | Dec 23, 2023 |
| AZW           | EQ                          | Desktop     | [9b3d265cd1](https://linux-hardware.org/?probe=9b3d265cd1) | Dec 23, 2023 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [c9555a34f2](https://linux-hardware.org/?probe=c9555a34f2) | Dec 23, 2023 |
| Dell          | 0J1C3P A01                  | Desktop     | [faea7a3006](https://linux-hardware.org/?probe=faea7a3006) | Dec 23, 2023 |
| ASUSTek       | GL503VM                     | Notebook    | [dfedaea706](https://linux-hardware.org/?probe=dfedaea706) | Dec 23, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [0b0beeca3a](https://linux-hardware.org/?probe=0b0beeca3a) | Dec 23, 2023 |
| Unknown       | Unknown                     | Notebook    | [ef80f96d40](https://linux-hardware.org/?probe=ef80f96d40) | Dec 23, 2023 |
| ASUSTek       | GL503VM                     | Notebook    | [05b212db99](https://linux-hardware.org/?probe=05b212db99) | Dec 23, 2023 |
| Sony          | VPCEA1S1E                   | Notebook    | [af850dd5f3](https://linux-hardware.org/?probe=af850dd5f3) | Dec 23, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | Desktop     | [b1c3408d24](https://linux-hardware.org/?probe=b1c3408d24) | Dec 23, 2023 |
| ASRock        | H310CM-HDV/M.2              | Desktop     | [76d95ab75c](https://linux-hardware.org/?probe=76d95ab75c) | Dec 23, 2023 |
| TUXEDO        | N24_25JU                    | Notebook    | [8a1a153723](https://linux-hardware.org/?probe=8a1a153723) | Dec 23, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [6f36390142](https://linux-hardware.org/?probe=6f36390142) | Dec 23, 2023 |
| Lenovo        | IdeaPad Y500 9541           | Notebook    | [a85ec375f5](https://linux-hardware.org/?probe=a85ec375f5) | Dec 23, 2023 |
| ASRock        | AMCP7A-ION                  | Desktop     | [fb0acc2d50](https://linux-hardware.org/?probe=fb0acc2d50) | Dec 23, 2023 |
| GITSTAR       | GDC-1461                    | Notebook    | [5412cf0f39](https://linux-hardware.org/?probe=5412cf0f39) | Dec 23, 2023 |
| MACHINIST     | X99-K9 V2.0                 | Desktop     | [7f4061fd49](https://linux-hardware.org/?probe=7f4061fd49) | Dec 23, 2023 |
| Lenovo        | ThinkPad T410 2537E82       | Notebook    | [d153c701cc](https://linux-hardware.org/?probe=d153c701cc) | Dec 23, 2023 |
| Unknown       | FastRhino R66S              | Soc         | [a9cd767c91](https://linux-hardware.org/?probe=a9cd767c91) | Dec 23, 2023 |
| Dell          | Latitude E5510              | Notebook    | [379ebf6111](https://linux-hardware.org/?probe=379ebf6111) | Dec 23, 2023 |
| MSI           | GE62 2QF                    | Notebook    | [cf9a783196](https://linux-hardware.org/?probe=cf9a783196) | Dec 23, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | Notebook    | [d409d2fe79](https://linux-hardware.org/?probe=d409d2fe79) | Dec 23, 2023 |
| HP            | 1497                        | Desktop     | [9d5244b557](https://linux-hardware.org/?probe=9d5244b557) | Dec 23, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | Notebook    | [eae7bab112](https://linux-hardware.org/?probe=eae7bab112) | Dec 23, 2023 |
| Lenovo        | ThinkPad T410 2537E82       | Notebook    | [398233e395](https://linux-hardware.org/?probe=398233e395) | Dec 23, 2023 |
| Lenovo        | ThinkCentre M58 7373AJ5     | Desktop     | [201981bc3f](https://linux-hardware.org/?probe=201981bc3f) | Dec 23, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [4b6025ed6e](https://linux-hardware.org/?probe=4b6025ed6e) | Dec 23, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [f30aec24c2](https://linux-hardware.org/?probe=f30aec24c2) | Dec 23, 2023 |
| ASRock        | AMCP7A-ION                  | Desktop     | [7d19dec574](https://linux-hardware.org/?probe=7d19dec574) | Dec 23, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [ab3cc8a89c](https://linux-hardware.org/?probe=ab3cc8a89c) | Dec 23, 2023 |
| Acer          | TravelMate 5730             | Notebook    | [69571c0b91](https://linux-hardware.org/?probe=69571c0b91) | Dec 23, 2023 |
| MSI           | A88XM-E35                   | Desktop     | [dce385e94b](https://linux-hardware.org/?probe=dce385e94b) | Dec 23, 2023 |
| Dell          | 0P4T42 A01                  | All in one  | [db76245a52](https://linux-hardware.org/?probe=db76245a52) | Dec 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [d3dabca767](https://linux-hardware.org/?probe=d3dabca767) | Dec 23, 2023 |
| Dell          | Latitude E6330              | Notebook    | [afca8c73b2](https://linux-hardware.org/?probe=afca8c73b2) | Dec 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [26673c372e](https://linux-hardware.org/?probe=26673c372e) | Dec 23, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [2fcf77279a](https://linux-hardware.org/?probe=2fcf77279a) | Dec 23, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [8f2f7cd8c9](https://linux-hardware.org/?probe=8f2f7cd8c9) | Dec 23, 2023 |
| HP            | Laptop 17-bs1xx             | Notebook    | [984a979a7b](https://linux-hardware.org/?probe=984a979a7b) | Dec 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [19e33f2ead](https://linux-hardware.org/?probe=19e33f2ead) | Dec 23, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [9b8ad6a3f1](https://linux-hardware.org/?probe=9b8ad6a3f1) | Dec 23, 2023 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | Desktop     | [da46ad37d3](https://linux-hardware.org/?probe=da46ad37d3) | Dec 23, 2023 |
| eMachines     | EL1360                      | Desktop     | [af31609559](https://linux-hardware.org/?probe=af31609559) | Dec 23, 2023 |
| Acer          | Aspire R3-131T              | Notebook    | [647b2fddf6](https://linux-hardware.org/?probe=647b2fddf6) | Dec 23, 2023 |
| ASUSTek       | P6T                         | Desktop     | [d90adb3a12](https://linux-hardware.org/?probe=d90adb3a12) | Dec 23, 2023 |
| Dell          | Latitude E6400              | Notebook    | [1a10fd9a2e](https://linux-hardware.org/?probe=1a10fd9a2e) | Dec 23, 2023 |
| System76      | Serval WS                   | Notebook    | [a250c12d1d](https://linux-hardware.org/?probe=a250c12d1d) | Dec 23, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [da051b693c](https://linux-hardware.org/?probe=da051b693c) | Dec 23, 2023 |
| Lenovo        | ThinkPad E15 20RD002RUS     | Notebook    | [6ba8bb7550](https://linux-hardware.org/?probe=6ba8bb7550) | Dec 23, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [36492390fd](https://linux-hardware.org/?probe=36492390fd) | Dec 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [0f2cad4391](https://linux-hardware.org/?probe=0f2cad4391) | Dec 22, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [e778e7923a](https://linux-hardware.org/?probe=e778e7923a) | Dec 22, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [b601b75917](https://linux-hardware.org/?probe=b601b75917) | Dec 22, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [42c72b303d](https://linux-hardware.org/?probe=42c72b303d) | Dec 22, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [a3fc39604c](https://linux-hardware.org/?probe=a3fc39604c) | Dec 22, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [b09c4dd8a2](https://linux-hardware.org/?probe=b09c4dd8a2) | Dec 22, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [980f7dfed7](https://linux-hardware.org/?probe=980f7dfed7) | Dec 22, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [bbdb2204d8](https://linux-hardware.org/?probe=bbdb2204d8) | Dec 22, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [2268342e9f](https://linux-hardware.org/?probe=2268342e9f) | Dec 22, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [89ef1fa23c](https://linux-hardware.org/?probe=89ef1fa23c) | Dec 22, 2023 |
| Dell          | 0D6H9T A00                  | Desktop     | [84275b737e](https://linux-hardware.org/?probe=84275b737e) | Dec 22, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [c81a75e686](https://linux-hardware.org/?probe=c81a75e686) | Dec 22, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [c9bee45423](https://linux-hardware.org/?probe=c9bee45423) | Dec 22, 2023 |
| Intel         | H61                         | Desktop     | [72c7724ef0](https://linux-hardware.org/?probe=72c7724ef0) | Dec 22, 2023 |
| HP            | 212B                        | Desktop     | [8fa44a703b](https://linux-hardware.org/?probe=8fa44a703b) | Dec 22, 2023 |
| ASUSTek       | ASUSLaptop_Q540VJ           | Notebook    | [937842fe5d](https://linux-hardware.org/?probe=937842fe5d) | Dec 22, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [6ff6445717](https://linux-hardware.org/?probe=6ff6445717) | Dec 22, 2023 |
| Gateway       | NV59C                       | Notebook    | [62d62c0a3b](https://linux-hardware.org/?probe=62d62c0a3b) | Dec 22, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [ff8ded7ff8](https://linux-hardware.org/?probe=ff8ded7ff8) | Dec 22, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [27a132c185](https://linux-hardware.org/?probe=27a132c185) | Dec 22, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [03ddd69e34](https://linux-hardware.org/?probe=03ddd69e34) | Dec 22, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [8e38fb94ba](https://linux-hardware.org/?probe=8e38fb94ba) | Dec 22, 2023 |
| Lenovo        | ThinkPad Edge E431 62771... | Notebook    | [e6f38cb85e](https://linux-hardware.org/?probe=e6f38cb85e) | Dec 22, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [30e988edc9](https://linux-hardware.org/?probe=30e988edc9) | Dec 22, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [9ff527cfd0](https://linux-hardware.org/?probe=9ff527cfd0) | Dec 22, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [3e49a75ff4](https://linux-hardware.org/?probe=3e49a75ff4) | Dec 22, 2023 |
| HP            | 8626                        | Desktop     | [b04d9fcad9](https://linux-hardware.org/?probe=b04d9fcad9) | Dec 22, 2023 |
| ASUSTek       | M3702WFA                    | All in one  | [9091136a65](https://linux-hardware.org/?probe=9091136a65) | Dec 22, 2023 |
| Lenovo        | ThinkPad T480 20L5004HUS    | Notebook    | [10c32df82e](https://linux-hardware.org/?probe=10c32df82e) | Dec 22, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [ec4972e3b4](https://linux-hardware.org/?probe=ec4972e3b4) | Dec 22, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [6f47019169](https://linux-hardware.org/?probe=6f47019169) | Dec 22, 2023 |
| Dell          | 0D4MD1 A00                  | Desktop     | [858b84769f](https://linux-hardware.org/?probe=858b84769f) | Dec 22, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [8a2d46dced](https://linux-hardware.org/?probe=8a2d46dced) | Dec 22, 2023 |
| Allview       | Allbook I/1                 | Notebook    | [960dfde4cd](https://linux-hardware.org/?probe=960dfde4cd) | Dec 22, 2023 |
| Dell          | Latitude 5414               | Notebook    | [9b02eedb05](https://linux-hardware.org/?probe=9b02eedb05) | Dec 22, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [d2c7d30632](https://linux-hardware.org/?probe=d2c7d30632) | Dec 22, 2023 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | Notebook    | [60690b9d12](https://linux-hardware.org/?probe=60690b9d12) | Dec 22, 2023 |
| LattePanda    | Sigma                       | Desktop     | [09cb864933](https://linux-hardware.org/?probe=09cb864933) | Dec 22, 2023 |
| Toshiba       | Satellite C55D-B            | Notebook    | [d705d8ee57](https://linux-hardware.org/?probe=d705d8ee57) | Dec 22, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [5f1c04a086](https://linux-hardware.org/?probe=5f1c04a086) | Dec 22, 2023 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [2af66f541d](https://linux-hardware.org/?probe=2af66f541d) | Dec 22, 2023 |
| Entroware     | Hybris                      | Notebook    | [870d0c5323](https://linux-hardware.org/?probe=870d0c5323) | Dec 22, 2023 |
| Dell          | Latitude 5501               | Notebook    | [0b6206153c](https://linux-hardware.org/?probe=0b6206153c) | Dec 22, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [1f9d486306](https://linux-hardware.org/?probe=1f9d486306) | Dec 22, 2023 |
| Supermicro    | X8DTH                       | Server      | [e00e89ffec](https://linux-hardware.org/?probe=e00e89ffec) | Dec 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [3ff2f289b9](https://linux-hardware.org/?probe=3ff2f289b9) | Dec 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [9e521ad3e9](https://linux-hardware.org/?probe=9e521ad3e9) | Dec 22, 2023 |
| Acer          | Aspire A515-44              | Notebook    | [874744ee1f](https://linux-hardware.org/?probe=874744ee1f) | Dec 22, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [1767c5b291](https://linux-hardware.org/?probe=1767c5b291) | Dec 21, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [dbc2e93666](https://linux-hardware.org/?probe=dbc2e93666) | Dec 21, 2023 |
| LG Electro... | 17U70Q-P.AAS7U1             | Notebook    | [8846a0ac06](https://linux-hardware.org/?probe=8846a0ac06) | Dec 21, 2023 |
| Dell          | Latitude E6440              | Notebook    | [904540fc01](https://linux-hardware.org/?probe=904540fc01) | Dec 21, 2023 |
| Dell          | Inspiron 3541               | Notebook    | [67f350fefc](https://linux-hardware.org/?probe=67f350fefc) | Dec 21, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [b3c6d4826f](https://linux-hardware.org/?probe=b3c6d4826f) | Dec 21, 2023 |
| ASRock        | A520M-HDV                   | Desktop     | [918677a1da](https://linux-hardware.org/?probe=918677a1da) | Dec 21, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [3441fd68be](https://linux-hardware.org/?probe=3441fd68be) | Dec 21, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [628ca02992](https://linux-hardware.org/?probe=628ca02992) | Dec 21, 2023 |
| ASUSTek       | M3702WFA                    | All in one  | [a6d6ecda48](https://linux-hardware.org/?probe=a6d6ecda48) | Dec 21, 2023 |
| ASRock        | A520M-HDV                   | Desktop     | [7136ba3916](https://linux-hardware.org/?probe=7136ba3916) | Dec 21, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [907851c66b](https://linux-hardware.org/?probe=907851c66b) | Dec 21, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [c5c9d669ae](https://linux-hardware.org/?probe=c5c9d669ae) | Dec 21, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [7a1001a094](https://linux-hardware.org/?probe=7a1001a094) | Dec 21, 2023 |
| Dell          | Precision 3581              | Notebook    | [aa0186ade6](https://linux-hardware.org/?probe=aa0186ade6) | Dec 21, 2023 |
| HP            | ProBook 445 14 inch G10 ... | Notebook    | [0e95b32d0b](https://linux-hardware.org/?probe=0e95b32d0b) | Dec 21, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [808fe0568d](https://linux-hardware.org/?probe=808fe0568d) | Dec 21, 2023 |
| Dell          | Inspiron 15 3535            | Notebook    | [466204d787](https://linux-hardware.org/?probe=466204d787) | Dec 21, 2023 |
| Fujitsu       | LIFEBOOK U749               | Notebook    | [75a3ef28b0](https://linux-hardware.org/?probe=75a3ef28b0) | Dec 21, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [f95bb7d27c](https://linux-hardware.org/?probe=f95bb7d27c) | Dec 21, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [49e514e9c4](https://linux-hardware.org/?probe=49e514e9c4) | Dec 21, 2023 |
| Intel         | NUC7i5BNB J31144-309        | Mini pc     | [75c700e92a](https://linux-hardware.org/?probe=75c700e92a) | Dec 21, 2023 |
| Acer          | Aspire XC-1760              | Desktop     | [ac3910a453](https://linux-hardware.org/?probe=ac3910a453) | Dec 21, 2023 |
| Fujitsu       | LIFEBOOK T5010              | Notebook    | [27e7d6f705](https://linux-hardware.org/?probe=27e7d6f705) | Dec 21, 2023 |
| Dell          | Latitude 7490               | Notebook    | [d0ea360540](https://linux-hardware.org/?probe=d0ea360540) | Dec 21, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [d8e473e1e4](https://linux-hardware.org/?probe=d8e473e1e4) | Dec 21, 2023 |
| HP            | Pavilion dv7                | Notebook    | [ef719917ef](https://linux-hardware.org/?probe=ef719917ef) | Dec 21, 2023 |
| Supermicro    | H13DSG-O-CPU                | Desktop     | [1ba9d3bc0c](https://linux-hardware.org/?probe=1ba9d3bc0c) | Dec 21, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [0cf7feafe8](https://linux-hardware.org/?probe=0cf7feafe8) | Dec 21, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [ebaf3f3e71](https://linux-hardware.org/?probe=ebaf3f3e71) | Dec 21, 2023 |
| Supermicro    | H13DSG-O-CPU                | Desktop     | [066ebdde5b](https://linux-hardware.org/?probe=066ebdde5b) | Dec 21, 2023 |
| Neousys Te... | NVS-10000 Rev. A2           | Server      | [cde616cde3](https://linux-hardware.org/?probe=cde616cde3) | Dec 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [ec0a846182](https://linux-hardware.org/?probe=ec0a846182) | Dec 21, 2023 |
| HP            | Notebook                    | Notebook    | [9010ced489](https://linux-hardware.org/?probe=9010ced489) | Dec 21, 2023 |
| Dell          | Inspiron 5448               | Notebook    | [edf818740d](https://linux-hardware.org/?probe=edf818740d) | Dec 21, 2023 |
| Lenovo        | ThinkPad 20FRS22T00         | Convertible | [d52b91f681](https://linux-hardware.org/?probe=d52b91f681) | Dec 21, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [e3a45d6095](https://linux-hardware.org/?probe=e3a45d6095) | Dec 21, 2023 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [191d4913cd](https://linux-hardware.org/?probe=191d4913cd) | Dec 21, 2023 |
| Lenovo        | ThinkPad 20FRS22T00         | Convertible | [1d07dbc740](https://linux-hardware.org/?probe=1d07dbc740) | Dec 21, 2023 |
| Dell          | OptiPlex 5050               | Desktop     | [c1cffe744f](https://linux-hardware.org/?probe=c1cffe744f) | Dec 21, 2023 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Convertible | [d14a2228a1](https://linux-hardware.org/?probe=d14a2228a1) | Dec 21, 2023 |
| HP            | Compaq 15                   | Notebook    | [e97b5e227e](https://linux-hardware.org/?probe=e97b5e227e) | Dec 21, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [735572694e](https://linux-hardware.org/?probe=735572694e) | Dec 21, 2023 |
| HP            | Pavilion dv7                | Notebook    | [cd7f768fe8](https://linux-hardware.org/?probe=cd7f768fe8) | Dec 21, 2023 |
| HP            | 18E7                        | Desktop     | [ad6cf02d18](https://linux-hardware.org/?probe=ad6cf02d18) | Dec 21, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [e36c36774e](https://linux-hardware.org/?probe=e36c36774e) | Dec 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [46c4d5053b](https://linux-hardware.org/?probe=46c4d5053b) | Dec 21, 2023 |
| HP            | 18E7                        | Desktop     | [fdb8b2d229](https://linux-hardware.org/?probe=fdb8b2d229) | Dec 21, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [8eca3c15e7](https://linux-hardware.org/?probe=8eca3c15e7) | Dec 21, 2023 |
| ASRock        | Z77 Pro4                    | Desktop     | [d8d81bc3e2](https://linux-hardware.org/?probe=d8d81bc3e2) | Dec 21, 2023 |
| ASUSTek       | Z10PG-D16 Series            | Desktop     | [6b3c6c4099](https://linux-hardware.org/?probe=6b3c6c4099) | Dec 21, 2023 |
| Dell          | Latitude E6520              | Notebook    | [9e16e8b2a6](https://linux-hardware.org/?probe=9e16e8b2a6) | Dec 21, 2023 |
| MSI           | NF725M-P43                  | Desktop     | [43756d6fad](https://linux-hardware.org/?probe=43756d6fad) | Dec 21, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [bc65f1d620](https://linux-hardware.org/?probe=bc65f1d620) | Dec 21, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [2c9d7daa8b](https://linux-hardware.org/?probe=2c9d7daa8b) | Dec 21, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [93a7029d22](https://linux-hardware.org/?probe=93a7029d22) | Dec 21, 2023 |
| Dell          | Inspiron 7572               | Notebook    | [cd9385a64b](https://linux-hardware.org/?probe=cd9385a64b) | Dec 21, 2023 |
| Lenovo        | ThinkPad L580 20LW0010GE    | Notebook    | [4bd3fc58a8](https://linux-hardware.org/?probe=4bd3fc58a8) | Dec 21, 2023 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [8116f31329](https://linux-hardware.org/?probe=8116f31329) | Dec 21, 2023 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [7597019eca](https://linux-hardware.org/?probe=7597019eca) | Dec 21, 2023 |
| Panasonic     | CF-19RDRCHH7                | Notebook    | [0e67081368](https://linux-hardware.org/?probe=0e67081368) | Dec 21, 2023 |
| HP            | Spectre x360 Convertible    | Convertible | [3aec09e469](https://linux-hardware.org/?probe=3aec09e469) | Dec 21, 2023 |
| DEXP          | Aquilon C14                 | Notebook    | [09cd71a27d](https://linux-hardware.org/?probe=09cd71a27d) | Dec 21, 2023 |
| ASRock        | H610M-HVS                   | Desktop     | [25b5c11ccc](https://linux-hardware.org/?probe=25b5c11ccc) | Dec 20, 2023 |
| In-S          | C116A                       | Notebook    | [ba252bb452](https://linux-hardware.org/?probe=ba252bb452) | Dec 20, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [fb91eaef3b](https://linux-hardware.org/?probe=fb91eaef3b) | Dec 20, 2023 |
| ASUSTek       | VM40B                       | Desktop     | [8deb79e86e](https://linux-hardware.org/?probe=8deb79e86e) | Dec 20, 2023 |
| Gigabyte      | B560M H                     | Desktop     | [6e7f8b2300](https://linux-hardware.org/?probe=6e7f8b2300) | Dec 20, 2023 |
| ASUSTek       | ROG Flow X16 GV601VI_GV6... | Convertible | [9c16cd82aa](https://linux-hardware.org/?probe=9c16cd82aa) | Dec 20, 2023 |
| Dell          | Latitude 5590               | Notebook    | [4f307c792f](https://linux-hardware.org/?probe=4f307c792f) | Dec 20, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [da159da872](https://linux-hardware.org/?probe=da159da872) | Dec 20, 2023 |
| Acer          | Aspire 6930G                | Notebook    | [3013bf91cd](https://linux-hardware.org/?probe=3013bf91cd) | Dec 20, 2023 |
| Acer          | Aspire 6930G                | Notebook    | [6bc25073be](https://linux-hardware.org/?probe=6bc25073be) | Dec 20, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [1da522781e](https://linux-hardware.org/?probe=1da522781e) | Dec 20, 2023 |
| Dell          | Latitude 7480               | Notebook    | [f080cc67aa](https://linux-hardware.org/?probe=f080cc67aa) | Dec 20, 2023 |
| HP            | Compaq 15                   | Notebook    | [8224a8ab3d](https://linux-hardware.org/?probe=8224a8ab3d) | Dec 20, 2023 |
| Dell          | Latitude 3520               | Notebook    | [7a4d520ba9](https://linux-hardware.org/?probe=7a4d520ba9) | Dec 20, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [35547b20b3](https://linux-hardware.org/?probe=35547b20b3) | Dec 20, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [393c13e870](https://linux-hardware.org/?probe=393c13e870) | Dec 20, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [09af8afa56](https://linux-hardware.org/?probe=09af8afa56) | Dec 20, 2023 |
| Toshiba       | Satellite C55D-B            | Notebook    | [dfd0e27118](https://linux-hardware.org/?probe=dfd0e27118) | Dec 20, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [64ec373e84](https://linux-hardware.org/?probe=64ec373e84) | Dec 20, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [f46e034f2c](https://linux-hardware.org/?probe=f46e034f2c) | Dec 20, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [e696fd9ae0](https://linux-hardware.org/?probe=e696fd9ae0) | Dec 20, 2023 |
| Gigabyte      | H81M-S                      | Desktop     | [5583555782](https://linux-hardware.org/?probe=5583555782) | Dec 20, 2023 |
| Gigabyte      | H81M-S                      | Desktop     | [eded3a5ce4](https://linux-hardware.org/?probe=eded3a5ce4) | Dec 20, 2023 |
| Lenovo        | ThinkPad T410 2537HN2       | Notebook    | [c268085f95](https://linux-hardware.org/?probe=c268085f95) | Dec 20, 2023 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [06984b497c](https://linux-hardware.org/?probe=06984b497c) | Dec 20, 2023 |
| Dell          | 0C522T A03                  | Desktop     | [7cd9f2379e](https://linux-hardware.org/?probe=7cd9f2379e) | Dec 20, 2023 |
| Dell          | Precision 5510              | Notebook    | [033bf69fdf](https://linux-hardware.org/?probe=033bf69fdf) | Dec 20, 2023 |
| ASUSTek       | Z97-PRO                     | Desktop     | [917d636ff9](https://linux-hardware.org/?probe=917d636ff9) | Dec 20, 2023 |
| Dell          | Precision 5510              | Notebook    | [a40fa883d2](https://linux-hardware.org/?probe=a40fa883d2) | Dec 20, 2023 |
| MSI           | H61M-E33                    | Desktop     | [ab39035cef](https://linux-hardware.org/?probe=ab39035cef) | Dec 20, 2023 |
| STONE COMP... | NOTCHA-286                  | Notebook    | [c931f0f65a](https://linux-hardware.org/?probe=c931f0f65a) | Dec 20, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | Notebook    | [71bc732b86](https://linux-hardware.org/?probe=71bc732b86) | Dec 20, 2023 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [58517da295](https://linux-hardware.org/?probe=58517da295) | Dec 20, 2023 |
| Dell          | G7 7700                     | Notebook    | [506de63cb5](https://linux-hardware.org/?probe=506de63cb5) | Dec 20, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | Notebook    | [5d14b45611](https://linux-hardware.org/?probe=5d14b45611) | Dec 20, 2023 |
| Lenovo        | ThinkPad T520 42404AU       | Notebook    | [2b29070879](https://linux-hardware.org/?probe=2b29070879) | Dec 20, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | Notebook    | [71d03541a9](https://linux-hardware.org/?probe=71d03541a9) | Dec 20, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [6f7295809b](https://linux-hardware.org/?probe=6f7295809b) | Dec 20, 2023 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [2b2e293dc4](https://linux-hardware.org/?probe=2b2e293dc4) | Dec 20, 2023 |
| System76      | Serval WS                   | Notebook    | [7475c97028](https://linux-hardware.org/?probe=7475c97028) | Dec 20, 2023 |
| Unknown       | Orange Pi 5B                | Soc         | [f809840436](https://linux-hardware.org/?probe=f809840436) | Dec 20, 2023 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [7aa12c94c1](https://linux-hardware.org/?probe=7aa12c94c1) | Dec 20, 2023 |
| Intel         | DH55TC AAE70932-206         | Desktop     | [3003aeb5a9](https://linux-hardware.org/?probe=3003aeb5a9) | Dec 20, 2023 |
| Supermicro    | X9DRD-7LN4F                 | Desktop     | [56a303c264](https://linux-hardware.org/?probe=56a303c264) | Dec 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [b45e149ce8](https://linux-hardware.org/?probe=b45e149ce8) | Dec 20, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [bb15070eb2](https://linux-hardware.org/?probe=bb15070eb2) | Dec 19, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [10470437db](https://linux-hardware.org/?probe=10470437db) | Dec 19, 2023 |
| Daten Tecn... | DT02-M4                     | Notebook    | [8f754589f6](https://linux-hardware.org/?probe=8f754589f6) | Dec 19, 2023 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [09ab03cdcd](https://linux-hardware.org/?probe=09ab03cdcd) | Dec 19, 2023 |
| ANGXUN        | X79-VG2 V1.3                | Desktop     | [532c5b5ddc](https://linux-hardware.org/?probe=532c5b5ddc) | Dec 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [dbbab5f96b](https://linux-hardware.org/?probe=dbbab5f96b) | Dec 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [775e2dfe26](https://linux-hardware.org/?probe=775e2dfe26) | Dec 19, 2023 |
| Gigabyte      | Z790 UD                     | Desktop     | [94a40a476d](https://linux-hardware.org/?probe=94a40a476d) | Dec 19, 2023 |
| Google        | Swanky                      | Notebook    | [46b7f27873](https://linux-hardware.org/?probe=46b7f27873) | Dec 19, 2023 |
| MSI           | B85-G43                     | Desktop     | [2c855d2376](https://linux-hardware.org/?probe=2c855d2376) | Dec 19, 2023 |
| Mediacom      | GTZS                        | Notebook    | [f326507469](https://linux-hardware.org/?probe=f326507469) | Dec 19, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [3cc3621576](https://linux-hardware.org/?probe=3cc3621576) | Dec 19, 2023 |
| Dell          | Precision 3581              | Notebook    | [c20f7cf0e0](https://linux-hardware.org/?probe=c20f7cf0e0) | Dec 19, 2023 |
| HUAWEI        | CREFG-XX                    | Notebook    | [b97589a2bc](https://linux-hardware.org/?probe=b97589a2bc) | Dec 19, 2023 |
| HUAWEI        | CREFG-XX                    | Notebook    | [5dd323e917](https://linux-hardware.org/?probe=5dd323e917) | Dec 19, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [20edb747d9](https://linux-hardware.org/?probe=20edb747d9) | Dec 19, 2023 |
| HP            | EliteBook 840 14 inch G1... | Notebook    | [2222f1a1fb](https://linux-hardware.org/?probe=2222f1a1fb) | Dec 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [1b5268d64f](https://linux-hardware.org/?probe=1b5268d64f) | Dec 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [1290fe8e5a](https://linux-hardware.org/?probe=1290fe8e5a) | Dec 19, 2023 |
| Dell          | Latitude E6510              | Notebook    | [e9aceddae8](https://linux-hardware.org/?probe=e9aceddae8) | Dec 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a4efec2a2c](https://linux-hardware.org/?probe=a4efec2a2c) | Dec 19, 2023 |
| Lenovo        | 330B SDK0T76530 WIN 3556... | Mini pc     | [97d6dd408b](https://linux-hardware.org/?probe=97d6dd408b) | Dec 19, 2023 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [f09218ee8f](https://linux-hardware.org/?probe=f09218ee8f) | Dec 19, 2023 |
| ASUSTek       | X450CC                      | Notebook    | [0af8e99fe6](https://linux-hardware.org/?probe=0af8e99fe6) | Dec 19, 2023 |
| ASUSTek       | X450CC                      | Notebook    | [238d032255](https://linux-hardware.org/?probe=238d032255) | Dec 19, 2023 |
| Dell          | 042P49 A02                  | Desktop     | [11f6da5848](https://linux-hardware.org/?probe=11f6da5848) | Dec 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [6f1ca9e563](https://linux-hardware.org/?probe=6f1ca9e563) | Dec 19, 2023 |
| Dell          | Precision M2800             | Notebook    | [8800042fb5](https://linux-hardware.org/?probe=8800042fb5) | Dec 19, 2023 |
| Acer          | Nitro ANV15-51              | Notebook    | [c4ddaa9bc4](https://linux-hardware.org/?probe=c4ddaa9bc4) | Dec 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [13072c9ecc](https://linux-hardware.org/?probe=13072c9ecc) | Dec 19, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [843515c201](https://linux-hardware.org/?probe=843515c201) | Dec 19, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [91c6527140](https://linux-hardware.org/?probe=91c6527140) | Dec 19, 2023 |
| Acer          | Nitro ANV15-51              | Notebook    | [aa343c3d4f](https://linux-hardware.org/?probe=aa343c3d4f) | Dec 19, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [1038e25caf](https://linux-hardware.org/?probe=1038e25caf) | Dec 19, 2023 |
| Dell          | 0C522T A03                  | Desktop     | [35b8611349](https://linux-hardware.org/?probe=35b8611349) | Dec 19, 2023 |
| ASUSTek       | H81-PLUS                    | Desktop     | [359af07cb2](https://linux-hardware.org/?probe=359af07cb2) | Dec 19, 2023 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [492194d1fc](https://linux-hardware.org/?probe=492194d1fc) | Dec 19, 2023 |
| ASUSTek       | H81-PLUS                    | Desktop     | [b4b91802b5](https://linux-hardware.org/?probe=b4b91802b5) | Dec 19, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [3cf8d970f8](https://linux-hardware.org/?probe=3cf8d970f8) | Dec 19, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [d41e584b48](https://linux-hardware.org/?probe=d41e584b48) | Dec 19, 2023 |
| Dell          | 0PJDGF A02                  | Desktop     | [cfdd125cd5](https://linux-hardware.org/?probe=cfdd125cd5) | Dec 19, 2023 |
| Dell          | 0PJDGF A02                  | Desktop     | [edcd06b95f](https://linux-hardware.org/?probe=edcd06b95f) | Dec 19, 2023 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [547d1bef1f](https://linux-hardware.org/?probe=547d1bef1f) | Dec 19, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [3a4a73b5f1](https://linux-hardware.org/?probe=3a4a73b5f1) | Dec 19, 2023 |
| Unknown       | X79                         | Desktop     | [167cf0a87f](https://linux-hardware.org/?probe=167cf0a87f) | Dec 19, 2023 |
| Unknown       | X79                         | Desktop     | [3961be9cb6](https://linux-hardware.org/?probe=3961be9cb6) | Dec 19, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [5781ca34c8](https://linux-hardware.org/?probe=5781ca34c8) | Dec 19, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [a2bb7b1e00](https://linux-hardware.org/?probe=a2bb7b1e00) | Dec 19, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [a2a69a3d09](https://linux-hardware.org/?probe=a2a69a3d09) | Dec 19, 2023 |
| HP            | 655                         | Notebook    | [c0bd13830f](https://linux-hardware.org/?probe=c0bd13830f) | Dec 19, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [2feb704b34](https://linux-hardware.org/?probe=2feb704b34) | Dec 19, 2023 |
| Dell          | 0Y7WYT A00                  | Desktop     | [705321d0b6](https://linux-hardware.org/?probe=705321d0b6) | Dec 19, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [4220452f9d](https://linux-hardware.org/?probe=4220452f9d) | Dec 18, 2023 |
| HP            | 3647h                       | Desktop     | [0e741d6d7c](https://linux-hardware.org/?probe=0e741d6d7c) | Dec 18, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [82be8c9bb4](https://linux-hardware.org/?probe=82be8c9bb4) | Dec 18, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [8ad076eb34](https://linux-hardware.org/?probe=8ad076eb34) | Dec 18, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [55a802f43c](https://linux-hardware.org/?probe=55a802f43c) | Dec 18, 2023 |
| Supermicro    | X7DWA                       | Desktop     | [2ea00dfda4](https://linux-hardware.org/?probe=2ea00dfda4) | Dec 18, 2023 |
| Acer          | Swift SF315-52G             | Notebook    | [26f06e876d](https://linux-hardware.org/?probe=26f06e876d) | Dec 18, 2023 |
| Supermicro    | X7DWA                       | Desktop     | [6357637f80](https://linux-hardware.org/?probe=6357637f80) | Dec 18, 2023 |
| Dell          | Latitude 3420               | Notebook    | [5fdda723cd](https://linux-hardware.org/?probe=5fdda723cd) | Dec 18, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [8f34c208f2](https://linux-hardware.org/?probe=8f34c208f2) | Dec 18, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [31b0444771](https://linux-hardware.org/?probe=31b0444771) | Dec 18, 2023 |
| Packard Be... | Veriton M275                | Desktop     | [2263820deb](https://linux-hardware.org/?probe=2263820deb) | Dec 18, 2023 |
| Dell          | 0NV0M7 A02                  | Desktop     | [577e6d8d0e](https://linux-hardware.org/?probe=577e6d8d0e) | Dec 18, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [923f390d62](https://linux-hardware.org/?probe=923f390d62) | Dec 18, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [83ef4dd286](https://linux-hardware.org/?probe=83ef4dd286) | Dec 18, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [f93e198dd4](https://linux-hardware.org/?probe=f93e198dd4) | Dec 18, 2023 |
| Acer          | Aspire E1-731               | Notebook    | [e5312bdd49](https://linux-hardware.org/?probe=e5312bdd49) | Dec 18, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [f0d39c9ef3](https://linux-hardware.org/?probe=f0d39c9ef3) | Dec 18, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [1232ff1050](https://linux-hardware.org/?probe=1232ff1050) | Dec 18, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [5976f16a69](https://linux-hardware.org/?probe=5976f16a69) | Dec 18, 2023 |
| Dell          | Latitude 5430               | Notebook    | [bce74a439e](https://linux-hardware.org/?probe=bce74a439e) | Dec 18, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [dd31f0d1ec](https://linux-hardware.org/?probe=dd31f0d1ec) | Dec 18, 2023 |
| Acer          | Aspire 8730                 | Notebook    | [c7b60bcb33](https://linux-hardware.org/?probe=c7b60bcb33) | Dec 18, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [498141a78c](https://linux-hardware.org/?probe=498141a78c) | Dec 18, 2023 |
| Toshiba       | Satellite C55-A             | Notebook    | [6c0f2ad0c9](https://linux-hardware.org/?probe=6c0f2ad0c9) | Dec 18, 2023 |
| Toshiba       | Satellite C55-A             | Notebook    | [0ae780878c](https://linux-hardware.org/?probe=0ae780878c) | Dec 18, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [8a224cfad3](https://linux-hardware.org/?probe=8a224cfad3) | Dec 18, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [0cf5577833](https://linux-hardware.org/?probe=0cf5577833) | Dec 18, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [0376612ef7](https://linux-hardware.org/?probe=0376612ef7) | Dec 18, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [45a0b94112](https://linux-hardware.org/?probe=45a0b94112) | Dec 18, 2023 |
| Dell          | Latitude 7440               | Notebook    | [644c46aba6](https://linux-hardware.org/?probe=644c46aba6) | Dec 18, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [2b7376d8a1](https://linux-hardware.org/?probe=2b7376d8a1) | Dec 18, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [458a8fb3f1](https://linux-hardware.org/?probe=458a8fb3f1) | Dec 18, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [100bef421f](https://linux-hardware.org/?probe=100bef421f) | Dec 18, 2023 |
| Dell          | 06FW8P A02                  | Desktop     | [7b66e504eb](https://linux-hardware.org/?probe=7b66e504eb) | Dec 18, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [2bee7533b2](https://linux-hardware.org/?probe=2bee7533b2) | Dec 18, 2023 |
| ASUSTek       | ROG Flow X16 GV601VI_GV6... | Convertible | [4065921cd4](https://linux-hardware.org/?probe=4065921cd4) | Dec 18, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [941f6d849a](https://linux-hardware.org/?probe=941f6d849a) | Dec 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [fcc1139818](https://linux-hardware.org/?probe=fcc1139818) | Dec 18, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [312fe4e212](https://linux-hardware.org/?probe=312fe4e212) | Dec 18, 2023 |
| Acer          | Aspire 5349                 | Notebook    | [f81cd33147](https://linux-hardware.org/?probe=f81cd33147) | Dec 18, 2023 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [054ed4fad9](https://linux-hardware.org/?probe=054ed4fad9) | Dec 18, 2023 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [0c3974dad9](https://linux-hardware.org/?probe=0c3974dad9) | Dec 18, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [f4412027d4](https://linux-hardware.org/?probe=f4412027d4) | Dec 18, 2023 |
| Medion        | E3216 MD61800               | Convertible | [c048f29733](https://linux-hardware.org/?probe=c048f29733) | Dec 18, 2023 |
| Medion        | E3216 MD61800               | Convertible | [fdc44cbae2](https://linux-hardware.org/?probe=fdc44cbae2) | Dec 18, 2023 |
| Gigabyte      | B550 GAMING X               | Desktop     | [6ecd3ce2c3](https://linux-hardware.org/?probe=6ecd3ce2c3) | Dec 18, 2023 |
| DTV           | G5A-BTJ1900                 | Other       | [f6c12e7381](https://linux-hardware.org/?probe=f6c12e7381) | Dec 18, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [bad7f51319](https://linux-hardware.org/?probe=bad7f51319) | Dec 18, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [c3968eb521](https://linux-hardware.org/?probe=c3968eb521) | Dec 18, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [ad8a2053bc](https://linux-hardware.org/?probe=ad8a2053bc) | Dec 17, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [d1dcdfda30](https://linux-hardware.org/?probe=d1dcdfda30) | Dec 17, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [4802066fc1](https://linux-hardware.org/?probe=4802066fc1) | Dec 17, 2023 |
| Lenovo        | ThinkPad T420 4180PR1       | Notebook    | [2c0267b77e](https://linux-hardware.org/?probe=2c0267b77e) | Dec 17, 2023 |
| Biostar       | B550MH                      | Desktop     | [32131b6631](https://linux-hardware.org/?probe=32131b6631) | Dec 17, 2023 |
| ASRock        | Z370M-ITX/ac                | Desktop     | [0f7c6a7383](https://linux-hardware.org/?probe=0f7c6a7383) | Dec 17, 2023 |
| ASRock        | Z390 Extreme4               | Desktop     | [4067f8d4cb](https://linux-hardware.org/?probe=4067f8d4cb) | Dec 17, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [8425b10899](https://linux-hardware.org/?probe=8425b10899) | Dec 17, 2023 |
| Biostar       | B550MH                      | Desktop     | [97d9affd9d](https://linux-hardware.org/?probe=97d9affd9d) | Dec 17, 2023 |
| Acer          | Aspire S7-391               | Notebook    | [ab734913e8](https://linux-hardware.org/?probe=ab734913e8) | Dec 17, 2023 |
| Acer          | Aspire S7-391               | Notebook    | [1d66b3f887](https://linux-hardware.org/?probe=1d66b3f887) | Dec 17, 2023 |
| Acer          | Swift SF315-41              | Notebook    | [300b426183](https://linux-hardware.org/?probe=300b426183) | Dec 17, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603VI... | Notebook    | [5a439f3bc5](https://linux-hardware.org/?probe=5a439f3bc5) | Dec 17, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [dbf9ec9380](https://linux-hardware.org/?probe=dbf9ec9380) | Dec 17, 2023 |
| HP            | ENVY Laptop 17-ch0xxx       | Notebook    | [43602a664e](https://linux-hardware.org/?probe=43602a664e) | Dec 17, 2023 |
| Lenovo        | ThinkPad W550s 20E2CTO1W... | Notebook    | [17b157ef44](https://linux-hardware.org/?probe=17b157ef44) | Dec 17, 2023 |
| Dell          | 05DN3X A00                  | Desktop     | [d14a1553b4](https://linux-hardware.org/?probe=d14a1553b4) | Dec 17, 2023 |
| Dell          | 0J1C3P A01                  | Desktop     | [99eb1f88a4](https://linux-hardware.org/?probe=99eb1f88a4) | Dec 17, 2023 |
| Dell          | 07N90W A02                  | Desktop     | [0c471e8b44](https://linux-hardware.org/?probe=0c471e8b44) | Dec 17, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [ead1dfb3ae](https://linux-hardware.org/?probe=ead1dfb3ae) | Dec 17, 2023 |
| ASRock        | H61M-VG4                    | Desktop     | [a845742a42](https://linux-hardware.org/?probe=a845742a42) | Dec 17, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [def7de5871](https://linux-hardware.org/?probe=def7de5871) | Dec 17, 2023 |
| Dell          | 02K9CR A02                  | Desktop     | [aeb868db71](https://linux-hardware.org/?probe=aeb868db71) | Dec 17, 2023 |
| Sony          | SVD1321L2EW                 | Notebook    | [b753425d70](https://linux-hardware.org/?probe=b753425d70) | Dec 17, 2023 |
| ASRock        | Z390 Extreme4               | Desktop     | [5db549dd99](https://linux-hardware.org/?probe=5db549dd99) | Dec 17, 2023 |
| Gigabyte      | Z790 UD                     | Desktop     | [bfe9651fbd](https://linux-hardware.org/?probe=bfe9651fbd) | Dec 17, 2023 |
| MSI           | 2A9C                        | Desktop     | [342d099a7f](https://linux-hardware.org/?probe=342d099a7f) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [78a88bfe8c](https://linux-hardware.org/?probe=78a88bfe8c) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [8833b0a058](https://linux-hardware.org/?probe=8833b0a058) | Dec 17, 2023 |
| Dell          | Vostro 3580                 | Notebook    | [90856c67e3](https://linux-hardware.org/?probe=90856c67e3) | Dec 17, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [dde306e444](https://linux-hardware.org/?probe=dde306e444) | Dec 17, 2023 |
| ASUSTek       | PRIME H510M-A WIFI          | Desktop     | [2335d46852](https://linux-hardware.org/?probe=2335d46852) | Dec 17, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [341ecee745](https://linux-hardware.org/?probe=341ecee745) | Dec 17, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | Notebook    | [987ab63f96](https://linux-hardware.org/?probe=987ab63f96) | Dec 17, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [d3e1291358](https://linux-hardware.org/?probe=d3e1291358) | Dec 17, 2023 |
| Lenovo        | ThinkPad A475 20KMS08300    | Notebook    | [b652245cca](https://linux-hardware.org/?probe=b652245cca) | Dec 17, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [1f0e0f04f8](https://linux-hardware.org/?probe=1f0e0f04f8) | Dec 17, 2023 |
| ASUSTek       | X456UB                      | Notebook    | [5a4a0662e1](https://linux-hardware.org/?probe=5a4a0662e1) | Dec 17, 2023 |
| HP            | 1790                        | Desktop     | [2d8c859110](https://linux-hardware.org/?probe=2d8c859110) | Dec 17, 2023 |
| Dell          | 03X6X0 A06                  | Server      | [65557703dc](https://linux-hardware.org/?probe=65557703dc) | Dec 17, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [91a9e2e8c4](https://linux-hardware.org/?probe=91a9e2e8c4) | Dec 17, 2023 |
| MSI           | PE70 6QE                    | Notebook    | [efc671c7c2](https://linux-hardware.org/?probe=efc671c7c2) | Dec 17, 2023 |
| MSI           | PE70 6QE                    | Notebook    | [c99e0d38ea](https://linux-hardware.org/?probe=c99e0d38ea) | Dec 17, 2023 |
| HP            | 2000                        | Notebook    | [3570eb7cd0](https://linux-hardware.org/?probe=3570eb7cd0) | Dec 17, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [e85c54f3fd](https://linux-hardware.org/?probe=e85c54f3fd) | Dec 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4c8c4e1c68](https://linux-hardware.org/?probe=4c8c4e1c68) | Dec 17, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [171e1a6bbb](https://linux-hardware.org/?probe=171e1a6bbb) | Dec 17, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [f84bfa5707](https://linux-hardware.org/?probe=f84bfa5707) | Dec 17, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [f04605f94c](https://linux-hardware.org/?probe=f04605f94c) | Dec 17, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [a77869199a](https://linux-hardware.org/?probe=a77869199a) | Dec 17, 2023 |
| HP            | Pavilion dv6                | Notebook    | [dd14fcb656](https://linux-hardware.org/?probe=dd14fcb656) | Dec 17, 2023 |
| Google        | Woomax                      | Notebook    | [7516d70c03](https://linux-hardware.org/?probe=7516d70c03) | Dec 17, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [8adfc82dc5](https://linux-hardware.org/?probe=8adfc82dc5) | Dec 17, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [d5632292b6](https://linux-hardware.org/?probe=d5632292b6) | Dec 17, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [6745d8d399](https://linux-hardware.org/?probe=6745d8d399) | Dec 17, 2023 |
| Lenovo        | ThinkPad W530 24491D1       | Notebook    | [bab70d44b1](https://linux-hardware.org/?probe=bab70d44b1) | Dec 17, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [a5e443e89c](https://linux-hardware.org/?probe=a5e443e89c) | Dec 17, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [1c0bbe412c](https://linux-hardware.org/?probe=1c0bbe412c) | Dec 17, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [253da93459](https://linux-hardware.org/?probe=253da93459) | Dec 17, 2023 |
| Samsung       | 930QED                      | Convertible | [90cf6b2c26](https://linux-hardware.org/?probe=90cf6b2c26) | Dec 17, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [de9dcb40ba](https://linux-hardware.org/?probe=de9dcb40ba) | Dec 17, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [6920e9d7c2](https://linux-hardware.org/?probe=6920e9d7c2) | Dec 17, 2023 |
| Dell          | Latitude E7440              | Notebook    | [35982f622e](https://linux-hardware.org/?probe=35982f622e) | Dec 17, 2023 |
| Dell          | 0PC5F7 A03                  | Desktop     | [b280c267db](https://linux-hardware.org/?probe=b280c267db) | Dec 17, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [492e654dfb](https://linux-hardware.org/?probe=492e654dfb) | Dec 17, 2023 |
| Shenzhen M... | TH80                        | Desktop     | [1ad9ee524d](https://linux-hardware.org/?probe=1ad9ee524d) | Dec 16, 2023 |
| LG Electro... | 16Z90R-A.ADC8U1             | Notebook    | [5ae89dd818](https://linux-hardware.org/?probe=5ae89dd818) | Dec 16, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [f46b47b272](https://linux-hardware.org/?probe=f46b47b272) | Dec 16, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [476c368866](https://linux-hardware.org/?probe=476c368866) | Dec 16, 2023 |
| Inventec      | DQ Class A02                | Desktop     | [73df6dfb3b](https://linux-hardware.org/?probe=73df6dfb3b) | Dec 16, 2023 |
| ASRock        | Z77 Pro4                    | Desktop     | [15ce6626f3](https://linux-hardware.org/?probe=15ce6626f3) | Dec 16, 2023 |
| Gigabyte      | B85-HD3-A                   | Desktop     | [e3d139cdb3](https://linux-hardware.org/?probe=e3d139cdb3) | Dec 16, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [646c403e2f](https://linux-hardware.org/?probe=646c403e2f) | Dec 16, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [7fc71d8954](https://linux-hardware.org/?probe=7fc71d8954) | Dec 16, 2023 |
| ASUSTek       | PRIME B760-PLUS             | Desktop     | [a7dd86011c](https://linux-hardware.org/?probe=a7dd86011c) | Dec 16, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [efe58ba5df](https://linux-hardware.org/?probe=efe58ba5df) | Dec 16, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [57a64ca85e](https://linux-hardware.org/?probe=57a64ca85e) | Dec 16, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [6e6dfdc457](https://linux-hardware.org/?probe=6e6dfdc457) | Dec 16, 2023 |
| ASUSTek       | PRIME H510M-A WIFI          | Desktop     | [e97f16f34e](https://linux-hardware.org/?probe=e97f16f34e) | Dec 16, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [e6019b847e](https://linux-hardware.org/?probe=e6019b847e) | Dec 16, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | Notebook    | [2167a2f148](https://linux-hardware.org/?probe=2167a2f148) | Dec 16, 2023 |
| HP            | 2B05                        | Desktop     | [81e68a1fb8](https://linux-hardware.org/?probe=81e68a1fb8) | Dec 16, 2023 |
| HP            | 2B05                        | Desktop     | [2063743d90](https://linux-hardware.org/?probe=2063743d90) | Dec 16, 2023 |
| ASUSTek       | Z97-PRO                     | Desktop     | [383682bb1f](https://linux-hardware.org/?probe=383682bb1f) | Dec 16, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [5f625c9177](https://linux-hardware.org/?probe=5f625c9177) | Dec 16, 2023 |
| Acer          | EG43M                       | Desktop     | [62c8e8acf8](https://linux-hardware.org/?probe=62c8e8acf8) | Dec 16, 2023 |
| HP            | 1790                        | Desktop     | [9bb2d6fcb4](https://linux-hardware.org/?probe=9bb2d6fcb4) | Dec 16, 2023 |
| Acer          | Aspire 6930G                | Notebook    | [3e93a62792](https://linux-hardware.org/?probe=3e93a62792) | Dec 16, 2023 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [862ce85408](https://linux-hardware.org/?probe=862ce85408) | Dec 16, 2023 |
| ASUSTek       | Z97-PRO                     | Desktop     | [a0e9f7ca57](https://linux-hardware.org/?probe=a0e9f7ca57) | Dec 16, 2023 |
| Lenovo        | ThinkPad T420 4238AW2       | Notebook    | [01fae631cf](https://linux-hardware.org/?probe=01fae631cf) | Dec 16, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [8297f20357](https://linux-hardware.org/?probe=8297f20357) | Dec 16, 2023 |
| Allview       | Allbook H                   | Notebook    | [2da4fcb35c](https://linux-hardware.org/?probe=2da4fcb35c) | Dec 16, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [22d7c1e77c](https://linux-hardware.org/?probe=22d7c1e77c) | Dec 16, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [e9f2e211bd](https://linux-hardware.org/?probe=e9f2e211bd) | Dec 16, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [109311067f](https://linux-hardware.org/?probe=109311067f) | Dec 16, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [5614a9077e](https://linux-hardware.org/?probe=5614a9077e) | Dec 16, 2023 |
| Dell          | 0RT6HT A01                  | Desktop     | [3509be8560](https://linux-hardware.org/?probe=3509be8560) | Dec 16, 2023 |
| Lenovo        | V17 G3 IAP 82U1             | Notebook    | [2598a81fd9](https://linux-hardware.org/?probe=2598a81fd9) | Dec 16, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [6458d64d28](https://linux-hardware.org/?probe=6458d64d28) | Dec 16, 2023 |
| Lenovo        | IdeaPad S400 20195          | Notebook    | [f4c6ceeca3](https://linux-hardware.org/?probe=f4c6ceeca3) | Dec 16, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [7b3d7fcb72](https://linux-hardware.org/?probe=7b3d7fcb72) | Dec 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [026638d09e](https://linux-hardware.org/?probe=026638d09e) | Dec 16, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [251ac554a9](https://linux-hardware.org/?probe=251ac554a9) | Dec 16, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [dc5e6d8ad5](https://linux-hardware.org/?probe=dc5e6d8ad5) | Dec 16, 2023 |
| MSI           | PRO Z790-A MAX WIFI         | Desktop     | [2832959c86](https://linux-hardware.org/?probe=2832959c86) | Dec 16, 2023 |
| MSI           | PRO Z790-A MAX WIFI         | Desktop     | [01f18b5c6f](https://linux-hardware.org/?probe=01f18b5c6f) | Dec 16, 2023 |
| Dell          | Precision 5540              | Notebook    | [ff22e47089](https://linux-hardware.org/?probe=ff22e47089) | Dec 16, 2023 |
| HP            | Notebook                    | Notebook    | [5bbbe8e356](https://linux-hardware.org/?probe=5bbbe8e356) | Dec 16, 2023 |
| Dell          | 0RY007                      | Desktop     | [162add826a](https://linux-hardware.org/?probe=162add826a) | Dec 16, 2023 |
| ROMBICA       | myBook Discovery            | Notebook    | [c7b69fb478](https://linux-hardware.org/?probe=c7b69fb478) | Dec 16, 2023 |
| ASRock        | Z790 Taichi                 | Desktop     | [a27506c744](https://linux-hardware.org/?probe=a27506c744) | Dec 16, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [3f47a63c82](https://linux-hardware.org/?probe=3f47a63c82) | Dec 16, 2023 |
| ASRock        | Z790 Taichi                 | Desktop     | [9a257410d4](https://linux-hardware.org/?probe=9a257410d4) | Dec 16, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [933e5b48f2](https://linux-hardware.org/?probe=933e5b48f2) | Dec 16, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [9df7fd000e](https://linux-hardware.org/?probe=9df7fd000e) | Dec 16, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [12c5d1d331](https://linux-hardware.org/?probe=12c5d1d331) | Dec 16, 2023 |
| ASUSTek       | ROG STRIX B760-F GAMING ... | Desktop     | [f3938de13a](https://linux-hardware.org/?probe=f3938de13a) | Dec 16, 2023 |
| Medion        | E6417 MD99252               | Notebook    | [26e9c2ba0c](https://linux-hardware.org/?probe=26e9c2ba0c) | Dec 15, 2023 |
| MSI           | Katana GF66 11SC            | Notebook    | [1eb5b02078](https://linux-hardware.org/?probe=1eb5b02078) | Dec 15, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [5c1d3d831c](https://linux-hardware.org/?probe=5c1d3d831c) | Dec 15, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [73a2cddbca](https://linux-hardware.org/?probe=73a2cddbca) | Dec 15, 2023 |
| Lenovo        | IdeaPad 320-17IKB 81BJ      | Notebook    | [2d3b97c04a](https://linux-hardware.org/?probe=2d3b97c04a) | Dec 15, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [199ffa8815](https://linux-hardware.org/?probe=199ffa8815) | Dec 15, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [7f648e3b6e](https://linux-hardware.org/?probe=7f648e3b6e) | Dec 15, 2023 |
| Dell          | Latitude 7490               | Notebook    | [a5431ec5e0](https://linux-hardware.org/?probe=a5431ec5e0) | Dec 15, 2023 |
| VIA Techno... | AMOS-3005                   | Desktop     | [10cf5bf932](https://linux-hardware.org/?probe=10cf5bf932) | Dec 15, 2023 |
| VIA Techno... | AMOS-3005                   | Desktop     | [0af62d144a](https://linux-hardware.org/?probe=0af62d144a) | Dec 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5223e586fd](https://linux-hardware.org/?probe=5223e586fd) | Dec 15, 2023 |
| Lenovo        | B590 62742QG                | Notebook    | [edb1cd89f6](https://linux-hardware.org/?probe=edb1cd89f6) | Dec 15, 2023 |
| MSI           | Thin GF63 12HW              | Notebook    | [47f661e72c](https://linux-hardware.org/?probe=47f661e72c) | Dec 15, 2023 |
| Gigabyte      | B85-HD3-A                   | Desktop     | [b60d191f59](https://linux-hardware.org/?probe=b60d191f59) | Dec 15, 2023 |
| VIT           | M2400-01                    | Mini pc     | [8c80d8ce0c](https://linux-hardware.org/?probe=8c80d8ce0c) | Dec 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [9e63ff66cb](https://linux-hardware.org/?probe=9e63ff66cb) | Dec 15, 2023 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [1fae1d3423](https://linux-hardware.org/?probe=1fae1d3423) | Dec 15, 2023 |
| HP            | Pavilion g6                 | Notebook    | [7863fae702](https://linux-hardware.org/?probe=7863fae702) | Dec 15, 2023 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [1a70a13ff4](https://linux-hardware.org/?probe=1a70a13ff4) | Dec 15, 2023 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [8be30808ec](https://linux-hardware.org/?probe=8be30808ec) | Dec 15, 2023 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [1e0ba866f7](https://linux-hardware.org/?probe=1e0ba866f7) | Dec 15, 2023 |
| Shenzhen M... | F7BSC                       | Mini pc     | [1b9fdf3844](https://linux-hardware.org/?probe=1b9fdf3844) | Dec 15, 2023 |
| HP            | Notebook                    | Notebook    | [26c91fe276](https://linux-hardware.org/?probe=26c91fe276) | Dec 15, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [638a0b8c0c](https://linux-hardware.org/?probe=638a0b8c0c) | Dec 15, 2023 |
| Trigkey       | S5 V2.0                     | Mini pc     | [90a7a3db53](https://linux-hardware.org/?probe=90a7a3db53) | Dec 15, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [20a11e4c01](https://linux-hardware.org/?probe=20a11e4c01) | Dec 15, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [035b37d481](https://linux-hardware.org/?probe=035b37d481) | Dec 15, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [618978da16](https://linux-hardware.org/?probe=618978da16) | Dec 15, 2023 |
| Acer          | Aspire 8730                 | Notebook    | [5f7e5fbfd8](https://linux-hardware.org/?probe=5f7e5fbfd8) | Dec 15, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [6ef649e844](https://linux-hardware.org/?probe=6ef649e844) | Dec 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b7194dbbb8](https://linux-hardware.org/?probe=b7194dbbb8) | Dec 15, 2023 |
| Acer          | Aspire 8730                 | Notebook    | [8e1f3c1aa9](https://linux-hardware.org/?probe=8e1f3c1aa9) | Dec 15, 2023 |
| HP            | Laptop 17-bs1xx             | Notebook    | [ef29718fd5](https://linux-hardware.org/?probe=ef29718fd5) | Dec 15, 2023 |
| Google        | Guado                       | Desktop     | [e981ac3399](https://linux-hardware.org/?probe=e981ac3399) | Dec 15, 2023 |
| ASRock        | H570 Phantom Gaming 4       | Desktop     | [b942870c3a](https://linux-hardware.org/?probe=b942870c3a) | Dec 15, 2023 |
| Gigabyte      | Z790 UD                     | Desktop     | [77da8f68cd](https://linux-hardware.org/?probe=77da8f68cd) | Dec 15, 2023 |
| Gigabyte      | MZAPLBP-00                  | Desktop     | [3935358dce](https://linux-hardware.org/?probe=3935358dce) | Dec 15, 2023 |
| XDO.AI        | Pantera Pico PC             | Desktop     | [6358b586ac](https://linux-hardware.org/?probe=6358b586ac) | Dec 15, 2023 |
| ASRock        | H310CM-HDV/M.2              | Desktop     | [c3604a3f0d](https://linux-hardware.org/?probe=c3604a3f0d) | Dec 15, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [92b42d7c3e](https://linux-hardware.org/?probe=92b42d7c3e) | Dec 15, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [051090b9e0](https://linux-hardware.org/?probe=051090b9e0) | Dec 15, 2023 |
| Gigabyte      | Z790 AORUS MASTER           | Desktop     | [6af7c135e1](https://linux-hardware.org/?probe=6af7c135e1) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [d8db62d461](https://linux-hardware.org/?probe=d8db62d461) | Dec 15, 2023 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | Notebook    | [a0eaa74105](https://linux-hardware.org/?probe=a0eaa74105) | Dec 15, 2023 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | Notebook    | [db4a7dea97](https://linux-hardware.org/?probe=db4a7dea97) | Dec 15, 2023 |
| HP            | Pavilion 15                 | Notebook    | [166f55ae0b](https://linux-hardware.org/?probe=166f55ae0b) | Dec 15, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [7e43febcae](https://linux-hardware.org/?probe=7e43febcae) | Dec 15, 2023 |
| Lenovo        | IdeaPad Slim 3 14AMN8 82... | Notebook    | [e4542af709](https://linux-hardware.org/?probe=e4542af709) | Dec 15, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [9fa07d2004](https://linux-hardware.org/?probe=9fa07d2004) | Dec 14, 2023 |
| MSI           | Creator Z16P B12UGST        | Notebook    | [fff0011dec](https://linux-hardware.org/?probe=fff0011dec) | Dec 14, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JNC... | Notebook    | [46fbc450b5](https://linux-hardware.org/?probe=46fbc450b5) | Dec 14, 2023 |
| HP            | ProBook 6450b               | Notebook    | [f63d5aa0f6](https://linux-hardware.org/?probe=f63d5aa0f6) | Dec 14, 2023 |
| HP            | ProBook 6450b               | Notebook    | [1a762fe797](https://linux-hardware.org/?probe=1a762fe797) | Dec 14, 2023 |
| HP            | EliteBook 8530w             | Notebook    | [6ce01d863a](https://linux-hardware.org/?probe=6ce01d863a) | Dec 14, 2023 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [5dca430907](https://linux-hardware.org/?probe=5dca430907) | Dec 14, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [eb487bbab2](https://linux-hardware.org/?probe=eb487bbab2) | Dec 14, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [435c0197d1](https://linux-hardware.org/?probe=435c0197d1) | Dec 14, 2023 |
| Dell          | Latitude E5450              | Notebook    | [b616faa68f](https://linux-hardware.org/?probe=b616faa68f) | Dec 14, 2023 |
| TECHNOPC      | NANO 5                      | Desktop     | [3ac9d2eb32](https://linux-hardware.org/?probe=3ac9d2eb32) | Dec 14, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [b95f42f691](https://linux-hardware.org/?probe=b95f42f691) | Dec 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [9fb745d9fe](https://linux-hardware.org/?probe=9fb745d9fe) | Dec 14, 2023 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [48c963a11d](https://linux-hardware.org/?probe=48c963a11d) | Dec 14, 2023 |
| Google        | Guado                       | Desktop     | [50ceaa2515](https://linux-hardware.org/?probe=50ceaa2515) | Dec 14, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0HC0... | Notebook    | [3aa9eb82fb](https://linux-hardware.org/?probe=3aa9eb82fb) | Dec 14, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [9609ed5138](https://linux-hardware.org/?probe=9609ed5138) | Dec 14, 2023 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [b537ee14db](https://linux-hardware.org/?probe=b537ee14db) | Dec 14, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | Desktop     | [742681b576](https://linux-hardware.org/?probe=742681b576) | Dec 14, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | Desktop     | [72cd581273](https://linux-hardware.org/?probe=72cd581273) | Dec 14, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [49278a194a](https://linux-hardware.org/?probe=49278a194a) | Dec 14, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [7f788f5265](https://linux-hardware.org/?probe=7f788f5265) | Dec 14, 2023 |
| XDO.AI        | Pantera Pico PC             | Desktop     | [fabfe15230](https://linux-hardware.org/?probe=fabfe15230) | Dec 14, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [d4d42016ea](https://linux-hardware.org/?probe=d4d42016ea) | Dec 14, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [74030d2ce6](https://linux-hardware.org/?probe=74030d2ce6) | Dec 14, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [ac8fb0b18d](https://linux-hardware.org/?probe=ac8fb0b18d) | Dec 14, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [56b77e5a7d](https://linux-hardware.org/?probe=56b77e5a7d) | Dec 14, 2023 |
| Lenovo        | ThinkPad T480 20L6S0U302    | Notebook    | [163493b62b](https://linux-hardware.org/?probe=163493b62b) | Dec 14, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [101f8237e0](https://linux-hardware.org/?probe=101f8237e0) | Dec 14, 2023 |
| Dell          | 0TDG4V A01                  | Desktop     | [6da01d5871](https://linux-hardware.org/?probe=6da01d5871) | Dec 14, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [877a0b72ab](https://linux-hardware.org/?probe=877a0b72ab) | Dec 14, 2023 |
| Dell          | Inspiron 16 5620            | Notebook    | [aac962ade2](https://linux-hardware.org/?probe=aac962ade2) | Dec 14, 2023 |
| Dell          | Inspiron 16 5620            | Notebook    | [85cb328b2d](https://linux-hardware.org/?probe=85cb328b2d) | Dec 14, 2023 |
| HP            | Laptop 17t-cn200            | Notebook    | [ffe76142c0](https://linux-hardware.org/?probe=ffe76142c0) | Dec 14, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [bfca25b6c1](https://linux-hardware.org/?probe=bfca25b6c1) | Dec 14, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [adbfbb8174](https://linux-hardware.org/?probe=adbfbb8174) | Dec 13, 2023 |
| ASUSTek       | T102HA                      | Tablet      | [0a2b707101](https://linux-hardware.org/?probe=0a2b707101) | Dec 13, 2023 |
| Acer          | TMP645-M                    | Notebook    | [bd22eef09b](https://linux-hardware.org/?probe=bd22eef09b) | Dec 13, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [9d0aff4b01](https://linux-hardware.org/?probe=9d0aff4b01) | Dec 13, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [e49be74129](https://linux-hardware.org/?probe=e49be74129) | Dec 13, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [1522c84fb7](https://linux-hardware.org/?probe=1522c84fb7) | Dec 13, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [9c3e8b880d](https://linux-hardware.org/?probe=9c3e8b880d) | Dec 13, 2023 |
| HP            | 83EF                        | Desktop     | [e2a7a03e4c](https://linux-hardware.org/?probe=e2a7a03e4c) | Dec 13, 2023 |
| HP            | 83EF                        | Desktop     | [d5d568c47c](https://linux-hardware.org/?probe=d5d568c47c) | Dec 13, 2023 |
| Sony          | VAIO                        | All in one  | [26d923a8b0](https://linux-hardware.org/?probe=26d923a8b0) | Dec 13, 2023 |
| HP            | 829A                        | Mini pc     | [4a18e66bdc](https://linux-hardware.org/?probe=4a18e66bdc) | Dec 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [ab0ac93be6](https://linux-hardware.org/?probe=ab0ac93be6) | Dec 13, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [e70de29c90](https://linux-hardware.org/?probe=e70de29c90) | Dec 13, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [f845d7a88e](https://linux-hardware.org/?probe=f845d7a88e) | Dec 13, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [c266418637](https://linux-hardware.org/?probe=c266418637) | Dec 13, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [de6e3bf0eb](https://linux-hardware.org/?probe=de6e3bf0eb) | Dec 13, 2023 |
| Lenovo        | ThinkPad X201 3626W1P       | Notebook    | [bf54dfd215](https://linux-hardware.org/?probe=bf54dfd215) | Dec 13, 2023 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [9d192a95d8](https://linux-hardware.org/?probe=9d192a95d8) | Dec 13, 2023 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [19e6b5a871](https://linux-hardware.org/?probe=19e6b5a871) | Dec 13, 2023 |
| LG Electro... | 16Z90R-G.AA76G              | Notebook    | [1e83ee89e2](https://linux-hardware.org/?probe=1e83ee89e2) | Dec 13, 2023 |
| HP            | 18E9                        | Desktop     | [ab47a5d40b](https://linux-hardware.org/?probe=ab47a5d40b) | Dec 13, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [e196db2480](https://linux-hardware.org/?probe=e196db2480) | Dec 13, 2023 |
| Unknown       | Unknown                     | Soc         | [abf8ea1275](https://linux-hardware.org/?probe=abf8ea1275) | Dec 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [4a5e5bbe29](https://linux-hardware.org/?probe=4a5e5bbe29) | Dec 13, 2023 |
| Unknown       | Unknown                     | Soc         | [4d27eccf69](https://linux-hardware.org/?probe=4d27eccf69) | Dec 13, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d3eea6ef7f](https://linux-hardware.org/?probe=d3eea6ef7f) | Dec 13, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [6e8b956266](https://linux-hardware.org/?probe=6e8b956266) | Dec 13, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [e198c73fa2](https://linux-hardware.org/?probe=e198c73fa2) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [f18bd26311](https://linux-hardware.org/?probe=f18bd26311) | Dec 13, 2023 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [cdcd6ddfc6](https://linux-hardware.org/?probe=cdcd6ddfc6) | Dec 13, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [963ff854d9](https://linux-hardware.org/?probe=963ff854d9) | Dec 13, 2023 |
| Lenovo        | ThinkPad 11e Yoga Gen 6 ... | Convertible | [95aecca331](https://linux-hardware.org/?probe=95aecca331) | Dec 13, 2023 |
| Lenovo        | ThinkPad 11e Yoga Gen 6 ... | Convertible | [7b3b853705](https://linux-hardware.org/?probe=7b3b853705) | Dec 13, 2023 |
| Lenovo        | ThinkPad 11e Yoga Gen 6 ... | Convertible | [d0cf4bc853](https://linux-hardware.org/?probe=d0cf4bc853) | Dec 13, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [01915c7894](https://linux-hardware.org/?probe=01915c7894) | Dec 13, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [a8d24008e2](https://linux-hardware.org/?probe=a8d24008e2) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [ed5de838eb](https://linux-hardware.org/?probe=ed5de838eb) | Dec 13, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Ubuntu 20.04    | 25650     | 37.49%  |
| Ubuntu 22.04    | 13712     | 20.04%  |
| Ubuntu 18.04    | 13179     | 19.26%  |
| Ubuntu 20.10    | 2231      | 3.26%   |
| Ubuntu 21.10    | 2094      | 3.06%   |
| Ubuntu 19.10    | 2057      | 3.01%   |
| Ubuntu 19.04    | 1903      | 2.78%   |
| Ubuntu 21.04    | 1778      | 2.6%    |
| Ubuntu 22.10    | 1633      | 2.39%   |
| Ubuntu 23.04    | 1610      | 2.35%   |
| Ubuntu 18.10    | 856       | 1.25%   |
| Ubuntu 16.04    | 758       | 1.11%   |
| Ubuntu 23.10    | 674       | 0.99%   |
| Ubuntu          | 73        | 0.11%   |
| Ubuntu 17.10    | 56        | 0.08%   |
| Ubuntu Core 16  | 41        | 0.06%   |
| Ubuntu Core 18  | 34        | 0.05%   |
| Ubuntu 14.04    | 19        | 0.03%   |
| Ubuntu 24.04    | 14        | 0.02%   |
| Ubuntu Core 22  | 13        | 0.02%   |
| Ubuntu 17.04    | 6         | 0.01%   |
| Ubuntu 18.08    | 5         | 0.01%   |
| Ubuntu Core 20  | 3         | 0.004%  |
| Ubuntu 16.10    | 3         | 0.004%  |
| Ubuntu 12.04    | 3         | 0.004%  |
| Ubuntu 9.5      | 1         | 0.001%  |
| Ubuntu 6.1      | 1         | 0.001%  |
| Ubuntu 6.0      | 1         | 0.001%  |
| Ubuntu 6        | 1         | 0.001%  |
| Ubuntu 21.12    | 1         | 0.001%  |
| Ubuntu 2023.3   | 1         | 0.001%  |
| Ubuntu 20.08.3  | 1         | 0.001%  |
| Ubuntu 20.04.3  | 1         | 0.001%  |
| Ubuntu 19.1     | 1         | 0.001%  |
| Ubuntu 18.08.39 | 1         | 0.001%  |
| Ubuntu 18.08.38 | 1         | 0.001%  |
| Ubuntu 18.08.36 | 1         | 0.001%  |
| Ubuntu 18.08.34 | 1         | 0.001%  |
| Ubuntu 10.04    | 1         | 0.001%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Ubuntu | 64942     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 2519      | 3.26%   |
| 5.4.0-26-generic  | 1022      | 1.32%   |
| 5.4.0-48-generic  | 1020      | 1.32%   |
| 5.4.0-29-generic  | 992       | 1.29%   |
| 5.4.0-52-generic  | 971       | 1.26%   |
| 5.15.0-56-generic | 909       | 1.18%   |
| 5.4.0-40-generic  | 849       | 1.1%    |
| 5.8.0-43-generic  | 848       | 1.1%    |
| 5.4.0-58-generic  | 832       | 1.08%   |
| 5.4.0-37-generic  | 777       | 1.01%   |
| 5.15.0-52-generic | 769       | 1%      |
| 6.2.0-26-generic  | 761       | 0.99%   |
| 5.15.0-58-generic | 718       | 0.93%   |
| 5.19.0-35-generic | 711       | 0.92%   |
| 5.3.0-40-generic  | 686       | 0.89%   |
| 5.11.0-27-generic | 677       | 0.88%   |
| 5.4.0-33-generic  | 671       | 0.87%   |
| 5.8.0-50-generic  | 642       | 0.83%   |
| 5.15.0-43-generic | 642       | 0.83%   |
| 5.8.0-44-generic  | 617       | 0.8%    |
| 5.19.0-38-generic | 617       | 0.8%    |
| 5.3.0-46-generic  | 614       | 0.8%    |
| 5.15.0-46-generic | 608       | 0.79%   |
| 5.15.0-48-generic | 606       | 0.79%   |
| 5.4.0-54-generic  | 603       | 0.78%   |
| 5.11.0-37-generic | 592       | 0.77%   |
| 5.4.0-31-generic  | 573       | 0.74%   |
| 5.19.0-32-generic | 571       | 0.74%   |
| 5.4.0-47-generic  | 565       | 0.73%   |
| 6.2.0-20-generic  | 560       | 0.73%   |
| 5.8.0-48-generic  | 558       | 0.72%   |
| 5.11.0-38-generic | 552       | 0.72%   |
| 5.0.0-23-generic  | 538       | 0.7%    |
| 5.0.0-37-generic  | 519       | 0.67%   |
| 5.19.0-46-generic | 512       | 0.66%   |
| 4.18.0-15-generic | 511       | 0.66%   |
| 5.11.0-40-generic | 500       | 0.65%   |
| 5.15.0-47-generic | 492       | 0.64%   |
| 5.13.0-39-generic | 487       | 0.63%   |
| 5.3.0-28-generic  | 486       | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.0    | 15787     | 22.33%  |
| 5.15.0   | 9141      | 12.93%  |
| 5.8.0    | 6732      | 9.52%   |
| 4.15.0   | 6054      | 8.56%   |
| 5.11.0   | 5183      | 7.33%   |
| 5.19.0   | 4780      | 6.76%   |
| 6.2.0    | 4412      | 6.24%   |
| 5.3.0    | 4358      | 6.17%   |
| 5.13.0   | 4230      | 5.98%   |
| 5.0.0    | 3866      | 5.47%   |
| 4.18.0   | 2700      | 3.82%   |
| 6.5.0    | 679       | 0.96%   |
| 4.4.0    | 286       | 0.4%    |
| 5.14.0   | 204       | 0.29%   |
| 5.10.0   | 127       | 0.18%   |
| 5.17.0   | 104       | 0.15%   |
| 4.13.0   | 101       | 0.14%   |
| 5.6.0    | 80        | 0.11%   |
| 6.1.0    | 56        | 0.08%   |
| 6.0.0    | 42        | 0.06%   |
| 5.9.0    | 33        | 0.05%   |
| 4.10.0   | 29        | 0.04%   |
| 5.7.1    | 27        | 0.04%   |
| 6.0.9    | 23        | 0.03%   |
| 5.18.0   | 22        | 0.03%   |
| 4.9.140  | 20        | 0.03%   |
| 6.4.0    | 19        | 0.03%   |
| 5.12.0   | 19        | 0.03%   |
| 6.3.0    | 18        | 0.03%   |
| 5.7.0    | 18        | 0.03%   |
| 5.2.0    | 17        | 0.02%   |
| 5.16.0   | 17        | 0.02%   |
| 4.19.0   | 17        | 0.02%   |
| 6.2.11   | 14        | 0.02%   |
| 5.19.5   | 14        | 0.02%   |
| 5.10.2   | 13        | 0.02%   |
| 4.8.0    | 13        | 0.02%   |
| 5.17.1   | 12        | 0.02%   |
| 5.15.2   | 12        | 0.02%   |
| 5.10.110 | 12        | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 15840     | 22.43%  |
| 5.15    | 9223      | 13.06%  |
| 5.8     | 6797      | 9.62%   |
| 4.15    | 6062      | 8.58%   |
| 5.11    | 5222      | 7.39%   |
| 5.19    | 4818      | 6.82%   |
| 6.2     | 4493      | 6.36%   |
| 5.3     | 4373      | 6.19%   |
| 5.13    | 4270      | 6.05%   |
| 5.0     | 3905      | 5.53%   |
| 4.18    | 2709      | 3.84%   |
| 6.5     | 716       | 1.01%   |
| 4.4     | 294       | 0.42%   |
| 5.10    | 251       | 0.36%   |
| 5.14    | 239       | 0.34%   |
| 5.17    | 160       | 0.23%   |
| 6.1     | 120       | 0.17%   |
| 5.6     | 117       | 0.17%   |
| 4.13    | 104       | 0.15%   |
| 6.0     | 103       | 0.15%   |
| 5.9     | 82        | 0.12%   |
| 5.7     | 80        | 0.11%   |
| 6.4     | 61        | 0.09%   |
| 6.3     | 61        | 0.09%   |
| 5.18    | 57        | 0.08%   |
| 4.19    | 50        | 0.07%   |
| 5.16    | 46        | 0.07%   |
| 4.9     | 46        | 0.07%   |
| 5.1     | 44        | 0.06%   |
| 5.12    | 42        | 0.06%   |
| 5.2     | 40        | 0.06%   |
| 5.5     | 38        | 0.05%   |
| 4.10    | 30        | 0.04%   |
| 6.6     | 28        | 0.04%   |
| 4.16    | 18        | 0.03%   |
| 4.8     | 15        | 0.02%   |
| 4.20    | 14        | 0.02%   |
| 4.17    | 11        | 0.02%   |
| 4.14    | 11        | 0.02%   |
| 3.13    | 10        | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 63185     | 97.28%  |
| i686    | 1046      | 1.61%   |
| aarch64 | 666       | 1.03%   |
| armv7l  | 45        | 0.07%   |
| Unknown | 3         | 0.005%  |
| riscv64 | 2         | 0.003%  |
| s390x   | 1         | 0.002%  |
| i586    | 1         | 0.002%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 50913     | 76.92%  |
| Unknown           | 13768     | 20.8%   |
| X-Cinnamon        | 480       | 0.73%   |
| GNOME Flashback   | 394       | 0.6%    |
| Cinnamon          | 166       | 0.25%   |
| GNUstep           | 156       | 0.24%   |
| i3                | 85        | 0.13%   |
| GNOME Classic     | 58        | 0.09%   |
| Enlightenment     | 53        | 0.08%   |
| awesome           | 17        | 0.03%   |
| openbox           | 14        | 0.02%   |
| sway              | 12        | 0.02%   |
| xubuntu           | 7         | 0.01%   |
| Pantheon          | 7         | 0.01%   |
| Lubuntu           | 7         | 0.01%   |
| Deepin            | 7         | 0.01%   |
| Yaru:ubuntu:GNOME | 5         | 0.01%   |
| DWM               | 5         | 0.01%   |
| xmonad            | 3         | 0.005%  |
| ubuntu            | 3         | 0.005%  |
| Trinity           | 3         | 0.005%  |
| ubuntustudio      | 2         | 0.003%  |
| mwm               | 2         | 0.003%  |
| ICEWM             | 2         | 0.003%  |
| fvwm              | 2         | 0.003%  |
| fluxbox           | 2         | 0.003%  |
| Cutefish          | 2         | 0.003%  |
| Core              | 2         | 0.003%  |
| bspwm             | 2         | 0.003%  |
| xsession          | 1         | 0.002%  |
| wmaker-common     | 1         | 0.002%  |
| ubuntu=GNOME      | 1         | 0.002%  |
| ratflow           | 1         | 0.002%  |
| kde               | 1         | 0.002%  |
| INPT              | 1         | 0.002%  |
| i3-with-shmlog    | 1         | 0.002%  |
| DDE               | 1         | 0.002%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 43672     | 64.87%  |
| Wayland     | 14545     | 21.6%   |
| Unknown     | 8009      | 11.9%   |
| Tty         | 1089      | 1.62%   |
| Web         | 7         | 0.01%   |
| Unspecified | 1         | 0.001%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 35612     | 53.21%  |
| GDM3    | 21192     | 31.66%  |
| GDM     | 8876      | 13.26%  |
| LightDM | 851       | 1.27%   |
| TDM     | 257       | 0.38%   |
| SDDM    | 105       | 0.16%   |
| SLiM    | 21        | 0.03%   |
| XDM     | 5         | 0.01%   |
| LXDM    | 3         | 0.004%  |
| NODM    | 2         | 0.003%  |
| Ly      | 2         | 0.003%  |
| GREETD  | 1         | 0.001%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 23850     | 36.1%   |
| Unknown | 10243     | 15.51%  |
| de_DE   | 5003      | 7.57%   |
| fr_FR   | 3231      | 4.89%   |
| en_GB   | 2763      | 4.18%   |
| pt_BR   | 2470      | 3.74%   |
| it_IT   | 1819      | 2.75%   |
| en_IN   | 1649      | 2.5%    |
| ru_RU   | 1556      | 2.36%   |
| es_ES   | 1462      | 2.21%   |
| en_CA   | 1333      | 2.02%   |
| C       | 1211      | 1.83%   |
| pl_PL   | 869       | 1.32%   |
| en_AU   | 855       | 1.29%   |
| nl_NL   | 579       | 0.88%   |
| hu_HU   | 391       | 0.59%   |
| cs_CZ   | 382       | 0.58%   |
| es_MX   | 375       | 0.57%   |
| es_AR   | 327       | 0.5%    |
| zh_CN   | 316       | 0.48%   |
| en_ZA   | 316       | 0.48%   |
| ja_JP   | 309       | 0.47%   |
| de_AT   | 269       | 0.41%   |
| pt_PT   | 253       | 0.38%   |
| tr_TR   | 239       | 0.36%   |
| sv_SE   | 233       | 0.35%   |
| de_CH   | 185       | 0.28%   |
| fi_FI   | 180       | 0.27%   |
| es_CO   | 162       | 0.25%   |
| en_IL   | 149       | 0.23%   |
| en_NZ   | 148       | 0.22%   |
| fr_CA   | 146       | 0.22%   |
| es_CL   | 146       | 0.22%   |
| el_GR   | 140       | 0.21%   |
| ru_UA   | 137       | 0.21%   |
| fr_BE   | 127       | 0.19%   |
| ko_KR   | 121       | 0.18%   |
| da_DK   | 121       | 0.18%   |
| ro_RO   | 119       | 0.18%   |
| en_IE   | 105       | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 36535     | 55.11%  |
| EFI  | 29765     | 44.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type          | Computers | Percent |
|---------------|-----------|---------|
| Ext4          | 55859     | 84.6%   |
| Tmpfs         | 4476      | 6.78%   |
| Overlay       | 2017      | 3.05%   |
| Unknown       | 1370      | 2.07%   |
| Zfs           | 892       | 1.35%   |
| Btrfs         | 697       | 1.06%   |
| Ext2          | 293       | 0.44%   |
| Xfs           | 215       | 0.33%   |
| Ext3          | 166       | 0.25%   |
| Aufs          | 20        | 0.03%   |
| Jfs           | 8         | 0.01%   |
| Reiserfs      | 7         | 0.01%   |
| XXX4          | 3         | 0.005%  |
| XXXXXXX       | 1         | 0.002%  |
| XXXX          | 1         | 0.002%  |
| SquXshfs      | 1         | 0.002%  |
| Nfs           | 1         | 0.002%  |
| Lvm           | 1         | 0.002%  |
| Fuse.snapfuse | 1         | 0.002%  |
| F2fs          | 1         | 0.002%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 40621     | 61.24%  |
| GPT     | 21901     | 33.02%  |
| MBR     | 3806      | 5.74%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 57629     | 87.42%  |
| Yes       | 8292      | 12.58%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 40985     | 62.16%  |
| Yes       | 24949     | 37.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 10017     | 15.42%  |
| Dell                    | 9693      | 14.93%  |
| Hewlett-Packard         | 9454      | 14.56%  |
| Lenovo                  | 8571      | 13.2%   |
| Gigabyte Technology     | 3912      | 6.02%   |
| Acer                    | 3517      | 5.42%   |
| MSI                     | 3367      | 5.18%   |
| ASRock                  | 1966      | 3.03%   |
| Apple                   | 1509      | 2.32%   |
| Intel                   | 1304      | 2.01%   |
| Toshiba                 | 1101      | 1.7%    |
| Samsung Electronics     | 757       | 1.17%   |
| Unknown                 | 620       | 0.95%   |
| Fujitsu                 | 578       | 0.89%   |
| Sony                    | 576       | 0.89%   |
| Raspberry Pi Foundation | 559       | 0.86%   |
| HUAWEI                  | 458       | 0.71%   |
| Supermicro              | 376       | 0.58%   |
| Medion                  | 361       | 0.56%   |
| Pegatron                | 293       | 0.45%   |
| Foxconn                 | 266       | 0.41%   |
| Packard Bell            | 247       | 0.38%   |
| Positivo                | 240       | 0.37%   |
| Microsoft               | 235       | 0.36%   |
| Biostar                 | 219       | 0.34%   |
| Notebook                | 206       | 0.32%   |
| Alienware               | 189       | 0.29%   |
| ECS                     | 188       | 0.29%   |
| Google                  | 185       | 0.28%   |
| Fujitsu Siemens         | 155       | 0.24%   |
| Timi                    | 152       | 0.23%   |
| Gateway                 | 139       | 0.21%   |
| AMI                     | 125       | 0.19%   |
| LG Electronics          | 119       | 0.18%   |
| TUXEDO                  | 89        | 0.14%   |
| Chuwi                   | 89        | 0.14%   |
| eMachines               | 85        | 0.13%   |
| System76                | 84        | 0.13%   |
| AZW                     | 84        | 0.13%   |
| Clevo                   | 77        | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 824       | 1.27%   |
| ASUS All Series                    | 639       | 0.98%   |
| RPi Raspberry Pi                   | 295       | 0.45%   |
| HP Notebook                        | 276       | 0.42%   |
| HP Pavilion dv6                    | 170       | 0.26%   |
| Dell OptiPlex 7010                 | 163       | 0.25%   |
| HP Pavilion g6                     | 148       | 0.23%   |
| HP Pavilion dv7                    | 122       | 0.19%   |
| HP Pavilion Notebook               | 114       | 0.18%   |
| ASUS PRIME A320M-K                 | 114       | 0.18%   |
| HP Pavilion 15                     | 105       | 0.16%   |
| Dell OptiPlex 9020                 | 102       | 0.16%   |
| Dell XPS 15 7590                   | 99        | 0.15%   |
| Dell OptiPlex 790                  | 98        | 0.15%   |
| MSI MS-7C37                        | 96        | 0.15%   |
| Dell Latitude E6420                | 95        | 0.15%   |
| Dell Latitude E6410                | 95        | 0.15%   |
| Gigabyte B450M DS3H                | 90        | 0.14%   |
| Dell XPS 15 9570                   | 89        | 0.14%   |
| Dell OptiPlex 780                  | 86        | 0.13%   |
| MSI MS-7C02                        | 84        | 0.13%   |
| HP EliteBook 840 G3                | 84        | 0.13%   |
| Dell Inspiron 15-3567              | 84        | 0.13%   |
| HP 15                              | 83        | 0.13%   |
| Dell Latitude E6430                | 83        | 0.13%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 81        | 0.12%   |
| MSI MS-7721                        | 78        | 0.12%   |
| ASUS TUF Gaming X570-PLUS          | 78        | 0.12%   |
| Apple MacBookPro9,2                | 78        | 0.12%   |
| Supermicro Super Server            | 77        | 0.12%   |
| ASUS M5A78L-M/USB3                 | 76        | 0.12%   |
| Dell XPS 13 9370                   | 74        | 0.11%   |
| Dell OptiPlex 3020                 | 74        | 0.11%   |
| HP Compaq Elite 8300 SFF           | 73        | 0.11%   |
| Dell XPS 13 7390                   | 73        | 0.11%   |
| Dell Latitude E6400                | 73        | 0.11%   |
| Dell Inspiron 5570                 | 73        | 0.11%   |
| HP Laptop 15-bs0xx                 | 71        | 0.11%   |
| Dell XPS 15 9500                   | 71        | 0.11%   |
| HP Laptop 15-db0xxx                | 69        | 0.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 3675      | 5.66%   |
| Dell Inspiron      | 2464      | 3.79%   |
| Acer Aspire        | 2396      | 3.69%   |
| Dell Latitude      | 2305      | 3.55%   |
| HP Pavilion        | 1694      | 2.61%   |
| Lenovo IdeaPad     | 1644      | 2.53%   |
| Dell OptiPlex      | 1374      | 2.12%   |
| HP EliteBook       | 1291      | 1.99%   |
| Dell XPS           | 1122      | 1.73%   |
| ASUS PRIME         | 1043      | 1.61%   |
| HP ProBook         | 978       | 1.51%   |
| Dell Precision     | 972       | 1.5%    |
| Toshiba Satellite  | 921       | 1.42%   |
| HP Compaq          | 899       | 1.38%   |
| HP Laptop          | 882       | 1.36%   |
| Unknown            | 824       | 1.27%   |
| ASUS ROG           | 818       | 1.26%   |
| ASUS VivoBook      | 662       | 1.02%   |
| ASUS All           | 639       | 0.98%   |
| Dell Vostro        | 618       | 0.95%   |
| Lenovo ThinkCentre | 614       | 0.95%   |
| RPi Raspberry      | 558       | 0.86%   |
| ASUS TUF           | 492       | 0.76%   |
| HP ENVY            | 468       | 0.72%   |
| Lenovo Yoga        | 378       | 0.58%   |
| Acer Swift         | 290       | 0.45%   |
| HP Notebook        | 278       | 0.43%   |
| HP ZBook           | 261       | 0.4%    |
| ASUS ZenBook       | 261       | 0.4%    |
| Lenovo Legion      | 251       | 0.39%   |
| Dell PowerEdge     | 246       | 0.38%   |
| Lenovo ThinkBook   | 242       | 0.37%   |
| Fujitsu LIFEBOOK   | 236       | 0.36%   |
| Microsoft Surface  | 235       | 0.36%   |
| HP EliteDesk       | 220       | 0.34%   |
| ASUS M5A78L-M      | 220       | 0.34%   |
| Fujitsu ESPRIMO    | 194       | 0.3%    |
| Acer Nitro         | 192       | 0.3%    |
| HP ProLiant        | 184       | 0.28%   |
| HP ProDesk         | 174       | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 6135      | 9.45%   |
| 2019    | 5641      | 8.69%   |
| 2012    | 5529      | 8.51%   |
| 2011    | 4963      | 7.64%   |
| 2020    | 4895      | 7.54%   |
| 2013    | 4727      | 7.28%   |
| 2017    | 4450      | 6.85%   |
| 2014    | 3909      | 6.02%   |
| 2010    | 3621      | 5.58%   |
| 2015    | 3451      | 5.31%   |
| 2021    | 3429      | 5.28%   |
| 2016    | 3276      | 5.04%   |
| 2009    | 2729      | 4.2%    |
| 2008    | 2653      | 4.09%   |
| 2022    | 1768      | 2.72%   |
| 2007    | 1627      | 2.51%   |
| Unknown | 633       | 0.97%   |
| 2006    | 624       | 0.96%   |
| 2023    | 592       | 0.91%   |
| 2005    | 219       | 0.34%   |
| 2004    | 51        | 0.08%   |
| 2003    | 8         | 0.01%   |
| 2002    | 7         | 0.01%   |
| 2001    | 4         | 0.01%   |
| 2000    | 1         | 0.002%  |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 35066     | 54%     |
| Desktop        | 24198     | 37.26%  |
| Convertible    | 1615      | 2.49%   |
| Mini pc        | 960       | 1.48%   |
| Server         | 916       | 1.41%   |
| All in one     | 900       | 1.39%   |
| System on chip | 703       | 1.08%   |
| Tablet         | 580       | 0.89%   |
| Stick pc       | 2         | 0.003%  |
| Other          | 1         | 0.002%  |
| Firewall       | 1         | 0.002%  |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 58468     | 89.27%  |
| Enabled  | 7026      | 10.73%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 64689     | 99.61%  |
| Yes  | 253       | 0.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 15297     | 23.23%  |
| 3.01-4.0        | 13535     | 20.55%  |
| 16.01-24.0      | 12832     | 19.48%  |
| 8.01-16.0       | 11673     | 17.72%  |
| 32.01-64.0      | 5649      | 8.58%   |
| 1.01-2.0        | 2506      | 3.8%    |
| 64.01-256.0     | 1968      | 2.99%   |
| 24.01-32.0      | 1002      | 1.52%   |
| 2.01-3.0        | 906       | 1.38%   |
| 0.51-1.0        | 269       | 0.41%   |
| More than 256.0 | 193       | 0.29%   |
| 0.01-0.5        | 27        | 0.04%   |
| Unknown         | 5         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 26397     | 37.16%  |
| 2.01-3.0        | 20182     | 28.41%  |
| 4.01-8.0        | 9417      | 13.26%  |
| 3.01-4.0        | 9150      | 12.88%  |
| 8.01-16.0       | 2620      | 3.69%   |
| 0.51-1.0        | 2163      | 3.04%   |
| 0.01-0.5        | 395       | 0.56%   |
| 16.01-24.0      | 370       | 0.52%   |
| 24.01-32.0      | 142       | 0.2%    |
| 32.01-64.0      | 124       | 0.17%   |
| 64.01-256.0     | 52        | 0.07%   |
| Unknown         | 19        | 0.03%   |
| More than 256.0 | 5         | 0.01%   |
| 0               | 2         | 0.003%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 41831     | 62.69%  |
| 2       | 15775     | 23.64%  |
| 3       | 4416      | 6.62%   |
| 4       | 1914      | 2.87%   |
| 0       | 894       | 1.34%   |
| 5       | 864       | 1.29%   |
| 6       | 431       | 0.65%   |
| 7       | 217       | 0.33%   |
| 8       | 93        | 0.14%   |
| 9       | 73        | 0.11%   |
| Unknown | 58        | 0.09%   |
| 10      | 42        | 0.06%   |
| 11      | 37        | 0.06%   |
| 13      | 17        | 0.03%   |
| 12      | 11        | 0.02%   |
| 17      | 7         | 0.01%   |
| 16      | 6         | 0.01%   |
| 20      | 5         | 0.01%   |
| 25      | 4         | 0.01%   |
| 18      | 4         | 0.01%   |
| 14      | 4         | 0.01%   |
| 36      | 3         | 0.004%  |
| 21      | 3         | 0.004%  |
| 32      | 2         | 0.003%  |
| 15      | 2         | 0.003%  |
| 101     | 1         | 0.001%  |
| 87      | 1         | 0.001%  |
| 45      | 1         | 0.001%  |
| 40      | 1         | 0.001%  |
| 38      | 1         | 0.001%  |
| 27      | 1         | 0.001%  |
| 26      | 1         | 0.001%  |
| 24      | 1         | 0.001%  |
| 23      | 1         | 0.001%  |
| 22      | 1         | 0.001%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 38218     | 58.39%  |
| Yes       | 27234     | 41.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 56245     | 86.4%   |
| No        | 8853      | 13.6%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 48664     | 74.47%  |
| No        | 16681     | 25.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 36771     | 55.93%  |
| No        | 28969     | 44.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 11450     | 17.55%  |
| Germany      | 7084      | 10.86%  |
| Brazil       | 4096      | 6.28%   |
| France       | 3926      | 6.02%   |
| UK           | 2895      | 4.44%   |
| Italy        | 2828      | 4.33%   |
| Russia       | 2549      | 3.91%   |
| India        | 2100      | 3.22%   |
| Canada       | 2072      | 3.18%   |
| Spain        | 2035      | 3.12%   |
| Netherlands  | 1491      | 2.29%   |
| Poland       | 1453      | 2.23%   |
| Australia    | 1068      | 1.64%   |
| Switzerland  | 930       | 1.43%   |
| Mexico       | 796       | 1.22%   |
| Sweden       | 728       | 1.12%   |
| Czechia      | 714       | 1.09%   |
| Belgium      | 704       | 1.08%   |
| Ukraine      | 703       | 1.08%   |
| Austria      | 667       | 1.02%   |
| Turkey       | 665       | 1.02%   |
| Hungary      | 662       | 1.01%   |
| Argentina    | 658       | 1.01%   |
| China        | 565       | 0.87%   |
| Portugal     | 551       | 0.84%   |
| Romania      | 541       | 0.83%   |
| Japan        | 504       | 0.77%   |
| Finland      | 486       | 0.74%   |
| Greece       | 464       | 0.71%   |
| Indonesia    | 416       | 0.64%   |
| South Africa | 415       | 0.64%   |
| Denmark      | 373       | 0.57%   |
| Norway       | 368       | 0.56%   |
| Colombia     | 355       | 0.54%   |
| Bulgaria     | 326       | 0.5%    |
| Chile        | 315       | 0.48%   |
| Iran         | 309       | 0.47%   |
| Israel       | 296       | 0.45%   |
| Taiwan       | 268       | 0.41%   |
| Serbia       | 256       | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 791       | 1.14%   |
| Berlin            | 699       | 1.01%   |
| Paris             | 614       | 0.89%   |
| Sao Paulo         | 536       | 0.77%   |
| Rome              | 385       | 0.56%   |
| Vienna            | 375       | 0.54%   |
| Milan             | 372       | 0.54%   |
| Warsaw            | 366       | 0.53%   |
| Madrid            | 352       | 0.51%   |
| St Petersburg     | 343       | 0.5%    |
| Munich            | 342       | 0.49%   |
| Budapest          | 297       | 0.43%   |
| Hamburg           | 287       | 0.41%   |
| Zurich            | 282       | 0.41%   |
| Sydney            | 279       | 0.4%    |
| Prague            | 276       | 0.4%    |
| Barcelona         | 273       | 0.39%   |
| Bengaluru         | 263       | 0.38%   |
| Istanbul          | 256       | 0.37%   |
| Athens            | 254       | 0.37%   |
| Kyiv              | 244       | 0.35%   |
| Melbourne         | 243       | 0.35%   |
| Amsterdam         | 243       | 0.35%   |
| Rio de Janeiro    | 242       | 0.35%   |
| Toronto           | 228       | 0.33%   |
| Helsinki          | 228       | 0.33%   |
| Montreal          | 222       | 0.32%   |
| Frankfurt am Main | 205       | 0.3%    |
| Sofia             | 190       | 0.27%   |
| Tehran            | 184       | 0.27%   |
| Bucharest         | 183       | 0.26%   |
| New York          | 180       | 0.26%   |
| Buenos Aires      | 179       | 0.26%   |
| Singapore         | 176       | 0.25%   |
| London            | 172       | 0.25%   |
| Stuttgart         | 166       | 0.24%   |
| Chicago           | 163       | 0.24%   |
| Mexico City       | 160       | 0.23%   |
| Mumbai            | 159       | 0.23%   |
| Chennai           | 158       | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 14152     | 21629  | 15.82%  |
| WDC                         | 14141     | 21326  | 15.81%  |
| Samsung Electronics         | 13478     | 19364  | 15.07%  |
| Toshiba                     | 6322      | 8265   | 7.07%   |
| Kingston                    | 4701      | 5956   | 5.26%   |
| SanDisk                     | 4431      | 5780   | 4.95%   |
| Unknown                     | 3749      | 4944   | 4.19%   |
| Hitachi                     | 3111      | 4074   | 3.48%   |
| Crucial                     | 2755      | 3788   | 3.08%   |
| Intel                       | 2326      | 3257   | 2.6%    |
| SK hynix                    | 2310      | 2820   | 2.58%   |
| HGST                        | 1778      | 2415   | 1.99%   |
| Micron Technology           | 1423      | 1733   | 1.59%   |
| A-DATA Technology           | 1128      | 1398   | 1.26%   |
| Apple                       | 676       | 840    | 0.76%   |
| KIOXIA                      | 660       | 801    | 0.74%   |
| China                       | 641       | 784    | 0.72%   |
| Phison                      | 600       | 793    | 0.67%   |
| Fujitsu                     | 450       | 695    | 0.5%    |
| PNY                         | 441       | 547    | 0.49%   |
| Maxtor                      | 419       | 565    | 0.47%   |
| SPCC                        | 411       | 551    | 0.46%   |
| Silicon Motion              | 410       | 528    | 0.46%   |
| Intenso                     | 403       | 558    | 0.45%   |
| LITEON                      | 394       | 478    | 0.44%   |
| OCZ                         | 367       | 461    | 0.41%   |
| Transcend                   | 341       | 397    | 0.38%   |
| Micron/Crucial Technology   | 321       | 414    | 0.36%   |
| Patriot                     | 270       | 338    | 0.3%    |
| Corsair                     | 258       | 340    | 0.29%   |
| Unknown                     | 250       | 287    | 0.28%   |
| Phison Electronics          | 243       | 313    | 0.27%   |
| JMicron Technology          | 230       | 264    | 0.26%   |
| Hewlett-Packard             | 218       | 419    | 0.24%   |
| GOODRAM                     | 212       | 289    | 0.24%   |
| LITEONIT                    | 199       | 242    | 0.22%   |
| ASMT                        | 179       | 266    | 0.2%    |
| Team                        | 172       | 221    | 0.19%   |
| Kingston Technology Company | 172       | 217    | 0.19%   |
| Apacer                      | 139       | 159    | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 974       | 1%      |
| Seagate ST1000LM035-1RK172 1TB                      | 883       | 0.9%    |
| Seagate ST500DM002-1BD142 500GB                     | 755       | 0.77%   |
| Unknown MMC Card  32GB                              | 726       | 0.74%   |
| Samsung SSD 860 EVO 500GB                           | 724       | 0.74%   |
| Toshiba MQ01ABD100 1TB                              | 716       | 0.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 690       | 0.71%   |
| Samsung SSD 850 EVO 250GB                           | 653       | 0.67%   |
| Kingston SA400S37120G 120GB SSD                     | 600       | 0.61%   |
| Unknown MMC Card  64GB                              | 575       | 0.59%   |
| Kingston SA400S37480G 480GB SSD                     | 526       | 0.54%   |
| Seagate ST1000DM010-2EP102 1TB                      | 519       | 0.53%   |
| Samsung NVMe SSD Drive 512GB                        | 507       | 0.52%   |
| Samsung SSD 850 EVO 500GB                           | 498       | 0.51%   |
| Toshiba MQ01ABF050 500GB                            | 465       | 0.48%   |
| Toshiba MQ04ABF100 1TB                              | 459       | 0.47%   |
| Toshiba DT01ACA100 1TB                              | 426       | 0.44%   |
| Seagate ST500LT012-1DG142 500GB                     | 421       | 0.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 421       | 0.43%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 417       | 0.43%   |
| Kingston SV300S37A120G 120GB SSD                    | 412       | 0.42%   |
| HGST HTS721010A9E630 1TB                            | 404       | 0.41%   |
| Seagate ST2000DM008-2FR102 2TB                      | 392       | 0.4%    |
| Seagate ST9500325AS 500GB                           | 389       | 0.4%    |
| Samsung NVMe SSD Drive 500GB                        | 388       | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB                            | 383       | 0.39%   |
| Crucial CT500MX500SSD1 500GB                        | 383       | 0.39%   |
| SanDisk NVMe SSD Drive 512GB                        | 364       | 0.37%   |
| Samsung SSD 860 EVO 250GB                           | 361       | 0.37%   |
| Samsung SSD 860 EVO 1TB                             | 357       | 0.37%   |
| Seagate ST1000DM003-1CH162 1TB                      | 338       | 0.35%   |
| Unknown SD/MMC/MS PRO 512GB                         | 336       | 0.34%   |
| Crucial CT240BX500SSD1 240GB                        | 335       | 0.34%   |
| Seagate ST3500418AS 500GB                           | 330       | 0.34%   |
| Intel NVMe SSD Drive 512GB                          | 315       | 0.32%   |
| Unknown MMC Card  128GB                             | 311       | 0.32%   |
| Seagate Expansion 2TB                               | 280       | 0.29%   |
| Crucial CT1000MX500SSD1 1TB                         | 280       | 0.29%   |
| Seagate ST1000DM003-1ER162 1TB                      | 276       | 0.28%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 275       | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13905     | 21166  | 35.28%  |
| WDC                 | 11732     | 17909  | 29.77%  |
| Toshiba             | 4838      | 6310   | 12.28%  |
| Hitachi             | 3107      | 4069   | 7.88%   |
| Samsung Electronics | 1896      | 2634   | 4.81%   |
| HGST                | 1776      | 2385   | 4.51%   |
| Fujitsu             | 444       | 684    | 1.13%   |
| Maxtor              | 397       | 524    | 1.01%   |
| Unknown             | 366       | 475    | 0.93%   |
| Apple               | 220       | 242    | 0.56%   |
| SABRENT             | 108       | 138    | 0.27%   |
| Hewlett-Packard     | 69        | 157    | 0.18%   |
| Intenso             | 60        | 81     | 0.15%   |
| ASMT                | 55        | 113    | 0.14%   |
| TO Exter            | 49        | 59     | 0.12%   |
| External            | 45        | 60     | 0.11%   |
| USB3.0              | 28        | 31     | 0.07%   |
| JMicron Technology  | 26        | 40     | 0.07%   |
| ExcelStor           | 23        | 26     | 0.06%   |
| LaCie               | 22        | 29     | 0.06%   |
| StoreJet            | 20        | 20     | 0.05%   |
| USB                 | 17        | 18     | 0.04%   |
| SSK                 | 15        | 16     | 0.04%   |
| HGST HTS            | 14        | 16     | 0.04%   |
| WD MediaMax         | 13        | 15     | 0.03%   |
| MARVELL             | 13        | 17     | 0.03%   |
| IBM/Hitachi         | 12        | 13     | 0.03%   |
| HPE                 | 12        | 22     | 0.03%   |
| ASMT109x            | 10        | 18     | 0.03%   |
| Inateck             | 9         | 9      | 0.02%   |
| KESU                | 8         | 12     | 0.02%   |
| ASMedia             | 8         | 8      | 0.02%   |
| Quantum             | 7         | 8      | 0.02%   |
| Unknown             | 7         | 9      | 0.02%   |
| Maxone              | 5         | 6      | 0.01%   |
| MARSHAL             | 5         | 5      | 0.01%   |
| TDAS                | 4         | 15     | 0.01%   |
| SAGE                | 4         | 4      | 0.01%   |
| IBM-ESXS            | 4         | 11     | 0.01%   |
| DELLBOSS            | 4         | 4      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6539      | 9046   | 23.44%  |
| Kingston            | 3959      | 5037   | 14.19%  |
| SanDisk             | 2662      | 3510   | 9.54%   |
| Crucial             | 2530      | 3491   | 9.07%   |
| WDC                 | 1653      | 2092   | 5.93%   |
| A-DATA Technology   | 916       | 1149   | 3.28%   |
| Intel               | 910       | 1248   | 3.26%   |
| China               | 629       | 767    | 2.25%   |
| Micron Technology   | 626       | 817    | 2.24%   |
| SK hynix            | 540       | 724    | 1.94%   |
| Toshiba             | 481       | 617    | 1.72%   |
| PNY                 | 414       | 513    | 1.48%   |
| SPCC                | 379       | 514    | 1.36%   |
| LITEON              | 372       | 456    | 1.33%   |
| OCZ                 | 360       | 437    | 1.29%   |
| Transcend           | 319       | 375    | 1.14%   |
| Apple               | 304       | 340    | 1.09%   |
| Intenso             | 267       | 371    | 0.96%   |
| Patriot             | 262       | 329    | 0.94%   |
| GOODRAM             | 207       | 283    | 0.74%   |
| LITEONIT            | 199       | 242    | 0.71%   |
| Corsair             | 191       | 253    | 0.68%   |
| Team                | 160       | 204    | 0.57%   |
| JMicron Technology  | 134       | 147    | 0.48%   |
| Apacer              | 132       | 151    | 0.47%   |
| KingSpec            | 131       | 161    | 0.47%   |
| Netac               | 119       | 149    | 0.43%   |
| ASMT                | 118       | 146    | 0.42%   |
| Hewlett-Packard     | 115       | 185    | 0.41%   |
| Plextor             | 112       | 145    | 0.4%    |
| Lexar               | 108       | 122    | 0.39%   |
| Gigabyte Technology | 101       | 136    | 0.36%   |
| Seagate             | 96        | 120    | 0.34%   |
| KingDian            | 79        | 94     | 0.28%   |
| Unknown             | 78        | 85     | 0.28%   |
| Mushkin             | 63        | 102    | 0.23%   |
| FORESEE             | 60        | 63     | 0.22%   |
| Unknown             | 57        | 65     | 0.2%    |
| Emtec               | 44        | 51     | 0.16%   |
| Dogfish             | 43        | 62     | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 33821     | 57480  | 41.68%  |
| SSD     | 25028     | 36571  | 30.85%  |
| NVMe    | 17724     | 23980  | 21.84%  |
| MMC     | 3212      | 4174   | 3.96%   |
| Unknown | 1356      | 1947   | 1.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 48849     | 90554  | 66.7%   |
| NVMe | 17711     | 23935  | 24.18%  |
| SAS  | 3469      | 5489   | 4.74%   |
| MMC  | 3212      | 4174   | 4.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 35550     | 53970  | 57.91%  |
| 0.51-1.0        | 17690     | 25419  | 28.82%  |
| 1.01-2.0        | 4729      | 7463   | 7.7%    |
| 3.01-4.0        | 1320      | 2431   | 2.15%   |
| 4.01-10.0       | 957       | 2323   | 1.56%   |
| 2.01-3.0        | 918       | 1705   | 1.5%    |
| 10.01-20.0      | 214       | 734    | 0.35%   |
| 0               | 4         | 4      | 0.01%   |
| More than 100.0 | 2         | 2      | 0.003%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 19533     | 28.78%  |
| 251-500        | 16567     | 24.41%  |
| 501-1000       | 10510     | 15.49%  |
| 51-100         | 4922      | 7.25%   |
| 1001-2000      | 4468      | 6.58%   |
| 1-20           | 3354      | 4.94%   |
| 21-50          | 3129      | 4.61%   |
| More than 3000 | 2555      | 3.76%   |
| 2001-3000      | 1664      | 2.45%   |
| Unknown        | 1161      | 1.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 29994     | 42.4%   |
| 21-50          | 12743     | 18.01%  |
| 101-250        | 8221      | 11.62%  |
| 51-100         | 8040      | 11.37%  |
| 251-500        | 4459      | 6.3%    |
| 501-1000       | 3037      | 4.29%   |
| 1001-2000      | 1583      | 2.24%   |
| Unknown        | 1161      | 1.64%   |
| More than 3000 | 914       | 1.29%   |
| 2001-3000      | 583       | 0.82%   |
| 0              | 4         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB    | 47        | 52     | 1.6%    |
| Seagate ST1000LM035-1RK172 1TB        | 43        | 44     | 1.47%   |
| Toshiba MQ01ABD100 1TB                | 40        | 44     | 1.36%   |
| Seagate ST500DM002-1BD142 500GB       | 39        | 42     | 1.33%   |
| Seagate ST9500325AS 500GB             | 34        | 35     | 1.16%   |
| HGST HTS541010A9E680 1TB              | 32        | 34     | 1.09%   |
| HGST HTS721010A9E630 1TB              | 28        | 31     | 0.95%   |
| Seagate ST3500418AS 500GB             | 27        | 33     | 0.92%   |
| HGST HTS725050A7E630 500GB            | 24        | 24     | 0.82%   |
| Seagate ST1000DM003-1CH162 1TB        | 21        | 23     | 0.72%   |
| Seagate ST500LM021-1KJ152 500GB       | 20        | 22     | 0.68%   |
| Toshiba MQ04ABF100 1TB                | 18        | 18     | 0.61%   |
| Seagate ST500LT012-1DG142 500GB       | 18        | 19     | 0.61%   |
| Kingston SV300S37A120G 120GB SSD      | 18        | 21     | 0.61%   |
| HGST HTS545050A7E680 500GB            | 17        | 17     | 0.58%   |
| Seagate ST500LT012-9WS142 500GB       | 16        | 18     | 0.55%   |
| Seagate ST31000528AS 1TB              | 16        | 18     | 0.55%   |
| Kingston SA400S37240G 240GB SSD       | 16        | 19     | 0.55%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 15        | 15     | 0.51%   |
| Samsung Electronics SSD 870 EVO 500GB | 15        | 15     | 0.51%   |
| HGST HTS545050A7E380 500GB            | 15        | 16     | 0.51%   |
| Seagate ST9500420AS 500GB             | 14        | 14     | 0.48%   |
| Toshiba MQ01ABF050 500GB              | 13        | 13     | 0.44%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 13        | 17     | 0.44%   |
| Seagate ST1000DM010-2EP102 1TB        | 13        | 14     | 0.44%   |
| Kingston SA400S37120G 120GB SSD       | 13        | 19     | 0.44%   |
| WDC WD40EFRX-68WT0N0 4TB              | 12        | 19     | 0.41%   |
| WDC WD10EARS-00Y5B1 1TB               | 12        | 16     | 0.41%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 12        | 12     | 0.41%   |
| Seagate ST2000DM001-1CH164 2TB        | 12        | 12     | 0.41%   |
| Seagate ST1000LX015-1U7172 1TB        | 12        | 12     | 0.41%   |
| Hitachi HTS543232A7A384 320GB         | 12        | 12     | 0.41%   |
| WDC WD5000AAKX-001CA0 500GB           | 11        | 14     | 0.37%   |
| Kingston SA400S37480G 480GB SSD       | 11        | 14     | 0.37%   |
| Hitachi HTS545050A7E380 500GB         | 11        | 12     | 0.37%   |
| WDC WD10EZEX-60ZF5A0 1TB              | 10        | 11     | 0.34%   |
| Toshiba DT01ACA100 1TB                | 10        | 12     | 0.34%   |
| Seagate ST9320423AS 320GB             | 10        | 10     | 0.34%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 10        | 12     | 0.34%   |
| Seagate ST1000DM003-9YN162 1TB        | 10        | 10     | 0.34%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 730       | 872    | 25.48%  |
| WDC                 | 613       | 722    | 21.4%   |
| Toshiba             | 213       | 235    | 7.43%   |
| Hitachi             | 211       | 231    | 7.36%   |
| Samsung Electronics | 200       | 239    | 6.98%   |
| HGST                | 142       | 153    | 4.96%   |
| SK hynix            | 102       | 109    | 3.56%   |
| Kingston            | 94        | 117    | 3.28%   |
| Intel               | 94        | 119    | 3.28%   |
| SanDisk             | 77        | 92     | 2.69%   |
| Crucial             | 57        | 66     | 1.99%   |
| Micron Technology   | 56        | 69     | 1.95%   |
| A-DATA Technology   | 47        | 57     | 1.64%   |
| Maxtor              | 24        | 34     | 0.84%   |
| Fujitsu             | 17        | 17     | 0.59%   |
| LITEON              | 15        | 16     | 0.52%   |
| Apple               | 15        | 18     | 0.52%   |
| Corsair             | 12        | 13     | 0.42%   |
| OCZ                 | 10        | 11     | 0.35%   |
| China               | 10        | 10     | 0.35%   |
| LITEONIT            | 9         | 11     | 0.31%   |
| Unknown             | 8         | 10     | 0.28%   |
| Hewlett-Packard     | 7         | 7      | 0.24%   |
| Unknown             | 6         | 6      | 0.21%   |
| Patriot             | 5         | 5      | 0.17%   |
| LDLC                | 5         | 6      | 0.17%   |
| KingSpec            | 5         | 5      | 0.17%   |
| Intenso             | 5         | 6      | 0.17%   |
| ASMT                | 5         | 5      | 0.17%   |
| Transcend           | 4         | 4      | 0.14%   |
| SPCC                | 4         | 4      | 0.14%   |
| Mushkin             | 4         | 4      | 0.14%   |
| XPG                 | 3         | 3      | 0.1%    |
| Netac               | 3         | 4      | 0.1%    |
| ASMedia             | 3         | 3      | 0.1%    |
| 2.5"                | 3         | 3      | 0.1%    |
| WD MediaMax         | 2         | 2      | 0.07%   |
| SSSTC               | 2         | 2      | 0.07%   |
| Plextor             | 2         | 2      | 0.07%   |
| Neo                 | 2         | 4      | 0.07%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 730       | 872    | 36.19%  |
| WDC                 | 569       | 674    | 28.21%  |
| Hitachi             | 211       | 231    | 10.46%  |
| Toshiba             | 201       | 222    | 9.97%   |
| HGST                | 142       | 153    | 7.04%   |
| Samsung Electronics | 94        | 109    | 4.66%   |
| Maxtor              | 24        | 34     | 1.19%   |
| Fujitsu             | 17        | 17     | 0.84%   |
| Apple               | 13        | 16     | 0.64%   |
| Unknown             | 7         | 9      | 0.35%   |
| Hewlett-Packard     | 4         | 4      | 0.2%    |
| WD MediaMax         | 2         | 2      | 0.1%    |
| ASMT                | 2         | 2      | 0.1%    |
| HPE                 | 1         | 1      | 0.05%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1910      | 2346   | 69.4%   |
| SSD     | 699       | 831    | 25.4%   |
| NVMe    | 142       | 157    | 5.16%   |
| Unknown | 1         | 1      | 0.04%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB                                 | 3         | 3      | 5.17%   |
| Samsung Electronics SSD 980 500GB                               | 3         | 3      | 5.17%   |
| WDC WD7500BPVT-22HXZT1 752GB                                    | 2         | 3      | 3.45%   |
| WDC WD10SPZX-21Z10T0 1TB                                        | 2         | 2      | 3.45%   |
| Samsung Electronics MZVLB1T0HALR-00000 1TB                      | 2         | 3      | 3.45%   |
| HGST HTS721010A9E630 1TB                                        | 2         | 2      | 3.45%   |
| WDC WD800BB-00FJA0 80GB                                         | 1         | 1      | 1.72%   |
| WDC WD5000BEVT-22A0RT0 500GB                                    | 1         | 1      | 1.72%   |
| WDC WD40EZRZ-00GXCB0 4TB                                        | 1         | 2      | 1.72%   |
| WDC WD3200BEKT-60PVMT0 320GB                                    | 1         | 1      | 1.72%   |
| WDC WD3200AAJS-22VWA0 320GB                                     | 1         | 1      | 1.72%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB                            | 1         | 1      | 1.72%   |
| Unknown 00000  16GB                                             | 1         | 1      | 1.72%   |
| Toshiba NVMe SSD Drive 256GB                                    | 1         | 1      | 1.72%   |
| Toshiba MQ02ABF050H 500GB                                       | 1         | 1      | 1.72%   |
| Toshiba MK5065GSXN 500GB                                        | 1         | 1      | 1.72%   |
| Toshiba MK3265GSX 320GB                                         | 1         | 1      | 1.72%   |
| Toshiba DT01ACA200 2TB                                          | 1         | 1      | 1.72%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB                         | 1         | 1      | 1.72%   |
| Seagate ST9500420AS 500GB                                       | 1         | 3      | 1.72%   |
| Seagate ST3500630AS 500GB                                       | 1         | 1      | 1.72%   |
| Seagate ST3500418AS 500GB                                       | 1         | 1      | 1.72%   |
| Seagate ST3300657SS 304GB                                       | 1         | 2      | 1.72%   |
| Seagate ST31000520AS 1TB                                        | 1         | 1      | 1.72%   |
| Seagate ST31000340NS 1TB                                        | 1         | 1      | 1.72%   |
| Seagate ST2000DM001-1CH164 2TB                                  | 1         | 1      | 1.72%   |
| Seagate ST1000LM048-2E7172 1TB                                  | 1         | 1      | 1.72%   |
| Samsung Electronics SSD 960 EVO 250GB                           | 1         | 1      | 1.72%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 250GB | 1         | 1      | 1.72%   |
| Samsung Electronics HD502HJ 500GB                               | 1         | 1      | 1.72%   |
| Samsung Electronics HD161GJ 160GB                               | 1         | 1      | 1.72%   |
| Samsung Electronics HD160JJ 160GB                               | 1         | 1      | 1.72%   |
| Samsung Electronics HD103SJ 1TB                                 | 1         | 1      | 1.72%   |
| Mushkin MKNSSDCR120GB-7                                         | 1         | 1      | 1.72%   |
| Maxtor STM380211AS 80GB                                         | 1         | 1      | 1.72%   |
| KingDian S400 120GB                                             | 1         | 1      | 1.72%   |
| JMicron Technology Tech 250GB                                   | 1         | 1      | 1.72%   |
| Intel SSDSCKGF256A5 SATA 256GB                                  | 1         | 1      | 1.72%   |
| Intel SSDSC2BB480G7 480GB                                       | 1         | 4      | 1.72%   |
| Intel SSDPEKKW256G7 256GB                                       | 1         | 1      | 1.72%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 14     | 18.97%  |
| Samsung Electronics | 11        | 12     | 18.97%  |
| WDC                 | 10        | 12     | 17.24%  |
| Toshiba             | 5         | 5      | 8.62%   |
| Intel               | 3         | 6      | 5.17%   |
| Hitachi             | 3         | 3      | 5.17%   |
| HGST                | 3         | 3      | 5.17%   |
| Crucial             | 2         | 2      | 3.45%   |
| Apple               | 2         | 2      | 3.45%   |
| Unknown             | 1         | 1      | 1.72%   |
| SK hynix            | 1         | 1      | 1.72%   |
| Mushkin             | 1         | 1      | 1.72%   |
| Maxtor              | 1         | 1      | 1.72%   |
| KingDian            | 1         | 1      | 1.72%   |
| JMicron Technology  | 1         | 1      | 1.72%   |
| Hewlett-Packard     | 1         | 4      | 1.72%   |
| A-DATA Technology   | 1         | 1      | 1.72%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 48115     | 93383  | 71.43%  |
| Works    | 16525     | 27361  | 24.53%  |
| Malfunc  | 2661      | 3335   | 3.95%   |
| Failed   | 58        | 70     | 0.09%   |
| Limited  | 2         | 2      | 0.003%  |
| Fixed    | 1         | 1      | 0.001%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 44920     | 56.46%  |
| AMD                              | 10912     | 13.72%  |
| Samsung Electronics              | 6203      | 7.8%    |
| SanDisk                          | 2720      | 3.42%   |
| SK hynix                         | 1725      | 2.17%   |
| Nvidia                           | 1248      | 1.57%   |
| ASMedia Technology               | 1180      | 1.48%   |
| Toshiba America Info Systems     | 1105      | 1.39%   |
| Marvell Technology Group         | 1062      | 1.33%   |
| JMicron Technology               | 1014      | 1.27%   |
| Phison Electronics               | 946       | 1.19%   |
| Kingston Technology Company      | 929       | 1.17%   |
| Micron Technology                | 803       | 1.01%   |
| KIOXIA                           | 686       | 0.86%   |
| Micron/Crucial Technology        | 549       | 0.69%   |
| Silicon Motion                   | 511       | 0.64%   |
| ADATA Technology                 | 383       | 0.48%   |
| LSI Logic / Symbios Logic        | 364       | 0.46%   |
| Broadcom / LSI                   | 280       | 0.35%   |
| VIA Technologies                 | 227       | 0.29%   |
| Realtek Semiconductor            | 202       | 0.25%   |
| Apple                            | 161       | 0.2%    |
| Union Memory (Shenzhen)          | 157       | 0.2%    |
| Solid State Storage Technology   | 139       | 0.17%   |
| Silicon Image                    | 127       | 0.16%   |
| Silicon Integrated Systems [SiS] | 126       | 0.16%   |
| Hewlett-Packard                  | 124       | 0.16%   |
| Adaptec                          | 104       | 0.13%   |
| Lite-On Technology               | 98        | 0.12%   |
| MAXIO Technology (Hangzhou)      | 85        | 0.11%   |
| Shenzhen Longsys Electronics     | 71        | 0.09%   |
| Seagate Technology               | 69        | 0.09%   |
| Lenovo                           | 49        | 0.06%   |
| Yangtze Memory Technologies      | 34        | 0.04%   |
| Integrated Technology Express    | 32        | 0.04%   |
| INNOGRIT                         | 20        | 0.03%   |
| Solidigm                         | 18        | 0.02%   |
| Areca Technology                 | 18        | 0.02%   |
| HighPoint Technologies           | 14        | 0.02%   |
| Transcend                        | 13        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 7129      | 7.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3492      | 3.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3026      | 3.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2906      | 3.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2889      | 3.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2486      | 2.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2153      | 2.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1548      | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1533      | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1516      | 1.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1501      | 1.62%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1491      | 1.6%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 1451      | 1.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1261      | 1.36%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1261      | 1.36%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1252      | 1.35%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1208      | 1.3%    |
| Intel SATA Controller [RAID mode]                                                       | 1199      | 1.29%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 1163      | 1.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1156      | 1.24%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1128      | 1.21%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1120      | 1.21%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1114      | 1.2%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1084      | 1.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1037      | 1.12%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 979       | 1.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 917       | 0.99%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 891       | 0.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 873       | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 842       | 0.91%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 792       | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 754       | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 702       | 0.76%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 697       | 0.75%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 644       | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 643       | 0.69%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 632       | 0.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 624       | 0.67%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 621       | 0.67%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 614       | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 46043     | 56.8%   |
| NVMe | 17988     | 22.19%  |
| IDE  | 10084     | 12.44%  |
| RAID | 6362      | 7.85%   |
| SAS  | 389       | 0.48%   |
| SCSI | 201       | 0.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 50800     | 78.22%  |
| AMD           | 13413     | 20.65%  |
| ARM           | 697       | 1.07%   |
| CentaurHauls  | 17        | 0.03%   |
| Unknown       | 11        | 0.02%   |
| sifive,u74-mc | 2         | 0.003%  |
| HiSilicon     | 2         | 0.003%  |
| QUALCOMM      | 1         | 0.002%  |
| Phytium       | 1         | 0.002%  |
| IBM/S390      | 1         | 0.002%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 798       | 1.23%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 714       | 1.1%    |
| ARM Processor                                 | 649       | 1%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 647       | 0.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 630       | 0.97%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 612       | 0.94%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 548       | 0.84%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 539       | 0.83%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 494       | 0.76%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 453       | 0.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 434       | 0.67%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 434       | 0.67%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 409       | 0.63%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 392       | 0.6%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 391       | 0.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 390       | 0.6%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 364       | 0.56%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 360       | 0.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 352       | 0.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 341       | 0.52%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 332       | 0.51%   |
| AMD Ryzen 5 3600 6-Core Processor             | 330       | 0.51%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 328       | 0.5%    |
| Intel Core i5-2400 CPU @ 3.10GHz              | 315       | 0.48%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 307       | 0.47%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 296       | 0.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 282       | 0.43%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 275       | 0.42%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 272       | 0.42%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 267       | 0.41%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 266       | 0.41%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 259       | 0.4%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 256       | 0.39%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 250       | 0.38%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 246       | 0.38%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 246       | 0.38%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 244       | 0.37%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 242       | 0.37%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 241       | 0.37%   |
| AMD FX-8350 Eight-Core Processor              | 234       | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 14583     | 22.43%  |
| Intel Core i7           | 12939     | 19.9%   |
| Intel Core i3           | 5226      | 8.04%   |
| Other                   | 4598      | 7.07%   |
| Intel Core 2 Duo        | 2919      | 4.49%   |
| AMD Ryzen 5             | 2839      | 4.37%   |
| Intel Celeron           | 2828      | 4.35%   |
| Intel Xeon              | 2100      | 3.23%   |
| AMD Ryzen 7             | 2063      | 3.17%   |
| Intel Pentium           | 1609      | 2.47%   |
| AMD FX                  | 1056      | 1.62%   |
| Intel Atom              | 1014      | 1.56%   |
| Intel Pentium Dual-Core | 838       | 1.29%   |
| Intel Core 2 Quad       | 671       | 1.03%   |
| AMD Ryzen 9             | 664       | 1.02%   |
| AMD Ryzen 3             | 630       | 0.97%   |
| AMD A6                  | 565       | 0.87%   |
| AMD A8                  | 523       | 0.8%    |
| AMD A10                 | 487       | 0.75%   |
| Intel Core i9           | 441       | 0.68%   |
| AMD A4                  | 411       | 0.63%   |
| Intel Core 2            | 409       | 0.63%   |
| Intel Pentium Dual      | 371       | 0.57%   |
| AMD Phenom II X4        | 369       | 0.57%   |
| AMD Athlon II X2        | 340       | 0.52%   |
| AMD Athlon 64 X2        | 318       | 0.49%   |
| AMD E                   | 226       | 0.35%   |
| AMD E1                  | 197       | 0.3%    |
| Intel Pentium 4         | 195       | 0.3%    |
| AMD Ryzen 7 PRO         | 193       | 0.3%    |
| AMD Athlon              | 190       | 0.29%   |
| Intel Genuine           | 181       | 0.28%   |
| AMD E2                  | 180       | 0.28%   |
| AMD Athlon II X4        | 167       | 0.26%   |
| Intel Pentium Silver    | 166       | 0.26%   |
| AMD Ryzen Threadripper  | 160       | 0.25%   |
| AMD Phenom II X6        | 154       | 0.24%   |
| Intel Pentium D         | 125       | 0.19%   |
| AMD Ryzen 5 PRO         | 122       | 0.19%   |
| AMD Phenom              | 101       | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 26760     | 41.14%  |
| 4       | 24103     | 37.06%  |
| 6       | 5521      | 8.49%   |
| 8       | 3836      | 5.9%    |
| 1       | 1363      | 2.1%    |
| 12      | 1042      | 1.6%    |
| 10      | 501       | 0.77%   |
| 16      | 488       | 0.75%   |
| 3       | 458       | 0.7%    |
| 14      | 364       | 0.56%   |
| 24      | 183       | 0.28%   |
| 20      | 82        | 0.13%   |
| 32      | 72        | 0.11%   |
| Unknown | 60        | 0.09%   |
| 28      | 55        | 0.08%   |
| 40      | 31        | 0.05%   |
| 18      | 23        | 0.04%   |
| 48      | 17        | 0.03%   |
| 64      | 15        | 0.02%   |
| 128     | 14        | 0.02%   |
| 5       | 13        | 0.02%   |
| 36      | 11        | 0.02%   |
| 44      | 8         | 0.01%   |
| 56      | 4         | 0.01%   |
| 52      | 3         | 0.005%  |
| 22      | 3         | 0.005%  |
| 104     | 2         | 0.003%  |
| 96      | 2         | 0.003%  |
| 80      | 2         | 0.003%  |
| 68      | 1         | 0.002%  |
| 26      | 1         | 0.002%  |
| 15      | 1         | 0.002%  |
| 9       | 1         | 0.002%  |
| 7       | 1         | 0.002%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 63803     | 98.24%  |
| 2       | 1041      | 1.6%    |
| Unknown | 58        | 0.09%   |
| 4       | 36        | 0.06%   |
| 3       | 10        | 0.02%   |
| 6       | 1         | 0.002%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 42212     | 64.92%  |
| 1       | 22743     | 34.98%  |
| Unknown | 60        | 0.09%   |
| 4       | 3         | 0.005%  |
| 112     | 1         | 0.002%  |
| 6       | 1         | 0.002%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 63894     | 98.34%  |
| Unknown        | 742       | 1.14%   |
| 32-bit         | 318       | 0.49%   |
| 64-bit         | 20        | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 19315     | 28.69%  |
| 0x206a7    | 3701      | 5.5%    |
| 0x306a9    | 3637      | 5.4%    |
| 0x306c3    | 2702      | 4.01%   |
| 0x1067a    | 2258      | 3.35%   |
| 0x906ea    | 1667      | 2.48%   |
| 0x806ea    | 1581      | 2.35%   |
| 0x806ec    | 1570      | 2.33%   |
| 0x806e9    | 1266      | 1.88%   |
| 0x40651    | 1260      | 1.87%   |
| 0x506e3    | 1201      | 1.78%   |
| 0x806c1    | 1175      | 1.75%   |
| 0x406e3    | 1146      | 1.7%    |
| 0x20655    | 1124      | 1.67%   |
| 0x906e9    | 1071      | 1.59%   |
| 0x306d4    | 1055      | 1.57%   |
| 0x6fd      | 749       | 1.11%   |
| 0x010000c8 | 643       | 0.95%   |
| 0x06000852 | 620       | 0.92%   |
| 0x10676    | 607       | 0.9%    |
| 0x30678    | 556       | 0.83%   |
| 0x08108109 | 536       | 0.8%    |
| 0x406c4    | 534       | 0.79%   |
| 0x06001119 | 520       | 0.77%   |
| 0x706e5    | 495       | 0.74%   |
| 0x20652    | 491       | 0.73%   |
| 0x806eb    | 457       | 0.68%   |
| 0x6fb      | 455       | 0.68%   |
| 0xa0652    | 430       | 0.64%   |
| 0x106e5    | 420       | 0.62%   |
| 0x906ed    | 409       | 0.61%   |
| 0x08701021 | 403       | 0.6%    |
| 0x0a50000c | 386       | 0.57%   |
| 0x0800820d | 358       | 0.53%   |
| 0x08108102 | 349       | 0.52%   |
| 0x08701013 | 322       | 0.48%   |
| 0x506c9    | 312       | 0.46%   |
| 0x706a1    | 310       | 0.46%   |
| 0x0810100b | 304       | 0.45%   |
| 0x08600106 | 296       | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 10917     | 16.78%  |
| Haswell          | 5754      | 8.85%   |
| SandyBridge      | 5103      | 7.85%   |
| IvyBridge        | 5008      | 7.7%    |
| Penryn           | 3721      | 5.72%   |
| Skylake          | 3632      | 5.58%   |
| Unknown          | 2385      | 3.67%   |
| Westmere         | 2379      | 3.66%   |
| Core             | 2090      | 3.21%   |
| Zen 2            | 1965      | 3.02%   |
| Silvermont       | 1922      | 2.96%   |
| TigerLake        | 1810      | 2.78%   |
| Zen+             | 1743      | 2.68%   |
| Broadwell        | 1609      | 2.47%   |
| K10              | 1604      | 2.47%   |
| Piledriver       | 1492      | 2.29%   |
| Zen 3            | 1271      | 1.95%   |
| CometLake        | 1207      | 1.86%   |
| Zen              | 1126      | 1.73%   |
| IceLake          | 1043      | 1.6%    |
| Nehalem          | 855       | 1.31%   |
| Excavator        | 840       | 1.29%   |
| Alderlake Hybrid | 813       | 1.25%   |
| Goldmont plus    | 771       | 1.19%   |
| K8 Hammer        | 609       | 0.94%   |
| Goldmont         | 461       | 0.71%   |
| Puma             | 432       | 0.66%   |
| Bobcat           | 428       | 0.66%   |
| NetBurst         | 380       | 0.58%   |
| Bonnell          | 327       | 0.5%    |
| Jaguar           | 283       | 0.44%   |
| Steamroller      | 273       | 0.42%   |
| K10 Llano        | 237       | 0.36%   |
| Bulldozer        | 212       | 0.33%   |
| P6               | 151       | 0.23%   |
| K8 & K10 hybrid  | 109       | 0.17%   |
| Tremont          | 59        | 0.09%   |
| Gracemont        | 12        | 0.02%   |
| K6               | 6         | 0.01%   |
| Sapphire Rapids  | 1         | 0.002%  |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 38593     | 50.46%  |
| Nvidia                                       | 20648     | 27%     |
| AMD                                          | 16076     | 21.02%  |
| Matrox Electronics Systems                   | 540       | 0.71%   |
| ASPEED Technology                            | 366       | 0.48%   |
| Silicon Integrated Systems [SiS]             | 103       | 0.13%   |
| VIA Technologies                             | 64        | 0.08%   |
| ATI Technologies                             | 42        | 0.05%   |
| XGI Technology (eXtreme Graphics Innovation) | 26        | 0.03%   |
| Zhaoxin                                      | 6         | 0.01%   |
| Silicon Motion                               | 6         | 0.01%   |
| Huawei Technologies                          | 5         | 0.01%   |
| S3 Graphics                                  | 2         | 0.003%  |
| NVidia / SGS Thomson (Joint Venture)         | 1         | 0.001%  |
| Moore Threads Technology                     | 1         | 0.001%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3704      | 4.72%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2715      | 3.46%   |
| Intel UHD Graphics 620                                                                   | 1923      | 2.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1650      | 2.1%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1627      | 2.07%   |
| Intel HD Graphics 620                                                                    | 1506      | 1.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1455      | 1.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1397      | 1.78%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1365      | 1.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1351      | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1341      | 1.71%   |
| Intel HD Graphics 5500                                                                   | 1174      | 1.49%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1133      | 1.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1096      | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1092      | 1.39%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1004      | 1.28%   |
| Intel HD Graphics 530                                                                    | 992       | 1.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 987       | 1.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 906       | 1.15%   |
| Intel HD Graphics 630                                                                    | 883       | 1.12%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 829       | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 821       | 1.05%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 770       | 0.98%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 690       | 0.88%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 655       | 0.83%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 634       | 0.81%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 632       | 0.8%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 604       | 0.77%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 541       | 0.69%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 538       | 0.68%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 537       | 0.68%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 484       | 0.62%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 477       | 0.61%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 462       | 0.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 462       | 0.59%   |
| AMD Lucienne                                                                             | 450       | 0.57%   |
| Nvidia GT218 [GeForce 210]                                                               | 438       | 0.56%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 436       | 0.56%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 434       | 0.55%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 431       | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 27658     | 42.34%  |
| 1 x AMD                  | 12284     | 18.8%   |
| 1 x Nvidia               | 11344     | 17.37%  |
| Intel + Nvidia           | 8096      | 12.39%  |
| Intel + AMD              | 2072      | 3.17%   |
| 2 x AMD                  | 890       | 1.36%   |
| AMD + Nvidia             | 784       | 1.2%    |
| Other                    | 775       | 1.19%   |
| 1 x Matrox               | 460       | 0.7%    |
| 1 x ASPEED               | 244       | 0.37%   |
| 2 x Nvidia               | 194       | 0.3%    |
| 1 x SiS                  | 102       | 0.16%   |
| Nvidia + ASPEED          | 101       | 0.15%   |
| 1 x VIA                  | 63        | 0.1%    |
| Nvidia + Matrox          | 56        | 0.09%   |
| 1 x XGI                  | 22        | 0.03%   |
| 2 x Intel                | 20        | 0.03%   |
| AMD + Matrox             | 20        | 0.03%   |
| Intel + 2 x Nvidia       | 19        | 0.03%   |
| AMD + ASPEED             | 14        | 0.02%   |
| Intel + AMD + 1 x Nvidia | 12        | 0.02%   |
| Intel + 2 x AMD          | 9         | 0.01%   |
| 3 x AMD                  | 6         | 0.01%   |
| 1 x Zhaoxin              | 6         | 0.01%   |
| 3 x Nvidia               | 5         | 0.01%   |
| 2 x Nvidia + 1 x ASPEED  | 5         | 0.01%   |
| 2 x AMD + 1 x Nvidia     | 5         | 0.01%   |
| 1 x Silicon Motion       | 5         | 0.01%   |
| 1 x Intel + 3 x Nvidia   | 5         | 0.01%   |
| 1 x Huawei Technologies  | 5         | 0.01%   |
| AMD + 2 x Nvidia         | 4         | 0.01%   |
| 2 x Nvidia + 1 x Matrox  | 3         | 0.005%  |
| AMD + XGI                | 3         | 0.005%  |
| 4 x Nvidia               | 2         | 0.003%  |
| 3 x Nvidia + 1 x ASPEED  | 2         | 0.003%  |
| 1 x Intel + 4 x Nvidia   | 2         | 0.003%  |
| 1 x Intel + 3 x AMD      | 2         | 0.003%  |
| Intel + ASPEED           | 2         | 0.003%  |
| 6 x Nvidia               | 1         | 0.002%  |
| 5 x AMD                  | 1         | 0.002%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 51479     | 78.14%  |
| Proprietary | 11172     | 16.96%  |
| Unknown     | 3230      | 4.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 38857     | 58.18%  |
| 1.01-2.0   | 8130      | 12.17%  |
| 0.01-0.5   | 6962      | 10.42%  |
| 0.51-1.0   | 5090      | 7.62%   |
| 3.01-4.0   | 4040      | 6.05%   |
| 7.01-8.0   | 1671      | 2.5%    |
| 5.01-6.0   | 1023      | 1.53%   |
| 8.01-16.0  | 499       | 0.75%   |
| 2.01-3.0   | 375       | 0.56%   |
| 16.01-24.0 | 98        | 0.15%   |
| 4.01-5.0   | 24        | 0.04%   |
| 32.01-64.0 | 5         | 0.01%   |
| 24.01-32.0 | 5         | 0.01%   |
| 0          | 2         | 0.003%  |
| 6.01-7.0   | 1         | 0.001%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 8976      | 13%     |
| AU Optronics            | 8075      | 11.69%  |
| LG Display              | 6235      | 9.03%   |
| Chimei Innolux          | 5474      | 7.93%   |
| BOE                     | 5441      | 7.88%   |
| Dell                    | 4292      | 6.21%   |
| Goldstar                | 3348      | 4.85%   |
| Hewlett-Packard         | 2607      | 3.77%   |
| Acer                    | 2263      | 3.28%   |
| AOC                     | 1515      | 2.19%   |
| Ancor Communications    | 1466      | 2.12%   |
| Philips                 | 1434      | 2.08%   |
| BenQ                    | 1405      | 2.03%   |
| Sharp                   | 1383      | 2%      |
| Apple                   | 1288      | 1.86%   |
| Lenovo                  | 1284      | 1.86%   |
| Chi Mei Optoelectronics | 1048      | 1.52%   |
| Iiyama                  | 722       | 1.05%   |
| ViewSonic               | 690       | 1%      |
| Sony                    | 608       | 0.88%   |
| Unknown                 | 526       | 0.76%   |
| LG Electronics          | 502       | 0.73%   |
| PANDA                   | 497       | 0.72%   |
| InfoVision              | 460       | 0.67%   |
| ASUSTek Computer        | 415       | 0.6%    |
| LG Philips              | 337       | 0.49%   |
| HannStar                | 257       | 0.37%   |
| Panasonic               | 247       | 0.36%   |
| NEC Computers           | 246       | 0.36%   |
| Fujitsu Siemens         | 241       | 0.35%   |
| Vizio                   | 239       | 0.35%   |
| Eizo                    | 224       | 0.32%   |
| Toshiba                 | 193       | 0.28%   |
| CSO                     | 172       | 0.25%   |
| Medion                  | 157       | 0.23%   |
| Sceptre Tech            | 154       | 0.22%   |
| MSI                     | 139       | 0.2%    |
| RTK                     | 116       | 0.17%   |
| Vestel Elektronik       | 110       | 0.16%   |
| CPT                     | 110       | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 342       | 0.48%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 332       | 0.47%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 302       | 0.42%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 257       | 0.36%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 255       | 0.36%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 245       | 0.34%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 212       | 0.3%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 206       | 0.29%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 186       | 0.26%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 176       | 0.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 167       | 0.23%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 162       | 0.23%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 156       | 0.22%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 144       | 0.2%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 143       | 0.2%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 140       | 0.2%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 140       | 0.2%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 140       | 0.2%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 130       | 0.18%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 127       | 0.18%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 124       | 0.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 118       | 0.17%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 117       | 0.16%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                        | 117       | 0.16%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 115       | 0.16%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 112       | 0.16%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 111       | 0.16%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 111       | 0.16%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 110       | 0.15%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 107       | 0.15%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 105       | 0.15%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 105       | 0.15%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 104       | 0.15%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 102       | 0.14%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 102       | 0.14%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 102       | 0.14%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 99        | 0.14%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 96        | 0.13%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 95        | 0.13%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 94        | 0.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 28227     | 42.49%  |
| 1366x768 (WXGA)    | 13219     | 19.9%   |
| 3840x2160 (4K)     | 3724      | 5.61%   |
| 1600x900 (HD+)     | 3109      | 4.68%   |
| 1280x1024 (SXGA)   | 2422      | 3.65%   |
| 2560x1440 (QHD)    | 2275      | 3.42%   |
| 1680x1050 (WSXGA+) | 1981      | 2.98%   |
| 1440x900 (WXGA+)   | 1735      | 2.61%   |
| 1920x1200 (WUXGA)  | 1588      | 2.39%   |
| 1280x800 (WXGA)    | 1497      | 2.25%   |
| Unknown            | 934       | 1.41%   |
| 1360x768           | 605       | 0.91%   |
| 2560x1080          | 523       | 0.79%   |
| 3440x1440          | 476       | 0.72%   |
| 2560x1600          | 458       | 0.69%   |
| 3840x1080          | 380       | 0.57%   |
| 1024x768 (XGA)     | 334       | 0.5%    |
| 1920x540           | 264       | 0.4%    |
| 2880x1800          | 244       | 0.37%   |
| 3840x2400          | 214       | 0.32%   |
| 1024x600           | 169       | 0.25%   |
| 1600x1200          | 168       | 0.25%   |
| 2160x1440          | 163       | 0.25%   |
| 3200x1800 (QHD+)   | 130       | 0.2%    |
| 1280x720 (HD)      | 116       | 0.17%   |
| 2736x1824          | 108       | 0.16%   |
| 3000x2000          | 60        | 0.09%   |
| 3840x1600          | 55        | 0.08%   |
| 1920x1280          | 55        | 0.08%   |
| 1400x1050          | 49        | 0.07%   |
| 2288x1287          | 47        | 0.07%   |
| 3072x1920          | 45        | 0.07%   |
| 2256x1504          | 44        | 0.07%   |
| 4480x1440          | 41        | 0.06%   |
| 3840x1200          | 41        | 0.06%   |
| 2048x1152          | 38        | 0.06%   |
| 5760x1080          | 33        | 0.05%   |
| 3200x1080          | 33        | 0.05%   |
| 1680x945           | 32        | 0.05%   |
| 1280x960           | 32        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 17512     | 25.44%  |
| 13      | 6403      | 9.3%    |
| 14      | 5261      | 7.64%   |
| 24      | 4538      | 6.59%   |
| Unknown | 4250      | 6.18%   |
| 27      | 4150      | 6.03%   |
| 23      | 4148      | 6.03%   |
| 17      | 4076      | 5.92%   |
| 21      | 3737      | 5.43%   |
| 19      | 2242      | 3.26%   |
| 18      | 1458      | 2.12%   |
| 22      | 1215      | 1.77%   |
| 20      | 1212      | 1.76%   |
| 31      | 1177      | 1.71%   |
| 12      | 1096      | 1.59%   |
| 34      | 797       | 1.16%   |
| 11      | 699       | 1.02%   |
| 16      | 562       | 0.82%   |
| 84      | 501       | 0.73%   |
| 72      | 406       | 0.59%   |
| 40      | 360       | 0.52%   |
| 32      | 356       | 0.52%   |
| 54      | 343       | 0.5%    |
| 10      | 280       | 0.41%   |
| 25      | 234       | 0.34%   |
| 26      | 193       | 0.28%   |
| 28      | 134       | 0.19%   |
| 46      | 117       | 0.17%   |
| 52      | 116       | 0.17%   |
| 37      | 110       | 0.16%   |
| 48      | 107       | 0.16%   |
| 42      | 86        | 0.12%   |
| 65      | 85        | 0.12%   |
| 29      | 72        | 0.1%    |
| 49      | 66        | 0.1%    |
| 33      | 64        | 0.09%   |
| 43      | 62        | 0.09%   |
| 39      | 57        | 0.08%   |
| 36      | 52        | 0.08%   |
| 38      | 38        | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 26877     | 39.57%  |
| 501-600        | 12067     | 17.77%  |
| 401-500        | 8553      | 12.59%  |
| 201-300        | 5236      | 7.71%   |
| 351-400        | 4902      | 7.22%   |
| Unknown        | 4250      | 6.26%   |
| 601-700        | 1888      | 2.78%   |
| 701-800        | 1267      | 1.87%   |
| 1001-1500      | 1047      | 1.54%   |
| 1501-2000      | 978       | 1.44%   |
| 801-900        | 601       | 0.88%   |
| 901-1000       | 178       | 0.26%   |
| 101-200        | 39        | 0.06%   |
| More than 2000 | 26        | 0.04%   |
| 1-100          | 6         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 46266     | 73.86%  |
| 16/10   | 7633      | 12.19%  |
| Unknown | 3743      | 5.98%   |
| 5/4     | 2217      | 3.54%   |
| 21/9    | 949       | 1.52%   |
| 3/2     | 715       | 1.14%   |
| 4/3     | 695       | 1.11%   |
| 32/9    | 153       | 0.24%   |
| 6/5     | 121       | 0.19%   |
| 0.56    | 36        | 0.06%   |
| 1.00    | 30        | 0.05%   |
| 1.96    | 27        | 0.04%   |
| 0.62    | 11        | 0.02%   |
| 3.40    | 8         | 0.01%   |
| 3.20    | 6         | 0.01%   |
| 3.73    | 5         | 0.01%   |
| 2.00    | 4         | 0.01%   |
| 2.12    | 3         | 0.005%  |
| 0.89    | 3         | 0.005%  |
| 11/10   | 2         | 0.003%  |
| 3.76    | 1         | 0.002%  |
| 3.33    | 1         | 0.002%  |
| 2.69    | 1         | 0.002%  |
| 2.50    | 1         | 0.002%  |
| 2.01    | 1         | 0.002%  |
| 0.75    | 1         | 0.002%  |
| 0.67    | 1         | 0.002%  |
| 0.65    | 1         | 0.002%  |
| 0.45    | 1         | 0.002%  |
| 0.00    | 1         | 0.002%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 17387     | 25.45%  |
| 201-250        | 10964     | 16.05%  |
| 81-90          | 9056      | 13.26%  |
| 151-200        | 4623      | 6.77%   |
| 301-350        | 4296      | 6.29%   |
| Unknown        | 4251      | 6.22%   |
| 71-80          | 2647      | 3.87%   |
| 121-130        | 2543      | 3.72%   |
| 351-500        | 2525      | 3.7%    |
| 141-150        | 2248      | 3.29%   |
| More than 1000 | 1801      | 2.64%   |
| 251-300        | 1699      | 2.49%   |
| 501-1000       | 1050      | 1.54%   |
| 61-70          | 943       | 1.38%   |
| 51-60          | 722       | 1.06%   |
| 111-120        | 551       | 0.81%   |
| 131-140        | 532       | 0.78%   |
| 41-50          | 267       | 0.39%   |
| 91-100         | 170       | 0.25%   |
| 1-40           | 42        | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 21851     | 32.8%   |
| 101-120       | 17621     | 26.45%  |
| 121-160       | 16130     | 24.21%  |
| Unknown       | 4250      | 6.38%   |
| 161-240       | 3521      | 5.28%   |
| 1-50          | 1716      | 2.58%   |
| More than 240 | 1539      | 2.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 52250     | 78.62%  |
| 2     | 9346      | 14.06%  |
| 0     | 3759      | 5.66%   |
| 3     | 1016      | 1.53%   |
| 4     | 80        | 0.12%   |
| 5     | 7         | 0.01%   |
| 6     | 2         | 0.003%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 34316     | 35.24%  |
| Intel                             | 30724     | 31.55%  |
| Qualcomm Atheros                  | 11282     | 11.58%  |
| Broadcom                          | 5963      | 6.12%   |
| Ralink Technology                 | 1276      | 1.31%   |
| Broadcom Limited                  | 1237      | 1.27%   |
| Marvell Technology Group          | 1194      | 1.23%   |
| Ralink                            | 1055      | 1.08%   |
| Nvidia                            | 1016      | 1.04%   |
| TP-Link                           | 990       | 1.02%   |
| MediaTek                          | 973       | 1%      |
| Samsung Electronics               | 469       | 0.48%   |
| ASIX Electronics                  | 450       | 0.46%   |
| Qualcomm Atheros Communications   | 343       | 0.35%   |
| NetGear                           | 338       | 0.35%   |
| Dell                              | 308       | 0.32%   |
| DisplayLink                       | 304       | 0.31%   |
| Xiaomi                            | 271       | 0.28%   |
| Huawei Technologies               | 247       | 0.25%   |
| D-Link                            | 246       | 0.25%   |
| Sierra Wireless                   | 227       | 0.23%   |
| D-Link System                     | 221       | 0.23%   |
| Ericsson Business Mobile Networks | 209       | 0.21%   |
| ASUSTek Computer                  | 207       | 0.21%   |
| Hewlett-Packard                   | 189       | 0.19%   |
| Lenovo                            | 186       | 0.19%   |
| JMicron Technology                | 174       | 0.18%   |
| Microsoft                         | 170       | 0.17%   |
| Aquantia                          | 159       | 0.16%   |
| Edimax Technology                 | 152       | 0.16%   |
| Qualcomm                          | 137       | 0.14%   |
| VIA Technologies                  | 117       | 0.12%   |
| Linksys                           | 111       | 0.11%   |
| Silicon Integrated Systems [SiS]  | 109       | 0.11%   |
| Belkin Components                 | 109       | 0.11%   |
| Motorola PCS                      | 87        | 0.09%   |
| Apple                             | 77        | 0.08%   |
| Arduino SA                        | 70        | 0.07%   |
| IMC Networks                      | 67        | 0.07%   |
| OPPO Electronics                  | 66        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 23271     | 20.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4596      | 4.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2510      | 2.2%    |
| Intel Wi-Fi 6 AX200                                               | 2050      | 1.8%    |
| Intel Wireless 8265 / 8275                                        | 1802      | 1.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1623      | 1.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1559      | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1499      | 1.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1490      | 1.31%   |
| Intel Wi-Fi 6 AX201                                               | 1410      | 1.24%   |
| Intel Wireless 7265                                               | 1319      | 1.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1229      | 1.08%   |
| Intel Wireless 7260                                               | 1221      | 1.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1162      | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1156      | 1.01%   |
| Intel I211 Gigabit Network Connection                             | 1129      | 0.99%   |
| Intel Wireless 8260                                               | 1031      | 0.9%    |
| Intel Ethernet Connection (2) I219-V                              | 994       | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 964       | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 949       | 0.83%   |
| Intel Ethernet Connection I217-LM                                 | 938       | 0.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 926       | 0.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 925       | 0.81%   |
| Intel Wireless 3165                                               | 920       | 0.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 894       | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 888       | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 781       | 0.68%   |
| Intel 82579V Gigabit Network Connection                           | 690       | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 677       | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 653       | 0.57%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 626       | 0.55%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 616       | 0.54%   |
| Broadcom BCM43142 802.11b/g/n                                     | 593       | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 573       | 0.5%    |
| Intel Wireless-AC 9260                                            | 565       | 0.5%    |
| Intel Wireless 3160                                               | 541       | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 524       | 0.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 505       | 0.44%   |
| Ralink MT7601U Wireless Adapter                                   | 505       | 0.44%   |
| Intel Ethernet Connection (7) I219-V                              | 502       | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 22233     | 43.32%  |
| Qualcomm Atheros                      | 8984      | 17.5%   |
| Realtek Semiconductor                 | 8424      | 16.41%  |
| Broadcom                              | 3767      | 7.34%   |
| Ralink Technology                     | 1276      | 2.49%   |
| Ralink                                | 1053      | 2.05%   |
| MediaTek                              | 891       | 1.74%   |
| TP-Link                               | 889       | 1.73%   |
| Broadcom Limited                      | 766       | 1.49%   |
| Qualcomm Atheros Communications       | 343       | 0.67%   |
| NetGear                               | 332       | 0.65%   |
| D-Link                                | 238       | 0.46%   |
| Sierra Wireless                       | 227       | 0.44%   |
| Dell                                  | 221       | 0.43%   |
| ASUSTek Computer                      | 197       | 0.38%   |
| Marvell Technology Group              | 160       | 0.31%   |
| D-Link System                         | 150       | 0.29%   |
| Microsoft                             | 138       | 0.27%   |
| Edimax Technology                     | 129       | 0.25%   |
| Belkin Components                     | 106       | 0.21%   |
| Linksys                               | 100       | 0.19%   |
| Qualcomm                              | 79        | 0.15%   |
| IMC Networks                          | 67        | 0.13%   |
| Fibocom                               | 57        | 0.11%   |
| AVM                                   | 52        | 0.1%    |
| Ericsson Business Mobile Networks     | 40        | 0.08%   |
| Hewlett-Packard                       | 39        | 0.08%   |
| Sitecom Europe                        | 32        | 0.06%   |
| ZyDAS                                 | 29        | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 29        | 0.06%   |
| BUFFALO                               | 28        | 0.05%   |
| Gemtek                                | 25        | 0.05%   |
| ZyXEL Communications                  | 24        | 0.05%   |
| Micro Star International              | 21        | 0.04%   |
| Mercucys                              | 18        | 0.04%   |
| Wilocity                              | 14        | 0.03%   |
| Wacom                                 | 11        | 0.02%   |
| TRENDnet                              | 10        | 0.02%   |
| Tenda                                 | 10        | 0.02%   |
| Guillemot                             | 10        | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 2050      | 3.97%   |
| Intel Wireless 8265 / 8275                                     | 1802      | 3.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1623      | 3.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1499      | 2.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1490      | 2.88%   |
| Intel Wi-Fi 6 AX201                                            | 1410      | 2.73%   |
| Intel Wireless 7265                                            | 1319      | 2.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1229      | 2.38%   |
| Intel Wireless 7260                                            | 1221      | 2.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1162      | 2.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1156      | 2.24%   |
| Intel Wireless 8260                                            | 1031      | 1.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 964       | 1.86%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 949       | 1.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 926       | 1.79%   |
| Intel Wireless 3165                                            | 920       | 1.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 894       | 1.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 888       | 1.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 781       | 1.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 677       | 1.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 653       | 1.26%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 626       | 1.21%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 616       | 1.19%   |
| Broadcom BCM43142 802.11b/g/n                                  | 593       | 1.15%   |
| Intel Wireless-AC 9260                                         | 565       | 1.09%   |
| Intel Wireless 3160                                            | 541       | 1.05%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 524       | 1.01%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 505       | 0.98%   |
| Ralink MT7601U Wireless Adapter                                | 505       | 0.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 468       | 0.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 458       | 0.89%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 431       | 0.83%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 416       | 0.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 414       | 0.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 397       | 0.77%   |
| Intel Centrino Ultimate-N 6300                                 | 397       | 0.77%   |
| Realtek 802.11ac NIC                                           | 390       | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 390       | 0.75%   |
| Intel WiFi Link 5100                                           | 389       | 0.75%   |
| Intel Centrino Advanced-N 6200                                 | 374       | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 30901     | 51.75%  |
| Intel                             | 16339     | 27.36%  |
| Qualcomm Atheros                  | 3364      | 5.63%   |
| Broadcom                          | 2991      | 5.01%   |
| Marvell Technology Group          | 1035      | 1.73%   |
| Nvidia                            | 1010      | 1.69%   |
| Broadcom Limited                  | 495       | 0.83%   |
| ASIX Electronics                  | 450       | 0.75%   |
| Samsung Electronics               | 341       | 0.57%   |
| DisplayLink                       | 304       | 0.51%   |
| Xiaomi                            | 263       | 0.44%   |
| Lenovo                            | 182       | 0.3%    |
| Huawei Technologies               | 181       | 0.3%    |
| JMicron Technology                | 174       | 0.29%   |
| Aquantia                          | 159       | 0.27%   |
| VIA Technologies                  | 114       | 0.19%   |
| Silicon Integrated Systems [SiS]  | 108       | 0.18%   |
| TP-Link                           | 101       | 0.17%   |
| MediaTek                          | 74        | 0.12%   |
| Apple                             | 73        | 0.12%   |
| D-Link System                     | 71        | 0.12%   |
| OPPO Electronics                  | 65        | 0.11%   |
| Motorola PCS                      | 65        | 0.11%   |
| Google                            | 61        | 0.1%    |
| Qualcomm                          | 53        | 0.09%   |
| ICS Advent                        | 52        | 0.09%   |
| Hewlett-Packard                   | 52        | 0.09%   |
| Mellanox Technologies             | 36        | 0.06%   |
| American Megatrends               | 36        | 0.06%   |
| Microsoft                         | 30        | 0.05%   |
| Microchip Technology              | 30        | 0.05%   |
| Attansic Technology               | 30        | 0.05%   |
| 3Com                              | 29        | 0.05%   |
| OnePlus Technology (Shenzhen)     | 28        | 0.05%   |
| IBM                               | 27        | 0.05%   |
| ZTE WCDMA Technologies MSM        | 24        | 0.04%   |
| Edimax Technology                 | 23        | 0.04%   |
| Dell                              | 20        | 0.03%   |
| HMD Global                        | 19        | 0.03%   |
| Sundance Technology Inc / IC Plus | 18        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 23271     | 38.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4596      | 7.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2510      | 4.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1559      | 2.55%   |
| Intel I211 Gigabit Network Connection                             | 1129      | 1.85%   |
| Intel Ethernet Connection (2) I219-V                              | 994       | 1.63%   |
| Intel Ethernet Connection I217-LM                                 | 938       | 1.53%   |
| Realtek RTL8125 2.5GbE Controller                                 | 925       | 1.51%   |
| Intel 82579V Gigabit Network Connection                           | 690       | 1.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 573       | 0.94%   |
| Intel Ethernet Connection (7) I219-V                              | 502       | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 495       | 0.81%   |
| Intel 82577LM Gigabit Network Connection                          | 489       | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                             | 469       | 0.77%   |
| Intel Ethernet Connection I219-LM                                 | 451       | 0.74%   |
| Intel Ethernet Controller I225-V                                  | 442       | 0.72%   |
| Intel I210 Gigabit Network Connection                             | 428       | 0.7%    |
| Intel Ethernet Connection I218-LM                                 | 393       | 0.64%   |
| Intel Ethernet Connection I217-V                                  | 380       | 0.62%   |
| Nvidia MCP61 Ethernet                                             | 375       | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 363       | 0.59%   |
| Intel Ethernet Connection (7) I219-LM                             | 359       | 0.59%   |
| ASIX AX88179 Gigabit Ethernet                                     | 346       | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 341       | 0.56%   |
| Intel Ethernet Connection (6) I219-V                              | 338       | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 334       | 0.55%   |
| Intel Ethernet Connection (4) I219-V                              | 334       | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 332       | 0.54%   |
| Intel 82574L Gigabit Network Connection                           | 332       | 0.54%   |
| Intel Ethernet Connection (3) I218-LM                             | 327       | 0.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 316       | 0.52%   |
| Intel 82567LM Gigabit Network Connection                          | 308       | 0.5%    |
| Intel Ethernet Connection (2) I218-V                              | 303       | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 302       | 0.49%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 293       | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 292       | 0.48%   |
| Intel I350 Gigabit Network Connection                             | 265       | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 257       | 0.42%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 253       | 0.41%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 251       | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 56143     | 53%     |
| WiFi     | 48633     | 45.91%  |
| Modem    | 994       | 0.94%   |
| Unknown  | 161       | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 38241     | 57.03%  |
| Ethernet | 28780     | 42.92%  |
| Unknown  | 22        | 0.03%   |
| Modem    | 14        | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 35465     | 54.43%  |
| 1     | 26241     | 40.27%  |
| 0     | 1543      | 2.37%   |
| 3     | 1265      | 1.94%   |
| 4     | 422       | 0.65%   |
| 5     | 81        | 0.12%   |
| 6     | 72        | 0.11%   |
| 8     | 32        | 0.05%   |
| 7     | 15        | 0.02%   |
| 10    | 12        | 0.02%   |
| 12    | 3         | 0.005%  |
| 18    | 2         | 0.003%  |
| 13    | 2         | 0.003%  |
| 11    | 2         | 0.003%  |
| 32    | 1         | 0.002%  |
| 17    | 1         | 0.002%  |
| 9     | 1         | 0.002%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 55251     | 83.65%  |
| Yes     | 10794     | 16.34%  |
| Unknown | 9         | 0.01%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17559     | 47.27%  |
| Realtek Semiconductor           | 3521      | 9.48%   |
| Qualcomm Atheros Communications | 3410      | 9.18%   |
| Cambridge Silicon Radio         | 2039      | 5.49%   |
| Broadcom                        | 1956      | 5.27%   |
| IMC Networks                    | 1412      | 3.8%    |
| Apple                           | 1334      | 3.59%   |
| Lite-On Technology              | 1197      | 3.22%   |
| Foxconn / Hon Hai               | 1157      | 3.11%   |
| Dell                            | 575       | 1.55%   |
| ASUSTek Computer                | 575       | 1.55%   |
| Hewlett-Packard                 | 429       | 1.15%   |
| Ralink                          | 303       | 0.82%   |
| Toshiba                         | 299       | 0.8%    |
| Realtek                         | 264       | 0.71%   |
| Marvell Semiconductor           | 158       | 0.43%   |
| MediaTek                        | 148       | 0.4%    |
| Alps Electric                   | 124       | 0.33%   |
| Foxconn International           | 95        | 0.26%   |
| Ralink Technology               | 69        | 0.19%   |
| TP-Link                         | 60        | 0.16%   |
| Integrated System Solution      | 51        | 0.14%   |
| Belkin Components               | 44        | 0.12%   |
| Dynex                           | 40        | 0.11%   |
| Askey Computer                  | 39        | 0.1%    |
| Micro Star International        | 33        | 0.09%   |
| Edimax Technology               | 31        | 0.08%   |
| USI                             | 24        | 0.06%   |
| Chicony Electronics             | 21        | 0.06%   |
| Logitech                        | 20        | 0.05%   |
| Taiyo Yuden                     | 18        | 0.05%   |
| Smart Modular Technologies      | 17        | 0.05%   |
| Opticis                         | 16        | 0.04%   |
| Qcom                            | 14        | 0.04%   |
| HTC (High Tech Computer)        | 13        | 0.03%   |
| Conwise Technology              | 13        | 0.03%   |
| D-Link System                   | 9         | 0.02%   |
| Primax Electronics              | 7         | 0.02%   |
| Fujitsu                         | 6         | 0.02%   |
| Actions                         | 6         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6663      | 17.92%  |
| Intel Bluetooth Device                              | 3889      | 10.46%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2645      | 7.12%   |
| Realtek Bluetooth Radio                             | 2070      | 5.57%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2039      | 5.49%   |
| Intel AX200 Bluetooth                               | 1921      | 5.17%   |
| Qualcomm Atheros  Bluetooth Device                  | 1626      | 4.37%   |
| Realtek  Bluetooth 4.2 Adapter                      | 998       | 2.68%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 651       | 1.75%   |
| Intel Wireless-AC 3168 Bluetooth                    | 640       | 1.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 523       | 1.41%   |
| Apple Bluetooth Host Controller                     | 477       | 1.28%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 454       | 1.22%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 448       | 1.21%   |
| IMC Networks Bluetooth Radio                        | 435       | 1.17%   |
| Foxconn / Hon Hai Bluetooth Device                  | 414       | 1.11%   |
| Apple Bluetooth USB Host Controller                 | 403       | 1.08%   |
| IMC Networks Bluetooth Device                       | 398       | 1.07%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 394       | 1.06%   |
| Intel AX210 Bluetooth                               | 387       | 1.04%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 364       | 0.98%   |
| Lite-On Bluetooth Device                            | 322       | 0.87%   |
| Ralink RT3290 Bluetooth                             | 303       | 0.82%   |
| IMC Networks Wireless_Device                        | 287       | 0.77%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 271       | 0.73%   |
| Realtek Bluetooth Radio                             | 264       | 0.71%   |
| Broadcom BCM2045B (BDC-2.1)                         | 263       | 0.71%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 256       | 0.69%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 252       | 0.68%   |
| HP Broadcom 2070 Bluetooth Combo                    | 249       | 0.67%   |
| Lite-On Atheros AR3012 Bluetooth                    | 237       | 0.64%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 228       | 0.61%   |
| Dell DW375 Bluetooth Module                         | 190       | 0.51%   |
| Apple Bluetooth HCI                                 | 183       | 0.49%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 176       | 0.47%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 166       | 0.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 157       | 0.42%   |
| Realtek RTL8723B Bluetooth                          | 151       | 0.41%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 149       | 0.4%    |
| Broadcom HP Portable SoftSailing                    | 140       | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 48081     | 55.96%  |
| AMD                              | 16344     | 19.02%  |
| Nvidia                           | 14408     | 16.77%  |
| C-Media Electronics              | 1106      | 1.29%   |
| Logitech                         | 589       | 0.69%   |
| Creative Labs                    | 480       | 0.56%   |
| GN Netcom                        | 309       | 0.36%   |
| Realtek Semiconductor            | 297       | 0.35%   |
| Texas Instruments                | 232       | 0.27%   |
| Plantronics                      | 213       | 0.25%   |
| JMTek                            | 199       | 0.23%   |
| Generalplus Technology           | 194       | 0.23%   |
| ASUSTek Computer                 | 169       | 0.2%    |
| Lenovo                           | 167       | 0.19%   |
| VIA Technologies                 | 165       | 0.19%   |
| Creative Technology              | 150       | 0.17%   |
| Kingston Technology              | 143       | 0.17%   |
| Apple                            | 130       | 0.15%   |
| Focusrite-Novation               | 129       | 0.15%   |
| Silicon Integrated Systems [SiS] | 123       | 0.14%   |
| Corsair                          | 121       | 0.14%   |
| Razer USA                        | 114       | 0.13%   |
| Hewlett-Packard                  | 109       | 0.13%   |
| SteelSeries ApS                  | 95        | 0.11%   |
| DSEA A/S                         | 72        | 0.08%   |
| Tenx Technology                  | 70        | 0.08%   |
| Micro Star International         | 70        | 0.08%   |
| Blue Microphones                 | 58        | 0.07%   |
| Microsoft                        | 57        | 0.07%   |
| Dell                             | 57        | 0.07%   |
| M-Audio                          | 46        | 0.05%   |
| BEHRINGER International          | 39        | 0.05%   |
| Sony                             | 37        | 0.04%   |
| Samson Technologies              | 37        | 0.04%   |
| XMOS                             | 33        | 0.04%   |
| GYROCOM C&C                      | 33        | 0.04%   |
| Sennheiser Communications        | 32        | 0.04%   |
| Conexant Systems                 | 31        | 0.04%   |
| Yamaha                           | 28        | 0.03%   |
| Giga-Byte Technology             | 28        | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 5268      | 5.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4787      | 4.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4632      | 4.59%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4030      | 3.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3221      | 3.19%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2628      | 2.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2503      | 2.48%   |
| Intel Cannon Lake PCH cAVS                                                 | 2455      | 2.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2450      | 2.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2054      | 2.03%   |
| AMD FCH Azalia Controller                                                  | 2038      | 2.02%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1908      | 1.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1808      | 1.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1807      | 1.79%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1736      | 1.72%   |
| Intel 8 Series HD Audio Controller                                         | 1677      | 1.66%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1674      | 1.66%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1629      | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1569      | 1.55%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1498      | 1.48%   |
| Intel Broadwell-U Audio Controller                                         | 1404      | 1.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1360      | 1.35%   |
| Intel 200 Series PCH HD Audio                                              | 1262      | 1.25%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1251      | 1.24%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1168      | 1.16%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1100      | 1.09%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1100      | 1.09%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1006      | 1%      |
| AMD Kabini HDMI/DP Audio                                                   | 983       | 0.97%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 933       | 0.92%   |
| Nvidia High Definition Audio Controller                                    | 909       | 0.9%    |
| Nvidia GF108 High Definition Audio Controller                              | 897       | 0.89%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 808       | 0.8%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 795       | 0.79%   |
| Intel Comet Lake PCH cAVS                                                  | 787       | 0.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 770       | 0.76%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 770       | 0.76%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 741       | 0.73%   |
| Nvidia GP106 High Definition Audio Controller                              | 716       | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 695       | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7471      | 23.68%  |
| SK hynix            | 6006      | 19.04%  |
| Kingston            | 3569      | 11.31%  |
| Micron Technology   | 3328      | 10.55%  |
| Unknown             | 2445      | 7.75%   |
| Crucial             | 1786      | 5.66%   |
| Corsair             | 1616      | 5.12%   |
| G.Skill             | 959       | 3.04%   |
| A-DATA Technology   | 664       | 2.1%    |
| Ramaxel Technology  | 504       | 1.6%    |
| Elpida              | 367       | 1.16%   |
| Nanya Technology    | 322       | 1.02%   |
| Unknown (ABCD)      | 271       | 0.86%   |
| Team                | 206       | 0.65%   |
| Smart               | 195       | 0.62%   |
| Unknown             | 194       | 0.61%   |
| Patriot             | 174       | 0.55%   |
| Transcend           | 160       | 0.51%   |
| Goodram             | 88        | 0.28%   |
| Apacer              | 70        | 0.22%   |
| Teikon              | 57        | 0.18%   |
| PNY                 | 51        | 0.16%   |
| Hewlett-Packard     | 49        | 0.16%   |
| ASint Technology    | 41        | 0.13%   |
| Silicon Power       | 40        | 0.13%   |
| Avant               | 39        | 0.12%   |
| Smart Brazil        | 32        | 0.1%    |
| Goldkey             | 30        | 0.1%    |
| AMD                 | 30        | 0.1%    |
| Qimonda             | 25        | 0.08%   |
| Neo Forza           | 24        | 0.08%   |
| Unifosa             | 23        | 0.07%   |
| GeIL                | 21        | 0.07%   |
| Timetec             | 20        | 0.06%   |
| CSX                 | 20        | 0.06%   |
| ChangXin Memory     | 20        | 0.06%   |
| Innodisk            | 19        | 0.06%   |
| High Bridge         | 18        | 0.06%   |
| Lexar               | 17        | 0.05%   |
| SHARETRONIC         | 14        | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 324       | 0.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 273       | 0.81%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 263       | 0.78%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 200       | 0.59%   |
| Unknown                                                          | 194       | 0.57%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 193       | 0.57%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 190       | 0.56%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 187       | 0.55%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 178       | 0.53%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 175       | 0.52%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 171       | 0.51%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 170       | 0.5%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 170       | 0.5%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 167       | 0.49%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 165       | 0.49%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 156       | 0.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 154       | 0.46%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 154       | 0.46%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 145       | 0.43%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 139       | 0.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 136       | 0.4%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 136       | 0.4%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 134       | 0.4%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 132       | 0.39%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 132       | 0.39%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 129       | 0.38%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 129       | 0.38%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 128       | 0.38%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 127       | 0.38%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 121       | 0.36%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 120       | 0.36%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 117       | 0.35%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 114       | 0.34%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 112       | 0.33%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 109       | 0.32%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 106       | 0.31%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 101       | 0.3%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 101       | 0.3%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 100       | 0.3%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 99        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind            | Computers | Percent |
|-----------------|-----------|---------|
| DDR4            | 13773     | 50.24%  |
| DDR3            | 8377      | 30.55%  |
| LPDDR4          | 1222      | 4.46%   |
| DDR2            | 963       | 3.51%   |
| LPDDR3          | 880       | 3.21%   |
| Unknown         | 657       | 2.4%    |
| SDRAM           | 602       | 2.2%    |
| DDR5            | 494       | 1.8%    |
| LPDDR5          | 241       | 0.88%   |
| DDR             | 145       | 0.53%   |
| DRAM            | 59        | 0.22%   |
| EEPROM          | 2         | 0.01%   |
| Logical non-vol | 1         | 0.004%  |
| DDR2 FB-DIMM    | 1         | 0.004%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 15602     | 57.18%  |
| DIMM            | 8957      | 32.83%  |
| Row Of Chips    | 2411      | 8.84%   |
| Chip            | 135       | 0.49%   |
| Unknown         | 91        | 0.33%   |
| FB-DIMM         | 44        | 0.16%   |
| RIMM            | 39        | 0.14%   |
| Proprietary Car | 5         | 0.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 11595     | 38.96%  |
| 4096    | 7813      | 26.25%  |
| 16384   | 5185      | 17.42%  |
| 2048    | 3111      | 10.45%  |
| 32768   | 1167      | 3.92%   |
| 1024    | 723       | 2.43%   |
| 512     | 84        | 0.28%   |
| 65536   | 47        | 0.16%   |
| 256     | 12        | 0.04%   |
| 49152   | 6         | 0.02%   |
| 1536    | 5         | 0.02%   |
| 6144    | 4         | 0.01%   |
| 131072  | 2         | 0.01%   |
| 129408  | 2         | 0.01%   |
| 12288   | 2         | 0.01%   |
| 1       | 2         | 0.01%   |
| Unknown | 2         | 0.01%   |
| 258496  | 1         | 0.003%  |
| 64      | 1         | 0.003%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 5375      | 18.21%  |
| 2667    | 4952      | 16.78%  |
| 3200    | 4693      | 15.9%   |
| 2400    | 2250      | 7.62%   |
| 1333    | 1956      | 6.63%   |
| 2133    | 1766      | 5.98%   |
| 1334    | 769       | 2.61%   |
| 3600    | 569       | 1.93%   |
| 1867    | 566       | 1.92%   |
| 4267    | 549       | 1.86%   |
| 667     | 494       | 1.67%   |
| 800     | 482       | 1.63%   |
| Unknown | 412       | 1.4%    |
| 4800    | 370       | 1.25%   |
| 1067    | 310       | 1.05%   |
| 3266    | 296       | 1%      |
| 6400    | 255       | 0.86%   |
| 1066    | 243       | 0.82%   |
| 3733    | 207       | 0.7%    |
| 2666    | 205       | 0.69%   |
| 3000    | 184       | 0.62%   |
| 2933    | 183       | 0.62%   |
| 1866    | 171       | 0.58%   |
| 3400    | 168       | 0.57%   |
| 1800    | 163       | 0.55%   |
| 4199    | 135       | 0.46%   |
| 8400    | 128       | 0.43%   |
| 2048    | 103       | 0.35%   |
| 4266    | 86        | 0.29%   |
| 533     | 86        | 0.29%   |
| 3800    | 85        | 0.29%   |
| 3866    | 83        | 0.28%   |
| 3533    | 80        | 0.27%   |
| 2800    | 79        | 0.27%   |
| 3466    | 76        | 0.26%   |
| 400     | 70        | 0.24%   |
| 975     | 68        | 0.23%   |
| 5600    | 65        | 0.22%   |
| 3666    | 41        | 0.14%   |
| 333     | 40        | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Hewlett-Packard                    | 645       | 34.98%  |
| Brother Industries                 | 320       | 17.35%  |
| Canon                              | 298       | 16.16%  |
| Samsung Electronics                | 208       | 11.28%  |
| Seiko Epson                        | 159       | 8.62%   |
| Prolific Technology                | 34        | 1.84%   |
| Lexmark International              | 23        | 1.25%   |
| Dymo-CoStar                        | 22        | 1.19%   |
| QinHeng Electronics                | 19        | 1.03%   |
| Xerox                              | 17        | 0.92%   |
| Kyocera                            | 13        | 0.7%    |
| Pantum                             | 11        | 0.6%    |
| Oki Data                           | 10        | 0.54%   |
| Zebra                              | 9         | 0.49%   |
| STMicroelectronics                 | 8         | 0.43%   |
| Ricoh                              | 8         | 0.43%   |
| Dell                               | 8         | 0.43%   |
| Fuji Xerox                         | 4         | 0.22%   |
| Citizen                            | 4         | 0.22%   |
| Apple                              | 3         | 0.16%   |
| TSC Auto ID Technology             | 2         | 0.11%   |
| Konica Minolta                     | 2         | 0.11%   |
| BESTEASY                           | 2         | 0.11%   |
| ATEN International                 | 2         | 0.11%   |
| Zhuhai Poskey Technology           | 1         | 0.05%   |
| Xiaomi                             | 1         | 0.05%   |
| Star Micronics                     | 1         | 0.05%   |
| Panasonic (Matsushita)             | 1         | 0.05%   |
| MIIIW                              | 1         | 0.05%   |
| GODEX INTERNATIONAL                | 1         | 0.05%   |
| GCC                                | 1         | 0.05%   |
| Datamax-O'Neil                     | 1         | 0.05%   |
| Custom Engineering SPA             | 1         | 0.05%   |
| BIXOLON                            | 1         | 0.05%   |
| BeiJing LanXum Computer Technology | 1         | 0.05%   |
| ARGOX                              | 1         | 0.05%   |
| Unknown                            | 1         | 0.05%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port        | 34        | 1.82%   |
| HP DeskJet 2600 series               | 30        | 1.61%   |
| Samsung M2020 Series                 | 22        | 1.18%   |
| Canon PIXMA MG2500 Series            | 22        | 1.18%   |
| Brother Printer                      | 21        | 1.12%   |
| HP LaserJet 1020                     | 20        | 1.07%   |
| QinHeng CH340S                       | 19        | 1.02%   |
| HP ENVY 4520 series                  | 19        | 1.02%   |
| HP Deskjet 2540 series               | 19        | 1.02%   |
| Brother HL-2030 Laser Printer        | 19        | 1.02%   |
| HP DeskJet 3700 series               | 18        | 0.96%   |
| HP DeskJet 2130 series               | 17        | 0.91%   |
| Canon PIXMA MX920 Series             | 17        | 0.91%   |
| Samsung M2070 Series                 | 16        | 0.86%   |
| Canon PIXMA MG3600 Series            | 16        | 0.86%   |
| Samsung ML-216x Series Laser Printer | 15        | 0.8%    |
| HP LaserJet 1018                     | 15        | 0.8%    |
| HP DeskJet 3630 series               | 15        | 0.8%    |
| HP LaserJet 3050                     | 14        | 0.75%   |
| HP OfficeJet 3830 series             | 11        | 0.59%   |
| HP LaserJet Professional P1102w      | 11        | 0.59%   |
| HP ENVY 5000 series                  | 11        | 0.59%   |
| Seiko Epson Printer                  | 10        | 0.54%   |
| Samsung SCX-3400 Series              | 10        | 0.54%   |
| Samsung C48x Series                  | 10        | 0.54%   |
| HP Printing Support                  | 10        | 0.54%   |
| HP ENVY 5540 series                  | 10        | 0.54%   |
| HP DeskJet 2700 series               | 10        | 0.54%   |
| HP Deskjet 2050 J510                 | 10        | 0.54%   |
| HP Deskjet 1050 J410                 | 10        | 0.54%   |
| Canon CanoScan LiDE 300              | 10        | 0.54%   |
| Samsung M267x 287x Series            | 9         | 0.48%   |
| Samsung Composite Device             | 9         | 0.48%   |
| Oki Data USB Device                  | 9         | 0.48%   |
| Canon iP7200 series                  | 9         | 0.48%   |
| Seiko Epson L360 Series              | 8         | 0.43%   |
| Seiko Epson L3150 Series             | 8         | 0.43%   |
| HP LaserJet P1005                    | 8         | 0.43%   |
| HP Deskjet 3050A                     | 8         | 0.43%   |
| Dymo-CoStar LabelWriter 400          | 8         | 0.43%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 232       | 60.57%  |
| Seiko Epson                                    | 78        | 20.37%  |
| Hewlett-Packard                                | 42        | 10.97%  |
| Mustek Systems                                 | 9         | 2.35%   |
| Ultima Electronics                             | 6         | 1.57%   |
| Plustek                                        | 5         | 1.31%   |
| AGFA-Gevaert NV                                | 2         | 0.52%   |
| Acer Peripherals (now BenQ)                    | 2         | 0.52%   |
| UMAX                                           | 1         | 0.26%   |
| Syscan                                         | 1         | 0.26%   |
| Siemens Information and Communication Products | 1         | 0.26%   |
| Nikon                                          | 1         | 0.26%   |
| Minolta                                        | 1         | 0.26%   |
| Microtek International                         | 1         | 0.26%   |
| KYE Systems (Mouse Systems)                    | 1         | 0.26%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 35        | 9.09%   |
| Canon CanoScan LiDE 210                                                               | 30        | 7.79%   |
| Canon CanoScan LiDE 220                                                               | 25        | 6.49%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 22        | 5.71%   |
| Canon CanoScan LIDE 25                                                                | 22        | 5.71%   |
| Canon CanoScan LiDE 120                                                               | 15        | 3.9%    |
| Canon CanoScan N1240U/LiDE 30                                                         | 14        | 3.64%   |
| Canon CanoScan LiDE 100                                                               | 14        | 3.64%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 9         | 2.34%   |
| Canon CanoScan LiDE 200                                                               | 9         | 2.34%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 8         | 2.08%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 7         | 1.82%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 7         | 1.82%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 5         | 1.3%    |
| Seiko Epson Scanner                                                                   | 5         | 1.3%    |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                               | 5         | 1.3%    |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 5         | 1.3%    |
| Canon CanoScan 9000F Mark II                                                          | 5         | 1.3%    |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 4         | 1.04%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 4         | 1.04%   |
| Canon CanoScan LiDE 60                                                                | 4         | 1.04%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 3         | 0.78%   |
| Seiko Epson GT-F700 [Perfection V350]                                                 | 3         | 0.78%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 3         | 0.78%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 3         | 0.78%   |
| Mustek Systems SNAPSCAN e22                                                           | 3         | 0.78%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 3         | 0.78%   |
| HP ScanJet G4050                                                                      | 3         | 0.78%   |
| HP ScanJet 3970c                                                                      | 3         | 0.78%   |
| HP ScanJet 3300c                                                                      | 3         | 0.78%   |
| Canon CanoScan LiDE 700F                                                              | 3         | 0.78%   |
| Canon CanoScan LiDE 600F                                                              | 3         | 0.78%   |
| Canon CanoScan 8800F                                                                  | 3         | 0.78%   |
| Canon CanoScan 4400F                                                                  | 3         | 0.78%   |
| Canon CanoScan 4200F                                                                  | 3         | 0.78%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 2         | 0.52%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 2         | 0.52%   |
| Seiko Epson ES-D200 [GT-S50]                                                          | 2         | 0.52%   |
| Plustek 600dpi USB Scanner                                                            | 2         | 0.52%   |
| Mustek Systems BearPaw 2448 CU Pro                                                    | 2         | 0.52%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 8090      | 21.11%  |
| Microdia                               | 3714      | 9.69%   |
| IMC Networks                           | 3231      | 8.43%   |
| Realtek Semiconductor                  | 3229      | 8.42%   |
| Sunplus Innovation Technology          | 2215      | 5.78%   |
| Bison Electronics                      | 2009      | 5.24%   |
| Logitech                               | 1911      | 4.99%   |
| Quanta                                 | 1667      | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) | 1517      | 3.96%   |
| Apple                                  | 1346      | 3.51%   |
| Suyin                                  | 1251      | 3.26%   |
| Lite-On Technology                     | 866       | 2.26%   |
| Syntek                                 | 835       | 2.18%   |
| Acer                                   | 632       | 1.65%   |
| Silicon Motion                         | 563       | 1.47%   |
| Alcor Micro                            | 484       | 1.26%   |
| Luxvisions Innotech Limited            | 472       | 1.23%   |
| Samsung Electronics                    | 437       | 1.14%   |
| Microsoft                              | 387       | 1.01%   |
| Ricoh                                  | 380       | 0.99%   |
| Z-Star Microelectronics                | 229       | 0.6%    |
| Lenovo                                 | 218       | 0.57%   |
| Sonix Technology                       | 154       | 0.4%    |
| Importek                               | 141       | 0.37%   |
| Generalplus Technology                 | 127       | 0.33%   |
| Primax Electronics                     | 119       | 0.31%   |
| ALi                                    | 111       | 0.29%   |
| SunplusIT                              | 95        | 0.25%   |
| GEMBIRD                                | 88        | 0.23%   |
| ARC International                      | 88        | 0.23%   |
| Creative Technology                    | 87        | 0.23%   |
| OmniVision Technologies                | 86        | 0.22%   |
| Cubeternet                             | 77        | 0.2%    |
| KYE Systems (Mouse Systems)            | 61        | 0.16%   |
| Jieli Technology                       | 58        | 0.15%   |
| Sunplus Technology                     | 57        | 0.15%   |
| DigiTech                               | 57        | 0.15%   |
| Intel                                  | 53        | 0.14%   |
| icSpring                               | 52        | 0.14%   |
| MacroSilicon                           | 46        | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD           | 1661      | 4.3%    |
| Chicony Integrated Camera               | 1388      | 3.59%   |
| Realtek Integrated_Webcam_HD            | 1235      | 3.2%    |
| IMC Networks Integrated Camera          | 848       | 2.2%    |
| IMC Networks USB2.0 HD UVC WebCam       | 772       | 2%      |
| Sunplus Integrated_Webcam_HD            | 740       | 1.92%   |
| Chicony HD WebCam                       | 701       | 1.82%   |
| Bison Integrated Camera                 | 636       | 1.65%   |
| Syntek Integrated Camera                | 448       | 1.16%   |
| Logitech Webcam C270                    | 441       | 1.14%   |
| Samsung Galaxy series, misc. (MTP mode) | 430       | 1.11%   |
| Apple iPhone 5/5C/5S/6/SE               | 427       | 1.11%   |
| Realtek USB camera                      | 380       | 0.98%   |
| Chicony HP HD Camera                    | 368       | 0.95%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 361       | 0.93%   |
| Apple Built-in iSight                   | 360       | 0.93%   |
| Apple FaceTime HD Camera (Built-in)     | 308       | 0.8%    |
| Logitech HD Pro Webcam C920             | 302       | 0.78%   |
| Microdia Integrated Webcam              | 295       | 0.76%   |
| Chicony HP Truevision HD                | 274       | 0.71%   |
| Sunplus HD WebCam                       | 271       | 0.7%    |
| Lite-On Integrated Camera               | 270       | 0.7%    |
| Chicony HP TrueVision HD Camera         | 259       | 0.67%   |
| Chicony TOSHIBA Web Camera - HD         | 256       | 0.66%   |
| Chicony USB2.0 HD UVC WebCam            | 245       | 0.63%   |
| Chicony EasyCamera                      | 244       | 0.63%   |
| Chicony USB 2.0 Camera                  | 241       | 0.62%   |
| Quanta HD User Facing                   | 240       | 0.62%   |
| Quanta HP TrueVision HD Camera          | 238       | 0.62%   |
| Bison Lenovo EasyCamera                 | 229       | 0.59%   |
| Lite-On HP HD Camera                    | 227       | 0.59%   |
| Chicony HP Wide Vision HD Camera        | 216       | 0.56%   |
| Realtek Integrated Webcam               | 213       | 0.55%   |
| Chicony USB2.0 VGA UVC WebCam           | 213       | 0.55%   |
| Quanta HP HD Camera                     | 212       | 0.55%   |
| Bison SunplusIT Integrated Camera       | 208       | 0.54%   |
| Alcor Micro USB 2.0 Camera              | 205       | 0.53%   |
| Chicony USB2.0 Camera                   | 198       | 0.51%   |
| Chicony Lenovo EasyCamera               | 197       | 0.51%   |
| Bison HD Webcam                         | 195       | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 2653      | 34.55%  |
| Synaptics                          | 2038      | 26.54%  |
| Shenzhen Goodix Technology         | 1197      | 15.59%  |
| AuthenTec                          | 446       | 5.81%   |
| Elan Microelectronics              | 441       | 5.74%   |
| Upek                               | 389       | 5.07%   |
| LighTuning Technology              | 316       | 4.12%   |
| STMicroelectronics                 | 83        | 1.08%   |
| Realtek USB2.0 Finger Print Bridge | 40        | 0.52%   |
| Samsung Electronics                | 28        | 0.36%   |
| Focal-systems.Corp                 | 23        | 0.3%    |
| HOLTEK                             | 7         | 0.09%   |
| DigitalPersona                     | 4         | 0.05%   |
| Dell                               | 4         | 0.05%   |
| Microsoft                          | 3         | 0.04%   |
| GDMicroelectronics                 | 3         | 0.04%   |
| Futronic Technology                | 2         | 0.03%   |
| Suprema                            | 1         | 0.01%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 659       | 8.58%   |
| Shenzhen Goodix  FingerPrint Device                                        | 644       | 8.39%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 488       | 6.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 363       | 4.73%   |
| Shenzhen Goodix Fingerprint Reader                                         | 350       | 4.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 271       | 3.53%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 254       | 3.31%   |
| Elan ELAN:Fingerprint                                                      | 225       | 2.93%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 219       | 2.85%   |
| Shenzhen Goodix FingerPrint                                                | 203       | 2.64%   |
| Elan ELAN:ARM-M4                                                           | 198       | 2.58%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 195       | 2.54%   |
| Validity Sensors Synaptics WBDI                                            | 194       | 2.53%   |
| Validity Sensors VFS491                                                    | 186       | 2.42%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 182       | 2.37%   |
| Synaptics  WBDI                                                            | 179       | 2.33%   |
| Synaptics WBDI                                                             | 160       | 2.08%   |
| AuthenTec AES2810                                                          | 151       | 1.97%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 144       | 1.88%   |
| Validity Sensors Fingerprint scanner                                       | 141       | 1.84%   |
| Synaptics Fingerprint reader [HP G6]                                       | 141       | 1.84%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 135       | 1.76%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 133       | 1.73%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 131       | 1.71%   |
| Synaptics UWP WBDI                                                         | 128       | 1.67%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 121       | 1.58%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 116       | 1.51%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 114       | 1.48%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 108       | 1.41%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 94        | 1.22%   |
| STMicroelectronics Fingerprint Reader                                      | 83        | 1.08%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 82        | 1.07%   |
| AuthenTec Fingerprint Sensor                                               | 75        | 0.98%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 71        | 0.92%   |
| AuthenTec AES1600                                                          | 60        | 0.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 57        | 0.74%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 55        | 0.72%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 52        | 0.68%   |
| Validity Sensors VFS Fingerprint sensor                                    | 43        | 0.56%   |
| Unknown                                                                    | 42        | 0.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 1570      | 50.35%  |
| Alcor Micro                       | 747       | 23.96%  |
| O2 Micro                          | 217       | 6.96%   |
| Upek                              | 151       | 4.84%   |
| Lenovo                            | 150       | 4.81%   |
| Gemalto (was Gemplus)             | 55        | 1.76%   |
| Advanced Card Systems             | 40        | 1.28%   |
| SCM Microsystems                  | 38        | 1.22%   |
| OmniKey                           | 18        | 0.58%   |
| Realtek Semiconductor             | 15        | 0.48%   |
| Chicony Electronics               | 11        | 0.35%   |
| Bit4id                            | 11        | 0.35%   |
| Aladdin Knowledge Systems         | 11        | 0.35%   |
| Reiner SCT Kartensysteme          | 10        | 0.32%   |
| Giesecke & Devrient               | 10        | 0.32%   |
| Cherry                            | 10        | 0.32%   |
| Yubico.com                        | 9         | 0.29%   |
| VASCO Data Security International | 9         | 0.29%   |
| Hewlett-Packard                   | 6         | 0.19%   |
| Fujitsu Siemens Computers         | 6         | 0.19%   |
| Watchdata                         | 5         | 0.16%   |
| NXP Semiconductors                | 3         | 0.1%    |
| C3PO                              | 3         | 0.1%    |
| Aladdin R.D.                      | 3         | 0.1%    |
| Clay Logic                        | 2         | 0.06%   |
| Athena Smartcard Solutions        | 2         | 0.06%   |
| Aktiv                             | 2         | 0.06%   |
| SpringCard                        | 1         | 0.03%   |
| Kobil Systems                     | 1         | 0.03%   |
| Integrated Technology Express     | 1         | 0.03%   |
| Feitian Technologies              | 1         | 0.03%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 737       | 23.61%  |
| Broadcom BCM5880 Secure Applications Processor                               | 547       | 17.53%  |
| Broadcom 58200                                                               | 406       | 13.01%  |
| Broadcom 5880                                                                | 361       | 11.57%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 249       | 7.98%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 193       | 6.18%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 151       | 4.84%   |
| Lenovo Integrated Smart Card Reader                                          | 148       | 4.74%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 35        | 1.12%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 26        | 0.83%   |
| O2 Micro Oz776 SmartCard Reader                                              | 24        | 0.77%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 20        | 0.64%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 16        | 0.51%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 15        | 0.48%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 11        | 0.35%   |
| Aladdin Knowledge Systems Token JC                                           | 11        | 0.35%   |
| Bit4id miniLector EVO                                                        | 10        | 0.32%   |
| Alcor Micro Watchdata W 1981                                                 | 10        | 0.32%   |
| Advanced Card Systems ACR122U                                                | 10        | 0.32%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 9         | 0.29%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 9         | 0.29%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 7         | 0.22%   |
| OmniKey CardMan 3021 / 3121                                                  | 6         | 0.19%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 6         | 0.19%   |
| Giesecke & Devrient StarSign CUT S                                           | 6         | 0.19%   |
| Watchdata USB Key                                                            | 5         | 0.16%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 5         | 0.16%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 5         | 0.16%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 5         | 0.16%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 5         | 0.16%   |
| VASCO Data Security International DIGIPASS 870                               | 4         | 0.13%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 4         | 0.13%   |
| Giesecke & Devrient StarSign CUT                                             | 4         | 0.13%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 4         | 0.13%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 4         | 0.13%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 3         | 0.1%    |
| OmniKey CardMan 4321                                                         | 3         | 0.1%    |
| OmniKey CardMan 3121 (HID Technologies)                                      | 3         | 0.1%    |
| NXP Semiconductors PR533                                                     | 3         | 0.1%    |
| Cherry SmartTerminal XX1X                                                    | 3         | 0.1%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 45403     | 68.48%  |
| 1     | 16746     | 25.26%  |
| 2     | 3211      | 4.84%   |
| 3     | 552       | 0.83%   |
| 4     | 220       | 0.33%   |
| 5     | 76        | 0.11%   |
| 6     | 44        | 0.07%   |
| 7     | 22        | 0.03%   |
| 8     | 16        | 0.02%   |
| 9     | 8         | 0.01%   |
| 10    | 4         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 7571      | 30.05%  |
| Graphics card            | 5976      | 23.72%  |
| Net/wireless             | 3176      | 12.61%  |
| Chipcard                 | 2914      | 11.57%  |
| Communication controller | 1126      | 4.47%   |
| Multimedia controller    | 860       | 3.41%   |
| Unassigned class         | 736       | 2.92%   |
| Camera                   | 573       | 2.27%   |
| Bluetooth                | 530       | 2.1%    |
| Sound                    | 459       | 1.82%   |
| Storage                  | 379       | 1.5%    |
| Net/ethernet             | 235       | 0.93%   |
| Card reader              | 222       | 0.88%   |
| Network                  | 97        | 0.38%   |
| Modem                    | 92        | 0.37%   |
| Storage/raid             | 87        | 0.35%   |
| Flash memory             | 49        | 0.19%   |
| Dvb card                 | 43        | 0.17%   |
| Storage/ata              | 13        | 0.05%   |
| Storage/nvme             | 12        | 0.05%   |
| Tv card                  | 11        | 0.04%   |
| Storage/ide              | 11        | 0.04%   |
| Firewire controller      | 11        | 0.04%   |
| Video                    | 7         | 0.03%   |
| Wireless                 | 4         | 0.02%   |
| Unclassified device      | 1         | 0.004%  |

