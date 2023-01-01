Linux in Poland - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Poland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Poland/Desktop/README.md) and [notebooks](/Location/Poland/Notebook/README.md).

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

Total: 6371

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | B250M PRO-VDH               | Desktop     | [0a4b320a9e](https://linux-hardware.org/?probe=0a4b320a9e) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [1347eaedb9](https://linux-hardware.org/?probe=1347eaedb9) | Dec 31, 2022 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [48c688033a](https://linux-hardware.org/?probe=48c688033a) | Dec 30, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [4393041949](https://linux-hardware.org/?probe=4393041949) | Dec 30, 2022 |
| ASUSTek       | K72F                        | Notebook    | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [82cbc15539](https://linux-hardware.org/?probe=82cbc15539) | Dec 30, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [9a05e8c413](https://linux-hardware.org/?probe=9a05e8c413) | Dec 30, 2022 |
| HP            | EliteBook 745 G5            | Notebook    | [d819dbd901](https://linux-hardware.org/?probe=d819dbd901) | Dec 30, 2022 |
| Gigabyte      | H61M-D2H                    | Desktop     | [28aede6faf](https://linux-hardware.org/?probe=28aede6faf) | Dec 29, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [ca7468f975](https://linux-hardware.org/?probe=ca7468f975) | Dec 29, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [9b264f00f0](https://linux-hardware.org/?probe=9b264f00f0) | Dec 29, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [fdb09844e9](https://linux-hardware.org/?probe=fdb09844e9) | Dec 29, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [9ff3461c31](https://linux-hardware.org/?probe=9ff3461c31) | Dec 29, 2022 |
| Dell          | Latitude E6420              | Notebook    | [9733c425b6](https://linux-hardware.org/?probe=9733c425b6) | Dec 29, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [fe7926d39a](https://linux-hardware.org/?probe=fe7926d39a) | Dec 28, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [41c7a16579](https://linux-hardware.org/?probe=41c7a16579) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [27e072cb3e](https://linux-hardware.org/?probe=27e072cb3e) | Dec 28, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [e232c2de6d](https://linux-hardware.org/?probe=e232c2de6d) | Dec 28, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [1ca2f43148](https://linux-hardware.org/?probe=1ca2f43148) | Dec 27, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [03cca95360](https://linux-hardware.org/?probe=03cca95360) | Dec 27, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [95555948a2](https://linux-hardware.org/?probe=95555948a2) | Dec 27, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [06cba3f478](https://linux-hardware.org/?probe=06cba3f478) | Dec 27, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [58b02cceb0](https://linux-hardware.org/?probe=58b02cceb0) | Dec 27, 2022 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [031a62faa8](https://linux-hardware.org/?probe=031a62faa8) | Dec 27, 2022 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [23d6589918](https://linux-hardware.org/?probe=23d6589918) | Dec 27, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f395b56cec](https://linux-hardware.org/?probe=f395b56cec) | Dec 26, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [02f55ff55b](https://linux-hardware.org/?probe=02f55ff55b) | Dec 26, 2022 |
| ASUSTek       | X550LD                      | Notebook    | [e0a09344e0](https://linux-hardware.org/?probe=e0a09344e0) | Dec 26, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5d2498f405](https://linux-hardware.org/?probe=5d2498f405) | Dec 26, 2022 |
| ASUSTek       | M4A88T-V EVO/USB3           | Desktop     | [05163a2fb9](https://linux-hardware.org/?probe=05163a2fb9) | Dec 26, 2022 |
| ASUSTek       | X550LD                      | Notebook    | [d6948e7207](https://linux-hardware.org/?probe=d6948e7207) | Dec 26, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [315cef73cd](https://linux-hardware.org/?probe=315cef73cd) | Dec 25, 2022 |
| Acer          | Nitro AN515-31              | Notebook    | [249f50d430](https://linux-hardware.org/?probe=249f50d430) | Dec 25, 2022 |
| Lenovo        | ThinkPad T430 23472Y0       | Notebook    | [4a2d13391c](https://linux-hardware.org/?probe=4a2d13391c) | Dec 25, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [5ca8ddb512](https://linux-hardware.org/?probe=5ca8ddb512) | Dec 24, 2022 |
| Xiaomi        | Pocophone F1 (Tianma)       | Soc         | [85b5b184bb](https://linux-hardware.org/?probe=85b5b184bb) | Dec 24, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [38ed4755c3](https://linux-hardware.org/?probe=38ed4755c3) | Dec 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [0836c3b800](https://linux-hardware.org/?probe=0836c3b800) | Dec 23, 2022 |
| MSI           | Z270 TOMAHAWK               | Desktop     | [b721ac26e2](https://linux-hardware.org/?probe=b721ac26e2) | Dec 23, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [c17fe8cbe0](https://linux-hardware.org/?probe=c17fe8cbe0) | Dec 23, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0277928378](https://linux-hardware.org/?probe=0277928378) | Dec 23, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [5bedf1557b](https://linux-hardware.org/?probe=5bedf1557b) | Dec 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [87da3fdf4d](https://linux-hardware.org/?probe=87da3fdf4d) | Dec 23, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [f3dc3c0121](https://linux-hardware.org/?probe=f3dc3c0121) | Dec 22, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [bf600b6f1c](https://linux-hardware.org/?probe=bf600b6f1c) | Dec 22, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B7402FEA... | Convertible | [0cb3ccf545](https://linux-hardware.org/?probe=0cb3ccf545) | Dec 21, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [9ada5592f6](https://linux-hardware.org/?probe=9ada5592f6) | Dec 21, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [06d78a17c1](https://linux-hardware.org/?probe=06d78a17c1) | Dec 21, 2022 |
| Dell          | Precision 3520              | Notebook    | [1763494294](https://linux-hardware.org/?probe=1763494294) | Dec 21, 2022 |
| Sony          | SVE1112M1EB                 | Notebook    | [74e100e63b](https://linux-hardware.org/?probe=74e100e63b) | Dec 21, 2022 |
| HP            | 8266                        | Desktop     | [321dbc66bf](https://linux-hardware.org/?probe=321dbc66bf) | Dec 21, 2022 |
| ASUSTek       | N55SF                       | Notebook    | [b1d6a6a73d](https://linux-hardware.org/?probe=b1d6a6a73d) | Dec 21, 2022 |
| ASUSTek       | PRIME X399-A                | Desktop     | [243fccb6fa](https://linux-hardware.org/?probe=243fccb6fa) | Dec 21, 2022 |
| ASUSTek       | N55SF                       | Notebook    | [bbec56fa90](https://linux-hardware.org/?probe=bbec56fa90) | Dec 21, 2022 |
| Dell          | G15 5510                    | Notebook    | [86d0642973](https://linux-hardware.org/?probe=86d0642973) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming FX505GE          | Notebook    | [094e72dc22](https://linux-hardware.org/?probe=094e72dc22) | Dec 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [0d59e38c20](https://linux-hardware.org/?probe=0d59e38c20) | Dec 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [37513092d6](https://linux-hardware.org/?probe=37513092d6) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [03e2c64868](https://linux-hardware.org/?probe=03e2c64868) | Dec 20, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [f2467d713d](https://linux-hardware.org/?probe=f2467d713d) | Dec 19, 2022 |
| Dell          | Latitude 3190               | Notebook    | [9227c8dbfb](https://linux-hardware.org/?probe=9227c8dbfb) | Dec 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [70a0e2a296](https://linux-hardware.org/?probe=70a0e2a296) | Dec 19, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [44a96b54b6](https://linux-hardware.org/?probe=44a96b54b6) | Dec 18, 2022 |
| HP            | ProLiant ML350 G6           | Desktop     | [58113862ee](https://linux-hardware.org/?probe=58113862ee) | Dec 18, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [8c0c2353ab](https://linux-hardware.org/?probe=8c0c2353ab) | Dec 18, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [85d6221160](https://linux-hardware.org/?probe=85d6221160) | Dec 18, 2022 |
| Foxconn       | A76GMV                      | Desktop     | [722a9911f8](https://linux-hardware.org/?probe=722a9911f8) | Dec 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [72f897b9d3](https://linux-hardware.org/?probe=72f897b9d3) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | Desktop     | [2e3cc90610](https://linux-hardware.org/?probe=2e3cc90610) | Dec 17, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [7ea253aa11](https://linux-hardware.org/?probe=7ea253aa11) | Dec 17, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [d3517edb25](https://linux-hardware.org/?probe=d3517edb25) | Dec 17, 2022 |
| Dell          | Latitude E6330              | Notebook    | [ca6551bf8e](https://linux-hardware.org/?probe=ca6551bf8e) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | Desktop     | [f0efaa3c30](https://linux-hardware.org/?probe=f0efaa3c30) | Dec 17, 2022 |
| MSI           | A68HM-E33                   | Desktop     | [0df6f80110](https://linux-hardware.org/?probe=0df6f80110) | Dec 17, 2022 |
| Dell          | Latitude E5570              | Notebook    | [cc58177561](https://linux-hardware.org/?probe=cc58177561) | Dec 17, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [0d7a54bc21](https://linux-hardware.org/?probe=0d7a54bc21) | Dec 16, 2022 |
| POSIFLEX      | KK-3703 D0                  | Desktop     | [8ce9910b00](https://linux-hardware.org/?probe=8ce9910b00) | Dec 16, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1860105d14](https://linux-hardware.org/?probe=1860105d14) | Dec 16, 2022 |
| Dell          | Latitude E6410              | Notebook    | [173f8a8dc8](https://linux-hardware.org/?probe=173f8a8dc8) | Dec 16, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [4f63e7b8d1](https://linux-hardware.org/?probe=4f63e7b8d1) | Dec 15, 2022 |
| Dell          | Latitude 7330               | Convertible | [b3956235ae](https://linux-hardware.org/?probe=b3956235ae) | Dec 15, 2022 |
| Dell          | Latitude 5420               | Notebook    | [5fa4cbba73](https://linux-hardware.org/?probe=5fa4cbba73) | Dec 15, 2022 |
| Lenovo        | ThinkPad T530 24295XU       | Notebook    | [0ebd945403](https://linux-hardware.org/?probe=0ebd945403) | Dec 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ad1e402db3](https://linux-hardware.org/?probe=ad1e402db3) | Dec 15, 2022 |
| Dell          | 05XGC8 A01                  | Desktop     | [f0e99676be](https://linux-hardware.org/?probe=f0e99676be) | Dec 14, 2022 |
| Gigabyte      | MMLP3AP-00                  | Notebook    | [6b53aab624](https://linux-hardware.org/?probe=6b53aab624) | Dec 14, 2022 |
| Google        | Ultima                      | Notebook    | [867abc2b8f](https://linux-hardware.org/?probe=867abc2b8f) | Dec 14, 2022 |
| ASUSTek       | M3N                         | Notebook    | [4e9f8e4c01](https://linux-hardware.org/?probe=4e9f8e4c01) | Dec 14, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [de7f9d5e33](https://linux-hardware.org/?probe=de7f9d5e33) | Dec 14, 2022 |
| Inventec      | D CLASS A02                 | Desktop     | [a607679697](https://linux-hardware.org/?probe=a607679697) | Dec 14, 2022 |
| Inventec      | D CLASS A02                 | Desktop     | [9bd8fecf82](https://linux-hardware.org/?probe=9bd8fecf82) | Dec 14, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [b7fa78df7a](https://linux-hardware.org/?probe=b7fa78df7a) | Dec 14, 2022 |
| ASUSTek       | P8H61-M LX2/CSM             | Desktop     | [cc6e7dae77](https://linux-hardware.org/?probe=cc6e7dae77) | Dec 14, 2022 |
| Dell          | XPS L501X                   | Notebook    | [f540185d6c](https://linux-hardware.org/?probe=f540185d6c) | Dec 14, 2022 |
| Dell          | XPS L501X                   | Notebook    | [32e195f4c6](https://linux-hardware.org/?probe=32e195f4c6) | Dec 14, 2022 |
| ASUSTek       | M3N                         | Notebook    | [ff772de294](https://linux-hardware.org/?probe=ff772de294) | Dec 13, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [37284f659a](https://linux-hardware.org/?probe=37284f659a) | Dec 13, 2022 |
| Dell          | Latitude 7330               | Convertible | [95aea2b219](https://linux-hardware.org/?probe=95aea2b219) | Dec 12, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [61685b4f1a](https://linux-hardware.org/?probe=61685b4f1a) | Dec 12, 2022 |
| Dell          | Latitude 5411               | Notebook    | [af806502e8](https://linux-hardware.org/?probe=af806502e8) | Dec 12, 2022 |
| Dell          | Latitude 5411               | Notebook    | [334ca886a4](https://linux-hardware.org/?probe=334ca886a4) | Dec 12, 2022 |
| HP            | Pavilion dv7                | Notebook    | [1e10e0306f](https://linux-hardware.org/?probe=1e10e0306f) | Dec 12, 2022 |
| Dell          | Latitude 7330               | Convertible | [3bd7f5734d](https://linux-hardware.org/?probe=3bd7f5734d) | Dec 12, 2022 |
| Dell          | Latitude 3190               | Notebook    | [c2c5f3feb3](https://linux-hardware.org/?probe=c2c5f3feb3) | Dec 12, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [177dded9e0](https://linux-hardware.org/?probe=177dded9e0) | Dec 12, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [492b382af1](https://linux-hardware.org/?probe=492b382af1) | Dec 11, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [c94af57999](https://linux-hardware.org/?probe=c94af57999) | Dec 11, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [cea4c76b9d](https://linux-hardware.org/?probe=cea4c76b9d) | Dec 11, 2022 |
| ASUSTek       | P5K Deluxe                  | Desktop     | [6f97813144](https://linux-hardware.org/?probe=6f97813144) | Dec 10, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | Desktop     | [ffb030fbbf](https://linux-hardware.org/?probe=ffb030fbbf) | Dec 10, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [ef403a3962](https://linux-hardware.org/?probe=ef403a3962) | Dec 10, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [50ccab1267](https://linux-hardware.org/?probe=50ccab1267) | Dec 10, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [fe9424a1f0](https://linux-hardware.org/?probe=fe9424a1f0) | Dec 09, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [0dc9bb1cf4](https://linux-hardware.org/?probe=0dc9bb1cf4) | Dec 09, 2022 |
| Dell          | Latitude 7330               | Convertible | [67bbcec9fd](https://linux-hardware.org/?probe=67bbcec9fd) | Dec 09, 2022 |
| Lenovo        | ThinkCentre M70e 0829RB4    | Desktop     | [5a5b271c35](https://linux-hardware.org/?probe=5a5b271c35) | Dec 09, 2022 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [b9e3c45caa](https://linux-hardware.org/?probe=b9e3c45caa) | Dec 09, 2022 |
| Dell          | 0PM2CW A02                  | Server      | [460791d797](https://linux-hardware.org/?probe=460791d797) | Dec 08, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [93075de512](https://linux-hardware.org/?probe=93075de512) | Dec 08, 2022 |
| MSI           | Vector GP76 12UGS           | Notebook    | [d6c55a874f](https://linux-hardware.org/?probe=d6c55a874f) | Dec 08, 2022 |
| Google        | Glimmer                     | Notebook    | [ad4b3f5575](https://linux-hardware.org/?probe=ad4b3f5575) | Dec 08, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [e15b555b1a](https://linux-hardware.org/?probe=e15b555b1a) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [8c8e80423c](https://linux-hardware.org/?probe=8c8e80423c) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [37283186c3](https://linux-hardware.org/?probe=37283186c3) | Dec 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [3a9774bdac](https://linux-hardware.org/?probe=3a9774bdac) | Dec 07, 2022 |
| Dell          | Latitude 5480               | Notebook    | [0cd7d6e4c0](https://linux-hardware.org/?probe=0cd7d6e4c0) | Dec 07, 2022 |
| Panasonic     | CFMX4-1                     | Notebook    | [c25c16fc1a](https://linux-hardware.org/?probe=c25c16fc1a) | Dec 06, 2022 |
| Dell          | Latitude E7440              | Notebook    | [9a859c9a5d](https://linux-hardware.org/?probe=9a859c9a5d) | Dec 06, 2022 |
| Dell          | Latitude 5310               | Notebook    | [06d96a49a1](https://linux-hardware.org/?probe=06d96a49a1) | Dec 06, 2022 |
| Dell          | Latitude E7440              | Notebook    | [63b84a9439](https://linux-hardware.org/?probe=63b84a9439) | Dec 06, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [e64c5d7bdc](https://linux-hardware.org/?probe=e64c5d7bdc) | Dec 06, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [e2be1fe149](https://linux-hardware.org/?probe=e2be1fe149) | Dec 06, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [798cf690c5](https://linux-hardware.org/?probe=798cf690c5) | Dec 06, 2022 |
| Dell          | Latitude 5411               | Notebook    | [62e5941721](https://linux-hardware.org/?probe=62e5941721) | Dec 06, 2022 |
| Dell          | Latitude 5411               | Notebook    | [e0815067bd](https://linux-hardware.org/?probe=e0815067bd) | Dec 06, 2022 |
| Dell          | Latitude 5310               | Notebook    | [f3801600ff](https://linux-hardware.org/?probe=f3801600ff) | Dec 06, 2022 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [091b8a3a8a](https://linux-hardware.org/?probe=091b8a3a8a) | Dec 05, 2022 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [aadffecf5b](https://linux-hardware.org/?probe=aadffecf5b) | Dec 05, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [a4a47ea164](https://linux-hardware.org/?probe=a4a47ea164) | Dec 05, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [119ec75a5f](https://linux-hardware.org/?probe=119ec75a5f) | Dec 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [36985fd47e](https://linux-hardware.org/?probe=36985fd47e) | Dec 05, 2022 |
| HP            | ProLiant ML350e Gen8        | Desktop     | [984fe41e3c](https://linux-hardware.org/?probe=984fe41e3c) | Dec 05, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [5b0565920f](https://linux-hardware.org/?probe=5b0565920f) | Dec 05, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [a849daba2b](https://linux-hardware.org/?probe=a849daba2b) | Dec 05, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [6c726b6eb7](https://linux-hardware.org/?probe=6c726b6eb7) | Dec 05, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [99b35ee6a3](https://linux-hardware.org/?probe=99b35ee6a3) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [ce36bcdf8b](https://linux-hardware.org/?probe=ce36bcdf8b) | Dec 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [12975376ba](https://linux-hardware.org/?probe=12975376ba) | Dec 05, 2022 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [1bf4364f61](https://linux-hardware.org/?probe=1bf4364f61) | Dec 05, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7a47529fdc](https://linux-hardware.org/?probe=7a47529fdc) | Dec 04, 2022 |
| GMKtec        | NucBox5                     | Notebook    | [cdfbbcc5b2](https://linux-hardware.org/?probe=cdfbbcc5b2) | Dec 04, 2022 |
| Lenovo        | G770 20089                  | Notebook    | [d35d60f972](https://linux-hardware.org/?probe=d35d60f972) | Dec 04, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [afbbf473b9](https://linux-hardware.org/?probe=afbbf473b9) | Dec 04, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [0bad01b327](https://linux-hardware.org/?probe=0bad01b327) | Dec 04, 2022 |
| Gigabyte      | B650E AORUS MASTER se2      | Desktop     | [101ea2715c](https://linux-hardware.org/?probe=101ea2715c) | Dec 04, 2022 |
| pine64,roc... | RockPro64 v2.1              | Soc         | [9973baf711](https://linux-hardware.org/?probe=9973baf711) | Dec 04, 2022 |
| ACTION        | ACTINA GA-G31M-S2L          | Desktop     | [2a2934f919](https://linux-hardware.org/?probe=2a2934f919) | Dec 04, 2022 |
| HP            | Pavilion dv7                | Notebook    | [90c7688386](https://linux-hardware.org/?probe=90c7688386) | Dec 04, 2022 |
| Google        | Lars                        | Notebook    | [efe9cef4b9](https://linux-hardware.org/?probe=efe9cef4b9) | Dec 04, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [0455f2c685](https://linux-hardware.org/?probe=0455f2c685) | Dec 04, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [84a50cd483](https://linux-hardware.org/?probe=84a50cd483) | Dec 03, 2022 |
| Lenovo        | SKYBAY NOK                  | Desktop     | [10315500be](https://linux-hardware.org/?probe=10315500be) | Dec 03, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [f8dacfeca3](https://linux-hardware.org/?probe=f8dacfeca3) | Dec 03, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [ec5047129a](https://linux-hardware.org/?probe=ec5047129a) | Dec 03, 2022 |
| HP            | Pavilion dv7                | Notebook    | [c398cf4372](https://linux-hardware.org/?probe=c398cf4372) | Dec 03, 2022 |
| HP            | Pavilion dv7                | Notebook    | [e34ad54f3b](https://linux-hardware.org/?probe=e34ad54f3b) | Dec 03, 2022 |
| Google        | Lars                        | Notebook    | [ad022bfd93](https://linux-hardware.org/?probe=ad022bfd93) | Dec 03, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [6578471259](https://linux-hardware.org/?probe=6578471259) | Dec 03, 2022 |
| Dell          | G15 5515                    | Notebook    | [218e5c2825](https://linux-hardware.org/?probe=218e5c2825) | Dec 03, 2022 |
| Dell          | Latitude 5480               | Notebook    | [4eba5810d7](https://linux-hardware.org/?probe=4eba5810d7) | Dec 03, 2022 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [bf8f5e2683](https://linux-hardware.org/?probe=bf8f5e2683) | Dec 03, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [9990900d63](https://linux-hardware.org/?probe=9990900d63) | Dec 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7177c55be0](https://linux-hardware.org/?probe=7177c55be0) | Dec 02, 2022 |
| Dell          | Vostro 5502                 | Notebook    | [86341e8306](https://linux-hardware.org/?probe=86341e8306) | Dec 02, 2022 |
| MSI           | A68HM-E33                   | Desktop     | [4e2313d8b7](https://linux-hardware.org/?probe=4e2313d8b7) | Dec 02, 2022 |
| HP            | 0A98h                       | Desktop     | [e1413607aa](https://linux-hardware.org/?probe=e1413607aa) | Dec 02, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4d33c2ab30](https://linux-hardware.org/?probe=4d33c2ab30) | Dec 02, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [8a25bf4545](https://linux-hardware.org/?probe=8a25bf4545) | Dec 01, 2022 |
| HP            | 0A98h                       | Desktop     | [f2b620c220](https://linux-hardware.org/?probe=f2b620c220) | Dec 01, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [929550dc41](https://linux-hardware.org/?probe=929550dc41) | Dec 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [615b292682](https://linux-hardware.org/?probe=615b292682) | Dec 01, 2022 |
| HP            | Pavilion dv7                | Notebook    | [aa6cdce8f8](https://linux-hardware.org/?probe=aa6cdce8f8) | Dec 01, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [dd124e3579](https://linux-hardware.org/?probe=dd124e3579) | Nov 30, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [a5b34b67f2](https://linux-hardware.org/?probe=a5b34b67f2) | Nov 30, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | Notebook    | [3aa3302b92](https://linux-hardware.org/?probe=3aa3302b92) | Nov 30, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [c3d55f501c](https://linux-hardware.org/?probe=c3d55f501c) | Nov 30, 2022 |
| MACHINIST     | X99-D8-MAX V1.0             | Desktop     | [c2430965a1](https://linux-hardware.org/?probe=c2430965a1) | Nov 30, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [81bf84e7e5](https://linux-hardware.org/?probe=81bf84e7e5) | Nov 29, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [f0dfa48048](https://linux-hardware.org/?probe=f0dfa48048) | Nov 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f4de100586](https://linux-hardware.org/?probe=f4de100586) | Nov 29, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [802af80043](https://linux-hardware.org/?probe=802af80043) | Nov 29, 2022 |
| HP            | Pavilion dv7                | Notebook    | [1ba2fdd19b](https://linux-hardware.org/?probe=1ba2fdd19b) | Nov 29, 2022 |
| Dell          | Latitude E6540              | Notebook    | [48c805974c](https://linux-hardware.org/?probe=48c805974c) | Nov 29, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9c45563fb6](https://linux-hardware.org/?probe=9c45563fb6) | Nov 29, 2022 |
| HP            | Pavilion dv7                | Notebook    | [db7897d2fc](https://linux-hardware.org/?probe=db7897d2fc) | Nov 28, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [56ceffe338](https://linux-hardware.org/?probe=56ceffe338) | Nov 28, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3c4756b965](https://linux-hardware.org/?probe=3c4756b965) | Nov 28, 2022 |
| HUAWEI        | MRC-WX0                     | Notebook    | [98f550465b](https://linux-hardware.org/?probe=98f550465b) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [ef85b8ab38](https://linux-hardware.org/?probe=ef85b8ab38) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [622315486c](https://linux-hardware.org/?probe=622315486c) | Nov 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [6bf87b9885](https://linux-hardware.org/?probe=6bf87b9885) | Nov 28, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [1a316a1239](https://linux-hardware.org/?probe=1a316a1239) | Nov 27, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [87ef485975](https://linux-hardware.org/?probe=87ef485975) | Nov 27, 2022 |
| Acer          | AO722                       | Notebook    | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| HP            | ProBook 6470b               | Notebook    | [c8da54315e](https://linux-hardware.org/?probe=c8da54315e) | Nov 26, 2022 |
| Dell          | Latitude E6220              | Notebook    | [aa8d2d2fc7](https://linux-hardware.org/?probe=aa8d2d2fc7) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [7a6ec88b73](https://linux-hardware.org/?probe=7a6ec88b73) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [b9bbfd7551](https://linux-hardware.org/?probe=b9bbfd7551) | Nov 26, 2022 |
| Lenovo        | B51-80 80LM                 | Notebook    | [848b6ab7b3](https://linux-hardware.org/?probe=848b6ab7b3) | Nov 26, 2022 |
| Lenovo        | B51-80 80LM                 | Notebook    | [c34893c661](https://linux-hardware.org/?probe=c34893c661) | Nov 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [7412d8b03b](https://linux-hardware.org/?probe=7412d8b03b) | Nov 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [24d078fe91](https://linux-hardware.org/?probe=24d078fe91) | Nov 26, 2022 |
| Dell          | Latitude E6420              | Notebook    | [c3e8903f19](https://linux-hardware.org/?probe=c3e8903f19) | Nov 25, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [4261949a3e](https://linux-hardware.org/?probe=4261949a3e) | Nov 25, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [8acafcf4ab](https://linux-hardware.org/?probe=8acafcf4ab) | Nov 25, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1bd15590c9](https://linux-hardware.org/?probe=1bd15590c9) | Nov 25, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [a17a108297](https://linux-hardware.org/?probe=a17a108297) | Nov 25, 2022 |
| MSI           | B350 GAMING PLUS            | Desktop     | [2b7bb89689](https://linux-hardware.org/?probe=2b7bb89689) | Nov 25, 2022 |
| HP            | 2215                        | Desktop     | [0134898651](https://linux-hardware.org/?probe=0134898651) | Nov 25, 2022 |
| Dell          | Inspiron 14 Plus 7420       | Notebook    | [a35ca4bbbe](https://linux-hardware.org/?probe=a35ca4bbbe) | Nov 24, 2022 |
| HP            | 213D A01                    | Desktop     | [b0c45fb200](https://linux-hardware.org/?probe=b0c45fb200) | Nov 24, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [b154300490](https://linux-hardware.org/?probe=b154300490) | Nov 24, 2022 |
| Dell          | Latitude 5310               | Notebook    | [8b4ad51670](https://linux-hardware.org/?probe=8b4ad51670) | Nov 24, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [e7bf51183d](https://linux-hardware.org/?probe=e7bf51183d) | Nov 24, 2022 |
| Dell          | Latitude 5310               | Notebook    | [a5265c8a0e](https://linux-hardware.org/?probe=a5265c8a0e) | Nov 24, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [8f1bec4fe9](https://linux-hardware.org/?probe=8f1bec4fe9) | Nov 24, 2022 |
| Unknown       | HX90                        | Desktop     | [e1bd045aaa](https://linux-hardware.org/?probe=e1bd045aaa) | Nov 24, 2022 |
| ASUSTek       | K51AC                       | Notebook    | [0b2413e13c](https://linux-hardware.org/?probe=0b2413e13c) | Nov 24, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [ca7045ed57](https://linux-hardware.org/?probe=ca7045ed57) | Nov 24, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [d2d484b35b](https://linux-hardware.org/?probe=d2d484b35b) | Nov 24, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [e7717a62cb](https://linux-hardware.org/?probe=e7717a62cb) | Nov 23, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [ac72570183](https://linux-hardware.org/?probe=ac72570183) | Nov 23, 2022 |
| Kruger&Mat... | KM1406                      | Notebook    | [d639be7513](https://linux-hardware.org/?probe=d639be7513) | Nov 23, 2022 |
| Kruger&Mat... | KM1406                      | Notebook    | [a7e0207e4b](https://linux-hardware.org/?probe=a7e0207e4b) | Nov 23, 2022 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | Notebook    | [57dfd88985](https://linux-hardware.org/?probe=57dfd88985) | Nov 23, 2022 |
| HP            | Pavilion dv6                | Notebook    | [e3921e4da9](https://linux-hardware.org/?probe=e3921e4da9) | Nov 23, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [51ca9fa048](https://linux-hardware.org/?probe=51ca9fa048) | Nov 23, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [0ca1ce1d74](https://linux-hardware.org/?probe=0ca1ce1d74) | Nov 23, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [6d217fbd52](https://linux-hardware.org/?probe=6d217fbd52) | Nov 23, 2022 |
| ASRock        | H410M-HVS R2.0              | Desktop     | [3f381f9fa3](https://linux-hardware.org/?probe=3f381f9fa3) | Nov 23, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [7dd9d3bec3](https://linux-hardware.org/?probe=7dd9d3bec3) | Nov 23, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [17b880ceb9](https://linux-hardware.org/?probe=17b880ceb9) | Nov 23, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [ad63d86cb9](https://linux-hardware.org/?probe=ad63d86cb9) | Nov 23, 2022 |
| HP            | G5000 (GF783EA#AKD)         | Notebook    | [2437328d23](https://linux-hardware.org/?probe=2437328d23) | Nov 22, 2022 |
| Dell          | Latitude 3420               | Notebook    | [30434de3e9](https://linux-hardware.org/?probe=30434de3e9) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [c345afe01a](https://linux-hardware.org/?probe=c345afe01a) | Nov 22, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [e36ab20d8c](https://linux-hardware.org/?probe=e36ab20d8c) | Nov 22, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [014cf9f78d](https://linux-hardware.org/?probe=014cf9f78d) | Nov 22, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [a38b2f2f2a](https://linux-hardware.org/?probe=a38b2f2f2a) | Nov 22, 2022 |
| Lenovo        | SKYBAY NOK                  | Desktop     | [24d16fa5df](https://linux-hardware.org/?probe=24d16fa5df) | Nov 22, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [a5dcbbbacd](https://linux-hardware.org/?probe=a5dcbbbacd) | Nov 22, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [26ac531682](https://linux-hardware.org/?probe=26ac531682) | Nov 22, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [4743344f41](https://linux-hardware.org/?probe=4743344f41) | Nov 22, 2022 |
| Dell          | 0PU052                      | Desktop     | [b54afc7e1a](https://linux-hardware.org/?probe=b54afc7e1a) | Nov 21, 2022 |
| Dell          | Latitude 5410               | Notebook    | [7fd0b3fca7](https://linux-hardware.org/?probe=7fd0b3fca7) | Nov 21, 2022 |
| Dell          | Latitude 5490               | Notebook    | [295073cd07](https://linux-hardware.org/?probe=295073cd07) | Nov 21, 2022 |
| Dell          | Latitude 5310               | Notebook    | [9c19a3de68](https://linux-hardware.org/?probe=9c19a3de68) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [64cff39a82](https://linux-hardware.org/?probe=64cff39a82) | Nov 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [0a98e4cae4](https://linux-hardware.org/?probe=0a98e4cae4) | Nov 21, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [d74e4882d8](https://linux-hardware.org/?probe=d74e4882d8) | Nov 21, 2022 |
| Dell          | Latitude 3190               | Notebook    | [1cfe937b0e](https://linux-hardware.org/?probe=1cfe937b0e) | Nov 21, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [740b4f9f03](https://linux-hardware.org/?probe=740b4f9f03) | Nov 20, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [aa4bde7d79](https://linux-hardware.org/?probe=aa4bde7d79) | Nov 20, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [3f18cccea5](https://linux-hardware.org/?probe=3f18cccea5) | Nov 20, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [2030d33f00](https://linux-hardware.org/?probe=2030d33f00) | Nov 20, 2022 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [75a8f2a500](https://linux-hardware.org/?probe=75a8f2a500) | Nov 20, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [05f54bd8da](https://linux-hardware.org/?probe=05f54bd8da) | Nov 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [d8f53f887a](https://linux-hardware.org/?probe=d8f53f887a) | Nov 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c967893dd4](https://linux-hardware.org/?probe=c967893dd4) | Nov 20, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [08372f6535](https://linux-hardware.org/?probe=08372f6535) | Nov 20, 2022 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [8c73ebd2b9](https://linux-hardware.org/?probe=8c73ebd2b9) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [1af7bd26fd](https://linux-hardware.org/?probe=1af7bd26fd) | Nov 19, 2022 |
| Lenovo        | S145-15API 81UT             | Notebook    | [fd832d05e2](https://linux-hardware.org/?probe=fd832d05e2) | Nov 19, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [8e7aa30e4e](https://linux-hardware.org/?probe=8e7aa30e4e) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [ad7abfb8cb](https://linux-hardware.org/?probe=ad7abfb8cb) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [598f8e7c34](https://linux-hardware.org/?probe=598f8e7c34) | Nov 19, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [bc46ec232a](https://linux-hardware.org/?probe=bc46ec232a) | Nov 18, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [c2ad29d3e8](https://linux-hardware.org/?probe=c2ad29d3e8) | Nov 18, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [74a3983b1e](https://linux-hardware.org/?probe=74a3983b1e) | Nov 18, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [4d8be4bb54](https://linux-hardware.org/?probe=4d8be4bb54) | Nov 18, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [dd25be7aef](https://linux-hardware.org/?probe=dd25be7aef) | Nov 17, 2022 |
| ASRock        | X670E Pro RS                | Desktop     | [bfccdbd536](https://linux-hardware.org/?probe=bfccdbd536) | Nov 17, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bb2db87e9a](https://linux-hardware.org/?probe=bb2db87e9a) | Nov 17, 2022 |
| Dell          | Inspiron 13-5368            | Notebook    | [203df386a1](https://linux-hardware.org/?probe=203df386a1) | Nov 17, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [105a376344](https://linux-hardware.org/?probe=105a376344) | Nov 17, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [5fd36e3d66](https://linux-hardware.org/?probe=5fd36e3d66) | Nov 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [cdf4d49427](https://linux-hardware.org/?probe=cdf4d49427) | Nov 16, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [62b2a72fa9](https://linux-hardware.org/?probe=62b2a72fa9) | Nov 16, 2022 |
| Lenovo        | ThinkPad T430 23498M7       | Notebook    | [fe520ea826](https://linux-hardware.org/?probe=fe520ea826) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [b5eb364ac6](https://linux-hardware.org/?probe=b5eb364ac6) | Nov 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [4ab915f825](https://linux-hardware.org/?probe=4ab915f825) | Nov 15, 2022 |
| Dell          | 0PU052                      | Desktop     | [802c39b94f](https://linux-hardware.org/?probe=802c39b94f) | Nov 15, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ea39f5300c](https://linux-hardware.org/?probe=ea39f5300c) | Nov 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [d07cacacde](https://linux-hardware.org/?probe=d07cacacde) | Nov 15, 2022 |
| HP            | 22F8                        | Desktop     | [754ebee9c8](https://linux-hardware.org/?probe=754ebee9c8) | Nov 14, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [7f21362848](https://linux-hardware.org/?probe=7f21362848) | Nov 14, 2022 |
| HP            | ProBook 6450b               | Notebook    | [ee3a2a2ef8](https://linux-hardware.org/?probe=ee3a2a2ef8) | Nov 14, 2022 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [e53d77c404](https://linux-hardware.org/?probe=e53d77c404) | Nov 14, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [27d4e1c496](https://linux-hardware.org/?probe=27d4e1c496) | Nov 13, 2022 |
| Toshiba       | Satellite P300              | Notebook    | [02285947b8](https://linux-hardware.org/?probe=02285947b8) | Nov 13, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [6fcf5c9bd6](https://linux-hardware.org/?probe=6fcf5c9bd6) | Nov 13, 2022 |
| Acer          | Aspire E1-531G              | Notebook    | [9f3c8742f7](https://linux-hardware.org/?probe=9f3c8742f7) | Nov 13, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [220c131e59](https://linux-hardware.org/?probe=220c131e59) | Nov 13, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [7a628290f2](https://linux-hardware.org/?probe=7a628290f2) | Nov 13, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [7ca98c421a](https://linux-hardware.org/?probe=7ca98c421a) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [1067cba3cc](https://linux-hardware.org/?probe=1067cba3cc) | Nov 12, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e28c12e783](https://linux-hardware.org/?probe=e28c12e783) | Nov 11, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [e69a98ce67](https://linux-hardware.org/?probe=e69a98ce67) | Nov 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [59aa7d31d8](https://linux-hardware.org/?probe=59aa7d31d8) | Nov 11, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [2981b232db](https://linux-hardware.org/?probe=2981b232db) | Nov 11, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | Desktop     | [e6ad281519](https://linux-hardware.org/?probe=e6ad281519) | Nov 11, 2022 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | Notebook    | [3ebec87cd1](https://linux-hardware.org/?probe=3ebec87cd1) | Nov 11, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [11344e1661](https://linux-hardware.org/?probe=11344e1661) | Nov 11, 2022 |
| Dell          | Latitude 7480               | Notebook    | [cd19ef7ab8](https://linux-hardware.org/?probe=cd19ef7ab8) | Nov 10, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [485568beb7](https://linux-hardware.org/?probe=485568beb7) | Nov 10, 2022 |
| Dell          | Latitude 7480               | Notebook    | [100bc3303a](https://linux-hardware.org/?probe=100bc3303a) | Nov 10, 2022 |
| MSI           | Stealth GS77 12UGS          | Notebook    | [bf125e16a2](https://linux-hardware.org/?probe=bf125e16a2) | Nov 10, 2022 |
| Dell          | Latitude E6330              | Notebook    | [04113ad3de](https://linux-hardware.org/?probe=04113ad3de) | Nov 10, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [8d43f2e3fc](https://linux-hardware.org/?probe=8d43f2e3fc) | Nov 10, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6531f0596d](https://linux-hardware.org/?probe=6531f0596d) | Nov 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [9d27997bce](https://linux-hardware.org/?probe=9d27997bce) | Nov 09, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [a3b1e0d746](https://linux-hardware.org/?probe=a3b1e0d746) | Nov 09, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [6642f568d4](https://linux-hardware.org/?probe=6642f568d4) | Nov 09, 2022 |
| MSI           | Stealth GS77 12UGS          | Notebook    | [ae6b308816](https://linux-hardware.org/?probe=ae6b308816) | Nov 08, 2022 |
| Dell          | G5 5587                     | Notebook    | [972a2dcaa0](https://linux-hardware.org/?probe=972a2dcaa0) | Nov 08, 2022 |
| Lenovo        | ThinkPad P53 20QQS2CY00     | Notebook    | [98e9599ea3](https://linux-hardware.org/?probe=98e9599ea3) | Nov 08, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [3928df6d1f](https://linux-hardware.org/?probe=3928df6d1f) | Nov 08, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [a22087073b](https://linux-hardware.org/?probe=a22087073b) | Nov 08, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a8f533624d](https://linux-hardware.org/?probe=a8f533624d) | Nov 08, 2022 |
| Dell          | Latitude E7470              | Notebook    | [3938dbeadd](https://linux-hardware.org/?probe=3938dbeadd) | Nov 08, 2022 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | Notebook    | [d19fce3e6c](https://linux-hardware.org/?probe=d19fce3e6c) | Nov 08, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [891dbf2492](https://linux-hardware.org/?probe=891dbf2492) | Nov 07, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [fafbf5ba02](https://linux-hardware.org/?probe=fafbf5ba02) | Nov 07, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [97e9d1458f](https://linux-hardware.org/?probe=97e9d1458f) | Nov 07, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [4c91fc2a59](https://linux-hardware.org/?probe=4c91fc2a59) | Nov 07, 2022 |
| HP            | ProBook 5330m               | Notebook    | [7ddff41cb6](https://linux-hardware.org/?probe=7ddff41cb6) | Nov 07, 2022 |
| Intel         | H55                         | Desktop     | [0481a6ff8e](https://linux-hardware.org/?probe=0481a6ff8e) | Nov 07, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [159ca02eca](https://linux-hardware.org/?probe=159ca02eca) | Nov 07, 2022 |
| HP            | ProBook 6570b               | Notebook    | [1fec197471](https://linux-hardware.org/?probe=1fec197471) | Nov 06, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [5deb773641](https://linux-hardware.org/?probe=5deb773641) | Nov 06, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [e872e8551e](https://linux-hardware.org/?probe=e872e8551e) | Nov 06, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d37fe5f0b4](https://linux-hardware.org/?probe=d37fe5f0b4) | Nov 06, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [e8588245aa](https://linux-hardware.org/?probe=e8588245aa) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [3ec96d66bb](https://linux-hardware.org/?probe=3ec96d66bb) | Nov 05, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [55b349ab41](https://linux-hardware.org/?probe=55b349ab41) | Nov 05, 2022 |
| MSI           | B350 GAMING PRO CARBON      | Desktop     | [16b0128664](https://linux-hardware.org/?probe=16b0128664) | Nov 05, 2022 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [7596586a99](https://linux-hardware.org/?probe=7596586a99) | Nov 05, 2022 |
| Gigabyte      | B560M D3H                   | Desktop     | [e8364f4018](https://linux-hardware.org/?probe=e8364f4018) | Nov 04, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMC    | Notebook    | [010fd86c32](https://linux-hardware.org/?probe=010fd86c32) | Nov 04, 2022 |
| Acer          | Aspire A715-74G             | Notebook    | [fa89b7a988](https://linux-hardware.org/?probe=fa89b7a988) | Nov 04, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [24e798d2a5](https://linux-hardware.org/?probe=24e798d2a5) | Nov 04, 2022 |
| MSI           | Z97-G43                     | Desktop     | [85701968ed](https://linux-hardware.org/?probe=85701968ed) | Nov 04, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [391881cdd5](https://linux-hardware.org/?probe=391881cdd5) | Nov 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [455bdc6c45](https://linux-hardware.org/?probe=455bdc6c45) | Nov 03, 2022 |
| HP            | EliteBook 745 G2            | Notebook    | [c6505744ca](https://linux-hardware.org/?probe=c6505744ca) | Nov 03, 2022 |
| Dell          | Latitude E6540              | Notebook    | [fe0f06d2d3](https://linux-hardware.org/?probe=fe0f06d2d3) | Nov 02, 2022 |
| Dell          | Latitude E6430              | Notebook    | [2b6012cc1d](https://linux-hardware.org/?probe=2b6012cc1d) | Nov 02, 2022 |
| Dell          | G15 5515                    | Notebook    | [92f1423303](https://linux-hardware.org/?probe=92f1423303) | Nov 02, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [a2af2980ad](https://linux-hardware.org/?probe=a2af2980ad) | Nov 02, 2022 |
| Dell          | G15 5515                    | Notebook    | [dae7c630d5](https://linux-hardware.org/?probe=dae7c630d5) | Nov 02, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [5f81698e9a](https://linux-hardware.org/?probe=5f81698e9a) | Nov 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [d28b33e126](https://linux-hardware.org/?probe=d28b33e126) | Nov 01, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [245ec71478](https://linux-hardware.org/?probe=245ec71478) | Nov 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [310895b721](https://linux-hardware.org/?probe=310895b721) | Nov 01, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [6d6a8caf61](https://linux-hardware.org/?probe=6d6a8caf61) | Nov 01, 2022 |
| HP            | Unknown                     | Notebook    | [1ca885060e](https://linux-hardware.org/?probe=1ca885060e) | Nov 01, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [8b208b8383](https://linux-hardware.org/?probe=8b208b8383) | Oct 31, 2022 |
| HP            | EliteBook 745 G2            | Notebook    | [0786ded6c8](https://linux-hardware.org/?probe=0786ded6c8) | Oct 31, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ce4bda1df2](https://linux-hardware.org/?probe=ce4bda1df2) | Oct 31, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [b4fedd7c20](https://linux-hardware.org/?probe=b4fedd7c20) | Oct 31, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [598d815c17](https://linux-hardware.org/?probe=598d815c17) | Oct 31, 2022 |
| Dell          | Latitude 3190               | Notebook    | [fe0d1261a6](https://linux-hardware.org/?probe=fe0d1261a6) | Oct 31, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c085788e44](https://linux-hardware.org/?probe=c085788e44) | Oct 31, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [738569f811](https://linux-hardware.org/?probe=738569f811) | Oct 30, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [a8b08a47aa](https://linux-hardware.org/?probe=a8b08a47aa) | Oct 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [24d91cf27b](https://linux-hardware.org/?probe=24d91cf27b) | Oct 30, 2022 |
| HP            | ProBook 6540b               | Notebook    | [be9c128b00](https://linux-hardware.org/?probe=be9c128b00) | Oct 30, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [9f43a68f81](https://linux-hardware.org/?probe=9f43a68f81) | Oct 30, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [d0814afd39](https://linux-hardware.org/?probe=d0814afd39) | Oct 29, 2022 |
| Kiano         | SlimNote 1.0                | Notebook    | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Dell          | Latitude 5501               | Notebook    | [67f979a26d](https://linux-hardware.org/?probe=67f979a26d) | Oct 29, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [9c1ab509ec](https://linux-hardware.org/?probe=9c1ab509ec) | Oct 29, 2022 |
| Lenovo        | ThinkPad T450s 20BWS0DD0... | Notebook    | [973a3662b9](https://linux-hardware.org/?probe=973a3662b9) | Oct 29, 2022 |
| Kruger&Mat... | KM1406                      | Notebook    | [70b8441ccf](https://linux-hardware.org/?probe=70b8441ccf) | Oct 29, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [91f0c87afa](https://linux-hardware.org/?probe=91f0c87afa) | Oct 29, 2022 |
| MSI           | B560M PRO                   | Desktop     | [a84dc6f9cb](https://linux-hardware.org/?probe=a84dc6f9cb) | Oct 29, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [59c02d4967](https://linux-hardware.org/?probe=59c02d4967) | Oct 28, 2022 |
| Dell          | Latitude 5531               | Notebook    | [a7ff9a34d2](https://linux-hardware.org/?probe=a7ff9a34d2) | Oct 28, 2022 |
| Dell          | Latitude 5531               | Notebook    | [73ddced77b](https://linux-hardware.org/?probe=73ddced77b) | Oct 28, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [89cc00ef58](https://linux-hardware.org/?probe=89cc00ef58) | Oct 28, 2022 |
| Fujitsu       | LIFEBOOK U728               | Notebook    | [c5867e7dd3](https://linux-hardware.org/?probe=c5867e7dd3) | Oct 28, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [d3879c6bb0](https://linux-hardware.org/?probe=d3879c6bb0) | Oct 28, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [9914e4d771](https://linux-hardware.org/?probe=9914e4d771) | Oct 28, 2022 |
| HP            | ProBook x360 11 G3 EE       | Convertible | [61e43ba85d](https://linux-hardware.org/?probe=61e43ba85d) | Oct 28, 2022 |
| Lenovo        | ThinkPad T430 23498M7       | Notebook    | [f936993d28](https://linux-hardware.org/?probe=f936993d28) | Oct 28, 2022 |
| Gateway       | P-7805u                     | Notebook    | [7597071801](https://linux-hardware.org/?probe=7597071801) | Oct 28, 2022 |
| Dell          | Latitude E6530              | Notebook    | [71b2df6eff](https://linux-hardware.org/?probe=71b2df6eff) | Oct 27, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [4261d8dd66](https://linux-hardware.org/?probe=4261d8dd66) | Oct 27, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [216730dba7](https://linux-hardware.org/?probe=216730dba7) | Oct 27, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [00e77b8815](https://linux-hardware.org/?probe=00e77b8815) | Oct 26, 2022 |
| Dell          | Latitude E6530              | Notebook    | [c271a351aa](https://linux-hardware.org/?probe=c271a351aa) | Oct 26, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [94d1c333ac](https://linux-hardware.org/?probe=94d1c333ac) | Oct 26, 2022 |
| HUAWEI        | HKD-WXX                     | Notebook    | [2ff7652d3a](https://linux-hardware.org/?probe=2ff7652d3a) | Oct 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [082e572642](https://linux-hardware.org/?probe=082e572642) | Oct 26, 2022 |
| Lenovo        | ThinkPad T490s 20NX002QU... | Notebook    | [6ba1aaf015](https://linux-hardware.org/?probe=6ba1aaf015) | Oct 26, 2022 |
| Lenovo        | ThinkPad T490s 20NX002QU... | Notebook    | [062d1d3b82](https://linux-hardware.org/?probe=062d1d3b82) | Oct 26, 2022 |
| Lenovo        | ThinkPad R500 2716W2K       | Notebook    | [c9a59d0ee9](https://linux-hardware.org/?probe=c9a59d0ee9) | Oct 26, 2022 |
| Gigabyte      | P35-DS3L                    | Desktop     | [2f5cb804c0](https://linux-hardware.org/?probe=2f5cb804c0) | Oct 25, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [18df556ca1](https://linux-hardware.org/?probe=18df556ca1) | Oct 25, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [a515dd93cd](https://linux-hardware.org/?probe=a515dd93cd) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6e98085fc5](https://linux-hardware.org/?probe=6e98085fc5) | Oct 25, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [ecbfb1ca5c](https://linux-hardware.org/?probe=ecbfb1ca5c) | Oct 25, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [fbec0d9d0e](https://linux-hardware.org/?probe=fbec0d9d0e) | Oct 24, 2022 |
| Lenovo        | ThinkPad T490 20N3S9DJ00    | Notebook    | [c1a4fde481](https://linux-hardware.org/?probe=c1a4fde481) | Oct 24, 2022 |
| Lenovo        | ThinkPad T490 20N3S9DJ00    | Notebook    | [80bf151a4d](https://linux-hardware.org/?probe=80bf151a4d) | Oct 24, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [083b2c218e](https://linux-hardware.org/?probe=083b2c218e) | Oct 24, 2022 |
| Dell          | Latitude 3190               | Notebook    | [b116ac92f3](https://linux-hardware.org/?probe=b116ac92f3) | Oct 24, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [ce77ed764b](https://linux-hardware.org/?probe=ce77ed764b) | Oct 24, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [d18380bf4c](https://linux-hardware.org/?probe=d18380bf4c) | Oct 24, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [d28d720a26](https://linux-hardware.org/?probe=d28d720a26) | Oct 23, 2022 |
| Dell          | Latitude 7390               | Notebook    | [f282e79ccb](https://linux-hardware.org/?probe=f282e79ccb) | Oct 23, 2022 |
| Dell          | Latitude 7390               | Notebook    | [ec27a5efb5](https://linux-hardware.org/?probe=ec27a5efb5) | Oct 23, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [b940acb734](https://linux-hardware.org/?probe=b940acb734) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [9035fff7ea](https://linux-hardware.org/?probe=9035fff7ea) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [3d2171b17e](https://linux-hardware.org/?probe=3d2171b17e) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [1f26696990](https://linux-hardware.org/?probe=1f26696990) | Oct 22, 2022 |
| Dell          | 0HX555                      | Desktop     | [86339c4a3f](https://linux-hardware.org/?probe=86339c4a3f) | Oct 22, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | Notebook    | [88a93e44f9](https://linux-hardware.org/?probe=88a93e44f9) | Oct 22, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [1056e456bc](https://linux-hardware.org/?probe=1056e456bc) | Oct 22, 2022 |
| ASUSTek       | X550LN                      | Notebook    | [7a6daf6023](https://linux-hardware.org/?probe=7a6daf6023) | Oct 22, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | Desktop     | [624b9f3b57](https://linux-hardware.org/?probe=624b9f3b57) | Oct 22, 2022 |
| HP            | EliteBook x360 1030 G4      | Convertible | [c853f4446a](https://linux-hardware.org/?probe=c853f4446a) | Oct 22, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [f5af95bb9a](https://linux-hardware.org/?probe=f5af95bb9a) | Oct 21, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [5def3f5324](https://linux-hardware.org/?probe=5def3f5324) | Oct 21, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [d607def641](https://linux-hardware.org/?probe=d607def641) | Oct 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [7cd6e349f0](https://linux-hardware.org/?probe=7cd6e349f0) | Oct 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [344040aee1](https://linux-hardware.org/?probe=344040aee1) | Oct 19, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [7f736b0a22](https://linux-hardware.org/?probe=7f736b0a22) | Oct 19, 2022 |
| HP            | 1825                        | Desktop     | [e0a35f1d0f](https://linux-hardware.org/?probe=e0a35f1d0f) | Oct 19, 2022 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [67ebd92594](https://linux-hardware.org/?probe=67ebd92594) | Oct 19, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [5d65b94f2b](https://linux-hardware.org/?probe=5d65b94f2b) | Oct 19, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [431a84fc31](https://linux-hardware.org/?probe=431a84fc31) | Oct 18, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [fc51a7c9dc](https://linux-hardware.org/?probe=fc51a7c9dc) | Oct 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [8bc82af4e5](https://linux-hardware.org/?probe=8bc82af4e5) | Oct 18, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [fcac80ff4a](https://linux-hardware.org/?probe=fcac80ff4a) | Oct 18, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [7639ea3b73](https://linux-hardware.org/?probe=7639ea3b73) | Oct 18, 2022 |
| Dell          | Latitude 5421               | Notebook    | [77cbc2b788](https://linux-hardware.org/?probe=77cbc2b788) | Oct 18, 2022 |
| Dell          | Vostro 7580                 | Notebook    | [69cc3a8c62](https://linux-hardware.org/?probe=69cc3a8c62) | Oct 18, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [2f27f08ce8](https://linux-hardware.org/?probe=2f27f08ce8) | Oct 17, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [b8dbd1daf9](https://linux-hardware.org/?probe=b8dbd1daf9) | Oct 17, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e8377da07e](https://linux-hardware.org/?probe=e8377da07e) | Oct 17, 2022 |
| Dell          | Inspiron 3541               | Notebook    | [858e5b974b](https://linux-hardware.org/?probe=858e5b974b) | Oct 17, 2022 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [4fe1c6d3e8](https://linux-hardware.org/?probe=4fe1c6d3e8) | Oct 17, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [b7ea5640c2](https://linux-hardware.org/?probe=b7ea5640c2) | Oct 17, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [2d7d5c19c0](https://linux-hardware.org/?probe=2d7d5c19c0) | Oct 17, 2022 |
| Dell          | Latitude E6430              | Notebook    | [2e8f3bd664](https://linux-hardware.org/?probe=2e8f3bd664) | Oct 16, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [e0400f3015](https://linux-hardware.org/?probe=e0400f3015) | Oct 16, 2022 |
| Gigabyte      | H61M-D2H                    | Desktop     | [3c51ad7454](https://linux-hardware.org/?probe=3c51ad7454) | Oct 15, 2022 |
| Acer          | Aspire SW5-012              | Notebook    | [530046bf8a](https://linux-hardware.org/?probe=530046bf8a) | Oct 15, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [bf6d77aefd](https://linux-hardware.org/?probe=bf6d77aefd) | Oct 15, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [bb7d61198e](https://linux-hardware.org/?probe=bb7d61198e) | Oct 14, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [720d282dfe](https://linux-hardware.org/?probe=720d282dfe) | Oct 14, 2022 |
| HP            | ENVY 15                     | Notebook    | [09bfbadebe](https://linux-hardware.org/?probe=09bfbadebe) | Oct 14, 2022 |
| MSI           | MS-N014                     | Notebook    | [87e6e540be](https://linux-hardware.org/?probe=87e6e540be) | Oct 14, 2022 |
| Lenovo        | G500s 20245                 | Notebook    | [61539bde5e](https://linux-hardware.org/?probe=61539bde5e) | Oct 13, 2022 |
| Dell          | Inspiron 5551               | Notebook    | [64865d9bb5](https://linux-hardware.org/?probe=64865d9bb5) | Oct 13, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [dd887afd02](https://linux-hardware.org/?probe=dd887afd02) | Oct 13, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [973f501233](https://linux-hardware.org/?probe=973f501233) | Oct 13, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [37b9e0d491](https://linux-hardware.org/?probe=37b9e0d491) | Oct 13, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [8e564b93cb](https://linux-hardware.org/?probe=8e564b93cb) | Oct 13, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [a122b26729](https://linux-hardware.org/?probe=a122b26729) | Oct 12, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [7706fb5578](https://linux-hardware.org/?probe=7706fb5578) | Oct 12, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [8437ac2ffc](https://linux-hardware.org/?probe=8437ac2ffc) | Oct 12, 2022 |
| Lenovo        | ThinkPad T530 24297TG       | Notebook    | [d6dec1ab6d](https://linux-hardware.org/?probe=d6dec1ab6d) | Oct 12, 2022 |
| ASUSTek       | X705UDR                     | Notebook    | [5c8601bb4f](https://linux-hardware.org/?probe=5c8601bb4f) | Oct 11, 2022 |
| ASUSTek       | G750JW                      | Notebook    | [251f32c620](https://linux-hardware.org/?probe=251f32c620) | Oct 11, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [a993db557b](https://linux-hardware.org/?probe=a993db557b) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [2f346a2afb](https://linux-hardware.org/?probe=2f346a2afb) | Oct 11, 2022 |
| Lenovo        | ThinkPad X200s 7470A98      | Notebook    | [2aea48a0f2](https://linux-hardware.org/?probe=2aea48a0f2) | Oct 11, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [b88e8a8b49](https://linux-hardware.org/?probe=b88e8a8b49) | Oct 11, 2022 |
| Lenovo        | ThinkPad X200s 7470A98      | Notebook    | [10d90de300](https://linux-hardware.org/?probe=10d90de300) | Oct 11, 2022 |
| Lenovo        | ThinkPad P50 20EQS5MP00     | Notebook    | [83858a99c3](https://linux-hardware.org/?probe=83858a99c3) | Oct 10, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [9e82633709](https://linux-hardware.org/?probe=9e82633709) | Oct 10, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | Notebook    | [4c575be5d7](https://linux-hardware.org/?probe=4c575be5d7) | Oct 10, 2022 |
| Acer          | Enduro EUN314-51W           | Notebook    | [14741407aa](https://linux-hardware.org/?probe=14741407aa) | Oct 10, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [b04149c5ea](https://linux-hardware.org/?probe=b04149c5ea) | Oct 10, 2022 |
| Dell          | Latitude 3190               | Notebook    | [bee132f486](https://linux-hardware.org/?probe=bee132f486) | Oct 10, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [cde031e816](https://linux-hardware.org/?probe=cde031e816) | Oct 10, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [d7bcf0afa3](https://linux-hardware.org/?probe=d7bcf0afa3) | Oct 09, 2022 |
| ASUSTek       | P5Q Premium                 | Desktop     | [8c0a201199](https://linux-hardware.org/?probe=8c0a201199) | Oct 09, 2022 |
| ASUSTek       | GL503VD                     | Notebook    | [1405b367c2](https://linux-hardware.org/?probe=1405b367c2) | Oct 09, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [94ccd99c78](https://linux-hardware.org/?probe=94ccd99c78) | Oct 09, 2022 |
| Dell          | 0GM819                      | Desktop     | [e0266a8468](https://linux-hardware.org/?probe=e0266a8468) | Oct 09, 2022 |
| ASUSTek       | H81M-P                      | Desktop     | [907b7761d0](https://linux-hardware.org/?probe=907b7761d0) | Oct 09, 2022 |
| ASUSTek       | H81M-P                      | Desktop     | [f2d9df375d](https://linux-hardware.org/?probe=f2d9df375d) | Oct 09, 2022 |
| ASUSTek       | X550VB                      | Notebook    | [a7c1c1cb1b](https://linux-hardware.org/?probe=a7c1c1cb1b) | Oct 09, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [8d58156239](https://linux-hardware.org/?probe=8d58156239) | Oct 09, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [cd707a79ef](https://linux-hardware.org/?probe=cd707a79ef) | Oct 09, 2022 |
| Foxconn       | H61MXT1/F2/-S/-V            | Desktop     | [be016db304](https://linux-hardware.org/?probe=be016db304) | Oct 08, 2022 |
| Dell          | Precision 7530              | Notebook    | [7f71730e68](https://linux-hardware.org/?probe=7f71730e68) | Oct 07, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [29de9dfa4a](https://linux-hardware.org/?probe=29de9dfa4a) | Oct 07, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [8a89e7f4da](https://linux-hardware.org/?probe=8a89e7f4da) | Oct 06, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [d4a282a4b8](https://linux-hardware.org/?probe=d4a282a4b8) | Oct 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [ae8f71dbd3](https://linux-hardware.org/?probe=ae8f71dbd3) | Oct 06, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [0f3e9273a6](https://linux-hardware.org/?probe=0f3e9273a6) | Oct 06, 2022 |
| Lenovo        | ThinkPad T480 20L50007PB    | Notebook    | [4c7a6898bf](https://linux-hardware.org/?probe=4c7a6898bf) | Oct 06, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [c12ce7288b](https://linux-hardware.org/?probe=c12ce7288b) | Oct 05, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [c3306965d6](https://linux-hardware.org/?probe=c3306965d6) | Oct 05, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [ed969ece24](https://linux-hardware.org/?probe=ed969ece24) | Oct 05, 2022 |
| Dell          | Precision 3541              | Notebook    | [bfef2cb8a3](https://linux-hardware.org/?probe=bfef2cb8a3) | Oct 05, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [2423d31aeb](https://linux-hardware.org/?probe=2423d31aeb) | Oct 05, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [147483a370](https://linux-hardware.org/?probe=147483a370) | Oct 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [ac2707d2e6](https://linux-hardware.org/?probe=ac2707d2e6) | Oct 05, 2022 |
| Lenovo        | ThinkPad T460p 20FW002CP... | Notebook    | [b7cd76d0b6](https://linux-hardware.org/?probe=b7cd76d0b6) | Oct 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d389c9fa00](https://linux-hardware.org/?probe=d389c9fa00) | Oct 05, 2022 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [736ded7422](https://linux-hardware.org/?probe=736ded7422) | Oct 04, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [b8ad7a8464](https://linux-hardware.org/?probe=b8ad7a8464) | Oct 04, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [1348c5b5eb](https://linux-hardware.org/?probe=1348c5b5eb) | Oct 03, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [563ae9b3df](https://linux-hardware.org/?probe=563ae9b3df) | Oct 03, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | Desktop     | [339dcddca7](https://linux-hardware.org/?probe=339dcddca7) | Oct 03, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [6c821c0c08](https://linux-hardware.org/?probe=6c821c0c08) | Oct 03, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [2dc13504cf](https://linux-hardware.org/?probe=2dc13504cf) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | Notebook    | [a9c2a1eca0](https://linux-hardware.org/?probe=a9c2a1eca0) | Oct 03, 2022 |
| ASUSTek       | 1225B                       | Notebook    | [9bb2d54ca7](https://linux-hardware.org/?probe=9bb2d54ca7) | Oct 03, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [9bf3a4a735](https://linux-hardware.org/?probe=9bf3a4a735) | Oct 03, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [6437ed8b0e](https://linux-hardware.org/?probe=6437ed8b0e) | Oct 03, 2022 |
| Dynabook      | PORTEGE X40-G               | Notebook    | [fc68a9cdbf](https://linux-hardware.org/?probe=fc68a9cdbf) | Oct 03, 2022 |
| Dell          | Latitude 3190               | Notebook    | [29b38a4a94](https://linux-hardware.org/?probe=29b38a4a94) | Oct 03, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [7fbccd3f20](https://linux-hardware.org/?probe=7fbccd3f20) | Oct 03, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [60bab6fe12](https://linux-hardware.org/?probe=60bab6fe12) | Oct 02, 2022 |
| Acer          | Veriton X6620G v1.0         | Desktop     | [80e98d9053](https://linux-hardware.org/?probe=80e98d9053) | Oct 02, 2022 |
| Acer          | Aspire 5755G                | Notebook    | [c552cb5631](https://linux-hardware.org/?probe=c552cb5631) | Oct 02, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [658873c1d0](https://linux-hardware.org/?probe=658873c1d0) | Oct 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [05e921b4aa](https://linux-hardware.org/?probe=05e921b4aa) | Oct 02, 2022 |
| Acer          | Aspire 4733Z                | Notebook    | [4be4debbe5](https://linux-hardware.org/?probe=4be4debbe5) | Oct 01, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | Notebook    | [34006e3b46](https://linux-hardware.org/?probe=34006e3b46) | Oct 01, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [aee33639b9](https://linux-hardware.org/?probe=aee33639b9) | Oct 01, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [bc6bcfe3f2](https://linux-hardware.org/?probe=bc6bcfe3f2) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [2d1e938e68](https://linux-hardware.org/?probe=2d1e938e68) | Oct 01, 2022 |
| Acer          | Aspire A715-74G             | Notebook    | [17abc08754](https://linux-hardware.org/?probe=17abc08754) | Sep 30, 2022 |
| HP            | Pavilion Laptop 17-ar0xx    | Notebook    | [733654d30d](https://linux-hardware.org/?probe=733654d30d) | Sep 30, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [fcf7e031e3](https://linux-hardware.org/?probe=fcf7e031e3) | Sep 30, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [f9582eb0a8](https://linux-hardware.org/?probe=f9582eb0a8) | Sep 29, 2022 |
| Lenovo        | G500s 20245                 | Notebook    | [b9001f7817](https://linux-hardware.org/?probe=b9001f7817) | Sep 29, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [be74c01cca](https://linux-hardware.org/?probe=be74c01cca) | Sep 29, 2022 |
| Dell          | Latitude E6330              | Notebook    | [b075fbcb56](https://linux-hardware.org/?probe=b075fbcb56) | Sep 29, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [82528435d8](https://linux-hardware.org/?probe=82528435d8) | Sep 29, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [4b9249b9b0](https://linux-hardware.org/?probe=4b9249b9b0) | Sep 29, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [d23d86be40](https://linux-hardware.org/?probe=d23d86be40) | Sep 28, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [a42a4722f7](https://linux-hardware.org/?probe=a42a4722f7) | Sep 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [bdc84f1b9b](https://linux-hardware.org/?probe=bdc84f1b9b) | Sep 28, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [1bdf72d415](https://linux-hardware.org/?probe=1bdf72d415) | Sep 27, 2022 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | Notebook    | [04fbd64661](https://linux-hardware.org/?probe=04fbd64661) | Sep 27, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [f35f96af50](https://linux-hardware.org/?probe=f35f96af50) | Sep 27, 2022 |
| Dell          | Precision 3561              | Notebook    | [77a4030052](https://linux-hardware.org/?probe=77a4030052) | Sep 27, 2022 |
| Dell          | 0DC48C A02                  | Desktop     | [9292e820c5](https://linux-hardware.org/?probe=9292e820c5) | Sep 27, 2022 |
| Toshiba       | Satellite C850-1LK          | Notebook    | [f0240dcb2d](https://linux-hardware.org/?probe=f0240dcb2d) | Sep 27, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | Notebook    | [70860ec433](https://linux-hardware.org/?probe=70860ec433) | Sep 26, 2022 |
| HP            | 805D                        | Desktop     | [b023737f63](https://linux-hardware.org/?probe=b023737f63) | Sep 26, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | Notebook    | [cb5f6f279b](https://linux-hardware.org/?probe=cb5f6f279b) | Sep 26, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | Notebook    | [3f11c520e0](https://linux-hardware.org/?probe=3f11c520e0) | Sep 26, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [476623a6a1](https://linux-hardware.org/?probe=476623a6a1) | Sep 26, 2022 |
| Dell          | Latitude 3190               | Notebook    | [27ac75e10c](https://linux-hardware.org/?probe=27ac75e10c) | Sep 26, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [6d3f575c3d](https://linux-hardware.org/?probe=6d3f575c3d) | Sep 26, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c447921f07](https://linux-hardware.org/?probe=c447921f07) | Sep 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [ebf3e70cf7](https://linux-hardware.org/?probe=ebf3e70cf7) | Sep 25, 2022 |
| Acer          | P5WE0                       | Notebook    | [124f7bdd77](https://linux-hardware.org/?probe=124f7bdd77) | Sep 25, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [d9f9db839d](https://linux-hardware.org/?probe=d9f9db839d) | Sep 25, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [8de01689b6](https://linux-hardware.org/?probe=8de01689b6) | Sep 24, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [dafafa97a4](https://linux-hardware.org/?probe=dafafa97a4) | Sep 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [89a1a3179d](https://linux-hardware.org/?probe=89a1a3179d) | Sep 24, 2022 |
| Toshiba       | Satellite P205              | Notebook    | [2a1450578e](https://linux-hardware.org/?probe=2a1450578e) | Sep 23, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [ceda61113a](https://linux-hardware.org/?probe=ceda61113a) | Sep 23, 2022 |
| Toshiba       | Satellite P205              | Notebook    | [98e97d946a](https://linux-hardware.org/?probe=98e97d946a) | Sep 23, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [36c369745a](https://linux-hardware.org/?probe=36c369745a) | Sep 23, 2022 |
| HP            | 3032h                       | Desktop     | [efb6671159](https://linux-hardware.org/?probe=efb6671159) | Sep 23, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [0121aac33a](https://linux-hardware.org/?probe=0121aac33a) | Sep 22, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [de7c138e21](https://linux-hardware.org/?probe=de7c138e21) | Sep 22, 2022 |
| MSI           | 760GM-P34                   | Desktop     | [af750add66](https://linux-hardware.org/?probe=af750add66) | Sep 22, 2022 |
| MSI           | H81M-P33                    | Desktop     | [05d5a24774](https://linux-hardware.org/?probe=05d5a24774) | Sep 22, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [671c1cb6c4](https://linux-hardware.org/?probe=671c1cb6c4) | Sep 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [967110ef60](https://linux-hardware.org/?probe=967110ef60) | Sep 21, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [978c6dd9dd](https://linux-hardware.org/?probe=978c6dd9dd) | Sep 21, 2022 |
| Xunlong       | Orange Pi Zero              | Soc         | [0aa622cc13](https://linux-hardware.org/?probe=0aa622cc13) | Sep 21, 2022 |
| Dell          | 0D883F A06                  | Desktop     | [01c50a7a4c](https://linux-hardware.org/?probe=01c50a7a4c) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [d22f082243](https://linux-hardware.org/?probe=d22f082243) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [e4f1a8245a](https://linux-hardware.org/?probe=e4f1a8245a) | Sep 21, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bdb353fd2c](https://linux-hardware.org/?probe=bdb353fd2c) | Sep 20, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [030ce84327](https://linux-hardware.org/?probe=030ce84327) | Sep 20, 2022 |
| Framework     | Laptop                      | Notebook    | [dd163cfa96](https://linux-hardware.org/?probe=dd163cfa96) | Sep 20, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [21c74278f8](https://linux-hardware.org/?probe=21c74278f8) | Sep 20, 2022 |
| Dell          | Latitude E4310              | Notebook    | [c77a454d4e](https://linux-hardware.org/?probe=c77a454d4e) | Sep 20, 2022 |
| Dell          | Latitude E4310              | Notebook    | [4e8bf046d8](https://linux-hardware.org/?probe=4e8bf046d8) | Sep 19, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [e6898c8aa0](https://linux-hardware.org/?probe=e6898c8aa0) | Sep 19, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [85952e171d](https://linux-hardware.org/?probe=85952e171d) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [eb67db5bff](https://linux-hardware.org/?probe=eb67db5bff) | Sep 19, 2022 |
| Lenovo        | ThinkPad T420 4180MY7       | Notebook    | [e6a930e933](https://linux-hardware.org/?probe=e6a930e933) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [793fa18b58](https://linux-hardware.org/?probe=793fa18b58) | Sep 19, 2022 |
| ASUSTek       | GL502VSK                    | Notebook    | [a6dc9b627f](https://linux-hardware.org/?probe=a6dc9b627f) | Sep 19, 2022 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [419bf72e22](https://linux-hardware.org/?probe=419bf72e22) | Sep 19, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [1f2bd2202c](https://linux-hardware.org/?probe=1f2bd2202c) | Sep 19, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f96d782326](https://linux-hardware.org/?probe=f96d782326) | Sep 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [52352bab7a](https://linux-hardware.org/?probe=52352bab7a) | Sep 19, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [eb1c0556c3](https://linux-hardware.org/?probe=eb1c0556c3) | Sep 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5a9ab0de04](https://linux-hardware.org/?probe=5a9ab0de04) | Sep 18, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [b3cb8fc82e](https://linux-hardware.org/?probe=b3cb8fc82e) | Sep 18, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [e903dccaf1](https://linux-hardware.org/?probe=e903dccaf1) | Sep 18, 2022 |
| Gigabyte      | B560M D3H                   | Desktop     | [515d75e6b7](https://linux-hardware.org/?probe=515d75e6b7) | Sep 17, 2022 |
| HP            | Notebook                    | Notebook    | [d29681d2ed](https://linux-hardware.org/?probe=d29681d2ed) | Sep 17, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [9c23c7bb58](https://linux-hardware.org/?probe=9c23c7bb58) | Sep 17, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [5023f912e2](https://linux-hardware.org/?probe=5023f912e2) | Sep 16, 2022 |
| Lenovo        | ThinkPad T420 4180A32       | Notebook    | [44841341fd](https://linux-hardware.org/?probe=44841341fd) | Sep 16, 2022 |
| Dell          | Latitude 5511               | Notebook    | [9a2faa8d22](https://linux-hardware.org/?probe=9a2faa8d22) | Sep 16, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [b15d9e1fe4](https://linux-hardware.org/?probe=b15d9e1fe4) | Sep 16, 2022 |
| Pine Micro... | Pine64 Rock64               | Soc         | [dbd6ac01d6](https://linux-hardware.org/?probe=dbd6ac01d6) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | Notebook    | [099e5d3523](https://linux-hardware.org/?probe=099e5d3523) | Sep 16, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [fcdfa43a37](https://linux-hardware.org/?probe=fcdfa43a37) | Sep 15, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [1c131a1acb](https://linux-hardware.org/?probe=1c131a1acb) | Sep 15, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f12132c99f](https://linux-hardware.org/?probe=f12132c99f) | Sep 14, 2022 |
| Dell          | Inspiron 5584               | Notebook    | [677d683644](https://linux-hardware.org/?probe=677d683644) | Sep 14, 2022 |
| Dell          | Latitude 5521               | Notebook    | [c342e3ab13](https://linux-hardware.org/?probe=c342e3ab13) | Sep 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [98ae2af06f](https://linux-hardware.org/?probe=98ae2af06f) | Sep 14, 2022 |
| Sun Micros... | ASSY,MOTHERBOARD,X4170 5... | Server      | [ea845ec5ea](https://linux-hardware.org/?probe=ea845ec5ea) | Sep 13, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [f06aa45765](https://linux-hardware.org/?probe=f06aa45765) | Sep 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [efc31007ac](https://linux-hardware.org/?probe=efc31007ac) | Sep 12, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [225bd59ba7](https://linux-hardware.org/?probe=225bd59ba7) | Sep 12, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3c0abb17a9](https://linux-hardware.org/?probe=3c0abb17a9) | Sep 12, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [ed5273b278](https://linux-hardware.org/?probe=ed5273b278) | Sep 11, 2022 |
| Gigabyte      | G41MT-ES2L                  | Desktop     | [74ee0e38a3](https://linux-hardware.org/?probe=74ee0e38a3) | Sep 11, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [0c536307da](https://linux-hardware.org/?probe=0c536307da) | Sep 11, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [eff4400b7d](https://linux-hardware.org/?probe=eff4400b7d) | Sep 10, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [6d032338c0](https://linux-hardware.org/?probe=6d032338c0) | Sep 10, 2022 |
| Lenovo        | ThinkPad L420 7829H86       | Notebook    | [406535e915](https://linux-hardware.org/?probe=406535e915) | Sep 10, 2022 |
| Acer          | Nitro AN517-55              | Notebook    | [16fa00177a](https://linux-hardware.org/?probe=16fa00177a) | Sep 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6248f4732d](https://linux-hardware.org/?probe=6248f4732d) | Sep 10, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [ef6556670c](https://linux-hardware.org/?probe=ef6556670c) | Sep 09, 2022 |
| Dell          | Latitude E6330              | Notebook    | [9f2183ce75](https://linux-hardware.org/?probe=9f2183ce75) | Sep 09, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [c2f25bcea8](https://linux-hardware.org/?probe=c2f25bcea8) | Sep 08, 2022 |
| Gigabyte      | AORUS 15G XC                | Notebook    | [ea131dfe2c](https://linux-hardware.org/?probe=ea131dfe2c) | Sep 08, 2022 |
| Dell          | Latitude E6540              | Notebook    | [5700f37281](https://linux-hardware.org/?probe=5700f37281) | Sep 08, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [6812b52b92](https://linux-hardware.org/?probe=6812b52b92) | Sep 08, 2022 |
| Dell          | Inspiron 3541               | Notebook    | [2cc868e8f0](https://linux-hardware.org/?probe=2cc868e8f0) | Sep 08, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [bb2d82813c](https://linux-hardware.org/?probe=bb2d82813c) | Sep 08, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [e757b79169](https://linux-hardware.org/?probe=e757b79169) | Sep 08, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [6ee5358914](https://linux-hardware.org/?probe=6ee5358914) | Sep 08, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [63524aa492](https://linux-hardware.org/?probe=63524aa492) | Sep 07, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [5cf26fac4d](https://linux-hardware.org/?probe=5cf26fac4d) | Sep 07, 2022 |
| HP            | 1497                        | Desktop     | [3cf8f5d97a](https://linux-hardware.org/?probe=3cf8f5d97a) | Sep 07, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [a6b07acfe5](https://linux-hardware.org/?probe=a6b07acfe5) | Sep 07, 2022 |
| Dell          | 0DR845                      | Desktop     | [f945fc3f5e](https://linux-hardware.org/?probe=f945fc3f5e) | Sep 07, 2022 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | Desktop     | [a816f4f60b](https://linux-hardware.org/?probe=a816f4f60b) | Sep 07, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [4adadf9e6a](https://linux-hardware.org/?probe=4adadf9e6a) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [4615004e85](https://linux-hardware.org/?probe=4615004e85) | Sep 06, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [5f7f592f25](https://linux-hardware.org/?probe=5f7f592f25) | Sep 05, 2022 |
| MSI           | B85M-E43 DASH               | Desktop     | [f52a53f4a7](https://linux-hardware.org/?probe=f52a53f4a7) | Sep 05, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [e0bb6ae251](https://linux-hardware.org/?probe=e0bb6ae251) | Sep 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [25c70ea2f3](https://linux-hardware.org/?probe=25c70ea2f3) | Sep 05, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [1d90e3b685](https://linux-hardware.org/?probe=1d90e3b685) | Sep 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [d802875fec](https://linux-hardware.org/?probe=d802875fec) | Sep 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [96d17dc188](https://linux-hardware.org/?probe=96d17dc188) | Sep 04, 2022 |
| Dell          | Latitude E6330              | Notebook    | [e4dcf51a84](https://linux-hardware.org/?probe=e4dcf51a84) | Sep 04, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [4f45b8e600](https://linux-hardware.org/?probe=4f45b8e600) | Sep 04, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [87a6f9162a](https://linux-hardware.org/?probe=87a6f9162a) | Sep 03, 2022 |
| HP            | 620                         | Notebook    | [096486e01d](https://linux-hardware.org/?probe=096486e01d) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6b62abaaaf](https://linux-hardware.org/?probe=6b62abaaaf) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ec466abbf7](https://linux-hardware.org/?probe=ec466abbf7) | Sep 03, 2022 |
| Dell          | Latitude E6330              | Notebook    | [626c1e28b1](https://linux-hardware.org/?probe=626c1e28b1) | Sep 03, 2022 |
| Dell          | Latitude E6330              | Notebook    | [6c7adba5b6](https://linux-hardware.org/?probe=6c7adba5b6) | Sep 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [6669ffa68e](https://linux-hardware.org/?probe=6669ffa68e) | Sep 02, 2022 |
| Dell          | Latitude E6220              | Notebook    | [e249853663](https://linux-hardware.org/?probe=e249853663) | Sep 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [8320ded55c](https://linux-hardware.org/?probe=8320ded55c) | Sep 02, 2022 |
| MSI           | B450 GAMING PLUS            | Desktop     | [3561723d92](https://linux-hardware.org/?probe=3561723d92) | Sep 02, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [5d85db2c66](https://linux-hardware.org/?probe=5d85db2c66) | Sep 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [ad3ce497e7](https://linux-hardware.org/?probe=ad3ce497e7) | Sep 02, 2022 |
| Dell          | Latitude E6220              | Notebook    | [99c8b865ad](https://linux-hardware.org/?probe=99c8b865ad) | Sep 02, 2022 |
| Dell          | Latitude E6330              | Notebook    | [179123f301](https://linux-hardware.org/?probe=179123f301) | Sep 01, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [12abd434b5](https://linux-hardware.org/?probe=12abd434b5) | Sep 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [e16313490d](https://linux-hardware.org/?probe=e16313490d) | Sep 01, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [31efc1e75f](https://linux-hardware.org/?probe=31efc1e75f) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [60db4bfa03](https://linux-hardware.org/?probe=60db4bfa03) | Aug 31, 2022 |
| ASUSTek       | P5K/EPU                     | Desktop     | [196d56922a](https://linux-hardware.org/?probe=196d56922a) | Aug 31, 2022 |
| Dell          | Latitude E6330              | Notebook    | [b5766d41fa](https://linux-hardware.org/?probe=b5766d41fa) | Aug 31, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d146908413](https://linux-hardware.org/?probe=d146908413) | Aug 31, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [f3389e42f8](https://linux-hardware.org/?probe=f3389e42f8) | Aug 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [49c235aa0d](https://linux-hardware.org/?probe=49c235aa0d) | Aug 30, 2022 |
| Lenovo        | ThinkPad L490 20Q5001YPB    | Notebook    | [daae538154](https://linux-hardware.org/?probe=daae538154) | Aug 30, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [1a8ff186c7](https://linux-hardware.org/?probe=1a8ff186c7) | Aug 29, 2022 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [4a96f9e792](https://linux-hardware.org/?probe=4a96f9e792) | Aug 29, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [e915bb3a8c](https://linux-hardware.org/?probe=e915bb3a8c) | Aug 29, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0998f7a5d1](https://linux-hardware.org/?probe=0998f7a5d1) | Aug 29, 2022 |
| Dell          | Latitude 9420               | Notebook    | [0b8d883170](https://linux-hardware.org/?probe=0b8d883170) | Aug 29, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [72c01f3cf1](https://linux-hardware.org/?probe=72c01f3cf1) | Aug 29, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [3b245a809d](https://linux-hardware.org/?probe=3b245a809d) | Aug 28, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [dcb225651d](https://linux-hardware.org/?probe=dcb225651d) | Aug 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [499889da7e](https://linux-hardware.org/?probe=499889da7e) | Aug 28, 2022 |
| ASUSTek       | F3E                         | Notebook    | [1314dc63b6](https://linux-hardware.org/?probe=1314dc63b6) | Aug 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [7ed4b144d7](https://linux-hardware.org/?probe=7ed4b144d7) | Aug 28, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [489691c2e3](https://linux-hardware.org/?probe=489691c2e3) | Aug 28, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [8fae050683](https://linux-hardware.org/?probe=8fae050683) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [afde42fb41](https://linux-hardware.org/?probe=afde42fb41) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6c1db95864](https://linux-hardware.org/?probe=6c1db95864) | Aug 28, 2022 |
| Dell          | Latitude E6400              | Notebook    | [666ba32534](https://linux-hardware.org/?probe=666ba32534) | Aug 28, 2022 |
| ASUSTek       | G15DK                       | Desktop     | [231c2674a6](https://linux-hardware.org/?probe=231c2674a6) | Aug 28, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [054a02f33e](https://linux-hardware.org/?probe=054a02f33e) | Aug 28, 2022 |
| ASUSTek       | P8B WS                      | Desktop     | [5f89ab0d00](https://linux-hardware.org/?probe=5f89ab0d00) | Aug 27, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [1912258e10](https://linux-hardware.org/?probe=1912258e10) | Aug 27, 2022 |
| HP            | 8054                        | Desktop     | [af4f950786](https://linux-hardware.org/?probe=af4f950786) | Aug 27, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [1813b94682](https://linux-hardware.org/?probe=1813b94682) | Aug 27, 2022 |
| HP            | 15                          | Notebook    | [310d617e09](https://linux-hardware.org/?probe=310d617e09) | Aug 26, 2022 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [0462079328](https://linux-hardware.org/?probe=0462079328) | Aug 25, 2022 |
| ASUSTek       | X705UAP                     | Notebook    | [eacfc15b6c](https://linux-hardware.org/?probe=eacfc15b6c) | Aug 24, 2022 |
| ASUSTek       | P5B                         | Desktop     | [27c91a4b60](https://linux-hardware.org/?probe=27c91a4b60) | Aug 24, 2022 |
| Dell          | Inspiron 5402               | Notebook    | [936ea503c8](https://linux-hardware.org/?probe=936ea503c8) | Aug 24, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d22f756c4c](https://linux-hardware.org/?probe=d22f756c4c) | Aug 24, 2022 |
| ASUSTek       | B85-PLUS                    | Desktop     | [1eba4b558d](https://linux-hardware.org/?probe=1eba4b558d) | Aug 23, 2022 |
| Dell          | 0T1D10 A01                  | Desktop     | [39e79a7077](https://linux-hardware.org/?probe=39e79a7077) | Aug 23, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [659e36b0ed](https://linux-hardware.org/?probe=659e36b0ed) | Aug 23, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [0796a8df9d](https://linux-hardware.org/?probe=0796a8df9d) | Aug 23, 2022 |
| HP            | EliteBook x360 1030 G4      | Convertible | [5e11bd516d](https://linux-hardware.org/?probe=5e11bd516d) | Aug 23, 2022 |
| Dell          | Latitude 5521               | Notebook    | [b14afc8c75](https://linux-hardware.org/?probe=b14afc8c75) | Aug 22, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [29d52f610c](https://linux-hardware.org/?probe=29d52f610c) | Aug 22, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [d37dfc0613](https://linux-hardware.org/?probe=d37dfc0613) | Aug 22, 2022 |
| Dell          | Latitude 3190               | Notebook    | [74fd1046be](https://linux-hardware.org/?probe=74fd1046be) | Aug 22, 2022 |
| Lenovo        | ThinkPad T400 6474B84       | Notebook    | [f8a6513790](https://linux-hardware.org/?probe=f8a6513790) | Aug 22, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f38202db0d](https://linux-hardware.org/?probe=f38202db0d) | Aug 21, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [a80c24ae6b](https://linux-hardware.org/?probe=a80c24ae6b) | Aug 21, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [33a9a68b5d](https://linux-hardware.org/?probe=33a9a68b5d) | Aug 21, 2022 |
| ASUSTek       | P7P55D-E                    | Desktop     | [7c83845247](https://linux-hardware.org/?probe=7c83845247) | Aug 20, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [2f5ef1300f](https://linux-hardware.org/?probe=2f5ef1300f) | Aug 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [eb63fecd35](https://linux-hardware.org/?probe=eb63fecd35) | Aug 19, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | Desktop     | [d39161dc13](https://linux-hardware.org/?probe=d39161dc13) | Aug 19, 2022 |
| HP            | Compaq nx7300 (RH678EA#A... | Notebook    | [6fc01cef23](https://linux-hardware.org/?probe=6fc01cef23) | Aug 19, 2022 |
| Acer          | Aspire E5-475               | Notebook    | [f21f1687d5](https://linux-hardware.org/?probe=f21f1687d5) | Aug 19, 2022 |
| Acer          | Aspire E5-475               | Notebook    | [04b38f1dfd](https://linux-hardware.org/?probe=04b38f1dfd) | Aug 19, 2022 |
| ASUSTek       | A88XM-E                     | Desktop     | [04d716a25d](https://linux-hardware.org/?probe=04d716a25d) | Aug 19, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ac7fb69037](https://linux-hardware.org/?probe=ac7fb69037) | Aug 19, 2022 |
| Dell          | Latitude 7280               | Notebook    | [63e00d0c9d](https://linux-hardware.org/?probe=63e00d0c9d) | Aug 18, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [fdcb40d147](https://linux-hardware.org/?probe=fdcb40d147) | Aug 18, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [cf5500d7b1](https://linux-hardware.org/?probe=cf5500d7b1) | Aug 18, 2022 |
| Lenovo        | ThinkPad E520 1143CWG       | Notebook    | [bc6f3f891a](https://linux-hardware.org/?probe=bc6f3f891a) | Aug 18, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [3d5404aaff](https://linux-hardware.org/?probe=3d5404aaff) | Aug 18, 2022 |
| ASRock        | H81M                        | Desktop     | [d59c4705a2](https://linux-hardware.org/?probe=d59c4705a2) | Aug 17, 2022 |
| MSI           | A320M-A PRO M2              | Desktop     | [abad46b854](https://linux-hardware.org/?probe=abad46b854) | Aug 17, 2022 |
| NEC Comput... | PC-LJ730MG6W                | Notebook    | [c0e6c7edb7](https://linux-hardware.org/?probe=c0e6c7edb7) | Aug 17, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1ea309e90c](https://linux-hardware.org/?probe=1ea309e90c) | Aug 17, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [d8e60dcf09](https://linux-hardware.org/?probe=d8e60dcf09) | Aug 17, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [7b3d6b544c](https://linux-hardware.org/?probe=7b3d6b544c) | Aug 16, 2022 |
| MSI           | GT72S 6QE                   | Notebook    | [20121e68c8](https://linux-hardware.org/?probe=20121e68c8) | Aug 16, 2022 |
| Dell          | Latitude 3190               | Notebook    | [5564506d3c](https://linux-hardware.org/?probe=5564506d3c) | Aug 15, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [08bf3d620e](https://linux-hardware.org/?probe=08bf3d620e) | Aug 15, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [48637ddb10](https://linux-hardware.org/?probe=48637ddb10) | Aug 14, 2022 |
| HP            | 8054                        | Desktop     | [75e3136f50](https://linux-hardware.org/?probe=75e3136f50) | Aug 14, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [cc28c5783a](https://linux-hardware.org/?probe=cc28c5783a) | Aug 14, 2022 |
| MSI           | A320M-A PRO M2              | Desktop     | [d0831907e8](https://linux-hardware.org/?probe=d0831907e8) | Aug 14, 2022 |
| Dell          | Latitude E5430 vPro         | Notebook    | [08f713e80b](https://linux-hardware.org/?probe=08f713e80b) | Aug 13, 2022 |
| HP            | EliteBook 2760p             | Notebook    | [bb4c1e4c3a](https://linux-hardware.org/?probe=bb4c1e4c3a) | Aug 13, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [f0e405bc07](https://linux-hardware.org/?probe=f0e405bc07) | Aug 13, 2022 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [2522ff1530](https://linux-hardware.org/?probe=2522ff1530) | Aug 13, 2022 |
| ASUSTek       | UX303LAB                    | Notebook    | [169419cea0](https://linux-hardware.org/?probe=169419cea0) | Aug 12, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [92cacb2a11](https://linux-hardware.org/?probe=92cacb2a11) | Aug 12, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [434ba505a3](https://linux-hardware.org/?probe=434ba505a3) | Aug 12, 2022 |
| HP            | EliteBook 2760p             | Notebook    | [0ce6a49a7f](https://linux-hardware.org/?probe=0ce6a49a7f) | Aug 12, 2022 |
| Lenovo        | Z710 20250                  | Notebook    | [8c7b1d0773](https://linux-hardware.org/?probe=8c7b1d0773) | Aug 11, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [6a07e79eb7](https://linux-hardware.org/?probe=6a07e79eb7) | Aug 11, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [7e83b07cca](https://linux-hardware.org/?probe=7e83b07cca) | Aug 11, 2022 |
| HP            | 255 G4                      | Notebook    | [3ed3978b93](https://linux-hardware.org/?probe=3ed3978b93) | Aug 11, 2022 |
| Alienware     | M17xR4                      | Notebook    | [a9d3769b5b](https://linux-hardware.org/?probe=a9d3769b5b) | Aug 10, 2022 |
| Dell          | Latitude 5521               | Notebook    | [25f117c439](https://linux-hardware.org/?probe=25f117c439) | Aug 10, 2022 |
| MSI           | B365M PRO-VDH               | Desktop     | [213778bd3c](https://linux-hardware.org/?probe=213778bd3c) | Aug 10, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [f3dcea80d5](https://linux-hardware.org/?probe=f3dcea80d5) | Aug 10, 2022 |
| HP            | Pavilion HDX9200            | Notebook    | [079cb2197b](https://linux-hardware.org/?probe=079cb2197b) | Aug 10, 2022 |
| HP            | 255 G4                      | Notebook    | [44b5858d14](https://linux-hardware.org/?probe=44b5858d14) | Aug 10, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [20f30b16e5](https://linux-hardware.org/?probe=20f30b16e5) | Aug 09, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [4f83e69c06](https://linux-hardware.org/?probe=4f83e69c06) | Aug 09, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [1c9cd79646](https://linux-hardware.org/?probe=1c9cd79646) | Aug 09, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMC    | Notebook    | [47d4f751e1](https://linux-hardware.org/?probe=47d4f751e1) | Aug 09, 2022 |
| ASUSTek       | A88XM-E                     | Desktop     | [f496954b96](https://linux-hardware.org/?probe=f496954b96) | Aug 08, 2022 |
| ASUSTek       | A88XM-E                     | Desktop     | [84dcf54ab8](https://linux-hardware.org/?probe=84dcf54ab8) | Aug 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [9943b58e25](https://linux-hardware.org/?probe=9943b58e25) | Aug 08, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1f10876798](https://linux-hardware.org/?probe=1f10876798) | Aug 08, 2022 |
| Dell          | Latitude 3190               | Notebook    | [5818ff09cb](https://linux-hardware.org/?probe=5818ff09cb) | Aug 08, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [71390cb3ec](https://linux-hardware.org/?probe=71390cb3ec) | Aug 07, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [ac538e23dc](https://linux-hardware.org/?probe=ac538e23dc) | Aug 07, 2022 |
| MSI           | A320M PRO-M2                | Desktop     | [43f6f3c828](https://linux-hardware.org/?probe=43f6f3c828) | Aug 07, 2022 |
| PC Special... | Recoil II                   | Notebook    | [1e05c3546f](https://linux-hardware.org/?probe=1e05c3546f) | Aug 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [95f444c24c](https://linux-hardware.org/?probe=95f444c24c) | Aug 07, 2022 |
| ASUSTek       | ROG Flow X16 GV601RM_GV6... | Convertible | [a35a597a1d](https://linux-hardware.org/?probe=a35a597a1d) | Aug 07, 2022 |
| ASUSTek       | K52JT                       | Notebook    | [013f296b81](https://linux-hardware.org/?probe=013f296b81) | Aug 07, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [0ae52eddd8](https://linux-hardware.org/?probe=0ae52eddd8) | Aug 07, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [b18ee3a2ff](https://linux-hardware.org/?probe=b18ee3a2ff) | Aug 06, 2022 |
| Gigabyte      | B550 GAMING X               | Desktop     | [b158696344](https://linux-hardware.org/?probe=b158696344) | Aug 06, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e0cfa37515](https://linux-hardware.org/?probe=e0cfa37515) | Aug 05, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [3c3a5af037](https://linux-hardware.org/?probe=3c3a5af037) | Aug 05, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [ccbb6bb183](https://linux-hardware.org/?probe=ccbb6bb183) | Aug 05, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [70d84ddbc1](https://linux-hardware.org/?probe=70d84ddbc1) | Aug 05, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [0a34d32db6](https://linux-hardware.org/?probe=0a34d32db6) | Aug 05, 2022 |
| Lenovo        | ThinkPad T440s 20AR003SM... | Notebook    | [e835f1eca5](https://linux-hardware.org/?probe=e835f1eca5) | Aug 04, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [a249c68580](https://linux-hardware.org/?probe=a249c68580) | Aug 04, 2022 |
| Fujitsu Si... | AMILO Li1705                | Notebook    | [87d90381e1](https://linux-hardware.org/?probe=87d90381e1) | Aug 04, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [7f2e8ddf72](https://linux-hardware.org/?probe=7f2e8ddf72) | Aug 04, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [e73f25c149](https://linux-hardware.org/?probe=e73f25c149) | Aug 03, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [fcef4276cb](https://linux-hardware.org/?probe=fcef4276cb) | Aug 03, 2022 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [1d0650ff70](https://linux-hardware.org/?probe=1d0650ff70) | Aug 03, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [87533b4847](https://linux-hardware.org/?probe=87533b4847) | Aug 03, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [76414b53ee](https://linux-hardware.org/?probe=76414b53ee) | Aug 03, 2022 |
| HP            | ProBook 650 G8 Notebook ... | Notebook    | [1b11fecca3](https://linux-hardware.org/?probe=1b11fecca3) | Aug 02, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [15bb5d1160](https://linux-hardware.org/?probe=15bb5d1160) | Aug 02, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [71c6ba6061](https://linux-hardware.org/?probe=71c6ba6061) | Aug 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [1f86e5fa57](https://linux-hardware.org/?probe=1f86e5fa57) | Aug 01, 2022 |
| HP            | EliteBook x360 1030 G4      | Convertible | [29295c7c8e](https://linux-hardware.org/?probe=29295c7c8e) | Aug 01, 2022 |
| HP            | EliteBook x360 1030 G4      | Convertible | [a56b47616c](https://linux-hardware.org/?probe=a56b47616c) | Aug 01, 2022 |
| Acer          | Aspire 5730                 | Notebook    | [1541bd94e2](https://linux-hardware.org/?probe=1541bd94e2) | Jul 31, 2022 |
| Acer          | Aspire V5-591G              | Notebook    | [80396b28bf](https://linux-hardware.org/?probe=80396b28bf) | Jul 31, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [097b95fdde](https://linux-hardware.org/?probe=097b95fdde) | Jul 31, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1051593809](https://linux-hardware.org/?probe=1051593809) | Jul 31, 2022 |
| HP            | 550                         | Notebook    | [efc4b32963](https://linux-hardware.org/?probe=efc4b32963) | Jul 30, 2022 |
| Lenovo        | 1051L 60073                 | Tablet      | [4ae44495ba](https://linux-hardware.org/?probe=4ae44495ba) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [10ece2cb6c](https://linux-hardware.org/?probe=10ece2cb6c) | Jul 30, 2022 |
| Dell          | XPS M1330                   | Notebook    | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | Desktop     | [13eff519f6](https://linux-hardware.org/?probe=13eff519f6) | Jul 30, 2022 |
| HP            | 21B4 A01                    | Desktop     | [474779f0b9](https://linux-hardware.org/?probe=474779f0b9) | Jul 30, 2022 |
| Acer          | Aspire 5730                 | Notebook    | [8ac8b8a87a](https://linux-hardware.org/?probe=8ac8b8a87a) | Jul 30, 2022 |
| Dell          | Precision 5550              | Notebook    | [e11d4be493](https://linux-hardware.org/?probe=e11d4be493) | Jul 30, 2022 |
| Lenovo        | ThinkPad L480 20LS002CPB    | Notebook    | [35764371d6](https://linux-hardware.org/?probe=35764371d6) | Jul 29, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [8415a45799](https://linux-hardware.org/?probe=8415a45799) | Jul 28, 2022 |
| Dell          | Latitude E7470              | Notebook    | [9f4d55071c](https://linux-hardware.org/?probe=9f4d55071c) | Jul 28, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [cb1458b51e](https://linux-hardware.org/?probe=cb1458b51e) | Jul 28, 2022 |
| HP            | ProLiant ML330 G6           | Desktop     | [7940deabb7](https://linux-hardware.org/?probe=7940deabb7) | Jul 28, 2022 |
| HP            | ProLiant ML330 G6           | Desktop     | [711602c0ac](https://linux-hardware.org/?probe=711602c0ac) | Jul 28, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [48e8d6fba9](https://linux-hardware.org/?probe=48e8d6fba9) | Jul 28, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [88ac64a1bd](https://linux-hardware.org/?probe=88ac64a1bd) | Jul 28, 2022 |
| Lenovo        | 1051L 60073                 | Tablet      | [2b505d28f7](https://linux-hardware.org/?probe=2b505d28f7) | Jul 27, 2022 |
| Lenovo        | 1051L 60073                 | Tablet      | [51bf4e60d3](https://linux-hardware.org/?probe=51bf4e60d3) | Jul 27, 2022 |
| MSI           | B250 PC MATE                | Desktop     | [dda7519d05](https://linux-hardware.org/?probe=dda7519d05) | Jul 27, 2022 |
| Dell          | Latitude 5421               | Notebook    | [ec91a9ea85](https://linux-hardware.org/?probe=ec91a9ea85) | Jul 27, 2022 |
| Dell          | 0G261D A00                  | Desktop     | [f7cb8645af](https://linux-hardware.org/?probe=f7cb8645af) | Jul 27, 2022 |
| Intel         | DH67VR AAG27177-201         | Desktop     | [3aeca135cd](https://linux-hardware.org/?probe=3aeca135cd) | Jul 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [05947b595a](https://linux-hardware.org/?probe=05947b595a) | Jul 26, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [4ddfbb6ad8](https://linux-hardware.org/?probe=4ddfbb6ad8) | Jul 26, 2022 |
| Toshiba       | Satellite L750D             | Notebook    | [c8e9ea3fdd](https://linux-hardware.org/?probe=c8e9ea3fdd) | Jul 26, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [aabcc30a17](https://linux-hardware.org/?probe=aabcc30a17) | Jul 25, 2022 |
| Dell          | Latitude 3190               | Notebook    | [2ec6ff1812](https://linux-hardware.org/?probe=2ec6ff1812) | Jul 25, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e1e16aa154](https://linux-hardware.org/?probe=e1e16aa154) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [123fc55893](https://linux-hardware.org/?probe=123fc55893) | Jul 24, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [153acd77c2](https://linux-hardware.org/?probe=153acd77c2) | Jul 24, 2022 |
| ASRock        | AM1H-ITX                    | Desktop     | [a15c82ba0c](https://linux-hardware.org/?probe=a15c82ba0c) | Jul 24, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [542296a447](https://linux-hardware.org/?probe=542296a447) | Jul 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [5658129aa4](https://linux-hardware.org/?probe=5658129aa4) | Jul 24, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [2b7f8eb0df](https://linux-hardware.org/?probe=2b7f8eb0df) | Jul 24, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [dc8bafd932](https://linux-hardware.org/?probe=dc8bafd932) | Jul 23, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | Notebook    | [b16e17a798](https://linux-hardware.org/?probe=b16e17a798) | Jul 23, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [597fb27e56](https://linux-hardware.org/?probe=597fb27e56) | Jul 23, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [8b1930ddbd](https://linux-hardware.org/?probe=8b1930ddbd) | Jul 22, 2022 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [c8e4c217c0](https://linux-hardware.org/?probe=c8e4c217c0) | Jul 22, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [4e47525879](https://linux-hardware.org/?probe=4e47525879) | Jul 22, 2022 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [e1099c5342](https://linux-hardware.org/?probe=e1099c5342) | Jul 22, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [8e0cd55a28](https://linux-hardware.org/?probe=8e0cd55a28) | Jul 22, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [abd0b78e41](https://linux-hardware.org/?probe=abd0b78e41) | Jul 21, 2022 |
| Dell          | Latitude E6540              | Notebook    | [4688c6f312](https://linux-hardware.org/?probe=4688c6f312) | Jul 21, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [03afe0a303](https://linux-hardware.org/?probe=03afe0a303) | Jul 20, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [63d34f24b6](https://linux-hardware.org/?probe=63d34f24b6) | Jul 20, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [83d1355e61](https://linux-hardware.org/?probe=83d1355e61) | Jul 19, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [68023f05e9](https://linux-hardware.org/?probe=68023f05e9) | Jul 18, 2022 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [4a97996102](https://linux-hardware.org/?probe=4a97996102) | Jul 18, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [4f4b63a026](https://linux-hardware.org/?probe=4f4b63a026) | Jul 18, 2022 |
| Dell          | Latitude 3190               | Notebook    | [4fa9fe26c1](https://linux-hardware.org/?probe=4fa9fe26c1) | Jul 18, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [8f2f1582e8](https://linux-hardware.org/?probe=8f2f1582e8) | Jul 17, 2022 |
| Intel         | DG31PR AAD97573-301         | Desktop     | [0ac01b7529](https://linux-hardware.org/?probe=0ac01b7529) | Jul 17, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [08446807d6](https://linux-hardware.org/?probe=08446807d6) | Jul 17, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [056d74f1a9](https://linux-hardware.org/?probe=056d74f1a9) | Jul 17, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [e454469a83](https://linux-hardware.org/?probe=e454469a83) | Jul 17, 2022 |
| MSI           | X370 KRAIT GAMING           | Desktop     | [e74a442ccc](https://linux-hardware.org/?probe=e74a442ccc) | Jul 17, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [18d1378620](https://linux-hardware.org/?probe=18d1378620) | Jul 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [e6b47dedd7](https://linux-hardware.org/?probe=e6b47dedd7) | Jul 15, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [75e4cc3704](https://linux-hardware.org/?probe=75e4cc3704) | Jul 15, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [ef0c958c66](https://linux-hardware.org/?probe=ef0c958c66) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [329ce2f7f8](https://linux-hardware.org/?probe=329ce2f7f8) | Jul 15, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [d6b737940e](https://linux-hardware.org/?probe=d6b737940e) | Jul 15, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [4d653cf4e6](https://linux-hardware.org/?probe=4d653cf4e6) | Jul 15, 2022 |
| Lenovo        | ThinkCentre M58p 6234F73    | Desktop     | [c5695a430f](https://linux-hardware.org/?probe=c5695a430f) | Jul 15, 2022 |
| Lenovo        | ThinkCentre M58p 6234F73    | Desktop     | [0a0ad06ece](https://linux-hardware.org/?probe=0a0ad06ece) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ea97effc52](https://linux-hardware.org/?probe=ea97effc52) | Jul 14, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [57ef4db755](https://linux-hardware.org/?probe=57ef4db755) | Jul 14, 2022 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [119c291cd5](https://linux-hardware.org/?probe=119c291cd5) | Jul 14, 2022 |
| Hyperbook     | Z15 Zen                     | Notebook    | [41129ecc5e](https://linux-hardware.org/?probe=41129ecc5e) | Jul 14, 2022 |
| Unknown       | Intel X79                   | Desktop     | [b0bb64b9ea](https://linux-hardware.org/?probe=b0bb64b9ea) | Jul 13, 2022 |
| MSI           | B250M PRO-VH                | Desktop     | [d0a4b76e78](https://linux-hardware.org/?probe=d0a4b76e78) | Jul 13, 2022 |
| HP            | 83E8                        | Desktop     | [a2dc0fc924](https://linux-hardware.org/?probe=a2dc0fc924) | Jul 13, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [c95dd7e491](https://linux-hardware.org/?probe=c95dd7e491) | Jul 13, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [7ecf3ad1b7](https://linux-hardware.org/?probe=7ecf3ad1b7) | Jul 13, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [f422c77bb1](https://linux-hardware.org/?probe=f422c77bb1) | Jul 12, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [495c5afa4b](https://linux-hardware.org/?probe=495c5afa4b) | Jul 12, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [2566bb66dd](https://linux-hardware.org/?probe=2566bb66dd) | Jul 12, 2022 |
| Dell          | Latitude E6420              | Notebook    | [d3bbc4a899](https://linux-hardware.org/?probe=d3bbc4a899) | Jul 12, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [6b29072d9e](https://linux-hardware.org/?probe=6b29072d9e) | Jul 11, 2022 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [24dc866c51](https://linux-hardware.org/?probe=24dc866c51) | Jul 11, 2022 |
| MSI           | H81M-P33                    | Desktop     | [05099f85ea](https://linux-hardware.org/?probe=05099f85ea) | Jul 11, 2022 |
| MSI           | B350 GAMING PLUS            | Desktop     | [778b1989d4](https://linux-hardware.org/?probe=778b1989d4) | Jul 11, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [fd9365ab43](https://linux-hardware.org/?probe=fd9365ab43) | Jul 11, 2022 |
| Dell          | Latitude 3190               | Notebook    | [b3c7283cdb](https://linux-hardware.org/?probe=b3c7283cdb) | Jul 11, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [f49fb95b26](https://linux-hardware.org/?probe=f49fb95b26) | Jul 10, 2022 |
| HP            | ProBook 4740s               | Notebook    | [18ff2d02bd](https://linux-hardware.org/?probe=18ff2d02bd) | Jul 10, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [6ed9abc24e](https://linux-hardware.org/?probe=6ed9abc24e) | Jul 10, 2022 |
| Lenovo        | SKYBAY NOK                  | Desktop     | [5e8f90f865](https://linux-hardware.org/?probe=5e8f90f865) | Jul 10, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [9da782ecf0](https://linux-hardware.org/?probe=9da782ecf0) | Jul 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c350afe818](https://linux-hardware.org/?probe=c350afe818) | Jul 10, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0237c9df10](https://linux-hardware.org/?probe=0237c9df10) | Jul 10, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [65c661af95](https://linux-hardware.org/?probe=65c661af95) | Jul 09, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [b8c450d5fa](https://linux-hardware.org/?probe=b8c450d5fa) | Jul 08, 2022 |
| Lenovo        | ThinkPad R61 8932FJG        | Notebook    | [d783a022b3](https://linux-hardware.org/?probe=d783a022b3) | Jul 08, 2022 |
| Dell          | Latitude D420               | Notebook    | [2e3ded5234](https://linux-hardware.org/?probe=2e3ded5234) | Jul 08, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [4a6cc98dd6](https://linux-hardware.org/?probe=4a6cc98dd6) | Jul 08, 2022 |
| MSI           | GF63 Thin 8RCS              | Notebook    | [886728c1b6](https://linux-hardware.org/?probe=886728c1b6) | Jul 08, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [5cf26aa015](https://linux-hardware.org/?probe=5cf26aa015) | Jul 08, 2022 |
| Lenovo        | ThinkPad T410 2537W2L       | Notebook    | [a2e55ad8ac](https://linux-hardware.org/?probe=a2e55ad8ac) | Jul 07, 2022 |
| MSI           | B250M BAZOOKA               | Desktop     | [e04f1fc85c](https://linux-hardware.org/?probe=e04f1fc85c) | Jul 07, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [b70f0fde7a](https://linux-hardware.org/?probe=b70f0fde7a) | Jul 07, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [c75201835c](https://linux-hardware.org/?probe=c75201835c) | Jul 06, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [4009adaca2](https://linux-hardware.org/?probe=4009adaca2) | Jul 05, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [7eb69e794e](https://linux-hardware.org/?probe=7eb69e794e) | Jul 05, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [b4732a4bda](https://linux-hardware.org/?probe=b4732a4bda) | Jul 05, 2022 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | Notebook    | [64dc631691](https://linux-hardware.org/?probe=64dc631691) | Jul 05, 2022 |
| HP            | ProBook 6475b               | Notebook    | [02eab8bd42](https://linux-hardware.org/?probe=02eab8bd42) | Jul 05, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [7d6a8718a8](https://linux-hardware.org/?probe=7d6a8718a8) | Jul 05, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [327086a8b8](https://linux-hardware.org/?probe=327086a8b8) | Jul 04, 2022 |
| Dell          | Latitude 7280               | Notebook    | [5333012df2](https://linux-hardware.org/?probe=5333012df2) | Jul 04, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f5c0f0798a](https://linux-hardware.org/?probe=f5c0f0798a) | Jul 04, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [740ba48457](https://linux-hardware.org/?probe=740ba48457) | Jul 03, 2022 |
| Dell          | Latitude E6420              | Notebook    | [e1b517f8af](https://linux-hardware.org/?probe=e1b517f8af) | Jul 03, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [6918411ee2](https://linux-hardware.org/?probe=6918411ee2) | Jul 03, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [a57cf9cc46](https://linux-hardware.org/?probe=a57cf9cc46) | Jul 03, 2022 |
| ASUSTek       | X55U                        | Notebook    | [ed55b4ef39](https://linux-hardware.org/?probe=ed55b4ef39) | Jul 03, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [6a5bc93a4b](https://linux-hardware.org/?probe=6a5bc93a4b) | Jul 03, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [6ffcfe37d6](https://linux-hardware.org/?probe=6ffcfe37d6) | Jul 03, 2022 |
| Lenovo        | ThinkPad E470 20H1007MPB    | Notebook    | [7a20748cc1](https://linux-hardware.org/?probe=7a20748cc1) | Jul 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [565fb652b8](https://linux-hardware.org/?probe=565fb652b8) | Jul 03, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | Notebook    | [8b717c6bdf](https://linux-hardware.org/?probe=8b717c6bdf) | Jul 02, 2022 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [d76404df8d](https://linux-hardware.org/?probe=d76404df8d) | Jul 02, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [c8b31466ed](https://linux-hardware.org/?probe=c8b31466ed) | Jul 02, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [9f1ed28d62](https://linux-hardware.org/?probe=9f1ed28d62) | Jul 02, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [163fad4354](https://linux-hardware.org/?probe=163fad4354) | Jul 02, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [10ff366630](https://linux-hardware.org/?probe=10ff366630) | Jul 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8e6d23cf01](https://linux-hardware.org/?probe=8e6d23cf01) | Jul 01, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [403db88011](https://linux-hardware.org/?probe=403db88011) | Jul 01, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [4ba5c0b79e](https://linux-hardware.org/?probe=4ba5c0b79e) | Jul 01, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [a32cb9b3f1](https://linux-hardware.org/?probe=a32cb9b3f1) | Jul 01, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [2671f4ffe2](https://linux-hardware.org/?probe=2671f4ffe2) | Jul 01, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [632dbea587](https://linux-hardware.org/?probe=632dbea587) | Jul 01, 2022 |
| Lenovo        | ThinkPad T450s 20BX002NM... | Notebook    | [3bb2e1821b](https://linux-hardware.org/?probe=3bb2e1821b) | Jul 01, 2022 |
| Dell          | Latitude 3420               | Notebook    | [651ab17da0](https://linux-hardware.org/?probe=651ab17da0) | Jun 30, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [06ca24d4e1](https://linux-hardware.org/?probe=06ca24d4e1) | Jun 30, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [aaf8589ded](https://linux-hardware.org/?probe=aaf8589ded) | Jun 30, 2022 |
| Framework     | Laptop                      | Notebook    | [61a6480a38](https://linux-hardware.org/?probe=61a6480a38) | Jun 30, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [6cf63ca19e](https://linux-hardware.org/?probe=6cf63ca19e) | Jun 30, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [0e09c926c1](https://linux-hardware.org/?probe=0e09c926c1) | Jun 30, 2022 |
| Dell          | Inspiron M5040              | Notebook    | [64c8f1ad3f](https://linux-hardware.org/?probe=64c8f1ad3f) | Jun 29, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [dbe5fe496a](https://linux-hardware.org/?probe=dbe5fe496a) | Jun 29, 2022 |
| Getac         | B300-X                      | Notebook    | [eb752b6c15](https://linux-hardware.org/?probe=eb752b6c15) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6dc02ab574](https://linux-hardware.org/?probe=6dc02ab574) | Jun 29, 2022 |
| Lenovo        | ThinkPad T420 4180MY7       | Notebook    | [a57e4e84f8](https://linux-hardware.org/?probe=a57e4e84f8) | Jun 29, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [bdecafbe1d](https://linux-hardware.org/?probe=bdecafbe1d) | Jun 29, 2022 |
| Dell          | Inspiron M5040              | Notebook    | [a9522b8288](https://linux-hardware.org/?probe=a9522b8288) | Jun 28, 2022 |
| Gigabyte      | B150-HD3 DDR3-CF            | Desktop     | [3fe71d66c6](https://linux-hardware.org/?probe=3fe71d66c6) | Jun 28, 2022 |
| Dell          | Latitude D420               | Notebook    | [c531c131ec](https://linux-hardware.org/?probe=c531c131ec) | Jun 28, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4c0fa03f61](https://linux-hardware.org/?probe=4c0fa03f61) | Jun 28, 2022 |
| Dell          | Latitude 5511               | Notebook    | [c361c37273](https://linux-hardware.org/?probe=c361c37273) | Jun 28, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [0ea209fffe](https://linux-hardware.org/?probe=0ea209fffe) | Jun 28, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [d399933441](https://linux-hardware.org/?probe=d399933441) | Jun 28, 2022 |
| Lenovo        | ThinkPad T470 20HES07J00    | Notebook    | [4be29eb5f1](https://linux-hardware.org/?probe=4be29eb5f1) | Jun 27, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3bf5b47ea1](https://linux-hardware.org/?probe=3bf5b47ea1) | Jun 27, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [a6555d107c](https://linux-hardware.org/?probe=a6555d107c) | Jun 27, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [79dca3a17c](https://linux-hardware.org/?probe=79dca3a17c) | Jun 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [1f3399d205](https://linux-hardware.org/?probe=1f3399d205) | Jun 26, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [02e93f831d](https://linux-hardware.org/?probe=02e93f831d) | Jun 26, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c84ca40dae](https://linux-hardware.org/?probe=c84ca40dae) | Jun 26, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d690a68389](https://linux-hardware.org/?probe=d690a68389) | Jun 25, 2022 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [6c6d94e4b7](https://linux-hardware.org/?probe=6c6d94e4b7) | Jun 25, 2022 |
| ASRock        | H87 Pro4                    | Desktop     | [47cf388077](https://linux-hardware.org/?probe=47cf388077) | Jun 25, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [e1918d8aab](https://linux-hardware.org/?probe=e1918d8aab) | Jun 25, 2022 |
| MSI           | H81M-P33                    | Desktop     | [9ba6c64800](https://linux-hardware.org/?probe=9ba6c64800) | Jun 25, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [fe8f74c9c1](https://linux-hardware.org/?probe=fe8f74c9c1) | Jun 25, 2022 |
| ASRock        | H87 Pro4                    | Desktop     | [73eb3e0db6](https://linux-hardware.org/?probe=73eb3e0db6) | Jun 25, 2022 |
| Unknown       | K8NF3-VSTA                  | Desktop     | [f2ea6e0d83](https://linux-hardware.org/?probe=f2ea6e0d83) | Jun 24, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [6a5e82663e](https://linux-hardware.org/?probe=6a5e82663e) | Jun 24, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [f4f2e68e79](https://linux-hardware.org/?probe=f4f2e68e79) | Jun 24, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [92c1597a97](https://linux-hardware.org/?probe=92c1597a97) | Jun 24, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [08e5f734f9](https://linux-hardware.org/?probe=08e5f734f9) | Jun 24, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [95d5fd3cd1](https://linux-hardware.org/?probe=95d5fd3cd1) | Jun 24, 2022 |
| ASUSTek       | X751LK                      | Notebook    | [d7f4b1678b](https://linux-hardware.org/?probe=d7f4b1678b) | Jun 24, 2022 |
| ASUSTek       | X751LK                      | Notebook    | [09dfab066c](https://linux-hardware.org/?probe=09dfab066c) | Jun 24, 2022 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | Notebook    | [0c96d2bc24](https://linux-hardware.org/?probe=0c96d2bc24) | Jun 24, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [ac634d8aa9](https://linux-hardware.org/?probe=ac634d8aa9) | Jun 23, 2022 |
| ASRock        | H510M-ITX/ac                | Desktop     | [f1e5f3d686](https://linux-hardware.org/?probe=f1e5f3d686) | Jun 23, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [906b1f465e](https://linux-hardware.org/?probe=906b1f465e) | Jun 23, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [5a66940742](https://linux-hardware.org/?probe=5a66940742) | Jun 23, 2022 |
| MSI           | B85M-E45                    | Desktop     | [f5e1312d31](https://linux-hardware.org/?probe=f5e1312d31) | Jun 22, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [43c1598008](https://linux-hardware.org/?probe=43c1598008) | Jun 22, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [212cd0ac63](https://linux-hardware.org/?probe=212cd0ac63) | Jun 22, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [f82628e802](https://linux-hardware.org/?probe=f82628e802) | Jun 21, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [402aec2b04](https://linux-hardware.org/?probe=402aec2b04) | Jun 21, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Poland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 574       | 12.8%   |
| OpenMandriva 4.2  | 316       | 7.04%   |
| Ubuntu 18.04      | 279       | 6.22%   |
| OpenMandriva 4.3  | 201       | 4.48%   |
| Ubuntu 22.04      | 137       | 3.05%   |
| Debian 11         | 114       | 2.54%   |
| Arch Rolling      | 99        | 2.21%   |
| ROSA R10          | 98        | 2.18%   |
| ROSA R9           | 70        | 1.56%   |
| ROSA R11          | 69        | 1.54%   |
| Arch              | 68        | 1.52%   |
| Linux Mint 20.1   | 66        | 1.47%   |
| Linux Mint 20.3   | 65        | 1.45%   |
| KDE neon 20.04    | 64        | 1.43%   |
| Manjaro           | 62        | 1.38%   |
| ROSA R11.1        | 60        | 1.34%   |
| Ubuntu 20.10      | 56        | 1.25%   |
| Fedora 36         | 56        | 1.25%   |
| Zorin 16          | 53        | 1.18%   |
| Linux Mint 20.2   | 51        | 1.14%   |
| Ubuntu 21.04      | 50        | 1.11%   |
| Ubuntu 19.10      | 48        | 1.07%   |
| Linux Mint 20     | 48        | 1.07%   |
| Linux Mint 19.3   | 48        | 1.07%   |
| Ubuntu 21.10      | 44        | 0.98%   |
| Fedora 35         | 43        | 0.96%   |
| ROSA R8           | 42        | 0.94%   |
| Fedora 33         | 41        | 0.91%   |
| Fedora 34         | 39        | 0.87%   |
| Xubuntu 20.04     | 38        | 0.85%   |
| Fedora 32         | 38        | 0.85%   |
| Debian 10         | 37        | 0.82%   |
| ROSA R8.1         | 36        | 0.8%    |
| Pop!_OS 20.04     | 36        | 0.8%    |
| Zorin 15          | 35        | 0.78%   |
| Linux Mint 21     | 34        | 0.76%   |
| Kubuntu 20.04     | 34        | 0.76%   |
| Ubuntu 19.04      | 33        | 0.74%   |
| OpenMandriva 4.50 | 31        | 0.69%   |
| Fedora 31         | 30        | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1204      | 28.8%   |
| OpenMandriva  | 559       | 13.37%  |
| Linux Mint    | 333       | 7.97%   |
| ROSA          | 326       | 7.8%    |
| Fedora        | 257       | 6.15%   |
| Debian        | 183       | 4.38%   |
| Manjaro       | 177       | 4.23%   |
| Arch          | 161       | 3.85%   |
| Pop!_OS       | 124       | 2.97%   |
| Zorin         | 92        | 2.2%    |
| Kubuntu       | 82        | 1.96%   |
| KDE neon      | 77        | 1.84%   |
| Xubuntu       | 68        | 1.63%   |
| Gentoo        | 39        | 0.93%   |
| Endless       | 35        | 0.84%   |
| openSUSE      | 34        | 0.81%   |
| Kali          | 34        | 0.81%   |
| Lubuntu       | 32        | 0.77%   |
| Elementary    | 28        | 0.67%   |
| ArcoLinux     | 27        | 0.65%   |
| LMDE          | 22        | 0.53%   |
| Clear Linux   | 21        | 0.5%    |
| EndeavourOS   | 20        | 0.48%   |
| Ubuntu Unity  | 17        | 0.41%   |
| BlackPanther  | 17        | 0.41%   |
| Ubuntu MATE   | 15        | 0.36%   |
| MX            | 13        | 0.31%   |
| CentOS        | 13        | 0.31%   |
| Ubuntu Budgie | 11        | 0.26%   |
| LinuxFX       | 10        | 0.24%   |
| Garuda Linux  | 10        | 0.24%   |
| SteamOS       | 9         | 0.22%   |
| Raspbian      | 8         | 0.19%   |
| Peppermint    | 7         | 0.17%   |
| Nobara        | 7         | 0.17%   |
| NixOS         | 7         | 0.17%   |
| Linux Lite    | 6         | 0.14%   |
| Xero          | 5         | 0.12%   |
| RHEL          | 5         | 0.12%   |
| EuroLinux     | 5         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 302       | 6.06%   |
| 5.16.7-desktop-1omv4003         | 190       | 3.81%   |
| 5.4.0-42-generic                | 78        | 1.57%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 54        | 1.08%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 53        | 1.06%   |
| 5.4.0-26-generic                | 40        | 0.8%    |
| 4.15.0-desktop-45.1rosa-x86_64  | 39        | 0.78%   |
| 5.4.0-52-generic                | 38        | 0.76%   |
| 5.4.0-48-generic                | 36        | 0.72%   |
| 5.15.0-56-generic               | 36        | 0.72%   |
| 5.15.0-52-generic               | 36        | 0.72%   |
| 5.15.0-43-generic               | 34        | 0.68%   |
| 5.4.0-58-generic                | 33        | 0.66%   |
| 5.4.0-29-generic                | 30        | 0.6%    |
| 5.3.0-46-generic                | 30        | 0.6%    |
| 5.4.0-54-generic                | 28        | 0.56%   |
| 5.13.0-39-generic               | 27        | 0.54%   |
| 5.11.0-37-generic               | 27        | 0.54%   |
| 5.8.0-43-generic                | 26        | 0.52%   |
| 5.4.0-40-generic                | 26        | 0.52%   |
| 5.4.0-37-generic                | 25        | 0.5%    |
| 5.15.0-48-generic               | 25        | 0.5%    |
| 4.1.34-nrj-desktop-2rosa-x86_64 | 24        | 0.48%   |
| 5.4.0-33-generic                | 23        | 0.46%   |
| 5.13.0-27-generic               | 23        | 0.46%   |
| 5.4.0-66-generic                | 22        | 0.44%   |
| 5.3.0-42-generic                | 22        | 0.44%   |
| 5.0.0-37-generic                | 22        | 0.44%   |
| 5.11.0-27-generic               | 21        | 0.42%   |
| 5.8.0-48-generic                | 20        | 0.4%    |
| 5.4.0-65-generic                | 20        | 0.4%    |
| 5.4.0-56-generic                | 20        | 0.4%    |
| 5.13.0-40-generic               | 20        | 0.4%    |
| 5.4.0-91-generic                | 19        | 0.38%   |
| 5.8.0-53-generic                | 18        | 0.36%   |
| 5.4.0-74-generic                | 18        | 0.36%   |
| 5.4.0-53-generic                | 18        | 0.36%   |
| 5.3.0-40-generic                | 18        | 0.36%   |
| 5.15.0-53-generic               | 18        | 0.36%   |
| 5.11.0-38-generic               | 18        | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 741       | 15.8%   |
| 5.10.14 | 304       | 6.48%   |
| 4.15.0  | 282       | 6.01%   |
| 5.15.0  | 261       | 5.57%   |
| 5.8.0   | 220       | 4.69%   |
| 5.11.0  | 220       | 4.69%   |
| 5.16.7  | 193       | 4.12%   |
| 5.13.0  | 190       | 4.05%   |
| 5.3.0   | 166       | 3.54%   |
| 5.10.0  | 123       | 2.62%   |
| 5.0.0   | 101       | 2.15%   |
| 4.18.0  | 89        | 1.9%    |
| 4.9.60  | 66        | 1.41%   |
| 4.9.20  | 62        | 1.32%   |
| 4.19.0  | 51        | 1.09%   |
| 5.19.0  | 33        | 0.7%    |
| 4.1.34  | 32        | 0.68%   |
| 4.1.38  | 28        | 0.6%    |
| 5.14.0  | 26        | 0.55%   |
| 5.17.5  | 20        | 0.43%   |
| 5.9.0   | 18        | 0.38%   |
| 5.11.12 | 18        | 0.38%   |
| 5.4.32  | 17        | 0.36%   |
| 4.9.76  | 16        | 0.34%   |
| 4.9.124 | 16        | 0.34%   |
| 5.17.0  | 15        | 0.32%   |
| 6.0.8   | 14        | 0.3%    |
| 4.9.155 | 14        | 0.3%    |
| 5.6.0   | 13        | 0.28%   |
| 5.4.83  | 13        | 0.28%   |
| 5.15.12 | 13        | 0.28%   |
| 5.16.13 | 12        | 0.26%   |
| 5.12.4  | 12        | 0.26%   |
| 6.0.0   | 11        | 0.23%   |
| 5.9.16  | 11        | 0.23%   |
| 5.15.32 | 11        | 0.23%   |
| 4.18.16 | 11        | 0.23%   |
| 6.0.7   | 10        | 0.21%   |
| 5.9.1   | 10        | 0.21%   |
| 5.19.5  | 10        | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 840       | 18.43%  |
| 5.10    | 537       | 11.78%  |
| 5.15    | 388       | 8.51%   |
| 5.11    | 285       | 6.25%   |
| 4.15    | 282       | 6.19%   |
| 5.8     | 278       | 6.1%    |
| 5.16    | 276       | 6.06%   |
| 5.13    | 220       | 4.83%   |
| 5.3     | 185       | 4.06%   |
| 4.9     | 181       | 3.97%   |
| 5.0     | 111       | 2.44%   |
| 4.18    | 101       | 2.22%   |
| 6.0     | 89        | 1.95%   |
| 5.19    | 89        | 1.95%   |
| 5.14    | 80        | 1.76%   |
| 5.17    | 79        | 1.73%   |
| 5.9     | 74        | 1.62%   |
| 5.6     | 69        | 1.51%   |
| 5.18    | 68        | 1.49%   |
| 4.19    | 64        | 1.4%    |
| 4.1     | 63        | 1.38%   |
| 5.12    | 60        | 1.32%   |
| 5.5     | 39        | 0.86%   |
| 5.7     | 35        | 0.77%   |
| 4.4     | 17        | 0.37%   |
| 5.1     | 8         | 0.18%   |
| 3.10    | 7         | 0.15%   |
| 5.2     | 4         | 0.09%   |
| 4.20    | 4         | 0.09%   |
| 4.16    | 3         | 0.07%   |
| 4.13    | 3         | 0.07%   |
| 4.8     | 2         | 0.04%   |
| 4.7     | 2         | 0.04%   |
| 4.14    | 2         | 0.04%   |
| 4.12    | 2         | 0.04%   |
| 4.10    | 2         | 0.04%   |
| 3.18    | 2         | 0.04%   |
| 6.1     | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |
| 4.11    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3845      | 95.31%  |
| i686    | 143       | 3.54%   |
| aarch64 | 24        | 0.59%   |
| armv7l  | 15        | 0.37%   |
| armv8l  | 3         | 0.07%   |
| armv6l  | 2         | 0.05%   |
| ppc64   | 1         | 0.02%   |
| ppc     | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1513      | 35.63%  |
| KDE5            | 1049      | 24.71%  |
| Unknown         | 466       | 10.98%  |
| XFCE            | 294       | 6.92%   |
| X-Cinnamon      | 223       | 5.25%   |
| KDE4            | 175       | 4.12%   |
| KDE             | 124       | 2.92%   |
| MATE            | 92        | 2.17%   |
| Cinnamon        | 63        | 1.48%   |
| LXQt            | 51        | 1.2%    |
| LXDE            | 42        | 0.99%   |
| i3              | 30        | 0.71%   |
| Pantheon        | 26        | 0.61%   |
| Unity           | 20        | 0.47%   |
| Budgie          | 19        | 0.45%   |
| Deepin          | 16        | 0.38%   |
| GNOME Flashback | 9         | 0.21%   |
| GNOME Classic   | 6         | 0.14%   |
| awesome         | 5         | 0.12%   |
| qtile           | 4         | 0.09%   |
| sway            | 3         | 0.07%   |
| Openbox         | 3         | 0.07%   |
| fluxbox         | 3         | 0.07%   |
| DWM             | 3         | 0.07%   |
| trinity         | 2         | 0.05%   |
| stumpwm         | 1         | 0.02%   |
| qt5ct           | 1         | 0.02%   |
| jwm             | 1         | 0.02%   |
| ICEWM           | 1         | 0.02%   |
| GNUstep         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3371      | 81.19%  |
| Wayland | 474       | 11.42%  |
| Unknown | 226       | 5.44%   |
| Tty     | 81        | 1.95%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1827      | 43.28%  |
| SDDM    | 1003      | 23.76%  |
| GDM     | 460       | 10.9%   |
| LightDM | 303       | 7.18%   |
| GDM3    | 271       | 6.42%   |
| KDM     | 185       | 4.38%   |
| TDM     | 152       | 3.6%    |
| XDM     | 10        | 0.24%   |
| Ly      | 3         | 0.07%   |
| SLiM    | 2         | 0.05%   |
| MDM     | 2         | 0.05%   |
| LXDM    | 2         | 0.05%   |
| SLIMSKI | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| pl_PL      | 2246      | 53.68%  |
| en_US      | 1014      | 24.24%  |
| Unknown    | 643       | 15.37%  |
| en_GB      | 121       | 2.89%   |
| C          | 71        | 1.7%    |
| ru_RU      | 20        | 0.48%   |
| szl_PL     | 12        | 0.29%   |
| en_CA      | 8         | 0.19%   |
| de_DE      | 6         | 0.14%   |
| uk_UA      | 5         | 0.12%   |
| fr_FR      | 5         | 0.12%   |
| en_IE      | 5         | 0.12%   |
| ru_UA      | 4         | 0.1%    |
| en_DK      | 3         | 0.07%   |
| en_AG      | 3         | 0.07%   |
| C.UTF8     | 3         | 0.07%   |
| nl_NL      | 2         | 0.05%   |
| it_IT      | 2         | 0.05%   |
| en_IN      | 2         | 0.05%   |
| sv_SE      | 1         | 0.02%   |
| sk_SK      | 1         | 0.02%   |
| hu_HU      | 1         | 0.02%   |
| es_ES      | 1         | 0.02%   |
| en_US.UTF8 | 1         | 0.02%   |
| en_AU      | 1         | 0.02%   |
| el_GR      | 1         | 0.02%   |
| af_ZA      | 1         | 0.02%   |
| aa_DJ      | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2321      | 56.29%  |
| EFI  | 1802      | 43.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 2864      | 68.75%  |
| Overlay  | 561       | 13.47%  |
| Btrfs    | 319       | 7.66%   |
| Unknown  | 297       | 7.13%   |
| Xfs      | 57        | 1.37%   |
| Zfs      | 26        | 0.62%   |
| F2fs     | 18        | 0.43%   |
| Ext2     | 7         | 0.17%   |
| Tmpfs    | 6         | 0.14%   |
| Ext3     | 5         | 0.12%   |
| XXXXX    | 1         | 0.02%   |
| SquXshfs | 1         | 0.02%   |
| Rootfs   | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |
| Bcachefs | 1         | 0.02%   |
| Aufs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2058      | 49.54%  |
| GPT     | 1356      | 32.64%  |
| MBR     | 740       | 17.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3373      | 81.73%  |
| Yes       | 754       | 18.27%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2678      | 65.16%  |
| Yes       | 1432      | 34.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 705       | 17.52%  |
| Dell                    | 649       | 16.12%  |
| ASUSTek Computer        | 625       | 15.53%  |
| Hewlett-Packard         | 480       | 11.93%  |
| Gigabyte Technology     | 371       | 9.22%   |
| MSI                     | 310       | 7.7%    |
| Acer                    | 169       | 4.2%    |
| ASRock                  | 140       | 3.48%   |
| Samsung Electronics     | 68        | 1.69%   |
| Toshiba                 | 67        | 1.66%   |
| Fujitsu                 | 44        | 1.09%   |
| Sony                    | 32        | 0.8%    |
| Fujitsu Siemens         | 31        | 0.77%   |
| Apple                   | 29        | 0.72%   |
| HUAWEI                  | 27        | 0.67%   |
| Intel                   | 25        | 0.62%   |
| Raspberry Pi Foundation | 22        | 0.55%   |
| Unknown                 | 16        | 0.4%    |
| Packard Bell            | 12        | 0.3%    |
| Medion                  | 12        | 0.3%    |
| Notebook                | 11        | 0.27%   |
| Google                  | 11        | 0.27%   |
| Foxconn                 | 11        | 0.27%   |
| Valve                   | 9         | 0.22%   |
| eMachines               | 9         | 0.22%   |
| AMI                     | 7         | 0.17%   |
| Timi                    | 6         | 0.15%   |
| Kiano                   | 6         | 0.15%   |
| Inventec                | 5         | 0.12%   |
| mPTech                  | 4         | 0.1%    |
| Kruger&Matz             | 4         | 0.1%    |
| Gateway                 | 4         | 0.1%    |
| ECS                     | 4         | 0.1%    |
| ZOTAC                   | 3         | 0.07%   |
| Supermicro              | 3         | 0.07%   |
| sunxi                   | 3         | 0.07%   |
| Nvidia                  | 3         | 0.07%   |
| Huanan                  | 3         | 0.07%   |
| Hardkernel              | 3         | 0.07%   |
| Clevo                   | 3         | 0.07%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 37        | 0.92%   |
| Dell Inspiron 3451                  | 31        | 0.77%   |
| ASUS All Series                     | 26        | 0.65%   |
| ASUS SABERTOOTH Z77                 | 18        | 0.45%   |
| MSI MS-7B86                         | 16        | 0.4%    |
| MSI MS-7817                         | 16        | 0.4%    |
| Gigabyte B450M DS3H                 | 16        | 0.4%    |
| Dell Latitude E6400                 | 15        | 0.37%   |
| Dell Latitude E6540                 | 14        | 0.35%   |
| Dell OptiPlex 780                   | 13        | 0.32%   |
| Lenovo G50-30 80G0                  | 12        | 0.3%    |
| MSI MS-7C02                         | 11        | 0.27%   |
| Dell Latitude E6430                 | 11        | 0.27%   |
| Dell Latitude 5480                  | 11        | 0.27%   |
| HP Pavilion dv7                     | 10        | 0.25%   |
| Dell Latitude 5490                  | 10        | 0.25%   |
| Valve Jupiter                       | 9         | 0.22%   |
| Gigabyte B450 AORUS ELITE           | 9         | 0.22%   |
| Dell Latitude E6420                 | 9         | 0.22%   |
| Dell Latitude D630                  | 9         | 0.22%   |
| ASUS X555LJ                         | 9         | 0.22%   |
| MSI MS-7B79                         | 8         | 0.2%    |
| MSI MS-7A38                         | 8         | 0.2%    |
| MSI MS-7721                         | 8         | 0.2%    |
| Lenovo G580 20150                   | 8         | 0.2%    |
| Gigabyte B85M-D3H                   | 8         | 0.2%    |
| Dell OptiPlex 755                   | 8         | 0.2%    |
| Dell OptiPlex 7010                  | 8         | 0.2%    |
| Dell Latitude E7440                 | 8         | 0.2%    |
| ASUS TUF Gaming X570-PLUS           | 8         | 0.2%    |
| MSI MS-7C37                         | 7         | 0.17%   |
| Lenovo Legion Y540-15IRH 81SX       | 7         | 0.17%   |
| Lenovo Legion Y530-15ICH 81FV       | 7         | 0.17%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 7         | 0.17%   |
| HP EliteBook 6930p                  | 7         | 0.17%   |
| HP 15                               | 7         | 0.17%   |
| Dell Latitude E6330                 | 7         | 0.17%   |
| ASUS PRIME X470-PRO                 | 7         | 0.17%   |
| ASUS PRIME B450M-A                  | 7         | 0.17%   |
| Toshiba Satellite A300              | 6         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 292       | 7.25%   |
| Dell Latitude           | 266       | 6.61%   |
| Dell Inspiron           | 143       | 3.55%   |
| Lenovo IdeaPad          | 127       | 3.16%   |
| Acer Aspire             | 100       | 2.48%   |
| Dell OptiPlex           | 86        | 2.14%   |
| HP Pavilion             | 82        | 2.04%   |
| HP EliteBook            | 81        | 2.01%   |
| HP ProBook              | 57        | 1.42%   |
| HP Compaq               | 55        | 1.37%   |
| Toshiba Satellite       | 54        | 1.34%   |
| Dell Precision          | 53        | 1.32%   |
| ASUS PRIME              | 52        | 1.29%   |
| ASUS TUF                | 46        | 1.14%   |
| Lenovo Legion           | 40        | 0.99%   |
| Lenovo ThinkCentre      | 39        | 0.97%   |
| ASUS ROG                | 38        | 0.94%   |
| Unknown                 | 37        | 0.92%   |
| Dell Vostro             | 35        | 0.87%   |
| ASUS VivoBook           | 32        | 0.8%    |
| HP Laptop               | 30        | 0.75%   |
| Dell XPS                | 26        | 0.65%   |
| ASUS All                | 26        | 0.65%   |
| Gigabyte B450M          | 23        | 0.57%   |
| RPi Raspberry           | 22        | 0.55%   |
| ASUS SABERTOOTH         | 20        | 0.5%    |
| HP 250                  | 18        | 0.45%   |
| Fujitsu LIFEBOOK        | 17        | 0.42%   |
| ASUS ASUS               | 17        | 0.42%   |
| MSI MS-7B86             | 16        | 0.4%    |
| MSI MS-7817             | 16        | 0.4%    |
| Lenovo Yoga             | 16        | 0.4%    |
| HP EliteDesk            | 16        | 0.4%    |
| Fujitsu ESPRIMO         | 15        | 0.37%   |
| Gigabyte X570           | 14        | 0.35%   |
| Acer Extensa            | 14        | 0.35%   |
| HP ZBook                | 13        | 0.32%   |
| Gigabyte B450           | 13        | 0.32%   |
| Fujitsu Siemens ESPRIMO | 13        | 0.32%   |
| Packard Bell EasyNote   | 12        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 350       | 8.7%    |
| 2018    | 344       | 8.55%   |
| 2013    | 340       | 8.45%   |
| 2019    | 328       | 8.15%   |
| 2011    | 306       | 7.6%    |
| 2020    | 292       | 7.25%   |
| 2014    | 265       | 6.58%   |
| 2017    | 238       | 5.91%   |
| 2008    | 237       | 5.89%   |
| 2015    | 225       | 5.59%   |
| 2010    | 218       | 5.42%   |
| 2009    | 186       | 4.62%   |
| 2007    | 182       | 4.52%   |
| 2021    | 175       | 4.35%   |
| 2016    | 173       | 4.3%    |
| 2006    | 71        | 1.76%   |
| 2022    | 44        | 1.09%   |
| Unknown | 35        | 0.87%   |
| 2005    | 9         | 0.22%   |
| 2004    | 6         | 0.15%   |
| 2001    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2366      | 58.78%  |
| Desktop        | 1503      | 37.34%  |
| Convertible    | 43        | 1.07%   |
| System on chip | 37        | 0.92%   |
| Mini pc        | 26        | 0.65%   |
| Server         | 19        | 0.47%   |
| All in one     | 15        | 0.37%   |
| Tablet         | 11        | 0.27%   |
| Phone          | 5         | 0.12%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3821      | 94.46%  |
| Enabled  | 224       | 5.54%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4011      | 99.65%  |
| Yes  | 14        | 0.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 904       | 22.05%  |
| 4.01-8.0        | 824       | 20.1%   |
| 8.01-16.0       | 756       | 18.44%  |
| 16.01-24.0      | 726       | 17.71%  |
| 32.01-64.0      | 410       | 10%     |
| 1.01-2.0        | 180       | 4.39%   |
| 2.01-3.0        | 112       | 2.73%   |
| 64.01-256.0     | 82        | 2%      |
| 24.01-32.0      | 65        | 1.59%   |
| 0.51-1.0        | 36        | 0.88%   |
| 0.01-0.5        | 4         | 0.1%    |
| More than 256.0 | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1733      | 38.05%  |
| 2.01-3.0    | 935       | 20.53%  |
| 4.01-8.0    | 577       | 12.67%  |
| 3.01-4.0    | 516       | 11.33%  |
| 0.51-1.0    | 450       | 9.88%   |
| 8.01-16.0   | 193       | 4.24%   |
| 0.01-0.5    | 91        | 2%      |
| 16.01-24.0  | 38        | 0.83%   |
| 24.01-32.0  | 12        | 0.26%   |
| 32.01-64.0  | 4         | 0.09%   |
| Unknown     | 4         | 0.09%   |
| 64.01-256.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2462      | 59%     |
| 2       | 1042      | 24.97%  |
| 3       | 345       | 8.27%   |
| 4       | 143       | 3.43%   |
| 0       | 67        | 1.61%   |
| 5       | 60        | 1.44%   |
| 6       | 26        | 0.62%   |
| 7       | 13        | 0.31%   |
| 8       | 7         | 0.17%   |
| 9       | 3         | 0.07%   |
| 11      | 2         | 0.05%   |
| 10      | 2         | 0.05%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2264      | 55.49%  |
| Yes       | 1816      | 44.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3656      | 90.61%  |
| No        | 379       | 9.39%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3018      | 74.33%  |
| No        | 1042      | 25.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2242      | 54.78%  |
| No        | 1851      | 45.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Poland  | 4025      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Warsaw                 | 902       | 20.65%  |
| Krakow                 | 328       | 7.51%   |
| Wroclaw                | 256       | 5.86%   |
| Poznan                 | 213       | 4.88%   |
| Lodz                   | 136       | 3.11%   |
| Gdansk                 | 134       | 3.07%   |
| Katowice               | 110       | 2.52%   |
| Lublin                 | 56        | 1.28%   |
| Gdynia                 | 51        | 1.17%   |
| Szczecin               | 47        | 1.08%   |
| Bialystok              | 37        | 0.85%   |
| Częstochowa           | 35        | 0.8%    |
| Rzeszów               | 33        | 0.76%   |
| Gliwice                | 33        | 0.76%   |
| Torun                  | 31        | 0.71%   |
| Ruda Śląska          | 31        | 0.71%   |
| Bytom                  | 28        | 0.64%   |
| Bydgoszcz              | 28        | 0.64%   |
| Płock                 | 23        | 0.53%   |
| Sosnowiec              | 21        | 0.48%   |
| Bielsko-Biala          | 21        | 0.48%   |
| Strzyzow               | 20        | 0.46%   |
| Olsztyn                | 20        | 0.46%   |
| Kielce                 | 20        | 0.46%   |
| Elblag                 | 20        | 0.46%   |
| Chorzów               | 19        | 0.43%   |
| Zabrze                 | 17        | 0.39%   |
| Tarnów                | 17        | 0.39%   |
| Rybnik                 | 17        | 0.39%   |
| Siemianowice Śląskie | 16        | 0.37%   |
| Radom                  | 16        | 0.37%   |
| Opole                  | 16        | 0.37%   |
| Tychy                  | 14        | 0.32%   |
| Cieszyn                | 13        | 0.3%    |
| Blizniew               | 13        | 0.3%    |
| Słupsk                | 12        | 0.27%   |
| Debica                 | 12        | 0.27%   |
| Zielona Góra          | 11        | 0.25%   |
| Pabianice              | 11        | 0.25%   |
| Legnica                | 11        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 873       | 1336   | 14.72%  |
| WDC                       | 841       | 1275   | 14.18%  |
| Samsung Electronics       | 814       | 1239   | 13.73%  |
| GOODRAM                   | 385       | 558    | 6.49%   |
| Toshiba                   | 376       | 556    | 6.34%   |
| Kingston                  | 227       | 315    | 3.83%   |
| Crucial                   | 226       | 370    | 3.81%   |
| A-DATA Technology         | 219       | 306    | 3.69%   |
| Unknown                   | 211       | 302    | 3.56%   |
| Hitachi                   | 204       | 283    | 3.44%   |
| SanDisk                   | 202       | 280    | 3.41%   |
| Intel                     | 154       | 202    | 2.6%    |
| SK hynix                  | 124       | 160    | 2.09%   |
| HGST                      | 96        | 124    | 1.62%   |
| Micron Technology         | 78        | 100    | 1.32%   |
| Patriot                   | 71        | 93     | 1.2%    |
| SPCC                      | 65        | 93     | 1.1%    |
| Plextor                   | 57        | 73     | 0.96%   |
| PNY                       | 42        | 46     | 0.71%   |
| XPG                       | 39        | 55     | 0.66%   |
| KIOXIA                    | 37        | 42     | 0.62%   |
| Phison                    | 35        | 49     | 0.59%   |
| Fujitsu                   | 32        | 36     | 0.54%   |
| Apacer                    | 31        | 48     | 0.52%   |
| OCZ                       | 26        | 28     | 0.44%   |
| Corsair                   | 25        | 33     | 0.42%   |
| China                     | 23        | 27     | 0.39%   |
| LITEON                    | 21        | 30     | 0.35%   |
| Maxtor                    | 20        | 20     | 0.34%   |
| Transcend                 | 17        | 18     | 0.29%   |
| Lite-On                   | 17        | 20     | 0.29%   |
| Silicon Motion            | 16        | 19     | 0.27%   |
| Realtek Semiconductor     | 16        | 26     | 0.27%   |
| KIOXIA-EXCERIA            | 16        | 21     | 0.27%   |
| ASMT                      | 16        | 17     | 0.27%   |
| Phison Electronics        | 15        | 23     | 0.25%   |
| LITEONIT                  | 15        | 16     | 0.25%   |
| JMicron Technology        | 15        | 16     | 0.25%   |
| Apple                     | 13        | 17     | 0.22%   |
| Micron/Crucial Technology | 12        | 12     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB        | 58        | 0.89%   |
| Seagate ST1000LM035-1RK172 1TB         | 54        | 0.83%   |
| Toshiba HDWD110 1TB                    | 49        | 0.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 49        | 0.75%   |
| Samsung SSD 850 EVO 250GB              | 49        | 0.75%   |
| Crucial CT500MX500SSD1 500GB           | 49        | 0.75%   |
| GOODRAM SSD 120GB                      | 45        | 0.69%   |
| Crucial CT1000MX500SSD1 1TB            | 40        | 0.62%   |
| Seagate ST500DM002-1BD142 500GB        | 38        | 0.59%   |
| GOODRAM SSDPR-CX400-256-G2 256GB       | 34        | 0.52%   |
| Samsung SSD 860 EVO 500GB              | 33        | 0.51%   |
| GOODRAM SSDPR-CX400-512 512GB          | 33        | 0.51%   |
| GOODRAM SSD 240GB                      | 33        | 0.51%   |
| Unknown MMC Card  32GB                 | 32        | 0.49%   |
| Samsung SSD 860 EVO 250GB              | 32        | 0.49%   |
| Samsung NVMe SSD Drive 500GB           | 32        | 0.49%   |
| Kingston SV300S37A120G 120GB SSD       | 30        | 0.46%   |
| Seagate ST9500325AS 500GB              | 28        | 0.43%   |
| Samsung NVMe SSD Drive 512GB           | 28        | 0.43%   |
| Kingston SA400S37240G 240GB SSD        | 28        | 0.43%   |
| Unknown MMC Card  64GB                 | 27        | 0.42%   |
| Toshiba MQ01ABD100 1TB                 | 27        | 0.42%   |
| Seagate ST3500418AS 500GB              | 27        | 0.42%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 27        | 0.42%   |
| A-DATA SU800 256GB SSD                 | 27        | 0.42%   |
| Seagate ST1000DM010-2EP102 1TB         | 26        | 0.4%    |
| Seagate ST1000DM003-1ER162 1TB         | 26        | 0.4%    |
| Intel NVMe SSD Drive 512GB             | 26        | 0.4%    |
| Patriot Burst 120GB SSD                | 25        | 0.39%   |
| Samsung HD502HJ 500GB                  | 24        | 0.37%   |
| GOODRAM SSDPR-CX400-512-G2 512GB       | 24        | 0.37%   |
| Crucial CT240BX500SSD1 240GB           | 24        | 0.37%   |
| HGST HTS721010A9E630 1TB               | 23        | 0.35%   |
| Seagate Expansion 4TB                  | 22        | 0.34%   |
| SanDisk SDSSDA240G 240GB               | 22        | 0.34%   |
| GOODRAM SSDPR-CX400-256 256GB          | 22        | 0.34%   |
| Toshiba DT01ACA100 1TB                 | 21        | 0.32%   |
| Kingston SA400S37480G 480GB SSD        | 21        | 0.32%   |
| GOODRAM SSDPR-CL100-120-G2 120GB       | 21        | 0.32%   |
| Toshiba MQ01ABF050 500GB               | 20        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 870       | 1331   | 36.01%  |
| WDC                 | 703       | 1080   | 29.1%   |
| Toshiba             | 294       | 455    | 12.17%  |
| Hitachi             | 204       | 283    | 8.44%   |
| Samsung Electronics | 157       | 223    | 6.5%    |
| HGST                | 96        | 124    | 3.97%   |
| Fujitsu             | 32        | 36     | 1.32%   |
| Maxtor              | 18        | 18     | 0.75%   |
| Unknown             | 7         | 7      | 0.29%   |
| ASMT                | 7         | 8      | 0.29%   |
| ASMedia             | 5         | 6      | 0.21%   |
| Apple               | 5         | 5      | 0.21%   |
| USB3.0              | 3         | 3      | 0.12%   |
| PHD 3.0             | 2         | 2      | 0.08%   |
| IBM/Hitachi         | 2         | 2      | 0.08%   |
| WD MediaMax         | 1         | 2      | 0.04%   |
| Synology            | 1         | 1      | 0.04%   |
| StoreJet            | 1         | 1      | 0.04%   |
| SAGE                | 1         | 1      | 0.04%   |
| MARVELL             | 1         | 1      | 0.04%   |
| LaCie               | 1         | 2      | 0.04%   |
| HPE                 | 1         | 1      | 0.04%   |
| Hewlett-Packard     | 1         | 1      | 0.04%   |
| ExcelStor           | 1         | 1      | 0.04%   |
| ASMT109x            | 1         | 1      | 0.04%   |
| Unknown             | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| GOODRAM             | 378       | 545    | 17.52%  |
| Samsung Electronics | 369       | 514    | 17.1%   |
| Crucial             | 218       | 360    | 10.1%   |
| A-DATA Technology   | 178       | 246    | 8.25%   |
| Kingston            | 166       | 227    | 7.69%   |
| SanDisk             | 144       | 205    | 6.67%   |
| WDC                 | 75        | 87     | 3.48%   |
| Patriot             | 62        | 84     | 2.87%   |
| SPCC                | 59        | 85     | 2.73%   |
| Intel               | 50        | 60     | 2.32%   |
| Plextor             | 48        | 64     | 2.22%   |
| Micron Technology   | 45        | 59     | 2.09%   |
| Toshiba             | 40        | 43     | 1.85%   |
| SK hynix            | 34        | 42     | 1.58%   |
| PNY                 | 30        | 34     | 1.39%   |
| Apacer              | 29        | 46     | 1.34%   |
| OCZ                 | 26        | 28     | 1.2%    |
| China               | 22        | 26     | 1.02%   |
| LITEON              | 21        | 30     | 0.97%   |
| Transcend           | 16        | 17     | 0.74%   |
| LITEONIT            | 15        | 16     | 0.7%    |
| KIOXIA-EXCERIA      | 13        | 17     | 0.6%    |
| JMicron Technology  | 10        | 10     | 0.46%   |
| Corsair             | 10        | 11     | 0.46%   |
| ASMT                | 9         | 9      | 0.42%   |
| Apple               | 7         | 7      | 0.32%   |
| KingSpec            | 6         | 6      | 0.28%   |
| Intenso             | 5         | 10     | 0.23%   |
| Team                | 4         | 4      | 0.19%   |
| BIWIN               | 4         | 4      | 0.19%   |
| Argon               | 4         | 6      | 0.19%   |
| Gigabyte Technology | 3         | 4      | 0.14%   |
| 2-Power             | 3         | 3      | 0.14%   |
| WDC WDS2            | 2         | 2      | 0.09%   |
| Union Memory        | 2         | 3      | 0.09%   |
| Ramaxel Technology  | 2         | 2      | 0.09%   |
| Phison              | 2         | 2      | 0.09%   |
| Maxtor              | 2         | 2      | 0.09%   |
| Lexar               | 2         | 2      | 0.09%   |
| HS-SSD-E100         | 2         | 2      | 0.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2047      | 3596   | 38.83%  |
| SSD     | 1895      | 2968   | 35.94%  |
| NVMe    | 1077      | 1614   | 20.43%  |
| MMC     | 189       | 268    | 3.58%   |
| Unknown | 64        | 95     | 1.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3179      | 6416   | 68.75%  |
| NVMe | 1076      | 1612   | 23.27%  |
| MMC  | 189       | 268    | 4.09%   |
| SAS  | 180       | 245    | 3.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2622      | 4302   | 65.75%  |
| 0.51-1.0   | 1006      | 1601   | 25.23%  |
| 1.01-2.0   | 185       | 309    | 4.64%   |
| 3.01-4.0   | 81        | 139    | 2.03%   |
| 2.01-3.0   | 55        | 127    | 1.38%   |
| 4.01-10.0  | 33        | 70     | 0.83%   |
| 10.01-20.0 | 6         | 16     | 0.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1227      | 28.21%  |
| 251-500        | 827       | 19.02%  |
| 1-20           | 518       | 11.91%  |
| 501-1000       | 485       | 11.15%  |
| 51-100         | 373       | 8.58%   |
| 1001-2000      | 284       | 6.53%   |
| 21-50          | 222       | 5.1%    |
| Unknown        | 184       | 4.23%   |
| More than 3000 | 134       | 3.08%   |
| 2001-3000      | 95        | 2.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1874      | 41.89%  |
| 21-50          | 664       | 14.84%  |
| 101-250        | 533       | 11.91%  |
| 51-100         | 493       | 11.02%  |
| 251-500        | 282       | 6.3%    |
| 501-1000       | 227       | 5.07%   |
| Unknown        | 184       | 4.11%   |
| 1001-2000      | 128       | 2.86%   |
| More than 3000 | 45        | 1.01%   |
| 2001-3000      | 44        | 0.98%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB            | 12        | 15     | 2.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 9         | 10     | 1.56%   |
| Seagate ST500LT012-9WS142 500GB      | 8         | 27     | 1.38%   |
| Seagate ST3500418AS 500GB            | 8         | 11     | 1.38%   |
| Seagate ST500DM002-1BD142 500GB      | 7         | 7      | 1.21%   |
| HGST HTS545050A7E680 500GB           | 6         | 6      | 1.04%   |
| Seagate ST500LT012-1DG142 500GB      | 5         | 7      | 0.87%   |
| Seagate ST1000DM003-9YN162 1TB       | 5         | 5      | 0.87%   |
| Kingston SV300S37A120G 120GB SSD     | 5         | 5      | 0.87%   |
| GOODRAM SSD 120GB                    | 5         | 5      | 0.87%   |
| ASMT 2135 120GB SSD                  | 5         | 5      | 0.87%   |
| WDC WD5000BEVT-22ZAT0 500GB          | 4         | 4      | 0.69%   |
| WDC WD10JPVX-22JC3T0 1TB             | 4         | 4      | 0.69%   |
| Toshiba MQ01ABD100 1TB               | 4         | 5      | 0.69%   |
| Seagate ST9500420AS 500GB            | 4         | 4      | 0.69%   |
| Seagate ST92505610AS 250GB           | 4         | 4      | 0.69%   |
| Seagate ST3320613AS 320GB            | 4         | 4      | 0.69%   |
| Hitachi HTS541612J9SA00 120GB        | 4         | 5      | 0.69%   |
| WDC WD3200BPVT-80ZEST0 320GB         | 3         | 3      | 0.52%   |
| Toshiba MK3265GSX 320GB              | 3         | 3      | 0.52%   |
| Toshiba MK1637GSX 160GB              | 3         | 3      | 0.52%   |
| Toshiba MK1246GSX 120GB              | 3         | 3      | 0.52%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 3         | 3      | 0.52%   |
| Seagate ST9320325AS 320GB            | 3         | 3      | 0.52%   |
| Seagate ST9250827AS 250GB            | 3         | 3      | 0.52%   |
| Seagate ST9250410AS 250GB            | 3         | 3      | 0.52%   |
| Seagate ST9250315AS 250GB            | 3         | 3      | 0.52%   |
| Seagate ST9160821AS 160GB            | 3         | 4      | 0.52%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 3      | 0.52%   |
| Seagate ST3500312CS 500GB            | 3         | 3      | 0.52%   |
| Seagate ST3250410AS 250GB            | 3         | 3      | 0.52%   |
| Seagate ST31500341AS 1TB             | 3         | 4      | 0.52%   |
| Seagate ST1000LM014-1EJ164 1TB       | 3         | 4      | 0.52%   |
| Seagate ST1000DX001-1CM162 1TB       | 3         | 6      | 0.52%   |
| Samsung Electronics HD502HJ 500GB    | 3         | 3      | 0.52%   |
| Hitachi HTS542516K9SA00 160GB        | 3         | 5      | 0.52%   |
| HGST HTS545050A7E380 500GB           | 3         | 3      | 0.52%   |
| WDC WD5002ABYS-01B1B0 500GB          | 2         | 14     | 0.35%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 2         | 2      | 0.35%   |
| WDC WD5000AVDS-63U7B1 500GB          | 2         | 2      | 0.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 169       | 231    | 30.45%  |
| WDC                   | 106       | 156    | 19.1%   |
| Hitachi               | 45        | 56     | 8.11%   |
| Toshiba               | 44        | 55     | 7.93%   |
| Samsung Electronics   | 44        | 50     | 7.93%   |
| A-DATA Technology     | 24        | 27     | 4.32%   |
| HGST                  | 16        | 17     | 2.88%   |
| SanDisk               | 14        | 17     | 2.52%   |
| Kingston              | 11        | 11     | 1.98%   |
| SK hynix              | 8         | 8      | 1.44%   |
| Intel                 | 7         | 7      | 1.26%   |
| GOODRAM               | 7         | 7      | 1.26%   |
| Fujitsu               | 7         | 9      | 1.26%   |
| ASMT                  | 6         | 7      | 1.08%   |
| LITEON                | 5         | 5      | 0.9%    |
| Crucial               | 5         | 6      | 0.9%    |
| Micron Technology     | 4         | 4      | 0.72%   |
| LITEONIT              | 4         | 4      | 0.72%   |
| SPCC                  | 3         | 3      | 0.54%   |
| Maxtor                | 3         | 3      | 0.54%   |
| Hewlett-Packard       | 3         | 3      | 0.54%   |
| ASMedia               | 3         | 3      | 0.54%   |
| Apacer                | 3         | 6      | 0.54%   |
| OCZ                   | 2         | 2      | 0.36%   |
| XPG                   | 1         | 1      | 0.18%   |
| WDC WDS2              | 1         | 1      | 0.18%   |
| WD MediaMax           | 1         | 2      | 0.18%   |
| SSSTC                 | 1         | 1      | 0.18%   |
| Realtek Semiconductor | 1         | 1      | 0.18%   |
| Plextor               | 1         | 1      | 0.18%   |
| Platinet              | 1         | 1      | 0.18%   |
| Patriot               | 1         | 3      | 0.18%   |
| Lexar                 | 1         | 1      | 0.18%   |
| Lenovo                | 1         | 1      | 0.18%   |
| Corsair               | 1         | 2      | 0.18%   |
| Unknown               | 1         | 1      | 0.18%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 169       | 231    | 39.76%  |
| WDC                 | 104       | 153    | 24.47%  |
| Hitachi             | 45        | 56     | 10.59%  |
| Toshiba             | 41        | 52     | 9.65%   |
| Samsung Electronics | 33        | 38     | 7.76%   |
| HGST                | 16        | 17     | 3.76%   |
| Fujitsu             | 7         | 9      | 1.65%   |
| Maxtor              | 3         | 3      | 0.71%   |
| ASMedia             | 3         | 3      | 0.71%   |
| WD MediaMax         | 1         | 2      | 0.24%   |
| Hewlett-Packard     | 1         | 1      | 0.24%   |
| ASMT                | 1         | 2      | 0.24%   |
| Unknown             | 1         | 1      | 0.24%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 398       | 568    | 75.67%  |
| SSD  | 109       | 124    | 20.72%  |
| NVMe | 19        | 21     | 3.61%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD800BEVS-75RST0 80GB         | 1         | 1      | 9.09%   |
| WDC WD3200BEVT-22ZCT0 320GB       | 1         | 1      | 9.09%   |
| WDC WD3200BEKT-75PVMT1 320GB      | 1         | 1      | 9.09%   |
| WDC WD2500BEVS-22UST0 250GB       | 1         | 1      | 9.09%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1         | 1      | 9.09%   |
| Toshiba MK3265GSXN 320GB          | 1         | 1      | 9.09%   |
| Toshiba DT01ACA100 1TB            | 1         | 2      | 9.09%   |
| Seagate ST500DM002-1BC142 500GB   | 1         | 1      | 9.09%   |
| Seagate ST320LT020-9YG142 320GB   | 1         | 1      | 9.09%   |
| Samsung Electronics HD250HJ 250GB | 1         | 1      | 9.09%   |
| OCZ-AGIL ITY3 120GB SSD           | 1         | 1      | 9.09%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 45.45%  |
| Toshiba             | 2         | 3      | 18.18%  |
| Seagate             | 2         | 2      | 18.18%  |
| Samsung Electronics | 1         | 1      | 9.09%   |
| OCZ-AGIL            | 1         | 1      | 9.09%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2111      | 4384   | 48%     |
| Works    | 1764      | 3432   | 40.11%  |
| Malfunc  | 512       | 713    | 11.64%  |
| Failed   | 11        | 12     | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2824      | 56.1%   |
| AMD                              | 742       | 14.74%  |
| Samsung Electronics              | 353       | 7.01%   |
| SanDisk                          | 132       | 2.62%   |
| Phison Electronics               | 91        | 1.81%   |
| JMicron Technology               | 90        | 1.79%   |
| SK hynix                         | 87        | 1.73%   |
| Nvidia                           | 85        | 1.69%   |
| ASMedia Technology               | 85        | 1.69%   |
| ADATA Technology                 | 81        | 1.61%   |
| Kingston Technology Company      | 67        | 1.33%   |
| Toshiba America Info Systems     | 45        | 0.89%   |
| Marvell Technology Group         | 44        | 0.87%   |
| KIOXIA                           | 42        | 0.83%   |
| Silicon Motion                   | 35        | 0.7%    |
| Micron Technology                | 34        | 0.68%   |
| Realtek Semiconductor            | 29        | 0.58%   |
| Lite-On Technology               | 24        | 0.48%   |
| VIA Technologies                 | 20        | 0.4%    |
| Micron/Crucial Technology        | 19        | 0.38%   |
| LSI Logic / Symbios Logic        | 15        | 0.3%    |
| Union Memory (Shenzhen)          | 13        | 0.26%   |
| Silicon Integrated Systems [SiS] | 11        | 0.22%   |
| Shenzhen Longsys Electronics     | 10        | 0.2%    |
| Solid State Storage Technology   | 8         | 0.16%   |
| Broadcom / LSI                   | 8         | 0.16%   |
| Silicon Image                    | 7         | 0.14%   |
| Lenovo                           | 6         | 0.12%   |
| Hewlett-Packard                  | 6         | 0.12%   |
| INNOGRIT                         | 3         | 0.06%   |
| Apple                            | 3         | 0.06%   |
| Yangtze Memory Technologies      | 2         | 0.04%   |
| ULi Electronics                  | 2         | 0.04%   |
| Adaptec                          | 2         | 0.04%   |
| Tekram Technology                | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| Integrated Technology Express    | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 478       | 7.99%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 209       | 3.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 199       | 3.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 191       | 3.19%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 168       | 2.81%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 147       | 2.46%   |
| AMD 400 Series Chipset SATA Controller                                         | 144       | 2.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 142       | 2.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 123       | 2.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 112       | 1.87%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 99        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 99        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 98        | 1.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 96        | 1.6%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 88        | 1.47%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 83        | 1.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 83        | 1.39%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 82        | 1.37%   |
| Samsung NVMe SSD Controller 980                                                | 81        | 1.35%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 78        | 1.3%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 77        | 1.29%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 75        | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 74        | 1.24%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 72        | 1.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 72        | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 70        | 1.17%   |
| Intel Volume Management Device NVMe RAID Controller                            | 67        | 1.12%   |
| Intel SSD 660P Series                                                          | 66        | 1.1%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 65        | 1.09%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 62        | 1.04%   |
| JMicron JMB363 SATA/IDE Controller                                             | 61        | 1.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 59        | 0.99%   |
| Intel SATA Controller [RAID mode]                                              | 56        | 0.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 53        | 0.89%   |
| Phison E12 NVMe Controller                                                     | 45        | 0.75%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 45        | 0.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 44        | 0.74%   |
| AMD 500 Series Chipset SATA Controller                                         | 42        | 0.7%    |
| Nvidia MCP61 SATA Controller                                                   | 37        | 0.62%   |
| Nvidia MCP61 IDE                                                               | 36        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2920      | 56.83%  |
| NVMe | 1093      | 21.27%  |
| IDE  | 789       | 15.36%  |
| RAID | 310       | 6.03%   |
| SAS  | 13        | 0.25%   |
| SCSI | 13        | 0.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3034      | 75.38%  |
| AMD          | 944       | 23.45%  |
| ARM          | 40        | 0.99%   |
| QUALCOMM     | 3         | 0.07%   |
| PowerMac11,2 | 1         | 0.02%   |
| PowerBook6,7 | 1         | 0.02%   |
| CentaurHauls | 1         | 0.02%   |
| AppliedMicro | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 48        | 1.19%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 41        | 1.01%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 38        | 0.94%   |
| AMD Ryzen 5 3600 6-Core Processor             | 36        | 0.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 33        | 0.82%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 33        | 0.82%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 32        | 0.79%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 31        | 0.77%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 30        | 0.74%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 30        | 0.74%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 29        | 0.72%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 29        | 0.72%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 28        | 0.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 26        | 0.64%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 26        | 0.64%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 26        | 0.64%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 25        | 0.62%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 24        | 0.59%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 24        | 0.59%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 22        | 0.54%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 22        | 0.54%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 22        | 0.54%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 21        | 0.52%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 21        | 0.52%   |
| ARM Processor                                 | 21        | 0.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 20        | 0.5%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 19        | 0.47%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 19        | 0.47%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 19        | 0.47%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 19        | 0.47%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 19        | 0.47%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 19        | 0.47%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 18        | 0.45%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 18        | 0.45%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 18        | 0.45%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 17        | 0.42%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 17        | 0.42%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 17        | 0.42%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 17        | 0.42%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 17        | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 973       | 24.11%  |
| Intel Core i7           | 616       | 15.27%  |
| Intel Core i3           | 299       | 7.41%   |
| Intel Core 2 Duo        | 278       | 6.89%   |
| AMD Ryzen 5             | 256       | 6.34%   |
| Intel Celeron           | 169       | 4.19%   |
| Other                   | 163       | 4.04%   |
| AMD Ryzen 7             | 160       | 3.97%   |
| Intel Pentium           | 117       | 2.9%    |
| Intel Xeon              | 101       | 2.5%    |
| Intel Atom              | 71        | 1.76%   |
| Intel Pentium Dual-Core | 65        | 1.61%   |
| Intel Core 2 Quad       | 58        | 1.44%   |
| AMD FX                  | 47        | 1.16%   |
| AMD Ryzen 9             | 45        | 1.12%   |
| Intel Core 2            | 40        | 0.99%   |
| AMD Ryzen 3             | 34        | 0.84%   |
| AMD Phenom II X4        | 33        | 0.82%   |
| Intel Pentium Dual      | 32        | 0.79%   |
| AMD A6                  | 32        | 0.79%   |
| AMD Athlon 64 X2        | 31        | 0.77%   |
| AMD A8                  | 30        | 0.74%   |
| AMD Athlon II X2        | 26        | 0.64%   |
| AMD A10                 | 26        | 0.64%   |
| AMD A4                  | 18        | 0.45%   |
| Intel Genuine           | 17        | 0.42%   |
| AMD Athlon II X4        | 17        | 0.42%   |
| Intel Core i9           | 15        | 0.37%   |
| AMD Ryzen 7 PRO         | 15        | 0.37%   |
| AMD E                   | 13        | 0.32%   |
| Intel Celeron M         | 11        | 0.27%   |
| ARM BCM                 | 11        | 0.27%   |
| AMD E1                  | 11        | 0.27%   |
| AMD Ryzen Threadripper  | 10        | 0.25%   |
| AMD GX                  | 9         | 0.22%   |
| AMD Athlon              | 9         | 0.22%   |
| Intel Pentium M         | 8         | 0.2%    |
| Intel Pentium D         | 8         | 0.2%    |
| AMD Turion 64 X2 Mobile | 8         | 0.2%    |
| AMD E2                  | 8         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1778      | 43.9%   |
| 4       | 1374      | 33.93%  |
| 6       | 377       | 9.31%   |
| 8       | 237       | 5.85%   |
| 1       | 99        | 2.44%   |
| Unknown | 69        | 1.7%    |
| 12      | 52        | 1.28%   |
| 3       | 23        | 0.57%   |
| 16      | 14        | 0.35%   |
| 14      | 8         | 0.2%    |
| 10      | 8         | 0.2%    |
| 32      | 3         | 0.07%   |
| 24      | 2         | 0.05%   |
| 20      | 2         | 0.05%   |
| 192     | 1         | 0.02%   |
| 48      | 1         | 0.02%   |
| 44      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3984      | 98.91%  |
| 2       | 38        | 0.94%   |
| Unknown | 5         | 0.12%   |
| 4       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2399      | 59.28%  |
| 1       | 1578      | 38.99%  |
| Unknown | 69        | 1.7%    |
| 8       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3902      | 96.7%   |
| Unknown        | 81        | 2.01%   |
| 32-bit         | 50        | 1.24%   |
| 64-bit         | 2         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 784       | 18.85%  |
| 0x306a9    | 262       | 6.3%    |
| 0x206a7    | 253       | 6.08%   |
| 0x306c3    | 211       | 5.07%   |
| 0x1067a    | 201       | 4.83%   |
| 0x906ea    | 114       | 2.74%   |
| 0x506e3    | 100       | 2.4%    |
| 0x40651    | 98        | 2.36%   |
| 0x906e9    | 85        | 2.04%   |
| 0x30678    | 83        | 2%      |
| 0x20655    | 83        | 2%      |
| 0x6fd      | 81        | 1.95%   |
| 0x806ec    | 79        | 1.9%    |
| 0x806ea    | 72        | 1.73%   |
| 0x306d4    | 72        | 1.73%   |
| 0x10676    | 70        | 1.68%   |
| 0x806c1    | 65        | 1.56%   |
| 0x406e3    | 63        | 1.51%   |
| 0x806e9    | 60        | 1.44%   |
| 0x0800820d | 59        | 1.42%   |
| 0x010000c8 | 56        | 1.35%   |
| 0x08701021 | 52        | 1.25%   |
| 0x6fb      | 43        | 1.03%   |
| 0x0a50000c | 43        | 1.03%   |
| 0x06001119 | 37        | 0.89%   |
| 0x08108109 | 34        | 0.82%   |
| 0x20652    | 33        | 0.79%   |
| 0x6f6      | 31        | 0.75%   |
| 0x08701013 | 27        | 0.65%   |
| 0x08600106 | 27        | 0.65%   |
| 0xa0652    | 25        | 0.6%    |
| 0x806eb    | 25        | 0.6%    |
| 0x08108102 | 23        | 0.55%   |
| 0x06000852 | 22        | 0.53%   |
| 0x906ed    | 21        | 0.5%    |
| 0x406c4    | 21        | 0.5%    |
| 0x106e5    | 21        | 0.5%    |
| 0x08001138 | 21        | 0.5%    |
| 0xa0653    | 20        | 0.48%   |
| 0x706e5    | 20        | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 566       | 14.02%  |
| Haswell          | 374       | 9.26%   |
| Penryn           | 312       | 7.73%   |
| IvyBridge        | 312       | 7.73%   |
| SandyBridge      | 300       | 7.43%   |
| Core             | 215       | 5.33%   |
| Skylake          | 203       | 5.03%   |
| Zen 2            | 191       | 4.73%   |
| Zen+             | 150       | 3.72%   |
| Westmere         | 146       | 3.62%   |
| Silvermont       | 142       | 3.52%   |
| K10              | 111       | 2.75%   |
| Broadwell        | 99        | 2.45%   |
| Unknown          | 99        | 2.45%   |
| Zen 3            | 87        | 2.16%   |
| Zen              | 84        | 2.08%   |
| Piledriver       | 78        | 1.93%   |
| TigerLake        | 75        | 1.86%   |
| CometLake        | 68        | 1.68%   |
| K8 Hammer        | 62        | 1.54%   |
| Icelake          | 44        | 1.09%   |
| Nehalem          | 36        | 0.89%   |
| Bobcat           | 34        | 0.84%   |
| Bonnell          | 32        | 0.79%   |
| P6               | 30        | 0.74%   |
| Jaguar           | 25        | 0.62%   |
| Goldmont plus    | 22        | 0.54%   |
| Steamroller      | 18        | 0.45%   |
| Excavator        | 18        | 0.45%   |
| Alderlake Hybrid | 18        | 0.45%   |
| NetBurst         | 17        | 0.42%   |
| K10 Llano        | 16        | 0.4%    |
| Puma             | 15        | 0.37%   |
| K8 & K10 hybrid  | 13        | 0.32%   |
| Goldmont         | 12        | 0.3%    |
| Bulldozer        | 12        | 0.3%    |
| Tremont          | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2246      | 46.92%  |
| Nvidia                           | 1462      | 30.54%  |
| AMD                              | 1054      | 22.02%  |
| Matrox Electronics Systems       | 10        | 0.21%   |
| Silicon Integrated Systems [SiS] | 6         | 0.13%   |
| VIA Technologies                 | 5         | 0.1%    |
| ASPEED Technology                | 3         | 0.06%   |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 241       | 4.83%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 195       | 3.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 118       | 2.36%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 99        | 1.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 93        | 1.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 90        | 1.8%    |
| Intel UHD Graphics 620                                                                   | 84        | 1.68%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 83        | 1.66%   |
| Intel HD Graphics 5500                                                                   | 82        | 1.64%   |
| Intel Core Processor Integrated Graphics Controller                                      | 82        | 1.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 82        | 1.64%   |
| AMD Renoir                                                                               | 81        | 1.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 78        | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 74        | 1.48%   |
| Intel HD Graphics 530                                                                    | 73        | 1.46%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 72        | 1.44%   |
| Intel HD Graphics 620                                                                    | 71        | 1.42%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 70        | 1.4%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 70        | 1.4%    |
| Intel HD Graphics 630                                                                    | 69        | 1.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 67        | 1.34%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 67        | 1.34%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 49        | 0.98%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 48        | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 48        | 0.96%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 44        | 0.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 37        | 0.74%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 37        | 0.74%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 37        | 0.74%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 37        | 0.74%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 37        | 0.74%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 37        | 0.74%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 36        | 0.72%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 30        | 0.6%    |
| Nvidia GT218 [GeForce 210]                                                               | 29        | 0.58%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 28        | 0.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 28        | 0.56%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 26        | 0.52%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 26        | 0.52%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 25        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1544      | 38.02%  |
| 1 x Nvidia               | 849       | 20.91%  |
| 1 x AMD                  | 782       | 19.26%  |
| Intel + Nvidia           | 532       | 13.1%   |
| Intel + AMD              | 138       | 3.4%    |
| AMD + Nvidia             | 75        | 1.85%   |
| 2 x AMD                  | 60        | 1.48%   |
| Other                    | 46        | 1.13%   |
| 1 x Matrox               | 10        | 0.25%   |
| 1 x SiS                  | 6         | 0.15%   |
| 1 x VIA                  | 5         | 0.12%   |
| 2 x Nvidia               | 4         | 0.1%    |
| 2 x Intel                | 3         | 0.07%   |
| 3 x AMD                  | 2         | 0.05%   |
| Nvidia + ASPEED          | 2         | 0.05%   |
| 1 x S3 Graphics          | 1         | 0.02%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.02%   |
| 1 x ASPEED               | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3196      | 77.82%  |
| Proprietary | 723       | 17.6%   |
| Unknown     | 188       | 4.58%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2057      | 49.3%   |
| 1.01-2.0   | 586       | 14.05%  |
| 0.01-0.5   | 549       | 13.16%  |
| 0.51-1.0   | 381       | 9.13%   |
| 3.01-4.0   | 282       | 6.76%   |
| 7.01-8.0   | 161       | 3.86%   |
| 5.01-6.0   | 107       | 2.56%   |
| 8.01-16.0  | 30        | 0.72%   |
| 2.01-3.0   | 16        | 0.38%   |
| 16.01-24.0 | 3         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 637       | 14.24%  |
| AU Optronics            | 522       | 11.67%  |
| LG Display              | 441       | 9.86%   |
| BOE                     | 322       | 7.2%    |
| Chimei Innolux          | 292       | 6.53%   |
| Dell                    | 270       | 6.04%   |
| Goldstar                | 253       | 5.66%   |
| Iiyama                  | 152       | 3.4%    |
| Philips                 | 142       | 3.18%   |
| BenQ                    | 115       | 2.57%   |
| Lenovo                  | 114       | 2.55%   |
| Hewlett-Packard         | 111       | 2.48%   |
| Acer                    | 107       | 2.39%   |
| Chi Mei Optoelectronics | 100       | 2.24%   |
| AOC                     | 92        | 2.06%   |
| NEC Computers           | 71        | 1.59%   |
| Eizo                    | 65        | 1.45%   |
| Ancor Communications    | 59        | 1.32%   |
| Sharp                   | 45        | 1.01%   |
| LG Philips              | 40        | 0.89%   |
| Fujitsu Siemens         | 33        | 0.74%   |
| LG Electronics          | 32        | 0.72%   |
| PANDA                   | 31        | 0.69%   |
| Sony                    | 30        | 0.67%   |
| InfoVision              | 21        | 0.47%   |
| Apple                   | 19        | 0.42%   |
| ASUSTek Computer        | 18        | 0.4%    |
| Unknown                 | 17        | 0.38%   |
| Toshiba                 | 16        | 0.36%   |
| ViewSonic               | 14        | 0.31%   |
| Panasonic               | 13        | 0.29%   |
| Idek Iiyama             | 13        | 0.29%   |
| HannStar                | 13        | 0.29%   |
| Gateway                 | 13        | 0.29%   |
| CPT                     | 13        | 0.29%   |
| MSI                     | 11        | 0.25%   |
| Belinea                 | 11        | 0.25%   |
| Hitachi                 | 9         | 0.2%    |
| Vestel Elektronik       | 8         | 0.18%   |
| Medion                  | 8         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 31        | 0.66%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 28        | 0.6%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 27        | 0.58%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 22        | 0.47%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 21        | 0.45%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 20        | 0.43%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 18        | 0.39%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 17        | 0.36%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 17        | 0.36%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 16        | 0.34%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 16        | 0.34%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 15        | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 15        | 0.32%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 14        | 0.3%    |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                    | 14        | 0.3%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 14        | 0.3%    |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 13        | 0.28%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 13        | 0.28%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 12        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 12        | 0.26%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 12        | 0.26%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 12        | 0.26%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 12        | 0.26%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 11        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 11        | 0.24%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 11        | 0.24%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 11        | 0.24%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 11        | 0.24%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 11        | 0.24%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 10        | 0.21%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch                 | 10        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 10        | 0.21%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 10        | 0.21%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 10        | 0.21%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 10        | 0.21%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 9         | 0.19%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 9         | 0.19%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 9         | 0.19%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                     | 9         | 0.19%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 9         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1793      | 42.33%  |
| 1366x768 (WXGA)    | 729       | 17.21%  |
| 1280x1024 (SXGA)   | 202       | 4.77%   |
| 1600x900 (HD+)     | 193       | 4.56%   |
| 3840x2160 (4K)     | 184       | 4.34%   |
| 2560x1440 (QHD)    | 174       | 4.11%   |
| 1280x800 (WXGA)    | 169       | 3.99%   |
| 1680x1050 (WSXGA+) | 164       | 3.87%   |
| 1920x1200 (WUXGA)  | 147       | 3.47%   |
| 1440x900 (WXGA+)   | 122       | 2.88%   |
| Unknown            | 42        | 0.99%   |
| 3440x1440          | 38        | 0.9%    |
| 2560x1080          | 35        | 0.83%   |
| 1024x600           | 26        | 0.61%   |
| 1360x768           | 22        | 0.52%   |
| 1024x768 (XGA)     | 21        | 0.5%    |
| 2560x1600          | 20        | 0.47%   |
| 3840x1080          | 19        | 0.45%   |
| 1600x1200          | 18        | 0.42%   |
| 800x1280           | 9         | 0.21%   |
| 1920x540           | 9         | 0.21%   |
| 2160x1440          | 8         | 0.19%   |
| 3840x2400          | 6         | 0.14%   |
| 3200x1800 (QHD+)   | 6         | 0.14%   |
| 2880x1800          | 6         | 0.14%   |
| 2048x1152          | 5         | 0.12%   |
| 1280x720 (HD)      | 5         | 0.12%   |
| 2288x1287          | 4         | 0.09%   |
| 1680x945           | 4         | 0.09%   |
| 1400x1050          | 4         | 0.09%   |
| 5120x1440          | 3         | 0.07%   |
| 3840x1600          | 3         | 0.07%   |
| 3286x1080          | 3         | 0.07%   |
| 3200x1080          | 3         | 0.07%   |
| 1280x960           | 3         | 0.07%   |
| 1280x768           | 3         | 0.07%   |
| 3840x1200          | 2         | 0.05%   |
| 3600x1080          | 2         | 0.05%   |
| 3000x2000          | 2         | 0.05%   |
| 2256x1504          | 2         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1217      | 27.19%  |
| 24      | 357       | 7.98%   |
| 13      | 332       | 7.42%   |
| 14      | 318       | 7.1%    |
| 23      | 304       | 6.79%   |
| 17      | 286       | 6.39%   |
| 21      | 268       | 5.99%   |
| 27      | 267       | 5.97%   |
| Unknown | 244       | 5.45%   |
| 19      | 163       | 3.64%   |
| 22      | 97        | 2.17%   |
| 12      | 87        | 1.94%   |
| 18      | 67        | 1.5%    |
| 34      | 65        | 1.45%   |
| 31      | 54        | 1.21%   |
| 20      | 45        | 1.01%   |
| 11      | 34        | 0.76%   |
| 84      | 28        | 0.63%   |
| 10      | 28        | 0.63%   |
| 25      | 25        | 0.56%   |
| 72      | 24        | 0.54%   |
| 16      | 21        | 0.47%   |
| 32      | 20        | 0.45%   |
| 54      | 18        | 0.4%    |
| 48      | 13        | 0.29%   |
| 40      | 10        | 0.22%   |
| 65      | 8         | 0.18%   |
| 42      | 8         | 0.18%   |
| 33      | 8         | 0.18%   |
| 28      | 8         | 0.18%   |
| 49      | 7         | 0.16%   |
| 26      | 6         | 0.13%   |
| 46      | 5         | 0.11%   |
| 37      | 5         | 0.11%   |
| 39      | 4         | 0.09%   |
| 142     | 3         | 0.07%   |
| 55      | 3         | 0.07%   |
| 43      | 3         | 0.07%   |
| 35      | 3         | 0.07%   |
| 29      | 3         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1764      | 40.18%  |
| 501-600        | 876       | 19.95%  |
| 401-500        | 532       | 12.12%  |
| 351-400        | 356       | 8.11%   |
| 201-300        | 291       | 6.63%   |
| Unknown        | 244       | 5.56%   |
| 701-800        | 93        | 2.12%   |
| 601-700        | 82        | 1.87%   |
| 1001-1500      | 60        | 1.37%   |
| 1501-2000      | 52        | 1.18%   |
| 801-900        | 23        | 0.52%   |
| 901-1000       | 11        | 0.25%   |
| More than 2000 | 3         | 0.07%   |
| 1-100          | 3         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2839      | 70.43%  |
| 16/10   | 601       | 14.91%  |
| Unknown | 209       | 5.18%   |
| 5/4     | 187       | 4.64%   |
| 21/9    | 72        | 1.79%   |
| 4/3     | 49        | 1.22%   |
| 3/2     | 44        | 1.09%   |
| 32/9    | 13        | 0.32%   |
| 0.62    | 7         | 0.17%   |
| 6/5     | 5         | 0.12%   |
| 1.00    | 3         | 0.07%   |
| 0.67    | 2         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1212      | 27.33%  |
| 201-250        | 783       | 17.66%  |
| 81-90          | 524       | 11.82%  |
| 151-200        | 277       | 6.25%   |
| 301-350        | 271       | 6.11%   |
| Unknown        | 244       | 5.5%    |
| 251-300        | 182       | 4.1%    |
| 121-130        | 160       | 3.61%   |
| 351-500        | 156       | 3.52%   |
| 141-150        | 139       | 3.13%   |
| 71-80          | 118       | 2.66%   |
| More than 1000 | 101       | 2.28%   |
| 61-70          | 85        | 1.92%   |
| 501-1000       | 45        | 1.01%   |
| 131-140        | 39        | 0.88%   |
| 51-60          | 34        | 0.77%   |
| 41-50          | 28        | 0.63%   |
| 91-100         | 18        | 0.41%   |
| 111-120        | 15        | 0.34%   |
| 1-40           | 3         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1534      | 35.69%  |
| 121-160       | 1143      | 26.59%  |
| 101-120       | 1087      | 25.29%  |
| Unknown       | 244       | 5.68%   |
| 161-240       | 149       | 3.47%   |
| 1-50          | 85        | 1.98%   |
| More than 240 | 56        | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3255      | 78.79%  |
| 2     | 608       | 14.72%  |
| 0     | 161       | 3.9%    |
| 3     | 92        | 2.23%   |
| 4     | 13        | 0.31%   |
| 6     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2040      | 32.76%  |
| Intel                                  | 1961      | 31.49%  |
| Qualcomm Atheros                       | 775       | 12.45%  |
| Broadcom                               | 360       | 5.78%   |
| Broadcom Limited                       | 111       | 1.78%   |
| TP-Link                                | 89        | 1.43%   |
| Marvell Technology Group               | 83        | 1.33%   |
| Huawei Technologies                    | 83        | 1.33%   |
| Ralink                                 | 65        | 1.04%   |
| Ralink Technology                      | 63        | 1.01%   |
| Dell                                   | 62        | 1%      |
| Nvidia                                 | 59        | 0.95%   |
| MediaTek                               | 47        | 0.75%   |
| Qualcomm Atheros Communications        | 42        | 0.67%   |
| Samsung Electronics                    | 34        | 0.55%   |
| Xiaomi                                 | 31        | 0.5%    |
| Microsoft                              | 27        | 0.43%   |
| Ericsson Business Mobile Networks      | 25        | 0.4%    |
| ASUSTek Computer                       | 23        | 0.37%   |
| Hewlett-Packard                        | 21        | 0.34%   |
| Sierra Wireless                        | 16        | 0.26%   |
| JMicron Technology                     | 15        | 0.24%   |
| Lenovo                                 | 13        | 0.21%   |
| ASIX Electronics                       | 11        | 0.18%   |
| VIA Technologies                       | 10        | 0.16%   |
| Motorola PCS                           | 10        | 0.16%   |
| Edimax Technology                      | 10        | 0.16%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.14%   |
| Aquantia                               | 9         | 0.14%   |
| NetGear                                | 8         | 0.13%   |
| Fibocom                                | 8         | 0.13%   |
| DisplayLink                            | 8         | 0.13%   |
| D-Link                                 | 8         | 0.13%   |
| Qualcomm                               | 6         | 0.1%    |
| Sony Ericsson Mobile Communications AB | 5         | 0.08%   |
| OnePlus Technology (Shenzhen)          | 5         | 0.08%   |
| Microchip Technology                   | 5         | 0.08%   |
| HTC (High Tech Computer)               | 5         | 0.08%   |
| Sagem                                  | 4         | 0.06%   |
| ZTE WCDMA Technologies MSM             | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1485      | 20.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 224       | 3.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 208       | 2.86%   |
| Intel Wi-Fi 6 AX200                                               | 148       | 2.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 109       | 1.5%    |
| Intel Wireless 8265 / 8275                                        | 109       | 1.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 107       | 1.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 104       | 1.43%   |
| Intel Wireless 7260                                               | 98        | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 89        | 1.22%   |
| Intel Wireless 8260                                               | 83        | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 76        | 1.04%   |
| Intel I211 Gigabit Network Connection                             | 74        | 1.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 72        | 0.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 71        | 0.97%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 67        | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 65        | 0.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 64        | 0.88%   |
| Intel Ethernet Connection I217-LM                                 | 64        | 0.88%   |
| Intel Wireless 7265                                               | 60        | 0.82%   |
| Intel Wi-Fi 6 AX201                                               | 60        | 0.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 56        | 0.77%   |
| Intel Wireless 3160                                               | 53        | 0.73%   |
| Intel Ethernet Connection (2) I219-V                              | 52        | 0.71%   |
| Intel 82579V Gigabit Network Connection                           | 51        | 0.7%    |
| Intel Wireless 3165                                               | 50        | 0.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 49        | 0.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 48        | 0.66%   |
| Intel 82567LM Gigabit Network Connection                          | 48        | 0.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 46        | 0.63%   |
| Huawei E353/E3131                                                 | 46        | 0.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 45        | 0.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 45        | 0.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 45        | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 44        | 0.6%    |
| Intel Centrino Ultimate-N 6300                                    | 44        | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 42        | 0.58%   |
| Intel Ethernet Connection I218-LM                                 | 41        | 0.56%   |
| Intel WiFi Link 5100                                              | 40        | 0.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 39        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1499      | 46.74%  |
| Qualcomm Atheros                | 588       | 18.33%  |
| Realtek Semiconductor           | 395       | 12.32%  |
| Broadcom                        | 208       | 6.49%   |
| TP-Link                         | 84        | 2.62%   |
| Ralink                          | 65        | 2.03%   |
| Ralink Technology               | 63        | 1.96%   |
| Broadcom Limited                | 53        | 1.65%   |
| MediaTek                        | 44        | 1.37%   |
| Qualcomm Atheros Communications | 42        | 1.31%   |
| Dell                            | 39        | 1.22%   |
| Microsoft                       | 27        | 0.84%   |
| ASUSTek Computer                | 23        | 0.72%   |
| Sierra Wireless                 | 16        | 0.5%    |
| Edimax Technology               | 10        | 0.31%   |
| Fibocom                         | 8         | 0.25%   |
| NetGear                         | 7         | 0.22%   |
| D-Link                          | 7         | 0.22%   |
| Hewlett-Packard                 | 5         | 0.16%   |
| Sagem                           | 4         | 0.12%   |
| Qualcomm                        | 4         | 0.12%   |
| ZyXEL Communications            | 2         | 0.06%   |
| ZyDAS                           | 2         | 0.06%   |
| Linksys                         | 2         | 0.06%   |
| D-Link System                   | 2         | 0.06%   |
| Belkin Components               | 2         | 0.06%   |
| Z-Com                           | 1         | 0.03%   |
| Wacom                           | 1         | 0.03%   |
| Tenda                           | 1         | 0.03%   |
| IMC Networks                    | 1         | 0.03%   |
| AVM                             | 1         | 0.03%   |
| Accton Technology               | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 148       | 4.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 109       | 3.39%   |
| Intel Wireless 8265 / 8275                                              | 109       | 3.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 107       | 3.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 104       | 3.24%   |
| Intel Wireless 7260                                                     | 98        | 3.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 89        | 2.77%   |
| Intel Wireless 8260                                                     | 83        | 2.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 76        | 2.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 72        | 2.24%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 67        | 2.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 65        | 2.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 64        | 1.99%   |
| Intel Wireless 7265                                                     | 60        | 1.87%   |
| Intel Wi-Fi 6 AX201                                                     | 60        | 1.87%   |
| Intel Wireless 3160                                                     | 53        | 1.65%   |
| Intel Wireless 3165                                                     | 50        | 1.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 49        | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 48        | 1.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 45        | 1.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 45        | 1.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 45        | 1.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 44        | 1.37%   |
| Intel Centrino Ultimate-N 6300                                          | 44        | 1.37%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 42        | 1.31%   |
| Intel WiFi Link 5100                                                    | 40        | 1.24%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 39        | 1.21%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 38        | 1.18%   |
| Broadcom BCM43142 802.11b/g/n                                           | 38        | 1.18%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 34        | 1.06%   |
| Intel Wireless-AC 9260                                                  | 34        | 1.06%   |
| Qualcomm Atheros AR9271 802.11n                                         | 32        | 1%      |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 32        | 1%      |
| Intel Comet Lake PCH CNVi WiFi                                          | 32        | 1%      |
| Intel Centrino Advanced-N 6200                                          | 29        | 0.9%    |
| Ralink MT7601U Wireless Adapter                                         | 28        | 0.87%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 28        | 0.87%   |
| Intel Centrino Advanced-N 6235                                          | 28        | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 27        | 0.84%   |
| Intel Centrino Wireless-N 2230                                          | 24        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1884      | 48.47%  |
| Intel                                  | 1086      | 27.94%  |
| Qualcomm Atheros                       | 271       | 6.97%   |
| Broadcom                               | 184       | 4.73%   |
| Marvell Technology Group               | 83        | 2.14%   |
| Nvidia                                 | 59        | 1.52%   |
| Broadcom Limited                       | 59        | 1.52%   |
| Huawei Technologies                    | 56        | 1.44%   |
| Samsung Electronics                    | 33        | 0.85%   |
| Xiaomi                                 | 30        | 0.77%   |
| JMicron Technology                     | 15        | 0.39%   |
| Lenovo                                 | 13        | 0.33%   |
| ASIX Electronics                       | 11        | 0.28%   |
| VIA Technologies                       | 10        | 0.26%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.23%   |
| Motorola PCS                           | 9         | 0.23%   |
| Aquantia                               | 9         | 0.23%   |
| DisplayLink                            | 8         | 0.21%   |
| TP-Link                                | 6         | 0.15%   |
| Microchip Technology                   | 5         | 0.13%   |
| HTC (High Tech Computer)               | 5         | 0.13%   |
| Sony Ericsson Mobile Communications AB | 4         | 0.1%    |
| OnePlus Technology (Shenzhen)          | 3         | 0.08%   |
| Hewlett-Packard                        | 3         | 0.08%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.05%   |
| Research In Motion                     | 2         | 0.05%   |
| Qualcomm                               | 2         | 0.05%   |
| QLogic                                 | 2         | 0.05%   |
| MediaTek                               | 2         | 0.05%   |
| ICS Advent                             | 2         | 0.05%   |
| Google                                 | 2         | 0.05%   |
| Attansic Technology                    | 2         | 0.05%   |
| Apple                                  | 2         | 0.05%   |
| 3Com                                   | 2         | 0.05%   |
| QinHeng Electronics                    | 1         | 0.03%   |
| OPPO Electronics                       | 1         | 0.03%   |
| NetXen Incorporated                    | 1         | 0.03%   |
| NetGear                                | 1         | 0.03%   |
| Mellanox Technologies                  | 1         | 0.03%   |
| LG Electronics                         | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1485      | 37.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 224       | 5.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 208       | 5.27%   |
| Intel I211 Gigabit Network Connection                             | 74        | 1.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 71        | 1.8%    |
| Intel Ethernet Connection I217-LM                                 | 64        | 1.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 56        | 1.42%   |
| Intel Ethernet Connection (2) I219-V                              | 52        | 1.32%   |
| Intel 82579V Gigabit Network Connection                           | 51        | 1.29%   |
| Intel 82567LM Gigabit Network Connection                          | 48        | 1.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 46        | 1.17%   |
| Huawei E353/E3131                                                 | 46        | 1.17%   |
| Intel Ethernet Connection I218-LM                                 | 41        | 1.04%   |
| Intel Ethernet Connection (7) I219-V                              | 37        | 0.94%   |
| Intel 82577LM Gigabit Network Connection                          | 37        | 0.94%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 34        | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 32        | 0.81%   |
| Intel Ethernet Connection (4) I219-LM                             | 32        | 0.81%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 31        | 0.79%   |
| Intel Ethernet Connection (2) I219-LM                             | 31        | 0.79%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 30        | 0.76%   |
| Nvidia MCP61 Ethernet                                             | 30        | 0.76%   |
| Intel Ethernet Connection (6) I219-V                              | 29        | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                             | 26        | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                             | 26        | 0.66%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 24        | 0.61%   |
| Intel Ethernet Connection I219-LM                                 | 23        | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 22        | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 22        | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 21        | 0.53%   |
| Intel Ethernet Controller I225-V                                  | 20        | 0.51%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 20        | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 19        | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 19        | 0.48%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 19        | 0.48%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 19        | 0.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 18        | 0.46%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 18        | 0.46%   |
| Intel Ethernet Connection (4) I219-V                              | 18        | 0.46%   |
| Intel Ethernet Connection (2) I218-V                              | 17        | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3649      | 53.77%  |
| WiFi     | 3016      | 44.44%  |
| Modem    | 109       | 1.61%   |
| Unknown  | 12        | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2322      | 56.61%  |
| Ethernet | 1779      | 43.37%  |
| Unknown  | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2369      | 58.62%  |
| 1     | 1513      | 37.44%  |
| 0     | 88        | 2.18%   |
| 3     | 54        | 1.34%   |
| 4     | 8         | 0.2%    |
| 5     | 3         | 0.07%   |
| 6     | 2         | 0.05%   |
| 17    | 1         | 0.02%   |
| 10    | 1         | 0.02%   |
| 9     | 1         | 0.02%   |
| 8     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3804      | 93.79%  |
| Yes  | 252       | 6.21%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1030      | 45.41%  |
| Qualcomm Atheros Communications | 220       | 9.7%    |
| Broadcom                        | 167       | 7.36%   |
| Realtek Semiconductor           | 147       | 6.48%   |
| Cambridge Silicon Radio         | 142       | 6.26%   |
| IMC Networks                    | 90        | 3.97%   |
| ASUSTek Computer                | 83        | 3.66%   |
| Dell                            | 74        | 3.26%   |
| Foxconn / Hon Hai               | 59        | 2.6%    |
| Hewlett-Packard                 | 56        | 2.47%   |
| Lite-On Technology              | 52        | 2.29%   |
| Apple                           | 26        | 1.15%   |
| Toshiba                         | 24        | 1.06%   |
| Ralink                          | 17        | 0.75%   |
| Foxconn International           | 14        | 0.62%   |
| Realtek                         | 11        | 0.49%   |
| MediaTek                        | 8         | 0.35%   |
| Integrated System Solution      | 7         | 0.31%   |
| Chicony Electronics             | 6         | 0.26%   |
| Taiyo Yuden                     | 5         | 0.22%   |
| Edimax Technology               | 5         | 0.22%   |
| Alps Electric                   | 5         | 0.22%   |
| TP-Link                         | 3         | 0.13%   |
| Ralink Technology               | 3         | 0.13%   |
| Micro Star International        | 2         | 0.09%   |
| Conwise Technology              | 2         | 0.09%   |
| USI                             | 1         | 0.04%   |
| SINO WEALTH                     | 1         | 0.04%   |
| Opticis                         | 1         | 0.04%   |
| Logitech                        | 1         | 0.04%   |
| Fujitsu                         | 1         | 0.04%   |
| Creative Technology             | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| Askey Computer                  | 1         | 0.04%   |
| AboCom Systems                  | 1         | 0.04%   |
| Unknown                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 450       | 19.84%  |
| Intel AX200 Bluetooth                               | 142       | 6.26%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 142       | 6.26%   |
| Intel AX201 Bluetooth                               | 140       | 6.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 134       | 5.91%   |
| Realtek Bluetooth Radio                             | 95        | 4.19%   |
| Qualcomm Atheros  Bluetooth Device                  | 94        | 4.14%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 51        | 2.25%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 49        | 2.16%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 47        | 2.07%   |
| Intel Wireless-AC 3168 Bluetooth                    | 44        | 1.94%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 37        | 1.63%   |
| IMC Networks Bluetooth Radio                        | 37        | 1.63%   |
| Broadcom BCM2045B (BDC-2.1)                         | 35        | 1.54%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 33        | 1.46%   |
| Realtek  Bluetooth 4.2 Adapter                      | 32        | 1.41%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 30        | 1.32%   |
| Dell BCM20702A0 Bluetooth Module                    | 24        | 1.06%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 22        | 0.97%   |
| HP Broadcom 2070 Bluetooth Combo                    | 22        | 0.97%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 22        | 0.97%   |
| IMC Networks Bluetooth Device                       | 18        | 0.79%   |
| Dell DW375 Bluetooth Module                         | 18        | 0.79%   |
| Ralink RT3290 Bluetooth                             | 17        | 0.75%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 17        | 0.75%   |
| Broadcom BCM2070 Bluetooth Device                   | 17        | 0.75%   |
| Realtek RTL8723B Bluetooth                          | 16        | 0.71%   |
| Lite-On Bluetooth Device                            | 15        | 0.66%   |
| IMC Networks Wireless_Device                        | 15        | 0.66%   |
| Lite-On Atheros AR3012 Bluetooth                    | 14        | 0.62%   |
| Foxconn International BCM43142A0 Bluetooth module   | 14        | 0.62%   |
| Foxconn / Hon Hai Wireless_Device                   | 13        | 0.57%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 12        | 0.53%   |
| Broadcom HP Portable SoftSailing                    | 12        | 0.53%   |
| Broadcom BCM2045 Bluetooth                          | 12        | 0.53%   |
| Toshiba Integrated Bluetooth HCI                    | 11        | 0.49%   |
| Realtek Bluetooth Radio                             | 11        | 0.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 11        | 0.49%   |
| Intel AX210 Bluetooth                               | 11        | 0.49%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 11        | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2914      | 52.7%   |
| AMD                                  | 1101      | 19.91%  |
| Nvidia                               | 986       | 17.83%  |
| Creative Labs                        | 77        | 1.39%   |
| C-Media Electronics                  | 77        | 1.39%   |
| Creative Technology                  | 39        | 0.71%   |
| Logitech                             | 22        | 0.4%    |
| Realtek Semiconductor                | 20        | 0.36%   |
| VIA Technologies                     | 19        | 0.34%   |
| Texas Instruments                    | 18        | 0.33%   |
| JMTek                                | 18        | 0.33%   |
| Plantronics                          | 16        | 0.29%   |
| Lenovo                               | 14        | 0.25%   |
| SteelSeries ApS                      | 12        | 0.22%   |
| Kingston Technology                  | 12        | 0.22%   |
| Silicon Integrated Systems [SiS]     | 11        | 0.2%    |
| GYROCOM C&C                          | 11        | 0.2%    |
| Dell                                 | 9         | 0.16%   |
| GN Netcom                            | 8         | 0.14%   |
| Generalplus Technology               | 8         | 0.14%   |
| SAVITECH                             | 7         | 0.13%   |
| Focusrite-Novation                   | 7         | 0.13%   |
| Razer USA                            | 6         | 0.11%   |
| BEHRINGER International              | 6         | 0.11%   |
| ASUSTek Computer                     | 6         | 0.11%   |
| Samson Technologies                  | 5         | 0.09%   |
| AudioQuest                           | 5         | 0.09%   |
| Valve Software                       | 4         | 0.07%   |
| RODE Microphones                     | 4         | 0.07%   |
| Hewlett-Packard                      | 4         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.05%   |
| Sennheiser Communications            | 3         | 0.05%   |
| PreSonus Audio Electronics           | 3         | 0.05%   |
| M-Audio                              | 3         | 0.05%   |
| Corsair                              | 3         | 0.05%   |
| Cambridge Audio                      | 3         | 0.05%   |
| XMOS                                 | 2         | 0.04%   |
| ULi Electronics                      | 2         | 0.04%   |
| Sony                                 | 2         | 0.04%   |
| SM900T Microphone                    | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 331       | 5.09%   |
| AMD Family 17h/19h HD Audio Controller                                     | 267       | 4.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 258       | 3.97%   |
| Intel Sunrise Point-LP HD Audio                                            | 242       | 3.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 205       | 3.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 200       | 3.08%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 170       | 2.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 167       | 2.57%   |
| Intel Cannon Lake PCH cAVS                                                 | 158       | 2.43%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 152       | 2.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 149       | 2.29%   |
| AMD Starship/Matisse HD Audio Controller                                   | 135       | 2.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 131       | 2.01%   |
| AMD FCH Azalia Controller                                                  | 128       | 1.97%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 125       | 1.92%   |
| Intel 8 Series HD Audio Controller                                         | 122       | 1.88%   |
| Intel Haswell-ULT HD Audio Controller                                      | 120       | 1.85%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 112       | 1.72%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 111       | 1.71%   |
| Nvidia GP107GL High Definition Audio Controller                            | 98        | 1.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 98        | 1.51%   |
| Intel Broadwell-U Audio Controller                                         | 93        | 1.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 92        | 1.41%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 83        | 1.28%   |
| Nvidia GF108 High Definition Audio Controller                              | 80        | 1.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 80        | 1.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 75        | 1.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 73        | 1.12%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 69        | 1.06%   |
| Nvidia GP106 High Definition Audio Controller                              | 64        | 0.98%   |
| Intel 200 Series PCH HD Audio                                              | 59        | 0.91%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 56        | 0.86%   |
| Intel CM238 HD Audio Controller                                            | 55        | 0.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 54        | 0.83%   |
| Nvidia GP104 High Definition Audio Controller                              | 51        | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                              | 50        | 0.77%   |
| Nvidia High Definition Audio Controller                                    | 48        | 0.74%   |
| Intel Comet Lake PCH-LP cAVS                                               | 46        | 0.71%   |
| AMD Kabini HDMI/DP Audio                                                   | 45        | 0.69%   |
| Nvidia GK107 HDMI Audio Controller                                         | 43        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 619       | 21.15%  |
| SK hynix                     | 474       | 16.19%  |
| Kingston                     | 392       | 13.39%  |
| Unknown                      | 368       | 12.57%  |
| Micron Technology            | 232       | 7.93%   |
| Goodram                      | 174       | 5.94%   |
| Crucial                      | 133       | 4.54%   |
| G.Skill                      | 85        | 2.9%    |
| Corsair                      | 70        | 2.39%   |
| A-DATA Technology            | 66        | 2.25%   |
| Ramaxel Technology           | 50        | 1.71%   |
| Nanya Technology             | 49        | 1.67%   |
| Patriot                      | 46        | 1.57%   |
| Elpida                       | 40        | 1.37%   |
| Unknown                      | 19        | 0.65%   |
| Wilk                         | 13        | 0.44%   |
| Qimonda                      | 13        | 0.44%   |
| Wilk Elektronik              | 9         | 0.31%   |
| Unknown (ABCD)               | 9         | 0.31%   |
| ASint Technology             | 9         | 0.31%   |
| Apacer                       | 9         | 0.31%   |
| GeIL                         | 8         | 0.27%   |
| Unifosa                      | 4         | 0.14%   |
| 48spaces                     | 4         | 0.14%   |
| Patriot Memory (PDP Systems) | 3         | 0.1%    |
| OCZ                          | 3         | 0.1%    |
| Toshiba                      | 2         | 0.07%   |
| Silicon Power                | 2         | 0.07%   |
| Aeneon                       | 2         | 0.07%   |
| Unknown (8A02)               | 1         | 0.03%   |
| Unknown (768A)               | 1         | 0.03%   |
| Unknown (0x0702)             | 1         | 0.03%   |
| Transcend                    | 1         | 0.03%   |
| tigo                         | 1         | 0.03%   |
| Team                         | 1         | 0.03%   |
| Swissbit                     | 1         | 0.03%   |
| Smart                        | 1         | 0.03%   |
| SHARETRONIC                  | 1         | 0.03%   |
| PNY                          | 1         | 0.03%   |
| KingFast                     | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s    | 36        | 1.12%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 28        | 0.87%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 28        | 0.87%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 25        | 0.78%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 23        | 0.72%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 23        | 0.72%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 23        | 0.72%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 22        | 0.69%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 22        | 0.69%   |
| GOODRAM RAM GR2666S464L19/16G 16GB SODIMM DDR4 2667MT/s  | 21        | 0.66%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s | 20        | 0.62%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s    | 19        | 0.59%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s    | 19        | 0.59%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s    | 19        | 0.59%   |
| Unknown                                                  | 19        | 0.59%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                   | 18        | 0.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 18        | 0.56%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s   | 17        | 0.53%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s    | 16        | 0.5%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s    | 15        | 0.47%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s    | 15        | 0.47%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s      | 14        | 0.44%   |
| GOODRAM RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s  | 14        | 0.44%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 13        | 0.41%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s    | 13        | 0.41%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2667MT/s  | 13        | 0.41%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                  | 12        | 0.37%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s    | 12        | 0.37%   |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s | 12        | 0.37%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 12        | 0.37%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s    | 12        | 0.37%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s    | 12        | 0.37%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 12        | 0.37%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s    | 11        | 0.34%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s    | 11        | 0.34%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s     | 11        | 0.34%   |
| GOODRAM RAM GR1333D364L9/4G 4GB DIMM DDR3 1600MT/s       | 11        | 0.34%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s      | 11        | 0.34%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s  | 11        | 0.34%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 10        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 973       | 39.27%  |
| DDR3    | 912       | 36.8%   |
| DDR2    | 212       | 8.56%   |
| Unknown | 127       | 5.13%   |
| SDRAM   | 118       | 4.76%   |
| LPDDR4  | 47        | 1.9%    |
| LPDDR3  | 37        | 1.49%   |
| DDR     | 31        | 1.25%   |
| DDR5    | 14        | 0.56%   |
| DRAM    | 6         | 0.24%   |
| LPDDR5  | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1457      | 59.86%  |
| DIMM         | 879       | 36.11%  |
| Row Of Chips | 78        | 3.2%    |
| Chip         | 10        | 0.41%   |
| Unknown      | 7         | 0.29%   |
| RIMM         | 2         | 0.08%   |
| FB-DIMM      | 1         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 818       | 29.97%  |
| 4096    | 759       | 27.81%  |
| 2048    | 496       | 18.18%  |
| 16384   | 364       | 13.34%  |
| 1024    | 184       | 6.74%   |
| 32768   | 73        | 2.67%   |
| 512     | 26        | 0.95%   |
| Unknown | 4         | 0.15%   |
| 1536    | 2         | 0.07%   |
| 256     | 2         | 0.07%   |
| 64      | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 623       | 22.85%  |
| 2667    | 358       | 13.13%  |
| 3200    | 312       | 11.45%  |
| 1333    | 184       | 6.75%   |
| 2400    | 158       | 5.8%    |
| 667     | 118       | 4.33%   |
| 1334    | 115       | 4.22%   |
| 2133    | 110       | 4.04%   |
| 800     | 110       | 4.04%   |
| Unknown | 70        | 2.57%   |
| 3600    | 65        | 2.38%   |
| 1067    | 50        | 1.83%   |
| 4199    | 39        | 1.43%   |
| 1867    | 32        | 1.17%   |
| 533     | 31        | 1.14%   |
| 1066    | 25        | 0.92%   |
| 2048    | 23        | 0.84%   |
| 3000    | 22        | 0.81%   |
| 975     | 22        | 0.81%   |
| 400     | 19        | 0.7%    |
| 3400    | 18        | 0.66%   |
| 1866    | 16        | 0.59%   |
| 2933    | 15        | 0.55%   |
| 4800    | 14        | 0.51%   |
| 4267    | 14        | 0.51%   |
| 3866    | 14        | 0.51%   |
| 3733    | 13        | 0.48%   |
| 3466    | 13        | 0.48%   |
| 1800    | 12        | 0.44%   |
| 3266    | 11        | 0.4%    |
| 8400    | 10        | 0.37%   |
| 333     | 10        | 0.37%   |
| 2666    | 9         | 0.33%   |
| 3800    | 8         | 0.29%   |
| 2866    | 6         | 0.22%   |
| 49926   | 4         | 0.15%   |
| 4266    | 4         | 0.15%   |
| 2800    | 4         | 0.15%   |
| 3333    | 3         | 0.11%   |
| 2000    | 3         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 45        | 46.39%  |
| Samsung Electronics   | 12        | 12.37%  |
| Brother Industries    | 11        | 11.34%  |
| Canon                 | 10        | 10.31%  |
| Seiko Epson           | 7         | 7.22%   |
| Prolific Technology   | 5         | 5.15%   |
| Zebra                 | 2         | 2.06%   |
| Xerox                 | 2         | 2.06%   |
| MIIIW                 | 1         | 1.03%   |
| Lexmark International | 1         | 1.03%   |
| Datamax-O'Neil        | 1         | 1.03%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port           | 5         | 5.05%   |
| HP LaserJet 1020                        | 4         | 4.04%   |
| Canon iP7200 series                     | 3         | 3.03%   |
| Seiko Epson AL-M310DN                   | 2         | 2.02%   |
| Samsung ML-216x Series Laser Printer    | 2         | 2.02%   |
| Samsung ML-2010P Mono Laser Printer     | 2         | 2.02%   |
| HP LaserJet P2015 series                | 2         | 2.02%   |
| HP LaserJet P1102                       | 2         | 2.02%   |
| HP LaserJet M14-M17                     | 2         | 2.02%   |
| HP Deskjet F4500 series                 | 2         | 2.02%   |
| HP DeskJet F4100 Printer series         | 2         | 2.02%   |
| HP Deskjet F2280 series                 | 2         | 2.02%   |
| HP DeskJet 845c                         | 2         | 2.02%   |
| HP DeskJet 3700 series                  | 2         | 2.02%   |
| HP DeskJet 2620 All-in-One Printer      | 2         | 2.02%   |
| HP Deskjet 2540 series                  | 2         | 2.02%   |
| HP Deskjet 1050 J410                    | 2         | 2.02%   |
| Canon MG5600 series                     | 2         | 2.02%   |
| Canon LiDE 400                          | 2         | 2.02%   |
| Brother DCP-J105                        | 2         | 2.02%   |
| Brother DCP-1610W                       | 2         | 2.02%   |
| Zebra ZTC GX420t                        | 1         | 1.01%   |
| Zebra LP2844 Printer                    | 1         | 1.01%   |
| Xerox WorkCentre PE16                   | 1         | 1.01%   |
| Xerox Phaser 6000B                      | 1         | 1.01%   |
| Seiko Epson Stylus NX230/SX235W Series  | 1         | 1.01%   |
| Seiko Epson L405 Series                 | 1         | 1.01%   |
| Seiko Epson L3150 Series                | 1         | 1.01%   |
| Seiko Epson L1110 Series                | 1         | 1.01%   |
| Seiko Epson ET-2600 Series              | 1         | 1.01%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 1.01%   |
| Samsung SCX-6545 Series                 | 1         | 1.01%   |
| Samsung SCX-4300 Series                 | 1         | 1.01%   |
| Samsung SCX-4200 series                 | 1         | 1.01%   |
| Samsung SCX-3400 Series                 | 1         | 1.01%   |
| Samsung ML-3050/ML-3051 Laser Printer   | 1         | 1.01%   |
| Samsung ML-2540 Series Laser Printer    | 1         | 1.01%   |
| Samsung M2020 Series                    | 1         | 1.01%   |
| MIIIW MW Keyboard Air Mini              | 1         | 1.01%   |
| Lexmark International Lexmark E352dn    | 1         | 1.01%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 11        | 61.11%  |
| Seiko Epson                 | 2         | 11.11%  |
| Plustek                     | 2         | 11.11%  |
| Ultima Electronics          | 1         | 5.56%   |
| Microtek International      | 1         | 5.56%   |
| Acer Peripherals (now BenQ) | 1         | 5.56%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 3         | 16.67%  |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 11.11%  |
| Canon CanoScan LiDE 120                                  | 2         | 11.11%  |
| Canon CanoScan LiDE 110                                  | 2         | 11.11%  |
| Ultima Artec E+ 48U                                      | 1         | 5.56%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 1         | 5.56%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 5.56%   |
| Plustek OpticSlim 1200 Scanner                           | 1         | 5.56%   |
| Plustek OpticPro 1248U Scanner #2                        | 1         | 5.56%   |
| Microtek International USB1200 Scanner                   | 1         | 5.56%   |
| Canon CanoScan N1240U/LiDE 30                            | 1         | 5.56%   |
| Canon CanoScan LIDE 25                                   | 1         | 5.56%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 1         | 5.56%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 506       | 22.2%   |
| Microdia                               | 237       | 10.4%   |
| IMC Networks                           | 225       | 9.87%   |
| Realtek Semiconductor                  | 191       | 8.38%   |
| Acer                                   | 164       | 7.2%    |
| Sunplus Innovation Technology          | 118       | 5.18%   |
| Suyin                                  | 97        | 4.26%   |
| Quanta                                 | 97        | 4.26%   |
| Logitech                               | 85        | 3.73%   |
| Cheng Uei Precision Industry (Foxlink) | 79        | 3.47%   |
| Syntek                                 | 69        | 3.03%   |
| Silicon Motion                         | 49        | 2.15%   |
| Lite-On Technology                     | 49        | 2.15%   |
| Creative Technology                    | 33        | 1.45%   |
| Ricoh                                  | 26        | 1.14%   |
| Apple                                  | 24        | 1.05%   |
| Lenovo                                 | 23        | 1.01%   |
| Alcor Micro                            | 23        | 1.01%   |
| Z-Star Microelectronics                | 19        | 0.83%   |
| Microsoft                              | 17        | 0.75%   |
| Samsung Electronics                    | 16        | 0.7%    |
| Luxvisions Innotech Limited            | 16        | 0.7%    |
| DigiTech                               | 11        | 0.48%   |
| Primax Electronics                     | 9         | 0.39%   |
| Intel                                  | 8         | 0.35%   |
| Generalplus Technology                 | 8         | 0.35%   |
| ALi                                    | 8         | 0.35%   |
| Cubeternet                             | 7         | 0.31%   |
| Hewlett-Packard                        | 6         | 0.26%   |
| DJJHFA1BIF5595                         | 5         | 0.22%   |
| Sonix Technology                       | 4         | 0.18%   |
| LG Electronics                         | 4         | 0.18%   |
| GEMBIRD                                | 4         | 0.18%   |
| Aveo Technology                        | 4         | 0.18%   |
| Xiongmai                               | 3         | 0.13%   |
| Trust                                  | 3         | 0.13%   |
| Sunplus Technology                     | 3         | 0.13%   |
| Jieli Technology                       | 3         | 0.13%   |
| Importek                               | 3         | 0.13%   |
| Valve Software                         | 2         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 102       | 4.46%   |
| Microdia Integrated_Webcam_HD            | 78        | 3.41%   |
| Realtek Integrated_Webcam_HD             | 71        | 3.1%    |
| IMC Networks Integrated Camera           | 60        | 2.62%   |
| IMC Networks USB2.0 HD UVC WebCam        | 55        | 2.4%    |
| Sunplus Integrated_Webcam_HD             | 51        | 2.23%   |
| Acer Integrated Camera                   | 40        | 1.75%   |
| Chicony Lenovo EasyCamera                | 39        | 1.7%    |
| Acer Lenovo EasyCamera                   | 36        | 1.57%   |
| Suyin Integrated_Webcam_HD               | 35        | 1.53%   |
| Microdia Integrated Webcam               | 35        | 1.53%   |
| Chicony HD WebCam                        | 34        | 1.49%   |
| Syntek Lenovo EasyCamera                 | 29        | 1.27%   |
| Realtek Lenovo EasyCamera                | 25        | 1.09%   |
| Syntek Integrated Camera                 | 23        | 1.01%   |
| Chicony USB2.0 HD UVC WebCam             | 23        | 1.01%   |
| Realtek USB Camera                       | 22        | 0.96%   |
| Lite-On Integrated Camera                | 21        | 0.92%   |
| Quanta HP TrueVision HD Camera           | 20        | 0.87%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 20        | 0.87%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 18        | 0.79%   |
| Logitech Webcam C270                     | 18        | 0.79%   |
| Acer Lenovo Integrated Webcam            | 18        | 0.79%   |
| Creative Live! Cam Sync HD [VF0770]      | 17        | 0.74%   |
| Chicony HP HD Camera                     | 17        | 0.74%   |
| Quanta HD User Facing                    | 16        | 0.7%    |
| Microdia Laptop_Integrated_Webcam_HD     | 16        | 0.7%    |
| IMC Networks Integrated Webcam           | 16        | 0.7%    |
| Chicony USB 2.0 Camera                   | 16        | 0.7%    |
| Samsung Galaxy A5 (MTP)                  | 15        | 0.66%   |
| Microdia USB 2.0 Camera                  | 15        | 0.66%   |
| Chicony USB2.0 VGA UVC WebCam            | 15        | 0.66%   |
| Acer SunplusIT Integrated Camera         | 15        | 0.66%   |
| Realtek Integrated Webcam                | 13        | 0.57%   |
| Microdia Sonix USB 2.0 Camera            | 13        | 0.57%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 13        | 0.57%   |
| Chicony Integrated Camera (1280x720@30)  | 12        | 0.52%   |
| Chicony HP HD Webcam [Fixed]             | 12        | 0.52%   |
| Chicony EasyCamera                       | 12        | 0.52%   |
| Sunplus HD WebCam                        | 11        | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 167       | 36.38%  |
| Synaptics                  | 114       | 24.84%  |
| AuthenTec                  | 53        | 11.55%  |
| Shenzhen Goodix Technology | 52        | 11.33%  |
| Upek                       | 32        | 6.97%   |
| LighTuning Technology      | 15        | 3.27%   |
| STMicroelectronics         | 13        | 2.83%   |
| Elan Microelectronics      | 13        | 2.83%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 40        | 8.71%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 32        | 6.97%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 31        | 6.75%   |
| Shenzhen Goodix  Fingerprint Device                                        | 28        | 6.1%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 23        | 5.01%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 4.58%   |
| AuthenTec AES2810                                                          | 21        | 4.58%   |
| Shenzhen Goodix Fingerprint Reader                                         | 19        | 4.14%   |
| Unknown                                                                    | 19        | 4.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 18        | 3.92%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 17        | 3.7%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 3.05%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 13        | 2.83%   |
| STMicroelectronics Fingerprint Reader                                      | 13        | 2.83%   |
| Validity Sensors VFS491                                                    | 12        | 2.61%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 11        | 2.4%    |
| Synaptics  WBDI                                                            | 9         | 1.96%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 8         | 1.74%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 1.74%   |
| Elan ELAN:Fingerprint                                                      | 8         | 1.74%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 1.53%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 1.53%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.53%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 1.53%   |
| AuthenTec AES1600                                                          | 7         | 1.53%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.31%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 1.09%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.09%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.09%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.87%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.87%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 0.87%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.87%   |
| Elan ELAN:ARM-M4                                                           | 4         | 0.87%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.87%   |
| Synaptics WBDI Device                                                      | 3         | 0.65%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.65%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.44%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.22%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.22%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 185       | 54.09%  |
| Alcor Micro               | 71        | 20.76%  |
| O2 Micro                  | 37        | 10.82%  |
| Upek                      | 18        | 5.26%   |
| Lenovo                    | 18        | 5.26%   |
| Gemalto (was Gemplus)     | 5         | 1.46%   |
| OmniKey                   | 2         | 0.58%   |
| Advanced Card Systems     | 2         | 0.58%   |
| SCM Microsystems          | 1         | 0.29%   |
| Clay Logic                | 1         | 0.29%   |
| Cherry                    | 1         | 0.29%   |
| Aladdin Knowledge Systems | 1         | 0.29%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 68        | 19.88%  |
| Broadcom BCM5880 Secure Applications Processor                               | 60        | 17.54%  |
| Broadcom 5880                                                                | 47        | 13.74%  |
| Broadcom 58200                                                               | 43        | 12.57%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 34        | 9.94%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 30        | 8.77%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 18        | 5.26%   |
| Lenovo Integrated Smart Card Reader                                          | 18        | 5.26%   |
| O2 Micro Oz776 SmartCard Reader                                              | 7         | 2.05%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.88%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.58%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.58%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.58%   |
| SCM Microsystems SCR333 SmartCard Reader                                     | 1         | 0.29%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.29%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.29%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.29%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.29%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.29%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.29%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.29%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2845      | 68.85%  |
| 1     | 1021      | 24.71%  |
| 2     | 222       | 5.37%   |
| 3     | 33        | 0.8%    |
| 4     | 5         | 0.12%   |
| 7     | 3         | 0.07%   |
| 5     | 2         | 0.05%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 453       | 29.15%  |
| Graphics card            | 351       | 22.59%  |
| Chipcard                 | 310       | 19.95%  |
| Net/wireless             | 132       | 8.49%   |
| Multimedia controller    | 50        | 3.22%   |
| Storage                  | 45        | 2.9%    |
| Bluetooth                | 42        | 2.7%    |
| Communication controller | 40        | 2.57%   |
| Camera                   | 30        | 1.93%   |
| Sound                    | 20        | 1.29%   |
| Unassigned class         | 19        | 1.22%   |
| Card reader              | 16        | 1.03%   |
| Modem                    | 8         | 0.51%   |
| Net/ethernet             | 7         | 0.45%   |
| Firewire controller      | 7         | 0.45%   |
| Network                  | 6         | 0.39%   |
| Dvb card                 | 5         | 0.32%   |
| Storage/raid             | 4         | 0.26%   |
| Storage/ide              | 4         | 0.26%   |
| Flash memory             | 3         | 0.19%   |
| Wireless                 | 1         | 0.06%   |
| Tv card                  | 1         | 0.06%   |

