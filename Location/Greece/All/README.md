Linux in Greece - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Greece.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Greece/Desktop/README.md) and [notebooks](/Location/Greece/Notebook/README.md).

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

Total: 1948

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 339A                        | Desktop     | [2ecbd957da](https://linux-hardware.org/?probe=2ecbd957da) | Aug 11, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [ba03034ac5](https://linux-hardware.org/?probe=ba03034ac5) | Aug 10, 2023 |
| Dell          | XPS L421X                   | Notebook    | [ba412a439b](https://linux-hardware.org/?probe=ba412a439b) | Aug 10, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | Notebook    | [55e9e43f37](https://linux-hardware.org/?probe=55e9e43f37) | Aug 06, 2023 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [9db6bfdcfa](https://linux-hardware.org/?probe=9db6bfdcfa) | Aug 05, 2023 |
| HP            | ProBook 6540b               | Notebook    | [6ae3405ec5](https://linux-hardware.org/?probe=6ae3405ec5) | Aug 03, 2023 |
| HP            | Pavilion g7                 | Notebook    | [882d2d9a16](https://linux-hardware.org/?probe=882d2d9a16) | Aug 02, 2023 |
| HP            | 339A                        | Desktop     | [782fefbccd](https://linux-hardware.org/?probe=782fefbccd) | Aug 01, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [e3999da810](https://linux-hardware.org/?probe=e3999da810) | Jul 31, 2023 |
| Dell          | Latitude 5340               | Notebook    | [5ab5c25167](https://linux-hardware.org/?probe=5ab5c25167) | Jul 28, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [2c2dfaa670](https://linux-hardware.org/?probe=2c2dfaa670) | Jul 27, 2023 |
| HP            | Pavilion dv6                | Notebook    | [1ed1c25f7e](https://linux-hardware.org/?probe=1ed1c25f7e) | Jul 26, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [88dd1326f2](https://linux-hardware.org/?probe=88dd1326f2) | Jul 26, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [295d363d3e](https://linux-hardware.org/?probe=295d363d3e) | Jul 24, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c2e02d1490](https://linux-hardware.org/?probe=c2e02d1490) | Jul 24, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [719e8b9ad3](https://linux-hardware.org/?probe=719e8b9ad3) | Jul 22, 2023 |
| Dell          | Vostro 3578                 | Notebook    | [bd32828bf5](https://linux-hardware.org/?probe=bd32828bf5) | Jul 22, 2023 |
| HP            | Presario CQ57               | Notebook    | [2c1bcfe898](https://linux-hardware.org/?probe=2c1bcfe898) | Jul 22, 2023 |
| Dell          | Latitude 3510               | Notebook    | [e1eb8b885c](https://linux-hardware.org/?probe=e1eb8b885c) | Jul 21, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [a9214c4672](https://linux-hardware.org/?probe=a9214c4672) | Jul 21, 2023 |
| Dell          | Latitude 5530               | Notebook    | [235731a6f1](https://linux-hardware.org/?probe=235731a6f1) | Jul 20, 2023 |
| HP            | ProBook 6540b               | Notebook    | [ec232bc3fa](https://linux-hardware.org/?probe=ec232bc3fa) | Jul 20, 2023 |
| Dell          | Latitude 5310               | Notebook    | [5b81040709](https://linux-hardware.org/?probe=5b81040709) | Jul 20, 2023 |
| HP            | Pavilion 17                 | Notebook    | [bf76e4c333](https://linux-hardware.org/?probe=bf76e4c333) | Jul 19, 2023 |
| Acer          | Aspire One 753              | Notebook    | [f2b71747bc](https://linux-hardware.org/?probe=f2b71747bc) | Jul 18, 2023 |
| Acer          | Aspire One 753              | Notebook    | [53d0821b75](https://linux-hardware.org/?probe=53d0821b75) | Jul 18, 2023 |
| Google        | Lick                        | Notebook    | [be8f8d1fd5](https://linux-hardware.org/?probe=be8f8d1fd5) | Jul 17, 2023 |
| Dell          | Precision 5510              | Notebook    | [ff4ea6ba94](https://linux-hardware.org/?probe=ff4ea6ba94) | Jul 17, 2023 |
| Dell          | Latitude 5530               | Notebook    | [37681b3327](https://linux-hardware.org/?probe=37681b3327) | Jul 17, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [8464b9ef50](https://linux-hardware.org/?probe=8464b9ef50) | Jul 17, 2023 |
| Google        | Lick                        | Notebook    | [177ed7483f](https://linux-hardware.org/?probe=177ed7483f) | Jul 16, 2023 |
| Dell          | Precision 3571              | Notebook    | [2123567cb0](https://linux-hardware.org/?probe=2123567cb0) | Jul 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9287464155](https://linux-hardware.org/?probe=9287464155) | Jul 16, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [a2f77869ad](https://linux-hardware.org/?probe=a2f77869ad) | Jul 14, 2023 |
| Dell          | Inspiron 5737               | Notebook    | [fa1cb6ffb8](https://linux-hardware.org/?probe=fa1cb6ffb8) | Jul 12, 2023 |
| Sony          | VPCEB1S1E                   | Notebook    | [4866baed77](https://linux-hardware.org/?probe=4866baed77) | Jul 10, 2023 |
| Fujitsu       | LIFEBOOK U727               | Notebook    | [ce095d85c9](https://linux-hardware.org/?probe=ce095d85c9) | Jul 09, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [de87cf7e95](https://linux-hardware.org/?probe=de87cf7e95) | Jul 07, 2023 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [a9f169ce16](https://linux-hardware.org/?probe=a9f169ce16) | Jul 05, 2023 |
| Gigabyte      | B150M-DS3H-CF               | Desktop     | [1a3056376b](https://linux-hardware.org/?probe=1a3056376b) | Jul 02, 2023 |
| Gigabyte      | B150M-DS3H-CF               | Desktop     | [648742f6d3](https://linux-hardware.org/?probe=648742f6d3) | Jul 02, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [c85bb607d4](https://linux-hardware.org/?probe=c85bb607d4) | Jul 02, 2023 |
| HP            | Pavilion 15                 | Notebook    | [2febd058ee](https://linux-hardware.org/?probe=2febd058ee) | Jul 02, 2023 |
| ASUSTek       | N752VX                      | Notebook    | [d4fd40a9f3](https://linux-hardware.org/?probe=d4fd40a9f3) | Jul 01, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [4557637b8a](https://linux-hardware.org/?probe=4557637b8a) | Jun 26, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [1a5d46559c](https://linux-hardware.org/?probe=1a5d46559c) | Jun 25, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [338b2e7db3](https://linux-hardware.org/?probe=338b2e7db3) | Jun 25, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [589dd91af9](https://linux-hardware.org/?probe=589dd91af9) | Jun 25, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [5b780b9ebd](https://linux-hardware.org/?probe=5b780b9ebd) | Jun 24, 2023 |
| Gigabyte      | EP45C-DS3R                  | Desktop     | [655d9d950d](https://linux-hardware.org/?probe=655d9d950d) | Jun 24, 2023 |
| Dell          | Latitude E5570              | Notebook    | [9f935b7571](https://linux-hardware.org/?probe=9f935b7571) | Jun 20, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [e1c2d99faa](https://linux-hardware.org/?probe=e1c2d99faa) | Jun 19, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [7fe527c4fa](https://linux-hardware.org/?probe=7fe527c4fa) | Jun 19, 2023 |
| Hampoo        | Cherry Trail CR Hampoo_r... | Notebook    | [e4a3b14c4c](https://linux-hardware.org/?probe=e4a3b14c4c) | Jun 18, 2023 |
| HP            | Pavilion dv6                | Notebook    | [f47b055767](https://linux-hardware.org/?probe=f47b055767) | Jun 18, 2023 |
| Hampoo        | Cherry Trail CR Hampoo_r... | Notebook    | [68f03108e5](https://linux-hardware.org/?probe=68f03108e5) | Jun 18, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [98c46aeea5](https://linux-hardware.org/?probe=98c46aeea5) | Jun 17, 2023 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [c5cea5f197](https://linux-hardware.org/?probe=c5cea5f197) | Jun 16, 2023 |
| MSI           | MS-7176                     | Desktop     | [952dc4b788](https://linux-hardware.org/?probe=952dc4b788) | Jun 16, 2023 |
| Lenovo        | IdeaPad N580 20182          | Notebook    | [93cb5afc77](https://linux-hardware.org/?probe=93cb5afc77) | Jun 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [ab92fe4791](https://linux-hardware.org/?probe=ab92fe4791) | Jun 13, 2023 |
| Lenovo        | ThinkPad X250 20CLS45J00    | Notebook    | [64bbeab44d](https://linux-hardware.org/?probe=64bbeab44d) | Jun 12, 2023 |
| Lenovo        | ThinkPad X250 20CLS45J00    | Notebook    | [a08326363f](https://linux-hardware.org/?probe=a08326363f) | Jun 12, 2023 |
| Google        | Argo_AR_11 PROD             | Server      | [7a931b2f8d](https://linux-hardware.org/?probe=7a931b2f8d) | Jun 11, 2023 |
| Lenovo        | IdeaPad N580 20182          | Notebook    | [8990fd0b51](https://linux-hardware.org/?probe=8990fd0b51) | Jun 10, 2023 |
| Dell          | 0K83V0 A00                  | Desktop     | [fc7fa0850a](https://linux-hardware.org/?probe=fc7fa0850a) | Jun 08, 2023 |
| Dell          | Inspiron 5565               | Notebook    | [91fc26029a](https://linux-hardware.org/?probe=91fc26029a) | Jun 07, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [827f6ecac2](https://linux-hardware.org/?probe=827f6ecac2) | Jun 07, 2023 |
| ASRock        | Z790 Taichi Carrara         | Desktop     | [bdea2092aa](https://linux-hardware.org/?probe=bdea2092aa) | Jun 06, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [558e181232](https://linux-hardware.org/?probe=558e181232) | Jun 05, 2023 |
| Unknown       | Intel X79                   | Desktop     | [0e2e65a79e](https://linux-hardware.org/?probe=0e2e65a79e) | Jun 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [91d11f8da1](https://linux-hardware.org/?probe=91d11f8da1) | Jun 04, 2023 |
| Dell          | 0DKKCF A00                  | All in one  | [48c5e3c802](https://linux-hardware.org/?probe=48c5e3c802) | Jun 03, 2023 |
| Dell          | Vostro 3520                 | Notebook    | [473145db98](https://linux-hardware.org/?probe=473145db98) | Jun 01, 2023 |
| Dell          | Vostro 3520                 | Notebook    | [088f4d3536](https://linux-hardware.org/?probe=088f4d3536) | Jun 01, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [f168bc9d53](https://linux-hardware.org/?probe=f168bc9d53) | May 31, 2023 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [b79113b0b5](https://linux-hardware.org/?probe=b79113b0b5) | May 30, 2023 |
| Dell          | G15 5525                    | Notebook    | [f7e5d0ae57](https://linux-hardware.org/?probe=f7e5d0ae57) | May 30, 2023 |
| Dell          | Vostro 3520                 | Notebook    | [4c50880385](https://linux-hardware.org/?probe=4c50880385) | May 30, 2023 |
| Fujitsu       | D3402-A1 S26361-D3402-A1    | Desktop     | [0ae3ea958a](https://linux-hardware.org/?probe=0ae3ea958a) | May 29, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [bb842bc2d8](https://linux-hardware.org/?probe=bb842bc2d8) | May 28, 2023 |
| Lenovo        | G700 20251                  | Notebook    | [8ba2c6e5ed](https://linux-hardware.org/?probe=8ba2c6e5ed) | May 26, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [1c67718bdb](https://linux-hardware.org/?probe=1c67718bdb) | May 26, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [08eec5e6ca](https://linux-hardware.org/?probe=08eec5e6ca) | May 26, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [4c22ef876f](https://linux-hardware.org/?probe=4c22ef876f) | May 26, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [b6d4eff333](https://linux-hardware.org/?probe=b6d4eff333) | May 26, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [baae1e4c8b](https://linux-hardware.org/?probe=baae1e4c8b) | May 25, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [945b06d022](https://linux-hardware.org/?probe=945b06d022) | May 25, 2023 |
| Compal        | JHL90 REFERENCE             | Notebook    | [0c115d29f3](https://linux-hardware.org/?probe=0c115d29f3) | May 25, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [eaa5b878d3](https://linux-hardware.org/?probe=eaa5b878d3) | May 23, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [cf10c1fb13](https://linux-hardware.org/?probe=cf10c1fb13) | May 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [1c178d1658](https://linux-hardware.org/?probe=1c178d1658) | May 21, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [f0eaf024c8](https://linux-hardware.org/?probe=f0eaf024c8) | May 20, 2023 |
| NEC Comput... | PC-VK26TXZCM                | Notebook    | [064b725160](https://linux-hardware.org/?probe=064b725160) | May 19, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [82dca1cbb8](https://linux-hardware.org/?probe=82dca1cbb8) | May 18, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [09f9f2e231](https://linux-hardware.org/?probe=09f9f2e231) | May 17, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [c8250719d9](https://linux-hardware.org/?probe=c8250719d9) | May 16, 2023 |
| HP            | Pavilion g6                 | Notebook    | [c94e96b76a](https://linux-hardware.org/?probe=c94e96b76a) | May 15, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [4ef8752290](https://linux-hardware.org/?probe=4ef8752290) | May 15, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [b5c9664f50](https://linux-hardware.org/?probe=b5c9664f50) | May 15, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [e9ce1757ae](https://linux-hardware.org/?probe=e9ce1757ae) | May 14, 2023 |
| Dell          | Latitude 7410               | Notebook    | [542e1d7f7b](https://linux-hardware.org/?probe=542e1d7f7b) | May 14, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [53b6692944](https://linux-hardware.org/?probe=53b6692944) | May 13, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [297921aabf](https://linux-hardware.org/?probe=297921aabf) | May 13, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [e13fe43842](https://linux-hardware.org/?probe=e13fe43842) | May 12, 2023 |
| Acer          | Aspire 3935                 | Notebook    | [39cbd19b39](https://linux-hardware.org/?probe=39cbd19b39) | May 10, 2023 |
| HP            | Pavilion dv6                | Notebook    | [735f9b7ee4](https://linux-hardware.org/?probe=735f9b7ee4) | May 10, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [bcb5863b0a](https://linux-hardware.org/?probe=bcb5863b0a) | May 09, 2023 |
| ASUSTek       | B85M-GAMER                  | Desktop     | [2f0a5430a3](https://linux-hardware.org/?probe=2f0a5430a3) | May 09, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [229861cf59](https://linux-hardware.org/?probe=229861cf59) | May 09, 2023 |
| HP            | Pavilion dv7                | Notebook    | [1d9699c86f](https://linux-hardware.org/?probe=1d9699c86f) | May 09, 2023 |
| Gigabyte      | Z690 AERO G                 | Desktop     | [7673380766](https://linux-hardware.org/?probe=7673380766) | May 07, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [00794346db](https://linux-hardware.org/?probe=00794346db) | May 06, 2023 |
| ASRock        | G41C-GS                     | Desktop     | [03076cae9a](https://linux-hardware.org/?probe=03076cae9a) | May 06, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [60c407b4e4](https://linux-hardware.org/?probe=60c407b4e4) | May 05, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [c8347acd5d](https://linux-hardware.org/?probe=c8347acd5d) | May 05, 2023 |
| ASUSTek       | P5KPL-AM/PS                 | Desktop     | [a5c1634444](https://linux-hardware.org/?probe=a5c1634444) | May 05, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [169cbbf5a9](https://linux-hardware.org/?probe=169cbbf5a9) | May 03, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [83abb6a8e0](https://linux-hardware.org/?probe=83abb6a8e0) | May 01, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [910f08075b](https://linux-hardware.org/?probe=910f08075b) | Apr 30, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [32f6248b20](https://linux-hardware.org/?probe=32f6248b20) | Apr 29, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [9f604fc816](https://linux-hardware.org/?probe=9f604fc816) | Apr 29, 2023 |
| HP            | 8054                        | Desktop     | [81a57b4a2f](https://linux-hardware.org/?probe=81a57b4a2f) | Apr 29, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [c1e0f0fa03](https://linux-hardware.org/?probe=c1e0f0fa03) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [4de963cbc6](https://linux-hardware.org/?probe=4de963cbc6) | Apr 28, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [7e7da68aa3](https://linux-hardware.org/?probe=7e7da68aa3) | Apr 28, 2023 |
| Pegatron      | A15                         | Notebook    | [e9de945dce](https://linux-hardware.org/?probe=e9de945dce) | Apr 28, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [012329ee1f](https://linux-hardware.org/?probe=012329ee1f) | Apr 27, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [f428173506](https://linux-hardware.org/?probe=f428173506) | Apr 27, 2023 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [3b263c29fc](https://linux-hardware.org/?probe=3b263c29fc) | Apr 26, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [ef2dfc5068](https://linux-hardware.org/?probe=ef2dfc5068) | Apr 25, 2023 |
| Dell          | Latitude 5490               | Notebook    | [32ddaf898c](https://linux-hardware.org/?probe=32ddaf898c) | Apr 25, 2023 |
| MSI           | H81M PRO-VD                 | Desktop     | [00ade274cb](https://linux-hardware.org/?probe=00ade274cb) | Apr 24, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [e4064abe78](https://linux-hardware.org/?probe=e4064abe78) | Apr 24, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [17ae2e245a](https://linux-hardware.org/?probe=17ae2e245a) | Apr 22, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [5b14b21a19](https://linux-hardware.org/?probe=5b14b21a19) | Apr 21, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f1193f152e](https://linux-hardware.org/?probe=f1193f152e) | Apr 20, 2023 |
| MSI           | MS-7235                     | Desktop     | [efaeac524b](https://linux-hardware.org/?probe=efaeac524b) | Apr 18, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [4abccb30eb](https://linux-hardware.org/?probe=4abccb30eb) | Apr 18, 2023 |
| Dell          | Inspiron 5406 2n1           | Convertible | [34204ad034](https://linux-hardware.org/?probe=34204ad034) | Apr 18, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [329811ff90](https://linux-hardware.org/?probe=329811ff90) | Apr 18, 2023 |
| Sony          | VPCCW1S1E                   | Notebook    | [49dc80d94c](https://linux-hardware.org/?probe=49dc80d94c) | Apr 18, 2023 |
| Dell          | 0K83V0 A00                  | Desktop     | [9e0514e439](https://linux-hardware.org/?probe=9e0514e439) | Apr 17, 2023 |
| Pegatron      | A15                         | Notebook    | [7532cb82f5](https://linux-hardware.org/?probe=7532cb82f5) | Apr 16, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [ff2ad3337b](https://linux-hardware.org/?probe=ff2ad3337b) | Apr 15, 2023 |
| HP            | 3048h                       | Desktop     | [c771c0b0a7](https://linux-hardware.org/?probe=c771c0b0a7) | Apr 15, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [f604f6e212](https://linux-hardware.org/?probe=f604f6e212) | Apr 14, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [e48eeac368](https://linux-hardware.org/?probe=e48eeac368) | Apr 14, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [220e98667f](https://linux-hardware.org/?probe=220e98667f) | Apr 13, 2023 |
| Compal        | JHL90 REFERENCE             | Notebook    | [6d4660e720](https://linux-hardware.org/?probe=6d4660e720) | Apr 13, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [47f2ba894b](https://linux-hardware.org/?probe=47f2ba894b) | Apr 12, 2023 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [6026c92eaa](https://linux-hardware.org/?probe=6026c92eaa) | Apr 11, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [f12e2a4eb4](https://linux-hardware.org/?probe=f12e2a4eb4) | Apr 11, 2023 |
| Dell          | Latitude 3190               | Notebook    | [c2a70674ac](https://linux-hardware.org/?probe=c2a70674ac) | Apr 10, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [4a0aa9f6d0](https://linux-hardware.org/?probe=4a0aa9f6d0) | Apr 06, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [59e664cdc6](https://linux-hardware.org/?probe=59e664cdc6) | Apr 05, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [2e9904d939](https://linux-hardware.org/?probe=2e9904d939) | Apr 05, 2023 |
| Sony          | SVF1521A6EW                 | Notebook    | [af908681c7](https://linux-hardware.org/?probe=af908681c7) | Apr 04, 2023 |
| ASUSTek       | H110M-C                     | Desktop     | [5995f1c96e](https://linux-hardware.org/?probe=5995f1c96e) | Apr 03, 2023 |
| ASUSTek       | H110M-C                     | Desktop     | [b9f944ed6e](https://linux-hardware.org/?probe=b9f944ed6e) | Apr 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [fe4d7e3bd0](https://linux-hardware.org/?probe=fe4d7e3bd0) | Apr 02, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [059e2e5858](https://linux-hardware.org/?probe=059e2e5858) | Apr 01, 2023 |
| MSI           | H81M-P33                    | Desktop     | [e2442d5cac](https://linux-hardware.org/?probe=e2442d5cac) | Mar 31, 2023 |
| Notebook      | N150CU                      | Notebook    | [5da0df2cf0](https://linux-hardware.org/?probe=5da0df2cf0) | Mar 30, 2023 |
| Lenovo        | IdeaPadFlex 10 20324        | Notebook    | [40b3e68058](https://linux-hardware.org/?probe=40b3e68058) | Mar 29, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [a9a8004509](https://linux-hardware.org/?probe=a9a8004509) | Mar 29, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [1dccfbe9f4](https://linux-hardware.org/?probe=1dccfbe9f4) | Mar 29, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [01a09bc2c7](https://linux-hardware.org/?probe=01a09bc2c7) | Mar 27, 2023 |
| Lenovo        | IdeaPadFlex 10 20324        | Notebook    | [629579e7f2](https://linux-hardware.org/?probe=629579e7f2) | Mar 27, 2023 |
| Dell          | Inspiron 5406 2n1           | Convertible | [6184002a0c](https://linux-hardware.org/?probe=6184002a0c) | Mar 27, 2023 |
| ASUSTek       | P5KPL-AM/PS                 | Desktop     | [02d9269abc](https://linux-hardware.org/?probe=02d9269abc) | Mar 25, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [0d62bf0ea8](https://linux-hardware.org/?probe=0d62bf0ea8) | Mar 24, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [49bc505f3e](https://linux-hardware.org/?probe=49bc505f3e) | Mar 22, 2023 |
| Dell          | Latitude D530               | Notebook    | [92cf04edba](https://linux-hardware.org/?probe=92cf04edba) | Mar 21, 2023 |
| Gigabyte      | Z690 AERO G                 | Desktop     | [5e8f9cafe8](https://linux-hardware.org/?probe=5e8f9cafe8) | Mar 20, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [6247a0887f](https://linux-hardware.org/?probe=6247a0887f) | Mar 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e0a2f725e3](https://linux-hardware.org/?probe=e0a2f725e3) | Mar 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a77ff93d75](https://linux-hardware.org/?probe=a77ff93d75) | Mar 19, 2023 |
| Dell          | Latitude D530               | Notebook    | [c02081557b](https://linux-hardware.org/?probe=c02081557b) | Mar 18, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [338ab5a12e](https://linux-hardware.org/?probe=338ab5a12e) | Mar 17, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [7630033ffb](https://linux-hardware.org/?probe=7630033ffb) | Mar 15, 2023 |
| HP            | 805A                        | Desktop     | [5401e12606](https://linux-hardware.org/?probe=5401e12606) | Mar 14, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [e0cde77238](https://linux-hardware.org/?probe=e0cde77238) | Mar 14, 2023 |
| Lenovo        | Legion 5 15ARH7H 82RD       | Notebook    | [8dc295e39b](https://linux-hardware.org/?probe=8dc295e39b) | Mar 13, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9d5d0051ea](https://linux-hardware.org/?probe=9d5d0051ea) | Mar 13, 2023 |
| HP            | 3397                        | Desktop     | [0b74e11cdd](https://linux-hardware.org/?probe=0b74e11cdd) | Mar 12, 2023 |
| Lenovo        | ThinkPad X131e 3367AG9      | Notebook    | [0ff86711d1](https://linux-hardware.org/?probe=0ff86711d1) | Mar 12, 2023 |
| Compal        | JHL90 REFERENCE             | Notebook    | [702a5939d3](https://linux-hardware.org/?probe=702a5939d3) | Mar 12, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f70aee3bd6](https://linux-hardware.org/?probe=f70aee3bd6) | Mar 12, 2023 |
| HP            | Pavilion dv6                | Notebook    | [fca49aa86c](https://linux-hardware.org/?probe=fca49aa86c) | Mar 11, 2023 |
| MSI           | MS-7369                     | Desktop     | [7900c0d288](https://linux-hardware.org/?probe=7900c0d288) | Mar 11, 2023 |
| HP            | Notebook                    | Notebook    | [a51df23e13](https://linux-hardware.org/?probe=a51df23e13) | Mar 10, 2023 |
| HP            | Notebook                    | Notebook    | [6065109591](https://linux-hardware.org/?probe=6065109591) | Mar 10, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [d49d17f980](https://linux-hardware.org/?probe=d49d17f980) | Mar 10, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [135d0d7806](https://linux-hardware.org/?probe=135d0d7806) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [0093249208](https://linux-hardware.org/?probe=0093249208) | Mar 09, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [625691c490](https://linux-hardware.org/?probe=625691c490) | Mar 06, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [66b4f88fb7](https://linux-hardware.org/?probe=66b4f88fb7) | Mar 06, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [dbc8fc4b0d](https://linux-hardware.org/?probe=dbc8fc4b0d) | Mar 03, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [52b68672fc](https://linux-hardware.org/?probe=52b68672fc) | Mar 03, 2023 |
| MSI           | MS-7250                     | Desktop     | [5127fbfef5](https://linux-hardware.org/?probe=5127fbfef5) | Mar 02, 2023 |
| Dell          | Inspiron 3537               | Notebook    | [78f270b35a](https://linux-hardware.org/?probe=78f270b35a) | Feb 27, 2023 |
| Dell          | Inspiron 3537               | Notebook    | [bb1ffc3498](https://linux-hardware.org/?probe=bb1ffc3498) | Feb 27, 2023 |
| Gigabyte      | H87M-D3H                    | Desktop     | [3c50af5218](https://linux-hardware.org/?probe=3c50af5218) | Feb 27, 2023 |
| Lenovo        | ThinkPad P70 20ESS2J700     | Notebook    | [5a94dfa289](https://linux-hardware.org/?probe=5a94dfa289) | Feb 23, 2023 |
| Lenovo        | ThinkPad P70 20ESS2J700     | Notebook    | [869614f52a](https://linux-hardware.org/?probe=869614f52a) | Feb 23, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [becb5b0ba1](https://linux-hardware.org/?probe=becb5b0ba1) | Feb 22, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [da640089bd](https://linux-hardware.org/?probe=da640089bd) | Feb 21, 2023 |
| ASUSTek       | Z9PE-D8 WS                  | Server      | [12dbe88bab](https://linux-hardware.org/?probe=12dbe88bab) | Feb 20, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [82fd276e35](https://linux-hardware.org/?probe=82fd276e35) | Feb 19, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f8f6e2baea](https://linux-hardware.org/?probe=f8f6e2baea) | Feb 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [94ca7f3e34](https://linux-hardware.org/?probe=94ca7f3e34) | Feb 13, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [2573ae3149](https://linux-hardware.org/?probe=2573ae3149) | Feb 13, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [dcb95dba09](https://linux-hardware.org/?probe=dcb95dba09) | Feb 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [4c191fe9c2](https://linux-hardware.org/?probe=4c191fe9c2) | Feb 12, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [f6ed3beac1](https://linux-hardware.org/?probe=f6ed3beac1) | Feb 12, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [f61d527ad8](https://linux-hardware.org/?probe=f61d527ad8) | Feb 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [70643a8be9](https://linux-hardware.org/?probe=70643a8be9) | Feb 11, 2023 |
| IBM           | ThinkPad T43 18714AG        | Notebook    | [0730c9228d](https://linux-hardware.org/?probe=0730c9228d) | Feb 10, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [fdcac99f8d](https://linux-hardware.org/?probe=fdcac99f8d) | Feb 09, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [cdfbd3e72a](https://linux-hardware.org/?probe=cdfbd3e72a) | Feb 09, 2023 |
| Dell          | 03KWTV A02                  | Desktop     | [d1656ace32](https://linux-hardware.org/?probe=d1656ace32) | Feb 07, 2023 |
| Dell          | 03KWTV A02                  | Desktop     | [b3d00219b0](https://linux-hardware.org/?probe=b3d00219b0) | Feb 07, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [c222b31f37](https://linux-hardware.org/?probe=c222b31f37) | Feb 05, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [cbec062cd5](https://linux-hardware.org/?probe=cbec062cd5) | Feb 04, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [4af8568b93](https://linux-hardware.org/?probe=4af8568b93) | Feb 03, 2023 |
| HP            | 09F8h                       | Desktop     | [19339c9512](https://linux-hardware.org/?probe=19339c9512) | Feb 02, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [542173e9a2](https://linux-hardware.org/?probe=542173e9a2) | Feb 01, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [609fc1e9bb](https://linux-hardware.org/?probe=609fc1e9bb) | Jan 31, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [17a5588d06](https://linux-hardware.org/?probe=17a5588d06) | Jan 30, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [7bc88d72f0](https://linux-hardware.org/?probe=7bc88d72f0) | Jan 29, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [7bb7fe1a4f](https://linux-hardware.org/?probe=7bb7fe1a4f) | Jan 29, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [34fab6626e](https://linux-hardware.org/?probe=34fab6626e) | Jan 29, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [725c2a80f8](https://linux-hardware.org/?probe=725c2a80f8) | Jan 29, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [e6fedcdbb0](https://linux-hardware.org/?probe=e6fedcdbb0) | Jan 29, 2023 |
| Timi          | TM1703                      | Notebook    | [6bb85263a7](https://linux-hardware.org/?probe=6bb85263a7) | Jan 29, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [2aa7e026c4](https://linux-hardware.org/?probe=2aa7e026c4) | Jan 28, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [25ea296433](https://linux-hardware.org/?probe=25ea296433) | Jan 28, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [4910cfdfcd](https://linux-hardware.org/?probe=4910cfdfcd) | Jan 26, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [babedb5bbc](https://linux-hardware.org/?probe=babedb5bbc) | Jan 26, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [d5eae98224](https://linux-hardware.org/?probe=d5eae98224) | Jan 25, 2023 |
| Dell          | 0Y2K8N A00                  | Desktop     | [7f135346af](https://linux-hardware.org/?probe=7f135346af) | Jan 24, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | Desktop     | [10f14c4cbd](https://linux-hardware.org/?probe=10f14c4cbd) | Jan 23, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [821e7b4330](https://linux-hardware.org/?probe=821e7b4330) | Jan 22, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [eb59dcb924](https://linux-hardware.org/?probe=eb59dcb924) | Jan 22, 2023 |
| ASUSTek       | H61M-E                      | Desktop     | [eec3fddef5](https://linux-hardware.org/?probe=eec3fddef5) | Jan 22, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [dcc2324c10](https://linux-hardware.org/?probe=dcc2324c10) | Jan 22, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [4ff88ad220](https://linux-hardware.org/?probe=4ff88ad220) | Jan 22, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [22d9f43ef5](https://linux-hardware.org/?probe=22d9f43ef5) | Jan 21, 2023 |
| Valve         | Jupiter                     | Notebook    | [c87d98cab1](https://linux-hardware.org/?probe=c87d98cab1) | Jan 21, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [3eaeffde09](https://linux-hardware.org/?probe=3eaeffde09) | Jan 21, 2023 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | Desktop     | [f6b68c1767](https://linux-hardware.org/?probe=f6b68c1767) | Jan 19, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [80712a04ec](https://linux-hardware.org/?probe=80712a04ec) | Jan 18, 2023 |
| DFI           | LP UT X58                   | Desktop     | [e4545a522c](https://linux-hardware.org/?probe=e4545a522c) | Jan 18, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [aa93abde02](https://linux-hardware.org/?probe=aa93abde02) | Jan 17, 2023 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [de3dde0785](https://linux-hardware.org/?probe=de3dde0785) | Jan 17, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [fb0b3500da](https://linux-hardware.org/?probe=fb0b3500da) | Jan 15, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [d95820725a](https://linux-hardware.org/?probe=d95820725a) | Jan 15, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [903841df4f](https://linux-hardware.org/?probe=903841df4f) | Jan 14, 2023 |
| Lenovo        | G50-80 80L0                 | Notebook    | [08a00eef73](https://linux-hardware.org/?probe=08a00eef73) | Jan 14, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [0153a9926a](https://linux-hardware.org/?probe=0153a9926a) | Jan 13, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [0536f685a0](https://linux-hardware.org/?probe=0536f685a0) | Jan 13, 2023 |
| Gigabyte      | P55-US3L                    | Desktop     | [49e7dc9b0b](https://linux-hardware.org/?probe=49e7dc9b0b) | Jan 12, 2023 |
| Dell          | 0X9M3X A01                  | Desktop     | [0dd66e3ec4](https://linux-hardware.org/?probe=0dd66e3ec4) | Jan 12, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [239e9a9620](https://linux-hardware.org/?probe=239e9a9620) | Jan 12, 2023 |
| ASUSTek       | H61M-E                      | Desktop     | [38691cf2cc](https://linux-hardware.org/?probe=38691cf2cc) | Jan 11, 2023 |
| ECS           | G31T-M7                     | Desktop     | [161442b256](https://linux-hardware.org/?probe=161442b256) | Jan 10, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b1a7adefab](https://linux-hardware.org/?probe=b1a7adefab) | Jan 09, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [45e96fb346](https://linux-hardware.org/?probe=45e96fb346) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [f0aa7955bf](https://linux-hardware.org/?probe=f0aa7955bf) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [dc86d08ec3](https://linux-hardware.org/?probe=dc86d08ec3) | Jan 08, 2023 |
| MSI           | MS-7176                     | Desktop     | [809a107ec7](https://linux-hardware.org/?probe=809a107ec7) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [90dea18a86](https://linux-hardware.org/?probe=90dea18a86) | Jan 07, 2023 |
| Lenovo        | 3000 G530 444622G           | Notebook    | [7f1a67e904](https://linux-hardware.org/?probe=7f1a67e904) | Jan 07, 2023 |
| Gigabyte      | P55-USB3                    | Desktop     | [7c741c709a](https://linux-hardware.org/?probe=7c741c709a) | Jan 06, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [d069cbd46b](https://linux-hardware.org/?probe=d069cbd46b) | Jan 06, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [a2ec6616aa](https://linux-hardware.org/?probe=a2ec6616aa) | Jan 05, 2023 |
| Dell          | Inspiron 5406 2n1           | Convertible | [e780ec3e2a](https://linux-hardware.org/?probe=e780ec3e2a) | Jan 04, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [036ae164e8](https://linux-hardware.org/?probe=036ae164e8) | Jan 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6da268e22f](https://linux-hardware.org/?probe=6da268e22f) | Jan 03, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [40af3a30ca](https://linux-hardware.org/?probe=40af3a30ca) | Jan 03, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [66538edc62](https://linux-hardware.org/?probe=66538edc62) | Jan 02, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [5e52308407](https://linux-hardware.org/?probe=5e52308407) | Jan 02, 2023 |
| Sony          | VPCEL3S1E                   | Notebook    | [b57b0db39c](https://linux-hardware.org/?probe=b57b0db39c) | Jan 01, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [d7e15d4cb9](https://linux-hardware.org/?probe=d7e15d4cb9) | Jan 01, 2023 |
| Lenovo        | G40-30 80FY                 | Notebook    | [49bb82ca4b](https://linux-hardware.org/?probe=49bb82ca4b) | Dec 29, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [250104c525](https://linux-hardware.org/?probe=250104c525) | Dec 29, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [7f33845279](https://linux-hardware.org/?probe=7f33845279) | Dec 28, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [0dc3c192fd](https://linux-hardware.org/?probe=0dc3c192fd) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [71bccea2dc](https://linux-hardware.org/?probe=71bccea2dc) | Dec 28, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [82b72a9059](https://linux-hardware.org/?probe=82b72a9059) | Dec 27, 2022 |
| Dell          | 0J1C3P A00                  | Desktop     | [5da7f2d3a9](https://linux-hardware.org/?probe=5da7f2d3a9) | Dec 27, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [be1ace7f20](https://linux-hardware.org/?probe=be1ace7f20) | Dec 26, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [a43899d587](https://linux-hardware.org/?probe=a43899d587) | Dec 26, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [f497db99b3](https://linux-hardware.org/?probe=f497db99b3) | Dec 22, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [e48882ad67](https://linux-hardware.org/?probe=e48882ad67) | Dec 22, 2022 |
| HP            | Compaq Presario CQ61        | Notebook    | [a85b255853](https://linux-hardware.org/?probe=a85b255853) | Dec 22, 2022 |
| Dell          | 0J1C3P A00                  | Desktop     | [b65b20a073](https://linux-hardware.org/?probe=b65b20a073) | Dec 22, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [b1fb2ae232](https://linux-hardware.org/?probe=b1fb2ae232) | Dec 22, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [b5fcbb8663](https://linux-hardware.org/?probe=b5fcbb8663) | Dec 22, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [2489f01426](https://linux-hardware.org/?probe=2489f01426) | Dec 22, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [a50ec1e677](https://linux-hardware.org/?probe=a50ec1e677) | Dec 22, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c0f831d7a4](https://linux-hardware.org/?probe=c0f831d7a4) | Dec 22, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [07dc9b96c1](https://linux-hardware.org/?probe=07dc9b96c1) | Dec 21, 2022 |
| HP            | Unknown                     | Notebook    | [84f5cfd0cf](https://linux-hardware.org/?probe=84f5cfd0cf) | Dec 20, 2022 |
| Dell          | 0Y2K8N A00                  | Desktop     | [840fbab6e4](https://linux-hardware.org/?probe=840fbab6e4) | Dec 20, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [c168fe495f](https://linux-hardware.org/?probe=c168fe495f) | Dec 19, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1QX0... | Notebook    | [76771fa0aa](https://linux-hardware.org/?probe=76771fa0aa) | Dec 19, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | Desktop     | [c0b006673c](https://linux-hardware.org/?probe=c0b006673c) | Dec 18, 2022 |
| Acer          | AOA110                      | Notebook    | [560aa745c1](https://linux-hardware.org/?probe=560aa745c1) | Dec 14, 2022 |
| Lenovo        | ThinkPad Edge 0301GBG       | Notebook    | [a48e9c810c](https://linux-hardware.org/?probe=a48e9c810c) | Dec 14, 2022 |
| Lenovo        | IdeaPadFlex 10 20324        | Notebook    | [2499d7057e](https://linux-hardware.org/?probe=2499d7057e) | Dec 14, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [76e4dff90a](https://linux-hardware.org/?probe=76e4dff90a) | Dec 13, 2022 |
| Acer          | Aspire A515-44G             | Notebook    | [b85a211b25](https://linux-hardware.org/?probe=b85a211b25) | Dec 11, 2022 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [27fdfb657e](https://linux-hardware.org/?probe=27fdfb657e) | Dec 09, 2022 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [130d5ec0ea](https://linux-hardware.org/?probe=130d5ec0ea) | Dec 09, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [947534b3be](https://linux-hardware.org/?probe=947534b3be) | Dec 09, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [6e40fd6fd3](https://linux-hardware.org/?probe=6e40fd6fd3) | Dec 08, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [5d462a147a](https://linux-hardware.org/?probe=5d462a147a) | Dec 08, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [30457468d5](https://linux-hardware.org/?probe=30457468d5) | Dec 08, 2022 |
| Gigabyte      | GA-MA78GM-UD2H              | Desktop     | [415844c745](https://linux-hardware.org/?probe=415844c745) | Dec 08, 2022 |
| Gigabyte      | Z690 AERO G                 | Desktop     | [1bd5929c16](https://linux-hardware.org/?probe=1bd5929c16) | Dec 07, 2022 |
| MSI           | K9A2 Platinum               | Desktop     | [3ce727deb7](https://linux-hardware.org/?probe=3ce727deb7) | Dec 06, 2022 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [799470f1aa](https://linux-hardware.org/?probe=799470f1aa) | Dec 05, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [bb589ef99d](https://linux-hardware.org/?probe=bb589ef99d) | Dec 04, 2022 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [9289635a09](https://linux-hardware.org/?probe=9289635a09) | Dec 04, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [8d5c8e8f4d](https://linux-hardware.org/?probe=8d5c8e8f4d) | Dec 04, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [b43b3227de](https://linux-hardware.org/?probe=b43b3227de) | Dec 04, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | Desktop     | [5326fede0a](https://linux-hardware.org/?probe=5326fede0a) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b475911aaf](https://linux-hardware.org/?probe=b475911aaf) | Dec 03, 2022 |
| MSI           | K9A2 Platinum               | Desktop     | [79c823558a](https://linux-hardware.org/?probe=79c823558a) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [dd1874248c](https://linux-hardware.org/?probe=dd1874248c) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [eaf129dcfe](https://linux-hardware.org/?probe=eaf129dcfe) | Dec 02, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c0663aa7da](https://linux-hardware.org/?probe=c0663aa7da) | Dec 01, 2022 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [0cd3005f69](https://linux-hardware.org/?probe=0cd3005f69) | Dec 01, 2022 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [32b68762df](https://linux-hardware.org/?probe=32b68762df) | Nov 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [1a742c23df](https://linux-hardware.org/?probe=1a742c23df) | Nov 29, 2022 |
| HP            | Pavilion g6                 | Notebook    | [fefac15f4c](https://linux-hardware.org/?probe=fefac15f4c) | Nov 29, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [92afc95831](https://linux-hardware.org/?probe=92afc95831) | Nov 29, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d20243efed](https://linux-hardware.org/?probe=d20243efed) | Nov 28, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [dee60b9f35](https://linux-hardware.org/?probe=dee60b9f35) | Nov 28, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [1651962e5a](https://linux-hardware.org/?probe=1651962e5a) | Nov 28, 2022 |
| Clevo         | W55xEU                      | Notebook    | [5ed799ba64](https://linux-hardware.org/?probe=5ed799ba64) | Nov 28, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [fa5d6f5ca6](https://linux-hardware.org/?probe=fa5d6f5ca6) | Nov 28, 2022 |
| ASRock        | A88M-G                      | Desktop     | [323199813d](https://linux-hardware.org/?probe=323199813d) | Nov 27, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [df3e0f4b6c](https://linux-hardware.org/?probe=df3e0f4b6c) | Nov 26, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [82ee1f1740](https://linux-hardware.org/?probe=82ee1f1740) | Nov 26, 2022 |
| Lenovo        | ThinkCentre M58 6258AP4     | Desktop     | [54d4e3a0ae](https://linux-hardware.org/?probe=54d4e3a0ae) | Nov 26, 2022 |
| MSI           | GE62 2QC                    | Notebook    | [6bdf66b3b6](https://linux-hardware.org/?probe=6bdf66b3b6) | Nov 26, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9e22e08aa1](https://linux-hardware.org/?probe=9e22e08aa1) | Nov 25, 2022 |
| Dell          | Inspiron 3585               | Notebook    | [33485dee6d](https://linux-hardware.org/?probe=33485dee6d) | Nov 24, 2022 |
| Lenovo        | ThinkPad T580 20LAS01H00    | Notebook    | [3714ee0985](https://linux-hardware.org/?probe=3714ee0985) | Nov 24, 2022 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [f442c854fc](https://linux-hardware.org/?probe=f442c854fc) | Nov 23, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [a7f0189359](https://linux-hardware.org/?probe=a7f0189359) | Nov 23, 2022 |
| Dell          | Latitude D530               | Notebook    | [1403a8c938](https://linux-hardware.org/?probe=1403a8c938) | Nov 23, 2022 |
| HP            | Pavilion dv5                | Notebook    | [2a497ff54f](https://linux-hardware.org/?probe=2a497ff54f) | Nov 22, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [452417fa68](https://linux-hardware.org/?probe=452417fa68) | Nov 21, 2022 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [34e6521bc8](https://linux-hardware.org/?probe=34e6521bc8) | Nov 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [a1b9357fc6](https://linux-hardware.org/?probe=a1b9357fc6) | Nov 20, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [f7ebd3f633](https://linux-hardware.org/?probe=f7ebd3f633) | Nov 20, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [55bd7957b4](https://linux-hardware.org/?probe=55bd7957b4) | Nov 20, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [13f1a98b2c](https://linux-hardware.org/?probe=13f1a98b2c) | Nov 19, 2022 |
| Purism        | Librem 14                   | Notebook    | [cbc8bf9c96](https://linux-hardware.org/?probe=cbc8bf9c96) | Nov 19, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [4e04b1a51f](https://linux-hardware.org/?probe=4e04b1a51f) | Nov 19, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [c7fe31050b](https://linux-hardware.org/?probe=c7fe31050b) | Nov 19, 2022 |
| MSI           | H81M-P33                    | Desktop     | [a535339292](https://linux-hardware.org/?probe=a535339292) | Nov 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [814b5d3d2e](https://linux-hardware.org/?probe=814b5d3d2e) | Nov 17, 2022 |
| MSI           | H81M-P33                    | Desktop     | [246d594268](https://linux-hardware.org/?probe=246d594268) | Nov 16, 2022 |
| Acer          | Veriton N4630G              | Desktop     | [f4566a57a9](https://linux-hardware.org/?probe=f4566a57a9) | Nov 16, 2022 |
| HP            | 1495                        | Desktop     | [e29c423a17](https://linux-hardware.org/?probe=e29c423a17) | Nov 15, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [49ac6f08f9](https://linux-hardware.org/?probe=49ac6f08f9) | Nov 15, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [459c5879e6](https://linux-hardware.org/?probe=459c5879e6) | Nov 15, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [0007401910](https://linux-hardware.org/?probe=0007401910) | Nov 15, 2022 |
| Gigabyte      | Z690 AERO G                 | Desktop     | [311a20e88f](https://linux-hardware.org/?probe=311a20e88f) | Nov 13, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [961b736faa](https://linux-hardware.org/?probe=961b736faa) | Nov 13, 2022 |
| Fujitsu Si... | MS-7304VP-A13               | Desktop     | [69b1471202](https://linux-hardware.org/?probe=69b1471202) | Nov 12, 2022 |
| Sony          | VGN-CR31S_P                 | Notebook    | [ce99a279ca](https://linux-hardware.org/?probe=ce99a279ca) | Nov 11, 2022 |
| Lenovo        | ThinkPad T580 20LAS01H00    | Notebook    | [4d41c7236e](https://linux-hardware.org/?probe=4d41c7236e) | Nov 10, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [1cee1a7bd4](https://linux-hardware.org/?probe=1cee1a7bd4) | Nov 09, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [f49624457d](https://linux-hardware.org/?probe=f49624457d) | Nov 09, 2022 |
| MSI           | GE62 2QC                    | Notebook    | [513a929878](https://linux-hardware.org/?probe=513a929878) | Nov 08, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [7eca97a8ef](https://linux-hardware.org/?probe=7eca97a8ef) | Nov 08, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [a734aa34bf](https://linux-hardware.org/?probe=a734aa34bf) | Nov 07, 2022 |
| MSI           | GF65 Thin 10UE              | Notebook    | [ec09d9e22e](https://linux-hardware.org/?probe=ec09d9e22e) | Nov 06, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [605c859789](https://linux-hardware.org/?probe=605c859789) | Nov 06, 2022 |
| Insyde        | CherryTrail                 | Notebook    | [72fdd6a414](https://linux-hardware.org/?probe=72fdd6a414) | Nov 06, 2022 |
| Insyde        | CherryTrail                 | Notebook    | [1a65afa04d](https://linux-hardware.org/?probe=1a65afa04d) | Nov 06, 2022 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [6dd41b1571](https://linux-hardware.org/?probe=6dd41b1571) | Nov 06, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [07e637210f](https://linux-hardware.org/?probe=07e637210f) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge 0301GBG       | Notebook    | [8b50396928](https://linux-hardware.org/?probe=8b50396928) | Nov 04, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [fecd8f06dd](https://linux-hardware.org/?probe=fecd8f06dd) | Nov 02, 2022 |
| HP            | 18E7                        | Desktop     | [c0d5c58895](https://linux-hardware.org/?probe=c0d5c58895) | Nov 02, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [aad6abb936](https://linux-hardware.org/?probe=aad6abb936) | Nov 01, 2022 |
| Lenovo        | ThinkCentre M55E 898578G    | Desktop     | [d025c115d8](https://linux-hardware.org/?probe=d025c115d8) | Nov 01, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [9dea1bfedb](https://linux-hardware.org/?probe=9dea1bfedb) | Nov 01, 2022 |
| ASUSTek       | H110M-D                     | Desktop     | [248b9533a3](https://linux-hardware.org/?probe=248b9533a3) | Nov 01, 2022 |
| MSI           | MS-7309                     | Desktop     | [a6b1a7d329](https://linux-hardware.org/?probe=a6b1a7d329) | Oct 31, 2022 |
| MSI           | MS-7309                     | Desktop     | [3c519589ad](https://linux-hardware.org/?probe=3c519589ad) | Oct 30, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [ed46beadef](https://linux-hardware.org/?probe=ed46beadef) | Oct 30, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [05b5af2e63](https://linux-hardware.org/?probe=05b5af2e63) | Oct 29, 2022 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [00b65eaa83](https://linux-hardware.org/?probe=00b65eaa83) | Oct 29, 2022 |
| Gigabyte      | GA-MA790FX-DQ6              | Desktop     | [8ba31a020c](https://linux-hardware.org/?probe=8ba31a020c) | Oct 28, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [7870d9b047](https://linux-hardware.org/?probe=7870d9b047) | Oct 28, 2022 |
| Dell          | 0KRC95 A02                  | Desktop     | [8afc3da46d](https://linux-hardware.org/?probe=8afc3da46d) | Oct 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0e69671817](https://linux-hardware.org/?probe=0e69671817) | Oct 27, 2022 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [a3f55b1301](https://linux-hardware.org/?probe=a3f55b1301) | Oct 27, 2022 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [285a7d17e3](https://linux-hardware.org/?probe=285a7d17e3) | Oct 27, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [26e7b206ef](https://linux-hardware.org/?probe=26e7b206ef) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [c9393d50b5](https://linux-hardware.org/?probe=c9393d50b5) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [5199be5418](https://linux-hardware.org/?probe=5199be5418) | Oct 24, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [aaad9f52d4](https://linux-hardware.org/?probe=aaad9f52d4) | Oct 24, 2022 |
| Toshiba       | dynabook Satellite T87/8... | Notebook    | [10f344a2b3](https://linux-hardware.org/?probe=10f344a2b3) | Oct 24, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [ade038c388](https://linux-hardware.org/?probe=ade038c388) | Oct 24, 2022 |
| Toshiba       | Satellite C50-B             | Notebook    | [a9041efc75](https://linux-hardware.org/?probe=a9041efc75) | Oct 23, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [19c3c8e1f6](https://linux-hardware.org/?probe=19c3c8e1f6) | Oct 23, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [e5b07599e3](https://linux-hardware.org/?probe=e5b07599e3) | Oct 22, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [7abef2546e](https://linux-hardware.org/?probe=7abef2546e) | Oct 21, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f3890a4db1](https://linux-hardware.org/?probe=f3890a4db1) | Oct 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [de5adb6775](https://linux-hardware.org/?probe=de5adb6775) | Oct 21, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d135b32e8b](https://linux-hardware.org/?probe=d135b32e8b) | Oct 21, 2022 |
| HP            | Pavilion g7                 | Notebook    | [19048aa8f0](https://linux-hardware.org/?probe=19048aa8f0) | Oct 19, 2022 |
| HP            | 339A                        | Desktop     | [bea86a9671](https://linux-hardware.org/?probe=bea86a9671) | Oct 19, 2022 |
| Gigabyte      | P55-USB3                    | Desktop     | [6f441865a9](https://linux-hardware.org/?probe=6f441865a9) | Oct 19, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [91e4682f34](https://linux-hardware.org/?probe=91e4682f34) | Oct 17, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [23c855f88b](https://linux-hardware.org/?probe=23c855f88b) | Oct 17, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [ebe65ec5fa](https://linux-hardware.org/?probe=ebe65ec5fa) | Oct 17, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [6a3309f753](https://linux-hardware.org/?probe=6a3309f753) | Oct 14, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [7c58857f43](https://linux-hardware.org/?probe=7c58857f43) | Oct 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [943ee204e0](https://linux-hardware.org/?probe=943ee204e0) | Oct 10, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [a281cc47e5](https://linux-hardware.org/?probe=a281cc47e5) | Oct 10, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [c4e09cdf87](https://linux-hardware.org/?probe=c4e09cdf87) | Oct 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [d1c01a07a2](https://linux-hardware.org/?probe=d1c01a07a2) | Oct 08, 2022 |
| Gigabyte      | P55M-UD2                    | Desktop     | [e9627c4c34](https://linux-hardware.org/?probe=e9627c4c34) | Oct 07, 2022 |
| Dell          | Precision M6800             | Notebook    | [802d1dbfcd](https://linux-hardware.org/?probe=802d1dbfcd) | Oct 06, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [84ba2e1db1](https://linux-hardware.org/?probe=84ba2e1db1) | Oct 05, 2022 |
| Apple         | MacBookPro5,2               | Notebook    | [b0a6dc4162](https://linux-hardware.org/?probe=b0a6dc4162) | Oct 02, 2022 |
| Gigabyte      | P55-USB3                    | Desktop     | [adf7389f06](https://linux-hardware.org/?probe=adf7389f06) | Sep 30, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [4e0be93d26](https://linux-hardware.org/?probe=4e0be93d26) | Sep 29, 2022 |
| NU591         | 1.0                         | Desktop     | [6be5a78c90](https://linux-hardware.org/?probe=6be5a78c90) | Sep 27, 2022 |
| Purism        | Librem 14                   | Notebook    | [213731b934](https://linux-hardware.org/?probe=213731b934) | Sep 24, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [59c4a7e761](https://linux-hardware.org/?probe=59c4a7e761) | Sep 23, 2022 |
| HP            | Notebook                    | Notebook    | [18b9221add](https://linux-hardware.org/?probe=18b9221add) | Sep 22, 2022 |
| MSI           | H310M PRO-VH                | Desktop     | [c11e067cb5](https://linux-hardware.org/?probe=c11e067cb5) | Sep 22, 2022 |
| ASRock        | H81M-GL                     | Desktop     | [fe7e5bbc9c](https://linux-hardware.org/?probe=fe7e5bbc9c) | Sep 21, 2022 |
| NU591         | 1.0                         | Desktop     | [6e29ae977f](https://linux-hardware.org/?probe=6e29ae977f) | Sep 21, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a1f237c86a](https://linux-hardware.org/?probe=a1f237c86a) | Sep 20, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [5c9688dac8](https://linux-hardware.org/?probe=5c9688dac8) | Sep 19, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [57db36ecc9](https://linux-hardware.org/?probe=57db36ecc9) | Sep 19, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [fe48912653](https://linux-hardware.org/?probe=fe48912653) | Sep 15, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [bad5b6606e](https://linux-hardware.org/?probe=bad5b6606e) | Sep 14, 2022 |
| Lenovo        | ThinkPad X230 23252QG       | Notebook    | [4146ff55f9](https://linux-hardware.org/?probe=4146ff55f9) | Sep 10, 2022 |
| Toshiba       | Satellite C55-A-1JL         | Notebook    | [906f27f221](https://linux-hardware.org/?probe=906f27f221) | Sep 10, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7208ed4b83](https://linux-hardware.org/?probe=7208ed4b83) | Sep 10, 2022 |
| Toshiba       | Satellite C55-A-1JL         | Notebook    | [d229fa96f3](https://linux-hardware.org/?probe=d229fa96f3) | Sep 08, 2022 |
| Lenovo        | B5400 20278                 | Notebook    | [1c9d752f91](https://linux-hardware.org/?probe=1c9d752f91) | Sep 07, 2022 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [29eaefa02d](https://linux-hardware.org/?probe=29eaefa02d) | Sep 06, 2022 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [4ca1a490f8](https://linux-hardware.org/?probe=4ca1a490f8) | Sep 05, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [ea93dfd855](https://linux-hardware.org/?probe=ea93dfd855) | Sep 04, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [bd0c518002](https://linux-hardware.org/?probe=bd0c518002) | Sep 03, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [ba1027940d](https://linux-hardware.org/?probe=ba1027940d) | Sep 03, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [109d233976](https://linux-hardware.org/?probe=109d233976) | Sep 03, 2022 |
| HP            | 620                         | Notebook    | [34002dc814](https://linux-hardware.org/?probe=34002dc814) | Sep 02, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [5e98ea70fb](https://linux-hardware.org/?probe=5e98ea70fb) | Sep 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [4aa935356c](https://linux-hardware.org/?probe=4aa935356c) | Sep 02, 2022 |
| Toshiba       | Satellite C850D-118         | Notebook    | [1950f0aeac](https://linux-hardware.org/?probe=1950f0aeac) | Aug 31, 2022 |
| Toshiba       | Satellite C850D-118         | Notebook    | [07000e4194](https://linux-hardware.org/?probe=07000e4194) | Aug 30, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [61a4780992](https://linux-hardware.org/?probe=61a4780992) | Aug 30, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [8beed8e261](https://linux-hardware.org/?probe=8beed8e261) | Aug 30, 2022 |
| Dell          | G15 5515                    | Notebook    | [708ef41c02](https://linux-hardware.org/?probe=708ef41c02) | Aug 29, 2022 |
| Plaisio       | Turbo X                     | Notebook    | [ae92ead1ca](https://linux-hardware.org/?probe=ae92ead1ca) | Aug 29, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [7eaabdb9ca](https://linux-hardware.org/?probe=7eaabdb9ca) | Aug 27, 2022 |
| HP            | 339A                        | Desktop     | [961ac650aa](https://linux-hardware.org/?probe=961ac650aa) | Aug 24, 2022 |
| ASRock        | H310CM-DVS                  | Desktop     | [17f6682bf3](https://linux-hardware.org/?probe=17f6682bf3) | Aug 20, 2022 |
| ASUSTek       | ProArt B660-CREATOR D4      | Desktop     | [0b9e6d6ad9](https://linux-hardware.org/?probe=0b9e6d6ad9) | Aug 19, 2022 |
| Sony          | VPCEB1S1E                   | Notebook    | [45dbb67d02](https://linux-hardware.org/?probe=45dbb67d02) | Aug 18, 2022 |
| Gigabyte      | B550 AORUS ELITE AX         | Desktop     | [49943f84c8](https://linux-hardware.org/?probe=49943f84c8) | Aug 18, 2022 |
| ASUSTek       | ProArt B660-CREATOR D4      | Desktop     | [f9f180ac3a](https://linux-hardware.org/?probe=f9f180ac3a) | Aug 18, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [3ab7d6393c](https://linux-hardware.org/?probe=3ab7d6393c) | Aug 17, 2022 |
| Dell          | G15 5515                    | Notebook    | [3a7c8ea452](https://linux-hardware.org/?probe=3a7c8ea452) | Aug 17, 2022 |
| ASUSTek       | UX310UQ                     | Notebook    | [f058aa0bf2](https://linux-hardware.org/?probe=f058aa0bf2) | Aug 15, 2022 |
| ASUSTek       | P5K SE                      | Desktop     | [59168fc3cb](https://linux-hardware.org/?probe=59168fc3cb) | Aug 14, 2022 |
| ASRock        | J4125B-ITX                  | Desktop     | [6e4ca6823f](https://linux-hardware.org/?probe=6e4ca6823f) | Aug 14, 2022 |
| ASRock        | J4125B-ITX                  | Desktop     | [81a8491905](https://linux-hardware.org/?probe=81a8491905) | Aug 14, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [ca96da9d08](https://linux-hardware.org/?probe=ca96da9d08) | Aug 12, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [0644c9f46c](https://linux-hardware.org/?probe=0644c9f46c) | Aug 12, 2022 |
| Lenovo        | V3000 80KV                  | Notebook    | [32c1aa64cf](https://linux-hardware.org/?probe=32c1aa64cf) | Aug 09, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [9e849a1708](https://linux-hardware.org/?probe=9e849a1708) | Aug 07, 2022 |
| Toshiba       | NB100                       | Notebook    | [b91ee9b36b](https://linux-hardware.org/?probe=b91ee9b36b) | Aug 05, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [1498e07a4b](https://linux-hardware.org/?probe=1498e07a4b) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e74155922c](https://linux-hardware.org/?probe=e74155922c) | Aug 04, 2022 |
| MSI           | H110M PRO-VH                | Desktop     | [8bdd8d91db](https://linux-hardware.org/?probe=8bdd8d91db) | Aug 04, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [dcc08c0fa5](https://linux-hardware.org/?probe=dcc08c0fa5) | Aug 03, 2022 |
| HP            | Compaq 6730s                | Notebook    | [5d805b2f5e](https://linux-hardware.org/?probe=5d805b2f5e) | Jul 31, 2022 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [7b0b52e138](https://linux-hardware.org/?probe=7b0b52e138) | Jul 31, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [ee5c151c3a](https://linux-hardware.org/?probe=ee5c151c3a) | Jul 30, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [e271ff9bf8](https://linux-hardware.org/?probe=e271ff9bf8) | Jul 29, 2022 |
| Gigabyte      | B550 AORUS ELITE AX         | Desktop     | [eee9c60bec](https://linux-hardware.org/?probe=eee9c60bec) | Jul 29, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [398fb75cec](https://linux-hardware.org/?probe=398fb75cec) | Jul 29, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [ceb1b7da41](https://linux-hardware.org/?probe=ceb1b7da41) | Jul 28, 2022 |
| MSI           | H110M PRO-VH                | Desktop     | [2058561297](https://linux-hardware.org/?probe=2058561297) | Jul 28, 2022 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [9b3bb82b80](https://linux-hardware.org/?probe=9b3bb82b80) | Jul 28, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [8b520883ad](https://linux-hardware.org/?probe=8b520883ad) | Jul 27, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [cf1f919243](https://linux-hardware.org/?probe=cf1f919243) | Jul 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [a57cf84361](https://linux-hardware.org/?probe=a57cf84361) | Jul 27, 2022 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [a296eed968](https://linux-hardware.org/?probe=a296eed968) | Jul 27, 2022 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [24ad5aed74](https://linux-hardware.org/?probe=24ad5aed74) | Jul 27, 2022 |
| Sony          | VPCF11M1E                   | Notebook    | [97a18303ee](https://linux-hardware.org/?probe=97a18303ee) | Jul 26, 2022 |
| Dynabook      | Satellite Pro C50D-B        | Notebook    | [bd7ef0af73](https://linux-hardware.org/?probe=bd7ef0af73) | Jul 25, 2022 |
| Dell          | Latitude 5420               | Notebook    | [eecbd6aeec](https://linux-hardware.org/?probe=eecbd6aeec) | Jul 22, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [52ca04ad6b](https://linux-hardware.org/?probe=52ca04ad6b) | Jul 20, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [59e9017400](https://linux-hardware.org/?probe=59e9017400) | Jul 19, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [257823caa8](https://linux-hardware.org/?probe=257823caa8) | Jul 17, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [0f1dd0317a](https://linux-hardware.org/?probe=0f1dd0317a) | Jul 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [3884be1bc0](https://linux-hardware.org/?probe=3884be1bc0) | Jul 15, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [1d2991137d](https://linux-hardware.org/?probe=1d2991137d) | Jul 15, 2022 |
| Acer          | Extensa 215-32              | Notebook    | [bd34d99acc](https://linux-hardware.org/?probe=bd34d99acc) | Jul 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [e992a45818](https://linux-hardware.org/?probe=e992a45818) | Jul 15, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [95b0d6d487](https://linux-hardware.org/?probe=95b0d6d487) | Jul 14, 2022 |
| Toshiba       | Satellite L550              | Notebook    | [cb3f0e6381](https://linux-hardware.org/?probe=cb3f0e6381) | Jul 13, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [8bdaa5b844](https://linux-hardware.org/?probe=8bdaa5b844) | Jul 13, 2022 |
| ASUSTek       | P5Q3                        | Desktop     | [5fb3e2b502](https://linux-hardware.org/?probe=5fb3e2b502) | Jul 10, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [f52d09ef30](https://linux-hardware.org/?probe=f52d09ef30) | Jul 07, 2022 |
| HP            | Compaq CQ58                 | Notebook    | [d46da7be57](https://linux-hardware.org/?probe=d46da7be57) | Jul 05, 2022 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [8dceb94bee](https://linux-hardware.org/?probe=8dceb94bee) | Jul 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [df0722af87](https://linux-hardware.org/?probe=df0722af87) | Jul 04, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [af74b651d5](https://linux-hardware.org/?probe=af74b651d5) | Jul 04, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [d030e357db](https://linux-hardware.org/?probe=d030e357db) | Jul 02, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [987d9aa4d3](https://linux-hardware.org/?probe=987d9aa4d3) | Jul 01, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [08ed20d4da](https://linux-hardware.org/?probe=08ed20d4da) | Jul 01, 2022 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [10620fe30b](https://linux-hardware.org/?probe=10620fe30b) | Jun 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [65e5ab29fd](https://linux-hardware.org/?probe=65e5ab29fd) | Jun 26, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [c6c59e12b6](https://linux-hardware.org/?probe=c6c59e12b6) | Jun 25, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [bb4f0d2bce](https://linux-hardware.org/?probe=bb4f0d2bce) | Jun 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | Notebook    | [a2a6f48fe2](https://linux-hardware.org/?probe=a2a6f48fe2) | Jun 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [eb61c79793](https://linux-hardware.org/?probe=eb61c79793) | Jun 21, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [999d6e4735](https://linux-hardware.org/?probe=999d6e4735) | Jun 20, 2022 |
| Gigabyte      | 965P-S3                     | Desktop     | [0beb9ce480](https://linux-hardware.org/?probe=0beb9ce480) | Jun 19, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [d42c64a985](https://linux-hardware.org/?probe=d42c64a985) | Jun 18, 2022 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [292cc4bcab](https://linux-hardware.org/?probe=292cc4bcab) | Jun 17, 2022 |
| Gigabyte      | X570S UD                    | Desktop     | [98f8907a6b](https://linux-hardware.org/?probe=98f8907a6b) | Jun 14, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [ee0b4c4389](https://linux-hardware.org/?probe=ee0b4c4389) | Jun 14, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [75fd209e13](https://linux-hardware.org/?probe=75fd209e13) | Jun 14, 2022 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [6acc89788e](https://linux-hardware.org/?probe=6acc89788e) | Jun 12, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [af2362a1e4](https://linux-hardware.org/?probe=af2362a1e4) | Jun 12, 2022 |
| HP            | ProBook 4530s               | Notebook    | [8162a82eba](https://linux-hardware.org/?probe=8162a82eba) | Jun 11, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [70254d6e4d](https://linux-hardware.org/?probe=70254d6e4d) | Jun 08, 2022 |
| Lenovo        | 3140 NOK                    | Desktop     | [03619a223f](https://linux-hardware.org/?probe=03619a223f) | Jun 07, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [039d0b1cdc](https://linux-hardware.org/?probe=039d0b1cdc) | Jun 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [2607169dfe](https://linux-hardware.org/?probe=2607169dfe) | Jun 06, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [3ede7ad313](https://linux-hardware.org/?probe=3ede7ad313) | Jun 02, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [51e3142bae](https://linux-hardware.org/?probe=51e3142bae) | Jun 02, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [e8e9948f71](https://linux-hardware.org/?probe=e8e9948f71) | Jun 02, 2022 |
| HP            | Unknown                     | Notebook    | [521124e0e2](https://linux-hardware.org/?probe=521124e0e2) | May 28, 2022 |
| Lenovo        | ThinkPad X230 2324FV6       | Notebook    | [6386696f31](https://linux-hardware.org/?probe=6386696f31) | May 25, 2022 |
| Dell          | Vostro 5625                 | Notebook    | [2ae97190b6](https://linux-hardware.org/?probe=2ae97190b6) | May 24, 2022 |
| Dell          | Latitude 5420               | Notebook    | [28c0f1ba96](https://linux-hardware.org/?probe=28c0f1ba96) | May 24, 2022 |
| ASUSTek       | X505BA                      | Notebook    | [685c1f7378](https://linux-hardware.org/?probe=685c1f7378) | May 22, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [22fb59a94a](https://linux-hardware.org/?probe=22fb59a94a) | May 19, 2022 |
| Pegatron      | A15                         | Notebook    | [335d6a014c](https://linux-hardware.org/?probe=335d6a014c) | May 18, 2022 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [87a148ac90](https://linux-hardware.org/?probe=87a148ac90) | May 18, 2022 |
| ASUSTek       | H61M-E                      | Desktop     | [1dc25cb237](https://linux-hardware.org/?probe=1dc25cb237) | May 17, 2022 |
| HP            | Mini 110-1100               | Notebook    | [b93ac7c302](https://linux-hardware.org/?probe=b93ac7c302) | May 16, 2022 |
| HP            | Mini 110-1100               | Notebook    | [4a5f85e53d](https://linux-hardware.org/?probe=4a5f85e53d) | May 16, 2022 |
| HP            | ProBook 645 G1              | Notebook    | [771f25ecc9](https://linux-hardware.org/?probe=771f25ecc9) | May 14, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [0e9a009c11](https://linux-hardware.org/?probe=0e9a009c11) | May 13, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [2c8d1eec1e](https://linux-hardware.org/?probe=2c8d1eec1e) | May 13, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [074043a5ca](https://linux-hardware.org/?probe=074043a5ca) | May 13, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [ed659a9633](https://linux-hardware.org/?probe=ed659a9633) | May 13, 2022 |
| Dell          | Inspiron 7786               | Convertible | [7df1484700](https://linux-hardware.org/?probe=7df1484700) | May 12, 2022 |
| AOpen         | i67QMx-DV R1.00BC1 55MP6... | Desktop     | [151db99970](https://linux-hardware.org/?probe=151db99970) | May 11, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [5d59ce5dd7](https://linux-hardware.org/?probe=5d59ce5dd7) | May 11, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [173fac4f5b](https://linux-hardware.org/?probe=173fac4f5b) | May 11, 2022 |
| HP            | 3031h                       | Desktop     | [4a57ff5761](https://linux-hardware.org/?probe=4a57ff5761) | May 10, 2022 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [8caf6e2b66](https://linux-hardware.org/?probe=8caf6e2b66) | May 09, 2022 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [4242d236c5](https://linux-hardware.org/?probe=4242d236c5) | May 09, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [bdfe0722a7](https://linux-hardware.org/?probe=bdfe0722a7) | May 09, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [4fe934e84d](https://linux-hardware.org/?probe=4fe934e84d) | May 06, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [9967806049](https://linux-hardware.org/?probe=9967806049) | May 02, 2022 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [ec5dbcb034](https://linux-hardware.org/?probe=ec5dbcb034) | May 02, 2022 |
| Dell          | Latitude E6500              | Notebook    | [bbd302d9ba](https://linux-hardware.org/?probe=bbd302d9ba) | May 02, 2022 |
| Dell          | Latitude E6500              | Notebook    | [8eb92ca472](https://linux-hardware.org/?probe=8eb92ca472) | May 02, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [d2903d25c5](https://linux-hardware.org/?probe=d2903d25c5) | Apr 30, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [de4ae72708](https://linux-hardware.org/?probe=de4ae72708) | Apr 28, 2022 |
| Lenovo        | ThinkPad T495 20NJ0012GM    | Notebook    | [81f7a796be](https://linux-hardware.org/?probe=81f7a796be) | Apr 28, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [c6bf48bfb3](https://linux-hardware.org/?probe=c6bf48bfb3) | Apr 27, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [9da2289998](https://linux-hardware.org/?probe=9da2289998) | Apr 24, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [e9676d63f9](https://linux-hardware.org/?probe=e9676d63f9) | Apr 24, 2022 |
| HP            | Notebook                    | Notebook    | [4772a69956](https://linux-hardware.org/?probe=4772a69956) | Apr 23, 2022 |
| HP            | Notebook                    | Notebook    | [e6099e9fd5](https://linux-hardware.org/?probe=e6099e9fd5) | Apr 22, 2022 |
| ASUSTek       | P5P43TD                     | Desktop     | [8c7c0bd289](https://linux-hardware.org/?probe=8c7c0bd289) | Apr 21, 2022 |
| HP            | Pavilion g7                 | Notebook    | [6bfdb0c3c9](https://linux-hardware.org/?probe=6bfdb0c3c9) | Apr 19, 2022 |
| HP            | Pavilion g7                 | Notebook    | [97e00013eb](https://linux-hardware.org/?probe=97e00013eb) | Apr 19, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [ee7354dd8d](https://linux-hardware.org/?probe=ee7354dd8d) | Apr 19, 2022 |
| Alienware     | M11x                        | Notebook    | [df72ecbe58](https://linux-hardware.org/?probe=df72ecbe58) | Apr 18, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [a6ae41a1c9](https://linux-hardware.org/?probe=a6ae41a1c9) | Apr 18, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [dddd6b6edd](https://linux-hardware.org/?probe=dddd6b6edd) | Apr 18, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [c5d02ba256](https://linux-hardware.org/?probe=c5d02ba256) | Apr 17, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [217905d42a](https://linux-hardware.org/?probe=217905d42a) | Apr 17, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [912c61bb9b](https://linux-hardware.org/?probe=912c61bb9b) | Apr 15, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | Notebook    | [4838334e73](https://linux-hardware.org/?probe=4838334e73) | Apr 14, 2022 |
| Dell          | 04PT3G A00                  | Desktop     | [a10754ebca](https://linux-hardware.org/?probe=a10754ebca) | Apr 14, 2022 |
| Dell          | Latitude D630               | Notebook    | [dbee98e342](https://linux-hardware.org/?probe=dbee98e342) | Apr 13, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [92b78eaf1b](https://linux-hardware.org/?probe=92b78eaf1b) | Apr 13, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [0ad016db29](https://linux-hardware.org/?probe=0ad016db29) | Apr 13, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [b41fc0fac0](https://linux-hardware.org/?probe=b41fc0fac0) | Apr 13, 2022 |
| Unknown       | Z37S                        | Notebook    | [25d5118843](https://linux-hardware.org/?probe=25d5118843) | Apr 13, 2022 |
| Schenker      | XMG NEO (TGL/M21)           | Notebook    | [eeb87dca9a](https://linux-hardware.org/?probe=eeb87dca9a) | Apr 13, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [5c247da651](https://linux-hardware.org/?probe=5c247da651) | Apr 10, 2022 |
| HP            | G7000                       | Notebook    | [11280d88c6](https://linux-hardware.org/?probe=11280d88c6) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [761e954b86](https://linux-hardware.org/?probe=761e954b86) | Apr 07, 2022 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [111167cacb](https://linux-hardware.org/?probe=111167cacb) | Apr 07, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [091e8b72d9](https://linux-hardware.org/?probe=091e8b72d9) | Apr 05, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [cda73dafa0](https://linux-hardware.org/?probe=cda73dafa0) | Apr 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40705 WIN     | Desktop     | [374819f582](https://linux-hardware.org/?probe=374819f582) | Apr 04, 2022 |
| Acer          | Aspire 5745G                | Notebook    | [4a6e981204](https://linux-hardware.org/?probe=4a6e981204) | Apr 04, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [492c2c7bf4](https://linux-hardware.org/?probe=492c2c7bf4) | Apr 03, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8d251b1b2a](https://linux-hardware.org/?probe=8d251b1b2a) | Apr 03, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [97969b1325](https://linux-hardware.org/?probe=97969b1325) | Apr 03, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [8aeaa381e8](https://linux-hardware.org/?probe=8aeaa381e8) | Apr 03, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [722346a184](https://linux-hardware.org/?probe=722346a184) | Apr 03, 2022 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [348af6c202](https://linux-hardware.org/?probe=348af6c202) | Apr 02, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [e237e56d72](https://linux-hardware.org/?probe=e237e56d72) | Apr 02, 2022 |
| Sony          | VGN-AW11XU_Q                | Notebook    | [b3f2270d5f](https://linux-hardware.org/?probe=b3f2270d5f) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [6b00b2928a](https://linux-hardware.org/?probe=6b00b2928a) | Apr 01, 2022 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [3ac2dfc728](https://linux-hardware.org/?probe=3ac2dfc728) | Apr 01, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [ee7a1d8721](https://linux-hardware.org/?probe=ee7a1d8721) | Mar 30, 2022 |
| HP            | Unknown                     | Notebook    | [e989736b06](https://linux-hardware.org/?probe=e989736b06) | Mar 30, 2022 |
| HP            | Unknown                     | Notebook    | [672d3c8b62](https://linux-hardware.org/?probe=672d3c8b62) | Mar 29, 2022 |
| ASRock        | M3N78D FX                   | Desktop     | [66bb134c6c](https://linux-hardware.org/?probe=66bb134c6c) | Mar 29, 2022 |
| Raspberry ... | Raspberry Pi Zero Rev 1.... | Soc         | [380efd9f08](https://linux-hardware.org/?probe=380efd9f08) | Mar 29, 2022 |
| HP            | 250 G3                      | Notebook    | [22f691edac](https://linux-hardware.org/?probe=22f691edac) | Mar 29, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [6335525127](https://linux-hardware.org/?probe=6335525127) | Mar 28, 2022 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [d01df98d83](https://linux-hardware.org/?probe=d01df98d83) | Mar 28, 2022 |
| ASRock        | M3N78D FX                   | Desktop     | [3ebcef4241](https://linux-hardware.org/?probe=3ebcef4241) | Mar 28, 2022 |
| Dell          | Latitude 7420               | Notebook    | [9ef752b49a](https://linux-hardware.org/?probe=9ef752b49a) | Mar 27, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [1297813d45](https://linux-hardware.org/?probe=1297813d45) | Mar 27, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [c8289cd264](https://linux-hardware.org/?probe=c8289cd264) | Mar 26, 2022 |
| HP            | ProBook 4530s               | Notebook    | [f4d3c7fddf](https://linux-hardware.org/?probe=f4d3c7fddf) | Mar 25, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [22d9e9ead2](https://linux-hardware.org/?probe=22d9e9ead2) | Mar 25, 2022 |
| Lenovo        | IdeaPad Y550 20017          | Notebook    | [09576b4897](https://linux-hardware.org/?probe=09576b4897) | Mar 25, 2022 |
| Lenovo        | IdeaPad Y550 20017          | Notebook    | [610b3ad535](https://linux-hardware.org/?probe=610b3ad535) | Mar 25, 2022 |
| Dell          | Latitude E6220              | Notebook    | [b006a7da3b](https://linux-hardware.org/?probe=b006a7da3b) | Mar 23, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [ac66ce376e](https://linux-hardware.org/?probe=ac66ce376e) | Mar 23, 2022 |
| ASUSTek       | N752VX                      | Notebook    | [9eb7fe04cf](https://linux-hardware.org/?probe=9eb7fe04cf) | Mar 21, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5c6b1616fa](https://linux-hardware.org/?probe=5c6b1616fa) | Mar 21, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [789a97d437](https://linux-hardware.org/?probe=789a97d437) | Mar 20, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [9055c398c9](https://linux-hardware.org/?probe=9055c398c9) | Mar 18, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [4fa05350b7](https://linux-hardware.org/?probe=4fa05350b7) | Mar 17, 2022 |
| Dell          | Latitude E7470              | Notebook    | [db5eecff9e](https://linux-hardware.org/?probe=db5eecff9e) | Mar 16, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [44e9c813e9](https://linux-hardware.org/?probe=44e9c813e9) | Mar 14, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [321ad64376](https://linux-hardware.org/?probe=321ad64376) | Mar 13, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [d5bc8e4202](https://linux-hardware.org/?probe=d5bc8e4202) | Mar 13, 2022 |
| HP            | 1850                        | Desktop     | [7e0b4230d4](https://linux-hardware.org/?probe=7e0b4230d4) | Mar 11, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [e251c9f079](https://linux-hardware.org/?probe=e251c9f079) | Mar 11, 2022 |
| HP            | 86F3 00100                  | All in one  | [7de0381db8](https://linux-hardware.org/?probe=7de0381db8) | Mar 11, 2022 |
| MSI           | MS-7091                     | Desktop     | [6ff1d651e4](https://linux-hardware.org/?probe=6ff1d651e4) | Mar 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c36fe6c067](https://linux-hardware.org/?probe=c36fe6c067) | Mar 10, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | Desktop     | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | Desktop     | [2a7edc452e](https://linux-hardware.org/?probe=2a7edc452e) | Mar 09, 2022 |
| Gigabyte      | F2A85XM-D3H                 | Desktop     | [cf20f6e233](https://linux-hardware.org/?probe=cf20f6e233) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| Toshiba       | Satellite C50-B             | Notebook    | [6bffc83185](https://linux-hardware.org/?probe=6bffc83185) | Mar 08, 2022 |
| Dell          | Latitude E6430              | Notebook    | [e32f5b40a1](https://linux-hardware.org/?probe=e32f5b40a1) | Mar 07, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [486f5c28ad](https://linux-hardware.org/?probe=486f5c28ad) | Mar 07, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [f56996aab6](https://linux-hardware.org/?probe=f56996aab6) | Mar 07, 2022 |
| Acer          | Aspire A515-44G             | Notebook    | [7f95a3373c](https://linux-hardware.org/?probe=7f95a3373c) | Mar 06, 2022 |
| Acer          | Aspire A515-44G             | Notebook    | [ea17b9cff2](https://linux-hardware.org/?probe=ea17b9cff2) | Mar 06, 2022 |
| HP            | 3048h                       | Desktop     | [cb9a7b7f4f](https://linux-hardware.org/?probe=cb9a7b7f4f) | Mar 05, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [9e9718070f](https://linux-hardware.org/?probe=9e9718070f) | Mar 02, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [3cc5bac970](https://linux-hardware.org/?probe=3cc5bac970) | Mar 02, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [299a727e8a](https://linux-hardware.org/?probe=299a727e8a) | Mar 02, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [2789dc5384](https://linux-hardware.org/?probe=2789dc5384) | Mar 02, 2022 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [3f6b2ab46e](https://linux-hardware.org/?probe=3f6b2ab46e) | Mar 01, 2022 |
| Toshiba       | Satellite C50-A-19T         | Notebook    | [daa7733b2d](https://linux-hardware.org/?probe=daa7733b2d) | Feb 28, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [e5da146c8e](https://linux-hardware.org/?probe=e5da146c8e) | Feb 27, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [926781b691](https://linux-hardware.org/?probe=926781b691) | Feb 27, 2022 |
| Supermicro    | X9SRA/X9SRA-3               | Server      | [7f43788673](https://linux-hardware.org/?probe=7f43788673) | Feb 27, 2022 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [abb12adccc](https://linux-hardware.org/?probe=abb12adccc) | Feb 26, 2022 |
| HP            | 2000                        | Notebook    | [53d7131a3d](https://linux-hardware.org/?probe=53d7131a3d) | Feb 26, 2022 |
| Clevo         | M740TU(N)/M760TU(N)/W7X0... | Notebook    | [810f5ad6fa](https://linux-hardware.org/?probe=810f5ad6fa) | Feb 25, 2022 |
| Dell          | 0N185P A01                  | Desktop     | [996f9f7805](https://linux-hardware.org/?probe=996f9f7805) | Feb 24, 2022 |
| Fujitsu       | LIFEBOOK AH512              | Notebook    | [d7889a52d1](https://linux-hardware.org/?probe=d7889a52d1) | Feb 24, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [ad54ee0dbe](https://linux-hardware.org/?probe=ad54ee0dbe) | Feb 20, 2022 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [fc444df804](https://linux-hardware.org/?probe=fc444df804) | Feb 20, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [1ba170be6a](https://linux-hardware.org/?probe=1ba170be6a) | Feb 20, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [c036f1a977](https://linux-hardware.org/?probe=c036f1a977) | Feb 20, 2022 |
| Teclast       | F7                          | Notebook    | [fccda8fbdc](https://linux-hardware.org/?probe=fccda8fbdc) | Feb 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [b8e767511b](https://linux-hardware.org/?probe=b8e767511b) | Feb 19, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [9e10ad29c3](https://linux-hardware.org/?probe=9e10ad29c3) | Feb 19, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [2e68ddfdd3](https://linux-hardware.org/?probe=2e68ddfdd3) | Feb 18, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [536a1e49b0](https://linux-hardware.org/?probe=536a1e49b0) | Feb 17, 2022 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [c9d8bb9bd9](https://linux-hardware.org/?probe=c9d8bb9bd9) | Feb 16, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [87774dacdd](https://linux-hardware.org/?probe=87774dacdd) | Feb 15, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [3cf4dc7f97](https://linux-hardware.org/?probe=3cf4dc7f97) | Feb 15, 2022 |
| MSI           | MS-7176                     | Desktop     | [b54631ff57](https://linux-hardware.org/?probe=b54631ff57) | Feb 14, 2022 |
| E-shop.gr     | V113                        | Notebook    | [e9a1ae2e96](https://linux-hardware.org/?probe=e9a1ae2e96) | Feb 14, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [640d06ac28](https://linux-hardware.org/?probe=640d06ac28) | Feb 12, 2022 |
| E-shop.gr     | V113                        | Notebook    | [6d015f399b](https://linux-hardware.org/?probe=6d015f399b) | Feb 12, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [57de891506](https://linux-hardware.org/?probe=57de891506) | Feb 12, 2022 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [e86fa9ee02](https://linux-hardware.org/?probe=e86fa9ee02) | Feb 09, 2022 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [1b6aa0ce08](https://linux-hardware.org/?probe=1b6aa0ce08) | Feb 09, 2022 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [dcd0177f71](https://linux-hardware.org/?probe=dcd0177f71) | Feb 07, 2022 |
| ASUSTek       | 900                         | Notebook    | [88ce413793](https://linux-hardware.org/?probe=88ce413793) | Feb 06, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [8f79e4d763](https://linux-hardware.org/?probe=8f79e4d763) | Feb 06, 2022 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [5a3fcd1230](https://linux-hardware.org/?probe=5a3fcd1230) | Feb 05, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [e32abec202](https://linux-hardware.org/?probe=e32abec202) | Feb 03, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [df711c6514](https://linux-hardware.org/?probe=df711c6514) | Feb 03, 2022 |
| Lenovo        | ThinkCentre M58 7373W43     | Desktop     | [4dc312f4f3](https://linux-hardware.org/?probe=4dc312f4f3) | Feb 02, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [f317005b0a](https://linux-hardware.org/?probe=f317005b0a) | Feb 02, 2022 |
| Lenovo        | NOK                         | Desktop     | [8905840b45](https://linux-hardware.org/?probe=8905840b45) | Feb 02, 2022 |
| ASUSTek       | H110M-D                     | Desktop     | [3dbf1d9544](https://linux-hardware.org/?probe=3dbf1d9544) | Jan 31, 2022 |
| Lenovo        | ThinkPad Edge 0301GBG       | Notebook    | [2227d37e2f](https://linux-hardware.org/?probe=2227d37e2f) | Jan 30, 2022 |
| Sony          | SVE1113M1EB                 | Notebook    | [83220eef23](https://linux-hardware.org/?probe=83220eef23) | Jan 30, 2022 |
| HP            | Pavilion dv3                | Notebook    | [c1abcb66ee](https://linux-hardware.org/?probe=c1abcb66ee) | Jan 29, 2022 |
| RuggedPC      | RuggedPadC86V               | Tablet      | [c9f76be971](https://linux-hardware.org/?probe=c9f76be971) | Jan 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [48ad956cc2](https://linux-hardware.org/?probe=48ad956cc2) | Jan 28, 2022 |
| HP            | 8434 11                     | Desktop     | [76a7851e7f](https://linux-hardware.org/?probe=76a7851e7f) | Jan 28, 2022 |
| VIA Techno... | VT8366-8233/5               | Desktop     | [e285c87c48](https://linux-hardware.org/?probe=e285c87c48) | Jan 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f7633506c3](https://linux-hardware.org/?probe=f7633506c3) | Jan 26, 2022 |
| VIA Techno... | VT8366-8233/5               | Desktop     | [54ce61fa7e](https://linux-hardware.org/?probe=54ce61fa7e) | Jan 25, 2022 |
| MSI           | A88XM-E45                   | Desktop     | [6a25ca99d2](https://linux-hardware.org/?probe=6a25ca99d2) | Jan 24, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [f6b7e2e2e6](https://linux-hardware.org/?probe=f6b7e2e2e6) | Jan 24, 2022 |
| HP            | 86F3 00100                  | All in one  | [6b9bc0d34d](https://linux-hardware.org/?probe=6b9bc0d34d) | Jan 24, 2022 |
| Lenovo        | 314F NO DPK                 | Desktop     | [07bd238c48](https://linux-hardware.org/?probe=07bd238c48) | Jan 24, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [13de9d767d](https://linux-hardware.org/?probe=13de9d767d) | Jan 21, 2022 |
| MSI           | H310M PRO-VH                | Desktop     | [68c71dac17](https://linux-hardware.org/?probe=68c71dac17) | Jan 21, 2022 |
| ASRock        | G41C-VS                     | Desktop     | [4dbb4b7fad](https://linux-hardware.org/?probe=4dbb4b7fad) | Jan 21, 2022 |
| Albatron      | PM73V                       | Desktop     | [7bd3956f1f](https://linux-hardware.org/?probe=7bd3956f1f) | Jan 21, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [e5d70436b2](https://linux-hardware.org/?probe=e5d70436b2) | Jan 21, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [5716cdab2a](https://linux-hardware.org/?probe=5716cdab2a) | Jan 21, 2022 |
| HP            | 8455                        | Desktop     | [fbf272366c](https://linux-hardware.org/?probe=fbf272366c) | Jan 20, 2022 |
| ASUSTek       | H110M-D                     | Desktop     | [b105d56395](https://linux-hardware.org/?probe=b105d56395) | Jan 19, 2022 |
| ASUSTek       | P5LD2                       | Desktop     | [00ec990ce2](https://linux-hardware.org/?probe=00ec990ce2) | Jan 19, 2022 |
| Dell          | 0KP561                      | Desktop     | [1b772786e5](https://linux-hardware.org/?probe=1b772786e5) | Jan 19, 2022 |
| Dell          | 0FH884                      | Desktop     | [5ffacf9f99](https://linux-hardware.org/?probe=5ffacf9f99) | Jan 19, 2022 |
| Dell          | 0UG982                      | Desktop     | [c85c923e97](https://linux-hardware.org/?probe=c85c923e97) | Jan 19, 2022 |
| Dell          | 0X7841                      | Desktop     | [40600195c8](https://linux-hardware.org/?probe=40600195c8) | Jan 19, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [597677191c](https://linux-hardware.org/?probe=597677191c) | Jan 19, 2022 |
| Dell          | 0UG982                      | Desktop     | [686f3558d2](https://linux-hardware.org/?probe=686f3558d2) | Jan 19, 2022 |
| Lenovo        | 314F NO DPK                 | Desktop     | [f4f3386726](https://linux-hardware.org/?probe=f4f3386726) | Jan 19, 2022 |
| Dell          | 0FH884                      | Desktop     | [f6e9bda3a9](https://linux-hardware.org/?probe=f6e9bda3a9) | Jan 19, 2022 |
| Lenovo        | 314F NO DPK                 | Desktop     | [b9153e0c28](https://linux-hardware.org/?probe=b9153e0c28) | Jan 19, 2022 |
| HP            | 18E7                        | Desktop     | [b68364ed90](https://linux-hardware.org/?probe=b68364ed90) | Jan 19, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [8314cd9ba6](https://linux-hardware.org/?probe=8314cd9ba6) | Jan 19, 2022 |
| Dell          | 0UG982                      | Desktop     | [38c30e280b](https://linux-hardware.org/?probe=38c30e280b) | Jan 19, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [f2d5dba7ff](https://linux-hardware.org/?probe=f2d5dba7ff) | Jan 19, 2022 |
| Dell          | 0FH884                      | Desktop     | [083697081f](https://linux-hardware.org/?probe=083697081f) | Jan 19, 2022 |
| MSI           | H310M PRO-VH                | Desktop     | [844791ed3e](https://linux-hardware.org/?probe=844791ed3e) | Jan 19, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [0601abdfa6](https://linux-hardware.org/?probe=0601abdfa6) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [9fedcb7ff7](https://linux-hardware.org/?probe=9fedcb7ff7) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [48871270a2](https://linux-hardware.org/?probe=48871270a2) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [ca38c856e1](https://linux-hardware.org/?probe=ca38c856e1) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [a4df88b38f](https://linux-hardware.org/?probe=a4df88b38f) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [a745b9add0](https://linux-hardware.org/?probe=a745b9add0) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [b69abe6fd4](https://linux-hardware.org/?probe=b69abe6fd4) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [9753f9164a](https://linux-hardware.org/?probe=9753f9164a) | Jan 18, 2022 |
| Lenovo        | ThinkCentre M58 7373W43     | Desktop     | [2d7a6e6cb6](https://linux-hardware.org/?probe=2d7a6e6cb6) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [51484889f9](https://linux-hardware.org/?probe=51484889f9) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [4ca462c89a](https://linux-hardware.org/?probe=4ca462c89a) | Jan 18, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [c4c9f4b0a9](https://linux-hardware.org/?probe=c4c9f4b0a9) | Jan 18, 2022 |
| HP            | 8434 11                     | Desktop     | [4a128d2bb2](https://linux-hardware.org/?probe=4a128d2bb2) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [97d4bc7367](https://linux-hardware.org/?probe=97d4bc7367) | Jan 18, 2022 |
| Lenovo        | NOK                         | Desktop     | [7ae2819a6f](https://linux-hardware.org/?probe=7ae2819a6f) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [e86d0cc284](https://linux-hardware.org/?probe=e86d0cc284) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [022f56a960](https://linux-hardware.org/?probe=022f56a960) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [0d2a09f683](https://linux-hardware.org/?probe=0d2a09f683) | Jan 18, 2022 |
| HP            | 8455                        | Desktop     | [639182896b](https://linux-hardware.org/?probe=639182896b) | Jan 18, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [f4bb742149](https://linux-hardware.org/?probe=f4bb742149) | Jan 17, 2022 |
| ASUSTek       | P5LD2                       | Desktop     | [b972c7929f](https://linux-hardware.org/?probe=b972c7929f) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [9a6c2f82f1](https://linux-hardware.org/?probe=9a6c2f82f1) | Jan 17, 2022 |
| Dell          | 0UG982                      | Desktop     | [684478b2fb](https://linux-hardware.org/?probe=684478b2fb) | Jan 17, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [13b01fb40a](https://linux-hardware.org/?probe=13b01fb40a) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [385f76b996](https://linux-hardware.org/?probe=385f76b996) | Jan 17, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [910af5ce1a](https://linux-hardware.org/?probe=910af5ce1a) | Jan 17, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [dc02dbb307](https://linux-hardware.org/?probe=dc02dbb307) | Jan 16, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [f21bf32c9a](https://linux-hardware.org/?probe=f21bf32c9a) | Jan 15, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [f1858e63f4](https://linux-hardware.org/?probe=f1858e63f4) | Jan 14, 2022 |
| Gigabyte      | P55-USB3                    | Desktop     | [07d50b5a0a](https://linux-hardware.org/?probe=07d50b5a0a) | Jan 14, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [6261e290d6](https://linux-hardware.org/?probe=6261e290d6) | Jan 13, 2022 |
| Dell          | Latitude E5440              | Notebook    | [e4ec245baf](https://linux-hardware.org/?probe=e4ec245baf) | Jan 12, 2022 |
| Lenovo        | ThinkPad Edge 0301GBG       | Notebook    | [41205188c5](https://linux-hardware.org/?probe=41205188c5) | Jan 12, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [32b2cea437](https://linux-hardware.org/?probe=32b2cea437) | Jan 10, 2022 |
| Unknown       | Unknown                     | Notebook    | [5557e91853](https://linux-hardware.org/?probe=5557e91853) | Jan 09, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [c09f135f63](https://linux-hardware.org/?probe=c09f135f63) | Jan 09, 2022 |
| HP            | Notebook                    | Notebook    | [97eb40cec9](https://linux-hardware.org/?probe=97eb40cec9) | Jan 07, 2022 |
| Dell          | Inspiron 3585               | Notebook    | [bd035d052c](https://linux-hardware.org/?probe=bd035d052c) | Jan 07, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [5467cc6a24](https://linux-hardware.org/?probe=5467cc6a24) | Jan 06, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [7887040435](https://linux-hardware.org/?probe=7887040435) | Jan 05, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [a03baba93d](https://linux-hardware.org/?probe=a03baba93d) | Jan 05, 2022 |
| ASRock        | H97M Pro4                   | Desktop     | [92a6f429b5](https://linux-hardware.org/?probe=92a6f429b5) | Jan 05, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [f5f5eadcd4](https://linux-hardware.org/?probe=f5f5eadcd4) | Jan 04, 2022 |
| ECS           | G31T-M7                     | Desktop     | [8cd5d79924](https://linux-hardware.org/?probe=8cd5d79924) | Dec 31, 2021 |
| ECS           | G31T-M7                     | Desktop     | [9ebfb53472](https://linux-hardware.org/?probe=9ebfb53472) | Dec 31, 2021 |
| HP            | Compaq 6730s                | Notebook    | [bd8962f904](https://linux-hardware.org/?probe=bd8962f904) | Dec 30, 2021 |
| Acer          | AOA110                      | Notebook    | [1670ad4a71](https://linux-hardware.org/?probe=1670ad4a71) | Dec 29, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [8e4a08a77a](https://linux-hardware.org/?probe=8e4a08a77a) | Dec 26, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [68ea35c97d](https://linux-hardware.org/?probe=68ea35c97d) | Dec 25, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [fdc6aac853](https://linux-hardware.org/?probe=fdc6aac853) | Dec 25, 2021 |
| Gigabyte      | H170M-D3H DDR3-CF           | Desktop     | [537cb36279](https://linux-hardware.org/?probe=537cb36279) | Dec 25, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [261883bf38](https://linux-hardware.org/?probe=261883bf38) | Dec 23, 2021 |
| HP            | Notebook                    | Notebook    | [c14ea64659](https://linux-hardware.org/?probe=c14ea64659) | Dec 23, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [c860a1c3c5](https://linux-hardware.org/?probe=c860a1c3c5) | Dec 22, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [a57edf2ddc](https://linux-hardware.org/?probe=a57edf2ddc) | Dec 22, 2021 |
| MSI           | H81M PRO-VD                 | Desktop     | [b0c70d78fd](https://linux-hardware.org/?probe=b0c70d78fd) | Dec 22, 2021 |
| Sony          | SVE1113M1EB                 | Notebook    | [09619ba678](https://linux-hardware.org/?probe=09619ba678) | Dec 19, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [8962cfd1c6](https://linux-hardware.org/?probe=8962cfd1c6) | Dec 19, 2021 |
| Dell          | 0MN1TX A01                  | Desktop     | [312bd0bfd8](https://linux-hardware.org/?probe=312bd0bfd8) | Dec 18, 2021 |
| IBM           | 00D4062                     | Server      | [76a0ebbfc4](https://linux-hardware.org/?probe=76a0ebbfc4) | Dec 17, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [a2ee48eeb1](https://linux-hardware.org/?probe=a2ee48eeb1) | Dec 16, 2021 |
| Dell          | Inspiron 3585               | Notebook    | [e12da201c3](https://linux-hardware.org/?probe=e12da201c3) | Dec 16, 2021 |
| Dell          | Inspiron 3585               | Notebook    | [f8e1e0ea63](https://linux-hardware.org/?probe=f8e1e0ea63) | Dec 16, 2021 |
| Sony          | SVE1113M1EB                 | Notebook    | [a91f9c891f](https://linux-hardware.org/?probe=a91f9c891f) | Dec 15, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [495d348f1e](https://linux-hardware.org/?probe=495d348f1e) | Dec 15, 2021 |
| HP            | G62                         | Notebook    | [80ca0b53f0](https://linux-hardware.org/?probe=80ca0b53f0) | Dec 14, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [da23db2916](https://linux-hardware.org/?probe=da23db2916) | Dec 13, 2021 |
| ASUSTek       | P8P67 LE                    | Desktop     | [b86c41a0a9](https://linux-hardware.org/?probe=b86c41a0a9) | Dec 13, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [ecc22ad350](https://linux-hardware.org/?probe=ecc22ad350) | Dec 12, 2021 |
| Sony          | SVF1521A1EW                 | Notebook    | [3ffae5f3ba](https://linux-hardware.org/?probe=3ffae5f3ba) | Dec 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b049c5de44](https://linux-hardware.org/?probe=b049c5de44) | Dec 12, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [ac3e0f0271](https://linux-hardware.org/?probe=ac3e0f0271) | Dec 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [191c3b9c7e](https://linux-hardware.org/?probe=191c3b9c7e) | Dec 10, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c7efd05b73](https://linux-hardware.org/?probe=c7efd05b73) | Dec 10, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [1876329ada](https://linux-hardware.org/?probe=1876329ada) | Dec 10, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [c97b5a008f](https://linux-hardware.org/?probe=c97b5a008f) | Dec 09, 2021 |
| Toshiba       | Satellite C850D-118         | Notebook    | [b15f2e2c92](https://linux-hardware.org/?probe=b15f2e2c92) | Dec 09, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f0a11b91f5](https://linux-hardware.org/?probe=f0a11b91f5) | Dec 09, 2021 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [11f31cc288](https://linux-hardware.org/?probe=11f31cc288) | Dec 08, 2021 |
| Gigabyte      | Z97P-D3                     | Desktop     | [abc89c9b78](https://linux-hardware.org/?probe=abc89c9b78) | Dec 07, 2021 |
| Gateway       | DT55                        | Desktop     | [efc935f11c](https://linux-hardware.org/?probe=efc935f11c) | Dec 06, 2021 |
| Dell          | Inspiron 3585               | Notebook    | [eea11725bb](https://linux-hardware.org/?probe=eea11725bb) | Dec 06, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [75933dd4ba](https://linux-hardware.org/?probe=75933dd4ba) | Dec 06, 2021 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [998b2258eb](https://linux-hardware.org/?probe=998b2258eb) | Dec 05, 2021 |
| Dell          | Inspiron 3585               | Notebook    | [d614f524af](https://linux-hardware.org/?probe=d614f524af) | Dec 05, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [e2d660554f](https://linux-hardware.org/?probe=e2d660554f) | Dec 05, 2021 |
| Acer          | Aspire 7540                 | Notebook    | [ebaf96fd07](https://linux-hardware.org/?probe=ebaf96fd07) | Dec 04, 2021 |
| Dell          | Inspiron 3541               | Notebook    | [6b187612d2](https://linux-hardware.org/?probe=6b187612d2) | Dec 04, 2021 |
| Sony          | SVE1711Q1EB                 | Notebook    | [a4e4d21671](https://linux-hardware.org/?probe=a4e4d21671) | Dec 04, 2021 |
| HP            | Compaq 6910p (GC021ET#AB... | Notebook    | [677180a63e](https://linux-hardware.org/?probe=677180a63e) | Dec 03, 2021 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [5ade9a0569](https://linux-hardware.org/?probe=5ade9a0569) | Dec 02, 2021 |
| Dell          | 0WK833                      | Desktop     | [59fed7d754](https://linux-hardware.org/?probe=59fed7d754) | Nov 30, 2021 |
| Lenovo        | G70-35 80Q5                 | Notebook    | [a53168ca9d](https://linux-hardware.org/?probe=a53168ca9d) | Nov 30, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [d860ff9858](https://linux-hardware.org/?probe=d860ff9858) | Nov 30, 2021 |
| HP            | Pavilion g7                 | Notebook    | [da6e298046](https://linux-hardware.org/?probe=da6e298046) | Nov 29, 2021 |
| Sony          | SVE1113M1EB                 | Notebook    | [e2df3c29e6](https://linux-hardware.org/?probe=e2df3c29e6) | Nov 29, 2021 |
| Dell          | Latitude 7490               | Notebook    | [c12e537d05](https://linux-hardware.org/?probe=c12e537d05) | Nov 29, 2021 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [6e37f9cd8a](https://linux-hardware.org/?probe=6e37f9cd8a) | Nov 29, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [999b38ba1f](https://linux-hardware.org/?probe=999b38ba1f) | Nov 28, 2021 |
| Dell          | 042P49 A02                  | Desktop     | [f6d9c481bd](https://linux-hardware.org/?probe=f6d9c481bd) | Nov 27, 2021 |
| Gigabyte      | P35-S3G                     | Desktop     | [f8b94398df](https://linux-hardware.org/?probe=f8b94398df) | Nov 27, 2021 |
| Toshiba       | Satellite C855-27U          | Notebook    | [5974840aa7](https://linux-hardware.org/?probe=5974840aa7) | Nov 27, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [82a3d5c144](https://linux-hardware.org/?probe=82a3d5c144) | Nov 27, 2021 |
| Unknown       | Unknown                     | Notebook    | [72b623d149](https://linux-hardware.org/?probe=72b623d149) | Nov 27, 2021 |
| Toshiba       | Satellite C850D-118         | Notebook    | [db07af607f](https://linux-hardware.org/?probe=db07af607f) | Nov 26, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [ba4141a214](https://linux-hardware.org/?probe=ba4141a214) | Nov 26, 2021 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [b6396cac2d](https://linux-hardware.org/?probe=b6396cac2d) | Nov 25, 2021 |
| Sony          | SVF1521A1EW                 | Notebook    | [52bd968f68](https://linux-hardware.org/?probe=52bd968f68) | Nov 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2c14d4d6ad](https://linux-hardware.org/?probe=2c14d4d6ad) | Nov 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [b6800c14dc](https://linux-hardware.org/?probe=b6800c14dc) | Nov 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [65b01d9a8a](https://linux-hardware.org/?probe=65b01d9a8a) | Nov 21, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [9915f9e908](https://linux-hardware.org/?probe=9915f9e908) | Nov 20, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [000f6b6f44](https://linux-hardware.org/?probe=000f6b6f44) | Nov 20, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [709cd419bc](https://linux-hardware.org/?probe=709cd419bc) | Nov 19, 2021 |
| HP            | 304Bh                       | Desktop     | [d6f490c0ea](https://linux-hardware.org/?probe=d6f490c0ea) | Nov 19, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [77b5cad080](https://linux-hardware.org/?probe=77b5cad080) | Nov 18, 2021 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [b3319a217d](https://linux-hardware.org/?probe=b3319a217d) | Nov 17, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [9b2574c5be](https://linux-hardware.org/?probe=9b2574c5be) | Nov 17, 2021 |
| Dell          | 0Y2K8N A00                  | Desktop     | [db79ad16d3](https://linux-hardware.org/?probe=db79ad16d3) | Nov 16, 2021 |
| MSI           | B350 TOMAHAWK ARCTIC        | Desktop     | [9cc745f754](https://linux-hardware.org/?probe=9cc745f754) | Nov 16, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [e39729aec8](https://linux-hardware.org/?probe=e39729aec8) | Nov 14, 2021 |
| Gigabyte      | 945P-S3                     | Desktop     | [770408fd3d](https://linux-hardware.org/?probe=770408fd3d) | Nov 14, 2021 |
| Gigabyte      | 945P-S3                     | Desktop     | [2cf9966c22](https://linux-hardware.org/?probe=2cf9966c22) | Nov 14, 2021 |
| Acer          | Aspire E5-553G              | Notebook    | [b22df8f53d](https://linux-hardware.org/?probe=b22df8f53d) | Nov 14, 2021 |
| Acer          | Aspire E5-553G              | Notebook    | [93d20530a1](https://linux-hardware.org/?probe=93d20530a1) | Nov 14, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [7a3d3a2f06](https://linux-hardware.org/?probe=7a3d3a2f06) | Nov 12, 2021 |
| Acer          | Aspire 5742                 | Notebook    | [4c0a93b88d](https://linux-hardware.org/?probe=4c0a93b88d) | Nov 12, 2021 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | Notebook    | [a7998fa53a](https://linux-hardware.org/?probe=a7998fa53a) | Nov 11, 2021 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [867958b2cc](https://linux-hardware.org/?probe=867958b2cc) | Nov 11, 2021 |
| Dell          | 0DXJD9 A00                  | Desktop     | [e9abfeb7a2](https://linux-hardware.org/?probe=e9abfeb7a2) | Nov 11, 2021 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [476167fea8](https://linux-hardware.org/?probe=476167fea8) | Nov 10, 2021 |
| HP            | 339A                        | Desktop     | [702ccff1e4](https://linux-hardware.org/?probe=702ccff1e4) | Nov 09, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [9dc24197f3](https://linux-hardware.org/?probe=9dc24197f3) | Nov 09, 2021 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [dc9fcc92be](https://linux-hardware.org/?probe=dc9fcc92be) | Nov 08, 2021 |
| ASUSTek       | 900                         | Notebook    | [b3f1475dcf](https://linux-hardware.org/?probe=b3f1475dcf) | Nov 08, 2021 |
| HP            | 255 G1                      | Notebook    | [3676d15104](https://linux-hardware.org/?probe=3676d15104) | Nov 06, 2021 |
| MSI           | B150M MORTAR                | Desktop     | [58d8ce0102](https://linux-hardware.org/?probe=58d8ce0102) | Nov 05, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [d1dcf79c72](https://linux-hardware.org/?probe=d1dcf79c72) | Nov 05, 2021 |
| Sony          | SVE1513Y1ESI                | Notebook    | [fc86d071c2](https://linux-hardware.org/?probe=fc86d071c2) | Nov 02, 2021 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [44acfe85a5](https://linux-hardware.org/?probe=44acfe85a5) | Oct 31, 2021 |
| Fujitsu Si... | AMILO Xi 2428               | Notebook    | [3332a4c510](https://linux-hardware.org/?probe=3332a4c510) | Oct 30, 2021 |
| Dell          | Latitude 5520               | Notebook    | [370dda1922](https://linux-hardware.org/?probe=370dda1922) | Oct 28, 2021 |
| HP            | Pavilion dv7                | Notebook    | [d4b81612a8](https://linux-hardware.org/?probe=d4b81612a8) | Oct 28, 2021 |
| Dell          | Latitude 5520               | Notebook    | [2a08ef4aeb](https://linux-hardware.org/?probe=2a08ef4aeb) | Oct 27, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [02cc756dd4](https://linux-hardware.org/?probe=02cc756dd4) | Oct 26, 2021 |
| ASUSTek       | TP202NAS                    | Convertible | [3498f0a5df](https://linux-hardware.org/?probe=3498f0a5df) | Oct 26, 2021 |
| Lenovo        | ThinkPad E595 20NF0002BM    | Notebook    | [52ba950565](https://linux-hardware.org/?probe=52ba950565) | Oct 25, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [cecd552e89](https://linux-hardware.org/?probe=cecd552e89) | Oct 25, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [4e11b29d08](https://linux-hardware.org/?probe=4e11b29d08) | Oct 23, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [16268db25b](https://linux-hardware.org/?probe=16268db25b) | Oct 22, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [963b34aa8b](https://linux-hardware.org/?probe=963b34aa8b) | Oct 22, 2021 |
| Toshiba       | Satellite L50-A-1D9         | Notebook    | [cd55b73689](https://linux-hardware.org/?probe=cd55b73689) | Oct 20, 2021 |
| Lenovo        | ThinkCentre M71e 3167A46    | Desktop     | [afc98aba09](https://linux-hardware.org/?probe=afc98aba09) | Oct 20, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [c76a2534a0](https://linux-hardware.org/?probe=c76a2534a0) | Oct 19, 2021 |
| HP            | Notebook                    | Notebook    | [ff690977bf](https://linux-hardware.org/?probe=ff690977bf) | Oct 19, 2021 |
| HP            | 8717                        | Desktop     | [23f7ea44ce](https://linux-hardware.org/?probe=23f7ea44ce) | Oct 18, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [fa1ceccee5](https://linux-hardware.org/?probe=fa1ceccee5) | Oct 18, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [255aca010b](https://linux-hardware.org/?probe=255aca010b) | Oct 18, 2021 |
| HP            | 1496                        | Desktop     | [f438fdb757](https://linux-hardware.org/?probe=f438fdb757) | Oct 17, 2021 |
| Dell          | Precision M4800             | Notebook    | [87034ed159](https://linux-hardware.org/?probe=87034ed159) | Oct 16, 2021 |
| MSI           | H110I PRO                   | Desktop     | [0aeac6b99e](https://linux-hardware.org/?probe=0aeac6b99e) | Oct 16, 2021 |
| HP            | 1495                        | Desktop     | [e7c0f59f92](https://linux-hardware.org/?probe=e7c0f59f92) | Oct 15, 2021 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [7ba2477e56](https://linux-hardware.org/?probe=7ba2477e56) | Oct 13, 2021 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [ae1811a242](https://linux-hardware.org/?probe=ae1811a242) | Oct 13, 2021 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [a671b6ab07](https://linux-hardware.org/?probe=a671b6ab07) | Oct 11, 2021 |
| HP            | 1496                        | Desktop     | [f6ad468908](https://linux-hardware.org/?probe=f6ad468908) | Oct 10, 2021 |
| ARIMA         | W651UI                      | Notebook    | [287379af9f](https://linux-hardware.org/?probe=287379af9f) | Oct 10, 2021 |
| MSI           | H110I PRO                   | Desktop     | [33e1bf9b6c](https://linux-hardware.org/?probe=33e1bf9b6c) | Oct 09, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [13ee121adc](https://linux-hardware.org/?probe=13ee121adc) | Oct 07, 2021 |
| MSI           | B150M MORTAR                | Desktop     | [fd3b108340](https://linux-hardware.org/?probe=fd3b108340) | Oct 07, 2021 |
| MSI           | Alpha 17 A4DEK              | Notebook    | [eca8493d4b](https://linux-hardware.org/?probe=eca8493d4b) | Oct 07, 2021 |
| HP            | 1496                        | Desktop     | [3f369a5dd6](https://linux-hardware.org/?probe=3f369a5dd6) | Oct 06, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [415ce3638d](https://linux-hardware.org/?probe=415ce3638d) | Oct 06, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [74e6b1bc07](https://linux-hardware.org/?probe=74e6b1bc07) | Oct 06, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [9e35238cd2](https://linux-hardware.org/?probe=9e35238cd2) | Oct 05, 2021 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [c627fc3c07](https://linux-hardware.org/?probe=c627fc3c07) | Oct 04, 2021 |
| HP            | 255 G6 Notebook PC          | Notebook    | [6ae274321c](https://linux-hardware.org/?probe=6ae274321c) | Oct 03, 2021 |
| MSI           | B150M MORTAR                | Desktop     | [224b713b5c](https://linux-hardware.org/?probe=224b713b5c) | Oct 03, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [62558ba69c](https://linux-hardware.org/?probe=62558ba69c) | Sep 29, 2021 |
| Lenovo        | ThinkPad T420 4236A22       | Notebook    | [e92d8556e9](https://linux-hardware.org/?probe=e92d8556e9) | Sep 29, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [68b6365968](https://linux-hardware.org/?probe=68b6365968) | Sep 28, 2021 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [1c1bca9399](https://linux-hardware.org/?probe=1c1bca9399) | Sep 28, 2021 |
| PC Special... | N85_N87,HJ,HJ1,HK1          | Notebook    | [c5a7069c64](https://linux-hardware.org/?probe=c5a7069c64) | Sep 26, 2021 |
| Apple         | MacBookAir3,1               | Notebook    | [2b14368aed](https://linux-hardware.org/?probe=2b14368aed) | Sep 25, 2021 |
| ASRock        | M3A790GXH/128M              | Desktop     | [818ec10ec8](https://linux-hardware.org/?probe=818ec10ec8) | Sep 24, 2021 |
| HP            | Pavilion g6                 | Notebook    | [43a34f4589](https://linux-hardware.org/?probe=43a34f4589) | Sep 23, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [bfa3ee0eda](https://linux-hardware.org/?probe=bfa3ee0eda) | Sep 22, 2021 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [b04783b7e1](https://linux-hardware.org/?probe=b04783b7e1) | Sep 20, 2021 |
| Sony          | VGN-FW510F                  | Notebook    | [8f2f403347](https://linux-hardware.org/?probe=8f2f403347) | Sep 19, 2021 |
| Fujitsu Si... | AMILO M7440D                | Notebook    | [e23f21b9b4](https://linux-hardware.org/?probe=e23f21b9b4) | Sep 19, 2021 |
| Fujitsu Si... | AMILO M7440D                | Notebook    | [bce3e66350](https://linux-hardware.org/?probe=bce3e66350) | Sep 19, 2021 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [ad193a0b9c](https://linux-hardware.org/?probe=ad193a0b9c) | Sep 16, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [64a2bd261a](https://linux-hardware.org/?probe=64a2bd261a) | Sep 12, 2021 |
| Acer          | Aspire 5020                 | Notebook    | [54ddef7aa7](https://linux-hardware.org/?probe=54ddef7aa7) | Sep 11, 2021 |
| Acer          | Aspire 5020                 | Notebook    | [8c00427976](https://linux-hardware.org/?probe=8c00427976) | Sep 11, 2021 |
| Acer          | Aspire 3610                 | Notebook    | [fc6953a3f9](https://linux-hardware.org/?probe=fc6953a3f9) | Sep 10, 2021 |
| Acer          | Aspire 3610                 | Notebook    | [3ab0387498](https://linux-hardware.org/?probe=3ab0387498) | Sep 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0bfdb154b9](https://linux-hardware.org/?probe=0bfdb154b9) | Sep 08, 2021 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [d45a82c3c9](https://linux-hardware.org/?probe=d45a82c3c9) | Sep 06, 2021 |
| HP            | 255 G3                      | Notebook    | [bd1a8b58da](https://linux-hardware.org/?probe=bd1a8b58da) | Sep 03, 2021 |
| HP            | 255 G3                      | Notebook    | [b5f1c73339](https://linux-hardware.org/?probe=b5f1c73339) | Sep 03, 2021 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [d3f86f70ae](https://linux-hardware.org/?probe=d3f86f70ae) | Sep 03, 2021 |
| HP            | Presario CQ58               | Notebook    | [313af01ef8](https://linux-hardware.org/?probe=313af01ef8) | Sep 01, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [171462cc36](https://linux-hardware.org/?probe=171462cc36) | Aug 29, 2021 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [862999e242](https://linux-hardware.org/?probe=862999e242) | Aug 27, 2021 |
| Dell          | Inspiron 15 5510            | Notebook    | [cbc1dd6499](https://linux-hardware.org/?probe=cbc1dd6499) | Aug 27, 2021 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [540c64bf79](https://linux-hardware.org/?probe=540c64bf79) | Aug 26, 2021 |
| Sony          | SVT1122B2EW                 | Notebook    | [cb166ff02b](https://linux-hardware.org/?probe=cb166ff02b) | Aug 24, 2021 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [dee9503ed0](https://linux-hardware.org/?probe=dee9503ed0) | Aug 24, 2021 |
| Sony          | SVT1122B2EW                 | Notebook    | [7ef0a9c54a](https://linux-hardware.org/?probe=7ef0a9c54a) | Aug 21, 2021 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [80dfc52333](https://linux-hardware.org/?probe=80dfc52333) | Aug 21, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [1639c4e352](https://linux-hardware.org/?probe=1639c4e352) | Aug 20, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [a7c72d0be5](https://linux-hardware.org/?probe=a7c72d0be5) | Aug 20, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [301da897a6](https://linux-hardware.org/?probe=301da897a6) | Aug 19, 2021 |
| Pegatron      | 2A72h                       | Desktop     | [57575daae2](https://linux-hardware.org/?probe=57575daae2) | Aug 19, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [e1467bfa3e](https://linux-hardware.org/?probe=e1467bfa3e) | Aug 18, 2021 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [0cdcd7cac9](https://linux-hardware.org/?probe=0cdcd7cac9) | Aug 17, 2021 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [d436538e39](https://linux-hardware.org/?probe=d436538e39) | Aug 13, 2021 |
| Acer          | Aspire A517-51G             | Notebook    | [6387ddee62](https://linux-hardware.org/?probe=6387ddee62) | Aug 13, 2021 |
| Dell          | Latitude 7420               | Notebook    | [67165b9d66](https://linux-hardware.org/?probe=67165b9d66) | Aug 12, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [b937ce5e88](https://linux-hardware.org/?probe=b937ce5e88) | Aug 10, 2021 |
| HP            | Pavilion g6                 | Notebook    | [d4523e209b](https://linux-hardware.org/?probe=d4523e209b) | Aug 09, 2021 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | Desktop     | [a2c47444e8](https://linux-hardware.org/?probe=a2c47444e8) | Aug 09, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [b5f6eb1dc0](https://linux-hardware.org/?probe=b5f6eb1dc0) | Aug 09, 2021 |
| HP            | Pavilion g6                 | Notebook    | [4116e486f5](https://linux-hardware.org/?probe=4116e486f5) | Aug 07, 2021 |
| Samsung       | R780                        | Notebook    | [f59b3d2a3f](https://linux-hardware.org/?probe=f59b3d2a3f) | Aug 05, 2021 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [08cf0272da](https://linux-hardware.org/?probe=08cf0272da) | Aug 05, 2021 |
| Dell          | Latitude 5410               | Notebook    | [5f861ac987](https://linux-hardware.org/?probe=5f861ac987) | Aug 04, 2021 |
| Dell          | Latitude 5410               | Notebook    | [aed58623e2](https://linux-hardware.org/?probe=aed58623e2) | Aug 04, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [7243281e28](https://linux-hardware.org/?probe=7243281e28) | Aug 01, 2021 |
| Dell          | Latitude 7390               | Notebook    | [ee6d9cb25f](https://linux-hardware.org/?probe=ee6d9cb25f) | Aug 01, 2021 |
| Dell          | Vostro 5502                 | Notebook    | [f1e6f11078](https://linux-hardware.org/?probe=f1e6f11078) | Jul 31, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [49e2ef564c](https://linux-hardware.org/?probe=49e2ef564c) | Jul 31, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [4c6cb12482](https://linux-hardware.org/?probe=4c6cb12482) | Jul 30, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [1cd2de69ff](https://linux-hardware.org/?probe=1cd2de69ff) | Jul 29, 2021 |
| Toshiba       | Satellite C850D-119         | Notebook    | [bb3f1b4afa](https://linux-hardware.org/?probe=bb3f1b4afa) | Jul 29, 2021 |
| Dell          | Latitude E7470              | Notebook    | [9d580f1809](https://linux-hardware.org/?probe=9d580f1809) | Jul 28, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [e2877b1692](https://linux-hardware.org/?probe=e2877b1692) | Jul 27, 2021 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [e8ffe8991b](https://linux-hardware.org/?probe=e8ffe8991b) | Jul 27, 2021 |
| Dell          | Studio 1555                 | Notebook    | [30b17f2421](https://linux-hardware.org/?probe=30b17f2421) | Jul 26, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [60451d6f55](https://linux-hardware.org/?probe=60451d6f55) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK AH532/G52          | Notebook    | [4e8d8d9253](https://linux-hardware.org/?probe=4e8d8d9253) | Jul 25, 2021 |
| Dell          | 0JD6X3 A05                  | Server      | [494cd954e9](https://linux-hardware.org/?probe=494cd954e9) | Jul 22, 2021 |
| MSI           | H81M PRO-VD                 | Desktop     | [190d4540e9](https://linux-hardware.org/?probe=190d4540e9) | Jul 20, 2021 |
| HP            | 250 G3                      | Notebook    | [b1a0952727](https://linux-hardware.org/?probe=b1a0952727) | Jul 19, 2021 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [aed568d94c](https://linux-hardware.org/?probe=aed568d94c) | Jul 19, 2021 |
| HP            | ProBook 470 G0              | Notebook    | [0ac8121d51](https://linux-hardware.org/?probe=0ac8121d51) | Jul 14, 2021 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [4ffde7a90a](https://linux-hardware.org/?probe=4ffde7a90a) | Jul 13, 2021 |
| Gigabyte      | GA-790XT-USB3               | Desktop     | [72f5d673d9](https://linux-hardware.org/?probe=72f5d673d9) | Jul 11, 2021 |
| PC Special... | N85_N87,HJ,HJ1,HK1          | Notebook    | [515b7e11d1](https://linux-hardware.org/?probe=515b7e11d1) | Jul 11, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [89a5013659](https://linux-hardware.org/?probe=89a5013659) | Jul 09, 2021 |
| Lenovo        | QIQY2                       | Notebook    | [7f8f82feb5](https://linux-hardware.org/?probe=7f8f82feb5) | Jul 07, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Greece/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 176       | 12.66%  |
| Ubuntu 18.04                 | 126       | 9.06%   |
| Ubuntu 22.04                 | 79        | 5.68%   |
| OpenMandriva 4.2             | 36        | 2.59%   |
| Arch Rolling                 | 28        | 2.01%   |
| Pop!_OS 22.04                | 26        | 1.87%   |
| KDE neon 20.04               | 26        | 1.87%   |
| Zorin 16                     | 24        | 1.73%   |
| Linux Mint 21.1              | 23        | 1.65%   |
| Debian 11                    | 23        | 1.65%   |
| OpenMandriva 4.3             | 22        | 1.58%   |
| Ubuntu MATE 20.04            | 21        | 1.51%   |
| Linux Mint 19.3              | 21        | 1.51%   |
| Zorin 15                     | 19        | 1.37%   |
| Ubuntu 19.10                 | 19        | 1.37%   |
| Manjaro                      | 19        | 1.37%   |
| Linux Mint 20.3              | 17        | 1.22%   |
| Ubuntu MATE 18.04            | 16        | 1.15%   |
| Arch                         | 16        | 1.15%   |
| Ubuntu 19.04                 | 15        | 1.08%   |
| Pop!_OS 20.04                | 15        | 1.08%   |
| Linux Mint 20.1              | 15        | 1.08%   |
| ArcoLinux Rolling            | 15        | 1.08%   |
| Xubuntu 18.04                | 14        | 1.01%   |
| Linux Mint 20.2              | 14        | 1.01%   |
| Kubuntu 20.04                | 14        | 1.01%   |
| Ubuntu 21.10                 | 13        | 0.94%   |
| Linux Mint 21                | 13        | 0.94%   |
| Fedora 35                    | 13        | 0.94%   |
| Xubuntu 20.04                | 12        | 0.86%   |
| Ubuntu 22.10                 | 12        | 0.86%   |
| OpenMandriva 23.03           | 12        | 0.86%   |
| Gentoo 2.7                   | 12        | 0.86%   |
| Ubuntu 21.04                 | 11        | 0.79%   |
| Pop!_OS 21.04                | 11        | 0.79%   |
| Debian 10                    | 11        | 0.79%   |
| ROSA R10                     | 10        | 0.72%   |
| openSUSE Tumbleweed-XXXXXXXX | 10        | 0.72%   |
| OpenMandriva 23.01           | 10        | 0.72%   |
| Ubuntu 23.04                 | 9         | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 444       | 34%     |
| Linux Mint    | 117       | 8.96%   |
| OpenMandriva  | 86        | 6.58%   |
| Pop!_OS       | 65        | 4.98%   |
| Fedora        | 61        | 4.67%   |
| Manjaro       | 48        | 3.68%   |
| Debian        | 47        | 3.6%    |
| Zorin         | 45        | 3.45%   |
| Arch          | 43        | 3.29%   |
| Ubuntu MATE   | 42        | 3.22%   |
| Xubuntu       | 34        | 2.6%    |
| KDE neon      | 32        | 2.45%   |
| Kubuntu       | 26        | 1.99%   |
| ROSA          | 23        | 1.76%   |
| Endless       | 18        | 1.38%   |
| ArcoLinux     | 17        | 1.3%    |
| Gentoo        | 16        | 1.23%   |
| openSUSE      | 14        | 1.07%   |
| Ubuntu Unity  | 11        | 0.84%   |
| Elementary    | 11        | 0.84%   |
| MX            | 10        | 0.77%   |
| LMDE          | 8         | 0.61%   |
| Lubuntu       | 7         | 0.54%   |
| BlackPanther  | 7         | 0.54%   |
| EndeavourOS   | 6         | 0.46%   |
| ALT Linux     | 6         | 0.46%   |
| Ubuntu Budgie | 5         | 0.38%   |
| Peppermint    | 4         | 0.31%   |
| Kali          | 4         | 0.31%   |
| Artix         | 4         | 0.31%   |
| Xero          | 3         | 0.23%   |
| Void Linux    | 3         | 0.23%   |
| Slackware     | 3         | 0.23%   |
| LinuxFX       | 3         | 0.23%   |
| CentOS        | 3         | 0.23%   |
| BigLinux      | 3         | 0.23%   |
| SteamOS       | 2         | 0.15%   |
| Solus         | 2         | 0.15%   |
| Reborn OS     | 2         | 0.15%   |
| Mageia        | 2         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 35        | 2.27%   |
| 5.15.0-52-generic        | 25        | 1.62%   |
| 5.16.7-desktop-1omv4003  | 22        | 1.43%   |
| 5.15.0-56-generic        | 22        | 1.43%   |
| 5.4.0-42-generic         | 20        | 1.3%    |
| 5.4.0-58-generic         | 19        | 1.23%   |
| 5.4.0-29-generic         | 14        | 0.91%   |
| 4.15.0-163-generic       | 14        | 0.91%   |
| 5.4.0-94-generic         | 13        | 0.84%   |
| 6.2.6-desktop-1omv2390   | 12        | 0.78%   |
| 5.3.0-46-generic         | 12        | 0.78%   |
| 5.15.0-58-generic        | 12        | 0.78%   |
| 5.4.0-54-generic         | 11        | 0.71%   |
| 5.4.0-48-generic         | 11        | 0.71%   |
| 5.15.0-53-generic        | 11        | 0.71%   |
| 5.11.0-40-generic        | 11        | 0.71%   |
| 6.1.1-desktop-1omv2290   | 10        | 0.65%   |
| 5.4.0-91-generic         | 10        | 0.65%   |
| 5.4.0-65-generic         | 10        | 0.65%   |
| 4.15.0-47-generic        | 10        | 0.65%   |
| 6.1.0-9-amd64            | 9         | 0.58%   |
| 5.4.0-52-generic         | 9         | 0.58%   |
| 5.19.0-35-generic        | 9         | 0.58%   |
| 5.4.0-56-generic         | 8         | 0.52%   |
| 5.4.0-37-generic         | 8         | 0.52%   |
| 5.3.0-42-generic         | 8         | 0.52%   |
| 5.15.0-46-generic        | 8         | 0.52%   |
| 5.13.0-39-generic        | 8         | 0.52%   |
| 5.11.0-38-generic        | 8         | 0.52%   |
| 5.11.0-37-generic        | 8         | 0.52%   |
| 5.0.0-37-generic         | 8         | 0.52%   |
| 5.0.0-13-generic         | 8         | 0.52%   |
| 4.15.0-45-generic        | 8         | 0.52%   |
| 6.0.6-76060006-generic   | 7         | 0.45%   |
| 5.8.0-43-generic         | 7         | 0.45%   |
| 5.4.0-53-generic         | 7         | 0.45%   |
| 5.4.0-47-generic         | 7         | 0.45%   |
| 5.4.0-40-generic         | 7         | 0.45%   |
| 5.3.0-51-generic         | 7         | 0.45%   |
| 5.3.0-45-generic         | 7         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 252       | 17.4%   |
| 5.15.0  | 137       | 9.46%   |
| 4.15.0  | 106       | 7.32%   |
| 5.11.0  | 82        | 5.66%   |
| 5.3.0   | 66        | 4.56%   |
| 5.8.0   | 65        | 4.49%   |
| 5.13.0  | 64        | 4.42%   |
| 5.19.0  | 50        | 3.45%   |
| 5.0.0   | 38        | 2.62%   |
| 5.10.14 | 35        | 2.42%   |
| 4.18.0  | 30        | 2.07%   |
| 5.10.0  | 29        | 2%      |
| 5.16.7  | 23        | 1.59%   |
| 6.2.6   | 14        | 0.97%   |
| 4.19.0  | 14        | 0.97%   |
| 6.1.1   | 12        | 0.83%   |
| 6.1.0   | 11        | 0.76%   |
| 6.2.0   | 10        | 0.69%   |
| 6.0.6   | 7         | 0.48%   |
| 5.9.11  | 7         | 0.48%   |
| 5.10.88 | 7         | 0.48%   |
| 4.9.60  | 7         | 0.48%   |
| 5.18.10 | 6         | 0.41%   |
| 5.17.5  | 6         | 0.41%   |
| 6.0.12  | 5         | 0.35%   |
| 5.18.12 | 5         | 0.35%   |
| 5.14.0  | 5         | 0.35%   |
| 5.12.4  | 5         | 0.35%   |
| 4.9.20  | 5         | 0.35%   |
| 4.18.16 | 5         | 0.35%   |
| 6.3.5   | 4         | 0.28%   |
| 6.1.12  | 4         | 0.28%   |
| 5.8.18  | 4         | 0.28%   |
| 5.17.4  | 4         | 0.28%   |
| 5.17.1  | 4         | 0.28%   |
| 5.16.0  | 4         | 0.28%   |
| 5.15.32 | 4         | 0.28%   |
| 5.14.14 | 4         | 0.28%   |
| 5.11.12 | 4         | 0.28%   |
| 6.3.2   | 3         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 273       | 19.05%  |
| 5.15    | 173       | 12.07%  |
| 4.15    | 106       | 7.4%    |
| 5.10    | 101       | 7.05%   |
| 5.11    | 99        | 6.91%   |
| 5.8     | 86        | 6%      |
| 5.3     | 72        | 5.02%   |
| 5.13    | 71        | 4.95%   |
| 5.19    | 58        | 4.05%   |
| 6.1     | 43        | 3%      |
| 5.0     | 42        | 2.93%   |
| 5.16    | 36        | 2.51%   |
| 4.18    | 36        | 2.51%   |
| 6.2     | 33        | 2.3%    |
| 6.0     | 29        | 2.02%   |
| 5.17    | 20        | 1.4%    |
| 5.14    | 20        | 1.4%    |
| 5.9     | 19        | 1.33%   |
| 5.18    | 17        | 1.19%   |
| 4.19    | 15        | 1.05%   |
| 5.6     | 14        | 0.98%   |
| 4.9     | 14        | 0.98%   |
| 5.7     | 12        | 0.84%   |
| 6.3     | 11        | 0.77%   |
| 5.12    | 11        | 0.77%   |
| 5.5     | 6         | 0.42%   |
| 6.4     | 3         | 0.21%   |
| 4.4     | 2         | 0.14%   |
| 4.10    | 2         | 0.14%   |
| 4.1     | 2         | 0.14%   |
| 5.2     | 1         | 0.07%   |
| 5.1     | 1         | 0.07%   |
| 4.20    | 1         | 0.07%   |
| 4.16    | 1         | 0.07%   |
| 4.14    | 1         | 0.07%   |
| 3.16    | 1         | 0.07%   |
| 3.10    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1198      | 95.08%  |
| i686    | 57        | 4.52%   |
| aarch64 | 3         | 0.24%   |
| armv7l  | 1         | 0.08%   |
| armv6l  | 1         | 0.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| GNOME               | 559       | 42.41%  |
| KDE5                | 211       | 16.01%  |
| Unknown             | 153       | 11.61%  |
| XFCE                | 116       | 8.8%    |
| X-Cinnamon          | 98        | 7.44%   |
| MATE                | 61        | 4.63%   |
| KDE                 | 39        | 2.96%   |
| KDE4                | 12        | 0.91%   |
| Unity               | 11        | 0.83%   |
| Pantheon            | 11        | 0.83%   |
| LXQt                | 11        | 0.83%   |
| Budgie              | 9         | 0.68%   |
| i3                  | 7         | 0.53%   |
| Cinnamon            | 5         | 0.38%   |
| LXDE                | 4         | 0.3%    |
| Openbox             | 2         | 0.15%   |
| GNOME Classic       | 2         | 0.15%   |
| ICEWM               | 1         | 0.08%   |
| hyprland            | 1         | 0.08%   |
| herbstluftwm        | 1         | 0.08%   |
| GNOME Flashback     | 1         | 0.08%   |
| Deepin              | 1         | 0.08%   |
| awesome             | 1         | 0.08%   |
| /usr/bin/startxfce4 | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1026      | 78.8%   |
| Wayland | 158       | 12.14%  |
| Unknown | 89        | 6.84%   |
| Tty     | 29        | 2.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 685       | 52.05%  |
| SDDM    | 182       | 13.83%  |
| LightDM | 151       | 11.47%  |
| GDM3    | 146       | 11.09%  |
| GDM     | 108       | 8.21%   |
| TDM     | 24        | 1.82%   |
| KDM     | 12        | 0.91%   |
| XDM     | 3         | 0.23%   |
| SLiM    | 2         | 0.15%   |
| LXDM    | 2         | 0.15%   |
| Ly      | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 719       | 55.65%  |
| el_GR      | 347       | 26.86%  |
| Unknown    | 145       | 11.22%  |
| en_GB      | 27        | 2.09%   |
| C          | 14        | 1.08%   |
| de_DE      | 13        | 1.01%   |
| ru_RU      | 6         | 0.46%   |
| POSIX      | 3         | 0.23%   |
| it_IT      | 2         | 0.15%   |
| fr_FR      | 2         | 0.15%   |
| en_IE      | 2         | 0.15%   |
| en_CA      | 2         | 0.15%   |
| unm_US     | 1         | 0.08%   |
| pl_PL      | 1         | 0.08%   |
| hu_HU      | 1         | 0.08%   |
| es_ES      | 1         | 0.08%   |
| en_AU      | 1         | 0.08%   |
| en_AG      | 1         | 0.08%   |
| el_GR@euro | 1         | 0.08%   |
| C.UTF8     | 1         | 0.08%   |
| bg_BG      | 1         | 0.08%   |
| anp_IN     | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 748       | 57.85%  |
| EFI  | 545       | 42.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 971       | 74.58%  |
| Overlay | 129       | 9.91%   |
| Btrfs   | 106       | 8.14%   |
| Unknown | 44        | 3.38%   |
| Tmpfs   | 27        | 2.07%   |
| Xfs     | 10        | 0.77%   |
| Zfs     | 8         | 0.61%   |
| F2fs    | 3         | 0.23%   |
| Ext3    | 2         | 0.15%   |
| Ext2    | 2         | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 746       | 57.3%   |
| GPT     | 389       | 29.88%  |
| MBR     | 167       | 12.83%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1081      | 83.93%  |
| Yes       | 207       | 16.07%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 833       | 64.98%  |
| Yes       | 449       | 35.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 205       | 16.27%  |
| ASUSTek Computer        | 185       | 14.68%  |
| Lenovo                  | 181       | 14.37%  |
| Dell                    | 162       | 12.86%  |
| Gigabyte Technology     | 144       | 11.43%  |
| MSI                     | 61        | 4.84%   |
| ASRock                  | 56        | 4.44%   |
| Acer                    | 48        | 3.81%   |
| Sony                    | 30        | 2.38%   |
| Toshiba                 | 28        | 2.22%   |
| Apple                   | 15        | 1.19%   |
| Fujitsu Siemens         | 13        | 1.03%   |
| Fujitsu                 | 12        | 0.95%   |
| Intel                   | 11        | 0.87%   |
| HUAWEI                  | 8         | 0.63%   |
| Unknown                 | 8         | 0.63%   |
| Pegatron                | 7         | 0.56%   |
| Notebook                | 7         | 0.56%   |
| Clevo                   | 6         | 0.48%   |
| Raspberry Pi Foundation | 5         | 0.4%    |
| Samsung Electronics     | 4         | 0.32%   |
| IBM                     | 4         | 0.32%   |
| Foxconn                 | 4         | 0.32%   |
| Chuwi                   | 4         | 0.32%   |
| Teclast                 | 3         | 0.24%   |
| Insyde                  | 3         | 0.24%   |
| Hampoo                  | 3         | 0.24%   |
| Google                  | 3         | 0.24%   |
| ECS                     | 3         | 0.24%   |
| E-shop.gr               | 3         | 0.24%   |
| Valve                   | 2         | 0.16%   |
| Info Quest Technologies | 2         | 0.16%   |
| AOpen                   | 2         | 0.16%   |
| ZOTAC                   | 1         | 0.08%   |
| VIA Technologies        | 1         | 0.08%   |
| VERO                    | 1         | 0.08%   |
| TUXEDO                  | 1         | 0.08%   |
| Timi                    | 1         | 0.08%   |
| Supermicro              | 1         | 0.08%   |
| Schenker                | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| ASUS All Series               | 14        | 1.11%   |
| Unknown                       | 13        | 1.03%   |
| HP Pavilion g6                | 10        | 0.79%   |
| HP Notebook                   | 8         | 0.63%   |
| HP ProDesk 600 G1 SFF         | 7         | 0.56%   |
| HP 255 G7 Notebook PC         | 6         | 0.48%   |
| ASRock B450 Gaming K4         | 6         | 0.48%   |
| Dell OptiPlex 7010            | 5         | 0.4%    |
| Dell Inspiron 3542            | 5         | 0.4%    |
| Dell Inspiron 3537            | 5         | 0.4%    |
| ASUS ROG STRIX B350-F GAMING  | 5         | 0.4%    |
| Pegatron A15                  | 4         | 0.32%   |
| MSI MS-7C02                   | 4         | 0.32%   |
| Lenovo G510 20238             | 4         | 0.32%   |
| HP Pavilion dv7               | 4         | 0.32%   |
| HP Pavilion dv6               | 4         | 0.32%   |
| HP G62                        | 4         | 0.32%   |
| HP Compaq Pro 6300 SFF        | 4         | 0.32%   |
| HP Compaq 8200 Elite SFF PC   | 4         | 0.32%   |
| Gigabyte H61M-S2PV            | 4         | 0.32%   |
| Gigabyte B450 AORUS M         | 4         | 0.32%   |
| Gigabyte A320M-S2H            | 4         | 0.32%   |
| Dell OptiPlex GX520           | 4         | 0.32%   |
| Dell Inspiron 5567            | 4         | 0.32%   |
| Notebook W54_W94_W955TU,-T,-C | 3         | 0.24%   |
| MSI MS-7C56                   | 3         | 0.24%   |
| MSI MS-7A38                   | 3         | 0.24%   |
| Lenovo V15-ADA 82C7           | 3         | 0.24%   |
| Lenovo MIIX 320-10ICR 80XF    | 3         | 0.24%   |
| Lenovo IdeaPad 100-15IBD 80QQ | 3         | 0.24%   |
| Lenovo G50-70 20351           | 3         | 0.24%   |
| Lenovo G40-30 80FY            | 3         | 0.24%   |
| Insyde CherryTrail            | 3         | 0.24%   |
| HUAWEI KLVL-WXX9              | 3         | 0.24%   |
| HP Pavilion Notebook          | 3         | 0.24%   |
| HP Pavilion 15                | 3         | 0.24%   |
| HP 255 G8 Notebook PC         | 3         | 0.24%   |
| Gigabyte Z170-HD3P            | 3         | 0.24%   |
| Gigabyte G41M-Combo           | 3         | 0.24%   |
| Gigabyte G31M-S2L             | 3         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 51        | 4.05%   |
| Lenovo IdeaPad        | 49        | 3.89%   |
| HP Pavilion           | 47        | 3.73%   |
| Lenovo ThinkPad       | 42        | 3.33%   |
| Acer Aspire           | 38        | 3.02%   |
| Dell Latitude         | 37        | 2.94%   |
| HP Compaq             | 36        | 2.86%   |
| Dell OptiPlex         | 29        | 2.3%    |
| Toshiba Satellite     | 24        | 1.9%    |
| Lenovo ThinkCentre    | 22        | 1.75%   |
| ASUS PRIME            | 20        | 1.59%   |
| Dell Precision        | 17        | 1.35%   |
| HP EliteBook          | 14        | 1.11%   |
| HP 255                | 14        | 1.11%   |
| ASUS ROG              | 14        | 1.11%   |
| ASUS All              | 14        | 1.11%   |
| ASUS VivoBook         | 13        | 1.03%   |
| Unknown               | 13        | 1.03%   |
| HP ProBook            | 12        | 0.95%   |
| HP Laptop             | 11        | 0.87%   |
| Dell Vostro           | 10        | 0.79%   |
| Fujitsu LIFEBOOK      | 9         | 0.71%   |
| ASUS TUF              | 9         | 0.71%   |
| HP ProDesk            | 8         | 0.63%   |
| HP Notebook           | 8         | 0.63%   |
| Dell XPS              | 8         | 0.63%   |
| Lenovo Legion         | 7         | 0.56%   |
| HP ENVY               | 7         | 0.56%   |
| Fujitsu Siemens AMILO | 7         | 0.56%   |
| Lenovo Yoga           | 6         | 0.48%   |
| Gigabyte B450         | 6         | 0.48%   |
| ASRock B450           | 6         | 0.48%   |
| RPi Raspberry         | 5         | 0.4%    |
| HP EliteDesk          | 5         | 0.4%    |
| HP 250                | 5         | 0.4%    |
| Gigabyte B550         | 5         | 0.4%    |
| Pegatron A15          | 4         | 0.32%   |
| MSI MS-7C02           | 4         | 0.32%   |
| Lenovo MIIX           | 4         | 0.32%   |
| Lenovo G510           | 4         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 105       | 8.33%   |
| 2019    | 104       | 8.25%   |
| 2018    | 95        | 7.54%   |
| 2012    | 92        | 7.3%    |
| 2008    | 89        | 7.06%   |
| 2017    | 86        | 6.83%   |
| 2011    | 84        | 6.67%   |
| 2020    | 83        | 6.59%   |
| 2009    | 82        | 6.51%   |
| 2014    | 76        | 6.03%   |
| 2015    | 73        | 5.79%   |
| 2007    | 54        | 4.29%   |
| 2010    | 53        | 4.21%   |
| 2016    | 52        | 4.13%   |
| 2021    | 49        | 3.89%   |
| 2006    | 22        | 1.75%   |
| 2005    | 22        | 1.75%   |
| 2022    | 21        | 1.67%   |
| 2023    | 5         | 0.4%    |
| 2004    | 5         | 0.4%    |
| 2003    | 4         | 0.32%   |
| Unknown | 4         | 0.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 679       | 53.89%  |
| Desktop        | 533       | 42.3%   |
| Convertible    | 19        | 1.51%   |
| Tablet         | 8         | 0.63%   |
| All in one     | 8         | 0.63%   |
| Server         | 6         | 0.48%   |
| System on chip | 5         | 0.4%    |
| Mini pc        | 2         | 0.16%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1179      | 92.76%  |
| Enabled  | 92        | 7.24%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1257      | 99.76%  |
| Yes  | 3         | 0.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 312       | 24.32%  |
| 4.01-8.0    | 282       | 21.98%  |
| 8.01-16.0   | 237       | 18.47%  |
| 16.01-24.0  | 204       | 15.9%   |
| 1.01-2.0    | 104       | 8.11%   |
| 32.01-64.0  | 68        | 5.3%    |
| 2.01-3.0    | 38        | 2.96%   |
| 0.51-1.0    | 14        | 1.09%   |
| 24.01-32.0  | 12        | 0.94%   |
| 64.01-256.0 | 11        | 0.86%   |
| 0.01-0.5    | 1         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 552       | 39.6%   |
| 2.01-3.0   | 318       | 22.81%  |
| 4.01-8.0   | 160       | 11.48%  |
| 3.01-4.0   | 151       | 10.83%  |
| 0.51-1.0   | 130       | 9.33%   |
| 8.01-16.0  | 50        | 3.59%   |
| 0.01-0.5   | 24        | 1.72%   |
| 16.01-24.0 | 7         | 0.5%    |
| 32.01-64.0 | 1         | 0.07%   |
| 24.01-32.0 | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 754       | 58.04%  |
| 2      | 329       | 25.33%  |
| 3      | 102       | 7.85%   |
| 4      | 54        | 4.16%   |
| 5      | 26        | 2%      |
| 6      | 14        | 1.08%   |
| 0      | 10        | 0.77%   |
| 7      | 6         | 0.46%   |
| 18     | 1         | 0.08%   |
| 13     | 1         | 0.08%   |
| 12     | 1         | 0.08%   |
| 8      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 667       | 52.56%  |
| Yes       | 602       | 47.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1123      | 88.99%  |
| No        | 139       | 11.01%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 893       | 70.15%  |
| No        | 380       | 29.85%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 653       | 51.18%  |
| No        | 623       | 48.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Greece  | 1260      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Computers | Percent |
|--------------|-----------|---------|
| Athens       | 639       | 46.64%  |
| Thessaloniki | 196       | 14.31%  |
| Heraklion    | 42        | 3.07%   |
| Pátrai      | 34        | 2.48%   |
| Volos        | 22        | 1.61%   |
| Chalcis      | 20        | 1.46%   |
| Kavala       | 19        | 1.39%   |
| Piraeus      | 17        | 1.24%   |
| Larissa      | 16        | 1.17%   |
| Katerini     | 15        | 1.09%   |
| Kalamata     | 12        | 0.88%   |
| Ioannina     | 12        | 0.88%   |
| Chania       | 12        | 0.88%   |
| Trikala      | 11        | 0.8%    |
| Rhodes       | 10        | 0.73%   |
| Chalandri    | 10        | 0.73%   |
| Lamia        | 9         | 0.66%   |
| Serres       | 8         | 0.58%   |
| Drama        | 8         | 0.58%   |
| Veroia       | 7         | 0.51%   |
| Corfu        | 7         | 0.51%   |
| Xanthi       | 6         | 0.44%   |
| Karditsa     | 6         | 0.44%   |
| Kallithea    | 6         | 0.44%   |
| Samos        | 5         | 0.36%   |
| Rethymno     | 5         | 0.36%   |
| Komotini     | 5         | 0.36%   |
| Fira         | 5         | 0.36%   |
| Corinth      | 5         | 0.36%   |
| Agrinio      | 5         | 0.36%   |
| Zakynthos    | 4         | 0.29%   |
| Salamina     | 4         | 0.29%   |
| Paros        | 4         | 0.29%   |
| Mytilene     | 4         | 0.29%   |
| Kozani       | 4         | 0.29%   |
| Kilkis       | 4         | 0.29%   |
| Glyfada      | 4         | 0.29%   |
| Arta         | 4         | 0.29%   |
| Aigaleo      | 4         | 0.29%   |
| Acharnes     | 4         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 344       | 561    | 18.15%  |
| Samsung Electronics         | 272       | 413    | 14.35%  |
| Seagate                     | 254       | 384    | 13.4%   |
| Toshiba                     | 144       | 193    | 7.6%    |
| Kingston                    | 121       | 157    | 6.39%   |
| SanDisk                     | 107       | 143    | 5.65%   |
| Patriot                     | 78        | 98     | 4.12%   |
| Unknown                     | 61        | 102    | 3.22%   |
| Hitachi                     | 48        | 52     | 2.53%   |
| Intenso                     | 41        | 50     | 2.16%   |
| Crucial                     | 40        | 60     | 2.11%   |
| SK hynix                    | 39        | 51     | 2.06%   |
| Intel                       | 33        | 41     | 1.74%   |
| HGST                        | 31        | 45     | 1.64%   |
| Micron Technology           | 20        | 23     | 1.06%   |
| Fujitsu                     | 18        | 19     | 0.95%   |
| Team                        | 17        | 23     | 0.9%    |
| OCZ                         | 16        | 19     | 0.84%   |
| Maxtor                      | 14        | 16     | 0.74%   |
| KIOXIA                      | 14        | 21     | 0.74%   |
| A-DATA Technology           | 14        | 22     | 0.74%   |
| JMicron Technology          | 11        | 21     | 0.58%   |
| PNY                         | 10        | 10     | 0.53%   |
| China                       | 9         | 9      | 0.47%   |
| SPCC                        | 8         | 10     | 0.42%   |
| Phison                      | 8         | 11     | 0.42%   |
| Corsair                     | 7         | 7      | 0.37%   |
| XPG                         | 6         | 8      | 0.32%   |
| Micron/Crucial Technology   | 6         | 7      | 0.32%   |
| Leven                       | 6         | 6      | 0.32%   |
| Gigabyte Technology         | 6         | 8      | 0.32%   |
| Transcend                   | 5         | 5      | 0.26%   |
| Kingston Technology Company | 5         | 6      | 0.26%   |
| Apple                       | 5         | 6      | 0.26%   |
| Phison Electronics          | 4         | 5      | 0.21%   |
| Mushkin                     | 4         | 4      | 0.21%   |
| Emtec                       | 4         | 5      | 0.21%   |
| Unknown                     | 4         | 4      | 0.21%   |
| Verbatim                    | 3         | 4      | 0.16%   |
| Teclast                     | 3         | 3      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 250GB                           | 29        | 1.38%   |
| Unknown MMC Card  32GB                              | 26        | 1.24%   |
| Samsung SSD 860 EVO 500GB                           | 26        | 1.24%   |
| Patriot Burst 120GB SSD                             | 21        | 1%      |
| Samsung SSD 850 EVO 250GB                           | 19        | 0.9%    |
| Patriot Burst 240GB SSD                             | 19        | 0.9%    |
| Kingston SA400S37120G 120GB SSD                     | 19        | 0.9%    |
| Seagate ST500DM002-1BD142 500GB                     | 18        | 0.86%   |
| Kingston SA400S37240G 240GB SSD                     | 18        | 0.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 17        | 0.81%   |
| Toshiba DT01ACA100 1TB                              | 15        | 0.71%   |
| Unknown MMC Card  64GB                              | 14        | 0.67%   |
| Toshiba MQ01ABF050 500GB                            | 14        | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB                      | 14        | 0.67%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 13        | 0.62%   |
| Toshiba DT01ACA050 500GB                            | 13        | 0.62%   |
| Samsung SSD 850 EVO 500GB                           | 13        | 0.62%   |
| SK hynix NVMe SSD Drive 256GB                       | 12        | 0.57%   |
| Seagate ST1000LM035-1RK172 1TB                      | 12        | 0.57%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 11        | 0.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 11        | 0.52%   |
| Patriot Burst 480GB SSD                             | 11        | 0.52%   |
| Kingston SA400S37480G 480GB SSD                     | 10        | 0.48%   |
| Toshiba MQ01ABD100 1TB                              | 9         | 0.43%   |
| Seagate ST500LT012-1DG142 500GB                     | 9         | 0.43%   |
| Samsung NVMe SSD Drive 500GB                        | 9         | 0.43%   |
| Kingston SV300S37A120G 120GB SSD                    | 9         | 0.43%   |
| Crucial CT250MX500SSD1 250GB                        | 9         | 0.43%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 8         | 0.38%   |
| Unknown MMC Card  128GB                             | 8         | 0.38%   |
| Toshiba DT01ACA200 2TB                              | 8         | 0.38%   |
| SanDisk SDSSDA120G 120GB                            | 8         | 0.38%   |
| SanDisk NVMe SSD Drive 256GB                        | 8         | 0.38%   |
| HGST HTS545050A7E680 500GB                          | 8         | 0.38%   |
| SanDisk NVMe SSD Drive 512GB                        | 7         | 0.33%   |
| Samsung SSD 970 EVO Plus 500GB                      | 7         | 0.33%   |
| Samsung SSD 850 EVO 120GB                           | 7         | 0.33%   |
| Samsung NVMe SSD Drive 512GB                        | 7         | 0.33%   |
| Intenso External USB 3.0 1TB                        | 7         | 0.33%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 6         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 288       | 461    | 35.73%  |
| Seagate             | 251       | 379    | 31.14%  |
| Toshiba             | 107       | 142    | 13.28%  |
| Hitachi             | 48        | 52     | 5.96%   |
| HGST                | 31        | 45     | 3.85%   |
| Samsung Electronics | 23        | 29     | 2.85%   |
| Fujitsu             | 18        | 19     | 2.23%   |
| Maxtor              | 14        | 16     | 1.74%   |
| JMicron Technology  | 8         | 15     | 0.99%   |
| Intenso             | 7         | 8      | 0.87%   |
| Apple               | 3         | 3      | 0.37%   |
| Unknown             | 1         | 1      | 0.12%   |
| Quantum             | 1         | 1      | 0.12%   |
| Min Yi U            | 1         | 2      | 0.12%   |
| Inateck             | 1         | 1      | 0.12%   |
| IBM/Hitachi         | 1         | 1      | 0.12%   |
| IBM-ESXS            | 1         | 3      | 0.12%   |
| Hewlett-Packard     | 1         | 1      | 0.12%   |
| External            | 1         | 2      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 161       | 221    | 21.88%  |
| Kingston            | 96        | 126    | 13.04%  |
| SanDisk             | 78        | 104    | 10.6%   |
| Patriot             | 77        | 97     | 10.46%  |
| WDC                 | 51        | 78     | 6.93%   |
| Crucial             | 38        | 58     | 5.16%   |
| Intenso             | 30        | 38     | 4.08%   |
| Toshiba             | 24        | 34     | 3.26%   |
| Intel               | 20        | 24     | 2.72%   |
| Team                | 17        | 23     | 2.31%   |
| OCZ                 | 15        | 18     | 2.04%   |
| A-DATA Technology   | 13        | 21     | 1.77%   |
| Micron Technology   | 12        | 13     | 1.63%   |
| PNY                 | 10        | 10     | 1.36%   |
| China               | 9         | 9      | 1.22%   |
| SPCC                | 8         | 10     | 1.09%   |
| SK hynix            | 6         | 6      | 0.82%   |
| Leven               | 6         | 6      | 0.82%   |
| Gigabyte Technology | 6         | 8      | 0.82%   |
| Corsair             | 5         | 5      | 0.68%   |
| Transcend           | 4         | 4      | 0.54%   |
| Mushkin             | 4         | 4      | 0.54%   |
| Emtec               | 4         | 5      | 0.54%   |
| Verbatim            | 3         | 4      | 0.41%   |
| Teclast             | 3         | 3      | 0.41%   |
| LITEONIT            | 3         | 3      | 0.41%   |
| GOODRAM             | 3         | 5      | 0.41%   |
| Apple               | 3         | 3      | 0.41%   |
| Apacer              | 3         | 3      | 0.41%   |
| Unknown             | 3         | 3      | 0.41%   |
| Plextor             | 2         | 2      | 0.27%   |
| Platinet            | 2         | 2      | 0.27%   |
| LITEON              | 2         | 2      | 0.27%   |
| Drevo               | 2         | 2      | 0.27%   |
| WDC WDS             | 1         | 1      | 0.14%   |
| USB30               | 1         | 1      | 0.14%   |
| Unknown             | 1         | 4      | 0.14%   |
| Seagate             | 1         | 1      | 0.14%   |
| OCZ-AGIL            | 1         | 1      | 0.14%   |
| Netac               | 1         | 1      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 684       | 1181   | 40.52%  |
| SSD     | 635       | 972    | 37.62%  |
| NVMe    | 296       | 425    | 17.54%  |
| MMC     | 60        | 102    | 3.55%   |
| Unknown | 13        | 20     | 0.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1039      | 2092   | 71.75%  |
| NVMe | 296       | 425    | 20.44%  |
| MMC  | 60        | 102    | 4.14%   |
| SAS  | 53        | 81     | 3.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 880       | 1480   | 66.92%  |
| 0.51-1.0   | 309       | 467    | 23.5%   |
| 1.01-2.0   | 69        | 109    | 5.25%   |
| 3.01-4.0   | 23        | 35     | 1.75%   |
| 2.01-3.0   | 19        | 34     | 1.44%   |
| 4.01-10.0  | 12        | 24     | 0.91%   |
| 10.01-20.0 | 3         | 4      | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 409       | 30.36%  |
| 251-500        | 257       | 19.08%  |
| 501-1000       | 151       | 11.21%  |
| 51-100         | 109       | 8.09%   |
| 1-20           | 103       | 7.65%   |
| 1001-2000      | 101       | 7.5%    |
| 21-50          | 72        | 5.35%   |
| More than 3000 | 56        | 4.16%   |
| Unknown        | 56        | 4.16%   |
| 2001-3000      | 33        | 2.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 526       | 37.95%  |
| 21-50          | 233       | 16.81%  |
| 51-100         | 162       | 11.69%  |
| 101-250        | 143       | 10.32%  |
| 251-500        | 106       | 7.65%   |
| 501-1000       | 78        | 5.63%   |
| Unknown        | 56        | 4.04%   |
| 1001-2000      | 48        | 3.46%   |
| More than 3000 | 26        | 1.88%   |
| 2001-3000      | 8         | 0.58%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB       | 4         | 4      | 3.64%   |
| Seagate ST500DM002-1BD142 500GB  | 2         | 2      | 1.82%   |
| Seagate ST3500320AS 500GB        | 2         | 2      | 1.82%   |
| SanDisk SSD PLUS 240GB           | 2         | 2      | 1.82%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1         | 1      | 0.91%   |
| WDC WD800JD-23LSA0 80GB          | 1         | 1      | 0.91%   |
| WDC WD800JB-00JJC0 80GB          | 1         | 2      | 0.91%   |
| WDC WD6400AAKS-65A7B0 640GB      | 1         | 1      | 0.91%   |
| WDC WD5000LPVT-00FMCT0 500GB     | 1         | 1      | 0.91%   |
| WDC WD5000LPCX-24VHAT0 500GB     | 1         | 1      | 0.91%   |
| WDC WD5000BPVT-60HXZT1 500GB     | 1         | 1      | 0.91%   |
| WDC WD5000AAVS-22G9B1 500GB      | 1         | 1      | 0.91%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1         | 1      | 0.91%   |
| WDC WD5000AAKX-603CA0 500GB      | 1         | 1      | 0.91%   |
| WDC WD5000AAKB-00H8A0 500GB      | 1         | 1      | 0.91%   |
| WDC WD3200BEVT-26ZCT0 320GB      | 1         | 1      | 0.91%   |
| WDC WD3200BEVT-00A0RT0 320GB     | 1         | 1      | 0.91%   |
| WDC WD30EZRZ-00GXCB0 3TB         | 1         | 1      | 0.91%   |
| WDC WD2500YS-01SHB1 256GB        | 1         | 2      | 0.91%   |
| WDC WD2500BEVT-22A23T0 250GB     | 1         | 1      | 0.91%   |
| WDC WD2500AAKX-083CA1 250GB      | 1         | 1      | 0.91%   |
| WDC WD20PURX-64P6ZY0 2TB         | 1         | 1      | 0.91%   |
| WDC WD20EARS-00MVWB0 2TB         | 1         | 1      | 0.91%   |
| WDC WD2002FAEX-007BA0 2TB        | 1         | 2      | 0.91%   |
| WDC WD1600BEVS-22RST0 160GB      | 1         | 1      | 0.91%   |
| WDC WD1600AAJS-22L7A0 160GB      | 1         | 1      | 0.91%   |
| WDC WD1200JD-00HBB0 120GB        | 1         | 2      | 0.91%   |
| WDC WD10JPVX-22JC3T0 1TB         | 1         | 1      | 0.91%   |
| WDC WD10EZEX-60WN4A1 1TB         | 1         | 3      | 0.91%   |
| WDC WD10EZEX-60WN4A0 1TB         | 1         | 1      | 0.91%   |
| WDC WD10EALX-009BA0 1TB          | 1         | 1      | 0.91%   |
| WDC WD10EADS-00M2B0 1TB          | 1         | 1      | 0.91%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 1         | 1      | 0.91%   |
| Toshiba MQ02ABF050H 500GB        | 1         | 1      | 0.91%   |
| Toshiba MQ01ACF050 500GB         | 1         | 1      | 0.91%   |
| Toshiba MQ01ABD100M 1TB          | 1         | 1      | 0.91%   |
| Toshiba MQ01ABD050 500GB         | 1         | 3      | 0.91%   |
| Toshiba MK5055GSX 500GB          | 1         | 1      | 0.91%   |
| Toshiba MK3263GSX 320GB          | 1         | 1      | 0.91%   |
| Toshiba MK1665GSX H 160GB        | 1         | 1      | 0.91%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 30     | 24.76%  |
| WDC                 | 25        | 35     | 23.81%  |
| Toshiba             | 9         | 12     | 8.57%   |
| Hitachi             | 7         | 7      | 6.67%   |
| HGST                | 6         | 12     | 5.71%   |
| SanDisk             | 4         | 4      | 3.81%   |
| Samsung Electronics | 4         | 4      | 3.81%   |
| Micron Technology   | 3         | 3      | 2.86%   |
| Maxtor              | 3         | 3      | 2.86%   |
| Corsair             | 3         | 3      | 2.86%   |
| SK hynix            | 2         | 2      | 1.9%    |
| Patriot             | 2         | 2      | 1.9%    |
| Kingston            | 2         | 2      | 1.9%    |
| Intel               | 2         | 2      | 1.9%    |
| Crucial             | 2         | 3      | 1.9%    |
| OCZ-AGIL            | 1         | 1      | 0.95%   |
| Intenso             | 1         | 1      | 0.95%   |
| Fujitsu             | 1         | 1      | 0.95%   |
| China               | 1         | 1      | 0.95%   |
| A-DATA Technology   | 1         | 1      | 0.95%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 30     | 33.77%  |
| WDC                 | 24        | 34     | 31.17%  |
| Toshiba             | 9         | 12     | 11.69%  |
| Hitachi             | 7         | 7      | 9.09%   |
| HGST                | 6         | 12     | 7.79%   |
| Maxtor              | 3         | 3      | 3.9%    |
| Samsung Electronics | 1         | 1      | 1.3%    |
| Fujitsu             | 1         | 1      | 1.3%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 70        | 100    | 71.43%  |
| SSD  | 24        | 25     | 24.49%  |
| NVMe | 4         | 4      | 4.08%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB | 1         | 1      | 50%     |
| Mushkin MKNSSDCR120GB-7   | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Mushkin | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 846       | 1754   | 62.21%  |
| Works    | 418       | 815    | 30.74%  |
| Malfunc  | 94        | 129    | 6.91%   |
| Failed   | 2         | 2      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 828       | 53.59%  |
| AMD                              | 280       | 18.12%  |
| Samsung Electronics              | 111       | 7.18%   |
| SanDisk                          | 41        | 2.65%   |
| JMicron Technology               | 39        | 2.52%   |
| SK hynix                         | 32        | 2.07%   |
| Kingston Technology Company      | 31        | 2.01%   |
| Nvidia                           | 26        | 1.68%   |
| Marvell Technology Group         | 24        | 1.55%   |
| ASMedia Technology               | 18        | 1.17%   |
| KIOXIA                           | 16        | 1.04%   |
| Toshiba America Info Systems     | 14        | 0.91%   |
| Phison Electronics               | 14        | 0.91%   |
| VIA Technologies                 | 10        | 0.65%   |
| ADATA Technology                 | 9         | 0.58%   |
| Micron Technology                | 8         | 0.52%   |
| Silicon Image                    | 7         | 0.45%   |
| Micron/Crucial Technology        | 7         | 0.45%   |
| Silicon Motion                   | 5         | 0.32%   |
| Union Memory (Shenzhen)          | 4         | 0.26%   |
| Realtek Semiconductor            | 3         | 0.19%   |
| LSI Logic / Symbios Logic        | 3         | 0.19%   |
| Broadcom / LSI                   | 3         | 0.19%   |
| Silicon Integrated Systems [SiS] | 2         | 0.13%   |
| Seagate Technology               | 2         | 0.13%   |
| O2 Micro                         | 2         | 0.13%   |
| Solid State Storage Technology   | 1         | 0.06%   |
| Promise Technology               | 1         | 0.06%   |
| OCZ Technology Group             | 1         | 0.06%   |
| Lite-On Technology               | 1         | 0.06%   |
| Integrated Technology Express    | 1         | 0.06%   |
| INNOGRIT                         | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 197       | 10.47%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 71        | 3.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 63        | 3.35%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 51        | 2.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 51        | 2.71%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 49        | 2.6%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 46        | 2.44%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 42        | 2.23%   |
| AMD 400 Series Chipset SATA Controller                                         | 38        | 2.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 36        | 1.91%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 36        | 1.91%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 31        | 1.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 28        | 1.49%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 27        | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 27        | 1.43%   |
| Samsung NVMe SSD Controller 980                                                | 26        | 1.38%   |
| JMicron JMB363 SATA/IDE Controller                                             | 25        | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 25        | 1.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 25        | 1.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 24        | 1.28%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 21        | 1.12%   |
| Intel Volume Management Device NVMe RAID Controller                            | 20        | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 19        | 1.01%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 18        | 0.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 17        | 0.9%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 17        | 0.9%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 16        | 0.85%   |
| AMD 300 Series Chipset SATA Controller                                         | 16        | 0.85%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 15        | 0.8%    |
| Intel SATA Controller [RAID mode]                                              | 15        | 0.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 15        | 0.8%    |
| AMD 500 Series Chipset SATA Controller                                         | 15        | 0.8%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 14        | 0.74%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 14        | 0.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 13        | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 13        | 0.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 13        | 0.69%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 13        | 0.69%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 13        | 0.69%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 12        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 904       | 56.93%  |
| NVMe | 303       | 19.08%  |
| IDE  | 296       | 18.64%  |
| RAID | 77        | 4.85%   |
| SAS  | 6         | 0.38%   |
| SCSI | 2         | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 905       | 71.83%  |
| AMD          | 349       | 27.7%   |
| ARM          | 5         | 0.4%    |
| CentaurHauls | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 16        | 1.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 14        | 1.11%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 14        | 1.11%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 12        | 0.95%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 11        | 0.87%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 10        | 0.79%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 10        | 0.79%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 9         | 0.71%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 9         | 0.71%   |
| Intel Pentium 4 CPU 3.00GHz                   | 8         | 0.63%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 8         | 0.63%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 8         | 0.63%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 8         | 0.63%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 8         | 0.63%   |
| AMD FX-6300 Six-Core Processor                | 8         | 0.63%   |
| Intel Pentium 4 CPU 3.20GHz                   | 7         | 0.55%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 0.55%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 7         | 0.55%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 7         | 0.55%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 7         | 0.55%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 7         | 0.55%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 0.55%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 7         | 0.55%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 0.47%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 6         | 0.47%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 6         | 0.47%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 6         | 0.47%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 6         | 0.47%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 6         | 0.47%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 6         | 0.47%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 6         | 0.47%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 6         | 0.47%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 6         | 0.47%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz          | 6         | 0.47%   |
| Intel Celeron CPU G1840 @ 2.80GHz             | 6         | 0.47%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 6         | 0.47%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 6         | 0.47%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 6         | 0.47%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 6         | 0.47%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 6         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 224       | 17.76%  |
| Intel Core i7           | 161       | 12.77%  |
| Intel Core i3           | 102       | 8.09%   |
| AMD Ryzen 5             | 95        | 7.53%   |
| Intel Core 2 Duo        | 88        | 6.98%   |
| Intel Celeron           | 66        | 5.23%   |
| AMD Ryzen 7             | 55        | 4.36%   |
| Other                   | 54        | 4.28%   |
| Intel Pentium           | 42        | 3.33%   |
| Intel Atom              | 38        | 3.01%   |
| AMD Ryzen 3             | 26        | 2.06%   |
| Intel Core 2 Quad       | 25        | 1.98%   |
| Intel Pentium 4         | 20        | 1.59%   |
| Intel Xeon              | 19        | 1.51%   |
| Intel Pentium Dual-Core | 19        | 1.51%   |
| AMD FX                  | 18        | 1.43%   |
| Intel Core 2            | 17        | 1.35%   |
| AMD Athlon 64 X2        | 17        | 1.35%   |
| AMD Ryzen 9             | 13        | 1.03%   |
| AMD A8                  | 13        | 1.03%   |
| AMD A10                 | 12        | 0.95%   |
| AMD A6                  | 11        | 0.87%   |
| AMD Phenom II X4        | 10        | 0.79%   |
| AMD A4                  | 10        | 0.79%   |
| AMD E1                  | 9         | 0.71%   |
| Intel Pentium Dual      | 8         | 0.63%   |
| Intel Pentium D         | 6         | 0.48%   |
| Intel Genuine           | 6         | 0.48%   |
| AMD Athlon              | 6         | 0.48%   |
| Intel Pentium M         | 5         | 0.4%    |
| Intel Celeron M         | 5         | 0.4%    |
| AMD E                   | 5         | 0.4%    |
| Intel Celeron Dual-Core | 4         | 0.32%   |
| AMD Phenom II X6        | 4         | 0.32%   |
| AMD Phenom              | 4         | 0.32%   |
| AMD Sempron             | 3         | 0.24%   |
| AMD Ryzen 7 PRO         | 3         | 0.24%   |
| Intel Pentium Gold      | 2         | 0.16%   |
| Intel Core i9           | 2         | 0.16%   |
| ARM BCM                 | 2         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 565       | 44.81%  |
| 4       | 421       | 33.39%  |
| 6       | 101       | 8.01%   |
| 8       | 64        | 5.08%   |
| 1       | 63        | 5%      |
| 12      | 14        | 1.11%   |
| 16      | 11        | 0.87%   |
| 3       | 11        | 0.87%   |
| 10      | 5         | 0.4%    |
| 14      | 3         | 0.24%   |
| 24      | 1         | 0.08%   |
| 20      | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1250      | 99.21%  |
| 2       | 8         | 0.63%   |
| 4       | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 699       | 55.48%  |
| 1       | 558       | 44.29%  |
| 8       | 1         | 0.08%   |
| 4       | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1208      | 95.57%  |
| 32-bit         | 35        | 2.77%   |
| Unknown        | 19        | 1.5%    |
| 64-bit         | 2         | 0.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 307       | 23.42%  |
| 0x206a7    | 72        | 5.49%   |
| 0x306c3    | 71        | 5.42%   |
| 0x306a9    | 60        | 4.58%   |
| 0x1067a    | 53        | 4.04%   |
| 0x40651    | 29        | 2.21%   |
| 0x10676    | 25        | 1.91%   |
| 0x806ea    | 23        | 1.75%   |
| 0x6fd      | 23        | 1.75%   |
| 0x08108109 | 23        | 1.75%   |
| 0x506e3    | 21        | 1.6%    |
| 0x906ea    | 20        | 1.53%   |
| 0x406c4    | 17        | 1.3%    |
| 0x30678    | 17        | 1.3%    |
| 0x08108102 | 17        | 1.3%    |
| 0x0800820d | 17        | 1.3%    |
| 0x806c1    | 16        | 1.22%   |
| 0x906e9    | 15        | 1.14%   |
| 0x806e9    | 15        | 1.14%   |
| 0x306d4    | 15        | 1.14%   |
| 0x506c9    | 13        | 0.99%   |
| 0x806ec    | 12        | 0.92%   |
| 0x6f6      | 12        | 0.92%   |
| 0x106c2    | 11        | 0.84%   |
| 0x06000852 | 11        | 0.84%   |
| 0x906ed    | 10        | 0.76%   |
| 0x406e3    | 10        | 0.76%   |
| 0x20655    | 10        | 0.76%   |
| 0x106e5    | 10        | 0.76%   |
| 0x0a50000c | 10        | 0.76%   |
| 0x08701021 | 10        | 0.76%   |
| 0x0810100b | 10        | 0.76%   |
| 0xf43      | 9         | 0.69%   |
| 0x6fb      | 9         | 0.69%   |
| 0x406c3    | 9         | 0.69%   |
| 0x20652    | 9         | 0.69%   |
| 0x05000119 | 9         | 0.69%   |
| 0x08600106 | 8         | 0.61%   |
| 0x08600104 | 8         | 0.61%   |
| 0x06003106 | 8         | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 132       | 10.45%  |
| Haswell          | 119       | 9.42%   |
| Penryn           | 107       | 8.47%   |
| SandyBridge      | 86        | 6.81%   |
| IvyBridge        | 81        | 6.41%   |
| Zen+             | 78        | 6.18%   |
| Core             | 68        | 5.38%   |
| Silvermont       | 51        | 4.04%   |
| Skylake          | 45        | 3.56%   |
| Zen 3            | 39        | 3.09%   |
| Zen 2            | 36        | 2.85%   |
| Zen              | 36        | 2.85%   |
| Unknown          | 29        | 2.3%    |
| Westmere         | 28        | 2.22%   |
| NetBurst         | 27        | 2.14%   |
| K10              | 27        | 2.14%   |
| Piledriver       | 25        | 1.98%   |
| K8 Hammer        | 24        | 1.9%    |
| TigerLake        | 23        | 1.82%   |
| Nehalem          | 19        | 1.5%    |
| Broadwell        | 19        | 1.5%    |
| Excavator        | 18        | 1.43%   |
| CometLake        | 17        | 1.35%   |
| P6               | 15        | 1.19%   |
| Bonnell          | 15        | 1.19%   |
| Goldmont         | 14        | 1.11%   |
| Bobcat           | 13        | 1.03%   |
| Alderlake Hybrid | 12        | 0.95%   |
| Puma             | 11        | 0.87%   |
| IceLake          | 11        | 0.87%   |
| Steamroller      | 10        | 0.79%   |
| Goldmont plus    | 9         | 0.71%   |
| K8 & K10 hybrid  | 6         | 0.48%   |
| K10 Llano        | 6         | 0.48%   |
| K6               | 3         | 0.24%   |
| Jaguar           | 3         | 0.24%   |
| Bulldozer        | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 626       | 43.38%  |
| AMD                              | 415       | 28.76%  |
| Nvidia                           | 393       | 27.23%  |
| VIA Technologies                 | 3         | 0.21%   |
| Matrox Electronics Systems       | 3         | 0.21%   |
| Silicon Integrated Systems [SiS] | 2         | 0.14%   |
| Conexant Systems                 | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 69        | 4.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 49        | 3.23%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 39        | 2.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 31        | 2.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 31        | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 30        | 1.98%   |
| Intel UHD Graphics 620                                                                   | 27        | 1.78%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 25        | 1.65%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 23        | 1.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 22        | 1.45%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 22        | 1.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 21        | 1.38%   |
| Intel HD Graphics 620                                                                    | 21        | 1.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 20        | 1.32%   |
| AMD Renoir                                                                               | 20        | 1.32%   |
| Intel HD Graphics 530                                                                    | 18        | 1.19%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 18        | 1.19%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 17        | 1.12%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 16        | 1.05%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 15        | 0.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 15        | 0.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 15        | 0.99%   |
| Intel HD Graphics 5500                                                                   | 15        | 0.99%   |
| Intel Core Processor Integrated Graphics Controller                                      | 15        | 0.99%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 15        | 0.99%   |
| Nvidia GT218 [GeForce 210]                                                               | 13        | 0.86%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 13        | 0.86%   |
| Intel HD Graphics 500                                                                    | 13        | 0.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 0.79%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 12        | 0.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 0.73%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 0.73%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 0.73%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 11        | 0.73%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 11        | 0.73%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 10        | 0.66%   |
| Intel HD Graphics 630                                                                    | 10        | 0.66%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 10        | 0.66%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 9         | 0.59%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| 1 x Intel                      | 455       | 35.88%  |
| 1 x AMD                        | 329       | 25.95%  |
| 1 x Nvidia                     | 259       | 20.43%  |
| Intel + Nvidia                 | 117       | 9.23%   |
| Intel + AMD                    | 42        | 3.31%   |
| 2 x AMD                        | 30        | 2.37%   |
| AMD + Nvidia                   | 13        | 1.03%   |
| Other                          | 9         | 0.71%   |
| 2 x Nvidia                     | 3         | 0.24%   |
| 1 x VIA                        | 3         | 0.24%   |
| 1 x Matrox                     | 3         | 0.24%   |
| 2 x Intel                      | 2         | 0.16%   |
| 1 x SiS                        | 2         | 0.16%   |
| 2 x AMD + 1 x Conexant Systems | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1033      | 81.08%  |
| Proprietary | 194       | 15.23%  |
| Unknown     | 47        | 3.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 628       | 48.23%  |
| 1.01-2.0   | 214       | 16.44%  |
| 0.01-0.5   | 194       | 14.9%   |
| 0.51-1.0   | 113       | 8.68%   |
| 3.01-4.0   | 82        | 6.3%    |
| 7.01-8.0   | 34        | 2.61%   |
| 5.01-6.0   | 24        | 1.84%   |
| 8.01-16.0  | 7         | 0.54%   |
| 2.01-3.0   | 6         | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 200       | 15.09%  |
| Goldstar                | 157       | 11.85%  |
| LG Display              | 133       | 10.04%  |
| AU Optronics            | 123       | 9.28%   |
| BOE                     | 106       | 8%      |
| Chimei Innolux          | 93        | 7.02%   |
| Dell                    | 75        | 5.66%   |
| Philips                 | 39        | 2.94%   |
| Hewlett-Packard         | 30        | 2.26%   |
| LG Electronics          | 25        | 1.89%   |
| Chi Mei Optoelectronics | 25        | 1.89%   |
| AOC                     | 22        | 1.66%   |
| ViewSonic               | 20        | 1.51%   |
| Ancor Communications    | 18        | 1.36%   |
| Sony                    | 17        | 1.28%   |
| BenQ                    | 17        | 1.28%   |
| LG Philips              | 15        | 1.13%   |
| Lenovo                  | 14        | 1.06%   |
| Apple                   | 14        | 1.06%   |
| Eizo                    | 13        | 0.98%   |
| Sharp                   | 12        | 0.91%   |
| Vestel Elektronik       | 10        | 0.75%   |
| Iiyama                  | 10        | 0.75%   |
| NEC Computers           | 9         | 0.68%   |
| InfoVision              | 8         | 0.6%    |
| Unknown                 | 7         | 0.53%   |
| Mi                      | 7         | 0.53%   |
| CPT                     | 7         | 0.53%   |
| PANDA                   | 6         | 0.45%   |
| JRY                     | 6         | 0.45%   |
| HannStar                | 6         | 0.45%   |
| Fujitsu Siemens         | 6         | 0.45%   |
| Belinea                 | 6         | 0.45%   |
| ASUSTek Computer        | 6         | 0.45%   |
| Acer                    | 6         | 0.45%   |
| Medion                  | 4         | 0.3%    |
| CSO                     | 4         | 0.3%    |
| Quanta Display          | 3         | 0.23%   |
| Toshiba                 | 2         | 0.15%   |
| Nvidia                  | 2         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 14        | 1.03%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 12        | 0.88%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 10        | 0.74%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 10        | 0.74%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 8         | 0.59%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 7         | 0.51%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 7         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 7         | 0.51%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 7         | 0.51%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch           | 6         | 0.44%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 6         | 0.44%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch              | 6         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 6         | 0.44%   |
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 338x270mm 17.0-inch         | 5         | 0.37%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch     | 5         | 0.37%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 5         | 0.37%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 5         | 0.37%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 5         | 0.37%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 5         | 0.37%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5         | 0.37%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                  | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch       | 5         | 0.37%   |
| Samsung Electronics T23B350 SAM093B 1920x1080 510x287mm 23.0-inch     | 4         | 0.29%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 4         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 4         | 0.29%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 4         | 0.29%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 4         | 0.29%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 4         | 0.29%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 4         | 0.29%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 4         | 0.29%   |
| Dell S2715H DEL40BB 1920x1080 598x336mm 27.0-inch                     | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 0.29%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 4         | 0.29%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 4         | 0.29%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 4         | 0.29%   |
| Samsung Electronics S27E390 SAM0C1C 1920x1080 598x336mm 27.0-inch     | 3         | 0.22%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 3         | 0.22%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 3         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 547       | 43.24%  |
| 1366x768 (WXGA)    | 260       | 20.55%  |
| 1280x1024 (SXGA)   | 73        | 5.77%   |
| 3840x2160 (4K)     | 51        | 4.03%   |
| 1280x800 (WXGA)    | 51        | 4.03%   |
| 1680x1050 (WSXGA+) | 48        | 3.79%   |
| 2560x1440 (QHD)    | 42        | 3.32%   |
| 1600x900 (HD+)     | 42        | 3.32%   |
| 1440x900 (WXGA+)   | 31        | 2.45%   |
| 1920x1200 (WUXGA)  | 20        | 1.58%   |
| 1360x768           | 12        | 0.95%   |
| 2560x1080          | 11        | 0.87%   |
| 1024x768 (XGA)     | 11        | 0.87%   |
| 1024x600           | 9         | 0.71%   |
| Unknown            | 9         | 0.71%   |
| 1600x1200          | 8         | 0.63%   |
| 3440x1440          | 6         | 0.47%   |
| 3840x1080          | 5         | 0.4%    |
| 2880x1800          | 4         | 0.32%   |
| 2160x1440          | 4         | 0.32%   |
| 2560x1600          | 2         | 0.16%   |
| 2048x1152          | 2         | 0.16%   |
| 1920x540           | 2         | 0.16%   |
| 800x1280           | 1         | 0.08%   |
| 5120x1440          | 1         | 0.08%   |
| 4864x2160          | 1         | 0.08%   |
| 4480x1080          | 1         | 0.08%   |
| 3840x2400          | 1         | 0.08%   |
| 3600x1080          | 1         | 0.08%   |
| 3200x1800 (QHD+)   | 1         | 0.08%   |
| 3072x1920          | 1         | 0.08%   |
| 3000x1920          | 1         | 0.08%   |
| 2960x1050          | 1         | 0.08%   |
| 2624x900           | 1         | 0.08%   |
| 2288x1287          | 1         | 0.08%   |
| 1680x945           | 1         | 0.08%   |
| 1280x768           | 1         | 0.08%   |
| 1024x576           | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 386       | 29.09%  |
| 23      | 101       | 7.61%   |
| 21      | 97        | 7.31%   |
| 17      | 85        | 6.41%   |
| 27      | 84        | 6.33%   |
| 13      | 81        | 6.1%    |
| 14      | 73        | 5.5%    |
| 24      | 69        | 5.2%    |
| Unknown | 69        | 5.2%    |
| 19      | 48        | 3.62%   |
| 18      | 29        | 2.19%   |
| 20      | 28        | 2.11%   |
| 31      | 22        | 1.66%   |
| 22      | 22        | 1.66%   |
| 34      | 17        | 1.28%   |
| 12      | 16        | 1.21%   |
| 84      | 13        | 0.98%   |
| 11      | 13        | 0.98%   |
| 10      | 11        | 0.83%   |
| 72      | 7         | 0.53%   |
| 40      | 6         | 0.45%   |
| 16      | 6         | 0.45%   |
| 54      | 5         | 0.38%   |
| 33      | 5         | 0.38%   |
| 32      | 4         | 0.3%    |
| 25      | 4         | 0.3%    |
| 60      | 3         | 0.23%   |
| 42      | 3         | 0.23%   |
| 8       | 3         | 0.23%   |
| 65      | 2         | 0.15%   |
| 49      | 2         | 0.15%   |
| 47      | 2         | 0.15%   |
| 142     | 1         | 0.08%   |
| 48      | 1         | 0.08%   |
| 46      | 1         | 0.08%   |
| 44      | 1         | 0.08%   |
| 39      | 1         | 0.08%   |
| 37      | 1         | 0.08%   |
| 36      | 1         | 0.08%   |
| 29      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 538       | 41.32%  |
| 501-600        | 228       | 17.51%  |
| 401-500        | 195       | 14.98%  |
| 351-400        | 86        | 6.61%   |
| 201-300        | 78        | 5.99%   |
| Unknown        | 69        | 5.3%    |
| 601-700        | 28        | 2.15%   |
| 701-800        | 27        | 2.07%   |
| 1501-2000      | 20        | 1.54%   |
| 1001-1500      | 16        | 1.23%   |
| 801-900        | 8         | 0.61%   |
| 901-1000       | 4         | 0.31%   |
| 101-200        | 3         | 0.23%   |
| More than 2000 | 1         | 0.08%   |
| 1-100          | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 872       | 72.49%  |
| 16/10   | 146       | 12.14%  |
| 5/4     | 61        | 5.07%   |
| Unknown | 61        | 5.07%   |
| 4/3     | 24        | 2%      |
| 21/9    | 16        | 1.33%   |
| 3/2     | 10        | 0.83%   |
| 6/5     | 9         | 0.75%   |
| 32/9    | 2         | 0.17%   |
| 1.00    | 1         | 0.08%   |
| 0.67    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 385       | 29.32%  |
| 201-250        | 244       | 18.58%  |
| 81-90          | 125       | 9.52%   |
| 151-200        | 93        | 7.08%   |
| 301-350        | 85        | 6.47%   |
| Unknown        | 69        | 5.26%   |
| 141-150        | 59        | 4.49%   |
| 351-500        | 48        | 3.66%   |
| 121-130        | 39        | 2.97%   |
| More than 1000 | 33        | 2.51%   |
| 71-80          | 30        | 2.28%   |
| 251-300        | 26        | 1.98%   |
| 501-1000       | 18        | 1.37%   |
| 61-70          | 14        | 1.07%   |
| 51-60          | 13        | 0.99%   |
| 41-50          | 11        | 0.84%   |
| 131-140        | 10        | 0.76%   |
| 1-40           | 4         | 0.3%    |
| 111-120        | 4         | 0.3%    |
| 91-100         | 3         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 474       | 37.5%   |
| 101-120       | 348       | 27.53%  |
| 121-160       | 288       | 22.78%  |
| Unknown       | 69        | 5.46%   |
| 161-240       | 39        | 3.09%   |
| 1-50          | 32        | 2.53%   |
| More than 240 | 14        | 1.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1057      | 81.56%  |
| 2     | 160       | 12.35%  |
| 0     | 59        | 4.55%   |
| 3     | 18        | 1.39%   |
| 4     | 2         | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 730       | 38.79%  |
| Intel                                 | 503       | 26.73%  |
| Qualcomm Atheros                      | 220       | 11.69%  |
| Broadcom                              | 109       | 5.79%   |
| Marvell Technology Group              | 43        | 2.28%   |
| TP-Link                               | 42        | 2.23%   |
| Ralink Technology                     | 35        | 1.86%   |
| Ralink                                | 25        | 1.33%   |
| Broadcom Limited                      | 24        | 1.28%   |
| Nvidia                                | 21        | 1.12%   |
| MediaTek                              | 18        | 0.96%   |
| Qualcomm Atheros Communications       | 10        | 0.53%   |
| VIA Technologies                      | 8         | 0.43%   |
| D-Link                                | 7         | 0.37%   |
| Xiaomi                                | 6         | 0.32%   |
| ASIX Electronics                      | 6         | 0.32%   |
| Dell                                  | 5         | 0.27%   |
| Sierra Wireless                       | 4         | 0.21%   |
| NetGear                               | 4         | 0.21%   |
| Microsoft                             | 4         | 0.21%   |
| Huawei Technologies                   | 4         | 0.21%   |
| Ericsson Business Mobile Networks     | 4         | 0.21%   |
| ASUSTek Computer                      | 4         | 0.21%   |
| JMicron Technology                    | 3         | 0.16%   |
| Hewlett-Packard                       | 3         | 0.16%   |
| Belkin Components                     | 3         | 0.16%   |
| Silicon Integrated Systems [SiS]      | 2         | 0.11%   |
| Motorola                              | 2         | 0.11%   |
| Lenovo                                | 2         | 0.11%   |
| IBM                                   | 2         | 0.11%   |
| Fujitsu Siemens Computers             | 2         | 0.11%   |
| Edimax Technology                     | 2         | 0.11%   |
| DisplayLink                           | 2         | 0.11%   |
| D-Link System                         | 2         | 0.11%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.11%   |
| ZyDAS                                 | 1         | 0.05%   |
| U-Blox                                | 1         | 0.05%   |
| Toshiba                               | 1         | 0.05%   |
| Sundance Technology Inc / IC Plus     | 1         | 0.05%   |
| Sitecom Europe                        | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 476       | 21.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 125       | 5.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 48        | 2.21%   |
| Intel I211 Gigabit Network Connection                                   | 40        | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 34        | 1.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 32        | 1.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 31        | 1.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 30        | 1.38%   |
| Intel Wireless 8265 / 8275                                              | 30        | 1.38%   |
| Intel Wi-Fi 6 AX200                                                     | 30        | 1.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 29        | 1.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 28        | 1.29%   |
| Intel Ethernet Connection I217-LM                                       | 22        | 1.01%   |
| Intel Wi-Fi 6 AX201                                                     | 21        | 0.97%   |
| Intel Wireless 7260                                                     | 20        | 0.92%   |
| Intel Wireless 3165                                                     | 20        | 0.92%   |
| Broadcom BCM43142 802.11b/g/n                                           | 20        | 0.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 19        | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                       | 18        | 0.83%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 18        | 0.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 17        | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 16        | 0.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 16        | 0.74%   |
| Intel Wireless 7265                                                     | 16        | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 14        | 0.65%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 13        | 0.6%    |
| Intel Wireless 3160                                                     | 13        | 0.6%    |
| Intel Ethernet Connection (2) I219-V                                    | 13        | 0.6%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 12        | 0.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 12        | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 12        | 0.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 0.55%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 12        | 0.55%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 12        | 0.55%   |
| Intel WiFi Link 5100                                                    | 11        | 0.51%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 10        | 0.46%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 10        | 0.46%   |
| Intel Wireless 8260                                                     | 10        | 0.46%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 10        | 0.46%   |
| Intel Ethernet Connection (2) I218-V                                    | 10        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 345       | 36.05%  |
| Realtek Semiconductor                 | 195       | 20.38%  |
| Qualcomm Atheros                      | 170       | 17.76%  |
| Broadcom                              | 68        | 7.11%   |
| TP-Link                               | 40        | 4.18%   |
| Ralink Technology                     | 35        | 3.66%   |
| Ralink                                | 25        | 2.61%   |
| MediaTek                              | 15        | 1.57%   |
| Qualcomm Atheros Communications       | 10        | 1.04%   |
| Broadcom Limited                      | 10        | 1.04%   |
| D-Link                                | 7         | 0.73%   |
| Sierra Wireless                       | 4         | 0.42%   |
| NetGear                               | 4         | 0.42%   |
| Microsoft                             | 4         | 0.42%   |
| ASUSTek Computer                      | 4         | 0.42%   |
| Belkin Components                     | 3         | 0.31%   |
| Hewlett-Packard                       | 2         | 0.21%   |
| Fujitsu Siemens Computers             | 2         | 0.21%   |
| Edimax Technology                     | 2         | 0.21%   |
| Dell                                  | 2         | 0.21%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.21%   |
| ZyDAS                                 | 1         | 0.1%    |
| Sitecom Europe                        | 1         | 0.1%    |
| Philips (or NXP)                      | 1         | 0.1%    |
| Ovislink                              | 1         | 0.1%    |
| Micro Star International              | 1         | 0.1%    |
| Linksys                               | 1         | 0.1%    |
| InProComm                             | 1         | 0.1%    |
| Accton Technology                     | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 34        | 3.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 32        | 3.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 31        | 3.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 30        | 3.12%   |
| Intel Wireless 8265 / 8275                                              | 30        | 3.12%   |
| Intel Wi-Fi 6 AX200                                                     | 30        | 3.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 29        | 3.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 28        | 2.91%   |
| Intel Wi-Fi 6 AX201                                                     | 21        | 2.18%   |
| Intel Wireless 7260                                                     | 20        | 2.08%   |
| Intel Wireless 3165                                                     | 20        | 2.08%   |
| Broadcom BCM43142 802.11b/g/n                                           | 20        | 2.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 19        | 1.98%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 18        | 1.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 16        | 1.66%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 16        | 1.66%   |
| Intel Wireless 7265                                                     | 16        | 1.66%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 13        | 1.35%   |
| Intel Wireless 3160                                                     | 13        | 1.35%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 12        | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 12        | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 1.25%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 12        | 1.25%   |
| Intel WiFi Link 5100                                                    | 11        | 1.14%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 10        | 1.04%   |
| Intel Wireless 8260                                                     | 10        | 1.04%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 10        | 1.04%   |
| Intel Centrino Wireless-N 2230                                          | 10        | 1.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 9         | 0.94%   |
| Qualcomm Atheros AR9271 802.11n                                         | 9         | 0.94%   |
| Intel Wireless-AC 9260                                                  | 9         | 0.94%   |
| Intel Ultimate N WiFi Link 5300                                         | 9         | 0.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 0.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 0.94%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 8         | 0.83%   |
| Realtek 802.11ac NIC                                                    | 8         | 0.83%   |
| Ralink MT7601U Wireless Adapter                                         | 8         | 0.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 0.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 661       | 56.88%  |
| Intel                             | 261       | 22.46%  |
| Qualcomm Atheros                  | 68        | 5.85%   |
| Broadcom                          | 50        | 4.3%    |
| Marvell Technology Group          | 43        | 3.7%    |
| Nvidia                            | 21        | 1.81%   |
| Broadcom Limited                  | 17        | 1.46%   |
| VIA Technologies                  | 7         | 0.6%    |
| Xiaomi                            | 6         | 0.52%   |
| ASIX Electronics                  | 6         | 0.52%   |
| JMicron Technology                | 3         | 0.26%   |
| TP-Link                           | 2         | 0.17%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.17%   |
| MediaTek                          | 2         | 0.17%   |
| Lenovo                            | 2         | 0.17%   |
| Huawei Technologies               | 2         | 0.17%   |
| DisplayLink                       | 2         | 0.17%   |
| D-Link System                     | 2         | 0.17%   |
| Sundance Technology Inc / IC Plus | 1         | 0.09%   |
| Qualcomm                          | 1         | 0.09%   |
| IBM                               | 1         | 0.09%   |
| Attansic Technology               | 1         | 0.09%   |
| Aquantia                          | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 476       | 40.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 125       | 10.6%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 48        | 4.07%   |
| Intel I211 Gigabit Network Connection                             | 40        | 3.39%   |
| Intel Ethernet Connection I217-LM                                 | 22        | 1.87%   |
| Realtek RTL8125 2.5GbE Controller                                 | 18        | 1.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 17        | 1.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14        | 1.19%   |
| Intel Ethernet Connection (2) I219-V                              | 13        | 1.1%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12        | 1.02%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 12        | 1.02%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 10        | 0.85%   |
| Intel Ethernet Connection (2) I218-V                              | 10        | 0.85%   |
| Intel Ethernet Controller I225-V                                  | 9         | 0.76%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 8         | 0.68%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 8         | 0.68%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 8         | 0.68%   |
| Intel Ethernet Connection I217-V                                  | 8         | 0.68%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 8         | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 0.59%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 7         | 0.59%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6         | 0.51%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 6         | 0.51%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 6         | 0.51%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 6         | 0.51%   |
| Intel 82567LM Gigabit Network Connection                          | 6         | 0.51%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 6         | 0.51%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 6         | 0.51%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 0.42%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 5         | 0.42%   |
| Nvidia MCP61 Ethernet                                             | 5         | 0.42%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.42%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 0.42%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 0.42%   |
| Intel Ethernet Connection (10) I219-V                             | 5         | 0.42%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.42%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 0.42%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 4         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1123      | 55%     |
| WiFi     | 892       | 43.68%  |
| Modem    | 26        | 1.27%   |
| Unknown  | 1         | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 702       | 53.92%  |
| Ethernet | 600       | 46.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 650       | 51.38%  |
| 1     | 565       | 44.66%  |
| 0     | 27        | 2.13%   |
| 3     | 19        | 1.5%    |
| 4     | 4         | 0.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 962       | 74%     |
| Yes  | 338       | 26%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 235       | 35.61%  |
| Realtek Semiconductor           | 89        | 13.48%  |
| Qualcomm Atheros Communications | 69        | 10.45%  |
| Cambridge Silicon Radio         | 53        | 8.03%   |
| Broadcom                        | 38        | 5.76%   |
| Foxconn / Hon Hai               | 28        | 4.24%   |
| IMC Networks                    | 25        | 3.79%   |
| Hewlett-Packard                 | 18        | 2.73%   |
| Toshiba                         | 16        | 2.42%   |
| Lite-On Technology              | 14        | 2.12%   |
| Apple                           | 14        | 2.12%   |
| Ralink                          | 8         | 1.21%   |
| Realtek                         | 7         | 1.06%   |
| ASUSTek Computer                | 7         | 1.06%   |
| Alps Electric                   | 7         | 1.06%   |
| Foxconn International           | 6         | 0.91%   |
| Dell                            | 6         | 0.91%   |
| Ralink Technology               | 4         | 0.61%   |
| Askey Computer                  | 4         | 0.61%   |
| Mobile Action Technology        | 2         | 0.3%    |
| Micro Star International        | 2         | 0.3%    |
| Chicony Electronics             | 2         | 0.3%    |
| Syntek                          | 1         | 0.15%   |
| ISSC                            | 1         | 0.15%   |
| Integrated System Solution      | 1         | 0.15%   |
| Edimax Technology               | 1         | 0.15%   |
| Belkin Components               | 1         | 0.15%   |
| Actions                         | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 102       | 15.45%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 53        | 8.03%   |
| Realtek Bluetooth Radio                             | 46        | 6.97%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 33        | 5%      |
| Intel AX201 Bluetooth                               | 33        | 5%      |
| Qualcomm Atheros  Bluetooth Device                  | 29        | 4.39%   |
| Intel AX200 Bluetooth                               | 28        | 4.24%   |
| Realtek  Bluetooth 4.2 Adapter                      | 22        | 3.33%   |
| Realtek RTL8723B Bluetooth                          | 11        | 1.67%   |
| IMC Networks Bluetooth Radio                        | 11        | 1.67%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 10        | 1.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 10        | 1.52%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 9         | 1.36%   |
| Intel Wireless-AC 3168 Bluetooth                    | 9         | 1.36%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 9         | 1.36%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 9         | 1.36%   |
| Ralink RT3290 Bluetooth                             | 8         | 1.21%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 8         | 1.21%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 8         | 1.21%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 1.21%   |
| Realtek 802.11ac WLAN Adapter                       | 7         | 1.06%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 6         | 0.91%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 6         | 0.91%   |
| Intel Bluetooth Device                              | 6         | 0.91%   |
| Foxconn International BCM43142A0 Bluetooth module   | 6         | 0.91%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 6         | 0.91%   |
| Toshiba RT Bluetooth Radio                          | 5         | 0.76%   |
| Toshiba Bluetooth Device                            | 5         | 0.76%   |
| Qualcomm Atheros Bluetooth                          | 5         | 0.76%   |
| IMC Networks Bluetooth Device                       | 5         | 0.76%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 0.76%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 5         | 0.76%   |
| Apple Bluetooth Host Controller                     | 5         | 0.76%   |
| Lite-On Bluetooth Device                            | 4         | 0.61%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 0.61%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 0.61%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.61%   |
| Askey Bluetooth Device                              | 4         | 0.61%   |
| Apple Bluetooth USB Host Controller                 | 4         | 0.61%   |
| Realtek RTL8723A Bluetooth                          | 3         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 854       | 50.21%  |
| AMD                              | 419       | 24.63%  |
| Nvidia                           | 268       | 15.76%  |
| C-Media Electronics              | 29        | 1.7%    |
| Creative Labs                    | 14        | 0.82%   |
| Logitech                         | 10        | 0.59%   |
| Creative Technology              | 10        | 0.59%   |
| Razer USA                        | 8         | 0.47%   |
| VIA Technologies                 | 6         | 0.35%   |
| Barco Display Systems            | 6         | 0.35%   |
| Kingston Technology              | 5         | 0.29%   |
| Texas Instruments                | 4         | 0.24%   |
| Focusrite-Novation               | 4         | 0.24%   |
| BEHRINGER International          | 4         | 0.24%   |
| Lenovo                           | 3         | 0.18%   |
| GN Netcom                        | 3         | 0.18%   |
| Yamaha                           | 2         | 0.12%   |
| Trust                            | 2         | 0.12%   |
| Silicon Integrated Systems [SiS] | 2         | 0.12%   |
| Plantronics                      | 2         | 0.12%   |
| Nordic Semiconductor ASA         | 2         | 0.12%   |
| Native Instruments               | 2         | 0.12%   |
| Hewlett-Packard                  | 2         | 0.12%   |
| Guillemot                        | 2         | 0.12%   |
| Generalplus Technology           | 2         | 0.12%   |
| Ensoniq                          | 2         | 0.12%   |
| Edifier Technology               | 2         | 0.12%   |
| Dell                             | 2         | 0.12%   |
| Cooler Master                    | 2         | 0.12%   |
| AudioQuest                       | 2         | 0.12%   |
| ASUSTek Computer                 | 2         | 0.12%   |
| Altec Lansing Technologies       | 2         | 0.12%   |
| Tenx Technology                  | 1         | 0.06%   |
| SteelSeries ApS                  | 1         | 0.06%   |
| Shenzhen Riitek Technology       | 1         | 0.06%   |
| Scarlett                         | 1         | 0.06%   |
| RODE Microphones                 | 1         | 0.06%   |
| Realtek Semiconductor            | 1         | 0.06%   |
| Numark                           | 1         | 0.06%   |
| Mark of the Unicorn              | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 122       | 5.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 83        | 4.01%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 74        | 3.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 71        | 3.43%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 67        | 3.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 66        | 3.19%   |
| Intel Sunrise Point-LP HD Audio                                            | 62        | 3%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 59        | 2.85%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 59        | 2.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 56        | 2.71%   |
| AMD FCH Azalia Controller                                                  | 46        | 2.22%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 45        | 2.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 44        | 2.13%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 38        | 1.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 38        | 1.84%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 37        | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 36        | 1.74%   |
| Intel Haswell-ULT HD Audio Controller                                      | 32        | 1.55%   |
| Intel 8 Series HD Audio Controller                                         | 32        | 1.55%   |
| AMD Starship/Matisse HD Audio Controller                                   | 31        | 1.5%    |
| Nvidia GP107GL High Definition Audio Controller                            | 29        | 1.4%    |
| Intel Cannon Lake PCH cAVS                                                 | 28        | 1.35%   |
| Nvidia High Definition Audio Controller                                    | 23        | 1.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 23        | 1.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 22        | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                              | 21        | 1.01%   |
| AMD Kabini HDMI/DP Audio                                                   | 21        | 1.01%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 20        | 0.97%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 20        | 0.97%   |
| Intel Broadwell-U Audio Controller                                         | 19        | 0.92%   |
| Intel 200 Series PCH HD Audio                                              | 19        | 0.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 18        | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 18        | 0.87%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 18        | 0.87%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 16        | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 14        | 0.68%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 14        | 0.68%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 14        | 0.68%   |
| Nvidia GT216 HDMI Audio Controller                                         | 13        | 0.63%   |
| Nvidia GP106 High Definition Audio Controller                              | 13        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 129       | 19.28%  |
| SK hynix            | 111       | 16.59%  |
| Unknown             | 96        | 14.35%  |
| Kingston            | 81        | 12.11%  |
| Micron Technology   | 55        | 8.22%   |
| Corsair             | 44        | 6.58%   |
| G.Skill             | 42        | 6.28%   |
| Crucial             | 34        | 5.08%   |
| Ramaxel Technology  | 12        | 1.79%   |
| Elpida              | 11        | 1.64%   |
| Transcend           | 9         | 1.35%   |
| Team                | 8         | 1.2%    |
| Nanya Technology    | 5         | 0.75%   |
| A-DATA Technology   | 5         | 0.75%   |
| Unknown (ABCD)      | 4         | 0.6%    |
| Unknown             | 4         | 0.6%    |
| Patriot             | 3         | 0.45%   |
| Goodram             | 3         | 0.45%   |
| Apacer              | 3         | 0.45%   |
| Veineda             | 1         | 0.15%   |
| Toshiba             | 1         | 0.15%   |
| Silicon Power       | 1         | 0.15%   |
| Qimonda             | 1         | 0.15%   |
| Infineon            | 1         | 0.15%   |
| HMD                 | 1         | 0.15%   |
| H                   | 1         | 0.15%   |
| Goldkey             | 1         | 0.15%   |
| GeIL                | 1         | 0.15%   |
| Avant               | 1         | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 1.36%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 10        | 1.36%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 1.22%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 1.09%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 1.09%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 7         | 0.95%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 5         | 0.68%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 0.68%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 5         | 0.68%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 5         | 0.68%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.68%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.68%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.68%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 4         | 0.54%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 4         | 0.54%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 4         | 0.54%   |
| Unknown RAM Module 2048MB DIMM DDR 533MT/s                       | 4         | 0.54%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.54%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.54%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.54%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.54%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.54%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.54%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.54%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 0.54%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.54%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 4         | 0.54%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 4         | 0.54%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s              | 4         | 0.54%   |
| Unknown                                                          | 4         | 0.54%   |
| Unknown RAM Module 512MB DIMM SDRAM                              | 3         | 0.41%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 3         | 0.41%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 3         | 0.41%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 3         | 0.41%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                      | 3         | 0.41%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                           | 3         | 0.41%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.41%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 3         | 0.41%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.41%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 236       | 40.62%  |
| DDR3    | 194       | 33.39%  |
| DDR2    | 44        | 7.57%   |
| Unknown | 34        | 5.85%   |
| SDRAM   | 24        | 4.13%   |
| DDR     | 15        | 2.58%   |
| LPDDR4  | 14        | 2.41%   |
| DDR5    | 9         | 1.55%   |
| LPDDR3  | 6         | 1.03%   |
| DRAM    | 3         | 0.52%   |
| LPDDR5  | 2         | 0.34%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 305       | 53.04%  |
| DIMM         | 238       | 41.39%  |
| Row Of Chips | 30        | 5.22%   |
| Chip         | 1         | 0.17%   |
| Unknown      | 1         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 227       | 35.64%  |
| 4096  | 182       | 28.57%  |
| 2048  | 113       | 17.74%  |
| 16384 | 59        | 9.26%   |
| 1024  | 41        | 6.44%   |
| 512   | 9         | 1.41%   |
| 32768 | 5         | 0.78%   |
| 256   | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 127       | 20.06%  |
| 3200    | 76        | 12.01%  |
| 2667    | 74        | 11.69%  |
| 2400    | 42        | 6.64%   |
| 1333    | 40        | 6.32%   |
| Unknown | 28        | 4.42%   |
| 667     | 25        | 3.95%   |
| 800     | 23        | 3.63%   |
| 2133    | 21        | 3.32%   |
| 1334    | 18        | 2.84%   |
| 3600    | 17        | 2.69%   |
| 1066    | 11        | 1.74%   |
| 3866    | 10        | 1.58%   |
| 533     | 10        | 1.58%   |
| 3266    | 9         | 1.42%   |
| 2933    | 9         | 1.42%   |
| 1067    | 8         | 1.26%   |
| 3000    | 7         | 1.11%   |
| 1800    | 6         | 0.95%   |
| 4800    | 5         | 0.79%   |
| 4267    | 5         | 0.79%   |
| 3400    | 5         | 0.79%   |
| 1867    | 5         | 0.79%   |
| 1866    | 5         | 0.79%   |
| 400     | 5         | 0.79%   |
| 3733    | 4         | 0.63%   |
| 6400    | 3         | 0.47%   |
| 4199    | 3         | 0.47%   |
| 2048    | 3         | 0.47%   |
| 333     | 3         | 0.47%   |
| 4266    | 2         | 0.32%   |
| 3007    | 2         | 0.32%   |
| 2800    | 2         | 0.32%   |
| 2733    | 2         | 0.32%   |
| 49926   | 1         | 0.16%   |
| 12800   | 1         | 0.16%   |
| 6000    | 1         | 0.16%   |
| 5808    | 1         | 0.16%   |
| 4802    | 1         | 0.16%   |
| 4000    | 1         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 31        | 55.36%  |
| Canon                 | 9         | 16.07%  |
| Samsung Electronics   | 8         | 14.29%  |
| Seiko Epson           | 2         | 3.57%   |
| Ricoh                 | 1         | 1.79%   |
| QinHeng Electronics   | 1         | 1.79%   |
| Oki Data              | 1         | 1.79%   |
| Lexmark International | 1         | 1.79%   |
| Konica Minolta        | 1         | 1.79%   |
| Brother Industries    | 1         | 1.79%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung M2020 Series                 | 6         | 10.71%  |
| HP DeskJet 3830 series               | 3         | 5.36%   |
| Canon TS3100 series                  | 3         | 5.36%   |
| Seiko Epson L310 Series              | 2         | 3.57%   |
| HP LaserJet P1102                    | 2         | 3.57%   |
| HP DeskJet 2620 All-in-One Printer   | 2         | 3.57%   |
| Samsung SCX-3400 Series              | 1         | 1.79%   |
| Samsung M2070 Series                 | 1         | 1.79%   |
| Ricoh SP 112SU                       | 1         | 1.79%   |
| QinHeng CH340S                       | 1         | 1.79%   |
| Oki Data USB Device                  | 1         | 1.79%   |
| Lexmark International E350d          | 1         | 1.79%   |
| Konica Minolta magicolor 1680MF scan | 1         | 1.79%   |
| HP Smart Tank 510 series             | 1         | 1.79%   |
| HP Officejet Pro L7400               | 1         | 1.79%   |
| HP OfficeJet Pro 8020 series         | 1         | 1.79%   |
| HP Officejet J4500 series            | 1         | 1.79%   |
| HP OfficeJet 6200                    | 1         | 1.79%   |
| HP Officejet 4500 G510g-m            | 1         | 1.79%   |
| HP LaserJet P1005                    | 1         | 1.79%   |
| HP LaserJet 1020                     | 1         | 1.79%   |
| HP LaserJet 1018                     | 1         | 1.79%   |
| HP LaserJet 1010                     | 1         | 1.79%   |
| HP Laser 107w                        | 1         | 1.79%   |
| HP DeskJet F300 series               | 1         | 1.79%   |
| HP DeskJet F2492 All-in-One          | 1         | 1.79%   |
| HP DeskJet D2300                     | 1         | 1.79%   |
| HP DeskJet 930c                      | 1         | 1.79%   |
| HP DeskJet 840c                      | 1         | 1.79%   |
| HP DeskJet 4670 series               | 1         | 1.79%   |
| HP DeskJet 4530 series               | 1         | 1.79%   |
| HP DeskJet 4100 series               | 1         | 1.79%   |
| HP DeskJet 3700 series               | 1         | 1.79%   |
| HP Deskjet 2640 series               | 1         | 1.79%   |
| HP Deskjet 2510 series               | 1         | 1.79%   |
| HP DeskJet 2300 series               | 1         | 1.79%   |
| HP Color Laser 150nw                 | 1         | 1.79%   |
| Canon TR4500 series                  | 1         | 1.79%   |
| Canon PIXMA MX390 Series             | 1         | 1.79%   |
| Canon PIXMA MX320 series             | 1         | 1.79%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 3         | 42.86%  |
| Hewlett-Packard | 2         | 28.57%  |
| Seiko Epson     | 1         | 14.29%  |
| Mustek Systems  | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X800 [Perfection 4990 PHOTO] | 1         | 14.29%  |
| Mustek Systems BearPaw 1200 CU Plus         | 1         | 14.29%  |
| HP Scanjet G2710                            | 1         | 14.29%  |
| HP ScanJet 4370                             | 1         | 14.29%  |
| Canon CanoScan LiDE 220                     | 1         | 14.29%  |
| Canon CanoScan LiDE 110                     | 1         | 14.29%  |
| Canon CanoScan LiDE 100                     | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 139       | 18.66%  |
| Microdia                               | 72        | 9.66%   |
| IMC Networks                           | 68        | 9.13%   |
| Realtek Semiconductor                  | 60        | 8.05%   |
| Logitech                               | 47        | 6.31%   |
| Suyin                                  | 37        | 4.97%   |
| Bison Electronics                      | 36        | 4.83%   |
| Sunplus Innovation Technology          | 32        | 4.3%    |
| Cheng Uei Precision Industry (Foxlink) | 29        | 3.89%   |
| Quanta                                 | 21        | 2.82%   |
| Syntek                                 | 19        | 2.55%   |
| Acer                                   | 19        | 2.55%   |
| Microsoft                              | 18        | 2.42%   |
| Lite-On Technology                     | 17        | 2.28%   |
| Ricoh                                  | 16        | 2.15%   |
| Alcor Micro                            | 16        | 2.15%   |
| Apple                                  | 11        | 1.48%   |
| Generalplus Technology                 | 10        | 1.34%   |
| Z-Star Microelectronics                | 7         | 0.94%   |
| Silicon Motion                         | 7         | 0.94%   |
| Luxvisions Innotech Limited            | 7         | 0.94%   |
| Creative Technology                    | 6         | 0.81%   |
| Arkmicro Technologies                  | 5         | 0.67%   |
| Samsung Electronics                    | 4         | 0.54%   |
| Philips (or NXP)                       | 4         | 0.54%   |
| Lenovo                                 | 4         | 0.54%   |
| Aveo Technology                        | 4         | 0.54%   |
| Genesys Logic                          | 3         | 0.4%    |
| Sonix Technology                       | 2         | 0.27%   |
| Razer USA                              | 2         | 0.27%   |
| Pixart Imaging                         | 2         | 0.27%   |
| Jieli Technology                       | 2         | 0.27%   |
| Importek                               | 2         | 0.27%   |
| ALi                                    | 2         | 0.27%   |
| Xiongmai                               | 1         | 0.13%   |
| Trust                                  | 1         | 0.13%   |
| Tripath Technology                     | 1         | 0.13%   |
| Sweex                                  | 1         | 0.13%   |
| Primax Electronics                     | 1         | 0.13%   |
| OmniVision Technologies                | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 26        | 3.48%   |
| Microdia Integrated_Webcam_HD                                   | 25        | 3.34%   |
| Realtek Integrated_Webcam_HD                                    | 23        | 3.07%   |
| IMC Networks Integrated Camera                                  | 18        | 2.41%   |
| Logitech Webcam C270                                            | 17        | 2.27%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 16        | 2.14%   |
| Chicony HP Truevision HD                                        | 12        | 1.6%    |
| Syntek Integrated Camera                                        | 11        | 1.47%   |
| Sunplus Integrated_Webcam_HD                                    | 11        | 1.47%   |
| Realtek Lenovo EasyCamera                                       | 8         | 1.07%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 8         | 1.07%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                | 8         | 1.07%   |
| Bison Lenovo EasyCamera                                         | 8         | 1.07%   |
| Chicony TOSHIBA Web Camera - HD                                 | 7         | 0.94%   |
| Chicony HP Webcam                                               | 7         | 0.94%   |
| Suyin Integrated_Webcam_HD                                      | 6         | 0.8%    |
| Realtek 2SF022                                                  | 6         | 0.8%    |
| Microsoft LifeCam HD-3000                                       | 6         | 0.8%    |
| Chicony USB 2.0 Camera                                          | 6         | 0.8%    |
| Chicony HD WebCam                                               | 6         | 0.8%    |
| Bison SunplusIT Integrated Camera                               | 6         | 0.8%    |
| Acer BisonCam, NB Pro                                           | 6         | 0.8%    |
| Realtek Integrated Webcam                                       | 5         | 0.67%   |
| Quanta VGA WebCam                                               | 5         | 0.67%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 5         | 0.67%   |
| Microdia Integrated_Webcam_FHD                                  | 5         | 0.67%   |
| Microdia Camera                                                 | 5         | 0.67%   |
| Logitech HD Pro Webcam C920                                     | 5         | 0.67%   |
| IMC Networks Lenovo EasyCamera                                  | 5         | 0.67%   |
| Generalplus GENERAL WEBCAM                                      | 5         | 0.67%   |
| Generalplus 808 Camera #9 (web-cam mode)                        | 5         | 0.67%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 5         | 0.67%   |
| Chicony Integrated Camera (1280x720@30)                         | 5         | 0.67%   |
| Chicony HP HD Webcam                                            | 5         | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 5         | 0.67%   |
| Alcor Micro USB 2.0 Camera                                      | 5         | 0.67%   |
| Alcor Micro HP Webcam-101                                       | 5         | 0.67%   |
| Acer Integrated Camera                                          | 5         | 0.67%   |
| Z-Star Venus USB2.0 Camera                                      | 4         | 0.53%   |
| Syntek Lenovo EasyCamera                                        | 4         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 33        | 32.35%  |
| Synaptics                  | 23        | 22.55%  |
| Shenzhen Goodix Technology | 15        | 14.71%  |
| AuthenTec                  | 13        | 12.75%  |
| Upek                       | 11        | 10.78%  |
| Elan Microelectronics      | 5         | 4.9%    |
| STMicroelectronics         | 1         | 0.98%   |
| LighTuning Technology      | 1         | 0.98%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 11        | 10.78%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 9.8%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 9         | 8.82%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 6.86%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 5.88%   |
| Synaptics  WBDI                                                            | 5         | 4.9%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 4.9%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 4.9%    |
| Synaptics WBDI                                                             | 4         | 3.92%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 3.92%   |
| Elan ELAN:ARM-M4                                                           | 4         | 3.92%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 2.94%   |
| AuthenTec AES2810                                                          | 3         | 2.94%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.96%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 1.96%   |
| Validity Sensors VFS491                                                    | 2         | 1.96%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.96%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.96%   |
| Synaptics UWP WBDI                                                         | 2         | 1.96%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.96%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 1.96%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.98%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.98%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 0.98%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.98%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.98%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.98%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.98%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.98%   |
| Elan ELAN:Fingerprint                                                      | 1         | 0.98%   |
| AuthenTec AES1600                                                          | 1         | 0.98%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 31        | 60.78%  |
| Alcor Micro | 10        | 19.61%  |
| O2 Micro    | 5         | 9.8%    |
| Upek        | 2         | 3.92%   |
| Lenovo      | 2         | 3.92%   |
| Yubico.com  | 1         | 1.96%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 16        | 31.37%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 19.61%  |
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 17.65%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 9.8%    |
| Broadcom 5880                                                                | 4         | 7.84%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.92%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 3.92%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 3.92%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 1.96%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 934       | 72.18%  |
| 1     | 291       | 22.49%  |
| 2     | 55        | 4.25%   |
| 3     | 9         | 0.7%    |
| 4     | 3         | 0.23%   |
| 7     | 1         | 0.08%   |
| 6     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 102       | 23.83%  |
| Graphics card            | 92        | 21.5%   |
| Net/wireless             | 65        | 15.19%  |
| Chipcard                 | 47        | 10.98%  |
| Multimedia controller    | 29        | 6.78%   |
| Bluetooth                | 19        | 4.44%   |
| Communication controller | 15        | 3.5%    |
| Camera                   | 11        | 2.57%   |
| Sound                    | 10        | 2.34%   |
| Modem                    | 7         | 1.64%   |
| Storage                  | 5         | 1.17%   |
| Dvb card                 | 5         | 1.17%   |
| Network                  | 4         | 0.93%   |
| Flash memory             | 4         | 0.93%   |
| Card reader              | 4         | 0.93%   |
| Net/ethernet             | 3         | 0.7%    |
| Unassigned class         | 2         | 0.47%   |
| Firewire controller      | 2         | 0.47%   |
| Tv card                  | 1         | 0.23%   |
| Storage/raid             | 1         | 0.23%   |

