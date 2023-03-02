Xubuntu - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Xubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xubuntu/Desktop/README.md) and [notebooks](/Dist/Xubuntu/Notebook/README.md).

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

Total: 5899

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | P5KC                        | Desktop     | [45f781ee3a](https://linux-hardware.org/?probe=45f781ee3a) | Feb 28, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [aeb7d7a9f4](https://linux-hardware.org/?probe=aeb7d7a9f4) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [83e6da010b](https://linux-hardware.org/?probe=83e6da010b) | Feb 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [1a407f82b9](https://linux-hardware.org/?probe=1a407f82b9) | Feb 27, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [de0d12baa4](https://linux-hardware.org/?probe=de0d12baa4) | Feb 27, 2023 |
| MSI           | B150M PRO-VDH               | Desktop     | [e538527e6c](https://linux-hardware.org/?probe=e538527e6c) | Feb 26, 2023 |
| HP            | 655                         | Notebook    | [e6b694526e](https://linux-hardware.org/?probe=e6b694526e) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [3f35f45bf0](https://linux-hardware.org/?probe=3f35f45bf0) | Feb 26, 2023 |
| Gigabyte      | MZBSWBP-00                  | Desktop     | [525ac20362](https://linux-hardware.org/?probe=525ac20362) | Feb 26, 2023 |
| Alienware     | 17 R4                       | Notebook    | [bfeccbf9f3](https://linux-hardware.org/?probe=bfeccbf9f3) | Feb 25, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [75a0fcca48](https://linux-hardware.org/?probe=75a0fcca48) | Feb 25, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [634b80ac90](https://linux-hardware.org/?probe=634b80ac90) | Feb 24, 2023 |
| Dell          | Latitude E5470              | Notebook    | [d7c8a049c4](https://linux-hardware.org/?probe=d7c8a049c4) | Feb 24, 2023 |
| MSI           | C847MS-E33                  | Desktop     | [698d950f05](https://linux-hardware.org/?probe=698d950f05) | Feb 24, 2023 |
| AZW           | U59                         | Desktop     | [b574c32b53](https://linux-hardware.org/?probe=b574c32b53) | Feb 24, 2023 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [2645328f34](https://linux-hardware.org/?probe=2645328f34) | Feb 23, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [43b2cca281](https://linux-hardware.org/?probe=43b2cca281) | Feb 23, 2023 |
| Dell          | 0YC03K A03                  | Desktop     | [0101ef8ce7](https://linux-hardware.org/?probe=0101ef8ce7) | Feb 23, 2023 |
| Dell          | Studio 1450                 | Notebook    | [c26228f66f](https://linux-hardware.org/?probe=c26228f66f) | Feb 22, 2023 |
| Lenovo        | ThinkPad X131e 3367AH5      | Notebook    | [3c1cec4c1c](https://linux-hardware.org/?probe=3c1cec4c1c) | Feb 22, 2023 |
| Acer          | Aspire 7736                 | Notebook    | [479496a645](https://linux-hardware.org/?probe=479496a645) | Feb 21, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [751f76b561](https://linux-hardware.org/?probe=751f76b561) | Feb 21, 2023 |
| HP            | Pavilion 15                 | Notebook    | [c33178dcdc](https://linux-hardware.org/?probe=c33178dcdc) | Feb 21, 2023 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [c9adb74693](https://linux-hardware.org/?probe=c9adb74693) | Feb 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [7ac4bb7d51](https://linux-hardware.org/?probe=7ac4bb7d51) | Feb 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [656629ffba](https://linux-hardware.org/?probe=656629ffba) | Feb 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [19e03ac7b2](https://linux-hardware.org/?probe=19e03ac7b2) | Feb 20, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [4a9dcac308](https://linux-hardware.org/?probe=4a9dcac308) | Feb 19, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [d808827823](https://linux-hardware.org/?probe=d808827823) | Feb 19, 2023 |
| HP            | 158A                        | Desktop     | [ce217224ba](https://linux-hardware.org/?probe=ce217224ba) | Feb 19, 2023 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [e85ff6e5c3](https://linux-hardware.org/?probe=e85ff6e5c3) | Feb 18, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [51cf60bd9b](https://linux-hardware.org/?probe=51cf60bd9b) | Feb 18, 2023 |
| Sony          | VPCEA3S1E                   | Notebook    | [45d0b9a823](https://linux-hardware.org/?probe=45d0b9a823) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [28c9b2590c](https://linux-hardware.org/?probe=28c9b2590c) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [89c51847f9](https://linux-hardware.org/?probe=89c51847f9) | Feb 18, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [8338ee5a0d](https://linux-hardware.org/?probe=8338ee5a0d) | Feb 17, 2023 |
| Sony          | VPCZ13M9E                   | Notebook    | [b3db404e91](https://linux-hardware.org/?probe=b3db404e91) | Feb 17, 2023 |
| Gigabyte      | H410M S2 V3                 | Desktop     | [0dbeeea38c](https://linux-hardware.org/?probe=0dbeeea38c) | Feb 16, 2023 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [8cd6645d36](https://linux-hardware.org/?probe=8cd6645d36) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [e1bbf14222](https://linux-hardware.org/?probe=e1bbf14222) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [ba96494c0f](https://linux-hardware.org/?probe=ba96494c0f) | Feb 16, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [40c415883e](https://linux-hardware.org/?probe=40c415883e) | Feb 16, 2023 |
| HP            | Pavilion g6                 | Notebook    | [8a53743bd0](https://linux-hardware.org/?probe=8a53743bd0) | Feb 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [0b622220d7](https://linux-hardware.org/?probe=0b622220d7) | Feb 15, 2023 |
| Pegatron      | EVE                         | Desktop     | [0bde64bb64](https://linux-hardware.org/?probe=0bde64bb64) | Feb 15, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | Notebook    | [d576d16c25](https://linux-hardware.org/?probe=d576d16c25) | Feb 14, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | Notebook    | [2334fc688f](https://linux-hardware.org/?probe=2334fc688f) | Feb 14, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [21ad600245](https://linux-hardware.org/?probe=21ad600245) | Feb 14, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | Notebook    | [e2f49b2fe4](https://linux-hardware.org/?probe=e2f49b2fe4) | Feb 14, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [6e1d13cecb](https://linux-hardware.org/?probe=6e1d13cecb) | Feb 14, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [33e3d93b19](https://linux-hardware.org/?probe=33e3d93b19) | Feb 14, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [25dbf25c62](https://linux-hardware.org/?probe=25dbf25c62) | Feb 14, 2023 |
| ASRock        | AOD790GX/128M               | Desktop     | [693f4f40f8](https://linux-hardware.org/?probe=693f4f40f8) | Feb 13, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [bb037d75a7](https://linux-hardware.org/?probe=bb037d75a7) | Feb 13, 2023 |
| HP            | Compaq nc6400 (RM741PA#A... | Notebook    | [d556bf453d](https://linux-hardware.org/?probe=d556bf453d) | Feb 13, 2023 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [0634db3367](https://linux-hardware.org/?probe=0634db3367) | Feb 13, 2023 |
| Fujitsu       | D3613-A1 S26361-D3613-A1    | Desktop     | [dd2d87798a](https://linux-hardware.org/?probe=dd2d87798a) | Feb 13, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [f840248d22](https://linux-hardware.org/?probe=f840248d22) | Feb 13, 2023 |
| Sony          | VPCX11Z6R                   | Notebook    | [ad87a45a26](https://linux-hardware.org/?probe=ad87a45a26) | Feb 12, 2023 |
| Packard Be... | DOT S                       | Notebook    | [1f57142ffd](https://linux-hardware.org/?probe=1f57142ffd) | Feb 12, 2023 |
| ASUSTek       | P8H77-I                     | Desktop     | [74013e0688](https://linux-hardware.org/?probe=74013e0688) | Feb 11, 2023 |
| Dell          | Latitude E5450              | Notebook    | [693f8c9c36](https://linux-hardware.org/?probe=693f8c9c36) | Feb 11, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [59a015c31d](https://linux-hardware.org/?probe=59a015c31d) | Feb 11, 2023 |
| Gigabyte      | GA-A75-UD4H                 | Desktop     | [eb4302c6dd](https://linux-hardware.org/?probe=eb4302c6dd) | Feb 10, 2023 |
| HP            | Compaq Presario A900        | Notebook    | [d3c4a9e1e6](https://linux-hardware.org/?probe=d3c4a9e1e6) | Feb 09, 2023 |
| Lenovo        | ThinkPad T430s 23562Z3      | Notebook    | [7338d8375a](https://linux-hardware.org/?probe=7338d8375a) | Feb 09, 2023 |
| Acer          | Extensa 5635ZG              | Notebook    | [dd22b216a9](https://linux-hardware.org/?probe=dd22b216a9) | Feb 08, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [d5bb6335d4](https://linux-hardware.org/?probe=d5bb6335d4) | Feb 08, 2023 |
| Acer          | Aspire E5-572G              | Notebook    | [f44e9ce856](https://linux-hardware.org/?probe=f44e9ce856) | Feb 08, 2023 |
| Lenovo        | ThinkPad T440p 20AN006NU... | Notebook    | [e3bd76eeaf](https://linux-hardware.org/?probe=e3bd76eeaf) | Feb 07, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [feeed093c0](https://linux-hardware.org/?probe=feeed093c0) | Feb 07, 2023 |
| Dell          | Latitude D430               | Notebook    | [0c1ad39f32](https://linux-hardware.org/?probe=0c1ad39f32) | Feb 06, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [cb02cfc77c](https://linux-hardware.org/?probe=cb02cfc77c) | Feb 05, 2023 |
| MSI           | MS-7309                     | Desktop     | [46995d58eb](https://linux-hardware.org/?probe=46995d58eb) | Feb 05, 2023 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [99dc5ad30d](https://linux-hardware.org/?probe=99dc5ad30d) | Feb 05, 2023 |
| ASUSTek       | P5V-VM DH                   | Desktop     | [9d090675b1](https://linux-hardware.org/?probe=9d090675b1) | Feb 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | Notebook    | [262dfe3aa9](https://linux-hardware.org/?probe=262dfe3aa9) | Feb 05, 2023 |
| Intel         | Unknown                     | Notebook    | [f12482330f](https://linux-hardware.org/?probe=f12482330f) | Feb 05, 2023 |
| Lenovo        | ThinkPad R500 2716W2K       | Notebook    | [a645368e82](https://linux-hardware.org/?probe=a645368e82) | Feb 04, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9c9aa5e0e0](https://linux-hardware.org/?probe=9c9aa5e0e0) | Feb 03, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [163991dfae](https://linux-hardware.org/?probe=163991dfae) | Feb 03, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [7cd66ad148](https://linux-hardware.org/?probe=7cd66ad148) | Feb 03, 2023 |
| HP            | 240 G3                      | Notebook    | [43e56d3ae5](https://linux-hardware.org/?probe=43e56d3ae5) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ccf7f4d126](https://linux-hardware.org/?probe=ccf7f4d126) | Feb 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [c6d48c9847](https://linux-hardware.org/?probe=c6d48c9847) | Feb 03, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [a08e60bb31](https://linux-hardware.org/?probe=a08e60bb31) | Feb 03, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [d6829621d7](https://linux-hardware.org/?probe=d6829621d7) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [fafb999b1a](https://linux-hardware.org/?probe=fafb999b1a) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [50076364b8](https://linux-hardware.org/?probe=50076364b8) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [0211cbb448](https://linux-hardware.org/?probe=0211cbb448) | Feb 03, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [17b77b89e5](https://linux-hardware.org/?probe=17b77b89e5) | Feb 03, 2023 |
| ECS           | SF20PA2                     | Notebook    | [30df19ca2e](https://linux-hardware.org/?probe=30df19ca2e) | Feb 02, 2023 |
| Dell          | 0HFG24 A02                  | Server      | [a05562bc52](https://linux-hardware.org/?probe=a05562bc52) | Feb 02, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [894f632950](https://linux-hardware.org/?probe=894f632950) | Feb 01, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [0d500d9d33](https://linux-hardware.org/?probe=0d500d9d33) | Jan 31, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [8641149603](https://linux-hardware.org/?probe=8641149603) | Jan 31, 2023 |
| Dell          | Latitude D630               | Notebook    | [d8ac695aa3](https://linux-hardware.org/?probe=d8ac695aa3) | Jan 31, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3fac03d01d](https://linux-hardware.org/?probe=3fac03d01d) | Jan 30, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [0f2037dcd8](https://linux-hardware.org/?probe=0f2037dcd8) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [0e28b954b4](https://linux-hardware.org/?probe=0e28b954b4) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [10421fe598](https://linux-hardware.org/?probe=10421fe598) | Jan 30, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [00a3607d18](https://linux-hardware.org/?probe=00a3607d18) | Jan 30, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6444a93633](https://linux-hardware.org/?probe=6444a93633) | Jan 29, 2023 |
| HP            | 0A08h                       | Desktop     | [f9b0168de1](https://linux-hardware.org/?probe=f9b0168de1) | Jan 28, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [c93d5da3f1](https://linux-hardware.org/?probe=c93d5da3f1) | Jan 28, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [e9d671848c](https://linux-hardware.org/?probe=e9d671848c) | Jan 27, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [f409b1df0b](https://linux-hardware.org/?probe=f409b1df0b) | Jan 27, 2023 |
| Philco        | 14E                         | Notebook    | [1c069ed627](https://linux-hardware.org/?probe=1c069ed627) | Jan 27, 2023 |
| Philco        | 14E                         | Notebook    | [cfb283e599](https://linux-hardware.org/?probe=cfb283e599) | Jan 27, 2023 |
| Gigabyte      | H310M S2H                   | Desktop     | [6aa78b855a](https://linux-hardware.org/?probe=6aa78b855a) | Jan 27, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [cf42b2f763](https://linux-hardware.org/?probe=cf42b2f763) | Jan 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [64810b20c3](https://linux-hardware.org/?probe=64810b20c3) | Jan 26, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [6de2ea7d90](https://linux-hardware.org/?probe=6de2ea7d90) | Jan 26, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [82ce911f26](https://linux-hardware.org/?probe=82ce911f26) | Jan 25, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [34e69693d1](https://linux-hardware.org/?probe=34e69693d1) | Jan 25, 2023 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [28effc69e6](https://linux-hardware.org/?probe=28effc69e6) | Jan 25, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [4867533043](https://linux-hardware.org/?probe=4867533043) | Jan 25, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [058de08b2b](https://linux-hardware.org/?probe=058de08b2b) | Jan 24, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Dell          | Inspiron 3541               | Notebook    | [12d8081c29](https://linux-hardware.org/?probe=12d8081c29) | Jan 23, 2023 |
| Notebook      | W65_67SZ                    | Notebook    | [74d788dccb](https://linux-hardware.org/?probe=74d788dccb) | Jan 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [7e91e49912](https://linux-hardware.org/?probe=7e91e49912) | Jan 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3324fafe5a](https://linux-hardware.org/?probe=3324fafe5a) | Jan 23, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [8d876754f3](https://linux-hardware.org/?probe=8d876754f3) | Jan 23, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [f1f61785e5](https://linux-hardware.org/?probe=f1f61785e5) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [ec7d450cb0](https://linux-hardware.org/?probe=ec7d450cb0) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [d55b2b9507](https://linux-hardware.org/?probe=d55b2b9507) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [8716ca07da](https://linux-hardware.org/?probe=8716ca07da) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [21e1d557cc](https://linux-hardware.org/?probe=21e1d557cc) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [33c845f3a4](https://linux-hardware.org/?probe=33c845f3a4) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [24d2721a00](https://linux-hardware.org/?probe=24d2721a00) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [1e1066bd8b](https://linux-hardware.org/?probe=1e1066bd8b) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [7e636906b9](https://linux-hardware.org/?probe=7e636906b9) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [5aa076d0a5](https://linux-hardware.org/?probe=5aa076d0a5) | Jan 23, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [b5e6a74fcb](https://linux-hardware.org/?probe=b5e6a74fcb) | Jan 22, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4c4a17a3cf](https://linux-hardware.org/?probe=4c4a17a3cf) | Jan 22, 2023 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | Notebook    | [873bf3c874](https://linux-hardware.org/?probe=873bf3c874) | Jan 22, 2023 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | Notebook    | [68ff3c02cb](https://linux-hardware.org/?probe=68ff3c02cb) | Jan 22, 2023 |
| Gigabyte      | 8I945GMF                    | Desktop     | [2971006e43](https://linux-hardware.org/?probe=2971006e43) | Jan 21, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [82c74e5cca](https://linux-hardware.org/?probe=82c74e5cca) | Jan 21, 2023 |
| Acer          | Aspire 1640                 | Notebook    | [fb70812654](https://linux-hardware.org/?probe=fb70812654) | Jan 21, 2023 |
| ASUSTek       | N53SN                       | Notebook    | [bc8c82ca9a](https://linux-hardware.org/?probe=bc8c82ca9a) | Jan 21, 2023 |
| Dell          | Inspiron 5391               | Notebook    | [050e28c342](https://linux-hardware.org/?probe=050e28c342) | Jan 20, 2023 |
| HP            | ProLiant DL160 G6           | Server      | [576a73e761](https://linux-hardware.org/?probe=576a73e761) | Jan 20, 2023 |
| Dell          | Venue 11 Pro 7139           | Notebook    | [6c3528d4c0](https://linux-hardware.org/?probe=6c3528d4c0) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [76ab21d17b](https://linux-hardware.org/?probe=76ab21d17b) | Jan 20, 2023 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [6c83597890](https://linux-hardware.org/?probe=6c83597890) | Jan 19, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [fd8b8416ea](https://linux-hardware.org/?probe=fd8b8416ea) | Jan 19, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [80712a04ec](https://linux-hardware.org/?probe=80712a04ec) | Jan 18, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [d5ad4c9486](https://linux-hardware.org/?probe=d5ad4c9486) | Jan 17, 2023 |
| Dell          | Latitude E6440              | Notebook    | [f2b34c7c46](https://linux-hardware.org/?probe=f2b34c7c46) | Jan 17, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [c32c7f2d35](https://linux-hardware.org/?probe=c32c7f2d35) | Jan 17, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [a49a3ddeaa](https://linux-hardware.org/?probe=a49a3ddeaa) | Jan 17, 2023 |
| ASUSTek       | P5K-E                       | Desktop     | [2b7ce8a40b](https://linux-hardware.org/?probe=2b7ce8a40b) | Jan 17, 2023 |
| Dell          | 0PM2CW A04                  | Server      | [5f3e7922cd](https://linux-hardware.org/?probe=5f3e7922cd) | Jan 16, 2023 |
| Dell          | Inspiron N4010              | Notebook    | [7d03111ac0](https://linux-hardware.org/?probe=7d03111ac0) | Jan 16, 2023 |
| ASUSTek       | UX305CA                     | Notebook    | [b831308d6c](https://linux-hardware.org/?probe=b831308d6c) | Jan 16, 2023 |
| Dell          | Latitude E6420              | Notebook    | [3594f88292](https://linux-hardware.org/?probe=3594f88292) | Jan 15, 2023 |
| Dell          | 0PM2CW A04                  | Server      | [b4bc427969](https://linux-hardware.org/?probe=b4bc427969) | Jan 15, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d667bf6bb2](https://linux-hardware.org/?probe=d667bf6bb2) | Jan 15, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [0277ea7e50](https://linux-hardware.org/?probe=0277ea7e50) | Jan 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [251a926c19](https://linux-hardware.org/?probe=251a926c19) | Jan 14, 2023 |
| Gigabyte      | GA-790XT-USB3               | Desktop     | [22c3999607](https://linux-hardware.org/?probe=22c3999607) | Jan 14, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | Notebook    | [558f3d0d93](https://linux-hardware.org/?probe=558f3d0d93) | Jan 14, 2023 |
| ASUSTek       | A7K                         | Notebook    | [1303f158ab](https://linux-hardware.org/?probe=1303f158ab) | Jan 13, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b3711a9adc](https://linux-hardware.org/?probe=b3711a9adc) | Jan 13, 2023 |
| HP            | 873A A01                    | Mini pc     | [5c3be4e9aa](https://linux-hardware.org/?probe=5c3be4e9aa) | Jan 13, 2023 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [07a6ffe405](https://linux-hardware.org/?probe=07a6ffe405) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f2d7914ecc](https://linux-hardware.org/?probe=f2d7914ecc) | Jan 11, 2023 |
| Sony          | VPCEB3L9E                   | Notebook    | [5a7ea474fd](https://linux-hardware.org/?probe=5a7ea474fd) | Jan 11, 2023 |
| ASUSTek       | X555YI                      | Notebook    | [4968e51e0b](https://linux-hardware.org/?probe=4968e51e0b) | Jan 10, 2023 |
| Acer          | Aspire E5-771               | Notebook    | [dc397ff7f7](https://linux-hardware.org/?probe=dc397ff7f7) | Jan 09, 2023 |
| HP            | Pavilion dv2000 (RX554LA... | Notebook    | [2f9ff5256a](https://linux-hardware.org/?probe=2f9ff5256a) | Jan 08, 2023 |
| HP            | Pavilion dv2000 (RX554LA... | Notebook    | [b952438f2c](https://linux-hardware.org/?probe=b952438f2c) | Jan 08, 2023 |
| Acer          | Veriton N2620G              | Desktop     | [6345424cff](https://linux-hardware.org/?probe=6345424cff) | Jan 07, 2023 |
| Toshiba       | NB205                       | Notebook    | [3d6ba0d0b3](https://linux-hardware.org/?probe=3d6ba0d0b3) | Jan 07, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [b11276e9d3](https://linux-hardware.org/?probe=b11276e9d3) | Jan 07, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [51bbf252db](https://linux-hardware.org/?probe=51bbf252db) | Jan 06, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [daca90b2bb](https://linux-hardware.org/?probe=daca90b2bb) | Jan 05, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [74bacb92f5](https://linux-hardware.org/?probe=74bacb92f5) | Jan 05, 2023 |
| Dell          | Latitude 5590               | Notebook    | [f32e1efdef](https://linux-hardware.org/?probe=f32e1efdef) | Jan 05, 2023 |
| Samsung       | R530/R730                   | Notebook    | [dd26df5f4f](https://linux-hardware.org/?probe=dd26df5f4f) | Jan 05, 2023 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [ef5e737fd6](https://linux-hardware.org/?probe=ef5e737fd6) | Jan 04, 2023 |
| MiPi PC       | Mini PC                     | Mini pc     | [776c827bdb](https://linux-hardware.org/?probe=776c827bdb) | Jan 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [0ac727d853](https://linux-hardware.org/?probe=0ac727d853) | Jan 03, 2023 |
| Gigabyte      | J1800N-D2H                  | Desktop     | [f809473b20](https://linux-hardware.org/?probe=f809473b20) | Jan 03, 2023 |
| HP            | 339A                        | Desktop     | [c35711cb53](https://linux-hardware.org/?probe=c35711cb53) | Jan 03, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [14aa07b144](https://linux-hardware.org/?probe=14aa07b144) | Jan 02, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [0c30f220cb](https://linux-hardware.org/?probe=0c30f220cb) | Jan 02, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [da1db1e278](https://linux-hardware.org/?probe=da1db1e278) | Jan 02, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [f1494f113b](https://linux-hardware.org/?probe=f1494f113b) | Jan 01, 2023 |
| MSI           | MS-7142                     | Desktop     | [b267479470](https://linux-hardware.org/?probe=b267479470) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [79d4fe0592](https://linux-hardware.org/?probe=79d4fe0592) | Jan 01, 2023 |
| MSI           | MS-7142                     | Desktop     | [ad19259a27](https://linux-hardware.org/?probe=ad19259a27) | Jan 01, 2023 |
| ASUSTek       | P5GD2-VM                    | Desktop     | [13ccd15493](https://linux-hardware.org/?probe=13ccd15493) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [aeb6ecee74](https://linux-hardware.org/?probe=aeb6ecee74) | Jan 01, 2023 |
| Unknown       | Intel X79                   | Desktop     | [f26c05e261](https://linux-hardware.org/?probe=f26c05e261) | Dec 31, 2022 |
| TrekStor      | Primebook C11B              | Convertible | [e96819bd00](https://linux-hardware.org/?probe=e96819bd00) | Dec 31, 2022 |
| Dell          | Latitude E5440              | Notebook    | [9578ad1ea3](https://linux-hardware.org/?probe=9578ad1ea3) | Dec 31, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [cc1d0776d5](https://linux-hardware.org/?probe=cc1d0776d5) | Dec 30, 2022 |
| Lenovo        | ChiefRiver                  | Desktop     | [847a9e86cd](https://linux-hardware.org/?probe=847a9e86cd) | Dec 30, 2022 |
| HP            | 1998                        | Desktop     | [c3404205e3](https://linux-hardware.org/?probe=c3404205e3) | Dec 29, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [f0b4df8849](https://linux-hardware.org/?probe=f0b4df8849) | Dec 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [4a8c3f4014](https://linux-hardware.org/?probe=4a8c3f4014) | Dec 29, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [79f628b951](https://linux-hardware.org/?probe=79f628b951) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [15ec0001c5](https://linux-hardware.org/?probe=15ec0001c5) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [e84551a6eb](https://linux-hardware.org/?probe=e84551a6eb) | Dec 29, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [20a055c383](https://linux-hardware.org/?probe=20a055c383) | Dec 29, 2022 |
| ASRock        | H61M-ITX                    | Desktop     | [0ee8e9bb5b](https://linux-hardware.org/?probe=0ee8e9bb5b) | Dec 28, 2022 |
| Lenovo        | ThinkPad X230 23252S4       | Notebook    | [667dcc287e](https://linux-hardware.org/?probe=667dcc287e) | Dec 28, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [a4d55d44ed](https://linux-hardware.org/?probe=a4d55d44ed) | Dec 28, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [3548fd618d](https://linux-hardware.org/?probe=3548fd618d) | Dec 28, 2022 |
| HIGRADED      | W651UI                      | Notebook    | [66d9d484cd](https://linux-hardware.org/?probe=66d9d484cd) | Dec 27, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [23dc9112a8](https://linux-hardware.org/?probe=23dc9112a8) | Dec 27, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [2041ed5cba](https://linux-hardware.org/?probe=2041ed5cba) | Dec 27, 2022 |
| Acer          | Veriton NBU                 | Desktop     | [cca454d1bd](https://linux-hardware.org/?probe=cca454d1bd) | Dec 26, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [9bfeb5727a](https://linux-hardware.org/?probe=9bfeb5727a) | Dec 26, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [01466a6701](https://linux-hardware.org/?probe=01466a6701) | Dec 25, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [89b85889f9](https://linux-hardware.org/?probe=89b85889f9) | Dec 25, 2022 |
| ASRock        | N3700-ITX                   | Desktop     | [dc3f0d5062](https://linux-hardware.org/?probe=dc3f0d5062) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [3bf8001e85](https://linux-hardware.org/?probe=3bf8001e85) | Dec 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [8a5bfa5e66](https://linux-hardware.org/?probe=8a5bfa5e66) | Dec 24, 2022 |
| Unknown       | OA Q-ONE BRAND_V2.0         | Notebook    | [e554aa3d11](https://linux-hardware.org/?probe=e554aa3d11) | Dec 24, 2022 |
| Khadas        | VIM2                        | Soc         | [2ead7fb94b](https://linux-hardware.org/?probe=2ead7fb94b) | Dec 23, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| ASUSTek       | G60JX                       | Notebook    | [5e9b0bb890](https://linux-hardware.org/?probe=5e9b0bb890) | Dec 23, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [41ec48c0e5](https://linux-hardware.org/?probe=41ec48c0e5) | Dec 23, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [360e473cf9](https://linux-hardware.org/?probe=360e473cf9) | Dec 22, 2022 |
| Clevo         | P170EM                      | Notebook    | [3c8b8bd784](https://linux-hardware.org/?probe=3c8b8bd784) | Dec 22, 2022 |
| Dell          | 0YJPT1 A00                  | Desktop     | [f78b9b1a90](https://linux-hardware.org/?probe=f78b9b1a90) | Dec 22, 2022 |
| ASUSTek       | X555LF                      | Notebook    | [bed000b293](https://linux-hardware.org/?probe=bed000b293) | Dec 22, 2022 |
| HP            | 81C9                        | Desktop     | [cb40ddba01](https://linux-hardware.org/?probe=cb40ddba01) | Dec 22, 2022 |
| Acer          | Aspire A114-31              | Notebook    | [850c0c4a65](https://linux-hardware.org/?probe=850c0c4a65) | Dec 22, 2022 |
| ASUSTek       | 1215P                       | Notebook    | [a39ca1c22f](https://linux-hardware.org/?probe=a39ca1c22f) | Dec 21, 2022 |
| ASUSTek       | 1215P                       | Notebook    | [ed3dc80f1b](https://linux-hardware.org/?probe=ed3dc80f1b) | Dec 21, 2022 |
| Dell          | Latitude E5450              | Notebook    | [652099945b](https://linux-hardware.org/?probe=652099945b) | Dec 21, 2022 |
| HP            | Pavilion dv7                | Notebook    | [075b40bb9e](https://linux-hardware.org/?probe=075b40bb9e) | Dec 21, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [827696b95a](https://linux-hardware.org/?probe=827696b95a) | Dec 21, 2022 |
| HP            | 8594                        | Desktop     | [de0b36257e](https://linux-hardware.org/?probe=de0b36257e) | Dec 21, 2022 |
| Acer          | Aspire 7730ZG               | Notebook    | [bf9325456e](https://linux-hardware.org/?probe=bf9325456e) | Dec 20, 2022 |
| PCWare        | IPMH81G1                    | Desktop     | [3dc25592eb](https://linux-hardware.org/?probe=3dc25592eb) | Dec 20, 2022 |
| Dell          | Latitude E6430              | Notebook    | [643c90d5e1](https://linux-hardware.org/?probe=643c90d5e1) | Dec 20, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [82687103ac](https://linux-hardware.org/?probe=82687103ac) | Dec 20, 2022 |
| Dell          | Latitude E6430              | Notebook    | [ba280c7787](https://linux-hardware.org/?probe=ba280c7787) | Dec 20, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [7f18d05353](https://linux-hardware.org/?probe=7f18d05353) | Dec 20, 2022 |
| Lenovo        | ThinkPad Edge E545 20B20... | Notebook    | [0293f9b7c3](https://linux-hardware.org/?probe=0293f9b7c3) | Dec 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8862992776](https://linux-hardware.org/?probe=8862992776) | Dec 20, 2022 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [52b5b53173](https://linux-hardware.org/?probe=52b5b53173) | Dec 19, 2022 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [64972eb902](https://linux-hardware.org/?probe=64972eb902) | Dec 19, 2022 |
| Sony          | VPCS12V9E                   | Notebook    | [a353c5ef57](https://linux-hardware.org/?probe=a353c5ef57) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [224bdb435d](https://linux-hardware.org/?probe=224bdb435d) | Dec 19, 2022 |
| ASUSTek       | K75VJ                       | Notebook    | [a1b40660b5](https://linux-hardware.org/?probe=a1b40660b5) | Dec 18, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [6ea891850f](https://linux-hardware.org/?probe=6ea891850f) | Dec 18, 2022 |
| Lenovo        | FLEX-14IWL Laptop 81SQ      | Convertible | [f64e5ab064](https://linux-hardware.org/?probe=f64e5ab064) | Dec 18, 2022 |
| Acer          | Aspire A317-51K             | Notebook    | [b02c6dccc2](https://linux-hardware.org/?probe=b02c6dccc2) | Dec 17, 2022 |
| Packard Be... | PT890-8237A                 | Desktop     | [bb9e8d2cd7](https://linux-hardware.org/?probe=bb9e8d2cd7) | Dec 17, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [fdb9e278dd](https://linux-hardware.org/?probe=fdb9e278dd) | Dec 16, 2022 |
| Toshiba       | Satellite M70               | Notebook    | [9415a97254](https://linux-hardware.org/?probe=9415a97254) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [5c6f8cd52d](https://linux-hardware.org/?probe=5c6f8cd52d) | Dec 16, 2022 |
| Toshiba       | Satellite M70               | Notebook    | [79506873c1](https://linux-hardware.org/?probe=79506873c1) | Dec 15, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [87603a034e](https://linux-hardware.org/?probe=87603a034e) | Dec 15, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [0679db84af](https://linux-hardware.org/?probe=0679db84af) | Dec 14, 2022 |
| ECS           | CMPC                        | Notebook    | [53d853228f](https://linux-hardware.org/?probe=53d853228f) | Dec 14, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [282ef194e5](https://linux-hardware.org/?probe=282ef194e5) | Dec 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [c62c8e69b0](https://linux-hardware.org/?probe=c62c8e69b0) | Dec 12, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [51acd303f0](https://linux-hardware.org/?probe=51acd303f0) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [a9505fa3e4](https://linux-hardware.org/?probe=a9505fa3e4) | Dec 12, 2022 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [0cc39aa03c](https://linux-hardware.org/?probe=0cc39aa03c) | Dec 12, 2022 |
| HP            | 350 G1                      | Notebook    | [c15f80a386](https://linux-hardware.org/?probe=c15f80a386) | Dec 12, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [d65a8640af](https://linux-hardware.org/?probe=d65a8640af) | Dec 11, 2022 |
| HP            | 1497                        | Desktop     | [475049bb79](https://linux-hardware.org/?probe=475049bb79) | Dec 10, 2022 |
| Fusion5       | Lapbook T90B                | Notebook    | [73a67d82fd](https://linux-hardware.org/?probe=73a67d82fd) | Dec 10, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [ef403a3962](https://linux-hardware.org/?probe=ef403a3962) | Dec 10, 2022 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [7968282240](https://linux-hardware.org/?probe=7968282240) | Dec 10, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [aca71547f1](https://linux-hardware.org/?probe=aca71547f1) | Dec 08, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ce802653d4](https://linux-hardware.org/?probe=ce802653d4) | Dec 07, 2022 |
| Acer          | Aspire 5935                 | Notebook    | [01da97dae6](https://linux-hardware.org/?probe=01da97dae6) | Dec 07, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e2e47d2d43](https://linux-hardware.org/?probe=e2e47d2d43) | Dec 06, 2022 |
| Acer          | Aspire 5935                 | Notebook    | [44895b82f9](https://linux-hardware.org/?probe=44895b82f9) | Dec 05, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [57e7bb2427](https://linux-hardware.org/?probe=57e7bb2427) | Dec 05, 2022 |
| HP            | 2B34                        | Desktop     | [18ec4a2e66](https://linux-hardware.org/?probe=18ec4a2e66) | Dec 04, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [f6bb91c588](https://linux-hardware.org/?probe=f6bb91c588) | Dec 03, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [db5a886817](https://linux-hardware.org/?probe=db5a886817) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [3ee313dd51](https://linux-hardware.org/?probe=3ee313dd51) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [fde8194d5c](https://linux-hardware.org/?probe=fde8194d5c) | Dec 01, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [6d21dd6cea](https://linux-hardware.org/?probe=6d21dd6cea) | Nov 30, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | Notebook    | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [87d3950072](https://linux-hardware.org/?probe=87d3950072) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [89e340c4ec](https://linux-hardware.org/?probe=89e340c4ec) | Nov 30, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [bd30397e24](https://linux-hardware.org/?probe=bd30397e24) | Nov 29, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [3b4f834c63](https://linux-hardware.org/?probe=3b4f834c63) | Nov 29, 2022 |
| ASRock        | H270M-ITX/ac                | Desktop     | [dfc381d411](https://linux-hardware.org/?probe=dfc381d411) | Nov 29, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [472530d650](https://linux-hardware.org/?probe=472530d650) | Nov 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [762b81c49e](https://linux-hardware.org/?probe=762b81c49e) | Nov 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [01543655e9](https://linux-hardware.org/?probe=01543655e9) | Nov 29, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [1387bf11ea](https://linux-hardware.org/?probe=1387bf11ea) | Nov 28, 2022 |
| Google        | Akemi                       | Notebook    | [89c466ffd4](https://linux-hardware.org/?probe=89c466ffd4) | Nov 28, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [97cf5008bb](https://linux-hardware.org/?probe=97cf5008bb) | Nov 27, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [7d6eeaf95c](https://linux-hardware.org/?probe=7d6eeaf95c) | Nov 26, 2022 |
| ASUSTek       | 1002HA                      | Notebook    | [15d5eb998d](https://linux-hardware.org/?probe=15d5eb998d) | Nov 26, 2022 |
| Dell          | Latitude D610               | Notebook    | [437f7630fd](https://linux-hardware.org/?probe=437f7630fd) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| ASUSTek       | 1015CX                      | Notebook    | [89ec4e86f7](https://linux-hardware.org/?probe=89ec4e86f7) | Nov 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [bc3563401b](https://linux-hardware.org/?probe=bc3563401b) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | Notebook    | [46ec8527f5](https://linux-hardware.org/?probe=46ec8527f5) | Nov 25, 2022 |
| sunxi         | LeMaker Banana Pi           | Soc         | [56f65f30b3](https://linux-hardware.org/?probe=56f65f30b3) | Nov 24, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [199ed733ad](https://linux-hardware.org/?probe=199ed733ad) | Nov 24, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [9ed3a001c9](https://linux-hardware.org/?probe=9ed3a001c9) | Nov 23, 2022 |
| Positivo      | Mobile                      | Notebook    | [609b7ff8c9](https://linux-hardware.org/?probe=609b7ff8c9) | Nov 22, 2022 |
| Positivo      | Mobile                      | Notebook    | [5e1d512269](https://linux-hardware.org/?probe=5e1d512269) | Nov 22, 2022 |
| Unknown       | Unknown                     | Notebook    | [c119fbb804](https://linux-hardware.org/?probe=c119fbb804) | Nov 22, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [7399298a0f](https://linux-hardware.org/?probe=7399298a0f) | Nov 22, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [8eb4e40bf5](https://linux-hardware.org/?probe=8eb4e40bf5) | Nov 22, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [b1e3f41ed1](https://linux-hardware.org/?probe=b1e3f41ed1) | Nov 22, 2022 |
| Intel         | AB2L .A004                  | Mini pc     | [6124722e1f](https://linux-hardware.org/?probe=6124722e1f) | Nov 22, 2022 |
| HP            | 8540w                       | Notebook    | [3712bfe3cb](https://linux-hardware.org/?probe=3712bfe3cb) | Nov 21, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [452417fa68](https://linux-hardware.org/?probe=452417fa68) | Nov 21, 2022 |
| Lenovo        | ThinkPad L380 20M6S4E000    | Notebook    | [4f65299a92](https://linux-hardware.org/?probe=4f65299a92) | Nov 20, 2022 |
| Sony          | VPCEH25EN                   | Notebook    | [d9136e5b75](https://linux-hardware.org/?probe=d9136e5b75) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [a5cfd24a43](https://linux-hardware.org/?probe=a5cfd24a43) | Nov 18, 2022 |
| Dell          | Latitude 5490               | Notebook    | [70b8fb5e89](https://linux-hardware.org/?probe=70b8fb5e89) | Nov 18, 2022 |
| HP            | 245 G8 Notebook PC          | Notebook    | [4d4f9a0e10](https://linux-hardware.org/?probe=4d4f9a0e10) | Nov 17, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [288b53c471](https://linux-hardware.org/?probe=288b53c471) | Nov 16, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [23ec67e81b](https://linux-hardware.org/?probe=23ec67e81b) | Nov 16, 2022 |
| ASUSTek       | M4A88TD-M/USB3              | Desktop     | [8ff2384625](https://linux-hardware.org/?probe=8ff2384625) | Nov 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [c9a4863d1f](https://linux-hardware.org/?probe=c9a4863d1f) | Nov 15, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [5ffe9844bd](https://linux-hardware.org/?probe=5ffe9844bd) | Nov 15, 2022 |
| HP            | 1495                        | Desktop     | [e29c423a17](https://linux-hardware.org/?probe=e29c423a17) | Nov 15, 2022 |
| ASUSTek       | K53U                        | Notebook    | [e947ac0aab](https://linux-hardware.org/?probe=e947ac0aab) | Nov 14, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [8a2f5e3f03](https://linux-hardware.org/?probe=8a2f5e3f03) | Nov 14, 2022 |
| HP            | ProBook 6450b               | Notebook    | [ee3a2a2ef8](https://linux-hardware.org/?probe=ee3a2a2ef8) | Nov 14, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [c120112085](https://linux-hardware.org/?probe=c120112085) | Nov 13, 2022 |
| MSI           | MS-7309                     | Desktop     | [bd4d6c72e3](https://linux-hardware.org/?probe=bd4d6c72e3) | Nov 12, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [a5575e0c9d](https://linux-hardware.org/?probe=a5575e0c9d) | Nov 12, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [2e6b12e93d](https://linux-hardware.org/?probe=2e6b12e93d) | Nov 12, 2022 |
| HP            | Pavilion g6                 | Notebook    | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [161b81845e](https://linux-hardware.org/?probe=161b81845e) | Nov 11, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [b042e75495](https://linux-hardware.org/?probe=b042e75495) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [38f39ebccd](https://linux-hardware.org/?probe=38f39ebccd) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [d3bbc5ba4f](https://linux-hardware.org/?probe=d3bbc5ba4f) | Nov 11, 2022 |
| Lenovo        | ThinkPad T450s 20BWS33U0... | Notebook    | [ce3e5599ad](https://linux-hardware.org/?probe=ce3e5599ad) | Nov 10, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [ac93b84c08](https://linux-hardware.org/?probe=ac93b84c08) | Nov 10, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [27af8e61c5](https://linux-hardware.org/?probe=27af8e61c5) | Nov 10, 2022 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [01cb4ff120](https://linux-hardware.org/?probe=01cb4ff120) | Nov 10, 2022 |
| Lenovo        | ThinkCentre M70e 0830AC4    | Desktop     | [8eb9b40274](https://linux-hardware.org/?probe=8eb9b40274) | Nov 10, 2022 |
| ASUSTek       | B150M-C                     | Desktop     | [d2dd725b2e](https://linux-hardware.org/?probe=d2dd725b2e) | Nov 09, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| Dell          | 06FW8M A03                  | Server      | [2d4eead63b](https://linux-hardware.org/?probe=2d4eead63b) | Nov 08, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [70ba1bf558](https://linux-hardware.org/?probe=70ba1bf558) | Nov 08, 2022 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [0a1efcf166](https://linux-hardware.org/?probe=0a1efcf166) | Nov 08, 2022 |
| ASUSTek       | VM40B                       | Desktop     | [5736f2e2ae](https://linux-hardware.org/?probe=5736f2e2ae) | Nov 08, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [377df38ed7](https://linux-hardware.org/?probe=377df38ed7) | Nov 08, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [2796faab6c](https://linux-hardware.org/?probe=2796faab6c) | Nov 08, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [640298162b](https://linux-hardware.org/?probe=640298162b) | Nov 07, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [a39cc50a9a](https://linux-hardware.org/?probe=a39cc50a9a) | Nov 07, 2022 |
| Lenovo        | ThinkPad T440p 20AN0033R... | Notebook    | [7ca892ad44](https://linux-hardware.org/?probe=7ca892ad44) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | Notebook    | [0eef83e969](https://linux-hardware.org/?probe=0eef83e969) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | Notebook    | [3268b6af5f](https://linux-hardware.org/?probe=3268b6af5f) | Nov 06, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [f2d6eec645](https://linux-hardware.org/?probe=f2d6eec645) | Nov 06, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d37fe5f0b4](https://linux-hardware.org/?probe=d37fe5f0b4) | Nov 06, 2022 |
| MSI           | CSM-H87M-G43                | Desktop     | [43ffdafb80](https://linux-hardware.org/?probe=43ffdafb80) | Nov 06, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [98a3c2457d](https://linux-hardware.org/?probe=98a3c2457d) | Nov 05, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [1cf71a1b5c](https://linux-hardware.org/?probe=1cf71a1b5c) | Nov 05, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [e97900160b](https://linux-hardware.org/?probe=e97900160b) | Nov 05, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [2bf5248261](https://linux-hardware.org/?probe=2bf5248261) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [f1117abc19](https://linux-hardware.org/?probe=f1117abc19) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | Desktop     | [f60040c1b7](https://linux-hardware.org/?probe=f60040c1b7) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | Desktop     | [cd87b011a0](https://linux-hardware.org/?probe=cd87b011a0) | Nov 05, 2022 |
| Lenovo        | ThinkPad P51 20HH0014IX     | Notebook    | [e519495581](https://linux-hardware.org/?probe=e519495581) | Nov 04, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [dab31889f1](https://linux-hardware.org/?probe=dab31889f1) | Nov 04, 2022 |
| HP            | 8054                        | Desktop     | [0f1371d133](https://linux-hardware.org/?probe=0f1371d133) | Nov 03, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [423d3158cd](https://linux-hardware.org/?probe=423d3158cd) | Nov 03, 2022 |
| eMachines     | EL1358G                     | Desktop     | [48d6ba4c24](https://linux-hardware.org/?probe=48d6ba4c24) | Nov 03, 2022 |
| eMachines     | EL1358G                     | Desktop     | [1acbe713b6](https://linux-hardware.org/?probe=1acbe713b6) | Nov 03, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [fa6ec2e89c](https://linux-hardware.org/?probe=fa6ec2e89c) | Nov 03, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [3eae1f74ca](https://linux-hardware.org/?probe=3eae1f74ca) | Nov 03, 2022 |
| Dell          | Precision M6400             | Notebook    | [b98b318067](https://linux-hardware.org/?probe=b98b318067) | Nov 02, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [65231808f8](https://linux-hardware.org/?probe=65231808f8) | Nov 02, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [034414a73e](https://linux-hardware.org/?probe=034414a73e) | Nov 01, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [6f635f46c6](https://linux-hardware.org/?probe=6f635f46c6) | Nov 01, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [428b353c2c](https://linux-hardware.org/?probe=428b353c2c) | Nov 01, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7a29190887](https://linux-hardware.org/?probe=7a29190887) | Nov 01, 2022 |
| BCM           | MX110HD                     | Desktop     | [60c3eb0c5c](https://linux-hardware.org/?probe=60c3eb0c5c) | Nov 01, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [37f3d75177](https://linux-hardware.org/?probe=37f3d75177) | Oct 31, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [3af3091881](https://linux-hardware.org/?probe=3af3091881) | Oct 31, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [32b9b29220](https://linux-hardware.org/?probe=32b9b29220) | Oct 31, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| ECS           | H81H3-M4                    | Desktop     | [a4e0449df5](https://linux-hardware.org/?probe=a4e0449df5) | Oct 30, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [ad558f1150](https://linux-hardware.org/?probe=ad558f1150) | Oct 30, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [caefae88bf](https://linux-hardware.org/?probe=caefae88bf) | Oct 30, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [1c95e9ba40](https://linux-hardware.org/?probe=1c95e9ba40) | Oct 28, 2022 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | Desktop     | [5831a0d715](https://linux-hardware.org/?probe=5831a0d715) | Oct 28, 2022 |
| Lenovo        | ThinkPad W530 2438CTO       | Notebook    | [1915c9d3b0](https://linux-hardware.org/?probe=1915c9d3b0) | Oct 28, 2022 |
| Dell          | 0XHGV1 A00                  | Desktop     | [8fad928e72](https://linux-hardware.org/?probe=8fad928e72) | Oct 28, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [bbea359211](https://linux-hardware.org/?probe=bbea359211) | Oct 28, 2022 |
| ZOTAC         | ZBOX-EN72080V/EN72070V/E... | Mini pc     | [fef5f08978](https://linux-hardware.org/?probe=fef5f08978) | Oct 27, 2022 |
| Dell          | Latitude E6510              | Notebook    | [2cb824b444](https://linux-hardware.org/?probe=2cb824b444) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [73d5bfb13a](https://linux-hardware.org/?probe=73d5bfb13a) | Oct 27, 2022 |
| Gigabyte      | H370 HD3-CF                 | Desktop     | [275bc51aaf](https://linux-hardware.org/?probe=275bc51aaf) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [7290786792](https://linux-hardware.org/?probe=7290786792) | Oct 26, 2022 |
| Dell          | Latitude E6510              | Notebook    | [ddb0a31443](https://linux-hardware.org/?probe=ddb0a31443) | Oct 26, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [6ebaad0374](https://linux-hardware.org/?probe=6ebaad0374) | Oct 25, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [46d64e9947](https://linux-hardware.org/?probe=46d64e9947) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3c65639aad](https://linux-hardware.org/?probe=3c65639aad) | Oct 25, 2022 |
| Lenovo        | ThinkPad T460 20FMS08H00    | Notebook    | [13422369f7](https://linux-hardware.org/?probe=13422369f7) | Oct 25, 2022 |
| ASUSTek       | X555YI                      | Notebook    | [5d6562117a](https://linux-hardware.org/?probe=5d6562117a) | Oct 25, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [7027921568](https://linux-hardware.org/?probe=7027921568) | Oct 25, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [4ef2a348fc](https://linux-hardware.org/?probe=4ef2a348fc) | Oct 25, 2022 |
| Dell          | Inspiron N5030              | Notebook    | [dbc717a299](https://linux-hardware.org/?probe=dbc717a299) | Oct 25, 2022 |
| Intel         | DH61AG AAG23736-507         | Desktop     | [7fa3b3bc6a](https://linux-hardware.org/?probe=7fa3b3bc6a) | Oct 25, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [d10106fb33](https://linux-hardware.org/?probe=d10106fb33) | Oct 24, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [6398e45c99](https://linux-hardware.org/?probe=6398e45c99) | Oct 24, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [927bfd543c](https://linux-hardware.org/?probe=927bfd543c) | Oct 24, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [23a298a9a5](https://linux-hardware.org/?probe=23a298a9a5) | Oct 23, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [3e39042f59](https://linux-hardware.org/?probe=3e39042f59) | Oct 23, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [b7412d4350](https://linux-hardware.org/?probe=b7412d4350) | Oct 23, 2022 |
| HP            | 15                          | Notebook    | [2831771472](https://linux-hardware.org/?probe=2831771472) | Oct 22, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [5f1aeaf170](https://linux-hardware.org/?probe=5f1aeaf170) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [66418dda52](https://linux-hardware.org/?probe=66418dda52) | Oct 22, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [f5b8282e1f](https://linux-hardware.org/?probe=f5b8282e1f) | Oct 21, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [d575515de3](https://linux-hardware.org/?probe=d575515de3) | Oct 20, 2022 |
| ASUSTek       | N551ZU                      | Notebook    | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | Notebook    | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| Acer          | Aspire ES1-331              | Notebook    | [f5ace96d5d](https://linux-hardware.org/?probe=f5ace96d5d) | Oct 19, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [4de39d4a1c](https://linux-hardware.org/?probe=4de39d4a1c) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| Itautec       | ST 4273 ST-4273 Padrao 0... | Desktop     | [8c4af1707c](https://linux-hardware.org/?probe=8c4af1707c) | Oct 17, 2022 |
| Dell          | 500                         | Notebook    | [91b78b800a](https://linux-hardware.org/?probe=91b78b800a) | Oct 17, 2022 |
| Dell          | Latitude E5270              | Notebook    | [6f07cdee36](https://linux-hardware.org/?probe=6f07cdee36) | Oct 17, 2022 |
| MSI           | MS-7309                     | Desktop     | [9d4f0daf60](https://linux-hardware.org/?probe=9d4f0daf60) | Oct 16, 2022 |
| Samsung       | NC10                        | Notebook    | [1ea93f5095](https://linux-hardware.org/?probe=1ea93f5095) | Oct 16, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [4f03e84827](https://linux-hardware.org/?probe=4f03e84827) | Oct 16, 2022 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [ed6ebf5f98](https://linux-hardware.org/?probe=ed6ebf5f98) | Oct 16, 2022 |
| HP            | 198E                        | Desktop     | [47439edd0e](https://linux-hardware.org/?probe=47439edd0e) | Oct 15, 2022 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [d00f5feebf](https://linux-hardware.org/?probe=d00f5feebf) | Oct 15, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [a14ced18eb](https://linux-hardware.org/?probe=a14ced18eb) | Oct 15, 2022 |
| MSI           | GS40 6QE Phantom            | Notebook    | [76a55aa9f5](https://linux-hardware.org/?probe=76a55aa9f5) | Oct 14, 2022 |
| Dell          | 0N36HY A09                  | Server      | [464fda30a8](https://linux-hardware.org/?probe=464fda30a8) | Oct 14, 2022 |
| Lenovo        | ThinkPad T490 20N20046US    | Notebook    | [a698e6de4d](https://linux-hardware.org/?probe=a698e6de4d) | Oct 13, 2022 |
| eMachines     | eME528                      | Notebook    | [502802d50d](https://linux-hardware.org/?probe=502802d50d) | Oct 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [16f5eb4d25](https://linux-hardware.org/?probe=16f5eb4d25) | Oct 12, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| Dell          | Latitude E5470              | Notebook    | [eee260b733](https://linux-hardware.org/?probe=eee260b733) | Oct 12, 2022 |
| Dell          | Latitude E5470              | Notebook    | [3bbb87ee1b](https://linux-hardware.org/?probe=3bbb87ee1b) | Oct 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [a098b893f4](https://linux-hardware.org/?probe=a098b893f4) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [c3513de476](https://linux-hardware.org/?probe=c3513de476) | Oct 11, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [3598f82c1e](https://linux-hardware.org/?probe=3598f82c1e) | Oct 10, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | Notebook    | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [65039e3fdd](https://linux-hardware.org/?probe=65039e3fdd) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [1be1f8f36e](https://linux-hardware.org/?probe=1be1f8f36e) | Oct 09, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [6580d55237](https://linux-hardware.org/?probe=6580d55237) | Oct 09, 2022 |
| HP            | 255 G1                      | Notebook    | [fc9f63bfb6](https://linux-hardware.org/?probe=fc9f63bfb6) | Oct 08, 2022 |
| ASUSTek       | K50ID                       | Notebook    | [05e82f0dd5](https://linux-hardware.org/?probe=05e82f0dd5) | Oct 08, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [caf9a63020](https://linux-hardware.org/?probe=caf9a63020) | Oct 08, 2022 |
| Acer          | Aspire 5739G                | Notebook    | [9a380f66ea](https://linux-hardware.org/?probe=9a380f66ea) | Oct 08, 2022 |
| HP            | 1589                        | Desktop     | [d50afd3db1](https://linux-hardware.org/?probe=d50afd3db1) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537AF8       | Notebook    | [06dd00b171](https://linux-hardware.org/?probe=06dd00b171) | Oct 08, 2022 |
| Dell          | Latitude 5411               | Notebook    | [4bb05d639f](https://linux-hardware.org/?probe=4bb05d639f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30L0... | Notebook    | [ea6a5c970c](https://linux-hardware.org/?probe=ea6a5c970c) | Oct 07, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [b67d9b67e4](https://linux-hardware.org/?probe=b67d9b67e4) | Oct 06, 2022 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [20fb15fcbf](https://linux-hardware.org/?probe=20fb15fcbf) | Oct 06, 2022 |
| ASUSTek       | ET1612I                     | Desktop     | [91fea00cbf](https://linux-hardware.org/?probe=91fea00cbf) | Oct 06, 2022 |
| Acer          | EQ35M                       | Desktop     | [6a765c4673](https://linux-hardware.org/?probe=6a765c4673) | Oct 05, 2022 |
| Acer          | EQ35M                       | Desktop     | [4ad6d2e719](https://linux-hardware.org/?probe=4ad6d2e719) | Oct 05, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [b838d87a4b](https://linux-hardware.org/?probe=b838d87a4b) | Oct 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [0e52b51f87](https://linux-hardware.org/?probe=0e52b51f87) | Oct 05, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [dd6693ffa9](https://linux-hardware.org/?probe=dd6693ffa9) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [986b3c962e](https://linux-hardware.org/?probe=986b3c962e) | Oct 04, 2022 |
| Dell          | Precision 7560              | Notebook    | [877583cc90](https://linux-hardware.org/?probe=877583cc90) | Oct 04, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [50615f4621](https://linux-hardware.org/?probe=50615f4621) | Oct 04, 2022 |
| Acer          | Extensa 5230                | Notebook    | [8154485976](https://linux-hardware.org/?probe=8154485976) | Oct 04, 2022 |
| Dell          | 0WF810                      | Desktop     | [dd24119965](https://linux-hardware.org/?probe=dd24119965) | Oct 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [10e3123558](https://linux-hardware.org/?probe=10e3123558) | Oct 03, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [8125b49bea](https://linux-hardware.org/?probe=8125b49bea) | Oct 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [fc4e415fe4](https://linux-hardware.org/?probe=fc4e415fe4) | Oct 02, 2022 |
| Dell          | 500                         | Notebook    | [83c01aa11f](https://linux-hardware.org/?probe=83c01aa11f) | Oct 01, 2022 |
| Lenovo        | B70-80 80MR                 | Notebook    | [69aec9e100](https://linux-hardware.org/?probe=69aec9e100) | Oct 01, 2022 |
| HP            | Notebook                    | Notebook    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [ddf1904011](https://linux-hardware.org/?probe=ddf1904011) | Oct 01, 2022 |
| Acer          | Aspire A315-55G             | Notebook    | [77605e313d](https://linux-hardware.org/?probe=77605e313d) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Sony          | SVE1512C6EB                 | Notebook    | [c47a3a5bd7](https://linux-hardware.org/?probe=c47a3a5bd7) | Sep 30, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | Notebook    | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| Dell          | Latitude 5420               | Notebook    | [36ddd1d6d7](https://linux-hardware.org/?probe=36ddd1d6d7) | Sep 30, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [1001ccbbaf](https://linux-hardware.org/?probe=1001ccbbaf) | Sep 30, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [ba607b91e0](https://linux-hardware.org/?probe=ba607b91e0) | Sep 29, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [dcdafbbd9b](https://linux-hardware.org/?probe=dcdafbbd9b) | Sep 28, 2022 |
| Gigabyte      | H81M-D2W                    | Desktop     | [467845e1c1](https://linux-hardware.org/?probe=467845e1c1) | Sep 28, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5479c35130](https://linux-hardware.org/?probe=5479c35130) | Sep 28, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [0a8aed635a](https://linux-hardware.org/?probe=0a8aed635a) | Sep 28, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [834ef0ec59](https://linux-hardware.org/?probe=834ef0ec59) | Sep 27, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [564d385b61](https://linux-hardware.org/?probe=564d385b61) | Sep 27, 2022 |
| Dell          | CS24-TY                     | Server      | [029e2bdb60](https://linux-hardware.org/?probe=029e2bdb60) | Sep 27, 2022 |
| ASRock        | 775Dual-VSTA                | Desktop     | [9509fb65dd](https://linux-hardware.org/?probe=9509fb65dd) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [41cc3cdcfd](https://linux-hardware.org/?probe=41cc3cdcfd) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [d6924eb78d](https://linux-hardware.org/?probe=d6924eb78d) | Sep 26, 2022 |
| MSI           | H170M PRO-VDH               | Desktop     | [f7254adff2](https://linux-hardware.org/?probe=f7254adff2) | Sep 25, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [c7920c2e68](https://linux-hardware.org/?probe=c7920c2e68) | Sep 24, 2022 |
| Packard Be... | EasyNote MH45               | Notebook    | [c312580997](https://linux-hardware.org/?probe=c312580997) | Sep 24, 2022 |
| Unknown       | Unknown                     | Notebook    | [63b1596d63](https://linux-hardware.org/?probe=63b1596d63) | Sep 24, 2022 |
| Toshiba       | Satellite C55D-B            | Notebook    | [5b2029b4d3](https://linux-hardware.org/?probe=5b2029b4d3) | Sep 24, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [3f6203e550](https://linux-hardware.org/?probe=3f6203e550) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5588f73920](https://linux-hardware.org/?probe=5588f73920) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a83e57d8c1](https://linux-hardware.org/?probe=a83e57d8c1) | Sep 23, 2022 |
| Tactus        | GeoBook 140                 | Notebook    | [7d8700d0e1](https://linux-hardware.org/?probe=7d8700d0e1) | Sep 23, 2022 |
| Dell          | Latitude 5411               | Notebook    | [018a9c569a](https://linux-hardware.org/?probe=018a9c569a) | Sep 23, 2022 |
| ASUSTek       | P6T                         | Desktop     | [612682c52d](https://linux-hardware.org/?probe=612682c52d) | Sep 23, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [c3a88ed62d](https://linux-hardware.org/?probe=c3a88ed62d) | Sep 22, 2022 |
| Lenovo        | ThinkPad P51s 20HCS00F00    | Notebook    | [5f0dc19f55](https://linux-hardware.org/?probe=5f0dc19f55) | Sep 22, 2022 |
| Lenovo        | ThinkPad T61 7659AB7        | Notebook    | [aa07f9c271](https://linux-hardware.org/?probe=aa07f9c271) | Sep 20, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [966ae734c2](https://linux-hardware.org/?probe=966ae734c2) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61p 6457A24       | Notebook    | [d98e9a64bd](https://linux-hardware.org/?probe=d98e9a64bd) | Sep 20, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [73c35ad64a](https://linux-hardware.org/?probe=73c35ad64a) | Sep 20, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [4b91f7a270](https://linux-hardware.org/?probe=4b91f7a270) | Sep 19, 2022 |
| Dell          | Precision 7750              | Notebook    | [ced8b5a7b2](https://linux-hardware.org/?probe=ced8b5a7b2) | Sep 19, 2022 |
| Lenovo        | ThinkPad X220 42918F6       | Notebook    | [69dda668fc](https://linux-hardware.org/?probe=69dda668fc) | Sep 18, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e2b4056812](https://linux-hardware.org/?probe=e2b4056812) | Sep 18, 2022 |
| ASRock        | 960GC-GS FX                 | Desktop     | [3e40742ff0](https://linux-hardware.org/?probe=3e40742ff0) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| ASUSTek       | ET1612I                     | Desktop     | [0ddd9554cc](https://linux-hardware.org/?probe=0ddd9554cc) | Sep 16, 2022 |
| Pine Micro... | Pine64 Rock64               | Soc         | [dbd6ac01d6](https://linux-hardware.org/?probe=dbd6ac01d6) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [588c189149](https://linux-hardware.org/?probe=588c189149) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [4b94d21772](https://linux-hardware.org/?probe=4b94d21772) | Sep 16, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [d852f09d43](https://linux-hardware.org/?probe=d852f09d43) | Sep 15, 2022 |
| Dell          | Latitude 7490               | Notebook    | [ce54bcd741](https://linux-hardware.org/?probe=ce54bcd741) | Sep 15, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [a0bdfffa04](https://linux-hardware.org/?probe=a0bdfffa04) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [196e6b048b](https://linux-hardware.org/?probe=196e6b048b) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [8e95a850da](https://linux-hardware.org/?probe=8e95a850da) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [499d354033](https://linux-hardware.org/?probe=499d354033) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [a830a7b6e5](https://linux-hardware.org/?probe=a830a7b6e5) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [19ba71f923](https://linux-hardware.org/?probe=19ba71f923) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [ad888e4455](https://linux-hardware.org/?probe=ad888e4455) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [d35bf4c513](https://linux-hardware.org/?probe=d35bf4c513) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [dce51bb6d6](https://linux-hardware.org/?probe=dce51bb6d6) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [3bc232858d](https://linux-hardware.org/?probe=3bc232858d) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [ca79460771](https://linux-hardware.org/?probe=ca79460771) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [1e24243624](https://linux-hardware.org/?probe=1e24243624) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [b0625e01e3](https://linux-hardware.org/?probe=b0625e01e3) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [f97cd53683](https://linux-hardware.org/?probe=f97cd53683) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [cd3fc03204](https://linux-hardware.org/?probe=cd3fc03204) | Sep 15, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [6d40add21a](https://linux-hardware.org/?probe=6d40add21a) | Sep 15, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [dd55f6960d](https://linux-hardware.org/?probe=dd55f6960d) | Sep 15, 2022 |
| Dell          | Latitude 7420               | Convertible | [5d119f6255](https://linux-hardware.org/?probe=5d119f6255) | Sep 14, 2022 |
| Dell          | 0DR845                      | Desktop     | [158b3832bc](https://linux-hardware.org/?probe=158b3832bc) | Sep 13, 2022 |
| Dell          | Precision 5540              | Notebook    | [229337f709](https://linux-hardware.org/?probe=229337f709) | Sep 13, 2022 |
| ASUSTek       | K30BD                       | Desktop     | [d6daf0e1f8](https://linux-hardware.org/?probe=d6daf0e1f8) | Sep 13, 2022 |
| HP            | 1000                        | Notebook    | [65024f3d7a](https://linux-hardware.org/?probe=65024f3d7a) | Sep 13, 2022 |
| ASUSTek       | H61M-C                      | Desktop     | [bb07dfab63](https://linux-hardware.org/?probe=bb07dfab63) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [e59aa2e1d5](https://linux-hardware.org/?probe=e59aa2e1d5) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [930da2e105](https://linux-hardware.org/?probe=930da2e105) | Sep 13, 2022 |
| Dell          | 0DR845                      | Desktop     | [f65bf44380](https://linux-hardware.org/?probe=f65bf44380) | Sep 13, 2022 |
| Gigabyte      | H510M S2H                   | Desktop     | [f004b06a17](https://linux-hardware.org/?probe=f004b06a17) | Sep 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3f56f510f8](https://linux-hardware.org/?probe=3f56f510f8) | Sep 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [940507a1ec](https://linux-hardware.org/?probe=940507a1ec) | Sep 12, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [afd2b6555e](https://linux-hardware.org/?probe=afd2b6555e) | Sep 12, 2022 |
| ASUSTek       | X453SA                      | Notebook    | [1446eda5e9](https://linux-hardware.org/?probe=1446eda5e9) | Sep 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7b7a1cfeb9](https://linux-hardware.org/?probe=7b7a1cfeb9) | Sep 11, 2022 |
| Dell          | 03NVJ6 A01                  | Desktop     | [3f51b6da48](https://linux-hardware.org/?probe=3f51b6da48) | Sep 10, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [d0e5863756](https://linux-hardware.org/?probe=d0e5863756) | Sep 10, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [bf1aba4ebe](https://linux-hardware.org/?probe=bf1aba4ebe) | Sep 10, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [33faaf5341](https://linux-hardware.org/?probe=33faaf5341) | Sep 10, 2022 |
| Dell          | 0R092H                      | Desktop     | [a22af2bad5](https://linux-hardware.org/?probe=a22af2bad5) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| ASRock        | Q1900-ITX                   | Desktop     | [738bae7e52](https://linux-hardware.org/?probe=738bae7e52) | Sep 08, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [31a50780b4](https://linux-hardware.org/?probe=31a50780b4) | Sep 08, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [2737c0fd67](https://linux-hardware.org/?probe=2737c0fd67) | Sep 08, 2022 |
| Nvidia        | Tegra                       | Soc         | [bf3fee013b](https://linux-hardware.org/?probe=bf3fee013b) | Sep 08, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [f714986404](https://linux-hardware.org/?probe=f714986404) | Sep 08, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [b0412cee20](https://linux-hardware.org/?probe=b0412cee20) | Sep 07, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [31fdd16d2f](https://linux-hardware.org/?probe=31fdd16d2f) | Sep 07, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [24647846ee](https://linux-hardware.org/?probe=24647846ee) | Sep 06, 2022 |
| MSI           | MS-7387                     | Desktop     | [1f49477abf](https://linux-hardware.org/?probe=1f49477abf) | Sep 06, 2022 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [7649a53341](https://linux-hardware.org/?probe=7649a53341) | Sep 06, 2022 |
| Dell          | Latitude 9520               | Notebook    | [04188fb6c2](https://linux-hardware.org/?probe=04188fb6c2) | Sep 06, 2022 |
| Dell          | 0NV0M7 A02                  | Desktop     | [23024b776e](https://linux-hardware.org/?probe=23024b776e) | Sep 06, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [989e0d5d57](https://linux-hardware.org/?probe=989e0d5d57) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [f51b1f139e](https://linux-hardware.org/?probe=f51b1f139e) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | Notebook    | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| ASUSTek       | M4A78T-E                    | Desktop     | [6c0537c32c](https://linux-hardware.org/?probe=6c0537c32c) | Sep 05, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [dd775ffe8f](https://linux-hardware.org/?probe=dd775ffe8f) | Sep 05, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [668995f3ff](https://linux-hardware.org/?probe=668995f3ff) | Sep 04, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [1bd6f2ba6f](https://linux-hardware.org/?probe=1bd6f2ba6f) | Sep 04, 2022 |
| Google        | Kip                         | Notebook    | [e92d971d5e](https://linux-hardware.org/?probe=e92d971d5e) | Sep 04, 2022 |
| ASUSTek       | K30BD                       | Desktop     | [6042bda5d7](https://linux-hardware.org/?probe=6042bda5d7) | Sep 03, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Google        | Reks                        | Notebook    | [d88eecb32d](https://linux-hardware.org/?probe=d88eecb32d) | Sep 03, 2022 |
| Clientron     | C800                        | Mini pc     | [18fcb4170b](https://linux-hardware.org/?probe=18fcb4170b) | Sep 03, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [506f9da93b](https://linux-hardware.org/?probe=506f9da93b) | Sep 03, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [8add31fdfe](https://linux-hardware.org/?probe=8add31fdfe) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [c3212ee5a3](https://linux-hardware.org/?probe=c3212ee5a3) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [673b33ac0c](https://linux-hardware.org/?probe=673b33ac0c) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [18a2d69632](https://linux-hardware.org/?probe=18a2d69632) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [965107cf86](https://linux-hardware.org/?probe=965107cf86) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [d8f5734dd8](https://linux-hardware.org/?probe=d8f5734dd8) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [b2f37a3080](https://linux-hardware.org/?probe=b2f37a3080) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [91857942dd](https://linux-hardware.org/?probe=91857942dd) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [940fb9c208](https://linux-hardware.org/?probe=940fb9c208) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [10315fa577](https://linux-hardware.org/?probe=10315fa577) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [aedc37e8e4](https://linux-hardware.org/?probe=aedc37e8e4) | Sep 02, 2022 |
| Acer          | Aspire A315-31              | Notebook    | [21d3a4bd56](https://linux-hardware.org/?probe=21d3a4bd56) | Sep 02, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [9f80ee3a09](https://linux-hardware.org/?probe=9f80ee3a09) | Sep 01, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [efc46d8d23](https://linux-hardware.org/?probe=efc46d8d23) | Sep 01, 2022 |
| HP            | 8433 11                     | Desktop     | [00868f25c6](https://linux-hardware.org/?probe=00868f25c6) | Aug 31, 2022 |
| sunxi         | Allwinner sun7i (A20) Fa... | Soc         | [632a8a0ad8](https://linux-hardware.org/?probe=632a8a0ad8) | Aug 30, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [7e839a0ef4](https://linux-hardware.org/?probe=7e839a0ef4) | Aug 30, 2022 |
| Acer          | Aspire E5-771G              | Notebook    | [76803c2532](https://linux-hardware.org/?probe=76803c2532) | Aug 30, 2022 |
| DNI           | SNDTP-1513N 5508015890      | Desktop     | [9570ee789c](https://linux-hardware.org/?probe=9570ee789c) | Aug 30, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [b54e74887f](https://linux-hardware.org/?probe=b54e74887f) | Aug 29, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [9bdae9239f](https://linux-hardware.org/?probe=9bdae9239f) | Aug 29, 2022 |
| Acer          | Aspire E5-771G              | Notebook    | [52cc79c6d9](https://linux-hardware.org/?probe=52cc79c6d9) | Aug 29, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [a8100fcf41](https://linux-hardware.org/?probe=a8100fcf41) | Aug 29, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [f8f42b0857](https://linux-hardware.org/?probe=f8f42b0857) | Aug 29, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [e692fe97cb](https://linux-hardware.org/?probe=e692fe97cb) | Aug 28, 2022 |
| Intel         | H61                         | Desktop     | [c829101789](https://linux-hardware.org/?probe=c829101789) | Aug 27, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [b9953ab67e](https://linux-hardware.org/?probe=b9953ab67e) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [f725a87544](https://linux-hardware.org/?probe=f725a87544) | Aug 27, 2022 |
| Lenovo        | 14w 81MQ000JUS              | Notebook    | [d71f12bede](https://linux-hardware.org/?probe=d71f12bede) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [8a689fc0fd](https://linux-hardware.org/?probe=8a689fc0fd) | Aug 27, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [7bf3626764](https://linux-hardware.org/?probe=7bf3626764) | Aug 25, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [5bb7561235](https://linux-hardware.org/?probe=5bb7561235) | Aug 25, 2022 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | Notebook    | [d269aaa456](https://linux-hardware.org/?probe=d269aaa456) | Aug 25, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [c37bc2a345](https://linux-hardware.org/?probe=c37bc2a345) | Aug 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [92be7f3368](https://linux-hardware.org/?probe=92be7f3368) | Aug 24, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [5652f2c73d](https://linux-hardware.org/?probe=5652f2c73d) | Aug 24, 2022 |
| HP            | 844C                        | Desktop     | [b56856200e](https://linux-hardware.org/?probe=b56856200e) | Aug 23, 2022 |
| Lenovo        | 14w 81MQ000JUS              | Notebook    | [1ff769c6ef](https://linux-hardware.org/?probe=1ff769c6ef) | Aug 23, 2022 |
| Gigabyte      | H370 HD3-CF                 | Desktop     | [3f06afc812](https://linux-hardware.org/?probe=3f06afc812) | Aug 21, 2022 |
| Acer          | Unknown                     | Notebook    | [c35afdde00](https://linux-hardware.org/?probe=c35afdde00) | Aug 21, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5dabf74b7f](https://linux-hardware.org/?probe=5dabf74b7f) | Aug 21, 2022 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [38fd87d37c](https://linux-hardware.org/?probe=38fd87d37c) | Aug 21, 2022 |
| Lenovo        | ThinkPad X220 4291V1C       | Notebook    | [8ab56e33c4](https://linux-hardware.org/?probe=8ab56e33c4) | Aug 21, 2022 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [d9ff119ebe](https://linux-hardware.org/?probe=d9ff119ebe) | Aug 21, 2022 |
| Lenovo        | ThinkPad T480 20L5000BGE    | Notebook    | [dd53f23249](https://linux-hardware.org/?probe=dd53f23249) | Aug 20, 2022 |
| MSI           | X370 KRAIT GAMING           | Desktop     | [ea80c11a16](https://linux-hardware.org/?probe=ea80c11a16) | Aug 20, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [ed1f055157](https://linux-hardware.org/?probe=ed1f055157) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [764eaea2ba](https://linux-hardware.org/?probe=764eaea2ba) | Aug 19, 2022 |
| Packard Be... | EasyNote TJ66               | Notebook    | [96c3144e93](https://linux-hardware.org/?probe=96c3144e93) | Aug 19, 2022 |
| Dell          | 07T4MC A06                  | Desktop     | [d6c22de1e9](https://linux-hardware.org/?probe=d6c22de1e9) | Aug 18, 2022 |
| eMachines     | ET1350                      | Desktop     | [96e9f7aba7](https://linux-hardware.org/?probe=96e9f7aba7) | Aug 18, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [015ccc4b06](https://linux-hardware.org/?probe=015ccc4b06) | Aug 18, 2022 |
| HP            | 8591                        | Desktop     | [4235eb97c1](https://linux-hardware.org/?probe=4235eb97c1) | Aug 18, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [c4336ae88d](https://linux-hardware.org/?probe=c4336ae88d) | Aug 17, 2022 |
| Dell          | 0YXT71 A00                  | Desktop     | [def7e10c65](https://linux-hardware.org/?probe=def7e10c65) | Aug 17, 2022 |
| Dell          | 0RY007                      | Desktop     | [a863b6949c](https://linux-hardware.org/?probe=a863b6949c) | Aug 16, 2022 |
| ASUSTek       | K53TA                       | Notebook    | [db6525efb3](https://linux-hardware.org/?probe=db6525efb3) | Aug 15, 2022 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [ea40fd79f3](https://linux-hardware.org/?probe=ea40fd79f3) | Aug 15, 2022 |
| ASUSTek       | K84C                        | Notebook    | [c19b238bcf](https://linux-hardware.org/?probe=c19b238bcf) | Aug 15, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [b98fcab3a6](https://linux-hardware.org/?probe=b98fcab3a6) | Aug 15, 2022 |
| Lenovo        | ThinkPad T460s 20FAS0Q90... | Notebook    | [644c7518e9](https://linux-hardware.org/?probe=644c7518e9) | Aug 14, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| Dell          | 0RY007                      | Desktop     | [592206f3e1](https://linux-hardware.org/?probe=592206f3e1) | Aug 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [fd06db829d](https://linux-hardware.org/?probe=fd06db829d) | Aug 14, 2022 |
| Panasonic     | CF-31XEUAXMF                | Notebook    | [914e54f984](https://linux-hardware.org/?probe=914e54f984) | Aug 13, 2022 |
| Toshiba       | PT10F                       | Notebook    | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Dell          | 0RY007                      | Desktop     | [05edd2876d](https://linux-hardware.org/?probe=05edd2876d) | Aug 12, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [5bb07e1a28](https://linux-hardware.org/?probe=5bb07e1a28) | Aug 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [23005caccd](https://linux-hardware.org/?probe=23005caccd) | Aug 11, 2022 |
| eMachines     | EL1358G                     | Desktop     | [eebc968f87](https://linux-hardware.org/?probe=eebc968f87) | Aug 11, 2022 |
| ASRock        | X58 Extreme3                | Desktop     | [81f68d4fc7](https://linux-hardware.org/?probe=81f68d4fc7) | Aug 10, 2022 |
| OEM_MB        | NARRA3                      | Desktop     | [4574011966](https://linux-hardware.org/?probe=4574011966) | Aug 09, 2022 |
| OEM_MB        | NARRA3                      | Desktop     | [8454f0f091](https://linux-hardware.org/?probe=8454f0f091) | Aug 09, 2022 |
| Dell          | System XPS L502X            | Notebook    | [1453afc507](https://linux-hardware.org/?probe=1453afc507) | Aug 09, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | Notebook    | [aed42791cd](https://linux-hardware.org/?probe=aed42791cd) | Aug 09, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [20a93d57e6](https://linux-hardware.org/?probe=20a93d57e6) | Aug 08, 2022 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [0fadd2421f](https://linux-hardware.org/?probe=0fadd2421f) | Aug 08, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [15522c32d7](https://linux-hardware.org/?probe=15522c32d7) | Aug 06, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6JY0... | Notebook    | [7d85d4f00b](https://linux-hardware.org/?probe=7d85d4f00b) | Aug 06, 2022 |
| Render        | NOTEBOOK Revision A         | Notebook    | [90a540652f](https://linux-hardware.org/?probe=90a540652f) | Aug 06, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [64b08b679f](https://linux-hardware.org/?probe=64b08b679f) | Aug 05, 2022 |
| ASUSTek       | 1015CX                      | Notebook    | [f8d358f521](https://linux-hardware.org/?probe=f8d358f521) | Aug 05, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [32a99db93e](https://linux-hardware.org/?probe=32a99db93e) | Aug 04, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [8b0237ee5e](https://linux-hardware.org/?probe=8b0237ee5e) | Aug 03, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | Notebook    | [fdd30ffa23](https://linux-hardware.org/?probe=fdd30ffa23) | Aug 03, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [b81c8578b9](https://linux-hardware.org/?probe=b81c8578b9) | Aug 03, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [4b8ed45c90](https://linux-hardware.org/?probe=4b8ed45c90) | Aug 03, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [8aa899fe67](https://linux-hardware.org/?probe=8aa899fe67) | Aug 02, 2022 |
| GMKtec        | NucBox5                     | Notebook    | [5023bc1773](https://linux-hardware.org/?probe=5023bc1773) | Aug 02, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [e512f0884d](https://linux-hardware.org/?probe=e512f0884d) | Aug 01, 2022 |
| Dell          | Inspiron 5748               | Notebook    | [9113ee6d54](https://linux-hardware.org/?probe=9113ee6d54) | Aug 01, 2022 |
| Unknown       | Unknown                     | Notebook    | [50153bd9ff](https://linux-hardware.org/?probe=50153bd9ff) | Aug 01, 2022 |
| HP            | Pavilion dv2600             | Notebook    | [87651d6efc](https://linux-hardware.org/?probe=87651d6efc) | Jul 31, 2022 |
| Unknown       | Unknown                     | Notebook    | [aa0c007709](https://linux-hardware.org/?probe=aa0c007709) | Jul 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [745f6815cb](https://linux-hardware.org/?probe=745f6815cb) | Jul 30, 2022 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [7325fb8135](https://linux-hardware.org/?probe=7325fb8135) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [01bcafef3c](https://linux-hardware.org/?probe=01bcafef3c) | Jul 30, 2022 |
| Alienware     | 17 R4                       | Notebook    | [ae2cd7095b](https://linux-hardware.org/?probe=ae2cd7095b) | Jul 29, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [bd5b812271](https://linux-hardware.org/?probe=bd5b812271) | Jul 29, 2022 |
| Dell          | Vostro 3700                 | Notebook    | [0a4b552d69](https://linux-hardware.org/?probe=0a4b552d69) | Jul 28, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [d435057109](https://linux-hardware.org/?probe=d435057109) | Jul 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9a97caa028](https://linux-hardware.org/?probe=9a97caa028) | Jul 28, 2022 |
| Schenker      | WORK (Early 2021)           | Notebook    | [8666cc396a](https://linux-hardware.org/?probe=8666cc396a) | Jul 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d00325cd68](https://linux-hardware.org/?probe=d00325cd68) | Jul 28, 2022 |
| ASUSTek       | P5QL/EPU                    | Desktop     | [797c3b1dc2](https://linux-hardware.org/?probe=797c3b1dc2) | Jul 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [da54317b9a](https://linux-hardware.org/?probe=da54317b9a) | Jul 27, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [611f1d79e3](https://linux-hardware.org/?probe=611f1d79e3) | Jul 26, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [4d6af73032](https://linux-hardware.org/?probe=4d6af73032) | Jul 26, 2022 |
| LG Electro... | LE50-5BC6H1                 | Notebook    | [010123b7d5](https://linux-hardware.org/?probe=010123b7d5) | Jul 26, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c380d02bbf](https://linux-hardware.org/?probe=c380d02bbf) | Jul 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cc16c01563](https://linux-hardware.org/?probe=cc16c01563) | Jul 25, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [a27a0707b8](https://linux-hardware.org/?probe=a27a0707b8) | Jul 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9b841f9332](https://linux-hardware.org/?probe=9b841f9332) | Jul 25, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [4db419918b](https://linux-hardware.org/?probe=4db419918b) | Jul 25, 2022 |
| PCWare        | IPX1800E2                   | Desktop     | [4426727633](https://linux-hardware.org/?probe=4426727633) | Jul 24, 2022 |
| Toshiba       | NB205                       | Notebook    | [2dd373f150](https://linux-hardware.org/?probe=2dd373f150) | Jul 23, 2022 |
| ASUSTek       | P4B-M                       | Desktop     | [a193b562fa](https://linux-hardware.org/?probe=a193b562fa) | Jul 22, 2022 |
| ASUSTek       | P4B-M                       | Desktop     | [5128fcd55d](https://linux-hardware.org/?probe=5128fcd55d) | Jul 22, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [3813cc04d1](https://linux-hardware.org/?probe=3813cc04d1) | Jul 22, 2022 |
| Dell          | Inspiron N5030              | Notebook    | [3ae520c245](https://linux-hardware.org/?probe=3ae520c245) | Jul 22, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [75f71928fe](https://linux-hardware.org/?probe=75f71928fe) | Jul 21, 2022 |
| MSI           | U-100 Ver.001               | Notebook    | [b5b7407958](https://linux-hardware.org/?probe=b5b7407958) | Jul 20, 2022 |
| MSI           | U-100 Ver.001               | Notebook    | [819488216f](https://linux-hardware.org/?probe=819488216f) | Jul 20, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [ba0058e96e](https://linux-hardware.org/?probe=ba0058e96e) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [75b4088788](https://linux-hardware.org/?probe=75b4088788) | Jul 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e2cd5c8d4b](https://linux-hardware.org/?probe=e2cd5c8d4b) | Jul 20, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [5889a04334](https://linux-hardware.org/?probe=5889a04334) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [3c2afd2b5e](https://linux-hardware.org/?probe=3c2afd2b5e) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| ASUSTek       | FX503VM                     | Notebook    | [47c70e3628](https://linux-hardware.org/?probe=47c70e3628) | Jul 19, 2022 |
| Dell          | Latitude D430               | Notebook    | [7ae462d6f7](https://linux-hardware.org/?probe=7ae462d6f7) | Jul 18, 2022 |
| Dell          | 0PM2CW A04                  | Server      | [8162a1a915](https://linux-hardware.org/?probe=8162a1a915) | Jul 17, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | Notebook    | [117f9a585b](https://linux-hardware.org/?probe=117f9a585b) | Jul 17, 2022 |
| ASUSTek       | U30Jc                       | Notebook    | [3a6a0ec169](https://linux-hardware.org/?probe=3a6a0ec169) | Jul 17, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | Notebook    | [e408c1236c](https://linux-hardware.org/?probe=e408c1236c) | Jul 17, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d5a64d7baa](https://linux-hardware.org/?probe=d5a64d7baa) | Jul 16, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [528f781464](https://linux-hardware.org/?probe=528f781464) | Jul 16, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [13d38a6632](https://linux-hardware.org/?probe=13d38a6632) | Jul 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [a6ae556389](https://linux-hardware.org/?probe=a6ae556389) | Jul 16, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [4773de66cf](https://linux-hardware.org/?probe=4773de66cf) | Jul 15, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [dd45175b9d](https://linux-hardware.org/?probe=dd45175b9d) | Jul 15, 2022 |
| HP            | 1496                        | Desktop     | [7797b2d6dd](https://linux-hardware.org/?probe=7797b2d6dd) | Jul 14, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [0c70241041](https://linux-hardware.org/?probe=0c70241041) | Jul 13, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [daf43ce57a](https://linux-hardware.org/?probe=daf43ce57a) | Jul 13, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [4a587952db](https://linux-hardware.org/?probe=4a587952db) | Jul 13, 2022 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [8a5a5a0987](https://linux-hardware.org/?probe=8a5a5a0987) | Jul 12, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [4929b942aa](https://linux-hardware.org/?probe=4929b942aa) | Jul 12, 2022 |
| Apple         | MacBookPro15,3              | Notebook    | [a8f8224853](https://linux-hardware.org/?probe=a8f8224853) | Jul 11, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [da05c4539d](https://linux-hardware.org/?probe=da05c4539d) | Jul 11, 2022 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [f2f3db370a](https://linux-hardware.org/?probe=f2f3db370a) | Jul 10, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [17b90f7a4b](https://linux-hardware.org/?probe=17b90f7a4b) | Jul 10, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3b8444274b](https://linux-hardware.org/?probe=3b8444274b) | Jul 10, 2022 |
| MSI           | A320M PRO-E                 | Desktop     | [d16a812a12](https://linux-hardware.org/?probe=d16a812a12) | Jul 10, 2022 |
| Lenovo        | ThinkPad W540 20BG001KGE    | Notebook    | [434091ba07](https://linux-hardware.org/?probe=434091ba07) | Jul 10, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [6ed805403a](https://linux-hardware.org/?probe=6ed805403a) | Jul 10, 2022 |
| Toshiba       | NB205                       | Notebook    | [f4046cb02f](https://linux-hardware.org/?probe=f4046cb02f) | Jul 10, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [7becd2f2df](https://linux-hardware.org/?probe=7becd2f2df) | Jul 10, 2022 |
| HP            | 158A                        | Desktop     | [e1bec79951](https://linux-hardware.org/?probe=e1bec79951) | Jul 10, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [bb736b4d03](https://linux-hardware.org/?probe=bb736b4d03) | Jul 08, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [0ce9dd5cee](https://linux-hardware.org/?probe=0ce9dd5cee) | Jul 08, 2022 |
| Dell          | 07T4MC A02                  | Desktop     | [88de707c31](https://linux-hardware.org/?probe=88de707c31) | Jul 08, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [b2d4e91300](https://linux-hardware.org/?probe=b2d4e91300) | Jul 07, 2022 |
| HP            | Notebook                    | Notebook    | [0c64a91465](https://linux-hardware.org/?probe=0c64a91465) | Jul 07, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [5cff36844a](https://linux-hardware.org/?probe=5cff36844a) | Jul 07, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [68efa303fa](https://linux-hardware.org/?probe=68efa303fa) | Jul 07, 2022 |
| Chuwi         | FreeBook                    | Notebook    | [3e0b057e38](https://linux-hardware.org/?probe=3e0b057e38) | Jul 07, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [e5bf9b72d0](https://linux-hardware.org/?probe=e5bf9b72d0) | Jul 07, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [2225f70ee7](https://linux-hardware.org/?probe=2225f70ee7) | Jul 06, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [542470182e](https://linux-hardware.org/?probe=542470182e) | Jul 05, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [d1aa8fe23d](https://linux-hardware.org/?probe=d1aa8fe23d) | Jul 05, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [5703355b59](https://linux-hardware.org/?probe=5703355b59) | Jul 04, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [51b138f349](https://linux-hardware.org/?probe=51b138f349) | Jul 04, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [2f915d68e5](https://linux-hardware.org/?probe=2f915d68e5) | Jul 04, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [ef75149636](https://linux-hardware.org/?probe=ef75149636) | Jul 03, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [7b470f27d3](https://linux-hardware.org/?probe=7b470f27d3) | Jul 03, 2022 |
| Samsung       | 370E4K                      | Notebook    | [a6512c1606](https://linux-hardware.org/?probe=a6512c1606) | Jul 03, 2022 |
| HP            | Mini 210-1100               | Notebook    | [72289b7641](https://linux-hardware.org/?probe=72289b7641) | Jul 03, 2022 |
| HP            | Mini 210-1100               | Notebook    | [aaa9b86216](https://linux-hardware.org/?probe=aaa9b86216) | Jul 02, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [3633eb51d4](https://linux-hardware.org/?probe=3633eb51d4) | Jul 01, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [8f90bed577](https://linux-hardware.org/?probe=8f90bed577) | Jul 01, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [d48eb55102](https://linux-hardware.org/?probe=d48eb55102) | Jul 01, 2022 |
| Dell          | 500                         | Notebook    | [040e3cb12c](https://linux-hardware.org/?probe=040e3cb12c) | Jun 30, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [9ce5b9c45c](https://linux-hardware.org/?probe=9ce5b9c45c) | Jun 30, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [05e7378ad8](https://linux-hardware.org/?probe=05e7378ad8) | Jun 29, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [f532d90f38](https://linux-hardware.org/?probe=f532d90f38) | Jun 29, 2022 |
| Standard      | Unknown                     | Notebook    | [1a94acbc05](https://linux-hardware.org/?probe=1a94acbc05) | Jun 29, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [e08493100f](https://linux-hardware.org/?probe=e08493100f) | Jun 29, 2022 |
| Lenovo        | IdeaPad 330-17IKB 81DK      | Notebook    | [2fa204d33e](https://linux-hardware.org/?probe=2fa204d33e) | Jun 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [bd4018ed46](https://linux-hardware.org/?probe=bd4018ed46) | Jun 29, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [a55837dc17](https://linux-hardware.org/?probe=a55837dc17) | Jun 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [87b9ce1db1](https://linux-hardware.org/?probe=87b9ce1db1) | Jun 28, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [372d361276](https://linux-hardware.org/?probe=372d361276) | Jun 28, 2022 |
| ASUSTek       | X551MA                      | Notebook    | [9bdb2a5577](https://linux-hardware.org/?probe=9bdb2a5577) | Jun 28, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [ac9a35e85e](https://linux-hardware.org/?probe=ac9a35e85e) | Jun 27, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [d0200625ac](https://linux-hardware.org/?probe=d0200625ac) | Jun 27, 2022 |
| Supermicro    | X10SRA                      | Server      | [4646cb2fae](https://linux-hardware.org/?probe=4646cb2fae) | Jun 27, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [e6d22a4d34](https://linux-hardware.org/?probe=e6d22a4d34) | Jun 27, 2022 |
| Standard      | Unknown                     | Notebook    | [93ac825a25](https://linux-hardware.org/?probe=93ac825a25) | Jun 27, 2022 |
| Apple         | MacBookPro1,1               | Notebook    | [feddac03b9](https://linux-hardware.org/?probe=feddac03b9) | Jun 26, 2022 |
| Lenovo        | ThinkPad T420s 417152U      | Notebook    | [cc52ed5e41](https://linux-hardware.org/?probe=cc52ed5e41) | Jun 26, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [47cddfb141](https://linux-hardware.org/?probe=47cddfb141) | Jun 25, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [ad5514340b](https://linux-hardware.org/?probe=ad5514340b) | Jun 25, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [4562c09862](https://linux-hardware.org/?probe=4562c09862) | Jun 24, 2022 |
| HP            | Pavilion dv5                | Notebook    | [4009a4fd8c](https://linux-hardware.org/?probe=4009a4fd8c) | Jun 24, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [8cf9d783a3](https://linux-hardware.org/?probe=8cf9d783a3) | Jun 23, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [1d18aab349](https://linux-hardware.org/?probe=1d18aab349) | Jun 23, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [4a61f83195](https://linux-hardware.org/?probe=4a61f83195) | Jun 23, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [b648b81eca](https://linux-hardware.org/?probe=b648b81eca) | Jun 23, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [db4763808b](https://linux-hardware.org/?probe=db4763808b) | Jun 22, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [5e9cdd75c7](https://linux-hardware.org/?probe=5e9cdd75c7) | Jun 22, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Alienware     | 17 R4                       | Notebook    | [74b66aebc5](https://linux-hardware.org/?probe=74b66aebc5) | Jun 21, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [9538654245](https://linux-hardware.org/?probe=9538654245) | Jun 21, 2022 |
| Intel         | D102GGC2 AAD42789-204       | Desktop     | [3ed07edb6a](https://linux-hardware.org/?probe=3ed07edb6a) | Jun 21, 2022 |
| HP            | 15                          | Notebook    | [61e6eddc93](https://linux-hardware.org/?probe=61e6eddc93) | Jun 20, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [e32a4e0214](https://linux-hardware.org/?probe=e32a4e0214) | Jun 20, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [ded5eaba87](https://linux-hardware.org/?probe=ded5eaba87) | Jun 19, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [515b063f08](https://linux-hardware.org/?probe=515b063f08) | Jun 18, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [fc761acd97](https://linux-hardware.org/?probe=fc761acd97) | Jun 18, 2022 |
| Intel         | NUC7i3BNB J22859-312        | Mini pc     | [89d99d840f](https://linux-hardware.org/?probe=89d99d840f) | Jun 17, 2022 |
| Google        | Kindred                     | Notebook    | [c12b15c596](https://linux-hardware.org/?probe=c12b15c596) | Jun 17, 2022 |
| Lenovo        | ThinkCentre M71e 5033AR1    | Desktop     | [dd0f797f78](https://linux-hardware.org/?probe=dd0f797f78) | Jun 17, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [f340c1d172](https://linux-hardware.org/?probe=f340c1d172) | Jun 17, 2022 |
| Medion        | E2221T MD60684              | Convertible | [559733f94d](https://linux-hardware.org/?probe=559733f94d) | Jun 16, 2022 |
| Acer          | Aspire 7720                 | Notebook    | [3f098cc493](https://linux-hardware.org/?probe=3f098cc493) | Jun 15, 2022 |
| Dynabook      | TECRA A50-J                 | Notebook    | [3f4449202f](https://linux-hardware.org/?probe=3f4449202f) | Jun 14, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [c1490b2a1c](https://linux-hardware.org/?probe=c1490b2a1c) | Jun 14, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [f41d413820](https://linux-hardware.org/?probe=f41d413820) | Jun 13, 2022 |
| Lenovo        | ThinkPad T530 23923MG       | Notebook    | [cf21c4e831](https://linux-hardware.org/?probe=cf21c4e831) | Jun 12, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [0ebaae147d](https://linux-hardware.org/?probe=0ebaae147d) | Jun 12, 2022 |
| GPU Compan... | GWTN141-4                   | Notebook    | [ba579cb383](https://linux-hardware.org/?probe=ba579cb383) | Jun 11, 2022 |
| Matsushita... | CF-W5LWEZZBM                | Notebook    | [380c6df037](https://linux-hardware.org/?probe=380c6df037) | Jun 11, 2022 |
| Packard Be... | EasyNote TK11BZ             | Notebook    | [f9c69ea1c6](https://linux-hardware.org/?probe=f9c69ea1c6) | Jun 11, 2022 |
| Lenovo        | G505 20240                  | Notebook    | [0b0d5e5252](https://linux-hardware.org/?probe=0b0d5e5252) | Jun 11, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [824dc8a1c9](https://linux-hardware.org/?probe=824dc8a1c9) | Jun 11, 2022 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [5df0f93da9](https://linux-hardware.org/?probe=5df0f93da9) | Jun 10, 2022 |
| Dell          | Latitude 7280               | Notebook    | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [535126df2b](https://linux-hardware.org/?probe=535126df2b) | Jun 09, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | Notebook    | [565722f81e](https://linux-hardware.org/?probe=565722f81e) | Jun 09, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | Notebook    | [c36b6d8e2c](https://linux-hardware.org/?probe=c36b6d8e2c) | Jun 09, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [bd0f56a43c](https://linux-hardware.org/?probe=bd0f56a43c) | Jun 09, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [7f48bb6a8a](https://linux-hardware.org/?probe=7f48bb6a8a) | Jun 08, 2022 |
| Acer          | Aspire 7720                 | Notebook    | [640b757bc8](https://linux-hardware.org/?probe=640b757bc8) | Jun 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [674cab9d61](https://linux-hardware.org/?probe=674cab9d61) | Jun 08, 2022 |
| Lenovo        | ThinkPad L380 20M6S4J400    | Notebook    | [dc1bcd1532](https://linux-hardware.org/?probe=dc1bcd1532) | Jun 08, 2022 |
| Lenovo        | CRESCENTBAY SDK0E50510 W... | All in one  | [5eaef9db5a](https://linux-hardware.org/?probe=5eaef9db5a) | Jun 08, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [bb17805ada](https://linux-hardware.org/?probe=bb17805ada) | Jun 08, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [77a5e1c6f9](https://linux-hardware.org/?probe=77a5e1c6f9) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [33dbe3e5db](https://linux-hardware.org/?probe=33dbe3e5db) | Jun 08, 2022 |
| Acer          | Aspire 7720                 | Notebook    | [ac4362743a](https://linux-hardware.org/?probe=ac4362743a) | Jun 07, 2022 |
| AMI           | Intel                       | Notebook    | [79b1f29bc4](https://linux-hardware.org/?probe=79b1f29bc4) | Jun 07, 2022 |
| AMI           | Intel                       | Notebook    | [d7746ec6d5](https://linux-hardware.org/?probe=d7746ec6d5) | Jun 07, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [064492c64d](https://linux-hardware.org/?probe=064492c64d) | Jun 07, 2022 |
| Lenovo        | CRESCENTBAY SDK0E50510 W... | All in one  | [0ce0f27bac](https://linux-hardware.org/?probe=0ce0f27bac) | Jun 07, 2022 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | Notebook    | [c4250d2ee2](https://linux-hardware.org/?probe=c4250d2ee2) | Jun 07, 2022 |
| Fujitsu       | LIFEBOOK U772               | Notebook    | [8dcf195f94](https://linux-hardware.org/?probe=8dcf195f94) | Jun 07, 2022 |
| Dell          | 0J1C3P A00                  | Desktop     | [3ee16e0227](https://linux-hardware.org/?probe=3ee16e0227) | Jun 07, 2022 |
| Digma         | EVE 15 C413 ES5059EW        | Notebook    | [26eb7d39e1](https://linux-hardware.org/?probe=26eb7d39e1) | Jun 06, 2022 |
| HP            | Pavilion g7                 | Notebook    | [b31de17368](https://linux-hardware.org/?probe=b31de17368) | Jun 06, 2022 |
| Unknown       | Unknown                     | Soc         | [0c5a37efd2](https://linux-hardware.org/?probe=0c5a37efd2) | Jun 05, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [63b4cd5c56](https://linux-hardware.org/?probe=63b4cd5c56) | Jun 05, 2022 |
| MSI           | PR601/VR603                 | Notebook    | [9763977184](https://linux-hardware.org/?probe=9763977184) | Jun 05, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| HP            | 3397                        | Desktop     | [775c6990fd](https://linux-hardware.org/?probe=775c6990fd) | Jun 03, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [49e472d67e](https://linux-hardware.org/?probe=49e472d67e) | Jun 02, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [dfe3e4b66b](https://linux-hardware.org/?probe=dfe3e4b66b) | Jun 02, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [d620bac2cb](https://linux-hardware.org/?probe=d620bac2cb) | Jun 02, 2022 |
| Dell          | Latitude D820               | Notebook    | [8c2336469f](https://linux-hardware.org/?probe=8c2336469f) | Jun 01, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [db6d025d69](https://linux-hardware.org/?probe=db6d025d69) | Jun 01, 2022 |
| Lenovo        | ThinkPad L13 20R4S4WG00     | Notebook    | [14100804b6](https://linux-hardware.org/?probe=14100804b6) | May 31, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [e46a1497d8](https://linux-hardware.org/?probe=e46a1497d8) | May 31, 2022 |
| Dell          | Latitude 5511               | Notebook    | [bc6fd9e79d](https://linux-hardware.org/?probe=bc6fd9e79d) | May 30, 2022 |
| ASUSTek       | VM60                        | Desktop     | [57bea34864](https://linux-hardware.org/?probe=57bea34864) | May 30, 2022 |
| ASUSTek       | VM60                        | Desktop     | [bf1dcb2901](https://linux-hardware.org/?probe=bf1dcb2901) | May 30, 2022 |
| Medion        | E15407                      | Notebook    | [6e457b6abb](https://linux-hardware.org/?probe=6e457b6abb) | May 29, 2022 |
| Medion        | E15407                      | Notebook    | [a0d6c795e7](https://linux-hardware.org/?probe=a0d6c795e7) | May 29, 2022 |
| TUXEDO        | N14xWU                      | Notebook    | [c20d682e14](https://linux-hardware.org/?probe=c20d682e14) | May 29, 2022 |
| HP            | 2B29                        | Desktop     | [d2ab16d631](https://linux-hardware.org/?probe=d2ab16d631) | May 28, 2022 |
| Pegatron      | Benicia                     | Desktop     | [64aa376623](https://linux-hardware.org/?probe=64aa376623) | May 28, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [d6adaef7cc](https://linux-hardware.org/?probe=d6adaef7cc) | May 28, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [c848e4649e](https://linux-hardware.org/?probe=c848e4649e) | May 28, 2022 |
| TUXEDO        | N14xWU                      | Notebook    | [8711ac9989](https://linux-hardware.org/?probe=8711ac9989) | May 26, 2022 |
| LG Electro... | 22V280 FAB1                 | All in one  | [d61829e715](https://linux-hardware.org/?probe=d61829e715) | May 26, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [496399846f](https://linux-hardware.org/?probe=496399846f) | May 26, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [2c541b20f6](https://linux-hardware.org/?probe=2c541b20f6) | May 26, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [f71c048a96](https://linux-hardware.org/?probe=f71c048a96) | May 25, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [aa8d9cb3b9](https://linux-hardware.org/?probe=aa8d9cb3b9) | May 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [a22a5ebbff](https://linux-hardware.org/?probe=a22a5ebbff) | May 25, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [23d890ffc6](https://linux-hardware.org/?probe=23d890ffc6) | May 23, 2022 |
| HP            | 1497                        | Desktop     | [4b9a65b621](https://linux-hardware.org/?probe=4b9a65b621) | May 23, 2022 |
| HP            | Mini 5103                   | Notebook    | [aa7f4e957e](https://linux-hardware.org/?probe=aa7f4e957e) | May 23, 2022 |
| ASUSTek       | X99-A II                    | Desktop     | [288a6b3b20](https://linux-hardware.org/?probe=288a6b3b20) | May 23, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [3e34ce179d](https://linux-hardware.org/?probe=3e34ce179d) | May 22, 2022 |
| ASUSTek       | X510UA                      | Notebook    | [51d57b9e53](https://linux-hardware.org/?probe=51d57b9e53) | May 22, 2022 |
| Sony          | VGN-NS21S_S                 | Notebook    | [0c972ad98b](https://linux-hardware.org/?probe=0c972ad98b) | May 21, 2022 |
| HP            | Pavilion dv6000 (RR374EA... | Notebook    | [926749e311](https://linux-hardware.org/?probe=926749e311) | May 21, 2022 |
| Google        | Snappy                      | Notebook    | [c88d27b24a](https://linux-hardware.org/?probe=c88d27b24a) | May 20, 2022 |
| Google        | Snappy                      | Notebook    | [9fc85cd49a](https://linux-hardware.org/?probe=9fc85cd49a) | May 20, 2022 |
| Google        | Snappy                      | Notebook    | [cb9e7730ad](https://linux-hardware.org/?probe=cb9e7730ad) | May 20, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | Notebook    | [baed2325d7](https://linux-hardware.org/?probe=baed2325d7) | May 20, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [ee3726a591](https://linux-hardware.org/?probe=ee3726a591) | May 19, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [086fceea4f](https://linux-hardware.org/?probe=086fceea4f) | May 19, 2022 |
| Lenovo        | ThinkPad E580 20KS001JGE    | Notebook    | [724c06c08c](https://linux-hardware.org/?probe=724c06c08c) | May 19, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | Notebook    | [e4150ff93b](https://linux-hardware.org/?probe=e4150ff93b) | May 19, 2022 |
| Acer          | Aspire G7750                | Desktop     | [28f3018ecc](https://linux-hardware.org/?probe=28f3018ecc) | May 18, 2022 |
| IBM           | ThinkPad T43 2668F5G        | Notebook    | [af59841e31](https://linux-hardware.org/?probe=af59841e31) | May 18, 2022 |
| Dell          | Latitude D610               | Notebook    | [2e945626d4](https://linux-hardware.org/?probe=2e945626d4) | May 17, 2022 |
| Dell          | Latitude D610               | Notebook    | [9ee1df5d0e](https://linux-hardware.org/?probe=9ee1df5d0e) | May 17, 2022 |
| HP            | 158A                        | Desktop     | [dd67e1f8d2](https://linux-hardware.org/?probe=dd67e1f8d2) | May 17, 2022 |
| Dell          | Latitude E6410              | Notebook    | [ae757ea3a4](https://linux-hardware.org/?probe=ae757ea3a4) | May 16, 2022 |
| ASUSTek       | UL30A                       | Notebook    | [c121dd37ba](https://linux-hardware.org/?probe=c121dd37ba) | May 16, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [544536b2d8](https://linux-hardware.org/?probe=544536b2d8) | May 16, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [fbcf200ed5](https://linux-hardware.org/?probe=fbcf200ed5) | May 16, 2022 |
| HP            | Mini 110-1100               | Notebook    | [b93ac7c302](https://linux-hardware.org/?probe=b93ac7c302) | May 16, 2022 |
| HP            | Mini 110-1100               | Notebook    | [4a5f85e53d](https://linux-hardware.org/?probe=4a5f85e53d) | May 16, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [2df08f807d](https://linux-hardware.org/?probe=2df08f807d) | May 15, 2022 |
| Dell          | Latitude 5580               | Notebook    | [c2f15d647a](https://linux-hardware.org/?probe=c2f15d647a) | May 15, 2022 |
| MSI           | AM1I                        | Desktop     | [f22b398676](https://linux-hardware.org/?probe=f22b398676) | May 15, 2022 |
| Google        | Droid                       | Notebook    | [e938864c93](https://linux-hardware.org/?probe=e938864c93) | May 15, 2022 |
| Lenovo        | ThinkPad X200s 74664SJ      | Notebook    | [65728fda7a](https://linux-hardware.org/?probe=65728fda7a) | May 14, 2022 |
| ECS           | Asterope                    | Desktop     | [a0c032d6f6](https://linux-hardware.org/?probe=a0c032d6f6) | May 14, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [a3b1829dec](https://linux-hardware.org/?probe=a3b1829dec) | May 13, 2022 |
| HP            | 82B4                        | Desktop     | [3a1723a2ee](https://linux-hardware.org/?probe=3a1723a2ee) | May 13, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [6f58937bed](https://linux-hardware.org/?probe=6f58937bed) | May 13, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [cace04f39a](https://linux-hardware.org/?probe=cace04f39a) | May 12, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [bf7fdb19c8](https://linux-hardware.org/?probe=bf7fdb19c8) | May 12, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [62744ba7e3](https://linux-hardware.org/?probe=62744ba7e3) | May 12, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bf4afe4481](https://linux-hardware.org/?probe=bf4afe4481) | May 12, 2022 |
| ASUSTek       | A7K                         | Notebook    | [29ca1c7e33](https://linux-hardware.org/?probe=29ca1c7e33) | May 11, 2022 |
| ASUSTek       | B150-PLUS                   | Desktop     | [eb2447cec6](https://linux-hardware.org/?probe=eb2447cec6) | May 11, 2022 |
| Dell          | Latitude E6410              | Notebook    | [a14c28c93f](https://linux-hardware.org/?probe=a14c28c93f) | May 11, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [bb4a27a023](https://linux-hardware.org/?probe=bb4a27a023) | May 10, 2022 |
| Dell          | Latitude 7400               | Notebook    | [a0600c38f3](https://linux-hardware.org/?probe=a0600c38f3) | May 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [f802e84b8e](https://linux-hardware.org/?probe=f802e84b8e) | May 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS6FF00    | Notebook    | [3e3da41a35](https://linux-hardware.org/?probe=3e3da41a35) | May 08, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [bd94a8145a](https://linux-hardware.org/?probe=bd94a8145a) | May 08, 2022 |
| Gigabyte      | Z68A-D3-B3                  | Desktop     | [573e425cb6](https://linux-hardware.org/?probe=573e425cb6) | May 08, 2022 |
| Dell          | Latitude E6410              | Notebook    | [361bcaa4cc](https://linux-hardware.org/?probe=361bcaa4cc) | May 07, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [a8a1e1e3a2](https://linux-hardware.org/?probe=a8a1e1e3a2) | May 07, 2022 |
| HP            | Compaq 6820s                | Notebook    | [1ba74fc299](https://linux-hardware.org/?probe=1ba74fc299) | May 07, 2022 |
| HP            | Compaq 6820s                | Notebook    | [5b027deec0](https://linux-hardware.org/?probe=5b027deec0) | May 07, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [e7ad5ed098](https://linux-hardware.org/?probe=e7ad5ed098) | May 06, 2022 |
| HP            | 3397                        | Desktop     | [157ef440d8](https://linux-hardware.org/?probe=157ef440d8) | May 06, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [fa4a4b7ffc](https://linux-hardware.org/?probe=fa4a4b7ffc) | May 06, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [e754b48e71](https://linux-hardware.org/?probe=e754b48e71) | May 06, 2022 |
| Dell          | Latitude 7420               | Notebook    | [384325350c](https://linux-hardware.org/?probe=384325350c) | May 05, 2022 |
| Gigabyte      | X48-DS5                     | Desktop     | [72a1aaf67d](https://linux-hardware.org/?probe=72a1aaf67d) | May 05, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [6dbe28a107](https://linux-hardware.org/?probe=6dbe28a107) | May 05, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [795d9af5a7](https://linux-hardware.org/?probe=795d9af5a7) | May 05, 2022 |
| Acer          | Veriton M490G               | Desktop     | [f55983d536](https://linux-hardware.org/?probe=f55983d536) | May 04, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [d4dff7f002](https://linux-hardware.org/?probe=d4dff7f002) | May 04, 2022 |
| HP            | 158A                        | Desktop     | [cb763d6fab](https://linux-hardware.org/?probe=cb763d6fab) | May 04, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [c6da7b776e](https://linux-hardware.org/?probe=c6da7b776e) | May 03, 2022 |
| Dell          | XPS M1530                   | Notebook    | [760cae00c1](https://linux-hardware.org/?probe=760cae00c1) | May 03, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [1533323fbf](https://linux-hardware.org/?probe=1533323fbf) | May 02, 2022 |
| ASRock        | P55 Pro                     | Desktop     | [e626676348](https://linux-hardware.org/?probe=e626676348) | May 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [981f468940](https://linux-hardware.org/?probe=981f468940) | May 02, 2022 |
| ASUSTek       | B150-PLUS                   | Desktop     | [e2f5eb0a39](https://linux-hardware.org/?probe=e2f5eb0a39) | May 02, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [6e1a9ce167](https://linux-hardware.org/?probe=6e1a9ce167) | May 01, 2022 |
| Razer         | Blade Stealth 13 Late 20... | Notebook    | [ba8fa66c1c](https://linux-hardware.org/?probe=ba8fa66c1c) | May 01, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [f9e5dd9719](https://linux-hardware.org/?probe=f9e5dd9719) | May 01, 2022 |
| Dell          | XPS M1530                   | Notebook    | [757d1b099e](https://linux-hardware.org/?probe=757d1b099e) | Apr 30, 2022 |
| ASUSTek       | T100HAN                     | Notebook    | [5ee200cfbe](https://linux-hardware.org/?probe=5ee200cfbe) | Apr 30, 2022 |
| Unknown       | Intel X79                   | Desktop     | [95d09d79ca](https://linux-hardware.org/?probe=95d09d79ca) | Apr 29, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [f2605ba739](https://linux-hardware.org/?probe=f2605ba739) | Apr 29, 2022 |
| Acer          | Aspire ES1-311              | Notebook    | [aa4612575b](https://linux-hardware.org/?probe=aa4612575b) | Apr 29, 2022 |
| HP            | Compaq 6730b (GW687AV)      | Notebook    | [96ee86a3c6](https://linux-hardware.org/?probe=96ee86a3c6) | Apr 28, 2022 |
| Dell          | Inspiron 3135               | Notebook    | [6ca6980f06](https://linux-hardware.org/?probe=6ca6980f06) | Apr 28, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [fc0cea6830](https://linux-hardware.org/?probe=fc0cea6830) | Apr 27, 2022 |
| HP            | 09F8h                       | Desktop     | [8605181df9](https://linux-hardware.org/?probe=8605181df9) | Apr 26, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [f0ed67e309](https://linux-hardware.org/?probe=f0ed67e309) | Apr 26, 2022 |
| Supermicro    | X11SPL-F                    | Server      | [34f6e28125](https://linux-hardware.org/?probe=34f6e28125) | Apr 26, 2022 |
| Dell          | Latitude 7480               | Notebook    | [7e85baf2f4](https://linux-hardware.org/?probe=7e85baf2f4) | Apr 26, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [bd286b124a](https://linux-hardware.org/?probe=bd286b124a) | Apr 25, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [6c64775a71](https://linux-hardware.org/?probe=6c64775a71) | Apr 24, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c16cb4e0d6](https://linux-hardware.org/?probe=c16cb4e0d6) | Apr 24, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| ASUSTek       | 1215N                       | Notebook    | [93ad513620](https://linux-hardware.org/?probe=93ad513620) | Apr 24, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [80befa3088](https://linux-hardware.org/?probe=80befa3088) | Apr 23, 2022 |
| Nvidia        | Tegra                       | Soc         | [36bbd53ec1](https://linux-hardware.org/?probe=36bbd53ec1) | Apr 23, 2022 |
| HP            | 09F8h                       | Desktop     | [5042a34dcd](https://linux-hardware.org/?probe=5042a34dcd) | Apr 23, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [d2cd51f72d](https://linux-hardware.org/?probe=d2cd51f72d) | Apr 22, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [bde3fa1f37](https://linux-hardware.org/?probe=bde3fa1f37) | Apr 22, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | Notebook    | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| Dell          | XPS M1530                   | Notebook    | [f22a6a2c55](https://linux-hardware.org/?probe=f22a6a2c55) | Apr 21, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [5a662b428e](https://linux-hardware.org/?probe=5a662b428e) | Apr 21, 2022 |
| Hardkernel    | ODROID-M1                   | Soc         | [481e87aa23](https://linux-hardware.org/?probe=481e87aa23) | Apr 21, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [e87dfd05bc](https://linux-hardware.org/?probe=e87dfd05bc) | Apr 20, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [fae46ae55c](https://linux-hardware.org/?probe=fae46ae55c) | Apr 20, 2022 |
| eMachines     | MCP61PM-GM                  | Desktop     | [16c4522843](https://linux-hardware.org/?probe=16c4522843) | Apr 20, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [d277143404](https://linux-hardware.org/?probe=d277143404) | Apr 20, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [d88db86125](https://linux-hardware.org/?probe=d88db86125) | Apr 20, 2022 |
| Dell          | XPS M1530                   | Notebook    | [60d3e4f97f](https://linux-hardware.org/?probe=60d3e4f97f) | Apr 20, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [40e958c5e1](https://linux-hardware.org/?probe=40e958c5e1) | Apr 19, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [6fa162f829](https://linux-hardware.org/?probe=6fa162f829) | Apr 19, 2022 |
| ASUSTek       | P8Z68 DELUXE                | Desktop     | [4df90e6250](https://linux-hardware.org/?probe=4df90e6250) | Apr 18, 2022 |
| HP            | 18E5                        | Desktop     | [211d35a24b](https://linux-hardware.org/?probe=211d35a24b) | Apr 17, 2022 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | Desktop     | [d2559a2f19](https://linux-hardware.org/?probe=d2559a2f19) | Apr 17, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Xubuntu/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Xubuntu 20.04 | 1932      | 48.63%  |
| Xubuntu 18.04 | 1028      | 25.87%  |
| Xubuntu 22.04 | 352       | 8.86%   |
| Xubuntu 19.10 | 199       | 5.01%   |
| Xubuntu 16.04 | 97        | 2.44%   |
| Xubuntu 21.10 | 96        | 2.42%   |
| Xubuntu 20.10 | 93        | 2.34%   |
| Xubuntu 21.04 | 79        | 1.99%   |
| Xubuntu 22.10 | 42        | 1.06%   |
| Xubuntu 19.04 | 26        | 0.65%   |
| Xubuntu 18.10 | 11        | 0.28%   |
| Xubuntu 17.10 | 6         | 0.15%   |
| Xubuntu       | 6         | 0.15%   |
| Xubuntu 14.04 | 3         | 0.08%   |
| Xubuntu 17.04 | 2         | 0.05%   |
| Xubuntu 23.04 | 1         | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Xubuntu | 3840      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.4.0-42-generic    | 155       | 3.42%   |
| 5.4.0-48-generic    | 65        | 1.43%   |
| 5.4.0-58-generic    | 60        | 1.32%   |
| 5.4.0-52-generic    | 59        | 1.3%    |
| 5.3.0-46-generic    | 59        | 1.3%    |
| 5.11.0-27-generic   | 50        | 1.1%    |
| 5.15.0-56-generic   | 49        | 1.08%   |
| 5.4.0-65-generic    | 48        | 1.06%   |
| 5.3.0-40-generic    | 48        | 1.06%   |
| 5.4.0-29-generic    | 46        | 1.01%   |
| 5.4.0-54-generic    | 45        | 0.99%   |
| 5.15.0-52-generic   | 44        | 0.97%   |
| 5.4.0-47-generic    | 42        | 0.93%   |
| 5.4.0-42-lowlatency | 40        | 0.88%   |
| 5.4.0-26-generic    | 38        | 0.84%   |
| 5.3.0-42-generic    | 38        | 0.84%   |
| 5.3.0-28-generic    | 36        | 0.79%   |
| 5.4.0-40-generic    | 35        | 0.77%   |
| 5.0.0-37-generic    | 35        | 0.77%   |
| 5.3.0-51-generic    | 34        | 0.75%   |
| 5.4.0-37-generic    | 33        | 0.73%   |
| 5.4.0-66-generic    | 31        | 0.68%   |
| 5.15.0-47-generic   | 31        | 0.68%   |
| 4.15.0-99-generic   | 31        | 0.68%   |
| 5.4.0-89-generic    | 30        | 0.66%   |
| 5.4.0-31-generic    | 30        | 0.66%   |
| 5.15.0-58-generic   | 30        | 0.66%   |
| 5.15.0-48-generic   | 30        | 0.66%   |
| 5.4.0-72-generic    | 28        | 0.62%   |
| 5.3.0-53-generic    | 28        | 0.62%   |
| 5.15.0-46-generic   | 28        | 0.62%   |
| 5.4.0-29-lowlatency | 27        | 0.6%    |
| 5.4.0-91-generic    | 26        | 0.57%   |
| 5.4.0-81-generic    | 26        | 0.57%   |
| 5.13.0-39-generic   | 26        | 0.57%   |
| 5.8.0-53-generic    | 25        | 0.55%   |
| 5.4.0-33-generic    | 25        | 0.55%   |
| 5.8.0-43-generic    | 24        | 0.53%   |
| 5.4.0-56-generic    | 24        | 0.53%   |
| 5.13.0-30-generic   | 24        | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1584      | 39.12%  |
| 4.15.0  | 479       | 11.83%  |
| 5.3.0   | 438       | 10.82%  |
| 5.15.0  | 383       | 9.46%   |
| 5.11.0  | 275       | 6.79%   |
| 5.8.0   | 255       | 6.3%    |
| 5.13.0  | 222       | 5.48%   |
| 5.0.0   | 107       | 2.64%   |
| 4.4.0   | 47        | 1.16%   |
| 5.19.0  | 46        | 1.14%   |
| 4.18.0  | 25        | 0.62%   |
| 5.17.0  | 10        | 0.25%   |
| 4.13.0  | 9         | 0.22%   |
| 4.10.0  | 6         | 0.15%   |
| 5.6.0   | 5         | 0.12%   |
| 5.14.0  | 5         | 0.12%   |
| 5.10.0  | 5         | 0.12%   |
| 6.1.0   | 3         | 0.07%   |
| 5.9.8   | 3         | 0.07%   |
| 5.9.16  | 3         | 0.07%   |
| 5.4.217 | 3         | 0.07%   |
| 5.18.0  | 3         | 0.07%   |
| 5.15.1  | 3         | 0.07%   |
| 5.11.16 | 3         | 0.07%   |
| 4.8.0   | 3         | 0.07%   |
| 6.0.9   | 2         | 0.05%   |
| 6.0.0   | 2         | 0.05%   |
| 5.9.0   | 2         | 0.05%   |
| 5.7.7   | 2         | 0.05%   |
| 5.7.6   | 2         | 0.05%   |
| 5.7.1   | 2         | 0.05%   |
| 5.7.0   | 2         | 0.05%   |
| 5.6.19  | 2         | 0.05%   |
| 5.5.19  | 2         | 0.05%   |
| 5.16.9  | 2         | 0.05%   |
| 5.16.0  | 2         | 0.05%   |
| 5.13.7  | 2         | 0.05%   |
| 5.12.12 | 2         | 0.05%   |
| 5.12.10 | 2         | 0.05%   |
| 5.11.6  | 2         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1593      | 39.38%  |
| 4.15    | 479       | 11.84%  |
| 5.3     | 440       | 10.88%  |
| 5.15    | 394       | 9.74%   |
| 5.11    | 282       | 6.97%   |
| 5.8     | 260       | 6.43%   |
| 5.13    | 226       | 5.59%   |
| 5.0     | 109       | 2.69%   |
| 4.4     | 50        | 1.24%   |
| 5.19    | 49        | 1.21%   |
| 4.18    | 25        | 0.62%   |
| 5.10    | 16        | 0.4%    |
| 5.9     | 11        | 0.27%   |
| 5.17    | 11        | 0.27%   |
| 5.7     | 10        | 0.25%   |
| 5.14    | 10        | 0.25%   |
| 5.6     | 9         | 0.22%   |
| 4.13    | 9         | 0.22%   |
| 5.12    | 8         | 0.2%    |
| 4.19    | 7         | 0.17%   |
| 6.1     | 6         | 0.15%   |
| 4.10    | 6         | 0.15%   |
| 6.0     | 5         | 0.12%   |
| 5.18    | 5         | 0.12%   |
| 5.16    | 5         | 0.12%   |
| 4.9     | 4         | 0.1%    |
| 5.5     | 3         | 0.07%   |
| 4.8     | 3         | 0.07%   |
| 5.2     | 2         | 0.05%   |
| 4.14    | 2         | 0.05%   |
| 4.11    | 2         | 0.05%   |
| 6.2     | 1         | 0.02%   |
| 4.20    | 1         | 0.02%   |
| 4.12    | 1         | 0.02%   |
| 3.13    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3306      | 85.96%  |
| i686    | 502       | 13.05%  |
| aarch64 | 30        | 0.78%   |
| armv7l  | 8         | 0.21%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 3705      | 96.31%  |
| GNOME           | 100       | 2.6%    |
| i3              | 8         | 0.21%   |
| KDE5            | 7         | 0.18%   |
| Cinnamon        | 7         | 0.18%   |
| Unity           | 4         | 0.1%    |
| GNOME Flashback | 4         | 0.1%    |
| X-Cinnamon      | 2         | 0.05%   |
| MATE            | 2         | 0.05%   |
| LXQt            | 2         | 0.05%   |
| GNUstep         | 2         | 0.05%   |
| xmonad          | 1         | 0.03%   |
| ICEWM           | 1         | 0.03%   |
| awesome         | 1         | 0.03%   |
| Unknown         | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3772      | 98.15%  |
| Tty     | 48        | 1.25%   |
| Wayland | 18        | 0.47%   |
| Web     | 3         | 0.08%   |
| Unknown | 2         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2085      | 52.57%  |
| LightDM | 1258      | 31.72%  |
| TDM     | 508       | 12.81%  |
| GDM3    | 53        | 1.34%   |
| GDM     | 47        | 1.19%   |
| SDDM    | 9         | 0.23%   |
| XDM     | 4         | 0.1%    |
| SLiM    | 1         | 0.03%   |
| NODM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1235      | 31.99%  |
| de_DE   | 404       | 10.47%  |
| fr_FR   | 338       | 8.76%   |
| it_IT   | 260       | 6.74%   |
| ru_RU   | 194       | 5.03%   |
| pt_BR   | 192       | 4.97%   |
| en_GB   | 139       | 3.6%    |
| C       | 133       | 3.45%   |
| es_ES   | 103       | 2.67%   |
| en_CA   | 90        | 2.33%   |
| Unknown | 81        | 2.1%    |
| en_AU   | 69        | 1.79%   |
| pl_PL   | 57        | 1.48%   |
| es_AR   | 41        | 1.06%   |
| nl_NL   | 38        | 0.98%   |
| hu_HU   | 38        | 0.98%   |
| ja_JP   | 35        | 0.91%   |
| cs_CZ   | 32        | 0.83%   |
| en_IN   | 23        | 0.6%    |
| es_MX   | 21        | 0.54%   |
| pt_PT   | 17        | 0.44%   |
| fr_BE   | 17        | 0.44%   |
| ru_UA   | 16        | 0.41%   |
| fi_FI   | 16        | 0.41%   |
| sv_SE   | 14        | 0.36%   |
| sk_SK   | 14        | 0.36%   |
| es_CO   | 14        | 0.36%   |
| en_ZA   | 14        | 0.36%   |
| tr_TR   | 13        | 0.34%   |
| el_GR   | 13        | 0.34%   |
| de_AT   | 13        | 0.34%   |
| de_CH   | 12        | 0.31%   |
| zh_TW   | 11        | 0.28%   |
| fr_CA   | 11        | 0.28%   |
| es_VE   | 10        | 0.26%   |
| nl_BE   | 9         | 0.23%   |
| zh_CN   | 8         | 0.21%   |
| en_IL   | 7         | 0.18%   |
| ca_ES   | 7         | 0.18%   |
| bg_BG   | 7         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2553      | 65.73%  |
| EFI  | 1331      | 34.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 3537      | 91.85%  |
| Overlay | 150       | 3.9%    |
| Btrfs   | 69        | 1.79%   |
| Zfs     | 36        | 0.93%   |
| Unknown | 24        | 0.62%   |
| Xfs     | 15        | 0.39%   |
| Ext2    | 11        | 0.29%   |
| Ext3    | 7         | 0.18%   |
| Ufs     | 1         | 0.03%   |
| Aufs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2482      | 63.82%  |
| GPT     | 908       | 23.35%  |
| MBR     | 499       | 12.83%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3274      | 83.58%  |
| Yes       | 643       | 16.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2582      | 66.05%  |
| Yes       | 1327      | 33.95%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 601       | 15.65%  |
| ASUSTek Computer        | 588       | 15.31%  |
| Dell                    | 468       | 12.19%  |
| Lenovo                  | 452       | 11.77%  |
| Acer                    | 257       | 6.69%   |
| Gigabyte Technology     | 224       | 5.83%   |
| MSI                     | 175       | 4.56%   |
| ASRock                  | 143       | 3.72%   |
| Toshiba                 | 97        | 2.53%   |
| Apple                   | 69        | 1.8%    |
| Intel                   | 65        | 1.69%   |
| Samsung Electronics     | 56        | 1.46%   |
| Sony                    | 50        | 1.3%    |
| Medion                  | 43        | 1.12%   |
| Unknown                 | 40        | 1.04%   |
| Fujitsu Siemens         | 31        | 0.81%   |
| Fujitsu                 | 30        | 0.78%   |
| ECS                     | 29        | 0.76%   |
| Packard Bell            | 28        | 0.73%   |
| Foxconn                 | 20        | 0.52%   |
| Notebook                | 17        | 0.44%   |
| Positivo                | 16        | 0.42%   |
| Raspberry Pi Foundation | 15        | 0.39%   |
| Google                  | 15        | 0.39%   |
| Pegatron                | 14        | 0.36%   |
| Clevo                   | 14        | 0.36%   |
| eMachines               | 13        | 0.34%   |
| IBM                     | 12        | 0.31%   |
| HUAWEI                  | 11        | 0.29%   |
| Supermicro              | 10        | 0.26%   |
| AMI                     | 9         | 0.23%   |
| LG Electronics          | 8         | 0.21%   |
| Gateway                 | 8         | 0.21%   |
| Biostar                 | 8         | 0.21%   |
| ZOTAC                   | 7         | 0.18%   |
| NEC Computers           | 6         | 0.16%   |
| GPU Company             | 6         | 0.16%   |
| Alienware               | 6         | 0.16%   |
| Semp Toshiba            | 5         | 0.13%   |
| OEM                     | 5         | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 61        | 1.59%   |
| ASUS All Series                        | 35        | 0.91%   |
| HP Pavilion dv6                        | 17        | 0.44%   |
| HP Notebook                            | 17        | 0.44%   |
| Gigabyte H410M S2H                     | 15        | 0.39%   |
| Dell OptiPlex 7010                     | 15        | 0.39%   |
| Dell OptiPlex 755                      | 11        | 0.29%   |
| Dell Latitude D630                     | 11        | 0.29%   |
| HP Pavilion 15                         | 10        | 0.26%   |
| HP 15                                  | 10        | 0.26%   |
| ECS G31T-M9                            | 9         | 0.23%   |
| Dell Latitude E6430                    | 9         | 0.23%   |
| Dell OptiPlex 780                      | 8         | 0.21%   |
| Dell OptiPlex 760                      | 8         | 0.21%   |
| Dell OptiPlex 390                      | 8         | 0.21%   |
| ASRock N68C-S UCC                      | 8         | 0.21%   |
| HP Pavilion dv7                        | 7         | 0.18%   |
| HP Pavilion dv6500                     | 7         | 0.18%   |
| MSI MS-7C37                            | 6         | 0.16%   |
| HP Pavilion g6                         | 6         | 0.16%   |
| HP EliteDesk 800 G1 SFF                | 6         | 0.16%   |
| ASUS VivoBook_ASUSLaptop X571LH_K571LH | 6         | 0.16%   |
| ASUS TUF Gaming X570-PLUS              | 6         | 0.16%   |
| MSI MS-7B89                            | 5         | 0.13%   |
| MSI MS-7B79                            | 5         | 0.13%   |
| MSI MS-7A38                            | 5         | 0.13%   |
| MSI MS-7721                            | 5         | 0.13%   |
| HP EliteBook 840 G3                    | 5         | 0.13%   |
| HP Compaq Elite 8300 SFF               | 5         | 0.13%   |
| HP Compaq dc7600 Small Form Factor     | 5         | 0.13%   |
| Gigabyte 945GZM-S2                     | 5         | 0.13%   |
| Dell OptiPlex GX620                    | 5         | 0.13%   |
| Dell OptiPlex 3020                     | 5         | 0.13%   |
| Dell Latitude E6520                    | 5         | 0.13%   |
| ASUS M5A78L-M/USB3                     | 5         | 0.13%   |
| ASUS 1005HA                            | 5         | 0.13%   |
| Acer Aspire one                        | 5         | 0.13%   |
| Acer AO751h                            | 5         | 0.13%   |
| RPi Raspberry Pi 4 Model B Rev 1.4     | 4         | 0.1%    |
| RPi Raspberry Pi 4 Model B Rev 1.1     | 4         | 0.1%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 226       | 5.89%   |
| Acer Aspire           | 163       | 4.24%   |
| Dell Inspiron         | 127       | 3.31%   |
| Dell Latitude         | 119       | 3.1%    |
| HP Pavilion           | 112       | 2.92%   |
| HP Compaq             | 110       | 2.86%   |
| Dell OptiPlex         | 98        | 2.55%   |
| Toshiba Satellite     | 82        | 2.14%   |
| Lenovo IdeaPad        | 67        | 1.74%   |
| Unknown               | 61        | 1.59%   |
| HP EliteBook          | 57        | 1.48%   |
| ASUS PRIME            | 45        | 1.17%   |
| HP ProBook            | 43        | 1.12%   |
| Lenovo ThinkCentre    | 39        | 1.02%   |
| HP Laptop             | 38        | 0.99%   |
| Dell Precision        | 35        | 0.91%   |
| ASUS All              | 35        | 0.91%   |
| ASUS VivoBook         | 34        | 0.89%   |
| ASUS TUF              | 20        | 0.52%   |
| Dell Vostro           | 19        | 0.49%   |
| HP Notebook           | 18        | 0.47%   |
| Dell XPS              | 18        | 0.47%   |
| HP ProDesk            | 17        | 0.44%   |
| Acer Veriton          | 17        | 0.44%   |
| Acer Extensa          | 17        | 0.44%   |
| Gigabyte H410M        | 16        | 0.42%   |
| ASUS ROG              | 16        | 0.42%   |
| RPi Raspberry         | 15        | 0.39%   |
| Fujitsu Siemens AMILO | 15        | 0.39%   |
| Dell PowerEdge        | 15        | 0.39%   |
| Packard Bell EasyNote | 14        | 0.36%   |
| HP EliteDesk          | 14        | 0.36%   |
| HP ENVY               | 13        | 0.34%   |
| Fujitsu LIFEBOOK      | 12        | 0.31%   |
| Dell Studio           | 12        | 0.31%   |
| HP Presario           | 11        | 0.29%   |
| HP Mini               | 11        | 0.29%   |
| HP 255                | 11        | 0.29%   |
| HP 15                 | 11        | 0.29%   |
| Fujitsu ESPRIMO       | 11        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 335       | 8.72%   |
| 2011    | 322       | 8.39%   |
| 2010    | 290       | 7.55%   |
| 2008    | 286       | 7.45%   |
| 2013    | 281       | 7.32%   |
| 2009    | 267       | 6.95%   |
| 2007    | 262       | 6.82%   |
| 2019    | 227       | 5.91%   |
| 2014    | 220       | 5.73%   |
| 2018    | 214       | 5.57%   |
| 2017    | 201       | 5.23%   |
| 2020    | 197       | 5.13%   |
| 2015    | 155       | 4.04%   |
| 2016    | 150       | 3.91%   |
| 2006    | 143       | 3.72%   |
| 2021    | 121       | 3.15%   |
| 2005    | 71        | 1.85%   |
| Unknown | 35        | 0.91%   |
| 2022    | 25        | 0.65%   |
| 2004    | 16        | 0.42%   |
| 2003    | 15        | 0.39%   |
| 2001    | 4         | 0.1%    |
| 2002    | 3         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2091      | 54.45%  |
| Desktop        | 1534      | 39.95%  |
| Mini pc        | 49        | 1.28%   |
| All in one     | 42        | 1.09%   |
| Convertible    | 38        | 0.99%   |
| System on chip | 36        | 0.94%   |
| Server         | 33        | 0.86%   |
| Tablet         | 16        | 0.42%   |
| Firewall       | 1         | 0.03%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3646      | 94.53%  |
| Enabled  | 211       | 5.47%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3824      | 99.58%  |
| Yes  | 16        | 0.42%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 1036      | 26.58%  |
| 4.01-8.0        | 741       | 19.01%  |
| 8.01-16.0       | 523       | 13.42%  |
| 16.01-24.0      | 499       | 12.8%   |
| 1.01-2.0        | 465       | 11.93%  |
| 32.01-64.0      | 203       | 5.21%   |
| 2.01-3.0        | 147       | 3.77%   |
| 0.51-1.0        | 147       | 3.77%   |
| 64.01-256.0     | 77        | 1.98%   |
| 24.01-32.0      | 45        | 1.15%   |
| 0.01-0.5        | 12        | 0.31%   |
| More than 256.0 | 2         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1786      | 42.09%  |
| 0.51-1.0   | 850       | 20.03%  |
| 2.01-3.0   | 764       | 18.01%  |
| 4.01-8.0   | 335       | 7.9%    |
| 3.01-4.0   | 276       | 6.5%    |
| 0.01-0.5   | 117       | 2.76%   |
| 8.01-16.0  | 94        | 2.22%   |
| 16.01-24.0 | 11        | 0.26%   |
| 24.01-32.0 | 7         | 0.16%   |
| 32.01-64.0 | 2         | 0.05%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2444      | 61.92%  |
| 2      | 952       | 24.12%  |
| 3      | 299       | 7.58%   |
| 4      | 115       | 2.91%   |
| 5      | 50        | 1.27%   |
| 0      | 44        | 1.11%   |
| 6      | 19        | 0.48%   |
| 7      | 13        | 0.33%   |
| 10     | 4         | 0.1%    |
| 9      | 3         | 0.08%   |
| 8      | 3         | 0.08%   |
| 11     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2026      | 52.36%  |
| No        | 1843      | 47.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3500      | 91.1%   |
| No        | 342       | 8.9%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2761      | 71.38%  |
| No        | 1107      | 28.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2206      | 56.75%  |
| Yes       | 1681      | 43.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 600       | 15.54%  |
| Germany      | 487       | 12.61%  |
| France       | 355       | 9.19%   |
| Italy        | 291       | 7.54%   |
| Russia       | 245       | 6.35%   |
| Brazil       | 221       | 5.72%   |
| Canada       | 145       | 3.76%   |
| UK           | 140       | 3.63%   |
| Spain        | 122       | 3.16%   |
| Netherlands  | 94        | 2.43%   |
| Australia    | 79        | 2.05%   |
| Poland       | 70        | 1.81%   |
| Ukraine      | 55        | 1.42%   |
| Argentina    | 54        | 1.4%    |
| Belgium      | 50        | 1.3%    |
| Hungary      | 44        | 1.14%   |
| Czechia      | 44        | 1.14%   |
| Mexico       | 43        | 1.11%   |
| Japan        | 41        | 1.06%   |
| Finland      | 39        | 1.01%   |
| Sweden       | 38        | 0.98%   |
| Portugal     | 34        | 0.88%   |
| India        | 33        | 0.85%   |
| Greece       | 33        | 0.85%   |
| Indonesia    | 27        | 0.7%    |
| Austria      | 27        | 0.7%    |
| Bulgaria     | 25        | 0.65%   |
| Romania      | 22        | 0.57%   |
| Turkey       | 21        | 0.54%   |
| Switzerland  | 19        | 0.49%   |
| Slovakia     | 18        | 0.47%   |
| Iran         | 17        | 0.44%   |
| Colombia     | 17        | 0.44%   |
| Taiwan       | 15        | 0.39%   |
| Norway       | 15        | 0.39%   |
| Venezuela    | 14        | 0.36%   |
| South Africa | 14        | 0.36%   |
| Israel       | 13        | 0.34%   |
| Slovenia     | 11        | 0.28%   |
| Belarus      | 11        | 0.28%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Paris             | 52        | 1.27%   |
| Berlin            | 46        | 1.13%   |
| Moscow            | 41        | 1.01%   |
| Voronezh          | 37        | 0.91%   |
| Milan             | 34        | 0.83%   |
| Rome              | 33        | 0.81%   |
| Sydney            | 25        | 0.61%   |
| Sao Paulo         | 25        | 0.61%   |
| Amsterdam         | 24        | 0.59%   |
| Athens            | 23        | 0.56%   |
| Munich            | 22        | 0.54%   |
| Warsaw            | 21        | 0.51%   |
| St Petersburg     | 21        | 0.51%   |
| Madrid            | 21        | 0.51%   |
| Hamburg           | 20        | 0.49%   |
| Budapest          | 20        | 0.49%   |
| Québec           | 19        | 0.47%   |
| Rio de Janeiro    | 17        | 0.42%   |
| Helsinki          | 17        | 0.42%   |
| Melbourne         | 16        | 0.39%   |
| Genoa             | 16        | 0.39%   |
| Barcelona         | 16        | 0.39%   |
| Oryol             | 15        | 0.37%   |
| Montreal          | 15        | 0.37%   |
| Kyiv              | 15        | 0.37%   |
| Vancouver         | 13        | 0.32%   |
| Turin             | 13        | 0.32%   |
| Prague            | 13        | 0.32%   |
| Buenos Aires      | 13        | 0.32%   |
| Tehran            | 12        | 0.29%   |
| Sofia             | 12        | 0.29%   |
| Leipzig           | 12        | 0.29%   |
| Vienna            | 11        | 0.27%   |
| Toronto           | 11        | 0.27%   |
| Stuttgart         | 11        | 0.27%   |
| Frankfurt am Main | 11        | 0.27%   |
| Cologne           | 11        | 0.27%   |
| Chicago           | 11        | 0.27%   |
| Belo Horizonte    | 11        | 0.27%   |
| Yokohama          | 10        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 972       | 1413   | 18.32%  |
| WDC                 | 920       | 1325   | 17.34%  |
| Samsung Electronics | 705       | 989    | 13.29%  |
| Toshiba             | 374       | 469    | 7.05%   |
| Hitachi             | 313       | 413    | 5.9%    |
| Unknown             | 254       | 321    | 4.79%   |
| Kingston            | 238       | 305    | 4.49%   |
| SanDisk             | 186       | 231    | 3.51%   |
| Crucial             | 140       | 187    | 2.64%   |
| HGST                | 106       | 126    | 2%      |
| Intel               | 97        | 139    | 1.83%   |
| SK hynix            | 81        | 94     | 1.53%   |
| A-DATA Technology   | 75        | 96     | 1.41%   |
| Fujitsu             | 67        | 84     | 1.26%   |
| Maxtor              | 60        | 85     | 1.13%   |
| China               | 55        | 65     | 1.04%   |
| Micron Technology   | 39        | 43     | 0.74%   |
| PNY                 | 36        | 46     | 0.68%   |
| Patriot             | 31        | 36     | 0.58%   |
| OCZ                 | 27        | 35     | 0.51%   |
| Intenso             | 27        | 34     | 0.51%   |
| Transcend           | 26        | 28     | 0.49%   |
| Phison              | 26        | 40     | 0.49%   |
| KIOXIA              | 18        | 24     | 0.34%   |
| Apple               | 18        | 26     | 0.34%   |
| SPCC                | 16        | 25     | 0.3%    |
| LITEONIT            | 16        | 19     | 0.3%    |
| LITEON              | 16        | 18     | 0.3%    |
| Apacer              | 16        | 22     | 0.3%    |
| Silicon Motion      | 15        | 16     | 0.28%   |
| Unknown             | 15        | 15     | 0.28%   |
| KingDian            | 12        | 18     | 0.23%   |
| JMicron Technology  | 12        | 12     | 0.23%   |
| ASMT                | 12        | 18     | 0.23%   |
| Hewlett-Packard     | 10        | 14     | 0.19%   |
| Lexar               | 9         | 9      | 0.17%   |
| KingSpec            | 8         | 10     | 0.15%   |
| USB3.0              | 7         | 10     | 0.13%   |
| Smartbuy            | 7         | 7      | 0.13%   |
| Plextor             | 7         | 9      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD        | 67        | 1.15%   |
| Unknown MMC Card  32GB                 | 51        | 0.88%   |
| Seagate ST500DM002-1BD142 500GB        | 51        | 0.88%   |
| Samsung SSD 860 EVO 500GB              | 42        | 0.72%   |
| Kingston SA400S37480G 480GB SSD        | 37        | 0.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 34        | 0.59%   |
| Samsung SSD 850 EVO 250GB              | 32        | 0.55%   |
| Seagate ST1000DM010-2EP102 1TB         | 31        | 0.53%   |
| Unknown MMC Card  64GB                 | 30        | 0.52%   |
| Seagate ST500LT012-1DG142 500GB        | 30        | 0.52%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 30        | 0.52%   |
| Samsung SSD 850 EVO 500GB              | 29        | 0.5%    |
| Toshiba MQ01ABF050 500GB               | 27        | 0.47%   |
| Toshiba MQ01ABD100 1TB                 | 26        | 0.45%   |
| Seagate ST1000LM035-1RK172 1TB         | 25        | 0.43%   |
| Kingston SA400S37120G 120GB SSD        | 25        | 0.43%   |
| Unknown SD/MMC/MS PRO 16GB             | 24        | 0.41%   |
| Seagate ST3500418AS 500GB              | 24        | 0.41%   |
| Seagate Expansion 1TB                  | 24        | 0.41%   |
| Toshiba DT01ACA100 1TB                 | 22        | 0.38%   |
| Seagate ST2000DM008-2FR102 2TB         | 21        | 0.36%   |
| HGST HTS721010A9E630 1TB               | 21        | 0.36%   |
| HGST HTS541010A9E680 1TB               | 21        | 0.36%   |
| Seagate ST9500325AS 500GB              | 20        | 0.34%   |
| Seagate ST1000DM003-1CH162 1TB         | 20        | 0.34%   |
| Seagate ST2000DM001-1CH164 2TB         | 19        | 0.33%   |
| Unknown MMC Card  128GB                | 18        | 0.31%   |
| Seagate ST31000528AS 1TB               | 18        | 0.31%   |
| Samsung SSD 860 EVO 250GB              | 18        | 0.31%   |
| Samsung SSD 860 EVO 1TB                | 18        | 0.31%   |
| Kingston SV300S37A120G 120GB SSD       | 18        | 0.31%   |
| Unknown MMC Card  16GB                 | 17        | 0.29%   |
| Seagate ST9320325AS 320GB              | 17        | 0.29%   |
| Seagate ST500LT012-9WS142 500GB        | 17        | 0.29%   |
| Crucial CT500MX500SSD1 500GB           | 17        | 0.29%   |
| WDC WD10JPVX-22JC3T0 1TB               | 16        | 0.28%   |
| Seagate ST4000DM004-2CV104 4TB         | 16        | 0.28%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 16        | 0.28%   |
| Hitachi HDS721010CLA332 1TB            | 16        | 0.28%   |
| Crucial CT240BX500SSD1 240GB           | 16        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 955       | 1386   | 32.95%  |
| WDC                 | 809       | 1162   | 27.92%  |
| Toshiba             | 317       | 401    | 10.94%  |
| Hitachi             | 313       | 413    | 10.8%   |
| Samsung Electronics | 186       | 261    | 6.42%   |
| HGST                | 106       | 126    | 3.66%   |
| Fujitsu             | 65        | 82     | 2.24%   |
| Maxtor              | 58        | 83     | 2%      |
| Unknown             | 25        | 28     | 0.86%   |
| USB3.0              | 7         | 10     | 0.24%   |
| IBM/Hitachi         | 7         | 7      | 0.24%   |
| JMicron Technology  | 6         | 6      | 0.21%   |
| ASMT                | 6         | 12     | 0.21%   |
| Intenso             | 5         | 6      | 0.17%   |
| SABRENT             | 4         | 4      | 0.14%   |
| Pioneer             | 3         | 3      | 0.1%    |
| Apple               | 3         | 4      | 0.1%    |
| WD MediaMax         | 2         | 2      | 0.07%   |
| PHD 3.0             | 2         | 2      | 0.07%   |
| HPE                 | 2         | 5      | 0.07%   |
| HGST HTS            | 2         | 2      | 0.07%   |
| Hewlett-Packard     | 2         | 2      | 0.07%   |
| ExcelStor           | 2         | 2      | 0.07%   |
| ASMedia             | 2         | 2      | 0.07%   |
| Apricorn            | 2         | 3      | 0.07%   |
| SAGE                | 1         | 1      | 0.03%   |
| LaCie               | 1         | 5      | 0.03%   |
| ICY BOX             | 1         | 1      | 0.03%   |
| Ext Hard            | 1         | 1      | 0.03%   |
| CLOVER              | 1         | 1      | 0.03%   |
| ACASIS              | 1         | 1      | 0.03%   |
| Unknown             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 367       | 491    | 23.27%  |
| Kingston            | 214       | 272    | 13.57%  |
| SanDisk             | 143       | 182    | 9.07%   |
| Crucial             | 130       | 177    | 8.24%   |
| WDC                 | 76        | 97     | 4.82%   |
| A-DATA Technology   | 64        | 84     | 4.06%   |
| China               | 55        | 65     | 3.49%   |
| Intel               | 51        | 75     | 3.23%   |
| PNY                 | 35        | 45     | 2.22%   |
| Patriot             | 31        | 36     | 1.97%   |
| Toshiba             | 30        | 37     | 1.9%    |
| Micron Technology   | 28        | 31     | 1.78%   |
| OCZ                 | 26        | 33     | 1.65%   |
| Transcend           | 24        | 24     | 1.52%   |
| SK hynix            | 22        | 22     | 1.4%    |
| Intenso             | 20        | 22     | 1.27%   |
| SPCC                | 16        | 25     | 1.01%   |
| LITEONIT            | 16        | 19     | 1.01%   |
| LITEON              | 16        | 18     | 1.01%   |
| Apacer              | 15        | 21     | 0.95%   |
| KingDian            | 12        | 18     | 0.76%   |
| Apple               | 10        | 14     | 0.63%   |
| Unknown             | 8         | 9      | 0.51%   |
| Lexar               | 8         | 8      | 0.51%   |
| Smartbuy            | 7         | 7      | 0.44%   |
| Plextor             | 7         | 9      | 0.44%   |
| KingSpec            | 7         | 9      | 0.44%   |
| GOODRAM             | 7         | 9      | 0.44%   |
| Hewlett-Packard     | 6         | 9      | 0.38%   |
| Corsair             | 6         | 6      | 0.38%   |
| ASMT                | 6         | 6      | 0.38%   |
| TO Exter            | 5         | 6      | 0.32%   |
| Team                | 5         | 9      | 0.32%   |
| Mushkin             | 5         | 5      | 0.32%   |
| Netac               | 4         | 7      | 0.25%   |
| FORESEE             | 4         | 5      | 0.25%   |
| Drevo               | 4         | 4      | 0.25%   |
| Dogfish             | 4         | 7      | 0.25%   |
| Vaseky              | 3         | 4      | 0.19%   |
| Seagate             | 3         | 3      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2439      | 4025   | 51.7%   |
| SSD     | 1416      | 2019   | 30.01%  |
| NVMe    | 553       | 728    | 11.72%  |
| MMC     | 233       | 298    | 4.94%   |
| Unknown | 77        | 97     | 1.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3300      | 5851   | 76.66%  |
| NVMe | 551       | 724    | 12.8%   |
| MMC  | 233       | 298    | 5.41%   |
| SAS  | 221       | 294    | 5.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2721      | 4100   | 67.52%  |
| 0.51-1.0   | 891       | 1259   | 22.11%  |
| 1.01-2.0   | 225       | 358    | 5.58%   |
| 3.01-4.0   | 75        | 128    | 1.86%   |
| 2.01-3.0   | 60        | 106    | 1.49%   |
| 4.01-10.0  | 53        | 86     | 1.32%   |
| 10.01-20.0 | 4         | 6      | 0.1%    |
| 0          | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1256      | 31.38%  |
| 251-500        | 898       | 22.44%  |
| 501-1000       | 512       | 12.79%  |
| 51-100         | 366       | 9.15%   |
| 21-50          | 266       | 6.65%   |
| 1001-2000      | 256       | 6.4%    |
| 1-20           | 181       | 4.52%   |
| More than 3000 | 146       | 3.65%   |
| 2001-3000      | 96        | 2.4%    |
| Unknown        | 25        | 0.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1701      | 40.94%  |
| 21-50          | 717       | 17.26%  |
| 101-250        | 518       | 12.47%  |
| 51-100         | 490       | 11.79%  |
| 251-500        | 287       | 6.91%   |
| 501-1000       | 207       | 4.98%   |
| 1001-2000      | 104       | 2.5%    |
| More than 3000 | 65        | 1.56%   |
| 2001-3000      | 41        | 0.99%   |
| Unknown        | 25        | 0.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 8         | 8      | 2.6%    |
| Seagate ST9500325AS 500GB           | 6         | 8      | 1.95%   |
| Seagate ST500DM002-1BD142 500GB     | 6         | 6      | 1.95%   |
| Toshiba MQ01ABD100 1TB              | 5         | 6      | 1.62%   |
| Seagate ST500LT012-9WS142 500GB     | 5         | 5      | 1.62%   |
| Seagate ST3500418AS 500GB           | 3         | 4      | 0.97%   |
| Seagate ST2000DM001-1CH164 2TB      | 3         | 4      | 0.97%   |
| Samsung Electronics HM321HI 320GB   | 3         | 4      | 0.97%   |
| Maxtor STM3160215AS 160GB           | 3         | 3      | 0.97%   |
| Hitachi HDS721050CLA362 500GB       | 3         | 3      | 0.97%   |
| HGST HTS545050A7E680 500GB          | 3         | 3      | 0.97%   |
| HGST HTS541010A9E680 1TB            | 3         | 3      | 0.97%   |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 2         | 2      | 0.65%   |
| WDC WD7500BPKX-00HPJT0 752GB        | 2         | 2      | 0.65%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 2      | 0.65%   |
| WDC WD4000FYYZ-01UL1B1 4TB          | 2         | 3      | 0.65%   |
| WDC WD3200AAKS-00L9A0 320GB         | 2         | 2      | 0.65%   |
| WDC WD1002FAEX-00Z3A0 1TB           | 2         | 2      | 0.65%   |
| Toshiba MK2552GSX 250GB             | 2         | 2      | 0.65%   |
| Toshiba DT01ACA100 1TB              | 2         | 2      | 0.65%   |
| Seagate ST9500423AS 500GB           | 2         | 2      | 0.65%   |
| Seagate ST9320423AS 320GB           | 2         | 2      | 0.65%   |
| Seagate ST9320325AS 320GB           | 2         | 2      | 0.65%   |
| Seagate ST9250410AS 250GB           | 2         | 2      | 0.65%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 2      | 0.65%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 2      | 0.65%   |
| Seagate ST3250318AS 250GB           | 2         | 4      | 0.65%   |
| Seagate ST320LT007-9ZV142 320GB     | 2         | 2      | 0.65%   |
| Seagate ST31000528AS 1TB            | 2         | 2      | 0.65%   |
| Seagate ST1000DM010-2EP102 1TB      | 2         | 2      | 0.65%   |
| Seagate ST1000DL002-9TT153 1TB      | 2         | 2      | 0.65%   |
| Samsung Electronics HD753LJ 752GB   | 2         | 3      | 0.65%   |
| Samsung Electronics HD103SJ 1TB     | 2         | 3      | 0.65%   |
| Samsung Electronics HD103SI 1TB     | 2         | 2      | 0.65%   |
| Samsung Electronics HD081GJ 80GB    | 2         | 2      | 0.65%   |
| Kingston SV300S37A120G 120GB SSD    | 2         | 2      | 0.65%   |
| Kingston SA400S37240G 240GB SSD     | 2         | 2      | 0.65%   |
| KingDian S100 32GB SSD              | 2         | 4      | 0.65%   |
| Hitachi HTS725050A9A364 500GB       | 2         | 3      | 0.65%   |
| Hitachi HTS725032A9A364 320GB       | 2         | 2      | 0.65%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 87        | 100    | 29%     |
| WDC                 | 62        | 71     | 20.67%  |
| Toshiba             | 28        | 34     | 9.33%   |
| Hitachi             | 28        | 35     | 9.33%   |
| Samsung Electronics | 23        | 30     | 7.67%   |
| HGST                | 10        | 13     | 3.33%   |
| Maxtor              | 7         | 7      | 2.33%   |
| Kingston            | 6         | 8      | 2%      |
| SK hynix            | 5         | 5      | 1.67%   |
| Intel               | 5         | 6      | 1.67%   |
| Fujitsu             | 5         | 6      | 1.67%   |
| Crucial             | 3         | 3      | 1%      |
| A-DATA Technology   | 3         | 4      | 1%      |
| SanDisk             | 2         | 2      | 0.67%   |
| OCZ                 | 2         | 2      | 0.67%   |
| Micron Technology   | 2         | 2      | 0.67%   |
| KingDian            | 2         | 4      | 0.67%   |
| Unknown             | 1         | 1      | 0.33%   |
| SSSTC               | 1         | 1      | 0.33%   |
| SPCC                | 1         | 1      | 0.33%   |
| PNY                 | 1         | 1      | 0.33%   |
| Netac               | 1         | 1      | 0.33%   |
| Neo Forza           | 1         | 1      | 0.33%   |
| Mushkin             | 1         | 1      | 0.33%   |
| LITEON              | 1         | 1      | 0.33%   |
| LDLC                | 1         | 1      | 0.33%   |
| JMicron Technology  | 1         | 1      | 0.33%   |
| ICY BOX             | 1         | 1      | 0.33%   |
| FORESEE             | 1         | 1      | 0.33%   |
| Drevo               | 1         | 1      | 0.33%   |
| Corsair             | 1         | 1      | 0.33%   |
| China               | 1         | 1      | 0.33%   |
| Avant               | 1         | 1      | 0.33%   |
| ASMT                | 1         | 4      | 0.33%   |
| Apple               | 1         | 1      | 0.33%   |
| Apacer              | 1         | 1      | 0.33%   |
| Unknown             | 1         | 1      | 0.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 87        | 100    | 35.66%  |
| WDC                 | 59        | 68     | 24.18%  |
| Hitachi             | 28        | 35     | 11.48%  |
| Toshiba             | 27        | 33     | 11.07%  |
| Samsung Electronics | 18        | 24     | 7.38%   |
| HGST                | 10        | 13     | 4.1%    |
| Maxtor              | 7         | 7      | 2.87%   |
| Fujitsu             | 5         | 6      | 2.05%   |
| JMicron Technology  | 1         | 1      | 0.41%   |
| ICY BOX             | 1         | 1      | 0.41%   |
| ASMT                | 1         | 4      | 0.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 230       | 292    | 80.99%  |
| SSD  | 52        | 61     | 18.31%  |
| NVMe | 2         | 2      | 0.7%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD20EARS-00J99B0 2TB         | 1         | 2      | 25%     |
| Toshiba DT01ACA200 2TB           | 1         | 1      | 25%     |
| Seagate ST500DM002-1BC142 500GB  | 1         | 1      | 25%     |
| A-DATA Technology SP800 32GB SSD | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 1         | 2      | 25%     |
| Toshiba           | 1         | 1      | 25%     |
| Seagate           | 1         | 1      | 25%     |
| A-DATA Technology | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2681      | 4992   | 66.15%  |
| Works    | 1090      | 1815   | 26.89%  |
| Malfunc  | 278       | 355    | 6.86%   |
| Failed   | 4         | 5      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2676      | 61.77%  |
| AMD                              | 654       | 15.1%   |
| Samsung Electronics              | 195       | 4.5%    |
| Nvidia                           | 140       | 3.23%   |
| SanDisk                          | 84        | 1.94%   |
| JMicron Technology               | 65        | 1.5%    |
| ASMedia Technology               | 63        | 1.45%   |
| VIA Technologies                 | 55        | 1.27%   |
| SK hynix                         | 52        | 1.2%    |
| Marvell Technology Group         | 45        | 1.04%   |
| Silicon Integrated Systems [SiS] | 39        | 0.9%    |
| Phison Electronics               | 31        | 0.72%   |
| Kingston Technology Company      | 30        | 0.69%   |
| Toshiba America Info Systems     | 26        | 0.6%    |
| Silicon Motion                   | 21        | 0.48%   |
| KIOXIA                           | 20        | 0.46%   |
| ADATA Technology                 | 15        | 0.35%   |
| LSI Logic / Symbios Logic        | 14        | 0.32%   |
| Micron/Crucial Technology        | 12        | 0.28%   |
| Micron Technology                | 12        | 0.28%   |
| Silicon Image                    | 10        | 0.23%   |
| Broadcom / LSI                   | 10        | 0.23%   |
| Realtek Semiconductor            | 9         | 0.21%   |
| Adaptec                          | 7         | 0.16%   |
| ULi Electronics                  | 6         | 0.14%   |
| Hewlett-Packard                  | 6         | 0.14%   |
| Apple                            | 5         | 0.12%   |
| Union Memory (Shenzhen)          | 4         | 0.09%   |
| Promise Technology               | 4         | 0.09%   |
| Integrated Technology Express    | 4         | 0.09%   |
| Seagate Technology               | 3         | 0.07%   |
| Lite-On Technology               | 3         | 0.07%   |
| Lenovo                           | 3         | 0.07%   |
| Shenzhen Longsys Electronics     | 2         | 0.05%   |
| INNOGRIT                         | 2         | 0.05%   |
| Solid State Storage Technology   | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.02%   |
| HighPoint Technologies           | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 386       | 7.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 174       | 3.2%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 171       | 3.15%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 153       | 2.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 145       | 2.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 130       | 2.39%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 130       | 2.39%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 118       | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 116       | 2.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 109       | 2.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 108       | 1.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 105       | 1.93%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 97        | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 94        | 1.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 88        | 1.62%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 78        | 1.44%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 74        | 1.36%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 70        | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 64        | 1.18%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 63        | 1.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 62        | 1.14%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 62        | 1.14%   |
| AMD 400 Series Chipset SATA Controller                                                  | 61        | 1.12%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 60        | 1.1%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 60        | 1.1%    |
| Nvidia MCP61 SATA Controller                                                            | 59        | 1.09%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 58        | 1.07%   |
| Intel SATA Controller [RAID mode]                                                       | 54        | 0.99%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 54        | 0.99%   |
| Nvidia MCP61 IDE                                                                        | 48        | 0.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 44        | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 44        | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 44        | 0.81%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 43        | 0.79%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 40        | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 40        | 0.74%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 39        | 0.72%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 38        | 0.7%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 37        | 0.68%   |
| Samsung NVMe SSD Controller 980                                                         | 37        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2601      | 56.41%  |
| IDE  | 1184      | 25.68%  |
| NVMe | 545       | 11.82%  |
| RAID | 256       | 5.55%   |
| SAS  | 13        | 0.28%   |
| SCSI | 12        | 0.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 2978      | 77.55%  |
| AMD          | 820       | 21.35%  |
| ARM          | 38        | 0.99%   |
| CentaurHauls | 4         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz           | 32        | 0.83%   |
| ARM Processor                           | 30        | 0.78%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 27        | 0.7%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 25        | 0.65%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 24        | 0.62%   |
| Intel Pentium 4 CPU 3.00GHz             | 23        | 0.6%    |
| Intel Core i5-8250U CPU @ 1.60GHz       | 22        | 0.57%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 22        | 0.57%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 22        | 0.57%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 21        | 0.54%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 21        | 0.54%   |
| Intel Atom CPU N450 @ 1.66GHz           | 21        | 0.54%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 21        | 0.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 20        | 0.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 19        | 0.49%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 19        | 0.49%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 19        | 0.49%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 18        | 0.47%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 18        | 0.47%   |
| Intel Core i3-10100 CPU @ 3.60GHz       | 18        | 0.47%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 18        | 0.47%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 18        | 0.47%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 18        | 0.47%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 17        | 0.44%   |
| Intel Core i3-2100 CPU @ 3.10GHz        | 17        | 0.44%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 17        | 0.44%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 16        | 0.42%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 16        | 0.42%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz    | 16        | 0.42%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 15        | 0.39%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 15        | 0.39%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz   | 15        | 0.39%   |
| Intel Celeron CPU N3050 @ 1.60GHz       | 15        | 0.39%   |
| AMD Ryzen 5 3600 6-Core Processor       | 15        | 0.39%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 14        | 0.36%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 14        | 0.36%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 14        | 0.36%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 14        | 0.36%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 14        | 0.36%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz    | 14        | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 649       | 16.84%  |
| Intel Core i7           | 484       | 12.56%  |
| Intel Core 2 Duo        | 311       | 8.07%   |
| Intel Core i3           | 300       | 7.78%   |
| Intel Celeron           | 259       | 6.72%   |
| Intel Atom              | 180       | 4.67%   |
| Other                   | 122       | 3.17%   |
| Intel Pentium           | 120       | 3.11%   |
| AMD Ryzen 5             | 114       | 2.96%   |
| Intel Xeon              | 98        | 2.54%   |
| Intel Pentium Dual-Core | 85        | 2.21%   |
| AMD Ryzen 7             | 80        | 2.08%   |
| Intel Pentium Dual      | 65        | 1.69%   |
| Intel Pentium 4         | 64        | 1.66%   |
| Intel Genuine           | 58        | 1.5%    |
| Intel Core 2            | 54        | 1.4%    |
| Intel Core 2 Quad       | 52        | 1.35%   |
| AMD FX                  | 50        | 1.3%    |
| AMD A8                  | 46        | 1.19%   |
| AMD Athlon 64 X2        | 41        | 1.06%   |
| AMD E1                  | 32        | 0.83%   |
| AMD A6                  | 31        | 0.8%    |
| AMD Ryzen 3             | 29        | 0.75%   |
| Intel Pentium M         | 28        | 0.73%   |
| AMD Ryzen 9             | 28        | 0.73%   |
| AMD Phenom II X4        | 28        | 0.73%   |
| AMD Athlon II X2        | 27        | 0.7%    |
| Intel Celeron M         | 24        | 0.62%   |
| AMD A4                  | 22        | 0.57%   |
| AMD A10                 | 22        | 0.57%   |
| AMD Turion 64 X2 Mobile | 20        | 0.52%   |
| AMD Sempron             | 20        | 0.52%   |
| AMD E                   | 19        | 0.49%   |
| AMD Athlon              | 18        | 0.47%   |
| Intel Pentium D         | 17        | 0.44%   |
| AMD E2                  | 16        | 0.42%   |
| AMD Athlon 64           | 16        | 0.42%   |
| Intel Core i9           | 15        | 0.39%   |
| AMD Ryzen 7 PRO         | 15        | 0.39%   |
| AMD Athlon II X4        | 12        | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1895      | 49.22%  |
| 4       | 1177      | 30.57%  |
| 1       | 344       | 8.94%   |
| 6       | 196       | 5.09%   |
| 8       | 149       | 3.87%   |
| 12      | 33        | 0.86%   |
| 16      | 19        | 0.49%   |
| 3       | 17        | 0.44%   |
| 10      | 7         | 0.18%   |
| Unknown | 4         | 0.1%    |
| 14      | 3         | 0.08%   |
| 64      | 2         | 0.05%   |
| 24      | 2         | 0.05%   |
| 20      | 2         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3792      | 98.75%  |
| 2       | 45        | 1.17%   |
| Unknown | 3         | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1934      | 50.3%   |
| 2       | 1906      | 49.57%  |
| Unknown | 4         | 0.1%    |
| 4       | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3621      | 94.27%  |
| 32-bit         | 193       | 5.02%   |
| Unknown        | 26        | 0.68%   |
| 64-bit         | 1         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 668       | 16.92%  |
| 0x206a7    | 264       | 6.69%   |
| 0x306a9    | 242       | 6.13%   |
| 0x1067a    | 231       | 5.85%   |
| 0x306c3    | 153       | 3.88%   |
| 0x6fd      | 142       | 3.6%    |
| 0x20655    | 86        | 2.18%   |
| 0x10676    | 81        | 2.05%   |
| 0x40651    | 68        | 1.72%   |
| 0x506e3    | 64        | 1.62%   |
| 0x30678    | 60        | 1.52%   |
| 0x906ea    | 59        | 1.49%   |
| 0x406c4    | 57        | 1.44%   |
| 0x6fb      | 53        | 1.34%   |
| 0x106ca    | 53        | 1.34%   |
| 0x406e3    | 52        | 1.32%   |
| 0x010000c8 | 51        | 1.29%   |
| 0x806ea    | 48        | 1.22%   |
| 0x6f6      | 48        | 1.22%   |
| 0x106c2    | 48        | 1.22%   |
| 0x806ec    | 45        | 1.14%   |
| 0x20652    | 45        | 1.14%   |
| 0x806c1    | 42        | 1.06%   |
| 0x306d4    | 42        | 1.06%   |
| 0x806e9    | 40        | 1.01%   |
| 0x906e9    | 38        | 0.96%   |
| 0x06000852 | 36        | 0.91%   |
| 0x6e8      | 35        | 0.89%   |
| 0x08108109 | 35        | 0.89%   |
| 0x6d8      | 34        | 0.86%   |
| 0x406c3    | 34        | 0.86%   |
| 0x106e5    | 33        | 0.84%   |
| 0x05000119 | 32        | 0.81%   |
| 0x08701021 | 31        | 0.79%   |
| 0x0800820d | 31        | 0.79%   |
| 0x07030105 | 28        | 0.71%   |
| 0x0700010f | 26        | 0.66%   |
| 0x06001119 | 26        | 0.66%   |
| 0xa0652    | 24        | 0.61%   |
| 0x03000027 | 24        | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 349       | 9.06%   |
| KabyLake         | 328       | 8.52%   |
| SandyBridge      | 311       | 8.08%   |
| Core             | 299       | 7.77%   |
| IvyBridge        | 283       | 7.35%   |
| Haswell          | 267       | 6.94%   |
| Silvermont       | 184       | 4.78%   |
| Westmere         | 166       | 4.31%   |
| Skylake          | 143       | 3.71%   |
| Bonnell          | 127       | 3.3%    |
| K8 Hammer        | 126       | 3.27%   |
| K10              | 110       | 2.86%   |
| P6               | 100       | 2.6%    |
| Zen 2            | 98        | 2.55%   |
| Zen+             | 91        | 2.36%   |
| NetBurst         | 90        | 2.34%   |
| Unknown          | 72        | 1.87%   |
| Piledriver       | 71        | 1.84%   |
| CometLake        | 55        | 1.43%   |
| Broadwell        | 55        | 1.43%   |
| Zen              | 53        | 1.38%   |
| TigerLake        | 53        | 1.38%   |
| Nehalem          | 51        | 1.32%   |
| Bobcat           | 47        | 1.22%   |
| Zen 3            | 37        | 0.96%   |
| Puma             | 37        | 0.96%   |
| Goldmont plus    | 37        | 0.96%   |
| Excavator        | 37        | 0.96%   |
| Goldmont         | 34        | 0.88%   |
| Icelake          | 31        | 0.81%   |
| Jaguar           | 30        | 0.78%   |
| K10 Llano        | 27        | 0.7%    |
| Steamroller      | 13        | 0.34%   |
| K8 & K10 hybrid  | 11        | 0.29%   |
| Bulldozer        | 10        | 0.26%   |
| Alderlake Hybrid | 8         | 0.21%   |
| K6               | 6         | 0.16%   |
| Tremont          | 3         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2160      | 50.67%  |
| Nvidia                           | 1084      | 25.43%  |
| AMD                              | 943       | 22.12%  |
| Silicon Integrated Systems [SiS] | 25        | 0.59%   |
| Matrox Electronics Systems       | 23        | 0.54%   |
| VIA Technologies                 | 19        | 0.45%   |
| ASPEED Technology                | 7         | 0.16%   |
| S3 Graphics                      | 1         | 0.02%   |
| Alliance Semiconductor           | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 228       | 5.02%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 149       | 3.28%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 116       | 2.56%   |
| Intel Core Processor Integrated Graphics Controller                                      | 102       | 2.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 99        | 2.18%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 88        | 1.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 84        | 1.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 82        | 1.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 82        | 1.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 75        | 1.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 73        | 1.61%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 60        | 1.32%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 58        | 1.28%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 57        | 1.26%   |
| Intel UHD Graphics 620                                                                   | 56        | 1.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 56        | 1.23%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 53        | 1.17%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 52        | 1.15%   |
| Intel HD Graphics 620                                                                    | 50        | 1.1%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 47        | 1.04%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 46        | 1.01%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 46        | 1.01%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 46        | 1.01%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 42        | 0.93%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 40        | 0.88%   |
| Intel HD Graphics 5500                                                                   | 39        | 0.86%   |
| Intel HD Graphics 530                                                                    | 39        | 0.86%   |
| AMD Renoir                                                                               | 38        | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 34        | 0.75%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 34        | 0.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 31        | 0.68%   |
| Nvidia GT218 [GeForce 210]                                                               | 30        | 0.66%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 29        | 0.64%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 28        | 0.62%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 28        | 0.62%   |
| Intel HD Graphics 500                                                                    | 27        | 0.59%   |
| Intel HD Graphics 630                                                                    | 26        | 0.57%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 25        | 0.55%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 24        | 0.53%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 23        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| 1 x Intel                            | 1757      | 45.49%  |
| 1 x Nvidia                           | 762       | 19.73%  |
| 1 x AMD                              | 758       | 19.63%  |
| Intel + Nvidia                       | 276       | 7.15%   |
| Intel + AMD                          | 85        | 2.2%    |
| 2 x AMD                              | 66        | 1.71%   |
| Other                                | 45        | 1.17%   |
| AMD + Nvidia                         | 26        | 0.67%   |
| 1 x SiS                              | 25        | 0.65%   |
| 1 x VIA                              | 19        | 0.49%   |
| 1 x Matrox                           | 17        | 0.44%   |
| 2 x Nvidia                           | 5         | 0.13%   |
| Nvidia + ASPEED                      | 5         | 0.13%   |
| Nvidia + Matrox                      | 3         | 0.08%   |
| 2 x Intel                            | 2         | 0.05%   |
| 1 x ASPEED                           | 2         | 0.05%   |
| AMD + Matrox                         | 2         | 0.05%   |
| 3 x AMD                              | 1         | 0.03%   |
| 2 x Nvidia + 1 x Matrox              | 1         | 0.03%   |
| 2 x AMD + 1 x Nvidia                 | 1         | 0.03%   |
| 2 x AMD + 1 x Alliance Semiconductor | 1         | 0.03%   |
| 1 x S3 Graphics                      | 1         | 0.03%   |
| Intel + 2 x AMD                      | 1         | 0.03%   |
| Intel + AMD + 1 x Nvidia             | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3099      | 80.12%  |
| Proprietary | 582       | 15.05%  |
| Unknown     | 187       | 4.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1970      | 50.2%   |
| 0.01-0.5   | 784       | 19.98%  |
| 1.01-2.0   | 455       | 11.6%   |
| 0.51-1.0   | 357       | 9.1%    |
| 3.01-4.0   | 196       | 4.99%   |
| 7.01-8.0   | 76        | 1.94%   |
| 5.01-6.0   | 46        | 1.17%   |
| 8.01-16.0  | 19        | 0.48%   |
| 2.01-3.0   | 16        | 0.41%   |
| 4.01-5.0   | 2         | 0.05%   |
| 16.01-24.0 | 2         | 0.05%   |
| 32.01-64.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 577       | 14.63%  |
| AU Optronics            | 438       | 11.11%  |
| LG Display              | 337       | 8.54%   |
| Chimei Innolux          | 221       | 5.6%    |
| Dell                    | 212       | 5.38%   |
| BOE                     | 205       | 5.2%    |
| Goldstar                | 192       | 4.87%   |
| Hewlett-Packard         | 148       | 3.75%   |
| Acer                    | 145       | 3.68%   |
| Philips                 | 100       | 2.54%   |
| Chi Mei Optoelectronics | 100       | 2.54%   |
| AOC                     | 100       | 2.54%   |
| Lenovo                  | 94        | 2.38%   |
| Ancor Communications    | 81        | 2.05%   |
| BenQ                    | 71        | 1.8%    |
| LG Philips              | 69        | 1.75%   |
| Apple                   | 55        | 1.39%   |
| ViewSonic               | 53        | 1.34%   |
| HannStar                | 50        | 1.27%   |
| Iiyama                  | 41        | 1.04%   |
| Unknown                 | 38        | 0.96%   |
| Sony                    | 38        | 0.96%   |
| LG Electronics          | 35        | 0.89%   |
| InfoVision              | 32        | 0.81%   |
| Sharp                   | 29        | 0.74%   |
| Fujitsu Siemens         | 26        | 0.66%   |
| CPT                     | 24        | 0.61%   |
| Panasonic               | 22        | 0.56%   |
| NEC Computers           | 22        | 0.56%   |
| PANDA                   | 19        | 0.48%   |
| Toshiba                 | 17        | 0.43%   |
| Eizo                    | 17        | 0.43%   |
| ASUSTek Computer        | 15        | 0.38%   |
| Vizio                   | 14        | 0.35%   |
| Medion                  | 14        | 0.35%   |
| Quanta Display          | 11        | 0.28%   |
| Vestel Elektronik       | 9         | 0.23%   |
| Lenovo Group Limited    | 8         | 0.2%    |
| IBM                     | 8         | 0.2%    |
| DENON                   | 8         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 22        | 0.54%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 20        | 0.49%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 18        | 0.44%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 17        | 0.42%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 16        | 0.39%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                       | 16        | 0.39%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 13        | 0.32%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 13        | 0.32%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.29%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.27%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 11        | 0.27%   |
| Panasonic TV MEIA296 3840x2160 1872x1053mm 84.6-inch                     | 10        | 0.25%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 10        | 0.25%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                      | 10        | 0.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 10        | 0.25%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 10        | 0.25%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 10        | 0.25%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                         | 9         | 0.22%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 9         | 0.22%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 8         | 0.2%    |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 8         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 8         | 0.2%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 8         | 0.2%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 8         | 0.2%    |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 8         | 0.2%    |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 8         | 0.2%    |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 8         | 0.2%    |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch     | 8         | 0.2%    |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 7         | 0.17%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 7         | 0.17%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 7         | 0.17%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 7         | 0.17%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 7         | 0.17%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                     | 7         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 7         | 0.17%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 7         | 0.17%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 7         | 0.17%   |
| AU Optronics LCD Monitor AUO205C 1366x768 256x144mm 11.6-inch            | 7         | 0.17%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 7         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1298      | 33.72%  |
| 1366x768 (WXGA)    | 853       | 22.16%  |
| 1280x800 (WXGA)    | 247       | 6.42%   |
| 1280x1024 (SXGA)   | 226       | 5.87%   |
| 1600x900 (HD+)     | 195       | 5.07%   |
| 1440x900 (WXGA+)   | 176       | 4.57%   |
| 1680x1050 (WSXGA+) | 147       | 3.82%   |
| 3840x2160 (4K)     | 140       | 3.64%   |
| 1920x1200 (WUXGA)  | 85        | 2.21%   |
| 2560x1440 (QHD)    | 84        | 2.18%   |
| 1024x600           | 67        | 1.74%   |
| Unknown            | 59        | 1.53%   |
| 1024x768 (XGA)     | 44        | 1.14%   |
| 1360x768           | 41        | 1.07%   |
| 3840x1080          | 23        | 0.6%    |
| 1920x540           | 17        | 0.44%   |
| 1600x1200          | 14        | 0.36%   |
| 2560x1600          | 13        | 0.34%   |
| 3440x1440          | 12        | 0.31%   |
| 2560x1080          | 12        | 0.31%   |
| 1280x720 (HD)      | 9         | 0.23%   |
| 2288x1287          | 7         | 0.18%   |
| 3200x1080          | 6         | 0.16%   |
| 1400x1050          | 5         | 0.13%   |
| 5120x1440          | 4         | 0.1%    |
| 3840x1200          | 4         | 0.1%    |
| 3200x1800 (QHD+)   | 4         | 0.1%    |
| 2880x1800          | 4         | 0.1%    |
| 2160x1440          | 4         | 0.1%    |
| 2048x1152          | 3         | 0.08%   |
| 4480x1440          | 2         | 0.05%   |
| 3840x2400          | 2         | 0.05%   |
| 3840x1600          | 2         | 0.05%   |
| 3600x1080          | 2         | 0.05%   |
| 3286x1080          | 2         | 0.05%   |
| 3200x900           | 2         | 0.05%   |
| 2960x1050          | 2         | 0.05%   |
| 2048x1536          | 2         | 0.05%   |
| 1280x960           | 2         | 0.05%   |
| 800x600            | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 951       | 24.22%  |
| 17      | 300       | 7.64%   |
| 14      | 300       | 7.64%   |
| Unknown | 289       | 7.36%   |
| 13      | 263       | 6.7%    |
| 23      | 231       | 5.88%   |
| 24      | 209       | 5.32%   |
| 21      | 205       | 5.22%   |
| 19      | 187       | 4.76%   |
| 27      | 163       | 4.15%   |
| 18      | 130       | 3.31%   |
| 20      | 95        | 2.42%   |
| 22      | 82        | 2.09%   |
| 12      | 76        | 1.94%   |
| 10      | 75        | 1.91%   |
| 31      | 70        | 1.78%   |
| 11      | 65        | 1.66%   |
| 84      | 29        | 0.74%   |
| 72      | 21        | 0.53%   |
| 54      | 20        | 0.51%   |
| 40      | 18        | 0.46%   |
| 26      | 17        | 0.43%   |
| 32      | 16        | 0.41%   |
| 16      | 16        | 0.41%   |
| 34      | 15        | 0.38%   |
| 25      | 13        | 0.33%   |
| 52      | 8         | 0.2%    |
| 48      | 8         | 0.2%    |
| 28      | 8         | 0.2%    |
| 37      | 7         | 0.18%   |
| 46      | 4         | 0.1%    |
| 8       | 4         | 0.1%    |
| 49      | 3         | 0.08%   |
| 47      | 3         | 0.08%   |
| 29      | 3         | 0.08%   |
| 142     | 2         | 0.05%   |
| 74      | 2         | 0.05%   |
| 65      | 2         | 0.05%   |
| 60      | 2         | 0.05%   |
| 57      | 2         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1477      | 38.08%  |
| 501-600        | 580       | 14.95%  |
| 401-500        | 576       | 14.85%  |
| 201-300        | 348       | 8.97%   |
| 351-400        | 330       | 8.51%   |
| Unknown        | 289       | 7.45%   |
| 601-700        | 103       | 2.66%   |
| 1501-2000      | 53        | 1.37%   |
| 1001-1500      | 52        | 1.34%   |
| 701-800        | 32        | 0.82%   |
| 801-900        | 29        | 0.75%   |
| 101-200        | 5         | 0.13%   |
| 901-1000       | 3         | 0.08%   |
| More than 2000 | 2         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2410      | 65.97%  |
| 16/10   | 626       | 17.14%  |
| Unknown | 262       | 7.17%   |
| 5/4     | 213       | 5.83%   |
| 4/3     | 77        | 2.11%   |
| 3/2     | 23        | 0.63%   |
| 21/9    | 20        | 0.55%   |
| 6/5     | 10        | 0.27%   |
| 32/9    | 4         | 0.11%   |
| 1.00    | 4         | 0.11%   |
| 3.73    | 1         | 0.03%   |
| 3.20    | 1         | 0.03%   |
| 1.96    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 948       | 24.28%  |
| 201-250        | 589       | 15.09%  |
| 81-90          | 452       | 11.58%  |
| 151-200        | 365       | 9.35%   |
| Unknown        | 289       | 7.4%    |
| 141-150        | 212       | 5.43%   |
| 301-350        | 172       | 4.41%   |
| 121-130        | 140       | 3.59%   |
| 351-500        | 109       | 2.79%   |
| More than 1000 | 97        | 2.48%   |
| 71-80          | 95        | 2.43%   |
| 251-300        | 93        | 2.38%   |
| 41-50          | 74        | 1.9%    |
| 61-70          | 71        | 1.82%   |
| 51-60          | 66        | 1.69%   |
| 131-140        | 49        | 1.26%   |
| 501-1000       | 42        | 1.08%   |
| 91-100         | 24        | 0.61%   |
| 111-120        | 12        | 0.31%   |
| 1-40           | 5         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1483      | 39.2%   |
| 101-120       | 1083      | 28.63%  |
| 121-160       | 718       | 18.98%  |
| Unknown       | 289       | 7.64%   |
| 161-240       | 93        | 2.46%   |
| 1-50          | 87        | 2.3%    |
| More than 240 | 30        | 0.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3233      | 82.77%  |
| 2     | 464       | 11.88%  |
| 0     | 174       | 4.45%   |
| 3     | 31        | 0.79%   |
| 4     | 4         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1987      | 33.7%   |
| Intel                             | 1560      | 26.46%  |
| Qualcomm Atheros                  | 756       | 12.82%  |
| Broadcom                          | 433       | 7.34%   |
| Marvell Technology Group          | 142       | 2.41%   |
| Broadcom Limited                  | 117       | 1.98%   |
| Nvidia                            | 114       | 1.93%   |
| Ralink Technology                 | 88        | 1.49%   |
| Ralink                            | 81        | 1.37%   |
| TP-Link                           | 65        | 1.1%    |
| VIA Technologies                  | 41        | 0.7%    |
| Qualcomm Atheros Communications   | 37        | 0.63%   |
| Silicon Integrated Systems [SiS]  | 32        | 0.54%   |
| Samsung Electronics               | 30        | 0.51%   |
| MediaTek                          | 30        | 0.51%   |
| Huawei Technologies               | 29        | 0.49%   |
| D-Link System                     | 26        | 0.44%   |
| NetGear                           | 22        | 0.37%   |
| JMicron Technology                | 22        | 0.37%   |
| Sierra Wireless                   | 16        | 0.27%   |
| D-Link                            | 16        | 0.27%   |
| Ericsson Business Mobile Networks | 15        | 0.25%   |
| Attansic Technology               | 15        | 0.25%   |
| ASIX Electronics                  | 15        | 0.25%   |
| Xiaomi                            | 11        | 0.19%   |
| Dell                              | 11        | 0.19%   |
| ASUSTek Computer                  | 11        | 0.19%   |
| Edimax Technology                 | 10        | 0.17%   |
| Qualcomm                          | 9         | 0.15%   |
| Lenovo                            | 9         | 0.15%   |
| DisplayLink                       | 9         | 0.15%   |
| Aquantia                          | 9         | 0.15%   |
| AMD                               | 8         | 0.14%   |
| Belkin Components                 | 7         | 0.12%   |
| Microsoft                         | 6         | 0.1%    |
| Fibocom                           | 6         | 0.1%    |
| ZyDAS                             | 5         | 0.08%   |
| ULi Electronics                   | 5         | 0.08%   |
| Sitecom Europe                    | 5         | 0.08%   |
| Linksys                           | 5         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1266      | 18.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 328       | 4.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 172       | 2.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 114       | 1.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 94        | 1.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 92        | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 91        | 1.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 89        | 1.3%    |
| Intel Wi-Fi 6 AX200                                                     | 89        | 1.3%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 72        | 1.05%   |
| Intel Wireless 7260                                                     | 72        | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 66        | 0.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 60        | 0.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 60        | 0.88%   |
| Intel Wireless 8265 / 8275                                              | 58        | 0.85%   |
| Intel Wireless 7265                                                     | 58        | 0.85%   |
| Intel Ethernet Connection I217-LM                                       | 58        | 0.85%   |
| Nvidia MCP61 Ethernet                                                   | 52        | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 51        | 0.75%   |
| Intel Wireless 3165                                                     | 48        | 0.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 46        | 0.67%   |
| Intel I211 Gigabit Network Connection                                   | 46        | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 43        | 0.63%   |
| Intel Wireless 8260                                                     | 41        | 0.6%    |
| Intel Wi-Fi 6 AX201                                                     | 41        | 0.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 40        | 0.59%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 40        | 0.59%   |
| Intel 82579V Gigabit Network Connection                                 | 38        | 0.56%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 38        | 0.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 36        | 0.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 35        | 0.51%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 34        | 0.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 34        | 0.5%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 34        | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                       | 33        | 0.48%   |
| Intel Ethernet Connection (2) I219-V                                    | 33        | 0.48%   |
| Ralink MT7601U Wireless Adapter                                         | 32        | 0.47%   |
| Qualcomm Atheros AR9271 802.11n                                         | 32        | 0.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 31        | 0.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 30        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1065      | 36.13%  |
| Qualcomm Atheros                      | 615       | 20.86%  |
| Realtek Semiconductor                 | 496       | 16.82%  |
| Broadcom                              | 260       | 8.82%   |
| Ralink Technology                     | 88        | 2.99%   |
| Ralink                                | 81        | 2.75%   |
| TP-Link                               | 61        | 2.07%   |
| Broadcom Limited                      | 56        | 1.9%    |
| Qualcomm Atheros Communications       | 37        | 1.26%   |
| NetGear                               | 22        | 0.75%   |
| MediaTek                              | 19        | 0.64%   |
| D-Link System                         | 18        | 0.61%   |
| Sierra Wireless                       | 16        | 0.54%   |
| D-Link                                | 15        | 0.51%   |
| Edimax Technology                     | 10        | 0.34%   |
| ASUSTek Computer                      | 10        | 0.34%   |
| Dell                                  | 7         | 0.24%   |
| Belkin Components                     | 7         | 0.24%   |
| Qualcomm                              | 6         | 0.2%    |
| Microsoft                             | 6         | 0.2%    |
| Fibocom                               | 6         | 0.2%    |
| ZyDAS                                 | 5         | 0.17%   |
| Sitecom Europe                        | 5         | 0.17%   |
| Linksys                               | 5         | 0.17%   |
| Marvell Technology Group              | 4         | 0.14%   |
| IMC Networks                          | 4         | 0.14%   |
| AVM                                   | 4         | 0.14%   |
| TRENDnet                              | 3         | 0.1%    |
| Ericsson Business Mobile Networks     | 3         | 0.1%    |
| Hewlett-Packard                       | 2         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.07%   |
| ZyXEL Communications                  | 1         | 0.03%   |
| Xiaomi                                | 1         | 0.03%   |
| Winbond Electronics                   | 1         | 0.03%   |
| Texas Instruments                     | 1         | 0.03%   |
| Philips (or NXP)                      | 1         | 0.03%   |
| Micro Star International              | 1         | 0.03%   |
| Gemtek                                | 1         | 0.03%   |
| BUFFALO                               | 1         | 0.03%   |
| AboCom Systems                        | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 114       | 3.83%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 94        | 3.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 92        | 3.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 91        | 3.06%   |
| Intel Wi-Fi 6 AX200                                                     | 89        | 2.99%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 72        | 2.42%   |
| Intel Wireless 7260                                                     | 72        | 2.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 66        | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 60        | 2.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 60        | 2.01%   |
| Intel Wireless 8265 / 8275                                              | 58        | 1.95%   |
| Intel Wireless 7265                                                     | 58        | 1.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 51        | 1.71%   |
| Intel Wireless 3165                                                     | 48        | 1.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 46        | 1.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 43        | 1.44%   |
| Intel Wireless 8260                                                     | 41        | 1.38%   |
| Intel Wi-Fi 6 AX201                                                     | 41        | 1.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 40        | 1.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 36        | 1.21%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 35        | 1.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 34        | 1.14%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 34        | 1.14%   |
| Ralink MT7601U Wireless Adapter                                         | 32        | 1.07%   |
| Qualcomm Atheros AR9271 802.11n                                         | 32        | 1.07%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 31        | 1.04%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 30        | 1.01%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 28        | 0.94%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 28        | 0.94%   |
| Broadcom BCM43142 802.11b/g/n                                           | 28        | 0.94%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 27        | 0.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 27        | 0.91%   |
| Intel Centrino Advanced-N 6200                                          | 27        | 0.91%   |
| Intel Wireless 3160                                                     | 26        | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 26        | 0.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 26        | 0.87%   |
| Intel Wireless-AC 9260                                                  | 25        | 0.84%   |
| Intel Centrino Ultimate-N 6300                                          | 24        | 0.81%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 24        | 0.81%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 23        | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1774      | 47.91%  |
| Intel                            | 894       | 24.14%  |
| Qualcomm Atheros                 | 231       | 6.24%   |
| Broadcom                         | 214       | 5.78%   |
| Marvell Technology Group         | 138       | 3.73%   |
| Nvidia                           | 113       | 3.05%   |
| Broadcom Limited                 | 62        | 1.67%   |
| VIA Technologies                 | 41        | 1.11%   |
| Silicon Integrated Systems [SiS] | 30        | 0.81%   |
| Samsung Electronics              | 29        | 0.78%   |
| JMicron Technology               | 22        | 0.59%   |
| Huawei Technologies              | 18        | 0.49%   |
| Attansic Technology              | 15        | 0.41%   |
| ASIX Electronics                 | 15        | 0.41%   |
| MediaTek                         | 12        | 0.32%   |
| Xiaomi                           | 10        | 0.27%   |
| Lenovo                           | 9         | 0.24%   |
| DisplayLink                      | 9         | 0.24%   |
| Aquantia                         | 9         | 0.24%   |
| D-Link System                    | 8         | 0.22%   |
| HTC (High Tech Computer)         | 5         | 0.14%   |
| TP-Link                          | 4         | 0.11%   |
| LG Electronics                   | 4         | 0.11%   |
| ZTE WCDMA Technologies MSM       | 3         | 0.08%   |
| Qualcomm                         | 3         | 0.08%   |
| IBM                              | 3         | 0.08%   |
| Apple                            | 3         | 0.08%   |
| Spreadtrum Communications        | 2         | 0.05%   |
| National Semiconductor           | 2         | 0.05%   |
| Motorola PCS                     | 2         | 0.05%   |
| Insyde Software                  | 2         | 0.05%   |
| Hewlett-Packard                  | 2         | 0.05%   |
| 3Com                             | 2         | 0.05%   |
| ULi Electronics                  | 1         | 0.03%   |
| T & A Mobile Phones              | 1         | 0.03%   |
| OPPO                             | 1         | 0.03%   |
| Microchip Technology             | 1         | 0.03%   |
| Mellanox Technologies            | 1         | 0.03%   |
| ICS Advent                       | 1         | 0.03%   |
| Hangzhou Silan Microelectronics  | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1266      | 33.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 328       | 8.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 172       | 4.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 89        | 2.37%   |
| Intel Ethernet Connection I217-LM                                 | 58        | 1.55%   |
| Nvidia MCP61 Ethernet                                             | 52        | 1.39%   |
| Intel I211 Gigabit Network Connection                             | 46        | 1.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 40        | 1.07%   |
| Intel 82579V Gigabit Network Connection                           | 38        | 1.01%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 38        | 1.01%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 34        | 0.91%   |
| Realtek RTL8125 2.5GbE Controller                                 | 33        | 0.88%   |
| Intel Ethernet Connection (2) I219-V                              | 33        | 0.88%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 30        | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 28        | 0.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 27        | 0.72%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 27        | 0.72%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 27        | 0.72%   |
| Intel 82577LM Gigabit Network Connection                          | 26        | 0.69%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 25        | 0.67%   |
| Intel Ethernet Connection I219-LM                                 | 25        | 0.67%   |
| Intel 82567LM Gigabit Network Connection                          | 25        | 0.67%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 21        | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 20        | 0.53%   |
| Intel Ethernet Connection (7) I219-V                              | 20        | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 19        | 0.51%   |
| Intel Ethernet Connection (4) I219-LM                             | 19        | 0.51%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 18        | 0.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 18        | 0.48%   |
| Intel 82566MM Gigabit Network Connection                          | 18        | 0.48%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 17        | 0.45%   |
| Intel PRO/100 VE Network Connection                               | 17        | 0.45%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 17        | 0.45%   |
| Intel 82573L Gigabit Ethernet Controller                          | 17        | 0.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 17        | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 16        | 0.43%   |
| Nvidia MCP79 Ethernet                                             | 16        | 0.43%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 15        | 0.4%    |
| Intel 82574L Gigabit Network Connection                           | 15        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3494      | 55%     |
| WiFi     | 2756      | 43.38%  |
| Modem    | 97        | 1.53%   |
| Unknown  | 6         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2186      | 55.17%  |
| Ethernet | 1776      | 44.83%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2150      | 55.74%  |
| 1     | 1519      | 39.38%  |
| 0     | 107       | 2.77%   |
| 3     | 56        | 1.45%   |
| 4     | 19        | 0.49%   |
| 5     | 3         | 0.08%   |
| 10    | 1         | 0.03%   |
| 8     | 1         | 0.03%   |
| 6     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3309      | 84.93%  |
| Yes  | 587       | 15.07%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 650       | 38.12%  |
| Broadcom                        | 170       | 9.97%   |
| Qualcomm Atheros Communications | 155       | 9.09%   |
| Realtek Semiconductor           | 148       | 8.68%   |
| Cambridge Silicon Radio         | 112       | 6.57%   |
| Apple                           | 61        | 3.58%   |
| Lite-On Technology              | 59        | 3.46%   |
| IMC Networks                    | 56        | 3.28%   |
| Foxconn / Hon Hai               | 56        | 3.28%   |
| Dell                            | 54        | 3.17%   |
| Hewlett-Packard                 | 49        | 2.87%   |
| ASUSTek Computer                | 28        | 1.64%   |
| Toshiba                         | 20        | 1.17%   |
| Ralink                          | 17        | 1%      |
| Alps Electric                   | 14        | 0.82%   |
| Integrated System Solution      | 8         | 0.47%   |
| Realtek                         | 7         | 0.41%   |
| Ralink Technology               | 6         | 0.35%   |
| MediaTek                        | 6         | 0.35%   |
| Foxconn International           | 6         | 0.35%   |
| Chicony Electronics             | 4         | 0.23%   |
| Edimax Technology               | 3         | 0.18%   |
| Taiyo Yuden                     | 2         | 0.12%   |
| Qcom                            | 2         | 0.12%   |
| Fujitsu                         | 2         | 0.12%   |
| USI                             | 1         | 0.06%   |
| TP-Link                         | 1         | 0.06%   |
| Syntek                          | 1         | 0.06%   |
| Sitecom Europe                  | 1         | 0.06%   |
| Micro Star International        | 1         | 0.06%   |
| Marvell Semiconductor           | 1         | 0.06%   |
| Logitech                        | 1         | 0.06%   |
| Conwise Technology              | 1         | 0.06%   |
| Askey Computer                  | 1         | 0.06%   |
| Unknown                         | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 289       | 16.94%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 112       | 6.57%   |
| Intel AX201 Bluetooth                                                               | 90        | 5.28%   |
| Intel AX200 Bluetooth                                                               | 89        | 5.22%   |
| Realtek Bluetooth Radio                                                             | 85        | 4.98%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 67        | 3.93%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 63        | 3.69%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 42        | 2.46%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 34        | 1.99%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 32        | 1.88%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 30        | 1.76%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 29        | 1.7%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 25        | 1.47%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 23        | 1.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 22        | 1.29%   |
| Apple Bluetooth HCI                                                                 | 20        | 1.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 19        | 1.11%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 19        | 1.11%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 18        | 1.06%   |
| Lite-On Bluetooth Device                                                            | 18        | 1.06%   |
| Ralink RT3290 Bluetooth                                                             | 17        | 1%      |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 17        | 1%      |
| IMC Networks Bluetooth Device                                                       | 17        | 1%      |
| Foxconn / Hon Hai Bluetooth Device                                                  | 17        | 1%      |
| Broadcom BCM2045 Bluetooth                                                          | 16        | 0.94%   |
| Apple Bluetooth Host Controller                                                     | 16        | 0.94%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 15        | 0.88%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 15        | 0.88%   |
| Intel AX210 Bluetooth                                                               | 15        | 0.88%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 15        | 0.88%   |
| IMC Networks Bluetooth Radio                                                        | 14        | 0.82%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 13        | 0.76%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 13        | 0.76%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 13        | 0.76%   |
| Realtek RTL8723B Bluetooth                                                          | 12        | 0.7%    |
| Dell DW375 Bluetooth Module                                                         | 12        | 0.7%    |
| Toshiba Integrated Bluetooth HCI                                                    | 11        | 0.64%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 11        | 0.64%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 11        | 0.64%   |
| Dell Wireless 360 Bluetooth                                                         | 10        | 0.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2755      | 55.57%  |
| AMD                                  | 903       | 18.21%  |
| Nvidia                               | 778       | 15.69%  |
| C-Media Electronics                  | 72        | 1.45%   |
| Creative Labs                        | 52        | 1.05%   |
| VIA Technologies                     | 49        | 0.99%   |
| Silicon Integrated Systems [SiS]     | 39        | 0.79%   |
| Logitech                             | 27        | 0.54%   |
| Texas Instruments                    | 25        | 0.5%    |
| GN Netcom                            | 15        | 0.3%    |
| Focusrite-Novation                   | 13        | 0.26%   |
| M-Audio                              | 12        | 0.24%   |
| JMTek                                | 11        | 0.22%   |
| Yamaha                               | 10        | 0.2%    |
| Plantronics                          | 10        | 0.2%    |
| Generalplus Technology               | 10        | 0.2%    |
| Creative Technology                  | 10        | 0.2%    |
| Lenovo                               | 9         | 0.18%   |
| Realtek Semiconductor                | 7         | 0.14%   |
| ULi Electronics                      | 6         | 0.12%   |
| BEHRINGER International              | 6         | 0.12%   |
| DSEA A/S                             | 5         | 0.1%    |
| ASUSTek Computer                     | 5         | 0.1%    |
| SAVITECH                             | 4         | 0.08%   |
| Ensoniq                              | 4         | 0.08%   |
| DigiTech                             | 4         | 0.08%   |
| Corsair                              | 4         | 0.08%   |
| AKAI Professional M.I.               | 4         | 0.08%   |
| Xilinx                               | 3         | 0.06%   |
| Tenx Technology                      | 3         | 0.06%   |
| TEAC                                 | 3         | 0.06%   |
| Roland                               | 3         | 0.06%   |
| Kingston Technology                  | 3         | 0.06%   |
| Elite Silicon                        | 3         | 0.06%   |
| EGO SYStems                          | 3         | 0.06%   |
| Digidesign                           | 3         | 0.06%   |
| ZOOM                                 | 2         | 0.04%   |
| XMOS                                 | 2         | 0.04%   |
| Unknown                              | 2         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 331       | 5.79%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 284       | 4.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 271       | 4.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 207       | 3.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 183       | 3.2%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 179       | 3.13%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 178       | 3.12%   |
| AMD FCH Azalia Controller                                                                         | 160       | 2.8%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 160       | 2.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 153       | 2.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 150       | 2.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 123       | 2.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 81        | 1.42%   |
| Intel Cannon Lake PCH cAVS                                                                        | 78        | 1.37%   |
| AMD Kabini HDMI/DP Audio                                                                          | 78        | 1.37%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 75        | 1.31%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 75        | 1.31%   |
| Intel 8 Series HD Audio Controller                                                                | 75        | 1.31%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 73        | 1.28%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 72        | 1.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 71        | 1.24%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 69        | 1.21%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 69        | 1.21%   |
| Nvidia High Definition Audio Controller                                                           | 67        | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 62        | 1.09%   |
| Nvidia MCP61 High Definition Audio                                                                | 56        | 0.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 53        | 0.93%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 53        | 0.93%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 50        | 0.88%   |
| Intel Broadwell-U Audio Controller                                                                | 50        | 0.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 49        | 0.86%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 48        | 0.84%   |
| Intel 200 Series PCH HD Audio                                                                     | 47        | 0.82%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 41        | 0.72%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 40        | 0.7%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 39        | 0.68%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 37        | 0.65%   |
| AMD Wrestler HDMI Audio                                                                           | 37        | 0.65%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 37        | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 36        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 406       | 20.94%  |
| SK hynix                                         | 323       | 16.66%  |
| Unknown                                          | 314       | 16.19%  |
| Kingston                                         | 228       | 11.76%  |
| Micron Technology                                | 157       | 8.1%    |
| Crucial                                          | 112       | 5.78%   |
| Corsair                                          | 71        | 3.66%   |
| G.Skill                                          | 54        | 2.78%   |
| Elpida                                           | 43        | 2.22%   |
| Ramaxel Technology                               | 32        | 1.65%   |
| Nanya Technology                                 | 28        | 1.44%   |
| A-DATA Technology                                | 26        | 1.34%   |
| Unknown (ABCD)                                   | 20        | 1.03%   |
| Smart                                            | 13        | 0.67%   |
| Transcend                                        | 12        | 0.62%   |
| Team                                             | 10        | 0.52%   |
| Goodram                                          | 9         | 0.46%   |
| Apacer                                           | 5         | 0.26%   |
| Unknown                                          | 5         | 0.26%   |
| Qimonda                                          | 4         | 0.21%   |
| Patriot                                          | 4         | 0.21%   |
| Avant                                            | 4         | 0.21%   |
| Unifosa                                          | 3         | 0.15%   |
| Timetec                                          | 3         | 0.15%   |
| GeIL                                             | 3         | 0.15%   |
| 48spaces                                         | 3         | 0.15%   |
| Teikon                                           | 2         | 0.1%    |
| Super Talent                                     | 2         | 0.1%    |
| PNY                                              | 2         | 0.1%    |
| Neo Forza                                        | 2         | 0.1%    |
| High Bridge                                      | 2         | 0.1%    |
| CSX                                              | 2         | 0.1%    |
| ASint Technology                                 | 2         | 0.1%    |
| Walton Chaintech                                 | 1         | 0.05%   |
| V-GeN                                            | 1         | 0.05%   |
| Unknown (7F7F7F7F7F7F6B00)                       | 1         | 0.05%   |
| Unknown (0x7FA8000000000000)                     | 1         | 0.05%   |
| Unknown (0x7F7FB5FFFFFFFFFF)                     | 1         | 0.05%   |
| Unknown (0x36345431323830323145444C335342322020) | 1         | 0.05%   |
| Unknown (0x0043415455000000)                     | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 17        | 0.81%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.81%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 16        | 0.77%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 15        | 0.72%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s            | 15        | 0.72%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 15        | 0.72%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.72%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 15        | 0.72%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.62%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 13        | 0.62%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 12        | 0.57%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 11        | 0.53%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 11        | 0.53%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 11        | 0.53%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.53%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 10        | 0.48%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.48%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 10        | 0.48%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 10        | 0.48%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.43%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 9         | 0.43%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.43%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 9         | 0.43%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 8         | 0.38%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 8         | 0.38%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 8         | 0.38%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 8         | 0.38%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 7         | 0.34%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 7         | 0.34%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.34%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 7         | 0.34%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.34%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 0.34%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 6         | 0.29%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 6         | 0.29%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 6         | 0.29%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 6         | 0.29%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 6         | 0.29%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 6         | 0.29%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 680       | 40.05%  |
| DDR4    | 587       | 34.57%  |
| DDR2    | 173       | 10.19%  |
| SDRAM   | 78        | 4.59%   |
| Unknown | 56        | 3.3%    |
| LPDDR4  | 54        | 3.18%   |
| LPDDR3  | 31        | 1.83%   |
| DDR     | 24        | 1.41%   |
| DRAM    | 8         | 0.47%   |
| DDR5    | 4         | 0.24%   |
| LPDDR5  | 2         | 0.12%   |
| EEPROM  | 1         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 976       | 58.55%  |
| DIMM         | 608       | 36.47%  |
| Row Of Chips | 65        | 3.9%    |
| Chip         | 10        | 0.6%    |
| Unknown      | 5         | 0.3%    |
| FB-DIMM      | 3         | 0.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 568       | 30.95%  |
| 8192    | 514       | 28.01%  |
| 2048    | 385       | 20.98%  |
| 16384   | 202       | 11.01%  |
| 1024    | 117       | 6.38%   |
| 32768   | 29        | 1.58%   |
| 512     | 14        | 0.76%   |
| 1536    | 2         | 0.11%   |
| 65536   | 1         | 0.05%   |
| 256     | 1         | 0.05%   |
| 1       | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 425       | 23.55%  |
| 2667    | 240       | 13.3%   |
| 3200    | 153       | 8.48%   |
| 1333    | 142       | 7.87%   |
| 2400    | 116       | 6.43%   |
| 667     | 94        | 5.21%   |
| 800     | 75        | 4.16%   |
| Unknown | 73        | 4.04%   |
| 2133    | 70        | 3.88%   |
| 1334    | 62        | 3.43%   |
| 1066    | 30        | 1.66%   |
| 3600    | 27        | 1.5%    |
| 1867    | 27        | 1.5%    |
| 1067    | 27        | 1.5%    |
| 3266    | 20        | 1.11%   |
| 1866    | 19        | 1.05%   |
| 533     | 19        | 1.05%   |
| 4199    | 17        | 0.94%   |
| 4267    | 14        | 0.78%   |
| 3000    | 14        | 0.78%   |
| 2666    | 14        | 0.78%   |
| 2048    | 13        | 0.72%   |
| 1800    | 12        | 0.66%   |
| 975     | 8         | 0.44%   |
| 400     | 8         | 0.44%   |
| 3800    | 5         | 0.28%   |
| 3400    | 5         | 0.28%   |
| 2733    | 5         | 0.28%   |
| 49926   | 4         | 0.22%   |
| 4800    | 4         | 0.22%   |
| 3733    | 4         | 0.22%   |
| 2800    | 4         | 0.22%   |
| 2200    | 4         | 0.22%   |
| 2000    | 4         | 0.22%   |
| 333     | 4         | 0.22%   |
| 4266    | 3         | 0.17%   |
| 3466    | 3         | 0.17%   |
| 2448    | 3         | 0.17%   |
| 6400    | 2         | 0.11%   |
| 4000    | 2         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 51        | 39.53%  |
| Brother Industries    | 25        | 19.38%  |
| Canon                 | 24        | 18.6%   |
| Samsung Electronics   | 10        | 7.75%   |
| Seiko Epson           | 5         | 3.88%   |
| Zebra                 | 4         | 3.1%    |
| QinHeng Electronics   | 2         | 1.55%   |
| Prolific Technology   | 2         | 1.55%   |
| STMicroelectronics    | 1         | 0.78%   |
| Pantum                | 1         | 0.78%   |
| Minolta               | 1         | 0.78%   |
| Lexmark International | 1         | 0.78%   |
| Kyocera               | 1         | 0.78%   |
| Dymo-CoStar           | 1         | 0.78%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| HP LaserJet P1005                                                     | 4         | 3.08%   |
| HP LaserJet 400 M401n                                                 | 4         | 3.08%   |
| Zebra ZP 450 Printer                                                  | 3         | 2.31%   |
| HP ENVY 4520 series                                                   | 3         | 2.31%   |
| Brother HL-5370DW series                                              | 3         | 2.31%   |
| Seiko Epson L220 Series                                               | 2         | 1.54%   |
| QinHeng CH340S                                                        | 2         | 1.54%   |
| Prolific PL2305 Parallel Port                                         | 2         | 1.54%   |
| HP OfficeJet Pro 7730 series                                          | 2         | 1.54%   |
| HP LaserJet P1006                                                     | 2         | 1.54%   |
| HP LaserJet 1320                                                      | 2         | 1.54%   |
| HP LaserJet 1020                                                      | 2         | 1.54%   |
| HP LaserJet 1015                                                      | 2         | 1.54%   |
| HP DeskJet 3700 series                                                | 2         | 1.54%   |
| HP Deskjet 3050A                                                      | 2         | 1.54%   |
| Canon TS3100 series                                                   | 2         | 1.54%   |
| Canon PIXMA MX530 Series                                              | 2         | 1.54%   |
| Canon LBP6000                                                         | 2         | 1.54%   |
| Brother HL-L2320D series                                              | 2         | 1.54%   |
| Brother HL-5340 series                                                | 2         | 1.54%   |
| Brother HL-2270DW Laser Printer                                       | 2         | 1.54%   |
| Zebra ZTC ZP 500 (ZPL)                                                | 1         | 0.77%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 1         | 0.77%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 0.77%   |
| Seiko Epson L396 Series                                               | 1         | 0.77%   |
| Seiko Epson ET-2720 Series                                            | 1         | 0.77%   |
| Samsung Xerox Phaser 3117 Laser Printer                               | 1         | 0.77%   |
| Samsung SF-760 Series                                                 | 1         | 0.77%   |
| Samsung SCX-4200 series                                               | 1         | 0.77%   |
| Samsung SCX-4100 Scanner                                              | 1         | 0.77%   |
| Samsung SCX-3400 Series                                               | 1         | 0.77%   |
| Samsung ML-2525W Series                                               | 1         | 0.77%   |
| Samsung ML-1740 Printer                                               | 1         | 0.77%   |
| Samsung M2070 Series                                                  | 1         | 0.77%   |
| Samsung M2020 Series                                                  | 1         | 0.77%   |
| Samsung C48x Series                                                   | 1         | 0.77%   |
| Pantum P2000                                                          | 1         | 0.77%   |
| Minolta PagePro 1300W                                                 | 1         | 0.77%   |
| Lexmark International E360d                                           | 1         | 0.77%   |
| Kyocera Mita FS-920                                                   | 1         | 0.77%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 25        | 69.44%  |
| Hewlett-Packard | 6         | 16.67%  |
| Seiko Epson     | 5         | 13.89%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                     | 4         | 11.11%  |
| Canon CanoScan LiDE 100                                     | 4         | 11.11%  |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                      | 3         | 8.33%   |
| Canon CanoScan LIDE 25                                      | 3         | 8.33%   |
| Canon CanoScan N650U/N656U                                  | 2         | 5.56%   |
| Canon CanoScan LiDE 220                                     | 2         | 5.56%   |
| Canon CanoScan LiDE 210                                     | 2         | 5.56%   |
| Canon CanoScan LiDE 120                                     | 2         | 5.56%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]            | 1         | 2.78%   |
| Seiko Epson GT-X770 [Perfection V500]                       | 1         | 2.78%   |
| Seiko Epson GT-9800F [Perfection 3200]                      | 1         | 2.78%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1         | 2.78%   |
| Seiko Epson GT-7700U [Perfection 1240U]                     | 1         | 2.78%   |
| HP ScanJet 82x0C                                            | 1         | 2.78%   |
| HP ScanJet 7400c                                            | 1         | 2.78%   |
| HP ScanJet 5590                                             | 1         | 2.78%   |
| HP ScanJet 3570c                                            | 1         | 2.78%   |
| HP Scanjet 200                                              | 1         | 2.78%   |
| HP PSC 1200                                                 | 1         | 2.78%   |
| Canon CanoScan N670U/N676U/LiDE 20                          | 1         | 2.78%   |
| Canon CanoScan LiDE 90                                      | 1         | 2.78%   |
| Canon CanoScan LiDE 200                                     | 1         | 2.78%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 498       | 24.97%  |
| Microdia                               | 156       | 7.82%   |
| Realtek Semiconductor                  | 132       | 6.62%   |
| IMC Networks                           | 129       | 6.47%   |
| Acer                                   | 126       | 6.32%   |
| Suyin                                  | 119       | 5.97%   |
| Logitech                               | 103       | 5.17%   |
| Sunplus Innovation Technology          | 94        | 4.71%   |
| Quanta                                 | 68        | 3.41%   |
| Cheng Uei Precision Industry (Foxlink) | 65        | 3.26%   |
| Apple                                  | 50        | 2.51%   |
| Alcor Micro                            | 45        | 2.26%   |
| Silicon Motion                         | 43        | 2.16%   |
| Syntek                                 | 40        | 2.01%   |
| Ricoh                                  | 40        | 2.01%   |
| Lite-On Technology                     | 35        | 1.76%   |
| Z-Star Microelectronics                | 22        | 1.1%    |
| Samsung Electronics                    | 22        | 1.1%    |
| Microsoft                              | 20        | 1%      |
| Lenovo                                 | 14        | 0.7%    |
| Luxvisions Innotech Limited            | 13        | 0.65%   |
| ALi                                    | 13        | 0.65%   |
| Importek                               | 10        | 0.5%    |
| Primax Electronics                     | 9         | 0.45%   |
| GEMBIRD                                | 8         | 0.4%    |
| OmniVision Technologies                | 7         | 0.35%   |
| MacroSilicon                           | 7         | 0.35%   |
| Generalplus Technology                 | 7         | 0.35%   |
| icSpring                               | 6         | 0.3%    |
| DigiTech                               | 6         | 0.3%    |
| Cubeternet                             | 6         | 0.3%    |
| KYE Systems (Mouse Systems)            | 5         | 0.25%   |
| Jieli Technology                       | 5         | 0.25%   |
| Creative Technology                    | 5         | 0.25%   |
| Sunplus Technology                     | 4         | 0.2%    |
| Sonix Technology                       | 4         | 0.2%    |
| ARC International                      | 4         | 0.2%    |
| Unknown                                | 3         | 0.15%   |
| Trust                                  | 3         | 0.15%   |
| OPPO Electronics                       | 3         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 76        | 3.8%    |
| Realtek Integrated_Webcam_HD                     | 33        | 1.65%   |
| Microdia Integrated_Webcam_HD                    | 31        | 1.55%   |
| Chicony HD WebCam                                | 31        | 1.55%   |
| Chicony USB 2.0 Camera                           | 28        | 1.4%    |
| Logitech Webcam C270                             | 25        | 1.25%   |
| IMC Networks USB2.0 HD UVC WebCam                | 25        | 1.25%   |
| Sunplus Integrated_Webcam_HD                     | 22        | 1.1%    |
| IMC Networks Integrated Camera                   | 22        | 1.1%    |
| Acer Integrated Camera                           | 22        | 1.1%    |
| Samsung Galaxy A5 (MTP)                          | 21        | 1.05%   |
| Microdia Sonix USB 2.0 Camera                    | 20        | 1%      |
| Chicony TOSHIBA Web Camera - HD                  | 20        | 1%      |
| Logitech HD Pro Webcam C920                      | 18        | 0.9%    |
| Chicony Lenovo EasyCamera                        | 18        | 0.9%    |
| Chicony HP Truevision HD                         | 18        | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 18        | 0.9%    |
| Apple iPhone 5/5C/5S/6/SE                        | 18        | 0.9%    |
| Suyin HP TrueVision HD                           | 17        | 0.85%   |
| Apple Built-in iSight                            | 17        | 0.85%   |
| Alcor Micro USB Camera                           | 17        | 0.85%   |
| Acer Lenovo EasyCamera                           | 17        | 0.85%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 16        | 0.8%    |
| Microdia Integrated Webcam                       | 15        | 0.75%   |
| Chicony USB2.0 VGA UVC WebCam                    | 15        | 0.75%   |
| Acer HD Webcam                                   | 15        | 0.75%   |
| Lite-On Integrated Camera                        | 14        | 0.7%    |
| Suyin Acer CrystalEye Webcam                     | 13        | 0.65%   |
| IMC Networks UVC VGA Webcam                      | 13        | 0.65%   |
| Acer SunplusIT Integrated Camera                 | 13        | 0.65%   |
| Acer BisonCam, NB Pro                            | 13        | 0.65%   |
| Syntek Lenovo EasyCamera                         | 12        | 0.6%    |
| Realtek USB Camera                               | 12        | 0.6%    |
| Quanta HP Webcam                                 | 12        | 0.6%    |
| Syntek Integrated Camera                         | 11        | 0.55%   |
| Sunplus HD WebCam                                | 11        | 0.55%   |
| Quanta HP TrueVision HD Camera                   | 11        | 0.55%   |
| Lite-On HP HD Camera                             | 11        | 0.55%   |
| Chicony HP HD Camera                             | 11        | 0.55%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 10        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 122       | 36.42%  |
| Synaptics                  | 65        | 19.4%   |
| AuthenTec                  | 54        | 16.12%  |
| Upek                       | 30        | 8.96%   |
| Shenzhen Goodix Technology | 23        | 6.87%   |
| STMicroelectronics         | 19        | 5.67%   |
| LighTuning Technology      | 11        | 3.28%   |
| Elan Microelectronics      | 8         | 2.39%   |
| Samsung Electronics        | 2         | 0.6%    |
| DigitalPersona             | 1         | 0.3%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 29        | 8.66%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 28        | 8.36%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 26        | 7.76%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 23        | 6.87%   |
| STMicroelectronics Fingerprint Reader                                      | 19        | 5.67%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 15        | 4.48%   |
| Shenzhen Goodix  Fingerprint Device                                        | 14        | 4.18%   |
| AuthenTec AES2810                                                          | 14        | 4.18%   |
| Validity Sensors Fingerprint scanner                                       | 13        | 3.88%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 11        | 3.28%   |
| Validity Sensors VFS491                                                    | 11        | 3.28%   |
| Unknown                                                                    | 11        | 3.28%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 10        | 2.99%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 2.39%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.39%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 2.39%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 2.39%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 2.09%   |
| AuthenTec AES1600                                                          | 7         | 2.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.79%   |
| Elan ELAN:Fingerprint                                                      | 6         | 1.79%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.49%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.49%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.19%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 1.19%   |
| Synaptics  WBDI                                                            | 4         | 1.19%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.9%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 0.9%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.9%    |
| LighTuning Fingerprint Reader                                              | 3         | 0.9%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 0.9%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.6%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.6%    |
| Synaptics WBDI Device                                                      | 2         | 0.6%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.6%    |
| Elan ELAN:ARM-M4                                                           | 2         | 0.6%    |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.3%    |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.3%    |
| Samsung Fingerprint Device                                                 | 1         | 0.3%    |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.3%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 66        | 35.11%  |
| Alcor Micro               | 48        | 25.53%  |
| O2 Micro                  | 28        | 14.89%  |
| Upek                      | 16        | 8.51%   |
| Lenovo                    | 16        | 8.51%   |
| OmniKey                   | 3         | 1.6%    |
| Reiner SCT Kartensysteme  | 2         | 1.06%   |
| Gemalto (was Gemplus)     | 2         | 1.06%   |
| In Focus Systems          | 1         | 0.53%   |
| Fujitsu Siemens Computers | 1         | 0.53%   |
| Chicony Electronics       | 1         | 0.53%   |
| Cherry                    | 1         | 0.53%   |
| C3PO                      | 1         | 0.53%   |
| Aktiv                     | 1         | 0.53%   |
| Advanced Card Systems     | 1         | 0.53%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 48        | 25.53%  |
| Broadcom BCM5880 Secure Applications Processor                               | 30        | 15.96%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 22        | 11.7%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 16        | 8.51%   |
| Broadcom 5880                                                                | 16        | 8.51%   |
| Lenovo Integrated Smart Card Reader                                          | 15        | 7.98%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 5.32%   |
| Broadcom 58200                                                               | 9         | 4.79%   |
| O2 Micro Oz776 SmartCard Reader                                              | 6         | 3.19%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.06%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.53%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 1         | 0.53%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.53%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.53%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.53%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.53%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.53%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.53%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.53%   |
| Cherry SmartTerminal XX44                                                    | 1         | 0.53%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.53%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.53%   |
| Aktiv Rutoken lite                                                           | 1         | 0.53%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.53%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2846      | 73.01%  |
| 1     | 828       | 21.24%  |
| 2     | 179       | 4.59%   |
| 3     | 29        | 0.74%   |
| 4     | 11        | 0.28%   |
| 5     | 3         | 0.08%   |
| 10    | 1         | 0.03%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 334       | 26.32%  |
| Graphics card            | 285       | 22.46%  |
| Chipcard                 | 180       | 14.18%  |
| Net/wireless             | 138       | 10.87%  |
| Communication controller | 56        | 4.41%   |
| Modem                    | 47        | 3.7%    |
| Camera                   | 38        | 2.99%   |
| Multimedia controller    | 33        | 2.6%    |
| Bluetooth                | 27        | 2.13%   |
| Unassigned class         | 26        | 2.05%   |
| Storage                  | 24        | 1.89%   |
| Sound                    | 21        | 1.65%   |
| Card reader              | 21        | 1.65%   |
| Flash memory             | 16        | 1.26%   |
| Network                  | 8         | 0.63%   |
| Net/ethernet             | 7         | 0.55%   |
| Dvb card                 | 3         | 0.24%   |
| Storage/raid             | 2         | 0.16%   |
| Video                    | 1         | 0.08%   |
| Storage/ide              | 1         | 0.08%   |
| Firewire controller      | 1         | 0.08%   |

