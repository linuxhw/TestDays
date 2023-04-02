Xubuntu - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Xubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 3204

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [2a881cc01e](https://linux-hardware.org/?probe=2a881cc01e) | Apr 01, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [81c43aeb0d](https://linux-hardware.org/?probe=81c43aeb0d) | Mar 30, 2023 |
| Medion        | S321X                       | [4c02136dda](https://linux-hardware.org/?probe=4c02136dda) | Mar 30, 2023 |
| Gateway       | LT27                        | [4697cead5f](https://linux-hardware.org/?probe=4697cead5f) | Mar 28, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [a7ff24abc4](https://linux-hardware.org/?probe=a7ff24abc4) | Mar 26, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [8d5a135264](https://linux-hardware.org/?probe=8d5a135264) | Mar 26, 2023 |
| Samsung       | RV408/RV508                 | [5f5efa7edc](https://linux-hardware.org/?probe=5f5efa7edc) | Mar 25, 2023 |
| Samsung       | RV408/RV508                 | [cce3fdd054](https://linux-hardware.org/?probe=cce3fdd054) | Mar 25, 2023 |
| HP            | EliteBook 6930p             | [da0d90d69f](https://linux-hardware.org/?probe=da0d90d69f) | Mar 25, 2023 |
| Unknown       | Unknown                     | [fb97269a4d](https://linux-hardware.org/?probe=fb97269a4d) | Mar 24, 2023 |
| Gigabyte      | AERO 15WV8                  | [379c88860a](https://linux-hardware.org/?probe=379c88860a) | Mar 23, 2023 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | [f97f90f7ce](https://linux-hardware.org/?probe=f97f90f7ce) | Mar 22, 2023 |
| TrekStor      | Notebook Slim S130          | [6c3a6e7e53](https://linux-hardware.org/?probe=6c3a6e7e53) | Mar 22, 2023 |
| Gateway       | EC14 Series                 | [fdeb2e4e3b](https://linux-hardware.org/?probe=fdeb2e4e3b) | Mar 22, 2023 |
| Getac         | F110G3                      | [792ac98040](https://linux-hardware.org/?probe=792ac98040) | Mar 22, 2023 |
| HP            | EliteBook 725 G2            | [5112f86dde](https://linux-hardware.org/?probe=5112f86dde) | Mar 21, 2023 |
| Lenovo        | ThinkPad T530 2429LT7       | [ebb127610b](https://linux-hardware.org/?probe=ebb127610b) | Mar 20, 2023 |
| Chuwi         | CoreBook X                  | [fd4d05d961](https://linux-hardware.org/?probe=fd4d05d961) | Mar 20, 2023 |
| Gateway       | EC14 Series                 | [c6ea9d7f10](https://linux-hardware.org/?probe=c6ea9d7f10) | Mar 18, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [a174d9ea53](https://linux-hardware.org/?probe=a174d9ea53) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [182bd8cca1](https://linux-hardware.org/?probe=182bd8cca1) | Mar 16, 2023 |
| Lenovo        | ThinkPad E15 20RES05U00     | [7047c529ef](https://linux-hardware.org/?probe=7047c529ef) | Mar 13, 2023 |
| Google        | Kefka                       | [58abcf00e9](https://linux-hardware.org/?probe=58abcf00e9) | Mar 12, 2023 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [728697bff3](https://linux-hardware.org/?probe=728697bff3) | Mar 11, 2023 |
| Lenovo        | G50-45 80E3                 | [e2b7d998d8](https://linux-hardware.org/?probe=e2b7d998d8) | Mar 11, 2023 |
| Lenovo        | ThinkPad T510 4384VJZ       | [d9c87b4795](https://linux-hardware.org/?probe=d9c87b4795) | Mar 11, 2023 |
| Apple         | MacBookPro1,1               | [105d39532f](https://linux-hardware.org/?probe=105d39532f) | Mar 10, 2023 |
| Toshiba       | Satellite L300              | [a35bb278ba](https://linux-hardware.org/?probe=a35bb278ba) | Mar 09, 2023 |
| Toshiba       | Satellite L300              | [13418c9605](https://linux-hardware.org/?probe=13418c9605) | Mar 08, 2023 |
| GPU Compan... | GWTN156-5                   | [2d093cc3ef](https://linux-hardware.org/?probe=2d093cc3ef) | Mar 08, 2023 |
| GPU Compan... | GWTN156-5                   | [57d690358f](https://linux-hardware.org/?probe=57d690358f) | Mar 08, 2023 |
| HP            | Pavilion x2 Detachable      | [04ef76ee4a](https://linux-hardware.org/?probe=04ef76ee4a) | Mar 07, 2023 |
| Toshiba       | Satellite C55D-B            | [963b41587c](https://linux-hardware.org/?probe=963b41587c) | Mar 07, 2023 |
| Acer          | Aspire ES1-572              | [a3dbc9b45e](https://linux-hardware.org/?probe=a3dbc9b45e) | Mar 07, 2023 |
| Toshiba       | Satellite L775              | [75a1948a64](https://linux-hardware.org/?probe=75a1948a64) | Mar 07, 2023 |
| Lenovo        | G50-45 80E3                 | [ade979391f](https://linux-hardware.org/?probe=ade979391f) | Mar 07, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [9404cddcdf](https://linux-hardware.org/?probe=9404cddcdf) | Mar 07, 2023 |
| HP            | Compaq Presario C700        | [fe1c136403](https://linux-hardware.org/?probe=fe1c136403) | Mar 06, 2023 |
| HP            | Compaq Presario C700        | [0b29805ec8](https://linux-hardware.org/?probe=0b29805ec8) | Mar 06, 2023 |
| Microtech     | ebookPro                    | [cac30f03b1](https://linux-hardware.org/?probe=cac30f03b1) | Mar 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [64c40ef1a4](https://linux-hardware.org/?probe=64c40ef1a4) | Mar 06, 2023 |
| Acer          | Aspire A315-43              | [c9efc71e60](https://linux-hardware.org/?probe=c9efc71e60) | Mar 04, 2023 |
| Acer          | Aspire 5740                 | [de0d12baa4](https://linux-hardware.org/?probe=de0d12baa4) | Feb 27, 2023 |
| HP            | 655                         | [e6b694526e](https://linux-hardware.org/?probe=e6b694526e) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [3f35f45bf0](https://linux-hardware.org/?probe=3f35f45bf0) | Feb 26, 2023 |
| Alienware     | 17 R4                       | [bfeccbf9f3](https://linux-hardware.org/?probe=bfeccbf9f3) | Feb 25, 2023 |
| HP            | EliteBook 820 G3            | [75a0fcca48](https://linux-hardware.org/?probe=75a0fcca48) | Feb 25, 2023 |
| HONOR         | BMH-WCX9                    | [634b80ac90](https://linux-hardware.org/?probe=634b80ac90) | Feb 24, 2023 |
| Dell          | Latitude E5470              | [d7c8a049c4](https://linux-hardware.org/?probe=d7c8a049c4) | Feb 24, 2023 |
| Dell          | Studio 1450                 | [c26228f66f](https://linux-hardware.org/?probe=c26228f66f) | Feb 22, 2023 |
| Lenovo        | ThinkPad X131e 3367AH5      | [3c1cec4c1c](https://linux-hardware.org/?probe=3c1cec4c1c) | Feb 22, 2023 |
| Acer          | Aspire 7736                 | [479496a645](https://linux-hardware.org/?probe=479496a645) | Feb 21, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [751f76b561](https://linux-hardware.org/?probe=751f76b561) | Feb 21, 2023 |
| HP            | Pavilion 15                 | [c33178dcdc](https://linux-hardware.org/?probe=c33178dcdc) | Feb 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [7ac4bb7d51](https://linux-hardware.org/?probe=7ac4bb7d51) | Feb 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [19e03ac7b2](https://linux-hardware.org/?probe=19e03ac7b2) | Feb 20, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | [4a9dcac308](https://linux-hardware.org/?probe=4a9dcac308) | Feb 19, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | [d808827823](https://linux-hardware.org/?probe=d808827823) | Feb 19, 2023 |
| Sony          | VPCEA3S1E                   | [45d0b9a823](https://linux-hardware.org/?probe=45d0b9a823) | Feb 18, 2023 |
| Sony          | VPCZ13M9E                   | [b3db404e91](https://linux-hardware.org/?probe=b3db404e91) | Feb 17, 2023 |
| HP            | Pavilion g6                 | [8a53743bd0](https://linux-hardware.org/?probe=8a53743bd0) | Feb 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [0b622220d7](https://linux-hardware.org/?probe=0b622220d7) | Feb 15, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | [d576d16c25](https://linux-hardware.org/?probe=d576d16c25) | Feb 14, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | [2334fc688f](https://linux-hardware.org/?probe=2334fc688f) | Feb 14, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | [e2f49b2fe4](https://linux-hardware.org/?probe=e2f49b2fe4) | Feb 14, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [25dbf25c62](https://linux-hardware.org/?probe=25dbf25c62) | Feb 14, 2023 |
| HP            | Compaq nc6400 (RM741PA#A... | [d556bf453d](https://linux-hardware.org/?probe=d556bf453d) | Feb 13, 2023 |
| Toshiba       | Satellite Pro R50-B         | [0634db3367](https://linux-hardware.org/?probe=0634db3367) | Feb 13, 2023 |
| Dell          | Inspiron 5490               | [f840248d22](https://linux-hardware.org/?probe=f840248d22) | Feb 13, 2023 |
| Sony          | VPCX11Z6R                   | [ad87a45a26](https://linux-hardware.org/?probe=ad87a45a26) | Feb 12, 2023 |
| Packard Be... | DOT S                       | [1f57142ffd](https://linux-hardware.org/?probe=1f57142ffd) | Feb 12, 2023 |
| Dell          | Latitude E5450              | [693f8c9c36](https://linux-hardware.org/?probe=693f8c9c36) | Feb 11, 2023 |
| HP            | Compaq Presario A900        | [d3c4a9e1e6](https://linux-hardware.org/?probe=d3c4a9e1e6) | Feb 09, 2023 |
| Lenovo        | ThinkPad T430s 23562Z3      | [7338d8375a](https://linux-hardware.org/?probe=7338d8375a) | Feb 09, 2023 |
| Acer          | Extensa 5635ZG              | [dd22b216a9](https://linux-hardware.org/?probe=dd22b216a9) | Feb 08, 2023 |
| HONOR         | NMH-WCX9                    | [d5bb6335d4](https://linux-hardware.org/?probe=d5bb6335d4) | Feb 08, 2023 |
| Acer          | Aspire E5-572G              | [f44e9ce856](https://linux-hardware.org/?probe=f44e9ce856) | Feb 08, 2023 |
| Lenovo        | ThinkPad T440p 20AN006NU... | [e3bd76eeaf](https://linux-hardware.org/?probe=e3bd76eeaf) | Feb 07, 2023 |
| Dell          | Latitude D430               | [0c1ad39f32](https://linux-hardware.org/?probe=0c1ad39f32) | Feb 06, 2023 |
| Insyde        | CherryTrail                 | [cb02cfc77c](https://linux-hardware.org/?probe=cb02cfc77c) | Feb 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | [262dfe3aa9](https://linux-hardware.org/?probe=262dfe3aa9) | Feb 05, 2023 |
| Intel         | Unknown                     | [f12482330f](https://linux-hardware.org/?probe=f12482330f) | Feb 05, 2023 |
| Lenovo        | ThinkPad R500 2716W2K       | [a645368e82](https://linux-hardware.org/?probe=a645368e82) | Feb 04, 2023 |
| HP            | 250 G7 Notebook PC          | [9c9aa5e0e0](https://linux-hardware.org/?probe=9c9aa5e0e0) | Feb 03, 2023 |
| HP            | 240 G3                      | [43e56d3ae5](https://linux-hardware.org/?probe=43e56d3ae5) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | [ccf7f4d126](https://linux-hardware.org/?probe=ccf7f4d126) | Feb 03, 2023 |
| HP            | Compaq Presario CQ60        | [c6d48c9847](https://linux-hardware.org/?probe=c6d48c9847) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | [fafb999b1a](https://linux-hardware.org/?probe=fafb999b1a) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | [50076364b8](https://linux-hardware.org/?probe=50076364b8) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [0211cbb448](https://linux-hardware.org/?probe=0211cbb448) | Feb 03, 2023 |
| HUAWEI        | NBD-WXX9                    | [17b77b89e5](https://linux-hardware.org/?probe=17b77b89e5) | Feb 03, 2023 |
| ECS           | SF20PA2                     | [30df19ca2e](https://linux-hardware.org/?probe=30df19ca2e) | Feb 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [0d500d9d33](https://linux-hardware.org/?probe=0d500d9d33) | Jan 31, 2023 |
| Dell          | Latitude D630               | [d8ac695aa3](https://linux-hardware.org/?probe=d8ac695aa3) | Jan 31, 2023 |
| HP            | 240 G8 Notebook PC          | [00a3607d18](https://linux-hardware.org/?probe=00a3607d18) | Jan 30, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [c93d5da3f1](https://linux-hardware.org/?probe=c93d5da3f1) | Jan 28, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [f409b1df0b](https://linux-hardware.org/?probe=f409b1df0b) | Jan 27, 2023 |
| Philco        | 14E                         | [1c069ed627](https://linux-hardware.org/?probe=1c069ed627) | Jan 27, 2023 |
| Philco        | 14E                         | [cfb283e599](https://linux-hardware.org/?probe=cfb283e599) | Jan 27, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [cf42b2f763](https://linux-hardware.org/?probe=cf42b2f763) | Jan 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| ASUSTek       | X541UVK                     | [64810b20c3](https://linux-hardware.org/?probe=64810b20c3) | Jan 26, 2023 |
| Lenovo        | E41-25 81FS                 | [6de2ea7d90](https://linux-hardware.org/?probe=6de2ea7d90) | Jan 26, 2023 |
| Packard Be... | EasyNote TK87               | [82ce911f26](https://linux-hardware.org/?probe=82ce911f26) | Jan 25, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [34e69693d1](https://linux-hardware.org/?probe=34e69693d1) | Jan 25, 2023 |
| Acer          | Aspire 5920G                | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Dell          | Inspiron 3541               | [12d8081c29](https://linux-hardware.org/?probe=12d8081c29) | Jan 23, 2023 |
| Notebook      | W65_67SZ                    | [74d788dccb](https://linux-hardware.org/?probe=74d788dccb) | Jan 23, 2023 |
| Apple         | MacBook4,1                  | [8d876754f3](https://linux-hardware.org/?probe=8d876754f3) | Jan 23, 2023 |
| Apple         | MacBook4,1                  | [f1f61785e5](https://linux-hardware.org/?probe=f1f61785e5) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | [873bf3c874](https://linux-hardware.org/?probe=873bf3c874) | Jan 22, 2023 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | [68ff3c02cb](https://linux-hardware.org/?probe=68ff3c02cb) | Jan 22, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [82c74e5cca](https://linux-hardware.org/?probe=82c74e5cca) | Jan 21, 2023 |
| Acer          | Aspire 1640                 | [fb70812654](https://linux-hardware.org/?probe=fb70812654) | Jan 21, 2023 |
| ASUSTek       | N53SN                       | [bc8c82ca9a](https://linux-hardware.org/?probe=bc8c82ca9a) | Jan 21, 2023 |
| Dell          | Inspiron 5391               | [050e28c342](https://linux-hardware.org/?probe=050e28c342) | Jan 20, 2023 |
| Dell          | Venue 11 Pro 7139           | [6c3528d4c0](https://linux-hardware.org/?probe=6c3528d4c0) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [76ab21d17b](https://linux-hardware.org/?probe=76ab21d17b) | Jan 20, 2023 |
| HP            | Stream Laptop 11-ah0XX      | [6c83597890](https://linux-hardware.org/?probe=6c83597890) | Jan 19, 2023 |
| Dell          | Inspiron N5110              | [fd8b8416ea](https://linux-hardware.org/?probe=fd8b8416ea) | Jan 19, 2023 |
| Acer          | Aspire A517-51G             | [80712a04ec](https://linux-hardware.org/?probe=80712a04ec) | Jan 18, 2023 |
| Dell          | Latitude E6440              | [f2b34c7c46](https://linux-hardware.org/?probe=f2b34c7c46) | Jan 17, 2023 |
| Dell          | Inspiron N4010              | [7d03111ac0](https://linux-hardware.org/?probe=7d03111ac0) | Jan 16, 2023 |
| ASUSTek       | UX305CA                     | [b831308d6c](https://linux-hardware.org/?probe=b831308d6c) | Jan 16, 2023 |
| Dell          | Latitude E6420              | [3594f88292](https://linux-hardware.org/?probe=3594f88292) | Jan 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [251a926c19](https://linux-hardware.org/?probe=251a926c19) | Jan 14, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [558f3d0d93](https://linux-hardware.org/?probe=558f3d0d93) | Jan 14, 2023 |
| ASUSTek       | A7K                         | [1303f158ab](https://linux-hardware.org/?probe=1303f158ab) | Jan 13, 2023 |
| Notebook      | NJx0MU                      | [b3711a9adc](https://linux-hardware.org/?probe=b3711a9adc) | Jan 13, 2023 |
| Sony          | VPCEB3L9E                   | [5a7ea474fd](https://linux-hardware.org/?probe=5a7ea474fd) | Jan 11, 2023 |
| ASUSTek       | X555YI                      | [4968e51e0b](https://linux-hardware.org/?probe=4968e51e0b) | Jan 10, 2023 |
| Acer          | Aspire E5-771               | [dc397ff7f7](https://linux-hardware.org/?probe=dc397ff7f7) | Jan 09, 2023 |
| HP            | Pavilion dv2000 (RX554LA... | [2f9ff5256a](https://linux-hardware.org/?probe=2f9ff5256a) | Jan 08, 2023 |
| HP            | Pavilion dv2000 (RX554LA... | [b952438f2c](https://linux-hardware.org/?probe=b952438f2c) | Jan 08, 2023 |
| Toshiba       | NB205                       | [3d6ba0d0b3](https://linux-hardware.org/?probe=3d6ba0d0b3) | Jan 07, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [daca90b2bb](https://linux-hardware.org/?probe=daca90b2bb) | Jan 05, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [74bacb92f5](https://linux-hardware.org/?probe=74bacb92f5) | Jan 05, 2023 |
| Dell          | Latitude 5590               | [f32e1efdef](https://linux-hardware.org/?probe=f32e1efdef) | Jan 05, 2023 |
| Samsung       | R530/R730                   | [dd26df5f4f](https://linux-hardware.org/?probe=dd26df5f4f) | Jan 05, 2023 |
| Dell          | Latitude E6420              | [0ac727d853](https://linux-hardware.org/?probe=0ac727d853) | Jan 03, 2023 |
| Dell          | Inspiron 5423               | [14aa07b144](https://linux-hardware.org/?probe=14aa07b144) | Jan 02, 2023 |
| Dell          | Inspiron 5423               | [0c30f220cb](https://linux-hardware.org/?probe=0c30f220cb) | Jan 02, 2023 |
| HP            | Laptop 17-bs0xx             | [f1494f113b](https://linux-hardware.org/?probe=f1494f113b) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | [79d4fe0592](https://linux-hardware.org/?probe=79d4fe0592) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | [aeb6ecee74](https://linux-hardware.org/?probe=aeb6ecee74) | Jan 01, 2023 |
| Dell          | Latitude E5440              | [9578ad1ea3](https://linux-hardware.org/?probe=9578ad1ea3) | Dec 31, 2022 |
| HP            | Pavilion 17                 | [4a8c3f4014](https://linux-hardware.org/?probe=4a8c3f4014) | Dec 29, 2022 |
| Acer          | Nitro AN515-55              | [79f628b951](https://linux-hardware.org/?probe=79f628b951) | Dec 29, 2022 |
| HP            | Pavilion 15                 | [15ec0001c5](https://linux-hardware.org/?probe=15ec0001c5) | Dec 29, 2022 |
| HP            | Pavilion 15                 | [e84551a6eb](https://linux-hardware.org/?probe=e84551a6eb) | Dec 29, 2022 |
| HP            | Compaq Presario C700        | [20a055c383](https://linux-hardware.org/?probe=20a055c383) | Dec 29, 2022 |
| Lenovo        | ThinkPad X230 23252S4       | [667dcc287e](https://linux-hardware.org/?probe=667dcc287e) | Dec 28, 2022 |
| HP            | Compaq Presario C700        | [a4d55d44ed](https://linux-hardware.org/?probe=a4d55d44ed) | Dec 28, 2022 |
| HIGRADED      | W651UI                      | [66d9d484cd](https://linux-hardware.org/?probe=66d9d484cd) | Dec 27, 2022 |
| Toshiba       | Satellite C650              | [89b85889f9](https://linux-hardware.org/?probe=89b85889f9) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | [3bf8001e85](https://linux-hardware.org/?probe=3bf8001e85) | Dec 24, 2022 |
| HP            | Laptop 15-bw0xx             | [8a5bfa5e66](https://linux-hardware.org/?probe=8a5bfa5e66) | Dec 24, 2022 |
| Unknown       | OA Q-ONE BRAND_V2.0         | [e554aa3d11](https://linux-hardware.org/?probe=e554aa3d11) | Dec 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| ASUSTek       | G60JX                       | [5e9b0bb890](https://linux-hardware.org/?probe=5e9b0bb890) | Dec 23, 2022 |
| Clevo         | P170EM                      | [3c8b8bd784](https://linux-hardware.org/?probe=3c8b8bd784) | Dec 22, 2022 |
| ASUSTek       | X555LF                      | [bed000b293](https://linux-hardware.org/?probe=bed000b293) | Dec 22, 2022 |
| Acer          | Aspire A114-31              | [850c0c4a65](https://linux-hardware.org/?probe=850c0c4a65) | Dec 22, 2022 |
| ASUSTek       | 1215P                       | [a39ca1c22f](https://linux-hardware.org/?probe=a39ca1c22f) | Dec 21, 2022 |
| ASUSTek       | 1215P                       | [ed3dc80f1b](https://linux-hardware.org/?probe=ed3dc80f1b) | Dec 21, 2022 |
| Dell          | Latitude E5450              | [652099945b](https://linux-hardware.org/?probe=652099945b) | Dec 21, 2022 |
| HP            | Pavilion dv7                | [075b40bb9e](https://linux-hardware.org/?probe=075b40bb9e) | Dec 21, 2022 |
| Google        | Auron_Yuna                  | [827696b95a](https://linux-hardware.org/?probe=827696b95a) | Dec 21, 2022 |
| Acer          | Aspire 7730ZG               | [bf9325456e](https://linux-hardware.org/?probe=bf9325456e) | Dec 20, 2022 |
| Dell          | Latitude E6430              | [643c90d5e1](https://linux-hardware.org/?probe=643c90d5e1) | Dec 20, 2022 |
| Dell          | Latitude E6430              | [ba280c7787](https://linux-hardware.org/?probe=ba280c7787) | Dec 20, 2022 |
| Lenovo        | ThinkPad Edge E545 20B20... | [0293f9b7c3](https://linux-hardware.org/?probe=0293f9b7c3) | Dec 20, 2022 |
| Sony          | VPCS12V9E                   | [a353c5ef57](https://linux-hardware.org/?probe=a353c5ef57) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [224bdb435d](https://linux-hardware.org/?probe=224bdb435d) | Dec 19, 2022 |
| ASUSTek       | K75VJ                       | [a1b40660b5](https://linux-hardware.org/?probe=a1b40660b5) | Dec 18, 2022 |
| Acer          | Aspire A317-51K             | [b02c6dccc2](https://linux-hardware.org/?probe=b02c6dccc2) | Dec 17, 2022 |
| Toshiba       | Satellite M70               | [9415a97254](https://linux-hardware.org/?probe=9415a97254) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | [5c6f8cd52d](https://linux-hardware.org/?probe=5c6f8cd52d) | Dec 16, 2022 |
| Toshiba       | Satellite M70               | [79506873c1](https://linux-hardware.org/?probe=79506873c1) | Dec 15, 2022 |
| HUAWEI        | HVY-WXX9                    | [87603a034e](https://linux-hardware.org/?probe=87603a034e) | Dec 15, 2022 |
| ECS           | CMPC                        | [53d853228f](https://linux-hardware.org/?probe=53d853228f) | Dec 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [a9505fa3e4](https://linux-hardware.org/?probe=a9505fa3e4) | Dec 12, 2022 |
| HP            | Pavilion Laptop 15-cc5xx    | [0cc39aa03c](https://linux-hardware.org/?probe=0cc39aa03c) | Dec 12, 2022 |
| HP            | 350 G1                      | [c15f80a386](https://linux-hardware.org/?probe=c15f80a386) | Dec 12, 2022 |
| Fusion5       | Lapbook T90B                | [73a67d82fd](https://linux-hardware.org/?probe=73a67d82fd) | Dec 10, 2022 |
| HP            | 250 G5 Notebook PC          | [aca71547f1](https://linux-hardware.org/?probe=aca71547f1) | Dec 08, 2022 |
| Acer          | Aspire 5935                 | [01da97dae6](https://linux-hardware.org/?probe=01da97dae6) | Dec 07, 2022 |
| ASUSTek       | UX31E                       | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| Acer          | Aspire 5935                 | [44895b82f9](https://linux-hardware.org/?probe=44895b82f9) | Dec 05, 2022 |
| ASUSTek       | K53SC                       | [57e7bb2427](https://linux-hardware.org/?probe=57e7bb2427) | Dec 05, 2022 |
| Apple         | MacBookPro8,1               | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| Dell          | XPS 15 9560                 | [3ee313dd51](https://linux-hardware.org/?probe=3ee313dd51) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | [fde8194d5c](https://linux-hardware.org/?probe=fde8194d5c) | Dec 01, 2022 |
| ASUSTek       | K53SC                       | [6d21dd6cea](https://linux-hardware.org/?probe=6d21dd6cea) | Nov 30, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [89e340c4ec](https://linux-hardware.org/?probe=89e340c4ec) | Nov 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [762b81c49e](https://linux-hardware.org/?probe=762b81c49e) | Nov 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [01543655e9](https://linux-hardware.org/?probe=01543655e9) | Nov 29, 2022 |
| Lenovo        | G50-80 80E5                 | [1387bf11ea](https://linux-hardware.org/?probe=1387bf11ea) | Nov 28, 2022 |
| Google        | Akemi                       | [89c466ffd4](https://linux-hardware.org/?probe=89c466ffd4) | Nov 28, 2022 |
| HP            | 255 G8 Notebook PC          | [97cf5008bb](https://linux-hardware.org/?probe=97cf5008bb) | Nov 27, 2022 |
| Acer          | Aspire E5-571G              | [7d6eeaf95c](https://linux-hardware.org/?probe=7d6eeaf95c) | Nov 26, 2022 |
| ASUSTek       | 1002HA                      | [15d5eb998d](https://linux-hardware.org/?probe=15d5eb998d) | Nov 26, 2022 |
| Dell          | Latitude D610               | [437f7630fd](https://linux-hardware.org/?probe=437f7630fd) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| ASUSTek       | 1015CX                      | [89ec4e86f7](https://linux-hardware.org/?probe=89ec4e86f7) | Nov 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [bc3563401b](https://linux-hardware.org/?probe=bc3563401b) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | [46ec8527f5](https://linux-hardware.org/?probe=46ec8527f5) | Nov 25, 2022 |
| Positivo      | Mobile                      | [609b7ff8c9](https://linux-hardware.org/?probe=609b7ff8c9) | Nov 22, 2022 |
| Positivo      | Mobile                      | [5e1d512269](https://linux-hardware.org/?probe=5e1d512269) | Nov 22, 2022 |
| Unknown       | Unknown                     | [c119fbb804](https://linux-hardware.org/?probe=c119fbb804) | Nov 22, 2022 |
| HP            | 8540w                       | [3712bfe3cb](https://linux-hardware.org/?probe=3712bfe3cb) | Nov 21, 2022 |
| Lenovo        | ThinkPad L380 20M6S4E000    | [4f65299a92](https://linux-hardware.org/?probe=4f65299a92) | Nov 20, 2022 |
| Sony          | VPCEH25EN                   | [d9136e5b75](https://linux-hardware.org/?probe=d9136e5b75) | Nov 20, 2022 |
| Dell          | Latitude 5490               | [70b8fb5e89](https://linux-hardware.org/?probe=70b8fb5e89) | Nov 18, 2022 |
| HP            | 245 G8 Notebook PC          | [4d4f9a0e10](https://linux-hardware.org/?probe=4d4f9a0e10) | Nov 17, 2022 |
| Acer          | Aspire A315-21              | [288b53c471](https://linux-hardware.org/?probe=288b53c471) | Nov 16, 2022 |
| Acer          | Aspire A315-21              | [23ec67e81b](https://linux-hardware.org/?probe=23ec67e81b) | Nov 16, 2022 |
| ASUSTek       | K53U                        | [e947ac0aab](https://linux-hardware.org/?probe=e947ac0aab) | Nov 14, 2022 |
| HP            | ProBook 6450b               | [ee3a2a2ef8](https://linux-hardware.org/?probe=ee3a2a2ef8) | Nov 14, 2022 |
| HP            | ProBook 640 G4              | [c120112085](https://linux-hardware.org/?probe=c120112085) | Nov 13, 2022 |
| HP            | Laptop 17-cp0xxx            | [a5575e0c9d](https://linux-hardware.org/?probe=a5575e0c9d) | Nov 12, 2022 |
| HP            | Laptop 17-cp0xxx            | [2e6b12e93d](https://linux-hardware.org/?probe=2e6b12e93d) | Nov 12, 2022 |
| HP            | Pavilion g6                 | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| HP            | EliteBook 840 G3            | [161b81845e](https://linux-hardware.org/?probe=161b81845e) | Nov 11, 2022 |
| Lenovo        | ThinkPad T450s 20BWS33U0... | [ce3e5599ad](https://linux-hardware.org/?probe=ce3e5599ad) | Nov 10, 2022 |
| HP            | Pavilion g6                 | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [0a1efcf166](https://linux-hardware.org/?probe=0a1efcf166) | Nov 08, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [a39cc50a9a](https://linux-hardware.org/?probe=a39cc50a9a) | Nov 07, 2022 |
| Lenovo        | ThinkPad T440p 20AN0033R... | [7ca892ad44](https://linux-hardware.org/?probe=7ca892ad44) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | [0eef83e969](https://linux-hardware.org/?probe=0eef83e969) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | [3268b6af5f](https://linux-hardware.org/?probe=3268b6af5f) | Nov 06, 2022 |
| HP            | EliteBook Folio 1040 G1     | [f2d6eec645](https://linux-hardware.org/?probe=f2d6eec645) | Nov 06, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [f1117abc19](https://linux-hardware.org/?probe=f1117abc19) | Nov 05, 2022 |
| Lenovo        | ThinkPad P51 20HH0014IX     | [e519495581](https://linux-hardware.org/?probe=e519495581) | Nov 04, 2022 |
| Dell          | Inspiron 15-3567            | [dab31889f1](https://linux-hardware.org/?probe=dab31889f1) | Nov 04, 2022 |
| Apple         | MacBookAir6,2               | [fa6ec2e89c](https://linux-hardware.org/?probe=fa6ec2e89c) | Nov 03, 2022 |
| Dell          | Inspiron 7501               | [3eae1f74ca](https://linux-hardware.org/?probe=3eae1f74ca) | Nov 03, 2022 |
| Dell          | Precision M6400             | [b98b318067](https://linux-hardware.org/?probe=b98b318067) | Nov 02, 2022 |
| Acer          | Aspire one 1-431            | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| Lenovo        | ThinkPad W530 2438CTO       | [1915c9d3b0](https://linux-hardware.org/?probe=1915c9d3b0) | Oct 28, 2022 |
| Dell          | Inspiron 5490               | [bbea359211](https://linux-hardware.org/?probe=bbea359211) | Oct 28, 2022 |
| Dell          | Latitude E6510              | [2cb824b444](https://linux-hardware.org/?probe=2cb824b444) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [73d5bfb13a](https://linux-hardware.org/?probe=73d5bfb13a) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [7290786792](https://linux-hardware.org/?probe=7290786792) | Oct 26, 2022 |
| Dell          | Latitude E6510              | [ddb0a31443](https://linux-hardware.org/?probe=ddb0a31443) | Oct 26, 2022 |
| Dell          | Inspiron 3421               | [6ebaad0374](https://linux-hardware.org/?probe=6ebaad0374) | Oct 25, 2022 |
| Lenovo        | ThinkPad T460 20FMS08H00    | [13422369f7](https://linux-hardware.org/?probe=13422369f7) | Oct 25, 2022 |
| ASUSTek       | X555YI                      | [5d6562117a](https://linux-hardware.org/?probe=5d6562117a) | Oct 25, 2022 |
| Dell          | Inspiron N5030              | [dbc717a299](https://linux-hardware.org/?probe=dbc717a299) | Oct 25, 2022 |
| Dell          | Inspiron 3421               | [d10106fb33](https://linux-hardware.org/?probe=d10106fb33) | Oct 24, 2022 |
| Apple         | MacBookPro6,2               | [927bfd543c](https://linux-hardware.org/?probe=927bfd543c) | Oct 24, 2022 |
| Toshiba       | Satellite C75D-B            | [3e39042f59](https://linux-hardware.org/?probe=3e39042f59) | Oct 23, 2022 |
| Toshiba       | Satellite C75D-B            | [b7412d4350](https://linux-hardware.org/?probe=b7412d4350) | Oct 23, 2022 |
| HP            | 15                          | [2831771472](https://linux-hardware.org/?probe=2831771472) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [66418dda52](https://linux-hardware.org/?probe=66418dda52) | Oct 22, 2022 |
| ASUSTek       | N551ZU                      | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| Acer          | Aspire ES1-331              | [f5ace96d5d](https://linux-hardware.org/?probe=f5ace96d5d) | Oct 19, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [4de39d4a1c](https://linux-hardware.org/?probe=4de39d4a1c) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| Dell          | 500                         | [91b78b800a](https://linux-hardware.org/?probe=91b78b800a) | Oct 17, 2022 |
| Dell          | Latitude E5270              | [6f07cdee36](https://linux-hardware.org/?probe=6f07cdee36) | Oct 17, 2022 |
| Samsung       | NC10                        | [1ea93f5095](https://linux-hardware.org/?probe=1ea93f5095) | Oct 16, 2022 |
| MSI           | GS40 6QE Phantom            | [76a55aa9f5](https://linux-hardware.org/?probe=76a55aa9f5) | Oct 14, 2022 |
| Lenovo        | ThinkPad T490 20N20046US    | [a698e6de4d](https://linux-hardware.org/?probe=a698e6de4d) | Oct 13, 2022 |
| eMachines     | eME528                      | [502802d50d](https://linux-hardware.org/?probe=502802d50d) | Oct 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| HP            | Stream Notebook PC 13       | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| Dell          | Latitude E5470              | [eee260b733](https://linux-hardware.org/?probe=eee260b733) | Oct 12, 2022 |
| Dell          | Latitude E5470              | [3bbb87ee1b](https://linux-hardware.org/?probe=3bbb87ee1b) | Oct 12, 2022 |
| Unknown       | Unknown                     | [a098b893f4](https://linux-hardware.org/?probe=a098b893f4) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [65039e3fdd](https://linux-hardware.org/?probe=65039e3fdd) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | [1be1f8f36e](https://linux-hardware.org/?probe=1be1f8f36e) | Oct 09, 2022 |
| HP            | 255 G1                      | [fc9f63bfb6](https://linux-hardware.org/?probe=fc9f63bfb6) | Oct 08, 2022 |
| ASUSTek       | K50ID                       | [05e82f0dd5](https://linux-hardware.org/?probe=05e82f0dd5) | Oct 08, 2022 |
| GPU Compan... | GWTN116-3                   | [caf9a63020](https://linux-hardware.org/?probe=caf9a63020) | Oct 08, 2022 |
| Acer          | Aspire 5739G                | [9a380f66ea](https://linux-hardware.org/?probe=9a380f66ea) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537AF8       | [06dd00b171](https://linux-hardware.org/?probe=06dd00b171) | Oct 08, 2022 |
| Dell          | Latitude 5411               | [4bb05d639f](https://linux-hardware.org/?probe=4bb05d639f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30L0... | [ea6a5c970c](https://linux-hardware.org/?probe=ea6a5c970c) | Oct 07, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [b67d9b67e4](https://linux-hardware.org/?probe=b67d9b67e4) | Oct 06, 2022 |
| Lenovo        | IdeaPad S510p 20298         | [20fb15fcbf](https://linux-hardware.org/?probe=20fb15fcbf) | Oct 06, 2022 |
| GPU Compan... | GWTN116-3                   | [b838d87a4b](https://linux-hardware.org/?probe=b838d87a4b) | Oct 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [0e52b51f87](https://linux-hardware.org/?probe=0e52b51f87) | Oct 05, 2022 |
| Lenovo        | IdeaPad N585 20179          | [dd6693ffa9](https://linux-hardware.org/?probe=dd6693ffa9) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [986b3c962e](https://linux-hardware.org/?probe=986b3c962e) | Oct 04, 2022 |
| Dell          | Precision 7560              | [877583cc90](https://linux-hardware.org/?probe=877583cc90) | Oct 04, 2022 |
| Dell          | Inspiron 3521               | [50615f4621](https://linux-hardware.org/?probe=50615f4621) | Oct 04, 2022 |
| Acer          | Extensa 5230                | [8154485976](https://linux-hardware.org/?probe=8154485976) | Oct 04, 2022 |
| Dell          | Inspiron 7520               | [8125b49bea](https://linux-hardware.org/?probe=8125b49bea) | Oct 03, 2022 |
| Dell          | 500                         | [83c01aa11f](https://linux-hardware.org/?probe=83c01aa11f) | Oct 01, 2022 |
| Lenovo        | B70-80 80MR                 | [69aec9e100](https://linux-hardware.org/?probe=69aec9e100) | Oct 01, 2022 |
| HP            | Notebook                    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | [ddf1904011](https://linux-hardware.org/?probe=ddf1904011) | Oct 01, 2022 |
| Acer          | Aspire A315-55G             | [77605e313d](https://linux-hardware.org/?probe=77605e313d) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Sony          | SVE1512C6EB                 | [c47a3a5bd7](https://linux-hardware.org/?probe=c47a3a5bd7) | Sep 30, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| Dell          | Latitude 5420               | [36ddd1d6d7](https://linux-hardware.org/?probe=36ddd1d6d7) | Sep 30, 2022 |
| Lenovo        | IdeaPad N585 20179          | [dcdafbbd9b](https://linux-hardware.org/?probe=dcdafbbd9b) | Sep 28, 2022 |
| HP            | Pavilion dv7                | [5479c35130](https://linux-hardware.org/?probe=5479c35130) | Sep 28, 2022 |
| Lenovo        | IdeaPad N585 20179          | [0a8aed635a](https://linux-hardware.org/?probe=0a8aed635a) | Sep 28, 2022 |
| Toshiba       | Satellite Pro R50-C         | [834ef0ec59](https://linux-hardware.org/?probe=834ef0ec59) | Sep 27, 2022 |
| Toshiba       | Satellite Pro R50-C         | [564d385b61](https://linux-hardware.org/?probe=564d385b61) | Sep 27, 2022 |
| Toshiba       | Satellite C650              | [c7920c2e68](https://linux-hardware.org/?probe=c7920c2e68) | Sep 24, 2022 |
| Packard Be... | EasyNote MH45               | [c312580997](https://linux-hardware.org/?probe=c312580997) | Sep 24, 2022 |
| Unknown       | Unknown                     | [63b1596d63](https://linux-hardware.org/?probe=63b1596d63) | Sep 24, 2022 |
| Toshiba       | Satellite C55D-B            | [5b2029b4d3](https://linux-hardware.org/?probe=5b2029b4d3) | Sep 24, 2022 |
| Toshiba       | Satellite A300              | [3f6203e550](https://linux-hardware.org/?probe=3f6203e550) | Sep 24, 2022 |
| Tactus        | GeoBook 140                 | [7d8700d0e1](https://linux-hardware.org/?probe=7d8700d0e1) | Sep 23, 2022 |
| Dell          | Latitude 5411               | [018a9c569a](https://linux-hardware.org/?probe=018a9c569a) | Sep 23, 2022 |
| HP            | EliteBook 840 G3            | [c3a88ed62d](https://linux-hardware.org/?probe=c3a88ed62d) | Sep 22, 2022 |
| Lenovo        | ThinkPad P51s 20HCS00F00    | [5f0dc19f55](https://linux-hardware.org/?probe=5f0dc19f55) | Sep 22, 2022 |
| Lenovo        | ThinkPad T61 7659AB7        | [aa07f9c271](https://linux-hardware.org/?probe=aa07f9c271) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61p 6457A24       | [d98e9a64bd](https://linux-hardware.org/?probe=d98e9a64bd) | Sep 20, 2022 |
| HP            | ProBook 450 G2              | [73c35ad64a](https://linux-hardware.org/?probe=73c35ad64a) | Sep 20, 2022 |
| Dell          | Precision 7750              | [ced8b5a7b2](https://linux-hardware.org/?probe=ced8b5a7b2) | Sep 19, 2022 |
| Lenovo        | ThinkPad X220 42918F6       | [69dda668fc](https://linux-hardware.org/?probe=69dda668fc) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| Dell          | Latitude 7490               | [ce54bcd741](https://linux-hardware.org/?probe=ce54bcd741) | Sep 15, 2022 |
| Dell          | Inspiron 3576               | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| HP            | Laptop 15-ef1xxx            | [dd55f6960d](https://linux-hardware.org/?probe=dd55f6960d) | Sep 15, 2022 |
| Dell          | Precision 5540              | [229337f709](https://linux-hardware.org/?probe=229337f709) | Sep 13, 2022 |
| HP            | 1000                        | [65024f3d7a](https://linux-hardware.org/?probe=65024f3d7a) | Sep 13, 2022 |
| Dell          | Inspiron 3537               | [afd2b6555e](https://linux-hardware.org/?probe=afd2b6555e) | Sep 12, 2022 |
| ASUSTek       | X453SA                      | [1446eda5e9](https://linux-hardware.org/?probe=1446eda5e9) | Sep 12, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| Dell          | Latitude 9520               | [04188fb6c2](https://linux-hardware.org/?probe=04188fb6c2) | Sep 06, 2022 |
| ASUSTek       | K55VD                       | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| HP            | 255 G7 Notebook PC          | [dd775ffe8f](https://linux-hardware.org/?probe=dd775ffe8f) | Sep 05, 2022 |
| HP            | Laptop 15-dw0xxx            | [1bd6f2ba6f](https://linux-hardware.org/?probe=1bd6f2ba6f) | Sep 04, 2022 |
| Google        | Kip                         | [e92d971d5e](https://linux-hardware.org/?probe=e92d971d5e) | Sep 04, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Google        | Reks                        | [d88eecb32d](https://linux-hardware.org/?probe=d88eecb32d) | Sep 03, 2022 |
| HP            | EliteBook 2570p             | [506f9da93b](https://linux-hardware.org/?probe=506f9da93b) | Sep 03, 2022 |
| Apple         | MacBookPro16,1              | [8add31fdfe](https://linux-hardware.org/?probe=8add31fdfe) | Sep 02, 2022 |
| Acer          | Aspire A315-31              | [21d3a4bd56](https://linux-hardware.org/?probe=21d3a4bd56) | Sep 02, 2022 |
| Dell          | Latitude E5530 non-vPro     | [7e839a0ef4](https://linux-hardware.org/?probe=7e839a0ef4) | Aug 30, 2022 |
| Acer          | Aspire E5-771G              | [76803c2532](https://linux-hardware.org/?probe=76803c2532) | Aug 30, 2022 |
| Sony          | VPCSB1V9R                   | [b54e74887f](https://linux-hardware.org/?probe=b54e74887f) | Aug 29, 2022 |
| Acer          | Aspire E5-771G              | [52cc79c6d9](https://linux-hardware.org/?probe=52cc79c6d9) | Aug 29, 2022 |
| Dell          | Inspiron N5010              | [b9953ab67e](https://linux-hardware.org/?probe=b9953ab67e) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | [f725a87544](https://linux-hardware.org/?probe=f725a87544) | Aug 27, 2022 |
| Lenovo        | 14w 81MQ000JUS              | [d71f12bede](https://linux-hardware.org/?probe=d71f12bede) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | [8a689fc0fd](https://linux-hardware.org/?probe=8a689fc0fd) | Aug 27, 2022 |
| Dell          | XPS 13 9380                 | [5bb7561235](https://linux-hardware.org/?probe=5bb7561235) | Aug 25, 2022 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | [d269aaa456](https://linux-hardware.org/?probe=d269aaa456) | Aug 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [92be7f3368](https://linux-hardware.org/?probe=92be7f3368) | Aug 24, 2022 |
| Acer          | Aspire 5740                 | [5652f2c73d](https://linux-hardware.org/?probe=5652f2c73d) | Aug 24, 2022 |
| Lenovo        | 14w 81MQ000JUS              | [1ff769c6ef](https://linux-hardware.org/?probe=1ff769c6ef) | Aug 23, 2022 |
| Acer          | Unknown                     | [c35afdde00](https://linux-hardware.org/?probe=c35afdde00) | Aug 21, 2022 |
| Lenovo        | ThinkPad X220 4291V1C       | [8ab56e33c4](https://linux-hardware.org/?probe=8ab56e33c4) | Aug 21, 2022 |
| Lenovo        | ThinkPad T480 20L5000BGE    | [dd53f23249](https://linux-hardware.org/?probe=dd53f23249) | Aug 20, 2022 |
| HP            | EliteBook 8540p             | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| Packard Be... | EasyNote TJ66               | [96c3144e93](https://linux-hardware.org/?probe=96c3144e93) | Aug 19, 2022 |
| ASUSTek       | K53TA                       | [db6525efb3](https://linux-hardware.org/?probe=db6525efb3) | Aug 15, 2022 |
| ASUSTek       | K84C                        | [c19b238bcf](https://linux-hardware.org/?probe=c19b238bcf) | Aug 15, 2022 |
| Lenovo        | ThinkPad T460s 20FAS0Q90... | [644c7518e9](https://linux-hardware.org/?probe=644c7518e9) | Aug 14, 2022 |
| ASUSTek       | X101CH                      | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| Panasonic     | CF-31XEUAXMF                | [914e54f984](https://linux-hardware.org/?probe=914e54f984) | Aug 13, 2022 |
| Toshiba       | PT10F                       | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | [5bb07e1a28](https://linux-hardware.org/?probe=5bb07e1a28) | Aug 11, 2022 |
| Dell          | System XPS L502X            | [1453afc507](https://linux-hardware.org/?probe=1453afc507) | Aug 09, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | [aed42791cd](https://linux-hardware.org/?probe=aed42791cd) | Aug 09, 2022 |
| ASUSTek       | K53SC                       | [15522c32d7](https://linux-hardware.org/?probe=15522c32d7) | Aug 06, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6JY0... | [7d85d4f00b](https://linux-hardware.org/?probe=7d85d4f00b) | Aug 06, 2022 |
| Render        | NOTEBOOK Revision A         | [90a540652f](https://linux-hardware.org/?probe=90a540652f) | Aug 06, 2022 |
| ASUSTek       | 1015CX                      | [f8d358f521](https://linux-hardware.org/?probe=f8d358f521) | Aug 05, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [32a99db93e](https://linux-hardware.org/?probe=32a99db93e) | Aug 04, 2022 |
| Acer          | Aspire V3-551G              | [8b0237ee5e](https://linux-hardware.org/?probe=8b0237ee5e) | Aug 03, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | [fdd30ffa23](https://linux-hardware.org/?probe=fdd30ffa23) | Aug 03, 2022 |
| Acer          | Aspire V3-551G              | [4b8ed45c90](https://linux-hardware.org/?probe=4b8ed45c90) | Aug 03, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [8aa899fe67](https://linux-hardware.org/?probe=8aa899fe67) | Aug 02, 2022 |
| GMKtec        | NucBox5                     | [5023bc1773](https://linux-hardware.org/?probe=5023bc1773) | Aug 02, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [e512f0884d](https://linux-hardware.org/?probe=e512f0884d) | Aug 01, 2022 |
| Dell          | Inspiron 5748               | [9113ee6d54](https://linux-hardware.org/?probe=9113ee6d54) | Aug 01, 2022 |
| Unknown       | Unknown                     | [50153bd9ff](https://linux-hardware.org/?probe=50153bd9ff) | Aug 01, 2022 |
| HP            | Pavilion dv2600             | [87651d6efc](https://linux-hardware.org/?probe=87651d6efc) | Jul 31, 2022 |
| Unknown       | Unknown                     | [aa0c007709](https://linux-hardware.org/?probe=aa0c007709) | Jul 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [745f6815cb](https://linux-hardware.org/?probe=745f6815cb) | Jul 30, 2022 |
| Alienware     | 17 R4                       | [ae2cd7095b](https://linux-hardware.org/?probe=ae2cd7095b) | Jul 29, 2022 |
| Dell          | Vostro 3700                 | [0a4b552d69](https://linux-hardware.org/?probe=0a4b552d69) | Jul 28, 2022 |
| Samsung       | R59P/R60P/R61P              | [d435057109](https://linux-hardware.org/?probe=d435057109) | Jul 28, 2022 |
| Schenker      | WORK (Early 2021)           | [8666cc396a](https://linux-hardware.org/?probe=8666cc396a) | Jul 28, 2022 |
| ASUSTek       | X450CP                      | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| LG Electro... | LE50-5BC6H1                 | [010123b7d5](https://linux-hardware.org/?probe=010123b7d5) | Jul 26, 2022 |
| Lenovo        | G50-30 80G0                 | [c380d02bbf](https://linux-hardware.org/?probe=c380d02bbf) | Jul 25, 2022 |
| Apple         | MacBookPro12,1              | [4db419918b](https://linux-hardware.org/?probe=4db419918b) | Jul 25, 2022 |
| Toshiba       | NB205                       | [2dd373f150](https://linux-hardware.org/?probe=2dd373f150) | Jul 23, 2022 |
| ASUSTek       | N56VZ                       | [3813cc04d1](https://linux-hardware.org/?probe=3813cc04d1) | Jul 22, 2022 |
| Dell          | Inspiron N5030              | [3ae520c245](https://linux-hardware.org/?probe=3ae520c245) | Jul 22, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [75f71928fe](https://linux-hardware.org/?probe=75f71928fe) | Jul 21, 2022 |
| MSI           | U-100 Ver.001               | [b5b7407958](https://linux-hardware.org/?probe=b5b7407958) | Jul 20, 2022 |
| MSI           | U-100 Ver.001               | [819488216f](https://linux-hardware.org/?probe=819488216f) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [75b4088788](https://linux-hardware.org/?probe=75b4088788) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [3c2afd2b5e](https://linux-hardware.org/?probe=3c2afd2b5e) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| ASUSTek       | FX503VM                     | [47c70e3628](https://linux-hardware.org/?probe=47c70e3628) | Jul 19, 2022 |
| Dell          | Latitude D430               | [7ae462d6f7](https://linux-hardware.org/?probe=7ae462d6f7) | Jul 18, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | [117f9a585b](https://linux-hardware.org/?probe=117f9a585b) | Jul 17, 2022 |
| ASUSTek       | U30Jc                       | [3a6a0ec169](https://linux-hardware.org/?probe=3a6a0ec169) | Jul 17, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | [e408c1236c](https://linux-hardware.org/?probe=e408c1236c) | Jul 17, 2022 |
| Acer          | Aspire E1-532               | [13d38a6632](https://linux-hardware.org/?probe=13d38a6632) | Jul 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [a6ae556389](https://linux-hardware.org/?probe=a6ae556389) | Jul 16, 2022 |
| Samsung       | R59P/R60P/R61P              | [4773de66cf](https://linux-hardware.org/?probe=4773de66cf) | Jul 15, 2022 |
| ASUSTek       | K53SC                       | [dd45175b9d](https://linux-hardware.org/?probe=dd45175b9d) | Jul 15, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [daf43ce57a](https://linux-hardware.org/?probe=daf43ce57a) | Jul 13, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [4a587952db](https://linux-hardware.org/?probe=4a587952db) | Jul 13, 2022 |
| Apple         | MacBookPro15,3              | [a8f8224853](https://linux-hardware.org/?probe=a8f8224853) | Jul 11, 2022 |
| ASUSTek       | X453MA                      | [da05c4539d](https://linux-hardware.org/?probe=da05c4539d) | Jul 11, 2022 |
| MSI           | GF63 Thin 9RCX              | [f2f3db370a](https://linux-hardware.org/?probe=f2f3db370a) | Jul 10, 2022 |
| HP            | Laptop 14-bw0xx             | [17b90f7a4b](https://linux-hardware.org/?probe=17b90f7a4b) | Jul 10, 2022 |
| HP            | Laptop 14-bw0xx             | [3b8444274b](https://linux-hardware.org/?probe=3b8444274b) | Jul 10, 2022 |
| Lenovo        | ThinkPad W540 20BG001KGE    | [434091ba07](https://linux-hardware.org/?probe=434091ba07) | Jul 10, 2022 |
| Toshiba       | NB205                       | [f4046cb02f](https://linux-hardware.org/?probe=f4046cb02f) | Jul 10, 2022 |
| Acer          | Aspire E5-521               | [7becd2f2df](https://linux-hardware.org/?probe=7becd2f2df) | Jul 10, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [bb736b4d03](https://linux-hardware.org/?probe=bb736b4d03) | Jul 08, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [b2d4e91300](https://linux-hardware.org/?probe=b2d4e91300) | Jul 07, 2022 |
| HP            | Notebook                    | [0c64a91465](https://linux-hardware.org/?probe=0c64a91465) | Jul 07, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [5cff36844a](https://linux-hardware.org/?probe=5cff36844a) | Jul 07, 2022 |
| Lenovo        | G50-70 20351                | [68efa303fa](https://linux-hardware.org/?probe=68efa303fa) | Jul 07, 2022 |
| Chuwi         | FreeBook                    | [3e0b057e38](https://linux-hardware.org/?probe=3e0b057e38) | Jul 07, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [e5bf9b72d0](https://linux-hardware.org/?probe=e5bf9b72d0) | Jul 07, 2022 |
| Acer          | Aspire E5-571               | [2225f70ee7](https://linux-hardware.org/?probe=2225f70ee7) | Jul 06, 2022 |
| Dell          | Inspiron 5593               | [542470182e](https://linux-hardware.org/?probe=542470182e) | Jul 05, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | [51b138f349](https://linux-hardware.org/?probe=51b138f349) | Jul 04, 2022 |
| Lenovo        | V330-15IKB 81AX             | [2f915d68e5](https://linux-hardware.org/?probe=2f915d68e5) | Jul 04, 2022 |
| ASUSTek       | K53SC                       | [ef75149636](https://linux-hardware.org/?probe=ef75149636) | Jul 03, 2022 |
| Samsung       | 370E4K                      | [a6512c1606](https://linux-hardware.org/?probe=a6512c1606) | Jul 03, 2022 |
| HP            | Mini 210-1100               | [72289b7641](https://linux-hardware.org/?probe=72289b7641) | Jul 03, 2022 |
| HP            | Mini 210-1100               | [aaa9b86216](https://linux-hardware.org/?probe=aaa9b86216) | Jul 02, 2022 |
| Dell          | 500                         | [040e3cb12c](https://linux-hardware.org/?probe=040e3cb12c) | Jun 30, 2022 |
| HP            | EliteBook 840 G3            | [9ce5b9c45c](https://linux-hardware.org/?probe=9ce5b9c45c) | Jun 30, 2022 |
| Acer          | Aspire E5-521               | [f532d90f38](https://linux-hardware.org/?probe=f532d90f38) | Jun 29, 2022 |
| Standard      | Unknown                     | [1a94acbc05](https://linux-hardware.org/?probe=1a94acbc05) | Jun 29, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [e08493100f](https://linux-hardware.org/?probe=e08493100f) | Jun 29, 2022 |
| Lenovo        | IdeaPad 330-17IKB 81DK      | [2fa204d33e](https://linux-hardware.org/?probe=2fa204d33e) | Jun 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [bd4018ed46](https://linux-hardware.org/?probe=bd4018ed46) | Jun 29, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [372d361276](https://linux-hardware.org/?probe=372d361276) | Jun 28, 2022 |
| ASUSTek       | X551MA                      | [9bdb2a5577](https://linux-hardware.org/?probe=9bdb2a5577) | Jun 28, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [ac9a35e85e](https://linux-hardware.org/?probe=ac9a35e85e) | Jun 27, 2022 |
| HP            | Laptop 15-ef1xxx            | [d0200625ac](https://linux-hardware.org/?probe=d0200625ac) | Jun 27, 2022 |
| Dell          | Inspiron 15-3567            | [e6d22a4d34](https://linux-hardware.org/?probe=e6d22a4d34) | Jun 27, 2022 |
| Standard      | Unknown                     | [93ac825a25](https://linux-hardware.org/?probe=93ac825a25) | Jun 27, 2022 |
| Apple         | MacBookPro1,1               | [feddac03b9](https://linux-hardware.org/?probe=feddac03b9) | Jun 26, 2022 |
| Lenovo        | ThinkPad T420s 417152U      | [cc52ed5e41](https://linux-hardware.org/?probe=cc52ed5e41) | Jun 26, 2022 |
| HP            | Pavilion dv5                | [4009a4fd8c](https://linux-hardware.org/?probe=4009a4fd8c) | Jun 24, 2022 |
| HP            | Laptop 15-ef1xxx            | [1d18aab349](https://linux-hardware.org/?probe=1d18aab349) | Jun 23, 2022 |
| Dell          | Inspiron 5570               | [4a61f83195](https://linux-hardware.org/?probe=4a61f83195) | Jun 23, 2022 |
| MSI           | Modern 15 A5M               | [b648b81eca](https://linux-hardware.org/?probe=b648b81eca) | Jun 23, 2022 |
| Apple         | MacBookPro14,1              | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Alienware     | 17 R4                       | [74b66aebc5](https://linux-hardware.org/?probe=74b66aebc5) | Jun 21, 2022 |
| Dell          | Inspiron 15-3567            | [9538654245](https://linux-hardware.org/?probe=9538654245) | Jun 21, 2022 |
| HP            | 15                          | [61e6eddc93](https://linux-hardware.org/?probe=61e6eddc93) | Jun 20, 2022 |
| Google        | Kindred                     | [c12b15c596](https://linux-hardware.org/?probe=c12b15c596) | Jun 17, 2022 |
| Acer          | Aspire 7720                 | [3f098cc493](https://linux-hardware.org/?probe=3f098cc493) | Jun 15, 2022 |
| Dynabook      | TECRA A50-J                 | [3f4449202f](https://linux-hardware.org/?probe=3f4449202f) | Jun 14, 2022 |
| Sony          | VPCSB1V9R                   | [c1490b2a1c](https://linux-hardware.org/?probe=c1490b2a1c) | Jun 14, 2022 |
| HP            | ProBook 445 G7              | [f41d413820](https://linux-hardware.org/?probe=f41d413820) | Jun 13, 2022 |
| Lenovo        | ThinkPad T530 23923MG       | [cf21c4e831](https://linux-hardware.org/?probe=cf21c4e831) | Jun 12, 2022 |
| HP            | 255 G7 Notebook PC          | [0ebaae147d](https://linux-hardware.org/?probe=0ebaae147d) | Jun 12, 2022 |
| GPU Compan... | GWTN141-4                   | [ba579cb383](https://linux-hardware.org/?probe=ba579cb383) | Jun 11, 2022 |
| Matsushita... | CF-W5LWEZZBM                | [380c6df037](https://linux-hardware.org/?probe=380c6df037) | Jun 11, 2022 |
| Packard Be... | EasyNote TK11BZ             | [f9c69ea1c6](https://linux-hardware.org/?probe=f9c69ea1c6) | Jun 11, 2022 |
| Lenovo        | G505 20240                  | [0b0d5e5252](https://linux-hardware.org/?probe=0b0d5e5252) | Jun 11, 2022 |
| Dell          | Latitude 7280               | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | [565722f81e](https://linux-hardware.org/?probe=565722f81e) | Jun 09, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | [c36b6d8e2c](https://linux-hardware.org/?probe=c36b6d8e2c) | Jun 09, 2022 |
| GPU Compan... | GWTN116-3                   | [bd0f56a43c](https://linux-hardware.org/?probe=bd0f56a43c) | Jun 09, 2022 |
| Chuwi         | GemiBook Pro                | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| Acer          | Aspire 7720                 | [640b757bc8](https://linux-hardware.org/?probe=640b757bc8) | Jun 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [674cab9d61](https://linux-hardware.org/?probe=674cab9d61) | Jun 08, 2022 |
| Lenovo        | ThinkPad L380 20M6S4J400    | [dc1bcd1532](https://linux-hardware.org/?probe=dc1bcd1532) | Jun 08, 2022 |
| Acer          | Aspire E5-573               | [bb17805ada](https://linux-hardware.org/?probe=bb17805ada) | Jun 08, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [77a5e1c6f9](https://linux-hardware.org/?probe=77a5e1c6f9) | Jun 08, 2022 |
| Acer          | Aspire 7720                 | [ac4362743a](https://linux-hardware.org/?probe=ac4362743a) | Jun 07, 2022 |
| AMI           | Intel                       | [79b1f29bc4](https://linux-hardware.org/?probe=79b1f29bc4) | Jun 07, 2022 |
| AMI           | Intel                       | [d7746ec6d5](https://linux-hardware.org/?probe=d7746ec6d5) | Jun 07, 2022 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | [c4250d2ee2](https://linux-hardware.org/?probe=c4250d2ee2) | Jun 07, 2022 |
| Fujitsu       | LIFEBOOK U772               | [8dcf195f94](https://linux-hardware.org/?probe=8dcf195f94) | Jun 07, 2022 |
| Digma         | EVE 15 C413 ES5059EW        | [26eb7d39e1](https://linux-hardware.org/?probe=26eb7d39e1) | Jun 06, 2022 |
| HP            | Pavilion g7                 | [b31de17368](https://linux-hardware.org/?probe=b31de17368) | Jun 06, 2022 |
| MSI           | PR601/VR603                 | [9763977184](https://linux-hardware.org/?probe=9763977184) | Jun 05, 2022 |
| Chuwi         | GemiBook Pro                | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| Dell          | Inspiron N4010              | [49e472d67e](https://linux-hardware.org/?probe=49e472d67e) | Jun 02, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [dfe3e4b66b](https://linux-hardware.org/?probe=dfe3e4b66b) | Jun 02, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [d620bac2cb](https://linux-hardware.org/?probe=d620bac2cb) | Jun 02, 2022 |
| Dell          | Latitude D820               | [8c2336469f](https://linux-hardware.org/?probe=8c2336469f) | Jun 01, 2022 |
| Acer          | Aspire 5740                 | [db6d025d69](https://linux-hardware.org/?probe=db6d025d69) | Jun 01, 2022 |
| Lenovo        | ThinkPad L13 20R4S4WG00     | [14100804b6](https://linux-hardware.org/?probe=14100804b6) | May 31, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [e46a1497d8](https://linux-hardware.org/?probe=e46a1497d8) | May 31, 2022 |
| Dell          | Latitude 5511               | [bc6fd9e79d](https://linux-hardware.org/?probe=bc6fd9e79d) | May 30, 2022 |
| Medion        | E15407                      | [6e457b6abb](https://linux-hardware.org/?probe=6e457b6abb) | May 29, 2022 |
| Medion        | E15407                      | [a0d6c795e7](https://linux-hardware.org/?probe=a0d6c795e7) | May 29, 2022 |
| TUXEDO        | N14xWU                      | [c20d682e14](https://linux-hardware.org/?probe=c20d682e14) | May 29, 2022 |
| TUXEDO        | N14xWU                      | [8711ac9989](https://linux-hardware.org/?probe=8711ac9989) | May 26, 2022 |
| Acer          | Aspire 5740                 | [2c541b20f6](https://linux-hardware.org/?probe=2c541b20f6) | May 26, 2022 |
| HP            | Laptop 15-bw0xx             | [f71c048a96](https://linux-hardware.org/?probe=f71c048a96) | May 25, 2022 |
| HP            | Mini 5103                   | [aa7f4e957e](https://linux-hardware.org/?probe=aa7f4e957e) | May 23, 2022 |
| ASUSTek       | X510UA                      | [51d57b9e53](https://linux-hardware.org/?probe=51d57b9e53) | May 22, 2022 |
| Sony          | VGN-NS21S_S                 | [0c972ad98b](https://linux-hardware.org/?probe=0c972ad98b) | May 21, 2022 |
| HP            | Pavilion dv6000 (RR374EA... | [926749e311](https://linux-hardware.org/?probe=926749e311) | May 21, 2022 |
| Google        | Snappy                      | [c88d27b24a](https://linux-hardware.org/?probe=c88d27b24a) | May 20, 2022 |
| Google        | Snappy                      | [9fc85cd49a](https://linux-hardware.org/?probe=9fc85cd49a) | May 20, 2022 |
| Google        | Snappy                      | [cb9e7730ad](https://linux-hardware.org/?probe=cb9e7730ad) | May 20, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | [baed2325d7](https://linux-hardware.org/?probe=baed2325d7) | May 20, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [086fceea4f](https://linux-hardware.org/?probe=086fceea4f) | May 19, 2022 |
| Lenovo        | ThinkPad E580 20KS001JGE    | [724c06c08c](https://linux-hardware.org/?probe=724c06c08c) | May 19, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | [e4150ff93b](https://linux-hardware.org/?probe=e4150ff93b) | May 19, 2022 |
| IBM           | ThinkPad T43 2668F5G        | [af59841e31](https://linux-hardware.org/?probe=af59841e31) | May 18, 2022 |
| Dell          | Latitude D610               | [2e945626d4](https://linux-hardware.org/?probe=2e945626d4) | May 17, 2022 |
| Dell          | Latitude D610               | [9ee1df5d0e](https://linux-hardware.org/?probe=9ee1df5d0e) | May 17, 2022 |
| Dell          | Latitude E6410              | [ae757ea3a4](https://linux-hardware.org/?probe=ae757ea3a4) | May 16, 2022 |
| ASUSTek       | UL30A                       | [c121dd37ba](https://linux-hardware.org/?probe=c121dd37ba) | May 16, 2022 |
| ASUSTek       | X101CH                      | [544536b2d8](https://linux-hardware.org/?probe=544536b2d8) | May 16, 2022 |
| ASUSTek       | X101CH                      | [fbcf200ed5](https://linux-hardware.org/?probe=fbcf200ed5) | May 16, 2022 |
| HP            | Mini 110-1100               | [b93ac7c302](https://linux-hardware.org/?probe=b93ac7c302) | May 16, 2022 |
| HP            | Mini 110-1100               | [4a5f85e53d](https://linux-hardware.org/?probe=4a5f85e53d) | May 16, 2022 |
| Dell          | Latitude 5580               | [c2f15d647a](https://linux-hardware.org/?probe=c2f15d647a) | May 15, 2022 |
| Google        | Droid                       | [e938864c93](https://linux-hardware.org/?probe=e938864c93) | May 15, 2022 |
| Lenovo        | ThinkPad X200s 74664SJ      | [65728fda7a](https://linux-hardware.org/?probe=65728fda7a) | May 14, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [a3b1829dec](https://linux-hardware.org/?probe=a3b1829dec) | May 13, 2022 |
| AMI           | Cherry Trail CR             | [62744ba7e3](https://linux-hardware.org/?probe=62744ba7e3) | May 12, 2022 |
| ASUSTek       | A7K                         | [29ca1c7e33](https://linux-hardware.org/?probe=29ca1c7e33) | May 11, 2022 |
| Dell          | Latitude E6410              | [a14c28c93f](https://linux-hardware.org/?probe=a14c28c93f) | May 11, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [bb4a27a023](https://linux-hardware.org/?probe=bb4a27a023) | May 10, 2022 |
| Dell          | Latitude 7400               | [a0600c38f3](https://linux-hardware.org/?probe=a0600c38f3) | May 09, 2022 |
| Unknown       | Unknown                     | [f802e84b8e](https://linux-hardware.org/?probe=f802e84b8e) | May 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS6FF00    | [3e3da41a35](https://linux-hardware.org/?probe=3e3da41a35) | May 08, 2022 |
| Dell          | Latitude E6410              | [361bcaa4cc](https://linux-hardware.org/?probe=361bcaa4cc) | May 07, 2022 |
| Dell          | Inspiron 7501               | [a8a1e1e3a2](https://linux-hardware.org/?probe=a8a1e1e3a2) | May 07, 2022 |
| HP            | Compaq 6820s                | [1ba74fc299](https://linux-hardware.org/?probe=1ba74fc299) | May 07, 2022 |
| HP            | Compaq 6820s                | [5b027deec0](https://linux-hardware.org/?probe=5b027deec0) | May 07, 2022 |
| Toshiba       | Satellite C70D-B            | [fa4a4b7ffc](https://linux-hardware.org/?probe=fa4a4b7ffc) | May 06, 2022 |
| Acer          | Aspire 5740                 | [e754b48e71](https://linux-hardware.org/?probe=e754b48e71) | May 06, 2022 |
| Dell          | Latitude 7420               | [384325350c](https://linux-hardware.org/?probe=384325350c) | May 05, 2022 |
| Google        | Auron_Yuna                  | [795d9af5a7](https://linux-hardware.org/?probe=795d9af5a7) | May 05, 2022 |
| Dell          | XPS M1530                   | [760cae00c1](https://linux-hardware.org/?probe=760cae00c1) | May 03, 2022 |
| ASUSTek       | K53SC                       | [1533323fbf](https://linux-hardware.org/?probe=1533323fbf) | May 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [981f468940](https://linux-hardware.org/?probe=981f468940) | May 02, 2022 |
| Acer          | Aspire 5740                 | [6e1a9ce167](https://linux-hardware.org/?probe=6e1a9ce167) | May 01, 2022 |
| Razer         | Blade Stealth 13 Late 20... | [ba8fa66c1c](https://linux-hardware.org/?probe=ba8fa66c1c) | May 01, 2022 |
| Acer          | Aspire 5740                 | [f9e5dd9719](https://linux-hardware.org/?probe=f9e5dd9719) | May 01, 2022 |
| Dell          | XPS M1530                   | [757d1b099e](https://linux-hardware.org/?probe=757d1b099e) | Apr 30, 2022 |
| ASUSTek       | T100HAN                     | [5ee200cfbe](https://linux-hardware.org/?probe=5ee200cfbe) | Apr 30, 2022 |
| ASUSTek       | K53SC                       | [f2605ba739](https://linux-hardware.org/?probe=f2605ba739) | Apr 29, 2022 |
| Acer          | Aspire ES1-311              | [aa4612575b](https://linux-hardware.org/?probe=aa4612575b) | Apr 29, 2022 |
| HP            | Compaq 6730b (GW687AV)      | [96ee86a3c6](https://linux-hardware.org/?probe=96ee86a3c6) | Apr 28, 2022 |
| Dell          | Inspiron 3135               | [6ca6980f06](https://linux-hardware.org/?probe=6ca6980f06) | Apr 28, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [fc0cea6830](https://linux-hardware.org/?probe=fc0cea6830) | Apr 27, 2022 |
| Acer          | Aspire ES1-512              | [f0ed67e309](https://linux-hardware.org/?probe=f0ed67e309) | Apr 26, 2022 |
| Dell          | Latitude 7480               | [7e85baf2f4](https://linux-hardware.org/?probe=7e85baf2f4) | Apr 26, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [bd286b124a](https://linux-hardware.org/?probe=bd286b124a) | Apr 25, 2022 |
| HP            | 255 G8 Notebook PC          | [c16cb4e0d6](https://linux-hardware.org/?probe=c16cb4e0d6) | Apr 24, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| ASUSTek       | 1215N                       | [93ad513620](https://linux-hardware.org/?probe=93ad513620) | Apr 24, 2022 |
| Lenovo        | B590 20206                  | [80befa3088](https://linux-hardware.org/?probe=80befa3088) | Apr 23, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| Dell          | XPS M1530                   | [f22a6a2c55](https://linux-hardware.org/?probe=f22a6a2c55) | Apr 21, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [e87dfd05bc](https://linux-hardware.org/?probe=e87dfd05bc) | Apr 20, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [fae46ae55c](https://linux-hardware.org/?probe=fae46ae55c) | Apr 20, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [d277143404](https://linux-hardware.org/?probe=d277143404) | Apr 20, 2022 |
| HP            | 255 G8 Notebook PC          | [d88db86125](https://linux-hardware.org/?probe=d88db86125) | Apr 20, 2022 |
| Dell          | XPS M1530                   | [60d3e4f97f](https://linux-hardware.org/?probe=60d3e4f97f) | Apr 20, 2022 |
| HP            | Compaq 6730s                | [4902d2bf25](https://linux-hardware.org/?probe=4902d2bf25) | Apr 16, 2022 |
| Positivo B... | VJC141F11X-B0111L           | [5ea499eca7](https://linux-hardware.org/?probe=5ea499eca7) | Apr 16, 2022 |
| Dell          | Latitude E6540              | [94fbc5408f](https://linux-hardware.org/?probe=94fbc5408f) | Apr 15, 2022 |
| HP            | Compaq 6730s                | [755dcc7629](https://linux-hardware.org/?probe=755dcc7629) | Apr 15, 2022 |
| Lenovo        | ThinkPad X280 20KE001MMX    | [fb0da9def7](https://linux-hardware.org/?probe=fb0da9def7) | Apr 15, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [554040d7b4](https://linux-hardware.org/?probe=554040d7b4) | Apr 14, 2022 |
| Lenovo        | ThinkPad P53 20QNS01C00     | [b320a8cca8](https://linux-hardware.org/?probe=b320a8cca8) | Apr 14, 2022 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [1f9cb1427a](https://linux-hardware.org/?probe=1f9cb1427a) | Apr 13, 2022 |
| Lenovo        | ThinkPad T480s 20L7001PI... | [53c7e12994](https://linux-hardware.org/?probe=53c7e12994) | Apr 13, 2022 |
| Dynabook      | TECRA X40-F                 | [6d6f37f70e](https://linux-hardware.org/?probe=6d6f37f70e) | Apr 13, 2022 |
| Dell          | Precision 7550              | [624c231f19](https://linux-hardware.org/?probe=624c231f19) | Apr 13, 2022 |
| Lenovo        | IdeaPad Y550 4186           | [0ba7d3b80a](https://linux-hardware.org/?probe=0ba7d3b80a) | Apr 13, 2022 |
| HP            | Laptop 15-bw0xx             | [1c15e67e64](https://linux-hardware.org/?probe=1c15e67e64) | Apr 11, 2022 |
| ASUSTek       | K53SC                       | [8b6bb16303](https://linux-hardware.org/?probe=8b6bb16303) | Apr 08, 2022 |
| Toshiba       | NB505                       | [55f9f70b0b](https://linux-hardware.org/?probe=55f9f70b0b) | Apr 08, 2022 |
| HP            | ENVY Sleekbook 6 PC         | [2e5d15f716](https://linux-hardware.org/?probe=2e5d15f716) | Apr 08, 2022 |
| HP            | Laptop 15s-fq2xxx           | [b073554afc](https://linux-hardware.org/?probe=b073554afc) | Apr 08, 2022 |
| Dell          | Latitude 5521               | [ce1e3c5551](https://linux-hardware.org/?probe=ce1e3c5551) | Apr 07, 2022 |
| Dell          | MXG061                      | [3ff1cc3367](https://linux-hardware.org/?probe=3ff1cc3367) | Apr 07, 2022 |
| Dell          | Inspiron 11-3162            | [8c348f2f1a](https://linux-hardware.org/?probe=8c348f2f1a) | Apr 07, 2022 |
| HP            | Pavilion dv6500             | [2f18112668](https://linux-hardware.org/?probe=2f18112668) | Apr 04, 2022 |
| Wortmann      | M7x0S                       | [364f9cbe89](https://linux-hardware.org/?probe=364f9cbe89) | Apr 03, 2022 |
| MSI           | GX70 3CC                    | [0b706f83d3](https://linux-hardware.org/?probe=0b706f83d3) | Apr 02, 2022 |
| HP            | Pavilion 15                 | [98be421e4c](https://linux-hardware.org/?probe=98be421e4c) | Apr 02, 2022 |
| HP            | Laptop 15s-fq2xxx           | [c3dcb61dd5](https://linux-hardware.org/?probe=c3dcb61dd5) | Apr 02, 2022 |
| HP            | Laptop 15-ef2xxx            | [a245ae2e74](https://linux-hardware.org/?probe=a245ae2e74) | Mar 29, 2022 |
| Acer          | Aspire one                  | [2b0b231b1a](https://linux-hardware.org/?probe=2b0b231b1a) | Mar 29, 2022 |
| Medion        | Crawler E25                 | [6093396d8a](https://linux-hardware.org/?probe=6093396d8a) | Mar 28, 2022 |
| Dell          | Studio 1450                 | [1b7df0163d](https://linux-hardware.org/?probe=1b7df0163d) | Mar 28, 2022 |
| ASUSTek       | K55VD                       | [5c65461fe1](https://linux-hardware.org/?probe=5c65461fe1) | Mar 28, 2022 |
| Dell          | Vostro 3458                 | [a3cb323822](https://linux-hardware.org/?probe=a3cb323822) | Mar 27, 2022 |
| Dell          | Vostro 3458                 | [9e9df1f902](https://linux-hardware.org/?probe=9e9df1f902) | Mar 27, 2022 |
| Toshiba       | NB505                       | [cab0ce252d](https://linux-hardware.org/?probe=cab0ce252d) | Mar 27, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [5b371c14a6](https://linux-hardware.org/?probe=5b371c14a6) | Mar 25, 2022 |
| GPU Compan... | GWTC116-2                   | [2e6f1e1946](https://linux-hardware.org/?probe=2e6f1e1946) | Mar 25, 2022 |
| GPU Compan... | GWTC116-2                   | [897adf54cc](https://linux-hardware.org/?probe=897adf54cc) | Mar 24, 2022 |
| HP            | Stream 11 Pro G2 Noteboo... | [879788ce4f](https://linux-hardware.org/?probe=879788ce4f) | Mar 24, 2022 |
| ASUSTek       | U31SD                       | [00cff36d3f](https://linux-hardware.org/?probe=00cff36d3f) | Mar 24, 2022 |
| Dell          | Latitude E6400              | [49b4e17d7a](https://linux-hardware.org/?probe=49b4e17d7a) | Mar 22, 2022 |
| ASUSTek       | X501A                       | [5c8c010850](https://linux-hardware.org/?probe=5c8c010850) | Mar 22, 2022 |
| Dell          | Latitude 5510               | [d83be08c5d](https://linux-hardware.org/?probe=d83be08c5d) | Mar 21, 2022 |
| HP            | ZBook 15                    | [303748aa9e](https://linux-hardware.org/?probe=303748aa9e) | Mar 21, 2022 |
| HUAWEI        | KPL-W0X                     | [fbe7d7c6b0](https://linux-hardware.org/?probe=fbe7d7c6b0) | Mar 21, 2022 |
| Dell          | Latitude 7490               | [0799e0955b](https://linux-hardware.org/?probe=0799e0955b) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | [dd40ec296a](https://linux-hardware.org/?probe=dd40ec296a) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | [fb3591c2f8](https://linux-hardware.org/?probe=fb3591c2f8) | Mar 20, 2022 |
| Dell          | Latitude E6430              | [6503f89ca1](https://linux-hardware.org/?probe=6503f89ca1) | Mar 20, 2022 |
| Samsung       | R510/P510                   | [5ec1b197a4](https://linux-hardware.org/?probe=5ec1b197a4) | Mar 19, 2022 |
| Samsung       | R530/R730/R540              | [17c8c47d7b](https://linux-hardware.org/?probe=17c8c47d7b) | Mar 18, 2022 |
| ASUSTek       | U31SD                       | [63c0093cea](https://linux-hardware.org/?probe=63c0093cea) | Mar 18, 2022 |
| HP            | ZBook 15                    | [c5d326781a](https://linux-hardware.org/?probe=c5d326781a) | Mar 17, 2022 |
| Packard Be... | EasyNote TM85               | [ec7dd9aba3](https://linux-hardware.org/?probe=ec7dd9aba3) | Mar 17, 2022 |
| Toshiba       | NB205                       | [ffef19b228](https://linux-hardware.org/?probe=ffef19b228) | Mar 17, 2022 |
| Acer          | Nitro AN515-42              | [97ebb0ca74](https://linux-hardware.org/?probe=97ebb0ca74) | Mar 16, 2022 |
| Teclast       | F15 Plus                    | [9d3b8151f2](https://linux-hardware.org/?probe=9d3b8151f2) | Mar 16, 2022 |
| Acer          | Aspire 5935                 | [69cae65bf4](https://linux-hardware.org/?probe=69cae65bf4) | Mar 16, 2022 |
| Acer          | Aspire 5935                 | [67a1970f50](https://linux-hardware.org/?probe=67a1970f50) | Mar 16, 2022 |
| Dell          | Inspiron 7437               | [83eed6eaef](https://linux-hardware.org/?probe=83eed6eaef) | Mar 14, 2022 |
| Fujitsu Si... | AMILO Xi 3650               | [6f416ff93b](https://linux-hardware.org/?probe=6f416ff93b) | Mar 13, 2022 |
| HP            | Pavilion dv7                | [7cc5311803](https://linux-hardware.org/?probe=7cc5311803) | Mar 13, 2022 |
| HP            | EliteBook 2540p             | [d07352bf9a](https://linux-hardware.org/?probe=d07352bf9a) | Mar 12, 2022 |
| Dell          | Inspiron 7520               | [2e4bdb96fa](https://linux-hardware.org/?probe=2e4bdb96fa) | Mar 10, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [4f65353f3e](https://linux-hardware.org/?probe=4f65353f3e) | Mar 10, 2022 |
| Acer          | TP-SW5-012-16UW             | [1558c31a17](https://linux-hardware.org/?probe=1558c31a17) | Mar 09, 2022 |
| Dell          | Latitude E6400              | [bcacefe427](https://linux-hardware.org/?probe=bcacefe427) | Mar 08, 2022 |
| Packard Be... | EasyNote TM85               | [10c87bed94](https://linux-hardware.org/?probe=10c87bed94) | Mar 07, 2022 |
| Packard Be... | EasyNote TM85               | [2b3ba9a762](https://linux-hardware.org/?probe=2b3ba9a762) | Mar 07, 2022 |
| Dell          | Latitude E6400              | [4e626b238b](https://linux-hardware.org/?probe=4e626b238b) | Mar 07, 2022 |
| Acer          | Aspire VN7-572              | [952fd83515](https://linux-hardware.org/?probe=952fd83515) | Mar 06, 2022 |
| HP            | Pavilion dv7                | [97b2a4a508](https://linux-hardware.org/?probe=97b2a4a508) | Mar 05, 2022 |
| ASUSTek       | X555LAB                     | [80be8910f4](https://linux-hardware.org/?probe=80be8910f4) | Mar 05, 2022 |
| ASUSTek       | X450CC                      | [835313a116](https://linux-hardware.org/?probe=835313a116) | Mar 03, 2022 |
| HP            | Pavilion dv7                | [b32286ecad](https://linux-hardware.org/?probe=b32286ecad) | Mar 03, 2022 |
| Lenovo        | B590 20208                  | [4a4fd37e32](https://linux-hardware.org/?probe=4a4fd37e32) | Mar 02, 2022 |
| HP            | Notebook PC                 | [2297e2813f](https://linux-hardware.org/?probe=2297e2813f) | Mar 02, 2022 |
| HP            | Pavilion dv7                | [d3a9235dcb](https://linux-hardware.org/?probe=d3a9235dcb) | Mar 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [4fe25f775d](https://linux-hardware.org/?probe=4fe25f775d) | Mar 01, 2022 |
| Notebook      | PC5x_7xHP_HR_HS             | [d88405b0dc](https://linux-hardware.org/?probe=d88405b0dc) | Mar 01, 2022 |
| Lenovo        | ThinkPad X270 20HNS0LW00    | [c781fc668f](https://linux-hardware.org/?probe=c781fc668f) | Mar 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [1b5df98df2](https://linux-hardware.org/?probe=1b5df98df2) | Feb 28, 2022 |
| VIT           | P3400                       | [6075d8d8b2](https://linux-hardware.org/?probe=6075d8d8b2) | Feb 28, 2022 |
| Medion        | E16402                      | [1622ca8570](https://linux-hardware.org/?probe=1622ca8570) | Feb 27, 2022 |
| Lenovo        | ThinkPad T510 4384VJM       | [19e8d8425e](https://linux-hardware.org/?probe=19e8d8425e) | Feb 26, 2022 |
| HP            | EliteBook 8560p             | [d440e21050](https://linux-hardware.org/?probe=d440e21050) | Feb 26, 2022 |
| Lenovo        | Unknown                     | [8a5df3c23e](https://linux-hardware.org/?probe=8a5df3c23e) | Feb 25, 2022 |
| HP            | 15                          | [fa8d20b53f](https://linux-hardware.org/?probe=fa8d20b53f) | Feb 23, 2022 |
| Dell          | Vostro V130                 | [75b7360134](https://linux-hardware.org/?probe=75b7360134) | Feb 22, 2022 |
| Dell          | Precision 3561              | [d46fbe1d5f](https://linux-hardware.org/?probe=d46fbe1d5f) | Feb 21, 2022 |
| Lenovo        | ThinkPad T410 2522W6G       | [d2b007cb44](https://linux-hardware.org/?probe=d2b007cb44) | Feb 20, 2022 |
| Gateway       | M-6307                      | [7cda83b770](https://linux-hardware.org/?probe=7cda83b770) | Feb 20, 2022 |
| ASUSTek       | X542URR                     | [ee334867a0](https://linux-hardware.org/?probe=ee334867a0) | Feb 19, 2022 |
| Dell          | Inspiron 5593               | [f4bce4423f](https://linux-hardware.org/?probe=f4bce4423f) | Feb 19, 2022 |
| ASUSTek       | A2D                         | [6fbba6195d](https://linux-hardware.org/?probe=6fbba6195d) | Feb 17, 2022 |
| Lenovo        | ThinkPad R500 2716A54       | [9aa87e9270](https://linux-hardware.org/?probe=9aa87e9270) | Feb 17, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [354434e81d](https://linux-hardware.org/?probe=354434e81d) | Feb 16, 2022 |
| Dell          | Inspiron 1764               | [475df3f2af](https://linux-hardware.org/?probe=475df3f2af) | Feb 16, 2022 |
| Dell          | Inspiron 1764               | [177f5aac6c](https://linux-hardware.org/?probe=177f5aac6c) | Feb 16, 2022 |
| Sony          | VPCEB3E1E                   | [a0be8de519](https://linux-hardware.org/?probe=a0be8de519) | Feb 13, 2022 |
| HP            | Stream Notebook PC 13       | [33d5b7046b](https://linux-hardware.org/?probe=33d5b7046b) | Feb 13, 2022 |
| Samsung       | 900X1B                      | [c609dfc310](https://linux-hardware.org/?probe=c609dfc310) | Feb 13, 2022 |
| HP            | ProBook 655 G1              | [1c6a5c6e55](https://linux-hardware.org/?probe=1c6a5c6e55) | Feb 11, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [935de1698b](https://linux-hardware.org/?probe=935de1698b) | Feb 08, 2022 |
| HP            | ProBook 650 G3              | [54a5c321be](https://linux-hardware.org/?probe=54a5c321be) | Feb 08, 2022 |
| Acer          | TravelMate 8172             | [76e402e3d6](https://linux-hardware.org/?probe=76e402e3d6) | Feb 07, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [a2e027fa38](https://linux-hardware.org/?probe=a2e027fa38) | Feb 07, 2022 |
| ASUSTek       | K73SV                       | [d02cd235da](https://linux-hardware.org/?probe=d02cd235da) | Feb 06, 2022 |
| Acer          | Aspire 5100                 | [191eb6224a](https://linux-hardware.org/?probe=191eb6224a) | Feb 06, 2022 |
| IBM           | ThinkPad T43 2668BU7        | [2586bf5e87](https://linux-hardware.org/?probe=2586bf5e87) | Feb 06, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMD    | [801aa8fb1e](https://linux-hardware.org/?probe=801aa8fb1e) | Feb 05, 2022 |
| HP            | EliteBook 8530p             | [a2fc96b3dc](https://linux-hardware.org/?probe=a2fc96b3dc) | Feb 05, 2022 |
| Dell          | Latitude E5450              | [84845ef09c](https://linux-hardware.org/?probe=84845ef09c) | Feb 04, 2022 |
| HP            | Pavilion 17                 | [f0d4a99870](https://linux-hardware.org/?probe=f0d4a99870) | Feb 04, 2022 |
| Dell          | Latitude E5450              | [fc7d07dba8](https://linux-hardware.org/?probe=fc7d07dba8) | Feb 04, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | [9359d0a8af](https://linux-hardware.org/?probe=9359d0a8af) | Feb 04, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | [44efd2d456](https://linux-hardware.org/?probe=44efd2d456) | Feb 03, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | [2e33681926](https://linux-hardware.org/?probe=2e33681926) | Feb 03, 2022 |
| Fujitsu       | LIFEBOOK E734               | [28280d252b](https://linux-hardware.org/?probe=28280d252b) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bba0be98c7](https://linux-hardware.org/?probe=bba0be98c7) | Feb 01, 2022 |
| HP            | EliteBook 725 G2            | [d49dd26324](https://linux-hardware.org/?probe=d49dd26324) | Feb 01, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [460a295f83](https://linux-hardware.org/?probe=460a295f83) | Jan 30, 2022 |
| Gateway       | MT6831                      | [36947a389a](https://linux-hardware.org/?probe=36947a389a) | Jan 30, 2022 |
| HP            | EliteBook 745 G3            | [20e43b8b53](https://linux-hardware.org/?probe=20e43b8b53) | Jan 29, 2022 |
| Acer          | AOD257                      | [4d8476adb1](https://linux-hardware.org/?probe=4d8476adb1) | Jan 29, 2022 |
| ASUSTek       | TP500LA                     | [e18b673cd3](https://linux-hardware.org/?probe=e18b673cd3) | Jan 28, 2022 |
| Dell          | Latitude E6510              | [a571bdc501](https://linux-hardware.org/?probe=a571bdc501) | Jan 28, 2022 |
| Fujitsu       | LIFEBOOK E734               | [c969e228f3](https://linux-hardware.org/?probe=c969e228f3) | Jan 28, 2022 |
| Dell          | Studio 1450                 | [9c2bf5854d](https://linux-hardware.org/?probe=9c2bf5854d) | Jan 28, 2022 |
| Fujitsu       | LIFEBOOK E734               | [3e66e21a1e](https://linux-hardware.org/?probe=3e66e21a1e) | Jan 28, 2022 |
| Dell          | Latitude D630               | [8a0a5b89dd](https://linux-hardware.org/?probe=8a0a5b89dd) | Jan 27, 2022 |
| Dell          | Latitude D630               | [321264426f](https://linux-hardware.org/?probe=321264426f) | Jan 26, 2022 |
| ASUSTek       | N56VZ                       | [6f1b0cf9e0](https://linux-hardware.org/?probe=6f1b0cf9e0) | Jan 26, 2022 |
| HP            | G42                         | [3d3f5f2d07](https://linux-hardware.org/?probe=3d3f5f2d07) | Jan 25, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [e932911cde](https://linux-hardware.org/?probe=e932911cde) | Jan 25, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | [a97c44b274](https://linux-hardware.org/?probe=a97c44b274) | Jan 25, 2022 |
| MSI           | Prestige 15 A11SC           | [71a31ddfac](https://linux-hardware.org/?probe=71a31ddfac) | Jan 25, 2022 |
| Acer          | Aspire E5-575G              | [2c42aa1caf](https://linux-hardware.org/?probe=2c42aa1caf) | Jan 24, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [e0197893fc](https://linux-hardware.org/?probe=e0197893fc) | Jan 24, 2022 |
| HP            | G60                         | [acd0e22a1a](https://linux-hardware.org/?probe=acd0e22a1a) | Jan 23, 2022 |
| MSI           | U90/U100                    | [a87163f5ea](https://linux-hardware.org/?probe=a87163f5ea) | Jan 23, 2022 |
| Kogan         | KAL11C250SB                 | [ba3fd61313](https://linux-hardware.org/?probe=ba3fd61313) | Jan 23, 2022 |
| MSI           | MS-163B Ver                 | [2e2d0c47bd](https://linux-hardware.org/?probe=2e2d0c47bd) | Jan 23, 2022 |
| HP            | ProBook 440 G6              | [b7fb25920a](https://linux-hardware.org/?probe=b7fb25920a) | Jan 23, 2022 |
| MSI           | U90/U100                    | [a005adaf94](https://linux-hardware.org/?probe=a005adaf94) | Jan 23, 2022 |
| Dell          | XPS 13 9310                 | [75d4eef3ba](https://linux-hardware.org/?probe=75d4eef3ba) | Jan 22, 2022 |
| HP            | Laptop 17-ca1xxx            | [77545529dc](https://linux-hardware.org/?probe=77545529dc) | Jan 21, 2022 |
| Lenovo        | B590 37612MG                | [cc8d1271b0](https://linux-hardware.org/?probe=cc8d1271b0) | Jan 21, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SNC... | [0b0ddf4175](https://linux-hardware.org/?probe=0b0ddf4175) | Jan 21, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [6906b181eb](https://linux-hardware.org/?probe=6906b181eb) | Jan 20, 2022 |
| Dell          | Latitude E6330              | [c7b076f945](https://linux-hardware.org/?probe=c7b076f945) | Jan 20, 2022 |
| ASUSTek       | K50IJ                       | [262dcaf21e](https://linux-hardware.org/?probe=262dcaf21e) | Jan 18, 2022 |
| ASUSTek       | K50IJ                       | [5187874180](https://linux-hardware.org/?probe=5187874180) | Jan 18, 2022 |
| HP            | 255 G8 Notebook PC          | [c1f8df4bbd](https://linux-hardware.org/?probe=c1f8df4bbd) | Jan 18, 2022 |
| Dell          | Latitude D630               | [6327eec09e](https://linux-hardware.org/?probe=6327eec09e) | Jan 18, 2022 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [3b8acf9181](https://linux-hardware.org/?probe=3b8acf9181) | Jan 17, 2022 |
| Lenovo        | ThinkPad W520 42844MG       | [cf460c52bb](https://linux-hardware.org/?probe=cf460c52bb) | Jan 16, 2022 |
| Lenovo        | ThinkPad X260 20F5S22K0Z    | [e83aec04ca](https://linux-hardware.org/?probe=e83aec04ca) | Jan 16, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [d735255913](https://linux-hardware.org/?probe=d735255913) | Jan 15, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [7edf924514](https://linux-hardware.org/?probe=7edf924514) | Jan 15, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [347317645d](https://linux-hardware.org/?probe=347317645d) | Jan 15, 2022 |
| Insyde        | Braswell                    | [a5bca1e5e8](https://linux-hardware.org/?probe=a5bca1e5e8) | Jan 14, 2022 |
| Dell          | Latitude 5480               | [d95c781c2e](https://linux-hardware.org/?probe=d95c781c2e) | Jan 14, 2022 |
| Dell          | Latitude 5480               | [d58108295c](https://linux-hardware.org/?probe=d58108295c) | Jan 14, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [e293ddf5fc](https://linux-hardware.org/?probe=e293ddf5fc) | Jan 14, 2022 |
| Dell          | Latitude D620               | [a43c35d2fa](https://linux-hardware.org/?probe=a43c35d2fa) | Jan 14, 2022 |
| ASUSTek       | 1015CX                      | [e682cee335](https://linux-hardware.org/?probe=e682cee335) | Jan 13, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [6892ab87e1](https://linux-hardware.org/?probe=6892ab87e1) | Jan 13, 2022 |
| Medion        | Akoya THE TOUCH 10          | [7606a573d6](https://linux-hardware.org/?probe=7606a573d6) | Jan 12, 2022 |
| Dell          | Inspiron 7520               | [e433dbb39d](https://linux-hardware.org/?probe=e433dbb39d) | Jan 12, 2022 |
| Google        | Auron_Yuna                  | [9ccb52f9b4](https://linux-hardware.org/?probe=9ccb52f9b4) | Jan 11, 2022 |
| Lenovo        | IdeaPad S415 Touch 20319    | [d59706fc52](https://linux-hardware.org/?probe=d59706fc52) | Jan 11, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [b673072fbb](https://linux-hardware.org/?probe=b673072fbb) | Jan 11, 2022 |
| ASUSTek       | K53SC                       | [b01004055c](https://linux-hardware.org/?probe=b01004055c) | Jan 11, 2022 |
| MOTION        | KEX00                       | [8e36590e72](https://linux-hardware.org/?probe=8e36590e72) | Jan 10, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | [bbcda99dab](https://linux-hardware.org/?probe=bbcda99dab) | Jan 10, 2022 |
| Fujitsu Si... | AMILO PRO V3515             | [d537e0bc35](https://linux-hardware.org/?probe=d537e0bc35) | Jan 09, 2022 |
| Fujitsu Si... | AMILO PRO V3515             | [4bfe339a98](https://linux-hardware.org/?probe=4bfe339a98) | Jan 09, 2022 |
| Alienware     | m15 R3                      | [8cff8c6d3f](https://linux-hardware.org/?probe=8cff8c6d3f) | Jan 09, 2022 |
| Acer          | Extensa 5620                | [41a1c7001c](https://linux-hardware.org/?probe=41a1c7001c) | Jan 08, 2022 |
| Sony          | SVF15A190X                  | [6d729a76af](https://linux-hardware.org/?probe=6d729a76af) | Jan 08, 2022 |
| Dell          | Latitude E6500              | [8355df56a3](https://linux-hardware.org/?probe=8355df56a3) | Jan 07, 2022 |
| Gateway       | NV53A                       | [2e67e3a86e](https://linux-hardware.org/?probe=2e67e3a86e) | Jan 05, 2022 |
| HP            | ProBook 640 G1              | [a7f4591b40](https://linux-hardware.org/?probe=a7f4591b40) | Jan 05, 2022 |
| ASUSTek       | N550JV                      | [aefb321446](https://linux-hardware.org/?probe=aefb321446) | Jan 04, 2022 |
| Dell          | Latitude E5440              | [16fbe4c9c0](https://linux-hardware.org/?probe=16fbe4c9c0) | Jan 03, 2022 |
| HP            | Pavilion dv6000 (GH912EA... | [a41f8d2d74](https://linux-hardware.org/?probe=a41f8d2d74) | Jan 03, 2022 |
| Packard Be... | EasyNote TK87               | [a551958cb8](https://linux-hardware.org/?probe=a551958cb8) | Jan 01, 2022 |
| Dell          | Inspiron N5030              | [127df37eab](https://linux-hardware.org/?probe=127df37eab) | Jan 01, 2022 |
| HP            | G60                         | [08350a2b75](https://linux-hardware.org/?probe=08350a2b75) | Jan 01, 2022 |
| Dell          | Inspiron N5030              | [fc6d58d758](https://linux-hardware.org/?probe=fc6d58d758) | Jan 01, 2022 |
| Dell          | Inspiron 5765               | [c3a91857b3](https://linux-hardware.org/?probe=c3a91857b3) | Jan 01, 2022 |
| ASUSTek       | 1001PX                      | [a175657549](https://linux-hardware.org/?probe=a175657549) | Dec 31, 2021 |
| Intel         | Crestline & ICH8M Chipse... | [286566a874](https://linux-hardware.org/?probe=286566a874) | Dec 31, 2021 |
| ASUSTek       | 1001PX                      | [48423d0bef](https://linux-hardware.org/?probe=48423d0bef) | Dec 31, 2021 |
| HP            | Laptop 17-cp0xxx            | [596bdeff81](https://linux-hardware.org/?probe=596bdeff81) | Dec 27, 2021 |
| HP            | EliteBook 8440p (VD484AV... | [ba4cf422e7](https://linux-hardware.org/?probe=ba4cf422e7) | Dec 27, 2021 |
| Toshiba       | Satellite C50-A-19U         | [6a61931dde](https://linux-hardware.org/?probe=6a61931dde) | Dec 26, 2021 |
| Acer          | Aspire A515-54G             | [00c1f1b6df](https://linux-hardware.org/?probe=00c1f1b6df) | Dec 26, 2021 |
| Lenovo        | ThinkPad X61 7674CT0        | [25a59e69c1](https://linux-hardware.org/?probe=25a59e69c1) | Dec 25, 2021 |
| Lenovo        | ThinkPad X61 7674CT0        | [a5b0d0a06a](https://linux-hardware.org/?probe=a5b0d0a06a) | Dec 25, 2021 |
| MSI           | GP76 Leopard 11UG           | [a14e38d07e](https://linux-hardware.org/?probe=a14e38d07e) | Dec 24, 2021 |
| GPU Compan... | GWTN156-11                  | [2ef30c62b5](https://linux-hardware.org/?probe=2ef30c62b5) | Dec 24, 2021 |
| Google        | Swanky                      | [7c19406756](https://linux-hardware.org/?probe=7c19406756) | Dec 24, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [6eec25d058](https://linux-hardware.org/?probe=6eec25d058) | Dec 24, 2021 |
| HP            | Pavilion dv7                | [3b47550de1](https://linux-hardware.org/?probe=3b47550de1) | Dec 23, 2021 |
| Acer          | Swift SF114-34              | [7178bccf8f](https://linux-hardware.org/?probe=7178bccf8f) | Dec 22, 2021 |
| HP            | Laptop 17-cn1xxx            | [c26a2c5c03](https://linux-hardware.org/?probe=c26a2c5c03) | Dec 22, 2021 |
| Samsung       | RC410/RC510/RC710           | [123bdbfa71](https://linux-hardware.org/?probe=123bdbfa71) | Dec 22, 2021 |
| Google        | Nami                        | [045f17f15d](https://linux-hardware.org/?probe=045f17f15d) | Dec 22, 2021 |
| HP            | Compaq Mini 311-1100        | [d1aaa6b464](https://linux-hardware.org/?probe=d1aaa6b464) | Dec 21, 2021 |
| Google        | Kefka                       | [4bd83691fd](https://linux-hardware.org/?probe=4bd83691fd) | Dec 20, 2021 |
| HP            | Laptop 17-cn1xxx            | [e3c5530718](https://linux-hardware.org/?probe=e3c5530718) | Dec 19, 2021 |
| Acer          | Swift SF314-43              | [1f0d544a85](https://linux-hardware.org/?probe=1f0d544a85) | Dec 18, 2021 |
| ASUSTek       | E200HA                      | [bcd4913896](https://linux-hardware.org/?probe=bcd4913896) | Dec 17, 2021 |
| Gateway       | MT6831                      | [3df425d68b](https://linux-hardware.org/?probe=3df425d68b) | Dec 17, 2021 |
| Lenovo        | B50-30 20382                | [7c3c9b5cdd](https://linux-hardware.org/?probe=7c3c9b5cdd) | Dec 17, 2021 |
| Dell          | System XPS L502X            | [4588c107ed](https://linux-hardware.org/?probe=4588c107ed) | Dec 16, 2021 |
| Packard Be... | EasyNote TK13BZ             | [e08d4e940c](https://linux-hardware.org/?probe=e08d4e940c) | Dec 15, 2021 |
| Toshiba       | Satellite A105              | [4bddc587d8](https://linux-hardware.org/?probe=4bddc587d8) | Dec 15, 2021 |
| Lenovo        | ThinkPad T530 24296JG       | [e8d6ff471a](https://linux-hardware.org/?probe=e8d6ff471a) | Dec 15, 2021 |
| Acer          | Aspire one                  | [32fd744f46](https://linux-hardware.org/?probe=32fd744f46) | Dec 14, 2021 |
| Gateway       | NV53A                       | [1912b6b8c5](https://linux-hardware.org/?probe=1912b6b8c5) | Dec 14, 2021 |
| ASUSTek       | X55U                        | [6260fe5ca9](https://linux-hardware.org/?probe=6260fe5ca9) | Dec 13, 2021 |
| Sony          | VGN-SZ2HP_B                 | [a5d51adfab](https://linux-hardware.org/?probe=a5d51adfab) | Dec 13, 2021 |
| HP            | Pavilion TS 11              | [1617abd2f4](https://linux-hardware.org/?probe=1617abd2f4) | Dec 12, 2021 |
| Dell          | Inspiron 13-5378            | [22b04adc28](https://linux-hardware.org/?probe=22b04adc28) | Dec 12, 2021 |
| Dell          | Inspiron 7501               | [25566e4f44](https://linux-hardware.org/?probe=25566e4f44) | Dec 11, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [9e861e7f7d](https://linux-hardware.org/?probe=9e861e7f7d) | Dec 11, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [615e44dbe8](https://linux-hardware.org/?probe=615e44dbe8) | Dec 11, 2021 |
| Dell          | Inspiron 7501               | [9d9b833c3a](https://linux-hardware.org/?probe=9d9b833c3a) | Dec 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [204f77ca68](https://linux-hardware.org/?probe=204f77ca68) | Dec 10, 2021 |
| Lenovo        | ThinkPad T61 64669YG        | [f0c57ccd03](https://linux-hardware.org/?probe=f0c57ccd03) | Dec 10, 2021 |
| HP            | ProBook 450 G4              | [9fb3716320](https://linux-hardware.org/?probe=9fb3716320) | Dec 10, 2021 |
| HP            | EliteBook Folio 9470m       | [c505dc1521](https://linux-hardware.org/?probe=c505dc1521) | Dec 09, 2021 |
| HUAWEI        | HKD-WXX                     | [2e235ec353](https://linux-hardware.org/?probe=2e235ec353) | Dec 09, 2021 |
| Lenovo        | ThinkPad T510 4384A78       | [2c5d450c67](https://linux-hardware.org/?probe=2c5d450c67) | Dec 08, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [269cb5f1c1](https://linux-hardware.org/?probe=269cb5f1c1) | Dec 08, 2021 |
| HP            | Pavilion dv6                | [479a9e57d5](https://linux-hardware.org/?probe=479a9e57d5) | Dec 07, 2021 |
| HP            | Pavilion dv6                | [98ad56ddcc](https://linux-hardware.org/?probe=98ad56ddcc) | Dec 07, 2021 |
| Toshiba       | Satellite A105              | [25a235745d](https://linux-hardware.org/?probe=25a235745d) | Dec 07, 2021 |
| Toshiba       | Satellite A105              | [8b638d983f](https://linux-hardware.org/?probe=8b638d983f) | Dec 07, 2021 |
| Acer          | Aspire 5336                 | [ce9d41eb2f](https://linux-hardware.org/?probe=ce9d41eb2f) | Dec 06, 2021 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [c4263a27a5](https://linux-hardware.org/?probe=c4263a27a5) | Dec 05, 2021 |
| Acer          | Aspire A315-34              | [b4382c3b38](https://linux-hardware.org/?probe=b4382c3b38) | Dec 04, 2021 |
| Acer          | Aspire A315-34              | [bc211e09fd](https://linux-hardware.org/?probe=bc211e09fd) | Dec 04, 2021 |
| Dixonsxp      | Unknown                     | [9f1502866b](https://linux-hardware.org/?probe=9f1502866b) | Dec 03, 2021 |
| Dixonsxp      | Unknown                     | [093fef7eaa](https://linux-hardware.org/?probe=093fef7eaa) | Dec 03, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [674712f2a1](https://linux-hardware.org/?probe=674712f2a1) | Dec 03, 2021 |
| Toshiba       | Satellite L870-196          | [15ed850b16](https://linux-hardware.org/?probe=15ed850b16) | Dec 02, 2021 |
| Dell          | Latitude 5401               | [796c461b16](https://linux-hardware.org/?probe=796c461b16) | Dec 01, 2021 |
| HP            | 2000                        | [f16b490828](https://linux-hardware.org/?probe=f16b490828) | Dec 01, 2021 |
| Acer          | Aspire 5630                 | [90453b887a](https://linux-hardware.org/?probe=90453b887a) | Dec 01, 2021 |
| ASUSTek       | E203NAS                     | [c400f4df81](https://linux-hardware.org/?probe=c400f4df81) | Nov 30, 2021 |
| MSI           | Alpha 17 A4DEK              | [6a72e44cf5](https://linux-hardware.org/?probe=6a72e44cf5) | Nov 29, 2021 |
| ASUSTek       | 1015CX                      | [d1c7a213b8](https://linux-hardware.org/?probe=d1c7a213b8) | Nov 29, 2021 |
| Samsung       | R530/R730/P590              | [0bbf67316b](https://linux-hardware.org/?probe=0bbf67316b) | Nov 28, 2021 |
| Acer          | Swift SF114-34              | [d0170808b3](https://linux-hardware.org/?probe=d0170808b3) | Nov 27, 2021 |
| HP            | ProBook 4310s               | [6d339b7843](https://linux-hardware.org/?probe=6d339b7843) | Nov 27, 2021 |
| Dell          | Inspiron N5030              | [6ddb7fee36](https://linux-hardware.org/?probe=6ddb7fee36) | Nov 26, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [71d58a102c](https://linux-hardware.org/?probe=71d58a102c) | Nov 26, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [d9b3bd7851](https://linux-hardware.org/?probe=d9b3bd7851) | Nov 26, 2021 |
| MSI           | MS-1034                     | [bbf051d81a](https://linux-hardware.org/?probe=bbf051d81a) | Nov 26, 2021 |
| Lenovo        | IdeaPad Y570 0862           | [c795d5132c](https://linux-hardware.org/?probe=c795d5132c) | Nov 26, 2021 |
| HP            | Laptop 17-ak0xx             | [176f69ab48](https://linux-hardware.org/?probe=176f69ab48) | Nov 25, 2021 |
| HP            | ProBook 640 G1              | [311cb04cc5](https://linux-hardware.org/?probe=311cb04cc5) | Nov 25, 2021 |
| HP            | Pavilion 17                 | [43944b4f78](https://linux-hardware.org/?probe=43944b4f78) | Nov 24, 2021 |
| HP            | Pavilion dv9700             | [5a583ec569](https://linux-hardware.org/?probe=5a583ec569) | Nov 24, 2021 |
| Lenovo        | ThinkPad R61 77331CU        | [28380a5079](https://linux-hardware.org/?probe=28380a5079) | Nov 23, 2021 |
| ASUSTek       | X51RL                       | [4ec59d2453](https://linux-hardware.org/?probe=4ec59d2453) | Nov 22, 2021 |
| Dell          | XPS 13 9333                 | [faf93e292c](https://linux-hardware.org/?probe=faf93e292c) | Nov 22, 2021 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [898f3db0ed](https://linux-hardware.org/?probe=898f3db0ed) | Nov 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [39d84bdde8](https://linux-hardware.org/?probe=39d84bdde8) | Nov 22, 2021 |
| Alienware     | M17x                        | [13acf7a3f9](https://linux-hardware.org/?probe=13acf7a3f9) | Nov 22, 2021 |
| Lenovo        | Edge 15 80K9                | [65a59cf71c](https://linux-hardware.org/?probe=65a59cf71c) | Nov 22, 2021 |
| Lenovo        | Edge 15 80K9                | [55d87b9d59](https://linux-hardware.org/?probe=55d87b9d59) | Nov 22, 2021 |
| HP            | EliteBook 835 G7 Noteboo... | [cdf3297bef](https://linux-hardware.org/?probe=cdf3297bef) | Nov 21, 2021 |
| Unknown       | Unknown                     | [81e2289408](https://linux-hardware.org/?probe=81e2289408) | Nov 21, 2021 |
| HP            | ProBook 640 G1              | [b75a64f96a](https://linux-hardware.org/?probe=b75a64f96a) | Nov 19, 2021 |
| Lenovo        | ThinkPad T61 766511G        | [e1c74cc580](https://linux-hardware.org/?probe=e1c74cc580) | Nov 19, 2021 |
| HP            | ProBook 650 G3              | [def83e3614](https://linux-hardware.org/?probe=def83e3614) | Nov 19, 2021 |
| MSI           | GT75VR 7RE                  | [02a0e2b5c8](https://linux-hardware.org/?probe=02a0e2b5c8) | Nov 19, 2021 |
| ONE-NETBOO... | A1                          | [aff2f60770](https://linux-hardware.org/?probe=aff2f60770) | Nov 19, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [dfba89a8f0](https://linux-hardware.org/?probe=dfba89a8f0) | Nov 17, 2021 |
| HP            | Pavilion dv9700             | [2d4636d0ee](https://linux-hardware.org/?probe=2d4636d0ee) | Nov 17, 2021 |
| HP            | Pavilion dv9700             | [e5da3884b4](https://linux-hardware.org/?probe=e5da3884b4) | Nov 17, 2021 |
| Dell          | Latitude 7370               | [b43fadb11c](https://linux-hardware.org/?probe=b43fadb11c) | Nov 16, 2021 |
| Dell          | XPS 13 9370                 | [343fdf2e23](https://linux-hardware.org/?probe=343fdf2e23) | Nov 16, 2021 |
| HP            | Compaq 6710b (RM405UT#AB... | [f758717e6b](https://linux-hardware.org/?probe=f758717e6b) | Nov 14, 2021 |
| Apple         | MacBookPro8,1               | [ea402fa75e](https://linux-hardware.org/?probe=ea402fa75e) | Nov 14, 2021 |
| HP            | Compaq 6710b (RM405UT#AB... | [547c6f47b2](https://linux-hardware.org/?probe=547c6f47b2) | Nov 13, 2021 |
| Dell          | Latitude E6430              | [16f005fd2b](https://linux-hardware.org/?probe=16f005fd2b) | Nov 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [78651b05bb](https://linux-hardware.org/?probe=78651b05bb) | Nov 13, 2021 |
| ASUSTek       | 1002HA                      | [2eb3d438b2](https://linux-hardware.org/?probe=2eb3d438b2) | Nov 12, 2021 |
| HP            | Pavilion TS 11              | [746f0808f4](https://linux-hardware.org/?probe=746f0808f4) | Nov 12, 2021 |
| Dell          | G15 5510                    | [178497a15b](https://linux-hardware.org/?probe=178497a15b) | Nov 12, 2021 |
| Dell          | Inspiron N5030              | [04def67913](https://linux-hardware.org/?probe=04def67913) | Nov 12, 2021 |
| Google        | Terra                       | [d80b98949e](https://linux-hardware.org/?probe=d80b98949e) | Nov 12, 2021 |
| ASUSTek       | X501A                       | [f1eb057027](https://linux-hardware.org/?probe=f1eb057027) | Nov 11, 2021 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [f168acafa4](https://linux-hardware.org/?probe=f168acafa4) | Nov 10, 2021 |
| HP            | ZBook 15 G3                 | [3e94ac7df1](https://linux-hardware.org/?probe=3e94ac7df1) | Nov 09, 2021 |
| Lenovo        | ThinkPad T410 2537MT3       | [76965c829b](https://linux-hardware.org/?probe=76965c829b) | Nov 09, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [6d3d2766f2](https://linux-hardware.org/?probe=6d3d2766f2) | Nov 09, 2021 |
| Sony          | VPCF13M1E                   | [9858905cc2](https://linux-hardware.org/?probe=9858905cc2) | Nov 09, 2021 |
| ASUSTek       | ROG Strix G531GT_GL531GT    | [685c3c0f3f](https://linux-hardware.org/?probe=685c3c0f3f) | Nov 08, 2021 |
| HP            | Compaq nc6320 (RH374EA#A... | [a67ec35b48](https://linux-hardware.org/?probe=a67ec35b48) | Nov 08, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [81237c05f7](https://linux-hardware.org/?probe=81237c05f7) | Nov 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [d7a0b05df7](https://linux-hardware.org/?probe=d7a0b05df7) | Nov 07, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [cd1647c038](https://linux-hardware.org/?probe=cd1647c038) | Nov 07, 2021 |
| Dell          | XPS 15 7590                 | [53cfd83c43](https://linux-hardware.org/?probe=53cfd83c43) | Nov 07, 2021 |
| System76      | Oryx Pro                    | [39d1d14e62](https://linux-hardware.org/?probe=39d1d14e62) | Nov 07, 2021 |
| HP            | Pavilion g6                 | [ed14748445](https://linux-hardware.org/?probe=ed14748445) | Nov 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [b4c93f107b](https://linux-hardware.org/?probe=b4c93f107b) | Nov 07, 2021 |
| HP            | Notebook                    | [9334c94844](https://linux-hardware.org/?probe=9334c94844) | Nov 07, 2021 |
| Dell          | G3 3500                     | [acc14d7efc](https://linux-hardware.org/?probe=acc14d7efc) | Nov 07, 2021 |
| Dell          | Precision M4600             | [acd5115099](https://linux-hardware.org/?probe=acd5115099) | Nov 06, 2021 |
| MSI           | GL63 8RC                    | [068ed7518b](https://linux-hardware.org/?probe=068ed7518b) | Nov 06, 2021 |
| Dell          | G3 3500                     | [ea3cdd3cc4](https://linux-hardware.org/?probe=ea3cdd3cc4) | Nov 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [617d2f5444](https://linux-hardware.org/?probe=617d2f5444) | Nov 06, 2021 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [305cca4bc8](https://linux-hardware.org/?probe=305cca4bc8) | Nov 06, 2021 |
| MAXDATA       | ECO4000IW                   | [090bbdeb4a](https://linux-hardware.org/?probe=090bbdeb4a) | Nov 06, 2021 |
| ASUSTek       | E402SA                      | [345438c3cd](https://linux-hardware.org/?probe=345438c3cd) | Nov 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0c1490178d](https://linux-hardware.org/?probe=0c1490178d) | Nov 06, 2021 |
| Acer          | Nitro AN715-52              | [d7fe8595a3](https://linux-hardware.org/?probe=d7fe8595a3) | Nov 05, 2021 |
| HP            | Compaq nc6320 (RH374EA#A... | [91c9beef79](https://linux-hardware.org/?probe=91c9beef79) | Nov 05, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [9d85113feb](https://linux-hardware.org/?probe=9d85113feb) | Nov 05, 2021 |
| Dell          | Inspiron 7501               | [3690315342](https://linux-hardware.org/?probe=3690315342) | Nov 05, 2021 |
| HP            | Pavilion dv6                | [dcd2956978](https://linux-hardware.org/?probe=dcd2956978) | Nov 05, 2021 |
| HP            | Pavilion dv6                | [a509e62c95](https://linux-hardware.org/?probe=a509e62c95) | Nov 05, 2021 |
| Acer          | Nitro AN515-54              | [8859c97474](https://linux-hardware.org/?probe=8859c97474) | Nov 05, 2021 |
| Toshiba       | Satellite P745              | [59b3468fb9](https://linux-hardware.org/?probe=59b3468fb9) | Nov 04, 2021 |
| HP            | ProBook 6450b               | [603fac0b2e](https://linux-hardware.org/?probe=603fac0b2e) | Nov 04, 2021 |
| Dell          | Latitude D630               | [f212896c99](https://linux-hardware.org/?probe=f212896c99) | Nov 04, 2021 |
| Dell          | Precision M4600             | [155f9ec4f4](https://linux-hardware.org/?probe=155f9ec4f4) | Nov 04, 2021 |
| Toshiba       | Satellite C70D-B            | [9fd353eaff](https://linux-hardware.org/?probe=9fd353eaff) | Nov 04, 2021 |
| ASUSTek       | T100TA                      | [fa6b87b50d](https://linux-hardware.org/?probe=fa6b87b50d) | Nov 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [070b533b05](https://linux-hardware.org/?probe=070b533b05) | Nov 02, 2021 |
| HP            | Compaq Presario CQ61        | [86dd6331fc](https://linux-hardware.org/?probe=86dd6331fc) | Nov 02, 2021 |
| HP            | Pavilion TS 11              | [29af280c0e](https://linux-hardware.org/?probe=29af280c0e) | Nov 01, 2021 |
| ASUSTek       | P2540UA                     | [f10ce209c4](https://linux-hardware.org/?probe=f10ce209c4) | Nov 01, 2021 |
| ASUSTek       | GL553VE                     | [22b5b29b32](https://linux-hardware.org/?probe=22b5b29b32) | Nov 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [c1965ee087](https://linux-hardware.org/?probe=c1965ee087) | Nov 01, 2021 |
| MSI           | GL63 8RC                    | [ad6c3506c1](https://linux-hardware.org/?probe=ad6c3506c1) | Nov 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [22728e37fe](https://linux-hardware.org/?probe=22728e37fe) | Oct 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [68a5bdc18a](https://linux-hardware.org/?probe=68a5bdc18a) | Oct 31, 2021 |
| Dell          | Precision M4600             | [f442df91a1](https://linux-hardware.org/?probe=f442df91a1) | Oct 31, 2021 |
| ASUSTek       | X756UX                      | [2f027fcbc2](https://linux-hardware.org/?probe=2f027fcbc2) | Oct 30, 2021 |
| VIT           | P3400                       | [58cc91aba3](https://linux-hardware.org/?probe=58cc91aba3) | Oct 30, 2021 |
| Toshiba       | Satellite P55W-C            | [8d16328dfd](https://linux-hardware.org/?probe=8d16328dfd) | Oct 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [48434e75fb](https://linux-hardware.org/?probe=48434e75fb) | Oct 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [13addb7994](https://linux-hardware.org/?probe=13addb7994) | Oct 28, 2021 |
| Lenovo        | ThinkPad W510 431963G       | [5ce9661292](https://linux-hardware.org/?probe=5ce9661292) | Oct 28, 2021 |
| MSI           | MS-1034                     | [f1770353a3](https://linux-hardware.org/?probe=f1770353a3) | Oct 28, 2021 |
| HP            | Compaq 6730s                | [8bc4483616](https://linux-hardware.org/?probe=8bc4483616) | Oct 27, 2021 |
| HP            | Pavilion g4                 | [90f6743fbd](https://linux-hardware.org/?probe=90f6743fbd) | Oct 27, 2021 |
| ASUSTek       | X501A                       | [2e47dd4121](https://linux-hardware.org/?probe=2e47dd4121) | Oct 27, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [2c2443341f](https://linux-hardware.org/?probe=2c2443341f) | Oct 27, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [406fcb6975](https://linux-hardware.org/?probe=406fcb6975) | Oct 27, 2021 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [16306ffb37](https://linux-hardware.org/?probe=16306ffb37) | Oct 25, 2021 |
| HUAWEI        | KLVL-WXX9                   | [336d9d575f](https://linux-hardware.org/?probe=336d9d575f) | Oct 25, 2021 |
| Toshiba       | Satellite L850              | [066f99ecbc](https://linux-hardware.org/?probe=066f99ecbc) | Oct 25, 2021 |
| Alienware     | m17 R4                      | [5c569c3982](https://linux-hardware.org/?probe=5c569c3982) | Oct 24, 2021 |
| HP            | Compaq 6730s                | [587b440ce4](https://linux-hardware.org/?probe=587b440ce4) | Oct 24, 2021 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | [68f1525bef](https://linux-hardware.org/?probe=68f1525bef) | Oct 23, 2021 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | [1146299277](https://linux-hardware.org/?probe=1146299277) | Oct 23, 2021 |
| HP            | Compaq Presario CQ61        | [cb8b850048](https://linux-hardware.org/?probe=cb8b850048) | Oct 23, 2021 |
| Sony          | VGN-NR11Z_T                 | [f76ae4b159](https://linux-hardware.org/?probe=f76ae4b159) | Oct 22, 2021 |
| HP            | kip                         | [18f48f3a5b](https://linux-hardware.org/?probe=18f48f3a5b) | Oct 22, 2021 |
| Lenovo        | ThinkPad W510 431963G       | [ba467258aa](https://linux-hardware.org/?probe=ba467258aa) | Oct 21, 2021 |
| HP            | Notebook                    | [fb90bf9dc7](https://linux-hardware.org/?probe=fb90bf9dc7) | Oct 21, 2021 |
| Lenovo        | ThinkPad T420 4180AP3       | [6be3808b94](https://linux-hardware.org/?probe=6be3808b94) | Oct 21, 2021 |
| Lenovo        | IdeaPad U550 20034,3749     | [3bbec8b8fd](https://linux-hardware.org/?probe=3bbec8b8fd) | Oct 21, 2021 |
| Toshiba       | Satellite Pro C850-1G8      | [8ad9f2f898](https://linux-hardware.org/?probe=8ad9f2f898) | Oct 20, 2021 |
| Apple         | MacBookPro11,1              | [7fb2681427](https://linux-hardware.org/?probe=7fb2681427) | Oct 20, 2021 |
| Lenovo        | B5400 s20278Q               | [c71ca98310](https://linux-hardware.org/?probe=c71ca98310) | Oct 19, 2021 |
| Lenovo        | ThinkPad T510 4384A78       | [a2aee507a3](https://linux-hardware.org/?probe=a2aee507a3) | Oct 19, 2021 |
| Lenovo        | ThinkPad T510 4384A78       | [5a3e03b67e](https://linux-hardware.org/?probe=5a3e03b67e) | Oct 19, 2021 |
| Samsung       | R530/R730/P590              | [e76e147759](https://linux-hardware.org/?probe=e76e147759) | Oct 19, 2021 |
| Lenovo        | B50-30 20382                | [235b6e8d1a](https://linux-hardware.org/?probe=235b6e8d1a) | Oct 18, 2021 |
| Acer          | Extensa 5630                | [4823b348aa](https://linux-hardware.org/?probe=4823b348aa) | Oct 18, 2021 |
| Dell          | Inspiron 3537               | [255aca010b](https://linux-hardware.org/?probe=255aca010b) | Oct 18, 2021 |
| Dell          | Latitude E6440              | [640d2341de](https://linux-hardware.org/?probe=640d2341de) | Oct 17, 2021 |
| HP            | 255 G7 Notebook PC          | [28930b356e](https://linux-hardware.org/?probe=28930b356e) | Oct 16, 2021 |
| Acer          | Aspire 4738Z                | [8962990035](https://linux-hardware.org/?probe=8962990035) | Oct 16, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [b9218a0347](https://linux-hardware.org/?probe=b9218a0347) | Oct 15, 2021 |
| Acer          | Aspire 5750                 | [ff12aa7481](https://linux-hardware.org/?probe=ff12aa7481) | Oct 15, 2021 |
| Dell          | XPS L521X                   | [5026df6496](https://linux-hardware.org/?probe=5026df6496) | Oct 15, 2021 |
| HP            | Mini 110-3000               | [ee2ce4e3b9](https://linux-hardware.org/?probe=ee2ce4e3b9) | Oct 14, 2021 |
| Toshiba       | Satellite A100              | [ef126ad790](https://linux-hardware.org/?probe=ef126ad790) | Oct 13, 2021 |
| Samsung       | 550XCJ/550XCR               | [125473d905](https://linux-hardware.org/?probe=125473d905) | Oct 13, 2021 |
| Dell          | Latitude D630               | [f931dcd89d](https://linux-hardware.org/?probe=f931dcd89d) | Oct 13, 2021 |
| Dell          | Latitude D630               | [328ae0eccc](https://linux-hardware.org/?probe=328ae0eccc) | Oct 13, 2021 |
| HP            | OMEN by Laptop              | [6163de66f1](https://linux-hardware.org/?probe=6163de66f1) | Oct 12, 2021 |
| eMachines     | G730                        | [b24afe5dc2](https://linux-hardware.org/?probe=b24afe5dc2) | Oct 12, 2021 |
| HP            | ProBook 650 G4              | [ea1c62ead1](https://linux-hardware.org/?probe=ea1c62ead1) | Oct 12, 2021 |
| Dell          | Latitude 7370               | [348b718b2b](https://linux-hardware.org/?probe=348b718b2b) | Oct 11, 2021 |
| HP            | Notebook                    | [732cc33a53](https://linux-hardware.org/?probe=732cc33a53) | Oct 11, 2021 |
| Lenovo        | ThinkPad T60 1952W97        | [17678957ea](https://linux-hardware.org/?probe=17678957ea) | Oct 11, 2021 |
| HP            | Compaq 6730s                | [9b21d843cd](https://linux-hardware.org/?probe=9b21d843cd) | Oct 10, 2021 |
| LG Electro... | R710-S.APSAG                | [07b311caef](https://linux-hardware.org/?probe=07b311caef) | Oct 09, 2021 |
| Sony          | VGN-N11M_W                  | [7a0e2dfd11](https://linux-hardware.org/?probe=7a0e2dfd11) | Oct 09, 2021 |
| Dell          | Precision 5540              | [b59369e8e7](https://linux-hardware.org/?probe=b59369e8e7) | Oct 08, 2021 |
| Multilaser    | UB32X                       | [e5e22df913](https://linux-hardware.org/?probe=e5e22df913) | Oct 08, 2021 |
| HP            | Compaq 6720s                | [36a9fc9a39](https://linux-hardware.org/?probe=36a9fc9a39) | Oct 07, 2021 |
| Lenovo        | ThinkPad T60 1952W97        | [babe5f02f0](https://linux-hardware.org/?probe=babe5f02f0) | Oct 07, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [399430cdbe](https://linux-hardware.org/?probe=399430cdbe) | Oct 06, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [9638a69b00](https://linux-hardware.org/?probe=9638a69b00) | Oct 06, 2021 |
| Lenovo        | ThinkPad E14 20RA0016RT     | [d09fddd2b5](https://linux-hardware.org/?probe=d09fddd2b5) | Oct 06, 2021 |
| ASUSTek       | 1005HA                      | [c420fc556e](https://linux-hardware.org/?probe=c420fc556e) | Oct 05, 2021 |
| Sony          | VPCSB1V9R                   | [2d0b219a36](https://linux-hardware.org/?probe=2d0b219a36) | Oct 05, 2021 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | [697843fefc](https://linux-hardware.org/?probe=697843fefc) | Oct 05, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [9ba5143844](https://linux-hardware.org/?probe=9ba5143844) | Oct 04, 2021 |
| Alienware     | 17 R4                       | [564dd05308](https://linux-hardware.org/?probe=564dd05308) | Oct 04, 2021 |
| Alienware     | 17 R4                       | [01f8341213](https://linux-hardware.org/?probe=01f8341213) | Oct 04, 2021 |
| ASUSTek       | X455LD                      | [70b6961d1d](https://linux-hardware.org/?probe=70b6961d1d) | Oct 03, 2021 |
| ASUSTek       | X455LD                      | [7587f9b825](https://linux-hardware.org/?probe=7587f9b825) | Oct 03, 2021 |
| Dell          | Vostro 3550                 | [e8fd995776](https://linux-hardware.org/?probe=e8fd995776) | Oct 03, 2021 |
| Medion        | E14303                      | [0fa72b5193](https://linux-hardware.org/?probe=0fa72b5193) | Oct 02, 2021 |
| Sony          | VGN-NR38E_S                 | [8cb5fc39c1](https://linux-hardware.org/?probe=8cb5fc39c1) | Oct 01, 2021 |
| Fujitsu       | LIFEBOOK E752               | [5cccf30dd4](https://linux-hardware.org/?probe=5cccf30dd4) | Oct 01, 2021 |
| ASUSTek       | K53E                        | [c98e6e26ce](https://linux-hardware.org/?probe=c98e6e26ce) | Oct 01, 2021 |
| HP            | Compaq 6730b (GW687AV)      | [ae3ecaef4f](https://linux-hardware.org/?probe=ae3ecaef4f) | Sep 29, 2021 |
| Fujitsu Si... | AMILO Pa 1510               | [73a0747f86](https://linux-hardware.org/?probe=73a0747f86) | Sep 29, 2021 |
| HP            | Notebook                    | [bdf314b662](https://linux-hardware.org/?probe=bdf314b662) | Sep 29, 2021 |
| Toshiba       | Satellite C55-A             | [97872be09f](https://linux-hardware.org/?probe=97872be09f) | Sep 28, 2021 |
| Toshiba       | Satellite C55-A             | [c79d4daf0a](https://linux-hardware.org/?probe=c79d4daf0a) | Sep 28, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [4850590ac5](https://linux-hardware.org/?probe=4850590ac5) | Sep 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e7f361c688](https://linux-hardware.org/?probe=e7f361c688) | Sep 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [17bef7f4cf](https://linux-hardware.org/?probe=17bef7f4cf) | Sep 27, 2021 |
| Dell          | Latitude E5530 non-vPro     | [7e710da685](https://linux-hardware.org/?probe=7e710da685) | Sep 27, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Xubuntu/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Xubuntu 20.04 | 1012      | 46.42%  |
| Xubuntu 18.04 | 596       | 27.34%  |
| Xubuntu 22.04 | 213       | 9.77%   |
| Xubuntu 19.10 | 110       | 5.05%   |
| Xubuntu 21.10 | 57        | 2.61%   |
| Xubuntu 16.04 | 47        | 2.16%   |
| Xubuntu 20.10 | 42        | 1.93%   |
| Xubuntu 21.04 | 41        | 1.88%   |
| Xubuntu 22.10 | 26        | 1.19%   |
| Xubuntu 19.04 | 13        | 0.6%    |
| Xubuntu 18.10 | 6         | 0.28%   |
| Xubuntu 17.10 | 6         | 0.28%   |
| Xubuntu       | 4         | 0.18%   |
| Xubuntu 14.04 | 3         | 0.14%   |
| Xubuntu 23.04 | 2         | 0.09%   |
| Xubuntu 17.04 | 2         | 0.09%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Xubuntu | 2119      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.4.0-42-generic    | 87        | 3.54%   |
| 5.3.0-46-generic    | 41        | 1.67%   |
| 5.11.0-27-generic   | 39        | 1.59%   |
| 5.4.0-58-generic    | 34        | 1.38%   |
| 5.4.0-47-generic    | 31        | 1.26%   |
| 5.4.0-52-generic    | 30        | 1.22%   |
| 5.4.0-29-generic    | 30        | 1.22%   |
| 5.4.0-48-generic    | 28        | 1.14%   |
| 5.4.0-65-generic    | 27        | 1.1%    |
| 5.3.0-40-generic    | 27        | 1.1%    |
| 5.15.0-56-generic   | 27        | 1.1%    |
| 5.3.0-42-generic    | 26        | 1.06%   |
| 5.4.0-54-generic    | 25        | 1.02%   |
| 5.3.0-51-generic    | 22        | 0.89%   |
| 5.4.0-31-generic    | 21        | 0.85%   |
| 5.0.0-37-generic    | 21        | 0.85%   |
| 5.4.0-40-generic    | 20        | 0.81%   |
| 5.15.0-58-generic   | 20        | 0.81%   |
| 5.3.0-28-generic    | 19        | 0.77%   |
| 5.15.0-52-generic   | 19        | 0.77%   |
| 5.15.0-47-generic   | 19        | 0.77%   |
| 4.15.0-99-generic   | 19        | 0.77%   |
| 5.4.0-42-lowlatency | 18        | 0.73%   |
| 5.3.0-53-generic    | 18        | 0.73%   |
| 5.15.0-48-generic   | 18        | 0.73%   |
| 5.4.0-89-generic    | 17        | 0.69%   |
| 5.4.0-66-generic    | 17        | 0.69%   |
| 5.4.0-26-generic    | 17        | 0.69%   |
| 5.4.0-67-generic    | 16        | 0.65%   |
| 5.4.0-53-generic    | 16        | 0.65%   |
| 5.4.0-37-generic    | 16        | 0.65%   |
| 5.8.0-53-generic    | 15        | 0.61%   |
| 5.8.0-43-generic    | 15        | 0.61%   |
| 5.4.0-56-generic    | 15        | 0.61%   |
| 5.13.0-39-generic   | 15        | 0.61%   |
| 5.13.0-30-generic   | 15        | 0.61%   |
| 5.4.0-72-generic    | 14        | 0.57%   |
| 5.4.0-60-generic    | 14        | 0.57%   |
| 5.4.0-33-generic    | 14        | 0.57%   |
| 5.15.0-46-generic   | 14        | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 826       | 37.21%  |
| 5.3.0   | 258       | 11.62%  |
| 4.15.0  | 246       | 11.08%  |
| 5.15.0  | 224       | 10.09%  |
| 5.11.0  | 166       | 7.48%   |
| 5.8.0   | 132       | 5.95%   |
| 5.13.0  | 131       | 5.9%    |
| 5.0.0   | 57        | 2.57%   |
| 5.19.0  | 35        | 1.58%   |
| 4.4.0   | 25        | 1.13%   |
| 4.18.0  | 14        | 0.63%   |
| 5.17.0  | 8         | 0.36%   |
| 4.13.0  | 7         | 0.32%   |
| 5.10.0  | 5         | 0.23%   |
| 5.14.0  | 4         | 0.18%   |
| 5.6.0   | 3         | 0.14%   |
| 5.4.217 | 3         | 0.14%   |
| 6.0.9   | 2         | 0.09%   |
| 5.6.19  | 2         | 0.09%   |
| 5.5.19  | 2         | 0.09%   |
| 5.18.0  | 2         | 0.09%   |
| 5.11.11 | 2         | 0.09%   |
| 4.8.0   | 2         | 0.09%   |
| 4.4.254 | 2         | 0.09%   |
| 4.11.0  | 2         | 0.09%   |
| 4.10.0  | 2         | 0.09%   |
| 6.2.2   | 1         | 0.05%   |
| 6.2.0   | 1         | 0.05%   |
| 6.1.6   | 1         | 0.05%   |
| 6.1.0   | 1         | 0.05%   |
| 6.0.7   | 1         | 0.05%   |
| 6.0.0   | 1         | 0.05%   |
| 5.9.6   | 1         | 0.05%   |
| 5.9.16  | 1         | 0.05%   |
| 5.9.0   | 1         | 0.05%   |
| 5.8.18  | 1         | 0.05%   |
| 5.7.7   | 1         | 0.05%   |
| 5.7.6   | 1         | 0.05%   |
| 5.7.19  | 1         | 0.05%   |
| 5.7.1   | 1         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 833       | 37.54%  |
| 5.3     | 260       | 11.72%  |
| 4.15    | 246       | 11.09%  |
| 5.15    | 226       | 10.18%  |
| 5.11    | 172       | 7.75%   |
| 5.8     | 133       | 5.99%   |
| 5.13    | 132       | 5.95%   |
| 5.0     | 58        | 2.61%   |
| 5.19    | 36        | 1.62%   |
| 4.4     | 27        | 1.22%   |
| 4.18    | 14        | 0.63%   |
| 5.10    | 11        | 0.5%    |
| 5.17    | 9         | 0.41%   |
| 5.14    | 8         | 0.36%   |
| 4.13    | 7         | 0.32%   |
| 5.6     | 6         | 0.27%   |
| 5.7     | 5         | 0.23%   |
| 4.19    | 5         | 0.23%   |
| 6.0     | 4         | 0.18%   |
| 5.12    | 4         | 0.18%   |
| 5.9     | 3         | 0.14%   |
| 6.2     | 2         | 0.09%   |
| 6.1     | 2         | 0.09%   |
| 5.5     | 2         | 0.09%   |
| 5.18    | 2         | 0.09%   |
| 5.16    | 2         | 0.09%   |
| 4.8     | 2         | 0.09%   |
| 4.11    | 2         | 0.09%   |
| 4.10    | 2         | 0.09%   |
| 4.20    | 1         | 0.05%   |
| 4.14    | 1         | 0.05%   |
| 4.12    | 1         | 0.05%   |
| 3.13    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1784      | 84.11%  |
| i686   | 337       | 15.89%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| XFCE            | 2052      | 96.66%  |
| GNOME           | 50        | 2.36%   |
| i3              | 8         | 0.38%   |
| Unity           | 3         | 0.14%   |
| KDE5            | 2         | 0.09%   |
| Cinnamon        | 2         | 0.09%   |
| xmonad          | 1         | 0.05%   |
| MATE            | 1         | 0.05%   |
| ICEWM           | 1         | 0.05%   |
| GNUstep         | 1         | 0.05%   |
| GNOME Flashback | 1         | 0.05%   |
| awesome         | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2096      | 98.87%  |
| Tty     | 12        | 0.57%   |
| Wayland | 11        | 0.52%   |
| Unknown | 1         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1120      | 51.19%  |
| LightDM | 722       | 33%     |
| TDM     | 284       | 12.98%  |
| GDM3    | 31        | 1.42%   |
| GDM     | 22        | 1.01%   |
| SDDM    | 6         | 0.27%   |
| SLiM    | 2         | 0.09%   |
| XDM     | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 700       | 32.93%  |
| de_DE   | 226       | 10.63%  |
| fr_FR   | 181       | 8.51%   |
| it_IT   | 160       | 7.53%   |
| pt_BR   | 105       | 4.94%   |
| ru_RU   | 90        | 4.23%   |
| C       | 79        | 3.72%   |
| en_GB   | 78        | 3.67%   |
| es_ES   | 63        | 2.96%   |
| Unknown | 43        | 2.02%   |
| pl_PL   | 35        | 1.65%   |
| en_CA   | 30        | 1.41%   |
| en_AU   | 28        | 1.32%   |
| cs_CZ   | 22        | 1.03%   |
| hu_HU   | 19        | 0.89%   |
| es_AR   | 18        | 0.85%   |
| nl_NL   | 17        | 0.8%    |
| en_IN   | 17        | 0.8%    |
| es_MX   | 15        | 0.71%   |
| ja_JP   | 14        | 0.66%   |
| pt_PT   | 11        | 0.52%   |
| tr_TR   | 10        | 0.47%   |
| el_GR   | 10        | 0.47%   |
| ru_UA   | 9         | 0.42%   |
| fr_BE   | 9         | 0.42%   |
| fi_FI   | 9         | 0.42%   |
| sk_SK   | 8         | 0.38%   |
| es_CO   | 8         | 0.38%   |
| en_ZA   | 8         | 0.38%   |
| sv_SE   | 7         | 0.33%   |
| nl_BE   | 6         | 0.28%   |
| de_CH   | 6         | 0.28%   |
| zh_CN   | 5         | 0.24%   |
| es_VE   | 5         | 0.24%   |
| es_CL   | 5         | 0.24%   |
| ca_ES   | 5         | 0.24%   |
| bg_BG   | 5         | 0.24%   |
| uk_UA   | 4         | 0.19%   |
| nb_NO   | 4         | 0.19%   |
| es_PE   | 4         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1321      | 61.87%  |
| EFI  | 814       | 38.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1941      | 91.51%  |
| Overlay | 101       | 4.76%   |
| Btrfs   | 37        | 1.74%   |
| Zfs     | 18        | 0.85%   |
| Unknown | 12        | 0.57%   |
| Xfs     | 4         | 0.19%   |
| Ext2    | 4         | 0.19%   |
| Ext3    | 3         | 0.14%   |
| Ufs     | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1347      | 62.74%  |
| GPT     | 539       | 25.1%   |
| MBR     | 261       | 12.16%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1894      | 87.85%  |
| Yes       | 262       | 12.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1494      | 69.62%  |
| Yes       | 652       | 30.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 439       | 20.72%  |
| Lenovo              | 377       | 17.79%  |
| Dell                | 276       | 13.03%  |
| ASUSTek Computer    | 239       | 11.28%  |
| Acer                | 212       | 10%     |
| Toshiba             | 99        | 4.67%   |
| Samsung Electronics | 54        | 2.55%   |
| Sony                | 49        | 2.31%   |
| Apple               | 38        | 1.79%   |
| MSI                 | 31        | 1.46%   |
| Medion              | 25        | 1.18%   |
| Fujitsu Siemens     | 24        | 1.13%   |
| Packard Bell        | 19        | 0.9%    |
| Notebook            | 17        | 0.8%    |
| Google              | 15        | 0.71%   |
| Clevo               | 15        | 0.71%   |
| Fujitsu             | 13        | 0.61%   |
| HUAWEI              | 11        | 0.52%   |
| Unknown             | 11        | 0.52%   |
| Positivo            | 10        | 0.47%   |
| Intel               | 8         | 0.38%   |
| Gateway             | 8         | 0.38%   |
| IBM                 | 7         | 0.33%   |
| GPU Company         | 7         | 0.33%   |
| LG Electronics      | 5         | 0.24%   |
| eMachines           | 5         | 0.24%   |
| TUXEDO              | 4         | 0.19%   |
| Schenker            | 4         | 0.19%   |
| Dynabook            | 4         | 0.19%   |
| Alienware           | 4         | 0.19%   |
| Semp Toshiba        | 3         | 0.14%   |
| OEM                 | 3         | 0.14%   |
| Itautec             | 3         | 0.14%   |
| Dixonsxp            | 3         | 0.14%   |
| Chuwi               | 3         | 0.14%   |
| AMI                 | 3         | 0.14%   |
| System76            | 2         | 0.09%   |
| Razer               | 2         | 0.09%   |
| Quanta              | 2         | 0.09%   |
| Panasonic           | 2         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 30        | 1.42%   |
| HP Pavilion dv6                        | 17        | 0.8%    |
| HP Notebook                            | 17        | 0.8%    |
| Dell Latitude D630                     | 11        | 0.52%   |
| HP Pavilion 15                         | 10        | 0.47%   |
| HP 15                                  | 10        | 0.47%   |
| Dell Latitude E6430                    | 9         | 0.42%   |
| HP Pavilion dv7                        | 7         | 0.33%   |
| HP Pavilion dv6500                     | 7         | 0.33%   |
| HP Pavilion g6                         | 6         | 0.28%   |
| ASUS VivoBook_ASUSLaptop X571LH_K571LH | 6         | 0.28%   |
| HP EliteBook 840 G3                    | 5         | 0.24%   |
| Dell Latitude E6520                    | 5         | 0.24%   |
| ASUS 1005HA                            | 5         | 0.24%   |
| Acer Aspire one                        | 5         | 0.24%   |
| Acer AO751h                            | 5         | 0.24%   |
| Positivo Mobile                        | 4         | 0.19%   |
| HP Pavilion g7                         | 4         | 0.19%   |
| HP Laptop 15-bw0xx                     | 4         | 0.19%   |
| HP G62                                 | 4         | 0.19%   |
| HP G42                                 | 4         | 0.19%   |
| HP EliteBook 8560p                     | 4         | 0.19%   |
| HP Compaq Presario C700                | 4         | 0.19%   |
| HP Compaq 6730s                        | 4         | 0.19%   |
| HP 255 G7 Notebook PC                  | 4         | 0.19%   |
| Dell Studio 1535                       | 4         | 0.19%   |
| Dell Latitude E6420                    | 4         | 0.19%   |
| Dell Latitude E6400                    | 4         | 0.19%   |
| Dell Latitude E6330                    | 4         | 0.19%   |
| Dell Inspiron 7520                     | 4         | 0.19%   |
| Dell Inspiron 1545                     | 4         | 0.19%   |
| Dell Inspiron 1525                     | 4         | 0.19%   |
| Dell Inspiron 15-3567                  | 4         | 0.19%   |
| ASUS X553MA                            | 4         | 0.19%   |
| ASUS T100HAN                           | 4         | 0.19%   |
| ASUS K53SC                             | 4         | 0.19%   |
| Acer Aspire 9300                       | 4         | 0.19%   |
| Acer Aspire 7720                       | 4         | 0.19%   |
| Toshiba Satellite L300                 | 3         | 0.14%   |
| Toshiba Satellite C650                 | 3         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 227       | 10.71%  |
| Acer Aspire             | 143       | 6.75%   |
| Dell Latitude           | 118       | 5.57%   |
| HP Pavilion             | 106       | 5%      |
| Dell Inspiron           | 95        | 4.48%   |
| Toshiba Satellite       | 84        | 3.96%   |
| Lenovo IdeaPad          | 69        | 3.26%   |
| HP EliteBook            | 56        | 2.64%   |
| HP Compaq               | 48        | 2.27%   |
| HP ProBook              | 43        | 2.03%   |
| HP Laptop               | 38        | 1.79%   |
| ASUS VivoBook           | 33        | 1.56%   |
| Unknown                 | 30        | 1.42%   |
| HP Notebook             | 18        | 0.85%   |
| Dell XPS                | 16        | 0.76%   |
| Dell Vostro             | 16        | 0.76%   |
| Acer Extensa            | 16        | 0.76%   |
| Fujitsu Siemens AMILO   | 15        | 0.71%   |
| Packard Bell EasyNote   | 14        | 0.66%   |
| Dell Precision          | 14        | 0.66%   |
| HP Mini                 | 11        | 0.52%   |
| HP 255                  | 11        | 0.52%   |
| HP 15                   | 11        | 0.52%   |
| Fujitsu LIFEBOOK        | 11        | 0.52%   |
| HP Presario             | 10        | 0.47%   |
| Acer TravelMate         | 10        | 0.47%   |
| HP Stream               | 9         | 0.42%   |
| HP 250                  | 9         | 0.42%   |
| Acer Swift              | 8         | 0.38%   |
| HP ZBook                | 7         | 0.33%   |
| HP ENVY                 | 7         | 0.33%   |
| Dell Studio             | 7         | 0.33%   |
| ASUS ASUS               | 7         | 0.33%   |
| Acer Nitro              | 7         | 0.33%   |
| Toshiba PORTEGE         | 6         | 0.28%   |
| IBM ThinkPad            | 6         | 0.28%   |
| Lenovo ThinkBook        | 5         | 0.24%   |
| Fujitsu Siemens ESPRIMO | 5         | 0.24%   |
| ASUS ROG                | 5         | 0.24%   |
| ASUS 1005HA             | 5         | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 188       | 8.87%   |
| 2012    | 185       | 8.73%   |
| 2008    | 177       | 8.35%   |
| 2010    | 165       | 7.79%   |
| 2007    | 154       | 7.27%   |
| 2013    | 144       | 6.8%    |
| 2019    | 130       | 6.13%   |
| 2009    | 125       | 5.9%    |
| 2014    | 111       | 5.24%   |
| 2018    | 108       | 5.1%    |
| 2017    | 107       | 5.05%   |
| 2020    | 106       | 5%      |
| 2016    | 97        | 4.58%   |
| 2021    | 88        | 4.15%   |
| 2015    | 85        | 4.01%   |
| 2006    | 79        | 3.73%   |
| 2005    | 34        | 1.6%    |
| 2022    | 17        | 0.8%    |
| 2003    | 8         | 0.38%   |
| 2004    | 7         | 0.33%   |
| Unknown | 2         | 0.09%   |
| 2023    | 1         | 0.05%   |
| 2002    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2119      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1969      | 92.44%  |
| Enabled  | 161       | 7.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2103      | 99.24%  |
| Yes  | 16        | 0.76%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 632       | 29.51%  |
| 4.01-8.0    | 464       | 21.66%  |
| 1.01-2.0    | 303       | 14.15%  |
| 8.01-16.0   | 234       | 10.92%  |
| 16.01-24.0  | 199       | 9.29%   |
| 0.51-1.0    | 110       | 5.14%   |
| 2.01-3.0    | 94        | 4.39%   |
| 32.01-64.0  | 69        | 3.22%   |
| 24.01-32.0  | 16        | 0.75%   |
| 64.01-256.0 | 14        | 0.65%   |
| 0.01-0.5    | 7         | 0.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 966       | 41.84%  |
| 0.51-1.0   | 496       | 21.48%  |
| 2.01-3.0   | 428       | 18.54%  |
| 4.01-8.0   | 163       | 7.06%   |
| 3.01-4.0   | 138       | 5.98%   |
| 0.01-0.5   | 73        | 3.16%   |
| 8.01-16.0  | 40        | 1.73%   |
| 16.01-24.0 | 3         | 0.13%   |
| 24.01-32.0 | 1         | 0.04%   |
| Unknown    | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1623      | 75.35%  |
| 2      | 446       | 20.71%  |
| 3      | 49        | 2.27%   |
| 0      | 27        | 1.25%   |
| 4      | 6         | 0.28%   |
| 5      | 2         | 0.09%   |
| 7      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1091      | 51.34%  |
| No        | 1034      | 48.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1862      | 87.79%  |
| No        | 259       | 12.21%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2063      | 97.17%  |
| No        | 60        | 2.83%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1302      | 60.7%   |
| No        | 843       | 39.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 300       | 14.06%  |
| Germany      | 277       | 12.98%  |
| France       | 199       | 9.33%   |
| Italy        | 176       | 8.25%   |
| Brazil       | 123       | 5.76%   |
| Russia       | 121       | 5.67%   |
| UK           | 79        | 3.7%    |
| Spain        | 75        | 3.51%   |
| Canada       | 66        | 3.09%   |
| Netherlands  | 49        | 2.3%    |
| Poland       | 44        | 2.06%   |
| Australia    | 35        | 1.64%   |
| Czechia      | 33        | 1.55%   |
| Mexico       | 31        | 1.45%   |
| Ukraine      | 29        | 1.36%   |
| Belgium      | 28        | 1.31%   |
| India        | 26        | 1.22%   |
| Argentina    | 25        | 1.17%   |
| Portugal     | 24        | 1.12%   |
| Finland      | 22        | 1.03%   |
| Hungary      | 20        | 0.94%   |
| Indonesia    | 19        | 0.89%   |
| Greece       | 19        | 0.89%   |
| Turkey       | 17        | 0.8%    |
| Sweden       | 17        | 0.8%    |
| Japan        | 16        | 0.75%   |
| Bulgaria     | 15        | 0.7%    |
| Romania      | 13        | 0.61%   |
| Austria      | 13        | 0.61%   |
| Slovakia     | 11        | 0.52%   |
| Norway       | 11        | 0.52%   |
| Colombia     | 11        | 0.52%   |
| Iran         | 10        | 0.47%   |
| Switzerland  | 9         | 0.42%   |
| Chile        | 9         | 0.42%   |
| Denmark      | 8         | 0.37%   |
| Belarus      | 8         | 0.37%   |
| Venezuela    | 7         | 0.33%   |
| South Africa | 7         | 0.33%   |
| Israel       | 7         | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Paris             | 33        | 1.46%   |
| Berlin            | 26        | 1.15%   |
| Moscow            | 25        | 1.11%   |
| Rome              | 21        | 0.93%   |
| Milan             | 21        | 0.93%   |
| St Petersburg     | 17        | 0.75%   |
| Québec           | 17        | 0.75%   |
| Athens            | 17        | 0.75%   |
| Warsaw            | 15        | 0.67%   |
| Munich            | 14        | 0.62%   |
| Sao Paulo         | 12        | 0.53%   |
| Prague            | 12        | 0.53%   |
| Amsterdam         | 12        | 0.53%   |
| Helsinki          | 11        | 0.49%   |
| Hamburg           | 11        | 0.49%   |
| Madrid            | 10        | 0.44%   |
| Kyiv              | 10        | 0.44%   |
| Budapest          | 10        | 0.44%   |
| Barcelona         | 10        | 0.44%   |
| Sydney            | 9         | 0.4%    |
| Rio de Janeiro    | 9         | 0.4%    |
| Stuttgart         | 8         | 0.36%   |
| Melbourne         | 8         | 0.36%   |
| Leipzig           | 8         | 0.36%   |
| Karlsruhe         | 8         | 0.36%   |
| Genoa             | 8         | 0.36%   |
| Ankara            | 8         | 0.36%   |
| Yokohama          | 7         | 0.31%   |
| Turin             | 7         | 0.31%   |
| Sofia             | 7         | 0.31%   |
| Lisbon            | 7         | 0.31%   |
| Frankfurt am Main | 7         | 0.31%   |
| Bucharest         | 7         | 0.31%   |
| Vienna            | 6         | 0.27%   |
| Toronto           | 6         | 0.27%   |
| Tehran            | 6         | 0.27%   |
| Seattle           | 6         | 0.27%   |
| Samara            | 6         | 0.27%   |
| Rostov-on-Don     | 6         | 0.27%   |
| Oryol             | 6         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 382       | 464    | 15.32%  |
| Samsung Electronics | 335       | 411    | 13.44%  |
| WDC                 | 320       | 390    | 12.84%  |
| Toshiba             | 233       | 266    | 9.35%   |
| Unknown             | 170       | 220    | 6.82%   |
| Hitachi             | 158       | 186    | 6.34%   |
| Kingston            | 99        | 130    | 3.97%   |
| SanDisk             | 90        | 106    | 3.61%   |
| HGST                | 80        | 92     | 3.21%   |
| SK hynix            | 65        | 79     | 2.61%   |
| Crucial             | 58        | 68     | 2.33%   |
| Fujitsu             | 57        | 72     | 2.29%   |
| Intel               | 54        | 72     | 2.17%   |
| Micron Technology   | 34        | 36     | 1.36%   |
| A-DATA Technology   | 31        | 43     | 1.24%   |
| China               | 28        | 30     | 1.12%   |
| Transcend           | 15        | 16     | 0.6%    |
| Apple               | 14        | 21     | 0.56%   |
| LITEONIT            | 13        | 16     | 0.52%   |
| PNY                 | 12        | 14     | 0.48%   |
| OCZ                 | 12        | 13     | 0.48%   |
| LITEON              | 12        | 14     | 0.48%   |
| Phison              | 11        | 15     | 0.44%   |
| KIOXIA              | 11        | 13     | 0.44%   |
| Intenso             | 11        | 11     | 0.44%   |
| Unknown             | 11        | 11     | 0.44%   |
| SPCC                | 9         | 11     | 0.36%   |
| JMicron Technology  | 9         | 8      | 0.36%   |
| Apacer              | 8         | 10     | 0.32%   |
| Patriot             | 7         | 7      | 0.28%   |
| KingSpec            | 7         | 9      | 0.28%   |
| Netac               | 6         | 9      | 0.24%   |
| IBM/Hitachi         | 6         | 6      | 0.24%   |
| Silicon Motion      | 5         | 5      | 0.2%    |
| KingDian            | 5         | 7      | 0.2%    |
| HUAWEI              | 5         | 5      | 0.2%    |
| Hewlett-Packard     | 5         | 5      | 0.2%    |
| USB3.0              | 4         | 5      | 0.16%   |
| Smartbuy            | 4         | 4      | 0.16%   |
| Pioneer             | 4         | 4      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                 | 42        | 1.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 30        | 1.17%   |
| Seagate ST500LT012-1DG142 500GB        | 24        | 0.94%   |
| Toshiba MQ01ABF050 500GB               | 23        | 0.9%    |
| Seagate ST500LM012 HN-M500MBB 500GB    | 23        | 0.9%    |
| Toshiba MQ01ABD100 1TB                 | 22        | 0.86%   |
| Seagate ST1000LM035-1RK172 1TB         | 22        | 0.86%   |
| Kingston SA400S37480G 480GB SSD        | 20        | 0.78%   |
| HGST HTS541010A9E680 1TB               | 19        | 0.74%   |
| Unknown MMC Card  64GB                 | 18        | 0.7%    |
| Seagate ST9500325AS 500GB              | 18        | 0.7%    |
| HGST HTS721010A9E630 1TB               | 18        | 0.7%    |
| Seagate ST9320325AS 320GB              | 17        | 0.66%   |
| Seagate ST500LT012-9WS142 500GB        | 16        | 0.62%   |
| Kingston SA400S37240G 240GB SSD        | 16        | 0.62%   |
| Samsung SSD 850 EVO 250GB              | 15        | 0.59%   |
| Unknown MMC Card  128GB                | 14        | 0.55%   |
| Toshiba MQ04ABF100 1TB                 | 14        | 0.55%   |
| Samsung SSD 860 EVO 500GB              | 13        | 0.51%   |
| Kingston SA400S37120G 120GB SSD        | 13        | 0.51%   |
| WDC WD10JPVX-22JC3T0 1TB               | 12        | 0.47%   |
| Unknown MMC Card  16GB                 | 12        | 0.47%   |
| WDC WD1600BEVT-22ZCT0 160GB            | 11        | 0.43%   |
| SK hynix NVMe SSD Drive 256GB          | 11        | 0.43%   |
| Seagate ST9250315AS 250GB              | 11        | 0.43%   |
| Seagate ST9160310AS 160GB              | 11        | 0.43%   |
| Samsung SSD 850 EVO 500GB              | 11        | 0.43%   |
| HGST HTS545050A7E680 500GB             | 11        | 0.43%   |
| Crucial CT240BX500SSD1 240GB           | 11        | 0.43%   |
| Unknown                                | 11        | 0.43%   |
| Samsung NVMe SSD Drive 512GB           | 10        | 0.39%   |
| Hitachi HTS543232A7A384 320GB          | 10        | 0.39%   |
| HGST HTS725050A7E630 500GB             | 10        | 0.39%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 9         | 0.35%   |
| WDC WD3200BEVT-22ZCT0 320GB            | 9         | 0.35%   |
| Unknown SD/MMC/MS PRO 64GB             | 9         | 0.35%   |
| Seagate ST9160314AS 160GB              | 9         | 0.35%   |
| Samsung SSD 860 EVO 1TB                | 9         | 0.35%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 9         | 0.35%   |
| Samsung HM321HI 320GB                  | 9         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 376       | 455    | 31.26%  |
| WDC                 | 252       | 311    | 20.95%  |
| Toshiba             | 191       | 221    | 15.88%  |
| Hitachi             | 158       | 186    | 13.13%  |
| HGST                | 80        | 92     | 6.65%   |
| Samsung Electronics | 57        | 66     | 4.74%   |
| Fujitsu             | 55        | 70     | 4.57%   |
| Unknown             | 9         | 10     | 0.75%   |
| IBM/Hitachi         | 6         | 6      | 0.5%    |
| USB3.0              | 4         | 5      | 0.33%   |
| Pioneer             | 3         | 3      | 0.25%   |
| ASMT                | 3         | 5      | 0.25%   |
| HGST HTS            | 2         | 2      | 0.17%   |
| SABRENT             | 1         | 1      | 0.08%   |
| Intenso             | 1         | 1      | 0.08%   |
| CLOVER              | 1         | 1      | 0.08%   |
| ASMedia             | 1         | 1      | 0.08%   |
| Apricorn            | 1         | 2      | 0.08%   |
| ACASIS              | 1         | 1      | 0.08%   |
| Unknown             | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 175       | 221    | 23.49%  |
| Kingston            | 89        | 118    | 11.95%  |
| SanDisk             | 64        | 77     | 8.59%   |
| Crucial             | 56        | 66     | 7.52%   |
| China               | 28        | 30     | 3.76%   |
| A-DATA Technology   | 28        | 40     | 3.76%   |
| WDC                 | 24        | 25     | 3.22%   |
| Intel               | 22        | 31     | 2.95%   |
| Micron Technology   | 21        | 22     | 2.82%   |
| Toshiba             | 19        | 20     | 2.55%   |
| SK hynix            | 18        | 18     | 2.42%   |
| Transcend           | 15        | 15     | 2.01%   |
| LITEONIT            | 13        | 16     | 1.74%   |
| PNY                 | 12        | 14     | 1.61%   |
| OCZ                 | 12        | 13     | 1.61%   |
| LITEON              | 12        | 14     | 1.61%   |
| Intenso             | 10        | 10     | 1.34%   |
| SPCC                | 9         | 11     | 1.21%   |
| Apple               | 9         | 13     | 1.21%   |
| Patriot             | 7         | 7      | 0.94%   |
| Apacer              | 7         | 9      | 0.94%   |
| KingSpec            | 6         | 8      | 0.81%   |
| Unknown             | 5         | 6      | 0.67%   |
| Netac               | 5         | 8      | 0.67%   |
| KingDian            | 5         | 7      | 0.67%   |
| JMicron Technology  | 5         | 5      | 0.67%   |
| Smartbuy            | 4         | 4      | 0.54%   |
| Hewlett-Packard     | 4         | 5      | 0.54%   |
| TO Exter            | 3         | 3      | 0.4%    |
| Plextor             | 3         | 6      | 0.4%    |
| GOODRAM             | 3         | 3      | 0.4%    |
| Drevo               | 3         | 3      | 0.4%    |
| Zheino              | 2         | 2      | 0.27%   |
| Team                | 2         | 4      | 0.27%   |
| TCSUNBOW            | 2         | 2      | 0.27%   |
| SSSTC               | 2         | 2      | 0.27%   |
| Mushkin             | 2         | 2      | 0.27%   |
| INNOVATION IT       | 2         | 2      | 0.27%   |
| FORESEE             | 2         | 2      | 0.27%   |
| Dogfish             | 2         | 5      | 0.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1166      | 1440   | 48.46%  |
| SSD     | 693       | 909    | 28.8%   |
| NVMe    | 346       | 417    | 14.38%  |
| MMC     | 169       | 216    | 7.02%   |
| Unknown | 32        | 35     | 1.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1723      | 2275   | 74.01%  |
| NVMe | 344       | 414    | 14.78%  |
| MMC  | 169       | 216    | 7.26%   |
| SAS  | 92        | 112    | 3.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1420      | 1828   | 76.84%  |
| 0.51-1.0   | 377       | 456    | 20.4%   |
| 1.01-2.0   | 41        | 48     | 2.22%   |
| 4.01-10.0  | 5         | 11     | 0.27%   |
| 3.01-4.0   | 3         | 4      | 0.16%   |
| 2.01-3.0   | 1         | 1      | 0.05%   |
| 0          | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 767       | 34.97%  |
| 251-500        | 560       | 25.54%  |
| 501-1000       | 262       | 11.95%  |
| 51-100         | 216       | 9.85%   |
| 21-50          | 154       | 7.02%   |
| 1-20           | 107       | 4.88%   |
| 1001-2000      | 81        | 3.69%   |
| 2001-3000      | 19        | 0.87%   |
| More than 3000 | 15        | 0.68%   |
| Unknown        | 12        | 0.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1050      | 46.17%  |
| 21-50          | 417       | 18.34%  |
| 101-250        | 280       | 12.31%  |
| 51-100         | 265       | 11.65%  |
| 251-500        | 137       | 6.02%   |
| 501-1000       | 79        | 3.47%   |
| 1001-2000      | 24        | 1.06%   |
| Unknown        | 12        | 0.53%   |
| More than 3000 | 5         | 0.22%   |
| 2001-3000      | 5         | 0.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 8         | 8      | 5.56%   |
| Seagate ST9500325AS 500GB          | 6         | 8      | 4.17%   |
| Toshiba MQ01ABD100 1TB             | 5         | 6      | 3.47%   |
| Seagate ST500LT012-9WS142 500GB    | 5         | 5      | 3.47%   |
| HGST HTS545050A7E680 500GB         | 3         | 3      | 2.08%   |
| HGST HTS541010A9E680 1TB           | 3         | 3      | 2.08%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 2         | 2      | 1.39%   |
| Seagate ST9500423AS 500GB          | 2         | 2      | 1.39%   |
| Seagate ST9320325AS 320GB          | 2         | 2      | 1.39%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 2      | 1.39%   |
| Seagate ST320LT007-9ZV142 320GB    | 2         | 2      | 1.39%   |
| Samsung Electronics HM321HI 320GB  | 2         | 2      | 1.39%   |
| Hitachi HTS725050A9A364 500GB      | 2         | 3      | 1.39%   |
| Hitachi HTS545050A7E380 500GB      | 2         | 2      | 1.39%   |
| Hitachi HTS543232A7A384 320GB      | 2         | 3      | 1.39%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 1      | 0.69%   |
| WDC WD7500BPVT-80HXZT3 752GB       | 1         | 2      | 0.69%   |
| WDC WD7500BPVT-24HXZT1 752GB       | 1         | 2      | 0.69%   |
| WDC WD7500BPKX-00HPJT0 752GB       | 1         | 1      | 0.69%   |
| WDC WD5000BEVT-60ZAT1 500GB        | 1         | 1      | 0.69%   |
| WDC WD5000BEKT-75KA9T0 500GB       | 1         | 1      | 0.69%   |
| WDC WD3200BPVT-35ZEST0 320GB       | 1         | 1      | 0.69%   |
| WDC WD3200BEVT-60ZCT1 320GB        | 1         | 1      | 0.69%   |
| WDC WD3200BEKT-75PVMT0 320GB       | 1         | 1      | 0.69%   |
| WDC WD1600BJKT-75F4T0 160GB        | 1         | 1      | 0.69%   |
| WDC WD1200BEVS-60UST0 120GB        | 1         | 1      | 0.69%   |
| WDC WD10SPCX-24HWST1 1TB           | 1         | 1      | 0.69%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 2      | 0.69%   |
| WDC WD10JPVT-08A1YT2 1TB           | 1         | 1      | 0.69%   |
| Toshiba MQ04ABF100 1TB             | 1         | 1      | 0.69%   |
| Toshiba MQ01ACF050 500GB           | 1         | 1      | 0.69%   |
| Toshiba MQ01ABD032 320GB           | 1         | 1      | 0.69%   |
| Toshiba MK7575GSX 752GB            | 1         | 1      | 0.69%   |
| Toshiba MK7559GSXP 752GB           | 1         | 2      | 0.69%   |
| Toshiba MK5076GSX 500GB            | 1         | 1      | 0.69%   |
| Toshiba MK5065GSXN 500GB           | 1         | 3      | 0.69%   |
| Toshiba MK5065GSX 500GB            | 1         | 1      | 0.69%   |
| Toshiba MK5059GSXP 500GB           | 1         | 1      | 0.69%   |
| Toshiba MK3276GSX -63 320GB        | 1         | 2      | 0.69%   |
| Toshiba MK3259GSXP 320GB           | 1         | 1      | 0.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 46     | 29.17%  |
| Toshiba             | 19        | 24     | 13.19%  |
| WDC                 | 16        | 19     | 11.11%  |
| Hitachi             | 16        | 18     | 11.11%  |
| Samsung Electronics | 8         | 8      | 5.56%   |
| HGST                | 8         | 9      | 5.56%   |
| Fujitsu             | 6         | 7      | 4.17%   |
| SK hynix            | 3         | 3      | 2.08%   |
| Intel               | 3         | 3      | 2.08%   |
| SanDisk             | 2         | 2      | 1.39%   |
| OCZ                 | 2         | 2      | 1.39%   |
| Micron Technology   | 2         | 2      | 1.39%   |
| Kingston            | 2         | 4      | 1.39%   |
| A-DATA Technology   | 2         | 3      | 1.39%   |
| SSSTC               | 1         | 1      | 0.69%   |
| Netac               | 1         | 1      | 0.69%   |
| Neo Forza           | 1         | 1      | 0.69%   |
| Mushkin             | 1         | 1      | 0.69%   |
| LITEON              | 1         | 1      | 0.69%   |
| LDLC                | 1         | 1      | 0.69%   |
| KingDian            | 1         | 3      | 0.69%   |
| JMicron Technology  | 1         | 1      | 0.69%   |
| Drevo               | 1         | 1      | 0.69%   |
| Crucial             | 1         | 1      | 0.69%   |
| China               | 1         | 1      | 0.69%   |
| Apple               | 1         | 1      | 0.69%   |
| Unknown             | 1         | 1      | 0.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 46     | 37.84%  |
| Toshiba             | 19        | 24     | 17.12%  |
| Hitachi             | 16        | 18     | 14.41%  |
| WDC                 | 15        | 18     | 13.51%  |
| HGST                | 8         | 9      | 7.21%   |
| Fujitsu             | 6         | 7      | 5.41%   |
| Samsung Electronics | 5         | 5      | 4.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 111       | 127    | 77.08%  |
| SSD  | 31        | 36     | 21.53%  |
| NVMe | 2         | 2      | 1.39%   |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1472      | 2098   | 66.91%  |
| Works    | 586       | 754    | 26.64%  |
| Malfunc  | 142       | 165    | 6.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1552      | 69.6%   |
| AMD                              | 267       | 11.97%  |
| Samsung Electronics              | 115       | 5.16%   |
| SanDisk                          | 68        | 3.05%   |
| SK hynix                         | 42        | 1.88%   |
| Silicon Integrated Systems [SiS] | 31        | 1.39%   |
| Nvidia                           | 31        | 1.39%   |
| Toshiba America Info Systems     | 21        | 0.94%   |
| KIOXIA                           | 14        | 0.63%   |
| VIA Technologies                 | 13        | 0.58%   |
| Phison Electronics               | 12        | 0.54%   |
| Micron Technology                | 12        | 0.54%   |
| Kingston Technology Company      | 12        | 0.54%   |
| Silicon Motion                   | 7         | 0.31%   |
| Apple                            | 5         | 0.22%   |
| ULi Electronics                  | 4         | 0.18%   |
| JMicron Technology               | 4         | 0.18%   |
| Silicon Image                    | 3         | 0.13%   |
| Realtek Semiconductor            | 3         | 0.13%   |
| Micron/Crucial Technology        | 3         | 0.13%   |
| Lenovo                           | 3         | 0.13%   |
| Union Memory (Shenzhen)          | 2         | 0.09%   |
| Seagate Technology               | 2         | 0.09%   |
| Lite-On Technology               | 2         | 0.09%   |
| INNOGRIT                         | 1         | 0.04%   |
| ADATA Technology                 | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 181       | 7.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 167       | 6.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 124       | 4.83%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 121       | 4.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 121       | 4.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 116       | 4.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 103       | 4.01%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 95        | 3.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 77        | 3%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 65        | 2.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 57        | 2.22%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 57        | 2.22%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 53        | 2.06%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 53        | 2.06%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 52        | 2.02%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 47        | 1.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 42        | 1.63%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 42        | 1.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 35        | 1.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 35        | 1.36%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 33        | 1.28%   |
| Samsung NVMe SSD Controller 980                                                  | 31        | 1.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 31        | 1.21%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 30        | 1.17%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 29        | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 27        | 1.05%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 24        | 0.93%   |
| Intel Volume Management Device NVMe RAID Controller                              | 23        | 0.9%    |
| AMD IXP SB4x0 IDE Controller                                                     | 22        | 0.86%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 21        | 0.82%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 20        | 0.78%   |
| AMD SB600 IDE                                                                    | 20        | 0.78%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 19        | 0.74%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 17        | 0.66%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 17        | 0.66%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 15        | 0.58%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 15        | 0.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 14        | 0.54%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 14        | 0.54%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 14        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1496      | 61.54%  |
| IDE  | 470       | 19.33%  |
| NVMe | 339       | 13.94%  |
| RAID | 126       | 5.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1780      | 84%     |
| AMD          | 337       | 15.9%   |
| CentaurHauls | 2         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz           | 30        | 1.41%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 22        | 1.04%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 21        | 0.99%   |
| Intel Atom CPU N450 @ 1.66GHz           | 21        | 0.99%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 20        | 0.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 20        | 0.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 19        | 0.9%    |
| Intel Core i5-7200U CPU @ 2.50GHz       | 19        | 0.9%    |
| Intel Celeron CPU N2840 @ 2.16GHz       | 19        | 0.9%    |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 18        | 0.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 18        | 0.85%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 18        | 0.85%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 17        | 0.8%    |
| Intel Core i5-6200U CPU @ 2.30GHz       | 16        | 0.75%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 16        | 0.75%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz    | 16        | 0.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 16        | 0.75%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 15        | 0.71%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 15        | 0.71%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 14        | 0.66%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 14        | 0.66%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 14        | 0.66%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 14        | 0.66%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 14        | 0.66%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 14        | 0.66%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz    | 14        | 0.66%   |
| Intel Pentium M processor 1.73GHz       | 13        | 0.61%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 13        | 0.61%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 13        | 0.61%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 13        | 0.61%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 13        | 0.61%   |
| Intel Core i3 CPU M 380 @ 2.53GHz       | 13        | 0.61%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz    | 13        | 0.61%   |
| Intel Celeron CPU N3050 @ 1.60GHz       | 13        | 0.61%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 13        | 0.61%   |
| Intel Atom CPU N455 @ 1.66GHz           | 13        | 0.61%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 12        | 0.57%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 12        | 0.57%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 12        | 0.57%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 12        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 401       | 18.9%   |
| Intel Core i7           | 322       | 15.17%  |
| Intel Core 2 Duo        | 196       | 9.24%   |
| Intel Core i3           | 169       | 7.96%   |
| Intel Celeron           | 166       | 7.82%   |
| Intel Atom              | 143       | 6.74%   |
| Intel Pentium           | 66        | 3.11%   |
| Other                   | 65        | 3.06%   |
| Intel Genuine           | 55        | 2.59%   |
| AMD Ryzen 5             | 43        | 2.03%   |
| Intel Pentium Dual-Core | 41        | 1.93%   |
| Intel Pentium Dual      | 41        | 1.93%   |
| Intel Core 2            | 31        | 1.46%   |
| Intel Pentium M         | 28        | 1.32%   |
| AMD Ryzen 7             | 28        | 1.32%   |
| AMD A8                  | 28        | 1.32%   |
| AMD E1                  | 27        | 1.27%   |
| Intel Celeron M         | 24        | 1.13%   |
| AMD A6                  | 24        | 1.13%   |
| AMD Turion 64 X2 Mobile | 20        | 0.94%   |
| AMD E2                  | 15        | 0.71%   |
| AMD E                   | 15        | 0.71%   |
| AMD A4                  | 14        | 0.66%   |
| AMD Ryzen 7 PRO         | 13        | 0.61%   |
| AMD Turion 64 Mobile    | 11        | 0.52%   |
| AMD Ryzen 3             | 9         | 0.42%   |
| Intel Pentium Silver    | 8         | 0.38%   |
| AMD Mobile Sempron      | 8         | 0.38%   |
| AMD Athlon              | 8         | 0.38%   |
| Intel Pentium 4         | 7         | 0.33%   |
| Intel Core Duo          | 7         | 0.33%   |
| AMD Athlon 64 X2        | 7         | 0.33%   |
| AMD A10                 | 7         | 0.33%   |
| Intel Celeron Dual-Core | 6         | 0.28%   |
| AMD C-60                | 5         | 0.24%   |
| AMD Sempron             | 4         | 0.19%   |
| AMD Ryzen 9             | 4         | 0.19%   |
| AMD Ryzen 5 PRO         | 4         | 0.19%   |
| AMD Athlon X2           | 4         | 0.19%   |
| Intel Xeon              | 3         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1298      | 61.23%  |
| 4      | 478       | 22.55%  |
| 1      | 221       | 10.42%  |
| 6      | 75        | 3.54%   |
| 8      | 46        | 2.17%   |
| 14     | 1         | 0.05%   |
| 12     | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2119      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1187      | 56.02%  |
| 1      | 932       | 43.98%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1954      | 92.17%  |
| 32-bit         | 166       | 7.83%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 323       | 14.93%  |
| 0x206a7    | 153       | 7.07%   |
| 0x306a9    | 140       | 6.47%   |
| 0x6fd      | 107       | 4.95%   |
| 0x1067a    | 104       | 4.81%   |
| 0x20655    | 73        | 3.37%   |
| 0x40651    | 63        | 2.91%   |
| 0x406e3    | 52        | 2.4%    |
| 0x10676    | 48        | 2.22%   |
| 0x30678    | 46        | 2.13%   |
| 0x106ca    | 45        | 2.08%   |
| 0x806ea    | 44        | 2.03%   |
| 0x806ec    | 42        | 1.94%   |
| 0x306c3    | 42        | 1.94%   |
| 0x406c4    | 41        | 1.9%    |
| 0x106c2    | 41        | 1.9%    |
| 0x306d4    | 40        | 1.85%   |
| 0x20652    | 39        | 1.8%    |
| 0x806c1    | 37        | 1.71%   |
| 0x806e9    | 35        | 1.62%   |
| 0x6d8      | 34        | 1.57%   |
| 0x906ea    | 33        | 1.53%   |
| 0x6e8      | 33        | 1.53%   |
| 0x6f6      | 28        | 1.29%   |
| 0x05000119 | 28        | 1.29%   |
| 0x406c3    | 25        | 1.16%   |
| 0xa0652    | 24        | 1.11%   |
| 0x07030105 | 24        | 1.11%   |
| 0x6ec      | 23        | 1.06%   |
| 0x6fb      | 22        | 1.02%   |
| 0x706a1    | 18        | 0.83%   |
| 0x10661    | 17        | 0.79%   |
| 0x0700010f | 17        | 0.79%   |
| 0x08108102 | 16        | 0.74%   |
| 0x706e5    | 15        | 0.69%   |
| 0x08108109 | 15        | 0.69%   |
| 0x906e9    | 14        | 0.65%   |
| 0x30661    | 13        | 0.6%    |
| 0x03000027 | 13        | 0.6%    |
| 0x08608103 | 12        | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 235       | 11.08%  |
| Core             | 189       | 8.91%   |
| Penryn           | 170       | 8.02%   |
| SandyBridge      | 169       | 7.97%   |
| IvyBridge        | 154       | 7.26%   |
| Westmere         | 130       | 6.13%   |
| Silvermont       | 121       | 5.7%    |
| Haswell          | 120       | 5.66%   |
| Bonnell          | 109       | 5.14%   |
| P6               | 97        | 4.57%   |
| Skylake          | 78        | 3.68%   |
| K8 Hammer        | 53        | 2.5%    |
| Broadwell        | 46        | 2.17%   |
| TigerLake        | 44        | 2.07%   |
| Bobcat           | 40        | 1.89%   |
| Zen+             | 35        | 1.65%   |
| Puma             | 33        | 1.56%   |
| Goldmont plus    | 32        | 1.51%   |
| Excavator        | 27        | 1.27%   |
| CometLake        | 27        | 1.27%   |
| Zen 2            | 26        | 1.23%   |
| Icelake          | 26        | 1.23%   |
| Jaguar           | 21        | 0.99%   |
| Unknown          | 21        | 0.99%   |
| Zen 3            | 16        | 0.75%   |
| Goldmont         | 15        | 0.71%   |
| Zen              | 14        | 0.66%   |
| K10 Llano        | 14        | 0.66%   |
| Piledriver       | 12        | 0.57%   |
| K8 & K10 hybrid  | 11        | 0.52%   |
| NetBurst         | 10        | 0.47%   |
| K10              | 10        | 0.47%   |
| Steamroller      | 5         | 0.24%   |
| Nehalem          | 5         | 0.24%   |
| Tremont          | 2         | 0.09%   |
| K6               | 2         | 0.09%   |
| Alderlake Hybrid | 2         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1513      | 61.01%  |
| AMD                              | 491       | 19.8%   |
| Nvidia                           | 443       | 17.86%  |
| Silicon Integrated Systems [SiS] | 20        | 0.81%   |
| VIA Technologies                 | 12        | 0.48%   |
| S3 Graphics                      | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 155       | 5.79%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 144       | 5.38%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 119       | 4.44%   |
| Intel Core Processor Integrated Graphics Controller                                      | 95        | 3.55%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 87        | 3.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 83        | 3.1%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 83        | 3.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 70        | 2.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 69        | 2.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 57        | 2.13%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 54        | 2.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 51        | 1.9%    |
| Intel UHD Graphics 620                                                                   | 50        | 1.87%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 47        | 1.76%   |
| Intel HD Graphics 620                                                                    | 46        | 1.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 45        | 1.68%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 42        | 1.57%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 39        | 1.46%   |
| Intel HD Graphics 5500                                                                   | 37        | 1.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 36        | 1.34%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 33        | 1.23%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 29        | 1.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 28        | 1.05%   |
| AMD Renoir                                                                               | 26        | 0.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 25        | 0.93%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 24        | 0.9%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 20        | 0.75%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 19        | 0.71%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 19        | 0.71%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 17        | 0.63%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 17        | 0.63%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 16        | 0.6%    |
| Intel HD Graphics 630                                                                    | 16        | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 0.56%   |
| Intel HD Graphics 500                                                                    | 15        | 0.56%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 15        | 0.56%   |
| AMD Lucienne                                                                             | 15        | 0.56%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 14        | 0.52%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 14        | 0.52%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 14        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1164      | 54.93%  |
| 1 x AMD         | 370       | 17.46%  |
| Intel + Nvidia  | 265       | 12.51%  |
| 1 x Nvidia      | 160       | 7.55%   |
| Intel + AMD     | 76        | 3.59%   |
| 2 x AMD         | 27        | 1.27%   |
| 1 x SiS         | 20        | 0.94%   |
| AMD + Nvidia    | 18        | 0.85%   |
| 1 x VIA         | 12        | 0.57%   |
| Other           | 5         | 0.24%   |
| 2 x Intel       | 1         | 0.05%   |
| 1 x S3 Graphics | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1845      | 86.74%  |
| Proprietary | 205       | 9.64%   |
| Unknown     | 77        | 3.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1224      | 57.06%  |
| 0.01-0.5   | 450       | 20.98%  |
| 1.01-2.0   | 221       | 10.3%   |
| 0.51-1.0   | 129       | 6.01%   |
| 3.01-4.0   | 85        | 3.96%   |
| 5.01-6.0   | 21        | 0.98%   |
| 7.01-8.0   | 8         | 0.37%   |
| 2.01-3.0   | 5         | 0.23%   |
| 8.01-16.0  | 2         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 425       | 19.28%  |
| LG Display              | 336       | 15.25%  |
| Samsung Electronics     | 305       | 13.84%  |
| Chimei Innolux          | 218       | 9.89%   |
| BOE                     | 198       | 8.98%   |
| Chi Mei Optoelectronics | 96        | 4.36%   |
| LG Philips              | 70        | 3.18%   |
| Lenovo                  | 69        | 3.13%   |
| Apple                   | 38        | 1.72%   |
| HannStar                | 34        | 1.54%   |
| Dell                    | 34        | 1.54%   |
| Goldstar                | 32        | 1.45%   |
| InfoVision              | 28        | 1.27%   |
| Sharp                   | 25        | 1.13%   |
| CPT                     | 23        | 1.04%   |
| Acer                    | 21        | 0.95%   |
| PANDA                   | 17        | 0.77%   |
| BenQ                    | 16        | 0.73%   |
| Philips                 | 15        | 0.68%   |
| Hewlett-Packard         | 15        | 0.68%   |
| Ancor Communications    | 14        | 0.64%   |
| Sony                    | 13        | 0.59%   |
| ViewSonic               | 11        | 0.5%    |
| Toshiba                 | 11        | 0.5%    |
| Quanta Display          | 11        | 0.5%    |
| AOC                     | 9         | 0.41%   |
| Iiyama                  | 8         | 0.36%   |
| CSO                     | 8         | 0.36%   |
| Seiko/Epson             | 7         | 0.32%   |
| InnoLux Display         | 7         | 0.32%   |
| Panasonic               | 5         | 0.23%   |
| Nvidia                  | 5         | 0.23%   |
| LPL                     | 5         | 0.23%   |
| Vizio                   | 4         | 0.18%   |
| LGD                     | 4         | 0.18%   |
| Fujitsu Siemens         | 4         | 0.18%   |
| Lenovo Group Limited    | 3         | 0.14%   |
| KDC                     | 3         | 0.14%   |
| IBM                     | 3         | 0.14%   |
| Eizo                    | 3         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 22        | 0.99%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 20        | 0.9%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 18        | 0.81%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 16        | 0.72%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 16        | 0.72%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 13        | 0.58%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 11        | 0.49%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.49%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 11        | 0.49%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 10        | 0.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 10        | 0.45%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 10        | 0.45%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 10        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 9         | 0.4%    |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 9         | 0.4%    |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 8         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 8         | 0.36%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 8         | 0.36%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 8         | 0.36%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 8         | 0.36%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 8         | 0.36%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 7         | 0.31%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 7         | 0.31%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 7         | 0.31%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 7         | 0.31%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 7         | 0.31%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 7         | 0.31%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 344x193mm 15.5-inch             | 7         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 7         | 0.31%   |
| AU Optronics LCD Monitor AUO205C 1366x768 256x144mm 11.6-inch            | 7         | 0.31%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 7         | 0.31%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 6         | 0.27%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 6         | 0.27%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 6         | 0.27%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 6         | 0.27%   |
| Lenovo LCD Monitor LEN4050 1280x800 331x207mm 15.4-inch                  | 6         | 0.27%   |
| Lenovo LCD Monitor LEN4020 1024x768 286x214mm 14.1-inch                  | 6         | 0.27%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                     | 6         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 758       | 35.62%  |
| 1920x1080 (FHD)    | 604       | 28.38%  |
| 1280x800 (WXGA)    | 245       | 11.51%  |
| 1600x900 (HD+)     | 139       | 6.53%   |
| 1440x900 (WXGA+)   | 80        | 3.76%   |
| 1024x600           | 67        | 3.15%   |
| 3840x2160 (4K)     | 46        | 2.16%   |
| 1680x1050 (WSXGA+) | 30        | 1.41%   |
| 1920x1200 (WUXGA)  | 27        | 1.27%   |
| 1280x1024 (SXGA)   | 23        | 1.08%   |
| 2560x1440 (QHD)    | 21        | 0.99%   |
| 1024x768 (XGA)     | 18        | 0.85%   |
| 2560x1600          | 7         | 0.33%   |
| 1360x768           | 7         | 0.33%   |
| 1920x540           | 5         | 0.23%   |
| 1400x1050          | 5         | 0.23%   |
| 3840x1080          | 4         | 0.19%   |
| 3200x1800 (QHD+)   | 4         | 0.19%   |
| 2880x1800          | 4         | 0.19%   |
| 2160x1440          | 4         | 0.19%   |
| Unknown            | 4         | 0.19%   |
| 2288x1287          | 3         | 0.14%   |
| 3840x2400          | 2         | 0.09%   |
| 3440x1440          | 2         | 0.09%   |
| 2560x1080          | 2         | 0.09%   |
| 1600x1200          | 2         | 0.09%   |
| 800x480            | 1         | 0.05%   |
| 3840x1200          | 1         | 0.05%   |
| 3600x1080          | 1         | 0.05%   |
| 3120x1050          | 1         | 0.05%   |
| 3072x1920          | 1         | 0.05%   |
| 3000x2000          | 1         | 0.05%   |
| 2520x1680          | 1         | 0.05%   |
| 2304x1440          | 1         | 0.05%   |
| 1920x515           | 1         | 0.05%   |
| 1920x1280          | 1         | 0.05%   |
| 1680x945           | 1         | 0.05%   |
| 1366x912           | 1         | 0.05%   |
| 1280x768           | 1         | 0.05%   |
| 1280x720 (HD)      | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 914       | 41.43%  |
| 14      | 293       | 13.28%  |
| 13      | 244       | 11.06%  |
| 17      | 189       | 8.57%   |
| 12      | 71        | 3.22%   |
| 10      | 71        | 3.22%   |
| 11      | 63        | 2.86%   |
| 24      | 51        | 2.31%   |
| Unknown | 48        | 2.18%   |
| 21      | 44        | 1.99%   |
| 27      | 41        | 1.86%   |
| 23      | 41        | 1.86%   |
| 18      | 25        | 1.13%   |
| 19      | 18        | 0.82%   |
| 16      | 13        | 0.59%   |
| 22      | 11        | 0.5%    |
| 54      | 9         | 0.41%   |
| 31      | 8         | 0.36%   |
| 20      | 8         | 0.36%   |
| 40      | 5         | 0.23%   |
| 34      | 4         | 0.18%   |
| 26      | 4         | 0.18%   |
| 8       | 4         | 0.18%   |
| 84      | 3         | 0.14%   |
| 72      | 3         | 0.14%   |
| 25      | 3         | 0.14%   |
| 52      | 2         | 0.09%   |
| 48      | 2         | 0.09%   |
| 42      | 2         | 0.09%   |
| 37      | 2         | 0.09%   |
| 32      | 2         | 0.09%   |
| 74      | 1         | 0.05%   |
| 58      | 1         | 0.05%   |
| 57      | 1         | 0.05%   |
| 49      | 1         | 0.05%   |
| 47      | 1         | 0.05%   |
| 39      | 1         | 0.05%   |
| 38      | 1         | 0.05%   |
| 29      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1316      | 60.01%  |
| 201-300     | 324       | 14.77%  |
| 351-400     | 228       | 10.4%   |
| 501-600     | 131       | 5.97%   |
| 401-500     | 87        | 3.97%   |
| Unknown     | 48        | 2.19%   |
| 1001-1500   | 17        | 0.78%   |
| 601-700     | 14        | 0.64%   |
| 801-900     | 9         | 0.41%   |
| 1501-2000   | 7         | 0.32%   |
| 701-800     | 6         | 0.27%   |
| 101-200     | 4         | 0.18%   |
| 901-1000    | 2         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1533      | 76.08%  |
| 16/10   | 372       | 18.46%  |
| Unknown | 36        | 1.79%   |
| 4/3     | 27        | 1.34%   |
| 5/4     | 20        | 0.99%   |
| 3/2     | 16        | 0.79%   |
| 21/9    | 4         | 0.2%    |
| 32/9    | 2         | 0.1%    |
| 6/5     | 1         | 0.05%   |
| 3.73    | 1         | 0.05%   |
| 3.20    | 1         | 0.05%   |
| 1.00    | 1         | 0.05%   |
| 0.62    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 911       | 41.37%  |
| 81-90          | 438       | 19.89%  |
| 121-130        | 139       | 6.31%   |
| 201-250        | 120       | 5.45%   |
| 71-80          | 83        | 3.77%   |
| 41-50          | 71        | 3.22%   |
| 61-70          | 70        | 3.18%   |
| 51-60          | 63        | 2.86%   |
| Unknown        | 48        | 2.18%   |
| 151-200        | 45        | 2.04%   |
| 131-140        | 44        | 2%      |
| 301-350        | 43        | 1.95%   |
| 141-150        | 26        | 1.18%   |
| More than 1000 | 21        | 0.95%   |
| 91-100         | 21        | 0.95%   |
| 251-300        | 16        | 0.73%   |
| 351-500        | 15        | 0.68%   |
| 501-1000       | 14        | 0.64%   |
| 111-120        | 10        | 0.45%   |
| 1-40           | 4         | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 866       | 40.07%  |
| 121-160       | 651       | 30.12%  |
| 51-100        | 472       | 21.84%  |
| 161-240       | 74        | 3.42%   |
| Unknown       | 48        | 2.22%   |
| More than 240 | 28        | 1.3%    |
| 1-50          | 22        | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1818      | 84.13%  |
| 2     | 254       | 11.75%  |
| 0     | 69        | 3.19%   |
| 3     | 18        | 0.83%   |
| 4     | 2         | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1038      | 29.57%  |
| Intel                             | 952       | 27.12%  |
| Qualcomm Atheros                  | 599       | 17.07%  |
| Broadcom                          | 321       | 9.15%   |
| Marvell Technology Group          | 104       | 2.96%   |
| Broadcom Limited                  | 87        | 2.48%   |
| Ralink                            | 49        | 1.4%    |
| Silicon Integrated Systems [SiS]  | 28        | 0.8%    |
| TP-Link                           | 27        | 0.77%   |
| Ralink Technology                 | 26        | 0.74%   |
| Nvidia                            | 26        | 0.74%   |
| Samsung Electronics               | 21        | 0.6%    |
| JMicron Technology                | 20        | 0.57%   |
| MediaTek                          | 19        | 0.54%   |
| Sierra Wireless                   | 15        | 0.43%   |
| Huawei Technologies               | 15        | 0.43%   |
| Ericsson Business Mobile Networks | 15        | 0.43%   |
| Attansic Technology               | 15        | 0.43%   |
| VIA Technologies                  | 11        | 0.31%   |
| Dell                              | 9         | 0.26%   |
| Qualcomm Atheros Communications   | 8         | 0.23%   |
| Xiaomi                            | 7         | 0.2%    |
| ASIX Electronics                  | 7         | 0.2%    |
| AMD                               | 7         | 0.2%    |
| Qualcomm                          | 6         | 0.17%   |
| Lenovo                            | 6         | 0.17%   |
| Fibocom                           | 6         | 0.17%   |
| D-Link System                     | 5         | 0.14%   |
| ZyDAS                             | 4         | 0.11%   |
| ULi Electronics                   | 4         | 0.11%   |
| Hewlett-Packard                   | 4         | 0.11%   |
| DisplayLink                       | 4         | 0.11%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.09%   |
| Toshiba                           | 3         | 0.09%   |
| Motorola PCS                      | 3         | 0.09%   |
| Edimax Technology                 | 3         | 0.09%   |
| ASUSTek Computer                  | 3         | 0.09%   |
| Spreadtrum Communications         | 2         | 0.06%   |
| Sitecom Europe                    | 2         | 0.06%   |
| NetGear                           | 2         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 543       | 12.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 274       | 6.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 107       | 2.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 95        | 2.24%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 94        | 2.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 87        | 2.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 80        | 1.89%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 71        | 1.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 66        | 1.56%   |
| Intel Wireless 7260                                                     | 65        | 1.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 61        | 1.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 57        | 1.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 53        | 1.25%   |
| Intel Wireless 8265 / 8275                                              | 50        | 1.18%   |
| Intel Wireless 7265                                                     | 47        | 1.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 46        | 1.09%   |
| Intel Wi-Fi 6 AX200                                                     | 42        | 0.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 41        | 0.97%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 39        | 0.92%   |
| Intel Wireless 8260                                                     | 37        | 0.87%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 34        | 0.8%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 32        | 0.76%   |
| Intel Wi-Fi 6 AX201                                                     | 32        | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 31        | 0.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 30        | 0.71%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 30        | 0.71%   |
| Intel Wireless 3165                                                     | 30        | 0.71%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 30        | 0.71%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 28        | 0.66%   |
| Intel Centrino Advanced-N 6200                                          | 28        | 0.66%   |
| Intel 82577LM Gigabit Network Connection                                | 27        | 0.64%   |
| Broadcom BCM43142 802.11b/g/n                                           | 27        | 0.64%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 26        | 0.61%   |
| Intel 82567LM Gigabit Network Connection                                | 26        | 0.61%   |
| Intel Ethernet Connection I219-LM                                       | 25        | 0.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 25        | 0.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 24        | 0.57%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 24        | 0.57%   |
| Intel Centrino Ultimate-N 6300                                          | 24        | 0.57%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 23        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 897       | 40.81%  |
| Qualcomm Atheros                      | 519       | 23.61%  |
| Realtek Semiconductor                 | 325       | 14.79%  |
| Broadcom                              | 224       | 10.19%  |
| Ralink                                | 49        | 2.23%   |
| Broadcom Limited                      | 47        | 2.14%   |
| Ralink Technology                     | 26        | 1.18%   |
| TP-Link                               | 22        | 1%      |
| MediaTek                              | 16        | 0.73%   |
| Sierra Wireless                       | 15        | 0.68%   |
| Qualcomm Atheros Communications       | 8         | 0.36%   |
| Qualcomm                              | 6         | 0.27%   |
| Fibocom                               | 6         | 0.27%   |
| Dell                                  | 6         | 0.27%   |
| D-Link System                         | 5         | 0.23%   |
| ZyDAS                                 | 4         | 0.18%   |
| Edimax Technology                     | 3         | 0.14%   |
| Sitecom Europe                        | 2         | 0.09%   |
| NetGear                               | 2         | 0.09%   |
| Linksys                               | 2         | 0.09%   |
| Hewlett-Packard                       | 2         | 0.09%   |
| D-Link                                | 2         | 0.09%   |
| ASUSTek Computer                      | 2         | 0.09%   |
| Winbond Electronics                   | 1         | 0.05%   |
| TRENDnet                              | 1         | 0.05%   |
| Toshiba                               | 1         | 0.05%   |
| Texas Instruments                     | 1         | 0.05%   |
| Micro Star International              | 1         | 0.05%   |
| BUFFALO                               | 1         | 0.05%   |
| AVM                                   | 1         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 107       | 4.81%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 94        | 4.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 87        | 3.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 80        | 3.6%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 71        | 3.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 66        | 2.97%   |
| Intel Wireless 7260                                                           | 65        | 2.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 61        | 2.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 57        | 2.56%   |
| Intel Wireless 8265 / 8275                                                    | 50        | 2.25%   |
| Intel Wireless 7265                                                           | 47        | 2.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 46        | 2.07%   |
| Intel Wi-Fi 6 AX200                                                           | 42        | 1.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 41        | 1.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 39        | 1.75%   |
| Intel Wireless 8260                                                           | 37        | 1.66%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 34        | 1.53%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 32        | 1.44%   |
| Intel Wi-Fi 6 AX201                                                           | 32        | 1.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 31        | 1.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 30        | 1.35%   |
| Intel Wireless 3165                                                           | 30        | 1.35%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 30        | 1.35%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 28        | 1.26%   |
| Intel Centrino Advanced-N 6200                                                | 28        | 1.26%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 27        | 1.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 25        | 1.12%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 24        | 1.08%   |
| Intel Centrino Ultimate-N 6300                                                | 24        | 1.08%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 23        | 1.03%   |
| Intel WiFi Link 5100                                                          | 22        | 0.99%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 21        | 0.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 21        | 0.94%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 20        | 0.9%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 20        | 0.9%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 20        | 0.9%    |
| Intel Centrino Advanced-N 6235                                                | 19        | 0.85%   |
| Intel Wireless-AC 9260                                                        | 18        | 0.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 17        | 0.76%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 16        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 906       | 47.09%  |
| Intel                            | 402       | 20.89%  |
| Qualcomm Atheros                 | 160       | 8.32%   |
| Broadcom                         | 132       | 6.86%   |
| Marvell Technology Group         | 104       | 5.41%   |
| Broadcom Limited                 | 41        | 2.13%   |
| Silicon Integrated Systems [SiS] | 26        | 1.35%   |
| Nvidia                           | 25        | 1.3%    |
| Samsung Electronics              | 20        | 1.04%   |
| JMicron Technology               | 20        | 1.04%   |
| Attansic Technology              | 15        | 0.78%   |
| VIA Technologies                 | 11        | 0.57%   |
| Huawei Technologies              | 8         | 0.42%   |
| Xiaomi                           | 7         | 0.36%   |
| ASIX Electronics                 | 7         | 0.36%   |
| Lenovo                           | 6         | 0.31%   |
| TP-Link                          | 5         | 0.26%   |
| MediaTek                         | 4         | 0.21%   |
| DisplayLink                      | 4         | 0.21%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.1%    |
| Spreadtrum Communications        | 2         | 0.1%    |
| Motorola PCS                     | 2         | 0.1%    |
| LG Electronics                   | 2         | 0.1%    |
| Hewlett-Packard                  | 2         | 0.1%    |
| Apple                            | 2         | 0.1%    |
| ULi Electronics                  | 1         | 0.05%   |
| OPPO Electronics                 | 1         | 0.05%   |
| National Semiconductor           | 1         | 0.05%   |
| Microchip Technology             | 1         | 0.05%   |
| ICS Advent                       | 1         | 0.05%   |
| HTC (High Tech Computer)         | 1         | 0.05%   |
| Foxconn / Hon Hai                | 1         | 0.05%   |
| ASUSTek Computer                 | 1         | 0.05%   |
| Aquantia                         | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 543       | 28.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 274       | 14.2%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 95        | 4.92%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 53        | 2.75%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 30        | 1.55%   |
| Intel 82577LM Gigabit Network Connection                                       | 27        | 1.4%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 26        | 1.35%   |
| Intel 82567LM Gigabit Network Connection                                       | 26        | 1.35%   |
| Intel Ethernet Connection I219-LM                                              | 25        | 1.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 24        | 1.24%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 22        | 1.14%   |
| Intel Ethernet Connection I217-LM                                              | 22        | 1.14%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 21        | 1.09%   |
| Intel Ethernet Connection (4) I219-LM                                          | 19        | 0.98%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 19        | 0.98%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 18        | 0.93%   |
| Intel 82566MM Gigabit Network Connection                                       | 18        | 0.93%   |
| Intel Ethernet Connection I218-LM                                              | 17        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 16        | 0.83%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 15        | 0.78%   |
| Intel PRO/100 VE Network Connection                                            | 15        | 0.78%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 15        | 0.78%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 13        | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                                          | 13        | 0.67%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 13        | 0.67%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 12        | 0.62%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 12        | 0.62%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 12        | 0.62%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 12        | 0.62%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 11        | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 11        | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 11        | 0.57%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 11        | 0.57%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 11        | 0.57%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 11        | 0.57%   |
| Intel Ethernet Connection (4) I219-V                                           | 11        | 0.57%   |
| Intel Ethernet Connection (10) I219-V                                          | 11        | 0.57%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 11        | 0.57%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 10        | 0.52%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 10        | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2063      | 51.51%  |
| Ethernet | 1859      | 46.42%  |
| Modem    | 82        | 2.05%   |
| Unknown  | 1         | 0.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1731      | 77.9%   |
| Ethernet | 491       | 22.1%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1734      | 81.56%  |
| 1     | 336       | 15.8%   |
| 0     | 47        | 2.21%   |
| 3     | 9         | 0.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1828      | 84.87%  |
| Yes  | 326       | 15.13%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 490       | 37.29%  |
| Broadcom                        | 141       | 10.73%  |
| Qualcomm Atheros Communications | 134       | 10.2%   |
| Realtek Semiconductor           | 126       | 9.59%   |
| Foxconn / Hon Hai               | 56        | 4.26%   |
| Lite-On Technology              | 54        | 4.11%   |
| Dell                            | 53        | 4.03%   |
| Hewlett-Packard                 | 49        | 3.73%   |
| IMC Networks                    | 48        | 3.65%   |
| Apple                           | 32        | 2.44%   |
| Cambridge Silicon Radio         | 29        | 2.21%   |
| Toshiba                         | 20        | 1.52%   |
| Ralink                          | 16        | 1.22%   |
| ASUSTek Computer                | 16        | 1.22%   |
| Alps Electric                   | 13        | 0.99%   |
| Realtek                         | 7         | 0.53%   |
| Ralink Technology               | 6         | 0.46%   |
| Foxconn International           | 6         | 0.46%   |
| Chicony Electronics             | 4         | 0.3%    |
| MediaTek                        | 3         | 0.23%   |
| Taiyo Yuden                     | 2         | 0.15%   |
| Qcom                            | 2         | 0.15%   |
| Integrated System Solution      | 2         | 0.15%   |
| USI                             | 1         | 0.08%   |
| Syntek                          | 1         | 0.08%   |
| Micro Star International        | 1         | 0.08%   |
| Edimax Technology               | 1         | 0.08%   |
| Askey Computer                  | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 233       | 17.72%  |
| Intel AX201 Bluetooth                                                               | 74        | 5.63%   |
| Realtek Bluetooth Radio                                                             | 73        | 5.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 58        | 4.41%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 55        | 4.18%   |
| Intel AX200 Bluetooth                                                               | 40        | 3.04%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 38        | 2.89%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 34        | 2.59%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 32        | 2.43%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 29        | 2.21%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 26        | 1.98%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 23        | 1.75%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 21        | 1.6%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 20        | 1.52%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 18        | 1.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 17        | 1.29%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 17        | 1.29%   |
| Ralink RT3290 Bluetooth                                                             | 16        | 1.22%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 15        | 1.14%   |
| IMC Networks Bluetooth Device                                                       | 15        | 1.14%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 14        | 1.06%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 13        | 0.99%   |
| Lite-On Bluetooth Device                                                            | 13        | 0.99%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 13        | 0.99%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 13        | 0.99%   |
| Broadcom BCM2045 Bluetooth                                                          | 13        | 0.99%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 12        | 0.91%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 12        | 0.91%   |
| Dell DW375 Bluetooth Module                                                         | 12        | 0.91%   |
| Apple Bluetooth Host Controller                                                     | 12        | 0.91%   |
| Toshiba Integrated Bluetooth HCI                                                    | 11        | 0.84%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 11        | 0.84%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 11        | 0.84%   |
| Apple Bluetooth HCI                                                                 | 11        | 0.84%   |
| Realtek RTL8723B Bluetooth                                                          | 10        | 0.76%   |
| Intel AX210 Bluetooth                                                               | 10        | 0.76%   |
| IMC Networks Bluetooth Radio                                                        | 10        | 0.76%   |
| Dell Wireless 360 Bluetooth                                                         | 10        | 0.76%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 10        | 0.76%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 10        | 0.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1682      | 69.25%  |
| AMD                              | 375       | 15.44%  |
| Nvidia                           | 212       | 8.73%   |
| Silicon Integrated Systems [SiS] | 31        | 1.28%   |
| C-Media Electronics              | 21        | 0.86%   |
| VIA Technologies                 | 13        | 0.54%   |
| Logitech                         | 11        | 0.45%   |
| GN Netcom                        | 6         | 0.25%   |
| Texas Instruments                | 5         | 0.21%   |
| Plantronics                      | 5         | 0.21%   |
| Lenovo                           | 5         | 0.21%   |
| Generalplus Technology           | 5         | 0.21%   |
| ULi Electronics                  | 4         | 0.16%   |
| Realtek Semiconductor            | 4         | 0.16%   |
| JMTek                            | 4         | 0.16%   |
| Focusrite-Novation               | 4         | 0.16%   |
| M-Audio                          | 3         | 0.12%   |
| Textech International            | 2         | 0.08%   |
| Sennheiser Communications        | 2         | 0.08%   |
| Avid Technology                  | 2         | 0.08%   |
| Audio-Technica                   | 2         | 0.08%   |
| ASUSTek Computer                 | 2         | 0.08%   |
| Apple                            | 2         | 0.08%   |
| ZOOM                             | 1         | 0.04%   |
| XMOS                             | 1         | 0.04%   |
| Tenx Technology                  | 1         | 0.04%   |
| TEAC                             | 1         | 0.04%   |
| TC Electronic                    | 1         | 0.04%   |
| Syntek                           | 1         | 0.04%   |
| Roland                           | 1         | 0.04%   |
| RODE Microphones                 | 1         | 0.04%   |
| QinHeng Electronics              | 1         | 0.04%   |
| PreSonus Audio Electronics       | 1         | 0.04%   |
| Numark                           | 1         | 0.04%   |
| Native Instruments               | 1         | 0.04%   |
| Microsoft                        | 1         | 0.04%   |
| KORG                             | 1         | 0.04%   |
| eMPIA Technology                 | 1         | 0.04%   |
| Elite Silicon                    | 1         | 0.04%   |
| Earth Computer Technologies      | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 194       | 6.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 174       | 6.11%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 167       | 5.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 153       | 5.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 135       | 4.74%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 134       | 4.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 129       | 4.53%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 104       | 3.65%   |
| AMD FCH Azalia Controller                                                                         | 103       | 3.61%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 70        | 2.46%   |
| Intel 8 Series HD Audio Controller                                                                | 70        | 2.46%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 62        | 2.18%   |
| AMD Kabini HDMI/DP Audio                                                                          | 62        | 2.18%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 52        | 1.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 50        | 1.75%   |
| Intel Cannon Lake PCH cAVS                                                                        | 48        | 1.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 47        | 1.65%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 46        | 1.61%   |
| Intel Broadwell-U Audio Controller                                                                | 46        | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 45        | 1.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 44        | 1.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 44        | 1.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 41        | 1.44%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 32        | 1.12%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 32        | 1.12%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 32        | 1.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 31        | 1.09%   |
| AMD Wrestler HDMI Audio                                                                           | 31        | 1.09%   |
| Intel Comet Lake PCH cAVS                                                                         | 26        | 0.91%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 26        | 0.91%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 21        | 0.74%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 21        | 0.74%   |
| Nvidia High Definition Audio Controller                                                           | 20        | 0.7%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 20        | 0.7%    |
| Intel CM238 HD Audio Controller                                                                   | 20        | 0.7%    |
| AMD High Definition Audio Controller                                                              | 19        | 0.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 17        | 0.6%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 15        | 0.53%   |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 15        | 0.53%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 14        | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 305       | 26.8%   |
| SK hynix                                         | 230       | 20.21%  |
| Unknown                                          | 155       | 13.62%  |
| Micron Technology                                | 118       | 10.37%  |
| Kingston                                         | 100       | 8.79%   |
| Crucial                                          | 41        | 3.6%    |
| Elpida                                           | 31        | 2.72%   |
| Ramaxel Technology                               | 26        | 2.28%   |
| Unknown (ABCD)                                   | 18        | 1.58%   |
| A-DATA Technology                                | 16        | 1.41%   |
| Nanya Technology                                 | 15        | 1.32%   |
| Smart                                            | 11        | 0.97%   |
| Corsair                                          | 11        | 0.97%   |
| G.Skill                                          | 10        | 0.88%   |
| Goodram                                          | 6         | 0.53%   |
| Transcend                                        | 4         | 0.35%   |
| 48spaces                                         | 3         | 0.26%   |
| Teikon                                           | 2         | 0.18%   |
| Team                                             | 2         | 0.18%   |
| Super Talent                                     | 2         | 0.18%   |
| Qimonda                                          | 2         | 0.18%   |
| High Bridge                                      | 2         | 0.18%   |
| Avant                                            | 2         | 0.18%   |
| Apacer                                           | 2         | 0.18%   |
| Unknown                                          | 2         | 0.18%   |
| V-GeN                                            | 1         | 0.09%   |
| V-Color                                          | 1         | 0.09%   |
| Unknown (7F7F7F7F7F7F6B00)                       | 1         | 0.09%   |
| Unknown (0x36345431323830323145444C335342322020) | 1         | 0.09%   |
| Unknown (0x0043415455000000)                     | 1         | 0.09%   |
| Unifosa                                          | 1         | 0.09%   |
| Timetec                                          | 1         | 0.09%   |
| Smart Brazil                                     | 1         | 0.09%   |
| SHARETRONIC                                      | 1         | 0.09%   |
| Patriot                                          | 1         | 0.09%   |
| Neo Forza                                        | 1         | 0.09%   |
| Memox                                            | 1         | 0.09%   |
| Foxline                                          | 1         | 0.09%   |
| fef5                                             | 1         | 0.09%   |
| Essencore                                        | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 17        | 1.41%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 17        | 1.41%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 16        | 1.33%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 15        | 1.24%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 14        | 1.16%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 1.16%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 13        | 1.08%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 13        | 1.08%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 11        | 0.91%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.91%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 10        | 0.83%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.75%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.75%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.75%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 9         | 0.75%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.75%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.75%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 8         | 0.66%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 8         | 0.66%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 8         | 0.66%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.66%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 8         | 0.66%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 7         | 0.58%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.58%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.58%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.58%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 7         | 0.58%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 6         | 0.5%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 6         | 0.5%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.5%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 6         | 0.5%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 0.5%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 6         | 0.5%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 6         | 0.5%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.41%   |
| SK hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 5         | 0.41%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 5         | 0.41%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 0.41%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 5         | 0.41%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 406       | 41.39%  |
| DDR4    | 337       | 34.35%  |
| DDR2    | 107       | 10.91%  |
| LPDDR4  | 46        | 4.69%   |
| SDRAM   | 27        | 2.75%   |
| LPDDR3  | 27        | 2.75%   |
| Unknown | 11        | 1.12%   |
| DDR     | 10        | 1.02%   |
| DRAM    | 7         | 0.71%   |
| DDR5    | 2         | 0.2%    |
| LPDDR5  | 1         | 0.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 894       | 92.26%  |
| Row Of Chips | 55        | 5.68%   |
| Chip         | 9         | 0.93%   |
| Unknown      | 6         | 0.62%   |
| DIMM         | 5         | 0.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 338       | 31.74%  |
| 8192    | 316       | 29.67%  |
| 2048    | 220       | 20.66%  |
| 16384   | 98        | 9.2%    |
| 1024    | 67        | 6.29%   |
| 32768   | 17        | 1.6%    |
| 512     | 6         | 0.56%   |
| 1536    | 1         | 0.09%   |
| 256     | 1         | 0.09%   |
| Unknown | 1         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 267       | 25.85%  |
| 2667    | 179       | 17.33%  |
| 3200    | 108       | 10.45%  |
| 667     | 73        | 7.07%   |
| 2400    | 72        | 6.97%   |
| 1334    | 60        | 5.81%   |
| 1333    | 51        | 4.94%   |
| 2133    | 36        | 3.48%   |
| Unknown | 36        | 3.48%   |
| 800     | 22        | 2.13%   |
| 4199    | 17        | 1.65%   |
| 1067    | 17        | 1.65%   |
| 3266    | 13        | 1.26%   |
| 4267    | 12        | 1.16%   |
| 1066    | 11        | 1.06%   |
| 533     | 11        | 1.06%   |
| 1867    | 10        | 0.97%   |
| 2048    | 9         | 0.87%   |
| 975     | 8         | 0.77%   |
| 4800    | 3         | 0.29%   |
| 4266    | 3         | 0.29%   |
| 3733    | 3         | 0.29%   |
| 1866    | 3         | 0.29%   |
| 400     | 2         | 0.19%   |
| 333     | 2         | 0.19%   |
| 8400    | 1         | 0.1%    |
| 6400    | 1         | 0.1%    |
| 2134    | 1         | 0.1%    |
| 1776    | 1         | 0.1%    |
| 133     | 1         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 8         | 34.78%  |
| Canon                 | 7         | 30.43%  |
| Brother Industries    | 3         | 13.04%  |
| Prolific Technology   | 2         | 8.7%    |
| Seiko Epson           | 1         | 4.35%   |
| Lexmark International | 1         | 4.35%   |
| Kyocera               | 1         | 4.35%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port   | 2         | 8.33%   |
| Seiko Epson L220 Series         | 1         | 4.17%   |
| Lexmark International E360d     | 1         | 4.17%   |
| Kyocera Mita FS-920             | 1         | 4.17%   |
| HP PSC 750xi                    | 1         | 4.17%   |
| HP OfficeJet Reflash            | 1         | 4.17%   |
| HP LaserJet P1005               | 1         | 4.17%   |
| HP LaserJet 1320                | 1         | 4.17%   |
| HP LaserJet 1020                | 1         | 4.17%   |
| HP LaserJet 1015                | 1         | 4.17%   |
| HP LaserJet 1012                | 1         | 4.17%   |
| HP DeskJet F2100 Printer series | 1         | 4.17%   |
| HP DeskJet 3700 series          | 1         | 4.17%   |
| Canon TS5100 series             | 1         | 4.17%   |
| Canon TS3300 series             | 1         | 4.17%   |
| Canon TS3100 series             | 1         | 4.17%   |
| Canon PIXMA MX320 series        | 1         | 4.17%   |
| Canon MF3200 series             | 1         | 4.17%   |
| Canon LBP6230/6240              | 1         | 4.17%   |
| Canon LBP6000                   | 1         | 4.17%   |
| Brother MFC-L2710DW series      | 1         | 4.17%   |
| Brother HL-L2320D series        | 1         | 4.17%   |
| Brother HL-2140 series          | 1         | 4.17%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 4         | 66.67%  |
| Seiko Epson     | 1         | 16.67%  |
| Hewlett-Packard | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 1         | 16.67%  |
| HP ScanJet 3570c                                 | 1         | 16.67%  |
| Canon CanoScan N650U/N656U                       | 1         | 16.67%  |
| Canon CanoScan LIDE 25                           | 1         | 16.67%  |
| Canon CanoScan LiDE 220                          | 1         | 16.67%  |
| Canon CanoScan LiDE 100                          | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 484       | 28.4%   |
| Microdia                               | 134       | 7.86%   |
| IMC Networks                           | 126       | 7.39%   |
| Realtek Semiconductor                  | 119       | 6.98%   |
| Suyin                                  | 118       | 6.92%   |
| Acer                                   | 106       | 6.22%   |
| Sunplus Innovation Technology          | 84        | 4.93%   |
| Quanta                                 | 66        | 3.87%   |
| Cheng Uei Precision Industry (Foxlink) | 65        | 3.81%   |
| Alcor Micro                            | 42        | 2.46%   |
| Silicon Motion                         | 41        | 2.41%   |
| Ricoh                                  | 39        | 2.29%   |
| Lite-On Technology                     | 34        | 2%      |
| Syntek                                 | 33        | 1.94%   |
| Apple                                  | 30        | 1.76%   |
| Bison Electronics                      | 18        | 1.06%   |
| Samsung Electronics                    | 16        | 0.94%   |
| Logitech                               | 16        | 0.94%   |
| Lenovo                                 | 15        | 0.88%   |
| ALi                                    | 15        | 0.88%   |
| Luxvisions Innotech Limited            | 14        | 0.82%   |
| Z-Star Microelectronics                | 13        | 0.76%   |
| Importek                               | 10        | 0.59%   |
| Primax Electronics                     | 9         | 0.53%   |
| USB Camera                             | 6         | 0.35%   |
| OmniVision Technologies                | 6         | 0.35%   |
| DigiTech                               | 6         | 0.35%   |
| Sonix Technology                       | 4         | 0.23%   |
| GEMBIRD                                | 4         | 0.23%   |
| Unknown                                | 2         | 0.12%   |
| Sunplus Technology                     | 2         | 0.12%   |
| Microsoft                              | 2         | 0.12%   |
| MacroSilicon                           | 2         | 0.12%   |
| Genesys Logic                          | 2         | 0.12%   |
| Cubeternet                             | 2         | 0.12%   |
| YGTek                                  | 1         | 0.06%   |
| Xiongmai                               | 1         | 0.06%   |
| USB Camera CS                          | 1         | 0.06%   |
| Tobii AB                               | 1         | 0.06%   |
| SunplusIT                              | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 82        | 4.8%    |
| Realtek Integrated_Webcam_HD                     | 35        | 2.05%   |
| Microdia Integrated_Webcam_HD                    | 31        | 1.81%   |
| Chicony HD WebCam                                | 30        | 1.75%   |
| Chicony USB 2.0 Camera                           | 26        | 1.52%   |
| IMC Networks USB2.0 HD UVC WebCam                | 24        | 1.4%    |
| Sunplus Integrated_Webcam_HD                     | 21        | 1.23%   |
| IMC Networks Integrated Camera                   | 21        | 1.23%   |
| Chicony TOSHIBA Web Camera - HD                  | 20        | 1.17%   |
| Chicony Lenovo EasyCamera                        | 18        | 1.05%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 18        | 1.05%   |
| Suyin HP TrueVision HD                           | 17        | 0.99%   |
| Chicony HP Truevision HD                         | 17        | 0.99%   |
| Acer Lenovo EasyCamera                           | 17        | 0.99%   |
| Microdia Sonix USB 2.0 Camera                    | 16        | 0.94%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 16        | 0.94%   |
| Samsung Galaxy A5 (MTP)                          | 15        | 0.88%   |
| Chicony USB2.0 VGA UVC WebCam                    | 15        | 0.88%   |
| Alcor Micro USB 2.0 Camera                       | 15        | 0.88%   |
| Microdia Integrated Webcam                       | 14        | 0.82%   |
| Lite-On Integrated Camera                        | 14        | 0.82%   |
| Acer BisonCam, NB Pro                            | 14        | 0.82%   |
| Suyin Acer CrystalEye Webcam                     | 13        | 0.76%   |
| IMC Networks UVC VGA Webcam                      | 13        | 0.76%   |
| Acer SunplusIT Integrated Camera                 | 13        | 0.76%   |
| Acer Integrated Camera                           | 13        | 0.76%   |
| Syntek Lenovo EasyCamera                         | 12        | 0.7%    |
| Sunplus HD WebCam                                | 12        | 0.7%    |
| Realtek USB Camera                               | 12        | 0.7%    |
| Quanta HP Webcam                                 | 12        | 0.7%    |
| Quanta HP TrueVision HD Camera                   | 11        | 0.64%   |
| Lite-On HP HD Camera                             | 11        | 0.64%   |
| Chicony HP HD Camera                             | 11        | 0.64%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 11        | 0.64%   |
| Acer HD Webcam                                   | 11        | 0.64%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 10        | 0.58%   |
| Suyin 1.3M HD WebCam                             | 10        | 0.58%   |
| Realtek Acer 640 x 480 laptop camera             | 10        | 0.58%   |
| Quanta VGA WebCam                                | 10        | 0.58%   |
| Chicony Webcam                                   | 10        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 120       | 37.27%  |
| Synaptics                  | 59        | 18.32%  |
| AuthenTec                  | 54        | 16.77%  |
| Upek                       | 31        | 9.63%   |
| Shenzhen Goodix Technology | 20        | 6.21%   |
| STMicroelectronics         | 19        | 5.9%    |
| LighTuning Technology      | 11        | 3.42%   |
| Elan Microelectronics      | 7         | 2.17%   |
| Focal-systems.Corp         | 1         | 0.31%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 29        | 9.01%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 28        | 8.7%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 27        | 8.39%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 23        | 7.14%   |
| STMicroelectronics Fingerprint Reader                                      | 19        | 5.9%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 15        | 4.66%   |
| Shenzhen Goodix  FingerPrint Device                                        | 15        | 4.66%   |
| AuthenTec AES2810                                                          | 14        | 4.35%   |
| Validity Sensors Fingerprint scanner                                       | 13        | 4.04%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 11        | 3.42%   |
| Validity Sensors VFS491                                                    | 11        | 3.42%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 10        | 3.11%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 2.48%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.48%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 2.48%   |
| AuthenTec AES1600                                                          | 7         | 2.17%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.86%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.86%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.55%   |
| Elan ELAN:Fingerprint                                                      | 5         | 1.55%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.24%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 1.24%   |
| Synaptics  WBDI                                                            | 4         | 1.24%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 1.24%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.93%   |
| LighTuning Fingerprint Reader                                              | 3         | 0.93%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 0.93%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.62%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.62%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 0.62%   |
| Synaptics WBDI Device                                                      | 2         | 0.62%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.62%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.62%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.62%   |
| Elan ELAN:ARM-M4                                                           | 2         | 0.62%   |
| Unknown                                                                    | 2         | 0.62%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.31%   |
| Synaptics UWP WBDI                                                         | 1         | 0.31%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.31%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 65        | 36.93%  |
| Alcor Micro              | 46        | 26.14%  |
| O2 Micro                 | 28        | 15.91%  |
| Upek                     | 17        | 9.66%   |
| Lenovo                   | 15        | 8.52%   |
| Reiner SCT Kartensysteme | 1         | 0.57%   |
| OmniKey                  | 1         | 0.57%   |
| C3PO                     | 1         | 0.57%   |
| Aktiv                    | 1         | 0.57%   |
| Advanced Card Systems    | 1         | 0.57%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 46        | 26.14%  |
| Broadcom BCM5880 Secure Applications Processor                               | 30        | 17.05%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 22        | 12.5%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 17        | 9.66%   |
| Broadcom 5880                                                                | 16        | 9.09%   |
| Lenovo Integrated Smart Card Reader                                          | 15        | 8.52%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 5.68%   |
| Broadcom 58200                                                               | 8         | 4.55%   |
| O2 Micro Oz776 SmartCard Reader                                              | 6         | 3.41%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.57%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.57%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.57%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.57%   |
| Aktiv Rutoken lite                                                           | 1         | 0.57%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.57%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1348      | 62.79%  |
| 1     | 623       | 29.02%  |
| 2     | 147       | 6.85%   |
| 3     | 20        | 0.93%   |
| 4     | 6         | 0.28%   |
| 10    | 1         | 0.05%   |
| 6     | 1         | 0.05%   |
| 5     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 321       | 32.52%  |
| Graphics card            | 205       | 20.77%  |
| Chipcard                 | 171       | 17.33%  |
| Net/wireless             | 81        | 8.21%   |
| Modem                    | 44        | 4.46%   |
| Camera                   | 28        | 2.84%   |
| Bluetooth                | 26        | 2.63%   |
| Storage                  | 24        | 2.43%   |
| Communication controller | 19        | 1.93%   |
| Card reader              | 18        | 1.82%   |
| Flash memory             | 16        | 1.62%   |
| Multimedia controller    | 12        | 1.22%   |
| Sound                    | 7         | 0.71%   |
| Network                  | 5         | 0.51%   |
| Net/ethernet             | 5         | 0.51%   |
| Unassigned class         | 2         | 0.2%    |
| Dvb card                 | 2         | 0.2%    |
| Firewire controller      | 1         | 0.1%    |

