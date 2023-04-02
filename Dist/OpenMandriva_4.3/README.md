OpenMandriva 4.3 - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 4.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenMandriva_4.3/Desktop/README.md) and [notebooks](/Dist/OpenMandriva_4.3/Notebook/README.md).

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

Total: 4457

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ZOTAC         | ZBOX-EN1070/1060,EN1070K... | Mini pc     | [5f703bfc7d](https://linux-hardware.org/?probe=5f703bfc7d) | Apr 01, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [96fcc41161](https://linux-hardware.org/?probe=96fcc41161) | Apr 01, 2023 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [f54ccba86f](https://linux-hardware.org/?probe=f54ccba86f) | Apr 01, 2023 |
| HP            | 2AFA                        | Desktop     | [d177838277](https://linux-hardware.org/?probe=d177838277) | Mar 31, 2023 |
| Dell          | XPS M1330                   | Notebook    | [46b9a5cfde](https://linux-hardware.org/?probe=46b9a5cfde) | Mar 31, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [c51f53a733](https://linux-hardware.org/?probe=c51f53a733) | Mar 31, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [fc9a42e387](https://linux-hardware.org/?probe=fc9a42e387) | Mar 31, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [36c0a38885](https://linux-hardware.org/?probe=36c0a38885) | Mar 31, 2023 |
| HP            | Pavilion dv6                | Notebook    | [c91e4d9c5a](https://linux-hardware.org/?probe=c91e4d9c5a) | Mar 30, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [6b9737a62f](https://linux-hardware.org/?probe=6b9737a62f) | Mar 30, 2023 |
| Lenovo        | ThinkPad Edge E530 3259M... | Notebook    | [9aaa97a931](https://linux-hardware.org/?probe=9aaa97a931) | Mar 30, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [a316144991](https://linux-hardware.org/?probe=a316144991) | Mar 29, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [0bc21ff162](https://linux-hardware.org/?probe=0bc21ff162) | Mar 28, 2023 |
| HP            | 3047h                       | Desktop     | [c4f4f0c51d](https://linux-hardware.org/?probe=c4f4f0c51d) | Mar 28, 2023 |
| Gigabyte      | GA-780T-D3L                 | Desktop     | [4f523c6409](https://linux-hardware.org/?probe=4f523c6409) | Mar 28, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [220c640743](https://linux-hardware.org/?probe=220c640743) | Mar 28, 2023 |
| ASUSTek       | PRIME B450M-A II            | All in one  | [fcd01e22d7](https://linux-hardware.org/?probe=fcd01e22d7) | Mar 28, 2023 |
| Dell          | Studio 1558                 | Notebook    | [955946c74d](https://linux-hardware.org/?probe=955946c74d) | Mar 28, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [0901eb1e27](https://linux-hardware.org/?probe=0901eb1e27) | Mar 27, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d6ddfac9d0](https://linux-hardware.org/?probe=d6ddfac9d0) | Mar 27, 2023 |
| HP            | 250 G1                      | Notebook    | [a19b3136b7](https://linux-hardware.org/?probe=a19b3136b7) | Mar 26, 2023 |
| HP            | 8158 A01                    | Mini pc     | [8d1c60fe86](https://linux-hardware.org/?probe=8d1c60fe86) | Mar 26, 2023 |
| Medion        | Akoya E6416                 | Notebook    | [bb2e759014](https://linux-hardware.org/?probe=bb2e759014) | Mar 26, 2023 |
| ASUSTek       | P8H77-M                     | Desktop     | [6fc56d2339](https://linux-hardware.org/?probe=6fc56d2339) | Mar 25, 2023 |
| MSI           | A520M PRO                   | Desktop     | [c27ea21be5](https://linux-hardware.org/?probe=c27ea21be5) | Mar 25, 2023 |
| Acer          | Aspire ES1-411              | Notebook    | [1a4caa9a83](https://linux-hardware.org/?probe=1a4caa9a83) | Mar 24, 2023 |
| HP            | 86F3 00100                  | All in one  | [4cf13e2cd3](https://linux-hardware.org/?probe=4cf13e2cd3) | Mar 24, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [178936b7f4](https://linux-hardware.org/?probe=178936b7f4) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [5c811e496f](https://linux-hardware.org/?probe=5c811e496f) | Mar 24, 2023 |
| Lenovo        | SDK0E50519 WIN              | Desktop     | [2fb6bb5874](https://linux-hardware.org/?probe=2fb6bb5874) | Mar 24, 2023 |
| ASUSTek       | M4N98TD EVO                 | Desktop     | [9cb4b84924](https://linux-hardware.org/?probe=9cb4b84924) | Mar 24, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [93bc601af0](https://linux-hardware.org/?probe=93bc601af0) | Mar 23, 2023 |
| MSI           | MS-7255                     | Desktop     | [7322068101](https://linux-hardware.org/?probe=7322068101) | Mar 23, 2023 |
| Toshiba       | T20                         | Notebook    | [a0757b47d7](https://linux-hardware.org/?probe=a0757b47d7) | Mar 22, 2023 |
| Acer          | TravelMate 5744             | Notebook    | [3ad8bf7639](https://linux-hardware.org/?probe=3ad8bf7639) | Mar 22, 2023 |
| Gigabyte      | P43-ES3G                    | Desktop     | [60a7dc4c2e](https://linux-hardware.org/?probe=60a7dc4c2e) | Mar 20, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [db3e17d5f1](https://linux-hardware.org/?probe=db3e17d5f1) | Mar 20, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9ee81ffe32](https://linux-hardware.org/?probe=9ee81ffe32) | Mar 20, 2023 |
| ASRock        | 970A-G                      | Desktop     | [52b0aa69ba](https://linux-hardware.org/?probe=52b0aa69ba) | Mar 20, 2023 |
| HP            | 18E7                        | Desktop     | [9e4b5010d8](https://linux-hardware.org/?probe=9e4b5010d8) | Mar 20, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [a3cee7c278](https://linux-hardware.org/?probe=a3cee7c278) | Mar 19, 2023 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [0daa99f732](https://linux-hardware.org/?probe=0daa99f732) | Mar 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [77b7fd07a4](https://linux-hardware.org/?probe=77b7fd07a4) | Mar 19, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [b637fa75c8](https://linux-hardware.org/?probe=b637fa75c8) | Mar 18, 2023 |
| Lenovo        | ThinkPad P50 20EQS1MY00     | Notebook    | [beeb327f26](https://linux-hardware.org/?probe=beeb327f26) | Mar 18, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [e90a87f6f2](https://linux-hardware.org/?probe=e90a87f6f2) | Mar 18, 2023 |
| MSI           | GP60 2OD                    | Notebook    | [a3ffd8113f](https://linux-hardware.org/?probe=a3ffd8113f) | Mar 18, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [19fd2af680](https://linux-hardware.org/?probe=19fd2af680) | Mar 18, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [2a1291ac22](https://linux-hardware.org/?probe=2a1291ac22) | Mar 18, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [39d6b256fa](https://linux-hardware.org/?probe=39d6b256fa) | Mar 18, 2023 |
| MSI           | H55M-P31                    | Desktop     | [e95e62df99](https://linux-hardware.org/?probe=e95e62df99) | Mar 18, 2023 |
| Notebook      | N8xxEP6                     | Notebook    | [a4bd2c22eb](https://linux-hardware.org/?probe=a4bd2c22eb) | Mar 18, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9c24401930](https://linux-hardware.org/?probe=9c24401930) | Mar 18, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [2d7a146140](https://linux-hardware.org/?probe=2d7a146140) | Mar 18, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [fce879befb](https://linux-hardware.org/?probe=fce879befb) | Mar 18, 2023 |
| Medion        | H81H3-EM2 H81EM2W08.217     | Desktop     | [1e1a430355](https://linux-hardware.org/?probe=1e1a430355) | Mar 17, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [c640b09a8b](https://linux-hardware.org/?probe=c640b09a8b) | Mar 17, 2023 |
| Dell          | Latitude E7440              | Notebook    | [8a6e751b61](https://linux-hardware.org/?probe=8a6e751b61) | Mar 16, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [7ab2e7b0ab](https://linux-hardware.org/?probe=7ab2e7b0ab) | Mar 16, 2023 |
| ASUSTek       | CG5290                      | Desktop     | [e0ab58dbfe](https://linux-hardware.org/?probe=e0ab58dbfe) | Mar 16, 2023 |
| ASUSTek       | VC62B                       | Desktop     | [9bf2d226a8](https://linux-hardware.org/?probe=9bf2d226a8) | Mar 15, 2023 |
| MSI           | H61M-P20                    | Desktop     | [8129a4f5a4](https://linux-hardware.org/?probe=8129a4f5a4) | Mar 15, 2023 |
| Dell          | Latitude E7240              | Notebook    | [7fbe857344](https://linux-hardware.org/?probe=7fbe857344) | Mar 14, 2023 |
| HP            | 245 G6 Notebook PC          | Notebook    | [8ff2a816b5](https://linux-hardware.org/?probe=8ff2a816b5) | Mar 13, 2023 |
| ASRock        | G31M-S                      | Desktop     | [7672cc15a2](https://linux-hardware.org/?probe=7672cc15a2) | Mar 13, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [9509c77e2b](https://linux-hardware.org/?probe=9509c77e2b) | Mar 13, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [7f3525f6ef](https://linux-hardware.org/?probe=7f3525f6ef) | Mar 12, 2023 |
| Gigabyte      | B85M-D3H-A                  | Desktop     | [4265744c52](https://linux-hardware.org/?probe=4265744c52) | Mar 12, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [4247bd6835](https://linux-hardware.org/?probe=4247bd6835) | Mar 12, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [a45ebd1b85](https://linux-hardware.org/?probe=a45ebd1b85) | Mar 12, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [757a62eff0](https://linux-hardware.org/?probe=757a62eff0) | Mar 11, 2023 |
| Pegatron      | 2AC2                        | Desktop     | [a6084e8904](https://linux-hardware.org/?probe=a6084e8904) | Mar 11, 2023 |
| Toshiba       | All In One PC MP            | All in one  | [2a3a0b15f8](https://linux-hardware.org/?probe=2a3a0b15f8) | Mar 11, 2023 |
| ASUSTek       | P7P55D DELUXE               | Desktop     | [d2b402f3c0](https://linux-hardware.org/?probe=d2b402f3c0) | Mar 11, 2023 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [1d2e721898](https://linux-hardware.org/?probe=1d2e721898) | Mar 10, 2023 |
| HP            | 0AA0h                       | Desktop     | [f86f0bc187](https://linux-hardware.org/?probe=f86f0bc187) | Mar 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [bf4c797c87](https://linux-hardware.org/?probe=bf4c797c87) | Mar 10, 2023 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [b8dffd9bd3](https://linux-hardware.org/?probe=b8dffd9bd3) | Mar 10, 2023 |
| Dell          | Vostro 1310                 | Notebook    | [a5677d37dc](https://linux-hardware.org/?probe=a5677d37dc) | Mar 09, 2023 |
| ASRock        | H61M-ITX                    | Desktop     | [ab7e81c6ca](https://linux-hardware.org/?probe=ab7e81c6ca) | Mar 09, 2023 |
| HP            | ENVY 6                      | Notebook    | [4873f7b85f](https://linux-hardware.org/?probe=4873f7b85f) | Mar 08, 2023 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | Desktop     | [b1a69ac03b](https://linux-hardware.org/?probe=b1a69ac03b) | Mar 08, 2023 |
| ECS           | MCP61PM-GM                  | Desktop     | [ac561937e3](https://linux-hardware.org/?probe=ac561937e3) | Mar 08, 2023 |
| AZW           | GT-R                        | Notebook    | [cce9cccb8f](https://linux-hardware.org/?probe=cce9cccb8f) | Mar 07, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c6f9f5a58d](https://linux-hardware.org/?probe=c6f9f5a58d) | Mar 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0cd8da5364](https://linux-hardware.org/?probe=0cd8da5364) | Mar 06, 2023 |
| Gigabyte      | P35-DS3L                    | Desktop     | [31aeecfcb9](https://linux-hardware.org/?probe=31aeecfcb9) | Mar 06, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [9b72e94139](https://linux-hardware.org/?probe=9b72e94139) | Mar 06, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [c420621505](https://linux-hardware.org/?probe=c420621505) | Mar 05, 2023 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [d000dc6718](https://linux-hardware.org/?probe=d000dc6718) | Mar 04, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [9c91f76369](https://linux-hardware.org/?probe=9c91f76369) | Mar 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [9b0664e4d7](https://linux-hardware.org/?probe=9b0664e4d7) | Mar 04, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [ba97297cf9](https://linux-hardware.org/?probe=ba97297cf9) | Mar 04, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [914a9990c4](https://linux-hardware.org/?probe=914a9990c4) | Mar 04, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [82ecc9ac72](https://linux-hardware.org/?probe=82ecc9ac72) | Mar 03, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [84e37e870d](https://linux-hardware.org/?probe=84e37e870d) | Mar 03, 2023 |
| Toshiba       | dynabook R73/BN             | Notebook    | [1d81bb5f08](https://linux-hardware.org/?probe=1d81bb5f08) | Mar 03, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [e828686fc3](https://linux-hardware.org/?probe=e828686fc3) | Mar 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [1da5b61697](https://linux-hardware.org/?probe=1da5b61697) | Mar 02, 2023 |
| Acer          | Aspire E1-532P              | Notebook    | [8a23f06db4](https://linux-hardware.org/?probe=8a23f06db4) | Mar 01, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [aa7d308d7e](https://linux-hardware.org/?probe=aa7d308d7e) | Mar 01, 2023 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | Desktop     | [6f1de5f17c](https://linux-hardware.org/?probe=6f1de5f17c) | Feb 28, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [5a0c297e10](https://linux-hardware.org/?probe=5a0c297e10) | Feb 28, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a6af4042ea](https://linux-hardware.org/?probe=a6af4042ea) | Feb 28, 2023 |
| Foxconn       | G31MX Series                | Desktop     | [79ee8e5da3](https://linux-hardware.org/?probe=79ee8e5da3) | Feb 28, 2023 |
| Dell          | Latitude E6420              | Notebook    | [a84f4dbcbb](https://linux-hardware.org/?probe=a84f4dbcbb) | Feb 28, 2023 |
| ASUSTek       | K75VJ                       | Notebook    | [7fc0fff829](https://linux-hardware.org/?probe=7fc0fff829) | Feb 27, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [0335729036](https://linux-hardware.org/?probe=0335729036) | Feb 27, 2023 |
| Intel         | H61                         | Desktop     | [b61ef1ed65](https://linux-hardware.org/?probe=b61ef1ed65) | Feb 27, 2023 |
| MSI           | NF750-G55                   | Desktop     | [f279251ffa](https://linux-hardware.org/?probe=f279251ffa) | Feb 27, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [5f035002e1](https://linux-hardware.org/?probe=5f035002e1) | Feb 27, 2023 |
| Acer          | EG43M                       | Desktop     | [d533c457eb](https://linux-hardware.org/?probe=d533c457eb) | Feb 26, 2023 |
| ASUSTek       | PRIME Q270M-C               | Desktop     | [edf748dbbb](https://linux-hardware.org/?probe=edf748dbbb) | Feb 26, 2023 |
| eMachines     | eME728                      | Notebook    | [2331984fc8](https://linux-hardware.org/?probe=2331984fc8) | Feb 26, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [d9f49e98fd](https://linux-hardware.org/?probe=d9f49e98fd) | Feb 25, 2023 |
| Toshiba       | Satellite C850              | Notebook    | [99d4efbb52](https://linux-hardware.org/?probe=99d4efbb52) | Feb 25, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [ab8247e106](https://linux-hardware.org/?probe=ab8247e106) | Feb 24, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [fad0bd20e1](https://linux-hardware.org/?probe=fad0bd20e1) | Feb 24, 2023 |
| HP            | 650                         | Notebook    | [ab0b350259](https://linux-hardware.org/?probe=ab0b350259) | Feb 24, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [91c8d45121](https://linux-hardware.org/?probe=91c8d45121) | Feb 24, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [9171567db4](https://linux-hardware.org/?probe=9171567db4) | Feb 24, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [b410c9f493](https://linux-hardware.org/?probe=b410c9f493) | Feb 24, 2023 |
| HP            | 1998                        | Desktop     | [145c009f05](https://linux-hardware.org/?probe=145c009f05) | Feb 24, 2023 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [21aa20cd64](https://linux-hardware.org/?probe=21aa20cd64) | Feb 24, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [12040fcd10](https://linux-hardware.org/?probe=12040fcd10) | Feb 24, 2023 |
| Toshiba       | Satellite C850-1GF          | Notebook    | [f568855409](https://linux-hardware.org/?probe=f568855409) | Feb 24, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [016a51a4af](https://linux-hardware.org/?probe=016a51a4af) | Feb 23, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [de05d0d3f6](https://linux-hardware.org/?probe=de05d0d3f6) | Feb 23, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [cfe5ecec44](https://linux-hardware.org/?probe=cfe5ecec44) | Feb 23, 2023 |
| Biostar       | N68S3B                      | Desktop     | [4572b3d965](https://linux-hardware.org/?probe=4572b3d965) | Feb 23, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [75b2eb9c1f](https://linux-hardware.org/?probe=75b2eb9c1f) | Feb 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [d488fc0d9a](https://linux-hardware.org/?probe=d488fc0d9a) | Feb 22, 2023 |
| Positivo      | S14SL01                     | Notebook    | [914a9e691e](https://linux-hardware.org/?probe=914a9e691e) | Feb 22, 2023 |
| Lenovo        | ThinkPad T430s 23551M9      | Notebook    | [91b6a109b4](https://linux-hardware.org/?probe=91b6a109b4) | Feb 22, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [ad365efca1](https://linux-hardware.org/?probe=ad365efca1) | Feb 22, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [4803e8ee01](https://linux-hardware.org/?probe=4803e8ee01) | Feb 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [2d36b57c9c](https://linux-hardware.org/?probe=2d36b57c9c) | Feb 22, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [9523a0ccc2](https://linux-hardware.org/?probe=9523a0ccc2) | Feb 22, 2023 |
| Gateway       | NV53A                       | Notebook    | [1e2b4ec4d3](https://linux-hardware.org/?probe=1e2b4ec4d3) | Feb 22, 2023 |
| Fujitsu Si... | AMILO Li3910                | Notebook    | [28890c5346](https://linux-hardware.org/?probe=28890c5346) | Feb 21, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [b4288b76ee](https://linux-hardware.org/?probe=b4288b76ee) | Feb 21, 2023 |
| HP            | Pavilion dv6                | Notebook    | [526430f218](https://linux-hardware.org/?probe=526430f218) | Feb 21, 2023 |
| MSI           | Z170A XPOWER GAMING TITA... | Desktop     | [b644019f77](https://linux-hardware.org/?probe=b644019f77) | Feb 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [80df77e6a1](https://linux-hardware.org/?probe=80df77e6a1) | Feb 21, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [bbef057c8f](https://linux-hardware.org/?probe=bbef057c8f) | Feb 21, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [d81ff5358a](https://linux-hardware.org/?probe=d81ff5358a) | Feb 20, 2023 |
| MSI           | G41M-P23                    | Desktop     | [04211b9202](https://linux-hardware.org/?probe=04211b9202) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [119e106d80](https://linux-hardware.org/?probe=119e106d80) | Feb 20, 2023 |
| ASRock        | 880GM-LE FX                 | Desktop     | [db290cd703](https://linux-hardware.org/?probe=db290cd703) | Feb 19, 2023 |
| Lenovo        | B560 43308VG                | Notebook    | [c30b594458](https://linux-hardware.org/?probe=c30b594458) | Feb 19, 2023 |
| HP            | ProBook 4520s               | Notebook    | [8192287499](https://linux-hardware.org/?probe=8192287499) | Feb 19, 2023 |
| MSI           | Z97M GAMING                 | Desktop     | [e983a3704e](https://linux-hardware.org/?probe=e983a3704e) | Feb 19, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | Notebook    | [b0941b8ef0](https://linux-hardware.org/?probe=b0941b8ef0) | Feb 18, 2023 |
| HP            | 15                          | Notebook    | [4db2520843](https://linux-hardware.org/?probe=4db2520843) | Feb 18, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [ff9cd473da](https://linux-hardware.org/?probe=ff9cd473da) | Feb 18, 2023 |
| HP            | ProBook 4540s               | Notebook    | [cc3e78f73f](https://linux-hardware.org/?probe=cc3e78f73f) | Feb 18, 2023 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [8dd1992835](https://linux-hardware.org/?probe=8dd1992835) | Feb 18, 2023 |
| ASRock        | 880GM-LE FX                 | Desktop     | [1d45a444a3](https://linux-hardware.org/?probe=1d45a444a3) | Feb 18, 2023 |
| PC Special... | NJ50_70CU                   | Notebook    | [68dd853397](https://linux-hardware.org/?probe=68dd853397) | Feb 17, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [3ed988e135](https://linux-hardware.org/?probe=3ed988e135) | Feb 17, 2023 |
| Gigabyte      | H87M-HD3                    | Desktop     | [778b7898e3](https://linux-hardware.org/?probe=778b7898e3) | Feb 17, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [a524479b7a](https://linux-hardware.org/?probe=a524479b7a) | Feb 17, 2023 |
| Toshiba       | Satellite C70-C-18E         | Notebook    | [7642482909](https://linux-hardware.org/?probe=7642482909) | Feb 17, 2023 |
| EVGA          | 151-IB-E699                 | Desktop     | [9e975c7966](https://linux-hardware.org/?probe=9e975c7966) | Feb 17, 2023 |
| HP            | Pavilion 15                 | Notebook    | [a48098f6fc](https://linux-hardware.org/?probe=a48098f6fc) | Feb 17, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [ac458108b4](https://linux-hardware.org/?probe=ac458108b4) | Feb 17, 2023 |
| Pegatron      | IPM31G                      | Desktop     | [42d112d7e0](https://linux-hardware.org/?probe=42d112d7e0) | Feb 17, 2023 |
| ASUSTek       | K54C                        | Notebook    | [ea944628df](https://linux-hardware.org/?probe=ea944628df) | Feb 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [66c33604c4](https://linux-hardware.org/?probe=66c33604c4) | Feb 17, 2023 |
| Samsung       | R519/R719                   | Notebook    | [1dc4bc1b72](https://linux-hardware.org/?probe=1dc4bc1b72) | Feb 17, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [ffd622d65f](https://linux-hardware.org/?probe=ffd622d65f) | Feb 17, 2023 |
| HP            | 2820h                       | Desktop     | [552bdc9930](https://linux-hardware.org/?probe=552bdc9930) | Feb 17, 2023 |
| eMachines     | eMachiens G443              | Notebook    | [096a4bb9e4](https://linux-hardware.org/?probe=096a4bb9e4) | Feb 16, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [95a9115968](https://linux-hardware.org/?probe=95a9115968) | Feb 16, 2023 |
| MSI           | H61M-E33                    | Desktop     | [f0c902ce04](https://linux-hardware.org/?probe=f0c902ce04) | Feb 16, 2023 |
| MSI           | Z97-G45 GAMING              | Desktop     | [c6a7d3a755](https://linux-hardware.org/?probe=c6a7d3a755) | Feb 16, 2023 |
| Gigabyte      | MZAPLBP-00                  | Desktop     | [b043125d6e](https://linux-hardware.org/?probe=b043125d6e) | Feb 16, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [3ce39f40e7](https://linux-hardware.org/?probe=3ce39f40e7) | Feb 16, 2023 |
| MSI           | B350M PRO-VD PLUS           | Desktop     | [63789621e0](https://linux-hardware.org/?probe=63789621e0) | Feb 16, 2023 |
| Lenovo        | ThinkCentre M91 4518E4S     | Desktop     | [91b1fb7e03](https://linux-hardware.org/?probe=91b1fb7e03) | Feb 16, 2023 |
| Philco        | DTC-A55                     | Desktop     | [e957b8f1cf](https://linux-hardware.org/?probe=e957b8f1cf) | Feb 16, 2023 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [9f9cc6f9e2](https://linux-hardware.org/?probe=9f9cc6f9e2) | Feb 16, 2023 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [8e521a2efc](https://linux-hardware.org/?probe=8e521a2efc) | Feb 16, 2023 |
| ASUSTek       | H81T                        | Desktop     | [51aa090e9a](https://linux-hardware.org/?probe=51aa090e9a) | Feb 16, 2023 |
| ASUSTek       | N76VZ                       | Notebook    | [ed9bd6b127](https://linux-hardware.org/?probe=ed9bd6b127) | Feb 16, 2023 |
| Dell          | Latitude E7440              | Notebook    | [86f8d34ba7](https://linux-hardware.org/?probe=86f8d34ba7) | Feb 16, 2023 |
| HP            | 3031h                       | Desktop     | [2b0cc2bd6e](https://linux-hardware.org/?probe=2b0cc2bd6e) | Feb 16, 2023 |
| Toshiba       | dynabook R73/BN             | Notebook    | [df7e69c5c4](https://linux-hardware.org/?probe=df7e69c5c4) | Feb 16, 2023 |
| HP            | ProBook 470 G4              | Notebook    | [8730091665](https://linux-hardware.org/?probe=8730091665) | Feb 15, 2023 |
| HP            | Notebook                    | Notebook    | [21442c303e](https://linux-hardware.org/?probe=21442c303e) | Feb 15, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [745ae4d0fb](https://linux-hardware.org/?probe=745ae4d0fb) | Feb 15, 2023 |
| MSI           | MS-7235                     | Desktop     | [519f3742a3](https://linux-hardware.org/?probe=519f3742a3) | Feb 15, 2023 |
| Dell          | 0NK5PH A00                  | Desktop     | [5455b577db](https://linux-hardware.org/?probe=5455b577db) | Feb 15, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [bc69f33fa2](https://linux-hardware.org/?probe=bc69f33fa2) | Feb 15, 2023 |
| ASUSTek       | K52N                        | Notebook    | [f87ece85e9](https://linux-hardware.org/?probe=f87ece85e9) | Feb 15, 2023 |
| Gigabyte      | P43-ES3G                    | Desktop     | [528ffce1c7](https://linux-hardware.org/?probe=528ffce1c7) | Feb 15, 2023 |
| HP            | 1000                        | Notebook    | [57de0f3103](https://linux-hardware.org/?probe=57de0f3103) | Feb 15, 2023 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [20b88dda19](https://linux-hardware.org/?probe=20b88dda19) | Feb 15, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [3ab6d305fc](https://linux-hardware.org/?probe=3ab6d305fc) | Feb 15, 2023 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [f0d6ada218](https://linux-hardware.org/?probe=f0d6ada218) | Feb 15, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [b30e6a84c8](https://linux-hardware.org/?probe=b30e6a84c8) | Feb 14, 2023 |
| Samsung       | RV419/RV420                 | Notebook    | [7ec9e518c4](https://linux-hardware.org/?probe=7ec9e518c4) | Feb 14, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [dddbb2d135](https://linux-hardware.org/?probe=dddbb2d135) | Feb 14, 2023 |
| MSI           | Z97-G45 GAMING              | Desktop     | [f9318d4390](https://linux-hardware.org/?probe=f9318d4390) | Feb 14, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [bf015f98c2](https://linux-hardware.org/?probe=bf015f98c2) | Feb 14, 2023 |
| ASRock        | E350M1                      | Desktop     | [ac69adceb6](https://linux-hardware.org/?probe=ac69adceb6) | Feb 13, 2023 |
| ASUSTek       | P7P55D-E EVO                | Desktop     | [f1ec250753](https://linux-hardware.org/?probe=f1ec250753) | Feb 13, 2023 |
| Dell          | 0YXT71 A01                  | Desktop     | [cdc2dedbcd](https://linux-hardware.org/?probe=cdc2dedbcd) | Feb 13, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7623da10b8](https://linux-hardware.org/?probe=7623da10b8) | Feb 13, 2023 |
| HP            | 3031h                       | Desktop     | [f9a0848388](https://linux-hardware.org/?probe=f9a0848388) | Feb 11, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [4f99163f99](https://linux-hardware.org/?probe=4f99163f99) | Feb 11, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f0f4d31de2](https://linux-hardware.org/?probe=f0f4d31de2) | Feb 10, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [e8fdc1676a](https://linux-hardware.org/?probe=e8fdc1676a) | Feb 10, 2023 |
| Medion        | TJ4105                      | Desktop     | [cd654518c0](https://linux-hardware.org/?probe=cd654518c0) | Feb 09, 2023 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [8532f05156](https://linux-hardware.org/?probe=8532f05156) | Feb 09, 2023 |
| HP            | Compaq Presario CQ61        | Notebook    | [df4d59acd5](https://linux-hardware.org/?probe=df4d59acd5) | Feb 07, 2023 |
| HP            | 1905                        | Desktop     | [a442e1de06](https://linux-hardware.org/?probe=a442e1de06) | Feb 07, 2023 |
| Lenovo        | ThinkPad X240 20AL00FMGE    | Notebook    | [0ac2678512](https://linux-hardware.org/?probe=0ac2678512) | Feb 06, 2023 |
| Acer          | Extensa 5635                | Notebook    | [8f8f4d24f9](https://linux-hardware.org/?probe=8f8f4d24f9) | Feb 06, 2023 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | Desktop     | [a527005a2a](https://linux-hardware.org/?probe=a527005a2a) | Feb 06, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [7ca566f68b](https://linux-hardware.org/?probe=7ca566f68b) | Feb 05, 2023 |
| Dell          | 084J0R A00                  | Desktop     | [7fe633b52f](https://linux-hardware.org/?probe=7fe633b52f) | Feb 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d6adca1255](https://linux-hardware.org/?probe=d6adca1255) | Feb 04, 2023 |
| HP            | ProBook 6465b               | Notebook    | [00b2021fae](https://linux-hardware.org/?probe=00b2021fae) | Feb 04, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [87fe173b18](https://linux-hardware.org/?probe=87fe173b18) | Feb 02, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [6a440e41d7](https://linux-hardware.org/?probe=6a440e41d7) | Feb 02, 2023 |
| Dell          | Latitude E5420              | Notebook    | [ccc3ca9853](https://linux-hardware.org/?probe=ccc3ca9853) | Jan 31, 2023 |
| HP            | 3115-AEC13432GR1            | Notebook    | [98eb70341a](https://linux-hardware.org/?probe=98eb70341a) | Jan 30, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [e2fa9aa820](https://linux-hardware.org/?probe=e2fa9aa820) | Jan 29, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [e3f865cd20](https://linux-hardware.org/?probe=e3f865cd20) | Jan 28, 2023 |
| HP            | Notebook                    | Notebook    | [d38e078368](https://linux-hardware.org/?probe=d38e078368) | Jan 28, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [e00443a9cc](https://linux-hardware.org/?probe=e00443a9cc) | Jan 27, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [d87ac57c19](https://linux-hardware.org/?probe=d87ac57c19) | Jan 27, 2023 |
| HP            | 14                          | Notebook    | [53d080d83a](https://linux-hardware.org/?probe=53d080d83a) | Jan 27, 2023 |
| Dell          | Inspiron 15 3521            | Notebook    | [41f89081ff](https://linux-hardware.org/?probe=41f89081ff) | Jan 26, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [873ee647b0](https://linux-hardware.org/?probe=873ee647b0) | Jan 26, 2023 |
| Dell          | 0773VG A00                  | Desktop     | [328dae4014](https://linux-hardware.org/?probe=328dae4014) | Jan 26, 2023 |
| HP            | 3048h                       | Desktop     | [caabf4189f](https://linux-hardware.org/?probe=caabf4189f) | Jan 25, 2023 |
| OEGStone      | C4100/C5100                 | Notebook    | [4365b7b231](https://linux-hardware.org/?probe=4365b7b231) | Jan 25, 2023 |
| AZW           | U59                         | Desktop     | [6d2b672b77](https://linux-hardware.org/?probe=6d2b672b77) | Jan 25, 2023 |
| ASRock        | 775XFire-VSTA               | Desktop     | [e80788f790](https://linux-hardware.org/?probe=e80788f790) | Jan 24, 2023 |
| Lenovo        | ThinkPad W541 20EF0020MD    | Notebook    | [fca73ad2a9](https://linux-hardware.org/?probe=fca73ad2a9) | Jan 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [95898eae6d](https://linux-hardware.org/?probe=95898eae6d) | Jan 23, 2023 |
| Packard Be... | PB56                        | Notebook    | [f26fcb7ee5](https://linux-hardware.org/?probe=f26fcb7ee5) | Jan 23, 2023 |
| Dell          | 0X2MKR A00                  | All in one  | [5b29ed7213](https://linux-hardware.org/?probe=5b29ed7213) | Jan 23, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [dcecec2239](https://linux-hardware.org/?probe=dcecec2239) | Jan 22, 2023 |
| Gigabyte      | N3050ND3H                   | Desktop     | [1663928526](https://linux-hardware.org/?probe=1663928526) | Jan 21, 2023 |
| HP            | Pavilion dv5                | Notebook    | [94ba65752b](https://linux-hardware.org/?probe=94ba65752b) | Jan 20, 2023 |
| GEEKOM        | MiniAir 11                  | Server      | [0d27879bb6](https://linux-hardware.org/?probe=0d27879bb6) | Jan 19, 2023 |
| ASUSTek       | Z77-A                       | Desktop     | [10081492a7](https://linux-hardware.org/?probe=10081492a7) | Jan 19, 2023 |
| Acer          | Iconia Tab W501             | Tablet      | [c3d132fb91](https://linux-hardware.org/?probe=c3d132fb91) | Jan 18, 2023 |
| ASUSTek       | C60M1-I                     | Desktop     | [defd3912ae](https://linux-hardware.org/?probe=defd3912ae) | Jan 18, 2023 |
| Panasonic     | CF-53JULCV1M                | Notebook    | [89c1166efc](https://linux-hardware.org/?probe=89c1166efc) | Jan 18, 2023 |
| Unknown       | HX90                        | Desktop     | [2b034e44e2](https://linux-hardware.org/?probe=2b034e44e2) | Jan 18, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [bf606ed50a](https://linux-hardware.org/?probe=bf606ed50a) | Jan 18, 2023 |
| HP            | ProBook 440 G1              | Notebook    | [035c7a4e2d](https://linux-hardware.org/?probe=035c7a4e2d) | Jan 18, 2023 |
| Medion        | MS-7621                     | Desktop     | [67b535d88f](https://linux-hardware.org/?probe=67b535d88f) | Jan 18, 2023 |
| Dell          | Latitude 7490               | Notebook    | [b611fc6b64](https://linux-hardware.org/?probe=b611fc6b64) | Jan 18, 2023 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [74a62575d2](https://linux-hardware.org/?probe=74a62575d2) | Jan 17, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [276102bb1a](https://linux-hardware.org/?probe=276102bb1a) | Jan 16, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [33985f088a](https://linux-hardware.org/?probe=33985f088a) | Jan 16, 2023 |
| Acer          | Iconia Tab W501             | Tablet      | [9941154ca3](https://linux-hardware.org/?probe=9941154ca3) | Jan 15, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [c20a339ddb](https://linux-hardware.org/?probe=c20a339ddb) | Jan 15, 2023 |
| Lenovo        | SDK0F82993 WIN              | Desktop     | [48f294dfb4](https://linux-hardware.org/?probe=48f294dfb4) | Jan 15, 2023 |
| Acer          | Aspire 7551                 | Notebook    | [b3e5df94f4](https://linux-hardware.org/?probe=b3e5df94f4) | Jan 15, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [291dceb273](https://linux-hardware.org/?probe=291dceb273) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [b70eca9c43](https://linux-hardware.org/?probe=b70eca9c43) | Jan 14, 2023 |
| Dell          | Latitude E7440              | Notebook    | [9c4aac8b46](https://linux-hardware.org/?probe=9c4aac8b46) | Jan 14, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [79d2961429](https://linux-hardware.org/?probe=79d2961429) | Jan 14, 2023 |
| HP            | 8054                        | Desktop     | [faf1c97cea](https://linux-hardware.org/?probe=faf1c97cea) | Jan 14, 2023 |
| Supermicro    | A1SA2-2750F                 | Server      | [e134d7a317](https://linux-hardware.org/?probe=e134d7a317) | Jan 14, 2023 |
| HP            | 18E5                        | Desktop     | [614faa708b](https://linux-hardware.org/?probe=614faa708b) | Jan 14, 2023 |
| Pegatron      | IPM41-D3                    | Desktop     | [23a918874b](https://linux-hardware.org/?probe=23a918874b) | Jan 14, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [d60bab803e](https://linux-hardware.org/?probe=d60bab803e) | Jan 13, 2023 |
| HP            | 84EE 1100                   | All in one  | [708c21d16b](https://linux-hardware.org/?probe=708c21d16b) | Jan 13, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [12f29d53ba](https://linux-hardware.org/?probe=12f29d53ba) | Jan 13, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [72e7e2e1cf](https://linux-hardware.org/?probe=72e7e2e1cf) | Jan 11, 2023 |
| Toshiba       | Satellite C850-B561         | Notebook    | [562d6cde14](https://linux-hardware.org/?probe=562d6cde14) | Jan 11, 2023 |
| Lenovo        | ThinkPad X240 20AM001RGE    | Notebook    | [f4aafcf7a9](https://linux-hardware.org/?probe=f4aafcf7a9) | Jan 11, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [805d82d697](https://linux-hardware.org/?probe=805d82d697) | Jan 10, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [ce911686b3](https://linux-hardware.org/?probe=ce911686b3) | Jan 10, 2023 |
| Dell          | XPS M1330                   | Notebook    | [e3d66114f6](https://linux-hardware.org/?probe=e3d66114f6) | Jan 10, 2023 |
| Acer          | Iconia Tab W501             | Tablet      | [ec34a44908](https://linux-hardware.org/?probe=ec34a44908) | Jan 10, 2023 |
| Gigabyte      | H170-D3H-CF                 | Desktop     | [8064745798](https://linux-hardware.org/?probe=8064745798) | Jan 10, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [f540a5f964](https://linux-hardware.org/?probe=f540a5f964) | Jan 09, 2023 |
| Star Labs     | Lite                        | Notebook    | [6614e226df](https://linux-hardware.org/?probe=6614e226df) | Jan 09, 2023 |
| HP            | 0AA4h                       | Desktop     | [e0776de36f](https://linux-hardware.org/?probe=e0776de36f) | Jan 09, 2023 |
| HP            | 802F                        | Desktop     | [1dd3655605](https://linux-hardware.org/?probe=1dd3655605) | Jan 09, 2023 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [e2f62062de](https://linux-hardware.org/?probe=e2f62062de) | Jan 09, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [a2bce032b4](https://linux-hardware.org/?probe=a2bce032b4) | Jan 09, 2023 |
| Dell          | 0654JC A01                  | Desktop     | [c3016e1823](https://linux-hardware.org/?probe=c3016e1823) | Jan 09, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [84aa790d17](https://linux-hardware.org/?probe=84aa790d17) | Jan 09, 2023 |
| HP            | 8265                        | Desktop     | [83897e98cf](https://linux-hardware.org/?probe=83897e98cf) | Jan 08, 2023 |
| MSI           | 990XA-GD55                  | Desktop     | [b4525a8431](https://linux-hardware.org/?probe=b4525a8431) | Jan 08, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [d94d0c7025](https://linux-hardware.org/?probe=d94d0c7025) | Jan 08, 2023 |
| Dell          | Latitude E6400              | Notebook    | [70bce3a55c](https://linux-hardware.org/?probe=70bce3a55c) | Jan 08, 2023 |
| HP            | 1489                        | All in one  | [2660a9d31d](https://linux-hardware.org/?probe=2660a9d31d) | Jan 08, 2023 |
| Dell          | Latitude E5440              | Notebook    | [91bedeb5e1](https://linux-hardware.org/?probe=91bedeb5e1) | Jan 07, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [c1c8654cde](https://linux-hardware.org/?probe=c1c8654cde) | Jan 07, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [782467ee8c](https://linux-hardware.org/?probe=782467ee8c) | Jan 07, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [d0e4567b4a](https://linux-hardware.org/?probe=d0e4567b4a) | Jan 07, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [3bc9e3b318](https://linux-hardware.org/?probe=3bc9e3b318) | Jan 07, 2023 |
| Acer          | Veriton N4640G              | Desktop     | [3392dd3c90](https://linux-hardware.org/?probe=3392dd3c90) | Jan 07, 2023 |
| Alienware     | 04VWF2 A02                  | Desktop     | [15f4ed4e31](https://linux-hardware.org/?probe=15f4ed4e31) | Jan 07, 2023 |
| Lenovo        | ThinkPad Helix 2nd 20CHS... | Tablet      | [e6190d3469](https://linux-hardware.org/?probe=e6190d3469) | Jan 07, 2023 |
| HP            | 250 G3                      | Notebook    | [227b44bf7c](https://linux-hardware.org/?probe=227b44bf7c) | Jan 06, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [0232b39536](https://linux-hardware.org/?probe=0232b39536) | Jan 06, 2023 |
| eMachines     | E725                        | Notebook    | [0655d63f70](https://linux-hardware.org/?probe=0655d63f70) | Jan 06, 2023 |
| Acer          | Spin SP513-51               | Convertible | [1fe9e7fa54](https://linux-hardware.org/?probe=1fe9e7fa54) | Jan 06, 2023 |
| Acer          | Veriton M2631G V:1.0        | Desktop     | [ddeffc27a7](https://linux-hardware.org/?probe=ddeffc27a7) | Jan 05, 2023 |
| Pegatron      | 2AC3                        | Desktop     | [4ce129e600](https://linux-hardware.org/?probe=4ce129e600) | Jan 05, 2023 |
| ASUSTek       | K55VM                       | Notebook    | [d4d53ed49f](https://linux-hardware.org/?probe=d4d53ed49f) | Jan 04, 2023 |
| HP            | Pavilion g6                 | Notebook    | [6cae064dc5](https://linux-hardware.org/?probe=6cae064dc5) | Jan 04, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [c64a1198cd](https://linux-hardware.org/?probe=c64a1198cd) | Jan 04, 2023 |
| HP            | ProBook 470 G2              | Notebook    | [1f62ff6417](https://linux-hardware.org/?probe=1f62ff6417) | Jan 04, 2023 |
| HP            | Compaq 15                   | Notebook    | [c282ede7c5](https://linux-hardware.org/?probe=c282ede7c5) | Jan 04, 2023 |
| HP            | EliteBook 725 G3            | Notebook    | [174e0c5f05](https://linux-hardware.org/?probe=174e0c5f05) | Jan 04, 2023 |
| Dell          | Latitude D520               | Notebook    | [7f05ddf105](https://linux-hardware.org/?probe=7f05ddf105) | Jan 04, 2023 |
| Dell          | Latitude 7490               | Notebook    | [7e445638b6](https://linux-hardware.org/?probe=7e445638b6) | Jan 04, 2023 |
| MSI           | A88X-G45 GAMING             | Desktop     | [1caf5c85d9](https://linux-hardware.org/?probe=1caf5c85d9) | Jan 04, 2023 |
| Sony          | VJF153                      | Notebook    | [f3643923cc](https://linux-hardware.org/?probe=f3643923cc) | Jan 04, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [c5bc3a8eae](https://linux-hardware.org/?probe=c5bc3a8eae) | Jan 03, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [c0e5361a69](https://linux-hardware.org/?probe=c0e5361a69) | Jan 03, 2023 |
| Gigabyte      | Z690 AORUS ULTRA            | Desktop     | [55627fc077](https://linux-hardware.org/?probe=55627fc077) | Jan 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [5f0eeeb9e7](https://linux-hardware.org/?probe=5f0eeeb9e7) | Jan 03, 2023 |
| Dell          | 0XCR8D A03                  | Desktop     | [faccba61cf](https://linux-hardware.org/?probe=faccba61cf) | Jan 03, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | Desktop     | [afe5105302](https://linux-hardware.org/?probe=afe5105302) | Jan 03, 2023 |
| ASUSTek       | Berkeley                    | Desktop     | [746d7be693](https://linux-hardware.org/?probe=746d7be693) | Jan 03, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | Notebook    | [a73ca839a1](https://linux-hardware.org/?probe=a73ca839a1) | Jan 03, 2023 |
| Dell          | 0MM599                      | Desktop     | [95763443e3](https://linux-hardware.org/?probe=95763443e3) | Jan 03, 2023 |
| Intel         | NUC5PPYB H76558-108         | Mini pc     | [e93bf27a59](https://linux-hardware.org/?probe=e93bf27a59) | Jan 02, 2023 |
| Positivo      | Z100                        | Notebook    | [58b7c4d1ff](https://linux-hardware.org/?probe=58b7c4d1ff) | Jan 02, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [df9ca70fa3](https://linux-hardware.org/?probe=df9ca70fa3) | Jan 02, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [85ad98c994](https://linux-hardware.org/?probe=85ad98c994) | Jan 02, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [287840d797](https://linux-hardware.org/?probe=287840d797) | Jan 02, 2023 |
| AZW           | MINI S                      | Desktop     | [ad7c4329eb](https://linux-hardware.org/?probe=ad7c4329eb) | Jan 02, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [86b79bce9e](https://linux-hardware.org/?probe=86b79bce9e) | Jan 01, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [509cc939cc](https://linux-hardware.org/?probe=509cc939cc) | Jan 01, 2023 |
| OEM           | Intel H81                   | Desktop     | [1700a7a4c7](https://linux-hardware.org/?probe=1700a7a4c7) | Jan 01, 2023 |
| Gigabyte      | B365 HD3                    | Desktop     | [195240c264](https://linux-hardware.org/?probe=195240c264) | Jan 01, 2023 |
| Dell          | System Inspiron N411Z       | Notebook    | [21f279751c](https://linux-hardware.org/?probe=21f279751c) | Jan 01, 2023 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [e2215a9d80](https://linux-hardware.org/?probe=e2215a9d80) | Jan 01, 2023 |
| Packard Be... | EasyNote TM97               | Notebook    | [fad44d67ab](https://linux-hardware.org/?probe=fad44d67ab) | Jan 01, 2023 |
| HP            | 1000                        | Notebook    | [5634ff72b1](https://linux-hardware.org/?probe=5634ff72b1) | Jan 01, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [bba53b0159](https://linux-hardware.org/?probe=bba53b0159) | Jan 01, 2023 |
| Toshiba       | Satellite A305D             | Notebook    | [b85a377462](https://linux-hardware.org/?probe=b85a377462) | Dec 31, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [7295ec02b5](https://linux-hardware.org/?probe=7295ec02b5) | Dec 31, 2022 |
| ASUSTek       | UN45                        | Desktop     | [bde2e2efb1](https://linux-hardware.org/?probe=bde2e2efb1) | Dec 31, 2022 |
| MSI           | MS-7502 Fab D               | Desktop     | [9126e1035f](https://linux-hardware.org/?probe=9126e1035f) | Dec 31, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [b0dd8fc6b5](https://linux-hardware.org/?probe=b0dd8fc6b5) | Dec 31, 2022 |
| Lenovo        | ThinkPad T410 2537BF9       | Notebook    | [f83ed1dd39](https://linux-hardware.org/?probe=f83ed1dd39) | Dec 30, 2022 |
| ASUSTek       | TP501UA                     | Notebook    | [1f2aaf8804](https://linux-hardware.org/?probe=1f2aaf8804) | Dec 30, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [e4c90250df](https://linux-hardware.org/?probe=e4c90250df) | Dec 30, 2022 |
| ASUSTek       | X555UJ                      | Notebook    | [f4ba8643aa](https://linux-hardware.org/?probe=f4ba8643aa) | Dec 30, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [b0bfa9530a](https://linux-hardware.org/?probe=b0bfa9530a) | Dec 29, 2022 |
| ASUSTek       | STRIKER II EXTREME          | Desktop     | [3258ffa0c1](https://linux-hardware.org/?probe=3258ffa0c1) | Dec 29, 2022 |
| ASUSTek       | G1                          | Notebook    | [1f8e426f96](https://linux-hardware.org/?probe=1f8e426f96) | Dec 29, 2022 |
| Gigabyte      | H61M-D2H                    | Desktop     | [28aede6faf](https://linux-hardware.org/?probe=28aede6faf) | Dec 29, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [1b7e70ab6e](https://linux-hardware.org/?probe=1b7e70ab6e) | Dec 29, 2022 |
| HP            | Notebook                    | Notebook    | [91bc85bf6e](https://linux-hardware.org/?probe=91bc85bf6e) | Dec 29, 2022 |
| Samsung       | NB30/N146                   | Notebook    | [7f9b976789](https://linux-hardware.org/?probe=7f9b976789) | Dec 29, 2022 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [3f0c89985c](https://linux-hardware.org/?probe=3f0c89985c) | Dec 29, 2022 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [4734f4370b](https://linux-hardware.org/?probe=4734f4370b) | Dec 28, 2022 |
| Lenovo        | V560                        | Notebook    | [f937de4c61](https://linux-hardware.org/?probe=f937de4c61) | Dec 28, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [92ece593f5](https://linux-hardware.org/?probe=92ece593f5) | Dec 28, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [bd56ec4f01](https://linux-hardware.org/?probe=bd56ec4f01) | Dec 28, 2022 |
| Gigabyte      | MJPLNBB-00                  | Desktop     | [879a5b77ff](https://linux-hardware.org/?probe=879a5b77ff) | Dec 28, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [6e1255aa44](https://linux-hardware.org/?probe=6e1255aa44) | Dec 28, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [43a0d87199](https://linux-hardware.org/?probe=43a0d87199) | Dec 28, 2022 |
| Positivo      | Hendrix                     | Notebook    | [55aa2f92d7](https://linux-hardware.org/?probe=55aa2f92d7) | Dec 27, 2022 |
| Dell          | Latitude 7480               | Notebook    | [45b0f992f6](https://linux-hardware.org/?probe=45b0f992f6) | Dec 27, 2022 |
| Pegatron      | APX85-GS                    | Desktop     | [82db9f15c6](https://linux-hardware.org/?probe=82db9f15c6) | Dec 27, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [7a3513a2e1](https://linux-hardware.org/?probe=7a3513a2e1) | Dec 27, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [58b02cceb0](https://linux-hardware.org/?probe=58b02cceb0) | Dec 27, 2022 |
| Acer          | Aspire TC-865 V:1.1         | Desktop     | [0c8add55fe](https://linux-hardware.org/?probe=0c8add55fe) | Dec 27, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [9e6b5e5ebf](https://linux-hardware.org/?probe=9e6b5e5ebf) | Dec 27, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [8ecb7e11b3](https://linux-hardware.org/?probe=8ecb7e11b3) | Dec 26, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [bc68280036](https://linux-hardware.org/?probe=bc68280036) | Dec 26, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [705baed85a](https://linux-hardware.org/?probe=705baed85a) | Dec 26, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [6703f01cfc](https://linux-hardware.org/?probe=6703f01cfc) | Dec 26, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [46123218f3](https://linux-hardware.org/?probe=46123218f3) | Dec 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34604... | Notebook    | [dfb555f802](https://linux-hardware.org/?probe=dfb555f802) | Dec 26, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [14611d6c99](https://linux-hardware.org/?probe=14611d6c99) | Dec 26, 2022 |
| HP            | 2AF7                        | Desktop     | [96344d97ba](https://linux-hardware.org/?probe=96344d97ba) | Dec 26, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [e012bb5bc1](https://linux-hardware.org/?probe=e012bb5bc1) | Dec 25, 2022 |
| ASUSTek       | M51Tr                       | Notebook    | [dffa412a98](https://linux-hardware.org/?probe=dffa412a98) | Dec 25, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [500abd4186](https://linux-hardware.org/?probe=500abd4186) | Dec 25, 2022 |
| ASUSTek       | NARRA3                      | Desktop     | [cc0a64d0df](https://linux-hardware.org/?probe=cc0a64d0df) | Dec 25, 2022 |
| Pegatron      | IPPPV-D3G                   | Desktop     | [4d1a2299dc](https://linux-hardware.org/?probe=4d1a2299dc) | Dec 24, 2022 |
| Dell          | G7 7790                     | Notebook    | [da767d5fd4](https://linux-hardware.org/?probe=da767d5fd4) | Dec 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [9e269ee2a4](https://linux-hardware.org/?probe=9e269ee2a4) | Dec 24, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [8c835888d6](https://linux-hardware.org/?probe=8c835888d6) | Dec 24, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [08a1ad1c63](https://linux-hardware.org/?probe=08a1ad1c63) | Dec 24, 2022 |
| Acer          | Aspire A315-21G             | Notebook    | [435933801a](https://linux-hardware.org/?probe=435933801a) | Dec 24, 2022 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [11eb39826a](https://linux-hardware.org/?probe=11eb39826a) | Dec 24, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [f2e0369ba1](https://linux-hardware.org/?probe=f2e0369ba1) | Dec 24, 2022 |
| Positivo      | Mobile                      | Notebook    | [6031910e64](https://linux-hardware.org/?probe=6031910e64) | Dec 24, 2022 |
| Lenovo        | ThinkPad SL 2746N8G         | Notebook    | [f540a3a892](https://linux-hardware.org/?probe=f540a3a892) | Dec 23, 2022 |
| Positivo      | H14BT58                     | Notebook    | [9914219613](https://linux-hardware.org/?probe=9914219613) | Dec 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [beb602dcf6](https://linux-hardware.org/?probe=beb602dcf6) | Dec 23, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [f993ebb9ed](https://linux-hardware.org/?probe=f993ebb9ed) | Dec 23, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [5105f25e5e](https://linux-hardware.org/?probe=5105f25e5e) | Dec 23, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [00e62a7231](https://linux-hardware.org/?probe=00e62a7231) | Dec 23, 2022 |
| MSI           | 880GM-E41                   | Desktop     | [2880803d71](https://linux-hardware.org/?probe=2880803d71) | Dec 23, 2022 |
| ASUSTek       | TUF B360-PRO GAMING         | Desktop     | [561b98afc3](https://linux-hardware.org/?probe=561b98afc3) | Dec 23, 2022 |
| Dell          | 0JJW8N A03                  | Desktop     | [5917cccca0](https://linux-hardware.org/?probe=5917cccca0) | Dec 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [87da3fdf4d](https://linux-hardware.org/?probe=87da3fdf4d) | Dec 23, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [791ace450e](https://linux-hardware.org/?probe=791ace450e) | Dec 23, 2022 |
| ASRock        | FM2A88M-HD+                 | Desktop     | [18b83ae613](https://linux-hardware.org/?probe=18b83ae613) | Dec 22, 2022 |
| Dell          | Latitude 5280               | Notebook    | [59002e923b](https://linux-hardware.org/?probe=59002e923b) | Dec 22, 2022 |
| HP            | Pavilion dv9000 (RR329EA... | Notebook    | [6fc7281f2f](https://linux-hardware.org/?probe=6fc7281f2f) | Dec 22, 2022 |
| ASUSTek       | 1015BXO                     | Notebook    | [7cce9a65ec](https://linux-hardware.org/?probe=7cce9a65ec) | Dec 22, 2022 |
| Toshiba       | Satellite C55-B             | Notebook    | [8f81c02bbf](https://linux-hardware.org/?probe=8f81c02bbf) | Dec 21, 2022 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [003ac98d7f](https://linux-hardware.org/?probe=003ac98d7f) | Dec 21, 2022 |
| PERTOSA       | GA-H110TN-M                 | Desktop     | [048d8cca49](https://linux-hardware.org/?probe=048d8cca49) | Dec 21, 2022 |
| Dell          | 0VHWTR A01                  | Desktop     | [a5070ec279](https://linux-hardware.org/?probe=a5070ec279) | Dec 20, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ec2528ae6f](https://linux-hardware.org/?probe=ec2528ae6f) | Dec 20, 2022 |
| Acer          | Aspire 5336                 | Notebook    | [9724b5d705](https://linux-hardware.org/?probe=9724b5d705) | Dec 20, 2022 |
| RM Educati... | RM                          | Notebook    | [758b521362](https://linux-hardware.org/?probe=758b521362) | Dec 20, 2022 |
| Langchao      | NF5110                      | Server      | [3578ca8ceb](https://linux-hardware.org/?probe=3578ca8ceb) | Dec 20, 2022 |
| Lenovo        | ThinkPad W510 4318CTO       | Notebook    | [215feb2d5e](https://linux-hardware.org/?probe=215feb2d5e) | Dec 20, 2022 |
| ECS           | G31T-M7                     | Desktop     | [327ac25b68](https://linux-hardware.org/?probe=327ac25b68) | Dec 20, 2022 |
| Gigabyte      | 945GCMX-S2                  | Desktop     | [3b9937e6df](https://linux-hardware.org/?probe=3b9937e6df) | Dec 20, 2022 |
| MSI           | GE62 6QD                    | Notebook    | [20d959e778](https://linux-hardware.org/?probe=20d959e778) | Dec 19, 2022 |
| LG Electro... | 17Z90P-G.AA56F              | Notebook    | [fa43417151](https://linux-hardware.org/?probe=fa43417151) | Dec 19, 2022 |
| MSI           | H81M-E34                    | Desktop     | [3aa811568d](https://linux-hardware.org/?probe=3aa811568d) | Dec 19, 2022 |
| Toshiba       | EQUIUM A300D                | Notebook    | [ffde5ccef4](https://linux-hardware.org/?probe=ffde5ccef4) | Dec 19, 2022 |
| ASUSTek       | P5QL PRO                    | Desktop     | [5f3343c803](https://linux-hardware.org/?probe=5f3343c803) | Dec 19, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [d1d5c6a19e](https://linux-hardware.org/?probe=d1d5c6a19e) | Dec 19, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [b5c4e6cf61](https://linux-hardware.org/?probe=b5c4e6cf61) | Dec 19, 2022 |
| Dell          | 0M858N A00                  | Desktop     | [e46a95080d](https://linux-hardware.org/?probe=e46a95080d) | Dec 18, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [4f41f354cd](https://linux-hardware.org/?probe=4f41f354cd) | Dec 18, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [ff287eecab](https://linux-hardware.org/?probe=ff287eecab) | Dec 18, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [71ebf721cc](https://linux-hardware.org/?probe=71ebf721cc) | Dec 17, 2022 |
| HP            | 8055                        | Desktop     | [6c7fa83dc9](https://linux-hardware.org/?probe=6c7fa83dc9) | Dec 17, 2022 |
| Dell          | Latitude E6330              | Notebook    | [ca6551bf8e](https://linux-hardware.org/?probe=ca6551bf8e) | Dec 17, 2022 |
| Notebook      | W65_67SZ                    | Notebook    | [770c00f7d9](https://linux-hardware.org/?probe=770c00f7d9) | Dec 17, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [0d7a54bc21](https://linux-hardware.org/?probe=0d7a54bc21) | Dec 16, 2022 |
| Dell          | 0RW203                      | Desktop     | [2f5bede488](https://linux-hardware.org/?probe=2f5bede488) | Dec 16, 2022 |
| Lenovo        | Yoga 2-11 20332             | Notebook    | [92a038a164](https://linux-hardware.org/?probe=92a038a164) | Dec 16, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [04cc986bf6](https://linux-hardware.org/?probe=04cc986bf6) | Dec 15, 2022 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [80358a5ba1](https://linux-hardware.org/?probe=80358a5ba1) | Dec 15, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [b2b98c19da](https://linux-hardware.org/?probe=b2b98c19da) | Dec 15, 2022 |
| Acer          | Veriton N2620G              | Desktop     | [a626bf668e](https://linux-hardware.org/?probe=a626bf668e) | Dec 15, 2022 |
| Dell          | 050Nt9 A00                  | All in one  | [075f206957](https://linux-hardware.org/?probe=075f206957) | Dec 15, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [a41e0d92a7](https://linux-hardware.org/?probe=a41e0d92a7) | Dec 15, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [ffe60f958c](https://linux-hardware.org/?probe=ffe60f958c) | Dec 15, 2022 |
| ASUSTek       | K40IJ                       | Notebook    | [191b6ded65](https://linux-hardware.org/?probe=191b6ded65) | Dec 15, 2022 |
| Dell          | 0FR6WH A01                  | Desktop     | [46d6c645fe](https://linux-hardware.org/?probe=46d6c645fe) | Dec 15, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [f18234034f](https://linux-hardware.org/?probe=f18234034f) | Dec 15, 2022 |
| HP            | 2AFB                        | Desktop     | [4c57ea0ee7](https://linux-hardware.org/?probe=4c57ea0ee7) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [587fac961e](https://linux-hardware.org/?probe=587fac961e) | Dec 15, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [9feb549665](https://linux-hardware.org/?probe=9feb549665) | Dec 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ad1e402db3](https://linux-hardware.org/?probe=ad1e402db3) | Dec 15, 2022 |
| Lenovo        | ThinkPad X230 23245QP       | Notebook    | [e525a77c95](https://linux-hardware.org/?probe=e525a77c95) | Dec 15, 2022 |
| Lenovo        | G460 20041                  | Notebook    | [b76fa704f7](https://linux-hardware.org/?probe=b76fa704f7) | Dec 15, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [a9d66f9686](https://linux-hardware.org/?probe=a9d66f9686) | Dec 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [259226594a](https://linux-hardware.org/?probe=259226594a) | Dec 14, 2022 |
| Dell          | Inspiron 11 - 3147          | Notebook    | [d5aa2c3900](https://linux-hardware.org/?probe=d5aa2c3900) | Dec 14, 2022 |
| ASUSTek       | P8H61-M LX2/CSM             | Desktop     | [cc6e7dae77](https://linux-hardware.org/?probe=cc6e7dae77) | Dec 14, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [0a564c9f0f](https://linux-hardware.org/?probe=0a564c9f0f) | Dec 14, 2022 |
| Datto         | SSD                         | Desktop     | [a9bff0a51c](https://linux-hardware.org/?probe=a9bff0a51c) | Dec 14, 2022 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [373f71370e](https://linux-hardware.org/?probe=373f71370e) | Dec 14, 2022 |
| HP            | 304Ah                       | Desktop     | [d8b600f39e](https://linux-hardware.org/?probe=d8b600f39e) | Dec 13, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [8525777743](https://linux-hardware.org/?probe=8525777743) | Dec 13, 2022 |
| Dell          | Latitude E7250              | Notebook    | [3e40466ae4](https://linux-hardware.org/?probe=3e40466ae4) | Dec 13, 2022 |
| HP            | Pavilion 15                 | Notebook    | [5d88eed564](https://linux-hardware.org/?probe=5d88eed564) | Dec 13, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [1539e12262](https://linux-hardware.org/?probe=1539e12262) | Dec 13, 2022 |
| ASUSTek       | Z10PH-D16 Series            | Desktop     | [18911cf243](https://linux-hardware.org/?probe=18911cf243) | Dec 13, 2022 |
| HP            | Notebook                    | Notebook    | [07b9e8995f](https://linux-hardware.org/?probe=07b9e8995f) | Dec 12, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [651fa58fbd](https://linux-hardware.org/?probe=651fa58fbd) | Dec 12, 2022 |
| MSI           | GS65 Stealth Thin 8RF       | Notebook    | [074195107c](https://linux-hardware.org/?probe=074195107c) | Dec 12, 2022 |
| Gigabyte      | H310M S2V                   | Desktop     | [6895902fe7](https://linux-hardware.org/?probe=6895902fe7) | Dec 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [c832b9b688](https://linux-hardware.org/?probe=c832b9b688) | Dec 12, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [ec5acc536f](https://linux-hardware.org/?probe=ec5acc536f) | Dec 12, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [260a382d54](https://linux-hardware.org/?probe=260a382d54) | Dec 12, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [4784b53f14](https://linux-hardware.org/?probe=4784b53f14) | Dec 12, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [62f6fd5f8d](https://linux-hardware.org/?probe=62f6fd5f8d) | Dec 12, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [9537bff125](https://linux-hardware.org/?probe=9537bff125) | Dec 11, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1d2ea30fb2](https://linux-hardware.org/?probe=1d2ea30fb2) | Dec 11, 2022 |
| Dell          | 0KG317                      | Desktop     | [cf7f697a0a](https://linux-hardware.org/?probe=cf7f697a0a) | Dec 11, 2022 |
| HP            | 650                         | Notebook    | [9bb3729969](https://linux-hardware.org/?probe=9bb3729969) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [d7ea1184a2](https://linux-hardware.org/?probe=d7ea1184a2) | Dec 10, 2022 |
| Acer          | Aspire V5-573               | Notebook    | [1d88db5ee2](https://linux-hardware.org/?probe=1d88db5ee2) | Dec 10, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [4f392d3575](https://linux-hardware.org/?probe=4f392d3575) | Dec 10, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [d53608f3e3](https://linux-hardware.org/?probe=d53608f3e3) | Dec 10, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [344383d85d](https://linux-hardware.org/?probe=344383d85d) | Dec 10, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [e0584a11c0](https://linux-hardware.org/?probe=e0584a11c0) | Dec 10, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [0dc9bb1cf4](https://linux-hardware.org/?probe=0dc9bb1cf4) | Dec 09, 2022 |
| Lenovo        | ThinkCentre M70e 0829RB4    | Desktop     | [5a5b271c35](https://linux-hardware.org/?probe=5a5b271c35) | Dec 09, 2022 |
| HP            | 18E7                        | Desktop     | [9759493e06](https://linux-hardware.org/?probe=9759493e06) | Dec 09, 2022 |
| ASRock        | 945GCM-S                    | Desktop     | [926787ea67](https://linux-hardware.org/?probe=926787ea67) | Dec 09, 2022 |
| Positivo      | Mobile                      | Notebook    | [bc5f4e6c85](https://linux-hardware.org/?probe=bc5f4e6c85) | Dec 09, 2022 |
| Acer          | TravelMate 5720             | Notebook    | [d0a54f621e](https://linux-hardware.org/?probe=d0a54f621e) | Dec 09, 2022 |
| Acer          | Aspire A515-52              | Notebook    | [99e671f55f](https://linux-hardware.org/?probe=99e671f55f) | Dec 09, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [945412b0cc](https://linux-hardware.org/?probe=945412b0cc) | Dec 09, 2022 |
| Dell          | 0P301D A02                  | Desktop     | [8ab7a916f1](https://linux-hardware.org/?probe=8ab7a916f1) | Dec 08, 2022 |
| HP            | 15                          | Notebook    | [20dfd7b8f5](https://linux-hardware.org/?probe=20dfd7b8f5) | Dec 08, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [29337f7359](https://linux-hardware.org/?probe=29337f7359) | Dec 08, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [0203e79add](https://linux-hardware.org/?probe=0203e79add) | Dec 08, 2022 |
| Packard Be... | DOT S                       | Notebook    | [753f17a658](https://linux-hardware.org/?probe=753f17a658) | Dec 08, 2022 |
| Lenovo        | ThinkPad L530 24783R8       | Notebook    | [406c066d36](https://linux-hardware.org/?probe=406c066d36) | Dec 08, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [469f0a1d1f](https://linux-hardware.org/?probe=469f0a1d1f) | Dec 07, 2022 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [dabda33265](https://linux-hardware.org/?probe=dabda33265) | Dec 07, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [3ab56a93d6](https://linux-hardware.org/?probe=3ab56a93d6) | Dec 07, 2022 |
| Toshiba       | Satellite C855              | Notebook    | [1a35ba24c1](https://linux-hardware.org/?probe=1a35ba24c1) | Dec 07, 2022 |
| ASUSTek       | K53SV                       | Notebook    | [a745b1ead9](https://linux-hardware.org/?probe=a745b1ead9) | Dec 07, 2022 |
| Positivo      | H14BT58                     | Notebook    | [c038df5c8c](https://linux-hardware.org/?probe=c038df5c8c) | Dec 07, 2022 |
| MAXSUN        | MS-TZZ A320M.2-VH           | Desktop     | [c3fc86b5d4](https://linux-hardware.org/?probe=c3fc86b5d4) | Dec 06, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [741c3e22b7](https://linux-hardware.org/?probe=741c3e22b7) | Dec 06, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [664d064b07](https://linux-hardware.org/?probe=664d064b07) | Dec 06, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [b0bc15145c](https://linux-hardware.org/?probe=b0bc15145c) | Dec 06, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [13ca001c57](https://linux-hardware.org/?probe=13ca001c57) | Dec 06, 2022 |
| HP            | 15                          | Notebook    | [e5a0cdc9de](https://linux-hardware.org/?probe=e5a0cdc9de) | Dec 06, 2022 |
| Lenovo        | 0x36A017AA 31900058 STD     | Desktop     | [ccc212b757](https://linux-hardware.org/?probe=ccc212b757) | Dec 06, 2022 |
| Dell          | Latitude E6540              | Notebook    | [20786b000c](https://linux-hardware.org/?probe=20786b000c) | Dec 05, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [a4a47ea164](https://linux-hardware.org/?probe=a4a47ea164) | Dec 05, 2022 |
| Intel         | HURONRIVER                  | Desktop     | [d8a4f4a923](https://linux-hardware.org/?probe=d8a4f4a923) | Dec 05, 2022 |
| HP            | ProLiant ML350e Gen8        | Desktop     | [984fe41e3c](https://linux-hardware.org/?probe=984fe41e3c) | Dec 05, 2022 |
| ECS           | 945P/PL-A                   | Desktop     | [8db8eec28d](https://linux-hardware.org/?probe=8db8eec28d) | Dec 05, 2022 |
| HP            | Pavilion dv6000 (RV009UA... | Notebook    | [6dcd661136](https://linux-hardware.org/?probe=6dcd661136) | Dec 05, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [fa3aeacc17](https://linux-hardware.org/?probe=fa3aeacc17) | Dec 05, 2022 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [1bf4364f61](https://linux-hardware.org/?probe=1bf4364f61) | Dec 05, 2022 |
| Dell          | 0M863N A01                  | Desktop     | [ee8183087b](https://linux-hardware.org/?probe=ee8183087b) | Dec 04, 2022 |
| Positivo      | POS-PIQ77CL POSITIVO        | Desktop     | [e98fcde376](https://linux-hardware.org/?probe=e98fcde376) | Dec 04, 2022 |
| Sony          | VPCEL2S1E                   | Notebook    | [0c98b9d570](https://linux-hardware.org/?probe=0c98b9d570) | Dec 04, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [af63449087](https://linux-hardware.org/?probe=af63449087) | Dec 04, 2022 |
| Lenovo        | G770 20089                  | Notebook    | [d35d60f972](https://linux-hardware.org/?probe=d35d60f972) | Dec 04, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [ef7a013f9b](https://linux-hardware.org/?probe=ef7a013f9b) | Dec 04, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [fd9114a304](https://linux-hardware.org/?probe=fd9114a304) | Dec 04, 2022 |
| ACTION        | ACTINA GA-G31M-S2L          | Desktop     | [2a2934f919](https://linux-hardware.org/?probe=2a2934f919) | Dec 04, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [7bde8b90c7](https://linux-hardware.org/?probe=7bde8b90c7) | Dec 04, 2022 |
| Sony          | VGN-NW31JF_S                | Notebook    | [ebfbfb034a](https://linux-hardware.org/?probe=ebfbfb034a) | Dec 04, 2022 |
| ASUSTek       | K42F                        | Notebook    | [05ddce411d](https://linux-hardware.org/?probe=05ddce411d) | Dec 04, 2022 |
| Acer          | Aspire 5750                 | Notebook    | [bfe28498bd](https://linux-hardware.org/?probe=bfe28498bd) | Dec 04, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [1dbda8e648](https://linux-hardware.org/?probe=1dbda8e648) | Dec 04, 2022 |
| Dell          | Latitude E5510              | Notebook    | [6027856ab6](https://linux-hardware.org/?probe=6027856ab6) | Dec 03, 2022 |
| Acer          | Aspire X3950                | Desktop     | [96044c1932](https://linux-hardware.org/?probe=96044c1932) | Dec 03, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [c79b15a3cf](https://linux-hardware.org/?probe=c79b15a3cf) | Dec 03, 2022 |
| HP            | ProBook 4530s               | Notebook    | [f8f94617e8](https://linux-hardware.org/?probe=f8f94617e8) | Dec 03, 2022 |
| HP            | 8648                        | Desktop     | [79673ee467](https://linux-hardware.org/?probe=79673ee467) | Dec 02, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [d9bba42204](https://linux-hardware.org/?probe=d9bba42204) | Dec 02, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [78f2f440eb](https://linux-hardware.org/?probe=78f2f440eb) | Dec 02, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [8a2aad437e](https://linux-hardware.org/?probe=8a2aad437e) | Dec 02, 2022 |
| Langchao      | NF5110                      | Server      | [ae8b7868da](https://linux-hardware.org/?probe=ae8b7868da) | Dec 02, 2022 |
| ASUSTek       | P7P55D PRO                  | Desktop     | [b566591b3c](https://linux-hardware.org/?probe=b566591b3c) | Dec 02, 2022 |
| Dell          | Latitude E6420              | Notebook    | [011df4cb7f](https://linux-hardware.org/?probe=011df4cb7f) | Dec 02, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [63820e3937](https://linux-hardware.org/?probe=63820e3937) | Dec 01, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [929550dc41](https://linux-hardware.org/?probe=929550dc41) | Dec 01, 2022 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [97a1793680](https://linux-hardware.org/?probe=97a1793680) | Dec 01, 2022 |
| ASUSTek       | P5K WS                      | Desktop     | [f3608476bf](https://linux-hardware.org/?probe=f3608476bf) | Dec 01, 2022 |
| Medion        | MS-7748                     | Desktop     | [0e92aa55ca](https://linux-hardware.org/?probe=0e92aa55ca) | Nov 30, 2022 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [422f84a794](https://linux-hardware.org/?probe=422f84a794) | Nov 30, 2022 |
| ASUSTek       | Z170-E                      | Desktop     | [5e68d23175](https://linux-hardware.org/?probe=5e68d23175) | Nov 30, 2022 |
| Samsung       | 550XDA                      | Notebook    | [7614fde301](https://linux-hardware.org/?probe=7614fde301) | Nov 30, 2022 |
| Medion        | MS-7800                     | Desktop     | [a5658a6933](https://linux-hardware.org/?probe=a5658a6933) | Nov 30, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [1d20e4ba6d](https://linux-hardware.org/?probe=1d20e4ba6d) | Nov 30, 2022 |
| Dell          | 0YHMCJ A01                  | Server      | [77f946c99b](https://linux-hardware.org/?probe=77f946c99b) | Nov 30, 2022 |
| MACHINIST     | X99-D8-MAX V1.0             | Desktop     | [c2430965a1](https://linux-hardware.org/?probe=c2430965a1) | Nov 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [9505f905e8](https://linux-hardware.org/?probe=9505f905e8) | Nov 30, 2022 |
| Dell          | Inspiron 5423               | Notebook    | [db57850733](https://linux-hardware.org/?probe=db57850733) | Nov 29, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [1a742c23df](https://linux-hardware.org/?probe=1a742c23df) | Nov 29, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [fa36933936](https://linux-hardware.org/?probe=fa36933936) | Nov 29, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [f03f3a9325](https://linux-hardware.org/?probe=f03f3a9325) | Nov 29, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [20219ca82a](https://linux-hardware.org/?probe=20219ca82a) | Nov 29, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [0bd83a29f4](https://linux-hardware.org/?probe=0bd83a29f4) | Nov 29, 2022 |
| ECS           | 945P/PL-A                   | Desktop     | [ff47651dd8](https://linux-hardware.org/?probe=ff47651dd8) | Nov 29, 2022 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [d89a05dd31](https://linux-hardware.org/?probe=d89a05dd31) | Nov 29, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d20243efed](https://linux-hardware.org/?probe=d20243efed) | Nov 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [97c63f232d](https://linux-hardware.org/?probe=97c63f232d) | Nov 28, 2022 |
| Toshiba       | Satellite L875              | Notebook    | [2d5e211d72](https://linux-hardware.org/?probe=2d5e211d72) | Nov 28, 2022 |
| Toshiba       | PORTEGE Z30t-A              | Notebook    | [8af94993bd](https://linux-hardware.org/?probe=8af94993bd) | Nov 28, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [51d2b67ca3](https://linux-hardware.org/?probe=51d2b67ca3) | Nov 28, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [e479f87a66](https://linux-hardware.org/?probe=e479f87a66) | Nov 28, 2022 |
| Medion        | E11201                      | Notebook    | [0838f9db75](https://linux-hardware.org/?probe=0838f9db75) | Nov 27, 2022 |
| Gateway       | M-1631U                     | Notebook    | [f0f0517dab](https://linux-hardware.org/?probe=f0f0517dab) | Nov 27, 2022 |
| Medion        | E2292                       | Convertible | [98818a6a22](https://linux-hardware.org/?probe=98818a6a22) | Nov 27, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [31f70fbb3e](https://linux-hardware.org/?probe=31f70fbb3e) | Nov 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [c218724cb4](https://linux-hardware.org/?probe=c218724cb4) | Nov 27, 2022 |
| MSI           | Z77MA-G45                   | Desktop     | [feb165c344](https://linux-hardware.org/?probe=feb165c344) | Nov 27, 2022 |
| ASRock        | A88M-G                      | Desktop     | [323199813d](https://linux-hardware.org/?probe=323199813d) | Nov 27, 2022 |
| Lenovo        | 3000 N500 42336DS           | Notebook    | [f3d917b782](https://linux-hardware.org/?probe=f3d917b782) | Nov 26, 2022 |
| MSI           | P55-CD53                    | Desktop     | [a602949484](https://linux-hardware.org/?probe=a602949484) | Nov 26, 2022 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [b680eec959](https://linux-hardware.org/?probe=b680eec959) | Nov 26, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [06c7fdf5c9](https://linux-hardware.org/?probe=06c7fdf5c9) | Nov 26, 2022 |
| Dell          | Latitude E6220              | Notebook    | [aa8d2d2fc7](https://linux-hardware.org/?probe=aa8d2d2fc7) | Nov 26, 2022 |
| HP            | 3397                        | Desktop     | [c943f7435d](https://linux-hardware.org/?probe=c943f7435d) | Nov 26, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [d70d7496df](https://linux-hardware.org/?probe=d70d7496df) | Nov 26, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [9419d2017e](https://linux-hardware.org/?probe=9419d2017e) | Nov 26, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [1eb32c408c](https://linux-hardware.org/?probe=1eb32c408c) | Nov 26, 2022 |
| HP            | 0AECh D                     | Desktop     | [857616948b](https://linux-hardware.org/?probe=857616948b) | Nov 26, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [3413fb7947](https://linux-hardware.org/?probe=3413fb7947) | Nov 26, 2022 |
| HP            | 1589                        | Desktop     | [077a89fb54](https://linux-hardware.org/?probe=077a89fb54) | Nov 26, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [7948a35f59](https://linux-hardware.org/?probe=7948a35f59) | Nov 25, 2022 |
| Acer          | NC-ES1-512-C3AH             | Notebook    | [0670f9ed15](https://linux-hardware.org/?probe=0670f9ed15) | Nov 25, 2022 |
| HP            | 2215                        | Desktop     | [0134898651](https://linux-hardware.org/?probe=0134898651) | Nov 25, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [9f49ff06cf](https://linux-hardware.org/?probe=9f49ff06cf) | Nov 24, 2022 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [418849100f](https://linux-hardware.org/?probe=418849100f) | Nov 24, 2022 |
| HP            | 650                         | Notebook    | [15c69c43ca](https://linux-hardware.org/?probe=15c69c43ca) | Nov 24, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [e7bf51183d](https://linux-hardware.org/?probe=e7bf51183d) | Nov 24, 2022 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [7d448ab5cc](https://linux-hardware.org/?probe=7d448ab5cc) | Nov 24, 2022 |
| HP            | ProBook 430 G3              | Notebook    | [0fa29b61e3](https://linux-hardware.org/?probe=0fa29b61e3) | Nov 24, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [600e3f0f09](https://linux-hardware.org/?probe=600e3f0f09) | Nov 24, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [adcb4db30d](https://linux-hardware.org/?probe=adcb4db30d) | Nov 24, 2022 |
| Unknown       | Unknown                     | Notebook    | [9b50d75b30](https://linux-hardware.org/?probe=9b50d75b30) | Nov 24, 2022 |
| Foxconn       | 2A92                        | Desktop     | [e21715c047](https://linux-hardware.org/?probe=e21715c047) | Nov 24, 2022 |
| Supermicro    | PDSMi+                      | Desktop     | [3a70b82d42](https://linux-hardware.org/?probe=3a70b82d42) | Nov 24, 2022 |
| Intel         | B75                         | Desktop     | [a8932d4a21](https://linux-hardware.org/?probe=a8932d4a21) | Nov 24, 2022 |
| Lenovo        | ThinkPad T420 4180GH5       | Notebook    | [8dba4b2123](https://linux-hardware.org/?probe=8dba4b2123) | Nov 23, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [3be30a3d31](https://linux-hardware.org/?probe=3be30a3d31) | Nov 23, 2022 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [67cc68fbfe](https://linux-hardware.org/?probe=67cc68fbfe) | Nov 23, 2022 |
| HP            | 8582 01100                  | All in one  | [4977f9d91d](https://linux-hardware.org/?probe=4977f9d91d) | Nov 23, 2022 |
| Sony          | VPCEG16EG                   | Notebook    | [ee22559858](https://linux-hardware.org/?probe=ee22559858) | Nov 23, 2022 |
| Dell          | 0M863N A01                  | Desktop     | [ca7e5eab8d](https://linux-hardware.org/?probe=ca7e5eab8d) | Nov 23, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [eca478ef1d](https://linux-hardware.org/?probe=eca478ef1d) | Nov 23, 2022 |
| HP            | Notebook                    | Notebook    | [616c071073](https://linux-hardware.org/?probe=616c071073) | Nov 23, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [063ffbb0e8](https://linux-hardware.org/?probe=063ffbb0e8) | Nov 23, 2022 |
| Lenovo        | IdeaPad U310 Touch          | Notebook    | [09beadc5ae](https://linux-hardware.org/?probe=09beadc5ae) | Nov 22, 2022 |
| Intel         | DG41TY AAE47335-302         | Desktop     | [ae2fb8d0b3](https://linux-hardware.org/?probe=ae2fb8d0b3) | Nov 22, 2022 |
| Intel         | powered classmate PC        | Notebook    | [d74f69f66a](https://linux-hardware.org/?probe=d74f69f66a) | Nov 22, 2022 |
| Lenovo        | ThinkPad R500 2716AZJ       | Notebook    | [ecf18761e4](https://linux-hardware.org/?probe=ecf18761e4) | Nov 22, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [1c7b4c3780](https://linux-hardware.org/?probe=1c7b4c3780) | Nov 21, 2022 |
| Dell          | Latitude E6410              | Notebook    | [22585074f3](https://linux-hardware.org/?probe=22585074f3) | Nov 21, 2022 |
| HP            | 3399                        | Desktop     | [bce6df1ffb](https://linux-hardware.org/?probe=bce6df1ffb) | Nov 21, 2022 |
| ASUSTek       | F1A55-M LE                  | Desktop     | [f2120128c1](https://linux-hardware.org/?probe=f2120128c1) | Nov 21, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [cd65013120](https://linux-hardware.org/?probe=cd65013120) | Nov 21, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [4792cdbba2](https://linux-hardware.org/?probe=4792cdbba2) | Nov 21, 2022 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | Desktop     | [ec30826806](https://linux-hardware.org/?probe=ec30826806) | Nov 21, 2022 |
| Pegatron      | NARRA5                      | Desktop     | [d8632e2872](https://linux-hardware.org/?probe=d8632e2872) | Nov 21, 2022 |
| ASRock        | P67 Extreme4                | Desktop     | [569fd8178d](https://linux-hardware.org/?probe=569fd8178d) | Nov 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [049f06f11d](https://linux-hardware.org/?probe=049f06f11d) | Nov 21, 2022 |
| AZW           | SEi                         | Desktop     | [a8e813c483](https://linux-hardware.org/?probe=a8e813c483) | Nov 21, 2022 |
| Dell          | 00NNT0 A00                  | Desktop     | [c25787d8b9](https://linux-hardware.org/?probe=c25787d8b9) | Nov 20, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [880e6565e8](https://linux-hardware.org/?probe=880e6565e8) | Nov 20, 2022 |
| Alienware     | M17xR3                      | Notebook    | [d472e55685](https://linux-hardware.org/?probe=d472e55685) | Nov 20, 2022 |
| Sony          | VPCEB2M1E                   | Notebook    | [eeefed51e4](https://linux-hardware.org/?probe=eeefed51e4) | Nov 20, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [733140c078](https://linux-hardware.org/?probe=733140c078) | Nov 20, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [7d3f0e5604](https://linux-hardware.org/?probe=7d3f0e5604) | Nov 20, 2022 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [5b31194732](https://linux-hardware.org/?probe=5b31194732) | Nov 20, 2022 |
| Chuwi         | LapBook SE                  | Notebook    | [ecc56a3703](https://linux-hardware.org/?probe=ecc56a3703) | Nov 19, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [45a5881e61](https://linux-hardware.org/?probe=45a5881e61) | Nov 19, 2022 |
| Shuttle       | FS61                        | Desktop     | [7a940c8fa3](https://linux-hardware.org/?probe=7a940c8fa3) | Nov 19, 2022 |
| Lenovo        | S145-15API 81UT             | Notebook    | [fd832d05e2](https://linux-hardware.org/?probe=fd832d05e2) | Nov 19, 2022 |
| HP            | Pavilion g7                 | Notebook    | [fae1d08109](https://linux-hardware.org/?probe=fae1d08109) | Nov 19, 2022 |
| Pegatron      | 2A94h                       | Desktop     | [be99475703](https://linux-hardware.org/?probe=be99475703) | Nov 19, 2022 |
| HP            | Pavilion dm4                | Notebook    | [d90ac7b5c2](https://linux-hardware.org/?probe=d90ac7b5c2) | Nov 19, 2022 |
| ECS           | G41T-M7                     | Desktop     | [f97036df33](https://linux-hardware.org/?probe=f97036df33) | Nov 18, 2022 |
| Intel         | X99                         | Desktop     | [c95c1d173b](https://linux-hardware.org/?probe=c95c1d173b) | Nov 18, 2022 |
| TPV-INVENT... | 2AC6 A01                    | Desktop     | [04b3ba4242](https://linux-hardware.org/?probe=04b3ba4242) | Nov 18, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [fc7b21bd04](https://linux-hardware.org/?probe=fc7b21bd04) | Nov 18, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [c2ad29d3e8](https://linux-hardware.org/?probe=c2ad29d3e8) | Nov 18, 2022 |
| HP            | Notebook                    | Notebook    | [ded915d6cd](https://linux-hardware.org/?probe=ded915d6cd) | Nov 18, 2022 |
| Fujitsu Si... | D2364-A3 S26361-D2364-A3    | Desktop     | [62ce7f9a0b](https://linux-hardware.org/?probe=62ce7f9a0b) | Nov 18, 2022 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [b1d1b0ad4c](https://linux-hardware.org/?probe=b1d1b0ad4c) | Nov 18, 2022 |
| HP            | Presario CQ43               | Notebook    | [0ed80872c0](https://linux-hardware.org/?probe=0ed80872c0) | Nov 18, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [c27978fdc4](https://linux-hardware.org/?probe=c27978fdc4) | Nov 18, 2022 |
| Acer          | Aspire 6930G                | Notebook    | [05ad62f97d](https://linux-hardware.org/?probe=05ad62f97d) | Nov 17, 2022 |
| Packard Be... | EasyNote TK81               | Notebook    | [c396423368](https://linux-hardware.org/?probe=c396423368) | Nov 17, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [dd25be7aef](https://linux-hardware.org/?probe=dd25be7aef) | Nov 17, 2022 |
| ASUSTek       | K54HR                       | Notebook    | [ba95174feb](https://linux-hardware.org/?probe=ba95174feb) | Nov 17, 2022 |
| Compaq        | 420                         | Notebook    | [07ab1c2b0f](https://linux-hardware.org/?probe=07ab1c2b0f) | Nov 17, 2022 |
| Dell          | 0FDT3J A03                  | Server      | [438f28559c](https://linux-hardware.org/?probe=438f28559c) | Nov 16, 2022 |
| ASUSTek       | P5KPL/1600                  | Desktop     | [24b13d1967](https://linux-hardware.org/?probe=24b13d1967) | Nov 16, 2022 |
| HP            | 843B                        | Desktop     | [373e5cc61d](https://linux-hardware.org/?probe=373e5cc61d) | Nov 16, 2022 |
| Intel         | H61                         | Desktop     | [faeac27433](https://linux-hardware.org/?probe=faeac27433) | Nov 16, 2022 |
| Medion        | MS-7728                     | Desktop     | [813d86814d](https://linux-hardware.org/?probe=813d86814d) | Nov 16, 2022 |
| MSI           | CR620                       | Notebook    | [4d90de18ca](https://linux-hardware.org/?probe=4d90de18ca) | Nov 16, 2022 |
| Acer          | Veriton N4630G              | Desktop     | [f4566a57a9](https://linux-hardware.org/?probe=f4566a57a9) | Nov 16, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [9c25ade74d](https://linux-hardware.org/?probe=9c25ade74d) | Nov 16, 2022 |
| Toshiba       | Satellite Pro U500          | Notebook    | [064a36a5bb](https://linux-hardware.org/?probe=064a36a5bb) | Nov 16, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [6f3ecf327d](https://linux-hardware.org/?probe=6f3ecf327d) | Nov 16, 2022 |
| ALDO          | C2016-BSWI-D2               | Desktop     | [0e4c4c6806](https://linux-hardware.org/?probe=0e4c4c6806) | Nov 16, 2022 |
| AZW           | Gemini M                    | Desktop     | [683123c4f5](https://linux-hardware.org/?probe=683123c4f5) | Nov 16, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [3f95d3f191](https://linux-hardware.org/?probe=3f95d3f191) | Nov 15, 2022 |
| LDLC          | SPC-N                       | Notebook    | [acec489419](https://linux-hardware.org/?probe=acec489419) | Nov 15, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [ff63827781](https://linux-hardware.org/?probe=ff63827781) | Nov 15, 2022 |
| Dell          | 0UR033 A00                  | Server      | [2ff8924b15](https://linux-hardware.org/?probe=2ff8924b15) | Nov 15, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [6cb0948dfd](https://linux-hardware.org/?probe=6cb0948dfd) | Nov 15, 2022 |
| MSI           | H61M-P31/W8                 | Desktop     | [a7d3a01ab2](https://linux-hardware.org/?probe=a7d3a01ab2) | Nov 15, 2022 |
| ASUSTek       | N751JX                      | Notebook    | [cea52af467](https://linux-hardware.org/?probe=cea52af467) | Nov 14, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [298f1bd357](https://linux-hardware.org/?probe=298f1bd357) | Nov 14, 2022 |
| HP            | 22F8                        | Desktop     | [754ebee9c8](https://linux-hardware.org/?probe=754ebee9c8) | Nov 14, 2022 |
| Lenovo        | G550 20023                  | Notebook    | [80be7e8e25](https://linux-hardware.org/?probe=80be7e8e25) | Nov 14, 2022 |
| Lenovo        | ThinkPad T470p 20J6CTO1W... | Notebook    | [4121297e16](https://linux-hardware.org/?probe=4121297e16) | Nov 14, 2022 |
| Sony          | SVE1411EGXB                 | Notebook    | [dafea482eb](https://linux-hardware.org/?probe=dafea482eb) | Nov 14, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [2d904e2be7](https://linux-hardware.org/?probe=2d904e2be7) | Nov 13, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [9506350a75](https://linux-hardware.org/?probe=9506350a75) | Nov 13, 2022 |
| Lenovo        | 0x36C4 SDK0K17763 WIN 18... | All in one  | [7a3f735fc0](https://linux-hardware.org/?probe=7a3f735fc0) | Nov 13, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [9ef06fcef1](https://linux-hardware.org/?probe=9ef06fcef1) | Nov 13, 2022 |
| HP            | 84FD                        | Desktop     | [6ee4b6828c](https://linux-hardware.org/?probe=6ee4b6828c) | Nov 13, 2022 |
| Deltron       | H81H3-M4                    | Desktop     | [49530f2e0b](https://linux-hardware.org/?probe=49530f2e0b) | Nov 13, 2022 |
| MSI           | H97 GUARD-PRO               | Desktop     | [3ea9d7a74a](https://linux-hardware.org/?probe=3ea9d7a74a) | Nov 13, 2022 |
| Gigabyte      | H87-HD3                     | Desktop     | [e5a8d4700d](https://linux-hardware.org/?probe=e5a8d4700d) | Nov 12, 2022 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [c5952a73e7](https://linux-hardware.org/?probe=c5952a73e7) | Nov 12, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [052f42f29a](https://linux-hardware.org/?probe=052f42f29a) | Nov 12, 2022 |
| Fujitsu       | LIFEBOOK E782               | Notebook    | [f6b2530682](https://linux-hardware.org/?probe=f6b2530682) | Nov 12, 2022 |
| HP            | ProBook 455 G2              | Notebook    | [1a5d0a1618](https://linux-hardware.org/?probe=1a5d0a1618) | Nov 12, 2022 |
| Dell          | Vostro 3300                 | Notebook    | [be3a3b081d](https://linux-hardware.org/?probe=be3a3b081d) | Nov 12, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [d5166a002a](https://linux-hardware.org/?probe=d5166a002a) | Nov 11, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [d710968897](https://linux-hardware.org/?probe=d710968897) | Nov 11, 2022 |
| Toshiba       | Satellite C870-D7K          | Notebook    | [b2f60a1b4d](https://linux-hardware.org/?probe=b2f60a1b4d) | Nov 11, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [fa27762189](https://linux-hardware.org/?probe=fa27762189) | Nov 11, 2022 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [d5e58b3718](https://linux-hardware.org/?probe=d5e58b3718) | Nov 11, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [19dc931962](https://linux-hardware.org/?probe=19dc931962) | Nov 10, 2022 |
| MSI           | U270DX                      | Notebook    | [2a68a6ba02](https://linux-hardware.org/?probe=2a68a6ba02) | Nov 10, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [aa006ea111](https://linux-hardware.org/?probe=aa006ea111) | Nov 10, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [4488e0a71a](https://linux-hardware.org/?probe=4488e0a71a) | Nov 10, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [0e624570e1](https://linux-hardware.org/?probe=0e624570e1) | Nov 10, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [8d43f2e3fc](https://linux-hardware.org/?probe=8d43f2e3fc) | Nov 10, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [5a5633f611](https://linux-hardware.org/?probe=5a5633f611) | Nov 09, 2022 |
| Acer          | RS880M05                    | Desktop     | [cb216f090c](https://linux-hardware.org/?probe=cb216f090c) | Nov 09, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [673c961915](https://linux-hardware.org/?probe=673c961915) | Nov 09, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [8383f208a6](https://linux-hardware.org/?probe=8383f208a6) | Nov 09, 2022 |
| Fujitsu       | FMVXN4MN2Z                  | Notebook    | [7a08a94b1e](https://linux-hardware.org/?probe=7a08a94b1e) | Nov 09, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [fb87099a0d](https://linux-hardware.org/?probe=fb87099a0d) | Nov 09, 2022 |
| Dell          | 0V52N7 A02                  | Server      | [3151a21ebf](https://linux-hardware.org/?probe=3151a21ebf) | Nov 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [c46b9195f3](https://linux-hardware.org/?probe=c46b9195f3) | Nov 09, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [ac916f47fc](https://linux-hardware.org/?probe=ac916f47fc) | Nov 08, 2022 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [a41a51330d](https://linux-hardware.org/?probe=a41a51330d) | Nov 08, 2022 |
| HP            | Pavilion dv2700             | Notebook    | [a8e36a1579](https://linux-hardware.org/?probe=a8e36a1579) | Nov 08, 2022 |
| Acer          | Aspire X1700                | Desktop     | [764516b8f0](https://linux-hardware.org/?probe=764516b8f0) | Nov 08, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [a22087073b](https://linux-hardware.org/?probe=a22087073b) | Nov 08, 2022 |
| Dell          | Latitude E6400              | Notebook    | [22ccbac81a](https://linux-hardware.org/?probe=22ccbac81a) | Nov 07, 2022 |
| HP            | Notebook                    | Notebook    | [0164126ac9](https://linux-hardware.org/?probe=0164126ac9) | Nov 07, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [f0b56da15d](https://linux-hardware.org/?probe=f0b56da15d) | Nov 07, 2022 |
| HP            | ProBook 4530s               | Notebook    | [afb0629ea9](https://linux-hardware.org/?probe=afb0629ea9) | Nov 07, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [b6768dd5b7](https://linux-hardware.org/?probe=b6768dd5b7) | Nov 07, 2022 |
| ASUSTek       | K53E                        | Notebook    | [07d6d01b99](https://linux-hardware.org/?probe=07d6d01b99) | Nov 06, 2022 |
| HP            | Notebook                    | Notebook    | [59b70f4c7c](https://linux-hardware.org/?probe=59b70f4c7c) | Nov 06, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [09c5b6e39e](https://linux-hardware.org/?probe=09c5b6e39e) | Nov 06, 2022 |
| Pegatron      | 2AE3                        | Desktop     | [19ae75aacc](https://linux-hardware.org/?probe=19ae75aacc) | Nov 06, 2022 |
| Lenovo        | G485 20136                  | Notebook    | [f8ee5082f8](https://linux-hardware.org/?probe=f8ee5082f8) | Nov 06, 2022 |
| ASRock        | 4CoreDual-SATA2             | Desktop     | [e1a81edea7](https://linux-hardware.org/?probe=e1a81edea7) | Nov 05, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [8aec7634ab](https://linux-hardware.org/?probe=8aec7634ab) | Nov 05, 2022 |
| Acer          | TravelMate P259-G2-M        | Notebook    | [4a85f586b3](https://linux-hardware.org/?probe=4a85f586b3) | Nov 05, 2022 |
| Acer          | Aspire A717-71G             | Notebook    | [a6fa794196](https://linux-hardware.org/?probe=a6fa794196) | Nov 05, 2022 |
| ASUSTek       | K56CM                       | Notebook    | [c93289dc28](https://linux-hardware.org/?probe=c93289dc28) | Nov 05, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [e2cadc512e](https://linux-hardware.org/?probe=e2cadc512e) | Nov 05, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [5ffd5ed23d](https://linux-hardware.org/?probe=5ffd5ed23d) | Nov 05, 2022 |
| HP            | 2820h                       | Desktop     | [6378a2e9c3](https://linux-hardware.org/?probe=6378a2e9c3) | Nov 05, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [c125fc089c](https://linux-hardware.org/?probe=c125fc089c) | Nov 05, 2022 |
| VS Company    | MCP61M                      | Desktop     | [ef6adc510d](https://linux-hardware.org/?probe=ef6adc510d) | Nov 05, 2022 |
| Lenovo        | ThinkPad L520 78596CG       | Notebook    | [094f09bcf8](https://linux-hardware.org/?probe=094f09bcf8) | Nov 04, 2022 |
| Toshiba       | Satellite Pro A200          | Notebook    | [09ae3b0b13](https://linux-hardware.org/?probe=09ae3b0b13) | Nov 04, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMC    | Notebook    | [010fd86c32](https://linux-hardware.org/?probe=010fd86c32) | Nov 04, 2022 |
| Lenovo        | B50-45 80F0                 | Notebook    | [2d36803ec6](https://linux-hardware.org/?probe=2d36803ec6) | Nov 04, 2022 |
| ASUSTek       | H170I-PLUS D3               | Desktop     | [74df37995c](https://linux-hardware.org/?probe=74df37995c) | Nov 04, 2022 |
| ASUSTek       | K50IN                       | Notebook    | [8c069a1707](https://linux-hardware.org/?probe=8c069a1707) | Nov 03, 2022 |
| Packard Be... | EasyNote MZ45               | Notebook    | [93dada1577](https://linux-hardware.org/?probe=93dada1577) | Nov 03, 2022 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [1d618807a7](https://linux-hardware.org/?probe=1d618807a7) | Nov 03, 2022 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [e2e281d38d](https://linux-hardware.org/?probe=e2e281d38d) | Nov 03, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | Desktop     | [bdc77dbc53](https://linux-hardware.org/?probe=bdc77dbc53) | Nov 03, 2022 |
| Samsung       | 400B2B/400B2B               | Notebook    | [a909b4b203](https://linux-hardware.org/?probe=a909b4b203) | Nov 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [f9f727f7e5](https://linux-hardware.org/?probe=f9f727f7e5) | Nov 02, 2022 |
| HP            | ENVY m6                     | Notebook    | [9043724da5](https://linux-hardware.org/?probe=9043724da5) | Nov 02, 2022 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [83a1fc191a](https://linux-hardware.org/?probe=83a1fc191a) | Nov 02, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [0a79270558](https://linux-hardware.org/?probe=0a79270558) | Nov 02, 2022 |
| Panasonic     | CF-C1BWFBZ1M                | Notebook    | [18a81d5db2](https://linux-hardware.org/?probe=18a81d5db2) | Nov 02, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [44f768478e](https://linux-hardware.org/?probe=44f768478e) | Nov 02, 2022 |
| Acer          | Aspire X1430                | Desktop     | [f48a8d45d8](https://linux-hardware.org/?probe=f48a8d45d8) | Nov 01, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [44c6e56cd9](https://linux-hardware.org/?probe=44c6e56cd9) | Nov 01, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [0470f02ccb](https://linux-hardware.org/?probe=0470f02ccb) | Nov 01, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [67e15a659d](https://linux-hardware.org/?probe=67e15a659d) | Oct 31, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [8b208b8383](https://linux-hardware.org/?probe=8b208b8383) | Oct 31, 2022 |
| Acer          | Extensa 5635Z               | Notebook    | [35ce596e08](https://linux-hardware.org/?probe=35ce596e08) | Oct 31, 2022 |
| ASUSTek       | M4A78 PLUS                  | Desktop     | [bac044cd22](https://linux-hardware.org/?probe=bac044cd22) | Oct 31, 2022 |
| Dell          | Latitude E5500              | Notebook    | [c64399793c](https://linux-hardware.org/?probe=c64399793c) | Oct 31, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c23efa8caa](https://linux-hardware.org/?probe=c23efa8caa) | Oct 31, 2022 |
| Dell          | Latitude E6400              | Notebook    | [8f2639b285](https://linux-hardware.org/?probe=8f2639b285) | Oct 31, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [598d815c17](https://linux-hardware.org/?probe=598d815c17) | Oct 31, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [acfa0d90d6](https://linux-hardware.org/?probe=acfa0d90d6) | Oct 31, 2022 |
| Pegatron      | IPPCR-SS                    | Desktop     | [9427da0212](https://linux-hardware.org/?probe=9427da0212) | Oct 31, 2022 |
| Intel         | powered classmate PC        | Notebook    | [5555da7553](https://linux-hardware.org/?probe=5555da7553) | Oct 31, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [202065a62d](https://linux-hardware.org/?probe=202065a62d) | Oct 30, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [5f7d9d2a04](https://linux-hardware.org/?probe=5f7d9d2a04) | Oct 30, 2022 |
| Prestigio     | PSB133S01ZFP                | Notebook    | [e10becbd35](https://linux-hardware.org/?probe=e10becbd35) | Oct 30, 2022 |
| Dell          | Latitude E7240              | Notebook    | [7605a5bf1c](https://linux-hardware.org/?probe=7605a5bf1c) | Oct 30, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [12b6232cdd](https://linux-hardware.org/?probe=12b6232cdd) | Oct 30, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [f8bdcbce4e](https://linux-hardware.org/?probe=f8bdcbce4e) | Oct 29, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [2a7d6b757b](https://linux-hardware.org/?probe=2a7d6b757b) | Oct 29, 2022 |
| Dell          | Studio 1737                 | Notebook    | [97f398804e](https://linux-hardware.org/?probe=97f398804e) | Oct 29, 2022 |
| HP            | Compaq 615                  | Notebook    | [ae90fa3742](https://linux-hardware.org/?probe=ae90fa3742) | Oct 29, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [6e9cb9c0e0](https://linux-hardware.org/?probe=6e9cb9c0e0) | Oct 29, 2022 |
| MSI           | P45 Platinum                | Desktop     | [5507d45c35](https://linux-hardware.org/?probe=5507d45c35) | Oct 29, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [ffb4369f83](https://linux-hardware.org/?probe=ffb4369f83) | Oct 29, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fc7ef1ce9a](https://linux-hardware.org/?probe=fc7ef1ce9a) | Oct 29, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [345683b134](https://linux-hardware.org/?probe=345683b134) | Oct 29, 2022 |
| ASRock        | H81M-ITX                    | Desktop     | [56f93814ea](https://linux-hardware.org/?probe=56f93814ea) | Oct 28, 2022 |
| Acer          | Aspire 5745                 | Notebook    | [2f79de6974](https://linux-hardware.org/?probe=2f79de6974) | Oct 28, 2022 |
| ASUSTek       | M5A87                       | Desktop     | [88e6b582c9](https://linux-hardware.org/?probe=88e6b582c9) | Oct 28, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [6b57390808](https://linux-hardware.org/?probe=6b57390808) | Oct 28, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [41e9e7aba7](https://linux-hardware.org/?probe=41e9e7aba7) | Oct 28, 2022 |
| HP            | Pavilion Laptop 15-cc0xx    | Notebook    | [0ca2ea7180](https://linux-hardware.org/?probe=0ca2ea7180) | Oct 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [8d93ee0286](https://linux-hardware.org/?probe=8d93ee0286) | Oct 28, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [ca5c26654a](https://linux-hardware.org/?probe=ca5c26654a) | Oct 27, 2022 |
| ASRock        | B550M-HDV                   | Desktop     | [4d5068a3be](https://linux-hardware.org/?probe=4d5068a3be) | Oct 27, 2022 |
| Acer          | Aspire 8730                 | Notebook    | [86bffd9523](https://linux-hardware.org/?probe=86bffd9523) | Oct 27, 2022 |
| Acer          | Aspire E3-112               | Notebook    | [fd34f66305](https://linux-hardware.org/?probe=fd34f66305) | Oct 26, 2022 |
| Acer          | Veriton M275                | Desktop     | [c4604d6f2a](https://linux-hardware.org/?probe=c4604d6f2a) | Oct 26, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [e2f30e0f1e](https://linux-hardware.org/?probe=e2f30e0f1e) | Oct 26, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [b50585b578](https://linux-hardware.org/?probe=b50585b578) | Oct 26, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [fa0daeab26](https://linux-hardware.org/?probe=fa0daeab26) | Oct 26, 2022 |
| Acer          | Veriton NBU                 | Desktop     | [7be04cd3ed](https://linux-hardware.org/?probe=7be04cd3ed) | Oct 25, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [2fb43f4be2](https://linux-hardware.org/?probe=2fb43f4be2) | Oct 25, 2022 |
| Acer          | Aspire ES1-571              | Notebook    | [f9f7926da2](https://linux-hardware.org/?probe=f9f7926da2) | Oct 25, 2022 |
| ASRock        | G41C-GS                     | Desktop     | [218d55e0ca](https://linux-hardware.org/?probe=218d55e0ca) | Oct 25, 2022 |
| ASUSTek       | P5Q3 DELUXE                 | Desktop     | [a25c84e8f1](https://linux-hardware.org/?probe=a25c84e8f1) | Oct 25, 2022 |
| Panasonic     | CFSX4-1                     | Notebook    | [2ddae6e0e1](https://linux-hardware.org/?probe=2ddae6e0e1) | Oct 25, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [ede3bcd3f3](https://linux-hardware.org/?probe=ede3bcd3f3) | Oct 24, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [bfa28dd791](https://linux-hardware.org/?probe=bfa28dd791) | Oct 24, 2022 |
| Dell          | 0GX297                      | Desktop     | [a047bbd7a0](https://linux-hardware.org/?probe=a047bbd7a0) | Oct 24, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [82afa0e5bc](https://linux-hardware.org/?probe=82afa0e5bc) | Oct 24, 2022 |
| Dell          | Studio 1737                 | Notebook    | [d6e17c05b2](https://linux-hardware.org/?probe=d6e17c05b2) | Oct 24, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [b7315785a1](https://linux-hardware.org/?probe=b7315785a1) | Oct 24, 2022 |
| ASUSTek       | A7U                         | Notebook    | [867f26dde1](https://linux-hardware.org/?probe=867f26dde1) | Oct 24, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [cce2975614](https://linux-hardware.org/?probe=cce2975614) | Oct 24, 2022 |
| ASUSTek       | P5QL-E                      | Desktop     | [41810c587a](https://linux-hardware.org/?probe=41810c587a) | Oct 24, 2022 |
| Acer          | TravelMate B311-31          | Notebook    | [010dd1e876](https://linux-hardware.org/?probe=010dd1e876) | Oct 24, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [683ac39f80](https://linux-hardware.org/?probe=683ac39f80) | Oct 24, 2022 |
| Packard Be... | EasyNote ENTE70BH           | Notebook    | [2135a5aed7](https://linux-hardware.org/?probe=2135a5aed7) | Oct 23, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e59cef718b](https://linux-hardware.org/?probe=e59cef718b) | Oct 23, 2022 |
| Acer          | WMCP78M                     | Desktop     | [f4e3945dea](https://linux-hardware.org/?probe=f4e3945dea) | Oct 23, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [5b61c1c241](https://linux-hardware.org/?probe=5b61c1c241) | Oct 23, 2022 |
| Lenovo        | ThinkPad X240 20AMS01M00    | Notebook    | [2f1c7b7716](https://linux-hardware.org/?probe=2f1c7b7716) | Oct 23, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [12b83ecfd4](https://linux-hardware.org/?probe=12b83ecfd4) | Oct 22, 2022 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [d806b92948](https://linux-hardware.org/?probe=d806b92948) | Oct 22, 2022 |
| Dell          | 0HX555                      | Desktop     | [86339c4a3f](https://linux-hardware.org/?probe=86339c4a3f) | Oct 22, 2022 |
| Philco        | DTC-A55                     | Desktop     | [5c7d64ff3f](https://linux-hardware.org/?probe=5c7d64ff3f) | Oct 22, 2022 |
| Acer          | WG43M                       | Desktop     | [e520a7dfca](https://linux-hardware.org/?probe=e520a7dfca) | Oct 22, 2022 |
| Gigabyte      | GA-790FXTA-UD5              | Desktop     | [78218a5b63](https://linux-hardware.org/?probe=78218a5b63) | Oct 21, 2022 |
| Dell          | Precision M6800             | Notebook    | [9b909039ee](https://linux-hardware.org/?probe=9b909039ee) | Oct 21, 2022 |
| ZOTAC         | ZBOX-QCM7T3000/EN072080S... | Mini pc     | [612f0f6e06](https://linux-hardware.org/?probe=612f0f6e06) | Oct 21, 2022 |
| MSI           | H61M-P20                    | Desktop     | [a50648c486](https://linux-hardware.org/?probe=a50648c486) | Oct 21, 2022 |
| Lenovo        | ThinkPad T520 42434WU       | Notebook    | [d118d39c58](https://linux-hardware.org/?probe=d118d39c58) | Oct 21, 2022 |
| MSI           | GT70 0NC/GT70 0NC           | Notebook    | [592b788d62](https://linux-hardware.org/?probe=592b788d62) | Oct 20, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [6c32002395](https://linux-hardware.org/?probe=6c32002395) | Oct 20, 2022 |
| Dell          | Latitude E5410              | Notebook    | [f3b5d196ef](https://linux-hardware.org/?probe=f3b5d196ef) | Oct 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [2ead6c088f](https://linux-hardware.org/?probe=2ead6c088f) | Oct 20, 2022 |
| Sony          | SVE1513B1EW                 | Notebook    | [77ef0b542b](https://linux-hardware.org/?probe=77ef0b542b) | Oct 20, 2022 |
| Dell          | 0V52N7 A01                  | Server      | [c3990d0066](https://linux-hardware.org/?probe=c3990d0066) | Oct 19, 2022 |
| Acer          | Aspire E5-574               | Notebook    | [d9797d9fa7](https://linux-hardware.org/?probe=d9797d9fa7) | Oct 19, 2022 |
| Dell          | Inspiron 13-7359            | Notebook    | [239627f1d1](https://linux-hardware.org/?probe=239627f1d1) | Oct 19, 2022 |
| HP            | 1825                        | Desktop     | [e0a35f1d0f](https://linux-hardware.org/?probe=e0a35f1d0f) | Oct 19, 2022 |
| Samsung       | 550XDA                      | Notebook    | [fcfceeaf04](https://linux-hardware.org/?probe=fcfceeaf04) | Oct 19, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [e14791bb51](https://linux-hardware.org/?probe=e14791bb51) | Oct 19, 2022 |
| HP            | 805D                        | Desktop     | [a70ef30fce](https://linux-hardware.org/?probe=a70ef30fce) | Oct 19, 2022 |
| MSI           | GE62 6QC                    | Notebook    | [92ac4fbaa6](https://linux-hardware.org/?probe=92ac4fbaa6) | Oct 19, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [770d8bf876](https://linux-hardware.org/?probe=770d8bf876) | Oct 19, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [9622704d8f](https://linux-hardware.org/?probe=9622704d8f) | Oct 18, 2022 |
| ASUSTek       | P5KPL-E                     | Desktop     | [2f1e1cbbf4](https://linux-hardware.org/?probe=2f1e1cbbf4) | Oct 18, 2022 |
| Lenovo        | G480                        | Notebook    | [984691a38d](https://linux-hardware.org/?probe=984691a38d) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [5823a0c5d0](https://linux-hardware.org/?probe=5823a0c5d0) | Oct 18, 2022 |
| HP            | Unknown                     | Notebook    | [4a0df43034](https://linux-hardware.org/?probe=4a0df43034) | Oct 17, 2022 |
| Dell          | Latitude E6330              | Notebook    | [d4d6ca7ae9](https://linux-hardware.org/?probe=d4d6ca7ae9) | Oct 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [a1e9be5323](https://linux-hardware.org/?probe=a1e9be5323) | Oct 17, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [29f6ba9612](https://linux-hardware.org/?probe=29f6ba9612) | Oct 17, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [5872b35f8c](https://linux-hardware.org/?probe=5872b35f8c) | Oct 17, 2022 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [8d9bc873e4](https://linux-hardware.org/?probe=8d9bc873e4) | Oct 17, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [9e37b60507](https://linux-hardware.org/?probe=9e37b60507) | Oct 16, 2022 |
| Dell          | Latitude E6430              | Notebook    | [2e8f3bd664](https://linux-hardware.org/?probe=2e8f3bd664) | Oct 16, 2022 |
| ASRock        | Z87 Pro3                    | Desktop     | [364a0afaff](https://linux-hardware.org/?probe=364a0afaff) | Oct 16, 2022 |
| Dell          | 0XFWHV A00                  | Desktop     | [4a5716d169](https://linux-hardware.org/?probe=4a5716d169) | Oct 16, 2022 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [b5c41a9fef](https://linux-hardware.org/?probe=b5c41a9fef) | Oct 16, 2022 |
| Dell          | Latitude E6420              | Notebook    | [913e2b1acd](https://linux-hardware.org/?probe=913e2b1acd) | Oct 15, 2022 |
| HP            | 1850                        | Desktop     | [eda9bb7861](https://linux-hardware.org/?probe=eda9bb7861) | Oct 15, 2022 |
| Lenovo        | ThinkPad L560 20F1000TJP    | Notebook    | [e9b7a4ffc2](https://linux-hardware.org/?probe=e9b7a4ffc2) | Oct 15, 2022 |
| Gigabyte      | H61M-D2H                    | Desktop     | [3c51ad7454](https://linux-hardware.org/?probe=3c51ad7454) | Oct 15, 2022 |
| Acer          | Aspire A515-44              | Notebook    | [a19fc69283](https://linux-hardware.org/?probe=a19fc69283) | Oct 15, 2022 |
| Intel         | DP45SG AAE27733-403         | Desktop     | [f391a78f4d](https://linux-hardware.org/?probe=f391a78f4d) | Oct 15, 2022 |
| LG Electro... | S460-G.BG31P1               | Notebook    | [a0b3b8e905](https://linux-hardware.org/?probe=a0b3b8e905) | Oct 15, 2022 |
| Dell          | Latitude 3340               | Notebook    | [d99dbe3b99](https://linux-hardware.org/?probe=d99dbe3b99) | Oct 14, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [720d282dfe](https://linux-hardware.org/?probe=720d282dfe) | Oct 14, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [bddc33ef5a](https://linux-hardware.org/?probe=bddc33ef5a) | Oct 14, 2022 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [1feb9942e8](https://linux-hardware.org/?probe=1feb9942e8) | Oct 14, 2022 |
| Packard Be... | EasyNote TJ66               | Notebook    | [e5f4bf84f8](https://linux-hardware.org/?probe=e5f4bf84f8) | Oct 14, 2022 |
| Compaq        | PRESARIOCQ18                | Notebook    | [5172032993](https://linux-hardware.org/?probe=5172032993) | Oct 14, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [8dc5e6f530](https://linux-hardware.org/?probe=8dc5e6f530) | Oct 14, 2022 |
| Dell          | Latitude E5440              | Notebook    | [432aa93109](https://linux-hardware.org/?probe=432aa93109) | Oct 14, 2022 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [a9f67e3f57](https://linux-hardware.org/?probe=a9f67e3f57) | Oct 13, 2022 |
| Dell          | Inspiron 5551               | Notebook    | [64865d9bb5](https://linux-hardware.org/?probe=64865d9bb5) | Oct 13, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [6144d2247a](https://linux-hardware.org/?probe=6144d2247a) | Oct 13, 2022 |
| Dell          | Precision 7720              | Notebook    | [4cadd86832](https://linux-hardware.org/?probe=4cadd86832) | Oct 13, 2022 |
| Dell          | Studio 1555                 | Notebook    | [52104abe69](https://linux-hardware.org/?probe=52104abe69) | Oct 13, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3a190d5718](https://linux-hardware.org/?probe=3a190d5718) | Oct 13, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [bccf0a4ebe](https://linux-hardware.org/?probe=bccf0a4ebe) | Oct 13, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [bb386c7d60](https://linux-hardware.org/?probe=bb386c7d60) | Oct 13, 2022 |
| Toshiba       | Satellite C855              | Notebook    | [65e0a41b8d](https://linux-hardware.org/?probe=65e0a41b8d) | Oct 13, 2022 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | Desktop     | [48ee58de23](https://linux-hardware.org/?probe=48ee58de23) | Oct 13, 2022 |
| Acer          | Aspire 7250G                | Notebook    | [34966259d6](https://linux-hardware.org/?probe=34966259d6) | Oct 13, 2022 |
| HP            | G42                         | Notebook    | [fd42e3aedb](https://linux-hardware.org/?probe=fd42e3aedb) | Oct 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [ad2b1ab7b8](https://linux-hardware.org/?probe=ad2b1ab7b8) | Oct 12, 2022 |
| Star Labs     | StarLite                    | Notebook    | [627ad33197](https://linux-hardware.org/?probe=627ad33197) | Oct 12, 2022 |
| HP            | 1497                        | Desktop     | [ff6d690da4](https://linux-hardware.org/?probe=ff6d690da4) | Oct 12, 2022 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [ff58ea3dc1](https://linux-hardware.org/?probe=ff58ea3dc1) | Oct 12, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [dc990d0395](https://linux-hardware.org/?probe=dc990d0395) | Oct 12, 2022 |
| Dell          | Latitude E6440              | Notebook    | [3b13c28e46](https://linux-hardware.org/?probe=3b13c28e46) | Oct 12, 2022 |
| AMD           | A88                         | Desktop     | [1ee2502537](https://linux-hardware.org/?probe=1ee2502537) | Oct 12, 2022 |
| Pegatron      | IPM31G                      | Desktop     | [75d4fc0b55](https://linux-hardware.org/?probe=75d4fc0b55) | Oct 12, 2022 |
| Lenovo        | ThinkPad T440s 20ARS4PR0... | Notebook    | [18c02300b9](https://linux-hardware.org/?probe=18c02300b9) | Oct 11, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [1680fa50c0](https://linux-hardware.org/?probe=1680fa50c0) | Oct 11, 2022 |
| HP            | 2171                        | Desktop     | [105af7e899](https://linux-hardware.org/?probe=105af7e899) | Oct 11, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [4bc40092b2](https://linux-hardware.org/?probe=4bc40092b2) | Oct 11, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [87cfe8ed2e](https://linux-hardware.org/?probe=87cfe8ed2e) | Oct 11, 2022 |
| Lenovo        | ThinkCentre M58 7359WES     | Desktop     | [1c00ee45c1](https://linux-hardware.org/?probe=1c00ee45c1) | Oct 11, 2022 |
| Dell          | Latitude E6540              | Notebook    | [d1b0bd16b5](https://linux-hardware.org/?probe=d1b0bd16b5) | Oct 11, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [92ab2501ea](https://linux-hardware.org/?probe=92ab2501ea) | Oct 11, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [22cf469faa](https://linux-hardware.org/?probe=22cf469faa) | Oct 10, 2022 |
| Acer          | Aspire XC-230               | Desktop     | [d213bca85f](https://linux-hardware.org/?probe=d213bca85f) | Oct 10, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [792528e3b2](https://linux-hardware.org/?probe=792528e3b2) | Oct 10, 2022 |
| Gigabyte      | 945GM-S2                    | Desktop     | [3087d063e3](https://linux-hardware.org/?probe=3087d063e3) | Oct 10, 2022 |
| ASUSTek       | PRIME H410I-PLUS            | Desktop     | [10709dd95e](https://linux-hardware.org/?probe=10709dd95e) | Oct 10, 2022 |
| HP            | 829E                        | Mini pc     | [465ec7a2fe](https://linux-hardware.org/?probe=465ec7a2fe) | Oct 10, 2022 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [a219433035](https://linux-hardware.org/?probe=a219433035) | Oct 10, 2022 |
| AZW           | U59                         | Desktop     | [8300f61a93](https://linux-hardware.org/?probe=8300f61a93) | Oct 10, 2022 |
| HP            | 805D                        | Desktop     | [8938f51322](https://linux-hardware.org/?probe=8938f51322) | Oct 09, 2022 |
| Lenovo        | Dory CRB                    | Desktop     | [33ae78632a](https://linux-hardware.org/?probe=33ae78632a) | Oct 09, 2022 |
| Dell          | Latitude E6410              | Notebook    | [4f6730e0f2](https://linux-hardware.org/?probe=4f6730e0f2) | Oct 09, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [3e7ef86329](https://linux-hardware.org/?probe=3e7ef86329) | Oct 09, 2022 |
| ASUSTek       | X550VB                      | Notebook    | [a7c1c1cb1b](https://linux-hardware.org/?probe=a7c1c1cb1b) | Oct 09, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [8d58156239](https://linux-hardware.org/?probe=8d58156239) | Oct 09, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [cf3661bb7c](https://linux-hardware.org/?probe=cf3661bb7c) | Oct 09, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [8918b1b82e](https://linux-hardware.org/?probe=8918b1b82e) | Oct 09, 2022 |
| Chuwi         | RZBOX                       | Desktop     | [76b6d7cd78](https://linux-hardware.org/?probe=76b6d7cd78) | Oct 08, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d172225c0b](https://linux-hardware.org/?probe=d172225c0b) | Oct 08, 2022 |
| MSI           | A55M-P33                    | Desktop     | [127b8f180e](https://linux-hardware.org/?probe=127b8f180e) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3665682cc6](https://linux-hardware.org/?probe=3665682cc6) | Oct 08, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [9d44a35e48](https://linux-hardware.org/?probe=9d44a35e48) | Oct 08, 2022 |
| ASRock        | M3N78D FX                   | Desktop     | [e40ba3988f](https://linux-hardware.org/?probe=e40ba3988f) | Oct 08, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [feb96964b1](https://linux-hardware.org/?probe=feb96964b1) | Oct 08, 2022 |
| Dell          | 0MN1TX A01                  | Desktop     | [a9faf44fe8](https://linux-hardware.org/?probe=a9faf44fe8) | Oct 07, 2022 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [3e7cc2c14a](https://linux-hardware.org/?probe=3e7cc2c14a) | Oct 07, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [b699753cc6](https://linux-hardware.org/?probe=b699753cc6) | Oct 07, 2022 |
| Dell          | Latitude E6400              | Notebook    | [509deb10b3](https://linux-hardware.org/?probe=509deb10b3) | Oct 07, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [9dc72dc357](https://linux-hardware.org/?probe=9dc72dc357) | Oct 07, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [8061516838](https://linux-hardware.org/?probe=8061516838) | Oct 06, 2022 |
| Toshiba       | Satellite R830              | Notebook    | [0a5299f7e0](https://linux-hardware.org/?probe=0a5299f7e0) | Oct 06, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [7a7bc387f4](https://linux-hardware.org/?probe=7a7bc387f4) | Oct 06, 2022 |
| Medion        | MS-7797                     | Desktop     | [9137d0eacf](https://linux-hardware.org/?probe=9137d0eacf) | Oct 06, 2022 |
| ASUSTek       | M2V-MX                      | Desktop     | [55b3f7f6b0](https://linux-hardware.org/?probe=55b3f7f6b0) | Oct 06, 2022 |
| HP            | 18E4                        | Desktop     | [d9deeda238](https://linux-hardware.org/?probe=d9deeda238) | Oct 05, 2022 |
| Positivo      | C14CR01                     | Notebook    | [7c0d0b2efd](https://linux-hardware.org/?probe=7c0d0b2efd) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [f9224c972e](https://linux-hardware.org/?probe=f9224c972e) | Oct 05, 2022 |
| HP            | Pavilion 17                 | Notebook    | [f7626421b2](https://linux-hardware.org/?probe=f7626421b2) | Oct 05, 2022 |
| Gigabyte      | H110M-S2PH-CF               | Desktop     | [580c13ac38](https://linux-hardware.org/?probe=580c13ac38) | Oct 05, 2022 |
| Acer          | Aspire 5250                 | Notebook    | [8a18115a5b](https://linux-hardware.org/?probe=8a18115a5b) | Oct 04, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [612b4b36a1](https://linux-hardware.org/?probe=612b4b36a1) | Oct 04, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [65103a04c3](https://linux-hardware.org/?probe=65103a04c3) | Oct 04, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [b8ad7a8464](https://linux-hardware.org/?probe=b8ad7a8464) | Oct 04, 2022 |
| Dell          | Latitude 3120               | Convertible | [60de9a1977](https://linux-hardware.org/?probe=60de9a1977) | Oct 04, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [89400b60b0](https://linux-hardware.org/?probe=89400b60b0) | Oct 04, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [5e60e8faae](https://linux-hardware.org/?probe=5e60e8faae) | Oct 04, 2022 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [8d5a649ba5](https://linux-hardware.org/?probe=8d5a649ba5) | Oct 03, 2022 |
| Intel         | H55                         | Desktop     | [73719c58ab](https://linux-hardware.org/?probe=73719c58ab) | Oct 03, 2022 |
| Dell          | Latitude E6420              | Notebook    | [cc0d33aedb](https://linux-hardware.org/?probe=cc0d33aedb) | Oct 03, 2022 |
| Acer          | TravelMate 5744             | Notebook    | [4817d4810d](https://linux-hardware.org/?probe=4817d4810d) | Oct 03, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [f6a6361e08](https://linux-hardware.org/?probe=f6a6361e08) | Oct 03, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [36b32fe8c0](https://linux-hardware.org/?probe=36b32fe8c0) | Oct 03, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [c6e6708366](https://linux-hardware.org/?probe=c6e6708366) | Oct 03, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [019702e62b](https://linux-hardware.org/?probe=019702e62b) | Oct 03, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [abfab502a6](https://linux-hardware.org/?probe=abfab502a6) | Oct 02, 2022 |
| Lenovo        | ThinkCentre M58p 6234FB9    | Desktop     | [3c772e3e1d](https://linux-hardware.org/?probe=3c772e3e1d) | Oct 02, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [d67f04fc6e](https://linux-hardware.org/?probe=d67f04fc6e) | Oct 02, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [47a7282318](https://linux-hardware.org/?probe=47a7282318) | Oct 02, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [43694e5952](https://linux-hardware.org/?probe=43694e5952) | Oct 02, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [bfd8dc3c18](https://linux-hardware.org/?probe=bfd8dc3c18) | Oct 02, 2022 |
| MSI           | A75A-G35                    | Desktop     | [66b1d71092](https://linux-hardware.org/?probe=66b1d71092) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [516795a4a8](https://linux-hardware.org/?probe=516795a4a8) | Oct 02, 2022 |
| Biostar       | A75MG                       | Desktop     | [ba1785b4b6](https://linux-hardware.org/?probe=ba1785b4b6) | Oct 02, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [a14df6d116](https://linux-hardware.org/?probe=a14df6d116) | Oct 02, 2022 |
| Lenovo        | ThinkCentre M91p 4518AU8    | Desktop     | [ce1567bb35](https://linux-hardware.org/?probe=ce1567bb35) | Oct 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [d4f76a4236](https://linux-hardware.org/?probe=d4f76a4236) | Oct 01, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [9c6340e585](https://linux-hardware.org/?probe=9c6340e585) | Oct 01, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [ba72c7ee42](https://linux-hardware.org/?probe=ba72c7ee42) | Oct 01, 2022 |
| MSI           | MS-7235                     | Desktop     | [838e2c27f1](https://linux-hardware.org/?probe=838e2c27f1) | Oct 01, 2022 |
| Lenovo        | 3000 N200 0769B4G           | Notebook    | [947f124efc](https://linux-hardware.org/?probe=947f124efc) | Oct 01, 2022 |
| Lenovo        | 0x30F617AA NOK              | Desktop     | [bb13b87bd5](https://linux-hardware.org/?probe=bb13b87bd5) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [7ff2c5ad1c](https://linux-hardware.org/?probe=7ff2c5ad1c) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [a64cec6a4d](https://linux-hardware.org/?probe=a64cec6a4d) | Oct 01, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [e09f793c1a](https://linux-hardware.org/?probe=e09f793c1a) | Oct 01, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [68b0c0ca1a](https://linux-hardware.org/?probe=68b0c0ca1a) | Oct 01, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [1a0d8b695d](https://linux-hardware.org/?probe=1a0d8b695d) | Oct 01, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [a46521af41](https://linux-hardware.org/?probe=a46521af41) | Oct 01, 2022 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [982b143d73](https://linux-hardware.org/?probe=982b143d73) | Oct 01, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [d967f57569](https://linux-hardware.org/?probe=d967f57569) | Oct 01, 2022 |
| ASUSTek       | M5A87                       | Desktop     | [89ca067566](https://linux-hardware.org/?probe=89ca067566) | Oct 01, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [8c24fa2271](https://linux-hardware.org/?probe=8c24fa2271) | Oct 01, 2022 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [87a1c21540](https://linux-hardware.org/?probe=87a1c21540) | Oct 01, 2022 |
| Sony          | VPCYB3V1E                   | Notebook    | [de50c8a304](https://linux-hardware.org/?probe=de50c8a304) | Oct 01, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [f50a823779](https://linux-hardware.org/?probe=f50a823779) | Oct 01, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [646f4ffa8e](https://linux-hardware.org/?probe=646f4ffa8e) | Oct 01, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [75b0aa3c75](https://linux-hardware.org/?probe=75b0aa3c75) | Sep 30, 2022 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | Desktop     | [a6b14fdcf3](https://linux-hardware.org/?probe=a6b14fdcf3) | Sep 30, 2022 |
| Dell          | Inspiron 11-3162            | Notebook    | [8cd15b2f0c](https://linux-hardware.org/?probe=8cd15b2f0c) | Sep 30, 2022 |
| Acer          | Batman A01                  | Desktop     | [f8ebe348e4](https://linux-hardware.org/?probe=f8ebe348e4) | Sep 30, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [cfe1aba7e6](https://linux-hardware.org/?probe=cfe1aba7e6) | Sep 30, 2022 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [66877298d4](https://linux-hardware.org/?probe=66877298d4) | Sep 30, 2022 |
| Dell          | Latitude E6520              | Notebook    | [04817b4ceb](https://linux-hardware.org/?probe=04817b4ceb) | Sep 30, 2022 |
| Lenovo        | G460 20041                  | Notebook    | [9018f40ad5](https://linux-hardware.org/?probe=9018f40ad5) | Sep 30, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [11e4602764](https://linux-hardware.org/?probe=11e4602764) | Sep 30, 2022 |
| Dell          | Latitude 3310               | Notebook    | [3c4874fa51](https://linux-hardware.org/?probe=3c4874fa51) | Sep 30, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [d153a4f97a](https://linux-hardware.org/?probe=d153a4f97a) | Sep 29, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_4.3/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003       | 4149      | 94.12%  |
| 5.16.13-desktop-1omv4003      | 220       | 4.99%   |
| 5.17.1-desktop-2omv4050       | 17        | 0.39%   |
| 5.14.14-desktop-1omv4050      | 5         | 0.11%   |
| 5.16.5-desktop-2omv4003       | 3         | 0.07%   |
| 5.17.1-desktop-clang-2omv4050 | 2         | 0.05%   |
| 5.16.9-desktop-1omv4003       | 2         | 0.05%   |
| 5.16.3-desktop-2omv4050       | 2         | 0.05%   |
| 6.1.10                        | 1         | 0.02%   |
| 5.17.7-desktop-1omv4090       | 1         | 0.02%   |
| 5.16.9-desktop-1omv4050       | 1         | 0.02%   |
| 5.16.7-desktop-clang-1omv4003 | 1         | 0.02%   |
| 5.16.13-desktop-1omv4050      | 1         | 0.02%   |
| 5.15.14-1-lts                 | 1         | 0.02%   |
| 5.11.12-desktop-1omv4002      | 1         | 0.02%   |
| 5.10.14-desktop-1omv4002      | 1         | 0.02%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.7  | 4150      | 94.15%  |
| 5.16.13 | 221       | 5.01%   |
| 5.17.1  | 19        | 0.43%   |
| 5.14.14 | 5         | 0.11%   |
| 5.16.9  | 3         | 0.07%   |
| 5.16.5  | 3         | 0.07%   |
| 5.16.3  | 2         | 0.05%   |
| 6.1.10  | 1         | 0.02%   |
| 5.17.7  | 1         | 0.02%   |
| 5.15.14 | 1         | 0.02%   |
| 5.11.12 | 1         | 0.02%   |
| 5.10.14 | 1         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 4338      | 99.34%  |
| 5.17    | 20        | 0.46%   |
| 5.14    | 5         | 0.11%   |
| 6.1     | 1         | 0.02%   |
| 5.15    | 1         | 0.02%   |
| 5.11    | 1         | 0.02%   |
| 5.10    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 4366      | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| KDE5    | 4351      | 99.66%  |
| LXQt    | 8         | 0.18%   |
| Unknown | 7         | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4338      | 99.36%  |
| Wayland | 28        | 0.64%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 4365      | 99.98%  |
| LightDM | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 2446      | 55.83%  |
| de_DE | 387       | 8.83%   |
| fr_FR | 222       | 5.07%   |
| ru_RU | 217       | 4.95%   |
| pt_BR | 175       | 3.99%   |
| pl_PL | 133       | 3.04%   |
| it_IT | 118       | 2.69%   |
| en_GB | 91        | 2.08%   |
| es_ES | 87        | 1.99%   |
| cs_CZ | 50        | 1.14%   |
| es_AR | 43        | 0.98%   |
| de_AT | 41        | 0.94%   |
| es_MX | 40        | 0.91%   |
| en_IN | 25        | 0.57%   |
| hu_HU | 22        | 0.5%    |
| tr_TR | 21        | 0.48%   |
| en_CA | 21        | 0.48%   |
| pt_PT | 19        | 0.43%   |
| es_CO | 19        | 0.43%   |
| fr_CA | 17        | 0.39%   |
| en_AU | 16        | 0.37%   |
| de_CH | 15        | 0.34%   |
| nl_NL | 14        | 0.32%   |
| es_CL | 14        | 0.32%   |
| fr_BE | 11        | 0.25%   |
| es_VE | 11        | 0.25%   |
| ru_UA | 10        | 0.23%   |
| nl_BE | 9         | 0.21%   |
| es_PE | 8         | 0.18%   |
| da_DK | 8         | 0.18%   |
| nb_NO | 6         | 0.14%   |
| fr_CH | 6         | 0.14%   |
| es_CR | 5         | 0.11%   |
| ro_RO | 4         | 0.09%   |
| es_UY | 4         | 0.09%   |
| es_BO | 4         | 0.09%   |
| uk_UA | 3         | 0.07%   |
| es_SV | 3         | 0.07%   |
| es_EC | 3         | 0.07%   |
| en_ZA | 3         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2270      | 51.98%  |
| BIOS | 2097      | 48.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Overlay  | 3587      | 81.32%  |
| Ext4     | 804       | 18.23%  |
| Xfs      | 6         | 0.14%   |
| Btrfs    | 6         | 0.14%   |
| F2fs     | 4         | 0.09%   |
| Jfs      | 2         | 0.05%   |
| Reiserfs | 1         | 0.02%   |
| Ext3     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2919      | 66.72%  |
| MBR     | 1437      | 32.85%  |
| Unknown | 19        | 0.43%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2409      | 54.94%  |
| No        | 1976      | 45.06%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2229      | 50.98%  |
| Yes       | 2143      | 49.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ASUSTek Computer      | 695       | 15.92%  |
| Dell                  | 589       | 13.49%  |
| Hewlett-Packard       | 570       | 13.06%  |
| Lenovo                | 512       | 11.73%  |
| Gigabyte Technology   | 380       | 8.7%    |
| Acer                  | 287       | 6.57%   |
| MSI                   | 255       | 5.84%   |
| ASRock                | 178       | 4.08%   |
| Toshiba               | 102       | 2.34%   |
| Intel                 | 92        | 2.11%   |
| Apple                 | 74        | 1.69%   |
| Fujitsu               | 68        | 1.56%   |
| Samsung Electronics   | 48        | 1.1%    |
| Sony                  | 45        | 1.03%   |
| Positivo              | 33        | 0.76%   |
| Medion                | 28        | 0.64%   |
| Pegatron              | 25        | 0.57%   |
| Packard Bell          | 25        | 0.57%   |
| Foxconn               | 25        | 0.57%   |
| Biostar               | 25        | 0.57%   |
| Unknown               | 20        | 0.46%   |
| ECS                   | 16        | 0.37%   |
| AZW                   | 13        | 0.3%    |
| Alienware             | 11        | 0.25%   |
| TUXEDO                | 10        | 0.23%   |
| HUAWEI                | 10        | 0.23%   |
| Fujitsu Siemens       | 10        | 0.23%   |
| BESSTAR Tech          | 10        | 0.23%   |
| Philco                | 9         | 0.21%   |
| eMachines             | 9         | 0.21%   |
| LG Electronics        | 8         | 0.18%   |
| Chuwi                 | 8         | 0.18%   |
| Supermicro            | 7         | 0.16%   |
| Shuttle               | 7         | 0.16%   |
| Notebook              | 7         | 0.16%   |
| Compaq                | 7         | 0.16%   |
| Microsoft             | 6         | 0.14%   |
| Gateway               | 6         | 0.14%   |
| Positivo Bahia - VAIO | 4         | 0.09%   |
| Panasonic             | 4         | 0.09%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell Latitude 3120             | 48        | 1.1%    |
| ASUS All Series                | 42        | 0.96%   |
| Dell Latitude 3190 2-in-1      | 34        | 0.78%   |
| Unknown                        | 34        | 0.78%   |
| Dell Latitude 3310             | 29        | 0.66%   |
| Gigabyte H410M H V3            | 27        | 0.62%   |
| HP Notebook                    | 22        | 0.5%    |
| ASUS SABERTOOTH Z77            | 19        | 0.44%   |
| ASUS UX31E                     | 17        | 0.39%   |
| Dell OptiPlex 7010             | 16        | 0.37%   |
| Lenovo IdeaPad 1 14ADA05 82GW  | 11        | 0.25%   |
| Intel H61                      | 10        | 0.23%   |
| HP Pavilion g6                 | 10        | 0.23%   |
| HP Pavilion dv6                | 9         | 0.21%   |
| Dell OptiPlex 780              | 9         | 0.21%   |
| ASUS PRIME B450M-A II          | 9         | 0.21%   |
| Positivo Mobile                | 8         | 0.18%   |
| MSI MS-7C91                    | 8         | 0.18%   |
| Lenovo IdeaPad S145-15AST 81N3 | 8         | 0.18%   |
| Gigabyte B450M DS3H            | 8         | 0.18%   |
| Dell OptiPlex 9020             | 8         | 0.18%   |
| Dell OptiPlex 790              | 8         | 0.18%   |
| Dell OptiPlex 380              | 8         | 0.18%   |
| Dell Latitude 3300             | 8         | 0.18%   |
| Sony VGN-FZ31Z                 | 7         | 0.16%   |
| HP 15                          | 7         | 0.16%   |
| Dell XPS 15 9530               | 7         | 0.16%   |
| Dell Latitude E7450            | 7         | 0.16%   |
| Dell Latitude E7240            | 7         | 0.16%   |
| Dell Latitude E6420            | 7         | 0.16%   |
| Acer Aspire A515-51G           | 7         | 0.16%   |
| MSI MS-7C37                    | 6         | 0.14%   |
| MSI MS-7B79                    | 6         | 0.14%   |
| MSI MS-7A38                    | 6         | 0.14%   |
| MSI MS-7721                    | 6         | 0.14%   |
| HP ProDesk 600 G1 SFF          | 6         | 0.14%   |
| HP Pavilion 15                 | 6         | 0.14%   |
| HP Laptop 15-da0xxx            | 6         | 0.14%   |
| HP Laptop 14-fq0xxx            | 6         | 0.14%   |
| HP EliteDesk 800 G1 SFF        | 6         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 279       | 6.39%   |
| Acer Aspire           | 193       | 4.42%   |
| Lenovo ThinkPad       | 161       | 3.69%   |
| Lenovo IdeaPad        | 134       | 3.07%   |
| Dell OptiPlex         | 111       | 2.54%   |
| HP Pavilion           | 102       | 2.34%   |
| HP Compaq             | 85        | 1.95%   |
| ASUS PRIME            | 84        | 1.92%   |
| Toshiba Satellite     | 83        | 1.9%    |
| Dell Inspiron         | 80        | 1.83%   |
| Lenovo ThinkCentre    | 61        | 1.4%    |
| HP Laptop             | 60        | 1.37%   |
| HP ProBook            | 52        | 1.19%   |
| ASUS VivoBook         | 43        | 0.98%   |
| ASUS All              | 42        | 0.96%   |
| ASUS TUF              | 41        | 0.94%   |
| ASUS ROG              | 37        | 0.85%   |
| Unknown               | 34        | 0.78%   |
| Dell Precision        | 33        | 0.76%   |
| HP EliteBook          | 32        | 0.73%   |
| HP EliteDesk          | 31        | 0.71%   |
| Gigabyte H410M        | 31        | 0.71%   |
| Fujitsu LIFEBOOK      | 28        | 0.64%   |
| Dell XPS              | 28        | 0.64%   |
| Dell Vostro           | 27        | 0.62%   |
| Fujitsu ESPRIMO       | 26        | 0.6%    |
| HP ProDesk            | 25        | 0.57%   |
| ASUS SABERTOOTH       | 25        | 0.57%   |
| HP Notebook           | 22        | 0.5%    |
| Lenovo IdeaCentre     | 21        | 0.48%   |
| Acer Nitro            | 18        | 0.41%   |
| Packard Bell EasyNote | 17        | 0.39%   |
| Gigabyte B450M        | 17        | 0.39%   |
| ASUS UX31E            | 17        | 0.39%   |
| ASUS M5A78L-M         | 17        | 0.39%   |
| Lenovo Yoga           | 14        | 0.32%   |
| Acer Swift            | 13        | 0.3%    |
| HP 250                | 12        | 0.27%   |
| Acer TravelMate       | 12        | 0.27%   |
| Acer Extensa          | 12        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 438       | 10.03%  |
| 2011    | 406       | 9.3%    |
| 2013    | 357       | 8.18%   |
| 2021    | 337       | 7.72%   |
| 2019    | 333       | 7.63%   |
| 2020    | 326       | 7.47%   |
| 2018    | 306       | 7.01%   |
| 2014    | 298       | 6.83%   |
| 2010    | 280       | 6.41%   |
| 2016    | 221       | 5.06%   |
| 2015    | 220       | 5.04%   |
| 2017    | 213       | 4.88%   |
| 2009    | 203       | 4.65%   |
| 2008    | 198       | 4.54%   |
| 2007    | 126       | 2.89%   |
| 2006    | 59        | 1.35%   |
| 2022    | 36        | 0.82%   |
| 2005    | 5         | 0.11%   |
| Unknown | 4         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 2053      | 47.02%  |
| Desktop     | 2011      | 46.06%  |
| Convertible | 124       | 2.84%   |
| Mini pc     | 72        | 1.65%   |
| All in one  | 70        | 1.6%    |
| Server      | 19        | 0.44%   |
| Tablet      | 17        | 0.39%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4366      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4360      | 99.86%  |
| Yes  | 6         | 0.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1249      | 28.58%  |
| 3.01-4.0        | 1131      | 25.88%  |
| 8.01-16.0       | 773       | 17.69%  |
| 16.01-24.0      | 642       | 14.69%  |
| 32.01-64.0      | 258       | 5.9%    |
| 1.01-2.0        | 142       | 3.25%   |
| 2.01-3.0        | 55        | 1.26%   |
| 24.01-32.0      | 54        | 1.24%   |
| 64.01-256.0     | 53        | 1.21%   |
| 0.51-1.0        | 10        | 0.23%   |
| More than 256.0 | 3         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 3235      | 73.64%  |
| 0.51-1.0  | 719       | 16.37%  |
| 2.01-3.0  | 317       | 7.22%   |
| 0.01-0.5  | 62        | 1.41%   |
| 3.01-4.0  | 33        | 0.75%   |
| 4.01-8.0  | 16        | 0.36%   |
| 8.01-16.0 | 11        | 0.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2580      | 58.92%  |
| 2      | 1067      | 24.37%  |
| 3      | 337       | 7.7%    |
| 4      | 184       | 4.2%    |
| 0      | 82        | 1.87%   |
| 5      | 70        | 1.6%    |
| 6      | 27        | 0.62%   |
| 7      | 13        | 0.3%    |
| 8      | 7         | 0.16%   |
| 9      | 4         | 0.09%   |
| 12     | 3         | 0.07%   |
| 11     | 2         | 0.05%   |
| 15     | 1         | 0.02%   |
| 13     | 1         | 0.02%   |
| 10     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2188      | 50.07%  |
| No        | 2182      | 49.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3927      | 89.95%  |
| No        | 439       | 10.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3008      | 68.83%  |
| No        | 1362      | 31.17%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2213      | 50.65%  |
| No        | 2156      | 49.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Germany     | 531       | 12.15%  |
| USA         | 500       | 11.44%  |
| France      | 291       | 6.66%   |
| Brazil      | 282       | 6.45%   |
| Russia      | 272       | 6.23%   |
| Poland      | 222       | 5.08%   |
| Netherlands | 196       | 4.49%   |
| Italy       | 185       | 4.23%   |
| UK          | 139       | 3.18%   |
| Spain       | 119       | 2.72%   |
| Canada      | 115       | 2.63%   |
| Mexico      | 81        | 1.85%   |
| India       | 74        | 1.69%   |
| Australia   | 73        | 1.67%   |
| Czechia     | 68        | 1.56%   |
| Indonesia   | 57        | 1.3%    |
| Japan       | 55        | 1.26%   |
| Austria     | 54        | 1.24%   |
| Argentina   | 53        | 1.21%   |
| Portugal    | 48        | 1.1%    |
| Ukraine     | 45        | 1.03%   |
| Romania     | 44        | 1.01%   |
| Turkey      | 43        | 0.98%   |
| Switzerland | 42        | 0.96%   |
| Sweden      | 39        | 0.89%   |
| Belgium     | 36        | 0.82%   |
| Hungary     | 35        | 0.8%    |
| Colombia    | 35        | 0.8%    |
| Slovakia    | 28        | 0.64%   |
| Serbia      | 27        | 0.62%   |
| Finland     | 24        | 0.55%   |
| Greece      | 22        | 0.5%    |
| China       | 22        | 0.5%    |
| Chile       | 22        | 0.5%    |
| Egypt       | 21        | 0.48%   |
| Bulgaria    | 21        | 0.48%   |
| Peru        | 19        | 0.43%   |
| Venezuela   | 18        | 0.41%   |
| Norway      | 17        | 0.39%   |
| Israel      | 17        | 0.39%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Schagen        | 137       | 3.11%   |
| Moscow         | 54        | 1.23%   |
| Berlin         | 39        | 0.89%   |
| Warsaw         | 38        | 0.86%   |
| Sao Paulo      | 35        | 0.79%   |
| Paris          | 35        | 0.79%   |
| Prague         | 28        | 0.64%   |
| Vienna         | 27        | 0.61%   |
| Milan          | 23        | 0.52%   |
| Gonikoppal     | 22        | 0.5%    |
| Mexico City    | 21        | 0.48%   |
| Sydney         | 20        | 0.45%   |
| Munich         | 20        | 0.45%   |
| St Petersburg  | 18        | 0.41%   |
| Strzyzow       | 17        | 0.39%   |
| Jakarta        | 17        | 0.39%   |
| Istanbul       | 17        | 0.39%   |
| Madrid         | 16        | 0.36%   |
| Hamburg        | 16        | 0.36%   |
| Belgrade       | 16        | 0.36%   |
| Rio de Janeiro | 15        | 0.34%   |
| Cairo          | 14        | 0.32%   |
| Rome           | 13        | 0.3%    |
| Lima           | 13        | 0.3%    |
| Krakow         | 12        | 0.27%   |
| Brisbane       | 12        | 0.27%   |
| Bengaluru      | 12        | 0.27%   |
| Montreal       | 11        | 0.25%   |
| Cascais        | 11        | 0.25%   |
| Bratislava     | 11        | 0.25%   |
| Barcelona      | 11        | 0.25%   |
| Zagreb         | 10        | 0.23%   |
| Wroclaw        | 10        | 0.23%   |
| Poznan         | 10        | 0.23%   |
| Montevideo     | 10        | 0.23%   |
| Cluj-Napoca    | 10        | 0.23%   |
| Buenos Aires   | 10        | 0.23%   |
| Yekaterinburg  | 9         | 0.2%    |
| San José      | 9         | 0.2%    |
| Novosibirsk    | 9         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1063      | 1290   | 16.93%  |
| Seagate             | 929       | 1144   | 14.8%   |
| Samsung Electronics | 810       | 975    | 12.9%   |
| Toshiba             | 437       | 463    | 6.96%   |
| Kingston            | 361       | 390    | 5.75%   |
| Crucial             | 276       | 319    | 4.4%    |
| SanDisk             | 271       | 302    | 4.32%   |
| Hitachi             | 253       | 270    | 4.03%   |
| Unknown             | 167       | 180    | 2.66%   |
| A-DATA Technology   | 150       | 158    | 2.39%   |
| SK hynix            | 138       | 142    | 2.2%    |
| HGST                | 118       | 131    | 1.88%   |
| Intel               | 71        | 77     | 1.13%   |
| China               | 71        | 78     | 1.13%   |
| Micron Technology   | 58        | 59     | 0.92%   |
| GOODRAM             | 50        | 52     | 0.8%    |
| PNY                 | 43        | 51     | 0.68%   |
| SPCC                | 41        | 45     | 0.65%   |
| Intenso             | 41        | 42     | 0.65%   |
| Unknown             | 40        | 42     | 0.64%   |
| Patriot             | 37        | 39     | 0.59%   |
| LITEON              | 35        | 35     | 0.56%   |
| KIOXIA              | 34        | 34     | 0.54%   |
| Maxtor              | 33        | 38     | 0.53%   |
| ASMT                | 32        | 39     | 0.51%   |
| Apple               | 32        | 32     | 0.51%   |
| JMicron Technology  | 31        | 32     | 0.49%   |
| Apacer              | 31        | 32     | 0.49%   |
| Gigabyte Technology | 29        | 29     | 0.46%   |
| Fujitsu             | 28        | 29     | 0.45%   |
| Netac               | 26        | 27     | 0.41%   |
| Corsair             | 25        | 27     | 0.4%    |
| SSSTC               | 24        | 24     | 0.38%   |
| Phison              | 24        | 26     | 0.38%   |
| OCZ                 | 23        | 23     | 0.37%   |
| Transcend           | 22        | 24     | 0.35%   |
| Hewlett-Packard     | 22        | 25     | 0.35%   |
| Team                | 20        | 20     | 0.32%   |
| Silicon Motion      | 18        | 21     | 0.29%   |
| KingSpec            | 18        | 18     | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 89        | 1.3%    |
| Seagate ST500DM002-1BD142 500GB     | 68        | 0.99%   |
| Seagate ST1000DM010-2EP102 1TB      | 58        | 0.85%   |
| Samsung SSD 860 EVO 500GB           | 45        | 0.66%   |
| Toshiba MQ01ABF050 500GB            | 43        | 0.63%   |
| Samsung SSD 860 EVO 250GB           | 43        | 0.63%   |
| Kingston SA400S37120G 120GB SSD     | 43        | 0.63%   |
| Samsung SSD 850 EVO 250GB           | 42        | 0.61%   |
| Kingston SA400S37480G 480GB SSD     | 42        | 0.61%   |
| Toshiba MQ01ABD100 1TB              | 41        | 0.6%    |
| Crucial CT500MX500SSD1 500GB        | 41        | 0.6%    |
| WDC WD10EZEX-08WN4A0 1TB            | 40        | 0.58%   |
| Unknown                             | 40        | 0.58%   |
| Unknown SD/MMC/MS PRO 64GB          | 39        | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 38        | 0.55%   |
| Crucial CT240BX500SSD1 240GB        | 37        | 0.54%   |
| Toshiba DT01ACA100 1TB              | 34        | 0.5%    |
| Seagate ST2000DM008-2FR102 2TB      | 34        | 0.5%    |
| Seagate ST500LT012-1DG142 500GB     | 32        | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 31        | 0.45%   |
| Seagate ST1000LM035-1RK172 1TB      | 31        | 0.45%   |
| Toshiba MQ04ABF100 1TB              | 30        | 0.44%   |
| Samsung SSD 850 EVO 500GB           | 29        | 0.42%   |
| Crucial CT1000MX500SSD1 1TB         | 29        | 0.42%   |
| Kingston SV300S37A120G 120GB SSD    | 28        | 0.41%   |
| Toshiba DT01ACA050 500GB            | 27        | 0.39%   |
| Crucial CT480BX500SSD1 480GB        | 26        | 0.38%   |
| Samsung SSD 970 EVO Plus 500GB      | 25        | 0.36%   |
| Seagate ST1000DM003-1ER162 1TB      | 24        | 0.35%   |
| HGST HTS545050A7E680 500GB          | 24        | 0.35%   |
| Seagate ST9500325AS 500GB           | 23        | 0.34%   |
| SK hynix BC711 NVMe 128GB           | 22        | 0.32%   |
| SanDisk SSD PLUS 240GB              | 22        | 0.32%   |
| A-DATA SU750 256GB SSD              | 22        | 0.32%   |
| Samsung SSD 970 EVO Plus 1TB        | 21        | 0.31%   |
| HGST HTS721010A9E630 1TB            | 21        | 0.31%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 20        | 0.29%   |
| Seagate ST1000DM003-1CH162 1TB      | 20        | 0.29%   |
| Toshiba HDWD110 1TB                 | 19        | 0.28%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 19        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 916       | 1122   | 31.64%  |
| WDC                 | 861       | 1018   | 29.74%  |
| Toshiba             | 387       | 409    | 13.37%  |
| Hitachi             | 253       | 270    | 8.74%   |
| Samsung Electronics | 167       | 188    | 5.77%   |
| HGST                | 118       | 131    | 4.08%   |
| Unknown             | 40        | 40     | 1.38%   |
| Maxtor              | 31        | 36     | 1.07%   |
| Fujitsu             | 28        | 29     | 0.97%   |
| ASMT                | 26        | 33     | 0.9%    |
| Apple               | 15        | 15     | 0.52%   |
| SABRENT             | 7         | 8      | 0.24%   |
| USB3.0              | 5         | 5      | 0.17%   |
| WD MediaMax         | 4         | 5      | 0.14%   |
| Hewlett-Packard     | 4         | 4      | 0.14%   |
| ASMedia             | 4         | 4      | 0.14%   |
| SAGE                | 3         | 3      | 0.1%    |
| Magnetic Data       | 3         | 3      | 0.1%    |
| JMicron Technology  | 3         | 3      | 0.1%    |
| Intenso             | 3         | 3      | 0.1%    |
| IBM/Hitachi         | 3         | 4      | 0.1%    |
| HPE                 | 2         | 2      | 0.07%   |
| Unknown             | 2         | 2      | 0.07%   |
| USB                 | 1         | 1      | 0.03%   |
| RSH-339             | 1         | 1      | 0.03%   |
| QUANTUM             | 1         | 1      | 0.03%   |
| QC-FT-D             | 1         | 1      | 0.03%   |
| MARVELL             | 1         | 1      | 0.03%   |
| LaCie               | 1         | 1      | 0.03%   |
| HGST HTS            | 1         | 1      | 0.03%   |
| ExcelStor           | 1         | 1      | 0.03%   |
| Config              | 1         | 1      | 0.03%   |
| China               | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 450       | 507    | 19%     |
| Kingston            | 300       | 321    | 12.67%  |
| SanDisk             | 238       | 263    | 10.05%  |
| Crucial             | 237       | 271    | 10.01%  |
| WDC                 | 131       | 142    | 5.53%   |
| A-DATA Technology   | 118       | 119    | 4.98%   |
| China               | 70        | 77     | 2.96%   |
| GOODRAM             | 48        | 48     | 2.03%   |
| Micron Technology   | 41        | 41     | 1.73%   |
| SK hynix            | 38        | 39     | 1.6%    |
| PNY                 | 38        | 44     | 1.6%    |
| Toshiba             | 35        | 36     | 1.48%   |
| Patriot             | 32        | 34     | 1.35%   |
| LITEON              | 32        | 32     | 1.35%   |
| SPCC                | 31        | 34     | 1.31%   |
| Intenso             | 31        | 32     | 1.31%   |
| Intel               | 31        | 33     | 1.31%   |
| Apacer              | 28        | 28     | 1.18%   |
| OCZ                 | 23        | 23     | 0.97%   |
| Netac               | 22        | 23     | 0.93%   |
| Unknown             | 22        | 23     | 0.93%   |
| Transcend           | 20        | 21     | 0.84%   |
| JMicron Technology  | 20        | 21     | 0.84%   |
| Team                | 19        | 19     | 0.8%    |
| KingSpec            | 18        | 18     | 0.76%   |
| Gigabyte Technology | 17        | 17     | 0.72%   |
| Apple               | 15        | 15     | 0.63%   |
| LITEONIT            | 14        | 14     | 0.59%   |
| Hewlett-Packard     | 13        | 15     | 0.55%   |
| Corsair             | 12        | 13     | 0.51%   |
| Lexar               | 10        | 10     | 0.42%   |
| KIOXIA-EXCERIA      | 9         | 9      | 0.38%   |
| KingFast            | 8         | 8      | 0.34%   |
| Leven               | 7         | 7      | 0.3%    |
| KingDian            | 7         | 7      | 0.3%    |
| TO Exter            | 6         | 6      | 0.25%   |
| Seagate             | 6         | 6      | 0.25%   |
| TCSUNBOW            | 5         | 5      | 0.21%   |
| Colorful            | 5         | 6      | 0.21%   |
| XrayDisk            | 4         | 4      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2464      | 3347   | 44.24%  |
| SSD     | 2024      | 2550   | 36.34%  |
| NVMe    | 866       | 1008   | 15.55%  |
| MMC     | 148       | 157    | 2.66%   |
| Unknown | 67        | 82     | 1.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3725      | 5637   | 74.1%   |
| NVMe | 862       | 997    | 17.15%  |
| SAS  | 292       | 353    | 5.81%   |
| MMC  | 148       | 157    | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2963      | 3839   | 63.86%  |
| 0.51-1.0   | 1174      | 1430   | 25.3%   |
| 1.01-2.0   | 311       | 379    | 6.7%    |
| 2.01-3.0   | 63        | 75     | 1.36%   |
| 4.01-10.0  | 57        | 81     | 1.23%   |
| 3.01-4.0   | 56        | 77     | 1.21%   |
| 10.01-20.0 | 16        | 16     | 0.34%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2472      | 56.11%  |
| 101-250        | 607       | 13.78%  |
| 251-500        | 364       | 8.26%   |
| Unknown        | 350       | 7.94%   |
| 501-1000       | 194       | 4.4%    |
| 51-100         | 171       | 3.88%   |
| 21-50          | 156       | 3.54%   |
| 1001-2000      | 60        | 1.36%   |
| More than 3000 | 17        | 0.39%   |
| 2001-3000      | 15        | 0.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3686      | 83.79%  |
| Unknown        | 350       | 7.96%   |
| 101-250        | 95        | 2.16%   |
| 21-50          | 85        | 1.93%   |
| 51-100         | 79        | 1.8%    |
| 251-500        | 48        | 1.09%   |
| 501-1000       | 31        | 0.7%    |
| 1001-2000      | 17        | 0.39%   |
| More than 3000 | 5         | 0.11%   |
| 2001-3000      | 3         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 30        | 31     | 2.29%   |
| HGST HTS545050A7E680 500GB          | 20        | 20     | 1.53%   |
| SanDisk SSD U100 256GB              | 17        | 17     | 1.3%    |
| Seagate ST9500325AS 500GB           | 16        | 16     | 1.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 15        | 15     | 1.14%   |
| HGST HTS541010A9E680 1TB            | 13        | 13     | 0.99%   |
| Toshiba MQ01ABF050 500GB            | 12        | 12     | 0.92%   |
| Seagate ST9320325AS 320GB           | 11        | 11     | 0.84%   |
| Kingston SV300S37A120G 120GB SSD    | 10        | 10     | 0.76%   |
| Seagate ST1000DM010-2EP102 1TB      | 9         | 9      | 0.69%   |
| Seagate ST1000DM003-9YN162 1TB      | 9         | 9      | 0.69%   |
| Samsung Electronics HD322HJ 320GB   | 9         | 10     | 0.69%   |
| Hitachi HTS543232A7A384 320GB       | 9         | 9      | 0.69%   |
| HGST HTS721010A9E630 1TB            | 9         | 10     | 0.69%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 8         | 9      | 0.61%   |
| Seagate ST500LT012-1DG142 500GB     | 8         | 8      | 0.61%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 8         | 8      | 0.61%   |
| Seagate ST3500413AS 500GB           | 8         | 8      | 0.61%   |
| Seagate ST1000LM035-1RK172 1TB      | 8         | 8      | 0.61%   |
| Toshiba MQ01ABD100 1TB              | 7         | 7      | 0.53%   |
| Toshiba MQ01ABD050 500GB            | 7         | 7      | 0.53%   |
| Seagate ST500LT012-9WS142 500GB     | 7         | 7      | 0.53%   |
| Seagate ST3500418AS 500GB           | 7         | 7      | 0.53%   |
| Seagate ST31000524AS 1TB            | 7         | 7      | 0.53%   |
| Hitachi HTS725032A7E630 320GB       | 7         | 7      | 0.53%   |
| HGST HTS545050A7E380 500GB          | 7         | 7      | 0.53%   |
| Crucial CT240M500SSD1 240GB         | 7         | 7      | 0.53%   |
| Seagate ST2000DM001-1CH164 2TB      | 6         | 6      | 0.46%   |
| SanDisk SSD PLUS 480GB              | 6         | 6      | 0.46%   |
| SanDisk SSD PLUS 240GB              | 6         | 6      | 0.46%   |
| Samsung Electronics HD502HJ 500GB   | 6         | 6      | 0.46%   |
| Hitachi HTS545050A7E380 500GB       | 6         | 6      | 0.46%   |
| HGST HTS725050A7E630 500GB          | 6         | 6      | 0.46%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 5         | 5      | 0.38%   |
| WDC WD5000AAKS-00V1A0 500GB         | 5         | 5      | 0.38%   |
| WDC WD5000AADS-00S9B0 500GB         | 5         | 5      | 0.38%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 5         | 5      | 0.38%   |
| WDC WD10EARS-00Y5B1 1TB             | 5         | 6      | 0.38%   |
| Toshiba MQ04ABF100 1TB              | 5         | 5      | 0.38%   |
| Toshiba DT01ACA100 1TB              | 5         | 5      | 0.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 342       | 369    | 26.87%  |
| WDC                 | 270       | 293    | 21.21%  |
| Hitachi             | 131       | 136    | 10.29%  |
| Toshiba             | 112       | 114    | 8.8%    |
| Samsung Electronics | 98        | 104    | 7.7%    |
| HGST                | 67        | 69     | 5.26%   |
| SanDisk             | 45        | 45     | 3.53%   |
| Kingston            | 28        | 29     | 2.2%    |
| Crucial             | 23        | 24     | 1.81%   |
| Maxtor              | 21        | 22     | 1.65%   |
| A-DATA Technology   | 16        | 16     | 1.26%   |
| Intel               | 12        | 12     | 0.94%   |
| Fujitsu             | 11        | 11     | 0.86%   |
| Micron Technology   | 9         | 9      | 0.71%   |
| SK hynix            | 8         | 9      | 0.63%   |
| China               | 8         | 8      | 0.63%   |
| Apple               | 7         | 7      | 0.55%   |
| GOODRAM             | 5         | 5      | 0.39%   |
| ASMT                | 5         | 6      | 0.39%   |
| OCZ                 | 4         | 4      | 0.31%   |
| LITEON              | 3         | 3      | 0.24%   |
| IBM/Hitachi         | 3         | 4      | 0.24%   |
| Hewlett-Packard     | 3         | 3      | 0.24%   |
| Corsair             | 3         | 4      | 0.24%   |
| Transcend           | 2         | 2      | 0.16%   |
| SPCC                | 2         | 2      | 0.16%   |
| Patriot             | 2         | 2      | 0.16%   |
| KingSpec            | 2         | 2      | 0.16%   |
| HP Phison           | 2         | 2      | 0.16%   |
| ASMedia             | 2         | 2      | 0.16%   |
| Unknown             | 2         | 2      | 0.16%   |
| WDC WDS2            | 1         | 1      | 0.08%   |
| WD MediaMax         | 1         | 1      | 0.08%   |
| Vaseky              | 1         | 1      | 0.08%   |
| USB3.0              | 1         | 1      | 0.08%   |
| TO Exter            | 1         | 1      | 0.08%   |
| TEXTORM             | 1         | 1      | 0.08%   |
| TCSUNBOW            | 1         | 1      | 0.08%   |
| RSH-339             | 1         | 1      | 0.08%   |
| PNY                 | 1         | 1      | 0.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 342       | 369    | 32.95%  |
| WDC                 | 257       | 277    | 24.76%  |
| Hitachi             | 131       | 136    | 12.62%  |
| Toshiba             | 109       | 111    | 10.5%   |
| Samsung Electronics | 79        | 84     | 7.61%   |
| HGST                | 67        | 69     | 6.45%   |
| Maxtor              | 21        | 22     | 2.02%   |
| Fujitsu             | 11        | 11     | 1.06%   |
| ASMT                | 5         | 6      | 0.48%   |
| IBM/Hitachi         | 3         | 4      | 0.29%   |
| Apple               | 3         | 3      | 0.29%   |
| ASMedia             | 2         | 2      | 0.19%   |
| WD MediaMax         | 1         | 1      | 0.1%    |
| USB3.0              | 1         | 1      | 0.1%    |
| RSH-339             | 1         | 1      | 0.1%    |
| Magnetic Data       | 1         | 1      | 0.1%    |
| HPE                 | 1         | 1      | 0.1%    |
| Hewlett-Packard     | 1         | 1      | 0.1%    |
| ExcelStor           | 1         | 1      | 0.1%    |
| Unknown             | 1         | 1      | 0.1%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 960       | 1102   | 80.4%   |
| SSD     | 221       | 230    | 18.51%  |
| NVMe    | 12        | 13     | 1.01%   |
| Unknown | 1         | 1      | 0.08%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HD103SJ 1TB                  | 3         | 3      | 7.32%   |
| Apple HDD HTS541010A9E662 1TB                    | 3         | 3      | 7.32%   |
| WDC WD3200BEVT-11ZCT0 320GB                      | 2         | 2      | 4.88%   |
| Toshiba MQ01ABD100 1TB                           | 2         | 2      | 4.88%   |
| WDC WD5000BEVT-22ZAT0 500GB                      | 1         | 1      | 2.44%   |
| WDC WD5000BEVT-22A0RT0 500GB                     | 1         | 1      | 2.44%   |
| WDC WD3200BEKT-60KA9T0 320GB                     | 1         | 1      | 2.44%   |
| WDC WD3200AAJS-60Z0A0 320GB                      | 1         | 1      | 2.44%   |
| WDC WD2500BEVT-60ZCT1 250GB                      | 1         | 1      | 2.44%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1         | 1      | 2.44%   |
| WDC WD1600YS-23SHB0 160GB                        | 1         | 1      | 2.44%   |
| WDC WD1600BEVT-75A23T0 160GB                     | 1         | 1      | 2.44%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 2.44%   |
| Toshiba MQ01ABD050 500GB                         | 1         | 1      | 2.44%   |
| Toshiba MK3265GSXN 320GB                         | 1         | 1      | 2.44%   |
| Toshiba MK3259GSXP 320GB                         | 1         | 1      | 2.44%   |
| Toshiba MK3256GSY 320GB                          | 1         | 1      | 2.44%   |
| Toshiba DT01ACA100 1TB                           | 1         | 1      | 2.44%   |
| Seagate STM31000528AS 1TB                        | 1         | 1      | 2.44%   |
| Seagate ST980811AS 80GB                          | 1         | 1      | 2.44%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 2.44%   |
| Seagate ST3250318AS 250GB                        | 1         | 1      | 2.44%   |
| Seagate ST3160215A 160GB                         | 1         | 1      | 2.44%   |
| Samsung Electronics SSD 980 500GB                | 1         | 1      | 2.44%   |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1         | 1      | 2.44%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 2.44%   |
| Samsung Electronics HD502IJ 500GB                | 1         | 1      | 2.44%   |
| Samsung Electronics HD103UJ 1TB                  | 1         | 1      | 2.44%   |
| Intel SSDSA2BW160G3 160GB                        | 1         | 1      | 2.44%   |
| Hitachi HTS725050A7E630 500GB                    | 1         | 1      | 2.44%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 2.44%   |
| Hitachi HDS721010DLE630 1TB                      | 1         | 1      | 2.44%   |
| Hitachi HDP725050GLA360 500GB                    | 1         | 1      | 2.44%   |
| GOODRAM SSDPR-PX500-256-80 256GB                 | 1         | 1      | 2.44%   |
| Apple HDD HTS545050A7E362 500GB                  | 1         | 1      | 2.44%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 11     | 26.83%  |
| Samsung Electronics | 8         | 8      | 19.51%  |
| Toshiba             | 7         | 7      | 17.07%  |
| Seagate             | 5         | 5      | 12.2%   |
| Hitachi             | 4         | 4      | 9.76%   |
| Apple               | 4         | 4      | 9.76%   |
| Intel               | 1         | 1      | 2.44%   |
| GOODRAM             | 1         | 1      | 2.44%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3426      | 5288   | 68.03%  |
| Malfunc  | 1169      | 1346   | 23.21%  |
| Detected | 401       | 469    | 7.96%   |
| Failed   | 40        | 41     | 0.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3073      | 58.3%   |
| AMD                              | 922       | 17.49%  |
| Samsung Electronics              | 256       | 4.86%   |
| SanDisk                          | 137       | 2.6%    |
| Nvidia                           | 94        | 1.78%   |
| SK hynix                         | 93        | 1.76%   |
| JMicron Technology               | 88        | 1.67%   |
| ASMedia Technology               | 78        | 1.48%   |
| Marvell Technology Group         | 69        | 1.31%   |
| Kingston Technology Company      | 66        | 1.25%   |
| Phison Electronics               | 65        | 1.23%   |
| Silicon Motion                   | 46        | 0.87%   |
| Micron/Crucial Technology        | 42        | 0.8%    |
| KIOXIA                           | 34        | 0.65%   |
| ADATA Technology                 | 30        | 0.57%   |
| Solid State Storage Technology   | 24        | 0.46%   |
| VIA Technologies                 | 22        | 0.42%   |
| Micron Technology                | 21        | 0.4%    |
| Toshiba America Info Systems     | 19        | 0.36%   |
| Realtek Semiconductor            | 19        | 0.36%   |
| Broadcom / LSI                   | 11        | 0.21%   |
| Union Memory (Shenzhen)          | 9         | 0.17%   |
| Seagate Technology               | 8         | 0.15%   |
| Lite-On Technology               | 6         | 0.11%   |
| Silicon Integrated Systems [SiS] | 5         | 0.09%   |
| Integrated Technology Express    | 5         | 0.09%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.08%   |
| LSI Logic / Symbios Logic        | 4         | 0.08%   |
| Silicon Image                    | 3         | 0.06%   |
| Shenzhen Longsys Electronics     | 3         | 0.06%   |
| Yangtze Memory Technologies      | 2         | 0.04%   |
| Promise Technology               | 2         | 0.04%   |
| Apple                            | 2         | 0.04%   |
| Adaptec                          | 2         | 0.04%   |
| OCZ Technology Group             | 1         | 0.02%   |
| Netac Technology                 | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |
| Hewlett-Packard                  | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 540       | 8.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 237       | 3.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 235       | 3.77%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 187       | 3%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 161       | 2.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 148       | 2.38%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 135       | 2.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 134       | 2.15%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 127       | 2.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 124       | 1.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 123       | 1.97%   |
| AMD 400 Series Chipset SATA Controller                                                  | 114       | 1.83%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 112       | 1.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 110       | 1.77%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 99        | 1.59%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 96        | 1.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 89        | 1.43%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 81        | 1.3%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 81        | 1.3%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 79        | 1.27%   |
| Samsung NVMe SSD Controller 980                                                         | 77        | 1.24%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 75        | 1.2%    |
| AMD 500 Series Chipset SATA Controller                                                  | 75        | 1.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 74        | 1.19%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 72        | 1.16%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 71        | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 70        | 1.12%   |
| Intel SATA Controller [RAID mode]                                                       | 69        | 1.11%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 69        | 1.11%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 69        | 1.11%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 67        | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 66        | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 66        | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 63        | 1.01%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 58        | 0.93%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 43        | 0.69%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 41        | 0.66%   |
| Nvidia MCP61 SATA Controller                                                            | 40        | 0.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 39        | 0.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 38        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3383      | 62.92%  |
| NVMe | 858       | 15.96%  |
| IDE  | 847       | 15.75%  |
| RAID | 273       | 5.08%   |
| SAS  | 9         | 0.17%   |
| SCSI | 7         | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 3282      | 75.17%  |
| AMD    | 1084      | 24.83%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium Silver N6000 @ 1.10GHz          | 54        | 1.24%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 40        | 0.92%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 36        | 0.82%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 34        | 0.78%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 32        | 0.73%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 32        | 0.73%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 31        | 0.71%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 30        | 0.69%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 29        | 0.66%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 27        | 0.62%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 27        | 0.62%   |
| AMD Ryzen 5 3600 6-Core Processor             | 26        | 0.6%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 25        | 0.57%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 24        | 0.55%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 24        | 0.55%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 24        | 0.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 23        | 0.53%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 22        | 0.5%    |
| Intel Core i5-3570K CPU @ 3.40GHz             | 22        | 0.5%    |
| AMD FX-8350 Eight-Core Processor              | 22        | 0.5%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 21        | 0.48%   |
| AMD 3020e with Radeon Graphics                | 21        | 0.48%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 20        | 0.46%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 20        | 0.46%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 20        | 0.46%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 20        | 0.46%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 19        | 0.44%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 19        | 0.44%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 19        | 0.44%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 18        | 0.41%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 18        | 0.41%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 18        | 0.41%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 18        | 0.41%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 18        | 0.41%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 18        | 0.41%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 18        | 0.41%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 18        | 0.41%   |
| Intel Core i7-2677M CPU @ 1.80GHz             | 17        | 0.39%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 17        | 0.39%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 17        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1033      | 23.66%  |
| Intel Core i3           | 485       | 11.11%  |
| Intel Core i7           | 452       | 10.35%  |
| Intel Celeron           | 313       | 7.17%   |
| Intel Core 2 Duo        | 242       | 5.54%   |
| AMD Ryzen 5             | 194       | 4.44%   |
| Intel Pentium           | 170       | 3.89%   |
| AMD Ryzen 7             | 140       | 3.21%   |
| Other                   | 123       | 2.82%   |
| Intel Pentium Silver    | 102       | 2.34%   |
| AMD FX                  | 87        | 1.99%   |
| Intel Pentium Dual-Core | 83        | 1.9%    |
| Intel Xeon              | 80        | 1.83%   |
| Intel Core 2 Quad       | 64        | 1.47%   |
| AMD Ryzen 3             | 64        | 1.47%   |
| AMD A8                  | 51        | 1.17%   |
| AMD A6                  | 49        | 1.12%   |
| AMD A4                  | 44        | 1.01%   |
| AMD A10                 | 39        | 0.89%   |
| AMD Athlon              | 32        | 0.73%   |
| Intel Pentium Dual      | 31        | 0.71%   |
| Intel Core 2            | 31        | 0.71%   |
| AMD E1                  | 31        | 0.71%   |
| Intel Atom              | 30        | 0.69%   |
| AMD Phenom II X4        | 30        | 0.69%   |
| AMD Athlon II X2        | 29        | 0.66%   |
| AMD Ryzen 9             | 28        | 0.64%   |
| AMD E                   | 28        | 0.64%   |
| AMD Athlon 64 X2        | 23        | 0.53%   |
| Intel Core i9           | 18        | 0.41%   |
| AMD E2                  | 14        | 0.32%   |
| Intel Genuine           | 13        | 0.3%    |
| Intel Pentium Gold      | 12        | 0.27%   |
| AMD Ryzen 5 PRO         | 12        | 0.27%   |
| AMD Athlon II X4        | 12        | 0.27%   |
| AMD C-60                | 11        | 0.25%   |
| AMD Sempron             | 10        | 0.23%   |
| AMD Phenom              | 10        | 0.23%   |
| AMD Athlon X4           | 10        | 0.23%   |
| AMD Athlon II X3        | 9         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2255      | 51.64%  |
| 4      | 1369      | 31.35%  |
| 6      | 356       | 8.15%   |
| 8      | 197       | 4.51%   |
| 1      | 95        | 2.18%   |
| 3      | 37        | 0.85%   |
| 12     | 24        | 0.55%   |
| 16     | 18        | 0.41%   |
| 10     | 10        | 0.23%   |
| 14     | 2         | 0.05%   |
| 128    | 1         | 0.02%   |
| 44     | 1         | 0.02%   |
| 28     | 1         | 0.02%   |
| 20     | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 4345      | 99.52%  |
| 2      | 21        | 0.48%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2376      | 54.42%  |
| 1      | 1978      | 45.3%   |
| 8      | 9         | 0.21%   |
| 4      | 3         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4364      | 99.95%  |
| Unknown        | 2         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 380       | 8.69%   |
| 0x306a9    | 360       | 8.24%   |
| 0x306c3    | 293       | 6.7%    |
| 0x1067a    | 274       | 6.27%   |
| Unknown    | 114       | 2.61%   |
| 0x20655    | 112       | 2.56%   |
| 0x906ea    | 106       | 2.43%   |
| 0x506e3    | 101       | 2.31%   |
| 0x306d4    | 91        | 2.08%   |
| 0x406e3    | 89        | 2.04%   |
| 0x40651    | 88        | 2.01%   |
| 0x806e9    | 83        | 1.9%    |
| 0x08108109 | 78        | 1.78%   |
| 0x6fd      | 75        | 1.72%   |
| 0x906c0    | 72        | 1.65%   |
| 0x806ea    | 71        | 1.62%   |
| 0x08701021 | 70        | 1.6%    |
| 0x906e9    | 69        | 1.58%   |
| 0x706a8    | 69        | 1.58%   |
| 0x30678    | 62        | 1.42%   |
| 0x806ec    | 59        | 1.35%   |
| 0x10676    | 52        | 1.19%   |
| 0xa0655    | 50        | 1.14%   |
| 0x6fb      | 48        | 1.1%    |
| 0x706a1    | 46        | 1.05%   |
| 0x0a50000c | 45        | 1.03%   |
| 0x010000c8 | 45        | 1.03%   |
| 0x06001119 | 43        | 0.98%   |
| 0x20652    | 41        | 0.94%   |
| 0xa0653    | 39        | 0.89%   |
| 0x506c9    | 38        | 0.87%   |
| 0x0800820d | 37        | 0.85%   |
| 0x806c1    | 34        | 0.78%   |
| 0x706e5    | 34        | 0.78%   |
| 0x406c4    | 34        | 0.78%   |
| 0x106e5    | 34        | 0.78%   |
| 0x06006705 | 34        | 0.78%   |
| 0x08600106 | 33        | 0.75%   |
| 0x06003106 | 32        | 0.73%   |
| 0x07030105 | 30        | 0.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 462       | 10.58%  |
| SandyBridge      | 396       | 9.07%   |
| Haswell          | 395       | 9.05%   |
| IvyBridge        | 372       | 8.52%   |
| Penryn           | 336       | 7.69%   |
| Skylake          | 199       | 4.56%   |
| Core             | 178       | 4.08%   |
| Westmere         | 166       | 3.8%    |
| Zen+             | 142       | 3.25%   |
| Zen 2            | 133       | 3.05%   |
| Silvermont       | 129       | 2.95%   |
| Piledriver       | 125       | 2.86%   |
| K10              | 123       | 2.82%   |
| Goldmont plus    | 115       | 2.63%   |
| CometLake        | 108       | 2.47%   |
| Broadwell        | 102       | 2.34%   |
| Zen 3            | 100       | 2.29%   |
| Zen              | 88        | 2.02%   |
| Tremont          | 72        | 1.65%   |
| Excavator        | 65        | 1.49%   |
| IceLake          | 59        | 1.35%   |
| Bobcat           | 58        | 1.33%   |
| Nehalem          | 50        | 1.14%   |
| K8 Hammer        | 48        | 1.1%    |
| Puma             | 44        | 1.01%   |
| Unknown          | 43        | 0.98%   |
| Goldmont         | 39        | 0.89%   |
| Steamroller      | 38        | 0.87%   |
| TigerLake        | 36        | 0.82%   |
| K10 Llano        | 30        | 0.69%   |
| Jaguar           | 30        | 0.69%   |
| Bonnell          | 25        | 0.57%   |
| Alderlake Hybrid | 18        | 0.41%   |
| NetBurst         | 17        | 0.39%   |
| Bulldozer        | 15        | 0.34%   |
| K8 & K10 hybrid  | 11        | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2450      | 50.72%  |
| Nvidia                           | 1187      | 24.58%  |
| AMD                              | 1170      | 24.22%  |
| Matrox Electronics Systems       | 8         | 0.17%   |
| ASPEED Technology                | 6         | 0.12%   |
| Silicon Integrated Systems [SiS] | 4         | 0.08%   |
| VIA Technologies                 | 3         | 0.06%   |
| Conexant Systems                 | 1         | 0.02%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 313       | 6.33%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 199       | 4.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 124       | 2.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 117       | 2.36%   |
| Intel Core Processor Integrated Graphics Controller                                      | 105       | 2.12%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 91        | 1.84%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 87        | 1.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 84        | 1.7%    |
| Intel HD Graphics 620                                                                    | 79        | 1.6%    |
| Intel HD Graphics 5500                                                                   | 75        | 1.52%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 74        | 1.5%    |
| Intel JasperLake [UHD Graphics]                                                          | 72        | 1.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 72        | 1.46%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 70        | 1.41%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 69        | 1.39%   |
| Intel HD Graphics 530                                                                    | 68        | 1.37%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 60        | 1.21%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 58        | 1.17%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 58        | 1.17%   |
| Intel UHD Graphics 620                                                                   | 57        | 1.15%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 57        | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 55        | 1.11%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 55        | 1.11%   |
| AMD Renoir                                                                               | 50        | 1.01%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 48        | 0.97%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 48        | 0.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 46        | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 46        | 0.93%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 46        | 0.93%   |
| Intel HD Graphics 630                                                                    | 45        | 0.91%   |
| Nvidia GT218 [GeForce 210]                                                               | 41        | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 40        | 0.81%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 40        | 0.81%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 37        | 0.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 34        | 0.69%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 31        | 0.63%   |
| AMD Lucienne                                                                             | 31        | 0.63%   |
| Intel HD Graphics 500                                                                    | 30        | 0.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 29        | 0.59%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 28        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 2012      | 46.05%  |
| 1 x AMD                  | 1015      | 23.23%  |
| 1 x Nvidia               | 835       | 19.11%  |
| Intel + Nvidia           | 322       | 7.37%   |
| Intel + AMD              | 75        | 1.72%   |
| 2 x AMD                  | 60        | 1.37%   |
| AMD + Nvidia             | 20        | 0.46%   |
| 2 x Nvidia               | 7         | 0.16%   |
| 1 x Matrox               | 6         | 0.14%   |
| 1 x ASPEED               | 5         | 0.11%   |
| 1 x SiS                  | 4         | 0.09%   |
| 1 x VIA                  | 3         | 0.07%   |
| 3 x AMD                  | 1         | 0.02%   |
| 2 x Nvidia + 1 x Matrox  | 1         | 0.02%   |
| Nvidia + Matrox          | 1         | 0.02%   |
| Nvidia + ASPEED          | 1         | 0.02%   |
| Intel + Conexant Systems | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4260      | 97.53%  |
| Unknown     | 103       | 2.36%   |
| Proprietary | 5         | 0.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2162      | 49.5%   |
| 0.01-0.5   | 660       | 15.11%  |
| 1.01-2.0   | 572       | 13.1%   |
| 0.51-1.0   | 482       | 11.03%  |
| 3.01-4.0   | 215       | 4.92%   |
| 7.01-8.0   | 143       | 3.27%   |
| 5.01-6.0   | 75        | 1.72%   |
| 2.01-3.0   | 32        | 0.73%   |
| 8.01-16.0  | 22        | 0.5%    |
| 16.01-24.0 | 4         | 0.09%   |
| 4.01-5.0   | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 589       | 13.49%  |
| AU Optronics            | 472       | 10.81%  |
| LG Display              | 402       | 9.21%   |
| Chimei Innolux          | 320       | 7.33%   |
| BOE                     | 317       | 7.26%   |
| Goldstar                | 252       | 5.77%   |
| Hewlett-Packard         | 227       | 5.2%    |
| Dell                    | 221       | 5.06%   |
| Acer                    | 164       | 3.76%   |
| AOC                     | 143       | 3.28%   |
| Philips                 | 138       | 3.16%   |
| BenQ                    | 96        | 2.2%    |
| Lenovo                  | 89        | 2.04%   |
| Chi Mei Optoelectronics | 79        | 1.81%   |
| Ancor Communications    | 74        | 1.7%    |
| ViewSonic               | 64        | 1.47%   |
| Apple                   | 59        | 1.35%   |
| Iiyama                  | 43        | 0.99%   |
| Eizo                    | 36        | 0.82%   |
| Sharp                   | 34        | 0.78%   |
| Sony                    | 33        | 0.76%   |
| InfoVision              | 28        | 0.64%   |
| LG Philips              | 27        | 0.62%   |
| ASUSTek Computer        | 27        | 0.62%   |
| CPT                     | 22        | 0.5%    |
| Toshiba                 | 21        | 0.48%   |
| NEC Computers           | 20        | 0.46%   |
| HannStar                | 18        | 0.41%   |
| PANDA                   | 16        | 0.37%   |
| Fujitsu Siemens         | 15        | 0.34%   |
| Panasonic               | 14        | 0.32%   |
| Hitachi                 | 11        | 0.25%   |
| Unknown                 | 10        | 0.23%   |
| Sceptre Tech            | 10        | 0.23%   |
| ___                     | 9         | 0.21%   |
| Vestel Elektronik       | 9         | 0.21%   |
| TCL                     | 9         | 0.21%   |
| Medion                  | 9         | 0.21%   |
| MSI                     | 8         | 0.18%   |
| Vizio                   | 7         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE093D 1366x768 256x144mm 11.6-inch                     | 33        | 0.75%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 25        | 0.57%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 24        | 0.54%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                         | 22        | 0.5%    |
| AU Optronics LCD Monitor AUO202D 1920x1080 293x165mm 13.2-inch           | 20        | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 18        | 0.41%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 18        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 18        | 0.41%   |
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 17        | 0.39%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 17        | 0.39%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 15        | 0.34%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                        | 15        | 0.34%   |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                    | 14        | 0.32%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 14        | 0.32%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 14        | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 0.29%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 13        | 0.29%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 13        | 0.29%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 13        | 0.29%   |
| AU Optronics LCD Monitor AUO7E91 1366x768 256x144mm 11.6-inch            | 12        | 0.27%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 12        | 0.27%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch     | 11        | 0.25%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 11        | 0.25%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 11        | 0.25%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.25%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 11        | 0.25%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                          | 11        | 0.25%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 10        | 0.23%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 10        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 10        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 10        | 0.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 10        | 0.23%   |
| BOE LCD Monitor BOE0744 1366x768 256x144mm 11.6-inch                     | 10        | 0.23%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 10        | 0.23%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 9         | 0.2%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 9         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 9         | 0.2%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 9         | 0.2%    |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 9         | 0.2%    |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 9         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1646      | 38.41%  |
| 1366x768 (WXGA)    | 1190      | 27.77%  |
| 3840x2160 (4K)     | 228       | 5.32%   |
| 1600x900 (HD+)     | 225       | 5.25%   |
| 1280x1024 (SXGA)   | 185       | 4.32%   |
| 2560x1440 (QHD)    | 138       | 3.22%   |
| 1440x900 (WXGA+)   | 135       | 3.15%   |
| 1680x1050 (WSXGA+) | 131       | 3.06%   |
| 1280x800 (WXGA)    | 111       | 2.59%   |
| 1920x1200 (WUXGA)  | 77        | 1.8%    |
| 1360x768           | 46        | 1.07%   |
| 3440x1440          | 28        | 0.65%   |
| 2560x1080          | 24        | 0.56%   |
| 1920x540           | 16        | 0.37%   |
| 1024x768 (XGA)     | 16        | 0.37%   |
| 2560x1600          | 13        | 0.3%    |
| 3200x1800 (QHD+)   | 12        | 0.28%   |
| 1600x1200          | 8         | 0.19%   |
| 2160x1440          | 6         | 0.14%   |
| 1280x720 (HD)      | 6         | 0.14%   |
| 2288x1287          | 5         | 0.12%   |
| 2880x1800          | 4         | 0.09%   |
| 2736x1824          | 4         | 0.09%   |
| 2048x1152          | 4         | 0.09%   |
| 1920x1280          | 4         | 0.09%   |
| 1280x960           | 4         | 0.09%   |
| 1024x600           | 4         | 0.09%   |
| 3840x1080          | 2         | 0.05%   |
| 2256x1504          | 2         | 0.05%   |
| 1680x945           | 2         | 0.05%   |
| 1280x768           | 2         | 0.05%   |
| 3840x2400          | 1         | 0.02%   |
| 3840x1600          | 1         | 0.02%   |
| 3840x1200          | 1         | 0.02%   |
| 3456x2160          | 1         | 0.02%   |
| 3200x2000          | 1         | 0.02%   |
| 1400x1050          | 1         | 0.02%   |
| Unknown            | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1000      | 22.88%  |
| 13      | 372       | 8.51%   |
| 23      | 338       | 7.73%   |
| 21      | 323       | 7.39%   |
| 27      | 310       | 7.09%   |
| 17      | 294       | 6.73%   |
| 24      | 274       | 6.27%   |
| 14      | 241       | 5.51%   |
| 19      | 183       | 4.19%   |
| 11      | 141       | 3.23%   |
| 18      | 133       | 3.04%   |
| 31      | 113       | 2.59%   |
| 22      | 99        | 2.27%   |
| 12      | 96        | 2.2%    |
| 20      | 78        | 1.78%   |
| 84      | 46        | 1.05%   |
| 34      | 45        | 1.03%   |
| 32      | 29        | 0.66%   |
| 40      | 25        | 0.57%   |
| Unknown | 25        | 0.57%   |
| 72      | 21        | 0.48%   |
| 54      | 18        | 0.41%   |
| 26      | 18        | 0.41%   |
| 25      | 18        | 0.41%   |
| 65      | 15        | 0.34%   |
| 16      | 15        | 0.34%   |
| 10      | 13        | 0.3%    |
| 52      | 11        | 0.25%   |
| 48      | 8         | 0.18%   |
| 39      | 7         | 0.16%   |
| 33      | 6         | 0.14%   |
| 74      | 5         | 0.11%   |
| 47      | 5         | 0.11%   |
| 46      | 5         | 0.11%   |
| 28      | 5         | 0.11%   |
| 142     | 4         | 0.09%   |
| 42      | 4         | 0.09%   |
| 37      | 4         | 0.09%   |
| 35      | 4         | 0.09%   |
| 29      | 4         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1494      | 34.57%  |
| 501-600        | 889       | 20.57%  |
| 401-500        | 718       | 16.61%  |
| 201-300        | 437       | 10.11%  |
| 351-400        | 336       | 7.77%   |
| 601-700        | 148       | 3.42%   |
| 701-800        | 80        | 1.85%   |
| 1001-1500      | 73        | 1.69%   |
| 1501-2000      | 72        | 1.67%   |
| 801-900        | 41        | 0.95%   |
| Unknown        | 25        | 0.58%   |
| 901-1000       | 5         | 0.12%   |
| More than 2000 | 4         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3353      | 80.41%  |
| 16/10   | 503       | 12.06%  |
| 5/4     | 179       | 4.29%   |
| 21/9    | 49        | 1.18%   |
| 4/3     | 41        | 0.98%   |
| 3/2     | 27        | 0.65%   |
| 6/5     | 6         | 0.14%   |
| 1.00    | 4         | 0.1%    |
| 32/9    | 3         | 0.07%   |
| 1.96    | 2         | 0.05%   |
| Unknown | 2         | 0.05%   |
| 3.20    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 995       | 22.91%  |
| 201-250        | 832       | 19.15%  |
| 81-90          | 452       | 10.41%  |
| 151-200        | 364       | 8.38%   |
| 301-350        | 325       | 7.48%   |
| 141-150        | 202       | 4.65%   |
| 351-500        | 198       | 4.56%   |
| 71-80          | 171       | 3.94%   |
| 121-130        | 166       | 3.82%   |
| 51-60          | 141       | 3.25%   |
| More than 1000 | 134       | 3.08%   |
| 251-300        | 122       | 2.81%   |
| 61-70          | 85        | 1.96%   |
| 501-1000       | 61        | 1.4%    |
| 131-140        | 37        | 0.85%   |
| Unknown        | 25        | 0.58%   |
| 111-120        | 15        | 0.35%   |
| 41-50          | 13        | 0.3%    |
| 91-100         | 6         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1742      | 40.83%  |
| 101-120       | 1371      | 32.14%  |
| 121-160       | 840       | 19.69%  |
| 161-240       | 152       | 3.56%   |
| 1-50          | 113       | 2.65%   |
| Unknown       | 25        | 0.59%   |
| More than 240 | 23        | 0.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3961      | 90.7%   |
| 2     | 330       | 7.56%   |
| 0     | 54        | 1.24%   |
| 3     | 19        | 0.44%   |
| 4     | 2         | 0.05%   |
| 7     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2554      | 40.12%  |
| Intel                             | 1787      | 28.07%  |
| Qualcomm Atheros                  | 836       | 13.13%  |
| Broadcom                          | 324       | 5.09%   |
| Ralink                            | 96        | 1.51%   |
| Ralink Technology                 | 95        | 1.49%   |
| Marvell Technology Group          | 82        | 1.29%   |
| Nvidia                            | 73        | 1.15%   |
| Broadcom Limited                  | 72        | 1.13%   |
| TP-Link                           | 53        | 0.83%   |
| Samsung Electronics               | 35        | 0.55%   |
| MediaTek                          | 32        | 0.5%    |
| Qualcomm Atheros Communications   | 21        | 0.33%   |
| JMicron Technology                | 21        | 0.33%   |
| Huawei Technologies               | 21        | 0.33%   |
| Dell                              | 19        | 0.3%    |
| Ericsson Business Mobile Networks | 18        | 0.28%   |
| ASIX Electronics                  | 17        | 0.27%   |
| D-Link System                     | 16        | 0.25%   |
| NetGear                           | 15        | 0.24%   |
| D-Link                            | 14        | 0.22%   |
| Motorola PCS                      | 13        | 0.2%    |
| Sierra Wireless                   | 11        | 0.17%   |
| VIA Technologies                  | 10        | 0.16%   |
| Hewlett-Packard                   | 8         | 0.13%   |
| Aquantia                          | 8         | 0.13%   |
| Microsoft                         | 7         | 0.11%   |
| Edimax Technology                 | 7         | 0.11%   |
| Belkin Components                 | 7         | 0.11%   |
| Xiaomi                            | 6         | 0.09%   |
| DisplayLink                       | 6         | 0.09%   |
| ASUSTek Computer                  | 6         | 0.09%   |
| Silicon Integrated Systems [SiS]  | 5         | 0.08%   |
| IMC Networks                      | 5         | 0.08%   |
| AVM                               | 5         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.06%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.05%   |
| Spreadtrum Communications         | 3         | 0.05%   |
| Mellanox Technologies             | 3         | 0.05%   |
| HTC (High Tech Computer)          | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1806      | 24.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 339       | 4.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 179       | 2.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 119       | 1.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 117       | 1.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 110       | 1.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 108       | 1.47%   |
| Intel Wi-Fi 6 AX200                                               | 104       | 1.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 100       | 1.36%   |
| Intel Wireless 8265 / 8275                                        | 96        | 1.31%   |
| Intel Wireless 7265                                               | 93        | 1.26%   |
| Intel Ethernet Connection I217-LM                                 | 84        | 1.14%   |
| Realtek RTL8125 2.5GbE Controller                                 | 79        | 1.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 73        | 0.99%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 69        | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 69        | 0.94%   |
| Intel Wireless 7260                                               | 68        | 0.92%   |
| Intel Wireless 3165                                               | 66        | 0.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 62        | 0.84%   |
| Intel I211 Gigabit Network Connection                             | 62        | 0.84%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 61        | 0.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 58        | 0.79%   |
| Intel 82579V Gigabit Network Connection                           | 56        | 0.76%   |
| Intel Ethernet Connection (2) I219-V                              | 55        | 0.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 54        | 0.73%   |
| Intel Wireless 8260                                               | 53        | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 49        | 0.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 46        | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 46        | 0.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 43        | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 42        | 0.57%   |
| Intel Wireless 3160                                               | 40        | 0.54%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 38        | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 38        | 0.52%   |
| Ralink MT7601U Wireless Adapter                                   | 36        | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 35        | 0.48%   |
| Intel Ethernet Connection (7) I219-V                              | 35        | 0.48%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 34        | 0.46%   |
| Nvidia MCP61 Ethernet                                             | 34        | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 33        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1231      | 39.43%  |
| Qualcomm Atheros                      | 669       | 21.43%  |
| Realtek Semiconductor                 | 597       | 19.12%  |
| Broadcom                              | 195       | 6.25%   |
| Ralink                                | 96        | 3.07%   |
| Ralink Technology                     | 95        | 3.04%   |
| TP-Link                               | 38        | 1.22%   |
| Broadcom Limited                      | 32        | 1.02%   |
| MediaTek                              | 30        | 0.96%   |
| Qualcomm Atheros Communications       | 21        | 0.67%   |
| D-Link                                | 14        | 0.45%   |
| NetGear                               | 13        | 0.42%   |
| Sierra Wireless                       | 11        | 0.35%   |
| Dell                                  | 11        | 0.35%   |
| Microsoft                             | 7         | 0.22%   |
| Edimax Technology                     | 7         | 0.22%   |
| D-Link System                         | 7         | 0.22%   |
| Belkin Components                     | 6         | 0.19%   |
| ASUSTek Computer                      | 6         | 0.19%   |
| Marvell Technology Group              | 5         | 0.16%   |
| IMC Networks                          | 5         | 0.16%   |
| AVM                                   | 5         | 0.16%   |
| Hewlett-Packard                       | 4         | 0.13%   |
| Qcom                                  | 2         | 0.06%   |
| Linksys                               | 2         | 0.06%   |
| Gemtek                                | 2         | 0.06%   |
| Chu Yuen Enterprise                   | 2         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.06%   |
| ZyDAS                                 | 1         | 0.03%   |
| TRENDnet                              | 1         | 0.03%   |
| Sitecom Europe                        | 1         | 0.03%   |
| Philips (or NXP)                      | 1         | 0.03%   |
| Mercucys                              | 1         | 0.03%   |
| Logitec                               | 1         | 0.03%   |
| Guillemot                             | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 119       | 3.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 117       | 3.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 110       | 3.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 108       | 3.45%   |
| Intel Wi-Fi 6 AX200                                            | 104       | 3.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 100       | 3.2%    |
| Intel Wireless 8265 / 8275                                     | 96        | 3.07%   |
| Intel Wireless 7265                                            | 93        | 2.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 73        | 2.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 69        | 2.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 69        | 2.21%   |
| Intel Wireless 7260                                            | 68        | 2.17%   |
| Intel Wireless 3165                                            | 66        | 2.11%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 61        | 1.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 58        | 1.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 54        | 1.73%   |
| Intel Wireless 8260                                            | 53        | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 46        | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 46        | 1.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 43        | 1.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 42        | 1.34%   |
| Intel Wireless 3160                                            | 40        | 1.28%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 38        | 1.21%   |
| Ralink MT7601U Wireless Adapter                                | 36        | 1.15%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 34        | 1.09%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 30        | 0.96%   |
| Intel Centrino Wireless-N 2230                                 | 30        | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 29        | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 28        | 0.9%    |
| Intel WiFi Link 5100                                           | 28        | 0.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 28        | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 27        | 0.86%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 26        | 0.83%   |
| Intel Centrino Ultimate-N 6300                                 | 26        | 0.83%   |
| Intel Wireless-AC 9260                                         | 25        | 0.8%    |
| Intel Wi-Fi 6 AX201                                            | 25        | 0.8%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 25        | 0.8%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 23        | 0.74%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 23        | 0.74%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 22        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2322      | 56.66%  |
| Intel                             | 956       | 23.33%  |
| Qualcomm Atheros                  | 250       | 6.1%    |
| Broadcom                          | 178       | 4.34%   |
| Marvell Technology Group          | 77        | 1.88%   |
| Nvidia                            | 73        | 1.78%   |
| Broadcom Limited                  | 40        | 0.98%   |
| Samsung Electronics               | 35        | 0.85%   |
| JMicron Technology                | 21        | 0.51%   |
| ASIX Electronics                  | 17        | 0.41%   |
| Huawei Technologies               | 16        | 0.39%   |
| TP-Link                           | 15        | 0.37%   |
| VIA Technologies                  | 10        | 0.24%   |
| D-Link System                     | 9         | 0.22%   |
| Motorola PCS                      | 8         | 0.2%    |
| Aquantia                          | 8         | 0.2%    |
| Xiaomi                            | 6         | 0.15%   |
| DisplayLink                       | 6         | 0.15%   |
| Silicon Integrated Systems [SiS]  | 5         | 0.12%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.1%    |
| ZTE WCDMA Technologies MSM        | 3         | 0.07%   |
| Spreadtrum Communications         | 3         | 0.07%   |
| HTC (High Tech Computer)          | 3         | 0.07%   |
| Hewlett-Packard                   | 3         | 0.07%   |
| Google                            | 3         | 0.07%   |
| 3Com                              | 3         | 0.07%   |
| T & A Mobile Phones               | 2         | 0.05%   |
| Qualcomm                          | 2         | 0.05%   |
| OPPO Electronics                  | 2         | 0.05%   |
| NetGear                           | 2         | 0.05%   |
| Mellanox Technologies             | 2         | 0.05%   |
| MediaTek                          | 2         | 0.05%   |
| ICS Advent                        | 2         | 0.05%   |
| vivo                              | 1         | 0.02%   |
| Sundance Technology Inc / IC Plus | 1         | 0.02%   |
| Netchip Technology                | 1         | 0.02%   |
| Lenovo                            | 1         | 0.02%   |
| Emulex                            | 1         | 0.02%   |
| Dell                              | 1         | 0.02%   |
| Davicom Semiconductor             | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 1806      | 43.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 339       | 8.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 179       | 4.28%   |
| Intel Ethernet Connection I217-LM                                              | 84        | 2.01%   |
| Realtek RTL8125 2.5GbE Controller                                              | 79        | 1.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 62        | 1.48%   |
| Intel I211 Gigabit Network Connection                                          | 62        | 1.48%   |
| Intel 82579V Gigabit Network Connection                                        | 56        | 1.34%   |
| Intel Ethernet Connection (2) I219-V                                           | 55        | 1.31%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 49        | 1.17%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 38        | 0.91%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 35        | 0.84%   |
| Intel Ethernet Connection (7) I219-V                                           | 35        | 0.84%   |
| Nvidia MCP61 Ethernet                                                          | 34        | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 33        | 0.79%   |
| Intel Ethernet Controller I225-V                                               | 33        | 0.79%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 32        | 0.77%   |
| Intel Ethernet Connection I218-LM                                              | 27        | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                                          | 27        | 0.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 26        | 0.62%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 26        | 0.62%   |
| Intel Ethernet Connection I217-V                                               | 25        | 0.6%    |
| Intel 82577LM Gigabit Network Connection                                       | 24        | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                                          | 23        | 0.55%   |
| Intel 82567LM Gigabit Network Connection                                       | 21        | 0.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 21        | 0.5%    |
| Intel Ethernet Connection I219-LM                                              | 20        | 0.48%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 18        | 0.43%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 18        | 0.43%   |
| Intel 82574L Gigabit Network Connection                                        | 17        | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 16        | 0.38%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 16        | 0.38%   |
| Intel Ethernet Connection (2) I218-V                                           | 15        | 0.36%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 15        | 0.36%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 14        | 0.33%   |
| Nvidia MCP79 Ethernet                                                          | 14        | 0.33%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 13        | 0.31%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 13        | 0.31%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 13        | 0.31%   |
| Intel Ethernet Connection (4) I219-LM                                          | 13        | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3925      | 56.25%  |
| WiFi     | 3009      | 43.12%  |
| Modem    | 35        | 0.5%    |
| Unknown  | 9         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2395      | 55.92%  |
| WiFi     | 1888      | 44.08%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2283      | 52.28%  |
| 1     | 1972      | 45.16%  |
| 3     | 64        | 1.47%   |
| 0     | 38        | 0.87%   |
| 4     | 7         | 0.16%   |
| 5     | 2         | 0.05%   |
| 10    | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3103      | 70.94%  |
| Yes  | 1271      | 29.06%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 924       | 41.42%  |
| Realtek Semiconductor           | 234       | 10.49%  |
| Qualcomm Atheros Communications | 204       | 9.14%   |
| Cambridge Silicon Radio         | 147       | 6.59%   |
| Broadcom                        | 143       | 6.41%   |
| Lite-On Technology              | 101       | 4.53%   |
| IMC Networks                    | 95        | 4.26%   |
| Apple                           | 71        | 3.18%   |
| Foxconn / Hon Hai               | 67        | 3%      |
| Dell                            | 45        | 2.02%   |
| Toshiba                         | 34        | 1.52%   |
| ASUSTek Computer                | 34        | 1.52%   |
| Ralink                          | 30        | 1.34%   |
| Hewlett-Packard                 | 29        | 1.3%    |
| Realtek                         | 8         | 0.36%   |
| Alps Electric                   | 8         | 0.36%   |
| MediaTek                        | 7         | 0.31%   |
| Ralink Technology               | 6         | 0.27%   |
| Marvell Semiconductor           | 5         | 0.22%   |
| Fujitsu                         | 4         | 0.18%   |
| Edimax Technology               | 4         | 0.18%   |
| Askey Computer                  | 4         | 0.18%   |
| TP-Link                         | 3         | 0.13%   |
| Foxconn International           | 3         | 0.13%   |
| Dynex                           | 3         | 0.13%   |
| Unknown                         | 3         | 0.13%   |
| Integrated System Solution      | 2         | 0.09%   |
| Chicony Electronics             | 2         | 0.09%   |
| Belkin Components               | 2         | 0.09%   |
| Accel Semiconductor             | 2         | 0.09%   |
| USI                             | 1         | 0.04%   |
| Taiyo Yuden                     | 1         | 0.04%   |
| Smart Modular Technologies      | 1         | 0.04%   |
| SINO WEALTH                     | 1         | 0.04%   |
| Primax Electronics              | 1         | 0.04%   |
| Opticis                         | 1         | 0.04%   |
| D-Link System                   | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 418       | 18.74%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 147       | 6.59%   |
| Realtek Bluetooth Radio                                                             | 139       | 6.23%   |
| Intel AX201 Bluetooth                                                               | 128       | 5.74%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 121       | 5.42%   |
| Intel AX200 Bluetooth                                                               | 100       | 4.48%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 79        | 3.54%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 71        | 3.18%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 51        | 2.29%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 41        | 1.84%   |
| IMC Networks Bluetooth Radio                                                        | 40        | 1.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 38        | 1.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 36        | 1.61%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 35        | 1.57%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 32        | 1.43%   |
| Ralink RT3290 Bluetooth                                                             | 30        | 1.34%   |
| IMC Networks Bluetooth Device                                                       | 29        | 1.3%    |
| Lite-On Bluetooth Device                                                            | 28        | 1.26%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 28        | 1.26%   |
| Apple Bluetooth Host Controller                                                     | 26        | 1.17%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 25        | 1.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 24        | 1.08%   |
| Dell DW375 Bluetooth Module                                                         | 24        | 1.08%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 21        | 0.94%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 21        | 0.94%   |
| Apple Bluetooth USB Host Controller                                                 | 20        | 0.9%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 19        | 0.85%   |
| Intel AX210 Bluetooth                                                               | 18        | 0.81%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 18        | 0.81%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 16        | 0.72%   |
| Realtek RTL8723B Bluetooth                                                          | 12        | 0.54%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 12        | 0.54%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 11        | 0.49%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 11        | 0.49%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 11        | 0.49%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 11        | 0.49%   |
| Toshiba RT Bluetooth Radio                                                          | 10        | 0.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 10        | 0.45%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 9         | 0.4%    |
| Broadcom BCM2045 Bluetooth                                                          | 9         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3190      | 55%     |
| AMD                                          | 1292      | 22.28%  |
| Nvidia                                       | 931       | 16.05%  |
| C-Media Electronics                          | 84        | 1.45%   |
| Creative Labs                                | 49        | 0.84%   |
| Logitech                                     | 35        | 0.6%    |
| Texas Instruments                            | 20        | 0.34%   |
| Creative Technology                          | 16        | 0.28%   |
| JMTek                                        | 15        | 0.26%   |
| Generalplus Technology                       | 12        | 0.21%   |
| ASUSTek Computer                             | 10        | 0.17%   |
| VIA Technologies                             | 7         | 0.12%   |
| GN Netcom                                    | 7         | 0.12%   |
| XMOS                                         | 5         | 0.09%   |
| Silicon Integrated Systems [SiS]             | 5         | 0.09%   |
| Realtek Semiconductor                        | 5         | 0.09%   |
| Plantronics                                  | 5         | 0.09%   |
| Tenx Technology                              | 4         | 0.07%   |
| Kingston Technology                          | 4         | 0.07%   |
| Focusrite-Novation                           | 4         | 0.07%   |
| Blue Microphones                             | 4         | 0.07%   |
| SteelSeries ApS                              | 3         | 0.05%   |
| Sony                                         | 3         | 0.05%   |
| Samson Technologies                          | 3         | 0.05%   |
| Razer USA                                    | 3         | 0.05%   |
| Lenovo                                       | 3         | 0.05%   |
| KTMicro                                      | 3         | 0.05%   |
| Hewlett-Packard                              | 3         | 0.05%   |
| Corsair                                      | 3         | 0.05%   |
| Apple                                        | 3         | 0.05%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.03%   |
| Trust                                        | 2         | 0.03%   |
| Thesycon Systemsoftware & Consulting         | 2         | 0.03%   |
| ROCCAT                                       | 2         | 0.03%   |
| QinHeng Electronics                          | 2         | 0.03%   |
| PreSonus Audio Electronics                   | 2         | 0.03%   |
| No brand                                     | 2         | 0.03%   |
| Medeli Electronics                           | 2         | 0.03%   |
| M-Audio                                      | 2         | 0.03%   |
| GYROCOM C&C                                  | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 381       | 5.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 365       | 5.25%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 305       | 4.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 259       | 3.72%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 239       | 3.44%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 236       | 3.39%   |
| AMD FCH Azalia Controller                                                                         | 215       | 3.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 205       | 2.95%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 184       | 2.65%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 172       | 2.47%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 147       | 2.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 147       | 2.11%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 134       | 1.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 119       | 1.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 114       | 1.64%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 112       | 1.61%   |
| Intel Cannon Lake PCH cAVS                                                                        | 110       | 1.58%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 107       | 1.54%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 96        | 1.38%   |
| Intel Broadwell-U Audio Controller                                                                | 95        | 1.37%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 91        | 1.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 91        | 1.31%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 89        | 1.28%   |
| Intel 8 Series HD Audio Controller                                                                | 89        | 1.28%   |
| Intel 200 Series PCH HD Audio                                                                     | 85        | 1.22%   |
| AMD Kabini HDMI/DP Audio                                                                          | 85        | 1.22%   |
| Nvidia High Definition Audio Controller                                                           | 80        | 1.15%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 79        | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 73        | 1.05%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 73        | 1.05%   |
| Intel Jasper Lake HD Audio                                                                        | 72        | 1.04%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 64        | 0.92%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 63        | 0.91%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 61        | 0.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 61        | 0.88%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 58        | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 51        | 0.73%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 50        | 0.72%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 48        | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 47        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 963       | 18.52%  |
| SK hynix            | 818       | 15.73%  |
| Unknown             | 667       | 12.82%  |
| Kingston            | 655       | 12.59%  |
| Micron Technology   | 432       | 8.31%   |
| Crucial             | 267       | 5.13%   |
| Corsair             | 213       | 4.1%    |
| G.Skill             | 172       | 3.31%   |
| A-DATA Technology   | 125       | 2.4%    |
| Ramaxel Technology  | 104       | 2%      |
| Elpida              | 97        | 1.87%   |
| Nanya Technology    | 74        | 1.42%   |
| Unknown             | 67        | 1.29%   |
| Smart               | 66        | 1.27%   |
| Patriot             | 46        | 0.88%   |
| Unknown (ABCD)      | 45        | 0.87%   |
| Team                | 38        | 0.73%   |
| GOODRAM             | 24        | 0.46%   |
| Transcend           | 22        | 0.42%   |
| AMD                 | 21        | 0.4%    |
| Teikon              | 18        | 0.35%   |
| Silicon Power       | 12        | 0.23%   |
| ASint Technology    | 12        | 0.23%   |
| Apacer              | 12        | 0.23%   |
| CSX                 | 11        | 0.21%   |
| Qimonda             | 10        | 0.19%   |
| Unifosa             | 8         | 0.15%   |
| PNY                 | 8         | 0.15%   |
| Kingmax             | 7         | 0.13%   |
| High Bridge         | 7         | 0.13%   |
| GeIL                | 7         | 0.13%   |
| Avant               | 7         | 0.13%   |
| Smart Brazil        | 6         | 0.12%   |
| Goldkey             | 6         | 0.12%   |
| Toshiba             | 5         | 0.1%    |
| Multilaser          | 5         | 0.1%    |
| Timetec             | 4         | 0.08%   |
| Super Talent        | 4         | 0.08%   |
| Sesame              | 4         | 0.08%   |
| OM Nanotech         | 4         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 67        | 1.19%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 62        | 1.1%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 53        | 0.94%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 51        | 0.9%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 51        | 0.9%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 45        | 0.8%    |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 44        | 0.78%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 40        | 0.71%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 35        | 0.62%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 34        | 0.6%    |
| Unknown RAM Module 2GB DIMM SDRAM                                | 34        | 0.6%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 34        | 0.6%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 34        | 0.6%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 34        | 0.6%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 33        | 0.58%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 33        | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 31        | 0.55%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 24        | 0.43%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 23        | 0.41%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 23        | 0.41%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 22        | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 21        | 0.37%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 20        | 0.35%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 20        | 0.35%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 20        | 0.35%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 20        | 0.35%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 20        | 0.35%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 19        | 0.34%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 19        | 0.34%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 19        | 0.34%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s              | 19        | 0.34%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 19        | 0.34%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 19        | 0.34%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 18        | 0.32%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 18        | 0.32%   |
| Micron RAM Module 8GB DIMM DDR4 2666MT/s                         | 18        | 0.32%   |
| Micron RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s             | 18        | 0.32%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s            | 18        | 0.32%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 17        | 0.3%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 1987      | 45.02%  |
| DDR4    | 1457      | 33.01%  |
| DDR2    | 340       | 7.7%    |
| SDRAM   | 212       | 4.8%    |
| Unknown | 190       | 4.3%    |
| LPDDR4  | 140       | 3.17%   |
| DDR     | 38        | 0.86%   |
| LPDDR3  | 33        | 0.75%   |
| DRAM    | 12        | 0.27%   |
| DDR5    | 4         | 0.09%   |
| LPDDR5  | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2276      | 52.39%  |
| DIMM         | 1901      | 43.76%  |
| Row Of Chips | 142       | 3.27%   |
| Chip         | 13        | 0.3%    |
| Unknown      | 5         | 0.12%   |
| FB-DIMM      | 4         | 0.09%   |
| RIMM         | 3         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 1807      | 37.1%   |
| 8192  | 1488      | 30.55%  |
| 2048  | 975       | 20.02%  |
| 16384 | 299       | 6.14%   |
| 1024  | 218       | 4.48%   |
| 32768 | 60        | 1.23%   |
| 512   | 22        | 0.45%   |
| 65536 | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1263      | 25.84%  |
| 1333    | 506       | 10.35%  |
| 2667    | 446       | 9.13%   |
| 2400    | 357       | 7.31%   |
| 3200    | 352       | 7.2%    |
| 1334    | 225       | 4.6%    |
| 800     | 185       | 3.79%   |
| 667     | 172       | 3.52%   |
| 2133    | 166       | 3.4%    |
| Unknown | 139       | 2.84%   |
| 3600    | 109       | 2.23%   |
| 1067    | 95        | 1.94%   |
| 1867    | 92        | 1.88%   |
| 4267    | 60        | 1.23%   |
| 1866    | 56        | 1.15%   |
| 2666    | 55        | 1.13%   |
| 1066    | 51        | 1.04%   |
| 3266    | 46        | 0.94%   |
| 2048    | 42        | 0.86%   |
| 4199    | 40        | 0.82%   |
| 3400    | 35        | 0.72%   |
| 533     | 34        | 0.7%    |
| 3000    | 32        | 0.65%   |
| 975     | 27        | 0.55%   |
| 2933    | 22        | 0.45%   |
| 1800    | 22        | 0.45%   |
| 400     | 22        | 0.45%   |
| 3866    | 17        | 0.35%   |
| 3466    | 16        | 0.33%   |
| 3733    | 14        | 0.29%   |
| 333     | 13        | 0.27%   |
| 8400    | 11        | 0.23%   |
| 2800    | 11        | 0.23%   |
| 3666    | 10        | 0.2%    |
| 4266    | 9         | 0.18%   |
| 3800    | 9         | 0.18%   |
| 1639    | 9         | 0.18%   |
| 49926   | 8         | 0.16%   |
| 3066    | 8         | 0.16%   |
| 2000    | 7         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 63        | 39.38%  |
| Brother Industries    | 34        | 21.25%  |
| Canon                 | 24        | 15%     |
| Samsung Electronics   | 13        | 8.13%   |
| Seiko Epson           | 9         | 5.63%   |
| Lexmark International | 6         | 3.75%   |
| Xerox                 | 2         | 1.25%   |
| Kyocera               | 2         | 1.25%   |
| Zebra                 | 1         | 0.63%   |
| Ricoh                 | 1         | 0.63%   |
| QinHeng Electronics   | 1         | 0.63%   |
| Prolific Technology   | 1         | 0.63%   |
| NXP Semiconductors    | 1         | 0.63%   |
| Dymo-CoStar           | 1         | 0.63%   |
| Citizen               | 1         | 0.63%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Brother DCP-7055W                            | 4         | 2.5%    |
| Samsung M2070 Series                         | 3         | 1.88%   |
| HP LaserJet 1018                             | 3         | 1.88%   |
| HP LaserJet 1010                             | 3         | 1.88%   |
| HP ENVY 4520 series                          | 3         | 1.88%   |
| HP DeskJet 2700 series                       | 3         | 1.88%   |
| Seiko Epson ET-4760 Series                   | 2         | 1.25%   |
| Samsung SCX-3400 Series                      | 2         | 1.25%   |
| Samsung M2020 Series                         | 2         | 1.25%   |
| Samsung CLP-310 Color Laser Printer          | 2         | 1.25%   |
| HP OfficeJet Pro 7740 series                 | 2         | 1.25%   |
| HP LaserJet P1005                            | 2         | 1.25%   |
| HP LaserJet 1200                             | 2         | 1.25%   |
| HP LaserJet 1020                             | 2         | 1.25%   |
| HP Ink Tank Wireless 410 series              | 2         | 1.25%   |
| HP ENVY 4500 series                          | 2         | 1.25%   |
| HP DeskJet 5550                              | 2         | 1.25%   |
| HP DeskJet 2600 series                       | 2         | 1.25%   |
| HP Deskjet 1050 J410                         | 2         | 1.25%   |
| Canon TS5100 series                          | 2         | 1.25%   |
| Canon iP7200 series                          | 2         | 1.25%   |
| Brother MFC-L2710DW series                   | 2         | 1.25%   |
| Brother MFC-J470DW                           | 2         | 1.25%   |
| Brother DCP-T310                             | 2         | 1.25%   |
| Zebra LP2824                                 | 1         | 0.63%   |
| Xerox Phaser 6510                            | 1         | 0.63%   |
| Xerox Phaser 6010N                           | 1         | 0.63%   |
| Seiko Epson XP-2100 Series                   | 1         | 0.63%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 0.63%   |
| Seiko Epson L365 Series                      | 1         | 0.63%   |
| Seiko Epson L355 Series                      | 1         | 0.63%   |
| Seiko Epson L3210 Series                     | 1         | 0.63%   |
| Seiko Epson L120 Series                      | 1         | 0.63%   |
| Seiko Epson ET-3750 Series                   | 1         | 0.63%   |
| Samsung ML-2850 Series                       | 1         | 0.63%   |
| Samsung ML-1640 Series Laser Printer         | 1         | 0.63%   |
| Samsung M267x 287x Series                    | 1         | 0.63%   |
| Samsung CLP-325 Color Laser Printer          | 1         | 0.63%   |
| Ricoh SP 211                                 | 1         | 0.63%   |
| QinHeng CH340S                               | 1         | 0.63%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 15        | 71.43%  |
| Seiko Epson     | 3         | 14.29%  |
| Mustek Systems  | 2         | 9.52%   |
| Hewlett-Packard | 1         | 4.76%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                  | 3         | 14.29%  |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 2         | 9.52%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 9.52%   |
| Canon CanoScan N1240U/LiDE 30                            | 2         | 9.52%   |
| Canon CanoScan LiDE 120                                  | 2         | 9.52%   |
| Canon CanoScan LiDE 100                                  | 2         | 9.52%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 4.76%   |
| Mustek Systems SNAPSCAN e22                              | 1         | 4.76%   |
| Mustek Systems ScanExpress 1200 CU                       | 1         | 4.76%   |
| HP ScanJet 2400c                                         | 1         | 4.76%   |
| Canon CanoScan LiDE 600F                                 | 1         | 4.76%   |
| Canon CanoScan LIDE 25                                   | 1         | 4.76%   |
| Canon CanoScan LiDE 210                                  | 1         | 4.76%   |
| Canon CanoScan 5200F                                     | 1         | 4.76%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 495       | 21.72%  |
| Realtek Semiconductor                  | 257       | 11.28%  |
| Microdia                               | 241       | 10.57%  |
| IMC Networks                           | 134       | 5.88%   |
| Sunplus Innovation Technology          | 131       | 5.75%   |
| Logitech                               | 114       | 5%      |
| Acer                                   | 95        | 4.17%   |
| Suyin                                  | 94        | 4.12%   |
| Quanta                                 | 86        | 3.77%   |
| Cheng Uei Precision Industry (Foxlink) | 85        | 3.73%   |
| Syntek                                 | 60        | 2.63%   |
| Apple                                  | 55        | 2.41%   |
| Lite-On Technology                     | 47        | 2.06%   |
| Silicon Motion                         | 44        | 1.93%   |
| Alcor Micro                            | 37        | 1.62%   |
| Ricoh                                  | 33        | 1.45%   |
| Bison Electronics                      | 26        | 1.14%   |
| Microsoft                              | 22        | 0.97%   |
| ALi                                    | 20        | 0.88%   |
| Importek                               | 17        | 0.75%   |
| Z-Star Microelectronics                | 16        | 0.7%    |
| Lenovo                                 | 16        | 0.7%    |
| Luxvisions Innotech Limited            | 13        | 0.57%   |
| Primax Electronics                     | 11        | 0.48%   |
| Generalplus Technology                 | 10        | 0.44%   |
| Sonix Technology                       | 9         | 0.39%   |
| KYE Systems (Mouse Systems)            | 7         | 0.31%   |
| Samsung Electronics                    | 6         | 0.26%   |
| Cubeternet                             | 6         | 0.26%   |
| Aveo Technology                        | 6         | 0.26%   |
| Sunplus Technology                     | 5         | 0.22%   |
| Hewlett-Packard                        | 5         | 0.22%   |
| DigiTech                               | 5         | 0.22%   |
| Trust                                  | 4         | 0.18%   |
| OmniVision Technologies                | 4         | 0.18%   |
| GEMBIRD                                | 4         | 0.18%   |
| ARC International                      | 4         | 0.18%   |
| Unknown                                | 3         | 0.13%   |
| Jieli Technology                       | 3         | 0.13%   |
| Creative Technology                    | 3         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 99        | 4.27%   |
| Chicony Integrated Camera                               | 66        | 2.85%   |
| Realtek Integrated_Webcam_5M                            | 59        | 2.55%   |
| Realtek Integrated_Webcam_HD                            | 56        | 2.42%   |
| Chicony HD WebCam                                       | 52        | 2.25%   |
| Sunplus Integrated_Webcam_HD                            | 50        | 2.16%   |
| Microdia Integrated Webcam                              | 32        | 1.38%   |
| Syntek Integrated Camera                                | 30        | 1.3%    |
| Logitech Webcam C270                                    | 28        | 1.21%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 27        | 1.17%   |
| IMC Networks Integrated Camera                          | 25        | 1.08%   |
| Realtek USB Camera                                      | 22        | 0.95%   |
| Chicony USB 2.0 Camera                                  | 22        | 0.95%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 21        | 0.91%   |
| Chicony TOSHIBA Web Camera - HD                         | 21        | 0.91%   |
| Chicony Lenovo EasyCamera                               | 21        | 0.91%   |
| Microdia USB 2.0 Camera                                 | 20        | 0.86%   |
| Chicony VGA Webcam                                      | 20        | 0.86%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 19        | 0.82%   |
| Chicony USB2.0 VGA UVC WebCam                           | 19        | 0.82%   |
| Apple Built-in iSight                                   | 18        | 0.78%   |
| Sunplus HD WebCam                                       | 17        | 0.73%   |
| Microdia Integrated_Webcam_5M                           | 17        | 0.73%   |
| Chicony FJ Camera                                       | 17        | 0.73%   |
| Quanta HD User Facing                                   | 16        | 0.69%   |
| Chicony HP Truevision HD                                | 16        | 0.69%   |
| Chicony HD User Facing                                  | 16        | 0.69%   |
| Realtek EasyCamera                                      | 15        | 0.65%   |
| Chicony HP TrueVision HD Camera                         | 15        | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 15        | 0.65%   |
| Apple FaceTime HD Camera (Built-in)                     | 15        | 0.65%   |
| Acer Lenovo EasyCamera                                  | 15        | 0.65%   |
| Quanta HP TrueVision HD Camera                          | 14        | 0.6%    |
| Logitech HD Webcam C525                                 | 14        | 0.6%    |
| Lite-On Integrated Camera                               | 14        | 0.6%    |
| Chicony USB2.0 HD UVC WebCam                            | 14        | 0.6%    |
| Acer Integrated Camera                                  | 14        | 0.6%    |
| Realtek Lenovo EasyCamera                               | 13        | 0.56%   |
| Quanta VGA WebCam                                       | 13        | 0.56%   |
| Logitech HD Pro Webcam C920                             | 13        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 81        | 38.39%  |
| AuthenTec                  | 30        | 14.22%  |
| Upek                       | 24        | 11.37%  |
| Elan Microelectronics      | 18        | 8.53%   |
| Synaptics                  | 17        | 8.06%   |
| Shenzhen Goodix Technology | 17        | 8.06%   |
| LighTuning Technology      | 11        | 5.21%   |
| STMicroelectronics         | 10        | 4.74%   |
| Samsung Electronics        | 1         | 0.47%   |
| HOLTEK                     | 1         | 0.47%   |
| Focal-systems.Corp         | 1         | 0.47%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 23        | 10.9%   |
| Validity Sensors VFS495 Fingerprint Reader                  | 21        | 9.95%   |
| Shenzhen Goodix  Fingerprint Device                         | 11        | 5.21%   |
| STMicroelectronics Fingerprint Reader                       | 10        | 4.74%   |
| Elan ELAN:Fingerprint                                       | 10        | 4.74%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 8         | 3.79%   |
| Elan ELAN:ARM-M4                                            | 8         | 3.79%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor           | 7         | 3.32%   |
| Validity Sensors VFS491                                     | 7         | 3.32%   |
| AuthenTec AES2810                                           | 7         | 3.32%   |
| AuthenTec AES2501 Fingerprint Sensor                        | 7         | 3.32%   |
| AuthenTec AES1600                                           | 7         | 3.32%   |
| Validity Sensors Swipe Fingerprint Sensor                   | 6         | 2.84%   |
| Validity Sensors VFS5011 Fingerprint Reader                 | 5         | 2.37%   |
| Validity Sensors Synaptics WBDI                             | 5         | 2.37%   |
| Shenzhen Goodix Fingerprint Reader                          | 5         | 2.37%   |
| LighTuning EgisTec Touch Fingerprint Sensor                 | 5         | 2.37%   |
| AuthenTec Fingerprint Sensor                                | 5         | 2.37%   |
| Validity Sensors VFS471 Fingerprint Reader                  | 4         | 1.9%    |
| Validity Sensors VFS301 Fingerprint Reader                  | 4         | 1.9%    |
| Validity Sensors Fingerprint scanner                        | 4         | 1.9%    |
| Synaptics UWP WBDI                                          | 4         | 1.9%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 4         | 1.9%    |
| Validity Sensors VFS451 Fingerprint Reader                  | 3         | 1.42%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint  | 3         | 1.42%   |
| LighTuning ES603 Swipe Fingerprint Sensor                   | 3         | 1.42%   |
| AuthenTec AES2550 Fingerprint Sensor                        | 3         | 1.42%   |
| Validity Sensors VFS300 Fingerprint Reader                  | 2         | 0.95%   |
| Validity Sensors VFS101 Fingerprint Reader                  | 2         | 0.95%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 2         | 0.95%   |
| LighTuning Fingerprint Reader                               | 2         | 0.95%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor           | 1         | 0.47%   |
| Upek TCS5B Fingerprint sensor                               | 1         | 0.47%   |
| Synaptics WBDI Fingerprint Reader USB 102                   | 1         | 0.47%   |
| Synaptics WBDI Device                                       | 1         | 0.47%   |
| Synaptics  WBDI                                             | 1         | 0.47%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint   | 1         | 0.47%   |
| Synaptics Metallica MOH Touch Fingerprint Reader            | 1         | 0.47%   |
| Synaptics Metallica MIS Touch Fingerprint Reader            | 1         | 0.47%   |
| Shenzhen Goodix FingerPrint                                 | 1         | 0.47%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 83        | 53.21%  |
| O2 Micro              | 18        | 11.54%  |
| Alcor Micro           | 18        | 11.54%  |
| Upek                  | 14        | 8.97%   |
| Lenovo                | 11        | 7.05%   |
| SCM Microsystems      | 3         | 1.92%   |
| Realtek Semiconductor | 3         | 1.92%   |
| Gemalto (was Gemplus) | 3         | 1.92%   |
| BIT4ID                | 2         | 1.28%   |
| Cherry                | 1         | 0.64%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 39        | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 24        | 15.38%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 17        | 10.9%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 17        | 10.9%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 14        | 8.97%   |
| Broadcom 5880                                                                | 14        | 8.97%   |
| Lenovo Integrated Smart Card Reader                                          | 11        | 7.05%   |
| Broadcom 58200                                                               | 5         | 3.21%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 1.92%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.28%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.28%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                              | 1         | 0.64%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.64%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.64%   |
| Cherry Smart Terminal XX44                                                   | 1         | 0.64%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.64%   |
| BIT4ID miniLector EVO                                                        | 1         | 0.64%   |
| BIT4ID miniLector AIR NFC v3                                                 | 1         | 0.64%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.64%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3583      | 82.01%  |
| 1     | 680       | 15.56%  |
| 2     | 94        | 2.15%   |
| 3     | 9         | 0.21%   |
| 7     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |
| 4     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 211       | 23.87%  |
| Graphics card            | 193       | 21.83%  |
| Chipcard                 | 151       | 17.08%  |
| Net/wireless             | 80        | 9.05%   |
| Multimedia controller    | 76        | 8.6%    |
| Bluetooth                | 61        | 6.9%    |
| Storage                  | 28        | 3.17%   |
| Communication controller | 23        | 2.6%    |
| Camera                   | 22        | 2.49%   |
| Unassigned class         | 16        | 1.81%   |
| Network                  | 7         | 0.79%   |
| Sound                    | 4         | 0.45%   |
| Wireless                 | 3         | 0.34%   |
| Flash memory             | 3         | 0.34%   |
| Storage/raid             | 2         | 0.23%   |
| Net/ethernet             | 2         | 0.23%   |
| Card reader              | 2         | 0.23%   |

