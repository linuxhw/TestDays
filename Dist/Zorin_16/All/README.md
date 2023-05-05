Zorin 16 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin_16/Desktop/README.md) and [notebooks](/Dist/Zorin_16/Notebook/README.md).

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

Total: 4421

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PN41                        | Mini pc     | [99d3eca719](https://linux-hardware.org/?probe=99d3eca719) | May 01, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [1a00a1321e](https://linux-hardware.org/?probe=1a00a1321e) | Apr 30, 2023 |
| MSI           | IONA                        | Desktop     | [966ec83038](https://linux-hardware.org/?probe=966ec83038) | Apr 30, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [6987a21849](https://linux-hardware.org/?probe=6987a21849) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [946a95c594](https://linux-hardware.org/?probe=946a95c594) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [58cebf39d1](https://linux-hardware.org/?probe=58cebf39d1) | Apr 30, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f1faff33de](https://linux-hardware.org/?probe=f1faff33de) | Apr 30, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [8b89ffd983](https://linux-hardware.org/?probe=8b89ffd983) | Apr 30, 2023 |
| HP            | Pavilion dv7                | Notebook    | [68b51fde68](https://linux-hardware.org/?probe=68b51fde68) | Apr 30, 2023 |
| Positivo      | S14CT01                     | Notebook    | [b11ef938e1](https://linux-hardware.org/?probe=b11ef938e1) | Apr 29, 2023 |
| Toshiba       | Satellite C650D             | Notebook    | [472dedd62a](https://linux-hardware.org/?probe=472dedd62a) | Apr 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [4b0542737c](https://linux-hardware.org/?probe=4b0542737c) | Apr 29, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [6bad65ad2d](https://linux-hardware.org/?probe=6bad65ad2d) | Apr 29, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [25bc3aa225](https://linux-hardware.org/?probe=25bc3aa225) | Apr 29, 2023 |
| Sony          | VPCF215FX                   | Notebook    | [49c7606269](https://linux-hardware.org/?probe=49c7606269) | Apr 29, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [58b09d7887](https://linux-hardware.org/?probe=58b09d7887) | Apr 29, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [7d91fe30f7](https://linux-hardware.org/?probe=7d91fe30f7) | Apr 29, 2023 |
| Positivo      | S14CT01                     | Notebook    | [58988f4876](https://linux-hardware.org/?probe=58988f4876) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [e908fdb73d](https://linux-hardware.org/?probe=e908fdb73d) | Apr 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [a984eefe43](https://linux-hardware.org/?probe=a984eefe43) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [d9010fa8d0](https://linux-hardware.org/?probe=d9010fa8d0) | Apr 28, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [2b5c6e2ded](https://linux-hardware.org/?probe=2b5c6e2ded) | Apr 28, 2023 |
| HP            | Laptop 14-em0xxx            | Notebook    | [8d06549ae0](https://linux-hardware.org/?probe=8d06549ae0) | Apr 28, 2023 |
| Lenovo        | IdeaPad Y470                | Notebook    | [58c809428e](https://linux-hardware.org/?probe=58c809428e) | Apr 28, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [896574c24a](https://linux-hardware.org/?probe=896574c24a) | Apr 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [f1290d4846](https://linux-hardware.org/?probe=f1290d4846) | Apr 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [c4941a5c16](https://linux-hardware.org/?probe=c4941a5c16) | Apr 27, 2023 |
| Pegatron      | IPM41-D3                    | Desktop     | [faf8704eb3](https://linux-hardware.org/?probe=faf8704eb3) | Apr 26, 2023 |
| Dell          | Vostro 1510                 | Notebook    | [71c860d51c](https://linux-hardware.org/?probe=71c860d51c) | Apr 26, 2023 |
| Medion        | E2215T MD60198              | Notebook    | [390ccbba6f](https://linux-hardware.org/?probe=390ccbba6f) | Apr 26, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [86dad710fa](https://linux-hardware.org/?probe=86dad710fa) | Apr 26, 2023 |
| Lenovo        | 3000 N200 0769A97           | Notebook    | [a293f4f1f7](https://linux-hardware.org/?probe=a293f4f1f7) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [c40de2e155](https://linux-hardware.org/?probe=c40de2e155) | Apr 26, 2023 |
| Intel         | D34010WYK H14771-304        | Desktop     | [4fbbe6e603](https://linux-hardware.org/?probe=4fbbe6e603) | Apr 26, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Desktop     | [07e9099105](https://linux-hardware.org/?probe=07e9099105) | Apr 26, 2023 |
| HP            | 1632                        | Desktop     | [0355cb4e69](https://linux-hardware.org/?probe=0355cb4e69) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [7abd61de30](https://linux-hardware.org/?probe=7abd61de30) | Apr 25, 2023 |
| HP            | EliteBook 2730p             | Notebook    | [51c0fadfdb](https://linux-hardware.org/?probe=51c0fadfdb) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [927c9a0377](https://linux-hardware.org/?probe=927c9a0377) | Apr 25, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [4231d023e9](https://linux-hardware.org/?probe=4231d023e9) | Apr 25, 2023 |
| eMachines     | MCP61PM-GM                  | Desktop     | [ff00693839](https://linux-hardware.org/?probe=ff00693839) | Apr 25, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [9bab79728a](https://linux-hardware.org/?probe=9bab79728a) | Apr 24, 2023 |
| Toshiba       | Satellite C45-A             | Notebook    | [7720195dfe](https://linux-hardware.org/?probe=7720195dfe) | Apr 24, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [57e3cfa7dc](https://linux-hardware.org/?probe=57e3cfa7dc) | Apr 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [9d5ada0fc4](https://linux-hardware.org/?probe=9d5ada0fc4) | Apr 24, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [154380c27c](https://linux-hardware.org/?probe=154380c27c) | Apr 24, 2023 |
| Dell          | Inspiron 5565               | Notebook    | [6622474d4b](https://linux-hardware.org/?probe=6622474d4b) | Apr 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [60d1d4aec8](https://linux-hardware.org/?probe=60d1d4aec8) | Apr 24, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [c087d6cbae](https://linux-hardware.org/?probe=c087d6cbae) | Apr 24, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [3d07651a47](https://linux-hardware.org/?probe=3d07651a47) | Apr 24, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [d9429d7e06](https://linux-hardware.org/?probe=d9429d7e06) | Apr 23, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1BH0... | Notebook    | [b76462c15b](https://linux-hardware.org/?probe=b76462c15b) | Apr 23, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [8db1376917](https://linux-hardware.org/?probe=8db1376917) | Apr 23, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [5f771d8ee5](https://linux-hardware.org/?probe=5f771d8ee5) | Apr 23, 2023 |
| Unknown       | G41                         | Desktop     | [cbe978cc34](https://linux-hardware.org/?probe=cbe978cc34) | Apr 23, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [49a0b005f8](https://linux-hardware.org/?probe=49a0b005f8) | Apr 23, 2023 |
| MSI           | GP62 7RD                    | Notebook    | [277bb2d2e3](https://linux-hardware.org/?probe=277bb2d2e3) | Apr 23, 2023 |
| Acer          | AOD270                      | Notebook    | [d7d653d3d6](https://linux-hardware.org/?probe=d7d653d3d6) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [25ee911879](https://linux-hardware.org/?probe=25ee911879) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [468824c4d9](https://linux-hardware.org/?probe=468824c4d9) | Apr 23, 2023 |
| Gigabyte      | B760M GAMING X AX DDR4      | Desktop     | [a68d32d442](https://linux-hardware.org/?probe=a68d32d442) | Apr 23, 2023 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [401f407dae](https://linux-hardware.org/?probe=401f407dae) | Apr 23, 2023 |
| HP            | Laptop 14-em0xxx            | Notebook    | [55ea4ded18](https://linux-hardware.org/?probe=55ea4ded18) | Apr 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [3c3719b07f](https://linux-hardware.org/?probe=3c3719b07f) | Apr 22, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [206de0188d](https://linux-hardware.org/?probe=206de0188d) | Apr 22, 2023 |
| Lenovo        | B590 62743NG                | Notebook    | [ca0be4b423](https://linux-hardware.org/?probe=ca0be4b423) | Apr 22, 2023 |
| Lenovo        | B590 62743NG                | Notebook    | [74e38a8db9](https://linux-hardware.org/?probe=74e38a8db9) | Apr 22, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [e60b9070a6](https://linux-hardware.org/?probe=e60b9070a6) | Apr 22, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [b19724085f](https://linux-hardware.org/?probe=b19724085f) | Apr 21, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [4dc6862db9](https://linux-hardware.org/?probe=4dc6862db9) | Apr 21, 2023 |
| Lenovo        | IdeaPadFlex 6-14IKB 81EM    | Convertible | [0a5da1a9a0](https://linux-hardware.org/?probe=0a5da1a9a0) | Apr 21, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [570077aa64](https://linux-hardware.org/?probe=570077aa64) | Apr 21, 2023 |
| AIERXUAN      | XIAOXUAN Pro                | Notebook    | [e472034313](https://linux-hardware.org/?probe=e472034313) | Apr 21, 2023 |
| AIERXUAN      | XIAOXUAN Pro                | Notebook    | [e500ddd5d9](https://linux-hardware.org/?probe=e500ddd5d9) | Apr 21, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [6222a9aa08](https://linux-hardware.org/?probe=6222a9aa08) | Apr 21, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [de196a2cfa](https://linux-hardware.org/?probe=de196a2cfa) | Apr 21, 2023 |
| Microsoft     | Surface Book                | Tablet      | [13c23678aa](https://linux-hardware.org/?probe=13c23678aa) | Apr 21, 2023 |
| MSI           | GS73VR 7RF                  | Notebook    | [2eb85cc7fe](https://linux-hardware.org/?probe=2eb85cc7fe) | Apr 20, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [d428839f7c](https://linux-hardware.org/?probe=d428839f7c) | Apr 20, 2023 |
| HP            | 2ADE                        | Desktop     | [1a3d108a58](https://linux-hardware.org/?probe=1a3d108a58) | Apr 20, 2023 |
| HP            | 8054                        | Desktop     | [0f2c12c877](https://linux-hardware.org/?probe=0f2c12c877) | Apr 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [7d380bf016](https://linux-hardware.org/?probe=7d380bf016) | Apr 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [7029b5ee48](https://linux-hardware.org/?probe=7029b5ee48) | Apr 20, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [9093d27c30](https://linux-hardware.org/?probe=9093d27c30) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [069a675d2a](https://linux-hardware.org/?probe=069a675d2a) | Apr 19, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [bb0be3d9e3](https://linux-hardware.org/?probe=bb0be3d9e3) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [e58c3ad9d7](https://linux-hardware.org/?probe=e58c3ad9d7) | Apr 19, 2023 |
| Lenovo        | SHARKBAY 31900058 STD or... | Desktop     | [1331c6ef06](https://linux-hardware.org/?probe=1331c6ef06) | Apr 19, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [65eb0fa6be](https://linux-hardware.org/?probe=65eb0fa6be) | Apr 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [c36b1a5778](https://linux-hardware.org/?probe=c36b1a5778) | Apr 19, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [86e2d42f73](https://linux-hardware.org/?probe=86e2d42f73) | Apr 19, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [1548cc4309](https://linux-hardware.org/?probe=1548cc4309) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [85c7be8d12](https://linux-hardware.org/?probe=85c7be8d12) | Apr 19, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [2a7fe6d74b](https://linux-hardware.org/?probe=2a7fe6d74b) | Apr 18, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [be92b53515](https://linux-hardware.org/?probe=be92b53515) | Apr 18, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [7da02a75b5](https://linux-hardware.org/?probe=7da02a75b5) | Apr 18, 2023 |
| ASL           | BayTrail JHS773             | Desktop     | [3a5977ad04](https://linux-hardware.org/?probe=3a5977ad04) | Apr 18, 2023 |
| Dell          | 0T656F A02                  | Desktop     | [0d291f14a1](https://linux-hardware.org/?probe=0d291f14a1) | Apr 18, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [119560d8db](https://linux-hardware.org/?probe=119560d8db) | Apr 17, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [79029817b8](https://linux-hardware.org/?probe=79029817b8) | Apr 17, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a99920ebba](https://linux-hardware.org/?probe=a99920ebba) | Apr 17, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [2f60207985](https://linux-hardware.org/?probe=2f60207985) | Apr 17, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [307e22b0d6](https://linux-hardware.org/?probe=307e22b0d6) | Apr 17, 2023 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [895f57e6d5](https://linux-hardware.org/?probe=895f57e6d5) | Apr 17, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [b2311e7cac](https://linux-hardware.org/?probe=b2311e7cac) | Apr 17, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [b9d869fe6b](https://linux-hardware.org/?probe=b9d869fe6b) | Apr 16, 2023 |
| Dell          | Vostro 3580                 | Notebook    | [b7d9953b54](https://linux-hardware.org/?probe=b7d9953b54) | Apr 16, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [f146ce9da7](https://linux-hardware.org/?probe=f146ce9da7) | Apr 16, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [ea8d83a743](https://linux-hardware.org/?probe=ea8d83a743) | Apr 16, 2023 |
| Lenovo        | ThinkPad P52s 20LCS1DU01    | Notebook    | [3fc78b3451](https://linux-hardware.org/?probe=3fc78b3451) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [a56688fd70](https://linux-hardware.org/?probe=a56688fd70) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [798405022f](https://linux-hardware.org/?probe=798405022f) | Apr 16, 2023 |
| AZW           | SEi                         | Notebook    | [a382976bf2](https://linux-hardware.org/?probe=a382976bf2) | Apr 15, 2023 |
| AZW           | SEi                         | Notebook    | [980b83cf5e](https://linux-hardware.org/?probe=980b83cf5e) | Apr 15, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [2b6f0394d7](https://linux-hardware.org/?probe=2b6f0394d7) | Apr 15, 2023 |
| Acer          | Aspire ES1-731G             | Notebook    | [1ef0f89c83](https://linux-hardware.org/?probe=1ef0f89c83) | Apr 15, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [ba3d9dd7e7](https://linux-hardware.org/?probe=ba3d9dd7e7) | Apr 15, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [506ba2605a](https://linux-hardware.org/?probe=506ba2605a) | Apr 15, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [c7568482a9](https://linux-hardware.org/?probe=c7568482a9) | Apr 15, 2023 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [b66c208e18](https://linux-hardware.org/?probe=b66c208e18) | Apr 15, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [2ca7c3fccc](https://linux-hardware.org/?probe=2ca7c3fccc) | Apr 15, 2023 |
| Intel         | H61                         | Desktop     | [81c7094e68](https://linux-hardware.org/?probe=81c7094e68) | Apr 15, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [a4c5130b84](https://linux-hardware.org/?probe=a4c5130b84) | Apr 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [e122e8dab8](https://linux-hardware.org/?probe=e122e8dab8) | Apr 15, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [d50de3a52c](https://linux-hardware.org/?probe=d50de3a52c) | Apr 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [fcfa1ed488](https://linux-hardware.org/?probe=fcfa1ed488) | Apr 14, 2023 |
| Biostar       | TZ75B                       | Desktop     | [c6720e2db2](https://linux-hardware.org/?probe=c6720e2db2) | Apr 14, 2023 |
| Foxconn       | G31MVP FAB:1.0              | Desktop     | [41eac5ca2f](https://linux-hardware.org/?probe=41eac5ca2f) | Apr 14, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [e9c2f8d5ba](https://linux-hardware.org/?probe=e9c2f8d5ba) | Apr 14, 2023 |
| HP            | 8430 1000                   | All in one  | [b813f95c6f](https://linux-hardware.org/?probe=b813f95c6f) | Apr 14, 2023 |
| HP            | 8430 1000                   | All in one  | [59572d294b](https://linux-hardware.org/?probe=59572d294b) | Apr 14, 2023 |
| Positivo      | Q4128C-S                    | Notebook    | [8dc2eb7738](https://linux-hardware.org/?probe=8dc2eb7738) | Apr 14, 2023 |
| Intel         | H61                         | Desktop     | [8aeeb449f8](https://linux-hardware.org/?probe=8aeeb449f8) | Apr 14, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [9da868694f](https://linux-hardware.org/?probe=9da868694f) | Apr 14, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [75ce029800](https://linux-hardware.org/?probe=75ce029800) | Apr 13, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [4267100894](https://linux-hardware.org/?probe=4267100894) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [5e9f89e556](https://linux-hardware.org/?probe=5e9f89e556) | Apr 13, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [9e6cfba525](https://linux-hardware.org/?probe=9e6cfba525) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [d72e78c1b0](https://linux-hardware.org/?probe=d72e78c1b0) | Apr 13, 2023 |
| Acer          | Aspire E5-771G              | Notebook    | [504d600530](https://linux-hardware.org/?probe=504d600530) | Apr 13, 2023 |
| HP            | Compaq Presario F700        | Notebook    | [2ae0d7557b](https://linux-hardware.org/?probe=2ae0d7557b) | Apr 13, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [ac4059b403](https://linux-hardware.org/?probe=ac4059b403) | Apr 13, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [6f7e9a6bb2](https://linux-hardware.org/?probe=6f7e9a6bb2) | Apr 13, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [27bfaf568a](https://linux-hardware.org/?probe=27bfaf568a) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [653a25793d](https://linux-hardware.org/?probe=653a25793d) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [dccecbecf9](https://linux-hardware.org/?probe=dccecbecf9) | Apr 12, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [878333e620](https://linux-hardware.org/?probe=878333e620) | Apr 12, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [b504683b39](https://linux-hardware.org/?probe=b504683b39) | Apr 12, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [8b8d053221](https://linux-hardware.org/?probe=8b8d053221) | Apr 12, 2023 |
| Toshiba       | Satellite C650D             | Notebook    | [fb8b24d111](https://linux-hardware.org/?probe=fb8b24d111) | Apr 12, 2023 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [82a946e356](https://linux-hardware.org/?probe=82a946e356) | Apr 12, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [1627e0654a](https://linux-hardware.org/?probe=1627e0654a) | Apr 11, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [57aa7d103d](https://linux-hardware.org/?probe=57aa7d103d) | Apr 11, 2023 |
| ASUSTek       | P5K                         | Desktop     | [36bc294c5b](https://linux-hardware.org/?probe=36bc294c5b) | Apr 11, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a2aa745e5c](https://linux-hardware.org/?probe=a2aa745e5c) | Apr 10, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [1bc09aed8a](https://linux-hardware.org/?probe=1bc09aed8a) | Apr 10, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [f847287142](https://linux-hardware.org/?probe=f847287142) | Apr 09, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [5c0467f4cb](https://linux-hardware.org/?probe=5c0467f4cb) | Apr 09, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [f410666614](https://linux-hardware.org/?probe=f410666614) | Apr 09, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [a651483f3c](https://linux-hardware.org/?probe=a651483f3c) | Apr 07, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c871e7c68b](https://linux-hardware.org/?probe=c871e7c68b) | Apr 07, 2023 |
| Thomson       | WWNEO14C-4BK32F             | Notebook    | [8b461d224b](https://linux-hardware.org/?probe=8b461d224b) | Apr 06, 2023 |
| Quanta        | XV1                         | All in one  | [7cce1c6f6f](https://linux-hardware.org/?probe=7cce1c6f6f) | Apr 06, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [27e5e2df0d](https://linux-hardware.org/?probe=27e5e2df0d) | Apr 06, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [ecba971f16](https://linux-hardware.org/?probe=ecba971f16) | Apr 06, 2023 |
| HP            | ProBook 4540s               | Notebook    | [02754e47f3](https://linux-hardware.org/?probe=02754e47f3) | Apr 05, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [5363e4031e](https://linux-hardware.org/?probe=5363e4031e) | Apr 05, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [085dc66a77](https://linux-hardware.org/?probe=085dc66a77) | Apr 05, 2023 |
| HP            | Notebook                    | Notebook    | [4ac4839ccd](https://linux-hardware.org/?probe=4ac4839ccd) | Apr 05, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [5a864191a9](https://linux-hardware.org/?probe=5a864191a9) | Apr 05, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [bb24498044](https://linux-hardware.org/?probe=bb24498044) | Apr 05, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [68d14e873f](https://linux-hardware.org/?probe=68d14e873f) | Apr 05, 2023 |
| eMachines     | MCP61PM-GM                  | Desktop     | [dc35ec4564](https://linux-hardware.org/?probe=dc35ec4564) | Apr 04, 2023 |
| Google        | Cyan                        | Notebook    | [f02aa2a210](https://linux-hardware.org/?probe=f02aa2a210) | Apr 04, 2023 |
| Gigabyte      | H410M S2 V3                 | Desktop     | [fdff0f112e](https://linux-hardware.org/?probe=fdff0f112e) | Apr 04, 2023 |
| HP            | 82B5                        | All in one  | [59fe255866](https://linux-hardware.org/?probe=59fe255866) | Apr 04, 2023 |
| Medion        | MS-7707                     | Desktop     | [c490d9dc74](https://linux-hardware.org/?probe=c490d9dc74) | Apr 04, 2023 |
| eMachines     | MCP61PM-GM                  | Desktop     | [59f9325843](https://linux-hardware.org/?probe=59f9325843) | Apr 03, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [190547d5cd](https://linux-hardware.org/?probe=190547d5cd) | Apr 03, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [e05fcde338](https://linux-hardware.org/?probe=e05fcde338) | Apr 03, 2023 |
| Acer          | Veriton X4610G              | Desktop     | [49b3c45306](https://linux-hardware.org/?probe=49b3c45306) | Apr 03, 2023 |
| Dell          | Latitude E6430              | Notebook    | [5c205ea646](https://linux-hardware.org/?probe=5c205ea646) | Apr 03, 2023 |
| Fujitsu       | LIFEBOOK T935               | Notebook    | [1cc4178b9a](https://linux-hardware.org/?probe=1cc4178b9a) | Apr 02, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [f78d5a9d04](https://linux-hardware.org/?probe=f78d5a9d04) | Apr 02, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [45086032e1](https://linux-hardware.org/?probe=45086032e1) | Apr 02, 2023 |
| Notebook      | NJ50GU                      | Notebook    | [91e860cd94](https://linux-hardware.org/?probe=91e860cd94) | Apr 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [ea4626fdcc](https://linux-hardware.org/?probe=ea4626fdcc) | Apr 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [118effffda](https://linux-hardware.org/?probe=118effffda) | Apr 02, 2023 |
| Dell          | 0D883F A04                  | Desktop     | [5bdaaa0d23](https://linux-hardware.org/?probe=5bdaaa0d23) | Apr 02, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [8a8a256b79](https://linux-hardware.org/?probe=8a8a256b79) | Apr 02, 2023 |
| Fujitsu       | STYLISTIC Q508              | Tablet      | [50862798b5](https://linux-hardware.org/?probe=50862798b5) | Apr 02, 2023 |
| Fujitsu       | STYLISTIC Q508              | Tablet      | [1340f929dd](https://linux-hardware.org/?probe=1340f929dd) | Apr 02, 2023 |
| Monster       | HUMA H4 V5.2                | Notebook    | [fdd74dbc8c](https://linux-hardware.org/?probe=fdd74dbc8c) | Apr 02, 2023 |
| Lenovo        | ThinkPad 10 20C3S0Q200      | Tablet      | [e014609915](https://linux-hardware.org/?probe=e014609915) | Apr 01, 2023 |
| Pegatron      | 2ACF                        | Desktop     | [c015b7fd50](https://linux-hardware.org/?probe=c015b7fd50) | Apr 01, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [644ab9aa21](https://linux-hardware.org/?probe=644ab9aa21) | Apr 01, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [61b490cae8](https://linux-hardware.org/?probe=61b490cae8) | Apr 01, 2023 |
| Lenovo        | ThinkPad 10 20C3S0Q200      | Tablet      | [9ee9bc67cf](https://linux-hardware.org/?probe=9ee9bc67cf) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [1fb4c6ac6a](https://linux-hardware.org/?probe=1fb4c6ac6a) | Apr 01, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [2132a3308c](https://linux-hardware.org/?probe=2132a3308c) | Apr 01, 2023 |
| Acer          | Predator G3-605             | Desktop     | [eb21663788](https://linux-hardware.org/?probe=eb21663788) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [80bb5bbf28](https://linux-hardware.org/?probe=80bb5bbf28) | Apr 01, 2023 |
| Lenovo        | ThinkPad T410 2518P9G       | Notebook    | [4f74fa6cd2](https://linux-hardware.org/?probe=4f74fa6cd2) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [1fa4ec7b05](https://linux-hardware.org/?probe=1fa4ec7b05) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [2e79b95cb4](https://linux-hardware.org/?probe=2e79b95cb4) | Apr 01, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [1f0b0c32ca](https://linux-hardware.org/?probe=1f0b0c32ca) | Apr 01, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [af258dcd36](https://linux-hardware.org/?probe=af258dcd36) | Mar 31, 2023 |
| ASUSTek       | X450LD                      | Notebook    | [1ca0cdc1e8](https://linux-hardware.org/?probe=1ca0cdc1e8) | Mar 31, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [ca6aacf14e](https://linux-hardware.org/?probe=ca6aacf14e) | Mar 31, 2023 |
| Positivo      | S14SL01                     | Notebook    | [e1c79f71b7](https://linux-hardware.org/?probe=e1c79f71b7) | Mar 30, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [2c13e40cd2](https://linux-hardware.org/?probe=2c13e40cd2) | Mar 30, 2023 |
| ASUSTek       | Benicia                     | Desktop     | [7332efabad](https://linux-hardware.org/?probe=7332efabad) | Mar 30, 2023 |
| HP            | kip                         | Notebook    | [fe84eac39e](https://linux-hardware.org/?probe=fe84eac39e) | Mar 30, 2023 |
| Positivo      | Q232A                       | Notebook    | [2282c5ce96](https://linux-hardware.org/?probe=2282c5ce96) | Mar 30, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [0e8950a217](https://linux-hardware.org/?probe=0e8950a217) | Mar 30, 2023 |
| Positivo      | Q232A                       | Notebook    | [98e6b249af](https://linux-hardware.org/?probe=98e6b249af) | Mar 29, 2023 |
| HOUTER        | ORO-PC                      | Desktop     | [9547c4bdac](https://linux-hardware.org/?probe=9547c4bdac) | Mar 29, 2023 |
| Acer          | FIH57                       | All in one  | [7a6b0e67f0](https://linux-hardware.org/?probe=7a6b0e67f0) | Mar 29, 2023 |
| Dell          | Precision M4500             | Notebook    | [cf7e033a17](https://linux-hardware.org/?probe=cf7e033a17) | Mar 29, 2023 |
| Dell          | Latitude 7430               | Notebook    | [fdef205301](https://linux-hardware.org/?probe=fdef205301) | Mar 29, 2023 |
| Dell          | Latitude 3590               | Notebook    | [9b5971401c](https://linux-hardware.org/?probe=9b5971401c) | Mar 29, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [a927671ce2](https://linux-hardware.org/?probe=a927671ce2) | Mar 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ebf2728d28](https://linux-hardware.org/?probe=ebf2728d28) | Mar 29, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [422e4056ea](https://linux-hardware.org/?probe=422e4056ea) | Mar 28, 2023 |
| MSI           | B560M-A PRO                 | Desktop     | [62bfea11fe](https://linux-hardware.org/?probe=62bfea11fe) | Mar 28, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [c97dbb0917](https://linux-hardware.org/?probe=c97dbb0917) | Mar 28, 2023 |
| Thomson       | WWNEO14C-4BK32F             | Notebook    | [90fa9585c9](https://linux-hardware.org/?probe=90fa9585c9) | Mar 28, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [ccef379a7f](https://linux-hardware.org/?probe=ccef379a7f) | Mar 28, 2023 |
| ASRock        | Z68 Pro3-M                  | Desktop     | [60f0809fbf](https://linux-hardware.org/?probe=60f0809fbf) | Mar 28, 2023 |
| Toshiba       | Satellite C55-A-1J8         | Notebook    | [c6ba40cd5c](https://linux-hardware.org/?probe=c6ba40cd5c) | Mar 27, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [dcbcf69a04](https://linux-hardware.org/?probe=dcbcf69a04) | Mar 27, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [dd242e4ae3](https://linux-hardware.org/?probe=dd242e4ae3) | Mar 27, 2023 |
| Dell          | 0J8H4R A00                  | Desktop     | [63d85fd315](https://linux-hardware.org/?probe=63d85fd315) | Mar 27, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [cf226d028d](https://linux-hardware.org/?probe=cf226d028d) | Mar 27, 2023 |
| HP            | 8430 1000                   | All in one  | [c0d9a96bbf](https://linux-hardware.org/?probe=c0d9a96bbf) | Mar 27, 2023 |
| Lenovo        | 11061GG ThinkServer TS13... | Desktop     | [174e514c30](https://linux-hardware.org/?probe=174e514c30) | Mar 26, 2023 |
| Packard Be... | MCP73PV                     | Desktop     | [87d1fd7511](https://linux-hardware.org/?probe=87d1fd7511) | Mar 26, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [05ecadea38](https://linux-hardware.org/?probe=05ecadea38) | Mar 26, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [76fc7291a6](https://linux-hardware.org/?probe=76fc7291a6) | Mar 26, 2023 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [c322e1c537](https://linux-hardware.org/?probe=c322e1c537) | Mar 26, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [7fa1fc4759](https://linux-hardware.org/?probe=7fa1fc4759) | Mar 26, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [cca501adf9](https://linux-hardware.org/?probe=cca501adf9) | Mar 26, 2023 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [b4787579d2](https://linux-hardware.org/?probe=b4787579d2) | Mar 25, 2023 |
| HP            | Compaq 6730s                | Notebook    | [ca30390612](https://linux-hardware.org/?probe=ca30390612) | Mar 25, 2023 |
| AZW           | MINI S                      | Desktop     | [f3381963ae](https://linux-hardware.org/?probe=f3381963ae) | Mar 25, 2023 |
| ASRock        | AB350 Gaming K4             | Desktop     | [ecc09c1362](https://linux-hardware.org/?probe=ecc09c1362) | Mar 25, 2023 |
| WEIPAI        | S15                         | Notebook    | [e6a15d7fa9](https://linux-hardware.org/?probe=e6a15d7fa9) | Mar 25, 2023 |
| HP            | Stream Notebook             | Notebook    | [b1ae4b8667](https://linux-hardware.org/?probe=b1ae4b8667) | Mar 25, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [ab9ed0121f](https://linux-hardware.org/?probe=ab9ed0121f) | Mar 25, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [38b08369e7](https://linux-hardware.org/?probe=38b08369e7) | Mar 25, 2023 |
| Dell          | Latitude E5510              | Notebook    | [8a9a1eec2c](https://linux-hardware.org/?probe=8a9a1eec2c) | Mar 24, 2023 |
| Framework     | Laptop                      | Notebook    | [4e1bd28ce3](https://linux-hardware.org/?probe=4e1bd28ce3) | Mar 24, 2023 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [ce9cdcc598](https://linux-hardware.org/?probe=ce9cdcc598) | Mar 24, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [628d2ea05c](https://linux-hardware.org/?probe=628d2ea05c) | Mar 24, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [e859e77bc7](https://linux-hardware.org/?probe=e859e77bc7) | Mar 24, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [efab305a00](https://linux-hardware.org/?probe=efab305a00) | Mar 24, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [ce7e17cb45](https://linux-hardware.org/?probe=ce7e17cb45) | Mar 24, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [05d4059f59](https://linux-hardware.org/?probe=05d4059f59) | Mar 24, 2023 |
| Acer          | FIH57                       | All in one  | [1f63978352](https://linux-hardware.org/?probe=1f63978352) | Mar 23, 2023 |
| Dell          | Inspiron 3721               | Notebook    | [e992b8f3a0](https://linux-hardware.org/?probe=e992b8f3a0) | Mar 23, 2023 |
| HP            | Pavilion 15                 | Notebook    | [32a0c3ec32](https://linux-hardware.org/?probe=32a0c3ec32) | Mar 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [78fab808a1](https://linux-hardware.org/?probe=78fab808a1) | Mar 23, 2023 |
| HP            | Pavilion dv6                | Notebook    | [625fff449a](https://linux-hardware.org/?probe=625fff449a) | Mar 23, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [c83000783a](https://linux-hardware.org/?probe=c83000783a) | Mar 23, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [e8ad290196](https://linux-hardware.org/?probe=e8ad290196) | Mar 23, 2023 |
| Intel         | G41                         | Desktop     | [c9fccfc8c1](https://linux-hardware.org/?probe=c9fccfc8c1) | Mar 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [d0b0015eb2](https://linux-hardware.org/?probe=d0b0015eb2) | Mar 22, 2023 |
| Orbsmart      | AW-11L                      | Mini pc     | [f66ed5bf1f](https://linux-hardware.org/?probe=f66ed5bf1f) | Mar 21, 2023 |
| Dell          | Latitude E7240              | Notebook    | [a3e408033c](https://linux-hardware.org/?probe=a3e408033c) | Mar 21, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [a6c90e3ad8](https://linux-hardware.org/?probe=a6c90e3ad8) | Mar 21, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [9409e4e133](https://linux-hardware.org/?probe=9409e4e133) | Mar 20, 2023 |
| Acer          | Revo RL80                   | Desktop     | [23ee51b834](https://linux-hardware.org/?probe=23ee51b834) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [93ae4afbbc](https://linux-hardware.org/?probe=93ae4afbbc) | Mar 20, 2023 |
| Dell          | Inspiron 5405               | Notebook    | [bb59d0b5e9](https://linux-hardware.org/?probe=bb59d0b5e9) | Mar 20, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [e7344d03c0](https://linux-hardware.org/?probe=e7344d03c0) | Mar 20, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [4b47e3ed6c](https://linux-hardware.org/?probe=4b47e3ed6c) | Mar 20, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [cddf0b016f](https://linux-hardware.org/?probe=cddf0b016f) | Mar 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [75996f8bcf](https://linux-hardware.org/?probe=75996f8bcf) | Mar 19, 2023 |
| HP            | 158A                        | Desktop     | [61467de4d5](https://linux-hardware.org/?probe=61467de4d5) | Mar 19, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [2b86166550](https://linux-hardware.org/?probe=2b86166550) | Mar 19, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [70f51cbfcb](https://linux-hardware.org/?probe=70f51cbfcb) | Mar 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f0f20a06ef](https://linux-hardware.org/?probe=f0f20a06ef) | Mar 19, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [1434607f7e](https://linux-hardware.org/?probe=1434607f7e) | Mar 19, 2023 |
| Microtech     | CoreBook                    | Notebook    | [d50c0297a6](https://linux-hardware.org/?probe=d50c0297a6) | Mar 19, 2023 |
| HP            | 2B01                        | Desktop     | [1a096f9b36](https://linux-hardware.org/?probe=1a096f9b36) | Mar 19, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | Notebook    | [5c59b55c2a](https://linux-hardware.org/?probe=5c59b55c2a) | Mar 19, 2023 |
| Lenovo        | ThinkPad T420 4180RK8       | Notebook    | [752373923e](https://linux-hardware.org/?probe=752373923e) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [ee8b155a83](https://linux-hardware.org/?probe=ee8b155a83) | Mar 18, 2023 |
| Quanta        | XV1                         | All in one  | [2bbbb73d41](https://linux-hardware.org/?probe=2bbbb73d41) | Mar 18, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [314245636a](https://linux-hardware.org/?probe=314245636a) | Mar 18, 2023 |
| Dell          | Inspiron 3721               | Notebook    | [c7b5ea67bb](https://linux-hardware.org/?probe=c7b5ea67bb) | Mar 18, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [211a71ed78](https://linux-hardware.org/?probe=211a71ed78) | Mar 18, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [5f4a932bcd](https://linux-hardware.org/?probe=5f4a932bcd) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [07dc0a0959](https://linux-hardware.org/?probe=07dc0a0959) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [f61ec5ce9f](https://linux-hardware.org/?probe=f61ec5ce9f) | Mar 18, 2023 |
| HP            | 83E1                        | Desktop     | [2a1ade4f84](https://linux-hardware.org/?probe=2a1ade4f84) | Mar 17, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [76b31023a4](https://linux-hardware.org/?probe=76b31023a4) | Mar 17, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [901e03fa6e](https://linux-hardware.org/?probe=901e03fa6e) | Mar 17, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [a012da47e9](https://linux-hardware.org/?probe=a012da47e9) | Mar 17, 2023 |
| HP            | Pavilion dm1                | Notebook    | [8707341105](https://linux-hardware.org/?probe=8707341105) | Mar 16, 2023 |
| Alienware     | 15 R3                       | Notebook    | [c1f4b90efb](https://linux-hardware.org/?probe=c1f4b90efb) | Mar 16, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [a029e62352](https://linux-hardware.org/?probe=a029e62352) | Mar 16, 2023 |
| HP            | 158A                        | Desktop     | [4a023a55d8](https://linux-hardware.org/?probe=4a023a55d8) | Mar 16, 2023 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [06dd580c2e](https://linux-hardware.org/?probe=06dd580c2e) | Mar 16, 2023 |
| Google        | Babymega                    | Notebook    | [beead110bb](https://linux-hardware.org/?probe=beead110bb) | Mar 16, 2023 |
| Google        | Babymega                    | Notebook    | [0a45acf149](https://linux-hardware.org/?probe=0a45acf149) | Mar 16, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [d9e1bb3da7](https://linux-hardware.org/?probe=d9e1bb3da7) | Mar 16, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [3388dd991a](https://linux-hardware.org/?probe=3388dd991a) | Mar 15, 2023 |
| AZW           | GTR V01                     | Mini pc     | [98d84656e8](https://linux-hardware.org/?probe=98d84656e8) | Mar 15, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [f5175006b7](https://linux-hardware.org/?probe=f5175006b7) | Mar 15, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [9565625dc4](https://linux-hardware.org/?probe=9565625dc4) | Mar 15, 2023 |
| Lenovo        | ThinkPad T430 23492D1       | Notebook    | [34e2b05336](https://linux-hardware.org/?probe=34e2b05336) | Mar 14, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [f6a3a68640](https://linux-hardware.org/?probe=f6a3a68640) | Mar 14, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [cbb20e87cb](https://linux-hardware.org/?probe=cbb20e87cb) | Mar 14, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [eb761f4a30](https://linux-hardware.org/?probe=eb761f4a30) | Mar 14, 2023 |
| ASUSTek       | U36SD                       | Notebook    | [74e2dfbbc6](https://linux-hardware.org/?probe=74e2dfbbc6) | Mar 14, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [cc372ccf7d](https://linux-hardware.org/?probe=cc372ccf7d) | Mar 14, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [4987f344f2](https://linux-hardware.org/?probe=4987f344f2) | Mar 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [0f440670f2](https://linux-hardware.org/?probe=0f440670f2) | Mar 14, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [55d6288663](https://linux-hardware.org/?probe=55d6288663) | Mar 14, 2023 |
| Google        | Celes                       | Notebook    | [4fd0271747](https://linux-hardware.org/?probe=4fd0271747) | Mar 13, 2023 |
| HP            | 83E1                        | Desktop     | [d286798430](https://linux-hardware.org/?probe=d286798430) | Mar 13, 2023 |
| Soncview      | G41D3C                      | Desktop     | [877ff67a70](https://linux-hardware.org/?probe=877ff67a70) | Mar 13, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [77569b52db](https://linux-hardware.org/?probe=77569b52db) | Mar 13, 2023 |
| Quanta        | XV1                         | All in one  | [930e98f517](https://linux-hardware.org/?probe=930e98f517) | Mar 13, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9d5d0051ea](https://linux-hardware.org/?probe=9d5d0051ea) | Mar 13, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [178af6e35b](https://linux-hardware.org/?probe=178af6e35b) | Mar 12, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d5eb709e13](https://linux-hardware.org/?probe=d5eb709e13) | Mar 12, 2023 |
| HP            | 18E7                        | Desktop     | [2042edf904](https://linux-hardware.org/?probe=2042edf904) | Mar 12, 2023 |
| Toshiba       | PORTEGE X30-D               | Notebook    | [9b7e4e10af](https://linux-hardware.org/?probe=9b7e4e10af) | Mar 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [d777dadd73](https://linux-hardware.org/?probe=d777dadd73) | Mar 12, 2023 |
| Novatech      | 15.6 nSpire Laptop          | Notebook    | [f5814aa2e6](https://linux-hardware.org/?probe=f5814aa2e6) | Mar 12, 2023 |
| Dell          | 0GM819                      | Desktop     | [1db4004d05](https://linux-hardware.org/?probe=1db4004d05) | Mar 12, 2023 |
| Medion        | MS-7707                     | Desktop     | [a0621e0cd1](https://linux-hardware.org/?probe=a0621e0cd1) | Mar 12, 2023 |
| Lenovo        | ThinkPad X270 20HMS1KL0C    | Notebook    | [f27bb76a32](https://linux-hardware.org/?probe=f27bb76a32) | Mar 12, 2023 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [f45a0d4c01](https://linux-hardware.org/?probe=f45a0d4c01) | Mar 12, 2023 |
| Medion        | MS-7707                     | Desktop     | [4c9432026b](https://linux-hardware.org/?probe=4c9432026b) | Mar 12, 2023 |
| Acer          | TravelMate B113             | Notebook    | [e5f001172d](https://linux-hardware.org/?probe=e5f001172d) | Mar 12, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [91da2169aa](https://linux-hardware.org/?probe=91da2169aa) | Mar 12, 2023 |
| Gigabyte      | X670E AORUS XTREME          | Desktop     | [83cb566647](https://linux-hardware.org/?probe=83cb566647) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [fd63e92774](https://linux-hardware.org/?probe=fd63e92774) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [6a0426cb65](https://linux-hardware.org/?probe=6a0426cb65) | Mar 12, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [bd0c265909](https://linux-hardware.org/?probe=bd0c265909) | Mar 11, 2023 |
| Acer          | TravelMate B113             | Notebook    | [ba6dc5dcb5](https://linux-hardware.org/?probe=ba6dc5dcb5) | Mar 11, 2023 |
| HP            | Pavilion dv6                | Notebook    | [fca49aa86c](https://linux-hardware.org/?probe=fca49aa86c) | Mar 11, 2023 |
| Acer          | WG43M                       | Desktop     | [5858448536](https://linux-hardware.org/?probe=5858448536) | Mar 11, 2023 |
| Acer          | WG43M                       | Desktop     | [3d562885d0](https://linux-hardware.org/?probe=3d562885d0) | Mar 11, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [daad1ee8d5](https://linux-hardware.org/?probe=daad1ee8d5) | Mar 11, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [4b9462a4ff](https://linux-hardware.org/?probe=4b9462a4ff) | Mar 11, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [a47baaadde](https://linux-hardware.org/?probe=a47baaadde) | Mar 11, 2023 |
| HP            | 2B3B                        | All in one  | [cb25c51987](https://linux-hardware.org/?probe=cb25c51987) | Mar 11, 2023 |
| ASUSTek       | T100TAM                     | Notebook    | [1d647e564b](https://linux-hardware.org/?probe=1d647e564b) | Mar 10, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [434a8e0e37](https://linux-hardware.org/?probe=434a8e0e37) | Mar 10, 2023 |
| Medion        | Akoya E1318T                | Notebook    | [8b24b109ec](https://linux-hardware.org/?probe=8b24b109ec) | Mar 10, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [6648af3696](https://linux-hardware.org/?probe=6648af3696) | Mar 10, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [807d1626b4](https://linux-hardware.org/?probe=807d1626b4) | Mar 10, 2023 |
| Toshiba       | Satellite L855              | Notebook    | [3b0a7cfbf0](https://linux-hardware.org/?probe=3b0a7cfbf0) | Mar 10, 2023 |
| Toshiba       | Satellite L855              | Notebook    | [08bfa4188e](https://linux-hardware.org/?probe=08bfa4188e) | Mar 10, 2023 |
| HP            | ProBook 4530s               | Notebook    | [e9c9dd943e](https://linux-hardware.org/?probe=e9c9dd943e) | Mar 10, 2023 |
| Dell          | Precision M6700             | Notebook    | [7a02d78344](https://linux-hardware.org/?probe=7a02d78344) | Mar 10, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [565c8963d4](https://linux-hardware.org/?probe=565c8963d4) | Mar 10, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [99d5f17b22](https://linux-hardware.org/?probe=99d5f17b22) | Mar 09, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [65b41dc560](https://linux-hardware.org/?probe=65b41dc560) | Mar 09, 2023 |
| HP            | Pavilion TS 15              | Notebook    | [5c0b7a773e](https://linux-hardware.org/?probe=5c0b7a773e) | Mar 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [bd1ab8d62d](https://linux-hardware.org/?probe=bd1ab8d62d) | Mar 09, 2023 |
| Dell          | Latitude 3180               | Notebook    | [07a18f8eb1](https://linux-hardware.org/?probe=07a18f8eb1) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [9acfcb9b4f](https://linux-hardware.org/?probe=9acfcb9b4f) | Mar 09, 2023 |
| HP            | 81C7 MVB 0C                 | Server      | [2ad477ea6c](https://linux-hardware.org/?probe=2ad477ea6c) | Mar 09, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [1599d2a2ef](https://linux-hardware.org/?probe=1599d2a2ef) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [21f11cf791](https://linux-hardware.org/?probe=21f11cf791) | Mar 09, 2023 |
| Unknown       | HX90                        | Desktop     | [21530c00a4](https://linux-hardware.org/?probe=21530c00a4) | Mar 09, 2023 |
| Multilaser    | PC130                       | Notebook    | [37212994df](https://linux-hardware.org/?probe=37212994df) | Mar 09, 2023 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [8115c702cb](https://linux-hardware.org/?probe=8115c702cb) | Mar 09, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [5fd5c7db62](https://linux-hardware.org/?probe=5fd5c7db62) | Mar 09, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [0dc84b30aa](https://linux-hardware.org/?probe=0dc84b30aa) | Mar 09, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0T500     | Notebook    | [e6fd8c46b0](https://linux-hardware.org/?probe=e6fd8c46b0) | Mar 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [d01b6ad50c](https://linux-hardware.org/?probe=d01b6ad50c) | Mar 08, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [fd255666fc](https://linux-hardware.org/?probe=fd255666fc) | Mar 08, 2023 |
| Dell          | Latitude E4310              | Notebook    | [8dbe3e01fa](https://linux-hardware.org/?probe=8dbe3e01fa) | Mar 08, 2023 |
| Gigabyte      | B450 GAMING X               | Desktop     | [6f7b473b62](https://linux-hardware.org/?probe=6f7b473b62) | Mar 08, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a598fd0bed](https://linux-hardware.org/?probe=a598fd0bed) | Mar 08, 2023 |
| Lenovo        | YB1-X91F                    | Tablet      | [5582ce4ba9](https://linux-hardware.org/?probe=5582ce4ba9) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | Desktop     | [5f93500136](https://linux-hardware.org/?probe=5f93500136) | Mar 08, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [a7c688e9be](https://linux-hardware.org/?probe=a7c688e9be) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | Desktop     | [fdba382132](https://linux-hardware.org/?probe=fdba382132) | Mar 08, 2023 |
| Dell          | Latitude 5310 2-in-1        | Convertible | [cccaedd7d3](https://linux-hardware.org/?probe=cccaedd7d3) | Mar 07, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [00ddbf4ad1](https://linux-hardware.org/?probe=00ddbf4ad1) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [10c9c37ebc](https://linux-hardware.org/?probe=10c9c37ebc) | Mar 07, 2023 |
| ASUSTek       | P5GC-MX                     | Desktop     | [c7ccf3de7b](https://linux-hardware.org/?probe=c7ccf3de7b) | Mar 07, 2023 |
| Google        | Candy                       | Notebook    | [e74102ff2c](https://linux-hardware.org/?probe=e74102ff2c) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [aa987a6626](https://linux-hardware.org/?probe=aa987a6626) | Mar 07, 2023 |
| Lenovo        | ThinkPad X240 20AMA3PVAR    | Notebook    | [367f53195a](https://linux-hardware.org/?probe=367f53195a) | Mar 07, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [0a85b4da67](https://linux-hardware.org/?probe=0a85b4da67) | Mar 07, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | Notebook    | [3f1ebc8271](https://linux-hardware.org/?probe=3f1ebc8271) | Mar 07, 2023 |
| Google        | Lillipup                    | Notebook    | [33350c987b](https://linux-hardware.org/?probe=33350c987b) | Mar 07, 2023 |
| Chuwi         | HeroBox                     | Mini pc     | [6e8a20eb98](https://linux-hardware.org/?probe=6e8a20eb98) | Mar 07, 2023 |
| Packard Be... | EasyNote TM82               | Notebook    | [33de288525](https://linux-hardware.org/?probe=33de288525) | Mar 07, 2023 |
| Gigabyte      | H61M-S2P-B3                 | Desktop     | [83c569f727](https://linux-hardware.org/?probe=83c569f727) | Mar 06, 2023 |
| Gigabyte      | H61M-S2P-B3                 | Desktop     | [ca3531a813](https://linux-hardware.org/?probe=ca3531a813) | Mar 06, 2023 |
| HP            | 81C7 MVB 0C                 | Server      | [e717a99f1f](https://linux-hardware.org/?probe=e717a99f1f) | Mar 06, 2023 |
| YJKC          | vBOOK Plus RVP7             | Notebook    | [acdf0dca1d](https://linux-hardware.org/?probe=acdf0dca1d) | Mar 06, 2023 |
| Google        | Lillipup                    | Notebook    | [214481f959](https://linux-hardware.org/?probe=214481f959) | Mar 06, 2023 |
| Dell          | 0JC474                      | Desktop     | [90db9efd8d](https://linux-hardware.org/?probe=90db9efd8d) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [7c9b56f288](https://linux-hardware.org/?probe=7c9b56f288) | Mar 05, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [df192a1871](https://linux-hardware.org/?probe=df192a1871) | Mar 05, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [12c8945329](https://linux-hardware.org/?probe=12c8945329) | Mar 05, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [d1a55c59a3](https://linux-hardware.org/?probe=d1a55c59a3) | Mar 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [657175938b](https://linux-hardware.org/?probe=657175938b) | Mar 05, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [47eeabee04](https://linux-hardware.org/?probe=47eeabee04) | Mar 05, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [f3c06b377f](https://linux-hardware.org/?probe=f3c06b377f) | Mar 04, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [05507dab01](https://linux-hardware.org/?probe=05507dab01) | Mar 04, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [240adbe154](https://linux-hardware.org/?probe=240adbe154) | Mar 04, 2023 |
| Timi          | TM1701                      | Notebook    | [4faac58613](https://linux-hardware.org/?probe=4faac58613) | Mar 04, 2023 |
| Lenovo        | ThinkPad X201 3680Z38       | Notebook    | [414dc8dc29](https://linux-hardware.org/?probe=414dc8dc29) | Mar 04, 2023 |
| Lenovo        | ThinkPad X201 3680Z38       | Notebook    | [3e60e33df2](https://linux-hardware.org/?probe=3e60e33df2) | Mar 04, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [c16eae7537](https://linux-hardware.org/?probe=c16eae7537) | Mar 04, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [829848b662](https://linux-hardware.org/?probe=829848b662) | Mar 04, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [767045c44e](https://linux-hardware.org/?probe=767045c44e) | Mar 03, 2023 |
| Unknown       | Rev.00                      | Desktop     | [89ff2d84f4](https://linux-hardware.org/?probe=89ff2d84f4) | Mar 03, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [80e66c5eac](https://linux-hardware.org/?probe=80e66c5eac) | Mar 03, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [1237954f03](https://linux-hardware.org/?probe=1237954f03) | Mar 03, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | Mini pc     | [03db87f6d8](https://linux-hardware.org/?probe=03db87f6d8) | Mar 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [1e039a31d1](https://linux-hardware.org/?probe=1e039a31d1) | Mar 03, 2023 |
| ASUSTek       | UX331UA                     | Notebook    | [310d69ff6f](https://linux-hardware.org/?probe=310d69ff6f) | Mar 03, 2023 |
| AZW           | GTR V01                     | Mini pc     | [fb4847e7ac](https://linux-hardware.org/?probe=fb4847e7ac) | Mar 03, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [81889ddc9c](https://linux-hardware.org/?probe=81889ddc9c) | Mar 02, 2023 |
| Lenovo        | ThinkPad X230 2333BR3       | Notebook    | [a3b6a280c1](https://linux-hardware.org/?probe=a3b6a280c1) | Mar 02, 2023 |
| HP            | Notebook                    | Notebook    | [453811c44a](https://linux-hardware.org/?probe=453811c44a) | Mar 02, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [188ba8d836](https://linux-hardware.org/?probe=188ba8d836) | Mar 02, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [0ad3a8182e](https://linux-hardware.org/?probe=0ad3a8182e) | Mar 02, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [5729d41d01](https://linux-hardware.org/?probe=5729d41d01) | Mar 02, 2023 |
| Toshiba       | Satellite A100              | Notebook    | [51e1183b15](https://linux-hardware.org/?probe=51e1183b15) | Mar 02, 2023 |
| ASUSTek       | UX331UA                     | Notebook    | [52c7446693](https://linux-hardware.org/?probe=52c7446693) | Mar 02, 2023 |
| Lenovo        | ThinkPad X230 2333BR3       | Notebook    | [7b17e49d0f](https://linux-hardware.org/?probe=7b17e49d0f) | Mar 02, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [95b0a4d944](https://linux-hardware.org/?probe=95b0a4d944) | Mar 02, 2023 |
| HP            | 805D                        | Desktop     | [4638c85566](https://linux-hardware.org/?probe=4638c85566) | Mar 01, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [e9b7ee04ec](https://linux-hardware.org/?probe=e9b7ee04ec) | Mar 01, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [fa7df5da3b](https://linux-hardware.org/?probe=fa7df5da3b) | Mar 01, 2023 |
| Toshiba       | Satellite S55t-B            | Notebook    | [69734289ba](https://linux-hardware.org/?probe=69734289ba) | Mar 01, 2023 |
| MSI           | Raider GE66 12UHS           | Notebook    | [3fcfdd9fba](https://linux-hardware.org/?probe=3fcfdd9fba) | Mar 01, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [a8b1a02128](https://linux-hardware.org/?probe=a8b1a02128) | Mar 01, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [c698fc199a](https://linux-hardware.org/?probe=c698fc199a) | Feb 28, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [b4be9a72dd](https://linux-hardware.org/?probe=b4be9a72dd) | Feb 28, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [66e63a311d](https://linux-hardware.org/?probe=66e63a311d) | Feb 28, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [4f835a4f35](https://linux-hardware.org/?probe=4f835a4f35) | Feb 28, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [7478549a38](https://linux-hardware.org/?probe=7478549a38) | Feb 28, 2023 |
| Dell          | Latitude E6440              | Notebook    | [80131cd2a4](https://linux-hardware.org/?probe=80131cd2a4) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [ca7d449be6](https://linux-hardware.org/?probe=ca7d449be6) | Feb 28, 2023 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | Desktop     | [75e0fb99ed](https://linux-hardware.org/?probe=75e0fb99ed) | Feb 28, 2023 |
| Google        | Buddy                       | Desktop     | [ac3d9aaed0](https://linux-hardware.org/?probe=ac3d9aaed0) | Feb 27, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [d7b51f6048](https://linux-hardware.org/?probe=d7b51f6048) | Feb 27, 2023 |
| AZW           | SER                         | Mini pc     | [e086890e6a](https://linux-hardware.org/?probe=e086890e6a) | Feb 27, 2023 |
| HP            | Pavilion dv7                | Notebook    | [d5da5f62b8](https://linux-hardware.org/?probe=d5da5f62b8) | Feb 27, 2023 |
| Acer          | TravelMate B113             | Notebook    | [31691f9681](https://linux-hardware.org/?probe=31691f9681) | Feb 27, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [42acb38635](https://linux-hardware.org/?probe=42acb38635) | Feb 27, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [e8c76a33fe](https://linux-hardware.org/?probe=e8c76a33fe) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [7f907fadb7](https://linux-hardware.org/?probe=7f907fadb7) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [766991da5e](https://linux-hardware.org/?probe=766991da5e) | Feb 27, 2023 |
| Dell          | Vostro 1540                 | Notebook    | [8f09ea4351](https://linux-hardware.org/?probe=8f09ea4351) | Feb 27, 2023 |
| HP            | ENVY m7 Notebook            | Notebook    | [14374fbcc8](https://linux-hardware.org/?probe=14374fbcc8) | Feb 27, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [6c62bbbf3b](https://linux-hardware.org/?probe=6c62bbbf3b) | Feb 27, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [2479c3c245](https://linux-hardware.org/?probe=2479c3c245) | Feb 27, 2023 |
| HP            | 1998                        | Desktop     | [90794415e9](https://linux-hardware.org/?probe=90794415e9) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [a21ea9613b](https://linux-hardware.org/?probe=a21ea9613b) | Feb 26, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [deb326cc4b](https://linux-hardware.org/?probe=deb326cc4b) | Feb 26, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [cc220b6122](https://linux-hardware.org/?probe=cc220b6122) | Feb 26, 2023 |
| HP            | 620                         | Notebook    | [e3bf80caf7](https://linux-hardware.org/?probe=e3bf80caf7) | Feb 25, 2023 |
| Quanta        | XV1                         | All in one  | [fa596130ae](https://linux-hardware.org/?probe=fa596130ae) | Feb 25, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [57a009cdd4](https://linux-hardware.org/?probe=57a009cdd4) | Feb 25, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [fc1a3d88ae](https://linux-hardware.org/?probe=fc1a3d88ae) | Feb 25, 2023 |
| MSI           | H81M-P33                    | Desktop     | [1bc1cedec6](https://linux-hardware.org/?probe=1bc1cedec6) | Feb 25, 2023 |
| Dell          | Latitude E6440              | Notebook    | [a4139e4774](https://linux-hardware.org/?probe=a4139e4774) | Feb 25, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [eca93ca661](https://linux-hardware.org/?probe=eca93ca661) | Feb 25, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [7357439273](https://linux-hardware.org/?probe=7357439273) | Feb 25, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [7f88a11698](https://linux-hardware.org/?probe=7f88a11698) | Feb 25, 2023 |
| HP            | 2AF7                        | Desktop     | [a8eba0b0c4](https://linux-hardware.org/?probe=a8eba0b0c4) | Feb 25, 2023 |
| HP            | 2AF7                        | Desktop     | [3bf3afd1d5](https://linux-hardware.org/?probe=3bf3afd1d5) | Feb 25, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [85ea6dded1](https://linux-hardware.org/?probe=85ea6dded1) | Feb 24, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [1fb9cfd7d4](https://linux-hardware.org/?probe=1fb9cfd7d4) | Feb 24, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [bafb67390c](https://linux-hardware.org/?probe=bafb67390c) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [602cac9f15](https://linux-hardware.org/?probe=602cac9f15) | Feb 24, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [3b27d3609f](https://linux-hardware.org/?probe=3b27d3609f) | Feb 24, 2023 |
| HP            | ProBook 4545s               | Notebook    | [0f56422e2d](https://linux-hardware.org/?probe=0f56422e2d) | Feb 24, 2023 |
| HP            | 2129                        | Desktop     | [5118eb06d4](https://linux-hardware.org/?probe=5118eb06d4) | Feb 24, 2023 |
| ASUSTek       | T100TAF                     | Notebook    | [4fce660f2d](https://linux-hardware.org/?probe=4fce660f2d) | Feb 23, 2023 |
| Dell          | Latitude 7480               | Notebook    | [fd80b301db](https://linux-hardware.org/?probe=fd80b301db) | Feb 23, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [f283ae7cb2](https://linux-hardware.org/?probe=f283ae7cb2) | Feb 23, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [294c5c45e6](https://linux-hardware.org/?probe=294c5c45e6) | Feb 23, 2023 |
| DERE          | V14                         | Notebook    | [bb2d40e676](https://linux-hardware.org/?probe=bb2d40e676) | Feb 22, 2023 |
| HP            | 2129                        | Desktop     | [5a6b1e7169](https://linux-hardware.org/?probe=5a6b1e7169) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [e861797e74](https://linux-hardware.org/?probe=e861797e74) | Feb 21, 2023 |
| ASUSTek       | F2A55-M                     | Desktop     | [c9d150f24c](https://linux-hardware.org/?probe=c9d150f24c) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [40e2157901](https://linux-hardware.org/?probe=40e2157901) | Feb 21, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [9a9c8192de](https://linux-hardware.org/?probe=9a9c8192de) | Feb 21, 2023 |
| Teclast       | F7                          | Notebook    | [3f5fdc3aa9](https://linux-hardware.org/?probe=3f5fdc3aa9) | Feb 21, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [5d32bc7f7c](https://linux-hardware.org/?probe=5d32bc7f7c) | Feb 21, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a00e724475](https://linux-hardware.org/?probe=a00e724475) | Feb 21, 2023 |
| HP            | 1850                        | Desktop     | [f184ff6250](https://linux-hardware.org/?probe=f184ff6250) | Feb 21, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | Desktop     | [e062475561](https://linux-hardware.org/?probe=e062475561) | Feb 20, 2023 |
| Dell          | System XPS L502X            | Notebook    | [7352f47bb0](https://linux-hardware.org/?probe=7352f47bb0) | Feb 20, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [5002433b97](https://linux-hardware.org/?probe=5002433b97) | Feb 20, 2023 |
| HP            | 620                         | Notebook    | [c3dae62545](https://linux-hardware.org/?probe=c3dae62545) | Feb 20, 2023 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [882e2c977d](https://linux-hardware.org/?probe=882e2c977d) | Feb 20, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [115fa87a77](https://linux-hardware.org/?probe=115fa87a77) | Feb 20, 2023 |
| Dell          | Latitude E5440              | Notebook    | [10b94a411c](https://linux-hardware.org/?probe=10b94a411c) | Feb 20, 2023 |
| HP            | Laptop 15s-dr0xxx           | Notebook    | [6733a448f9](https://linux-hardware.org/?probe=6733a448f9) | Feb 20, 2023 |
| eMachines     | MCP61PM-GM                  | Desktop     | [aeafa2dbee](https://linux-hardware.org/?probe=aeafa2dbee) | Feb 19, 2023 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [d20a6e81f8](https://linux-hardware.org/?probe=d20a6e81f8) | Feb 19, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [3c53a60245](https://linux-hardware.org/?probe=3c53a60245) | Feb 19, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | Desktop     | [5d6240bcc6](https://linux-hardware.org/?probe=5d6240bcc6) | Feb 19, 2023 |
| ASUSTek       | Zenbook UX562UG_Q508UG      | Convertible | [2bb870a042](https://linux-hardware.org/?probe=2bb870a042) | Feb 19, 2023 |
| Lenovo        | ThinkPad T460 20FN003LMZ    | Notebook    | [1752223e74](https://linux-hardware.org/?probe=1752223e74) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | Desktop     | [09aad96389](https://linux-hardware.org/?probe=09aad96389) | Feb 19, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [be0f73193d](https://linux-hardware.org/?probe=be0f73193d) | Feb 19, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [752cdf5b2b](https://linux-hardware.org/?probe=752cdf5b2b) | Feb 19, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [c784a261d4](https://linux-hardware.org/?probe=c784a261d4) | Feb 19, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [d6f4d9d8df](https://linux-hardware.org/?probe=d6f4d9d8df) | Feb 19, 2023 |
| Multilaser    | PC130                       | Notebook    | [3526846c1f](https://linux-hardware.org/?probe=3526846c1f) | Feb 19, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [16350a9c3b](https://linux-hardware.org/?probe=16350a9c3b) | Feb 19, 2023 |
| Lenovo        | ThinkPad T570 20H90002MZ    | Notebook    | [6694311da2](https://linux-hardware.org/?probe=6694311da2) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | Desktop     | [af7ffdc7a9](https://linux-hardware.org/?probe=af7ffdc7a9) | Feb 18, 2023 |
| Lenovo        | ThinkPad T550 20CK003LMZ    | Notebook    | [e3b00dc0f6](https://linux-hardware.org/?probe=e3b00dc0f6) | Feb 18, 2023 |
| HP            | Unknown                     | Notebook    | [3fea6a053b](https://linux-hardware.org/?probe=3fea6a053b) | Feb 18, 2023 |
| Lenovo        | ThinkPad T560 20FJS24T00    | Notebook    | [91a1aa0a0d](https://linux-hardware.org/?probe=91a1aa0a0d) | Feb 18, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | Notebook    | [bba1f53762](https://linux-hardware.org/?probe=bba1f53762) | Feb 18, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [b2a9f21210](https://linux-hardware.org/?probe=b2a9f21210) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [6cc82a744e](https://linux-hardware.org/?probe=6cc82a744e) | Feb 18, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [215ae5796f](https://linux-hardware.org/?probe=215ae5796f) | Feb 18, 2023 |
| Dell          | Inspiron 14 Plus 7420       | Notebook    | [59387e9081](https://linux-hardware.org/?probe=59387e9081) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [96c9f07207](https://linux-hardware.org/?probe=96c9f07207) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [2734c1a2ae](https://linux-hardware.org/?probe=2734c1a2ae) | Feb 18, 2023 |
| Medion        | E7220                       | Notebook    | [289b7dc6aa](https://linux-hardware.org/?probe=289b7dc6aa) | Feb 17, 2023 |
| MSI           | H270 PC MATE                | Desktop     | [6581748d54](https://linux-hardware.org/?probe=6581748d54) | Feb 17, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [48bbbc04c4](https://linux-hardware.org/?probe=48bbbc04c4) | Feb 17, 2023 |
| ASUSTek       | X450LD                      | Notebook    | [b4fb1ddc5a](https://linux-hardware.org/?probe=b4fb1ddc5a) | Feb 17, 2023 |
| Google        | Robo                        | Notebook    | [303c72db93](https://linux-hardware.org/?probe=303c72db93) | Feb 17, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [529e0929d2](https://linux-hardware.org/?probe=529e0929d2) | Feb 17, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [88d9514231](https://linux-hardware.org/?probe=88d9514231) | Feb 17, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [b997f44969](https://linux-hardware.org/?probe=b997f44969) | Feb 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [97e017594b](https://linux-hardware.org/?probe=97e017594b) | Feb 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [8043264215](https://linux-hardware.org/?probe=8043264215) | Feb 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [51b7c93a69](https://linux-hardware.org/?probe=51b7c93a69) | Feb 16, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [4275665066](https://linux-hardware.org/?probe=4275665066) | Feb 16, 2023 |
| Quanta        | XV1                         | All in one  | [6c4ea36dc2](https://linux-hardware.org/?probe=6c4ea36dc2) | Feb 16, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [c08ad0f295](https://linux-hardware.org/?probe=c08ad0f295) | Feb 16, 2023 |
| HP            | ENVY TS Sleekbook 4         | Notebook    | [1189701feb](https://linux-hardware.org/?probe=1189701feb) | Feb 15, 2023 |
| Acer          | Extensa 5230                | Notebook    | [2716bcf519](https://linux-hardware.org/?probe=2716bcf519) | Feb 15, 2023 |
| Dell          | Latitude 3320               | Notebook    | [fecee449d4](https://linux-hardware.org/?probe=fecee449d4) | Feb 15, 2023 |
| MSI           | Z370M MORTAR                | Desktop     | [5ac9c9a924](https://linux-hardware.org/?probe=5ac9c9a924) | Feb 15, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | Notebook    | [6c1c0027b1](https://linux-hardware.org/?probe=6c1c0027b1) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c2d957f650](https://linux-hardware.org/?probe=c2d957f650) | Feb 15, 2023 |
| Dell          | System XPS L502X            | Notebook    | [2ea016be2a](https://linux-hardware.org/?probe=2ea016be2a) | Feb 14, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [b9301138cc](https://linux-hardware.org/?probe=b9301138cc) | Feb 14, 2023 |
| Apple         | MacBook2,1                  | Notebook    | [915e87767b](https://linux-hardware.org/?probe=915e87767b) | Feb 14, 2023 |
| Dell          | Latitude 5480               | Notebook    | [03123ee601](https://linux-hardware.org/?probe=03123ee601) | Feb 14, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [995da369f0](https://linux-hardware.org/?probe=995da369f0) | Feb 14, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Desktop     | [b6b09f6455](https://linux-hardware.org/?probe=b6b09f6455) | Feb 14, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [92fc220243](https://linux-hardware.org/?probe=92fc220243) | Feb 14, 2023 |
| Google        | Teemo                       | Desktop     | [53bf6d19ca](https://linux-hardware.org/?probe=53bf6d19ca) | Feb 14, 2023 |
| Samsung       | 700T1C                      | Notebook    | [66c15f037d](https://linux-hardware.org/?probe=66c15f037d) | Feb 14, 2023 |
| Samsung       | 700T1C                      | Notebook    | [9e154ea3a4](https://linux-hardware.org/?probe=9e154ea3a4) | Feb 14, 2023 |
| MSI           | MS-B9181                    | Desktop     | [a155bc9fc3](https://linux-hardware.org/?probe=a155bc9fc3) | Feb 13, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [1e3c885566](https://linux-hardware.org/?probe=1e3c885566) | Feb 13, 2023 |
| Dell          | 0Y7WYT A00                  | Desktop     | [e289b5bb8d](https://linux-hardware.org/?probe=e289b5bb8d) | Feb 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [5efd07985b](https://linux-hardware.org/?probe=5efd07985b) | Feb 13, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [d1edc30dac](https://linux-hardware.org/?probe=d1edc30dac) | Feb 13, 2023 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [de30205f54](https://linux-hardware.org/?probe=de30205f54) | Feb 12, 2023 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [19700ab1bd](https://linux-hardware.org/?probe=19700ab1bd) | Feb 12, 2023 |
| Alienware     | 0N43JM A00                  | Desktop     | [ef1d9239ab](https://linux-hardware.org/?probe=ef1d9239ab) | Feb 12, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [59eeaafe59](https://linux-hardware.org/?probe=59eeaafe59) | Feb 12, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [45f78c29cb](https://linux-hardware.org/?probe=45f78c29cb) | Feb 12, 2023 |
| HP            | Compaq 6730b (NB034ET#UU... | Notebook    | [baa5f72e80](https://linux-hardware.org/?probe=baa5f72e80) | Feb 12, 2023 |
| HP            | Notebook                    | Notebook    | [a17adfd867](https://linux-hardware.org/?probe=a17adfd867) | Feb 12, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [498c449a46](https://linux-hardware.org/?probe=498c449a46) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [6f7c0f381e](https://linux-hardware.org/?probe=6f7c0f381e) | Feb 12, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [131d5052d1](https://linux-hardware.org/?probe=131d5052d1) | Feb 11, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [d4951f7e68](https://linux-hardware.org/?probe=d4951f7e68) | Feb 11, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [43e0c40499](https://linux-hardware.org/?probe=43e0c40499) | Feb 11, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [698006ab18](https://linux-hardware.org/?probe=698006ab18) | Feb 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [ce78e6cdb9](https://linux-hardware.org/?probe=ce78e6cdb9) | Feb 11, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [a789235fe3](https://linux-hardware.org/?probe=a789235fe3) | Feb 11, 2023 |
| HP            | 8054                        | Desktop     | [55c5642509](https://linux-hardware.org/?probe=55c5642509) | Feb 11, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [f3919f8d69](https://linux-hardware.org/?probe=f3919f8d69) | Feb 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [f5e5e27e8e](https://linux-hardware.org/?probe=f5e5e27e8e) | Feb 11, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | Notebook    | [518f413d2f](https://linux-hardware.org/?probe=518f413d2f) | Feb 11, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | Notebook    | [a24d7423c4](https://linux-hardware.org/?probe=a24d7423c4) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [7a6b34f58c](https://linux-hardware.org/?probe=7a6b34f58c) | Feb 11, 2023 |
| Dell          | Latitude E6400              | Notebook    | [8c489c529a](https://linux-hardware.org/?probe=8c489c529a) | Feb 11, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [5e8a88b237](https://linux-hardware.org/?probe=5e8a88b237) | Feb 11, 2023 |
| ASUSTek       | P5K                         | Desktop     | [9f8790812d](https://linux-hardware.org/?probe=9f8790812d) | Feb 11, 2023 |
| Acer          | TravelMate P253             | Notebook    | [8947050124](https://linux-hardware.org/?probe=8947050124) | Feb 11, 2023 |
| HONOR         | HLYL-WXX9                   | Notebook    | [9d916e8e03](https://linux-hardware.org/?probe=9d916e8e03) | Feb 10, 2023 |
| Acer          | Aspire 5720                 | Notebook    | [9b71ff828e](https://linux-hardware.org/?probe=9b71ff828e) | Feb 10, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [49b463f14c](https://linux-hardware.org/?probe=49b463f14c) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [6d9d60d4b8](https://linux-hardware.org/?probe=6d9d60d4b8) | Feb 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [cb0a834e1a](https://linux-hardware.org/?probe=cb0a834e1a) | Feb 10, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [477eb8ad3c](https://linux-hardware.org/?probe=477eb8ad3c) | Feb 10, 2023 |
| MSI           | GF615M-P31                  | Desktop     | [36dcd2e516](https://linux-hardware.org/?probe=36dcd2e516) | Feb 10, 2023 |
| Acer          | Predator G3-571             | Notebook    | [50fe192ea1](https://linux-hardware.org/?probe=50fe192ea1) | Feb 10, 2023 |
| Lenovo        | Yoga 500-14ACL 80NA         | Notebook    | [3bdbc623a8](https://linux-hardware.org/?probe=3bdbc623a8) | Feb 10, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [dba0167a53](https://linux-hardware.org/?probe=dba0167a53) | Feb 09, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [ad403b2126](https://linux-hardware.org/?probe=ad403b2126) | Feb 09, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [8513e7eb92](https://linux-hardware.org/?probe=8513e7eb92) | Feb 09, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [458744c54d](https://linux-hardware.org/?probe=458744c54d) | Feb 09, 2023 |
| Positivo      | Smash2                      | Notebook    | [1948e9489d](https://linux-hardware.org/?probe=1948e9489d) | Feb 09, 2023 |
| Positivo      | Smash2                      | Notebook    | [47760ee46f](https://linux-hardware.org/?probe=47760ee46f) | Feb 09, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [628151aedd](https://linux-hardware.org/?probe=628151aedd) | Feb 09, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [dd9b71e8d2](https://linux-hardware.org/?probe=dd9b71e8d2) | Feb 09, 2023 |
| Gigabyte      | B660 DS3H AX DDR4           | Desktop     | [73ae27760d](https://linux-hardware.org/?probe=73ae27760d) | Feb 09, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | Notebook    | [5c9ca6cd47](https://linux-hardware.org/?probe=5c9ca6cd47) | Feb 09, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [dd76c764a1](https://linux-hardware.org/?probe=dd76c764a1) | Feb 08, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [37aec8a881](https://linux-hardware.org/?probe=37aec8a881) | Feb 08, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [e7ee51ecdd](https://linux-hardware.org/?probe=e7ee51ecdd) | Feb 08, 2023 |
| HP            | Pavilion dv7                | Notebook    | [6b7ba3365e](https://linux-hardware.org/?probe=6b7ba3365e) | Feb 08, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [0d0c6fe86c](https://linux-hardware.org/?probe=0d0c6fe86c) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [26f7ad82d9](https://linux-hardware.org/?probe=26f7ad82d9) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [d54546bce9](https://linux-hardware.org/?probe=d54546bce9) | Feb 08, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [1fdf18a3ed](https://linux-hardware.org/?probe=1fdf18a3ed) | Feb 08, 2023 |
| AZW           | GTR V01                     | Mini pc     | [69bc815c6d](https://linux-hardware.org/?probe=69bc815c6d) | Feb 08, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [f963048c4c](https://linux-hardware.org/?probe=f963048c4c) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [e32b918f95](https://linux-hardware.org/?probe=e32b918f95) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [c0aab06a5c](https://linux-hardware.org/?probe=c0aab06a5c) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [830072137a](https://linux-hardware.org/?probe=830072137a) | Feb 07, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | Notebook    | [ae78404854](https://linux-hardware.org/?probe=ae78404854) | Feb 07, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | Notebook    | [b2c3e0fa85](https://linux-hardware.org/?probe=b2c3e0fa85) | Feb 07, 2023 |
| Multilaser    | UB23X LINUX                 | Notebook    | [d630a4eeff](https://linux-hardware.org/?probe=d630a4eeff) | Feb 07, 2023 |
| Foxconn       | NT-A2400&NT-A3500 FAB       | Desktop     | [000ed6c589](https://linux-hardware.org/?probe=000ed6c589) | Feb 07, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [1830edf54c](https://linux-hardware.org/?probe=1830edf54c) | Feb 07, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [e3ffc73e43](https://linux-hardware.org/?probe=e3ffc73e43) | Feb 06, 2023 |
| Acer          | Okinawa                     | Notebook    | [eab799e6dc](https://linux-hardware.org/?probe=eab799e6dc) | Feb 06, 2023 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [d7795277f3](https://linux-hardware.org/?probe=d7795277f3) | Feb 06, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [0e47e3afd8](https://linux-hardware.org/?probe=0e47e3afd8) | Feb 06, 2023 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | Desktop     | [96f24866e0](https://linux-hardware.org/?probe=96f24866e0) | Feb 06, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [a57b142e05](https://linux-hardware.org/?probe=a57b142e05) | Feb 06, 2023 |
| Intel         | Unknown                     | Notebook    | [a1044e362f](https://linux-hardware.org/?probe=a1044e362f) | Feb 06, 2023 |
| Sony          | VPCEG36FX                   | Notebook    | [d760d9e79b](https://linux-hardware.org/?probe=d760d9e79b) | Feb 06, 2023 |
| Acer          | TravelMate P253             | Notebook    | [050d7b5d68](https://linux-hardware.org/?probe=050d7b5d68) | Feb 06, 2023 |
| Lenovo        | ThinkPad T420 4236KU9       | Notebook    | [f536be92d0](https://linux-hardware.org/?probe=f536be92d0) | Feb 06, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [00714979fe](https://linux-hardware.org/?probe=00714979fe) | Feb 06, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [3bba794976](https://linux-hardware.org/?probe=3bba794976) | Feb 05, 2023 |
| Acer          | One S1002                   | Notebook    | [2d98ceddca](https://linux-hardware.org/?probe=2d98ceddca) | Feb 05, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [b3ad379bdc](https://linux-hardware.org/?probe=b3ad379bdc) | Feb 05, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [05b252ac05](https://linux-hardware.org/?probe=05b252ac05) | Feb 05, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [d33be0bc3f](https://linux-hardware.org/?probe=d33be0bc3f) | Feb 05, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [0de7e3b318](https://linux-hardware.org/?probe=0de7e3b318) | Feb 05, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [e61bc21eaf](https://linux-hardware.org/?probe=e61bc21eaf) | Feb 05, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [e8b8e1b8e5](https://linux-hardware.org/?probe=e8b8e1b8e5) | Feb 04, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [0f57b84fe7](https://linux-hardware.org/?probe=0f57b84fe7) | Feb 04, 2023 |
| HP            | 2B47                        | Desktop     | [3db96ac186](https://linux-hardware.org/?probe=3db96ac186) | Feb 04, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [0399613500](https://linux-hardware.org/?probe=0399613500) | Feb 04, 2023 |
| Lenovo        | 14w 81MQ00AVCL              | Notebook    | [bd59f68ce8](https://linux-hardware.org/?probe=bd59f68ce8) | Feb 03, 2023 |
| Dell          | Latitude D630               | Notebook    | [aa435d7701](https://linux-hardware.org/?probe=aa435d7701) | Feb 03, 2023 |
| Dell          | Latitude D630               | Notebook    | [b191402036](https://linux-hardware.org/?probe=b191402036) | Feb 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [e5a1cf7284](https://linux-hardware.org/?probe=e5a1cf7284) | Feb 03, 2023 |
| Quanta        | XV1                         | All in one  | [8904f5e7fa](https://linux-hardware.org/?probe=8904f5e7fa) | Feb 03, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [7555fafa98](https://linux-hardware.org/?probe=7555fafa98) | Feb 03, 2023 |
| MSI           | B85M-E45                    | Desktop     | [13453f924e](https://linux-hardware.org/?probe=13453f924e) | Feb 03, 2023 |
| Intel         | X58                         | Desktop     | [55a6a5bd82](https://linux-hardware.org/?probe=55a6a5bd82) | Feb 03, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [5bfa4ad142](https://linux-hardware.org/?probe=5bfa4ad142) | Feb 02, 2023 |
| HP            | 1825                        | Desktop     | [fd942fd3ba](https://linux-hardware.org/?probe=fd942fd3ba) | Feb 02, 2023 |
| Intel         | Unknown                     | Notebook    | [ba5bda9424](https://linux-hardware.org/?probe=ba5bda9424) | Feb 02, 2023 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [324ab7fbd3](https://linux-hardware.org/?probe=324ab7fbd3) | Feb 02, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [e1da7f708a](https://linux-hardware.org/?probe=e1da7f708a) | Feb 02, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [741a1b90bd](https://linux-hardware.org/?probe=741a1b90bd) | Feb 02, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [b34b3228d3](https://linux-hardware.org/?probe=b34b3228d3) | Feb 01, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [95e019beb2](https://linux-hardware.org/?probe=95e019beb2) | Feb 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [b2c18d04be](https://linux-hardware.org/?probe=b2c18d04be) | Feb 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [050126f7f7](https://linux-hardware.org/?probe=050126f7f7) | Feb 01, 2023 |
| MSI           | Raider GE66 12UHS           | Notebook    | [75e83dae8b](https://linux-hardware.org/?probe=75e83dae8b) | Feb 01, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [3fab7107b7](https://linux-hardware.org/?probe=3fab7107b7) | Feb 01, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [d221bc6b8d](https://linux-hardware.org/?probe=d221bc6b8d) | Feb 01, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [51b04e5d58](https://linux-hardware.org/?probe=51b04e5d58) | Feb 01, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [92f6e450b8](https://linux-hardware.org/?probe=92f6e450b8) | Jan 31, 2023 |
| Dell          | Latitude E6540              | Notebook    | [156a047a82](https://linux-hardware.org/?probe=156a047a82) | Jan 31, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [8a53501060](https://linux-hardware.org/?probe=8a53501060) | Jan 31, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [a663152b7c](https://linux-hardware.org/?probe=a663152b7c) | Jan 31, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [ae3838cc5d](https://linux-hardware.org/?probe=ae3838cc5d) | Jan 31, 2023 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [2c021665e1](https://linux-hardware.org/?probe=2c021665e1) | Jan 31, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9bb7eb28ed](https://linux-hardware.org/?probe=9bb7eb28ed) | Jan 31, 2023 |
| HP            | Compaq 6730s                | Notebook    | [1b083e5b64](https://linux-hardware.org/?probe=1b083e5b64) | Jan 31, 2023 |
| HP            | Compaq 6730s                | Notebook    | [ced2899d20](https://linux-hardware.org/?probe=ced2899d20) | Jan 31, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [912213d849](https://linux-hardware.org/?probe=912213d849) | Jan 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [456415a23e](https://linux-hardware.org/?probe=456415a23e) | Jan 30, 2023 |
| Dell          | Latitude E6520              | Notebook    | [f042c5966b](https://linux-hardware.org/?probe=f042c5966b) | Jan 30, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [7b2b210afd](https://linux-hardware.org/?probe=7b2b210afd) | Jan 30, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1F20... | Notebook    | [39b709296b](https://linux-hardware.org/?probe=39b709296b) | Jan 30, 2023 |
| MSI           | H81M-P33                    | Desktop     | [63402c414d](https://linux-hardware.org/?probe=63402c414d) | Jan 30, 2023 |
| HP            | 1791                        | Desktop     | [0cb5402c68](https://linux-hardware.org/?probe=0cb5402c68) | Jan 29, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [56622f5d6c](https://linux-hardware.org/?probe=56622f5d6c) | Jan 29, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [b5612c2501](https://linux-hardware.org/?probe=b5612c2501) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | Notebook    | [47438e081a](https://linux-hardware.org/?probe=47438e081a) | Jan 29, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [d868c23c4b](https://linux-hardware.org/?probe=d868c23c4b) | Jan 29, 2023 |
| Dell          | Precision 5530              | Notebook    | [92399ea8dc](https://linux-hardware.org/?probe=92399ea8dc) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | Notebook    | [621aca8707](https://linux-hardware.org/?probe=621aca8707) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | Notebook    | [55fe252b4e](https://linux-hardware.org/?probe=55fe252b4e) | Jan 29, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [62b104b3d2](https://linux-hardware.org/?probe=62b104b3d2) | Jan 29, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [b7cf9bee5c](https://linux-hardware.org/?probe=b7cf9bee5c) | Jan 28, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [bc4b6513bb](https://linux-hardware.org/?probe=bc4b6513bb) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [0da956ecde](https://linux-hardware.org/?probe=0da956ecde) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [e00bd18cc2](https://linux-hardware.org/?probe=e00bd18cc2) | Jan 28, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ae644e258a](https://linux-hardware.org/?probe=ae644e258a) | Jan 28, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [eeaf26e835](https://linux-hardware.org/?probe=eeaf26e835) | Jan 28, 2023 |
| Dell          | Precision 5530              | Notebook    | [a9a54c5b7f](https://linux-hardware.org/?probe=a9a54c5b7f) | Jan 28, 2023 |
| HP            | 843F                        | Desktop     | [5e9a5d2afd](https://linux-hardware.org/?probe=5e9a5d2afd) | Jan 28, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [ad4f37d5a4](https://linux-hardware.org/?probe=ad4f37d5a4) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a6f188ab67](https://linux-hardware.org/?probe=a6f188ab67) | Jan 28, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [cf4086f3e4](https://linux-hardware.org/?probe=cf4086f3e4) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [57e0449f0f](https://linux-hardware.org/?probe=57e0449f0f) | Jan 28, 2023 |
| HP            | 2B47                        | Desktop     | [cce5f9ec07](https://linux-hardware.org/?probe=cce5f9ec07) | Jan 27, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [b2eb47268c](https://linux-hardware.org/?probe=b2eb47268c) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [e7b74c9ad4](https://linux-hardware.org/?probe=e7b74c9ad4) | Jan 27, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [6a8408404e](https://linux-hardware.org/?probe=6a8408404e) | Jan 27, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [825e70e660](https://linux-hardware.org/?probe=825e70e660) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [9d3e931cc1](https://linux-hardware.org/?probe=9d3e931cc1) | Jan 27, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | Notebook    | [8bd062dd40](https://linux-hardware.org/?probe=8bd062dd40) | Jan 27, 2023 |
| Dell          | Latitude E7470              | Notebook    | [4245585e75](https://linux-hardware.org/?probe=4245585e75) | Jan 27, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [5e0dfe2630](https://linux-hardware.org/?probe=5e0dfe2630) | Jan 27, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [02cd28549c](https://linux-hardware.org/?probe=02cd28549c) | Jan 27, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [c1427c9b7b](https://linux-hardware.org/?probe=c1427c9b7b) | Jan 26, 2023 |
| HP            | Notebook                    | Notebook    | [4c632128bf](https://linux-hardware.org/?probe=4c632128bf) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [951bfcd626](https://linux-hardware.org/?probe=951bfcd626) | Jan 26, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [de7bee1cd6](https://linux-hardware.org/?probe=de7bee1cd6) | Jan 26, 2023 |
| Alienware     | M11xR3                      | Notebook    | [634b7f8eb0](https://linux-hardware.org/?probe=634b7f8eb0) | Jan 26, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [c29f24d0ca](https://linux-hardware.org/?probe=c29f24d0ca) | Jan 26, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [756bf12bd7](https://linux-hardware.org/?probe=756bf12bd7) | Jan 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [c216d513a0](https://linux-hardware.org/?probe=c216d513a0) | Jan 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [06b972165b](https://linux-hardware.org/?probe=06b972165b) | Jan 25, 2023 |
| HP            | 625                         | Notebook    | [06c4fa5119](https://linux-hardware.org/?probe=06c4fa5119) | Jan 25, 2023 |
| Google        | Blorb                       | Notebook    | [adae28c837](https://linux-hardware.org/?probe=adae28c837) | Jan 25, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [5672937ec6](https://linux-hardware.org/?probe=5672937ec6) | Jan 25, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [5dfd026f77](https://linux-hardware.org/?probe=5dfd026f77) | Jan 25, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [c083024afa](https://linux-hardware.org/?probe=c083024afa) | Jan 25, 2023 |
| Sony          | SVE1513C5E                  | Notebook    | [48ee443aef](https://linux-hardware.org/?probe=48ee443aef) | Jan 25, 2023 |
| Lenovo        | ThinkPad T470 20HES0PF00    | Notebook    | [61d7aa3ef9](https://linux-hardware.org/?probe=61d7aa3ef9) | Jan 25, 2023 |
| Google        | Kip                         | Notebook    | [b450bb3bcf](https://linux-hardware.org/?probe=b450bb3bcf) | Jan 24, 2023 |
| Google        | Kip                         | Notebook    | [bf5c5ab5e6](https://linux-hardware.org/?probe=bf5c5ab5e6) | Jan 24, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | Notebook    | [da316254bb](https://linux-hardware.org/?probe=da316254bb) | Jan 24, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [af9518a90a](https://linux-hardware.org/?probe=af9518a90a) | Jan 24, 2023 |
| Dell          | Latitude E7470              | Notebook    | [db73b82761](https://linux-hardware.org/?probe=db73b82761) | Jan 24, 2023 |
| Dell          | Latitude E7470              | Notebook    | [6fd520f670](https://linux-hardware.org/?probe=6fd520f670) | Jan 23, 2023 |
| Acer          | Aspire SW5-012              | Notebook    | [247455614c](https://linux-hardware.org/?probe=247455614c) | Jan 23, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [788d350490](https://linux-hardware.org/?probe=788d350490) | Jan 23, 2023 |
| Acer          | RS880M05                    | Desktop     | [c7e3fe60e1](https://linux-hardware.org/?probe=c7e3fe60e1) | Jan 23, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f72fec3364](https://linux-hardware.org/?probe=f72fec3364) | Jan 23, 2023 |
| Dell          | Latitude E7470              | Notebook    | [525bcdd915](https://linux-hardware.org/?probe=525bcdd915) | Jan 23, 2023 |
| ASUSTek       | T300CHI                     | Notebook    | [bc020f2d3e](https://linux-hardware.org/?probe=bc020f2d3e) | Jan 23, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [20b73bd156](https://linux-hardware.org/?probe=20b73bd156) | Jan 23, 2023 |
| Lenovo        | E51-80 80QB                 | Notebook    | [37073c4323](https://linux-hardware.org/?probe=37073c4323) | Jan 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6d5ca0b2e3](https://linux-hardware.org/?probe=6d5ca0b2e3) | Jan 22, 2023 |
| ASRock        | H61M                        | Desktop     | [f5b1db73f7](https://linux-hardware.org/?probe=f5b1db73f7) | Jan 22, 2023 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [8363dc95c3](https://linux-hardware.org/?probe=8363dc95c3) | Jan 22, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [9e3b6b7075](https://linux-hardware.org/?probe=9e3b6b7075) | Jan 22, 2023 |
| Dell          | Precision M6800             | Notebook    | [a6beff01de](https://linux-hardware.org/?probe=a6beff01de) | Jan 22, 2023 |
| HP            | 625                         | Notebook    | [838d72399b](https://linux-hardware.org/?probe=838d72399b) | Jan 22, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [25013b14a9](https://linux-hardware.org/?probe=25013b14a9) | Jan 22, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1c3214e8c5](https://linux-hardware.org/?probe=1c3214e8c5) | Jan 22, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [b47caaf20b](https://linux-hardware.org/?probe=b47caaf20b) | Jan 22, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [1707a21fed](https://linux-hardware.org/?probe=1707a21fed) | Jan 22, 2023 |
| Itautec       | Infoway w7430               | Notebook    | [b33318e6e0](https://linux-hardware.org/?probe=b33318e6e0) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [90ad82dcac](https://linux-hardware.org/?probe=90ad82dcac) | Jan 21, 2023 |
| HP            | 625                         | Notebook    | [9a8a243973](https://linux-hardware.org/?probe=9a8a243973) | Jan 21, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | Notebook    | [aa8fbd29c9](https://linux-hardware.org/?probe=aa8fbd29c9) | Jan 21, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [548d331968](https://linux-hardware.org/?probe=548d331968) | Jan 21, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [94b155d9c2](https://linux-hardware.org/?probe=94b155d9c2) | Jan 21, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [f52614c5aa](https://linux-hardware.org/?probe=f52614c5aa) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [9579ec96bc](https://linux-hardware.org/?probe=9579ec96bc) | Jan 21, 2023 |
| Timi          | Mi Notebook Pro             | Notebook    | [1db1382f0b](https://linux-hardware.org/?probe=1db1382f0b) | Jan 21, 2023 |
| HP            | 89B5 A                      | Desktop     | [1b6e288840](https://linux-hardware.org/?probe=1b6e288840) | Jan 21, 2023 |
| Lenovo        | G560 20042                  | Notebook    | [9c78155cfe](https://linux-hardware.org/?probe=9c78155cfe) | Jan 20, 2023 |
| Lenovo        | G560 20042                  | Notebook    | [61e3ee0517](https://linux-hardware.org/?probe=61e3ee0517) | Jan 20, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [f3af245bf8](https://linux-hardware.org/?probe=f3af245bf8) | Jan 20, 2023 |
| HP            | 843F                        | Desktop     | [07f6efa703](https://linux-hardware.org/?probe=07f6efa703) | Jan 20, 2023 |
| Acer          | Aspire A317-33              | Notebook    | [b7147af4f6](https://linux-hardware.org/?probe=b7147af4f6) | Jan 20, 2023 |
| ASUSTek       | M4A3000E                    | Desktop     | [650236c7cc](https://linux-hardware.org/?probe=650236c7cc) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [d7344938fb](https://linux-hardware.org/?probe=d7344938fb) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [9b3bbccece](https://linux-hardware.org/?probe=9b3bbccece) | Jan 19, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [8131194ea1](https://linux-hardware.org/?probe=8131194ea1) | Jan 19, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [6bc203c6fd](https://linux-hardware.org/?probe=6bc203c6fd) | Jan 19, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [90746298fc](https://linux-hardware.org/?probe=90746298fc) | Jan 19, 2023 |
| HP            | 843F                        | Desktop     | [83ca70ac2d](https://linux-hardware.org/?probe=83ca70ac2d) | Jan 19, 2023 |
| HP            | ProBook 4740s               | Notebook    | [3392f975ec](https://linux-hardware.org/?probe=3392f975ec) | Jan 19, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [82b540a137](https://linux-hardware.org/?probe=82b540a137) | Jan 19, 2023 |
| ASUSTek       | M4A3000E                    | Desktop     | [4f8a71f0c5](https://linux-hardware.org/?probe=4f8a71f0c5) | Jan 19, 2023 |
| Acer          | Aspire E5-774G              | Notebook    | [f3ab78c392](https://linux-hardware.org/?probe=f3ab78c392) | Jan 19, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [4908236396](https://linux-hardware.org/?probe=4908236396) | Jan 19, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [9e17ffeecc](https://linux-hardware.org/?probe=9e17ffeecc) | Jan 19, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [cfe9a9d924](https://linux-hardware.org/?probe=cfe9a9d924) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [7be5d0d09b](https://linux-hardware.org/?probe=7be5d0d09b) | Jan 18, 2023 |
| HP            | 15                          | Notebook    | [cebe1b150e](https://linux-hardware.org/?probe=cebe1b150e) | Jan 18, 2023 |
| Packard Be... | EasyNote TM82               | Notebook    | [49ae8de234](https://linux-hardware.org/?probe=49ae8de234) | Jan 18, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6f91cb09e7](https://linux-hardware.org/?probe=6f91cb09e7) | Jan 18, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [dfac4d4f79](https://linux-hardware.org/?probe=dfac4d4f79) | Jan 17, 2023 |
| Google        | Kip                         | Notebook    | [e74935629a](https://linux-hardware.org/?probe=e74935629a) | Jan 17, 2023 |
| Google        | Kip                         | Notebook    | [558cff5048](https://linux-hardware.org/?probe=558cff5048) | Jan 17, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2efb4b16de](https://linux-hardware.org/?probe=2efb4b16de) | Jan 17, 2023 |
| HP            | 3397                        | Desktop     | [a58c9ac196](https://linux-hardware.org/?probe=a58c9ac196) | Jan 17, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [5ebc1885c3](https://linux-hardware.org/?probe=5ebc1885c3) | Jan 17, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [d87fb3cf65](https://linux-hardware.org/?probe=d87fb3cf65) | Jan 17, 2023 |
| Fujitsu       | LIFEBOOK T726               | Convertible | [ab8e5c3c70](https://linux-hardware.org/?probe=ab8e5c3c70) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [e9e902c625](https://linux-hardware.org/?probe=e9e902c625) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [00ebda8ae9](https://linux-hardware.org/?probe=00ebda8ae9) | Jan 17, 2023 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | Notebook    | [473ae331ec](https://linux-hardware.org/?probe=473ae331ec) | Jan 16, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [69b469a6fb](https://linux-hardware.org/?probe=69b469a6fb) | Jan 16, 2023 |
| Wortmann      | Mobile 1524                 | Notebook    | [17fc7e2f75](https://linux-hardware.org/?probe=17fc7e2f75) | Jan 16, 2023 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [bb62149054](https://linux-hardware.org/?probe=bb62149054) | Jan 16, 2023 |
| Medion        | MS-7707                     | Desktop     | [9665ceabf1](https://linux-hardware.org/?probe=9665ceabf1) | Jan 16, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f4232dc72a](https://linux-hardware.org/?probe=f4232dc72a) | Jan 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [3677d8f4e7](https://linux-hardware.org/?probe=3677d8f4e7) | Jan 15, 2023 |
| Lenovo        | G560 0679                   | Notebook    | [26e16a5898](https://linux-hardware.org/?probe=26e16a5898) | Jan 15, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [a728c46633](https://linux-hardware.org/?probe=a728c46633) | Jan 15, 2023 |
| Dell          | Inspiron 7437               | Notebook    | [df8d69926f](https://linux-hardware.org/?probe=df8d69926f) | Jan 15, 2023 |
| Dell          | Inspiron 7437               | Notebook    | [0670d91eb0](https://linux-hardware.org/?probe=0670d91eb0) | Jan 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [a69d4b7b4f](https://linux-hardware.org/?probe=a69d4b7b4f) | Jan 15, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [2f2fec82c8](https://linux-hardware.org/?probe=2f2fec82c8) | Jan 15, 2023 |
| Tactus        | GeoPad 110                  | Tablet      | [810d937888](https://linux-hardware.org/?probe=810d937888) | Jan 14, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [331b5e3efa](https://linux-hardware.org/?probe=331b5e3efa) | Jan 14, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [e5ab68f182](https://linux-hardware.org/?probe=e5ab68f182) | Jan 14, 2023 |
| ASUSTek       | K75VM                       | Notebook    | [6cd0e1793b](https://linux-hardware.org/?probe=6cd0e1793b) | Jan 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [9cb802849a](https://linux-hardware.org/?probe=9cb802849a) | Jan 14, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [19531b68b1](https://linux-hardware.org/?probe=19531b68b1) | Jan 14, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [941c62872e](https://linux-hardware.org/?probe=941c62872e) | Jan 14, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [6c53f137fd](https://linux-hardware.org/?probe=6c53f137fd) | Jan 14, 2023 |
| HP            | Presario F500 (GF795EA#A... | Notebook    | [588148e349](https://linux-hardware.org/?probe=588148e349) | Jan 14, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [e00028a10c](https://linux-hardware.org/?probe=e00028a10c) | Jan 14, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [845fca1774](https://linux-hardware.org/?probe=845fca1774) | Jan 14, 2023 |
| HC            | HCAR357-MI V1.0             | Desktop     | [b5f80f8eac](https://linux-hardware.org/?probe=b5f80f8eac) | Jan 14, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [8a4bbb603e](https://linux-hardware.org/?probe=8a4bbb603e) | Jan 14, 2023 |
| Sony          | SVE1513U1ESI                | Notebook    | [d1c4a0dc83](https://linux-hardware.org/?probe=d1c4a0dc83) | Jan 14, 2023 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [ddf679df3a](https://linux-hardware.org/?probe=ddf679df3a) | Jan 14, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [c5edc9fbc7](https://linux-hardware.org/?probe=c5edc9fbc7) | Jan 14, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [baa87ed4e0](https://linux-hardware.org/?probe=baa87ed4e0) | Jan 13, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [cb94045e18](https://linux-hardware.org/?probe=cb94045e18) | Jan 13, 2023 |
| Fujitsu       | FARQ02010                   | Notebook    | [5d3f5fcee2](https://linux-hardware.org/?probe=5d3f5fcee2) | Jan 13, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [250b4a09a0](https://linux-hardware.org/?probe=250b4a09a0) | Jan 13, 2023 |
| HP            | 3397                        | Desktop     | [baae324548](https://linux-hardware.org/?probe=baae324548) | Jan 13, 2023 |
| Acer          | FRS690L                     | Desktop     | [5b27fe10aa](https://linux-hardware.org/?probe=5b27fe10aa) | Jan 13, 2023 |
| Kiano         | Elegance 13.3               | Notebook    | [2e77ce51b9](https://linux-hardware.org/?probe=2e77ce51b9) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [07cedbf55a](https://linux-hardware.org/?probe=07cedbf55a) | Jan 12, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [3d1b3bf218](https://linux-hardware.org/?probe=3d1b3bf218) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [1706cf55cf](https://linux-hardware.org/?probe=1706cf55cf) | Jan 12, 2023 |
| GPU Compan... | GWTC116-2                   | Convertible | [a1c1965381](https://linux-hardware.org/?probe=a1c1965381) | Jan 12, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [0092ec8702](https://linux-hardware.org/?probe=0092ec8702) | Jan 12, 2023 |
| Acer          | Aspire 2920                 | Notebook    | [0766ea34c6](https://linux-hardware.org/?probe=0766ea34c6) | Jan 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [fb5857252b](https://linux-hardware.org/?probe=fb5857252b) | Jan 12, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [78eb96d148](https://linux-hardware.org/?probe=78eb96d148) | Jan 11, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [4ac36f25a9](https://linux-hardware.org/?probe=4ac36f25a9) | Jan 11, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [9dfcb68d9a](https://linux-hardware.org/?probe=9dfcb68d9a) | Jan 11, 2023 |
| Wortmann      | TERRA_MOBILE_1062           | Tablet      | [d363c969bc](https://linux-hardware.org/?probe=d363c969bc) | Jan 10, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [fd9ae626c7](https://linux-hardware.org/?probe=fd9ae626c7) | Jan 10, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [8c41599fdd](https://linux-hardware.org/?probe=8c41599fdd) | Jan 10, 2023 |
| HP            | 843B                        | Desktop     | [ac14cee88f](https://linux-hardware.org/?probe=ac14cee88f) | Jan 10, 2023 |
| HP            | Notebook                    | Notebook    | [8df5d522da](https://linux-hardware.org/?probe=8df5d522da) | Jan 10, 2023 |
| HP            | Notebook                    | Notebook    | [c58dde8021](https://linux-hardware.org/?probe=c58dde8021) | Jan 10, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [cb037b984e](https://linux-hardware.org/?probe=cb037b984e) | Jan 10, 2023 |
| HP            | 843B                        | Desktop     | [e45a20a47f](https://linux-hardware.org/?probe=e45a20a47f) | Jan 10, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [04a9deb0c1](https://linux-hardware.org/?probe=04a9deb0c1) | Jan 10, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [5aaaf24b85](https://linux-hardware.org/?probe=5aaaf24b85) | Jan 09, 2023 |
| HP            | Pavilion dv6                | Notebook    | [852e84ccaa](https://linux-hardware.org/?probe=852e84ccaa) | Jan 09, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d482768ec9](https://linux-hardware.org/?probe=d482768ec9) | Jan 09, 2023 |
| ASUSTek       | M4A88T-M                    | Desktop     | [4c3d063774](https://linux-hardware.org/?probe=4c3d063774) | Jan 09, 2023 |
| Dell          | Latitude E6510              | Notebook    | [28cceb82e3](https://linux-hardware.org/?probe=28cceb82e3) | Jan 09, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [a8f14a8a8e](https://linux-hardware.org/?probe=a8f14a8a8e) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [5bd32eb6f6](https://linux-hardware.org/?probe=5bd32eb6f6) | Jan 08, 2023 |
| ASUSTek       | X555LF                      | Notebook    | [0ff44cdd4f](https://linux-hardware.org/?probe=0ff44cdd4f) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [88ba7d805e](https://linux-hardware.org/?probe=88ba7d805e) | Jan 08, 2023 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [abc1a27105](https://linux-hardware.org/?probe=abc1a27105) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [b5b4c3f6ef](https://linux-hardware.org/?probe=b5b4c3f6ef) | Jan 08, 2023 |
| HP            | 2129                        | Desktop     | [4d6113e60d](https://linux-hardware.org/?probe=4d6113e60d) | Jan 08, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [2b3261504f](https://linux-hardware.org/?probe=2b3261504f) | Jan 08, 2023 |
| MSI           | CR62 6M                     | Notebook    | [942ca0f3b3](https://linux-hardware.org/?probe=942ca0f3b3) | Jan 07, 2023 |
| Sony          | VAIO                        | All in one  | [1f521568e1](https://linux-hardware.org/?probe=1f521568e1) | Jan 07, 2023 |
| MAXSUN        | MS-TZZ A320M.2-VH           | Desktop     | [f3e00dc862](https://linux-hardware.org/?probe=f3e00dc862) | Jan 07, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [4c680e9948](https://linux-hardware.org/?probe=4c680e9948) | Jan 07, 2023 |
| HP            | Laptop 17-cp1xxx            | Notebook    | [d699356fd1](https://linux-hardware.org/?probe=d699356fd1) | Jan 07, 2023 |
| HP            | 2B47                        | Desktop     | [8ad8cb5e8f](https://linux-hardware.org/?probe=8ad8cb5e8f) | Jan 06, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | Desktop     | [2df76bde47](https://linux-hardware.org/?probe=2df76bde47) | Jan 06, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [6148bc3313](https://linux-hardware.org/?probe=6148bc3313) | Jan 06, 2023 |
| Multilaser    | PC024                       | Notebook    | [006690ac84](https://linux-hardware.org/?probe=006690ac84) | Jan 06, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | Notebook    | [1afcc520de](https://linux-hardware.org/?probe=1afcc520de) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [9b828358df](https://linux-hardware.org/?probe=9b828358df) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [7cf92f3f43](https://linux-hardware.org/?probe=7cf92f3f43) | Jan 05, 2023 |
| Multilaser    | PC024                       | Notebook    | [8d9a2a1304](https://linux-hardware.org/?probe=8d9a2a1304) | Jan 05, 2023 |
| Dell          | Precision M90               | Notebook    | [b622160555](https://linux-hardware.org/?probe=b622160555) | Jan 05, 2023 |
| HP            | ProBook 4540s               | Notebook    | [6e2638a12e](https://linux-hardware.org/?probe=6e2638a12e) | Jan 04, 2023 |
| Toshiba       | Satellite C50D-B            | Notebook    | [e4bc0d4130](https://linux-hardware.org/?probe=e4bc0d4130) | Jan 04, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [4ec59dca55](https://linux-hardware.org/?probe=4ec59dca55) | Jan 04, 2023 |
| Sony          | VPCEB3L1E                   | Notebook    | [e8ac8a5d95](https://linux-hardware.org/?probe=e8ac8a5d95) | Jan 04, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [7fff20462c](https://linux-hardware.org/?probe=7fff20462c) | Jan 03, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [e597f176c2](https://linux-hardware.org/?probe=e597f176c2) | Jan 03, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [309e449325](https://linux-hardware.org/?probe=309e449325) | Jan 03, 2023 |
| HP            | Pavilion dv7                | Notebook    | [574f62a8ad](https://linux-hardware.org/?probe=574f62a8ad) | Jan 03, 2023 |
| Dell          | 018D1Y A00                  | Desktop     | [9ba9bcee90](https://linux-hardware.org/?probe=9ba9bcee90) | Jan 03, 2023 |
| Foxconn       | H67S/H61SP                  | Desktop     | [c7684d1f93](https://linux-hardware.org/?probe=c7684d1f93) | Jan 03, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [ce3dc1998f](https://linux-hardware.org/?probe=ce3dc1998f) | Jan 02, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [fcf5d132a5](https://linux-hardware.org/?probe=fcf5d132a5) | Jan 02, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [f31ae01428](https://linux-hardware.org/?probe=f31ae01428) | Jan 02, 2023 |
| HP            | 8350                        | Desktop     | [3ab0d55a41](https://linux-hardware.org/?probe=3ab0d55a41) | Jan 02, 2023 |
| ASUSTek       | D300TA                      | Desktop     | [f522fa7b4d](https://linux-hardware.org/?probe=f522fa7b4d) | Jan 02, 2023 |
| Acer          | Aspire 4310                 | Notebook    | [e179184ea3](https://linux-hardware.org/?probe=e179184ea3) | Jan 02, 2023 |
| Dell          | Latitude E5440              | Notebook    | [d8b08abf08](https://linux-hardware.org/?probe=d8b08abf08) | Jan 02, 2023 |
| HP            | Pavilion dv6                | Notebook    | [d735200dcf](https://linux-hardware.org/?probe=d735200dcf) | Jan 01, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [64c803c589](https://linux-hardware.org/?probe=64c803c589) | Jan 01, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [b1007671e3](https://linux-hardware.org/?probe=b1007671e3) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | Notebook    | [91741e63eb](https://linux-hardware.org/?probe=91741e63eb) | Jan 01, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [f95906c714](https://linux-hardware.org/?probe=f95906c714) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | Notebook    | [6ac462efda](https://linux-hardware.org/?probe=6ac462efda) | Jan 01, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [0360bb01d0](https://linux-hardware.org/?probe=0360bb01d0) | Jan 01, 2023 |
| Dell          | Latitude E5500              | Notebook    | [f04cd8f466](https://linux-hardware.org/?probe=f04cd8f466) | Dec 31, 2022 |
| Dell          | Latitude E5500              | Notebook    | [24a0ca1b65](https://linux-hardware.org/?probe=24a0ca1b65) | Dec 31, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [39c9c8aaea](https://linux-hardware.org/?probe=39c9c8aaea) | Dec 31, 2022 |
| Dell          | 0T10XW A00                  | Desktop     | [21638e1dfe](https://linux-hardware.org/?probe=21638e1dfe) | Dec 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9220da7abb](https://linux-hardware.org/?probe=9220da7abb) | Dec 31, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [39f08657f8](https://linux-hardware.org/?probe=39f08657f8) | Dec 31, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [43f808e1e4](https://linux-hardware.org/?probe=43f808e1e4) | Dec 30, 2022 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [c8da48f03c](https://linux-hardware.org/?probe=c8da48f03c) | Dec 30, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [b8eccb0fbe](https://linux-hardware.org/?probe=b8eccb0fbe) | Dec 30, 2022 |
| Biostar       | TA970                       | Desktop     | [6a55825894](https://linux-hardware.org/?probe=6a55825894) | Dec 30, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e0e5f33e60](https://linux-hardware.org/?probe=e0e5f33e60) | Dec 30, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [c841093094](https://linux-hardware.org/?probe=c841093094) | Dec 30, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [59f6170d5b](https://linux-hardware.org/?probe=59f6170d5b) | Dec 29, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [e4e5afd812](https://linux-hardware.org/?probe=e4e5afd812) | Dec 29, 2022 |
| ASUSTek       | X540YA                      | Notebook    | [d128cfee28](https://linux-hardware.org/?probe=d128cfee28) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [0d8d6061d7](https://linux-hardware.org/?probe=0d8d6061d7) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [4bda137e99](https://linux-hardware.org/?probe=4bda137e99) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [7ce6d4b3e3](https://linux-hardware.org/?probe=7ce6d4b3e3) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [f828f74e07](https://linux-hardware.org/?probe=f828f74e07) | Dec 29, 2022 |
| PCWare        | IPMH61R1                    | Desktop     | [a221946f02](https://linux-hardware.org/?probe=a221946f02) | Dec 29, 2022 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [cc1dd99957](https://linux-hardware.org/?probe=cc1dd99957) | Dec 28, 2022 |
| Dell          | 03KWTV A02                  | Desktop     | [82612358ac](https://linux-hardware.org/?probe=82612358ac) | Dec 28, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0c49efe5e1](https://linux-hardware.org/?probe=0c49efe5e1) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [27e072cb3e](https://linux-hardware.org/?probe=27e072cb3e) | Dec 28, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [75fe6d9325](https://linux-hardware.org/?probe=75fe6d9325) | Dec 28, 2022 |
| HP            | 2AF7                        | Desktop     | [9663a281c1](https://linux-hardware.org/?probe=9663a281c1) | Dec 28, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | Notebook    | [70d10e91fb](https://linux-hardware.org/?probe=70d10e91fb) | Dec 28, 2022 |
| Toshiba       | Satellite C50-B             | Notebook    | [31241c1f30](https://linux-hardware.org/?probe=31241c1f30) | Dec 28, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [b65d5ce654](https://linux-hardware.org/?probe=b65d5ce654) | Dec 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [6aa557fb75](https://linux-hardware.org/?probe=6aa557fb75) | Dec 27, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [71c1ee486e](https://linux-hardware.org/?probe=71c1ee486e) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [2c6e8a0c9f](https://linux-hardware.org/?probe=2c6e8a0c9f) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [b3db56361b](https://linux-hardware.org/?probe=b3db56361b) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0763603d12](https://linux-hardware.org/?probe=0763603d12) | Dec 27, 2022 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Convertible | [2fe0a7fe8b](https://linux-hardware.org/?probe=2fe0a7fe8b) | Dec 27, 2022 |
| Acer          | Aspire XC-780               | Desktop     | [0d90d1884c](https://linux-hardware.org/?probe=0d90d1884c) | Dec 27, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [5ce1ea886f](https://linux-hardware.org/?probe=5ce1ea886f) | Dec 26, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | Notebook    | [052cdcd8bb](https://linux-hardware.org/?probe=052cdcd8bb) | Dec 26, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | Notebook    | [940218d084](https://linux-hardware.org/?probe=940218d084) | Dec 26, 2022 |
| Lenovo        | ThinkPad E590 20NB001AMX    | Notebook    | [047944fa9f](https://linux-hardware.org/?probe=047944fa9f) | Dec 26, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [f56ea263a2](https://linux-hardware.org/?probe=f56ea263a2) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [da3f79863a](https://linux-hardware.org/?probe=da3f79863a) | Dec 26, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [047823ffbc](https://linux-hardware.org/?probe=047823ffbc) | Dec 26, 2022 |
| ASUSTek       | T100TAS                     | Notebook    | [25894bb300](https://linux-hardware.org/?probe=25894bb300) | Dec 26, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [1ba51900a6](https://linux-hardware.org/?probe=1ba51900a6) | Dec 25, 2022 |
| Acer          | Aspire M3-581G              | Notebook    | [67071376c6](https://linux-hardware.org/?probe=67071376c6) | Dec 25, 2022 |
| HP            | 2AF7                        | Desktop     | [287696b4fc](https://linux-hardware.org/?probe=287696b4fc) | Dec 25, 2022 |
| Gigabyte      | GA-770T-USB3                | Desktop     | [08d1b04754](https://linux-hardware.org/?probe=08d1b04754) | Dec 25, 2022 |
| Sony          | VGN-NR32M_S                 | Notebook    | [6ad0da2e88](https://linux-hardware.org/?probe=6ad0da2e88) | Dec 25, 2022 |
| ASRock        | 970 Extreme4                | Desktop     | [2655b3c6b6](https://linux-hardware.org/?probe=2655b3c6b6) | Dec 24, 2022 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [1c2f8d9457](https://linux-hardware.org/?probe=1c2f8d9457) | Dec 24, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [e968a4fe6d](https://linux-hardware.org/?probe=e968a4fe6d) | Dec 24, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [2415ad5980](https://linux-hardware.org/?probe=2415ad5980) | Dec 24, 2022 |
| HP            | Compaq 6730b (NB034ET#UU... | Notebook    | [304e2ca750](https://linux-hardware.org/?probe=304e2ca750) | Dec 24, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [9bcea5d857](https://linux-hardware.org/?probe=9bcea5d857) | Dec 24, 2022 |
| HP            | Pavilion dv7                | Notebook    | [a099e9b6ac](https://linux-hardware.org/?probe=a099e9b6ac) | Dec 24, 2022 |
| Intel         | H61                         | Desktop     | [8d5eb236e1](https://linux-hardware.org/?probe=8d5eb236e1) | Dec 24, 2022 |
| HP            | Pavilion g7                 | Notebook    | [ef4cc6fa1a](https://linux-hardware.org/?probe=ef4cc6fa1a) | Dec 24, 2022 |
| HP            | 2AF7                        | Desktop     | [7b79dd8352](https://linux-hardware.org/?probe=7b79dd8352) | Dec 23, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [3e8fb581f0](https://linux-hardware.org/?probe=3e8fb581f0) | Dec 23, 2022 |
| HP            | 2AF7                        | Desktop     | [5ef9ce3357](https://linux-hardware.org/?probe=5ef9ce3357) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | Desktop     | [08a8cc75ac](https://linux-hardware.org/?probe=08a8cc75ac) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | Desktop     | [bd8a5003e8](https://linux-hardware.org/?probe=bd8a5003e8) | Dec 23, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [bb9724d53f](https://linux-hardware.org/?probe=bb9724d53f) | Dec 23, 2022 |
| Dell          | Latitude E4310              | Notebook    | [6386845196](https://linux-hardware.org/?probe=6386845196) | Dec 23, 2022 |
| ASRock        | G31M-S                      | Desktop     | [476c5ec563](https://linux-hardware.org/?probe=476c5ec563) | Dec 22, 2022 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | Notebook    | [f82f15da88](https://linux-hardware.org/?probe=f82f15da88) | Dec 22, 2022 |
| MSI           | H61MU-E35                   | Desktop     | [cb9ec3d5ad](https://linux-hardware.org/?probe=cb9ec3d5ad) | Dec 22, 2022 |
| MSI           | H61MU-E35                   | Desktop     | [bfdc9d1e12](https://linux-hardware.org/?probe=bfdc9d1e12) | Dec 22, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [f497db99b3](https://linux-hardware.org/?probe=f497db99b3) | Dec 22, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [79aabf81c4](https://linux-hardware.org/?probe=79aabf81c4) | Dec 22, 2022 |
| ECS           | H110M4-C2H                  | Desktop     | [f349ed8914](https://linux-hardware.org/?probe=f349ed8914) | Dec 22, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [2279954594](https://linux-hardware.org/?probe=2279954594) | Dec 22, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c0f831d7a4](https://linux-hardware.org/?probe=c0f831d7a4) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [279e1eacf6](https://linux-hardware.org/?probe=279e1eacf6) | Dec 22, 2022 |
| ASRock        | G31M-S                      | Desktop     | [88d93da5a7](https://linux-hardware.org/?probe=88d93da5a7) | Dec 22, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [3caae1ba3b](https://linux-hardware.org/?probe=3caae1ba3b) | Dec 21, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [8d8716cdca](https://linux-hardware.org/?probe=8d8716cdca) | Dec 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [2e63730e46](https://linux-hardware.org/?probe=2e63730e46) | Dec 21, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [64cd4afc6d](https://linux-hardware.org/?probe=64cd4afc6d) | Dec 21, 2022 |
| PCWare        | IPMH310 PRO 1.0             | Desktop     | [c4dea5edbb](https://linux-hardware.org/?probe=c4dea5edbb) | Dec 21, 2022 |
| Sony          | VJZ13A                      | Notebook    | [748f77bace](https://linux-hardware.org/?probe=748f77bace) | Dec 21, 2022 |
| Dell          | Latitude E4310              | Notebook    | [7b184a032b](https://linux-hardware.org/?probe=7b184a032b) | Dec 21, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [06c3b647be](https://linux-hardware.org/?probe=06c3b647be) | Dec 21, 2022 |
| MSI           | GS73VR 7RF                  | Notebook    | [7f37920146](https://linux-hardware.org/?probe=7f37920146) | Dec 20, 2022 |
| Dell          | 0MGK50 A04                  | Desktop     | [931b01be38](https://linux-hardware.org/?probe=931b01be38) | Dec 20, 2022 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [5212fb0d93](https://linux-hardware.org/?probe=5212fb0d93) | Dec 20, 2022 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [9f456f73eb](https://linux-hardware.org/?probe=9f456f73eb) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [03e2c64868](https://linux-hardware.org/?probe=03e2c64868) | Dec 20, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [ca027f264a](https://linux-hardware.org/?probe=ca027f264a) | Dec 20, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [83df1364c8](https://linux-hardware.org/?probe=83df1364c8) | Dec 20, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [0e5b8434fe](https://linux-hardware.org/?probe=0e5b8434fe) | Dec 20, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [83a3d8e955](https://linux-hardware.org/?probe=83a3d8e955) | Dec 19, 2022 |
| GPD           | G1619-04                    | Notebook    | [f184c297f2](https://linux-hardware.org/?probe=f184c297f2) | Dec 19, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_16/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 215       | 6.46%   |
| 5.11.0-38-generic | 179       | 5.38%   |
| 5.11.0-27-generic | 154       | 4.62%   |
| 5.15.0-46-generic | 152       | 4.56%   |
| 5.15.0-58-generic | 150       | 4.5%    |
| 5.15.0-52-generic | 145       | 4.35%   |
| 5.15.0-67-generic | 139       | 4.17%   |
| 5.15.0-69-generic | 132       | 3.96%   |
| 5.13.0-30-generic | 125       | 3.75%   |
| 5.11.0-40-generic | 124       | 3.72%   |
| 5.13.0-39-generic | 120       | 3.6%    |
| 5.11.0-41-generic | 107       | 3.21%   |
| 5.11.0-37-generic | 107       | 3.21%   |
| 5.15.0-60-generic | 105       | 3.15%   |
| 5.11.0-43-generic | 101       | 3.03%   |
| 5.15.0-48-generic | 95        | 2.85%   |
| 5.11.0-34-generic | 94        | 2.82%   |
| 5.13.0-40-generic | 89        | 2.67%   |
| 5.15.0-53-generic | 79        | 2.37%   |
| 5.15.0-41-generic | 76        | 2.28%   |
| 5.13.0-44-generic | 76        | 2.28%   |
| 5.13.0-35-generic | 74        | 2.22%   |
| 5.13.0-28-generic | 73        | 2.19%   |
| 5.13.0-52-generic | 59        | 1.77%   |
| 5.13.0-27-generic | 59        | 1.77%   |
| 5.13.0-41-generic | 54        | 1.62%   |
| 5.13.0-51-generic | 42        | 1.26%   |
| 5.15.0-43-generic | 40        | 1.2%    |
| 5.11.0-36-generic | 39        | 1.17%   |
| 5.15.0-57-generic | 35        | 1.05%   |
| 5.11.0-46-generic | 35        | 1.05%   |
| 5.11.0-44-generic | 34        | 1.02%   |
| 5.13.0-37-generic | 29        | 0.87%   |
| 5.13.0-48-generic | 23        | 0.69%   |
| 5.15.0-50-generic | 20        | 0.6%    |
| 5.15.0-71-generic | 18        | 0.54%   |
| 5.11.0-25-generic | 17        | 0.51%   |
| 5.8.0-53-generic  | 13        | 0.39%   |
| 5.8.0-50-generic  | 12        | 0.36%   |
| 5.8.0-59-generic  | 9         | 0.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 1262      | 41.03%  |
| 5.11.0  | 948       | 30.82%  |
| 5.13.0  | 766       | 24.9%   |
| 5.8.0   | 53        | 1.72%   |
| 5.14.0  | 10        | 0.33%   |
| 5.4.0   | 3         | 0.1%    |
| 5.19.12 | 2         | 0.07%   |
| 5.18.15 | 2         | 0.07%   |
| 5.17.5  | 2         | 0.07%   |
| 5.17.1  | 2         | 0.07%   |
| 5.16.0  | 2         | 0.07%   |
| 5.10.0  | 2         | 0.07%   |
| 6.2.7   | 1         | 0.03%   |
| 6.1.8   | 1         | 0.03%   |
| 6.1.7   | 1         | 0.03%   |
| 6.0.8   | 1         | 0.03%   |
| 6.0.19  | 1         | 0.03%   |
| 6.0.0   | 1         | 0.03%   |
| 5.4.180 | 1         | 0.03%   |
| 5.19.9  | 1         | 0.03%   |
| 5.19.6  | 1         | 0.03%   |
| 5.19.2  | 1         | 0.03%   |
| 5.19.14 | 1         | 0.03%   |
| 5.19.1  | 1         | 0.03%   |
| 5.19.0  | 1         | 0.03%   |
| 5.18.6  | 1         | 0.03%   |
| 5.17.9  | 1         | 0.03%   |
| 5.16.5  | 1         | 0.03%   |
| 5.16.14 | 1         | 0.03%   |
| 5.16.12 | 1         | 0.03%   |
| 5.15.49 | 1         | 0.03%   |
| 5.15.24 | 1         | 0.03%   |
| 5.15.13 | 1         | 0.03%   |
| 5.13.18 | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 1265      | 41.14%  |
| 5.11    | 948       | 30.83%  |
| 5.13    | 767       | 24.94%  |
| 5.8     | 53        | 1.72%   |
| 5.14    | 10        | 0.33%   |
| 5.19    | 8         | 0.26%   |
| 5.17    | 5         | 0.16%   |
| 5.16    | 5         | 0.16%   |
| 5.4     | 4         | 0.13%   |
| 6.0     | 3         | 0.1%    |
| 5.18    | 3         | 0.1%    |
| 5.10    | 2         | 0.07%   |
| 6.2     | 1         | 0.03%   |
| 6.1     | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 2934      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 2554      | 86.46%  |
| XFCE       | 365       | 12.36%  |
| Unknown    | 18        | 0.61%   |
| X-Cinnamon | 4         | 0.14%   |
| Cinnamon   | 3         | 0.1%    |
| Budgie     | 3         | 0.1%    |
| KDE5       | 2         | 0.07%   |
| Unity      | 1         | 0.03%   |
| MATE       | 1         | 0.03%   |
| LXDE       | 1         | 0.03%   |
| KDE        | 1         | 0.03%   |
| i3         | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2893      | 98.1%   |
| Wayland | 48        | 1.63%   |
| Unknown | 6         | 0.2%    |
| Tty     | 2         | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2310      | 77.75%  |
| GDM     | 303       | 10.2%   |
| GDM3    | 265       | 8.92%   |
| LightDM | 89        | 3%      |
| SDDM    | 2         | 0.07%   |
| TDM     | 1         | 0.03%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 1171      | 39.74%  |
| de_DE | 282       | 9.57%   |
| en_GB | 205       | 6.96%   |
| pt_BR | 171       | 5.8%    |
| fr_FR | 100       | 3.39%   |
| it_IT | 87        | 2.95%   |
| es_ES | 83        | 2.82%   |
| en_IN | 80        | 2.71%   |
| en_CA | 79        | 2.68%   |
| pl_PL | 68        | 2.31%   |
| en_AU | 64        | 2.17%   |
| nl_NL | 51        | 1.73%   |
| ru_RU | 43        | 1.46%   |
| es_MX | 40        | 1.36%   |
| en_ZA | 28        | 0.95%   |
| pt_PT | 26        | 0.88%   |
| cs_CZ | 26        | 0.88%   |
| hu_HU | 20        | 0.68%   |
| es_AR | 20        | 0.68%   |
| tr_TR | 17        | 0.58%   |
| sv_SE | 17        | 0.58%   |
| en_NZ | 16        | 0.54%   |
| nl_BE | 15        | 0.51%   |
| fr_BE | 15        | 0.51%   |
| es_CL | 14        | 0.48%   |
| de_CH | 14        | 0.48%   |
| de_AT | 12        | 0.41%   |
| fr_CA | 11        | 0.37%   |
| ja_JP | 10        | 0.34%   |
| es_CO | 10        | 0.34%   |
| nb_NO | 9         | 0.31%   |
| fi_FI | 9         | 0.31%   |
| el_GR | 9         | 0.31%   |
| en_PH | 8         | 0.27%   |
| es_VE | 7         | 0.24%   |
| es_CR | 6         | 0.2%    |
| ar_EG | 6         | 0.2%    |
| sk_SK | 5         | 0.17%   |
| en_IL | 5         | 0.17%   |
| da_DK | 5         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1688      | 56.89%  |
| BIOS | 1279      | 43.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 2786      | 94.63%  |
| Zfs      | 58        | 1.97%   |
| Overlay  | 48        | 1.63%   |
| Btrfs    | 28        | 0.95%   |
| Xfs      | 8         | 0.27%   |
| Ext2     | 7         | 0.24%   |
| Ext3     | 5         | 0.17%   |
| Tmpfs    | 2         | 0.07%   |
| Reiserfs | 1         | 0.03%   |
| Jfs      | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2486      | 83.82%  |
| GPT     | 375       | 12.64%  |
| MBR     | 105       | 3.54%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2865      | 97.38%  |
| Yes       | 77        | 2.62%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2652      | 90.11%  |
| Yes       | 291       | 9.89%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 482       | 16.43%  |
| ASUSTek Computer    | 447       | 15.24%  |
| Dell                | 387       | 13.19%  |
| Lenovo              | 370       | 12.61%  |
| Gigabyte Technology | 175       | 5.96%   |
| Acer                | 149       | 5.08%   |
| MSI                 | 142       | 4.84%   |
| Apple               | 101       | 3.44%   |
| ASRock              | 79        | 2.69%   |
| Toshiba             | 71        | 2.42%   |
| Intel               | 47        | 1.6%    |
| Samsung Electronics | 33        | 1.12%   |
| Unknown             | 29        | 0.99%   |
| Sony                | 24        | 0.82%   |
| Google              | 24        | 0.82%   |
| Fujitsu             | 24        | 0.82%   |
| Microsoft           | 20        | 0.68%   |
| Packard Bell        | 18        | 0.61%   |
| Biostar             | 17        | 0.58%   |
| Foxconn             | 15        | 0.51%   |
| Positivo            | 14        | 0.48%   |
| HUAWEI              | 14        | 0.48%   |
| Pegatron            | 11        | 0.37%   |
| Alienware           | 11        | 0.37%   |
| Medion              | 10        | 0.34%   |
| Chuwi               | 9         | 0.31%   |
| Notebook            | 8         | 0.27%   |
| AZW                 | 7         | 0.24%   |
| Multilaser          | 6         | 0.2%    |
| GPU Company         | 6         | 0.2%    |
| Gateway             | 6         | 0.2%    |
| AMI                 | 6         | 0.2%    |
| Fujitsu Siemens     | 5         | 0.17%   |
| BESSTAR Tech        | 5         | 0.17%   |
| Thomson             | 4         | 0.14%   |
| Razer               | 4         | 0.14%   |
| OEM                 | 4         | 0.14%   |
| LG Electronics      | 4         | 0.14%   |
| Jumper              | 4         | 0.14%   |
| Framework           | 4         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 39        | 1.33%   |
| ASUS All Series            | 28        | 0.95%   |
| HP Notebook                | 20        | 0.68%   |
| HP Pavilion Notebook       | 13        | 0.44%   |
| Dell OptiPlex 7010         | 9         | 0.31%   |
| HP 15                      | 8         | 0.27%   |
| Dell OptiPlex 790          | 8         | 0.27%   |
| MSI MS-7817                | 7         | 0.24%   |
| HP Pavilion dv6            | 7         | 0.24%   |
| HP Pavilion 15             | 7         | 0.24%   |
| Dell OptiPlex 780          | 7         | 0.24%   |
| Apple MacBookPro8,1        | 7         | 0.24%   |
| Apple iMac12,2             | 7         | 0.24%   |
| MSI MS-7C02                | 6         | 0.2%    |
| Microsoft Surface Pro      | 6         | 0.2%    |
| HP Pavilion dv7            | 6         | 0.2%    |
| Dell OptiPlex 380          | 6         | 0.2%    |
| Dell Latitude E6540        | 6         | 0.2%    |
| ASUS M5A78L-M/USB3         | 6         | 0.2%    |
| Apple iMac12,1             | 6         | 0.2%    |
| Apple iMac10,1             | 6         | 0.2%    |
| Microsoft Surface Pro 4    | 5         | 0.17%   |
| Lenovo MIIX 320-10ICR 80XF | 5         | 0.17%   |
| HP ProBook 640 G1          | 5         | 0.17%   |
| GPU Company GWTC116-2      | 5         | 0.17%   |
| Gigabyte A320M-S2H         | 5         | 0.17%   |
| Dell OptiPlex 990          | 5         | 0.17%   |
| Dell OptiPlex 3010         | 5         | 0.17%   |
| Dell Inspiron 15-3567      | 5         | 0.17%   |
| ASUS M5A97 R2.0            | 5         | 0.17%   |
| Toshiba Satellite C660     | 4         | 0.14%   |
| Toshiba Satellite C55-C    | 4         | 0.14%   |
| Intel H61                  | 4         | 0.14%   |
| HP ProDesk 600 G1 SFF      | 4         | 0.14%   |
| HP Pavilion g6             | 4         | 0.14%   |
| HP Laptop 15-bw0xx         | 4         | 0.14%   |
| HP EliteBook 840 G1        | 4         | 0.14%   |
| HP Compaq Pro 6300 SFF     | 4         | 0.14%   |
| Gigabyte X570 AORUS ELITE  | 4         | 0.14%   |
| Gigabyte B450 AORUS M      | 4         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 114       | 3.89%   |
| Dell Inspiron         | 108       | 3.68%   |
| HP Pavilion           | 100       | 3.41%   |
| Dell Latitude         | 100       | 3.41%   |
| Acer Aspire           | 100       | 3.41%   |
| Lenovo IdeaPad        | 93        | 3.17%   |
| Dell OptiPlex         | 72        | 2.45%   |
| Toshiba Satellite     | 57        | 1.94%   |
| HP EliteBook          | 50        | 1.7%    |
| ASUS ROG              | 44        | 1.5%    |
| HP Compaq             | 42        | 1.43%   |
| HP ProBook            | 40        | 1.36%   |
| ASUS PRIME            | 40        | 1.36%   |
| Unknown               | 39        | 1.33%   |
| HP Laptop             | 33        | 1.12%   |
| Lenovo ThinkCentre    | 32        | 1.09%   |
| ASUS VivoBook         | 32        | 1.09%   |
| ASUS TUF              | 29        | 0.99%   |
| ASUS All              | 28        | 0.95%   |
| HP ENVY               | 27        | 0.92%   |
| Dell XPS              | 26        | 0.89%   |
| Dell Precision        | 26        | 0.89%   |
| Lenovo Yoga           | 25        | 0.85%   |
| Dell Vostro           | 25        | 0.85%   |
| Microsoft Surface     | 20        | 0.68%   |
| HP Notebook           | 20        | 0.68%   |
| HP Stream             | 15        | 0.51%   |
| HP EliteDesk          | 15        | 0.51%   |
| Packard Bell EasyNote | 14        | 0.48%   |
| Apple iMac12          | 13        | 0.44%   |
| ASUS ZenBook          | 12        | 0.41%   |
| ASUS ASUS             | 12        | 0.41%   |
| HP OMEN               | 11        | 0.37%   |
| Gigabyte B450         | 11        | 0.37%   |
| Fujitsu ESPRIMO       | 11        | 0.37%   |
| Dell Studio           | 11        | 0.37%   |
| HP ProDesk            | 10        | 0.34%   |
| HP 15                 | 10        | 0.34%   |
| Lenovo MIIX           | 9         | 0.31%   |
| Gigabyte X570         | 9         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 262       | 8.93%   |
| 2021    | 257       | 8.76%   |
| 2011    | 252       | 8.59%   |
| 2013    | 245       | 8.35%   |
| 2018    | 231       | 7.87%   |
| 2020    | 219       | 7.46%   |
| 2019    | 212       | 7.23%   |
| 2014    | 195       | 6.65%   |
| 2017    | 174       | 5.93%   |
| 2010    | 171       | 5.83%   |
| 2016    | 160       | 5.45%   |
| 2015    | 147       | 5.01%   |
| 2008    | 127       | 4.33%   |
| 2009    | 105       | 3.58%   |
| 2022    | 74        | 2.52%   |
| 2007    | 71        | 2.42%   |
| 2006    | 17        | 0.58%   |
| 2023    | 7         | 0.24%   |
| 2005    | 5         | 0.17%   |
| Unknown | 3         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 1603      | 54.64%  |
| Desktop     | 1074      | 36.61%  |
| Convertible | 77        | 2.62%   |
| All in one  | 73        | 2.49%   |
| Tablet      | 53        | 1.81%   |
| Mini pc     | 48        | 1.64%   |
| Server      | 6         | 0.2%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2592      | 87.54%  |
| Enabled  | 369       | 12.46%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2906      | 99.05%  |
| Yes  | 28        | 0.95%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 793       | 26.84%  |
| 3.01-4.0        | 656       | 22.2%   |
| 8.01-16.0       | 504       | 17.06%  |
| 16.01-24.0      | 499       | 16.89%  |
| 32.01-64.0      | 234       | 7.92%   |
| 1.01-2.0        | 142       | 4.81%   |
| 64.01-256.0     | 51        | 1.73%   |
| 2.01-3.0        | 38        | 1.29%   |
| 24.01-32.0      | 32        | 1.08%   |
| 0.51-1.0        | 5         | 0.17%   |
| More than 256.0 | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1242      | 39.03%  |
| 2.01-3.0   | 1035      | 32.53%  |
| 3.01-4.0   | 427       | 13.42%  |
| 4.01-8.0   | 355       | 11.16%  |
| 0.51-1.0   | 55        | 1.73%   |
| 8.01-16.0  | 53        | 1.67%   |
| 16.01-24.0 | 8         | 0.25%   |
| 24.01-32.0 | 4         | 0.13%   |
| 32.01-64.0 | 2         | 0.06%   |
| 0.01-0.5   | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1897      | 63.32%  |
| 2      | 729       | 24.33%  |
| 3      | 175       | 5.84%   |
| 4      | 87        | 2.9%    |
| 5      | 44        | 1.47%   |
| 6      | 28        | 0.93%   |
| 0      | 14        | 0.47%   |
| 7      | 11        | 0.37%   |
| 8      | 8         | 0.27%   |
| 51     | 1         | 0.03%   |
| 30     | 1         | 0.03%   |
| 11     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1668      | 56.6%   |
| Yes       | 1279      | 43.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2447      | 83.23%  |
| No        | 493       | 16.77%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2339      | 79.45%  |
| No        | 605       | 20.55%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1731      | 58.46%  |
| No        | 1230      | 41.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 704       | 23.92%  |
| Germany      | 302       | 10.26%  |
| Brazil       | 190       | 6.46%   |
| UK           | 187       | 6.35%   |
| Canada       | 101       | 3.43%   |
| Italy        | 98        | 3.33%   |
| Spain        | 94        | 3.19%   |
| France       | 91        | 3.09%   |
| Netherlands  | 83        | 2.82%   |
| India        | 83        | 2.82%   |
| Poland       | 67        | 2.28%   |
| Australia    | 64        | 2.17%   |
| Mexico       | 52        | 1.77%   |
| Russia       | 41        | 1.39%   |
| Belgium      | 39        | 1.33%   |
| South Africa | 33        | 1.12%   |
| Portugal     | 32        | 1.09%   |
| Sweden       | 30        | 1.02%   |
| Switzerland  | 29        | 0.99%   |
| Czechia      | 29        | 0.99%   |
| Austria      | 29        | 0.99%   |
| Argentina    | 28        | 0.95%   |
| Turkey       | 26        | 0.88%   |
| Hungary      | 26        | 0.88%   |
| Norway       | 25        | 0.85%   |
| Romania      | 23        | 0.78%   |
| Greece       | 22        | 0.75%   |
| New Zealand  | 18        | 0.61%   |
| Japan        | 18        | 0.61%   |
| Egypt        | 18        | 0.61%   |
| Chile        | 18        | 0.61%   |
| Finland      | 16        | 0.54%   |
| Denmark      | 16        | 0.54%   |
| Colombia     | 15        | 0.51%   |
| Indonesia    | 14        | 0.48%   |
| Serbia       | 11        | 0.37%   |
| Malaysia     | 11        | 0.37%   |
| Bulgaria     | 11        | 0.37%   |
| Venezuela    | 10        | 0.34%   |
| Slovenia     | 9         | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 28        | 0.92%   |
| Munich            | 23        | 0.75%   |
| Athens            | 20        | 0.66%   |
| Sydney            | 17        | 0.56%   |
| Madrid            | 17        | 0.56%   |
| Vienna            | 15        | 0.49%   |
| Sao Paulo         | 15        | 0.49%   |
| Rome              | 15        | 0.49%   |
| New York          | 15        | 0.49%   |
| Hamburg           | 14        | 0.46%   |
| Rio de Janeiro    | 13        | 0.43%   |
| Montreal          | 13        | 0.43%   |
| London            | 13        | 0.43%   |
| Dallas            | 12        | 0.39%   |
| Amsterdam         | 11        | 0.36%   |
| Salt Lake City    | 10        | 0.33%   |
| Milan             | 10        | 0.33%   |
| Melbourne         | 10        | 0.33%   |
| Bengaluru         | 10        | 0.33%   |
| Phoenix           | 9         | 0.29%   |
| Perth             | 9         | 0.29%   |
| Paris             | 9         | 0.29%   |
| Johannesburg      | 9         | 0.29%   |
| Istanbul          | 9         | 0.29%   |
| Frankfurt am Main | 9         | 0.29%   |
| Denver            | 9         | 0.29%   |
| Brisbane          | 9         | 0.29%   |
| Valencia          | 8         | 0.26%   |
| Toronto           | 8         | 0.26%   |
| Stuttgart         | 8         | 0.26%   |
| Seattle           | 8         | 0.26%   |
| Prague            | 8         | 0.26%   |
| Moscow            | 8         | 0.26%   |
| Mexico City       | 8         | 0.26%   |
| Jakarta           | 8         | 0.26%   |
| Helsinki          | 8         | 0.26%   |
| Glasgow           | 8         | 0.26%   |
| Diepoldsau        | 8         | 0.26%   |
| Delhi             | 8         | 0.26%   |
| Cape Town         | 8         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 641       | 915    | 15.4%   |
| Samsung Electronics       | 568       | 809    | 13.64%  |
| WDC                       | 539       | 725    | 12.95%  |
| Toshiba                   | 298       | 380    | 7.16%   |
| Sandisk                   | 256       | 297    | 6.15%   |
| Unknown                   | 244       | 338    | 5.86%   |
| Kingston                  | 226       | 302    | 5.43%   |
| Crucial                   | 157       | 189    | 3.77%   |
| Hitachi                   | 131       | 176    | 3.15%   |
| Intel                     | 87        | 116    | 2.09%   |
| SK hynix                  | 75        | 88     | 1.8%    |
| HGST                      | 70        | 87     | 1.68%   |
| A-DATA Technology         | 58        | 70     | 1.39%   |
| Micron Technology         | 52        | 62     | 1.25%   |
| China                     | 48        | 56     | 1.15%   |
| Apple                     | 39        | 44     | 0.94%   |
| Intenso                   | 34        | 37     | 0.82%   |
| Silicon Motion            | 33        | 41     | 0.79%   |
| Phison                    | 29        | 33     | 0.7%    |
| PNY                       | 26        | 33     | 0.62%   |
| KIOXIA                    | 24        | 26     | 0.58%   |
| Patriot                   | 23        | 28     | 0.55%   |
| SPCC                      | 22        | 26     | 0.53%   |
| Netac                     | 21        | 24     | 0.5%    |
| JMicron Technology        | 20        | 24     | 0.48%   |
| Unknown                   | 20        | 22     | 0.48%   |
| OCZ                       | 16        | 19     | 0.38%   |
| GOODRAM                   | 16        | 17     | 0.38%   |
| Micron/Crucial Technology | 14        | 16     | 0.34%   |
| LITEON                    | 14        | 16     | 0.34%   |
| Lexar                     | 14        | 14     | 0.34%   |
| Team                      | 12        | 15     | 0.29%   |
| Transcend                 | 11        | 28     | 0.26%   |
| Realtek Semiconductor     | 11        | 12     | 0.26%   |
| Phison Electronics        | 11        | 12     | 0.26%   |
| Maxtor                    | 11        | 15     | 0.26%   |
| LITEONIT                  | 11        | 13     | 0.26%   |
| KingSpec                  | 11        | 13     | 0.26%   |
| Hewlett-Packard           | 11        | 15     | 0.26%   |
| Gigabyte Technology       | 10        | 12     | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                            | 77        | 1.68%   |
| Unknown MMC Card  64GB                            | 70        | 1.53%   |
| Kingston SA400S37240G 240GB SSD                   | 51        | 1.11%   |
| Seagate ST500DM002-1BD142 500GB                   | 43        | 0.94%   |
| Seagate ST1000LM035-1RK172 970GB                  | 37        | 0.81%   |
| Samsung SSD 860 EVO 500GB                         | 35        | 0.76%   |
| Crucial CT240BX500SSD1 240GB                      | 33        | 0.72%   |
| Unknown MMC Card  128GB                           | 32        | 0.7%    |
| Toshiba MQ01ABD100 1TB                            | 32        | 0.7%    |
| Kingston SA400S37480G 480GB SSD                   | 30        | 0.65%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 28        | 0.61%   |
| Kingston SA400S37120G 120GB SSD                   | 28        | 0.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 27        | 0.59%   |
| Toshiba MQ01ABF050 500GB                          | 26        | 0.57%   |
| Seagate ST1000DM010-2EP102 1TB                    | 26        | 0.57%   |
| Samsung NVMe SSD Drive 256GB                      | 26        | 0.57%   |
| Unknown SD/MMC/MS PRO 249GB                       | 25        | 0.55%   |
| Toshiba MQ04ABF100 1TB                            | 25        | 0.55%   |
| Samsung NVMe SSD Drive 512GB                      | 25        | 0.55%   |
| Samsung NVMe SSD Drive 1TB                        | 25        | 0.55%   |
| Samsung SSD 850 EVO 500GB                         | 23        | 0.5%    |
| Samsung SSD 850 EVO 250GB                         | 23        | 0.5%    |
| Seagate ST500LT012-1DG142 500GB                   | 22        | 0.48%   |
| Crucial CT500MX500SSD1 500GB                      | 22        | 0.48%   |
| SanDisk NVMe SSD Drive 256GB                      | 21        | 0.46%   |
| Samsung NVMe SSD Drive 500GB                      | 21        | 0.46%   |
| Unknown                                           | 20        | 0.44%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 18        | 0.39%   |
| Seagate ST9500325AS 500GB                         | 18        | 0.39%   |
| Seagate Expansion 4TB                             | 18        | 0.39%   |
| Samsung SSD 870 EVO 1TB                           | 18        | 0.39%   |
| Unknown MMC Card  16GB                            | 17        | 0.37%   |
| Kingston SV300S37A120G 120GB SSD                  | 17        | 0.37%   |
| Crucial CT1000MX500SSD1 1TB                       | 17        | 0.37%   |
| Seagate ST3500418AS 500GB                         | 16        | 0.35%   |
| SanDisk NVMe SSD Drive 1TB                        | 16        | 0.35%   |
| Samsung SSD 860 EVO 250GB                         | 16        | 0.35%   |
| HGST HTS721010A9E630 1TB                          | 16        | 0.35%   |
| Toshiba HDWD110 1TB                               | 15        | 0.33%   |
| Toshiba DT01ACA100 1TB                            | 15        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 634       | 895    | 37.32%  |
| WDC                 | 464       | 615    | 27.31%  |
| Toshiba             | 236       | 307    | 13.89%  |
| Hitachi             | 131       | 176    | 7.71%   |
| HGST                | 70        | 87     | 4.12%   |
| Samsung Electronics | 69        | 87     | 4.06%   |
| Unknown             | 25        | 32     | 1.47%   |
| Apple               | 20        | 22     | 1.18%   |
| JMicron Technology  | 14        | 16     | 0.82%   |
| Maxtor              | 11        | 15     | 0.65%   |
| Fujitsu             | 8         | 9      | 0.47%   |
| USB3.0              | 3         | 4      | 0.18%   |
| Super Talent        | 3         | 4      | 0.18%   |
| Hewlett-Packard     | 3         | 6      | 0.18%   |
| T-CREATE            | 2         | 2      | 0.12%   |
| Intenso             | 2         | 2      | 0.12%   |
| SABRENT             | 1         | 1      | 0.06%   |
| QUANTUM             | 1         | 1      | 0.06%   |
| KESU                | 1         | 1      | 0.06%   |
| ACASIS              | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 296       | 405    | 20.76%  |
| Kingston            | 186       | 242    | 13.04%  |
| Crucial             | 150       | 180    | 10.52%  |
| SanDisk             | 146       | 169    | 10.24%  |
| WDC                 | 63        | 79     | 4.42%   |
| A-DATA Technology   | 52        | 64     | 3.65%   |
| China               | 47        | 55     | 3.3%    |
| Toshiba             | 32        | 37     | 2.24%   |
| Intel               | 31        | 38     | 2.17%   |
| PNY                 | 26        | 33     | 1.82%   |
| Micron Technology   | 24        | 28     | 1.68%   |
| SK hynix            | 23        | 23     | 1.61%   |
| Patriot             | 22        | 27     | 1.54%   |
| Intenso             | 22        | 24     | 1.54%   |
| SPCC                | 21        | 25     | 1.47%   |
| Netac               | 21        | 23     | 1.47%   |
| OCZ                 | 15        | 18     | 1.05%   |
| GOODRAM             | 15        | 16     | 1.05%   |
| Apple               | 15        | 16     | 1.05%   |
| LITEON              | 14        | 16     | 0.98%   |
| Lexar               | 13        | 13     | 0.91%   |
| Team                | 12        | 15     | 0.84%   |
| Transcend           | 11        | 28     | 0.77%   |
| LITEONIT            | 11        | 13     | 0.77%   |
| KingSpec            | 10        | 12     | 0.7%    |
| Unknown             | 9         | 11     | 0.63%   |
| Hewlett-Packard     | 8         | 9      | 0.56%   |
| Gigabyte Technology | 8         | 9      | 0.56%   |
| Apacer              | 8         | 9      | 0.56%   |
| Leven               | 6         | 7      | 0.42%   |
| Plextor             | 4         | 5      | 0.28%   |
| Mushkin             | 4         | 4      | 0.28%   |
| FORESEE             | 4         | 4      | 0.28%   |
| ASMT                | 4         | 4      | 0.28%   |
| Teclast             | 3         | 3      | 0.21%   |
| Seagate             | 3         | 5      | 0.21%   |
| OWC                 | 3         | 3      | 0.21%   |
| KIOXIA-EXCERIA      | 3         | 7      | 0.21%   |
| Drevo               | 3         | 4      | 0.21%   |
| Corsair             | 3         | 8      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1454      | 2283   | 38.47%  |
| SSD     | 1279      | 1786   | 33.84%  |
| NVMe    | 727       | 974    | 19.23%  |
| MMC     | 229       | 306    | 6.06%   |
| Unknown | 91        | 115    | 2.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2308      | 3941   | 67.23%  |
| NVMe | 723       | 963    | 21.06%  |
| MMC  | 229       | 306    | 6.67%   |
| SAS  | 173       | 254    | 5.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1719      | 2467   | 60.79%  |
| 0.51-1.0   | 776       | 1071   | 27.44%  |
| 1.01-2.0   | 193       | 269    | 6.82%   |
| 3.01-4.0   | 64        | 130    | 2.26%   |
| 4.01-10.0  | 40        | 58     | 1.41%   |
| 2.01-3.0   | 27        | 51     | 0.95%   |
| 10.01-20.0 | 9         | 23     | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 966       | 31.85%  |
| 251-500        | 752       | 24.79%  |
| 501-1000       | 453       | 14.94%  |
| 51-100         | 258       | 8.51%   |
| 1001-2000      | 176       | 5.8%    |
| 21-50          | 150       | 4.95%   |
| More than 3000 | 107       | 3.53%   |
| 1-20           | 73        | 2.41%   |
| 2001-3000      | 59        | 1.95%   |
| Unknown        | 39        | 1.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1222      | 38.65%  |
| 21-50          | 862       | 27.26%  |
| 51-100         | 383       | 12.11%  |
| 101-250        | 299       | 9.46%   |
| 251-500        | 158       | 5%      |
| 501-1000       | 96        | 3.04%   |
| More than 3000 | 50        | 1.58%   |
| 1001-2000      | 39        | 1.23%   |
| Unknown        | 39        | 1.23%   |
| 2001-3000      | 14        | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                   | 3         | 3      | 3.41%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 3.41%   |
| Toshiba MQ02ABD100H 1TB                  | 2         | 2      | 2.27%   |
| Seagate ST9500420AS 500GB                | 2         | 2      | 2.27%   |
| Kingston SUV400S37240G 240GB SSD         | 2         | 2      | 2.27%   |
| WDC WD6400BEVT-22A0RT0 640GB             | 1         | 1      | 1.14%   |
| WDC WD5000LPVX-75V0TT0 500GB             | 1         | 1      | 1.14%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1         | 1      | 1.14%   |
| WDC WD5000BEVT-24A0RT0 500GB             | 1         | 1      | 1.14%   |
| WDC WD3200AAKS-22B3A0 320GB              | 1         | 1      | 1.14%   |
| WDC WD3200AAJS-00L7A0 320GB              | 1         | 1      | 1.14%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 1         | 1      | 1.14%   |
| WDC WD1200BEVS-60UST0 120GB              | 1         | 1      | 1.14%   |
| WDC WD10SPZX-75Z10T2 1TB                 | 1         | 1      | 1.14%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1      | 1.14%   |
| WDC WD10JPVT-55A1YT0 1TB                 | 1         | 1      | 1.14%   |
| WDC WD10EZEX-21M2NA0 1TB                 | 1         | 2      | 1.14%   |
| WDC WD10EURX-63FH1Y0 1TB                 | 1         | 1      | 1.14%   |
| WDC WD Green 2.5 1000GB SSD              | 1         | 1      | 1.14%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 1.14%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 1         | 1      | 1.14%   |
| Toshiba MQ01ABF050 500GB                 | 1         | 1      | 1.14%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1      | 1.14%   |
| Toshiba MK8046GSX 80GB                   | 1         | 1      | 1.14%   |
| Toshiba MK3265GSX 320GB                  | 1         | 1      | 1.14%   |
| Toshiba MG03ACA200 2TB                   | 1         | 1      | 1.14%   |
| Toshiba DT01ACA100 1TB                   | 1         | 1      | 1.14%   |
| Teclast 128GB NS550-2242 SSD             | 1         | 1      | 1.14%   |
| SK hynix BC711 HFM512GD3JX013N 512GB     | 1         | 1      | 1.14%   |
| Silicon Motion Inland NVMe SSD 256GB     | 1         | 1      | 1.14%   |
| Seagate ST9500325AS 500GB                | 1         | 1      | 1.14%   |
| Seagate ST9320310AS 320GB                | 1         | 1      | 1.14%   |
| Seagate ST9250315AS 250GB                | 1         | 1      | 1.14%   |
| Seagate ST9200420ASG 200GB               | 1         | 1      | 1.14%   |
| Seagate ST9160411ASG 160GB               | 1         | 1      | 1.14%   |
| Seagate ST8000DM004-2CX188 8TB           | 1         | 1      | 1.14%   |
| Seagate ST500LT012-9WS142 500GB          | 1         | 1      | 1.14%   |
| Seagate ST500LT012-1DG142 500GB          | 1         | 1      | 1.14%   |
| Seagate ST500LM000-SSHD-8GB              | 1         | 1      | 1.14%   |
| Seagate ST500DM002-1BD142 500GB          | 1         | 1      | 1.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 30     | 33.33%  |
| WDC                 | 14        | 15     | 16.09%  |
| Toshiba             | 13        | 13     | 14.94%  |
| HGST                | 7         | 7      | 8.05%   |
| Kingston            | 6         | 6      | 6.9%    |
| Samsung Electronics | 4         | 4      | 4.6%    |
| Hitachi             | 3         | 3      | 3.45%   |
| A-DATA Technology   | 2         | 2      | 2.3%    |
| Teclast             | 1         | 1      | 1.15%   |
| SK hynix            | 1         | 1      | 1.15%   |
| Silicon Motion      | 1         | 1      | 1.15%   |
| OCZ                 | 1         | 1      | 1.15%   |
| Maxtor              | 1         | 1      | 1.15%   |
| LITEONIT            | 1         | 1      | 1.15%   |
| Intel               | 1         | 1      | 1.15%   |
| Hewlett-Packard     | 1         | 1      | 1.15%   |
| Drevo               | 1         | 1      | 1.15%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 30     | 43.94%  |
| WDC                 | 13        | 14     | 19.7%   |
| Toshiba             | 11        | 11     | 16.67%  |
| HGST                | 7         | 7      | 10.61%  |
| Hitachi             | 3         | 3      | 4.55%   |
| Samsung Electronics | 2         | 2      | 3.03%   |
| Maxtor              | 1         | 1      | 1.52%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 62        | 68     | 74.7%   |
| SSD  | 18        | 18     | 21.69%  |
| NVMe | 3         | 3      | 3.61%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2601      | 4802   | 85.84%  |
| Works    | 345       | 571    | 11.39%  |
| Malfunc  | 82        | 89     | 2.71%   |
| Failed   | 2         | 2      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2004      | 57.7%   |
| AMD                              | 565       | 16.27%  |
| Samsung Electronics              | 254       | 7.31%   |
| SanDisk                          | 120       | 3.46%   |
| Kingston Technology Company      | 51        | 1.47%   |
| Nvidia                           | 50        | 1.44%   |
| SK hynix                         | 49        | 1.41%   |
| ASMedia Technology               | 46        | 1.32%   |
| Phison Electronics               | 44        | 1.27%   |
| Silicon Motion                   | 36        | 1.04%   |
| Toshiba America Info Systems     | 30        | 0.86%   |
| Micron Technology                | 29        | 0.84%   |
| JMicron Technology               | 28        | 0.81%   |
| Marvell Technology Group         | 26        | 0.75%   |
| KIOXIA                           | 26        | 0.75%   |
| Micron/Crucial Technology        | 21        | 0.6%    |
| ADATA Technology                 | 18        | 0.52%   |
| Realtek Semiconductor            | 12        | 0.35%   |
| VIA Technologies                 | 8         | 0.23%   |
| Silicon Image                    | 8         | 0.23%   |
| Seagate Technology               | 6         | 0.17%   |
| Lite-On Technology               | 6         | 0.17%   |
| Union Memory (Shenzhen)          | 5         | 0.14%   |
| Broadcom / LSI                   | 4         | 0.12%   |
| Solid State Storage Technology   | 3         | 0.09%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.09%   |
| Apple                            | 3         | 0.09%   |
| Yangtze Memory Technologies      | 2         | 0.06%   |
| Silicon Integrated Systems [SiS] | 2         | 0.06%   |
| OCZ Technology Group             | 2         | 0.06%   |
| LSI Logic / Symbios Logic        | 2         | 0.06%   |
| INNOGRIT                         | 2         | 0.06%   |
| TenaFe                           | 1         | 0.03%   |
| Netac Technology                 | 1         | 0.03%   |
| Lenovo                           | 1         | 0.03%   |
| HighPoint Technologies           | 1         | 0.03%   |
| Dell                             | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |
| Beijing Starblaze Technology     | 1         | 0.03%   |
| Adaptec                          | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 379       | 9.42%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 161       | 4%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 150       | 3.73%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 134       | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 111       | 2.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 106       | 2.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 105       | 2.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 82        | 2.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 81        | 2.01%   |
| AMD 400 Series Chipset SATA Controller                                                  | 71        | 1.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 68        | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 68        | 1.69%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 65        | 1.62%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 64        | 1.59%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 63        | 1.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 61        | 1.52%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 60        | 1.49%   |
| Samsung NVMe SSD Controller 980                                                         | 56        | 1.39%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 56        | 1.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 55        | 1.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 52        | 1.29%   |
| Intel SATA Controller [RAID mode]                                                       | 51        | 1.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 49        | 1.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 45        | 1.12%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 44        | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 44        | 1.09%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 42        | 1.04%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 41        | 1.02%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 40        | 0.99%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 38        | 0.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 37        | 0.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 34        | 0.84%   |
| AMD 500 Series Chipset SATA Controller                                                  | 34        | 0.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 32        | 0.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 32        | 0.8%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 29        | 0.72%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 29        | 0.72%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 28        | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 28        | 0.7%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 27        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2196      | 61.08%  |
| NVMe | 723       | 20.11%  |
| IDE  | 410       | 11.4%   |
| RAID | 257       | 7.15%   |
| SAS  | 6         | 0.17%   |
| SCSI | 3         | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 2286      | 77.91%  |
| AMD    | 648       | 22.09%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 45        | 1.53%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 35        | 1.19%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 28        | 0.95%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 26        | 0.89%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 25        | 0.85%   |
| AMD Ryzen 5 3600 6-Core Processor             | 25        | 0.85%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 24        | 0.82%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 22        | 0.75%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 20        | 0.68%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 19        | 0.65%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 19        | 0.65%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 18        | 0.61%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 18        | 0.61%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 18        | 0.61%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 18        | 0.61%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 18        | 0.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 17        | 0.58%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 16        | 0.54%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 16        | 0.54%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 15        | 0.51%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 15        | 0.51%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 14        | 0.48%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 14        | 0.48%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 14        | 0.48%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 14        | 0.48%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 14        | 0.48%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 14        | 0.48%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 13        | 0.44%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 13        | 0.44%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 13        | 0.44%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 13        | 0.44%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 13        | 0.44%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 13        | 0.44%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 13        | 0.44%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 12        | 0.41%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 12        | 0.41%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 12        | 0.41%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 12        | 0.41%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 11        | 0.37%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 689       | 23.47%  |
| Intel Core i7           | 411       | 14%     |
| Intel Core i3           | 281       | 9.57%   |
| Intel Celeron           | 194       | 6.61%   |
| AMD Ryzen 5             | 156       | 5.31%   |
| Intel Core 2 Duo        | 153       | 5.21%   |
| Other                   | 149       | 5.07%   |
| Intel Atom              | 95        | 3.24%   |
| AMD Ryzen 7             | 95        | 3.24%   |
| Intel Pentium           | 89        | 3.03%   |
| Intel Xeon              | 65        | 2.21%   |
| AMD FX                  | 49        | 1.67%   |
| AMD Ryzen 9             | 39        | 1.33%   |
| Intel Pentium Dual-Core | 37        | 1.26%   |
| AMD A6                  | 37        | 1.26%   |
| AMD A10                 | 29        | 0.99%   |
| Intel Core 2 Quad       | 28        | 0.95%   |
| AMD A8                  | 28        | 0.95%   |
| AMD A4                  | 28        | 0.95%   |
| AMD Ryzen 3             | 26        | 0.89%   |
| Intel Pentium Dual      | 25        | 0.85%   |
| Intel Core 2            | 17        | 0.58%   |
| AMD E1                  | 15        | 0.51%   |
| AMD Athlon II X2        | 15        | 0.51%   |
| Intel Core i9           | 13        | 0.44%   |
| AMD Phenom II X4        | 12        | 0.41%   |
| Intel Pentium Silver    | 11        | 0.37%   |
| AMD Athlon              | 10        | 0.34%   |
| Intel Pentium Gold      | 9         | 0.31%   |
| AMD E                   | 9         | 0.31%   |
| AMD Athlon 64 X2        | 9         | 0.31%   |
| Intel Core M            | 8         | 0.27%   |
| AMD Phenom II X6        | 8         | 0.27%   |
| AMD Turion 64 X2 Mobile | 7         | 0.24%   |
| AMD Athlon II X4        | 7         | 0.24%   |
| Intel Pentium 4         | 6         | 0.2%    |
| AMD E2                  | 5         | 0.17%   |
| AMD Athlon II           | 5         | 0.17%   |
| Intel Core m5           | 4         | 0.14%   |
| AMD Ryzen 7 PRO         | 4         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1381      | 47.02%  |
| 4      | 1051      | 35.78%  |
| 6      | 232       | 7.9%    |
| 8      | 150       | 5.11%   |
| 1      | 38        | 1.29%   |
| 12     | 26        | 0.89%   |
| 3      | 20        | 0.68%   |
| 16     | 16        | 0.54%   |
| 10     | 16        | 0.54%   |
| 14     | 5         | 0.17%   |
| 40     | 1         | 0.03%   |
| 28     | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 2922      | 99.59%  |
| 2      | 12        | 0.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1765      | 60.14%  |
| 1      | 1170      | 39.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2934      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 235       | 7.89%   |
| 0x306a9    | 231       | 7.75%   |
| Unknown    | 212       | 7.11%   |
| 0x306c3    | 167       | 5.6%    |
| 0x1067a    | 143       | 4.8%    |
| 0x40651    | 91        | 3.05%   |
| 0x806c1    | 82        | 2.75%   |
| 0x20655    | 77        | 2.58%   |
| 0x806e9    | 71        | 2.38%   |
| 0x406e3    | 68        | 2.28%   |
| 0x406c4    | 68        | 2.28%   |
| 0x30678    | 67        | 2.25%   |
| 0x306d4    | 65        | 2.18%   |
| 0x506e3    | 58        | 1.95%   |
| 0x906ea    | 56        | 1.88%   |
| 0x806ea    | 56        | 1.88%   |
| 0x806ec    | 49        | 1.64%   |
| 0x08701021 | 47        | 1.58%   |
| 0x6fd      | 46        | 1.54%   |
| 0x906e9    | 45        | 1.51%   |
| 0x706a8    | 39        | 1.31%   |
| 0x06000852 | 34        | 1.14%   |
| 0x20652    | 32        | 1.07%   |
| 0x10676    | 32        | 1.07%   |
| 0x506c9    | 31        | 1.04%   |
| 0x08108109 | 30        | 1.01%   |
| 0x706e5    | 29        | 0.97%   |
| 0x6fb      | 28        | 0.94%   |
| 0x406c3    | 26        | 0.87%   |
| 0x0a50000c | 26        | 0.87%   |
| 0x010000c8 | 25        | 0.84%   |
| 0x07030105 | 24        | 0.81%   |
| 0x06001119 | 23        | 0.77%   |
| 0x08600106 | 20        | 0.67%   |
| 0x0800820d | 20        | 0.67%   |
| 0x06006705 | 20        | 0.67%   |
| 0xa0653    | 19        | 0.64%   |
| 0x0700010f | 19        | 0.64%   |
| 0x0a201016 | 18        | 0.6%    |
| 0x08108102 | 18        | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 344       | 11.72%  |
| Haswell          | 286       | 9.74%   |
| SandyBridge      | 255       | 8.69%   |
| IvyBridge        | 245       | 8.35%   |
| Penryn           | 180       | 6.13%   |
| Silvermont       | 171       | 5.83%   |
| Skylake          | 134       | 4.57%   |
| Westmere         | 118       | 4.02%   |
| Core             | 103       | 3.51%   |
| Zen 2            | 101       | 3.44%   |
| TigerLake        | 93        | 3.17%   |
| Zen 3            | 85        | 2.9%    |
| Zen+             | 74        | 2.52%   |
| Broadwell        | 70        | 2.39%   |
| Piledriver       | 63        | 2.15%   |
| K10              | 61        | 2.08%   |
| CometLake        | 58        | 1.98%   |
| Goldmont plus    | 55        | 1.87%   |
| Excavator        | 52        | 1.77%   |
| Icelake          | 51        | 1.74%   |
| Unknown          | 45        | 1.53%   |
| Zen              | 43        | 1.47%   |
| Puma             | 37        | 1.26%   |
| Goldmont         | 34        | 1.16%   |
| Nehalem          | 31        | 1.06%   |
| Jaguar           | 23        | 0.78%   |
| K8 Hammer        | 21        | 0.72%   |
| Alderlake Hybrid | 18        | 0.61%   |
| Bobcat           | 15        | 0.51%   |
| K10 Llano        | 14        | 0.48%   |
| Bulldozer        | 12        | 0.41%   |
| Tremont          | 11        | 0.37%   |
| Steamroller      | 10        | 0.34%   |
| NetBurst         | 9         | 0.31%   |
| Bonnell          | 9         | 0.31%   |
| K8 & K10 hybrid  | 4         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1776      | 52.84%  |
| Nvidia                           | 814       | 24.22%  |
| AMD                              | 763       | 22.7%   |
| VIA Technologies                 | 3         | 0.09%   |
| Silicon Integrated Systems [SiS] | 2         | 0.06%   |
| Matrox Electronics Systems       | 2         | 0.06%   |
| ASPEED Technology                | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 194       | 5.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 147       | 4.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 95        | 2.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 92        | 2.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 76        | 2.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 74        | 2.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 73        | 2.12%   |
| Intel HD Graphics 620                                                                    | 63        | 1.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 61        | 1.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 58        | 1.68%   |
| Intel UHD Graphics 620                                                                   | 55        | 1.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 53        | 1.54%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 50        | 1.45%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 48        | 1.39%   |
| Intel HD Graphics 5500                                                                   | 43        | 1.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 41        | 1.19%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 39        | 1.13%   |
| AMD Renoir                                                                               | 39        | 1.13%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 39        | 1.13%   |
| Intel HD Graphics 630                                                                    | 38        | 1.1%    |
| Intel HD Graphics 530                                                                    | 36        | 1.04%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 31        | 0.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 30        | 0.87%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 30        | 0.87%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 30        | 0.87%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 30        | 0.87%   |
| Intel HD Graphics 500                                                                    | 29        | 0.84%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 28        | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 28        | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 28        | 0.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 28        | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 25        | 0.73%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 24        | 0.7%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 24        | 0.7%    |
| AMD Lucienne                                                                             | 24        | 0.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 22        | 0.64%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 20        | 0.58%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 18        | 0.52%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 18        | 0.52%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 18        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1401      | 47.52%  |
| 1 x AMD        | 620       | 21.03%  |
| 1 x Nvidia     | 507       | 17.2%   |
| Intel + Nvidia | 257       | 8.72%   |
| Intel + AMD    | 72        | 2.44%   |
| AMD + Nvidia   | 37        | 1.26%   |
| 2 x AMD        | 36        | 1.22%   |
| 2 x Nvidia     | 5         | 0.17%   |
| Other          | 4         | 0.14%   |
| 1 x VIA        | 3         | 0.1%    |
| 1 x SiS        | 2         | 0.07%   |
| 1 x Matrox     | 2         | 0.07%   |
| 2 x Intel      | 1         | 0.03%   |
| 1 x ASPEED     | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2386      | 80.69%  |
| Proprietary | 484       | 16.37%  |
| Unknown     | 87        | 2.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1740      | 58.23%  |
| 0.01-0.5   | 355       | 11.88%  |
| 1.01-2.0   | 286       | 9.57%   |
| 0.51-1.0   | 254       | 8.5%    |
| 3.01-4.0   | 144       | 4.82%   |
| 7.01-8.0   | 100       | 3.35%   |
| 5.01-6.0   | 48        | 1.61%   |
| 8.01-16.0  | 35        | 1.17%   |
| 2.01-3.0   | 22        | 0.74%   |
| 16.01-24.0 | 4         | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 377       | 12.63%  |
| AU Optronics            | 351       | 11.76%  |
| Chimei Innolux          | 265       | 8.88%   |
| LG Display              | 263       | 8.81%   |
| BOE                     | 244       | 8.17%   |
| Dell                    | 144       | 4.82%   |
| Goldstar                | 132       | 4.42%   |
| Hewlett-Packard         | 104       | 3.48%   |
| Acer                    | 88        | 2.95%   |
| Apple                   | 86        | 2.88%   |
| Philips                 | 69        | 2.31%   |
| AOC                     | 66        | 2.21%   |
| Chi Mei Optoelectronics | 57        | 1.91%   |
| Ancor Communications    | 54        | 1.81%   |
| BenQ                    | 51        | 1.71%   |
| Lenovo                  | 47        | 1.57%   |
| Sharp                   | 39        | 1.31%   |
| LG Electronics          | 28        | 0.94%   |
| Sony                    | 24        | 0.8%    |
| PANDA                   | 24        | 0.8%    |
| LG Philips              | 24        | 0.8%    |
| InfoVision              | 23        | 0.77%   |
| Unknown                 | 22        | 0.74%   |
| ViewSonic               | 21        | 0.7%    |
| Unknown                 | 21        | 0.7%    |
| Vizio                   | 20        | 0.67%   |
| Iiyama                  | 18        | 0.6%    |
| ASUSTek Computer        | 18        | 0.6%    |
| Fujitsu Siemens         | 14        | 0.47%   |
| Sceptre Tech            | 11        | 0.37%   |
| Toshiba                 | 10        | 0.34%   |
| Panasonic               | 10        | 0.34%   |
| HPN                     | 10        | 0.34%   |
| Eizo                    | 10        | 0.34%   |
| CPT                     | 10        | 0.34%   |
| NEC Computers           | 9         | 0.3%    |
| MSI                     | 9         | 0.3%    |
| HannStar                | 8         | 0.27%   |
| LGD                     | 6         | 0.2%    |
| FUS                     | 6         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                  | 22        | 0.72%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 20        | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 15        | 0.49%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 15        | 0.49%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 14        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 13        | 0.42%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 13        | 0.42%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 11        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 11        | 0.36%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 11        | 0.36%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 11        | 0.36%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 10        | 0.33%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 10        | 0.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.33%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 9         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 9         | 0.29%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 9         | 0.29%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch             | 8         | 0.26%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 8         | 0.26%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 8         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 7         | 0.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.23%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 7         | 0.23%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 7         | 0.23%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 7         | 0.23%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 7         | 0.23%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 6         | 0.2%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 6         | 0.2%    |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 6         | 0.2%    |
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                         | 6         | 0.2%    |
| Apple iMac APPA007 2560x1440 597x336mm 27.0-inch                         | 6         | 0.2%    |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch     | 5         | 0.16%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 5         | 0.16%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch    | 5         | 0.16%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 5         | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1079      | 37.13%  |
| 1366x768 (WXGA)    | 747       | 25.71%  |
| 1600x900 (HD+)     | 155       | 5.33%   |
| 3840x2160 (4K)     | 150       | 5.16%   |
| 2560x1440 (QHD)    | 91        | 3.13%   |
| 1280x800 (WXGA)    | 87        | 2.99%   |
| 1680x1050 (WSXGA+) | 82        | 2.82%   |
| 1440x900 (WXGA+)   | 74        | 2.55%   |
| 1280x1024 (SXGA)   | 72        | 2.48%   |
| Unknown            | 56        | 1.93%   |
| 1920x1200 (WUXGA)  | 43        | 1.48%   |
| 1360x768           | 34        | 1.17%   |
| 3440x1440          | 27        | 0.93%   |
| 3840x1080          | 24        | 0.83%   |
| 2560x1600          | 19        | 0.65%   |
| 2560x1080          | 16        | 0.55%   |
| 1920x540           | 16        | 0.55%   |
| 2736x1824          | 14        | 0.48%   |
| 2256x1504          | 9         | 0.31%   |
| 2160x1440          | 9         | 0.31%   |
| 3200x1800 (QHD+)   | 8         | 0.28%   |
| 1024x768 (XGA)     | 8         | 0.28%   |
| 2880x1800          | 6         | 0.21%   |
| 1600x1200          | 6         | 0.21%   |
| 3840x2400          | 5         | 0.17%   |
| 5760x1080          | 4         | 0.14%   |
| 3840x1600          | 4         | 0.14%   |
| 4480x1440          | 3         | 0.1%    |
| 3600x1080          | 3         | 0.1%    |
| 2880x1920          | 3         | 0.1%    |
| 1920x1280          | 3         | 0.1%    |
| 1280x720 (HD)      | 3         | 0.1%    |
| 1024x600           | 3         | 0.1%    |
| 5760x2160          | 2         | 0.07%   |
| 4480x1600          | 2         | 0.07%   |
| 4480x1080          | 2         | 0.07%   |
| 3360x1080          | 2         | 0.07%   |
| 3200x1200          | 2         | 0.07%   |
| 3120x1050          | 2         | 0.07%   |
| 3000x2000          | 2         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 770       | 26.08%  |
| 13      | 277       | 9.38%   |
| Unknown | 243       | 8.23%   |
| 14      | 211       | 7.15%   |
| 17      | 179       | 6.06%   |
| 27      | 165       | 5.59%   |
| 24      | 141       | 4.77%   |
| 21      | 136       | 4.61%   |
| 23      | 135       | 4.57%   |
| 11      | 77        | 2.61%   |
| 19      | 73        | 2.47%   |
| 31      | 68        | 2.3%    |
| 20      | 63        | 2.13%   |
| 12      | 63        | 2.13%   |
| 18      | 62        | 2.1%    |
| 22      | 56        | 1.9%    |
| 34      | 33        | 1.12%   |
| 40      | 20        | 0.68%   |
| 84      | 18        | 0.61%   |
| 54      | 15        | 0.51%   |
| 16      | 15        | 0.51%   |
| 72      | 14        | 0.47%   |
| 32      | 14        | 0.47%   |
| 26      | 11        | 0.37%   |
| 10      | 11        | 0.37%   |
| 25      | 10        | 0.34%   |
| 36      | 7         | 0.24%   |
| 65      | 5         | 0.17%   |
| 52      | 5         | 0.17%   |
| 49      | 5         | 0.17%   |
| 48      | 4         | 0.14%   |
| 47      | 4         | 0.14%   |
| 37      | 4         | 0.14%   |
| 35      | 4         | 0.14%   |
| 29      | 4         | 0.14%   |
| 64      | 3         | 0.1%    |
| 42      | 3         | 0.1%    |
| 33      | 3         | 0.1%    |
| 74      | 2         | 0.07%   |
| 58      | 2         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1130      | 38.84%  |
| 501-600     | 415       | 14.27%  |
| 401-500     | 351       | 12.07%  |
| 201-300     | 291       | 10%     |
| Unknown     | 243       | 8.35%   |
| 351-400     | 209       | 7.18%   |
| 601-700     | 91        | 3.13%   |
| 701-800     | 57        | 1.96%   |
| 1001-1500   | 48        | 1.65%   |
| 1501-2000   | 37        | 1.27%   |
| 801-900     | 30        | 1.03%   |
| 901-1000    | 6         | 0.21%   |
| 101-200     | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2025      | 74.04%  |
| 16/10   | 310       | 11.33%  |
| Unknown | 219       | 8.01%   |
| 5/4     | 63        | 2.3%    |
| 3/2     | 43        | 1.57%   |
| 21/9    | 41        | 1.5%    |
| 4/3     | 21        | 0.77%   |
| 32/9    | 8         | 0.29%   |
| 6/5     | 2         | 0.07%   |
| 3.73    | 2         | 0.07%   |
| 0.62    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 768       | 26.17%  |
| 81-90          | 385       | 13.12%  |
| 201-250        | 374       | 12.74%  |
| Unknown        | 243       | 8.28%   |
| 151-200        | 190       | 6.47%   |
| 301-350        | 169       | 5.76%   |
| 351-500        | 128       | 4.36%   |
| 121-130        | 126       | 4.29%   |
| 71-80          | 110       | 3.75%   |
| 141-150        | 84        | 2.86%   |
| 51-60          | 79        | 2.69%   |
| More than 1000 | 78        | 2.66%   |
| 61-70          | 54        | 1.84%   |
| 251-300        | 54        | 1.84%   |
| 501-1000       | 45        | 1.53%   |
| 131-140        | 18        | 0.61%   |
| 111-120        | 14        | 0.48%   |
| 41-50          | 9         | 0.31%   |
| 91-100         | 6         | 0.2%    |
| 1-40           | 1         | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 883       | 30.82%  |
| 51-100        | 844       | 29.46%  |
| 121-160       | 628       | 21.92%  |
| Unknown       | 243       | 8.48%   |
| 161-240       | 141       | 4.92%   |
| 1-50          | 77        | 2.69%   |
| More than 240 | 49        | 1.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2504      | 84.14%  |
| 2     | 351       | 11.79%  |
| 0     | 91        | 3.06%   |
| 3     | 27        | 0.91%   |
| 4     | 2         | 0.07%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1572      | 35.21%  |
| Intel                             | 1249      | 27.97%  |
| Qualcomm Atheros                  | 563       | 12.61%  |
| Broadcom                          | 330       | 7.39%   |
| Broadcom Limited                  | 94        | 2.11%   |
| Ralink Technology                 | 67        | 1.5%    |
| TP-Link                           | 64        | 1.43%   |
| Marvell Technology Group          | 59        | 1.32%   |
| Ralink                            | 52        | 1.16%   |
| MediaTek                          | 48        | 1.08%   |
| Nvidia                            | 44        | 0.99%   |
| Samsung Electronics               | 30        | 0.67%   |
| ASIX Electronics                  | 22        | 0.49%   |
| NetGear                           | 19        | 0.43%   |
| Xiaomi                            | 17        | 0.38%   |
| Dell                              | 15        | 0.34%   |
| Qualcomm Atheros Communications   | 14        | 0.31%   |
| DisplayLink                       | 14        | 0.31%   |
| Huawei Technologies               | 13        | 0.29%   |
| Microsoft                         | 12        | 0.27%   |
| Hewlett-Packard                   | 10        | 0.22%   |
| D-Link                            | 10        | 0.22%   |
| Sierra Wireless                   | 9         | 0.2%    |
| JMicron Technology                | 9         | 0.2%    |
| Edimax Technology                 | 9         | 0.2%    |
| D-Link System                     | 9         | 0.2%    |
| ASUSTek Computer                  | 8         | 0.18%   |
| Qualcomm                          | 7         | 0.16%   |
| OPPO Electronics                  | 7         | 0.16%   |
| Motorola PCS                      | 6         | 0.13%   |
| Linksys                           | 5         | 0.11%   |
| Ericsson Business Mobile Networks | 5         | 0.11%   |
| Aquantia                          | 5         | 0.11%   |
| T & A Mobile Phones               | 4         | 0.09%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.09%   |
| Google                            | 4         | 0.09%   |
| VIA Technologies                  | 3         | 0.07%   |
| Belkin Components                 | 3         | 0.07%   |
| ZyDAS                             | 2         | 0.04%   |
| U-Blox                            | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 993       | 19.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 237       | 4.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 140       | 2.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 101       | 1.94%   |
| Intel Wi-Fi 6 AX200                                               | 97        | 1.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 80        | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 77        | 1.48%   |
| Intel Wireless 7265                                               | 77        | 1.48%   |
| Intel Wireless 7260                                               | 72        | 1.39%   |
| Intel Wireless 8265 / 8275                                        | 67        | 1.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 65        | 1.25%   |
| Intel Wi-Fi 6 AX201                                               | 65        | 1.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 64        | 1.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 57        | 1.1%    |
| Intel Ethernet Connection I217-LM                                 | 54        | 1.04%   |
| Intel I211 Gigabit Network Connection                             | 52        | 1%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 51        | 0.98%   |
| Broadcom BCM43142 802.11b/g/n                                     | 51        | 0.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 49        | 0.94%   |
| Intel Wireless 3165                                               | 47        | 0.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 44        | 0.85%   |
| Intel Wireless 8260                                               | 42        | 0.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 42        | 0.81%   |
| Realtek 802.11ac NIC                                              | 40        | 0.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 39        | 0.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 38        | 0.73%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 35        | 0.67%   |
| Intel Ethernet Connection (2) I219-V                              | 34        | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 33        | 0.63%   |
| Ralink MT7601U Wireless Adapter                                   | 31        | 0.6%    |
| Intel Ethernet Controller I225-V                                  | 30        | 0.58%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 30        | 0.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 29        | 0.56%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 28        | 0.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 28        | 0.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 28        | 0.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 27        | 0.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 26        | 0.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 24        | 0.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 21        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 947       | 37.91%  |
| Realtek Semiconductor                 | 462       | 18.49%  |
| Qualcomm Atheros                      | 447       | 17.89%  |
| Broadcom                              | 234       | 9.37%   |
| Ralink Technology                     | 67        | 2.68%   |
| Broadcom Limited                      | 59        | 2.36%   |
| TP-Link                               | 55        | 2.2%    |
| Ralink                                | 52        | 2.08%   |
| MediaTek                              | 42        | 1.68%   |
| NetGear                               | 19        | 0.76%   |
| Marvell Technology Group              | 17        | 0.68%   |
| Qualcomm Atheros Communications       | 14        | 0.56%   |
| D-Link                                | 10        | 0.4%    |
| Microsoft                             | 9         | 0.36%   |
| Edimax Technology                     | 9         | 0.36%   |
| Sierra Wireless                       | 7         | 0.28%   |
| Dell                                  | 7         | 0.28%   |
| D-Link System                         | 7         | 0.28%   |
| ASUSTek Computer                      | 7         | 0.28%   |
| Linksys                               | 5         | 0.2%    |
| Belkin Components                     | 3         | 0.12%   |
| ZyDAS                                 | 2         | 0.08%   |
| Gemtek                                | 2         | 0.08%   |
| FIBOCOM                               | 2         | 0.08%   |
| AVM                                   | 2         | 0.08%   |
| ZyXEL Communications                  | 1         | 0.04%   |
| Xiaomi                                | 1         | 0.04%   |
| TRENDnet                              | 1         | 0.04%   |
| Qualcomm                              | 1         | 0.04%   |
| Panasonic (Matsushita)                | 1         | 0.04%   |
| Ovislink                              | 1         | 0.04%   |
| Mercucys                              | 1         | 0.04%   |
| Hewlett-Packard                       | 1         | 0.04%   |
| Askey Computer                        | 1         | 0.04%   |
| ADMtek                                | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 101       | 4%      |
| Intel Wi-Fi 6 AX200                                            | 97        | 3.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 80        | 3.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 77        | 3.05%   |
| Intel Wireless 7265                                            | 77        | 3.05%   |
| Intel Wireless 7260                                            | 72        | 2.85%   |
| Intel Wireless 8265 / 8275                                     | 67        | 2.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 65        | 2.58%   |
| Intel Wi-Fi 6 AX201                                            | 65        | 2.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 57        | 2.26%   |
| Broadcom BCM43142 802.11b/g/n                                  | 51        | 2.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 49        | 1.94%   |
| Intel Wireless 3165                                            | 47        | 1.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 44        | 1.74%   |
| Intel Wireless 8260                                            | 42        | 1.66%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 42        | 1.66%   |
| Realtek 802.11ac NIC                                           | 40        | 1.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 39        | 1.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 38        | 1.51%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 35        | 1.39%   |
| Ralink MT7601U Wireless Adapter                                | 31        | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 29        | 1.15%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 28        | 1.11%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 28        | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 28        | 1.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 27        | 1.07%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 26        | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 24        | 0.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 21        | 0.83%   |
| Intel WiFi Link 5100                                           | 21        | 0.83%   |
| Intel Centrino Ultimate-N 6300                                 | 21        | 0.83%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 21        | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 19        | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 19        | 0.75%   |
| Intel Wireless 3160                                            | 19        | 0.75%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 18        | 0.71%   |
| Intel Wireless-AC 9260                                         | 18        | 0.71%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 18        | 0.71%   |
| Intel Centrino Wireless-N 2230                                 | 17        | 0.67%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 17        | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1369      | 53.17%  |
| Intel                             | 620       | 24.08%  |
| Qualcomm Atheros                  | 160       | 6.21%   |
| Broadcom                          | 142       | 5.51%   |
| Nvidia                            | 44        | 1.71%   |
| Marvell Technology Group          | 42        | 1.63%   |
| Broadcom Limited                  | 37        | 1.44%   |
| ASIX Electronics                  | 22        | 0.85%   |
| Samsung Electronics               | 19        | 0.74%   |
| Xiaomi                            | 16        | 0.62%   |
| DisplayLink                       | 14        | 0.54%   |
| Huawei Technologies               | 10        | 0.39%   |
| TP-Link                           | 9         | 0.35%   |
| JMicron Technology                | 9         | 0.35%   |
| OPPO Electronics                  | 7         | 0.27%   |
| Qualcomm                          | 6         | 0.23%   |
| MediaTek                          | 6         | 0.23%   |
| Aquantia                          | 5         | 0.19%   |
| Motorola PCS                      | 4         | 0.16%   |
| Google                            | 4         | 0.16%   |
| VIA Technologies                  | 3         | 0.12%   |
| Hewlett-Packard                   | 3         | 0.12%   |
| Sundance Technology Inc / IC Plus | 2         | 0.08%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.08%   |
| Sierra Wireless                   | 2         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.08%   |
| Microsoft                         | 2         | 0.08%   |
| HMD Global                        | 2         | 0.08%   |
| D-Link System                     | 2         | 0.08%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.04%   |
| Sun Microsystems                  | 1         | 0.04%   |
| Research In Motion                | 1         | 0.04%   |
| Novatel Wireless                  | 1         | 0.04%   |
| Motorola BCS                      | 1         | 0.04%   |
| LG Electronics                    | 1         | 0.04%   |
| Lenovo                            | 1         | 0.04%   |
| ICS Advent                        | 1         | 0.04%   |
| GoPro                             | 1         | 0.04%   |
| ASUSTek Computer                  | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 993       | 38%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 237       | 9.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 140       | 5.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 64        | 2.45%   |
| Intel Ethernet Connection I217-LM                                 | 54        | 2.07%   |
| Intel I211 Gigabit Network Connection                             | 52        | 1.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 51        | 1.95%   |
| Intel Ethernet Connection (2) I219-V                              | 34        | 1.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 33        | 1.26%   |
| Intel Ethernet Controller I225-V                                  | 30        | 1.15%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 30        | 1.15%   |
| Intel Ethernet Connection I218-LM                                 | 21        | 0.8%    |
| Intel Ethernet Connection I217-V                                  | 20        | 0.77%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 20        | 0.77%   |
| Intel 82577LM Gigabit Network Connection                          | 19        | 0.73%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 18        | 0.69%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 18        | 0.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 17        | 0.65%   |
| Nvidia MCP79 Ethernet                                             | 17        | 0.65%   |
| Intel Ethernet Connection I219-LM                                 | 17        | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                     | 17        | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 16        | 0.61%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 16        | 0.61%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 15        | 0.57%   |
| Intel 82567LM Gigabit Network Connection                          | 14        | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 13        | 0.5%    |
| Intel Ethernet Connection (7) I219-V                              | 13        | 0.5%    |
| Intel 82579V Gigabit Network Connection                           | 13        | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 12        | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 12        | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 12        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12        | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 12        | 0.46%   |
| Nvidia MCP61 Ethernet                                             | 12        | 0.46%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 0.46%   |
| Intel Ethernet Connection I219-V                                  | 11        | 0.42%   |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 0.42%   |
| Intel Ethernet Connection (2) I218-V                              | 11        | 0.42%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 11        | 0.42%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 11        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2441      | 50.42%  |
| WiFi     | 2340      | 48.34%  |
| Modem    | 49        | 1.01%   |
| Unknown  | 11        | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1836      | 60.24%  |
| Ethernet | 1207      | 39.6%   |
| Modem    | 3         | 0.1%    |
| Unknown  | 2         | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1593      | 54.05%  |
| 1     | 1194      | 40.52%  |
| 0     | 104       | 3.53%   |
| 3     | 50        | 1.7%    |
| 5     | 3         | 0.1%    |
| 4     | 2         | 0.07%   |
| 7     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2040      | 68.5%   |
| Yes  | 938       | 31.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 717       | 40.83%  |
| Realtek Semiconductor           | 206       | 11.73%  |
| Qualcomm Atheros Communications | 167       | 9.51%   |
| Broadcom                        | 101       | 5.75%   |
| Cambridge Silicon Radio         | 96        | 5.47%   |
| Apple                           | 94        | 5.35%   |
| IMC Networks                    | 84        | 4.78%   |
| Foxconn / Hon Hai               | 47        | 2.68%   |
| Lite-On Technology              | 46        | 2.62%   |
| Dell                            | 33        | 1.88%   |
| Hewlett-Packard                 | 27        | 1.54%   |
| ASUSTek Computer                | 26        | 1.48%   |
| Toshiba                         | 23        | 1.31%   |
| Marvell Semiconductor           | 15        | 0.85%   |
| Ralink                          | 13        | 0.74%   |
| MediaTek                        | 12        | 0.68%   |
| Realtek                         | 7         | 0.4%    |
| TP-Link                         | 6         | 0.34%   |
| Foxconn International           | 6         | 0.34%   |
| Integrated System Solution      | 5         | 0.28%   |
| Alps Electric                   | 5         | 0.28%   |
| Dynex                           | 4         | 0.23%   |
| Belkin Components               | 2         | 0.11%   |
| Askey Computer                  | 2         | 0.11%   |
| Actions                         | 2         | 0.11%   |
| Unknown                         | 2         | 0.11%   |
| Sitecom Europe                  | 1         | 0.06%   |
| Ralink Technology               | 1         | 0.06%   |
| Qcom                            | 1         | 0.06%   |
| National Semiconductor          | 1         | 0.06%   |
| Micro Star International        | 1         | 0.06%   |
| Edimax Technology               | 1         | 0.06%   |
| D-Link System                   | 1         | 0.06%   |
| Chicony Electronics             | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 310       | 17.64%  |
| Realtek Bluetooth Radio                             | 136       | 7.74%   |
| Intel AX201 Bluetooth                               | 106       | 6.03%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 96        | 5.46%   |
| Qualcomm Atheros  Bluetooth Device                  | 87        | 4.95%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 85        | 4.84%   |
| Intel AX200 Bluetooth                               | 83        | 4.72%   |
| Realtek  Bluetooth 4.2 Adapter                      | 44        | 2.5%    |
| Apple Bluetooth Host Controller                     | 44        | 2.5%    |
| Intel AX210 Bluetooth                               | 41        | 2.33%   |
| IMC Networks Bluetooth Device                       | 32        | 1.82%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 31        | 1.76%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 26        | 1.48%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 26        | 1.48%   |
| Intel Wireless-AC 3168 Bluetooth                    | 24        | 1.37%   |
| IMC Networks Bluetooth Radio                        | 24        | 1.37%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 23        | 1.31%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 23        | 1.31%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 19        | 1.08%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 17        | 0.97%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 16        | 0.91%   |
| Marvell Bluetooth and Wireless LAN Composite        | 15        | 0.85%   |
| Lite-On Atheros AR3012 Bluetooth                    | 15        | 0.85%   |
| Foxconn / Hon Hai Bluetooth Device                  | 15        | 0.85%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 14        | 0.8%    |
| Ralink RT3290 Bluetooth                             | 13        | 0.74%   |
| IMC Networks Wireless_Device                        | 13        | 0.74%   |
| HP Broadcom 2070 Bluetooth Combo                    | 13        | 0.74%   |
| Apple Bluetooth USB Host Controller                 | 13        | 0.74%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 12        | 0.68%   |
| Dell DW375 Bluetooth Module                         | 12        | 0.68%   |
| MediaTek Wireless_Device                            | 11        | 0.63%   |
| Broadcom BCM2045B (BDC-2.1)                         | 11        | 0.63%   |
| Apple Bluetooth HCI                                 | 11        | 0.63%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 10        | 0.57%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 10        | 0.57%   |
| Lite-On Bluetooth Device                            | 9         | 0.51%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 9         | 0.51%   |
| Toshiba Bluetooth Device                            | 8         | 0.46%   |
| Realtek RTL8723B Bluetooth                          | 8         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2158      | 55.01%  |
| AMD                                          | 817       | 20.83%  |
| Nvidia                                       | 640       | 16.31%  |
| C-Media Electronics                          | 46        | 1.17%   |
| Creative Labs                                | 20        | 0.51%   |
| Logitech                                     | 18        | 0.46%   |
| Texas Instruments                            | 14        | 0.36%   |
| Kingston Technology                          | 14        | 0.36%   |
| JMTek                                        | 12        | 0.31%   |
| Generalplus Technology                       | 12        | 0.31%   |
| Realtek Semiconductor                        | 11        | 0.28%   |
| ASUSTek Computer                             | 10        | 0.25%   |
| Razer USA                                    | 8         | 0.2%    |
| VIA Technologies                             | 7         | 0.18%   |
| Plantronics                                  | 7         | 0.18%   |
| GN Netcom                                    | 7         | 0.18%   |
| SteelSeries ApS                              | 6         | 0.15%   |
| Creative Technology                          | 6         | 0.15%   |
| Lenovo                                       | 5         | 0.13%   |
| Focusrite-Novation                           | 5         | 0.13%   |
| DCMT Technology                              | 5         | 0.13%   |
| Tenx Technology                              | 4         | 0.1%    |
| RODE Microphones                             | 3         | 0.08%   |
| Micro Star International                     | 3         | 0.08%   |
| DSEA A/S                                     | 3         | 0.08%   |
| Corsair                                      | 3         | 0.08%   |
| Astro Gaming                                 | 3         | 0.08%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.05%   |
| Yamaha                                       | 2         | 0.05%   |
| Thesycon Systemsoftware & Consulting         | 2         | 0.05%   |
| Sony                                         | 2         | 0.05%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.05%   |
| SAVITECH                                     | 2         | 0.05%   |
| Samsung Electronics                          | 2         | 0.05%   |
| Numark                                       | 2         | 0.05%   |
| KTMicro                                      | 2         | 0.05%   |
| Dell                                         | 2         | 0.05%   |
| Cambridge Audio                              | 2         | 0.05%   |
| BR25                                         | 2         | 0.05%   |
| Blue Microphones                             | 2         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 248       | 5.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 238       | 5.1%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 208       | 4.46%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 187       | 4.01%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 168       | 3.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 129       | 2.77%   |
| AMD FCH Azalia Controller                                                                         | 118       | 2.53%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 112       | 2.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 108       | 2.32%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 100       | 2.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 96        | 2.06%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 96        | 2.06%   |
| Intel 8 Series HD Audio Controller                                                                | 94        | 2.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 93        | 1.99%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 90        | 1.93%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 83        | 1.78%   |
| Intel Cannon Lake PCH cAVS                                                                        | 76        | 1.63%   |
| AMD Kabini HDMI/DP Audio                                                                          | 75        | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 68        | 1.46%   |
| Intel Broadwell-U Audio Controller                                                                | 67        | 1.44%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 62        | 1.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 61        | 1.31%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 58        | 1.24%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 56        | 1.2%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 55        | 1.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 52        | 1.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 51        | 1.09%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 49        | 1.05%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 42        | 0.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 40        | 0.86%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 40        | 0.86%   |
| Intel 200 Series PCH HD Audio                                                                     | 39        | 0.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 37        | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 34        | 0.73%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 33        | 0.71%   |
| Nvidia High Definition Audio Controller                                                           | 33        | 0.71%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 33        | 0.71%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 33        | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 33        | 0.71%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 33        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 154       | 23.95%  |
| SK hynix               | 113       | 17.57%  |
| Micron Technology      | 64        | 9.95%   |
| Unknown                | 59        | 9.18%   |
| Kingston               | 53        | 8.24%   |
| Crucial                | 35        | 5.44%   |
| G.Skill                | 20        | 3.11%   |
| Unknown (ABCD)         | 19        | 2.95%   |
| Corsair                | 17        | 2.64%   |
| A-DATA Technology      | 14        | 2.18%   |
| Ramaxel Technology     | 11        | 1.71%   |
| Elpida                 | 11        | 1.71%   |
| Team                   | 9         | 1.4%    |
| Nanya Technology       | 7         | 1.09%   |
| Patriot                | 5         | 0.78%   |
| Unknown                | 5         | 0.78%   |
| Smart                  | 4         | 0.62%   |
| Avant                  | 3         | 0.47%   |
| Wilk                   | 2         | 0.31%   |
| Unifosa                | 2         | 0.31%   |
| Transcend              | 2         | 0.31%   |
| Timetec                | 2         | 0.31%   |
| Teikon                 | 2         | 0.31%   |
| Qimonda                | 2         | 0.31%   |
| ff                     | 2         | 0.31%   |
| fef5                   | 2         | 0.31%   |
| 4ea5                   | 2         | 0.31%   |
| Unknown (08B5)         | 1         | 0.16%   |
| Unknown (07F7)         | 1         | 0.16%   |
| Unknown (000080B30080) | 1         | 0.16%   |
| SUPER KINGSTEK         | 1         | 0.16%   |
| Strontium              | 1         | 0.16%   |
| SHARETRONIC            | 1         | 0.16%   |
| PUSKILL                | 1         | 0.16%   |
| ProMos/Mosel Vitelic   | 1         | 0.16%   |
| PNY                    | 1         | 0.16%   |
| Patriot Memory         | 1         | 0.16%   |
| Netlist                | 1         | 0.16%   |
| Kllisre                | 1         | 0.16%   |
| Kingmax                | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s  | 17        | 2.48%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 9         | 1.31%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 7         | 1.02%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s            | 7         | 1.02%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 7         | 1.02%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s             | 7         | 1.02%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 6         | 0.87%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 6         | 0.87%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s            | 5         | 0.73%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s             | 5         | 0.73%   |
| Unknown                                                           | 5         | 0.73%   |
| Unknown RAM Module 4096MB SODIMM DDR3                             | 4         | 0.58%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                      | 4         | 0.58%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                    | 4         | 0.58%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 4         | 0.58%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 4         | 0.58%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s        | 4         | 0.58%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 4         | 0.58%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s             | 4         | 0.58%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s       | 4         | 0.58%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s             | 4         | 0.58%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s             | 4         | 0.58%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.58%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s        | 4         | 0.58%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3000MT/s                | 3         | 0.44%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 3         | 0.44%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 3         | 0.44%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 3         | 0.44%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s            | 3         | 0.44%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s            | 3         | 0.44%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s  | 3         | 0.44%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s             | 3         | 0.44%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s             | 3         | 0.44%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s             | 3         | 0.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s       | 3         | 0.44%   |
| Micron RAM MT40A512M16TB-062E:J 4096MB Row Of Chips DDR4 3200MT/s | 3         | 0.44%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 3         | 0.44%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s              | 3         | 0.44%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s             | 3         | 0.44%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s            | 3         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 233       | 42.29%  |
| DDR3    | 205       | 37.21%  |
| LPDDR4  | 41        | 7.44%   |
| LPDDR3  | 23        | 4.17%   |
| DDR2    | 22        | 3.99%   |
| SDRAM   | 11        | 2%      |
| Unknown | 10        | 1.81%   |
| DDR     | 3         | 0.54%   |
| DDR5    | 2         | 0.36%   |
| LPDDR5  | 1         | 0.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 335       | 61.02%  |
| DIMM         | 149       | 27.14%  |
| Row Of Chips | 54        | 9.84%   |
| Unknown      | 6         | 1.09%   |
| Chip         | 4         | 0.73%   |
| FB-DIMM      | 1         | 0.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 227       | 37.09%  |
| 4096  | 200       | 32.68%  |
| 2048  | 89        | 14.54%  |
| 16384 | 59        | 9.64%   |
| 1024  | 20        | 3.27%   |
| 32768 | 16        | 2.61%   |
| 512   | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 129       | 21.61%  |
| 3200    | 93        | 15.58%  |
| 2667    | 77        | 12.9%   |
| 2400    | 53        | 8.88%   |
| 1333    | 43        | 7.2%    |
| 1334    | 24        | 4.02%   |
| 2133    | 23        | 3.85%   |
| 1867    | 14        | 2.35%   |
| 4267    | 13        | 2.18%   |
| 667     | 13        | 2.18%   |
| 3600    | 12        | 2.01%   |
| 3266    | 10        | 1.68%   |
| 800     | 10        | 1.68%   |
| Unknown | 10        | 1.68%   |
| 1066    | 9         | 1.51%   |
| 3000    | 6         | 1.01%   |
| 1866    | 4         | 0.67%   |
| 1800    | 4         | 0.67%   |
| 1067    | 4         | 0.67%   |
| 8400    | 3         | 0.5%    |
| 4266    | 3         | 0.5%    |
| 2933    | 3         | 0.5%    |
| 2666    | 3         | 0.5%    |
| 2048    | 3         | 0.5%    |
| 4800    | 2         | 0.34%   |
| 4199    | 2         | 0.34%   |
| 3866    | 2         | 0.34%   |
| 3800    | 2         | 0.34%   |
| 3733    | 2         | 0.34%   |
| 3666    | 2         | 0.34%   |
| 3466    | 2         | 0.34%   |
| 3333    | 2         | 0.34%   |
| 975     | 2         | 0.34%   |
| 6400    | 1         | 0.17%   |
| 5354    | 1         | 0.17%   |
| 4000    | 1         | 0.17%   |
| 3933    | 1         | 0.17%   |
| 3500    | 1         | 0.17%   |
| 3467    | 1         | 0.17%   |
| 3400    | 1         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 17        | 25.37%  |
| Canon                 | 13        | 19.4%   |
| Brother Industries    | 13        | 19.4%   |
| Seiko Epson           | 10        | 14.93%  |
| Samsung Electronics   | 9         | 13.43%  |
| Lexmark International | 2         | 2.99%   |
| Zebra                 | 1         | 1.49%   |
| QinHeng Electronics   | 1         | 1.49%   |
| Konica Minolta        | 1         | 1.49%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson L3110 Series                     | 3         | 4.48%   |
| Samsung C460 Series                          | 2         | 2.99%   |
| HP ENVY Photo 6200 series                    | 2         | 2.99%   |
| HP DeskJet 2130 series                       | 2         | 2.99%   |
| Canon TS3100 series                          | 2         | 2.99%   |
| Canon LiDE 400                               | 2         | 2.99%   |
| Brother HL-2140 series                       | 2         | 2.99%   |
| Zebra ZP 450 Printer                         | 1         | 1.49%   |
| Seiko Epson XP-7100 Series                   | 1         | 1.49%   |
| Seiko Epson XP-200 Series                    | 1         | 1.49%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 1.49%   |
| Seiko Epson L355 Series                      | 1         | 1.49%   |
| Seiko Epson L3150 Series                     | 1         | 1.49%   |
| Seiko Epson ET-2820 Series                   | 1         | 1.49%   |
| Seiko Epson ET-2810 Series                   | 1         | 1.49%   |
| Samsung SCX-483x 5x3x Series                 | 1         | 1.49%   |
| Samsung SCX-4623 Series                      | 1         | 1.49%   |
| Samsung SCX-4200 series                      | 1         | 1.49%   |
| Samsung SCX-3400 Series                      | 1         | 1.49%   |
| Samsung ML-2950 Series                       | 1         | 1.49%   |
| Samsung ML-216x Series Laser Printer         | 1         | 1.49%   |
| Samsung M2020 Series                         | 1         | 1.49%   |
| QinHeng CH340S                               | 1         | 1.49%   |
| Lexmark International MX317dn                | 1         | 1.49%   |
| Lexmark International 2400 series            | 1         | 1.49%   |
| Konica Minolta PagePro 1380MF                | 1         | 1.49%   |
| HP Smart Tank 510 series                     | 1         | 1.49%   |
| HP PSC 1100 series                           | 1         | 1.49%   |
| HP OfficeJet Pro 9010 series                 | 1         | 1.49%   |
| HP Officejet 6600                            | 1         | 1.49%   |
| HP OfficeJet 5600 (USBHUB)                   | 1         | 1.49%   |
| HP OfficeJet 4650 series                     | 1         | 1.49%   |
| HP LaserJet Professional P1102w              | 1         | 1.49%   |
| HP LaserJet 1200                             | 1         | 1.49%   |
| HP LaserJet 1000                             | 1         | 1.49%   |
| HP ENVY 4520 series                          | 1         | 1.49%   |
| HP DeskJet 2700 series                       | 1         | 1.49%   |
| HP DeskJet 2300 series                       | 1         | 1.49%   |
| HP DeskJet 1110 series                       | 1         | 1.49%   |
| Canon TR4500 series                          | 1         | 1.49%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 7         | 63.64%  |
| Seiko Epson     | 2         | 18.18%  |
| Hewlett-Packard | 2         | 18.18%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 18.18%  |
| HP ScanJet 2400c                            | 1         | 9.09%   |
| HP PSC 1200                                 | 1         | 9.09%   |
| Canon CanoScan LiDE 90                      | 1         | 9.09%   |
| Canon CanoScan LiDE 60                      | 1         | 9.09%   |
| Canon CanoScan LIDE 25                      | 1         | 9.09%   |
| Canon CanoScan LiDE 110                     | 1         | 9.09%   |
| Canon CanoScan LiDE 100                     | 1         | 9.09%   |
| Canon CanoScan D660U                        | 1         | 9.09%   |
| Canon CanoScan 8800F                        | 1         | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 353       | 20.51%  |
| Microdia                               | 160       | 9.3%    |
| Realtek Semiconductor                  | 145       | 8.43%   |
| IMC Networks                           | 131       | 7.61%   |
| Sunplus Innovation Technology          | 94        | 5.46%   |
| Apple                                  | 87        | 5.06%   |
| Cheng Uei Precision Industry (Foxlink) | 78        | 4.53%   |
| Quanta                                 | 67        | 3.89%   |
| Logitech                               | 66        | 3.83%   |
| Suyin                                  | 63        | 3.66%   |
| Acer                                   | 63        | 3.66%   |
| Bison Electronics                      | 49        | 2.85%   |
| Syntek                                 | 45        | 2.61%   |
| Lite-On Technology                     | 30        | 1.74%   |
| Silicon Motion                         | 27        | 1.57%   |
| Alcor Micro                            | 24        | 1.39%   |
| Samsung Electronics                    | 17        | 0.99%   |
| Ricoh                                  | 17        | 0.99%   |
| Microsoft                              | 17        | 0.99%   |
| Luxvisions Innotech Limited            | 15        | 0.87%   |
| icSpring                               | 12        | 0.7%    |
| Primax Electronics                     | 11        | 0.64%   |
| Sonix Technology                       | 10        | 0.58%   |
| Generalplus Technology                 | 10        | 0.58%   |
| ARC International                      | 10        | 0.58%   |
| Lenovo                                 | 8         | 0.46%   |
| GEMBIRD                                | 8         | 0.46%   |
| ALi                                    | 8         | 0.46%   |
| SunplusIT                              | 6         | 0.35%   |
| Z-Star Microelectronics                | 5         | 0.29%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.29%   |
| Importek                               | 5         | 0.29%   |
| Sunplus Technology                     | 4         | 0.23%   |
| Razer USA                              | 4         | 0.23%   |
| Jieli Technology                       | 4         | 0.23%   |
| Y Media                                | 3         | 0.17%   |
| Tobii Technology AB                    | 3         | 0.17%   |
| OmniVision Technologies                | 3         | 0.17%   |
| Huawei Technologies                    | 3         | 0.17%   |
| Genesys Logic                          | 3         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 52        | 3%      |
| Microdia Integrated_Webcam_HD                    | 35        | 2.02%   |
| IMC Networks USB2.0 HD UVC WebCam                | 34        | 1.96%   |
| Apple FaceTime HD Camera (Built-in)              | 33        | 1.91%   |
| Realtek Integrated_Webcam_HD                     | 30        | 1.73%   |
| Syntek Integrated Camera                         | 28        | 1.62%   |
| Chicony HD WebCam                                | 28        | 1.62%   |
| Microdia Integrated Webcam                       | 26        | 1.5%    |
| Chicony HP Truevision HD                         | 24        | 1.39%   |
| IMC Networks Integrated Camera                   | 23        | 1.33%   |
| Apple Built-in iSight                            | 21        | 1.21%   |
| Chicony TOSHIBA Web Camera - HD                  | 20        | 1.15%   |
| Bison Integrated Camera                          | 19        | 1.1%    |
| IMC Networks USB2.0 VGA UVC WebCam               | 18        | 1.04%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 18        | 1.04%   |
| Samsung Galaxy series, misc. (MTP mode)          | 17        | 0.98%   |
| Acer Lenovo EasyCamera                           | 17        | 0.98%   |
| Realtek USB Camera                               | 16        | 0.92%   |
| Logitech Webcam C270                             | 16        | 0.92%   |
| Acer Integrated Camera                           | 15        | 0.87%   |
| Sunplus HD WebCam                                | 14        | 0.81%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 14        | 0.81%   |
| Microdia Webcam Vitade AF                        | 13        | 0.75%   |
| Chicony Lenovo EasyCamera                        | 13        | 0.75%   |
| Sunplus Integrated_Webcam_HD                     | 12        | 0.69%   |
| Logitech HD Pro Webcam C920                      | 12        | 0.69%   |
| icSpring camera                                  | 12        | 0.69%   |
| Chicony HP Wide Vision HD Camera                 | 12        | 0.69%   |
| Chicony HP Truevision HD camera                  | 12        | 0.69%   |
| Apple FaceTime HD Camera                         | 12        | 0.69%   |
| Realtek Integrated Webcam HD                     | 11        | 0.64%   |
| Realtek Integrated Webcam                        | 11        | 0.64%   |
| Realtek HP Truevision HD                         | 11        | 0.64%   |
| Chicony VGA WebCam                               | 11        | 0.64%   |
| Chicony USB2.0 VGA UVC WebCam                    | 11        | 0.64%   |
| Chicony EasyCamera                               | 11        | 0.64%   |
| Realtek Lenovo EasyCamera                        | 10        | 0.58%   |
| Quanta HP Wide Vision HD Camera                  | 10        | 0.58%   |
| Chicony HP HD Webcam                             | 10        | 0.58%   |
| ARC International Camera                         | 10        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 108       | 40.6%   |
| Synaptics                  | 40        | 15.04%  |
| Shenzhen Goodix Technology | 36        | 13.53%  |
| AuthenTec                  | 26        | 9.77%   |
| Upek                       | 21        | 7.89%   |
| Elan Microelectronics      | 16        | 6.02%   |
| LighTuning Technology      | 8         | 3.01%   |
| STMicroelectronics         | 6         | 2.26%   |
| Samsung Electronics        | 2         | 0.75%   |
| Next Biometrics            | 1         | 0.38%   |
| HOLTEK                     | 1         | 0.38%   |
| Focal-systems.Corp         | 1         | 0.38%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 21        | 7.89%   |
| Shenzhen Goodix  FingerPrint Device                                        | 21        | 7.89%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 20        | 7.52%   |
| Shenzhen Goodix Fingerprint Reader                                         | 13        | 4.89%   |
| Validity Sensors VFS491                                                    | 12        | 4.51%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 4.51%   |
| Elan ELAN:ARM-M4                                                           | 11        | 4.14%   |
| AuthenTec AES2810                                                          | 11        | 4.14%   |
| Validity Sensors Fingerprint scanner                                       | 10        | 3.76%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 3.38%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 3.01%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 2.63%   |
| Synaptics  WBDI                                                            | 7         | 2.63%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 2.63%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 2.26%   |
| Synaptics UWP WBDI                                                         | 6         | 2.26%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 2.26%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2.26%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 1.88%   |
| Synaptics WBDI                                                             | 5         | 1.88%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 5         | 1.88%   |
| Elan ELAN:Fingerprint                                                      | 5         | 1.88%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.5%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.5%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.5%    |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.5%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 1.13%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 1.13%   |
| AuthenTec AES1600                                                          | 3         | 1.13%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.75%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.75%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.75%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.75%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 0.75%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 0.75%   |
| LighTuning Fingerprint Sensor                                              | 2         | 0.75%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.38%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.38%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.38%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.38%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 54        | 49.54%  |
| Alcor Micro                       | 17        | 15.6%   |
| O2 Micro                          | 12        | 11.01%  |
| Lenovo                            | 6         | 5.5%    |
| Upek                              | 5         | 4.59%   |
| Realtek Semiconductor             | 3         | 2.75%   |
| Yubico.com                        | 2         | 1.83%   |
| VASCO Data Security International | 2         | 1.83%   |
| SCM Microsystems                  | 2         | 1.83%   |
| Fujitsu Siemens Computers         | 2         | 1.83%   |
| Advanced Card Systems             | 2         | 1.83%   |
| Reiner SCT Kartensysteme          | 1         | 0.92%   |
| OmniKey                           | 1         | 0.92%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 21        | 19.27%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 17        | 15.6%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 16        | 14.68%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 11        | 10.09%  |
| Broadcom 5880                                                                | 11        | 10.09%  |
| Lenovo Integrated Smart Card Reader                                          | 6         | 5.5%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 4.59%   |
| Broadcom 58200                                                               | 4         | 3.67%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 2.75%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 2         | 1.83%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 2         | 1.83%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.83%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.92%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.92%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.92%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.92%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                              | 1         | 0.92%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.92%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.92%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.92%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.92%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2154      | 72.16%  |
| 1     | 676       | 22.65%  |
| 2     | 142       | 4.76%   |
| 3     | 11        | 0.37%   |
| 8     | 1         | 0.03%   |
| 4     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 260       | 26.83%  |
| Graphics card            | 206       | 21.26%  |
| Net/wireless             | 165       | 17.03%  |
| Multimedia controller    | 114       | 11.76%  |
| Chipcard                 | 100       | 10.32%  |
| Storage                  | 22        | 2.27%   |
| Bluetooth                | 19        | 1.96%   |
| Communication controller | 15        | 1.55%   |
| Sound                    | 11        | 1.14%   |
| Unassigned class         | 9         | 0.93%   |
| Camera                   | 9         | 0.93%   |
| Modem                    | 7         | 0.72%   |
| Net/ethernet             | 6         | 0.62%   |
| Storage/raid             | 5         | 0.52%   |
| Storage/ide              | 4         | 0.41%   |
| Network                  | 4         | 0.41%   |
| Dvb card                 | 4         | 0.41%   |
| Card reader              | 4         | 0.41%   |
| Storage/nvme             | 2         | 0.21%   |
| Flash memory             | 2         | 0.21%   |
| Unclassified device      | 1         | 0.1%    |

