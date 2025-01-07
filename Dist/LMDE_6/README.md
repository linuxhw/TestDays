LMDE 6 - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for LMDE 6.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/LMDE_6/Desktop/README.md) and [notebooks](/Dist/LMDE_6/Notebook/README.md).

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

Total: 729

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| PELADN        | WI-6                        | Desktop     | [537a11ae44](https://linux-hardware.org/?probe=537a11ae44) | Jan 06, 2025 |
| Medion        | E6214                       | Notebook    | [e72344f20c](https://linux-hardware.org/?probe=e72344f20c) | Jan 05, 2025 |
| Medion        | E6214                       | Notebook    | [1abed4b52d](https://linux-hardware.org/?probe=1abed4b52d) | Jan 05, 2025 |
| Apple         | MacBookAir6,2               | Notebook    | [2a0e5e8dee](https://linux-hardware.org/?probe=2a0e5e8dee) | Jan 04, 2025 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [d6e8f1ee6c](https://linux-hardware.org/?probe=d6e8f1ee6c) | Jan 04, 2025 |
| HP            | Laptop 15-ef3xxx            | Notebook    | [990ef26285](https://linux-hardware.org/?probe=990ef26285) | Jan 04, 2025 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [88d10a1126](https://linux-hardware.org/?probe=88d10a1126) | Jan 04, 2025 |
| Apple         | MacBookAir6,2               | Notebook    | [ba9cefc697](https://linux-hardware.org/?probe=ba9cefc697) | Jan 03, 2025 |
| PELADN        | WI-6                        | Desktop     | [ed403a09ce](https://linux-hardware.org/?probe=ed403a09ce) | Jan 01, 2025 |
| PELADN        | WI-6                        | Desktop     | [9961c80013](https://linux-hardware.org/?probe=9961c80013) | Dec 31, 2024 |
| PELADN        | WI-6                        | Desktop     | [ad75e2844c](https://linux-hardware.org/?probe=ad75e2844c) | Dec 31, 2024 |
| PELADN        | WI-6                        | Desktop     | [a4d452eb65](https://linux-hardware.org/?probe=a4d452eb65) | Dec 31, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [a91c16b9c4](https://linux-hardware.org/?probe=a91c16b9c4) | Dec 31, 2024 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [176c7dc908](https://linux-hardware.org/?probe=176c7dc908) | Dec 29, 2024 |
| Dell          | 0MWYPT A02                  | Desktop     | [3a7c58054c](https://linux-hardware.org/?probe=3a7c58054c) | Dec 29, 2024 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [f680af729c](https://linux-hardware.org/?probe=f680af729c) | Dec 28, 2024 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [0ac54971da](https://linux-hardware.org/?probe=0ac54971da) | Dec 28, 2024 |
| Dell          | Inspiron 5577               | Notebook    | [dabaffa853](https://linux-hardware.org/?probe=dabaffa853) | Dec 25, 2024 |
| Dell          | 0DT021 A02                  | Server      | [5de4c4a538](https://linux-hardware.org/?probe=5de4c4a538) | Dec 23, 2024 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [43e003f874](https://linux-hardware.org/?probe=43e003f874) | Dec 22, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8144311954](https://linux-hardware.org/?probe=8144311954) | Dec 22, 2024 |
| HP            | 2820h                       | Desktop     | [64ccd9e1f2](https://linux-hardware.org/?probe=64ccd9e1f2) | Dec 22, 2024 |
| Acer          | Aspire 5738                 | Notebook    | [edb35a4953](https://linux-hardware.org/?probe=edb35a4953) | Dec 17, 2024 |
| Sony          | VPCM12M1E                   | Notebook    | [eca3984533](https://linux-hardware.org/?probe=eca3984533) | Dec 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [68a46993af](https://linux-hardware.org/?probe=68a46993af) | Dec 15, 2024 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [ebcaaa33b0](https://linux-hardware.org/?probe=ebcaaa33b0) | Dec 15, 2024 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [787e3a402c](https://linux-hardware.org/?probe=787e3a402c) | Dec 14, 2024 |
| ASUSTek       | N551JK                      | Notebook    | [10b918146d](https://linux-hardware.org/?probe=10b918146d) | Dec 13, 2024 |
| Dell          | Precision 3551              | Notebook    | [598abdb472](https://linux-hardware.org/?probe=598abdb472) | Dec 13, 2024 |
| Acer          | Extensa 5220                | Notebook    | [864e664760](https://linux-hardware.org/?probe=864e664760) | Dec 10, 2024 |
| Lenovo        | ThinkPad E495 20NE0002US    | Notebook    | [690a841928](https://linux-hardware.org/?probe=690a841928) | Dec 10, 2024 |
| Lenovo        | IdeaPad Slim 3 14IAH8 83... | Notebook    | [132e6e2862](https://linux-hardware.org/?probe=132e6e2862) | Dec 09, 2024 |
| Sony          | VPCM12M1E                   | Notebook    | [e7896a9326](https://linux-hardware.org/?probe=e7896a9326) | Dec 08, 2024 |
| ASUSTek       | H81M-K                      | Desktop     | [4c7c8cc298](https://linux-hardware.org/?probe=4c7c8cc298) | Dec 08, 2024 |
| Lenovo        | Yoga Slim 6 14IAP8 82WU     | Notebook    | [ecbb2dfb26](https://linux-hardware.org/?probe=ecbb2dfb26) | Dec 07, 2024 |
| Acer          | Aspire 5738                 | Notebook    | [041abf44b0](https://linux-hardware.org/?probe=041abf44b0) | Dec 07, 2024 |
| Lenovo        | ThinkPad X240 20AM001JUS    | Notebook    | [1ac27908e6](https://linux-hardware.org/?probe=1ac27908e6) | Dec 06, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [5fd88a9482](https://linux-hardware.org/?probe=5fd88a9482) | Dec 04, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [8456ee2251](https://linux-hardware.org/?probe=8456ee2251) | Dec 03, 2024 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [d085327361](https://linux-hardware.org/?probe=d085327361) | Dec 02, 2024 |
| Lenovo        | ThinkPad T60 2007YQY        | Notebook    | [8d792cc626](https://linux-hardware.org/?probe=8d792cc626) | Dec 02, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [146d9d897a](https://linux-hardware.org/?probe=146d9d897a) | Dec 02, 2024 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [5dd8a1851e](https://linux-hardware.org/?probe=5dd8a1851e) | Dec 02, 2024 |
| Insyde        | BayTrail                    | Notebook    | [101b76beeb](https://linux-hardware.org/?probe=101b76beeb) | Dec 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fb5d35bd4b](https://linux-hardware.org/?probe=fb5d35bd4b) | Dec 01, 2024 |
| Lenovo        | ThinkCentre M58p 7220AVG    | Desktop     | [9d47a500ed](https://linux-hardware.org/?probe=9d47a500ed) | Dec 01, 2024 |
| Acer          | Aspire AV15-51              | Notebook    | [c98b2b5898](https://linux-hardware.org/?probe=c98b2b5898) | Dec 01, 2024 |
| Unknown       | Unknown                     | Notebook    | [678e33b8ed](https://linux-hardware.org/?probe=678e33b8ed) | Dec 01, 2024 |
| Fujitsu       | LIFEBOOK E753               | Notebook    | [e36fbc49ec](https://linux-hardware.org/?probe=e36fbc49ec) | Dec 01, 2024 |
| Lenovo        | ThinkPad X270 20HN001MUS    | Notebook    | [6c580a86e2](https://linux-hardware.org/?probe=6c580a86e2) | Nov 30, 2024 |
| Notebook      | W65_67SZ                    | Notebook    | [245be0630e](https://linux-hardware.org/?probe=245be0630e) | Nov 29, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [ca8808db77](https://linux-hardware.org/?probe=ca8808db77) | Nov 29, 2024 |
| Acer          | Spin SP514-51N              | Convertible | [ff213eb067](https://linux-hardware.org/?probe=ff213eb067) | Nov 29, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [fb2858b084](https://linux-hardware.org/?probe=fb2858b084) | Nov 28, 2024 |
| Lenovo        | ThinkPad neo 14 21DN0009... | Notebook    | [63a0ee38c2](https://linux-hardware.org/?probe=63a0ee38c2) | Nov 27, 2024 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [612c9b02a8](https://linux-hardware.org/?probe=612c9b02a8) | Nov 26, 2024 |
| Notebook      | W65_67SZ                    | Notebook    | [7cf2df4c2d](https://linux-hardware.org/?probe=7cf2df4c2d) | Nov 25, 2024 |
| PELADN        | WI-6                        | Desktop     | [deec076d09](https://linux-hardware.org/?probe=deec076d09) | Nov 24, 2024 |
| PELADN        | WI-6                        | Desktop     | [f1daf75b91](https://linux-hardware.org/?probe=f1daf75b91) | Nov 24, 2024 |
| HP            | Laptop 17z-cp300            | Notebook    | [be49e0c290](https://linux-hardware.org/?probe=be49e0c290) | Nov 23, 2024 |
| HP            | Laptop 17z-cp300            | Notebook    | [4090b82a10](https://linux-hardware.org/?probe=4090b82a10) | Nov 23, 2024 |
| Acer          | Aspire A315-510P            | Notebook    | [99993b0f3e](https://linux-hardware.org/?probe=99993b0f3e) | Nov 21, 2024 |
| TUXEDO        | InfinityBook S Gen8         | Notebook    | [ac4e85e111](https://linux-hardware.org/?probe=ac4e85e111) | Nov 21, 2024 |
| Notebook      | W65_67SZ                    | Notebook    | [c7eb463249](https://linux-hardware.org/?probe=c7eb463249) | Nov 20, 2024 |
| Toshiba       | Satellite P105              | Notebook    | [74a9b7015c](https://linux-hardware.org/?probe=74a9b7015c) | Nov 18, 2024 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [a087a2818f](https://linux-hardware.org/?probe=a087a2818f) | Nov 18, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [3f6a95ad11](https://linux-hardware.org/?probe=3f6a95ad11) | Nov 18, 2024 |
| Fujitsu Si... | AMILO Li 2735               | Notebook    | [afbab1e78c](https://linux-hardware.org/?probe=afbab1e78c) | Nov 17, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [da064fe75f](https://linux-hardware.org/?probe=da064fe75f) | Nov 16, 2024 |
| Dell          | 073MMW A03                  | Desktop     | [715ccc808c](https://linux-hardware.org/?probe=715ccc808c) | Nov 16, 2024 |
| Toshiba       | Satellite M100              | Notebook    | [655a407dd2](https://linux-hardware.org/?probe=655a407dd2) | Nov 15, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [bd75bc63f7](https://linux-hardware.org/?probe=bd75bc63f7) | Nov 15, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [7ac1792400](https://linux-hardware.org/?probe=7ac1792400) | Nov 14, 2024 |
| Lenovo        | ThinkPad T450 20BUS1110E    | Notebook    | [c6bc9a84e4](https://linux-hardware.org/?probe=c6bc9a84e4) | Nov 14, 2024 |
| Gigabyte      | A520M S2H                   | Desktop     | [53fa642cd5](https://linux-hardware.org/?probe=53fa642cd5) | Nov 13, 2024 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [70007038ab](https://linux-hardware.org/?probe=70007038ab) | Nov 13, 2024 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [97617e7ac0](https://linux-hardware.org/?probe=97617e7ac0) | Nov 10, 2024 |
| ASUSTek       | T101HA                      | Tablet      | [2aa1d5261d](https://linux-hardware.org/?probe=2aa1d5261d) | Nov 09, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [5ed52c1fdc](https://linux-hardware.org/?probe=5ed52c1fdc) | Nov 09, 2024 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [acecc3bec2](https://linux-hardware.org/?probe=acecc3bec2) | Nov 09, 2024 |
| HP            | ProBook 450 G2              | Notebook    | [db16e5b334](https://linux-hardware.org/?probe=db16e5b334) | Nov 09, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [01063d0f9e](https://linux-hardware.org/?probe=01063d0f9e) | Nov 08, 2024 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [856f712b05](https://linux-hardware.org/?probe=856f712b05) | Nov 08, 2024 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [40be935ed5](https://linux-hardware.org/?probe=40be935ed5) | Nov 06, 2024 |
| Conectar I... | SF20GM7                     | Notebook    | [1c43877e91](https://linux-hardware.org/?probe=1c43877e91) | Nov 06, 2024 |
| HP            | Laptop 15-bs2xx             | Notebook    | [fb25b57170](https://linux-hardware.org/?probe=fb25b57170) | Nov 06, 2024 |
| ASUSTek       | P8H67-M                     | Desktop     | [d7ef318b8e](https://linux-hardware.org/?probe=d7ef318b8e) | Nov 06, 2024 |
| MSI           | Prestige 15 A12SC           | Notebook    | [403f475ebb](https://linux-hardware.org/?probe=403f475ebb) | Nov 03, 2024 |
| ASUSTek       | X450LN                      | Notebook    | [029f170b3e](https://linux-hardware.org/?probe=029f170b3e) | Nov 02, 2024 |
| Conectar I... | SF20GM7                     | Notebook    | [95da818f37](https://linux-hardware.org/?probe=95da818f37) | Nov 02, 2024 |
| Intel         | H110D4-P1                   | Desktop     | [65e304fcef](https://linux-hardware.org/?probe=65e304fcef) | Nov 02, 2024 |
| AZW           | MINI S 10                   | Desktop     | [a76f3d4f56](https://linux-hardware.org/?probe=a76f3d4f56) | Nov 01, 2024 |
| AZW           | MINI S 10                   | Desktop     | [eae99fa9a9](https://linux-hardware.org/?probe=eae99fa9a9) | Nov 01, 2024 |
| HP            | Pavilion dv6000 (RY645EA... | Notebook    | [a9cb45608f](https://linux-hardware.org/?probe=a9cb45608f) | Nov 01, 2024 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [159bac7506](https://linux-hardware.org/?probe=159bac7506) | Nov 01, 2024 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [bd1050484e](https://linux-hardware.org/?probe=bd1050484e) | Oct 31, 2024 |
| Lenovo        | Unknown                     | Notebook    | [0fdc4e7dac](https://linux-hardware.org/?probe=0fdc4e7dac) | Oct 31, 2024 |
| HP            | 2820h                       | Desktop     | [940082e5de](https://linux-hardware.org/?probe=940082e5de) | Oct 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [cb80f674ac](https://linux-hardware.org/?probe=cb80f674ac) | Oct 30, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [9cc00f993a](https://linux-hardware.org/?probe=9cc00f993a) | Oct 29, 2024 |
| HP            | 1906                        | Desktop     | [2d314c1b57](https://linux-hardware.org/?probe=2d314c1b57) | Oct 28, 2024 |
| Lenovo        | ThinkPad T550 20CK004QUS    | Notebook    | [d4d5181e4f](https://linux-hardware.org/?probe=d4d5181e4f) | Oct 28, 2024 |
| Lenovo        | ThinkPad T550 20CK004QUS    | Notebook    | [c7b77b3285](https://linux-hardware.org/?probe=c7b77b3285) | Oct 27, 2024 |
| ASRock        | A320M-HDV                   | Desktop     | [7ae06e5667](https://linux-hardware.org/?probe=7ae06e5667) | Oct 27, 2024 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [91631ac2c3](https://linux-hardware.org/?probe=91631ac2c3) | Oct 27, 2024 |
| Dell          | Latitude D820               | Notebook    | [e8052d5ecd](https://linux-hardware.org/?probe=e8052d5ecd) | Oct 26, 2024 |
| HP            | EliteBook 850 G3            | Notebook    | [a62e77d2a5](https://linux-hardware.org/?probe=a62e77d2a5) | Oct 26, 2024 |
| Dell          | Latitude D820               | Notebook    | [69777b44d3](https://linux-hardware.org/?probe=69777b44d3) | Oct 25, 2024 |
| Dell          | Latitude E6430              | Notebook    | [7aa1bdef3c](https://linux-hardware.org/?probe=7aa1bdef3c) | Oct 25, 2024 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [38e3efc950](https://linux-hardware.org/?probe=38e3efc950) | Oct 24, 2024 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [60f87c4f6d](https://linux-hardware.org/?probe=60f87c4f6d) | Oct 24, 2024 |
| HP            | 2AFB                        | Desktop     | [c7b44337e2](https://linux-hardware.org/?probe=c7b44337e2) | Oct 23, 2024 |
| HP            | 2AFB                        | Desktop     | [cedecd78de](https://linux-hardware.org/?probe=cedecd78de) | Oct 23, 2024 |
| Lenovo        | ThinkPad T400s 28153VG      | Notebook    | [312c0a0fb9](https://linux-hardware.org/?probe=312c0a0fb9) | Oct 22, 2024 |
| Dell          | Latitude 5350               | Notebook    | [58f8fa615d](https://linux-hardware.org/?probe=58f8fa615d) | Oct 21, 2024 |
| Dell          | Latitude 5350               | Notebook    | [b2d8fecadb](https://linux-hardware.org/?probe=b2d8fecadb) | Oct 21, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B5402FEA... | Convertible | [9477b439b9](https://linux-hardware.org/?probe=9477b439b9) | Oct 20, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B5402FEA... | Convertible | [c7769abd75](https://linux-hardware.org/?probe=c7769abd75) | Oct 20, 2024 |
| Acer          | Aspire 5738                 | Notebook    | [ca83f1cc2d](https://linux-hardware.org/?probe=ca83f1cc2d) | Oct 19, 2024 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [50d12895aa](https://linux-hardware.org/?probe=50d12895aa) | Oct 18, 2024 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [2c7a8f6c86](https://linux-hardware.org/?probe=2c7a8f6c86) | Oct 17, 2024 |
| Fujitsu       | LIFEBOOK U759               | Notebook    | [fed82bdfb6](https://linux-hardware.org/?probe=fed82bdfb6) | Oct 17, 2024 |
| AZW           | GTR V01                     | Mini pc     | [e9502fa314](https://linux-hardware.org/?probe=e9502fa314) | Oct 13, 2024 |
| Toshiba       | Satellite L50D-B            | Notebook    | [a2287ef876](https://linux-hardware.org/?probe=a2287ef876) | Oct 12, 2024 |
| Acer          | Aspire 5738                 | Notebook    | [eb50a1a3c6](https://linux-hardware.org/?probe=eb50a1a3c6) | Oct 12, 2024 |
| PELADN        | WI-6                        | Desktop     | [475cbc4d32](https://linux-hardware.org/?probe=475cbc4d32) | Oct 12, 2024 |
| PELADN        | WI-6                        | Desktop     | [26845b5304](https://linux-hardware.org/?probe=26845b5304) | Oct 12, 2024 |
| PELADN        | WI-6                        | Desktop     | [0531287d03](https://linux-hardware.org/?probe=0531287d03) | Oct 12, 2024 |
| PELADN        | WI-6                        | Desktop     | [ab803d1e89](https://linux-hardware.org/?probe=ab803d1e89) | Oct 12, 2024 |
| Acer          | Aspire 5738                 | Notebook    | [b7da389696](https://linux-hardware.org/?probe=b7da389696) | Oct 12, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [cc8c1d6778](https://linux-hardware.org/?probe=cc8c1d6778) | Oct 11, 2024 |
| Medion        | TJ4125                      | Desktop     | [a371c066fd](https://linux-hardware.org/?probe=a371c066fd) | Oct 11, 2024 |
| Fujitsu       | D3427-A1 S26361-D3427-A1    | Desktop     | [31774f82cc](https://linux-hardware.org/?probe=31774f82cc) | Oct 11, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B5402FEA... | Convertible | [6e7991ae99](https://linux-hardware.org/?probe=6e7991ae99) | Oct 11, 2024 |
| Lenovo        | B50-70 80EU                 | Notebook    | [5c0fd8834f](https://linux-hardware.org/?probe=5c0fd8834f) | Oct 11, 2024 |
| Fujitsu       | D3427-A1 S26361-D3427-A1    | Desktop     | [f42bacdfa7](https://linux-hardware.org/?probe=f42bacdfa7) | Oct 11, 2024 |
| Dell          | Inspiron 5570               | Notebook    | [46275a960a](https://linux-hardware.org/?probe=46275a960a) | Oct 11, 2024 |
| AZW           | GTR V01                     | Mini pc     | [df73bf01cd](https://linux-hardware.org/?probe=df73bf01cd) | Oct 10, 2024 |
| Acer          | Aspire E5-521G              | Notebook    | [63755713f4](https://linux-hardware.org/?probe=63755713f4) | Oct 10, 2024 |
| Dell          | Inspiron 5570               | Notebook    | [c1fdcf2050](https://linux-hardware.org/?probe=c1fdcf2050) | Oct 10, 2024 |
| Lenovo        | ThinkPad T480 20L6S0EY00    | Notebook    | [123b9ee07a](https://linux-hardware.org/?probe=123b9ee07a) | Oct 09, 2024 |
| Medion        | TJ4125                      | Desktop     | [24e446e7a7](https://linux-hardware.org/?probe=24e446e7a7) | Oct 08, 2024 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [5aadf01aae](https://linux-hardware.org/?probe=5aadf01aae) | Oct 06, 2024 |
| Chuwi         | CoreBook X                  | Notebook    | [c2905b1bd7](https://linux-hardware.org/?probe=c2905b1bd7) | Oct 06, 2024 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [b0bd2a93c2](https://linux-hardware.org/?probe=b0bd2a93c2) | Oct 04, 2024 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [f216dafbba](https://linux-hardware.org/?probe=f216dafbba) | Oct 04, 2024 |
| Lenovo        | ThinkPad X61 Tablet 7764... | Notebook    | [4a002c0f20](https://linux-hardware.org/?probe=4a002c0f20) | Oct 04, 2024 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [060b69d0b3](https://linux-hardware.org/?probe=060b69d0b3) | Oct 01, 2024 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [bc7fdf7279](https://linux-hardware.org/?probe=bc7fdf7279) | Oct 01, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [df3520af77](https://linux-hardware.org/?probe=df3520af77) | Oct 01, 2024 |
| Lenovo        | ThinkPad T400s 28153VG      | Notebook    | [508b12a75b](https://linux-hardware.org/?probe=508b12a75b) | Oct 01, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [1eafc27f9d](https://linux-hardware.org/?probe=1eafc27f9d) | Sep 30, 2024 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [e9bbaa808d](https://linux-hardware.org/?probe=e9bbaa808d) | Sep 30, 2024 |
| Notebook      | N2x0WU                      | Notebook    | [7e061af782](https://linux-hardware.org/?probe=7e061af782) | Sep 29, 2024 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [51fe2ae08f](https://linux-hardware.org/?probe=51fe2ae08f) | Sep 29, 2024 |
| Dell          | XPS 13 9360                 | Notebook    | [4559019bac](https://linux-hardware.org/?probe=4559019bac) | Sep 28, 2024 |
| Lenovo        | ThinkPad X230 2330A17       | Notebook    | [ce28e0de6c](https://linux-hardware.org/?probe=ce28e0de6c) | Sep 27, 2024 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [dc7fdc65d6](https://linux-hardware.org/?probe=dc7fdc65d6) | Sep 26, 2024 |
| ASRock        | A320M-HDV                   | Desktop     | [23c6bbe37a](https://linux-hardware.org/?probe=23c6bbe37a) | Sep 25, 2024 |
| ASUSTek       | ZenBook UX434FAC_UX433FA... | Notebook    | [76bce69bcf](https://linux-hardware.org/?probe=76bce69bcf) | Sep 24, 2024 |
| Lenovo        | ThinkPad X230 2330A17       | Notebook    | [4c04674392](https://linux-hardware.org/?probe=4c04674392) | Sep 23, 2024 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [d2315eef29](https://linux-hardware.org/?probe=d2315eef29) | Sep 22, 2024 |
| HP            | Pavilion dv5000 (RG937EA... | Notebook    | [a022208bc5](https://linux-hardware.org/?probe=a022208bc5) | Sep 22, 2024 |
| HP            | Pavilion dv5000 (RG937EA... | Notebook    | [ce20a826eb](https://linux-hardware.org/?probe=ce20a826eb) | Sep 22, 2024 |
| Biostar       | P31-A7                      | Desktop     | [8f249ff212](https://linux-hardware.org/?probe=8f249ff212) | Sep 22, 2024 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [10e3fce76a](https://linux-hardware.org/?probe=10e3fce76a) | Sep 21, 2024 |
| HP            | Laptop                      | Notebook    | [fa20696672](https://linux-hardware.org/?probe=fa20696672) | Sep 21, 2024 |
| MSI           | B350 TOMAHAWK               | Desktop     | [f87173b8b2](https://linux-hardware.org/?probe=f87173b8b2) | Sep 20, 2024 |
| Toshiba       | Satellite L745              | Notebook    | [b60f22f240](https://linux-hardware.org/?probe=b60f22f240) | Sep 19, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JKC... | Notebook    | [186c21f29f](https://linux-hardware.org/?probe=186c21f29f) | Sep 19, 2024 |
| Dell          | 0T568R A00                  | Desktop     | [1e475fbe85](https://linux-hardware.org/?probe=1e475fbe85) | Sep 18, 2024 |
| ASRock        | B650M Pro RS WiFi           | Desktop     | [8f68843f40](https://linux-hardware.org/?probe=8f68843f40) | Sep 18, 2024 |
| Lenovo        | ThinkPad T480s 20L8S9JE0... | Notebook    | [9ef5814db9](https://linux-hardware.org/?probe=9ef5814db9) | Sep 17, 2024 |
| ASUSTek       | V241EA                      | All in one  | [e02555bd07](https://linux-hardware.org/?probe=e02555bd07) | Sep 15, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [af848409fc](https://linux-hardware.org/?probe=af848409fc) | Sep 15, 2024 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [4815c901f0](https://linux-hardware.org/?probe=4815c901f0) | Sep 15, 2024 |
| Lenovo        | Yoga 500-14IBD 80N4         | Notebook    | [09dda9115e](https://linux-hardware.org/?probe=09dda9115e) | Sep 12, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [60a485333f](https://linux-hardware.org/?probe=60a485333f) | Sep 11, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [47ffb7c0c0](https://linux-hardware.org/?probe=47ffb7c0c0) | Sep 11, 2024 |
| Fujitsu       | LIFEBOOK U7512              | Notebook    | [fefdfd4982](https://linux-hardware.org/?probe=fefdfd4982) | Sep 10, 2024 |
| Dell          | Latitude 5550               | Notebook    | [b409cdf8ab](https://linux-hardware.org/?probe=b409cdf8ab) | Sep 09, 2024 |
| PELADN        | WI-6                        | Desktop     | [1a20712dde](https://linux-hardware.org/?probe=1a20712dde) | Sep 08, 2024 |
| PELADN        | WI-6                        | Desktop     | [c250dba9ae](https://linux-hardware.org/?probe=c250dba9ae) | Sep 07, 2024 |
| Acer          | Spin SP514-51N              | Convertible | [0bf8c23be2](https://linux-hardware.org/?probe=0bf8c23be2) | Sep 07, 2024 |
| Dell          | XPS 15 9510                 | Notebook    | [c36d4de7b4](https://linux-hardware.org/?probe=c36d4de7b4) | Sep 06, 2024 |
| HP            | Pavilion dv2700             | Notebook    | [dae4a490a7](https://linux-hardware.org/?probe=dae4a490a7) | Sep 06, 2024 |
| HP            | Pavilion dv2700             | Notebook    | [3dd25c19fb](https://linux-hardware.org/?probe=3dd25c19fb) | Sep 06, 2024 |
| HP            | Notebook                    | Notebook    | [03bdb73471](https://linux-hardware.org/?probe=03bdb73471) | Sep 05, 2024 |
| Lenovo        | ThinkPad T520 4243W63       | Notebook    | [3e79035d31](https://linux-hardware.org/?probe=3e79035d31) | Sep 03, 2024 |
| Microsoft     | Surface Go 2                | Tablet      | [fcdcfb0dc3](https://linux-hardware.org/?probe=fcdcfb0dc3) | Sep 03, 2024 |
| HP            | 829A                        | Mini pc     | [3183148718](https://linux-hardware.org/?probe=3183148718) | Sep 02, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [386d564b97](https://linux-hardware.org/?probe=386d564b97) | Aug 31, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [db7197814c](https://linux-hardware.org/?probe=db7197814c) | Aug 31, 2024 |
| Lenovo        | Slim 7 16IAH7 82VB          | Notebook    | [f45acc7e20](https://linux-hardware.org/?probe=f45acc7e20) | Aug 31, 2024 |
| MSI           | A68HM GRENADE               | Desktop     | [d823f74970](https://linux-hardware.org/?probe=d823f74970) | Aug 29, 2024 |
| MSI           | A68HM GRENADE               | Desktop     | [10f8a9b965](https://linux-hardware.org/?probe=10f8a9b965) | Aug 29, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [a33c000c3c](https://linux-hardware.org/?probe=a33c000c3c) | Aug 29, 2024 |
| ASUSTek       | G11CD-K                     | Desktop     | [97151fcf68](https://linux-hardware.org/?probe=97151fcf68) | Aug 27, 2024 |
| MSI           | GP60 2QE                    | Notebook    | [fe42ba85a4](https://linux-hardware.org/?probe=fe42ba85a4) | Aug 24, 2024 |
| Framework     | Laptop                      | Notebook    | [ec6fd2129b](https://linux-hardware.org/?probe=ec6fd2129b) | Aug 23, 2024 |
| Samsung       | 370E4J/370E4Q               | Notebook    | [5627935947](https://linux-hardware.org/?probe=5627935947) | Aug 21, 2024 |
| Acer          | Aspire 5732Z                | Notebook    | [1782abff4d](https://linux-hardware.org/?probe=1782abff4d) | Aug 20, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [29bb2038d4](https://linux-hardware.org/?probe=29bb2038d4) | Aug 20, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [bc5d967ee2](https://linux-hardware.org/?probe=bc5d967ee2) | Aug 20, 2024 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [c771260335](https://linux-hardware.org/?probe=c771260335) | Aug 19, 2024 |
| Acer          | Swift SF315-52G             | Notebook    | [7e4cececee](https://linux-hardware.org/?probe=7e4cececee) | Aug 16, 2024 |
| PELADN        | WI-6                        | Desktop     | [862128760a](https://linux-hardware.org/?probe=862128760a) | Aug 15, 2024 |
| Acer          | Aspire 5732Z                | Notebook    | [399dfa9617](https://linux-hardware.org/?probe=399dfa9617) | Aug 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [1647e0bf63](https://linux-hardware.org/?probe=1647e0bf63) | Aug 14, 2024 |
| Shenzhen M... | DNBIB                       | Desktop     | [b96a88e34c](https://linux-hardware.org/?probe=b96a88e34c) | Aug 13, 2024 |
| PELADN        | WI-6                        | Desktop     | [e23677d993](https://linux-hardware.org/?probe=e23677d993) | Aug 13, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [586288c72b](https://linux-hardware.org/?probe=586288c72b) | Aug 13, 2024 |
| ASRock        | X370 Killer SLI             | Desktop     | [e2b748b24a](https://linux-hardware.org/?probe=e2b748b24a) | Aug 11, 2024 |
| MACHINIST     | X99 PR9                     | Desktop     | [fd08f80e3b](https://linux-hardware.org/?probe=fd08f80e3b) | Aug 10, 2024 |
| Olidata       | REGLO LIVE                  | Other       | [4fd22e0e76](https://linux-hardware.org/?probe=4fd22e0e76) | Aug 09, 2024 |
| Acer          | Aspire 5750G                | Notebook    | [f351efafd1](https://linux-hardware.org/?probe=f351efafd1) | Aug 08, 2024 |
| Fujitsu       | CELSIUS H7510               | Notebook    | [ece1093c90](https://linux-hardware.org/?probe=ece1093c90) | Aug 08, 2024 |
| HP            | ENVY 15                     | Notebook    | [969779119a](https://linux-hardware.org/?probe=969779119a) | Aug 08, 2024 |
| Olidata       | REGLO LIVE                  | Other       | [335ce4e028](https://linux-hardware.org/?probe=335ce4e028) | Aug 08, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | Notebook    | [57987db9cf](https://linux-hardware.org/?probe=57987db9cf) | Aug 08, 2024 |
| MSI           | X670E GAMING PLUS WIFI      | Desktop     | [ac8d4298ad](https://linux-hardware.org/?probe=ac8d4298ad) | Aug 06, 2024 |
| HP            | ProBook 4720s               | Notebook    | [f017d85cdb](https://linux-hardware.org/?probe=f017d85cdb) | Aug 06, 2024 |
| Gigabyte      | B760M DS3H DDR4             | Desktop     | [f65ee4168b](https://linux-hardware.org/?probe=f65ee4168b) | Aug 06, 2024 |
| HP            | x2 210 G2                   | Tablet      | [b4f46406f5](https://linux-hardware.org/?probe=b4f46406f5) | Aug 04, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [8902556150](https://linux-hardware.org/?probe=8902556150) | Aug 04, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [da35f8a43c](https://linux-hardware.org/?probe=da35f8a43c) | Aug 04, 2024 |
| GEEKOM        | A7                          | Desktop     | [a642de18b4](https://linux-hardware.org/?probe=a642de18b4) | Aug 03, 2024 |
| GEEKOM        | A7                          | Desktop     | [5e4d479deb](https://linux-hardware.org/?probe=5e4d479deb) | Aug 03, 2024 |
| ASUSTek       | X540LA                      | Notebook    | [802e2c494e](https://linux-hardware.org/?probe=802e2c494e) | Aug 01, 2024 |
| ASUSTek       | X540LA                      | Notebook    | [5db4299943](https://linux-hardware.org/?probe=5db4299943) | Aug 01, 2024 |
| MSI           | B560M PRO-E                 | Desktop     | [e822834efe](https://linux-hardware.org/?probe=e822834efe) | Jul 31, 2024 |
| Lenovo        | ThinkPad T520 4243W63       | Notebook    | [59769429e0](https://linux-hardware.org/?probe=59769429e0) | Jul 31, 2024 |
| Lenovo        | ThinkPad T520 4243W63       | Notebook    | [1e8c2ea6ef](https://linux-hardware.org/?probe=1e8c2ea6ef) | Jul 31, 2024 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [a7c539d689](https://linux-hardware.org/?probe=a7c539d689) | Jul 27, 2024 |
| AWOW          | PC BOX                      | Mini pc     | [e529565d58](https://linux-hardware.org/?probe=e529565d58) | Jul 27, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [9a733fe6d3](https://linux-hardware.org/?probe=9a733fe6d3) | Jul 26, 2024 |
| Medion        | TJ4125                      | Desktop     | [8a4a376199](https://linux-hardware.org/?probe=8a4a376199) | Jul 25, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [5261c040c3](https://linux-hardware.org/?probe=5261c040c3) | Jul 25, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [9f6655b549](https://linux-hardware.org/?probe=9f6655b549) | Jul 25, 2024 |
| Unknown       | Unknown                     | Desktop     | [9f21efbdc8](https://linux-hardware.org/?probe=9f21efbdc8) | Jul 24, 2024 |
| Acer          | Aspire E1-531               | Notebook    | [07ce6ddc7c](https://linux-hardware.org/?probe=07ce6ddc7c) | Jul 24, 2024 |
| Lenovo        | 334A NOK                    | Mini pc     | [96bc976697](https://linux-hardware.org/?probe=96bc976697) | Jul 24, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [c031d1b6ab](https://linux-hardware.org/?probe=c031d1b6ab) | Jul 22, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [ae9443b715](https://linux-hardware.org/?probe=ae9443b715) | Jul 21, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a0300a1940](https://linux-hardware.org/?probe=a0300a1940) | Jul 21, 2024 |
| Medion        | TJ4125                      | Desktop     | [50af4fbfc4](https://linux-hardware.org/?probe=50af4fbfc4) | Jul 20, 2024 |
| Toshiba       | TECRA X40-D                 | Notebook    | [cf856c7d5f](https://linux-hardware.org/?probe=cf856c7d5f) | Jul 18, 2024 |
| Intel         | H81                         | Desktop     | [22d5bf41a9](https://linux-hardware.org/?probe=22d5bf41a9) | Jul 17, 2024 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [ae5c5e7f74](https://linux-hardware.org/?probe=ae5c5e7f74) | Jul 16, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [b0be759962](https://linux-hardware.org/?probe=b0be759962) | Jul 16, 2024 |
| ASRock        | H270M Pro4                  | Desktop     | [0098f75d27](https://linux-hardware.org/?probe=0098f75d27) | Jul 16, 2024 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [95700ccdf3](https://linux-hardware.org/?probe=95700ccdf3) | Jul 14, 2024 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [885ee058e5](https://linux-hardware.org/?probe=885ee058e5) | Jul 13, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [af6036e896](https://linux-hardware.org/?probe=af6036e896) | Jul 11, 2024 |
| PELADN        | WI-6                        | Desktop     | [5bf72a6fb4](https://linux-hardware.org/?probe=5bf72a6fb4) | Jul 07, 2024 |
| Medion        | TJ4125                      | Desktop     | [d6eea34c91](https://linux-hardware.org/?probe=d6eea34c91) | Jul 06, 2024 |
| PELADN        | WI-6                        | Desktop     | [bf8f9bc3b3](https://linux-hardware.org/?probe=bf8f9bc3b3) | Jul 06, 2024 |
| Medion        | TJ4125                      | Desktop     | [01eef112d6](https://linux-hardware.org/?probe=01eef112d6) | Jul 06, 2024 |
| ASUSTek       | X551CA                      | Notebook    | [c1d5a9a08d](https://linux-hardware.org/?probe=c1d5a9a08d) | Jul 06, 2024 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [11c7e97835](https://linux-hardware.org/?probe=11c7e97835) | Jul 05, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [b5c7b17e9f](https://linux-hardware.org/?probe=b5c7b17e9f) | Jul 05, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [873d00bade](https://linux-hardware.org/?probe=873d00bade) | Jul 04, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [f600a1f5e7](https://linux-hardware.org/?probe=f600a1f5e7) | Jul 04, 2024 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [7e78c3299d](https://linux-hardware.org/?probe=7e78c3299d) | Jul 03, 2024 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [6773aae4ed](https://linux-hardware.org/?probe=6773aae4ed) | Jun 30, 2024 |
| Intel         | H61                         | Desktop     | [0373caa5cc](https://linux-hardware.org/?probe=0373caa5cc) | Jun 28, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [4070fa9d3e](https://linux-hardware.org/?probe=4070fa9d3e) | Jun 28, 2024 |
| ASUSTek       | PRIME N100I-D D4            | Desktop     | [3ef6295470](https://linux-hardware.org/?probe=3ef6295470) | Jun 27, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [e58ec4ab82](https://linux-hardware.org/?probe=e58ec4ab82) | Jun 27, 2024 |
| Dell          | 0T568R A00                  | Desktop     | [be28ff899b](https://linux-hardware.org/?probe=be28ff899b) | Jun 25, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [250352499d](https://linux-hardware.org/?probe=250352499d) | Jun 24, 2024 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [75050a724c](https://linux-hardware.org/?probe=75050a724c) | Jun 24, 2024 |
| Notebook      | W65_67SZ                    | Notebook    | [3b720bff42](https://linux-hardware.org/?probe=3b720bff42) | Jun 22, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [31708d14fb](https://linux-hardware.org/?probe=31708d14fb) | Jun 22, 2024 |
| ASUSTek       | K50IJ                       | Notebook    | [2eb9b0bf9b](https://linux-hardware.org/?probe=2eb9b0bf9b) | Jun 22, 2024 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [286891ce23](https://linux-hardware.org/?probe=286891ce23) | Jun 22, 2024 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [43ddc59145](https://linux-hardware.org/?probe=43ddc59145) | Jun 22, 2024 |
| Dell          | 048DY8 A01                  | Desktop     | [b044c0600b](https://linux-hardware.org/?probe=b044c0600b) | Jun 22, 2024 |
| Lenovo        | ThinkCentre M71e 3133A8S    | Desktop     | [e73d8477a0](https://linux-hardware.org/?probe=e73d8477a0) | Jun 21, 2024 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [fcc5c05273](https://linux-hardware.org/?probe=fcc5c05273) | Jun 20, 2024 |
| HP            | 3397                        | Desktop     | [6156808fc9](https://linux-hardware.org/?probe=6156808fc9) | Jun 20, 2024 |
| HP            | 3397                        | Desktop     | [28f359e68a](https://linux-hardware.org/?probe=28f359e68a) | Jun 20, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [86fb4cb7e8](https://linux-hardware.org/?probe=86fb4cb7e8) | Jun 18, 2024 |
| ASUSTek       | P7P55 LX                    | Desktop     | [a8754caf68](https://linux-hardware.org/?probe=a8754caf68) | Jun 17, 2024 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [cb0f2121d5](https://linux-hardware.org/?probe=cb0f2121d5) | Jun 14, 2024 |
| Shenzhen M... | F7BRC                       | Desktop     | [c5fa0bb59b](https://linux-hardware.org/?probe=c5fa0bb59b) | Jun 10, 2024 |
| HP            | Pavilion dv6                | Notebook    | [0010ed731f](https://linux-hardware.org/?probe=0010ed731f) | Jun 08, 2024 |
| HP            | ENVY Laptop 13-aq1xxx       | Notebook    | [3ef8d7d35a](https://linux-hardware.org/?probe=3ef8d7d35a) | Jun 08, 2024 |
| Dell          | Inspiron 3501               | Notebook    | [7bd7c51885](https://linux-hardware.org/?probe=7bd7c51885) | Jun 07, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [55b98015cb](https://linux-hardware.org/?probe=55b98015cb) | Jun 06, 2024 |
| Lenovo        | 500w Gen 3 82J3             | Convertible | [bec9de1440](https://linux-hardware.org/?probe=bec9de1440) | Jun 06, 2024 |
| Lenovo        | 500w Gen 3 82J3             | Convertible | [d82bb98114](https://linux-hardware.org/?probe=d82bb98114) | Jun 06, 2024 |
| ASUSTek       | A7F                         | Notebook    | [d2c993325b](https://linux-hardware.org/?probe=d2c993325b) | Jun 05, 2024 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [7c63ac7810](https://linux-hardware.org/?probe=7c63ac7810) | Jun 04, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [0707d81b82](https://linux-hardware.org/?probe=0707d81b82) | Jun 03, 2024 |
| TENKU         | Mobile S10                  | Convertible | [e9016f6223](https://linux-hardware.org/?probe=e9016f6223) | Jun 02, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [187d6649ae](https://linux-hardware.org/?probe=187d6649ae) | Jun 02, 2024 |
| Medion        | E6214                       | Notebook    | [a67672f4f1](https://linux-hardware.org/?probe=a67672f4f1) | Jun 01, 2024 |
| Medion        | E6214                       | Notebook    | [3e6d7287eb](https://linux-hardware.org/?probe=3e6d7287eb) | Jun 01, 2024 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [b56aaa479c](https://linux-hardware.org/?probe=b56aaa479c) | May 28, 2024 |
| ASUSTek       | 1201N                       | Notebook    | [6466d5ce59](https://linux-hardware.org/?probe=6466d5ce59) | May 27, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [02fb324096](https://linux-hardware.org/?probe=02fb324096) | May 23, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [7c07d6eceb](https://linux-hardware.org/?probe=7c07d6eceb) | May 23, 2024 |
| MSI           | A320M-A PRO MAX             | Desktop     | [ee19bbcc37](https://linux-hardware.org/?probe=ee19bbcc37) | May 19, 2024 |
| Dell          | Latitude 5590               | Notebook    | [4b5982bff4](https://linux-hardware.org/?probe=4b5982bff4) | May 19, 2024 |
| Notebook      | W65_67SZ                    | Notebook    | [47bb1315ce](https://linux-hardware.org/?probe=47bb1315ce) | May 19, 2024 |
| ASUSTek       | P8H61-M                     | Desktop     | [451e286c21](https://linux-hardware.org/?probe=451e286c21) | May 18, 2024 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [2736095341](https://linux-hardware.org/?probe=2736095341) | May 18, 2024 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [9ae2bfab73](https://linux-hardware.org/?probe=9ae2bfab73) | May 18, 2024 |
| ASUSTek       | 900                         | Notebook    | [770a3f0d8d](https://linux-hardware.org/?probe=770a3f0d8d) | May 17, 2024 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [f0f7c823e6](https://linux-hardware.org/?probe=f0f7c823e6) | May 17, 2024 |
| Notebook      | P65xHP                      | Notebook    | [809f680e12](https://linux-hardware.org/?probe=809f680e12) | May 16, 2024 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [57e0f5eb29](https://linux-hardware.org/?probe=57e0f5eb29) | May 13, 2024 |
| Samsung       | RV415/RV515                 | Notebook    | [9ae57537b3](https://linux-hardware.org/?probe=9ae57537b3) | May 13, 2024 |
| PELADN        | WI-6                        | Desktop     | [4cabf19872](https://linux-hardware.org/?probe=4cabf19872) | May 13, 2024 |
| Dell          | Latitude E6510              | Notebook    | [c1d8e78181](https://linux-hardware.org/?probe=c1d8e78181) | May 12, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [180ba77304](https://linux-hardware.org/?probe=180ba77304) | May 12, 2024 |
| Notebook      | W250EGQ / W270EGQ           | Notebook    | [50c20659c5](https://linux-hardware.org/?probe=50c20659c5) | May 11, 2024 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [1f7c62ca20](https://linux-hardware.org/?probe=1f7c62ca20) | May 11, 2024 |
| ASUSTek       | P5Q SE2                     | Desktop     | [0a49b531a8](https://linux-hardware.org/?probe=0a49b531a8) | May 10, 2024 |
| Maibenben     | Perfectum Series            | Notebook    | [d6d3c7760c](https://linux-hardware.org/?probe=d6d3c7760c) | May 10, 2024 |
| Acer          | Aspire AL14-31P             | Notebook    | [2f7ab2437f](https://linux-hardware.org/?probe=2f7ab2437f) | May 09, 2024 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [0a6d61d9f6](https://linux-hardware.org/?probe=0a6d61d9f6) | May 09, 2024 |
| GEEKOM        | Mini Air12                  | Server      | [c02c2be45e](https://linux-hardware.org/?probe=c02c2be45e) | May 08, 2024 |
| Acer          | Aspire AL14-31P             | Notebook    | [fc4db570af](https://linux-hardware.org/?probe=fc4db570af) | May 08, 2024 |
| ASUSTek       | P5Q SE2                     | Desktop     | [cf126cd087](https://linux-hardware.org/?probe=cf126cd087) | May 08, 2024 |
| PELADN        | WI-6                        | Desktop     | [73069ab9f5](https://linux-hardware.org/?probe=73069ab9f5) | May 07, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [9176ad5eb1](https://linux-hardware.org/?probe=9176ad5eb1) | May 04, 2024 |
| Dell          | 0V0D45 A01                  | All in one  | [8ac266bc9b](https://linux-hardware.org/?probe=8ac266bc9b) | May 03, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [2837d61bc4](https://linux-hardware.org/?probe=2837d61bc4) | May 03, 2024 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [9d375acdb0](https://linux-hardware.org/?probe=9d375acdb0) | May 03, 2024 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [1ae07ba421](https://linux-hardware.org/?probe=1ae07ba421) | May 01, 2024 |
| HP            | Compaq 6730s                | Notebook    | [ab6d479788](https://linux-hardware.org/?probe=ab6d479788) | May 01, 2024 |
| ASUSTek       | H81-PLUS                    | Desktop     | [efe7c01899](https://linux-hardware.org/?probe=efe7c01899) | May 01, 2024 |
| ASUSTek       | H81-PLUS                    | Desktop     | [512660cdbc](https://linux-hardware.org/?probe=512660cdbc) | May 01, 2024 |
| Unknown       | Unknown                     | Notebook    | [a677f40065](https://linux-hardware.org/?probe=a677f40065) | Apr 30, 2024 |
| HP            | ProBook 450 G1              | Notebook    | [5f5030ef83](https://linux-hardware.org/?probe=5f5030ef83) | Apr 29, 2024 |
| Medion        | TJ4125                      | Desktop     | [5107c56945](https://linux-hardware.org/?probe=5107c56945) | Apr 29, 2024 |
| Fujitsu       | D3171-A1 S26361-D3171-A1    | Desktop     | [a52ce5dea5](https://linux-hardware.org/?probe=a52ce5dea5) | Apr 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [bc0e0ae6b8](https://linux-hardware.org/?probe=bc0e0ae6b8) | Apr 25, 2024 |
| ASUSTek       | X541UVK                     | Notebook    | [422fd329a8](https://linux-hardware.org/?probe=422fd329a8) | Apr 25, 2024 |
| Pegatron      | 2A94                        | Desktop     | [3673d4e290](https://linux-hardware.org/?probe=3673d4e290) | Apr 25, 2024 |
| Lenovo        | V15 G4 IAH 83FS             | Notebook    | [b922fc6d5e](https://linux-hardware.org/?probe=b922fc6d5e) | Apr 24, 2024 |
| Acer          | TravelMate 4070             | Notebook    | [99e797eb28](https://linux-hardware.org/?probe=99e797eb28) | Apr 23, 2024 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [b7a4824162](https://linux-hardware.org/?probe=b7a4824162) | Apr 23, 2024 |
| HP            | 8876 11                     | Desktop     | [b15b96ee62](https://linux-hardware.org/?probe=b15b96ee62) | Apr 23, 2024 |
| AMI           | Intel                       | Desktop     | [7f5a03f6a3](https://linux-hardware.org/?probe=7f5a03f6a3) | Apr 23, 2024 |
| Unknown       | Unknown                     | Desktop     | [2be166cff9](https://linux-hardware.org/?probe=2be166cff9) | Apr 22, 2024 |
| Unknown       | Unknown                     | Desktop     | [9bce7f48fb](https://linux-hardware.org/?probe=9bce7f48fb) | Apr 22, 2024 |
| Packard Be... | EasyNote_MX45               | Notebook    | [2af5864c3c](https://linux-hardware.org/?probe=2af5864c3c) | Apr 22, 2024 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [46d23f3585](https://linux-hardware.org/?probe=46d23f3585) | Apr 21, 2024 |
| HP            | 1495                        | Desktop     | [0eb85fb716](https://linux-hardware.org/?probe=0eb85fb716) | Apr 20, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [4aabe77962](https://linux-hardware.org/?probe=4aabe77962) | Apr 20, 2024 |
| HP            | 1495                        | Desktop     | [f3b383fe91](https://linux-hardware.org/?probe=f3b383fe91) | Apr 20, 2024 |
| Acer          | Aspire E1-571G              | Notebook    | [cfb1f06070](https://linux-hardware.org/?probe=cfb1f06070) | Apr 20, 2024 |
| ASUSTek       | T101HA                      | Tablet      | [703372f7ac](https://linux-hardware.org/?probe=703372f7ac) | Apr 19, 2024 |
| Medion        | E6214                       | Notebook    | [fef41424b0](https://linux-hardware.org/?probe=fef41424b0) | Apr 19, 2024 |
| Lenovo        | ThinkPad X140e 20BLS0040... | Notebook    | [028ee7ca9d](https://linux-hardware.org/?probe=028ee7ca9d) | Apr 19, 2024 |
| Medion        | E6214                       | Notebook    | [f6e648f8a4](https://linux-hardware.org/?probe=f6e648f8a4) | Apr 19, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [7cfe6d651b](https://linux-hardware.org/?probe=7cfe6d651b) | Apr 18, 2024 |
| Medion        | TJ4125                      | Desktop     | [283e08c36b](https://linux-hardware.org/?probe=283e08c36b) | Apr 18, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [0bf4de97cf](https://linux-hardware.org/?probe=0bf4de97cf) | Apr 17, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [39e93654ec](https://linux-hardware.org/?probe=39e93654ec) | Apr 13, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [562a3aa8fe](https://linux-hardware.org/?probe=562a3aa8fe) | Apr 13, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [a996f7b2e9](https://linux-hardware.org/?probe=a996f7b2e9) | Apr 12, 2024 |
| GMKtec        | M5 Pro                      | Mini pc     | [1545f1ad9f](https://linux-hardware.org/?probe=1545f1ad9f) | Apr 11, 2024 |
| ASUSTek       | PN53-G                      | Mini pc     | [d3be5bf008](https://linux-hardware.org/?probe=d3be5bf008) | Apr 10, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [cbc8162b5a](https://linux-hardware.org/?probe=cbc8162b5a) | Apr 10, 2024 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [3d748511c8](https://linux-hardware.org/?probe=3d748511c8) | Apr 08, 2024 |
| ASUSTek       | G752VSK                     | Notebook    | [49116bb834](https://linux-hardware.org/?probe=49116bb834) | Apr 08, 2024 |
| Dell          | Latitude E7250              | Notebook    | [3979d6a4a1](https://linux-hardware.org/?probe=3979d6a4a1) | Apr 07, 2024 |
| PELADN        | WI-6                        | Desktop     | [16b9fe150d](https://linux-hardware.org/?probe=16b9fe150d) | Apr 07, 2024 |
| Google        | Voxel                       | Notebook    | [5242e65363](https://linux-hardware.org/?probe=5242e65363) | Apr 06, 2024 |
| Medion        | E6214                       | Notebook    | [5ddeb441b9](https://linux-hardware.org/?probe=5ddeb441b9) | Apr 06, 2024 |
| Medion        | E6214                       | Notebook    | [20d0838443](https://linux-hardware.org/?probe=20d0838443) | Apr 06, 2024 |
| PELADN        | WI-6                        | Desktop     | [e3e158c12c](https://linux-hardware.org/?probe=e3e158c12c) | Apr 05, 2024 |
| Medion        | TJ4125                      | Desktop     | [9d159ef9de](https://linux-hardware.org/?probe=9d159ef9de) | Apr 04, 2024 |
| Medion        | TJ4125                      | Desktop     | [3133554055](https://linux-hardware.org/?probe=3133554055) | Apr 04, 2024 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [e075d81601](https://linux-hardware.org/?probe=e075d81601) | Apr 04, 2024 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [43a27413f2](https://linux-hardware.org/?probe=43a27413f2) | Mar 31, 2024 |
| AZW           | SER V2.0                    | Mini pc     | [1dd2fa7d48](https://linux-hardware.org/?probe=1dd2fa7d48) | Mar 31, 2024 |
| HP            | Pavilion 15                 | Notebook    | [69bc35a5b1](https://linux-hardware.org/?probe=69bc35a5b1) | Mar 30, 2024 |
| HP            | Pavilion 15                 | Notebook    | [69293f7635](https://linux-hardware.org/?probe=69293f7635) | Mar 30, 2024 |
| Quanta        | 2AC7 011                    | Desktop     | [ee7988e621](https://linux-hardware.org/?probe=ee7988e621) | Mar 29, 2024 |
| Lenovo        | V15 G4 IAH 83FS             | Notebook    | [ec668db660](https://linux-hardware.org/?probe=ec668db660) | Mar 28, 2024 |
| ASRock        | J3455-ITX                   | Desktop     | [a0f0f8fc52](https://linux-hardware.org/?probe=a0f0f8fc52) | Mar 26, 2024 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [14cbf1cf7d](https://linux-hardware.org/?probe=14cbf1cf7d) | Mar 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [0cee79fd45](https://linux-hardware.org/?probe=0cee79fd45) | Mar 24, 2024 |
| PELADN        | WI-6                        | Desktop     | [76b4088a9e](https://linux-hardware.org/?probe=76b4088a9e) | Mar 23, 2024 |
| Lenovo        | 500w Gen 3 82J3             | Convertible | [e88e880d21](https://linux-hardware.org/?probe=e88e880d21) | Mar 23, 2024 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [153847bfc0](https://linux-hardware.org/?probe=153847bfc0) | Mar 23, 2024 |
| Lenovo        | 500w Gen 3 82J3             | Convertible | [c5e27f31fa](https://linux-hardware.org/?probe=c5e27f31fa) | Mar 23, 2024 |
| HP            | ProBook 470 G0              | Notebook    | [7947b2c132](https://linux-hardware.org/?probe=7947b2c132) | Mar 22, 2024 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [07889f98fc](https://linux-hardware.org/?probe=07889f98fc) | Mar 22, 2024 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | Desktop     | [dfa8ff45b7](https://linux-hardware.org/?probe=dfa8ff45b7) | Mar 21, 2024 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | Desktop     | [5c0de1313b](https://linux-hardware.org/?probe=5c0de1313b) | Mar 21, 2024 |
| Lenovo        | IdeaPad Pro 5 16IRH8 83A... | Notebook    | [a4c78f511d](https://linux-hardware.org/?probe=a4c78f511d) | Mar 21, 2024 |
| Apple         | MacBookAir4,2               | Notebook    | [3d42d3e1f9](https://linux-hardware.org/?probe=3d42d3e1f9) | Mar 19, 2024 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [230ed44a0f](https://linux-hardware.org/?probe=230ed44a0f) | Mar 18, 2024 |
| Dell          | Inspiron 3585               | Notebook    | [2378788f88](https://linux-hardware.org/?probe=2378788f88) | Mar 18, 2024 |
| Lenovo        | IdeaPad U160 08946JG        | Notebook    | [62adedc3dc](https://linux-hardware.org/?probe=62adedc3dc) | Mar 17, 2024 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [d1f4d3e711](https://linux-hardware.org/?probe=d1f4d3e711) | Mar 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [25c1a0e7d3](https://linux-hardware.org/?probe=25c1a0e7d3) | Mar 16, 2024 |
| ASUSTek       | T103HAF                     | Tablet      | [cae2c37148](https://linux-hardware.org/?probe=cae2c37148) | Mar 14, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [e5bf526b80](https://linux-hardware.org/?probe=e5bf526b80) | Mar 13, 2024 |
| Lenovo        | IdeaPad U160 08946JG        | Notebook    | [0d6bea90e0](https://linux-hardware.org/?probe=0d6bea90e0) | Mar 11, 2024 |
| Unknown       | G31T-M7                     | Desktop     | [1bf4ded8e3](https://linux-hardware.org/?probe=1bf4ded8e3) | Mar 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1dda71290f](https://linux-hardware.org/?probe=1dda71290f) | Mar 08, 2024 |
| ASUSTek       | M3702WFA                    | All in one  | [9d1db96cef](https://linux-hardware.org/?probe=9d1db96cef) | Mar 07, 2024 |
| Monster       | TULPAR T7 V20.3             | Notebook    | [df8b4e385a](https://linux-hardware.org/?probe=df8b4e385a) | Mar 06, 2024 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [b4f3b9c879](https://linux-hardware.org/?probe=b4f3b9c879) | Mar 06, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [5f7a226ed8](https://linux-hardware.org/?probe=5f7a226ed8) | Mar 06, 2024 |
| Acer          | Aspire 5570Z                | Notebook    | [16e46c8657](https://linux-hardware.org/?probe=16e46c8657) | Mar 05, 2024 |
| Acer          | Aspire 5570Z                | Notebook    | [4471c4987a](https://linux-hardware.org/?probe=4471c4987a) | Mar 05, 2024 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [fc21a2b0e2](https://linux-hardware.org/?probe=fc21a2b0e2) | Mar 04, 2024 |
| ASUSTek       | T101HA                      | Tablet      | [08453be623](https://linux-hardware.org/?probe=08453be623) | Feb 28, 2024 |
| ASUSTek       | T101HA                      | Tablet      | [8bb6693e8a](https://linux-hardware.org/?probe=8bb6693e8a) | Feb 28, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [d67a754532](https://linux-hardware.org/?probe=d67a754532) | Feb 27, 2024 |
| Lenovo        | ThinkPad T480 20L6S2CB00    | Notebook    | [eff836bcb1](https://linux-hardware.org/?probe=eff836bcb1) | Feb 27, 2024 |
| Lenovo        | ThinkPad T480 20L6S2CB00    | Notebook    | [a78eb227db](https://linux-hardware.org/?probe=a78eb227db) | Feb 26, 2024 |
| Dell          | Vostro 1510                 | Notebook    | [c2b1496073](https://linux-hardware.org/?probe=c2b1496073) | Feb 24, 2024 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [9f6a95d5b4](https://linux-hardware.org/?probe=9f6a95d5b4) | Feb 23, 2024 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [dad4fdcceb](https://linux-hardware.org/?probe=dad4fdcceb) | Feb 22, 2024 |
| ASUSTek       | ZenBook UX434FL_UX434FL     | Notebook    | [309bc99f27](https://linux-hardware.org/?probe=309bc99f27) | Feb 22, 2024 |
| Apple         | MacBookPro5,1               | Notebook    | [6bbe163c4b](https://linux-hardware.org/?probe=6bbe163c4b) | Feb 21, 2024 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [954a5c5822](https://linux-hardware.org/?probe=954a5c5822) | Feb 20, 2024 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [54eb218a18](https://linux-hardware.org/?probe=54eb218a18) | Feb 20, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [383bb58584](https://linux-hardware.org/?probe=383bb58584) | Feb 20, 2024 |
| Lenovo        | ThinkPad E470 20H2S00500    | Notebook    | [3c24c9be66](https://linux-hardware.org/?probe=3c24c9be66) | Feb 20, 2024 |
| MSI           | Z370-A PRO                  | Desktop     | [3715fac015](https://linux-hardware.org/?probe=3715fac015) | Feb 20, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [29958a239f](https://linux-hardware.org/?probe=29958a239f) | Feb 19, 2024 |
| MSI           | Z170A SLI PLUS              | Desktop     | [5dff40d28c](https://linux-hardware.org/?probe=5dff40d28c) | Feb 19, 2024 |
| ASRock        | B760M Pro RS/D4             | Desktop     | [f0f36877ea](https://linux-hardware.org/?probe=f0f36877ea) | Feb 19, 2024 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [5cc2223e2a](https://linux-hardware.org/?probe=5cc2223e2a) | Feb 18, 2024 |
| Dell          | XPS 13 9310                 | Notebook    | [0867cf376f](https://linux-hardware.org/?probe=0867cf376f) | Feb 18, 2024 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [741292eb40](https://linux-hardware.org/?probe=741292eb40) | Feb 18, 2024 |
| HP            | Pavilion 15                 | Notebook    | [55af31fd66](https://linux-hardware.org/?probe=55af31fd66) | Feb 17, 2024 |
| Gigabyte      | B560M D3H                   | Desktop     | [dd40636963](https://linux-hardware.org/?probe=dd40636963) | Feb 17, 2024 |
| HP            | Pavilion 15                 | Notebook    | [7dbe71cc73](https://linux-hardware.org/?probe=7dbe71cc73) | Feb 17, 2024 |
| ASUSTek       | BU201LA                     | Notebook    | [7d7e9ee7df](https://linux-hardware.org/?probe=7d7e9ee7df) | Feb 14, 2024 |
| ASUSTek       | BU201LA                     | Notebook    | [420cd60b3b](https://linux-hardware.org/?probe=420cd60b3b) | Feb 14, 2024 |
| Acer          | Aspire A315-44P             | Notebook    | [ffb90b8b62](https://linux-hardware.org/?probe=ffb90b8b62) | Feb 13, 2024 |
| ASUSTek       | K52JU                       | Notebook    | [d9ff2db026](https://linux-hardware.org/?probe=d9ff2db026) | Feb 13, 2024 |
| ASUSTek       | K52JU                       | Notebook    | [15af146ca8](https://linux-hardware.org/?probe=15af146ca8) | Feb 13, 2024 |
| Inventec      | VXC Class A02               | Desktop     | [f5467a7fcc](https://linux-hardware.org/?probe=f5467a7fcc) | Feb 12, 2024 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [042003f9b0](https://linux-hardware.org/?probe=042003f9b0) | Feb 12, 2024 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [b342dc33d2](https://linux-hardware.org/?probe=b342dc33d2) | Feb 11, 2024 |
| Toshiba       | Satellite A135              | Notebook    | [42cf20d3d4](https://linux-hardware.org/?probe=42cf20d3d4) | Feb 11, 2024 |
| Inventec      | VXC Class A02               | Desktop     | [cd813cc599](https://linux-hardware.org/?probe=cd813cc599) | Feb 10, 2024 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [5488b51445](https://linux-hardware.org/?probe=5488b51445) | Feb 10, 2024 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [f810a582b9](https://linux-hardware.org/?probe=f810a582b9) | Feb 07, 2024 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [5b65435343](https://linux-hardware.org/?probe=5b65435343) | Feb 06, 2024 |
| Toshiba       | Satellite Pro C850-1DQ      | Notebook    | [ecd1214308](https://linux-hardware.org/?probe=ecd1214308) | Feb 06, 2024 |
| Toshiba       | Satellite Pro C850-1DQ      | Notebook    | [af5799035c](https://linux-hardware.org/?probe=af5799035c) | Feb 06, 2024 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [df7b813324](https://linux-hardware.org/?probe=df7b813324) | Feb 05, 2024 |
| Fujitsu Si... | AMILO Li3910                | Notebook    | [ecde56e2bb](https://linux-hardware.org/?probe=ecde56e2bb) | Feb 04, 2024 |
| Intel         | B75                         | Desktop     | [23e52718b5](https://linux-hardware.org/?probe=23e52718b5) | Feb 03, 2024 |
| HP            | 212B                        | Desktop     | [ada937137f](https://linux-hardware.org/?probe=ada937137f) | Feb 03, 2024 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [32b5d46627](https://linux-hardware.org/?probe=32b5d46627) | Feb 02, 2024 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [4c5e48c75f](https://linux-hardware.org/?probe=4c5e48c75f) | Feb 02, 2024 |
| Inventec      | DQ Class A02                | Desktop     | [4cb447dae2](https://linux-hardware.org/?probe=4cb447dae2) | Feb 02, 2024 |
| MSI           | Thin GF63 12HW              | Notebook    | [b5b16477c3](https://linux-hardware.org/?probe=b5b16477c3) | Feb 02, 2024 |
| Dell          | Latitude 7280               | Notebook    | [c94b45b8f4](https://linux-hardware.org/?probe=c94b45b8f4) | Feb 02, 2024 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [78ef1fbd6c](https://linux-hardware.org/?probe=78ef1fbd6c) | Jan 31, 2024 |
| Medion        | TJ4125                      | Desktop     | [2705de4986](https://linux-hardware.org/?probe=2705de4986) | Jan 31, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [78a08c286e](https://linux-hardware.org/?probe=78a08c286e) | Jan 30, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [a23343d32d](https://linux-hardware.org/?probe=a23343d32d) | Jan 30, 2024 |
| MSI           | MS-7345                     | Desktop     | [3453f85c21](https://linux-hardware.org/?probe=3453f85c21) | Jan 30, 2024 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [429541ce17](https://linux-hardware.org/?probe=429541ce17) | Jan 29, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [c7a52fe756](https://linux-hardware.org/?probe=c7a52fe756) | Jan 29, 2024 |
| HP            | 805D                        | Desktop     | [81113f9b0d](https://linux-hardware.org/?probe=81113f9b0d) | Jan 29, 2024 |
| Fanless Mi... | Rev JSL62                   | Mini pc     | [f0e620b88a](https://linux-hardware.org/?probe=f0e620b88a) | Jan 29, 2024 |
| Medion        | P7612                       | Notebook    | [875d083de0](https://linux-hardware.org/?probe=875d083de0) | Jan 29, 2024 |
| HP            | Compaq 615                  | Notebook    | [907b046dda](https://linux-hardware.org/?probe=907b046dda) | Jan 29, 2024 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [79381fe2e8](https://linux-hardware.org/?probe=79381fe2e8) | Jan 29, 2024 |
| Lenovo        | ThinkPad X230 2325SU3       | Notebook    | [664fffd47e](https://linux-hardware.org/?probe=664fffd47e) | Jan 29, 2024 |
| Lenovo        | ThinkPad X230 2325SU3       | Notebook    | [cc42f2d5e4](https://linux-hardware.org/?probe=cc42f2d5e4) | Jan 29, 2024 |
| ASUSTek       | PRIME X670-P                | Desktop     | [08b5799cfd](https://linux-hardware.org/?probe=08b5799cfd) | Jan 27, 2024 |
| Acer          | Aspire E5-575               | Notebook    | [6764984d72](https://linux-hardware.org/?probe=6764984d72) | Jan 26, 2024 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [30954e841f](https://linux-hardware.org/?probe=30954e841f) | Jan 26, 2024 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [56bd222ae5](https://linux-hardware.org/?probe=56bd222ae5) | Jan 24, 2024 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [7cd83ff81e](https://linux-hardware.org/?probe=7cd83ff81e) | Jan 23, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [ed52617ade](https://linux-hardware.org/?probe=ed52617ade) | Jan 23, 2024 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [b8a8ce8fc0](https://linux-hardware.org/?probe=b8a8ce8fc0) | Jan 23, 2024 |
| Dell          | Latitude D610               | Notebook    | [b1f24babef](https://linux-hardware.org/?probe=b1f24babef) | Jan 22, 2024 |
| ASRock        | Z690 Pro RS                 | Desktop     | [4083a31da9](https://linux-hardware.org/?probe=4083a31da9) | Jan 21, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [61f93014cf](https://linux-hardware.org/?probe=61f93014cf) | Jan 21, 2024 |
| ASRock        | X670E Taichi Carrara        | Desktop     | [52318f5ae6](https://linux-hardware.org/?probe=52318f5ae6) | Jan 20, 2024 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [b2d419f7dc](https://linux-hardware.org/?probe=b2d419f7dc) | Jan 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [d40c2f48dd](https://linux-hardware.org/?probe=d40c2f48dd) | Jan 18, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [323c35348f](https://linux-hardware.org/?probe=323c35348f) | Jan 16, 2024 |
| ASUSTek       | P7P55D-E                    | Desktop     | [bb8785aa08](https://linux-hardware.org/?probe=bb8785aa08) | Jan 15, 2024 |
| Lenovo        | ThinkPad X61 76754BJ        | Notebook    | [42f1380b4e](https://linux-hardware.org/?probe=42f1380b4e) | Jan 15, 2024 |
| MSI           | MEG X670E ACE               | Desktop     | [08ee758712](https://linux-hardware.org/?probe=08ee758712) | Jan 15, 2024 |
| ASRock        | Z97 Pro4                    | Desktop     | [e3ef5ae05b](https://linux-hardware.org/?probe=e3ef5ae05b) | Jan 14, 2024 |
| Lenovo        | ThinkPad T400 6474EU3       | Notebook    | [0d9d328c8d](https://linux-hardware.org/?probe=0d9d328c8d) | Jan 14, 2024 |
| Dell          | Inspiron 15-3552            | Notebook    | [2a9bde666e](https://linux-hardware.org/?probe=2a9bde666e) | Jan 13, 2024 |
| Dell          | Inspiron 15-3552            | Notebook    | [87e8f38d79](https://linux-hardware.org/?probe=87e8f38d79) | Jan 13, 2024 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [516c8f6f9c](https://linux-hardware.org/?probe=516c8f6f9c) | Jan 13, 2024 |
| Gigabyte      | GA-78LMT-S2P 78LMT2         | Desktop     | [b81e3342c6](https://linux-hardware.org/?probe=b81e3342c6) | Jan 13, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [70dedc5c9d](https://linux-hardware.org/?probe=70dedc5c9d) | Jan 12, 2024 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [a358114f21](https://linux-hardware.org/?probe=a358114f21) | Jan 12, 2024 |
| Lenovo        | ThinkPad X1 Carbon 34601... | Notebook    | [bdfab62447](https://linux-hardware.org/?probe=bdfab62447) | Jan 12, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [6b5cc546b5](https://linux-hardware.org/?probe=6b5cc546b5) | Jan 12, 2024 |
| MSI           | Z390-A PRO                  | Desktop     | [538119eb86](https://linux-hardware.org/?probe=538119eb86) | Jan 11, 2024 |
| MSI           | B350M BAZOOKA               | Desktop     | [fab33560f3](https://linux-hardware.org/?probe=fab33560f3) | Jan 10, 2024 |
| VALE          | Notebook Classic C171V      | Notebook    | [8ecf376e28](https://linux-hardware.org/?probe=8ecf376e28) | Jan 10, 2024 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | Desktop     | [c9096376d8](https://linux-hardware.org/?probe=c9096376d8) | Jan 09, 2024 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [702eef24cf](https://linux-hardware.org/?probe=702eef24cf) | Jan 09, 2024 |
| Lenovo        | IdeaPad Y530                | Notebook    | [344509ac97](https://linux-hardware.org/?probe=344509ac97) | Jan 08, 2024 |
| Notebook      | W35xSTQ_370ST               | Notebook    | [a2f670a8f0](https://linux-hardware.org/?probe=a2f670a8f0) | Jan 08, 2024 |
| Dell          | Latitude E6320              | Notebook    | [75e562d28a](https://linux-hardware.org/?probe=75e562d28a) | Jan 07, 2024 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [2c36dcaa22](https://linux-hardware.org/?probe=2c36dcaa22) | Jan 07, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [e2e58f59b7](https://linux-hardware.org/?probe=e2e58f59b7) | Jan 06, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ff9686f03c](https://linux-hardware.org/?probe=ff9686f03c) | Jan 06, 2024 |
| Google        | Swanky                      | Notebook    | [1b6173f1e0](https://linux-hardware.org/?probe=1b6173f1e0) | Jan 05, 2024 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [de8842c748](https://linux-hardware.org/?probe=de8842c748) | Jan 04, 2024 |
| Apple         | MacBookAir7,1               | Notebook    | [5596e9e3a7](https://linux-hardware.org/?probe=5596e9e3a7) | Jan 04, 2024 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [a04f45ddfb](https://linux-hardware.org/?probe=a04f45ddfb) | Jan 03, 2024 |
| Dell          | Latitude E6320              | Notebook    | [e6fec1134a](https://linux-hardware.org/?probe=e6fec1134a) | Jan 03, 2024 |
| Medion        | TJ4125                      | Desktop     | [ca0e4105c2](https://linux-hardware.org/?probe=ca0e4105c2) | Jan 02, 2024 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [26f77fa950](https://linux-hardware.org/?probe=26f77fa950) | Jan 02, 2024 |
| Dell          | Latitude E6320              | Notebook    | [1833dcdd43](https://linux-hardware.org/?probe=1833dcdd43) | Dec 31, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [9e622b4006](https://linux-hardware.org/?probe=9e622b4006) | Dec 31, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [0f440edfb5](https://linux-hardware.org/?probe=0f440edfb5) | Dec 31, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [edbe61f4fa](https://linux-hardware.org/?probe=edbe61f4fa) | Dec 31, 2023 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [fc3a637b52](https://linux-hardware.org/?probe=fc3a637b52) | Dec 31, 2023 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [86a499d322](https://linux-hardware.org/?probe=86a499d322) | Dec 30, 2023 |
| Sony          | VGN-FW21E                   | Notebook    | [52ff803e03](https://linux-hardware.org/?probe=52ff803e03) | Dec 29, 2023 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [c2a3ce3927](https://linux-hardware.org/?probe=c2a3ce3927) | Dec 29, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [05e0faf913](https://linux-hardware.org/?probe=05e0faf913) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [242659bbee](https://linux-hardware.org/?probe=242659bbee) | Dec 27, 2023 |
| Dell          | 0RW199                      | Desktop     | [906719d239](https://linux-hardware.org/?probe=906719d239) | Dec 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [3673afc1cd](https://linux-hardware.org/?probe=3673afc1cd) | Dec 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [9b570f14f6](https://linux-hardware.org/?probe=9b570f14f6) | Dec 26, 2023 |
| HP            | ProBook 445 14 inch G9 N... | Notebook    | [d3e1c0dbdc](https://linux-hardware.org/?probe=d3e1c0dbdc) | Dec 25, 2023 |
| HP            | 090Ch                       | Desktop     | [06e9f893bc](https://linux-hardware.org/?probe=06e9f893bc) | Dec 25, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [4b2ed8b976](https://linux-hardware.org/?probe=4b2ed8b976) | Dec 23, 2023 |
| ASUSTek       | X99-A II                    | Desktop     | [37e4430c0e](https://linux-hardware.org/?probe=37e4430c0e) | Dec 23, 2023 |
| ASRock        | Z97 Pro4                    | Desktop     | [f8e2df67b1](https://linux-hardware.org/?probe=f8e2df67b1) | Dec 23, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [db8c00daf3](https://linux-hardware.org/?probe=db8c00daf3) | Dec 22, 2023 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [942da4e853](https://linux-hardware.org/?probe=942da4e853) | Dec 20, 2023 |
| Lenovo        | 317C NOK                    | Desktop     | [87064e6d98](https://linux-hardware.org/?probe=87064e6d98) | Dec 20, 2023 |
| Medion        | TJ4125                      | Desktop     | [8fce958467](https://linux-hardware.org/?probe=8fce958467) | Dec 20, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [a1f4076586](https://linux-hardware.org/?probe=a1f4076586) | Dec 19, 2023 |
| Sony          | SVE1511A1EW                 | Notebook    | [2f0fde3487](https://linux-hardware.org/?probe=2f0fde3487) | Dec 19, 2023 |
| Sony          | SVE1511A1EW                 | Notebook    | [e5531ecc00](https://linux-hardware.org/?probe=e5531ecc00) | Dec 19, 2023 |
| Medion        | TJ4125                      | Desktop     | [c7eeb77279](https://linux-hardware.org/?probe=c7eeb77279) | Dec 18, 2023 |
| Irbis         | NB264                       | Notebook    | [8c32d8fb0b](https://linux-hardware.org/?probe=8c32d8fb0b) | Dec 18, 2023 |
| Medion        | E6214                       | Notebook    | [1bc5839854](https://linux-hardware.org/?probe=1bc5839854) | Dec 17, 2023 |
| Medion        | E6214                       | Notebook    | [5269b6e576](https://linux-hardware.org/?probe=5269b6e576) | Dec 17, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [378b82ce2f](https://linux-hardware.org/?probe=378b82ce2f) | Dec 17, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [e7f9b37ee3](https://linux-hardware.org/?probe=e7f9b37ee3) | Dec 17, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [935f688c90](https://linux-hardware.org/?probe=935f688c90) | Dec 17, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [f53d129b3d](https://linux-hardware.org/?probe=f53d129b3d) | Dec 17, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [6b3cd841db](https://linux-hardware.org/?probe=6b3cd841db) | Dec 17, 2023 |
| Medion        | TJ4125                      | Desktop     | [7556d73046](https://linux-hardware.org/?probe=7556d73046) | Dec 17, 2023 |
| Dell          | Latitude E6430              | Notebook    | [13af5c2dc4](https://linux-hardware.org/?probe=13af5c2dc4) | Dec 17, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [0b4a9d3a4e](https://linux-hardware.org/?probe=0b4a9d3a4e) | Dec 16, 2023 |
| Lenovo        | ThinkPad X230 2325BA3       | Notebook    | [1c573f00c0](https://linux-hardware.org/?probe=1c573f00c0) | Dec 16, 2023 |
| Medion        | E6214                       | Notebook    | [806be57bd5](https://linux-hardware.org/?probe=806be57bd5) | Dec 16, 2023 |
| Apple         | Mac-F4208EAA PVT            | Mini pc     | [973e09e6eb](https://linux-hardware.org/?probe=973e09e6eb) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [8f7755936c](https://linux-hardware.org/?probe=8f7755936c) | Dec 14, 2023 |
| Acer          | Veriton M4630G V:1.0        | Desktop     | [91ec51ebf5](https://linux-hardware.org/?probe=91ec51ebf5) | Dec 12, 2023 |
| Lenovo        | 30BB SDK0J40709 WIN 3259... | All in one  | [9d9d96201b](https://linux-hardware.org/?probe=9d9d96201b) | Dec 12, 2023 |
| Acer          | Aspire Z3-615               | All in one  | [e71cda8b04](https://linux-hardware.org/?probe=e71cda8b04) | Dec 12, 2023 |
| Acer          | Aspire Z3-615               | All in one  | [c3d3cc14e8](https://linux-hardware.org/?probe=c3d3cc14e8) | Dec 12, 2023 |
| Dell          | 0GXM1W A02                  | Desktop     | [3184d3c38b](https://linux-hardware.org/?probe=3184d3c38b) | Dec 11, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [78562df77d](https://linux-hardware.org/?probe=78562df77d) | Dec 11, 2023 |
| ASRock        | H310M-STX                   | Desktop     | [205a5c1696](https://linux-hardware.org/?probe=205a5c1696) | Dec 10, 2023 |
| Dell          | Precision 3550              | Notebook    | [0235a02831](https://linux-hardware.org/?probe=0235a02831) | Dec 10, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [71de71e3f4](https://linux-hardware.org/?probe=71de71e3f4) | Dec 10, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [64b0038221](https://linux-hardware.org/?probe=64b0038221) | Dec 10, 2023 |
| ASUSTek       | X505BP                      | Notebook    | [408ad7dd06](https://linux-hardware.org/?probe=408ad7dd06) | Dec 10, 2023 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [eaedc51abc](https://linux-hardware.org/?probe=eaedc51abc) | Dec 10, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [0d970bde9a](https://linux-hardware.org/?probe=0d970bde9a) | Dec 09, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [4525b7e30c](https://linux-hardware.org/?probe=4525b7e30c) | Dec 09, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [42a7acfe4b](https://linux-hardware.org/?probe=42a7acfe4b) | Dec 09, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b553ec2266](https://linux-hardware.org/?probe=b553ec2266) | Dec 08, 2023 |
| ASUSTek       | Rampage III Extreme         | Desktop     | [d4d934c9be](https://linux-hardware.org/?probe=d4d934c9be) | Dec 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [7144bda606](https://linux-hardware.org/?probe=7144bda606) | Dec 07, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [748534900a](https://linux-hardware.org/?probe=748534900a) | Dec 04, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [6fca6c7335](https://linux-hardware.org/?probe=6fca6c7335) | Dec 03, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [e6fd8cf7f1](https://linux-hardware.org/?probe=e6fd8cf7f1) | Dec 02, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [e33632af4f](https://linux-hardware.org/?probe=e33632af4f) | Dec 02, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [f86dd8a709](https://linux-hardware.org/?probe=f86dd8a709) | Dec 02, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [b53f576b27](https://linux-hardware.org/?probe=b53f576b27) | Dec 02, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [75dcedad41](https://linux-hardware.org/?probe=75dcedad41) | Nov 30, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [8a91691d0b](https://linux-hardware.org/?probe=8a91691d0b) | Nov 30, 2023 |
| Alienware     | 17                          | Notebook    | [1c23fa6051](https://linux-hardware.org/?probe=1c23fa6051) | Nov 29, 2023 |
| LETSUNG       | Unknown                     | Notebook    | [bfbf7dfeaa](https://linux-hardware.org/?probe=bfbf7dfeaa) | Nov 27, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [9fa48c41da](https://linux-hardware.org/?probe=9fa48c41da) | Nov 27, 2023 |
| Lenovo        | ThinkPad W541 20EGS07C01    | Notebook    | [c05294f5f5](https://linux-hardware.org/?probe=c05294f5f5) | Nov 26, 2023 |
| Gigabyte      | B560M D3H                   | Desktop     | [8a894da286](https://linux-hardware.org/?probe=8a894da286) | Nov 26, 2023 |
| Lenovo        | ThinkPad W541 20EGS07C01    | Notebook    | [dc051898f5](https://linux-hardware.org/?probe=dc051898f5) | Nov 26, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [1a31182007](https://linux-hardware.org/?probe=1a31182007) | Nov 26, 2023 |
| Medion        | E6214                       | Notebook    | [83d5d32938](https://linux-hardware.org/?probe=83d5d32938) | Nov 26, 2023 |
| Shenzhen M... | F7BRC                       | Desktop     | [9ff2c76737](https://linux-hardware.org/?probe=9ff2c76737) | Nov 26, 2023 |
| HP            | Pavilion TS Sleekbook 15    | Notebook    | [3a3a75aa94](https://linux-hardware.org/?probe=3a3a75aa94) | Nov 26, 2023 |
| MSI           | MAG B760M MORTAR WIFI DD... | Desktop     | [b11fcf42c2](https://linux-hardware.org/?probe=b11fcf42c2) | Nov 25, 2023 |
| HP            | Pavilion TS Sleekbook 15    | Notebook    | [9c76ca1014](https://linux-hardware.org/?probe=9c76ca1014) | Nov 25, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7fce567d9e](https://linux-hardware.org/?probe=7fce567d9e) | Nov 25, 2023 |
| HP            | 245 G7                      | Notebook    | [42ee8e6975](https://linux-hardware.org/?probe=42ee8e6975) | Nov 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [8131bff614](https://linux-hardware.org/?probe=8131bff614) | Nov 25, 2023 |
| Medion        | TJ4125                      | Desktop     | [512206df27](https://linux-hardware.org/?probe=512206df27) | Nov 24, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [81d1db42ea](https://linux-hardware.org/?probe=81d1db42ea) | Nov 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a8b99ab7f3](https://linux-hardware.org/?probe=a8b99ab7f3) | Nov 23, 2023 |
| HP            | 829A                        | Mini pc     | [b8edb25d4c](https://linux-hardware.org/?probe=b8edb25d4c) | Nov 23, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [af55920808](https://linux-hardware.org/?probe=af55920808) | Nov 23, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [b564a39ed5](https://linux-hardware.org/?probe=b564a39ed5) | Nov 22, 2023 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [ce96501574](https://linux-hardware.org/?probe=ce96501574) | Nov 22, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [a0f12099c5](https://linux-hardware.org/?probe=a0f12099c5) | Nov 22, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | Notebook    | [9f4829b792](https://linux-hardware.org/?probe=9f4829b792) | Nov 22, 2023 |
| HP            | 8158 A01                    | Mini pc     | [5132b64a8a](https://linux-hardware.org/?probe=5132b64a8a) | Nov 22, 2023 |
| Soyo          | SY-N3150L Quad              | Desktop     | [7fd72fcced](https://linux-hardware.org/?probe=7fd72fcced) | Nov 21, 2023 |
| HP            | Pavilion 15                 | Notebook    | [b12a3ea8d6](https://linux-hardware.org/?probe=b12a3ea8d6) | Nov 21, 2023 |
| HP            | Pavilion 15                 | Notebook    | [7239efa8fe](https://linux-hardware.org/?probe=7239efa8fe) | Nov 20, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [085623428e](https://linux-hardware.org/?probe=085623428e) | Nov 19, 2023 |
| Acer          | Aspire X3400                | Desktop     | [26cedbdbde](https://linux-hardware.org/?probe=26cedbdbde) | Nov 19, 2023 |
| Acer          | Aspire X3400                | Desktop     | [83890ec21c](https://linux-hardware.org/?probe=83890ec21c) | Nov 19, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [e65cf40bcb](https://linux-hardware.org/?probe=e65cf40bcb) | Nov 19, 2023 |
| Intel         | NUC7i5DNB J57626-509        | Mini pc     | [672ed26145](https://linux-hardware.org/?probe=672ed26145) | Nov 17, 2023 |
| ASUSTek       | EB1035                      | All in one  | [c42d11074a](https://linux-hardware.org/?probe=c42d11074a) | Nov 17, 2023 |
| ASUSTek       | EB1035                      | All in one  | [04b01b0be5](https://linux-hardware.org/?probe=04b01b0be5) | Nov 17, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [f6d6d655df](https://linux-hardware.org/?probe=f6d6d655df) | Nov 16, 2023 |
| HP            | 8265                        | Desktop     | [d3f5c1d6ce](https://linux-hardware.org/?probe=d3f5c1d6ce) | Nov 15, 2023 |
| Toshiba       | Satellite Pro L100          | Notebook    | [429902b4e5](https://linux-hardware.org/?probe=429902b4e5) | Nov 15, 2023 |
| Acer          | AOA110                      | Notebook    | [a6b7a86c67](https://linux-hardware.org/?probe=a6b7a86c67) | Nov 14, 2023 |
| MSI           | Thin GF63 12HW              | Notebook    | [087220685a](https://linux-hardware.org/?probe=087220685a) | Nov 14, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | Desktop     | [c4b486ecb1](https://linux-hardware.org/?probe=c4b486ecb1) | Nov 13, 2023 |
| Toshiba       | Satellite Pro L100          | Notebook    | [ade0fd48dc](https://linux-hardware.org/?probe=ade0fd48dc) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [c00b5e7c16](https://linux-hardware.org/?probe=c00b5e7c16) | Nov 12, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [e45cab7f2c](https://linux-hardware.org/?probe=e45cab7f2c) | Nov 12, 2023 |
| Medion        | TJ4125                      | Desktop     | [1e0f7cdf34](https://linux-hardware.org/?probe=1e0f7cdf34) | Nov 12, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [feaa9f3eac](https://linux-hardware.org/?probe=feaa9f3eac) | Nov 11, 2023 |
| Medion        | TJ4125                      | Desktop     | [ab37177769](https://linux-hardware.org/?probe=ab37177769) | Nov 10, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [80bba409c5](https://linux-hardware.org/?probe=80bba409c5) | Nov 10, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [54073a3305](https://linux-hardware.org/?probe=54073a3305) | Nov 09, 2023 |
| Toshiba       | Satellite L745              | Notebook    | [4dbd78f68d](https://linux-hardware.org/?probe=4dbd78f68d) | Nov 09, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | Notebook    | [c594d3daae](https://linux-hardware.org/?probe=c594d3daae) | Nov 09, 2023 |
| IBM           | ThinkPad T40 23736G4        | Notebook    | [5c1d0bcbb2](https://linux-hardware.org/?probe=5c1d0bcbb2) | Nov 08, 2023 |
| Dell          | 0HH807                      | Desktop     | [300ee3d8f5](https://linux-hardware.org/?probe=300ee3d8f5) | Nov 08, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [8d5332d643](https://linux-hardware.org/?probe=8d5332d643) | Nov 07, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [f51da852ca](https://linux-hardware.org/?probe=f51da852ca) | Nov 07, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [35b7b043ff](https://linux-hardware.org/?probe=35b7b043ff) | Nov 07, 2023 |
| Google        | Akemi                       | Notebook    | [f19a7fb862](https://linux-hardware.org/?probe=f19a7fb862) | Nov 06, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | Notebook    | [d86018bbd8](https://linux-hardware.org/?probe=d86018bbd8) | Nov 06, 2023 |
| MSI           | B75MA-P45                   | Desktop     | [bfe1423965](https://linux-hardware.org/?probe=bfe1423965) | Nov 06, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [39e8a692ae](https://linux-hardware.org/?probe=39e8a692ae) | Nov 05, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [62a888f71c](https://linux-hardware.org/?probe=62a888f71c) | Nov 05, 2023 |
| Medion        | TJ4125                      | Desktop     | [65a059325e](https://linux-hardware.org/?probe=65a059325e) | Nov 05, 2023 |
| Gigabyte      | MZBSWAP-K4                  | Desktop     | [ef6c15830d](https://linux-hardware.org/?probe=ef6c15830d) | Nov 05, 2023 |
| Google        | Akemi                       | Notebook    | [350f53d84a](https://linux-hardware.org/?probe=350f53d84a) | Nov 05, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [b77c593ace](https://linux-hardware.org/?probe=b77c593ace) | Nov 04, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [1c80cbda1c](https://linux-hardware.org/?probe=1c80cbda1c) | Nov 04, 2023 |
| Medion        | E6214                       | Notebook    | [776be82bf6](https://linux-hardware.org/?probe=776be82bf6) | Nov 04, 2023 |
| HP            | 246 G6 Notebook PC          | Notebook    | [cd997e5a97](https://linux-hardware.org/?probe=cd997e5a97) | Nov 03, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [b73e7cf536](https://linux-hardware.org/?probe=b73e7cf536) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [a0c7507d6d](https://linux-hardware.org/?probe=a0c7507d6d) | Nov 03, 2023 |
| Google        | Akemi                       | Notebook    | [20ec65943c](https://linux-hardware.org/?probe=20ec65943c) | Nov 02, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [ae6c835796](https://linux-hardware.org/?probe=ae6c835796) | Nov 02, 2023 |
| ASUSTek       | X456UR                      | Notebook    | [9a0a4dfd02](https://linux-hardware.org/?probe=9a0a4dfd02) | Nov 02, 2023 |
| ASRock        | Z97 Pro4                    | Desktop     | [6fa2a70f99](https://linux-hardware.org/?probe=6fa2a70f99) | Nov 01, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [826dc000ff](https://linux-hardware.org/?probe=826dc000ff) | Nov 01, 2023 |
| HP            | Notebook                    | Notebook    | [b1491b73ae](https://linux-hardware.org/?probe=b1491b73ae) | Oct 31, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [1107919053](https://linux-hardware.org/?probe=1107919053) | Oct 31, 2023 |
| HP            | 18EB                        | Desktop     | [83596ab9d9](https://linux-hardware.org/?probe=83596ab9d9) | Oct 31, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [e741e073e0](https://linux-hardware.org/?probe=e741e073e0) | Oct 30, 2023 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [810297d46b](https://linux-hardware.org/?probe=810297d46b) | Oct 30, 2023 |
| Gigabyte      | MZBSWAP-K4                  | Desktop     | [aed94a16c1](https://linux-hardware.org/?probe=aed94a16c1) | Oct 30, 2023 |
| ASUSTek       | X540YA                      | Notebook    | [082e5b7e0b](https://linux-hardware.org/?probe=082e5b7e0b) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [1267d6df00](https://linux-hardware.org/?probe=1267d6df00) | Oct 29, 2023 |
| Trigkey       | Green G4 10                 | Desktop     | [bb72f6af02](https://linux-hardware.org/?probe=bb72f6af02) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9f0452aba6](https://linux-hardware.org/?probe=9f0452aba6) | Oct 29, 2023 |
| Lenovo        | ThinkPad T420 4236W1Y       | Notebook    | [2ff5cba7a7](https://linux-hardware.org/?probe=2ff5cba7a7) | Oct 29, 2023 |
| Medion        | TJ4125                      | Desktop     | [f791cf88cb](https://linux-hardware.org/?probe=f791cf88cb) | Oct 27, 2023 |
| Dell          | 0HH807                      | Desktop     | [7f15d65c22](https://linux-hardware.org/?probe=7f15d65c22) | Oct 27, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [a899ecd171](https://linux-hardware.org/?probe=a899ecd171) | Oct 27, 2023 |
| Toshiba       | Satellite L745              | Notebook    | [c126c9e041](https://linux-hardware.org/?probe=c126c9e041) | Oct 27, 2023 |
| Avell High... | 1513 Mxti                   | Notebook    | [9f5d60c02b](https://linux-hardware.org/?probe=9f5d60c02b) | Oct 27, 2023 |
| Unknown       | P4M800CE-8237               | Desktop     | [bf22b887f8](https://linux-hardware.org/?probe=bf22b887f8) | Oct 26, 2023 |
| ASUSTek       | X505BP                      | Notebook    | [884529eef1](https://linux-hardware.org/?probe=884529eef1) | Oct 26, 2023 |
| ASUSTek       | X505BP                      | Notebook    | [f32e8922c8](https://linux-hardware.org/?probe=f32e8922c8) | Oct 26, 2023 |
| ASRock        | Z97 Pro4                    | Desktop     | [bcf737a9cd](https://linux-hardware.org/?probe=bcf737a9cd) | Oct 25, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD000... | Notebook    | [4e393023d7](https://linux-hardware.org/?probe=4e393023d7) | Oct 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [251baa33d7](https://linux-hardware.org/?probe=251baa33d7) | Oct 23, 2023 |
| Unknown       | Unknown                     | Notebook    | [a06cdb13fc](https://linux-hardware.org/?probe=a06cdb13fc) | Oct 23, 2023 |
| Framework     | Laptop                      | Notebook    | [f78c8c1b58](https://linux-hardware.org/?probe=f78c8c1b58) | Oct 22, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [b9698d48be](https://linux-hardware.org/?probe=b9698d48be) | Oct 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [77fb62615e](https://linux-hardware.org/?probe=77fb62615e) | Oct 22, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [74d5de2172](https://linux-hardware.org/?probe=74d5de2172) | Oct 21, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [4633508fb0](https://linux-hardware.org/?probe=4633508fb0) | Oct 20, 2023 |
| HP            | Pavilion dv6                | Notebook    | [d5669e2ea8](https://linux-hardware.org/?probe=d5669e2ea8) | Oct 19, 2023 |
| Acer          | Predator G3-605             | Desktop     | [d3b59b34a0](https://linux-hardware.org/?probe=d3b59b34a0) | Oct 19, 2023 |
| Alienware     | 13                          | Notebook    | [15e7dfbbab](https://linux-hardware.org/?probe=15e7dfbbab) | Oct 19, 2023 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [5064906065](https://linux-hardware.org/?probe=5064906065) | Oct 18, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [041aba02ce](https://linux-hardware.org/?probe=041aba02ce) | Oct 17, 2023 |
| HP            | 843B                        | Desktop     | [0e5a69e3ab](https://linux-hardware.org/?probe=0e5a69e3ab) | Oct 17, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [1d624b8227](https://linux-hardware.org/?probe=1d624b8227) | Oct 17, 2023 |
| Alienware     | 13                          | Notebook    | [24ce621e56](https://linux-hardware.org/?probe=24ce621e56) | Oct 16, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2G90... | Notebook    | [36282033c6](https://linux-hardware.org/?probe=36282033c6) | Oct 15, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [cf68d0c810](https://linux-hardware.org/?probe=cf68d0c810) | Oct 14, 2023 |
| HP            | ENVY dv7                    | Notebook    | [0972d8543e](https://linux-hardware.org/?probe=0972d8543e) | Oct 14, 2023 |
| ASRock        | H310M-STX                   | Desktop     | [b0bc91de7a](https://linux-hardware.org/?probe=b0bc91de7a) | Oct 14, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [809ff050d7](https://linux-hardware.org/?probe=809ff050d7) | Oct 13, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [abfe76b2c9](https://linux-hardware.org/?probe=abfe76b2c9) | Oct 13, 2023 |
| Dell          | Latitude E6520              | Notebook    | [e29f6e9ba8](https://linux-hardware.org/?probe=e29f6e9ba8) | Oct 11, 2023 |
| Acer          | AOD270                      | Notebook    | [b45399c83c](https://linux-hardware.org/?probe=b45399c83c) | Oct 11, 2023 |
| Medion        | TJ4125                      | Desktop     | [e60adf45ac](https://linux-hardware.org/?probe=e60adf45ac) | Oct 10, 2023 |
| Lenovo        | ThinkPad T490 20N3S7DP00    | Notebook    | [eb9d7ec72c](https://linux-hardware.org/?probe=eb9d7ec72c) | Oct 10, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [d71ced0f1d](https://linux-hardware.org/?probe=d71ced0f1d) | Oct 08, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [7bd89c0f18](https://linux-hardware.org/?probe=7bd89c0f18) | Oct 07, 2023 |
| ASUSTek       | ROG STRIX Z790-I GAMING ... | Desktop     | [04473f37e9](https://linux-hardware.org/?probe=04473f37e9) | Oct 07, 2023 |
| Lenovo        | ThinkPad T430 2349STC       | Notebook    | [53e8d1302b](https://linux-hardware.org/?probe=53e8d1302b) | Oct 05, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [bfed98df15](https://linux-hardware.org/?probe=bfed98df15) | Oct 04, 2023 |
| Lenovo        | ThinkPad T420s 4176W23      | Notebook    | [0d27b7532c](https://linux-hardware.org/?probe=0d27b7532c) | Oct 02, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [271131f10a](https://linux-hardware.org/?probe=271131f10a) | Oct 01, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [438271a68c](https://linux-hardware.org/?probe=438271a68c) | Oct 01, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [f7375967ee](https://linux-hardware.org/?probe=f7375967ee) | Sep 30, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [4d2f60a496](https://linux-hardware.org/?probe=4d2f60a496) | Sep 29, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [99fb3ec5e9](https://linux-hardware.org/?probe=99fb3ec5e9) | Sep 29, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7fb0e4c19c](https://linux-hardware.org/?probe=7fb0e4c19c) | Sep 28, 2023 |
| Dell          | Latitude E5570              | Notebook    | [150f9e624b](https://linux-hardware.org/?probe=150f9e624b) | Sep 28, 2023 |
| HP            | 620                         | Notebook    | [1bdfd56638](https://linux-hardware.org/?probe=1bdfd56638) | Sep 27, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [5fa6a632ae](https://linux-hardware.org/?probe=5fa6a632ae) | Sep 18, 2023 |
| HP            | 158B                        | Desktop     | [d56ff45f03](https://linux-hardware.org/?probe=d56ff45f03) | Sep 17, 2023 |
| HP            | Compaq Mini 311-1100        | Notebook    | [eefc7ef22f](https://linux-hardware.org/?probe=eefc7ef22f) | Sep 17, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [11d9d55772](https://linux-hardware.org/?probe=11d9d55772) | Sep 17, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [807a40b618](https://linux-hardware.org/?probe=807a40b618) | Sep 15, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/LMDE_6/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 6.1.0-12-amd64           | 76        | 14.53%  |
| 6.1.0-13-amd64           | 68        | 13%     |
| 6.1.0-17-amd64           | 47        | 8.99%   |
| 6.1.0-18-amd64           | 42        | 8.03%   |
| 6.1.0-23-amd64           | 35        | 6.69%   |
| 6.1.0-21-amd64           | 32        | 6.12%   |
| 6.1.0-26-amd64           | 31        | 5.93%   |
| 6.1.0-25-amd64           | 27        | 5.16%   |
| 6.1.0-28-amd64           | 24        | 4.59%   |
| 6.1.0-20-amd64           | 21        | 4.02%   |
| 6.1.0-16-amd64           | 19        | 3.63%   |
| 6.1.0-12-686             | 12        | 2.29%   |
| 6.1.0-27-amd64           | 10        | 1.91%   |
| 6.1.0-22-amd64           | 9         | 1.72%   |
| 6.1.0-15-amd64           | 7         | 1.34%   |
| 6.10.11+bpo-amd64        | 4         | 0.76%   |
| 6.1.0-14-amd64           | 4         | 0.76%   |
| 6.5.0-0.deb12.4-amd64    | 3         | 0.57%   |
| 6.1.0-27-686             | 3         | 0.57%   |
| 6.1.0-20-686             | 3         | 0.57%   |
| 6.1.0-18-686             | 3         | 0.57%   |
| 6.9.7+bpo-amd64          | 2         | 0.38%   |
| 6.9.5-1-liquorix-amd64   | 2         | 0.38%   |
| 6.6.13+bpo-amd64         | 2         | 0.38%   |
| 6.11.5+bpo-amd64         | 2         | 0.38%   |
| 6.10.6+bpo-amd64         | 2         | 0.38%   |
| 6.1.0-28-686             | 2         | 0.38%   |
| 6.1.0-26-686             | 2         | 0.38%   |
| 6.1.0-25-686             | 2         | 0.38%   |
| 6.9.7-1-liquorix-amd64   | 1         | 0.19%   |
| 6.7.12+bpo-amd64         | 1         | 0.19%   |
| 6.7.10-060710-generic    | 1         | 0.19%   |
| 6.6.2-x64v4-xanmod1      | 1         | 0.19%   |
| 6.6.15-x64v3-xanmod1     | 1         | 0.19%   |
| 6.6.13-1-liquorix-amd64  | 1         | 0.19%   |
| 6.6.11-x64v3-xanmod1     | 1         | 0.19%   |
| 6.6.10-chrultrabook      | 1         | 0.19%   |
| 6.5.11-asus-vivobook     | 1         | 0.19%   |
| 6.5.10-asus-vivobook     | 1         | 0.19%   |
| 6.5.0-0.deb12.1-rt-amd64 | 1         | 0.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.0   | 441       | 92.45%  |
| 6.5.0   | 5         | 1.05%   |
| 6.10.11 | 4         | 0.84%   |
| 6.9.7   | 3         | 0.63%   |
| 6.6.13  | 3         | 0.63%   |
| 6.9.5   | 2         | 0.42%   |
| 6.11.5  | 2         | 0.42%   |
| 6.11.10 | 2         | 0.42%   |
| 6.10.6  | 2         | 0.42%   |
| 5.10.0  | 2         | 0.42%   |
| 6.7.12  | 1         | 0.21%   |
| 6.7.10  | 1         | 0.21%   |
| 6.6.2   | 1         | 0.21%   |
| 6.6.15  | 1         | 0.21%   |
| 6.6.11  | 1         | 0.21%   |
| 6.6.10  | 1         | 0.21%   |
| 6.5.11  | 1         | 0.21%   |
| 6.5.10  | 1         | 0.21%   |
| 6.4.0   | 1         | 0.21%   |
| 6.12.6  | 1         | 0.21%   |
| 6.10.5  | 1         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 441       | 92.65%  |
| 6.6     | 7         | 1.47%   |
| 6.10    | 7         | 1.47%   |
| 6.5     | 6         | 1.26%   |
| 6.9     | 5         | 1.05%   |
| 6.11    | 4         | 0.84%   |
| 6.7     | 2         | 0.42%   |
| 5.10    | 2         | 0.42%   |
| 6.4     | 1         | 0.21%   |
| 6.12    | 1         | 0.21%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 443       | 93.26%  |
| i686   | 32        | 6.74%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 440       | 92.24%  |
| Cinnamon   | 12        | 2.52%   |
| Unknown    | 12        | 2.52%   |
| KDE5       | 4         | 0.84%   |
| XFCE       | 3         | 0.63%   |
| LXDE       | 3         | 0.63%   |
| MATE       | 2         | 0.42%   |
| GNOME      | 1         | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 467       | 98.52%  |
| Wayland | 5         | 1.05%   |
| Tty     | 2         | 0.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 324       | 68.07%  |
| Unknown | 147       | 30.88%  |
| GDM3    | 3         | 0.63%   |
| SDDM    | 2         | 0.42%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 167       | 35.08%  |
| de_DE   | 73        | 15.34%  |
| it_IT   | 65        | 13.66%  |
| en_GB   | 26        | 5.46%   |
| fr_FR   | 23        | 4.83%   |
| ru_RU   | 15        | 3.15%   |
| pt_BR   | 15        | 3.15%   |
| Unknown | 12        | 2.52%   |
| pl_PL   | 9         | 1.89%   |
| es_ES   | 9         | 1.89%   |
| nl_NL   | 5         | 1.05%   |
| en_AU   | 5         | 1.05%   |
| cs_CZ   | 5         | 1.05%   |
| sv_SE   | 4         | 0.84%   |
| hu_HU   | 3         | 0.63%   |
| es_AR   | 3         | 0.63%   |
| en_CA   | 3         | 0.63%   |
| tr_TR   | 2         | 0.42%   |
| nl_BE   | 2         | 0.42%   |
| es_UY   | 2         | 0.42%   |
| es_HN   | 2         | 0.42%   |
| es_BO   | 2         | 0.42%   |
| en_NZ   | 2         | 0.42%   |
| de_CH   | 2         | 0.42%   |
| ro_RO   | 1         | 0.21%   |
| pt_PT   | 1         | 0.21%   |
| nn_NO   | 1         | 0.21%   |
| ja_JP   | 1         | 0.21%   |
| it_CH   | 1         | 0.21%   |
| hr_HR   | 1         | 0.21%   |
| gl_ES   | 1         | 0.21%   |
| fr_CA   | 1         | 0.21%   |
| fi_FI   | 1         | 0.21%   |
| es_PA   | 1         | 0.21%   |
| es_MX   | 1         | 0.21%   |
| es_GT   | 1         | 0.21%   |
| es_DO   | 1         | 0.21%   |
| en_ZA   | 1         | 0.21%   |
| en_SG   | 1         | 0.21%   |
| en_IN   | 1         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 328       | 68.91%  |
| BIOS | 148       | 31.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 395       | 82.29%  |
| Overlay | 35        | 7.29%   |
| Btrfs   | 25        | 5.21%   |
| Tmpfs   | 23        | 4.79%   |
| Zfs     | 1         | 0.21%   |
| Xfs     | 1         | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 255       | 53.57%  |
| Unknown | 136       | 28.57%  |
| MBR     | 85        | 17.86%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 421       | 88.08%  |
| Yes       | 57        | 11.92%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 355       | 74.11%  |
| Yes       | 124       | 25.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 96        | 20.25%  |
| Hewlett-Packard                      | 73        | 15.4%   |
| Lenovo                               | 64        | 13.5%   |
| Dell                                 | 38        | 8.02%   |
| MSI                                  | 25        | 5.27%   |
| Acer                                 | 25        | 5.27%   |
| Gigabyte Technology                  | 20        | 4.22%   |
| Apple                                | 20        | 4.22%   |
| ASRock                               | 16        | 3.38%   |
| Fujitsu                              | 13        | 2.74%   |
| Toshiba                              | 8         | 1.69%   |
| Intel                                | 7         | 1.48%   |
| Unknown                              | 7         | 1.48%   |
| HUAWEI                               | 5         | 1.05%   |
| Notebook                             | 4         | 0.84%   |
| Sony                                 | 3         | 0.63%   |
| Shenzhen Meigao Electronic Equipment | 3         | 0.63%   |
| Samsung Electronics                  | 3         | 0.63%   |
| Medion                               | 3         | 0.63%   |
| AZW                                  | 3         | 0.63%   |
| TUXEDO                               | 2         | 0.42%   |
| Inventec                             | 2         | 0.42%   |
| Google                               | 2         | 0.42%   |
| GEEKOM                               | 2         | 0.42%   |
| Fujitsu Siemens                      | 2         | 0.42%   |
| Alienware                            | 2         | 0.42%   |
| VALE                                 | 1         | 0.21%   |
| Trigkey                              | 1         | 0.21%   |
| TENKU                                | 1         | 0.21%   |
| Soyo                                 | 1         | 0.21%   |
| Quanta                               | 1         | 0.21%   |
| PELADN                               | 1         | 0.21%   |
| Pegatron                             | 1         | 0.21%   |
| Packard Bell                         | 1         | 0.21%   |
| Olidata                              | 1         | 0.21%   |
| Monster                              | 1         | 0.21%   |
| Microsoft                            | 1         | 0.21%   |
| Maibenben                            | 1         | 0.21%   |
| MACHINIST                            | 1         | 0.21%   |
| LETSUNG                              | 1         | 0.21%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown                                             | 9         | 1.9%    |
| ASUS VivoBook_ASUSLaptop X1605VA_X1605VA            | 3         | 0.63%   |
| ASUS All Series                                     | 3         | 0.63%   |
| Shenzhen Meigao Electronic Equipment Mercury series | 2         | 0.42%   |
| MSI MS-7D91                                         | 2         | 0.42%   |
| HUAWEI CREM-WXX9                                    | 2         | 0.42%   |
| HP Pavilion dv6                                     | 2         | 0.42%   |
| HP Pavilion 15                                      | 2         | 0.42%   |
| HP Notebook                                         | 2         | 0.42%   |
| HP Laptop 15-dy2xxx                                 | 2         | 0.42%   |
| HP Laptop 15-dw1xxx                                 | 2         | 0.42%   |
| HP EliteDesk 800 G3 DM 65W                          | 2         | 0.42%   |
| HP EliteBook 8440p                                  | 2         | 0.42%   |
| Gigabyte A520M S2H                                  | 2         | 0.42%   |
| Dell XPS 13 9360                                    | 2         | 0.42%   |
| Dell Precision T1700                                | 2         | 0.42%   |
| Dell OptiPlex 7010                                  | 2         | 0.42%   |
| Dell Latitude E6430                                 | 2         | 0.42%   |
| ASUS Zenbook UX3402ZA_UX3402ZA                      | 2         | 0.42%   |
| ASUS NUC13ANH-B                                     | 2         | 0.42%   |
| Apple MacBookAir6,2                                 | 2         | 0.42%   |
| Apple iMac5,1                                       | 2         | 0.42%   |
| Acer Aspire E5-575                                  | 2         | 0.42%   |
| VALE Notebook Classic C171V                         | 1         | 0.21%   |
| TUXEDO Pulse 14 Gen1                                | 1         | 0.21%   |
| TUXEDO InfinityBook S Gen8                          | 1         | 0.21%   |
| Trigkey Green G4                                    | 1         | 0.21%   |
| Toshiba TECRA X40-D                                 | 1         | 0.21%   |
| Toshiba Satellite Pro L100                          | 1         | 0.21%   |
| Toshiba Satellite Pro C850-1DQ                      | 1         | 0.21%   |
| Toshiba Satellite P105                              | 1         | 0.21%   |
| Toshiba Satellite M100                              | 1         | 0.21%   |
| Toshiba Satellite L745                              | 1         | 0.21%   |
| Toshiba Satellite L50D-B                            | 1         | 0.21%   |
| Toshiba Satellite A135                              | 1         | 0.21%   |
| TENKU Mobile S10                                    | 1         | 0.21%   |
| Soyo SY-N3150L Quad                                 | 1         | 0.21%   |
| Sony VPCM12M1E                                      | 1         | 0.21%   |
| Sony VGN-FW21E                                      | 1         | 0.21%   |
| Sony SVE1511A1EW                                    | 1         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Lenovo ThinkPad                              | 37        | 7.81%   |
| Acer Aspire                                  | 18        | 3.8%    |
| ASUS VivoBook                                | 16        | 3.38%   |
| HP Pavilion                                  | 12        | 2.53%   |
| HP Laptop                                    | 11        | 2.32%   |
| Dell Latitude                                | 11        | 2.32%   |
| HP EliteBook                                 | 10        | 2.11%   |
| ASUS PRIME                                   | 10        | 2.11%   |
| Lenovo IdeaPad                               | 9         | 1.9%    |
| Unknown                                      | 9         | 1.9%    |
| ASUS TUF                                     | 8         | 1.69%   |
| Toshiba Satellite                            | 7         | 1.48%   |
| HP ProBook                                   | 7         | 1.48%   |
| HP Compaq                                    | 7         | 1.48%   |
| Dell Inspiron                                | 7         | 1.48%   |
| ASUS ROG                                     | 7         | 1.48%   |
| Dell Precision                               | 6         | 1.27%   |
| ASUS ASUS                                    | 6         | 1.27%   |
| HP ENVY                                      | 5         | 1.05%   |
| Fujitsu LIFEBOOK                             | 5         | 1.05%   |
| Fujitsu ESPRIMO                              | 5         | 1.05%   |
| Dell XPS                                     | 5         | 1.05%   |
| Dell OptiPlex                                | 5         | 1.05%   |
| ASUS Zenbook                                 | 5         | 1.05%   |
| Lenovo ThinkCentre                           | 4         | 0.84%   |
| Lenovo Yoga                                  | 3         | 0.63%   |
| ASUS P5G41T-M                                | 3         | 0.63%   |
| ASUS All                                     | 3         | 0.63%   |
| Shenzhen Meigao Electronic Equipment Mercury | 2         | 0.42%   |
| MSI MS-7D91                                  | 2         | 0.42%   |
| HUAWEI CREM-WXX9                             | 2         | 0.42%   |
| HP ProDesk                                   | 2         | 0.42%   |
| HP Notebook                                  | 2         | 0.42%   |
| HP EliteDesk                                 | 2         | 0.42%   |
| HP 250                                       | 2         | 0.42%   |
| Gigabyte B450                                | 2         | 0.42%   |
| Gigabyte A520M                               | 2         | 0.42%   |
| Fujitsu Siemens AMILO                        | 2         | 0.42%   |
| Fujitsu CELSIUS                              | 2         | 0.42%   |
| Dell Vostro                                  | 2         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 45        | 9.49%   |
| 2023    | 43        | 9.07%   |
| 2020    | 31        | 6.54%   |
| 2017    | 31        | 6.54%   |
| 2018    | 30        | 6.33%   |
| 2021    | 29        | 6.12%   |
| 2012    | 29        | 6.12%   |
| 2010    | 26        | 5.49%   |
| 2019    | 25        | 5.27%   |
| 2014    | 24        | 5.06%   |
| 2016    | 23        | 4.85%   |
| 2013    | 23        | 4.85%   |
| 2015    | 20        | 4.22%   |
| 2008    | 20        | 4.22%   |
| 2011    | 19        | 4.01%   |
| 2007    | 14        | 2.95%   |
| 2024    | 13        | 2.74%   |
| 2009    | 13        | 2.74%   |
| 2006    | 10        | 2.11%   |
| Unknown | 3         | 0.63%   |
| 2005    | 1         | 0.21%   |
| 2004    | 1         | 0.21%   |
| 2003    | 1         | 0.21%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 266       | 56.12%  |
| Desktop     | 166       | 35.02%  |
| Mini pc     | 16        | 3.38%   |
| All in one  | 13        | 2.74%   |
| Convertible | 7         | 1.48%   |
| Tablet      | 3         | 0.63%   |
| Server      | 2         | 0.42%   |
| Other       | 1         | 0.21%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 432       | 90.95%  |
| Enabled  | 43        | 9.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 472       | 99.58%  |
| Yes  | 2         | 0.42%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 130       | 27.14%  |
| 16.01-24.0  | 95        | 19.83%  |
| 3.01-4.0    | 62        | 12.94%  |
| 8.01-16.0   | 62        | 12.94%  |
| 32.01-64.0  | 59        | 12.32%  |
| 64.01-256.0 | 25        | 5.22%   |
| 24.01-32.0  | 19        | 3.97%   |
| 1.01-2.0    | 12        | 2.51%   |
| 2.01-3.0    | 11        | 2.3%    |
| 0.51-1.0    | 4         | 0.84%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 154       | 30.74%  |
| 1.01-2.0   | 127       | 25.35%  |
| 4.01-8.0   | 102       | 20.36%  |
| 3.01-4.0   | 84        | 16.77%  |
| 8.01-16.0  | 18        | 3.59%   |
| 0.51-1.0   | 10        | 2%      |
| 16.01-24.0 | 3         | 0.6%    |
| 0.01-0.5   | 2         | 0.4%    |
| 24.01-32.0 | 1         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 288       | 59.75%  |
| 2      | 109       | 22.61%  |
| 3      | 39        | 8.09%   |
| 4      | 22        | 4.56%   |
| 5      | 9         | 1.87%   |
| 0      | 5         | 1.04%   |
| 6      | 4         | 0.83%   |
| 7      | 3         | 0.62%   |
| 8      | 2         | 0.41%   |
| 10     | 1         | 0.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 315       | 66.46%  |
| Yes       | 159       | 33.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 400       | 84.39%  |
| No        | 74        | 15.61%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 386       | 81.43%  |
| No        | 88        | 18.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 326       | 68.49%  |
| No        | 150       | 31.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 94        | 19.83%  |
| Italy        | 87        | 18.35%  |
| USA          | 76        | 16.03%  |
| France       | 20        | 4.22%   |
| Brazil       | 17        | 3.59%   |
| UK           | 16        | 3.38%   |
| Russia       | 15        | 3.16%   |
| Spain        | 11        | 2.32%   |
| Poland       | 11        | 2.32%   |
| Canada       | 9         | 1.9%    |
| Sweden       | 6         | 1.27%   |
| Netherlands  | 6         | 1.27%   |
| Malaysia     | 6         | 1.27%   |
| Argentina    | 6         | 1.27%   |
| India        | 5         | 1.05%   |
| Czechia      | 5         | 1.05%   |
| Belgium      | 5         | 1.05%   |
| Australia    | 5         | 1.05%   |
| Turkey       | 4         | 0.84%   |
| Switzerland  | 4         | 0.84%   |
| Romania      | 4         | 0.84%   |
| Hungary      | 4         | 0.84%   |
| Norway       | 3         | 0.63%   |
| New Zealand  | 3         | 0.63%   |
| Austria      | 3         | 0.63%   |
| Uruguay      | 2         | 0.42%   |
| Ukraine      | 2         | 0.42%   |
| Saudi Arabia | 2         | 0.42%   |
| Portugal     | 2         | 0.42%   |
| Mexico       | 2         | 0.42%   |
| Japan        | 2         | 0.42%   |
| Indonesia    | 2         | 0.42%   |
| Greece       | 2         | 0.42%   |
| Finland      | 2         | 0.42%   |
| Denmark      | 2         | 0.42%   |
| Croatia      | 2         | 0.42%   |
| Bolivia      | 2         | 0.42%   |
| South Africa | 1         | 0.21%   |
| Réunion     | 1         | 0.21%   |
| Puerto Rico  | 1         | 0.21%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Milan            | 13        | 2.6%    |
| Berlin           | 10        | 2%      |
| Traunstein       | 8         | 1.6%    |
| Bologna          | 8         | 1.6%    |
| Rome             | 6         | 1.2%    |
| Florence         | 5         | 1%      |
| Delligsen        | 5         | 1%      |
| Sydney           | 4         | 0.8%    |
| Paris            | 4         | 0.8%    |
| Kuala Lumpur     | 4         | 0.8%    |
| Turin            | 3         | 0.6%    |
| Padova           | 3         | 0.6%    |
| Milano           | 3         | 0.6%    |
| Mannheim         | 3         | 0.6%    |
| Madrid           | 3         | 0.6%    |
| Hamburg          | 3         | 0.6%    |
| Duingen          | 3         | 0.6%    |
| Dallas           | 3         | 0.6%    |
| Cologne          | 3         | 0.6%    |
| Bucharest        | 3         | 0.6%    |
| Bonn             | 3         | 0.6%    |
| Auckland         | 3         | 0.6%    |
| Aalten           | 3         | 0.6%    |
| Yekaterinburg    | 2         | 0.4%    |
| Vienna           | 2         | 0.4%    |
| Verona           | 2         | 0.4%    |
| Valencia         | 2         | 0.4%    |
| Uetze            | 2         | 0.4%    |
| Toronto          | 2         | 0.4%    |
| Stuttgart        | 2         | 0.4%    |
| St Petersburg    | 2         | 0.4%    |
| South Bend       | 2         | 0.4%    |
| Sochi            | 2         | 0.4%    |
| Slough           | 2         | 0.4%    |
| Šlapanice       | 2         | 0.4%    |
| Shah Alam        | 2         | 0.4%    |
| Sesto Fiorentino | 2         | 0.4%    |
| Sao Paulo        | 2         | 0.4%    |
| San Antonio      | 2         | 0.4%    |
| Rho              | 2         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 110       | 150    | 14.88%  |
| WDC                         | 84        | 110    | 11.37%  |
| Seagate                     | 69        | 102    | 9.34%   |
| SanDisk                     | 41        | 50     | 5.55%   |
| Kingston                    | 38        | 64     | 5.14%   |
| Crucial                     | 38        | 44     | 5.14%   |
| Toshiba                     | 30        | 34     | 4.06%   |
| Unknown                     | 22        | 35     | 2.98%   |
| Micron Technology           | 20        | 22     | 2.71%   |
| China                       | 15        | 16     | 2.03%   |
| SK hynix                    | 14        | 14     | 1.89%   |
| Intel                       | 12        | 13     | 1.62%   |
| Hitachi                     | 12        | 13     | 1.62%   |
| Unknown                     | 12        | 22     | 1.62%   |
| SPCC                        | 11        | 11     | 1.49%   |
| Apple                       | 10        | 11     | 1.35%   |
| A-DATA Technology           | 10        | 11     | 1.35%   |
| PNY                         | 9         | 13     | 1.22%   |
| Phison Electronics          | 8         | 9      | 1.08%   |
| KIOXIA                      | 8         | 11     | 1.08%   |
| Intenso                     | 8         | 8      | 1.08%   |
| Lexar                       | 7         | 7      | 0.95%   |
| JMicron Technology          | 7         | 7      | 0.95%   |
| HGST                        | 7         | 7      | 0.95%   |
| Micron/Crucial Technology   | 6         | 9      | 0.81%   |
| Kingston Technology Company | 6         | 6      | 0.81%   |
| Apacer                      | 6         | 8      | 0.81%   |
| ADATA Technology            | 6         | 10     | 0.81%   |
| Team                        | 5         | 6      | 0.68%   |
| Phison                      | 5         | 11     | 0.68%   |
| Patriot                     | 5         | 5      | 0.68%   |
| MAXIO Technology (Hangzhou) | 5         | 5      | 0.68%   |
| Gigabyte Technology         | 5         | 5      | 0.68%   |
| Fujitsu                     | 5         | 5      | 0.68%   |
| XrayDisk                    | 4         | 4      | 0.54%   |
| Verbatim                    | 4         | 5      | 0.54%   |
| Transcend                   | 3         | 3      | 0.41%   |
| TO Exter                    | 3         | 3      | 0.41%   |
| T-FORCE                     | 3         | 3      | 0.41%   |
| Silicon Motion              | 3         | 3      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown                                                           | 12        | 1.5%    |
| SanDisk NVMe SSD Drive 1TB                                        | 10        | 1.25%   |
| Kingston SA400S37480G 480GB SSD                                   | 10        | 1.25%   |
| Kingston SA400S37240G 240GB SSD                                   | 8         | 1%      |
| Crucial CT500MX500SSD1 500GB                                      | 8         | 1%      |
| Seagate ST1000LM035-1RK172 1TB                                    | 6         | 0.75%   |
| SanDisk NVMe SSD Drive 2TB                                        | 6         | 0.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB               | 6         | 0.75%   |
| Crucial CT1000MX500SSD1 1TB                                       | 6         | 0.75%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                              | 5         | 0.62%   |
| Samsung SSD 980 1TB                                               | 5         | 0.62%   |
| Samsung SSD 860 EVO 250GB                                         | 5         | 0.62%   |
| MAXIO (Hangzhou) NVMe SSD Drive 512GB                             | 5         | 0.62%   |
| JMicron Generic 500GB                                             | 5         | 0.62%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 256GB | 5         | 0.62%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                                  | 4         | 0.5%    |
| Unknown SD/MMC/MS PRO 128GB                                       | 4         | 0.5%    |
| Seagate ST2000DM006-2DM164 2TB                                    | 4         | 0.5%    |
| SanDisk NVMe SSD Drive 512GB                                      | 4         | 0.5%    |
| Samsung SSD 990 PRO 2TB                                           | 4         | 0.5%    |
| Samsung SSD 980 500GB                                             | 4         | 0.5%    |
| Samsung SSD 970 EVO Plus 2TB                                      | 4         | 0.5%    |
| Samsung SSD 860 EVO 500GB                                         | 4         | 0.5%    |
| Phison PS5013 E13 NVMe Controller 512GB                           | 4         | 0.5%    |
| Unknown MMC Card  128GB                                           | 3         | 0.37%   |
| Toshiba MQ01ABD100 1TB                                            | 3         | 0.37%   |
| Toshiba DT01ACA100 1TB                                            | 3         | 0.37%   |
| TO Exter nal USB 3.0 1024GB                                       | 3         | 0.37%   |
| SPCC Solid State Disk 256GB                                       | 3         | 0.37%   |
| SK hynix BC711 HFM256GD3JX013N 256GB                              | 3         | 0.37%   |
| Seagate ST9500325AS 500GB                                         | 3         | 0.37%   |
| Seagate ST500LM021-1KJ152 500GB                                   | 3         | 0.37%   |
| Seagate ST1000DM003-1ER162 1TB                                    | 3         | 0.37%   |
| Seagate Expansion Desk 5TB                                        | 3         | 0.37%   |
| Samsung SSD 990 PRO 1TB                                           | 3         | 0.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB              | 3         | 0.37%   |
| Samsung MZVLQ1T0HALB-00000 1TB                                    | 3         | 0.37%   |
| Samsung MZVL4512HBLU-00BTW 512GB                                  | 3         | 0.37%   |
| SABRENT Disk 2TB                                                  | 3         | 0.37%   |
| Phison PCIe SSD 512GB                                             | 3         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 68        | 100    | 32.38%  |
| WDC                 | 59        | 80     | 28.1%   |
| Toshiba             | 25        | 29     | 11.9%   |
| Hitachi             | 12        | 13     | 5.71%   |
| HGST                | 7         | 7      | 3.33%   |
| JMicron Technology  | 5         | 5      | 2.38%   |
| Fujitsu             | 5         | 5      | 2.38%   |
| Apple               | 5         | 5      | 2.38%   |
| Unknown             | 4         | 4      | 1.9%    |
| Samsung Electronics | 4         | 4      | 1.9%    |
| TO Exter            | 3         | 3      | 1.43%   |
| SABRENT             | 3         | 3      | 1.43%   |
| Maxtor              | 2         | 2      | 0.95%   |
| External            | 2         | 2      | 0.95%   |
| USB3.0              | 1         | 1      | 0.48%   |
| Intenso             | 1         | 1      | 0.48%   |
| IBM/Hitachi         | 1         | 1      | 0.48%   |
| DC-624e             | 1         | 1      | 0.48%   |
| ASMedia             | 1         | 1      | 0.48%   |
| Unknown             | 1         | 1      | 0.48%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 49        | 60     | 18.77%  |
| Kingston            | 30        | 49     | 11.49%  |
| Crucial             | 27        | 32     | 10.34%  |
| WDC                 | 15        | 17     | 5.75%   |
| China               | 15        | 16     | 5.75%   |
| SanDisk             | 14        | 15     | 5.36%   |
| SPCC                | 9         | 9      | 3.45%   |
| PNY                 | 9         | 13     | 3.45%   |
| A-DATA Technology   | 7         | 8      | 2.68%   |
| Team                | 5         | 6      | 1.92%   |
| Intenso             | 5         | 5      | 1.92%   |
| Apple               | 5         | 5      | 1.92%   |
| Unknown             | 5         | 13     | 1.92%   |
| Patriot             | 4         | 4      | 1.53%   |
| Micron Technology   | 4         | 5      | 1.53%   |
| Intel               | 4         | 5      | 1.53%   |
| Apacer              | 4         | 6      | 1.53%   |
| Verbatim            | 3         | 4      | 1.15%   |
| Transcend           | 3         | 3      | 1.15%   |
| Phison              | 3         | 9      | 1.15%   |
| Gigabyte Technology | 3         | 3      | 1.15%   |
| XrayDisk            | 2         | 2      | 0.77%   |
| Toshiba             | 2         | 2      | 0.77%   |
| T-FORCE             | 2         | 2      | 0.77%   |
| SK hynix            | 2         | 2      | 0.77%   |
| OCZ                 | 2         | 2      | 0.77%   |
| Lexar               | 2         | 2      | 0.77%   |
| Integral            | 2         | 2      | 0.77%   |
| Hewlett-Packard     | 2         | 2      | 0.77%   |
| Fanxiang            | 2         | 3      | 0.77%   |
| V Series            | 1         | 1      | 0.38%   |
| TrueNAS             | 1         | 1      | 0.38%   |
| Solid               | 1         | 1      | 0.38%   |
| PELADN              | 1         | 1      | 0.38%   |
| OWC                 | 1         | 1      | 0.38%   |
| NT-512              | 1         | 1      | 0.38%   |
| MAXSUN              | 1         | 1      | 0.38%   |
| LITEONIT            | 1         | 1      | 0.38%   |
| LDLC                | 1         | 1      | 0.38%   |
| KUU                 | 1         | 1      | 0.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 226       | 326    | 34.66%  |
| NVMe    | 215       | 298    | 32.98%  |
| HDD     | 175       | 268    | 26.84%  |
| MMC     | 20        | 29     | 3.07%   |
| Unknown | 16        | 24     | 2.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 323       | 558    | 53.57%  |
| NVMe | 214       | 296    | 35.49%  |
| SAS  | 46        | 62     | 7.63%   |
| MMC  | 20        | 29     | 3.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 238       | 335    | 55.48%  |
| 0.51-1.0   | 114       | 145    | 26.57%  |
| 1.01-2.0   | 39        | 58     | 9.09%   |
| 3.01-4.0   | 17        | 25     | 3.96%   |
| 4.01-10.0  | 13        | 20     | 3.03%   |
| 2.01-3.0   | 6         | 8      | 1.4%    |
| 10.01-20.0 | 2         | 3      | 0.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 121       | 24.8%   |
| 251-500        | 97        | 19.88%  |
| 501-1000       | 90        | 18.44%  |
| 1001-2000      | 52        | 10.66%  |
| 1-20           | 35        | 7.17%   |
| More than 3000 | 34        | 6.97%   |
| 51-100         | 21        | 4.3%    |
| 2001-3000      | 18        | 3.69%   |
| Unknown        | 12        | 2.46%   |
| 21-50          | 8         | 1.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 154       | 30.56%  |
| 21-50          | 100       | 19.84%  |
| 101-250        | 73        | 14.48%  |
| 51-100         | 57        | 11.31%  |
| 251-500        | 36        | 7.14%   |
| 501-1000       | 34        | 6.75%   |
| 1001-2000      | 17        | 3.37%   |
| More than 3000 | 14        | 2.78%   |
| Unknown        | 12        | 2.38%   |
| 2001-3000      | 7         | 1.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                           | 2         | 2      | 3.7%    |
| WDC WD7500BPVT-00HXZT3 752GB                        | 1         | 1      | 1.85%   |
| WDC WD5000LPVX-60V0TT0 500GB                        | 1         | 1      | 1.85%   |
| WDC WD3200BEVT-22A23T0 320GB                        | 1         | 1      | 1.85%   |
| WDC WD3200AAKS-00L9A0 320GB                         | 1         | 1      | 1.85%   |
| WDC WD15EADS-00P8B0 1TB                             | 1         | 1      | 1.85%   |
| WDC WD10SPZX-24Z10 1TB                              | 1         | 1      | 1.85%   |
| WDC WD10EZRZ-00HTKB0 1TB                            | 1         | 1      | 1.85%   |
| WDC WD10EZEX-75M2NA0 1TB                            | 1         | 1      | 1.85%   |
| WDC WD10EFRX-68PJCN0 1TB                            | 1         | 1      | 1.85%   |
| Unknown MMC Card  128GB                             | 1         | 1      | 1.85%   |
| Transcend TS512GMTS430S 512GB SSD                   | 1         | 1      | 1.85%   |
| Toshiba MK1652GSX 160GB                             | 1         | 1      | 1.85%   |
| Solid SSD0256S00 256GB                              | 1         | 1      | 1.85%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 1         | 1      | 1.85%   |
| SK hynix HFS060G32MNB-2000A 64GB SSD                | 1         | 1      | 1.85%   |
| Seagate ST910021AS 100GB                            | 1         | 1      | 1.85%   |
| Seagate ST500LM021-1KJ152 500GB                     | 1         | 1      | 1.85%   |
| Seagate ST31000528AS 1TB                            | 1         | 1      | 1.85%   |
| Seagate ST31000524AS 1TB                            | 1         | 1      | 1.85%   |
| Seagate ST2000DM006-2DM164 2TB                      | 1         | 1      | 1.85%   |
| Seagate ST1000LM014-1EJ164 1TB                      | 1         | 1      | 1.85%   |
| Seagate ST1000DX001-1NS162 1TB                      | 1         | 1      | 1.85%   |
| Seagate ST1000DM003-1SB102 1TB                      | 1         | 1      | 1.85%   |
| Samsung Electronics SSD 970 EVO 500GB               | 1         | 1      | 1.85%   |
| Samsung Electronics SSD 850 PRO 256GB               | 1         | 1      | 1.85%   |
| Samsung Electronics HM251JI 250GB                   | 1         | 1      | 1.85%   |
| Samsung Electronics HD103UJ 1TB                     | 1         | 1      | 1.85%   |
| Micron Technology MTFDDAK512MAY-1AE1ZABHA 512GB SSD | 1         | 1      | 1.85%   |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD      | 1         | 1      | 1.85%   |
| Maxtor 6E040L0 41GB                                 | 1         | 1      | 1.85%   |
| Lexar SSD 480GB                                     | 1         | 1      | 1.85%   |
| KUU SSD 512GB                                       | 1         | 1      | 1.85%   |
| Kingston SUV400S37240G 240GB SSD                    | 1         | 1      | 1.85%   |
| Kingston SKC2500M8500G 500GB                        | 1         | 1      | 1.85%   |
| Kingston SA400S37240G 240GB SSD                     | 1         | 1      | 1.85%   |
| Intel SSDSA2M080G2HP 80GB                           | 1         | 1      | 1.85%   |
| IBM/Hitachi IC35L040AVER07-0 41GB                   | 1         | 1      | 1.85%   |
| Hitachi HTS548080M9AT00 80GB                        | 1         | 1      | 1.85%   |
| Hitachi HTS543232L9A300 320GB                       | 1         | 1      | 1.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 18.52%  |
| WDC                 | 9         | 9      | 16.67%  |
| Samsung Electronics | 4         | 4      | 7.41%   |
| Hitachi             | 4         | 4      | 7.41%   |
| Kingston            | 3         | 3      | 5.56%   |
| Fujitsu             | 3         | 3      | 5.56%   |
| SK hynix            | 2         | 2      | 3.7%    |
| Micron Technology   | 2         | 2      | 3.7%    |
| China               | 2         | 2      | 3.7%    |
| Apple               | 2         | 2      | 3.7%    |
| A-DATA Technology   | 2         | 2      | 3.7%    |
| Unknown             | 1         | 1      | 1.85%   |
| Transcend           | 1         | 1      | 1.85%   |
| Toshiba             | 1         | 1      | 1.85%   |
| Solid               | 1         | 1      | 1.85%   |
| Maxtor              | 1         | 1      | 1.85%   |
| Lexar               | 1         | 1      | 1.85%   |
| KUU                 | 1         | 1      | 1.85%   |
| Intel               | 1         | 1      | 1.85%   |
| IBM/Hitachi         | 1         | 1      | 1.85%   |
| HGST                | 1         | 1      | 1.85%   |
| Crucial             | 1         | 2      | 1.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 30.3%   |
| WDC                 | 9         | 9      | 27.27%  |
| Hitachi             | 4         | 4      | 12.12%  |
| Fujitsu             | 3         | 3      | 9.09%   |
| Samsung Electronics | 2         | 2      | 6.06%   |
| Toshiba             | 1         | 1      | 3.03%   |
| Maxtor              | 1         | 1      | 3.03%   |
| IBM/Hitachi         | 1         | 1      | 3.03%   |
| HGST                | 1         | 1      | 3.03%   |
| Apple               | 1         | 1      | 3.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 33     | 60.38%  |
| SSD  | 17        | 18     | 32.08%  |
| NVMe | 3         | 3      | 5.66%   |
| MMC  | 1         | 1      | 1.89%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 288       | 473    | 52.94%  |
| Detected | 203       | 417    | 37.32%  |
| Malfunc  | 53        | 55     | 9.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 301       | 46.09%  |
| AMD                                     | 86        | 13.17%  |
| Samsung Electronics                     | 64        | 9.8%    |
| SanDisk                                 | 36        | 5.51%   |
| Phison Electronics                      | 18        | 2.76%   |
| Micron Technology                       | 17        | 2.6%    |
| Kingston Technology Company             | 16        | 2.45%   |
| Micron/Crucial Technology               | 15        | 2.3%    |
| SK hynix                                | 12        | 1.84%   |
| ASMedia Technology                      | 11        | 1.68%   |
| Marvell Technology Group                | 9         | 1.38%   |
| KIOXIA                                  | 9         | 1.38%   |
| ADATA Technology                        | 9         | 1.38%   |
| MAXIO Technology (Hangzhou)             | 8         | 1.23%   |
| JMicron Technology                      | 6         | 0.92%   |
| Silicon Motion                          | 5         | 0.77%   |
| Nvidia                                  | 5         | 0.77%   |
| Toshiba America Info Systems            | 4         | 0.61%   |
| VIA Technologies                        | 3         | 0.46%   |
| Shenzhen Longsys Electronics            | 3         | 0.46%   |
| Hosin Global Electronics                | 3         | 0.46%   |
| Realtek Semiconductor                   | 2         | 0.31%   |
| Union Memory (Shenzhen)                 | 1         | 0.15%   |
| Solidigm                                | 1         | 0.15%   |
| Silicon Image                           | 1         | 0.15%   |
| Shenzhen Unionmemory Information System | 1         | 0.15%   |
| Seagate Technology                      | 1         | 0.15%   |
| LSI Logic / Symbios Logic               | 1         | 0.15%   |
| Integrated Technology Express           | 1         | 0.15%   |
| INNOGRIT                                | 1         | 0.15%   |
| Dell                                    | 1         | 0.15%   |
| Broadcom / LSI                          | 1         | 0.15%   |
| Apple                                   | 1         | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 47        | 6.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 25        | 3.37%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 21        | 2.83%   |
| Intel Volume Management Device NVMe RAID Controller                            | 19        | 2.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 19        | 2.56%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 17        | 2.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 16        | 2.16%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 14        | 1.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 14        | 1.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 13        | 1.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 11        | 1.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 1.48%   |
| AMD 500 Series Chipset SATA Controller                                         | 11        | 1.48%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 10        | 1.35%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 10        | 1.35%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 10        | 1.35%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 10        | 1.35%   |
| Intel SATA Controller [RAID mode]                                              | 9         | 1.21%   |
| Intel Alder Lake-N SATA AHCI Controller                                        | 9         | 1.21%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 9         | 1.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 9         | 1.21%   |
| AMD 400 Series Chipset SATA Controller                                         | 9         | 1.21%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 8         | 1.08%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 8         | 1.08%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 8         | 1.08%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 8         | 1.08%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 8         | 1.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 8         | 1.08%   |
| AMD 600 Series Chipset SATA Controller                                         | 8         | 1.08%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 7         | 0.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 7         | 0.94%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 7         | 0.94%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 7         | 0.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 7         | 0.94%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 7         | 0.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 7         | 0.94%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 6         | 0.81%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 6         | 0.81%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 6         | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 6         | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 303       | 47.27%  |
| NVMe | 211       | 32.92%  |
| IDE  | 65        | 10.14%  |
| RAID | 61        | 9.52%   |
| SAS  | 1         | 0.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 357       | 75.32%  |
| AMD    | 117       | 24.68%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel N100                                  | 9         | 1.89%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 6         | 1.26%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 4         | 0.84%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4         | 0.84%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 4         | 0.84%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4         | 0.84%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 4         | 0.84%   |
| Intel 12th Gen Core i7-12700H               | 4         | 0.84%   |
| Intel 12th Gen Core i5-1240P                | 4         | 0.84%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 4         | 0.84%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4         | 0.84%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 3         | 0.63%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 3         | 0.63%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 3         | 0.63%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3         | 0.63%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 3         | 0.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 3         | 0.63%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 3         | 0.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 0.63%   |
| Intel Core i5-4260U CPU @ 1.40GHz           | 3         | 0.63%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 3         | 0.63%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3         | 0.63%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 3         | 0.63%   |
| Intel 13th Gen Core i9-13900H               | 3         | 0.63%   |
| Intel 13th Gen Core i5-1340P                | 3         | 0.63%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3         | 0.63%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3         | 0.63%   |
| AMD Ryzen 7 7800X3D 8-Core Processor        | 3         | 0.63%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 3         | 0.63%   |
| AMD Ryzen 5 7520U with Radeon Graphics      | 3         | 0.63%   |
| AMD Ryzen 5 4500U with Radeon Graphics      | 3         | 0.63%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 2         | 0.42%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 2         | 0.42%   |
| Intel N95                                   | 2         | 0.42%   |
| Intel Genuine CPU T2300 @ 1.66GHz           | 2         | 0.42%   |
| Intel Genuine CPU T2060 @ 1.60GHz           | 2         | 0.42%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 0.42%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 0.42%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2         | 0.42%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 2         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 92        | 19.37%  |
| Other                   | 72        | 15.16%  |
| Intel Core i7           | 72        | 15.16%  |
| AMD Ryzen 7             | 32        | 6.74%   |
| AMD Ryzen 5             | 28        | 5.89%   |
| Intel Core i3           | 25        | 5.26%   |
| Intel Core 2 Duo        | 17        | 3.58%   |
| Intel Celeron           | 15        | 3.16%   |
| AMD Ryzen 9             | 13        | 2.74%   |
| Intel Xeon              | 9         | 1.89%   |
| Intel Genuine           | 9         | 1.89%   |
| Intel Pentium Dual-Core | 8         | 1.68%   |
| Intel Atom              | 8         | 1.68%   |
| Intel Pentium           | 7         | 1.47%   |
| AMD Ryzen 3             | 7         | 1.47%   |
| AMD A8                  | 5         | 1.05%   |
| AMD Phenom II X6        | 4         | 0.84%   |
| Intel Pentium Silver    | 3         | 0.63%   |
| Intel Pentium M         | 3         | 0.63%   |
| Intel Core Duo          | 3         | 0.63%   |
| Intel Core 2 Quad       | 3         | 0.63%   |
| Intel Core 2            | 3         | 0.63%   |
| AMD Ryzen 7 PRO         | 3         | 0.63%   |
| AMD FX                  | 3         | 0.63%   |
| Intel Pentium 4         | 2         | 0.42%   |
| Intel Core i9           | 2         | 0.42%   |
| AMD Sempron             | 2         | 0.42%   |
| AMD Ryzen 5 PRO         | 2         | 0.42%   |
| AMD E2                  | 2         | 0.42%   |
| AMD E                   | 2         | 0.42%   |
| AMD Athlon              | 2         | 0.42%   |
| Intel Pentium Dual      | 1         | 0.21%   |
| Intel Pentium D         | 1         | 0.21%   |
| Intel Core m3           | 1         | 0.21%   |
| Intel Core              | 1         | 0.21%   |
| Intel Celeron M         | 1         | 0.21%   |
| Intel Celeron Dual-Core | 1         | 0.21%   |
| AMD Phenom II X4        | 1         | 0.21%   |
| AMD Phenom II X3        | 1         | 0.21%   |
| AMD GX                  | 1         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 168       | 35.37%  |
| 4      | 154       | 32.42%  |
| 8      | 46        | 9.68%   |
| 6      | 44        | 9.26%   |
| 12     | 20        | 4.21%   |
| 1      | 16        | 3.37%   |
| 14     | 9         | 1.89%   |
| 10     | 8         | 1.68%   |
| 16     | 7         | 1.47%   |
| 24     | 2         | 0.42%   |
| 3      | 1         | 0.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 471       | 99.37%  |
| 2      | 3         | 0.63%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 318       | 67.09%  |
| 1      | 156       | 32.91%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 455       | 95.99%  |
| 32-bit         | 19        | 4.01%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 12.61%  |
| 0x306a9    | 24        | 5.04%   |
| 0x206a7    | 22        | 4.62%   |
| 0x306c3    | 19        | 3.99%   |
| 0x1067a    | 17        | 3.57%   |
| 0x40651    | 14        | 2.94%   |
| 0xb06e0    | 11        | 2.31%   |
| 0x806ec    | 11        | 2.31%   |
| 0x906e9    | 10        | 2.1%    |
| 0x906a3    | 10        | 2.1%    |
| 0x506e3    | 10        | 2.1%    |
| 0x806c1    | 9         | 1.89%   |
| 0x806e9    | 8         | 1.68%   |
| 0x306d4    | 8         | 1.68%   |
| 0x20655    | 8         | 1.68%   |
| 0x806ea    | 7         | 1.47%   |
| 0x08108109 | 7         | 1.47%   |
| 0x6ec      | 6         | 1.26%   |
| 0x0a50000c | 6         | 1.26%   |
| 0xb06a2    | 5         | 1.05%   |
| 0xb0671    | 5         | 1.05%   |
| 0x6fd      | 5         | 1.05%   |
| 0x6e8      | 5         | 1.05%   |
| 0x406e3    | 5         | 1.05%   |
| 0x10676    | 5         | 1.05%   |
| 0x0a20120e | 5         | 1.05%   |
| 0x906ea    | 4         | 0.84%   |
| 0x906c0    | 4         | 0.84%   |
| 0x806d1    | 4         | 0.84%   |
| 0x706e5    | 4         | 0.84%   |
| 0x706a8    | 4         | 0.84%   |
| 0x0a50000f | 4         | 0.84%   |
| 0x0a404102 | 4         | 0.84%   |
| 0x08a00008 | 4         | 0.84%   |
| 0x0810100b | 4         | 0.84%   |
| 0x08001138 | 4         | 0.84%   |
| 0xb06a3    | 3         | 0.63%   |
| 0xa0652    | 3         | 0.63%   |
| 0x906a4    | 3         | 0.63%   |
| 0x6f6      | 3         | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 54        | 11.37%  |
| Haswell          | 40        | 8.42%   |
| Alderlake Hybrid | 37        | 7.79%   |
| Unknown          | 34        | 7.16%   |
| IvyBridge        | 29        | 6.11%   |
| Penryn           | 24        | 5.05%   |
| SandyBridge      | 23        | 4.84%   |
| Zen 3            | 22        | 4.63%   |
| Skylake          | 20        | 4.21%   |
| TigerLake        | 15        | 3.16%   |
| P6               | 15        | 3.16%   |
| Zen+             | 13        | 2.74%   |
| Core             | 13        | 2.74%   |
| Zen 2            | 12        | 2.53%   |
| Gracemont        | 12        | 2.53%   |
| Broadwell        | 12        | 2.53%   |
| Zen              | 11        | 2.32%   |
| Westmere         | 11        | 2.32%   |
| IceLake          | 10        | 2.11%   |
| Silvermont       | 8         | 1.68%   |
| K10              | 8         | 1.68%   |
| CometLake        | 7         | 1.47%   |
| Excavator        | 6         | 1.26%   |
| Piledriver       | 5         | 1.05%   |
| Goldmont plus    | 5         | 1.05%   |
| Bonnell          | 5         | 1.05%   |
| Tremont          | 4         | 0.84%   |
| Puma             | 4         | 0.84%   |
| NetBurst         | 4         | 0.84%   |
| Nehalem          | 3         | 0.63%   |
| Bobcat           | 3         | 0.63%   |
| Jaguar           | 2         | 0.42%   |
| Goldmont         | 2         | 0.42%   |
| Steamroller      | 1         | 0.21%   |
| K8 & K10 hybrid  | 1         | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 284       | 53.28%  |
| AMD    | 135       | 25.33%  |
| Nvidia | 114       | 21.39%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 3.37%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 17        | 3.02%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 2.49%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 13        | 2.31%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 11        | 1.95%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 1.78%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 9         | 1.6%    |
| Intel HD Graphics 620                                                                    | 9         | 1.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 1.6%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 1.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 1.42%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 1.42%   |
| Intel HD Graphics 5500                                                                   | 8         | 1.42%   |
| Intel HD Graphics 530                                                                    | 8         | 1.42%   |
| AMD Rembrandt [Radeon 680M]                                                              | 8         | 1.42%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 1.42%   |
| Intel UHD Graphics 620                                                                   | 7         | 1.24%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 1.24%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 1.24%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 7         | 1.24%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 1.24%   |
| AMD Raphael                                                                              | 7         | 1.24%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 1.07%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 6         | 1.07%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 1.07%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 1.07%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.07%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 6         | 1.07%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 6         | 1.07%   |
| AMD Lucienne                                                                             | 6         | 1.07%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 0.89%   |
| Intel HD Graphics 630                                                                    | 5         | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 0.89%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 0.89%   |
| Intel JasperLake [UHD Graphics]                                                          | 4         | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 0.71%   |
| AMD Phoenix1                                                                             | 4         | 0.71%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                                  | 4         | 0.71%   |
| AMD Mendocino                                                                            | 4         | 0.71%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 206       | 43.37%  |
| 1 x AMD        | 112       | 23.58%  |
| 1 x Nvidia     | 64        | 13.47%  |
| Intel + Nvidia | 44        | 9.26%   |
| 2 x Intel      | 23        | 4.84%   |
| 2 x AMD        | 13        | 2.74%   |
| Intel + AMD    | 7         | 1.47%   |
| AMD + Nvidia   | 4         | 0.84%   |
| 2 x Nvidia     | 2         | 0.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 423       | 89.24%  |
| Proprietary | 46        | 9.7%    |
| Unknown     | 5         | 1.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 265       | 55.79%  |
| 0.01-0.5   | 67        | 14.11%  |
| 1.01-2.0   | 37        | 7.79%   |
| 3.01-4.0   | 27        | 5.68%   |
| 0.51-1.0   | 27        | 5.68%   |
| 7.01-8.0   | 22        | 4.63%   |
| 5.01-6.0   | 13        | 2.74%   |
| 8.01-16.0  | 9         | 1.89%   |
| 2.01-3.0   | 6         | 1.26%   |
| 16.01-24.0 | 2         | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 65        | 12.62%  |
| Samsung Electronics     | 60        | 11.65%  |
| BOE                     | 51        | 9.9%    |
| Chimei Innolux          | 39        | 7.57%   |
| LG Display              | 38        | 7.38%   |
| Goldstar                | 29        | 5.63%   |
| Dell                    | 19        | 3.69%   |
| Hewlett-Packard         | 17        | 3.3%    |
| Apple                   | 16        | 3.11%   |
| AOC                     | 16        | 3.11%   |
| Acer                    | 14        | 2.72%   |
| Philips                 | 12        | 2.33%   |
| Lenovo                  | 11        | 2.14%   |
| Ancor Communications    | 10        | 1.94%   |
| Iiyama                  | 9         | 1.75%   |
| BenQ                    | 9         | 1.75%   |
| ASUSTek Computer        | 8         | 1.55%   |
| Sharp                   | 7         | 1.36%   |
| HUAWEI                  | 7         | 1.36%   |
| Eizo                    | 7         | 1.36%   |
| Chi Mei Optoelectronics | 6         | 1.17%   |
| PANDA                   | 5         | 0.97%   |
| LG Philips              | 5         | 0.97%   |
| Panasonic               | 4         | 0.78%   |
| MSI                     | 3         | 0.58%   |
| Mi                      | 3         | 0.58%   |
| HannStar                | 3         | 0.58%   |
| CSO                     | 3         | 0.58%   |
| ViewSonic               | 2         | 0.39%   |
| Toshiba                 | 2         | 0.39%   |
| STA                     | 2         | 0.39%   |
| Sceptre                 | 2         | 0.39%   |
| NEC Computers           | 2         | 0.39%   |
| InfoVision              | 2         | 0.39%   |
| Huion                   | 2         | 0.39%   |
| Hitachi                 | 2         | 0.39%   |
| GreenWood               | 2         | 0.39%   |
| Belinea                 | 2         | 0.39%   |
| Unknown                 | 1         | 0.19%   |
| Tech Concepts           | 1         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| HUAWEI ZQE-CBA HWV6A25 3440x1440 797x334mm 34.0-inch                 | 7         | 1.34%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 4         | 0.76%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch     | 4         | 0.76%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch    | 3         | 0.57%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch          | 3         | 0.57%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 3         | 0.57%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 3         | 0.57%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 3         | 0.57%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch              | 2         | 0.38%   |
| Samsung Electronics SyncMaster SAM0456 1360x768 410x230mm 18.5-inch  | 2         | 0.38%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch    | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch | 2         | 0.38%   |
| Philips 247E4 PHLC0C0 1920x1080 521x293mm 23.5-inch                  | 2         | 0.38%   |
| PANDA LCD Monitor NCP0061 2560x1600 302x189mm 14.0-inch              | 2         | 0.38%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                     | 2         | 0.38%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch          | 2         | 0.38%   |
| Lenovo LEN G32qc-10 LEN66A2 2560x1440 698x392mm 31.5-inch            | 2         | 0.38%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 2         | 0.38%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                               | 2         | 0.38%   |
| Eizo S2202W ENC1975 1680x1050 480x300mm 22.3-inch                    | 2         | 0.38%   |
| Dell U2720QM DEL41BC 3840x2160 597x336mm 27.0-inch                   | 2         | 0.38%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                    | 2         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 2         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch     | 2         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch      | 2         | 0.38%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 2         | 0.38%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 2         | 0.38%   |
| BOE LCD Monitor BOE092F 2520x1680 338x226mm 16.0-inch                | 2         | 0.38%   |
| BOE LCD Monitor BOE0903 1920x1080 344x194mm 15.5-inch                | 2         | 0.38%   |
| BOE LCD Monitor BOE0897 1366x768 344x194mm 15.5-inch                 | 2         | 0.38%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                | 2         | 0.38%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                 | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch        | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch       | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO229E 1600x900 382x214mm 17.2-inch        | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch       | 2         | 0.38%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 2         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 194       | 38.96%  |
| 1366x768 (WXGA)    | 85        | 17.07%  |
| 3840x2160 (4K)     | 53        | 10.64%  |
| 2560x1440 (QHD)    | 19        | 3.82%   |
| 1920x1200 (WUXGA)  | 19        | 3.82%   |
| 1600x900 (HD+)     | 18        | 3.61%   |
| 1680x1050 (WSXGA+) | 17        | 3.41%   |
| 1280x800 (WXGA)    | 16        | 3.21%   |
| 1440x900 (WXGA+)   | 12        | 2.41%   |
| 1280x1024 (SXGA)   | 8         | 1.61%   |
| 3440x1440          | 7         | 1.41%   |
| 2560x1600          | 7         | 1.41%   |
| 1360x768           | 5         | 1%      |
| 3840x1080          | 4         | 0.8%    |
| 2560x1080          | 4         | 0.8%    |
| 1024x768 (XGA)     | 4         | 0.8%    |
| Unknown            | 4         | 0.8%    |
| 2880x1800          | 2         | 0.4%    |
| 2520x1680          | 2         | 0.4%    |
| 2256x1504          | 2         | 0.4%    |
| 2160x1440          | 2         | 0.4%    |
| 1920x1280          | 2         | 0.4%    |
| 1024x600           | 2         | 0.4%    |
| 9600x2160          | 1         | 0.2%    |
| 3840x2400          | 1         | 0.2%    |
| 2880x1620          | 1         | 0.2%    |
| 2240x1400          | 1         | 0.2%    |
| 2160x1350          | 1         | 0.2%    |
| 1920x540           | 1         | 0.2%    |
| 1680x945           | 1         | 0.2%    |
| 1600x2560          | 1         | 0.2%    |
| 1400x1050          | 1         | 0.2%    |
| 1280x720 (HD)      | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 135       | 26.26%  |
| 27      | 39        | 7.59%   |
| 14      | 39        | 7.59%   |
| 24      | 37        | 7.2%    |
| 13      | 37        | 7.2%    |
| 23      | 29        | 5.64%   |
| 17      | 23        | 4.47%   |
| 31      | 20        | 3.89%   |
| 21      | 19        | 3.7%    |
| 34      | 16        | 3.11%   |
| Unknown | 14        | 2.72%   |
| 22      | 13        | 2.53%   |
| 19      | 13        | 2.53%   |
| 16      | 12        | 2.33%   |
| 18      | 10        | 1.95%   |
| 12      | 10        | 1.95%   |
| 11      | 8         | 1.56%   |
| 20      | 6         | 1.17%   |
| 84      | 5         | 0.97%   |
| 32      | 5         | 0.97%   |
| 54      | 4         | 0.78%   |
| 72      | 3         | 0.58%   |
| 26      | 3         | 0.58%   |
| 86      | 2         | 0.39%   |
| 42      | 2         | 0.39%   |
| 10      | 2         | 0.39%   |
| 95      | 1         | 0.19%   |
| 57      | 1         | 0.19%   |
| 48      | 1         | 0.19%   |
| 46      | 1         | 0.19%   |
| 40      | 1         | 0.19%   |
| 38      | 1         | 0.19%   |
| 35      | 1         | 0.19%   |
| 8       | 1         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 198       | 38.9%   |
| 501-600     | 99        | 19.45%  |
| 401-500     | 53        | 10.41%  |
| 201-300     | 44        | 8.64%   |
| 351-400     | 30        | 5.89%   |
| 601-700     | 26        | 5.11%   |
| 701-800     | 21        | 4.13%   |
| Unknown     | 14        | 2.75%   |
| 1501-2000   | 10        | 1.96%   |
| 1001-1500   | 7         | 1.38%   |
| 801-900     | 4         | 0.79%   |
| 901-1000    | 2         | 0.39%   |
| 101-200     | 1         | 0.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 351       | 72.82%  |
| 16/10   | 75        | 15.56%  |
| 21/9    | 17        | 3.53%   |
| Unknown | 12        | 2.49%   |
| 5/4     | 9         | 1.87%   |
| 3/2     | 9         | 1.87%   |
| 4/3     | 6         | 1.24%   |
| 0.56    | 2         | 0.41%   |
| 32/9    | 1         | 0.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 133       | 26.18%  |
| 201-250        | 72        | 14.17%  |
| 81-90          | 61        | 12.01%  |
| 351-500        | 42        | 8.27%   |
| 301-350        | 40        | 7.87%   |
| 151-200        | 27        | 5.31%   |
| 121-130        | 18        | 3.54%   |
| More than 1000 | 16        | 3.15%   |
| 251-300        | 15        | 2.95%   |
| Unknown        | 14        | 2.76%   |
| 71-80          | 13        | 2.56%   |
| 111-120        | 12        | 2.36%   |
| 141-150        | 11        | 2.17%   |
| 61-70          | 10        | 1.97%   |
| 51-60          | 9         | 1.77%   |
| 501-1000       | 6         | 1.18%   |
| 91-100         | 4         | 0.79%   |
| 131-140        | 3         | 0.59%   |
| 41-50          | 1         | 0.2%    |
| 1-40           | 1         | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 174       | 35.01%  |
| 121-160       | 133       | 26.76%  |
| 101-120       | 126       | 25.35%  |
| 161-240       | 38        | 7.65%   |
| Unknown       | 14        | 2.82%   |
| 1-50          | 8         | 1.61%   |
| More than 240 | 4         | 0.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 416       | 87.39%  |
| 2     | 51        | 10.71%  |
| 3     | 4         | 0.84%   |
| 0     | 3         | 0.63%   |
| 4     | 2         | 0.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 258       | 36.49%  |
| Intel                                 | 217       | 30.69%  |
| Qualcomm Atheros                      | 59        | 8.35%   |
| Broadcom                              | 38        | 5.37%   |
| MediaTek                              | 27        | 3.82%   |
| Broadcom Limited                      | 16        | 2.26%   |
| TP-Link                               | 13        | 1.84%   |
| Marvell Technology Group              | 11        | 1.56%   |
| Ralink                                | 8         | 1.13%   |
| ASIX Electronics                      | 8         | 1.13%   |
| Ralink Technology                     | 7         | 0.99%   |
| Samsung Electronics                   | 5         | 0.71%   |
| Qualcomm                              | 4         | 0.57%   |
| Nvidia                                | 4         | 0.57%   |
| JMicron Technology                    | 3         | 0.42%   |
| VIA Technologies                      | 2         | 0.28%   |
| Sierra Wireless                       | 2         | 0.28%   |
| QinHeng Electronics                   | 2         | 0.28%   |
| NetGear                               | 2         | 0.28%   |
| Microsoft                             | 2         | 0.28%   |
| Mercucys                              | 2         | 0.28%   |
| Ericsson Business Mobile Networks     | 2         | 0.28%   |
| Edimax Technology                     | 2         | 0.28%   |
| D-Link                                | 2         | 0.28%   |
| Xiaomi                                | 1         | 0.14%   |
| U-Blox                                | 1         | 0.14%   |
| Lenovo                                | 1         | 0.14%   |
| Hewlett-Packard                       | 1         | 0.14%   |
| DisplayLink                           | 1         | 0.14%   |
| Dell                                  | 1         | 0.14%   |
| D-Link System                         | 1         | 0.14%   |
| Cisco Aironet Wireless Communications | 1         | 0.14%   |
| AVM                                   | 1         | 0.14%   |
| Aquantia                              | 1         | 0.14%   |
| AMD                                   | 1         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 156       | 18.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 29        | 3.39%   |
| Realtek RTL8125 2.5GbE Controller                                      | 24        | 2.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 21        | 2.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 19        | 2.22%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 16        | 1.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 13        | 1.52%   |
| Intel Wi-Fi 6 AX200                                                    | 13        | 1.52%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 10        | 1.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 10        | 1.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 10        | 1.17%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 10        | 1.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 9         | 1.05%   |
| Intel Wireless 8265 / 8275                                             | 9         | 1.05%   |
| Intel Wireless 7265                                                    | 9         | 1.05%   |
| Intel Wireless 7260                                                    | 9         | 1.05%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 9         | 1.05%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                      | 8         | 0.93%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 8         | 0.93%   |
| Intel Ethernet Connection I217-LM                                      | 8         | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 8         | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 7         | 0.82%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 7         | 0.82%   |
| ASIX AX88179 Gigabit Ethernet                                          | 7         | 0.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 6         | 0.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 6         | 0.7%    |
| Intel Wi-Fi 6 AX201                                                    | 6         | 0.7%    |
| Intel I211 Gigabit Network Connection                                  | 6         | 0.7%    |
| Intel Ethernet Controller I225-V                                       | 6         | 0.7%    |
| Intel Ethernet Connection (2) I219-V                                   | 6         | 0.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 6         | 0.7%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 6         | 0.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 5         | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 5         | 0.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5         | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 5         | 0.58%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 5         | 0.58%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 0.58%   |
| Intel CNVi: Wi-Fi                                                      | 5         | 0.58%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 5         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 166       | 40.49%  |
| Realtek Semiconductor                 | 84        | 20.49%  |
| Qualcomm Atheros                      | 47        | 11.46%  |
| Broadcom                              | 27        | 6.59%   |
| MediaTek                              | 24        | 5.85%   |
| TP-Link                               | 13        | 3.17%   |
| Broadcom Limited                      | 13        | 3.17%   |
| Ralink                                | 8         | 1.95%   |
| Ralink Technology                     | 7         | 1.71%   |
| Qualcomm                              | 4         | 0.98%   |
| Sierra Wireless                       | 2         | 0.49%   |
| NetGear                               | 2         | 0.49%   |
| Microsoft                             | 2         | 0.49%   |
| Mercucys                              | 2         | 0.49%   |
| Edimax Technology                     | 2         | 0.49%   |
| D-Link                                | 2         | 0.49%   |
| Hewlett-Packard                       | 1         | 0.24%   |
| Dell                                  | 1         | 0.24%   |
| D-Link System                         | 1         | 0.24%   |
| Cisco Aironet Wireless Communications | 1         | 0.24%   |
| AVM                                   | 1         | 0.24%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 21        | 5.06%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 16        | 3.86%   |
| Intel Wi-Fi 6 AX200                                                  | 13        | 3.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 10        | 2.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 10        | 2.41%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 10        | 2.41%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 9         | 2.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 9         | 2.17%   |
| Intel Wireless 8265 / 8275                                           | 9         | 2.17%   |
| Intel Wireless 7265                                                  | 9         | 2.17%   |
| Intel Wireless 7260                                                  | 9         | 2.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 9         | 2.17%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                    | 8         | 1.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 8         | 1.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 7         | 1.69%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 7         | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 6         | 1.45%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 6         | 1.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 6         | 1.45%   |
| Intel Wi-Fi 6 AX201                                                  | 6         | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 6         | 1.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 5         | 1.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 5         | 1.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 5         | 1.2%    |
| Intel Raptor Lake-S PCH CNVi WiFi                                    | 5         | 1.2%    |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 5         | 1.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 5         | 1.2%    |
| TP-Link RTL8812AU Archer T4U 802.11ac                                | 4         | 0.96%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 4         | 0.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 4         | 0.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 4         | 0.96%   |
| Intel Wireless 8260                                                  | 4         | 0.96%   |
| Intel Wireless 3165                                                  | 4         | 0.96%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 4         | 0.96%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection              | 4         | 0.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 4         | 0.96%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 4         | 0.96%   |
| Intel Centrino Ultimate-N 6300                                       | 4         | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 4         | 0.96%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 4         | 0.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 226       | 53.55%  |
| Intel                    | 119       | 28.2%   |
| Broadcom                 | 20        | 4.74%   |
| Qualcomm Atheros         | 16        | 3.79%   |
| Marvell Technology Group | 11        | 2.61%   |
| ASIX Electronics         | 8         | 1.9%    |
| Nvidia                   | 4         | 0.95%   |
| Samsung Electronics      | 3         | 0.71%   |
| MediaTek                 | 3         | 0.71%   |
| JMicron Technology       | 3         | 0.71%   |
| Broadcom Limited         | 3         | 0.71%   |
| VIA Technologies         | 2         | 0.47%   |
| Xiaomi                   | 1         | 0.24%   |
| Lenovo                   | 1         | 0.24%   |
| DisplayLink              | 1         | 0.24%   |
| Aquantia                 | 1         | 0.24%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 156       | 36.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 29        | 6.71%   |
| Realtek RTL8125 2.5GbE Controller                                      | 24        | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 19        | 4.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 13        | 3.01%   |
| Intel Ethernet Connection I217-LM                                      | 8         | 1.85%   |
| ASIX AX88179 Gigabit Ethernet                                          | 7         | 1.62%   |
| Intel I211 Gigabit Network Connection                                  | 6         | 1.39%   |
| Intel Ethernet Controller I225-V                                       | 6         | 1.39%   |
| Intel Ethernet Connection (2) I219-V                                   | 6         | 1.39%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 6         | 1.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 5         | 1.16%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 1.16%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 0.93%   |
| Intel Ethernet Controller I226-V                                       | 4         | 0.93%   |
| Intel CNVi: Wi-Fi                                                      | 4         | 0.93%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.69%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R]     | 3         | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3         | 0.69%   |
| Nvidia MCP79 Ethernet                                                  | 3         | 0.69%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 3         | 0.69%   |
| Intel Ethernet Connection (7) I219-V                                   | 3         | 0.69%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 0.69%   |
| Intel Ethernet Connection (5) I219-LM                                  | 3         | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 0.69%   |
| Intel Ethernet Connection (10) I219-V                                  | 3         | 0.69%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 0.69%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 0.69%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 0.46%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 0.46%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 2         | 0.46%   |
| Intel PRO/100 VE Network Connection                                    | 2         | 0.46%   |
| Intel I210 Gigabit Network Connection                                  | 2         | 0.46%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.46%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.46%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 0.46%   |
| Intel Ethernet Connection (2) I218-V                                   | 2         | 0.46%   |
| Intel Ethernet Connection (16) I219-LM                                 | 2         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 401       | 50.44%  |
| WiFi     | 385       | 48.43%  |
| Modem    | 9         | 1.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 276       | 55.2%   |
| Ethernet | 224       | 44.8%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 261       | 54.95%  |
| 1     | 197       | 41.47%  |
| 3     | 15        | 3.16%   |
| 0     | 2         | 0.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 332       | 68.74%  |
| Yes  | 151       | 31.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 134       | 40.61%  |
| Realtek Semiconductor           | 42        | 12.73%  |
| IMC Networks                    | 31        | 9.39%   |
| Apple                           | 21        | 6.36%   |
| Qualcomm Atheros Communications | 17        | 5.15%   |
| Broadcom                        | 17        | 5.15%   |
| Cambridge Silicon Radio         | 16        | 4.85%   |
| MediaTek                        | 7         | 2.12%   |
| Lite-On Technology              | 6         | 1.82%   |
| Foxconn / Hon Hai               | 6         | 1.82%   |
| Hewlett-Packard                 | 5         | 1.52%   |
| Realtek                         | 4         | 1.21%   |
| Ralink                          | 4         | 1.21%   |
| ASUSTek Computer                | 4         | 1.21%   |
| Dell                            | 3         | 0.91%   |
| USI                             | 2         | 0.61%   |
| TP-Link                         | 2         | 0.61%   |
| Toshiba                         | 2         | 0.61%   |
| Integrated System Solution      | 2         | 0.61%   |
| Askey Computer                  | 2         | 0.61%   |
| Logitech                        | 1         | 0.3%    |
| D-Link                          | 1         | 0.3%    |
| Unknown                         | 1         | 0.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 37        | 11.21%  |
| Realtek Bluetooth Radio                             | 34        | 10.3%   |
| Intel AX211 Bluetooth                               | 24        | 7.27%   |
| Intel AX201 Bluetooth                               | 24        | 7.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 18        | 5.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 16        | 4.85%   |
| IMC Networks Wireless_Device                        | 14        | 4.24%   |
| Intel AX200 Bluetooth                               | 13        | 3.94%   |
| IMC Networks Bluetooth Radio                        | 10        | 3.03%   |
| Intel AX210 Bluetooth                               | 9         | 2.73%   |
| Apple Bluetooth Host Controller                     | 9         | 2.73%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 2.42%   |
| MediaTek Wireless_Device                            | 7         | 2.12%   |
| Apple Bluetooth USB Host Controller                 | 7         | 2.12%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 1.82%   |
| IMC Networks Bluetooth Device                       | 5         | 1.52%   |
| Realtek Bluetooth Radio                             | 4         | 1.21%   |
| Ralink RT3290 Bluetooth                             | 4         | 1.21%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 1.21%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.21%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 1.21%   |
| Apple Bluetooth HCI                                 | 4         | 1.21%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.91%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 0.91%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 3         | 0.91%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 3         | 0.91%   |
| USI Bluetooth Device                                | 2         | 0.61%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 2         | 0.61%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.61%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 0.61%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.61%   |
| Integrated System Solution Bluetooth Device         | 2         | 0.61%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.61%   |
| Dell Wireless 350 Bluetooth                         | 2         | 0.61%   |
| ASUS ASUS USB-BT500                                 | 2         | 0.61%   |
| Askey Bluetooth Device                              | 2         | 0.61%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.3%    |
| Toshiba BCM43142A0                                  | 1         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 343       | 53.26%  |
| AMD                                          | 140       | 21.74%  |
| Nvidia                                       | 86        | 13.35%  |
| C-Media Electronics                          | 11        | 1.71%   |
| Creative Technology                          | 6         | 0.93%   |
| Creative Labs                                | 5         | 0.78%   |
| Texas Instruments                            | 4         | 0.62%   |
| Micro Star International                     | 4         | 0.62%   |
| Logitech                                     | 4         | 0.62%   |
| JMTek                                        | 4         | 0.62%   |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 0.47%   |
| GN Netcom                                    | 3         | 0.47%   |
| Generalplus Technology                       | 3         | 0.47%   |
| Fujitsu                                      | 3         | 0.47%   |
| VIA Technologies                             | 2         | 0.31%   |
| Hewlett-Packard                              | 2         | 0.31%   |
| ZOOM                                         | 1         | 0.16%   |
| Walmart                                      | 1         | 0.16%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.16%   |
| Samson Technologies                          | 1         | 0.16%   |
| Razer USA                                    | 1         | 0.16%   |
| M-Audio                                      | 1         | 0.16%   |
| Kingston Technology                          | 1         | 0.16%   |
| Jieli Technology                             | 1         | 0.16%   |
| JBL                                          | 1         | 0.16%   |
| Guillemot                                    | 1         | 0.16%   |
| Focusrite-Novation                           | 1         | 0.16%   |
| DSEA A/S                                     | 1         | 0.16%   |
| Bluetrum                                     | 1         | 0.16%   |
| Blue Microphones                             | 1         | 0.16%   |
| Avnera                                       | 1         | 0.16%   |
| ASUSTek Computer                             | 1         | 0.16%   |
| Astro Gaming                                 | 1         | 0.16%   |
| ASRock                                       | 1         | 0.16%   |
| Apple                                        | 1         | 0.16%   |
| Altec Lansing Technologies                   | 1         | 0.16%   |
| Unknown                                      | 1         | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 65        | 8.29%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 30        | 3.83%   |
| Intel Sunrise Point-LP HD Audio                                            | 25        | 3.19%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 25        | 3.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 24        | 3.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 24        | 3.06%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 23        | 2.93%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 20        | 2.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 20        | 2.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 17        | 2.17%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 15        | 1.91%   |
| Intel Haswell-ULT HD Audio Controller                                      | 14        | 1.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 14        | 1.79%   |
| Intel 8 Series HD Audio Controller                                         | 14        | 1.79%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 14        | 1.79%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                    | 13        | 1.66%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 13        | 1.66%   |
| AMD Starship/Matisse HD Audio Controller                                   | 13        | 1.66%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 12        | 1.53%   |
| Intel Broadwell-U Audio Controller                                         | 11        | 1.4%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 11        | 1.4%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 10        | 1.28%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 10        | 1.28%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 1.15%   |
| Intel Comet Lake PCH-LP cAVS                                               | 9         | 1.15%   |
| Intel Cannon Lake PCH cAVS                                                 | 9         | 1.15%   |
| Intel 200 Series PCH HD Audio                                              | 9         | 1.15%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 9         | 1.15%   |
| AMD Kabini HDMI/DP Audio                                                   | 9         | 1.15%   |
| AMD FCH Azalia Controller                                                  | 9         | 1.15%   |
| Nvidia GF108 High Definition Audio Controller                              | 8         | 1.02%   |
| Intel Raptor Lake High Definition Audio Controller                         | 7         | 0.89%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 7         | 0.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7         | 0.89%   |
| Nvidia GP106 High Definition Audio Controller                              | 6         | 0.77%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6         | 0.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 0.77%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 6         | 0.77%   |
| Nvidia GP104 High Definition Audio Controller                              | 5         | 0.64%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 85        | 22.73%  |
| SK hynix                     | 52        | 13.9%   |
| Unknown                      | 43        | 11.5%   |
| Kingston                     | 41        | 10.96%  |
| Micron Technology            | 37        | 9.89%   |
| G.Skill                      | 20        | 5.35%   |
| Crucial                      | 19        | 5.08%   |
| Corsair                      | 19        | 5.08%   |
| Unknown                      | 9         | 2.41%   |
| A-DATA Technology            | 8         | 2.14%   |
| Elpida                       | 6         | 1.6%    |
| Team                         | 5         | 1.34%   |
| Ramaxel Technology           | 3         | 0.8%    |
| Patriot                      | 3         | 0.8%    |
| Nanya Technology             | 3         | 0.8%    |
| Silicon Power                | 2         | 0.53%   |
| PNY                          | 2         | 0.53%   |
| Avant                        | 2         | 0.53%   |
| V-Color                      | 1         | 0.27%   |
| Unknown (ABCD)               | 1         | 0.27%   |
| Unknown (0x0E9D)             | 1         | 0.27%   |
| Unknown (0x0CC7)             | 1         | 0.27%   |
| Timetec                      | 1         | 0.27%   |
| Super Talent                 | 1         | 0.27%   |
| Smart                        | 1         | 0.27%   |
| Shenzhen Longsys             | 1         | 0.27%   |
| Qimonda                      | 1         | 0.27%   |
| Patriot Memory (PDP Systems) | 1         | 0.27%   |
| Mushkin                      | 1         | 0.27%   |
| Goldkey                      | 1         | 0.27%   |
| GeIL                         | 1         | 0.27%   |
| ASint Technology             | 1         | 0.27%   |
| 48spaces                     | 1         | 0.27%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 9         | 2.18%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 6         | 1.46%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 5         | 1.21%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.21%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 5         | 1.21%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 4         | 0.97%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                       | 4         | 0.97%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.97%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.73%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 3         | 0.73%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.73%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.73%   |
| Micron RAM MT62F1G32D4DR-031 2GB Row Of Chips LPDDR5 6400MT/s    | 3         | 0.73%   |
| Crucial RAM CT16G4SFRA32A.C16FT 16GB SODIMM DDR4 3200MT/s        | 3         | 0.73%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 3         | 0.73%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 2         | 0.49%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                       | 2         | 0.49%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                             | 2         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                       | 2         | 0.49%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                             | 2         | 0.49%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.49%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 2         | 0.49%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.49%   |
| SK hynix RAM HMT425S6CFR6C-PB 2GB SODIMM 1600MT/s                | 2         | 0.49%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.49%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.49%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB DIMM LPDDR5 6400MT/s         | 2         | 0.49%   |
| SK hynix RAM H9JCNNNBK3MLYR-N6E 1GB Row Of Chips LPDDR5 6400MT/s | 2         | 0.49%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 4199MT/s                 | 2         | 0.49%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.49%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.49%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.49%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.49%   |
| Samsung RAM M471A2G44BM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.49%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.49%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 0.49%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.49%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 0.49%   |
| Micron RAM Module 4GB Row Of Chips LPDDR5 6400MT/s               | 2         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 141       | 41.96%  |
| DDR3    | 89        | 26.49%  |
| DDR2    | 27        | 8.04%   |
| LPDDR5  | 23        | 6.85%   |
| DDR5    | 17        | 5.06%   |
| SDRAM   | 13        | 3.87%   |
| LPDDR4  | 7         | 2.08%   |
| Unknown | 7         | 2.08%   |
| DDR     | 6         | 1.79%   |
| LPDDR3  | 4         | 1.19%   |
| RAM     | 1         | 0.3%    |
| DRAM    | 1         | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 204       | 61.26%  |
| DIMM         | 94        | 28.23%  |
| Row Of Chips | 31        | 9.31%   |
| Chip         | 3         | 0.9%    |
| Unknown      | 1         | 0.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 114       | 30.89%  |
| 4096  | 92        | 24.93%  |
| 16384 | 58        | 15.72%  |
| 2048  | 54        | 14.63%  |
| 1024  | 24        | 6.5%    |
| 32768 | 17        | 4.61%   |
| 512   | 8         | 2.17%   |
| 49152 | 2         | 0.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 71        | 20.06%  |
| 1600    | 59        | 16.67%  |
| 2667    | 31        | 8.76%   |
| 6400    | 20        | 5.65%   |
| Unknown | 16        | 4.52%   |
| 1333    | 15        | 4.24%   |
| 667     | 15        | 4.24%   |
| 2133    | 13        | 3.67%   |
| 3600    | 12        | 3.39%   |
| 2400    | 10        | 2.82%   |
| 4800    | 8         | 2.26%   |
| 1334    | 8         | 2.26%   |
| 533     | 7         | 1.98%   |
| 5600    | 6         | 1.69%   |
| 1067    | 6         | 1.69%   |
| 1066    | 5         | 1.41%   |
| 3266    | 4         | 1.13%   |
| 2800    | 4         | 1.13%   |
| 2048    | 4         | 1.13%   |
| 1867    | 4         | 1.13%   |
| 800     | 4         | 1.13%   |
| 4267    | 3         | 0.85%   |
| 4199    | 3         | 0.85%   |
| 3733    | 3         | 0.85%   |
| 3400    | 3         | 0.85%   |
| 6000    | 2         | 0.56%   |
| 5500    | 2         | 0.56%   |
| 2666    | 2         | 0.56%   |
| 1866    | 2         | 0.56%   |
| 7467    | 1         | 0.28%   |
| 7400    | 1         | 0.28%   |
| 4266    | 1         | 0.28%   |
| 3500    | 1         | 0.28%   |
| 3466    | 1         | 0.28%   |
| 3066    | 1         | 0.28%   |
| 3000    | 1         | 0.28%   |
| 2934    | 1         | 0.28%   |
| 2000    | 1         | 0.28%   |
| 1800    | 1         | 0.28%   |
| 1639    | 1         | 0.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 7         | 50%     |
| Canon                 | 4         | 28.57%  |
| Seiko Epson           | 2         | 14.29%  |
| Lexmark International | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Seiko Epson ET-2820 Series    | 1         | 7.14%   |
| Seiko Epson ET-1810 Series    | 1         | 7.14%   |
| Lexmark International MX310dn | 1         | 7.14%   |
| HP LaserJet P2015 series      | 1         | 7.14%   |
| HP LaserJet P1005             | 1         | 7.14%   |
| HP HP LaserJet Pro M404-M405  | 1         | 7.14%   |
| HP ENVY 5000 series           | 1         | 7.14%   |
| HP ENVY 4520 series           | 1         | 7.14%   |
| HP DeskJet F4200 series       | 1         | 7.14%   |
| HP DeskJet 4100 series        | 1         | 7.14%   |
| Canon TS9100 series           | 1         | 7.14%   |
| Canon TR4600 series           | 1         | 7.14%   |
| Canon PIXMA MG3500 Series     | 1         | 7.14%   |
| Canon CanoScan LiDE 300       | 1         | 7.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 50%     |
| Seiko Epson CC-570L [Stylus CX3100/CX3200]  | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 61        | 23.11%  |
| IMC Networks                           | 30        | 11.36%  |
| Quanta                                 | 20        | 7.58%   |
| Bison Electronics                      | 17        | 6.44%   |
| Microdia                               | 15        | 5.68%   |
| Sunplus Innovation Technology          | 14        | 5.3%    |
| Logitech                               | 14        | 5.3%    |
| Luxvisions Innotech Limited            | 13        | 4.92%   |
| Apple                                  | 13        | 4.92%   |
| Realtek Semiconductor                  | 12        | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 3.41%   |
| Suyin                                  | 6         | 2.27%   |
| Sonix Technology                       | 5         | 1.89%   |
| Shinetech                              | 5         | 1.89%   |
| MacroSilicon                           | 4         | 1.52%   |
| Syntek                                 | 3         | 1.14%   |
| Ricoh                                  | 3         | 1.14%   |
| Lite-On Technology                     | 3         | 1.14%   |
| Silicon Motion                         | 2         | 0.76%   |
| Shine-optics                           | 2         | 0.76%   |
| Microsoft                              | 2         | 0.76%   |
| Z-Star Microelectronics                | 1         | 0.38%   |
| Web Camera                             | 1         | 0.38%   |
| SunplusIT                              | 1         | 0.38%   |
| Magic Control Technology               | 1         | 0.38%   |
| Lenovo                                 | 1         | 0.38%   |
| KYE Systems (Mouse Systems)            | 1         | 0.38%   |
| Jieli Technology                       | 1         | 0.38%   |
| HYGD-220831-A                          | 1         | 0.38%   |
| globaloptics                           | 1         | 0.38%   |
| Alcor Micro                            | 1         | 0.38%   |
| Acer                                   | 1         | 0.38%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 15        | 5.64%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 14        | 5.26%   |
| Bison Integrated Camera                                 | 8         | 3.01%   |
| Chicony HD WebCam                                       | 7         | 2.63%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 6         | 2.26%   |
| Microdia Integrated_Webcam_HD                           | 5         | 1.88%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 5         | 1.88%   |
| Sonix USB2.0 HD UVC WebCam                              | 4         | 1.5%    |
| Realtek Integrated_Webcam_HD                            | 4         | 1.5%    |
| Quanta HP HD Camera                                     | 4         | 1.5%    |
| Logitech HD Pro Webcam C920                             | 4         | 1.5%    |
| Apple FaceTime HD Camera (Built-in)                     | 4         | 1.5%    |
| Sunplus HD WebCam                                       | 3         | 1.13%   |
| Quanta HP TrueVision HD Camera                          | 3         | 1.13%   |
| Microdia Sonix USB 2.0 Camera                           | 3         | 1.13%   |
| MacroSilicon USB Video                                  | 3         | 1.13%   |
| IMC Networks Integrated Camera                          | 3         | 1.13%   |
| Chicony TOSHIBA Web Camera - HD                         | 3         | 1.13%   |
| Chicony Integrated Camera (1280x720@30)                 | 3         | 1.13%   |
| Chicony HP Truevision HD                                | 3         | 1.13%   |
| Chicony HP HD Camera                                    | 3         | 1.13%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 3         | 1.13%   |
| Apple Built-in iSight                                   | 3         | 1.13%   |
| Syntek Integrated Camera                                | 2         | 0.75%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 2         | 0.75%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 0.75%   |
| Sunplus Integrated_Webcam_FHD                           | 2         | 0.75%   |
| ShineTech USB2.0 HD UVC WebCam                          | 2         | 0.75%   |
| ShineTech HD Camera                                     | 2         | 0.75%   |
| Shine-optics USB2.0 HD UVC WebCam                       | 2         | 0.75%   |
| Quanta ov9734_techfront_camera                          | 2         | 0.75%   |
| Quanta HD User Facing                                   | 2         | 0.75%   |
| Quanta ACER HD User Facing                              | 2         | 0.75%   |
| Luxvisions Innotech Limited Integrated RGB Camera       | 2         | 0.75%   |
| Luxvisions Innotech Limited Integrated Camera           | 2         | 0.75%   |
| Logitech BRIO Ultra HD Webcam                           | 2         | 0.75%   |
| Lite-On Integrated Camera                               | 2         | 0.75%   |
| IMC Networks USB2.0 HD IR UVC WebCam                    | 2         | 0.75%   |
| IMC Networks Integrated Webcam                          | 2         | 0.75%   |
| Chicony USB2.0 VGA UVC WebCam                           | 2         | 0.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 15        | 28.85%  |
| Synaptics                  | 13        | 25%     |
| Shenzhen Goodix Technology | 7         | 13.46%  |
| STMicroelectronics         | 5         | 9.62%   |
| LighTuning Technology      | 4         | 7.69%   |
| Elan Microelectronics      | 4         | 7.69%   |
| Upek                       | 3         | 5.77%   |
| Microsoft                  | 1         | 1.92%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| STMicroelectronics Fingerprint Reader                    | 5         | 9.62%   |
| Shenzhen Goodix  FingerPrint Device                      | 5         | 9.62%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 4         | 7.69%   |
| Validity Sensors VFS495 Fingerprint Reader               | 3         | 5.77%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 3         | 5.77%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 3         | 5.77%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 3         | 5.77%   |
| Validity Sensors VFS451 Fingerprint Reader               | 2         | 3.85%   |
| Synaptics UWP WBDI                                       | 2         | 3.85%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 2         | 3.85%   |
| LighTuning ES603 Swipe Fingerprint Sensor                | 2         | 3.85%   |
| Elan ELAN:ARM-M4                                         | 2         | 3.85%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor        | 1         | 1.92%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 1         | 1.92%   |
| Validity Sensors VFS491                                  | 1         | 1.92%   |
| Validity Sensors VFS Fingerprint sensor                  | 1         | 1.92%   |
| Validity Sensors Swipe Fingerprint Sensor                | 1         | 1.92%   |
| Validity Sensors Fingerprint scanner                     | 1         | 1.92%   |
| Synaptics WBDI                                           | 1         | 1.92%   |
| Synaptics UWP WBDI Device                                | 1         | 1.92%   |
| Synaptics Fingerprint reader [HP G6]                     | 1         | 1.92%   |
| Shenzhen Goodix Fingerprint Reader                       | 1         | 1.92%   |
| Shenzhen Goodix FingerPrint                              | 1         | 1.92%   |
| Microsoft Fingerprint Reader                             | 1         | 1.92%   |
| LighTuning Fingerprint Sensor                            | 1         | 1.92%   |
| LighTuning EgisTec Touch Fingerprint Sensor              | 1         | 1.92%   |
| Elan WBF Fingerprint Sensor                              | 1         | 1.92%   |
| Elan ELAN:Fingerprint                                    | 1         | 1.92%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 7         | 33.33%  |
| Alcor Micro | 6         | 28.57%  |
| Lenovo      | 3         | 14.29%  |
| Upek        | 2         | 9.52%   |
| O2 Micro    | 2         | 9.52%   |
| Swissbit    | 1         | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 28.57%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 14.29%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 9.52%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 9.52%   |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 9.52%   |
| Broadcom 58200                                                               | 2         | 9.52%   |
| Swissbit iShield Key Pro                                                     | 1         | 4.76%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 4.76%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4.76%   |
| Broadcom 5880                                                                | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 330       | 68.32%  |
| 1     | 124       | 25.67%  |
| 2     | 25        | 5.18%   |
| 3     | 4         | 0.83%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 52        | 28.42%  |
| Net/wireless             | 38        | 20.77%  |
| Graphics card            | 36        | 19.67%  |
| Chipcard                 | 20        | 10.93%  |
| Multimedia controller    | 12        | 6.56%   |
| Bluetooth                | 6         | 3.28%   |
| Camera                   | 5         | 2.73%   |
| Communication controller | 3         | 1.64%   |
| Card reader              | 3         | 1.64%   |
| Unassigned class         | 2         | 1.09%   |
| Storage                  | 2         | 1.09%   |
| Tv card                  | 1         | 0.55%   |
| Storage/nvme             | 1         | 0.55%   |
| Sound                    | 1         | 0.55%   |
| Network                  | 1         | 0.55%   |

